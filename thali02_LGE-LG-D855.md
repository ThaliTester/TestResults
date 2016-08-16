#### Test 80761374bf0e3f7_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-16 13:43:09.216  2175  2175 I ConfigService: onDestroy
,08-16 13:43:35.357  6921  6921 D AndroidRuntime: 
08-16 13:43:35.357  6921  6921 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-16 13:43:35.364  6921  6921 D AndroidRuntime: CheckJNI is OFF
08-16 13:43:35.566  6921  6921 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-16 13:43:35.577  1036  1885 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-16 13:43:35.593  1941  1957 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-16 13:43:35.600  1036  1885 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-16 13:43:35.601  1036  1885 D ActivityManager: setTaskToReturnTo : TaskRecord{e1f4004 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-16 13:43:35.602  1036  1885 D ActivityManager: setTaskToReturnTo : TaskRecord{e1f4004 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-16 13:43:35.603  1036  1885 D WindowStateEx: AppWindowTokenEx init.. 
08-16 13:43:35.604   332   348 E GBMv2   : DFP En is all cleared set to be enabled
08-16 13:43:35.633  1036  1885 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6936 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-16 13:43:35.636  6921  6921 D AndroidRuntime: Shutting down VM
08-16 13:43:35.690  1941  4406 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-16 13:43:35.690  1941  4406 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3a131305 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-16 13:43:35.691  1941  1956 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-16 13:43:35.691  1941  1956 D SplitWindowPolicy: topRunningActivity=ActivityInfo{4c8cf5a co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-16 13:43:35.740  6936  6936 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-16 13:43:35.815  6936  6936 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
08-16 13:43:35.837  6936  6936 I LibraryLoader: Loading: webviewchromium
,08-16 13:43:35.851  6936  6936 I LibraryLoader: Time to load native libraries: 16 ms (timestamps 2516-2532)
08-16 13:43:35.852  6936  6936 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 13:43:35.868  6936  6936 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {166647fb}
,08-16 13:43:35.869  6936  6936 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 13:43:35.870  6936  6936 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-16 13:43:35.884  6936  6936 I BrowserStartupController: Initializing chromium process, renderers=0
08-16 13:43:35.885  6936  6936 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-16 13:43:35.896  6936  6936 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-16 13:43:35.897  6936  6936 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-16 13:43:35.897  6936  6936 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-16 13:43:35.898   312  2155 V AudioPolicyService: registerClient() client 0xb557c520, uid 10118
08-16 13:43:35.901  1036  1107 D BluetoothManagerService: Message: 20
08-16 13:43:35.901  1036  1107 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2cb5bc6e:true
,08-16 13:43:35.915  6936  6936 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 13:43:35.915  6936  6936 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 13:43:35.915  6936  6936 I Adreno-EGL: Build Date: 12/12/14 금
08-16 13:43:35.915  6936  6936 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 13:43:35.915  6936  6936 I Adreno-EGL: Remote Branch: 
08-16 13:43:35.915  6936  6936 I Adreno-EGL: Local Patches: 
08-16 13:43:35.915  6936  6936 I Adreno-EGL: Reconstruct Branch: 
,08-16 13:43:35.978  6936  6971 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
08-16 13:43:35.980  6936  6936 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,08-16 13:43:35.996  6936  6936 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-16 13:43:36.002  6936  6936 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-16 13:43:36.005  6936  6936 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-16 13:43:36.007  6936  6936 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-16 13:43:36.007  6936  6936 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-16 13:43:36.019  6936  6936 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-16 13:43:36.026  6936  6936 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-16 13:43:36.026  6936  6936 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-16 13:43:36.060  6936  6983 D OpenGLRenderer: Render dirty regions requested: true
08-16 13:43:36.060  6936  6983 I OpenGLRenderer: Initialized EGL, version 1.4
08-16 13:43:36.065  6936  6983 D OpenGLRenderer: Enabling debug mode 0
08-16 13:43:36.073  6936  6936 D Atlas   : Validating map...
,08-16 13:43:36.078  1036  1994 D SplitWindow: check instance of lgWin Window{22a8a0b8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-16 13:43:36.131  6936  6981 D LgDataFeature: LgDataFeature() Constructor: none
,08-16 13:43:36.132  6936  6981 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 13:43:36.185  1036  1109 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +496ms (total +579ms)
08-16 13:43:36.186  1036  1109 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{fe7a9ed u0 com.test.thalitest/.MainActivity t6} time:312866
,08-16 13:43:36.190  6936  6936 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@16cf8b06 time:312870
08-16 13:43:36.349  6936  6936 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-16 13:43:36.499  6936  6994 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435182080
,08-16 13:43:36.512  6936  6994 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-16 13:43:36.512  6936  6994 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-16 13:43:36.512  6936  6994 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-16 13:43:36.512  6936  6994 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-16 13:43:36.512  6936  6994 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-16 13:43:36.513  6936  6994 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13a980ea added. We now have 1 listener(s)
,08-16 13:43:36.519  1036  2032 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 13:43:36.523  6936  6994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-16 13:43:36.525  6936  6994 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 13:43:36.526  6936  6994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 13:43:36.527  6936  6994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-16 13:43:36.535  6936  6994 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-16 13:43:36.535  6936  6994 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-16 13:43:36.535  6936  6994 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-16 13:43:36.535  6936  6994 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-16 13:43:36.535  6936  6994 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-16 13:43:36.535  6936  6994 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-16 13:43:36.535  6936  6994 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-16 13:43:36.535  6936  6994 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-16 13:43:36.535  6936  6994 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-16 13:43:36.535  6936  6994 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-16 13:43:36.535  6936  6994 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-16 13:43:36.535  6936  6994 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-16 13:43:36.535  6936  6994 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-16 13:43:36.535  6936  6994 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-16 13:43:36.535  6936  6994 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3aca2551 added. We now have 1 listener(s)
08-16 13:43:36.536  6936  6994 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 13:43:36.543  1036  1543 D WifiService: New client listening to asynchronous messages
08-16 13:43:36.547  6936  6994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 13:43:36.547  6936  6994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-16 13:43:36.549  6936  6994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-16 13:43:36.549  6936  6994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-16 13:43:36.549  6936  6994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-16 13:43:36.552  6936  6994 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 13:43:36.554  1036  1958 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 13:43:36.556  6936  6994 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-16 13:43:36.569  6936  6994 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-16 13:43:36.570  6936  6994 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 13:43:36.570  6936  6994 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:43:36.570  6936  6994 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 13:43:36.570  6936  6994 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:43:36.570  6936  6994 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 13:43:36.570  6936  6994 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 13:43:36.570  6936  6994 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 13:43:36.570  6936  6994 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 13:43:36.570  6936  6994 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-16 13:43:36.570  6936  6994 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 13:43:36.573  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:43:36.575  6936  6994 I io.jxcore.node.LifeCycleMonitor: start: OK
08-16 13:43:36.575  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:43:36.610  6936  6981 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-16 13:43:36.610  6936  6981 I chromium: 
,08-16 13:43:36.665  6936  6936 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-16 13:43:36.760  6936  6936 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-16 13:43:36.760  6936  6936 I chromium: 
,08-16 13:43:37.181   332   350 E GBMv2   : DFP En is all cleared set to be enabled
08-16 13:43:37.181   332   350 E GBMv2   : Set value is all cleared set the max
08-16 13:43:37.181   332   350 I GBMv2   : DFP Enabled. Ignore VFP set
,08-16 13:43:37.978  6936  6997 W jxcore-log: Initializing JXcore engine
08-16 13:43:37.978  6936  6997 W jxcore-log: JXcore engine is ready
,08-16 13:43:38.043  6997  6997 W Thread-812: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[10284]" dev="sockfs" ino=10284 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-16 13:43:38.043  6997  6997 W Thread-812: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-16 13:43:38.043  6997  6997 W Thread-812: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[10460]" dev="sockfs" ino=10460 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-16 13:43:38.043  6997  6997 W Thread-812: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-16 13:43:38.043  6997  6997 W Thread-812: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[33593]" dev="sockfs" ino=33593 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-16 13:43:38.079  6936  6997 W jxcore-log: Starting JXcore engine
,08-16 13:43:38.244  6936  6997 W jxcore-log: Platform android
08-16 13:43:38.244  6936  6997 W jxcore-log: 
08-16 13:43:38.244  6936  6997 W jxcore-log: Process ARCH arm
08-16 13:43:38.244  6936  6997 W jxcore-log: 
,08-16 13:43:38.586  6936  6997 I jxcore-log: JXcore Cordova bridge is ready!
08-16 13:43:38.586  6936  6997 I jxcore-log: 
08-16 13:43:38.586  6936  6997 W jxcore-log: JXcore engine is started
,08-16 13:43:38.613  6936  6994 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-16 13:43:38.625  6936  6936 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-16 13:43:57.990  1036  3471 I LocationManagerService: remove 3c9b1773
08-16 13:43:57.990  1036  3471 D LocationManagerService: provider request: passive ProviderRequest[ON interval=0]
,08-16 13:43:57.991  1036  3471 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 13:43:57.991  1036  3471 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
08-16 13:43:57.992  1036  3471 D LocationManagerService: getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
08-16 13:43:57.992  1036  3471 D LocationManagerService: getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,08-16 13:44:00.071  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-16 13:44:00.071  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
08-16 13:44:00.072  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-16 13:44:00.072  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
08-16 13:44:00.075  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
08-16 13:44:00.076  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
08-16 13:44:00.077  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
08-16 13:44:00.078  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
,08-16 13:44:03.882  6936  6997 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-16 13:44:03.882  6936  6997 I jxcore-log: 
,08-16 13:44:03.885  6936  6997 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-16 13:44:03.885  6936  6997 I jxcore-log: 
08-16 13:44:03.890  6936  6997 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 13:44:03.890  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:44:03.890  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 13:44:03.890  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:44:03.890  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 13:44:03.890  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 13:44:03.890  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 13:44:03.890  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 13:44:03.893  6936  6997 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 13:44:03.896  6936  6997 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-16 13:44:03.896  6936  6997 I jxcore-log: 
08-16 13:44:03.897  6936  6997 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-16 13:44:03.897  6936  6997 I jxcore-log: 
,08-16 13:44:04.232  6936  6997 I jxcore-log: Running unit tests
08-16 13:44:04.232  6936  6997 I jxcore-log: 
08-16 13:44:04.233  6936  6997 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 13:44:04.233  6936  6997 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16595bb4 added. We now have 2 listener(s)
08-16 13:44:04.233  1036  1940 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-16 13:44:04.235  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 13:44:04.235  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 13:44:04.235  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 13:44:04.235  6936  6997 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 13:44:04.235  6936  6997 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f3513dd added. We now have 2 listener(s)
08-16 13:44:04.235  6936  6997 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 13:44:04.236  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 13:44:04.239  6936  6997 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 13:44:04.242  6936  6997 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 13:44:04.242  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:44:04.242  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 13:44:04.242  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:44:04.242  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 13:44:04.242  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 13:44:04.242  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 13:44:04.242  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 13:44:04.243  6936  6997 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 13:44:04.243  6936  6997 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 13:44:04.245  6936  6997 D ExecuteNativeTests: Running unit tests
08-16 13:44:04.245  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:44:04.255  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:44:09.330  6936  6997 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 13:44:09.331  6936  6997 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3356e613 added. We now have 3 listener(s)
,08-16 13:44:09.337  1036  1995 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 13:44:09.346  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 13:44:09.346  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 13:44:09.346  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 13:44:09.346  6936  6997 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 13:44:09.347  6936  6997 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1bcbf050 added. We now have 3 listener(s)
08-16 13:44:09.347  6936  6997 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 13:44:09.352  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 13:44:09.356  6936  6997 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 13:44:09.360  6936  6997 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 13:44:09.360  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:44:09.360  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 13:44:09.360  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:44:09.360  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 13:44:09.360  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 13:44:09.360  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 13:44:09.360  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 13:44:09.362  6936  6997 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 13:44:09.362  6936  6997 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 13:44:09.366  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:44:09.368  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:44:09.373  6936  6997 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-16 13:44:09.376  6936  6997 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 13:44:09.376  6936  6997 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-16 13:44:09.380  6936  6997 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 13:44:09.384  6936  6997 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-16 13:44:09.385  6936  6997 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-16 13:44:09.386  6936  6997 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 13:44:09.388  6936  6997 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 13:44:09.388  6936  6997 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 13:44:09.388  6936  6997 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 13:44:09.392  6936  6997 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 13:44:09.392  6936  6997 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 13:44:09.393  6936  6997 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 13:44:09.395  6936  6997 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:44:09.395  6936  6997 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:44:09.395  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 13:44:09.396  6936  6997 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 13:44:09.396  6936  6997 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3356e613 removed from the list
08-16 13:44:09.396  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:44:09.396  6936  6997 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1bcbf050 removed from the list
08-16 13:44:09.396  6936  6997 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:44:09.396  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:44:09.397  6936  6997 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:44:09.397  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:44:09.398  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:44:09.398  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:44:09.398  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:44:09.398  6936  6997 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1bcbf050 not in the list
08-16 13:44:09.401  6936  6997 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-16 13:44:09.401  6936  6997 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 13:44:09.401  6936  6997 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 13:44:09.401  6936  6997 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 13:44:09.402  6936  6997 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:44:09.403  6936  6997 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:44:09.403  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:44:09.403  6936  6997 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3356e613 not in the list
08-16 13:44:09.403  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:44:09.403  6936  6997 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1bcbf050 not in the list
08-16 13:44:09.403  6936  6997 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:44:09.403  6936  6997 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:44:09.403  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08,-16 13:44:09.403  6936  6997 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:44:09.403  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:44:09.404  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:44:09.404  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:44:09.404  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:44:09.404  6936  6997 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1bcbf050 not in the list
,08-16 13:44:09.416  6936  6997 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-16 13:44:09.416  6936  6997 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-16 13:44:09.416  6936  6997 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-16 13:44:09.416  6936  6997 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-16 13:44:09.416  6936  6997 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-16 13:44:09.416  6936  6997 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-16 13:44:09.416  6936  6997 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-16 13:44:09.416  6936  6997 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-16 13:44:09.416  6936  6997 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-16 13:44:09.416  6936  6997 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-16 13:44:09.416  6936  6997 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-16 13:44:09.416  6936  6997 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-16 13:44:09.416  6936  6997 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-16 13:44:09.416  6936  6997 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-16 13:44:09.416  6936  6997 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-16 13:44:09.416  6936  6997 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-16 13:44:09.417  6936  6997 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-16 13:44:09.417  6936  6997 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-16 13:44:09.417  6936  6997 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-16 13:44:09.417  6936  6997 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-16 13:44:09.417  6936  6997 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-16 13:44:09.417  6936  6997 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-16 13:44:09.417  6936  6997 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-16 13:44:09.417  6936  6997 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-16 13:44:09.417  6936  6997 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-16 13:44:09.417  6936  6997 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-16 13:44:09.417  6936  6997 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 3,5:2510:2510:2510:2510:2510]
08-16 13:44:09.417  6936  6997 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-16 13:44:09.417  6936  6997 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-16 13:44:09.417  6936  6997 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-16 13:44:09.417  6936  6997 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-16 13:44:09.417  6936  6997 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 13:44:09.417  6936  6997 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 13:44:09.417  6936  6997 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 13:44:09.420  6936  6997 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:44:09.420  6936  6997 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:44:09.420  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:44:09.420  6936  6997 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3356e613 not in the list
08-16 13:44:09.420  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:44:09.420  6936  6997 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1bcbf050 not in the list
08-16 13:44:09.420  6936  6997 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:44:09.420  6936  6997 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:44:09.420  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:44:09.420  6936  6997 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:44:09.420  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:44:09.422  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:44:09.422  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
08-16 13:44:09.422  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:44:09.422  6936  6997 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1bcbf050 not in the list
08-16 13:44:09.423  6936  6997 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-16 13:44:09.432  6936  6997 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 13:44:09.435  6936  6997 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 13:44:09.435  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:44:09.435  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 13:44:09.435  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:44:09.435  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 13:44:09.435  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 13:44:09.435  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 13:44:09.435  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 13:44:09.438  6936  6997 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 13:44:09.438  6936  6997 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 13:44:09.440  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:44:09.442  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:44:09.443  6936  6997 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 13:44:09.443  6936  6997 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 13:44:09.443  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 13:44:09.443  6936  6997 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 13:44:09.443  6936  6997 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 13:44:09.448  6936  6997 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 13:44:09.450  1036  1958 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 13:44:09.457  6936  6997 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-16 13:44:09.464  6936  6997 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 13:44:09.468  6936  6997 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
08-16 13:44:09.470  6936  6997 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 13:44:09.470  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 13:44:09.473  6936  6997 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-16 13:44:09.474  6936  6997 I io.jxcore.node.ConnectionHelper: start: OK
08-16 13:44:14.485  6936  6997 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 13:44:14.486  6936  6997 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 13:44:14.486  6936  6997 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 13:44:14.492  6936  6997 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:44:14.492  6936  6997 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:44:14.492  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 13:44:14.492  6936  6997 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3356e613 not in the list
08-16 13:44:14.492  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:44:14.493  6936  6997 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1bcbf050 not in the list
08-16 13:44:14.493  6936  6997 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:44:14.493  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:44:19.494  6936  6997 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-16 13:44:19.500  6936  6997 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 13:44:19.504  6936  6997 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 13:44:19.504  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:44:19.504  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 13:44:19.504  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:44:19.504  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 13:44:19.504  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 13:44:19.504  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 13:44:19.504  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 13:44:19.505  6936  6997 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 13:44:19.506  6936  6997 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 13:44:19.508  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:44:19.512  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:44:19.512  6936  6997 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 13:44:19.512  6936  6997 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 13:44:19.512  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 13:44:19.512  6936  6997 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 13:44:19.512  6936  6997 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 13:44:19.518  6936  6997 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 13:44:19.518  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 13:44:19.520  6936  6997 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-16 13:44:19.522  6936  6997 I io.jxcore.node.ConnectionHelper: start: OK
08-16 13:44:19.525  6936  6997 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 13:44:19.525  6936  6997 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 13:44:19.525  6936  6997 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 13:44:19.525  6936  6997 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:44:19.525  6936  6997 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:44:19.525  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 13:44:19.525  6936  6997 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3356e613 not in the list
08-16 13:44:19.525  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:44:19.525  6936  6997 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1bcbf050 not in the list
08-16 13:44:19.526  6936  6997 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:44:19.526  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:44:19.526  6936  6997 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:44:19.526  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:44:19.527  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:44:19.527  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:44:19.530  6936  6997 D BluetoothLeScanner: could not find callback wrapper
08-16 13:44:19.530  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 13:44:19.530  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:44:19.530  6936  6997 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1bcbf050 not in the list
08-16 13:44:19.531  6936  6997 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-16 13:44:19.537  6936  6997 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 13:44:19.540  6936  6997 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 13:44:19.540  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:44:19.540  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 13:44:19.540  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:44:19.540  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 13:44:19.540  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 13:44:19.540  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 13:44:19.540  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 13:44:19.542  6936  6997 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 13:44:19.542  6936  6997 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 13:44:19.544  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:44:19.548  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:44:19.548  6936  6997 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 13:44:19.548  6936  6997 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 13:44:19.548  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 13:44:19.548  6936  6997 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 13:44:19.548  6936  6997 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 13:44:19.554  6936  6997 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 13:44:19.554  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 13:44:19.556  6936  6997 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-16 13:44:19.559  6936  6997 I io.jxcore.node.ConnectionHelper: start: OK
08-16 13:44:24.559  6936  6997 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 13:44:24.559  6936  6997 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 13:44:24.559  6936  6997 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 13:44:29.567  6936  6997 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 13:44:29.568  6936  6997 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 13:44:29.568  6936  6997 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 13:44:29.574  6936  6997 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:44:29.575  6936  6997 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:44:29.575  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 13:44:29.576  6936  6997 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3356e613 not in the list
08-16 13:44:29.576  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:44:29.576  6936  6997 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1bcbf050 not in the list
08-16 13:44:29.576  6936  6997 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:44:29.576  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:44:29.579  6936  6997 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:44:29.579  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 13:44:29.581  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:44:29.581  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:44:29.583  6936  6997 D BluetoothLeScanner: could not find callback wrapper
08-16 13:44:29.583  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 13:44:29.583  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:44:29.583  6936  6997 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1bcbf050 not in the list
,08-16 13:44:29.587  6936  6997 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-16 13:44:29.587  6936  6997 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 13:44:29.587  6936  6997 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 13:44:29.587  6936  6997 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 13:44:29.588  6936  6997 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:44:29.588  6936  6997 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:44:29.588  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:44:29.588  6936  6997 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3356e613 not in the list
08-16 13:44:29.588  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:44:29.588  6936  6997 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1bcbf050 not in the list
08-16 13:44:29.588  6936  6997 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:44:29.588  6936  6997 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:44:29.588  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:44:29.589  6936  6997 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:44:29.589  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:44:29.590  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:44:29.590  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:44:29.591  6936  6997 D BluetoothLeScanner: could not find callback wrapper
08-16 13:44:29.591  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 13:44:29.591  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:44:29.591  6936  6997 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1bcbf050 not in the list
08-16 13:44:29.593  6936  6997 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-16 13:44:29.593  6936  6997 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 13:44:29.593  6936  6997 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 13:44:29.593  6936  6997 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 13:44:29.594  6936  6997 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:44:29.594  6936  6997 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:44:29.594  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s,) left
08-16 13:44:29.594  6936  6997 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3356e613 not in the list
08-16 13:44:29.594  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:44:29.594  6936  6997 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1bcbf050 not in the list
08-16 13:44:29.594  6936  6997 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:44:29.594  6936  6997 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:44:29.594  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:44:29.594  6936  6997 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:44:29.594  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:44:29.596  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:44:29.596  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 13:44:29.601  6936  6997 D BluetoothLeScanner: could not find callback wrapper
08-16 13:44:29.601  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 13:44:29.601  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:44:29.601  6936  6997 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1bcbf050 not in the list
08-16 13:44:29.602  6936  6997 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-16 13:44:29.603  6936  6997 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 13:44:29.603  6936  6997 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 13:44:29.603  6936  6997 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 13:44:29.603  6936  6997 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:44:29.603  6936  6997 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:44:29.603  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:44:29.604  6936  6997 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3356e613 not in the list
08-16 13:44:29.604  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:44:29.604  6936  6997 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1bcbf050 not in the list
08-16 13:44:29.604  6936  6997 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:44:29.604  6936  6997 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:44:29.604  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:44:29.604  6936  6997 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:44:29.604  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:44:29.605  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:44:29.605  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:44:29.606  6936  6997 D BluetoothLeScanner: could not find callback wrapper
08-16 13:44:29.606  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 13:44:29.606  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:44:29.606  6936  6997 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1bcbf050 not in the list
08-16 13:44:29.607  6936  6997 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-16 13:44:29.607  6936  6997 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 13:44:29.607  6936  6997 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 13:44:29.607  6936  6997 V io.jxcore.node.StartStopOperationH,andler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 13:44:29.609  6936  6997 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:44:29.609  6936  6997 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:44:29.609  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:44:29.609  6936  6997 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3356e613 not in the list
08-16 13:44:29.609  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:44:29.609  6936  6997 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1bcbf050 not in the list
08-16 13:44:29.609  6936  6997 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:44:29.609  6936  6997 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:44:29.609  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:44:29.609  6936  6997 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:44:29.609  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:44:29.614  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:44:29.615  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:44:29.615  6936  6997 D BluetoothLeScanner: could not find callback wrapper
08-16 13:44:29.615  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 13:44:29.615  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:44:29.615  6936  6997 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1bcbf050 not in the list
08-16 13:44:29.616  6936  6997 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-16 13:44:29.620  6936  6997 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 13:44:29.620  6936  6997 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 13:44:29.620  6936  6997 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-16 13:44:29.623  6936  6997 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 13:44:29.623  6936  6997 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 13:44:29.624  6936  6997 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-16 13:44:29.624  6936  6997 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 13:44:29.624  6936  6997 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 13:44:29.625  6936  6997 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 13:44:29.625  6936  6997 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 13:44:29.625  6936  6997 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 13:44:29.626  6936  6997 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:44:29.626  6936  6997 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:44:29.626  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:44:29.626  6936  6997 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3356e613 not in the list
08-16 13:44:29.626  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:44:29.626  6936  6997 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1bcbf050 not in the list
08-16 13:44:29.626  6936  6997 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:44:29.626  6936  6997 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:44:29.626  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:44:29.626  6936  6997 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:44:29.626  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:44:29.628  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:44:29.629  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:44:29.629  6936  6997 D BluetoothLeScanner: could not find callback wrapper
08-16 13:44:29.629  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 13:44:29.629  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:44:29.629  6936  6997 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1bcbf050 not in the list
08-16 13:44:29.633  6936  6997 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-16 13:44:29.638  6936  6997 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-16 13:44:29.638  6936  6997 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-16 13:44:29.645  6936  6997 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 13:44:29.645  6936  6997 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-16 13:44:29.645  6936  6997 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-16 13:44:29.645  6936  6997 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-16 13:44:29.645  6936  6997 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-16 13:44:29.645  6936  6997 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-16 13:44:29.645  6936  6997 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-16 13:44:29.645  6936  6997 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-16 13:44:29.645  6936  6997 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-16 13:44:29.645  6936  6997 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-16 13:44:29.645  6936  6997 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-16 13:44:29.646  6936  6997 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-16 13:44:29.646  6936  6997 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-16 13:44:29.646  6936  6997 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-16 13:44:29.646  6936  6997 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-16 13:44:29.646  6936  6997 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-16 13:44:29.646  6936  6997 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-16 13:44:29.646  6936  6997 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-16 13:44:29.646  6936  6997 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-16 13:44:29.646  6936  6997 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-16 13:44:29.646  6936  6997 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-16 13:44:29.646  6936  6997 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-16 13:44:29.646  6936  6997 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-16 13:44:29.646  6936  6997 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-16 13:44:29.646  6936  6997 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-16 13:44:29.646  6936  6997 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-16 13:44:29.646  6936  6997 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-16 13:44:29.646  6936  6997 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-16 13:44:29.646  6936  6997 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-16 13:44:29.646  6936  6997 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-16 13:44:29.646  6936  6997 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-16 13:44:29.646  6936  6997 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-16 13:44:29.646  6936  6997 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-16 13:44:29.647  6936  6997 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 13:44:29.647  6936  6997 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-16 13:44:29.647  6936  6997 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 13:44:29.647  6936  6997 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,08-16 13:44:29.647  6936  6997 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-16 13:44:29.647  6936  6997 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 13:44:29.647  6936  6997 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 13:44:29.647  6936  6997 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-16 13:44:29.652  6936  6997 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-16 13:44:29.653  6936  6997 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
,08-16 13:44:29.653  6936  6997 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-16 13:44:29.654  6936  6997 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-16 13:44:29.654  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-16 13:44:29.655  6936  6997 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-16 13:44:29.655  6936  6997 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 13:44:29.655  6936  6997 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-16 13:44:29.655  6936  6997 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 13:44:29.655  6936  6997 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 13:44:29.655  6936  6997 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 13:44:29.663  6936  6997 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:44:29.663  6936  6997 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:44:29.663  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:44:29.666  6936  7035 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 876)
08-16 13:44:29.663  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,08-16 13:44:29.672  6936  6997 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3356e613 not in the list
08-16 13:44:29.672  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:44:29.672  6936  6997 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1bcbf050 not in the list
08-16 13:44:29.672  6936  6997 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:44:29.672  6936  6997 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:44:29.672  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:44:29.672  6936  6997 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:44:29.672  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:44:29.674  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:44:29.674  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:44:29.674  6936  6997 D BluetoothLeScanner: could not find callback wrapper
08-16 13:44:29.674  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 13:44:29.674  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:44:29.675  6936  6997 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1bcbf050 not in the list
08-16 13:44:29.676  6936  6997 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-16 13:44:29.676  6936  6997 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 13:44:29.676  6936  6997 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 13:44:29.676  6936  6997 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 13:44:29.679  6936  7036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 876
08-16 13:44:29.679  6936  7036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 876)
08-16 13:44:29.679  6936  7036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 876)
08-16 13:44:29.679  6936  6997 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:44:29.679  6936  6997 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:44:29.679  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:44:29.679  6936  6997 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3356e613 not in the list
08-16 13:44:29.679  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:44:29.680  6936  6997 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1bcbf050 not in the list
08-16 13:44:29.680  6936  6997 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:44:29.680  6936,  6997 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:44:29.680  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:44:29.680  6936  6997 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:44:29.680  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:44:29.681  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:44:29.681  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 13:44:29.685  6936  6997 D BluetoothLeScanner: could not find callback wrapper
08-16 13:44:29.685  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 13:44:29.685  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:44:29.685  6936  6997 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1bcbf050 not in the list
08-16 13:44:29.686  6936  6997 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-16 13:44:29.687  6936  6997 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 13:44:29.687  6936  6997 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 13:44:29.687  6936  6997 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 13:44:29.699  6936  6997 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:44:29.700  6936  6997 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:44:29.700  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:44:29.700  6936  6997 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3356e613 not in the list
08-16 13:44:29.700  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:44:29.700  6936  6997 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1bcbf050 not in the list
08-16 13:44:29.700  6936  6997 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:44:29.700  6936  6997 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:44:29.700  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:44:29.700  6936  6997 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:44:29.700  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 13:44:29.704  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:44:29.704  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:44:29.705  6936  6997 D BluetoothLeScanner: could not find callback wrapper
08-16 13:44:29.705  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 13:44:29.705  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:44:29.705  6936  6997 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1bcbf050 not in the list
08-16 13:44:29.706  6936  6997 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-16 13:44:29.706  6936  6997 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-16 13:44:29.707  6936  6997 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,08-16 13:44:29.707  6936  6997 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-16 13:44:29.707  6936  6997 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-16 13:44:29.707  6936  6997 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-16 13:44:29.707  6936  6997 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 13:44:29.707  6936  6997 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-16 13:44:29.707  6936  6997 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-16 13:44:29.707  6936  6997 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-16 13:44:29.707  6936  6997 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 13:44:29.707  6936  6997 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-16 13:44:29.708  6936  6997 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 13:44:29.708  6936  6997 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 13:44:29.708  6936  6997 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 13:44:29.709  6936  6997 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 13:44:29.709  6936  6997 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:44:29.709  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:44:29.709  6936  6997 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3356e613 not in the list
08-16 13:44:29.709  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:44:29.709  6936  6997 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1bcbf050 not in the list
08-16 13:44:29.709  6936  6997 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:44:29.709  6936  6997 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:44:29.709  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:44:29.709  6936  6997 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:44:29.709  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 13:44:29.710  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:44:29.710  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:44:29.711  6936  6997 D BluetoothLeScanner: could not find callback wrapper
08-16 13:44:29.711  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 13:44:29.711  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:44:29.711  6936  6997 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1bcbf050 not in the list
08-16 13:44:29.712  6936  6997 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:44:29.712  6936  6997 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:44:29.712  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 13:44:29.712  6936  6997 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3356e613 not in the list
08-16 13:44:29.712  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:44:29.712  6936  6997 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1bcbf050 not in the list
08-16 13:44:29.712  6936  6997 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:44:29.712  6936  6997 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:44:29.712  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:44:29.824  6936  7035 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
08-16 13:44:29.825  6936  7035 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 876)
,08-16 13:44:34.713  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:44:34.714  6936  6997 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1bcbf050 not in the list
08-16 13:44:34.714  6936  6997 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:44:34.714  6936  6997 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:44:34.714  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:44:34.714  6936  6997 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3356e613 not in the list
08-16 13:44:34.714  6936  6997 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 13:44:34.715  6936  6997 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 13:44:34.715  6936  6997 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 13:44:34.723  6936  6997 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:44:34.723  6936  6997 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:44:34.723  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:44:34.723  6936  6997 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3356e613 not in the list
08-16 13:44:34.723  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:44:34.723  6936  6997 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1bcbf050 not in the list
08-16 13:44:34.723  6936  6997 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:44:34.724  6936  6997 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:44:34.724  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:44:34.724  6936  6997 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:44:34.724  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:44:34.731  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:44:34.731  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 13:44:34.734  6936  6997 D BluetoothLeScanner: could not find callback wrapper
08-16 13:44:34.734  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 13:44:34.734  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:44:34.734  6936  6997 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1bcbf050 not in the list
08-16 13:44:34.737  6936  6997 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-16 13:44:34.738  6936  6997 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 13:44:34.739  6936  6997 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-16 13:44:34.740  6936  6997 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-16 13:44:34.740  6936  6997 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-16 13:44:34.741  6936  6936 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-16 13:44:34.741  6936  6997 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-16 13:44:34.741  6936  6997 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 13:44:34.742  6936  6997 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:44:34.743  6936  6997 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-16 13:44:34.743  6936  6997 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-16 13:44:34.743  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-16 13:44:34.743  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:44:34.743  6936  6997 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-16 13:44:34.743  6936  6936 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,08-16 13:44:34.747  6936  6997 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3356e613 not in the list
08-16 13:44:34.747  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:44:34.747  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 13:44:34.747  6936  6997 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 13:44:34.747  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 13:44:34.750  6936  7054 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-16 13:44:34.750  6936  7054 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-16 13:44:34.751  6936  6997 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 13:44:34.752  6936  6997 D BluetoothLeScanner: could not find callback wrapper
08-16 13:44:34.752  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 13:44:34.752  6936  6997 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 13:44:34.752  6936  6997 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:44:34.752  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:44:34.754  6936  6997 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 13:44:34.754  6936  6936 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 13:44:34.754  6936  6936 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 13:44:34.755  6936  6936 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 13:44:34.755  6936  6997 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1bcbf050 not in the list
08-16 13:44:34.755  6936  6997 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 13:44:34.755  6936  6997 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 13:44:34.755  6936  6997 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 13:44:34.757  6936  6936 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,08-16 13:44:34.760  6936  6997 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:44:34.760  6936  6997 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:44:34.760  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:44:34.761  6936  6997 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3356e613 not in the list
08-16 13:44:34.761  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:44:34.761  6936  6997 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1bcbf050 not in the list
08-16 13:44:34.761  6936  6997 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:44:34.761  6936  6997 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:44:34.761  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:44:34.761  6936  6997 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:44:34.761  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:44:34.763  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:44:34.763  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:44:34.763  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:44:34.763  6936  6997 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1bcbf050 not in the list
08-16 13:44:34.765  6936  6997 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-16 13:44:34.766  6936  6997 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-16 13:44:34.766  6936  6997 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 13:44:34.768  6936  6997 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 13:44:34.768  6936  6997 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-16 13:44:34.772  6936  6997 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 13:44:34.772  6936  6997 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 13:44:34.773  6936  6997 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 13:44:34.773  6936  6997 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:44:34.774  6936  6997 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:44:34.774  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:44:34.774  6936  6997 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3356e613 not in the list
08-16 13:44:34.774  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:44:34.774  6936  6997 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1bcbf050 not in the list
08-16 13:44:34.774  6936  6997 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:44:34.774  6936  6997 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:44:34.774  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:44:34.774  6936  6997 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:44:34.775  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:44:34.776  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:44:34.776  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:44:34.776  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:44:34.776  6936  6997 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1bcbf050 not in the list
08-16 13:44:34.778  1036  1903 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 13:44:34.780  1036  1885 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-16 13:44:34.784  1036  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 13:44:34.785  6936  6997 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 13:44:34.785  6936  6997 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 13:44:34.785  6936  6997 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 13:44:34.786  6936  6997 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:44:34.786  6936  6997 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:44:34.786  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:44:34.786  6936  6997 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3356e613 not in the list
08-16 13:44:34.786  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:44:34.786  6936  6997 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1bcbf050 not in the list
08-16 13:44:34.786  6936  6997 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:44:34.786  6936  6997 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:44:34.786  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:44:34.786  6936  6997 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:44:34.786  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:44:34.787  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:44:34.787  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:44:34.788  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:44:34.788  6936  6997 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1bcbf050 not in the list
08-16 13:44:34.789  6936  6997 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 13:44:34.789  6936  6997 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 13:44:34.789  6936  6997 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 13:44:34.790  6936  6997 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:44:34.790  6936  6997 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:44:34.790  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:44:34.790  6936  6997 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3356e613 not in the list
08-16 13:44:34.790  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:44:34.790  6936  6997 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1bcbf050 not in the list
08-16 13:44:34.790  6936  6997 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:44:34.790  6936  6997 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:44:34.790  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:44:34.790  6936  6997 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:44:34.790  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:44:34.791  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:44:34.791  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:44:34.791  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:44:34.791  6936  6997 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1bcbf050 not in the list
08-16 13:44:35.256  6936  6936 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-16 13:44:39.796  6936  6997 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-16 13:44:39.796  6936  6997 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 13:44:39.798  6936  6997 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-16 13:44:39.798  6936  6997 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 13:44:39.798  6936  6997 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-16 13:44:39.798  6936  6997 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-16 13:44:39.812  6936  6997 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-16 13:44:39.812  6936  6997 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-16 13:44:39.813  6936  6997 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-16 13:44:39.813  6936  6997 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-16 13:44:39.814  6936  6997 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-16 13:44:39.814  6936  6997 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-16 13:44:39.814  6936  6997 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-16 13:44:39.814  6936  6997 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-16 13:44:39.815  6936  6997 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-16 13:44:39.816  6936  6997 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-16 13:44:39.816  6936  6997 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-16 13:44:39.817  6936  6997 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-16 13:44:39.817  6936  6997 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-16 13:44:39.817  6936  6997 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-16 13:44:39.818  6936  6997 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 13:44:39.818  6936  6997 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@29ea9181 added. We now have 3 listener(s)
08-16 13:44:39.818  6936  6997 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 13:44:39.824  6936  6997 D BluetoothAdapter: enable(): BT is already enabled..!
08-16 13:44:39.825  1036  1755 D WifiServiceImplEx: setWifiEnabled: true pid=6936, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-16 13:44:39.826  1036  1755 D WifiService: setWifiEnabled: true pid=6936, uid=10118
08-16 13:44:39.826  1036  1755 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-16 13:44:44.834  6936  6997 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 13:44:44.835  6936  6997 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1bfb7226 added. We now have 4 listener(s)
08-16 13:44:44.835  6936  6997 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 13:44:44.853  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:44:44.853  6936  6997 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1bfb7226 removed from the list
08-16 13:44:44.853  6936  6997 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:44:44.853  6936  6997 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:44:44.853  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:44:44.854  6936  6997 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 13:44:44.854  6936  6997 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@363b5e67 added. We now have 4 listener(s)
08-16 13:44:44.854  6936  6997 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 13:44:44.859  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:44:44.859  6936  6997 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@363b5e67 removed from the list
08-16 13:44:44.859  6936  6997 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:44:44.859  6936  6997 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:44:44.859  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:44:44.860  6936  6997 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 13:44:44.860  6936  6997 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@18b4c414 added. We now have 4 listener(s)
08-16 13:44:44.860  6936  6997 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 13:44:44.863  1036  1958 D WifiServiceImplEx: setWifiEnabled: false pid=6936, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-16 13:44:44.863  1036  1958 D WifiService: setWifiEnabled: false pid=6936, uid=10118
08-16 13:44:44.863  1036  1958 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-16 13:44:44.882  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 13:44:44.882  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,08-16 13:44:44.885  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-16 13:44:44.887  1036  1538 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-16 13:44:44.888  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-16 13:44:44.888  1036  1538 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-16 13:44:44.888  1036  1538 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-16 13:44:44.889  1036  1538 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-16 13:44:44.889  1036  1538 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-16 13:44:44.889  1036  1538 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 13:44:44.890  1036  1538 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-16 13:44:44.891  1036  1538 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-16 13:44:44.891  1036  1538 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-16 13:44:44.893  1036  1922 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 13:44:44.894  1036  1922 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@c46356 mBinding = false
08-16 13:44:44.899  1036  1538 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-16 13:44:44.902  1036  1537 D LGWifiP2pService: InactiveState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:44:44.902  1036  1537 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:44:44.902  1036  1538 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-16 13:44:44.903  2720  2720 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-16 13:44:44.903  1036  1538 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-16 13:44:44.903  1036  1538 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 13:44:44.904  1036  1538 D WifiNative-wlan0: SET ps 1: returned true
08-16 13:44:44.905  1036  2843 D DhcpStateMachine: RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:44:44.911  1036  1107 D BluetoothManagerService: Message: 2
,08-16 13:44:44.915  1036  1107 D BluetoothManagerService: Sending off request.
08-16 13:44:44.915  4245  4272 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-16 13:44:44.916  4245  4337 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-16 13:44:44.916  4245  4337 D BluetoothAdapterProperties: Setting state to 13
08-16 13:44:44.916  4245  4337 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-16 13:44:44.917  4245  4337 D BluetoothAdapterProperties: onBluetoothDisable()
08-16 13:44:44.917  4245  4337 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-16 13:44:44.922  4245  4349 D BluetoothAdapterProperties: Scan Mode:20
08-16 13:44:44.922  4245  4337 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-16 13:44:44.923  4245  4337 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-16 13:44:44.927  4245  4624 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 13:44:44.928  4245  4681 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 13:44:44.929  4245  4676 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 13:44:44.929  4245  4679 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 13:44:44.930  4245  4623 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-16 13:44:44.930  4245  4623 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 13:44:44.930  4245  4623 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-16 13:44:44.930  4245  4623 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-16 13:44:44.930  4245  4623 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-16 13:44:44.930  4245  4623 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-16 13:44:44.930  4245  4623 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-16 13:44:44.930  4245  4623 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-16 13:44:44.932  4245  4468 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-16 13:44:44.932  4245  4468 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-16 13:44:44.934  4245  4468 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 13:44:44.934  4245  4468 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 13:44:44.934  4245  4468 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 13:44:44.934  4245  4468 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 13:44:44.934  4245  4468 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 13:44:44.934  4245  4468 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 13:44:44.934  4245  4468 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 13:44:44.934  4245  4468 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 13:44:44.934  4245  4468 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 13:44:44.934  4245  4468 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-16 13:44:44.934  4245  4468 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-16 13:44:44.934  4245  4468 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-16 13:44:44.955  6936  6936 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:44:44.955  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:44:44.955  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:44:44.955  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 13:44:44.955  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:44:44.955  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 13:44:44.955  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 13:44:44.955  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 13:44:44.955  6936 , 6936 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 13:44:44.960  6936  6936 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:44:44.961  6936  6936 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 13:44:44.969  6936  6936 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:44:44.969  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:44:44.969  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:44:44.969  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 13:44:44.969  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:44:44.969  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 13:44:44.969  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 13:44:44.969  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 13:44:44.969  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 13:44:44.972  1036  1107 D BluetoothManagerService: Message: 60
08-16 13:44:44.972  1036  1107 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-16 13:44:44.972  1036  1107 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-16 13:44:44.974  6936  6936 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:44:44.974  6936  6936 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 13:44:44.976   308   895 D CommandListener: Clearing all IP addresses on wlan0
08-16 13:44:45.008  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 13:44:45.008  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,08-16 13:44:45.012  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-16 13:44:45.028  1036  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-16 13:44:45.039  1036  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,08-16 13:44:45.047  1036  1093 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7077 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-16 13:44:45.051  1036  1537 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:44:45.051  1036  1537 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 13:44:45.051  1036  1537 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@2e3e6111
08-16 13:44:45.052  1036  1538 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 13:44:45.052  1036  1537 D LGWifiP2pService: P2pDisablingState
08-16 13:44:45.052  1036  1537 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:44:45.052  1036  1538 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 13:44:45.052  1036  1537 D LGWifiP2pService: p2p socket connection lost
08-16 13:44:45.052  1036  1537 D LGWifiP2pService: P2pDisabledState
08-16 13:44:45.052  1036  1538 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 13:44:45.053  1036  1538 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 13:44:45.053  1036  1538 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,08-16 13:44:45.054  1036  1538 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 13:44:45.054  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-16 13:44:45.055  1036  1538 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-16 13:44:45.055  1036  1538 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-16 13:44:45.055  6936  6997 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 13:44:45.055  1036  1538 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-16 13:44:45.055  2720  2720 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-16 13:44:45.058  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 13:44:45.058  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 13:44:45.059  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 13:44:45.062  1941  1941 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-16 13:44:45.065  1036  1538 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-16 13:44:45.065  1036  1538 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 13:44:45.065  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:44:45.065  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:44:45.065  1036  1538 D WifiNative-wlan0: SET ps 1: returned true
08-16 13:44:45.065  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 13:44:45.066  1036  1537 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:44:45.066  1036  1537 D LGWifiP2pService: DefaultState{ when=-11ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 13:44:45.068  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-16 13:44:45.071  6936  6997 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:44:45.072  6936  6997 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 13:44:45.072  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:44:45.072  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 13:44:45.072  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:44:45.072  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 13:44:45.072  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 13:44:45.072  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 13:44:45.072  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 13:44:45.073  6936  6997 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:44:45.073  6936  6997 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 13:44:45.073  6936  6997 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 13:44:45.074  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:44:45.074  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:44:45.074  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 13:44:45.075  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:44:45.075  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 1
08-16 13:44:45.075  1036  1036 D RttService: SCAN_AVAILABLE : 1
08-16 13:44:45.075  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-16 13:44:45.075  1941  1941 D WfdsService: WifiP2pState is changed : false
,08-16 13:44:45.076  1941  2315 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-16 13:44:45.076  1941  2315 D WfdsService: Set the WFDS Monitor: false
08-16 13:44:45.076  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:44:45.077  1941  2767 D CtrlSupplicant: Received on exit socket, terminate
08-16 13:44:45.077  1941  2767 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-16 13:44:45.077  1941  2767 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-16 13:44:45.077  1941  2767 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-16 13:44:45.079  1036  1556 D WifiScanningService: DefaultState got{ when=-5ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:44:45.080  1941  2315 D WfdsMonitor: WFDS Monitor is stopped
08-16 13:44:45.080  1941  2315 D WfdsService: STATE : WfdsDisabledState - enter
08-16 13:44:45.080  1941  2315 W WfdsService: DefaultState - msg [9445378] is not handled
08-16 13:44:45.080  1941  2316 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
,08-16 13:44:45.080  1036  1382 D PowerManagerServiceEx: acquireWakeLockInternal: lock=439211240, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
08-16 13:44:45.082  1036  1557 D RttService: EnabledState got{ when=-7ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:44:45.084  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 13:44:45.084  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 13:44:45.086  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 13:44:45.092  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-16 13:44:45.094  4245  4245 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:44:45.095  6936  6936 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:44:45.095  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:44:45.095  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:44:45.095  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 13:44:45.095  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:44:45.095  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 13:44:45.095  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 13:44:45.095  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 13:44:45.095  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 13:44:45.095  4245  4245 D BluetoothMapService: STATE_TURNING_OFF
08-16 13:44:45.095  4245  4245 V BluetoothMapService: Handler(): got msg=4
08-16 13:44:45.095  4245  4245 D BluetoothMapService: MAP Service closeService in
08-16 13:44:45.095  4245  4245 D BluetoothMapMasInstance: MAP Service shutdown
08-16 13:44:45.095  6936  6936 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:44:45.095  4245  4245 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-16 13:44:45.095  6936  6936 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 13:44:45.095  4245  4245 V BluetoothMapService: MAP Service closeService out
08-16 13:44:45.096  4245  4245 V BtOppService: Receiver DISABLED_ACTION 
08-16 13:44:45.096  4245  4245 I BtOppRfcommListener: stopping Accept Thread
08-16 13:44:45.096  4245  4245 V BtOppRfcommListener: close mBtServerSocket
08-16 13:44:45.097  4245  4245 V BtOppRfcommListener: waiting for thread to terminate
08-16 13:44:45.097  4245  4676 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-16 13:44:45.097  6936  6936 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:44:45.097  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:44:45.097  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:44:45.097  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 13:44:45.097  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:44:45.097  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 13:44:45.097  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 13:44:45.097  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 13:44:45.097  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 13:44:45.097  4245  4245 V BtOppRfcommListener: done waiting for thread to terminate
08-16 13:44:45.098  6936  6936 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:44:45.098  6936  6936 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi,: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 13:44:45.099  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:44:45.099  4245  4245 V BtOppService: onDestroy
08-16 13:44:45.102  1036  1646 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
08-16 13:44:45.102  1036  2841 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:44:45.102  1036  2841 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:44:45.102  1036  2841 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-16 13:44:45.102  1036  2841 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:44:45.102  1036  2841 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
08-16 13:44:45.105  4245  4245 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-16 13:44:45.107  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 13:44:45.110   308   895 D CommandListener: Clearing all IP addresses on wlan0
08-16 13:44:45.110   308  7097 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-16 13:44:45.110  1036  1545 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-16 13:44:45.111  1036  1545 D DSQN    : disableDataServiceNotify
08-16 13:44:45.111  1036  1545 D DSQN    : stop dsqn bin
08-16 13:44:45.111  1036  2841 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
08-16 13:44:45.112  1036  1105 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-16 13:44:45.113  1036  1538 D WifiNative-p2p0: doBoolean: TERMINATE
08-16 13:44:45.114  1036  1538 D WifiNative-p2p0: TERMINATE: returned true
08-16 13:44:45.114  1036  1538 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 13:44:45.114  1036  1538 E WifiStateMachine: useWiFiOffloading() : false
08-16 13:44:45.114  1036  1538 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-16 13:44:45.115  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-16 13:44:45.118  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:44:45.118  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:44:45.118  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 13:44:45.119  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-16 13:44:45.121  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-16 13:44:45.121  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 13:44:45.121  1036  1036 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-16 13:44:45.122  6936  6936 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:44:45.122  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:44:45.122  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:44:45.122  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 13:44:45.122  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 13:44:45.122  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 13:44:45.122  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 13:44:45.122  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 13:44:45.122  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 13:44:45.122  6936  6936 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:44:45.122  6936  6936 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 13:44:45.124  6936  6936 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:44:45.124  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:44:45.124  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:44:45.124  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 13:44:45.124  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 13:44:45.124  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 13:44:45.124  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 13:44:45.124  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 13:44:45.124  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 13:44:45.125  6936  6936 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:44:45.125  6936  6936 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 13:44:45.125  1036  1545 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-16 13:44:45.125  1036  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 13:44:45.125  1036  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 13:44:45.126  1036  1545 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 13:44:45.126  1036  1545 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-16 13:44:45.126  1036  1545 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-16 13:44:45.126  1036  1545 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-16 13:44:45.127  1036  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-16 13:44:45.127  1036  1545 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-16 13:44:45.127  1036  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-16 13:44:45.127  1036  1545 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-16 13:44:45.127  1036  1545 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 13:44:45.127  1036  1545 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 13:44:45.128  1603  2071 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-16 13:44:45.128  1036  2841 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:44:45.128  1036  2841 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:44:45.128  1036  2841 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-16 13:44:45.129  1036  1536 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-16 13:44:45.131  1036  1538 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 13:44:45.131  1036  1538 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 13:44:45.131  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-16 13:44:45.132  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-16 13:44:45.132  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-16 13:44:45.132  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-16 13:44:45.133  1036  1545 D NetworkManagementService: Removing idletimer
08-16 13:44:45.133  6936  6936 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:44:45.133  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:44:45.133  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:44:45.133  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 13:44:45.133  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 13:44:45.133  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 13:44:45.133  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 13:44:45.133  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 13:44:45.133  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 13:44:45.133  1036  1545 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:44:45.133  1036  1545 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-16 13:44:45.134  6936  6936 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:44:45.134  6936  6936 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 13:44:45.134  1851  1851 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 13:44:45.135  1851  1851 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-16 13:44:45.135  1036  1536 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-16 13:44:45.136  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-16 13:44:45.136  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-16 13:44:45.136  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-16 13:44:45.136  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-16 13:44:45.140  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-16 13:44:45.140  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-16 13:44:45.142  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 13:44:45.162  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 13:44:45.175  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 13:44:45.176  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 13:44:45.176  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 13:44:45.190  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 13:44:45.191  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 13:44:45.191  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 13:44:45.196  2600  2600 D [Concierge]Service: onStartCommand(). Type : 9
08-16 13:44:45.200  7077  7077 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-16 13:44:45.201  7077  7077 W LG Account v2.2: No ProfileInfo entries
08-16 13:44:45.201  7077  7077 I LG Account v2.2: isEnabled: false
08-16 13:44:45.201  7077  7077 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-16 13:44:45.201  7077  7077 I Feature : [Lifetracker]Country: EU
08-16 13:44:45.201  7077  7077 I Feature : [Lifetracker]Operator: OPEN
08-16 13:44:45.201  7077  7077 I Feature : [Lifetracker]Ranking support: false
08-16 13:44:45.201  7077  7077 I Feature : [Lifetracker]Comfort support: false
08-16 13:44:45.201  7077  7077 I Feature : [Lifetracker]Accessory: true
08-16 13:44:45.201  7077  7077 I Feature : [Lifetracker]Health device: true
08-16 13:44:45.201  7077  7077 I Feature : [Lifetracker]Extra Pedometer: false
08-16 13:44:45.201  7077  7077 I Feature : [Lifetracker]Blood glucose device: false
,08-16 13:44:45.201  7077  7077 I Feature : [Lifetracker]Device Number: 3
08-16 13:44:45.204  2720  2720 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-16 13:44:45.204  2720  2720 I wpa_supplicant: monitor socket send errors count : 1
08-16 13:44:45.204  2720  2720 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1941-2\x00 that cannot receive messages
,08-16 13:44:45.205  1036  2747 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-16 13:44:45.205  1036  2747 D WifiMonitor: Dropping event because (p2p0) is stopped
08-16 13:44:45.207  1036  2843 D DhcpStateMachine: StoppedState
08-16 13:44:45.207  1036  2843 D DhcpStateMachine: StoppedState{ when=-141ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:44:45.207  1036  1538 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-16 13:44:45.207  1036  1538 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-16 13:44:45.209  6395  6395 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 13:44:45.228  1036  1051 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7103 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-16 13:44:45.229  1036  1051 I ActivityManager: Killing 6178:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-16 13:44:45.242  2720  2720 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-16 13:44:45.243  2720  2720 W wpa_supplicant: USIM:  scard_deinit function
08-16 13:44:45.243  1036  2747 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-16 13:44:45.243  1036  2747 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-16 13:44:45.243  1036  2747 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-16 13:44:45.244  1036  2747 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-16 13:44:45.244  1036  2747 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 13:44:45.244  1036  2747 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 13:44:45.244  1036  1538 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=381914
08-16 13:44:45.245  1036  1538 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=381914
08-16 13:44:45.245  1036  1538 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=381914  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-16 13:44:45.245  1036  1107 D Tethering: InitialState.processMessage what=4
08-16 13:44:45.245  1036  1538 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=381914  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
,08-16 13:44:45.264  1036  1904 W libprocessgroup: failed to open /acct/uid_10014/pid_6178/cgroup.procs: No such file or directory
08-16 13:44:45.266  1036  1107 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-16 13:44:45.272  1036  1538 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-16 13:44:45.272  1036  1538 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-16 13:44:45.326  1036  1903 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=7122 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-16 13:44:45.331  2720  2720 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-16 13:44:45.331  1036  2747 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-16 13:44:45.331  1036  2747 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
08-16 13:44:45.331  1036  2747 D WifiMonitor: Disconnecting from the supplicant, no more events
08-16 13:44:45.332  1036  1538 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
08-16 13:44:45.361  7103  7103 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-16 13:44:45.364  7103  7103 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 13:44:45.365  7103  7103 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 13:44:45.366  1036  2033 I ActivityManager: Killing 6274:com.android.defcontainer/u0a4 (adj 15): empty #17
,08-16 13:44:45.453  1036  1052 W libprocessgroup: failed to open /acct/uid_10004/pid_6274/cgroup.procs: No such file or directory
,08-16 13:44:45.461  1036  1538 D WifiOffDelayIfNotUsed: stopMonitoring
08-16 13:44:45.461  1036  1538 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 13:44:45.461  1036  1538 E WifiStateMachine: useWiFiOffloading() : false
08-16 13:44:45.461  1036  1538 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-16 13:44:45.464  1941  1941 D WfdsService: Supplicant Connection state is changed : false
08-16 13:44:45.464  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-16 13:44:45.465  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-16 13:44:45.465  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 13:44:45.466  1036  1542 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-16 13:44:45.466  1036  1542 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-16 13:44:45.466  1941  2315 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-16 13:44:45.467  1941  2315 D WfdsService: Set the WFDS Monitor: false
08-16 13:44:45.467  1941  2315 D WfdsMonitor: WFDS Monitor is stopped
,08-16 13:44:45.471  6936  6936 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 13:44:45.471  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:44:45.471  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:44:45.471  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 13:44:45.471  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 13:44:45.471  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 13:44:45.471  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 13:44:45.471  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 13:44:45.471  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 13:44:45.474  2474  2474 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 13:44:45.475  6936  6936 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:44:45.475  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:44:45.475  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:44:45.475  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 13:44:45.475  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 13:44:45.475  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 13:44:45.475  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 13:44:45.475  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 13:44:45.475  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 13:44:45.478  6936  6936 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:44:45.478  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:44:45.478  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:44:45.478  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 13:44:45.478  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 13:44:45.478  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 13:44:45.478  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 13:44:45.478  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 13:44:45.478  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 13:44:45.497  7122  7122 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 13:44:45.497  7122  7122 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-16 13:44:45.498  7122  7122 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 13:44:45.498  7122  7122 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-16 13:44:45.500  7122  7122 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-16 13:44:45.501  7122  7122 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-16 13:44:45.667  7122  7122 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-16 13:44:45.673  4245  4245 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-16 13:44:45.673  4245  4245 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:44:45.673  4245  4245 V BluetoothPbapReceiver: ***********state = 13
08-16 13:44:45.677  4245  4245 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-16 13:44:45.678  4245  4245 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:44:45.678  4245  4245 V BluetoothPbapService: state: 13
08-16 13:44:45.679  4245  4245 V BluetoothPbapService: Pbap Service closeService in
08-16 13:44:45.685  7122  7122 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 13:44:45.687  2175  2175 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 13:44:45.689  4245  4245 V BluetoothPbapService: successfully stopped pbap service
08-16 13:44:45.689  4245  4245 V BluetoothPbapService: Pbap Service closeService out
08-16 13:44:45.690  4245  4245 V BluetoothPbapService: Pbap Service onDestroy
,08-16 13:44:45.691  4245  4245 V BluetoothPbapService: Pbap Service closeService in
08-16 13:44:45.691  4245  4245 V BluetoothPbapService: Pbap Service closeService out
08-16 13:44:45.691  4245  4245 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-16 13:44:45.712  7122  7122 D LgDataFeature: LgDataFeature() Constructor: none
08-16 13:44:45.712  7122  7122 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 13:44:45.719  7122  7122 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 13:44:45.724  1036  1107 D BluetoothManagerService: Message: 20
08-16 13:44:45.725  1036  1107 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@118635a9:true
,08-16 13:44:45.732  1036  1107 D BluetoothManagerService: Message: 30
08-16 13:44:45.735  1036  1107 D BluetoothManagerService: Message: 30
08-16 13:44:45.737  7122  7122 D LocalBluetoothProfileManager: Adding local MAP profile
08-16 13:44:45.738  7122  7122 D BluetoothMap: Create BluetoothMap proxy object
,08-16 13:44:45.739  1036  1107 D BluetoothManagerService: Message: 30
,08-16 13:44:45.743  1036  1107 D BluetoothManagerService: Message: 30
08-16 13:44:45.745  7122  7122 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-16 13:44:45.746  7122  7122 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
08-16 13:44:45.757  7122  7122 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,08-16 13:44:45.761  7122  7122 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
08-16 13:44:45.774  7122  7122 D DockEventReceiver: finishStartingService: stopping service
,08-16 13:44:45.796  7122  7122 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-16 13:44:45.804  7122  7122 D BluetoothInputDevice: Proxy object connected
08-16 13:44:45.806  7122  7122 D HidProfile: Bluetooth service connected
08-16 13:44:45.808  7122  7122 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 13:44:45.810  7122  7122 D PanProfile: Bluetooth service connected
,08-16 13:44:45.811  7122  7122 D BluetoothMap: Proxy object connected
08-16 13:44:45.814  7122  7122 D MapProfile: Bluetooth service connected
08-16 13:44:45.814  7122  7122 D BluetoothMap: getConnectedDevices()
08-16 13:44:45.815  7122  7122 D BluetoothMap: Bluetooth is Not enabled
,08-16 13:44:45.816  7122  7122 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-16 13:44:45.820  7122  7122 D BluetoothPermissionRequest: onReceive
08-16 13:44:45.824  7122  7122 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-16 13:44:45.838  1036  1052 I ActivityManager: Killing 6436:com.google.android.partnersetup/u0a8 (adj 15): empty #17
08-16 13:44:45.840  7122  7122 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-16 13:44:45.937  4245  4349 D bt_hci_bdroid: cleanup
,08-16 13:44:45.938  4245  4470 I bt_lpm  : LPM is already off!!!
,08-16 13:44:45.938  4245  4610 I bt_userial_mct: exiting userial_read_thread
08-16 13:44:45.938  4245  4610 D bt_userial_mct: Leaving userial_evt_read_thread()
08-16 13:44:45.939  4245  4468 W bt-btif : ag scb idx 1 not allocated
,08-16 13:44:45.939  4245  4468 E bt-btif : BTA AG is already disabled, ignoring ...
08-16 13:44:45.939  4245  4468 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 13:44:45.939  4245  4468 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 13:44:45.940  4245  4468 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 13:44:45.940  4245  4468 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 13:44:45.940  4245  4468 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 13:44:45.940  4245  4468 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 13:44:45.940  4245  4468 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 13:44:45.940  4245  4468 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 13:44:45.940  4245  4468 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 13:44:45.940  4245  4468 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 13:44:45.940  4245  4468 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 13:44:45.940  4245  4468 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 13:44:45.940  4245  4468 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 13:44:45.940  4245  4468 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 13:44:45.940  4245  4468 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 13:44:45.940  4245  4468 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 13:44:45.940  4245  4468 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 13:44:45.940  4245  4468 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 13:44:45.941  4245  4468 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-16 13:44:45.941  4245  4349 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-16 13:44:45.941  4245  4470 I bt_vendor: hw_epilog_process
08-16 13:44:45.942  4245  4349 D bt_hci_bdroid: cleanup Finalizing cleanup
08-16 13:44:45.942  4245  4349 D bt_userial_mct: userial_close
08-16 13:44:45.942  4245  4349 E bt_userial_mct: pthread_join() FAILED result:3
08-16 13:44:45.942  4245  4349 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-16 13:44:45.946  1036  1885 W libprocessgroup: failed to open /acct/uid_10008/pid_6436/cgroup.procs: No such file or directory
08-16 13:44:45.946  4245  4245 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-16 13:44:45.946  4245  4245 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-16 13:44:45.948  4245  4245 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
,08-16 13:44:46.019  1036  1994 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7150 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
08-16 13:44:46.020  4245  4245 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:44:46.020  4245  4245 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-16 13:44:46.021  4245  4245 V BluetoothFtpService: Ftp Service onStartCommand
08-16 13:44:46.022  4245  4245 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:44:46.022  4245  4245 V BluetoothFtpService: Ftp Service closeService
08-16 13:44:46.022  4245  4245 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-16 13:44:46.023  4245  4245 V BluetoothFtpService: successfully stopped ftp service
08-16 13:44:46.023  4245  4245 V BluetoothFtpService: Ftp Service onDestroy
08-16 13:44:46.023  4245  4245 V BluetoothFtpService: Ftp Service closeService
,08-16 13:44:46.028  4245  4245 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 13:44:46.028  4245  4245 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 13:44:46.028  4245  4245 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 13:44:46.028  4245  4245 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:44:46.028  4245  4245 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-16 13:44:46.028  4245  4245 V BluetoothSapReceiver: Calling SAP service start service with action = null
,08-16 13:44:46.030  4245  4245 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:44:46.030  4245  4245 V BluetoothSapService: state: 13
08-16 13:44:46.030  4245  4245 V BluetoothSapService: Stopping SAP server process
08-16 13:44:46.031  4245  4245 V BluetoothSapService: Sap Service closeSapService in
08-16 13:44:46.032  4245  4245 V BluetoothSapService: Close listen Socket : 
08-16 13:44:46.032  4245  4245 V BluetoothSapService: Close rfcomm Socket : 
08-16 13:44:46.032  4245  4245 V BluetoothSapService: Close sapd  Socket : 
08-16 13:44:46.073  4245  4349 D bt_hci_bdroid: set_power 0
08-16 13:44:46.073  4245  4349 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,08-16 13:44:46.073  4245  4349 I bt_vendor: bluetooth satus is on
08-16 13:44:46.073  4245  4349 I bt_vendor: bt-vendor : resetting BT status
08-16 13:44:46.073  4245  4349 I bt_vendor: Starting hciattach daemon
08-16 13:44:46.073  4245  4349 I bt_vendor: try to set false
08-16 13:44:46.074  4245  4349 I bt_vendor: Starting hciattach daemon
08-16 13:44:46.074  4245  4349 I bt_vendor: try to set false
08-16 13:44:46.074  4245  4349 I bt_vendor: cleanup
08-16 13:44:46.075  4245  4468 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
,08-16 13:44:46.083  1036  1646 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7167 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-16 13:44:46.084  4245  4245 V BluetoothSapService: Sap Service closeSapService out
08-16 13:44:46.084  4245  4245 V BluetoothSapService: Sap Service onDestroy
08-16 13:44:46.084  4245  4245 V BluetoothSapService: Sap Service closeSapService in
08-16 13:44:46.084  4245  4245 V BluetoothSapService: Close listen Socket : 
08-16 13:44:46.084  4245  4245 V BluetoothSapService: Close rfcomm Socket : 
08-16 13:44:46.084  4245  4245 V BluetoothSapService: Close sapd  Socket : 
08-16 13:44:46.087  4245  4349 I GKI_LINUX: GKI_exit_task 0 done
08-16 13:44:46.087  4245  4349 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-16 13:44:46.089  4245  4337 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-16 13:44:46.089  4245  4245 V BluetoothSapService: Sap Service closeSapService out
,08-16 13:44:46.092  4245  4245 D HeadsetService: Received stop request...Stopping profile...
08-16 13:44:46.093  4245  4384 D HeadsetStateMachine: Exit Disconnected: -1
08-16 13:44:46.094  4245  4245 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-16 13:44:46.094  4245  4245 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 13:44:46.094  4245  4245 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a9d5018
08-16 13:44:46.095  1851  1851 D BluetoothHeadset: Proxy object disconnected
08-16 13:44:46.095  1851  1851 D BluetoothHeadset: Proxy object disconnected
08-16 13:44:46.095  1851  1851 D BluetoothHeadset: Proxy object disconnected
08-16 13:44:46.095  1036  1036 D BluetoothHeadset: Proxy object disconnected
08-16 13:44:46.095  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-16 13:44:46.096  4245  4245 D A2dpService: Received stop request...Stopping profile...
08-16 13:44:46.096  4245  4440 D A2dpStateMachine: Exit Disconnected: -1
08-16 13:44:46.096  4245  4245 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-16 13:44:46.098  4245  4245 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-16 13:44:46.098  4245  4245 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 13:44:46.098  4245  4245 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a9d5018
08-16 13:44:46.098  1036  1036 D BluetoothA2dp: Proxy object disconnected
08-16 13:44:46.098  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-16 13:44:46.099  4245  4337 D BluetoothAdapterState: Stopping profile services that were post enabled
08-16 13:44:46.099  4245  4245 D HidService: Received stop request...Stopping profile...
08-16 13:44:46.099  4245  4245 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a9d5018
08-16 13:44:46.100  4245  4245 D HealthService: Received stop request...Stopping profile...
08-16 13:44:46.101  4245  4245 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a9d5018
08-16 13:44:46.101  7122  7122 D BluetoothInputDevice: Proxy object disconnected
08-16 13:44:46.101  7122  7122 D HidProfile: Bluetooth service disconnected
08-16 13:44:46.102  4245  4245 D HeadsetStateMachine: Unbinding service...
08-16 13:44:46.102  4245  4245 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-16 13:44:46.102  4245  4245 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-16 13:44:46.102  4245  4245 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-16 13:44:46.102  4245  4245 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-16 13:44:46.102  4245  4245 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-16 13:44:46.102  4245  4245 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 13:44:46.102  4245  4245 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
,08-16 13:44:46.105  4245  4245 D PanService: Received stop request...Stopping profile...
08-16 13:44:46.106  4245  4245 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a9d5018
08-16 13:44:46.109  7122  7122 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-16 13:44:46.109  7122  7122 D PanProfile: Bluetooth service disconnected
08-16 13:44:46.109  4245  4245 D BtGatt.DebugUtils: handleDebugAction() action=null
08-16 13:44:46.109  4245  4245 D BtGatt.GattService: Received stop request...Stopping profile...
08-16 13:44:46.109  4245  4245 D BtGatt.GattService: stop()
08-16 13:44:46.109  4245  4245 D BtGatt.AdvertiseManager: advertise clients cleared
08-16 13:44:46.110  4245  4245 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a9d5018
08-16 13:44:46.111  4245  4245 I BluetoothA2dpServiceJni: cleanupNative
08-16 13:44:46.111  4245  4441 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-16 13:44:46.111  4245  4245 I GKI_LINUX: GKI_exit_task 2 done
08-16 13:44:46.111  4245  4245 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-16 13:44:46.112  4245  4245 D BluetoothMapService: Received stop request...Stopping profile...
08-16 13:44:46.112  4245  4245 D BluetoothMapService: stop()
08-16 13:44:46.113  4245  4245 D BluetoothMapEmailAppObserver: deinitObservers()
08-16 13:44:46.113  4245  4245 D BluetoothMapEmailAppObserver: removeReceiver()
08-16 13:44:46.113  4245  4245 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a9d5018
08-16 13:44:46.114  4245  4245 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-16 13:44:46.114  4245  4245 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-16 13:44:46.114  4245  4245 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-16 13:44:46.114  4245  4245 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-16 13:44:46.114  4245  4245 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-16 13:44:46.114  4245  4245 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-16 13:44:46.114  4245  4245 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-16 13:44:46.115  7122  7122 D BluetoothMap: Proxy object disconnected
08-16 13:44:46.115  7122  7122 D MapProfile: Bluetooth service disconnected
08-16 13:44:46.115  4245  4245 V BluetoothMapService: Handler(): got msg=4
08-16 13:44:46.115  4245  4245 D BluetoothMapService: MAP Service closeService in
08-16 13:44:46.115  4245  4245 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-16 13:44:46.115  4245  4245 V BluetoothMapService: MAP Service closeService out
08-16 13:44:46.116  4245  4245 D BluetoothMapService: cleanup()
08-16 13:44:46.116  4245  4245 D BluetoothMapService: MAP Service closeService in
08-16 13:44:46.116  4245  4245 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-16 13:44:46.116  4245  4245 V BluetoothMapService: MAP Service closeService out
08-16 13:44:46.116  4245  4337 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-16 13:44:46.116  4245  4337 D BluetoothAdapterProperties: Setting state to 10
08-16 13:44:46.116  4245  4337 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-16 13:44:46.117  4245  4337 I BluetoothAdapterState: Entering OffState
08-16 13:44:46.117  1036  1107 D BluetoothManagerService: Message: 60
08-16 13:44:46.117  1036  1107 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-16 13:44:46.117  1036  1107 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-16 13:44:46.117  1851  2444 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 13:44:46.118  1036  1107 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 13:44:46.118  1851  1867 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 13:44:46.119  1036  1107 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 13:44:46.119  1851  1866 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 13:44:46.120  7122  7138 D BluetoothPbap: onBluetoothStateChange: up=false
08-16 13:44:46.120  7122  7139 D BluetoothMap: onBluetoothStateChange: up=false
08-16 13:44:46.121  7122  7138 D BluetoothPan: onBluetoothStateChange on: false
08-16 13:44:46.121  7122  7139 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-16 13:44:46.123  1036  1107 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-16 13:44:46.123  7150  7150 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 13:44:46.123  1036  1107 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-16 13:44:46.125  1036  1107 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-16 13:44:46.125  1036  1107 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-16 13:44:46.125  1036  1107 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@c46356 mBinding = false
08-16 13:44:46.125  1036  1107 D BluetoothManagerService: Sending unbind request.
,08-16 13:44:46.127  1036  1107 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-16 13:44:46.130  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 13:44:46.130  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:44:46.131  7122  7122 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-16 13:44:46.132  7122  7122 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-16 13:44:46.132  7122  7122 D LGBluetoothEventManager: [BTUI] clear device connection state
08-16 13:44:46.133  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:44:46.133  1941  2125 D LGBluetoothAPIService: Message: 2
08-16 13:44:46.133  4245  4349 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-16 13:44:46.133  1941  2125 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@3249e58b mBinding = false
08-16 13:44:46.133  1941  2125 D LGBluetoothAPIService: Sending unbind request.
08-16 13:44:46.134  4245  4245 I GKI_LINUX: GKI_exit_task 1 done
08-16 13:44:46.134  4245  4245 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-16 13:44:46.134  4245  4245 I BluetoothServiceJni: cleanupNative: return from cleanup
08-16 13:44:46.134  4245  4245 I art     : --- WEIRD: removing null entry 246
08-16 13:44:46.134  4245  4245 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-16 13:44:46.134  4245  4245 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-16 13:44:46.135  4245  4245 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-16 13:44:46.137  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:44:46.137  4245  4245 I art     : System.exit called, status: 0
08-16 13:44:46.137  4245  4245 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-16 13:44:46.137  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:44:46.139  1603  1603 D BluetoothAdapter: 735540912: getState() :  mService = null. Returning STATE_OFF
08-16 13:44:46.139  1603  1603 D BluetoothAdapter: 735540912: getState() :  mService = null. Returning STATE_OFF
,08-16 13:44:46.152   312  1385 V AudioFlinger: 4245 died, releasing its sessions
08-16 13:44:46.152   312  1385 V AudioFlinger:  pid 1851 @ 0
08-16 13:44:46.152   312  1385 V AudioFlinger:  pid 3309 @ 1
08-16 13:44:46.152   312  1385 V AudioFlinger:  pid 3309 @ 2
08-16 13:44:46.153  7122  7122 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
,08-16 13:44:46.155  7167  7167 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 13:44:46.240  1036  2032 I ActivityManager: Process com.android.bluetooth (pid 4245) has died
08-16 13:44:46.240  1036  2032 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,08-16 13:44:46.253  7150  7150 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
08-16 13:44:46.263  7122  7122 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-16 13:44:46.324  7150  7150 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,08-16 13:44:46.325  7150  7150 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-16 13:44:46.325  7150  7150 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-16 13:44:46.326  7150  7150 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-16 13:44:46.326  7150  7150 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-16 13:44:46.329  7150  7150 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-16 13:44:46.336  7150  7150 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-16 13:44:46.355  1036  1646 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7186 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
08-16 13:44:46.356  7122  7122 D DockEventReceiver: finishStartingService: stopping service
,08-16 13:44:46.362  1036  1940 I ActivityManager: Killing 6484:com.lge.appbox.client/u0a11 (adj 15): empty #17
08-16 13:44:46.363  7150  7150 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 13:44:46.368  7150  7150 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 13:44:46.494  1036  1885 W libprocessgroup: failed to open /acct/uid_10011/pid_6484/cgroup.procs: No such file or directory
,08-16 13:44:46.508  7150  7150 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-16 13:44:46.559  7186  7186 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-16 13:44:46.560  7186  7186 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-16 13:44:46.563  7186  7186 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-16 13:44:46.564  7186  7186 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-16 13:44:46.583  7186  7186 D BluetoothAdapterApp: Loading JNI Library
,08-16 13:44:46.610  6395  6395 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 13:44:46.624  7186  7186 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@1a1b7d39 Instance Count = 1
,08-16 13:44:46.636  7186  7186 D BluetoothAdapterApp: onCreate
08-16 13:44:46.640  7103  7103 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-16 13:44:46.640  7103  7103 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 13:44:46.640  7103  7103 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-16 13:44:46.663  7122  7122 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 13:44:46.666  7186  7186 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-16 13:44:46.667  7186  7186 D ProfileConfigQcom: Adding HeadsetService
08-16 13:44:46.667  7186  7186 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-16 13:44:46.667  7186  7186 D ProfileConfigQcom: Adding A2dpService
08-16 13:44:46.667  7186  7186 D ProfileConfigQcom: [BTUI] HidService is supported
08-16 13:44:46.667  7186  7186 D ProfileConfigQcom: Adding HidService
08-16 13:44:46.668  7186  7186 D ProfileConfigQcom: [BTUI] HealthService is supported
08-16 13:44:46.668  7186  7186 D ProfileConfigQcom: Adding HealthService
08-16 13:44:46.668  7186  7186 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-16 13:44:46.669  7186  7186 D ProfileConfigQcom: [BTUI] PanService is supported
08-16 13:44:46.670  7186  7186 D ProfileConfigQcom: Adding PanService
08-16 13:44:46.670  7186  7186 D ProfileConfigQcom: [BTUI] GattService is supported
08-16 13:44:46.670  7186  7186 D ProfileConfigQcom: Adding GattService
08-16 13:44:46.670  7186  7186 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-16 13:44:46.670  7186  7186 D ProfileConfigQcom: Adding BluetoothMapService
08-16 13:44:46.671  7186  7186 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-16 13:44:46.672  7186  7186 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-16 13:44:46.673  7186  7186 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:44:46.673  7186  7186 V BluetoothPbapReceiver: ***********state = 10
08-16 13:44:46.675  7186  7186 V LGMDMManagerInternal: Create singleton instance
,08-16 13:44:46.712  7150  7150 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-16 13:44:46.722  7122  7122 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-16 13:44:46.719  7150  7150 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-16 13:44:46.729  7150  7150 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 13:44:46.730  7150  7150 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 13:44:46.731  7150  7150 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-16 13:44:46.734  1036  1036 D PowerManagerServiceEx: releaseWakeLockInternal: lock=439211240 [*alarm*], flags=0x0
08-16 13:44:46.738  6395  6395 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 13:44:46.747  7103  7103 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-16 13:44:46.747  7103  7103 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 13:44:46.747  7103  7103 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 13:44:46.754  7122  7122 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 13:44:46.775  7122  7122 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 13:44:46.782  7150  7150 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-16 13:44:46.782  7150  7150 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 13:44:46.783  7150  7150 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-16 13:44:46.825  1036  1904 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7234 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
08-16 13:44:46.826  7122  7122 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,08-16 13:44:46.831  2175  2175 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 13:44:46.834  1036  1904 I ActivityManager: Killing 5978:com.android.contacts/u0a19 (adj 15): empty #17
,08-16 13:44:46.849   341   341 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 387us total 17.823ms
08-16 13:44:46.866   341   341 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 300us total 16.255ms
,08-16 13:44:46.880   341   341 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 285us total 13.618ms
,08-16 13:44:46.896  1036  2033 W libprocessgroup: failed to open /acct/uid_10019/pid_5978/cgroup.procs: No such file or directory
,08-16 13:44:46.915  7122  7122 D BluetoothPermissionRequest: onReceive
,08-16 13:44:46.921  7122  7122 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-16 13:44:46.921  7122  7122 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-16 13:44:46.924  7122  7122 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-16 13:44:46.927  7186  7186 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-16 13:44:46.931  7186  7186 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-16 13:44:46.934  7186  7186 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 13:44:46.934  7186  7186 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 13:44:46.935  7186  7186 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 13:44:46.936  7186  7186 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:44:46.936  7186  7186 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
,08-16 13:44:46.945  7167  7167 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-16 13:44:47.052  1036  2033 I art     : Explicit concurrent mark sweep GC freed 52608(2MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/64MB, paused 1.301ms total 107.622ms
,08-16 13:44:47.063  7103  7103 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-16 13:44:47.071  7122  7122 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-16 13:44:47.076  7122  7122 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-16 13:44:47.081  7234  7260 W FormManager: Network not available. Please check & try again.
,08-16 13:44:47.091  7234  7261 V FormManager: Network unavailable.
,08-16 13:44:47.091  7122  7122 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-16 13:44:47.092  7122  7122 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-16 13:44:47.092  7122  7122 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-16 13:44:47.092  7122  7122 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-16 13:44:47.093  7122  7122 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-16 13:44:47.093  7234  7261 V FormManager: Network unavailable.
08-16 13:44:47.100  7122  7122 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-16 13:44:47.100  7122  7122 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-16 13:44:47.100  7122  7122 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-16 13:44:47.100  7122  7122 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-16 13:44:47.101  7122  7122 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-16 13:44:47.102  7122  7122 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-16 13:44:47.105  1036  1575 I ActivityManager: Killing 6512:com.lge.email/u0a23 (adj 15): empty #17
,08-16 13:44:47.134  1036  1903 W libprocessgroup: failed to open /acct/uid_10023/pid_6512/cgroup.procs: No such file or directory
,08-16 13:44:47.138  4740  4740 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,08-16 13:44:47.138  4740  4740 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 13:44:47.143  4740  4740 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 13:44:47.145  4740  4740 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-16 13:44:47.151  4740  7265 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 13:44:47.152  4740  7265 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-16 13:44:47.156  7103  7103 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-16 13:44:47.156  7103  7103 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 13:44:47.156  7103  7103 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 13:44:47.159  4740  7264 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-16 13:44:47.162  7122  7122 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-16 13:44:47.168  7234  7268 W FormManager: Network not available. Please check & try again.
,08-16 13:44:47.172  7122  7122 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 13:44:47.181  1036  1382 V AlarmManager: ELAPSED_WAKEUP set : Alarm{1c5bbc89 type 2 when 383845 com.google.android.gms} when 383845
08-16 13:44:47.190  7234  7269 V FormManager: Network unavailable.
,08-16 13:44:47.199  7150  7150 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-16 13:44:47.200  7234  7269 V FormManager: Network unavailable.
08-16 13:44:47.201  7150  7150 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-16 13:44:47.202  7150  7150 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,08-16 13:44:47.249  7150  7150 D LgDataFeature: LgDataFeature() Constructor: none
08-16 13:44:47.249  7150  7150 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 13:44:47.258  7150  7150 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-16 13:44:47.259  7150  7150 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-16 13:44:47.259  7150  7150 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-16 13:44:47.259  7150  7150 V SoundPool: doLoad: loading sample sampleID=1
08-16 13:44:47.260  7150  7150 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-16 13:44:47.263  7150  7272 V SoundPool: Start decode
08-16 13:44:47.264  7150  7272 V MediaPlayer[Native]: decode(31, 10857164, 17813)
,08-16 13:44:47.265   312  2154 V MediaPlayerService: decode(22, 10857164, 17813)
08-16 13:44:47.265   312  2154 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
,08-16 13:44:47.265   312  2154 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-16 13:44:47.265   312  2154 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-16 13:44:47.266   312  2154 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-16 13:44:47.266   312  2154 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-16 13:44:47.266   312  2154 V MediaPlayerService: player type = 3
08-16 13:44:47.266  7150  7150 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-16 13:44:47.266   312  2154 V AwesomePlayer: AwesomePlayer create()
08-16 13:44:47.266  6798  6798 D UEI.SmartControl: QS Service created
08-16 13:44:47.267   312  2154 V AwesomePlayer: reset_l() 
08-16 13:44:47.267   312  2154 V AwesomePlayer: cancelPlayerEvents
08-16 13:44:47.267   312  2154 V AwesomePlayer: setAudioSink() 
08-16 13:44:47.267   312  2154 V AwesomePlayer: reset_l() 
08-16 13:44:47.267   312  2154 V AudioCache: notify(0xb5474b00, 8, 0, 0)
08-16 13:44:47.267   312  2154 V AudioCache: ignored
08-16 13:44:47.267   312  2154 V AwesomePlayer: cancelPlayerEvents
08-16 13:44:47.268   312  2154 D Utils   : printFileName fd(23) -> /data/preload/LGQRemote/LGQRemote.apk
08-16 13:44:47.268   312  2154 V AwesomePlayer: setDataSource_l dataSource
08-16 13:44:47.268   312  2154 V LGParserOSAL: SniffLGParser start
08-16 13:44:47.268   312  2154 V LGParserOSAL: MainType:5, SubType=0
08-16 13:44:47.268   312  2154 V LGParserOSAL: #### check Mime : application/ogg
08-16 13:44:47.268   312  2154 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-16 13:44:47.268   312  2154 E MediaExtractor: Use LGExtractor :application/ogg 
08-16 13:44:47.270  7150  7150 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-16 13:44:47.271  7150  7150 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-16 13:44:47.300  6798  6798 I UEI.SmartControl: Service initServices...
08-16 13:44:47.301  6798  6798 D UEI.SmartControl: QS start get config
,08-16 13:44:47.303  7150  7150 V LGMDMManager: Create singleton instance
08-16 13:44:47.307   312  2154 V LGParserOSAL: supported mime: application/ogg
08-16 13:44:47.308   312  2154 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-16 13:44:47.308   312  2154 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
,08-16 13:44:47.308   312  2154 V AwesomePlayer: mBitrate = -1 bits/sec
08-16 13:44:47.308   312  2154 V AwesomePlayer: AudioTrack Setting
08-16 13:44:47.308   312  2154 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-16 13:44:47.308   312  2154 V AwesomePlayer: setAudioSource() 
08-16 13:44:47.308   312  2154 V MediaPlayerService: prepare
08-16 13:44:47.308   312  2154 V AwesomePlayer: prepareAsync_l() 
08-16 13:44:47.308   312  2154 V MediaPlayerService: wait for prepare
08-16 13:44:47.308   312  7274 V AwesomePlayer: onPrepareAsyncEvent() 
08-16 13:44:47.308   312  7274 V AwesomePlayer: initAudioDecoder() 
08-16 13:44:47.308   312  7274 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-16 13:44:47.308   312  7274 V AudioSystem: isOffloadSupported()
08-16 13:44:47.308   312  7274 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-16 13:44:47.308   312  7274 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-16 13:44:47.308   312  7274 I AudioFlinger: isAudioPlaybackHookOn() false
08-16 13:44:47.308   312  7274 V AwesomePlayer: getUseOffload() = 0 
08-16 13:44:47.308   312  7274 V OMXCodec: OMXCodec::Create
08-16 13:44:47.308   312  7274 V OMXCodec: findMatchingCodecs()
08-16 13:44:47.308   312  7274 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-16 13:44:47.308   312  7274 V OMXCodec: matchingCodecs.size()=1
08-16 13:44:47.308   312  7274 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-16 13:44:47.310   312  7274 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-16 13:44:47.310   312  7274 V LGCodecAdapter: LG Codec Adapter start
08-16 13:44:47.310   312  7274 V OMXCodec: OMXCodec Createtor
08-16 13:44:47.310   312  7274 V OMXCodec: setComponentRole
08-16 13:44:47.310   312  7274 V OMXCodec: configureCodec protected=0
08-16 13:44:47.310   312  7274 V LGCodecAdapter: called getLGCodecSpecificData
08-16 13:44:47.310   312  7274 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-16 13:44:47.310   312  7274 V LGCodecOSAL: Called LGconfigureCodecMETA
,08-16 13:44:47.310   312  7274 V LGCodecOSAL: Called LGconfigureCodecMSG
08-16 13:44:47.310   312  7274 V LGCodecOSAL: Not support LGCodec
08-16 13:44:47.310   312  7274 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-16 13:44:47.310   312  7274 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-16 13:44:47.311   312  7274 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-16 13:44:47.311   312  7274 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-16 13:44:47.311   312  7274 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-16 13:44:47.311   312  7274 V AudioSystem: isOffloadSupported()
08-16 13:44:47.311   312  7274 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-16 13:44:47.311   312  7274 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-16 13:44:47.311   312  7274 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-16 13:44:47.311   312  7274 V OMXCodec: init()
08-16 13:44:47.311   312  7274 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-16 13:44:47.311   312  7274 V OMXCodec: allocateBuffers
08-16 13:44:47.311   312  7274 V OMXCodec: allocateBuffersOnPort portIndex=0
08-16 13:44:47.311   312  7274 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-16 13:44:47.311   312  7274 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7970 on input port
08-16 13:44:47.311   312  7274 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on input port
08-16 13:44:47.311   312  7274 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on input port
08-16 13:44:47.311   312  7274 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on input port
08-16 13:44:47.311   312  7274 V OMXCodec: allocateBuffersOnPort portIndex=1
08-16 13:44:47.311   312  7274 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-16 13:44:47.311   312  7274 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d80 on output port
08-16 13:44:47.311   312  7274 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7f10 on output port
08-16 13:44:47.311   312  7274 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57ff0b0 on output port
08-16 13:44:47.311   312  7274 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57ff380 on output port
08-16 13:44:47.311   312  7274 V OMXCodec: init() mAsyncCompletion wait!!! 
08-16 13:44:47.311   312  7276 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-16 13:44:47.311   312  7276 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-16 13:44:47.311   312  7276 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-16 13:44:47.312   312  7274 V OMXCodec: init() mAsyncCompletion wait!!! 
08-16 13:44:47.312   312  7276 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-16 13:44:47.312   312  7276 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-16 13:44:47.312   312  7276 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-16 13:44:47.312   312  7274 V OMXCodec: init() mAsyncCompletion wait free! 
08-16 13:44:47.312   312  7274 V AwesomePlayer: finishAsyncPrepare_l() 
08-16 13:44:47.312   312  7274 V AudioCache: notify(0xb5474b00, 5, 0, 0)
08-16 13:44:47.312   312  7274 V AudioCache: ignored
08-16 13:44:47.312   312  7274 V AudioCache: notify(0xb5474b00, 1, 0, 0)
08-16 13:44:47.312   312  7274 V AudioCache: prepared
08-16 13:44:47.312   312  2154 V AudioCache: wait - success
,08-16 13:44:47.312   312  2154 V MediaPlayerService: start
08-16 13:44:47.312   312  2154 V AwesomePlayer: play_l() 
08-16 13:44:47.312   312  2154 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-16 13:44:47.312   312  2154 V AwesomePlayer: createAudioPlayer_l
08-16 13:44:47.312   312  2154 V AwesomePlayer: seekAudioIfNecessary_l() 
08-16 13:44:47.312   312  2154 V AwesomePlayer: startAudioPlayer_l() 
08-16 13:44:47.312   312  2154 D AudioPlayer: start of Playback, useOffload 0
08-16 13:44:47.312   312  2154 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-16 13:44:47.312   312  2154 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-16 13:44:47.314   312  7276 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-16 13:44:47.314   312  7276 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
,08-16 13:44:47.314   312  7276 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-16 13:44:47.314   312  7276 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-16 13:44:47.314   312  7276 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-16 13:44:47.314   312  7276 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-16 13:44:47.315   312  7276 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885568
08-16 13:44:47.315   312  7276 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 13:44:47.315   312  7276 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885968
08-16 13:44:47.315   312  7276 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 13:44:47.315   312  7276 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3045060784
08-16 13:44:47.315   312  7276 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 13:44:47.315   312  7276 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3045061504
08-16 13:44:47.315   312  7276 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 13:44:47.315   312  7276 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-16 13:44:47.315   312  7276 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
,08-16 13:44:47.315   312  7276 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-16 13:44:47.315   312  7276 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-16 13:44:47.315   312  7276 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-16 13:44:47.315   312  7276 V OMXCodec: allocateBuffersOnPort portIndex=1
08-16 13:44:47.315   312  7276 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-16 13:44:47.315   312  7276 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57ff0b0 on output port
08-16 13:44:47.315   312  7276 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7f10 on output port
08-16 13:44:47.315   312  7276 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d80 on output port
08-16 13:44:47.315   312  7276 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57ff6a0 on output port
08-16 13:44:47.316   312  7276 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-16 13:44:47.316   312  7276 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-16 13:44:47.317   312  2154 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-16 13:44:47.317   312  2154 V AudioCache: notify(0xb5474b00, 6, 0, 0)
08-16 13:44:47.317   312  2154 V AudioCache: ignored
08-16 13:44:47.317   312  2154 V MediaPlayerService: wait for playback complete
08-16 13:44:47.319   312  7277 V AudioCache: write(0xb178a000, 4096)
08-16 13:44:47.319   312  7277 V AudioCache: memcpy(0xaf0fc000, 0xb178a000, 4096)
,08-16 13:44:47.320   312  7277 V AudioCache: write(0xb178a000, 4096)
08-16 13:44:47.320   312  7277 V AudioCache: memcpy(0xaf0fd000, 0xb178a000, 4096)
,08-16 13:44:47.322   312  7277 V AudioCache: write(0xb178a000, 4096)
,08-16 13:44:47.322   312  7277 V AudioCache: memcpy(0xaf0fe000, 0xb178a000, 4096)
08-16 13:44:47.322   312  7277 V AudioCache: write(0xb178a000, 4096)
08-16 13:44:47.322   312  7277 V AudioCache: memcpy(0xaf0ff000, 0xb178a000, 4096)
08-16 13:44:47.322   312  7277 V AudioCache: write(0xb178a000, 4096)
08-16 13:44:47.322   312  7277 V AudioCache: memcpy(0xaf100000, 0xb178a000, 4096)
08-16 13:44:47.322   312  7277 V AudioCache: write(0xb178a000, 4096)
08-16 13:44:47.322   312  7277 V AudioCache: memcpy(0xaf101000, 0xb178a000, 4096)
08-16 13:44:47.325   312  7277 V AudioCache: write(0xb178a000, 4096)
08-16 13:44:47.325   312  7277 V AudioCache: memcpy(0xaf102000, 0xb178a000, 4096)
08-16 13:44:47.325   312  7277 V AudioCache: write(0xb178a000, 4096)
08-16 13:44:47.325   312  7277 V AudioCache: memcpy(0xaf103000, 0xb178a000, 4096)
08-16 13:44:47.325   312  7277 V AudioCache: write(0xb178a000, 4096)
,08-16 13:44:47.325   312  7277 V AudioCache: memcpy(0xaf104000, 0xb178a000, 4096)
08-16 13:44:47.326   312  7277 V AudioCache: write(0xb178a000, 4096)
08-16 13:44:47.326   312  7277 V AudioCache: memcpy(0xaf105000, 0xb178a000, 4096)
08-16 13:44:47.326   312  7277 V AudioCache: write(0xb178a000, 4096)
08-16 13:44:47.326   312  7277 V AudioCache: memcpy(0xaf106000, 0xb178a000, 4096)
08-16 13:44:47.327   312  7277 V AudioCache: write(0xb178a000, 4096)
08-16 13:44:47.327   312  7277 V AudioCache: memcpy(0xaf107000, 0xb178a000, 4096)
08-16 13:44:47.328   312  7277 V AudioCache: write(0xb178a000, 4096)
08-16 13:44:47.328   312  7277 V AudioCache: memcpy(0xaf108000, 0xb178a000, 4096)
08-16 13:44:47.328   312  7277 V AudioCache: write(0xb178a000, 4096)
08-16 13:44:47.328   312  7277 V AudioCache: memcpy(0xaf109000, 0xb178a000, 4096)
08-16 13:44:47.329   312  7277 V AudioCache: write(0xb178a000, 4096)
,08-16 13:44:47.329   312  7277 V AudioCache: memcpy(0xaf10a000, 0xb178a000, 4096)
08-16 13:44:47.330   312  7277 V AudioCache: write(0xb178a000, 4096)
08-16 13:44:47.330   312  7277 V AudioCache: memcpy(0xaf10b000, 0xb178a000, 4096)
08-16 13:44:47.330   312  7277 V AudioCache: write(0xb178a000, 4096)
08-16 13:44:47.330   312  7277 V AudioCache: memcpy(0xaf10c000, 0xb178a000, 4096)
08-16 13:44:47.331   312  7277 V AudioCache: write(0xb178a000, 4096)
08-16 13:44:47.331   312  7277 V AudioCache: memcpy(0xaf10d000, 0xb178a000, 4096)
08-16 13:44:47.332   312  7277 V AudioCache: write(0xb178a000, 4096)
08-16 13:44:47.332   312  7277 V AudioCache: memcpy(0xaf10e000, 0xb178a000, 4096)
08-16 13:44:47.332   312  7277 V AudioCache: write(0xb178a000, 4096)
08-16 13:44:47.332   312  7277 V AudioCache: memcpy(0xaf10f000, 0xb178a000, 4096)
08-16 13:44:47.333   312  7277 V AudioCache: write(0xb178a000, 4096)
08-16 13:44:47.333   312  7277 V AudioCache: memcpy(0xaf110000, 0xb178a000, 4096)
08-16 13:44:47.334   312  7277 V AudioCache: write(0xb178a000, 4096)
08-16 13:44:47.334   312  7277 V AudioCache: memcpy(0xaf111000, 0xb178a000, 4096)
08-16 13:44:47.335   312  7277 V AudioCache: write(0xb178a000, 4096)
08-16 13:44:47.335   312  7277 V AudioCache: memcpy(0xaf112000, 0xb178a000, 4096)
08-16 13:44:47.335   312  7277 V AudioCache: write(0xb178a000, 4096)
08-16 13:44:47.335   312  7277 V AudioCache: memcpy(0xaf113000, 0xb178a000, 4096)
08-16 13:44:47.336   312  7277 V AudioCache: write(0xb178a000, 4096)
08-16 13:44:47.336   312  7277 V AudioCache: memcpy(0xaf114000, 0xb178a000, 4096)
08-16 13:44:47.337   312  7277 V AudioCache: write(0xb178a000, 4096)
08-16 13:44:47.337   312  7277 V AudioCache: memcpy(0xaf115000, 0xb178a000, 4096)
08-16 13:44:47.338   312  7277 V AudioCache: write(0xb178a000, 4096)
08-16 13:44:47.338   312  7277 V AudioCache: memcpy(0xaf116000, 0xb178a000, 4096)
08-16 13:44:47.339   312  7277 V AudioCache: write(0xb178a000, 4096)
08-16 13:44:47.339   312  7277 V AudioCache: memcpy(0xaf117000, 0xb178a000, 4096)
08-16 13:44:47.339   312  7277 V AudioCache: write(0xb178a000, 4096)
08-16 13:44:47.339   312  7277 V AudioCache: memcpy(0xaf118000, 0xb178a000, 4096)
08-16 13:44:47.340   312  7277 V AudioCache: write(0xb178a000, 4096)
08-16 13:44:47.340   312  7277 V AudioCache: memcpy(0xaf119000, 0xb178a000, 4096)
08-16 13:44:47.340   312  7277 V AudioCache: write(0xb178a000, 4096)
08-16 13:44:47.340   312  7277 V AudioCache: memcpy(0xaf11a000, 0xb178a000, 4096)
08-16 13:44:47.341   312  7277 V AudioCache: write(0xb178a000, 4096)
08-16 13:44:47.341   312  7277 V AudioCache: memcpy(0xaf11b000, 0xb178a000, 4096)
08-16 13:44:47.341   312  7277 V AudioCache: write(0xb178a000, 4096)
08-16 13:44:47.341   312  7277 V AudioCache: memcpy(0xaf11c000, 0xb178a000, 4096)
08-16 13:44:47.341   312  7277 V AudioCache: write(0xb178a000, 4096)
08-16 13:44:47.341   312  7277 V AudioCache: memcpy(0xaf11d000, 0xb178a000, 4096)
08-16 13:44:47.342   312  7277 V AudioCache: write(0xb178a000, 4096)
08-16 13:44:47.342   312  7277 V AudioCache: memcpy(0xaf11e000, 0xb178a000, 4096)
08-16 13:44:47.342   312  7277 V AudioCache: write(0xb178a000, 4096)
08-16 13:44:47.342   312  7277 V AudioCache: memcpy(0xaf11f000, 0xb178a000, 4096)
08-16 13:44:47.343   312  7277 V AudioCache: write(0xb178a000, 4096)
08-16 13:44:47.343   312  7277 V AudioCache: memcpy(0xaf120000, 0xb178a000, 4096)
08-16 13:44:47.343   312  7277 V AudioCache: write(0xb178a000, 4096)
08-16 13:44:47.343   312  7277 V AudioCache: memcpy(0xaf121000, 0xb178a000, 4096)
08-16 13:44:47.344   312  7277 V AudioCache: write(0xb178a000, 4096)
08-16 13:44:47.344   312  7277 V AudioCache: memcpy(0xaf122000, 0xb178a000, 4096)
08-16 13:44:47.345   312  7277 V AudioCache: write(0xb178a000, 4096)
08-16 13:44:47.345   312  7277 V AudioCache: memcpy(0xaf123000, 0xb178a000, 4096)
08-16 13:44:47.345   312  7277 V AudioCache: write(0xb178a000, 4096)
08-16 13:44:47.345   312  7277 V AudioCache: memcpy(0xaf124000, 0xb178a000, 4096)
08-16 13:44:47.346   312  7277 V AudioCache: write(0xb178a000, 4096)
08-16 13:44:47.346   312  7277 V AudioCache: memcpy(0xaf125000, 0xb178a000, 4096)
08-16 13:44:47.347   312  7277 V AudioCache: write(0xb178a000, 4096)
08-16 13:44:47.347   312  7277 V AudioCache: memcpy(0xaf126000, 0xb178a000, 4096)
08-16 13:44:47.348   312  7277 V AudioCache: write(0xb178a000, 4096)
08-16 13:44:47.348   312  7277 V AudioCache: memcpy(0xaf127000, 0xb178a000, 4096)
08-16 13:44:47.348   312  7277 V AudioCache: write(0xb178a000, 4096)
08-16 13:44:47.348   312  7277 V AudioCache: memcpy(0xaf128000, 0xb178a000, 4096)
08-16 13:44:47.349   312  7277 V AudioCache: write(0xb178a000, 4096)
08-16 13:44:47.349   312  7277 V AudioCache: memcpy(0xaf129000, 0xb178a000, 4096)
08-16 13:44:47.350   312  7277 V AudioCache: write(0xb178a000, 4096)
08-16 13:44:47.350   312  7277 V AudioCache: memcpy(0xaf12a000, 0xb178a000, 4096)
08-16 13:44:47.350   312  7277 V AudioCache: write(0xb178a000, 4096)
08-16 13:44:47.351   312  7277 V AudioCache: memcpy(0xaf12b000, 0xb178a000, 4096)
08-16 13:44:47.351   312  7277 V AudioCache: write(0xb178a000, 4096)
08-16 13:44:47.351   312  7277 V AudioCache: memcpy(0xaf12c000, 0xb178a000, 4096)
08-16 13:44:47.352   312  7277 V AudioCache: write(0xb178a000, 4096)
08-16 13:44:47.352   312  7277 V AudioCache: memcpy(0xaf12d000, 0xb178a000, 4096)
08-16 13:44:47.352   312  7276 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-16 13:44:47.352   312  7277 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-16 13:44:47.352   312  7277 V AwesomePlayer: postAudioEOS() 
08-16 13:44:47.352   312  7277 V AudioCache: write(0xb178a000, 280)
08-16 13:44:47.352   312  7277 V AudioCache: memcpy(0xaf12e000, 0xb178a000, 280)
08-16 13:44:47.354   312  7274 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-16 13:44:47.354   312  7274 V AwesomePlayer: onStreamDone
08-16 13:44:47.354   312  7274 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-16 13:44:47.354   312  7274 V AudioCache: notify(0xb5474b00, 2, 0, 0)
08-16 13:44:47.354   312  7274 V AudioCache: playback complete
08-16 13:44:47.354   312  7274 V AwesomePlayer: pause_l() 
08-16 13:44:47.354   312  7274 V AudioCache: notify(0xb5474b00, 7, 0, 0)
08-16 13:44:47.354   312  7274 V AudioCache: ignored
08-16 13:44:47.354   312  7274 V AwesomePlayer: cancelPlayerEvents
08-16 13:44:47.354   312  2154 V AudioCache: wait - success
08-16 13:44:47.354   312  2154 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-16 13:44:47.354   312  7274 D AudioPlayer: Pause Playback at 1068125
,08-16 13:44:47.355   312  2154 V AwesomePlayer: reset_l() 
08-16 13:44:47.355   312  2154 V AudioCache: notify(0xb5474b00, 8, 0, 0)
08-16 13:44:47.355   312  2154 V AudioCache: ignored
08-16 13:44:47.355   312  2154 V AwesomePlayer: cancelPlayerEvents
08-16 13:44:47.355   312  2154 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-16 13:44:47.355   312  2154 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-16 13:44:47.355   312  2154 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-16 13:44:47.355   312  2154 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-16 13:44:47.355   312  2154 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-16 13:44:47.356   312  7276 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-16 13:44:47.356   312  7276 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-16 13:44:47.356   312  7276 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-16 13:44:47.356   312  7276 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7bf0 on port 0
08-16 13:44:47.356   312  7276 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-16 13:44:47.356   312  7276 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b00 on port 0
08-16 13:44:47.356   312  7276 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-16 13:44:47.356   312  7276 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 0
08-16 13:44:47.356   312  7276 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-16 13:44:47.356   312  7276 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7970 on port 0
08-16 13:44:47.356   312  7276 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-16 13:44:47.356   312  7276 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-16 13:44:47.356   312  7276 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57ff6a0 on port 1
08-16 13:44:47.356   312  7276 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-16 13:44:47.356   312  7276 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7d80 on port 1
08-16 13:44:47.356   312  7276 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-16 13:44:47.356   312  7276 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7f10 on port 1
08-16 13:44:47.356   312  7276 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-16 13:44:47.356   312  7276 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57ff0b0 on port 1
08-16 13:44:47.356   312  7276 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 13:44:47.357   312  7276 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-16 13:44:47.357   312  2154 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-16 13:44:47.357   312  2154 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-16 13:44:47.357   312  7276 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-16 13:44:47.357   312  7276 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-16 13:44:47.357   312  7276 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-16 13:44:47.357   312  2154 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-16 13:44:47.357   312  2154 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-16 13:44:47.357   312  2154 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-16 13:44:47.358   312  2154 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-16 13:44:47.358   312  2154 D AudioPlayer: AudioPlayer releasing audio source
08-16 13:44:47.358   312  2154 D AudioPlayer: AudioPlayer done releasing audio source
08-16 13:44:47.358   312  2154 V AwesomePlayer: reset_l() 
08-16 13:44:47.358   312  2154 V AwesomePlayer: cancelPlayerEvents
08-16 13:44:47.358   312  2154 V AwesomePlayer: ~AwesomePlayer call
08-16 13:44:47.359   312  2154 V AwesomePlayer: reset_l() 
08-16 13:44:47.359   312  2154 V AwesomePlayer: cancelPlayerEvents
08-16 13:44:47.359  7150  7272 V SoundPool: close(31)
08-16 13:44:47.359  7150  7272 V SoundPool: pointer = 0x9ffcd000, size = 205080, sampleRate = 48000, numChannels = 2
08-16 13:44:47.400  7150  7150 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-16 13:44:47.401  7150  7150 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,08-16 13:44:47.404  7150  7150 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:4698
08-16 13:44:47.410   308  7279 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-16 13:44:47.410  1036  1105 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-16 13:44:47.570  6798  6798 I UEI.SmartControl: Supports setup maps: true
,08-16 13:44:47.573  6798  6798 D UEI.SmartControl: QS start statue = true Error code = 0
08-16 13:44:47.573  6798  6798 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-16 13:44:47.573  6798  6798 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
,08-16 13:44:47.573  6798  6798 I UEI.SmartControl: ### init IR Blaster...
08-16 13:44:47.577  6798  6798 D serial_port: Configuring serial port
08-16 13:44:47.577  6798  6798 E UEI.SmartControl: UEIBLaster setting for 616
08-16 13:44:47.577  6798  6798 I UEI.SmartControl: Setting serial record hearder size = 2
08-16 13:44:47.577  6798  6798 I UEI.SmartControl: configuring settings for MAXQ616
08-16 13:44:47.577  6798  6798 I UEI.SmartControl: Get version...
08-16 13:44:47.596  6798  7280 D UEI.SmartControl: serial port data available: 21
,08-16 13:44:47.623  6798  6798 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-16 13:44:47.623  6798  6798 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-16 13:44:47.623  6798  6798 I UEI.SmartControl: QS saving settings...
08-16 13:44:47.626  6798  6798 D UEI.SmartControl: IR Blaster version: 25672567
,08-16 13:44:47.643  6798  7280 D UEI.SmartControl: serial port data available: 4
,08-16 13:44:47.684  6798  6798 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-16 13:44:47.684  6798  7289 I UEI.SmartControl: Device manager: loading config....
,08-16 13:44:47.685  6798  7289 D UEI.SmartControl: ----------- loading internal config...
,08-16 13:44:47.693  6798  6798 E UEI.SmartControl: Services init done
,08-16 13:44:47.693  6798  6798 D UEI.SmartControl: QS Service init finished
08-16 13:44:47.694  6798  6798 D UEI.SmartControl: QS Service version name: 2.1.91
08-16 13:44:47.694  6798  6798 D UEI.SmartControl: QS Service version code: 201091
08-16 13:44:47.695  6798  6798 D UEI.SmartControl: Service requested: Control
08-16 13:44:47.698  6798  7289 E UEI.SmartControl: Loading SETTINGS...
08-16 13:44:47.700  6798  6798 D UEI.SmartControl: Request IControl service: devices are loaded...
08-16 13:44:47.703  7150  7150 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
,08-16 13:44:47.706  6798  6813 I UEI.SmartControl: ------ IControl API: 11
08-16 13:44:47.706  6798  6813 D UEI.SmartControl: File observer start...
08-16 13:44:47.707  6798  6813 E UEI.SmartControl: IR Port is disabled: false
08-16 13:44:47.707  6798  6813 D UEI.SmartControl: Starting file observer...
08-16 13:44:47.708  6798  6813 I UEI.SmartControl: Registering callback...
08-16 13:44:47.709  6798  6798 D UEI.SmartControl: Internal service binding...
08-16 13:44:47.709  6798  6814 I UEI.SmartControl: ------ IControl API: 19
08-16 13:44:47.710  6798  6814 I UEI.SmartControl: Registering Services Ready callback...
08-16 13:44:47.715  6798  7289 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-16 13:44:47.743  6798  7288 I UEI.SmartControl: Notify AllClients services are ready: 0
08-16 13:44:47.744  6798  7288 D UEI.SmartControl: -----service ready thread exits
08-16 13:44:47.744  7150  7166 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
,08-16 13:44:47.745  7150  7270 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-16 13:44:47.745  7150  7270 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-16 13:44:47.746  7150  7150 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-16 13:44:47.746  7150  7150 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-16 13:44:47.747  6798  6814 I UEI.SmartControl: ------ IControl API: 8
08-16 13:44:47.751  7150  7150 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-16 13:44:47.752  7150  7150 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-16 13:44:47.753  7150  7150 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-16 13:44:47.754  7150  7150 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-16 13:44:47.755  7150  7150 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-16 13:44:47.757  7150  7150 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
,08-16 13:44:47.763  7150  7150 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-16 13:44:47.765  7150  7150 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-16 13:44:47.766  7150  7150 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-16 13:44:47.767  7150  7150 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-16 13:44:47.768  7150  7150 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-16 13:44:47.769  7150  7150 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-16 13:44:47.771  7150  7150 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-16 13:44:47.771  7150  7150 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-16 13:44:47.772  7150  7150 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1471347887772]
,08-16 13:44:47.776  7150  7150 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-16 13:44:47.781  1036  1940 I ActivityManager: Killing 6545:com.android.gallery3d/u0a27 (adj 15): empty #17
08-16 13:44:47.801  7150  7291 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-16 13:44:47.811  1036  1922 W libprocessgroup: failed to open /acct/uid_10027/pid_6545/cgroup.procs: No such file or directory
,08-16 13:44:47.817  7150  7150 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,08-16 13:44:47.818  7150  7150 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-16 13:44:47.819  7150  7150 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-16 13:44:47.819  7150  7150 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-16 13:44:47.819  7150  7150 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-16 13:44:47.820  7150  7150 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-16 13:44:47.820  7150  7150 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-16 13:44:47.829  7150  7150 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-16 13:44:48.130  1036  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 13:44:48.145  1036  1107 D Tethering: MasterInitialState.processMessage what=3
08-16 13:44:48.161  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:44:48.166  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:44:48.168  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:44:48.170  1036  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-16 13:44:48.173  1036  1107 D Tethering: MasterInitialState.processMessage what=3
08-16 13:44:48.182  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:44:48.187  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:44:48.189  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:44:48.189  1036  1092 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-16 13:44:48.191  6395  6395 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-16 13:44:48.194  6395  7102 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-16 13:44:48.206  5811  5811 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-16 13:44:48.224  5811  5811 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-16 13:44:48.248  2175  2175 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-16 13:44:48.286  1036  1092 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-16 13:44:48.324  1036  1922 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7309 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-16 13:44:48.328  1036  1092 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 13:44:48.328  1036  1092 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-16 13:44:48.401  7309  7309 I AppUp4:AppBoxCP: onCreate
08-16 13:44:48.402  7309  7309 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,08-16 13:44:48.412  7309  7309 I AppUp4:DB:  setFingerPrint start
,08-16 13:44:48.412  7309  7309 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-16 13:44:48.421  7309  7309 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
,08-16 13:44:48.421  7309  7309 I AppUp4:DB:  SDK version = 21
,08-16 13:44:48.421  7309  7309 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-16 13:44:48.424  7309  7309 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-16 13:44:48.426  7309  7309 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-16 13:44:48.426  7309  7309 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,08-16 13:44:48.428  7309  7309 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-16 13:44:48.429  7309  7309 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-16 13:44:48.436  7309  7309 I AppUp4:CustModeStarterReceiver: onReceive
,08-16 13:44:48.478  7309  7309 D LgDataFeature: LgDataFeature() Constructor: none
,08-16 13:44:48.478  7309  7309 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 13:44:48.487  7309  7309 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@166647fb
08-16 13:44:48.487  7309  7309 D AppUp4:CustFacade: isCustomizationCompleted : false
08-16 13:44:48.487  7309  7309 D AppUp4:CustFacade: isPhone : true
08-16 13:44:48.488  7309  7309 D AppUp4:CustModeStarterReceiver: begin check event
08-16 13:44:48.490  7309  7309 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-16 13:44:48.490  7309  7309 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-16 13:44:48.491  7309  7329 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-16 13:44:48.492  7309  7329 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-16 13:44:48.492  7309  7329 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-16 13:44:48.494  1036  1646 I ActivityManager: Killing 2127:com.lge.music/u0a34 (adj 15): empty #17
08-16 13:44:48.524   312  1385 V AudioFlinger: 2127 died, releasing its sessions
08-16 13:44:48.525   312  1385 V AudioFlinger:  pid 1851 @ 0
08-16 13:44:48.525   312  1385 V AudioFlinger:  pid 3309 @ 1
08-16 13:44:48.525   312  1385 V AudioFlinger:  pid 3309 @ 2
,08-16 13:44:48.552  4740  4740 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-16 13:44:48.553  1036  1755 W libprocessgroup: failed to open /acct/uid_10034/pid_2127/cgroup.procs: No such file or directory
,08-16 13:44:48.553  4740  4740 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 13:44:48.558  4740  4740 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 13:44:48.563  4740  4740 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 13:44:48.572  4740  7333 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-16 13:44:48.580  4740  7334 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-16 13:44:48.580  4740  7334 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-16 13:44:48.663  1036  1052 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7338 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-16 13:44:48.747  7338  7338 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-16 13:44:48.748  7338  7338 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-16 13:44:48.750  7338  7338 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-16 13:44:48.751  7338  7338 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-16 13:44:48.849  7338  7338 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-16 13:44:48.873  7338  7338 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-16 13:44:48.915  7338  7338 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-16 13:44:48.953  7338  7338 D LgDataFeature: LgDataFeature() Constructor: none
,08-16 13:44:48.954  7338  7338 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 13:44:49.091  7338  7338 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-16 13:44:49.149  3309  3309 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-16 13:44:49.149  3309  3309 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
,08-16 13:44:49.154  3309  3309 I LgeMiscReceiver: networkInfo.isConnected() = false
08-16 13:44:49.157  7338  7338 I HubEmail: JNI_OnLoad()
08-16 13:44:49.157  7338  7338 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-16 13:44:49.158  7338  7338 I HubEmail: registerNatives()
08-16 13:44:49.158  7338  7338 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-16 13:44:49.158  7338  7338 I HubEmail: registerNativeMethods()
08-16 13:44:49.158  7338  7338 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-16 13:44:49.158  7338  7338 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
08-16 13:44:49.206  1036  1904 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7368 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-16 13:44:49.217  7338  7367 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:44:49.232  7234  7366 V FormManager: Network unavailable.
,08-16 13:44:49.236  7234  7365 W FormManager: Network not available. Please check & try again.
08-16 13:44:49.236  7234  7366 V FormManager: Network unavailable.
08-16 13:44:49.245  1036  2032 I ActivityManager: Killing 6615:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,08-16 13:44:49.344  1036  1052 W libprocessgroup: failed to open /acct/uid_10061/pid_6615/cgroup.procs: No such file or directory
,08-16 13:44:49.451  7368  7368 D LgDataFeature: LgDataFeature() Constructor: none
08-16 13:44:49.451  7368  7368 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 13:44:49.455  7368  7368 D PhoneMonitor: Register our PhoneStateListener
,08-16 13:44:49.480  7368  7368 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-16 13:44:49.485  7368  7368 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-16 13:44:49.518  7368  7368 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,08-16 13:44:49.519  7368  7368 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
,08-16 13:44:49.521  7368  7368 D TelephonyAutoProfiling: [parse] Load xml
,08-16 13:44:49.530  7368  7368 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-16 13:44:49.533  7368  7368 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-16 13:44:49.533  7368  7368 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-16 13:44:49.533  7368  7368 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-16 13:44:49.533  7368  7368 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-16 13:44:49.533  7368  7368 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-16 13:44:49.533  7368  7368 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-16 13:44:49.533  7368  7368 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-16 13:44:49.534  7368  7368 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-16 13:44:49.534  7368  7368 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-16 13:44:49.534  7368  7368 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-16 13:44:49.534  7368  7368 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-16 13:44:49.534  7368  7368 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-16 13:44:49.534  7368  7368 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-16 13:44:49.534  7368  7368 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-16 13:44:49.534  7368  7368 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-16 13:44:49.535  7368  7368 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-16 13:44:49.553  7368  7368 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-16 13:44:49.576  1036  1051 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7403 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-16 13:44:49.577  1036  1051 I ActivityManager: Killing 6675:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,08-16 13:44:49.672  1036  1958 W libprocessgroup: failed to open /acct/uid_10080/pid_6675/cgroup.procs: No such file or directory
,08-16 13:44:49.957  1036  1958 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7427 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,08-16 13:44:49.965  1036  1958 I ActivityManager: Killing 6745:com.lge.eula/1000 (adj 15): empty #17
08-16 13:44:50.021  1036  1093 W ProcessCpuTracker: Skipping unknown process pid 7296
,08-16 13:44:50.024  1036  1093 W ProcessCpuTracker: Skipping unknown process pid 7297
08-16 13:44:50.024  1036  1093 W ProcessCpuTracker: Skipping unknown process pid 7307
08-16 13:44:50.025  1036  1093 W ProcessCpuTracker: Skipping unknown process pid 7326
08-16 13:44:50.027  1036  1093 W ProcessCpuTracker: Skipping unknown process pid 7375
08-16 13:44:50.027  1036  1093 W ProcessCpuTracker: Skipping unknown process pid 7376
08-16 13:44:50.027  1036  1093 W ProcessCpuTracker: Skipping unknown process pid 7382
08-16 13:44:50.028  1036  1093 W ProcessCpuTracker: Skipping unknown process pid 7396
08-16 13:44:50.028  1036  1093 W ProcessCpuTracker: Skipping unknown process pid 7421
08-16 13:44:50.029  1036  1093 W ProcessCpuTracker: Skipping unknown process pid 7424
08-16 13:44:50.057  1036  1537 D LGWifiP2pService: P2pDisabledState{ when=-5ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:44:50.057  1036  1537 D LGWifiP2pService: DefaultState{ when=-5ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 13:44:50.083  1036  1755 W libprocessgroup: failed to open /acct/uid_1000/pid_6745/cgroup.procs: No such file or directory
08-16 13:44:50.086  1036  1994 D WifiServiceImplEx: setWifiEnabled: true pid=6936, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-16 13:44:50.086  1036  1994 D WifiService: setWifiEnabled: true pid=6936, uid=10118
08-16 13:44:50.086  1036  1994 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-16 13:44:50.100  1036  1538 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-16 13:44:50.100  1036  1538 I LGFTMITEM: [GET_FTM][id=6], offset=12288
,08-16 13:44:50.103  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 13:44:50.104  1036  1538 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-16 13:44:50.104  1036  1538 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-16 13:44:50.104  1036  1538 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-16 13:44:50.104  1036  1538 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-16 13:44:50.104  1036  1538 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-16 13:44:50.104  1036  1538 E WifiHW  : unknown target_country: EU , set to default
08-16 13:44:50.104  1036  1538 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-16 13:44:50.104  1036  1538 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-16 13:44:50.104  1036  1538 I WifiUtil: gEnableBmps=1
08-16 13:44:50.105  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 13:44:50.105  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-16 13:44:50.268  1036  2032 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7453 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-16 13:44:50.268  1036  2032 I ActivityManager: Killing 6766:com.lge.bnr/1000 (adj 15): empty #17
,08-16 13:44:50.361  1036  1940 W libprocessgroup: failed to open /acct/uid_1000/pid_6766/cgroup.procs: No such file or directory
,08-16 13:44:50.419  7453  7453 I art     : Almond Protected OAT
,08-16 13:44:50.481  7453  7453 D WeatherApplication: removeAccount
,08-16 13:44:50.484  7453  7453 D WeatherApplication: Account.length = 0
,08-16 13:44:50.485  7453  7453 E WeatherApplication: OPERATOR:OPEN
08-16 13:44:50.497  7453  7453 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:44:50
,08-16 13:44:50.508  7453  7453 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-16 13:44:50.508  7453  7453 D Weather.Utils: 2 : All the weather widget is gone.
08-16 13:44:50.510  7453  7453 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-16 13:44:50.513  7453  7453 D WeatherAncestor: connectivity changed - connection : true
,08-16 13:44:50.514  7453  7453 D WeatherService: 2 : isServiceAlived():false forecastCache:null
,08-16 13:44:50.527  7453  7453 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-16 13:44:50.527  7453  7453 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-16 13:44:50.527  7453  7453 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
,08-16 13:44:50.554  7453  7453 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-16 13:44:50.555  7453  7453 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:44:50
,08-16 13:44:50.641  1036  1904 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7487 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-16 13:44:50.642  1036  1904 I ActivityManager: Killing 6714:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,08-16 13:44:50.720  1036  1922 W libprocessgroup: failed to open /acct/uid_10097/pid_6714/cgroup.procs: No such file or directory
,08-16 13:44:50.855   308   895 D SoftapController: Softap fwReload - Ok
08-16 13:44:50.858  1036  1107 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-16 13:44:50.859  1036  1107 D Tethering: InitialState.processMessage what=4
08-16 13:44:50.861  1036  1107 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-16 13:44:50.865  1036  1538 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (755ms)
08-16 13:44:50.869   308   895 D CommandListener: Setting iface cfg
08-16 13:44:50.870   308   895 D CommandListener: Trying to bring down wlan0
,08-16 13:44:50.872   308   895 D CommandListener: Clearing all IP addresses on wlan0
08-16 13:44:50.874  1036  1538 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-16 13:44:50.873  7511  7511 W wpa_supplicant: type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-16 13:44:50.873  7511  7511 W wpa_supplicant: type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 13:44:50.888  1036  1538 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 13:44:50.888  1036  1538 E WifiStateMachine: useWiFiOffloading() : false
08-16 13:44:50.888  1036  1538 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-16 13:44:50.894  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-16 13:44:50.901  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 13:44:50.914  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:44:50.914  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-16 13:44:50.915  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:44:50.915  1036  1538 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-16 13:44:50.915  1036  1538 D WifiMonitor: connecting to supplicant
08-16 13:44:50.922  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:44:50.934  7511  7511 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-16 13:44:50.939   278   371 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-16 13:44:50.939   278   371 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-16 13:44:50.939   278   371 W Vold    : Returning OperationFailed - no handler for errno 0
08-16 13:44:50.939  7487  7524 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-16 13:44:50.941   278   371 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-16 13:44:50.941   278   371 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-16 13:44:50.941   278   371 W Vold    : Returning OperationFailed - no handler for errno 0
08-16 13:44:50.942  7487  7524 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-16 13:44:50.960   278   371 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-16 13:44:50.960   278   371 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-16 13:44:50.960   278   371 W Vold    : Returning OperationFailed - no handler for errno 0
,08-16 13:44:50.961  7487  7526 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,08-16 13:44:50.964   278   371 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-16 13:44:50.964   278   371 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-16 13:44:50.964   278   371 W Vold    : Returning OperationFailed - no handler for errno 0
08-16 13:44:50.965  7487  7526 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-16 13:44:50.968  7511  7511 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-16 13:44:50.968  7511  7511 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
08-16 13:44:51.064  7511  7511 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-16 13:44:51.123  7511  7511 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-16 13:44:51.129  7511  7511 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
,08-16 13:44:51.130  1036  1538 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-16 13:44:51.131  1036  1538 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-16 13:44:51.131  7511  7511 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-16 13:44:51.131  1036  1538 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-16 13:44:51.132  1036  1538 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-16 13:44:51.132  1036  1538 E WifiStateMachine:  SupplicantStartingState CMD_STOP_SUPPLICANT_FAILED 1 0
08-16 13:44:51.133  1036  1538 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
08-16 13:44:51.133  1036  1538 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-16 13:44:51.133  1036  7543 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-16 13:44:51.133  1036  7543 D WifiMonitor: Dropping event because (p2p0) is stopped
08-16 13:44:51.134  1036  1538 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-16 13:44:51.134  1036  7543 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-16 13:44:51.134  1036  7543 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-16 13:44:51.134  1036  1538 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-16 13:44:51.134  1036  7543 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-16 13:44:51.134  1036  7543 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-16 13:44:51.134  1036  7543 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-16 13:44:51.134  1036  1538 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 13:44:51.134  1036  7543 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-16 13:44:51.135  1036  1538 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-16 13:44:51.135  1036  1538 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-16 13:44:51.135  1036  1538 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-16 13:44:51.136  1036  1538 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-16 13:44:51.136  1036  1538 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-16 13:44:51.137  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:44:51.137  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:44:51.138  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:44:51.138  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:44:51.138  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 13:44:51.138  1036  1538 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 13:44:51.138  1036  1538 E WifiStateMachine: useWiFiOffloading() : false
08-16 13:44:51.138  1036  1538 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-16 13:44:51.140  1036  1538 D WifiNative-wlan0: doBoolean: SET update_config 1
08-16 13:44:51.140  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 13:44:51.141  1941  1941 D WfdService: Waiting for WifiP2p enabling
08-16 13:44:51.141  1036  1538 D WifiNative-wlan0: SET update_config 1: returned true
08-16 13:44:51.141  1036  1538 D WifiConfigStore: Loading config and enabling all networks 
08-16 13:44:51.141  1036  1538 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-16 13:44:51.143  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-16 13:44:51.143  1036  1542 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-16 13:44:51.148  1036  1538 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-16 13:44:51.149  6936  6936 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:44:51.149  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:44:51.149  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:44:51.149  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 13:44:51.149  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:44:51.149  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 13:44:51.149  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 13:44:51.149  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 13:44:51.149  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 13:44:51.150  6936  6936 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:44:51.150  6936  6936 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 13:44:51.151  6936  6936 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:44:51.151  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:44:51.151  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:44:51.151  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 13:44:51.151  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:44:51.151  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 13:44:51.151  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 13:44:51.151  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 13:44:51.151  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 13:44:51.151  6936  6936 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:44:51.151  6936  6936 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 13:44:51.152  6936  6936 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:44:51.152  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:44:51.152  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi D,irect supported: true
08-16 13:44:51.152  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 13:44:51.152  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:44:51.152  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 13:44:51.152  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 13:44:51.152  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 13:44:51.152  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 13:44:51.152  6936  6936 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:44:51.152  6936  6936 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 13:44:51.154  1036  1538 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
,08-16 13:44:51.165  1036  1538 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-16 13:44:51.166  1036  1538 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-16 13:44:51.166  1036  1538 D WifiStateMachine: enableVerboseLogging : level 2
08-16 13:44:51.166  1036  1538 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-16 13:44:51.167  1036  1538 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-16 13:44:51.167  1036  1538 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-16 13:44:51.167  1036  1538 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-16 13:44:51.167  1036  1538 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
,08-16 13:44:51.168  1036  1538 D WifiNative-wlan0: SET model_name LG-D855: returned true
,08-16 13:44:51.168  1036  1538 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-16 13:44:51.168  1036  1538 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-16 13:44:51.169  1036  1538 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-16 13:44:51.169  1036  1538 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-16 13:44:51.169  1036  1538 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-16 13:44:51.169  1036  1538 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-16 13:44:51.169  1036  1538 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-16 13:44:51.170  1036  1538 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-16 13:44:51.170  1036  1538 D WifiStateMachine: Setting OUI to DA-A1-19
08-16 13:44:51.170  1036  1538 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-16 13:44:51.170  1036  1538 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-16 13:44:51.170  1036  1538 D WifiNative-HAL: Setting external_sim to 1
08-16 13:44:51.170  1036  1538 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-16 13:44:51.171  1036  1538 D WifiNative-wlan0: SET external_sim 1: returned true
08-16 13:44:51.171  1036  1538 I WifiNative-HAL: startHal
08-16 13:44:51.171  1036  1538 D wifi    : setting scan oui 0xaf6dae60
08-16 13:44:51.171  1036  1538 D WifiStateMachine: Setting OUI to DA-A1-19
08-16 13:44:51.171  1036  1538 I WifiNative-HAL: startHal
08-16 13:44:51.171  1036  1538 D wifi    : setting scan oui 0xaf6dae60
08-16 13:44:51.171  1036  1538 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-16 13:44:51.171  1036  1538 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-16 13:44:51.171  1036  1538 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-16 13:44:51.172  7511  7511 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-16 13:44:51.172  1941  1941 D WfdsService: Supplicant Connection state is changed : true
08-16 13:44:51.172  1036  1538 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-16 13:44:51.172  1941  2315 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-16 13:44:51.172  1941  2315 D WfdsService: Set the WFDS Monitor: true
08-16 13:44:51.172  1941  2315 D WfdsMonitor: WfdsMonitorThread create
08-16 13:44:51.172  1941  2315 D WfdsMonitor: WFDS Monitor is created and started
08-16 13:44:51.172  1941  2315 D WfdsService: WiFi: Supplicant connection re-established
08-16 13:44:51.172  1036  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-16 13:44:51.172  7511  7511 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-16 13:44:51.172  1036  1538 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-16 13:44:51.172  1036  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-16 13:44:51.173  7511  7511 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-16 13:44:51.173  1941  7545 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-16 13:44:51.173  1036  1538 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-16 13:44:51.173  1036  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-16 13:44:51.173  7511  7511 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-16 13:44:51.173  1036  1538 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-16 13:44:51.173  1036  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-16 13:44:51.173  7511  7511 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-16 13:44:51.173  1941  7545 E CtrlSupplicant: Succeed to open control connection
08-16 13:44:51.173  1036  1538 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-16 13:44:51.173  1036  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-16 13:44:51.173  1941  7545 E CtrlSupplicant: Succeed to open monitor connection
08-16 13:44:51.173  7511  7511 I wpa_supplicant: android_multicast_filter_startstop : mu,lticast filter set
08-16 13:44:51.174  1941  7545 D WfdsMonitor: Supplicant connection established
08-16 13:44:51.174  1941  2315 D WfdsService: Connected to the supplicant for wfds
08-16 13:44:51.174  1036  1538 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-16 13:44:51.174  1036  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-16 13:44:51.174  7511  7511 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-16 13:44:51.174  1036  1538 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-16 13:44:51.175  1036  1538 E WifiNative: : [387,843,844 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-16 13:44:51.175  1036  1538 D WifiNative-wlan0: doBoolean: RECONNECT
08-16 13:44:51.175  1036  1538 D WifiNative-wlan0: RECONNECT: returned true
08-16 13:44:51.175  1036  1538 D WifiNative-wlan0: doString: [STATUS]
08-16 13:44:51.175  1036  7543 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-16 13:44:51.175  1036  1538 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-16 13:44:51.175  1036  7543 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-16 13:44:51.175  1036  1538 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 13:44:51.176  1036  1538 D WifiNative-wlan0: SET ps 1: returned true
08-16 13:44:51.176  1036  1537 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:44:51.176  1036  1538 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-16 13:44:51.177  1036  1538 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-16 13:44:51.177  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 3
08-16 13:44:51.177  1036  1036 D RttService: SCAN_AVAILABLE : 3
08-16 13:44:51.177  1036  1538 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-16 13:44:51.177  1036  1556 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:44:51.177  1036  1556 I WifiNative-HAL: startHal
08-16 13:44:51.177  1036  1556 D wifi    : getting scan capabilities on interface[1] = 0xaf6dae60
08-16 13:44:51.177  1036  1538 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-16 13:44:51.177  1036  1556 D wifi    : failed to get capabilities : -3
08-16 13:44:51.177  1036  1556 E WifiScanningService: could not get scan capabilities
08-16 13:44:51.177  1036  1557 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:44:51.178  1036  1538 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=387847  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-16 13:44:51.178   308   895 D CommandListener: Setting iface cfg
,08-16 13:44:51.178   308   895 D CommandListener: Trying to bring up p2p0
08-16 13:44:51.178  1036  1537 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-16 13:44:51.178  1036  1537 D LGWifiP2pService: P2pEnablingState
08-16 13:44:51.178  1036  1537 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:44:51.178  1036  1537 D LGWifiP2pService: P2p socket connection successful
08-16 13:44:51.178  1036  1537 D LGWifiP2pService: P2pEnabledState
,08-16 13:44:51.181  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 13:44:51.181  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 13:44:51.181  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:44:51.181  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:44:51.181  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-16 13:44:51.181  1036  1537 D LGWifiP2pService: sending p2p connection changed broadcast
08-16 13:44:51.182  1036  1537 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-16 13:44:51.183  1036  1537 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-16 13:44:51.183  1036  1537 D WifiNative-p2p0: doBoolean: SET device_name G3
08-16 13:44:51.183  1036  1537 D WifiNative-p2p0: SET device_name G3: returned true
08-16 13:44:51.183  1036  1537 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-16 13:44:51.183  1036  1537 D LGWifiP2pService: before postfix = G3
08-16 13:44:51.183  1036  1537 D WifiServerServiceExt: postfix byte check : 2
08-16 13:44:51.183  1036  1537 D LGWifiP2pService: after postfix = G3
08-16 13:44:51.183  1036  1537 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-16 13:44:51.183  1036  1537 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-16 13:44:51.183  1036  1537 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-16 13:44:51.184  1036  1537 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-16 13:44:51.184  1036  1537 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-16 13:44:51.184  1036  1537 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-16 13:44:51.184  1036  1537 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
,08-16 13:44:51.184  1036  1537 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-16 13:44:51.184  1036  1537 D WifiNative-HAL: p2pGetDeviceAddress
08-16 13:44:51.184  1036  1537 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-16 13:44:51.185  1036  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=387854  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-16 13:44:51.185  1036  1538 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-16 13:44:51.185  1036  1538 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-16 13:44:51.186  1036  1538 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-16 13:44:51.186  1036  1538 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-16 13:44:51.186  7511  7511 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-16 13:44:51.186  1036  1538 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-16 13:44:51.186  1036  1538 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-16 13:44:51.187  1036  1538 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-16 13:44:51.187  1036  1538 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-16 13:44:51.187  7511  7511 E wpa_supplicant: disconnect_rssi_lvl: -100
08-16 13:44:51.187  1036  1538 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-16 13:44:51.187  1036  1538 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-16 13:44:51.188  1036  1538 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-16 13:44:51.188  1036  1538 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-16 13:44:51.188  7511  7511 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-16 13:44:51.188  7511  7511 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 13:44:51.189  1036  7543 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
,08-16 13:44:51.189  1036  7543 E WifiMonitor: WifiMonitor:wlan0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 13:44:51.189  1036  7543 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 13:44:51.189  1036  7543 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 13:44:51.189  7511  7511 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-16 13:44:51.189  7511  7511 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 13:44:51.189  1941  7545 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 13:44:51.189  1036  7543 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 13:44:51.189  1036  7543 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 13:44:51.189  1036  7543 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 13:44:51.189  1036  7543 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 13:44:51.190  7511  7511 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 13:44:51.190  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-16 13:44:51.190  1941  1941 D WfdsService: WifiP2pState is changed : true
08-16 13:44:51.191  1941  2315 D WfdsService: Receive the WFDS_ENABLE Method
08-16 13:44:51.191  1941  2315 D WfdsService: Set the WFDS Monitor: true
08-16 13:44:51.191  1941  7545 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 13:44:51.191  1941  2315 D WfdsService: Connected to the supplicant for wfds
08-16 13:44:51.191  1941  2315 D WfdsJNI : doCommand: WFDS_SET TRUE
08-16 13:44:51.191  1036  7543 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 13:44:51.191  1036  7543 E WifiMonitor: WifiMonitor:p2p0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 13:44:51.191  7511  7511 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-16 13:44:51.191  1036  7543 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 13:44:51.191  1036  7543 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 13:44:51.191  1941  2315 D WfdsJNI : doCommand: WFDS_GET_MAC_ADDRESS
08-16 13:44:51.191  7511  7511 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = GET_MAC_ADDRESS
08-16 13:44:51.191  1941  1941 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-16 13:44:51.191  1036  1537 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-16 13:44:51.191  1036  1537 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-16 13:44:51.192  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 13:44:51.192  1941  1941 D WfdsService: isConnected: false
08-16 13:44:51.192  1941  2315 D WfdsJNI : doCommand: IFNAME=wlan0 GET_CAPABILITY channels
08-16 13:44:51.193  1036  1538 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-16 13:44:51.193  1036  1537 D WifiNative-p2p0: P2P_FLUSH: returned true
08-16 13:44:51.193  1036  1537 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
,08-16 13:44:51.193  1036  1537 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-16 13:44:51.193  1036  1537 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-16 13:44:51.193  1941  2315 D WfdsService: selectPreferredScanChannel [36]
08-16 13:44:51.193  1036  1537 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-16 13:44:51.194  1036  1537 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-16 13:44:51.193  1941  2315 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-16 13:44:51.194  1941  1941 I WfdStateTracker: handleP2pThisDeviceChanged
08-16 13:44:51.194  1941  1941 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-16 13:44:51.194  1941  1941 D WfdsService: Update P2p Interface State: 3
,08-16 13:44:51.194  1036  1538 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-16 13:44:51.195  1036  1538 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-16 13:44:51.195  1036  1538 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-16 13:44:51.195  1036  1538 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-16 13:44:51.207  1036  1537 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-16 13:44:51.207  1036  1537 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-16 13:44:51.207  1036  1537 D LGWifiP2pService: InactiveState
08-16 13:44:51.207  1036  1537 D LGWifiP2pService: InactiveState{ when=-13ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:44:51.207  1036  1537 D LGWifiP2pService: P2pEnabledState{ when=-13ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:44:51.207  1036  1537 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-16 13:44:51.208  7511  7511 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-16 13:44:51.208  7511  7511 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 13:44:51.208  1941  7545 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-16 13:44:51.208  1036  7543 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-16 13:44:51.208  1036  7543 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 13:44:51.208  1036  7543 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 13:44:51.208  1036  7543 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 13:44:51.209  7511  7511 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-16 13:44:51.209  7511  7511 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 13:44:51.209  1941  7545 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 13:44:51.209  1036  7543 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 13:44:51.209  1036  7543 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 13:44:51.209  1036  7543 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 13:44:51.209  1036  7543 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 13:44:51.209  7511  7511 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 13:44:51.210  1941  7545 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,08-16 13:44:51.210  1036  7543 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 13:44:51.210  1036  7543 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 13:44:51.210  1036  7543 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 13:44:51.210  1036  7543 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 13:44:51.210  1036  1537 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-16 13:44:51.210  7511  7511 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-16 13:44:51.210  7511  7511 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 13:44:51.211  1036  7543 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-16 13:44:51.211  1036  7543 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 13:44:51.211  1036  7543 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 13:44:51.211  1036  7543 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 13:44:51.211  1036  1537 D LGWifiP2pService: InactiveState{ when=-17ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:44:51.211  1036  1538 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-16 13:44:51.211  1036  1537 D LGWifiP2pService: P2pEnabledState{ when=-17ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:44:51.211  1036  1538 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-16 13:44:51.211  1036  1537 D LGWifiP2pService: InactiveState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:44:51.211  1036  1537 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:44:51.211  1036  1537 D LGWifiP2pService: DefaultState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:44:51.211  1036  1537 D LGWifiP2pService: InactiveState{ when=-5ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:44:51.211  1036  1537 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:44:51.211  1036  1537 D LGWifiP2pService: DefaultState{ when=-5ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:44:51.212  1036  1537 D LGWifiP2pService: InactiveState{ when=-2ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:44:51.212  1036  1537 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:44:51.212  1036  1537 D LGWifiP2pService: DefaultState{ when=-2ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:44:51.212  1036  1537 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:44:51.212  1036  1537 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:44:51.212  1036  1537 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:44:51.212  1941  2315 W WfdsService: DefaultState - msg [9441285] is not handled
08-16 13:44:51.212  1036  1538 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-16 13:44:51.212  1036  1538 D WifiNative-wlan0: doBoolean: SCAN
08-16 13:44:51.212  7487  7487 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
08-16 13:44:51.212  1036  1538 D WifiNative-wlan0: SCAN: returned false
08-16 13:44:51.213  1036  1538 E WifiStateMachine:  DisconnectedState ,SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=387882  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-16 13:44:51.213  1036  1036 E WifiServerServiceExt: No p2p device connected
08-16 13:44:51.214  1036  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=387883  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-16 13:44:51.214  1036  1538 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 13:44:51.215  1036  1538 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 13:44:51.215  1036  1538 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 13:44:51.216  1036  1538 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 13:44:51.216  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:44:51.216  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:44:51.216  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-16 13:44:51.216  1036  1538 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 13:44:51.216  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 13:44:51.216  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 13:44:51.216  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 13:44:51.216  1036  1036 D WifiServerServiceExt: setSupplicantStateSCANNING
08-16 13:44:51.217  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 13:44:51.218  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 13:44:51.218  1036  1036 D WifiServerServiceExt: setSupplicantStateSCANNING
08-16 13:44:51.219  7487  7487 I LibraryLoader: Loading: webviewchromium
08-16 13:44:51.222  7487  7487 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 7899-7902)
08-16 13:44:51.222  7487  7487 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-16 13:44:51.227  7487  7487 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {e69b7f4}
,08-16 13:44:51.228  7487  7487 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 13:44:51.228  7487  7487 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-16 13:44:51.239  7487  7487 I BrowserStartupController: Initializing chromium process, renderers=0
,08-16 13:44:51.241  7487  7487 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-16 13:44:51.249  7487  7487 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-16 13:44:51.250  7487  7487 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-16 13:44:51.251  7487  7487 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-16 13:44:51.251   312  1386 V AudioPolicyService: registerClient() client 0xb558a3e0, uid 10093
08-16 13:44:51.252  7487  7551 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-16 13:44:51.266  7487  7487 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 13:44:51.266  7487  7487 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 13:44:51.266  7487  7487 I Adreno-EGL: Build Date: 12/12/14 금
08-16 13:44:51.266  7487  7487 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 13:44:51.266  7487  7487 I Adreno-EGL: Remote Branch: 
08-16 13:44:51.266  7487  7487 I Adreno-EGL: Local Patches: 
08-16 13:44:51.266  7487  7487 I Adreno-EGL: Reconstruct Branch: 
,08-16 13:44:51.349  7487  7487 I NSApplication: Starting up...
,08-16 13:44:51.430  1036  1052 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7564 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-16 13:44:51.431  1036  1052 I ActivityManager: Killing 6568:com.android.vending/u0a44 (adj 15): empty #17
08-16 13:44:51.504  1036  1885 W libprocessgroup: failed to open /acct/uid_10044/pid_6568/cgroup.procs: No such file or directory
,08-16 13:44:51.554  7564  7564 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-16 13:44:51.778  1036  7543 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-16 13:44:51.778  1036  7543 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-16 13:44:51.778  1036  7543 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-16 13:44:51.779  1036  7543 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: WPS-AP-AVAILABLE 
08-16 13:44:51.779  1036  7543 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-16 13:44:51.779  7511  7511 E wpa_supplicant: USIM:  scard_init function
,08-16 13:44:51.780  1036  1538 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=6 bcn=0
08-16 13:44:51.782  1036  1538 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=6 bcn=0
08-16 13:44:51.783  1036  1538 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=6 bcn=0
08-16 13:44:51.783  7511  7511 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-16 13:44:51.784  1036  1538 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=6 bcn=0
08-16 13:44:51.784  1036  1538 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-16 13:44:51.785  1036  7543 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-16 13:44:51.786  1036  7543 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-16 13:44:51.801  1036  1538 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=388470  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-16 13:44:51.803  1036  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=388472  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-16 13:44:51.804  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:44:51.804  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:44:51.805  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-16 13:44:51.805  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 13:44:51.805  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-16 13:44:51.810  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 13:44:51.813  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 13:44:51.813  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-16 13:44:51.866  6395  6395 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-16 13:44:51.869  6395  7102 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-16 13:44:51.882  2175  2175 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-16 13:44:51.893  7309  7309 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
,08-16 13:44:51.893  7309  7309 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-16 13:44:51.893  7309  7309 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-16 13:44:51.893  7309  7309 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-16 13:44:51.898  7511  7511 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-16 13:44:51.898  1036  7543 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-16 13:44:51.898  1036  7543 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-16 13:44:51.898  1036  7543 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-16 13:44:51.899  1036  1538 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=388568  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-16 13:44:51.900  1036  7543 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-16 13:44:51.900  1036  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=388568  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-16 13:44:51.900  1036  7543 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 13:44:51.900  1036  7543 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 13:44:51.901  1036  1538 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=388570
08-16 13:44:51.901  1036  1538 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=388570
08-16 13:44:51.902  1036  1538 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=388571
08-16 13:44:51.902  7309  7309 I AppUp4:CustModeStarterReceiver: onReceive
08-16 13:44:51.902  1036  1538 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=388571
08-16 13:44:51.903  1036  1107 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-16 13:44:51.906  1036  1538 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=388576
08-16 13:44:51.907  7511  7511 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 13:44:51.907  7511  7511 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-16 13:44:51.909  1036  7543 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 13:44:51.909  1036  7543 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 13:44:51.910  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 13:44:51.910  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-16 13:44:51.910  1036  7543 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-16 13:44:51.910  1036  7543 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 13:44:51.910  1036  7543 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 13:44:51.910  1036  7543 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-16 13:44:51.910  1036  7543 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-16 13:44:51.911  1036  7543 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-16 13:44:51.911  1036  7543 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 13:44:51.911  1036  7543 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 13:44:51.911  1036  1538 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=388580  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-16 13:44:51.913  7309  7309 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@166647fb
08-16 13:44:51.913  7309  7309 D AppUp4:CustFacade: isCustomizationCompleted : false
08-16 13:44:51.913  7309  7309 D AppUp4:CustFacade: isPhone : true
08-16 13:44:51.913  7309  7309 D AppUp4:CustModeStarterReceiver: begin check event
08-16 13:44:51.914  7309  7309 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
,08-16 13:44:51.918  4740  4740 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-16 13:44:51.919  4740  4740 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 13:44:51.919  1036  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=388588  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
,08-16 13:44:51.922  4740  4740 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 13:44:51.925  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 13:44:51.925  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 13:44:51.925  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:44:51.925  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:44:51.925  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-16 13:44:51.926  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 13:44:51.930  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:44:51.930  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:44:51.930  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-16 13:44:51.931  1036  1538 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
08-16 13:44:51.933  1036  1538 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-16 13:44:51.933  1036  1538 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-16 13:44:51.934  1036  1538 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-16 13:44:51.934  1036  1538 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 13:44:51.935  1036  1538 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=388604  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-16 13:44:51.935  1036  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=388604  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-16 13:44:51.936  1036  1538 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=388605
08-16 13:44:51.936  1036  1538 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=388606
08-16 13:44:51.937  1036  1538 D WifiNative-wlan0: doString: [STATUS]
,08-16 13:44:51.938  1036  7543 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 13:44:51.938  1036  7543 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,08-16 13:44:51.940  4740  4740 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 13:44:51.940  1036  1538 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-16 13:44:51.942  1036  1538 I WifiServiceExtension: setVHTCapabilityType  : false
08-16 13:44:51.949  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 13:44:51.949  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 13:44:51.951  1036  1538 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-16 13:44:51.951  1036  1538 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-16 13:44:51.952  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 13:44:51.954  7338  7338 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-16 13:44:51.958  4740  7595 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-16 13:44:51.960  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:44:51.960  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:44:51.960  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-16 13:44:51.964  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:44:51.964  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:44:51.964  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,08-16 13:44:51.970  1036  1538 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-16 13:44:51.970  1036  1545 D ConnectivityService: Got NetworkAgent Messenger
08-16 13:44:51.970  1036  1538 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 13:44:51.970  1036  1538 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-16 13:44:51.970  1036  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-16 13:44:51.970  1036  1545 D ConnectivityService: NetworkAgent connected
08-16 13:44:51.970  1036  1538 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-16 13:44:51.970  1036  1538 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-16 13:44:51.971  4740  7596 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-16 13:44:51.972  4740  7596 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-16 13:44:51.972  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 13:44:51.972  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 13:44:51.974  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 13:44:51.982  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 13:44:51.982  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-16 13:44:51.986  1036  1538 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-16 13:44:51.986  1036  1538 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 13:44:51.986  1036  1538 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-16 13:44:51.987  1036  1538 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-16 13:44:51.987  1036  1538 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-16 13:44:51.987  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 13:44:51.996  1036  1538 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-16 13:44:52.000   308   895 D CommandListener: Setting iface cfg
08-16 13:44:52.013  1036  1538 E WifiStateMachine: Start Dhcp Watchdog 2
08-16 13:44:52.013  1036  7604 D DhcpStateMachine: StoppedState
08-16 13:44:52.013  1036  7604 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 13:44:52.013  1036  7604 D DhcpStateMachine: WaitBeforeStartState
08-16 13:44:52.013  1036  1538 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=388682  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 13:44:52.014  1036  1538 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=388683  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,08-16 13:44:52.014  1036  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=388683  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,08-16 13:44:52.015  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 13:44:52.015  1036  1036 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-16 13:44:52.016  1036  1538 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=388686  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 13:44:52.017  1036  1538 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=388686  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 13:44:52.017  1036  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=388687  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 13:44:52.018  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 13:44:52.018  1036  1036 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-16 13:44:52.018  7338  7605 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:44:52.019  1036  1538 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:342141] from screen [on:0 period:-1825890509] gl rssi=-56 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 13:44:52.019  7234  7607 W FormManager: Network not available. Please check & try again.
08-16 13:44:52.020  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1825890508] gl rssi=-56 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 13:44:52.020  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-16 13:44:52.024  3309  3309 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-16 13:44:52.024  3309  3309 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-16 13:44:52.024  3309  3309 I LgeMiscReceiver: networkInfo.isConnected() = false
08-16 13:44:52.026  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 13:44:52.026  1036  1545 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-16 13:44:52.027  1036  1538 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 13:44:52.027  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 13:44:52.027  1036  1538 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
,08-16 13:44:52.028  1036  1538 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 13:44:52.028  1036  1538 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 13:44:52.028  1036  1538 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 13:44:52.029  1036  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-16 13:44:52.029  7368  7368 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-16 13:44:52.029  7368  7368 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-16 13:44:52.029  1036  1538 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=165,0,0
08-16 13:44:52.030  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=165,0,0
08-16 13:44:52.030  1036  1538 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-16 13:44:52.030  7511  7511 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-16 13:44:52.031  1036  1538 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-16 13:44:52.031  1036  1538 D WifiNative-wlan0: doBoolean: SET ps 0
08-16 13:44:52.031  1036  1538 D WifiNative-wlan0: SET ps 0: returned true
08-16 13:44:52.031  1036  1538 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-16 13:44:52.031  7511  7511 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
,08-16 13:44:52.031  7234  7608 V FormManager: Network unavailable.
08-16 13:44:52.032  1036  1538 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
,08-16 13:44:52.032  1036  1537 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1075386 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:44:52.032  1036  1537 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1075386 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:44:52.032  1036  1538 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-16 13:44:52.032  1036  1538 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-16 13:44:52.032  1036  7604 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:44:52.032  1036  7604 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-16 13:44:52.033  1036  1538 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-16 13:44:52.034   308   895 D CommandListener: Setting iface cfg
08-16 13:44:52.035   308   895 D CommandListener: Trying to bring up wlan0
08-16 13:44:52.036  1036  1538 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-16 13:44:52.039  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 13:44:52.039  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-16 13:44:52.042  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 13:44:52.042  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-16 13:44:52.042  1036  1538 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK 
,08-16 13:44:52.043  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK 
08-16 13:44:52.043  1036  1538 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-16 13:44:52.043  7511  7511 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-16 13:44:52.043  1036  1537 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:44:52.043  1036  1537 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:44:52.044  1036  1538 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-16 13:44:52.044  1036  1538 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-16 13:44:52.044  7234  7608 V FormManager: Network unavailable.
08-16 13:44:52.044  7511  7511 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-16 13:44:52.044  1036  1538 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-16 13:44:52.044  1036  1538 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 13:44:52.047  7453  7453 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:44:52
08-16 13:44:52.051  7453  7453 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-16 13:44:52.051  7453  7453 D Weather.Utils: 2 : All the weather widget is gone.
08-16 13:44:52.051  7453  7453 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-16 13:44:52.052  7453  7453 D WeatherAncestor: connectivity changed - connection : true
08-16 13:44:52.052  7453  7453 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@df29a71
08-16 13:44:52.054  7453  7453 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-16 13:44:52.054  7453  7453 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-16 13:44:52.054  7453  7453 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-16 13:44:52.054  7453  7453 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-16 13:44:52.054  7453  7453 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:44:52
08-16 13:44:52.060  1036  1538 D WifiNative-wlan0: SET ps 1: returned true
08-16 13:44:52.061  1036  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,08-16 13:44:52.061  1036  1538 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 13:44:52.061  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 13:44:52.062  1036  1538 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 13:44:52.062  1036  1538 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 13:44:52.063  1036  1538 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 13:44:52.063  1036  1538 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 13:44:52.064  1036  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-16 13:44:52.064  1036  1538 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-16 13:44:52.064  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-16 13:44:52.064  1036  1538 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-16 13:44:52.065  1036  1545 D ConnectivityService: ignoring duplicate network state non-change
08-16 13:44:52.069  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 13:44:52.069  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 13:44:52.069  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:44:52.069  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:44:52.069  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-16 13:44:52.070  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 13:44:52.075  1036  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-16 13:44:52.076  1036  1545 D ConnectivityService: Adding iface wlan0 to network 101
08-16 13:44:52.078  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:44:52.078  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:44:52.078  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-16 13:44:52.082  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-16 13:44:52.084  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:44:52.084  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:44:52.084  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-16 13:44:52.086  1036  1538 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-16 13:44:52.086  1941  1941 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-16 13:44:52.086  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,08-16 13:44:52.090  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 13:44:52.090  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 13:44:52.092  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 13:44:52.092  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:44:52.092  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:44:52.093  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-16 13:44:52.099  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 13:44:52.099  1603  1603 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-16 13:44:52.099  1036  1545 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-16 13:44:52.099  1036  1545 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-16 13:44:52.099  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 13:44:52.100  1036  1545 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-16 13:44:52.101   308   895 E Netd    : netlink response contains error (File exists)
08-16 13:44:52.101  1036  1545 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-16 13:44:52.102  7122  7122 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-16 13:44:52.102  7122  7122 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-16 13:44:52.102  7122  7122 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-16 13:44:52.102  7122  7122 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-16 13:44:52.102  1036  1545 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-16 13:44:52.102  1036  1545 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-16 13:44:52.102  1036  1545 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-16 13:44:52.103  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 13:44:52.103  1603  1603 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-16 13:44:52.103  7122  7122 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-16 13:44:52.103  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 13:44:52.106  1036  1545 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-16 13:44:52.106  1036  1545 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-16 13:44:52.106  1036  1545 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-16 13:44:52.106  1036  1545 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-16 13:44:52.106  1036  7598 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:44:52.106  1036  1545 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 13:44:52.106  1036  7598 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-16 13:44:52.106  1036  1545 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 13:44:52.106  1036  1545 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-16 13:44:52.106  1036  7598 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:44:52.106  1036  1545 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 13:44:52.106  1036  7598 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-16 13:44:52.106  1036  1545 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-16 13:44:52.106  1036  1545 D ConnectivityService: currentScore = 0, newScore = 20
08-16 13:44:52.107  1036  1545 D ConnectivityService:    accepting network in place of null
08-16 13:44:52.107  1036  1545 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 13:44:52.107  1036  1538 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 13:44:52.107  1036  1538 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilitie,s: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 13:44:52.107  7122  7122 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-16 13:44:52.107  7122  7122 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-16 13:44:52.107  7122  7122 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-16 13:44:52.107  7122  7122 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-16 13:44:52.107  7122  7122 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-16 13:44:52.108  7122  7122 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-16 13:44:52.108  7122  7122 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-16 13:44:52.109  1036  1545 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-16 13:44:52.109   308  7614 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-16 13:44:52.109  1036  1545 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-16 13:44:52.109  1036  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-16 13:44:52.110  1851  1851 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 13:44:52.110  1851  1851 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-16 13:44:52.115  1036  1545 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-16 13:44:52.115  1036  1545 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-16 13:44:52.116  1036  1545 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-16 13:44:52.116  1036  1545 D ConnectivityService: validation of new default Network = false
08-16 13:44:52.116  1036  1545 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-16 13:44:52.116  1036  1545 D DSQN    : enableDataServiceNotify 
08-16 13:44:52.117  1036  1545 D DSQN    : start dsqn bin
08-16 13:44:52.117  1036  1036 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-16 13:44:52.117  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-16 13:44:52.117  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roamin,g: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-16 13:44:52.117  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-16 13:44:52.125  7103  7103 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 13:44:52.127  1036  1545 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-16 13:44:52.127  1036  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 13:44:52.128  1036  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 13:44:52.113  7616  7616 W dsqn    : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 13:44:52.113  7616  7616 W dsqn    : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 13:44:52.128  1036  1545 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 13:44:52.128  1603  2071 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-16 13:44:52.131  7122  7122 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-16 13:44:52.138  1036  1536 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-16 13:44:52.140  7616  7616 E DSQN    : DSQN ssw
08-16 13:44:52.148  7122  7122 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 13:44:52.150   308  7614 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-16 13:44:52.155  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 13:44:52.155  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 13:44:52.156  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 13:44:52.159  1816  7622 I CheckinService: active receiver: enabled
,08-16 13:44:52.173  7103  7103 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 13:44:52.174  1816  7622 I CheckinService: Preparing to send checkin request
08-16 13:44:52.174  1816  7622 I EventLogService: Accumulating logs since 1471347546641
08-16 13:44:52.175  7122  7122 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-16 13:44:52.178  7122  7122 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 13:44:52.182   308  7614 D libc-netbsd: res_queryN name = clients3.google.com succeed
08-16 13:44:52.186  4740  4740 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,08-16 13:44:52.186  4740  4740 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 13:44:52.187  4740  4740 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 13:44:52.188  4740  4740 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 13:44:52.188   308  7625 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-16 13:44:52.188   308  7625 D libc-netbsd: res_queryN name = static-avc.lglime.com, class = 1, type = 1
08-16 13:44:52.190  6395  6395 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 13:44:52.191  4740  7626 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-16 13:44:52.192  4740  7627 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 13:44:52.192  4740  7627 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-16 13:44:52.193  4740  7626 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
08-16 13:44:52.195  7122  7122 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 13:44:52.199  7122  7122 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 13:44:52.203  4740  7626 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
08-16 13:44:52.206  7150  7150 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 13:44:52.206  7150  7150 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 13:44:52.206  4740  4740 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
08-16 13:44:52.207  7150  7150 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-16 13:44:52.207  4740  4740 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
08-16 13:44:52.207  4740  4740 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
08-16 13:44:52.208  4740  4740 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
,08-16 13:44:52.209   308   894 D LGDataListener: argv[0]=dsqncommand
08-16 13:44:52.209   308   894 D LGDataListener: argv[1]=wlan0
08-16 13:44:52.209   308   894 D LGDataListener: argv[2]=1
08-16 13:44:52.209   308   894 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-16 13:44:52.210  1036  1105 D DSQN    : DSQM DsqnNotification wlan0  1
08-16 13:44:52.210  1036  1105 D DSQN    : start to monitor internet connection
,08-16 13:44:52.216  4740  4740 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
08-16 13:44:52.233   308  7625 D libc-netbsd: res_queryN name = static-avc.lglime.com succeed
,08-16 13:44:52.234  1036  7604 D DhcpStateMachine: DHCPV4 request on wlan0
08-16 13:44:52.234  1036  7604 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-16 13:44:52.234  1036  7604 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-16 13:44:52.223  7631  7631 W dhcpcd  : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 13:44:52.237  1036  7598 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 16 Aug 2016 11:44:52 GMT], X-Android-Received-Millis=[1471347892236], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1471347892209]}
08-16 13:44:52.237  1036  7598 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-16 13:44:52.237  1036  7598 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-16 13:44:52.223  7631  7631 W dhcpcd  : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 13:44:52.237  1036  1545 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-16 13:44:52.237  1036  1545 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-16 13:44:52.237  1036  1545 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 13:44:52.237  1036  1545 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 13:44:52.237  1036  1545 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-16 13:44:52.237  1036  1545 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-16 13:44:52.237  1036  1545 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-16 13:44:52.238  1036  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 13:44:52.238  1036  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 13:44:52.238  1036  1545 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 13:44:52.238  1036  1545 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 13:44:52.238  1036  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-16 13:44:52.238  1603  2071 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-16 13:44:52.239  1036  1538 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 13:44:52.239  1036  1538 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 13:44:52.239  1851  1851 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 13:44:52.239  1851  1851 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-16 13:44:52.240  1036  1646 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7632 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, ,3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
08-16 13:44:52.243  1816  7622 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
08-16 13:44:52.244  7631  7631 I dhcpcd  : version 5.5.6 starting
08-16 13:44:52.245  7631  7631 E dhcpcd  : get_duid: m
08-16 13:44:52.245  7631  7631 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-16 13:44:52.245  7631  7631 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-16 13:44:52.261  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 13:44:52.262  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 13:44:52.262  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 13:44:52.278  7234  7619 V FormManager: There are no updated forms. The schedule will be deleted.
08-16 13:44:52.281  7234  7619 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
08-16 13:44:52.304  7631  7631 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-16 13:44:52.304  7631  7631 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-16 13:44:52.304  7631  7631 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-16 13:44:52.305  7631  7631 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
08-16 13:44:52.305  7631  7631 D dhcpcd  : wlan0: sending REQUEST (xid 0xde76b986), next in 4.57 seconds
,08-16 13:44:52.337  1036  1904 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7657 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-16 13:44:52.339  7632  7632 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-16 13:44:52.339  7632  7632 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
08-16 13:44:52.343  7632  7632 V [BNRBootReceiver]: Boot Receiver Return
08-16 13:44:52.343  7632  7632 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-16 13:44:52.344  6395  6395 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 13:44:52.348  7631  7631 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
08-16 13:44:52.348  7122  7122 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 13:44:52.352  7122  7122 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 13:44:52.356  7150  7150 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 13:44:52.356  7150  7150 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 13:44:52.357  7150  7150 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-16 13:44:52.359  7122  7122 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-16 13:44:52.361  7122  7122 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-16 13:44:52.363  6395  6395 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 13:44:52.368  7122  7122 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 13:44:52.369  7631  7631 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
08-16 13:44:52.369  7631  7631 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
08-16 13:44:52.370  7631  7631 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-16 13:44:52.370  7631  7631 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-16 13:44:52.370  7631  7631 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-16 13:44:52.370  7631  7631 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-16 13:44:52.370  7631  7631 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-16 13:44:52.370  7631  7631 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,08-16 13:44:52.382  7122  7122 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 13:44:52.387  7150  7150 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 13:44:52.387  7150  7150 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 13:44:52.388  7150  7150 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 13:44:52.391  6395  6395 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 13:44:52.393  7234  7655 V FormManager: There are no updated forms. The schedule will be deleted.
08-16 13:44:52.396  7234  7655 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
08-16 13:44:52.401  7657  7657 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-16 13:44:52.402  7657  7657 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
08-16 13:44:52.402  7122  7122 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 13:44:52.410  7122  7122 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 13:44:52.414  7150  7150 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 13:44:52.415  7150  7150 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 13:44:52.415  7150  7150 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-16 13:44:52.419  6395  6395 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 13:44:52.426  7122  7122 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 13:44:52.432  7122  7122 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 13:44:52.436  7150  7150 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 13:44:52.437  7150  7150 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 13:44:52.437  7150  7150 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 13:44:52.439  6395  6395 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 13:44:52.444  7657  7657 I MultiDex: VM with version 2.1.0 has multidex support
08-16 13:44:52.444  7657  7657 I MultiDex: install
08-16 13:44:52.444  7657  7657 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-16 13:44:52.445  7122  7122 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 13:44:52.451  7122  7122 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 13:44:52.455  7150  7150 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 13:44:52.455  7150  7150 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 13:44:52.455  7150  7150 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 13:44:52.458  6395  6395 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 13:44:52.463  7122  7122 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 13:44:52.465  7657  7657 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,08-16 13:44:52.474  7122  7122 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 13:44:52.480  7150  7150 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 13:44:52.480  7150  7150 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 13:44:52.481  7150  7150 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 13:44:52.485  6395  6395 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 13:44:52.495  7122  7122 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 13:44:52.499  7122  7122 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 13:44:52.505  7150  7150 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 13:44:52.505  7150  7150 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 13:44:52.508  7150  7150 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-16 13:44:52.512  6395  6395 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 13:44:52.522  7122  7122 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 13:44:52.526  7122  7122 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 13:44:52.530  7150  7150 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 13:44:52.531  7150  7150 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 13:44:52.531  7150  7150 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 13:44:52.542  6395  6395 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 13:44:52.546  7103  7103 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-16 13:44:52.549  7103  7103 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-16 13:44:52.552  7122  7122 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 13:44:52.556  7122  7122 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 13:44:52.560  7150  7150 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 13:44:52.561  7150  7150 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 13:44:52.561  7150  7150 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-16 13:44:52.562  7150  7150 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-16 13:44:52.562  7150  7150 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-16 13:44:52.566  6395  6395 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 13:44:52.570  7103  7103 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-16 13:44:52.571  7103  7103 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-16 13:44:52.575  7122  7122 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 13:44:52.579  7122  7122 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 13:44:52.586  7150  7150 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 13:44:52.586  7150  7150 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 13:44:52.586  7150  7150 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-16 13:44:52.587  7150  7150 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-16 13:44:52.587  7150  7150 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-16 13:44:52.589  1036  1051 I ActivityManager: Killing 7077:com.lge.lifetracker/u0a37 (adj 15): empty #17
,08-16 13:44:52.637  1036  7604 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-16 13:44:52.640  1036  7604 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
,08-16 13:44:52.640  1036  7604 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-16 13:44:52.641  1036  7604 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
08-16 13:44:52.641  1036  7604 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-16 13:44:52.641  1036  7604 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-16 13:44:52.641  1036  7604 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-16 13:44:52.641  1036  7604 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-16 13:44:52.643  1036  7604 D DhcpStateMachine: RunningState
08-16 13:44:52.652  1036  1052 W libprocessgroup: failed to open /acct/uid_10037/pid_7077/cgroup.procs: No such file or directory
,08-16 13:44:52.656  2175  2175 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-16 13:44:52.668  2175  2175 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
08-16 13:44:52.668  2175  2175 D c       : Getting all permits...
08-16 13:44:52.668  2175  2175 D a       : Opening database...
08-16 13:44:52.673  2175  2175 D a       : Opening database auth.proximity.permit_store...
08-16 13:44:52.674  2175  2175 D a       : Closing database...
,08-16 13:44:52.681  6798  7290 D UEI.SmartControl: Internal timer expired: 2
08-16 13:44:52.681  6798  7290 D UEI.SmartControl: unbind internal service
08-16 13:44:52.803  6798  7284 D serial_port: close(fd = 24)
08-16 13:44:52.807  6798  7284 I UEI.SmartControl: Serial port is closed.
,08-16 13:44:52.907  7657  7674 D LgDataFeature: LgDataFeature() Constructor: none
08-16 13:44:52.907  7657  7674 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 13:44:53.010  1036  1904 I art     : Explicit concurrent mark sweep GC freed 93949(4MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/64MB, paused 3.344ms total 86.583ms
,08-16 13:44:53.054  7705  7705 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-16 13:44:53.062  1036  1538 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 13:44:53.062  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 13:44:53.062  1036  1538 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 13:44:53.063  1036  1538 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 13:44:53.063  1036  1538 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 13:44:53.063  1036  1538 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 13:44:53.065  1036  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
08-16 13:44:53.066  1036  1545 D ConnectivityService: identical MTU - not setting
08-16 13:44:53.067  1036  1545 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-16 13:44:53.068  1036  1545 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-16 13:44:53.070  1036  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 13:44:53.070  1036  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 13:44:53.071  1036  1545 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 13:44:53.073  1603  2071 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-16 13:44:53.117  7705  7705 I dex2oat : dex2oat took 62.546ms (threads: 4)
,08-16 13:44:53.128  1036  1545 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-16 13:44:53.132  7657  7674 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 13:44:53.132  7657  7674 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 13:44:53.132  7657  7674 I Adreno-EGL: Build Date: 12/12/14 금
08-16 13:44:53.132  7657  7674 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 13:44:53.132  7657  7674 I Adreno-EGL: Remote Branch: 
08-16 13:44:53.132  7657  7674 I Adreno-EGL: Local Patches: 
08-16 13:44:53.132  7657  7674 I Adreno-EGL: Reconstruct Branch: 
,08-16 13:44:53.260  7657  7674 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 13:44:53.260  7657  7674 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 13:44:53.260  7657  7674 I Adreno-EGL: Build Date: 12/12/14 금
08-16 13:44:53.260  7657  7674 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 13:44:53.260  7657  7674 I Adreno-EGL: Remote Branch: 
08-16 13:44:53.260  7657  7674 I Adreno-EGL: Local Patches: 
08-16 13:44:53.260  7657  7674 I Adreno-EGL: Reconstruct Branch: 
,08-16 13:44:53.364  7657  7674 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 13:44:53.364  7657  7674 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 13:44:53.364  7657  7674 I Adreno-EGL: Build Date: 12/12/14 금
08-16 13:44:53.364  7657  7674 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 13:44:53.364  7657  7674 I Adreno-EGL: Remote Branch: 
08-16 13:44:53.364  7657  7674 I Adreno-EGL: Local Patches: 
08-16 13:44:53.364  7657  7674 I Adreno-EGL: Reconstruct Branch: 
,08-16 13:44:53.789   308  7716 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-16 13:44:53.792   308  7716 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
08-16 13:44:53.836   308  7716 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,08-16 13:44:54.038  1816  7622 I CheckinTask: Sending checkin request (7928 bytes)
,08-16 13:44:54.248  1816  7622 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,08-16 13:44:54.258  1816  7622 I CheckinService: active receiver: disabled
,08-16 13:44:54.288  2175  2175 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-16 13:44:54.307  2175  2175 I GCM     : GCM config loaded
,08-16 13:44:54.328  7368  7368 V SetupWizard: Connected to Gservices successfully
,08-16 13:44:54.341   308  7720 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-16 13:44:54.344   308  7720 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
08-16 13:44:54.377   308  7720 D libc-netbsd: res_queryN name = mtalk.google.com succeed
,08-16 13:44:54.674  2175  7722 D GCM     : Connected
,08-16 13:44:54.718  2175  7722 D GCM     : Message class com.google.e.a.a.q
,08-16 13:44:55.029  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-54 f=2447 sc=60 link=72 tx=82.5, 0.0, 0.0  rx=78.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1825887499] gl rssi=-54 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-16 13:44:55.034  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-54 f=2447 sc=60 link=72 tx=82.5, 0.0, 0.0  rx=78.0 bcn=0 [on:0 tx:0 rx:0 period:5] from screen [on:0 period:-1825887494] gl rssi=-54 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 13:44:55.035  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-16 13:44:55.053  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 13:44:55.085  1036  1539 V WifiInternetCheck: Single check msg out of sync, ignoring.
,08-16 13:44:55.103  1036  1994 D WifiServiceImplEx: setWifiEnabled: false pid=6936, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-16 13:44:55.103  1036  1994 D WifiService: setWifiEnabled: false pid=6936, uid=10118
08-16 13:44:55.103  1036  1994 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 13:44:55.119  1036  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-16 13:44:55.124  1036  1107 D Tethering: MasterInitialState.processMessage what=3
,08-16 13:44:55.140  6936  6936 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:44:55.140  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:44:55.140  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:44:55.140  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 13:44:55.140  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:44:55.140  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 13:44:55.140  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 13:44:55.140  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 13:44:55.140  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 13:44:55.140  6936  6936 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:44:55.141  6936  6936 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 13:44:55.146  6936  6936 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:44:55.146  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:44:55.146  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:44:55.146  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 13:44:55.146  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:44:55.146  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 13:44:55.146  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 13:44:55.146  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 13:44:55.146  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 13:44:55.146  6936  6936 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:44:55.146  6936  6936 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 13:44:55.148  6936  6936 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:44:55.148  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:44:55.148  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:44:55.148  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 13:44:55.148  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:44:55.148  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 13:44:55.148  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 13:44:55.148  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 13:44:55.148  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 13:44:55.148  6936  6936 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:44:55.149  6936  6936 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 13:44:55.152  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 13:44:55.152  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 13:44:55.152  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-16 13:44:55.154  1036  1538 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-16 13:44:55.154  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-16 13:44:55.155  1036  1538 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-16 13:44:55.155  1036  1538 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-16 13:44:55.156  1036  1538 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-16 13:44:55.156  1036  1538 E WifiStateMachine: WifiStateMachine: Leaving Connected state
0,8-16 13:44:55.156  1036  1538 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 13:44:55.156  1036  1538 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
,08-16 13:44:55.164  1036  1538 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-16 13:44:55.164  1036  1538 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-16 13:44:55.175  1036  1538 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-16 13:44:55.175  1036  1538 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-16 13:44:55.175  7511  7511 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
,08-16 13:44:55.179  1036  1537 D LGWifiP2pService: InactiveState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:44:55.179  1036  1537 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:44:55.179  1036  1538 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-16 13:44:55.179  1036  1538 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 13:44:55.180  1036  1538 D WifiNative-wlan0: SET ps 1: returned true
08-16 13:44:55.181   308   895 D CommandListener: Clearing all IP addresses on wlan0
08-16 13:44:55.190  1036  7604 D DhcpStateMachine: RunningState{ when=-9ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 13:44:55.254  1036  1036 D WifiHS20: hidePasspointNotification off =false
,08-16 13:44:55.260  1036  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-16 13:44:55.261  1036  1545 D ConnectivityService: ignoring duplicate network state non-change
08-16 13:44:55.262  1036  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
08-16 13:44:55.264  6395  6395 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-16 13:44:55.266  6395  7102 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-16 13:44:55.280  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 13:44:55.280  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:44:55.280  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,08-16 13:44:55.295  1941  1941 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-16 13:44:55.295  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 13:44:55.292  1036  1537 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:44:55.295  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 13:44:55.295  1036  1537 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:44:55.295  1036  1537 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@2e3e6111
08-16 13:44:55.295  1036  1537 D LGWifiP2pService: P2pDisablingState
08-16 13:44:55.295  1036  1537 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:44:55.295  1036  1537 D LGWifiP2pService: p2p socket connection lost
08-16 13:44:55.295  1036  1537 D LGWifiP2pService: P2pDisabledState
08-16 13:44:55.296  1036  1538 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 13:44:55.296  1036  1538 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 13:44:55.297  1036  1538 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 13:44:55.297  1036  1538 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-16 13:44:55.297  1036  1538 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-16 13:44:55.303  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-16 13:44:55.303  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:44:55.303  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:44:55.303  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 13:44:55.303  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 1
08-16 13:44:55.305  1036  1556 D WifiScanningService: DefaultState got{ when=-2ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:44:55.305  1036  1036 D RttService: SCAN_AVAILABLE : 1
08-16 13:44:55.305  1036  1557 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:44:55.305  1036  1092 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-16 13:44:55.307  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-16 13:44:55.307  1941  1941 D WfdsService: WifiP2pState is changed : false
08-16 13:44:55.307  1941  2315 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-16 13:44:55.307  1941  2315 D WfdsService: Set the WFDS Monitor: false
08-16 13:44:55.310  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 13:44:55.312  1941  2315 D WfdsMonitor: WFDS Monitor is stopped
08-16 13:44:55.312  1941  2315 D WfdsService: STATE : WfdsDisabledState - enter
08-16 13:44:55.312  1941  7545 D CtrlSupplicant: Received on exit socket, terminate
08-16 13:44:55.312  1941  7545 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-16 13:44:55.312  1941  7545 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-16 13:44:55.312  1941  7545 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-16 13:44:55.313  1941  2316 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-16 13:44:55.313  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WI,FI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 13:44:55.313  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 13:44:55.313  1941  2315 W WfdsService: DefaultState - msg [9445378] is not handled
08-16 13:44:55.313  5811  5811 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-16 13:44:55.313  1036  1538 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-16 13:44:55.314  7511  7511 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-16 13:44:55.314  1036  1538 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-16 13:44:55.314  1036  1538 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 13:44:55.314  1036  1538 D WifiNative-wlan0: SET ps 1: returned true
08-16 13:44:55.315  1036  1537 D LGWifiP2pService: P2pDisabledState{ when=-17ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:44:55.315  1036  1537 D LGWifiP2pService: DefaultState{ when=-17ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 13:44:55.317  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 13:44:55.320  1036  1092 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 13:44:55.326  1036  1051 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10005
08-16 13:44:55.326  1036  7598 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:44:55.326  1036  7598 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:44:55.327  1036  7598 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-16 13:44:55.327  1036  7598 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:44:55.327  1036  7598 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
08-16 13:44:55.327   308   895 D CommandListener: Clearing all IP addresses on wlan0
08-16 13:44:55.328  1036  1545 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-16 13:44:55.328  1036  1545 D DSQN    : disableDataServiceNotify
08-16 13:44:55.328  1036  1545 D DSQN    : stop dsqn bin
,08-16 13:44:55.329  1036  1538 D WifiNative-p2p0: doBoolean: TERMINATE
08-16 13:44:55.330  1036  1538 D WifiNative-p2p0: TERMINATE: returned true
08-16 13:44:55.331  1036  1538 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 13:44:55.331  1036  1538 E WifiStateMachine: useWiFiOffloading() : false
08-16 13:44:55.331  1036  1538 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-16 13:44:55.331  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-16 13:44:55.332  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:44:55.332  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:44:55.332  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 13:44:55.332  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-16 13:44:55.332  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 13:44:55.333  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 13:44:55.334   308  7745 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-16 13:44:55.335  1036  1105 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-16 13:44:55.335  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-16 13:44:55.336  1036  7598 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
08-16 13:44:55.337  6936  6936 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:44:55.337  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:44:55.337  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:44:55.337  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 13:44:55.337  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 13:44:55.337  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 13:44:55.337  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 13:44:55.337  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 13:44:55.337  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 13:44:55.337  6936  6936 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:44:55.337  6936  6936 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 13:44:55.337  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-16 13:44:55.337  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 13:44:55.337  1036  1036 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-16 13:44:55.338  6936  6936 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:44:55.338  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:44:5,5.338  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:44:55.338  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 13:44:55.338  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 13:44:55.338  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 13:44:55.338  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 13:44:55.338  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 13:44:55.338  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 13:44:55.338  6936  6936 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:44:55.338  6936  6936 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 13:44:55.339  6936  6936 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:44:55.339  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:44:55.339  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:44:55.339  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 13:44:55.339  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 13:44:55.339  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 13:44:55.339  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 13:44:55.339  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 13:44:55.339  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 13:44:55.339  6936  6936 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:44:55.339  6936  6936 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 13:44:55.341  1036  1545 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-16 13:44:55.341  1036  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 13:44:55.341  1036  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 13:44:55.342  1036  1545 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 13:44:55.342  1036  1545 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-16 13:44:55.343  2175  2175 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-16 13:44:55.344  1603  2071 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-16 13:44:55.344  1036  7598 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:44:55.344  1036  7598 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:44:55.344  1036  7598 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-16 13:44:55.345  1036  1545 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-16 13:44:55.345  1036  1545 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-16 13:44:55.345  1036  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-16 13:44:55.346  1036  1545 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-16 13:44:55.346  1036  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-16 13:44:55.347  1036  1545 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-16 13:44:55.347  1036  1545 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 13:44:55.347  1036  1545 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 13:44:55.347  1036  1545 D NetworkManagementService: Removing idletimer
08-16 13:44:55.347  1036  1545 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:44:55.347  1851  1851 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 13:44:55.347  1036  1538 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 13:44:55.347  1036  1538 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 13:44:55.347  1851  1851 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-16 13:44:55.348  1036  1536 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-16 13:44:55.348  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-16 13:44:55.348  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-16 13:44:55.348  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-16 13:44:55.348  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-16 13:44:55.348  1036  1536 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-16 13:44:55.350  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-16 13:44:55.350  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-16 13:44:55.351  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-16 13:44:55.351  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-16 13:44:55.351  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 13:44:55.354  2175  2175 W GCM     : ACTIVE NETWORK NOT CONNECTED
08-16 13:44:55.363  7309  7309 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-16 13:44:55.363  7309  7309 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-16 13:44:55.363  7309  7309 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-16 13:44:55.364  7309  7309 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-16 13:44:55.369  7309  7309 I AppUp4:CustModeStarterReceiver: onReceive
08-16 13:44:55.374  7309  7309 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@166647fb
08-16 13:44:55.374  7309  7309 D AppUp4:CustFacade: isCustomizationCompleted : false
08-16 13:44:55.374  7309  7309 D AppUp4:CustFacade: isPhone : true
08-16 13:44:55.375  7309  7309 D AppUp4:CustModeStarterReceiver: begin check event
08-16 13:44:55.375  7309  7309 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-16 13:44:55.379  4740  4740 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-16 13:44:55.380  7511  7511 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-16 13:44:55.381  7511  7511 I wpa_supplicant: monitor socket send errors count : 1
08-16 13:44:55.381  7511  7511 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1941-4\x00 that cannot receive messages
08-16 13:44:55.383  1036  7543 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-16 13:44:55.383  1036  7543 D WifiMonitor: Dropping event because (p2p0) is stopped
08-16 13:44:55.383  4740  4740 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 13:44:55.384  4740  4740 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 13:44:55.387  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 13:44:55.387  4740  4740 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 13:44:55.388  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 13:44:55.389  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 13:44:55.391  4740  7748 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-16 13:44:55.393  7338  7338 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-16 13:44:55.398  4740  7749 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-16 13:44:55.398  4740  7749 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-16 13:44:55.408  7338  7751 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 13:44:55.410  7234  7753 W FormManager: Network not available. Please check & try again.
08-16 13:44:55.417  3309  3309 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-16 13:44:55.418  3309  3309 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-16 13:44:55.418  3309  3309 I LgeMiscReceiver: networkInfo.isConnected() = true
08-16 13:44:55.418  3309  3309 D PhoneState: setPdpRejectCasuse : false
08-16 13:44:55.420  7511  7511 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-16 13:44:55.420  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 13:44:55.420  1036  7604 D DhcpStateMachine: StoppedState
08-16 13:44:55.421  1036  7604 D DhcpStateMachine: StoppedState{ when=-106ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:44:55.421  7511  7511 W wpa_supplicant: USIM:  scard_deinit function
08-16 13:44:55.421  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 13:44:55.421  1036  7543 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-16 13:44:55.421  1036  7543 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-16 13:44:55.421  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 13:44:55.421  1036  7543 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-16 13:44:55.421  1036  7543 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-16 13:44:55.422  1036  7543 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 13:44:55.422  1036  7543 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 13:44:55.422  1036  1538 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=392091
08-16 13:44:55.422  1036  1538 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=392092
,08-16 13:44:55.423  1036  1538 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=392092  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-16 13:44:55.423  1036  1538 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=392092  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-16 13:44:55.424  1036  1107 D Tethering: InitialState.processMessage what=4
08-16 13:44:55.426  7368  7368 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-16 13:44:55.426  7368  7368 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-16 13:44:55.427  1036  1538 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-16 13:44:55.427  1036  1538 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-16 13:44:55.430  1036  1107 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-16 13:44:55.431  7234  7754 V FormManager: Network unavailable.
08-16 13:44:55.432  1036  1538 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-16 13:44:55.432  1036  1538 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 13:44:55.434  7234  7754 V FormManager: Network unavailable.
08-16 13:44:55.435  7453  7453 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:44:55
,08-16 13:44:55.438  7453  7453 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-16 13:44:55.438  7453  7453 D Weather.Utils: 2 : All the weather widget is gone.
08-16 13:44:55.438  7453  7453 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-16 13:44:55.438  7453  7453 D WeatherAncestor: connectivity changed - connection : true
08-16 13:44:55.438  7453  7453 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@df29a71
08-16 13:44:55.439  7453  7453 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-16 13:44:55.439  7453  7453 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-16 13:44:55.439  7453  7453 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-16 13:44:55.439  7453  7453 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-16 13:44:55.439  7453  7453 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:44:55
08-16 13:44:55.453  6395  6395 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 13:44:55.455  7103  7103 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-16 13:44:55.455  7103  7103 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 13:44:55.455  7103  7103 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-16 13:44:55.457  7122  7122 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 13:44:55.461  7122  7122 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 13:44:55.466  7150  7150 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 13:44:55.467  7150  7150 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 13:44:55.468  7150  7150 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-16 13:44:55.471  6395  6395 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 13:44:55.475  7103  7103 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-16 13:44:55.475  7103  7103 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 13:44:55.475  7103  7103 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 13:44:55.477  7122  7122 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 13:44:55.481  7122  7122 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 13:44:55.485  7150  7150 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 13:44:55.485  7150  7150 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 13:44:55.487  7150  7150 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-16 13:44:55.489  6395  6395 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 13:44:55.492  7103  7103 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-16 13:44:55.492  7103  7103 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 13:44:55.492  7103  7103 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-16 13:44:55.496  7122  7122 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 13:44:55.502  7122  7122 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 13:44:55.506  7150  7150 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 13:44:55.506  7150  7150 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 13:44:55.508  7150  7150 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-16 13:44:55.509  7511  7511 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-16 13:44:55.509  1036  7543 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-16 13:44:55.509  1036  7543 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-TERMINATING 
08-16 13:44:55.509  1036  7543 D WifiMonitor: Disconnecting from the supplicant, no more events
08-16 13:44:55.510  1036  1538 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 45 0
08-16 13:44:55.517  7103  7103 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 13:44:55.522  7122  7122 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-16 13:44:55.525  7234  7758 W FormManager: Network not available. Please check & try again.
08-16 13:44:55.528  7122  7122 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-16 13:44:55.544  7122  7122 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-16 13:44:55.544  7122  7122 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-16 13:44:55.544  7122  7122 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-16 13:44:55.544  7122  7122 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-16 13:44:55.545  7122  7122 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-16 13:44:55.545  7234  7759 V FormManager: Network unavailable.
,08-16 13:44:55.547  7122  7122 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-16 13:44:55.547  7122  7122 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-16 13:44:55.547  7122  7122 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-16 13:44:55.547  7122  7122 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-16 13:44:55.547  7122  7122 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-16 13:44:55.547  7122  7122 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-16 13:44:55.552  7234  7759 V FormManager: Network unavailable.
08-16 13:44:55.611  1036  1538 D WifiOffDelayIfNotUsed: stopMonitoring
08-16 13:44:55.611  1036  1538 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 13:44:55.611  1036  1538 E WifiStateMachine: useWiFiOffloading() : false
08-16 13:44:55.611  1036  1538 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-16 13:44:55.612  1941  1941 D WfdsService: Supplicant Connection state is changed : false
08-16 13:44:55.613  1941  2315 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-16 13:44:55.613  1941  2315 D WfdsService: Set the WFDS Monitor: false
08-16 13:44:55.613  1941  2315 D WfdsMonitor: WFDS Monitor is stopped
,08-16 13:44:55.616  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-16 13:44:55.617  4740  4740 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 13:44:55.617  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 13:44:55.618  4740  4740 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-16 13:44:55.620  2474  2474 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:44:55.622  4740  4740 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 13:44:55.624  6936  6936 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:44:55.625  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:44:55.625  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:44:55.625  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 13:44:55.625  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 13:44:55.625  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 13:44:55.625  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 13:44:55.625  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 13:44:55.625  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 13:44:55.626  6936  6936 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:44:55.626  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:44:55.626  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:44:55.626  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 13:44:55.626  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 13:44:55.626  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 13:44:55.626  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 13:44:55.626  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 13:44:55.626  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 13:44:55.627  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-16 13:44:55.627  1036  1542 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-16 13:44:55.627  1036  1542 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-16 13:44:55.628  6936  6936 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:44:55.628  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:44:55.628  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:44:55.628  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 13:44:55.628  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 13:44:55.628  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 13:44:55.628  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 13:44:55.628  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to a,ctive network: false
08-16 13:44:55.628  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 13:44:55.633  4740  4740 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 13:44:55.639  4740  7760 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-16 13:44:55.642  7103  7103 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
,08-16 13:44:55.642  7103  7103 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 13:44:55.642  7103  7103 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 13:44:55.646  7122  7122 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-16 13:44:55.648  4740  7761 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 13:44:55.648  4740  7761 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-16 13:44:55.654  7122  7122 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 13:44:55.655  7234  7763 W FormManager: Network not available. Please check & try again.
08-16 13:44:55.666  7234  7764 V FormManager: Network unavailable.
,08-16 13:44:55.668  7234  7764 V FormManager: Network unavailable.
08-16 13:44:55.977  7487  7527 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,08-16 13:44:56.874  1036  1995 I ActivityManager: Killing 7167:com.lge.settings.easy/1000 (adj 15): empty #17
,08-16 13:44:56.907  1036  1755 W libprocessgroup: failed to open /acct/uid_1000/pid_7167/cgroup.procs: No such file or directory
,08-16 13:44:58.064  1036  1538 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1825884464] gl rssi=-54 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-16 13:44:58.066  1036  1538 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1825884462] gl rssi=-54 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-16 13:44:58.350  1036  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 13:44:58.361  1036  1107 D Tethering: MasterInitialState.processMessage what=3
08-16 13:44:58.379  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:44:58.384  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:44:58.385  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:44:58.387  1036  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-16 13:44:58.390  1036  1092 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-16 13:44:58.394  1036  1107 D Tethering: MasterInitialState.processMessage what=3
,08-16 13:44:58.405  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:44:58.406  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:44:58.407  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:44:58.412  6395  6395 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-16 13:44:58.414  6395  7102 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-16 13:44:58.425  5811  5811 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-16 13:44:58.434  5811  5811 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-16 13:44:58.455  2175  2175 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-16 13:44:58.472  7309  7309 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-16 13:44:58.472  7309  7309 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-16 13:44:58.472  7309  7309 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-16 13:44:58.472  7309  7309 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-16 13:44:58.477  7309  7309 I AppUp4:CustModeStarterReceiver: onReceive
08-16 13:44:58.480  7309  7309 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@166647fb
08-16 13:44:58.480  7309  7309 D AppUp4:CustFacade: isCustomizationCompleted : false
08-16 13:44:58.480  7309  7309 D AppUp4:CustFacade: isPhone : true
08-16 13:44:58.481  7309  7309 D AppUp4:CustModeStarterReceiver: begin check event
08-16 13:44:58.481  7309  7309 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-16 13:44:58.486  4740  4740 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-16 13:44:58.486  4740  4740 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 13:44:58.488  4740  4740 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-16 13:44:58.493  4740  4740 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 13:44:58.501  7338  7338 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-16 13:44:58.527  1036  1092 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-16 13:44:58.534  1036  1092 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false],
08-16 13:44:58.534  1036  1092 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 13:44:58.538  4740  7791 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-16 13:44:58.538  4740  7791 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-16 13:44:58.540  4740  7789 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-16 13:44:58.544  3309  3309 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,08-16 13:44:58.544  3309  3309 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-16 13:44:58.544  3309  3309 I LgeMiscReceiver: networkInfo.isConnected() = false
08-16 13:44:58.547  7338  7792 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:44:58.550  7368  7368 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-16 13:44:58.551  7368  7368 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-16 13:44:58.556  7234  7794 W FormManager: Network not available. Please check & try again.
,08-16 13:44:58.564  7453  7453 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:44:58
08-16 13:44:58.565  7234  7795 V FormManager: Network unavailable.
08-16 13:44:58.566  7453  7453 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-16 13:44:58.566  7453  7453 D Weather.Utils: 2 : All the weather widget is gone.
08-16 13:44:58.567  7453  7453 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,08-16 13:44:58.567  7453  7453 D WeatherAncestor: connectivity changed - connection : true
08-16 13:44:58.567  7453  7453 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@df29a71
08-16 13:44:58.567  7234  7795 V FormManager: Network unavailable.
08-16 13:44:58.568  7453  7453 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-16 13:44:58.568  7453  7453 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-16 13:44:58.568  7453  7453 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-16 13:44:58.568  7453  7453 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-16 13:44:58.568  7453  7453 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:44:58
08-16 13:44:58.594  6395  6395 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-16 13:44:58.597  6395  7102 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-16 13:44:58.613  2175  2175 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-16 13:44:58.628  7309  7309 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-16 13:44:58.628  7309  7309 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-16 13:44:58.628  7309  7309 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-16 13:44:58.628  7309  7309 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-16 13:44:58.630  7309  7309 I AppUp4:CustModeStarterReceiver: onReceive
,08-16 13:44:58.633  7309  7309 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@166647fb
08-16 13:44:58.633  7309  7309 D AppUp4:CustFacade: isCustomizationCompleted : false
08-16 13:44:58.633  7309  7309 D AppUp4:CustFacade: isPhone : true
08-16 13:44:58.634  7309  7309 D AppUp4:CustModeStarterReceiver: begin check event
08-16 13:44:58.634  7309  7309 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-16 13:44:58.639  4740  4740 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-16 13:44:58.640  4740  4740 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 13:44:58.643  4740  4740 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-16 13:44:58.648  4740  4740 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-16 13:44:58.661  7338  7338 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-16 13:44:58.661  4740  7800 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-16 13:44:58.669  4740  7801 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-16 13:44:58.670  4740  7801 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-16 13:44:58.707  3309  3309 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-16 13:44:58.709  3309  3309 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-16 13:44:58.710  3309  3309 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-16 13:44:58.716  7338  7802 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:44:58.720  7368  7368 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-16 13:44:58.720  7368  7368 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-16 13:44:58.730  7234  7804 W FormManager: Network not available. Please check & try again.
08-16 13:44:58.740  7453  7453 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:44:58
,08-16 13:44:58.742  7234  7805 V FormManager: Network unavailable.
08-16 13:44:58.744  7453  7453 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-16 13:44:58.744  7453  7453 D Weather.Utils: 2 : All the weather widget is gone.
08-16 13:44:58.745  7453  7453 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-16 13:44:58.745  7453  7453 D WeatherAncestor: connectivity changed - connection : true
08-16 13:44:58.745  7234  7805 V FormManager: Network unavailable.
08-16 13:44:58.745  7453  7453 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@df29a71
08-16 13:44:58.748  7453  7453 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-16 13:44:58.748  7453  7453 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-16 13:44:58.748  7453  7453 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-16 13:44:58.748  7453  7453 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-16 13:44:58.748  7453  7453 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:44:58
08-16 13:44:58.774  1036  1903 I ActivityManager: Killing 7632:com.lge.bnr/1000 (adj 15): empty #17
,08-16 13:44:58.805  1036  1940 W libprocessgroup: failed to open /acct/uid_1000/pid_7632/cgroup.procs: No such file or directory
,08-16 13:45:00.000  1036  1382 D PowerManagerServiceEx: acquireWakeLockInternal: lock=439211240, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
,08-16 13:45:00.013  7150  7150 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
08-16 13:45:00.015  7150  7150 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:4698
,08-16 13:45:00.040  2600  2600 D [Concierge]Service: onStartCommand(). Type : 9
,08-16 13:45:00.054  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-16 13:45:00.054  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
08-16 13:45:00.054  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-16 13:45:00.054  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,08-16 13:45:00.059  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
08-16 13:45:00.059  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
08-16 13:45:00.060  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
08-16 13:45:00.062  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
08-16 13:45:00.113  1036  1036 D PowerManagerServiceEx: releaseWakeLockInternal: lock=439211240 [*alarm*], flags=0x0
,08-16 13:45:00.166  1036  1958 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 13:45:00.166  1036  1958 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-16 13:45:00.191  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 13:45:00.192  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 13:45:00.192  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-16 13:45:00.192  1036  1107 D BluetoothManagerService: Message: 1
08-16 13:45:00.193  1036  1107 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-16 13:45:00.221  1036  1107 D BluetoothManagerService: Message: 20
08-16 13:45:00.221  1036  1107 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2bb50304:true
,08-16 13:45:00.226  7186  7186 D BluetoothAdapterState: make
,08-16 13:45:00.231  7186  7186 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-16 13:45:00.231  7186  7186 I bluedroid-qcom: init
08-16 13:45:00.232  7186  7818 I BluetoothAdapterState: Entering OffState
08-16 13:45:00.233  7186  7186 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-16 13:45:00.233  7186  7186 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-16 13:45:00.233  7186  7186 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-16 13:45:00.233  7186  7186 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-16 13:45:00.233  7186  7186 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-16 13:45:00.235  7186  7186 I bluedroid-qcom: get_profile_interface socket
08-16 13:45:00.235  7186  7186 I bluedroid-qcom: get_profile_interface map_client
,08-16 13:45:00.241  7186  7822 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-16 13:45:00.244  7186  7822 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-16 13:45:00.233  7821  7821 W bdaddr_loader: type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 13:45:00.233  7821  7821 W bdaddr_loader: type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 13:45:00.252  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-16 13:45:00.252  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
,08-16 13:45:00.260  7821  7821 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-16 13:45:00.260  7821  7821 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-16 13:45:00.260  7821  7821 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-16 13:45:00.261  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-16 13:45:00.261  1036  1107 D BluetoothManagerService: Message: 40
08-16 13:45:00.261  1036  1107 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-16 13:45:00.262  7186  7203 I bluedroid-qcom: config_hci_snoop_log
08-16 13:45:00.264  1036  1107 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-16 13:45:00.264  1036  1107 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-16 13:45:00.266  7821  7821 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
,08-16 13:45:00.274  7186  7818 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-16 13:45:00.275  7186  7822 D BluetoothAdapterProperties: Name is: G3
08-16 13:45:00.276  7186  7818 D BluetoothAdapterProperties: Setting state to 11
08-16 13:45:00.277  7186  7818 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-16 13:45:00.277  1036  1107 D BluetoothManagerService: Message: 60
08-16 13:45:00.277  1036  1107 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-16 13:45:00.278  1036  1107 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
,08-16 13:45:00.284  7821  7821 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-16 13:45:00.284  7821  7821 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-16 13:45:00.286  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 13:45:00.290  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-16 13:45:00.295  7122  7122 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-16 13:45:00.297  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:45:00.299  1036  1537 D LGWifiP2pService: P2pDisabledState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:45:00.299  1036  1537 D LGWifiP2pService: DefaultState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:45:00.304  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:45:00.310  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:45:00.311  7186  7186 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-16 13:45:00.311  7186  7186 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:45:00.311  7186  7186 V BluetoothPbapReceiver: ***********state = 11
08-16 13:45:00.316  2175  2175 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 13:45:00.328  7186  7818 I LGBluetoothServiceJni: classInitNative: succeeds
,08-16 13:45:00.333  1036  1538 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
08-16 13:45:00.333  1036  1538 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
08-16 13:45:00.379  1036  1995 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7837 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-16 13:45:00.383  7186  7818 D BluetoothBondStateMachine: make
08-16 13:45:00.386  7186  7818 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@df29a71
08-16 13:45:00.386  7186  7818 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-16 13:45:00.386  7186  7818 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@df29a71
08-16 13:45:00.387  7186  7818 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-16 13:45:00.387  7186  7818 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-16 13:45:00.388  7186  7851 I BluetoothBondStateMachine: StableState(): Entering Off State
08-16 13:45:00.392  7186  7818 E BluetoothAdapterService: File transfer profiles supported!!
08-16 13:45:00.401  7186  7186 D HeadsetService: Received start request. Starting profile...
,08-16 13:45:00.401   341   341 I art     : Explicit concurrent mark sweep GC freed 708(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 418us total 24.352ms
08-16 13:45:00.401  7186  7186 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-16 13:45:00.401  7186  7186 D LGBluetoothHfpAdapter: Version 1.6
08-16 13:45:00.405  7186  7186 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-16 13:45:00.406  7186  7186 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-16 13:45:00.406  7186  7186 D HeadsetStateMachine: make
08-16 13:45:00.407  7186  7818 E BluetoothAdapterService: File transfer profiles supported!!
08-16 13:45:00.422   341   341 I art     : Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 421us total 19.979ms
08-16 13:45:00.424  7186  7818 E BluetoothAdapterService: File transfer profiles supported!!
,08-16 13:45:00.429  7186  7818 E BluetoothAdapterService: File transfer profiles supported!!
08-16 13:45:00.435  7186  7818 E BluetoothAdapterService: File transfer profiles supported!!
08-16 13:45:00.442   341   341 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 459us total 19.786ms
,08-16 13:45:00.443  7186  7818 E BluetoothAdapterService: File transfer profiles supported!!
08-16 13:45:00.444  7186  7186 D LgDataFeature: LgDataFeature() Constructor: none
08-16 13:45:00.444  7186  7186 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 13:45:00.447  7186  7818 E BluetoothAdapterService: File transfer profiles supported!!
08-16 13:45:00.448  7186  7186 D HeadsetStateMachine: max_hf_connections = 1
08-16 13:45:00.448  7186  7186 I bluedroid-qcom: get_profile_interface handsfree
08-16 13:45:00.451  7186  7186 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-16 13:45:00.451   312  2154 V AudioPolicyService: registerClient() client 0xb557c060, uid 1002
08-16 13:45:00.451   312  1385 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-16 13:45:00.451   312  1385 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-16 13:45:00.452   312  1385 V AudioPolicyManagerEx: getOutput() returns output 2
08-16 13:45:00.452  7186  7186 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-16 13:45:00.452   312  1386 V AudioFlinger: registerClient() client 0xb102eb38, pid 7186
08-16 13:45:00.453   312  1379 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 13:45:00.453   312  1379 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 13:45:00.453  1036  2033 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 13:45:00.453  1036  2033 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 13:45:00.453  7186  7203 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 13:45:00.453  7186  7203 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-16 13:45:00.453  3309  3324 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 13:45:00.453  3309  3324 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 13:45:00.453  1851  1867 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 13:45:00.453  1851  1867 V AudioSystem: ioConfigChanged() opening already existing output! 2
,08-16 13:45:00.453   312  1380 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 13:45:00.453   312  1380 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 13:45:00.454  1603  1620 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 13:45:00.454  1603  1620 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 13:45:00.454  1036  1904 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 13:45:00.454  1036  1904 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 13:45:00.454  1603  1620 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 13:45:00.454  1603  1620 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 13:45:00.454  1851  2444 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 13:45:00.454  7186  7204 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 13:45:00.454  1851  2444 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 13:45:00.454  7186  7204 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-16 13:45:00.454  3309  3325 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 13:45:00.454  3309  3325 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 13:45:00.454  7186  7186 V ToneGenerator: Create Track: 0xb4928a80
08-16 13:45:00.454  7186  7186 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-16 13:45:00.454  7186  7186 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-16 13:45:00.454   312  2154 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-16 13:45:00.454   312  2154 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-16 13:45:00.454   312  2154 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-16 13:45:00.454   312  2154 V AudioPolicyManagerEx: getOutput() returns output 2
08-16 13:45:00.454   312  1385 I AudioFlinger: isAudioPlaybackHookOn() false
08-16 13:45:00.455   312  2155 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-16 13:45:00.455   312  2155 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-16 13:45:00.455   312  2155 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-16 13:45:00.455   312  2155 V AudioPolicyManagerEx: getOutput() returns output 2
08-16 13:45:00.455  7186  7186 V AudioSystem: getLatency() output 2, latency 50
,08-16 13:45:00.455  7186  7186 V AudioSystem: getFrameCount() output 2, frameCount 960
08-16 13:45:00.455  7186  7186 V AudioTrack: createTrack_l() output 2 afLatency 50
08-16 13:45:00.455   312   312 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-16 13:45:00.455   312   312 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-16 13:45:00.455   312   312 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-16 13:45:00.455   312   312 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-16 13:45:00.455   312   312 V AudioFlinger: createTrack() lSessionId: 22
08-16 13:45:00.457  7186  7186 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-16 13:45:00.457   312   312 V AudioFlinger: acquiring 22 from 7186, for 7186
08-16 13:45:00.457   312   312 V AudioFlinger:  added new entry for 22
08-16 13:45:00.457  7186  7186 V ToneGenerator: ToneGenerator INIT OK, time: 397138
08-16 13:45:00.457  7186  7186 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@df29a71
08-16 13:45:00.458  7186  7854 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-16 13:45:00.458  7186  7854 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-16 13:45:00.459  7186  7186 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@df29a71
08-16 13:45:00.461  7186  7186 D A2dpService: Received start request. Starting profile...
08-16 13:45:00.461  7186  7186 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-16 13:45:00.462  7186  7854 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-16 13:45:00.462  7186  7186 V Avrcp   : make
08-16 13:45:00.463  7186  7186 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-16 13:45:00.463  7186  7186 I bluedroid-qcom: get_profile_interface avrcp
08-16 13:45:00.463  7186  7854 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-16 13:45:00.463   312  2154 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7186
08-16 13:45:00.464   312  2154 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-16 13:45:00.464   312  2154 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-16 13:45:00.464   312  2154 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-16 13:45:00.464   312  2154 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-16 13:45:00.464   312  2154 V voice   : voice_set_parameters: exit with code(0)
08-16 13:45:00.464   312  2154 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-16 13:45:00.464   312  2154 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-16 13:45:00.465   312  2154 V msm8974_platform: platform_set_parameters: exit with code(0)
08-16 13:45:00.465   312  2154 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-16 13:45:00.465   312  2154 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-16 13:45:00.465   312  2154 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-16 13:45:00.465  7186  7854 V ToneGenerator: ToneGenerator destructor
08-16 13:45:00.465  7186  7854 V ToneGenerator: stopTone
08-16 13:45:00.465  7186  7854 V ToneGenerator: Delete Track: 0xb4928a80
08-16 13:45:00.465  7186  7854 V AudioTrack: ~AudioTrack, releasing session id from 7186 on behalf of 7186
08-16 13:45:00.465   312  1386 V AudioFlinger: releasing 22 from 7186 for 7186
08-16 13:45:00.465   312  1386 V AudioFlinger:  decremented refcount to 0
08-16 13:45:00.465   312  1386 V AudioFlinger: purging stale effects
08-16 13:45:00.465   312  1386 V AudioPolicyService: AudioCommandThread() adding release output 2
08-16 13:45:00.466   312  1386 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-16 ,13:45:00.466   312  1263 V AudioPolicyService: AudioCommandThread() waking up
08-16 13:45:00.466   312  1263 V AudioPolicyService: AudioCommandThread() processing release output 2
08-16 13:45:00.466   312  1263 V AudioPolicyManager: releaseOutput() 2
08-16 13:45:00.466   312  1263 V AudioPolicyService: AudioCommandThread() going to sleep
08-16 13:45:00.466   312  1386 V AudioFlinger: PlaybackThread::Track destructor
08-16 13:45:00.466   312  1386 V AudioFlinger: removeClient_l() pid 7186, calling pid 312
08-16 13:45:00.466  7186  7818 V LGMDMManager: Create singleton instance
,08-16 13:45:00.468  7186  7818 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-16 13:45:00.470  7186  7186 V AudioManager: registerRemoteController: size of Media player list: 0
08-16 13:45:00.472  7186  7186 E AudioManager: No RCC entry present to update
08-16 13:45:00.472  7186  7186 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-16 13:45:00.475  7186  7186 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-16 13:45:00.476  7186  7186 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-16 13:45:00.476  7186  7186 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-16 13:45:00.479  7186  7186 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-16 13:45:00.508  7837  7837 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
,08-16 13:45:00.509  7837  7837 W LG Account v2.2: No ProfileInfo entries
08-16 13:45:00.509  7837  7837 I LG Account v2.2: isEnabled: false
,08-16 13:45:00.509  7837  7837 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-16 13:45:00.509  7837  7837 I Feature : [Lifetracker]Country: EU
08-16 13:45:00.509  7837  7837 I Feature : [Lifetracker]Operator: OPEN
08-16 13:45:00.509  7837  7837 I Feature : [Lifetracker]Ranking support: false
08-16 13:45:00.509  7837  7837 I Feature : [Lifetracker]Comfort support: false
08-16 13:45:00.509  7837  7837 I Feature : [Lifetracker]Accessory: true
08-16 13:45:00.509  7837  7837 I Feature : [Lifetracker]Health device: true
08-16 13:45:00.509  7837  7837 I Feature : [Lifetracker]Extra Pedometer: false
08-16 13:45:00.509  7837  7837 I Feature : [Lifetracker]Blood glucose device: false
08-16 13:45:00.510  7837  7837 I Feature : [Lifetracker]Device Number: 3
08-16 13:45:00.517  7122  7122 D BluetoothPermissionRequest: onReceive
08-16 13:45:00.520  7122  7122 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-16 13:45:00.559  1036  1904 V SIM_STK : Menu title from STK is T-Mobile
08-16 13:45:00.559  1036  1904 V SIM_STK : Menu title from STK is T-Mobile
,08-16 13:45:00.681  1036  2032 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-16 13:45:00.690  7186  7186 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-16 13:45:00.695  7186  7186 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-16 13:45:00.695  7186  7186 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-16 13:45:00.695  7186  7186 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
,08-16 13:45:00.695  7186  7186 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-16 13:45:00.696  7186  7186 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-16 13:45:00.696  7186  7186 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-16 13:45:00.696  7186  7186 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-16 13:45:00.696  7186  7186 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-16 13:45:00.696  7186  7186 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-16 13:45:00.696  7186  7186 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-16 13:45:00.696  7186  7186 I BluetoothA2dpServiceJni: classInitNative
08-16 13:45:00.696  7186  7186 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-16 13:45:00.696  7186  7186 D A2dpStateMachine: make
08-16 13:45:00.699  7186  7186 I bluedroid-qcom: get_profile_interface a2dp
08-16 13:45:00.700  7186  7866 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,08-16 13:45:00.702  7186  7186 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-16 13:45:00.702  7186  7186 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-16 13:45:00.703  7186  7186 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@df29a71
08-16 13:45:00.703  7186  7865 D A2dpStateMachine: Enter Disconnected: -2
08-16 13:45:00.704  7186  7186 I BluetoothHidServiceJni: classInitNative: succeeds
08-16 13:45:00.705  7186  7186 D HidService: Received start request. Starting profile...
08-16 13:45:00.705  7186  7186 I bluedroid-qcom: get_profile_interface hidhost
08-16 13:45:00.705  7186  7186 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@df29a71
08-16 13:45:00.706  7186  7186 I BluetoothHealthServiceJni: classInitNative: succeeds
08-16 13:45:00.707  7186  7186 D HealthService: Received start request. Starting profile...
08-16 13:45:00.711  7186  7186 I bluedroid-qcom: get_profile_interface health
08-16 13:45:00.711  7186  7186 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-16 13:45:00.711  7186  7186 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@df29a71
08-16 13:45:00.711  7186  7186 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-16 13:45:00.713  7186  7186 D PanService: Received start request. Starting profile...
08-16 13:45:00.714  7186  7186 D BluetoothPanServiceJni: initializeNative(L110): pan
08-16 13:45:00.714  7186  7186 I bluedroid-qcom: get_profile_interface pan
08-16 13:45:00.728  7186  7186 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
,08-16 13:45:00.729  7186  7186 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@df29a71
08-16 13:45:00.733  7186  7186 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-16 13:45:00.747  7186  7186 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-16 13:45:00.748  7186  7186 D BtGatt.GattService: Received start request. Starting profile...
08-16 13:45:00.748  7186  7186 D BtGatt.GattService: start()
08-16 13:45:00.748  7186  7186 I bluedroid-qcom: get_profile_interface gatt
08-16 13:45:00.750  7186  7186 D BtGatt.AdvertiseManager: advertise manager created
08-16 13:45:00.759  7186  7186 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@df29a71
08-16 13:45:00.760  7186  7186 D HeadsetStateMachine: Proxy object connected
08-16 13:45:00.762  7186  7186 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-16 13:45:00.762  7186  7186 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
,08-16 13:45:00.768  7186  7186 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@df29a71
08-16 13:45:00.769  7186  7186 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-16 13:45:00.772  7186  7186 V BluetoothMapService: BluetoothMapBinder()
08-16 13:45:00.773  7186  7186 D BluetoothMapService: Received start request. Starting profile...
,08-16 13:45:00.773  7186  7186 D BluetoothMapService: start()
08-16 13:45:00.781  7186  7186 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-16 13:45:00.781  7186  7186 D BluetoothMapEmailAppObserver: createReceiver()
08-16 13:45:00.783  7186  7186 D BluetoothMapEmailAppObserver: initObservers()
,08-16 13:45:00.783  7186  7186 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-16 13:45:00.793  7186  7186 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@df29a71
08-16 13:45:00.794  7186  7854 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-16 13:45:00.794  7186  7854 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-16 13:45:00.795  7186  7854 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-16 13:45:00.799  7186  7186 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 13:45:00.804  7186  7186 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-16 13:45:00.810  7186  7186 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 13:45:00.815  7186  7186 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 13:45:00.816  7186  7186 V PanService: [BTUI] SIM Extra State :ABSENT
08-16 13:45:00.821  7186  7186 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-16 13:45:00.827  7186  7186 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-16 13:45:00.827  7186  7186 V BluetoothMapService: Handler(): got msg=1
08-16 13:45:00.828  7186  7818 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-16 13:45:00.828  7186  7818 I bluedroid-qcom: enable
08-16 13:45:00.828  7186  7818 I bt_hci_bdroid: init
08-16 13:45:00.829  7186  7876 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-16 13:45:00.830  7186  7876 I bt-btu  : btu_task pending for preload complete event
08-16 13:45:00.830  7186  7186 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:45:00.832  7186  7818 I bt_vendor: bt-vendor : init
08-16 13:45:00.832  7186  7818 I bt_vendor: bt-vendor : get_bt_soc_type
08-16 13:45:00.832  7186  7818 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-16 13:45:00.832  7186  7818 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-16 13:45:00.832  7186  7818 D bt_userial_mct: userial_init
08-16 13:45:00.833  7186  7186 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 13:45:00.833  7186  7818 D bt_hci_bdroid: set_power 1
08-16 13:45:00.833  7186  7186 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 13:45:00.833  7186  7186 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 13:45:00.833  7186  7818 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-16 13:45:00.833  7186  7818 I bt_vendor: Starting hciattach daemon
08-16 13:45:00.833  7186  7186 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:45:00.833  7186  7818 I bt_vendor: try to set true
08-16 13:45:00.833  7186  7186 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-16 13:45:00.823  7879  7879 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-16 13:45:00.833  7879  7879 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 13:45:00.873  7880  7880 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-16 13:45:00.884  1036  1904 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7881 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-16 13:45:00.943  7903  7903 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-16 13:45:00.964  7904  7904 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-16 13:45:00.965  7881  7881 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-16 13:45:00.984  1036  1994 I ActivityManager: Killing 7103:com.lge.sync/1000 (adj 15): empty #17
,08-16 13:45:00.988  7906  7906 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
08-16 13:45:00.999  7907  7907 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-16 13:45:01.009  7908  7908 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-16 13:45:01.026  7909  7909 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-16 13:45:01.042  1036  1885 W libprocessgroup: failed to open /acct/uid_1000/pid_7103/cgroup.procs: No such file or directory
,08-16 13:45:01.048  7911  7911 I libmdmdetect: ESOC framework not supported
08-16 13:45:01.049  7911  7911 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
08-16 13:45:01.057  7911  7911 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-16 13:45:01.057  7911  7911 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-16 13:45:01.057  7911  7911 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-16 13:45:01.057  7911  7911 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-16 13:45:01.057  7911  7911 D bthci_qcomm_common: [BTUI]     LE: Class 2
,08-16 13:45:01.057  7911  7911 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
,08-16 13:45:01.058  7911  7911 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
,08-16 13:45:01.096  7911  7912 E QC-QMI  : qmi_client [7911] 14: failed to locate client data
08-16 13:45:01.096   483   483 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-16 13:45:01.097   483   483 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
,08-16 13:45:01.142  7913  7913 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-16 13:45:01.157  7914  7914 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-16 13:45:01.188  7186  7818 I bt_vendor: bluetooth satus is on
08-16 13:45:01.188  7186  7818 D bt_hci_bdroid: preload
,08-16 13:45:01.188  7186  7878 D bt_userial_mct: userial_open(port:0)
08-16 13:45:01.188  7186  7878 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-16 13:45:01.192  7186  7878 I bt_vendor: Done intiailizing UART
08-16 13:45:01.193  7186  7878 I bt_vendor: Done intiailizing UART
08-16 13:45:01.193  7186  7878 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-16 13:45:01.193  7186  7878 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-16 13:45:01.193  7186  7876 I bt-btu  : btu_task received preload complete event
08-16 13:45:01.194  7186  7876 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-16 13:45:01.195  7186  7876 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-16 13:45:01.199  7186  7916 D bt_userial_mct: Entering userial_read_thread()
08-16 13:45:01.200  7186  7876 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
,08-16 13:45:01.207  7186  7876 I         : BTE_InitTraceLevels -- TRC_HCI
,08-16 13:45:01.207  7186  7876 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-16 13:45:01.207  7186  7876 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-16 13:45:01.207  7186  7876 I         : BTE_InitTraceLevels -- TRC_AVDT
08-16 13:45:01.207  7186  7876 I         : BTE_InitTraceLevels -- TRC_AVRC
08-16 13:45:01.207  7186  7876 I         : BTE_InitTraceLevels -- TRC_A2D
08-16 13:45:01.207  7186  7876 I         : BTE_InitTraceLevels -- TRC_BNEP
08-16 13:45:01.207  7186  7876 I         : BTE_InitTraceLevels -- TRC_BTM
08-16 13:45:01.207  7186  7876 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-16 13:45:01.207  7186  7876 I         : BTE_InitTraceLevels -- TRC_GAP
08-16 13:45:01.207  7186  7876 I         : BTE_InitTraceLevels -- TRC_PAN
08-16 13:45:01.207  7186  7876 I         : BTE_InitTraceLevels -- TRC_SDP
08-16 13:45:01.207  7186  7876 I         : BTE_InitTraceLevels -- TRC_GATT
08-16 13:45:01.207  7186  7876 I         : BTE_InitTraceLevels -- TRC_SMP
08-16 13:45:01.207  7186  7876 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-16 13:45:01.207  7186  7876 I         : BTE_InitTraceLevels -- TRC_BTIF
08-16 13:45:01.305  7186  7876 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-16 13:45:01.305  7186  7876 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01db061 
08-16 13:45:01.305  7186  7876 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01db061 
,08-16 13:45:01.367  7186  7822 E bt-btif : Calling BTA_HhEnable,
08-16 13:45:01.367  7186  7822 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-16 13:45:01.367  7186  7822 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17,
,08-16 13:45:01.378  7186  7876 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
,08-16 13:45:01.378  7186  7876 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-16 13:45:01.378  7186  7876 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
,08-16 13:45:01.382  7186  7876 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-16 13:45:01.382  7186  7876 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-16 13:45:01.387  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-16 13:45:01.388  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
,08-16 13:45:01.397  7186  7822 D BluetoothAdapterProperties: Name is: G3
08-16 13:45:01.402  7186  7822 D BluetoothAdapterProperties: Scan Mode:20
08-16 13:45:01.402  7186  7822 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 13:45:01.402  7186  7822 D bt_hci_bdroid: postload
08-16 13:45:01.402  7186  7878 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 13:45:01.404  7186  7876 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
,08-16 13:45:01.406  7186  7876 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 13:45:01.406  7186  7876 W bt-smp  : Plain text(LSB ~ MSB) = 04 db 79 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 13:45:01.406  7186  7876 W bt-smp  : Encrypted text(LSB ~ MSB) = 3c d7 29 b5 a5 0f 30 0d 9c 45 77 5d 59 3e 58 39 
08-16 13:45:01.406  7186  7878 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 13:45:01.407  7186  7876 W bt-btm  : Stopping oneshot timer
08-16 13:45:01.407  7186  7822 D bte_conf: Device ID record 1 : primary
08-16 13:45:01.407  7186  7822 D bte_conf:   vendorId            = 00c4
08-16 13:45:01.407  7186  7822 D bte_conf:   vendorIdSource      = 0001
08-16 13:45:01.407  7186  7822 D bte_conf:   product             = 13a1
08-16 13:45:01.407  7186  7822 D bte_conf:   version             = 1000
08-16 13:45:01.407  7186  7822 D bte_conf:   clientExecutableURL = 
08-16 13:45:01.407  7186  7822 D bte_conf:   serviceDescription  = 
08-16 13:45:01.407  7186  7822 D bte_conf:   documentationURL    = 
08-16 13:45:01.407  7186  7822 D bte_conf: bte_load_did_conf no section named DID2.
08-16 13:45:01.409  7186  7878 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 13:45:01.410  7186  7878 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 13:45:01.412  7186  7916 E bt_mct  : hci lib postload completed
08-16 13:45:01.403  7924  7924 W sh      : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 13:45:01.416  7186  7818 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-16 13:45:01.417  7186  7818 D BluetoothAdapterProperties: ScanMode =  20
,08-16 13:45:01.421  7186  7818 D BluetoothAdapterProperties: State =  11
08-16 13:45:01.421  7186  7818 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-16 13:45:01.422  7186  7818 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-16 13:45:01.422  7186  7818 D BluetoothAdapterProperties: Setting state to 12
08-16 13:45:01.422  7186  7818 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-16 13:45:01.423  7186  7822 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-16 13:45:01.423  7186  7822 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-16 13:45:01.413  7924  7924 W sh      : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 13:45:01.430  1036  1107 D BluetoothManagerService: Message: 60
08-16 13:45:01.430  1036  1107 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-16 13:45:01.430  1036  1107 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
,08-16 13:45:01.434  7186  7818 I BluetoothAdapterState: Entering On State
08-16 13:45:01.449  7186  7818 D LGBluetoothServiceAdapter: [BTUI] OnState
08-16 13:45:01.449  7186  7818 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
,08-16 13:45:01.454  7186  7818 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-16 13:45:01.454  7186  7876 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 13:45:01.454  7186  7876 W bt-smp  : Plain text(LSB ~ MSB) = 34 7d 44 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 13:45:01.454  7186  7876 W bt-smp  : Encrypted text(LSB ~ MSB) = 6e 57 86 71 58 21 6f 49 70 44 76 ce e8 f6 3f 65 
08-16 13:45:01.455  7186  7876 W bt-btm  : Stopping oneshot timer
08-16 13:45:01.460  7186  7818 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-16 13:45:01.460  1851  1867 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 13:45:01.475  7186  7876 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 13:45:01.475  7186  7876 W bt-smp  : Plain text(LSB ~ MSB) = ff 83 7e 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 13:45:01.475  7186  7876 W bt-smp  : Encrypted text(LSB ~ MSB) = e7 c6 43 53 87 59 c9 6c 81 a0 75 4a c7 ce 96 12 
,08-16 13:45:01.478  7186  7876 W bt-btm  : Stopping oneshot timer
08-16 13:45:01.485  7186  7818 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-16 13:45:01.485  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:45:01.485  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:45:01.485  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 13:45:01.485  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 13:45:01.485  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 13:45:01.485  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 13:45:01.485  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 13:45:01.485  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 13:45:01.486  7186  7822 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 13:45:01.486  7186  7822 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-16 13:45:01.490  6936  6936 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 13:45:01.494  7186  7876 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 13:45:01.494  7186  7876 W bt-smp  : Plain text(LSB ~ MSB) = 1a 1a 47 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 13:45:01.494  7186  7876 W bt-smp  : Encrypted text(LSB ~ MSB) = 66 20 bd db c1 ee 09 a9 56 86 92 76 e2 ed 5f f6 
08-16 13:45:01.494  7186  7876 W bt-btm  : Stopping oneshot timer
08-16 13:45:01.505  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:45:01.505  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:45:01.505  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 13:45:01.505  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 13:45:01.505  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 13:45:01.505  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 13:45:01.505  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 13:45:01.505  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 13:45:01.508  7186  7876 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 13:45:01.508  7186  7876 W bt-smp  : Plain text(LSB ~ MSB) = 3b 75 49 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 13:45:01.508  7186  7876 W bt-smp  : Encrypted text(LSB ~ MSB) = ba 91 60 9a fc a5 35 7b fb 56 fa 91 bb b8 14 21 
08-16 13:45:01.509  7186  7876 W bt-btm  : Stopping oneshot timer
08-16 13:45:01.516  6936  6936 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 13:45:01.537  1851  1851 D BluetoothHeadset: Proxy object connected
,08-16 13:45:01.541  1036  1107 D BluetoothA2dp: onBluetoothStateChange: up=true
08-16 13:45:01.544  1036  1036 D BluetoothA2dp: Proxy object connected
08-16 13:45:01.551  1851  1866 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-16 13:45:01.555  1851  1851 D BluetoothHeadset: Proxy object connected
08-16 13:45:01.557  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:45:01.557  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:45:01.557  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 13:45:01.557  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 13:45:01.557  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 13:45:01.557  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 13:45:01.557  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 13:45:01.557  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 13:45:01.558  7939  7939 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-16 13:45:01.560  6936  6936 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 13:45:01.560  1036  1107 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 13:45:01.561  1036  1036 D BluetoothHeadset: Proxy object connected
08-16 13:45:01.563  1851  2444 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 13:45:01.566  1851  1851 D BluetoothHeadset: Proxy object connected
,08-16 13:45:01.566  7122  7139 D BluetoothPbap: onBluetoothStateChange: up=true
08-16 13:45:01.569  7122  7138 D BluetoothMap: onBluetoothStateChange: up=true
08-16 13:45:01.573  7122  7139 D BluetoothPan: onBluetoothStateChange on: true
08-16 13:45:01.573  7122  7139 D BluetoothPan: onBluetoothStateChange call bindService
08-16 13:45:01.574  7122  7122 D BluetoothMap: Proxy object connected
08-16 13:45:01.574  7122  7122 D MapProfile: Bluetooth service connected
08-16 13:45:01.574  7122  7122 D BluetoothMap: getConnectedDevices()
08-16 13:45:01.576  7122  7138 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-16 13:45:01.578  7186  7940 V BluetoothMapService: getConnectedDevices()
,08-16 13:45:01.580  7122  7122 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 13:45:01.580  1036  1107 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-16 13:45:01.580  7122  7122 D PanProfile: Bluetooth service connected
08-16 13:45:01.580  1036  1107 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-16 13:45:01.581  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:45:01.582  1941  2125 D LGBluetoothAPIService: Message: 1
08-16 13:45:01.582  1941  2125 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-16 13:45:01.585  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 13:45:01.590  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,08-16 13:45:01.591  1036  1107 D BluetoothManagerService: Message: 40
08-16 13:45:01.591  1036  1107 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-16 13:45:01.594  1941  2125 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-16 13:45:01.595  6936  6936 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
08-16 13:45:01.598  7122  7122 D BluetoothInputDevice: Proxy object connected
08-16 13:45:01.598  7122  7122 D HidProfile: Bluetooth service connected
08-16 13:45:01.598  7186  7186 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:45:01.598  7186  7186 D BluetoothMapService: STATE_ON
08-16 13:45:01.599  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:45:01.600  7186  7186 D LGBluetoothAPIServer: [BTUI] onCreate()
08-16 13:45:01.600  7186  7186 D LGBluetoothAPIServer: [BTUI] onBind()
08-16 13:45:01.601  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:45:01.603  1941  1941 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-16 13:45:01.603  1941  2125 D LGBluetoothAPIService: Message: 100
08-16 13:45:01.603  1941  2125 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
,08-16 13:45:01.606  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:45:01.607  7122  7122 D LocalBluetoothProfileManager: Adding local A2DP profile
08-16 13:45:01.610  1036  1107 D BluetoothManagerService: Message: 30
08-16 13:45:01.612  7122  7122 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-16 13:45:01.615  1036  1107 D BluetoothManagerService: Message: 30
,08-16 13:45:01.621  7186  7186 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@df29a71
08-16 13:45:01.621  7186  7186 V BluetoothPbapService: Pbap Service onCreate
08-16 13:45:01.621  7122  7122 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-16 13:45:01.621  7186  7186 V BluetoothPbapService: Starting PBAP service
08-16 13:45:01.622  7186  7186 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-16 13:45:01.622  7122  7122 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-16 13:45:01.623  7186  7186 V BluetoothPbapService: Pbap Service onBind
08-16 13:45:01.625  7186  7186 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:45:01.625  7186  7186 V BluetoothPbapService: state: 12
08-16 13:45:01.625  7186  7186 V BluetoothMapService: Handler(): got msg=1
08-16 13:45:01.625  7122  7122 D BluetoothA2dp: Proxy object connected
08-16 13:45:01.626  7186  7186 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-16 13:45:01.626  7122  7122 D A2dpProfile: Bluetooth service connected
,08-16 13:45:01.626  7186  7186 V BluetoothPbapService: Handler(): got msg=1
08-16 13:45:01.627  7186  7186 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-16 13:45:01.627  7186  7950 D BluetoothMapMasInstance: MAS initSocket()
08-16 13:45:01.628  7186  7950 D BluetoothMapMasInstance:   masId = 00
08-16 13:45:01.628  7186  7950 D BluetoothMapMasInstance:   msgTypes = 0e
08-16 13:45:01.628  7186  7950 D BluetoothMapMasInstance:   masName = SMS/MMS
08-16 13:45:01.628  7186  7950 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
,08-16 13:45:01.630  7186  7951 V BluetoothPbapService: Pbap Service initSocket
08-16 13:45:01.631  1036  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 13:45:01.631  1036  1958 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 13:45:01.632  7186  7950 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 13:45:01.633  7186  7951 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 13:45:01.635  7186  7186 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-16 13:45:01.635  7186  7186 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:45:01.635  7186  7186 V BluetoothPbapReceiver: ***********state = 12
08-16 13:45:01.636  7186  7951 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-16 13:45:01.636  7186  7951 V BluetoothPbapService: Succeed to create listening socket 
08-16 13:45:01.636  7186  7951 V BluetoothPbapService: Accepting socket connection...
08-16 13:45:01.636  7186  7950 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-16 13:45:01.636  7186  7950 V BluetoothMapMasInstance: Succeed to create listening socket 
08-16 13:45:01.637  7186  7950 D BluetoothMapMasInstance: Accepting socket connection...
08-16 13:45:01.637  7186  7822 D BluetoothAdapterProperties: Scan Mode:21
08-16 13:45:01.637  7186  7822 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-16 13:45:01.637  7122  7122 D BluetoothHeadset: Proxy object connected
08-16 13:45:01.638  7122  7122 D HeadsetProfile: Bluetooth service connected
08-16 13:45:01.640  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:45:01.642  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:45:01.643  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:45:01.645  2175  2175 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 13:45:01.646  2175  2175 D c       : Getting all permits...
08-16 13:45:01.646  2175  2175 D a       : Opening database...
08-16 13:45:01.649  7122  7122 D DockEventReceiver: finishStartingService: stopping service
08-16 13:45:01.650  7122  7122 D BluetoothPbap: Proxy object connected
08-16 13:45:01.650  7122  7122 D PbapServerProfile: Bluetooth service connected
08-16 13:45:01.651  2175  2175 D a       : Opening database auth.proximity.permit_store...
08-16 13:45:01.652  2175  2175 D a       : Closing database...
,08-16 13:45:01.664  7122  7122 D BluetoothPermissionRequest: onReceive
,08-16 13:45:01.666  7122  7122 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,08-16 13:45:01.668  7122  7122 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-16 13:45:01.672  7186  7186 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-16 13:45:01.674  7186  7186 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-16 13:45:01.685  7186  7186 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-16 13:45:01.722  7186  7186 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-16 13:45:01.722  7186  7186 V BtOppService: onCreate
,08-16 13:45:01.728  7186  7186 V BluetoothOppNotification: send message
08-16 13:45:01.733  7186  7186 V BtOppService: Starting RfcommListener
08-16 13:45:01.742  7186  7186 D BluetoothOppPreference: Dumping Names:  
08-16 13:45:01.742  7186  7186 D BluetoothOppPreference: {}
08-16 13:45:01.742  7186  7186 D BluetoothOppPreference: Dumping Channels:  
,08-16 13:45:01.742  7186  7186 D BluetoothOppPreference: {}
08-16 13:45:01.743  7186  7186 V BtOppService: onStartCommand
08-16 13:45:01.750  7186  7186 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:45:01.750  7186  7186 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-16 13:45:01.753  7186  7960 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-16 13:45:01.757  7186  7186 V BluetoothOppNotification: new notify threadi!
,08-16 13:45:01.758  7186  7186 V BluetoothOppNotification: send delay message
,08-16 13:45:01.759  7186  7186 V BtOppService: start RfcommListener
08-16 13:45:01.762  7186  7960 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-16 13:45:01.762  7186  7957 V BtOppService: Deleted complete outbound shares, number =  0
08-16 13:45:01.763  7186  7961 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-16 13:45:01.763  7186  7960 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@17b900f2 on behalf of 
08-16 13:45:01.765  7186  7961 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@253b5343 on behalf of 
08-16 13:45:01.765  7186  7960 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-16 13:45:01.767  7186  7957 V BtOppService: Deleted complete inbound failed shares, number = 0
08-16 13:45:01.768  7186  7961 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-16 13:45:01.769  7186  7186 V BtOppService: RfcommListener started
,08-16 13:45:01.771  7186  7962 V BtOppRfcommListener: Starting RFCOMM listener....
08-16 13:45:01.771  1036  1885 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 13:45:01.772  7186  7957 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-16 13:45:01.772  7186  7962 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 13:45:01.773  7186  7957 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@16730dc0 on behalf of 
08-16 13:45:01.774  7186  7962 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
08-16 13:45:01.774  7186  7961 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-16 13:45:01.775  7186  7962 V BtOppRfcommListener: Started RFCOMM listener....
08-16 13:45:01.775  7186  7962 I BtOppRfcommListener: Accept thread started.
08-16 13:45:01.775  7186  7962 V BtOppRfcommListener: Accepting connection...
08-16 13:45:01.776  7186  7961 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3fad8af9 on behalf of 
08-16 13:45:01.777  7186  7961 V BluetoothOppNotification: outbound: succ-0  fail-0
08-16 13:45:01.779  7186  7961 V BluetoothOppNotification: outbound notification was removed.
08-16 13:45:01.779  7186  7961 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-16 13:45:01.780  7186  7961 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@32d23a3e on behalf of 
08-16 13:45:01.781  7186  7961 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-16 13:45:01.783  7186  7961 V BluetoothOppNotification: inbound notification was removed.
08-16 13:45:01.783  7186  7961 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-16 13:45:01.785  7186  7961 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3b35e09f on behalf of 
08-16 13:45:01.789  7186  7186 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@df29a71
08-16 13:45:01.790  7186  7186 V BluetoothFtpService: Ftp Service onCreate
08-16 13:45:01.790  7186  7186 I BluetoothFtpService: Ftp Service onCreate
08-16 13:45:01.790  7186  7186 V BluetoothFtpService: Ftp Service onStartCommand
08-16 13:45:01.790  7186  7186 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:45:01.790  7186  7186 V BluetoothFtpService: Starting Listening on sockets
08-16 13:45:01.790  7186  7186 V BtOppService: ContentObserver received notification
08-16 13:45:01.791  7186  7186 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 13:45:01.791  7186  7186 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 13:45:01.791  7186  7186 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 13:45:01.791  7186  7186 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:45:01.791  7186  7186 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-16 13:45:01.791  7186  7186 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-16 13:45:01.792  7186  7963 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-16 13:45:01.792  7186  7963 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-16 13:45:01.793  7186  7186 V BtOppService: ContentObserver received notification
,08-16 13:45:01.793  7186  7186 V BluetoothFtpService: Handler(): got msg=1
08-16 13:45:01.794  7186  7186 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-16 13:45:01.794  7186  7186 V BluetoothFtpService: Ftp Service initSocket
08-16 13:45:01.798  1036  1755 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 13:45:01.798  7186  7963 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@28b2ddb5 on behalf of 
08-16 13:45:01.799  7186  7963 V BluetoothOppNotification: update too frequent, put in queue
08-16 13:45:01.799  7186  7186 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 13:45:01.800  7186  7186 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=81 mFd=79
08-16 13:45:01.800  7186  7186 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-16 13:45:01.802  7186  7963 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-16 13:45:01.802  7186  7964 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-16 13:45:01.802  7186  7963 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-16 13:45:01.804  7186  7963 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2b3bc4a on behalf of 
08-16 13:45:01.805  7186  7963 V BluetoothOppNotification: update too frequent, put in queue
08-16 13:45:01.806  7186  7963 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
,08-16 13:45:01.817  7186  7186 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@df29a71
,08-16 13:45:01.817  7186  7186 V BluetoothSapService: Sap Service onCreate
08-16 13:45:01.819  7186  7186 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:45:01.819  7186  7186 V BluetoothSapService: state: 12
08-16 13:45:01.819  7186  7186 V BluetoothSapService: Starting SAP server process
,08-16 13:45:01.813  7965  7965 W sapd    : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 13:45:01.824  7186  7186 V BluetoothSapService: SAP Service startRfcommListenerThread
08-16 13:45:01.826  7186  7966 V BluetoothSapService: Sap Service initRfcommSocket
08-16 13:45:01.826  1036  1904 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 13:45:01.813  7965  7965 W sapd    : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-16 13:45:01.827  7186  7966 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 13:45:01.829  7186  7966 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=81
08-16 13:45:01.829  7186  7966 V BluetoothSapService: Succeed to create listening socket 
08-16 13:45:01.829  7186  7966 V BluetoothSapService: Accepting socket connection...
,08-16 13:45:01.839  7965  7965 V BT_SAP  : Event pipe created
08-16 13:45:01.839  7965  7965 V BT_SAP  : create_server_socket qcom.sap.server
08-16 13:45:01.839  7965  7965 V BT_SAP  : created socket fd 6
08-16 13:45:02.257  1603  1603 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-16 13:45:02.345  1036  1093 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7976 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-16 13:45:02.351  1603  1603 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
08-16 13:45:02.352  1603  1603 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
08-16 13:45:02.397  1036  1036 D administrator: Handling package changes for user 0
,08-16 13:45:02.439  1036  1441 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-16 13:45:02.442  2034  2034 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-16 13:45:02.460  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-16 13:45:02.467  7976  7976 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-16 13:45:02.548  7976  7976 D LgDataFeature: LgDataFeature() Constructor: none
08-16 13:45:02.548  7976  7976 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 13:45:02.570  1036  1036 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-16 13:45:02.570  1036  1036 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-16 13:45:02.638  1036  1092 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-16 13:45:02.649  1036  1092 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-16 13:45:02.653  7976  8021 I Babel   : MmsConfig: mnc/mcc: 0/0
08-16 13:45:02.653  7976  8021 I Babel   : MmsConfig.loadMmsSettings
,08-16 13:45:02.657  2034  2034 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-16 13:45:02.658  2474  2474 V GmsNetworkLocationProvi: DISABLE
08-16 13:45:02.664  7976  8021 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-16 13:45:02.664  7976  8021 I Babel   : MmsConfig.loadFromDatabase
,08-16 13:45:02.687  7976  8021 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-16 13:45:02.687  7976  8021 I Babel   : MmsConfig.loadFromResources
08-16 13:45:02.689  1036  1092 D LocationProviderProxy: applying state to connected service
08-16 13:45:02.691  2474  2474 E GCoreFlp: Bound FusedProviderService with LocationManager
08-16 13:45:02.693  7976  8021 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-16 13:45:02.694  7976  8021 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-16 13:45:02.695  7976  7976 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 13:45:02.710  7976  8019 W AudioCapabilities: Unsupported mime audio/evrc
,08-16 13:45:02.711  7976  8019 W AudioCapabilities: Unsupported mime audio/qcelp
08-16 13:45:02.713  7976  8019 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-16 13:45:02.726  7976  8019 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,08-16 13:45:02.730  1816  8025 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-16 13:45:02.730  1816  8025 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
08-16 13:45:02.731  7309  7309 I AppUp4:CustModeStarterReceiver: onReceive
08-16 13:45:02.731  7976  8019 W AudioCapabilities: Unsupported mime audio/qcelp
08-16 13:45:02.733  7976  8019 W AudioCapabilities: Unsupported mime audio/evrc
,08-16 13:45:02.738  7309  7309 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@166647fb
08-16 13:45:02.738  7309  7309 D AppUp4:CustFacade: isCustomizationCompleted : false
08-16 13:45:02.738  7309  7309 D AppUp4:CustFacade: isPhone : true
08-16 13:45:02.738  7309  7309 D AppUp4:CustModeStarterReceiver: begin check event
,08-16 13:45:02.739  7309  7309 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-16 13:45:02.747  1816  5159 I Icing   : updateResources: need to parse e{com.google.android.gms}
08-16 13:45:02.747  7976  8019 W VideoCapabilities: Unsupported mime video/x-ms-wmv
08-16 13:45:02.750  7976  8019 W VideoCapabilities: Unsupported mime video/divx
08-16 13:45:02.752  7976  8019 W VideoCapabilities: Unsupported mime video/divx311
,08-16 13:45:02.754  7976  8019 W VideoCapabilities: Unsupported mime video/divx4
08-16 13:45:02.760  7186  7186 V BluetoothOppNotification: new notify threadi!
08-16 13:45:02.760  7186  7186 V BluetoothOppNotification: send delay message
08-16 13:45:02.759  7976  8019 W VideoCapabilities: Unsupported mime video/mp4v-esdp
08-16 13:45:02.761  7186  8028 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-16 13:45:02.769  1036  1051 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=8029 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,08-16 13:45:02.772  1036  1958 I ActivityManager: Killing 7338:com.lge.email/u0a23 (adj 15): empty #17
08-16 13:45:02.773  7186  8028 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@24795316 on behalf of 
08-16 13:45:02.774  7186  8028 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-16 13:45:02.782  7976  8019 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-16 13:45:02.782  7186  8028 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-16 13:45:02.788  7186  8028 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@17fd4497 on behalf of 
08-16 13:45:02.788  7186  8028 V BluetoothOppNotification: outbound: succ-0  fail-0
08-16 13:45:02.790  7186  8028 V BluetoothOppNotification: outbound notification was removed.
08-16 13:45:02.790  7186  8028 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-16 13:45:02.792  7976  8019 W AudioCapabilities: Unsupported mime audio/eac3
08-16 13:45:02.792  7976  8019 W AudioCapabilities: Unsupported mime audio/ac3
08-16 13:45:02.793  7976  8019 W AudioCapabilities: Unsupported mime audio/g726
08-16 13:45:02.794  7976  8019 W AudioCapabilities: Unsupported mime audio/wma-voice
08-16 13:45:02.796  7976  8019 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,08-16 13:45:02.799  7976  8019 W AudioCapabilities: Unsupported mime audio/adpcm
08-16 13:45:02.801  7976  8019 W VideoCapabilities: Unsupported mime video/theora
08-16 13:45:02.802  7976  8019 W VideoCapabilities: Unsupported mime video/mjpg
08-16 13:45:02.876  1036  1646 I art     : Explicit concurrent mark sweep GC freed 81540(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 1.175ms total 85.773ms
08-16 13:45:02.877  7186  8028 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@5866684 on behalf of 
08-16 13:45:02.879  7186  8028 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-16 13:45:02.882  7186  8028 V BluetoothOppNotification: inbound notification was removed.
08-16 13:45:02.882  7186  8028 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-16 13:45:02.888  7186  8028 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1b8e0e6d on behalf of 
08-16 13:45:02.901  1036  1051 W libprocessgroup: failed to open /acct/uid_10023/pid_7338/cgroup.procs: No such file or directory
,08-16 13:45:02.918  8029  8029 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 13:45:02.918  8029  8029 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 13:45:02.918  8029  8029 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-16 13:45:02.919  8029  8029 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-16 13:45:02.919  8029  8029 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,08-16 13:45:02.969  8029  8029 I SystemConfig: BUILD Country: EU
08-16 13:45:02.969  8029  8029 I SystemConfig: BUILD Operator: OPEN
,08-16 13:45:03.003  1036  1575 I ActivityManager: Killing 7234:com.lge.formmanager/u0a26 (adj 15): empty #17
,08-16 13:45:03.072  1036  1958 W libprocessgroup: failed to open /acct/uid_10026/pid_7234/cgroup.procs: No such file or directory
,08-16 13:45:03.087  8029  8047 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-16 13:45:03.087  8029  8047 I SystemConfig: existFile = false
08-16 13:45:03.087  8029  8047 I SystemConfig: canReadFile = false
,08-16 13:45:03.087  8029  8047 I SystemConfig: systemFeature RCS result false
08-16 13:45:03.088  8029  8047 D SystemConfig: refreshRcsSupport() :false
08-16 13:45:03.152  1036  1994 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=8049 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-16 13:45:03.203  8049  8049 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-16 13:45:03.204  8049  8049 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-16 13:45:03.204  8049  8049 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-16 13:45:03.204  8049  8049 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-16 13:45:03.327  8049  8049 I AppConfig: Total System Memory = 2995761152
,08-16 13:45:03.342  8049  8049 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
,08-16 13:45:03.442  1036  1922 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8074 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-16 13:45:03.443  1036  1922 I ActivityManager: Killing 6395:com.wsandroid.suite.lge/1000 (adj 15): empty #17
08-16 13:45:03.489  1036  1093 W ProcessCpuTracker: Skipping unknown process pid 8002
08-16 13:45:03.490  1036  1093 W ProcessCpuTracker: Skipping unknown process pid 8003
,08-16 13:45:03.490  1036  1093 W ProcessCpuTracker: Skipping unknown process pid 8006
,08-16 13:45:03.491  1036  1093 W ProcessCpuTracker: Skipping unknown process pid 8009
08-16 13:45:03.493  1036  1093 W ProcessCpuTracker: Skipping unknown process pid 8068
,08-16 13:45:03.563  1036  1575 W libprocessgroup: failed to open /acct/uid_1000/pid_6395/cgroup.procs: No such file or directory
08-16 13:45:03.763  8074  8074 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-16 13:45:03.849  8074  8074 D LgDataFeature: LgDataFeature() Constructor: none
08-16 13:45:03.849  8074  8074 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 13:45:03.920  8074  8074 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-16 13:45:03.942  8074  8074 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-16 13:45:03.943  8074  8074 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-16 13:45:03.973  8074  8074 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-16 13:45:03.974  8074  8074 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
08-16 13:45:04.001  1036  1646 I ActivityManager: Killing 7368:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,08-16 13:45:04.025  2851  3085 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-16 13:45:04.025  1036  2033 W libprocessgroup: failed to open /acct/uid_10046/pid_7368/cgroup.procs: No such file or directory
,08-16 13:45:04.029  2851  3085 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@4982daf on behalf of 8074
08-16 13:45:04.032  4997  8111 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
08-16 13:45:04.084  1036  1940 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=8112 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-16 13:45:04.109  8074  8074 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-16 13:45:04.130  8074  8074 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-16 13:45:04.180  8112  8112 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-16 13:45:04.203  8112  8112 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-16 13:45:04.203  8112  8112 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-16 13:45:04.203  8112  8112 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-16 13:45:04.203  8112  8112 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-16 13:45:04.203  8112  8112 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-16 13:45:04.203  8112  8112 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,08-16 13:45:04.231  1036  1922 I ActivityManager: Killing 7403:com.android.chrome/u0a57 (adj 15): empty #17
,08-16 13:45:04.270  1036  1940 W libprocessgroup: failed to open /acct/uid_10057/pid_7403/cgroup.procs: No such file or directory
,08-16 13:45:04.420  1036  1575 V SIM_STK : Menu title from STK is T-Mobile
,08-16 13:45:04.441  4997  8111 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 409 ms] updated apps [took 409 ms] 
,08-16 13:45:05.213  1036  2033 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-16 13:45:05.213  1036  2033 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@cec5de5 mBinding = false
,08-16 13:45:05.246  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 13:45:05.246  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 13:45:05.247  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-16 13:45:05.247  1036  1107 D BluetoothManagerService: Message: 2
08-16 13:45:05.248  1036  1107 D BluetoothManagerService: Sending off request.
08-16 13:45:05.249  7186  7948 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-16 13:45:05.250  7186  7818 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-16 13:45:05.250  7186  7818 D BluetoothAdapterProperties: Setting state to 13
08-16 13:45:05.250  7186  7818 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-16 13:45:05.251  7186  7818 D BluetoothAdapterProperties: onBluetoothDisable()
08-16 13:45:05.251  7186  7818 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-16 13:45:05.253  7186  7822 D BluetoothAdapterProperties: Scan Mode:20
08-16 13:45:05.254  7186  7818 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-16 13:45:05.257  7186  7818 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-16 13:45:05.262  7186  7951 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 13:45:05.263  7186  7950 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-16 13:45:05.263  7186  7950 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 13:45:05.263  7186  7950 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-16 13:45:05.263  7186  7950 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-16 13:45:05.263  7186  7950 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-16 13:45:05.263  7186  7950 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-16 13:45:05.263  7186  7950 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-16 13:45:05.263  7186  7950 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-16 13:45:05.264  7186  7964 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 13:45:05.265  7186  7876 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-16 13:45:05.265  7186  7876 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-16 13:45:05.266  7186  7966 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 13:45:05.267  7186  7962 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 13:45:05.276  7186  7876 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 13:45:05.276  7186  7876 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 13:45:05.276  7186  7876 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 13:45:05.276  7186  7876 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 13:45:05.276  7186  7876 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 13:45:05.276  7186  7876 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 13:45:05.276  7186  7876 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 13:45:05.276  7186  7876 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 13:45:05.276  7186  7876 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 13:45:05.276  7186  7876 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-16 13:45:05.276  7186  7876 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
,08-16 13:45:05.279  7186  7876 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-16 13:45:05.284  6936  6936 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:45:05.284  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:45:05.284  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:45:05.284  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 13:45:05.284  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 13:45:05.284  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 13:45:05.284  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 13:45:05.284  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 13:45:05.284  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 13:45:05.285  6936  6936 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:45:05.285  6936  6936 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 13:45:05.288  6936  6936 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:45:05.288  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:45:05.288  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:45:05.288  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 13:45:05.288  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 13:45:05.288  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 13:45:05.288  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 13:45:05.288  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 13:45:05.288  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 13:45:05.292  6936  6936 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:45:05.292  6936  6936 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 13:45:05.295  6936  6936 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:45:05.295  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:45:05.295  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:45:05.295  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 13:45:05.295  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 13:45:05.295  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 13:45:05.295  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 13:45:05.295  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 13:45:05.295  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 13:45:05.297  6936  6936 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:45:05.297  6936  6936 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 13:45:05.300  1036  1107 D BluetoothManagerService: Message: 60
08-16 13:45:05.300  1036  1107 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-16 13:45:05.300  1036  1107 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
,08-16 13:45:05.304  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:45:05.308  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 13:45:05.313  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:45:05.316  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:45:05.318  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:45:05.320  7186  7186 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:45:05.320  7186  7186 D BluetoothMapService: STATE_TURNING_OFF
08-16 13:45:05.320  7186  7186 V BluetoothMapService: Handler(): got msg=4
08-16 13:45:05.320  7186  7186 D BluetoothMapService: MAP Service closeService in
08-16 13:45:05.320  7186  7186 D BluetoothMapMasInstance: MAP Service shutdown
08-16 13:45:05.320  7186  7186 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-16 13:45:05.321  7186  7186 V BluetoothMapService: MAP Service closeService out
08-16 13:45:05.322  7186  7186 V BtOppService: Receiver DISABLED_ACTION 
08-16 13:45:05.322  7186  7186 I BtOppRfcommListener: stopping Accept Thread
08-16 13:45:05.322  7186  7186 V BtOppRfcommListener: close mBtServerSocket
08-16 13:45:05.322  7186  7962 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-16 13:45:05.323  7186  7186 V BtOppRfcommListener: waiting for thread to terminate
08-16 13:45:05.323  7186  7186 V BtOppRfcommListener: done waiting for thread to terminate
08-16 13:45:05.327  7122  7122 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
,08-16 13:45:05.336  6936  6997 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:45:05.336  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:45:05.340  7122  7122 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-16 13:45:05.343  7186  7186 V BtOppService: onDestroy
08-16 13:45:05.345  7186  7186 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-16 13:45:05.347  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:45:05.347  6936  6997 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@18b4c414 removed from the list
08-16 13:45:05.347  6936  6997 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:45:05.347  6936  6997 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:45:05.347  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:45:05.348  6936  6997 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 13:45:05.348  6936  6997 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@309c8ab2 added. We now have 4 listener(s)
08-16 13:45:05.348  6936  6997 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 13:45:05.351  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:45:05.352  6936  6997 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@309c8ab2 removed from the list
08-16 13:45:05.352  6936  6997 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:45:05.352  6936  6997 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:45:05.352  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 13:45:05.355  1036  1545 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
08-16 13:45:05.357  6936  6997 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 13:45:05.357  6936  6997 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1c957a03 added. We now have 4 listener(s)
08-16 13:45:05.357  6936  6997 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 13:45:05.360  7186  7186 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-16 13:45:05.360  7186  7186 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:45:05.360  7186  7186 V BluetoothPbapReceiver: ***********state = 13
08-16 13:45:05.362  7186  7186 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-16 13:45:05.363  7186  7186 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:45:05.363  7186  7186 V BluetoothPbapService: state: 13
08-16 13:45:05.363  7186  7186 V BluetoothPbapService: Pbap Service closeService in
,08-16 13:45:05.370  2175  2175 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 13:45:05.372  7186  7186 V BluetoothPbapService: successfully stopped pbap service
08-16 13:45:05.372  7186  7186 V BluetoothPbapService: Pbap Service closeService out
08-16 13:45:05.373  7186  7186 V BluetoothPbapService: Pbap Service onDestroy
08-16 13:45:05.373  7186  7186 V BluetoothPbapService: Pbap Service closeService in
08-16 13:45:05.373  7186  7186 V BluetoothPbapService: Pbap Service closeService out
08-16 13:45:05.374  7186  7186 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-16 13:45:05.388  1036  1922 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 13:45:05.388  1036  1922 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@cec5de5 mBinding = false
,08-16 13:45:05.391  1036  1107 D BluetoothManagerService: Message: 2
08-16 13:45:05.392  1036  1107 D BluetoothManagerService: Sending off request.
08-16 13:45:05.393  7186  7940 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-16 13:45:05.393  7122  7122 D DockEventReceiver: finishStartingService: stopping service
08-16 13:45:05.394  7186  7940 D BluetoothAdapterService: disable() : BT State is not STATE_ON. Can't disable BT
08-16 13:45:05.394  7122  7122 D BluetoothPbap: Proxy object disconnected
08-16 13:45:05.395  7122  7122 D PbapServerProfile: Bluetooth service disconnected
08-16 13:45:05.395  1036  1107 E BluetoothManagerService: IBluetooth.disable() returned false
08-16 13:45:05.408  7122  7122 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-16 13:45:05.428  7122  7122 D BluetoothPermissionRequest: onReceive
08-16 13:45:05.428  7122  7122 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-16 13:45:05.436  7122  7122 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-16 13:45:05.444  7186  7186 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
,08-16 13:45:05.444  7186  7186 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-16 13:45:05.445  7186  7186 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-16 13:45:05.450  7186  7186 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:45:05.450  7186  7186 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-16 13:45:05.452  7186  7186 V BluetoothFtpService: Ftp Service onStartCommand
08-16 13:45:05.452  7186  7186 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:45:05.452  7186  7186 V BluetoothFtpService: Ftp Service closeService
,08-16 13:45:05.453  7186  7186 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-16 13:45:05.456  7186  7186 V BluetoothFtpService: successfully stopped ftp service
08-16 13:45:05.456  7186  7186 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 13:45:05.457  7186  7186 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 13:45:05.457  7186  7186 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 13:45:05.457  7186  7186 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:45:05.457  7186  7186 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-16 13:45:05.457  7186  7186 V BluetoothSapReceiver: Calling SAP service start service with action = null
,08-16 13:45:05.459  7186  7186 V BluetoothFtpService: Ftp Service onDestroy
,08-16 13:45:05.459  7186  7186 V BluetoothFtpService: Ftp Service closeService
08-16 13:45:05.462  7186  7186 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:45:05.462  7186  7186 V BluetoothSapService: state: 13
08-16 13:45:05.463  7186  7186 V BluetoothSapService: Stopping SAP server process
,08-16 13:45:05.465  7186  7186 V BluetoothSapService: Sap Service closeSapService in
08-16 13:45:05.465  7186  7186 V BluetoothSapService: Close listen Socket : 
08-16 13:45:05.466  7186  7186 V BluetoothSapService: Close rfcomm Socket : 
08-16 13:45:05.466  7186  7186 V BluetoothSapService: Close sapd  Socket : 
08-16 13:45:05.466  7186  7186 V BluetoothSapService: Sap Service closeSapService out
,08-16 13:45:05.467  7186  7186 V BluetoothSapService: Sap Service onDestroy,
,08-16 13:45:05.467  7186  7186 V BluetoothSapService: Sap Service closeSapService in
,08-16 13:45:05.467  7186  7186 V BluetoothSapService: Close listen Socket : ,
,08-16 13:45:05.467  7186  7186 V BluetoothSapService: Close rfcomm Socket : 
,08-16 13:45:05.467  7186  7186 V BluetoothSapService: Close sapd  Socket : ,
,08-16 13:45:05.467  7186  7186 V BluetoothSapService: Sap Service closeSapService out
,08-16 13:45:06.212  7186  7822 D bt_hci_bdroid: cleanup,
,08-16 13:45:06.235  7186  7878 I bt_lpm  : LPM is already off!!!
08-16 13:45:06.235  7186  7916 I bt_userial_mct: exiting userial_read_thread
08-16 13:45:06.235  7186  7916 D bt_userial_mct: Leaving userial_evt_read_thread()
08-16 13:45:06.241  7186  7876 W bt-btif : ag scb idx 1 not allocated
08-16 13:45:06.241  7186  7876 E bt-btif : BTA AG is already disabled, ignoring ...
08-16 13:45:06.241  7186  7876 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 13:45:06.241  7186  7876 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration,
08-16 13:45:06.241  7186  7876 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 13:45:06.241  7186  7876 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 13:45:06.241  7186  7876 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 13:45:06.241  7186  7876 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-16 13:45:06.241  7186  7876 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 13:45:06.241  7186  7876 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 13:45:06.241  7186  7876 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 13:45:06.241  7186  7876 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-16 13:45:06.241  7186  7876 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 13:45:06.241  7186  7876 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 13:45:06.241  7186  7876 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 13:45:06.241  7186  7876 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration,
08-16 13:45:06.241  7186  7876 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017,
08-16 13:45:06.241  7186  7876 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 13:45:06.241  7186  7876 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 13:45:06.241  7186  7876 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 13:45:06.241  7186  7876 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif,
,08-16 13:45:06.245  7186  7822 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-16 13:45:06.246  7186  7878 I bt_vendor: hw_epilog_process
08-16 13:45:06.247  7186  7822 D bt_hci_bdroid: cleanup Finalizing cleanup
08-16 13:45:06.247  7186  7822 D bt_userial_mct: userial_close
08-16 13:45:06.248  7186  7822 E bt_userial_mct: pthread_join() FAILED result:3
08-16 13:45:06.248  7186  7822 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-16 13:45:06.260  7186  7822 D bt_hci_bdroid: set_power 0
,08-16 13:45:06.263  7186  7822 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-16 13:45:06.263  7186  7822 I bt_vendor: bluetooth satus is on
08-16 13:45:06.263  7186  7822 I bt_vendor: bt-vendor : resetting BT status
08-16 13:45:06.264  7186  7822 I bt_vendor: Starting hciattach daemon
08-16 13:45:06.264  7186  7822 I bt_vendor: try to set false
08-16 13:45:06.266  7186  7822 I bt_vendor: Starting hciattach daemon
08-16 13:45:06.266  7186  7822 I bt_vendor: try to set false
08-16 13:45:06.267  7186  7822 I bt_vendor: cleanup
08-16 13:45:06.268  7186  7876 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-16 13:45:06.268  7186  7822 I GKI_LINUX: GKI_exit_task 0 done
08-16 13:45:06.268  7186  7822 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-16 13:45:06.270  7186  7818 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-16 13:45:06.276  7186  7186 D HeadsetService: Received stop request...Stopping profile...
,08-16 13:45:06.282  7186  7186 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-16 13:45:06.282  7186  7186 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 13:45:06.283  7186  7186 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@df29a71
08-16 13:45:06.283  7186  7854 D HeadsetStateMachine: Exit Disconnected: -1
08-16 13:45:06.286  1036  1036 D BluetoothHeadset: Proxy object disconnected
08-16 13:45:06.286  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-16 13:45:06.287  1851  1851 D BluetoothHeadset: Proxy object disconnected
08-16 13:45:06.287  1851  1851 D BluetoothHeadset: Proxy object disconnected
08-16 13:45:06.287  1851  1851 D BluetoothHeadset: Proxy object disconnected
08-16 13:45:06.289  7186  7818 D BluetoothAdapterState: Stopping profile services that were post enabled
08-16 13:45:06.291  7186  7186 D A2dpService: Received stop request...Stopping profile...
,08-16 13:45:06.293  7186  7865 D A2dpStateMachine: Exit Disconnected: -1
08-16 13:45:06.295  7186  7186 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-16 13:45:06.296  7186  7186 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-16 13:45:06.296  7186  7186 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 13:45:06.296  7186  7186 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@df29a71
08-16 13:45:06.298  1036  1036 D BluetoothA2dp: Proxy object disconnected
08-16 13:45:06.298  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-16 13:45:06.299  7186  7186 D HidService: Received stop request...Stopping profile...
08-16 13:45:06.299  7186  7186 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@df29a71
08-16 13:45:06.301  7186  7186 D HealthService: Received stop request...Stopping profile...
08-16 13:45:06.301  7186  7186 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@df29a71
08-16 13:45:06.304  7186  7186 D PanService: Received stop request...Stopping profile...
,08-16 13:45:06.310  7186  7186 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@df29a71
08-16 13:45:06.312  7186  7186 D BtGatt.DebugUtils: handleDebugAction() action=null
08-16 13:45:06.313  7186  7186 D BtGatt.GattService: Received stop request...Stopping profile...
08-16 13:45:06.313  7186  7186 D BtGatt.GattService: stop()
08-16 13:45:06.313  7186  7186 D BtGatt.AdvertiseManager: advertise clients cleared
08-16 13:45:06.314  7186  7186 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@df29a71
08-16 13:45:06.315  7186  7186 D HeadsetStateMachine: Unbinding service...
08-16 13:45:06.316  7186  7186 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-16 13:45:06.316  7186  7186 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-16 13:45:06.316  7186  7186 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-16 13:45:06.316  7186  7186 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-16 13:45:06.316  7186  7186 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-16 13:45:06.316  7186  7186 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 13:45:06.316  7186  7186 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-16 13:45:06.319  7186  7186 D BluetoothMapService: Received stop request...Stopping profile...
08-16 13:45:06.319  7186  7186 D BluetoothMapService: stop()
,08-16 13:45:06.322  7186  7186 D BluetoothMapEmailAppObserver: deinitObservers()
08-16 13:45:06.322  7186  7186 D BluetoothMapEmailAppObserver: removeReceiver()
08-16 13:45:06.323  7186  7186 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@df29a71
08-16 13:45:06.324  7186  7186 I BluetoothA2dpServiceJni: cleanupNative
08-16 13:45:06.324  7186  7866 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-16 13:45:06.324  7186  7186 I GKI_LINUX: GKI_exit_task 2 done
08-16 13:45:06.324  7186  7186 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-16 13:45:06.325  7186  7186 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-16 13:45:06.325  7186  7186 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-16 13:45:06.325  7186  7186 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-16 13:45:06.325  7186  7186 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-16 13:45:06.325  7186  7186 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-16 13:45:06.326  7186  7186 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-16 13:45:06.326  7186  7186 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-16 13:45:06.328  7186  7186 V BluetoothMapService: Handler(): got msg=4
08-16 13:45:06.328  7186  7186 D BluetoothMapService: MAP Service closeService in
08-16 13:45:06.328  7186  7186 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-16 13:45:06.328  7186  7186 V BluetoothMapService: MAP Service closeService out
08-16 13:45:06.330  7186  7818 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-16 13:45:06.330  7186  7818 D BluetoothAdapterProperties: Setting state to 10
08-16 13:45:06.330  7186  7818 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
,08-16 13:45:06.333  7186  7186 D BluetoothMapService: cleanup()
08-16 13:45:06.333  7186  7186 D BluetoothMapService: MAP Service closeService in
08-16 13:45:06.333  7186  7186 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-16 13:45:06.334  7186  7186 V BluetoothMapService: MAP Service closeService out
08-16 13:45:06.334  1036  1107 D BluetoothManagerService: Message: 60
08-16 13:45:06.334  1036  1107 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-16 13:45:06.334  1036  1107 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-16 13:45:06.335  7186  7818 I BluetoothAdapterState: Entering OffState
08-16 13:45:06.336  1851  1866 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 13:45:06.336  1036  1107 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 13:45:06.336  7122  7947 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 13:45:06.337  7122  7947 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 13:45:06.338  1851  1867 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 13:45:06.338  1036  1107 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 13:45:06.338  1851  2444 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 13:45:06.339  7122  7947 D BluetoothPbap: onBluetoothStateChange: up=false
08-16 13:45:06.340  7122  7947 D BluetoothMap: onBluetoothStateChange: up=false
08-16 13:45:06.340  7122  7947 D BluetoothPan: onBluetoothStateChange on: false
08-16 13:45:06.342  7122  7947 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-16 13:45:06.345  1036  1107 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-16 13:45:06.345  1036  1107 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-16 13:45:06.347  1036  1107 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-16 13:45:06.347  1036  1107 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-16 13:45:06.347  1036  1107 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@cec5de5 mBinding = false
08-16 13:45:06.348  1036  1107 D BluetoothManagerService: Sending unbind request.
08-16 13:45:06.353  7186  7822 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-16 13:45:06.354  7186  7186 I GKI_LINUX: GKI_exit_task 1 done
08-16 13:45:06.354  7186  7186 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-16 13:45:06.354  7186  7186 I BluetoothServiceJni: cleanupNative: return from cleanup
08-16 13:45:06.354  7186  7186 I art     : --- WEIRD: removing null entry 248
08-16 13:45:06.355  7186  7186 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-16 13:45:06.355  7186  7186 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
,08-16 13:45:06.358  7186  7186 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-16 13:45:06.359  1036  1107 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-16 13:45:06.361  7186  7186 I art     : System.exit called, status: 0
08-16 13:45:06.361  7186  7186 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-16 13:45:06.381   312  1386 V AudioFlinger: 7186 died, releasing its sessions
08-16 13:45:06.381   312  1386 V AudioFlinger:  pid 1851 @ 0
08-16 13:45:06.381   312  1386 V AudioFlinger:  pid 3309 @ 1
08-16 13:45:06.381   312  1386 V AudioFlinger:  pid 3309 @ 2
,08-16 13:45:06.384  1941  1941 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
08-16 13:45:06.385  1941  2125 D LGBluetoothAPIService: Message: 101
08-16 13:45:06.385  1941  2125 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
08-16 13:45:06.385  1941  2125 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
08-16 13:45:06.385  1941  2125 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
08-16 13:45:06.387  7122  7122 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-16 13:45:06.389  1036  1051 I ActivityManager: Process com.android.bluetooth (pid 7186) has died
08-16 13:45:06.390  1036  1051 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms
08-16 13:45:06.390  1036  1051 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 14000ms
08-16 13:45:06.395  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-16 13:45:06.398  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 13:45:06.399  1941  2125 D LGBluetoothAPIService: Message: 2
08-16 13:45:06.399  1941  2125 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
08-16 13:45:06.400  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:45:06.401  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:45:06.408  7122  7122 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-16 13:45:06.408  7122  7122 D LGBluetoothEventManager: [BTUI] clear device connection state
,08-16 13:45:06.418  7122  7122 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-16 13:45:06.420  1603  1603 D BluetoothAdapter: 735540912: getState() :  mService = null. Returning STATE_OFF
,08-16 13:45:06.420  1603  1603 D BluetoothAdapter: 735540912: getState() :  mService = null. Returning STATE_OFF
08-16 13:45:06.475  1036  1052 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=8183 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-16 13:45:06.476  7122  7122 D DockEventReceiver: finishStartingService: stopping service
,08-16 13:45:06.532  8183  8183 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-16 13:45:06.533  8183  8183 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 13:45:06.533  8183  8183 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
,08-16 13:45:06.534  8183  8183 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-16 13:45:06.554  8183  8183 D BluetoothAdapterApp: Loading JNI Library
,08-16 13:45:06.591  8183  8183 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@1a1b7d39 Instance Count = 1
,08-16 13:45:06.597  8183  8183 D BluetoothAdapterApp: onCreate
08-16 13:45:06.622  8183  8183 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-16 13:45:06.622  8183  8183 D ProfileConfigQcom: Adding HeadsetService
08-16 13:45:06.622  8183  8183 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-16 13:45:06.623  8183  8183 D ProfileConfigQcom: Adding A2dpService
08-16 13:45:06.623  8183  8183 D ProfileConfigQcom: [BTUI] HidService is supported
08-16 13:45:06.623  8183  8183 D ProfileConfigQcom: Adding HidService
08-16 13:45:06.623  8183  8183 D ProfileConfigQcom: [BTUI] HealthService is supported
08-16 13:45:06.623  8183  8183 D ProfileConfigQcom: Adding HealthService
,08-16 13:45:06.624  8183  8183 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-16 13:45:06.625  8183  8183 D ProfileConfigQcom: [BTUI] PanService is supported
08-16 13:45:06.625  8183  8183 D ProfileConfigQcom: Adding PanService
08-16 13:45:06.625  8183  8183 D ProfileConfigQcom: [BTUI] GattService is supported
08-16 13:45:06.625  8183  8183 D ProfileConfigQcom: Adding GattService
08-16 13:45:06.625  8183  8183 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-16 13:45:06.626  8183  8183 D ProfileConfigQcom: Adding BluetoothMapService
08-16 13:45:06.626  8183  8183 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-16 13:45:06.627  8183  8183 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-16 13:45:06.628  8183  8183 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:45:06.628  8183  8183 V BluetoothPbapReceiver: ***********state = 10
08-16 13:45:06.630  8183  8183 V LGMDMManagerInternal: Create singleton instance
08-16 13:45:06.736  2175  2175 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 13:45:06.753  7122  7122 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,08-16 13:45:06.754  8183  8183 D LGBluetoothAPIServer: [BTUI] onCreate()
08-16 13:45:06.754  8183  8183 D LGBluetoothAPIServer: [BTUI] onBind()
08-16 13:45:06.762  1941  1941 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-16 13:45:06.762  1941  2125 D LGBluetoothAPIService: Message: 100
08-16 13:45:06.762  1941  2125 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-16 13:45:06.768  7122  7122 D BluetoothPermissionRequest: onReceive
,08-16 13:45:06.771  7122  7122 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-16 13:45:06.771  7122  7122 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-16 13:45:06.776  7122  7122 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-16 13:45:06.781  8183  8183 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,08-16 13:45:06.789  8183  8183 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:45:06.794  8183  8183 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 13:45:06.794  8183  8183 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 13:45:06.794  8183  8183 V BluetoothSapReceiver: SapReceiver onReceive 
,08-16 13:45:06.796  8183  8183 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
,08-16 13:45:06.796  8183  8183 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
,08-16 13:45:06.804  7881  7881 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-16 13:45:10.404  6936  6997 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:45:10.415  1036  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 13:45:10.415  1036  1052 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-16 13:45:10.435  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 13:45:10.435  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 13:45:10.435  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-16 13:45:10.436  1036  1107 D BluetoothManagerService: Message: 1
08-16 13:45:10.436  1036  1107 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-16 13:45:10.463  1036  1107 D BluetoothManagerService: Message: 20
08-16 13:45:10.463  1036  1107 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@39257774:true
,08-16 13:45:10.467  8183  8183 D BluetoothAdapterState: make
08-16 13:45:10.472  8183  8183 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-16 13:45:10.472  8183  8183 I bluedroid-qcom: init
08-16 13:45:10.473  8183  8215 I BluetoothAdapterState: Entering OffState
08-16 13:45:10.474  8183  8183 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-16 13:45:10.474  8183  8183 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-16 13:45:10.474  8183  8183 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-16 13:45:10.474  8183  8183 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-16 13:45:10.474  8183  8183 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-16 13:45:10.476  8183  8183 I bluedroid-qcom: get_profile_interface socket
08-16 13:45:10.476  8183  8183 I bluedroid-qcom: get_profile_interface map_client
,08-16 13:45:10.480  8183  8219 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-16 13:45:10.473  8218  8218 W bdaddr_loader: type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 13:45:10.485  8183  8219 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-16 13:45:10.473  8218  8218 W bdaddr_loader: type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 13:45:10.492  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-16 13:45:10.493  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
,08-16 13:45:10.500  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-16 13:45:10.500  1036  1107 D BluetoothManagerService: Message: 40
08-16 13:45:10.501  1036  1107 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-16 13:45:10.501  8183  8198 I bluedroid-qcom: config_hci_snoop_log
08-16 13:45:10.504  8218  8218 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-16 13:45:10.504  8218  8218 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-16 13:45:10.504  8218  8218 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-16 13:45:10.505  1036  1107 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-16 13:45:10.505  1036  1107 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-16 13:45:10.506  8218  8218 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
,08-16 13:45:10.513  8183  8219 D BluetoothAdapterProperties: Name is: G3
08-16 13:45:10.513  8218  8218 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-16 13:45:10.513  8218  8218 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-16 13:45:10.518  8183  8215 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-16 13:45:10.518  8183  8215 D BluetoothAdapterProperties: Setting state to 11
08-16 13:45:10.519  8183  8215 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,08-16 13:45:10.523  8183  8215 I LGBluetoothServiceJni: classInitNative: succeeds
08-16 13:45:10.523  1036  1107 D BluetoothManagerService: Message: 60
08-16 13:45:10.523  1036  1107 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-16 13:45:10.523  1036  1107 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-16 13:45:10.527  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:45:10.528  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 13:45:10.531  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:45:10.533  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:45:10.543  7122  7122 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-16 13:45:10.552  8183  8183 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-16 13:45:10.552  8183  8183 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:45:10.552  8183  8183 V BluetoothPbapReceiver: ***********state = 11
,08-16 13:45:10.559  8183  8215 D BluetoothBondStateMachine: make
,08-16 13:45:10.567  8183  8215 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3fc06056
08-16 13:45:10.567  8183  8215 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-16 13:45:10.568  8183  8215 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3fc06056
08-16 13:45:10.568  8183  8215 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
,08-16 13:45:10.573  8183  8220 I BluetoothBondStateMachine: StableState(): Entering Off State
08-16 13:45:10.575  8183  8215 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-16 13:45:10.578  2175  2175 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 13:45:10.582  8183  8215 E BluetoothAdapterService: File transfer profiles supported!!
,08-16 13:45:10.590  8183  8215 E BluetoothAdapterService: File transfer profiles supported!!
08-16 13:45:10.590  8183  8183 D HeadsetService: Received start request. Starting profile...
08-16 13:45:10.591  8183  8183 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-16 13:45:10.591  8183  8183 D LGBluetoothHfpAdapter: Version 1.6
08-16 13:45:10.594  8183  8183 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-16 13:45:10.596  8183  8183 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-16 13:45:10.596  8183  8183 D HeadsetStateMachine: make
08-16 13:45:10.596  8183  8215 E BluetoothAdapterService: File transfer profiles supported!!
08-16 13:45:10.602  7122  7122 D BluetoothPermissionRequest: onReceive
08-16 13:45:10.603  8183  8215 E BluetoothAdapterService: File transfer profiles supported!!
08-16 13:45:10.609  7122  7122 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-16 13:45:10.611  8183  8215 E BluetoothAdapterService: File transfer profiles supported!!
08-16 13:45:10.614  8183  8215 E BluetoothAdapterService: File transfer profiles supported!!
08-16 13:45:10.619  8183  8215 E BluetoothAdapterService: File transfer profiles supported!!
,08-16 13:45:10.631  8183  8215 V LGMDMManager: Create singleton instance
08-16 13:45:10.633  8183  8215 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-16 13:45:10.633  8183  8183 D LgDataFeature: LgDataFeature() Constructor: none
,08-16 13:45:10.633  8183  8183 D LgDataFeature: LgDataFeature() Constructor Done, null
08-16 13:45:10.638  8183  8183 D HeadsetStateMachine: max_hf_connections = 1
08-16 13:45:10.638  8183  8183 I bluedroid-qcom: get_profile_interface handsfree
08-16 13:45:10.641  8183  8183 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-16 13:45:10.641   312  2154 V AudioPolicyService: registerClient() client 0xb558a560, uid 1002
,08-16 13:45:10.642   312  1386 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-16 13:45:10.642   312  1386 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-16 13:45:10.642   312  1386 V AudioPolicyManagerEx: getOutput() returns output 2
08-16 13:45:10.642  8183  8183 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-16 13:45:10.642   312  1385 V AudioFlinger: registerClient() client 0xb14336b8, pid 8183
08-16 13:45:10.643   312  1379 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 13:45:10.643   312  1379 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 13:45:10.643  8183  8198 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 13:45:10.644  8183  8198 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-16 13:45:10.644  1036  1958 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 13:45:10.644  1036  1958 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 13:45:10.644   312  1380 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 13:45:10.644   312  1380 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 13:45:10.644  3309  3324 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 13:45:10.644  3309  3324 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 13:45:10.645  1036  1051 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 13:45:10.645  3309  3325 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 13:45:10.645  3309  3325 V AudioSystem: ioConfigChanged() opening already existing output! 4
,08-16 13:45:10.645  1603  1619 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 13:45:10.645  1603  1619 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 13:45:10.646  1603  1619 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 13:45:10.646  1603  1619 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 13:45:10.646  1851  1867 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 13:45:10.646  1851  1867 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 13:45:10.646  8183  8183 V ToneGenerator: Create Track: 0xb4928a80
08-16 13:45:10.646  8183  8183 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-16 13:45:10.646  1851  1867 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 13:45:10.646  8183  8183 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-16 13:45:10.646  1851  1867 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 13:45:10.646  1036  1051 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 13:45:10.646  8183  8198 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 13:45:10.646  8183  8198 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-16 13:45:10.646   312  1385 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-16 13:45:10.646   312  1385 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-16 13:45:10.646   312  1385 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-16 13:45:10.646   312  1385 V AudioPolicyManagerEx: getOutput() returns output 2
08-16 13:45:10.647   312   312 I AudioFlinger: isAudioPlaybackHookOn() false
08-16 13:45:10.647   312  2155 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-16 13:45:10.647   312  2155 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-16 13:45:10.647   312  2155 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-16 13:45:10.647   312  2155 V AudioPolicyManagerEx: getOutput() returns output 2
08-16 13:45:10.647  8183  8183 V AudioSystem: getLatency() output 2, latency 50
08-16 13:45:10.647  8183  8183 V AudioSystem: getFrameCount() output 2, frameCount 960
08-16 13:45:10.647  8183  8183 V AudioTrack: createTrack_l() output 2 afLatency 50
08-16 13:45:10.647   312  1385 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-16 13:45:10.647   312  1385 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-16 13:45:10.647   312  1385 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-16 13:45:10.647   312  1385 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-16 13:45:10.647   312  1385 V AudioFlinger: createTrack() lSessionId: 23
08-16 13:45:10.649  8183  8183 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-16 13:45:10.649   312  1385 V AudioFlinger: acquiring 23 from 8183, for 8183
08-16 13:45:10.649   312  1385 V AudioFlinger:  added new entry for 23
08-16 13:45:10.649  8183  8183 V ToneGenerator: ToneGenerator INIT OK, time: 407329
08-16 13:45:10.649  8183  8183 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3fc06056
08-16 13:45:10.650  8183  8237 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-16 13:45:10.650  8183  8237 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-16 13:45:10.650  8183  8237 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-16 13:45:10.650  8183  8237 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-16 13:45:10.651   312  1386 V Au,dioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 8183
08-16 13:45:10.653   312  1386 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-16 13:45:10.653   312  1386 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-16 13:45:10.653   312  1386 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-16 13:45:10.653   312  1386 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-16 13:45:10.653   312  1386 V voice   : voice_set_parameters: exit with code(0)
08-16 13:45:10.653   312  1386 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-16 13:45:10.653   312  1386 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-16 13:45:10.653  8183  8183 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3fc06056
08-16 13:45:10.654   312  1386 V msm8974_platform: platform_set_parameters: exit with code(0)
08-16 13:45:10.654   312  1386 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-16 13:45:10.654   312  1386 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-16 13:45:10.654   312  1386 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-16 13:45:10.654  8183  8237 V ToneGenerator: ToneGenerator destructor
08-16 13:45:10.654  8183  8237 V ToneGenerator: stopTone
08-16 13:45:10.654  8183  8237 V ToneGenerator: Delete Track: 0xb4928a80
08-16 13:45:10.656  8183  8237 V AudioTrack: ~AudioTrack, releasing session id from 8183 on behalf of 8183
08-16 13:45:10.656   312  2154 V AudioFlinger: releasing 23 from 8183 for 8183
08-16 13:45:10.656   312  2154 V AudioFlinger:  decremented refcount to 0
08-16 13:45:10.656   312  2154 V AudioFlinger: purging stale effects
08-16 13:45:10.656   312  2154 V AudioPolicyService: AudioCommandThread() adding release output 2
08-16 13:45:10.656   312  2154 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-16 13:45:10.656   312  2154 V AudioFlinger: PlaybackThread::Track destructor
08-16 13:45:10.656   312  1263 V AudioPolicyService: AudioCommandThread() waking up
08-16 13:45:10.656   312  2154 V AudioFlinger: removeClient_l() pid 8183, calling pid 312
08-16 13:45:10.656   312  1263 V AudioPolicyService: AudioCommandThread() processing release output 2
08-16 13:45:10.656   312  1263 V AudioPolicyManager: releaseOutput() 2
08-16 13:45:10.656   312  1263 V AudioPolicyService: AudioCommandThread() going to sleep
08-16 13:45:10.657  8183  8183 D A2dpService: Received start request. Starting profile...
,08-16 13:45:10.657  8183  8183 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-16 13:45:10.658  8183  8183 V Avrcp   : make
,08-16 13:45:10.659  8183  8183 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-16 13:45:10.659  8183  8183 I bluedroid-qcom: get_profile_interface avrcp
08-16 13:45:10.669  8183  8183 V AudioManager: registerRemoteController: size of Media player list: 0
08-16 13:45:10.671  8183  8183 E AudioManager: No RCC entry present to update
08-16 13:45:10.671  8183  8183 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-16 13:45:10.674  8183  8183 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-16 13:45:10.676  8183  8183 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-16 13:45:10.676  8183  8183 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-16 13:45:10.680  8183  8183 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-16 13:45:10.794  1036  1051 V SIM_STK : Menu title from STK is T-Mobile
08-16 13:45:10.794  1036  1051 V SIM_STK : Menu title from STK is T-Mobile
,08-16 13:45:10.940  1036  1958 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-16 13:45:10.961  8183  8183 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,08-16 13:45:10.967  8183  8183 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
,08-16 13:45:10.968  8183  8183 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-16 13:45:10.968  8183  8183 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-16 13:45:10.968  8183  8183 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-16 13:45:10.968  8183  8183 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-16 13:45:10.969  8183  8183 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-16 13:45:10.969  8183  8183 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
,08-16 13:45:10.969  8183  8183 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-16 13:45:10.969  8183  8183 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-16 13:45:10.969  8183  8183 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-16 13:45:10.969  8183  8183 I BluetoothA2dpServiceJni: classInitNative
08-16 13:45:10.970  8183  8183 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-16 13:45:10.970  8183  8183 D A2dpStateMachine: make
08-16 13:45:10.973  8183  8183 I bluedroid-qcom: get_profile_interface a2dp
08-16 13:45:10.973  8183  8250 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-16 13:45:10.979  8183  8183 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
,08-16 13:45:10.979  8183  8183 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter],
08-16 13:45:10.980  8183  8183 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3fc06056
,08-16 13:45:10.982  8183  8183 I BluetoothHidServiceJni: classInitNative: succeeds
,08-16 13:45:10.984  8183  8249 D A2dpStateMachine: Enter Disconnected: -2,
,08-16 13:45:10.989  8183  8183 D HidService: Received start request. Starting profile...
08-16 13:45:10.989  8183  8183 I bluedroid-qcom: get_profile_interface hidhost
08-16 13:45:10.989  8183  8183 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3fc06056
08-16 13:45:10.990  8183  8183 I BluetoothHealthServiceJni: classInitNative: succeeds
08-16 13:45:10.994  8183  8183 D HealthService: Received start request. Starting profile...
08-16 13:45:10.996  8183  8183 I bluedroid-qcom: get_profile_interface health
08-16 13:45:10.996  8183  8183 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-16 13:45:10.996  8183  8183 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3fc06056
08-16 13:45:10.998  8183  8183 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-16 13:45:11.002  8183  8183 D PanService: Received start request. Starting profile...
08-16 13:45:11.003  8183  8183 D BluetoothPanServiceJni: initializeNative(L110): pan
08-16 13:45:11.003  8183  8183 I bluedroid-qcom: get_profile_interface pan
08-16 13:45:11.011  8183  8183 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-16 13:45:11.011  8183  8183 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3fc06056
,08-16 13:45:11.012  8183  8183 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-16 13:45:11.019  8183  8183 D BtGatt.DebugUtils: handleDebugAction() action=null
08-16 13:45:11.020  8183  8183 D BtGatt.GattService: Received start request. Starting profile...
08-16 13:45:11.020  8183  8183 D BtGatt.GattService: start()
08-16 13:45:11.020  8183  8183 I bluedroid-qcom: get_profile_interface gatt
08-16 13:45:11.021  8183  8183 D BtGatt.AdvertiseManager: advertise manager created
08-16 13:45:11.027  8183  8183 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3fc06056
,08-16 13:45:11.030  8183  8183 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3fc06056
08-16 13:45:11.031  8183  8183 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-16 13:45:11.032  8183  8183 V BluetoothMapService: BluetoothMapBinder()
08-16 13:45:11.033  8183  8183 D BluetoothMapService: Received start request. Starting profile...
08-16 13:45:11.033  8183  8183 D BluetoothMapService: start()
08-16 13:45:11.037  8183  8183 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-16 13:45:11.037  8183  8183 D BluetoothMapEmailAppObserver: createReceiver()
08-16 13:45:11.039  8183  8183 D BluetoothMapEmailAppObserver: initObservers()
08-16 13:45:11.039  8183  8183 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
,08-16 13:45:11.052  8183  8183 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3fc06056
08-16 13:45:11.053  8183  8183 D HeadsetStateMachine: Proxy object connected
08-16 13:45:11.054  8183  8183 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-16 13:45:11.054  8183  8183 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-16 13:45:11.060  8183  8183 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-16 13:45:11.062  8183  8237 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-16 13:45:11.063  8183  8237 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-16 13:45:11.063  8183  8237 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-16 13:45:11.067  8183  8183 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 13:45:11.071  8183  8183 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-16 13:45:11.076  8183  8183 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 13:45:11.078  8183  8183 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:45:11.079  8183  8183 V PanService: [BTUI] SIM Extra State :ABSENT
08-16 13:45:11.083  8183  8183 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-16 13:45:11.086  8183  8183 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-16 13:45:11.087  8183  8183 V BluetoothMapService: Handler(): got msg=1
08-16 13:45:11.088  8183  8215 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-16 13:45:11.088  8183  8215 I bluedroid-qcom: enable
08-16 13:45:11.088  8183  8215 I bt_hci_bdroid: init
08-16 13:45:11.088  8183  8183 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 13:45:11.088  8183  8183 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 13:45:11.088  8183  8183 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 13:45:11.089  8183  8183 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:45:11.089  8183  8183 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-16 13:45:11.090  8183  8215 I bt_vendor: bt-vendor : init
08-16 13:45:11.090  8183  8215 I bt_vendor: bt-vendor : get_bt_soc_type
08-16 13:45:11.090  8183  8215 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-16 13:45:11.090  8183  8215 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-16 13:45:11.090  8183  8215 D bt_userial_mct: userial_init
08-16 13:45:11.091  8183  8215 D bt_hci_bdroid: set_power 1
08-16 13:45:11.091  8183  8215 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-16 13:45:11.091  8183  8215 I bt_vendor: Starting hciattach daemon
08-16 13:45:11.091  8183  8215 I bt_vendor: try to set true
08-16 13:45:11.091  8183  8257 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-16 13:45:11.093  8183  8257 I bt-btu  : btu_task pending for preload complete event
08-16 13:45:11.083  8260  8260 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-16 13:45:11.083  8260  8260 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 13:45:11.121  8261  8261 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-16 13:45:11.216  8267  8267 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-16 13:45:11.240  8268  8268 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-16 13:45:11.266  8270  8270 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-16 13:45:11.279  8271  8271 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
08-16 13:45:11.292  8272  8272 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-16 13:45:11.311  8273  8273 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-16 13:45:11.346  8275  8275 I libmdmdetect: ESOC framework not supported
08-16 13:45:11.347  8275  8275 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-16 13:45:11.357  8275  8275 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,08-16 13:45:11.357  8275  8275 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-16 13:45:11.357  8275  8275 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-16 13:45:11.357  8275  8275 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-16 13:45:11.357  8275  8275 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-16 13:45:11.357  8275  8275 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-16 13:45:11.357  8275  8275 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-16 13:45:11.396  8275  8276 E QC-QMI  : qmi_client [8275] 15: failed to locate client data
08-16 13:45:11.397   483   483 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-16 13:45:11.398   483   483 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,08-16 13:45:11.447  8277  8277 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-16 13:45:11.472  8278  8278 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-16 13:45:11.495  8183  8215 I bt_vendor: bluetooth satus is on
08-16 13:45:11.495  8183  8215 D bt_hci_bdroid: preload
08-16 13:45:11.495  8183  8259 D bt_userial_mct: userial_open(port:0)
08-16 13:45:11.495  8183  8259 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-16 13:45:11.499  8183  8259 I bt_vendor: Done intiailizing UART
08-16 13:45:11.500  8183  8259 I bt_vendor: Done intiailizing UART
08-16 13:45:11.500  8183  8259 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-16 13:45:11.501  8183  8259 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-16 13:45:11.501  8183  8257 I bt-btu  : btu_task received preload complete event
08-16 13:45:11.501  8183  8257 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-16 13:45:11.501  8183  8257 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-16 13:45:11.503  8183  8257 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-16 13:45:11.501  8183  8280 D bt_userial_mct: Entering userial_read_thread()
08-16 13:45:11.508  8183  8257 I         : BTE_InitTraceLevels -- TRC_HCI
08-16 13:45:11.508  8183  8257 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-16 13:45:11.508  8183  8257 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-16 13:45:11.508  8183  8257 I         : BTE_InitTraceLevels -- TRC_AVDT
08-16 13:45:11.508  8183  8257 I         : BTE_InitTraceLevels -- TRC_AVRC
08-16 13:45:11.508  8183  8257 I         : BTE_InitTraceLevels -- TRC_A2D
08-16 13:45:11.508  8183  8257 I         : BTE_InitTraceLevels -- TRC_BNEP
08-16 13:45:11.508  8183  8257 I         : BTE_InitTraceLevels -- TRC_BTM
08-16 13:45:11.508  8183  8257 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-16 13:45:11.508  8183  8257 I         : BTE_InitTraceLevels -- TRC_GAP
08-16 13:45:11.508  8183  8257 I         : BTE_InitTraceLevels -- TRC_PAN
08-16 13:45:11.508  8183  8257 I         : BTE_InitTraceLevels -- TRC_SDP
08-16 13:45:11.508  8183  8257 I         : BTE_InitTraceLevels -- TRC_GATT
08-16 13:45:11.508  8183  8257 I         : BTE_InitTraceLevels -- TRC_SMP
08-16 13:45:11.508  8183  8257 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-16 13:45:11.508  8183  8257 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-16 13:45:11.614  8183  8257 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
,08-16 13:45:11.614  8183  8257 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01db061 
,08-16 13:45:11.615  8183  8257 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01db061 
,08-16 13:45:11.662  8183  8219 E bt-btif : Calling BTA_HhEnable
08-16 13:45:11.662  8183  8219 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-16 13:45:11.663  8183  8219 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-16 13:45:11.670  8183  8219 D BluetoothAdapterProperties: Name is: G3
08-16 13:45:11.671  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-16 13:45:11.673  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
08-16 13:45:11.674  8183  8219 D BluetoothAdapterProperties: Scan Mode:20
08-16 13:45:11.674  8183  8219 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 13:45:11.674  8183  8219 D bt_hci_bdroid: postload
08-16 13:45:11.676  8183  8219 D bte_conf: Device ID record 1 : primary
08-16 13:45:11.676  8183  8219 D bte_conf:   vendorId            = 00c4
08-16 13:45:11.677  8183  8219 D bte_conf:   vendorIdSource      = 0001
08-16 13:45:11.677  8183  8219 D bte_conf:   product             = 13a1
08-16 13:45:11.677  8183  8219 D bte_conf:   version             = 1000
08-16 13:45:11.677  8183  8219 D bte_conf:   clientExecutableURL = 
08-16 13:45:11.677  8183  8219 D bte_conf:   serviceDescription  = 
08-16 13:45:11.677  8183  8219 D bte_conf:   documentationURL    = 
08-16 13:45:11.680  8183  8259 D bt_hci_bdroid: Used up Tx Cmd credits
,08-16 13:45:11.683  8183  8219 D bte_conf: bte_load_did_conf no section named DID2.
08-16 13:45:11.686  8183  8215 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-16 13:45:11.687  8183  8215 D BluetoothAdapterProperties: ScanMode =  20
08-16 13:45:11.687  8183  8215 D BluetoothAdapterProperties: State =  11
08-16 13:45:11.687  8183  8215 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-16 13:45:11.687  8183  8215 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-16 13:45:11.687  8183  8215 D BluetoothAdapterProperties: Setting state to 12
08-16 13:45:11.687  8183  8215 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-16 13:45:11.688  8183  8219 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-16 13:45:11.683  8285  8285 W sh      : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 13:45:11.683  8285  8285 W sh      : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-16 13:45:11.697  8183  8215 I BluetoothAdapterState: Entering On State
08-16 13:45:11.700  1036  1107 D BluetoothManagerService: Message: 60
08-16 13:45:11.700  1036  1107 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-16 13:45:11.700  1036  1107 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
08-16 13:45:11.714  8183  8215 D LGBluetoothServiceAdapter: [BTUI] OnState
08-16 13:45:11.714  8183  8215 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-16 13:45:11.714  8183  8215 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,08-16 13:45:11.718  1851  1866 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 13:45:11.720  8183  8215 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-16 13:45:11.732  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:45:11.732  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:45:11.732  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 13:45:11.732  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 13:45:11.732  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 13:45:11.732  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 13:45:11.732  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 13:45:11.732  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 13:45:11.735  8183  8219 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 13:45:11.735  8183  8219 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-16 13:45:11.740  6936  6936 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 13:45:11.747  8183  8215 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
,08-16 13:45:11.759  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:45:11.759  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:45:11.759  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 13:45:11.759  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 13:45:11.759  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 13:45:11.759  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 13:45:11.759  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 13:45:11.759  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 13:45:11.763  6936  6936 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 13:45:11.770  1851  1851 D BluetoothHeadset: Proxy object connected
08-16 13:45:11.771  8183  8259 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 13:45:11.772  1036  1107 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-16 13:45:11.779  8183  8280 E bt_mct  : hci lib postload completed
08-16 13:45:11.787  1036  1036 D BluetoothA2dp: Proxy object connected
,08-16 13:45:11.797  8183  8257 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-16 13:45:11.797  8183  8257 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-16 13:45:11.797  8183  8257 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-16 13:45:11.798  8183  8257 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-16 13:45:11.798  8183  8257 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-16 13:45:11.798  8183  8257 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-16 13:45:11.798  8183  8219 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-16 13:45:11.813  8290  8290 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,08-16 13:45:11.819  7122  7139 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 13:45:11.822  7122  7139 D BluetoothA2dp: onBluetoothStateChange: up=true
08-16 13:45:11.824  1851  2444 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 13:45:11.826  1851  1851 D BluetoothHeadset: Proxy object connected
08-16 13:45:11.826  1036  1107 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 13:45:11.827  1036  1036 D BluetoothHeadset: Proxy object connected
08-16 13:45:11.829  8183  8257 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 13:45:11.829  8183  8257 W bt-smp  : Plain text(LSB ~ MSB) = 5d 9f 68 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 13:45:11.829  8183  8257 W bt-smp  : Encrypted text(LSB ~ MSB) = 20 22 22 73 8e 6b 43 ac 66 55 c7 bd 41 d1 ff f9 
08-16 13:45:11.829  8183  8257 W bt-btm  : Stopping oneshot timer
,08-16 13:45:11.832  1851  1866 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 13:45:11.834  1851  1851 D BluetoothHeadset: Proxy object connected
08-16 13:45:11.835  7122  7122 D BluetoothHeadset: Proxy object connected
08-16 13:45:11.835  7122  7122 D HeadsetProfile: Bluetooth service connected
08-16 13:45:11.836  7122  7947 D BluetoothPbap: onBluetoothStateChange: up=true
08-16 13:45:11.838  7122  7139 D BluetoothMap: onBluetoothStateChange: up=true
08-16 13:45:11.852  7122  7138 D BluetoothPan: onBluetoothStateChange on: true
08-16 13:45:11.852  7122  7138 D BluetoothPan: onBluetoothStateChange call bindService
,08-16 13:45:11.858  7122  7122 D BluetoothA2dp: Proxy object connected
08-16 13:45:11.858  7122  7122 D A2dpProfile: Bluetooth service connected
08-16 13:45:11.859  7122  7139 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-16 13:45:11.863  1036  1107 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-16 13:45:11.863  1036  1107 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-16 13:45:11.865  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-16 13:45:11.868  8183  8257 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
,08-16 13:45:11.868  8183  8257 W bt-smp  : Plain text(LSB ~ MSB) = 1d 28 41 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 13:45:11.868  8183  8257 W bt-smp  : Encrypted text(LSB ~ MSB) = e0 19 46 d7 dc 2a 31 0b af e2 78 bf 17 12 2c 49 
08-16 13:45:11.868  8183  8257 W bt-btm  : Stopping oneshot timer
08-16 13:45:11.870  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:45:11.871  1941  2125 D LGBluetoothAPIService: Message: 1
08-16 13:45:11.871  1941  2125 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-16 13:45:11.871  1941  2125 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
08-16 13:45:11.871  1941  2125 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-16 13:45:11.872  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-16 13:45:11.872  1036  1107 D BluetoothManagerService: Message: 40
08-16 13:45:11.872  1036  1107 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-16 13:45:11.873  8183  8183 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:45:11.873  8183  8183 D BluetoothMapService: STATE_ON
08-16 13:45:11.873  8183  8183 V BluetoothMapService: Handler(): got msg=1
08-16 13:45:11.874  8183  8183 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-16 13:45:11.875  8183  8306 D BluetoothMapMasInstance: MAS initSocket()
08-16 13:45:11.876  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:45:11.878  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:45:11.878  7122  7122 D BluetoothMap: Proxy object connected
08-16 13:45:11.878  7122  7122 D MapProfile: Bluetooth service connected
08-16 13:45:11.878  7122  7122 D BluetoothMap: getConnectedDevices()
08-16 13:45:11.881  8183  8257 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 13:45:11.881  8183  8257 W bt-smp  : Plain text(LSB ~ MSB) = 93 a4 56 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 13:45:11.881  8183  8257 W bt-smp  : Encrypted text(LSB ~ MSB) = 4e 0b 10 9a 2b 95 00 90 83 b9 10 7c 61 0b 5d 22 
08-16 13:45:11.881  8183  8257 W bt-btm  : Stopping oneshot timer
,08-16 13:45:11.886  8183  8306 D BluetoothMapMasInstance:   masId = 00
08-16 13:45:11.886  8183  8306 D BluetoothMapMasInstance:   msgTypes = 0e
08-16 13:45:11.886  8183  8306 D BluetoothMapMasInstance:   masName = SMS/MMS
08-16 13:45:11.886  8183  8306 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-16 13:45:11.889  8183  8304 V BluetoothMapService: getConnectedDevices()
08-16 13:45:11.890  1036  1994 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 13:45:11.891  7122  7122 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 13:45:11.891  7122  7122 D PanProfile: Bluetooth service connected
08-16 13:45:11.892  8183  8306 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 13:45:11.892  8183  8257 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 13:45:11.892  8183  8257 W bt-smp  : Plain text(LSB ~ MSB) = 8b f4 4a 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 13:45:11.892  8183  8257 W bt-smp  : Encrypted text(LSB ~ MSB) = 4b 6a e9 5a 7c d6 0c fc fe 1a 4e f0 53 aa a8 69 
08-16 13:45:11.892  8183  8257 W bt-btm  : Stopping oneshot timer
08-16 13:45:11.893  8183  8183 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3fc06056
08-16 13:45:11.893  8183  8183 V BluetoothPbapService: Pbap Service onCreate
,08-16 13:45:11.893  8183  8183 V BluetoothPbapService: Starting PBAP service
,08-16 13:45:11.895  8183  8183 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-16 13:45:11.895  8183  8183 V BluetoothPbapService: Pbap Service onBind
08-16 13:45:11.896  8183  8219 D BluetoothAdapterProperties: Scan Mode:21
08-16 13:45:11.899  8183  8306 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-16 13:45:11.899  8183  8219 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-16 13:45:11.899  8183  8183 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:45:11.899  8183  8183 V BluetoothPbapService: state: 12
08-16 13:45:11.899  8183  8183 V BluetoothPbapService: Handler(): got msg=1
08-16 13:45:11.899  8183  8306 V BluetoothMapMasInstance: Succeed to create listening socket 
,08-16 13:45:11.899  8183  8306 D BluetoothMapMasInstance: Accepting socket connection...
08-16 13:45:11.900  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:45:11.900  8183  8183 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-16 13:45:11.900  7122  7122 D BluetoothInputDevice: Proxy object connected
08-16 13:45:11.900  7122  7122 D HidProfile: Bluetooth service connected
08-16 13:45:11.901  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:45:11.901  8183  8309 V BluetoothPbapService: Pbap Service initSocket
08-16 13:45:11.904  1036  1958 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 13:45:11.904  8183  8257 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 13:45:11.904  8183  8257 W bt-smp  : Plain text(LSB ~ MSB) = 2d f9 63 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 13:45:11.904  8183  8257 W bt-smp  : Encrypted text(LSB ~ MSB) = c1 5d 63 c6 14 e2 7e 2c 29 73 15 73 a6 8d 9f 1c 
08-16 13:45:11.904  8183  8257 W bt-btm  : Stopping oneshot timer
08-16 13:45:11.904  8183  8309 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 13:45:11.905  8183  8309 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-16 13:45:11.905  8183  8309 V BluetoothPbapService: Succeed to create listening socket 
08-16 13:45:11.905  8183  8309 V BluetoothPbapService: Accepting socket connection...
,08-16 13:45:11.906  7122  7122 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-16 13:45:11.907  7122  7122 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-16 13:45:11.910  7122  7122 D BluetoothPbap: Proxy object connected
08-16 13:45:11.910  7122  7122 D PbapServerProfile: Bluetooth service connected
08-16 13:45:11.910  8183  8183 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-16 13:45:11.910  8183  8183 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:45:11.910  8183  8183 V BluetoothPbapReceiver: ***********state = 12
08-16 13:45:11.915  2175  2175 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 13:45:11.916  7122  7122 D DockEventReceiver: finishStartingService: stopping service
08-16 13:45:11.917  2175  2175 D c       : Getting all permits...
08-16 13:45:11.917  2175  2175 D a       : Opening database...
,08-16 13:45:11.921  2175  2175 D a       : Opening database auth.proximity.permit_store...
08-16 13:45:11.922  2175  2175 D a       : Closing database...
08-16 13:45:11.931  7122  7122 D BluetoothPermissionRequest: onReceive
,08-16 13:45:11.932  7122  7122 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,08-16 13:45:11.934  7122  7122 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-16 13:45:11.936  8183  8183 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-16 13:45:11.937  8183  8183 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-16 13:45:11.943  8183  8183 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-16 13:45:11.961  8183  8183 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-16 13:45:11.961  8183  8183 V BtOppService: onCreate
08-16 13:45:11.966  8183  8183 V BluetoothOppNotification: send message
08-16 13:45:11.969  8183  8183 V BtOppService: Starting RfcommListener
08-16 13:45:11.973  8183  8183 D BluetoothOppPreference: Dumping Names:  
08-16 13:45:11.973  8183  8183 D BluetoothOppPreference: {}
08-16 13:45:11.973  8183  8183 D BluetoothOppPreference: Dumping Channels:  
08-16 13:45:11.973  8183  8183 D BluetoothOppPreference: {}
08-16 13:45:11.974  8183  8183 V BtOppService: onStartCommand
,08-16 13:45:11.977  8183  8318 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
,08-16 13:45:11.978  8183  8183 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:45:11.978  8183  8183 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-16 13:45:11.982  8183  8183 V BluetoothOppNotification: new notify threadi!
08-16 13:45:11.983  8183  8183 V BluetoothOppNotification: send delay message
08-16 13:45:11.984  8183  8183 V BtOppService: start RfcommListener
08-16 13:45:11.990  8183  8183 V BtOppService: RfcommListener started
08-16 13:45:11.991  8183  8315 V BtOppService: Deleted complete outbound shares, number =  0
08-16 13:45:11.993  8183  8315 V BtOppService: Deleted complete inbound failed shares, number = 0
,08-16 13:45:11.993  8183  8315 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-16 13:45:11.995  8183  8319 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-16 13:45:11.995  8183  8318 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-16 13:45:11.995  8183  8315 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@17b900f2 on behalf of 
08-16 13:45:11.996  8183  8319 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@253b5343 on behalf of 
08-16 13:45:11.998  8183  8320 V BtOppRfcommListener: Starting RFCOMM listener....
08-16 13:45:11.999  1036  1904 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 13:45:12.002  8183  8319 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-16 13:45:12.003  8183  8320 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 13:45:12.006  8183  8320 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
08-16 13:45:12.007  8183  8320 V BtOppRfcommListener: Started RFCOMM listener....
08-16 13:45:12.007  8183  8320 I BtOppRfcommListener: Accept thread started.
08-16 13:45:12.007  8183  8320 V BtOppRfcommListener: Accepting connection...
08-16 13:45:12.008  8183  8319 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-16 13:45:12.009  8183  8183 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3fc06056
08-16 13:45:12.009  8183  8183 V BluetoothFtpService: Ftp Service onCreate
08-16 13:45:12.009  8183  8183 I BluetoothFtpService: Ftp Service onCreate
08-16 13:45:12.009  8183  8318 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3fad8af9 on behalf of 
08-16 13:45:12.011  8183  8319 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@32d23a3e on behalf of 
08-16 13:45:12.011  8183  8183 V BluetoothFtpService: Ftp Service onStartCommand
08-16 13:45:12.011  8183  8183 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:45:12.012  8183  8183 V BluetoothFtpService: Starting Listening on sockets
08-16 13:45:12.012  8183  8183 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 13:45:12.012  8183  8183 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 13:45:12.012  8183  8183 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 13:45:12.012  8183  8318 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-16 13:45:12.012  8183  8183 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:45:12.012  8183  8183 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-16 13:45:12.014  8183  8183 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-16 13:45:12.014  8183  8319 V BluetoothOppNotification: outbound: succ-0  fail-0
08-16 13:45:12.017  8183  8183 V BtOppService: ContentObserver received notification
08-16 13:45:12.017  8183  8319 V BluetoothOppNotification: outbound notification was removed.
08-16 13:45:12.017  8183  8183 V BtOppService: ContentObserver received notification
08-16 13:45:12.017  8183  8183 V BluetoothFtpService: Handler(): got msg=1
08-16 13:45:12.017  8183  8319 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-16 13:45:12.019  8183  8183 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-16 13:45:12.020  8183  8183 V BluetoothFtpService: Ftp Service initSocket
,08-16 13:45:12.025  8183  8319 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3b35e09f on behalf of 
08-16 13:45:12.026  8183  8321 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-16 13:45:12.026  1036  1575 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 13:45:12.026  8183  8321 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-16 13:45:12.026  8183  8319 V BluetoothOppNotification: inbound: succ-0  fail-0
08-16 13:45:12.028  8183  8183 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 13:45:12.028  8183  8321 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3a5b45ec on behalf of 
08-16 13:45:12.028  8183  8319 V BluetoothOppNotification: inbound notification was removed.
08-16 13:45:12.029  8183  8319 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-16 13:45:12.029  8183  8321 V BluetoothOppNotification: update too frequent, put in queue
08-16 13:45:12.029  8183  8183 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=81 mFd=78
08-16 13:45:12.029  8183  8183 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-16 13:45:12.030  8183  8321 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
,08-16 13:45:12.034  8183  8319 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@28b2ddb5 on behalf of 
08-16 13:45:12.040  8183  8322 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-16 13:45:12.058  8183  8183 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3fc06056
,08-16 13:45:12.059  8183  8183 V BluetoothSapService: Sap Service onCreate
08-16 13:45:12.062  8183  8183 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:45:12.062  8183  8183 V BluetoothSapService: state: 12
08-16 13:45:12.062  8183  8183 V BluetoothSapService: Starting SAP server process
08-16 13:45:12.064  8183  8183 V BluetoothSapService: SAP Service startRfcommListenerThread
08-16 13:45:12.066  8183  8323 V BluetoothSapService: Sap Service initRfcommSocket
08-16 13:45:12.066  1036  1995 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 13:45:12.053  8324  8324 W sapd    : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 13:45:12.068  8183  8323 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 13:45:12.053  8324  8324 W sapd    : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 13:45:12.069  8183  8323 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=81
08-16 13:45:12.070  8183  8323 V BluetoothSapService: Succeed to create listening socket 
08-16 13:45:12.070  8183  8323 V BluetoothSapService: Accepting socket connection...
,08-16 13:45:12.079  8324  8324 V BT_SAP  : Event pipe created
,08-16 13:45:12.079  8324  8324 V BT_SAP  : create_server_socket qcom.sap.server
,08-16 13:45:12.079  8324  8324 V BT_SAP  : created socket fd 6
08-16 13:45:12.984  8183  8183 V BluetoothOppNotification: new notify threadi!
08-16 13:45:12.985  8183  8183 V BluetoothOppNotification: send delay message
,08-16 13:45:13.001  8183  8334 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-16 13:45:13.005  8183  8334 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3e80a031 on behalf of 
08-16 13:45:13.006  8183  8334 V BluetoothOppNotification: mUpdateCompleteNotification = true
,08-16 13:45:13.009  8183  8334 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-16 13:45:13.011  8183  8334 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@24795316 on behalf of 
08-16 13:45:13.012  8183  8334 V BluetoothOppNotification: outbound: succ-0  fail-0
08-16 13:45:13.014  8183  8334 V BluetoothOppNotification: outbound notification was removed.
08-16 13:45:13.014  8183  8334 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-16 13:45:13.015  8183  8334 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@17fd4497 on behalf of 
08-16 13:45:13.015  8183  8334 V BluetoothOppNotification: inbound: succ-0  fail-0
08-16 13:45:13.017  8183  8334 V BluetoothOppNotification: inbound notification was removed.
08-16 13:45:13.017  8183  8334 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-16 13:45:13.018  8183  8334 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@5866684 on behalf of 
,08-16 13:45:15.467  6936  6997 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:45:15.467  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:45:15.467  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 13:45:15.467  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 13:45:15.467  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 13:45:15.467  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 13:45:15.467  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 13:45:15.467  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 13:45:15.478  6936  6997 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 13:45:15.480  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:45:15.480  6936  6997 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1c957a03 removed from the list
08-16 13:45:15.480  6936  6997 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:45:15.480  6936  6997 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:45:15.480  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:45:15.482  6936  6997 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 13:45:15.482  6936  6997 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@18240d80 added. We now have 4 listener(s)
08-16 13:45:15.482  6936  6997 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 13:45:15.487  1036  1755 D WifiServiceImplEx: setWifiEnabled: false pid=6936, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-16 13:45:15.487  1036  1755 D WifiService: setWifiEnabled: false pid=6936, uid=10118
08-16 13:45:15.487  1036  1755 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 13:45:20.501  6936  6997 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:45:20.512  1036  1051 D WifiServiceImplEx: setWifiEnabled: true pid=6936, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-16 13:45:20.512  1036  1051 D WifiService: setWifiEnabled: true pid=6936, uid=10118
08-16 13:45:20.512  1036  1051 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 13:45:20.530  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 13:45:20.530  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 13:45:20.530  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-16 13:45:20.532  1036  1538 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-16 13:45:20.532  1036  1538 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-16 13:45:20.534  1036  1538 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-16 13:45:20.534  1036  1538 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-16 13:45:20.534  1036  1538 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-16 13:45:20.535  1036  1538 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-16 13:45:20.535  1036  1538 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-16 13:45:20.535  1036  1538 E WifiHW  : unknown target_country: EU , set to default
08-16 13:45:20.535  1036  1538 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-16 13:45:20.535  1036  1538 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-16 13:45:20.535  1036  1538 I WifiUtil: gEnableBmps=1
08-16 13:45:21.117   308   895 D SoftapController: Softap fwReload - Ok
,08-16 13:45:21.129  1036  1538 E NetdConnector: NDC Command {84 softap fwreload wlan0 STA} took too long (586ms)
08-16 13:45:21.131   308   895 D CommandListener: Setting iface cfg
08-16 13:45:21.132   308   895 D CommandListener: Trying to bring down wlan0
,08-16 13:45:21.135   308   895 D CommandListener: Clearing all IP addresses on wlan0
08-16 13:45:21.151  1036  1107 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-16 13:45:21.171  1036  1538 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,08-16 13:45:21.163  8345  8345 W wpa_supplicant: type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 13:45:21.173  8345  8345 W wpa_supplicant: type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-16 13:45:21.233  1036  1538 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 13:45:21.233  1036  1538 E WifiStateMachine: useWiFiOffloading() : false
08-16 13:45:21.233  1036  1538 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-16 13:45:21.244  8345  8345 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-16 13:45:21.252  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-16 13:45:21.266  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 13:45:21.269  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-16 13:45:21.269  1036  1538 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-16 13:45:21.269  1036  1538 D WifiMonitor: connecting to supplicant
,08-16 13:45:21.273  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:45:21.276  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:45:21.283  7122  7122 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-16 13:45:21.283  7122  7122 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-16 13:45:21.283  7122  7122 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-16 13:45:21.283  7122  7122 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,08-16 13:45:21.283  7122  7122 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-16 13:45:21.284  7122  7122 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-16 13:45:21.284  7122  7122 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-16 13:45:21.284  7122  7122 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-16 13:45:21.284  7122  7122 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-16 13:45:21.284  7122  7122 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-16 13:45:21.284  7122  7122 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-16 13:45:21.284  7122  7122 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-16 13:45:21.308  8345  8345 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-16 13:45:21.308  8345  8345 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-16 13:45:21.313  1036  1107 D Tethering: InitialState.processMessage what=4
08-16 13:45:21.327  1036  2033 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8363 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-16 13:45:21.329  1036  1107 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-16 13:45:21.388  8345  8345 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-16 13:45:21.426  1036  1904 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8385 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-16 13:45:21.431  8363  8383 W FormManager: Network not available. Please check & try again.
08-16 13:45:21.442  8363  8384 V FormManager: Network unavailable.
,08-16 13:45:21.444  8363  8384 V FormManager: Network unavailable.
08-16 13:45:21.452  8345  8345 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
08-16 13:45:21.457  8345  8345 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
,08-16 13:45:21.457  1036  1538 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-16 13:45:21.458  1036  1538 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-16 13:45:21.458  1036  8403 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-16 13:45:21.458  1036  8403 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-16 13:45:21.458  1036  8403 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-16 13:45:21.458  1036  8403 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-16 13:45:21.458  1036  1538 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-16 13:45:21.459  1036  1755 I ActivityManager: Killing 7427:com.lge.drmservice/u0a62 (adj 15): empty #17
08-16 13:45:21.460  1036  1538 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-16 13:45:21.460  1036  1538 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-16 13:45:21.461  1036  1538 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 13:45:21.461  1036  1538 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-16 13:45:21.461  1036  1538 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 13:45:21.462  1036  1538 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-16 13:45:21.462  1036  1538 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-16 13:45:21.462  1036  1538 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-16 13:45:21.462  1036  1538 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-16 13:45:21.462  1036  1538 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-16 13:45:21.492  8385  8385 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-16 13:45:21.510  1036  1538 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 13:45:21.510  1036  1538 E WifiStateMachine: useWiFiOffloading() : false
08-16 13:45:21.510  1036  1538 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-16 13:45:21.511  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:45:21.511  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:45:21.511  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:45:21.511  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:45:21.511  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 13:45:21.511  1036  1538 D WifiNative-wlan0: doBoolean: SET update_config 1
08-16 13:45:21.511  1036  1575 W libprocessgroup: failed to open /acct/uid_10062/pid_7427/cgroup.procs: No such file or directory
,08-16 13:45:21.512  1036  1538 D WifiNative-wlan0: SET update_config 1: returned true
08-16 13:45:21.512  1036  1538 D WifiConfigStore: Loading config and enabling all networks 
08-16 13:45:21.512  1036  1538 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-16 13:45:21.512  1036  1538 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-16 13:45:21.515  1941  1941 D WfdService: Waiting for WifiP2p enabling
08-16 13:45:21.516  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 13:45:21.517  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-16 13:45:21.518  1036  1542 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-16 13:45:21.520  7122  7122 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-16 13:45:21.522  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:45:21.522  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:45:21.522  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 13:45:21.522  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:45:21.522  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 13:45:21.522  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 13:45:21.522  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 13:45:21.522  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 13:45:21.529  1036  1538 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
,08-16 13:45:21.531  6936  6936 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 13:45:21.536  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:45:21.536  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:45:21.536  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 13:45:21.536  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:45:21.536  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 13:45:21.536  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 13:45:21.536  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 13:45:21.536  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 13:45:21.541  6936  6936 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 13:45:21.548  7122  7122 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 13:45:21.549  1036  1995 I ActivityManager: Killing 7453:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
08-16 13:45:21.554  1036  1538 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-16 13:45:21.554  1036  1538 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-16 13:45:21.581  1036  1940 W libprocessgroup: failed to open /acct/uid_10085/pid_7453/cgroup.procs: No such file or directory
08-16 13:45:21.581  1036  1538 D WifiStateMachine: enableVerboseLogging : level 2
08-16 13:45:21.581  1036  1538 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
,08-16 13:45:21.582  1036  1538 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-16 13:45:21.582  1036  1538 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-16 13:45:21.584  1036  1538 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-16 13:45:21.584  1036  1538 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-16 13:45:21.585  1036  1538 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-16 13:45:21.585  1036  1538 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-16 13:45:21.585  1036  1538 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-16 13:45:21.586  1036  1538 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-16 13:45:21.586  1036  1538 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-16 13:45:21.587  1036  1538 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-16 13:45:21.587  1036  1538 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-16 13:45:21.588  1036  1538 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-16 13:45:21.588  1036  1538 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-16 13:45:21.590  1036  1538 D WifiStateMachine: Setting OUI to DA-A1-19
08-16 13:45:21.590  1036  1538 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-16 13:45:21.591  1036  1538 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-16 13:45:21.591  1036  1538 D WifiNative-HAL: Setting external_sim to 1
08-16 13:45:21.591  1036  1538 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-16 13:45:21.592  1941  1941 D WfdsService: Supplicant Connection state is changed : true
08-16 13:45:21.592  1036  1538 D WifiNative-wlan0: SET external_sim 1: returned true
08-16 13:45:21.592  1941  2315 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-16 13:45:21.592  1036  1538 I WifiNative-HAL: startHal
08-16 13:45:21.592  1941  2315 D WfdsService: Set the WFDS Monitor: true
08-16 13:45:21.592  1941  2315 D WfdsMonitor: WfdsMonitorThread create
08-16 13:45:21.592  1036  1538 D wifi    : setting scan oui 0xaf6dae60
08-16 13:45:21.592  1941  2315 D WfdsMonitor: WFDS Monitor is created and started
08-16 13:45:21.592  1941  2315 D WfdsService: WiFi: Supplicant connection re-established
08-16 13:45:21.593  7976  7976 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:45:21.593  1036  1538 D WifiStateMachine: Setting OUI to DA-A1-19
08-16 13:45:21.593  1036  1538 I WifiNative-HAL: startHal
,08-16 13:45:21.594  1036  1538 D wifi    : setting scan oui 0xaf6dae60
08-16 13:45:21.595  1941  8406 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-16 13:45:21.595  1941  8406 E CtrlSupplicant: Succeed to open control connection
08-16 13:45:21.595  1941  8406 E CtrlSupplicant: Succeed to open monitor connection
08-16 13:45:21.595  1941  8406 D WfdsMonitor: Supplicant connection established
08-16 13:45:21.596  7122  7122 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-16 13:45:21.596  7122  7122 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-16 13:45:21.596  1941  2315 D WfdsService: Connected to the supplicant for wfds
08-16 13:45:21.596  7122  7122 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-16 13:45:21.596  7122  7122 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-16 13:45:21.596  1036  1538 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-16 13:45:21.597  1036  1538 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-16 13:45:21.597  1036  1538 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-16 13:45:21.597  8345  8345 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-16 13:45:21.597  7122  7122 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-16 13:45:21.598  1036  1538 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-16 13:45:21.598  1036  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-16 13:45:21.598  8345  8345 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-16 13:45:21.598  1036  1538 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-16 13:45:21.599  1036  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-16 13:45:21.599  8345  8345 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-16 13:45:21.599  7122  7122 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-16 13:45:21.599  7122  7122 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-16 13:45:21.599  7122  7122 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-16 13:45:21.599  1036  1538 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-16 13:45:21.599  1036  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-16 13:45:21.599  7122  7122 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-16 13:45:21.599  8345  8345 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-16 13:45:21.600  1036  1538 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-16 13:45:21.600  1036  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP,
08-16 13:45:21.600  7122  7122 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-16 13:45:21.600  8345  8345 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-16 13:45:21.600  7122  7122 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-16 13:45:21.600  1036  1538 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-16 13:45:21.601  1036  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-16 13:45:21.601  8345  8345 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-16 13:45:21.601  1036  1538 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
,08-16 13:45:21.601  1036  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-16 13:45:21.601  8345  8345 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-16 13:45:21.602  1036  1538 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-16 13:45:21.603  1036  1538 E WifiNative: : [418,271,519 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-16 13:45:21.603  1036  1538 D WifiNative-wlan0: doBoolean: RECONNECT
08-16 13:45:21.603  1036  1538 D WifiNative-wlan0: RECONNECT: returned true
08-16 13:45:21.603  1036  1538 D WifiNative-wlan0: doString: [STATUS]
08-16 13:45:21.604  1036  8403 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-16 13:45:21.604  1036  8403 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-16 13:45:21.604  1036  1538 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
,08-16 13:45:21.604  1036  1538 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 13:45:21.605  1036  1538 D WifiNative-wlan0: SET ps 1: returned true
08-16 13:45:21.605  1036  1537 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:45:21.607   308   895 D CommandListener: Setting iface cfg
08-16 13:45:21.607   308   895 D CommandListener: Trying to bring up p2p0
,08-16 13:45:21.609  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 3
08-16 13:45:21.610  1036  1036 D RttService: SCAN_AVAILABLE : 3
08-16 13:45:21.610  1036  1537 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-16 13:45:21.610  1036  1538 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-16 13:45:21.610  1036  1537 D LGWifiP2pService: P2pEnablingState
08-16 13:45:21.610  1036  1537 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:45:21.610  1036  1537 D LGWifiP2pService: P2p socket connection successful
08-16 13:45:21.610  1036  1537 D LGWifiP2pService: P2pEnabledState
08-16 13:45:21.610  1036  1538 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-16 13:45:21.611  1036  1538 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-16 13:45:21.611  1036  1557 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:45:21.611  1036  1556 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:45:21.611  1036  1538 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-16 13:45:21.611  1036  1556 I WifiNative-HAL: startHal
08-16 13:45:21.612  1036  1538 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-16 13:45:21.612  1036  1556 D wifi    : getting scan capabilities on interface[1] = 0xaf6dae60
08-16 13:45:21.612  1036  1556 D wifi    : failed to get capabilities : -3
08-16 13:45:21.612  1036  1556 E WifiScanningService: could not get scan capabilities
08-16 13:45:21.612  1036  1538 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-16 13:45:21.612  1036  1538 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-16 13:45:21.612  1036  1538 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-16 13:45:21.613  8345  8345 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-16 13:45:21.613  1036  1538 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-16 13:45:21.613  1036  1537 D LGWifiP2pService: sending p2p connection changed broadcast
08-16 13:45:21.613  1036  1538 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-16 13:45:21.614  1036  1537 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-16 13:45:21.614  1036  1538 E WifiStateMachine:  DriverStartedState what:132096 -100 0
,08-16 13:45:21.614  1036  1538 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
,08-16 13:45:21.614  8345  8345 E wpa_supplicant: disconnect_rssi_lvl: -100
08-16 13:45:21.614  1036  1537 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-16 13:45:21.614  1036  1537 D WifiNative-p2p0: doBoolean: SET device_name G3
08-16 13:45:21.615  8385  8385 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 13:45:21.615  1036  1537 D WifiNative-p2p0: SET device_name G3: returned true
08-16 13:45:21.615  1036  1538 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-16 13:45:21.615  1036  1537 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-16 13:45:21.615  1036  1537 D LGWifiP2pService: before postfix = G3
08-16 13:45:21.615  1036  1537 D WifiServerServiceExt: postfix byte check : 2
08-16 13:45:21.615  1036  1537 D LGWifiP2pService: after postfix = G3
08-16 13:45:21.615  1036  1537 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-16 13:45:21.615  1036  1538 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-16 13:45:21.615  1036  1537 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-16 13:45:21.615  1036  1537 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-16 13:45:21.616  1036  1538 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-16 13:45:21.616  1036  1538 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-16 13:45:21.616  1036  1537 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-16 13:45:21.616  1036  1537 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-16 13:45:21.616  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-16 13:45:21.616  1941  1941 D WfdsService: WifiP2pState is changed : true
08-16 13:45:21.616  1036  1537 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-16 13:45:21.616  1036  1537 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-16 13:45:21.617  1941  2315 D WfdsService: Receive the WFDS_ENABLE Method
08-16 13:45:21.617  1941  2315 D WfdsService: Set the WFDS Monitor: true
08-16 13:45:21.617  1036  1537 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-16 13:45:21.617  1941  2315 D WfdsService: Connected to the supplicant for wfds
08-16 13:45:21.617  1036  1537 D WifiNative-HAL: p2pGetDeviceAddress
08-16 13:45:21.617  1941  2315 D WfdsJNI : doCommand: WFDS_SET TRUE
08-16 13:45:21.617  8345  8345 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-16 13:45:21.617  1941  2315 D WfdsService: selectPreferredScanChannel [36]
08-16 13:45:21.617  1941  2315 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-16 13:45:21.617  1036  1537 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-16 13:45:21.618  8345  8345 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-16 13:45:21.619  1941  1941 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-16 13:45:21.619  8345  8345 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 13:45:21.620  1036  8403 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-16 13:45:21.620  8345  8345 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-16 13:45:21.620  1036  8403 E WifiMonitor: WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 13:45:21.620  8345  8345 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 13:45:21.620  1036  8403 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 13:45:21.620  1036  8403 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 13:45:21.620  1036  1538 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-16 13:45:21.620  1036  8403 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER t,ype=WORLD]
08-16 13:45:21.620  1036  8403 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 13:45:21.620  1036  8403 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 13:45:21.620  1036  8403 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 13:45:21.621  1036  1538 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-16 13:45:21.621  8345  8345 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 13:45:21.621  1036  1538 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-16 13:45:21.621  1036  1538 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-16 13:45:21.622  1036  1538 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-16 13:45:21.622  8345  8345 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-16 13:45:21.622  8345  8345 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 13:45:21.623  1036  8403 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 13:45:21.623  1036  8403 E WifiMonitor: WifiMonitor:p2p0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 13:45:21.623  1036  8403 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 13:45:21.623  1036  1538 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-16 13:45:21.623  1036  8403 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 13:45:21.623  1036  1538 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-16 13:45:21.623  1036  8403 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-16 13:45:21.623  1036  8403 E WifiMonitor: WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 13:45:21.623  1036  8403 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 13:45:21.623  1036  8403 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 13:45:21.623  1036  1538 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-16 13:45:21.623  1036  1538 D WifiNative-wlan0: doBoolean: SCAN
08-16 13:45:21.623  1036  1538 D WifiNative-wlan0: SCAN: returned false
08-16 13:45:21.623  1036  1537 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-16 13:45:21.624  1036  1537 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-16 13:45:21.624  1941  1941 D WfdsService: isConnected: false
08-16 13:45:21.624  1036  1538 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=418293  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-16 13:45:21.624  1941  8406 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 13:45:21.624  1941  8406 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 13:45:21.625  1036  1537 D WifiNative-p2p0: P2P_FLUSH: returned true
08-16 13:45:21.625  1036  1537 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-16 13:45:21.626  1036  1537 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-16 13:45:21.626  1036  1537 D WifiNative-p2p0: doString: [LIST_NETWORKS]
,08-16 13:45:21.627  1036  1537 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-16 13:45:21.627  1036  1537 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
,08-16 13:45:21.630  1941  1941 I WfdStateTracker: handleP2pThisDeviceChanged
08-16 13:45:21.630  1941  1941 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-16 13:45:21.630  1941  1941 D WfdsService: Update P2p Interface State: 3
08-16 13:45:21.632  7122  7122 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-16 13:45:21.633  1036  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=418302  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-16 13:45:21.633  1036  1538 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 13:45:21.634  1036  1538 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 13:45:21.634  1036  1538 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 13:45:21.637  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 13:45:21.637  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-16 13:45:21.638  1036  1538 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 13:45:21.638  1036  1538 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 13:45:21.639  1036  1537 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-16 13:45:21.639  1036  1537 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-16 13:45:21.640  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:45:21.640  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:45:21.640  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-16 13:45:21.639  1036  1537 D LGWifiP2pService: InactiveState
08-16 13:45:21.640  1036  1537 D LGWifiP2pService: InactiveState{ when=-19ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:45:21.640  1036  1537 D LGWifiP2pService: P2pEnabledState{ when=-19ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:45:21.640  1036  1537 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-16 13:45:21.641  8345  8345 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
,08-16 13:45:21.641  8345  8345 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 13:45:21.642  1941  8406 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-16 13:45:21.642  8345  8345 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-16 13:45:21.642  8345  8345 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 13:45:21.642  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 13:45:21.642  1036  1036 D WifiServerServiceExt: setSupplicantStateSCANNING
08-16 13:45:21.642  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 13:45:21.643  1941  8406 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 13:45:21.643  1036  1537 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-16 13:45:21.643  8345  8345 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 13:45:21.643  1036  1537 D LGWifiP2pService: InactiveState{ when=-17ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:45:21.643  1036  1537 D LGWifiP2pService: P2pEnabledState{ when=-17ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:45:21.643  1036  1537 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:45:21.643  1036  1537 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:45:21.643  1036  1537 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:45:21.643  1036  1537 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:45:21.644  1036  1537 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:45:21.644  1036  1537 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:45:21.644  1036  1537 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:45:21.644  1036  1537 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:45:21.644  1036  1537 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:45:21.644  1036  1537 D LGWifiP2pService: InactiveState{ when=-1ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:45:21.644  1036  1537 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:45:21.644  1036  1537 D LGWifiP2pService: DefaultState{ when=-1ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:45:21.644  1941  8406 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 13:45:21.644  1036  1036 E WifiServerServiceExt: No p2p device connected
08-16 13:45:21.645  1036  8403 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-16 13:45:21.645  1036  8403 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 13:45:21.645  1036  8403 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 13:45:21.645  1036  8403 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 13:45:21.645  1036  8403 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 13:45:21.645  1036  8403 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CH,ANGE init=DRIVER type=WORLD
08-16 13:45:21.645  1036  8403 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 13:45:21.645  1036  8403 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 13:45:21.645  1036  8403 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 13:45:21.645  1036  8403 E WifiMonitor: WifiMonitor:p2p0 cnt=53 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 13:45:21.645  1036  8403 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 13:45:21.645  1036  8403 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 13:45:21.646  1941  2315 W WfdsService: DefaultState - msg [9441285] is not handled
08-16 13:45:21.646  8363  8408 W FormManager: Network not available. Please check & try again.
08-16 13:45:21.648  8363  8409 V FormManager: Network unavailable.
08-16 13:45:21.648  7122  7122 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 13:45:21.659  8363  8409 V FormManager: Network unavailable.
,08-16 13:45:21.664  4740  4740 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,08-16 13:45:21.664  4740  4740 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 13:45:21.666  4740  4740 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 13:45:21.671  4740  4740 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 13:45:21.675  4740  8410 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-16 13:45:21.677  4740  8411 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 13:45:21.678  4740  8411 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-16 13:45:21.706  1036  1995 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8412 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-16 13:45:21.789  8412  8412 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-16 13:45:21.789  8412  8412 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-16 13:45:21.794  8412  8412 V [BNRBootReceiver]: Boot Receiver Return
08-16 13:45:21.797  8412  8412 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-16 13:45:21.873  1036  1904 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8430 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-16 13:45:21.874  1036  1904 I ActivityManager: Killing 7657:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
08-16 13:45:21.896   341   341 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 435us total 20.312ms
,08-16 13:45:21.915   341   341 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 365us total 17.981ms
,08-16 13:45:21.931   341   341 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 289us total 15.107ms
,08-16 13:45:21.955  1036  1958 W libprocessgroup: failed to open /acct/uid_10005/pid_7657/cgroup.procs: No such file or directory
08-16 13:45:21.969  8430  8430 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-16 13:45:21.990  8430  8430 D PluginManager: init()
,08-16 13:45:22.137  1036  8403 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-16 13:45:22.137  1036  8403 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-16 13:45:22.137  1036  8403 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-16 13:45:22.137  1036  8403 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: WPS-AP-AVAILABLE 
08-16 13:45:22.137  1036  8403 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-16 13:45:22.138  1036  1538 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-16 13:45:22.138  1036  1538 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
,08-16 13:45:22.138  8345  8345 E wpa_supplicant: USIM:  scard_init function
08-16 13:45:22.138  1036  1538 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-16 13:45:22.139  1036  1538 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-16 13:45:22.139  1036  1538 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-16 13:45:22.140  8345  8345 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-16 13:45:22.141  1036  8403 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-16 13:45:22.141  1036  8403 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-16 13:45:22.160  1036  1538 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=418829  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-16 13:45:22.163  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:45:22.163  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:45:22.163  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
,08-16 13:45:22.171  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 13:45:22.171  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 13:45:22.173  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:45:22.173  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:45:22.173  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-16 13:45:22.176  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 13:45:22.177  1036  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=418846  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-16 13:45:22.178  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 13:45:22.178  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-16 13:45:22.179  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 13:45:22.179  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 13:45:22.180  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 13:45:22.255  8345  8345 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-16 13:45:22.257  1036  1107 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-16 13:45:22.258  1036  8403 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-16 13:45:22.258  1036  8403 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-16 13:45:22.258  1036  8403 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-16 13:45:22.258  1036  8403 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-16 13:45:22.258  1036  8403 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 13:45:22.258  1036  8403 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 13:45:22.259  1036  1538 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=418928  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-16 13:45:22.261  1036  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=418930  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-16 13:45:22.265  8345  8345 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 13:45:22.265  8345  8345 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-16 13:45:22.268  1036  8403 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 13:45:22.269  1036  8403 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 13:45:22.270  1036  1538 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=418939
08-16 13:45:22.270  1036  8403 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-16 13:45:22.270  1036  1538 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=418939
08-16 13:45:22.270  1036  8403 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 13:45:22.270  1036  8403 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 13:45:22.270  1036  8403 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-16 13:45:22.270  1036  8403 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-16 13:45:22.270  1036  8403 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-16 13:45:22.270  1036  8403 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 13:45:22.271  1036  8403 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 13:45:22.271  1036  1538 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=418940
08-16 13:45:22.271  1036  1538 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=418940
08-16 13:45:22.271  1036  1538 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=418940
08-16 13:45:22.272  1036  1538 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=418941  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
,08-16 13:45:22.274  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:45:22.274  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:45:22.274  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-16 13:45:22.275  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 13:45:22.275  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 13:45:22.277  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:45:22.277  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:45:22.277  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
,08-16 13:45:22.278  1036  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=418947  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-16 13:45:22.278  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 13:45:22.280  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 13:45:22.280  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-16 13:45:22.280  1036  1538 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
08-16 13:45:22.281  1036  1538 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-16 13:45:22.281  1036  1538 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-16 13:45:22.282  1036  1538 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-16 13:45:22.282  8430  8430 W ExternalStrings: load override strings
08-16 13:45:22.282  8430  8430 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
08-16 13:45:22.282  8430  8430 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
08-16 13:45:22.282  8430  8430 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
08-16 13:45:22.282  8430  8430 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
08-16 13:45:22.282  8430  8430 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
08-16 13:45:22.282  8430  8430 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
08-16 13:45:22.282  8430  8430 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
08-16 13:45:22.282  8430  8430 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-16 13:45:22.282  8430  8430 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-16 13:45:22.282  8430  8430 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-16 13:45:22.282  8430  8430 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-16 13:45:22.282  8430  8430 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 13:45:22.282  8430  8430 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
08-16 13:45:22.282  8430  8430 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-16 13:45:22.282  8430  8430 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 13:45:22.282  8430  8430 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 13:45:22.282  8430  8430 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-16 13:45:22.282  8430  8430 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-16 13:45:22.282  1036  1538 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 13:45:22.283  1036  1538 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=418952  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-16 13:45:22.284  1036  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=418953  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-16 13:45:22.284  8430  8430 D StatusProvider: onCreate
08-16 13:45:22.284  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 13:45:22.284  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 13:45:22.284  1036  1538 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=418954
08-16 13:45:22.285  1036  1538 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=418954
08-16 13:45:22.285  ,1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 13:45:22.285  1036  1538 D WifiNative-wlan0: doString: [STATUS]
08-16 13:45:22.286  1036  8403 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 13:45:22.286  1036  8403 E WifiMonitor: WifiMonitor:wlan0 cnt=64 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 13:45:22.288  1036  1538 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
,08-16 13:45:22.293  1036  1538 I WifiServiceExtension: setVHTCapabilityType  : false
08-16 13:45:22.302  1036  1538 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-16 13:45:22.302  1036  1538 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,08-16 13:45:22.305  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:45:22.305  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:45:22.306  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-16 13:45:22.307  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:45:22.307  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:45:22.307  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-16 13:45:22.307  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 13:45:22.307  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 13:45:22.310  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 13:45:22.312  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 13:45:22.312  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 13:45:22.313  1036  1382 V AlarmManager: RTC_WAKEUP set : Alarm{3bfa2083 type 0 when 1471347904262 com.google.android.gms} when 1471347904262
08-16 13:45:22.313  1036  1382 V AlarmManager: ELAPSED_WAKEUP set : Alarm{27b9f200 type 2 when 409920 com.google.android.gms} when 409920
,08-16 13:45:22.314  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 13:45:22.320  1036  1538 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-16 13:45:22.320  1036  1545 D ConnectivityService: Got NetworkAgent Messenger
08-16 13:45:22.321  1036  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-16 13:45:22.321  1036  1545 D ConnectivityService: NetworkAgent connected
08-16 13:45:22.321  1036  1538 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 13:45:22.321  1036  1538 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-16 13:45:22.321  1036  1538 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-16 13:45:22.321  1036  1538 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-16 13:45:22.329  1036  1538 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-16 13:45:22.329  1036  1538 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 13:45:22.329  1036  1538 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-16 13:45:22.329  1036  1538 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-16 13:45:22.329  1036  1538 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,08-16 13:45:22.335  1036  1538 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-16 13:45:22.336   308   895 D CommandListener: Setting iface cfg
08-16 13:45:22.338  1036  1538 E WifiStateMachine: Start Dhcp Watchdog 3
08-16 13:45:22.339  1036  1538 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=419008  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 13:45:22.339  1036  8451 D DhcpStateMachine: StoppedState
08-16 13:45:22.339  1036  8451 D DhcpStateMachine: StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:45:22.339  1036  8451 D DhcpStateMachine: WaitBeforeStartState
08-16 13:45:22.340  1036  1538 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=419009  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,08-16 13:45:22.340  1036  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=419009  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 13:45:22.341  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 13:45:22.341  1036  1036 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-16 13:45:22.341  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 13:45:22.341  1036  1036 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-16 13:45:22.342  1036  1538 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=419011  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 13:45:22.342  1036  1538 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=419011  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 13:45:22.343  1036  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=419012  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 13:45:22.344  1036  1538 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:24276] from screen [on:0 period:-1825860185] gl rssi=-54 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 13:45:22.344  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1825860184] gl rssi=-54 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 13:45:22.345  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-16 13:45:22.348  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 13:45:22.349  1036  1545 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
08-16 13:45:22.349  1036  1538 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 13:45:22.350  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 13:45:22.350  1036  1538 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 13:45:22.350  1036  1538 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 13:45:22.351  1036  1538 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 13:45:22.352  1036  1538 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 13:45:22.352  1036  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-16 13:45:22.352  1036  1538 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=207,0,0
08-16 13:45:22.353  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=207,0,0
08-16 13:45:22.353  1036  1538 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-16 13:45:22.353  8345  8345 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-16 13:45:22.353  1036  1538 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-16 13:45:22.353  1036  1538 D WifiNative-wlan0: doBoolean: SET ps 0
08-16 13:45:22.354  1036  1538 D WifiNative-wlan0: SET ps 0: returned true
08-16 13:45:22.354  1036  1538 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-16 13:45:22.354  8345  8345 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-16 13:45:22.356  1036  1538 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-16 13:45:22.356  1036  1538 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-16 13:45:22.356  1036  1538 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-16 13:45:22.356  1036  1537 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1e933aeb target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:45:22.356  1036  1537 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1e933aeb target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:45:22.356  1036  8451 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:45:22.356  1036  1538 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-16 13:45:22.356  1036  8451 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-16 13:45:22.357   308   895 D CommandListener: Setting iface cfg
,08-16 13:45:22.357   308   895 D CommandListener: Trying to bring up wlan0
08-16 13:45:22.358  1036  1538 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-16 13:45:22.360  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 13:45:22.360  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-16 13:45:22.362  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 13:45:22.362  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-16 13:45:22.363  1036  1538 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK 
08-16 13:45:22.364  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK 
08-16 13:45:22.364  1036  1538 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-16 13:45:22.364  1036  1537 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:45:22.364  1036  1537 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:45:22.364  8345  8345 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-16 13:45:22.365  1036  1538 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-16 13:45:22.365  1036  1538 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-16 13:45:22.365  8345  8345 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-16 13:45:22.365  1036  1538 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-16 13:45:22.365  1036  1538 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 13:45:22.369  1036  2033 I art     : Explicit concurrent mark sweep GC freed 61297(2MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 1.654ms total 75.867ms
,08-16 13:45:22.381  1036  1538 D WifiNative-wlan0: SET ps 1: returned true
08-16 13:45:22.382  1036  1538 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 13:45:22.382  1036  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-16 13:45:22.382  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 13:45:22.382  1036  1538 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 13:45:22.383  1036  1538 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 13:45:22.383  1036  1538 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 13:45:22.384  1036  1538 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 13:45:22.384  1036  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-16 13:45:22.385  1036  1538 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-16 13:45:22.385  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-16 13:45:22.385  1036  1538 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-16 13:45:22.386  1036  1545 D ConnectivityService: ignoring duplicate network state non-change
,08-16 13:45:22.388  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 13:45:22.388  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 13:45:22.390  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:45:22.390  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:45:22.390  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-16 13:45:22.390  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 13:45:22.393  1036  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-16 13:45:22.394  1036  1545 D ConnectivityService: Adding iface wlan0 to network 102
08-16 13:45:22.395  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:45:22.395  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:45:22.395  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-16 13:45:22.398  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-16 13:45:22.400  1941  1941 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-16 13:45:22.403  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:45:22.403  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:45:22.403  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-16 13:45:22.404  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,08-16 13:45:22.408  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:45:22.409  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:45:22.409  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-16 13:45:22.409  1036  1538 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-16 13:45:22.410  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 13:45:22.410  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 13:45:22.412  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 13:45:22.414  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 13:45:22.414  1603  1603 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-16 13:45:22.414  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 13:45:22.417  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 13:45:22.417  1603  1603 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-16 13:45:22.417  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 13:45:22.421  1036  1545 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-16 13:45:22.421  1036  1545 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-16 13:45:22.423  1036  1545 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
08-16 13:45:22.424   308   895 E Netd    : netlink response contains error (File exists)
08-16 13:45:22.424  1036  1545 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-16 13:45:22.425  1036  1545 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-16 13:45:22.425  1036  1545 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
08-16 13:45:22.425  1036  1545 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
08-16 13:45:22.426  1036  1545 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-16 13:45:22.426  1036  1545 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-16 13:45:22.426  1036  1545 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-16 13:45:22.428  1036  8450 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:45:22.428  1036  8450 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-16 13:45:22.428  1036  8450 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:45:22.428  1036  8450 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-16 13:45:22.429  1036  1545 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-16 13:45:22.429  1036  1545 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 13:45:22.429  1036  1545 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 13:45:22.429  1036  1545 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-16 13:45:22.429  1036  1545 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 13:45:22.429  1036  1545 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-16 13:45:22.429  1036  1545 D ConnectivityService: currentScore = 0, newScore = 20
08-16 13:45:22.429  1036  1545 D ConnectivityService:    accepting network in place of null
08-16 13:45:22.430  1036  1545 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 13:45:22.431  1036  1545 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-16 13:45:22.431  1036  1545 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-16 13:45:22.431  1036  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,_IMMEDIATE
08-16 13:45:22.431  1036  1545 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-16 13:45:22.431  1036  1545 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-16 13:45:22.432  1036  1545 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-16 13:45:22.432  1036  1538 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 13:45:22.432  1036  1538 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 13:45:22.433  1036  1036 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-16 13:45:22.433  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-16 13:45:22.433  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-16 13:45:22.433  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-16 13:45:22.433   308  8461 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-16 13:45:22.433  1851  1851 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-16 13:45:22.435  1851  1851 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-16 13:45:22.436  1036  1545 D ConnectivityService: validation of new default Network = false
08-16 13:45:22.436  1036  1545 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-16 13:45:22.436  1036  1545 D DSQN    : enableDataServiceNotify 
08-16 13:45:22.436  1036  1545 D DSQN    : start dsqn bin
08-16 13:45:22.442  1036  1545 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-16 13:45:22.442  1036  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 13:45:22.442  1036  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 13:45:22.433  8462  8462 W dsqn    : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 13:45:22.433  8462  8462 W dsqn    : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 13:45:22.443  1036  1545 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 13:45:22.444  1603  2071 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-16 13:45:22.451  1036  1536 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,08-16 13:45:22.456  8462  8462 E DSQN    : DSQN ssw
08-16 13:45:22.458  8430  8430 V Signer  : override build config not found
08-16 13:45:22.459  8430  8430 D Signer  : value of property debug is false
08-16 13:45:22.461  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 13:45:22.462  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 13:45:22.462  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 13:45:22.486   308  8461 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-16 13:45:22.491  8430  8430 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
08-16 13:45:22.491  8430  8430 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
08-16 13:45:22.491  8430  8430 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
08-16 13:45:22.491  8430  8430 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
08-16 13:45:22.492  8430  8430 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
08-16 13:45:22.492  8430  8430 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
08-16 13:45:22.492  8430  8430 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
08-16 13:45:22.492  8430  8430 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
08-16 13:45:22.492  8430  8430 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
08-16 13:45:22.492  8430  8430 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
08-16 13:45:22.493  8430  8430 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
08-16 13:45:22.493  8430  8430 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
08-16 13:45:22.493  8430  8430 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
08-16 13:45:22.502  8430  8430 V LGMDMManager: Create singleton instance
,08-16 13:45:22.527   308  8461 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-16 13:45:22.546  8430  8430 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
,08-16 13:45:22.557  1036  8451 D DhcpStateMachine: DHCPV4 request on wlan0
,08-16 13:45:22.558  1036  8451 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
,08-16 13:45:22.558  1036  8451 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-16 13:45:22.553  8467  8467 W dhcpcd  : type=1400 audit(0.0:195): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 13:45:22.562   308   894 D LGDataListener: argv[0]=dsqncommand
08-16 13:45:22.562   308   894 D LGDataListener: argv[1]=wlan0
08-16 13:45:22.562   308   894 D LGDataListener: argv[2]=1
08-16 13:45:22.562   308   894 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-16 13:45:22.553  8467  8467 W dhcpcd  : type=1400 audit(0.0:196): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 13:45:22.564  1036  1105 D DSQN    : DSQM DsqnNotification wlan0  1
08-16 13:45:22.564  1036  1105 D DSQN    : start to monitor internet connection
,08-16 13:45:22.567  8467  8467 I dhcpcd  : version 5.5.6 starting
08-16 13:45:22.568  8467  8467 E dhcpcd  : get_duid: m
08-16 13:45:22.568  8467  8467 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-16 13:45:22.568  8467  8467 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-16 13:45:22.587  1036  8450 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 16 Aug 2016 11:45:22 GMT], X-Android-Received-Millis=[1471347922587], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1471347922560]}
08-16 13:45:22.587  1036  8450 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-16 13:45:22.587  1036  8450 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-16 13:45:22.587  1036  1545 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
08-16 13:45:22.587  1036  1545 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
,08-16 13:45:22.587  1036  1545 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 13:45:22.587  1036  1545 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 13:45:22.588  1036  1545 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-16 13:45:22.588  1036  1545 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-16 13:45:22.588  1036  1545 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-16 13:45:22.588  1036  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 13:45:22.588  1036  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 13:45:22.588  1036  1545 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 13:45:22.588  1036  1545 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 13:45:22.589  1036  1538 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 13:45:22.589  1603  2071 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-16 13:45:22.589  1036  1538 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 13:45:22.589  1036  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-16 13:45:22.590  1851  1851 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 13:45:22.590  1851  1851 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,08-16 13:45:22.606  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 13:45:22.607  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 13:45:22.608  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 13:45:22.626  8467  8467 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-16 13:45:22.626  8467  8467 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-16 13:45:22.626  8467  8467 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-16 13:45:22.626  8467  8467 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
08-16 13:45:22.626  8467  8467 D dhcpcd  : wlan0: sending REQUEST (xid 0x4a84e443), next in 4.58 seconds
,08-16 13:45:22.633  8430  8430 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 13:45:22.634  8430  8477 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-16 13:45:22.641  7122  7122 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 13:45:22.650  8467  8467 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
08-16 13:45:22.652  7122  7122 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 13:45:22.663  7150  7150 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 13:45:22.664  7150  7150 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 13:45:22.666  7150  7150 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-16 13:45:22.671  7122  7122 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-16 13:45:22.678  7122  7122 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-16 13:45:22.690  8467  8467 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
08-16 13:45:22.690  8467  8467 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
08-16 13:45:22.691  8467  8467 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
,08-16 13:45:22.691  8467  8467 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-16 13:45:22.691  8467  8467 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-16 13:45:22.692  8467  8467 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-16 13:45:22.692  8467  8467 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-16 13:45:22.693  8467  8467 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-16 13:45:22.761  8430  8430 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 13:45:22.761  8430  8477 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-16 13:45:22.772  8430  8476 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
08-16 13:45:22.775  7122  7122 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 13:45:22.781  7122  7122 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 13:45:22.788  7150  7150 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 13:45:22.789  7150  7150 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 13:45:22.793  7150  7150 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-16 13:45:22.795  8430  8430 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 13:45:22.795  8430  8477 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-16 13:45:22.802  7122  7122 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 13:45:22.808  7122  7122 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 13:45:22.814  7150  7150 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 13:45:22.814  7150  7150 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 13:45:22.815  7150  7150 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-16 13:45:22.819  7122  7122 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-16 13:45:22.819  7122  7122 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-16 13:45:22.819  7122  7122 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-16 13:45:22.819  7122  7122 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-16 13:45:22.820  7122  7122 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-16 13:45:22.821  7122  7122 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-16 13:45:22.821  7122  7122 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-16 13:45:22.821  7122  7122 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-16 13:45:22.821  7122  7122 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-16 13:45:22.821  7122  7122 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-16 13:45:22.821  7122  7122 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-16 13:45:22.821  7122  7122 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-16 13:45:22.824  8430  8430 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 13:45:22.824  8430  8477 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-16 13:45:22.830  7122  7122 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 13:45:22.835  7122  7122 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 13:45:22.842  7150  7150 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 13:45:22.842  7150  7150 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 13:45:22.843  7150  7150 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-16 13:45:22.846  8430  8430 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 13:45:22.847  8430  8477 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-16 13:45:22.855  7122  7122 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 13:45:22.861  7122  7122 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 13:45:22.868  7150  7150 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-16 13:45:22.869  7150  7150 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 13:45:22.869  7150  7150 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 13:45:22.872  8430  8430 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 13:45:22.872  8430  8477 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-16 13:45:22.877  7122  7122 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 13:45:22.883  7122  7122 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 13:45:22.888  7150  7150 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 13:45:22.888  7150  7150 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 13:45:22.889  7150  7150 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 13:45:22.897  8430  8430 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 13:45:22.897  8430  8477 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-16 13:45:22.906  7122  7122 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 13:45:22.912  7122  7122 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 13:45:22.917  7150  7150 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 13:45:22.917  7150  7150 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 13:45:22.917  7150  7150 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 13:45:22.918  1036  1994 I ActivityManager: Killing 7487:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
08-16 13:45:22.959  8430  8476 D LgDataFeature: LgDataFeature() Constructor: none
08-16 13:45:22.960  8430  8476 D LgDataFeature: LgDataFeature() Constructor Done, null
08-16 13:45:22.961  1036  8451 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-16 13:45:22.963  1036  8451 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-16 13:45:22.964  1036  8451 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-16 13:45:22.964  1036  8451 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
08-16 13:45:22.964  1036  8451 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-16 13:45:22.964  1036  8451 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-16 13:45:22.964  1036  8451 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-16 13:45:22.964  1036  8451 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-16 13:45:22.967  1036  8451 D DhcpStateMachine: RunningState
,08-16 13:45:23.065  8430  8476 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
,08-16 13:45:23.133  1036  1903 W libprocessgroup: failed to open /acct/uid_10093/pid_7487/cgroup.procs: No such file or directory
,08-16 13:45:23.157  1816  6233 I EventLogService: Aggregate from 1471347892175 (log), 1471346104192 (data)
,08-16 13:45:23.159   308  8510 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-16 13:45:23.159   308  8510 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
08-16 13:45:23.170  8430  8476 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
08-16 13:45:23.190  8430  8476 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
,08-16 13:45:23.190  8430  8476 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-16 13:45:23.191  8430  8476 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-16 13:45:23.191   308  8510 D libc-netbsd: res_queryN name = mtalk.google.com succeed
08-16 13:45:23.193  8430  8476 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
08-16 13:45:23.193  8430  8476 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
08-16 13:45:23.197  8430  8476 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
08-16 13:45:23.199  8430  8476 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
08-16 13:45:23.205  1036  1995 I ActivityManager: Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=8516 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,08-16 13:45:23.307  8516  8516 I DigitalAppWidgetProvider: onReceive: com.android.deskclock.ON_QUARTER_HOUR
,08-16 13:45:23.313  8516  8516 V DigitalAppWidgetProvider: startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@313e8d2c
08-16 13:45:23.324  8430  8477 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-16 13:45:23.325  8430  8430 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 13:45:23.338  7122  7122 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 13:45:23.345  7122  7122 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-16 13:45:23.352  7150  7150 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 13:45:23.352  7150  7150 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 13:45:23.353  7150  7150 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-16 13:45:23.358  8430  8430 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 13:45:23.404  7122  7122 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 13:45:23.413  7122  7122 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 13:45:23.423  7150  7150 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-16 13:45:23.424  7150  7150 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 13:45:23.425  7150  7150 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 13:45:23.435  8430  8430 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 13:45:23.444  2175  8538 D GCM     : Connected
08-16 13:45:23.445  8385  8385 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-16 13:45:23.453  1036  1538 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 13:45:23.454  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 13:45:23.455  1036  1538 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 13:45:23.456  1036  1538 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 13:45:23.458  1036  1538 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 13:45:23.458  8385  8385 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-16 13:45:23.459  1036  1538 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-16 13:45:23.460  1036  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
08-16 13:45:23.460  1036  1545 D ConnectivityService: identical MTU - not setting
08-16 13:45:23.461  1036  1545 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-16 13:45:23.461  1036  1545 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-16 13:45:23.461  1036  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 13:45:23.461  1036  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 13:45:23.462  1036  1545 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 13:45:23.463  1603  2071 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-16 13:45:23.466  7122  7122 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 13:45:23.472  7122  7122 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 13:45:23.476  2175  8538 D GCM     : Message class com.google.e.a.a.q
,08-16 13:45:23.481  7150  7150 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 13:45:23.481  7150  7150 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 13:45:23.482  7150  7150 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-16 13:45:23.483  7150  7150 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-16 13:45:23.483  7150  7150 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-16 13:45:23.491  8430  8430 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 13:45:23.501  8385  8385 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-16 13:45:23.502  8385  8385 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-16 13:45:23.509  7122  7122 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 13:45:23.515  7122  7122 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 13:45:23.525  7150  7150 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 13:45:23.525  7150  7150 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 13:45:23.526  7150  7150 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-16 13:45:23.527  7150  7150 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,08-16 13:45:23.527  7150  7150 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-16 13:45:23.533  8430  8430 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 13:45:23.536  8430  8430 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 13:45:23.543  8430  8430 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 13:45:23.550  8430  8430 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 13:45:23.552  8430  8430 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 13:45:23.554  8430  8430 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 13:45:23.558  8430  8430 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 13:45:23.561  8430  8430 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 13:45:23.563  1036  1575 I ActivityManager: Killing 7976:com.google.android.talk/u0a72 (adj 15): empty #17
08-16 13:45:23.619  1036  1940 W libprocessgroup: failed to open /acct/uid_10072/pid_7976/cgroup.procs: No such file or directory
,08-16 13:45:25.355  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-53 f=2447 sc=60 link=72 tx=103.5, 0.0, 0.0  rx=96.0 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:-1825857173] gl rssi=-53 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 13:45:25.358  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-53 f=2447 sc=60 link=72 tx=103.5, 0.0, 0.0  rx=96.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1825857170] gl rssi=-53 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 13:45:25.358  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-16 13:45:25.383  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 13:45:25.399  1036  1539 V WifiInternetCheck: Single check msg out of sync, ignoring.
,08-16 13:45:25.434  1036  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 13:45:25.451  1036  1107 D Tethering: MasterInitialState.processMessage what=3
08-16 13:45:25.471  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:45:25.471  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:45:25.471  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 13:45:25.471  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:45:25.471  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 13:45:25.471  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 13:45:25.471  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 13:45:25.471  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 13:45:25.476  6936  6936 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 13:45:25.481  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:45:25.481  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:45:25.481  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 13:45:25.481  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:45:25.481  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 13:45:25.481  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 13:45:25.481  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 13:45:25.481  6936  6936 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 13:45:25.483  6936  6936 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 13:45:25.486  1036  1092 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-16 13:45:25.493  8430  8430 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-16 13:45:25.510  5811  5811 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,08-16 13:45:25.527  8430  8505 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-16 13:45:25.544  6936  6997 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:45:25.544  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:45:25.544  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 13:45:25.544  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:45:25.544  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 13:45:25.544  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 13:45:25.544  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 13:45:25.544  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 13:45:25.548  6936  6997 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 13:45:25.549  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:45:25.549  6936  6997 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@18240d80 removed from the list
08-16 13:45:25.549  6936  6997 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:45:25.549  6936  6997 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:45:25.549  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:45:25.554  2175  2175 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-16 13:45:25.567  7309  7309 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-16 13:45:25.567  7309  7309 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-16 13:45:25.567  7309  7309 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-16 13:45:25.567  7309  7309 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-16 13:45:25.573  7309  7309 I AppUp4:CustModeStarterReceiver: onReceive
08-16 13:45:25.576  7309  7309 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@166647fb
08-16 13:45:25.576  7309  7309 D AppUp4:CustFacade: isCustomizationCompleted : false
08-16 13:45:25.576  7309  7309 D AppUp4:CustFacade: isPhone : true
08-16 13:45:25.577  7309  7309 D AppUp4:CustModeStarterReceiver: begin check event
08-16 13:45:25.577  7309  7309 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-16 13:45:25.582  4740  4740 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-16 13:45:25.582  4740  4740 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 13:45:25.583  4740  4740 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-16 13:45:25.589  4740  4740 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 13:45:25.603  2851  2851 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,08-16 13:45:25.607  1036  1092 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 13:45:25.612  2851  2851 V DownloadManager: DownloadService onCreate
08-16 13:45:25.613  4740  8566 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-16 13:45:25.614  2851  8569 I DownloadManager: in removeSpuriousFiles
08-16 13:45:25.616  2851  8569 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,08-16 13:45:25.619  4740  8568 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-16 13:45:25.619  4740  8568 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-16 13:45:25.620  2851  8569 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@1710f5bc on behalf of 2851
08-16 13:45:25.621  2851  8569 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
08-16 13:45:25.621  2851  8569 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
08-16 13:45:25.621  2851  8569 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
08-16 13:45:25.621  2851  8569 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
08-16 13:45:25.621  2851  8569 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
08-16 13:45:25.621  2851  8569 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
,08-16 13:45:25.621  2851  8569 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
08-16 13:45:25.622  2851  8569 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
08-16 13:45:25.622  4740  8566 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
08-16 13:45:25.622  2851  8569 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
08-16 13:45:25.622  2851  8569 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
08-16 13:45:25.622  2851  8569 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
08-16 13:45:25.623  2851  8569 I DownloadManager: in trimDatabase
08-16 13:45:25.623  2851  8569 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
08-16 13:45:25.624  2851  8569 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@8801945 on behalf of 2851
08-16 13:45:25.634  1036  1575 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 102]) by 10005
08-16 13:45:25.634  1036  8450 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:45:25.635  1036  8450 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:45:25.635  1036  8450 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-16 13:45:25.635  1036  8450 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:45:25.635  1036  8450 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
,08-16 13:45:25.659  1036  1922 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=8576 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-16 13:45:25.663  1036  8450 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 16 Aug 2016 11:45:25 GMT], X-Android-Received-Millis=[1471347925663], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1471347925636]}
08-16 13:45:25.663  1036  8450 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-16 13:45:25.663  1036  8450 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-16 13:45:25.663  1036  1545 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
08-16 13:45:25.664  1036  1545 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-16 13:45:25.664  1036  1545 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 13:45:25.664  1036  1545 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 13:45:25.664  1036  1545 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-16 13:45:25.664  4740  8566 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
08-16 13:45:25.664  1036  1545 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-16 13:45:25.664  1036  1545 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-16 13:45:25.664  1036  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 13:45:25.664  1036  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 13:45:25.665  1036  1545 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 13:45:25.665  1603  2071 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-16 13:45:25.666  2851  2851 V DownloadManager: DownloadService onStartCommand
08-16 13:45:25.667  2851  8570 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
08-16 13:45:25.669  2851  8570 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@12d5b1a8 on behalf of 2851
08-16 13:45:25.672  4740  4740 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
08-16 13:45:25.673  4740  4740 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
08-16 13:45:25.673  4740  4740 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,08-16 13:45:25.675  4740  4740 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
08-16 13:45:25.677  2851  8570 V DownloadManager: processing inserted download 1
08-16 13:45:25.678  2851  8570 V DownloadManager: processing inserted download 4
08-16 13:45:25.679  2851  8570 V DownloadManager: processing inserted download 7
08-16 13:45:25.681  2851  8570 V DownloadManager: processing inserted download 8
08-16 13:45:25.682  4740  4740 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
08-16 13:45:25.682  2851  8570 V DownloadManager: processing inserted download 9
08-16 13:45:25.683  2851  8570 V DownloadManager: processing inserted download 10
08-16 13:45:25.685  2851  8570 V DownloadManager: processing inserted download 11
08-16 13:45:25.686  2851  8570 V DownloadManager: processing inserted download 12
08-16 13:45:25.687  2851  8570 V DownloadManager: processing inserted download 13
08-16 13:45:25.688  2851  8570 V DownloadManager: processing inserted download 14
08-16 13:45:25.689  2851  8570 V DownloadManager: processing inserted download 16
,08-16 13:45:25.692  2851  2851 V DownloadManager: DownloadService onDestroy
08-16 13:45:25.716  8576  8576 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 13:45:25.716  8576  8576 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 13:45:25.717  8576  8576 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-16 13:45:25.718  8576  8576 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-16 13:45:25.810  8576  8576 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-16 13:45:25.824  8576  8576 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-16 13:45:25.881  8576  8576 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-16 13:45:25.923  8576  8576 D LgDataFeature: LgDataFeature() Constructor: none
,08-16 13:45:25.923  8576  8576 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 13:45:26.093  8576  8576 D eas_req : ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-16 13:45:26.155  8576  8576 I HubEmail: JNI_OnLoad()
08-16 13:45:26.155  8576  8576 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-16 13:45:26.155  8576  8576 I HubEmail: registerNatives()
08-16 13:45:26.155  8576  8576 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-16 13:45:26.155  8576  8576 I HubEmail: registerNativeMethods()
08-16 13:45:26.155  8576  8576 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,08-16 13:45:26.162  8576  8576 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
08-16 13:45:26.170   308  8609 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-16 13:45:26.173   308  8609 D libc-netbsd: res_queryN name = static-avc.lglime.com, class = 1, type = 1
08-16 13:45:26.176  8576  8607 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:45:26.184  3309  3309 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-16 13:45:26.184  3309  3309 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-16 13:45:26.185  3309  3309 I LgeMiscReceiver: networkInfo.isConnected() = true
08-16 13:45:26.185  3309  3309 D PhoneState: setPdpRejectCasuse : false
,08-16 13:45:26.213   308  8609 D libc-netbsd: res_queryN name = static-avc.lglime.com succeed
,08-16 13:45:26.232  1036  1995 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=8616 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-16 13:45:26.386  8616  8616 D LgDataFeature: LgDataFeature() Constructor: none
08-16 13:45:26.386  8616  8616 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 13:45:26.394  8616  8616 D PhoneMonitor: Register our PhoneStateListener
08-16 13:45:26.418  8616  8616 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-16 13:45:26.421  8616  8616 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-16 13:45:26.440  8616  8616 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
08-16 13:45:26.493  1036  1958 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=8641 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-16 13:45:26.494  1036  1958 I ActivityManager: Killing 8029:com.android.contacts/u0a19 (adj 15): empty #17
08-16 13:45:26.551  1036  1051 W libprocessgroup: failed to open /acct/uid_10019/pid_8029/cgroup.procs: No such file or directory
,08-16 13:45:26.553  8616  8616 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-16 13:45:26.554  8616  8616 D TelephonyAutoProfiling: [parse] Load xml
08-16 13:45:26.557  8616  8616 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-16 13:45:26.557  8616  8616 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-16 13:45:26.557  8616  8616 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-16 13:45:26.557  8616  8616 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-16 13:45:26.557  8616  8616 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-16 13:45:26.557  8616  8616 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-16 13:45:26.557  8616  8616 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-16 13:45:26.557  8616  8616 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-16 13:45:26.557  8616  8616 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-16 13:45:26.557  8616  8616 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-16 13:45:26.557  8616  8616 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-16 13:45:26.557  8616  8616 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-16 13:45:26.557  8616  8616 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-16 13:45:26.557  8616  8616 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-16 13:45:26.558  8616  8616 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-16 13:45:26.558  8616  8616 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-16 13:45:26.558  8616  8616 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
08-16 13:45:26.566  8616  8616 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,08-16 13:45:26.604  1816  8662 I CheckinService: active receiver: enabled
08-16 13:45:26.612   308  8663 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-16 13:45:26.612   308  8663 D libc-netbsd: res_queryN name = www.google.com, class = 1, type = 1
08-16 13:45:26.620  1816  8662 I CheckinService: Preparing to send checkin request
08-16 13:45:26.620  1816  8662 I EventLogService: Accumulating logs since 1471347923159
,08-16 13:45:26.643   308  8663 D libc-netbsd: res_queryN name = www.google.com succeed
,08-16 13:45:26.648   308  8667 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-16 13:45:26.648   308  8667 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-16 13:45:26.648   308  8667 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-16 13:45:26.661  1816  8662 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-16 13:45:26.691  8363  8606 V FormManager: There are no updated forms. The schedule will be deleted.
,08-16 13:45:26.695  8363  8606 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
08-16 13:45:26.708  1036  1540 V WifiInternetCheck: isHttpConnectionAvailable - We got a valid response : 204
,08-16 13:45:26.752  1036  1922 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=8672 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
08-16 13:45:26.753  1036  1922 I ActivityManager: Killing 8049:com.android.gallery3d/u0a27 (adj 15): empty #17
,08-16 13:45:26.801  1036  1922 I ActivityManager: Killing 8074:com.android.vending/u0a44 (adj 15): empty #17
,08-16 13:45:26.933  1036  2033 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=8691 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-16 13:45:26.934  1036  1903 W libprocessgroup: failed to open /acct/uid_10027/pid_8049/cgroup.procs: No such file or directory
,08-16 13:45:26.945  1036  1052 W libprocessgroup: failed to open /acct/uid_10044/pid_8074/cgroup.procs: No such file or directory
,08-16 13:45:27.011  8691  8691 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-16 13:45:27.011  8691  8691 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-16 13:45:27.035  8691  8691 I MultiDex: VM with version 2.1.0 has multidex support
08-16 13:45:27.035  8691  8691 I MultiDex: install
08-16 13:45:27.035  8691  8691 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-16 13:45:27.042  1036  1940 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=8708 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-16 13:45:27.043  1036  1940 I ActivityManager: Killing 8112:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
08-16 13:45:27.090  1036  2032 W libprocessgroup: failed to open /acct/uid_10080/pid_8112/cgroup.procs: No such file or directory
,08-16 13:45:27.102  8691  8691 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,08-16 13:45:27.135  8708  8708 I art     : Almond Protected OAT
,08-16 13:45:27.195  8708  8708 D WeatherApplication: removeAccount
,08-16 13:45:27.198  8708  8708 D WeatherApplication: Account.length = 0
08-16 13:45:27.199  8708  8708 E WeatherApplication: OPERATOR:OPEN
08-16 13:45:27.211  8708  8708 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:45:27
,08-16 13:45:27.216  8708  8708 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-16 13:45:27.217  8708  8708 D Weather.Utils: 2 : All the weather widget is gone.
08-16 13:45:27.219  8708  8708 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-16 13:45:27.222  8708  8708 D WeatherAncestor: connectivity changed - connection : true
08-16 13:45:27.223  8708  8708 D WeatherService: 2 : isServiceAlived():false forecastCache:null
08-16 13:45:27.237  8708  8708 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
,08-16 13:45:27.238  8708  8708 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-16 13:45:27.238  8708  8708 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
08-16 13:45:27.271  8708  8708 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-16 13:45:27.272  8708  8708 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:45:27
,08-16 13:45:27.322  1036  1904 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=8730 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-16 13:45:27.322  1036  1904 I ActivityManager: Killing 7564:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,08-16 13:45:27.339  1036  1093 W ProcessCpuTracker: Skipping unknown process pid 8669
,08-16 13:45:27.340  1036  1093 W ProcessCpuTracker: Skipping unknown process pid 8670
08-16 13:45:27.341  1036  1093 W ProcessCpuTracker: Skipping unknown process pid 8678
08-16 13:45:27.341  1036  1093 W ProcessCpuTracker: Skipping unknown process pid 8690
08-16 13:45:27.343  1036  1093 W ProcessCpuTracker: Skipping unknown process pid 8727
08-16 13:45:27.370  1036  1940 W libprocessgroup: failed to open /acct/uid_10097/pid_7564/cgroup.procs: No such file or directory
,08-16 13:45:27.455   278   371 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,08-16 13:45:27.455   278   371 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-16 13:45:27.455   278   371 W Vold    : Returning OperationFailed - no handler for errno 0
08-16 13:45:27.456  8730  8753 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,08-16 13:45:27.462   278   371 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-16 13:45:27.462   278   371 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-16 13:45:27.462   278   371 W Vold    : Returning OperationFailed - no handler for errno 0
08-16 13:45:27.470  8730  8753 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-16 13:45:27.475   278   371 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,08-16 13:45:27.475   278   371 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-16 13:45:27.475   278   371 W Vold    : Returning OperationFailed - no handler for errno 0
08-16 13:45:27.475  8730  8757 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-16 13:45:27.477   278   371 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-16 13:45:27.478   278   371 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
,08-16 13:45:27.478   278   371 W Vold    : Returning OperationFailed - no handler for errno 0
08-16 13:45:27.478  8730  8757 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-16 13:45:27.589  8691  8707 D LgDataFeature: LgDataFeature() Constructor: none
,08-16 13:45:27.589  8691  8707 D LgDataFeature: LgDataFeature() Constructor Done, null
08-16 13:45:27.650  8772  8772 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-16 13:45:27.671  8730  8730 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-16 13:45:27.690  8730  8730 I LibraryLoader: Loading: webviewchromium
,08-16 13:45:27.698  8730  8730 I LibraryLoader: Time to load native libraries: 10 ms (timestamps 4368-4378)
08-16 13:45:27.698  8730  8730 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 13:45:27.701  8772  8772 I dex2oat : dex2oat took 51.402ms (threads: 4)
,08-16 13:45:27.704  8730  8730 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {26495192}
08-16 13:45:27.705  8730  8730 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 13:45:27.705  8730  8730 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-16 13:45:27.711  8730  8730 I BrowserStartupController: Initializing chromium process, renderers=0
08-16 13:45:27.712  8730  8730 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-16 13:45:27.721  8730  8730 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-16 13:45:27.721  8691  8707 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 13:45:27.721  8691  8707 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 13:45:27.721  8691  8707 I Adreno-EGL: Build Date: 12/12/14 금
08-16 13:45:27.721  8691  8707 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 13:45:27.721  8691  8707 I Adreno-EGL: Remote Branch: 
08-16 13:45:27.721  8691  8707 I Adreno-EGL: Local Patches: 
08-16 13:45:27.721  8691  8707 I Adreno-EGL: Reconstruct Branch: 
08-16 13:45:27.721  8730  8730 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-16 13:45:27.721  8730  8730 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-16 13:45:27.723   312  2154 V AudioPolicyService: registerClient() client 0xb0403d20, uid 10093
,08-16 13:45:27.724  8730  8784 W AudioManagerAndroid: Requires BLUETOOTH permission
08-16 13:45:27.733  8730  8730 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 13:45:27.733  8730  8730 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 13:45:27.733  8730  8730 I Adreno-EGL: Build Date: 12/12/14 금
08-16 13:45:27.733  8730  8730 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 13:45:27.733  8730  8730 I Adreno-EGL: Remote Branch: 
08-16 13:45:27.733  8730  8730 I Adreno-EGL: Local Patches: 
08-16 13:45:27.733  8730  8730 I Adreno-EGL: Reconstruct Branch: 
,08-16 13:45:27.811  8730  8730 I NSApplication: Starting up...
,08-16 13:45:27.865  8691  8707 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 13:45:27.865  8691  8707 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 13:45:27.865  8691  8707 I Adreno-EGL: Build Date: 12/12/14 금
08-16 13:45:27.865  8691  8707 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 13:45:27.865  8691  8707 I Adreno-EGL: Remote Branch: 
08-16 13:45:27.865  8691  8707 I Adreno-EGL: Local Patches: 
08-16 13:45:27.865  8691  8707 I Adreno-EGL: Reconstruct Branch: 
,08-16 13:45:27.881  1036  1755 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=8798 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-16 13:45:27.883  1036  1755 I ActivityManager: Killing 7837:com.lge.lifetracker/u0a37 (adj 15): empty #17
,08-16 13:45:27.920  8691  8707 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 13:45:27.920  8691  8707 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 13:45:27.920  8691  8707 I Adreno-EGL: Build Date: 12/12/14 금
08-16 13:45:27.920  8691  8707 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 13:45:27.920  8691  8707 I Adreno-EGL: Remote Branch: 
08-16 13:45:27.920  8691  8707 I Adreno-EGL: Local Patches: 
08-16 13:45:27.920  8691  8707 I Adreno-EGL: Reconstruct Branch: 
,08-16 13:45:27.964  1036  1904 W libprocessgroup: failed to open /acct/uid_10037/pid_7837/cgroup.procs: No such file or directory
,08-16 13:45:28.026  8798  8798 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-16 13:45:28.272  2175  2175 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,08-16 13:45:28.282  2175  2175 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
08-16 13:45:28.282  2175  2175 D c       : Getting all permits...
08-16 13:45:28.282  2175  2175 D a       : Opening database...
08-16 13:45:28.287   308  8827 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-16 13:45:28.287   308  8827 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
08-16 13:45:28.287  2175  2175 D a       : Opening database auth.proximity.permit_store...
,08-16 13:45:28.288  2175  2175 D a       : Closing database...
,08-16 13:45:28.334   308  8827 D libc-netbsd: res_queryN name = android.clients.google.com succeed
08-16 13:45:28.398  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-52 f=2447 sc=60 link=72 tx=61.2, 0.0, 0.0  rx=55.5 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1825854130] gl rssi=-52 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-16 13:45:28.403  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-52 f=2447 sc=60 link=72 tx=61.2, 0.0, 0.0  rx=55.5 bcn=0 [on:0 tx:0 rx:0 period:5] from screen [on:0 period:-1825854125] gl rssi=-52 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 13:45:28.403  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-16 13:45:28.468  1036  2032 I art     : Explicit concurrent mark sweep GC freed 47018(2MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/64MB, paused 2.523ms total 141.359ms
,08-16 13:45:28.530  1816  8662 I CheckinTask: Sending checkin request (7901 bytes)
,08-16 13:45:28.781  1816  8662 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,08-16 13:45:28.788  1816  8662 I CheckinService: active receiver: disabled
,08-16 13:45:28.818  2175  2175 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
08-16 13:45:28.833  2175  2175 I GCM     : GCM config loaded
,08-16 13:45:28.841   308  8839 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-16 13:45:28.841   308  8839 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
08-16 13:45:28.841   308  8839 D libc-netbsd: res_queryN name = mtalk.google.com succeed
08-16 13:45:28.852  8616  8616 V SetupWizard: Connected to Gservices successfully
,08-16 13:45:29.059  1036  1382 V AlarmManager: ELAPSED_WAKEUP set : Alarm{373fd038 type 2 when 425725 com.google.android.gms} when 425725
,08-16 13:45:29.129  2175  8842 D GCM     : Connected
,08-16 13:45:29.155  2175  8842 D GCM     : Message class com.google.e.a.a.q
08-16 13:45:30.564  6936  8847 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
08-16 13:45:30.565  6936  8847 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-16 13:45:31.416  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-55 f=2447 sc=60 link=72 tx=40.6, 0.0, 0.0  rx=34.2 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1825851112] gl rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-16 13:45:31.426  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-55 f=2447 sc=60 link=72 tx=40.6, 0.0, 0.0  rx=34.2 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1825851103] gl rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 13:45:31.426  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-16 13:45:32.014  1036  1538 E WifiStateMachine:  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-16 13:45:32.015  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-16 13:45:32.015  1036  1538 E WifiStateMachine:  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-16 13:45:32.016  1036  1538 E WifiStateMachine:  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-16 13:45:32.016  1036  1538 E WifiStateMachine:  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-16 13:45:32.016  1036  1538 E WifiStateMachine:  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,08-16 13:45:32.332  1603  1603 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-16 13:45:32.332  1603  1603 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-16 13:45:32.351  1036  1543 D WifiController: battery changed pluggedType: 2
,08-16 13:45:32.354  1603  1603 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 286,
08-16 13:45:32.355  1941  2109 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-16 13:45:32.355  1941  2109 D LEDHandler: Battery Level Remaining: 100%
08-16 13:45:32.355  1941  2109 D LEDHandler: Battery Temp: 286, mChargingStatus=5, mChargingStop=false
08-16 13:45:32.357  1603  1603 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-16 13:45:32.359  1603  1603 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-16 13:45:32.362  8183  8237 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-16 13:45:32.362  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:45:32.362  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:45:32.367  8412  8412 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-16 13:45:32.487  8730  8755 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,08-16 13:45:33.282  1036  1885 I ActivityManager: Killing 7881:com.lge.settings.easy/1000 (adj 15): empty #17
,08-16 13:45:33.316  1036  1755 W libprocessgroup: failed to open /acct/uid_1000/pid_7881/cgroup.procs: No such file or directory
,08-16 13:45:33.325  1036  2032 I ActivityManager: Killing 8412:com.lge.bnr/1000 (adj 15): empty #17
,08-16 13:45:33.364  1036  1958 W libprocessgroup: failed to open /acct/uid_1000/pid_8412/cgroup.procs: No such file or directory
,08-16 13:45:33.562  6936  8847 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
08-16 13:45:33.562  6936  8847 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-16 13:45:33.563  6936  8847 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 13:45:33.563  6936  8847 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 13:45:33.563  6936  8847 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,08-16 13:45:33.568  6936  8850 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
08-16 13:45:33.568  6936  8850 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-16 13:45:33.568  6936  8850 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 13:45:33.570  6936  8850 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 13:45:33.571  6936  8853 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 908, name: OutgoingSocketThread/Receiver)
08-16 13:45:33.572  6936  8853 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 908, thread name: OutgoingSocketThread/Receiver)
08-16 13:45:33.572  6936  8853 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-16 13:45:33.572  6936  8853 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 908, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
08-16 13:45:33.574  6936  8852 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 907, name: OutgoingSocketThread/Sender)
08-16 13:45:33.575  6936  8850 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
08-16 13:45:33.577  6936  8854 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 909, name: IncomingSocketThread/Sender)
08-16 13:45:33.579  6936  8855 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 910, name: IncomingSocketThread/Receiver)
,08-16 13:45:33.582  6936  8855 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 910, thread name: IncomingSocketThread/Receiver)
08-16 13:45:33.582  6936  8855 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,08-16 13:45:33.582  6936  8855 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 910, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,08-16 13:45:34.448  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-55 f=2447 sc=60 link=72 tx=31.3, 0.0, 0.0  rx=27.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1825848081] gl rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-16 13:45:34.464  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-55 f=2447 sc=60 link=72 tx=31.3, 0.0, 0.0  rx=27.1 bcn=0 [on:0 tx:0 rx:0 period:17] from screen [on:0 period:-1825848064] gl rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 13:45:34.464  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-16 13:45:36.684  1603  1603 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-16 13:45:36.723  1036  1441 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-16 13:45:36.769   341   341 I art     : Background concurrent mark sweep GC freed 788(33KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 5.474ms total 38.224ms
,08-16 13:45:36.798  1036  1093 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=8856 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-16 13:45:36.805  1603  1603 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
08-16 13:45:36.805  1603  1603 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,08-16 13:45:36.807  2034  2034 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
08-16 13:45:36.832  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-16 13:45:36.842  1036  1036 D administrator: Handling package changes for user 0
,08-16 13:45:36.908  8856  8856 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-16 13:45:36.946  1036  1036 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-16 13:45:36.946  1036  1036 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-16 13:45:36.985  8856  8856 D LgDataFeature: LgDataFeature() Constructor: none
,08-16 13:45:36.985  8856  8856 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 13:45:37.013  1036  1092 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-16 13:45:37.020  1036  1092 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-16 13:45:37.027  2034  2034 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-16 13:45:37.029  2474  2474 V GmsNetworkLocationProvi: DISABLE
,08-16 13:45:37.064  1036  1092 D LocationProviderProxy: applying state to connected service
08-16 13:45:37.065  2474  2474 E GCoreFlp: Bound FusedProviderService with LocationManager
,08-16 13:45:37.114  8856  8901 I Babel   : MmsConfig: mnc/mcc: 0/0
08-16 13:45:37.114  8856  8901 I Babel   : MmsConfig.loadMmsSettings
08-16 13:45:37.126  8856  8901 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-16 13:45:37.127  8856  8901 I Babel   : MmsConfig.loadFromDatabase
,08-16 13:45:37.147  8856  8901 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-16 13:45:37.147  8856  8901 I Babel   : MmsConfig.loadFromResources
08-16 13:45:37.151  8856  8901 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-16 13:45:37.151  8856  8901 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,08-16 13:45:37.166  8856  8856 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:45:37.170  8856  8899 W AudioCapabilities: Unsupported mime audio/evrc
08-16 13:45:37.171  8856  8899 W AudioCapabilities: Unsupported mime audio/qcelp
08-16 13:45:37.172  8856  8899 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-16 13:45:37.183  8856  8899 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
08-16 13:45:37.184  8856  8899 W AudioCapabilities: Unsupported mime audio/qcelp
,08-16 13:45:37.186  8856  8899 W AudioCapabilities: Unsupported mime audio/evrc
08-16 13:45:37.204  7309  7309 I AppUp4:CustModeStarterReceiver: onReceive
08-16 13:45:37.206  1816  8904 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,08-16 13:45:37.206  1816  8904 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
08-16 13:45:37.210  7309  7309 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@166647fb
08-16 13:45:37.210  7309  7309 D AppUp4:CustFacade: isCustomizationCompleted : false
08-16 13:45:37.210  7309  7309 D AppUp4:CustFacade: isPhone : true
08-16 13:45:37.211  7309  7309 D AppUp4:CustModeStarterReceiver: begin check event
08-16 13:45:37.211  7309  7309 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-16 13:45:37.215  8856  8899 W VideoCapabilities: Unsupported mime video/x-ms-wmv
08-16 13:45:37.216  1816  5159 I Icing   : updateResources: need to parse e{com.google.android.gms}
,08-16 13:45:37.219  8856  8899 W VideoCapabilities: Unsupported mime video/divx
08-16 13:45:37.223  8856  8899 W VideoCapabilities: Unsupported mime video/divx311
08-16 13:45:37.224  8856  8899 W VideoCapabilities: Unsupported mime video/divx4
08-16 13:45:37.228  8856  8899 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-16 13:45:37.248  8856  8899 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
08-16 13:45:37.248  1036  2032 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=8907 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
08-16 13:45:37.252  1036  2032 I ActivityManager: Killing 8516:com.lge.clock/u0a10 (adj 15): empty #17
08-16 13:45:37.253  8856  8899 W AudioCapabilities: Unsupported mime audio/eac3
08-16 13:45:37.254  8856  8899 W AudioCapabilities: Unsupported mime audio/ac3
08-16 13:45:37.255  8856  8899 W AudioCapabilities: Unsupported mime audio/g726
08-16 13:45:37.257  8856  8899 W AudioCapabilities: Unsupported mime audio/wma-voice
,08-16 13:45:37.272   341   341 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 588us total 24.573ms
08-16 13:45:37.275  8856  8899 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-16 13:45:37.275  8856  8899 W AudioCapabilities: Unsupported mime audio/adpcm
08-16 13:45:37.277  8856  8899 W VideoCapabilities: Unsupported mime video/theora
08-16 13:45:37.278  8856  8899 W VideoCapabilities: Unsupported mime video/mjpg
08-16 13:45:37.293   341   341 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 399us total 19.669ms
,08-16 13:45:37.313   341   341 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 407us total 18.713ms
,08-16 13:45:37.320  1036  1904 W libprocessgroup: failed to open /acct/uid_10010/pid_8516/cgroup.procs: No such file or directory
08-16 13:45:37.346  8907  8907 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-16 13:45:37.347  8907  8907 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 13:45:37.347  8907  8907 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-16 13:45:37.349  8907  8907 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-16 13:45:37.349  8907  8907 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-16 13:45:37.407  8907  8907 I SystemConfig: BUILD Country: EU
08-16 13:45:37.407  8907  8907 I SystemConfig: BUILD Operator: OPEN
,08-16 13:45:37.446  1036  1940 I ActivityManager: Killing 8385:com.lge.sync/1000 (adj 15): empty #17
,08-16 13:45:37.481  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-55 f=2447 sc=60 link=72 tx=16.2, 0.0, 0.0  rx=13.6 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1825845047] gl rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 13:45:37.482  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-55 f=2447 sc=60 link=72 tx=16.2, 0.0, 0.0  rx=13.6 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1825845046] gl rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 13:45:37.482  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-16 13:45:37.512  1036  2032 W libprocessgroup: failed to open /acct/uid_1000/pid_8385/cgroup.procs: No such file or directory
,08-16 13:45:37.520  8907  8925 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-16 13:45:37.520  8907  8925 I SystemConfig: existFile = false
08-16 13:45:37.520  8907  8925 I SystemConfig: canReadFile = false
08-16 13:45:37.520  8907  8925 I SystemConfig: systemFeature RCS result false
08-16 13:45:37.521  8907  8925 D SystemConfig: refreshRcsSupport() :false
08-16 13:45:37.590  1036  1903 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=8927 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-16 13:45:37.660  8927  8927 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 13:45:37.661  8927  8927 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-16 13:45:37.661  8927  8927 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-16 13:45:37.661  8927  8927 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-16 13:45:37.762  8927  8927 I AppConfig: Total System Memory = 2995761152
,08-16 13:45:37.773  8927  8927 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
08-16 13:45:37.883  1036  1885 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8946 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-16 13:45:37.894  1036  1885 I ActivityManager: Killing 6798:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
08-16 13:45:37.928  7150  7150 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-16 13:45:37.928  7150  7150 W System.err: android.os.DeadObjectException
08-16 13:45:37.928  7150  7150 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-16 13:45:37.928  7150  7150 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-16 13:45:37.928  7150  7150 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-16 13:45:37.928  7150  7150 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
,08-16 13:45:37.929  7150  7150 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-16 13:45:37.929  7150  7150 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-16 13:45:37.929  7150  7150 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-16 13:45:37.929  7150  7150 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 13:45:37.929  7150  7150 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-16 13:45:37.929  7150  7150 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-16 13:45:37.929  7150  7150 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 13:45:37.929  7150  7150 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 13:45:37.929  7150  7150 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-16 13:45:37.929  7150  7150 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-16 13:45:37.929  7150  7150 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-16 13:45:37.930  7150  7150 W System.err: android.os.DeadObjectException
08-16 13:45:37.930  7150  7150 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-16 13:45:37.930  7150  7150 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-16 13:45:37.930  7150  7150 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-16 13:45:37.930  7150  7150 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-16 13:45:37.930  7150  7150 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-16 13:45:37.930  7150  7150 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-16 13:45:37.930  7150  7150 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-16 13:45:37.930  7150  7150 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 13:45:37.930  7150  7150 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-16 13:45:37.930  7150  7150 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-16 13:45:37.930  7150  7150 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 13:45:37.930  7150  7150 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 13:45:37.930  7150  7150 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-16 13:45:37.930  7150  7150 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-16 13:45:37.931  7150  7150 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-16 13:45:37.931  7150  7150 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-16 13:45:38.006  1036  1958 W libprocessgroup: failed to open /acct/uid_1000/pid_6798/cgroup.procs: No such file or directory
08-16 13:45:38.007  1036  1958 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-16 13:45:38.023  7150  7150 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-16 13:45:38.024  7150  7150 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-16 13:45:38.107  1036  1575 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=8967 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-16 13:45:38.108  7150  7150 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-16 13:45:38.193  8967  8967 D UEI.SmartControl: Quickset Services start...
,08-16 13:45:38.195  8967  8967 I UEI.SmartControl: Manufacture = LGE
08-16 13:45:38.196  8967  8967 D UEI.SmartControl: Id = LGNevo
08-16 13:45:38.198  8967  8967 D UEI.SmartControl: File observer start...
08-16 13:45:38.199  8967  8967 E UEI.SmartControl: IR Port is disabled: false
08-16 13:45:38.199  8967  8967 D UEI.SmartControl: Starting file observer...
08-16 13:45:38.200  8967  8967 D UEI.SmartControl: Extracting JNI libs...
08-16 13:45:38.200  8967  8967 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-16 13:45:38.243  8946  8946 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-16 13:45:38.303  8967  8967 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-16 13:45:38.303  8967  8967 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-16 13:45:38.303  8967  8967 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-16 13:45:38.335  8946  8946 D LgDataFeature: LgDataFeature() Constructor: none
,08-16 13:45:38.335  8946  8946 D LgDataFeature: LgDataFeature() Constructor Done, null
08-16 13:45:38.345  8967  8967 I UEI.SmartControl: --- Selecting new region: 6
08-16 13:45:38.348  8967  8967 I UEI.SmartControl: Model = LG-D855
,08-16 13:45:38.350  8967  8967 D UEI.SmartControl: QS Service created
08-16 13:45:38.367  8967  8967 I UEI.SmartControl: Service initServices...
,08-16 13:45:38.373  8967  8967 D UEI.SmartControl: QS start get config
08-16 13:45:38.387  8946  8946 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-16 13:45:38.407  8946  8946 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-16 13:45:38.412  8946  8946 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-16 13:45:38.428  8967  8967 D UEI.SmartControl: Loading JNI Libs...
,08-16 13:45:38.435  8946  8946 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-16 13:45:38.436  8946  8946 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
08-16 13:45:38.457  1036  1646 I ActivityManager: Killing 7122:com.android.settings/1000 (adj 15): empty #17
,08-16 13:45:38.552  1036  1903 W libprocessgroup: failed to open /acct/uid_1000/pid_7122/cgroup.procs: No such file or directory
,08-16 13:45:38.583  4997  9004 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,08-16 13:45:38.584  2851  3085 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,08-16 13:45:38.588  2851  3085 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@16b10466 on behalf of 8946
08-16 13:45:38.636  1036  1904 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=9005 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-16 13:45:38.668  8946  8946 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-16 13:45:38.701  8946  8946 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
08-16 13:45:38.717  9005  9005 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-16 13:45:38.718  8967  8967 I UEI.SmartControl: Supports setup maps: true
08-16 13:45:38.726  8967  8967 D UEI.SmartControl: QS start statue = true Error code = 0
08-16 13:45:38.726  8967  8967 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-16 13:45:38.726  8967  8967 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-16 13:45:38.727  8967  8967 I UEI.SmartControl: ### init IR Blaster...
08-16 13:45:38.729  9005  9005 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-16 13:45:38.729  9005  9005 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
,08-16 13:45:38.729  9005  9005 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-16 13:45:38.729  9005  9005 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-16 13:45:38.729  9005  9005 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-16 13:45:38.729  9005  9005 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,08-16 13:45:38.733  8967  8967 D serial_port: Configuring serial port
08-16 13:45:38.740  8967  8967 E UEI.SmartControl: UEIBLaster setting for 616
08-16 13:45:38.740  8967  8967 I UEI.SmartControl: Setting serial record hearder size = 2
08-16 13:45:38.740  8967  8967 I UEI.SmartControl: configuring settings for MAXQ616
08-16 13:45:38.740  8967  8967 I UEI.SmartControl: Get version...
08-16 13:45:38.747  1036  1885 I ActivityManager: Killing 7150:com.lge.qremote/u0a112 (adj 15): empty #17
,08-16 13:45:38.756  8967  9025 D UEI.SmartControl: serial port data available: 21
,08-16 13:45:38.770  1036  1940 W libprocessgroup: failed to open /acct/uid_10112/pid_7150/cgroup.procs: No such file or directory
,08-16 13:45:38.783  8967  8967 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-16 13:45:38.783  8967  8967 I UEI.SmartControl: IR Blaster version: 256702256704300002
,08-16 13:45:38.783  8967  8967 I UEI.SmartControl: QS saving settings...
,08-16 13:45:38.784  8967  8967 D UEI.SmartControl: IR Blaster version: 25672567
08-16 13:45:38.799  8967  9025 D UEI.SmartControl: serial port data available: 4
,08-16 13:45:38.831  8967  9035 I UEI.SmartControl: Device manager: loading config....
,08-16 13:45:38.831  8967  9035 D UEI.SmartControl: ----------- loading internal config...
08-16 13:45:38.834  8967  8967 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-16 13:45:38.839  8967  8967 E UEI.SmartControl: Services init done
08-16 13:45:38.840  8967  8967 D UEI.SmartControl: QS Service init finished
08-16 13:45:38.841  8967  8967 D UEI.SmartControl: QS Service version name: 2.1.91
08-16 13:45:38.841  8967  8967 D UEI.SmartControl: QS Service version code: 201091
08-16 13:45:38.842  8967  8967 D UEI.SmartControl: Service requested: Control
,08-16 13:45:38.851  8967  9035 E UEI.SmartControl: Loading SETTINGS...
08-16 13:45:38.857  8967  8967 D UEI.SmartControl: Request IControl service: devices are loaded...
08-16 13:45:38.858  8967  8967 D UEI.SmartControl: Service.onUnbind: IControl
08-16 13:45:38.858  8967  8967 D UEI.SmartControl: Service.onDestroy
08-16 13:45:38.858  8967  8967 D UEI.SmartControl: Lock is in USE false
08-16 13:45:38.858  8967  8967 D UEI.SmartControl: unbind internal service
,08-16 13:45:38.860  8967  8967 D serial_port: close(fd = 25)
08-16 13:45:38.862  8967  9035 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-16 13:45:38.865  8967  8967 I UEI.SmartControl: Serial port is closed.
08-16 13:45:38.865  8967  8967 I UEI.SmartControl: Serial port is closed.
08-16 13:45:38.865  8967  8967 D UEI.SmartControl: Blaster closed
08-16 13:45:38.865  8967  8967 D UEI.SmartControl: Shut down QS...
08-16 13:45:38.865  8967  8967 D UEI.SmartControl: Stopping QS lib
08-16 13:45:38.865  8967  8967 D UEI.SmartControl: QS lib stop result = true
08-16 13:45:38.865  8967  8967 D UEI.SmartControl: Stopped QS lib
08-16 13:45:38.867  8967  8967 D UEI.SmartControl: Stopped file observer...
,08-16 13:45:38.867  8967  8967 D UEI.SmartControl: QS shutdown complete
08-16 13:45:38.868  8967  8967 D UEI.SmartControl: QS Service created
08-16 13:45:38.869  8967  9034 I UEI.SmartControl: Notify AllClients services are ready: 11
08-16 13:45:38.870  8967  9034 D UEI.SmartControl: -----service ready thread exits
08-16 13:45:38.884  1036  1940 V SIM_STK : Menu title from STK is T-Mobile
08-16 13:45:38.885  8967  8967 I UEI.SmartControl: Service initServices...
08-16 13:45:38.885  8967  8967 D UEI.SmartControl: QS start get config
,08-16 13:45:38.895  4997  9004 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 312 ms] updated apps [took 312 ms] 
08-16 13:45:39.317  8967  8967 I UEI.SmartControl: Supports setup maps: true
,08-16 13:45:39.326  8967  8967 D UEI.SmartControl: QS start statue = true Error code = 0
08-16 13:45:39.326  8967  8967 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-16 13:45:39.326  8967  8967 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-16 13:45:39.326  8967  8967 I UEI.SmartControl: ### init IR Blaster...
08-16 13:45:39.330  8967  8967 D serial_port: Configuring serial port
08-16 13:45:39.331  8967  8967 E UEI.SmartControl: UEIBLaster setting for 616
08-16 13:45:39.331  8967  8967 I UEI.SmartControl: Setting serial record hearder size = 2
08-16 13:45:39.331  8967  8967 I UEI.SmartControl: configuring settings for MAXQ616
08-16 13:45:39.331  8967  8967 I UEI.SmartControl: Get version...
08-16 13:45:39.348  8967  9047 D UEI.SmartControl: serial port data available: 21
,08-16 13:45:39.377  8967  8967 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-16 13:45:39.377  8967  8967 I UEI.SmartControl: IR Blaster version: 256702256704300002
,08-16 13:45:39.377  8967  8967 I UEI.SmartControl: QS saving settings...
,08-16 13:45:39.391  8967  8967 D UEI.SmartControl: IR Blaster version: 25672567
,08-16 13:45:39.408  8967  9047 D UEI.SmartControl: serial port data available: 4
,08-16 13:45:39.444  8967  8967 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-16 13:45:39.458  8967  9050 I UEI.SmartControl: Device manager: loading config....
08-16 13:45:39.459  8967  9050 D UEI.SmartControl: ----------- loading internal config...
08-16 13:45:39.463  8967  8967 E UEI.SmartControl: Services init done
08-16 13:45:39.463  8967  8967 D UEI.SmartControl: QS Service init finished
,08-16 13:45:39.467  8967  8967 D UEI.SmartControl: QS Service version name: 2.1.91
08-16 13:45:39.467  8967  8967 D UEI.SmartControl: QS Service version code: 201091
08-16 13:45:39.468  8967  8967 D UEI.SmartControl: Service requested: Control
08-16 13:45:39.472  8967  9050 E UEI.SmartControl: Loading SETTINGS...
08-16 13:45:39.473  8967  8967 D UEI.SmartControl: Request IControl service: devices are loaded...
08-16 13:45:39.477  1036  1995 I ActivityManager: Killing 8576:com.lge.email/u0a23 (adj 15): empty #17
,08-16 13:45:39.492  8967  9050 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-16 13:45:39.503  8967  9049 I UEI.SmartControl: Notify AllClients services are ready: 0
08-16 13:45:39.503  8967  9049 D UEI.SmartControl: -----service ready thread exits
,08-16 13:45:39.537  1036  1646 W libprocessgroup: failed to open /acct/uid_10023/pid_8576/cgroup.procs: No such file or directory
,08-16 13:45:39.553  8967  8967 E ActivityThread: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@1ac768d7 that was originally bound here
08-16 13:45:39.553  8967  8967 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@1ac768d7 that was originally bound here
08-16 13:45:39.553  8967  8967 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1167)
08-16 13:45:39.553  8967  8967 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1061)
08-16 13:45:39.553  8967  8967 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1839)
08-16 13:45:39.553  8967  8967 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1822)
08-16 13:45:39.553  8967  8967 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
08-16 13:45:39.553  8967  8967 E ActivityThread: 	at com.uei.control.Service.b(Unknown Source)
08-16 13:45:39.553  8967  8967 E ActivityThread: 	at com.uei.control.Service.a(Unknown Source)
08-16 13:45:39.553  8967  8967 E ActivityThread: 	at com.uei.control.Service.onCreate(Unknown Source)
08-16 13:45:39.553  8967  8967 E ActivityThread: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2738)
08-16 13:45:39.553  8967  8967 E ActivityThread: 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
08-16 13:45:39.553  8967  8967 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
08-16 13:45:39.553  8967  8967 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 13:45:39.553  8967  8967 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
08-16 13:45:39.553  8967  8967 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-16 13:45:39.553  8967  8967 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 13:45:39.553  8967  8967 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 13:45:39.553  8967  8967 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-16 13:45:39.553  8967  8967 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-16 13:45:39.561  8967  8967 D UEI.SmartControl: Internal service binding...
,08-16 13:45:39.859  8967  9037 D UEI.SmartControl: Internal timer expired: 2
,08-16 13:45:40.501  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-55 f=2447 sc=60 link=72 tx=8.1, 0.0, 0.0  rx=6.8 bcn=0 [on:0 tx:0 rx:0 period:3007] from screen [on:0 period:-1825842027] gl rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 13:45:40.504  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-55 f=2447 sc=60 link=72 tx=8.1, 0.0, 0.0  rx=6.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1825842024] gl rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 13:45:40.505  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-16 13:45:41.574  6936  6997 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-16 13:45:41.577  6936  6997 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-16 13:45:41.592  6936  6997 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1e948465 Bundle[{}]
,08-16 13:45:41.593  6936  6997 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-16 13:45:41.593  6936  6997 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-16 13:45:41.594  6936  6997 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-16 13:45:41.595  6936  6997 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-16 13:45:41.595  6936  6997 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed,
08-16 13:45:41.596  6936  6997 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-16 13:45:42.089  2175  2195 W art     : Suspending all threads took: 8.879ms
,08-16 13:45:43.199  8967  8978 E UEI.SmartControl: file observer is disposed!
,08-16 13:45:43.528  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-55 f=2447 sc=60 link=72 tx=4.0, 0.0, 0.0  rx=3.4 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:-1825839000] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-16 13:45:43.538  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-55 f=2447 sc=60 link=72 tx=4.0, 0.0, 0.0  rx=3.4 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1825838990] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-16 13:45:43.538  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-16 13:45:44.443  8967  9051 D UEI.SmartControl: Internal timer expired: 3
08-16 13:45:44.443  8967  9051 D UEI.SmartControl: unbind internal service
,08-16 13:45:44.463  8967  8967 D UEI.SmartControl: Service.onUnbind: IControl
,08-16 13:45:44.466  8967  8967 D UEI.SmartControl: Service.onDestroy
,08-16 13:45:44.466  8967  8967 D UEI.SmartControl: Lock is in USE false
,08-16 13:45:44.466  8967  8967 D UEI.SmartControl: unbind internal service
,08-16 13:45:44.466  8967  8967 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@d13242e
08-16 13:45:44.468  8967  8967 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
08-16 13:45:44.468  8967  8967 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
08-16 13:45:44.468  8967  8967 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
,08-16 13:45:44.468  8967  8967 W System.err: 	at com.uei.control.Service.c(Unknown Source)
08-16 13:45:44.468  8967  8967 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
08-16 13:45:44.468  8967  8967 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
08-16 13:45:44.468  8967  8967 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
08-16 13:45:44.468  8967  8967 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
08-16 13:45:44.468  8967  8967 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 13:45:44.468  8967  8967 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-16 13:45:44.468  8967  8967 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-16 13:45:44.468  8967  8967 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 13:45:44.468  8967  8967 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 13:45:44.468  8967  8967 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-16 13:45:44.468  8967  8967 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-16 13:45:44.468  8967  8967 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@d13242e
08-16 13:45:44.470  8967  8967 D serial_port: close(fd = 24)
08-16 13:45:44.473  8967  8967 I UEI.SmartControl: Serial port is closed.,
08-16 13:45:44.473  8967  8967 I UEI.SmartControl: Serial port is closed.
08-16 13:45:44.473  8967  8967 D UEI.SmartControl: Blaster closed
08-16 13:45:44.473  8967  8967 D UEI.SmartControl: Shut down QS...
08-16 13:45:44.473  8967  8967 D UEI.SmartControl: Stopping QS lib
,08-16 13:45:44.474  8967  8967 D UEI.SmartControl: QS lib stop result = true
08-16 13:45:44.474  8967  8967 D UEI.SmartControl: Stopped QS lib
08-16 13:45:44.474  8967  8967 D UEI.SmartControl: QS shutdown complete
08-16 13:45:46.558  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-55 f=2447 sc=60 link=72 tx=2.0, 0.0, 0.0  rx=1.7 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1825835970] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-16 13:45:46.576  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-55 f=2447 sc=60 link=72 tx=2.0, 0.0, 0.0  rx=1.7 bcn=0 [on:0 tx:0 rx:0 period:18] from screen [on:0 period:-1825835952] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 13:45:46.576  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-16 13:45:49.595  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-55 f=2447 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:-1825832933] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 13:45:49.598  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-55 f=2447 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1825832930] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 13:45:49.598  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-16 13:45:51.606  6936  6997 I System.out: Running OutgoingSocketThread
,08-16 13:45:51.619  6936  9052 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
08-16 13:45:51.619  6936  9052 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-16 13:45:52.623  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-55 f=2447 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1825829905] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 13:45:52.626  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-55 f=2447 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1825829902] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-16 13:45:52.626  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-16 13:45:52.643  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 13:45:54.622  6936  9052 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
08-16 13:45:54.622  6936  9052 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-16 13:45:54.622  6936  9052 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 13:45:54.622  6936  9052 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 13:45:54.622  6936  9052 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,08-16 13:45:54.627  6936  9053 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
08-16 13:45:54.628  6936  9053 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-16 13:45:54.628  6936  9053 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 13:45:54.628  6936  9053 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 13:45:54.628  6936  9053 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
08-16 13:45:54.630  6936  9056 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 920, name: OutgoingSocketThread/Receiver)
08-16 13:45:54.631  6936  9056 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 920, thread name: OutgoingSocketThread/Receiver)
08-16 13:45:54.631  6936  9056 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-16 13:45:54.631  6936  9056 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 920, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
08-16 13:45:54.633  6936  9055 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 919, name: OutgoingSocketThread/Sender)
08-16 13:45:54.634  6936  9058 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 922, name: IncomingSocketThread/Receiver)
08-16 13:45:54.634  6936  9058 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 922, thread name: IncomingSocketThread/Receiver)
08-16 13:45:54.634  6936  9058 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-16 13:45:54.634  6936  9058 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 922, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
08-16 13:45:54.636  6936  9057 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 921, name: IncomingSocketThread/Sender)
,08-16 13:45:55.654  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:-1825826875] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-16 13:45:55.657  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1825826872] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-16 13:45:55.657  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-16 13:45:58.683  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:-1825823845] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 13:45:58.686  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1825823842] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 13:45:58.686  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-16 13:46:00.048  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-16 13:46:00.048  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
,08-16 13:46:00.048  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-16 13:46:00.049  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,08-16 13:46:00.062  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
,08-16 13:46:00.062  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
08-16 13:46:00.063  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
08-16 13:46:00.064  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
08-16 13:46:01.710  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3007] from screen [on:0 period:-1825820818] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 13:46:01.713  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1825820815] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 13:46:01.714  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-16 13:46:02.341  1036  1538 E WifiStateMachine:  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 3 0
,08-16 13:46:02.342  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 3 0
,08-16 13:46:02.344  1036  1538 E WifiStateMachine:  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 3 0
08-16 13:46:02.345  1036  1538 E WifiStateMachine:  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 3 0
08-16 13:46:02.346  1036  1538 E WifiStateMachine:  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 3 0
08-16 13:46:02.347  1036  1538 E WifiStateMachine:  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 3 0
,08-16 13:46:02.629  6936  6997 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 931)
,08-16 13:46:02.639  6936  6997 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-16 13:46:02.639  6936  6997 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 932)
,08-16 13:46:04.738  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1825817790] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-16 13:46:04.751  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1825817777] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-16 13:46:04.751  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-16 13:46:07.647  6936  6997 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 13:46:07.647  6936  6997 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3476efb9 added. We now have 3 listener(s)
,08-16 13:46:07.658  1036  1994 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 13:46:07.662  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 13:46:07.663  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 13:46:07.663  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 13:46:07.663  6936  6997 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 13:46:07.663  6936  6997 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35c49ffe added. We now have 4 listener(s)
08-16 13:46:07.663  6936  6997 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 13:46:07.665  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 13:46:07.669  6936  6997 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 13:46:07.675  6936  6997 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 13:46:07.675  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:46:07.675  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 13:46:07.675  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:46:07.675  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 13:46:07.675  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 13:46:07.675  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 13:46:07.675  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 13:46:07.678  6936  6997 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 13:46:07.679  6936  6997 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 13:46:07.681  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:46:07.685  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:46:07.686  6936  6997 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 13:46:07.686  6936  6997 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 13:46:07.686  6936  6997 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 13:46:07.686  6936  6997 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:46:07.686  6936  6997 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:46:07.686  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 13:46:07.686  6936  6997 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 13:46:07.686  6936  6997 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3476efb9 removed from the list
08-16 13:46:07.686  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:46:07.686  6936  6997 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35c49ffe removed from the list
08-16 13:46:07.687  6936  6997 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:46:07.687  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:46:07.687  6936  6997 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:46:07.687  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:46:07.690  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:46:07.690  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:46:07.690  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:46:07.690  6936  6997 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35c49ffe not in the list
08-16 13:46:07.690  6936  6997 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:46:07.691  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:46:07.692  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:46:07.692  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:46:07.692  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:46:07.692  6936  6997 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35c49ffe not in the list
08-16 13:46:07.692  6936  6997 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:46:07.692  6936  6997 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:46:07.692  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:46:07.692  6936  6997 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: ,removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3476efb9 not in the list
08-16 13:46:07.693  6936  6997 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 13:46:07.693  6936  6997 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@247c81ac added. We now have 3 listener(s)
08-16 13:46:07.694  1036  2032 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-16 13:46:07.702  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 13:46:07.702  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 13:46:07.702  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 13:46:07.702  6936  6997 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 13:46:07.702  6936  6997 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f8dce75 added. We now have 4 listener(s)
08-16 13:46:07.702  6936  6997 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 13:46:07.704  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 13:46:07.707  6936  6997 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 13:46:07.713  6936  6997 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 13:46:07.713  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:46:07.713  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 13:46:07.713  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:46:07.713  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 13:46:07.713  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 13:46:07.713  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 13:46:07.713  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 13:46:07.715  6936  6997 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 13:46:07.715  6936  6997 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 13:46:07.718  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:46:07.720  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:46:07.721  6936  6997 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 13:46:07.721  6936  6997 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 13:46:07.722  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 13:46:07.722  6936  6997 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 13:46:07.722  6936  6997 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 13:46:07.726  6936  6997 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-16 13:46:07.726  1036  1958 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 13:46:07.731  6936  6997 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 13:46:07.734  6936  6997 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-16 13:46:07.736  6936  6997 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 13:46:07.736  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 13:46:07.738  6936  6997 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-16 13:46:07.740  6936  6997 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 13:46:07.740  6936  6997 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 13:46:07.768  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1825814760] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 13:46:07.769  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:-1825814760] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 13:46:07.769  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-16 13:46:10.741  6936  6997 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 13:46:10.741  6936  6997 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 13:46:10.741  6936  6997 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 13:46:10.752  6936  6997 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:46:10.752  6936  6997 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:46:10.752  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 13:46:10.752  6936  6997 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 13:46:10.752  6936  6997 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@247c81ac removed from the list
08-16 13:46:10.752  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:46:10.752  6936  6997 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f8dce75 removed from the list
08-16 13:46:10.752  6936  6997 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:46:10.753  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:46:10.755  6936  6997 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:46:10.755  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:46:10.761  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:46:10.761  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 13:46:10.765  6936  6997 D BluetoothLeScanner: could not find callback wrapper
08-16 13:46:10.765  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 13:46:10.765  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:46:10.765  6936  6997 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f8dce75 not in the list
08-16 13:46:10.765  6936  6997 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:46:10.765  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:46:10.766  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:46:10.767  6936  6997 D BluetoothLeScanner: could not find callback wrapper
08-16 13:46:10.767  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 13:46:10.767  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:46:10.767  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:46:10.767  6936  6997 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f8dce75 not in the list
08-16 13:46:10.767  6936  6997 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:46:10.767  6936  6997 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:46:10.767  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:46:10.767  6936  6997 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@247c81ac not in the list
08-16 13:46:10.768  6936  6997 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 13:46:10.768  6936  6997 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34f9dcf1 added. We now have 3 listener(s)
08-16 13:46:10.769  1036  1994 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 13:46:10.773  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 13:46:10.773  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 13:46:10.773  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 13:46:10.774  6936  6997 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 13:46:10.774  6936  6997 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31ab0d6 added. We now have 4 listener(s)
08-16 13:46:10.774  6936  6997 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 13:46:10.778  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 13:46:10.782  6936  6997 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 13:46:10.787  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1825811741] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 13:46:10.788  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1825811740] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 13:46:10.788  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-16 13:46:10.795  6936  6997 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 13:46:10.795  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:46:10.795  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 13:46:10.795  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:46:10.795  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 13:46:10.795  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 13:46:10.795  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 13:46:10.795  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 13:46:10.798  6936  6997 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 13:46:10.798  6936  6997 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 13:46:10.801  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:46:10.802  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:46:10.804  6936  6997 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-16 13:46:10.805  6936  6997 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
08-16 13:46:10.805  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
,08-16 13:46:10.810  6936  6997 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-16 13:46:10.810  6936  6997 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
08-16 13:46:10.810  6936  6997 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-16 13:46:10.810  6936  6997 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 13:46:10.813  6936  6997 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-16 13:46:10.814  6936  6997 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-16 13:46:10.814  6936  6997 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-16 13:46:10.814  6936  6936 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-16 13:46:10.816  6936  6997 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-16 13:46:10.816  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
08-16 13:46:10.816  6936  6997 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 13:46:10.816  6936  6997 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 13:46:10.822  6936  6997 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 13:46:10.824  1036  2032 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 13:46:10.830  6936  6997 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-16 13:46:10.831  6936  6997 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-16 13:46:10.832  1036  1995 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 13:46:10.834  6936  6997 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-16 13:46:10.836  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-16 13:46:10.839  6936  6997 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-16 13:46:10.841  6936  9059 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 13:46:10.843  8183  8198 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=82
08-16 13:46:10.843  6936  9059 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
08-16 13:46:13.811  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3007] from screen [on:0 period:-1825808717] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 13:46:13.814  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1825808714] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 13:46:13.814  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-16 13:46:13.842  6936  6997 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 13:46:13.842  6936  6997 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 13:46:13.843  6936  6997 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-16 13:46:13.843  6936  6997 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-16 13:46:13.843  6936  6997 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-16 13:46:13.843  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,08-16 13:46:13.856  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 13:46:13.856  6936  6997 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-16 13:46:13.857  6936  9059 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-16 13:46:13.857  6936  9059 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-16 13:46:13.857  6936  9059 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-16 13:46:13.861  6936  6936 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-16 13:46:13.862  6936  6997 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 13:46:13.862  6936  6997 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:46:13.862  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-16 13:46:13.867  6936  6936 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 13:46:13.867  6936  6936 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-16 13:46:13.867  6936  6936 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-16 13:46:13.867  6936  6997 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:46:13.867  6936  6997 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:46:13.867  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 13:46:13.867  6936  6997 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 13:46:13.867  6936  6997 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34f9dcf1 removed from the list
08-16 13:46:13.867  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:46:13.867  6936  6997 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31ab0d6 removed from the list
08-16 13:46:13.867  6936  6997 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:46:13.868  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:46:13.868  6936  6997 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:46:13.868  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:46:13.869  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:46:13.869  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:46:13.870  6936  6997 D BluetoothLeScanner: could not find callback wrapper
08-16 13:46:13.870  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 13:46:13.870  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:46:13.870  6936  6997 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31ab0d6 not in the list
08-16 13:46:13.870  6936  6997 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:46:13.870  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:46:13.872  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:46:13.874  6936  6997 D BluetoothLeScanner: could not find callback wrapper
08-16 13:46:13.874  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 13:46:13.874  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:46:13.874  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:46:13.874  6936  6997 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31ab0d6 not in the list
08-16 13:46:13.874  6936  6997 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:46:13.874  6936  6997 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already remo,ved
08-16 13:46:13.874  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:46:13.875  6936  6997 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34f9dcf1 not in the list
08-16 13:46:13.875  6936  6997 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 13:46:13.875  6936  6997 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21e90462 added. We now have 3 listener(s)
,08-16 13:46:13.881  1036  2032 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 13:46:13.884  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 13:46:13.885  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 13:46:13.885  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 13:46:13.885  6936  6997 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 13:46:13.885  6936  6997 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3558e9f3 added. We now have 4 listener(s)
08-16 13:46:13.885  6936  6997 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 13:46:13.887  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 13:46:13.890  6936  6997 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 13:46:13.896  6936  6997 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 13:46:13.896  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:46:13.896  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 13:46:13.896  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:46:13.896  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 13:46:13.896  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 13:46:13.896  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 13:46:13.896  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 13:46:13.897  6936  6997 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 13:46:13.898  6936  6997 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 13:46:13.901  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:46:13.903  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:46:13.905  6936  6997 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 13:46:13.905  6936  6997 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 13:46:13.905  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 13:46:13.905  6936  6997 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 13:46:13.905  6936  6997 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 13:46:13.909  6936  6997 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-16 13:46:13.911  1036  1958 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 13:46:13.915  6936  6997 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 13:46:13.917  6936  6997 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-16 13:46:13.919  6936  6997 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 13:46:13.920  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 13:46:13.921  6936  6997 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-16 13:46:16.840  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1825805688] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 13:46:16.843  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1825805685] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 13:46:16.843  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-16 13:46:16.929  6936  6997 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 13:46:16.938  6936  6997 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 13:46:16.938  6936  6997 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 13:46:16.939  6936  6997 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:46:16.939  6936  6997 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:46:16.940  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 13:46:16.941  6936  6997 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 13:46:16.941  6936  6997 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21e90462 removed from the list
08-16 13:46:16.941  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:46:16.941  6936  6997 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3558e9f3 removed from the list
08-16 13:46:16.941  6936  6997 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:46:16.941  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:46:16.943  6936  6997 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:46:16.943  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:46:16.944  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:46:16.944  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:46:16.946  6936  6997 D BluetoothLeScanner: could not find callback wrapper
08-16 13:46:16.946  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 13:46:16.946  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:46:16.946  6936  6997 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3558e9f3 not in the list
08-16 13:46:16.946  6936  6997 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:46:16.946  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:46:16.947  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 13:46:16.951  6936  6997 D BluetoothLeScanner: could not find callback wrapper
08-16 13:46:16.951  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 13:46:16.951  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:46:16.951  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:46:16.951  6936  6997 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3558e9f3 not in the list
08-16 13:46:16.951  6936  6997 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:46:16.951  6936  6997 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:46:16.951  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:46:16.951  6936  6997 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21e90462 not in the list
08-16 13:46:16.952  6936  6997 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 13:46:16.952  6936  6997 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@230e324f added. We now have 3 listener(s)
08-16 13:46:16.953  1036  1646 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 13:46:16.956  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 13:46:16.956  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 13:46:16.956  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 13:46:16.956  6936  6997 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 13:46:16.956  6936  6997 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3879addc added. We now have 4 listener(s)
08-16 13:46:16.956  6936  6997 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 13:46:16.958  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 13:46:16.962  6936  6997 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 13:46:16.969  6936  6997 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 13:46:16.969  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:46:16.969  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 13:46:16.969  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:46:16.969  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 13:46:16.969  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 13:46:16.969  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 13:46:16.969  6936  6997 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 13:46:16.972  6936  6997 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 13:46:16.972  6936  6997 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 13:46:16.974  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:46:16.978  6936  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:46:16.979  6936  6997 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 13:46:16.980  6936  6997 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 13:46:16.980  6936  6997 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 13:46:16.980  6936  6997 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:46:16.980  6936  6997 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:46:16.980  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 13:46:16.980  6936  6997 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 13:46:16.980  6936  6997 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@230e324f removed from the list
08-16 13:46:16.980  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:46:16.980  6936  6997 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3879addc removed from the list
08-16 13:46:16.980  6936  6997 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:46:16.980  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:46:16.981  6936  6997 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:46:16.981  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:46:16.984  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:46:16.984  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:46:16.984  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 13:46:16.984  6936  6997 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3879addc not in the list
08-16 13:46:16.984  6936  6997 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:46:16.984  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:46:16.985  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:46:16.985  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:46:16.985  6936  6997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:46:16.985  6936  6997 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3879addc not in the list
08-16 13:46:16.985  6936  6997 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:46:16.985  6936  6997 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:46:16.985  6936  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:46:16.985  6936  6997 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@230e324f not in the list
08-16 13:46:19.870  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3007] from screen [on:0 period:-1825802658] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 13:46:19.873  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1825802655] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 13:46:19.873  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-16 13:46:21.988  6936  6997 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-16 13:46:21.989  6936  6997 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-16 13:46:21.997  6936  6997 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,08-16 13:46:21.998  6936  6997 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 13:46:21.999  6936  6997 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-16 13:46:22.000  6936  6997 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-16 13:46:22.898  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:-1825799630] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-16 13:46:22.911  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1825799617] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-16 13:46:22.911  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-16 13:46:25.930  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:-1825796598] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 13:46:25.933  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1825796595] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 13:46:25.934  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-16 13:46:28.958  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1825793570] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-16 13:46:28.969  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1825793559] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 13:46:28.971  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-16 13:46:29.027  6936  9060 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 941, name: My test thread name)
,08-16 13:46:31.024  6936  6997 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 941
08-16 13:46:31.025  6936  6997 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 941, name: My test thread name)
,08-16 13:46:31.041  6936  9061 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 942, name: My test thread name)
08-16 13:46:31.041  6936  9061 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 942, thread name: My test thread name)
08-16 13:46:31.041  6936  9061 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 942, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
08-16 13:46:31.051  6936  6997 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-16 13:46:31.058  6936  9062 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 946, name: My test thread name)
08-16 13:46:31.058  6936  9062 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 946, thread name: My test thread name): Test exception.
08-16 13:46:31.058  6936  9062 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 946, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
08-16 13:46:31.062  6936  6997 I jxcore-log: Total number of executed tests:  82
08-16 13:46:31.062  6936  6997 I jxcore-log: 
08-16 13:46:31.062  6936  6997 I jxcore-log: Number of passed tests:  82
08-16 13:46:31.062  6936  6997 I jxcore-log: 
08-16 13:46:31.062  6936  6997 I jxcore-log: Number of failed tests:  0
08-16 13:46:31.062  6936  6997 I jxcore-log: 
08-16 13:46:31.063  6936  6997 I jxcore-log: Number of ignored tests:  0
08-16 13:46:31.063  6936  6997 I jxcore-log: 
08-16 13:46:31.063  6936  6997 I jxcore-log: Total duration:  146733
08-16 13:46:31.063  6936  6997 I jxcore-log: 
08-16 13:46:31.063  6936  6997 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-16 13:46:31.063  6936  6997 I jxcore-log: 
08-16 13:46:31.081  6936  6997 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 13:46:31.081  6936  6997 I jxcore-log: 
08-16 13:46:31.084  6936  6997 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 13:46:31.084  6936  6997 I jxcore-log: 
08-16 13:46:31.086  6936  6997 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 13:46:31.086  6936  6997 I jxcore-log: 
08-16 13:46:31.087  6936  6997 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 13:46:31.087  6936  6997 I jxcore-log: 
08-16 13:46:31.088  6936  6997 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 13:46:31.088  6936  6997 I jxcore-log: 
,08-16 13:46:31.101  6936  6936 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
08-16 13:46:31.101  6936  6997 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 13:46:31.101  6936  6997 I jxcore-log: 
08-16 13:46:31.105  6936  6997 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 13:46:31.105  6936  6997 I jxcore-log: 
08-16 13:46:31.107  6936  6997 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 13:46:31.107  6936  6997 I jxcore-log: 
08-16 13:46:31.108  6936  6997 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 13:46:31.108  6936  6997 I jxcore-log: 
08-16 13:46:31.109  6936  6997 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 13:46:31.109  6936  6997 I jxcore-log: 
08-16 13:46:31.111  6936  6997 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 13:46:31.111  6936  6997 I jxcore-log: 
08-16 13:46:31.113  6936  6997 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 13:46:31.113  6936  6997 I jxcore-log: 
08-16 13:46:31.114  6936  6997 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 13:46:31.114  6936  6997 I jxcore-log: 
08-16 13:46:31.115  6936  6997 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 13:46:31.115  6936  6997 I jxcore-log: 
08-16 13:46:31.115  6936  6997 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 13:46:31.115  6936  6997 I jxcore-log: 
08-16 13:46:31.117  6936  6997 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 13:46:31.117  6936  6997 I jxcore-log: 
08-16 13:46:31.117  6936  6997 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 13:46:31.117  6936  6997 I jxcore-log: 
08-16 13:46:31.118  6936  6997 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 13:46:31.118  6936  6997 I jxcore-log: 
,08-16 13:46:31.122  6936  6997 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 13:46:31.122  6936  6997 I jxcore-log: 
08-16 13:46:31.125  6936  6997 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 13:46:31.125  6936  6997 I jxcore-log: 
08-16 13:46:31.126  6936  6997 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 13:46:31.126  6936  6997 I jxcore-log: 
08-16 13:46:31.127  6936  6997 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 13:46:31.127  6936  6997 I jxcore-log: 
08-16 13:46:31.128  6936  6997 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 13:46:31.128  6936  6997 I jxcore-log: 
08-16 13:46:31.128  6936  6997 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 13:46:31.128  6936  6997 I jxcore-log: 
08-16 13:46:31.130  6936  6997 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 13:46:31.130  6936  6997 I jxcore-log: 
08-16 13:46:31.131  6936  6997 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 13:46:31.131  6936  6997 I jxcore-log: 
08-16 13:46:31.132  6936  6997 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 13:46:31.132  6936  6997 I jxcore-log: 
08-16 13:46:31.133  6936  6997 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 13:46:31.133  6936  6997 I jxcore-log: 
08-16 13:46:31.133  6936  6997 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 13:46:31.133  6936  6997 I jxcore-log: 
08-16 13:46:31.134  6936  6997 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 13:46:31.134  6936  6997 I jxcore-log: 
08-16 13:46:31.135  6936  6997 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 13:46:31.135  6936  6997 I jxcore-log: 
08-16 13:46:31.136  6936  6997 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 13:46:31.136  6936  6997 I jxcore-log: 
08-16 13:46:31.136  6936  6997 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 13:46:31.136  6936  6997 I jxcore-log: 
08-16 13:46:31.137  6936  6997 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 13:46:31.137  6936  6997 I jxcore-log: 
08-16 13:46:31.138  6936  6997 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 13:46:31.138  6936  6997 I jxcore-log: 
08-16 13:46:31.139  6936  6997 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":,"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 13:46:31.139  6936  6997 I jxcore-log: 
08-16 13:46:31.140  6936  6997 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 13:46:31.140  6936  6997 I jxcore-log: 
08-16 13:46:31.141  6936  6997 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 13:46:31.141  6936  6997 I jxcore-log: 
08-16 13:46:31.142  6936  6997 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 13:46:31.142  6936  6997 I jxcore-log: 
08-16 13:46:31.143  6936  6997 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 13:46:31.143  6936  6997 I jxcore-log: 
08-16 13:46:31.143  6936  6997 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 13:46:31.143  6936  6997 I jxcore-log: 
08-16 13:46:31.144  6936  6997 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 13:46:31.144  6936  6997 I jxcore-log: 
08-16 13:46:31.145  6936  6997 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 13:46:31.145  6936  6997 I jxcore-log: 
,08-16 13:46:31.194  6936  9060 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 941, name: My test thread name), during the lifetime of the thread the total number of bytes read was 154 and the total number of bytes written 154
,08-16 13:46:31.406  9063  9063 D AndroidRuntime: 
08-16 13:46:31.406  9063  9063 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-16 13:46:31.414  9063  9063 D AndroidRuntime: CheckJNI is OFF
08-16 13:46:31.626  9063  9063 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-16 13:46:31.645  1036  1093 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
,08-16 13:46:31.649  1036  1093 I ActivityManager: Killing 6936:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
08-16 13:46:31.729  1036  1755 I WindowState: WIN DEATH: Window{22a8a0b8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-16 13:46:31.735  1036  1543 D WifiService: Client connection lost with reason: 4
08-16 13:46:31.741  1036  1755 D InputDispatcher: Window went away: Window{22a8a0b8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-16 13:46:31.781  1036  1093 I ActivityManager:   Force finishing activity ActivityRecord{fe7a9ed u0 com.test.thalitest/.MainActivity t6}
,08-16 13:46:31.858   332   348 E GBMv2   : DFP En is all cleared set to be enabled
08-16 13:46:31.863  1036  1646 W ActivityManager: Spurious death for ProcessRecord{111750df 6936:com.test.thalitest/u0a118}, curProc for 6936: null
08-16 13:46:31.866  1036  1125 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-16 13:46:31.866  1941  1956 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-16 13:46:31.866  1036  1125 I ActivityManager:   Force finishing activity ActivityRecord{fe7a9ed u0 com.test.thalitest/.MainActivity t6 f}
08-16 13:46:31.866  1941  1956 D SplitWindowPolicy: topRunningActivity=ActivityInfo{7406114 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-16 13:46:31.866  1036  1125 W ActivityManager: Duplicate finish request for ActivityRecord{fe7a9ed u0 com.test.thalitest/.MainActivity t6 f}
08-16 13:46:31.868  1941  4406 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-16 13:46:31.869  1941  4406 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1d759dbd co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
,08-16 13:46:31.903  2034  2034 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-16 13:46:31.904  2034  2034 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-16 13:46:31.907  1603  1603 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-16 13:46:31.910  1036  1441 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-16 13:46:31.920  3769  3769 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-16 13:46:31.920  1997  1997 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
,08-16 13:46:31.922  8183  8183 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-16 13:46:31.922  8183  8183 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-16 13:46:31.923  2474  2630 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-16 13:46:31.934  4891  4891 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-16 13:46:31.934  4891  4891 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-16 13:46:31.934  4891  4891 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-16 13:46:31.935  4891  4891 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-16 13:46:31.935  4891  4891 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-16 13:46:31.935  4891  4891 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 13:46:31.935  4891  4891 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-16 13:46:31.935  4891  4891 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-16 13:46:31.935  4891  4891 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 13:46:31.935  4891  4891 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 13:46:31.935  4891  4891 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-16 13:46:31.935  4891  4891 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-16 13:46:31.952  4997  4997 I art     : Explicit concurrent mark sweep GC freed 15444(886KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 418us total 64.090ms
,08-16 13:46:31.961  1036  1940 V SIM_STK : Menu title from STK is T-Mobile
08-16 13:46:31.971  8430  8430 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-16 13:46:31.971  2034  2034 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-16 13:46:31.972  2034  2124 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
,08-16 13:46:31.986  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1825790542] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 13:46:31.987  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1825790541] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 13:46:31.987  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-16 13:46:31.992  1603  1603 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-16 13:46:31.994  2034  2034 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-16 13:46:31.994  1603  1656 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-16 13:46:31.994  1603  1656 D KeyguardModel: createShortcutInfo...
08-16 13:46:31.995  1905  1905 D ActionManagerService: notifyUserLog: 1000003
08-16 13:46:31.996  3769  4911 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-16 13:46:31.996  1816  1816 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-16 13:46:31.996  2034  2034 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-16 13:46:31.997  2034  2034 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-16 13:46:31.999  1603  1656 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-16 13:46:31.999  1603  1656 D KeyguardModel: createShortcutInfo...
08-16 13:46:32.002  2034  2034 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
,08-16 13:46:32.004  1603  1656 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-16 13:46:32.004  1603  1656 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 13:46:32.004  1603  1656 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-16 13:46:32.005  1905  1905 D ActionManagerService: notifyUserLog: 1000004
08-16 13:46:32.005  1603  1656 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-16 13:46:32.006  3769  4911 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-16 13:46:32.006  2034  2034 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-16 13:46:32.008  1603  1603 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-16 13:46:32.008  1603  1603 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-16 13:46:32.009  1603  1656 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-16 13:46:32.010  1603  1656 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-16 13:46:32.010  3769  3785 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-16 13:46:32.011  2034  2034 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-16 13:46:32.011  2034  2034 I GBoardWebViewUtils: , create_time: 1430832262123
08-16 13:46:32.011  2034  2034 I GBoardWebViewUtils: , expire_time: 0
08-16 13:46:32.011  2034  2034 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-16 13:46:32.011  2034  2034 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-16 13:46:32.011  2034  2034 I GBoardWebViewUtils: , display: false
08-16 13:46:32.011  2034  2034 I GBoardWebViewUtils: , animation: false }
08-16 13:46:32.011  2034  2034 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-16 13:46:32.011  2034  2034 I GBoardWebViewUtils: , create_time: 1430832262287
08-16 13:46:32.011  2034  2034 I GBoardWebViewUtils: , expire_time: 0
08-16 13:46:32.011  2034  2034 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-16 13:46:32.011  2034  2034 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-16 13:46:32.011  2034  2034 I GBoardWebViewUtils: , display: false
08-16 13:46:32.011  2034  2034 I GBoardWebViewUtils: , animation: false }
08-16 13:46:32.011  2034  2034 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1471007225619
08-16 13:46:32.011  2034  2034 I GBoardWebViewUtils: , create_time: 1471007226523
08-16 13:46:32.011  2034  2034 I GBoardWebViewUtils: , expire_time: 0
08-16 13:46:32.011  2034  2034 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide.html?id=guide_1111111111116_1471007225619&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-16 13:46:32.011  2034  2034 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-16 13:46:32.011  2034  2034 I GBoardWebViewUtils: , display: false
08-16 13:46:32.011  2034  2034 I GBoardWebViewUtils: , animation: false }
08-16 13:46:32.017  1603  1656 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-16 13:46:32.017  1603  1656 D KeyguardModel: cre,ateShortcutInfo...
,08-16 13:46:32.024  1603  1656 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-16 13:46:32.024  1603  1656 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 13:46:32.026  2034  9094 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-16 13:46:32.026  1603  1656 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-16 13:46:32.027  1603  1656 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-16 13:46:32.031  1603  1656 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
,08-16 13:46:32.031  1603  1656 D KeyguardModel: createShortcutInfo...
08-16 13:46:32.036  1868  1868 D SplitUIManager: split_name #11 / not available #0
08-16 13:46:32.037  1868  1868 D SplitUIService: removed split : 
08-16 13:46:32.038  2034  2034 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-16 13:46:32.039  2034  2034 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-16 13:46:32.044  1603  1656 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 13:46:32.044  1603  1656 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-16 13:46:32.045  1603  1656 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,08-16 13:46:32.050  1603  1656 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-16 13:46:32.056  2175  2175 I ConfigService: onCreate
08-16 13:46:32.056  2175  2175 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-16 13:46:32.060  1603  1656 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-16 13:46:32.060  1603  1656 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-16 13:46:32.069  2175  2175 I ConfigService: onBind returning update interface
,08-16 13:46:32.070  1036  2032 V SIM_STK : Menu title from STK is T-Mobile
08-16 13:46:32.070  1036  2032 V SIM_STK : Menu title from STK is T-Mobile
08-16 13:46:32.072  1603  1656 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-16 13:46:32.072  1603  1656 D KeyguardModel: createShortcutInfo...
08-16 13:46:32.072  1816  1816 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-16 13:46:32.087  1603  1603 D KeyguardModel: handleShortcutListChanged...
08-16 13:46:32.087  1603  1603 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,08-16 13:46:32.090  2175  2175 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-16 13:46:32.090  2175  2175 I ConfigService: onBind returning config service
08-16 13:46:32.100  1603  1656 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-16 13:46:32.100  1603  1656 D KeyguardModel: createShortcutInfo...
,08-16 13:46:32.104  1603  1656 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-16 13:46:32.104  1603  1656 D KeyguardModel: createShortcutInfo...
08-16 13:46:32.113  1603  1656 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-16 13:46:32.113  1603  1656 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-16 13:46:32.114  1868  1868 D SplitUIManager: split_name #11 / not available #0
08-16 13:46:32.114  1868  1868 I SplitUIService: split app #11
08-16 13:46:32.115  1603  1656 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-16 13:46:32.115  1603  1656 D KeyguardModel: createShortcutInfo...
08-16 13:46:32.116  1603  1656 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-16 13:46:32.117  1603  1656 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-16 13:46:32.117  1603  1656 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-16 13:46:32.118  1603  1656 D KeyguardModel: createShortcutInfo...
08-16 13:46:32.119  1603  1656 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-16 13:46:32.119  1603  1656 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-16 13:46:32.120  1036  1036 I art     : Explicit concurrent mark sweep GC freed 52448(2MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 43MB/65MB, paused 2.793ms total 227.013ms
,08-16 13:46:32.126  1603  1656 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-16 13:46:32.126  1603  1656 D KeyguardModel: createShortcutInfo...
08-16 13:46:32.126  1036  1125 I art     : WaitForGcToComplete blocked for 116.972ms for cause Explicit
08-16 13:46:32.127  2034  2034 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-16 13:46:32.133  1036  1036 D administrator: Handling package changes for user 0
08-16 13:46:32.136  1603  1603 D KeyguardModel: handleShortcutListChanged...
08-16 13:46:32.136  1603  1603 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,08-16 13:46:32.151  1816  1816 I ConfigFetchService: service connected
08-16 13:46:32.152  1816  1816 I ConfigClient: service connected
,08-16 13:46:32.153  1036  2033 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-16 13:46:32.158  8183  8183 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-16 13:46:32.158  8183  8183 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-16 13:46:32.158  8183  8183 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-16 13:46:32.158  8183  8183 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-16 13:46:32.158  8183  8183 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-16 13:46:32.158  8183  8183 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-16 13:46:32.158  8183  8183 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-16 13:46:32.158  8183  8183 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-16 13:46:32.158  8183  8183 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-16 13:46:32.158  8183  8183 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-16 13:46:32.158  8183  8183 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-16 13:46:32.180  2175  2175 I ConfigService: onDestroy
,08-16 13:46:32.184  2034  2034 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
08-16 13:46:32.186  1816  9099 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-16 13:46:32.187  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 13:46:32.188  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-16 13:46:32.190  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-16 13:46:32.191  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-16 13:46:32.192  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-16 13:46:32.196  1036  1052 V SIM_STK : Menu title from STK is T-Mobile
08-16 13:46:32.210  2034  2034 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-16 13:46:32.210  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-16 13:46:32.213  2034  2198 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-16 13:46:32.213  2034  2198 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-16 13:46:32.219  1036  1109 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2486e257 u0 com.lge.launcher2/.Launcher t5} time:488900
08-16 13:46:32.231  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-16 13:46:32.231  2034  2034 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-16 13:46:32.231  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-16 13:46:32.241  5843  9106 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
,08-16 13:46:32.242  2034  2034 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-16 13:46:32.247  2600  2600 D [Concierge]Service: onStartCommand(). Type : 8
08-16 13:46:32.247  2600  2600 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-16 13:46:32.249  2600  2600 D [Concierge]Service: Update widget ID : 11
08-16 13:46:32.250  1036  1036 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-16 13:46:32.250  1036  1036 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-16 13:46:32.250  1036  1036 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-16 13:46:32.250  2034  2034 D [Concierge]WidgetView: change position of spinner
08-16 13:46:32.253  1036  1577 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-16 13:46:32.253  2034  2034 I [Concierge]WidgetView: initWebView(). Time : 1471347992253
08-16 13:46:32.254  2600  2600 D [Concierge]Service: onStartCommand(). Type : 0
08-16 13:46:32.268  1816  9109 I PeopleContactsSync: CP2 sync disabled
08-16 13:46:32.269  1816  5159 I Icing   : doRemovePackageData com.test.thalitest
,08-16 13:46:32.273  1816  9107 W GmsApplication: Using Auth Proxy for data requests.
08-16 13:46:32.273  7309  7309 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
08-16 13:46:32.277  2034  2034 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 315083390
08-16 13:46:32.278  2034  2034 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-16 13:46:32.278  2034  2034 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-16 13:46:32.281  2034  2034 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@31873ffe
08-16 13:46:32.281  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
,08-16 13:46:32.284  2034  2034 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-16 13:46:32.284  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 13:46:32.294  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
,08-16 13:46:32.294  2034  2034 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-16 13:46:32.294  2034  2034 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-16 13:46:32.297  2336  9110 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-16 13:46:32.321  1036  1755 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=9113 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-16 13:46:32.323  2034  2034 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1471347531490, New one : 1471347992253
08-16 13:46:32.323  2034  2034 D [Concierge]WidgetView: Unregister all receivers
08-16 13:46:32.323  2034  2034 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-16 13:46:32.324  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 13:46:32.326  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-16 13:46:32.327  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-16 13:46:32.328  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-16 13:46:32.330  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-16 13:46:32.331  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-16 13:46:32.333  1816  9107 W GmsApplication: Using Auth Proxy for data requests.
08-16 13:46:32.333  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 13:46:32.333  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-16 13:46:32.362  2034  2034 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-16 13:46:32.366  9113  9113 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 13:46:32.367  9113  9113 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 13:46:32.367  9113  9113 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-16 13:46:32.368  9113  9113 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-16 13:46:32.370  2034  2034 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-16 13:46:32.370  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-16 13:46:32.371  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 13:46:32.401  2034  2034 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@201835ab time:489081
,08-16 13:46:32.422  1036  1125 I art     : Explicit concurrent mark sweep GC freed 9686(544KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 10.613ms total 295.341ms
,08-16 13:46:32.435  9113  9113 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-16 13:46:32.447  9113  9113 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-16 13:46:32.472  9113  9113 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-16 13:46:32.498  9113  9113 D LgDataFeature: LgDataFeature() Constructor: none
08-16 13:46:32.498  9113  9113 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 13:46:32.508  9063  9063 D AndroidRuntime: Shutting down VM
,08-16 13:46:32.551  9113  9113 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
08-16 13:46:32.554  2034  2034 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-16 13:46:32.564  1036  1903 I ActivityManager: Killing 8363:com.lge.formmanager/u0a26 (adj 15): empty #17
,08-16 13:46:32.591  2034  2854 I GBoardtInterface: onReloaded()
,08-16 13:46:32.596  2034  2034 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-16 13:46:32.612  1997  1997 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-16 13:46:32.612  1997  1997 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
,08-16 13:46:32.615  1036  2032 W libprocessgroup: failed to open /acct/uid_10026/pid_8363/cgroup.procs: No such file or directory
08-16 13:46:32.618  1997  1997 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
08-16 13:46:32.619  3769  3785 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-16 13:46:32.623  3769  4887 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,08-16 13:46:32.630  8430  8430 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
,08-16 13:46:32.687  1036  2033 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=9136 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-16 13:46:32.690  1905  1905 D ActionManagerService: notifyUserLog: 1000001
08-16 13:46:32.693  3769  4911 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-16 13:46:32.693  3769  4911 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-16 13:46:32.701  1905  1905 D ActionManagerService: notifyUserLog: 1000001
,08-16 13:46:32.703  3769  4911 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-16 13:46:32.703  3769  4911 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-16 13:46:32.703  3769  4911 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-16 13:46:32.704  3769  4911 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-16 13:46:32.705  3769  3785 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-16 13:46:32.710  2034  2034 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-16 13:46:32.710  2034  2034 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-16 13:46:32.715  2034  2034 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
,08-16 13:46:32.715  2034  2034 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-16 13:46:32.720  2034  2034 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide2.html?id=guide_1111111111116_1471007225619&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-16 13:46:32.720  2034  2034 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide2.html?id=guide_1111111111116_1471007225619&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-16 13:46:32.761  1036  1125 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=9153 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-16 13:46:32.829  1036  2033 I ActivityManager: Killing 8641:com.android.chrome/u0a57 (adj 15): empty #17
,08-16 13:46:32.841  9136  9136 E SQLiteDatabase: Failed to open database '/data/data/com.lge.lifetracker/databases/lifetracker2.db'.
08-16 13:46:32.841  9136  9136 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 13:46:32.841  9136  9136 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 13:46:32.841  9136  9136 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-16 13:46:32.841  9136  9136 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-16 13:46:32.841  9136  9136 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 13:46:32.841  9136  9136 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 13:46:32.841  9136  9136 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 13:46:32.841  9136  9136 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-16 13:46:32.841  9136  9136 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-16 13:46:32.841  9136  9136 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-16 13:46:32.841  9136  9136 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-16 13:46:32.841  9136  9136 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-16 13:46:32.841  9136  9136 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 13:46:32.841  9136  9136 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-16 13:46:32.841  9136  9136 E SQLiteDatabase: 	at com.lge.lifetracker.core.provider.LifetrackerProvider2.onCreate(LifetrackerProvider2.java:56)
08-16 13:46:32.841  9136  9136 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
08-16 13:46:32.841  9136  9136 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
08-16 13:46:32.841  9136  9136 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
08-16 13:46:32.841  9136  9136 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-16 13:46:32.841  9136  9136 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-16 13:46:32.841  9136  9136 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-16 13:46:32.841  9136  9136 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-16 13:46:32.841  9136  9136 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 13:46:32.841  9136  9136 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-16 13:46:32.841  9136  9136 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-16 13:46:32.841  9136  9136 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 13:46:32.841  9136  9136 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 13:46:32.841  9136  9136 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-16 13:46:32.841  9136  9136 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)

```
