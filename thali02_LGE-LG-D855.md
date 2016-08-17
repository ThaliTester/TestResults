#### Test 808075736be4f0c_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-17 13:13:00.063  1602  1602 I [SystemUI]Clock: called onTimeUpdated()
08-17 13:13:00.072  1602  1602 I LgeClockWidgetControlView: called onTimeUpdated()
08-17 13:13:00.072  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-17 13:13:00.075  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-17 13:13:00.077  1602  1602 D KeyguardUpdateMonitor: handleTimeUpdate
,08-17 13:13:37.844  6868  6868 D AndroidRuntime: 
08-17 13:13:37.844  6868  6868 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-17 13:13:37.850  6868  6868 D AndroidRuntime: CheckJNI is OFF
08-17 13:13:37.974  6868  6868 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-17 13:13:37.979  1036  2033 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-17 13:13:37.990  1940  4267 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-17 13:13:37.994  1036  2033 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-17 13:13:37.995  1036  2033 D ActivityManager: setTaskToReturnTo : TaskRecord{19e8c0d1 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-17 13:13:37.995  1036  2033 D ActivityManager: setTaskToReturnTo : TaskRecord{19e8c0d1 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-17 13:13:37.996  1036  2033 D WindowStateEx: AppWindowTokenEx init.. 
08-17 13:13:37.997   341   357 E GBMv2   : DFP En is all cleared set to be enabled
08-17 13:13:38.031  1036  2033 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6887 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-17 13:13:38.032  6868  6868 D AndroidRuntime: Shutting down VM
08-17 13:13:38.106  1940  1955 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-17 13:13:38.107  1940  1955 D SplitWindowPolicy: topRunningActivity=ActivityInfo{32b45281 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-17 13:13:38.108  1940  1956 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-17 13:13:38.110  1940  1956 D SplitWindowPolicy: topRunningActivity=ActivityInfo{18b09f26 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-17 13:13:38.190  6887  6887 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
,08-17 13:13:38.299  6887  6887 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-17 13:13:38.308  6887  6887 I LibraryLoader: Loading: webviewchromium
08-17 13:13:38.311  6887  6887 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 3241-3245)
,08-17 13:13:38.311  6887  6887 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-17 13:13:38.329  6887  6887 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1e7ba0d7}
,08-17 13:13:38.330  6887  6887 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-17 13:13:38.331  6887  6887 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-17 13:13:38.341  6887  6887 I BrowserStartupController: Initializing chromium process, renderers=0
08-17 13:13:38.342  6887  6887 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-17 13:13:38.356  6887  6887 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-17 13:13:38.357  6887  6887 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-17 13:13:38.358  6887  6887 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-17 13:13:38.371   321  2155 V AudioPolicyService: registerClient() client 0xb100b640, uid 10118
,08-17 13:13:38.379  1036  1118 D BluetoothManagerService: Message: 20
08-17 13:13:38.379  1036  1118 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5a5aed3:true
08-17 13:13:38.391  6887  6887 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-17 13:13:38.391  6887  6887 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-17 13:13:38.391  6887  6887 I Adreno-EGL: Build Date: 12/12/14 금
08-17 13:13:38.391  6887  6887 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-17 13:13:38.391  6887  6887 I Adreno-EGL: Remote Branch: 
08-17 13:13:38.391  6887  6887 I Adreno-EGL: Local Patches: 
08-17 13:13:38.391  6887  6887 I Adreno-EGL: Reconstruct Branch: 
,08-17 13:13:38.470  6887  6922 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
08-17 13:13:38.471  6887  6887 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,08-17 13:13:38.511  6887  6887 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-17 13:13:38.516  6887  6887 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-17 13:13:38.519  6887  6887 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-17 13:13:38.523  6887  6887 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-17 13:13:38.523  6887  6887 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,08-17 13:13:38.539  6887  6887 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-17 13:13:38.546  6887  6887 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-17 13:13:38.546  6887  6887 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-17 13:13:38.582  6887  6936 D OpenGLRenderer: Render dirty regions requested: true
08-17 13:13:38.583  6887  6936 I OpenGLRenderer: Initialized EGL, version 1.4
,08-17 13:13:38.590  6887  6936 D OpenGLRenderer: Enabling debug mode 0
08-17 13:13:38.605  1036  1114 W ActivityManager: Activity pause timeout for ActivityRecord{257ff736 u0 com.test.thalitest/.MainActivity t6}
,08-17 13:13:38.613  6887  6887 D Atlas   : Validating map...
08-17 13:13:38.619  1036  1051 D SplitWindow: check instance of lgWin Window{356e8135 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-17 13:13:38.686  6887  6934 D LgDataFeature: LgDataFeature() Constructor: none
,08-17 13:13:38.686  6887  6934 D LgDataFeature: LgDataFeature() Constructor Done, null
08-17 13:13:38.759  1036  1119 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +654ms (total +762ms)
08-17 13:13:38.759  6887  6887 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1beae992 time:263693
,08-17 13:13:38.762  1036  1119 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{257ff736 u0 com.test.thalitest/.MainActivity t6} time:263696
08-17 13:13:38.883  6887  6887 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-17 13:13:38.883  6887  6887 I chromium: 
,08-17 13:13:38.905  6887  6887 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-17 13:13:38.999  6887  6934 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-17 13:13:38.999  6887  6934 I chromium: 
,08-17 13:13:39.146  6887  6948 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435145728
,08-17 13:13:39.161  6887  6948 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-17 13:13:39.161  6887  6948 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-17 13:13:39.161  6887  6948 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-17 13:13:39.161  6887  6948 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-17 13:13:39.161  6887  6948 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-17 13:13:39.161  6887  6948 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2584d9b6 added. We now have 1 listener(s)
08-17 13:13:39.167  1036  1957 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-17 13:13:39.173  6887  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-17 13:13:39.176  6887  6948 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-17 13:13:39.178  6887  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 13:13:39.178  6887  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-17 13:13:39.186  6887  6948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-17 13:13:39.186  6887  6948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-17 13:13:39.186  6887  6948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-17 13:13:39.186  6887  6948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-17 13:13:39.186  6887  6948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-17 13:13:39.186  6887  6948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-17 13:13:39.186  6887  6948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-17 13:13:39.186  6887  6948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-17 13:13:39.186  6887  6948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-17 13:13:39.186  6887  6948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-17 13:13:39.186  6887  6948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-17 13:13:39.186  6887  6948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-17 13:13:39.186  6887  6948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-17 13:13:39.186  6887  6948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-17 13:13:39.186  6887  6948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bb1bd8d added. We now have 1 listener(s)
08-17 13:13:39.186  6887  6948 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 13:13:39.195  1036  1443 D WifiService: New client listening to asynchronous messages
,08-17 13:13:39.200  6887  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-17 13:13:39.201  6887  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-17 13:13:39.203  6887  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-17 13:13:39.203  6887  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-17 13:13:39.203  6887  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-17 13:13:39.207  6887  6948 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 13:13:39.207  1036  1648 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 13:13:39.209  6887  6948 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-17 13:13:39.219  6887  6948 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-17 13:13:39.219  6887  6948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 13:13:39.219  6887  6948 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 13:13:39.219  6887  6948 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 13:13:39.219  6887  6948 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 13:13:39.219  6887  6948 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 13:13:39.219  6887  6948 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 13:13:39.219  6887  6948 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 13:13:39.219  6887  6948 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 13:13:39.220  6887  6948 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-17 13:13:39.220  6887  6948 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 13:13:39.223  6887  6887 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 13:13:39.225  6887  6948 I io.jxcore.node.LifeCycleMonitor: start: OK
08-17 13:13:39.225  6887  6887 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 13:13:39.267  6887  6887 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-17 13:13:39.898   341   359 E GBMv2   : DFP En is all cleared set to be enabled
,08-17 13:13:39.900   341   359 E GBMv2   : Set value is all cleared set the max
08-17 13:13:39.900   341   359 I GBMv2   : DFP Enabled. Ignore VFP set
,08-17 13:13:40.480  6887  6951 W jxcore-log: Initializing JXcore engine
08-17 13:13:40.480  6887  6951 W jxcore-log: JXcore engine is ready
,08-17 13:13:40.506  6951  6951 W Thread-806: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[7404]" dev="sockfs" ino=7404 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-17 13:13:40.506  6951  6951 W Thread-806: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-17 13:13:40.506  6951  6951 W Thread-806: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[7563]" dev="sockfs" ino=7563 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-17 13:13:40.506  6951  6951 W Thread-806: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
,08-17 13:13:40.506  6951  6951 W Thread-806: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[33393]" dev="sockfs" ino=33393 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-17 13:13:40.531  6887  6951 W jxcore-log: Starting JXcore engine
08-17 13:13:40.609  6887  6951 W jxcore-log: Platform android
08-17 13:13:40.609  6887  6951 W jxcore-log: 
08-17 13:13:40.610  6887  6951 W jxcore-log: Process ARCH arm
08-17 13:13:40.610  6887  6951 W jxcore-log: 
,08-17 13:13:40.856  6887  6951 I jxcore-log: JXcore Cordova bridge is ready!
08-17 13:13:40.856  6887  6951 I jxcore-log: 
08-17 13:13:40.857  6887  6951 W jxcore-log: JXcore engine is started

```
