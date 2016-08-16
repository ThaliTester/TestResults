#### Test 8076137450b0c73_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-16 10:27:00.059  1588  1588 I [SystemUI]Clock: called onTimeUpdated()
08-16 10:27:00.069  1588  1588 I LgeClockWidgetControlView: called onTimeUpdated()
08-16 10:27:00.069  1588  1588 I [SystemUI]DateView: called onTimeUpdated()
08-16 10:27:00.071  1588  1588 I [SystemUI]DateView: called onTimeUpdated()
08-16 10:27:00.073  1588  1588 D KeyguardUpdateMonitor: handleTimeUpdate
,08-16 10:27:36.417  6128  6128 D AndroidRuntime: 
08-16 10:27:36.417  6128  6128 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-16 10:27:36.420  6128  6128 D AndroidRuntime: CheckJNI is OFF
08-16 10:27:36.540  6128  6128 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-16 10:27:36.544  1037  2034 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-16 10:27:36.575  1928  1943 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-16 10:27:36.578  1037  2034 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-16 10:27:36.579  1037  2034 D ActivityManager: setTaskToReturnTo : TaskRecord{1e321bb #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-16 10:27:36.579  1037  2034 D ActivityManager: setTaskToReturnTo : TaskRecord{1e321bb #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-16 10:27:36.580  1037  2034 D WindowStateEx: AppWindowTokenEx init.. 
08-16 10:27:36.581   331   340 E GBMv2   : DFP En is all cleared set to be enabled
08-16 10:27:36.603  1037  2034 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6149 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-16 10:27:36.604  6128  6128 D AndroidRuntime: Shutting down VM
08-16 10:27:36.642  1928  3919 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-16 10:27:36.642  1928  3919 D SplitWindowPolicy: topRunningActivity=ActivityInfo{114ea324 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-16 10:27:36.643  1928  1944 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-16 10:27:36.643  1928  1944 D SplitWindowPolicy: topRunningActivity=ActivityInfo{26089e8d co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-16 10:27:36.721  6149  6149 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
,08-16 10:27:36.822  6149  6149 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-16 10:27:36.833  6149  6149 I LibraryLoader: Loading: webviewchromium
08-16 10:27:36.837  6149  6149 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 6376-6381)
,08-16 10:27:36.837  6149  6149 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 10:27:36.856  6149  6149 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {23822140}
,08-16 10:27:36.857  6149  6149 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 10:27:36.858  6149  6149 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-16 10:27:36.870  6149  6149 I BrowserStartupController: Initializing chromium process, renderers=0
08-16 10:27:36.871  6149  6149 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-16 10:27:36.877  6149  6173 W chromium: [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
08-16 10:27:36.883  6149  6149 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-16 10:27:36.883  6149  6149 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-16 10:27:36.884  6149  6149 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-16 10:27:36.890   316  1371 V AudioPolicyService: registerClient() client 0xb558a820, uid 10118
,08-16 10:27:36.907  6149  6149 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 10:27:36.907  6149  6149 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 10:27:36.907  6149  6149 I Adreno-EGL: Build Date: 12/12/14 금
08-16 10:27:36.907  6149  6149 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 10:27:36.907  6149  6149 I Adreno-EGL: Remote Branch: 
08-16 10:27:36.907  6149  6149 I Adreno-EGL: Local Patches: 
08-16 10:27:36.907  6149  6149 I Adreno-EGL: Reconstruct Branch: 
,08-16 10:27:37.012  1037  1963 I art     : Explicit concurrent mark sweep GC freed 34457(1573KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 2.080ms total 100.717ms
08-16 10:27:37.014  1037  1119 D BluetoothManagerService: Message: 20
08-16 10:27:37.014  1037  1119 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3c7b58f0:true
,08-16 10:27:37.044  6149  6184 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-16 10:27:37.048  6149  6149 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-16 10:27:37.067  6149  6149 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-16 10:27:37.072  6149  6149 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-16 10:27:37.076  6149  6149 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-16 10:27:37.079  6149  6149 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-16 10:27:37.079  6149  6149 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,08-16 10:27:37.096  6149  6149 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-16 10:27:37.104  6149  6149 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-16 10:27:37.104  6149  6149 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-16 10:27:37.142  1037  1104 W ActivityManager: Activity pause timeout for ActivityRecord{139e86d8 u0 com.test.thalitest/.MainActivity t6}
08-16 10:27:37.152  6149  6196 D OpenGLRenderer: Render dirty regions requested: true
08-16 10:27:37.152  6149  6196 I OpenGLRenderer: Initialized EGL, version 1.4
,08-16 10:27:37.162  6149  6196 D OpenGLRenderer: Enabling debug mode 0
08-16 10:27:37.190  6149  6149 D Atlas   : Validating map...
,08-16 10:27:37.197  1037  1053 D SplitWindow: check instance of lgWin Window{3f86b47f u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-16 10:27:37.229  6149  6194 D LgDataFeature: LgDataFeature() Constructor: none
,08-16 10:27:37.229  6149  6194 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 10:27:37.321  1037  1120 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +679ms (total +739ms)
,08-16 10:27:37.322  1037  1120 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{139e86d8 u0 com.test.thalitest/.MainActivity t6} time:296867
08-16 10:27:37.327  6149  6149 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2d5e590f time:296871
08-16 10:27:37.454  6149  6149 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-16 10:27:37.454  6149  6149 I chromium: 
,08-16 10:27:37.518  6149  6149 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-16 10:27:37.590  6149  6194 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-16 10:27:37.590  6149  6194 I chromium: 
,08-16 10:27:37.723  6149  6209 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1434979840
,08-16 10:27:37.741  6149  6209 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-16 10:27:37.741  6149  6209 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-16 10:27:37.741  6149  6209 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-16 10:27:37.741  6149  6209 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-16 10:27:37.741  6149  6209 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-16 10:27:37.742  6149  6209 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f6ba0a3 added. We now have 1 listener(s)
08-16 10:27:37.755  1037  1053 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-16 10:27:37.761  6149  6209 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
,08-16 10:27:37.764  6149  6209 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 10:27:37.766  6149  6209 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 10:27:37.767  6149  6209 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-16 10:27:37.775  6149  6209 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-16 10:27:37.775  6149  6209 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-16 10:27:37.775  6149  6209 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-16 10:27:37.775  6149  6209 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-16 10:27:37.775  6149  6209 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-16 10:27:37.775  6149  6209 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-16 10:27:37.775  6149  6209 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-16 10:27:37.775  6149  6209 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-16 10:27:37.775  6149  6209 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-16 10:27:37.775  6149  6209 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-16 10:27:37.775  6149  6209 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-16 10:27:37.775  6149  6209 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-16 10:27:37.775  6149  6209 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-16 10:27:37.775  6149  6209 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-16 10:27:37.775  6149  6209 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37ab6f1e added. We now have 1 listener(s)
08-16 10:27:37.776  6149  6209 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 10:27:37.780  1037  1529 D WifiService: New client listening to asynchronous messages
,08-16 10:27:37.784  6149  6209 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 10:27:37.784  6149  6209 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-16 10:27:37.784  6149  6209 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-16 10:27:37.785  6149  6209 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-16 10:27:37.785  6149  6209 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-16 10:27:37.789  6149  6209 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 10:27:37.789  1037  1901 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 10:27:37.790  6149  6209 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-16 10:27:37.797  6149  6209 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-16 10:27:37.798  6149  6209 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 10:27:37.798  6149  6209 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 10:27:37.798  6149  6209 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 10:27:37.798  6149  6209 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 10:27:37.798  6149  6209 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 10:27:37.798  6149  6209 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 10:27:37.798  6149  6209 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 10:27:37.798  6149  6209 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 10:27:37.798  6149  6209 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,08-16 10:27:37.798  6149  6209 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 10:27:37.800  6149  6149 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 10:27:37.804  6149  6209 I io.jxcore.node.LifeCycleMonitor: start: OK
08-16 10:27:37.847  6149  6149 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-16 10:27:38.221   331   343 E GBMv2   : DFP En is all cleared set to be enabled
08-16 10:27:38.221   331   343 E GBMv2   : Set value is all cleared set the max
08-16 10:27:38.221   331   343 I GBMv2   : DFP Enabled. Ignore VFP set
,08-16 10:27:39.002  6149  6212 W jxcore-log: Initializing JXcore engine
08-16 10:27:39.002  6149  6212 W jxcore-log: JXcore engine is ready
,08-16 10:27:39.072  6212  6212 W Thread-697: type=1400 audit(0.0:158): avc: denied { ioctl } for path="socket:[7454]" dev="sockfs" ino=7454 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-16 10:27:39.072  6212  6212 W Thread-697: type=1400 audit(0.0:159): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-16 10:27:39.072  6212  6212 W Thread-697: type=1400 audit(0.0:160): avc: denied { ioctl } for path="socket:[10440]" dev="sockfs" ino=10440 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-16 10:27:39.072  6212  6212 W Thread-697: type=1400 audit(0.0:161): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-16 10:27:39.072  6212  6212 W Thread-697: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[30857]" dev="sockfs" ino=30857 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-16 10:27:39.094  6149  6212 W jxcore-log: Starting JXcore engine
,08-16 10:27:39.198  6149  6212 W jxcore-log: Platform android
08-16 10:27:39.198  6149  6212 W jxcore-log: 
08-16 10:27:39.198  6149  6212 W jxcore-log: Process ARCH arm
08-16 10:27:39.198  6149  6212 W jxcore-log: 
,08-16 10:27:39.425  6149  6212 I jxcore-log: JXcore Cordova bridge is ready!
08-16 10:27:39.425  6149  6212 I jxcore-log: 
08-16 10:27:39.425  6149  6212 W jxcore-log: JXcore engine is started
,08-16 10:27:39.430  6149  6209 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-16 10:27:39.436  6149  6149 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-16 10:27:55.183  6149  6212 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-16 10:27:55.183  6149  6212 I jxcore-log: 
,08-16 10:27:55.185  6149  6212 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-16 10:27:55.185  6149  6212 I jxcore-log: 
08-16 10:27:55.190  6149  6212 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 10:27:55.190  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 10:27:55.190  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 10:27:55.190  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 10:27:55.190  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 10:27:55.190  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 10:27:55.190  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 10:27:55.190  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 10:27:55.193  6149  6212 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 10:27:55.195  6149  6212 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-16 10:27:55.195  6149  6212 I jxcore-log: 
08-16 10:27:55.197  6149  6212 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-16 10:27:55.197  6149  6212 I jxcore-log: 
,08-16 10:27:55.533  6149  6212 I jxcore-log: Running unit tests
08-16 10:27:55.533  6149  6212 I jxcore-log: 
,08-16 10:27:55.534  6149  6212 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 10:27:55.534  6149  6212 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@469dbcf added. We now have 2 listener(s)
08-16 10:27:55.535  1037  1999 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 10:27:55.540  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 10:27:55.540  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 10:27:55.541  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 10:27:55.541  6149  6212 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 10:27:55.541  6149  6212 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3325d95c added. We now have 2 listener(s)
08-16 10:27:55.541  6149  6212 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 10:27:55.542  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 10:27:55.546  6149  6212 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 10:27:55.548  6149  6212 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 10:27:55.548  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 10:27:55.548  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 10:27:55.548  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 10:27:55.548  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 10:27:55.548  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 10:27:55.548  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 10:27:55.548  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 10:27:55.550  6149  6212 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 10:27:55.550  6149  6212 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 10:27:55.551  6149  6149 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 10:27:55.552  6149  6212 D ExecuteNativeTests: Running unit tests
08-16 10:28:00.071  1588  1588 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-16 10:28:00.071  1588  1588 I KeyguardUpdateMonitor: called onTimeUpdated()
08-16 10:28:00.072  1588  1588 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-16 10:28:00.072  1588  1588 I [SystemUI]Clock: called onTimeUpdated()
,08-16 10:28:00.084  1588  1588 I LgeClockWidgetControlView: called onTimeUpdated()
08-16 10:28:00.085  1588  1588 I [SystemUI]DateView: called onTimeUpdated()
,08-16 10:28:00.087  1588  1588 I [SystemUI]DateView: called onTimeUpdated()
08-16 10:28:00.088  1588  1588 D KeyguardUpdateMonitor: handleTimeUpdate
,08-16 10:28:00.697  6149  6212 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 10:28:00.697  6149  6212 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3963c0ea added. We now have 3 listener(s)
,08-16 10:28:00.703  1037  1901 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 10:28:00.711  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 10:28:00.711  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 10:28:00.712  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 10:28:00.712  6149  6212 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 10:28:00.712  6149  6212 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@333c9fdb added. We now have 3 listener(s)
08-16 10:28:00.712  6149  6212 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 10:28:00.717  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 10:28:00.721  6149  6212 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 10:28:00.724  6149  6212 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 10:28:00.724  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 10:28:00.724  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 10:28:00.724  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 10:28:00.724  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 10:28:00.724  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 10:28:00.724  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 10:28:00.724  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 10:28:00.727  6149  6212 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 10:28:00.731  6149  6212 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 10:28:00.733  6149  6149 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 10:28:00.738  6149  6212 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-16 10:28:00.741  6149  6212 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-16 10:28:00.743  6149  6212 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 10:28:00.743  6149  6212 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 10:28:00.746  6149  6212 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-16 10:28:00.749  6149  6212 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-16 10:28:00.749  6149  6212 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 10:28:00.750  6149  6212 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 10:28:00.750  6149  6212 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 10:28:00.750  6149  6212 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 10:28:00.751  6149  6212 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 10:28:00.752  6149  6212 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 10:28:00.752  6149  6212 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 10:28:00.753  6149  6212 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 10:28:00.753  6149  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:28:00.753  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 10:28:00.753  6149  6212 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 10:28:00.754  6149  6212 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3963c0ea removed from the list
08-16 10:28:00.754  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:28:00.754  6149  6212 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@333c9fdb removed from the list
08-16 10:28:00.754  6149  6212 D io.jxcore.node.ConnectivityMonitor: stop
08-16 10:28:00.754  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 10:28:00.759  6149  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:28:00.759  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:28:00.760  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 10:28:00.760  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 10:28:00.760  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:28:00.760  6149  6212 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@333c9fdb not in the list
08-16 10:28:00.763  6149  6212 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-16 10:28:00.764  6149  6212 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 10:28:00.764  6149  6212 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 10:28:00.764  6149  6212 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 10:28:00.764  6149  6212 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 10:28:00.764  6149  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:28:00.765  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:28:00.765  6149  6212 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3963c0ea not in the list
08-16 10:28:00.765  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:28:00.765  6149  6212 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@333c9fdb not in the list
08-16 10:28:00.765  6149  6212 D io.jxcore.node.ConnectivityMonitor: stop
08-16 10:28:00.765  6149  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:28:00.765  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:28:00.765  6149  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:28:00.765  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:28:00.766  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 10:28:00.766  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 10:28:00.766  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:28:00.766  6149  6212 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@333c9fdb not in the list
,08-16 10:28:00.777  6149  6212 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-16 10:28:00.777  6149  6212 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-16 10:28:00.777  6149  6212 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-16 10:28:00.777  6149  6212 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-16 10:28:00.777  6149  6212 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-16 10:28:00.777  6149  6212 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-16 10:28:00.777  6149  6212 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-16 10:28:00.777  6149  6212 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-16 10:28:00.777  6149  6212 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-16 10:28:00.778  6149  6212 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-16 10:28:00.778  6149  6212 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-16 10:28:00.778  6149  6212 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-16 10:28:00.778  6149  6212 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-16 10:28:00.778  6149  6212 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-16 10:28:00.778  6149  6212 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-16 10:28:00.778  6149  6212 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-16 10:28:00.778  6149  6212 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-16 10:28:00.778  6149  6212 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-16 10:28:00.778  6149  6212 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-16 10:28:00.778  6149  6212 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-16 10:28:00.778  6149  6212 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-16 10:28:00.778  6149  6212 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-16 10:28:00.778  6149  6212 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-16 10:28:00.778  6149  6212 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-16 10:28:00.778  6149  6212 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-16 10:28:00.778  6149  6212 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-16 10:28:00.778  6149  6212 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 3,5:2510:2510:2510:2510:2510]
08-16 10:28:00.778  6149  6212 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-16 10:28:00.778  6149  6212 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-16 10:28:00.778  6149  6212 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-16 10:28:00.778  6149  6212 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-16 10:28:00.779  6149  6212 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 10:28:00.779  6149  6212 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 10:28:00.779  6149  6212 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 10:28:00.780  6149  6212 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 10:28:00.780  6149  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:28:00.780  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 10:28:00.780  6149  6212 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3963c0ea not in the list
08-16 10:28:00.780  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:28:00.781  6149  6212 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@333c9fdb not in the list
08-16 10:28:00.781  6149  6212 D io.jxcore.node.ConnectivityMonitor: stop
08-16 10:28:00.781  6149  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:28:00.781  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 10:28:00.781  6149  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:28:00.781  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:28:00.782  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 10:28:00.782  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 10:28:00.782  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:28:00.782  6149  6212 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@333c9fdb not in the list,
08-16 10:28:00.783  6149  6212 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-16 10:28:00.786  6149  6212 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 10:28:00.796  6149  6212 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 10:28:00.796  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 10:28:00.796  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 10:28:00.796  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 10:28:00.796  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 10:28:00.796  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 10:28:00.796  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 10:28:00.796  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 10:28:00.798  6149  6212 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 10:28:00.798  6149  6212 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 10:28:00.800  6149  6149 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 10:28:00.801  6149  6212 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 10:28:00.801  6149  6212 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 10:28:00.801  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 10:28:00.801  6149  6212 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 10:28:00.801  6149  6212 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 10:28:00.806  6149  6212 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-16 10:28:00.807  1037  1053 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 10:28:00.813  6149  6212 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 10:28:00.822  6149  6212 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-16 10:28:00.825  6149  6212 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
08-16 10:28:00.827  6149  6212 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-16 10:28:00.828  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 10:28:00.831  6149  6212 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-16 10:28:00.832  6149  6212 I io.jxcore.node.ConnectionHelper: start: OK
08-16 10:28:05.843  6149  6212 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 10:28:05.843  6149  6212 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 10:28:05.844  6149  6212 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 10:28:05.849  6149  6212 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 10:28:05.849  6149  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:28:05.849  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 10:28:05.849  6149  6212 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3963c0ea not in the list
08-16 10:28:05.850  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:28:05.850  6149  6212 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@333c9fdb not in the list
08-16 10:28:05.850  6149  6212 D io.jxcore.node.ConnectivityMonitor: stop
08-16 10:28:05.850  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:28:10.851  6149  6212 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-16 10:28:10.864  6149  6212 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 10:28:10.869  6149  6212 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 10:28:10.869  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 10:28:10.869  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 10:28:10.869  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 10:28:10.869  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 10:28:10.869  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 10:28:10.869  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 10:28:10.869  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 10:28:10.873  6149  6212 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 10:28:10.873  6149  6212 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 10:28:10.874  6149  6149 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 10:28:10.874  6149  6212 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 10:28:10.874  6149  6212 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 10:28:10.875  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 10:28:10.875  6149  6212 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 10:28:10.875  6149  6212 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 10:28:10.880  6149  6212 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 10:28:10.880  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 10:28:10.883  6149  6212 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-16 10:28:10.884  6149  6212 I io.jxcore.node.ConnectionHelper: start: OK
08-16 10:28:10.887  6149  6212 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 10:28:10.887  6149  6212 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 10:28:10.887  6149  6212 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 10:28:10.887  6149  6212 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 10:28:10.887  6149  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:28:10.887  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 10:28:10.888  6149  6212 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3963c0ea not in the list
08-16 10:28:10.888  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:28:10.888  6149  6212 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@333c9fdb not in the list
08-16 10:28:10.888  6149  6212 D io.jxcore.node.ConnectivityMonitor: stop
08-16 10:28:10.888  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:28:10.888  6149  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:28:10.888  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:28:10.889  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 10:28:10.889  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 10:28:10.892  6149  6212 D BluetoothLeScanner: could not find callback wrapper
08-16 10:28:10.892  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 10:28:10.892  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:28:10.892  6149  6212 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@333c9fdb not in the list
08-16 10:28:10.893  6149  6212 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-16 10:28:10.896  6149  6212 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 10:28:10.901  6149  6212 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 10:28:10.901  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 10:28:10.901  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 10:28:10.901  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 10:28:10.901  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 10:28:10.901  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 10:28:10.901  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 10:28:10.901  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 10:28:10.903  6149  6212 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 10:28:10.903  6149  6212 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 10:28:10.904  6149  6149 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 10:28:10.905  6149  6212 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 10:28:10.905  6149  6212 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 10:28:10.905  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 10:28:10.905  6149  6212 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 10:28:10.905  6149  6212 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 10:28:10.911  6149  6212 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-16 10:28:10.913  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 10:28:10.915  6149  6212 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-16 10:28:10.916  6149  6212 I io.jxcore.node.ConnectionHelper: start: OK
08-16 10:28:15.023  1037  3452 I LocationManagerService: remove 1747d70d
08-16 10:28:15.024  1037  3452 D LocationManagerService: provider request: passive ProviderRequest[ON interval=0]
08-16 10:28:15.025  1037  3452 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-16 10:28:15.032  1037  3452 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
08-16 10:28:15.034  1037  3452 D LocationManagerService: getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
08-16 10:28:15.037  1037  3452 D LocationManagerService: getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,08-16 10:28:15.916  6149  6212 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 10:28:15.916  6149  6212 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 10:28:15.916  6149  6212 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 10:28:20.926  6149  6212 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 10:28:20.926  6149  6212 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 10:28:20.926  6149  6212 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 10:28:20.932  6149  6212 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 10:28:20.932  6149  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:28:20.934  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 10:28:20.935  6149  6212 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3963c0ea not in the list
08-16 10:28:20.935  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:28:20.935  6149  6212 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@333c9fdb not in the list
08-16 10:28:20.935  6149  6212 D io.jxcore.node.ConnectivityMonitor: stop
08-16 10:28:20.938  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:28:20.940  6149  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:28:20.940  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:28:20.942  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 10:28:20.942  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 10:28:20.945  6149  6212 D BluetoothLeScanner: could not find callback wrapper
08-16 10:28:20.945  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 10:28:20.945  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:28:20.945  6149  6212 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@333c9fdb not in the list
08-16 10:28:20.946  6149  6212 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-16 10:28:20.946  6149  6212 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 10:28:20.946  6149  6212 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 10:28:20.946  6149  6212 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 10:28:20.947  6149  6212 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 10:28:20.947  6149  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:28:20.947  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:28:20.947  6149  6212 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3963c0ea not in the list
08-16 10:28:20.947  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:28:20.947  6149  6212 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@333c9fdb not in the list
08-16 10:28:20.947  6149  6212 D io.jxcore.node.ConnectivityMonitor: stop
08-16 10:28:20.947  6149  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:28:20.947  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:28:20.947  6149  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:28:20.947  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:28:20.949  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 10:28:20.949  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 10:28:20.949  6149  6212 D BluetoothLeScanner: could not find callback wrapper
08-16 10:28:20.949  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 10:28:20.949  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:28:20.949  6149  6212 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@333c9fdb not in the list
08-16 10:28:20.951  6149  6212 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-16 10:28:20.951  6149  6212 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 10:28:20.951  6149  6212 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 10:28:20.951  6149  6212 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 10:28:20.952  6149  6212 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 10:28:20.952  6149  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:28:20.952  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:28:20.952  6149  6212 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3963c0ea not in the list
08-16 10:28:20.952  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:28:20.952  6149  6212 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@333c9fdb not in the list
08-16 10:28:20.952  6149  6212 D io.jxcore.node.ConnectivityMonitor: stop
08-16 10:28:20.952  6149  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:28:20.952  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:28:20.952  6149  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:28:20.952  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:28:20.955  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 10:28:20.955  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 10:28:20.960  6149  6212 D BluetoothLeScanner: could not find callback wrapper
08-16 10:28:20.960  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 10:28:20.960  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:28:20.960  6149  6212 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@333c9fdb not in the list
08-16 10:28:20.961  6149  6212 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-16 10:28:20.961  6149  6212 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 10:28:20.961  6149  6212 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 10:28:20.961  6149  6212 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 10:28:20.962  6149  6212 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 10:28:20.962  6149  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:28:20.962  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:28:20.962  6149  6212 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3963c0ea not in the list
08-16 10:28:20.962  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:28:20.962  6149  6212 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@333c9fdb not in the list
08-16 10:28:20.962  6149  6212 D io.jxcore.node.ConnectivityMonitor: stop
08-16 10:28:20.962  6149  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:28:20.962  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:28:20.962  6149  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:28:20.962  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:28:20.964  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 10:28:20.964  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 10:28:20.965  6149  6212 D BluetoothLeScanner: could not find callback wrapper
08-16 10:28:20.965  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 10:28:20.965  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:28:20.965  6149  6212 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@333c9fdb not in the list
08-16 10:28:20.967  6149  6212 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-16 10:28:20.967  6149  6212 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 10:28:20.967  6149  6212 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 10:28:20.967  6149  6212 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 10:28:20.967  6149  6212 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 10:28:20.967  6149  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:28:20.967  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:28:20.968  6149  6212 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3963c0ea not in the list
08-16 10:28:20.968  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:28:20.968  6149  6212 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@333c9fdb not in the list
08-16 10:28:20.968  6149  6212 D io.jxcore.node.ConnectivityMonitor: stop
08-16 10:28:20.968  6149  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:28:20.968  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:28:20.968  6149  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:28:20.968  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 10:28:20.973  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 10:28:20.973  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 10:28:20.974  6149  6212 D BluetoothLeScanner: could not find callback wrapper
08-16 10:28:20.974  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 10:28:20.974  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:28:20.974  6149  6212 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@333c9fdb not in the list
08-16 10:28:20.976  6149  6212 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-16 10:28:20.979  6149  6212 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 10:28:20.979  6149  6212 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 10:28:20.979  6149  6212 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-16 10:28:20.979  6149  6212 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 10:28:20.980  6149  6212 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-16 10:28:20.984  6149  6212 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-16 10:28:20.984  6149  6212 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 10:28:20.984  6149  6212 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 10:28:20.984  6149  6212 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 10:28:20.984  6149  6212 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 10:28:20.984  6149  6212 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 10:28:20.985  6149  6212 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 10:28:20.985  6149  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:28:20.985  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:28:20.985  6149  6212 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3963c0ea not in the list
08-16 10:28:20.985  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:28:20.985  6149  6212 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@333c9fdb not in the list
08-16 10:28:20.986  6149  6212 D io.jxcore.node.ConnectivityMonitor: stop
08-16 10:28:20.986  6149  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:28:20.986  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:28:20.986  6149  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:28:20.986  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:28:20.988  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 10:28:20.988  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 10:28:20.992  6149  6212 D BluetoothLeScanner: could not find callback wrapper
08-16 10:28:20.992  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 10:28:20.992  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:28:20.992  6149  6212 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@333c9fdb not in the list
08-16 10:28:20.993  6149  6212 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 10:28:20.994  6149  6212 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-16 10:28:20.994  6149  6212 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-16 10:28:21.004  6149  6212 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 10:28:21.004  6149  6212 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-16 10:28:21.004  6149  6212 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-16 10:28:21.004  6149  6212 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-16 10:28:21.004  6149  6212 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-16 10:28:21.004  6149  6212 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-16 10:28:21.004  6149  6212 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-16 10:28:21.004  6149  6212 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-16 10:28:21.004  6149  6212 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-16 10:28:21.004  6149  6212 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-16 10:28:21.004  6149  6212 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-16 10:28:21.004  6149  6212 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-16 10:28:21.004  6149  6212 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-16 10:28:21.004  6149  6212 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-16 10:28:21.004  6149  6212 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-16 10:28:21.005  6149  6212 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-16 10:28:21.005  6149  6212 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-16 10:28:21.005  6149  6212 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-16 10:28:21.005  6149  6212 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-16 10:28:21.005  6149  6212 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-16 10:28:21.005  6149  6212 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-16 10:28:21.005  6149  6212 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-16 10:28:21.005  6149  6212 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-16 10:28:21.005  6149  6212 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-16 10:28:21.005  6149  6212 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-16 10:28:21.007  6149  6212 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-16 10:28:21.007  6149  6212 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-16 10:28:21.007  6149  6212 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-16 10:28:21.007  6149  6212 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-16 10:28:21.007  6149  6212 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-16 10:28:21.007  6149  6212 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-16 10:28:21.007  6149  6212 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-16 10:28:21.007  6149  6212 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-16 10:28:21.007  6149  6212 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 10:28:21.007  6149  6212 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-16 10:28:21.008  6149  6212 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 10:28:21.008  6149  6212 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 10:28:21.008  6149  6212 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-16 10:28:21.008  6149  6212 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 10:28:21.008  6149  6212 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 10:28:21.008  6149  6212 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,08-16 10:28:21.016  6149  6212 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-16 10:28:21.017  6149  6212 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-16 10:28:21.018  6149  6212 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-16 10:28:21.018  6149  6212 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-16 10:28:21.019  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-16 10:28:21.019  6149  6212 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-16 10:28:21.019  6149  6212 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 10:28:21.019  6149  6212 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-16 10:28:21.019  6149  6212 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 10:28:21.020  6149  6212 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 10:28:21.020  6149  6212 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 10:28:21.022  6149  6218 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 761)
,08-16 10:28:21.028  6149  6212 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 10:28:21.028  6149  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:28:21.028  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:28:21.029  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-16 10:28:21.030  6149  6212 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3963c0ea not in the list
08-16 10:28:21.030  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:28:21.030  6149  6212 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@333c9fdb not in the list
08-16 10:28:21.030  6149  6212 D io.jxcore.node.ConnectivityMonitor: stop
08-16 10:28:21.030  6149  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:28:21.030  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:28:21.030  6149  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:28:21.030  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:28:21.032  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 10:28:21.032  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 10:28:21.033  6149  6212 D BluetoothLeScanner: could not find callback wrapper
08-16 10:28:21.033  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 10:28:21.033  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:28:21.033  6149  6212 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@333c9fdb not in the list
08-16 10:28:21.034  6149  6212 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-16 10:28:21.034  6149  6212 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 10:28:21.034  6149  6212 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 10:28:21.034  6149  6212 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 10:28:21.035  6149  6212 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 10:28:21.035  6149  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:28:21.035  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:28:21.035  6149  6212 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3963c0ea not in the list
08-16 10:28:21.035  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:28:21.035  6149  6212 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@333c9fdb not in the list
08-16 10:28:21.035  6149  6212 D io.jxcore.node.ConnectivityMonitor: stop
08-16 10:28:21.035  6149  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:28:21.035  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:28:21.035  6149  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:28:21.035  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:28:21.046  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 10:28:21.046  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 10:28:21.051  6149  6212 D BluetoothLeScanner: could not find callback wrapper
08-16 10:28:21.051  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 10:28:21.051  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:28:21.051  6149  6212 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@333c9fdb not in the list
08-16 10:28:21.053  6149  6212 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-16 10:28:21.054  6149  6212 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 10:28:21.054  6149  6212 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 10:28:21.054  6149  6212 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 10:28:21.055  6149  6219 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 761
08-16 10:28:21.055  6149  6219 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 761)
08-16 10:28:21.055  6149  6219 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 761)
08-16 10:28:21.055  6149  6212 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 10:28:21.056  6149  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:28:21.056  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:28:21.056  6149  6212 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3963c0ea not in the list
08-16 10:28:21.056  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:28:21.056  6149  6212 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@333c9fdb not in the list
08-16 10:28:21.056  6149  6212 D io.jxcore.node.ConnectivityMonitor: stop
08-16 10:28:21.056  6149  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:28:21.056  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:28:21.056  6149  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:28:21.056  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:28:21.057  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 10:28:21.057  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 10:28:21.059  6149  6212 D BluetoothLeScanner: could not find callback wrapper
08-16 10:28:21.059  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 10:28:21.059  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:28:21.059  6149  6212 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@333c9fdb not in the list
08-16 10:28:21.060  6149  6212 D io.jxcore.node.ConnectionHelper: disconnectOutgoin,gConnection: Trying to close connection to peer with ID randomString
08-16 10:28:21.060  6149  6212 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-16 10:28:21.060  6149  6212 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 10:28:21.060  6149  6212 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-16 10:28:21.060  6149  6212 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-16 10:28:21.060  6149  6212 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-16 10:28:21.060  6149  6212 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 10:28:21.060  6149  6212 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-16 10:28:21.061  6149  6212 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-16 10:28:21.061  6149  6212 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-16 10:28:21.061  6149  6212 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 10:28:21.061  6149  6212 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-16 10:28:21.061  6149  6212 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 10:28:21.061  6149  6212 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 10:28:21.061  6149  6212 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 10:28:21.067  6149  6212 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 10:28:21.067  6149  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:28:21.067  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:28:21.067  6149  6212 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3963c0ea not in the list
08-16 10:28:21.067  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:28:21.067  6149  6212 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@333c9fdb not in the list
08-16 10:28:21.067  6149  6212 D io.jxcore.node.ConnectivityMonitor: stop
08-16 10:28:21.067  6149  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:28:21.067  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:28:21.067  6149  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:28:21.067  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:28:21.096  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 10:28:21.096  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 10:28:21.096  6149  6212 D BluetoothLeScanner: could not find callback wrapper
08-16 10:28:21.096  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 10:28:21.097  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:28:21.097  6149  6212 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@333c9fdb not in the list
08-16 10:28:21.097  6149  6212 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 10:28:21.098  6149  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:28:21.098  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:28:21.098  6149  6212 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3963c0ea not in the list
08-16 10:28:21.098  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:28:21.098  6149  6212 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@333c9fdb not in the list
08-16 10:28:21.098  6149  6212 D io.jxcore.node.ConnectivityMonitor: stop
08-16 10:28:21.098  6149  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:28:21.098  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 10:28:21.171  6149  6218 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
08-16 10:28:21.173  6149  6218 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 761)
,08-16 10:28:26.099  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:28:26.099  6149  6212 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@333c9fdb not in the list
08-16 10:28:26.100  6149  6212 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 10:28:26.100  6149  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:28:26.100  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:28:26.100  6149  6212 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3963c0ea not in the list
08-16 10:28:26.100  6149  6212 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 10:28:26.100  6149  6212 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 10:28:26.101  6149  6212 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 10:28:26.110  6149  6212 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 10:28:26.110  6149  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:28:26.110  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:28:26.110  6149  6212 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3963c0ea not in the list
08-16 10:28:26.110  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:28:26.110  6149  6212 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@333c9fdb not in the list
08-16 10:28:26.110  6149  6212 D io.jxcore.node.ConnectivityMonitor: stop
08-16 10:28:26.111  6149  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:28:26.111  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:28:26.111  6149  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:28:26.111  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:28:26.116  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 10:28:26.116  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 10:28:26.119  6149  6212 D BluetoothLeScanner: could not find callback wrapper
08-16 10:28:26.119  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 10:28:26.119  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:28:26.119  6149  6212 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@333c9fdb not in the list
08-16 10:28:26.122  6149  6212 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-16 10:28:26.123  6149  6212 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 10:28:26.124  6149  6212 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-16 10:28:26.124  6149  6212 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-16 10:28:26.125  6149  6212 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-16 10:28:26.125  6149  6149 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-16 10:28:26.126  6149  6212 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-16 10:28:26.126  6149  6212 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 10:28:26.127  6149  6212 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 10:28:26.127  6149  6212 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-16 10:28:26.127  6149  6212 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-16 10:28:26.127  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-16 10:28:26.127  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:28:26.127  6149  6212 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-16 10:28:26.129  6149  6228 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-16 10:28:26.129  6149  6228 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,08-16 10:28:26.133  6149  6149 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-16 10:28:26.133  6149  6212 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3963c0ea not in the list
08-16 10:28:26.134  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:28:26.134  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 10:28:26.134  6149  6212 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 10:28:26.134  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 10:28:26.136  6149  6212 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 10:28:26.137  6149  6212 D BluetoothLeScanner: could not find callback wrapper
08-16 10:28:26.137  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 10:28:26.137  6149  6212 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 10:28:26.138  6149  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:28:26.138  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:28:26.139  6149  6212 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 10:28:26.139  6149  6149 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 10:28:26.139  6149  6149 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-16 10:28:26.139  6149  6149 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 10:28:26.140  6149  6149 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 10:28:26.140  6149  6212 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@333c9fdb not in the list
08-16 10:28:26.140  6149  6212 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 10:28:26.140  6149  6212 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 10:28:26.140  6149  6212 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 10:28:26.141  6149  6212 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 10:28:26.141  6149  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:28:26.141  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:28:26.141  6149  6212 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3963c0ea not in the list
08-16 10:28:26.141  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:28:26.141  6149  6212 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@333c9fdb not in the list
08-16 10:28:26.141  6149  6212 D io.jxcore.node.ConnectivityMonitor: stop
08-16 10:28:26.141  6149 , 6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:28:26.141  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:28:26.141  6149  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:28:26.141  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:28:26.142  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 10:28:26.142  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 10:28:26.142  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:28:26.142  6149  6212 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@333c9fdb not in the list
08-16 10:28:26.144  6149  6212 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,08-16 10:28:26.149  6149  6212 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-16 10:28:26.149  6149  6212 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 10:28:26.151  6149  6212 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 10:28:26.151  6149  6212 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 10:28:26.152  6149  6212 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 10:28:26.152  6149  6212 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 10:28:26.152  6149  6212 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 10:28:26.153  6149  6212 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 10:28:26.153  6149  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:28:26.153  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:28:26.153  6149  6212 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3963c0ea not in the list
08-16 10:28:26.154  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:28:26.154  6149  6212 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@333c9fdb not in the list
08-16 10:28:26.154  6149  6212 D io.jxcore.node.ConnectivityMonitor: stop
08-16 10:28:26.154  6149  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:28:26.154  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:28:26.154  6149  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:28:26.154  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:28:26.156  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 10:28:26.156  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 10:28:26.156  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:28:26.156  6149  6212 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@333c9fdb not in the list
,08-16 10:28:26.164  1037  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 10:28:26.165  1037  2037 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 10:28:26.167  1037  1703 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 10:28:26.168  6149  6212 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 10:28:26.168  6149  6212 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 10:28:26.168  6149  6212 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 10:28:26.168  6149  6212 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 10:28:26.168  6149  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:28:26.168  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:28:26.168  6149  6212 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3963c0ea not in the list
08-16 10:28:26.168  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:28:26.169  6149  6212 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@333c9fdb not in the list
08-16 10:28:26.169  6149  6212 D io.jxcore.node.ConnectivityMonitor: stop
08-16 10:28:26.169  6149  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:28:26.169  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:28:26.169  6149  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:28:26.169  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:28:26.171  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 10:28:26.171  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 10:28:26.171  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:28:26.171  6149  6212 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@333c9fdb not in the list
08-16 10:28:26.172  6149  6212 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 10:28:26.172  6149  6212 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 10:28:26.172  6149  6212 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 10:28:26.175  6149  6212 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 10:28:26.175  6149  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:28:26.176  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:28:26.176  6149  6212 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3963c0ea not in the list
08-16 10:28:26.176  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:28:26.176  6149  6212 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@333c9fdb not in the list
08-16 10:28:26.176  6149  6212 D io.jxcore.node.ConnectivityMonitor: stop
08-16 10:28:26.176  6149  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:28:26.176  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:28:26.176  6149  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:28:26.176  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:28:26.177  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 10:28:26.177  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 10:28:26.177  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:28:26.178  6149  6212 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@333c9fdb not in the list
08-16 10:28:26.460  1037  1365 D PowerManagerServiceEx: acquireWakeLockInternal: lock=479019197, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,08-16 10:28:26.511  2597  2597 D [Concierge]Service: onStartCommand(). Type : 9
,08-16 10:28:26.549  1037  1037 D PowerManagerServiceEx: releaseWakeLockInternal: lock=479019197 [*alarm*], flags=0x0
,08-16 10:28:26.640  6149  6149 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-16 10:28:31.182  6149  6212 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-16 10:28:31.182  6149  6212 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 10:28:31.183  6149  6212 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-16 10:28:31.184  6149  6212 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 10:28:31.184  6149  6212 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-16 10:28:31.184  6149  6212 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-16 10:28:31.199  6149  6212 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-16 10:28:31.200  6149  6212 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-16 10:28:31.203  6149  6212 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-16 10:28:31.203  6149  6212 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-16 10:28:31.204  6149  6212 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-16 10:28:31.204  6149  6212 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-16 10:28:31.204  6149  6212 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-16 10:28:31.204  6149  6212 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-16 10:28:31.209  6149  6212 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-16 10:28:31.209  6149  6212 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-16 10:28:31.210  6149  6212 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-16 10:28:31.210  6149  6212 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-16 10:28:31.210  6149  6212 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-16 10:28:31.210  6149  6212 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,08-16 10:28:36.212  6149  6212 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 10:28:36.213  6149  6212 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7aaa090 added. We now have 3 listener(s)
08-16 10:28:36.213  6149  6212 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 10:28:36.225  6149  6212 D BluetoothAdapter: enable(): BT is already enabled..!
08-16 10:28:36.228  1037  1873 D WifiServiceImplEx: setWifiEnabled: true pid=6149, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-16 10:28:36.230  1037  1873 D WifiService: setWifiEnabled: true pid=6149, uid=10118
08-16 10:28:36.230  1037  1873 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 10:28:41.236  6149  6212 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 10:28:41.237  6149  6212 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3ff26d89 added. We now have 4 listener(s)
08-16 10:28:41.237  6149  6212 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 10:28:41.257  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:28:41.257  6149  6212 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3ff26d89 removed from the list
08-16 10:28:41.257  6149  6212 D io.jxcore.node.ConnectivityMonitor: stop
08-16 10:28:41.257  6149  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:28:41.257  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:28:41.260  6149  6212 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 10:28:41.260  6149  6212 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@188e918e added. We now have 4 listener(s)
08-16 10:28:41.260  6149  6212 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 10:28:41.269  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:28:41.269  6149  6212 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@188e918e removed from the list
08-16 10:28:41.269  6149  6212 D io.jxcore.node.ConnectivityMonitor: stop
08-16 10:28:41.269  6149  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:28:41.269  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:28:41.270  6149  6212 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 10:28:41.270  6149  6212 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6e16daf added. We now have 4 listener(s)
08-16 10:28:41.270  6149  6212 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 10:28:41.273  1037  1873 D WifiServiceImplEx: setWifiEnabled: false pid=6149, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-16 10:28:41.273  1037  1873 D WifiService: setWifiEnabled: false pid=6149, uid=10118
08-16 10:28:41.273  1037  1873 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 10:28:41.293  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 10:28:41.293  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 10:28:41.294  1037  1037 D Ulp_jni : JNI:system_update. Event-4
08-16 10:28:41.296  1037  1523 E WifiStateMachine:  DisconnectedState CMD_STOP_SUPPLICANT 0 0
08-16 10:28:41.296  1037  1523 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-16 10:28:41.296  1037  1523 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-16 10:28:41.297  1037  1523 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-16 10:28:41.298  1037  1037 D WifiScanningService: SCAN_AVAILABLE : 1
08-16 10:28:41.298  1037  1541 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-16 10:28:41.299  1037  1037 D RttService: SCAN_AVAILABLE : 1
08-16 10:28:41.299  1037  1542 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-16 10:28:41.301  1037  1522 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-16 10:28:41.302  1037  1522 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-16 10:28:41.302  1037  1522 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@f947de
08-16 10:28:41.302  1037  1522 D LGWifiP2pService: P2pDisablingState
08-16 10:28:41.302  1037  1522 D LGWifiP2pService: P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-16 10:28:41.303  1037  1522 D LGWifiP2pService: p2p socket connection lost
08-16 10:28:41.303  1037  1522 D LGWifiP2pService: P2pDisabledState
,08-16 10:28:41.310  1928  1928 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-16 10:28:41.310  1928  1928 D WfdsService: WifiP2pState is changed : false
08-16 10:28:41.310  1928  2293 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-16 10:28:41.310  1928  2293 D WfdsService: Set the WFDS Monitor: false
08-16 10:28:41.312  1928  2293 D WfdsMonitor: WFDS Monitor is stopped
08-16 10:28:41.312  1928  2293 D WfdsService: STATE : WfdsDisabledState - enter
08-16 10:28:41.313  1928  2843 D CtrlSupplicant: Received on exit socket, terminate
08-16 10:28:41.313  1928  2843 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-16 10:28:41.313  1928  2843 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-16 10:28:41.313  1928  2843 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-16 10:28:41.314  1928  2295 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
,08-16 10:28:41.316  1928  2293 W WfdsService: DefaultState - msg [9445378] is not handled
08-16 10:28:41.317  1037  1523 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-16 10:28:41.318   305   906 D CommandListener: Clearing all IP addresses on wlan0
08-16 10:28:41.319  1037  1901 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 10:28:41.320  1037  1901 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@289df175 mBinding = false
08-16 10:28:41.327  1037  1037 D WifiHS20: hidePasspointNotification off =false
,08-16 10:28:41.330  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-16 10:28:41.330  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 10:28:41.335  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 10:28:41.335  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 10:28:41.336  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 10:28:41.337  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 10:28:41.342  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 10:28:41.342  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,08-16 10:28:41.344  1037  1037 D Ulp_jni : JNI:system_update. Event-4
08-16 10:28:41.348  1037  1119 D BluetoothManagerService: Message: 2
08-16 10:28:41.349  1037  1119 D BluetoothManagerService: Sending off request.
08-16 10:28:41.350  3814  3844 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-16 10:28:41.350  3814  3900 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-16 10:28:41.350  3814  3900 D BluetoothAdapterProperties: Setting state to 13
08-16 10:28:41.350  3814  3900 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-16 10:28:41.351  3814  3900 D BluetoothAdapterProperties: onBluetoothDisable()
08-16 10:28:41.351  3814  3900 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-16 10:28:41.355  3814  3905 D BluetoothAdapterProperties: Scan Mode:20
,08-16 10:28:41.357  3814  3900 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-16 10:28:41.359  3814  3900 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-16 10:28:41.360  3814  4186 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-16 10:28:41.360  3814  4186 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 10:28:41.360  3814  4186 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-16 10:28:41.360  3814  4186 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-16 10:28:41.360  3814  4186 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-16 10:28:41.360  3814  4186 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-16 10:28:41.360  3814  4186 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-16 10:28:41.360  3814  4186 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-16 10:28:41.361  3814  4189 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 10:28:41.362  3814  4250 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 10:28:41.362  3814  4251 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 10:28:41.362  3814  4253 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 10:28:41.364  3814  4012 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-16 10:28:41.364  3814  4012 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-16 10:28:41.369  3814  4012 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 10:28:41.369  3814  4012 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 10:28:41.369  3814  4012 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 10:28:41.369  3814  4012 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 10:28:41.369  3814  4012 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 10:28:41.369  3814  4012 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 10:28:41.369  3814  4012 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 10:28:41.369  3814  4012 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 10:28:41.369  3814  4012 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 10:28:41.369  3814  4012 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-16 10:28:41.369  3814  4012 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-16 10:28:41.369  3814  4012 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
,08-16 10:28:41.374  1037  1119 D BluetoothManagerService: Message: 60
08-16 10:28:41.374  1037  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-16 10:28:41.375  1037  1119 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-16 10:28:41.378  6149  6149 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 10:28:41.379  6149  6149 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 10:28:41.379  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 10:28:41.379  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 10:28:41.379  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 10:28:41.379  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 10:28:41.379  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 10:28:41.379  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 10:28:41.379  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 10:28:41.379  6149  6149 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 10:28:41.379  6149  6149 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 10:28:41.381  6149  6149 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 10:28:41.381  6149  6149 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 10:28:41.381  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 10:28:41.381  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 10:28:41.381  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 10:28:41.381  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 10:28:41.381  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 10:28:41.381  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 10:28:41.381  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 10:28:41.383  6149  6149 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 10:28:41.385  6149  6149 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 10:28:41.386  1928  1928 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-16 10:28:41.393  3814  3814 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-16 10:28:41.393  3814  3814 D BluetoothMapService: STATE_TURNING_OFF
08-16 10:28:41.394  3814  3814 V BluetoothMapService: Handler(): got msg=4
08-16 10:28:41.394  3814  3814 D BluetoothMapService: MAP Service closeService in
08-16 10:28:41.394  3814  3814 D BluetoothMapMasInstance: MAP Service shutdown
08-16 10:28:41.395  3814  3814 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-16 10:28:41.395  3814  3814 V BluetoothMapService: MAP Service closeService out
,08-16 10:28:41.403  1588  1588 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 10:28:41.404  3814  3814 V BtOppService: Receiver DISABLED_ACTION 
08-16 10:28:41.404  3814  3814 I BtOppRfcommListener: stopping Accept Thread
08-16 10:28:41.404  3814  3814 V BtOppRfcommListener: close mBtServerSocket
08-16 10:28:41.405  3814  4250 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-16 10:28:41.407  3814  3814 V BtOppRfcommListener: waiting for thread to terminate
08-16 10:28:41.407  3722  3722 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 10:28:41.407  3814  3814 V BtOppRfcommListener: done waiting for thread to terminate
,08-16 10:28:41.425  6149  6149 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 10:28:41.426  6149  6149 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 10:28:41.464  1037  1104 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6279 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-16 10:28:41.464  6149  6212 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 10:28:41.465  1037  1523 D WifiNative-p2p0: doBoolean: TERMINATE
08-16 10:28:41.466  3814  3814 V BtOppService: onDestroy
08-16 10:28:41.466  1037  1523 D WifiNative-p2p0: TERMINATE: returned true
08-16 10:28:41.466  1037  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 10:28:41.466  1037  1523 E WifiStateMachine: useWiFiOffloading() : false
08-16 10:28:41.466  1037  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-16 10:28:41.470  1037  1037 D WifiHS20: hidePasspointNotification off =false
08-16 10:28:41.470  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 10:28:41.471  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 10:28:41.471  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 10:28:41.472  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-16 10:28:41.472  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 10:28:41.474  6149  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 10:28:41.475  6149  6212 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 10:28:41.475  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 10:28:41.475  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 10:28:41.475  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 10:28:41.475  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 10:28:41.475  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 10:28:41.475  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 10:28:41.475  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 10:28:41.479  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 10:28:41.479  6149  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 10:28:41.479  6149  6212 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 10:28:41.480  6149  6212 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 10:28:41.482  6149  6149 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 10:28:41.509  1037  1945 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6296 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-16 10:28:41.515  3814  3814 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-16 10:28:41.516  1928  1928 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-16 10:28:41.516  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 10:28:41.518  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-16 10:28:41.519  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 10:28:41.519  1037  1037 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-16 10:28:41.519  6149  6149 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 10:28:41.519  6149  6149 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 10:28:41.519  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 10:28:41.519  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 10:28:41.519  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 10:28:41.519  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 10:28:41.519  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 10:28:41.519  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 10:28:41.519  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 10:28:41.520  6149  6149 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 10:28:41.520  6149  6149 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 10:28:41.522  6149  6149 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 10:28:41.522  6149  6149 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 10:28:41.522  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 10:28:41.522  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 10:28:41.522  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 10:28:41.522  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 10:28:41.522  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 10:28:41.522  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 10:28:41.522  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 10:28:41.523  6149  6149 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 10:28:41.523  6149  6149 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 10:28:41.524  6149  6149 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 10:28:41.530  6279  6279 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 10:28:41.531  6279  6279 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-16 10:28:41.531  6279  6279 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-16 10:28:41.531  6279  6279 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-16 10:28:41.532  6279  6279 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-16 10:28:41.533  6279  6279 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-16 10:28:41.558  2686  2686 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-16 10:28:41.558  2686  2686 I wpa_supplicant: monitor socket send errors count : 1
,08-16 10:28:41.558  2686  2686 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1928-2\x00 that cannot receive messages
,08-16 10:28:41.560  1037  2840 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-16 10:28:41.560  1037  2840 D WifiMonitor: Dropping event because (p2p0) is stopped
08-16 10:28:41.583  6296  6296 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-16 10:28:41.587  6296  6296 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 10:28:41.588  6296  6296 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-16 10:28:41.590  1037  1872 I ActivityManager: Killing 4851:com.android.providers.calendar/u0a14 (adj 15): empty #17
,08-16 10:28:41.607  2686  2686 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-16 10:28:41.608  1037  2840 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-16 10:28:41.608  1037  2840 E WifiMonitor: WifiMonitor:wlan0 cnt=12 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-16 10:28:41.608  1037  2840 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-16 10:28:41.608  1037  2840 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-16 10:28:41.608  2686  2686 W wpa_supplicant: USIM:  scard_deinit function
08-16 10:28:41.609  1037  1523 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=361143
08-16 10:28:41.609  1037  1523 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=361143
,08-16 10:28:41.609  1037  2840 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 10:28:41.609  1037  2840 E WifiMonitor: WifiMonitor:wlan0 cnt=13 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 10:28:41.610  1037  1523 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 13 0 rt=361145  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-16 10:28:41.610  1037  1119 D Tethering: InitialState.processMessage what=4
08-16 10:28:41.611  1037  1523 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 13 0 rt=361145  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-16 10:28:41.611  1037  1119 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-16 10:28:41.611  1037  2000 W libprocessgroup: failed to open /acct/uid_10014/pid_4851/cgroup.procs: No such file or directory
08-16 10:28:41.613  1037  1523 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-16 10:28:41.613  1037  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 10:28:41.614   305  6319 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-16 10:28:41.615  1037  1117 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-16 10:28:41.690  6279  6279 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-16 10:28:41.696  3814  3814 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-16 10:28:41.697  3814  3814 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 10:28:41.697  3814  3814 V BluetoothPbapReceiver: ***********state = 13
08-16 10:28:41.700  3814  3814 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-16 10:28:41.703  3814  3814 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 10:28:41.703  3814  3814 V BluetoothPbapService: state: 13
08-16 10:28:41.703  3814  3814 V BluetoothPbapService: Pbap Service closeService in
08-16 10:28:41.704  6279  6279 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 10:28:41.707  2179  2179 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 10:28:41.709  3814  3814 V BluetoothPbapService: successfully stopped pbap service
08-16 10:28:41.709  3814  3814 V BluetoothPbapService: Pbap Service closeService out
08-16 10:28:41.709  3814  3814 V BluetoothPbapService: Pbap Service onDestroy
08-16 10:28:41.709  3814  3814 V BluetoothPbapService: Pbap Service closeService in
08-16 10:28:41.709  3814  3814 V BluetoothPbapService: Pbap Service closeService out
08-16 10:28:41.710  3814  3814 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-16 10:28:41.718  2686  2686 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-16 10:28:41.722  1037  2840 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-16 10:28:41.722  1037  2840 E WifiMonitor: WifiMonitor:wlan0 cnt=14 dispatchEvent: CTRL-EVENT-TERMINATING 
08-16 10:28:41.723  1037  2840 D WifiMonitor: Disconnecting from the supplicant, no more events
08-16 10:28:41.724  1037  1523 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 14 0
08-16 10:28:41.738  6279  6279 D LgDataFeature: LgDataFeature() Constructor: none
08-16 10:28:41.738  6279  6279 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 10:28:41.746  6279  6279 D WiFiOffLoadBroadcast: MCCMNC not supported: null,
,08-16 10:28:41.753  1037  1119 D BluetoothManagerService: Message: 20
08-16 10:28:41.753  1037  1119 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2059ba57:true
08-16 10:28:41.789  1037  1927 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6324 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-16 10:28:41.802  1037  1119 D BluetoothManagerService: Message: 30
,08-16 10:28:41.809  1037  1119 D BluetoothManagerService: Message: 30
08-16 10:28:41.812  6279  6279 D LocalBluetoothProfileManager: Adding local MAP profile
08-16 10:28:41.814  6279  6279 D BluetoothMap: Create BluetoothMap proxy object
08-16 10:28:41.814  1037  1119 D BluetoothManagerService: Message: 30
,08-16 10:28:41.820  1037  1119 D BluetoothManagerService: Message: 30
08-16 10:28:41.823  6279  6279 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-16 10:28:41.825  6279  6279 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
08-16 10:28:41.832  1037  1523 D WifiOffDelayIfNotUsed: stopMonitoring
08-16 10:28:41.833  1037  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 10:28:41.833  1037  1523 E WifiStateMachine: useWiFiOffloading() : false
08-16 10:28:41.833  1037  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-16 10:28:41.836  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-16 10:28:41.836  1037  1527 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-16 10:28:41.836  1037  1527 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-16 10:28:41.836  1928  1928 D WfdsService: Supplicant Connection state is changed : false
08-16 10:28:41.837  1928  1928 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-16 10:28:41.837  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 10:28:41.838  2465  2465 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 10:28:41.838  1928  2293 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-16 10:28:41.839  1928  2293 D WfdsService: Set the WFDS Monitor: false
08-16 10:28:41.839  1928  2293 D WfdsMonitor: WFDS Monitor is stopped
08-16 10:28:41.840  6149  6149 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 10:28:41.841  6149  6149 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 10:28:41.842  6149  6149 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 10:28:41.854  6279  6279 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
08-16 10:28:41.860  6279  6279 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
,08-16 10:28:41.869  6279  6279 D DockEventReceiver: finishStartingService: stopping service
08-16 10:28:41.878  6279  6279 D BluetoothInputDevice: Proxy object connected
08-16 10:28:41.879  6279  6279 D HidProfile: Bluetooth service connected
,08-16 10:28:41.881  6279  6279 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 10:28:41.881  6279  6279 D PanProfile: Bluetooth service connected
08-16 10:28:41.882  6279  6279 D BluetoothMap: Proxy object connected
08-16 10:28:41.883  6279  6279 D MapProfile: Bluetooth service connected
08-16 10:28:41.883  6279  6279 D BluetoothMap: getConnectedDevices()
08-16 10:28:41.883  6279  6279 D BluetoothMap: Bluetooth is Not enabled
08-16 10:28:41.884  6279  6279 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,08-16 10:28:41.917  1037  2037 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6350 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-16 10:28:41.927  1037  2037 I ActivityManager: Killing 5710:com.google.android.partnersetup/u0a8 (adj 15): empty #17
08-16 10:28:41.967  1037  1703 W libprocessgroup: failed to open /acct/uid_10008/pid_5710/cgroup.procs: No such file or directory
,08-16 10:28:41.968  6324  6324 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-16 10:28:41.969  6324  6324 W LG Account v2.2: No ProfileInfo entries
,08-16 10:28:41.969  6324  6324 I LG Account v2.2: isEnabled: false
08-16 10:28:41.970  6324  6324 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-16 10:28:41.970  6324  6324 I Feature : [Lifetracker]Country: EU
08-16 10:28:41.970  6324  6324 I Feature : [Lifetracker]Operator: OPEN
08-16 10:28:41.970  6324  6324 I Feature : [Lifetracker]Ranking support: false
08-16 10:28:41.971  6324  6324 I Feature : [Lifetracker]Comfort support: false
08-16 10:28:41.971  6324  6324 I Feature : [Lifetracker]Accessory: true
08-16 10:28:41.971  6324  6324 I Feature : [Lifetracker]Health device: true
08-16 10:28:41.971  6324  6324 I Feature : [Lifetracker]Extra Pedometer: false
08-16 10:28:41.971  6324  6324 I Feature : [Lifetracker]Blood glucose device: false
08-16 10:28:41.972  6324  6324 I Feature : [Lifetracker]Device Number: 3
08-16 10:28:41.989  6279  6279 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-16 10:28:41.997  6279  6279 D BluetoothPermissionRequest: onReceive
08-16 10:28:42.001  6279  6279 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-16 10:28:42.012  6279  6279 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-16 10:28:42.012  6350  6350 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 10:28:42.014  1037  1927 I ActivityManager: Killing 5743:com.lge.appbox.client/u0a11 (adj 15): empty #17
,08-16 10:28:42.070  1037  1963 W libprocessgroup: failed to open /acct/uid_10011/pid_5743/cgroup.procs: No such file or directory
,08-16 10:28:42.071  3814  3814 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-16 10:28:42.071  3814  3814 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-16 10:28:42.073  6350  6350 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
08-16 10:28:42.074  3814  3814 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-16 10:28:42.079  3814  3814 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-16 10:28:42.079  3814  3814 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-16 10:28:42.081  3814  3814 V BluetoothFtpService: Ftp Service onStartCommand
08-16 10:28:42.081  3814  3814 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 10:28:42.082  3814  3814 V BluetoothFtpService: Ftp Service closeService
08-16 10:28:42.082  3814  3814 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-16 10:28:42.088  3814  3814 V BluetoothFtpService: successfully stopped ftp service
,08-16 10:28:42.089  3814  3814 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 10:28:42.089  3814  3814 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 10:28:42.089  3814  3814 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 10:28:42.089  3814  3814 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 10:28:42.089  3814  3814 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-16 10:28:42.089  3814  3814 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-16 10:28:42.090  3814  3814 V BluetoothFtpService: Ftp Service onDestroy
08-16 10:28:42.090  3814  3814 V BluetoothFtpService: Ftp Service closeService
08-16 10:28:42.091  3814  3814 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 10:28:42.091  3814  3814 V BluetoothSapService: state: 13
08-16 10:28:42.091  3814  3814 V BluetoothSapService: Stopping SAP server process
08-16 10:28:42.092  3814  3814 V BluetoothSapService: Sap Service closeSapService in
08-16 10:28:42.092  3814  3814 V BluetoothSapService: Close listen Socket : 
08-16 10:28:42.092  3814  3814 V BluetoothSapService: Close rfcomm Socket : 
08-16 10:28:42.092  3814  3814 V BluetoothSapService: Close sapd  Socket : 
08-16 10:28:42.120  6350  6350 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,08-16 10:28:42.121  6350  6350 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-16 10:28:42.121  6350  6350 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-16 10:28:42.121  6350  6350 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-16 10:28:42.122  6350  6350 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-16 10:28:42.124  6350  6350 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-16 10:28:42.129  6350  6350 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-16 10:28:42.153  1037  1927 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6376 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-16 10:28:42.155  3814  3814 V BluetoothSapService: Sap Service closeSapService out
08-16 10:28:42.155  3814  3814 V BluetoothSapService: Sap Service onDestroy
08-16 10:28:42.155  3814  3814 V BluetoothSapService: Sap Service closeSapService in
08-16 10:28:42.155  3814  3814 V BluetoothSapService: Close listen Socket : 
08-16 10:28:42.155  3814  3814 V BluetoothSapService: Close rfcomm Socket : 
08-16 10:28:42.155  3814  3814 V BluetoothSapService: Close sapd  Socket : 
08-16 10:28:42.157  3814  3814 V BluetoothSapService: Sap Service closeSapService out
08-16 10:28:42.163  6350  6350 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 10:28:42.166  6350  6350 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 10:28:42.190  6350  6350 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-16 10:28:42.193  6350  6350 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-16 10:28:42.196  6350  6350 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-16 10:28:42.197  3722  3722 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 10:28:42.203  6296  6296 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-16 10:28:42.203  6296  6296 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 10:28:42.203  6296  6296 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-16 10:28:42.219  6279  6279 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 10:28:42.228  6279  6279 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 10:28:42.229  6376  6376 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 10:28:42.236  6350  6350 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 10:28:42.237  6350  6350 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 10:28:42.239  6350  6350 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-16 10:28:42.314  1037  2037 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6396 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
08-16 10:28:42.317  1037  2037 I ActivityManager: Killing 5761:com.android.contacts/u0a19 (adj 15): empty #17
,08-16 10:28:42.372  3814  3905 D bt_hci_bdroid: cleanup
,08-16 10:28:42.373  3814  4014 I bt_lpm  : LPM is already off!!!
,08-16 10:28:42.373  3814  4012 W bt-btif : ag scb idx 1 not allocated
08-16 10:28:42.373  3814  4012 E bt-btif : BTA AG is already disabled, ignoring ...
08-16 10:28:42.373  3814  4181 I bt_userial_mct: exiting userial_read_thread
08-16 10:28:42.373  3814  4012 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 10:28:42.373  3814  4012 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 10:28:42.373  3814  4181 D bt_userial_mct: Leaving userial_evt_read_thread()
08-16 10:28:42.373  3814  4012 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 10:28:42.373  3814  4012 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 10:28:42.373  3814  4012 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 10:28:42.373  3814  4012 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 10:28:42.373  3814  4012 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 10:28:42.373  3814  4012 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 10:28:42.373  3814  4012 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 10:28:42.373  3814  4012 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 10:28:42.373  3814  4012 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 10:28:42.373  3814  4012 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 10:28:42.373  3814  4012 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 10:28:42.373  3814  4012 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 10:28:42.373  3814  4012 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 10:28:42.373  3814  4012 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 10:28:42.373  3814  4012 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 10:28:42.373  3814  4012 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 10:28:42.373  3814  3905 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-16 10:28:42.373  3814  4012 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-16 10:28:42.373  3814  4014 I bt_vendor: hw_epilog_process
08-16 10:28:42.374  3814  3905 D bt_hci_bdroid: cleanup Finalizing cleanup
08-16 10:28:42.374  3814  3905 D bt_userial_mct: userial_close
08-16 10:28:42.374  3814  3905 E bt_userial_mct: pthread_join() FAILED result:3
08-16 10:28:42.374  3814  3905 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-16 10:28:42.381  1037  1901 W libprocessgroup: failed to open /acct/uid_10019/pid_5761/cgroup.procs: No such file or directory
,08-16 10:28:42.425  3814  3905 D bt_hci_bdroid: set_power 0
08-16 10:28:42.425  3814  3905 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-16 10:28:42.425  3814  3905 I bt_vendor: bluetooth satus is on
08-16 10:28:42.426  3814  3905 I bt_vendor: bt-vendor : resetting BT status
08-16 10:28:42.426  3814  3905 I bt_vendor: Starting hciattach daemon
08-16 10:28:42.426  3814  3905 I bt_vendor: try to set false
,08-16 10:28:42.428  3814  3905 I bt_vendor: Starting hciattach daemon
08-16 10:28:42.428  3814  3905 I bt_vendor: try to set false
08-16 10:28:42.429  3814  3905 I bt_vendor: cleanup
08-16 10:28:42.430  3814  4012 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-16 10:28:42.431  3814  3905 I GKI_LINUX: GKI_exit_task 0 done
08-16 10:28:42.431  3814  3905 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-16 10:28:42.433  3814  3900 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-16 10:28:42.436  6296  6296 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 10:28:42.438  3814  3814 D HeadsetService: Received stop request...Stopping profile...
,08-16 10:28:42.440  3814  3814 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
,08-16 10:28:42.440  3814  3814 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 10:28:42.440  3814  3814 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c09d879
08-16 10:28:42.440  3814  3937 D HeadsetStateMachine: Exit Disconnected: -1
08-16 10:28:42.445  6279  6279 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-16 10:28:42.446  1838  1838 D BluetoothHeadset: Proxy object disconnected
08-16 10:28:42.446  1838  1838 D BluetoothHeadset: Proxy object disconnected
08-16 10:28:42.446  1838  1838 D BluetoothHeadset: Proxy object disconnected
08-16 10:28:42.446  1037  1037 D BluetoothHeadset: Proxy object disconnected
08-16 10:28:42.446  1037  1037 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-16 10:28:42.448  3814  3814 D A2dpService: Received stop request...Stopping profile...
08-16 10:28:42.448  3814  3997 D A2dpStateMachine: Exit Disconnected: -1
08-16 10:28:42.449  3814  3814 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-16 10:28:42.452  3814  3814 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-16 10:28:42.452  3814  3814 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 10:28:42.452  3814  3814 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c09d879
08-16 10:28:42.453  1037  1037 D BluetoothA2dp: Proxy object disconnected
08-16 10:28:42.453  1037  1037 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-16 10:28:42.454  3814  3814 D HeadsetStateMachine: Unbinding service...
08-16 10:28:42.456  3814  3814 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-16 10:28:42.456  3814  3814 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-16 10:28:42.456  3814  3814 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-16 10:28:42.456  3814  3814 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-16 10:28:42.456  3814  3814 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-16 10:28:42.456  3814  3814 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 10:28:42.456  3814  3814 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-16 10:28:42.457  3814  3814 D HidService: Received stop request...Stopping profile...
08-16 10:28:42.457  3814  3900 D BluetoothAdapterState: Stopping profile services that were post enabled
08-16 10:28:42.457  3814  3814 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c09d879
,08-16 10:28:42.458  3814  3814 D HealthService: Received stop request...Stopping profile...
08-16 10:28:42.458  3814  3814 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c09d879
08-16 10:28:42.459  3814  3814 D PanService: Received stop request...Stopping profile...
08-16 10:28:42.460  3814  3814 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c09d879
08-16 10:28:42.461  3814  3814 I BluetoothA2dpServiceJni: cleanupNative
08-16 10:28:42.461  3814  3998 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-16 10:28:42.461  3814  3814 I GKI_LINUX: GKI_exit_task 2 done
08-16 10:28:42.461  3814  3814 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-16 10:28:42.462  3814  3814 D BtGatt.DebugUtils: handleDebugAction() action=null
08-16 10:28:42.462  3814  3814 D BtGatt.GattService: Received stop request...Stopping profile...
08-16 10:28:42.462  3814  3814 D BtGatt.GattService: stop()
08-16 10:28:42.462  3814  3814 D BtGatt.AdvertiseManager: advertise clients cleared
08-16 10:28:42.463  3814  3814 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c09d879
08-16 10:28:42.464  3814  3814 D BluetoothMapService: Received stop request...Stopping profile...
08-16 10:28:42.464  3814  3814 D BluetoothMapService: stop()
08-16 10:28:42.465  3814  3814 D BluetoothMapEmailAppObserver: deinitObservers()
08-16 10:28:42.466  3814  3814 D BluetoothMapEmailAppObserver: removeReceiver()
08-16 10:28:42.466  3814  3814 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c09d879
,08-16 10:28:42.468  3814  3814 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-16 10:28:42.468  3814  3814 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-16 10:28:42.468  3814  3814 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-16 10:28:42.468  3814  3814 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-16 10:28:42.468  3814  3814 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-16 10:28:42.469  3814  3814 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,08-16 10:28:42.469  3814  3814 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-16 10:28:42.470  3814  3814 V BluetoothMapService: Handler(): got msg=4
08-16 10:28:42.470  3814  3814 D BluetoothMapService: MAP Service closeService in
08-16 10:28:42.470  3814  3814 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-16 10:28:42.470  3814  3814 V BluetoothMapService: MAP Service closeService out
08-16 10:28:42.470  3814  3900 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-16 10:28:42.471  3814  3900 D BluetoothAdapterProperties: Setting state to 10
08-16 10:28:42.471  3814  3900 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-16 10:28:42.471  1037  1119 D BluetoothManagerService: Message: 60
08-16 10:28:42.471  1037  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-16 10:28:42.471  1037  1119 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-16 10:28:42.471  3814  3814 D BluetoothMapService: cleanup()
08-16 10:28:42.471  3814  3814 D BluetoothMapService: MAP Service closeService in
08-16 10:28:42.471  3814  3814 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-16 10:28:42.471  3814  3814 V BluetoothMapService: MAP Service closeService out
08-16 10:28:42.472  3814  3900 I BluetoothAdapterState: Entering OffState
08-16 10:28:42.472  1838  2749 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 10:28:42.473  1037  1119 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 10:28:42.473  6279  6294 D BluetoothMap: onBluetoothStateChange: up=false
08-16 10:28:42.474  1037  1119 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 10:28:42.475  6279  6295 D BluetoothPan: onBluetoothStateChange on: false
08-16 10:28:42.476  1838  1854 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 10:28:42.480  1838  2749 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 10:28:42.481  6279  6294 D BluetoothPbap: onBluetoothStateChange: up=false
08-16 10:28:42.481  6279  6279 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-16 10:28:42.481  6279  6279 D BluetoothInputDevice: Proxy object disconnected
08-16 10:28:42.481  6279  6279 D HidProfile: Bluetooth service disconnected
08-16 10:28:42.488  6279  6295 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-16 10:28:42.490  1037  1119 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-16 10:28:42.490  1037  1119 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-16 10:28:42.492  1037  1119 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-16 10:28:42.492  1037  1119 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-16 10:28:42.493  1037  1119 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@289df175 mBinding = false
08-16 10:28:42.493  1037  1119 D BluetoothManagerService: Sending unbind request.
08-16 10:28:42.495  1037  1119 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
,08-16 10:28:42.497  6396  6416 W FormManager: Network not available. Please check & try again.
08-16 10:28:42.501  3814  3905 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-16 10:28:42.501  3814  3814 I GKI_LINUX: GKI_exit_task 1 done
08-16 10:28:42.501  3814  3814 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-16 10:28:42.502  3814  3814 I BluetoothServiceJni: cleanupNative: return from cleanup
08-16 10:28:42.502  3814  3814 I art     : --- WEIRD: removing null entry 246
08-16 10:28:42.502  3814  3814 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-16 10:28:42.502  3814  3814 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-16 10:28:42.504  1928  1928 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-16 10:28:42.504  1928  2114 D LGBluetoothAPIService: Message: 2
08-16 10:28:42.505  1928  2114 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@8a842 mBinding = false
08-16 10:28:42.505  1928  2114 D LGBluetoothAPIService: Sending unbind request.
08-16 10:28:42.506  1588  1588 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 10:28:42.508  6149  6149 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 10:28:42.509  6149  6149 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 10:28:42.510  6149  6149 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 10:28:42.511  1588  1588 D BluetoothAdapter: 943633624: getState() :  mService = null. Returning STATE_OFF
08-16 10:28:42.511  1588  1588 D BluetoothAdapter: 943633624: getState() :  mService = null. Returning STATE_OFF
08-16 10:28:42.512  3814  3814 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-16 10:28:42.513  6279  6279 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-16 10:28:42.513  6279  6279 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-16 10:28:42.513  6279  6279 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-16 10:28:42.513  6279  6279 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-16 10:28:42.514  6279  6279 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-16 10:28:42.515  3814  3814 I art     : System.exit called, status: 0
08-16 10:28:42.515  3814  3814 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-16 10:28:42.527  6396  6417 V FormManager: Network unavailable.
,08-16 10:28:42.528  6279  6279 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-16 10:28:42.528  6279  6279 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-16 10:28:42.528  6279  6279 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-16 10:28:42.528  6279  6279 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-16 10:28:42.528  6279  6279 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-16 10:28:42.529  6279  6279 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-16 10:28:42.530  6279  6279 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-16 10:28:42.530  6279  6279 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-16 10:28:42.530  6279  6279 D LGBluetoothEventManager: [BTUI] clear device connection state
08-16 10:28:42.533  6279  6279 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-16 10:28:42.534  1037  1963 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
08-16 10:28:42.537   316  2137 V AudioFlinger: 3814 died, releasing its sessions
08-16 10:28:42.537   316  2137 V AudioFlinger:  pid 1838 @ 0
08-16 10:28:42.537   316  2137 V AudioFlinger:  pid 3369 @ 1
08-16 10:28:42.537   316  2137 V AudioFlinger:  pid 3369 @ 2
08-16 10:28:42.539  6279  6279 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-16 10:28:42.543  4259  4259 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 10:28:42.543  4259  4259 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 10:28:42.545  4259  4259 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 10:28:42.571  1037  1052 I ActivityManager: Process com.android.bluetooth (pid 3814) has died
08-16 10:28:42.571  1037  1052 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,08-16 10:28:42.580  4259  4259 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 10:28:42.581  6396  6417 V FormManager: Network unavailable.
08-16 10:28:42.583  2179  2179 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 10:28:42.583  6279  6279 D DockEventReceiver: finishStartingService: stopping service
,08-16 10:28:42.609  4259  6428 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-16 10:28:42.618  4259  6430 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 10:28:42.619  4259  6430 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-16 10:28:42.630  6296  6296 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-16 10:28:42.630  6296  6296 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 10:28:42.630  6296  6296 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-16 10:28:42.636  6279  6279 D BluetoothPermissionRequest: onReceive
08-16 10:28:42.640  6396  6432 W FormManager: Network not available. Please check & try again.
08-16 10:28:42.649  6279  6279 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-16 10:28:42.660  6396  6433 V FormManager: Network unavailable.
,08-16 10:28:42.661  6279  6279 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 10:28:42.663  6279  6279 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-16 10:28:42.664  6279  6279 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-16 10:28:42.665  6396  6433 V FormManager: Network unavailable.
08-16 10:28:42.666  6279  6279 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-16 10:28:42.737  1037  1560 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6435 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-16 10:28:42.745  1037  1560 I ActivityManager: Killing 5637:com.android.defcontainer/u0a4 (adj 15): empty #17
,08-16 10:28:42.864  1037  1963 W libprocessgroup: failed to open /acct/uid_10004/pid_5637/cgroup.procs: No such file or directory
,08-16 10:28:42.894  6435  6435 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-16 10:28:42.895  6435  6435 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 10:28:42.895  6435  6435 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-16 10:28:42.896  6435  6435 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-16 10:28:42.904  6350  6350 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-16 10:28:42.906  6350  6350 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,08-16 10:28:42.907  6350  6350 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,08-16 10:28:42.917  6435  6435 D BluetoothAdapterApp: Loading JNI Library
08-16 10:28:42.951  6435  6435 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@242893e6 Instance Count = 1
,08-16 10:28:42.954  6350  6350 D LgDataFeature: LgDataFeature() Constructor: none
08-16 10:28:42.954  6350  6350 D LgDataFeature: LgDataFeature() Constructor Done, null
08-16 10:28:42.956  6435  6435 D BluetoothAdapterApp: onCreate
08-16 10:28:42.961  6350  6350 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-16 10:28:42.963  6350  6350 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
,08-16 10:28:42.963  6350  6350 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-16 10:28:42.963  6350  6350 V SoundPool: doLoad: loading sample sampleID=1
,08-16 10:28:42.963  6350  6350 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,08-16 10:28:42.968  6350  6454 V SoundPool: Start decode
08-16 10:28:42.968  6350  6454 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-16 10:28:42.969  6033  6033 D UEI.SmartControl: QS Service created
08-16 10:28:42.972   316  1372 V MediaPlayerService: decode(23, 10857164, 17813)
08-16 10:28:42.972   316  1372 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-16 10:28:42.972   316  1372 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-16 10:28:42.972   316  1372 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-16 10:28:42.972   316  1372 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-16 10:28:42.972   316  1372 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-16 10:28:42.972   316  1372 V MediaPlayerService: player type = 3
08-16 10:28:42.972   316  1372 V AwesomePlayer: AwesomePlayer create()
08-16 10:28:42.973  6350  6350 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-16 10:28:42.974   316  1372 V AwesomePlayer: reset_l() 
08-16 10:28:42.974   316  1372 V AwesomePlayer: cancelPlayerEvents
08-16 10:28:42.974   316  1372 V AwesomePlayer: setAudioSink() 
08-16 10:28:42.974   316  1372 V AwesomePlayer: reset_l() 
08-16 10:28:42.974   316  1372 V AudioCache: notify(0xb16a6080, 8, 0, 0)
08-16 10:28:42.974   316  1372 V AudioCache: ignored
08-16 10:28:42.974   316  1372 V AwesomePlayer: cancelPlayerEvents
08-16 10:28:42.975   316  1372 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-16 10:28:42.975   316  1372 V AwesomePlayer: setDataSource_l dataSource
08-16 10:28:42.975   316  1372 V LGParserOSAL: SniffLGParser start
08-16 10:28:42.975   316  1372 V LGParserOSAL: MainType:5, SubType=0
08-16 10:28:42.975   316  1372 V LGParserOSAL: #### check Mime : application/ogg
08-16 10:28:42.975   316  1372 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-16 10:28:42.975   316  1372 E MediaExtractor: Use LGExtractor :application/ogg 
,08-16 10:28:42.979  6350  6350 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-16 10:28:42.979  6350  6350 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-16 10:28:42.981  6033  6033 I UEI.SmartControl: Service initServices...
08-16 10:28:42.981  6033  6033 D UEI.SmartControl: QS start get config
08-16 10:28:42.987  6435  6435 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-16 10:28:42.987  6435  6435 D ProfileConfigQcom: Adding HeadsetService
08-16 10:28:42.987  6435  6435 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-16 10:28:42.988  6435  6435 D ProfileConfigQcom: Adding A2dpService
08-16 10:28:42.988  6435  6435 D ProfileConfigQcom: [BTUI] HidService is supported
08-16 10:28:42.988  6435  6435 D ProfileConfigQcom: Adding HidService
08-16 10:28:42.988  6350  6350 V LGMDMManager: Create singleton instance
08-16 10:28:42.988  6435  6435 D ProfileConfigQcom: [BTUI] HealthService is supported
08-16 10:28:42.988  6435  6435 D ProfileConfigQcom: Adding HealthService
08-16 10:28:42.989  6435  6435 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-16 10:28:42.989  6435  6435 D ProfileConfigQcom: [BTUI] PanService is supported
08-16 10:28:42.990  6435  6435 D ProfileConfigQcom: Adding PanService
08-16 10:28:42.990  6435  6435 D ProfileConfigQcom: [BTUI] GattService is supported
08-16 10:28:42.990  6435  6435 D ProfileConfigQcom: Adding GattService
08-16 10:28:42.990  6435  6435 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-16 10:28:42.990  6435  6435 D ProfileConfigQcom: Adding BluetoothMapService
08-16 10:28:42.991  6435  6435 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-16 10:28:42.993  6435  6435 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-16 10:28:42.996  6279  6279 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-16 10:28:42.999  6435  6435 V LGMDMManagerInternal: Create singleton instance
,08-16 10:28:43.020   316  1372 V LGParserOSAL: supported mime: application/ogg
08-16 10:28:43.020   316  1372 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-16 10:28:43.020   316  1372 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-16 10:28:43.020   316  1372 V AwesomePlayer: mBitrate = -1 bits/sec
08-16 10:28:43.020   316  1372 V AwesomePlayer: AudioTrack Setting
08-16 10:28:43.020   316  1372 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-16 10:28:43.020   316  1372 V AwesomePlayer: setAudioSource() 
08-16 10:28:43.020   316  1372 V MediaPlayerService: prepare
08-16 10:28:43.020   316  1372 V AwesomePlayer: prepareAsync_l() 
08-16 10:28:43.020   316  1372 V MediaPlayerService: wait for prepare
08-16 10:28:43.020   316  6456 V AwesomePlayer: onPrepareAsyncEvent() 
08-16 10:28:43.020   316  6456 V AwesomePlayer: initAudioDecoder() 
08-16 10:28:43.020   316  6456 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-16 10:28:43.020   316  6456 V AudioSystem: isOffloadSupported()
08-16 10:28:43.020   316  6456 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-16 10:28:43.020   316  6456 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-16 10:28:43.020   316  6456 I AudioFlinger: isAudioPlaybackHookOn() false
08-16 10:28:43.020   316  6456 V AwesomePlayer: getUseOffload() = 0 
08-16 10:28:43.020   316  6456 V OMXCodec: OMXCodec::Create
08-16 10:28:43.020   316  6456 V OMXCodec: findMatchingCodecs()
08-16 10:28:43.020   316  6456 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
,08-16 10:28:43.021   316  6456 V OMXCodec: matchingCodecs.size()=1
08-16 10:28:43.021   316  6456 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-16 10:28:43.022   316  6456 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-16 10:28:43.022   316  6456 V LGCodecAdapter: LG Codec Adapter start
08-16 10:28:43.022   316  6456 V OMXCodec: OMXCodec Createtor
08-16 10:28:43.022   316  6456 V OMXCodec: setComponentRole
,08-16 10:28:43.022   316  6456 V OMXCodec: configureCodec protected=0
08-16 10:28:43.022   316  6456 V LGCodecAdapter: called getLGCodecSpecificData
08-16 10:28:43.022   316  6456 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-16 10:28:43.022   316  6456 V LGCodecOSAL: Called LGconfigureCodecMETA
08-16 10:28:43.022   316  6456 V LGCodecOSAL: Called LGconfigureCodecMSG
08-16 10:28:43.022   316  6456 V LGCodecOSAL: Not support LGCodec
08-16 10:28:43.022   316  6456 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-16 10:28:43.022   316  6456 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-16 10:28:43.022   316  6456 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-16 10:28:43.022   316  6456 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-16 10:28:43.022   316  6456 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-16 10:28:43.022   316  6456 V AudioSystem: isOffloadSupported()
08-16 10:28:43.022   316  6456 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-16 10:28:43.022   316  6456 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-16 10:28:43.022   316  6456 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-16 10:28:43.022   316  6456 V OMXCodec: init()
08-16 10:28:43.022   316  6456 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-16 10:28:43.022   316  6456 V OMXCodec: allocateBuffers
08-16 10:28:43.022   316  6456 V OMXCodec: allocateBuffersOnPort portIndex=0
08-16 10:28:43.022   316  6456 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-16 10:28:43.022   316  6456 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7920 on input port
08-16 10:28:43.022   316  6456 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on input port
08-16 10:28:43.022   316  6456 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on input port
08-16 10:28:43.022   316  6456 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on input port
08-16 10:28:43.023   316  6456 V OMXCodec: allocateBuffersOnPort portIndex=1
08-16 10:28:43.023   316  6456 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-16 10:28:43.023   316  6456 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on output port
08-16 10:28:43.023   316  6456 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
08-16 10:28:43.023   316  6456 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7e70 on output port
08-16 10:28:43.023   316  6456 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7fb0 on output port
08-16 10:28:43.023   316  6456 V OMXCodec: init() mAsyncCompletion wait!!! 
08-16 10:28:43.023   316  6458 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-16 10:28:43.023   316  6458 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-16 10:28:43.024   316  6458 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-16 10:28:43.024   316  6456 V OMXCodec: init() mAsyncCompletion wait!!! 
08-16 10:28:43.024   316  6458 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-16 10:28:43.024   316  6458 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-16 10:28:43.024   316  6458 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-16 10:28:43.024   316  6456 V OMXCodec: init() mAsyncCompletion wait free! 
08-16 10:28:43.024   316  6456 V AwesomePlayer: finishAsyncPrepare_l() 
08-16 10:28:43.025   316  6456 V AudioCache: notify(0xb16a6080, 5, 0,, 0)
08-16 10:28:43.025   316  6456 V AudioCache: ignored
08-16 10:28:43.025   316  6456 V AudioCache: notify(0xb16a6080, 1, 0, 0)
08-16 10:28:43.025   316  6456 V AudioCache: prepared
08-16 10:28:43.025   316  1372 V AudioCache: wait - success
08-16 10:28:43.025   316  1372 V MediaPlayerService: start
08-16 10:28:43.025   316  1372 V AwesomePlayer: play_l() 
08-16 10:28:43.025   316  1372 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-16 10:28:43.025   316  1372 V AwesomePlayer: createAudioPlayer_l
08-16 10:28:43.025   316  1372 V AwesomePlayer: seekAudioIfNecessary_l() 
08-16 10:28:43.025   316  1372 V AwesomePlayer: startAudioPlayer_l() 
08-16 10:28:43.025   316  1372 D AudioPlayer: start of Playback, useOffload 0
08-16 10:28:43.025   316  1372 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-16 10:28:43.025   316  1372 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-16 10:28:43.030   316  6458 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-16 10:28:43.030   316  6458 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-16 10:28:43.030   316  6458 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-16 10:28:43.030   316  6458 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-16 10:28:43.030   316  6458 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-16 10:28:43.030   316  6458 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-16 10:28:43.031   316  6458 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884848
08-16 10:28:43.031   316  6458 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 10:28:43.031   316  6458 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885008
08-16 10:28:43.031   316  6458 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 10:28:43.031   316  6458 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885808
08-16 10:28:43.031   316  6458 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 10:28:43.031   316  6458 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041886128
08-16 10:28:43.031   316  6458 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 10:28:43.031   316  6458 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-16 10:28:43.031   316  6458 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-16 10:28:43.031   316  6458 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-16 10:28:43.031   316  6458 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-16 10:28:43.031   316  6458 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-16 10:28:43.031   316  6458 V OMXCodec: allocateBuffersOnPort portIndex=1
08-16 10:28:43.031   316  6458 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-16 10:28:43.031   316  6458 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7e70 on output port
08-16 10:28:43.031   316  6458 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
08-16 10:28:43.032   316  6458 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on output port
08-16 10:28:43.032   316  6458 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57bd740 on output port
08-16 10:28:43.032   316  6458 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-16 10:28:43.032   316  6458 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-16 10:28:43.032   316  1372 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-16 10:28:43.032   316  1372 V AudioCache: notify(0xb16a6080, 6, 0, 0)
08-16 10:28:43.032   316  1372 V AudioCache: ignored
08-16 10:28:43.033   316  1372 V MediaPlayerService: wait for playback complete
08-16 10:28:43.033   316  6459 V AudioCache: write(0xb17f9000, 4096)
08-16 10:28:43.033   316  6459 V AudioCache: memcpy(0xaf006000, 0xb17f9000, 4096)
08-16 10:28:43.034   316  6459 V AudioCache: write(0xb17f9000, 4096)
08-16 10:28:43.035   316  6459 V AudioCache: memcpy(0xaf007000, 0xb17f9000, 4096)
08-16 10:28:43.035   316  6459 V AudioCache: write(0xb17f9000, 4096)
08-16 10:28:43.035   316  6459 V AudioCache: memcpy(0xaf008000, 0xb17f9000, 4096)
08-16 10:28:43.035   316  6459 V AudioCache: write(0xb17f9000, 4096)
08-16 10:28:43.035   316  6459 V AudioCache: memcpy(0xaf009000, 0xb17f9000, 4096)
08-16 10:28:43.036   316  6459 V AudioCache: write(0xb17f9000, 4096)
08-16 10:28:43.036   316  6459 V AudioCache: memcpy(0xaf00a000, 0xb17f9000, 4096)
08-16 10:28:43.037   316  6459 V AudioCache: write(0xb17f9000, 4096)
08-16 10:28:43.037   316  6459 V AudioCache: memcpy(0xaf00b000, 0xb17f9000, 4096)
08-16 10:28:43.037   316  6459 V AudioCache: write(0xb17f9000, 4096)
08-16 10:28:43.037   316  6459 V AudioCache: memcpy(0xaf00c000, 0xb17f9000, 4096)
08-16 10:28:43.038   316  6459 V AudioCache: write(0xb17f9000, 4096)
08-16 10:28:43.038   316  6459 V AudioCache: memcpy(0xaf00d000, 0xb17f9000, 4096)
08-16 10:28:43.038   316  6459 V AudioCache: write(0xb17f9000, 4096)
08-16 10:28:43.038   316  6459 V AudioCache: memcpy(0xaf00e000, 0xb17f9000, 4096)
08-16 10:28:43.039   316  6459 V AudioCache: write(0xb17f9000, 4096)
08-16 10:28:43.039   316  6459 V AudioCache: memcpy(0xaf00f000, 0xb17f9000, 4096)
08-16 10:28:43.040   316  6459 V AudioCache: write(0xb17f9000, 4096)
08-16 10:28:43.040   316  6459 V AudioCache: memcpy(0xaf010000, 0xb17f9000, 4096)
08-16 10:28:43.040   316  6459 V AudioCache: write(0xb17f9000, 4096)
08-16 10:28:43.040   316  6459 V AudioCache: memcpy(0xaf011000, 0xb17f9000, 4096)
08-16 10:28:43.041   316  6459 V AudioCache: write(0xb17f9000, 4096)
08-16 10:28:43.041   316  6459 V AudioCache: memcpy(0xaf012000, 0xb17f9000, 4096)
08-16 10:28:43.042   316  6459 V AudioCache: write(0xb17f9000, 4096)
08-16 10:28:43.042   316  6459 V AudioCache: memcpy(0xaf013000, 0xb17f9000, 4096)
08-16 10:28:43.042   316  6459 V AudioCache: write(0xb17f9000, 4096)
08-16 10:28:43.042   316  6459 V AudioCache: memcpy(0xaf014000, 0xb17f9000, 4096)
08-16 10:28:43.043   316  6459 V AudioCache: write(0xb17f9000, 4096)
08-16 10:28:43.043   316  6459 V AudioCache: memcpy(0xaf015000, 0xb17f9000, 4096)
08-16 10:28:43.044   316  6459 V AudioCache: write(0xb17f9000, 4096)
08-16 10:28:43.044   316  6459 V AudioCache: memcpy(0xaf016000, 0xb17f9000, 4096)
08-16 10:28:43.044   316  6459 V AudioCache: write(0xb17f9000, 4096)
08-16 10:28:43.044   316  6459 V AudioCache: memcpy(0xaf017000, 0xb17f9000, 4096)
08-16 10:28:43.045   316  6459 V AudioCache: write(0xb17f9000, 4096)
08-16 10:28:43.045   316  6459 V AudioCache: memcpy(0xaf018000, 0xb17f9000, 4096)
08-16 10:28:43.045  6350  6350 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-16 10:28:43.046   316  6459 V AudioCache: write(0xb17f9000, 4096)
08-16 10:28:43.046   316  6459 V AudioCache: memcpy(0xaf019000, 0xb17f9000, 4096)
08-16 10:28:43.046  6350  6350 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-16 10:28:43.047   316  6459 V AudioCache: write(0xb17f9000, 4096)
08-16 10:28:43.047   316  6459 V AudioCache: memcpy(0xaf01a000, 0xb17f9000, 4096)
08-16 10:28:43.047  6350  6350 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:5322
08-16 10:28:43.048   316  6459 V AudioCache: write(0xb17f9000, 4096)
08-16 10:28:43.048   316  6459 V AudioCache: memcpy(0xaf01b000, 0xb17f9000, 4096)
08-16 10:28:43.048   316  6459 V AudioCache: write(0xb17f9000, 4096)
08-16 10:28:43.048   316  6459 V AudioCache: memcpy(0xaf01c000, 0xb17f9000, 4096)
08-16 10:28:43.049   316  6459 V AudioCache: write(0xb17f9000, 4096)
08-16 10:28:43.049   316  6459 V AudioCache: memcpy(0xaf01d000, 0xb17f9000, 4096)
08-16 10:28:43.049   316  6459 V AudioCache: write(0xb17f9000, 4096)
08-16 10:28:43.049   316  6459 V AudioCache: memcpy(0xaf01e000, 0xb17f9000, 4096)
08-16 10:28:43.050   316  6459 V AudioCache: write(0xb17f9000, 4096)
08-16 10:28:43.050   316  6459 V AudioCache: memcpy(0xaf01f000, 0xb17f9000, 4096)
08-16 10:28:43.050   316  6459 V AudioCache: write(0xb17f9000, 4096)
08-16 10:28:43.050   316  6459 V AudioCache: memcpy(0xaf020000, 0xb17f9000, 4096)
08-16 10:28:43.051   316  6459 V AudioCache: write(0xb17f9000, 4096)
08-16 10:28:43.051   316  6459 V AudioCache: memcpy(0xaf021000, 0xb17f9000, 4096)
08-16 10:28:43.051   316  6459 V AudioCache: write(0xb17f9000, 4096)
08-16 10:28:43.051   316  6459 V AudioCache: memcpy(0xaf022000, 0xb17f9000, 4096)
08-16 10:28:43.052   316  6459 V AudioCache: write(0xb17f9000, 4096)
08-16 10:28:43.052   316  6459 V AudioCache: memcpy(0xaf023000, 0xb17f9000, 4096)
08-16 10:28:43.052   316  6459 V AudioCache: write(0xb17f9000, 4096)
08-16 10:28:43.052   316  6459 V AudioCache: memcpy(0xaf024000, 0xb17f9000, 4096)
08-16 10:28:43.053   316  6459 V AudioCache: write(0xb17f9000, 4096)
08-16 10:28:43.053   316  6459 V AudioCache: memcpy(0xaf025000, 0xb17f9000, 4096)
08-16 10:28:43.053   316  6459 V AudioCache: write(0xb17f9000, 4096)
08-16 10:28:43.053   316  6459 V AudioCache: memcpy(0xaf026000, 0xb17f9000, 4096)
08-16 10:28:43.054   316  6459 V AudioCache: write(0xb17f9000, 4096)
08-16 10:28:43.054   316  6459 V AudioCache: memcpy(0xaf027000, 0xb17f9000, 4096)
08-16 10:28:43.054   316  6459 V AudioCache: write(0xb17f9000, 4096)
08-16 10:28:43.054   316  6459 V AudioCache: memcpy(0xaf028000, 0xb17f9000, 4096)
08-16 10:28:43.055   316  6459 V AudioCache: write(0xb17f9000, 4096)
08-16 10:28:43.055   316  6459 V AudioCache: memcpy(0xaf029000, 0xb17f9000, 4096)
08-16 10:28:43.056   316  6459 V AudioCache: write(0xb17f9000, 4096)
08-16 10:28:43.056   316  6459 V AudioCache: memcpy(0xaf02a000, 0xb17f9000, 4096)
08-16 10:28:43.056   316  6459 V AudioCache: write(0xb17f9000, 4096)
08-16 10:28:43.056   316  6459 V AudioCache: memcpy(0xaf02b000, 0xb17f9000, 4096)
08-16 10:28:43.056   316  6459 V AudioCache: write(0xb17f9000, 4096)
08-16 10:28:43.057   316  6459 V AudioCache: memcpy(0xaf02c000, 0xb17f9000, 4096)
08-16 10:28:43.057   316  6459 V AudioCache: write(0xb17f9000, 4096)
08-16 10:28:43.057   316  6459 V AudioCache: memcpy(0xaf02d000, 0xb17f9000, 4096)
08-16 10:28:43.057   316  6459 V AudioCache: write(0xb17f9000, 4096)
08-16 10:28:43.057   316  6459 V AudioCache: memcpy(0xaf02e000, 0xb17f9000, 4096)
08-16 10:28:43.058   316  6459 V AudioCache: write(0xb17f9000, 4096)
08-16 10:28:43.058   316  6459 V AudioCache: memcpy(0xaf02f000, 0xb17f9000, 4096)
08-16 10:28:43.058   316  6459 V AudioCache: write(0xb17f9000, 4096)
08-16 10:28:43.058   316  6459 V AudioCache: memcpy(0xaf030000, 0xb17f9000, 4096)
08-16 10:28:43.059   316  6459 V AudioCache: write(0xb17f9000, 4096)
08-16 10:28:43.059   316  6459 V AudioCache: memcpy(0xaf031000, 0xb17f9000, 4096)
08-16 10:28:43.059   316  6459 V AudioCache: write(0xb17f9000, 4096)
08-16 10:28:43.059   316  6459 V AudioCache: memcpy(0xaf032000, 0xb17f9000, 4096)
08-16 10:28:43.060   316  6459 V AudioCache: write(0xb17f9000, 4096)
08-16 10:28:43.060   316  6459 V AudioCache: memcpy(0xaf033000, 0xb17f9000, 4096)
08-16 10:28:43.060   316  6459 V AudioCache: write(0xb17f9000, 4096)
08-16 10:28:43.060   316  6459 V AudioCache: memcpy(0xaf034000, 0xb17f9000, 4096)
08-16 10:28:43.061   316  6459 V AudioCache: write(0xb17f9000, 4096)
08-16 10:28:43.061   316  6459 V AudioCache: memcpy(0xaf035000, 0xb17f9000, 4096)
08-16 10:28:43.061   316  6459 V AudioCache: write(0xb17f9000, 4096)
08-16 10:28:43.061   316  6459 V AudioCache: memcpy(0xaf036000, 0xb17f9000, 4096)
08-16 10:28:43.061   316  6459 V AudioCache: write(0xb17f9000, 4096)
08-16 10:28:43.061   316  6459 V AudioCache: memcpy(0xaf037000, 0xb17f9000, 4096)
08-16 10:28:43.062   316  6458 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-16 10:28:43.062   316  6459 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-16 10:28:43.062   316  6459 V AwesomePlayer: postAudioEOS() 
08-16 10:28:43.062   316  6459 V AudioCache: write(0xb17f9000, 280)
08-16 10:28:43.062   316  6459 V AudioCache: memcpy(0xaf038000, 0xb17f9000, 280)
08-16 10:28:43.065   316  6456 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-16 10:28:43.065   316  6456 V AwesomePlayer: onStreamDone
08-16 10:28:43.065   316  6456 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-16 10:28:43.065   316  6456 V AudioCache: notify(0xb16a6080, 2, 0, 0)
08-16 10:28:43.065   316  6456 V AudioCache: playback complete
08-16 10:28:43.065   316  6456 V AwesomePlayer: pause_l() 
08-16 10:28:43.065   316  1372 V AudioCache: wait - success
08-16 10:28:43.065   316  1372 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-16 10:28:43.066   316  6456 V AudioCache: notify(0xb16a6080, 7, 0, 0)
08-16 10:28:43.066   316  6456 V AudioCache: ignored
08-16 10:28:43.066   316  6456 V AwesomePlayer: cancelPlayerEvents
08-16 10:28:43.066   316  6456 D AudioPlayer: Pause Playback at 1068125
,08-16 10:28:43.066   316  1372 V AwesomePlayer: reset_l() 
08-16 10:28:43.066   316  1372 V AudioCache: notify(0xb16a6080, 8, 0, 0)
08-16 10:28:43.066   316  1372 V AudioCache: ignored
08-16 10:28:43.066   316  1372 V AwesomePlayer: cancelPlayerEvents
08-16 10:28:43.066   316  1372 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-16 10:28:43.066   316  1372 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-16 10:28:43.066   316  1372 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-16 10:28:43.066   316  1372 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-16 10:28:43.066   316  1372 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-16 10:28:43.066   316  6458 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-16 10:28:43.066   316  6458 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-16 10:28:43.067   316  6458 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-16 10:28:43.067   316  6458 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 0
08-16 10:28:43.067   316  6458 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-16 10:28:43.067   316  6458 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 0
08-16 10:28:43.067   316  6458 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-16 10:28:43.067   316  6458 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f79c0 on port 0
08-16 10:28:43.067   316  6458 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-16 10:28:43.067   316  6458 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7920 on port 0
08-16 10:28:43.067   316  6458 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-16 10:28:43.067   316  6458 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-16 10:28:43.067   316  6458 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57bd740 on port 1
08-16 10:28:43.067   316  6458 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-16 10:28:43.067   316  6458 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 1
08-16 10:28:43.067   316  6458 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-16 10:28:43.067   316  6458 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 1
08-16 10:28:43.067   316  6458 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-16 10:28:43.067   316  6458 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7e70 on port 1
08-16 10:28:43.067   316  6458 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 10:28:43.067   316  6458 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-16 10:28:43.068   316  1372 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-16 10:28:43.068   316  1372 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-16 10:28:43.068   316  6458 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-16 10:28:43.068   316  6458 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-16 10:28:43.068   316  6458 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-16 10:28:43.068   316  1372 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-16 10:28:43.068   316  1372 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-16 10:28:43.068   316  1372 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-16 10:28:43.069   316  1372 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-16 10:28:43.069   316  1372 D AudioPlayer: AudioPlayer releasing audio source
08-16 10:28:43.069   316  1372 D AudioPlayer: AudioPlayer done releasing audio source
08-16 10:28:43.069   316  1372 V AwesomePlayer: reset_l() 
08-16 10:28:43.069   316  1372 V AwesomePlayer: cancelPlayerEvents
08-16 10:28:43.069   316  1372 V AwesomePlayer: ~AwesomePlayer call
08-16 10:28:43.069   316  1372 V AwesomePlayer: reset_l() 
08-16 10:28:43.069   316  1372 V AwesomePlayer: cancelPlayerEvents
08-16 10:28:43.070  6350  6454 V SoundPool: close(31)
08-16 10:28:43.070  6350  6454 V SoundPool: pointer = 0xa0036000, size = 205080, sampleRate = 48000, numChannels = 2
08-16 10:28:43.071  6435  6435 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-16 10:28:43.073  6435  6435 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 10:28:43.073  6435  6435 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 10:28:43.073  6435  6435 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 10:28:43.074  6435  6435 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 10:28:43.074  6435  6435 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-16 10:28:43.078  6376  6376 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-16 10:28:43.243  6033  6033 I UEI.SmartControl: Supports setup maps: true,
,08-16 10:28:43.246  6033  6033 D UEI.SmartControl: QS start statue = true Error code = 0
08-16 10:28:43.246  6033  6033 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-16 10:28:43.247  6033  6033 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-16 10:28:43.247  6033  6033 I UEI.SmartControl: ### init IR Blaster...
08-16 10:28:43.250  6033  6033 D serial_port: Configuring serial port
08-16 10:28:43.251  6033  6033 E UEI.SmartControl: UEIBLaster setting for 616
08-16 10:28:43.251  6033  6033 I UEI.SmartControl: Setting serial record hearder size = 2
08-16 10:28:43.251  6033  6033 I UEI.SmartControl: configuring settings for MAXQ616
,08-16 10:28:43.251  6033  6033 I UEI.SmartControl: Get version...
08-16 10:28:43.269  6033  6461 D UEI.SmartControl: serial port data available: 21
,08-16 10:28:43.296  6033  6033 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-16 10:28:43.296  6033  6033 I UEI.SmartControl: IR Blaster version: 256702256704300002
,08-16 10:28:43.296  6033  6033 I UEI.SmartControl: QS saving settings...
,08-16 10:28:43.298  6033  6033 D UEI.SmartControl: IR Blaster version: 25672567
08-16 10:28:43.316  6033  6461 D UEI.SmartControl: serial port data available: 4
,08-16 10:28:43.347  6033  6467 I UEI.SmartControl: Device manager: loading config....
08-16 10:28:43.348  6033  6033 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-16 10:28:43.348  6033  6467 D UEI.SmartControl: ----------- loading internal config...
,08-16 10:28:43.352  6033  6033 E UEI.SmartControl: Services init done
08-16 10:28:43.352  6033  6033 D UEI.SmartControl: QS Service init finished
08-16 10:28:43.353  6033  6033 D UEI.SmartControl: QS Service version name: 2.1.91
08-16 10:28:43.354  6033  6033 D UEI.SmartControl: QS Service version code: 201091
08-16 10:28:43.354  6033  6033 D UEI.SmartControl: Service requested: Control
08-16 10:28:43.357  6033  6467 E UEI.SmartControl: Loading SETTINGS...
08-16 10:28:43.359  6033  6033 D UEI.SmartControl: Request IControl service: devices are loaded...
08-16 10:28:43.362  6033  6033 D UEI.SmartControl: Internal service binding...
,08-16 10:28:43.364  6350  6350 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-16 10:28:43.368  6033  6049 I UEI.SmartControl: ------ IControl API: 11
08-16 10:28:43.368  6033  6049 D UEI.SmartControl: File observer start...
08-16 10:28:43.368  6033  6467 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-16 10:28:43.369  6033  6049 E UEI.SmartControl: IR Port is disabled: false
08-16 10:28:43.369  6033  6049 D UEI.SmartControl: Starting file observer...
08-16 10:28:43.371  6033  6049 I UEI.SmartControl: Registering callback...
08-16 10:28:43.372  6033  6048 I UEI.SmartControl: ------ IControl API: 19
08-16 10:28:43.373  6033  6048 I UEI.SmartControl: Registering Services Ready callback...
08-16 10:28:43.385  6033  6466 I UEI.SmartControl: Notify AllClients services are ready: 0
,08-16 10:28:43.391  6350  6367 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-16 10:28:43.392  6033  6466 D UEI.SmartControl: -----service ready thread exits
,08-16 10:28:43.394  6350  6452 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-16 10:28:43.395  6350  6452 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-16 10:28:43.396  6350  6350 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-16 10:28:43.397  6350  6350 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-16 10:28:43.397  6033  6049 I UEI.SmartControl: ------ IControl API: 8
08-16 10:28:43.401  6350  6350 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-16 10:28:43.402  6350  6350 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-16 10:28:43.403  6350  6350 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-16 10:28:43.404  6350  6350 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
,08-16 10:28:43.406  6350  6350 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-16 10:28:43.406  6350  6350 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-16 10:28:43.407  6350  6350 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-16 10:28:43.412  6350  6350 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-16 10:28:43.413  6350  6350 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-16 10:28:43.414  6350  6350 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-16 10:28:43.414  6350  6350 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-16 10:28:43.415  6350  6350 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-16 10:28:43.416  6350  6350 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-16 10:28:43.417  6350  6350 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-16 10:28:43.418  6350  6350 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1471336123418]
,08-16 10:28:43.422  6350  6350 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-16 10:28:43.424  1037  1999 I ActivityManager: Killing 5823:com.android.gallery3d/u0a27 (adj 15): empty #17
08-16 10:28:43.448  6350  6472 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-16 10:28:43.455  1037  1999 I ActivityManager: Killing 5785:com.lge.email/u0a23 (adj 15): empty #18
08-16 10:28:43.483  1037  1872 W libprocessgroup: failed to open /acct/uid_10027/pid_5823/cgroup.procs: No such file or directory
,08-16 10:28:43.495  1037  1981 W libprocessgroup: failed to open /acct/uid_10023/pid_5785/cgroup.procs: No such file or directory
08-16 10:28:43.496  6350  6350 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-16 10:28:43.500  6350  6350 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-16 10:28:43.501  6350  6350 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-16 10:28:43.501  6350  6350 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-16 10:28:43.502  6350  6350 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-16 10:28:43.502  6350  6350 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-16 10:28:43.502  6350  6350 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
,08-16 10:28:43.526  6350  6350 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-16 10:28:46.308  1037  1522 D LGWifiP2pService: P2pDisabledState{ when=-6ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-16 10:28:46.308  1037  1522 D LGWifiP2pService: DefaultState{ when=-6ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 10:28:46.472  1037  1523 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 1 0
08-16 10:28:46.472  1037  1523 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
,08-16 10:28:46.482  1037  2037 D WifiServiceImplEx: setWifiEnabled: true pid=6149, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-16 10:28:46.482  1037  2037 D WifiService: setWifiEnabled: true pid=6149, uid=10118
08-16 10:28:46.482  1037  2037 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-16 10:28:46.549  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 10:28:46.550  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 10:28:46.550  1037  1037 D Ulp_jni : JNI:system_update. Event-4
,08-16 10:28:46.552  1037  1523 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-16 10:28:46.552  1037  1523 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-16 10:28:46.555  1037  1523 E WifiUtil: wfc_util_ffile_check_copy(): pid[1037] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-16 10:28:46.555  1037  1523 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-16 10:28:46.555  1037  1523 E WifiUtil: wfc_util_ffile_check_copy(): pid[1037] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-16 10:28:46.555  1037  1523 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-16 10:28:46.555  1037  1523 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-16 10:28:46.555  1037  1523 E WifiHW  : unknown target_country: EU , set to default
08-16 10:28:46.555  1037  1523 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-16 10:28:46.556  1037  1523 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-16 10:28:46.556  1037  1523 I WifiUtil: gEnableBmps=1
08-16 10:28:47.160   305   906 D SoftapController: Softap fwReload - Ok
,08-16 10:28:47.170  1037  1523 E NetdConnector: NDC Command {37 softap fwreload wlan0 STA} took too long (609ms)
08-16 10:28:47.178   305   906 D CommandListener: Setting iface cfg
08-16 10:28:47.178   305   906 D CommandListener: Trying to bring down wlan0
,08-16 10:28:47.182  1037  1119 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-16 10:28:47.182  1037  1119 D Tethering: InitialState.processMessage what=4
08-16 10:28:47.185   305  6484 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-16 10:28:47.199   305   906 D CommandListener: Clearing all IP addresses on wlan0
,08-16 10:28:47.202  1037  1119 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-16 10:28:47.205  1037  1523 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-16 10:28:47.205  1037  1117 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-16 10:28:47.212  6485  6485 W wpa_supplicant: type=1400 audit(0.0:163): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-16 10:28:47.221  1037  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 10:28:47.221  1037  1523 E WifiStateMachine: useWiFiOffloading() : false
08-16 10:28:47.221  1037  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-16 10:28:47.223  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 10:28:47.212  6485  6485 W wpa_supplicant: type=1400 audit(0.0:164): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 10:28:47.229  1928  1928 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-16 10:28:47.253  6149  6149 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 10:28:47.257  6149  6149 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 10:28:47.258  6149  6149 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 10:28:47.258  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-16 10:28:47.277  1037  1523 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-16 10:28:47.277  1037  1523 D WifiMonitor: connecting to supplicant
,08-16 10:28:47.289  6279  6279 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-16 10:28:47.289  6279  6279 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-16 10:28:47.290  6279  6279 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-16 10:28:47.290  6279  6279 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-16 10:28:47.292  6485  6485 I wpa_supplicant: Successfully initialized wpa_supplicant
08-16 10:28:47.292  6279  6279 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-16 10:28:47.294  6279  6279 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-16 10:28:47.294  6279  6279 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-16 10:28:47.294  6279  6279 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-16 10:28:47.294  6279  6279 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
,08-16 10:28:47.294  6279  6279 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-16 10:28:47.295  6279  6279 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-16 10:28:47.296  6279  6279 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-16 10:28:47.301  6279  6279 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-16 10:28:47.302  6279  6279 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-16 10:28:47.302  6279  6279 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-16 10:28:47.302  6279  6279 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-16 10:28:47.303  6279  6279 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-16 10:28:47.304  6279  6279 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-16 10:28:47.304  6279  6279 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-16 10:28:47.304  6279  6279 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-16 10:28:47.304  6279  6279 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-16 10:28:47.304  6279  6279 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-16 10:28:47.304  6279  6279 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-16 10:28:47.311  6296  6296 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-16 10:28:47.315  6279  6279 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-16 10:28:47.322  6396  6504 W FormManager: Network not available. Please check & try again.
08-16 10:28:47.322  6279  6279 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 10:28:47.326  6485  6485 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-16 10:28:47.327  6485  6485 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-16 10:28:47.335  6396  6505 V FormManager: Network unavailable.
,08-16 10:28:47.337  6396  6505 V FormManager: Network unavailable.
08-16 10:28:47.404  6485  6485 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-16 10:28:47.418  6485  6485 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-16 10:28:47.424  6485  6485 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
,08-16 10:28:47.426  1037  1523 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-16 10:28:47.426  1037  1523 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-16 10:28:47.427  1037  1523 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-16 10:28:47.427  1037  1523 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-16 10:28:47.428  1037  1523 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-16 10:28:47.428  1037  6506 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-16 10:28:47.428  1037  6506 D WifiMonitor: Dropping event because (p2p0) is stopped
08-16 10:28:47.428  1037  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 10:28:47.429  1037  1523 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-16 10:28:47.429  1037  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 10:28:47.430  1037  1523 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-16 10:28:47.430  1037  1523 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-16 10:28:47.431  1037  1523 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-16 10:28:47.431  1037  1523 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-16 10:28:47.431  1037  1523 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-16 10:28:47.432  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 10:28:47.432  1037  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 10:28:47.432  1037  1523 E WifiStateMachine: useWiFiOffloading() : false
08-16 10:28:47.432  1037  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-16 10:28:47.433  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 10:28:47.433  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 10:28:47.433  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 10:28:47.433  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,08-16 10:28:47.438  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-16 10:28:47.439  1037  1527 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-16 10:28:47.439  1037  1523 D WifiNative-wlan0: doBoolean: SET update_config 1
08-16 10:28:47.440  1928  1928 D WfdService: Waiting for WifiP2p enabling
08-16 10:28:47.440  1037  1523 D WifiNative-wlan0: SET update_config 1: returned true
08-16 10:28:47.440  1037  1523 D WifiConfigStore: Loading config and enabling all networks 
08-16 10:28:47.440  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 10:28:47.440  1037  1523 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-16 10:28:47.441  1037  1523 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-16 10:28:47.444  6149  6149 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 10:28:47.444  6149  6149 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 10:28:47.444  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 10:28:47.444  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 10:28:47.444  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 10:28:47.444  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 10:28:47.444  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 10:28:47.444  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 10:28:47.444  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 10:28:47.444  6149  6149 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 10:28:47.444  6149  6149 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 10:28:47.446  6149  6149 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 10:28:47.446  6149  6149 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 10:28:47.446  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 10:28:47.446  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 10:28:47.446  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 10:28:47.446  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 10:28:47.446  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 10:28:47.446  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 10:28:47.446  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 10:28:47.446  6149  6149 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 10:28:47.446  6149  6149 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 10:28:47.447  6149  6149 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will re,turn stored value
08-16 10:28:47.447  6149  6149 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 10:28:47.447  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 10:28:47.447  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 10:28:47.447  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 10:28:47.447  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 10:28:47.447  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 10:28:47.447  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 10:28:47.447  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 10:28:47.447  6149  6149 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 10:28:47.447  6149  6149 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 10:28:47.448  1037  6506 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-16 10:28:47.448  6485  6485 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-16 10:28:47.448  1037  6506 E WifiMonitor: WifiMonitor:wlan0 cnt=14 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-16 10:28:47.448  1037  6506 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-16 10:28:47.448  1037  6506 E WifiMonitor: WifiMonitor:wlan0 cnt=15 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-16 10:28:47.448  1037  6506 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-16 10:28:47.448  1037  6506 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,08-16 10:28:47.454  6296  6296 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 10:28:47.458  6279  6279 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-16 10:28:47.458  1037  1523 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
,08-16 10:28:47.467  6396  6509 W FormManager: Network not available. Please check & try again.
08-16 10:28:47.469  6279  6279 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 10:28:47.476  1037  1523 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-16 10:28:47.476  1037  1523 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-16 10:28:47.478  6396  6510 V FormManager: Network unavailable.
08-16 10:28:47.478  1037  1523 D WifiStateMachine: enableVerboseLogging : level 2
08-16 10:28:47.478  1037  1523 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-16 10:28:47.479  1037  1523 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-16 10:28:47.479  1037  1523 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-16 10:28:47.479  1037  1523 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-16 10:28:47.479  1037  1523 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-16 10:28:47.479  1037  1523 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-16 10:28:47.480  1037  1523 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-16 10:28:47.480  1037  1523 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-16 10:28:47.480  1037  1523 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-16 10:28:47.481  1037  1523 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-16 10:28:47.481  1037  1523 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-16 10:28:47.481  6396  6510 V FormManager: Network unavailable.
08-16 10:28:47.481  1037  1523 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-16 10:28:47.481  1037  1523 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-16 10:28:47.481  1037  1523 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-16 10:28:47.482  1037  1523 D WifiStateMachine: Setting OUI to DA-A1-19
08-16 10:28:47.483  1928  1928 D WfdsService: Supplicant Connection state is changed : true
08-16 10:28:47.484  1928  2293 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-16 10:28:47.484  1928  2293 D WfdsService: Set the WFDS Monitor: true
08-16 10:28:47.484  1928  2293 D WfdsMonitor: WfdsMonitorThread create
08-16 10:28:47.484  1928  2293 D WfdsMonitor: WFDS Monitor is created and started
08-16 10:28:47.484  1928  2293 D WfdsService: WiFi: Supplicant connection re-established
08-16 10:28:47.484  1037  1523 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-16 10:28:47.484  1037  1523 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-16 10:28:47.485  1037  1523 D WifiNative-HAL: Setting external_sim to 1
08-16 10:28:47.485  1037  1523 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-16 10:28:47.485  1037  1523 D WifiNative-wlan0: SET external_sim 1: returned true
08-16 10:28:47.485  1037  1523 I WifiNative-HAL: startHal
08-16 10:28:47.485  1928  6511 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-16 10:28:47.485  1037  1523 D wifi    : setting scan oui 0xaf5a7020
08-16 10:28:47.486  1928  6511 E CtrlSupplicant: Succeed to open control connection
08-16 10:28:47.486  1037  1523 D WifiStateMachine: Setting OUI to DA-A1-19
08-16 10:28:47.486  1037  1523 I WifiNative-HAL: startHal
08-16 10:28:47.486  1037  1523 D wifi    : setting scan oui 0xaf5a7020
08-16 10:28:47.486  1928  6511 E CtrlSupplicant: Succeed to open monitor connection
08-16 10:28:47.486  1037  1523 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-16 10:28:47.486  1037  1523 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-16 10:28:47.486  1037  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-16 10:28:47.487  6485  6485 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-16 10:28:47.487  1928  6511 D WfdsMonitor: Supplicant connection established
08-16 10:28:47.487  1928  2293 D WfdsService: Connected to the supplicant for wfds
08-16 10:28:47.487  1037  1523 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-16 10:28:47.487  1037  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-16 10:28:47.487  6485  6485 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-16 10:28:47.488  1037  1523 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-16 10:28:47.488  1037  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-R,EMOVE 3
08-16 10:28:47.488  6485  6485 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
,08-16 10:28:47.489  1037  1523 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-16 10:28:47.489  1037  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-16 10:28:47.489  6485  6485 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-16 10:28:47.490  1037  1523 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-16 10:28:47.490  1037  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-16 10:28:47.490  6485  6485 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-16 10:28:47.490  1037  1523 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-16 10:28:47.490  1037  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-16 10:28:47.490  6485  6485 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-16 10:28:47.491  1037  1523 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-16 10:28:47.491  1037  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-16 10:28:47.491  6485  6485 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-16 10:28:47.491  4259  4259 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 10:28:47.491  4259  4259 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 10:28:47.491  1037  1523 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-16 10:28:47.492  1037  1523 E WifiNative: : [367,026,375 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-16 10:28:47.492  1037  1523 D WifiNative-wlan0: doBoolean: RECONNECT
08-16 10:28:47.493  1037  1523 D WifiNative-wlan0: RECONNECT: returned true
08-16 10:28:47.493  1037  1523 D WifiNative-wlan0: doString: [STATUS]
08-16 10:28:47.493  1037  6506 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-16 10:28:47.493  1037  6506 E WifiMonitor: WifiMonitor:wlan0 cnt=16 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-16 10:28:47.494  4259  4259 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 10:28:47.494  1037  1523 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-16 10:28:47.494  1037  1523 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 10:28:47.494  1037  1523 D WifiNative-wlan0: SET ps 1: returned true
08-16 10:28:47.495  1037  1522 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-16 10:28:47.497   305   906 D CommandListener: Setting iface cfg
,08-16 10:28:47.497   305   906 D CommandListener: Trying to bring up p2p0
08-16 10:28:47.497  1037  1522 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-16 10:28:47.497  1037  1522 D LGWifiP2pService: P2pEnablingState
08-16 10:28:47.497  1037  1522 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-16 10:28:47.497  1037  1522 D LGWifiP2pService: P2p socket connection successful
08-16 10:28:47.497  1037  1522 D LGWifiP2pService: P2pEnabledState
08-16 10:28:47.497  4259  4259 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 10:28:47.498  1037  1522 D LGWifiP2pService: sending p2p connection changed broadcast
08-16 10:28:47.498  1037  1522 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-16 10:28:47.499  1037  1522 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-16 10:28:47.499  1037  1522 D WifiNative-p2p0: doBoolean: SET device_name G3
08-16 10:28:47.499  1037  1523 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-16 10:28:47.499  1037  1522 D WifiNative-p2p0: SET device_name G3: returned true
08-16 10:28:47.499  1037  1522 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-16 10:28:47.500  1037  1523 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-16 10:28:47.500  1037  1522 D LGWifiP2pService: before postfix = G3
08-16 10:28:47.500  1037  1522 D WifiServerServiceExt: postfix byte check : 2
,08-16 10:28:47.500  1037  1522 D LGWifiP2pService: after postfix = G3
08-16 10:28:47.500  1037  1522 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-16 10:28:47.500  1037  1523 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-16 10:28:47.500  1037  1522 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-16 10:28:47.500  1037  1522 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-16 10:28:47.500  1037  1523 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-16 10:28:47.501  1037  1522 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
,08-16 10:28:47.501  1037  1522 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-16 10:28:47.501  1037  1523 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-16 10:28:47.501  1037  1523 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-16 10:28:47.501  1037  1522 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-16 10:28:47.501  1037  1523 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-16 10:28:47.502  1037  1522 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-16 10:28:47.502  1037  1523 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-16 10:28:47.502  6485  6485 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-16 10:28:47.502  1037  1522 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
,08-16 10:28:47.502  1037  1522 D WifiNative-HAL: p2pGetDeviceAddress
08-16 10:28:47.502  1037  1037 D WifiScanningService: SCAN_AVAILABLE : 3
08-16 10:28:47.503  1037  1037 D RttService: SCAN_AVAILABLE : 3
08-16 10:28:47.503  1037  1522 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-16 10:28:47.503  1037  1542 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-16 10:28:47.504  1037  1541 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-16 10:28:47.504  1037  1541 I WifiNative-HAL: startHal
08-16 10:28:47.504  1037  1541 D wifi    : getting scan capabilities on interface[1] = 0xaf5a7020
08-16 10:28:47.504  1037  1541 D wifi    : failed to get capabilities : -3
,08-16 10:28:47.504  1037  1541 E WifiScanningService: could not get scan capabilities
08-16 10:28:47.503  1037  1523 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-16 10:28:47.504  1928  1928 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-16 10:28:47.504  1928  1928 D WfdsService: WifiP2pState is changed : true
08-16 10:28:47.504  1037  1523 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-16 10:28:47.504  1928  1928 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-16 10:28:47.505  1928  1928 D WfdsService: isConnected: false
08-16 10:28:47.505  1928  2293 D WfdsService: Receive the WFDS_ENABLE Method
08-16 10:28:47.505  1928  2293 D WfdsService: Set the WFDS Monitor: true
08-16 10:28:47.505  1928  2293 D WfdsService: Connected to the supplicant for wfds
08-16 10:28:47.505  1928  2293 D WfdsJNI : doCommand: WFDS_SET TRUE
08-16 10:28:47.505  6485  6485 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-16 10:28:47.506  1928  2293 D WfdsService: selectPreferredScanChannel [36]
08-16 10:28:47.506  1928  2293 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-16 10:28:47.506  1037  1523 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-16 10:28:47.506  1037  1523 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-16 10:28:47.506  6485  6485 E wpa_supplicant: disconnect_rssi_lvl: -100
08-16 10:28:47.507  1037  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 14 0 rt=367041  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-16 10:28:47.509  6006  6006 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-16 10:28:47.509  6006  6006 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
08-16 10:28:47.510  1037  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 14 0 rt=367045  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-16 10:28:47.511  4259  6512 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-16 10:28:47.511  1037  1523 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
,08-16 10:28:47.511  1037  1523 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-16 10:28:47.512  1037  1522 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-16 10:28:47.512  1037  1522 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-16 10:28:47.512  1037  1523 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-16 10:28:47.512  1037  1523 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-16 10:28:47.512  1037  1522 D WifiNative-p2p0: P2P_FLUSH: returned true
08-16 10:28:47.512  1037  1522 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-16 10:28:47.513  6485  6485 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-16 10:28:47.513  6485  6485 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 10:28:47.514  6485  6485 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-16 10:28:47.514  6485  6485 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 10:28:47.514  1928  1928 I WfdStateTracker: handleP2pThisDeviceChanged
08-16 10:28:47.514  1928  1928 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-16 10:28:47.514  1928  1928 D WfdsService: Update P2p Interface State: 3
08-16 10:28:47.515  6485  6485 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 10:28:47.515  1037  1523 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-16 10:28:47.516  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 10:28:47.516  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 10:28:47.516  1928  6511 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 10:28:47.516  1928  6511 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 10:28:47.516  1037  1523 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-16 10:28:47.516  1037  1523 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-16 10:28:47.517  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 10:28:47.517  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 10:28:47.517  1037  1523 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-16 10:28:47.517  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-16 10:28:47.517  1037  1523 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-16 10:28:47.517  6485  6485 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-16 10:28:47.517  6485  6485 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 10:28:47.518  1037  6506 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-16 10:28:47.518  1037  6506 E WifiMonitor: WifiMonitor:wlan0 cnt=17 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,08-16 10:28:47.518  1037  6506 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 10:28:47.518  1037  6506 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 10:28:47.518  1037  6506 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 10:28:47.518  1037  6506 E WifiMonitor: WifiMonitor:p2p0 cnt=18 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 10:28:47.518  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 10:28:47.518  1037  1523 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-16 10:28:47.518  1037  6506 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 10:28:47.518  1037  1523 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-16 10:28:47.518  1037  6506 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 10:28:47.518  1037  6506 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 10:28:47.518  1037  6506 E WifiMonitor: WifiMonitor:p2p0 cnt=19 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 10:28:47.518  1037  6506 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 10:28:47.518  1037  6506 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 10:28:47.518  1037  6506 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-16 10:28:47.518  1037  6506 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 10:28:47.519  1037  1523 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-16 10:28:47.519  1037  6506 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 10:28:47.519  1037  1523 D WifiNative-wlan0: doBoolean: SCAN
08-16 10:28:47.519  1037  6506 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 10:28:47.519  1037  1523 D WifiNative-wlan0: SCAN: returned false
08-16 10:28:47.520  1037  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 16 0 rt=367054  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-16 10:28:47.522  1037  1522 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-16 10:28:47.522  1037  1522 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-16 10:28:47.522  1037  1522 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-16 10:28:47.522  1037  1522 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-16 10:28:47.523  1037  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 16 0 rt=367056  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-16 10:28:47.524  1037  1523 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 10:28:47.524  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 10:28:47.524  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 10:28:47.524  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-16 10:28:47.524  1037  1523 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 10:28:47.524  4259  6513 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 10:28:47.525  4259  6513 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-16 10:28:47.525  1037  1523 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 10:28:47.525  1037  1523 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 10:28:47.526  1037  1523 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 10:28:47.527  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 10:28:47.527  1037  1037 D WifiServerServiceExt: setSupplicantStateSCANNING
08-16 10:28:47.528  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 10:28:47.528  1037  1037 D WifiServerServiceExt: setSupplicantStateSCANNING
08-16 10:28:47.529  6006  6006 V [BNRBootReceiver]: Boot Receiver Return
08-16 10:28:47.530  1037  1522 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-16 10:28:47.530  1037  1522 D LGWifiP2pService: sending p2p persistent groups changed broadcast
,08-16 10:28:47.533  1037  1522 D LGWifiP2pService: InactiveState
,08-16 10:28:47.533  1037  1522 D LGWifiP2pService: InactiveState{ when=-18ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-16 10:28:47.533  1037  1522 D LGWifiP2pService: P2pEnabledState{ when=-19ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-16 10:28:47.533  1037  1522 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-16 10:28:47.534  6485  6485 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-16 10:28:47.534  6485  6485 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 10:28:47.535  1928  6511 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-16 10:28:47.535  6485  6485 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-16 10:28:47.535  6485  6485 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 10:28:47.535  1037  6506 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-16 10:28:47.535  1037  6506 E WifiMonitor: WifiMonitor:p2p0 cnt=21 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 10:28:47.536  1037  6506 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 10:28:47.536  1037  6506 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 10:28:47.536  1037  6506 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 10:28:47.536  1037  6506 E WifiMonitor: WifiMonitor:p2p0 cnt=22 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 10:28:47.536  1037  6506 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 10:28:47.536  1037  6506 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 10:28:47.536  6485  6485 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 10:28:47.536  1928  6511 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 10:28:47.537  1928  6511 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 10:28:47.537  1037  6506 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 10:28:47.537  1037  6506 E WifiMonitor: WifiMonitor:p2p0 cnt=23 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 10:28:47.537  1037  6506 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 10:28:47.537  1037  1522 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-16 10:28:47.537  1037  6506 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 10:28:47.537  1037  1522 D LGWifiP2pService: InactiveState{ when=-15ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-16 10:28:47.537  1037  1522 D LGWifiP2pService: P2pEnabledState{ when=-16ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-16 10:28:47.537  1037  1522 D LGWifiP2pService: InactiveState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-16 10:28:47.537  1037  1522 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-16 10:28:47.537  1037  1522 D LGWifiP2pService: DefaultState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-16 10:28:47.537  1037  1522 D LGWifiP2pService: InactiveState{ when=-5ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-16 10:28:47.537  1037  1522 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-16 10:28:47.537  1037  1522 D LGWifiP2pService: DefaultState{ when=-5ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-16 10:28:47.538  1037  1522 D LGWifiP2pService: InactiveState{ when=-5ms what,=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-16 10:28:47.538  1037  1522 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-16 10:28:47.538  1037  1522 D LGWifiP2pService: DefaultState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-16 10:28:47.538  1928  2293 W WfdsService: DefaultState - msg [9441285] is not handled
08-16 10:28:47.539  1037  1522 D LGWifiP2pService: InactiveState{ when=-6ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-16 10:28:47.539  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 10:28:47.539  1037  1522 D LGWifiP2pService: P2pEnabledState{ when=-6ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-16 10:28:47.539  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 10:28:47.539  1037  1522 D LGWifiP2pService: DefaultState{ when=-6ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-16 10:28:47.535  3722  3722 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 10:28:47.539  1037  1037 E WifiServerServiceExt: No p2p device connected
08-16 10:28:47.540  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 10:28:47.546  6279  6279 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 10:28:47.552  6279  6279 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 10:28:47.560  6350  6350 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 10:28:47.561  6350  6350 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 10:28:47.562  6350  6350 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-16 10:28:47.564  3722  3722 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 10:28:47.569  6279  6279 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 10:28:47.574  6279  6279 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 10:28:47.580  6350  6350 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 10:28:47.580  6350  6350 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 10:28:47.581  6350  6350 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-16 10:28:48.090  6485  6485 E wpa_supplicant: USIM:  scard_init function
08-16 10:28:48.091  6485  6485 I wpa_supplicant: Trying to associate with SSID 'NG700'
,08-16 10:28:48.102  1037  6506 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-16 10:28:48.102  1037  6506 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-16 10:28:48.103  1037  6506 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-16 10:28:48.104  1037  6506 E WifiMonitor: WifiMonitor:wlan0 cnt=25 dispatchEvent: WPS-AP-AVAILABLE 
08-16 10:28:48.104  1037  6506 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-16 10:28:48.104  1037  6506 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-16 10:28:48.104  1037  6506 E WifiMonitor: WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-16 10:28:48.108  1037  1523 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=11 bcn=0
08-16 10:28:48.109  1037  1523 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=11 bcn=0
08-16 10:28:48.109  1037  1523 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=11 bcn=0
08-16 10:28:48.109  1037  1523 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=11 bcn=0
08-16 10:28:48.109  1037  1523 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-16 10:28:48.125  1037  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=367659  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-16 10:28:48.132  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 10:28:48.132  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 10:28:48.133  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 10:28:48.138  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 10:28:48.138  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 10:28:48.138  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-16 10:28:48.143  1037  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=367677  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-16 10:28:48.149  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 10:28:48.149  1037  1037 D WifiServerServiceExt: setSupplicantStateASSOCIATING
,08-16 10:28:48.154  6279  6279 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-16 10:28:48.168  6279  6279 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
,08-16 10:28:48.174  3722  3722 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 10:28:48.184  6279  6279 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 10:28:48.192  6279  6279 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 10:28:48.200  6350  6350 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-16 10:28:48.203  6350  6350 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 10:28:48.204  6350  6350 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 10:28:48.220  6485  6485 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-16 10:28:48.228  1037  6506 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-16 10:28:48.228  1037  6506 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-16 10:28:48.229  1037  6506 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-16 10:28:48.229  1037  6506 E WifiMonitor: WifiMonitor:wlan0 cnt=28 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-16 10:28:48.229  1037  6506 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 10:28:48.229  1037  6506 E WifiMonitor: WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 10:28:48.231  6485  6485 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 10:28:48.231  6485  6485 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-16 10:28:48.233  1037  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=367767  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-16 10:28:48.234  1037  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=367768  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-16 10:28:48.234  1037  1523 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 28 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=367769
08-16 10:28:48.235  1037  1523 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 28 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=367769
08-16 10:28:48.237  1037  6506 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 10:28:48.237  1037  6506 E WifiMonitor: WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 10:28:48.238  1037  6506 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
,08-16 10:28:48.238  1037  6506 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 10:28:48.241  1037  6506 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 10:28:48.241  1037  6506 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-16 10:28:48.241  1037  6506 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-16 10:28:48.241  1037  6506 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-16 10:28:48.242  1037  6506 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 10:28:48.242  1037  6506 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 10:28:48.243  1037  1523 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=367777
08-16 10:28:48.243  1037  1523 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=367778
08-16 10:28:48.245  1037  1119 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-16 10:28:48.256  1037  1523 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 28 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=367778
08-16 10:28:48.258  1037  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=367792  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-16 10:28:48.261  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 10:28:48.261  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 10:28:48.261  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-16 10:28:48.263  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 10:28:48.263  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 10:28:48.265  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 10:28:48.274  6279  6279 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-16 10:28:48.274  6279  6279 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-16 10:28:48.274  6279  6279 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-16 10:28:48.274  6279  6279 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-16 10:28:48.274  6279  6279 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-16 10:28:48.280  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 10:28:48.280  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 10:28:48.280  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-16 10:28:48.281  6279  6279 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-16 10:28:48.281  1037  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=367815  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-16 10:28:48.281  6279  6279 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-16 10:28:48.281  6279  6279 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-16 10:28:48.281  6279  6279 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-16 10:28:48.281  6279  6279 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-16 10:28:48.281  6279  6279 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-16 10:28:48.282  6279  6279 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-16 10:28:48.282  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 10:28:48.282  1037  1037 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-16 10:28:48.283  1037  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=367817  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-16 10:28:48.283  1037  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=367818  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
,08-16 10:28:48.284  1037  1523 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=367819
08-16 10:28:48.285  1037  1523 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=367819
08-16 10:28:48.285  1037  1523 D WifiNative-wlan0: doString: [STATUS]
08-16 10:28:48.286  1037  1523 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-16 10:28:48.286  1037  6506 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 10:28:48.286  1037  6506 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 10:28:48.287  3722  3722 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 10:28:48.289  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 10:28:48.289  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 10:28:48.290  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 10:28:48.293  1037  1523 I WifiServiceExtension: setVHTCapabilityType  : false
08-16 10:28:48.296  6279  6279 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 10:28:48.300  1037  1523 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-16 10:28:48.300  1037  1523 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-16 10:28:48.303  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 10:28:48.303  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 10:28:48.303  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-16 10:28:48.305  6279  6279 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 10:28:48.306  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 10:28:48.306  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 10:28:48.307  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-16 10:28:48.318  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-16 10:28:48.318  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 10:28:48.320  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 10:28:48.322  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 10:28:48.322  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 10:28:48.322  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 10:28:48.327  6350  6350 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 10:28:48.327  6350  6350 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 10:28:48.328  6350  6350 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 10:28:48.331  3722  3722 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 10:28:48.333  1037  1523 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,08-16 10:28:48.333  1037  1523 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 10:28:48.333  1037  1523 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-16 10:28:48.334  1037  1530 D ConnectivityService: Got NetworkAgent Messenger
08-16 10:28:48.335  1037  1530 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-16 10:28:48.335  1037  1530 D ConnectivityService: NetworkAgent connected
08-16 10:28:48.335  1037  1523 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-16 10:28:48.335  1037  1523 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-16 10:28:48.341  6279  6279 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 10:28:48.342  1037  1523 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-16 10:28:48.343  1037  1523 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 10:28:48.343  1037  1523 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-16 10:28:48.343  1037  1523 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-16 10:28:48.343  1037  1523 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,08-16 10:28:48.347  6033  6468 D UEI.SmartControl: Internal timer expired: 2
08-16 10:28:48.347  6033  6468 D UEI.SmartControl: unbind internal service
08-16 10:28:48.350  1037  1523 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-16 10:28:48.350  6279  6279 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 10:28:48.351   305   906 D CommandListener: Setting iface cfg
08-16 10:28:48.357  6350  6350 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-16 10:28:48.357  6350  6350 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 10:28:48.357  6350  6350 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 10:28:48.362  3722  3722 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 10:28:48.363  1037  6542 D DhcpStateMachine: StoppedState
08-16 10:28:48.363  1037  1523 E WifiStateMachine: Start Dhcp Watchdog 1
08-16 10:28:48.363  1037  6542 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-16 10:28:48.363  1037  6542 D DhcpStateMachine: WaitBeforeStartState
08-16 10:28:48.363  1037  1523 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=367898  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 10:28:48.364  1037  1523 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=367898  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 10:28:48.364  1037  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=367899  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 10:28:48.365  1037  1523 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-16 10:28:48.366  1037  1523 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-16 10:28:48.366  1037  1523 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-16 10:28:48.366  1037  1523 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-16 10:28:48.367  1037  1523 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-16 10:28:48.367  1037  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 10:28:48.368  6279  6279 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 10:28:48.369  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 10:28:48.369  1037  1037 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-16 10:28:48.370  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 10:28:48.370  1037  1037 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-16 10:28:48.371  1037  1523 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=367906  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,08-16 10:28:48.372  1037  1523 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=367906  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 10:28:48.372  1037  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=367907  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 10:28:48.373  6279  6279 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 10:28:48.374  1037  1523 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:-1837654154] from screen [on:0 period:-1837654154]
08-16 10:28:48.375  1037  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1837654153]
08-16 10:28:48.375  1037  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-16 10:28:48.379  6350  6350 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 10:28:48.379  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 10:28:48.379  6350  6350 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 10:28:48.380  6350  6350 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-16 10:28:48.382  1037  1530 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
08-16 10:28:48.382  3722  3722 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 10:28:48.383  1037  1523 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 10:28:48.383  1037  1523 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 10:28:48.384  1037  1523 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 10:28:48.384  1037  1523 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 10:28:48.384  1037  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 10:28:48.385  1037  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 10:28:48.386  1037  1530 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
08-16 10:28:48.386  1037  1523 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
08-16 10:28:48.386  1037  1523 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
08-16 10:28:48.386  1037  1523 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-16 10:28:48.387  6485  6485 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-16 10:28:48.387  6279  6279 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 10:28:48.387  1037  1523 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-16 10:28:48.387  1037  1523 D WifiNative-wlan0: doBoolean: SET ps 0
08-16 10:28:48.388  1037  1523 D WifiNative-wlan0: SET ps 0: returned true
08-16 10:28:48.388  1037  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-16 10:28:48.388  6485  6485 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-16 10:28:48.388  1037  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-16 10:28:48.389  1037  1523 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-16 10:28:48.389  1037  1522 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2e478c34 target=com.android.internal.util.StateMachine$SmHandler }
08-16 10:28:48.389  1037  1523 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-16 10:28:48.389  1037  1522 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2e478c34 target=com.android.internal.util.StateMachine$SmHandler }
08-16 10:28:48.389  1037  6542 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-16 10:28:48.389  1037  1523 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-16 10:28:48.389  1037  1523 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700" is not exist.
08-16 10:28:48.389  1037  6542 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-16 10:28:48.390  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 10:28:48.390  1037  1037 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-16 10:28:48.391  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 10:28:48.391  1037  1037 D WifiServerServiceExt: setSupplicantStateCOMPLETED
,08-16 10:28:48.392  6279  6279 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-16 10:28:48.398  6350  6350 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-16 10:28:48.398  6350  6350 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 10:28:48.399  6350  6350 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 10:28:48.575  6033  6462 D serial_port: close(fd = 24)
08-16 10:28:48.579  6033  6462 I UEI.SmartControl: Serial port is closed.
,08-16 10:28:48.592  1037  6542 D DhcpStateMachine: DHCPV4 request on wlan0,
08-16 10:28:48.594  1037  6542 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-16 10:28:48.594  1037  6542 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
,08-16 10:28:48.602  6543  6543 W dhcpcd  : type=1400 audit(0.0:165): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-16 10:28:48.602  6543  6543 W dhcpcd  : type=1400 audit(0.0:166): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 10:28:48.646  6543  6543 I dhcpcd  : version 5.5.6 starting
,08-16 10:28:48.650  6543  6543 E dhcpcd  : get_duid: m
08-16 10:28:48.651  6543  6543 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-16 10:28:48.651  6543  6543 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-16 10:28:48.758  6543  6543 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-16 10:28:48.758  6543  6543 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-16 10:28:48.759  6543  6543 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-16 10:28:48.762  6543  6543 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
,08-16 10:28:48.763  6543  6543 D dhcpcd  : wlan0: sending REQUEST (xid 0x762cf082), next in 3.74 seconds
,08-16 10:28:48.776  6543  6543 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,08-16 10:28:48.802  6543  6543 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
08-16 10:28:48.802  6543  6543 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
08-16 10:28:48.803  6543  6543 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-16 10:28:48.804  6543  6543 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-16 10:28:48.804  6543  6543 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-16 10:28:48.805  6543  6543 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-16 10:28:48.805  6543  6543 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-16 10:28:48.805  6543  6543 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-16 10:28:48.809  1037  1523 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 10:28:48.810  1037  1523 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
,08-16 10:28:48.812  1037  1523 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 10:28:48.815  1037  1523 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 10:28:48.816  1037  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 10:28:48.817  1037  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 10:28:48.819  1037  1530 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
08-16 10:28:49.204  1037  6542 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-16 10:28:49.216  1037  6542 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-16 10:28:49.216  1037  6542 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-16 10:28:49.217  1037  6542 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
08-16 10:28:49.217  1037  6542 V LgDhcpStateMachineHelper: Add DhcpResults: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-16 10:28:49.217  1037  6542 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-16 10:28:49.217  1037  6542 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: true
08-16 10:28:49.220  1037  1523 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-16 10:28:49.220  1037  1523 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-16 10:28:49.224  1037  6542 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
,08-16 10:28:49.227  1037  1522 D LGWifiP2pService: InactiveState{ when=-7ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 10:28:49.227  1037  1522 D LGWifiP2pService: P2pEnabledState{ when=-7ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 10:28:49.228  1037  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-16 10:28:49.228  6485  6485 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-16 10:28:49.229  1037  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-16 10:28:49.229  1037  1523 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-16 10:28:49.230  6485  6485 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-16 10:28:49.231  1037  6542 D DhcpStateMachine: RunningState
08-16 10:28:49.232  1037  1523 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-16 10:28:49.232  1037  1523 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 10:28:49.249  1037  1523 D WifiNative-wlan0: SET ps 1: returned true
,08-16 10:28:49.255  1037  1530 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
08-16 10:28:49.257  1037  1523 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-16 10:28:49.258  1037  1523 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-16 10:28:49.258  1037  1523 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-16 10:28:49.260  1037  1530 D ConnectivityService: ignoring duplicate network state non-change
,08-16 10:28:49.288  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 10:28:49.288  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 10:28:49.288  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,08-16 10:28:49.305  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 10:28:49.305  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 10:28:49.311  1037  1523 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-16 10:28:49.314  1037  1530 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-16 10:28:49.323  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 10:28:49.329  1037  1530 D ConnectivityService: Adding iface wlan0 to network 100
08-16 10:28:49.332  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 10:28:49.333  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 10:28:49.333  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-16 10:28:49.334  1037  1037 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-16 10:28:49.347  1928  1928 V WfdStateTracker: handleWifiStateChangedEvent: 1
,08-16 10:28:49.353  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 10:28:49.353  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 10:28:49.367  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 10:28:49.373  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 10:28:49.373  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 10:28:49.373  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-16 10:28:49.374  1037  1037 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-16 10:28:49.382  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 10:28:49.385  1588  1588 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 2
,08-16 10:28:49.408  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 10:28:49.408  3722  3722 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 10:28:49.413  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 10:28:49.413  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 10:28:49.413  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-16 10:28:49.422  1037  1530 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-16 10:28:49.426  1037  1530 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 100
08-16 10:28:49.430  1037  1530 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
08-16 10:28:49.431  6279  6279 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 10:28:49.432  1037  1530 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
08-16 10:28:49.434  1037  1530 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-16 10:28:49.435  1037  1530 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 100
08-16 10:28:49.435  1037  1530 D ConnectivityService: Setting Dns servers for network 100 to [/192.168.1.1]
,08-16 10:28:49.439  1037  1530 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-16 10:28:49.439  1037  1530 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
08-16 10:28:49.440  1037  1530 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
08-16 10:28:49.440  1037  1530 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
08-16 10:28:49.440  1037  1530 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 10:28:49.440  1037  1530 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 10:28:49.440  1037  1530 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-16 10:28:49.441  1037  1530 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 10:28:49.441  1037  1530 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-16 10:28:49.441  1037  1530 D ConnectivityService: currentScore = 0, newScore = 20
08-16 10:28:49.441  1037  1530 D ConnectivityService:    accepting network in place of null
08-16 10:28:49.441  1037  1530 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 10:28:49.442  1037  6541 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-16 10:28:49.442  1037  6541 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-16 10:28:49.442  1037  6541 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-16 10:28:49.443  1037  6541 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-16 10:28:49.446  1838  1838 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 10:28:49.447  1037  1523 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 10:28:49.447  1838  1838 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-16 10:28:49.447  1037  1523 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 10:28:49.448  1037  1530 D ConnectivityService: Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
,08-16 10:28:49.451  6279  6279 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 10:28:49.455   305  6599 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-16 10:28:49.459  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 10:28:49.459  1588  1588 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 2
08-16 10:28:49.459  1037  1530 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-16 10:28:49.459  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 10:28:49.460  1037  1530 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-16 10:28:49.460  1037  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-16 10:28:49.461  1037  1530 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 10:28:49.461  1037  1530 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-16 10:28:49.462  1037  1530 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,08-16 10:28:49.463  1037  1037 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-16 10:28:49.464  1037  1037 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-16 10:28:49.464  1037  1037 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-16 10:28:49.464  1037  1037 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-16 10:28:49.464  1037  1037 D LocSvc_java: Sending msg: 5 arg1:0 arg2:1
08-16 10:28:49.466  1037  1530 D ConnectivityService: validation of new default Network = false
08-16 10:28:49.466  1037  1530 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-16 10:28:49.466  1037  1530 D DSQN    : enableDataServiceNotify 
08-16 10:28:49.466  1037  1530 D DSQN    : start dsqn bin
08-16 10:28:49.468   305  6602 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-16 10:28:49.468   305  6602 D libc-netbsd: res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
08-16 10:28:49.469  6350  6350 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 10:28:49.469  6350  6350 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 10:28:49.470   305  6603 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-16 10:28:49.470   305  6603 D libc-netbsd: res_queryN name = europe.pool.ntp.org, class = 1, type = 1
08-16 10:28:49.473  1037  1530 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
08-16 10:28:49.474  1037  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 10:28:49.474  1037  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 10:28:49.474  1037  1530 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 10:28:49.475  1588  1830 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-16 10:28:49.472  6604  6604 W dsqn    : type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 10:28:49.472  6604  6604 W dsqn    : type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-16 10:28:49.488  6350  6350 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 10:28:49.490  6604  6604 E DSQN    : DSQN ssw
,08-16 10:28:49.492  3722  3722 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 10:28:49.500  6279  6279 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 10:28:49.506  6279  6279 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 10:28:49.506   305  6599 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-16 10:28:49.512  1588  1588 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 10:28:49.512  6350  6350 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 10:28:49.513  6350  6350 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 10:28:49.513  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 10:28:49.513  6350  6350 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 10:28:49.513  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 10:28:49.517  3722  3722 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 10:28:49.521   305  6602 D libc-netbsd: res_queryN name = 2.android.pool.ntp.org succeed
08-16 10:28:49.521  6296  6296 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-16 10:28:49.525  6296  6296 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,08-16 10:28:49.528  6279  6279 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 10:28:49.533  6279  6279 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 10:28:49.538  6350  6350 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-16 10:28:49.543   305  6599 D libc-netbsd: res_queryN name = clients3.google.com succeed
08-16 10:28:49.543  1037  1521 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-16 10:28:49.538  6350  6350 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 10:28:49.544  6350  6350 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-16 10:28:49.545  6350  6350 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-16 10:28:49.545  6350  6350 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-16 10:28:49.549  3722  3722 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 10:28:49.552  6296  6296 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-16 10:28:49.553  6296  6296 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-16 10:28:49.558  6279  6279 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 10:28:49.564  6279  6279 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 10:28:49.574   305   905 D LGDataListener: argv[0]=dsqncommand
08-16 10:28:49.574   305   905 D LGDataListener: argv[1]=wlan0
08-16 10:28:49.574   305   905 D LGDataListener: argv[2]=1
08-16 10:28:49.575   305   905 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-16 10:28:49.576  1037  1117 D DSQN    : DSQM DsqnNotification wlan0  1
08-16 10:28:49.576  1037  1117 D DSQN    : start to monitor internet connection
08-16 10:28:49.577  6350  6350 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-16 10:28:49.577  6350  6350 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 10:28:49.578  6350  6350 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-16 10:28:49.580  6350  6350 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-16 10:28:49.580  6350  6350 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-16 10:28:49.606  1037  6541 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 16 Aug 2016 08:28:50 GMT], X-Android-Received-Millis=[1471336129604], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1471336129574]}
08-16 10:28:49.606  1037  6541 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-16 10:28:49.607  1037  6541 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-16 10:28:49.607  1037  1530 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 100]
08-16 10:28:49.607  1037  1530 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
,08-16 10:28:49.608  1037  1530 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-16 10:28:49.608  1037  1530 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 10:28:49.608  1037  1530 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-16 10:28:49.608  1037  1530 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
08-16 10:28:49.608  1037  1530 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
08-16 10:28:49.609  1037  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-16 10:28:49.609  1037  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 10:28:49.609  1037  1530 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 10:28:49.610  1588  1830 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-16 10:28:49.610  1037  1530 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 10:28:49.610  1037  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-16 10:28:49.611  1037  1523 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 10:28:49.611  1037  1523 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 10:28:49.612  1838  1838 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 10:28:49.612  1838  1838 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-16 10:28:49.643  1588  1588 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 10:28:49.645  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 10:28:49.647  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 10:28:49.689  1037  1523 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-16 10:28:49.690  1037  1523 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 10:28:49.692  1037  1523 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 10:28:49.693  1037  1523 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 10:28:49.694  1037  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 10:28:49.696  1037  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 10:28:49.698  1037  1530 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=true
08-16 10:28:49.699  1037  1530 D ConnectivityService: identical MTU - not setting
08-16 10:28:49.699  1037  1530 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-16 10:28:49.700  1037  1530 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
08-16 10:28:49.700  1037  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 10:28:49.700  1037  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 10:28:49.702  1037  1530 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 10:28:49.705  1588  1830 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-16 10:28:49.757   305  6603 D libc-netbsd: res_queryN name = europe.pool.ntp.org succeed
,08-16 10:28:49.789  1037  6601 D LocSvc_java: NTP server : europe.pool.ntp.org
,08-16 10:28:49.791  1037  6601 D LocSvc_java: NTP server returned: 1471336130205 (Tue Aug 16 10:28:50 GMT+02:00 2016) reference: 369323 certainty: 14 system time offset: 416
,08-16 10:28:49.792  1037  6601 D LocSvc_java: Sending msg: 10 arg1:0 arg2:1
08-16 10:28:51.385  1037  1523 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1837651144] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-16 10:28:51.397  1037  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1837651131] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 10:28:51.397  1037  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-16 10:28:51.418  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 10:28:51.554  1037  1945 D WifiServiceImplEx: setWifiEnabled: false pid=6149, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-16 10:28:51.554  1037  1945 D WifiService: setWifiEnabled: false pid=6149, uid=10118
08-16 10:28:51.554  1037  1945 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 10:28:51.582  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 10:28:51.583  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 10:28:51.583  1037  1037 D Ulp_jni : JNI:system_update. Event-4
08-16 10:28:51.584  1037  1523 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-16 10:28:51.585  1037  1523 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-16 10:28:51.586  1037  1523 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-16 10:28:51.586  1037  1523 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-16 10:28:51.586  1037  1523 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-16 10:28:51.587  1037  1523 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-16 10:28:51.587  1037  1523 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 10:28:51.587  1037  1523 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-16 10:28:51.590  1037  1523 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-16 10:28:51.590  1037  1523 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-16 10:28:51.605  1037  1523 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-16 10:28:51.609  1037  1522 D LGWifiP2pService: InactiveState{ when=-5ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 10:28:51.609  1037  1522 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 10:28:51.610  1037  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-16 10:28:51.610  6485  6485 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-16 10:28:51.610  1037  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-16 10:28:51.611  1037  1523 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 10:28:51.611  1037  1523 D WifiNative-wlan0: SET ps 1: returned true
08-16 10:28:51.612  1037  6542 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-16 10:28:51.616   305   906 D CommandListener: Clearing all IP addresses on wlan0
08-16 10:28:51.670  1037  1037 D WifiHS20: hidePasspointNotification off =false
,08-16 10:28:51.688  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 10:28:51.688  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-16 10:28:51.693  1928  1928 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-16 10:28:51.694  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 10:28:51.708  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 10:28:51.715  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 10:28:51.716  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 10:28:51.720  1037  1530 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-16 10:28:51.720  1037  1530 D ConnectivityService: ignoring duplicate network state non-change
08-16 10:28:51.720  1037  1530 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
08-16 10:28:51.731  1037  1037 D WifiHS20: hidePasspointNotification off =false
,08-16 10:28:51.735  1037  1522 D LGWifiP2pService: InactiveState{ when=-4ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-16 10:28:51.735  1037  1522 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-16 10:28:51.735  1037  1522 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@f947de
08-16 10:28:51.736  1037  1523 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 10:28:51.736  1037  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 10:28:51.736  1037  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 10:28:51.736  1037  1523 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 10:28:51.737  1037  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 10:28:51.737  3722  3722 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 10:28:51.737  1037  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 10:28:51.738  1037  1523 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-16 10:28:51.738  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 10:28:51.738  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 10:28:51.749  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 10:28:51.752  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 10:28:51.752  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 10:28:51.752  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 10:28:51.752  1037  1037 D WifiScanningService: SCAN_AVAILABLE : 1
08-16 10:28:51.753  1037  1541 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-16 10:28:51.753  1037  1037 D RttService: SCAN_AVAILABLE : 1
08-16 10:28:51.753  1037  1542 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-16 10:28:51.753  1037  1522 D LGWifiP2pService: P2pDisablingState
08-16 10:28:51.754  1037  1522 D LGWifiP2pService: P2pDisablingState{ when=-19ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-16 10:28:51.754  1037  1522 D LGWifiP2pService: p2p socket connection lost
08-16 10:28:51.754  1037  1522 D LGWifiP2pService: P2pDisabledState
08-16 10:28:51.758  1037  1523 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-16 10:28:51.758  1037  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-16 10:28:51.758  6485  6485 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-16 10:28:51.758  1037  1522 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 10:28:51.758  1037  1522 D LGWifiP2pService: DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 10:28:51.759  1037  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-16 10:28:51.759  1037  1523 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 10:28:51.759  1037  1523 D WifiNative-wlan0: SET ps 1: returned true
08-16 10:28:51.760  1928  1928 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-16 10:28:51.761  1928  1928 D WfdsService: WifiP2pState is changed : false
,08-16 10:28:51.763  6296  6296 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-16 10:28:51.763  6296  6296 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 10:28:51.763  6296  6296 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 10:28:51.764  1928  2293 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-16 10:28:51.764  1928  2293 D WfdsService: Set the WFDS Monitor: false
08-16 10:28:51.766  1928  2293 D WfdsMonitor: WFDS Monitor is stopped
08-16 10:28:51.767  1928  2293 D WfdsService: STATE : WfdsDisabledState - enter
08-16 10:28:51.767  1928  6511 D CtrlSupplicant: Received on exit socket, terminate
08-16 10:28:51.767  1928  6511 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-16 10:28:51.767  1928  6511 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-16 10:28:51.767  1928  6511 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-16 10:28:51.768  1928  2293 W WfdsService: DefaultState - msg [9445378] is not handled
08-16 10:28:51.770  1928  2295 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-16 10:28:51.771  6279  6279 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 10:28:51.775  6279  6279 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 10:28:51.781   305   906 D CommandListener: Clearing all IP addresses on wlan0
,08-16 10:28:51.782  1037  1530 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-16 10:28:51.782  1037  1530 D DSQN    : disableDataServiceNotify
08-16 10:28:51.782  1037  1530 D DSQN    : stop dsqn bin
08-16 10:28:51.784  6350  6350 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 10:28:51.784  6350  6350 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 10:28:51.785  1037  1523 D WifiNative-p2p0: doBoolean: TERMINATE
08-16 10:28:51.786  1037  1037 D WifiHS20: hidePasspointNotification off =false
08-16 10:28:51.786  1037  1523 D WifiNative-p2p0: TERMINATE: returned true
08-16 10:28:51.786  1037  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 10:28:51.786  1037  1523 E WifiStateMachine: useWiFiOffloading() : false
08-16 10:28:51.786  1037  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-16 10:28:51.786  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-16 10:28:51.786  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 10:28:51.787  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 10:28:51.787  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 10:28:51.787  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 10:28:51.787  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 10:28:51.789  1928  1928 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-16 10:28:51.789  6350  6350 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-16 10:28:51.790  1037  1530 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-16 10:28:51.790  1037  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 10:28:51.790  1037  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 10:28:51.790  1037  1530 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 10:28:51.790  1037  1530 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-16 10:28:51.791  1588  1830 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-16 10:28:51.791  1037  1530 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
,08-16 10:28:51.791  1037  1530 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-16 10:28:51.791  1037  6541 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-16 10:28:51.791  1037  6541 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-16 10:28:51.791  1037  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-16 10:28:51.791  1037  6541 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-16 10:28:51.792  1037  1530 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-16 10:28:51.792  1037  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-16 10:28:51.792  1037  1530 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-16 10:28:51.792  1037  1530 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 10:28:51.792  1037  1530 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 10:28:51.793  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-16 10:28:51.793  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 10:28:51.793  1037  1037 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-16 10:28:51.794  6149  6149 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 10:28:51.794  6149  6149 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 10:28:51.794  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 10:28:51.794  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 10:28:51.794  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 10:28:51.794  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 10:28:51.794  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 10:28:51.794  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 10:28:51.794  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 10:28:51.794  1037  1521 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-16 10:28:51.794  6149  6149 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 10:28:51.794  6149  6149 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 10:28:51.795  1037  1037 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-16 10:28:51.795  1037  1037 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-16 10:28:51.795  1037  1037 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-16 10:28:51.795  1037  1037 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-16 10:28:51.796  1037  1521 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-16 10:28:51.797  1037 , 1037 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-16 10:28:51.797  1037  1037 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-16 10:28:51.797  1037  1037 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-16 10:28:51.797  1037  1037 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-16 10:28:51.799  6149  6149 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 10:28:51.799  6149  6149 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 10:28:51.799  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 10:28:51.799  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 10:28:51.799  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 10:28:51.799  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 10:28:51.799  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 10:28:51.799  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 10:28:51.799  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 10:28:51.799  6149  6149 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 10:28:51.799  6149  6149 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 10:28:51.799  1838  1838 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 10:28:51.799  1838  1838 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-16 10:28:51.799  1037  1523 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 10:28:51.799  1037  1523 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 10:28:51.799  1037  1530 D NetworkManagementService: Removing idletimer
08-16 10:28:51.800  1037  1530 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 10:28:51.800  6149  6149 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 10:28:51.800  6149  6149 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 10:28:51.800  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 10:28:51.800  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 10:28:51.800  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 10:28:51.800  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 10:28:51.800  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 10:28:51.800  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is co,nnected/connecting to active network: false
08-16 10:28:51.800  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 10:28:51.800  6149  6149 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 10:28:51.800  6149  6149 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 10:28:51.805  3722  3722 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 10:28:51.807  6296  6296 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-16 10:28:51.808  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 10:28:51.808  6296  6296 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 10:28:51.808  6296  6296 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 10:28:51.813  6279  6279 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 10:28:51.819  6279  6279 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 10:28:51.825  6350  6350 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 10:28:51.825  6350  6350 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 10:28:51.828  6350  6350 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-16 10:28:51.830  3722  3722 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 10:28:51.834  6296  6296 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-16 10:28:51.834  6296  6296 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 10:28:51.834  6296  6296 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 10:28:51.837  6279  6279 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 10:28:51.838  6485  6485 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-16 10:28:51.838  6485  6485 I wpa_supplicant: monitor socket send errors count : 1
08-16 10:28:51.838  6485  6485 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1928-4\x00 that cannot receive messages
08-16 10:28:51.839  1037  6506 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-16 10:28:51.839  1037  6506 D WifiMonitor: Dropping event because (p2p0) is stopped
08-16 10:28:51.840  6279  6279 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 10:28:51.845  6350  6350 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 10:28:51.845  6350  6350 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 10:28:51.847  6350  6350 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-16 10:28:51.849  1037  6542 D DhcpStateMachine: StoppedState
08-16 10:28:51.849  1037  6542 D DhcpStateMachine: StoppedState{ when=-89ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-16 10:28:51.851  1588  1588 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 10:28:51.852  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 10:28:51.852  1037  1523 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-16 10:28:51.853  1037  1523 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-16 10:28:51.853  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 10:28:51.858  6296  6296 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-16 10:28:51.862  6279  6279 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-16 10:28:51.866  6279  6279 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 10:28:51.866  6396  6645 W FormManager: Network not available. Please check & try again.
08-16 10:28:51.876  6396  6646 V FormManager: Network unavailable.
,08-16 10:28:51.878  6485  6485 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-16 10:28:51.879  1037  6506 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-16 10:28:51.879  1037  6506 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-16 10:28:51.879  1037  6506 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-16 10:28:51.879  1037  6506 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-16 10:28:51.879  6485  6485 W wpa_supplicant: USIM:  scard_deinit function
08-16 10:28:51.879  1037  6506 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 10:28:51.879  1037  6506 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 10:28:51.880  1037  1523 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=371415
08-16 10:28:51.881  1037  1523 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=371415
08-16 10:28:51.881  1037  1119 D Tethering: InitialState.processMessage what=4
08-16 10:28:51.881  1037  1523 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=371415  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-16 10:28:51.881  6396  6646 V FormManager: Network unavailable.
08-16 10:28:51.882  1037  1523 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=371416  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-16 10:28:51.882  1037  1119 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-16 10:28:51.883  1037  1523 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-16 10:28:51.883  1037  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 10:28:51.891  6279  6279 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-16 10:28:51.891  6279  6279 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-16 10:28:51.891  6279  6279 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-16 10:28:51.891  6279  6279 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,08-16 10:28:51.894  6279  6279 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-16 10:28:51.896  6279  6279 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-16 10:28:51.896  6279  6279 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-16 10:28:51.896  6279  6279 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-16 10:28:51.896  6279  6279 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-16 10:28:51.896  6279  6279 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-16 10:28:51.897  1588  1588 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 10:28:51.897  6279  6279 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-16 10:28:51.898  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 10:28:51.898  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 10:28:51.907  6485  6485 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-16 10:28:51.907  1037  6506 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-16 10:28:51.908  1037  6506 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-TERMINATING 
08-16 10:28:51.908  1037  6506 D WifiMonitor: Disconnecting from the supplicant, no more events
08-16 10:28:51.908  1037  1523 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 37 0
,08-16 10:28:52.014  1928  1928 D WfdsService: Supplicant Connection state is changed : false
,08-16 10:28:52.014  1928  2293 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-16 10:28:52.014  1928  2293 D WfdsService: Set the WFDS Monitor: false
08-16 10:28:52.014  1928  2293 D WfdsMonitor: WFDS Monitor is stopped
,08-16 10:28:52.018  1037  1523 D WifiOffDelayIfNotUsed: stopMonitoring
,08-16 10:28:52.019  1037  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 10:28:52.019  1037  1523 E WifiStateMachine: useWiFiOffloading() : false
08-16 10:28:52.019  1037  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-16 10:28:52.020  4259  4259 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 10:28:52.024  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 10:28:52.024  1928  1928 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-16 10:28:52.027  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-16 10:28:52.028  1037  1527 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-16 10:28:52.028  4259  4259 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 10:28:52.028  1037  1527 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-16 10:28:52.030  6149  6149 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 10:28:52.031  6149  6149 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 10:28:52.031  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 10:28:52.031  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 10:28:52.031  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 10:28:52.031  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 10:28:52.031  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 10:28:52.031  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 10:28:52.031  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 10:28:52.036  6149  6149 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 10:28:52.036  6149  6149 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 10:28:52.036  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 10:28:52.036  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 10:28:52.036  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 10:28:52.036  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 10:28:52.036  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 10:28:52.036  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 10:28:52.036  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 10:28:52.037  2465  2465 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 10:28:52.040  6149  6149 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 10:28:52.040  6149  6149 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 10:28:52.040  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 10:28:52.040  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 10:28:52.040  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 10:28:52.040  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 10:28:52.040  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 10:28:52.040  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 10:28:52.040  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 10:28:52.041  4259  4259 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 10:28:52.048  4259  4259 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-16 10:28:52.055  4259  6647 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-16 10:28:52.059  6296  6296 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-16 10:28:52.059  6296  6296 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 10:28:52.059  6296  6296 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-16 10:28:52.063  4259  6648 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
,08-16 10:28:52.063  4259  6648 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-16 10:28:52.064  6279  6279 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-16 10:28:52.069  6396  6650 W FormManager: Network not available. Please check & try again.
,08-16 10:28:52.075  6279  6279 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-16 10:28:52.081  6396  6651 V FormManager: Network unavailable.
08-16 10:28:52.084  6396  6651 V FormManager: Network unavailable.
,08-16 10:28:52.461  1037  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 10:28:52.477  1037  1119 D Tethering: MasterInitialState.processMessage what=3
08-16 10:28:52.480  1037  1102 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-16 10:28:52.496  6149  6149 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 10:28:52.501  6149  6149 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 10:28:52.503  6149  6149 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 10:28:52.510  3722  3722 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-16 10:28:52.515  3722  6270 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-16 10:28:52.528  5330  5330 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-16 10:28:52.552  1037  1102 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 10:28:52.579  1037  1102 E GpsLocationProvider: No APN found to select.
,08-16 10:28:52.609  2179  2179 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-16 10:28:52.654  1037  1873 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6669 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-16 10:28:52.673   363   363 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 304us total 18.796ms
,08-16 10:28:52.688   363   363 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 286us total 13.687ms
,08-16 10:28:52.704   363   363 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 283us total 14.271ms
,08-16 10:28:52.728  6669  6669 I AppUp4:AppBoxCP: onCreate
,08-16 10:28:52.729  6669  6669 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
08-16 10:28:52.736  6669  6669 I AppUp4:DB:  setFingerPrint start
08-16 10:28:52.737  6669  6669 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-16 10:28:52.743  6669  6669 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-16 10:28:52.743  6669  6669 I AppUp4:DB:  SDK version = 21
08-16 10:28:52.743  6669  6669 I AppUp4:DB:  beforefinger == newfinger no write in DB
,08-16 10:28:52.745  6669  6669 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-16 10:28:52.746  6669  6669 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-16 10:28:52.746  6669  6669 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-16 10:28:52.749  6669  6669 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-16 10:28:52.749  6669  6669 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-16 10:28:52.754  6669  6669 I AppUp4:CustModeStarterReceiver: onReceive
,08-16 10:28:52.803  6669  6669 D LgDataFeature: LgDataFeature() Constructor: none
08-16 10:28:52.803  6669  6669 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 10:28:52.811  6669  6669 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@23822140
,08-16 10:28:52.811  6669  6669 D AppUp4:CustFacade: isCustomizationCompleted : false
,08-16 10:28:52.811  6669  6669 D AppUp4:CustFacade: isPhone : true
,08-16 10:28:52.812  6669  6669 D AppUp4:CustModeStarterReceiver: begin check event
08-16 10:28:52.813  6669  6669 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-16 10:28:52.814  6669  6669 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-16 10:28:52.834  6669  6686 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-16 10:28:52.834  6669  6686 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-16 10:28:52.834  6669  6686 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
,08-16 10:28:52.839  1037  1873 I ActivityManager: Killing 2121:com.lge.music/u0a34 (adj 15): empty #17
,08-16 10:28:52.860   316  2138 V AudioFlinger: 2121 died, releasing its sessions
08-16 10:28:52.860   316  2138 V AudioFlinger:  pid 1838 @ 0
08-16 10:28:52.860   316  2138 V AudioFlinger:  pid 3369 @ 1
08-16 10:28:52.860   316  2138 V AudioFlinger:  pid 3369 @ 2
,08-16 10:28:52.877  1037  1981 W libprocessgroup: failed to open /acct/uid_10034/pid_2121/cgroup.procs: No such file or directory
,08-16 10:28:52.881  4259  4259 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-16 10:28:52.882  4259  4259 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 10:28:52.883  4259  4259 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 10:28:52.887  4259  4259 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 10:28:52.903  4259  6688 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-16 10:28:52.910  4259  6689 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-16 10:28:52.910  4259  6689 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-16 10:28:52.954  1037  1999 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6690 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-16 10:28:53.054  6690  6690 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-16 10:28:53.056  6690  6690 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-16 10:28:53.058  6690  6690 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,08-16 10:28:53.058  6690  6690 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-16 10:28:53.147  6690  6690 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-16 10:28:53.162  6690  6690 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
08-16 10:28:53.223  6690  6690 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-16 10:28:53.280  6690  6690 D LgDataFeature: LgDataFeature() Constructor: none
,08-16 10:28:53.280  6690  6690 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 10:28:53.414  6690  6690 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-16 10:28:53.451  3369  3369 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-16 10:28:53.451  3369  3369 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-16 10:28:53.453  3369  3369 I LgeMiscReceiver: networkInfo.isConnected() = true
08-16 10:28:53.453  3369  3369 D PhoneState: setPdpRejectCasuse : false
,08-16 10:28:53.461  6690  6690 I HubEmail: JNI_OnLoad()
08-16 10:28:53.462  6690  6690 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-16 10:28:53.462  6690  6690 I HubEmail: registerNatives()
08-16 10:28:53.462  6690  6690 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-16 10:28:53.462  6690  6690 I HubEmail: registerNativeMethods()
08-16 10:28:53.462  6690  6690 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-16 10:28:53.462  6690  6690 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
08-16 10:28:53.506  1037  1739 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6716 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-16 10:28:53.519  6690  6715 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 10:28:53.519  6396  6713 W FormManager: Network not available. Please check & try again.
,08-16 10:28:53.523  6396  6714 V FormManager: Network unavailable.
08-16 10:28:53.528  6396  6714 V FormManager: Network unavailable.
08-16 10:28:53.549  1037  1981 I ActivityManager: Killing 5896:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,08-16 10:28:53.589  1037  2037 W libprocessgroup: failed to open /acct/uid_10061/pid_5896/cgroup.procs: No such file or directory
08-16 10:28:53.657  6716  6716 D LgDataFeature: LgDataFeature() Constructor: none
08-16 10:28:53.658  6716  6716 D LgDataFeature: LgDataFeature() Constructor Done, null
08-16 10:28:53.661  6716  6716 D PhoneMonitor: Register our PhoneStateListener
,08-16 10:28:53.685  6716  6716 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-16 10:28:53.691  6716  6716 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-16 10:28:53.728  6716  6716 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
08-16 10:28:53.729  6716  6716 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
,08-16 10:28:53.731  6716  6716 D TelephonyAutoProfiling: [parse] Load xml
08-16 10:28:53.737  6716  6716 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-16 10:28:53.738  6716  6716 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-16 10:28:53.738  6716  6716 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-16 10:28:53.738  6716  6716 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-16 10:28:53.738  6716  6716 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-16 10:28:53.738  6716  6716 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-16 10:28:53.738  6716  6716 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-16 10:28:53.738  6716  6716 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-16 10:28:53.738  6716  6716 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-16 10:28:53.738  6716  6716 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-16 10:28:53.738  6716  6716 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-16 10:28:53.739  6716  6716 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-16 10:28:53.739  6716  6716 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-16 10:28:53.739  6716  6716 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-16 10:28:53.739  6716  6716 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-16 10:28:53.739  6716  6716 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-16 10:28:53.739  6716  6716 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-16 10:28:53.759  6716  6716 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-16 10:28:53.759  1037  1927 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=6745 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-16 10:28:53.761  1037  1927 I ActivityManager: Killing 5933:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,08-16 10:28:53.816  1037  1739 W libprocessgroup: failed to open /acct/uid_10080/pid_5933/cgroup.procs: No such file or directory
,08-16 10:28:54.188  1037  1927 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6770 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
08-16 10:28:54.189  1037  1927 I ActivityManager: Killing 5954:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,08-16 10:28:54.230  1037  1963 W libprocessgroup: failed to open /acct/uid_10097/pid_5954/cgroup.procs: No such file or directory
08-16 10:28:54.277  6770  6770 D DrmBroadcastReceiver: Receive CONNECTIVITY_ACTION
08-16 10:28:54.279  6770  6770 D DrmBroadcastReceiver: 1  network is available. Sync DRM Time with NTP
,08-16 10:28:54.285  6770  6770 V DrmService: Service onCreate
08-16 10:28:54.286  6770  6770 D DrmService: Received new request = 2
08-16 10:28:54.290  6770  6787 I DrmSntpClient: Start Sync process
08-16 10:28:54.290  6770  6787 D DrmSntpClient: Server : 0
08-16 10:28:54.333  1037  2000 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=6788 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-16 10:28:54.336  6770  6787 D DrmSntpClient: Automatic sync but WiFi isn't enabled
08-16 10:28:54.337  6770  6770 D DrmService: Completed !! request = 2
08-16 10:28:54.337  6770  6770 D DrmService: Request count = 0
08-16 10:28:54.341  6770  6770 V DrmService: Service onDestroy
08-16 10:28:54.342  1037  1739 I ActivityManager: Killing 5983:com.lge.eula/1000 (adj 15): empty #17
,08-16 10:28:54.377  1037  1873 W libprocessgroup: failed to open /acct/uid_1000/pid_5983/cgroup.procs: No such file or directory
,08-16 10:28:54.419  1037  1523 E WifiStateMachine:  InitialState CMD_RSSI_POLL 1 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1837648109] gl rssi=-56 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-16 10:28:54.420  1037  1523 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 1 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1837648108] gl rssi=-56 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 10:28:54.580  1037  1872 I art     : Explicit concurrent mark sweep GC freed 130767(6MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 43MB/64MB, paused 2.897ms total 184.945ms
,08-16 10:28:54.630  6788  6788 I art     : Almond Protected OAT
,08-16 10:28:54.683  6788  6788 D WeatherApplication: removeAccount
,08-16 10:28:54.685  6788  6788 D WeatherApplication: Account.length = 0
,08-16 10:28:54.685  6788  6788 E WeatherApplication: OPERATOR:OPEN
08-16 10:28:54.691  6788  6788 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:28:54
08-16 10:28:54.694  6788  6788 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-16 10:28:54.694  6788  6788 D Weather.Utils: 2 : All the weather widget is gone.
08-16 10:28:54.696  6788  6788 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-16 10:28:54.699  6788  6788 D WeatherAncestor: connectivity changed - connection : true
,08-16 10:28:54.701  6788  6788 D WeatherService: 2 : isServiceAlived():false forecastCache:null
08-16 10:28:54.709  6788  6788 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-16 10:28:54.709  6788  6788 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-16 10:28:54.709  6788  6788 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
08-16 10:28:54.739  6788  6788 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-16 10:28:54.739  6788  6788 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:28:54
,08-16 10:28:54.773  1037  1999 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6806 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-16 10:28:54.774  1037  1999 I ActivityManager: Killing 5852:com.android.vending/u0a44 (adj 15): empty #17
08-16 10:28:54.794  1037  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 10:28:54.830  1037  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 10:28:54.832  1037  1102 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-16 10:28:54.832  1037  1873 W libprocessgroup: failed to open /acct/uid_10044/pid_5852/cgroup.procs: No such file or directory
08-16 10:28:54.833  1037  1119 D Tethering: MasterInitialState.processMessage what=3
08-16 10:28:54.835  6149  6149 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 10:28:54.836  6149  6149 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 10:28:54.837  6149  6149 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 10:28:54.842  1037  1119 D Tethering: MasterInitialState.processMessage what=3
,08-16 10:28:54.846  6149  6149 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 10:28:54.847  6149  6149 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 10:28:54.847  6149  6149 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 10:28:54.851  5330  5330 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-16 10:28:54.853  1037  1102 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-16 10:28:54.854  5330  5330 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-16 10:28:54.855  1037  1102 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-16 10:28:54.855  1037  1102 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 10:28:54.926   278   455 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-16 10:28:54.926   278   455 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-16 10:28:54.926   278   455 W Vold    : Returning OperationFailed - no handler for errno 0
08-16 10:28:54.928  6806  6833 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,08-16 10:28:54.932   278   455 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,08-16 10:28:54.932   278   455 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-16 10:28:54.932   278   455 W Vold    : Returning OperationFailed - no handler for errno 0
08-16 10:28:54.933  6806  6833 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-16 10:28:54.945   278   455 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-16 10:28:54.945   278   455 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
,08-16 10:28:54.945   278   455 W Vold    : Returning OperationFailed - no handler for errno 0
,08-16 10:28:54.945  6806  6838 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,08-16 10:28:54.948   278   455 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-16 10:28:54.948   278   455 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-16 10:28:54.948   278   455 W Vold    : Returning OperationFailed - no handler for errno 0
08-16 10:28:54.948  6806  6838 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-16 10:28:55.192  6806  6806 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-16 10:28:55.203  6806  6806 I LibraryLoader: Loading: webviewchromium
08-16 10:28:55.207  6806  6806 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 4747-4751)
,08-16 10:28:55.207  6806  6806 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 10:28:55.215  6806  6806 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2a9fa3a5}
08-16 10:28:55.217  6806  6806 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-16 10:28:55.217  6806  6806 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0,
08-16 10:28:55.251  6806  6806 I BrowserStartupController: Initializing chromium process, renderers=0
08-16 10:28:55.254  6806  6806 W art     : Attempt to remove local handle scope entry from IRT, ignoring,
,08-16 10:28:55.275  6806  6806 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-16 10:28:55.293  6806  6806 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-16 10:28:55.297  6806  6806 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
,08-16 10:28:55.302   316  1371 V AudioPolicyService: registerClient() client 0xb1023e40, uid 10093
08-16 10:28:55.304  6806  6862 W AudioManagerAndroid: Requires BLUETOOTH permission
08-16 10:28:55.324  6806  6806 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 10:28:55.324  6806  6806 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 10:28:55.324  6806  6806 I Adreno-EGL: Build Date: 12/12/14 금
08-16 10:28:55.324  6806  6806 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 10:28:55.324  6806  6806 I Adreno-EGL: Remote Branch: 
08-16 10:28:55.324  6806  6806 I Adreno-EGL: Local Patches: 
08-16 10:28:55.324  6806  6806 I Adreno-EGL: Reconstruct Branch: 
,08-16 10:28:55.410  6806  6806 I NSApplication: Starting up...
,08-16 10:28:55.482  1037  1873 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6878 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-16 10:28:55.484  1037  2000 I ActivityManager: Killing 6324:com.lge.lifetracker/u0a37 (adj 15): empty #17
,08-16 10:28:55.547  1037  1901 W libprocessgroup: failed to open /acct/uid_10037/pid_6324/cgroup.procs: No such file or directory
,08-16 10:28:55.588  6878  6878 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-16 10:28:55.915  3722  3722 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-16 10:28:55.918  3722  6270 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-16 10:28:55.937  2179  2179 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-16 10:28:55.953  6669  6669 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-16 10:28:55.953  6669  6669 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-16 10:28:55.954  6669  6669 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-16 10:28:55.954  6669  6669 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-16 10:28:55.958  6669  6669 I AppUp4:CustModeStarterReceiver: onReceive
08-16 10:28:55.961  6669  6669 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@23822140
08-16 10:28:55.961  6669  6669 D AppUp4:CustFacade: isCustomizationCompleted : false
08-16 10:28:55.961  6669  6669 D AppUp4:CustFacade: isPhone : true
08-16 10:28:55.962  6669  6669 D AppUp4:CustModeStarterReceiver: begin check event
08-16 10:28:55.962  6669  6669 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-16 10:28:55.966  4259  4259 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-16 10:28:55.967  4259  4259 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 10:28:55.968  4259  4259 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-16 10:28:55.971  4259  4259 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 10:28:55.978  6690  6690 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-16 10:28:55.980  4259  6911 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-16 10:28:56.004  4259  6912 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-16 10:28:56.005  4259  6912 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-16 10:28:56.009  6690  6914 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 10:28:56.012  6396  6917 W FormManager: Network not available. Please check & try again.
08-16 10:28:56.012  3369  3369 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-16 10:28:56.012  3369  3369 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-16 10:28:56.012  3369  3369 I LgeMiscReceiver: networkInfo.isConnected() = false
08-16 10:28:56.014  6716  6716 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-16 10:28:56.015  6716  6716 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-16 10:28:56.029  6788  6788 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:28:56
,08-16 10:28:56.036  6396  6923 V FormManager: Network unavailable.
08-16 10:28:56.038  6788  6788 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-16 10:28:56.038  6788  6788 D Weather.Utils: 2 : All the weather widget is gone.
08-16 10:28:56.038  6788  6788 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-16 10:28:56.039  6788  6788 D WeatherAncestor: connectivity changed - connection : true
08-16 10:28:56.039  6396  6923 V FormManager: Network unavailable.
08-16 10:28:56.040  6788  6788 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@36bc39be
08-16 10:28:56.041  6788  6788 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-16 10:28:56.041  6788  6788 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-16 10:28:56.041  6788  6788 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-16 10:28:56.041  6788  6788 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-16 10:28:56.041  6788  6788 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:28:56
,08-16 10:28:56.069  3722  3722 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-16 10:28:56.070  3722  6270 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-16 10:28:56.086  2179  2179 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-16 10:28:56.097  6669  6669 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-16 10:28:56.097  6669  6669 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,08-16 10:28:56.097  6669  6669 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-16 10:28:56.097  6669  6669 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-16 10:28:56.099  6669  6669 I AppUp4:CustModeStarterReceiver: onReceive
08-16 10:28:56.102  6669  6669 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@23822140
08-16 10:28:56.102  6669  6669 D AppUp4:CustFacade: isCustomizationCompleted : false
08-16 10:28:56.102  6669  6669 D AppUp4:CustFacade: isPhone : true
08-16 10:28:56.103  6669  6669 D AppUp4:CustModeStarterReceiver: begin check event
08-16 10:28:56.103  6669  6669 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-16 10:28:56.107  4259  4259 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-16 10:28:56.107  4259  4259 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 10:28:56.108  4259  4259 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 10:28:56.118  4259  4259 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-16 10:28:56.125  6690  6690 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-16 10:28:56.126  4259  6934 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-16 10:28:56.128  4259  6935 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-16 10:28:56.128  4259  6935 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-16 10:28:56.146  6690  6936 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 10:28:56.150  3369  3369 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,08-16 10:28:56.150  3369  3369 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-16 10:28:56.151  3369  3369 I LgeMiscReceiver: networkInfo.isConnected() = false
08-16 10:28:56.153  6716  6716 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-16 10:28:56.153  6716  6716 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-16 10:28:56.161  6396  6939 W FormManager: Network not available. Please check & try again.
,08-16 10:28:56.164  6788  6788 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:28:56
,08-16 10:28:56.166  6788  6788 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-16 10:28:56.166  6788  6788 D Weather.Utils: 2 : All the weather widget is gone.
08-16 10:28:56.167  6396  6940 V FormManager: Network unavailable.
08-16 10:28:56.167  6788  6788 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-16 10:28:56.168  6788  6788 D WeatherAncestor: connectivity changed - connection : true
08-16 10:28:56.168  6788  6788 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@36bc39be
08-16 10:28:56.169  6788  6788 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-16 10:28:56.169  6788  6788 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
,08-16 10:28:56.169  6788  6788 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-16 10:28:56.169  6788  6788 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-16 10:28:56.169  6788  6788 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:28:56
08-16 10:28:56.176  6396  6940 V FormManager: Network unavailable.
,08-16 10:28:56.588  1037  2000 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 10:28:56.589  1037  2000 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-16 10:28:56.626  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 10:28:56.626  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 10:28:56.626  1037  1037 D Ulp_jni : JNI:system_update. Event-4
08-16 10:28:56.627  1037  1119 D BluetoothManagerService: Message: 1
08-16 10:28:56.627  1037  1119 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-16 10:28:56.656  1037  1119 D BluetoothManagerService: Message: 20
08-16 10:28:56.656  1037  1119 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2306c853:true
,08-16 10:28:56.660  6435  6435 D BluetoothAdapterState: make
08-16 10:28:56.665  6435  6435 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-16 10:28:56.665  6435  6435 I bluedroid-qcom: init
08-16 10:28:56.666  6435  6951 I BluetoothAdapterState: Entering OffState
08-16 10:28:56.667  6435  6435 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-16 10:28:56.667  6435  6435 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-16 10:28:56.667  6435  6435 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-16 10:28:56.667  6435  6435 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-16 10:28:56.667  6435  6435 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-16 10:28:56.669  6435  6435 I bluedroid-qcom: get_profile_interface socket
08-16 10:28:56.669  6435  6435 I bluedroid-qcom: get_profile_interface map_client
,08-16 10:28:56.674  6435  6955 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-16 10:28:56.672  6954  6954 W bdaddr_loader: type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 10:28:56.672  6954  6954 W bdaddr_loader: type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 10:28:56.684  6954  6954 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-16 10:28:56.684  6954  6954 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-16 10:28:56.684  6954  6954 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,08-16 10:28:56.690  1037  1037 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-16 10:28:56.690  1037  1119 D BluetoothManagerService: Message: 40
08-16 10:28:56.690  1037  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-16 10:28:56.691  6435  6451 I bluedroid-qcom: config_hci_snoop_log
08-16 10:28:56.693  1037  1119 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-16 10:28:56.693  1037  1119 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-16 10:28:56.706  6954  6954 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
,08-16 10:28:56.713  6435  6955 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-16 10:28:56.716  1037  1037 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-16 10:28:56.716  1037  1037 D BluetoothManagerService: Stored Bluetooth name: G3
08-16 10:28:56.717  6435  6955 D BluetoothAdapterProperties: Name is: G3
08-16 10:28:56.717  6435  6951 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-16 10:28:56.717  6435  6951 D BluetoothAdapterProperties: Setting state to 11
08-16 10:28:56.718  6435  6951 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-16 10:28:56.719  6435  6951 I LGBluetoothServiceJni: classInitNative: succeeds
08-16 10:28:56.719  1037  1119 D BluetoothManagerService: Message: 60
08-16 10:28:56.719  1037  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-16 10:28:56.720  1037  1119 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-16 10:28:56.721  1588  1588 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 10:28:56.722  6954  6954 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-16 10:28:56.722  6954  6954 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-16 10:28:56.727  1928  1928 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-16 10:28:56.727  6149  6149 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 10:28:56.731  6279  6279 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
,08-16 10:28:56.736  6149  6149 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 10:28:56.737  6149  6149 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 10:28:56.738  6435  6435 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-16 10:28:56.739  6435  6435 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 10:28:56.739  6435  6435 V BluetoothPbapReceiver: ***********state = 11
08-16 10:28:56.742  2179  2179 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 10:28:56.758  1037  1522 D LGWifiP2pService: P2pDisabledState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-16 10:28:56.759  1037  1522 D LGWifiP2pService: DefaultState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 10:28:56.788  1037  1523 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
08-16 10:28:56.788  1037  1945 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6973 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-16 10:28:56.788  1037  1523 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
08-16 10:28:56.791  6435  6951 D BluetoothBondStateMachine: make
,08-16 10:28:56.794  6435  6951 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36bc39be
08-16 10:28:56.794  6435  6951 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-16 10:28:56.794  6435  6951 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36bc39be
08-16 10:28:56.794  6435  6951 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-16 10:28:56.795  6435  6951 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-16 10:28:56.795  6435  6982 I BluetoothBondStateMachine: StableState(): Entering Off State
08-16 10:28:56.798  6435  6951 E BluetoothAdapterService: File transfer profiles supported!!
08-16 10:28:56.802  6435  6951 E BluetoothAdapterService: File transfer profiles supported!!
08-16 10:28:56.804  6435  6435 D HeadsetService: Received start request. Starting profile...
08-16 10:28:56.804  6435  6435 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-16 10:28:56.805  6435  6435 D LGBluetoothHfpAdapter: Version 1.6
,08-16 10:28:56.808  6435  6951 E BluetoothAdapterService: File transfer profiles supported!!
08-16 10:28:56.808  6435  6435 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-16 10:28:56.809  6435  6435 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-16 10:28:56.809  6435  6435 D HeadsetStateMachine: make
08-16 10:28:56.812  6435  6951 E BluetoothAdapterService: File transfer profiles supported!!
08-16 10:28:56.817  6435  6951 E BluetoothAdapterService: File transfer profiles supported!!
08-16 10:28:56.820  6435  6951 E BluetoothAdapterService: File transfer profiles supported!!
,08-16 10:28:56.826  6435  6951 E BluetoothAdapterService: File transfer profiles supported!!
08-16 10:28:56.835  6435  6435 D LgDataFeature: LgDataFeature() Constructor: none
,08-16 10:28:56.835  6435  6435 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 10:28:56.839  6435  6435 D HeadsetStateMachine: max_hf_connections = 1
08-16 10:28:56.839  6435  6435 I bluedroid-qcom: get_profile_interface handsfree
08-16 10:28:56.839  6435  6951 V LGMDMManager: Create singleton instance
08-16 10:28:56.840  6435  6951 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-16 10:28:56.840  6435  6435 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-16 10:28:56.841   316  1372 V AudioPolicyService: registerClient() client 0xb558a3e0, uid 1002
08-16 10:28:56.841   316  2138 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-16 10:28:56.841   316  2138 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-16 10:28:56.841   316  2138 V AudioPolicyManagerEx: getOutput() returns output 2
08-16 10:28:56.841  6435  6435 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
,08-16 10:28:56.841   316  1371 V AudioFlinger: registerClient() client 0xb14331d8, pid 6435
08-16 10:28:56.842   316  1366 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 10:28:56.842   316  1366 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 10:28:56.842  6435  6435 V ToneGenerator: Create Track: 0xb4928a80
,08-16 10:28:56.842  6435  6435 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-16 10:28:56.842  6435  6435 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-16 10:28:56.842   316  2137 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-16 10:28:56.842   316  2137 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
,08-16 10:28:56.842   316  2137 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-16 10:28:56.842   316  2137 V AudioPolicyManagerEx: getOutput() returns output 2
,08-16 10:28:56.842   316  1367 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 10:28:56.842  6435  6435 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-16 10:28:56.842   316  1367 V AudioSystem: ioConfigChanged() opening already existing output! 4
,08-16 10:28:56.842  1588  2061 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 10:28:56.842  1588  2061 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 10:28:56.842   316  1371 I AudioFlinger: isAudioPlaybackHookOn() false
08-16 10:28:56.842  1588  2061 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
,08-16 10:28:56.842  1588  2061 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 10:28:56.842   316   316 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
,08-16 10:28:56.842   316   316 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-16 10:28:56.842  1838  4357 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 10:28:56.842   316   316 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-16 10:28:56.842  1838  4357 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 10:28:56.842   316   316 V AudioPolicyManagerEx: getOutput() returns output 2
08-16 10:28:56.842  1838  4357 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 10:28:56.842  1037  1560 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 10:28:56.842  1838  4357 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 10:28:56.842  1037  1560 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 10:28:56.843  1037  1560 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 10:28:56.843  1037  1560 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 10:28:56.843  6435  6435 V AudioSystem: getLatency() output 2, latency 50
08-16 10:28:56.843  3369  3385 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 10:28:56.843  3369  3385 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 10:28:56.843  6435  6961 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 10:28:56.843  3369  3385 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 10:28:56.843  6435  6961 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-16 10:28:56.843  3369  3385 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 10:28:56.843  6435  6435 V AudioSystem: getFrameCount() output 2, frameCount 960
08-16 10:28:56.843  6435  6435 V AudioTrack: createTrack_l() output 2 afLatency 50
,08-16 10:28:56.843  6435  6961 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 10:28:56.843  6435  6961 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-16 10:28:56.843   316  1372 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-16 10:28:56.843   316  1372 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-16 10:28:56.843   316  1372 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-16 10:28:56.843   316  1372 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-16 10:28:56.843   316  1372 V AudioFlinger: createTrack() lSessionId: 22
08-16 10:28:56.844  6435  6435 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-16 10:28:56.844   316  1372 V AudioFlinger: acquiring 22 from 6435, for 6435
08-16 10:28:56.844   316  1372 V AudioFlinger:  added new entry for 22
08-16 10:28:56.844  6435  6435 V ToneGenerator: ToneGenerator INIT OK, time: 376388
08-16 10:28:56.844  6435  6435 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36bc39be
08-16 10:28:56.844  6435  6990 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-16 10:28:56.844  6435  6990 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-16 10:28:56.845  6435  6990 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-16 10:28:56.845  6435  6990 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-16 10:28:56.845   316   316 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6435
08-16 10:28:56.845  6435  6435 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36bc39be
08-16 10:28:56.845   316   316 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-16 10:28:56.845   316   316 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-16 10:28:56.845   316   316 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-16 10:28:56.845   316   316 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-16 10:28:56.845   316   316 V voice   : voice_set_parameters: exit with code(0)
08-16 10:28:56.845   316   316 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-16 10:28:56.845   316   316 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-16 10:28:56.846   316   316 V msm8974_platform: platform_set_parameters: exit with code(0)
08-16 10:28:56.846   316   316 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-16 10:28:56.846   316   316 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-16 10:28:56.846   316   316 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-16 10:28:56.846  6435  6435 D A2dpService: Received start request. Starting profile...
08-16 10:28:56.846  6435  6990 V ToneGenerator: ToneGenerator destructor
08-16 10:28:56.846  6435  6990 V ToneGenerator: stopTone
08-16 10:28:56.846  6435  6990 V ToneGenerator: Delete Track: 0xb4928a80
08-16 10:28:56.846  6435  6990 V AudioTrack: ~AudioTrack, releasing session id from 6435 on behalf of 6435
08-16 10:28:56.847   316  1372 V AudioFlinger: releasing 22 from 6435 for 6435
08-16 10:28:56.847   316  1372 V AudioFlinger:  decremented refcount to 0
08-16 10:28:56.847  6435  6435 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-16 10:28:56.847   316  1372 V AudioFlinger: purging stale effects
08-16 10:28:56.847   316  1372 V AudioPolicyService: AudioCommandThread() adding release output 2
08-16 10:28:56.847   316  1372 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-16 10:28:56.847   316  1372 V AudioFlinger: PlaybackThread::Track destructor
08-16 10:28:56.847   316  1269 V AudioPolicyService: AudioCommandT,hread() waking up
08-16 10:28:56.847   316  1372 V AudioFlinger: removeClient_l() pid 6435, calling pid 316
08-16 10:28:56.847   316  1269 V AudioPolicyService: AudioCommandThread() processing release output 2
08-16 10:28:56.847   316  1269 V AudioPolicyManager: releaseOutput() 2
08-16 10:28:56.847   316  1269 V AudioPolicyService: AudioCommandThread() going to sleep
08-16 10:28:56.847  6435  6435 V Avrcp   : make
08-16 10:28:56.848  6435  6435 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-16 10:28:56.848  6435  6435 I bluedroid-qcom: get_profile_interface avrcp
08-16 10:28:56.852  1037  1963 W Process : Unable to open /proc/6994/status
08-16 10:28:56.856  6435  6435 V AudioManager: registerRemoteController: size of Media player list: 0
,08-16 10:28:56.860  6435  6435 E AudioManager: No RCC entry present to update
08-16 10:28:56.860  6435  6435 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-16 10:28:56.863  6435  6435 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-16 10:28:56.863  6435  6435 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-16 10:28:56.863  6435  6435 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-16 10:28:56.866  6435  6435 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-16 10:28:56.934  6973  6973 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-16 10:28:56.934  6973  6973 W LG Account v2.2: No ProfileInfo entries
08-16 10:28:56.934  6973  6973 I LG Account v2.2: isEnabled: false
08-16 10:28:56.934  6973  6973 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-16 10:28:56.934  6973  6973 I Feature : [Lifetracker]Country: EU
08-16 10:28:56.934  6973  6973 I Feature : [Lifetracker]Operator: OPEN
08-16 10:28:56.935  6973  6973 I Feature : [Lifetracker]Ranking support: false
08-16 10:28:56.935  6973  6973 I Feature : [Lifetracker]Comfort support: false
08-16 10:28:56.935  6973  6973 I Feature : [Lifetracker]Accessory: true
08-16 10:28:56.935  6973  6973 I Feature : [Lifetracker]Health device: true
08-16 10:28:56.935  6973  6973 I Feature : [Lifetracker]Extra Pedometer: false
08-16 10:28:56.935  6973  6973 I Feature : [Lifetracker]Blood glucose device: false
08-16 10:28:56.935  6973  6973 I Feature : [Lifetracker]Device Number: 3
08-16 10:28:56.943  6279  6279 D BluetoothPermissionRequest: onReceive
,08-16 10:28:56.946  6279  6279 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-16 10:28:56.961  1037  2034 V SIM_STK : Menu title from STK is T-Mobile
08-16 10:28:56.961  1037  2034 V SIM_STK : Menu title from STK is T-Mobile
,08-16 10:28:57.032  1037  1872 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-16 10:28:57.041  6435  6435 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-16 10:28:57.045  6435  6435 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-16 10:28:57.046  6435  6435 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-16 10:28:57.046  6435  6435 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-16 10:28:57.046  6435  6435 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-16 10:28:57.047  6435  6435 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-16 10:28:57.047  6435  6435 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-16 10:28:57.047  6435  6435 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-16 10:28:57.047  6435  6435 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-16 10:28:57.047  6435  6435 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-16 10:28:57.047  6435  6435 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-16 10:28:57.047  6435  6435 I BluetoothA2dpServiceJni: classInitNative
08-16 10:28:57.047  6435  6435 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-16 10:28:57.047  6435  6435 D A2dpStateMachine: make
,08-16 10:28:57.049  6435  6435 I bluedroid-qcom: get_profile_interface a2dp
08-16 10:28:57.050  6435  7000 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-16 10:28:57.052  6435  6435 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-16 10:28:57.052  6435  6435 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-16 10:28:57.053  6435  6435 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36bc39be
08-16 10:28:57.053  6435  6999 D A2dpStateMachine: Enter Disconnected: -2
08-16 10:28:57.054  6435  6435 I BluetoothHidServiceJni: classInitNative: succeeds
08-16 10:28:57.056  6435  6435 D HidService: Received start request. Starting profile...
08-16 10:28:57.056  6435  6435 I bluedroid-qcom: get_profile_interface hidhost
08-16 10:28:57.056  6435  6435 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36bc39be
08-16 10:28:57.056  6435  6435 I BluetoothHealthServiceJni: classInitNative: succeeds
08-16 10:28:57.058  6435  6435 D HealthService: Received start request. Starting profile...
08-16 10:28:57.060  6435  6435 I bluedroid-qcom: get_profile_interface health
08-16 10:28:57.061  6435  6435 I LGBluetoothHealthServiceJni: classInitNative: succeeds
,08-16 10:28:57.061  6435  6435 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36bc39be
,08-16 10:28:57.062  6435  6435 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-16 10:28:57.063  6435  6435 D PanService: Received start request. Starting profile...,
08-16 10:28:57.063  6435  6435 D BluetoothPanServiceJni: initializeNative(L110): pan
08-16 10:28:57.063  6435  6435 I bluedroid-qcom: get_profile_interface pan
08-16 10:28:57.068  6435  6435 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
,08-16 10:28:57.068  6435  6435 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36bc39be
08-16 10:28:57.069  6435  6435 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-16 10:28:57.074  6435  6435 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-16 10:28:57.075  6435  6435 D BtGatt.GattService: Received start request. Starting profile...
08-16 10:28:57.075  6435  6435 D BtGatt.GattService: start()
08-16 10:28:57.075  6435  6435 I bluedroid-qcom: get_profile_interface gatt
,08-16 10:28:57.075  6435  6435 D BtGatt.AdvertiseManager: advertise manager created
,08-16 10:28:57.079  6435  6435 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36bc39be
08-16 10:28:57.081  6435  6435 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36bc39be
08-16 10:28:57.081  6435  6435 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-16 10:28:57.082  6435  6435 V BluetoothMapService: BluetoothMapBinder()
08-16 10:28:57.083  6435  6435 D BluetoothMapService: Received start request. Starting profile...
08-16 10:28:57.083  6435  6435 D BluetoothMapService: start()
08-16 10:28:57.085  6435  6435 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-16 10:28:57.086  6435  6435 D BluetoothMapEmailAppObserver: createReceiver()
08-16 10:28:57.087  6435  6435 D BluetoothMapEmailAppObserver: initObservers()
08-16 10:28:57.087  6435  6435 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
,08-16 10:28:57.094  6435  6435 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36bc39be
08-16 10:28:57.094  6435  6435 D HeadsetStateMachine: Proxy object connected
08-16 10:28:57.095  6435  6435 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-16 10:28:57.095  6435  6435 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-16 10:28:57.100  6435  6435 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 10:28:57.100  6435  6990 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-16 10:28:57.101  6435  6990 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-16 10:28:57.101  6435  6990 D HeadsetStateMachine: Disconnected process message: 11, size: 0
,08-16 10:28:57.105  6435  6435 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 10:28:57.110  6435  6435 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 10:28:57.114  6435  6435 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 10:28:57.115  6435  6435 V PanService: [BTUI] SIM Extra State :ABSENT
,08-16 10:28:57.120  6435  6435 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 10:28:57.123  6435  6435 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-16 10:28:57.123  6435  6435 V BluetoothMapService: Handler(): got msg=1
08-16 10:28:57.124  6435  6951 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-16 10:28:57.124  6435  6951 I bluedroid-qcom: enable
08-16 10:28:57.125  6435  6951 I bt_hci_bdroid: init
08-16 10:28:57.125  6435  7007 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-16 10:28:57.125  6435  7007 I bt-btu  : btu_task pending for preload complete event
08-16 10:28:57.125  6435  6435 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-16 10:28:57.126  6435  6951 I bt_vendor: bt-vendor : init
08-16 10:28:57.126  6435  6951 I bt_vendor: bt-vendor : get_bt_soc_type
08-16 10:28:57.126  6435  6951 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-16 10:28:57.126  6435  6951 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-16 10:28:57.126  6435  6951 D bt_userial_mct: userial_init
08-16 10:28:57.127  6435  6951 D bt_hci_bdroid: set_power 1
08-16 10:28:57.127  6435  6951 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-16 10:28:57.127  6435  6951 I bt_vendor: Starting hciattach daemon
08-16 10:28:57.127  6435  6951 I bt_vendor: try to set true
08-16 10:28:57.127  6435  6435 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 10:28:57.127  6435  6435 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 10:28:57.127  6435  6435 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 10:28:57.127  6435  6435 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 10:28:57.127  6435  6435 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
,08-16 10:28:57.122  7010  7010 W sh      : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 10:28:57.122  7010  7010 W sh      : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 10:28:57.159  7011  7011 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-16 10:28:57.219  7020  7020 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-16 10:28:57.228  7021  7021 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-16 10:28:57.242  7023  7023 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-16 10:28:57.251  7024  7024 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
08-16 10:28:57.259  7025  7025 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-16 10:28:57.266  7026  7026 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
08-16 10:28:57.300  7028  7028 I libmdmdetect: ESOC framework not supported
08-16 10:28:57.300  7028  7028 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-16 10:28:57.311  7028  7028 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-16 10:28:57.311  7028  7028 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-16 10:28:57.311  7028  7028 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-16 10:28:57.311  7028  7028 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
,08-16 10:28:57.311  7028  7028 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-16 10:28:57.311  7028  7028 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-16 10:28:57.311  7028  7028 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-16 10:28:57.350  7028  7029 E QC-QMI  : qmi_client [7028] 14: failed to locate client data
,08-16 10:28:57.356   479   479 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
,08-16 10:28:57.356   479   479 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
08-16 10:28:57.409  7030  7030 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-16 10:28:57.446  7034  7034 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-16 10:28:57.479  6435  6951 I bt_vendor: bluetooth satus is on
08-16 10:28:57.479  6435  6951 D bt_hci_bdroid: preload
08-16 10:28:57.480  6435  7009 D bt_userial_mct: userial_open(port:0)
08-16 10:28:57.480  6435  7009 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-16 10:28:57.483  6435  7009 I bt_vendor: Done intiailizing UART
08-16 10:28:57.483  6435  7009 I bt_vendor: Done intiailizing UART
08-16 10:28:57.483  6435  7009 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-16 10:28:57.483  6435  7009 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-16 10:28:57.483  6435  7007 I bt-btu  : btu_task received preload complete event
08-16 10:28:57.483  6435  7036 D bt_userial_mct: Entering userial_read_thread()
08-16 10:28:57.484  6435  7007 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-16 10:28:57.484  6435  7007 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-16 10:28:57.489  6435  7007 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-16 10:28:57.496  6435  7007 I         : BTE_InitTraceLevels -- TRC_HCI
08-16 10:28:57.496  6435  7007 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-16 10:28:57.496  6435  7007 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-16 10:28:57.496  6435  7007 I         : BTE_InitTraceLevels -- TRC_AVDT
08-16 10:28:57.496  6435  7007 I         : BTE_InitTraceLevels -- TRC_AVRC
08-16 10:28:57.496  6435  7007 I         : BTE_InitTraceLevels -- TRC_A2D
08-16 10:28:57.496  6435  7007 I         : BTE_InitTraceLevels -- TRC_BNEP
08-16 10:28:57.496  6435  7007 I         : BTE_InitTraceLevels -- TRC_BTM
08-16 10:28:57.496  6435  7007 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-16 10:28:57.496  6435  7007 I         : BTE_InitTraceLevels -- TRC_GAP
08-16 10:28:57.496  6435  7007 I         : BTE_InitTraceLevels -- TRC_PAN
08-16 10:28:57.496  6435  7007 I         : BTE_InitTraceLevels -- TRC_SDP
08-16 10:28:57.496  6435  7007 I         : BTE_InitTraceLevels -- TRC_GATT
08-16 10:28:57.496  6435  7007 I         : BTE_InitTraceLevels -- TRC_SMP
08-16 10:28:57.496  6435  7007 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-16 10:28:57.496  6435  7007 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-16 10:28:57.584  6435  7007 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-16 10:28:57.584  6435  7007 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0244061 
08-16 10:28:57.584  6435  7007 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0244061 
,08-16 10:28:57.609  6435  6955 E bt-btif : Calling BTA_HhEnable
08-16 10:28:57.609  6435  6955 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-16 10:28:57.609  6435  6955 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-16 10:28:57.612  6435  7007 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-16 10:28:57.612  6435  7007 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-16 10:28:57.612  6435  7007 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-16 10:28:57.613  6435  7007 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-16 10:28:57.613  6435  7007 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-16 10:28:57.614  6435  6955 D BluetoothAdapterProperties: Name is: G3
08-16 10:28:57.616  6435  6955 D BluetoothAdapterProperties: Scan Mode:20
08-16 10:28:57.616  6435  6955 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 10:28:57.617  6435  6955 D bt_hci_bdroid: postload
08-16 10:28:57.617  6435  7009 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 10:28:57.618  6435  7009 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 10:28:57.618  6435  7007 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-16 10:28:57.619  6435  7009 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 10:28:57.619  6435  7009 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 10:28:57.619  6435  6955 D bte_conf: Device ID record 1 : primary
08-16 10:28:57.619  6435  6955 D bte_conf:   vendorId            = 00c4
08-16 10:28:57.619  6435  6955 D bte_conf:   vendorIdSource      = 0001
08-16 10:28:57.619  6435  6955 D bte_conf:   product             = 13a1
08-16 10:28:57.619  6435  6955 D bte_conf:   version             = 1000
08-16 10:28:57.619  6435  6955 D bte_conf:   clientExecutableURL = 
08-16 10:28:57.619  6435  6955 D bte_conf:   serviceDescription  = 
08-16 10:28:57.619  6435  6955 D bte_conf:   documentationURL    = 
08-16 10:28:57.619  6435  6955 D bte_conf: bte_load_did_conf no section named DID2.
08-16 10:28:57.623  6435  6951 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-16 10:28:57.623  6435  6951 D BluetoothAdapterProperties: ScanMode =  20
08-16 10:28:57.623  6435  6951 D BluetoothAdapterProperties: State =  11
08-16 10:28:57.624  6435  6951 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-16 10:28:57.624  6435  6951 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-16 10:28:57.624  6435  6951 D BluetoothAdapterProperties: Setting state to 12
08-16 10:28:57.624  6435  6951 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-16 10:28:57.622  7041  7041 W sh      : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 10:28:57.622  7041  7041 W sh      : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 10:28:57.631  1037  1119 D BluetoothManagerService: Message: 60
08-16 10:28:57.631  1037  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-16 10:28:57.631  1037  1119 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
08-16 10:28:57.632  6435  7007 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 10:28:57.632  6435  7007 W bt-smp  : Plain text(LSB ~ MSB) = 9a 10 4a 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 10:28:57.632  6435  7007 W bt-smp  : Encrypted text(LSB ~ MSB) = 26 2a a5 6d 20 fa b4 c7 e1 86 e4 ac 03 a2 d3 35 
08-16 10:28:57.632  6435  7009 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 10:28:57.632  6435  7007 W bt-btm  : Stopping oneshot timer
08-16 10:28:57.632  6435  6955 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-16 10:28:57.633  6435  6955 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-16 10:28:57.643  6435  7036 E bt_mct  : hci lib postload completed
,08-16 10:28:57.647  6435  6951 I BluetoothAdapterState: Entering On State
08-16 10:28:57.648  1838  1853 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 10:28:57.654  6435  6951 D LGBluetoothServiceAdapter: [BTUI] OnState
08-16 10:28:57.654  6435  6951 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-16 10:28:57.656  6435  6951 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,08-16 10:28:57.658  6435  6951 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-16 10:28:57.668  6435  6955 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 10:28:57.668  6435  6955 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
,08-16 10:28:57.677  6435  7007 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 10:28:57.677  6435  7007 W bt-smp  : Plain text(LSB ~ MSB) = f5 60 4f 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 10:28:57.677  6435  7007 W bt-smp  : Encrypted text(LSB ~ MSB) = 6f ae 64 53 38 ad 33 ad f9 0e 11 bb c5 b0 03 66 
08-16 10:28:57.677  6435  7007 W bt-btm  : Stopping oneshot timer
08-16 10:28:57.682  1838  1838 D BluetoothHeadset: Proxy object connected
,08-16 10:28:57.689  1037  1119 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 10:28:57.690  6435  7007 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 10:28:57.690  6435  7007 W bt-smp  : Plain text(LSB ~ MSB) = 3b d0 4e 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 10:28:57.690  6435  7007 W bt-smp  : Encrypted text(LSB ~ MSB) = 04 07 40 bf 69 4f 03 d1 2d 47 b0 54 21 d2 72 df 
08-16 10:28:57.690  6435  7007 W bt-btm  : Stopping oneshot timer
08-16 10:28:57.690  1037  1037 D BluetoothHeadset: Proxy object connected
08-16 10:28:57.700  6435  6951 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
,08-16 10:28:57.701  1037  1104 W ProcessCpuTracker: Skipping unknown process pid 6958
08-16 10:28:57.702  1037  1104 W ProcessCpuTracker: Skipping unknown process pid 6965
08-16 10:28:57.704  6279  6295 D BluetoothMap: onBluetoothStateChange: up=true
08-16 10:28:57.709  6435  7007 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 10:28:57.709  6435  7007 W bt-smp  : Plain text(LSB ~ MSB) = 35 b3 59 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 10:28:57.709  6435  7007 W bt-smp  : Encrypted text(LSB ~ MSB) = 94 96 42 25 9f 79 62 c2 e9 07 7f f8 9f 6c 03 8e 
08-16 10:28:57.710  6435  7007 W bt-btm  : Stopping oneshot timer
08-16 10:28:57.711  1037  1104 W ProcessCpuTracker: Skipping unknown process pid 6967
08-16 10:28:57.712  1037  1104 W ProcessCpuTracker: Skipping unknown process pid 7037
08-16 10:28:57.721  6149  6149 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 10:28:57.721  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 10:28:57.721  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 10:28:57.721  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 10:28:57.721  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 10:28:57.721  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 10:28:57.721  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 10:28:57.721  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 10:28:57.726  6149  6149 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 10:28:57.743  7057  7057 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,08-16 10:28:57.747  6435  7007 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 10:28:57.747  6435  7007 W bt-smp  : Plain text(LSB ~ MSB) = f9 45 46 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 10:28:57.747  6435  7007 W bt-smp  : Encrypted text(LSB ~ MSB) = 4b 2c 8a 3e 91 73 30 09 8b 43 c1 2d 6e 3b c6 f2 
08-16 10:28:57.747  6435  7007 W bt-btm  : Stopping oneshot timer
08-16 10:28:57.749  1037  1119 D BluetoothA2dp: onBluetoothStateChange: up=true
08-16 10:28:57.749  1037  1037 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-16 10:28:57.749  1037  1037 D BluetoothManagerService: Stored Bluetooth name: G3
08-16 10:28:57.751  6279  6294 D BluetoothPan: onBluetoothStateChange on: true
08-16 10:28:57.751  6279  6294 D BluetoothPan: onBluetoothStateChange call bindService
08-16 10:28:57.752  6279  6279 D BluetoothMap: Proxy object connected
08-16 10:28:57.752  6279  6279 D MapProfile: Bluetooth service connected
08-16 10:28:57.752  6149  6149 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 10:28:57.752  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 10:28:57.752  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 10:28:57.752  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 10:28:57.752  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 10:28:57.752  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 10:28:57.752  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 10:28:57.752  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 10:28:57.752  6279  6279 D BluetoothMap: getConnectedDevices()
08-16 10:28:57.755  1037  1037 D BluetoothA2dp: Proxy object connected
08-16 10:28:57.755  6149  6149 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 10:28:57.759  1838  1854 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-16 10:28:57.760  6435  6451 V BluetoothMapService: getConnectedDevices()
08-16 10:28:57.761  6149  6149 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 10:28:57.761  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 10:28:57.761  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 10:28:57.761  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 10:28:57.761  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 10:28:57.761  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 10:28:57.761  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 10:28:57.761  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 10:28:57.762  1838  1838 D BluetoothHeadset: Proxy object connected
,08-16 10:28:57.763  6149  6149 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 10:28:57.763  1838  2749 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 10:28:57.764  1838  1838 D BluetoothHeadset: Proxy object connected
08-16 10:28:57.764  6279  6418 D BluetoothPbap: onBluetoothStateChange: up=true
08-16 10:28:57.764  6279  6279 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 10:28:57.764  6279  6279 D PanProfile: Bluetooth service connected
08-16 10:28:57.766  6279  6295 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-16 10:28:57.768  1037  1119 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-16 10:28:57.768  1037  1119 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-16 10:28:57.769  6279  6279 D BluetoothInputDevice: Proxy object connected
08-16 10:28:57.769  6279  6279 D HidProfile: Bluetooth service connected
08-16 10:28:57.770  1928  1928 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-16 10:28:57.770  1928  2114 D LGBluetoothAPIService: Message: 1
08-16 10:28:57.770  1928  2114 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
,08-16 10:28:57.776  1588  1588 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 10:28:57.777  1928  2114 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-16 10:28:57.778  6435  6435 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-16 10:28:57.778  6435  6435 D BluetoothMapService: STATE_ON
,08-16 10:28:57.779  1037  1037 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-16 10:28:57.779  1037  1119 D BluetoothManagerService: Message: 40
08-16 10:28:57.779  1037  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-16 10:28:57.779  6149  6149 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
08-16 10:28:57.780  6435  6435 D LGBluetoothAPIServer: [BTUI] onCreate()
08-16 10:28:57.780  6435  6435 V BluetoothMapService: Handler(): got msg=1
08-16 10:28:57.781  6435  6435 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-16 10:28:57.781  6435  6435 D LGBluetoothAPIServer: [BTUI] onBind()
08-16 10:28:57.781  6149  6149 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 10:28:57.782  1928  1928 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-16 10:28:57.783  6149  6149 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 10:28:57.784  6149  6149 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 10:28:57.785  1928  2114 D LGBluetoothAPIService: Message: 100
08-16 10:28:57.785  1928  2114 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-16 10:28:57.787  6279  6279 D LocalBluetoothProfileManager: Adding local A2DP profile
08-16 10:28:57.788  6435  7064 D BluetoothMapMasInstance: MAS initSocket()
08-16 10:28:57.789  6435  7064 D BluetoothMapMasInstance:   masId = 00
08-16 10:28:57.789  6435  7064 D BluetoothMapMasInstance:   msgTypes = 0e
08-16 10:28:57.789  6435  7064 D BluetoothMapMasInstance:   masName = SMS/MMS
08-16 10:28:57.789  6435  7064 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-16 10:28:57.789  1037  1119 D BluetoothManagerService: Message: 30
08-16 10:28:57.790  1037  1703 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 10:28:57.792  6435  7064 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 10:28:57.794  6279  6279 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-16 10:28:57.794  6435  7064 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-16 10:28:57.795  6435  7064 V BluetoothMapMasInstance: Succeed to create listening socket 
08-16 10:28:57.795  6435  7064 D BluetoothMapMasInstance: Accepting socket connection...
,08-16 10:28:57.795  6435  6955 D BluetoothAdapterProperties: Scan Mode:21
08-16 10:28:57.795  6435  6955 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-16 10:28:57.798  6435  6435 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36bc39be
08-16 10:28:57.798  6435  6435 V BluetoothPbapService: Pbap Service onCreate
08-16 10:28:57.799  6149  6149 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 10:28:57.799  6435  6435 V BluetoothPbapService: Starting PBAP service
08-16 10:28:57.800  6149  6149 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 10:28:57.800  6435  6435 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-16 10:28:57.800  6435  6435 V BluetoothPbapService: Pbap Service onBind
08-16 10:28:57.801  1037  1119 D BluetoothManagerService: Message: 30
08-16 10:28:57.802  6149  6149 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 10:28:57.803  6435  6435 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 10:28:57.803  6435  6435 V BluetoothPbapService: state: 12
08-16 10:28:57.804  6435  6435 V BluetoothPbapService: Handler(): got msg=1
08-16 10:28:57.804  6435  6435 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-16 10:28:57.805  6435  7066 V BluetoothPbapService: Pbap Service initSocket
,08-16 10:28:57.806  1037  1963 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 10:28:57.807  6279  6279 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-16 10:28:57.808  6435  7066 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 10:28:57.808  6279  6279 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-16 10:28:57.809  6435  7066 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-16 10:28:57.809  6435  7066 V BluetoothPbapService: Succeed to create listening socket 
08-16 10:28:57.809  6435  7066 V BluetoothPbapService: Accepting socket connection...
08-16 10:28:57.810  6279  6279 D BluetoothA2dp: Proxy object connected
08-16 10:28:57.811  6279  6279 D A2dpProfile: Bluetooth service connected
08-16 10:28:57.812  6435  6435 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-16 10:28:57.812  6435  6435 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 10:28:57.812  6435  6435 V BluetoothPbapReceiver: ***********state = 12
08-16 10:28:57.812  6279  6279 D BluetoothPbap: Proxy object connected
08-16 10:28:57.813  6279  6279 D PbapServerProfile: Bluetooth service connected
08-16 10:28:57.813  6279  6279 D BluetoothHeadset: Proxy object connected
08-16 10:28:57.814  6279  6279 D HeadsetProfile: Bluetooth service connected
08-16 10:28:57.815  2179  2179 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 10:28:57.815  2179  2179 D c       : Getting all permits...
08-16 10:28:57.815  2179  2179 D a       : Opening database...
,08-16 10:28:57.818  2179  2179 D a       : Opening database auth.proximity.permit_store...
,08-16 10:28:57.818  2179  2179 D a       : Closing database...
08-16 10:28:57.825  6279  6279 D DockEventReceiver: finishStartingService: stopping service
08-16 10:28:57.829  6279  6279 D BluetoothPermissionRequest: onReceive
,08-16 10:28:57.831  6279  6279 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-16 10:28:57.832  6279  6279 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-16 10:28:57.835  6435  6435 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-16 10:28:57.836  6435  6435 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-16 10:28:57.841  6435  6435 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-16 10:28:57.862  6435  6435 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-16 10:28:57.862  6435  6435 V BtOppService: onCreate
,08-16 10:28:57.869  6435  6435 V BluetoothOppNotification: send message
08-16 10:28:57.873  6435  6435 V BtOppService: Starting RfcommListener
08-16 10:28:57.885  6435  6435 D BluetoothOppPreference: Dumping Names:  
08-16 10:28:57.885  6435  6435 D BluetoothOppPreference: {}
08-16 10:28:57.885  6435  6435 D BluetoothOppPreference: Dumping Channels:  
08-16 10:28:57.885  6435  6435 D BluetoothOppPreference: {}
,08-16 10:28:57.886  6435  6435 V BtOppService: onStartCommand
08-16 10:28:57.890  6435  7073 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-16 10:28:57.893  6435  6435 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-16 10:28:57.893  6435  6435 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-16 10:28:57.894  6435  7073 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-16 10:28:57.896  6435  7070 V BtOppService: Deleted complete outbound shares, number =  0
08-16 10:28:57.898  6435  7073 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@d21e70b on behalf of 
08-16 10:28:57.899  6435  6435 V BluetoothOppNotification: new notify threadi!
,08-16 10:28:57.900  6435  6435 V BluetoothOppNotification: send delay message
08-16 10:28:57.901  6435  6435 V BtOppService: start RfcommListener
08-16 10:28:57.902  6435  7070 V BtOppService: Deleted complete inbound failed shares, number = 0
08-16 10:28:57.903  6435  7070 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-16 10:28:57.904  6435  7074 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-16 10:28:57.905  6435  7070 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2956e9e8 on behalf of 
08-16 10:28:57.907  6435  7073 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-16 10:28:57.907  6435  7074 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@26b67801 on behalf of 
08-16 10:28:57.908  6435  7074 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-16 10:28:57.910  6435  6435 V BtOppService: RfcommListener started
08-16 10:28:57.910  6435  7074 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-16 10:28:57.910  6435  6435 V BtOppService: ContentObserver received notification
08-16 10:28:57.912  6435  7074 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@260796a6 on behalf of 
08-16 10:28:57.912  6435  7075 V BtOppRfcommListener: Starting RFCOMM listener....
,08-16 10:28:57.913  6435  7074 V BluetoothOppNotification: outbound: succ-0  fail-0
08-16 10:28:57.915  6435  7076 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-16 10:28:57.916  6435  7076 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-16 10:28:57.918  6435  7076 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2b85e8e7 on behalf of 
08-16 10:28:57.918  6435  7074 V BluetoothOppNotification: outbound notification was removed.
08-16 10:28:57.918  6435  7074 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-16 10:28:57.919  6435  7076 V BluetoothOppNotification: update too frequent, put in queue
08-16 10:28:57.922  6435  7074 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1ea4bc94 on behalf of 
08-16 10:28:57.922  6435  7076 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-16 10:28:57.923  1037  1901 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 10:28:57.924  6435  7074 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-16 10:28:57.926  6435  7075 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 10:28:57.929  6435  7074 V BluetoothOppNotification: inbound notification was removed.
08-16 10:28:57.929  6435  7075 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
08-16 10:28:57.929  6435  7074 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-16 10:28:57.929  6435  7075 V BtOppRfcommListener: Started RFCOMM listener....
08-16 10:28:57.930  6435  7075 I BtOppRfcommListener: Accept thread started.
08-16 10:28:57.930  6435  7075 V BtOppRfcommListener: Accepting connection...
08-16 10:28:57.932  6435  7074 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2c11933d on behalf of 
08-16 10:28:57.936  6435  6435 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36bc39be
,08-16 10:28:57.936  6435  6435 V BluetoothFtpService: Ftp Service onCreate
08-16 10:28:57.936  6435  6435 I BluetoothFtpService: Ftp Service onCreate
08-16 10:28:57.937  6435  6435 V BluetoothFtpService: Ftp Service onStartCommand
08-16 10:28:57.937  6435  6435 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 10:28:57.937  6435  6435 V BluetoothFtpService: Starting Listening on sockets
08-16 10:28:57.937  6435  6435 V BtOppService: ContentObserver received notification
08-16 10:28:57.938  6435  6435 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 10:28:57.938  6435  6435 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 10:28:57.938  6435  6435 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 10:28:57.938  6435  6435 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 10:28:57.938  6435  6435 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-16 10:28:57.938  6435  6435 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-16 10:28:57.941  6435  7078 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-16 10:28:57.941  6435  6435 V BluetoothFtpService: Handler(): got msg=1
08-16 10:28:57.941  6435  7078 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-16 10:28:57.944  6435  6435 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-16 10:28:57.944  6435  6435 V BluetoothFtpService: Ftp Service initSocket
08-16 10:28:57.945  6435  7078 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@203e2c83 on behalf of 
08-16 10:28:57.946  6435  7078 V BluetoothOppNotification: update too frequent, put in queue
08-16 10:28:57.947  6435  7078 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
,08-16 10:28:57.955  1037  1873 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 10:28:57.957  6435  6435 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 10:28:57.959  6435  6435 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=78
08-16 10:28:57.959  6435  6435 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-16 10:28:57.962  6435  7079 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
,08-16 10:28:57.980  6435  6435 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36bc39be
,08-16 10:28:57.980  6435  6435 V BluetoothSapService: Sap Service onCreate
08-16 10:28:57.982  6435  6435 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 10:28:57.983  6435  6435 V BluetoothSapService: state: 12
08-16 10:28:57.983  6435  6435 V BluetoothSapService: Starting SAP server process
08-16 10:28:57.986  6435  6435 V BluetoothSapService: SAP Service startRfcommListenerThread
08-16 10:28:57.982  7080  7080 W sapd    : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 10:28:57.982  7080  7080 W sapd    : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 10:28:57.988  6435  7081 V BluetoothSapService: Sap Service initRfcommSocket
08-16 10:28:57.989  1037  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 10:28:57.990  6435  7081 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 10:28:57.991  6435  7081 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
,08-16 10:28:57.993  6435  7081 V BluetoothSapService: Succeed to create listening socket 
08-16 10:28:57.993  6435  7081 V BluetoothSapService: Accepting socket connection...
08-16 10:28:58.010  7080  7080 V BT_SAP  : Event pipe created
08-16 10:28:58.010  7080  7080 V BT_SAP  : create_server_socket qcom.sap.server
08-16 10:28:58.010  7080  7080 V BT_SAP  : created socket fd 6
,08-16 10:28:58.903  6435  6435 V BluetoothOppNotification: new notify threadi!
08-16 10:28:58.904  6435  6435 V BluetoothOppNotification: send delay message
,08-16 10:28:58.916  6435  7091 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-16 10:28:58.918  6435  7091 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@27ad0ddf on behalf of 
08-16 10:28:58.919  6435  7091 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-16 10:28:58.921  6435  7091 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,08-16 10:28:58.924  6435  7091 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@38630a2c on behalf of 
08-16 10:28:58.925  6435  7091 V BluetoothOppNotification: outbound: succ-0  fail-0
08-16 10:28:58.926  6435  7091 V BluetoothOppNotification: outbound notification was removed.
08-16 10:28:58.926  6435  7091 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-16 10:28:58.928  6435  7091 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@394cecf5 on behalf of 
08-16 10:28:58.928  6435  7091 V BluetoothOppNotification: inbound: succ-0  fail-0
08-16 10:28:58.930  6435  7091 V BluetoothOppNotification: inbound notification was removed.
08-16 10:28:58.930  6435  7091 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-16 10:28:58.931  6435  7091 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1071ba8a on behalf of 
08-16 10:28:59.938  6806  6835 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,08-16 10:29:00.002  1037  1365 D PowerManagerServiceEx: acquireWakeLockInternal: lock=479019197, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,08-16 10:29:00.022  6350  6350 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
08-16 10:29:00.023  6350  6350 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:5322
,08-16 10:29:00.049  2597  2597 D [Concierge]Service: onStartCommand(). Type : 9
,08-16 10:29:00.062  1588  1588 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-16 10:29:00.062  1588  1588 I KeyguardUpdateMonitor: called onTimeUpdated()
08-16 10:29:00.062  1588  1588 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-16 10:29:00.062  1588  1588 I [SystemUI]Clock: called onTimeUpdated()
,08-16 10:29:00.070  1588  1588 I LgeClockWidgetControlView: called onTimeUpdated()
08-16 10:29:00.071  1588  1588 I [SystemUI]DateView: called onTimeUpdated()
08-16 10:29:00.071  1588  1588 I [SystemUI]DateView: called onTimeUpdated()
08-16 10:29:00.073  1588  1588 D KeyguardUpdateMonitor: handleTimeUpdate
08-16 10:29:00.116  1037  1037 D PowerManagerServiceEx: releaseWakeLockInternal: lock=479019197 [*alarm*], flags=0x0
,08-16 10:29:00.941  1037  1053 I ActivityManager: Killing 6006:com.lge.bnr/1000 (adj 15): empty #17
,08-16 10:29:00.972  1037  1927 W libprocessgroup: failed to open /acct/uid_1000/pid_6006/cgroup.procs: No such file or directory
,08-16 10:29:01.649  1037  1739 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-16 10:29:01.649  1037  1739 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@69d6d5f mBinding = false
,08-16 10:29:01.680  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 10:29:01.680  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 10:29:01.681  1037  1037 D Ulp_jni : JNI:system_update. Event-4
08-16 10:29:01.681  1037  1119 D BluetoothManagerService: Message: 2
08-16 10:29:01.682  1037  1119 D BluetoothManagerService: Sending off request.
08-16 10:29:01.683  6435  6451 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-16 10:29:01.684  6435  6951 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-16 10:29:01.684  6435  6951 D BluetoothAdapterProperties: Setting state to 13
08-16 10:29:01.684  6435  6951 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-16 10:29:01.684  6435  6951 D BluetoothAdapterProperties: onBluetoothDisable()
08-16 10:29:01.685  6435  6951 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-16 10:29:01.686  6435  6955 D BluetoothAdapterProperties: Scan Mode:20
08-16 10:29:01.688  6435  6951 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-16 10:29:01.689  6435  7064 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-16 10:29:01.689  6435  7064 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 10:29:01.689  6435  7064 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-16 10:29:01.689  6435  7064 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-16 10:29:01.689  6435  7064 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-16 10:29:01.689  6435  7064 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-16 10:29:01.689  6435  7064 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-16 10:29:01.689  6435  7064 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,08-16 10:29:01.694  6435  7066 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 10:29:01.694  6435  7075 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 10:29:01.695  6435  7081 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 10:29:01.696  6435  6951 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-16 10:29:01.698  6435  7007 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-16 10:29:01.698  6435  7007 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-16 10:29:01.704  6435  7007 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
,08-16 10:29:01.708  6435  7007 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 10:29:01.708  6435  7007 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 10:29:01.708  6435  7007 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 10:29:01.708  6435  7007 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 10:29:01.708  6435  7007 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 10:29:01.708  6435  7007 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 10:29:01.708  6435  7007 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 10:29:01.708  6435  7007 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 10:29:01.708  6435  7007 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-16 10:29:01.708  6435  7007 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-16 10:29:01.710  6435  7007 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-16 10:29:01.714  6149  6149 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 10:29:01.714  6149  6149 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 10:29:01.714  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 10:29:01.714  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 10:29:01.714  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 10:29:01.714  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 10:29:01.714  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 10:29:01.714  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 10:29:01.714  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 10:29:01.716  6149  6149 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 10:29:01.716  6149  6149 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 10:29:01.719  6149  6149 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 10:29:01.719  6149  6149 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 10:29:01.719  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 10:29:01.719  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 10:29:01.719  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 10:29:01.719  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 10:29:01.719  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 10:29:01.719  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 10:29:01.719  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 10:29:01.724  6149  6149 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 10:29:01.724  6149  6149 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 10:29:01.726  6149  6149 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 10:29:01.726  6149  6149 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 10:29:01.726  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 10:29:01.726  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 10:29:01.726  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 10:29:01.726  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 10:29:01.726  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 10:29:01.726  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 10:29:01.726  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 10:29:01.729  6149  6149 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 10:29:01.729  6149  6149 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 10:29:01.730  1037  1119 D BluetoothManagerService: Message: 60
08-16 10:29:01.731  1037  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-16 10:29:01.731  1037  1119 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
,08-16 10:29:01.736  1928  1928 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-16 10:29:01.737  1588  1588 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 10:29:01.742  6149  6149 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 10:29:01.743  6149  6149 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 10:29:01.746  6149  6149 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 10:29:01.748  6435  6435 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-16 10:29:01.748  6435  6435 D BluetoothMapService: STATE_TURNING_OFF
08-16 10:29:01.748  6435  6435 V BluetoothMapService: Handler(): got msg=4
08-16 10:29:01.749  6435  6435 D BluetoothMapService: MAP Service closeService in
08-16 10:29:01.749  6435  6435 D BluetoothMapMasInstance: MAP Service shutdown
08-16 10:29:01.749  6435  6435 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-16 10:29:01.749  6435  6435 V BluetoothMapService: MAP Service closeService out
08-16 10:29:01.750  6435  6435 V BtOppService: Receiver DISABLED_ACTION 
08-16 10:29:01.750  6435  6435 I BtOppRfcommListener: stopping Accept Thread
08-16 10:29:01.750  6435  6435 V BtOppRfcommListener: close mBtServerSocket
08-16 10:29:01.751  6435  7075 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-16 10:29:01.751  6435  6435 V BtOppRfcommListener: waiting for thread to terminate
08-16 10:29:01.751  6435  6435 V BtOppRfcommListener: done waiting for thread to terminate
08-16 10:29:01.754  6279  6279 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
08-16 10:29:01.754  6435  7079 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 10:29:01.764  6279  6279 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-16 10:29:01.769  6435  6435 V BtOppService: onDestroy
08-16 10:29:01.771  6435  6435 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-16 10:29:01.775  6435  6435 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-16 10:29:01.776  6435  6435 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 10:29:01.776  6435  6435 V BluetoothPbapReceiver: ***********state = 13
08-16 10:29:01.777  6435  6435 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
,08-16 10:29:01.781  6435  6435 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 10:29:01.781  6435  6435 V BluetoothPbapService: state: 13
08-16 10:29:01.782  6435  6435 V BluetoothPbapService: Pbap Service closeService in
08-16 10:29:01.784  2179  2179 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 10:29:01.786  6435  6435 V BluetoothPbapService: successfully stopped pbap service
08-16 10:29:01.786  6435  6435 V BluetoothPbapService: Pbap Service closeService out
08-16 10:29:01.787  6435  6435 V BluetoothPbapService: Pbap Service onDestroy
08-16 10:29:01.787  6435  6435 V BluetoothPbapService: Pbap Service closeService in
08-16 10:29:01.787  6435  6435 V BluetoothPbapService: Pbap Service closeService out
08-16 10:29:01.787  6435  6435 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-16 10:29:01.803  6279  6279 D DockEventReceiver: finishStartingService: stopping service
,08-16 10:29:01.809  1037  1530 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
08-16 10:29:01.812  6279  6279 D BluetoothPbap: Proxy object disconnected
08-16 10:29:01.812  6279  6279 D PbapServerProfile: Bluetooth service disconnected
08-16 10:29:01.824  6279  6279 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-16 10:29:01.830  6279  6279 D BluetoothPermissionRequest: onReceive
08-16 10:29:01.831  6279  6279 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-16 10:29:01.839  6279  6279 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-16 10:29:01.846  6435  6435 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-16 10:29:01.846  6435  6435 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-16 10:29:01.847  6435  6435 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-16 10:29:01.851  6435  6435 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-16 10:29:01.851  6435  6435 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,08-16 10:29:01.853  6435  6435 V BluetoothFtpService: Ftp Service onStartCommand
08-16 10:29:01.853  6435  6435 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 10:29:01.854  6435  6435 V BluetoothFtpService: Ftp Service closeService
08-16 10:29:01.854  6435  6435 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-16 10:29:01.858  6435  6435 V BluetoothFtpService: successfully stopped ftp service
08-16 10:29:01.858  6435  6435 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 10:29:01.858  6435  6435 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 10:29:01.858  6435  6435 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 10:29:01.858  6435  6435 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 10:29:01.858  6435  6435 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-16 10:29:01.858  6435  6435 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-16 10:29:01.859  6435  6435 V BluetoothFtpService: Ftp Service onDestroy
08-16 10:29:01.859  6435  6435 V BluetoothFtpService: Ftp Service closeService
08-16 10:29:01.863  6435  6435 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 10:29:01.863  6435  6435 V BluetoothSapService: state: 13
08-16 10:29:01.863  6435  6435 V BluetoothSapService: Stopping SAP server process
08-16 10:29:01.864  6435  6435 V BluetoothSapService: Sap Service closeSapService in
08-16 10:29:01.864  6435  6435 V BluetoothSapService: Close listen Socket : 
08-16 10:29:01.864  6435  6435 V BluetoothSapService: Close rfcomm Socket : 
08-16 10:29:01.865  6435  6435 V BluetoothSapService: Close sapd  Socket : 
08-16 10:29:01.866  6435  6435 V BluetoothSapService: Sap Service closeSapService out
08-16 10:29:01.866  6435  6435 V BluetoothSapService: Sap Service onDestroy
08-16 10:29:01.866  6435  6435 V BluetoothSapService: Sap Service closeSapService in
08-16 10:29:01.866  6435  6435 V BluetoothSapService: Close listen Socket : 
08-16 10:29:01.866  6435  6435 V BluetoothSapService: Close rfcomm Socket : 
08-16 10:29:01.866  6435  6435 V BluetoothSapService: Close sapd  Socket : 
08-16 10:29:01.867  6435  6435 V BluetoothSapService: Sap Service closeSapService out
,08-16 10:29:02.604  6435  6955 D bt_hci_bdroid: cleanup
,08-16 10:29:02.610  6435  7009 I bt_lpm  : LPM is already off!!!
08-16 10:29:02.611  6435  7036 I bt_userial_mct: exiting userial_read_thread
08-16 10:29:02.611  6435  7036 D bt_userial_mct: Leaving userial_evt_read_thread()
08-16 10:29:02.612  6435  7007 W bt-btif : ag scb idx 1 not allocated
08-16 10:29:02.612  6435  7007 E bt-btif : BTA AG is already disabled, ignoring ...
08-16 10:29:02.612  6435  7007 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 10:29:02.612  6435  7007 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 10:29:02.612  6435  7007 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 10:29:02.612  6435  7007 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 10:29:02.612  6435  7007 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 10:29:02.612  6435  7007 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 10:29:02.612  6435  7007 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 10:29:02.613  6435  7007 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 10:29:02.613  6435  7007 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 10:29:02.613  6435  7007 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 10:29:02.613  6435  7007 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
,08-16 10:29:02.613  6435  7007 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 10:29:02.613  6435  7007 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 10:29:02.613  6435  7007 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 10:29:02.613  6435  7007 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 10:29:02.613  6435  7007 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 10:29:02.613  6435  7007 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 10:29:02.613  6435  7007 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 10:29:02.613  6435  7007 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-16 10:29:02.617  6435  6955 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-16 10:29:02.617  6435  7009 I bt_vendor: hw_epilog_process
08-16 10:29:02.617  6435  6955 D bt_hci_bdroid: cleanup Finalizing cleanup
08-16 10:29:02.617  6435  6955 D bt_userial_mct: userial_close
08-16 10:29:02.617  6435  6955 E bt_userial_mct: pthread_join() FAILED result:3
08-16 10:29:02.617  6435  6955 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-16 10:29:02.626  6435  6955 D bt_hci_bdroid: set_power 0
08-16 10:29:02.626  6435  6955 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-16 10:29:02.626  6435  6955 I bt_vendor: bluetooth satus is on
08-16 10:29:02.626  6435  6955 I bt_vendor: bt-vendor : resetting BT status
08-16 10:29:02.626  6435  6955 I bt_vendor: Starting hciattach daemon
08-16 10:29:02.626  6435  6955 I bt_vendor: try to set false
,08-16 10:29:02.632  6435  6955 I bt_vendor: Starting hciattach daemon
08-16 10:29:02.632  6435  6955 I bt_vendor: try to set false
08-16 10:29:02.635  6435  6955 I bt_vendor: cleanup
08-16 10:29:02.635  6435  7007 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-16 10:29:02.636  6435  6955 I GKI_LINUX: GKI_exit_task 0 done
08-16 10:29:02.636  6435  6955 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-16 10:29:02.637  6435  6951 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-16 10:29:02.644  6435  6435 D HeadsetService: Received stop request...Stopping profile...
,08-16 10:29:02.649  6435  6951 D BluetoothAdapterState: Stopping profile services that were post enabled
08-16 10:29:02.650  6435  6435 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-16 10:29:02.650  6435  6435 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 10:29:02.651  6435  6990 D HeadsetStateMachine: Exit Disconnected: -1
08-16 10:29:02.651  6435  6435 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36bc39be
08-16 10:29:02.653  1838  1838 D BluetoothHeadset: Proxy object disconnected
08-16 10:29:02.653  1838  1838 D BluetoothHeadset: Proxy object disconnected
08-16 10:29:02.653  1838  1838 D BluetoothHeadset: Proxy object disconnected
08-16 10:29:02.654  1037  1037 D BluetoothHeadset: Proxy object disconnected
08-16 10:29:02.654  1037  1037 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-16 10:29:02.655  6435  6435 D A2dpService: Received stop request...Stopping profile...
08-16 10:29:02.656  6435  6999 D A2dpStateMachine: Exit Disconnected: -1
08-16 10:29:02.658  6435  6435 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
,08-16 10:29:02.662  6435  6435 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-16 10:29:02.662  6435  6435 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 10:29:02.662  6435  6435 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36bc39be
08-16 10:29:02.663  1037  1037 D BluetoothA2dp: Proxy object disconnected
08-16 10:29:02.663  1037  1037 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-16 10:29:02.664  6435  6435 D HidService: Received stop request...Stopping profile...
08-16 10:29:02.664  6435  6435 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36bc39be
08-16 10:29:02.666  6435  6435 D HealthService: Received stop request...Stopping profile...
08-16 10:29:02.666  6435  6435 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36bc39be
08-16 10:29:02.670  6435  6435 D PanService: Received stop request...Stopping profile...
,08-16 10:29:02.673  6435  6435 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36bc39be
08-16 10:29:02.675  6435  6435 D BtGatt.DebugUtils: handleDebugAction() action=null
08-16 10:29:02.676  6435  6435 D BtGatt.GattService: Received stop request...Stopping profile...
08-16 10:29:02.676  6435  6435 D BtGatt.GattService: stop()
08-16 10:29:02.676  6435  6435 D BtGatt.AdvertiseManager: advertise clients cleared
08-16 10:29:02.677  6435  6435 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36bc39be
08-16 10:29:02.678  6435  6435 D BluetoothMapService: Received stop request...Stopping profile...
08-16 10:29:02.678  6435  6435 D BluetoothMapService: stop()
08-16 10:29:02.679  6435  6435 D BluetoothMapEmailAppObserver: deinitObservers()
08-16 10:29:02.679  6435  6435 D BluetoothMapEmailAppObserver: removeReceiver()
08-16 10:29:02.680  6435  6435 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36bc39be
08-16 10:29:02.682  6435  6435 D HeadsetStateMachine: Unbinding service...
08-16 10:29:02.684  6435  6435 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-16 10:29:02.684  6435  6435 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-16 10:29:02.684  6435  6435 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-16 10:29:02.684  6435  6435 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-16 10:29:02.684  6435  6435 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-16 10:29:02.684  6435  6435 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 10:29:02.684  6435  6435 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-16 10:29:02.684  6435  6435 I BluetoothA2dpServiceJni: cleanupNative
,08-16 10:29:02.687  6435  7000 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-16 10:29:02.687  6435  6435 I GKI_LINUX: GKI_exit_task 2 done
08-16 10:29:02.687  6435  6435 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-16 10:29:02.688  6435  6435 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-16 10:29:02.688  6435  6435 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-16 10:29:02.688  6435  6435 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-16 10:29:02.689  6435  6435 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-16 10:29:02.689  6435  6435 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-16 10:29:02.689  6435  6435 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-16 10:29:02.689  6435  6435 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-16 10:29:02.691  6435  6435 V BluetoothMapService: Handler(): got msg=4
08-16 10:29:02.692  6435  6435 D BluetoothMapService: MAP Service closeService in
08-16 10:29:02.692  6435  6435 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-16 10:29:02.692  6435  6435 V BluetoothMapService: MAP Service closeService out
08-16 10:29:02.692  6435  6951 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-16 10:29:02.692  6435  6951 D BluetoothAdapterProperties: Setting state to 10
08-16 10:29:02.692  6435  6951 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-16 10:29:02.693  6435  6435 D BluetoothMapService: cleanup()
08-16 10:29:02.693  6435  6435 D BluetoothMapService: MAP Service closeService in
08-16 10:29:02.693  6435  6435 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-16 10:29:02.693  6435  6435 V BluetoothMapService: MAP Service closeService out
08-16 10:29:02.696  1037  1119 D BluetoothManagerService: Message: 60
08-16 10:29:02.696  1037  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-16 10:29:02.696  1037  1119 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
,08-16 10:29:02.698  6435  6951 I BluetoothAdapterState: Entering OffState
08-16 10:29:02.699  1838  1853 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 10:29:02.700  6279  6294 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 10:29:02.700  1037  1119 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 10:29:02.702  6279  6294 D BluetoothMap: onBluetoothStateChange: up=false
08-16 10:29:02.703  1037  1119 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 10:29:02.703  6279  6294 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 10:29:02.704  6279  6294 D BluetoothPan: onBluetoothStateChange on: false
08-16 10:29:02.705  1838  4357 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 10:29:02.707  1838  2749 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 10:29:02.707  6279  6294 D BluetoothPbap: onBluetoothStateChange: up=false
,08-16 10:29:02.709  6279  6294 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-16 10:29:02.711  1037  1119 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-16 10:29:02.711  1037  1119 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-16 10:29:02.713  1037  1119 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-16 10:29:02.713  1037  1119 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-16 10:29:02.713  1037  1119 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@69d6d5f mBinding = false
08-16 10:29:02.714  1037  1119 D BluetoothManagerService: Sending unbind request.
08-16 10:29:02.718  6435  6955 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-16 10:29:02.721  6435  6435 I GKI_LINUX: GKI_exit_task 1 done
08-16 10:29:02.721  6435  6435 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-16 10:29:02.721  6435  6435 I BluetoothServiceJni: cleanupNative: return from cleanup
08-16 10:29:02.721  6435  6435 I art     : --- WEIRD: removing null entry 248
08-16 10:29:02.721  6435  6435 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-16 10:29:02.721  6435  6435 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-16 10:29:02.723  6435  6435 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-16 10:29:02.724  1037  1119 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-16 10:29:02.726  6435  6435 I art     : System.exit called, status: 0
08-16 10:29:02.726  6435  6435 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-16 10:29:02.746   316   316 V AudioFlinger: 6435 died, releasing its sessions
08-16 10:29:02.746   316   316 V AudioFlinger:  pid 1838 @ 0
08-16 10:29:02.746   316   316 V AudioFlinger:  pid 3369 @ 1
08-16 10:29:02.746   316   316 V AudioFlinger:  pid 3369 @ 2
,08-16 10:29:02.749  1928  1928 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
,08-16 10:29:02.750  1928  2114 D LGBluetoothAPIService: Message: 101
08-16 10:29:02.750  1928  2114 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
08-16 10:29:02.750  1928  2114 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
08-16 10:29:02.750  1928  2114 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
08-16 10:29:02.752  6279  6279 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-16 10:29:02.757  1037  1053 I ActivityManager: Process com.android.bluetooth (pid 6435) has died
08-16 10:29:02.758  1037  1053 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms
08-16 10:29:02.758  1037  1053 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 14000ms
,08-16 10:29:02.768  1928  1928 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-16 10:29:02.769  1928  2114 D LGBluetoothAPIService: Message: 2
08-16 10:29:02.769  1928  2114 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
08-16 10:29:02.769  1588  1588 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 10:29:02.772  6279  6279 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-16 10:29:02.772  6279  6279 D LGBluetoothEventManager: [BTUI] clear device connection state
08-16 10:29:02.776  6149  6149 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 10:29:02.777  6149  6149 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 10:29:02.778  6149  6149 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 10:29:02.778  1588  1588 D BluetoothAdapter: 943633624: getState() :  mService = null. Returning STATE_OFF
08-16 10:29:02.778  1588  1588 D BluetoothAdapter: 943633624: getState() :  mService = null. Returning STATE_OFF
08-16 10:29:02.779  6279  6279 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-16 10:29:02.825  1037  2034 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7141 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-16 10:29:02.827  6279  6279 D DockEventReceiver: finishStartingService: stopping service
,08-16 10:29:02.975  1037  1872 I art     : Explicit concurrent mark sweep GC freed 35997(1721KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 1.518ms total 117.705ms
,08-16 10:29:02.994  7141  7141 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-16 10:29:02.994  7141  7141 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 10:29:02.995  7141  7141 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-16 10:29:02.995  7141  7141 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-16 10:29:03.007  7141  7141 D BluetoothAdapterApp: Loading JNI Library
08-16 10:29:03.027  7141  7141 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@242893e6 Instance Count = 1
,08-16 10:29:03.031  7141  7141 D BluetoothAdapterApp: onCreate
08-16 10:29:03.047  7141  7141 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-16 10:29:03.047  7141  7141 D ProfileConfigQcom: Adding HeadsetService
08-16 10:29:03.047  7141  7141 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-16 10:29:03.047  7141  7141 D ProfileConfigQcom: Adding A2dpService
08-16 10:29:03.047  7141  7141 D ProfileConfigQcom: [BTUI] HidService is supported
08-16 10:29:03.047  7141  7141 D ProfileConfigQcom: Adding HidService
,08-16 10:29:03.048  7141  7141 D ProfileConfigQcom: [BTUI] HealthService is supported
08-16 10:29:03.048  7141  7141 D ProfileConfigQcom: Adding HealthService
08-16 10:29:03.048  7141  7141 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-16 10:29:03.048  7141  7141 D ProfileConfigQcom: [BTUI] PanService is supported
08-16 10:29:03.048  7141  7141 D ProfileConfigQcom: Adding PanService
08-16 10:29:03.049  7141  7141 D ProfileConfigQcom: [BTUI] GattService is supported
08-16 10:29:03.049  7141  7141 D ProfileConfigQcom: Adding GattService
08-16 10:29:03.049  7141  7141 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-16 10:29:03.049  7141  7141 D ProfileConfigQcom: Adding BluetoothMapService
08-16 10:29:03.049  7141  7141 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-16 10:29:03.050  7141  7141 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-16 10:29:03.050  7141  7141 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 10:29:03.050  7141  7141 V BluetoothPbapReceiver: ***********state = 10
08-16 10:29:03.051  7141  7141 V LGMDMManagerInternal: Create singleton instance
08-16 10:29:03.097  2179  2179 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 10:29:03.114  6279  6279 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,08-16 10:29:03.120  7141  7141 D LGBluetoothAPIServer: [BTUI] onCreate()
08-16 10:29:03.120  7141  7141 D LGBluetoothAPIServer: [BTUI] onBind()
08-16 10:29:03.122  6279  6279 D BluetoothPermissionRequest: onReceive
08-16 10:29:03.122  1928  1928 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-16 10:29:03.122  1928  2114 D LGBluetoothAPIService: Message: 100
08-16 10:29:03.122  1928  2114 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-16 10:29:03.124  6279  6279 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-16 10:29:03.124  6279  6279 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-16 10:29:03.127  6279  6279 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-16 10:29:03.133  7141  7141 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-16 10:29:03.136  7141  7141 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-16 10:29:03.139  7141  7141 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 10:29:03.140  7141  7141 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 10:29:03.140  7141  7141 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 10:29:03.141  7141  7141 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 10:29:03.141  7141  7141 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
,08-16 10:29:03.145  6376  6376 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-16 10:29:06.763  6149  6212 D io.jxcore.node.ConnectivityMonitor: stop
08-16 10:29:06.763  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 10:29:11.774  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:29:11.774  6149  6212 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6e16daf removed from the list
08-16 10:29:11.774  6149  6212 D io.jxcore.node.ConnectivityMonitor: stop
08-16 10:29:11.774  6149  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:29:11.775  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 10:29:11.788  6149  6212 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 10:29:11.788  6149  6212 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@24e135cb added. We now have 4 listener(s)
08-16 10:29:11.788  6149  6212 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 10:29:11.789  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:29:11.789  6149  6212 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@24e135cb removed from the list
08-16 10:29:11.789  6149  6212 D io.jxcore.node.ConnectivityMonitor: stop
08-16 10:29:11.789  6149  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:29:11.789  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:29:11.789  6149  6212 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 10:29:11.790  6149  6212 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3849f1a8 added. We now have 4 listener(s)
08-16 10:29:11.790  6149  6212 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 10:29:11.791  1037  2037 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 10:29:11.791  1037  2037 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
,08-16 10:29:11.794  1037  1119 D BluetoothManagerService: Message: 2
08-16 10:29:13.797  6149  6212 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 10:29:13.803  1037  1872 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 10:29:13.804  1037  1872 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-16 10:29:13.822  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 10:29:13.822  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 10:29:13.822  1037  1037 D Ulp_jni : JNI:system_update. Event-4
08-16 10:29:13.823  1037  1119 D BluetoothManagerService: Message: 1
08-16 10:29:13.823  1037  1119 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-16 10:29:13.848  1037  1119 D BluetoothManagerService: Message: 20
08-16 10:29:13.848  1037  1119 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@13e152d6:true
,08-16 10:29:13.852  7141  7141 D BluetoothAdapterState: make
08-16 10:29:13.860  7141  7141 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-16 10:29:13.860  7141  7141 I bluedroid-qcom: init
08-16 10:29:13.862  7141  7171 I BluetoothAdapterState: Entering OffState
,08-16 10:29:13.864  7141  7141 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-16 10:29:13.864  7141  7141 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-16 10:29:13.864  7141  7141 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-16 10:29:13.864  7141  7141 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-16 10:29:13.864  7141  7141 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-16 10:29:13.866  7141  7141 I bluedroid-qcom: get_profile_interface socket
08-16 10:29:13.866  7141  7141 I bluedroid-qcom: get_profile_interface map_client
08-16 10:29:13.868  7141  7175 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-16 10:29:13.870  7141  7175 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-16 10:29:13.862  7174  7174 W bdaddr_loader: type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 10:29:13.862  7174  7174 W bdaddr_loader: type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 10:29:13.884  7174  7174 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-16 10:29:13.884  7174  7174 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-16 10:29:13.884  7174  7174 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,08-16 10:29:13.889  1037  1037 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-16 10:29:13.890  1037  1037 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-16 10:29:13.890  1037  1037 D BluetoothManagerService: Stored Bluetooth name: G3
08-16 10:29:13.890  1037  1119 D BluetoothManagerService: Message: 40
08-16 10:29:13.890  1037  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-16 10:29:13.891  7141  7158 I bluedroid-qcom: config_hci_snoop_log
08-16 10:29:13.892  1037  1119 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-16 10:29:13.892  1037  1119 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-16 10:29:13.894  7141  7175 D BluetoothAdapterProperties: Name is: G3
08-16 10:29:13.894  7174  7174 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-16 10:29:13.905  7141  7171 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-16 10:29:13.906  7141  7171 D BluetoothAdapterProperties: Setting state to 11
,08-16 10:29:13.909  7141  7171 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-16 10:29:13.912  7141  7171 I LGBluetoothServiceJni: classInitNative: succeeds
08-16 10:29:13.916  1037  1119 D BluetoothManagerService: Message: 60
08-16 10:29:13.916  1037  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-16 10:29:13.916  1037  1119 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
,08-16 10:29:13.924  1928  1928 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-16 10:29:13.926  1588  1588 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 10:29:13.928  6149  6149 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 10:29:13.930  7174  7174 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-16 10:29:13.930  7174  7174 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-16 10:29:13.932  6149  6149 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 10:29:13.934  6279  6279 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
,08-16 10:29:13.942  7141  7141 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-16 10:29:13.943  7141  7141 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 10:29:13.943  7141  7141 V BluetoothPbapReceiver: ***********state = 11
08-16 10:29:13.959  2179  2179 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 10:29:13.967  7141  7171 D BluetoothBondStateMachine: make
08-16 10:29:13.970  7141  7189 I BluetoothBondStateMachine: StableState(): Entering Off State
08-16 10:29:13.970  7141  7171 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@eb0aa1f
08-16 10:29:13.970  7141  7171 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-16 10:29:13.970  7141  7171 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@eb0aa1f
08-16 10:29:13.970  7141  7171 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-16 10:29:13.971  7141  7171 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
,08-16 10:29:13.978  7141  7171 E BluetoothAdapterService: File transfer profiles supported!!
08-16 10:29:13.981  6279  6279 D BluetoothPermissionRequest: onReceive
08-16 10:29:13.984  7141  7141 D HeadsetService: Received start request. Starting profile...
08-16 10:29:13.985  7141  7141 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-16 10:29:13.985  7141  7141 D LGBluetoothHfpAdapter: Version 1.6
08-16 10:29:13.987  7141  7141 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-16 10:29:13.988  7141  7141 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-16 10:29:13.989  7141  7141 D HeadsetStateMachine: make
,08-16 10:29:13.989  6279  6279 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-16 10:29:13.993  7141  7171 E BluetoothAdapterService: File transfer profiles supported!!
08-16 10:29:13.998  7141  7171 E BluetoothAdapterService: File transfer profiles supported!!
08-16 10:29:14.004  7141  7171 E BluetoothAdapterService: File transfer profiles supported!!
08-16 10:29:14.008  7141  7171 E BluetoothAdapterService: File transfer profiles supported!!
08-16 10:29:14.012  7141  7171 E BluetoothAdapterService: File transfer profiles supported!!
,08-16 10:29:14.018  7141  7171 E BluetoothAdapterService: File transfer profiles supported!!
08-16 10:29:14.023  7141  7141 D LgDataFeature: LgDataFeature() Constructor: none
08-16 10:29:14.023  7141  7141 D LgDataFeature: LgDataFeature() Constructor Done, null
08-16 10:29:14.028  7141  7141 D HeadsetStateMachine: max_hf_connections = 1
08-16 10:29:14.028  7141  7141 I bluedroid-qcom: get_profile_interface handsfree
08-16 10:29:14.029  7141  7141 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
,08-16 10:29:14.030   316  2137 V AudioPolicyService: registerClient() client 0xb1023e20, uid 1002
08-16 10:29:14.030   316  2138 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-16 10:29:14.030   316  2138 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-16 10:29:14.030   316  2138 V AudioPolicyManagerEx: getOutput() returns output 2
08-16 10:29:14.031  7141  7141 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-16 10:29:14.031   316  1371 V AudioFlinger: registerClient() client 0xb1433160, pid 7141
08-16 10:29:14.031  7141  7141 V ToneGenerator: Create Track: 0xb4928080
08-16 10:29:14.031  7141  7141 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-16 10:29:14.031  7141  7141 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-16 10:29:14.031   316   316 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-16 10:29:14.031   316   316 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-16 10:29:14.031   316   316 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-16 10:29:14.031   316   316 V AudioPolicyManagerEx: getOutput() returns output 2
08-16 10:29:14.032  7141  7141 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
,08-16 10:29:14.032   316  2138 I AudioFlinger: isAudioPlaybackHookOn() false
08-16 10:29:14.032   316  1371 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-16 10:29:14.032   316  1371 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-16 10:29:14.032   316  1371 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-16 10:29:14.032   316  1371 V AudioPolicyManagerEx: getOutput() returns output 2
08-16 10:29:14.033   316  1366 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 10:29:14.033   316  1366 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 10:29:14.033  7141  7141 V AudioSystem: getLatency() output 2, latency 50
08-16 10:29:14.033  7141  7141 V AudioSystem: getFrameCount() output 2, frameCount 960
08-16 10:29:14.033  7141  7141 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-16 10:29:14.033  1588  3067 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 10:29:14.033  1588  3067 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 10:29:14.034   316  1367 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 10:29:14.034  7141  7141 V AudioTrack: createTrack_l() output 2 afLatency 50
08-16 10:29:14.034   316  1367 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 10:29:14.034  1037  1901 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 10:29:14.034  1037  1901 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 10:29:14.034  1037  1901 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 10:29:14.034  1037  1901 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 10:29:14.035  7141  7171 V LGMDMManager: Create singleton instance
08-16 10:29:14.035  7141  7158 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 10:29:14.035  7141  7158 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-16 10:29:14.035  1838  1853 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 10:29:14.035  1838  1853 V AudioSystem: ioConfigChanged() opening already existing output! 2
,08-16 10:29:14.035  3369  3384 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 10:29:14.035  3369  3384 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 10:29:14.035  1588  2061 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 10:29:14.035  1588  2061 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 10:29:14.035  3369  3385 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 10:29:14.035  3369  3385 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 10:29:14.035  1838  4357 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 10:29:14.035  1838  4357 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 10:29:14.035   316  1371 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-16 10:29:14.035   316  1371 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-16 10:29:14.035   316  1371 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-16 10:29:14.035   316  1371 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-16 10:29:14.036   316  1371 V AudioFlinger: createTrack() lSessionId: 23
08-16 10:29:14.036  7141  7158 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 10:29:14.036  7141  7158 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-16 10:29:14.036  7141  7141 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-16 10:29:14.037   316  1371 V AudioFlinger: acquiring 23 from 7141, for 7141
08-16 10:29:14.037   316  1371 V AudioFlinger:  added new entry for 23
08-16 10:29:14.037  7141  7141 V ToneGenerator: ToneGenerator INIT OK, time: 393582
08-16 10:29:14.037  7141  7141 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@eb0aa1f
08-16 10:29:14.038  7141  7171 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-16 10:29:14.038  7141  7192 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-16 10:29:14.038  7141  7192 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-16 10:29:14.038  7141  7141 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@eb0aa1f
08-16 10:29:14.040  7141  7192 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-16 10:29:14.040  7141  7141 D A2dpService: Received start request. Starting profile...
08-16 10:29:14.041  7141  7141 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-16 10:29:14.041  7141  7141 V Avrcp   : make
08-16 10:29:14.042  7141  7141 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-16 10:29:14.042  7141  7141 I bluedroid-qcom: get_profile_interface avrcp
08-16 10:29:14.044  7141  7192 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-16 10:29:14.044   316  2137 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7141
08-16 10:29:14.044   316  2137 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-16 10:29:14.044   316  2137 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-16 10:29:14.045   316  2137 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-16 10:29:14.045   316  2137 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-16 10:29:14.045   316  2137 V voice   : voice_set_parameters: exit with code(0)
08-16 10:29:14.045   316  2137 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-16 10:29:14.045   316  2137 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-16 10:29:14.045   316  2137 V msm8974_platform: platform_set_parameters: exit with code(0)
08-16 10:29:14.045   316  2137 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-16 10:29:14.045   31,6  2137 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-16 10:29:14.045   316  2137 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-16 10:29:14.045  7141  7192 V ToneGenerator: ToneGenerator destructor
08-16 10:29:14.045  7141  7192 V ToneGenerator: stopTone
08-16 10:29:14.045  7141  7192 V ToneGenerator: Delete Track: 0xb4928080
08-16 10:29:14.046  7141  7192 V AudioTrack: ~AudioTrack, releasing session id from 7141 on behalf of 7141
08-16 10:29:14.046   316  1371 V AudioFlinger: releasing 23 from 7141 for 7141
08-16 10:29:14.046   316  1371 V AudioFlinger:  decremented refcount to 0
08-16 10:29:14.046   316  1371 V AudioFlinger: purging stale effects
08-16 10:29:14.046   316  1371 V AudioPolicyService: AudioCommandThread() adding release output 2
08-16 10:29:14.046   316  1371 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-16 10:29:14.046   316  1269 V AudioPolicyService: AudioCommandThread() waking up
08-16 10:29:14.046   316  1269 V AudioPolicyService: AudioCommandThread() processing release output 2
08-16 10:29:14.046   316  1269 V AudioPolicyManager: releaseOutput() 2
08-16 10:29:14.046   316  1269 V AudioPolicyService: AudioCommandThread() going to sleep
08-16 10:29:14.049   316  1371 V AudioFlinger: PlaybackThread::Track destructor
08-16 10:29:14.049   316  1371 V AudioFlinger: removeClient_l() pid 7141, calling pid 316
,08-16 10:29:14.050  7141  7141 V AudioManager: registerRemoteController: size of Media player list: 0
,08-16 10:29:14.052  7141  7141 E AudioManager: No RCC entry present to update
08-16 10:29:14.052  7141  7141 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-16 10:29:14.054  7141  7141 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-16 10:29:14.055  7141  7141 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-16 10:29:14.055  7141  7141 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-16 10:29:14.058  7141  7141 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-16 10:29:14.163  1037  1560 V SIM_STK : Menu title from STK is T-Mobile
08-16 10:29:14.163  1037  1560 V SIM_STK : Menu title from STK is T-Mobile
,08-16 10:29:14.233  1037  2034 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-16 10:29:14.242  7141  7141 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-16 10:29:14.246  7141  7141 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-16 10:29:14.246  7141  7141 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
,08-16 10:29:14.246  7141  7141 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-16 10:29:14.246  7141  7141 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-16 10:29:14.246  7141  7141 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-16 10:29:14.246  7141  7141 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-16 10:29:14.246  7141  7141 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-16 10:29:14.246  7141  7141 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-16 10:29:14.246  7141  7141 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-16 10:29:14.247  7141  7141 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-16 10:29:14.247  7141  7141 I BluetoothA2dpServiceJni: classInitNative
08-16 10:29:14.247  7141  7141 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-16 10:29:14.247  7141  7141 D A2dpStateMachine: make
08-16 10:29:14.250  7141  7141 I bluedroid-qcom: get_profile_interface a2dp
,08-16 10:29:14.250  7141  7200 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-16 10:29:14.255  7141  7141 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-16 10:29:14.255  7141  7141 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-16 10:29:14.256  7141  7141 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@eb0aa1f
08-16 10:29:14.256  7141  7199 D A2dpStateMachine: Enter Disconnected: -2
08-16 10:29:14.256  7141  7141 I BluetoothHidServiceJni: classInitNative: succeeds
08-16 10:29:14.258  7141  7141 D HidService: Received start request. Starting profile...
,08-16 10:29:14.258  7141  7141 I bluedroid-qcom: get_profile_interface hidhost
08-16 10:29:14.258  7141  7141 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@eb0aa1f
08-16 10:29:14.259  7141  7141 I BluetoothHealthServiceJni: classInitNative: succeeds
08-16 10:29:14.260  7141  7141 D HealthService: Received start request. Starting profile...
08-16 10:29:14.263  7141  7141 I bluedroid-qcom: get_profile_interface health
08-16 10:29:14.263  7141  7141 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-16 10:29:14.263  7141  7141 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@eb0aa1f
08-16 10:29:14.264  7141  7141 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-16 10:29:14.265  7141  7141 D PanService: Received start request. Starting profile...
08-16 10:29:14.265  7141  7141 D BluetoothPanServiceJni: initializeNative(L110): pan
08-16 10:29:14.265  7141  7141 I bluedroid-qcom: get_profile_interface pan
08-16 10:29:14.272  7141  7141 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-16 10:29:14.272  7141  7141 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@eb0aa1f
08-16 10:29:14.273  7141  7141 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-16 10:29:14.276  7141  7141 D BtGatt.DebugUtils: handleDebugAction() action=null
08-16 10:29:14.277  7141  7141 D BtGatt.GattService: Received start request. Starting profile...
08-16 10:29:14.277  7141  7141 D BtGatt.GattService: start()
08-16 10:29:14.277  7141  7141 I bluedroid-qcom: get_profile_interface gatt
08-16 10:29:14.277  7141  7141 D BtGatt.AdvertiseManager: advertise manager created
,08-16 10:29:14.286  7141  7141 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@eb0aa1f
,08-16 10:29:14.287  7141  7141 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@eb0aa1f
08-16 10:29:14.287  7141  7141 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-16 10:29:14.288  7141  7141 V BluetoothMapService: BluetoothMapBinder()
08-16 10:29:14.288  7141  7141 D BluetoothMapService: Received start request. Starting profile...
08-16 10:29:14.288  7141  7141 D BluetoothMapService: start()
08-16 10:29:14.291  7141  7141 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-16 10:29:14.291  7141  7141 D BluetoothMapEmailAppObserver: createReceiver()
,08-16 10:29:14.291  7141  7141 D BluetoothMapEmailAppObserver: initObservers()
08-16 10:29:14.291  7141  7141 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-16 10:29:14.296  7141  7141 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@eb0aa1f
08-16 10:29:14.297  7141  7141 D HeadsetStateMachine: Proxy object connected
08-16 10:29:14.297  7141  7141 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-16 10:29:14.298  7141  7141 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-16 10:29:14.313  7141  7141 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-16 10:29:14.317  7141  7192 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-16 10:29:14.319  7141  7192 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-16 10:29:14.321  7141  7192 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-16 10:29:14.323  7141  7141 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-16 10:29:14.329  7141  7141 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-16 10:29:14.333  7141  7141 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-16 10:29:14.339  7141  7141 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 10:29:14.344  7141  7141 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 10:29:14.344  7141  7141 V PanService: [BTUI] SIM Extra State :ABSENT
,08-16 10:29:14.350  7141  7141 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-16 10:29:14.350  7141  7141 V BluetoothMapService: Handler(): got msg=1
08-16 10:29:14.351  7141  7171 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-16 10:29:14.351  7141  7171 I bluedroid-qcom: enable
08-16 10:29:14.352  7141  7141 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 10:29:14.352  7141  7141 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 10:29:14.352  7141  7141 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 10:29:14.352  7141  7141 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 10:29:14.353  7141  7141 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
,08-16 10:29:14.353  7141  7210 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-16 10:29:14.354  7141  7171 I bt_hci_bdroid: init
08-16 10:29:14.357  7141  7171 I bt_vendor: bt-vendor : init
08-16 10:29:14.357  7141  7171 I bt_vendor: bt-vendor : get_bt_soc_type
08-16 10:29:14.357  7141  7171 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-16 10:29:14.357  7141  7171 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-16 10:29:14.357  7141  7171 D bt_userial_mct: userial_init
08-16 10:29:14.357  7141  7210 I bt-btu  : btu_task pending for preload complete event
08-16 10:29:14.358  7141  7171 D bt_hci_bdroid: set_power 1
08-16 10:29:14.358  7141  7171 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-16 10:29:14.358  7141  7171 I bt_vendor: Starting hciattach daemon
08-16 10:29:14.358  7141  7171 I bt_vendor: try to set true
,08-16 10:29:14.352  7213  7213 W sh      : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 10:29:14.352  7213  7213 W sh      : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 10:29:14.392  7214  7214 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-16 10:29:14.509  7220  7220 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-16 10:29:14.537  7221  7221 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-16 10:29:14.566  7223  7223 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-16 10:29:14.586  7224  7224 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-16 10:29:14.599  7225  7225 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-16 10:29:14.625  7226  7226 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-16 10:29:14.647  7231  7231 I libmdmdetect: ESOC framework not supported
08-16 10:29:14.648  7231  7231 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-16 10:29:14.655  7231  7231 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-16 10:29:14.655  7231  7231 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-16 10:29:14.655  7231  7231 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-16 10:29:14.655  7231  7231 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-16 10:29:14.655  7231  7231 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-16 10:29:14.655  7231  7231 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-16 10:29:14.656  7231  7231 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-16 10:29:14.694  7231  7232 E QC-QMI  : qmi_client [7231] 15: failed to locate client data
08-16 10:29:14.695   479   479 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-16 10:29:14.695   479   479 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,08-16 10:29:14.743  7236  7236 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-16 10:29:14.760  7237  7237 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-16 10:29:14.778  7141  7171 I bt_vendor: bluetooth satus is on
08-16 10:29:14.778  7141  7171 D bt_hci_bdroid: preload
,08-16 10:29:14.780  7141  7212 D bt_userial_mct: userial_open(port:0)
08-16 10:29:14.780  7141  7212 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-16 10:29:14.784  7141  7212 I bt_vendor: Done intiailizing UART
08-16 10:29:14.784  7141  7212 I bt_vendor: Done intiailizing UART
08-16 10:29:14.784  7141  7212 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-16 10:29:14.785  7141  7212 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-16 10:29:14.785  7141  7210 I bt-btu  : btu_task received preload complete event
08-16 10:29:14.785  7141  7210 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-16 10:29:14.785  7141  7210 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-16 10:29:14.788  7141  7210 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-16 10:29:14.790  7141  7239 D bt_userial_mct: Entering userial_read_thread()
,08-16 10:29:14.795  7141  7210 I         : BTE_InitTraceLevels -- TRC_HCI
,08-16 10:29:14.795  7141  7210 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-16 10:29:14.795  7141  7210 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-16 10:29:14.795  7141  7210 I         : BTE_InitTraceLevels -- TRC_AVDT
08-16 10:29:14.795  7141  7210 I         : BTE_InitTraceLevels -- TRC_AVRC
08-16 10:29:14.795  7141  7210 I         : BTE_InitTraceLevels -- TRC_A2D
08-16 10:29:14.795  7141  7210 I         : BTE_InitTraceLevels -- TRC_BNEP
08-16 10:29:14.795  7141  7210 I         : BTE_InitTraceLevels -- TRC_BTM
08-16 10:29:14.795  7141  7210 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-16 10:29:14.795  7141  7210 I         : BTE_InitTraceLevels -- TRC_GAP
08-16 10:29:14.796  7141  7210 I         : BTE_InitTraceLevels -- TRC_PAN
08-16 10:29:14.796  7141  7210 I         : BTE_InitTraceLevels -- TRC_SDP
08-16 10:29:14.796  7141  7210 I         : BTE_InitTraceLevels -- TRC_GATT
08-16 10:29:14.796  7141  7210 I         : BTE_InitTraceLevels -- TRC_SMP
08-16 10:29:14.796  7141  7210 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-16 10:29:14.796  7141  7210 I         : BTE_InitTraceLevels -- TRC_BTIF
08-16 10:29:14.898  7141  7210 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-16 10:29:14.898  7141  7210 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0244061 
08-16 10:29:14.898  7141  7210 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0244061 
,08-16 10:29:14.939  7141  7175 E bt-btif : Calling BTA_HhEnable
08-16 10:29:14.939  7141  7175 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-16 10:29:14.939  7141  7175 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-16 10:29:14.943  7141  7210 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-16 10:29:14.943  7141  7210 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-16 10:29:14.943  7141  7210 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-16 10:29:14.943  7141  7210 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-16 10:29:14.943  7141  7210 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-16 10:29:14.944  1037  1037 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-16 10:29:14.944  1037  1037 D BluetoothManagerService: Stored Bluetooth name: G3
08-16 10:29:14.945  7141  7175 D BluetoothAdapterProperties: Name is: G3
08-16 10:29:14.946  7141  7175 D BluetoothAdapterProperties: Scan Mode:20
08-16 10:29:14.947  7141  7175 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 10:29:14.947  7141  7175 D bt_hci_bdroid: postload
08-16 10:29:14.947  7141  7212 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 10:29:14.948  7141  7175 D bte_conf: Device ID record 1 : primary
08-16 10:29:14.948  7141  7175 D bte_conf:   vendorId            = 00c4
08-16 10:29:14.948  7141  7175 D bte_conf:   vendorIdSource      = 0001
08-16 10:29:14.948  7141  7175 D bte_conf:   product             = 13a1
08-16 10:29:14.948  7141  7175 D bte_conf:   version             = 1000
08-16 10:29:14.948  7141  7175 D bte_conf:   clientExecutableURL = 
08-16 10:29:14.948  7141  7175 D bte_conf:   serviceDescription  = 
08-16 10:29:14.948  7141  7175 D bte_conf:   documentationURL    = 
08-16 10:29:14.948  7141  7175 D bte_conf: bte_load_did_conf no section named DID2.
08-16 10:29:14.949  7141  7210 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-16 10:29:14.950  7141  7212 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 10:29:14.953  7141  7171 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-16 10:29:14.953  7141  7171 D BluetoothAdapterProperties: ScanMode =  20
08-16 10:29:14.953  7141  7171 D BluetoothAdapterProperties: State =  11
,08-16 10:29:14.959  7141  7171 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-16 10:29:14.960  7141  7171 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-16 10:29:14.960  7141  7171 D BluetoothAdapterProperties: Setting state to 12
08-16 10:29:14.960  7141  7171 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-16 10:29:14.960  7141  7175 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-16 10:29:14.961  7141  7175 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-16 10:29:14.952  7241  7241 W sh      : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 10:29:14.952  7241  7241 W sh      : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 10:29:14.970  1037  1119 D BluetoothManagerService: Message: 60
08-16 10:29:14.970  1037  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-16 10:29:14.970  1037  1119 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
,08-16 10:29:14.974  7141  7212 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 10:29:14.978  7141  7212 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 10:29:14.978  7141  7239 E bt_mct  : hci lib postload completed
08-16 10:29:14.985  7141  7210 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 10:29:14.985  7141  7210 W bt-smp  : Plain text(LSB ~ MSB) = f3 61 5b 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 10:29:14.985  7141  7210 W bt-smp  : Encrypted text(LSB ~ MSB) = 5e 8b e9 11 a5 6c dc b7 49 b6 74 e3 13 bf 9a bf 
,08-16 10:29:14.989  7141  7210 W bt-btm  : Stopping oneshot timer
08-16 10:29:15.001  7141  7175 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 10:29:15.001  7141  7175 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
,08-16 10:29:15.004  7141  7171 I BluetoothAdapterState: Entering On State
08-16 10:29:15.007  1838  2748 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 10:29:15.024  7141  7210 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 10:29:15.024  7141  7210 W bt-smp  : Plain text(LSB ~ MSB) = a2 95 6b 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 10:29:15.024  7141  7210 W bt-smp  : Encrypted text(LSB ~ MSB) = 8a 97 95 00 45 cf 2f 48 51 0e 39 01 f9 4c 51 a6 
,08-16 10:29:15.027  7141  7210 W bt-btm  : Stopping oneshot timer
08-16 10:29:15.027  6149  6149 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 10:29:15.027  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 10:29:15.027  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 10:29:15.027  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 10:29:15.027  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 10:29:15.027  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 10:29:15.027  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 10:29:15.027  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 10:29:15.035  6149  6149 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 10:29:15.040  7141  7210 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 10:29:15.040  7141  7210 W bt-smp  : Plain text(LSB ~ MSB) = 2f 91 75 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 10:29:15.040  7141  7210 W bt-smp  : Encrypted text(LSB ~ MSB) = 9e ba c3 1e 93 01 71 65 63 a5 8e fa 2e 43 5c 72 
,08-16 10:29:15.043  7141  7210 W bt-btm  : Stopping oneshot timer
08-16 10:29:15.059  7141  7210 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 10:29:15.059  7141  7210 W bt-smp  : Plain text(LSB ~ MSB) = 67 f3 43 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 10:29:15.059  7141  7210 W bt-smp  : Encrypted text(LSB ~ MSB) = e8 b7 50 28 60 1e 39 e3 1d 4b 10 aa 0c 72 e2 15 
,08-16 10:29:15.062  7141  7210 W bt-btm  : Stopping oneshot timer
08-16 10:29:15.064  6149  6149 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 10:29:15.064  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 10:29:15.064  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 10:29:15.064  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 10:29:15.064  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 10:29:15.064  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 10:29:15.064  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 10:29:15.064  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 10:29:15.074  7246  7246 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,08-16 10:29:15.082  6149  6149 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 10:29:15.083  7141  7171 D LGBluetoothServiceAdapter: [BTUI] OnState
08-16 10:29:15.083  7141  7171 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-16 10:29:15.083  7141  7171 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-16 10:29:15.084  7141  7171 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-16 10:29:15.084  7141  7171 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-16 10:29:15.087  1838  1838 D BluetoothHeadset: Proxy object connected
08-16 10:29:15.088  6279  6295 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-16 10:29:15.092  1037  1119 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-16 10:29:15.093  7141  7210 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 10:29:15.093  7141  7210 W bt-smp  : Plain text(LSB ~ MSB) = 3a 1b 4b 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 10:29:15.093  7141  7210 W bt-smp  : Encrypted text(LSB ~ MSB) = d8 fd 18 8b 9f 61 08 65 c1 15 71 a2 0a 50 34 09 
,08-16 10:29:15.093  7141  7210 W bt-btm  : Stopping oneshot timer
,08-16 10:29:15.094  1037  1037 D BluetoothHeadset: Proxy object connected
08-16 10:29:15.097  6279  6279 D BluetoothHeadset: Proxy object connected
08-16 10:29:15.097  6279  6279 D HeadsetProfile: Bluetooth service connected
08-16 10:29:15.108  6279  6295 D BluetoothMap: onBluetoothStateChange: up=true
,08-16 10:29:15.119  1037  1119 D BluetoothA2dp: onBluetoothStateChange: up=true
08-16 10:29:15.120  6279  6279 D BluetoothMap: Proxy object connected
,08-16 10:29:15.120  6279  6279 D MapProfile: Bluetooth service connected
08-16 10:29:15.120  6279  6279 D BluetoothMap: getConnectedDevices()
08-16 10:29:15.121  7141  7252 V BluetoothMapService: getConnectedDevices()
08-16 10:29:15.122  6279  6294 D BluetoothA2dp: onBluetoothStateChange: up=true
08-16 10:29:15.122  1037  1037 D BluetoothA2dp: Proxy object connected
08-16 10:29:15.125  6279  6279 D BluetoothA2dp: Proxy object connected
08-16 10:29:15.125  6279  6279 D A2dpProfile: Bluetooth service connected
08-16 10:29:15.126  6279  6294 D BluetoothPan: onBluetoothStateChange on: true
08-16 10:29:15.126  6279  6294 D BluetoothPan: onBluetoothStateChange call bindService
,08-16 10:29:15.128  1838  1853 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 10:29:15.129  6279  6279 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 10:29:15.129  6279  6279 D PanProfile: Bluetooth service connected
08-16 10:29:15.130  1838  1838 D BluetoothHeadset: Proxy object connected
08-16 10:29:15.130  1838  2749 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 10:29:15.132  1838  1838 D BluetoothHeadset: Proxy object connected
08-16 10:29:15.133  6279  6295 D BluetoothPbap: onBluetoothStateChange: up=true
08-16 10:29:15.134  6279  6294 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-16 10:29:15.137  6279  6279 D BluetoothInputDevice: Proxy object connected
08-16 10:29:15.137  6279  6279 D HidProfile: Bluetooth service connected
08-16 10:29:15.138  1037  1119 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-16 10:29:15.138  1037  1119 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
,08-16 10:29:15.139  1037  1037 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-16 10:29:15.140  1037  1119 D BluetoothManagerService: Message: 40
08-16 10:29:15.140  1037  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-16 10:29:15.140  1928  1928 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-16 10:29:15.141  1588  1588 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 10:29:15.143  1928  2114 D LGBluetoothAPIService: Message: 1
08-16 10:29:15.143  1928  2114 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-16 10:29:15.144  1928  2114 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
08-16 10:29:15.144  1928  2114 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-16 10:29:15.145  6149  6149 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 10:29:15.147  6149  6149 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 10:29:15.151  7141  7141 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-16 10:29:15.151  7141  7141 D BluetoothMapService: STATE_ON
08-16 10:29:15.154  6279  6279 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-16 10:29:15.155  6279  6279 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-16 10:29:15.161  6279  6279 D DockEventReceiver: finishStartingService: stopping service
08-16 10:29:15.164  7141  7141 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@eb0aa1f
08-16 10:29:15.164  7141  7141 V BluetoothPbapService: Pbap Service onCreate
08-16 10:29:15.164  7141  7141 V BluetoothPbapService: Starting PBAP service
,08-16 10:29:15.165  7141  7141 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-16 10:29:15.166  7141  7141 V BluetoothPbapService: Pbap Service onBind
08-16 10:29:15.166  7141  7141 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,08-16 10:29:15.166  7141  7141 V BluetoothPbapService: state: 12
08-16 10:29:15.166  6279  6279 D BluetoothPbap: Proxy object connected
08-16 10:29:15.166  6279  6279 D PbapServerProfile: Bluetooth service connected
08-16 10:29:15.166  7141  7141 V BluetoothMapService: Handler(): got msg=1
08-16 10:29:15.167  7141  7141 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-16 10:29:15.167  7141  7141 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-16 10:29:15.167  7141  7141 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 10:29:15.167  7141  7141 V BluetoothPbapReceiver: ***********state = 12
08-16 10:29:15.168  7141  7265 D BluetoothMapMasInstance: MAS initSocket()
08-16 10:29:15.168  7141  7265 D BluetoothMapMasInstance:   masId = 00
08-16 10:29:15.168  7141  7265 D BluetoothMapMasInstance:   msgTypes = 0e
08-16 10:29:15.168  7141  7265 D BluetoothMapMasInstance:   masName = SMS/MMS
08-16 10:29:15.168  7141  7265 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-16 10:29:15.168  7141  7141 V BluetoothPbapService: Handler(): got msg=1
08-16 10:29:15.169  7141  7141 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-16 10:29:15.170  7141  7266 V BluetoothPbapService: Pbap Service initSocket
08-16 10:29:15.170  1037  1053 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 10:29:15.170  2179  2179 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 10:29:15.170  1037  1873 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 10:29:15.171  7141  7265 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 10:29:15.171  7141  7266 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 10:29:15.171  2179  2179 D c       : Getting all permits...
08-16 10:29:15.171  2179  2179 D a       : Opening database...
08-16 10:29:15.173  7141  7265 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-16 10:29:15.173  7141  7265 V BluetoothMapMasInstance: Succeed to create listening socket 
08-16 10:29:15.173  7141  7265 D BluetoothMapMasInstance: Accepting socket connection...
08-16 10:29:15.174  7141  7175 D BluetoothAdapterProperties: Scan Mode:21
08-16 10:29:15.174  7141  7175 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-16 10:29:15.176  2179  2179 D a       : Opening database auth.proximity.permit_store...
08-16 10:29:15.176  7141  7266 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
,08-16 10:29:15.177  7141  7175 D BluetoothAdapterProperties: Scan Mode:21
08-16 10:29:15.177  7141  7175 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-16 10:29:15.177  6149  6149 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 10:29:15.177  2179  2179 D a       : Closing database...
08-16 10:29:15.177  7141  7266 V BluetoothPbapService: Succeed to create listening socket 
08-16 10:29:15.178  7141  7266 V BluetoothPbapService: Accepting socket connection...
08-16 10:29:15.178  6149  6149 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 10:29:15.179  6149  6149 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 10:29:15.180  6149  6149 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 10:29:15.195  6279  6279 D BluetoothPermissionRequest: onReceive
,08-16 10:29:15.197  6279  6279 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,08-16 10:29:15.198  6279  6279 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-16 10:29:15.201  7141  7141 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-16 10:29:15.203  7141  7141 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-16 10:29:15.208  7141  7141 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-16 10:29:15.228  7141  7141 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-16 10:29:15.228  7141  7141 V BtOppService: onCreate
,08-16 10:29:15.233  7141  7141 V BluetoothOppNotification: send message
08-16 10:29:15.236  7141  7141 V BtOppService: Starting RfcommListener
08-16 10:29:15.245  7141  7141 D BluetoothOppPreference: Dumping Names:  
08-16 10:29:15.245  7141  7141 D BluetoothOppPreference: {}
,08-16 10:29:15.245  7141  7141 D BluetoothOppPreference: Dumping Channels:  
,08-16 10:29:15.245  7141  7141 D BluetoothOppPreference: {}
08-16 10:29:15.250  7141  7141 V BtOppService: onStartCommand
08-16 10:29:15.252  7141  7275 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-16 10:29:15.252  7141  7275 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-16 10:29:15.254  7141  7272 V BtOppService: Deleted complete outbound shares, number =  0
08-16 10:29:15.256  7141  7275 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@d21e70b on behalf of 
08-16 10:29:15.256  7141  7141 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-16 10:29:15.256  7141  7141 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-16 10:29:15.257  7141  7275 V BluetoothOppNotification: update too frequent, put in queue
08-16 10:29:15.260  7141  7275 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
,08-16 10:29:15.261  7141  7275 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-16 10:29:15.262  7141  7141 V BluetoothOppNotification: new notify threadi!
08-16 10:29:15.264  7141  7141 V BluetoothOppNotification: send delay message
08-16 10:29:15.265  7141  7272 V BtOppService: Deleted complete inbound failed shares, number = 0
08-16 10:29:15.266  7141  7276 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-16 10:29:15.266  7141  7272 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-16 10:29:15.266  7141  7141 V BtOppService: start RfcommListener
08-16 10:29:15.268  7141  7276 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2956e9e8 on behalf of 
08-16 10:29:15.268  7141  7275 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@26b67801 on behalf of 
08-16 10:29:15.269  7141  7272 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@260796a6 on behalf of 
08-16 10:29:15.273  7141  7276 V BluetoothOppNotification: mUpdateCompleteNotification = true
,08-16 10:29:15.276  7141  7141 V BtOppService: RfcommListener started
08-16 10:29:15.279  7141  7141 V BtOppService: ContentObserver received notification
08-16 10:29:15.279  7141  7276 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-16 10:29:15.280  7141  7277 V BtOppRfcommListener: Starting RFCOMM listener....
08-16 10:29:15.281  7141  7275 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-16 10:29:15.281  1037  1560 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 10:29:15.281  7141  7141 V BtOppService: ContentObserver received notification
08-16 10:29:15.281  7141  7276 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2b85e8e7 on behalf of 
08-16 10:29:15.282  7141  7277 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 10:29:15.283  7141  7276 V BluetoothOppNotification: outbound: succ-0  fail-0
08-16 10:29:15.283  7141  7277 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
08-16 10:29:15.283  7141  7277 V BtOppRfcommListener: Started RFCOMM listener....
08-16 10:29:15.284  7141  7277 I BtOppRfcommListener: Accept thread started.
08-16 10:29:15.284  7141  7277 V BtOppRfcommListener: Accepting connection...
08-16 10:29:15.284  7141  7278 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-16 10:29:15.284  7141  7278 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-16 10:29:15.287  7141  7276 V BluetoothOppNotification: outbound notification was removed.
08-16 10:29:15.287  7141  7276 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
,08-16 10:29:15.288  7141  7278 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1ea4bc94 on behalf of 
08-16 10:29:15.289  7141  7276 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2c11933d on behalf of 
08-16 10:29:15.290  7141  7276 V BluetoothOppNotification: inbound: succ-0  fail-0
08-16 10:29:15.291  7141  7278 V BluetoothOppNotification: update too frequent, put in queue
08-16 10:29:15.293  7141  7278 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-16 10:29:15.293  7141  7276 V BluetoothOppNotification: inbound notification was removed.
08-16 10:29:15.293  7141  7276 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-16 10:29:15.295  7141  7276 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3c867732 on behalf of 
08-16 10:29:15.302  7141  7141 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@eb0aa1f
,08-16 10:29:15.302  7141  7141 V BluetoothFtpService: Ftp Service onCreate
08-16 10:29:15.302  7141  7141 I BluetoothFtpService: Ftp Service onCreate
08-16 10:29:15.302  7141  7141 V BluetoothFtpService: Ftp Service onStartCommand
08-16 10:29:15.303  7141  7141 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 10:29:15.304  7141  7141 V BluetoothFtpService: Starting Listening on sockets
,08-16 10:29:15.305  7141  7141 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 10:29:15.305  7141  7141 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 10:29:15.305  7141  7141 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 10:29:15.305  7141  7141 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 10:29:15.305  7141  7141 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-16 10:29:15.305  7141  7141 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-16 10:29:15.307  7141  7141 V BluetoothFtpService: Handler(): got msg=1
08-16 10:29:15.309  7141  7141 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-16 10:29:15.309  7141  7141 V BluetoothFtpService: Ftp Service initSocket
08-16 10:29:15.314  1037  1963 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 10:29:15.315  7141  7141 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 10:29:15.316  7141  7141 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=79
08-16 10:29:15.317  7141  7141 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-16 10:29:15.319  7141  7279 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-16 10:29:15.333  7141  7141 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@eb0aa1f
08-16 10:29:15.334  7141  7141 V BluetoothSapService: Sap Service onCreate
,08-16 10:29:15.336  7141  7141 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 10:29:15.336  7141  7141 V BluetoothSapService: state: 12
08-16 10:29:15.337  7141  7141 V BluetoothSapService: Starting SAP server process
08-16 10:29:15.332  7280  7280 W sapd    : type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 10:29:15.332  7280  7280 W sapd    : type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 10:29:15.340  7141  7141 V BluetoothSapService: SAP Service startRfcommListenerThread
08-16 10:29:15.343  7141  7281 V BluetoothSapService: Sap Service initRfcommSocket
08-16 10:29:15.344  1037  1873 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 10:29:15.346  7141  7281 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 10:29:15.349  7141  7281 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-16 10:29:15.349  7141  7281 V BluetoothSapService: Succeed to create listening socket 
08-16 10:29:15.350  7141  7281 V BluetoothSapService: Accepting socket connection...
08-16 10:29:15.358  7280  7280 V BT_SAP  : Event pipe created
08-16 10:29:15.358  7280  7280 V BT_SAP  : create_server_socket qcom.sap.server
,08-16 10:29:15.358  7280  7280 V BT_SAP  : created socket fd 6
,08-16 10:29:15.845  6149  6212 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 10:29:15.845  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 10:29:15.845  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 10:29:15.845  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 10:29:15.845  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 10:29:15.845  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 10:29:15.845  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 10:29:15.845  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 10:29:15.859  6149  6212 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 10:29:15.863  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:29:15.863  6149  6212 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3849f1a8 removed from the list
08-16 10:29:15.864  6149  6212 D io.jxcore.node.ConnectivityMonitor: stop
08-16 10:29:15.864  6149  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:29:15.864  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 10:29:15.869  6149  6212 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 10:29:15.869  6149  6212 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f0d44c1 added. We now have 4 listener(s)
08-16 10:29:15.869  6149  6212 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 10:29:15.872  1037  1052 D WifiServiceImplEx: setWifiEnabled: false pid=6149, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-16 10:29:15.872  1037  1052 D WifiService: setWifiEnabled: false pid=6149, uid=10118
08-16 10:29:15.872  1037  1052 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-16 10:29:15.879  6149  6212 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 10:29:15.882  1037  1981 D WifiServiceImplEx: setWifiEnabled: true pid=6149, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-16 10:29:15.882  1037  1981 D WifiService: setWifiEnabled: true pid=6149, uid=10118
08-16 10:29:15.882  1037  1981 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 10:29:15.910  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 10:29:15.911  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 10:29:15.911  1037  1037 D Ulp_jni : JNI:system_update. Event-4
08-16 10:29:15.912  1037  1523 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-16 10:29:15.912  1037  1523 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-16 10:29:15.921  1037  1523 E WifiUtil: wfc_util_ffile_check_copy(): pid[1037] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-16 10:29:15.921  1037  1523 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-16 10:29:15.921  1037  1523 E WifiUtil: wfc_util_ffile_check_copy(): pid[1037] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-16 10:29:15.921  1037  1523 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-16 10:29:15.922  1037  1523 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-16 10:29:15.922  1037  1523 E WifiHW  : unknown target_country: EU , set to default
08-16 10:29:15.922  1037  1523 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-16 10:29:15.922  1037  1523 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-16 10:29:15.922  1037  1523 I WifiUtil: gEnableBmps=1
,08-16 10:29:16.267  7141  7141 V BluetoothOppNotification: new notify threadi!
,08-16 10:29:16.267  7141  7141 V BluetoothOppNotification: send delay message
,08-16 10:29:16.280  7141  7294 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-16 10:29:16.285  7141  7294 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@27ad0ddf on behalf of 
,08-16 10:29:16.290  7141  7294 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-16 10:29:16.291  7141  7294 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-16 10:29:16.292  7141  7294 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@38630a2c on behalf of 
08-16 10:29:16.293  7141  7294 V BluetoothOppNotification: outbound: succ-0  fail-0
08-16 10:29:16.295  7141  7294 V BluetoothOppNotification: outbound notification was removed.
08-16 10:29:16.295  7141  7294 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
,08-16 10:29:16.329  7141  7294 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@394cecf5 on behalf of 
08-16 10:29:16.329  7141  7294 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-16 10:29:16.334  7141  7294 V BluetoothOppNotification: inbound notification was removed.
08-16 10:29:16.334  7141  7294 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-16 10:29:16.335  7141  7294 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1071ba8a on behalf of 
08-16 10:29:16.497   305   906 D SoftapController: Softap fwReload - Ok
,08-16 10:29:16.505  1037  1523 E NetdConnector: NDC Command {67 softap fwreload wlan0 STA} took too long (573ms)
08-16 10:29:16.512   305   906 D CommandListener: Setting iface cfg
08-16 10:29:16.512   305   906 D CommandListener: Trying to bring down wlan0
,08-16 10:29:16.536  1037  1119 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-16 10:29:16.537   305   906 D CommandListener: Clearing all IP addresses on wlan0
08-16 10:29:16.546  1037  1523 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,08-16 10:29:16.566  1037  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 10:29:16.566  1037  1523 E WifiStateMachine: useWiFiOffloading() : false
08-16 10:29:16.566  1037  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-16 10:29:16.562  7302  7302 W wpa_supplicant: type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-16 10:29:16.562  7302  7302 W wpa_supplicant: type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 10:29:16.576  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 10:29:16.583  1928  1928 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
,08-16 10:29:16.594  6279  6279 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-16 10:29:16.594  6279  6279 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-16 10:29:16.594  6279  6279 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-16 10:29:16.594  6279  6279 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-16 10:29:16.591  1037  1523 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-16 10:29:16.595  1037  1523 D WifiMonitor: connecting to supplicant
,08-16 10:29:16.603  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-16 10:29:16.606  6149  6149 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 10:29:16.607  6279  6279 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-16 10:29:16.607  6149  6149 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 10:29:16.608  6279  6279 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-16 10:29:16.608  6279  6279 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-16 10:29:16.608  6279  6279 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-16 10:29:16.608  6279  6279 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-16 10:29:16.609  6279  6279 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-16 10:29:16.609  6279  6279 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-16 10:29:16.609  6279  6279 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-16 10:29:16.617  7302  7302 I wpa_supplicant: Successfully initialized wpa_supplicant
08-16 10:29:16.618  6296  6296 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 10:29:16.620  6279  6279 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-16 10:29:16.625  6279  6279 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-16 10:29:16.640  6396  7320 W FormManager: Network not available. Please check & try again.
,08-16 10:29:16.643  6396  7321 V FormManager: Network unavailable.
08-16 10:29:16.645  6396  7321 V FormManager: Network unavailable.
08-16 10:29:16.651  7302  7302 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-16 10:29:16.651  7302  7302 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-16 10:29:16.653  1037  1119 D Tethering: InitialState.processMessage what=4
08-16 10:29:16.653  1037  1119 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0,
08-16 10:29:16.656  6279  6279 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-16 10:29:16.656  6279  6279 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-16 10:29:16.657  6279  6279 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-16 10:29:16.657  6279  6279 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-16 10:29:16.657  6279  6279 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-16 10:29:16.658  6279  6279 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
,08-16 10:29:16.658  6279  6279 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-16 10:29:16.658  6279  6279 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-16 10:29:16.658  6279  6279 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-16 10:29:16.658  6279  6279 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-16 10:29:16.658  6279  6279 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-16 10:29:16.769  7302  7302 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-16 10:29:16.865  7302  7302 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-16 10:29:16.879  7302  7302 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-16 10:29:16.882  1037  1523 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-16 10:29:16.883  1037  1523 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
,08-16 10:29:16.883  1037  1523 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-16 10:29:16.883  1037  1523 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-16 10:29:16.884  1037  1523 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-16 10:29:16.884  1037  7323 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-16 10:29:16.884  1037  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 10:29:16.885  1037  7323 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-16 10:29:16.885  1037  7323 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-16 10:29:16.885  1037  1523 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-16 10:29:16.885  1037  7323 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-16 10:29:16.885  1037  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 10:29:16.886  1037  1523 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-16 10:29:16.886  1037  1523 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-16 10:29:16.887  1037  1523 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-16 10:29:16.888  1037  1523 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-16 10:29:16.888  1037  1523 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-16 10:29:16.895  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 10:29:16.895  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 10:29:16.896  1037  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 10:29:16.896  1037  1523 E WifiStateMachine: useWiFiOffloading() : false
08-16 10:29:16.896  1037  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-16 10:29:16.896  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 10:29:16.896  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 10:29:16.896  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 10:29:16.899  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 10:29:16.900  1928  1928 D WfdService: Waiting for WifiP2p enabling
08-16 10:29:16.908  6149  6149 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 10:29:16.908  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 10:29:16.908  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 10:29:16.908  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 10:29:16.908  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 10:29:16.908  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 10:29:16.908  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 10:29:16.908  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 10:29:16.909  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-16 10:29:16.909  1037  1527 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-16 10:29:16.910  1037  1523 D WifiNative-wlan0: doBoolean: SET update_config 1
08-16 10:29:16.910  6149  6149 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 10:29:16.912  1037  1523 D WifiNative-wlan0: SET update_config 1: returned true
,08-16 10:29:16.915  1037  1523 D WifiConfigStore: Loading config and enabling all networks 
08-16 10:29:16.915  1037  1523 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-16 10:29:16.916  1037  1523 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-16 10:29:16.919  6149  6149 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 10:29:16.919  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 10:29:16.919  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 10:29:16.919  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 10:29:16.919  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 10:29:16.919  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 10:29:16.919  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 10:29:16.919  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 10:29:16.919  6296  6296 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 10:29:16.923  6149  6149 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 10:29:16.924  6279  6279 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-16 10:29:16.930  1037  1523 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-16 10:29:16.931  6279  6279 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 10:29:16.941  6396  7329 W FormManager: Network not available. Please check & try again.
,08-16 10:29:16.944  6396  7330 V FormManager: Network unavailable.
08-16 10:29:16.947  6396  7330 V FormManager: Network unavailable.
08-16 10:29:16.949  1037  1523 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-16 10:29:16.950  1037  1523 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-16 10:29:16.950  1037  1523 D WifiStateMachine: enableVerboseLogging : level 2
08-16 10:29:16.950  1037  1523 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-16 10:29:16.951  1037  1523 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-16 10:29:16.951  1037  1523 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-16 10:29:16.952  1037  1523 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-16 10:29:16.952  1037  1523 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-16 10:29:16.952  1037  1523 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-16 10:29:16.953  1037  1523 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-16 10:29:16.953  1037  1523 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-16 10:29:16.953  1037  1523 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
,08-16 10:29:16.953  1037  1523 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-16 10:29:16.953  1037  1523 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-16 10:29:16.954  1037  1523 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-16 10:29:16.954  1037  1523 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-16 10:29:16.954  1037  1523 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-16 10:29:16.955  1037  1523 D WifiStateMachine: Setting OUI to DA-A1-19
08-16 10:29:16.955  1037  1523 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-16 10:29:16.957  1928  1928 D WfdsService: Supplicant Connection state is changed : true
08-16 10:29:16.957  1928  2293 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-16 10:29:16.957  1928  2293 D WfdsService: Set the WFDS Monitor: true
08-16 10:29:16.957  1928  2293 D WfdsMonitor: WfdsMonitorThread create
08-16 10:29:16.957  1928  2293 D WfdsMonitor: WFDS Monitor is created and started
08-16 10:29:16.957  1928  2293 D WfdsService: WiFi: Supplicant connection re-established
08-16 10:29:16.957  4259  4259 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 10:29:16.957  4259  4259 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 10:29:16.958  1928  7331 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
,08-16 10:29:16.958  1928  7331 E CtrlSupplicant: Succeed to open control connection
08-16 10:29:16.959  1928  7331 E CtrlSupplicant: Succeed to open monitor connection
08-16 10:29:16.959  1928  7331 D WfdsMonitor: Supplicant connection established
08-16 10:29:16.959  1037  1523 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-16 10:29:16.959  1037  1523 D WifiNative-HAL: Setting external_sim to 1
08-16 10:29:16.959  1928  2293 D WfdsService: Connected to the supplicant for wfds
08-16 10:29:16.959  1037  1523 D WifiNative-wlan0: doBoolean: SET external_sim 1
,08-16 10:29:16.959  1037  1523 D WifiNative-wlan0: SET external_sim 1: returned true
08-16 10:29:16.959  1037  1523 I WifiNative-HAL: startHal
08-16 10:29:16.959  1037  1523 D wifi    : setting scan oui 0xaf5a7020
08-16 10:29:16.960  1037  1523 D WifiStateMachine: Setting OUI to DA-A1-19
08-16 10:29:16.960  1037  1523 I WifiNative-HAL: startHal
08-16 10:29:16.960  1037  1523 D wifi    : setting scan oui 0xaf5a7020
08-16 10:29:16.960  1037  1523 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-16 10:29:16.961  1037  1523 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-16 10:29:16.961  1037  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-16 10:29:16.961  7302  7302 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-16 10:29:16.961  1037  1523 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-16 10:29:16.961  1037  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-16 10:29:16.961  7302  7302 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-16 10:29:16.962  1037  1523 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-16 10:29:16.962  1037  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-16 10:29:16.962  7302  7302 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-16 10:29:16.962  1037  1523 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-16 10:29:16.962  1037  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-16 10:29:16.962  7302  7302 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-16 10:29:16.962  1037  1523 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-16 10:29:16.963  1037  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-16 10:29:16.963  7302  7302 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-16 10:29:16.963  1037  1523 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-16 10:29:16.963  1037  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-16 10:29:16.963  7302  7302 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-16 10:29:16.963  1037  1523 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-16 10:29:16.963  1037  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-16 10:29:16.963  7302  7302 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-16 10:29:16.964  1037  1523 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-16 10:29:16.964  4259  4259 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 10:29:16.965  1037  1523 E WifiNative: : [396,498,700 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-16 10:29:16.965  1037  1523 D WifiNative-wlan0: doBoolean: RECONNECT
08-16 10:29:16.965  1037  1523 D WifiNative-wlan0: RECONNECT: returned true
08-16 10:29:16.965  1037  1523 D WifiNative-wlan0: doString: [STATUS]
08-16 10:29:16.966  4259  4259 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 10:29:16.967  1037  7323 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-16 10:29:16.967  1037  7323 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-16 10:29:16.967  1037  1523 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=,c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-16 10:29:16.967  1037  1523 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 10:29:16.968  1037  1523 D WifiNative-wlan0: SET ps 1: returned true
08-16 10:29:16.969  1037  1522 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-16 10:29:16.970   305   906 D CommandListener: Setting iface cfg
08-16 10:29:16.970   305   906 D CommandListener: Trying to bring up p2p0
08-16 10:29:16.971  1037  1522 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-16 10:29:16.971  1037  1522 D LGWifiP2pService: P2pEnablingState
08-16 10:29:16.971  1037  1522 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-16 10:29:16.971  1037  1522 D LGWifiP2pService: P2p socket connection successful
08-16 10:29:16.971  1037  1522 D LGWifiP2pService: P2pEnabledState
08-16 10:29:16.971  1037  1522 D LGWifiP2pService: sending p2p connection changed broadcast
08-16 10:29:16.973  1928  1928 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-16 10:29:16.973  1037  1522 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-16 10:29:16.974  1037  1522 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-16 10:29:16.975  1037  1522 D WifiNative-p2p0: doBoolean: SET device_name G3
08-16 10:29:16.975  1037  1037 D WifiScanningService: SCAN_AVAILABLE : 3
08-16 10:29:16.975  1037  1037 D RttService: SCAN_AVAILABLE : 3
08-16 10:29:16.975  1037  1541 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-16 10:29:16.975  1037  1541 I WifiNative-HAL: startHal
08-16 10:29:16.975  1928  1928 D WfdsService: WifiP2pState is changed : true
08-16 10:29:16.975  1037  1522 D WifiNative-p2p0: SET device_name G3: returned true
08-16 10:29:16.975  1037  1522 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-16 10:29:16.975  1928  2293 D WfdsService: Receive the WFDS_ENABLE Method
08-16 10:29:16.975  1037  1522 D LGWifiP2pService: before postfix = G3
08-16 10:29:16.976  1928  2293 D WfdsService: Set the WFDS Monitor: true
08-16 10:29:16.976  1037  1522 D WifiServerServiceExt: postfix byte check : 2
08-16 10:29:16.976  1037  1522 D LGWifiP2pService: after postfix = G3
08-16 10:29:16.976  1928  2293 D WfdsService: Connected to the supplicant for wfds
08-16 10:29:16.976  1037  1522 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-16 10:29:16.976  1928  2293 D WfdsJNI : doCommand: WFDS_SET TRUE
08-16 10:29:16.976  7302  7302 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-16 10:29:16.976  1928  2293 D WfdsService: selectPreferredScanChannel [36]
08-16 10:29:16.976  1928  2293 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-16 10:29:16.977  1037  1542 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-16 10:29:16.977  1037  1523 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-16 10:29:16.977  1928  1928 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-16 10:29:16.977  1037  1522 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-16 10:29:16.977  1037  1523 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-16 10:29:16.977  1037  1522 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-16 10:29:16.977  1037  1541 D wifi    : getting scan capabilities on interface[1] = 0xaf5a7020
08-16 10:29:16.977  1037  1541 D wifi    : failed to get capabilities : -3
08-16 10:29:16.977  1037  1541 E WifiScanningService: could not get scan capabilities
08-16 10:29:16.977  1928  1928 D WfdsService: isConnected: false
08-16 10:29:16.978  1037  1522 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-16 10:29:16.978  1037  1523 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-16 10:29:16.979  1037  1523 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-16 10:29:16.979  1037  1522 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-16 10:29:16.979  1037  1523 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-16 10:29:16.979  4259  7332 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-16 10:29:16.979  1037  1523 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-16 10:29:16.980  1037  1523 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-16 10:29:16.980  1037  1523 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-16 10:29:16.980  7302  7302 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-16 10:29:16.981  1037  1522 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-16 10:29:16.981  1037  1522 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-16 10:29:16.981  1037  1522 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-16 10:29:16.981  1037  1522 D WifiNative-HAL: p2pGetDeviceAddress
08-16 10:29:16.981  1037  1522 D WifiNative-HAL: p2pGetDeviceAddress returning 
08-16 10:29:16.984  4259  7333 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 10:29:16.984  4259  7333 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-16 10:29:16.988  1037  1523 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-16 10:29:16.988  1037  1523 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-16 10:29:16.989  1037  1523 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-16 10:29:16.989  1037  1523 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-16 10:29:16.989  7302  7302 E wpa_supplicant: disconnect_rssi_lvl: -100
08-16 10:29:16.990  1037  1523 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-16 10:29:16.990  1037  1523 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-16 10:29:16.990  1037  1523 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-16 10:29:16.990  1037  1523 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-16 10:29:16.991  7302  7302 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-16 10:29:16.992  7302  7302 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 10:29:16.992  7302  7302 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-16 10:29:16.992  7302  7302 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 10:29:16.993  1037  1523 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-16 10:29:16.993  7302  7302 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 10:29:16.993  1037  1523 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-16 10:29:16.994  1037  1523 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-16 10:29:16.994  1037  1523 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-16 10:29:16.994  1037  1523 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-16 10:29:16.994  7302  7302 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-16 10:29:16.994  7302  7302 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 10:29:16.995  1037  7323 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-16 10:29:16.995  1037  7323 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 10:29:16.995  1037  7323 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 10:29:16.995  1037  7323 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 10:29:16.995  1037  7323 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,08-16 10:29:16.995  1037  7323 E WifiMonitor: WifiMonitor:p2p0 cnt=40 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 10:29:16.995  1037  7323 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 10:29:16.995  1037  7323 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 10:29:16.996  1037  7323 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 10:29:16.996  1928  7331 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 10:29:16.996  1928  7331 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 10:29:16.996  1037  1523 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-16 10:29:16.996  1037  1523 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-16 10:29:16.997  1037  1523 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-16 10:29:16.997  1037  1523 D WifiNative-wlan0: doBoolean: SCAN
08-16 10:29:16.997  1037  1523 D WifiNative-wlan0: SCAN: returned false
08-16 10:29:16.998  1037  7323 E WifiMonitor: WifiMonitor:p2p0 cnt=41 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 10:29:16.998  1037  7323 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 10:29:16.998  1037  7323 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 10:29:16.998  1037  7323 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-16 10:29:16.998  1037  7323 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 10:29:16.998  1037  7323 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 10:29:16.998  1037  7323 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 10:29:17.001  1037  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=396535  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-16 10:29:17.031  1037  1104 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7339 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
08-16 10:29:17.032  1037  1522 D LGWifiP2pService: DeviceAddress: 
,08-16 10:29:17.032  1037  1522 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-16 10:29:17.033  1037  1522 D WifiNative-p2p0: P2P_FLUSH: returned true
08-16 10:29:17.033  1037  1522 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-16 10:29:17.033  1037  1522 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-16 10:29:17.033  1037  1522 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-16 10:29:17.034  1037  1522 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-16 10:29:17.034  1037  1522 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-16 10:29:17.034  1037  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=396568  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-16 10:29:17.035  1037  1523 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 10:29:17.035  1037  1523 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 10:29:17.035  1928  1928 I WfdStateTracker: handleP2pThisDeviceChanged
08-16 10:29:17.036  1928  1928 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-16 10:29:17.036  1928  1928 D WfdsService: Update P2p Interface State: 3
08-16 10:29:17.037  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 10:29:17.037  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 10:29:17.038  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 10:29:17.038  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 10:29:17.038  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-16 10:29:17.038  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 10:29:17.040  1037  1523 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 10:29:17.040  1037  1523 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 10:29:17.041  1037  1523 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 10:29:17.042  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 10:29:17.042  1037  1037 D WifiServerServiceExt: setSupplicantStateSCANNING
08-16 10:29:17.055  1037  1522 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-16 10:29:17.055  1037  1522 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-16 10:29:17.055  1037  1522 D LGWifiP2pService: InactiveState
,08-16 10:29:17.056  1037  1522 D LGWifiP2pService: InactiveState{ when=-63ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
,08-16 10:29:17.056  1037  1522 D LGWifiP2pService: P2pEnabledState{ when=-63ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-16 10:29:17.056  1037  1522 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-16 10:29:17.056  7302  7302 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-16 10:29:17.057  7302  7302 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 10:29:17.057  1037  7323 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-16 10:29:17.057  1037  7323 E WifiMonitor: WifiMonitor:p2p0 cnt=43 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 10:29:17.057  1037  7323 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 10:29:17.057  1037  7323 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 10:29:17.057  7302  7302 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-16 10:29:17.057  7302  7302 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 10:29:17.058  1037  7323 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 10:29:17.058  1037  7323 E WifiMonitor: WifiMonitor:p2p0 cnt=44 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 10:29:17.058  1037  7323 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 10:29:17.058  1037  7323 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 10:29:17.058  7302  7302 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 10:29:17.059  1037  7323 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 10:29:17.059  1037  7323 E WifiMonitor: WifiMonitor:p2p0 cnt=45 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 10:29:17.059  1037  7323 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 10:29:17.059  1928  7331 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-16 10:29:17.059  1037  7323 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 10:29:17.059  1928  7331 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 10:29:17.059  1928  7331 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 10:29:17.059  1037  1522 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-16 10:29:17.059  1037  1522 D LGWifiP2pService: InactiveState{ when=-26ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-16 10:29:17.059  1037  1522 D LGWifiP2pService: P2pEnabledState{ when=-26ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-16 10:29:17.059  1037  1522 D LGWifiP2pService: InactiveState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-16 10:29:17.060  1037  1522 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-16 10:29:17.060  1037  1522 D LGWifiP2pService: DefaultState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-16 10:29:17.060  1037  1522 D LGWifiP2pService: InactiveState{ when=-4ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-16 10:29:17.060  1037  1522 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-16 10:29:17.060  1037  1522 D LGWifiP2pService: DefaultState{ when=-4ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-16 10:29:17.060  1037  1522 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-16 10:29:17.060  1037  1522 D LGWifiP2pService: P2pEnabledState{ when=-1ms wha,t=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-16 10:29:17.060  1037  1522 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-16 10:29:17.062  1037  1522 D LGWifiP2pService: InactiveState{ when=-3ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-16 10:29:17.062  1037  1522 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-16 10:29:17.062  1037  1522 D LGWifiP2pService: DefaultState{ when=-3ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-16 10:29:17.063  1037  1037 E WifiServerServiceExt: No p2p device connected
08-16 10:29:17.063  1928  2293 W WfdsService: DefaultState - msg [9441285] is not handled
,08-16 10:29:17.132  7339  7339 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-16 10:29:17.132  7339  7339 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-16 10:29:17.141  7339  7339 V [BNRBootReceiver]: Boot Receiver Return
08-16 10:29:17.144  7339  7339 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-16 10:29:17.144  3722  3722 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 10:29:17.157  6279  6279 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 10:29:17.161  6279  6279 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-16 10:29:17.171  6350  6350 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 10:29:17.172  6350  6350 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 10:29:17.175  6350  6350 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-16 10:29:17.179  1037  1901 I ActivityManager: Killing 6669:com.lge.appbox.client/u0a11 (adj 15): empty #17
,08-16 10:29:17.212  1037  1981 W libprocessgroup: failed to open /acct/uid_10011/pid_6669/cgroup.procs: No such file or directory
,08-16 10:29:17.576  7302  7302 E wpa_supplicant: USIM:  scard_init function
,08-16 10:29:17.578  7302  7302 I wpa_supplicant: Trying to associate with SSID 'NG700'
,08-16 10:29:17.589  1037  7323 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-16 10:29:17.589  1037  7323 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-16 10:29:17.590  1037  7323 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-16 10:29:17.590  1037  7323 E WifiMonitor: WifiMonitor:wlan0 cnt=47 dispatchEvent: WPS-AP-AVAILABLE 
08-16 10:29:17.590  1037  7323 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-16 10:29:17.590  1037  7323 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-16 10:29:17.590  1037  7323 E WifiMonitor: WifiMonitor:wlan0 cnt=48 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
,08-16 10:29:17.593  1037  1523 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=5 bcn=0
08-16 10:29:17.595  1037  1523 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=5 bcn=0
,08-16 10:29:17.600  1037  1523 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=5 bcn=0
08-16 10:29:17.601  1037  1523 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=5 bcn=0
08-16 10:29:17.601  1037  1523 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-16 10:29:17.618  1037  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 48 0 rt=397152  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-16 10:29:17.626  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 10:29:17.626  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 10:29:17.629  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 10:29:17.629  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 10:29:17.629  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-16 10:29:17.631  1037  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 48 0 rt=397165  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-16 10:29:17.635  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 10:29:17.643  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 10:29:17.643  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 10:29:17.643  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,08-16 10:29:17.645  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 10:29:17.645  1037  1037 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-16 10:29:17.651  6279  6279 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-16 10:29:17.657  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 10:29:17.658  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-16 10:29:17.662  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 10:29:17.667  6279  6279 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-16 10:29:17.671  3722  3722 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 10:29:17.685  6279  6279 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 10:29:17.694  6279  6279 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 10:29:17.701  6350  6350 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 10:29:17.702  6350  6350 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 10:29:17.706  6350  6350 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-16 10:29:17.711  7302  7302 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-16 10:29:17.716  1037  7323 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-16 10:29:17.716  1037  7323 E WifiMonitor: WifiMonitor:wlan0 cnt=49 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-16 10:29:17.716  1037  7323 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-16 10:29:17.716  1037  7323 E WifiMonitor: WifiMonitor:wlan0 cnt=50 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-16 10:29:17.716  1037  7323 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 10:29:17.716  1037  7323 E WifiMonitor: WifiMonitor:wlan0 cnt=51 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,08-16 10:29:17.720  7302  7302 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 10:29:17.720  7302  7302 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-16 10:29:17.725  1037  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 49 0 rt=397259  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-16 10:29:17.725  1037  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 49 0 rt=397260  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-16 10:29:17.726  1037  1523 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 50 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=397260
08-16 10:29:17.726  1037  1523 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 50 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=397261
08-16 10:29:17.726  1037  1523 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 50 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=397261
08-16 10:29:17.727  1037  1523 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 50 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=397261
08-16 10:29:17.730  1037  7323 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 10:29:17.730  1037  7323 E WifiMonitor: WifiMonitor:wlan0 cnt=52 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 10:29:17.730  1037  7323 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-16 10:29:17.730  1037  7323 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 10:29:17.730  1037  7323 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 10:29:17.730  1037  7323 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-16 10:29:17.730  1037  7323 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-16 10:29:17.730  1037  7323 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-16 10:29:17.730  1037  7323 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 10:29:17.730  1037  7323 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,08-16 10:29:17.738  1037  1119 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-16 10:29:17.747  1037  1523 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 50 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=397282
08-16 10:29:17.748  1037  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 51 0 rt=397282  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-16 10:29:17.751  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 10:29:17.751  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 10:29:17.751  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-16 10:29:17.753  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 10:29:17.753  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 10:29:17.755  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 10:29:17.762  3722  3722 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 10:29:17.772  1037  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 51 0 rt=397306  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
,08-16 10:29:17.779  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 10:29:17.780  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 10:29:17.780  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-16 10:29:17.781  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 10:29:17.781  1037  1037 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-16 10:29:17.782  1037  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 52 0 rt=397316  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
,08-16 10:29:17.783  1037  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 52 0 rt=397318  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-16 10:29:17.785  1037  1523 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=397319
08-16 10:29:17.787  1037  1523 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=397322
08-16 10:29:17.789  1037  1523 D WifiNative-wlan0: doString: [STATUS]
08-16 10:29:17.790  1037  7323 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
,08-16 10:29:17.790  1037  7323 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 10:29:17.790  1037  1523 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-16 10:29:17.790  6279  6279 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 10:29:17.794  1037  1523 I WifiServiceExtension: setVHTCapabilityType  : false
08-16 10:29:17.796  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 10:29:17.796  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 10:29:17.796  6279  6279 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 10:29:17.798  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 10:29:17.802  6350  6350 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 10:29:17.803  6350  6350 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 10:29:17.803  6350  6350 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-16 10:29:17.806  6279  6279 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-16 10:29:17.806  6279  6279 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-16 10:29:17.806  6279  6279 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-16 10:29:17.806  1037  1523 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-16 10:29:17.806  6279  6279 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-16 10:29:17.806  1037  1523 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-16 10:29:17.807  6279  6279 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-16 10:29:17.809  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 10:29:17.809  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 10:29:17.809  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-16 10:29:17.814  6279  6279 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-16 10:29:17.814  6279  6279 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-16 10:29:17.814  6279  6279 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-16 10:29:17.814  6279  6279 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-16 10:29:17.814  6279  6279 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-16 10:29:17.814  6279  6279 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-16 10:29:17.814  6279  6279 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-16 10:29:17.815  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 10:29:17.815  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 10:29:17.815  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-16 10:29:17.818  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 10:29:17.819  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 10:29:17.821  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 10:29:17.821  3722  3722 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 10:29:17.822  1037  1523 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-16 10:29:17.822  1037  1523 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 10:29:17.822  1037  1523 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-16 10:29:17.823  1037  1530 D ConnectivityService: Got NetworkAgent Messenger
08-16 10:29:17.823  1037  1530 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-16 10:29:17.823  1037  1530 D ConnectivityService: NetworkAgent connected
08-16 10:29:17.823  1037  1523 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-16 10:29:17.823  1037  1523 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-16 10:29:17.824  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 10:29:17.824  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 10:29:17.825  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 10:29:17.828  6279  6279 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 10:29:17.836  6279  6279 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 10:29:17.843  6350  6350 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-16 10:29:17.843  1037  1523 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-16 10:29:17.843  1037  1523 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 10:29:17.843  6350  6350 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 10:29:17.843  1037  1523 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-16 10:29:17.844  6350  6350 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 10:29:17.844  1037  1523 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-16 10:29:17.844  1037  1523 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-16 10:29:17.850  3722  3722 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 10:29:17.851  1037  1523 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-16 10:29:17.852   305   906 D CommandListener: Setting iface cfg
08-16 10:29:17.861  6279  6279 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 10:29:17.862  1037  7385 D DhcpStateMachine: StoppedState
08-16 10:29:17.862  1037  1523 E WifiStateMachine: Start Dhcp Watchdog 2
08-16 10:29:17.862  1037  7385 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-16 10:29:17.862  1037  7385 D DhcpStateMachine: WaitBeforeStartState
08-16 10:29:17.864  1037  1523 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=397398  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 10:29:17.866  1037  1523 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=397400  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 10:29:17.867  1037  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=397401  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 10:29:17.868  1037  1523 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-16 10:29:17.868  1037  1523 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-16 10:29:17.869  1037  1523 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-16 10:29:17.870  1037  1523 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-16 10:29:17.871  1037  1523 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-16 10:29:17.871  1037  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 10:29:17.872  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 10:29:17.872  1037  1037 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
,08-16 10:29:17.874  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 10:29:17.874  1037  1037 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-16 10:29:17.875  6279  6279 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 10:29:17.875  1037  1523 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=397409  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 10:29:17.876  1037  1523 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=397410  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 10:29:17.877  1037  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=397411  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 10:29:17.879  1037  1523 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:23459] from screen [on:0 period:-1837624649] gl rssi=-56 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 10:29:17.879  6350  6350 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 10:29:17.879  6350  6350 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 10:29:17.880  6350  6350 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 10:29:17.880  1037  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1837624648] gl rssi=-56 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 10:29:17.881  1037  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-16 10:29:17.882  3722  3722 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 10:29:17.886  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 10:29:17.887  1037  1530 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-16 10:29:17.887  6279  6279 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 10:29:17.888  1037  1523 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 10:29:17.889  1037  1523 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 10:29:17.889  1037  1523 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 10:29:17.890  1037  1523 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 10:29:17.890  1037  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 10:29:17.891  1037  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 10:29:17.892  1037  1530 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-16 10:29:17.892  1037  1523 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=14,0,0
08-16 10:29:17.893  6279  6279 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 10:29:17.893  1037  1523 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=14,0,0
08-16 10:29:17.893  1037  1523 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-16 10:29:17.893  7302  7302 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-16 10:29:17.893  1037  1523 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-16 10:29:17.894  1037  1523 D WifiNative-wlan0: doBoolean: SET ps 0
08-16 10:29:17.894  1037  1523 D WifiNative-wlan0: SET ps 0: returned true
08-16 10:29:17.894  1037  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-16 10:29:17.894  7302  7302 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-16 10:29:17.894  1037  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-16 10:29:17.894  1037  1523 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-16 10:29:17.894  1037  1523 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-16 10:29:17.894  1037  1522 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2cea74df target=com.android.internal.util.StateMachine$SmHandler }
08-16 10:29:17.894  1037  1522 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2cea74df target=com.android.internal.util.StateMachine$SmHandler }
08-16 10:29:17.894  1037  7385 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-16 10:29:17.894  1037  7385 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-16 10:29:17.894  1037  1523 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-16 10:29:17.896   305   906 D CommandListener: Setting iface cfg
08-16 10:29:17.896   305   906 D CommandListener: Trying to bring up wlan0
08-16 10:29:17.897  1037  1523 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-16 10:29:17.900  1037  1523 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
,08-16 10:29:17.900  1037  1523 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 10:29:17.901  1037  1523 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 10:29:17.901  1037  1523 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 10:29:17.901  1037  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 10:29:17.902  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 10:29:17.902  1037  1037 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-16 10:29:17.902  1037  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 10:29:17.903  1037  1530 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-16 10:29:17.903  1037  1523 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-16 10:29:17.904  6350  6350 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 10:29:17.904  6350  6350 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 10:29:17.904  1037  1523 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-16 10:29:17.904  1037  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-16 10:29:17.904  1037  1522 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 10:29:17.904  1037  1522 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 10:29:17.904  7302  7302 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
,08-16 10:29:17.904  6350  6350 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 10:29:17.905  1037  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-16 10:29:17.905  1037  1523 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-16 10:29:17.905  7302  7302 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-16 10:29:17.905  1037  1523 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-16 10:29:17.905  1037  1523 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 10:29:17.908  3722  3722 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 10:29:17.913  6279  6279 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 10:29:17.919  6279  6279 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 10:29:17.922  1037  1523 D WifiNative-wlan0: SET ps 1: returned true
08-16 10:29:17.923  1037  1530 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-16 10:29:17.923  1037  1523 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-16 10:29:17.924  1037  1523 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-16 10:29:17.924  1037  1523 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-16 10:29:17.925  1037  1530 D ConnectivityService: ignoring duplicate network state non-change
08-16 10:29:17.928  6149  6212 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 10:29:17.928  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 10:29:17.928  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 10:29:17.928  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 10:29:17.928  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 10:29:17.928  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 10:29:17.928  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 10:29:17.928  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 10:29:17.929  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 10:29:17.929  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 10:29:17.929  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-16 10:29:17.930  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 10:29:17.930  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 10:29:17.931  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 10:29:17.931  6149  6212 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 10:29:17.932  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:29:17.932  6149  6212 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f0d44c1 removed from the list
08-16 10:29:17.932  6149  6212 D io.jxcore.node.ConnectivityMonitor: stop
08-16 10:29:17.932  6149  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:29:17.932  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:29:17.933  1037  1530 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-16 10:29:17.934  1037  1530 D ConnectivityService: Adding iface wlan0 to network 101
08-16 10:29:17.936  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 10:29:17.936  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 10:29:17.936  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-16 10:29:17.937  1037  1037 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-16 10:29:17.938  1037  1523 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-16 10:29:17.939  1928  1928 V WfdStateTracker: handleWifiStateChangedEvent: 1
,08-16 10:29:17.941  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 10:29:17.941  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 10:29:17.941  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-16 10:29:17.942  1037  1037 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-16 10:29:17.948  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 10:29:17.948  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 10:29:17.948  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-16 10:29:17.952  6350  6350 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-16 10:29:17.952  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 10:29:17.952  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 10:29:17.952  6350  6350 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 10:29:17.953  6350  6350 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 10:29:17.955  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 10:29:17.958  3722  3722 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 10:29:17.958  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 10:29:17.958  1588  1588 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 2
08-16 10:29:17.958  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 10:29:17.961  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 10:29:17.961  1588  1588 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 2
08-16 10:29:17.961  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 10:29:17.964  1037  1530 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-16 10:29:17.964  1037  1530 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-16 10:29:17.965  1037  1530 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-16 10:29:17.965  6279  6279 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 10:29:17.966   305   906 E Netd    : netlink response contains error (File exists)
,08-16 10:29:17.967  1037  1530 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-16 10:29:17.969  1037  1530 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-16 10:29:17.969  1037  1530 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-16 10:29:17.969  1037  1530 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-16 10:29:17.973  6279  6279 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 10:29:17.974  1037  1530 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-16 10:29:17.974  1037  1530 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-16 10:29:17.974  1037  1530 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-16 10:29:17.974  1037  1530 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-16 10:29:17.974  1037  7384 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-16 10:29:17.974  1037  7384 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-16 10:29:17.974  1037  7384 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-16 10:29:17.974  1037  1530 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 10:29:17.974  1037  7384 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-16 10:29:17.974  1037  1530 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 10:29:17.974  1037  1530 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-16 10:29:17.974  1037  1530 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 10:29:17.974  1037  1530 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-16 10:29:17.974  1037  1530 D ConnectivityService: currentScore = 0, newScore = 20
08-16 10:29:17.974  1037  1530 D ConnectivityService:    accepting network in place of null
08-16 10:29:17.974  1037  1530 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 10:29:17.975   305  7390 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-16 10:29:17.976  1037  1523 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 10:29:17.976  1838  1838 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 10:29:17.976  1037  1523 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 10:29:17.976  1838  1838 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-16 10:29:17.977  1037  1530 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 ,-> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-16 10:29:17.977  1037  1530 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-16 10:29:17.977  1037  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-16 10:29:17.978  1037  1530 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-16 10:29:17.978  1037  1530 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-16 10:29:17.979  1037  1530 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-16 10:29:17.980  1037  1530 D ConnectivityService: validation of new default Network = false
08-16 10:29:17.980  1037  1530 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-16 10:29:17.980  1037  1530 D DSQN    : enableDataServiceNotify 
08-16 10:29:17.980  1037  1530 D DSQN    : start dsqn bin
08-16 10:29:17.980  1037  1037 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-16 10:29:17.980  1037  1037 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-16 10:29:17.980  1037  1037 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-16 10:29:17.980  1037  1037 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-16 10:29:17.987  1037  1530 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-16 10:29:17.987  1037  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 10:29:17.987  1037  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 10:29:17.988  1037  1530 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 10:29:17.988  1588  1830 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-16 10:29:17.982  7391  7391 W dsqn    : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 10:29:17.982  7391  7391 W dsqn    : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-16 10:29:17.992  6350  6350 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 10:29:17.993  6350  6350 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 10:29:17.993  6350  6350 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 10:29:17.998  3722  3722 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 10:29:17.999  7391  7391 E DSQN    : DSQN ssw
08-16 10:29:18.005  6279  6279 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 10:29:18.011  1037  1521 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,08-16 10:29:18.012  6279  6279 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 10:29:18.021  6350  6350 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 10:29:18.021  6350  6350 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 10:29:18.021  6350  6350 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-16 10:29:18.029  1802  7395 I CheckinService: active receiver: enabled
08-16 10:29:18.029  3722  3722 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 10:29:18.038  1802  7395 I CheckinService: Preparing to send checkin request
08-16 10:29:18.038  1802  7395 I EventLogService: Accumulating logs since 1471335801753
08-16 10:29:18.039  6296  6296 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-16 10:29:18.039  6296  6296 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-16 10:29:18.041   305  7390 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-16 10:29:18.042  6279  6279 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 10:29:18.043  1588  1588 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 10:29:18.044  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 10:29:18.045  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 10:29:18.046  6279  6279 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 10:29:18.053  6350  6350 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 10:29:18.053  6350  6350 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 10:29:18.054  6350  6350 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,08-16 10:29:18.054  6350  6350 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-16 10:29:18.055  6350  6350 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-16 10:29:18.059  3722  3722 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 10:29:18.061  6296  6296 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-16 10:29:18.061  6296  6296 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-16 10:29:18.063  6279  6279 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 10:29:18.067  6279  6279 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-16 10:29:18.071  6350  6350 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 10:29:18.072  6350  6350 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 10:29:18.072  6350  6350 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-16 10:29:18.073  6350  6350 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-16 10:29:18.073  6350  6350 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-16 10:29:18.074   305  7390 D libc-netbsd: res_queryN name = clients3.google.com succeed
08-16 10:29:18.083  1802  7395 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-16 10:29:18.088  1037  1529 D WifiService: New client listening to asynchronous messages
,08-16 10:29:18.096  1037  7385 D DhcpStateMachine: DHCPV4 request on wlan0
08-16 10:29:18.097  1037  7385 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-16 10:29:18.097  1037  7385 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
,08-16 10:29:18.092  7398  7398 W dhcpcd  : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 10:29:18.092  7398  7398 W dhcpcd  : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 10:29:18.106   305   905 D LGDataListener: argv[0]=dsqncommand
08-16 10:29:18.106   305   905 D LGDataListener: argv[1]=wlan0
08-16 10:29:18.106   305   905 D LGDataListener: argv[2]=1
08-16 10:29:18.106   305   905 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-16 10:29:18.106  1037  1117 D DSQN    : DSQM DsqnNotification wlan0  1
08-16 10:29:18.106  1037  1117 D DSQN    : start to monitor internet connection
08-16 10:29:18.108  7398  7398 I dhcpcd  : version 5.5.6 starting
,08-16 10:29:18.111  7398  7398 E dhcpcd  : get_duid: m
08-16 10:29:18.111  7398  7398 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-16 10:29:18.111  7398  7398 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-16 10:29:18.138  1037  7384 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 16 Aug 2016 08:29:18 GMT], X-Android-Received-Millis=[1471336158137], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1471336158104]}
08-16 10:29:18.138  1037  7384 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-16 10:29:18.138  1037  7384 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
,08-16 10:29:18.138  1037  1530 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-16 10:29:18.138  1037  1530 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-16 10:29:18.139  1037  1530 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 10:29:18.139  1037  1530 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 10:29:18.139  1037  1530 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-16 10:29:18.139  1037  1530 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-16 10:29:18.139  1037  1530 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-16 10:29:18.139  1037  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 10:29:18.139  1037  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 10:29:18.140  1037  1530 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 10:29:18.140  1037  1530 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 10:29:18.140  1037  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-16 10:29:18.140  1838  1838 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 10:29:18.141  1838  1838 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-16 10:29:18.141  1037  1523 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 10:29:18.141  1037  1523 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 10:29:18.141  1588  1830 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-16 10:29:18.162  1588  1588 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 10:29:18.163  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 10:29:18.164  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 10:29:18.166  7398  7398 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-16 10:29:18.166  7398  7398 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-16 10:29:18.166  7398  7398 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-16 10:29:18.166  7398  7398 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
,08-16 10:29:18.167  7398  7398 D dhcpcd  : wlan0: sending REQUEST (xid 0x9c0cb1ab), next in 4.58 seconds
,08-16 10:29:18.187  7398  7398 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,08-16 10:29:18.195  7398  7398 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
08-16 10:29:18.195  7398  7398 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
08-16 10:29:18.196  7398  7398 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-16 10:29:18.196  7398  7398 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-16 10:29:18.196  7398  7398 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-16 10:29:18.196  7398  7398 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-16 10:29:18.196  7398  7398 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-16 10:29:18.196  7398  7398 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-16 10:29:18.245  1037  1999 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7410 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-16 10:29:18.267   363   363 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 493us total 22.611ms
,08-16 10:29:18.288   363   363 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 660us total 19.199ms
08-16 10:29:18.310   363   363 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 768us total 21.498ms
08-16 10:29:18.310  7410  7410 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-16 10:29:18.310  7410  7410 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-16 10:29:18.338  7410  7410 I MultiDex: VM with version 2.1.0 has multidex support
08-16 10:29:18.338  7410  7410 I MultiDex: install
08-16 10:29:18.338  7410  7410 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-16 10:29:18.345  7410  7410 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
08-16 10:29:18.350  2179  2179 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,08-16 10:29:18.362  2179  2179 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-16 10:29:18.362  2179  2179 D c       : Getting all permits...
08-16 10:29:18.362  2179  2179 D a       : Opening database...
08-16 10:29:18.368  2179  2179 D a       : Opening database auth.proximity.permit_store...
08-16 10:29:18.369  2179  2179 D a       : Closing database...
08-16 10:29:18.501  1037  7385 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-16 10:29:18.504  1037  7385 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-16 10:29:18.504  1037  7385 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-16 10:29:18.504  1037  7385 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
08-16 10:29:18.505  1037  7385 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-16 10:29:18.505  1037  7385 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-16 10:29:18.505  1037  7385 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-16 10:29:18.505  1037  7385 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-16 10:29:18.506  1037  7385 D DhcpStateMachine: RunningState
08-16 10:29:18.743  7410  7428 D LgDataFeature: LgDataFeature() Constructor: none
08-16 10:29:18.744  7410  7428 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 10:29:19.010  7453  7453 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-16 10:29:19.080  7453  7453 I dex2oat : dex2oat took 69.438ms (threads: 4)
,08-16 10:29:19.084  1037  1104 W ProcessCpuTracker: Skipping unknown process pid 7453
08-16 10:29:19.095  7410  7428 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 10:29:19.095  7410  7428 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 10:29:19.095  7410  7428 I Adreno-EGL: Build Date: 12/12/14 금
08-16 10:29:19.095  7410  7428 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 10:29:19.095  7410  7428 I Adreno-EGL: Remote Branch: 
08-16 10:29:19.095  7410  7428 I Adreno-EGL: Local Patches: 
08-16 10:29:19.095  7410  7428 I Adreno-EGL: Reconstruct Branch: 
,08-16 10:29:19.403  1037  1523 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 10:29:19.404  1037  1523 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 10:29:19.404  1037  1523 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 10:29:19.404  1037  1523 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-16 10:29:19.404  1037  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 10:29:19.405  1037  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 10:29:19.407  1037  1530 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
08-16 10:29:19.407  1037  1530 D ConnectivityService: identical MTU - not setting
08-16 10:29:19.407  1037  1530 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-16 10:29:19.407  1037  1530 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-16 10:29:19.407  1037  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 10:29:19.407  1037  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 10:29:19.408  1037  1530 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 10:29:19.408  1588  1830 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-16 10:29:19.413  7410  7428 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 10:29:19.413  7410  7428 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 10:29:19.413  7410  7428 I Adreno-EGL: Build Date: 12/12/14 금
08-16 10:29:19.413  7410  7428 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 10:29:19.413  7410  7428 I Adreno-EGL: Remote Branch: 
08-16 10:29:19.413  7410  7428 I Adreno-EGL: Local Patches: 
08-16 10:29:19.413  7410  7428 I Adreno-EGL: Reconstruct Branch: 
08-16 10:29:19.462  7410  7428 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 10:29:19.462  7410  7428 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 10:29:19.462  7410  7428 I Adreno-EGL: Build Date: 12/12/14 금
08-16 10:29:19.462  7410  7428 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 10:29:19.462  7410  7428 I Adreno-EGL: Remote Branch: 
08-16 10:29:19.462  7410  7428 I Adreno-EGL: Local Patches: 
08-16 10:29:19.462  7410  7428 I Adreno-EGL: Reconstruct Branch: 
,08-16 10:29:19.568   305  7461 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-16 10:29:19.568   305  7461 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
,08-16 10:29:19.603   305  7461 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,08-16 10:29:19.872  1802  7395 I CheckinTask: Sending checkin request (7953 bytes)
,08-16 10:29:20.175  1802  7395 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,08-16 10:29:20.186  1802  7395 I CheckinService: active receiver: disabled
,08-16 10:29:20.218  2179  2179 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-16 10:29:20.235  2179  2179 I GCM     : GCM config loaded
,08-16 10:29:20.256   305  7468 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-16 10:29:20.258   305  7468 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
,08-16 10:29:20.265  6716  6716 V SetupWizard: Connected to Gservices successfully
08-16 10:29:20.292   305  7468 D libc-netbsd: res_queryN name = mtalk.google.com succeed
,08-16 10:29:20.431  2179  7466 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-16 10:29:20.603  2179  7471 D GCM     : Connected
,08-16 10:29:20.645  2179  7471 D GCM     : Message class com.google.e.a.a.q
,08-16 10:29:20.891  1037  1523 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=7.0, 0.0, 0.0  rx=5.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1837621638] gl rssi=-56 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-16 10:29:20.893  1037  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=7.0, 0.0, 0.0  rx=5.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1837621635] gl rssi=-56 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 10:29:20.894  1037  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-16 10:29:20.909  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 10:29:20.939  1037  1524 V WifiInternetCheck: Single check msg out of sync, ignoring.
,08-16 10:29:20.980  1037  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 10:29:20.997  1037  1119 D Tethering: MasterInitialState.processMessage what=3
08-16 10:29:21.002  1037  1812 D AlarmManagerService: Setting time of day to sec=1471336161
,08-16 10:29:21.420  1037  1812 W AlarmManagerService: Unable to set rtc to 1471336161: Invalid argument
08-16 10:29:21.436  6149  6149 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 10:29:21.436  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 10:29:21.436  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 10:29:21.436  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 10:29:21.436  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 10:29:21.436  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 10:29:21.436  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 10:29:21.436  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 10:29:21.440  6149  6149 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 10:29:21.445  6149  6149 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 10:29:21.445  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 10:29:21.445  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 10:29:21.445  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 10:29:21.445  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 10:29:21.445  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 10:29:21.445  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 10:29:21.445  6149  6149 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 10:29:21.446  6149  6149 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 10:29:21.448  1037  1102 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-16 10:29:21.473  1588  1588 D KeyguardUpdateMonitor: handleTimeUpdate
,08-16 10:29:21.477  1928  1928 I SecureClockService: Intent.ACTION_TIME_CHANGED 
08-16 10:29:21.477  1588  1588 I [SystemUI]Clock: onReceive = android.intent.action.TIME_SET
08-16 10:29:21.483  3683  3683 D LIA_Informant_Tips_DateChangeManager: onReceive() : ACTION_TIME_CHANGED
08-16 10:29:21.484  3683  3683 I LIA_Informant_Tips_LogTracer: [Log Tracer - Schedule Transition] Time Change Event Received : 2016-08-16 10:29:21...... Request
08-16 10:29:21.484  3683  3683 I LIA_Informant_Tips_LogTracer: [Log Tracer - Schedule Transition] UserGuide, DATE_UPDATE : working count : 5, total count : 57, new day : false...... Request
08-16 10:29:21.484  3683  3683 D LIA_Informant_Tips_DateChangeManager: DateInfo : SmartTips Total Working Day Count = 57
08-16 10:29:21.484  3683  3683 D LIA_Informant_Tips_DateChangeManager: DateInfo : UserGuide Working Duration Count = 5
08-16 10:29:21.485  3683  3683 D LIA_Informant_Tips_DateChangeManager: DateInfo : Last Date Check Time = 2016-08-16 10:29:21
08-16 10:29:21.487  3722  3722 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-16 10:29:21.492  3722  6270 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-16 10:29:21.497  1588  1588 I LgeClockWidgetControlView: time changed, timezoneChanged : false
08-16 10:29:21.510  1037  1981 W ActivityManager: getTasks: caller 10029 is using old GET_TASKS but privileged; allowing
,08-16 10:29:21.514  2019  2019 I [LGHome]LGDateChangeReceiver: [LGDateChangeReceiver.java:78:updateCalendarShortcut()]date=16 currentDate=-1 dayofweek=3 currentDayOfWeek=-1
08-16 10:29:21.516  2019  2019 I [LGHome]LGCalendarIcon: [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Tue date= 16
08-16 10:29:21.521  2019  2019 I [LGHome]LGCalendarIcon: [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Tue date= 16
08-16 10:29:21.521  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 10:29:21.542  2597  2597 D [Concierge]Service: onStartCommand(). Type : 9
,08-16 10:29:21.585  5330  5330 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,08-16 10:29:21.593  1037  1102 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 10:29:21.606  2179  2179 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-16 10:29:21.632  1037  1981 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10005
,08-16 10:29:21.632  1037  7384 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-16 10:29:21.632  1037  7384 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-16 10:29:21.632  1037  7384 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-16 10:29:21.633  1037  7384 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-16 10:29:21.633  1037  7384 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-16 10:29:21.670  1037  7384 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 16 Aug 2016 08:29:21 GMT], X-Android-Received-Millis=[1471336161668], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1471336161636]}
08-16 10:29:21.670  1037  7384 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-16 10:29:21.670  1037  7384 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-16 10:29:21.671  1037  1530 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-16 10:29:21.671  1037  1530 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-16 10:29:21.671  1037  1530 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 10:29:21.671  1037  1530 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 10:29:21.671  1037  1530 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-16 10:29:21.672  1037  1530 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-16 10:29:21.672  1037  1530 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-16 10:29:21.672  1037  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 10:29:21.672  1037  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 10:29:21.673  1037  1530 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 10:29:21.674  1588  1830 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-16 10:29:21.686  1037  1739 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7488 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-16 10:29:21.786  7488  7488 I AppUp4:AppBoxCP: onCreate
08-16 10:29:21.787  7488  7488 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,08-16 10:29:21.798  7488  7488 I AppUp4:DB:  setFingerPrint start
,08-16 10:29:21.798  7488  7488 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-16 10:29:21.808  7488  7488 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-16 10:29:21.808  7488  7488 I AppUp4:DB:  SDK version = 21
08-16 10:29:21.808  7488  7488 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-16 10:29:21.810  7488  7488 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-16 10:29:21.812  7488  7488 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-16 10:29:21.812  7488  7488 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,08-16 10:29:21.814  7488  7488 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-16 10:29:21.815  7488  7488 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-16 10:29:21.822  7488  7488 I AppUp4:CustModeStarterReceiver: onReceive
08-16 10:29:21.864  7488  7488 D LgDataFeature: LgDataFeature() Constructor: none
08-16 10:29:21.864  7488  7488 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 10:29:21.874  7488  7488 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@23822140
08-16 10:29:21.874  7488  7488 D AppUp4:CustFacade: isCustomizationCompleted : false
08-16 10:29:21.874  7488  7488 D AppUp4:CustFacade: isPhone : true
08-16 10:29:21.875  7488  7488 D AppUp4:CustModeStarterReceiver: begin check event
08-16 10:29:21.875  7488  7488 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-16 10:29:21.875  7488  7488 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-16 10:29:21.876  7488  7507 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-16 10:29:21.876  7488  7507 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-16 10:29:21.877  7488  7507 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-16 10:29:21.881  1037  1927 I ActivityManager: Killing 6690:com.lge.email/u0a23 (adj 15): empty #17
,08-16 10:29:21.996  4259  4259 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,08-16 10:29:21.997  1037  1901 W libprocessgroup: failed to open /acct/uid_10023/pid_6690/cgroup.procs: No such file or directory
,08-16 10:29:21.999  4259  4259 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 10:29:22.004  4259  4259 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-16 10:29:22.015  4259  4259 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-16 10:29:22.035  2814  2814 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,08-16 10:29:22.059  2814  2814 V DownloadManager: DownloadService onCreate
,08-16 10:29:22.093  1037  1703 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7520 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-16 10:29:22.152  2814  7518 I DownloadManager: in removeSpuriousFiles
08-16 10:29:22.153  2814  7518 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,08-16 10:29:22.158  2814  7518 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@37ab6f1e on behalf of 2814
08-16 10:29:22.162  2814  7518 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
08-16 10:29:22.162  2814  7518 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
08-16 10:29:22.162  2814  7518 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
08-16 10:29:22.162  2814  7518 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
08-16 10:29:22.162  2814  7518 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
08-16 10:29:22.162  2814  7518 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
08-16 10:29:22.162  2814  7518 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
08-16 10:29:22.162  2814  7518 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
08-16 10:29:22.163  2814  7518 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
08-16 10:29:22.163  2814  7518 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
08-16 10:29:22.163  2814  7518 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
08-16 10:29:22.164  4259  7537 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-16 10:29:22.165  2814  7518 I DownloadManager: in trimDatabase
08-16 10:29:22.165  2814  7518 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,08-16 10:29:22.178  4259  7539 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,08-16 10:29:22.183  2814  7518 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@3f0da3ff on behalf of 2814
08-16 10:29:22.188  4259  7537 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
08-16 10:29:22.190  4259  7539 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-16 10:29:22.191  2814  2814 V DownloadManager: DownloadService onStartCommand
08-16 10:29:22.192  2814  7519 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
08-16 10:29:22.194  7520  7520 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 10:29:22.194  7520  7520 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-16 10:29:22.199  2814  7519 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@139b5f2a on behalf of 2814
08-16 10:29:22.201  2814  7519 V DownloadManager: processing inserted download 1
08-16 10:29:22.202  2814  7519 V DownloadManager: processing inserted download 4
08-16 10:29:22.202  4259  7537 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
08-16 10:29:22.203  2814  7519 V DownloadManager: processing inserted download 7
08-16 10:29:22.204  2814  7519 V DownloadManager: processing inserted download 8
08-16 10:29:22.205  4259  4259 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
08-16 10:29:22.205  4259  4259 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
08-16 10:29:22.205  4259  4259 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
08-16 10:29:22.205  2814  7519 V DownloadManager: processing inserted download 9
08-16 10:29:22.206  4259  4259 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
08-16 10:29:22.206  2814  7519 V DownloadManager: processing inserted download 10
08-16 10:29:22.208  2814  7519 V DownloadManager: processing inserted download 11
08-16 10:29:22.209  7520  7520 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-16 10:29:22.209  7520  7520 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-16 10:29:22.209  2814  7519 V DownloadManager: processing inserted download 12
,08-16 10:29:22.214  4259  4259 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
08-16 10:29:22.214  2814  7519 V DownloadManager: processing inserted download 13
08-16 10:29:22.215  2814  7519 V DownloadManager: processing inserted download 14
08-16 10:29:22.216  2814  7519 V DownloadManager: processing inserted download 16
08-16 10:29:22.220  2814  2814 V DownloadManager: DownloadService onDestroy
08-16 10:29:22.284  7520  7520 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-16 10:29:22.294  7520  7520 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
08-16 10:29:22.339  7520  7520 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-16 10:29:22.377  7520  7520 D LgDataFeature: LgDataFeature() Constructor: none
,08-16 10:29:22.378  7520  7520 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 10:29:22.552  7520  7520 D eas_req : ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-16 10:29:22.570   305  7567 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-16 10:29:22.571   305  7567 D libc-netbsd: res_queryN name = www.google.com, class = 1, type = 1
08-16 10:29:22.603   305  7567 D libc-netbsd: res_queryN name = www.google.com succeed
,08-16 10:29:22.621   305  7569 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-16 10:29:22.622   305  7569 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-16 10:29:22.622   305  7569 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-16 10:29:22.712  1037  1525 V WifiInternetCheck: isHttpConnectionAvailable - We got a valid response : 204
,08-16 10:29:22.728  1037  2000 I art     : Explicit concurrent mark sweep GC freed 76109(3MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 43MB/64MB, paused 2.280ms total 160.408ms
,08-16 10:29:22.746  7520  7520 I HubEmail: JNI_OnLoad()
08-16 10:29:22.746  7520  7520 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-16 10:29:22.746  7520  7520 I HubEmail: registerNatives()
08-16 10:29:22.746  7520  7520 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-16 10:29:22.746  7520  7520 I HubEmail: registerNativeMethods()
08-16 10:29:22.746  7520  7520 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-16 10:29:22.746  7520  7520 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
08-16 10:29:22.763  3369  3369 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-16 10:29:22.763  3369  3369 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-16 10:29:22.763  3369  3369 I LgeMiscReceiver: networkInfo.isConnected() = true
08-16 10:29:22.763  3369  3369 D PhoneState: setPdpRejectCasuse : false
,08-16 10:29:22.770  7520  7574 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 10:29:22.770  6716  6716 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-16 10:29:22.770  6716  6716 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-16 10:29:22.784  6788  6788 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:29:22
,08-16 10:29:22.789  6788  6788 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-16 10:29:22.789  6788  6788 D Weather.Utils: 2 : All the weather widget is gone.
08-16 10:29:22.789  6788  6788 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-16 10:29:22.789  6788  6788 D WeatherAncestor: connectivity changed - connection : true
08-16 10:29:22.790  6788  6788 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@36bc39be
08-16 10:29:22.790  6788  6788 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-16 10:29:22.790  6788  6788 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-16 10:29:22.790  6788  6788 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-16 10:29:22.790  6788  6788 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-16 10:29:22.790  6788  6788 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:29:22
08-16 10:29:22.821  3722  3722 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.TIME_SET'.
,08-16 10:29:22.855   305  7578 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-16 10:29:22.856   305  7578 D libc-netbsd: res_queryN name = static-avc.lglime.com, class = 1, type = 1
,08-16 10:29:22.901  1802  1802 I art     : Explicit concurrent mark sweep GC freed 32358(2MB) AllocSpace objects, 20(339KB) LOS objects, 51% free, 29MB/61MB, paused 1.802ms total 73.847ms
,08-16 10:29:22.907   305  7578 D libc-netbsd: res_queryN name = static-avc.lglime.com succeed
,08-16 10:29:22.949  1037  1999 I ActivityManager: Start proc com.lge.clock for broadcast com.lge.clock/.alarmclock.ALBootInit: pid=7581 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,08-16 10:29:22.960  1802  7580 I CheckinService: active receiver: disabled
,08-16 10:29:22.992  6396  7572 V FormManager: There are no updated forms. The schedule will be deleted.
,08-16 10:29:22.998  6396  7572 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
08-16 10:29:23.031  1037  1963 I ActivityManager: Killing 6973:com.lge.lifetracker/u0a37 (adj 15): empty #17
,08-16 10:29:23.121  1037  2037 W libprocessgroup: failed to open /acct/uid_10037/pid_6973/cgroup.procs: No such file or directory
,08-16 10:29:23.138  7581  7610 D ALBootInit: ====action==>android.intent.action.TIME_SET
,08-16 10:29:23.149  7581  7610 D ALBootInit: Alarm ALBootInit: TIME_SET
,08-16 10:29:23.158  7581  7610 D Alarms  : [setNextAlert] start
,08-16 10:29:23.187  7581  7610 D Alarms  : [setNextAlert] (1)
,08-16 10:29:23.193  7581  7610 D Alarms  :  minTime  = 0
,08-16 10:29:23.198  7581  7610 D Alarms  :  -- OK multi -- 0
08-16 10:29:23.199  7581  7610 E jeny.kim: [setNextAlert] setNextAlert  temp_Alarmlink + 
08-16 10:29:23.200  7581  7610 E jeny.kim: [setNextAlert]setNextAlert temp_AlarmLinkText + 
08-16 10:29:23.226  7581  7610 I CommonUtil: BUILD Country: EU
,08-16 10:29:23.229  7581  7610 D Alarms  : broadcastToWidgetProvider : false
,08-16 10:29:23.235  7581  7610 D Alarms  : Enter formatDayAndTime(final Context context, long timeInMiliSec)
08-16 10:29:23.259  1037  1963 V SettingsProvider: call_put(system:next_alarm_formatted=) for 0 calling package = com.lge.clock
,08-16 10:29:23.268  7581  7581 I DigitalAppWidgetProvider: onReceive: android.intent.action.TIME_SET
08-16 10:29:23.272  7581  7581 V DigitalAppWidgetProvider: cancelAlarmOnQuarterHour android.app.ReceiverRestrictedContext@3c09d879
08-16 10:29:23.276  7581  7581 V DigitalAppWidgetProvider: startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@3c09d879
,08-16 10:29:23.284  7581  7581 D QuickCoverProvider: onReceiver
08-16 10:29:23.300  1543  1543 I indal   : SmartCoverWidgetContext createApplicationContext
,08-16 10:29:23.301  1543  1543 I indal   : SmartCoverWidgetContext createApplicationContext
08-16 10:29:23.330  6788  6788 D WeatherAncestor: 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 10:29:23
08-16 10:29:23.332  6788  6788 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,08-16 10:29:23.332  6788  6788 D Weather.Utils: 2 : All the weather widget is gone.
08-16 10:29:23.333  6788  6788 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-16 10:29:23.340  6788  6788 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@36bc39be
08-16 10:29:23.342  6788  6788 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-16 10:29:23.342  6788  6788 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-16 10:29:23.342  6788  6788 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-16 10:29:23.348  6788  6788 D Weather_cast: 2 : set auto-update time : 8/16 13:29
,08-16 10:29:23.356  6149  7615 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
08-16 10:29:23.356  6149  7615 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-16 10:29:23.361  6788  6788 D WeatherAncestor: 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 10:29:23
,08-16 10:29:23.420  1037  2000 I ActivityManager: Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=7619 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
08-16 10:29:23.421  1037  2000 I ActivityManager: Killing 6376:com.lge.settings.easy/1000 (adj 15): empty #17
,08-16 10:29:23.462  1037  2034 W libprocessgroup: failed to open /acct/uid_1000/pid_6376/cgroup.procs: No such file or directory
,08-16 10:29:23.522  7619  7619 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1471336163522
08-16 10:29:23.522  7619  7619 D         : TimeServiceNative: User Time to be set is 1471336163522
08-16 10:29:23.522  7619  7619 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
08-16 10:29:23.522  7619  7619 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
08-16 10:29:23.522  7619  7619 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1471336163522
08-16 10:29:23.522   408  1036 D QC-time-services: Daemon: Connection accepted:time_genoff
,08-16 10:29:23.523  7619  7619 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
08-16 10:29:23.523   408  7636 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1471336163522
08-16 10:29:23.523   408  7636 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1471336163522, operation = 0
08-16 10:29:23.523   408  7636 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS1/26/70 2:56:58
08-16 10:29:23.523   408  7636 D QC-time-services: Daemon:Value read from RTC seconds = 4849018000
08-16 10:29:23.523   408  7636 D QC-time-services: Daemon:new time 1471336163522 
08-16 10:29:23.523   408  7636 D QC-time-services: Daemon: delta 1466487145522 genoff 1466487145522 
08-16 10:29:23.523   408  7636 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1466487145522 to memory
08-16 10:29:23.523   408  7636 D QC-time-services: Daemon:Opening File: /data/time/ats_2
08-16 10:29:23.523   408  7636 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,08-16 10:29:23.529   408  7636 D QC-time-services: Updating the TOD offset
08-16 10:29:23.529   408  7636 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1466487145522 to memory
08-16 10:29:23.529   408  7636 D QC-time-services: Daemon:Opening File: /data/time/ats_1
08-16 10:29:23.529   408  7636 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
08-16 10:29:23.533   408  7636 E QC-time-services: Daemon:Update to modem bit set
08-16 10:29:23.533   408  7636 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
08-16 10:29:23.533   408  7636 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1150522345522
08-16 10:29:23.534  7619  7619 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
08-16 10:29:23.536   408  1034 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
08-16 10:29:23.536   408  1036 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
08-16 10:29:23.541  7339  7339 V [BNRBootReceiver]: boot receiver action = android.intent.action.TIME_SET
,08-16 10:29:23.546  7339  7339 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.lge.bnr.service.BNRBootReceiver.setHomeBadgeCount:192 com.lge.bnr.service.BNRBootReceiver.setBadgeStatus:225 
08-16 10:29:23.549  1588  1588 D KeyguardModel: mReceiver, received action: android.intent.action.BADGE_COUNT_UPDATE, sendingUserId:0
08-16 10:29:23.549  1588  1588 D KeyguardModel: ACTION_GENERAL_UPDATE_NOTIFICATION received! package: com.lge.bnr.launcher, class: com.lge.bnr.launcher.BNRLauncherActivity, unread_count: 0
08-16 10:29:23.549  1588  1588 D KeyguardModel: putThirdPartyNotificationIntoList Number: 0 Id: 12 UserId: 0
,08-16 10:29:23.559  7339  7339 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.lge.bnr.service.BNRBootReceiver.setBadgeStatus:230 com.lge.bnr.service.BNRBootReceiver.onReceive:121 
08-16 10:29:23.561  7339  7339 V [BNRBootReceiver]: Boot Receiver Return
08-16 10:29:23.642  1037  1703 I ActivityManager: Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetProvider: pid=7637 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi
08-16 10:29:23.644  1037  1703 I ActivityManager: Killing 6296:com.lge.sync/1000 (adj 15): empty #17
,08-16 10:29:23.695  1037  1945 W libprocessgroup: failed to open /acct/uid_1000/pid_6296/cgroup.procs: No such file or directory
,08-16 10:29:23.738  7637  7637 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-16 10:29:23.777  7637  7637 D CalendarApplication: CalendarApplication.onCreate()
,08-16 10:29:23.794  7637  7637 D PreferenceKeysParser: [debug_displayParseInfos] preference keys.size() = 44
08-16 10:29:23.795  7637  7637 D PreferenceKeysParser: [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@35051bd4, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@3b9fa17d, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@29da0872, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@3a9484c3, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@23822140, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@3c09d879, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@36bc39be, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@eb0aa1f, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@808116c, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@6468335, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@17fe33ca, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@33fc93b, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@301ad858, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@15691db1, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@cb3c296, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@3d7be17, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@3b912204, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@2840e3ed, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@1f617222, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@359024b3, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@f005a70, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@2154d1e9, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@c488e6e, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@2d5e590f, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@e8ad9c, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@2a9fa3a5, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@73237a, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@3031772b, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@2da10788, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@190bd521, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@3d7ffd46, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@18ce5b07, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@1e031434, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@bafa25d, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@2e2ea7d2, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@3f6ba0a3, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@2cd73fa0, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@2c90759, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@37ab6f1e, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@3f0da3ff, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.Preferen,ceKey$KeyData@1700b5cc, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@2a79c015, lg
,08-16 10:29:23.802  7637  7637 D GeneralPreferenceUtils: [migratePrefrenceKeys] Exit: Version(44001600) >= 42001300
08-16 10:29:23.813  7637  7637 D Config  : [init]
,08-16 10:29:23.814  7637  7637 I Config  : LGCalendar ver.4.40.16
,08-16 10:29:23.814  7637  7637 I Config  : start check model
08-16 10:29:23.814  7637  7637 I Config  : start check native_ca
08-16 10:29:23.815  7637  7637 I Config  : Config Operator=OPEN, Country=EU
08-16 10:29:23.816  7637  7637 D Config  : [setDefaultValuesToPref]
08-16 10:29:23.816  7637  7637 D Config  : [parseProfiles]
08-16 10:29:23.822  7637  7637 D ProfilesParser: [debug_displayParseInfos] profile.country = null
08-16 10:29:23.822  7637  7637 D ProfilesParser: [debug_displayParseInfos] profile.operator = null
08-16 10:29:23.822  7637  7637 D Config  : [updateProfiletoCountryInfo]
08-16 10:29:23.823  7637  7637 D GeneralPreference: [checkAndMigrateOldPreference]
08-16 10:29:23.848  7637  7637 E AgendaWidgetManager: [updateWidgets] 
,08-16 10:29:23.858  7637  7656 I InitNotificationRingtoneService: Start InitializeAlertRingtoneService.onHandleIntent
,08-16 10:29:23.871  7637  7656 I AlertUtils: [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/41
,08-16 10:29:23.890  7637  7656 I AlertUtils: [getCalendarNotiSoundURIFromCursor] getCount()= 21
,08-16 10:29:23.896  7637  7656 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arpeggio.ogg
08-16 10:29:23.903  7637  7656 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
08-16 10:29:23.907  7637  7656 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
,08-16 10:29:23.912  7637  7656 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
08-16 10:29:23.917  7637  7656 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
08-16 10:29:23.922  7637  7656 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
,08-16 10:29:23.926  7637  7656 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
08-16 10:29:23.931  7637  7656 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
08-16 10:29:23.935  7637  7656 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
,08-16 10:29:23.940  7637  7656 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Afternoon_Walk.ogg
08-16 10:29:23.944  7637  7656 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
08-16 10:29:23.948  7637  7656 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
,08-16 10:29:23.957  7637  7656 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
08-16 10:29:23.961  7637  7656 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
08-16 10:29:23.965  7637  7656 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
08-16 10:29:23.965  7637  7656 I AlertUtils: [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/41
,08-16 10:29:23.968  7637  7656 I AlertUtils: set default noti to content://media/internal/audio/media/41
08-16 10:29:23.973  7637  7656 I InitNotificationRingtoneService: End InitializeAlertRingtoneService.onHandleIntent
08-16 10:29:24.027  7637  7637 D MonthWidgetProvider: [onReceive]
08-16 10:29:24.028  7637  7637 D CalendarWidgetProvider: [onReceive]
08-16 10:29:24.028  7637  7637 D CalendarWidgetProvider: [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.MonthWidgetProvider }
,08-16 10:29:24.031  7637  7659 W HolidayIntentService: onHandleIntent
08-16 10:29:24.035  7637  7637 D CalendarTypeController: [onUpdateAndInitCalendarTime]
08-16 10:29:24.036  7637  7659 D HolidayDataLoader: readJsonAsset : holiday.json
08-16 10:29:24.052  7637  7637 D WeekWidgetProvider: [onReceive]
08-16 10:29:24.052  7637  7637 D CalendarWidgetProvider: [onReceive]
08-16 10:29:24.052  7637  7637 D CalendarWidgetProvider: [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.WeekWidgetProvider }
,08-16 10:29:24.057  7637  7637 D CalendarTypeController: [onUpdateAndInitCalendarTime]
08-16 10:29:24.063  2179  2179 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
08-16 10:29:24.080  7581  7581 I DigitalAppWidgetProvider: onReceive: android.intent.action.ALARM_CHANGED
08-16 10:29:24.084  6788  6788 D WeatherAncestor: 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 10:29:24
,08-16 10:29:24.087  6788  6788 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-16 10:29:24.087  6788  6788 D Weather.Utils: 2 : All the weather widget is gone.
08-16 10:29:24.088  6788  6788 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-16 10:29:24.090  6788  6788 D Weather_cast: 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
08-16 10:29:24.090  6788  6788 D WeatherAncestor: 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 10:29:24
08-16 10:29:24.096  2019  2019 I [LGHome]LGNumberBadgeReceiver: [LGNumberBadgeReceiver.java:64:onReceive()]LGNumberBadgeReceiver.onReceive() is called : action = android.intent.action.BADGE_COUNT_UPDATE
08-16 10:29:24.097  2019  2834 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.ui.ConversationList = 0
08-16 10:29:24.097  2019  2834 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.activity.MainMenuActivity = 0
08-16 10:29:24.097  2019  2834 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.android.mms.ui.ConversationList = 0
08-16 10:29:24.099  7339  7339 V [BNRBootReceiver]: boot receiver action = com.lge.bnr.releasebadge
08-16 10:29:24.099  7339  7339 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.lge.bnr.service.BNRBootReceiver.setHomeBadgeCount:192 com.lge.bnr.service.BNRBootReceiver.setBadgeStatus:225 
,08-16 10:29:24.102  1588  1588 D KeyguardModel: mReceiver, received action: android.intent.action.BADGE_COUNT_UPDATE, sendingUserId:0
08-16 10:29:24.102  1588  1588 D KeyguardModel: ACTION_GENERAL_UPDATE_NOTIFICATION received! package: com.lge.bnr.launcher, class: com.lge.bnr.launcher.BNRLauncherActivity, unread_count: 0
08-16 10:29:24.102  1588  1588 D KeyguardModel: putThirdPartyNotificationIntoList Number: 0 Id: 12 UserId: 0
08-16 10:29:24.104  2019  2834 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 1
08-16 10:29:24.104  2019  2834 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.bnr.launcher.BNRLauncherActivity = 0
08-16 10:29:24.104  7339  7339 V [BNRBootReceiver]: Boot Receiver Return
08-16 10:29:24.108  2019  2019 I [LGHome]LGNumberBadgeReceiver: [LGNumberBadgeReceiver.java:64:onReceive()]LGNumberBadgeReceiver.onReceive() is called : action = android.intent.action.BADGE_COUNT_UPDATE
08-16 10:29:24.109  2019  5359 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.ui.ConversationList = 0
08-16 10:29:24.109  2019  5359 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.activity.MainMenuActivity = 0
08-16 10:29:24.110  2019  5359 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.android.mms.ui.ConversationList = 0
08-16 10:29:24.111  2019  5359 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 1
08-16 10:29:24.111  2019  5359 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.bnr.launcher.BNRLauncherActivity = 0
08-16 10:29:24.128  7637  7659 E HolidayIntentService: onHandleIntent:holiday data empty
,08-16 10:29:24.131  1037  1945 I ActivityManager: Killing 6033:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
08-16 10:29:24.152  6350  6350 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-16 10:29:24.153  6350  6350 W System.err: android.os.DeadObjectException
08-16 10:29:24.154  6350  6350 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-16 10:29:24.154  6350  6350 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-16 10:29:24.154  6350  6350 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-16 10:29:24.154  6350  6350 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-16 10:29:24.154  6350  6350 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-16 10:29:24.154  6350  6350 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-16 10:29:24.154  6350  6350 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-16 10:29:24.154  6350  6350 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 10:29:24.154  6350  6350 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-16 10:29:24.154  6350  6350 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-16 10:29:24.154  6350  6350 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
,08-16 10:29:24.154  6350  6350 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 10:29:24.154  6350  6350 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-16 10:29:24.154  6350  6350 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-16 10:29:24.154  6350  6350 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-16 10:29:24.155  6350  6350 W System.err: android.os.DeadObjectException
08-16 10:29:24.155  6350  6350 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-16 10:29:24.155  6350  6350 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-16 10:29:24.155  6350  6350 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-16 10:29:24.155  6350  6350 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
,08-16 10:29:24.155  6350  6350 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-16 10:29:24.155  6350  6350 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-16 10:29:24.155  6350  6350 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-16 10:29:24.155  6350  6350 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
,08-16 10:29:24.155  6350  6350 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-16 10:29:24.155  6350  6350 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-16 10:29:24.155  6350  6350 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 10:29:24.155  6350  6350 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
,08-16 10:29:24.155  6350  6350 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-16 10:29:24.155  6350  6350 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-16 10:29:24.155  6350  6350 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-16 10:29:24.156  6350  6350 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,08-16 10:29:24.239  1037  2000 W libprocessgroup: failed to open /acct/uid_1000/pid_6033/cgroup.procs: No such file or directory
,08-16 10:29:24.240  1037  2000 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
08-16 10:29:24.249  6350  6350 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-16 10:29:24.250  6350  6350 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-16 10:29:24.309  1037  1927 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7663 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-16 10:29:24.311  6350  6350 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-16 10:29:24.330  1037  1523 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=21.5, 0.0, 0.0  rx=17.0 bcn=0 [on:0 tx:0 rx:0 period:3419] from screen [on:0 period:-1837618198] gl rssi=-56 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-16 10:29:24.334  1037  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=21.5, 0.0, 0.0  rx=17.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1837618195] gl rssi=-56 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 10:29:24.334  1037  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-16 10:29:24.347  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 10:29:24.400  7663  7663 D UEI.SmartControl: Quickset Services start...
,08-16 10:29:24.402  7663  7663 I UEI.SmartControl: Manufacture = LGE
,08-16 10:29:24.403  7663  7663 D UEI.SmartControl: Id = LGNevo
08-16 10:29:24.407  7663  7663 D UEI.SmartControl: File observer start...
08-16 10:29:24.408  7663  7663 E UEI.SmartControl: IR Port is disabled: false
08-16 10:29:24.409  7663  7663 D UEI.SmartControl: Starting file observer...
08-16 10:29:24.410  7663  7663 D UEI.SmartControl: Extracting JNI libs...
08-16 10:29:24.411  7663  7663 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
,08-16 10:29:24.523  7663  7663 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,08-16 10:29:24.524  7663  7663 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
,08-16 10:29:24.524  7663  7663 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-16 10:29:24.566  7663  7663 I UEI.SmartControl: --- Selecting new region: 6
,08-16 10:29:24.569  7663  7663 I UEI.SmartControl: Model = LG-D855
,08-16 10:29:24.571  7663  7663 D UEI.SmartControl: QS Service created
08-16 10:29:24.587  7663  7663 I UEI.SmartControl: Service initServices...
,08-16 10:29:24.592  7663  7663 D UEI.SmartControl: QS start get config
,08-16 10:29:24.663  7663  7663 D UEI.SmartControl: Loading JNI Libs...
,08-16 10:29:24.715  1037  1365 V AlarmManager: ELAPSED_WAKEUP set : Alarm{9ce4dbc type 2 when 403832 com.google.android.gms} when 403832
,08-16 10:29:24.726   305  7685 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-16 10:29:24.727   305  7685 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
08-16 10:29:24.728   305  7685 D libc-netbsd: res_queryN name = mtalk.google.com succeed
,08-16 10:29:24.946  1037  2000 I ActivityManager: Killing 6279:com.android.settings/1000 (adj 15): empty #17
,08-16 10:29:24.983  7663  7663 I UEI.SmartControl: Supports setup maps: true
,08-16 10:29:24.991  7663  7663 D UEI.SmartControl: QS start statue = true Error code = 0
08-16 10:29:24.991  7663  7663 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-16 10:29:24.991  7663  7663 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-16 10:29:24.991  7663  7663 I UEI.SmartControl: ### init IR Blaster...
08-16 10:29:24.997  7663  7663 D serial_port: Configuring serial port
,08-16 10:29:25.003  7663  7663 E UEI.SmartControl: UEIBLaster setting for 616
08-16 10:29:25.003  7663  7663 I UEI.SmartControl: Setting serial record hearder size = 2
08-16 10:29:25.003  7663  7663 I UEI.SmartControl: configuring settings for MAXQ616
08-16 10:29:25.003  7663  7663 I UEI.SmartControl: Get version...
08-16 10:29:25.006  1037  1927 W libprocessgroup: failed to open /acct/uid_1000/pid_6279/cgroup.procs: No such file or directory
08-16 10:29:25.011  2179  7686 D GCM     : Connected
,08-16 10:29:25.019  7663  7693 D UEI.SmartControl: serial port data available: 21
,08-16 10:29:25.042  2179  7686 D GCM     : Message class com.google.e.a.a.q
,08-16 10:29:25.058  7663  7663 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-16 10:29:25.058  7663  7663 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-16 10:29:25.058  7663  7663 I UEI.SmartControl: QS saving settings...
,08-16 10:29:25.061  7663  7663 D UEI.SmartControl: IR Blaster version: 25672567
08-16 10:29:25.077  7663  7693 D UEI.SmartControl: serial port data available: 4
,08-16 10:29:25.112  7663  7696 I UEI.SmartControl: Device manager: loading config....
,08-16 10:29:25.113  7663  7696 D UEI.SmartControl: ----------- loading internal config...
,08-16 10:29:25.120  7663  7663 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-16 10:29:25.125  7663  7663 E UEI.SmartControl: Services init done
08-16 10:29:25.126  7663  7663 D UEI.SmartControl: QS Service init finished
08-16 10:29:25.126  7663  7696 E UEI.SmartControl: Loading SETTINGS...
08-16 10:29:25.128  7663  7663 D UEI.SmartControl: QS Service version name: 2.1.91
08-16 10:29:25.128  7663  7663 D UEI.SmartControl: QS Service version code: 201091
08-16 10:29:25.130  7663  7663 D UEI.SmartControl: Service requested: Control
,08-16 10:29:25.134  1037  1872 I ActivityManager: Killing 6350:com.lge.qremote/u0a112 (adj 15): empty #17
,08-16 10:29:25.143  7663  7696 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-16 10:29:25.171  7663  7695 I UEI.SmartControl: Notify AllClients services are ready: 0
,08-16 10:29:25.171  7663  7695 D UEI.SmartControl: -----service ready thread exits
,08-16 10:29:25.190  1037  1927 W libprocessgroup: failed to open /acct/uid_10112/pid_6350/cgroup.procs: No such file or directory
08-16 10:29:25.192  7663  7663 D UEI.SmartControl: Internal service binding...
,08-16 10:29:26.364  6149  7615 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,08-16 10:29:26.364  6149  7615 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-16 10:29:26.365  6149  7615 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 10:29:26.366  6149  7615 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 10:29:26.367  6149  7615 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,08-16 10:29:26.375  6149  7704 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
08-16 10:29:26.375  6149  7704 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-16 10:29:26.377  6149  7704 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 10:29:26.378  6149  7706 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 789, name: OutgoingSocketThread/Sender)
08-16 10:29:26.379  6149  7704 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 10:29:26.379  6149  7704 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
08-16 10:29:26.380  6149  7707 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 790, name: OutgoingSocketThread/Receiver)
08-16 10:29:26.381  6149  7707 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 790, thread name: OutgoingSocketThread/Receiver)
08-16 10:29:26.381  6149  7707 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-16 10:29:26.381  6149  7707 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 790, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
08-16 10:29:26.384  6149  7709 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 792, name: IncomingSocketThread/Receiver)
08-16 10:29:26.386  6149  7708 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 791, name: IncomingSocketThread/Sender)
,08-16 10:29:26.388  6149  7709 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 792, thread name: IncomingSocketThread/Receiver)
,08-16 10:29:26.389  6149  7709 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,08-16 10:29:26.389  6149  7709 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 792, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
08-16 10:29:27.354  1037  1523 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=19.8, 0.0, 0.0  rx=14.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1837615174] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 10:29:27.357  1037  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=19.8, 0.0, 0.0  rx=14.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1837615171] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 10:29:27.357  1037  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-16 10:29:27.387  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 10:29:28.506  1588  1588 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-16 10:29:28.539  1037  1413 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-16 10:29:28.606  1037  1037 D administrator: Handling package changes for user 0
,08-16 10:29:28.632  1037  1104 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7710 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
08-16 10:29:28.645  2019  2019 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-16 10:29:28.657  1588  1588 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
08-16 10:29:28.669  1588  1588 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,08-16 10:29:28.694  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 10:29:28.711  7710  7710 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-16 10:29:28.747  1037  1037 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-16 10:29:28.747  1037  1037 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-16 10:29:28.778  1037  1523 E WifiStateMachine:  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,08-16 10:29:28.778  1037  1523 E WifiStateMachine:  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
08-16 10:29:28.778  1037  1523 E WifiStateMachine:  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,08-16 10:29:28.778  1037  1523 E WifiStateMachine:  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
08-16 10:29:28.779  1037  1523 E WifiStateMachine:  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
08-16 10:29:28.779  1037  1523 E WifiStateMachine:  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,08-16 10:29:28.782  7710  7710 D LgDataFeature: LgDataFeature() Constructor: none
08-16 10:29:28.782  7710  7710 D LgDataFeature: LgDataFeature() Constructor Done, null
08-16 10:29:28.815  1037  1102 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-16 10:29:28.821  1037  1102 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-16 10:29:28.830  2019  2019 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-16 10:29:28.835  2465  2465 V GmsNetworkLocationProvi: DISABLE
,08-16 10:29:28.859  2465  2465 E GCoreFlp: Bound FusedProviderService with LocationManager
,08-16 10:29:28.872  1037  1102 D LocationProviderProxy: applying state to connected service
08-16 10:29:28.886  7710  7756 I Babel   : MmsConfig: mnc/mcc: 0/0
08-16 10:29:28.886  7710  7756 I Babel   : MmsConfig.loadMmsSettings
08-16 10:29:28.888  7710  7756 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,08-16 10:29:28.888  7710  7756 I Babel   : MmsConfig.loadFromDatabase
,08-16 10:29:28.897  7710  7756 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-16 10:29:28.897  7710  7756 I Babel   : MmsConfig.loadFromResources
08-16 10:29:28.898  7710  7756 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-16 10:29:28.898  7710  7756 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,08-16 10:29:28.919  7710  7754 W AudioCapabilities: Unsupported mime audio/evrc
,08-16 10:29:28.920  7710  7754 W AudioCapabilities: Unsupported mime audio/qcelp
08-16 10:29:28.922  7710  7754 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-16 10:29:28.925  7710  7710 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 10:29:28.928  7710  7754 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
08-16 10:29:28.928  7710  7754 W AudioCapabilities: Unsupported mime audio/qcelp
08-16 10:29:28.929  7710  7754 W AudioCapabilities: Unsupported mime audio/evrc
,08-16 10:29:28.937  7710  7754 W VideoCapabilities: Unsupported mime video/x-ms-wmv
08-16 10:29:28.938  7710  7754 W VideoCapabilities: Unsupported mime video/divx
,08-16 10:29:28.945  7710  7754 W VideoCapabilities: Unsupported mime video/divx311
08-16 10:29:28.949  1802  7758 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-16 10:29:28.949  1802  7758 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
08-16 10:29:28.953  7710  7754 W VideoCapabilities: Unsupported mime video/divx4
,08-16 10:29:28.954  7488  7488 I AppUp4:CustModeStarterReceiver: onReceive
08-16 10:29:28.957  7710  7754 W VideoCapabilities: Unsupported mime video/mp4v-esdp
08-16 10:29:28.960  7488  7488 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@23822140
08-16 10:29:28.960  7488  7488 D AppUp4:CustFacade: isCustomizationCompleted : false
08-16 10:29:28.960  7488  7488 D AppUp4:CustFacade: isPhone : true
08-16 10:29:28.961  7488  7488 D AppUp4:CustModeStarterReceiver: begin check event
08-16 10:29:28.961  7488  7488 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-16 10:29:28.967  1802  4684 I Icing   : updateResources: need to parse e{com.google.android.gms}
,08-16 10:29:28.977  7710  7754 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
08-16 10:29:28.979  7710  7754 W AudioCapabilities: Unsupported mime audio/eac3
,08-16 10:29:28.981  7710  7754 W AudioCapabilities: Unsupported mime audio/ac3
08-16 10:29:28.981  7710  7754 W AudioCapabilities: Unsupported mime audio/g726
08-16 10:29:28.982  7710  7754 W AudioCapabilities: Unsupported mime audio/wma-voice
08-16 10:29:28.983  7710  7754 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-16 10:29:28.984  7710  7754 W AudioCapabilities: Unsupported mime audio/adpcm
08-16 10:29:28.986  7710  7754 W VideoCapabilities: Unsupported mime video/theora
08-16 10:29:28.987  7710  7754 W VideoCapabilities: Unsupported mime video/mjpg
08-16 10:29:28.995  1037  1052 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7761 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,08-16 10:29:29.032  1037  1873 I ActivityManager: Killing 6396:com.lge.formmanager/u0a26 (adj 15): empty #17
08-16 10:29:29.042  7761  7761 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 10:29:29.042  7761  7761 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 10:29:29.043  7761  7761 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-16 10:29:29.044  7761  7761 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-16 10:29:29.044  7761  7761 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,08-16 10:29:29.153  1037  2037 W libprocessgroup: failed to open /acct/uid_10026/pid_6396/cgroup.procs: No such file or directory
,08-16 10:29:29.208  7761  7761 I SystemConfig: BUILD Country: EU
08-16 10:29:29.209  7761  7761 I SystemConfig: BUILD Operator: OPEN
,08-16 10:29:29.265  1037  1739 I ActivityManager: Killing 6745:com.android.chrome/u0a57 (adj 15): empty #17
,08-16 10:29:29.373  1037  1872 W libprocessgroup: failed to open /acct/uid_10057/pid_6745/cgroup.procs: No such file or directory
,08-16 10:29:29.391  7761  7779 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-16 10:29:29.391  7761  7779 I SystemConfig: existFile = false
08-16 10:29:29.392  7761  7779 I SystemConfig: canReadFile = false
08-16 10:29:29.392  7761  7779 I SystemConfig: systemFeature RCS result false
08-16 10:29:29.392  7761  7779 D SystemConfig: refreshRcsSupport() :false
,08-16 10:29:29.431  1037  1739 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7787 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-16 10:29:29.498  7787  7787 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-16 10:29:29.499  7787  7787 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-16 10:29:29.499  7787  7787 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-16 10:29:29.499  7787  7787 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-16 10:29:29.614  7787  7787 I AppConfig: Total System Memory = 2995761152
,08-16 10:29:29.627  7787  7787 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
08-16 10:29:29.716  1037  1945 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7806 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-16 10:29:29.719  1037  1945 I ActivityManager: Killing 6770:com.lge.drmservice/u0a62 (adj 15): empty #17
,08-16 10:29:29.770  1037  1052 W libprocessgroup: failed to open /acct/uid_10062/pid_6770/cgroup.procs: No such file or directory
,08-16 10:29:29.949  7806  7806 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-16 10:29:30.041  7806  7806 D LgDataFeature: LgDataFeature() Constructor: none
08-16 10:29:30.042  7806  7806 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 10:29:30.101  7806  7806 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-16 10:29:30.113  7663  7697 D UEI.SmartControl: Internal timer expired: 1
08-16 10:29:30.114  7663  7697 D UEI.SmartControl: unbind internal service
08-16 10:29:30.119  7806  7806 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-16 10:29:30.120  7663  7663 D UEI.SmartControl: Service.onUnbind: IControl
,08-16 10:29:30.120  7663  7663 D UEI.SmartControl: Service.onDestroy
08-16 10:29:30.121  7806  7806 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-16 10:29:30.122  7663  7663 D UEI.SmartControl: Lock is in USE false
08-16 10:29:30.122  7663  7663 D UEI.SmartControl: unbind internal service
08-16 10:29:30.123  7663  7663 D serial_port: close(fd = 25)
08-16 10:29:30.128  7663  7663 I UEI.SmartControl: Serial port is closed.
08-16 10:29:30.128  7663  7663 I UEI.SmartControl: Serial port is closed.
08-16 10:29:30.129  7663  7663 D UEI.SmartControl: Blaster closed
08-16 10:29:30.129  7663  7663 D UEI.SmartControl: Shut down QS...
08-16 10:29:30.129  7663  7663 D UEI.SmartControl: Stopping QS lib
08-16 10:29:30.130  7663  7663 D UEI.SmartControl: QS lib stop result = true
08-16 10:29:30.130  7663  7663 D UEI.SmartControl: Stopped QS lib
08-16 10:29:30.134  7663  7663 D UEI.SmartControl: Stopped file observer...
08-16 10:29:30.134  7663  7663 D UEI.SmartControl: QS shutdown complete
,08-16 10:29:30.138  7806  7806 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-16 10:29:30.139  7806  7806 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
08-16 10:29:30.169  1037  1872 I ActivityManager: Killing 6806:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,08-16 10:29:30.279  1037  2000 W libprocessgroup: failed to open /acct/uid_10093/pid_6806/cgroup.procs: No such file or directory
,08-16 10:29:30.287  2814  2835 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-16 10:29:30.290  2814  2835 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@226962b8 on behalf of 7806
08-16 10:29:30.298  4540  7849 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,08-16 10:29:30.363  1037  1053 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7850 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-16 10:29:30.386   363   363 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 496us total 23.271ms
08-16 10:29:30.387  1037  1523 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=13.9, 0.0, 0.0  rx=11.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1837612141] gl rssi=-56 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 10:29:30.388  1037  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=13.9, 0.0, 0.0  rx=11.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1837612140] gl rssi=-56 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 10:29:30.388  1037  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-16 10:29:30.401  7806  7806 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
08-16 10:29:30.410   363   363 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 463us total 21.137ms
,08-16 10:29:30.427  7806  7806 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-16 10:29:30.436   363   363 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 413us total 25.089ms
08-16 10:29:30.472  7850  7850 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-16 10:29:30.495  7850  7850 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
,08-16 10:29:30.495  7850  7850 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-16 10:29:30.495  7850  7850 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-16 10:29:30.495  7850  7850 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-16 10:29:30.495  7850  7850 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-16 10:29:30.495  7850  7850 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
08-16 10:29:30.518  1037  1901 I ActivityManager: Killing 7520:com.lge.email/u0a23 (adj 15): empty #17
,08-16 10:29:30.573  1037  1963 W libprocessgroup: failed to open /acct/uid_10023/pid_7520/cgroup.procs: No such file or directory
,08-16 10:29:30.761  1037  1981 I art     : Explicit concurrent mark sweep GC freed 33126(1593KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 1.873ms total 136.888ms
,08-16 10:29:30.861  1037  1927 V SIM_STK : Menu title from STK is T-Mobile
,08-16 10:29:30.886  4540  7849 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 588 ms] updated apps [took 588 ms] 
,08-16 10:29:33.408  1037  1523 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=8.4, 0.0, 0.0  rx=6.0 bcn=0 [on:0 tx:0 rx:0 period:3007] from screen [on:0 period:-1837609120] gl rssi=-56 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-16 10:29:33.418  1037  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=8.4, 0.0, 0.0  rx=6.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1837609110] gl rssi=-56 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-16 10:29:33.420  1037  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-16 10:29:34.365  6149  6212 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-16 10:29:34.368  6149  6212 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-16 10:29:34.382  6149  6212 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1f617222 Bundle[{}]
08-16 10:29:34.383  6149  6212 I io.jxcore.node.LifeCycleMonitor: start: OK
08-16 10:29:34.383  6149  6212 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-16 10:29:34.384  6149  6212 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-16 10:29:34.385  6149  6212 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-16 10:29:34.385  6149  6212 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-16 10:29:34.386  6149  6212 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-16 10:29:36.441  1037  1523 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=4.2, 0.0, 0.0  rx=3.0 bcn=0 [on:0 tx:0 rx:0 period:3008] from screen [on:0 period:-1837606087] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 10:29:36.444  1037  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=4.2, 0.0, 0.0  rx=3.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1837606084] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 10:29:36.444  1037  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-16 10:29:39.468  1037  1523 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=2.1, 0.0, 0.0  rx=1.5 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1837603061] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-16 10:29:39.478  1037  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=2.1, 0.0, 0.0  rx=1.5 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1837603050] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-16 10:29:39.478  1037  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-16 10:29:42.498  1037  1523 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-57 f=2447 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1837600030] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-16 10:29:42.510  1037  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-57 f=2447 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1837600018] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-16 10:29:42.510  1037  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-16 10:29:44.405  6149  6212 I System.out: Running OutgoingSocketThread
,08-16 10:29:44.420  6149  7886 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775,
08-16 10:29:44.420  6149  7886 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-16 10:29:45.530  1037  1523 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-57 f=2447 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:-1837596999] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 10:29:45.533  1037  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-57 f=2447 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1837596995] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 10:29:45.533  1037  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-16 10:29:47.421  6149  7886 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
08-16 10:29:47.421  6149  7886 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-16 10:29:47.421  6149  7886 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 10:29:47.422  6149  7886 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 10:29:47.422  6149  7886 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,08-16 10:29:47.427  6149  7887 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
08-16 10:29:47.427  6149  7887 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-16 10:29:47.427  6149  7887 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 10:29:47.428  6149  7887 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 10:29:47.428  6149  7887 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
08-16 10:29:47.430  6149  7890 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 802, name: OutgoingSocketThread/Receiver)
08-16 10:29:47.431  6149  7890 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 802, thread name: OutgoingSocketThread/Receiver)
08-16 10:29:47.431  6149  7890 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-16 10:29:47.431  6149  7890 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 802, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
08-16 10:29:47.433  6149  7889 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 801, name: OutgoingSocketThread/Sender)
08-16 10:29:47.434  6149  7892 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 804, name: IncomingSocketThread/Receiver)
08-16 10:29:47.434  6149  7892 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 804, thread name: IncomingSocketThread/Receiver)
08-16 10:29:47.434  6149  7892 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-16 10:29:47.434  6149  7892 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 804, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
08-16 10:29:47.436  6149  7891 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 803, name: IncomingSocketThread/Sender)
,08-16 10:29:48.559  1037  1523 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-57 f=2447 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1837593970] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-16 10:29:48.562  1037  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-57 f=2447 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1837593966] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 10:29:48.563  1037  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-16 10:29:49.872  1588  1588 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-16 10:29:49.873  1588  1588 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-16 10:29:49.887  1037  1529 D WifiController: battery changed pluggedType: 2
,08-16 10:29:49.891  1928  2087 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-16 10:29:49.891  1928  2087 D LEDHandler: Battery Level Remaining: 100%
08-16 10:29:49.891  1928  2087 D LEDHandler: Battery Temp: 278, mChargingStatus=5, mChargingStop=false
08-16 10:29:49.892  1588  1588 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
08-16 10:29:49.893  1588  1588 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-16 10:29:49.894  1588  1588 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-16 10:29:49.900  7141  7192 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-16 10:29:49.903  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 10:29:49.903  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 10:29:49.905  7339  7339 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-16 10:29:51.590  1037  1523 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-58 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3008] from screen [on:0 period:-1837590938] gl rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 10:29:51.593  1037  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-58 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1837590935] gl rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 10:29:51.593  1037  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-16 10:29:54.620  1037  1523 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-58 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3007] from screen [on:0 period:-1837587909] gl rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-16 10:29:54.623  1037  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-58 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1837587906] gl rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 10:29:54.623  1037  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-16 10:29:55.428  6149  6212 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 813)
,08-16 10:29:55.438  6149  6212 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-16 10:29:55.438  6149  6212 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 814)
08-16 10:29:57.651  1037  1523 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-58 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3008] from screen [on:0 period:-1837584877] gl rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 10:29:57.654  1037  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-58 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1837584874] gl rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 10:29:57.654  1037  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-16 10:29:58.278  1037  1523 E WifiStateMachine:  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,08-16 10:29:58.286  1037  1523 E WifiStateMachine:  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,08-16 10:29:58.287  1037  1523 E WifiStateMachine:  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-16 10:29:58.288  1037  1523 E WifiStateMachine:  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-16 10:29:58.291  1037  1523 E WifiStateMachine:  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-16 10:29:58.291  1037  1523 E WifiStateMachine:  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-16 10:30:00.446  6149  6212 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 10:30:00.446  6149  6212 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21df4466 added. We now have 3 listener(s)
,08-16 10:30:00.457  1037  1703 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 10:30:00.462  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 10:30:00.462  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 10:30:00.462  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 10:30:00.462  6149  6212 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 10:30:00.462  6149  6212 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fcb63a7 added. We now have 4 listener(s)
08-16 10:30:00.462  6149  6212 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 10:30:00.464  1588  1588 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-16 10:30:00.465  1588  1588 I KeyguardUpdateMonitor: called onTimeUpdated()
08-16 10:30:00.465  1588  1588 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-16 10:30:00.465  1588  1588 I [SystemUI]Clock: called onTimeUpdated()
,08-16 10:30:00.470  1588  1588 I LgeClockWidgetControlView: called onTimeUpdated()
08-16 10:30:00.470  1588  1588 I [SystemUI]DateView: called onTimeUpdated()
08-16 10:30:00.471  1588  1588 I [SystemUI]DateView: called onTimeUpdated()
08-16 10:30:00.471  1588  1588 D KeyguardUpdateMonitor: handleTimeUpdate
08-16 10:30:00.472  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 10:30:00.475  6149  6212 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 10:30:00.481  6149  6212 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 10:30:00.481  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 10:30:00.481  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 10:30:00.481  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 10:30:00.481  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 10:30:00.481  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 10:30:00.481  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 10:30:00.481  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 10:30:00.485  6149  6212 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 10:30:00.485  6149  6212 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 10:30:00.489  6149  6212 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 10:30:00.490  6149  6212 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 10:30:00.490  6149  6212 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 10:30:00.490  6149  6212 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 10:30:00.490  6149  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:30:00.490  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 10:30:00.490  6149  6212 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 10:30:00.490  6149  6212 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21df4466 removed from the list
08-16 10:30:00.490  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:30:00.490  6149  6212 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fcb63a7 removed from the list
08-16 10:30:00.494  6149  6149 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 10:30:00.498  6149  6149 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 10:30:00.499  6149  6212 D io.jxcore.node.ConnectivityMonitor: stop
08-16 10:30:00.499  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:30:00.500  6149  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:30:00.500  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:30:00.501  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 10:30:00.501  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 10:30:00.501  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:30:00.501  6149  6212 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fcb63a7 not in the list
08-16 10:30:00.501  6149  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:30:00.501  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:30:00.502  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 10:30:00.502  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 10:30:00.502  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:30:00.502  6149  6212 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fcb63a7 not in the list
08-16 10:30:00.502  6149  6212 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 10:30:00.502  6149  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:30:00.502  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:30:00.502  6149  6212 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21df4466 not in the list
08-16 10:30:00.503  6149  6212 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 10:30:00.503  6149  6212 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35e86bfd added. We now have 3 listener(s)
08-16 10:30:00.505  1037  1901 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-16 10:30:00.513  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 10:30:00.513  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 10:30:00.513  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 10:30:00.514  6149  6212 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 10:30:00.514  6149  6212 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@78b40f2 added. We now have 4 listener(s)
08-16 10:30:00.514  6149  6212 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 10:30:00.515  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 10:30:00.518  6149  6212 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 10:30:00.524  6149  6212 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 10:30:00.524  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 10:30:00.524  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 10:30:00.524  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 10:30:00.524  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 10:30:00.524  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 10:30:00.524  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 10:30:00.524  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 10:30:00.526  6149  6212 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 10:30:00.526  6149  6212 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 10:30:00.528  6149  6149 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 10:30:00.530  6149  6149 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 10:30:00.531  6149  6212 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 10:30:00.531  6149  6212 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 10:30:00.531  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 10:30:00.531  6149  6212 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 10:30:00.531  6149  6212 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 10:30:00.537  6149  6212 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-16 10:30:00.538  1037  1053 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 10:30:00.542  6149  6212 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-16 10:30:00.544  6149  6212 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 10:30:00.546  6149  6212 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-16 10:30:00.547  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 10:30:00.548  6149  6212 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-16 10:30:00.549  6149  6212 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 10:30:00.549  6149  6212 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 10:30:00.677  1037  1523 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-57 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1837581851] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-16 10:30:00.690  1037  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-57 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1837581840] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-16 10:30:00.690  1037  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-16 10:30:01.276  1037  1365 D PowerManagerServiceEx: acquireWakeLockInternal: lock=479019197, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,08-16 10:30:01.299  7581  7581 I DigitalAppWidgetProvider: onReceive: com.android.deskclock.ON_QUARTER_HOUR
,08-16 10:30:01.304  7581  7581 V DigitalAppWidgetProvider: startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@3c09d879
08-16 10:30:01.328  2597  2597 D [Concierge]Service: onStartCommand(). Type : 9
,08-16 10:30:01.356  1037  1037 D PowerManagerServiceEx: releaseWakeLockInternal: lock=479019197 [*alarm*], flags=0x0
,08-16 10:30:03.551  6149  6212 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 10:30:03.551  6149  6212 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 10:30:03.551  6149  6212 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 10:30:03.561  6149  6212 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 10:30:03.561  6149  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:30:03.561  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 10:30:03.561  6149  6212 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 10:30:03.561  6149  6212 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35e86bfd removed from the list
08-16 10:30:03.561  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:30:03.561  6149  6212 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@78b40f2 removed from the list
08-16 10:30:03.562  6149  6212 D io.jxcore.node.ConnectivityMonitor: stop
08-16 10:30:03.562  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:30:03.564  6149  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:30:03.565  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:30:03.568  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 10:30:03.568  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 10:30:03.573  6149  6212 D BluetoothLeScanner: could not find callback wrapper
08-16 10:30:03.573  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 10:30:03.574  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:30:03.574  6149  6212 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@78b40f2 not in the list
08-16 10:30:03.574  6149  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:30:03.574  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:30:03.575  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 10:30:03.576  6149  6212 D BluetoothLeScanner: could not find callback wrapper
08-16 10:30:03.576  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 10:30:03.576  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 10:30:03.576  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:30:03.576  6149  6212 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@78b40f2 not in the list
08-16 10:30:03.576  6149  6212 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 10:30:03.576  6149  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:30:03.576  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:30:03.576  6149  6212 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35e86bfd not in the list
08-16 10:30:03.577  6149  6212 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 10:30:03.577  6149  6212 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d887a3e added. We now have 3 listener(s)
08-16 10:30:03.578  1037  1981 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 10:30:03.581  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 10:30:03.581  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 10:30:03.581  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 10:30:03.581  6149  6212 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 10:30:03.581  6149  6212 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24f209f added. We now have 4 listener(s)
08-16 10:30:03.581  6149  6212 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 10:30:03.582  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 10:30:03.590  6149  6212 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 10:30:03.594  6149  6212 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 10:30:03.594  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 10:30:03.594  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 10:30:03.594  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 10:30:03.594  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 10:30:03.594  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 10:30:03.594  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 10:30:03.594  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 10:30:03.599  6149  6212 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 10:30:03.599  6149  6212 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 10:30:03.603  6149  6149 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 10:30:03.605  6149  6149 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 10:30:03.606  6149  6212 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-16 10:30:03.607  6149  6212 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
08-16 10:30:03.608  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
08-16 10:30:03.612  6149  6212 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-16 10:30:03.612  6149  6212 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
08-16 10:30:03.612  6149  6212 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-16 10:30:03.612  6149  6212 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 10:30:03.616  6149  6212 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-16 10:30:03.617  6149  6212 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-16 10:30:03.617  6149  6212 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-16 10:30:03.618  6149  6149 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-16 10:30:03.619  6149  6212 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-16 10:30:03.621  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
08-16 10:30:03.621  6149  6212 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 10:30:03.621  6149  6212 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 10:30:03.626  6149  6212 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 10:30:03.628  1037  1053 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 10:30:03.634  1037  1901 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 10:30:03.637  6149  6212 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-16 10:30:03.638  6149  6212 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 10:30:03.641  6149  6212 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 10:30:03.641  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-16 10:30:03.643  6149  6212 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-16 10:30:03.644  6149  7893 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 10:30:03.645  7141  7253 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=82
08-16 10:30:03.646  6149  7893 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
08-16 10:30:03.711  1037  1523 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-58 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3008] from screen [on:0 period:-1837578817] gl rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 10:30:03.715  1037  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-58 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1837578814] gl rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 10:30:03.715  1037  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-16 10:30:06.644  6149  6212 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-16 10:30:06.737  1037  1523 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-58 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1837575791] gl rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-16 10:30:06.746  1037  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-58 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1837575782] gl rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-16 10:30:06.746  1037  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-16 10:30:09.650  6149  6212 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 10:30:09.651  6149  6212 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-16 10:30:09.651  6149  6212 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 10:30:09.651  6149  6212 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-16 10:30:09.651  6149  6212 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-16 10:30:09.651  6149  6212 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-16 10:30:09.651  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,08-16 10:30:09.663  6149  7893 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-16 10:30:09.663  6149  7893 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-16 10:30:09.663  6149  7893 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-16 10:30:09.663  6149  6149 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-16 10:30:09.664  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 10:30:09.664  6149  6212 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-16 10:30:09.665  6149  6149 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-16 10:30:09.665  6149  6212 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 10:30:09.665  6149  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:30:09.665  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 10:30:09.667  6149  6149 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 10:30:09.667  6149  6149 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-16 10:30:09.669  6149  6212 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 10:30:09.669  6149  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:30:09.669  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 10:30:09.669  6149  6212 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 10:30:09.669  6149  6212 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d887a3e removed from the list
08-16 10:30:09.669  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:30:09.669  6149  6212 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24f209f removed from the list
08-16 10:30:09.669  6149  6212 D io.jxcore.node.ConnectivityMonitor: stop
08-16 10:30:09.669  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:30:09.670  6149  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:30:09.670  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:30:09.671  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 10:30:09.671  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 10:30:09.675  6149  6212 D BluetoothLeScanner: could not find callback wrapper
08-16 10:30:09.675  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 10:30:09.675  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:30:09.675  6149  6212 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24f209f not in the list
08-16 10:30:09.675  6149  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:30:09.675  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:30:09.676  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 10:30:09.677  6149  6212 D BluetoothLeScanner: could not find callback wrapper
08-16 10:30:09.677  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 10:30:09.677  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 10:30:09.677  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:30:09.677  6149  6212 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24f209f not in the list
08-16 10:30:09.677  6149  6212 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 10:30:09.677  6149  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:30:09.677  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:30:09.677  6149  6212 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d887a3e not in the list
08-16 10:30:09.679  6149  6212 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 10:30:09.679  6149  6212 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@148f27bb added. We now have 3 listener(s)
08-16 10:30:09.681  1037  2037 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 10:30:09.684  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 10:30:09.684  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 10:30:09.685  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 10:30:09.685  6149  6212 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 10:30:09.685  6149  6212 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14b114d8 added. We now have 4 listener(s)
08-16 10:30:09.685  6149  6212 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 10:30:09.688  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 10:30:09.692  6149  6212 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 10:30:09.697  6149  6212 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 10:30:09.697  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 10:30:09.697  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 10:30:09.697  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 10:30:09.697  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 10:30:09.697  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 10:30:09.697  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 10:30:09.697  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 10:30:09.701  6149  6212 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 10:30:09.701  6149  6212 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 10:30:09.703  6149  6149 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 10:30:09.705  6149  6149 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 10:30:09.706  6149  6212 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 10:30:09.706  6149  6212 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 10:30:09.707  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 10:30:09.707  6149  6212 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 10:30:09.707  6149  6212 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 10:30:09.710  6149  6212 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 10:30:09.712  1037  2034 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 10:30:09.717  6149  6212 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-16 10:30:09.718  6149  6212 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-16 10:30:09.720  6149  6212 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 10:30:09.721  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 10:30:09.722  6149  6212 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-16 10:30:09.768  1037  1523 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-57 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1837572760] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-16 10:30:09.780  1037  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-57 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1837572748] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-16 10:30:09.780  1037  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-16 10:30:12.731  6149  6212 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 10:30:12.731  6149  6212 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 10:30:12.731  6149  6212 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 10:30:12.741  6149  6212 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 10:30:12.741  6149  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:30:12.741  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 10:30:12.741  6149  6212 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 10:30:12.741  6149  6212 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@148f27bb removed from the list
08-16 10:30:12.741  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:30:12.742  6149  6212 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14b114d8 removed from the list
08-16 10:30:12.742  6149  6212 D io.jxcore.node.ConnectivityMonitor: stop
08-16 10:30:12.742  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:30:12.743  6149  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:30:12.743  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:30:12.744  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 10:30:12.744  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 10:30:12.745  6149  6212 D BluetoothLeScanner: could not find callback wrapper
08-16 10:30:12.745  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 10:30:12.745  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:30:12.745  6149  6212 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14b114d8 not in the list
08-16 10:30:12.745  6149  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:30:12.745  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:30:12.746  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 10:30:12.748  6149  6212 D BluetoothLeScanner: could not find callback wrapper
08-16 10:30:12.748  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 10:30:12.748  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 10:30:12.748  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:30:12.748  6149  6212 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14b114d8 not in the list
08-16 10:30:12.748  6149  6212 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 10:30:12.748  6149  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:30:12.748  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:30:12.748  6149  6212 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@148f27bb not in the list
08-16 10:30:12.749  6149  6212 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 10:30:12.749  614,9  6212 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c8ea684 added. We now have 3 listener(s)
,08-16 10:30:12.753  1037  2000 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 10:30:12.756  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 10:30:12.757  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 10:30:12.757  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 10:30:12.757  6149  6212 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 10:30:12.757  6149  6212 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d914e6d added. We now have 4 listener(s)
08-16 10:30:12.757  6149  6212 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 10:30:12.758  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 10:30:12.763  6149  6212 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 10:30:12.768  6149  6212 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 10:30:12.768  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 10:30:12.768  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 10:30:12.768  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 10:30:12.768  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 10:30:12.768  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 10:30:12.768  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 10:30:12.768  6149  6212 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 10:30:12.770  6149  6212 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 10:30:12.770  6149  6212 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 10:30:12.773  6149  6149 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 10:30:12.775  6149  6149 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 10:30:12.777  6149  6212 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 10:30:12.777  6149  6212 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 10:30:12.778  6149  6212 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 10:30:12.778  6149  6212 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 10:30:12.778  6149  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:30:12.778  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 10:30:12.778  6149  6212 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 10:30:12.778  6149  6212 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c8ea684 removed from the list
08-16 10:30:12.778  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:30:12.778  6149  6212 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d914e6d removed from the list
08-16 10:30:12.779  6149  6212 D io.jxcore.node.ConnectivityMonitor: stop
08-16 10:30:12.779  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:30:12.780  6149  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:30:12.780  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:30:12.781  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 10:30:12.781  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 10:30:12.781  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:30:12.781  6149  6212 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d914e6d not in the list
08-16 10:30:12.781  6149  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:30:12.781  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:30:12.782  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 10:30:12.782  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 10:30:12.782  6149  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:30:12.782  6149  6212 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d914e6d not in the list
08-16 10:30:12.783  6149  6212 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 10:30:12.783  6149  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:30:12.783  6149  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:30:12.783  6149  6212 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c8ea684 not in the list
08-16 10:30:12.,796  1037  1523 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-57 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1837569732] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 10:30:12.797  1037  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-57 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1837569731] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 10:30:12.797  1037  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-16 10:30:15.820  1037  1523 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-57 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3007] from screen [on:0 period:-1837566708] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-16 10:30:15.823  1037  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-57 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1837566705] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 10:30:15.823  1037  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-16 10:30:17.786  6149  6212 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,08-16 10:30:17.786  6149  6212 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-16 10:30:17.787  6149  6212 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-16 10:30:17.787  6149  6212 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 10:30:17.788  6149  6212 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,08-16 10:30:17.798  6149  6212 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-16 10:30:18.848  1037  1523 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-57 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1837563680] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 10:30:18.852  1037  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-57 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1837563676] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 10:30:18.852  1037  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-16 10:30:21.878  1037  1523 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-57 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1837560651] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-16 10:30:21.888  1037  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-57 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1837560640] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-16 10:30:21.888  1037  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-16 10:30:24.823  6149  7894 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 823, name: My test thread name)
,08-16 10:30:24.912  1037  1523 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-57 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3007] from screen [on:0 period:-1837557616] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 10:30:24.915  1037  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-57 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1837557613] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 10:30:24.915  1037  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-16 10:30:26.819  6149  6212 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 823
,08-16 10:30:26.820  6149  6212 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 823, name: My test thread name)
,08-16 10:30:26.836  6149  7895 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 824, name: My test thread name)
08-16 10:30:26.836  6149  7895 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 824, thread name: My test thread name)
08-16 10:30:26.836  6149  7895 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 824, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
08-16 10:30:26.841  6149  6212 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-16 10:30:26.847  6149  7896 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 828, name: My test thread name)
08-16 10:30:26.848  6149  7896 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 828, thread name: My test thread name): Test exception.
08-16 10:30:26.848  6149  7896 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 828, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
08-16 10:30:26.852  6149  6212 I jxcore-log: Total number of executed tests:  82
08-16 10:30:26.852  6149  6212 I jxcore-log: 
08-16 10:30:26.852  6149  6212 I jxcore-log: Number of passed tests:  81
08-16 10:30:26.852  6149  6212 I jxcore-log: 
08-16 10:30:26.852  6149  6212 I jxcore-log: Number of failed tests:  1
08-16 10:30:26.852  6149  6212 I jxcore-log: 
08-16 10:30:26.852  6149  6212 I jxcore-log: Number of ignored tests:  0
08-16 10:30:26.852  6149  6212 I jxcore-log: 
08-16 10:30:26.853  6149  6212 I jxcore-log: Total duration:  151156
08-16 10:30:26.853  6149  6212 I jxcore-log: 
08-16 10:30:26.853  6149  6212 I jxcore-log: Failures: 
08-16 10:30:26.853  6149  6212 I jxcore-log:  mCurrentOperation should be null1
08-16 10:30:26.853  6149  6212 I jxcore-log: Expected: is null
08-16 10:30:26.853  6149  6212 I jxcore-log:      but: was <Start operation: Should start/stop everything>
08-16 10:30:26.853  6149  6212 I jxcore-log: 
08-16 10:30:26.853  6149  6212 I jxcore-log: 
08-16 10:30:26.853  6149  6212 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-16 10:30:26.853  6149  6212 I jxcore-log: 
08-16 10:30:26.871  6149  6212 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 10:30:26.871  6149  6212 I jxcore-log: 
,08-16 10:30:26.877  6149  6212 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 10:30:26.877  6149  6212 I jxcore-log: 
08-16 10:30:26.882  6149  6212 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 10:30:26.882  6149  6212 I jxcore-log: 
08-16 10:30:26.884  6149  6212 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 10:30:26.884  6149  6212 I jxcore-log: 
08-16 10:30:26.885  6149  6212 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 10:30:26.885  6149  6212 I jxcore-log: 
08-16 10:30:26.887  6149  6212 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 10:30:26.887  6149  6212 I jxcore-log: 
08-16 10:30:26.894  6149  6149 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-16 10:30:26.898  6149  6212 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 10:30:26.898  6149  6212 I jxcore-log: 
08-16 10:30:26.900  6149  6212 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 10:30:26.900  6149  6212 I jxcore-log: 
08-16 10:30:26.901  6149  6212 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 10:30:26.901  6149  6212 I jxcore-log: 
08-16 10:30:26.902  6149  6212 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 10:30:26.902  6149  6212 I jxcore-log: 
08-16 10:30:26.903  6149  6212 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 10:30:26.903  6149  6212 I jxcore-log: 
08-16 10:30:26.904  6149  6212 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 10:30:26.904  6149  6212 I jxcore-log: 
08-16 10:30:26.906  6149  6212 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 10:30:26.906  6149  6212 I jxcore-log: 
08-16 10:30:26.906  6149  6212 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 10:30:26.906  6149  6212 I jxcore-log: 
08-16 10:30:26.907  6149  6212 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 10:30:26.907  6149  6212 I jxcore-log: 
08-16 10:30:26.908  6149  6212 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 10:30:26.908  6149  6212 I jxcore-log: 
08-16 10:30:26.909  6149  6212 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 10:30:26.909  6149  6212 I jxcore-log: 
08-16 10:30:26.910  6149  6212 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 10:30:26.910  6149  6212 I jxcore-log: 
08-16 10:30:26.911  6149  6212 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 10:30:26.911  6149  6212 I jxcore-log: 
08-16 10:30:26.912  6149  6212 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 10:30:26.912  6149  6212 I jxcore-log: 
08-16 10:30:26.913  6149  6212 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 10:30:26.913  6149  6212 I jxcore-log: 
08-16 10:30:26.913  6149  6212 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 10:30:26.913  6149  6212 I jxcore-log: 
08-16 10:30:26.914  6149  6212 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 10:30:26.914  6149  6212 I jxcore-log: 
08-16 10:30:26.915  6149  6212 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 10:30:26.915  6149  6212 I jxcore-log: 
08-16 10:30:,26.916  6149  6212 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 10:30:26.916  6149  6212 I jxcore-log: 
08-16 10:30:26.916  6149  6212 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 10:30:26.916  6149  6212 I jxcore-log: 
08-16 10:30:26.917  6149  6212 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 10:30:26.917  6149  6212 I jxcore-log: 
08-16 10:30:26.918  6149  6212 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 10:30:26.918  6149  6212 I jxcore-log: 
,08-16 10:30:26.924  6149  6212 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 10:30:26.924  6149  6212 I jxcore-log: 
08-16 10:30:26.925  6149  6212 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 10:30:26.925  6149  6212 I jxcore-log: 
08-16 10:30:26.926  6149  6212 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 10:30:26.926  6149  6212 I jxcore-log: 
08-16 10:30:26.927  6149  6212 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 10:30:26.927  6149  6212 I jxcore-log: 
08-16 10:30:26.927  6149  6212 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 10:30:26.927  6149  6212 I jxcore-log: 
08-16 10:30:26.928  6149  6212 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 10:30:26.928  6149  6212 I jxcore-log: 
08-16 10:30:26.929  6149  6212 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 10:30:26.929  6149  6212 I jxcore-log: 
08-16 10:30:26.930  6149  6212 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 10:30:26.930  6149  6212 I jxcore-log: 
08-16 10:30:26.931  6149  6212 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 10:30:26.931  6149  6212 I jxcore-log: 
08-16 10:30:26.990  6149  7894 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 823, name: My test thread name), during the lifetime of the thread the total number of bytes read was 187 and the total number of bytes written 187
,08-16 10:30:27.192  7897  7897 D AndroidRuntime: 
08-16 10:30:27.192  7897  7897 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-16 10:30:27.197  7897  7897 D AndroidRuntime: CheckJNI is OFF
08-16 10:30:27.314  7897  7897 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-16 10:30:27.324  1037  1104 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-16 10:30:27.324  1037  1104 I ActivityManager: Killing 6149:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,08-16 10:30:27.394  1037  1999 I WindowState: WIN DEATH: Window{3f86b47f u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-16 10:30:27.394  1037  1529 D WifiService: Client connection lost with reason: 4
08-16 10:30:27.401  1037  1999 D InputDispatcher: Window went away: Window{3f86b47f u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-16 10:30:27.553  1037  1104 I ActivityManager:   Force finishing activity ActivityRecord{139e86d8 u0 com.test.thalitest/.MainActivity t6}
,08-16 10:30:27.606   331   340 E GBMv2   : DFP En is all cleared set to be enabled
,08-16 10:30:27.614  1037  2037 W ActivityManager: Spurious death for ProcessRecord{7b4f658 6149:com.test.thalitest/u0a118}, curProc for 6149: null
08-16 10:30:27.615  1037  1125 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-16 10:30:27.616  1037  1125 I ActivityManager:   Force finishing activity ActivityRecord{139e86d8 u0 com.test.thalitest/.MainActivity t6 f}
08-16 10:30:27.616  1037  1125 W ActivityManager: Duplicate finish request for ActivityRecord{139e86d8 u0 com.test.thalitest/.MainActivity t6 f}
,08-16 10:30:27.650  2019  2019 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-16 10:30:27.652  2019  2019 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
,08-16 10:30:27.655  1928  3919 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-16 10:30:27.656  1928  3919 D SplitWindowPolicy: topRunningActivity=ActivityInfo{30ed9689 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-16 10:30:27.657  1928  1943 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-16 10:30:27.657  1928  1943 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2ffd068e co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-16 10:30:27.659  2019  2019 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-16 10:30:27.660  2019  2110 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
08-16 10:30:27.664  1588  1588 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,08-16 10:30:27.672  1037  1413 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-16 10:30:27.688  1982  1982 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
,08-16 10:30:27.689  3683  3683 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-16 10:30:27.689  2465  2646 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-16 10:30:27.692  7141  7141 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-16 10:30:27.692  7141  7141 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-16 10:30:27.707  4540  4540 I art     : Explicit concurrent mark sweep GC freed 8115(468KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 29MB/45MB, paused 551us total 73.810ms
08-16 10:30:27.728  1037  1927 V SIM_STK : Menu title from STK is T-Mobile
08-16 10:30:27.738  2019  2019 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
,08-16 10:30:27.740  1891  1891 D ActionManagerService: notifyUserLog: 1000003
08-16 10:30:27.740  3683  4416 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-16 10:30:27.745  3722  3722 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-16 10:30:27.750  2019  2019 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-16 10:30:27.755  4425  4425 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-16 10:30:27.755  1802  1802 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-16 10:30:27.755  4425  4425 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-16 10:30:27.755  4425  4425 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-16 10:30:27.755  4425  4425 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-16 10:30:27.755  4425  4425 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-16 10:30:27.755  4425  4425 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 10:30:27.756  4425  4425 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-16 10:30:27.756  4425  4425 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-16 10:30:27.756  4425  4425 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 10:30:27.756  4425  4425 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 10:30:27.756  4425  4425 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-16 10:30:27.756  4425  4425 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-16 10:30:27.759  2019  2019 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-16 10:30:27.764  1037  1102 W InputMethodInfo: Duplicated subtype definition found: , voice
08-16 10:30:27.770  1588  1588 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
,08-16 10:30:27.779  2019  2019 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-16 10:30:27.786  1588  1635 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-16 10:30:27.786  1588  1635 D KeyguardModel: createShortcutInfo...
08-16 10:30:27.789  2019  2019 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
,08-16 10:30:27.796  2179  2179 I ConfigService: onCreate
08-16 10:30:27.797  1891  1891 D ActionManagerService: notifyUserLog: 1000004
08-16 10:30:27.797  2179  2179 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-16 10:30:27.798  1588  1588 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-16 10:30:27.798  1588  1588 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-16 10:30:27.798  3683  4416 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-16 10:30:27.799  1588  1635 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-16 10:30:27.799  1588  1635 D KeyguardModel: createShortcutInfo...
08-16 10:30:27.802  1802  1802 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,08-16 10:30:27.804  3683  3699 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-16 10:30:27.807  1588  1635 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-16 10:30:27.808  1588  1635 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 10:30:27.808  1588  1635 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-16 10:30:27.810  2019  2019 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-16 10:30:27.810  2019  2019 I GBoardWebViewUtils: , create_time: 1430832262123
08-16 10:30:27.810  2019  2019 I GBoardWebViewUtils: , expire_time: 0
08-16 10:30:27.810  2019  2019 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-16 10:30:27.810  2019  2019 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-16 10:30:27.810  2019  2019 I GBoardWebViewUtils: , display: false
08-16 10:30:27.810  2019  2019 I GBoardWebViewUtils: , animation: false }
08-16 10:30:27.810  2019  2019 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-16 10:30:27.810  2019  2019 I GBoardWebViewUtils: , create_time: 1430832262287
08-16 10:30:27.810  2019  2019 I GBoardWebViewUtils: , expire_time: 0
08-16 10:30:27.810  2019  2019 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-16 10:30:27.810  2019  2019 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-16 10:30:27.810  2019  2019 I GBoardWebViewUtils: , display: false
08-16 10:30:27.810  2019  2019 I GBoardWebViewUtils: , animation: false }
08-16 10:30:27.810  2019  2019 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1471007225619
08-16 10:30:27.810  2019  2019 I GBoardWebViewUtils: , create_time: 1471007226523
08-16 10:30:27.810  2019  2019 I GBoardWebViewUtils: , expire_time: 0
08-16 10:30:27.810  2019  2019 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide.html?id=guide_1111111111116_1471007225619&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-16 10:30:27.810  2019  2019 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-16 10:30:27.810  2019  2019 I GBoardWebViewUtils: , display: false
08-16 10:30:27.810  2019  2019 I GBoardWebViewUtils: , animation: false }
08-16 10:30:27.812  2179  2179 I ConfigService: onBind returning update interface
08-16 10:30:27.813  2179  2179 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-16 10:30:27.813  2179  2179 I ConfigService: onBind returning config service
,08-16 10:30:27.817  1588  1635 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-16 10:30:27.821  1855  1855 D SplitUIManager: split_name #11 / not available #0
08-16 10:30:27.822  1855  1855 D SplitUIService: removed split : 
08-16 10:30:27.823  2179  2179 I ConfigService: onDestroy
08-16 10:30:27.830  1588  1635 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-16 10:30:27.830  1588  1635 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
,08-16 10:30:27.831  2019  7930 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-16 10:30:27.833  1802  7932 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-16 10:30:27.834  1588  1635 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-16 10:30:27.834  1588  1635 D KeyguardModel: createShortcutInfo...
08-16 10:30:27.848  1588  1635 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-16 10:30:27.848  1588  1635 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-16 10:30:27.851  2019  2019 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-16 10:30:27.851  2019  2019 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-16 10:30:27.853  1588  1635 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-16 10:30:27.854  1588  1635 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-16 10:30:27.858  1855  1855 D SplitUIManager: split_name #11 / not available #0
08-16 10:30:27.858  1855  1855 I SplitUIService: split app #11
,08-16 10:30:27.860  1037  1053 V SIM_STK : Menu title from STK is T-Mobile
08-16 10:30:27.860  1037  1053 V SIM_STK : Menu title from STK is T-Mobile
08-16 10:30:27.869  1037  1037 I art     : Explicit concurrent mark sweep GC freed 32340(2027KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 2.776ms total 229.930ms
08-16 10:30:27.869  1588  1635 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-16 10:30:27.869  1588  1635 D KeyguardModel: createShortcutInfo...
08-16 10:30:27.870  1037  1125 I art     : WaitForGcToComplete blocked for 116.648ms for cause Explicit
,08-16 10:30:27.879  1588  1635 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 10:30:27.879  1588  1635 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-16 10:30:27.879  1588  1635 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-16 10:30:27.879  1588  1635 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-16 10:30:27.880  1588  1635 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-16 10:30:27.880  1588  1635 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,08-16 10:30:27.886  1588  1635 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-16 10:30:27.886  1588  1635 D KeyguardModel: createShortcutInfo...
08-16 10:30:27.888  5477  7939 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
08-16 10:30:27.890  2179  2205 I art     : Explicit concurrent mark sweep GC freed 8738(539KB) AllocSpace objects, 6(96KB) LOS objects, 52% free, 29MB/61MB, paused 573us total 32.140ms
,08-16 10:30:27.919  1802  7941 I PeopleContactsSync: CP2 sync disabled
08-16 10:30:27.921  1588  1588 D KeyguardModel: handleShortcutListChanged...
08-16 10:30:27.921  1588  1588 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,08-16 10:30:27.923  1037  1945 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-16 10:30:27.923  1802  4684 I Icing   : doRemovePackageData com.test.thalitest
08-16 10:30:27.924  7141  7141 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-16 10:30:27.924  7141  7141 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-16 10:30:27.925  7141  7141 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-16 10:30:27.925  7141  7141 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-16 10:30:27.925  7141  7141 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-16 10:30:27.925  7141  7141 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-16 10:30:27.925  7141  7141 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-16 10:30:27.925  7141  7141 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-16 10:30:27.925  7141  7141 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-16 10:30:27.925  7141  7141 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-16 10:30:27.925  7141  7141 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-16 10:30:27.927  2019  2019 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-16 10:30:27.933  1588  1635 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-16 10:30:27.933  1588  1635 D KeyguardModel: createShortcutInfo...
08-16 10:30:27.935  1588  1635 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-16 10:30:27.935  1588  1635 D KeyguardModel: createShortcutInfo...
08-16 10:30:27.936  1588  1635 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-16 10:30:27.936  1588  1635 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-16 10:30:27.936   325   392 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-16 10:30:27.936  3129  7942 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-16 10:30:27.937  1037  1523 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-57 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1837554591] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 10:30:27.937  1588  1635 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-16 10:30:27.938  1588  1635 D KeyguardModel: createShortcutInfo...
08-16 10:30:27.938  1037  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-57 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1837554590] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 10:30:27.938  1037  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-16 10:30:27.938  1588  1635 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-16 10:30:27.939  1588  1635 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,08-16 10:30:27.939  1037  1963 V SIM_STK : Menu title from STK is T-Mobile
08-16 10:30:27.940  7488  7488 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
08-16 10:30:27.947  1588  1635 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-16 10:30:27.947  1588  1635 D KeyguardModel: createShortcutInfo...
08-16 10:30:27.949  1588  1635 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-16 10:30:27.949  1588  1635 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-16 10:30:27.949  2376  7943 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-16 10:30:27.958  1588  1635 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-16 10:30:27.958  1588  1635 D KeyguardModel: createShortcutInfo...
,08-16 10:30:27.982  1037  1872 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=7946 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-16 10:30:27.987  1588  1588 D KeyguardModel: handleShortcutListChanged...
08-16 10:30:27.987  1588  1588 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-16 10:30:27.999  1802  7940 W GmsApplication: Using Auth Proxy for data requests.
,08-16 10:30:28.013  1037  1037 D administrator: Handling package changes for user 0
08-16 10:30:28.016  1802  7940 W GmsApplication: Using Auth Proxy for data requests.
08-16 10:30:28.021  2019  2019 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,08-16 10:30:28.025  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 10:30:28.026  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-16 10:30:28.027  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-16 10:30:28.029  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-16 10:30:28.030  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-16 10:30:28.050  2019  2019 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-16 10:30:28.050  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 10:30:28.051  1037  1120 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1a2ecdf0 u0 com.lge.launcher2/.Launcher t5} time:467182
,08-16 10:30:28.056  2019  2178 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-16 10:30:28.057  2019  2178 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-16 10:30:28.065  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-16 10:30:28.065  2019  2019 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-16 10:30:28.065  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-16 10:30:28.073  7946  7946 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 10:30:28.073  7946  7946 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 10:30:28.074  2019  2019 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-16 10:30:28.074  7946  7946 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-16 10:30:28.074  7946  7946 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-16 10:30:28.075  2597  2597 D [Concierge]Service: onStartCommand(). Type : 8
08-16 10:30:28.075  2597  2597 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-16 10:30:28.076  2597  2597 D [Concierge]Service: Update widget ID : 11
08-16 10:30:28.078  2019  2019 D [Concierge]WidgetView: change position of spinner
08-16 10:30:28.079  2597  2597 D [Concierge]Service: onStartCommand(). Type : 0
08-16 10:30:28.080  2019  2019 I [Concierge]WidgetView: initWebView(). Time : 1471336228080
,08-16 10:30:28.096  1037  1037 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-16 10:30:28.096  1037  1037 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-16 10:30:28.097  1037  1037 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-16 10:30:28.100  2019  2019 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 8649025
08-16 10:30:28.101  2019  2019 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-16 10:30:28.101  2019  2019 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-16 10:30:28.101  1037  1563 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-16 10:30:28.104  2019  2019 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@204de466
08-16 10:30:28.104  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-16 10:30:28.105  2019  2019 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-16 10:30:28.105  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 10:30:28.110  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
,08-16 10:30:28.110  2019  2019 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-16 10:30:28.111  2019  2019 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1471335788326, New one : 1471336228080
08-16 10:30:28.111  2019  2019 D [Concierge]WidgetView: Unregister all receivers
08-16 10:30:28.111  2019  2019 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-16 10:30:28.112  2019  2019 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-16 10:30:28.112  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 10:30:28.113  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-16 10:30:28.115  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-16 10:30:28.116  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-16 10:30:28.117  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-16 10:30:28.118  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-16 10:30:28.122  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-16 10:30:28.122  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 10:30:28.137  7946  7946 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-16 10:30:28.146  7946  7946 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
08-16 10:30:28.167  7946  7946 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-16 10:30:28.173  1037  1102 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-16 10:30:28.180  2019  2019 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-16 10:30:28.185  1037  1102 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-16 10:30:28.186  7946  7946 D LgDataFeature: LgDataFeature() Constructor: none
08-16 10:30:28.186  7946  7946 D LgDataFeature: LgDataFeature() Constructor Done, null
08-16 10:30:28.187  2019  2019 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-16 10:30:28.188  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
,08-16 10:30:28.190  2019  2019 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-16 10:30:28.191  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 10:30:28.194  1037  1125 I art     : Explicit concurrent mark sweep GC freed 10997(589KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 3.791ms total 314.208ms
08-16 10:30:28.208  2019  2019 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2d4df730 time:467339
,08-16 10:30:28.237  7946  7946 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,08-16 10:30:28.247  1037  1872 I ActivityManager: Killing 7619:com.qualcomm.timeservice/1000 (adj 15): empty #17
08-16 10:30:28.267  7897  7897 D AndroidRuntime: Shutting down VM
,08-16 10:30:28.304  2019  2019 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-16 10:30:28.339  2019  2893 I GBoardtInterface: onReloaded()
,08-16 10:30:28.341  1982  1982 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-16 10:30:28.341  1982  1982 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
08-16 10:30:28.341  2019  2019 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-16 10:30:28.341  1037  1945 W libprocessgroup: failed to open /acct/uid_1000/pid_7619/cgroup.procs: No such file or directory
08-16 10:30:28.343  1982  1982 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
08-16 10:30:28.344  3683  3699 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-16 10:30:28.345  3722  3722 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-16 10:30:28.375  1037  1560 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=7971 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-16 10:30:28.377  3683  4415 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,08-16 10:30:28.383  1891  1891 D ActionManagerService: notifyUserLog: 1000001
08-16 10:30:28.384  3683  4416 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-16 10:30:28.384  3683  4416 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-16 10:30:28.387  1891  1891 D ActionManagerService: notifyUserLog: 1000001
08-16 10:30:28.388  3683  4416 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
,08-16 10:30:28.388  3683  4416 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
,08-16 10:30:28.388  3683  4416 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-16 10:30:28.388  3683  4416 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-16 10:30:28.389  3683  3699 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-16 10:30:28.391  2019  2019 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-16 10:30:28.391  2019  2019 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-16 10:30:28.393  2019  2019 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-16 10:30:28.393  2019  2019 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-16 10:30:28.394  2019  2019 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide2.html?id=guide_1111111111116_1471007225619&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-16 10:30:28.394  2019  2019 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide2.html?id=guide_1111111111116_1471007225619&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
,08-16 10:30:28.440  7971  7971 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
,08-16 10:30:28.440  7971  7971 W LG Account v2.2: No ProfileInfo entries
08-16 10:30:28.440  7971  7971 I LG Account v2.2: isEnabled: false
08-16 10:30:28.440  7971  7971 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-16 10:30:28.440  7971  7971 I Feature : [Lifetracker]Country: EU
08-16 10:30:28.441  7971  7971 I Feature : [Lifetracker]Operator: OPEN
08-16 10:30:28.441  7971  7971 I Feature : [Lifetracker]Ranking support: false
08-16 10:30:28.441  7971  7971 I Feature : [Lifetracker]Comfort support: false
08-16 10:30:28.441  7971  7971 I Feature : [Lifetracker]Accessory: true
08-16 10:30:28.441  7971  7971 I Feature : [Lifetracker]Health device: true
08-16 10:30:28.441  7971  7971 I Feature : [Lifetracker]Extra Pedometer: false
08-16 10:30:28.441  7971  7971 I Feature : [Lifetracker]Blood glucose device: false
08-16 10:30:28.441  7971  7971 I Feature : [Lifetracker]Device Number: 3
08-16 10:30:28.441  7971  7971 D CoreEventReceiver: [onReceive] Action=android.intent.action.PACKAGE_REMOVED
,08-16 10:30:28.475  1037  1901 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=7990 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-16 10:30:28.476  1037  1901 I ActivityManager: Killing 7637:com.android.calendar/u0a13 (adj 15): empty #17
08-16 10:30:28.582  1037  1125 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8009 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-16 10:30:28.582  1037  2037 W libprocessgroup: failed to open /acct/uid_10013/pid_7637/cgroup.procs: No such file or directory
08-16 10:30:28.604  7990  7990 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-16 10:30:28.606  7990  7990 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-16 10:30:28.606  7990  7990 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 10:30:28.606  7990  7990 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-16 10:30:28.607  7990  7990 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-16 10:30:28.608  7990  7990 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-16 10:30:28.632  1037  2034 I ActivityManager: Killing 6716:com.google.android.setupwizard/u0a46 (adj 15): empty #17

```
