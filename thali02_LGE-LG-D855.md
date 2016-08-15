#### Test 81316179298ded4_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-15 16:22:00.055  1606  1606 I [SystemUI]Clock: called onTimeUpdated()
08-15 16:22:00.064  1606  1606 I LgeClockWidgetControlView: called onTimeUpdated()
08-15 16:22:00.064  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
08-15 16:22:00.067  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
08-15 16:22:00.069  1606  1606 D KeyguardUpdateMonitor: handleTimeUpdate
,08-15 16:22:01.846  6811  6811 D AndroidRuntime: 
08-15 16:22:01.846  6811  6811 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-15 16:22:01.852  6811  6811 D AndroidRuntime: CheckJNI is OFF
08-15 16:22:01.976  6811  6811 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-15 16:22:01.981  1036  1945 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-15 16:22:01.990  1942  3350 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-15 16:22:01.994  1036  1945 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-15 16:22:01.995  1036  1945 D ActivityManager: setTaskToReturnTo : TaskRecord{20211402 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-15 16:22:01.995  1036  1945 D ActivityManager: setTaskToReturnTo : TaskRecord{20211402 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-15 16:22:01.996  1036  1945 D WindowStateEx: AppWindowTokenEx init.. 
08-15 16:22:01.997   340   361 E GBMv2   : DFP En is all cleared set to be enabled
08-15 16:22:02.029  1036  1945 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6826 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-15 16:22:02.035  6811  6811 D AndroidRuntime: Shutting down VM
08-15 16:22:02.082  1942  3350 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-15 16:22:02.082  1942  3350 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1d48c78d co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-15 16:22:02.084  1942  1959 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-15 16:22:02.084  1942  1959 D SplitWindowPolicy: topRunningActivity=ActivityInfo{8d81d42 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-15 16:22:02.147  6826  6826 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-15 16:22:02.241  6826  6826 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-15 16:22:02.253  6826  6826 I LibraryLoader: Loading: webviewchromium
08-15 16:22:02.256  6826  6826 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 8994-8997)
,08-15 16:22:02.256  6826  6826 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-15 16:22:02.271  6826  6826 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {227395c3}
,08-15 16:22:02.272  6826  6826 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-15 16:22:02.273  6826  6826 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-15 16:22:02.282  6826  6826 I BrowserStartupController: Initializing chromium process, renderers=0
,08-15 16:22:02.283  6826  6826 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-15 16:22:02.293  6826  6826 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-15 16:22:02.294   319  1396 V AudioPolicyService: registerClient() client 0xb0410680, uid 10118
,08-15 16:22:02.294  6826  6826 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-15 16:22:02.294  6826  6826 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
,08-15 16:22:02.300  1036  1118 D BluetoothManagerService: Message: 20
08-15 16:22:02.300  1036  1118 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@17d0407c:true
08-15 16:22:02.309  6826  6826 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-15 16:22:02.309  6826  6826 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-15 16:22:02.309  6826  6826 I Adreno-EGL: Build Date: 12/12/14 금
08-15 16:22:02.309  6826  6826 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-15 16:22:02.309  6826  6826 I Adreno-EGL: Remote Branch: 
08-15 16:22:02.309  6826  6826 I Adreno-EGL: Local Patches: 
08-15 16:22:02.309  6826  6826 I Adreno-EGL: Reconstruct Branch: 
,08-15 16:22:02.387  6826  6861 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-15 16:22:02.391  6826  6826 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-15 16:22:02.408  6826  6826 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-15 16:22:02.413  6826  6826 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-15 16:22:02.417  6826  6826 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-15 16:22:02.420  6826  6826 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-15 16:22:02.420  6826  6826 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,08-15 16:22:02.435  6826  6826 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-15 16:22:02.442  6826  6826 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-15 16:22:02.442  6826  6826 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-15 16:22:02.470  6826  6873 D OpenGLRenderer: Render dirty regions requested: true
08-15 16:22:02.470  6826  6873 I OpenGLRenderer: Initialized EGL, version 1.4
08-15 16:22:02.476  6826  6873 D OpenGLRenderer: Enabling debug mode 0
,08-15 16:22:02.486  6826  6826 D Atlas   : Validating map...
,08-15 16:22:02.490  1036  1945 D SplitWindow: check instance of lgWin Window{af6f7d6 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-15 16:22:02.537  6826  6871 D LgDataFeature: LgDataFeature() Constructor: none
,08-15 16:22:02.537  6826  6871 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-15 16:22:02.612  1036  1119 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +531ms (total +614ms)
08-15 16:22:02.613  6826  6826 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@13c6d36e time:179354
,08-15 16:22:02.614  1036  1119 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3dba5113 u0 com.test.thalitest/.MainActivity t6} time:179356
08-15 16:22:02.731  6826  6826 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-15 16:22:02.731  6826  6826 I chromium: 
,08-15 16:22:02.740  6826  6826 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
08-15 16:22:02.927  6826  6884 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435153408
,08-15 16:22:02.944  6826  6884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-15 16:22:02.944  6826  6884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-15 16:22:02.944  6826  6884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-15 16:22:02.944  6826  6884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-15 16:22:02.944  6826  6884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-15 16:22:02.945  6826  6884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@949dcd2 added. We now have 1 listener(s)
08-15 16:22:02.951  1036  1945 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-15 16:22:02.955  6826  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-15 16:22:02.957  6826  6884 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-15 16:22:02.958  6826  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-15 16:22:02.959  6826  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-15 16:22:02.967  6826  6884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-15 16:22:02.967  6826  6884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-15 16:22:02.967  6826  6884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-15 16:22:02.967  6826  6884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-15 16:22:02.967  6826  6884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-15 16:22:02.967  6826  6884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-15 16:22:02.967  6826  6884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-15 16:22:02.967  6826  6884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-15 16:22:02.967  6826  6884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-15 16:22:02.967  6826  6884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-15 16:22:02.967  6826  6884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-15 16:22:02.967  6826  6884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-15 16:22:02.967  6826  6884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-15 16:22:02.967  6826  6884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-15 16:22:02.967  6826  6884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f18059 added. We now have 1 listener(s)
08-15 16:22:02.967  6826  6884 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-15 16:22:02.975  1036  1470 D WifiService: New client listening to asynchronous messages
,08-15 16:22:02.982  6826  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-15 16:22:02.983  6826  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-15 16:22:02.984  6826  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-15 16:22:02.985  6826  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-15 16:22:02.985  6826  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-15 16:22:02.989  6826  6884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-15 16:22:02.990  1036  1787 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-15 16:22:02.993  6826  6884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-15 16:22:03.003  6826  6884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-15 16:22:03.003  6826  6884 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-15 16:22:03.003  6826  6884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 16:22:03.003  6826  6884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-15 16:22:03.003  6826  6884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-15 16:22:03.003  6826  6884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-15 16:22:03.003  6826  6884 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-15 16:22:03.003  6826  6884 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-15 16:22:03.003  6826  6884 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-15 16:22:03.003  6826  6884 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-15 16:22:03.003  6826  6884 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-15 16:22:03.008  6826  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 16:22:03.009  6826  6884 I io.jxcore.node.LifeCycleMonitor: start: OK
08-15 16:22:03.009  6826  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 16:22:03.044  6826  6871 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-15 16:22:03.044  6826  6871 I chromium: 
,08-15 16:22:03.050   340   363 E GBMv2   : DFP En is all cleared set to be enabled
08-15 16:22:03.050   340   363 E GBMv2   : Set value is all cleared set the max
08-15 16:22:03.050   340   363 I GBMv2   : DFP Enabled. Ignore VFP set
08-15 16:22:03.121  6826  6826 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-15 16:22:03.900  6826  6887 W jxcore-log: Initializing JXcore engine
08-15 16:22:03.900  6826  6887 W jxcore-log: JXcore engine is ready
,08-15 16:22:03.947  6887  6887 W Thread-782: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[8937]" dev="sockfs" ino=8937 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-15 16:22:03.947  6887  6887 W Thread-782: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-15 16:22:03.947  6887  6887 W Thread-782: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[10394]" dev="sockfs" ino=10394 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-15 16:22:03.947  6887  6887 W Thread-782: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-15 16:22:03.947  6887  6887 W Thread-782: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[33099]" dev="sockfs" ino=33099 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-15 16:22:03.972  6826  6887 W jxcore-log: Starting JXcore engine
08-15 16:22:04.063  6826  6887 W jxcore-log: Platform android
08-15 16:22:04.063  6826  6887 W jxcore-log: 
08-15 16:22:04.063  6826  6887 W jxcore-log: Process ARCH arm
08-15 16:22:04.063  6826  6887 W jxcore-log: 
,08-15 16:22:04.239  6826  6887 I jxcore-log: JXcore Cordova bridge is ready!
08-15 16:22:04.239  6826  6887 I jxcore-log: 
08-15 16:22:04.240  6826  6887 W jxcore-log: JXcore engine is started
,08-15 16:22:04.247  6826  6884 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-15 16:22:04.249  6826  6826 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-15 16:22:14.273  6826  6887 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-15 16:22:14.273  6826  6887 I jxcore-log: 
,08-15 16:22:14.276  6826  6887 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-15 16:22:14.276  6826  6887 I jxcore-log: 
08-15 16:22:14.282  6826  6887 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-15 16:22:14.282  6826  6887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 16:22:14.282  6826  6887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-15 16:22:14.282  6826  6887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-15 16:22:14.282  6826  6887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-15 16:22:14.282  6826  6887 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-15 16:22:14.282  6826  6887 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-15 16:22:14.282  6826  6887 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-15 16:22:14.284  6826  6887 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-15 16:22:14.287  6826  6887 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-15 16:22:14.287  6826  6887 I jxcore-log: 
,08-15 16:22:14.289  6826  6887 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-15 16:22:14.289  6826  6887 I jxcore-log: 
08-15 16:22:14.610  6826  6887 D ExecuteNativeTests: Running unit tests
,08-15 16:22:14.690  6826  6887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-15 16:22:14.690  6826  6887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@89eba96 added. We now have 2 listener(s),
08-15 16:22:14.691  1036  1945 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-15 16:22:14.692  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-15 16:22:14.692  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-15 16:22:14.692  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-15 16:22:14.692  6826  6887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-15 16:22:14.692  6826  6887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e735617 added. We now have 2 listener(s)
08-15 16:22:14.692  6826  6887 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-15 16:22:14.693  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported,
08-15 16:22:14.695  6826  6887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-15 16:22:14.697  6826  6887 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
08-15 16:22:14.697  6826  6887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 16:22:14.697  6826  6887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-15 16:22:14.697  6826  6887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true,
08-15 16:22:14.697  6826  6887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-15 16:22:14.697  6826  6887 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-15 16:22:14.697  6826  6887 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true,
08-15 16:22:14.697  6826  6887 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-15 16:22:14.697  6826  6887 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
08-15 16:22:14.698  6826  6887 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-15 16:22:14.699  6826  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 16:22:14.700  6826  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-15 16:22:14.702  6826  6887 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect,
08-15 16:22:14.704  6826  6887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-15 16:22:14.704  6826  6887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-15 16:22:14.706  6826  6887 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-15 16:22:14.708  6826  6887 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-15 16:22:14.708  6826  6887 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-15 16:22:14.708  6826  6887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-15 16:22:14.708  6826  6887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-15 16:22:14.709  6826  6887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-15 16:22:14.710  6826  6887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-15 16:22:14.710  6826  6887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-15 16:22:14.710  6826  6887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-15 16:22:14.710  6826  6887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-15 16:22:14.710  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-15 16:22:14.711  6826  6887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-15 16:22:14.711  6826  6887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@89eba96 removed from the list
08-15 16:22:14.711  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:22:14.711  6826  6887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e735617 removed from the list
08-15 16:22:14.711  6826  6887 D io.jxcore.node.ConnectivityMonitor: stop
08-15 16:22:14.711  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:22:14.712  6826  6887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:22:14.712  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-15 16:22:14.712  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-15 16:22:14.713  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-15 16:22:14.713  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:22:14.713  6826  6887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e735617 not in the list
08-15 16:22:14.716  6826  6887 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-15 16:22:14.717  6826  6887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-15 16:22:14.717  6826  6887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-15 16:22:14.717  6826  6887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-15 16:22:14.718  6826  6887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-15 16:22:14.718  6826  6887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:22:14.718  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:22:14.718  6826  6887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@89eba96 not in the list
08-15 16:22:14.718  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:22:14.718  6826  6887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e735617 not in the list
08-15 16:22:14.718  6826  6887 D io.jxcore.node.ConnectivityMonitor: stop
,08-15 16:22:14.718  6826  6887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:22:14.718  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:22:14.718  6826  6887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:22:14.718  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:22:14.719  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-15 16:22:14.719  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-15 16:22:14.719  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:22:14.719  6826  6887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e735617 not in the list
08-15 16:22:14.722  6826  6887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-15 16:22:14.722  6826  6887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010],
08-15 16:22:14.723  6826  6887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-15 16:22:14.723  6826  6887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-15 16:22:14.723  6826  6887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-15 16:22:14.723  6826  6887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-15 16:22:14.723  6826  6887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-15 16:22:14.723  6826  6887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-15 16:22:14.723  6826  6887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-15 16:22:14.723  6826  6887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-15 16:22:14.723  6826  6887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-15 16:22:14.723  6826  6887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-15 16:22:14.723  6826  6887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,08-15 16:22:14.723  6826  6887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-15 16:22:14.723  6826  6887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-15 16:22:14.723  6826  6887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-15 16:22:14.723  6826  6887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-15 16:22:14.723  6826  6887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,08-15 16:22:14.723  6826  6887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,08-15 16:22:14.723  6826  6887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810],
08-15 16:22:14.723  6826  6887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-15 16:22:14.723  6826  6887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-15 16:22:14.723  6826  6887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-15 16:22:14.723  6826  6887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-15 16:22:14.723  6826  6887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-15 16:22:14.723  6826  6887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-15 16:22:14.723  6826  6887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-15 16:22:14.723  6826  6887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-15 16:22:14.723  6826  6887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-15 16:22:14.723  6826  6887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-15 16:22:14.723  6826  6887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-15 16:22:14.723  6826  6887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-15 16:22:14.723  6826  6887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-15 16:22:14.723  6826  6887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-15 16:22:14.723  6826  6887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-15 16:22:14.724  6826  6887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:22:14.724  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:22:14.724  6826  6887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@89eba96 not in the list
08-15 16:22:14.724  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:22:14.724  6826  6887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e735617 not in the list
08-15 16:22:14.724  6826  6887 D io.jxcore.node.ConnectivityMonitor: stop
08-15 16:22:14.724  6826  6887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:22:14.724  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:22:14.724  6826  6887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:22:14.724  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:22:14.725  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-15 16:22:14.725  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-15 16:22:14.725  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:22:14.725  6826  6887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e735617 not in the list
08-15 16:22:14.725  6826  6887 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-15 16:22:14.727  6826  6887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-15 16:22:14.729  6826  6887 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-15 16:22:14.729  6826  6887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 16:22:14.729  6826  6887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-15 16:22:14.729  6826  6887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-15 16:22:14.729  6826  6887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-15 16:22:14.729  6826  6887 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-15 16:22:14.729  6826  6887 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-15 16:22:14.729  6826  6887 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-15 16:22:14.730  6826  6887 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-15 16:22:14.730  6826  6887 D io.jxcore.node.ConnectivityMonitor: start: OK
08-15 16:22:14.731  6826  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 16:22:14.731  6826  6887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-15 16:22:14.731  6826  6887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-15 16:22:14.731  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-15 16:22:14.732  6826  6887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-15 16:22:14.732  6826  6887 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-15 16:22:14.732  6826  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 16:22:14.734  6826  6887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-15 16:22:14.734  1036  1915 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-15 16:22:14.738  6826  6887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-15 16:22:14.741  6826  6887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-15 16:22:14.743  6826  6887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
08-15 16:22:14.744  6826  6887 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-15 16:22:14.744  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-15 16:22:14.745  6826  6887 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-15 16:22:14.745  6826  6887 I io.jxcore.node.ConnectionHelper: start: OK
08-15 16:22:14.748  6826  6887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-15 16:22:14.748  6826  6887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-15 16:22:14.748  6826  6887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-15 16:22:14.748  6826  6887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-15 16:22:14.748  6826  6887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:22:14.748  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-15 16:22:14.748  6826  6887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@89eba96 not in the list
08-15 16:22:14.748  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:22:14.748  6826  6887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e735617 not in the list
08-15 16:22:14.748  6826  6887 D io.jxcore.node.ConnectivityMonitor: stop
08-15 16:22:14.748  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-15 16:22:14.749  6826  6887 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false,
08-15 16:22:14.751  6826  6887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-15 16:22:14.752  6826  6887 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-15 16:22:14.752  6826  6887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 16:22:14.752  6826  6887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-15 16:22:14.752  6826  6887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-15 16:22:14.752  6826  6887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-15 16:22:14.752  6826  6887 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-15 16:22:14.752  6826  6887 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-15 16:22:14.752  6826  6887 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-15 16:22:14.753  6826  6887 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-15 16:22:14.753  6826  6887 D io.jxcore.node.ConnectivityMonitor: start: OK,
08-15 16:22:14.754  6826  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 16:22:14.755  6826  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 16:22:14.755  6826  6887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-15 16:22:14.755  6826  6887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-15 16:22:14.755  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-15 16:22:14.755  6826  6887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-15 16:22:14.755  6826  6887 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-15 16:22:14.758  6826  6887 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-15 16:22:14.759  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-15 16:22:14.760  6826  6887 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-15 16:22:14.760  6826  6887 I io.jxcore.node.ConnectionHelper: start: OK
,08-15 16:22:14.761  6826  6887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-15 16:22:14.761  6826  6887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-15 16:22:14.761  6826  6887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-15 16:22:14.761  6826  6887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-15 16:22:14.761  6826  6887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:22:14.761  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-15 16:22:14.761  6826  6887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@89eba96 not in the list
08-15 16:22:14.761  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:22:14.761  6826  6887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e735617 not in the list
08-15 16:22:14.761  6826  6887 D io.jxcore.node.ConnectivityMonitor: stop
08-15 16:22:14.762  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:22:14.762  6826  6887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:22:14.762  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:22:14.762  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-15 16:22:14.762  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-15 16:22:14.763  6826  6887 D BluetoothLeScanner: could not find callback wrapper
08-15 16:22:14.763  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-15 16:22:14.764  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:22:14.764  6826  6887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e735617 not in the list
08-15 16:22:14.764  6826  6887 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-15 16:22:14.835  1036  1051 I art     : Explicit concurrent mark sweep GC freed 28742(1403KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/64MB, paused 1.437ms total 70.282ms
08-15 16:22:14.838  6826  6887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-15 16:22:14.840  6826  6887 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-15 16:22:14.840  6826  6887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 16:22:14.840  6826  6887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-15 16:22:14.840  6826  6887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-15 16:22:14.840  6826  6887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-15 16:22:14.840  6826  6887 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-15 16:22:14.840  6826  6887 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-15 16:22:14.840  6826  6887 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-15 16:22:14.841  6826  6887 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-15 16:22:14.841  6826  6887 D io.jxcore.node.ConnectivityMonitor: start: OK
08-15 16:22:14.842  6826  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 16:22:14.843  6826  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 16:22:14.843  6826  6887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-15 16:22:14.843  6826  6887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-15 16:22:14.843  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-15 16:22:14.843  6826  6887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-15 16:22:14.843  6826  6887 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-15 16:22:14.848  6826  6887 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-15 16:22:14.848  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-15 16:22:14.852  6826  6887 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-15 16:22:14.852  6826  6887 I io.jxcore.node.ConnectionHelper: start: OK
08-15 16:22:14.852  6826  6887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-15 16:22:14.852  6826  6887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-15 16:22:14.856  6826  6887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-15 16:22:14.858  6826  6887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-15 16:22:14.858  6826  6887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-15 16:22:14.858  6826  6887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-15 16:22:14.858  6826  6887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-15 16:22:14.858  6826  6887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:22:14.858  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-15 16:22:14.859  6826  6887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@89eba96 not in the list
08-15 16:22:14.859  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:22:14.859  6826  6887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e735617 not in the list
08-15 16:22:14.859  6826  6887 D io.jxcore.node.ConnectivityMonitor: stop
08-15 16:22:14.859  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:22:14.865  6826  6887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:22:14.865  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-15 16:22:14.868  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-15 16:22:14.868  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-15 16:22:14.868  6826  6887 D BluetoothLeScanner: could not find callback wrapper
08-15 16:22:14.869  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-15 16:22:14.869  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:22:14.869  6826  6887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e735617 not in the list
08-15 16:22:14.869  6826  6887 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-15 16:22:14.869  6826  6887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-15 16:22:14.869  6826  6887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-15 16:22:14.869  6826  6887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-15 16:22:14.869  6826  6887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-15 16:22:14.869  6826  6887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:22:14.869  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:22:14.870  6826  6887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@89eba96 not in the list
08-15 16:22:14.870  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:22:14.870  6826  6887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e735617 not in the list
08-15 16:22:14.870  6826  6887 D io.jxcore.node.ConnectivityMonitor: stop
08-15 16:22:14.870  6826  6887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:22:14.870  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:22:14.870  6826  6887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:22:14.870  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:22:14.870  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-15 16:22:14.870  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-15 16:22:14.870  6826  6887 D BluetoothLeScanner: could not find callback wrapper
08-15 16:22:14.870  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-15 16:22:14.870  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:22:14.870  6826  6887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e735617 not in the list
08-15 16:22:14.871  6826  6887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-15 16:22:14.871  6826  6887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-15 16:22:14.871  6826  6887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-15 16:22:14.871  6826  6887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-15 16:22:14.871  6826  6887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-15 16:22:14.871  6826  6887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:22:14.871  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:22:14.871  6826  6887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@89eba96 not in the list
08-15 16:22:14.871  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:22:14.871  6826  6887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e735617 not in the list
08-15 16:22:14.871  6826  6887 D io.jxcore.node.ConnectivityMonitor: stop
08-15 16:22:14.871  6826  6887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:22:14.872  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:22:14.872  6826  6887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:22:14.872  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:22:14.872  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-15 16:22:14.872  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-15 16:22:14.873  6826  6887 D BluetoothLeScanner: could not find callback wrapper
08-15 16:22:14.873  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-15 16:22:14.873  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:22:14.873  6826  6887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e735617 not in the list
08-15 16:22:14.873  6826  6887 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-15 16:22:14.873  6826  6887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-15 16:22:14.874  6826  6887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-15 16:22:14.874  6826  6887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-15 16:22:14.876  6826  6887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-15 16:22:14.876  6826  6887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:22:14.876  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:22:14.876  6826  6887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@89eba96 not in the list
08-15 16:22:14.876  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:22:14.876  6826  6887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e735617 not in the list
08-15 16:22:14.876  6826  6887 D io.jxcore.node.ConnectivityMonitor: stop
08-15 16:22:14.876  6826  6887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:22:14.876  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:22:14.876  6826  6887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:22:14.876  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:22:14.877  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-15 16:22:14.877  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-15 16:22:14.877  6826  6887 D BluetoothLeScanner: could not find callback wrapper
08-15 16:22:14.877  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-15 16:22:14.877  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:22:14.877  6826  6887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e735617 not in the list
08-15 16:22:14.878  6826  6887 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-15 16:22:14.878  6826  6887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-15 16:22:14.878  6826  6887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-15 16:22:14.878  6826  6887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-15 16:22:14.878  6826  6887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-15 16:22:14.878  6826  6887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:22:14.878  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:22:14.878  6826  6887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@89eba96 not in the list
08-15 16:22:14.878  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:22:14.878  6826  6887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e735617 not in the list
08-15 16:22:14.878  6826  6887 D io.jxcore.node.ConnectivityMonitor: stop
08-15 16:22:14.878  6826  6887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:22:14.878  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:22:14.878  6826  6887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:22:14.878  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:22:14.880  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-15 16:22:14.880  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-15 16:22:14.880  6826  6887 D BluetoothLeScanner: could not find callback wrapper
08-15 16:22:14.880  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-15 16:22:14.880  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:22:14.880  6826  6887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e735617 not in the list
08-15 16:22:14.881  6826  6887 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-15 16:22:14.882  6826  6887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-15 16:22:14.882  6826  6887 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-15 16:22:14.882  6826  6887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-15 16:22:14.882  6826  6887 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-15 16:22:14.882  6826  6887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-15 16:22:14.882  6826  6887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-15 16:22:14.882  6826  6887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-15 16:22:14.882  6826  6887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-15 16:22:14.882  6826  6887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-15 16:22:14.882  6826  6887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:22:14.882  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:22:14.882  6826  6887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@89eba96 not in the list
08-15 16:22:14.882  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:22:14.882  6826  6887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e735617 not in the list
08-15 16:22:14.882  6826  6887 D io.jxcore.node.ConnectivityMonitor: stop
08-15 16:22:14.882  6826  6887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:22:14.882  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:22:14.883  6826  6887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:22:14.883  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:22:14.883  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-15 16:22:14.883  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-15 16:22:14.884  6826  6887 D BluetoothLeScanner: could not find callback wrapper
08-15 16:22:14.884  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-15 16:22:14.884  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:22:14.884  6826  6887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e735617 not in the list
08-15 16:22:14.884  6826  6887 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-15 16:22:14.884  6826  6887 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-15 16:22:14.884  6826  6887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-15 16:22:14.886  6826  6887 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-15 16:22:14.886  6826  6887 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-15 16:22:14.886  6826  6887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-15 16:22:14.886  6826  6887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-15 16:22:14.886  6826  6887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-15 16:22:14.886  6826  6887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-15 16:22:14.886  6826  6887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-15 16:22:14.886  6826  6887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-15 16:22:14.886  6826  6887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-15 16:22:14.886  6826  6887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-15 16:22:14.886  6826  6887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-15 16:22:14.886  6826  6887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-15 16:22:14.886  6826  6887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-15 16:22:14.887  6826  6887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-15 16:22:14.887  6826  6887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-15 16:22:14.887  6826  6887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-15 16:22:14.887  6826  6887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-15 16:22:14.887  6826  6887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-15 16:22:14.887  6826  6887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-15 16:22:14.887  6826  6887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-15 16:22:14.887  6826  6887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-15 16:22:14.887  6826  6887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-15 16:22:14.887  6826  6887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-15 16:22:14.887  6826  6887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-15 16:22:14.887  6826  6887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-15 16:22:14.887  6826  6887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-15 16:22:14.887  6826  6887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-15 16:22:14.887  6826  6887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-15 16:22:14.887  6826  6887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-15 16:22:14.887  6826  6887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-15 16:22:14.887  6826  6887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-15 16:22:14.887  6826  6887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-15 16:22:14.887  6826  6887 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-15 16:22:14.887  6826  6887 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-15 16:22:14.887  6826  6887 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-15 16:22:14.887  6826  6887 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-15 16:22:14.887  6826  6887 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-15 16:22:14.887  6826  6887 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-15 16:22:14.887  6826  6887 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-15 16:22:14.887  6826  6887 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-15 16:22:14.887  6826  6887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-15 16:22:14.889  6826  6887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-15 16:22:14.891  6826  6887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-15 16:22:14.892  6826  6887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-15 16:22:14.894  6826  6887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-15 16:22:14.894  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-15 16:22:14.894  6826  6887 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-15 16:22:14.894  6826  6887 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-15 16:22:14.894  6826  6887 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-15 16:22:14.895  6826  6887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-15 16:22:14.895  6826  6887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-15 16:22:14.895  6826  6887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-15 16:22:14.895  6826  6887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-15 16:22:14.895  6826  6887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:22:14.895  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:22:14.896  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-15 16:22:14.896  6826  6887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@89eba96 not in the list
08-15 16:22:14.896  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:22:14.896  6826  6887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e735617 not in the list
08-15 16:22:14.896  6826  6887 D io.jxcore.node.ConnectivityMonitor: stop
08-15 16:22:14.896  6826  6887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:22:14.896  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:22:14.896  6826  6887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:22:14.896  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:22:14.897  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-15 16:22:14.897  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-15 16:22:14.898  6826  6887 D BluetoothLeScanner: could not find callback wrapper
08-15 16:22:14.898  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-15 16:22:14.898  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:22:14.898  6826  6887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e735617 not in the list
08-15 16:22:14.898  6826  6887 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-15 16:22:14.898  6826  6887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-15 16:22:14.898  6826  6887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-15 16:22:14.898  6826  6887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-15 16:22:14.899  6826  6887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-15 16:22:14.899  6826  6887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:22:14.899  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:22:14.899  6826  6887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@89eba96 not in the list
08-15 16:22:14.899  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:22:14.899  6826  6887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e735617 not in the list
08-15 16:22:14.899  6826  6887 D io.jxcore.node.ConnectivityMonitor: stop
08-15 16:22:14.899  6826  6887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:22:14.899  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:22:14.899  6826  6887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:22:14.899  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:22:14.900  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-15 16:22:14.900  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-15 16:22:14.900  6826  6887 D BluetoothLeScanner: could not find callback wrapper
08-15 16:22:14.900  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-15 16:22:14.900  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:22:14.900  6826  6887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e735617 not in the list
08-15 16:22:14.900  6826  6887 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-15 16:22:14.901  6826  6887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-15 16:22:14.901  6826  6887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-15 16:22:14.901  6826  6887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-15 16:22:14.902  6826  6889 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 846)
,08-15 16:22:14.908  6826  6887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-15 16:22:14.908  6826  6887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:22:14.908  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:22:14.908  6826  6887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@89eba96 not in the list
08-15 16:22:14.908  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:22:14.908  6826  6887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e735617 not in the list
08-15 16:22:14.908  6826  6887 D io.jxcore.node.ConnectivityMonitor: stop
08-15 16:22:14.908  6826  6887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:22:14.908  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:22:14.908  6826  6887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:22:14.908  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:22:14.909  6826  6890 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 846
08-15 16:22:14.909  6826  6890 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 846)
08-15 16:22:14.910  6826  6890 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 846)
08-15 16:22:14.910  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-15 16:22:14.910  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-15 16:22:14.910  6826  6887 D BluetoothLeScanner: could not find callback wrapper
08-15 16:22:14.910  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-15 16:22:14.910  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:22:14.910  6826  6887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e735617 not in the list
08-15 16:22:14.911  6826  6887 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-15 16:22:14.911  6826  6887 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-15 16:22:14.911  6826  6887 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-15 16:22:14.911  6826  6887 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-15 16:22:14.911  6826  6887 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-15 16:22:14.911  6826  6887 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-15 16:22:14.911  6826  6887 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-15 16:22:14.911  6826  6887 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-15 16:22:14.911  6826  6887 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-15 16:22:14.911  6826  6887 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-15 16:22:14.911  6826  6887 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-15 16:22:14.911  6826  6887 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-15 16:22:14.911  6826  6887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-15 16:22:14.911  6826  6887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-15 16:22:14.911  6826  6887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-15 16:22:14.912  6826  6887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-15 16:22:14.912  6826  6887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:22:14.912  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:22:14.912  6826  6887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@89eba96 not in the list
08-15 16:22:14.912  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:22:14.912  6826  6887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e735617 not in the list
08-15 16:22:14.912  6826  6887 D io.jxcore.node.ConnectivityMonitor: stop
08-15 16:22:14.912  6826  6887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:22:14.912  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:22:14.912  6826  6887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:22:14.912  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:22:14.913  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-15 16:22:14.913  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-15 16:22:14.913  6826  6887 D BluetoothLeScanner: could not find callback wrapper
08-15 16:22:14.913  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-15 16:22:14.913  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:22:14.913  6826  6887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e735617 not in the list
08-15 16:22:14.914  6826  6887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-15 16:22:14.914  6826  6887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:22:14.914  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:22:14.914  6826  6887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@89eba96 not in the list
08-15 16:22:14.914  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:22:14.914  6826  6887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e735617 not in the list
08-15 16:22:14.914  6826  6887 D io.jxcore.node.ConnectivityMonitor: stop
08-15 16:22:14.914  6826  6887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:22:14.914  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:22:14.914  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:22:14.914  6826  6887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e735617 not in the list
08-15 16:22:14.914  6826  6887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-15 16:22:14.914  6826  6887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:22:14.914  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:22:14.914  6826  6887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@89eba96 not in the list
08-15 16:22:14.914  6826  6887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-15 16:22:14.914  6826  6887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-15 16:22:14.914  6826  6887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-15 16:22:14.915  6826  6887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-15 16:22:14.915  6826  6887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:22:14.915  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:22:14.915  6826  6887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@89eba96 not in the list
08-15 16:22:14.915  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:22:14.915  6826  6887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e735617 not in the list
08-15 16:22:14.915  6826  6887 D io.jxcore.node.ConnectivityMonitor: stop
08-15 16:22:14.915  6826  6887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:22:14.915  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:22:14.915  6826  6887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:22:14.915  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:22:14.918  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-15 16:22:14.919  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-15 16:22:14.920  6826  6887 D BluetoothLeScanner: could not find callback wrapper
08-15 16:22:14.920  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-15 16:22:14.920  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:22:14.920  6826  6887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e735617 not in the list
08-15 16:22:14.921  6826  6887 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-15 16:22:14.921  6826  6887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-15 16:22:14.922  6826  6887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-15 16:22:14.924  6826  6887 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-15 16:22:14.924  6826  6887 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-15 16:22:14.925  6826  6826 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-15 16:22:14.925  6826  6887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-15 16:22:14.926  6826  6887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-15 16:22:14.927  6826  6887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-15 16:22:14.927  6826  6887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-15 16:22:14.927  6826  6887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-15 16:22:14.927  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-15 16:22:14.927  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:22:14.927  6826  6887 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-15 16:22:14.928  6826  6826 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-15 16:22:14.928  6826  6887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@89eba96 not in the list
08-15 16:22:14.928  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:22:14.928  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-15 16:22:14.928  6826  6887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-15 16:22:14.928  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-15 16:22:14.930  6826  6887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-15 16:22:14.931  6826  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-15 16:22:14.931  6826  6896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-15 16:22:14.932  6826  6887 D BluetoothLeScanner: could not find callback wrapper
08-15 16:22:14.932  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-15 16:22:14.932  6826  6887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-15 16:22:14.932  6826  6887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:22:14.932  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:22:14.938  6826  6887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-15 16:22:14.939  6826  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-15 16:22:14.939  6826  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-15 16:22:14.939  6826  6826 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-15 16:22:14.939  6826  6826 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-15 16:22:14.939  6826  6887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e735617 not in the list
08-15 16:22:14.939  6826  6887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-15 16:22:14.939  6826  6887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-15 16:22:14.939  6826  6887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-15 16:22:14.939  6826  6887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-15 16:22:14.939  6826  6887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:22:14.939  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:22:14.939  6826  6887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@89eba96 not in the list
08-15 16:22:14.939  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:22:14.939  6826  6887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e735617 not in the list
08-15 16:22:14.939  6826  6887 D io.jxcore.node.ConnectivityMonitor: stop
08-15 16:22:14.939  6826  6887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:22:14.939  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:22:14.939  6826  6887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:22:14.939  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:22:14.940  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-15 16:22:14.940  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-15 16:22:14.940  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:22:14.940  6826  6887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e735617 not in the list
08-15 16:22:14.941  6826  6887 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-15 16:22:14.941  6826  6887 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-15 16:22:14.941  6826  6887 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-15 16:22:14.942  6826  6887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-15 16:22:14.943  6826  6887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-15 16:22:14.943  6826  6887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-15 16:22:14.943  6826  6887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-15 16:22:14.943  6826  6887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-15 16:22:14.943  6826  6887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:22:14.943  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:22:14.943  6826  6887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@89eba96 not in the list
08-15 16:22:14.943  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:22:14.943  6826  6887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e735617 not in the list
08-15 16:22:14.943  6826  6887 D io.jxcore.node.ConnectivityMonitor: stop
08-15 16:22:14.943  6826  6887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:22:14.943  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:22:14.943  6826  6887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:22:14.943  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:22:14.944  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-15 16:22:14.944  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-15 16:22:14.944  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:22:14.944  6826  6887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e735617 not in the list
08-15 16:22:14.944  1036  1901 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-15 16:22:14.945  1036  1787 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-15 16:22:14.945  1036  1915 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-15 16:22:14.946  6826  6887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-15 16:22:14.946  6826  6887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-15 16:22:14.946  6826  6887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-15 16:22:14.946  6826  6887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-15 16:22:14.946  6826  6887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:22:14.946  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:22:14.946  6826  6887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@89eba96 not in the list
08-15 16:22:14.946  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:22:14.946  6826  6887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e735617 not in the list
08-15 16:22:14.946  6826  6887 D io.jxcore.node.ConnectivityMonitor: stop
08-15 16:22:14.946  6826  6887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:22:14.946  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:22:14.946  6826  6887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:22:14.946  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:22:14.946  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-15 16:22:14.946  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-15 16:22:14.946  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:22:14.946  6826  6887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e735617 not in the list
08-15 16:22:14.947  6826  6887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-15 16:22:14.947  6826  6887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-15 16:22:14.947  6826  6887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-15 16:22:14.947  6826  6887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-15 16:22:14.947  6826  6887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:22:14.947  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:22:14.947  6826  6887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@89eba96 not in the list
08-15 16:22:14.947  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:22:14.947  6826  6887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e735617 not in the list
08-15 16:22:14.947  6826  6887 D io.jxcore.node.ConnectivityMonitor: stop
08-15 16:22:14.947  6826  6887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:22:14.947  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:22:14.947  6826  6887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:22:14.947  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:22:14.948  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-15 16:22:14.948  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-15 16:22:14.948  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:22:14.948  6826  6887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e735617 not in the list
08-15 16:22:14.949  6826  6887 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-15 16:22:14.949  6826  6887 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-15 16:22:14.949  6826  6887 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-15 16:22:14.949  6826  6887 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-15 16:22:14.949  6826  6887 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-15 16:22:14.949  6826  6887 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-15 16:22:14.951  6826  6887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-15 16:22:14.951  6826  6887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-15 16:22:14.951  6826  6887 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-15 16:22:14.951  6826  6887 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-15 16:22:14.951  6826  6887 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-15 16:22:14.951  6826  6887 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-15 16:22:14.951  6826  6887 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-15 16:22:14.951  6826  6887 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-15 16:22:14.952  6826  6887 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-15 16:22:14.952  6826  6887 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-15 16:22:14.952  6826  6887 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-15 16:22:14.952  6826  6887 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-15 16:22:14.952  6826  6887 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-15 16:22:14.953  6826  6887 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-15 16:22:14.953  6826  6887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-15 16:22:14.953  6826  6887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@38b7659c added. We now have 2 listener(s)
08-15 16:22:14.953  6826  6887 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-15 16:22:14.955  6826  6887 D BluetoothAdapter: enable(): BT is already enabled..!,
08-15 16:22:14.956  1036  1939 D WifiServiceImplEx: setWifiEnabled: true pid=6826, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-15 16:22:14.956  1036  1939 D WifiService: setWifiEnabled: true pid=6826, uid=10118
08-15 16:22:14.956  1036  1939 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-15 16:22:14.957  6826  6887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-15 16:22:14.957  6826  6887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@39b3fba5 added. We now have 3 listener(s)
08-15 16:22:14.957  6826  6887 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-15 16:22:14.970  6826  6887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-15 16:22:14.970  6826  6887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2eec9b7a added. We now have 4 listener(s)
08-15 16:22:14.970  6826  6887 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-15 16:22:14.973  6826  6887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
08-15 16:22:14.973  6826  6887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c798f2b added. We now have 5 listener(s)
08-15 16:22:14.973  6826  6887 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-15 16:22:14.974  1036  2046 D WifiServiceImplEx: setWifiEnabled: false pid=6826, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-15 16:22:14.975  1036  2046 D WifiService: setWifiEnabled: false pid=6826, uid=10118
08-15 16:22:14.975  1036  2046 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-15 16:22:14.985  1036  1550 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-15 16:22:14.986  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-15 16:22:14.986  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-15 16:22:14.986  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-15 16:22:14.986  1036  1550 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@772ad1 mBinding = false
08-15 16:22:14.987  1036  1422 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-15 16:22:14.988  1036  1422 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-15 16:22:14.988  1036  1422 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-15 16:22:14.989  1036  1422 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-15 16:22:14.989  1036  1422 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-15 16:22:14.989  1036  1422 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-15 16:22:14.989  1036  1422 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-15 16:22:14.989  1036  1422 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-15 16:22:14.992  1036  1422 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-15 16:22:14.992  1036  1422 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-15 16:22:14.992  6826  6889 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
08-15 16:22:14.993  6826  6889 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 846)
08-15 16:22:14.997  1036  1422 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-15 16:22:14.997  1036  1389 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-15 16:22:14.997  1036  1389 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-15 16:22:14.997  1036  1422 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-15 16:22:14.998  2764  2764 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-15 16:22:14.998  1036  1422 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-15 16:22:14.998  1036  1422 D WifiNative-wlan0: doBoolean: SET ps 1
08-15 16:22:14.998  1036  1422 D WifiNative-wlan0: SET ps 1: returned true
08-15 16:22:14.999  1036  2868 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-15 16:22:15.003  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-15 16:22:15.003  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-15 16:22:15.003   312   894 D CommandListener: Clearing all IP addresses on wlan0
08-15 16:22:15.003  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-15 16:22:15.006  1036  1118 D BluetoothManagerService: Message: 2
08-15 16:22:15.007  1036  1118 D BluetoothManagerService: Sending off request.
08-15 16:22:15.008  3838  3957 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-15 16:22:15.009  3838  3927 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-15 16:22:15.009  3838  3927 D BluetoothAdapterProperties: Setting state to 13
08-15 16:22:15.009  3838  3927 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-15 16:22:15.009  3838  3927 D BluetoothAdapterProperties: onBluetoothDisable()
08-15 16:22:15.010  3838  3927 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-15 16:22:15.010  6826  6887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-15 16:22:15.012  3838  3937 D BluetoothAdapterProperties: Scan Mode:20
08-15 16:22:15.012  3838  3927 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-15 16:22:15.013  3838  4088 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-15 16:22:15.013  3838  4088 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-15 16:22:15.013  3838  4243 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-15 16:22:15.013  3838  3927 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-15 16:22:15.014  3838  4244 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-15 16:22:15.014  3838  4246 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-15 16:22:15.014  3838  4194 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-15 16:22:15.016  3838  4192 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-15 16:22:15.016  3838  4192 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-15 16:22:15.016  3838  4192 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-15 16:22:15.016  3838  4192 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-15 16:22:15.016  3838  4192 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-15 16:22:15.016  3838  4192 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-15 16:22:15.016  3838  4192 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-15 16:22:15.016  3838  4192 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-15 16:22:15.017  3838  4088 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-15 16:22:15.017  3838  4088 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-15 16:22:15.017  3838  4088 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-15 16:22:15.017  3838  4088 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-15 16:22:15.017  3838  4088 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-15 16:22:15.017  3838  4088 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-15 16:22:15.017  3838  4088 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-15 16:22:15.017  3838  4088 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-15 16:22:15.017  3838  4088 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-15 16:22:15.017  3838  4088 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-15 16:22:15.017  3838  4088 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-15 16:22:15.017  3838  4088 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-15 16:22:15.021  6826  6887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-15 16:22:15.021  6826  6887 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-15 16:22:15.021  6826  6887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 16:22:15.021  6826  6887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-15 16:22:15.021  6826  6887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-15 1,6:22:15.021  6826  6887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-15 16:22:15.021  6826  6887 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-15 16:22:15.021  6826  6887 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-15 16:22:15.021  6826  6887 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-15 16:22:15.023  6826  6887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-15 16:22:15.023  6826  6887 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-15 16:22:15.023  6826  6887 D io.jxcore.node.ConnectivityMonitor: start: OK
08-15 16:22:15.024  6826  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-15 16:22:15.025  1036  1118 D BluetoothManagerService: Message: 60
08-15 16:22:15.025  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-15 16:22:15.025  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-15 16:22:15.026  6826  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 16:22:15.027  6826  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-15 16:22:15.027  6826  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-15 16:22:15.027  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 16:22:15.027  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-15 16:22:15.027  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-15 16:22:15.027  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-15 16:22:15.027  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-15 16:22:15.027  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-15 16:22:15.027  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-15 16:22:15.028  6826  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-15 16:22:15.028  6826  6826 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-15 16:22:15.030  6826  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 16:22:15.031  1036  1477 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-15 16:22:15.031  1036  1477 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
08-15 16:22:15.040  1036  1992 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
,08-15 16:22:15.041  1036  2866 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-2ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-15 16:22:15.041  1036  2866 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-15 16:22:15.041  1036  2866 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-15 16:22:15.041  1036  2866 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
08-15 16:22:15.041  1036  2866 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
08-15 16:22:15.051  1036  1092 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6908 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-15 16:22:15.053  1942  1942 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-15 16:22:15.054  3838  3838 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-15 16:22:15.054  3838  3838 D BluetoothMapService: STATE_TURNING_OFF
08-15 16:22:15.054  3838  3838 V BluetoothMapService: Handler(): got msg=4
08-15 16:22:15.054  3838  3838 D BluetoothMapService: MAP Service closeService in
08-15 16:22:15.054  3838  3838 D BluetoothMapMasInstance: MAP Service shutdown
08-15 16:22:15.054  3838  3838 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-15 16:22:15.054  3838  3838 V BluetoothMapService: MAP Service closeService out
08-15 16:22:15.055  3838  3838 V BtOppService: Receiver DISABLED_ACTION 
08-15 16:22:15.055  3838  3838 I BtOppRfcommListener: stopping Accept Thread
08-15 16:22:15.055  3838  3838 V BtOppRfcommListener: close mBtServerSocket
08-15 16:22:15.055  3838  3838 V BtOppRfcommListener: waiting for thread to terminate
08-15 16:22:15.055  3838  4243 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-15 16:22:15.056  1606  1606 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-15 16:22:15.057  6826  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-15 16:22:15.057  6826  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-15 16:22:15.057  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 16:22:15.057  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-15 16:22:15.057  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-15 16:22:15.057  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-15 16:22:15.057  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-15 16:22:15.057  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-15 16:22:15.057  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-15 16:22:15.058  6826  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-15 16:22:15.058  6826  6826 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-15 16:22:15.058  3838  3838 V BtOppRfcommListener: done waiting for thread to terminate
08-15 16:22:15.060  6826  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-15 16:22:15.060  6826  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-15 16:22:15.060  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 16:22:15.060  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-15 16:22:15.060  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-15 16:22:15.060  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-15 16:22:15.060  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-15 16:22:15.060  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-15 16:22:15.060  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-15 16:22:15.060  6826  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-15 16:22:1,5.060  6826  6826 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-15 16:22:15.076  1036  1477 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-15 16:22:15.076  1036  1477 D DSQN    : disableDataServiceNotify
08-15 16:22:15.076  1036  1477 D DSQN    : stop dsqn bin
,08-15 16:22:15.079   312  6928 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-15 16:22:15.079  1036  1116 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-15 16:22:15.088  1036  2866 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,08-15 16:22:15.089  1036  1477 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-15 16:22:15.089  1036  1477 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-15 16:22:15.089  1036  1477 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-15 16:22:15.089  1036  1477 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-15 16:22:15.090  1036  1477 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-15 16:22:15.090  1606  2076 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-15 16:22:15.090  1036  2866 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-15 16:22:15.090  1036  2866 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-15 16:22:15.090  1036  2866 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-15 16:22:15.091  1036  1477 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-15 16:22:15.091  1036  1477 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-15 16:22:15.091  1036  1477 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-15 16:22:15.100  1036  1092 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6929 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-15 16:22:15.102  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-15 16:22:15.102  1942  1942 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-15 16:22:15.102  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 16:22:15.102  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 16:22:15.102  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-15 16:22:15.104  1036  1389 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-15 16:22:15.104  1036  1389 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-15 16:22:15.104  1036  1422 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-15 16:22:15.104  1036  1422 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-15 16:22:15.104  1036  1422 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-15 16:22:15.105  1036  1422 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-15 16:22:15.105  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-15 16:22:15.105  1606  1606 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-15 16:22:15.105  1036  1422 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-15 16:22:15.105  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-15 16:22:15.105  1036  1422 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-15 16:22:15.105  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 16:22:15.105  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 16:22:15.105  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-15 16:22:15.106  1036  1422 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-15 16:22:15.106  1036  1422 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-15 16:22:15.106  1036  1422 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-15 16:22:15.106  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 1
08-15 16:22:15.106  1036  1036 D RttService: SCAN_AVAILABLE : 1
08-15 16:22:15.106  1036  1422 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-15 16:22:15.107  1036  1389 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@4694419
08-15 16:22:15.109  1036  1557 D WifiScanningService: DefaultState got{ when=-2ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-15 16:22:15.109  1036  1558 D RttService: EnabledState got{ when=-3ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-15 16:22:15.110  3838  3838 V BtOppService: onDestroy
08-15 16:22:15.110  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-15 16:22:15.112  1036  1477 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNE,CTIVITY_CHANGE
08-15 16:22:15.112  1036  1389 D LGWifiP2pService: P2pDisablingState
,08-15 16:22:15.112  1036  1477 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-15 16:22:15.112  1036  1389 D LGWifiP2pService: P2pDisablingState{ when=-6ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-15 16:22:15.112  1036  1389 D LGWifiP2pService: p2p socket connection lost
08-15 16:22:15.112  1036  1389 D LGWifiP2pService: P2pDisabledState
08-15 16:22:15.112  3838  3838 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-15 16:22:15.113  1036  1477 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-15 16:22:15.113  1036  1477 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-15 16:22:15.113  1036  1477 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-15 16:22:15.113  1036  1477 D NetworkManagementService: Removing idletimer
08-15 16:22:15.113  1036  1477 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 16:22:15.114  1036  1477 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-15 16:22:15.114  1853  1853 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-15 16:22:15.114  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-15 16:22:15.114  1036  1388 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-15 16:22:15.115  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-15 16:22:15.115  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-15 16:22:15.115  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-15 16:22:15.115  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-15 16:22:15.119   344   344 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 264us total 18.741ms
08-15 16:22:15.119  1036  1388 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-15 16:22:15.119  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-15 16:22:15.120  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-15 16:22:15.120  1942  1942 D WfdsService: WifiP2pState is changed : false
08-15 16:22:15.120  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-15 16:22:15.120  1942  2262 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-15 16:22:15.120  1942  2262 D WfdsService: Set the WFDS Monitor: false
08-15 16:22:15.120  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-15 16:22:15.120  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-15 16:22:15.120  1942  2262 D WfdsMonitor: WFDS Monitor is stopped
08-15 16:22:15.120  1942  2262 D WfdsService: STATE : WfdsDisabledState - enter
08-15 16:22:15.120  1942  2787 D CtrlSupplicant: Received on exit socket, terminate
08-15 16:22:15.120  1942  2787 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-15 16:22:15.120  1942  2787 D WfdsMonito,r: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-15 16:22:15.120  1942  2787 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-15 16:22:15.121  1942  2264 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-15 16:22:15.121  1942  2262 W WfdsService: DefaultState - msg [9445378] is not handled
08-15 16:22:15.121  1036  1422 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-15 16:22:15.121  1036  1389 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-15 16:22:15.121  1036  1389 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-15 16:22:15.122  1036  1422 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-15 16:22:15.122  2764  2764 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-15 16:22:15.122  1036  1422 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-15 16:22:15.122  1036  1422 D WifiNative-wlan0: doBoolean: SET ps 1
08-15 16:22:15.122  1036  1422 D WifiNative-wlan0: SET ps 1: returned true
08-15 16:22:15.123   312   894 D CommandListener: Clearing all IP addresses on wlan0
08-15 16:22:15.125  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-15 16:22:15.125  1606  1606 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-15 16:22:15.127  1036  1422 D WifiNative-p2p0: doBoolean: TERMINATE
08-15 16:22:15.127  1036  1422 D WifiNative-p2p0: TERMINATE: returned true
08-15 16:22:15.128  1036  1422 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-15 16:22:15.128  1036  1422 E WifiStateMachine: useWiFiOffloading() : false
08-15 16:22:15.128  1036  1422 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-15 16:22:15.128  1036  1422 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-15 16:22:15.128  1036  1422 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-15 16:22:15.130  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-15 16:22:15.131  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-15 16:22:15.131   344   344 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 226us total 11.591ms
,08-15 16:22:15.133  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 16:22:15.133  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 16:22:15.133  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-15 16:22:15.139  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-15 16:22:15.141  6826  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-15 16:22:15.141  6826  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-15 16:22:15.141  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 16:22:15.141  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-15 16:22:15.141  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-15 16:22:15.141  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-15 16:22:15.141  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-15 16:22:15.141  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-15 16:22:15.141  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-15 16:22:15.142   344   344 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 222us total 10.654ms
08-15 16:22:15.145  6826  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-15 16:22:15.145  6826  6826 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-15 16:22:15.146  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-15 16:22:15.146  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-15 16:22:15.146  1036  1036 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-15 16:22:15.150  6826  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-15 16:22:15.150  6826  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-15 16:22:15.150  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 16:22:15.150  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-15 16:22:15.150  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-15 16:22:15.150  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-15 16:22:15.150  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-15 16:22:15.150  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-15 16:22:15.150  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-15 16:22:15.152  6826  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-15 16:22:15.152  6826  6826 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-15 16:22:15.168  6929  6929 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-15 16:22:15.168  6929  6929 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-15 16:22:15.168  6929  6929 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-15 16:22:15.168  6929  6929 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-15 16:22:15.169  1606  1606 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-15 16:22:15.169  6929  6929 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-15 16:22:15.170  6929  6929 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-15 16:22:15.170  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-15 16:22:15.170  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-15 16:22:15.182  1606  1606 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-15 16:22:15.183  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-15 16:22:15.183  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-15 16:22:15.185  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-15 16:22:15.185  1606  1606 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-15 16:22:15.186  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-15 16:22:15.187  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-15 16:22:15.194  6908  6908 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-15 16:22:15.195  6908  6908 W LG Account v2.2: No ProfileInfo entries
08-15 16:22:15.195  6908  6908 I LG Account v2.2: isEnabled: false
08-15 16:22:15.195  6908  6908 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-15 16:22:15.195  6908  6908 I Feature : [Lifetracker]Country: EU
08-15 16:22:15.195  6908  6908 I Feature : [Lifetracker]Operator: OPEN
08-15 16:22:15.195  6908  6908 I Feature : [Lifetracker]Ranking support: false
08-15 16:22:15.195  6908  6908 I Feature : [Lifetracker]Comfort support: false
08-15 16:22:15.195  6908  6908 I Feature : [Lifetracker]Accessory: true
08-15 16:22:15.195  6908  6908 I Feature : [Lifetracker]Health device: true
08-15 16:22:15.195  6908  6908 I Feature : [Lifetracker]Extra Pedometer: false
08-15 16:22:15.195  6908  6908 I Feature : [Lifetracker]Blood glucose device: false
08-15 16:22:15.195  6908  6908 I Feature : [Lifetracker]Device Number: 3
,08-15 16:22:15.204  1036  2868 D DhcpStateMachine: StoppedState
08-15 16:22:15.204  1036  2868 D DhcpStateMachine: StoppedState{ when=-82ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-15 16:22:15.205  1036  1422 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-15 16:22:15.205  1036  1422 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-15 16:22:15.206  6515  6515 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-15 16:22:15.209  2764  2764 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-15 16:22:15.209  2764  2764 I wpa_supplicant: monitor socket send errors count : 1
08-15 16:22:15.209  2764  2764 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1942-2\x00 that cannot receive messages
08-15 16:22:15.210  1036  2784 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-15 16:22:15.210  1036  2784 D WifiMonitor: Dropping event because (p2p0) is stopped
08-15 16:22:15.234  1036  1597 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6949 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-15 16:22:15.235  1036  1597 I ActivityManager: Killing 6291:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-15 16:22:15.246  2764  2764 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-15 16:22:15.247  2764  2764 W wpa_supplicant: USIM:  scard_deinit function
,08-15 16:22:15.247  1036  2784 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-15 16:22:15.247  1036  2784 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-15 16:22:15.247  1036  2784 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-15 16:22:15.247  1036  1118 D Tethering: InitialState.processMessage what=4
08-15 16:22:15.247  1036  2784 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-15 16:22:15.247  1036  2784 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-15 16:22:15.247  1036  2784 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-15 16:22:15.248  1036  1422 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=191979
08-15 16:22:15.249  1036  1422 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=191980
08-15 16:22:15.249  1036  1422 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=191980  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-15 16:22:15.249  1036  1422 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=191980  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-15 16:22:15.269  1036  1915 W libprocessgroup: failed to open /acct/uid_10014/pid_6291/cgroup.procs: No such file or directory
,08-15 16:22:15.271  1036  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-15 16:22:15.271  1036  1422 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-15 16:22:15.271  1036  1422 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-15 16:22:15.279  2764  2764 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-15 16:22:15.279  1036  2784 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-15 16:22:15.279  1036  2784 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
08-15 16:22:15.279  1036  2784 D WifiMonitor: Disconnecting from the supplicant, no more events
08-15 16:22:15.279  1036  1422 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
08-15 16:22:15.297  6949  6949 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-15 16:22:15.301  6949  6949 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-15 16:22:15.301  6949  6949 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-15 16:22:15.302  1036  1915 I ActivityManager: Killing 6407:com.android.defcontainer/u0a4 (adj 15): empty #17
08-15 16:22:15.330  6929  6929 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-15 16:22:15.351  1036  1901 W libprocessgroup: failed to open /acct/uid_10004/pid_6407/cgroup.procs: No such file or directory
,08-15 16:22:15.358  3838  3838 V BluetoothPbapReceiver: PbapReceiver onReceive 
,08-15 16:22:15.359  3838  3838 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-15 16:22:15.359  3838  3838 V BluetoothPbapReceiver: ***********state = 13
08-15 16:22:15.362  3838  3838 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-15 16:22:15.363  3838  3838 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-15 16:22:15.364  3838  3838 V BluetoothPbapService: state: 13
08-15 16:22:15.364  3838  3838 V BluetoothPbapService: Pbap Service closeService in
,08-15 16:22:15.366  6929  6929 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-15 16:22:15.367  2131  2131 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-15 16:22:15.369  3838  3838 V BluetoothPbapService: successfully stopped pbap service
08-15 16:22:15.369  3838  3838 V BluetoothPbapService: Pbap Service closeService out
08-15 16:22:15.369  3838  3838 V BluetoothPbapService: Pbap Service onDestroy
08-15 16:22:15.369  3838  3838 V BluetoothPbapService: Pbap Service closeService in
08-15 16:22:15.369  3838  3838 V BluetoothPbapService: Pbap Service closeService out
08-15 16:22:15.370  3838  3838 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-15 16:22:15.384  1036  1422 D WifiOffDelayIfNotUsed: stopMonitoring
08-15 16:22:15.384  1036  1422 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-15 16:22:15.384  1036  1422 E WifiStateMachine: useWiFiOffloading() : false
08-15 16:22:15.384  1036  1422 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-15 16:22:15.387  1942  1942 D WfdsService: Supplicant Connection state is changed : false
08-15 16:22:15.388  1942  2262 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-15 16:22:15.388  1942  2262 D WfdsService: Set the WFDS Monitor: false
08-15 16:22:15.388  1942  2262 D WfdsMonitor: WFDS Monitor is stopped
08-15 16:22:15.388  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-15 16:22:15.389  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-15 16:22:15.391  2478  2478 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 16:22:15.391  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-15 16:22:15.391  1036  1442 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-15 16:22:15.391  1036  1442 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-15 16:22:15.393  6929  6929 D LgDataFeature: LgDataFeature() Constructor: none
08-15 16:22:15.393  6826  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 16:22:15.393  6929  6929 D LgDataFeature: LgDataFeature() Constructor Done, null
08-15 16:22:15.394  6826  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-15 16:22:15.401  6929  6929 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-15 16:22:15.407  1036  1118 D BluetoothManagerService: Message: 20
08-15 16:22:15.407  1036  1118 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c27fc10:true
08-15 16:22:15.414  1036  1118 D BluetoothManagerService: Message: 30
,08-15 16:22:15.418  1036  1118 D BluetoothManagerService: Message: 30
08-15 16:22:15.420  6929  6929 D LocalBluetoothProfileManager: Adding local MAP profile
08-15 16:22:15.421  6929  6929 D BluetoothMap: Create BluetoothMap proxy object
08-15 16:22:15.421  1036  1118 D BluetoothManagerService: Message: 30
08-15 16:22:15.425  1036  1118 D BluetoothManagerService: Message: 30
08-15 16:22:15.427  6929  6929 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-15 16:22:15.428  6929  6929 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
,08-15 16:22:15.437  6929  6929 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
08-15 16:22:15.438  6826  6826 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-15 16:22:15.441  6929  6929 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
,08-15 16:22:15.451  6929  6929 D DockEventReceiver: finishStartingService: stopping service
08-15 16:22:15.460  6929  6929 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-15 16:22:15.461  6929  6929 D BluetoothInputDevice: Proxy object connected
08-15 16:22:15.462  6929  6929 D HidProfile: Bluetooth service connected
,08-15 16:22:15.464  6929  6929 D BluetoothPan: BluetoothPAN Proxy object connected
08-15 16:22:15.464  6929  6929 D PanProfile: Bluetooth service connected
08-15 16:22:15.465  6929  6929 D BluetoothMap: Proxy object connected
08-15 16:22:15.465  6929  6929 D MapProfile: Bluetooth service connected
08-15 16:22:15.465  6929  6929 D BluetoothMap: getConnectedDevices()
08-15 16:22:15.465  6929  6929 D BluetoothMap: Bluetooth is Not enabled
08-15 16:22:15.465  6929  6929 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-15 16:22:15.467  6929  6929 D BluetoothPermissionRequest: onReceive
08-15 16:22:15.470  6929  6929 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-15 16:22:15.475  1036  1901 I ActivityManager: Killing 6551:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,08-15 16:22:15.482  6929  6929 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-15 16:22:15.520  1036  2025 W libprocessgroup: failed to open /acct/uid_10008/pid_6551/cgroup.procs: No such file or directory
,08-15 16:22:15.521  3838  3838 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-15 16:22:15.521  3838  3838 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-15 16:22:15.522  3838  3838 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-15 16:22:15.616  1036  1052 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6977 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-15 16:22:15.619  3838  3838 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-15 16:22:15.619  3838  3838 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-15 16:22:15.622  3838  3838 V BluetoothFtpService: Ftp Service onStartCommand
08-15 16:22:15.622  3838  3838 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-15 16:22:15.622  3838  3838 V BluetoothFtpService: Ftp Service closeService
08-15 16:22:15.623  3838  3838 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-15 16:22:15.625  3838  3838 V BluetoothFtpService: successfully stopped ftp service
08-15 16:22:15.626  3838  3838 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-15 16:22:15.626  3838  3838 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-15 16:22:15.626  3838  3838 V BluetoothSapReceiver: SapReceiver onReceive 
08-15 16:22:15.626  3838  3838 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-15 16:22:15.626  3838  3838 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-15 16:22:15.626  3838  3838 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-15 16:22:15.628  3838  3838 V BluetoothFtpService: Ftp Service onDestroy
08-15 16:22:15.628  3838  3838 V BluetoothFtpService: Ftp Service closeService
,08-15 16:22:15.679  1036  2025 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6994 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-15 16:22:15.681  3838  3838 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-15 16:22:15.681  3838  3838 V BluetoothSapService: state: 13
08-15 16:22:15.681  3838  3838 V BluetoothSapService: Stopping SAP server process
08-15 16:22:15.683  3838  3838 V BluetoothSapService: Sap Service closeSapService in
08-15 16:22:15.683  3838  3838 V BluetoothSapService: Close listen Socket : 
08-15 16:22:15.683  3838  3838 V BluetoothSapService: Close rfcomm Socket : 
08-15 16:22:15.683  3838  3838 V BluetoothSapService: Close sapd  Socket : 
08-15 16:22:15.688  3838  3838 V BluetoothSapService: Sap Service closeSapService out
08-15 16:22:15.689  3838  3838 V BluetoothSapService: Sap Service onDestroy
08-15 16:22:15.689  3838  3838 V BluetoothSapService: Sap Service closeSapService in
08-15 16:22:15.689  3838  3838 V BluetoothSapService: Close listen Socket : 
08-15 16:22:15.689  3838  3838 V BluetoothSapService: Close rfcomm Socket : 
08-15 16:22:15.689  3838  3838 V BluetoothSapService: Close sapd  Socket : 
08-15 16:22:15.689  3838  3838 V BluetoothSapService: Sap Service closeSapService out
08-15 16:22:15.708  6977  6977 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-15 16:22:15.733  6977  6977 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-15 16:22:15.739  6994  6994 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-15 16:22:15.754  1036  1051 I ActivityManager: Killing 6171:com.lge.appbox.client/u0a11 (adj 15): empty #17
,08-15 16:22:15.769  6977  6977 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,08-15 16:22:15.770  6977  6977 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
,08-15 16:22:15.770  6977  6977 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-15 16:22:15.770  6977  6977 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-15 16:22:15.771  6977  6977 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
,08-15 16:22:15.773  6977  6977 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-15 16:22:15.777  6977  6977 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-15 16:22:15.790  1036  1052 W libprocessgroup: failed to open /acct/uid_10011/pid_6171/cgroup.procs: No such file or directory
,08-15 16:22:15.798  6977  6977 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-15 16:22:15.802  6977  6977 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-15 16:22:15.830  6977  6977 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-15 16:22:15.835  6515  6515 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-15 16:22:15.839  6977  6977 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-15 16:22:15.841  6949  6949 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-15 16:22:15.841  6949  6949 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-15 16:22:15.841  6949  6949 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-15 16:22:15.844  6977  6977 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
,08-15 16:22:15.845  6929  6929 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-15 16:22:15.853  6929  6929 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-15 16:22:15.861  6977  6977 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-15 16:22:15.862  6977  6977 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-15 16:22:15.864  6977  6977 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-15 16:22:15.868  6515  6515 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-15 16:22:15.871  6949  6949 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-15 16:22:15.871  6949  6949 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-15 16:22:15.871  6949  6949 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-15 16:22:15.875  6929  6929 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-15 16:22:15.883  6929  6929 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-15 16:22:15.893  6977  6977 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-15 16:22:15.893  6977  6977 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-15 16:22:15.895  6977  6977 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-15 16:22:15.963  1036  1550 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7017 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-15 16:22:16.021  3838  4088 W bt-btif : ag scb idx 1 not allocated
08-15 16:22:16.021  3838  4088 E bt-btif : BTA AG is already disabled, ignoring ...
08-15 16:22:16.021  3838  4088 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-15 16:22:16.021  3838  3937 D bt_hci_bdroid: cleanup
,08-15 16:22:16.021  3838  4088 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-15 16:22:16.021  3838  4088 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-15 16:22:16.021  3838  4088 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-15 16:22:16.021  3838  4088 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-15 16:22:16.021  3838  4088 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-15 16:22:16.021  3838  4088 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-15 16:22:16.021  3838  4088 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-15 16:22:16.021  3838  4088 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-15 16:22:16.021  3838  4088 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-15 16:22:16.021  3838  4088 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-15 16:22:16.021  3838  4088 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-15 16:22:16.021  3838  4088 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-15 16:22:16.021  3838  4088 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-15 16:22:16.021  3838  4088 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-15 16:22:16.022  3838  4088 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-15 16:22:16.022  3838  4088 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-15 16:22:16.022  3838  4088 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-15 16:22:16.022  3838  4088 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-15 16:22:16.022  3838  4090 I bt_lpm  : LPM is already off!!!
08-15 16:22:16.022  3838  4180 I bt_userial_mct: exiting userial_read_thread
08-15 16:22:16.022  3838  4180 D bt_userial_mct: Leaving userial_evt_read_thread()
08-15 16:22:16.023  3838  3937 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-15 16:22:16.023  3838  4090 I bt_vendor: hw_epilog_process
08-15 16:22:16.024  3838  3937 D bt_hci_bdroid: cleanup Finalizing cleanup
08-15 16:22:16.024  3838  3937 D bt_userial_mct: userial_close
08-15 16:22:16.024  3838  3937 E bt_userial_mct: pthread_join() FAILED result:3
08-15 16:22:16.024  3838  3937 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-15 16:22:16.088  6949  6949 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-15 16:22:16.097  6929  6929 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-15 16:22:16.107  6929  6929 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-15 16:22:16.109  3838  3937 D bt_hci_bdroid: set_power 0
08-15 16:22:16.109  3838  3937 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-15 16:22:16.109  3838  3937 I bt_vendor: bluetooth satus is on
08-15 16:22:16.109  3838  3937 I bt_vendor: bt-vendor : resetting BT status
08-15 16:22:16.109  3838  3937 I bt_vendor: Starting hciattach daemon
08-15 16:22:16.109  3838  3937 I bt_vendor: try to set false
08-15 16:22:16.109  3838  3937 I bt_vendor: Starting hciattach daemon
08-15 16:22:16.110  3838  3937 I bt_vendor: try to set false
08-15 16:22:16.110  3838  3937 I bt_vendor: cleanup
08-15 16:22:16.111  3838  4088 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-15 16:22:16.112  3838  3937 I GKI_LINUX: GKI_exit_task 0 done
08-15 16:22:16.112  3838  3937 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-15 16:22:16.113  3838  3927 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-15 16:22:16.120  3838  3838 D HeadsetService: Received stop request...Stopping profile...
,08-15 16:22:16.125  3838  3838 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-15 16:22:16.125  3838  3838 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-15 16:22:16.125  3838  3838 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3aaa5e40
08-15 16:22:16.126  3838  3958 D HeadsetStateMachine: Exit Disconnected: -1
08-15 16:22:16.127  7017  7037 W FormManager: Network not available. Please check & try again.
08-15 16:22:16.130  1853  1853 D BluetoothHeadset: Proxy object disconnected
08-15 16:22:16.130  1853  1853 D BluetoothHeadset: Proxy object disconnected
08-15 16:22:16.130  1853  1853 D BluetoothHeadset: Proxy object disconnected
08-15 16:22:16.130  1036  1036 D BluetoothHeadset: Proxy object disconnected
08-15 16:22:16.130  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-15 16:22:16.132  3838  3838 D A2dpService: Received stop request...Stopping profile...
08-15 16:22:16.132  3838  4037 D A2dpStateMachine: Exit Disconnected: -1
,08-15 16:22:16.134  3838  3838 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-15 16:22:16.135  3838  3927 D BluetoothAdapterState: Stopping profile services that were post enabled
08-15 16:22:16.136  3838  3838 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-15 16:22:16.136  3838  3838 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-15 16:22:16.136  3838  3838 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3aaa5e40
08-15 16:22:16.138  1036  1036 D BluetoothA2dp: Proxy object disconnected
08-15 16:22:16.138  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-15 16:22:16.138  3838  3838 D HidService: Received stop request...Stopping profile...
08-15 16:22:16.138  3838  3838 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3aaa5e40
08-15 16:22:16.140  3838  3838 D HealthService: Received stop request...Stopping profile...
08-15 16:22:16.140  3838  3838 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3aaa5e40
08-15 16:22:16.140  6929  6929 D BluetoothInputDevice: Proxy object disconnected
08-15 16:22:16.140  6929  6929 D HidProfile: Bluetooth service disconnected
08-15 16:22:16.142  3838  3838 D PanService: Received stop request...Stopping profile...
08-15 16:22:16.142  3838  3838 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3aaa5e40
08-15 16:22:16.143  3838  3838 D HeadsetStateMachine: Unbinding service...
08-15 16:22:16.143  6929  6929 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-15 16:22:16.143  6929  6929 D PanProfile: Bluetooth service disconnected
,08-15 16:22:16.147  3838  3838 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-15 16:22:16.147  3838  3838 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-15 16:22:16.147  3838  3838 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-15 16:22:16.147  3838  3838 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-15 16:22:16.147  3838  3838 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-15 16:22:16.147  3838  3838 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-15 16:22:16.147  3838  3838 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-15 16:22:16.148  3838  3838 D BtGatt.DebugUtils: handleDebugAction() action=null
08-15 16:22:16.148  3838  3838 D BtGatt.GattService: Received stop request...Stopping profile...
08-15 16:22:16.148  3838  3838 D BtGatt.GattService: stop()
08-15 16:22:16.148  3838  3838 D BtGatt.AdvertiseManager: advertise clients cleared
08-15 16:22:16.149  3838  3838 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3aaa5e40
08-15 16:22:16.150  3838  3838 D BluetoothMapService: Received stop request...Stopping profile...
08-15 16:22:16.150  3838  3838 D BluetoothMapService: stop()
08-15 16:22:16.151  3838  3838 D BluetoothMapEmailAppObserver: deinitObservers()
08-15 16:22:16.151  6929  6929 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-15 16:22:16.151  3838  3838 D BluetoothMapEmailAppObserver: removeReceiver()
08-15 16:22:16.151  6929  6929 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-15 16:22:16.151  6929  6929 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-15 16:22:16.152  6929  6929 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-15 16:22:16.152  3838  3838 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3aaa5e40
08-15 16:22:16.153  6929  6929 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-15 16:22:16.153  3838  3838 I BluetoothA2dpServiceJni: cleanupNative
08-15 16:22:16.153  3838  4039 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-15 16:22:16.153  3838  3838 I GKI_LINUX: GKI_exit_task 2 done
08-15 16:22:16.153  3838  3838 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-15 16:22:16.154  3838  3838 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-15 16:22:16.154  3838  3838 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-15 16:22:16.154  3838  3838 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-15 16:22:16.154  3838  3838 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-15 16:22:16.154  3838  3838 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-15 16:22:16.154  3838  3838 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-15 16:22:16.154  3838  3838 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-15 16:22:16.155  3838  3838 V BluetoothMapService: Handler(): got msg=4
08-15 16:22:16.155  3838  3838 D BluetoothMapService: MAP Service closeService in
08-15 16:22:16.155  3838  3838 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-15 16:22:16.155  3838  3838 V BluetoothMapService: MAP Service closeService out
08-15 16:22:16.156  3838  3838 D BluetoothMapService: cleanup()
08-15 16:22:16.156  3838  3838 D BluetoothMapService: MAP Service closeService in
08-15 16:22:16.156  3838  3838 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-15 16:22:16.156  3838  3838 V BluetoothMapService: MAP Service closeService out
08-15 16:22:16.156  3838  3927 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-15 16:22:16.156  3838  3927 D BluetoothAdapterProperties: Setting state to 10
08-15 ,16:22:16.156  3838  3927 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-15 16:22:16.156  1036  1118 D BluetoothManagerService: Message: 60
08-15 16:22:16.156  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-15 16:22:16.157  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
,08-15 16:22:16.158  6929  6944 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-15 16:22:16.159  6929  6945 D BluetoothPbap: onBluetoothStateChange: up=false
08-15 16:22:16.159  1036  1118 D BluetoothHeadset: onBluetoothStateChange: up=false
08-15 16:22:16.160  1853  1869 D BluetoothHeadset: onBluetoothStateChange: up=false
08-15 16:22:16.161  1853  2462 D BluetoothHeadset: onBluetoothStateChange: up=false
08-15 16:22:16.161  6929  6944 D BluetoothMap: onBluetoothStateChange: up=false
08-15 16:22:16.162  3838  3927 I BluetoothAdapterState: Entering OffState
08-15 16:22:16.162  1036  1118 D BluetoothA2dp: onBluetoothStateChange: up=false
08-15 16:22:16.162  1853  1868 D BluetoothHeadset: onBluetoothStateChange: up=false
08-15 16:22:16.163  6929  6945 D BluetoothPan: onBluetoothStateChange on: false
08-15 16:22:16.164  1036  1118 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-15 16:22:16.164  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-15 16:22:16.168  1036  1118 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-15 16:22:16.168  1036  1118 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-15 16:22:16.168  1036  1118 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@772ad1 mBinding = false
08-15 16:22:16.168  6929  6929 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-15 16:22:16.169  6929  6929 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-15 16:22:16.169  6929  6929 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-15 16:22:16.169  1036  1118 D BluetoothManagerService: Sending unbind request.
08-15 16:22:16.169  6929  6929 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-15 16:22:16.169  7017  7038 V FormManager: Network unavailable.
08-15 16:22:16.169  6929  6929 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-15 16:22:16.169  6929  6929 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-15 16:22:16.172  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-15 16:22:16.174  1606  1606 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-15 16:22:16.176  6929  6929 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-15 16:22:16.177  6929  6929 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-15 16:22:16.177  6929  6929 D LGBluetoothEventManager: [BTUI] clear device connection state
08-15 16:22:16.178  1942  1942 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-15 16:22:16.178  1942  2100 D LGBluetoothAPIService: Message: 2
08-15 16:22:16.179  1942  2100 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@3ffac153 mBinding = false
08-15 16:22:16.179  1942  2100 D LGBluetoothAPIService: Sending unbind request.
08-15 16:22:16.181  6929  6929 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-15 16:22:16.184  6826  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 16:22:16.187  3838  3937 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-15 16:22:16.187  6826  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 16:22:16.188  3838  3838 I GKI_LINUX: GKI_exit_task 1 done
08-15 16:22:16.188  3838  3838 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-15 16:22:16.188  3838  3838 I BluetoothServiceJni: cleanupNative: return from cleanup
08-15 16:22:16.189  3838  3838 I art     : --- WEIRD: removing null entry 246
08-15 16:22:16.189  3838  3838 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-15 16:22:16.189  3838  3838 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-15 16:22:16.190  1606  1606 D BluetoothAdapter: 963613144: getState() :  mService = null. Returning STATE_OFF
08-15 16:22:16.191  1606  1606 D BluetoothAdapter: 963613144: getState() :  mService = null. Returning STATE_OFF
08-15 16:22:16.192  3838  3838 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-15 16:22:16.195  3838  3838 I art     : System.exit called, status: 0
08-15 16:22:16.195  3838  3838 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-15 16:22:16.198  7017  7038 V FormManager: Network unavailable.
08-15 16:22:16.200  4300  4300 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-15 16:22:16.200  4300  4300 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-15 16:22:16.202  4300  4300 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-15 16:22:16.204  4300  4300 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-15 16:22:16.213  6929  6929 D DockEventReceiver: finishStartingService: stopping service
08-15 16:22:16.216  6949  6949 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-15 16:22:16.216  6949  6949 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-15 16:22:16.216  6949  6949 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-15 16:22:16.217   319  3971 V AudioFlinger: 3838 died, releasing its sessions
08-15 16:22:16.217   319  3971 V AudioFlinger:  pid 1853 @ 0
08-15 16:22:16.217   319  3971 V AudioFlinger:  pid 3420 @ 1
08-15 16:22:16.217   319  3971 V AudioFlinger:  pid 3420 @ 2
08-15 16:22:16.217  6929  6929 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-15 16:22:16.219  4300  7049 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-15 16:22:16.223  4300  7050 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-15 16:22:16.223  4300  7050 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-15 16:22:16.299  1036  1978 I ActivityManager: Process com.android.bluetooth (pid 3838) has died
08-15 16:22:16.299  1036  1978 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,08-15 16:22:16.316  2131  2131 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-15 16:22:16.322  6929  6929 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-15 16:22:16.333  7017  7051 W FormManager: Network not available. Please check & try again.
08-15 16:22:16.335  6929  6929 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-15 16:22:16.354  6929  6929 D BluetoothPermissionRequest: onReceive
,08-15 16:22:16.358  7017  7052 V FormManager: Network unavailable.
08-15 16:22:16.361  6929  6929 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-15 16:22:16.361  6929  6929 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-15 16:22:16.365  6929  6929 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-15 16:22:16.429  1036  1945 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7053 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-15 16:22:16.433  7017  7052 V FormManager: Network unavailable.
08-15 16:22:16.442  1036  1787 I ActivityManager: Killing 6195:com.android.contacts/u0a19 (adj 15): empty #17
,08-15 16:22:16.605  1036  1915 W libprocessgroup: failed to open /acct/uid_10019/pid_6195/cgroup.procs: No such file or directory
,08-15 16:22:16.638  7053  7053 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-15 16:22:16.640  7053  7053 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-15 16:22:16.641  7053  7053 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-15 16:22:16.642  6977  6977 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-15 16:22:16.642  7053  7053 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-15 16:22:16.644  6977  6977 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-15 16:22:16.645  6977  6977 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-15 16:22:16.663  7053  7053 D BluetoothAdapterApp: Loading JNI Library
,08-15 16:22:16.692  6977  6977 D LgDataFeature: LgDataFeature() Constructor: none
,08-15 16:22:16.692  6977  6977 D LgDataFeature: LgDataFeature() Constructor Done, null
08-15 16:22:16.700  7053  7053 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@2669fb41 Instance Count = 1
08-15 16:22:16.701  6977  6977 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-15 16:22:16.702  6977  6977 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-15 16:22:16.702  6977  6977 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-15 16:22:16.702  6977  6977 V SoundPool: doLoad: loading sample sampleID=1
08-15 16:22:16.703  6977  6977 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,08-15 16:22:16.705  6977  7075 V SoundPool: Start decode
08-15 16:22:16.705  6977  7075 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-15 16:22:16.709   319   319 V MediaPlayerService: decode(23, 10857164, 17813)
08-15 16:22:16.709   319   319 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-15 16:22:16.709   319   319 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-15 16:22:16.709   319   319 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-15 16:22:16.709   319   319 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-15 16:22:16.709   319   319 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-15 16:22:16.709   319   319 V MediaPlayerService: player type = 3
08-15 16:22:16.709   319   319 V AwesomePlayer: AwesomePlayer create()
08-15 16:22:16.709  6721  6721 D UEI.SmartControl: QS Service created
08-15 16:22:16.710   319   319 V AwesomePlayer: reset_l() 
08-15 16:22:16.710   319   319 V AwesomePlayer: cancelPlayerEvents
08-15 16:22:16.710   319   319 V AwesomePlayer: setAudioSink() 
08-15 16:22:16.710   319   319 V AwesomePlayer: reset_l() 
08-15 16:22:16.710   319   319 V AudioCache: notify(0xb5474ac0, 8, 0, 0)
08-15 16:22:16.710   319   319 V AudioCache: ignored
08-15 16:22:16.710   319   319 V AwesomePlayer: cancelPlayerEvents
08-15 16:22:16.710   319   319 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-15 16:22:16.710   319   319 V AwesomePlayer: setDataSource_l dataSource
08-15 16:22:16.710   319   319 V LGParserOSAL: SniffLGParser start
08-15 16:22:16.711   319   319 V LGParserOSAL: MainType:5, SubType=0
08-15 16:22:16.711   319   319 V LGParserOSAL: #### check Mime : application/ogg
08-15 16:22:16.711   319   319 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-15 16:22:16.711   319   319 E MediaExtractor: Use LGExtractor :application/ogg 
08-15 16:22:16.711  6977  6977 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-15 16:22:16.718  6977  6977 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-15 16:22:16.718  7053  7053 D BluetoothAdapterApp: onCreate
08-15 16:22:16.718  6977  6977 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,08-15 16:22:16.735  6977  6977 V LGMDMManager: Create singleton instance
08-15 16:22:16.758   319   319 V LGParserOSAL: supported mime: application/ogg
08-15 16:22:16.758   319   319 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-15 16:22:16.758   319   319 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-15 16:22:16.758   319   319 V AwesomePlayer: mBitrate = -1 bits/sec
,08-15 16:22:16.758   319   319 V AwesomePlayer: AudioTrack Setting
08-15 16:22:16.759   319   319 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-15 16:22:16.759   319   319 V AwesomePlayer: setAudioSource() 
08-15 16:22:16.759   319   319 V MediaPlayerService: prepare
08-15 16:22:16.759   319   319 V AwesomePlayer: prepareAsync_l() 
08-15 16:22:16.759   319   319 V MediaPlayerService: wait for prepare
08-15 16:22:16.759   319  7076 V AwesomePlayer: onPrepareAsyncEvent() 
08-15 16:22:16.759   319  7076 V AwesomePlayer: initAudioDecoder() 
08-15 16:22:16.759   319  7076 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-15 16:22:16.759   319  7076 V AudioSystem: isOffloadSupported()
08-15 16:22:16.759   319  7076 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-15 16:22:16.759   319  7076 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-15 16:22:16.759   319  7076 I AudioFlinger: isAudioPlaybackHookOn() false
08-15 16:22:16.759   319  7076 V AwesomePlayer: getUseOffload() = 0 
08-15 16:22:16.759   319  7076 V OMXCodec: OMXCodec::Create
08-15 16:22:16.759   319  7076 V OMXCodec: findMatchingCodecs()
08-15 16:22:16.759   319  7076 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-15 16:22:16.760   319  7076 V OMXCodec: matchingCodecs.size()=1
08-15 16:22:16.760   319  7076 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-15 16:22:16.762   319  7076 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-15 16:22:16.762   319  7076 V LGCodecAdapter: LG Codec Adapter start
08-15 16:22:16.762   319  7076 V OMXCodec: OMXCodec Createtor
08-15 16:22:16.762   319  7076 V OMXCodec: setComponentRole
08-15 16:22:16.762   319  7076 V OMXCodec: configureCodec protected=0
08-15 16:22:16.762   319  7076 V LGCodecAdapter: called getLGCodecSpecificData
08-15 16:22:16.762   319  7076 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-15 16:22:16.762   319  7076 V LGCodecOSAL: Called LGconfigureCodecMETA
08-15 16:22:16.762   319  7076 V LGCodecOSAL: Called LGconfigureCodecMSG
08-15 16:22:16.762   319  7076 V LGCodecOSAL: Not support LGCodec
08-15 16:22:16.762   319  7076 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-15 16:22:16.762   319  7076 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-15 16:22:16.762   319  7076 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-15 16:22:16.762   319  7076 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-15 16:22:16.762   319  7076 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-15 16:22:16.762   319  7076 V AudioSystem: isOffloadSupported()
08-15 16:22:16.762   319  7076 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-15 16:22:16.762   319  7076 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-15 16:22:16.762   319  7076 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-15 16:22:16.762   319  7076 V OMXCodec: init()
08-15 16:22:16.762   319  7076 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-15 16:22:16.762   319  7076 V OMXCodec: allocateBuffers
08-15 16:22:16.762   319  7076 V OMXCodec: allocateBuffersOnPort portIndex=0
08-15 16:22:16.762   319  7076 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-15 16:22:16.763   319  7076 V OMXCodec: [OMX.google.vorb,is.decoder] allocated buffer 0xb040f240 on input port
08-15 16:22:16.763   319  7076 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f920 on input port
08-15 16:22:16.763   319  7076 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f9c0 on input port
08-15 16:22:16.763   319  7076 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa10 on input port
08-15 16:22:16.763   319  7076 V OMXCodec: allocateBuffersOnPort portIndex=1
08-15 16:22:16.763   319  7076 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-15 16:22:16.763   319  7076 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fab0 on output port
08-15 16:22:16.763   319  7076 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fd80 on output port
08-15 16:22:16.763   319  7076 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fdd0 on output port
08-15 16:22:16.763   319  7076 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1434420 on output port
08-15 16:22:16.763   319  7076 V OMXCodec: init() mAsyncCompletion wait!!! 
08-15 16:22:16.765  7053  7053 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-15 16:22:16.765  7053  7053 D ProfileConfigQcom: Adding HeadsetService
08-15 16:22:16.765  7053  7053 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-15 16:22:16.765  7053  7053 D ProfileConfigQcom: Adding A2dpService
08-15 16:22:16.765  7053  7053 D ProfileConfigQcom: [BTUI] HidService is supported
08-15 16:22:16.766  7053  7053 D ProfileConfigQcom: Adding HidService
08-15 16:22:16.766  7053  7053 D ProfileConfigQcom: [BTUI] HealthService is supported
08-15 16:22:16.766  7053  7053 D ProfileConfigQcom: Adding HealthService
08-15 16:22:16.766  7053  7053 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-15 16:22:16.767  7053  7053 D ProfileConfigQcom: [BTUI] PanService is supported
08-15 16:22:16.768  7053  7053 D ProfileConfigQcom: Adding PanService
08-15 16:22:16.768  7053  7053 D ProfileConfigQcom: [BTUI] GattService is supported
08-15 16:22:16.768   319  7079 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-15 16:22:16.768   319  7079 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-15 16:22:16.768  7053  7053 D ProfileConfigQcom: Adding GattService
08-15 16:22:16.768   319  7079 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-15 16:22:16.768   319  7076 V OMXCodec: init() mAsyncCompletion wait!!! 
08-15 16:22:16.768  7053  7053 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-15 16:22:16.769  7053  7053 D ProfileConfigQcom: Adding BluetoothMapService
08-15 16:22:16.769  7053  7053 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-15 16:22:16.771  7053  7053 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-15 16:22:16.774   319  7079 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-15 16:22:16.774   319  7079 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-15 16:22:16.774   319  7079 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
,08-15 16:22:16.776  6721  6721 I UEI.SmartControl: Service initServices...
08-15 16:22:16.776  6721  6721 D UEI.SmartControl: QS start get config
08-15 16:22:16.778   319  7076 V OMXCodec: init() mAsyncCompletion wait free! 
08-15 16:22:16.778   319  7076 V AwesomePlayer: finishAsyncPrepare_l() 
08-15 16:22:16.778   319  7076 V AudioCache: notify(0xb5474ac0, 5, 0, 0)
08-15 16:22:16.778   319  7076 V AudioCache: ignored
08-15 16:22:16.778   319  7076 V AudioCache: notify(0xb5474ac0, 1, 0, 0)
08-15 16:22:16.778   319  7076 V AudioCache: prepared
08-15 16:22:16.778   319   319 V AudioCache: wait - success
08-15 16:22:16.778   319   319 V MediaPlayerService: start
08-15 16:22:16.778   319   319 V AwesomePlayer: play_l() 
08-15 16:22:16.778   319   319 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-15 16:22:16.778   319   319 V AwesomePlayer: createAudioPlayer_l
08-15 16:22:16.778   319   319 V AwesomePlayer: seekAudioIfNecessary_l() 
08-15 16:22:16.778   319   319 V AwesomePlayer: startAudioPlayer_l() 
08-15 16:22:16.778   319   319 D AudioPlayer: start of Playback, useOffload 0
08-15 16:22:16.778   319   319 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-15 16:22:16.778   319   319 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-15 16:22:16.787  7053  7053 V LGMDMManagerInternal: Create singleton instance
08-15 16:22:16.799   319  7079 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-15 16:22:16.799   319  7079 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
,08-15 16:22:16.799   319  7079 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-15 16:22:16.802   319  7079 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-15 16:22:16.802   319  7079 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-15 16:22:16.802   319  7079 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-15 16:22:16.803   319  7079 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048496
08-15 16:22:16.803   319  7079 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-15 16:22:16.803   319  7079 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957049216
08-15 16:22:16.803   319  7079 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-15 16:22:16.803   319  7079 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957049296
08-15 16:22:16.803   319  7079 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-15 16:22:16.803   319  7079 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973975584
08-15 16:22:16.803   319  7079 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-15 16:22:16.803   319  7079 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-15 16:22:16.804   319  7079 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-15 16:22:16.804   319  7079 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-15 16:22:16.804   319  7079 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-15 16:22:16.804   319  7079 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-15 16:22:16.804   319  7079 V OMXCodec: allocateBuffersOnPort portIndex=1
08-15 16:22:16.804   319  7079 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-15 16:22:16.804   319  7079 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fdd0 on output port
08-15 16:22:16.804   319  7079 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fd80 on output port
08-15 16:22:16.804   319  7079 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fab0 on output port
08-15 16:22:16.804   319  7079 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7920 on output port
08-15 16:22:16.804   319  7079 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-15 16:22:16.804   319  7079 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-15 16:22:16.805   319   319 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-15 16:22:16.805   319   319 V AudioCache: notify(0xb5474ac0, 6, 0, 0)
08-15 16:22:16.805   319   319 V AudioCache: ignored
08-15 16:22:16.806   319   319 V MediaPlayerService: wait for playback complete
08-15 16:22:16.807   319  7084 V AudioCache: write(0xb040c000, 4096)
08-15 16:22:16.807   319  7084 V AudioCache: memcpy(0xac100000, 0xb040c000, 4096)
08-15 16:22:16.810   319  7084 V AudioCache: write(0xb040c000, 4096)
08-15 16:22:16.810   319  7084 V AudioCache: memcpy(0xac101000, 0xb040c000, 4096)
08-15 16:22:16.811   319  7084 V AudioCache: write(0xb040c000, 4096)
08-15 16:22:16.811   319  7084 V AudioCache: memcpy(0xac102000, 0xb040c000, 4096)
08-15 16:22:16.812   319  7084 V AudioCache: write(0xb040c000, 4096)
08-15 16:22:16.812   319  7084 V AudioCache: memcpy(0xac103000, 0xb040c000, 4096)
08-15 16:22:16.812   319  7084 V AudioCache: write(0xb040c000, 4096)
08-15 16:22:16.812   319  7084 V AudioCache: memcpy(0xac104000, 0xb040c000, 4096)
08-15 16:22:16.813   319  7084 V AudioCache: write(0xb040c000, 4096)
08-15 16:22:16.813   319  7084 V AudioCache: memcpy(0xac105000, 0xb040c000, 4096)
08-15 16:22:16.814   319  7084 V AudioCache: write(0xb040c000, 4096)
08-15 16:22:16.814   319  7084 V AudioCache: memcpy(0xac106000, 0xb040c000, 4096)
08-15 16:22:16.814   319  7084 V AudioCache: write(0xb040c000, 4096)
08-15 16:22:16.814   31,9  7084 V AudioCache: memcpy(0xac107000, 0xb040c000, 4096)
08-15 16:22:16.815   319  7084 V AudioCache: write(0xb040c000, 4096)
08-15 16:22:16.815   319  7084 V AudioCache: memcpy(0xac108000, 0xb040c000, 4096)
08-15 16:22:16.816   319  7084 V AudioCache: write(0xb040c000, 4096)
08-15 16:22:16.816   319  7084 V AudioCache: memcpy(0xac109000, 0xb040c000, 4096)
08-15 16:22:16.817   319  7084 V AudioCache: write(0xb040c000, 4096)
08-15 16:22:16.817   319  7084 V AudioCache: memcpy(0xac10a000, 0xb040c000, 4096)
08-15 16:22:16.817   319  7084 V AudioCache: write(0xb040c000, 4096)
08-15 16:22:16.817   319  7084 V AudioCache: memcpy(0xac10b000, 0xb040c000, 4096)
08-15 16:22:16.818   319  7084 V AudioCache: write(0xb040c000, 4096)
08-15 16:22:16.818   319  7084 V AudioCache: memcpy(0xac10c000, 0xb040c000, 4096)
08-15 16:22:16.819   319  7084 V AudioCache: write(0xb040c000, 4096)
08-15 16:22:16.819   319  7084 V AudioCache: memcpy(0xac10d000, 0xb040c000, 4096)
08-15 16:22:16.819   319  7084 V AudioCache: write(0xb040c000, 4096)
08-15 16:22:16.819   319  7084 V AudioCache: memcpy(0xac10e000, 0xb040c000, 4096)
08-15 16:22:16.820   319  7084 V AudioCache: write(0xb040c000, 4096)
08-15 16:22:16.820   319  7084 V AudioCache: memcpy(0xac10f000, 0xb040c000, 4096)
08-15 16:22:16.821   319  7084 V AudioCache: write(0xb040c000, 4096)
08-15 16:22:16.821   319  7084 V AudioCache: memcpy(0xac110000, 0xb040c000, 4096)
08-15 16:22:16.821   319  7084 V AudioCache: write(0xb040c000, 4096)
08-15 16:22:16.821   319  7084 V AudioCache: memcpy(0xac111000, 0xb040c000, 4096)
08-15 16:22:16.822   319  7084 V AudioCache: write(0xb040c000, 4096)
08-15 16:22:16.822   319  7084 V AudioCache: memcpy(0xac112000, 0xb040c000, 4096)
08-15 16:22:16.823   319  7084 V AudioCache: write(0xb040c000, 4096)
08-15 16:22:16.823   319  7084 V AudioCache: memcpy(0xac113000, 0xb040c000, 4096)
08-15 16:22:16.823   319  7084 V AudioCache: write(0xb040c000, 4096)
08-15 16:22:16.823   319  7084 V AudioCache: memcpy(0xac114000, 0xb040c000, 4096)
08-15 16:22:16.824   319  7084 V AudioCache: write(0xb040c000, 4096)
08-15 16:22:16.824   319  7084 V AudioCache: memcpy(0xac115000, 0xb040c000, 4096)
08-15 16:22:16.825   319  7084 V AudioCache: write(0xb040c000, 4096)
08-15 16:22:16.825   319  7084 V AudioCache: memcpy(0xac116000, 0xb040c000, 4096)
08-15 16:22:16.825   319  7084 V AudioCache: write(0xb040c000, 4096)
08-15 16:22:16.825   319  7084 V AudioCache: memcpy(0xac117000, 0xb040c000, 4096)
08-15 16:22:16.826   319  7084 V AudioCache: write(0xb040c000, 4096)
08-15 16:22:16.826   319  7084 V AudioCache: memcpy(0xac118000, 0xb040c000, 4096)
08-15 16:22:16.827  6977  6977 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-15 16:22:16.827   319  7084 V AudioCache: write(0xb040c000, 4096)
08-15 16:22:16.827   319  7084 V AudioCache: memcpy(0xac119000, 0xb040c000, 4096)
08-15 16:22:16.828  6977  6977 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-15 16:22:16.830   319  7084 V AudioCache: write(0xb040c000, 4096)
,08-15 16:22:16.830   319  7084 V AudioCache: memcpy(0xac11a000, 0xb040c000, 4096)
08-15 16:22:16.831  6977  6977 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:7177
08-15 16:22:16.831   319  7084 V AudioCache: write(0xb040c000, 4096)
08-15 16:22:16.831   319  7084 V AudioCache: memcpy(0xac11b000, 0xb040c000, 4096)
08-15 16:22:16.832   319  7084 V AudioCache: write(0xb040c000, 4096)
08-15 16:22:16.832   319  7084 V AudioCache: memcpy(0xac11c000, 0xb040c000, 4096)
08-15 16:22:16.833   319  7084 V AudioCache: write(0xb040c000, 4096)
08-15 16:22:16.833   319  7084 V AudioCache: memcpy(0xac11d000, 0xb040c000, 4096)
08-15 16:22:16.833   319  7084 V AudioCache: write(0xb040c000, 4096)
08-15 16:22:16.833   319  7084 V AudioCache: memcpy(0xac11e000, 0xb040c000, 4096)
08-15 16:22:16.834   319  7084 V AudioCache: write(0xb040c000, 4096)
08-15 16:22:16.834   319  7084 V AudioCache: memcpy(0xac11f000, 0xb040c000, 4096)
,08-15 16:22:16.835   319  7084 V AudioCache: write(0xb040c000, 4096)
08-15 16:22:16.835   319  7084 V AudioCache: memcpy(0xac120000, 0xb040c000, 4096)
08-15 16:22:16.835   319  7084 V AudioCache: write(0xb040c000, 4096)
08-15 16:22:16.835   319  7084 V AudioCache: memcpy(0xac121000, 0xb040c000, 4096)
08-15 16:22:16.836   319  7084 V AudioCache: write(0xb040c000, 4096)
08-15 16:22:16.836   319  7084 V AudioCache: memcpy(0xac122000, 0xb040c000, 4096)
08-15 16:22:16.837   319  7084 V AudioCache: write(0xb040c000, 4096)
08-15 16:22:16.837   319  7084 V AudioCache: memcpy(0xac123000, 0xb040c000, 4096)
08-15 16:22:16.837  6929  6929 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-15 16:22:16.838   319  7084 V AudioCache: write(0xb040c000, 4096)
08-15 16:22:16.838   319  7084 V AudioCache: memcpy(0xac124000, 0xb040c000, 4096)
08-15 16:22:16.839   319  7084 V AudioCache: write(0xb040c000, 4096)
08-15 16:22:16.839   319  7084 V AudioCache: memcpy(0xac125000, 0xb040c000, 4096)
08-15 16:22:16.840   319  7084 V AudioCache: write(0xb040c000, 4096)
08-15 16:22:16.840   319  7084 V AudioCache: memcpy(0xac126000, 0xb040c000, 4096)
08-15 16:22:16.841   319  7084 V AudioCache: write(0xb040c000, 4096)
08-15 16:22:16.841   319  7084 V AudioCache: memcpy(0xac127000, 0xb040c000, 4096)
08-15 16:22:16.843   319  7084 V AudioCache: write(0xb040c000, 4096)
08-15 16:22:16.843   319  7084 V AudioCache: memcpy(0xac128000, 0xb040c000, 4096)
08-15 16:22:16.843   319  7084 V AudioCache: write(0xb040c000, 4096)
08-15 16:22:16.843   319  7084 V AudioCache: memcpy(0xac129000, 0xb040c000, 4096)
08-15 16:22:16.844   319  7084 V AudioCache: write(0xb040c000, 4096)
08-15 16:22:16.844   319  7084 V AudioCache: memcpy(0xac12a000, 0xb040c000, 4096)
08-15 16:22:16.845   319  7084 V AudioCache: write(0xb040c000, 4096)
08-15 16:22:16.845   319  7084 V AudioCache: memcpy(0xac12b000, 0xb040c000, 4096)
08-15 16:22:16.846   319  7084 V AudioCache: write(0xb040c000, 4096)
08-15 16:22:16.846   319  7084 V AudioCache: memcpy(0xac12c000, 0xb040c000, 4096)
08-15 16:22:16.846   319  7084 V AudioCache: write(0xb040c000, 4096)
08-15 16:22:16.846   319  7084 V AudioCache: memcpy(0xac12d000, 0xb040c000, 4096)
08-15 16:22:16.847   319  7084 V AudioCache: write(0xb040c000, 4096)
08-15 16:22:16.847   319  7084 V AudioCache: memcpy(0xac12e000, 0xb040c000, 4096)
08-15 16:22:16.847   319  7084 V AudioCache: write(0xb040c000, 4096)
08-15 16:22:16.847   319  7084 V AudioCache: memcpy(0xac12f000, 0xb040c000, 4096)
08-15 16:22:16.848   319  7084 V AudioCache: write(0xb040c000, 4096)
08-15 16:22:16.848   319  7084 V AudioCache: memcpy(0xac130000, 0xb040c000, 4096)
08-15 16:22:16.849   319  7084 V AudioCache: write(0xb040c000, 4096)
08-15 16:22:16.849   319  7084 V AudioCache: memcpy(0xac131000, 0xb040c000, 4096)
08-15 16:22:16.849   319  7079 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-15 16:22:16.849   319  7084 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-15 16:22:16.849   319  7084 V AwesomePlayer: postAudioEOS() 
08-15 16:22:16.849   319  7084 V AudioCache: write(0xb040c000, 280)
08-15 16:22:16.849   319  7084 V AudioCache: memcpy(0xac132000, 0xb040c000, 280)
08-15 16:22:16.853   319  7076 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-15 16:22:16.853   319  7076 V AwesomePlayer: onStreamDone
08-15 16:22:16.853   319  7076 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-15 16:22:16.853   319  7076 V AudioCache: notify(0xb5474ac0, 2, 0, 0)
08-15 16:22:16.853   319  7076 V AudioCache: playback complete
08-15 16:22:16.853   319  7076 V AwesomePlayer: pause_l() 
08-15 16:22:16.853   319  7076 V AudioCache: notify(0xb5474ac0, 7, 0, 0)
08-15 16:22:16.853   319  7076 V AudioCache: ignored
08-15 16:22:16.853   319  7076 V AwesomePlayer: cancelPlayerEvents
08-15 16:22:16.853   319   319 V AudioCache: wait - success
08-15 16:22:16.853   319   319 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-1,5 16:22:16.853   319  7076 D AudioPlayer: Pause Playback at 1068125
08-15 16:22:16.854   319   319 V AwesomePlayer: reset_l() 
08-15 16:22:16.854   319   319 V AudioCache: notify(0xb5474ac0, 8, 0, 0)
08-15 16:22:16.854   319   319 V AudioCache: ignored
08-15 16:22:16.854   319   319 V AwesomePlayer: cancelPlayerEvents
08-15 16:22:16.854   319   319 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-15 16:22:16.854   319   319 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-15 16:22:16.854   319   319 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-15 16:22:16.854   319   319 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-15 16:22:16.854   319   319 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-15 16:22:16.855   319  7079 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-15 16:22:16.855   319  7079 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-15 16:22:16.855   319  7079 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-15 16:22:16.855   319  7079 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fa10 on port 0
08-15 16:22:16.855   319  7079 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-15 16:22:16.855   319  7079 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f9c0 on port 0
08-15 16:22:16.855   319  7079 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-15 16:22:16.855   319  7079 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f920 on port 0
08-15 16:22:16.855   319  7079 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-15 16:22:16.855   319  7079 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f240 on port 0
08-15 16:22:16.855   319  7079 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-15 16:22:16.855   319  7079 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-15 16:22:16.855   319  7079 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7920 on port 1
08-15 16:22:16.855   319  7079 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-15 16:22:16.855   319  7079 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fab0 on port 1
08-15 16:22:16.855   319  7079 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-15 16:22:16.855   319  7079 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fd80 on port 1
08-15 16:22:16.855   319  7079 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-15 16:22:16.855   319  7079 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fdd0 on port 1
08-15 16:22:16.855   319  7079 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-15 16:22:16.855   319  7079 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-15 16:22:16.855   319   319 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-15 16:22:16.855   319   319 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-15 16:22:16.856   319  7079 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-15 16:22:16.856   319  7079 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-15 16:22:16.856   319  7079 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-15 16:22:16.856   319   319 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-15 16:22:16.856   319   319 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-15 16:22:16.856   319   319 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-15 16:22:16.857   319   319 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-15 16:22:16.857   319   319 D AudioPlayer: AudioPlayer releasing audio source
08-15 16:22:16.857   319   319 D AudioPlayer: AudioPlayer done releasing audio source
08-15 16:22:16.857   319   319 V AwesomePlayer: reset_l() 
08-15 1,6:22:16.857   319   319 V AwesomePlayer: cancelPlayerEvents
08-15 16:22:16.857   319   319 V AwesomePlayer: ~AwesomePlayer call
08-15 16:22:16.858   319   319 V AwesomePlayer: reset_l() 
08-15 16:22:16.858   319   319 V AwesomePlayer: cancelPlayerEvents
08-15 16:22:16.858  6977  7075 V SoundPool: close(31)
08-15 16:22:16.858  6977  7075 V SoundPool: pointer = 0x9fe78000, size = 205080, sampleRate = 48000, numChannels = 2
08-15 16:22:16.895  7053  7053 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-15 16:22:16.898  7053  7053 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-15 16:22:16.899  7053  7053 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-15 16:22:16.899  7053  7053 V BluetoothSapReceiver: SapReceiver onReceive 
08-15 16:22:16.899  7053  7053 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-15 16:22:16.900  7053  7053 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-15 16:22:16.910  6994  6994 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-15 16:22:17.094  6721  6721 I UEI.SmartControl: Supports setup maps: true
08-15 16:22:17.096  6721  6721 D UEI.SmartControl: QS start statue = true Error code = 0
08-15 16:22:17.096  6721  6721 I UEI.SmartControl: QS version = v2.7.10.1_RC1
,08-15 16:22:17.097  6721  6721 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-15 16:22:17.097  6721  6721 I UEI.SmartControl: ### init IR Blaster...
,08-15 16:22:17.100  6721  6721 D serial_port: Configuring serial port
08-15 16:22:17.100  6721  6721 E UEI.SmartControl: UEIBLaster setting for 616
08-15 16:22:17.100  6721  6721 I UEI.SmartControl: Setting serial record hearder size = 2
08-15 16:22:17.100  6721  6721 I UEI.SmartControl: configuring settings for MAXQ616
08-15 16:22:17.100  6721  6721 I UEI.SmartControl: Get version...
08-15 16:22:17.119  6721  7087 D UEI.SmartControl: serial port data available: 21
,08-15 16:22:17.144  6721  6721 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-15 16:22:17.144  6721  6721 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-15 16:22:17.144  6721  6721 I UEI.SmartControl: QS saving settings...
08-15 16:22:17.145  6721  6721 D UEI.SmartControl: IR Blaster version: 25672567
,08-15 16:22:17.161  6721  7087 D UEI.SmartControl: serial port data available: 4
,08-15 16:22:17.194  6721  6721 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-15 16:22:17.195  6721  7093 I UEI.SmartControl: Device manager: loading config....
,08-15 16:22:17.197  6721  6721 E UEI.SmartControl: Services init done
,08-15 16:22:17.198  6721  6721 D UEI.SmartControl: QS Service init finished
08-15 16:22:17.198  6721  7093 D UEI.SmartControl: ----------- loading internal config...
08-15 16:22:17.200  6721  6721 D UEI.SmartControl: QS Service version name: 2.1.91
08-15 16:22:17.200  6721  6721 D UEI.SmartControl: QS Service version code: 201091
08-15 16:22:17.201  6721  6721 D UEI.SmartControl: Service requested: Control
08-15 16:22:17.217  6721  7093 E UEI.SmartControl: Loading SETTINGS...
08-15 16:22:17.220  6721  6721 D UEI.SmartControl: Request IControl service: devices are loaded...
,08-15 16:22:17.229  6977  6977 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-15 16:22:17.231  6721  6721 D UEI.SmartControl: Internal service binding...
08-15 16:22:17.232  6721  6759 I UEI.SmartControl: ------ IControl API: 11
08-15 16:22:17.232  6721  6759 D UEI.SmartControl: File observer start...
08-15 16:22:17.232  6721  6759 E UEI.SmartControl: IR Port is disabled: false
08-15 16:22:17.233  6721  6759 D UEI.SmartControl: Starting file observer...
08-15 16:22:17.234  6721  6759 I UEI.SmartControl: Registering callback...
08-15 16:22:17.236  6721  6737 I UEI.SmartControl: ------ IControl API: 19
08-15 16:22:17.237  6721  7093 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-15 16:22:17.239  6721  6737 I UEI.SmartControl: Registering Services Ready callback...
,08-15 16:22:17.255  6721  7092 I UEI.SmartControl: Notify AllClients services are ready: 0
08-15 16:22:17.256  6721  7092 D UEI.SmartControl: -----service ready thread exits
,08-15 16:22:17.256  6977  6992 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-15 16:22:17.257  6977  7073 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-15 16:22:17.257  6977  7073 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-15 16:22:17.258  6977  6977 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-15 16:22:17.258  6977  6977 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-15 16:22:17.258  6721  6736 I UEI.SmartControl: ------ IControl API: 8
08-15 16:22:17.260  6977  6977 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-15 16:22:17.260  6977  6977 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-15 16:22:17.261  6977  6977 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-15 16:22:17.261  6977  6977 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-15 16:22:17.262  6977  6977 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-15 16:22:17.262  6977  6977 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-15 16:22:17.266  6977  6977 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-15 16:22:17.267  6977  6977 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,08-15 16:22:17.271  6977  6977 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-15 16:22:17.271  6977  6977 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-15 16:22:17.272  6977  6977 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-15 16:22:17.273  6977  6977 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-15 16:22:17.274  6977  6977 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-15 16:22:17.274  6977  6977 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-15 16:22:17.275  6977  6977 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1471270937275]
08-15 16:22:17.277  6977  6977 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-15 16:22:17.279  1036  1901 I ActivityManager: Killing 6216:com.android.gallery3d/u0a27 (adj 15): empty #17
,08-15 16:22:17.299  6977  7098 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-15 16:22:17.318  1036  1901 I ActivityManager: Killing 6604:com.lge.email/u0a23 (adj 15): empty #18
,08-15 16:22:17.347  1036  1787 W libprocessgroup: failed to open /acct/uid_10027/pid_6216/cgroup.procs: No such file or directory
,08-15 16:22:17.355  1036  1597 W libprocessgroup: failed to open /acct/uid_10023/pid_6604/cgroup.procs: No such file or directory
08-15 16:22:17.355  6977  6977 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-15 16:22:17.357  6977  6977 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-15 16:22:17.357  6977  6977 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-15 16:22:17.358  6977  6977 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-15 16:22:17.358  6977  6977 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-15 16:22:17.359  6977  6977 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-15 16:22:17.359  6977  6977 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-15 16:22:17.370  6977  6977 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-15 16:22:18.029  1036  2025 D WifiServiceImplEx: setWifiEnabled: true pid=6826, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-15 16:22:18.030  1036  2025 D WifiService: setWifiEnabled: true pid=6826, uid=10118
08-15 16:22:18.031  1036  2025 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-15 16:22:18.054  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-15 16:22:18.054  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-15 16:22:18.054  1036  1036 D Ulp_jni : JNI:system_update. Event-4
,08-15 16:22:18.058  1036  1422 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-15 16:22:18.058  1036  1422 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-15 16:22:18.061  1036  1422 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-15 16:22:18.061  1036  1422 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-15 16:22:18.061  1036  1422 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-15 16:22:18.061  1036  1422 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-15 16:22:18.061  1036  1422 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-15 16:22:18.061  1036  1422 E WifiHW  : unknown target_country: EU , set to default
08-15 16:22:18.061  1036  1422 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-15 16:22:18.061  1036  1422 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-15 16:22:18.061  1036  1422 I WifiUtil: gEnableBmps=1
08-15 16:22:18.115  1036  1477 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-15 16:22:18.133  1036  1118 D Tethering: MasterInitialState.processMessage what=3
,08-15 16:22:18.144  6826  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 16:22:18.146  6826  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-15 16:22:18.152  1036  1477 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-15 16:22:18.154  1036  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-15 16:22:18.155  6515  6515 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-15 16:22:18.160  1036  1118 D Tethering: MasterInitialState.processMessage what=3
,08-15 16:22:18.171  6826  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 16:22:18.172  6826  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 16:22:18.177  5786  5786 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-15 16:22:18.190  5786  5786 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-15 16:22:18.194  6515  6948 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-15 16:22:18.229  2131  2131 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-15 16:22:18.284  1036  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-15 16:22:18.311  1036  2025 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7117 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-15 16:22:18.314  1036  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-15 16:22:18.314  1036  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-15 16:22:18.394  7117  7117 I AppUp4:AppBoxCP: onCreate
08-15 16:22:18.395  7117  7117 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,08-15 16:22:18.405  7117  7117 I AppUp4:DB:  setFingerPrint start
08-15 16:22:18.405  7117  7117 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-15 16:22:18.414  7117  7117 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-15 16:22:18.414  7117  7117 I AppUp4:DB:  SDK version = 21
08-15 16:22:18.414  7117  7117 I AppUp4:DB:  beforefinger == newfinger no write in DB
,08-15 16:22:18.417  7117  7117 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-15 16:22:18.418  7117  7117 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-15 16:22:18.419  7117  7117 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-15 16:22:18.421  7117  7117 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-15 16:22:18.421  7117  7117 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-15 16:22:18.430  7117  7117 I AppUp4:CustModeStarterReceiver: onReceive
,08-15 16:22:18.470  7117  7117 D LgDataFeature: LgDataFeature() Constructor: none
,08-15 16:22:18.470  7117  7117 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-15 16:22:18.479  7117  7117 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@227395c3
08-15 16:22:18.479  7117  7117 D AppUp4:CustFacade: isCustomizationCompleted : false
08-15 16:22:18.480  7117  7117 D AppUp4:CustFacade: isPhone : true
08-15 16:22:18.481  7117  7117 D AppUp4:CustModeStarterReceiver: begin check event
08-15 16:22:18.482  7117  7117 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-15 16:22:18.483  7117  7117 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-15 16:22:18.484  7117  7135 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-15 16:22:18.484  7117  7135 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-15 16:22:18.485  7117  7135 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-15 16:22:18.486  1036  1901 I ActivityManager: Killing 6638:com.google.android.apps.docs/u0a61 (adj 15): empty #17
08-15 16:22:18.554  1036  1978 W libprocessgroup: failed to open /acct/uid_10061/pid_6638/cgroup.procs: No such file or directory
08-15 16:22:18.555  4300  4300 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-15 16:22:18.555  4300  4300 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-15 16:22:18.561  4300  4300 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-15 16:22:18.567  4300  4300 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-15 16:22:18.576  4300  7145 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-15 16:22:18.577  4300  7146 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-15 16:22:18.577  4300  7146 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-15 16:22:18.651  1036  2025 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7148 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-15 16:22:18.723  1036  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-15 16:22:18.725  1036  1118 D Tethering: InitialState.processMessage what=4
08-15 16:22:18.726   312   894 D SoftapController: Softap fwReload - Ok
08-15 16:22:18.727  1036  1422 E NetdConnector: NDC Command {52 softap fwreload wlan0 STA} took too long (660ms)
08-15 16:22:18.732  1036  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-15 16:22:18.733   312   894 D CommandListener: Setting iface cfg
,08-15 16:22:18.733   312   894 D CommandListener: Trying to bring down wlan0
08-15 16:22:18.734  7148  7148 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-15 16:22:18.735  7148  7148 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-15 16:22:18.736   312   894 D CommandListener: Clearing all IP addresses on wlan0
08-15 16:22:18.736  7148  7148 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-15 16:22:18.737  7148  7148 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-15 16:22:18.739  1036  1422 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-15 16:22:18.741  1036  1422 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-15 16:22:18.741  1036  1422 E WifiStateMachine: useWiFiOffloading() : false
08-15 16:22:18.741  1036  1422 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-15 16:22:18.741  1036  1422 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-15 16:22:18.741  1036  1422 D WifiMonitor: connecting to supplicant
08-15 16:22:18.742  1036  1422 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
08-15 16:22:18.744  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-15 16:22:18.745  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-15 16:22:18.746  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-15 16:22:18.746  6826  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 16:22:18.747  6826  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 16:22:18.747  7166  7166 W wpa_supplicant: type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-15 16:22:18.747  7166  7166 W wpa_supplicant: type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-15 16:22:18.776  7166  7166 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-15 16:22:18.810  7166  7166 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-15 16:22:18.811  7166  7166 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-15 16:22:18.829  7148  7148 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-15 16:22:18.843  7148  7148 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-15 16:22:18.873  7148  7148 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-15 16:22:18.896  7166  7166 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-15 16:22:18.898  7148  7148 D LgDataFeature: LgDataFeature() Constructor: none
,08-15 16:22:18.898  7148  7148 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-15 16:22:18.965  7166  7166 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-15 16:22:18.974  7166  7166 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
,08-15 16:22:18.975  7166  7166 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
,08-15 16:22:19.043  7148  7148 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-15 16:22:19.092  3420  3420 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-15 16:22:19.092  3420  3420 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
,08-15 16:22:19.092  3420  3420 I LgeMiscReceiver: networkInfo.isConnected() = false
08-15 16:22:19.100  7148  7148 I HubEmail: JNI_OnLoad()
08-15 16:22:19.101  7148  7148 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-15 16:22:19.101  7148  7148 I HubEmail: registerNatives()
08-15 16:22:19.101  7148  7148 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-15 16:22:19.101  7148  7148 I HubEmail: registerNativeMethods()
08-15 16:22:19.101  7148  7148 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-15 16:22:19.101  7148  7148 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
08-15 16:22:19.144  1036  1052 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7179 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-15 16:22:19.151  7017  7176 W FormManager: Network not available. Please check & try again.
08-15 16:22:19.154  7148  7178 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 16:22:19.157  7017  7177 V FormManager: Network unavailable.
08-15 16:22:19.161  7017  7177 V FormManager: Network unavailable.
,08-15 16:22:19.170  1036  1978 I ActivityManager: Killing 6242:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,08-15 16:22:19.206  1036  2025 W libprocessgroup: failed to open /acct/uid_10080/pid_6242/cgroup.procs: No such file or directory
,08-15 16:22:19.286  7179  7179 D LgDataFeature: LgDataFeature() Constructor: none
,08-15 16:22:19.286  7179  7179 D LgDataFeature: LgDataFeature() Constructor Done, null
08-15 16:22:19.290  7179  7179 D PhoneMonitor: Register our PhoneStateListener
,08-15 16:22:19.314  7179  7179 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-15 16:22:19.323  7179  7179 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-15 16:22:19.342  7179  7179 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,08-15 16:22:19.344  7179  7179 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-15 16:22:19.346  7179  7179 D TelephonyAutoProfiling: [parse] Load xml
08-15 16:22:19.352  7179  7179 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-15 16:22:19.352  7179  7179 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-15 16:22:19.352  7179  7179 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-15 16:22:19.352  7179  7179 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-15 16:22:19.352  7179  7179 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-15 16:22:19.352  7179  7179 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-15 16:22:19.352  7179  7179 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-15 16:22:19.352  7179  7179 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-15 16:22:19.352  7179  7179 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-15 16:22:19.352  7179  7179 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-15 16:22:19.353  7179  7179 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-15 16:22:19.353  7179  7179 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-15 16:22:19.353  7179  7179 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-15 16:22:19.353  7179  7179 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-15 16:22:19.353  7179  7179 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-15 16:22:19.353  7179  7179 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-15 16:22:19.353  7179  7179 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-15 16:22:19.364  7179  7179 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-15 16:22:19.378  1036  1052 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7198 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-15 16:22:19.381  1036  1052 I ActivityManager: Killing 6092:com.google.android.apps.plus/u0a97 (adj 15): empty #17
08-15 16:22:19.439  1036  2046 W libprocessgroup: failed to open /acct/uid_10097/pid_6092/cgroup.procs: No such file or directory
,08-15 16:22:19.633  7166  7166 E wpa_supplicant: USIM:  scard_init function
08-15 16:22:19.635  7166  7166 I wpa_supplicant: Trying to associate with SSID 'NG700'
,08-15 16:22:19.639  1036  1918 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7216 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,08-15 16:22:19.641  1036  1918 I ActivityManager: Killing 6673:com.lge.eula/1000 (adj 15): empty #17
08-15 16:22:19.709  1036  2025 W libprocessgroup: failed to open /acct/uid_1000/pid_6673/cgroup.procs: No such file or directory
,08-15 16:22:19.744  7166  7166 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-15 16:22:19.750  1036  1118 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-15 16:22:19.752  1036  1422 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-15 16:22:19.752  1036  1422 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-15 16:22:19.753  1036  1422 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-15 16:22:19.755  7166  7166 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-15 16:22:19.755  7166  7166 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-15 16:22:19.756  1036  1422 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-15 16:22:19.757  1036  1422 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-15 16:22:19.758  1036  1422 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-15 16:22:19.759  1036  1422 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-15 16:22:19.760  1036  7233 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-15 16:22:19.760  1036  1422 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-15 16:22:19.760  1036  7233 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-15 16:22:19.761  1036  7233 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-15 16:22:19.761  1036  7233 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-15 16:22:19.761  1036  7233 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-15 16:22:19.761  1036  7233 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-15 16:22:19.761  1036  7233 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-15 16:22:19.762  1036  7233 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-15 16:22:19.762  1036  1422 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-15 16:22:19.762  1036  1422 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-15 16:22:19.762  1036  7233 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-15 16:22:19.762  1036  7233 E WifiMonitor: WifiMonitor:wlan0 cnt=25 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-15 16:22:19.762  1036  1422 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-15 16:22:19.763  1036  1422 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-15 16:22:19.763  1036  1422 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-15 16:22:19.764  1036  1422 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-15 16:22:19.764  1036  1422 E WifiStateMachine: useWiFiOffloading() : false
08-15 16:22:19.764  1036  1422 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-15 16:22:19.764  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 16:22:19.764  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 16:22:19.764  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 16:22:19.764  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 16:22:19.764  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-15 16:22:19.764  1036  1422 D WifiNative-wlan0: doBoolean: SET update_config 1
08-15 16:22:19.766  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-15 16:22:19.767  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-15 16:22:19.768  1036  1442 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-15 16:22:19.768  1942  1942 D WfdService: Waiting for WifiP2p enabling
08-15 16:22:19.769  6826  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-15 16:22:19.769  6826  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-15 16:22:19.769  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 16:22:19.769  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-15 16:22:19.769  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-15 16:22:19.769  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-15 16:22:19.769  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-15 16:22:19.769  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-15 16:22:19.769  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-15 16:22:19.769  6826  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-15 16:22:19.769  6826  6826 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-15 16:22:19.770  6826  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-15 16:22:19.771  6826  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-15 16:22:19.771  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 16:22:19.771  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-15 16:22:19.771  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-15 16:22:19.771  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-15 16:22:19.771  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-15 16:22:19.771  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-15 16:22:19.771  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-15 16:22:19.771  6826  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-15 16:22:19.771  6826  6826 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-15 16:22:19.778  1036  1422 D WifiNative-wlan0: SET update_config 1: returned true
08-15 16:22:19.778  1036  1422 D WifiConfigStore: Loading config and enabling all networks 
08-15 16:22:19.778  1036  1422 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-15 16:22:19.779  1036  1422 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	[CURRENT]
08-15 16:22:19.787  1036  1422 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-15 16:22:19.797  1036  1422 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-15 16:22:19.797  1036  1422 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-15 16:22:19.822  1036  1787 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7234 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-15 16:22:19.823  1036  1787 I ActivityManager: Killing 6695:com.lge.bnr/1000 (adj 15): empty #17
08-15 16:22:19.844   344   344 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 474us total 22.333ms
,08-15 16:22:19.868   344   344 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 448us total 20.545ms
,08-15 16:22:19.889   344   344 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 447us total 20.703ms
,08-15 16:22:19.909  1036  1422 D WifiStateMachine: enableVerboseLogging : level 2
08-15 16:22:19.909  1036  1422 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-15 16:22:19.910  1036  1422 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-15 16:22:19.910  1036  1422 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-15 16:22:19.910  1036  1901 W libprocessgroup: failed to open /acct/uid_1000/pid_6695/cgroup.procs: No such file or directory
08-15 16:22:19.910  1036  1422 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-15 16:22:19.910  1036  1422 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-15 16:22:19.911  1036  1422 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-15 16:22:19.911  1036  1422 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-15 16:22:19.911  1036  1422 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-15 16:22:19.911  1036  1422 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
,08-15 16:22:19.912  1036  1422 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-15 16:22:19.912  1036  1422 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-15 16:22:19.912  1036  1422 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-15 16:22:19.912  1036  1422 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
,08-15 16:22:19.913  1036  1422 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-15 16:22:19.917  1036  1422 D WifiStateMachine: Setting OUI to DA-A1-19
08-15 16:22:19.917  1036  1422 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
,08-15 16:22:19.917  1942  1942 D WfdsService: Supplicant Connection state is changed : true
08-15 16:22:19.918  1942  2262 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-15 16:22:19.918  1942  2262 D WfdsService: Set the WFDS Monitor: true
08-15 16:22:19.918  1942  2262 D WfdsMonitor: WfdsMonitorThread create
08-15 16:22:19.918  1036  1422 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-15 16:22:19.918  1036  1422 D WifiNative-HAL: Setting external_sim to 1
08-15 16:22:19.918  1036  1422 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-15 16:22:19.919  1942  2262 D WfdsMonitor: WFDS Monitor is created and started
,08-15 16:22:19.919  1942  2262 D WfdsService: WiFi: Supplicant connection re-established,
,08-15 16:22:19.919  1036  1422 D WifiNative-wlan0: SET external_sim 1: returned true
08-15 16:22:19.919  1036  1422 I WifiNative-HAL: startHal
08-15 16:22:19.919  1036  1422 D wifi    : setting scan oui 0xaf52e780
,08-15 16:22:19.919  1942  7257 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-15 16:22:19.920  1036  1422 D WifiStateMachine: Setting OUI to DA-A1-19
08-15 16:22:19.920  1036  1422 I WifiNative-HAL: startHal
08-15 16:22:19.920  1036  1422 D wifi    : setting scan oui 0xaf52e780
08-15 16:22:19.920  1036  1422 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-15 16:22:19.920  1942  7257 E CtrlSupplicant: Succeed to open control connection
,08-15 16:22:19.920  1942  7257 E CtrlSupplicant: Succeed to open monitor connection
08-15 16:22:19.920  1942  7257 D WfdsMonitor: Supplicant connection established
08-15 16:22:19.921  1036  1422 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
,08-15 16:22:19.921  1036  1422 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-15 16:22:19.921  7166  7166 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-15 16:22:19.921  1942  2262 D WfdsService: Connected to the supplicant for wfds
08-15 16:22:19.921  1036  1422 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-15 16:22:19.922  1036  1422 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-15 16:22:19.922  7166  7166 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
,08-15 16:22:19.922  1036  1422 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-15 16:22:19.922  1036  1422 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-15 16:22:19.923  7166  7166 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
,08-15 16:22:19.923  1036  1422 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-15 16:22:19.923  1036  1422 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-15 16:22:19.923  7166  7166 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-15 16:22:19.923  1036  1422 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-15 16:22:19.923  1036  1422 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-15 16:22:19.924  7166  7166 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
,08-15 16:22:19.924  1036  1422 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-15 16:22:19.924  1036  1422 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-15 16:22:19.924  7166  7166 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-15 16:22:19.924  1036  1422 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-15 16:22:19.924  1036  1422 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-15 16:22:19.924  7166  7166 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START,
08-15 16:22:19.925  1036  1422 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-15 16:22:19.926  1036  1422 E WifiNative: : [196,656,640 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-15 16:22:19.926  1036  1422 D WifiNative-wlan0: doBoolean: RECONNECT
,08-15 16:22:19.926  1036  1422 D WifiNative-wlan0: RECONNECT: returned true
08-15 16:22:19.926  1036  1422 D WifiNative-wlan0: doString: [STATUS]
08-15 16:22:19.927  1036  7233 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
,08-15 16:22:19.927  1036  7233 E WifiMonitor: WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-15 16:22:19.927  1036  1422 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4,
,08-15 16:22:19.927  1036  1422 D WifiNative-wlan0: doBoolean: SET ps 1,
,08-15 16:22:19.928  1036  1422 D WifiNative-wlan0: SET ps 1: returned true
08-15 16:22:19.928  1036  1389 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-15 16:22:19.930   312   894 D CommandListener: Setting iface cfg
08-15 16:22:19.930   312   894 D CommandListener: Trying to bring up p2p0
08-15 16:22:19.930  1036  1389 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-15 16:22:19.930  1036  1389 D LGWifiP2pService: P2pEnablingState
,08-15 16:22:19.930  1036  1389 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-15 16:22:19.930  1036  1389 D LGWifiP2pService: P2p socket connection successful
08-15 16:22:19.930  1036  1389 D LGWifiP2pService: P2pEnabledState
,08-15 16:22:19.932  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 3
08-15 16:22:19.932  1036  1036 D RttService: SCAN_AVAILABLE : 3
08-15 16:22:19.932  1036  1557 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-15 16:22:19.932  1036  1557 I WifiNative-HAL: startHal
08-15 16:22:19.932  1036  1557 D wifi    : getting scan capabilities on interface[1] = 0xaf52e780
08-15 16:22:19.932  1036  1557 D wifi    : failed to get capabilities : -3
08-15 16:22:19.932  1036  1557 E WifiScanningService: could not get scan capabilities
08-15 16:22:19.933  1036  1558 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,08-15 16:22:19.933  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-15 16:22:19.933  1942  1942 D WfdsService: WifiP2pState is changed : true
08-15 16:22:19.933  1942  2262 D WfdsService: Receive the WFDS_ENABLE Method
08-15 16:22:19.933  1942  2262 D WfdsService: Set the WFDS Monitor: true
08-15 16:22:19.933  1942  2262 D WfdsService: Connected to the supplicant for wfds
08-15 16:22:19.934  1942  2262 D WfdsJNI : doCommand: WFDS_SET TRUE
08-15 16:22:19.934  7166  7166 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-15 16:22:19.934  1942  2262 D WfdsService: selectPreferredScanChannel [36]
08-15 16:22:19.934  1942  2262 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-15 16:22:19.935  1036  1389 D LGWifiP2pService: sending p2p connection changed broadcast
08-15 16:22:19.935  1036  1389 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-15 16:22:19.937  1036  1389 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-15 16:22:19.937  1036  1389 D WifiNative-p2p0: doBoolean: SET device_name G3
08-15 16:22:19.937  1942  1942 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-15 16:22:19.937  1036  1389 D WifiNative-p2p0: SET device_name G3: returned true
,08-15 16:22:19.937  1036  1389 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-15 16:22:19.937  1036  1389 D LGWifiP2pService: before postfix = G3
08-15 16:22:19.937  1036  1389 D WifiServerServiceExt: postfix byte check : 2
08-15 16:22:19.937  1036  1389 D LGWifiP2pService: after postfix = G3
08-15 16:22:19.937  1036  1389 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-15 16:22:19.938  1036  1389 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
,08-15 16:22:19.938  1036  1389 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-15 16:22:19.938  1036  1389 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-15 16:22:19.938  1036  1389 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-15 16:22:19.938  1942  1942 D WfdsService: isConnected: false
08-15 16:22:19.939  1036  1389 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-15 16:22:19.939  1036  1389 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-15 16:22:19.939  1036  1389 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-15 16:22:19.939  1036  1389 D WifiNative-HAL: p2pGetDeviceAddress
08-15 16:22:19.939  1036  1389 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-15 16:22:19.941  1942  1942 I WfdStateTracker: handleP2pThisDeviceChanged
08-15 16:22:19.941  1942  1942 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-15 16:22:19.941  1942  1942 D WfdsService: Update P2p Interface State: 3
08-15 16:22:19.941  1036  1389 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-15 16:22:19.941  1036  1389 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-15 16:22:19.942  1036  1389 D WifiNative-p2p0: P2P_FLUSH: returned true
08-15 16:22:19.942  1036  1389 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
,08-15 16:22:19.942  1036  1389 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-15 16:22:19.942  1036  1389 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-15 16:22:19.943  1036  1422 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-15 16:22:19.944  1036  1422 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-15 16:22:19.944  1036  1422 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-15 16:22:19.945  1036  1422 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-15 16:22:19.945  1036  1422 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
08-15 16:22:19.945  1036  1422 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-15 16:22:19.946  1036  1422 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
,08-15 16:22:19.946  1036  1422 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-15 16:22:19.946  1036  1422 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-15 16:22:19.947  1036  1422 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=196678  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-15 16:22:19.948  1036  1389 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-15 16:22:19.948  1036  1389 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-15 16:22:19.950  1036  1422 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=196682  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-15 16:22:19.951  1036  1422 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=196683
08-15 16:22:19.952  1036  1422 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=196683
08-15 16:22:19.952  1036  1422 D WifiNative-wlan0: doString: [STATUS]
08-15 16:22:19.953  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-15 16:22:19.953  1606  1606 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-15 16:22:19.953  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 16:22:19.953  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 16:22:19.953  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-15 16:22:19.955  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-15 16:22:19.958  1036  1389 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-15 16:22:19.958  1036  1389 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-15 16:22:19.958  1036  1389 D LGWifiP2pService: InactiveState
08-15 16:22:19.958  1036  1389 D LGWifiP2pService: InactiveState{ when=-16ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-15 16:22:19.958  1036  1389 D LGWifiP2pService: P2pEnabledState{ when=-16ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-15 16:22:19.958  1036  1389 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-15 16:22:19.959  1036  7233 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-15 16:22:19.959  1036  7233 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-15 16:22:19.959  1036  1422 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
,08-15 16:22:19.960  7166  7166 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-15 16:22:19.960  7166  7166 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-15 16:22:19.961  7166  7166 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-15 16:22:19.961  7166  7166 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-15 16:22:19.961  7166  7166 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-15 16:22:19.962  1942  7257 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-15 16:22:19.962  1942  7257 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-15 16:22:19.962  1942  7257 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-15 16:22:19.962  1036  7233 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-15 16:22:19.962  1036  7233 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-15 16:22:19.962  1036  7233 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-15 16:22:19.962  1036  1422 I WifiServiceExtension: setVHTCapabilityType  : false
08-15 16:22:19.962  1036  7233 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-15 16:22:19.962  1036  7233 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-15 16:22:19.962  1036  7233 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-15 16:22:19.962  1036  7233 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-15 16:22:19.962  1036  7233 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-15 16:22:19.962  1036  7233 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-15 16:22:19.962  1036  7233 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-15 16:22:19.962  1036  7233 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-15 16:22:19.963  1036  7233 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-15 16:22:19.963  1036  1389 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-15 16:22:19.963  1036  1389 D LGWifiP2pService: InactiveState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-15 16:22:19.963  1036  1389 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-15 16:22:19.963  1036  1389 D LGWifiP2pService: DefaultState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-15 16:22:19.963  1036  1389 D LGWifiP2pService: InactiveState{ when=-5ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-15 16:22:19.963  1036  1389 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-15 16:22:19.964  1036  1389 D LGWifiP2pService: DefaultState{ when=-5ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-15 16:22:19.964  1036  1389 D LGWifiP2pService: InactiveState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-15 16:22:19.964  1036  1389 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-15 16:22:19.964  1036  1389 D LGWifiP2pService: DefaultState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-15 16:22:19.964  1036  1389 D LGWifiP2pService: InactiveState{ when=-6ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-15 16:22:19.964  1036  1389 D LGWifiP2pService: P2pEnabledState{ when=-6ms wha,t=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-15 16:22:19.964  1942  2262 W WfdsService: DefaultState - msg [9441285] is not handled
08-15 16:22:19.964  1036  1389 D LGWifiP2pService: DefaultState{ when=-6ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-15 16:22:19.964  1036  1036 E WifiServerServiceExt: No p2p device connected
08-15 16:22:19.968  1036  1422 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-15 16:22:19.968  1036  1422 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-15 16:22:19.970  7234  7234 I art     : Almond Protected OAT
08-15 16:22:19.971  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 16:22:19.971  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 16:22:19.972  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-15 16:22:19.976  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 16:22:19.976  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 16:22:19.976  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-15 16:22:19.977  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-15 16:22:19.977  1606  1606 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-15 16:22:19.980  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-15 16:22:19.980  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 16:22:19.980  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 16:22:19.980  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-15 16:22:19.982  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-15 16:22:19.982  1606  1606 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-15 16:22:19.983  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-15 16:22:19.985  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-15 16:22:19.985  1606  1606 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-15 16:22:19.986  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-15 16:22:19.987  1036  1422 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-15 16:22:19.987  1036  1477 D ConnectivityService: Got NetworkAgent Messenger
08-15 16:22:19.987  1036  1422 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-15 16:22:19.987  1036  1422 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-15 16:22:19.987  1036  1477 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-15 16:22:19.987  1036  1477 D ConnectivityService: NetworkAgent connected
08-15 16:22:19.987  1036  1422 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-15 16:22:19.987  1036  1422 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-15 16:22:19.992  1036  1422 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-15 16:22:19.992  1036  1422 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-15 16:22:19.992  1036  1422 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-15 16:22:19.994  1036  1422 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-15 16:22:19.994  1036  1422 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-15 16:22:19.997  1036  1422 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-15 16:22:19.998   312   894 D CommandListener: Setting iface cfg
08-15 16:22:20.000  1036  1422 E WifiStateMachine: Start Dhcp Watchdog 2
08-15 16:22:20.001  1036  1422 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 25 0 rt=196732  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-15 16:22:20.001  1036  1422 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 25 0 rt=196732  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-15 16:22:20.001  1036  1422 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 25 0 rt=196733  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-15 16:22:20.002  1036  1422 E WifiStateMachine:  ObtainingIpState what:132106 1 0
08-15 16:22:20.002  1036  1422 E WifiStateMachine:  L2ConnectedState what:132106 1 0
08-15 16:22:20.002  1036  1422 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-15 16:22:20.003  1036  1422 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-15 16:22:20.003  1036  1422 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-15 16:22:20.003  7166  7166 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-15 16:22:20.003  1036  1422 E WifiStateMachine:  ObtainingIpState what:132096 -100 0
08-15 16:22:20.004  1036  1422 E WifiStateMachine:  L2ConnectedState what:132096 -100 0
08-15 16:22:20.004  1036  1422 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-15 16:22:20.004  1036  1422 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-15 16:22:20.004  1036  1422 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-15 16:22:20.004  7166  7166 E wpa_supplicant: disconnect_rssi_lvl: -100
08-15 16:22:20.006  1036  1422 E WifiStateMachine:  ObtainingIpState CMD_SET_COUNTRY_CODE 2 0 cz
08-15 16:22:20.006  1036  1422 E WifiStateMachine:  L2ConnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-15 16:22:20.007  1036  1422 E WifiStateMachine:  ObtainingIpState CMD_SET_FREQUENCY_BAND 0 0
08-15 16:22:20.007  1036  1422 E WifiStateMachine:  L2ConnectedState CMD_SET_FREQUENCY_BAND 0 0
08-15 16:22:20.007  1036  1422 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-15 16:22:20.007  1036  1422 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-15 16:22:20.007  1036  1422 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-15 16:22:20.008  7166  7166 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-15 16:22:20.008  7166  7166 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-15 16:22:20.008  1036  7233 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-15 16:22:20.008  1036  7233 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-15 16:22:20.008  1036  7259 D DhcpStateMachine: StoppedState
08-15 16:22:20.008  1036  7233 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-15 16:22:20.008  1036  7233 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-15 16:22:20.008  1036  7259 D DhcpStateMachine: StoppedState{ when=-8ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-15 16:22:20.008  1036  7259 D DhcpStateMachine: WaitBeforeStartState
08-15 16:22:20.009  1036  1422 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-15 16:22:20.009  1036  1422 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-15 16:22:20.009  1036  1422 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-15 16:22:20.009  1036  1422 D WifiNative-wlan0: doBoolean: SCAN
08-15 16:22:20.009  7166  7166 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-15 16:22:20.009  1036  7233 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-15 16:22:20.009  1036  7233 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-15 16:22:20.010  1036  7233 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-15 16:22:20.010  1036  7233 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-15 16:22:20.010  1036  1422 D WifiNative-wlan0: SCAN: returned true
08-15 16:22:20.010  1036  1422 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=196742  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-15 16:22:20.011  1036  1422 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=196742  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-15 16:22:20.011  1036  1422 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=196742  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-15 16:22:20.011  1036  1422 E WifiStateMachine:  ObtainingIpState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-15 16:22:20.012  1036  1422 E WifiStateMachine:  L2ConnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-15 16:22:20.012  1036  1422 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-15 16:22:20.012  1036  1422 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-15 16:22:20.012  1036  1422 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-15 16:22:20.013  1036  1422 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-15 16:22:20.013  1036  1422 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=196745  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-15 16:22:20.014  1036  1422 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=196745  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-15 16:22:20.014  1036  1422 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=196745  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-15 16:22:20.015  1036  1422 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:150360] from screen [on:0 period:-1902842513] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-15 16:22:20.015  1036  1422 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:-1902842513] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-15 16:22:20.016  1036  1422 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-15 16:22:20.019  7234  7234 D WeatherApplication: removeAccount
08-15 16:22:20.019  7234  7234 D WeatherApplication: Account.length = 0
08-15 16:22:20.020  7234  7234 E WeatherApplication: OPERATOR:OPEN
08-15 16:22:20.024  7234  7234 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:22:20
08-15 16:22:20.026  7234  7234 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-15 16:22:20.026  7234  7234 D Weather.Utils: 2 : All the weather widget is gone.
08-15 16:22:20.027  7234  7234 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-15 16:22:20.029  7234  7234 D WeatherAncestor: connectivity changed - connection : true
08-15 16:22:20.030  7234  7234 D WeatherService: 2 : isServiceAlived():false forecastCache:null
08-15 16:22:20.036  7234  7234 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-15 16:22:20.036  7234  7234 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-15 16:22:20.036  7234  7234 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
,08-15 16:22:20.050  7234  7234 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-15 16:22:20.051  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-15 16:22:20.051  7234  7234 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:22:20
,08-15 16:22:20.051  1036  1036 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
,08-15 16:22:20.099  1036  1052 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7261 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-15 16:22:20.100  1036  1052 I ActivityManager: Killing 2150:com.lge.music/u0a34 (adj 15): empty #17
08-15 16:22:20.113  1036  1389 D LGWifiP2pService: InactiveState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-15 16:22:20.113  1036  1389 D LGWifiP2pService: P2pEnabledState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-15 16:22:20.113  1036  1389 D LGWifiP2pService: DefaultState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-15 16:22:20.145   319  3971 V AudioFlinger: 2150 died, releasing its sessions
08-15 16:22:20.145   319  3971 V AudioFlinger:  pid 1853 @ 0
08-15 16:22:20.145   319  3971 V AudioFlinger:  pid 3420 @ 1
08-15 16:22:20.145   319  3971 V AudioFlinger:  pid 3420 @ 2
,08-15 16:22:20.198  1036  2025 W libprocessgroup: failed to open /acct/uid_10034/pid_2150/cgroup.procs: No such file or directory
,08-15 16:22:20.210  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-15 16:22:20.214  1036  1477 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-15 16:22:20.215  1036  1422 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-15 16:22:20.216  1036  1422 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-15 16:22:20.218  1036  1422 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-15 16:22:20.220  1036  1422 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-15 16:22:20.221  1036  1422 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-15 16:22:20.222  1036  1422 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,08-15 16:22:20.223  1036  1477 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-15 16:22:20.225  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-15 16:22:20.225  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-15 16:22:20.228  1036  1422 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=190,0,0
08-15 16:22:20.229  1036  1422 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=190,0,0
08-15 16:22:20.229  1036  1422 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-15 16:22:20.229  7166  7166 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-15 16:22:20.230  1036  1422 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-15 16:22:20.230  1036  1422 D WifiNative-wlan0: doBoolean: SET ps 0
08-15 16:22:20.230  1036  1422 D WifiNative-wlan0: SET ps 0: returned true
08-15 16:22:20.230  1036  1422 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-15 16:22:20.231  7166  7166 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-15 16:22:20.231  1036  1422 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-15 16:22:20.231  1036  1389 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@195ce448 target=com.android.internal.util.StateMachine$SmHandler }
08-15 16:22:20.231  1036  1389 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@195ce448 target=com.android.internal.util.StateMachine$SmHandler }
08-15 16:22:20.231  1036  7259 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-15 16:22:20.231  1036  7259 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-15 16:22:20.232  1036  1422 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-15 16:22:20.232  1036  1422 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-15 16:22:20.232  1036  1422 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-15 16:22:20.233  1036  7233 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-15 16:22:20.233  1036  7233 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-15 16:22:20.233   312   894 D CommandListener: Setting iface cfg
08-15 16:22:20.234   312   894 D CommandListener: Trying to bring up wlan0
08-15 16:22:20.235  1036  7233 E WifiMonitor: WifiMonitor:p2p0 cnt=34 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-15 16:22:20.235  1036  7233 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-15 16:22:20.235  1942  7257 D WfdsMonitor: Event [CTRL-EVENT-SCAN-RESULTS ]
08-15 16:22:20.235  1036  1389 D LGWifiP2pService: InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
08-15 16:22:20.235  1036  1389 D LGWifiP2pService: P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
08-15 16:22:20.235  1942  7257 D WfdsMonitor: Event [WPS-AP-AVAILABLE ]
08-15 16:22:20.235  1036  7233 D WifiMonitor: Event [IFNAME=p2p0 WPS-AP-AVAILABLE ]
08-15 16:22:20.235  1036  1389 D LGWifiP2pService: DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
08-15 16:22:20.235  1036  7233 E WifiMonitor: WifiMonitor:p2p0 cnt=35 dispatchEvent: WPS-AP-AVAILABLE 
08-15 16:22:20.235  1036  7233 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-15 16:22:20.235  1036  1422 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-15 16:22:20.237  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-15 16:22:20.237  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-15 16:22:20.239  1036  1036 D WifiServerServiceEx,t: SUPPLICANT_STATE_CHANGED_ACTION
08-15 16:22:20.239  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
,08-15 16:22:20.240  1036  1422 E WifiStateMachine:  ObtainingIpState CMD_STOP_SUPPLICANT_FAILED 1 0
,08-15 16:22:20.241  1036  1422 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-15 16:22:20.241  1036  1422 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
08-15 16:22:20.242  1036  1422 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-15 16:22:20.242  1036  1422 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-15 16:22:20.243  1036  1422 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
08-15 16:22:20.243  1036  1422 E WifiStateMachine:  ObtainingIpState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-15 16:22:20.244  1036  1422 E WifiStateMachine:  L2ConnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
,08-15 16:22:20.244  1036  1422 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-15 16:22:20.245  1036  1422 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-15 16:22:20.245  1036  1422 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-15 16:22:20.245  1036  1422 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-15 16:22:20.251  1036  1422 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-15 16:22:20.252  1036  1422 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-15 16:22:20.253  1036  1422 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-15 16:22:20.253  1036  1422 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-15 16:22:20.254  1036  1422 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-15 16:22:20.254  1036  1422 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-15 16:22:20.254  1036  1477 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-15 16:22:20.255  1036  1422 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-15 16:22:20.255  1036  1422 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-15 16:22:20.255  1036  1389 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-15 16:22:20.255  1036  1389 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-15 16:22:20.255  1036  1422 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-15 16:22:20.256  7166  7166 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-15 16:22:20.256  1036  1422 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-15 16:22:20.256  1036  1422 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-15 16:22:20.256  7166  7166 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-15 16:22:20.257  1036  1422 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-15 16:22:20.257  1036  1422 D WifiNative-wlan0: doBoolean: SET ps 1
08-15 16:22:20.272  1036  1422 D WifiNative-wlan0: SET ps 1: returned true
08-15 16:22:20.273  1036  1477 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-15 16:22:20.273  1036  1422 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-15 16:22:20.274  1036  1422 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-15 16:22:20.274  1036  1422 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-15 16:22:20.274  1036  1477 D ConnectivityService: ignoring duplicate network state non-change
,08-15 16:22:20.279  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-15 16:22:20.279  1606  1606 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-15 16:22:20.281  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-15 16:22:20.285  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 16:22:20.286  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 16:22:20.286  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-15 16:22:20.287  1036  1477 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-15 16:22:20.288  1036  1477 D ConnectivityService: Adding iface wlan0 to network 101
,08-15 16:22:20.294  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 16:22:20.294  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 16:22:20.294  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-15 16:22:20.296  1036  1422 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-15 16:22:20.300  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,08-15 16:22:20.303  1942  1942 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-15 16:22:20.307  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-15 16:22:20.307  1606  1606 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-15 16:22:20.308  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 16:22:20.308  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 16:22:20.308  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,08-15 16:22:20.310  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-15 16:22:20.310  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-15 16:22:20.311  1036  1477 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-15 16:22:20.311  1036  1477 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-15 16:22:20.312  1036  1477 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-15 16:22:20.313  1036  1422 E WifiStateMachine:  ConnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-15 16:22:20.313   312   894 E Netd    : netlink response contains error (File exists)
08-15 16:22:20.313  1036  1477 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-15 16:22:20.314  1036  1477 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-15 16:22:20.314  1036  1477 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-15 16:22:20.314  1036  1477 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-15 16:22:20.315  1036  1422 E WifiStateMachine:  L2ConnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-15 16:22:20.317  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-15 16:22:20.317  1606  1606 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-15 16:22:20.317  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming,
08-15 16:22:20.322  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 16:22:20.322  1036  1477 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-15 16:22:20.322  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 16:22:20.322  1036  1477 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-15 16:22:20.322  1036  1477 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-15 16:22:20.322  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-15 16:22:20.322  1036  1477 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-15 16:22:20.322  1036  7258 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-15 16:22:20.322  1036  7258 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-15 16:22:20.322  1036  1477 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-15 16:22:20.322  1036  1477 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-15 16:22:20.323  1036  7258 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-15 16:22:20.323  1036  1477 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-15 16:22:20.323  1036  1477 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-15 16:22:20.323  1036  7258 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-15 16:22:20.323  1036  1477 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-15 16:22:20.323  1036  1477 D ConnectivityService: currentScore = 0, newScore = 20
08-15 16:22:20.323  1036  1477 D ConnectivityService:    accepting network in place of null
08-15 16:22:20.323  1036  1477 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-15 16:22:20.323  1036  1422 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-15 16:22:20.323  1036  1422 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-15 16:22:20.323  1853  1853 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-15 16:22:20.324  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-15 16:22:20.325  1036  1477 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,5242,88,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-15 16:22:20.325  1036  1477 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-15 16:22:20.325   312  7282 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-15 16:22:20.325  1036  1477 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-15 16:22:20.332  1036  1477 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-15 16:22:20.332  1036  1477 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-15 16:22:20.332  1036  1477 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-15 16:22:20.332  1036  1036 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
,08-15 16:22:20.333  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-15 16:22:20.333  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-15 16:22:20.333  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-15 16:22:20.333  1036  1477 D ConnectivityService: validation of new default Network = false
08-15 16:22:20.333  1036  1477 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-15 16:22:20.333  1036  1477 D DSQN    : enableDataServiceNotify 
08-15 16:22:20.333  1036  1477 D DSQN    : start dsqn bin
08-15 16:22:20.335   277   406 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-15 16:22:20.335   277   406 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
,08-15 16:22:20.335   277   406 W Vold    : Returning OperationFailed - no handler for errno 0
08-15 16:22:20.338  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-15 16:22:20.338  1606  1606 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-15 16:22:20.338  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-15 16:22:20.339  7261  7283 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,08-15 16:22:20.341  1036  1477 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-15 16:22:20.341  1036  1477 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-15 16:22:20.342  1036  1477 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-15 16:22:20.342   277   406 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-15 16:22:20.342  1036  1477 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-15 16:22:20.342   277   406 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-15 16:22:20.342   277   406 W Vold    : Returning OperationFailed - no handler for errno 0
08-15 16:22:20.337  7284  7284 W dsqn    : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-15 16:22:20.343  7261  7283 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-15 16:22:20.337  7284  7284 W dsqn    : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-15 16:22:20.347  1606  2076 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-15 16:22:20.356  7284  7284 E DSQN    : DSQN ssw
,08-15 16:22:20.359  1036  1388 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-15 16:22:20.360   277   406 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,08-15 16:22:20.360   277   406 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-15 16:22:20.360   277   406 W Vold    : Returning OperationFailed - no handler for errno 0
08-15 16:22:20.360  7261  7288 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-15 16:22:20.362   277   406 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-15 16:22:20.362   277   406 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-15 16:22:20.362   277   406 W Vold    : Returning OperationFailed - no handler for errno 0
08-15 16:22:20.362  7261  7288 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-15 16:22:20.367  1818  7287 I CheckinService: active receiver: enabled
,08-15 16:22:20.376  1818  7287 I CheckinService: Preparing to send checkin request
,08-15 16:22:20.376  1818  7287 I EventLogService: Accumulating logs since 1471270801356
08-15 16:22:20.377  1606  1606 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-15 16:22:20.378  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-15 16:22:20.378  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-15 16:22:20.382  1818  7287 W EventLogAggregator: Unknown tag: snet_gcore
08-15 16:22:20.382  1818  7287 W EventLogAggregator: Unknown tag: snet_launch_service
,08-15 16:22:20.419  1818  7287 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-15 16:22:20.433  1036  7259 D DhcpStateMachine: DHCPV4 request on wlan0
08-15 16:22:20.434  1036  7259 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-15 16:22:20.434  1036  7259 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
,08-15 16:22:20.427  7295  7295 W dhcpcd  : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-15 16:22:20.427  7295  7295 W dhcpcd  : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-15 16:22:20.445  7295  7295 I dhcpcd  : version 5.5.6 starting
08-15 16:22:20.447  7295  7295 E dhcpcd  : get_duid: m
08-15 16:22:20.447  7295  7295 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-15 16:22:20.447  7295  7295 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,08-15 16:22:20.494  7295  7295 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-15 16:22:20.495  7295  7295 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-15 16:22:20.495  7295  7295 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-15 16:22:20.495  7295  7295 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
08-15 16:22:20.495  7295  7295 D dhcpcd  : wlan0: sending REQUEST (xid 0xc90133c1), next in 3.23 seconds
,08-15 16:22:20.504   308   308 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x6 conn_h=0xb6403090
08-15 16:22:20.504   308   308 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
08-15 16:22:20.504   308   308 I rmt_storage: wakelock acquired: 1, error no: 42
08-15 16:22:20.504   308   914 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1236806912)
08-15 16:22:20.522  1036  1597 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7315 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-15 16:22:20.555   308   914 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 1572864
08-15 16:22:20.555   308   914 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
08-15 16:22:20.555   308   914 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1236806912) wakelock released: 1, error no: 0
08-15 16:22:20.555   308   914 I rmt_storage: 
08-15 16:22:20.557   308   308 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x0x6 conn_h=0x0xb6403090
08-15 16:22:20.558   901   912 E Diag_Lib: [IMS_FATAL]| 3347 | 912 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
08-15 16:22:20.557  7261  7261 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
08-15 16:22:20.558  7295  7295 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
08-15 16:22:20.563  7315  7315 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-15 16:22:20.563  7315  7315 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-15 16:22:20.571  7261  7261 I LibraryLoader: Loading: webviewchromium
08-15 16:22:20.575  7261  7261 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 7311-7316)
08-15 16:22:20.575  7261  7261 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-15 16:22:20.578  7315  7315 I MultiDex: VM with version 2.1.0 has multidex support
08-15 16:22:20.578  7315  7315 I MultiDex: install
08-15 16:22:20.578  7315  7315 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-15 16:22:20.581  7261  7261 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {210b87a}
08-15 16:22:20.582  7261  7261 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-15 16:22:20.582  7261  7261 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-15 16:22:20.584  7315  7315 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
08-15 16:22:20.588  7295  7295 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
08-15 16:22:20.588  7295  7295 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
,08-15 16:22:20.589  7295  7295 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-15 16:22:20.589  7295  7295 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-15 16:22:20.589  7295  7295 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-15 16:22:20.590  7295  7295 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-15 16:22:20.590  7295  7295 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-15 16:22:20.590  7295  7295 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-15 16:22:20.594  7261  7261 I BrowserStartupController: Initializing chromium process, renderers=0
08-15 16:22:20.596  7261  7261 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-15 16:22:20.618  7261  7261 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-15 16:22:20.620  7261  7261 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-15 16:22:20.621   319  1395 V AudioPolicyService: registerClient() client 0xb1427160, uid 10093
08-15 16:22:20.620  7261  7261 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-15 16:22:20.623  7261  7341 W AudioManagerAndroid: Requires BLUETOOTH permission
08-15 16:22:20.638  7261  7261 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-15 16:22:20.638  7261  7261 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-15 16:22:20.638  7261  7261 I Adreno-EGL: Build Date: 12/12/14 금
08-15 16:22:20.638  7261  7261 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-15 16:22:20.638  7261  7261 I Adreno-EGL: Remote Branch: 
08-15 16:22:20.638  7261  7261 I Adreno-EGL: Local Patches: 
08-15 16:22:20.638  7261  7261 I Adreno-EGL: Reconstruct Branch: 
,08-15 16:22:20.766  1036  2014 I art     : Explicit concurrent mark sweep GC freed 97389(4MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/64MB, paused 1.850ms total 141.978ms
,08-15 16:22:20.782  7261  7261 I NSApplication: Starting up...
,08-15 16:22:20.838  1036  7259 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-15 16:22:20.839  1036  1978 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7373 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-15 16:22:20.841  1036  1978 I ActivityManager: Killing 5831:com.android.vending/u0a44 (adj 15): empty #17
08-15 16:22:20.841  1036  7259 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-15 16:22:20.841  1036  7259 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-15 16:22:20.842  1036  7259 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
08-15 16:22:20.842  1036  7259 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-15 16:22:20.842  1036  7259 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-15 16:22:20.842  1036  7259 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
,08-15 16:22:20.842  1036  7259 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-15 16:22:20.845  1036  7259 D DhcpStateMachine: RunningState
08-15 16:22:20.921  7390  7390 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-15 16:22:20.931  1036  1052 W libprocessgroup: failed to open /acct/uid_10044/pid_5831/cgroup.procs: No such file or directory
,08-15 16:22:20.994  7390  7390 I dex2oat : dex2oat took 72.324ms (threads: 4)
,08-15 16:22:21.007  7373  7373 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-15 16:22:21.013  7315  7330 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-15 16:22:21.013  7315  7330 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-15 16:22:21.013  7315  7330 I Adreno-EGL: Build Date: 12/12/14 금
08-15 16:22:21.013  7315  7330 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-15 16:22:21.013  7315  7330 I Adreno-EGL: Remote Branch: 
08-15 16:22:21.013  7315  7330 I Adreno-EGL: Local Patches: 
08-15 16:22:21.013  7315  7330 I Adreno-EGL: Reconstruct Branch: 
,08-15 16:22:21.060  1036  2014 D WifiServiceImplEx: setWifiEnabled: false pid=6826, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-15 16:22:21.060  1036  2014 D WifiService: setWifiEnabled: false pid=6826, uid=10118
08-15 16:22:21.060  1036  2014 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-15 16:22:21.070  1036  1422 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-15 16:22:21.070  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-15 16:22:21.070  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-15 16:22:21.070  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-15 16:22:21.070  1036  1422 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-15 16:22:21.070  1036  1422 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-15 16:22:21.071  1036  1422 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-15 16:22:21.071  1036  1422 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-15 16:22:21.071  1036  1422 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-15 16:22:21.071  1036  1422 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-15 16:22:21.071  1036  1422 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-15 16:22:21.072  1036  1422 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-15 16:22:21.072  1036  1422 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-15 16:22:21.077  1036  1422 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-15 16:22:21.077  1036  1422 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-15 16:22:21.077  7166  7166 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-15 16:22:21.078  1036  1389 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-15 16:22:21.078  1036  1389 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-15 16:22:21.078  1036  1422 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-15 16:22:21.078  1036  1422 D WifiNative-wlan0: doBoolean: SET ps 1
08-15 16:22:21.079  1036  1422 D WifiNative-wlan0: SET ps 1: returned true
08-15 16:22:21.079   312   894 D CommandListener: Clearing all IP addresses on wlan0
,08-15 16:22:21.086  1036  7259 D DhcpStateMachine: RunningState{ when=-7ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,08-15 16:22:21.107  1036  1422 E WifiStateMachine:  WaitForP2pDisableState CMD_SET_COUNTRY_CODE 2 0 cz
08-15 16:22:21.107  1036  1422 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-15 16:22:21.107  1036  1422 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-15 16:22:21.107  1036  1422 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-15 16:22:21.108  1036  1477 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-15 16:22:21.108  1036  1477 D ConnectivityService: ignoring duplicate network state non-change
08-15 16:22:21.108  1036  1389 D LGWifiP2pService: InactiveState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-15 16:22:21.108  1036  1389 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-15 16:22:21.108  1036  1477 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
08-15 16:22:21.108  1036  1389 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@4694419
08-15 16:22:21.110  1036  1422 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-15 16:22:21.110  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-15 16:22:21.110  1036  1389 D LGWifiP2pService: P2pDisablingState
08-15 16:22:21.110  1036  1389 D LGWifiP2pService: P2pDisablingState{ when=-2ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-15 16:22:21.110  1036  1389 D LGWifiP2pService: p2p socket connection lost
08-15 16:22:21.110  1036  1389 D LGWifiP2pService: P2pDisabledState
08-15 16:22:21.111  1036  1422 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-15 16:22:21.111  1036  1389 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-15 16:22:21.111  1036  1389 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,08-15 16:22:21.112  1036  1422 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-15 16:22:21.112  7166  7166 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-15 16:22:21.113  1036  1422 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-15 16:22:21.113  1036  1422 D WifiNative-wlan0: doBoolean: SET ps 1
08-15 16:22:21.113  1036  1422 D WifiNative-wlan0: SET ps 1: returned true
08-15 16:22:21.119  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 16:22:21.119  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 16:22:21.119  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-15 16:22:21.120  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-15 16:22:21.120  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 16:22:21.120  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 16:22:21.120  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-15 16:22:21.120  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 1
08-15 16:22:21.120  1036  1036 D RttService: SCAN_AVAILABLE : 1
08-15 16:22:21.120  1036  1557 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-15 16:22:21.120  1036  1558 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-15 16:22:21.121  1942  1942 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-15 16:22:21.124  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-15 16:22:21.124  1606  1606 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-15 16:22:21.127  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-15 16:22:21.129  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-15 16:22:21.129  1606  1606 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-15 16:22:21.130  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-15 16:22:21.131  1942  1942 D WfdsService: WifiP2pState is changed : false
08-15 16:22:21.131  1942  2262 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-15 16:22:21.131  1942  2262 D WfdsService: Set the WFDS Monitor: false
08-15 16:22:21.132  1942  2262 D WfdsMonitor: WFDS Monitor is stopped
08-15 16:22:21.132  1942  2262 D WfdsService: STATE : WfdsDisabledState - enter
08-15 16:22:21.132  1942  7257 D CtrlSupplicant: Received on exit socket, terminate
08-15 16:22:21.132  1942  7257 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-15 16:22:21.132  1942  7257 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-15 16:22:21.132  1942  7257 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-15 16:22:21.133  1942  2262 W WfdsService: DefaultState - msg [9445378] is not handled
08-15 16:22:21.136  1942  2264 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
,08-15 16:22:21.139  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-15 16:22:21.164   312   894 D CommandListener: Clearing all IP addresses on wlan0
08-15 16:22:21.165  1036  1477 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-15 16:22:21.165  1036  1477 D DSQN    : disableDataServiceNotify
08-15 16:22:21.165  1036  1477 D DSQN    : stop dsqn bin
,08-15 16:22:21.166  1036  1422 D WifiNative-p2p0: doBoolean: TERMINATE
08-15 16:22:21.167  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-15 16:22:21.168  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-15 16:22:21.168  1606  1606 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-15 16:22:21.168  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 16:22:21.168  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 16:22:21.168  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-15 16:22:21.169  1036  1422 D WifiNative-p2p0: TERMINATE: returned true
08-15 16:22:21.169  1036  1422 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-15 16:22:21.169  1036  1422 E WifiStateMachine: useWiFiOffloading() : false
08-15 16:22:21.169  1036  1422 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-15 16:22:21.169  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-15 16:22:21.170  1036  1422 E WifiStateMachine:  SupplicantStoppingState CMD_SET_COUNTRY_CODE 2 0 cz
08-15 16:22:21.171  1036  1477 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-15 16:22:21.171  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-15 16:22:21.171  1036  1477 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-15 16:22:21.171  1036  1477 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-15 16:22:21.172  1036  1477 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-15 16:22:21.172  1036  1477 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-15 16:22:21.172  6826  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-15 16:22:21.172  6826  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-15 16:22:21.172  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 16:22:21.172  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-15 16:22:21.172  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-15 16:22:21.172  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-15 16:22:21.172  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-15 16:22:21.172  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-15 16:22:21.172  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-15 16:22:21.172  6826  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-15 16:22:21.172  6826  6826 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-15 16:22:21.173  1036  1477 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, is,ConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-15 16:22:21.173  1036  1477 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-15 16:22:21.173  7315  7330 D LgDataFeature: LgDataFeature() Constructor: none
08-15 16:22:21.173  1036  1477 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-15 16:22:21.173  7315  7330 D LgDataFeature: LgDataFeature() Constructor Done, null
08-15 16:22:21.173  6826  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-15 16:22:21.173  6826  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-15 16:22:21.173  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 16:22:21.173  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-15 16:22:21.173  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-15 16:22:21.173  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-15 16:22:21.173  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-15 16:22:21.173  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-15 16:22:21.173  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-15 16:22:21.173  6826  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-15 16:22:21.173  6826  6826 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-15 16:22:21.173  1036  1477 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-15 16:22:21.173  1036  1477 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-15 16:22:21.173  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-15 16:22:21.173  1036  1477 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-15 16:22:21.174  1036  1477 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-15 16:22:21.174  1036  1477 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-15 16:22:21.174  1036  1477 D NetworkManagementService: Removing idletimer
08-15 16:22:21.174  1036  1477 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 16:22:21.174  1036  1422 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-15 16:22:21.174  1036  1422 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-15 16:22:21.174  1853  1853 D Te,lephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-15 16:22:21.174  1606  2076 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-15 16:22:21.174  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-15 16:22:21.175  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-15 16:22:21.175  1036  1036 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-15 16:22:21.175  1036  1388 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-15 16:22:21.175  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-15 16:22:21.176  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-15 16:22:21.176  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-15 16:22:21.176  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-15 16:22:21.177  1036  1388 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-15 16:22:21.178  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-15 16:22:21.178  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-15 16:22:21.178  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-15 16:22:21.178  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-15 16:22:21.189  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-15 16:22:21.207  1606  1606 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-15 16:22:21.207  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-15 16:22:21.209  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-15 16:22:21.231  1606  1606 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-15 16:22:21.232  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-15 16:22:21.233  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-15 16:22:21.271  7166  7166 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-15 16:22:21.271  7166  7166 I wpa_supplicant: monitor socket send errors count : 1
08-15 16:22:21.271  7166  7166 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1942-4\x00 that cannot receive messages
,08-15 16:22:21.273  1036  7233 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
,08-15 16:22:21.273  1036  7233 D WifiMonitor: Dropping event because (p2p0) is stopped
08-15 16:22:21.292  1036  7259 D DhcpStateMachine: StoppedState
08-15 16:22:21.292  1036  7259 D DhcpStateMachine: StoppedState{ when=-179ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-15 16:22:21.294  1036  1422 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-15 16:22:21.294  1036  1422 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
,08-15 16:22:21.296  7166  7166 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-15 16:22:21.296  1036  7233 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-15 16:22:21.296  1036  7233 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-15 16:22:21.296  1036  7233 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-15 16:22:21.296  1036  7233 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-15 16:22:21.297  1036  1422 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=198028
08-15 16:22:21.297  1036  1422 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=198029
08-15 16:22:21.300  7166  7166 W wpa_supplicant: USIM:  scard_deinit function
08-15 16:22:21.301  1036  7233 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-15 16:22:21.301  1036  7233 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-15 16:22:21.301  1036  1118 D Tethering: InitialState.processMessage what=4
08-15 16:22:21.301  1036  1422 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=198033  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-15 16:22:21.302  1036  1422 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=198033  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-15 16:22:21.302  1036  1422 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-15 16:22:21.302  1036  1422 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-15 16:22:21.303  1036  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-15 16:22:21.342  1036  1477 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-15 16:22:21.347  6515  6515 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-15 16:22:21.352  6515  6948 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-15 16:22:21.372  2131  2131 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-15 16:22:21.389  7117  7117 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-15 16:22:21.390  7117  7117 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-15 16:22:21.390  7117  7117 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-15 16:22:21.390  7117  7117 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-15 16:22:21.394  7117  7117 I AppUp4:CustModeStarterReceiver: onReceive
08-15 16:22:21.399  7117  7117 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@227395c3
08-15 16:22:21.399  7117  7117 D AppUp4:CustFacade: isCustomizationCompleted : false
08-15 16:22:21.399  7117  7117 D AppUp4:CustFacade: isPhone : true
08-15 16:22:21.399  7117  7117 D AppUp4:CustModeStarterReceiver: begin check event
08-15 16:22:21.400  7117  7117 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-15 16:22:21.403  4300  4300 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-15 16:22:21.403  4300  4300 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-15 16:22:21.406  4300  4300 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-15 16:22:21.409  4300  4300 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-15 16:22:21.409  7166  7166 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-15 16:22:21.409  1036  7233 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-15 16:22:21.409  1036  7233 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-TERMINATING 
08-15 16:22:21.409  1036  7233 D WifiMonitor: Disconnecting from the supplicant, no more events
08-15 16:22:21.410  1036  1422 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 38 0
08-15 16:22:21.419  4300  7422 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-15 16:22:21.420  7148  7148 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-15 16:22:21.423  4300  7423 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-15 16:22:21.423  4300  7423 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-15 16:22:21.433  7148  7424 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-15 16:22:21.437  3420  3420 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-15 16:22:21.438  3420  3420 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-15 16:22:21.438  3420  3420 I LgeMiscReceiver: networkInfo.isConnected() = false
08-15 16:22:21.442  7017  7427 W FormManager: Network not available. Please check & try again.
08-15 16:22:21.444  7179  7179 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-15 16:22:21.444  7179  7179 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-15 16:22:21.456  7234  7234 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:22:21
,08-15 16:22:21.458  7017  7428 V FormManager: Network unavailable.
,08-15 16:22:21.458  7234  7234 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-15 16:22:21.458  7234  7234 D Weather.Utils: 2 : All the weather widget is gone.
08-15 16:22:21.460  7017  7428 V FormManager: Network unavailable.
08-15 16:22:21.463  7234  7234 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-15 16:22:21.463  7234  7234 D WeatherAncestor: connectivity changed - connection : true
08-15 16:22:21.463  7234  7234 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@8c1d179
08-15 16:22:21.465  7234  7234 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-15 16:22:21.465  7234  7234 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-15 16:22:21.465  7234  7234 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-15 16:22:21.465  7234  7234 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-15 16:22:21.465  7234  7234 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:22:21
,08-15 16:22:21.488  6929  6929 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-15 16:22:21.488  6929  6929 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-15 16:22:21.488  6929  6929 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-15 16:22:21.488  6929  6929 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-15 16:22:21.488  6929  6929 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-15 16:22:21.489  6929  6929 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-15 16:22:21.489  6929  6929 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-15 16:22:21.489  6929  6929 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-15 16:22:21.489  6929  6929 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-15 16:22:21.489  6929  6929 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-15 16:22:21.489  6929  6929 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-15 16:22:21.497  6949  6949 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-15 16:22:21.500  7315  7330 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-15 16:22:21.500  7315  7330 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-15 16:22:21.500  7315  7330 I Adreno-EGL: Build Date: 12/12/14 금
08-15 16:22:21.500  7315  7330 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-15 16:22:21.500  7315  7330 I Adreno-EGL: Remote Branch: 
08-15 16:22:21.500  7315  7330 I Adreno-EGL: Local Patches: 
08-15 16:22:21.500  7315  7330 I Adreno-EGL: Reconstruct Branch: 
08-15 16:22:21.502  6929  6929 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-15 16:22:21.510  7017  7430 W FormManager: Network not available. Please check & try again.
08-15 16:22:21.512  1036  1422 D WifiOffDelayIfNotUsed: stopMonitoring
08-15 16:22:21.512  1036  1422 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-15 16:22:21.512  1036  1422 E WifiStateMachine: useWiFiOffloading() : false
08-15 16:22:21.512  1036  1422 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-15 16:22:21.513  1942  1942 D WfdsService: Supplicant Connection state is changed : false
08-15 16:22:21.513  1942  2262 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-15 16:22:21.513  1942  2262 D WfdsService: Set the WFDS Monitor: false
08-15 16:22:21.513  1942  2262 D WfdsMonitor: WFDS Monitor is stopped
08-15 16:22:21.513  6929  6929 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-15 16:22:21.517  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-15 16:22:21.517  6826  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-15 16:22:21.517  6826  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-15 16:22:21.517  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 16:22:21.517  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-15 16:22:21.517  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-15 16:22:21.517  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-15 16:22:21.517  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-15 16:22:21.517  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-15 16:22:21.517  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-15 16:22:21.518  2478  2478 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 16:22:21.518  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-15 16:22:21.519  6826  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-15 16:22:21.520  6826  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-15 16:22:21.520  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 16:22:21.520  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-15 16:22:21.520  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-15 16:22:21.520  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-15 16:22:21.520  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-15 16:22:21.520  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-15 16:22:21.520  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-15 16:22:21.523  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-15 16:22:21.524  1036  1442 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-15 16:22:21.524  1036  1442 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-15 16:22:21.525  7017  7431 V FormManager: Network unavailable.
,08-15 16:22:21.533  7017  7431 V FormManager: Network unavailable.
08-15 16:22:21.543  6949  6949 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-15 16:22:21.547  6929  6929 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-15 16:22:21.549  7315  7330 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-15 16:22:21.549  7315  7330 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-15 16:22:21.549  7315  7330 I Adreno-EGL: Build Date: 12/12/14 금
08-15 16:22:21.549  7315  7330 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-15 16:22:21.549  7315  7330 I Adreno-EGL: Remote Branch: 
08-15 16:22:21.549  7315  7330 I Adreno-EGL: Local Patches: 
08-15 16:22:21.549  7315  7330 I Adreno-EGL: Reconstruct Branch: 
,08-15 16:22:21.564  7017  7433 W FormManager: Network not available. Please check & try again.
08-15 16:22:21.565  6929  6929 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-15 16:22:21.571  7017  7434 V FormManager: Network unavailable.
,08-15 16:22:21.577  7017  7434 V FormManager: Network unavailable.
08-15 16:22:21.579  4300  4300 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-15 16:22:21.580  4300  4300 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-15 16:22:21.582  4300  4300 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-15 16:22:21.585  4300  4300 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-15 16:22:21.592  4300  7435 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-15 16:22:21.597  4300  7436 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-15 16:22:21.597  4300  7436 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-15 16:22:21.621  1036  1550 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7437 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-15 16:22:21.651   312  7455 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-15 16:22:21.652  1036  1116 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-15 16:22:21.653  1818  7287 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
08-15 16:22:21.666  1818  7287 I CheckinService: active receiver: disabled
,08-15 16:22:21.716  1036  1422 E WifiStateMachine:  InitialState CMD_SET_COUNTRY_CODE 2 0 cz
,08-15 16:22:21.717  1036  1422 E WifiStateMachine:  DefaultState CMD_SET_COUNTRY_CODE 2 0 cz
,08-15 16:22:21.720  7437  7437 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-15 16:22:21.720  7437  7437 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
08-15 16:22:21.729  7437  7437 V [BNRBootReceiver]: Boot Receiver Return
08-15 16:22:21.729  7437  7437 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-15 16:22:21.736  6515  6515 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-15 16:22:21.750  6929  6929 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-15 16:22:21.757  6929  6929 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-15 16:22:21.775  6977  6977 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-15 16:22:21.776  6977  6977 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-15 16:22:21.776  6977  6977 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-15 16:22:21.789  6515  6515 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-15 16:22:21.803  6929  6929 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-15 16:22:21.816  6929  6929 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-15 16:22:21.827  6977  6977 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-15 16:22:21.827  6977  6977 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-15 16:22:21.828  6977  6977 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-15 16:22:21.832  1036  1378 D PowerManagerServiceEx: acquireWakeLockInternal: lock=262048216, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
08-15 16:22:21.836  6515  6515 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-15 16:22:21.849  6929  6929 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-15 16:22:21.861  6929  6929 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-15 16:22:21.875  6977  6977 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-15 16:22:21.876  6977  6977 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-15 16:22:21.877  6977  6977 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-15 16:22:21.885  6515  6515 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-15 16:22:21.889  2577  2577 D [Concierge]Service: onStartCommand(). Type : 9
08-15 16:22:21.897  6929  6929 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-15 16:22:21.916  6929  6929 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-15 16:22:21.923  6977  6977 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-15 16:22:21.924  6977  6977 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-15 16:22:21.925  6977  6977 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-15 16:22:21.929  6929  6929 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-15 16:22:21.933  6929  6929 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-15 16:22:21.941  6515  6515 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-15 16:22:21.954  6929  6929 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-15 16:22:21.959  6929  6929 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-15 16:22:21.967  6977  6977 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-15 16:22:21.967  6977  6977 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-15 16:22:21.975  6977  6977 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-15 16:22:21.980  6515  6515 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-15 16:22:21.999  6929  6929 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-15 16:22:22.010  6929  6929 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-15 16:22:22.024  6977  6977 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-15 16:22:22.025  6977  6977 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-15 16:22:22.028  6977  6977 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-15 16:22:22.039  6515  6515 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-15 16:22:22.050  6949  6949 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-15 16:22:22.069  1036  1470 D WifiService: New client listening to asynchronous messages
,08-15 16:22:22.070  6949  6949 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-15 16:22:22.080  6929  6929 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-15 16:22:22.092  6929  6929 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-15 16:22:22.111  6977  6977 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-15 16:22:22.112  6977  6977 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-15 16:22:22.114  6977  6977 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,08-15 16:22:22.117  6977  6977 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-15 16:22:22.118  6977  6977 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-15 16:22:22.133  6515  6515 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-15 16:22:22.142  6949  6949 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-15 16:22:22.146  6949  6949 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-15 16:22:22.154  6929  6929 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-15 16:22:22.164  6929  6929 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-15 16:22:22.179  6977  6977 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-15 16:22:22.180  6977  6977 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-15 16:22:22.180  6977  6977 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-15 16:22:22.181  6977  6977 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,08-15 16:22:22.182  6977  6977 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-15 16:22:22.184  1036  1597 I ActivityManager: Killing 6908:com.lge.lifetracker/u0a37 (adj 15): empty #17
08-15 16:22:22.192  6721  7094 D UEI.SmartControl: Internal timer expired: 4
08-15 16:22:22.192  6721  7094 D UEI.SmartControl: unbind internal service
08-15 16:22:22.245  1036  1915 W libprocessgroup: failed to open /acct/uid_10037/pid_6908/cgroup.procs: No such file or directory
,08-15 16:22:22.250  2131  2131 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,08-15 16:22:22.271  2131  2131 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
08-15 16:22:22.272  2131  2131 D c       : Getting all permits...
08-15 16:22:22.272  2131  2131 D a       : Opening database...
,08-15 16:22:22.283  2131  2131 D a       : Opening database auth.proximity.permit_store...
08-15 16:22:22.286  2131  2131 D a       : Closing database...
,08-15 16:22:22.306  6515  6515 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-15 16:22:22.311  6721  7091 D serial_port: close(fd = 24)
,08-15 16:22:22.313  6949  6949 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-15 16:22:22.313  6949  6949 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-15 16:22:22.313  6949  6949 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-15 16:22:22.315  6721  7091 I UEI.SmartControl: Serial port is closed.
08-15 16:22:22.319  6929  6929 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-15 16:22:22.328  6929  6929 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-15 16:22:22.336  6977  6977 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-15 16:22:22.336  6977  6977 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-15 16:22:22.340  6977  6977 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-15 16:22:22.346  6515  6515 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-15 16:22:22.350  6949  6949 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-15 16:22:22.350  6949  6949 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-15 16:22:22.350  6949  6949 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-15 16:22:22.356  6929  6929 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-15 16:22:22.367  6929  6929 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-15 16:22:22.380  6977  6977 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-15 16:22:22.380  6977  6977 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-15 16:22:22.386  6977  6977 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-15 16:22:22.392  6515  6515 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-15 16:22:22.397  6949  6949 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-15 16:22:22.397  6949  6949 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-15 16:22:22.398  6949  6949 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-15 16:22:22.407  6929  6929 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-15 16:22:22.418  6929  6929 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-15 16:22:22.428  6977  6977 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-15 16:22:22.429  6977  6977 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-15 16:22:22.432  6977  6977 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-15 16:22:22.451  6949  6949 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-15 16:22:22.461  6929  6929 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-15 16:22:22.471  7017  7464 W FormManager: Network not available. Please check & try again.
08-15 16:22:22.473  6929  6929 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-15 16:22:22.484  7017  7465 V FormManager: Network unavailable.
,08-15 16:22:22.487  7017  7465 V FormManager: Network unavailable.
08-15 16:22:22.494  4300  4300 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-15 16:22:22.495  4300  4300 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-15 16:22:22.499  4300  4300 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-15 16:22:22.501  4300  4300 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-15 16:22:22.509  6949  6949 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-15 16:22:22.509  6949  6949 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-15 16:22:22.509  6949  6949 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-15 16:22:22.513  6929  6929 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-15 16:22:22.516  4300  7466 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-15 16:22:22.521  6929  6929 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-15 16:22:22.527  4300  7470 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-15 16:22:22.527  4300  7470 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-15 16:22:22.529  7017  7468 W FormManager: Network not available. Please check & try again.
08-15 16:22:22.539  7017  7469 V FormManager: Network unavailable.
,08-15 16:22:22.542  7017  7469 V FormManager: Network unavailable.
08-15 16:22:22.548  2131  2131 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
08-15 16:22:22.563  6977  6977 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
08-15 16:22:22.564  6977  6977 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:7177
08-15 16:22:22.564  1036  1036 D PowerManagerServiceEx: releaseWakeLockInternal: lock=262048216 [*alarm*], flags=0x0
,08-15 16:22:23.216  1036  1422 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1902839312] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-15 16:22:23.228  1036  1422 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1902839300] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-15 16:22:23.334  1036  1477 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-15 16:22:23.350  1036  1118 D Tethering: MasterInitialState.processMessage what=3
,08-15 16:22:23.353  1036  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-15 16:22:23.365  6826  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-15 16:22:23.371  6826  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 16:22:23.379  6515  6515 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-15 16:22:23.384  6515  6948 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-15 16:22:23.403  5786  5786 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-15 16:22:23.423  2131  2131 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-15 16:22:23.448  1036  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-15 16:22:23.462  7117  7117 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-15 16:22:23.462  7117  7117 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-15 16:22:23.462  7117  7117 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-15 16:22:23.462  7117  7117 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-15 16:22:23.468  7117  7117 I AppUp4:CustModeStarterReceiver: onReceive
08-15 16:22:23.471  7117  7117 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@227395c3
08-15 16:22:23.471  7117  7117 D AppUp4:CustFacade: isCustomizationCompleted : false
08-15 16:22:23.471  7117  7117 D AppUp4:CustFacade: isPhone : true
08-15 16:22:23.472  7117  7117 D AppUp4:CustModeStarterReceiver: begin check event
08-15 16:22:23.473  7117  7117 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-15 16:22:23.477  4300  4300 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-15 16:22:23.477  4300  4300 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-15 16:22:23.482  4300  4300 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-15 16:22:23.484  4300  4300 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-15 16:22:23.491  7148  7148 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-15 16:22:23.511  3420  3420 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-15 16:22:23.511  3420  3420 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-15 16:22:23.512  3420  3420 I LgeMiscReceiver: networkInfo.isConnected() = true
08-15 16:22:23.512  3420  3420 D PhoneState: setPdpRejectCasuse : false
,08-15 16:22:23.519  7179  7179 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-15 16:22:23.519  7179  7179 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-15 16:22:23.543  4300  7501 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-15 16:22:23.548  4300  7504 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-15 16:22:23.549  4300  7504 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-15 16:22:23.554  7148  7503 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 16:22:23.556  7234  7234 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:22:23
08-15 16:22:23.558  7017  7492 W FormManager: Network not available. Please check & try again.
08-15 16:22:23.559  7234  7234 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-15 16:22:23.559  7234  7234 D Weather.Utils: 2 : All the weather widget is gone.
08-15 16:22:23.560  7234  7234 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-15 16:22:23.560  7234  7234 D WeatherAncestor: connectivity changed - connection : true
08-15 16:22:23.560  7234  7234 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@8c1d179
,08-15 16:22:23.561  7234  7234 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-15 16:22:23.561  7234  7234 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-15 16:22:23.561  7234  7234 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-15 16:22:23.561  7234  7234 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-15 16:22:23.561  7234  7234 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:22:23
08-15 16:22:23.563  7017  7493 V FormManager: Network unavailable.
08-15 16:22:23.574  7017  7493 V FormManager: Network unavailable.
,08-15 16:22:24.072  1036  2025 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-15 16:22:24.072  1036  2025 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-15 16:22:24.106  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-15 16:22:24.106  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-15 16:22:24.106  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-15 16:22:24.107  1036  1118 D BluetoothManagerService: Message: 1
08-15 16:22:24.107  1036  1118 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-15 16:22:24.134  1036  1118 D BluetoothManagerService: Message: 20
08-15 16:22:24.134  1036  1118 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3592ac6:true
,08-15 16:22:24.140  7053  7053 D BluetoothAdapterState: make
08-15 16:22:24.144  7053  7053 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-15 16:22:24.145  7053  7053 I bluedroid-qcom: init
08-15 16:22:24.146  7053  7519 I BluetoothAdapterState: Entering OffState
08-15 16:22:24.146  7053  7053 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-15 16:22:24.147  7053  7053 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-15 16:22:24.147  7053  7053 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-15 16:22:24.147  7053  7053 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-15 16:22:24.147  7053  7053 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-15 16:22:24.149  7053  7053 I bluedroid-qcom: get_profile_interface socket
08-15 16:22:24.149  7053  7053 I bluedroid-qcom: get_profile_interface map_client
,08-15 16:22:24.154  7053  7523 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-15 16:22:24.147  7522  7522 W bdaddr_loader: type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-15 16:22:24.157  7522  7522 W bdaddr_loader: type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-15 16:22:24.163  7053  7523 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-15 16:22:24.173  7522  7522 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-15 16:22:24.173  7522  7522 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-15 16:22:24.173  7522  7522 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-15 16:22:24.175  1036  1477 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-15 16:22:24.177  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-15 16:22:24.179  1036  1118 D BluetoothManagerService: Message: 40
08-15 16:22:24.179  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-15 16:22:24.180  7053  7069 I bluedroid-qcom: config_hci_snoop_log
08-15 16:22:24.181  1036  1118 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-15 16:22:24.181  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-15 16:22:24.182  7522  7522 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-15 16:22:24.186  1036  1477 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-15 16:22:24.186  1036  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-15 16:22:24.189  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
,08-15 16:22:24.192  7522  7522 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-15 16:22:24.192  7522  7522 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-15 16:22:24.195  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
08-15 16:22:24.201  6826  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-15 16:22:24.203  6826  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 16:22:24.213  7053  7519 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,08-15 16:22:24.216  1036  1118 D Tethering: MasterInitialState.processMessage what=3
08-15 16:22:24.220  1036  1118 D Tethering: MasterInitialState.processMessage what=3
08-15 16:22:24.220  7053  7523 D BluetoothAdapterProperties: Name is: G3
08-15 16:22:24.220  7053  7519 D BluetoothAdapterProperties: Setting state to 11
08-15 16:22:24.221  7053  7519 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-15 16:22:24.229  6515  6515 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-15 16:22:24.233  6515  6948 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-15 16:22:24.242  6826  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 16:22:24.245  6826  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 16:22:24.238  1036  1118 D BluetoothManagerService: Message: 60
,08-15 16:22:24.253  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-15 16:22:24.254  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-15 16:22:24.255  1036  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-15 16:22:24.257  7053  7519 I LGBluetoothServiceJni: classInitNative: succeeds
08-15 16:22:24.263  7053  7519 D BluetoothBondStateMachine: make
08-15 16:22:24.265  1942  1942 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-15 16:22:24.265  5786  5786 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-15 16:22:24.268  6929  6929 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-15 16:22:24.268  6826  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-15 16:22:24.268  1606  1606 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-15 16:22:24.272  6826  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 16:22:24.280  7053  7537 I BluetoothBondStateMachine: StableState(): Entering Off State
08-15 16:22:24.280  7053  7519 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8c1d179
08-15 16:22:24.280  7053  7519 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-15 16:22:24.280  7053  7519 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8c1d179
08-15 16:22:24.280  7053  7519 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-15 16:22:24.281  7053  7519 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-15 16:22:24.285  7053  7519 E BluetoothAdapterService: File transfer profiles supported!!
08-15 16:22:24.285  7053  7053 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-15 16:22:24.286  7053  7053 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-15 16:22:24.286  7053  7053 V BluetoothPbapReceiver: ***********state = 11
08-15 16:22:24.293  5786  5786 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-15 16:22:24.299  2131  2131 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-15 16:22:24.343  1036  1978 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7540 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-15 16:22:24.352  7053  7519 E BluetoothAdapterService: File transfer profiles supported!!
08-15 16:22:24.353  1036  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-15 16:22:24.353  1036  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-15 16:22:24.357  7053  7053 D HeadsetService: Received start request. Starting profile...
08-15 16:22:24.357  7053  7053 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
,08-15 16:22:24.358  7053  7053 D LGBluetoothHfpAdapter: Version 1.6
08-15 16:22:24.361  7053  7053 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-15 16:22:24.362  7053  7053 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-15 16:22:24.363  7053  7519 E BluetoothAdapterService: File transfer profiles supported!!
08-15 16:22:24.363  7053  7053 D HeadsetStateMachine: make
08-15 16:22:24.367  2131  2131 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-15 16:22:24.370  7053  7519 E BluetoothAdapterService: File transfer profiles supported!!
,08-15 16:22:24.380  7053  7519 E BluetoothAdapterService: File transfer profiles supported!!
08-15 16:22:24.383  7117  7117 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-15 16:22:24.383  7117  7117 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-15 16:22:24.383  7117  7117 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-15 16:22:24.383  7117  7117 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-15 16:22:24.387  7053  7519 E BluetoothAdapterService: File transfer profiles supported!!
08-15 16:22:24.388  7117  7117 I AppUp4:CustModeStarterReceiver: onReceive
08-15 16:22:24.392  7053  7519 E BluetoothAdapterService: File transfer profiles supported!!
08-15 16:22:24.393  7117  7117 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@227395c3
08-15 16:22:24.393  7117  7117 D AppUp4:CustFacade: isCustomizationCompleted : false
08-15 16:22:24.393  7117  7117 D AppUp4:CustFacade: isPhone : true
08-15 16:22:24.394  7117  7117 D AppUp4:CustModeStarterReceiver: begin check event
08-15 16:22:24.394  7117  7117 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
,08-15 16:22:24.399  4300  4300 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-15 16:22:24.399  4300  4300 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-15 16:22:24.401  4300  4300 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-15 16:22:24.402  7053  7053 D LgDataFeature: LgDataFeature() Constructor: none
08-15 16:22:24.402  7053  7053 D LgDataFeature: LgDataFeature() Constructor Done, null
08-15 16:22:24.405  4300  4300 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-15 16:22:24.408  7053  7519 V LGMDMManager: Create singleton instance
,08-15 16:22:24.410  7053  7053 D HeadsetStateMachine: max_hf_connections = 1
08-15 16:22:24.410  7053  7053 I bluedroid-qcom: get_profile_interface handsfree
08-15 16:22:24.412  7053  7053 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-15 16:22:24.412   319   319 V AudioPolicyService: registerClient() client 0xb04102c0, uid 1002
08-15 16:22:24.413   319  3971 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-15 16:22:24.413   319  3971 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-15 16:22:24.413   319  3971 V AudioPolicyManagerEx: getOutput() returns output 2
08-15 16:22:24.413  7053  7519 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-15 16:22:24.413  7053  7053 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-15 16:22:24.413   319  1395 V AudioFlinger: registerClient() client 0xb1433100, pid 7053
08-15 16:22:24.414   319  1390 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-15 16:22:24.414   319  1390 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-15 16:22:24.414  7053  7053 V ToneGenerator: Create Track: 0xb4928080
08-15 16:22:24.414  7053  7053 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-15 16:22:24.414  7053  7053 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-15 16:22:24.414  1853  2462 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-15 16:22:24.414  1853  2462 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-15 16:22:24.414  3420  3435 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-15 16:22:24.414  3420  3435 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-15 16:22:24.414   319  1395 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-15 16:22:24.414   319  1395 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-15 16:22:24.414   319  1395 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-15 16:22:24.414   319  1395 V AudioPolicyManagerEx: getOutput() returns output 2
08-15 16:22:24.414  1606  2083 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-15 16:22:24.414  1606  2083 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-15 16:22:24.414   319  1391 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-15 16:22:24.414   319  1391 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-15 16:22:24.414  1036  2046 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-15 16:22:24.414  1036  2046 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-15 16:22:24.414  7053  7053 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-15 16:22:24.414  7053  7069 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-15 16:22:24.414  7053  7069 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-15 16:22:24.415   319  1396 I AudioFlinger: isAudioPlaybackHookOn() false
08-15 16:22:24.415   319   319 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-15 16:22:24.415   319   319 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-15 16:22:24.415   319   319 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-15 16:22:24.415   319   319 V AudioPolicyManagerEx: getOutput() returns output 2
08-15 16:22:24.415  7053  7053 V AudioSystem: getLatency() output 2, latency 50
08-15 16:22:24.415  7053  7053 V AudioSystem: getFrameCount() output 2, frameCount 960
08-15 16:22:24.415  7053  7053 V AudioTrack: createTrack_l() output 2 afLatency 50
08-15 16:22:24.416  7148  7148 D eas_req : ---,addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-15 16:22:24.417  4300  7559 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-15 16:22:24.418  4300  7562 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-15 16:22:24.418  4300  7562 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-15 16:22:24.418  3420  3436 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-15 16:22:24.418  7053  7069 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-15 16:22:24.418  3420  3436 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-15 16:22:24.418  7053  7069 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-15 16:22:24.418  1036  1945 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-15 16:22:24.418  1036  1945 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-15 16:22:24.418   319  1395 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-15 16:22:24.418   319  1395 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-15 16:22:24.418  1606  1628 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-15 16:22:24.418   319  1395 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-15 16:22:24.418  1606  1628 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-15 16:22:24.418   319  1395 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-15 16:22:24.418   319  1395 V AudioFlinger: createTrack() lSessionId: 20
08-15 16:22:24.419  1853  1868 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-15 16:22:24.419  1853  1868 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-15 16:22:24.419  7053  7053 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-15 16:22:24.420   319  1395 V AudioFlinger: acquiring 20 from 7053, for 7053
08-15 16:22:24.420   319  1395 V AudioFlinger:  added new entry for 20
08-15 16:22:24.420  7053  7053 V ToneGenerator: ToneGenerator INIT OK, time: 201162
08-15 16:22:24.420  7053  7053 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8c1d179
08-15 16:22:24.421  7053  7550 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-15 16:22:24.421  7053  7550 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-15 16:22:24.421  7053  7550 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-15 16:22:24.421  7053  7550 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-15 16:22:24.422  7053  7053 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8c1d179
08-15 16:22:24.423  7053  7053 D A2dpService: Received start request. Starting profile...
08-15 16:22:24.424   319  3971 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7053
08-15 16:22:24.424  7053  7053 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-15 16:22:24.424   319  3971 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-15 16:22:24.424   319  3971 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-15 16:22:24.424   319  3971 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-15 16:22:24.424   319  3971 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-15 16:22:24.424   319  3971 V voice   : voice_set_parameters: exit with code(0)
08-15 16:22:24.424   319  3971 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-15 16:22:24.424   319  3971 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-15 16:22:24.424   319  3971 V msm8974_platform: platform_set_parameters: exit with code(0)
08-15 16:22:24.424   319  3971 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-15 16:22:24.424   319  3971 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-15 16:22:24.424   319  3971 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-15 16:22:24.424  7053  7550 V ToneGenerator: ToneGenerator destructor
08-15 16:22:24.424  7053  7550 V ToneGenerator: stopTone
08-15 16:22:24.424  7053  7550 V ToneGenerator: Delete Track: 0xb4928080
08-15 16:22:24.425  7053  7053 V Avrcp   : make
08-15 16:22:24.425  7053  7053 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-15 16:22:24.425  7053  7053 I bluedroid-qcom: get_profile_interface avrcp
08-15 16:22:24.426  7053  7550 V AudioTrack: ~AudioTrack, releasing session id from 7053 on behalf of 7053
08-15 16:22:24.426   319  1395 V AudioFlinger: releasing 20 from 7053 for 7053
08-15 16:22:24.426   319  1395 V AudioFlinger:  decremented refcount to 0
08-15 16:22:24.426   319  1395 V AudioFlinger: purging stale effects
08-15 16:22:24.426   319  1395 V AudioPolicyService: AudioCommandThread() adding release output 2
08-15 16:22:24.426   319  1395 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-15 16:22:24.426   319  1269 V AudioPolicyService: AudioCommandThread() waking up
08-15 16:22:24.427   319  1269 V AudioPolicyService: AudioCommandThread() processing release output 2
08-15 16:22:24.427   319  1269 V AudioPolicyManager: releaseOutput() 2
08-15 16:22:24.427   319  1269 V AudioPolicyService: AudioCommandThread() going to sleep
08-15 16:22:24.427   319  1395 V AudioFlinger: PlaybackThread::Track destructor
08-15 16:22:24.427   319  1395 V AudioFlinger: removeClient_l() pid 7053, calling pid 319
08-15 16:22:24.434  7053  7053 V AudioManager: registerRemoteController: size of Media player list: 0
08-15 16:22:24.439  7053  7053 E AudioManager: No RCC entry present to update
08-15 16:22:24.439  7053  7053 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-15 16:22:24.441  7148  7564 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 16:22:24.442  7053  7053 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-15 16:22:24.443  7053  7053 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-15 16:22:24.443  7053  7053 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-15 16:22:24.445  3420  3420 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-15 16:22:24.445  3420  3420 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-15 16:22:24.445  3420  3420 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-15 16:22:24.450  7053  7053 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-15 16:22:24.503  7179  7179 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-15 16:22:24.503  7179  7179 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-15 16:22:24.508  7017  7568 W FormManager: Network not available. Please check & try again.
08-15 16:22:24.513  7540  7540 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-15 16:22:24.514  7540  7540 W LG Account v2.2: No ProfileInfo entries
08-15 16:22:24.515  7540  7540 I LG Account v2.2: isEnabled: false
08-15 16:22:24.515  7540  7540 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-15 16:22:24.515  7540  7540 I Feature : [Lifetracker]Country: EU
08-15 16:22:24.516  7540  7540 I Feature : [Lifetracker]Operator: OPEN
08-15 16:22:24.516  7540  7540 I Feature : [Lifetracker]Ranking support: false
08-15 16:22:24.516  7540  7540 I Feature : [Lifetracker]Comfort support: false
08-15 16:22:24.516  7234  7234 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:22:24
08-15 16:22:24.516  7540  7540 I Feature : [Lifetracker]Accessory: true
08-15 16:22:24.517  7540  7540 I Feature : [Lifetracker]Health device: true
08-15 16:22:24.517  7540  7540 I Feature : [Lifetracker]Extra Pedometer: false
08-15 16:22:24.517  7540  7540 I Feature : [Lifetracker]Blood glucose device: false
08-15 16:22:24.517  7540  7540 I Feature : [Lifetracker]Device Number: 3
08-15 16:22:24.519  7234  7234 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-15 16:22:24.519  7234  7234 D Weather.Utils: 2 : All the weather widget is gone.
,08-15 16:22:24.519  7017  7569 V FormManager: Network unavailable.
08-15 16:22:24.520  7234  7234 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-15 16:22:24.520  7234  7234 D WeatherAncestor: connectivity changed - connection : true
08-15 16:22:24.520  7234  7234 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@8c1d179
08-15 16:22:24.526  7234  7234 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-15 16:22:24.528  7234  7234 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-15 16:22:24.528  7234  7234 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-15 16:22:24.528  7234  7234 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-15 16:22:24.529  7234  7234 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:22:24
08-15 16:22:24.530  7017  7569 V FormManager: Network unavailable.
08-15 16:22:24.534  6929  6929 D BluetoothPermissionRequest: onReceive
,08-15 16:22:24.546  6929  6929 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-15 16:22:24.562  1036  1992 V SIM_STK : Menu title from STK is T-Mobile
08-15 16:22:24.562  1036  1992 V SIM_STK : Menu title from STK is T-Mobile
08-15 16:22:24.562  6515  6515 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-15 16:22:24.563  6515  6948 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-15 16:22:24.581  2131  2131 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-15 16:22:24.590  7117  7117 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-15 16:22:24.590  7117  7117 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-15 16:22:24.590  7117  7117 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-15 16:22:24.590  7117  7117 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-15 16:22:24.591  7117  7117 I AppUp4:CustModeStarterReceiver: onReceive
08-15 16:22:24.594  7117  7117 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@227395c3
08-15 16:22:24.594  7117  7117 D AppUp4:CustFacade: isCustomizationCompleted : false
08-15 16:22:24.594  7117  7117 D AppUp4:CustFacade: isPhone : true
08-15 16:22:24.594  7117  7117 D AppUp4:CustModeStarterReceiver: begin check event
,08-15 16:22:24.594  7117  7117 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-15 16:22:24.597  4300  4300 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-15 16:22:24.598  4300  4300 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-15 16:22:24.600  4300  4300 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-15 16:22:24.602  4300  4300 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-15 16:22:24.607  7148  7148 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-15 16:22:24.609  4300  7573 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-15 16:22:24.613  4300  7574 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-15 16:22:24.614  4300  7574 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-15 16:22:24.626  3420  3420 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,08-15 16:22:24.626  3420  3420 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-15 16:22:24.626  3420  3420 I LgeMiscReceiver: networkInfo.isConnected() = false
08-15 16:22:24.629  7179  7179 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-15 16:22:24.629  7179  7179 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-15 16:22:24.632  7148  7576 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 16:22:24.641  7017  7577 W FormManager: Network not available. Please check & try again.
,08-15 16:22:24.645  7234  7234 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:22:24
08-15 16:22:24.645  1036  1052 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-15 16:22:24.645  7017  7578 V FormManager: Network unavailable.
08-15 16:22:24.649  7234  7234 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-15 16:22:24.649  7234  7234 D Weather.Utils: 2 : All the weather widget is gone.
08-15 16:22:24.650  7234  7234 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-15 16:22:24.650  7234  7234 D WeatherAncestor: connectivity changed - connection : true
08-15 16:22:24.650  7234  7234 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@8c1d179
08-15 16:22:24.650  7234  7234 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-15 16:22:24.650  7234  7234 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-15 16:22:24.650  7234  7234 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-15 16:22:24.650  7234  7234 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-15 16:22:24.651  7234  7234 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:22:24
08-15 16:22:24.652  7053  7053 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-15 16:22:24.654  7017  7578 V FormManager: Network unavailable.
,08-15 16:22:24.656  7053  7053 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-15 16:22:24.657  7053  7053 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-15 16:22:24.657  7053  7053 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-15 16:22:24.657  7053  7053 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-15 16:22:24.657  7053  7053 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-15 16:22:24.657  7053  7053 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-15 16:22:24.657  7053  7053 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-15 16:22:24.657  7053  7053 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-15 16:22:24.657  7053  7053 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-15 16:22:24.657  7053  7053 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-15 16:22:24.657  7053  7053 I BluetoothA2dpServiceJni: classInitNative
08-15 16:22:24.657  7053  7053 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-15 16:22:24.658  7053  7053 D A2dpStateMachine: make
08-15 16:22:24.659  7053  7053 I bluedroid-qcom: get_profile_interface a2dp
08-15 16:22:24.659  7053  7581 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-15 16:22:24.661  7053  7053 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-15 16:22:24.661  7053  7053 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-15 16:22:24.662  7053  7053 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8c1d179
08-15 16:22:24.662  7053  7580 D A2dpStateMachine: Enter Disconnected: -2
08-15 16:22:24.662  7053  7053 I BluetoothHidServiceJni: classInitNative: succeeds
08-15 16:22:24.664  7053  7053 D HidService: Received start request. Starting profile...
08-15 16:22:24.664  7053  7053 I bluedroid-qcom: get_profile_interface hidhost
08-15 16:22:24.664  7053  7053 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8c1d179
08-15 16:22:24.665  7053  7053 I BluetoothHealthServiceJni: classInitNative: succeeds
08-15 16:22:24.668  7053  7053 D HealthService: Received start request. Starting profile...
,08-15 16:22:24.670  7053  7053 I bluedroid-qcom: get_profile_interface health
08-15 16:22:24.670  7053  7053 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-15 16:22:24.670  7053  7053 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8c1d179
08-15 16:22:24.671  7053  7053 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-15 16:22:24.672  7053  7053 D PanService: Received start request. Starting profile...
08-15 16:22:24.672  7053  7053 D BluetoothPanServiceJni: initializeNative(L110): pan
08-15 16:22:24.672  7053  7053 I bluedroid-qcom: get_profile_interface pan
08-15 16:22:24.677  7053  7053 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-15 16:22:24.677  7053  7053 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8c1d179
08-15 16:22:24.678  7053  7053 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-15 16:22:24.681  7053  7053 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-15 16:22:24.682  7053  7053 D BtGatt.GattService: Received start request. Starting profile...
08-15 16:22:24.682  7053  7053 D BtGatt.GattService: start()
08-15 16:22:24.682  7053  7053 I bluedroid-qcom: get_profile_interface gatt
08-15 16:22:24.682  7053  7053 D BtGatt.AdvertiseManager: advertise manager created
08-15 16:22:24.687  7053  7053 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8c1d179
08-15 16:22:24.689  7053  7053 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8c1d179
08-15 16:22:24.689  7053  7053 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-15 16:22:24.690  7053  7053 V BluetoothMapService: BluetoothMapBinder()
08-15 16:22:24.690  7053  7053 D BluetoothMapService: Received start request. Starting profile...
08-15 16:22:24.690  7053  7053 D BluetoothMapService: start()
08-15 16:22:24.693  7053  7053 D BluetoothMapEmailSettingsLoader: Found 0 applications
,08-15 16:22:24.693  7053  7053 D BluetoothMapEmailAppObserver: createReceiver()
08-15 16:22:24.694  7053  7053 D BluetoothMapEmailAppObserver: initObservers()
08-15 16:22:24.694  7053  7053 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-15 16:22:24.701  7053  7053 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8c1d179
08-15 16:22:24.701  7053  7053 D HeadsetStateMachine: Proxy object connected
08-15 16:22:24.702  7053  7053 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-15 16:22:24.702  7053  7053 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-15 16:22:24.705  7053  7053 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-15 16:22:24.706  7053  7550 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-15 16:22:24.706  7053  7550 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-15 16:22:24.707  7053  7550 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-15 16:22:24.708  7053  7053 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-15 16:22:24.710  7053  7053 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-15 16:22:24.712  7053  7053 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-15 16:22:24.712  7053  7053 V PanService: [BTUI] SIM Extra State :ABSENT
08-15 16:22:24.714  7053  7053 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-15 16:22:24.716  7053  7053 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
,08-15 16:22:24.716  7053  7053 V BluetoothMapService: Handler(): got msg=1
08-15 16:22:24.717  7053  7519 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-15 16:22:24.717  7053  7519 I bluedroid-qcom: enable
08-15 16:22:24.718  7053  7519 I bt_hci_bdroid: init
08-15 16:22:24.719  7053  7053 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-15 16:22:24.719  7053  7519 I bt_vendor: bt-vendor : init
08-15 16:22:24.719  7053  7519 I bt_vendor: bt-vendor : get_bt_soc_type
08-15 16:22:24.719  7053  7519 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-15 16:22:24.719  7053  7519 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-15 16:22:24.719  7053  7519 D bt_userial_mct: userial_init
08-15 16:22:24.719  7053  7588 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-15 16:22:24.719  7053  7519 D bt_hci_bdroid: set_power 1
08-15 16:22:24.719  7053  7588 I bt-btu  : btu_task pending for preload complete event
08-15 16:22:24.719  7053  7519 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-15 16:22:24.719  7053  7519 I bt_vendor: Starting hciattach daemon
08-15 16:22:24.719  7053  7519 I bt_vendor: try to set true
08-15 16:22:24.720  7053  7053 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-15 16:22:24.720  7053  7053 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-15 16:22:24.720  7053  7053 V BluetoothSapReceiver: SapReceiver onReceive 
08-15 16:22:24.720  7053  7053 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-15 16:22:24.720  7053  7053 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-15 16:22:24.717  7591  7591 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-15 16:22:24.717  7591  7591 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-15 16:22:24.738  7592  7592 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-15 16:22:24.794  7598  7598 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-15 16:22:24.811  7599  7599 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-15 16:22:24.832  7601  7601 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-15 16:22:24.844  7602  7602 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-15 16:22:24.859  7603  7603 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-15 16:22:24.872  7604  7604 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-15 16:22:24.897  7606  7606 I libmdmdetect: ESOC framework not supported
,08-15 16:22:24.898  7606  7606 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-15 16:22:24.906  7606  7606 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-15 16:22:24.906  7606  7606 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-15 16:22:24.906  7606  7606 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-15 16:22:24.906  7606  7606 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-15 16:22:24.906  7606  7606 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-15 16:22:24.906  7606  7606 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-15 16:22:24.906  7606  7606 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-15 16:22:24.941  7606  7607 E QC-QMI  : qmi_client [7606] 14: failed to locate client data
,08-15 16:22:24.944   453   453 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-15 16:22:24.944   453   453 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
08-15 16:22:24.988  7608  7608 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-15 16:22:25.021  7612  7612 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-15 16:22:25.072  7053  7519 I bt_vendor: bluetooth satus is on
08-15 16:22:25.072  7053  7519 D bt_hci_bdroid: preload
,08-15 16:22:25.074  7053  7590 D bt_userial_mct: userial_open(port:0)
08-15 16:22:25.074  7053  7590 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-15 16:22:25.078  7053  7590 I bt_vendor: Done intiailizing UART
08-15 16:22:25.079  7053  7590 I bt_vendor: Done intiailizing UART
08-15 16:22:25.079  7053  7590 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-15 16:22:25.080  7053  7590 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-15 16:22:25.080  7053  7617 D bt_userial_mct: Entering userial_read_thread()
,08-15 16:22:25.080  7053  7588 I bt-btu  : btu_task received preload complete event
08-15 16:22:25.080  7053  7588 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-15 16:22:25.080  7053  7588 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-15 16:22:25.083  7053  7588 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-15 16:22:25.087  7053  7588 I         : BTE_InitTraceLevels -- TRC_HCI
08-15 16:22:25.087  7053  7588 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-15 16:22:25.087  7053  7588 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-15 16:22:25.087  7053  7588 I         : BTE_InitTraceLevels -- TRC_AVDT
08-15 16:22:25.087  7053  7588 I         : BTE_InitTraceLevels -- TRC_AVRC
08-15 16:22:25.087  7053  7588 I         : BTE_InitTraceLevels -- TRC_A2D
08-15 16:22:25.087  7053  7588 I         : BTE_InitTraceLevels -- TRC_BNEP
08-15 16:22:25.087  7053  7588 I         : BTE_InitTraceLevels -- TRC_BTM
08-15 16:22:25.087  7053  7588 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-15 16:22:25.087  7053  7588 I         : BTE_InitTraceLevels -- TRC_GAP
08-15 16:22:25.087  7053  7588 I         : BTE_InitTraceLevels -- TRC_PAN
08-15 16:22:25.087  7053  7588 I         : BTE_InitTraceLevels -- TRC_SDP
08-15 16:22:25.087  7053  7588 I         : BTE_InitTraceLevels -- TRC_GATT
08-15 16:22:25.087  7053  7588 I         : BTE_InitTraceLevels -- TRC_SMP
08-15 16:22:25.087  7053  7588 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-15 16:22:25.087  7053  7588 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-15 16:22:25.143  7053  7588 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-15 16:22:25.143  7053  7588 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa018e061 
08-15 16:22:25.143  7053  7588 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa018e061 
,08-15 16:22:25.185  7053  7523 E bt-btif : Calling BTA_HhEnable
,08-15 16:22:25.185  7053  7523 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-15 16:22:25.186  7053  7523 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-15 16:22:25.194  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-15 16:22:25.195  7053  7588 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
,08-15 16:22:25.195  7053  7588 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-15 16:22:25.195  7053  7588 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-15 16:22:25.196  7053  7588 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-15 16:22:25.196  7053  7588 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-15 16:22:25.197  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
08-15 16:22:25.197  7053  7523 D BluetoothAdapterProperties: Name is: G3
08-15 16:22:25.201  7053  7523 D BluetoothAdapterProperties: Scan Mode:20
08-15 16:22:25.205  7053  7523 D BluetoothAdapterProperties: Discoverable Timeout:120
08-15 16:22:25.205  7053  7523 D bt_hci_bdroid: postload
,08-15 16:22:25.210  7053  7590 D bt_hci_bdroid: Used up Tx Cmd credits
08-15 16:22:25.211  7053  7590 D bt_hci_bdroid: Used up Tx Cmd credits
08-15 16:22:25.211  7053  7588 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-15 16:22:25.212  7053  7523 D bte_conf: Device ID record 1 : primary
08-15 16:22:25.212  7053  7523 D bte_conf:   vendorId            = 00c4
08-15 16:22:25.212  7053  7523 D bte_conf:   vendorIdSource      = 0001
08-15 16:22:25.212  7053  7523 D bte_conf:   product             = 13a1
08-15 16:22:25.212  7053  7523 D bte_conf:   version             = 1000
08-15 16:22:25.212  7053  7523 D bte_conf:   clientExecutableURL = 
08-15 16:22:25.212  7053  7523 D bte_conf:   serviceDescription  = 
08-15 16:22:25.212  7053  7523 D bte_conf:   documentationURL    = 
08-15 16:22:25.212  7053  7523 D bte_conf: bte_load_did_conf no section named DID2.
08-15 16:22:25.215  7053  7590 D bt_hci_bdroid: Used up Tx Cmd credits
08-15 16:22:25.218  7053  7519 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-15 16:22:25.218  7053  7519 D BluetoothAdapterProperties: ScanMode =  20
08-15 16:22:25.219  7053  7519 D BluetoothAdapterProperties: State =  11
08-15 16:22:25.219  7053  7519 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-15 16:22:25.219  7053  7519 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-15 16:22:25.219  7053  7519 D BluetoothAdapterProperties: Setting state to 12
08-15 16:22:25.219  7053  7519 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-15 16:22:25.222  7053  7523 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-15 16:22:25.217  7622  7622 W sh      : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-15 16:22:25.225  1036  1118 D BluetoothManagerService: Message: 60
08-15 16:22:25.225  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-15 16:22:25.225  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
08-15 16:22:25.226  7053  7588 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-15 16:22:25.226  7053  7588 W bt-smp  : Plain text(LSB ~ MSB) = 6f f1 78 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-15 16:22:25.226  7053  7588 W bt-smp  : Encrypted text(LSB ~ MSB) = 0c 17 36 76 ef be 4b 83 c1 13 d8 36 ab 69 58 25 
08-15 16:22:25.228  7053  7590 D bt_hci_bdroid: Used up Tx Cmd credits
08-15 16:22:25.228  7053  7588 W bt-btm  : Stopping oneshot timer
08-15 16:22:25.228  7053  7523 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-15 16:22:25.227  7622  7622 W sh      : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-15 16:22:25.237  7053  7617 E bt_mct  : hci lib postload completed
,08-15 16:22:25.252  7053  7519 I BluetoothAdapterState: Entering On State
,08-15 16:22:25.269  6826  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-15 16:22:25.269  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 16:22:25.269  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-15 16:22:25.269  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-15 16:22:25.269  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-15 16:22:25.269  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-15 16:22:25.269  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-15 16:22:25.269  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-15 16:22:25.274  6826  6826 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-15 16:22:25.275  7053  7523 D BluetoothAdapterProperties: Discoverable Timeout:120
08-15 16:22:25.275  7053  7523 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-15 16:22:25.279  7053  7588 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-15 16:22:25.279  7053  7588 W bt-smp  : Plain text(LSB ~ MSB) = c9 26 53 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-15 16:22:25.279  7053  7588 W bt-smp  : Encrypted text(LSB ~ MSB) = db 12 21 bb 02 9f 42 a5 95 93 fd f0 72 ef 01 0d 
08-15 16:22:25.279  7053  7588 W bt-btm  : Stopping oneshot timer
08-15 16:22:25.292  7053  7588 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-15 16:22:25.293  7053  7588 W bt-smp  : Plain text(LSB ~ MSB) = 07 c5 62 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-15 16:22:25.293  7053  7588 W bt-smp  : Encrypted text(LSB ~ MSB) = 09 2c 75 cf 0c 79 ea 42 c2 b5 ca d6 1c 5d 94 8e 
,08-15 16:22:25.295  7053  7588 W bt-btm  : Stopping oneshot timer
08-15 16:22:25.296  6826  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-15 16:22:25.296  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 16:22:25.296  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-15 16:22:25.296  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-15 16:22:25.296  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-15 16:22:25.296  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-15 16:22:25.296  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-15 16:22:25.296  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-15 16:22:25.298  6826  6826 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-15 16:22:25.309  7053  7519 D LGBluetoothServiceAdapter: [BTUI] OnState
08-15 16:22:25.310  7053  7519 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-15 16:22:25.310  7053  7519 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,08-15 16:22:25.318  7053  7519 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-15 16:22:25.319  7053  7519 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-15 16:22:25.319  7053  7588 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-15 16:22:25.319  7053  7588 W bt-smp  : Plain text(LSB ~ MSB) = 8d bd 60 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-15 16:22:25.319  7053  7588 W bt-smp  : Encrypted text(LSB ~ MSB) = d6 1f a5 fe 1c 34 af 26 f3 5a 27 a4 30 6f bd e6 
08-15 16:22:25.319  7053  7588 W bt-btm  : Stopping oneshot timer
08-15 16:22:25.328   312  7282 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-15 16:22:25.329   312  7282 D libc-netbsd: res_queryN name = clients3.google.com., class = 1, type = 28
08-15 16:22:25.329   312  7282 D libc-netbsd: res_queryN name = clients3.google.com., class = 1, type = 1
,08-15 16:22:25.343  1036  1116 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-15 16:22:25.347  1036  7258 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
08-15 16:22:25.347  1036  7258 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-4s175ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-15 16:22:25.347  1036  7258 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-4s175ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-15 16:22:25.347  1036  7258 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-15 16:22:25.355  7636  7636 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-15 16:22:25.357  7053  7588 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-15 16:22:25.357  7053  7588 W bt-smp  : Plain text(LSB ~ MSB) = 86 4c 61 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-15 16:22:25.357  7053  7588 W bt-smp  : Encrypted text(LSB ~ MSB) = 52 cd c5 0b 11 b0 64 cc 1b 80 6f f8 62 3a 64 35 
08-15 16:22:25.357  7053  7588 W bt-btm  : Stopping oneshot timer
08-15 16:22:25.363  6929  6944 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-15 16:22:25.370  6929  6945 D BluetoothPbap: onBluetoothStateChange: up=true
08-15 16:22:25.372  1036  1118 D BluetoothHeadset: onBluetoothStateChange: up=true
08-15 16:22:25.374  1036  1036 D BluetoothHeadset: Proxy object connected
08-15 16:22:25.376  1853  4421 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-15 16:22:25.381  1853  1868 D BluetoothHeadset: onBluetoothStateChange: up=true
08-15 16:22:25.383  6929  6944 D BluetoothMap: onBluetoothStateChange: up=true
08-15 16:22:25.386  1036  1118 D BluetoothA2dp: onBluetoothStateChange: up=true
08-15 16:22:25.388  1853  1853 D BluetoothHeadset: Proxy object connected
08-15 16:22:25.388  1853  1853 D BluetoothHeadset: Proxy object connected
08-15 16:22:25.389  1036  1036 D BluetoothA2dp: Proxy object connected
08-15 16:22:25.390  1036  1092 W ProcessCpuTracker: Skipping unknown process pid 7622
08-15 16:22:25.391  1036  1092 W ProcessCpuTracker: Skipping unknown process pid 7625
08-15 16:22:25.391  6929  6929 D BluetoothInputDevice: Proxy object connected
08-15 16:22:25.391  6929  6929 D HidProfile: Bluetooth service connected
,08-15 16:22:25.394  1853  2462 D BluetoothHeadset: onBluetoothStateChange: up=true
08-15 16:22:25.394  6929  6929 D BluetoothMap: Proxy object connected
08-15 16:22:25.394  6929  6929 D MapProfile: Bluetooth service connected
08-15 16:22:25.394  6929  6929 D BluetoothMap: getConnectedDevices()
08-15 16:22:25.395  7053  7643 V BluetoothMapService: getConnectedDevices()
08-15 16:22:25.396  1853  1853 D BluetoothHeadset: Proxy object connected
08-15 16:22:25.396  6929  7638 D BluetoothPan: onBluetoothStateChange on: true
08-15 16:22:25.396  6929  7638 D BluetoothPan: onBluetoothStateChange call bindService
08-15 16:22:25.398  6929  6929 D BluetoothPan: BluetoothPAN Proxy object connected
08-15 16:22:25.398  6929  6929 D PanProfile: Bluetooth service connected
08-15 16:22:25.399  1036  1118 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-15 16:22:25.399  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-15 16:22:25.404  6826  6826 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
08-15 16:22:25.404  1942  1942 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-15 16:22:25.404  1942  2100 D LGBluetoothAPIService: Message: 1
08-15 16:22:25.404  1942  2100 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-15 16:22:25.405  1606  1606 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-15 16:22:25.407  7053  7053 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-15 16:22:25.407  7053  7053 D BluetoothMapService: STATE_ON
08-15 16:22:25.408  7053  7053 V BluetoothMapService: Handler(): got msg=1
,08-15 16:22:25.408  7053  7053 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-15 16:22:25.410  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-15 16:22:25.410  1036  1118 D BluetoothManagerService: Message: 40
08-15 16:22:25.410  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-15 16:22:25.411  6929  6929 D LocalBluetoothProfileManager: Adding local A2DP profile
08-15 16:22:25.411  7053  7644 D BluetoothMapMasInstance: MAS initSocket()
08-15 16:22:25.411  7053  7644 D BluetoothMapMasInstance:   masId = 00
08-15 16:22:25.411  7053  7644 D BluetoothMapMasInstance:   msgTypes = 0e
08-15 16:22:25.411  7053  7644 D BluetoothMapMasInstance:   masName = SMS/MMS
08-15 16:22:25.411  7053  7644 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-15 16:22:25.413  1036  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-15 16:22:25.413  1036  1118 D BluetoothManagerService: Message: 30
08-15 16:22:25.416  6826  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 16:22:25.416  1942  2100 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-15 16:22:25.417  7053  7644 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-15 16:22:25.417  6826  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 16:22:25.418  7053  7644 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-15 16:22:25.419  7053  7644 V BluetoothMapMasInstance: Succeed to create listening socket 
08-15 16:22:25.419  7053  7644 D BluetoothMapMasInstance: Accepting socket connection...
08-15 16:22:25.419  7053  7523 D BluetoothAdapterProperties: Scan Mode:21
08-15 16:22:25.419  7053  7523 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
,08-15 16:22:25.423  7053  7053 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8c1d179
08-15 16:22:25.423  6826  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 16:22:25.423  7053  7053 V BluetoothPbapService: Pbap Service onCreate
08-15 16:22:25.423  7053  7053 V BluetoothPbapService: Starting PBAP service
08-15 16:22:25.424  6826  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 16:22:25.425  7053  7053 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-15 16:22:25.425  7053  7053 V BluetoothPbapService: Pbap Service onBind
08-15 16:22:25.426  7053  7053 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,08-15 16:22:25.426  7053  7053 V BluetoothPbapService: state: 12
08-15 16:22:25.427  7053  7053 D LGBluetoothAPIServer: [BTUI] onCreate()
08-15 16:22:25.427  7053  7053 D LGBluetoothAPIServer: [BTUI] onBind()
08-15 16:22:25.428  7053  7053 V BluetoothPbapService: Handler(): got msg=1
08-15 16:22:25.428  1942  1942 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-15 16:22:25.429  7053  7053 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-15 16:22:25.429  1942  2100 D LGBluetoothAPIService: Message: 100
08-15 16:22:25.429  1942  2100 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-15 16:22:25.429  6929  6929 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-15 16:22:25.430  7053  7645 V BluetoothPbapService: Pbap Service initSocket
08-15 16:22:25.430  1036  1939 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-15 16:22:25.432  1036  1118 D BluetoothManagerService: Message: 30
08-15 16:22:25.433  7053  7645 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-15 16:22:25.436  7053  7645 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-15 16:22:25.436  7053  7645 V BluetoothPbapService: Succeed to create listening socket 
08-15 16:22:25.436  7053  7645 V BluetoothPbapService: Accepting socket connection...
08-15 16:22:25.437  6929  6929 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-15 16:22:25.439  6929  6929 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-15 16:22:25.441  6929  6929 D BluetoothPbap: Proxy object connected
08-15 16:22:25.441  6929  6929 D PbapServerProfile: Bluetooth service connected
08-15 16:22:25.441  6929  6929 D BluetoothA2dp: Proxy object connected
08-15 16:22:25.442  7053  7053 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-15 16:22:25.442  6929  6929 D A2dpProfile: Bluetooth service connected
08-15 16:22:25.442  7053  7053 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-15 16:22:25.442  7053  7053 V BluetoothPbapReceiver: ***********state = 12
08-15 16:22:25.446  6929  6929 D BluetoothHeadset: Proxy object connected
,08-15 16:22:25.447  2131  2131 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-15 16:22:25.447  6929  6929 D HeadsetProfile: Bluetooth service connected
08-15 16:22:25.447  2131  2131 D c       : Getting all permits...
08-15 16:22:25.447  2131  2131 D a       : Opening database...
08-15 16:22:25.451  6929  6929 D DockEventReceiver: finishStartingService: stopping service
08-15 16:22:25.451  2131  2131 D a       : Opening database auth.proximity.permit_store...
08-15 16:22:25.452  2131  2131 D a       : Closing database...
08-15 16:22:25.463  7261  7291 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
08-15 16:22:25.463  6929  6929 D BluetoothPermissionRequest: onReceive
08-15 16:22:25.465  6929  6929 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,08-15 16:22:25.466  6929  6929 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-15 16:22:25.470  7053  7053 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-15 16:22:25.471  7053  7053 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-15 16:22:25.476  7053  7053 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-15 16:22:25.500  7053  7053 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-15 16:22:25.500  7053  7053 V BtOppService: onCreate
08-15 16:22:25.505  7053  7053 V BluetoothOppNotification: send message
08-15 16:22:25.508  7053  7053 V BtOppService: Starting RfcommListener
08-15 16:22:25.516  7053  7053 D BluetoothOppPreference: Dumping Names:  
08-15 16:22:25.516  7053  7053 D BluetoothOppPreference: {}
08-15 16:22:25.516  7053  7053 D BluetoothOppPreference: Dumping Channels:  
08-15 16:22:25.516  7053  7053 D BluetoothOppPreference: {}
08-15 16:22:25.517  7053  7053 V BtOppService: onStartCommand
,08-15 16:22:25.523  7053  7053 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-15 16:22:25.524  7053  7053 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-15 16:22:25.528  7053  7658 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
,08-15 16:22:25.529  7053  7053 V BluetoothOppNotification: new notify threadi!
08-15 16:22:25.530  7053  7053 V BluetoothOppNotification: send delay message
08-15 16:22:25.532  7053  7658 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-15 16:22:25.533  7053  7053 V BtOppService: start RfcommListener
08-15 16:22:25.536  7053  7658 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@20edfbda on behalf of 
08-15 16:22:25.536  7053  7654 V BtOppService: Deleted complete outbound shares, number =  0
08-15 16:22:25.538  7053  7659 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-15 16:22:25.540  7053  7053 V BtOppService: RfcommListener started
08-15 16:22:25.540  7053  7659 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2cacd80b on behalf of 
08-15 16:22:25.541  7053  7660 V BtOppRfcommListener: Starting RFCOMM listener....
,08-15 16:22:25.541  7053  7654 V BtOppService: Deleted complete inbound failed shares, number = 0
08-15 16:22:25.541  7053  7654 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-15 16:22:25.543  7053  7659 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-15 16:22:25.544  1036  1939 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-15 16:22:25.544  7053  7654 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@12ed86e8 on behalf of 
08-15 16:22:25.545  7053  7660 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-15 16:22:25.545  7053  7658 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-15 16:22:25.546  7053  7660 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=81 mFd=75
08-15 16:22:25.546  7053  7660 V BtOppRfcommListener: Started RFCOMM listener....
08-15 16:22:25.546  7053  7660 I BtOppRfcommListener: Accept thread started.
08-15 16:22:25.546  7053  7660 V BtOppRfcommListener: Accepting connection...
08-15 16:22:25.549  7053  7659 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-15 16:22:25.552  7053  7659 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2dad5101 on behalf of 
08-15 16:22:25.553  7053  7659 V BluetoothOppNotification: outbound: succ-0  fail-0
,08-15 16:22:25.556  7053  7659 V BluetoothOppNotification: outbound notification was removed.
08-15 16:22:25.556  7053  7659 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-15 16:22:25.559  7053  7659 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@293ffba6 on behalf of 
08-15 16:22:25.561  7053  7659 V BluetoothOppNotification: inbound: succ-0  fail-0
08-15 16:22:25.561  7053  7053 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8c1d179
08-15 16:22:25.562  7053  7053 V BluetoothFtpService: Ftp Service onCreate
08-15 16:22:25.562  7053  7053 I BluetoothFtpService: Ftp Service onCreate
08-15 16:22:25.562  7053  7053 V BluetoothFtpService: Ftp Service onStartCommand
08-15 16:22:25.563  7053  7053 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
,08-15 16:22:25.563  7053  7053 V BluetoothFtpService: Starting Listening on sockets
08-15 16:22:25.563  7053  7659 V BluetoothOppNotification: inbound notification was removed.
08-15 16:22:25.564  7053  7659 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-15 16:22:25.564  7053  7053 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-15 16:22:25.564  7053  7053 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-15 16:22:25.564  7053  7053 V BluetoothSapReceiver: SapReceiver onReceive 
08-15 16:22:25.564  7053  7053 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-15 16:22:25.564  7053  7053 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-15 16:22:25.565  7053  7053 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-15 16:22:25.565  7053  7659 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@7882994 on behalf of 
,08-15 16:22:25.567  7053  7053 V BtOppService: ContentObserver received notification
08-15 16:22:25.568  7053  7053 V BtOppService: ContentObserver received notification
08-15 16:22:25.568  7053  7053 V BluetoothFtpService: Handler(): got msg=1
08-15 16:22:25.569  7053  7053 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-15 16:22:25.569  7053  7661 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-15 16:22:25.569  7053  7053 V BluetoothFtpService: Ftp Service initSocket
08-15 16:22:25.569  7053  7661 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-15 16:22:25.570  7053  7661 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2e1cfc3d on behalf of 
08-15 16:22:25.571  1036  1787 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-15 16:22:25.572  7053  7053 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-15 16:22:25.573  7053  7661 V BluetoothOppNotification: update too frequent, put in queue
08-15 16:22:25.574  7053  7661 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-15 16:22:25.576  7053  7053 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-15 16:22:25.578  7053  7662 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
,08-15 16:22:25.592  7053  7053 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8c1d179
,08-15 16:22:25.593  7053  7053 V BluetoothSapService: Sap Service onCreate
08-15 16:22:25.595  7053  7053 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-15 16:22:25.595  7053  7053 V BluetoothSapService: state: 12
08-15 16:22:25.595  7053  7053 V BluetoothSapService: Starting SAP server process
08-15 16:22:25.597  7053  7053 V BluetoothSapService: SAP Service startRfcommListenerThread
08-15 16:22:25.587  7663  7663 W sapd    : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-15 16:22:25.587  7663  7663 W sapd    : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-15 16:22:25.599  7053  7664 V BluetoothSapService: Sap Service initRfcommSocket
08-15 16:22:25.600  1036  1918 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-15 16:22:25.603  7053  7664 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-15 16:22:25.604  7053  7664 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=81
08-15 16:22:25.604  7053  7664 V BluetoothSapService: Succeed to create listening socket 
08-15 16:22:25.604  7053  7664 V BluetoothSapService: Accepting socket connection...
08-15 16:22:25.611  7663  7663 V BT_SAP  : Event pipe created
08-15 16:22:25.611  7663  7663 V BT_SAP  : create_server_socket qcom.sap.server
08-15 16:22:25.611  7663  7663 V BT_SAP  : created socket fd 6
,08-15 16:22:26.113  1036  1389 D LGWifiP2pService: P2pDisabledState{ when=-3ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-15 16:22:26.113  1036  1389 D LGWifiP2pService: DefaultState{ when=-3ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-15 16:22:26.173  1036  1422 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-15 16:22:26.181  1036  1422 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
08-15 16:22:26.352  1036  2046 I ActivityManager: Killing 7437:com.lge.bnr/1000 (adj 15): empty #17
,08-15 16:22:26.383  1036  1918 W libprocessgroup: failed to open /acct/uid_1000/pid_7437/cgroup.procs: No such file or directory
,08-15 16:22:26.533  7053  7053 V BluetoothOppNotification: new notify threadi!
,08-15 16:22:26.534  7053  7053 V BluetoothOppNotification: send delay message
,08-15 16:22:26.547  7053  7674 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-15 16:22:26.710  1036  1550 I art     : Explicit concurrent mark sweep GC freed 94635(4MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 2.879ms total 153.414ms
,08-15 16:22:26.719  1036  2025 I ActivityManager: Killing 6949:com.lge.sync/1000 (adj 15): empty #17
08-15 16:22:26.727  7053  7674 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@26e21f39 on behalf of 
08-15 16:22:26.728  7053  7674 V BluetoothOppNotification: mUpdateCompleteNotification = true
,08-15 16:22:26.737  1036  1470 D WifiService: Client connection lost with reason: 4
08-15 16:22:26.738  7053  7674 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-15 16:22:26.739  7053  7674 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@12e0d97e on behalf of 
08-15 16:22:26.740  7053  7674 V BluetoothOppNotification: outbound: succ-0  fail-0
,08-15 16:22:26.743  7053  7674 V BluetoothOppNotification: outbound notification was removed.
,08-15 16:22:26.743  7053  7674 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-15 16:22:26.744  7053  7674 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1752edf on behalf of 
08-15 16:22:26.745  7053  7674 V BluetoothOppNotification: inbound: succ-0  fail-0
08-15 16:22:26.746  7053  7674 V BluetoothOppNotification: inbound notification was removed.
08-15 16:22:26.746  7053  7674 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-15 16:22:26.747  7053  7674 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@32a7172c on behalf of 
08-15 16:22:26.751  1036  1992 W libprocessgroup: failed to open /acct/uid_1000/pid_6949/cgroup.procs: No such file or directory
,08-15 16:22:27.121  1036  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
08-15 16:22:27.122  1036  1051 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@3cd06b72 mBinding = false
,08-15 16:22:27.152  1036  1378 V AlarmManager: ELAPSED_WAKEUP set : Alarm{31a6abc3 type 2 when 203862 com.google.android.gms} when 203862
,08-15 16:22:27.162   312  7676 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-15 16:22:27.163  1036  1116 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-15 16:22:27.174  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-15 16:22:27.174  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-15 16:22:27.174  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-15 16:22:27.175  1036  1118 D BluetoothManagerService: Message: 2
08-15 16:22:27.176  1036  1118 D BluetoothManagerService: Sending off request.
08-15 16:22:27.177  7053  7643 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-15 16:22:27.178  7053  7519 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-15 16:22:27.178  7053  7519 D BluetoothAdapterProperties: Setting state to 13
08-15 16:22:27.178  7053  7519 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-15 16:22:27.179  7053  7519 D BluetoothAdapterProperties: onBluetoothDisable()
08-15 16:22:27.179  7053  7519 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-15 16:22:27.181  7053  7523 D BluetoothAdapterProperties: Scan Mode:20
08-15 16:22:27.184  7053  7519 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,08-15 16:22:27.187  7053  7519 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-15 16:22:27.189  7053  7644 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-15 16:22:27.189  7053  7644 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-15 16:22:27.189  7053  7644 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-15 16:22:27.189  7053  7644 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-15 16:22:27.189  7053  7644 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-15 16:22:27.189  7053  7644 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-15 16:22:27.189  7053  7644 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-15 16:22:27.189  7053  7644 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-15 16:22:27.189  7053  7645 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-15 16:22:27.190  7053  7588 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-15 16:22:27.190  7053  7588 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-15 16:22:27.192  7053  7660 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-15 16:22:27.192  7053  7664 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-15 16:22:27.195  7053  7588 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-15 16:22:27.195  7053  7588 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-15 16:22:27.195  7053  7588 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-15 16:22:27.195  7053  7588 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-15 16:22:27.195  7053  7588 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-15 16:22:27.195  7053  7588 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-15 16:22:27.195  7053  7588 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-15 16:22:27.195  7053  7588 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-15 16:22:27.195  7053  7588 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-15 16:22:27.195  7053  7588 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-15 16:22:27.195  7053  7588 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-15 16:22:27.195  7053  7588 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
,08-15 16:22:27.207  6826  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-15 16:22:27.207  6826  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-15 16:22:27.207  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 16:22:27.207  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-15 16:22:27.207  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-15 16:22:27.207  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-15 16:22:27.207  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-15 16:22:27.207  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-15 16:22:27.207  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-15 16:22:27.209  6826  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-15 16:22:27.212  6826  6826 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-15 16:22:27.216  6826  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-15 16:22:27.216  6826  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-15 16:22:27.216  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 16:22:27.216  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-15 16:22:27.216  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-15 16:22:27.216  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-15 16:22:27.216  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-15 16:22:27.216  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-15 16:22:27.216  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-15 16:22:27.219  6826  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-15 16:22:27.219  6826  6826 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-15 16:22:27.220  1036  1118 D BluetoothManagerService: Message: 60
08-15 16:22:27.220  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-15 16:22:27.220  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-15 16:22:27.224  1942  1942 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-15 16:22:27.228  1606  1606 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-15 16:22:27.234  6826  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 16:22:27.237  6826  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-15 16:22:27.242  7053  7053 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-15 16:22:27.242  7053  7053 D BluetoothMapService: STATE_TURNING_OFF
08-15 16:22:27.242  7053  7053 V BluetoothMapService: Handler(): got msg=4
08-15 16:22:27.242  7053  7053 D BluetoothMapService: MAP Service closeService in
08-15 16:22:27.242  7053  7053 D BluetoothMapMasInstance: MAP Service shutdown
08-15 16:22:27.243  7053  7053 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-15 16:22:27.243  7053  7053 V BluetoothMapService: MAP Service closeService out
08-15 16:22:27.244  7053  7053 V BtOppService: Receiver DISABLED_ACTION 
08-15 16:22:27.244  7053  7053 I BtOppRfcommListener: stopping Accept Thread
08-15 16:22:27.244  7053  7053 V BtOppRfcommListener: close mBtServerSocket
08-15 16:22:27.245  7053  7660 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-15 16:22:27.245  7053  7053 V BtOppRfcommListener: waiting for thread to terminate
08-15 16:22:27.245  7053  7053 V BtOppRfcommListener: done waiting for thread to terminate
08-15 16:22:27.248  6929  6929 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
,08-15 16:22:27.256  7053  7662 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-15 16:22:27.262  6929  6929 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-15 16:22:27.276  6929  6929 D DockEventReceiver: finishStartingService: stopping service
,08-15 16:22:27.285  7053  7053 V BtOppService: onDestroy
08-15 16:22:27.296  7053  7053 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-15 16:22:27.297  7053  7053 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-15 16:22:27.297  7053  7053 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-15 16:22:27.297  7053  7053 V BluetoothPbapReceiver: ***********state = 13
,08-15 16:22:27.301  7053  7053 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-15 16:22:27.304  7053  7053 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-15 16:22:27.304  7053  7053 V BluetoothPbapService: state: 13
08-15 16:22:27.304  7053  7053 V BluetoothPbapService: Pbap Service closeService in
08-15 16:22:27.308  7053  7053 V BluetoothPbapService: successfully stopped pbap service
08-15 16:22:27.308  7053  7053 V BluetoothPbapService: Pbap Service closeService out
08-15 16:22:27.309  2131  2131 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-15 16:22:27.310  7053  7053 V BluetoothPbapService: Pbap Service onDestroy
08-15 16:22:27.310  7053  7053 V BluetoothPbapService: Pbap Service closeService in
08-15 16:22:27.310  7053  7053 V BluetoothPbapService: Pbap Service closeService out
08-15 16:22:27.310  7053  7053 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-15 16:22:27.310  6929  6929 D BluetoothPbap: Proxy object disconnected
08-15 16:22:27.311  6929  6929 D PbapServerProfile: Bluetooth service disconnected
,08-15 16:22:27.322  6929  6929 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-15 16:22:27.329  6929  6929 D BluetoothPermissionRequest: onReceive
08-15 16:22:27.329  6929  6929 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-15 16:22:27.337  6929  6929 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-15 16:22:27.344  7053  7053 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-15 16:22:27.344  7053  7053 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-15 16:22:27.345  7053  7053 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-15 16:22:27.351  7053  7053 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-15 16:22:27.351  7053  7053 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-15 16:22:27.352  7053  7053 V BluetoothFtpService: Ftp Service onStartCommand
08-15 16:22:27.352  7053  7053 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-15 16:22:27.352  7053  7053 V BluetoothFtpService: Ftp Service closeService
08-15 16:22:27.352  7053  7053 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
,08-15 16:22:27.354  7053  7053 V BluetoothFtpService: successfully stopped ftp service
08-15 16:22:27.354  7053  7053 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-15 16:22:27.354  7053  7053 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-15 16:22:27.354  7053  7053 V BluetoothSapReceiver: SapReceiver onReceive 
08-15 16:22:27.354  7053  7053 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-15 16:22:27.354  7053  7053 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-15 16:22:27.354  7053  7053 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-15 16:22:27.356  7053  7053 V BluetoothFtpService: Ftp Service onDestroy
08-15 16:22:27.356  7053  7053 V BluetoothFtpService: Ftp Service closeService
08-15 16:22:27.360  7053  7053 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-15 16:22:27.360  7053  7053 V BluetoothSapService: state: 13
08-15 16:22:27.360  7053  7053 V BluetoothSapService: Stopping SAP server process
08-15 16:22:27.361  7053  7053 V BluetoothSapService: Sap Service closeSapService in
08-15 16:22:27.361  7053  7053 V BluetoothSapService: Close listen Socket : 
08-15 16:22:27.362  7053  7053 V BluetoothSapService: Close rfcomm Socket : 
08-15 16:22:27.362  7053  7053 V BluetoothSapService: Close sapd  Socket : 
08-15 16:22:27.366  7053  7053 V BluetoothSapService: Sap Service closeSapService out
08-15 16:22:27.366  7053  7053 V BluetoothSapService: Sap Service onDestroy
08-15 16:22:27.366  7053  7053 V BluetoothSapService: Sap Service closeSapService in
08-15 16:22:27.366  7053  7053 V BluetoothSapService: Close listen Socket : 
08-15 16:22:27.366  7053  7053 V BluetoothSapService: Close rfcomm Socket : 
08-15 16:22:27.366  7053  7053 V BluetoothSapService: Close sapd  Socket : 
08-15 16:22:27.366  7053  7053 V BluetoothSapService: Sap Service closeSapService out
,08-15 16:22:28.097  7053  7523 D bt_hci_bdroid: cleanup
,08-15 16:22:28.104  7053  7590 I bt_lpm  : LPM is already off!!!
08-15 16:22:28.105  7053  7617 I bt_userial_mct: exiting userial_read_thread
08-15 16:22:28.105  7053  7617 D bt_userial_mct: Leaving userial_evt_read_thread()
08-15 16:22:28.106  7053  7588 W bt-btif : ag scb idx 1 not allocated
08-15 16:22:28.106  7053  7588 E bt-btif : BTA AG is already disabled, ignoring ...
08-15 16:22:28.106  7053  7588 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-15 16:22:28.106  7053  7588 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-15 16:22:28.106  7053  7588 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-15 16:22:28.106  7053  7588 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-15 16:22:28.106  7053  7588 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-15 16:22:28.106  7053  7588 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-15 16:22:28.106  7053  7588 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-15 16:22:28.107  7053  7588 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-15 16:22:28.107  7053  7588 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-15 16:22:28.107  7053  7588 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-15 16:22:28.107  7053  7588 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-15 16:22:28.107  7053  7588 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-15 16:22:28.107  7053  7588 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-15 16:22:28.107  7053  7588 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-15 16:22:28.107  7053  7588 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-15 16:22:28.107  7053  7588 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-15 16:22:28.107  7053  7588 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-15 16:22:28.107  7053  7588 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-15 16:22:28.107  7053  7588 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-15 16:22:28.110  7053  7523 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-15 16:22:28.110  7053  7590 I bt_vendor: hw_epilog_process
08-15 16:22:28.110  7053  7523 D bt_hci_bdroid: cleanup Finalizing cleanup
08-15 16:22:28.110  7053  7523 D bt_userial_mct: userial_close
08-15 16:22:28.110  7053  7523 E bt_userial_mct: pthread_join() FAILED result:3
08-15 16:22:28.110  7053  7523 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-15 16:22:28.119  7053  7523 D bt_hci_bdroid: set_power 0
08-15 16:22:28.119  7053  7523 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-15 16:22:28.119  7053  7523 I bt_vendor: bluetooth satus is on
08-15 16:22:28.119  7053  7523 I bt_vendor: bt-vendor : resetting BT status
08-15 16:22:28.119  7053  7523 I bt_vendor: Starting hciattach daemon
08-15 16:22:28.119  7053  7523 I bt_vendor: try to set false
,08-15 16:22:28.125  7053  7523 I bt_vendor: Starting hciattach daemon
08-15 16:22:28.125  7053  7523 I bt_vendor: try to set false
08-15 16:22:28.127  7053  7523 I bt_vendor: cleanup
08-15 16:22:28.128  7053  7588 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-15 16:22:28.128  7053  7523 I GKI_LINUX: GKI_exit_task 0 done
08-15 16:22:28.128  7053  7523 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-15 16:22:28.130  7053  7519 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-15 16:22:28.134  7053  7053 D HeadsetService: Received stop request...Stopping profile...
,08-15 16:22:28.137  7053  7053 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-15 16:22:28.137  7053  7053 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-15 16:22:28.137  7053  7053 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8c1d179
08-15 16:22:28.143  1853  1853 D BluetoothHeadset: Proxy object disconnected
08-15 16:22:28.143  1036  1036 D BluetoothHeadset: Proxy object disconnected
08-15 16:22:28.143  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-15 16:22:28.144  7053  7550 D HeadsetStateMachine: Exit Disconnected: -1
08-15 16:22:28.145  1853  1853 D BluetoothHeadset: Proxy object disconnected
08-15 16:22:28.148  1853  1853 D BluetoothHeadset: Proxy object disconnected
,08-15 16:22:28.150  7053  7053 D A2dpService: Received stop request...Stopping profile...
08-15 16:22:28.152  7053  7580 D A2dpStateMachine: Exit Disconnected: -1
08-15 16:22:28.153  7053  7519 D BluetoothAdapterState: Stopping profile services that were post enabled
08-15 16:22:28.154  7053  7053 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-15 16:22:28.155  7053  7053 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-15 16:22:28.155  7053  7053 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-15 16:22:28.155  7053  7053 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8c1d179
08-15 16:22:28.157  1036  1036 D BluetoothA2dp: Proxy object disconnected
08-15 16:22:28.157  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-15 16:22:28.158  7053  7053 D HidService: Received stop request...Stopping profile...
08-15 16:22:28.158  7053  7053 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8c1d179
08-15 16:22:28.160  7053  7053 D HeadsetStateMachine: Unbinding service...
,08-15 16:22:28.163  7053  7053 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-15 16:22:28.164  7053  7053 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-15 16:22:28.164  7053  7053 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-15 16:22:28.164  7053  7053 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-15 16:22:28.164  7053  7053 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-15 16:22:28.164  7053  7053 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-15 16:22:28.164  7053  7053 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-15 16:22:28.166  7053  7053 D HealthService: Received stop request...Stopping profile...
08-15 16:22:28.166  7053  7053 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8c1d179
08-15 16:22:28.168  7053  7053 D PanService: Received stop request...Stopping profile...
08-15 16:22:28.169  7053  7053 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8c1d179
08-15 16:22:28.170  7053  7053 D BtGatt.DebugUtils: handleDebugAction() action=null
08-15 16:22:28.170  7053  7053 D BtGatt.GattService: Received stop request...Stopping profile...
08-15 16:22:28.171  7053  7053 D BtGatt.GattService: stop()
08-15 16:22:28.171  7053  7053 D BtGatt.AdvertiseManager: advertise clients cleared
08-15 16:22:28.172  7053  7053 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8c1d179
,08-15 16:22:28.175  7053  7053 D BluetoothMapService: Received stop request...Stopping profile...
08-15 16:22:28.175  7053  7053 D BluetoothMapService: stop()
08-15 16:22:28.177  7053  7053 D BluetoothMapEmailAppObserver: deinitObservers()
08-15 16:22:28.177  7053  7053 D BluetoothMapEmailAppObserver: removeReceiver()
08-15 16:22:28.178  7053  7053 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8c1d179
08-15 16:22:28.179  7053  7053 I BluetoothA2dpServiceJni: cleanupNative
08-15 16:22:28.179  7053  7581 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-15 16:22:28.179  7053  7053 I GKI_LINUX: GKI_exit_task 2 done
08-15 16:22:28.179  7053  7053 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-15 16:22:28.180  7053  7053 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-15 16:22:28.180  7053  7053 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-15 16:22:28.180  7053  7053 V BluetoothMapService: Handler(): got msg=4
08-15 16:22:28.180  7053  7053 D BluetoothMapService: MAP Service closeService in
08-15 16:22:28.180  7053  7053 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-15 16:22:28.180  7053  7053 V BluetoothMapService: MAP Service closeService out
08-15 16:22:28.181  7053  7519 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-15 16:22:28.181  7053  7519 D BluetoothAdapterProperties: Setting state to 10
08-15 16:22:28.181  7053  7519 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-15 16:22:28.182  1036  1118 D BluetoothManagerService: Message: 60
08-15 16:22:28.182  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-15 16:22:28.183  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-15 16:22:28.183  7053  7053 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-15 16:22:28.186  7053  7053 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-15 16:22:28.186  7053  7053 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-15 16:22:28.187  7053  7519 I BluetoothAdapterState: Entering OffState
08-15 16:22:28.188  6929  6945 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-15 16:22:28.190  7053  7053 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-15 16:22:28.190  7053  7053 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-15 16:22:28.191  7053  7053 D BluetoothMapService: cleanup()
08-15 16:22:28.191  7053  7053 D BluetoothMapService: MAP Service closeService in
08-15 16:22:28.191  7053  7053 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-15 16:22:28.191  7053  7053 V BluetoothMapService: MAP Service closeService out
08-15 16:22:28.192  6929  6945 D BluetoothHeadset: onBluetoothStateChange: up=false
08-15 16:22:28.193  6929  6945 D BluetoothA2dp: onBluetoothStateChange: up=false
08-15 16:22:28.196  6929  6945 D BluetoothPbap: onBluetoothStateChange: up=false
,08-15 16:22:28.199  1036  1118 D BluetoothHeadset: onBluetoothStateChange: up=false
08-15 16:22:28.200  1853  1868 D BluetoothHeadset: onBluetoothStateChange: up=false
08-15 16:22:28.201  1853  1869 D BluetoothHeadset: onBluetoothStateChange: up=false
08-15 16:22:28.201  6929  6945 D BluetoothMap: onBluetoothStateChange: up=false
08-15 16:22:28.202  1036  1118 D BluetoothA2dp: onBluetoothStateChange: up=false
08-15 16:22:28.202  1853  4421 D BluetoothHeadset: onBluetoothStateChange: up=false
08-15 16:22:28.202  6929  6945 D BluetoothPan: onBluetoothStateChange on: false
08-15 16:22:28.203  1036  1118 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-15 16:22:28.203  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-15 16:22:28.206  1036  1118 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-15 16:22:28.206  1036  1118 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-15 16:22:28.206  1036  1118 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@3cd06b72 mBinding = false
08-15 16:22:28.207  1036  1118 D BluetoothManagerService: Sending unbind request.
,08-15 16:22:28.214  7053  7523 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-15 16:22:28.215  7053  7053 I GKI_LINUX: GKI_exit_task 1 done
08-15 16:22:28.216  7053  7053 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-15 16:22:28.216  7053  7053 I BluetoothServiceJni: cleanupNative: return from cleanup
08-15 16:22:28.216  7053  7053 I art     : --- WEIRD: removing null entry 248
08-15 16:22:28.216  7053  7053 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-15 16:22:28.216  7053  7053 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-15 16:22:28.217  7053  7053 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-15 16:22:28.219  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
,08-15 16:22:28.222  7053  7053 I art     : System.exit called, status: 0
08-15 16:22:28.222  7053  7053 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-15 16:22:28.241   319  3971 V AudioFlinger: 7053 died, releasing its sessions
08-15 16:22:28.241   319  3971 V AudioFlinger:  pid 1853 @ 0
08-15 16:22:28.241   319  3971 V AudioFlinger:  pid 3420 @ 1
08-15 16:22:28.241   319  3971 V AudioFlinger:  pid 3420 @ 2
,08-15 16:22:28.244  1942  1942 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
08-15 16:22:28.245  1942  2100 D LGBluetoothAPIService: Message: 101
08-15 16:22:28.245  1942  2100 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
08-15 16:22:28.245  1942  2100 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
08-15 16:22:28.245  1942  2100 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
08-15 16:22:28.247  6929  6929 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-15 16:22:28.288  1036  2025 I ActivityManager: Process com.android.bluetooth (pid 7053) has died
08-15 16:22:28.289  1036  2025 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 1000ms
08-15 16:22:28.289  1036  2025 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 11000ms
,08-15 16:22:28.298  1606  1606 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-15 16:22:28.300  6826  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 16:22:28.301  6826  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 16:22:28.303  6929  6929 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
,08-15 16:22:28.303  6929  6929 D LGBluetoothEventManager: [BTUI] clear device connection state
08-15 16:22:28.306  1942  1942 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-15 16:22:28.306  6929  6929 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-15 16:22:28.308  1942  2100 D LGBluetoothAPIService: Message: 2
08-15 16:22:28.308  1942  2100 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
,08-15 16:22:28.310  1606  1606 D BluetoothAdapter: 963613144: getState() :  mService = null. Returning STATE_OFF
08-15 16:22:28.311  1606  1606 D BluetoothAdapter: 963613144: getState() :  mService = null. Returning STATE_OFF
08-15 16:22:28.364  1036  1901 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7724 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-15 16:22:28.366  6929  6929 D DockEventReceiver: finishStartingService: stopping service
,08-15 16:22:28.452  7724  7724 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-15 16:22:28.452  7724  7724 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-15 16:22:28.453  7724  7724 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-15 16:22:28.453  7724  7724 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-15 16:22:28.475  7724  7724 D BluetoothAdapterApp: Loading JNI Library
,08-15 16:22:28.512  7724  7724 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@2669fb41 Instance Count = 1
,08-15 16:22:28.519  7724  7724 D BluetoothAdapterApp: onCreate
08-15 16:22:28.549  7724  7724 D ProfileConfigQcom: [BTUI] HeadsetService is supported
,08-15 16:22:28.550  7724  7724 D ProfileConfigQcom: Adding HeadsetService
08-15 16:22:28.550  7724  7724 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-15 16:22:28.551  7724  7724 D ProfileConfigQcom: Adding A2dpService
08-15 16:22:28.551  7724  7724 D ProfileConfigQcom: [BTUI] HidService is supported
08-15 16:22:28.553  7724  7724 D ProfileConfigQcom: Adding HidService
08-15 16:22:28.554  7724  7724 D ProfileConfigQcom: [BTUI] HealthService is supported
08-15 16:22:28.555  7724  7724 D ProfileConfigQcom: Adding HealthService
08-15 16:22:28.555  7724  7724 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-15 16:22:28.558  7724  7724 D ProfileConfigQcom: [BTUI] PanService is supported
08-15 16:22:28.558  7724  7724 D ProfileConfigQcom: Adding PanService
08-15 16:22:28.559  7724  7724 D ProfileConfigQcom: [BTUI] GattService is supported
08-15 16:22:28.559  7724  7724 D ProfileConfigQcom: Adding GattService
08-15 16:22:28.559  7724  7724 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-15 16:22:28.559  7724  7724 D ProfileConfigQcom: Adding BluetoothMapService
08-15 16:22:28.560  7724  7724 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-15 16:22:28.561  7724  7724 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-15 16:22:28.562  7724  7724 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,08-15 16:22:28.563  7724  7724 V BluetoothPbapReceiver: ***********state = 10
08-15 16:22:28.565  7724  7724 V LGMDMManagerInternal: Create singleton instance
08-15 16:22:28.680  2131  2131 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-15 16:22:28.683  7724  7724 D LGBluetoothAPIServer: [BTUI] onCreate()
,08-15 16:22:28.683  7724  7724 D LGBluetoothAPIServer: [BTUI] onBind()
08-15 16:22:28.687  1942  1942 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-15 16:22:28.687  1942  2100 D LGBluetoothAPIService: Message: 100
08-15 16:22:28.687  1942  2100 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-15 16:22:28.693  6929  6929 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,08-15 16:22:28.698  6929  6929 D BluetoothPermissionRequest: onReceive
08-15 16:22:28.701  6929  6929 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-15 16:22:28.701  6929  6929 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-15 16:22:28.703  6929  6929 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-15 16:22:28.709  7724  7724 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,08-15 16:22:28.713  7724  7724 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-15 16:22:28.717  7724  7724 V BluetoothSapReceiver: [BTUI] checkServiceStart
,08-15 16:22:28.717  7724  7724 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-15 16:22:28.717  7724  7724 V BluetoothSapReceiver: SapReceiver onReceive 
08-15 16:22:28.719  7724  7724 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-15 16:22:28.719  7724  7724 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-15 16:22:28.722  6994  6994 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-15 16:22:30.223  6826  6887 D io.jxcore.node.ConnectivityMonitor: stop
,08-15 16:22:30.223  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-15 16:22:30.446  1606  1606 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-15 16:22:30.468  1036  1380 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-15 16:22:30.529  2034  2034 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-15 16:22:30.538  1036  1036 D administrator: Handling package changes for user 0
08-15 16:22:30.559  1036  1092 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7753 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-15 16:22:30.585  1606  1606 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
,08-15 16:22:30.587  1606  1606 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,08-15 16:22:30.648  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-15 16:22:30.657  7753  7753 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-15 16:22:30.687  1036  1036 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-15 16:22:30.687  1036  1036 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-15 16:22:30.719  7753  7753 D LgDataFeature: LgDataFeature() Constructor: none
08-15 16:22:30.719  7753  7753 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-15 16:22:30.740  1036  1091 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-15 16:22:30.745  1036  1091 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-15 16:22:30.752  2034  2034 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-15 16:22:30.753  2478  2478 V GmsNetworkLocationProvi: DISABLE
08-15 16:22:30.782  1036  1091 D LocationProviderProxy: applying state to connected service
,08-15 16:22:30.782  2478  2478 E GCoreFlp: Bound FusedProviderService with LocationManager
,08-15 16:22:30.804  7753  7798 I Babel   : MmsConfig: mnc/mcc: 0/0
08-15 16:22:30.805  7753  7798 I Babel   : MmsConfig.loadMmsSettings
08-15 16:22:30.811  7753  7798 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-15 16:22:30.811  7753  7798 I Babel   : MmsConfig.loadFromDatabase
,08-15 16:22:30.827  7753  7798 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-15 16:22:30.827  7753  7798 I Babel   : MmsConfig.loadFromResources
08-15 16:22:30.829  7753  7798 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-15 16:22:30.829  7753  7798 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-15 16:22:30.831  7753  7753 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-15 16:22:30.840  7753  7796 W AudioCapabilities: Unsupported mime audio/evrc
08-15 16:22:30.842  7753  7796 W AudioCapabilities: Unsupported mime audio/qcelp
08-15 16:22:30.844  7753  7796 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-15 16:22:30.846  1818  7799 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-15 16:22:30.846  1818  7799 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
08-15 16:22:30.851  7117  7117 I AppUp4:CustModeStarterReceiver: onReceive
,08-15 16:22:30.854  1818  4666 I Icing   : updateResources: need to parse e{com.google.android.gms}
08-15 16:22:30.856  7117  7117 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@227395c3
08-15 16:22:30.856  7117  7117 D AppUp4:CustFacade: isCustomizationCompleted : false
08-15 16:22:30.856  7117  7117 D AppUp4:CustFacade: isPhone : true
08-15 16:22:30.857  7117  7117 D AppUp4:CustModeStarterReceiver: begin check event
08-15 16:22:30.857  7117  7117 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-15 16:22:30.861  7753  7796 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
08-15 16:22:30.862  7753  7796 W AudioCapabilities: Unsupported mime audio/qcelp
08-15 16:22:30.863  7753  7796 W AudioCapabilities: Unsupported mime audio/evrc
08-15 16:22:30.879  7753  7796 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-15 16:22:30.883  1036  1597 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7802 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
08-15 16:22:30.884  7753  7796 W VideoCapabilities: Unsupported mime video/divx
08-15 16:22:30.890  7753  7796 W VideoCapabilities: Unsupported mime video/divx311
08-15 16:22:30.893  1036  1939 I ActivityManager: Killing 6721:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
08-15 16:22:30.893  7753  7796 W VideoCapabilities: Unsupported mime video/divx4
,08-15 16:22:30.902  7753  7796 W VideoCapabilities: Unsupported mime video/mp4v-esdp
08-15 16:22:30.907  6977  6977 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-15 16:22:30.909  6977  6977 W System.err: android.os.DeadObjectException
08-15 16:22:30.909  6977  6977 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-15 16:22:30.909  6977  6977 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
,08-15 16:22:30.909  6977  6977 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-15 16:22:30.909  6977  6977 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
,08-15 16:22:30.909  6977  6977 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-15 16:22:30.909  6977  6977 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-15 16:22:30.909  6977  6977 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-15 16:22:30.909  6977  6977 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-15 16:22:30.909  6977  6977 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-15 16:22:30.909  6977  6977 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-15 16:22:30.909  6977  6977 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-15 16:22:30.909  6977  6977 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-15 16:22:30.909  6977  6977 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-15 16:22:30.909  6977  6977 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-15 16:22:30.910  6977  6977 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-15 16:22:30.910  6977  6977 W System.err: android.os.DeadObjectException
08-15 16:22:30.910  6977  6977 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-15 16:22:30.910  6977  6977 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-15 16:22:30.911  6977  6977 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-15 16:22:30.911  6977  6977 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-15 16:22:30.911  6977  6977 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-15 16:22:30.911  6977  6977 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-15 16:22:30.911  6977  6977 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-15 16:22:30.911  6977  6977 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-15 16:22:30.911  6977  6977 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-15 16:22:30.911  6977  6977 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-15 16:22:30.911  6977  6977 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-15 16:22:30.911  6977  6977 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-15 16:22:30.911  6977  6977 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-15 16:22:30.911  6977  6977 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-15 16:22:30.911  6977  6977 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-15 16:22:30.911  6977  6977 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,08-15 16:22:30.917  7753  7796 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
08-15 16:22:30.920  7753  7796 W AudioCapabilities: Unsupported mime audio/eac3
08-15 16:22:30.921  7753  7796 W AudioCapabilities: Unsupported mime audio/ac3
08-15 16:22:30.921  7753  7796 W AudioCapabilities: Unsupported mime audio/g726
08-15 16:22:30.926  7753  7796 W AudioCapabilities: Unsupported mime audio/wma-voice
,08-15 16:22:30.926  7753  7796 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,08-15 16:22:30.927  7753  7796 W AudioCapabilities: Unsupported mime audio/adpcm
08-15 16:22:30.929  7753  7796 W VideoCapabilities: Unsupported mime video/theora
08-15 16:22:30.930  7753  7796 W VideoCapabilities: Unsupported mime video/mjpg
08-15 16:22:31.103  1036  1939 E libprocessgroup: failed to kill 1 processes for processgroup 6721
,08-15 16:22:31.310  1036  2046 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
08-15 16:22:31.314  6977  6977 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-15 16:22:31.314  6977  6977 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-15 16:22:31.354  1036  1550 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7828 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-15 16:22:31.354  6977  6977 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-15 16:22:31.404  7802  7802 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-15 16:22:31.405  7802  7802 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-15 16:22:31.408  7802  7802 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-15 16:22:31.409  7802  7802 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-15 16:22:31.410  7802  7802 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,08-15 16:22:31.425  7828  7828 D UEI.SmartControl: Quickset Services start...
08-15 16:22:31.427  7828  7828 I UEI.SmartControl: Manufacture = LGE
08-15 16:22:31.427  7828  7828 D UEI.SmartControl: Id = LGNevo
08-15 16:22:31.427  7828  7828 D UEI.SmartControl: File observer start...
,08-15 16:22:31.429  7828  7828 E UEI.SmartControl: IR Port is disabled: false
08-15 16:22:31.429  7828  7828 D UEI.SmartControl: Starting file observer...
08-15 16:22:31.429  7828  7828 D UEI.SmartControl: Extracting JNI libs...
08-15 16:22:31.429  7828  7828 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-15 16:22:31.500  7828  7828 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-15 16:22:31.500  7828  7828 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-15 16:22:31.500  7828  7828 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-15 16:22:31.505  7802  7802 I SystemConfig: BUILD Country: EU
08-15 16:22:31.505  7802  7802 I SystemConfig: BUILD Operator: OPEN
08-15 16:22:31.532  7828  7828 I UEI.SmartControl: --- Selecting new region: 6
,08-15 16:22:31.534  7828  7828 I UEI.SmartControl: Model = LG-D855
,08-15 16:22:31.536  7828  7828 D UEI.SmartControl: QS Service created
08-15 16:22:31.547  7828  7828 I UEI.SmartControl: Service initServices...
,08-15 16:22:31.552  7828  7828 D UEI.SmartControl: QS start get config
08-15 16:22:31.561  1036  1992 I ActivityManager: Killing 6977:com.lge.qremote/u0a112 (adj 15): empty #17
,08-15 16:22:31.600  7828  7828 D UEI.SmartControl: Loading JNI Libs...
,08-15 16:22:31.657  1036  2025 W libprocessgroup: failed to open /acct/uid_10112/pid_6977/cgroup.procs: No such file or directory
,08-15 16:22:31.736  1036  1992 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7861 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-15 16:22:31.745  7802  7857 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-15 16:22:31.746  7802  7857 I SystemConfig: existFile = false
08-15 16:22:31.746  7802  7857 I SystemConfig: canReadFile = false
08-15 16:22:31.746  7802  7857 I SystemConfig: systemFeature RCS result false
08-15 16:22:31.746  7802  7857 D SystemConfig: refreshRcsSupport() :false
,08-15 16:22:31.799  7861  7861 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-15 16:22:31.799  7861  7861 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-15 16:22:31.799  7861  7861 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-15 16:22:31.800  7861  7861 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-15 16:22:31.867  7861  7861 I AppConfig: Total System Memory = 2995761152
,08-15 16:22:31.873  7861  7861 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
08-15 16:22:31.944  1036  2046 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7880 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-15 16:22:31.945  1036  2046 I ActivityManager: Killing 7148:com.lge.email/u0a23 (adj 15): empty #17
,08-15 16:22:31.968   344   344 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 456us total 21.666ms
,08-15 16:22:32.000   344   344 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 453us total 30.289ms
,08-15 16:22:32.003  7828  7828 I UEI.SmartControl: Supports setup maps: true
08-15 16:22:32.008  7828  7828 D UEI.SmartControl: QS start statue = true Error code = 0
08-15 16:22:32.008  7828  7828 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-15 16:22:32.008  7828  7828 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-15 16:22:32.009  7828  7828 I UEI.SmartControl: ### init IR Blaster...
08-15 16:22:32.013  7828  7828 D serial_port: Configuring serial port
,08-15 16:22:32.018  7828  7828 E UEI.SmartControl: UEIBLaster setting for 616
,08-15 16:22:32.018  7828  7828 I UEI.SmartControl: Setting serial record hearder size = 2
08-15 16:22:32.018  7828  7828 I UEI.SmartControl: configuring settings for MAXQ616
08-15 16:22:32.018  7828  7828 I UEI.SmartControl: Get version...
08-15 16:22:32.023   344   344 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 561us total 21.691ms
08-15 16:22:32.034  7828  7897 D UEI.SmartControl: serial port data available: 21
,08-15 16:22:32.040  1036  2025 W libprocessgroup: failed to open /acct/uid_10023/pid_7148/cgroup.procs: No such file or directory
08-15 16:22:32.062  7828  7828 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-15 16:22:32.062  7828  7828 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-15 16:22:32.063  7828  7828 I UEI.SmartControl: QS saving settings...
,08-15 16:22:32.064  7828  7828 D UEI.SmartControl: IR Blaster version: 25672567
,08-15 16:22:32.080  7828  7897 D UEI.SmartControl: serial port data available: 4
,08-15 16:22:32.112  7828  7901 I UEI.SmartControl: Device manager: loading config....
08-15 16:22:32.113  7828  7828 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-15 16:22:32.113  7828  7901 D UEI.SmartControl: ----------- loading internal config...
08-15 16:22:32.117  7828  7828 E UEI.SmartControl: Services init done
08-15 16:22:32.117  7828  7828 D UEI.SmartControl: QS Service init finished
,08-15 16:22:32.119  7828  7828 D UEI.SmartControl: QS Service version name: 2.1.91
08-15 16:22:32.119  7828  7828 D UEI.SmartControl: QS Service version code: 201091
08-15 16:22:32.120  7828  7828 D UEI.SmartControl: Service requested: Control
08-15 16:22:32.129  7828  7901 E UEI.SmartControl: Loading SETTINGS...
,08-15 16:22:32.130  7828  7828 D UEI.SmartControl: Request IControl service: devices are loaded...
08-15 16:22:32.132  7828  7828 D UEI.SmartControl: Service.onUnbind: IControl
08-15 16:22:32.133  7828  7828 D UEI.SmartControl: Service.onDestroy
08-15 16:22:32.133  7828  7828 D UEI.SmartControl: Lock is in USE false
08-15 16:22:32.133  7828  7828 D UEI.SmartControl: unbind internal service
08-15 16:22:32.136  7828  7828 D serial_port: close(fd = 25)
08-15 16:22:32.141  7828  7828 I UEI.SmartControl: Serial port is closed.
08-15 16:22:32.141  7828  7828 I UEI.SmartControl: Serial port is closed.
08-15 16:22:32.141  7828  7828 D UEI.SmartControl: Blaster closed
08-15 16:22:32.141  7828  7828 D UEI.SmartControl: Shut down QS...
08-15 16:22:32.141  7828  7828 D UEI.SmartControl: Stopping QS lib
08-15 16:22:32.142  7828  7828 D UEI.SmartControl: QS lib stop result = true
08-15 16:22:32.142  7828  7828 D UEI.SmartControl: Stopped QS lib
08-15 16:22:32.143  7828  7828 D UEI.SmartControl: Stopped file observer...
08-15 16:22:32.143  7828  7828 D UEI.SmartControl: QS shutdown complete
08-15 16:22:32.144  7828  7828 D UEI.SmartControl: QS Service created
08-15 16:22:32.148  7828  7901 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-15 16:22:32.150  7828  7900 I UEI.SmartControl: Notify AllClients services are ready: 11
08-15 16:22:32.150  7828  7900 D UEI.SmartControl: -----service ready thread exits
,08-15 16:22:32.159  7828  7828 I UEI.SmartControl: Service initServices...
08-15 16:22:32.159  7828  7828 D UEI.SmartControl: QS start get config
08-15 16:22:32.218  7880  7880 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-15 16:22:32.257  1036  1378 V AlarmManager: ELAPSED_WAKEUP set : Alarm{1b064b42 type 2 when 208988 com.google.android.gms} when 208988
,08-15 16:22:32.264  7880  7880 D LgDataFeature: LgDataFeature() Constructor: none
08-15 16:22:32.264  7880  7880 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-15 16:22:32.294  7880  7880 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-15 16:22:32.330  7880  7880 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-15 16:22:32.331  7880  7880 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-15 16:22:32.340  7880  7880 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-15 16:22:32.340  7880  7880 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
08-15 16:22:32.354  1036  2025 I ActivityManager: Killing 7017:com.lge.formmanager/u0a26 (adj 15): empty #17
,08-15 16:22:32.421  7828  7828 I UEI.SmartControl: Supports setup maps: true
,08-15 16:22:32.424  7828  7828 D UEI.SmartControl: QS start statue = true Error code = 0
,08-15 16:22:32.424  7828  7828 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-15 16:22:32.424  7828  7828 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-15 16:22:32.424  7828  7828 I UEI.SmartControl: ### init IR Blaster...
08-15 16:22:32.427  7828  7828 D serial_port: Configuring serial port
,08-15 16:22:32.427  7828  7828 E UEI.SmartControl: UEIBLaster setting for 616
08-15 16:22:32.427  7828  7828 I UEI.SmartControl: Setting serial record hearder size = 2
08-15 16:22:32.427  7828  7828 I UEI.SmartControl: configuring settings for MAXQ616
08-15 16:22:32.427  7828  7828 I UEI.SmartControl: Get version...
08-15 16:22:32.442  7828  7923 D UEI.SmartControl: serial port data available: 21
08-15 16:22:32.444  1036  2014 W libprocessgroup: failed to open /acct/uid_10026/pid_7017/cgroup.procs: No such file or directory
,08-15 16:22:32.456  3486  3501 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,08-15 16:22:32.458  3486  3501 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@37f4d4f7 on behalf of 7880
08-15 16:22:32.461  4600  7924 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
08-15 16:22:32.469  7828  7828 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-15 16:22:32.470  7828  7828 I UEI.SmartControl: IR Blaster version: 256702256704300002
,08-15 16:22:32.470  7828  7828 I UEI.SmartControl: QS saving settings...
08-15 16:22:32.472  7828  7828 D UEI.SmartControl: IR Blaster version: 25672567
08-15 16:22:32.488  7828  7923 D UEI.SmartControl: serial port data available: 4
,08-15 16:22:32.516  7828  7828 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-15 16:22:32.529  7828  7930 I UEI.SmartControl: Device manager: loading config....
08-15 16:22:32.529  7828  7930 D UEI.SmartControl: ----------- loading internal config...
08-15 16:22:32.540  7828  7930 E UEI.SmartControl: Loading SETTINGS...
,08-15 16:22:32.545  7828  7930 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-15 16:22:32.550  1036  1051 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7932 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
08-15 16:22:32.553  7828  7828 E UEI.SmartControl: Services init done
08-15 16:22:32.553  7828  7828 D UEI.SmartControl: QS Service init finished
,08-15 16:22:32.554  7828  7828 D UEI.SmartControl: QS Service version name: 2.1.91
08-15 16:22:32.554  7828  7828 D UEI.SmartControl: QS Service version code: 201091
08-15 16:22:32.555  7828  7828 D UEI.SmartControl: Service requested: Control
08-15 16:22:32.559  1036  2014 I ActivityManager: Killing 6515:com.wsandroid.suite.lge/1000 (adj 15): empty #17
08-15 16:22:32.567  7828  7929 I UEI.SmartControl: Notify AllClients services are ready: 0
,08-15 16:22:32.567  7828  7929 D UEI.SmartControl: -----service ready thread exits
08-15 16:22:32.601  1036  1945 W libprocessgroup: failed to open /acct/uid_1000/pid_6515/cgroup.procs: No such file or directory
,08-15 16:22:32.606  7828  7828 E ActivityThread: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@3efcb1f that was originally bound here
08-15 16:22:32.606  7828  7828 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@3efcb1f that was originally bound here
08-15 16:22:32.606  7828  7828 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1167)
08-15 16:22:32.606  7828  7828 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1061)
08-15 16:22:32.606  7828  7828 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1839)
08-15 16:22:32.606  7828  7828 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1822)
08-15 16:22:32.606  7828  7828 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
08-15 16:22:32.606  7828  7828 E ActivityThread: 	at com.uei.control.Service.b(Unknown Source)
08-15 16:22:32.606  7828  7828 E ActivityThread: 	at com.uei.control.Service.a(Unknown Source)
08-15 16:22:32.606  7828  7828 E ActivityThread: 	at com.uei.control.Service.onCreate(Unknown Source)
08-15 16:22:32.606  7828  7828 E ActivityThread: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2738)
08-15 16:22:32.606  7828  7828 E ActivityThread: 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
08-15 16:22:32.606  7828  7828 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
08-15 16:22:32.606  7828  7828 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-15 16:22:32.606  7828  7828 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
08-15 16:22:32.606  7828  7828 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-15 16:22:32.606  7828  7828 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
08-15 16:22:32.606  7828  7828 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-15 16:22:32.606  7828  7828 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-15 16:22:32.606  7828  7828 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-15 16:22:32.619  7828  7828 D UEI.SmartControl: Internal service binding...
08-15 16:22:32.620  7880  7880 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-15 16:22:32.645  7880  7880 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-15 16:22:32.658  7932  7932 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-15 16:22:32.681  7932  7932 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-15 16:22:32.681  7932  7932 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-15 16:22:32.681  7932  7932 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-15 16:22:32.681  7932  7932 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-15 16:22:32.681  7932  7932 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-15 16:22:32.681  7932  7932 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,08-15 16:22:32.695   312  7953 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-15 16:22:32.697  1036  1116 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-15 16:22:32.711  1036  1918 I ActivityManager: Killing 7179:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,08-15 16:22:32.741  1036  1550 W libprocessgroup: failed to open /acct/uid_10046/pid_7179/cgroup.procs: No such file or directory
,08-15 16:22:32.942  1036  2046 V SIM_STK : Menu title from STK is T-Mobile
,08-15 16:22:32.977  4600  7924 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 516 ms] updated apps [took 515 ms] 
,08-15 16:22:33.134  7828  7903 D UEI.SmartControl: Internal timer expired: 2
,08-15 16:22:33.241  6826  6887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-15 16:22:33.248  6826  6887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@10dad21 added. We now have 6 listener(s)
,08-15 16:22:33.249  6826  6887 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-15 16:22:33.253  6826  6887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-15 16:22:33.253  6826  6887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2618f546 added. We now have 7 listener(s)
08-15 16:22:33.253  6826  6887 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-15 16:22:33.255  6826  6887 I System.out: IsBluetoothEnabled
08-15 16:22:33.260  1036  1597 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-15 16:22:33.260  1036  1597 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
,08-15 16:22:33.270  1036  1118 D BluetoothManagerService: Message: 2
,08-15 16:22:33.274  6826  6887 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 16:22:33.275  1036  1915 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-15 16:22:33.275  1036  1915 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-15 16:22:33.293  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-15 16:22:33.294  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-15 16:22:33.294  1036  1036 D Ulp_jni : JNI:system_update. Event-4
,08-15 16:22:33.297  1036  1118 D BluetoothManagerService: Message: 1
08-15 16:22:33.297  1036  1118 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
,08-15 16:22:33.327  1036  1118 D BluetoothManagerService: Message: 20
08-15 16:22:33.327  1036  1118 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@27914fbb:true
,08-15 16:22:33.332  7724  7724 D BluetoothAdapterState: make
08-15 16:22:33.336  7724  7724 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-15 16:22:33.337  7724  7724 I bluedroid-qcom: init
08-15 16:22:33.338  7724  7964 I BluetoothAdapterState: Entering OffState
08-15 16:22:33.338  7724  7724 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-15 16:22:33.338  7724  7724 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-15 16:22:33.338  7724  7724 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-15 16:22:33.338  7724  7724 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-15 16:22:33.339  7724  7724 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-15 16:22:33.340  7724  7724 I bluedroid-qcom: get_profile_interface socket
08-15 16:22:33.340  7724  7724 I bluedroid-qcom: get_profile_interface map_client
,08-15 16:22:33.345  7724  7968 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-15 16:22:33.337  7967  7967 W bdaddr_loader: type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-15 16:22:33.347  7967  7967 W bdaddr_loader: type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-15 16:22:33.353  7724  7968 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-15 16:22:33.361  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-15 16:22:33.361  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-15 16:22:33.361  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
,08-15 16:22:33.364  1036  1118 D BluetoothManagerService: Message: 40
08-15 16:22:33.364  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-15 16:22:33.365  7724  7741 I bluedroid-qcom: config_hci_snoop_log
08-15 16:22:33.366  7967  7967 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-15 16:22:33.366  7967  7967 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-15 16:22:33.366  7967  7967 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-15 16:22:33.367  1036  1118 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-15 16:22:33.368  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-15 16:22:33.368  7724  7968 D BluetoothAdapterProperties: Name is: G3
08-15 16:22:33.369  7967  7967 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-15 16:22:33.374  7967  7967 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-15 16:22:33.374  7967  7967 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
,08-15 16:22:33.381  7724  7964 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-15 16:22:33.381  7724  7964 D BluetoothAdapterProperties: Setting state to 11
08-15 16:22:33.382  7724  7964 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-15 16:22:33.383  7724  7964 I LGBluetoothServiceJni: classInitNative: succeeds
08-15 16:22:33.386  1036  1118 D BluetoothManagerService: Message: 60
08-15 16:22:33.387  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-15 16:22:33.387  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
,08-15 16:22:33.391  1942  1942 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-15 16:22:33.394  1606  1606 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-15 16:22:33.397  6826  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 16:22:33.401  6929  6929 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
,08-15 16:22:33.407  7724  7724 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-15 16:22:33.407  7724  7724 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-15 16:22:33.407  7724  7724 V BluetoothPbapReceiver: ***********state = 11
08-15 16:22:33.411  2131  2131 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-15 16:22:33.424  6929  6929 D BluetoothPermissionRequest: onReceive
,08-15 16:22:33.436  6929  6929 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-15 16:22:33.443  7724  7964 D BluetoothBondStateMachine: make
,08-15 16:22:33.444  7724  7724 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-15 16:22:33.447  7724  7724 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-15 16:22:33.447  7724  7724 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-15 16:22:33.447  7724  7724 V BluetoothSapReceiver: SapReceiver onReceive 
08-15 16:22:33.447  7724  7724 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-15 16:22:33.447  7724  7724 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-15 16:22:33.449  7724  7964 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4ef3ebe
08-15 16:22:33.449  7724  7964 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-15 16:22:33.449  7724  7964 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4ef3ebe
08-15 16:22:33.449  7724  7964 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-15 16:22:33.450  7724  7964 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-15 16:22:33.451  7724  7981 I BluetoothBondStateMachine: StableState(): Entering Off State
08-15 16:22:33.454  7724  7964 E BluetoothAdapterService: File transfer profiles supported!!
08-15 16:22:33.460  7724  7724 D HeadsetService: Received start request. Starting profile...
08-15 16:22:33.460  7724  7724 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
,08-15 16:22:33.460  7724  7724 D LGBluetoothHfpAdapter: Version 1.6
08-15 16:22:33.461  7724  7964 E BluetoothAdapterService: File transfer profiles supported!!
08-15 16:22:33.463  7724  7724 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-15 16:22:33.464  7724  7724 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-15 16:22:33.465  7724  7724 D HeadsetStateMachine: make
08-15 16:22:33.467  7724  7964 E BluetoothAdapterService: File transfer profiles supported!!
08-15 16:22:33.472  7724  7964 E BluetoothAdapterService: File transfer profiles supported!!
,08-15 16:22:33.478  7724  7964 E BluetoothAdapterService: File transfer profiles supported!!
08-15 16:22:33.483  7724  7964 E BluetoothAdapterService: File transfer profiles supported!!
08-15 16:22:33.488  7724  7964 E BluetoothAdapterService: File transfer profiles supported!!
,08-15 16:22:33.493  7724  7724 D LgDataFeature: LgDataFeature() Constructor: none
08-15 16:22:33.493  7724  7724 D LgDataFeature: LgDataFeature() Constructor Done, null
08-15 16:22:33.497  7724  7724 D HeadsetStateMachine: max_hf_connections = 1
08-15 16:22:33.497  7724  7724 I bluedroid-qcom: get_profile_interface handsfree
08-15 16:22:33.498  7724  7724 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-15 16:22:33.499   319   319 V AudioPolicyService: registerClient() client 0xb0410600, uid 1002
08-15 16:22:33.499   319  1548 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-15 16:22:33.499   319  1548 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-15 16:22:33.499   319  1548 V AudioPolicyManagerEx: getOutput() returns output 2
,08-15 16:22:33.500  7724  7724 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-15 16:22:33.501   319  1396 V AudioFlinger: registerClient() client 0xb5581610, pid 7724
08-15 16:22:33.501   319  1390 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-15 16:22:33.501   319  1390 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-15 16:22:33.501  3420  3435 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-15 16:22:33.501  3420  3435 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-15 16:22:33.501  1606  1628 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-15 16:22:33.501  1606  1628 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-15 16:22:33.501  1853  4421 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-15 16:22:33.501  1853  4421 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-15 16:22:33.502   319  1391 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-15 16:22:33.502   319  1391 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-15 16:22:33.502  7724  7740 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-15 16:22:33.502  7724  7740 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-15 16:22:33.502  7724  7740 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-15 16:22:33.502  7724  7740 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-15 16:22:33.502  1606  1625 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-15 16:22:33.502  1606  1625 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-15 16:22:33.502  7724  7724 V ToneGenerator: Create Track: 0xb4928080
08-15 16:22:33.502  7724  7724 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-15 16:22:33.502  7724  7724 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-15 16:22:33.502   319  3971 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-15 16:22:33.502   319  3971 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-15 16:22:33.502   319  3971 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-15 16:22:33.502   319  3971 V AudioPolicyManagerEx: getOutput() returns output 2
08-15 16:22:33.502  1036  1051 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-15 16:22:33.502  1036  1051 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-15 16:22:33.502  1036  1051 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-15 16:22:33.502  1036  1051 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-15 16:22:33.502   319   319 I AudioFlinger: isAudioPlaybackHookOn() false
08-15 16:22:33.502   319  1548 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-15 16:22:33.502   319  1548 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-15 16:22:33.502   319  1548 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-15 16:22:33.502   319  1548 V AudioPolicyManagerEx: getOutput() returns output 2
08-15 16:22:33.503  7724  7724 V AudioSystem: getLatency() output 2, latency 50
08-15 16:22:33.503  7724  7724 V AudioSystem: getFrameCount() output 2, frameCount 960
08-15 16:22:33.503  7724  7724 V AudioTrack: createTrack_l() output 2 afLatency 50
08-15 16:22:33.503   319  1396 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-15 16:22:33.503   319  1396 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-15 16:22:33.503   319  1396 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-15 16:22:33.503  3420  3436 V ,AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-15 16:22:33.503   319  1396 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-15 16:22:33.503  3420  3436 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-15 16:22:33.503   319  1396 V AudioFlinger: createTrack() lSessionId: 21
08-15 16:22:33.504  7724  7724 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-15 16:22:33.504   319  1396 V AudioFlinger: acquiring 21 from 7724, for 7724
08-15 16:22:33.504   319  1396 V AudioFlinger:  added new entry for 21
08-15 16:22:33.504  7724  7724 V ToneGenerator: ToneGenerator INIT OK, time: 210246
08-15 16:22:33.504  7724  7724 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4ef3ebe
08-15 16:22:33.504  1853  1869 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-15 16:22:33.504  1853  1869 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-15 16:22:33.505  7724  7986 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-15 16:22:33.505  7724  7986 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-15 16:22:33.506  7724  7986 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-15 16:22:33.506  7724  7964 V LGMDMManager: Create singleton instance
08-15 16:22:33.506  7724  7986 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-15 16:22:33.506   319  1395 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7724
08-15 16:22:33.506  7724  7724 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4ef3ebe
08-15 16:22:33.506   319  1395 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-15 16:22:33.506   319  1395 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-15 16:22:33.506   319  1395 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-15 16:22:33.506   319  1395 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-15 16:22:33.506   319  1395 V voice   : voice_set_parameters: exit with code(0)
08-15 16:22:33.506   319  1395 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-15 16:22:33.506   319  1395 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-15 16:22:33.507   319  1395 V msm8974_platform: platform_set_parameters: exit with code(0)
08-15 16:22:33.507   319  1395 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-15 16:22:33.507   319  1395 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-15 16:22:33.507   319  1395 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-15 16:22:33.507  7724  7986 V ToneGenerator: ToneGenerator destructor
08-15 16:22:33.507  7724  7986 V ToneGenerator: stopTone
08-15 16:22:33.507  7724  7986 V ToneGenerator: Delete Track: 0xb4928080
08-15 16:22:33.508  7724  7724 D A2dpService: Received start request. Starting profile...
08-15 16:22:33.509  7724  7724 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-15 16:22:33.510  7724  7724 V Avrcp   : make
08-15 16:22:33.510   319  1548 V AudioPolicyService: AudioCommandThread() adding release output 2
08-15 16:22:33.510   319  1548 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-15 16:22:33.510   319  1269 V AudioPolicyService: AudioCommandThread() waking up
08-15 16:22:33.510   319  1269 V AudioPolicyService: AudioCommandThread() processing release output 2
,08-15 16:22:33.510   319  1269 V AudioPolicyManager: releaseOutput() 2
08-15 16:22:33.510   319  1269 V AudioPolicyService: AudioCommandThread() going to sleep
08-15 16:22:33.510   319  1548 V AudioFlinger: PlaybackThread::Track destructor
08-15 16:22:33.510   319  1548 V AudioFlinger: removeClient_l() pid 7724, calling pid 319
08-15 16:22:33.510  7724  7724 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-15 16:22:33.510  7724  7724 I bluedroid-qcom: get_profile_interface avrcp
08-15 16:22:33.510  7724  7986 V AudioTrack: ~AudioTrack, releasing session id from 7724 on behalf of 7724
08-15 16:22:33.511  7724  7964 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-15 16:22:33.511   319  1396 V AudioFlinger: releasing 21 from 7724 for 7724
08-15 16:22:33.511   319  1396 V AudioFlinger:  decremented refcount to 0
08-15 16:22:33.511   319  1396 V AudioFlinger: purging stale effects
08-15 16:22:33.512  1036  1051 W Process : Unable to open /proc/7987/status
,08-15 16:22:33.517  7724  7724 V AudioManager: registerRemoteController: size of Media player list: 0
08-15 16:22:33.519  7724  7724 E AudioManager: No RCC entry present to update
08-15 16:22:33.519  7724  7724 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-15 16:22:33.522  7724  7724 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-15 16:22:33.523  7724  7724 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
,08-15 16:22:33.523  7724  7724 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-15 16:22:33.526  7724  7724 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-15 16:22:33.660  1036  2046 V SIM_STK : Menu title from STK is T-Mobile
08-15 16:22:33.660  1036  2046 V SIM_STK : Menu title from STK is T-Mobile
,08-15 16:22:33.734  1036  1051 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-15 16:22:33.743  7724  7724 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,08-15 16:22:33.747  7724  7724 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-15 16:22:33.748  7724  7724 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-15 16:22:33.748  7724  7724 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-15 16:22:33.748  7724  7724 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
,08-15 16:22:33.748  7724  7724 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-15 16:22:33.748  7724  7724 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-15 16:22:33.748  7724  7724 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
,08-15 16:22:33.748  7724  7724 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-15 16:22:33.748  7724  7724 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-15 16:22:33.748  7724  7724 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-15 16:22:33.749  7724  7724 I BluetoothA2dpServiceJni: classInitNative
,08-15 16:22:33.749  7724  7724 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-15 16:22:33.749  7724  7724 D A2dpStateMachine: make
08-15 16:22:33.752  7724  7724 I bluedroid-qcom: get_profile_interface a2dp
,08-15 16:22:33.752  7724  7992 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,08-15 16:22:33.755  7724  7724 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-15 16:22:33.755  7724  7724 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-15 16:22:33.756  7724  7724 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4ef3ebe
08-15 16:22:33.756  7724  7991 D A2dpStateMachine: Enter Disconnected: -2
08-15 16:22:33.756  7724  7724 I BluetoothHidServiceJni: classInitNative: succeeds
08-15 16:22:33.757  7724  7724 D HidService: Received start request. Starting profile...
08-15 16:22:33.757  7724  7724 I bluedroid-qcom: get_profile_interface hidhost
08-15 16:22:33.757  7724  7724 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4ef3ebe
08-15 16:22:33.758  7724  7724 I BluetoothHealthServiceJni: classInitNative: succeeds
08-15 16:22:33.759  7724  7724 D HealthService: Received start request. Starting profile...
08-15 16:22:33.762  7724  7724 I bluedroid-qcom: get_profile_interface health
08-15 16:22:33.762  7724  7724 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-15 16:22:33.762  7724  7724 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4ef3ebe
08-15 16:22:33.763  7724  7724 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-15 16:22:33.764  7724  7724 D PanService: Received start request. Starting profile...
08-15 16:22:33.765  7724  7724 D BluetoothPanServiceJni: initializeNative(L110): pan
08-15 16:22:33.765  7724  7724 I bluedroid-qcom: get_profile_interface pan
08-15 16:22:33.772  7724  7724 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-15 16:22:33.772  7724  7724 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4ef3ebe
08-15 16:22:33.773  7724  7724 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
,08-15 16:22:33.777  7724  7724 D BtGatt.DebugUtils: handleDebugAction() action=null
08-15 16:22:33.777  7724  7724 D BtGatt.GattService: Received start request. Starting profile...
08-15 16:22:33.777  7724  7724 D BtGatt.GattService: start()
08-15 16:22:33.777  7724  7724 I bluedroid-qcom: get_profile_interface gatt
08-15 16:22:33.778  7724  7724 D BtGatt.AdvertiseManager: advertise manager created
08-15 16:22:33.785  7724  7724 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4ef3ebe
,08-15 16:22:33.794  7724  7724 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4ef3ebe
08-15 16:22:33.796  7724  7724 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-15 16:22:33.799  7724  7724 V BluetoothMapService: BluetoothMapBinder()
08-15 16:22:33.801  7724  7724 D BluetoothMapService: Received start request. Starting profile...
08-15 16:22:33.801  7724  7724 D BluetoothMapService: start()
,08-15 16:22:33.811  7724  7724 D BluetoothMapEmailSettingsLoader: Found 0 applications
,08-15 16:22:33.811  7724  7724 D BluetoothMapEmailAppObserver: createReceiver()
,08-15 16:22:33.812  7724  7724 D BluetoothMapEmailAppObserver: initObservers()
08-15 16:22:33.812  7724  7724 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-15 16:22:33.822  7724  7724 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4ef3ebe
08-15 16:22:33.822  7724  7724 D HeadsetStateMachine: Proxy object connected
08-15 16:22:33.823  7724  7724 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-15 16:22:33.823  7724  7724 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
,08-15 16:22:33.827  7724  7986 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-15 16:22:33.828  7724  7986 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-15 16:22:33.829  7724  7986 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-15 16:22:33.834  7724  7724 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-15 16:22:33.841  7724  7724 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-15 16:22:33.847  7724  7724 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-15 16:22:33.853  7724  7724 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-15 16:22:33.858  7724  7724 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-15 16:22:33.859  7724  7724 V PanService: [BTUI] SIM Extra State :ABSENT
08-15 16:22:33.866  7724  7724 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-15 16:22:33.866  7724  7724 V BluetoothMapService: Handler(): got msg=1
08-15 16:22:33.867  7724  7964 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-15 16:22:33.868  7724  7964 I bluedroid-qcom: enable
08-15 16:22:33.869  7724  8003 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-15 16:22:33.869  7724  8003 I bt-btu  : btu_task pending for preload complete event
08-15 16:22:33.869  7724  7964 I bt_hci_bdroid: init
08-15 16:22:33.871  7724  7964 I bt_vendor: bt-vendor : init
,08-15 16:22:33.871  7724  7964 I bt_vendor: bt-vendor : get_bt_soc_type
08-15 16:22:33.871  7724  7964 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-15 16:22:33.871  7724  7964 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-15 16:22:33.871  7724  7964 D bt_userial_mct: userial_init
08-15 16:22:33.872  7724  7964 D bt_hci_bdroid: set_power 1
08-15 16:22:33.872  7724  7964 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-15 16:22:33.872  7724  7964 I bt_vendor: Starting hciattach daemon
08-15 16:22:33.872  7724  7964 I bt_vendor: try to set true
08-15 16:22:33.867  8006  8006 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-15 16:22:33.867  8006  8006 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-15 16:22:33.907  8007  8007 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-15 16:22:34.022  8013  8013 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-15 16:22:34.048  8014  8014 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-15 16:22:34.090  8016  8016 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-15 16:22:34.107  8020  8020 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-15 16:22:34.121  8021  8021 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-15 16:22:34.140  8022  8022 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-15 16:22:34.176  8024  8024 I libmdmdetect: ESOC framework not supported
08-15 16:22:34.176  8024  8024 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-15 16:22:34.185  8024  8024 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-15 16:22:34.185  8024  8024 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-15 16:22:34.185  8024  8024 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-15 16:22:34.185  8024  8024 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
,08-15 16:22:34.185  8024  8024 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-15 16:22:34.185  8024  8024 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-15 16:22:34.185  8024  8024 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-15 16:22:34.226  8024  8025 E QC-QMI  : qmi_client [8024] 15: failed to locate client data
08-15 16:22:34.227   453   453 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-15 16:22:34.227   453   453 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,08-15 16:22:34.286  8029  8029 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-15 16:22:34.302  8030  8030 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-15 16:22:34.324  7724  7964 I bt_vendor: bluetooth satus is on
08-15 16:22:34.324  7724  7964 D bt_hci_bdroid: preload
,08-15 16:22:34.327  7724  8005 D bt_userial_mct: userial_open(port:0)
08-15 16:22:34.327  7724  8005 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-15 16:22:34.332  7724  8005 I bt_vendor: Done intiailizing UART
08-15 16:22:34.333  7724  8005 I bt_vendor: Done intiailizing UART
08-15 16:22:34.333  7724  8005 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-15 16:22:34.333  7724  8005 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-15 16:22:34.333  7724  8003 I bt-btu  : btu_task received preload complete event
08-15 16:22:34.334  7724  8003 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-15 16:22:34.334  7724  8003 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-15 16:22:34.336  7724  8003 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-15 16:22:34.339  7724  8032 D bt_userial_mct: Entering userial_read_thread()
,08-15 16:22:34.345  7724  8003 I         : BTE_InitTraceLevels -- TRC_HCI
,08-15 16:22:34.345  7724  8003 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-15 16:22:34.345  7724  8003 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-15 16:22:34.345  7724  8003 I         : BTE_InitTraceLevels -- TRC_AVDT
08-15 16:22:34.345  7724  8003 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-15 16:22:34.345  7724  8003 I         : BTE_InitTraceLevels -- TRC_A2D
,08-15 16:22:34.345  7724  8003 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-15 16:22:34.345  7724  8003 I         : BTE_InitTraceLevels -- TRC_BTM
08-15 16:22:34.345  7724  8003 I         : BTE_InitTraceLevels -- TRC_HID_HOST
,08-15 16:22:34.345  7724  8003 I         : BTE_InitTraceLevels -- TRC_GAP
08-15 16:22:34.345  7724  8003 I         : BTE_InitTraceLevels -- TRC_PAN
08-15 16:22:34.345  7724  8003 I         : BTE_InitTraceLevels -- TRC_SDP
08-15 16:22:34.345  7724  8003 I         : BTE_InitTraceLevels -- TRC_GATT
08-15 16:22:34.345  7724  8003 I         : BTE_InitTraceLevels -- TRC_SMP
08-15 16:22:34.345  7724  8003 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-15 16:22:34.345  7724  8003 I         : BTE_InitTraceLevels -- TRC_BTIF
08-15 16:22:34.440  7724  8003 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-15 16:22:34.440  7724  8003 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa018e061 
08-15 16:22:34.440  7724  8003 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa018e061 
,08-15 16:22:34.479  7724  7968 E bt-btif : Calling BTA_HhEnable
08-15 16:22:34.479  7724  7968 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-15 16:22:34.480  7724  7968 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-15 16:22:34.482  7724  8003 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-15 16:22:34.482  7724  8003 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-15 16:22:34.482  7724  8003 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-15 16:22:34.484  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-15 16:22:34.484  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
08-15 16:22:34.485  7724  8003 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-15 16:22:34.485  7724  8003 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-15 16:22:34.485  7724  7968 D BluetoothAdapterProperties: Name is: G3
08-15 16:22:34.486  7724  7968 D BluetoothAdapterProperties: Scan Mode:20
08-15 16:22:34.487  7724  7968 D BluetoothAdapterProperties: Discoverable Timeout:120
08-15 16:22:34.487  7724  7968 D bt_hci_bdroid: postload
08-15 16:22:34.487  7724  8005 D bt_hci_bdroid: Used up Tx Cmd credits
08-15 16:22:34.488  7724  7968 D bte_conf: Device ID record 1 : primary
08-15 16:22:34.488  7724  7968 D bte_conf:   vendorId            = 00c4
08-15 16:22:34.488  7724  7968 D bte_conf:   vendorIdSource      = 0001
08-15 16:22:34.488  7724  7968 D bte_conf:   product             = 13a1
08-15 16:22:34.488  7724  7968 D bte_conf:   version             = 1000
08-15 16:22:34.489  7724  7968 D bte_conf:   clientExecutableURL = 
08-15 16:22:34.489  7724  7968 D bte_conf:   serviceDescription  = 
08-15 16:22:34.489  7724  7968 D bte_conf:   documentationURL    = 
08-15 16:22:34.489  7724  8003 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-15 16:22:34.490  7724  8005 D bt_hci_bdroid: Used up Tx Cmd credits
08-15 16:22:34.490  7724  7968 D bte_conf: bte_load_did_conf no section named DID2.
08-15 16:22:34.493  7724  8032 E bt_mct  : hci lib postload completed
,08-15 16:22:34.499  7724  7964 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-15 16:22:34.499  7724  7964 D BluetoothAdapterProperties: ScanMode =  20
08-15 16:22:34.499  7724  7964 D BluetoothAdapterProperties: State =  11
08-15 16:22:34.499  7724  7964 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-15 16:22:34.499  7724  7964 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-15 16:22:34.500  7724  7964 D BluetoothAdapterProperties: Setting state to 12
08-15 16:22:34.500  7724  7964 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-15 16:22:34.500  7724  7968 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-15 16:22:34.501  7724  7968 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-15 16:22:34.497  8034  8034 W sh      : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-15 16:22:34.497  8034  8034 W sh      : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-15 16:22:34.509  1036  1118 D BluetoothManagerService: Message: 60
08-15 16:22:34.509  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-15 16:22:34.509  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
,08-15 16:22:34.513  7724  8003 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-15 16:22:34.513  7724  8003 W bt-smp  : Plain text(LSB ~ MSB) = 16 82 52 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-15 16:22:34.513  7724  8003 W bt-smp  : Encrypted text(LSB ~ MSB) = 56 ba 48 3d 1a 76 9a 8c 1b 29 51 ca eb d9 2c 4f 
08-15 16:22:34.513  7724  8003 W bt-btm  : Stopping oneshot timer
08-15 16:22:34.535  7724  7964 I BluetoothAdapterState: Entering On State
,08-15 16:22:34.546  6826  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-15 16:22:34.546  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 16:22:34.546  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-15 16:22:34.546  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-15 16:22:34.546  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-15 16:22:34.546  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-15 16:22:34.546  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-15 16:22:34.546  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-15 16:22:34.549  6826  6826 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-15 16:22:34.565  7724  8003 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-15 16:22:34.565  7724  8003 W bt-smp  : Plain text(LSB ~ MSB) = cf 28 67 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-15 16:22:34.565  7724  8003 W bt-smp  : Encrypted text(LSB ~ MSB) = c5 8e c5 de 4e 4a c6 7d ea bb 99 bc a3 4e 39 9f 
,08-15 16:22:34.568  7724  8003 W bt-btm  : Stopping oneshot timer
08-15 16:22:34.583  7724  7968 D BluetoothAdapterProperties: Discoverable Timeout:120
08-15 16:22:34.584  7724  7968 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
,08-15 16:22:34.587  7724  8003 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-15 16:22:34.587  7724  8003 W bt-smp  : Plain text(LSB ~ MSB) = 4c 9f 6e 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-15 16:22:34.587  7724  8003 W bt-smp  : Encrypted text(LSB ~ MSB) = 56 e5 b1 1a 86 bc db 48 af 43 3a 4c e4 f4 8a b3 
08-15 16:22:34.587  7724  8003 W bt-btm  : Stopping oneshot timer
08-15 16:22:34.588  7724  7964 D LGBluetoothServiceAdapter: [BTUI] OnState
08-15 16:22:34.591  7724  7964 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-15 16:22:34.591  7724  7964 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-15 16:22:34.593  7724  7964 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-15 16:22:34.593  7724  7964 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-15 16:22:34.593  6929  6945 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-15 16:22:34.618  8039  8039 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,08-15 16:22:34.627  6929  6945 D BluetoothHeadset: onBluetoothStateChange: up=true
08-15 16:22:34.630  6929  7638 D BluetoothA2dp: onBluetoothStateChange: up=true
08-15 16:22:34.632  7724  8003 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-15 16:22:34.632  7724  8003 W bt-smp  : Plain text(LSB ~ MSB) = 46 81 6a 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-15 16:22:34.632  7724  8003 W bt-smp  : Encrypted text(LSB ~ MSB) = 2f 8a 36 93 c8 76 17 67 12 11 ee b5 25 44 43 a6 
08-15 16:22:34.632  7724  8003 W bt-btm  : Stopping oneshot timer
,08-15 16:22:34.636  6929  6945 D BluetoothPbap: onBluetoothStateChange: up=true
08-15 16:22:34.638  1036  1118 D BluetoothHeadset: onBluetoothStateChange: up=true
08-15 16:22:34.640  1036  1036 D BluetoothHeadset: Proxy object connected
08-15 16:22:34.641  1853  1868 D BluetoothHeadset: onBluetoothStateChange: up=true
08-15 16:22:34.646  1853  1853 D BluetoothHeadset: Proxy object connected
,08-15 16:22:34.651  7724  8003 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-15 16:22:34.652  7724  8003 W bt-smp  : Plain text(LSB ~ MSB) = ce 00 53 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-15 16:22:34.652  7724  8003 W bt-smp  : Encrypted text(LSB ~ MSB) = 7c bc e4 53 df b4 97 2d 99 bd df 1a c0 00 9b 90 
08-15 16:22:34.652  7724  8003 W bt-btm  : Stopping oneshot timer
08-15 16:22:34.654  1853  1869 D BluetoothHeadset: onBluetoothStateChange: up=true
08-15 16:22:34.658  6929  6929 D BluetoothInputDevice: Proxy object connected
08-15 16:22:34.658  6929  6929 D HidProfile: Bluetooth service connected
08-15 16:22:34.663  1853  1853 D BluetoothHeadset: Proxy object connected
,08-15 16:22:34.663  6929  7638 D BluetoothMap: onBluetoothStateChange: up=true
08-15 16:22:34.665  6929  6929 D BluetoothHeadset: Proxy object connected
08-15 16:22:34.665  6929  6929 D HeadsetProfile: Bluetooth service connected
08-15 16:22:34.666  1036  1118 D BluetoothA2dp: onBluetoothStateChange: up=true
08-15 16:22:34.667  1036  1036 D BluetoothA2dp: Proxy object connected
08-15 16:22:34.667  1853  4421 D BluetoothHeadset: onBluetoothStateChange: up=true
08-15 16:22:34.673  1853  1853 D BluetoothHeadset: Proxy object connected
08-15 16:22:34.673  6929  6944 D BluetoothPan: onBluetoothStateChange on: true
08-15 16:22:34.673  6929  6944 D BluetoothPan: onBluetoothStateChange call bindService
08-15 16:22:34.675  6929  6929 D BluetoothA2dp: Proxy object connected
,08-15 16:22:34.675  6929  6929 D A2dpProfile: Bluetooth service connected
08-15 16:22:34.683  6929  6929 D BluetoothMap: Proxy object connected
08-15 16:22:34.684  6929  6929 D MapProfile: Bluetooth service connected
08-15 16:22:34.684  6929  6929 D BluetoothMap: getConnectedDevices()
08-15 16:22:34.684  7724  8054 V BluetoothMapService: getConnectedDevices()
08-15 16:22:34.685  1036  1118 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-15 16:22:34.685  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-15 16:22:34.688  1942  1942 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-15 16:22:34.689  1942  2100 D LGBluetoothAPIService: Message: 1
08-15 16:22:34.689  1942  2100 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-15 16:22:34.689  1942  2100 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
08-15 16:22:34.689  1942  2100 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-15 16:22:34.689  1606  1606 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-15 16:22:34.690  6826  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 16:22:34.811  1036  1550 I art     : Explicit concurrent mark sweep GC freed 27212(1346KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 2.039ms total 133.392ms
,08-15 16:22:34.815  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-15 16:22:34.815  1036  1118 D BluetoothManagerService: Message: 40
08-15 16:22:34.815  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-15 16:22:34.817  6929  6929 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-15 16:22:34.820  6929  6929 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-15 16:22:34.821  7724  7724 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-15 16:22:34.821  7724  7724 D BluetoothMapService: STATE_ON
08-15 16:22:34.830  6929  6929 D BluetoothPan: BluetoothPAN Proxy object connected
08-15 16:22:34.830  6929  6929 D PanProfile: Bluetooth service connected
,08-15 16:22:34.835  6929  6929 D DockEventReceiver: finishStartingService: stopping service
08-15 16:22:34.855  7724  7724 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4ef3ebe
,08-15 16:22:34.856  7724  7724 V BluetoothPbapService: Pbap Service onCreate
08-15 16:22:34.856  7724  7724 V BluetoothPbapService: Starting PBAP service
08-15 16:22:34.857  7724  7724 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-15 16:22:34.857  7724  7724 V BluetoothPbapService: Pbap Service onBind
08-15 16:22:34.858  7724  7724 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-15 16:22:34.858  6929  6929 D BluetoothPbap: Proxy object connected
08-15 16:22:34.858  6929  6929 D PbapServerProfile: Bluetooth service connected
08-15 16:22:34.858  7724  7724 V BluetoothPbapService: state: 12
08-15 16:22:34.858  7724  7724 V BluetoothMapService: Handler(): got msg=1
08-15 16:22:34.859  7724  7724 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-15 16:22:34.859  7724  7724 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-15 16:22:34.859  7724  7724 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-15 16:22:34.859  7724  7724 V BluetoothPbapReceiver: ***********state = 12
08-15 16:22:34.860  7724  8061 D BluetoothMapMasInstance: MAS initSocket()
08-15 16:22:34.860  7724  8061 D BluetoothMapMasInstance:   masId = 00
08-15 16:22:34.860  7724  8061 D BluetoothMapMasInstance:   msgTypes = 0e
08-15 16:22:34.860  7724  8061 D BluetoothMapMasInstance:   masName = SMS/MMS
08-15 16:22:34.860  7724  8061 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-15 16:22:34.861  7724  7724 V BluetoothPbapService: Handler(): got msg=1
08-15 16:22:34.862  1036  1915 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-15 16:22:34.862  7724  7724 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-15 16:22:34.862  2131  2131 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-15 16:22:34.863  2131  2131 D c       : Getting all permits...
08-15 16:22:34.863  2131  2131 D a       : Opening database...
08-15 16:22:34.863  7724  8061 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-15 16:22:34.864  7724  8061 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=74 mFd=0
08-15 16:22:34.865  7724  8062 V BluetoothPbapService: Pbap Service initSocket
08-15 16:22:34.865  7724  8061 V BluetoothMapMasInstance: Succeed to create listening socket 
08-15 16:22:34.865  7724  8061 D BluetoothMapMasInstance: Accepting socket connection...
08-15 16:22:34.865  7724  7968 D BluetoothAdapterProperties: Scan Mode:21
08-15 16:22:34.865  7724  7968 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-15 16:22:34.866  1036  2014 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-15 16:22:34.867  6826  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 16:22:34.868  2131  2131 D a       : Opening database auth.proximity.permit_store...
,08-15 16:22:34.870  2131  2131 D a       : Closing database...
08-15 16:22:34.871  7724  8062 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-15 16:22:34.874  7724  8062 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=74
08-15 16:22:34.874  7724  8062 V BluetoothPbapService: Succeed to create listening socket 
08-15 16:22:34.874  7724  8062 V BluetoothPbapService: Accepting socket connection...
08-15 16:22:34.885  6929  6929 D BluetoothPermissionRequest: onReceive
,08-15 16:22:34.887  6929  6929 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-15 16:22:34.890  6929  6929 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-15 16:22:34.894  7724  7724 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-15 16:22:34.895  7724  7724 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-15 16:22:34.905  7724  7724 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-15 16:22:34.928  7724  7724 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-15 16:22:34.929  7724  7724 V BtOppService: onCreate
,08-15 16:22:34.933  7724  7724 V BluetoothOppNotification: send message
08-15 16:22:34.936  7724  7724 V BtOppService: Starting RfcommListener
08-15 16:22:34.941  7724  7724 D BluetoothOppPreference: Dumping Names:  
,08-15 16:22:34.941  7724  7724 D BluetoothOppPreference: {}
,08-15 16:22:34.941  7724  7724 D BluetoothOppPreference: Dumping Channels:  
08-15 16:22:34.941  7724  7724 D BluetoothOppPreference: {}
,08-15 16:22:34.943  7724  7724 V BtOppService: onStartCommand
08-15 16:22:34.947  7724  7724 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-15 16:22:34.947  7724  7724 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-15 16:22:34.947  7724  8068 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-15 16:22:34.950  7724  7724 V BluetoothOppNotification: new notify threadi!
08-15 16:22:34.952  7724  7724 V BluetoothOppNotification: send delay message
08-15 16:22:34.955  7724  7724 V BtOppService: start RfcommListener
08-15 16:22:34.955  7724  8068 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-15 16:22:34.956  7724  8065 V BtOppService: Deleted complete outbound shares, number =  0
08-15 16:22:34.956  7724  8069 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-15 16:22:34.958  7724  8068 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@20edfbda on behalf of 
08-15 16:22:34.958  7724  7724 V BtOppService: RfcommListener started
,08-15 16:22:34.959  7724  8070 V BtOppRfcommListener: Starting RFCOMM listener....
08-15 16:22:34.960  1036  1992 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-15 16:22:34.961  7724  8070 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-15 16:22:34.962  7724  8070 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
08-15 16:22:34.962  7724  8070 V BtOppRfcommListener: Started RFCOMM listener....
08-15 16:22:34.963  7724  8070 I BtOppRfcommListener: Accept thread started.
08-15 16:22:34.963  7724  8070 V BtOppRfcommListener: Accepting connection...
08-15 16:22:34.964  7724  8069 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2cacd80b on behalf of 
08-15 16:22:34.965  7724  8069 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-15 16:22:34.965  7724  8068 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-15 16:22:34.965  7724  8065 V BtOppService: Deleted complete inbound failed shares, number = 0
08-15 16:22:34.966  7724  8065 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-15 16:22:34.967  7724  8069 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-15 16:22:34.969  7724  8065 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@12ed86e8 on behalf of 
,08-15 16:22:34.972  7724  8069 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2dad5101 on behalf of 
08-15 16:22:34.973  7724  8069 V BluetoothOppNotification: outbound: succ-0  fail-0
08-15 16:22:34.977  7724  8069 V BluetoothOppNotification: outbound notification was removed.
08-15 16:22:34.978  7724  8069 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-15 16:22:34.979  7724  7724 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4ef3ebe
08-15 16:22:34.979  7724  7724 V BluetoothFtpService: Ftp Service onCreate
08-15 16:22:34.979  7724  7724 I BluetoothFtpService: Ftp Service onCreate
08-15 16:22:34.980  7724  7724 V BluetoothFtpService: Ftp Service onStartCommand
08-15 16:22:34.980  7724  7724 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-15 16:22:34.980  7724  7724 V BluetoothFtpService: Starting Listening on sockets
08-15 16:22:34.980  7724  7724 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-15 16:22:34.980  7724  7724 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-15 16:22:34.980  7724  7724 V BluetoothSapReceiver: SapReceiver onReceive 
08-15 16:22:34.981  7724  7724 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-15 16:22:34.981  7724  7724 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-15 16:22:34.981  7724  8069 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@174ee9e7 on behalf of 
08-15 16:22:34.981  7724  7724 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-15 16:22:34.982  7724  8069 V BluetoothOppNotification: inbound: succ-0  fail-0
08-15 16:22:34.983  7724  7724 V BtOppService: ContentObserver received notification
08-15 16:22:34.983  7724  7724 V BtOppService: ContentObserver received notification
08-15 16:22:34.983  7724  7724 V BluetoothFtpService: Handler(): got msg=1
,08-15 16:22:34.986  7724  7724 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-15 16:22:34.986  7724  7724 V BluetoothFtpService: Ftp Service initSocket
08-15 16:22:34.988  1036  1597 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-15 16:22:34.989  7724  8071 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-15 16:22:34.990  7724  8071 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-15 16:22:34.990  7724  8069 V BluetoothOppNotification: inbound notification was removed.
08-15 16:22:34.990  7724  7724 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-15 16:22:34.991  7724  8071 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@7882994 on behalf of 
08-15 16:22:34.991  7724  8069 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-15 16:22:34.992  7724  7724 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=81 mFd=79
08-15 16:22:34.993  7724  7724 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-15 16:22:34.993  7724  8071 V BluetoothOppNotification: update too frequent, put in queue
08-15 16:22:34.994  7724  8069 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2e1cfc3d on behalf of 
08-15 16:22:34.995  7724  8072 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-15 16:22:34.996  7724  8071 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
,08-15 16:22:35.018  7724  7724 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4ef3ebe
,08-15 16:22:35.019  7724  7724 V BluetoothSapService: Sap Service onCreate
,08-15 16:22:35.021  7724  7724 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-15 16:22:35.021  7724  7724 V BluetoothSapService: state: 12
08-15 16:22:35.021  7724  7724 V BluetoothSapService: Starting SAP server process
,08-15 16:22:35.023  7724  7724 V BluetoothSapService: SAP Service startRfcommListenerThread
08-15 16:22:35.017  8073  8073 W sapd    : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-15 16:22:35.017  8073  8073 W sapd    : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-15 16:22:35.026  7724  8074 V BluetoothSapService: Sap Service initRfcommSocket
08-15 16:22:35.026  1036  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-15 16:22:35.028  7724  8074 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-15 16:22:35.030  7724  8074 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=81
08-15 16:22:35.030  7724  8074 V BluetoothSapService: Succeed to create listening socket 
08-15 16:22:35.030  7724  8074 V BluetoothSapService: Accepting socket connection...
08-15 16:22:35.043  8073  8073 V BT_SAP  : Event pipe created
08-15 16:22:35.043  8073  8073 V BT_SAP  : create_server_socket qcom.sap.server
08-15 16:22:35.043  8073  8073 V BT_SAP  : created socket fd 6
,08-15 16:22:35.343  6826  6887 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:,
08-15 16:22:35.343  6826  6887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 16:22:35.343  6826  6887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-15 16:22:35.343  6826  6887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-15 16:22:35.343  6826  6887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-15 16:22:35.343  6826  6887 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-15 16:22:35.343  6826  6887 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-15 16:22:35.343  6826  6887 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-15 16:22:35.354  6826  6887 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-15 16:22:35.356  6826  6887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-15 16:22:35.356  6826  6887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d7ff307 added. We now have 8 listener(s)
08-15 16:22:35.356  6826  6887 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-15 16:22:35.359  1036  1901 D WifiServiceImplEx: setWifiEnabled: false pid=6826, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-15 16:22:35.359  1036  1901 D WifiService: setWifiEnabled: false pid=6826, uid=10118
08-15 16:22:35.359  1036  1901 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-15 16:22:35.366  6826  6887 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-15 16:22:35.370  1036  1918 D WifiServiceImplEx: setWifiEnabled: true pid=6826, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-15 16:22:35.371  1036  1918 D WifiService: setWifiEnabled: true pid=6826, uid=10118
08-15 16:22:35.371  1036  1918 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-15 16:22:35.391  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-15 16:22:35.392  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-15 16:22:35.392  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-15 16:22:35.393  1036  1422 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-15 16:22:35.393  1036  1422 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-15 16:22:35.396  1036  1422 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-15 16:22:35.396  1036  1422 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-15 16:22:35.396  1036  1422 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-15 16:22:35.396  1036  1422 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-15 16:22:35.396  1036  1422 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-15 16:22:35.396  1036  1422 E WifiHW  : unknown target_country: EU , set to default
08-15 16:22:35.396  1036  1422 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-15 16:22:35.396  1036  1422 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-15 16:22:35.396  1036  1422 I WifiUtil: gEnableBmps=1
08-15 16:22:35.966   312   894 D SoftapController: Softap fwReload - Ok
,08-15 16:22:35.985  1036  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-15 16:22:35.985  1036  1118 D Tethering: InitialState.processMessage what=4
,08-15 16:22:35.988  7724  7724 V BluetoothOppNotification: new notify threadi!
08-15 16:22:35.989  7724  7724 V BluetoothOppNotification: send delay message
08-15 16:22:36.000  1036  1422 E NetdConnector: NDC Command {83 softap fwreload wlan0 STA} took too long (599ms)
,08-15 16:22:36.011  1036  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-15 16:22:36.023   312   894 D CommandListener: Setting iface cfg
08-15 16:22:36.024   312   894 D CommandListener: Trying to bring down wlan0
08-15 16:22:36.024   312   894 D CommandListener: Clearing all IP addresses on wlan0
08-15 16:22:36.038  1036  1422 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,08-15 16:22:36.037  8095  8095 W wpa_supplicant: type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-15 16:22:36.047  8095  8095 W wpa_supplicant: type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-15 16:22:36.053  1036  1422 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-15 16:22:36.053  1036  1422 E WifiStateMachine: useWiFiOffloading() : false
08-15 16:22:36.053  1036  1422 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-15 16:22:36.071  7724  8094 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-15 16:22:36.079  6929  6929 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-15 16:22:36.079  6929  6929 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-15 16:22:36.079  6929  6929 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-15 16:22:36.079  6929  6929 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,08-15 16:22:36.088  1036  1422 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-15 16:22:36.089  1036  1422 D WifiMonitor: connecting to supplicant
08-15 16:22:36.091  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-15 16:22:36.092  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-15 16:22:36.097  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-15 16:22:36.099  8095  8095 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-15 16:22:36.103  7724  8094 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@26e21f39 on behalf of 
08-15 16:22:36.104  7724  8094 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-15 16:22:36.104  6929  6929 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-15 16:22:36.105  6826  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 16:22:36.106  6929  6929 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-15 16:22:36.106  6929  6929 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-15 16:22:36.106  6929  6929 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-15 16:22:36.106  6929  6929 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-15 16:22:36.106  6929  6929 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-15 16:22:36.107  6929  6929 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-15 16:22:36.110  6929  6929 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-15 16:22:36.110  7724  8094 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-15 16:22:36.110  6929  6929 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
,08-15 16:22:36.110  6929  6929 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-15 16:22:36.110  6929  6929 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-15 16:22:36.114  6929  6929 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-15 16:22:36.115  6929  6929 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-15 16:22:36.115  6929  6929 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-15 16:22:36.115  6929  6929 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-15 16:22:36.115  6929  6929 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-15 16:22:36.115  6929  6929 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-15 16:22:36.115  6929  6929 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-15 16:22:36.116  7724  8094 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@12e0d97e on behalf of 
08-15 16:22:36.117  7724  8094 V BluetoothOppNotification: outbound: succ-0  fail-0
08-15 16:22:36.121  7724  8094 V BluetoothOppNotification: outbound notification was removed.
08-15 16:22:36.121  7724  8094 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-15 16:22:36.123  7724  8094 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1752edf on behalf of 
08-15 16:22:36.123  7724  8094 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-15 16:22:36.125  7724  8094 V BluetoothOppNotification: inbound notification was removed.
08-15 16:22:36.125  7724  8094 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-15 16:22:36.126  7724  8094 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@32a7172c on behalf of 
08-15 16:22:36.129  8095  8095 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-15 16:22:36.130  8095  8095 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-15 16:22:36.163  1036  2025 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8113 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-15 16:22:36.207  8095  8095 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-15 16:22:36.241  8095  8095 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-15 16:22:36.249  1036  1422 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-15 16:22:36.249  1036  1422 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-15 16:22:36.250  1036  1422 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-15 16:22:36.250  8095  8095 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
,08-15 16:22:36.250  1036  1422 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-15 16:22:36.251  1036  1422 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-15 16:22:36.251  1036  1422 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-15 16:22:36.252  8095  8095 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-15 16:22:36.252  1036  1422 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-15 16:22:36.252  1036  8134 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-15 16:22:36.253  1036  8134 D WifiMonitor: Dropping event because (p2p0) is stopped
08-15 16:22:36.253  1036  1422 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-15 16:22:36.253  1036  8134 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-15 16:22:36.253  1036  8134 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-15 16:22:36.253  1036  1422 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-15 16:22:36.253  1036  1422 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-15 16:22:36.253  1036  8134 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-15 16:22:36.254  1036  8134 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-15 16:22:36.254  1036  8134 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-15 16:22:36.254  1036  8134 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-15 16:22:36.254  1036  1422 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-15 16:22:36.255  1036  1422 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-15 16:22:36.255  1036  1422 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-15 16:22:36.285  1036  1945 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8135 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-15 16:22:36.290  1036  1422 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-15 16:22:36.290  1036  1422 E WifiStateMachine: useWiFiOffloading() : false
08-15 16:22:36.290  1036  1422 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-15 16:22:36.291  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 16:22:36.291  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 16:22:36.291  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 16:22:36.291  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 16:22:36.291  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-15 16:22:36.293  1036  1422 D WifiNative-wlan0: doBoolean: SET update_config 1
08-15 16:22:36.294  1036  1422 D WifiNative-wlan0: SET update_config 1: returned true
08-15 16:22:36.294  1036  1422 D WifiConfigStore: Loading config and enabling all networks 
08-15 16:22:36.294  1036  1422 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-15 16:22:36.295  1036  1422 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-15 16:22:36.296  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-15 16:22:36.296  1942  1942 D WfdService: Waiting for WifiP2p enabling
08-15 16:22:36.298  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-15 16:22:36.299  1036  1442 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-15 16:22:36.302  6826  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-15 16:22:36.302  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 16:22:36.302  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-15 16:22:36.302  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-15 16:22:36.302  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-15 16:22:36.302  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-15 16:22:36.302  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-15 16:22:36.302  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-15 16:22:36.304  1036  1422 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-15 16:22:36.307  6826  6826 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-15 16:22:36.308  8113  8132 W FormManager: Network not available. Please check & try again.
08-15 16:22:36.315  1036  1422 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
,08-15 16:22:36.316  1036  1422 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-15 16:22:36.316  1036  1422 D WifiStateMachine: enableVerboseLogging : level 2
08-15 16:22:36.317  1036  1422 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-15 16:22:36.317  1036  1422 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-15 16:22:36.317  1036  1422 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-15 16:22:36.317  1036  1422 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-15 16:22:36.317  1036  1422 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-15 16:22:36.318  1036  1422 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-15 16:22:36.318  1036  1422 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-15 16:22:36.318  1036  1422 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-15 16:22:36.318  1036  1422 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-15 16:22:36.319  1036  1422 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-15 16:22:36.319  1036  1422 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-15 16:22:36.319  1036  1422 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-15 16:22:36.320  1036  1422 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-15 16:22:36.320  1036  1422 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-15 16:22:36.321  1036  1422 D WifiStateMachine: Setting OUI to DA-A1-19
08-15 16:22:36.321  1036  1422 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-15 16:22:36.321  1036  1422 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-15 16:22:36.322  1036  1422 D WifiNative-HAL: Setting external_sim to 1
08-15 16:22:36.322  1942  1942 D WfdsService: Supplicant Connection state is changed : true
08-15 16:22:36.322  1036  1422 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-15 16:22:36.322  1942  2262 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-15 16:22:36.322  1942  2262 D WfdsService: Set the WFDS Monitor: true
08-15 16:22:36.322  1942  2262 D WfdsMonitor: WfdsMonitorThread create
08-15 16:22:36.322  1942  2262 D WfdsMonitor: WFDS Monitor is created and started
08-15 16:22:36.322  1942  2262 D WfdsService: WiFi: Supplicant connection re-established
08-15 16:22:36.322  7753  7753 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 16:22:36.322  1036  1422 D WifiNative-wlan0: SET external_sim 1: returned true
08-15 16:22:36.322  1036  1422 I WifiNative-HAL: startHal
08-15 16:22:36.323  1036  1422 D wifi    : setting scan oui 0xaf52e780
08-15 16:22:36.323  1036  1422 D WifiStateMachine: Setting OUI to DA-A1-19
08-15 16:22:36.323  1036  1422 I WifiNative-HAL: startHal
08-15 16:22:36.323  1036  1422 D wifi    : setting scan oui 0xaf52e780
08-15 16:22:36.323  1036  1422 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-15 16:22:36.324  1942  8153 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-15 16:22:36.324  1036  1422 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-15 16:22:36.324  1036  1422 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-15 16:22:36.325  8095  8095 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-15 16:22:36.325  1942  8153 E CtrlSupplicant: Succeed to open control connection
08-15 16:22:36.325  1036  1422 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-15 16:22:36.325  1036  1422 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-15 16:22:36.325  8095  8095 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-15 16:22:36.326  1942  8153 E CtrlSupplicant: Succeed to open monitor connection
08-15 16:22:36.326  1036  1422 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-15 16:2,2:36.326  1036  1422 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-15 16:22:36.326  1942  8153 D WfdsMonitor: Supplicant connection established
08-15 16:22:36.326  8095  8095 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-15 16:22:36.326  1942  2262 D WfdsService: Connected to the supplicant for wfds
08-15 16:22:36.327  1036  1422 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-15 16:22:36.327  1036  1422 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-15 16:22:36.327  8095  8095 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-15 16:22:36.327  1036  1422 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-15 16:22:36.327  1036  1422 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-15 16:22:36.327  8095  8095 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-15 16:22:36.328  1036  1422 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-15 16:22:36.328  1036  1422 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-15 16:22:36.328  8095  8095 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-15 16:22:36.329  1036  1422 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
,08-15 16:22:36.329  1036  1422 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-15 16:22:36.329  8095  8095 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-15 16:22:36.330  1036  1422 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-15 16:22:36.331  1036  1422 E WifiNative: : [213,061,880 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-15 16:22:36.331  1036  1422 D WifiNative-wlan0: doBoolean: RECONNECT
08-15 16:22:36.332  1036  1422 D WifiNative-wlan0: RECONNECT: returned true
08-15 16:22:36.332  1036  1422 D WifiNative-wlan0: doString: [STATUS]
08-15 16:22:36.332  1036  8134 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-15 16:22:36.332  1036  8134 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-15 16:22:36.334  1036  1422 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-15 16:22:36.334  1036  1422 D WifiNative-wlan0: doBoolean: SET ps 1
08-15 16:22:36.335  1036  1422 D WifiNative-wlan0: SET ps 1: returned true
08-15 16:22:36.335  1036  1389 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-15 16:22:36.335  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 3
08-15 16:22:36.335  1036  1036 D RttService: SCAN_AVAILABLE : 3
08-15 16:22:36.336  1036  1557 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-15 16:22:36.336  1036  1557 I WifiNative-HAL: startHal
08-15 16:22:36.336  1036  1557 D wifi    : getting scan capabilities on interface[1] = 0xaf52e780
08-15 16:22:36.336  1036  1557 D wifi    : failed to get capabilities : -3
08-15 16:22:36.336  1036  1557 E WifiScanningService: could not get scan capabilities
08-15 16:22:36.336  1036  1558 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-15 16:22:36.336  1036  1422 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-15 16:22:36.336  1036  1422 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-15 16:22:36.337  1036  1422 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-15 16:22:36.337   312   894 D CommandListener: Setting iface cfg
08-15 16:22:36.337   312   894 D CommandListener: Trying to bring up p2p0
08-15 16:22:36.337  1036  1389 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-15 16:22:36.337  1036  1389 D LGWifiP2pService: P2pEnablingState
08-15 16:22:36.337  1036  1422 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-15 16:22:36.337  1036  1389 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-15 16:22:36.337  1036  1389 D LGWifiP2pService: P2p socket connection successful
08-15 16:22:36.337  1036  1389 D LGWifiP2pService: P2pEnabledState
08-15 16:22:36.338  1036  1389 D LGWifiP2pService: sending p2p connection changed broadcast
08-15 16:22:36.339  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-15 16:22:36.338  1036  1422 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=213069  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-15 16:22:36.339  1942  1942 D WfdsService: WifiP2pState is changed : true
08-15 16:22:36.339  1942  2262 D WfdsService: Receive the WFDS_ENABLE Method
08-15 16:22:36.339  1942  2262 D WfdsService: Set the WFDS Monitor: true
08-15 16:22:36.339  1942  2262 D WfdsService: Connected to the supplicant for wfds
08-15 16:22:36.339  1942  2262 D WfdsJNI : doCommand: WFDS_SET TRUE
08-15 16:22:36.339  1036  1389 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-15 16:22:36.339  8095  8095 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-1,5 16:22:36.340  1036  1389 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-15 16:22:36.340  1036  1389 D WifiNative-p2p0: doBoolean: SET device_name G3
08-15 16:22:36.340  1942  1942 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-15 16:22:36.341  1942  2262 D WfdsService: selectPreferredScanChannel [36]
08-15 16:22:36.341  1942  2262 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-15 16:22:36.341  1942  1942 D WfdsService: isConnected: false
08-15 16:22:36.341  1036  1389 D WifiNative-p2p0: SET device_name G3: returned true
08-15 16:22:36.341  1036  1389 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-15 16:22:36.341  1036  1389 D LGWifiP2pService: before postfix = G3
08-15 16:22:36.341  1036  1389 D WifiServerServiceExt: postfix byte check : 2
08-15 16:22:36.341  1036  1389 D LGWifiP2pService: after postfix = G3
08-15 16:22:36.341  1036  1389 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
,08-15 16:22:36.342  1036  1389 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
,08-15 16:22:36.342  1036  1389 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-15 16:22:36.342  1036  1422 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=213073  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-15 16:22:36.342  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-15 16:22:36.342  1606  1606 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-15 16:22:36.343  1036  1422 E WifiStateMachine:  DisconnectedState what:132106 1 0
,08-15 16:22:36.343  1036  1422 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-15 16:22:36.343  1036  1422 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-15 16:22:36.343  1036  1422 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-15 16:22:36.344  8095  8095 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-15 16:22:36.344  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-15 16:22:36.344  1036  1422 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-15 16:22:36.345  1036  1422 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-15 16:22:36.345  1036  1422 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-15 16:22:36.345  1036  1422 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-15 16:22:36.345  8095  8095 E wpa_supplicant: disconnect_rssi_lvl: -100
08-15 16:22:36.346  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 16:22:36.346  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 16:22:36.346  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-15 16:22:36.347  1036  1422 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-15 16:22:36.347  1036  1422 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-15 16:22:36.348  1036  1422 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-15 16:22:36.348  1036  1422 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-15 16:22:36.348  1036  1389 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-15 16:22:36.348  1036  1389 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-15 16:22:36.349  8095  8095 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-15 16:22:36.350  8095  8095 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-15 16:22:36.350  1036  8134 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-15 16:22:36.350  1036  8134 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-15 16:22:36.350  1036  8134 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-15 16:22:36.350  1036  8134 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-15 16:22:36.350  8095  8095 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-15 16:22:36.350  8095  8095 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-15 16:22:36.350  1036  1422 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-15 16:22:36.351  1036  1422 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-15 16:22:36.351  8095  8095 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-15 16:22:36.351  1036  1422 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-15 16:22:36.351  1942  8153 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-15 16:22:36.351  1942  8153 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-15 16:22:36.352  1036  1422 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-15 16:22:36.352  1036  1422 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-15 16:22:36.352  1036  8134 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-15 16:22:36.352  8095  8095 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-15 16:22:36.352  1036  8134 E WifiMonitor: WifiMonitor:p2p0 cnt=42 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-15 16:22:36.352  8095  8095 I wpa_supplicant: wlan0: CTR,L-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-15 16:22:36.352  1036  8134 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-15 16:22:36.352  1036  8134 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-15 16:22:36.352  1036  8134 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-15 16:22:36.352  1036  8134 E WifiMonitor: WifiMonitor:p2p0 cnt=43 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-15 16:22:36.352  1036  8134 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-15 16:22:36.352  1036  8134 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-15 16:22:36.352  1036  8134 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-15 16:22:36.352  8113  8133 V FormManager: Network unavailable.
08-15 16:22:36.352  1036  8134 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-15 16:22:36.352  1036  8134 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-15 16:22:36.352  1036  8134 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-15 16:22:36.353  1036  1422 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-15 16:22:36.353  1036  1422 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-15 16:22:36.353  1036  1422 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-15 16:22:36.353  1036  1422 D WifiNative-wlan0: doBoolean: SCAN
08-15 16:22:36.353  1036  1389 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-15 16:22:36.353  1036  1389 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-15 16:22:36.354  1036  1422 D WifiNative-wlan0: SCAN: returned false
08-15 16:22:36.354  1036  1389 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-15 16:22:36.354  1036  1389 D WifiNative-HAL: p2pGetDeviceAddress
08-15 16:22:36.354  1036  1422 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=213086  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-15 16:22:36.354  1036  1389 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-15 16:22:36.355  1036  1389 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-15 16:22:36.355  1036  1389 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-15 16:22:36.355  1036  1422 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=213087  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-15 16:22:36.356  1036  1422 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
,08-15 16:22:36.356  1036  1422 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-15 16:22:36.357  1036  1422 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-15 16:22:36.357  1036  1422 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-15 16:22:36.358  1036  1422 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-15 16:22:36.358  1942  1942 I WfdStateTracker: handleP2pThisDeviceChanged
08-15 16:22:36.358  1942  1942 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-15 16:22:36.358  1942  1942 D WfdsService: Update P2p Interface State: 3
08-15 16:22:36.359  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.,
08-15 16:22:36.359  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 16:22:36.359  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-15 16:22:36.359  1036  1389 D WifiNative-p2p0: P2P_FLUSH: returned true
08-15 16:22:36.359  1036  1389 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-15 16:22:36.359  1036  1389 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-15 16:22:36.359  1036  1389 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-15 16:22:36.360  1036  1389 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
,08-15 16:22:36.360  1036  1389 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-15 16:22:36.361  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-15 16:22:36.361  1036  1036 D WifiServerServiceExt: setSupplicantStateSCANNING
,08-15 16:22:36.362  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-15 16:22:36.362  1036  1036 D WifiServerServiceExt: setSupplicantStateSCANNING
08-15 16:22:36.364  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-15 16:22:36.364  1606  1606 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-15 16:22:36.365  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-15 16:22:36.367  8113  8133 V FormManager: Network unavailable.
08-15 16:22:36.369  1036  1389 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-15 16:22:36.369  1036  1389 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-15 16:22:36.369  1036  1389 D LGWifiP2pService: InactiveState
08-15 16:22:36.369  1036  1389 D LGWifiP2pService: InactiveState{ when=-19ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-15 16:22:36.369  1036  1389 D LGWifiP2pService: P2pEnabledState{ when=-19ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-15 16:22:36.369  1036  1389 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
,08-15 16:22:36.370  8095  8095 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-15 16:22:36.370  8095  8095 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-15 16:22:36.370  1036  8134 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-15 16:22:36.370  1942  8153 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-15 16:22:36.370  1036  8134 E WifiMonitor: WifiMonitor:p2p0 cnt=45 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-15 16:22:36.371  1036  8134 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-15 16:22:36.371  1036  8134 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-15 16:22:36.371  8095  8095 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-15 16:22:36.371  8095  8095 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-15 16:22:36.371  1942  8153 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-15 16:22:36.371  1036  1389 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-15 16:22:36.371  1036  1389 D LGWifiP2pService: InactiveState{ when=-12ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-15 16:22:36.371  1036  1389 D LGWifiP2pService: P2pEnabledState{ when=-12ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-15 16:22:36.371  8095  8095 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-15 16:22:36.371  1036  1389 D LGWifiP2pService: InactiveState{ when=-2ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-15 16:22:36.372  1036  1389 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-15 16:22:36.372  1942  8153 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-15 16:22:36.372  1036  1389 D LGWifiP2pService: DefaultState{ when=-2ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-15 16:22:36.372  1036  1389 D LGWifiP2pService: InactiveState{ when=-2ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-15 16:22:36.372  1036  1389 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-15 16:22:36.372  1036  1389 D LGWifiP2pService: DefaultState{ when=-3ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-15 16:22:36.372  1036  1389 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-15 16:22:36.372  1036  8134 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-15 16:22:36.372  1036  1389 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-15 16:22:36.372  1036  8134 E WifiMonitor: WifiMonitor:p2p0 cnt=46 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-15 16:22:36.372  1036  1389 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-15 16:22:36.372  1036  8134 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-15 16:22:36.372  1036  8134 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-15 16:22:36.372  1942  2262 W WfdsService: DefaultState - msg [9441285] is not handled
08-15 16:22:36.372  1036  8134 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-15 16:22:36.372  1036  1389 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-15 16:22:36.372  1036  8134 E WifiMonitor: WifiMonitor:p2p0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WO,RLD
08-15 16:22:36.372  1036  1389 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-15 16:22:36.372  1036  8134 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-15 16:22:36.372  1036  8134 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-15 16:22:36.372  1036  1389 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-15 16:22:36.372  1036  1036 E WifiServerServiceExt: No p2p device connected
,08-15 16:22:36.385  8135  8135 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-15 16:22:36.387  1036  1918 I ActivityManager: Killing 7198:com.android.chrome/u0a57 (adj 15): empty #17
,08-15 16:22:36.388  6929  6929 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-15 16:22:36.392  6929  6929 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-15 16:22:36.404  6826  6887 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-15 16:22:36.404  6826  6887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 16:22:36.404  6826  6887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-15 16:22:36.404  6826  6887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-15 16:22:36.404  6826  6887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-15 16:22:36.404  6826  6887 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-15 16:22:36.404  6826  6887 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-15 16:22:36.404  6826  6887 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-15 16:22:36.405  6826  6887 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-15 16:22:36.410  6826  6887 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-15 16:22:36.410  6826  6887 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-15 16:22:36.411  6826  6887 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@31278ced Bundle[{}]
08-15 16:22:36.412  6826  6887 I io.jxcore.node.LifeCycleMonitor: start: OK
08-15 16:22:36.412  6826  6887 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-15 16:22:36.412  6826  6887 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-15 16:22:36.413  6826  6887 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-15 16:22:36.413  6826  6887 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-15 16:22:36.414  6826  6887 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-15 16:22:36.418  6826  6887 I System.out: Running OutgoingSocketThread
08-15 16:22:36.419  7828  7839 E UEI.SmartControl: file observer is disposed!
08-15 16:22:36.419  6826  8158 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 877)
,08-15 16:22:36.420  6826  8158 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 55241
08-15 16:22:36.420  6826  8158 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-15 16:22:36.429  1036  1918 I ActivityManager: Killing 7216:com.lge.drmservice/u0a62 (adj 15): empty #17
08-15 16:22:36.471  1036  1597 W libprocessgroup: failed to open /acct/uid_10062/pid_7216/cgroup.procs: No such file or directory
,08-15 16:22:36.478  1036  1052 W libprocessgroup: failed to open /acct/uid_10057/pid_7198/cgroup.procs: No such file or directory
08-15 16:22:36.503  8135  8135 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-15 16:22:36.508  6929  6929 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-15 16:22:36.516  6929  6929 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-15 16:22:36.518  8113  8160 W FormManager: Network not available. Please check & try again.
08-15 16:22:36.534  8113  8161 V FormManager: Network unavailable.
,08-15 16:22:36.538  8113  8161 V FormManager: Network unavailable.
08-15 16:22:36.542  4300  4300 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-15 16:22:36.542  4300  4300 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-15 16:22:36.544  4300  4300 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-15 16:22:36.549  4300  4300 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-15 16:22:36.557  4300  8162 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-15 16:22:36.563  4300  8163 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
,08-15 16:22:36.564  4300  8163 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-15 16:22:36.606  1036  1901 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8164 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-15 16:22:36.738  8164  8164 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-15 16:22:36.740  8164  8164 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-15 16:22:36.756  8164  8164 V [BNRBootReceiver]: Boot Receiver Return
08-15 16:22:36.758  8164  8164 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-15 16:22:36.810  1036  1787 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8185 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-15 16:22:36.816  1036  1787 I ActivityManager: Killing 7234:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
08-15 16:22:36.870  1036  1597 W libprocessgroup: failed to open /acct/uid_10085/pid_7234/cgroup.procs: No such file or directory
,08-15 16:22:36.883  8095  8095 E wpa_supplicant: USIM:  scard_init function
08-15 16:22:36.884  8095  8095 I wpa_supplicant: Trying to associate with SSID 'NG700'
,08-15 16:22:36.886  1036  8134 E WifiMonitor: WifiMonitor:wlan0 cnt=48 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-15 16:22:36.886  1036  8134 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-15 16:22:36.886  1036  8134 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-15 16:22:36.886  1036  8134 E WifiMonitor: WifiMonitor:wlan0 cnt=49 dispatchEvent: WPS-AP-AVAILABLE 
08-15 16:22:36.886  1036  8134 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-15 16:22:36.886  1036  8134 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-15 16:22:36.886  1036  8134 E WifiMonitor: WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-15 16:22:36.887  1036  1422 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-15 16:22:36.888  1036  1422 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-15 16:22:36.889  1036  1422 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-15 16:22:36.889  1036  1422 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-15 16:22:36.889  1036  1422 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-15 16:22:36.900  8185  8185 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-15 16:22:36.902  1036  1422 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 50 0 rt=213634  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-15 16:22:36.905  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-15 16:22:36.905  1606  1606 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-15 16:22:36.905  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 16:22:36.905  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 16:22:36.905  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-15 16:22:36.906  1036  1422 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 50 0 rt=213638  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-15 16:22:36.907  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-15 16:22:36.907  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-15 16:22:36.907  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-15 16:22:36.931  8185  8185 D PluginManager: init()
,08-15 16:22:36.999  8095  8095 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-15 16:22:36.999  1036  8134 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-15 16:22:36.999  1036  8134 E WifiMonitor: WifiMonitor:wlan0 cnt=51 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-15 16:22:37.000  1036  8134 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-15 16:22:37.000  1036  8134 E WifiMonitor: WifiMonitor:wlan0 cnt=52 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-15 16:22:37.001  1036  8134 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-15 16:22:37.001  1036  8134 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-15 16:22:37.005  1036  1422 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 51 0 rt=213736  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-15 16:22:37.008  1036  8134 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-15 16:22:37.008  8095  8095 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-15 16:22:37.008  1036  8134 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-15 16:22:37.008  8095  8095 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-15 16:22:37.010  1036  1118 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-15 16:22:37.012  1036  8134 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-15 16:22:37.012  1036  8134 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-15 16:22:37.012  1036  8134 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-15 16:22:37.012  1036  8134 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-15 16:22:37.012  1036  8134 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-15 16:22:37.013  1036  8134 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-15 16:22:37.013  1036  8134 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-15 16:22:37.013  1036  8134 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-15 16:22:37.013  1036  1422 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 51 0 rt=213744  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-15 16:22:37.014  1036  1422 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 52 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=213745
08-15 16:22:37.014  1036  1422 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 52 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=213746
08-15 16:22:37.015  1036  1422 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 52 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=213746
08-15 16:22:37.015  1036  1422 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 52 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=213746
08-15 16:22:37.016  1036  1422 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 52 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=213747
08-15 16:22:37.016  1036  1422 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 53 0 rt=213748  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
,08-15 16:22:37.024  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 16:22:37.024  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 16:22:37.025  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-15 16:22:37.028  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 16:22:37.028  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 16:22:37.028  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-15 16:22:37.029  1036  1422 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 53 0 rt=213760  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-15 16:22:37.029  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-15 16:22:37.029  1606  1606 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-15 16:22:37.030  1036  1422 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 54 0 rt=213761  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-15 16:22:37.031  1036  1422 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 54 0 rt=213762  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-15 16:22:37.031  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-15 16:22:37.031  1036  1422 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
08-15 16:22:37.032  1036  1422 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-15 16:22:37.032  1036  1422 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
,08-15 16:22:37.033  1036  1422 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-15 16:22:37.033  1036  1422 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-15 16:22:37.033  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-15 16:22:37.033  1606  1606 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-15 16:22:37.034  1036  1422 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=213765
08-15 16:22:37.034  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-15 16:22:37.035  1036  1422 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=213767
08-15 16:22:37.036  1036  1422 D WifiNative-wlan0: doString: [STATUS]
08-15 16:22:37.037  1036  8134 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-15 16:22:37.037  1036  8134 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-15 16:22:37.037  1036  1422 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-15 16:22:37.039  1036  1422 I WifiServiceExtension: setVHTCapabilityType  : false
08-15 16:22:37.044  1036  1422 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-15 16:22:37.044  1036  1422 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,08-15 16:22:37.053  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 16:22:37.053  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 16:22:37.053  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-15 16:22:37.053  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 16:22:37.053  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 16:22:37.053  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-15 16:22:37.054  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-15 16:22:37.054  1606  1606 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-15 16:22:37.055  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-15 16:22:37.057  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-15 16:22:37.057  1606  1606 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-15 16:22:37.058  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-15 16:22:37.061  1036  1422 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-15 16:22:37.062  1036  1477 D ConnectivityService: Got NetworkAgent Messenger
08-15 16:22:37.062  1036  1422 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-15 16:22:37.062  1036  1422 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-15 16:22:37.062  1036  1477 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-15 16:22:37.062  1036  1477 D ConnectivityService: NetworkAgent connected
08-15 16:22:37.063  1036  1422 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-15 16:22:37.063  1036  1422 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-15 16:22:37.070  1036  1422 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-15 16:22:37.070  1036  1422 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-15 16:22:37.070  1036  1422 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-15 16:22:37.071  1036  1422 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-15 16:22:37.071  1036  1422 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-15 16:22:37.076  1036  1422 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-15 16:22:37.078   312   894 D CommandListener: Setting iface cfg
08-15 16:22:37.081  1036  1422 E WifiStateMachine: Start Dhcp Watchdog 3
08-15 16:22:37.081  1036  1422 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=213813  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-15 16:22:37.082  1036  1422 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=213813  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-15 16:22:37.082  1036  1422 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=213814  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-15 16:22:37.083  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
,08-15 16:22:37.083  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-15 16:22:37.085  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-15 16:22:37.085  1036  1036 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-15 16:22:37.086  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-15 16:22:37.086  1036  1036 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-15 16:22:37.087  1036  1422 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=213818  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-15 16:22:37.087  1036  1422 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=213818  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-15 16:22:37.088  1036  1422 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=213819  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-15 16:22:37.089  1036  1422 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13859] from screen [on:0 period:-1902825439] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-15 16:22:37.090  1036  1422 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1902825438] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-15 16:22:37.090  1036  1422 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-15 16:22:37.092  1036  8203 D DhcpStateMachine: StoppedState
08-15 16:22:37.092  1036  8203 D DhcpStateMachine: StoppedState{ when=-11ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-15 16:22:37.092  1036  8203 D DhcpStateMachine: WaitBeforeStartState
08-15 16:22:37.094  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-15 16:22:37.096  1036  1477 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
08-15 16:22:37.096  1036  1422 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-15 16:22:37.097  1036  1422 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-15 16:22:37.097  1036  1422 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-15 16:22:37.097  1036  1422 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-15 16:22:37.098  1036  1422 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-15 16:22:37.098  1036  1422 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,08-15 16:22:37.098  1036  1477 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-15 16:22:37.099  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-15 16:22:37.099  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-15 16:22:37.101  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-15 16:22:37.101  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
,08-15 16:22:37.101  1036  1422 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=195,0,0
08-15 16:22:37.102  1036  1422 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=195,0,0
08-15 16:22:37.102  1036  1422 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-15 16:22:37.102  8095  8095 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-15 16:22:37.102  1036  1422 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-15 16:22:37.102  1036  1422 D WifiNative-wlan0: doBoolean: SET ps 0
08-15 16:22:37.103  1036  1422 D WifiNative-wlan0: SET ps 0: returned true
08-15 16:22:37.103  1036  1422 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-15 16:22:37.103  8095  8095 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-15 16:22:37.105  1036  1422 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-15 16:22:37.105  1036  1422 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-15 16:22:37.105  1036  1422 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-15 16:22:37.105  1036  1389 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@156eef40 target=com.android.internal.util.StateMachine$SmHandler }
08-15 16:22:37.105  1036  1389 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@156eef40 target=com.android.internal.util.StateMachine$SmHandler }
08-15 16:22:37.105  1036  1422 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-15 16:22:37.105  1036  8203 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-15 16:22:37.105  1036  8203 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-15 16:22:37.106   312   894 D CommandListener: Setting iface cfg
08-15 16:22:37.106   312   894 D CommandListener: Trying to bring up wlan0
08-15 16:22:37.107  1036  1422 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-15 16:22:37.108  1036  1422 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-15 16:22:37.109  1036  1422 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-15 16:22:37.109  1036  1422 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-15 16:22:37.109  1036  1422 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-15 16:22:37.110  1036  1422 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-15 16:22:37.110  1036  1422 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-15 16:22:37.110  1036  1477 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-15 16:22:37.111  1036  1422 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-15 16:22:37.111  1036  1422 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-15 16:22:37.111  1036  1389 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-15 16:22:37.111  1036  1389 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-15 16:22:37.112  1036  1422 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-15 16:22:37.112  8095  8095 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-15 16:22:37.112  1036  1422 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-15 16:22:37.112  1036  1422 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-15 16:22:37.112  8095  8095 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-15 16:22:37.112  1036  1422 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
,08-15 16:22:37.112  1036  1422 D WifiNative-wlan0: doBoolean: SET ps 1
08-15 16:22:37.128  1036  1422 D WifiNative-wlan0: SET ps 1: returned true
08-15 16:22:37.129  1036  1477 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-15 16:22:37.129  1036  1422 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-15 16:22:37.129  1036  1422 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-15 16:22:37.129  1036  1422 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-15 16:22:37.129  1036  1477 D ConnectivityService: ignoring duplicate network state non-change
08-15 16:22:37.131  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-15 16:22:37.131  1606  1606 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-15 16:22:37.132  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 16:22:37.133  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 16:22:37.133  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-15 16:22:37.133  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-15 16:22:37.135  1036  1422 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-15 16:22:37.135  1036  1477 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-15 16:22:37.136  1036  1477 D ConnectivityService: Adding iface wlan0 to network 102
08-15 16:22:37.141  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 16:22:37.141  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 16:22:37.141  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-15 16:22:37.142  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-15 16:22:37.145  1942  1942 V WfdStateTracker: handleWifiStateChangedEvent: 1
,08-15 16:22:37.149  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 16:22:37.149  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 16:22:37.150  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-15 16:22:37.151  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-15 16:22:37.152  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-15 16:22:37.152  1606  1606 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-15 16:22:37.154  1036  1477 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-15 16:22:37.154  1036  1477 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-15 16:22:37.155  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-15 16:22:37.156  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 16:22:37.156  1036  1477 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
08-15 16:22:37.156  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 16:22:37.156  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-15 16:22:37.156   312   894 E Netd    : netlink response contains error (File exists)
08-15 16:22:37.157  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-15 16:22:37.158  1606  1606 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-15 16:22:37.158  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-15 16:22:37.158  1036  1477 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-15 16:22:37.160  1036  1477 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-15 16:22:37.160  1036  1477 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
08-15 16:22:37.160  1036  1477 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-15 16:22:37.160  1036  1477 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-15 16:22:37.161  1036  1477 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-15 16:22:37.161  1036  1477 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-15 16:22:37.162  1036  8202 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-15 16:22:37.162  1036  8202 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-15 16:22:37.162  1036  8202 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-15 16:22:37.162  1036  8202 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-15 16:22:37.164  1036  1477 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-15 16:22:37.164  1036  1477 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-15 16:22:37.164  1036  1477 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-15 16:22:37.164  1036  1477 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-15 16:22:37.164  1036  1477 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-15 16:22:37.164  1036  1477 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-15 16:22:37.165  1036  1477 D ConnectivityService: currentScore = 0, newScore = 20
08-15 16:22:37.165  1036  1477 D ConnectivityService:    accepting network in place of null
08-15 16:22:37.165  1036  1477 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-15 16:22:37.165  1036  1422 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-15 16:22:37.165  1036  1422 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-15 16:22:37.165  1853  1853 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-15 16:22:37.166  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-15 16:22:37.166   312  8213 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-15 16:22:37.166  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-15 16:22:37.167  1606  1606 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-15 16:22:37.167  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-15 16:22:37.168  1036  1477 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> ,192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-15 16:22:37.168  1036  1477 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-15 16:22:37.168  1036  1477 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-15 16:22:37.168  1036  1477 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-15 16:22:37.169  1036  1477 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-15 16:22:37.169  1036  1477 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-15 16:22:37.170  1036  1036 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-15 16:22:37.170  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-15 16:22:37.170  1036  1477 D ConnectivityService: validation of new default Network = false
08-15 16:22:37.170  1036  1477 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-15 16:22:37.170  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-15 16:22:37.170  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-15 16:22:37.170  1036  1477 D DSQN    : enableDataServiceNotify 
08-15 16:22:37.170  1036  1477 D DSQN    : start dsqn bin
,08-15 16:22:37.175  1036  1477 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-15 16:22:37.175  1036  1477 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-15 16:22:37.175  1036  1477 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-15 16:22:37.176  1036  1477 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-15 16:22:37.167  8214  8214 W dsqn    : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-15 16:22:37.167  8214  8214 W dsqn    : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-15 16:22:37.181  1606  2076 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-15 16:22:37.185  1036  1388 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-15 16:22:37.189  8214  8214 E DSQN    : DSQN ssw
,08-15 16:22:37.196  1606  1606 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-15 16:22:37.197  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-15 16:22:37.198  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-15 16:22:37.214   312  8213 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-15 16:22:37.245   312  8213 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-15 16:22:37.280   312   893 D LGDataListener: argv[0]=dsqncommand
08-15 16:22:37.280   312   893 D LGDataListener: argv[1]=wlan0
08-15 16:22:37.280   312   893 D LGDataListener: argv[2]=1
08-15 16:22:37.280   312   893 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
,08-15 16:22:37.281  1036  1116 D DSQN    : DSQM DsqnNotification wlan0  1
08-15 16:22:37.281  1036  1116 D DSQN    : start to monitor internet connection
08-15 16:22:37.307  1036  8203 D DhcpStateMachine: DHCPV4 request on wlan0
,08-15 16:22:37.308  1036  8202 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 15 Aug 2016 14:22:37 GMT], X-Android-Received-Millis=[1471270957307], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1471270957278]}
08-15 16:22:37.308  1036  8203 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-15 16:22:37.308  1036  8203 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-15 16:22:37.308  1036  8202 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-15 16:22:37.308  1036  8202 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-15 16:22:37.309  1036  1477 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
08-15 16:22:37.309  1036  1477 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-15 16:22:37.310  1036  1477 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-15 16:22:37.310  1036  1477 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-15 16:22:37.310  1036  1477 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-15 16:22:37.310  1036  1477 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-15 16:22:37.310  1036  1477 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-15 16:22:37.310  1036  1477 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-15 16:22:37.311  1036  1477 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-15 16:22:37.312  1036  1477 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-15 16:22:37.307  8220  8220 W dhcpcd  : type=1400 audit(0.0:195): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-15 16:22:37.307  8220  8220 W dhcpcd  : type=1400 audit(0.0:196): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-15 16:22:37.313  1606  2076 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-15 16:22:37.315  1036  1477 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-15 16:22:37.315  1036  1422 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-15 16:22:37.315  1036  1422 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-15 16:22:37.316  1036  1477 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-15 16:22:37.316  1853  1853 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-15 16:22:37.317  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-15 16:22:37.330  8220  8220 I dhcpcd  : version 5.5.6 starting
08-15 16:22:37.332  8220  8220 E dhcpcd  : get_duid: m
08-15 16:22:37.332  8220  8220 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-15 16:22:37.332  8220  8220 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hoo,ks', reason PREINIT
,08-15 16:22:37.337  1606  1606 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-15 16:22:37.339  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-15 16:22:37.340  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-15 16:22:37.395  8185  8185 W ExternalStrings: load override strings
08-15 16:22:37.395  8185  8185 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
08-15 16:22:37.395  8185  8185 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
08-15 16:22:37.395  8185  8185 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
08-15 16:22:37.395  8185  8185 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
08-15 16:22:37.395  8185  8185 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
08-15 16:22:37.395  8185  8185 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
08-15 16:22:37.395  8185  8185 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
08-15 16:22:37.395  8185  8185 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-15 16:22:37.395  8185  8185 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-15 16:22:37.395  8185  8185 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-15 16:22:37.395  8185  8185 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-15 16:22:37.395  8185  8185 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-15 16:22:37.395  8185  8185 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
08-15 16:22:37.395  8185  8185 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-15 16:22:37.395  8185  8185 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
08-15 16:22:37.395  8185  8185 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-15 16:22:37.395  8185  8185 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-15 16:22:37.395  8185  8185 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-15 16:22:37.397  8185  8185 D StatusProvider: onCreate
,08-15 16:22:37.406  8220  8220 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-15 16:22:37.407  8220  8220 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-15 16:22:37.407  8220  8220 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-15 16:22:37.407  8220  8220 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
08-15 16:22:37.407  8220  8220 D dhcpcd  : wlan0: sending REQUEST (xid 0x2dc8934d), next in 3.38 seconds
,08-15 16:22:37.420  6826  6887 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 878)
,08-15 16:22:37.420  6826  6887 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 878)
08-15 16:22:37.423  6826  6887 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 883)
08-15 16:22:37.424  6826  6887 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-15 16:22:37.424  6826  6887 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 884)
08-15 16:22:37.427  6826  6887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-15 16:22:37.427  6826  6887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39f0cc34 added. We now have 2 listener(s)
08-15 16:22:37.428  1036  2014 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-15 16:22:37.432  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-15 16:22:37.432  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-15 16:22:37.432  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-15 16:22:37.432  6826  6887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-15 16:22:37.432  6826  6887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2df6fa5d added. We now have 9 listener(s)
08-15 16:22:37.433  6826  6887 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-15 16:22:37.433  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-15 16:22:37.436  6826  6887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-15 16:22:37.442  6826  6887 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-15 16:22:37.442  6826  6887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 16:22:37.442  6826  6887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-15 16:22:37.442  6826  6887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-15 16:22:37.442  6826  6887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-15 16:22:37.442  6826  6887 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-15 16:22:37.442  6826  6887 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-15 16:22:37.442  6826  6887 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-15 16:22:37.443  6826  6887 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-15 16:22:37.443  6826  6887 D io.jxcore.node.ConnectivityMonitor: start: OK
08-15 16:22:37.443  6826  6887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-15 16:22:37.443  6826  6887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@299eb8a3 added. We now have 3 listener(s)
08-15 16:22:37.444  1036  1945 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-15 16:22:37.446  6826  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-15 16:22:37.447  6826  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 16:22:37.449  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-15 16:22:37.449  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-15 16:22:37.449  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-15 16:22:37.449  6826  6887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-15 16:22:37.449  6826  6887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e877a0 added. We now have 10 listener(s)
08-15 16:22:37.449  6826  6887 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-15 16:22:37.449  6826  6887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-15 16:22:37.449  6826  6887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-15 16:22:37.449  6826  6887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-15 16:22:37.450  6826  6887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-15 16:22:37.450  6826  6887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:22:37.450  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-15 16:22:37.450  6826  6887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-15 16:22:37.450  6826  6887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39f0cc34 removed from the list
08-15 16:22:37.450  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:22:37.450  6826  6887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2df6fa5d removed from the list
08-15 16:22:37.450  6826  6887 D io.jxcore.node.ConnectivityMonitor: stop
08-15 16:22:37.450  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:22:37.450  6826  6887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:22:37.450  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:22:37.451  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-15 16:22:37.451  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-15 16:22:37.451  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:22:37.451  6826  6887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2df6fa5d not in the list
08-15 16:22:37.451  6826  6887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:22:37.451  6826  6887 D org.thaliproject.p2p.btconnec,torlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:22:37.452  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-15 16:22:37.452  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-15 16:22:37.452  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:22:37.452  6826  6887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e877a0 removed from the list
08-15 16:22:37.452  6826  6887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-15 16:22:37.452  6826  6887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:22:37.453  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:22:37.453  6826  6887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-15 16:22:37.453  6826  6887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@299eb8a3 removed from the list
08-15 16:22:37.453  6826  6887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-15 16:22:37.454  6826  6887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e2ddf59 added. We now have 2 listener(s)
08-15 16:22:37.454  1036  1901 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-15 16:22:37.455  8220  8220 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
08-15 16:22:37.456  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-15 16:22:37.456  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-15 16:22:37.456  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-15 16:22:37.457  6826  6887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-15 16:22:37.457  6826  6887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6b671e added. We now have 9 listener(s)
08-15 16:22:37.457  6826  6887 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-15 16:22:37.457  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-15 16:22:37.459  6826  6887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-15 16:22:37.463  6826  6887 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-15 16:22:37.463  6826  6887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 16:22:37.463  6826  6887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-15 16:22:37.463  6826  6887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-15 16:22:37.463  6826  6887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-15 16:22:37.463  6826  6887 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-15 16:22:37.463  6826  6887 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-15 16:22:37.463  6826  6887 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-15 16:22:37.465  6826  6887 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-15 16:22:37.465  6826  6887 D io.jxcore.node.ConnectivityMonitor: start: OK
08-15 16:22:37.465  6826  6887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-15 16:22:37.465  6826  6887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bed6dcc added. We now have 3 listener(s)
08-15 16:22:37.466  1036  1939 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-15 16:22:37.468  6826  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 16:22:37.469  6826  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 16:22:37.470  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-15 16:22:37.470  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-15 16:22:37.470  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-15 16:22:37.471  6826  6887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-15 16:22:37.471  6826  6887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33541815 added. We now have 10 listener(s)
08-15 16:22:37.471  6826  6887 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-15 16:22:37.471  6826  6887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-15 16:22:37.471  6826  6887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-15 16:22:37.471  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-15 16:22:37.471  6826  6887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-15 16:22:37.471  6826  6887 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-15 16:22:37.474  6826  6887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-15 16:22:37.478  1036  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-15 16:22:37.482  6826  6887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-15 16:22:37.483  6826  6887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-15 16:22:37.484  6826  6887 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-15 16:22:37.485  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-15 16:22:37.486  6826  6887 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-15 16:22:37.487  6826  6887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-15 16:22:37.487  6826  6887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-15 16:22:37.488  8220  8220 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
08-15 16:22:37.488  8220  8220 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
08-15 16:22:37.489  8220  8220 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-15 16:22:37.489  8220  8220 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-15 16:22:37.489  6826  6887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-15 16:22:37.489  6826  6887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-15 16:22:37.490  6826  6887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-15 16:22:37.490  8220  8220 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-15 16:22:37.490  6826  6887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-15 16:22:37.490  6826  6887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:22:37.490  8185  8185 V Signer  : override build config not found
08-15 16:22:37.490  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-15 16:22:37.490  6826  6887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-15 16:22:37.490  6826  6887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e2ddf59 removed from the list
08-15 16:22:37.490  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:22:37.490  6826  6887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6b671e removed from the list
08-15 16:22:37.490  6826  6887 D io.jxcore.node.ConnectivityMonitor: stop
08-15 16:22:37.490  8185  8185 D Signer  : value of property debug is false
08-15 16:22:37.490  8220  8220 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-15 16:22:37.490  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:22:37.491  8220  8220 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-15 16:22:37.491  8220  8220 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-15 16:22:37.492  6826  6887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:22:37.492  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:22:37.493  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-15 16:22:37.493  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-15 16:22:37.493  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:22:37.493  6826  6887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6b671e not in the list
08-15 16:22:37.493  6826  6887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:22:37.493  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:22:37.494  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-15 16:22:37.494  6826  6887 D BluetoothLeScanner: could not find callback wrapper
08-15 16:22:37.494  6826  ,6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-15 16:22:37.494  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-15 16:22:37.494  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:22:37.494  6826  6887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33541815 removed from the list
08-15 16:22:37.494  6826  6887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-15 16:22:37.494  6826  6887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:22:37.494  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:22:37.495  6826  6887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-15 16:22:37.495  6826  6887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bed6dcc removed from the list
08-15 16:22:37.495  6826  6887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-15 16:22:37.496  6826  6887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35699ab8 added. We now have 2 listener(s)
08-15 16:22:37.496  1036  1915 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-15 16:22:37.499  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-15 16:22:37.499  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-15 16:22:37.499  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-15 16:22:37.499  6826  6887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-15 16:22:37.499  6826  6887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6b2091 added. We now have 9 listener(s)
08-15 16:22:37.499  6826  6887 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-15 16:22:37.500  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-15 16:22:37.503  6826  6887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-15 16:22:37.506  6826  6887 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-15 16:22:37.506  6826  6887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 16:22:37.506  6826  6887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-15 16:22:37.506  6826  6887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-15 16:22:37.506  6826  6887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-15 16:22:37.506  6826  6887 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-15 16:22:37.506  6826  6887 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-15 16:22:37.506  6826  6887 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-15 16:22:37.508  6826  6887 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-15 16:22:37.508  6826  6887 D io.jxcore.node.ConnectivityMonitor: start: OK
08-15 16:22:37.510  6826  6887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-15 16:22:37.510  6826  6887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@425abf7 added. We now have 3 listener(s)
08-15 16:22:37.510  1036  2025 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-15 16:22:37.510  6826  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 16:22:37.512  6826  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-15 16:22:37.515  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-15 16:22:37.515  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-15 16:22:37.515  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-15 16:22:37.515  6826  6887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-15 16:22:37.515  7828  7931 D UEI.SmartControl: Internal timer expired: 3
08-15 16:22:37.515  6826  6887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3679aa64 added. We now have 10 listener(s)
08-15 16:22:37.515  7828  7931 D UEI.SmartControl: unbind internal service
08-15 16:22:37.515  6826  6887 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-15 16:22:37.515  6826  6887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-15 16:22:37.516  6826  6887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-15 16:22:37.516  6826  6887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-15 16:22:37.516  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-15 16:22:37.516  6826  6887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-15 16:22:37.516  6826  6887 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-15 16:22:37.518  7828  7828 D UEI.SmartControl: Service.onUnbind: IControl
08-15 16:22:37.518  7828  7828 D UEI.SmartControl: Service.onDestroy
08-15 16:22:37.519  7828  7828 D UEI.SmartControl: Lock is in USE false
08-15 16:22:37.519  7828  7828 D UEI.SmartControl: unbind internal service
08-15 16:22:37.519  7828  7828 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@23a26796
08-15 16:22:37.519  7828  7828 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
08-15 16:22:37.519  7828  7828 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
08-15 16:22:37.519  7828  7828 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
08-15 16:22:37.521  7828  7828 W System.err: 	at com.uei.control.Service.c(Unknown Source)
08-15 16:22:37.521  7828  7828 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
08-15 16:22:37.521  7828  7828 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
08-15 16:22:37.521  7828  7828 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
08-15 16:22:37.521  7828  7828 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
08-15 16:22:37.521  7828  7828 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-15 16:22:37.521  7828  7828 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-15 16:22:37.521  7828  7828 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-15 16:22:37.522  7828  7828 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-15 16:22:37.522  7828  78,28 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-15 16:22:37.522  7828  7828 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-15 16:22:37.522  7828  7828 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-15 16:22:37.522  7828  7828 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@23a26796
08-15 16:22:37.522  7828  7828 D serial_port: close(fd = 24)
08-15 16:22:37.523  6826  6887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-15 16:22:37.524  1036  1787 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-15 16:22:37.527  6826  6887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-15 16:22:37.528  6826  6887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-15 16:22:37.530  6826  6887 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-15 16:22:37.531  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-15 16:22:37.532  6826  6887 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-15 16:22:37.533  7828  7828 I UEI.SmartControl: Serial port is closed.
08-15 16:22:37.533  7828  7828 I UEI.SmartControl: Serial port is closed.
08-15 16:22:37.533  7828  7828 D UEI.SmartControl: Blaster closed
08-15 16:22:37.533  7828  7828 D UEI.SmartControl: Shut down QS...
08-15 16:22:37.533  7828  7828 D UEI.SmartControl: Stopping QS lib
08-15 16:22:37.533  7828  7828 D UEI.SmartControl: QS lib stop result = true
08-15 16:22:37.533  7828  7828 D UEI.SmartControl: Stopped QS lib
08-15 16:22:37.533  7828  7828 D UEI.SmartControl: QS shutdown complete
08-15 16:22:37.535  6826  6887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-15 16:22:37.535  6826  6887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-15 16:22:37.535  6826  6887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-15 16:22:37.535  6826  6887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-15 16:22:37.535  6826  6887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:22:37.535  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-15 16:22:37.535  6826  6887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-15 16:22:37.535  6826  6887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35699ab8 removed from the list
08-15 16:22:37.535  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:22:37.535  6826  6887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6b2091 removed from the list
08-15 16:22:37.535  6826  6887 D io.jxcore.node.ConnectivityMonitor: stop
08-15 16:22:37.535  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:22:37.536  6826  6887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:22:37.536  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:22:37.537  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-15 16:22:37.537  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-15 16:22:37.537  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:22:37.537  6826  6887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6b2091 not in the list
08-15 16:22:37.537  6826  6887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:22:37.537  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:22:37.538  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-15 16:22:37.539  6826  6887 D BluetoothL,eScanner: could not find callback wrapper
08-15 16:22:37.539  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-15 16:22:37.539  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-15 16:22:37.539  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:22:37.539  6826  6887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3679aa64 removed from the list
08-15 16:22:37.539  6826  6887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-15 16:22:37.539  6826  6887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:22:37.539  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:22:37.539  6826  6887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-15 16:22:37.539  6826  6887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@425abf7 removed from the list
08-15 16:22:37.540  6826  6887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-15 16:22:37.540  6826  6887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36ff1093 added. We now have 2 listener(s)
08-15 16:22:37.540  1036  1978 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-15 16:22:37.543  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-15 16:22:37.543  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-15 16:22:37.543  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-15 16:22:37.543  6826  6887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-15 16:22:37.543  6826  6887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@65908d0 added. We now have 9 listener(s)
08-15 16:22:37.543  6826  6887 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-15 16:22:37.543  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-15 16:22:37.545  6826  6887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-15 16:22:37.545  8185  8185 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
08-15 16:22:37.545  8185  8185 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
08-15 16:22:37.546  8185  8185 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
08-15 16:22:37.546  8185  8185 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
08-15 16:22:37.546  8185  8185 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
08-15 16:22:37.546  8185  8185 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
08-15 16:22:37.546  8185  8185 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
08-15 16:22:37.547  8185  8185 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
08-15 16:22:37.547  8185  8185 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
08-15 16:22:37.547  8185  8185 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
08-15 16:22:37.547  8185  8185 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
08-15 16:22:37.548  8185  8185 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
08-15 16:22:37.548  8185  8185 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
08-15 16:22:37.549  6826  6887 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-15 16:22:37.549  6826  6887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 16:22:37.549  6826  6887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-15 16:22:37.549  6826  6887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-15 16:22:37.549  6826  6887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-15 16:22:37.549  6826  6887 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-15 16:22:37.549  6826  6887 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-15 16:22:37.549  6826  6887 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-15 16:22:37.551  6826  6887 D io.jxcore.node.JXcoreExtension: notifyNetwor,kChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-15 16:22:37.551  6826  6887 D io.jxcore.node.ConnectivityMonitor: start: OK
08-15 16:22:37.551  6826  6887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-15 16:22:37.551  6826  6887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@314dd3ce added. We now have 3 listener(s)
08-15 16:22:37.551  1036  1978 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-15 16:22:37.553  6826  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 16:22:37.555  6826  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 16:22:37.557  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-15 16:22:37.557  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-15 16:22:37.557  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-15 16:22:37.557  6826  6887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-15 16:22:37.557  6826  6887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@140022ef added. We now have 10 listener(s)
08-15 16:22:37.557  6826  6887 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-15 16:22:37.557  8185  8185 V LGMDMManager: Create singleton instance
08-15 16:22:37.557  6826  6887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-15 16:22:37.557  6826  6887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-15 16:22:37.557  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-15 16:22:37.557  6826  6887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-15 16:22:37.557  6826  6887 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-15 16:22:37.561  6826  6887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-15 16:22:37.561  1036  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-15 16:22:37.565  6826  6887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-15 16:22:37.566  6826  6887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-15 16:22:37.568  6826  6887 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-15 16:22:37.568  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-15 16:22:37.570  6826  6887 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-15 16:22:37.571  6826  6887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-15 16:22:37.571  6826  6887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-15 16:22:37.572  6826  6887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-15 16:22:37.572  6826  6887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-15 16:22:37.572  6826  6887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:22:37.572  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-15 16:22:37.572  6826  6887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-15 16:22:37.572  6826  6887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36ff1093 removed from the list
08-15 16:22:37.572  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:22:37.572  6826  6887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@65908d0 removed from the list
08-15 16:22:37.572  6826  6887 D io.jxcore.node.ConnectivityMonitor: stop
08-15 16:22:37.572  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:22:37.572  6826  6887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:22:37.572  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:22:37.574  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-15 16:22:37.574  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-15 16:22:37.574  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:22:37.574  6826  6887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@65908d0 not in the list
08-15 16:22:37.574  6826  6887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:22:37.574  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:22:37.575  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-15 16:22:37.575  6826  6887 D BluetoothLeScanner: could not find callback wrapper
08-15 16:22:37.575  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-15 16:22:37.575  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-15 16:22:37.575  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:22:37.575  6826  6887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@140022ef removed from the list
08-15, 16:22:37.575  6826  6887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-15 16:22:37.575  6826  6887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:22:37.575  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:22:37.575  6826  6887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-15 16:22:37.575  6826  6887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@314dd3ce removed from the list
08-15 16:22:37.576  6826  6887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-15 16:22:37.576  6826  6887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33775eda added. We now have 2 listener(s)
08-15 16:22:37.577  1036  1945 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-15 16:22:37.579  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-15 16:22:37.579  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-15 16:22:37.579  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-15 16:22:37.579  6826  6887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-15 16:22:37.579  6826  6887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f55ff0b added. We now have 9 listener(s)
08-15 16:22:37.579  6826  6887 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-15 16:22:37.580  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-15 16:22:37.583  6826  6887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-15 16:22:37.586  6826  6887 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-15 16:22:37.586  6826  6887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 16:22:37.586  6826  6887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-15 16:22:37.586  6826  6887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-15 16:22:37.586  6826  6887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-15 16:22:37.586  6826  6887 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-15 16:22:37.586  6826  6887 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-15 16:22:37.586  6826  6887 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-15 16:22:37.587  6826  6887 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-15 16:22:37.588  6826  6887 D io.jxcore.node.ConnectivityMonitor: start: OK
08-15 16:22:37.588  6826  6887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-15 16:22:37.588  6826  6887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4845001 added. We now have 3 listener(s)
08-15 16:22:37.588  1036  1915 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-15 16:22:37.589  6826  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 16:22:37.590  6826  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 16:22:37.592  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-15 16:22:37.592  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-15 16:22:37.592  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-15 16:22:37.593  6826  6887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-15 16:22:37.593  6826  6887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e7c8ea6 added. We now have 10 listener(s)
08-15 16:22:37.593  6826  6887 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-15 16:22:37.593  6826  6887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-15 16:22:37.593  6826  6887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-15 16:22:37.593  6826  6887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-15 16:22:37.593  6826  6887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-15 16:22:37.593  6826  6887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:22:37.593  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-15 16:22:37.593  6826  6887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-15 16:22:37.593  6826  6887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33775eda removed from the list
08-15 16:22:37.593  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:22:37.593  6826  6887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f55ff0b removed from the list
08-15 16:22:37.593  6826  6887 D io.jxcore.node.ConnectivityMonitor: stop
08-15 16:22:37.593  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:22:37.594  6826  6887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:22:37.594  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:22:37.594  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-15 16:22:37.594  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-15 16:22:37.594  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:22:37.595  6826  6887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f55ff0b not in the list
08-15 16:22:37.595  6826  6887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:22:37.595  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:22:37.595  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-15 16:22:37.595  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-15 16:22:37.595  6826  6887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:22:37.595  6826  6887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e7c8ea6 removed from the list
08-15 16:22:37.595  6826  6887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-15 16:22:37.595  6826  6887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:22:37.595  6826  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:22:37.595  6826  6887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-15 16:22:37.595  6826  6887 V org.thaliproject.p2p.btconnectorlib.Conne,ctionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4845001 removed from the list
08-15 16:22:37.596  6826  6887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-15 16:22:37.596  6826  6887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-15 16:22:37.597  6826  6887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-15 16:22:37.597  6826  6887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-15 16:22:37.597  6826  6887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-15 16:22:37.597  6826  6887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-15 16:22:37.606  6826  8238 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 891, name: My test thread name)
08-15 16:22:37.607  6826  8238 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 891, thread name: My test thread name)
08-15 16:22:37.607  6826  8238 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 891, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-15 16:22:37.609  6826  8239 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 893, name: My test thread name)
08-15 16:22:37.609  6826  8239 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 893, thread name: My test thread name)
08-15 16:22:37.609  6826  8239 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 893, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-15 16:22:37.612  6826  6887 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-15 16:22:37.612  6826  6887 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-15 16:22:37.612  6826  6887 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-15 16:22:37.612  6826  6887 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-15 16:22:37.612  6826  6887 D com.test.thalitest.ThaliTestRunner: Total duration: 22924 ms
08-15 16:22:37.613  6826  6887 I jxcore-log: Total number of executed tests:  80
08-15 16:22:37.613  6826  6887 I jxcore-log: 
08-15 16:22:37.613  6826  6887 I jxcore-log: Number of passed tests:  80
08-15 16:22:37.613  6826  6887 I jxcore-log: 
08-15 16:22:37.613  6826  6887 I jxcore-log: Number of failed tests:  0
08-15 16:22:37.613  6826  6887 I jxcore-log: 
08-15 16:22:37.614  6826  6887 I jxcore-log: Number of ignored tests:  0
08-15 16:22:37.614  6826  6887 I jxcore-log: 
08-15 16:22:37.614  6826  6887 I jxcore-log: Total duration:  22924
08-15 16:22:37.614  6826  6887 I jxcore-log: 
08-15 16:22:37.614  6826  6887 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-15 16:22:37.614  6826  6887 I jxcore-log: 
08-15 16:22:37.619  8185  8185 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
,08-15 16:22:37.628  6826  6887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-15 16:22:37.628  6826  6887 I jxcore-log: 
08-15 16:22:37.629  6826  6826 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
08-15 16:22:37.630  6826  6887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-15 16:22:37.630  6826  6887 I jxcore-log: 
08-15 16:22:37.631  6826  6887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-15 16:22:37.631  6826  6887 I jxcore-log: 
08-15 16:22:37.632  6826  6887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-15 16:22:37.632  6826  6887 I jxcore-log: 
08-15 16:22:37.632  6826  6887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-15 16:22:37.632  6826  6887 I jxcore-log: 
08-15 16:22:37.633  6826  6887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-15 16:22:37.633  6826  6887 I jxcore-log: 
08-15 16:22:37.636  6826  6887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-15 16:22:37.636  6826  6887 I jxcore-log: 
,08-15 16:22:37.637  6826  6887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-15 16:22:37.637  6826  6887 I jxcore-log: 
08-15 16:22:37.638  6826  6887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-15 16:22:37.638  6826  6887 I jxcore-log: 
08-15 16:22:37.639  6826  6887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-15 16:22:37.639  6826  6887 I jxcore-log: 
08-15 16:22:37.639  6826  6887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-15 16:22:37.639  6826  6887 I jxcore-log: 
08-15 16:22:37.640  6826  6887 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-15 16:22:37.640  6826  6887 I jxcore-log: 
08-15 16:22:37.641  6826  6887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-15 16:22:37.641  6826  6887 I jxcore-log: 
08-15 16:22:37.641  6826  6887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-15 16:22:37.641  6826  6887 I jxcore-log: 
08-15 16:22:37.642  6826  6887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-15 16:22:37.642  6826  6887 I jxcore-log: 
08-15 16:22:37.642  6826  6887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-15 16:22:37.642  6826  6887 I jxcore-log: 
08-15 16:22:37.643  6826  6887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-15 16:22:37.643  6826  6887 I jxcore-log: 
08-15 16:22:37.643  6826  6887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-15 16:22:37.643  6826  6887 I jxcore-log: 
08-15 16:22:37.645  6826  6887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-15 16:22:37.645  6826  6887 I jxcore-log: 
08-15 16:22:37.645  6826  6887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-15 16:22:37.645  6826  6887 I jxcore-log: 
08-15 16:22:37.646  6826  6887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-15 16:22:37.646  6826  6887 I jxcore-log: 
,08-15 16:22:37.646  6826  6887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-15 16:22:37.646  6826  6887 I jxcore-log: 
08-15 16:22:37.647  6826  6887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-15 16:22:37.647  6826  6887 I jxcore-log: 
08-15 16:22:37.647  6826  6887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-15 16:22:37.647  6826  6887 I jxcore-log: 
08-15 16:22:37.648  6826  6887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-15 16:22:37.648  6826  6887 I jxcore-log: 
08-15 16:22:37.648  6826  6887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-15 16:22:37.648  6826  6887 I jxcore-log: 
08-15 16:22:37.649  6826  6887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-15 16:22:37.649  6826  6887 I jxcore-log: 
08-15 16:22:37.651  6826  6887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-15 16:22:37.651  6826  6887 I jxcore-log: 
08-15 16:22:37.652  6826  6887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-15 16:22:37.652  6826  6887 I jxcore-log: 
08-15 16:22:37.674  8185  8185 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-15 16:22:37.674  8185  8251 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-15 16:22:37.682  6929  6929 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-15 16:22:37.687  6929  6929 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-15 16:22:37.711  1036  8203 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-15 16:22:37.712  1036  8203 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-15 16:22:37.712  1036  8203 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-15 16:22:37.712  1036  8203 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
08-15 16:22:37.712  1036  8203 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-15 16:22:37.712  1036  8203 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-15 16:22:37.712  1036  8203 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-15 16:22:37.712  1036  8203 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-15 16:22:37.713  1036  8203 D DhcpStateMachine: RunningState
08-15 16:22:37.720  1036  2046 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=8256 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
08-15 16:22:37.721  1036  2046 I ActivityManager: Killing 7261:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,08-15 16:22:37.813  8185  8249 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-15 16:22:37.884  8254  8254 D AndroidRuntime: 
08-15 16:22:37.884  8254  8254 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-15 16:22:37.887  8254  8254 D AndroidRuntime: CheckJNI is OFF
,08-15 16:22:38.010  1036  1787 W libprocessgroup: failed to open /acct/uid_10093/pid_7261/cgroup.procs: No such file or directory
,08-15 16:22:38.040  8254  8254 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
08-15 16:22:38.049  1036  1092 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
,08-15 16:22:38.049  1036  1092 I ActivityManager: Killing 6826:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,08-15 16:22:38.061  8256  8256 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-15 16:22:38.118  1036  2014 I WindowState: WIN DEATH: Window{af6f7d6 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-15 16:22:38.119  1036  1470 D WifiService: Client connection lost with reason: 4
,08-15 16:22:38.126  1036  2014 D InputDispatcher: Window went away: Window{af6f7d6 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-15 16:22:38.168  8185  8249 D LgDataFeature: LgDataFeature() Constructor: none
,08-15 16:22:38.168  8185  8249 D LgDataFeature: LgDataFeature() Constructor Done, null
08-15 16:22:38.238  8185  8249 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
,08-15 16:22:38.261  1036  1422 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-15 16:22:38.262  1036  1422 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-15 16:22:38.263  1036  1422 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-15 16:22:38.264  1036  1422 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-15 16:22:38.265  1036  1422 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-15 16:22:38.266  1036  1422 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-15 16:22:38.268  1036  1477 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
08-15 16:22:38.268  1036  1477 D ConnectivityService: identical MTU - not setting
08-15 16:22:38.268  1036  1477 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-15 16:22:38.268  1036  1477 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-15 16:22:38.269  1036  1477 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-15 16:22:38.269  1036  1477 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-15 16:22:38.270  1036  1477 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-15 16:22:38.272  1606  2076 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-15 16:22:38.294  1036  1092 I ActivityManager:   Force finishing activity ActivityRecord{3dba5113 u0 com.test.thalitest/.MainActivity t6}
,08-15 16:22:38.354   340   361 E GBMv2   : DFP En is all cleared set to be enabled
,08-15 16:22:38.360  1036  2046 W ActivityManager: Spurious death for ProcessRecord{19430da0 6826:com.test.thalitest/u0a118}, curProc for 6826: null
08-15 16:22:38.361  1036  1124 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-15 16:22:38.371  1036  1124 I ActivityManager:   Force finishing activity ActivityRecord{3dba5113 u0 com.test.thalitest/.MainActivity t6 f}
08-15 16:22:38.371  1036  1124 W ActivityManager: Duplicate finish request for ActivityRecord{3dba5113 u0 com.test.thalitest/.MainActivity t6 f}
,08-15 16:22:38.392  2034  2034 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
,08-15 16:22:38.393  8256  8256 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
08-15 16:22:38.394  1942  1959 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-15 16:22:38.395  1942  1959 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2ececb8e co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-15 16:22:38.397  2034  2034 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-15 16:22:38.400  1942  1959 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-15 16:22:38.401  1942  1959 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2de61faf co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-15 16:22:38.401  2034  2034 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-15 16:22:38.402  2034  2101 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
08-15 16:22:38.409  1606  1606 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-15 16:22:38.414  1997  1997 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-15 16:22:38.414  2747  2747 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
,08-15 16:22:38.420  2478  2669 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-15 16:22:38.421  4483  4483 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-15 16:22:38.421  4483  4483 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-15 16:22:38.422  7724  7724 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-15 16:22:38.423  4483  4483 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-15 16:22:38.423  7724  7724 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-15 16:22:38.423  4483  4483 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-15 16:22:38.423  4483  4483 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-15 16:22:38.423  4483  4483 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-15 16:22:38.423  4483  4483 W System.err: 	at android.os.Looper.loop(Looper.java:135)
,08-15 16:22:38.423  4483  4483 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-15 16:22:38.423  4483  4483 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-15 16:22:38.423  4483  4483 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-15 16:22:38.423  4483  4483 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-15 16:22:38.423  4483  4483 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-15 16:22:38.429  1036  1380 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-15 16:22:38.469  4600  4600 I art     : Explicit concurrent mark sweep GC freed 8398(478KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 616us total 87.987ms
,08-15 16:22:38.481  1036  1550 V SIM_STK : Menu title from STK is T-Mobile
,08-15 16:22:38.490  1036  1036 D administrator: Handling package changes for user 0
08-15 16:22:38.495  2034  2034 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
,08-15 16:22:38.498  1905  1905 D ActionManagerService: notifyUserLog: 1000003
08-15 16:22:38.499  2747  4477 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-15 16:22:38.504  8185  8249 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
08-15 16:22:38.510  1036  1091 W InputMethodInfo: Duplicated subtype definition found: , voice
,08-15 16:22:38.519  2034  2034 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-15 16:22:38.532  1606  1661 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-15 16:22:38.532  1606  1661 D KeyguardModel: createShortcutInfo...
,08-15 16:22:38.533  1606  1661 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-15 16:22:38.533  1606  1661 D KeyguardModel: createShortcutInfo...
08-15 16:22:38.533  2034  2034 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-15 16:22:38.535  8256  8256 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-15 16:22:38.535  2034  2034 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-15 16:22:38.535  8256  8256 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-15 16:22:38.535  8256  8256 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-15 16:22:38.536  8256  8256 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-15 16:22:38.536  8256  8256 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-15 16:22:38.537  1606  1606 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-15 16:22:38.545  1606  1661 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-15 16:22:38.546  1606  1661 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-15 16:22:38.546  1606  1661 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-15 16:22:38.547  1606  1661 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-15 16:22:38.549  8185  8249 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
08-15 16:22:38.549  2034  2034 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-15 16:22:38.550  8185  8249 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-15 16:22:38.550  8185  8249 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-15 16:22:38.551  2747  2781 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-15 16:22:38.553  2034  2034 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-15 16:22:38.553  2034  2034 I GBoardWebViewUtils: , create_time: 1430832262123
08-15 16:22:38.553  2034  2034 I GBoardWebViewUtils: , expire_time: 0
08-15 16:22:38.553  2034  2034 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-15 16:22:38.553  2034  2034 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-15 16:22:38.553  2034  2034 I GBoardWebViewUtils: , display: false
08-15 16:22:38.553  2034  2034 I GBoardWebViewUtils: , animation: false }
08-15 16:22:38.553  2034  2034 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-15 16:22:38.553  2034  2034 I GBoardWebViewUtils: , create_time: 1430832262287
08-15 16:22:38.553  2034  2034 I GBoardWebViewUtils: , expire_time: 0
08-15 16:22:38.553  2034  2034 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-15 16:22:38.553  2034  2034 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-15 16:22:38.553  2034  2034 I GBoardWebViewUtils: , display: false
08-15 16:22:38.553  2034  2034 I GBoardWebViewUtils: , animation:, false }
08-15 16:22:38.553  2034  2034 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1471007225619
08-15 16:22:38.553  2034  2034 I GBoardWebViewUtils: , create_time: 1471007226523
08-15 16:22:38.553  2034  2034 I GBoardWebViewUtils: , expire_time: 0
08-15 16:22:38.553  2034  2034 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide.html?id=guide_1111111111116_1471007225619&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-15 16:22:38.553  2034  2034 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-15 16:22:38.553  2034  2034 I GBoardWebViewUtils: , display: false
08-15 16:22:38.553  2034  2034 I GBoardWebViewUtils: , animation: false }
08-15 16:22:38.554  1905  1905 D ActionManagerService: notifyUserLog: 1000004
08-15 16:22:38.554  1606  1661 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-15 16:22:38.555  1606  1661 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-15 16:22:38.555  2747  4477 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
,08-15 16:22:38.560  8256  8256 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-15 16:22:38.562  2034  8304 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-15 16:22:38.562  8185  8249 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
08-15 16:22:38.563  8185  8249 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
08-15 16:22:38.564  1606  1661 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-15 16:22:38.564  1606  1661 D KeyguardModel: createShortcutInfo...
08-15 16:22:38.566  8256  8256 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-15 16:22:38.569  1606  1661 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
,08-15 16:22:38.570  1606  1661 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-15 16:22:38.573  1870  1870 D SplitUIManager: split_name #11 / not available #0
08-15 16:22:38.574  1870  1870 D SplitUIService: removed split : 
08-15 16:22:38.579  2034  2034 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-15 16:22:38.580  2034  2034 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-15 16:22:38.582  1606  1606 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-15 16:22:38.582  1606  1606 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,08-15 16:22:38.585  1606  1661 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-15 16:22:38.585  1606  1661 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-15 16:22:38.587  1606  1661 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-15 16:22:38.587  1606  1661 D KeyguardModel: createShortcutInfo...
08-15 16:22:38.595  1606  1661 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-15 16:22:38.595  1606  1661 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-15 16:22:38.596  1606  1661 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-15 16:22:38.596  1606  1661 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-15 16:22:38.602  8185  8249 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
08-15 16:22:38.603  1606  1661 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-15 16:22:38.603  1606  1661 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-15 16:22:38.605  8256  8256 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-15 16:22:38.614  1870  1870 D SplitUIManager: split_name #11 / not available #0
08-15 16:22:38.614  1870  1870 I SplitUIService: split app #11
,08-15 16:22:38.620  1606  1661 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-15 16:22:38.620  1606  1661 D KeyguardModel: createShortcutInfo...
08-15 16:22:38.621  1036  1918 V SIM_STK : Menu title from STK is T-Mobile
08-15 16:22:38.621  1036  1918 V SIM_STK : Menu title from STK is T-Mobile
08-15 16:22:38.626  8185  8249 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
08-15 16:22:38.636  8256  8256 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-15 16:22:38.640  1036  1992 V SIM_STK : Menu title from STK is T-Mobile
08-15 16:22:38.661  1606  1606 D KeyguardModel: handleShortcutListChanged...
08-15 16:22:38.661  1606  1606 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,08-15 16:22:38.663  2034  2034 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-15 16:22:38.668  1606  1661 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-15 16:22:38.668  1606  1661 D KeyguardModel: createShortcutInfo...
08-15 16:22:38.670  8256  8256 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-15 16:22:38.671  1606  1661 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-15 16:22:38.671  1606  1661 D KeyguardModel: createShortcutInfo...
08-15 16:22:38.671  8185  8185 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-15 16:22:38.672  8185  8251 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-15 16:22:38.673  1606  1661 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-15 16:22:38.674  1606  1661 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-15 16:22:38.675  1606  1661 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-15 16:22:38.675  1606  1661 D KeyguardModel: createShortcutInfo...
08-15 16:22:38.676  1036  1597 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-15 16:22:38.676  7724  7724 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-15 16:22:38.676  7724  7724 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-15 16:22:38.676  7724  7724 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-15 16:22:38.676  7724  7724 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-15 16:22:38.676  7724  7724 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-15 16:22:38.676  7724  7724 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-15 16:22:38.676  7724  7724 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-15 16:22:38.676  7724  7724 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-15 16:22:38.676  7724  7724 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-15 16:22:38.676  7724  7724 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-15 16:22:38.676  7724  7724 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-15 16:22:38.676  1606  1661 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-15 16:22:38.677  1606  1661 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-15 16:22:38.678  1606  1661 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-15 16:22:38.678  1606  1661 D KeyguardModel: createShortcutInfo...
08-15 16:22:38.680  1606  1661 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-15 16:22:38.680  1606  1661 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-15 16:22:38.682  1606  1661 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-15 16:22:38.682  1606  1661 D KeyguardModel: createShortcutInfo...
08-15 16:22:38.691  8256  8256 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-15 16:22:38.692  6929  6929 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-15 16:22:38.694  1606  1606 D KeyguardModel: handleShortcutListChanged...
08-15 16:22:38.694  1606  1606 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,08-15 16:22:38.699  6929  6929 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-15 16:22:38.703  8256  8256 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-15 16:22:38.704  8256  8256 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-15 16:22:38.704  8256  8256 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-15 16:22:38.705  8256  8256 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-15 16:22:38.707  6929  6929 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-15 16:22:38.712  6929  6929 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
,08-15 16:22:38.718  8185  8185 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-15 16:22:38.718  8185  8251 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-15 16:22:38.732  2034  2034 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,08-15 16:22:38.736  6929  6929 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-15 16:22:38.737  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-15 16:22:38.738  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-15 16:22:38.740  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
,08-15 16:22:38.741  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-15 16:22:38.742  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
,08-15 16:22:38.758  2034  2034 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-15 16:22:38.758  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-15 16:22:38.760  1036  1119 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1a13fffd u0 com.lge.launcher2/.Launcher t5} time:215502
,08-15 16:22:38.770  6929  6929 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-15 16:22:38.772  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
,08-15 16:22:38.773  2034  2034 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-15 16:22:38.773  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-15 16:22:38.783  2034  2149 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-15 16:22:38.783  2034  2149 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-15 16:22:38.785  1036  1036 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-15 16:22:38.785  1036  1036 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-15 16:22:38.786  1036  1036 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-15 16:22:38.787  2034  2034 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-15 16:22:38.787  8256  8256 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-15 16:22:38.787  8256  8256 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-15 16:22:38.787  1036  1579 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-15 16:22:38.787  8256  8256 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-15 16:22:38.789  6929  6929 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-15 16:22:38.789  6929  6929 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-15 16:22:38.789  6929  6929 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-15 16:22:38.789  6929  6929 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-15 16:22:38.790  6929  6929 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-15 16:22:38.790  6929  6929 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-15 16:22:38.791  6929  6929 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-15 16:22:38.791  6929  6929 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-15 16:22:38.791  6929  6929 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-15 16:22:38.791  6929  6929 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-15 16:22:38.791  6929  6929 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-15 16:22:38.791  6929  6929 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-15 16:22:38.792  2034  2034 D [Concierge]WidgetView: change position of spinner
08-15 16:22:38.793  2577  2577 D [Concierge]Service: onStartCommand(). Type : 8
08-15 16:22:38.793  2577  2577 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-15 16:22:38.793  2034  2034 I [Concierge]WidgetView: initWebView(). Time : 1471270958793
08-15 16:22:38.794  2577  2577 D [Concierge]Service: Update widget ID : 11
08-15 16:22:38.794  2577  2577 D [Concierge]Service: onStartCommand(). Type : 0
08-15 16:22:38.795  8185  8185 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-15 16:22:38.795  8185  8251 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-15 16:22:38.799  6929  6929 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-15 16:22:38.801  1036  1124 I art     : Explicit concurrent mark sweep GC freed 79433(4MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/65MB, paused 2.671ms total 401.034ms
08-15 16:22:38.812  6929  6929 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-15 16:22:38.818  8256  8256 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-15 16:22:38.818  8256  8256 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-15 16:22:38.819  8256  8256 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-15 16:22:38.819  2034  2034 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 240104086
08-15 16:22:38.819  2034  2034 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-15 16:22:38.820  2034  2034 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-15 16:22:38.822  2034  2034 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@398e3dc1
08-15 16:22:38.822  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-15 16:22:38.823  2034  2034 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-15 16:22:38.823  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-15 16:22:38.823  8185  8185 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-15 16:22:38.824  8185  8251 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-15 16:22:38.829  6929  6929 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-15 16:22:38.829  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-15 16:22:38.830  2034  2034 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-15 16:22:38.830  2034  2034 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-15 16:22:38.831  2034  2034 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1471270771031, New one : 1471270958793
08-15 16:22:38.831  2034  2034 D [Concierge]WidgetView: Unregister all receivers
08-15 16:22:38.831  2034  2034 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-15 16:22:38.832  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-15 16:22:38.832  6929  6929 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-15 16:22:38.833  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-15 16:22:38.835  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-15 16:22:38.835  8256  8256 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-15 16:22:38.835  8256  8256 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-15 16:22:38.835  8256  8256 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-15 16:22:38.836  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-15 16:22:38.837  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-15 16:22:38.838  8185  8185 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-15 16:22:38.839  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
,08-15 16:22:38.841  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-15 16:22:38.842  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-15 16:22:38.860  6929  6929 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-15 16:22:38.864  6929  6929 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-15 16:22:38.868  8256  8256 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-15 16:22:38.868  8256  8256 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-15 16:22:38.869  8256  8256 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-15 16:22:38.871  8185  8185 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-15 16:22:38.871  2034  2034 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-15 16:22:38.879  2034  2034 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-15 16:22:38.879  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
,08-15 16:22:38.880  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-15 16:22:38.882  6929  6929 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-15 16:22:38.885  6929  6929 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-15 16:22:38.889  8256  8256 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-15 16:22:38.889  8256  8256 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-15 16:22:38.889  8256  8256 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-15 16:22:38.895  8185  8185 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-15 16:22:38.907  8254  8254 D AndroidRuntime: Shutting down VM
,08-15 16:22:38.911  2034  2034 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@38518d73 time:215652
08-15 16:22:38.940  1036  1124 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8317 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-15 16:22:38.944  6929  6929 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-15 16:22:38.946  1036  1091 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-15 16:22:38.948  6929  6929 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-15 16:22:38.952  8256  8256 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-15 16:22:38.952  8256  8256 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-15 16:22:38.955  8256  8256 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-15 16:22:38.959  8185  8185 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-15 16:22:38.967  1036  1091 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-15 16:22:38.967  6929  6929 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-15 16:22:38.969  2034  2034 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-15 16:22:38.974  6929  6929 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-15 16:22:38.978  8256  8256 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-15 16:22:38.979  8256  8256 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-15 16:22:38.979  8256  8256 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-15 16:22:38.983  8185  8185 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-15 16:22:38.987  8135  8135 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-15 16:22:38.990  8135  8135 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-15 16:22:38.992  6929  6929 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-15 16:22:38.999  6929  6929 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-15 16:22:39.004  8256  8256 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-15 16:22:39.004  8256  8256 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-15 16:22:39.005  8256  8256 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,08-15 16:22:39.005  8256  8256 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-15 16:22:39.005  8256  8256 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-15 16:22:39.007  1036  1915 I ActivityManager: Killing 7315:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
08-15 16:22:39.041  2034  2034 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-15 16:22:39.077  2034  2862 I GBoardtInterface: onReloaded()
,08-15 16:22:39.080  2034  2034 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-15 16:22:39.082  1036  1052 W libprocessgroup: failed to open /acct/uid_10005/pid_7315/cgroup.procs: No such file or directory
,08-15 16:22:39.085  2747  2781 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-15 16:22:39.093  8185  8185 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-15 16:22:39.094  2747  2763 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-15 16:22:39.099  8135  8135 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-15 16:22:39.101  8135  8135 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-15 16:22:39.106  6929  6929 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-15 16:22:39.109  1905  1905 D ActionManagerService: notifyUserLog: 1000001
08-15 16:22:39.110  6929  6929 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-15 16:22:39.112  2747  4477 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-15 16:22:39.112  2747  4477 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-15 16:22:39.120  1905  1905 D ActionManagerService: notifyUserLog: 1000001
,08-15 16:22:39.123  2747  4477 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-15 16:22:39.123  2747  4477 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-15 16:22:39.123  2747  4477 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-15 16:22:39.123  2747  2763 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-15 16:22:39.123  2747  4477 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-15 16:22:39.123  8256  8256 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-15 16:22:39.124  8256  8256 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-15 16:22:39.124  8256  8256 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-15 16:22:39.125  8256  8256 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-15 16:22:39.125  8256  8256 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-15 16:22:39.127  2034  2034 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-15 16:22:39.127  2034  2034 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-15 16:22:39.128  8185  8185 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-15 16:22:39.131  8185  8185 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-15 16:22:39.131  2034  2034 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-15 16:22:39.131  2034  2034 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
,08-15 16:22:39.135  2034  2034 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide2.html?id=guide_1111111111116_1471007225619&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-15 16:22:39.135  2034  2034 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide2.html?id=guide_1111111111116_1471007225619&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-15 16:22:39.138  1818  1818 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-15 16:22:39.150  2131  2131 I ConfigService: onCreate
,08-15 16:22:39.153  2131  2131 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-15 16:22:39.157  2131  2131 I ConfigService: onBind returning update interface
08-15 16:22:39.159  1818  1818 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-15 16:22:39.162  2131  2131 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-15 16:22:39.162  2131  2131 I ConfigService: onBind returning config service
,08-15 16:22:39.219  2131  2131 I ConfigService: onDestroy
,08-15 16:22:39.223  1818  8337 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-15 16:22:39.237  7117  7117 E SQLiteLog: (3850) statement aborts at 24: [INSERT INTO exclude_apps(package) VALUES (?)] disk I/O error
,08-15 16:22:39.241  7117  7117 E SQLiteDatabase: Error inserting package=com.test.thalitest
08-15 16:22:39.241  7117  7117 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-15 16:22:39.241  7117  7117 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
08-15 16:22:39.241  7117  7117 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:787)
08-15 16:22:39.241  7117  7117 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:926)
08-15 16:22:39.241  7117  7117 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
08-15 16:22:39.241  7117  7117 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1572)
08-15 16:22:39.241  7117  7117 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1442)
08-15 16:22:39.241  7117  7117 E SQLiteDatabase: 	at com.lge.appbox.databases.AppBoxContentProvider.insert(AppBoxContentProvider.java:220)
08-15 16:22:39.241  7117  7117 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:238)
08-15 16:22:39.241  7117  7117 E SQLiteDatabase: 	at android.content.ContentResolver.insert(ContentResolver.java:1223)
08-15 16:22:39.241  7117  7117 E SQLiteDatabase: 	at com.lge.appbox.manager.PreloadListManagerHelper.addExcludeApp(PreloadListManagerHelper.java:134)
08-15 16:22:39.241  7117  7117 E SQLiteDatabase: 	at com.lge.appbox.manager.PreloadListManagerHelper.addExcludeAppInternal(PreloadListManagerHelper.java:115)
08-15 16:22:39.241  7117  7117 E SQLiteDatabase: 	at com.lge.appbox.manager.PreloadListManagerHelper.onRemoveAppEvent(PreloadListManagerHelper.java:100)
08-15 16:22:39.241  7117  7117 E SQLiteDatabase: 	at com.lge.appbox.manager.PreloadListManagerHelper.updateExDb(PreloadListManagerHelper.java:65)
08-15 16:22:39.241  7117  7117 E SQLiteDatabase: 	at com.lge.appbox.manager.PreloadListManagerHelper.onReceive(PreloadListManagerHelper.java:46)
08-15 16:22:39.241  7117  7117 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2586)
08-15 16:22:39.241  7117  7117 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:148)
08-15 16:22:39.241  7117  7117 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1360)
08-15 16:22:39.241  7117  7117 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-15 16:22:39.241  7117  7117 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-15 16:22:39.241  7117  7117 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-15 16:22:39.241  7117  7117 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-15 16:22:39.241  7117  7117 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-15 16:22:39.241  7117  7117 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-15 16:22:39.241  7117  7117 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-15 16:22:39.258  5989  8344 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
,08-15 16:22:39.272  1818  4666 I Icing   : doRemovePackageData com.test.thalitest
,08-15 16:22:39.273  1818  8345 I PeopleContactsSync: CP2 sync disabled
08-15 16:22:39.275  2371  8346 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-15 16:22:39.305  1036  2025 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8348 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
08-15 16:22:39.332  2131  2320 I art     : Explicit concurrent mark sweep GC freed 7325(434KB) AllocSpace objects, 0(0B) LOS objects, 52% free, 29MB/61MB, paused 696us total 18.824ms
,08-15 16:22:39.334  1818  4666 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-1 for write failed: Read-only file system
08-15 16:22:39.334  1818  4666 E Icing   : Could not init tag ds.tag.corpusid-1
08-15 16:22:39.334  1818  4666 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-13 for write failed: Read-only file system
08-15 16:22:39.334  1818  4666 E Icing   : Could not init tag ds.tag.corpusid-13
08-15 16:22:39.334  1818  4666 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-7 for write failed: Read-only file system
08-15 16:22:39.334  1818  4666 E Icing   : Could not init tag ds.tag.corpusid-7
08-15 16:22:39.334  1818  4666 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-8 for write failed: Read-only file system
08-15 16:22:39.334  1818  4666 E Icing   : Could not init tag ds.tag.corpusid-8
08-15 16:22:39.336  1818  4666 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-9 for write failed: Read-only file system
08-15 16:22:39.336  1818  4666 E Icing   : Could not init tag ds.tag.corpusid-9
08-15 16:22:39.336  1818  4666 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.deleted for write failed: Read-only file system
08-15 16:22:39.336  1818  4666 E Icing   : Could not init tag ds.tag.deleted
08-15 16:22:39.336  1818  4666 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.status for write failed: Read-only file system
08-15 16:22:39.336  1818  4666 E Icing   : Writing status failed
08-15 16:22:39.340  1818  8347 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
08-15 16:22:39.340  1818  8347 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-15 16:22:39.340  1818  8347 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-15 16:22:39.340  1818  8347 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-15 16:22:39.340  1818  8347 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-15 16:22:39.340  1818  8347 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-15 16:22:39.340  1818  8347 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-15 16:22:39.340  1818  8347 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-15 16:22:39.340  1818  8347 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-15 16:22:39.340  1818  8347 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-15 16:22:39.340  1818  8347 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-15 16:22:39.340  1818  8347 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-15 16:22:39.340  1818  8347 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-15 16:22:39.340  1818  8347 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-15 16:22:39.340  1818  8347 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-15 16:22:39.340  1818  8347 E SQLiteDatabase: 	at com.google.android.gms.drive.database.k.b(SourceFile:502)
08-15 16:22:39.340  1818  8347 E SQLiteDatabase: 	at com.google.android.gms.drive.database.k.a(SourceFile:496)
08-15 16:22:39.340  1818  8347 E SQLiteDatabase: 	at com.google.android.gms.dri,ve.database.l.run(SourceFile:519)
08-15 16:22:39.340  1818  8342 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
08-15 16:22:39.340  1818  8342 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-15 16:22:39.340  1818  8342 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-15 16:22:39.340  1818  8342 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-15 16:22:39.340  1818  8342 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-15 16:22:39.340  1818  8342 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-15 16:22:39.340  1818  8342 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-15 16:22:39.340  1818  8342 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-15 16:22:39.340  1818  8342 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-15 16:22:39.340  1818  8342 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-15 16:22:39.340  1818  8342 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-15 16:22:39.340  1818  8342 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-15 16:22:39.340  1818  8342 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-15 16:22:39.340  1818  8342 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-15 16:22:39.340  1818  8342 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-15 16:22:39.340  1818  8342 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.d.e.e(SourceFile:98)
08-15 16:22:39.340  1818  8342 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.d.e.a(SourceFile:212)
08-15 16:22:39.340  1818  8342 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:47)
08-15 16:22:39.340  1818  8342 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-15 16:22:39.340  1818  8342 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-15 16:22:39.340  1818  8342 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-15 16:22:39.340  1818  8342 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-15 16:22:39.341  1818  8342 E SQLiteOpenHelper: Couldn't open metrics.db for writing (will try read-only):
08-15 16:22:39.341  1818  8342 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-15 16:22:39.341  1818  8342 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-15 16:22:39.341  1818  8342 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-15 16:22:39.341  1818  8342 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-15 16:22:39.341  1818  8342 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-15 16:22:39.341  1818  8342 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-15 16:22:39.341  1818  8342 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-15 16:22:39.341  1818  8342 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-15 16:22:39.341  1818  8,342 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-15 16:22:39.341  1818  8342 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-15 16:22:39.341  1818  8342 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-15 16:22:39.341  1818  8342 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-15 16:22:39.341  1818  8342 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-15 16:22:39.341  1818  8342 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-15 16:22:39.341  1818  8342 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.d.e.e(SourceFile:98)
08-15 16:22:39.341  1818  8342 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.d.e.a(SourceFile:212)
08-15 16:22:39.341  1818  8342 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:47)
08-15 16:22:39.341  1818  8342 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-15 16:22:39.341  1818  8342 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-15 16:22:39.341  1818  8342 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:135)
08-15 16:22:39.341  1818  8342 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-15 16:22:39.342  2371  2477 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-15 16:22:39.342  1818  8342 W SQLiteOpenHelper: Opened metrics.db in read-only mode
08-15 16:22:39.343  1818  8342 E SQLiteLog: (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
--------- beginning of crash
08-15 16:22:39.344  1818  8347 E AndroidRuntime: FATAL EXCEPTION: Open database in background
08-15 16:22:39.344  1818  8347 E AndroidRuntime: Process: com.google.android.gms, PID: 1818
08-15 16:22:39.344  1818  8347 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-15 16:22:39.344  1818  8347 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-15 16:22:39.344  1818  8347 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-15 16:22:39.344  1818  8347 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-15 16:22:39.344  1818  8347 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-15 16:22:39.344  1818  8347 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-15 16:22:39.344  1818  8347 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-15 16:22:39.344  1818  8347 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-15 16:22:39.344  1818  8347 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-15 16:22:39.344  1818  8347 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-15 16:22:39.344  1818  8347 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-15 16:22:39.344  1818  8347 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-15 16:22:39.344  1818  8347 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-15 16:22:39.344  1818  8347 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-15 16:22:39.344  1818  8347 E AndroidRuntime: 	at com.google.android.gms.drive.database.k.b(SourceFile:502)
08-15 16:22:39.344  1818  8347 E AndroidRuntime: 	at com.google.android.gms.drive.database.k.a(SourceFile:496)
08-15 16:22:39.344  1818  8347 E AndroidRuntime: 	at com.google.android.gms.drive.database.l.run(SourceFile:519)
08-15 16:22:39.346  1818  8343 W GmsApplication: Using Auth Proxy for data requests.
08-15 16:22:39.348  1818  8342 I Process : Sending signal. PID: 1818 SIG: 9
08-15 16:22:39.354  1036  8359 E DropBoxManagerService: Can't write: system_app_crash
08-15 16:22:39.354  1036  8359 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop131.tmp: open failed: EROFS (Read-only file system)
08-15 16:22:39.354  1036  8359 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-15 16:22:39.354  1036  8359 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-15 16:22:39.354  1036  8359 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-15 16:22:39.354  1036  8359 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-15 16:22:39.354  1036  8359 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-15 16:22:39.354  1036  8359 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
08-15 16:22:39.354  1036  8359 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-15 16:22:39.354  1036  8359 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-15 16:22:39.354  1036  8359 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-15 16:22:39.354  1036  8359 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-15 16:22:39.354  1036  8359 E DropBoxManagerService: 	... 5 more
08-15 16:22:39.355  2371  2477 D ContactsProvider2ForLG: performBackgroundTask SQLiteDiskIOException during query
08-15 16:22:39.355  2371  2477 D ContactsProvider2ForLG: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-15 16:22:39.355  2371  2477 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-15 16:22:39.355  2371  2477 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:560)
08-15 16:22:39.355  2371  2477 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-15 16:22:39.355  2371  2477 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-15 16:22:39.355  2371  2477 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-15 16:22:39.355  2371  2477 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-15 16:22:39.355  2371  2477 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:394)
08-15 16:22:39.355  2371  2477 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:363)
08-15 16:22:39.355  2371  2477 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:974)
08-15 16:22:39.355  2371  2477 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactsProvider2ForLG.performBackgroundTask(ContactsProvider2ForLG.java:375)
08-15 16:22:39.355  2371  2477 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:748)
08-15 16:22:39.355  2371  2477 D ContactsProvider2ForLG: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-15 16:22:39.355  2371  2477 D ContactsProvider2ForLG: 	at android.os.Looper.loop(Looper.java:135)
08-15 16:22:39.355  2371  2477 D ContactsProvider2ForLG: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-15 16:22:39.365  2371  8346 E SQLiteLog: (3850) statement aborts at 37: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,08-15 16:22:39.367  2371  8346 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-15 16:22:39.367  2371  8346 E AndroidRuntime: Process: android.process.acore, PID: 2371
08-15 16:22:39.367  2371  8346 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-15 16:22:39.367  2371  8346 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-15 16:22:39.367  2371  8346 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:739)
08-15 16:22:39.367  2371  8346 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:892)
08-15 16:22:39.367  2371  8346 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-15 16:22:39.367  2371  8346 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1600)
08-15 16:22:39.367  2371  8346 E AndroidRuntime: 	at com.android.providers.contacts.util.DbModifierWithNotification.delete(DbModifierWithNotification.java:161)
08-15 16:22:39.367  2371  8346 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailContentTable.delete(VoicemailContentTable.java:229)
08-15 16:22:39.367  2371  8346 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailContentProvider.delete(VoicemailContentProvider.java:135)
08-15 16:22:39.367  2371  8346 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
08-15 16:22:39.367  2371  8346 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1315)
08-15 16:22:39.367  2371  8346 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-15 16:22:39.367  2371  8346 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-15 16:22:39.367  2371  8346 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-15 16:22:39.367  2371  8346 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-15 16:22:39.367  2371  8346 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
08-15 16:22:39.367  2371  8346 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-15 16:22:39.375  1036  1470 D WifiService: Client connection lost with reason: 4
08-15 16:22:39.378  1036  8368 E DropBoxManagerService: Can't write: system_app_crash
08-15 16:22:39.378  1036  8368 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop132.tmp: open failed: EROFS (Read-only file system)
08-15 16:22:39.378  1036  8368 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-15 16:22:39.378  1036  8368 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-15 16:22:39.378  1036  8368 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-15 16:22:39.378  1036  8368 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-15 16:22:39.378  1036  8368 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-15 16:22:39.378  1036  8368 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
08-15 16:22:39.378  1036  8368 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-15 16:22:39.378  1036  8368 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-15 16:22:39.378  1036  8368 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-15 16:22:39.378  1036  8368 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-15 16:22:39.378  1036  8368 E DropBoxManagerService: 	... 5 more
08-15 16:22:39.379  4483  4508 E SQLiteDatabase: Error inserting f004=13 f005=8348 f002=1471270959334 f003=com.lge.email f006=10023
08-15 16:22:39.379  4483  4508 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
08-15 16:22:39.379  4483  4508 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
08-15 16:22:39.379  4483  4508 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:787)
08-15 16:22:39.379  4483  4508 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:926)
08-15 16:22:39.379  4483  4508 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
08-15 16:22:39.379  4483  4508 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1572)
08-15 16:22:39.379  4483  4508 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1442)
08-15 16:22:39.379  4483  4508 E SQLiteDatabase: 	at com.lge.mlt.MptCommonLogProvider.insert(MptCommonLogProvider.java:706)
08-15 16:22:39.379  4483  4508 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:238)
08-15 16:22:39.379  4483  4508 E SQLiteDatabase: 	at android.content.ContentResolver.insert(ContentResolver.java:1223)
08-15 16:22:39.379  4483  4508 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService.insertProcessInfoLog(MltMonitorService.java:2584)
08-15 16:22:39.379  4483  4508 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService.access$2700(MltMonitorService.java:38)
08-15 16:22:39.379  4483  4508 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService$DbFlushManager$1.handleMessage(MltMonitorService.java:3409)
08-15 16:22:39.379  4483  4508 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-15 16:22:39.379  4483  4508 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-15 16:22:39.379  4483  4508 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService$DbFlushManager.run(MltMonitorService.java:3518)
08-15 16:22:39.393  8348  8348 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-15 16:22:39.393  8348  8348 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-15 16:22:39.394  8348  8348 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-15 16:22:39.394  8348  8348 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-15 16:22:39.433  8348  8348 E SQLiteDatabase: Failed to open database '/data/data/com.lge.email/databases/Downloads.db'.
08-15 16:22:39.433  8348  8348 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-15 16:22:39.433  8348  8348 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-15 16:22:39.433  8348  8348 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-15 16:22:39.433  8348  8348 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-15 16:22:39.433  8348  8348 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-15 16:22:39.433  8348  8348 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-15 16:22:39.433  8348  8348 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-15 16:22:39.433  8348  8348 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-15 16:22:39.433  8348  8348 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-15 16:22:39.433  8348  8348 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-15 16:22:39.433  8348  8348 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-15 16:22:39.433  8348  8348 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-15 16:22:39.433  8348  8348 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-15 16:22:39.433  8348  8348 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-15 16:22:39.433  8348  8348 E SQLiteDatabase: 	at com.lge.email.ui.largefile.DownloadProvider.onCreate(DownloadProvider.java:51)
08-15 16:22:39.433  8348  8348 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
08-15 16:22:39.433  8348  8348 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
08-15 16:22:39.433  8348  8348 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
08-15 16:22:39.433  8348  8348 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-15 16:22:39.433  8348  8348 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-15 16:22:39.433  8348  8348 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-15 16:22:39.433  8348  8348 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-15 16:22:39.433  8348  8348 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-15 16:22:39.433  8348  8348 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-15 16:22:39.433  8348  8348 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-15 16:22:39.433  8348  8348 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-15 16:22:39.433  8348  8348 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-15 16:22:39.433  8348  8348 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-15 16:2,2:39.433  8348  8348 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-15 16:22:39.433  8348  8348 W System.err: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-15 16:22:39.433  8348  8348 W System.err: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-15 16:22:39.433  8348  8348 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-15 16:22:39.433  8348  8348 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-15 16:22:39.434  8348  8348 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-15 16:22:39.434  8348  8348 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-15 16:22:39.434  8348  8348 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-15 16:22:39.434  8348  8348 W System.err: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-15 16:22:39.434  8348  8348 W System.err: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-15 16:22:39.434  8348  8348 W System.err: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-15 16:22:39.434  8348  8348 W System.err: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-15 16:22:39.434  8348  8348 W System.err: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-15 16:22:39.434  8348  8348 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-15 16:22:39.434  8348  8348 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-15 16:22:39.434  8348  8348 W System.err: 	at com.lge.email.ui.largefile.DownloadProvider.onCreate(DownloadProvider.java:51)

```
