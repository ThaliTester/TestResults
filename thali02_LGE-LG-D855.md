#### Test 84265062e3ffea4_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
09-07 12:06:00.091  1592  1592 I [SystemUI]Clock: called onTimeUpdated()
09-07 12:06:00.103  1592  1592 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 12:06:00.103  1592  1592 I [SystemUI]DateView: called onTimeUpdated()
09-07 12:06:00.104  1592  1592 I [SystemUI]DateView: called onTimeUpdated()
09-07 12:06:00.104  1592  1592 D KeyguardUpdateMonitor: handleTimeUpdate
,09-07 12:06:07.669  6783  6783 D AndroidRuntime: 
09-07 12:06:07.669  6783  6783 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-07 12:06:07.678  6783  6783 D AndroidRuntime: CheckJNI is OFF
09-07 12:06:07.879  6783  6783 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-07 12:06:07.890  1037  1564 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-07 12:06:07.906  1930  1945 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
09-07 12:06:07.912  1037  1564 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
09-07 12:06:07.914  1037  1564 D ActivityManager: setTaskToReturnTo : TaskRecord{234aa599 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-07 12:06:07.914  1037  1564 D ActivityManager: setTaskToReturnTo : TaskRecord{234aa599 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-07 12:06:07.916  1037  1564 D WindowStateEx: AppWindowTokenEx init.. 
09-07 12:06:07.917   346   356 E GBMv2   : DFP En is all cleared set to be enabled
09-07 12:06:07.945  1037  1564 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6798 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-07 12:06:07.948  6783  6783 D AndroidRuntime: Shutting down VM
09-07 12:06:08.002  1930  1946 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
09-07 12:06:08.003  1930  1946 D SplitWindowPolicy: topRunningActivity=ActivityInfo{23c49b8b co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
09-07 12:06:08.003  1930  4431 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
09-07 12:06:08.004  1930  4431 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3a9cc468 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
09-07 12:06:08.069  6798  6798 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
,09-07 12:06:08.180  6798  6798 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,09-07 12:06:08.191  6798  6798 I LibraryLoader: Loading: webviewchromium
09-07 12:06:08.195  6798  6798 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 2418-2423)
,09-07 12:06:08.195  6798  6798 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-07 12:06:08.221  6798  6798 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3e0cc071}
,09-07 12:06:08.225  6798  6798 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-07 12:06:08.226  6798  6798 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
09-07 12:06:08.242  6798  6798 I BrowserStartupController: Initializing chromium process, renderers=0
,09-07 12:06:08.244  6798  6798 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-07 12:06:08.265  6798  6798 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
09-07 12:06:08.266  6798  6798 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
,09-07 12:06:08.266  6798  6798 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
09-07 12:06:08.272   313  1370 V AudioPolicyService: registerClient() client 0xb558a960, uid 10118
09-07 12:06:08.284  1037  1119 D BluetoothManagerService: Message: 20
09-07 12:06:08.284  1037  1119 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1e7d2d5b:true
,09-07 12:06:08.287  6798  6798 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-07 12:06:08.287  6798  6798 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-07 12:06:08.287  6798  6798 I Adreno-EGL: Build Date: 12/12/14 금
09-07 12:06:08.287  6798  6798 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-07 12:06:08.287  6798  6798 I Adreno-EGL: Remote Branch: 
09-07 12:06:08.287  6798  6798 I Adreno-EGL: Local Patches: 
09-07 12:06:08.287  6798  6798 I Adreno-EGL: Reconstruct Branch: 
09-07 12:06:08.400  6798  6838 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,09-07 12:06:08.403  6798  6798 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
09-07 12:06:08.425  6798  6798 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-07 12:06:08.431  6798  6798 W AwContents: onDetachedFromWindow called when already detached. Ignoring
09-07 12:06:08.435  6798  6798 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
09-07 12:06:08.438  6798  6798 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
09-07 12:06:08.438  6798  6798 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,09-07 12:06:08.455  6798  6798 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,09-07 12:06:08.464  6798  6798 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-07 12:06:08.464  6798  6798 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-07 12:06:08.501  1037  1100 W ActivityManager: Activity pause timeout for ActivityRecord{3293505e u0 com.test.thalitest/.MainActivity t6}
,09-07 12:06:08.513  6798  6850 D OpenGLRenderer: Render dirty regions requested: true
09-07 12:06:08.513  6798  6850 I OpenGLRenderer: Initialized EGL, version 1.4
09-07 12:06:08.522  6798  6850 D OpenGLRenderer: Enabling debug mode 0
,09-07 12:06:08.533  6798  6798 D Atlas   : Validating map...
,09-07 12:06:08.538  1037  1893 D SplitWindow: check instance of lgWin Window{8d3ed7d u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-07 12:06:08.579  6798  6848 D LgDataFeature: LgDataFeature() Constructor: none
09-07 12:06:08.579  6798  6848 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-07 12:06:08.671  1037  1120 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +671ms (total +753ms)
,09-07 12:06:08.672  6798  6798 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3cc215f4 time:162900
09-07 12:06:08.674  1037  1120 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3293505e u0 com.test.thalitest/.MainActivity t6} time:162902
,09-07 12:06:08.799  6798  6798 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
09-07 12:06:08.799  6798  6798 I chromium: 
,09-07 12:06:08.849  6798  6798 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-07 12:06:08.974  6798  6848 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
09-07 12:06:08.974  6798  6848 I chromium: 
,09-07 12:06:09.126  6798  6864 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435051008
,09-07 12:06:09.143  6798  6864 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-07 12:06:09.143  6798  6864 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-07 12:06:09.143  6798  6864 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-07 12:06:09.143  6798  6864 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-07 12:06:09.143  6798  6864 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-07 12:06:09.144  6798  6864 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e8cb878 added. We now have 1 listener(s)
,09-07 12:06:09.157  1037  1929 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-07 12:06:09.165  6798  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
09-07 12:06:09.168  6798  6864 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-07 12:06:09.172  6798  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 12:06:09.173  6798  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-07 12:06:09.186  6798  6864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-07 12:06:09.186  6798  6864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-07 12:06:09.186  6798  6864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-07 12:06:09.186  6798  6864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
09-07 12:06:09.186  6798  6864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-07 12:06:09.186  6798  6864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-07 12:06:09.186  6798  6864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-07 12:06:09.186  6798  6864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-07 12:06:09.186  6798  6864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-07 12:06:09.186  6798  6864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-07 12:06:09.186  6798  6864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-07 12:06:09.186  6798  6864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-07 12:06:09.186  6798  6864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-07 12:06:09.186  6798  6864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-07 12:06:09.186  6798  6864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a92b4b7 added. We now have 1 listener(s)
,09-07 12:06:09.187  6798  6864 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 12:06:09.191  1037  1533 D WifiService: New client listening to asynchronous messages
09-07 12:06:09.196  6798  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-07 12:06:09.196  6798  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-07 12:06:09.196  6798  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-07 12:06:09.196  6798  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-07 12:06:09.196  6798  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-07 12:06:09.201  6798  6864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 12:06:09.202  1037  1564 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 12:06:09.204  6798  6864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
09-07 12:06:09.215  6798  6864 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
,09-07 12:06:09.215  6798  6864 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 12:06:09.215  6798  6864 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:06:09.215  6798  6864 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 12:06:09.215  6798  6864 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 12:06:09.215  6798  6864 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 12:06:09.215  6798  6864 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 12:06:09.215  6798  6864 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 12:06:09.215  6798  6864 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 12:06:09.216  6798  6864 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-07 12:06:09.216  6798  6864 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 12:06:09.219  6798  6798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 12:06:09.222  6798  6798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 12:06:09.223  6798  6864 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-07 12:06:09.259  6798  6798 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-07 12:06:09.563   346   358 E GBMv2   : DFP En is all cleared set to be enabled
09-07 12:06:09.564   346   358 E GBMv2   : Set value is all cleared set the max
09-07 12:06:09.564   346   358 I GBMv2   : DFP Enabled. Ignore VFP set
,09-07 12:06:10.350  6798  6867 W jxcore-log: Initializing JXcore engine
09-07 12:06:10.351  6798  6867 W jxcore-log: JXcore engine is ready
,09-07 12:06:10.414  6867  6867 W Thread-807: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[7399]" dev="sockfs" ino=7399 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
09-07 12:06:10.414  6867  6867 W Thread-807: type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
09-07 12:06:10.414  6867  6867 W Thread-807: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[8559]" dev="sockfs" ino=8559 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,09-07 12:06:10.414  6867  6867 W Thread-807: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
09-07 12:06:10.414  6867  6867 W Thread-807: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[31421]" dev="sockfs" ino=31421 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
09-07 12:06:10.449  6798  6867 W jxcore-log: Starting JXcore engine
,09-07 12:06:10.605  6798  6867 W jxcore-log: Platform android
09-07 12:06:10.605  6798  6867 W jxcore-log: 
09-07 12:06:10.605  6798  6867 W jxcore-log: Process ARCH arm
09-07 12:06:10.605  6798  6867 W jxcore-log: 
,09-07 12:06:10.989  6798  6867 I jxcore-log: JXcore Cordova bridge is ready!
09-07 12:06:10.989  6798  6867 I jxcore-log: 
09-07 12:06:10.990  6798  6867 W jxcore-log: JXcore engine is started
,09-07 12:06:10.998  6798  6864 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
09-07 12:06:11.005  6798  6798 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-07 12:06:21.529  6798  6867 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-07 12:06:21.529  6798  6867 I jxcore-log: 
,09-07 12:06:21.532  6798  6867 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-07 12:06:21.532  6798  6867 I jxcore-log: 
,09-07 12:06:21.537  6798  6867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 12:06:21.537  6798  6867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:06:21.537  6798  6867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 12:06:21.537  6798  6867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 12:06:21.537  6798  6867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 12:06:21.537  6798  6867 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 12:06:21.537  6798  6867 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 12:06:21.537  6798  6867 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 12:06:21.539  6798  6867 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 12:06:21.542  6798  6867 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-07 12:06:21.542  6798  6867 I jxcore-log: 
09-07 12:06:21.544  6798  6867 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-07 12:06:21.544  6798  6867 I jxcore-log: 
,09-07 12:06:22.041  6798  6867 D executeNativeTests: Running unit tests
,09-07 12:06:22.122  6798  6867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-07 12:06:22.122  6798  6867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3edc8148 added. We now have 2 listener(s)
09-07 12:06:22.123  1037  1774 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 12:06:22.125  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-07 12:06:22.125  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 12:06:22.125  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 12:06:22.125  6798  6867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 12:06:22.125  6798  6867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38f72be1 added. We now have 2 listener(s)
09-07 12:06:22.125  6798  6867 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 12:06:22.126  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-07 12:06:22.128  6798  6867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 12:06:22.130  6798  6867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 12:06:22.130  6798  6867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:06:22.130  6798  6867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 12:06:22.130  6798  6867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 12:06:22.130  6798  6867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 12:06:22.130  6798  6867 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 12:06:22.130  6798  6867 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 12:06:22.130  6798  6867 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 12:06:22.131  6798  6867 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 12:06:22.132  6798  6867 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 12:06:22.133  6798  6798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 12:06:22.134  6798  6798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 12:06:22.137  6798  6867 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-07 12:06:22.139  6798  6867 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-07 12:06:22.139  6798  6867 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-07 12:06:22.141  6798  6867 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-07 12:06:22.142  6798  6867 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-07 12:06:22.142  6798  6867 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-07 12:06:22.142  6798  6867 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-07 12:06:22.142  6798  6867 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-07 12:06:22.142  6798  6867 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 12:06:22.143  6798  6867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 12:06:22.143  6798  6867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 12:06:22.144  6798  6867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:06:22.144  6798  6867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:06:22.144  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 12:06:22.144  6798  6867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 12:06:22.144  6798  6867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3edc8148 removed from the list
09-07 12:06:22.144  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:06:22.144  6798  6867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38f72be1 removed from the list
09-07 12:06:22.144  6798  6867 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:06:22.144  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:06:22.145  6798  6867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:06:22.145  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:06:22.147  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 12:06:22.147  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 12:06:22.147  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:06:22.147  6798  6867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38f72be1 not in the list
09-07 12:06:22.149  6798  6867 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-07 12:06:22.149  6798  6867 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 12:06:22.149  6798  6867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 12:06:22.149  6798  6867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operati,on, skipping...
09-07 12:06:22.149  6798  6867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:06:22.149  6798  6867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:06:22.149  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:06:22.149  6798  6867 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3edc8148 not in the list
09-07 12:06:22.149  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:06:22.149  6798  6867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38f72be1 not in the list
09-07 12:06:22.149  6798  6867 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:06:22.149  6798  6867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:06:22.149  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:06:22.149  6798  6867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:06:22.149  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:06:22.150  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 12:06:22.150  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
09-07 12:06:22.150  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:06:22.150  6798  6867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38f72be1 not in the list
09-07 12:06:22.154  6798  6867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-07 12:06:22.154  6798  6867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-07 12:06:22.154  6798  6867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-07 12:06:22.154  6798  6867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-07 12:06:22.154  6798  6867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-07 12:06:22.154  6798  6867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-07 12:06:22.154  6798  6867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-07 12:06:22.154  6798  6867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-07 12:06:22.154  6798  6867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-07 12:06:22.154  6798  6867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-07 12:06:22.155  6798  6867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-07 12:06:22.155  6798  6867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,09-07 12:06:22.155  6798  6867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,09-07 12:06:22.155  6798  6867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-07 12:06:22.155  6798  6867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-07 12:06:22.155  6798  6867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-07 12:06:22.155  6798  6867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-07 12:06:22.155  6798  6867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-07 12:06:22.155  6798  6867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-07 12:06:22.155  6798  6867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-07 12:06:22.155  6798  6867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-07 12:06:22.155  6798  6867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-07 12:06:22.155  6798  6867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-07 12:06:22.155  6798  6867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-07 12:06:22.155  6798  6867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-07 12:06:22.155  6798  6867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-07 12:06:22.155  6798  6867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-07 12:06:22.155  6798  6867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-07 12:06:22.155  6798  6867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-07 12:06:22.155  6798  6867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-07 12:06:22.155  6798  6867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-07 12:06:22.155  6798  6867 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 12:06:22.155  6798  6867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 12:06:22.155  6798  6867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 12:06:22.155  6798  6867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:06:22.155  6798  6867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:06:22.155  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:06:22.155  6798  6867 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3edc8148 not in the list
09-07 12:06:22.155  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:06:22.155  6798  6867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38f72be1 not in the list
09-07 12:06:22.155  6798  6867 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:06:22.155  6798  6867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:06:22.155  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:06:22.155  6798  6867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:06:22.155  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:06:22.156  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 12:06:22.156  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 12:06:22.156  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:06:22.156  6798  6867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38f72be1 not in the list
09-07 12:06:22.157  6798  6867 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-07 12:06:22.158  6798  6867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 12:06:22.160  6798  6867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 12:06:22.160  6798  6867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:06:22.160  6798  6867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 12:06:22.160  6798  6867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 12:06:22.160  6798  6867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true,
09-07 12:06:22.160  6798  6867 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 12:06:22.160  6798  6867 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 12:06:22.160  6798  6867 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 12:06:22.161  6798  6867 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 12:06:22.161  6798  6867 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-07 12:06:22.162  6798  6798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
09-07 12:06:22.163  6798  6798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 12:06:22.163  6798  6867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 12:06:22.163  6798  6867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-07 12:06:22.163  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-07 12:06:22.163  6798  6867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 12:06:22.163  6798  6867 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-07 12:06:22.167  6798  6867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-07 12:06:22.167  1037  1564 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-07 12:06:22.171  6798  6867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-07 12:06:22.176  6798  6867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-07 12:06:22.178  6798  6867 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage,
09-07 12:06:22.178  6798  6867 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-07 12:06:22.179  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 12:06:22.181  6798  6867 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-07 12:06:22.181  6798  6867 I io.jxcore.node.ConnectionHelper: start: OK
09-07 12:06:22.183  6798  6867 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-07 12:06:22.183  6798  6867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 12:06:22.183  6798  6867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 12:06:22.184  6798  6867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:06:22.184  6798  6867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:06:22.184  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 12:06:22.184  6798  6867 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3edc8148 not in the list
09-07 12:06:22.184  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:06:22.184  6798  6867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38f72be1 not in the list
09-07 12:06:22.184  6798  6867 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:06:22.184  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:06:22.184  6798  6867 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-07 12:06:22.186  6798  6867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 12:06:22.187  6798  6867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 12:06:22.187  6798  6867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:06:22.187  6798  6867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 12:06:22.187  6798  6867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 12:06:22.187  6798  6867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 12:06:22.187  6798  6867 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 12:06:22.187  6798  6867 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 12:06:22.187  6798  6867 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 12:06:22.188  6798  6867 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 12:06:22.188  6798  6867 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-07 12:06:22.189  6798  6798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
09-07 12:06:22.190  6798  6798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 12:06:22.190  6798  6867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 12:06:22.190  6798  6867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-07 12:06:22.190  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false,
09-07 12:06:22.190  6798  6867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 12:06:22.190  6798  6867 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-07 12:06:22.193  6798  6867 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-07 12:06:22.193  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 12:06:22.194  6798  6867 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,09-07 12:06:22.194  6798  6867 I io.jxcore.node.ConnectionHelper: start: OK
09-07 12:06:22.195  6798  6867 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 12:06:22.195  6798  6867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 12:06:22.195  6798  6867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 12:06:22.196  6798  6867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 12:06:22.196  6798  6867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:06:22.196  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 12:06:22.196  6798  6867 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3edc8148 not in the list
09-07 12:06:22.196  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:06:22.196  6798  6867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38f72be1 not in the list
,09-07 12:06:22.196  6798  6867 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:06:22.196  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:06:22.196  6798  6867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:06:22.196  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:06:22.197  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 12:06:22.197  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
09-07 12:06:22.198  6798  6867 D BluetoothLeScanner: could not find callback wrapper
09-07 12:06:22.198  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 12:06:22.198  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:06:22.198  6798  6867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38f72be1 not in the list
09-07 12:06:22.199  6798  6867 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-07 12:06:22.200  6798  6867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 12:06:22.202  6798  6867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
09-07 12:06:22.202  6798  6867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:06:22.202  6798  6867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 12:06:22.202  6798  6867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 12:06:22.202  6798  6867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 12:06:22.202  6798  6867 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 12:06:22.202  6798  6867 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 12:06:22.202  6798  6867 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 12:06:22.203  6798  6867 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 12:06:22.203  6798  6867 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 12:06:22.204  6798  6798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 12:06:22.205  6798  6798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 12:06:22.205  6798  6867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 12:06:22.205  6798  6867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-07 12:06:22.205  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-07 12:06:22.205  6798  6867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 12:06:22.205  6798  6867 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-07 12:06:22.277  1037  1875 I art     : Explicit concurrent mark sweep GC freed 33731(1582KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/64MB, paused 1.694ms total 71.146ms
,09-07 12:06:22.279  6798  6867 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-07 12:06:22.279  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 12:06:22.280  6798  6867 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-07 12:06:22.280  6798  6867 I io.jxcore.node.ConnectionHelper: start: OK
09-07 12:06:22.280  6798  6867 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 12:06:22.280  6798  6867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 12:06:22.280  6798  6867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 12:06:22.281  6798  6867 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 12:06:22.281  6798  6867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 12:06:22.281  6798  6867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 12:06:22.282  6798  6867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:06:22.282  6798  6867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:06:22.282  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 12:06:22.282  6798  6867 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3edc8148 not in the list
09-07 12:06:22.282  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:06:22.282  6798  6867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38f72be1 not in the list
09-07 12:06:22.282  6798  6867 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:06:22.282  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:06:22.282  6798  6867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:06:22.282  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:06:22.283  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 12:06:22.283  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 12:06:22.283  6798  6867 D BluetoothLeScanner: could not find callback wrapper
09-07 12:06:22.283  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 12:06:22.283  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:06:22.283  6798  6867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38f72be1 not in the list
09-07 12:06:22.284  6798  6867 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-07 12:06:22.284  6798  6867 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 12:06:22.284  6798  6867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discov,ery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 12:06:22.284  6798  6867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 12:06:22.284  6798  6867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:06:22.284  6798  6867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:06:22.284  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:06:22.284  6798  6867 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3edc8148 not in the list
09-07 12:06:22.284  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:06:22.285  6798  6867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38f72be1 not in the list
09-07 12:06:22.285  6798  6867 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:06:22.285  6798  6867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:06:22.285  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:06:22.285  6798  6867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:06:22.285  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:06:22.288  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 12:06:22.288  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 12:06:22.289  6798  6867 D BluetoothLeScanner: could not find callback wrapper
09-07 12:06:22.289  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 12:06:22.289  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:06:22.289  6798  6867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38f72be1 not in the list
09-07 12:06:22.290  6798  6867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-07 12:06:22.290  6798  6867 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 12:06:22.290  6798  6867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 12:06:22.290  6798  6867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 12:06:22.290  6798  6867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:06:22.290  6798  6867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:06:22.290  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:06:22.290  6798  6867 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3edc8148 not in the list
09-07 12:06:22.291  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:06:22.291  6798  6867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38f72be1 not in the list
09-07 12:06:22.291  6798  6867 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:06:22.291  6798  6867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:06:22.291  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:06:22.291  6798  6867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:06:22.291  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:06:22.291  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 12:06:22.291  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 12:06:22.292  6798  6867 D BluetoothLeScanner: could not find callback wrapper
09-07 12:06:22.292  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 12:06:22.292  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:06:22.292  6798  6867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38f72be1 not in the list
09-07 12:06:22.292  6798  6867 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-07 12:06:22.293  6798  6867 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 12:06:22.293  6798  6867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 12:06:22.293  6798  6867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 12:06:22.293  6798  6867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:06:22.293  6798  6867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:06:22.293  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:06:22.293  6798  6867 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3edc8148 not in the list
09-07 12:06:22.293  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:06:22.293  6798  6867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38f72be1 not in the list
09-07 12:06:22.293  6798  6867 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:06:22.293  6798  6867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:06:22.293  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:06:22.293  6798  6867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:06:22.293  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:06:22.294  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 12:06:22.294  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 12:06:22.294  6798  6867 D BluetoothLeScanner: could not find callback wrapper
09-07 12:06:22.295  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 12:06:22.295  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:06:22.295  6798  6867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38f72be1 not in the list
09-07 12:06:22.295  6798  6867 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-07 12:06:22.295  6798  6867 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 12:06:22.295  6798  6867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 12:06:22.295  6798  6867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 12:06:22.296  6798  6867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:06:22.296  6798  6867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:06:22.296  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:06:22.296  6798  6867 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3edc8148 not in the list
09-07 12:06:22.296  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:06:22.296  6798  6867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38f72be1 not in the list
09-07 12:06:22.296  6798  6867 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:06:22.296  6798  6867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:06:22.296  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:06:22.296  6798  6867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:06:22.296  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:06:22.297  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 12:06:22.297  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 12:06:22.297  6798  6867 D BluetoothLeScanner: could not find callback wrapper
09-07 12:06:22.297  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 12:06:22.297  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:06:22.297  6798  6867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38f72be1 not in the list
09-07 12:06:22.297  6798  6867 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-07 12:06:22.299  6798  6867 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-07 12:06:22.299  6798  6867 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-07 12:06:22.299  6798  6867 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-07 12:06:22.299  6798  6867 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-07 12:06:22.299  6798  6867 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-07 12:06:22.299  6798  6867 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 12:06:22.299  6798  6867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 12:06:22.299  6798  6867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 12:06:22.300  6798  6867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:06:22.300  6798  6867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:06:22.300  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:06:22.300  6798  6867 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3edc8148 not in the list
09-07 12:06:22.300  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:06:22.300  6798  6867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38f72be1 not in the list
09-07 12:06:22.300  6798  6867 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:06:22.300  6798  6867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:06:22.300  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:06:22.300  6798  6867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:06:22.300  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:06:22.301  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 12:06:22.301  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 12:06:22.302  6798  6867 D BluetoothLeScanner: could not find callback wrapper
09-07 12:06:22.302  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 12:06:22.302  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:06:22.302  6798  6867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38f72be1 not in the list
09-07 12:06:22.304  6798  6867 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 12:06:22.305  6798  6867 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-07 12:06:22.305  6798  6867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-07 12:06:22.314  6798  6867 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 12:06:22.314  6798  6867 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-07 12:06:22.315  6798  6867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-07 12:06:22.315  6798  6867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-07 12:06:22.315  6798  6867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-07 12:06:22.315  6798  6867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-07 12:06:22.315  6798  6867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-07 12:06:22.315  6798  6867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-07 12:06:22.315  6798  6867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-07 12:06:22.315  6798  6867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-07 12:06:22.316  6798  6867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-07 12:06:22.316  6798  6867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-07 12:06:22.316  6798  6867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-07 12:06:22.316  6798  6867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-07 12:06:22.316  6798  6867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-07 12:06:22.316  6798  6867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-07 12:06:22.316  6798  6867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-07 12:06:22.316  6798  6867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-07 12:06:22.316  6798  6867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-07 12:06:22.316  6798  6867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-07 12:06:22.317  6798  6867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-07 12:06:22.317  6798  6867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-07 12:06:22.317  6798  6867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-07 12:06:22.317  6798  6867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-07 12:06:22.317  6798  6867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-07 12:06:22.317  6798  6867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-07 12:06:22.317  6798  6867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-07 12:06:22.317  6798  6867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-07 12:06:22.317  6798  6867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-07 12:06:22.318  6798  6867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-07 12:06:22.318  6798  6867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-07 12:06:22.318  6798  6867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-07 12:06:22.318  6798  6867 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-07 12:06:22.318  6798  6867 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-07 12:06:22.319  6798  6867 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-07 12:06:22.319  6798  6867 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 12:06:22.319  6798  6867 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-07 12:06:22.319  6798  6867 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-07 12:06:22.320  6798  6867 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 12:06:22.320  6798  6867 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-07 12:06:22.320  6798  6867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-07 12:06:22.321  6798  6867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,09-07 12:06:22.322  6798  6867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-07 12:06:22.322  6798  6867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-07 12:06:22.322  6798  6867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-07 12:06:22.322  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-07 12:06:22.323  6798  6867 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-07 12:06:22.323  6798  6867 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 12:06:22.323  6798  6867 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-07 12:06:22.323  6798  6867 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 12:06:22.323  6798  6867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 12:06:22.323  6798  6867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 12:06:22.324  6798  6867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:06:22.324  6798  6867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:06:22.324  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:06:22.325  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-07 12:06:22.326  6798  6867 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3edc8148 not in the list
09-07 12:06:22.326  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:06:22.326  6798  6867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38f72be1 not in the list
09-07 12:06:22.326  6798  6867 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:06:22.326  6798  6867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:06:22.326  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:06:22.326  6798  6867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:06:22.326  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:06:22.327  6798  6881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 871)
09-07 12:06:22.327  6798  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 871
09-07 12:06:22.327  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 12:06:22.327  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 12:06:22.328  6798  6867 D BluetoothLeScanner: could not find callback wrapper
09-07 12:06:22.328  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 12:06:22.328  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:06:22.328  6798  6867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38f72be1 not in the list
09-07 12:06:22.329  6798  6867 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-07 12:06:22.329  6798  6867 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 12:06:22.329  6798  6867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 12:06:22.329  6798  6867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 12:06:22.329  6798  6867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:06:22.329  6798  6867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:06:22.329  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:06:22.329  6798  6867 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3edc8148 not in the list
09-07 12:06:22.329  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:06:22.329  6798  6867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38f72be1 not in the list
09-07 12:06:22.329  6798  6867 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:06:22.329  6798  6867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:06:22.329  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:06:22.329  6798  6867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:06:22.329  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:06:22.330  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 12:06:22.330  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 12:06:22.330  6798  6867 D BluetoothLeScanner: could not find callback wrapper
09-07 12:06:22.330  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 12:06:22.330  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:06:22.330  6798  6867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38f72be1 not in the list
09-07 12:06:22.331  6798  6867 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-07 12:06:22.331  6798  6867 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 12:06:22.331  6798  6867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 12:06:22.331  6798  6867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 12:06:22.331  6798  6867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:06:22.331  6798  6867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:06:22.331  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:06:22.331  6798  6867 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3edc8148 not in the list
09-07 12:06:22.331  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:06:22.331  6798  6867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38f72be1 not in the list
09-07 12:06:22.331  6798  6867 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:06:22.331  6798  6867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:06:22.331  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:06:22.331  6798  6867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:06:22.331  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:06:22.332  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 12:06:22.332  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 12:06:22.333  6798  6867 D BluetoothLeScanner: could not find callback wrapper
09-07 12:06:22.333  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 12:06:22.333  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:06:22.333  6798  6867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38f72be1 not in the list
09-07 12:06:22.333  6798  6867 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-07 12:06:22.333  6798  6867 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-07 12:06:22.333  6798  6867 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-07 12:06:22.334  6798  6867 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-07 12:06:22.334  6798  6867 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-07 12:06:22.334  6798  6867 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-07 12:06:22.334  6798  6867 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-07 12:06:22.334  6798  6867 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-07 12:06:22.334  6798  6867 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-07 12:06:22.334  6798  6867 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-07 12:06:22.334  6798  6867 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-07 12:06:22.334  6798  6867 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-07 12:06:22.334  6798  6867 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 12:06:22.334  6798  6867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 12:06:22.334  6798  6867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 12:06:22.334  6798  6867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:06:22.334  6798  6867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:06:22.334  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:06:22.334  6798  6867 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3edc8148 not in the list
09-07 12:06:22.334  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:06:22.334  6798  6867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38f72be1 not in the list
09-07 12:06:22.334  6798  6867 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:06:22.334  6798  6867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:06:22.334  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:06:22.334  6798  6867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:06:22.334  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:06:22.337  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 12:06:22.337  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 12:06:22.338  6798  6867 D BluetoothLeScanner: could not find callback wrapper
09-07 12:06:22.338  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 12:06:22.338  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:06:22.338  6798  6867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38f72be1 not in the list
09-07 12:06:22.339  6798  6867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:06:22.339  6798  6867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:06:22.339  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:06:22.339  6798  6867 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3edc8148 not in the list
09-07 12:06:22.339  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:06:22.339  6798  6867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38f72be1 not in the list
09-07 12:06:22.339  6798  6867 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:06:22.339  6798  6867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:06:22.339  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:06:22.340  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:06:22.340  6798  6867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38f72be1 not in the list
09-07 12:06:22.340  6798  6867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:06:22.340  6798  6867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:06:22.340  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:06:22.340  6798  6867 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3edc8148 not in the list
09-07 12:06:22.340  6798  6867 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 12:06:22.340  6798  6867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 12:06:22.340  6798  6867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 12:06:22.341  6798  6867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:06:22.341  6798  6867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:06:22.341  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:06:22.341  6798  6867 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3edc8148 not in the list
09-07 12:06:22.341  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:06:22.341  6798  6867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38f72be1 not in the list
09-07 12:06:22.341  6798  6867 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:06:22.341  6798  6867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:06:22.341  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:06:22.341  6798  6867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:06:22.341  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:06:22.341  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 12:06:22.341  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 12:06:22.342  6798  6867 D BluetoothLeScanner: could not find callback wrapper
09-07 12:06:22.342  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 12:06:22.342  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:06:22.342  6798  6867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38f72be1 not in the list
09-07 12:06:22.352  6798  6867 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-07 12:06:22.352  6798  6867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 12:06:22.353  6798  6867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-07 12:06:22.353  6798  6867 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-07 12:06:22.355  6798  6867 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-07 12:06:22.355  6798  6867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-07 12:06:22.355  6798  6798 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-07 12:06:22.355  6798  6867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-07 12:06:22.356  1037  1911 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 12:06:22.357  6798  6884 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-07 12:06:22.357  6798  6867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:06:22.357  4299  4317 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=82
09-07 12:06:22.357  6798  6867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-07 12:06:22.357  6798  6867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-07 12:06:22.357  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-07 12:06:22.357  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:06:22.357  6798  6867 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-07 12:06:22.358  6798  6867 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3edc8148 not in the list
09-07 12:06:22.358  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:06:22.358  6798  6798 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-07 12:06:22.358  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-07 12:06:22.358  6798  6884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-07 12:06:22.358  6798  6867 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-07 12:06:22.358  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-07 12:06:22.358  6798  6867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-07 12:06:22.358  6798  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-07 12:06:22.358  6798  6884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-07 12:06:22.359  6798  6867 D BluetoothLeScanner: could not find callback wrapper
09-07 12:06:22.359  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 12:06:22.359  6798  6867 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-07 12:06:22.359  6798  6867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:06:22.359  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:06:22.359  6798  6867 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 12:06:22.360  6798  6867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38f72be1 not in the list
09-07 12:06:22.360  6798  6798 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 12:06:22.360  6798  6867 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 12:06:22.360  6798  6867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 12:06:22.360  6798  6798 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 12:06:22.360  6798  6867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 12:06:22.360  6798  6867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:06:22.360  6798  6867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:06:22.360  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:06:22.360  6798  6798 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-07 12:06:22.360  6798  6867 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3edc8148 not in the list
09-07 12:06:22.360  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:06:22.360  6798  6867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38f72be1 not in the list
09-07 12:06:22.360  6798  6798 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 12:06:22.360  6798  6867 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:06:22.360  6798  6867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:06:22.360  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:06:22.360  6798  6867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:06:22.360  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:06:22.361  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 12:06:22.361  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 12:06:22.361  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:06:22.361  6798  6867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38f72be1 not in the list
09-07 12:06:22.362  6798  6867 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-07 12:06:22.362  6798  6867 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-07 12:06:22.362  6798  6867 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-07 12:06:22.363  6798  6867 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-07 12:06:22.363  6798  6867 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 12:06:22.363  6798  6867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 12:06:22.363  6798  6867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 12:06:22.363  6798  6867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:06:22.363  6798  6867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:06:22.363  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:06:22.363  6798  6867 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3edc8148 not in the list
09-07 12:06:22.363  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:06:22.363  6798  6867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38f72be1 not in the list
09-07 12:06:22.363  6798  6867 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:06:22.363  6798  6867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:06:22.363  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:06:22.363  6798  6867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:06:22.363  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:06:22.364  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 12:06:22.364  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 12:06:22.364  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:06:22.364  6798  6867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38f72be1 not in the list
09-07 12:06:22.365  1037  1964 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-07 12:06:22.368  1037  1875 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 12:06:22.368  1037  1564 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 12:06:22.369  6798  6867 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 12:06:22.369  6798  6867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 12:06:22.369  6798  6867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 12:06:22.369  6798  6867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:06:22.369  6798  6867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:06:22.369  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:06:22.369  6798  6867 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3edc8148 not in the list
09-07 12:06:22.369  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:06:22.369  6798  6867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38f72be1 not in the list
09-07 12:06:22.369  6798  6867 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:06:22.369  6798  6867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:06:22.369  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:06:22.369  6798  6867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:06:22.369  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:06:22.370  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 12:06:22.370  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 12:06:22.370  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:06:22.370  6798  6867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38f72be1 not in the list
09-07 12:06:22.371  6798  6867 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 12:06:22.371  6798  6867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 12:06:22.371  6798  6867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 12:06:22.371  6798  6867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:06:22.371  6798  6867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:06:22.371  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:06:22.371  6798  6867 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3edc8148 not in the list
09-07 12:06:22.371  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:06:22.371  6798  6867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38f72be1 not in the list
09-07 12:06:22.371  6798  6867 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:06:22.371  6798  6867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:06:22.371  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:06:22.371  6798  6867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:06:22.371  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:06:22.372  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 12:06:22.372  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 12:06:22.372  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:06:22.372  6798  6867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38f72be1 not in the list
09-07 12:06:22.374  6798  6867 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-07 12:06:22.374  6798  6867 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-07 12:06:22.374  6798  6867 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-07 12:06:22.374  6798  6867 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-07 12:06:22.374  6798  6867 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-07 12:06:22.374  6798  6867 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-07 12:06:22.376  6798  6867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-07 12:06:22.377  6798  6867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-07 12:06:22.377  6798  6867 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-07 12:06:22.378  6798  6867 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-07 12:06:22.378  6798  6867 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-07 12:06:22.378  6798  6867 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-07 12:06:22.378  6798  6867 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-07 12:06:22.378  6798  6867 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-07 12:06:22.379  6798  6867 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-07 12:06:22.379  6798  6867 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-07 12:06:22.380  6798  6867 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-07 12:06:22.380  6798  6867 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-07 12:06:22.380  6798  6867 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-07 12:06:22.380  6798  6867 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-07 12:06:22.381  6798  6867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 12:06:22.381  6798  6867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@183416de added. We now have 2 listener(s)
09-07 12:06:22.381  6798  6867 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 12:06:22.382  6798  6867 D BluetoothAdapter: enable(): BT is already enabled..!
09-07 12:06:22.383  1037  2001 D WifiServiceImplEx: setWifiEnabled: true pid=6798, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-07 12:06:22.383  1037  2001 D WifiService: setWifiEnabled: true pid=6798, uid=10118
09-07 12:06:22.383  1037  2001 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-07 12:06:22.385  6798  6867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 12:06:22.385  6798  6867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3ad990bf added. We now have 3 listener(s)
09-07 12:06:22.385  6798  6867 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 12:06:22.388  6798  6867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 12:06:22.388  6798  6867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b77038c added. We now have 4 listener(s)
09-07 12:06:22.388  6798  6867 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 12:06:22.391  6798  6867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 12:06:22.391  6798  6867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2f095ad5 added. We now have 5 listener(s)
09-07 12:06:22.391  6798  6867 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 12:06:22.392  1037  1694 D WifiServiceImplEx: setWifiEnabled: false pid=6798, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-07 12:06:22.393  1037  1694 D WifiService: setWifiEnabled: false pid=6798, uid=10118
09-07 12:06:22.393  1037  1694 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-07 12:06:22.412  1037  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 12:06:22.413  1037  1052 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@34171034 mBinding = false
,09-07 12:06:22.414  1037  1527 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
09-07 12:06:22.414  1037  1527 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
09-07 12:06:22.414  1037  1527 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
09-07 12:06:22.414  1037  1527 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
09-07 12:06:22.415  1037  1527 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
09-07 12:06:22.415  1037  1527 E WifiStateMachine: WifiStateMachine: Leaving Connected state
09-07 12:06:22.415  1037  1527 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-07 12:06:22.415  1037  1527 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-07 12:06:22.415  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-07 12:06:22.415  1037  1527 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-07 12:06:22.415  1037  1527 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-07 12:06:22.416  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-07 12:06:22.416  1037  1037 D Ulp_jni : JNI:system_update. Event-4
09-07 12:06:22.422  1037  1527 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-07 12:06:22.422  1037  1526 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-07 12:06:22.422  1037  1526 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-07 12:06:22.423  1037  1527 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-07 12:06:22.423  2641  2641 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-07 12:06:22.423  1037  1527 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-07 12:06:22.423  1037  1527 D WifiNative-wlan0: doBoolean: SET ps 1
09-07 12:06:22.423  1037  1527 D WifiNative-wlan0: SET ps 1: returned true
09-07 12:06:22.423  1037  2787 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,09-07 12:06:22.428   309   894 D CommandListener: Clearing all IP addresses on wlan0
09-07 12:06:22.428  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-07 12:06:22.429  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-07 12:06:22.429  1037  1037 D Ulp_jni : JNI:system_update. Event-4
09-07 12:06:22.430  1037  1119 D BluetoothManagerService: Message: 2
09-07 12:06:22.431  1037  1119 D BluetoothManagerService: Sending off request.
09-07 12:06:22.431  4299  4322 D LGBluetoothServiceAdapter: [BTUI] Precleanup
09-07 12:06:22.432  4299  4384 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
09-07 12:06:22.432  4299  4384 D BluetoothAdapterProperties: Setting state to 13
09-07 12:06:22.432  4299  4384 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-07 12:06:22.433  4299  4384 D BluetoothAdapterProperties: onBluetoothDisable()
09-07 12:06:22.433  4299  4384 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-07 12:06:22.435  1037  1119 D BluetoothManagerService: Message: 60
09-07 12:06:22.435  1037  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
09-07 12:06:22.435  1037  1119 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
09-07 12:06:22.437  1930  1930 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,09-07 12:06:22.439  1592  1592 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-07 12:06:22.441  4299  4299 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-07 12:06:22.441  4299  4299 D BluetoothMapService: STATE_TURNING_OFF
09-07 12:06:22.441  4299  4299 V BluetoothMapService: Handler(): got msg=4
09-07 12:06:22.442  4299  4299 D BluetoothMapService: MAP Service closeService in
09-07 12:06:22.442  4299  4299 D BluetoothMapMasInstance: MAP Service shutdown
09-07 12:06:22.442  4299  4708 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
09-07 12:06:22.442  4299  4708 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-07 12:06:22.442  4299  4708 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
09-07 12:06:22.442  4299  4708 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
09-07 12:06:22.442  4299  4708 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
09-07 12:06:22.442  4299  4708 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
09-07 12:06:22.442  4299  4708 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
09-07 12:06:22.442  4299  4708 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
09-07 12:06:22.442  4299  4299 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-07 12:06:22.443  4299  4299 V BluetoothMapService: MAP Service closeService out
09-07 12:06:22.443  4299  4299 V BtOppService: Receiver DISABLED_ACTION 
09-07 12:06:22.443  4299  4299 I BtOppRfcommListener: stopping Accept Thread
09-07 12:06:22.443  4299  4299 V BtOppRfcommListener: close mBtServerSocket
09-07 12:06:22.443  4299  4755 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-07 12:06:22.443  4299  4299 V BtOppRfcommListener: waiting for thread to terminate
09-07 12:06:22.443  4299  4755 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-07 12:06:22.444  4299  4299 V BtOppRfcommListener: done waiting for thread to terminate
09-07 12:06:22.448  6798  6798 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 12:06:22.448  6798  6798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 12:06:22.448  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:06:22.448  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 12:06:22.448  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 12:06:22.448  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 12:06:22.448  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 12:06:22.448  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 12:06:22.448  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 12:06:22.449  6798  6798 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 12:06:22.449  6798  6798 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 12:06:22.452  6798  6881 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
09-07 12:06:22.452  6798  6881 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 12:06:22.472  1037  1534 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-07 12:06:22.472  1037  1534 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,09-07 12:06:22.477  1037  1911 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
09-07 12:06:22.477  1037  2785 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-07 12:06:22.477  1037  2785 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-07 12:06:22.477  1037  2785 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
09-07 12:06:22.477  1037  2785 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-07 12:06:22.477  1037  2785 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
09-07 12:06:22.481  1037  1100 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6889 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-07 12:06:22.482  4299  4390 D BluetoothAdapterProperties: Scan Mode:20
09-07 12:06:22.482  4299  4384 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-07 12:06:22.483  4299  4756 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-07 12:06:22.483  4299  4384 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-07 12:06:22.483  4299  4717 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-07 12:06:22.483  4299  4502 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
09-07 12:06:22.483  4299  4502 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
,09-07 12:06:22.485  4299  4758 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-07 12:06:22.486  4299  4502 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-07 12:06:22.486  4299  4502 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-07 12:06:22.486  4299  4502 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-07 12:06:22.486  4299  4502 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-07 12:06:22.486  4299  4502 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-07 12:06:22.486  4299  4502 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-07 12:06:22.486  4299  4502 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-07 12:06:22.486  4299  4502 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-07 12:06:22.486  4299  4502 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-07 12:06:22.486  4299  4502 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
09-07 12:06:22.486  4299  4502 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
09-07 12:06:22.486  4299  4502 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-07 12:06:22.487  6798  6867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 12:06:22.492  4299  4299 V BtOppService: onDestroy
09-07 12:06:22.522  1037  1534 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
09-07 12:06:22.522  1037  1534 D DSQN    : disableDataServiceNotify
09-07 12:06:22.522  1037  1534 D DSQN    : stop dsqn bin
,09-07 12:06:22.524   309  6912 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
09-07 12:06:22.525  1037  2785 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,09-07 12:06:22.525  1037  1100 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6911 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
09-07 12:06:22.526  1037  1527 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 12:06:22.526  1037  1527 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 12:06:22.527  1037  1526 D LGWifiP2pService: InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-07 12:06:22.527  1037  1526 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-07 12:06:22.527  1037  1526 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@1ca6b677
09-07 12:06:22.527  1037  1117 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
09-07 12:06:22.527  1037  1526 D LGWifiP2pService: P2pDisablingState
09-07 12:06:22.528  1037  1526 D LGWifiP2pService: P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
09-07 12:06:22.528  1037  1526 D LGWifiP2pService: p2p socket connection lost
09-07 12:06:22.528  1037  1527 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 12:06:22.528  1037  1526 D LGWifiP2pService: P2pDisabledState
09-07 12:06:22.528  1037  1527 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 12:06:22.528  1037  1527 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 12:06:22.528  1037  1527 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 12:06:22.529  1037  1527 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-07 12:06:22.529  1037  1527 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 12:06:22.529  1037  1527 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 12:06:22.529  1037  1527 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 12:06:22.530  1037  1527 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
09-07 12:06:22.530  1037  1527 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-07 12:06:22.531  1037  1526 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-07 12:06:22.531  2641  2641 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-07 12:06:22.531  1037  1526 D LGWifiP2pService: DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-07 12:06:22.532  1037  1037 D WifiHS20: hidePasspointNotification off =false
09-07 12:06:22.532  6798  6867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 12:06:22.532  6798  6867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 12:06:22.532  6798  6867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:06:22.532  6798  6867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 12:06:22.532  6798  6867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 12:06:22.532  6798  6867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 12:06:22.532  6798  6867 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 12:06:22.532  6798  6867 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 12:06:22.532  6798  6867 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 12:06:22.532  4299  4322 E BluetoothServiceJni: Socket connection failed: 2
09-07 12:06:22.533  4299  4322 E BluetoothAdapterService(376868438): Fa,iled to connect socket
09-07 12:06:22.533  1037  1534 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-07 12:06:22.533  1037  1534 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 12:06:22.533  1037  1534 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-07 12:06:22.533  1037  1534 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
09-07 12:06:22.534  1037  1527 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-07 12:06:22.534  1037  1527 D WifiNative-wlan0: doBoolean: SET ps 1
09-07 12:06:22.534  1037  1527 D WifiNative-wlan0: SET ps 1: returned true
09-07 12:06:22.535   309   894 D CommandListener: Clearing all IP addresses on wlan0
,09-07 12:06:22.536  6798  6867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 12:06:22.536  6798  6867 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-07 12:06:22.537  6798  6867 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 12:06:22.538  1037  2785 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-07 12:06:22.538  1037  2785 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-07 12:06:22.538  1037  1534 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
09-07 12:06:22.538  1037  2785 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-07 12:06:22.539  6798  6798 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 12:06:22.539  6798  6798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 12:06:22.539  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:06:22.539  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 12:06:22.539  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 12:06:22.539  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 12:06:22.539  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 12:06:22.539  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 12:06:22.539  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 12:06:22.539  1592  2035 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-07 12:06:22.540  1037  1534 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
09-07 12:06:22.541  1037  1534 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-07 12:06:22.541  1037  1534 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-07 12:06:22.542  6798  6881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 871)
09-07 12:06:22.542  6798  6798 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 12:06:22.543  6798  6798 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-07 12:06:22.546  1930  1930 V WfdStateTracker: handleWifiStateChangedEvent: 0
09-07 12:06:22.547  1037  1037 W Settings: Sett,ing stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 12:06:22.547  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 12:06:22.547  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-07 12:06:22.547  1037  1037 D WifiHS20: hidePasspointNotification off =false
09-07 12:06:22.548  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 12:06:22.548  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 12:06:22.548  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-07 12:06:22.548  1037  1037 D WifiScanningService: SCAN_AVAILABLE : 1
09-07 12:06:22.548  1037  1037 D RttService: SCAN_AVAILABLE : 1
09-07 12:06:22.548  1037  1545 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-07 12:06:22.548  1037  1546 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-07 12:06:22.549  4299  4299 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
,09-07 12:06:22.550  1037  1527 D WifiNative-p2p0: doBoolean: TERMINATE
09-07 12:06:22.550  1037  1527 D WifiNative-p2p0: TERMINATE: returned true
09-07 12:06:22.550  1037  1534 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-07 12:06:22.551  1037  1534 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-07 12:06:22.551  1037  1527 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-07 12:06:22.551  1037  1527 E WifiStateMachine: useWiFiOffloading() : false
09-07 12:06:22.551  1037  1527 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-07 12:06:22.551  1037  1037 D WifiHS20: hidePasspointNotification off =false
09-07 12:06:22.553  6798  6798 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 12:06:22.554  6798  6798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 12:06:22.554  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:06:22.554  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 12:06:22.554  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 12:06:22.554  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 12:06:22.554  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 12:06:22.554  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 12:06:22.554  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 12:06:22.554  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 12:06:22.554  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 12:06:22.554  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-07 12:06:22.554  1930  1930 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-07 12:06:22.554  1930  1930 D WfdsService: WifiP2pState is changed : false
09-07 12:06:22.555  1930  2316 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
09-07 12:06:22.555  1930  2316 D WfdsService: Set the WFDS Monitor: false
09-07 12:06:22.555  1930  2316 D WfdsMonitor: WFDS Monitor is stopped
09-07 12:06:22.556  1930  2691 D CtrlSupplicant: Received on exit socket, terminate
09-07 12:06:22.556  1930  2691 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
09-07 12:06:22.556  1930  2316 D WfdsService: STATE : WfdsDisabledState - enter
09-07 12:06:22.556  1930  2691 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
09-07 12:06:22.556  1930  2691 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
09-07 12:06:22.556  1930  2316 W WfdsService: DefaultState - msg [9445378] is not handled
09-07 12:06:22.556  1930  2317 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
09-07 12:06:22.556  1037  1037 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-07 12:06:22.557  1037  1037 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-07 12:06:22.557  1037  1037 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-07 12:06:22.557  1037  1037 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-07 12:06:22.557  1037  1534 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=,3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-07 12:06:22.557  1037  1534 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 12:06:22.557  1037  1534 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 12:06:22.558  1037  1534 D NetworkManagementService: Removing idletimer
09-07 12:06:22.558  1037  1534 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 12:06:22.558  1037  1525 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-07 12:06:22.559  1037  1534 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-07 12:06:22.559  1037  1527 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 12:06:22.559  1037  1527 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-07 12:06:22.559  6798  6798 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 12:06:22.559  6798  6798 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 12:06:22.560  1840  1840 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 12:06:22.561  1840  1840 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-07 12:06:22.561  6798  6798 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 12:06:22.561  6798  6798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 12:06:22.561  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:06:22.561  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 12:06:22.561  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 12:06:22.561  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 12:06:22.561  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 12:06:22.561  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 12:06:22.561  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 12:06:22.562  1037  1525 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
,09-07 12:06:22.565  1592  1592 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 12:06:22.566  1592  1592 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-07 12:06:22.566  1037  1037 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-07 12:06:22.566  1037  1037 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-07 12:06:22.567  1037  1037 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-07 12:06:22.567  1037  1037 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-07 12:06:22.567  6798  6798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 12:06:22.570  1930  1930 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
09-07 12:06:22.571  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 12:06:22.572  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
09-07 12:06:22.573  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-07 12:06:22.573  1037  1037 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
09-07 12:06:22.577  6798  6798 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 12:06:22.577  6798  6798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 12:06:22.577  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:06:22.577  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 12:06:22.577  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 12:06:22.577  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 12:06:22.577  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 12:06:22.577  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 12:06:22.577  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 12:06:22.577  6798  6798 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 12:06:22.577  6798  6798 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 12:06:22.579  6798  6798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 12:06:22.590  1592  1592 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 12:06:22.590  1592  1592 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-07 12:06:22.592  6889  6889 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-07 12:06:22.592  6889  6889 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
09-07 12:06:22.593  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 12:06:22.593  6889  6889 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-07 12:06:22.593  6889  6889 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
09-07 12:06:22.595  6889  6889 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-07 12:06:22.595  6889  6889 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-07 12:06:22.602  1592  1592 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-07 12:06:22.602  1592  1592 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-07 12:06:22.602  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-07 12:06:22.618  1592  1592 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-07 12:06:22.618  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 12:06:22.619  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 12:06:22.628  1037  2787 D DhcpStateMachine: StoppedState
09-07 12:06:22.628  1037  2787 D DhcpStateMachine: StoppedState{ when=-94ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-07 12:06:22.629  1037  1527 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
09-07 12:06:22.629  1037  1527 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
09-07 12:06:22.634  1592  1592 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-07 12:06:22.635  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-07 12:06:22.636  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 12:06:22.636  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 12:06:22.649  6911  6911 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
09-07 12:06:22.650  6911  6911 W LG Account v2.2: No ProfileInfo entries
09-07 12:06:22.650  6911  6911 I LG Account v2.2: isEnabled: false
09-07 12:06:22.650  6911  6911 I Feature : [Lifetracker]ver: 4.21.112(40211120)
09-07 12:06:22.650  6911  6911 I Feature : [Lifetracker]Country: EU
09-07 12:06:22.650  6911  6911 I Feature : [Lifetracker]Operator: OPEN
09-07 12:06:22.650  6911  6911 I Feature : [Lifetracker]Ranking support: false
09-07 12:06:22.650  6911  6911 I Feature : [Lifetracker]Comfort support: false
09-07 12:06:22.650  6911  6911 I Feature : [Lifetracker]Accessory: true
09-07 12:06:22.650  6911  6911 I Feature : [Lifetracker]Health device: true
09-07 12:06:22.650  6911  6911 I Feature : [Lifetracker]Extra Pedometer: false
09-07 12:06:22.650  6911  6911 I Feature : [Lifetracker]Blood glucose device: false
09-07 12:06:22.651  6911  6911 I Feature : [Lifetracker]Device Number: 3
,09-07 12:06:22.653  2641  2641 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-07 12:06:22.653  2641  2641 I wpa_supplicant: monitor socket send errors count : 1
09-07 12:06:22.653  2641  2641 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1930-2\x00 that cannot receive messages
09-07 12:06:22.654  1037  2687 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
,09-07 12:06:22.654  1037  2687 D WifiMonitor: Dropping event because (p2p0) is stopped
09-07 12:06:22.659  6497  6497 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-07 12:06:22.693  2641  2641 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-07 12:06:22.694  1037  2687 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
09-07 12:06:22.694  1037  2687 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-07 12:06:22.694  1037  2687 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-07 12:06:22.694  1037  2687 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
09-07 12:06:22.695  1037  1527 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=176910
09-07 12:06:22.695  1037  1527 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=176911
09-07 12:06:22.696  1037  1119 D Tethering: InitialState.processMessage what=4
,09-07 12:06:22.698  2641  2641 W wpa_supplicant: USIM:  scard_deinit function
09-07 12:06:22.699  1037  2687 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-07 12:06:22.699  1037  2687 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-07 12:06:22.700  1037  1527 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=176915  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-07 12:06:22.700  1037  1527 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=176916  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-07 12:06:22.702  1037  1874 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6938 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-07 12:06:22.703  1037  1119 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-07 12:06:22.705  1037  1527 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
09-07 12:06:22.706  1037  1527 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-07 12:06:22.710  1037  1874 I ActivityManager: Killing 6292:com.android.providers.calendar/u0a14 (adj 15): empty #17
,09-07 12:06:22.751  6889  6889 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,09-07 12:06:22.754  1037  1929 W libprocessgroup: failed to open /acct/uid_10014/pid_6292/cgroup.procs: No such file or directory
09-07 12:06:22.760  4299  4299 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-07 12:06:22.760  4299  4299 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-07 12:06:22.760  4299  4299 V BluetoothPbapReceiver: ***********state = 13
09-07 12:06:22.763  2641  2641 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-07 12:06:22.763  1037  1119 D BluetoothManagerService: Message: 20
09-07 12:06:22.763  1037  1119 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@14258fff:true
09-07 12:06:22.766  1037  2687 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
09-07 12:06:22.766  1037  2687 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
09-07 12:06:22.766  1037  2687 D WifiMonitor: Disconnecting from the supplicant, no more events
09-07 12:06:22.767  1037  1527 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
09-07 12:06:22.768  4299  4299 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
09-07 12:06:22.768  1930  1930 D WfdsService: Supplicant Connection state is changed : false
09-07 12:06:22.769  1930  2316 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
09-07 12:06:22.769  1930  2316 D WfdsService: Set the WFDS Monitor: false
09-07 12:06:22.769  1930  2316 D WfdsMonitor: WFDS Monitor is stopped
09-07 12:06:22.769  1037  1527 D WifiOffDelayIfNotUsed: stopMonitoring
09-07 12:06:22.769  1037  1527 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-07 12:06:22.769  1037  1527 E WifiStateMachine: useWiFiOffloading() : false
09-07 12:06:22.769  1037  1527 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-07 12:06:22.769  4299  4299 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-07 12:06:22.769  4299  4299 V BluetoothPbapService: state: 13
09-07 12:06:22.769  4299  4299 V BluetoothPbapService: Pbap Service closeService in
09-07 12:06:22.771  2163  2163 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-07 12:06:22.771  4299  4299 V BluetoothPbapService: successfully stopped pbap service
09-07 12:06:22.772  4299  4299 V BluetoothPbapService: Pbap Service closeService out
09-07 12:06:22.772  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 12:06:22.772  1930  1930 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-07 12:06:22.773  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
09-07 12:06:22.773  1037  1532 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
09-07 12:06:22.773  1037  1532 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
09-07 12:06:22.774  6798  6798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 12:06:22.774  4299  4299 V BluetoothPbapService: Pbap Service onDestroy
09-07 12:06:22.774  4299  4299 V BluetoothPbapService: Pbap Service closeService in
09-07 12:06:22.774  4299  4299 V BluetoothPbapService: Pbap Service closeService out
09-07 12:06:22.775  4299  4299 D LGBluetoothPbapAdapter: [BTUI] cleanup
09-07 12:06:22.776  2488  2488 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 12:06:22.776  6798  6798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 12:06:22.779  1037  1119 D BluetoothManagerService: Message: 30
,09-07 12:06:22.782  1037  1119 D BluetoothManagerService: Message: 30
09-07 12:06:22.787  6889  6889 D LocalBluetoothProfileManager: Adding local MAP profile
09-07 12:06:22.788  6889  6889 D BluetoothMap: Create BluetoothMap proxy object
09-07 12:06:22.788  1037  1119 D BluetoothManagerService: Message: 30
09-07 12:06:22.793  1037  1119 D BluetoothManagerService: Message: 30
,09-07 12:06:22.794  6889  6889 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
09-07 12:06:22.794  6889  6889 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
09-07 12:06:22.802  6889  6889 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
09-07 12:06:22.805  6889  6889 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
,09-07 12:06:22.809  6938  6938 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-07 12:06:22.811  6889  6889 D DockEventReceiver: finishStartingService: stopping service
09-07 12:06:22.811  6889  6889 D BluetoothInputDevice: Proxy object connected
09-07 12:06:22.812  6889  6889 D HidProfile: Bluetooth service connected
09-07 12:06:22.816  6938  6938 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-07 12:06:22.816  6938  6938 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-07 12:06:22.817  1037  1929 I ActivityManager: Killing 6376:com.android.defcontainer/u0a4 (adj 15): empty #17
09-07 12:06:22.822  6889  6889 D BluetoothPan: BluetoothPAN Proxy object connected
09-07 12:06:22.823  6889  6889 D PanProfile: Bluetooth service connected
09-07 12:06:22.823  6889  6889 D BluetoothMap: Proxy object connected
09-07 12:06:22.824  6889  6889 D MapProfile: Bluetooth service connected
09-07 12:06:22.824  6889  6889 D BluetoothMap: getConnectedDevices()
09-07 12:06:22.824  6889  6889 D BluetoothMap: Bluetooth is Not enabled
09-07 12:06:22.824  6889  6889 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
09-07 12:06:22.836  1037  1874 W libprocessgroup: failed to open /acct/uid_10004/pid_6376/cgroup.procs: No such file or directory
,09-07 12:06:22.856  6889  6889 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-07 12:06:22.860  6798  6798 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
09-07 12:06:22.890  6889  6889 D LgDataFeature: LgDataFeature() Constructor: none
09-07 12:06:22.891  6889  6889 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-07 12:06:22.904  6889  6889 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 12:06:22.905  6889  6889 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,09-07 12:06:22.912  6889  6889 D BluetoothPermissionRequest: onReceive
09-07 12:06:22.916  6889  6889 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,09-07 12:06:22.927  1037  1929 I ActivityManager: Killing 6540:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,09-07 12:06:22.928  6889  6889 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-07 12:06:22.991  4299  4299 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
09-07 12:06:22.991  4299  4299 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
09-07 12:06:22.992  4299  4299 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
,09-07 12:06:22.995  1037  2039 W libprocessgroup: failed to open /acct/uid_10008/pid_6540/cgroup.procs: No such file or directory
09-07 12:06:22.995  1037  1372 D PowerManagerServiceEx: acquireWakeLockInternal: lock=529372928, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
09-07 12:06:22.999  1037  1372 V AlarmManager: ELAPSED_WAKEUP set : Alarm{212232a6 type 2 when 177156 com.google.android.gms} when 177156
09-07 12:06:23.008  4299  4299 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-07 12:06:23.008  4299  4299 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,09-07 12:06:23.079  1037  2001 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6971 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,09-07 12:06:23.080  4299  4299 V BluetoothFtpService: Ftp Service onStartCommand
09-07 12:06:23.080  4299  4299 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-07 12:06:23.080  4299  4299 V BluetoothFtpService: Ftp Service closeService
09-07 12:06:23.080  4299  4299 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
09-07 12:06:23.082  4299  4299 V BluetoothFtpService: successfully stopped ftp service
09-07 12:06:23.084  4299  4299 V BluetoothFtpService: Ftp Service onDestroy
09-07 12:06:23.084  4299  4299 V BluetoothFtpService: Ftp Service closeService
09-07 12:06:23.087  4299  4299 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-07 12:06:23.087  4299  4299 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-07 12:06:23.087  4299  4299 V BluetoothSapReceiver: SapReceiver onReceive 
09-07 12:06:23.088  4299  4299 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-07 12:06:23.088  4299  4299 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
09-07 12:06:23.088  4299  4299 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-07 12:06:23.089  4299  4299 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-07 12:06:23.089  4299  4299 V BluetoothSapService: state: 13
09-07 12:06:23.089  4299  4299 V BluetoothSapService: Stopping SAP server process
09-07 12:06:23.090  4299  4299 V BluetoothSapService: Sap Service closeSapService in
09-07 12:06:23.091  4299  4299 V BluetoothSapService: Close listen Socket : 
09-07 12:06:23.091  4299  4299 V BluetoothSapService: Close rfcomm Socket : 
09-07 12:06:23.091  4299  4299 V BluetoothSapService: Close sapd  Socket : 
09-07 12:06:23.140  1037  2039 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6988 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-07 12:06:23.147  4299  4299 V BluetoothSapService: Sap Service closeSapService out
09-07 12:06:23.147  4299  4299 V BluetoothSapService: Sap Service onDestroy
09-07 12:06:23.148  4299  4299 V BluetoothSapService: Sap Service closeSapService in
09-07 12:06:23.148  4299  4299 V BluetoothSapService: Close listen Socket : 
09-07 12:06:23.148  4299  4299 V BluetoothSapService: Close rfcomm Socket : 
09-07 12:06:23.148  4299  4299 V BluetoothSapService: Close sapd  Socket : 
09-07 12:06:23.149  4299  4299 V BluetoothSapService: Sap Service closeSapService out
09-07 12:06:23.173  6971  6971 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-07 12:06:23.198  6988  6988 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-07 12:06:23.216  6971  6971 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,09-07 12:06:23.219  1037  1874 I ActivityManager: Killing 6055:com.lge.appbox.client/u0a11 (adj 15): empty #17
09-07 12:06:23.251  1037  2001 W libprocessgroup: failed to open /acct/uid_10011/pid_6055/cgroup.procs: No such file or directory
,09-07 12:06:23.307  6971  6971 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,09-07 12:06:23.308  6971  6971 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
09-07 12:06:23.309  6971  6971 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
09-07 12:06:23.310  2667  2667 D [Concierge]Service: onStartCommand(). Type : 9
09-07 12:06:23.310  6971  6971 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
09-07 12:06:23.315  6971  6971 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
09-07 12:06:23.321  6971  6971 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,09-07 12:06:23.335  6971  6971 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
,09-07 12:06:23.342  6971  6971 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-07 12:06:23.345  6971  6971 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-07 12:06:23.361  6971  6971 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-07 12:06:23.363  6497  6497 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-07 12:06:23.366  6938  6938 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-07 12:06:23.367  6938  6938 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-07 12:06:23.367  6938  6938 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-07 12:06:23.367  6971  6971 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
09-07 12:06:23.370  6889  6889 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-07 12:06:23.371  6971  6971 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
,09-07 12:06:23.378  6889  6889 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 12:06:23.385  6971  6971 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-07 12:06:23.386  6971  6971 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-07 12:06:23.388  6971  6971 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-07 12:06:23.390  6497  6497 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-07 12:06:23.394  6938  6938 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-07 12:06:23.394  6938  6938 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-07 12:06:23.394  6938  6938 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-07 12:06:23.399  6889  6889 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-07 12:06:23.408  6889  6889 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 12:06:23.415  6971  6971 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-07 12:06:23.416  6971  6971 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-07 12:06:23.418  6971  6971 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-07 12:06:23.489  4299  4390 D bt_hci_bdroid: cleanup
09-07 12:06:23.489  4299  4521 I bt_lpm  : LPM is already off!!!
,09-07 12:06:23.490  4299  4684 I bt_userial_mct: exiting userial_read_thread
09-07 12:06:23.490  4299  4684 D bt_userial_mct: Leaving userial_evt_read_thread()
09-07 12:06:23.490  4299  4502 W bt-btif : ag scb idx 1 not allocated
09-07 12:06:23.491  4299  4502 E bt-btif : BTA AG is already disabled, ignoring ...
09-07 12:06:23.491  4299  4502 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-07 12:06:23.491  4299  4502 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-07 12:06:23.491  4299  4502 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-07 12:06:23.491  4299  4502 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-07 12:06:23.491  4299  4390 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-07 12:06:23.492  4299  4521 I bt_vendor: hw_epilog_process
09-07 12:06:23.492  4299  4502 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-07 12:06:23.492  4299  4502 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-07 12:06:23.492  4299  4502 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-07 12:06:23.492  4299  4502 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-07 12:06:23.492  4299  4502 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-07 12:06:23.492  4299  4502 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-07 12:06:23.492  4299  4390 D bt_hci_bdroid: cleanup Finalizing cleanup
,09-07 12:06:23.493  4299  4502 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-07 12:06:23.493  4299  4390 D bt_userial_mct: userial_close
09-07 12:06:23.493  4299  4502 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,09-07 12:06:23.493  4299  4390 E bt_userial_mct: pthread_join() FAILED result:3
09-07 12:06:23.493  4299  4390 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
09-07 12:06:23.493  4299  4502 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
,09-07 12:06:23.494  4299  4502 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-07 12:06:23.494  4299  4502 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-07 12:06:23.494  4299  4502 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-07 12:06:23.494  4299  4502 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-07 12:06:23.494  4299  4502 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-07 12:06:23.495  4299  4502 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
,09-07 12:06:23.497  1037  1564 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7008 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
09-07 12:06:23.532  4299  4390 D bt_hci_bdroid: set_power 0
09-07 12:06:23.532  4299  4390 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,09-07 12:06:23.532  4299  4390 I bt_vendor: bluetooth satus is on
09-07 12:06:23.532  4299  4390 I bt_vendor: bt-vendor : resetting BT status
09-07 12:06:23.532  4299  4390 I bt_vendor: Starting hciattach daemon
,09-07 12:06:23.532  4299  4390 I bt_vendor: try to set false
09-07 12:06:23.534  4299  4390 I bt_vendor: Starting hciattach daemon
09-07 12:06:23.534  4299  4390 I bt_vendor: try to set false
,09-07 12:06:23.536  4299  4390 I bt_vendor: cleanup
09-07 12:06:23.538  4299  4502 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-07 12:06:23.539  4299  4390 I GKI_LINUX: GKI_exit_task 0 done
,09-07 12:06:23.539  4299  4390 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,09-07 12:06:23.542  4299  4384 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,09-07 12:06:23.547  4299  4299 D HeadsetService: Received stop request...Stopping profile...
09-07 12:06:23.551  4299  4299 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
,09-07 12:06:23.551  4299  4299 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-07 12:06:23.551  4299  4299 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16768e56
09-07 12:06:23.552  4299  4433 D HeadsetStateMachine: Exit Disconnected: -1
09-07 12:06:23.554  1840  1840 D BluetoothHeadset: Proxy object disconnected
09-07 12:06:23.554  1840  1840 D BluetoothHeadset: Proxy object disconnected
09-07 12:06:23.554  1840  1840 D BluetoothHeadset: Proxy object disconnected
09-07 12:06:23.554  1037  1037 D BluetoothHeadset: Proxy object disconnected
09-07 12:06:23.554  1037  1037 D AudioService: onServiceDisconnected: Bluetooth profile: 1,
09-07 12:06:23.556  4299  4299 D A2dpService: Received stop request...Stopping profile...
09-07 12:06:23.556  4299  4482 D A2dpStateMachine: Exit Disconnected: -1
09-07 12:06:23.556  4299  4299 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
09-07 12:06:23.559  4299  4384 D BluetoothAdapterState: Stopping profile services that were post enabled
09-07 12:06:23.560  4299  4299 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
09-07 12:06:23.560  4299  4299 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
09-07 12:06:23.560  4299  4299 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16768e56
09-07 12:06:23.561  1037  1037 D BluetoothA2dp: Proxy object disconnected
09-07 12:06:23.561  1037  1037 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-07 12:06:23.563  4299  4299 D HidService: Received stop request...Stopping profile...
09-07 12:06:23.563  4299  4299 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16768e56
,09-07 12:06:23.569  4299  4299 D HealthService: Received stop request...Stopping profile...
,09-07 12:06:23.569  4299  4299 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16768e56
09-07 12:06:23.570  6889  6889 D BluetoothInputDevice: Proxy object disconnected
09-07 12:06:23.570  6889  6889 D HidProfile: Bluetooth service disconnected
09-07 12:06:23.571  4299  4299 D HeadsetStateMachine: Unbinding service...
09-07 12:06:23.572  4299  4299 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-07 12:06:23.572  4299  4299 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-07 12:06:23.572  4299  4299 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-07 12:06:23.572  4299  4299 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-07 12:06:23.572  4299  4299 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-07 12:06:23.572  4299  4299 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-07 12:06:23.572  4299  4299 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-07 12:06:23.573  4299  4299 D PanService: Received stop request...Stopping profile...
09-07 12:06:23.573  4299  4299 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16768e56
09-07 12:06:23.574  6889  6889 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-07 12:06:23.574  6889  6889 D PanProfile: Bluetooth service disconnected
09-07 12:06:23.574  4299  4299 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-07 12:06:23.575  4299  4299 D BtGatt.GattService: Received stop request...Stopping profile...
09-07 12:06:23.575  4299  4299 D BtGatt.GattService: stop()
09-07 12:06:23.575  4299  4299 D BtGatt.AdvertiseManager: advertise clients cleared
09-07 12:06:23.576  4299  4299 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16768e56
09-07 12:06:23.577  4299  4299 D BluetoothMapService: Received stop request...Stopping profile...
09-07 12:06:23.577  4299  4299 D BluetoothMapService: stop()
09-07 12:06:23.578  4299  4299 D BluetoothMapEmailAppObserver: deinitObservers()
09-07 12:06:23.578  4299  4299 D BluetoothMapEmailAppObserver: removeReceiver()
09-07 12:06:23.579  4299  4299 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16768e56
09-07 12:06:23.579  6889  6889 D BluetoothMap: Proxy object disconnected
09-07 12:06:23.580  6889  6889 D MapProfile: Bluetooth service disconnected
09-07 12:06:23.580  4299  4299 I BluetoothA2dpServiceJni: cleanupNative
09-07 12:06:23.580  4299  4483 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-07 12:06:23.580  4299  4299 I GKI_LINUX: GKI_exit_task 2 done
09-07 12:06:23.580  4299  4299 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-07 12:06:23.581  4299  4299 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-07 12:06:23.581  4299  4299 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-07 12:06:23.581  4299  4299 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-07 12:06:23.581  4299  4299 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-07 12:06:23.581  4299  4299 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-07 12:06:23.581  4299  4299 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-07 12:06:23.581  4299  4299 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-07 12:06:23.583  4299  4299 V BluetoothMapService: Handler(): got msg=4
09-07 12:06:23.583  4299  4299 D BluetoothMapService: MAP Service closeService in
09-07 12:06:23.583  4299  4299 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-07 12:06:23.583  4299  4299 V BluetoothMapService: MAP Service closeService out
09-07 12:06:23.583  4299  4299 D BluetoothMapService: cleanup()
09-07 12:06:23.584  4299  4299 D BluetoothMapService: MAP Service closeService in
09-07 12:06:23.584  4299  4299 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-07 12:06:23.584  4299  4299 V BluetoothMapService: MAP Service closeService out
09-07 12:06:23.584  4299  4384 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
09-07 12:06:23.584  4299  4384 D BluetoothAdapterProperties: Setting state to 10
09-07 12:06:23.584  4299  4384 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-07 12:06:23.584  1037  1119 D BluetoothManagerService: Message: 60
09-07 12:06:23.584  1037  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
09-07 12:06:23.584  1037  1119 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
09-07 12:06:23.584  1037  1119 D BluetoothA2dp: onBluetoothStateChange: up=false
09-07 12:06:23.585  4299  4384 I BluetoothAdapterState: Entering OffState
09-07 12:06:23.585  6889  6906 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-07 12:06:23.585  1037  1119 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 12:06:23.586  6889  6908 D BluetoothPbap: onBluetoothStateChange: up=false
09-07 12:06:23.586  6889  6906 D BluetoothPan: onBluetoothStateChange on: false
09-07 12:06:23.587  1840  2444 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-07 12:06:23.587  1840  1856 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 12:06:23.588  6889  6908 D BluetoothMap: onBluetoothStateChange: up=false
09-07 12:06:23.589  1840  3325 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 12:06:23.590  1037  1119 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
09-07 12:06:23.590  1037  1119 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
09-07 12:06:23.592  1037  1119 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
09-07 12:06:23.593  1037  1119 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
09-07 12:06:23.593  1037  1119 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@34171034 mBinding = false
09-07 12:06:23.593  1037  1119 D BluetoothManagerService: Sending unbind request.
09-07 12:06:23.595  1037  1119 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
09-07 12:06:23.602  4299  4390 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
09-07 12:06:23.602  4299  4299 I GKI_LINUX: GKI_exit_task 1 done
,09-07 12:06:23.602  4299  4299 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
09-07 12:06:23.603  4299  4299 I BluetoothServiceJni: cleanupNative: return from cleanup
09-07 12:06:23.603  4299  4299 I art     : --- WEIRD: removing null entry 246
09-07 12:06:23.603  4299  4299 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
09-07 12:06:23.603  4299  4299 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
09-07 12:06:23.605  1930  1930 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-07 12:06:23.605  1930  2132 D LGBluetoothAPIService: Message: 2
09-07 12:06:23.605  1930  2132 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@9078081 mBinding = false
09-07 12:06:23.605  1930  2132 D LGBluetoothAPIService: Sending unbind request.
09-07 12:06:23.607  1592  1592 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-07 12:06:23.608  6798  6798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 12:06:23.609  6798  6798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 12:06:23.611  1592  1592 D BluetoothAdapter: 897859369: getState() :  mService = null. Returning STATE_OFF
09-07 12:06:23.611  1592  1592 D BluetoothAdapter: 897859369: getState() :  mService = null. Returning STATE_OFF
09-07 12:06:23.613  6889  6889 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-07 12:06:23.614  6889  6889 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
09-07 12:06:23.614  6889  6889 D LGBluetoothEventManager: [BTUI] clear device connection state
09-07 12:06:23.616  4299  4299 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
,09-07 12:06:23.617  6889  6889 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-07 12:06:23.620  4299  4299 I art     : System.exit called, status: 0
09-07 12:06:23.620  4299  4299 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
09-07 12:06:23.624  6889  6889 D DockEventReceiver: finishStartingService: stopping service
09-07 12:06:23.638  6938  6938 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-07 12:06:23.641  6889  6889 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-07 12:06:23.644   313  1371 V AudioFlinger: 4299 died, releasing its sessions
09-07 12:06:23.644   313  1371 V AudioFlinger:  pid 1840 @ 0
09-07 12:06:23.644   313  1371 V AudioFlinger:  pid 3161 @ 1
09-07 12:06:23.644   313  1371 V AudioFlinger:  pid 3161 @ 2
09-07 12:06:23.648  6889  6889 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 12:06:23.648  6889  6889 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
09-07 12:06:23.682  1037  1929 I ActivityManager: Process com.android.bluetooth (pid 4299) has died
09-07 12:06:23.683  1037  1929 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,09-07 12:06:23.705  2163  2163 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-07 12:06:23.729  7008  7034 W FormManager: Network not available. Please check & try again.
,09-07 12:06:23.737  6889  6889 D BluetoothPermissionRequest: onReceive
09-07 12:06:23.739  7008  7036 V FormManager: Network unavailable.
09-07 12:06:23.742  6889  6889 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,09-07 12:06:23.743  6889  6889 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
09-07 12:06:23.745  7008  7036 V FormManager: Network unavailable.
09-07 12:06:23.748  6889  6889 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,09-07 12:06:23.807  1037  2001 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7039 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
09-07 12:06:23.819  6889  6889 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-07 12:06:23.819  6889  6889 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-07 12:06:23.819  6889  6889 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-07 12:06:23.819  6889  6889 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,09-07 12:06:23.820  6889  6889 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-07 12:06:23.840  6889  6889 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-07 12:06:23.840  6889  6889 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-07 12:06:23.841  6889  6889 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-07 12:06:23.841  6889  6889 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-07 12:06:23.841  6889  6889 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-07 12:06:23.842  6889  6889 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,09-07 12:06:23.847  1037  1874 I ActivityManager: Killing 6076:com.android.contacts/u0a19 (adj 15): empty #17
09-07 12:06:23.896  4760  4760 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,09-07 12:06:23.896  4760  4760 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-07 12:06:23.899  4760  4760 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-07 12:06:23.902  1037  1911 W libprocessgroup: failed to open /acct/uid_10019/pid_6076/cgroup.procs: No such file or directory
09-07 12:06:23.910  4760  4760 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-07 12:06:23.925  4760  7058 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
,09-07 12:06:23.927  4760  7058 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-07 12:06:23.933  4760  7057 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-07 12:06:23.935  6938  6938 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
09-07 12:06:23.935  6938  6938 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-07 12:06:23.935  6938  6938 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-07 12:06:23.936  7039  7039 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
09-07 12:06:23.936  7039  7039 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-07 12:06:23.937  7039  7039 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
09-07 12:06:23.938  7039  7039 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-07 12:06:23.940  6889  6889 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-07 12:06:23.946  7008  7061 W FormManager: Network not available. Please check & try again.
,09-07 12:06:23.958  7008  7062 V FormManager: Network unavailable.
09-07 12:06:23.960  6889  6889 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 12:06:23.961  7039  7039 D BluetoothAdapterApp: Loading JNI Library
09-07 12:06:23.962  7008  7062 V FormManager: Network unavailable.
09-07 12:06:23.983  1037  1037 D PowerManagerServiceEx: releaseWakeLockInternal: lock=529372928 [*alarm*], flags=0x0
09-07 12:06:23.985   309  7064 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,09-07 12:06:23.986  1037  1117 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
09-07 12:06:23.988  6971  6971 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
09-07 12:06:23.989  6971  6971 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
09-07 12:06:23.990  6971  6971 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
09-07 12:06:24.002  7039  7039 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@399992df Instance Count = 1
,09-07 12:06:24.007  7039  7039 D BluetoothAdapterApp: onCreate
09-07 12:06:24.030  6971  6971 D LgDataFeature: LgDataFeature() Constructor: none
09-07 12:06:24.030  7039  7039 D ProfileConfigQcom: [BTUI] HeadsetService is supported
09-07 12:06:24.030  6971  6971 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-07 12:06:24.030  7039  7039 D ProfileConfigQcom: Adding HeadsetService
09-07 12:06:24.030  7039  7039 D ProfileConfigQcom: [BTUI] A2dpService is supported
09-07 12:06:24.031  7039  7039 D ProfileConfigQcom: Adding A2dpService
09-07 12:06:24.031  7039  7039 D ProfileConfigQcom: [BTUI] HidService is supported
09-07 12:06:24.031  7039  7039 D ProfileConfigQcom: Adding HidService
09-07 12:06:24.031  7039  7039 D ProfileConfigQcom: [BTUI] HealthService is supported
09-07 12:06:24.031  7039  7039 D ProfileConfigQcom: Adding HealthService
09-07 12:06:24.032  7039  7039 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
09-07 12:06:24.033  7039  7039 D ProfileConfigQcom: [BTUI] PanService is supported
09-07 12:06:24.033  7039  7039 D ProfileConfigQcom: Adding PanService
09-07 12:06:24.033  7039  7039 D ProfileConfigQcom: [BTUI] GattService is supported
09-07 12:06:24.033  7039  7039 D ProfileConfigQcom: Adding GattService
09-07 12:06:24.034  7039  7039 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
09-07 12:06:24.034  7039  7039 D ProfileConfigQcom: Adding BluetoothMapService
09-07 12:06:24.034  7039  7039 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
09-07 12:06:24.036  7039  7039 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
09-07 12:06:24.040  6889  6889 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
09-07 12:06:24.042  6971  6971 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
09-07 12:06:24.043  7039  7039 V LGMDMManagerInternal: Create singleton instance
,09-07 12:06:24.045  6971  6971 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
,09-07 12:06:24.045  6971  6971 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
09-07 12:06:24.045  6971  6971 V SoundPool: doLoad: loading sample sampleID=1
,09-07 12:06:24.046  6971  7068 V SoundPool: Start decode
09-07 12:06:24.046  6971  7068 V MediaPlayer[Native]: decode(31, 10857164, 17813)
09-07 12:06:24.047   313  2153 V MediaPlayerService: decode(22, 10857164, 17813)
,09-07 12:06:24.047   313  2153 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
09-07 12:06:24.047   313  2153 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
09-07 12:06:24.047   313  2153 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
09-07 12:06:24.047   313  2153 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
09-07 12:06:24.047   313  2153 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
09-07 12:06:24.048   313  2153 V MediaPlayerService: player type = 3
09-07 12:06:24.048   313  2153 V AwesomePlayer: AwesomePlayer create()
09-07 12:06:24.049   313  2153 V AwesomePlayer: reset_l() 
09-07 12:06:24.049   313  2153 V AwesomePlayer: cancelPlayerEvents
09-07 12:06:24.049   313  2153 V AwesomePlayer: setAudioSink() 
09-07 12:06:24.049   313  2153 V AwesomePlayer: reset_l() 
09-07 12:06:24.049   313  2153 V AudioCache: notify(0xb16a6680, 8, 0, 0)
09-07 12:06:24.049   313  2153 V AudioCache: ignored
09-07 12:06:24.049   313  2153 V AwesomePlayer: cancelPlayerEvents
09-07 12:06:24.050   313  2153 D Utils   : printFileName fd(23) -> /data/preload/LGQRemote/LGQRemote.apk
09-07 12:06:24.050   313  2153 V AwesomePlayer: setDataSource_l dataSource
09-07 12:06:24.050   313  2153 V LGParserOSAL: SniffLGParser start
09-07 12:06:24.050   313  2153 V LGParserOSAL: MainType:5, SubType=0
09-07 12:06:24.050   313  2153 V LGParserOSAL: #### check Mime : application/ogg
09-07 12:06:24.050   313  2153 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
09-07 12:06:24.050   313  2153 E MediaExtractor: Use LGExtractor :application/ogg 
09-07 12:06:24.052  6971  6971 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
09-07 12:06:24.060  6718  6718 D UEI.SmartControl: QS Service created
,09-07 12:06:24.070  6971  6971 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
09-07 12:06:24.076  6971  6971 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,09-07 12:06:24.077  6971  6971 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
09-07 12:06:24.084  6718  6718 I UEI.SmartControl: Service initServices...
09-07 12:06:24.085  6718  6718 D UEI.SmartControl: QS start get config
09-07 12:06:24.100   313  2153 V LGParserOSAL: supported mime: application/ogg
09-07 12:06:24.100   313  2153 V AwesomePlayer: setDataSource_l() extractor countTracks=1
09-07 12:06:24.100   313  2153 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
09-07 12:06:24.100   313  2153 V AwesomePlayer: mBitrate = -1 bits/sec
09-07 12:06:24.100  6971  6971 V LGMDMManager: Create singleton instance
09-07 12:06:24.100   313  2153 V AwesomePlayer: AudioTrack Setting
09-07 12:06:24.100   313  2153 V AwesomePlayer: AudioTrack Setting channelCount = 2
09-07 12:06:24.100   313  2153 V AwesomePlayer: setAudioSource() 
09-07 12:06:24.100   313  2153 V MediaPlayerService: prepare
09-07 12:06:24.100   313  2153 V AwesomePlayer: prepareAsync_l() 
09-07 12:06:24.100   313  2153 V MediaPlayerService: wait for prepare
09-07 12:06:24.100   313  7069 V AwesomePlayer: onPrepareAsyncEvent() 
09-07 12:06:24.100   313  7069 V AwesomePlayer: initAudioDecoder() 
09-07 12:06:24.100   313  7069 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-07 12:06:24.100   313  7069 V AudioSystem: isOffloadSupported()
09-07 12:06:24.100   313  7069 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-07 12:06:24.100   313  7069 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-07 12:06:24.100   313  7069 I AudioFlinger: isAudioPlaybackHookOn() false
09-07 12:06:24.100   313  7069 V AwesomePlayer: getUseOffload() = 0 
09-07 12:06:24.100   313  7069 V OMXCodec: OMXCodec::Create
09-07 12:06:24.101   313  7069 V OMXCodec: findMatchingCodecs()
09-07 12:06:24.101   313  7069 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
,09-07 12:06:24.101   313  7069 V OMXCodec: matchingCodecs.size()=1
09-07 12:06:24.101   313  7069 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
09-07 12:06:24.102   313  7069 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
09-07 12:06:24.102   313  7069 V LGCodecAdapter: LG Codec Adapter start
09-07 12:06:24.102   313  7069 V OMXCodec: OMXCodec Createtor
09-07 12:06:24.102   313  7069 V OMXCodec: setComponentRole
09-07 12:06:24.103   313  7069 V OMXCodec: configureCodec protected=0
09-07 12:06:24.103   313  7069 V LGCodecAdapter: called getLGCodecSpecificData
09-07 12:06:24.103   313  7069 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
09-07 12:06:24.103   313  7069 V LGCodecOSAL: Called LGconfigureCodecMETA
09-07 12:06:24.103   313  7069 V LGCodecOSAL: Called LGconfigureCodecMSG
09-07 12:06:24.103   313  7069 V LGCodecOSAL: Not support LGCodec
09-07 12:06:24.103   313  7069 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-07 12:06:24.103   313  7069 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
09-07 12:06:24.103   313  7069 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
,09-07 12:06:24.103   313  7069 I AwesomePlayer: Could not offload audio decode, try pcm offload
09-07 12:06:24.103   313  7069 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-07 12:06:24.103   313  7069 V AudioSystem: isOffloadSupported()
09-07 12:06:24.103   313  7069 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-07 12:06:24.103   313  7069 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-07 12:06:24.103   313  7069 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
09-07 12:06:24.103   313  7069 V OMXCodec: init()
09-07 12:06:24.103   313  7069 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
09-07 12:06:24.103   313  7069 V OMXCodec: allocateBuffers
09-07 12:06:24.103   313  7069 V OMXCodec: allocateBuffersOnPort portIndex=0
09-07 12:06:24.103   313  7069 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
09-07 12:06:24.103   313  7069 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7830 on input port
09-07 12:06:24.103   313  7069 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7880 on input port
09-07 12:06:24.103   313  7069 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f78d0 on input port
09-07 12:06:24.103   313  7069 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7920 on input port
09-07 12:06:24.104   313  7069 V OMXCodec: allocateBuffersOnPort portIndex=1
09-07 12:06:24.104   313  7069 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-07 12:06:24.104   313  7069 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7970 on output port
09-07 12:06:24.104   313  7069 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7dd0 on output port
09-07 12:06:24.104   313  7069 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7e20 on output port
09-07 12:06:24.104   313  7069 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7f10 on output port
09-07 12:06:24.104   313  7069 V OMXCodec: init() mAsyncCompletion wait!!! 
09-07 12:06:24.104   313  7071 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-07 12:06:24.104   313  7071 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-07 12:06:24.104   313  7071 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
09-07 12:06:24.104   313  7071 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
09-07 12:06:24.104   313  7071 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
09-07 12:06:24.104   313  7071 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
09-07 12:06:24.104   313  7069 V OMXCodec: init() mAsyncCompletion wait free! 
09-07 12:06:24.104   313  7069 V AwesomePlayer: finishAsyncPrepare_l() 
09-07 12:06:24.104   313  7069 V AudioCache: notify(0xb16a6680, 5, 0, 0)
09-07 12:06:24.104   313  7069 V AudioCache: ignored
09-07 12:06:24.104   313  7069 V AudioCache: notify(0xb16a6680, 1, 0, 0)
09-07 12:06:24.104   313  7069 V AudioCache: prepared
09-07 12:06:24.104   313  2153 V AudioCache: wait - success
09-07 12:06:24.104   313  2153 V MediaPlayerService: start
09-07 12:06:24.105   313  2153 V AwesomePlayer: play_l() 
09-07 12:06:24.105   313  2153 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
09-07 12:06:24.105   313  2153 V AwesomePlayer: createAudioPlayer_l
09-07 12:06:24.105   313  2153 V AwesomePlayer: seekAudioIfNecessary_l() 
09-07 12:06:24.105   313  2153 V AwesomePlayer: startAudioPlayer_l() 
09-07 12:06:24.105   313  2153 D AudioPlayer: start of Playback, useOffload 0
09-07 12:06:24.105   313  2153 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-07 12:06:24.105   313  2153 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer ,with codec specific data
09-07 12:06:24.109   313  7071 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
09-07 12:06:24.109   313  7071 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
09-07 12:06:24.109   313  7071 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
09-07 12:06:24.109   313  7071 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
09-07 12:06:24.109   313  7071 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
09-07 12:06:24.109   313  7071 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-07 12:06:24.109   313  7071 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884528
09-07 12:06:24.109   313  7071 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-07 12:06:24.110   313  7071 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885648
09-07 12:06:24.110   313  7071 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-07 12:06:24.110   313  7071 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885728
09-07 12:06:24.110   313  7071 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-07 12:06:24.110   313  7071 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885968
09-07 12:06:24.110   313  7071 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-07 12:06:24.110   313  7071 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
09-07 12:06:24.110   313  7071 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-07 12:06:24.110   313  7071 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
09-07 12:06:24.110   313  7071 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
09-07 12:06:24.110   313  7071 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
09-07 12:06:24.110   313  7071 V OMXCodec: allocateBuffersOnPort portIndex=1
09-07 12:06:24.110   313  7071 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-07 12:06:24.110   313  7071 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7e20 on output port
09-07 12:06:24.110   313  7071 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7dd0 on output port
09-07 12:06:24.110   313  7071 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7970 on output port
09-07 12:06:24.110   313  7071 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57bf240 on output port
09-07 12:06:24.110   313  7071 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
09-07 12:06:24.110   313  7071 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
09-07 12:06:24.112   313  2153 V AudioCache: open(48000, 2, 0x0, 1, 4)
09-07 12:06:24.112   313  2153 V AudioCache: notify(0xb16a6680, 6, 0, 0)
09-07 12:06:24.112   313  2153 V AudioCache: ignored
09-07 12:06:24.112   313  2153 V MediaPlayerService: wait for playback complete
09-07 12:06:24.112   313  7072 V AudioCache: write(0xb16b8000, 4096)
09-07 12:06:24.112   313  7072 V AudioCache: memcpy(0xaf0f9000, 0xb16b8000, 4096)
09-07 12:06:24.114   313  7072 V AudioCache: write(0xb16b8000, 4096)
09-07 12:06:24.114   313  7072 V AudioCache: memcpy(0xaf0fa000, 0xb16b8000, 4096)
09-07 12:06:24.114   313  7072 V AudioCache: write(0xb16b8000, 4096)
09-07 12:06:24.114   313  7072 V AudioCache: memcpy(0xaf0fb000, 0xb16b8000, 4096)
09-07 12:06:24.114  7039  7039 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-07 12:06:24.114   313  7072 V AudioCache: write(0xb16b8000, 4096)
09-07 12:06:24.114   313  7072 V AudioCache: memcpy(0xaf0fc000, 0xb16b8000, 4096)
09-07 12:06:24.115   313  7072 V AudioCache: write(0xb16b8000, 4096)
09-07 12:06:24.115   313  7072 V AudioCache: memcpy(0xaf0fd000, 0xb16b8000, 4096)
,09-07 12:06:24.116   313  7072 V AudioCache: write(0xb16b8000, 4096)
09-07 12:06:24.116   313  7072 V AudioCache: memcpy(0xaf0fe000, 0xb16b8000, 4096)
09-07 12:06:24.117   313  7072 V AudioCache: write(0xb16b8000, 4096)
09-07 12:06:24.117   313  7072 V AudioCache: memcpy(0xaf0ff000, 0xb16b8000, 4096)
09-07 12:06:24.117   313  7072 V AudioCache: write(0xb16b8000, 4096)
09-07 12:06:24.117   313  7072 V AudioCache: memcpy(0xaf100000, 0xb16b8000, 4096)
09-07 12:06:24.117   313  7072 V AudioCache: write(0xb16b8000, 4096)
09-07 12:06:24.117  7039  7039 V BluetoothSapReceiver: [BTUI] checkServiceStart
,09-07 12:06:24.117   313  7072 V AudioCache: memcpy(0xaf101000, 0xb16b8000, 4096)
09-07 12:06:24.117  7039  7039 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-07 12:06:24.117  7039  7039 V BluetoothSapReceiver: SapReceiver onReceive 
09-07 12:06:24.118   313  7072 V AudioCache: write(0xb16b8000, 4096)
09-07 12:06:24.118   313  7072 V AudioCache: memcpy(0xaf102000, 0xb16b8000, 4096)
09-07 12:06:24.118   313  7072 V AudioCache: write(0xb16b8000, 4096)
09-07 12:06:24.118   313  7072 V AudioCache: memcpy(0xaf103000, 0xb16b8000, 4096)
09-07 12:06:24.118   313  7072 V AudioCache: write(0xb16b8000, 4096)
09-07 12:06:24.118   313  7072 V AudioCache: memcpy(0xaf104000, 0xb16b8000, 4096)
09-07 12:06:24.119  7039  7039 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-07 12:06:24.119  7039  7039 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
09-07 12:06:24.119   313  7072 V AudioCache: write(0xb16b8000, 4096)
09-07 12:06:24.119   313  7072 V AudioCache: memcpy(0xaf105000, 0xb16b8000, 4096)
09-07 12:06:24.126   313  7072 V AudioCache: write(0xb16b8000, 4096)
09-07 12:06:24.126   313  7072 V AudioCache: memcpy(0xaf106000, 0xb16b8000, 4096)
09-07 12:06:24.126   313  7072 V AudioCache: write(0xb16b8000, 4096)
09-07 12:06:24.126   313  7072 V AudioCache: memcpy(0xaf107000, 0xb16b8000, 4096)
09-07 12:06:24.126   313  7072 V AudioCache: write(0xb16b8000, 4096)
09-07 12:06:24.126   313  7072 V AudioCache: memcpy(0xaf108000, 0xb16b8000, 4096)
09-07 12:06:24.126   313  7072 V AudioCache: write(0xb16b8000, 4096)
09-07 12:06:24.126   313  7072 V AudioCache: memcpy(0xaf109000, 0xb16b8000, 4096)
09-07 12:06:24.126   313  7072 V AudioCache: write(0xb16b8000, 4096)
09-07 12:06:24.126   313  7072 V AudioCache: memcpy(0xaf10a000, 0xb16b8000, 4096)
09-07 12:06:24.127   313  7072 V AudioCache: write(0xb16b8000, 4096)
09-07 12:06:24.127   313  7072 V AudioCache: memcpy(0xaf10b000, 0xb16b8000, 4096)
09-07 12:06:24.128   313  7072 V AudioCache: write(0xb16b8000, 4096)
09-07 12:06:24.128   313  7072 V AudioCache: memcpy(0xaf10c000, 0xb16b8000, 4096)
09-07 12:06:24.128   313  7072 V AudioCache: write(0xb16b8000, 4096)
09-07 12:06:24.128   313  7072 V AudioCache: memcpy(0xaf10d000, 0xb16b8000, 4096)
09-07 12:06:24.129   313  7072 V AudioCache: write(0xb16b8000, 4096)
09-07 12:06:24.129   313  7072 V AudioCache: memcpy(0xaf10e000, 0xb16b8000, 4096)
09-07 12:06:24.130   313  7072 V AudioCache: write(0xb16b8000, 4096)
09-07 12:06:24.130   313  7072 V AudioCache: memcpy(0xaf10f000, 0xb16b8000, 4096)
09-07 12:06:24.130  6988  6988 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
09-07 12:06:24.130   313  7072 V AudioCache: write(0xb16b8000, 4096)
09-07 12:06:24.130   313  7072 V AudioCache: memcpy(0xaf110000, 0xb16b8000, 4096)
09-07 12:06:24.131   313  7072 V AudioCache: write(0xb16b8000, 4096)
09-07 12:06:24.131   313  7072 V AudioCache: memcpy(0xaf111000, 0xb16b8000, 4096)
09-07 12:06:24.134   313  7072 V AudioCache: write(0xb16b8000, 4096)
09-07 12:06:24.134   313  7072 V AudioCache: memcpy(0xaf112000, 0xb16b8000, 4096)
09-07 12:06:24.137   313  7072 V AudioCache: write(0xb16b8000, 4096)
09-07 12:06:24.137   313  7072 V AudioCache: memcpy(0xaf113000, 0xb16b8000, 4096)
09-07 12:06:24.137   313  7072 V AudioCache: write(0xb16b8000, 4096)
09-07 12:06:24.137   313  7072 V AudioCache: memcpy(0xaf114000, 0xb16b8000, 4096)
09-07 12:06:24.138   313  7072 V AudioCache: write(0xb16b8000, 4096)
09-07 12:06:24.138   313  7072 V AudioCache: memcpy(0xaf115000, 0xb16b8000, 4096)
09-07 12:06:24.138   313  7072 V AudioCache: write(0xb16b8000, 4096)
09-07 12:06:24.138   313  7072 V AudioCache: memcpy(0xaf116000, 0xb16b8000, 4096)
09-07 12:06:24.139   313  7072 V AudioCache: write(0xb16b8000, 4096)
09-07 12:06:24.139   313  7072 V AudioCache: memcpy(0xaf117000, 0xb16b8000, 4096)
,09-07 12:06:24.139   313  7072 V AudioCache: write(0xb16b8000, 4096)
09-07 12:06:24.139   313  7072 V AudioCache: memcpy(0xaf118000, 0xb16b8000, 4096)
09-07 12:06:24.140   313  7072 V AudioCache: write(0xb16b8000, 4096)
,09-07 12:06:24.140   313  7072 V AudioCache: memcpy(0xaf119000, 0xb16b8000, 4096)
09-07 12:06:24.141   313  7072 V AudioCache: write(0xb16b8000, 4096)
09-07 12:06:24.141   313  7072 V AudioCache: memcpy(0xaf11a000, 0xb16b8000, 4096)
09-07 12:06:24.141   313  7072 V AudioCache: write(0xb16b8000, 4096)
09-07 12:06:24.141   313  7072 V AudioCache: memcpy(0xaf11b000, 0xb16b8000, 4096)
09-07 12:06:24.142   313  7072 V AudioCache: write(0xb16b8000, 4096)
09-07 12:06:24.142   313  7072 V AudioCache: memcpy(0xaf11c000, 0xb16b8000, 4096)
09-07 12:06:24.143   313  7072 V AudioCache: write(0xb16b8000, 4096)
,09-07 12:06:24.143   313  7072 V AudioCache: memcpy(0xaf11d000, 0xb16b8000, 4096)
09-07 12:06:24.143   313  7072 V AudioCache: write(0xb16b8000, 4096)
09-07 12:06:24.143   313  7072 V AudioCache: memcpy(0xaf11e000, 0xb16b8000, 4096)
09-07 12:06:24.144   313  7072 V AudioCache: write(0xb16b8000, 4096)
09-07 12:06:24.144   313  7072 V AudioCache: memcpy(0xaf11f000, 0xb16b8000, 4096)
09-07 12:06:24.145   313  7072 V AudioCache: write(0xb16b8000, 4096)
09-07 12:06:24.145   313  7072 V AudioCache: memcpy(0xaf120000, 0xb16b8000, 4096)
09-07 12:06:24.145   313  7072 V AudioCache: write(0xb16b8000, 4096),
09-07 12:06:24.145   313  7072 V AudioCache: memcpy(0xaf121000, 0xb16b8000, 4096)
09-07 12:06:24.146   313  7072 V AudioCache: write(0xb16b8000, 4096)
09-07 12:06:24.146   313  7072 V AudioCache: memcpy(0xaf122000, 0xb16b8000, 4096)
09-07 12:06:24.147   313  7072 V AudioCache: write(0xb16b8000, 4096)
09-07 12:06:24.147   313  7072 V AudioCache: memcpy(0xaf123000, 0xb16b8000, 4096)
09-07 12:06:24.148   313  7072 V AudioCache: write(0xb16b8000, 4096)
09-07 12:06:24.148   313  7072 V AudioCache: memcpy(0xaf124000, 0xb16b8000, 4096)
,09-07 12:06:24.149   313  7072 V AudioCache: write(0xb16b8000, 4096)
09-07 12:06:24.149   313  7072 V AudioCache: memcpy(0xaf125000, 0xb16b8000, 4096)
09-07 12:06:24.150   313  7072 V AudioCache: write(0xb16b8000, 4096)
09-07 12:06:24.150   313  7072 V AudioCache: memcpy(0xaf126000, 0xb16b8000, 4096)
09-07 12:06:24.150   313  7072 V AudioCache: write(0xb16b8000, 4096)
09-07 12:06:24.150   313  7072 V AudioCache: memcpy(0xaf127000, 0xb16b8000, 4096)
09-07 12:06:24.151   313  7072 V AudioCache: write(0xb16b8000, 4096)
09-07 12:06:24.151   313  7072 V AudioCache: memcpy(0xaf128000, 0xb16b8000, 4096)
,09-07 12:06:24.151   313  7072 V AudioCache: write(0xb16b8000, 4096)
09-07 12:06:24.151   313  7072 V AudioCache: memcpy(0xaf129000, 0xb16b8000, 4096)
09-07 12:06:24.152   313  7072 V AudioCache: write(0xb16b8000, 4096)
09-07 12:06:24.152   313  7072 V AudioCache: memcpy(0xaf12a000, 0xb16b8000, 4096)
09-07 12:06:24.152   313  7071 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
09-07 12:06:24.153   313  7072 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
09-07 12:06:24.153   313  7072 V AwesomePlayer: postAudioEOS() 
09-07 12:06:24.153   313  7072 V AudioCache: write(0xb16b8000, 280)
09-07 12:06:24.153   313  7072 V AudioCache: memcpy(0xaf12b000, 0xb16b8000, 280)
09-07 12:06:24.154   313  7069 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
09-07 12:06:24.154   313  7069 V AwesomePlayer: onStreamDone
09-07 12:06:24.154   313  7069 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
09-07 12:06:24.154   313  7069 V AudioCache: notify(0xb16a6680, 2, 0, 0)
09-07 12:06:24.154   313  7069 V AudioCache: playback complete
09-07 12:06:24.154   313  7069 V AwesomePlayer: pause_l() 
09-07 12:06:24.154   313  7069 V AudioCache: notify(0xb16a6680, 7, 0, 0)
09-07 12:06:24.154   313  7069 V AudioCache: ignored
09-07 12:06:24.154   313  7069 V AwesomePlayer: cancelPlayerEvents
09-07 12:06:24.155   313  2153 V AudioCache: wait - success
09-07 12:06:24.155   313  2153 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
09-07 12:06:24.155   313  7069 D AudioPlayer: Pause Playback at 1068125
09-07 12:06:24.155   313  2153 V AwesomePlayer: reset_l() 
09-07 12:06:24.155   313  2153 V AudioCache: notify(0xb16a6680, 8, 0, 0)
09-07 12:06:24.155   313  2153 V AudioCache: ignored
09-07 12:06:24.155   313  2153 V AwesomePlayer: cancelPlayerEvents
09-07 12:06:24.155   313  2153 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
09-07 12:06:24.155   313  2153 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
09-07 12:06:24.155   313  2153 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
09-07 12:06:24.155   313  2153 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
09-07 12:06:24.155   313  2153 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-07 12:06:24.155   313  7071 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-07 12:06:24.155   313  7071 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-07 12:06:24.155   313  7071 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
09-07 12:06:24.155   313  7071 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7920 on port 0
09-07 12:06:24.155   313  7071 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
09-07 12:06:24.155   313  7071 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f78d0 on port 0
09-07 12:06:24.156   313  7071 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
09-07 12:06:24.156   313  7071 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7880 on port 0
09-07 12:06:24.156   313  7071 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
09-07 12:06:24.156   313  7071 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7830 on port 0
09-07 12:06:24.156   313  7071 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
09-07 12:06:24.156   313  7071 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-07 12:06:24.156   313  7071 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57bf240 on port 1
09-07 12:06:24.156   313  7071 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
09-07 12:06:24.156   313  7071 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7970 on port 1
09-07 12:06:24.156   313  7071 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
09-07 12:06:24.156   313  7071 V OMXCodec: [OMX.google.vorbis.decoder], freeing buffer 0xb54f7dd0 on port 1
09-07 12:06:24.156   313  7071 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
09-07 12:06:24.156   313  7071 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7e20 on port 1
09-07 12:06:24.156   313  7071 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-07 12:06:24.156   313  7071 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
09-07 12:06:24.156   313  2153 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-07 12:06:24.156   313  2153 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-07 12:06:24.156   313  7071 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
09-07 12:06:24.156   313  7071 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
09-07 12:06:24.156   313  7071 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
09-07 12:06:24.156   313  2153 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-07 12:06:24.156   313  2153 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
09-07 12:06:24.156   313  2153 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
09-07 12:06:24.157   313  2153 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
09-07 12:06:24.158   313  2153 D AudioPlayer: AudioPlayer releasing audio source
09-07 12:06:24.158   313  2153 D AudioPlayer: AudioPlayer done releasing audio source
09-07 12:06:24.158   313  2153 V AwesomePlayer: reset_l() 
09-07 12:06:24.158   313  2153 V AwesomePlayer: cancelPlayerEvents
09-07 12:06:24.158   313  2153 V AwesomePlayer: ~AwesomePlayer call
09-07 12:06:24.158   313  2153 V AwesomePlayer: reset_l() 
09-07 12:06:24.158   313  2153 V AwesomePlayer: cancelPlayerEvents
09-07 12:06:24.158  6971  7068 V SoundPool: close(31)
09-07 12:06:24.159  6971  7068 V SoundPool: pointer = 0x9ffe5000, size = 205080, sampleRate = 48000, numChannels = 2
09-07 12:06:24.180  6971  6971 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
09-07 12:06:24.181  6971  6971 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,09-07 12:06:24.183  6971  6971 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:5193,
,09-07 12:06:24.369  6718  6718 I UEI.SmartControl: Supports setup maps: true
09-07 12:06:24.373  6718  6718 D UEI.SmartControl: QS start statue = true Error code = 0
09-07 12:06:24.373  6718  6718 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-07 12:06:24.373  6718  6718 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-07 12:06:24.373  6718  6718 I UEI.SmartControl: ### init IR Blaster...
,09-07 12:06:24.376  6718  6718 D serial_port: Configuring serial port
,09-07 12:06:24.376  6718  6718 E UEI.SmartControl: UEIBLaster setting for 616
,09-07 12:06:24.376  6718  6718 I UEI.SmartControl: Setting serial record hearder size = 2
09-07 12:06:24.376  6718  6718 I UEI.SmartControl: configuring settings for MAXQ616
09-07 12:06:24.376  6718  6718 I UEI.SmartControl: Get version...
09-07 12:06:24.395  6718  7074 D UEI.SmartControl: serial port data available: 21
,09-07 12:06:24.422  6718  6718 D UEI.SmartControl: MAXQ616 A2-X4 software.
09-07 12:06:24.422  6718  6718 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-07 12:06:24.422  6718  6718 I UEI.SmartControl: QS saving settings...
09-07 12:06:24.424  6718  6718 D UEI.SmartControl: IR Blaster version: 25672567
,09-07 12:06:24.441  6718  7074 D UEI.SmartControl: serial port data available: 4
,09-07 12:06:24.476  6718  6718 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,09-07 12:06:24.486  6718  6718 E UEI.SmartControl: Services init done
09-07 12:06:24.486  6718  6718 D UEI.SmartControl: QS Service init finished
09-07 12:06:24.486  6718  7083 I UEI.SmartControl: Device manager: loading config....
09-07 12:06:24.486  6718  7083 D UEI.SmartControl: ----------- loading internal config...
09-07 12:06:24.488  6718  6718 D UEI.SmartControl: QS Service version name: 2.1.91
09-07 12:06:24.488  6718  6718 D UEI.SmartControl: QS Service version code: 201091
09-07 12:06:24.489  6718  6718 D UEI.SmartControl: Service requested: Control
09-07 12:06:24.492  6718  7083 E UEI.SmartControl: Loading SETTINGS...
09-07 12:06:24.494  6718  6718 D UEI.SmartControl: Request IControl service: devices are loaded...
,09-07 12:06:24.498  6971  6971 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
09-07 12:06:24.499  6718  6733 I UEI.SmartControl: ------ IControl API: 11
09-07 12:06:24.499  6718  6733 D UEI.SmartControl: File observer start...
09-07 12:06:24.500  6718  6733 E UEI.SmartControl: IR Port is disabled: false
09-07 12:06:24.500  6718  6733 D UEI.SmartControl: Starting file observer...
09-07 12:06:24.501  6718  6733 I UEI.SmartControl: Registering callback...
09-07 12:06:24.502  6718  6734 I UEI.SmartControl: ------ IControl API: 19
09-07 12:06:24.503  6718  6734 I UEI.SmartControl: Registering Services Ready callback...
09-07 12:06:24.503  6718  6718 D UEI.SmartControl: Internal service binding...
09-07 12:06:24.504  6718  7083 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
09-07 12:06:24.526  6718  7082 I UEI.SmartControl: Notify AllClients services are ready: 0
09-07 12:06:24.526  6718  7082 D UEI.SmartControl: -----service ready thread exits
09-07 12:06:24.526  6971  6987 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
09-07 12:06:24.527  6971  7066 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
,09-07 12:06:24.527  6971  7066 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
09-07 12:06:24.527  6971  6971 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
09-07 12:06:24.528  6971  6971 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
09-07 12:06:24.528  6718  6734 I UEI.SmartControl: ------ IControl API: 8
09-07 12:06:24.531  6971  6971 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
09-07 12:06:24.531  6971  6971 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
09-07 12:06:24.531  6971  6971 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
09-07 12:06:24.532  6971  6971 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
09-07 12:06:24.532  6971  6971 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
09-07 12:06:24.533  6971  6971 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
09-07 12:06:24.536  6971  6971 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
09-07 12:06:24.538  6971  6971 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
09-07 12:06:24.539  6971  6971 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
09-07 12:06:24.540  6971  6971 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-07 12:06:24.540  6971  6971 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,09-07 12:06:24.542  6971  6971 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
09-07 12:06:24.543  6971  6971 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
09-07 12:06:24.544  6971  6971 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
09-07 12:06:24.545  6971  6971 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1473242784545]
09-07 12:06:24.548  6971  6971 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
09-07 12:06:24.550  1037  1874 I ActivityManager: Killing 6098:com.android.gallery3d/u0a27 (adj 15): empty #17
09-07 12:06:24.581  6971  7085 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,09-07 12:06:24.585  1037  1874 I ActivityManager: Killing 6587:com.lge.email/u0a23 (adj 15): empty #18
09-07 12:06:24.615  1037  1052 W libprocessgroup: failed to open /acct/uid_10027/pid_6098/cgroup.procs: No such file or directory
,09-07 12:06:24.619  1037  1893 W libprocessgroup: failed to open /acct/uid_10023/pid_6587/cgroup.procs: No such file or directory
09-07 12:06:24.625  6971  6971 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
09-07 12:06:24.626  6971  6971 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-07 12:06:24.627  6971  6971 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
09-07 12:06:24.627  6971  6971 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
09-07 12:06:24.627  6971  6971 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
09-07 12:06:24.628  6971  6971 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
09-07 12:06:24.628  6971  6971 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
,09-07 12:06:24.638  6971  6971 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
09-07 12:06:24.931  1037  1372 V AlarmManager: ELAPSED_WAKEUP set : Alarm{df36ec4 type 2 when 179133 com.google.android.gms} when 179133
,09-07 12:06:25.541  1037  1964 D WifiServiceImplEx: setWifiEnabled: true pid=6798, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,09-07 12:06:25.551  1037  1964 D WifiService: setWifiEnabled: true pid=6798, uid=10118
09-07 12:06:25.551  1037  1964 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-07 12:06:25.553  1037  1534 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-07 12:06:25.558  1037  1119 D Tethering: MasterInitialState.processMessage what=3
,09-07 12:06:25.565  6798  6798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 12:06:25.572  6798  6798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 12:06:25.575  1037  1534 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-07 12:06:25.581  1037  1099 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-07 12:06:25.582  1037  1119 D Tethering: MasterInitialState.processMessage what=3
09-07 12:06:25.594  6798  6798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 12:06:25.598  6798  6798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 12:06:25.600  6497  6497 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-07 12:06:25.606  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-07 12:06:25.606  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-07 12:06:25.606  1037  1037 D Ulp_jni : JNI:system_update. Event-4
09-07 12:06:25.608  1037  1527 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
09-07 12:06:25.608  1037  1527 I LGFTMITEM: [GET_FTM][id=6], offset=12288
,09-07 12:06:25.612  1037  1527 E WifiUtil: wfc_util_ffile_check_copy(): pid[1037] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
09-07 12:06:25.612  1037  1527 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-07 12:06:25.612  1037  1527 E WifiUtil: wfc_util_ffile_check_copy(): pid[1037] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
09-07 12:06:25.612  1037  1527 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-07 12:06:25.612  1037  1527 I WifiUtil: Intf0MacAddress=C49A027FFB5D
09-07 12:06:25.612  1037  1527 E WifiHW  : unknown target_country: EU , set to default
09-07 12:06:25.612  1037  1527 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
09-07 12:06:25.612  1037  1527 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
09-07 12:06:25.612  1037  1527 I WifiUtil: gEnableBmps=1
09-07 12:06:25.624  5859  5859 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,09-07 12:06:25.633  5859  5859 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
09-07 12:06:25.635  6497  6937 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,09-07 12:06:25.667  2163  2163 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-07 12:06:25.702  1037  1099 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-07 12:06:25.743  1037  1965 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7105 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,09-07 12:06:25.750  1037  1099 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 12:06:25.750  1037  1099 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 12:06:25.766   351   351 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 412us total 20.135ms
,09-07 12:06:25.787   351   351 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 424us total 20.935ms
,09-07 12:06:25.807   351   351 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 412us total 19.599ms
,09-07 12:06:25.811  7105  7105 I AppUp4:AppBoxCP: onCreate
,09-07 12:06:25.811  7105  7105 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
09-07 12:06:25.822  7105  7105 I AppUp4:DB:  setFingerPrint start
,09-07 12:06:25.822  7105  7105 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
09-07 12:06:25.831  7105  7105 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
09-07 12:06:25.831  7105  7105 I AppUp4:DB:  SDK version = 21
09-07 12:06:25.831  7105  7105 I AppUp4:DB:  beforefinger == newfinger no write in DB
09-07 12:06:25.833  7105  7105 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
09-07 12:06:25.834  7105  7105 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-07 12:06:25.834  7105  7105 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-07 12:06:25.837  7105  7105 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
,09-07 12:06:25.837  7105  7105 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,09-07 12:06:25.845  7105  7105 I AppUp4:CustModeStarterReceiver: onReceive
09-07 12:06:25.887  7105  7105 D LgDataFeature: LgDataFeature() Constructor: none
09-07 12:06:25.887  7105  7105 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-07 12:06:25.897  7105  7105 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@3e0cc071
09-07 12:06:25.897  7105  7105 D AppUp4:CustFacade: isCustomizationCompleted : false
09-07 12:06:25.897  7105  7105 D AppUp4:CustFacade: isPhone : true
09-07 12:06:25.898  7105  7105 D AppUp4:CustModeStarterReceiver: begin check event
09-07 12:06:25.898  7105  7105 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
09-07 12:06:25.899  7105  7105 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
09-07 12:06:25.899  7105  7125 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
09-07 12:06:25.900  7105  7125 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
09-07 12:06:25.900  7105  7125 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
09-07 12:06:25.903  1037  1964 I ActivityManager: Killing 6621:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,09-07 12:06:25.963  1037  2001 W libprocessgroup: failed to open /acct/uid_10061/pid_6621/cgroup.procs: No such file or directory
,09-07 12:06:25.964  4760  4760 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-07 12:06:25.965  4760  4760 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-07 12:06:25.971  4760  4760 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-07 12:06:25.975  4760  4760 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-07 12:06:25.984  4760  7127 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-07 12:06:25.989  4760  7128 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-07 12:06:25.990  4760  7128 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-07 12:06:26.065  1037  1564 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7132 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,09-07 12:06:26.134  7132  7132 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-07 12:06:26.135  7132  7132 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-07 12:06:26.136  7132  7132 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,09-07 12:06:26.137  7132  7132 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,09-07 12:06:26.240  7132  7132 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,09-07 12:06:26.256  7132  7132 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
09-07 12:06:26.325  7132  7132 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-07 12:06:26.367  7132  7132 D LgDataFeature: LgDataFeature() Constructor: none
,09-07 12:06:26.367  7132  7132 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-07 12:06:26.483  1037  1119 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-07 12:06:26.483  1037  1119 D Tethering: InitialState.processMessage what=4
,09-07 12:06:26.486   309   894 D SoftapController: Softap fwReload - Ok
09-07 12:06:26.489  1037  1527 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (871ms)
09-07 12:06:26.491  1037  1119 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-07 12:06:26.493   309   894 D CommandListener: Setting iface cfg
09-07 12:06:26.493   309   894 D CommandListener: Trying to bring down wlan0
09-07 12:06:26.494   309   894 D CommandListener: Clearing all IP addresses on wlan0
09-07 12:06:26.499  1037  1527 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
09-07 12:06:26.501  1037  1527 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-07 12:06:26.501  1037  1527 E WifiStateMachine: useWiFiOffloading() : false
09-07 12:06:26.501  1037  1527 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,09-07 12:06:26.506  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 12:06:26.506  1930  1930 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
09-07 12:06:26.508  1037  1527 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-07 12:06:26.508  1037  1527 D WifiMonitor: connecting to supplicant
09-07 12:06:26.509  6798  6798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 12:06:26.511  6798  6798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 12:06:26.504  7161  7161 W wpa_supplicant: type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-07 12:06:26.513  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
09-07 12:06:26.504  7161  7161 W wpa_supplicant: type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-07 12:06:26.537  7161  7161 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-07 12:06:26.563  7132  7132 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,09-07 12:06:26.569  7161  7161 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-07 12:06:26.569  7161  7161 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
09-07 12:06:26.598  3161  3161 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-07 12:06:26.598  3161  3161 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-07 12:06:26.598  3161  3161 I LgeMiscReceiver: networkInfo.isConnected() = false
,09-07 12:06:26.602  7132  7132 I HubEmail: JNI_OnLoad()
09-07 12:06:26.602  7132  7132 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-07 12:06:26.602  7132  7132 I HubEmail: registerNatives()
09-07 12:06:26.602  7132  7132 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-07 12:06:26.602  7132  7132 I HubEmail: registerNativeMethods()
,09-07 12:06:26.602  7132  7132 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-07 12:06:26.602  7132  7132 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
09-07 12:06:26.644  1037  1893 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7172 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,09-07 12:06:26.650  7008  7169 W FormManager: Network not available. Please check & try again.
09-07 12:06:26.652  7132  7171 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 12:06:26.659  7008  7170 V FormManager: Network unavailable.
,09-07 12:06:26.671  7161  7161 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-07 12:06:26.675  7008  7170 V FormManager: Network unavailable.
09-07 12:06:26.680  1037  1053 I ActivityManager: Killing 6658:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
09-07 12:06:26.715  7161  7161 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,09-07 12:06:26.721  7161  7161 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
,09-07 12:06:26.721  1037  1527 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
09-07 12:06:26.722  1037  1527 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
,09-07 12:06:26.723  1037  1527 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
09-07 12:06:26.723  1037  1527 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
09-07 12:06:26.724  1037  7190 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
09-07 12:06:26.724  1037  1527 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-07 12:06:26.724  1037  7190 D WifiMonitor: Dropping event because (p2p0) is stopped
09-07 12:06:26.724  1037  1527 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-07 12:06:26.724  1037  1527 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-07 12:06:26.725  1037  1527 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-07 12:06:26.725  1037  1527 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
09-07 12:06:26.725  1037  1527 D WifiNative-wlan0: doString: [DRIVER MACADDR]
09-07 12:06:26.726  1037  1527 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
09-07 12:06:26.726  1037  1527 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
09-07 12:06:26.726  1037  1527 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
,09-07 12:06:26.738  7161  7161 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
09-07 12:06:26.738  1037  7190 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-07 12:06:26.738  1037  7190 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
,09-07 12:06:26.738  1037  7190 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
09-07 12:06:26.739  1037  7190 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
09-07 12:06:26.739  1037  7190 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
09-07 12:06:26.739  1037  7190 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
09-07 12:06:26.746  1037  1694 W libprocessgroup: failed to open /acct/uid_10080/pid_6658/cgroup.procs: No such file or directory
09-07 12:06:26.748  1037  1527 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-07 12:06:26.748  1037  1527 E WifiStateMachine: useWiFiOffloading() : false
09-07 12:06:26.748  1037  1527 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-07 12:06:26.750  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 12:06:26.750  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 12:06:26.750  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 12:06:26.750  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 12:06:26.750  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-07 12:06:26.753  1037  1527 D WifiNative-wlan0: doBoolean: SET update_config 1
,09-07 12:06:26.753  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 12:06:26.754  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
09-07 12:06:26.755  1930  1930 D WfdService: Waiting for WifiP2p enabling
09-07 12:06:26.755  1037  1532 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
09-07 12:06:26.756  6798  6798 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 12:06:26.756  6798  6798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 12:06:26.756  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:06:26.756  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 12:06:26.756  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 12:06:26.756  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 12:06:26.756  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 12:06:26.756  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 12:06:26.756  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 12:06:26.756  6798  6798 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 12:06:26.757  6798  6798 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-07 12:06:26.757  1037  1527 D WifiNative-wlan0: SET update_config 1: returned true
09-07 12:06:26.757  1037  1527 D WifiConfigStore: Loading config and enabling all networks 
09-07 12:06:26.757  1037  1527 D WifiNative-wlan0: doString: [LIST_NETWORKS]
09-07 12:06:26.758  1037  1527 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
09-07 12:06:26.759  6798  6798 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 12:06:26.759  6798  6798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 12:06:26.759  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:06:26.759  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 12:06:26.759  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 12:06:26.759  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 12:06:26.759  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 12:06:26.759  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 12:06:26.759  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 12:06:26.760  6798  6798 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 12:06:26.760  6798  6798 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-07 12:06:26.771  1037  1527 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
,09-07 12:06:26.782  1037  1527 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
09-07 12:06:26.782  1037  1527 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-07 12:06:26.783  1037  1527 D WifiStateMachine: enableVerboseLogging : level 2
09-07 12:06:26.783  1037  1527 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
09-07 12:06:26.784  1037  1527 D WifiNative-wlan0: SET device_name g3_global_com: returned true
09-07 12:06:26.784  1037  1527 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
09-07 12:06:26.784  1037  1527 D WifiNative-wlan0: SET manufacturer LGE: returned true
09-07 12:06:26.784  1037  1527 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
09-07 12:06:26.785  1037  1527 D WifiNative-wlan0: SET model_name LG-D855: returned true
09-07 12:06:26.785  1037  1527 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
09-07 12:06:26.785  1037  1527 D WifiNative-wlan0: SET model_number LG-D855: returned true
,09-07 12:06:26.785  1037  1527 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
09-07 12:06:26.786  1037  1527 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
09-07 12:06:26.786  1037  1527 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
09-07 12:06:26.787  1037  1527 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
09-07 12:06:26.787  1037  1527 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
09-07 12:06:26.787  1037  1527 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
09-07 12:06:26.789  1037  1527 D WifiStateMachine: Setting OUI to DA-A1-19
09-07 12:06:26.789  1037  1527 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
09-07 12:06:26.789  1930  1930 D WfdsService: Supplicant Connection state is changed : true
09-07 12:06:26.789  1930  2316 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
09-07 12:06:26.789  1930  2316 D WfdsService: Set the WFDS Monitor: true
09-07 12:06:26.789  1930  2316 D WfdsMonitor: WfdsMonitorThread create
09-07 12:06:26.790  1930  2316 D WfdsMonitor: WFDS Monitor is created and started
09-07 12:06:26.790  1037  1527 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
09-07 12:06:26.790  1930  2316 D WfdsService: WiFi: Supplicant connection re-established
09-07 12:06:26.790  1037  1527 D WifiNative-HAL: Setting external_sim to 1
09-07 12:06:26.790  1037  1527 D WifiNative-wlan0: doBoolean: SET external_sim 1
,09-07 12:06:26.790  1037  1527 D WifiNative-wlan0: SET external_sim 1: returned true
09-07 12:06:26.790  1037  1527 I WifiNative-HAL: startHal
09-07 12:06:26.790  1037  1527 D wifi    : setting scan oui 0xaf6111e0
09-07 12:06:26.791  1930  7191 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
,09-07 12:06:26.791  1037  1527 D WifiStateMachine: Setting OUI to DA-A1-19
09-07 12:06:26.791  1037  1527 I WifiNative-HAL: startHal
09-07 12:06:26.791  1037  1527 D wifi    : setting scan oui 0xaf6111e0
09-07 12:06:26.791  1037  1527 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
,09-07 12:06:26.791  1930  7191 E CtrlSupplicant: Succeed to open control connection
09-07 12:06:26.791  1930  7191 E CtrlSupplicant: Succeed to open monitor connection
09-07 12:06:26.791  1037  1527 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
09-07 12:06:26.791  1037  1527 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
,09-07 12:06:26.792  1930  7191 D WfdsMonitor: Supplicant connection established
09-07 12:06:26.792  7161  7161 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
09-07 12:06:26.792  1930  2316 D WfdsService: Connected to the supplicant for wfds
09-07 12:06:26.792  1037  1527 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
,09-07 12:06:26.793  1037  1527 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-07 12:06:26.793  7161  7161 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-07 12:06:26.793  1037  1527 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-07 12:06:26.794  1037  1527 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
,09-07 12:06:26.794  7161  7161 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
09-07 12:06:26.794  1037  1527 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
09-07 12:06:26.794  1037  1527 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-07 12:06:26.794  7161  7161 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
,09-07 12:06:26.794  1037  1527 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-07 12:06:26.794  1037  1527 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-07 12:06:26.795  7161  7161 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-07 12:06:26.795  1037  1527 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
,09-07 12:06:26.795  1037  1527 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
09-07 12:06:26.795  7161  7161 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
09-07 12:06:26.795  1037  1527 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
09-07 12:06:26.795  1037  1527 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
,09-07 12:06:26.795  7161  7161 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-07 12:06:26.796  1037  1527 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-07 12:06:26.797  1037  1527 E WifiNative: : [181,012,108 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
09-07 12:06:26.797  1037  1527 D WifiNative-wlan0: doBoolean: RECONNECT
,09-07 12:06:26.797  1037  1527 D WifiNative-wlan0: RECONNECT: returned true
09-07 12:06:26.797  1037  1527 D WifiNative-wlan0: doString: [STATUS]
09-07 12:06:26.798  1037  7190 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-07 12:06:26.798  1037  7190 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
,09-07 12:06:26.798  1037  1527 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-07 12:06:26.798  1037  1527 D WifiNative-wlan0: doBoolean: SET ps 1
09-07 12:06:26.798  1037  1527 D WifiNative-wlan0: SET ps 1: returned true
09-07 12:06:26.799  1037  1526 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
,09-07 12:06:26.800   309   894 D CommandListener: Setting iface cfg
09-07 12:06:26.800   309   894 D CommandListener: Trying to bring up p2p0
09-07 12:06:26.801  1037  1526 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-07 12:06:26.801  1037  1526 D LGWifiP2pService: P2pEnablingState
09-07 12:06:26.801  1037  1526 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
09-07 12:06:26.801  1037  1526 D LGWifiP2pService: P2p socket connection successful
09-07 12:06:26.801  1037  1526 D LGWifiP2pService: P2pEnabledState
09-07 12:06:26.803  1930  1930 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
09-07 12:06:26.803  1930  1930 D WfdsService: WifiP2pState is changed : true
09-07 12:06:26.804  1930  2316 D WfdsService: Receive the WFDS_ENABLE Method
09-07 12:06:26.804  1930  2316 D WfdsService: Set the WFDS Monitor: true
09-07 12:06:26.804  1930  2316 D WfdsService: Connected to the supplicant for wfds
09-07 12:06:26.804  1930  2316 D WfdsJNI : doCommand: WFDS_SET TRUE
09-07 12:06:26.804  7161  7161 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
09-07 12:06:26.804  1930  2316 D WfdsService: selectPreferredScanChannel [36]
09-07 12:06:26.804  1930  2316 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
09-07 12:06:26.806  1037  1526 D LGWifiP2pService: sending p2p connection changed broadcast
09-07 12:06:26.806  1037  1526 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
09-07 12:06:26.807  1037  1526 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
09-07 12:06:26.807  1037  1526 D WifiNative-p2p0: doBoolean: SET device_name G3
09-07 12:06:26.807  1037  1527 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
09-07 12:06:26.808  1037  1526 D WifiNative-p2p0: SET device_name G3: returned true
09-07 12:06:26.808  1037  1526 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
09-07 12:06:26.808  1037  1526 D LGWifiP2pService: before postfix = G3
09-07 12:06:26.808  1037  1526 D WifiServerServiceExt: postfix byte check : 2
09-07 12:06:26.808  1037  1526 D LGWifiP2pService: after postfix = G3
,09-07 12:06:26.808  1037  1526 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
,09-07 12:06:26.808  1037  1527 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
09-07 12:06:26.808  1930  1930 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
09-07 12:06:26.808  1037  1526 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
09-07 12:06:26.808  1037  1526 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
09-07 12:06:26.809  1037  1527 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
09-07 12:06:26.809  1930  1930 D WfdsService: isConnected: false
09-07 12:06:26.809  1037  1526 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
09-07 12:06:26.809  1037  1526 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
09-07 12:06:26.809  1037  1527 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
09-07 12:06:26.809  1037  1526 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
09-07 12:06:26.809  1037  1526 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
09-07 12:06:26.810  1037  1037 D WifiScanningService: SCAN_AVAILABLE : 3
09-07 12:06:26.810  1037  1527 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=181025  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-07 12:06:26.810  1037  1526 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
09-07 12:06:26.810  1037  1526 D WifiNative-HAL: p2pGetDeviceAddress
09-07 12:06:26.810  1037  1545 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-07 12:06:26.810  1037  1545 I WifiNative-HAL: startHal
,09-07 12:06:26.810  1037  1526 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
09-07 12:06:26.810  1037  1037 D RttService: SCAN_AVAILABLE : 3
09-07 12:06:26.810  1037  1546 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-07 12:06:26.811  1037  1545 D wifi    : getting scan capabilities on interface[1] = 0xaf6111e0
09-07 12:06:26.811  1037  1545 D wifi    : failed to get capabilities : -3
09-07 12:06:26.811  1037  1545 E WifiScanningService: could not get scan capabilities
09-07 12:06:26.814  1037  1527 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=181028  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-07 12:06:26.814  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 12:06:26.815  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 12:06:26.815  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-07 12:06:26.815  1592  1592 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-07 12:06:26.815  1592  1592 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-07 12:06:26.815  1037  1527 E WifiStateMachine:  DisconnectedState what:132106 1 0
09-07 12:06:26.815  1930  1930 I WfdStateTracker: handleP2pThisDeviceChanged
09-07 12:06:26.815  1930  1930 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
09-07 12:06:26.816  1930  1930 D WfdsService: Update P2p Interface State: 3
09-07 12:06:26.816  1037  1527 E WifiStateMachine:  ConnectModeState what:132106 1 0
09-07 12:06:26.816  1037  1526 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
09-07 12:06:26.816  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 12:06:26.816  1037  1526 D WifiNative-p2p0: doBoolean: P2P_FLUSH
09-07 12:06:26.816  1037  1527 E WifiStateMachine:  DriverStartedState what:132106 1 0
09-07 12:06:26.816  1037  1527 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
09-07 12:06:26.816  7161  7161 E wpa_supplicant: nWIFIDualbandAPConnection: 1
09-07 12:06:26.817  1037  1527 E WifiStateMachine:  DisconnectedState what:132096 -100 0
09-07 12:06:26.817  1037  1526 D WifiNative-p2p0: P2P_FLUSH: returned true
09-07 12:06:26.817  1037  1526 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
09-07 12:06:26.818  1037  1527 E WifiStateMachine:  ConnectModeState what:132096 -100 0
09-07 12:06:26.818  1037  1526 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
09-07 12:06:26.818  1037  1526 D WifiNative-p2p0: doString: [LIST_NETWORKS]
09-07 12:06:26.818  1037  1527 E WifiStateMachine:  DriverStartedState what:132096 -100 0
09-07 12:06:26.818  1037  1526 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
09-07 12:06:26.818  1037  1527 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
09-07 12:06:26.818  1037  1526 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
09-07 12:06:26.818  7161  7161 E wpa_supplicant: disconnect_rssi_lvl: -100
09-07 12:06:26.819  1037  1527 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
09-07 12:06:26.820  1037  1527 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
09-07 12:06:26.820  1037  1527 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
09-07 12:06:26.820  1037  1527 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
09-07 12:06:26.829  1037  1526 D WifiNative-p2p0: SAVE_CONFIG: returned true
09-07 12:06:26.829  1037  1526 D LGWifiP2pService: sending p2p persistent groups changed broadcast
09-07 12:06:26.829  1037  1526 D LGWifiP2pService: InactiveState
09-07 12:06:26.830  1037  1526 D LGWifiP2pService: InactiveState{ when=-12ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-07 12:06:26.830  1037  1526 D LGWifiP2pService: P2pEnabledState{ when=-12ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-07 12:06:26.830  1037  1526 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
09-07 12:06:26.831  7161  7161 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-07 12:06:26.832  7161  7161 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-07 12:06:26.832  1037  7190 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-07 12:06:26.832  1037  7190 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-07 12:06:26.832  1037  7190 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-07 12:06:26.832  1037  7190 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-07 12:06:26.832  1930  7191 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-07 12:06:26.832  7161  7161 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-07 12:06:26.833  7161  7161 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 12:06:26.833  1930  7191 D WfdsMonitor: Event [CTRL-EVENT-R,EGDOM-CHANGE init=DRIVER type=WORLD]
09-07 12:06:26.833  1037  7190 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-07 12:06:26.833  1037  7190 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 12:06:26.833  1037  7190 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 12:06:26.833  1037  7190 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 12:06:26.833  1037  1526 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
,09-07 12:06:26.833  7161  7161 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 12:06:26.833  1930  7191 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-07 12:06:26.834  1037  7190 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-07 12:06:26.834  1037  7190 E WifiMonitor: WifiMonitor:p2p0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 12:06:26.834  1037  7190 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 12:06:26.834  1037  7190 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 12:06:26.834  1037  1526 D LGWifiP2pService: InactiveState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-07 12:06:26.834  1037  1526 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-07 12:06:26.834  1037  1526 D LGWifiP2pService: DefaultState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-07 12:06:26.835  1037  1526 D LGWifiP2pService: InactiveState{ when=-6ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-07 12:06:26.835  1037  1526 D LGWifiP2pService: P2pEnabledState{ when=-6ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-07 12:06:26.835  1037  1526 D LGWifiP2pService: DefaultState{ when=-6ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-07 12:06:26.835  7161  7161 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-07 12:06:26.835  1037  1526 D LGWifiP2pService: InactiveState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-07 12:06:26.835  1037  1526 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-07 12:06:26.835  1037  1526 D LGWifiP2pService: DefaultState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-07 12:06:26.836  7161  7161 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-07 12:06:26.836  7161  7161 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-07 12:06:26.836  7161  7161 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 12:06:26.836  1930  2316 W WfdsService: DefaultState - msg [9441285] is not handled
09-07 12:06:26.836  1037  7190 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-07 12:06:26.837  1037  7190 E WifiMonitor: WifiMonitor:wlan0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-07 12:06:26.837  1037  7190 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-07 12:06:26.837  1037  7190 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-07 12:06:26.837  1037  7190 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-07 12:06:26.837  1037  7190 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 12:06:26.837  1037  7190 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 12:06:26.837  7161  7161 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 12:06:26.837  1037  7190 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 12:06:26.837  1037  7190 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-07 12:06:26.837  1037  7190 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 12:06:26.837  1037  7190 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 12:06:26.837  1037  7190 E WifiMonitor: handleEvent unkno,wn: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 12:06:26.838  1037  1527 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
09-07 12:06:26.838  1037  1527 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
09-07 12:06:26.838  1930  7191 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-07 12:06:26.839  1930  7191 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-07 12:06:26.839  1037  1527 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
09-07 12:06:26.839  1037  1527 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
09-07 12:06:26.839  1037  1527 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
09-07 12:06:26.840  1037  1526 D LGWifiP2pService: InactiveState{ when=-10ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-07 12:06:26.840  1037  1526 D LGWifiP2pService: P2pEnabledState{ when=-10ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-07 12:06:26.840  1037  1526 D LGWifiP2pService: DefaultState{ when=-10ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-07 12:06:26.840  1037  1526 D LGWifiP2pService: InactiveState{ when=-2ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-07 12:06:26.840  1037  1037 E WifiServerServiceExt: No p2p device connected
09-07 12:06:26.840  1037  1526 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-07 12:06:26.840  7161  7161 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
09-07 12:06:26.841  7161  7161 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-07 12:06:26.842  1037  7190 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
09-07 12:06:26.842  1037  1527 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
09-07 12:06:26.842  1037  7190 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
,09-07 12:06:26.842  1037  1527 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
09-07 12:06:26.842  1037  7190 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-07 12:06:26.842  1037  7190 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-07 12:06:26.843  1037  1527 D WifiNative-wlan0: BSS_FLUSH 0: returned true
09-07 12:06:26.843  1037  1527 D WifiNative-wlan0: doBoolean: SCAN
09-07 12:06:26.843  1037  1527 D WifiNative-wlan0: SCAN: returned false
09-07 12:06:26.844  1037  1527 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=181060  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-07 12:06:26.845  1037  1527 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=181061  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-07 12:06:26.846  1037  1527 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-07 12:06:26.847  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 12:06:26.847  1037  1527 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
,09-07 12:06:26.847  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 12:06:26.847  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-07 12:06:26.847  1037  1527 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-07 12:06:26.847  1592  1592 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 12:06:26.847  1592  1592 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-07 12:06:26.848  1037  1527 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-07 12:06:26.848  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 12:06:26.848  1037  1527 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-07 12:06:26.849  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
,09-07 12:06:26.850  1037  1037 D WifiServerServiceExt: setSupplicantStateSCANNING
09-07 12:06:26.851  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-07 12:06:26.851  1037  1037 D WifiServerServiceExt: setSupplicantStateSCANNING
,09-07 12:06:26.865  7172  7172 D LgDataFeature: LgDataFeature() Constructor: none
,09-07 12:06:26.865  7172  7172 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-07 12:06:26.868  7172  7172 D PhoneMonitor: Register our PhoneStateListener
09-07 12:06:26.879  7172  7172 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,09-07 12:06:26.881  7172  7172 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-07 12:06:26.891  7172  7172 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
09-07 12:06:26.892  7172  7172 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
09-07 12:06:26.893  7172  7172 D TelephonyAutoProfiling: [parse] Load xml
,09-07 12:06:26.896  7172  7172 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
,09-07 12:06:26.896  7172  7172 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
09-07 12:06:26.896  7172  7172 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
09-07 12:06:26.896  7172  7172 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
09-07 12:06:26.896  7172  7172 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
09-07 12:06:26.896  7172  7172 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
09-07 12:06:26.896  7172  7172 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
09-07 12:06:26.897  7172  7172 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
09-07 12:06:26.897  7172  7172 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
09-07 12:06:26.897  7172  7172 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
09-07 12:06:26.897  7172  7172 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
09-07 12:06:26.897  7172  7172 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
09-07 12:06:26.897  7172  7172 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
09-07 12:06:26.897  7172  7172 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
09-07 12:06:26.897  7172  7172 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
09-07 12:06:26.897  7172  7172 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
09-07 12:06:26.897  7172  7172 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
09-07 12:06:26.903  7172  7172 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
09-07 12:06:26.944  1037  1053 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7194 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-07 12:06:26.945  1037  1053 I ActivityManager: Killing 6206:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,09-07 12:06:27.004  1037  2001 W libprocessgroup: failed to open /acct/uid_10097/pid_6206/cgroup.procs: No such file or directory
,09-07 12:06:27.279  1037  2001 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7218 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,09-07 12:06:27.286  1037  2001 I ActivityManager: Killing 6679:com.lge.eula/1000 (adj 15): empty #17
09-07 12:06:27.325  7161  7161 E wpa_supplicant: USIM:  scard_init function
09-07 12:06:27.325  7161  7161 I wpa_supplicant: Trying to associate with SSID 'NG700'
09-07 12:06:27.326  1037  7190 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
09-07 12:06:27.327  1037  7190 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
09-07 12:06:27.327  1037  7190 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
09-07 12:06:27.327  1037  7190 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: WPS-AP-AVAILABLE 
09-07 12:06:27.327  1037  7190 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
09-07 12:06:27.327  1037  7190 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
,09-07 12:06:27.327  1037  7190 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
,09-07 12:06:27.332  1037  1527 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
09-07 12:06:27.333  1037  1527 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
09-07 12:06:27.333  1037  1527 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
09-07 12:06:27.334  1037  1527 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
09-07 12:06:27.334  1037  1527 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
09-07 12:06:27.343  1037  2039 W libprocessgroup: failed to open /acct/uid_1000/pid_6679/cgroup.procs: No such file or directory
,09-07 12:06:27.355  1037  1527 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=181571  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-07 12:06:27.357  1037  1527 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=181573  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,09-07 12:06:27.365  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 12:06:27.365  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 12:06:27.365  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-07 12:06:27.365  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-07 12:06:27.365  1037  1037 D WifiServerServiceExt: setSupplicantStateASSOCIATING
09-07 12:06:27.369  1592  1592 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 12:06:27.370  1592  1592 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-07 12:06:27.372  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 12:06:27.444  7161  7161 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
09-07 12:06:27.447  1037  7190 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
09-07 12:06:27.447  1037  7190 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
09-07 12:06:27.447  1037  7190 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
09-07 12:06:27.448  1037  7190 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: Associated with f4:f2:6d:22:99:3e
09-07 12:06:27.448  1037  7190 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-07 12:06:27.448  1037  7190 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-07 12:06:27.450  1037  1527 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=181665  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-07 12:06:27.451  1037  1527 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=181666  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-07 12:06:27.452  1037  1527 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=181668
09-07 12:06:27.453  1037  1527 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=181669
09-07 12:06:27.454  1037  1527 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=181670
09-07 12:06:27.455  1037  1527 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=181670
09-07 12:06:27.456  1037  1527 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=181671
09-07 12:06:27.457  1037  1527 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=181672  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
,09-07 12:06:27.464  7161  7161 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-07 12:06:27.464  7161  7161 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-07 12:06:27.474  1037  7190 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-07 12:06:27.475  1037  7190 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,09-07 12:06:27.475  1037  7190 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
09-07 12:06:27.475  1037  7190 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-07 12:06:27.475  1037  7190 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-07 12:06:27.475  1037  7190 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
09-07 12:06:27.475  1037  7190 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-07 12:06:27.475  1037  7190 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-07 12:06:27.475  1037  7190 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-07 12:06:27.475  1037  7190 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-07 12:06:27.476  1037  1874 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7240 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-07 12:06:27.478  1037  1874 I ActivityManager: Killing 6696:com.lge.bnr/1000 (adj 15): empty #17
09-07 12:06:27.529  1037  1526 D LGWifiP2pService: InactiveState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-07 12:06:27.529  1037  1526 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-07 12:06:27.529  1037  1526 D LGWifiP2pService: DefaultState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,09-07 12:06:27.534  1037  1119 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-07 12:06:27.536  1037  1053 W libprocessgroup: failed to open /acct/uid_1000/pid_6696/cgroup.procs: No such file or directory
,09-07 12:06:27.553  1037  1527 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=181769  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
,09-07 12:06:27.558  1592  1592 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-07 12:06:27.558  1592  1592 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-07 12:06:27.561  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 12:06:27.563  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 12:06:27.563  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 12:06:27.563  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-07 12:06:27.569  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 12:06:27.570  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 12:06:27.572  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
,09-07 12:06:27.573  1037  1527 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=181789  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-07 12:06:27.574  1037  1527 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=181790  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-07 12:06:27.574  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-07 12:06:27.575  1037  1037 D WifiServerServiceExt: setSupplicantStateASSOCIATED
09-07 12:06:27.575  1037  1527 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=181790
09-07 12:06:27.575  1037  1527 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=181791
09-07 12:06:27.576  1037  1527 D WifiNative-wlan0: doString: [STATUS]
09-07 12:06:27.576  1037  7190 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-07 12:06:27.576  1037  7190 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-07 12:06:27.576  1037  1527 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-07 12:06:27.579  1037  1527 I WifiServiceExtension: setVHTCapabilityType  : false
09-07 12:06:27.584  1037  1527 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
09-07 12:06:27.584  1037  1527 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
09-07 12:06:27.585  1592  1592 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 12:06:27.585  1592  1592 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-07 12:06:27.587  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-07 12:06:27.596  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 12:06:27.596  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 12:06:27.596  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-07 12:06:27.598  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 12:06:27.598  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 12:06:27.598  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,09-07 12:06:27.601  1037  1527 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
09-07 12:06:27.601  1037  1534 D ConnectivityService: Got NetworkAgent Messenger
09-07 12:06:27.601  1037  1527 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-07 12:06:27.601  1037  1527 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-07 12:06:27.601  1037  1534 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-07 12:06:27.602  1037  1534 D ConnectivityService: NetworkAgent connected
09-07 12:06:27.602  1037  1527 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-07 12:06:27.602  1037  1527 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-07 12:06:27.608  1592  1592 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 12:06:27.608  1592  1592 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-07 12:06:27.609  1037  1527 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-07 12:06:27.609  1037  1527 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-07 12:06:27.609  1037  1527 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-07 12:06:27.611  1037  1527 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-07 12:06:27.611  1037  1527 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-07 12:06:27.612  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-07 12:06:27.614  1037  1527 D WifiNative-wlan0: SAVE_CONFIG: returned true
,09-07 12:06:27.615   309   894 D CommandListener: Setting iface cfg
09-07 12:06:27.616  1592  1592 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 12:06:27.616  1592  1592 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-07 12:06:27.617  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 12:06:27.619  7240  7240 I art     : Almond Protected OAT
09-07 12:06:27.620  1037  1527 E WifiStateMachine: Start Dhcp Watchdog 2
09-07 12:06:27.621  1037  1527 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=181836  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-07 12:06:27.621  1037  1527 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=181837  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-07 12:06:27.622  1037  1527 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=181837  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-07 12:06:27.622  1037  1527 E WifiStateMachine:  ObtainingIpState CMD_STOP_SUPPLICANT_FAILED 1 0
09-07 12:06:27.623  1037  1527 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-07 12:06:27.623  1037  1527 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
09-07 12:06:27.624  1037  1527 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-07 12:06:27.624  1037  1527 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-07 12:06:27.624  1037  1527 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
09-07 12:06:27.625  1037  7259 D DhcpStateMachine: StoppedState
09-07 12:06:27.625  1037  7259 D DhcpStateMachine: StoppedState{ when=-5ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
09-07 12:06:27.625  1037  7259 D DhcpStateMachine: WaitBeforeStartState
09-07 12:06:27.626  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-07 12:06:27.626  1037  1037 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
09-07 12:06:27.627  1037  1527 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
09-07 12:06:27.627  1037  1527 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
09-07 12:06:27.628  1037  1527 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
09-07 12:06:27.628  1037  1527 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
09-07 12:06:27.628  1037  1527 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
09-07 12:06:27.629  1037  1527 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-07 12:06:27.630  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-07 12:06:27.630  1037  1037 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
09-07 12:06:27.631  1037  1527 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=181846  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-07 12:06:27.631  1037  1527 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=181847  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-07 12:06:27.632  1037  1527 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=181848  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-07 12:06:27.633  1037  1527 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:135183] from screen [on:0 period:69005105] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
09-07 12:06:27.634  1037  1527 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx,:0 period:1] from screen [on:0 period:69005106] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
09-07 12:06:27.634  1037  1527 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,09-07 12:06:27.640  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 12:06:27.641  1037  1534 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
09-07 12:06:27.641  1037  1527 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 12:06:27.642  1037  1527 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 12:06:27.643  1037  1527 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 12:06:27.643  1037  1527 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 12:06:27.644  1037  1527 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 12:06:27.644  1037  1527 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 12:06:27.645  1037  1534 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-07 12:06:27.646  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-07 12:06:27.646  1037  1037 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-07 12:06:27.647  1037  1527 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=103,0,0
,09-07 12:06:27.647  1037  1527 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=103,0,0
09-07 12:06:27.649  1037  1527 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
09-07 12:06:27.650  7161  7161 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
09-07 12:06:27.650  1037  1527 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
09-07 12:06:27.650  1037  1527 D WifiNative-wlan0: doBoolean: SET ps 0
09-07 12:06:27.651  1037  1527 D WifiNative-wlan0: SET ps 0: returned true
09-07 12:06:27.651  1037  1527 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
09-07 12:06:27.651  7161  7161 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
09-07 12:06:27.652  1037  1527 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
09-07 12:06:27.653  1037  1526 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1d3ccba2 target=com.android.internal.util.StateMachine$SmHandler }
09-07 12:06:27.653  1037  1526 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1d3ccba2 target=com.android.internal.util.StateMachine$SmHandler }
09-07 12:06:27.653  1037  7259 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
09-07 12:06:27.653  1037  7259 D DhcpStateMachine: DHCP Start wake lock is acquired.
09-07 12:06:27.653  1037  1527 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
09-07 12:06:27.653  1037  1527 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-07 12:06:27.654  1037  1527 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-07 12:06:27.655   309   894 D CommandListener: Setting iface cfg
09-07 12:06:27.655   309   894 D CommandListener: Trying to bring up wlan0
09-07 12:06:27.656  1037  1527 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
09-07 12:06:27.657  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-07 12:06:27.657  1037  1037 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-07 12:06:27.659  1037  1527 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
,09-07 12:06:27.659  1037  1527 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
,09-07 12:06:27.660  1037  1527 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 12:06:27.660  1037  1527 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 12:06:27.661  1037  1527 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 12:06:27.661  1037  1527 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 12:06:27.662  1037  1534 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-07 12:06:27.663  1037  1527 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-07 12:06:27.663  1037  1527 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-07 12:06:27.664  1037  1526 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-07 12:06:27.664  1037  1526 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-07 12:06:27.664  1037  1527 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-07 12:06:27.664  7161  7161 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-07 12:06:27.665  1037  1527 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-07 12:06:27.665  1037  1527 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
09-07 12:06:27.665  7161  7161 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
09-07 12:06:27.665  1037  1527 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
09-07 12:06:27.665  1037  1527 D WifiNative-wlan0: doBoolean: SET ps 1
09-07 12:06:27.681  1037  1527 D WifiNative-wlan0: SET ps 1: returned true
,09-07 12:06:27.682  1037  1534 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-07 12:06:27.683  1037  1527 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-07 12:06:27.683  1037  1527 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-07 12:06:27.683  1037  1527 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-07 12:06:27.684  1037  1534 D ConnectivityService: ignoring duplicate network state non-change
09-07 12:06:27.688  1592  1592 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 12:06:27.688  1592  1592 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-07 12:06:27.688  7240  7240 D WeatherApplication: removeAccount
09-07 12:06:27.689  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 12:06:27.690  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 12:06:27.690  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 12:06:27.690  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-07 12:06:27.692  1037  1534 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-07 12:06:27.693  7240  7240 D WeatherApplication: Account.length = 0
09-07 12:06:27.693  1037  1534 D ConnectivityService: Adding iface wlan0 to network 101
09-07 12:06:27.693  7240  7240 E WeatherApplication: OPERATOR:OPEN
,09-07 12:06:27.699  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 12:06:27.699  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 12:06:27.699  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-07 12:06:27.703  1930  1930 V WfdStateTracker: handleWifiStateChangedEvent: 1
09-07 12:06:27.704  1037  1037 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-07 12:06:27.705  7240  7240 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:6:27
09-07 12:06:27.705  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 12:06:27.705  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 12:06:27.706  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,09-07 12:06:27.707  1037  1527 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-07 12:06:27.708  7240  7240 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-07 12:06:27.708  7240  7240 D Weather.Utils: 2 : All the weather widget is gone.
09-07 12:06:27.710  7240  7240 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-07 12:06:27.711  1037  1037 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-07 12:06:27.712  1592  1592 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 12:06:27.712  1592  1592 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-07 12:06:27.713  7240  7240 D WeatherAncestor: connectivity changed - connection : true
09-07 12:06:27.713  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 12:06:27.715  7240  7240 D WeatherService: 2 : isServiceAlived():false forecastCache:null
09-07 12:06:27.718  1037  1534 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-07 12:06:27.718  1037  1534 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
09-07 12:06:27.719  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 12:06:27.719  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 12:06:27.719  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-07 12:06:27.720  1592  1592 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 12:06:27.720  1592  1592 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-07 12:06:27.720  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-07 12:06:27.721  1037  1534 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
09-07 12:06:27.722  7240  7240 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-07 12:06:27.722  7240  7240 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-07 12:06:27.723  7240  7240 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
09-07 12:06:27.724   309   894 E Netd    : netlink response contains error (File exists)
09-07 12:06:27.724  1037  1534 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
09-07 12:06:27.725  1037  1534 D ConnectivityService: addLocalRoutetoDefaultNetwork
09-07 12:06:27.725  1037  1534 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
09-07 12:06:27.725  1037  1534 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
09-07 12:06:27.730  1037  1534 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-07 12:06:27.730  1037  1534 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-07 12:06:27.730  1037  1534 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-07 12:06:27.730  1037  1534 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
09-07 12:06:27.730  1037  1534 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-07 12:06:27.730  1037  7258 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-07 12:06:27.730  1037  7258 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
09-07 12:06:27.730  1037  1534 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-07 12:06:27.731  1037  1534 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
,09-07 12:06:27.731  1037  7258 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-07 12:06:27.731  1037  1534 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 12:06:27.731  1037  7258 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-07 12:06:27.731  1037  1534 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
09-07 12:06:27.731  1037  1534 D ConnectivityService: currentScore = 0, newScore = 20
09-07 12:06:27.731  1037  1534 D ConnectivityService:    accepting network in place of null
09-07 12:06:27.731  1037  1534 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 12:06:27.731  1840  1840 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 12:06:27.732  1840  1840 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-07 12:06:27.732  1037  1527 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 12:06:27.732  1037  1527 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-07 12:06:27.732  1037  1534 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-07 12:06:27.732  1037  1534 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-07 12:06:27.732  1037  1534 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,09-07 12:06:27.734  1592  1592 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 12:06:27.734  1592  1592 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-07 12:06:27.734  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 12:06:27.735   309  7270 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
09-07 12:06:27.735  1037  1534 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-07 12:06:27.736  1037  1534 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
09-07 12:06:27.736  1037  1534 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
09-07 12:06:27.738  1037  1534 D ConnectivityService: validation of new default Network = false
09-07 12:06:27.738  1037  1534 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
09-07 12:06:27.738  1037  1534 D DSQN    : enableDataServiceNotify 
09-07 12:06:27.738  1037  1534 D DSQN    : start dsqn bin
09-07 12:06:27.739  1037  1037 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
09-07 12:06:27.739  1037  1037 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-07 12:06:27.739  1037  1037 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-07 12:06:27.739  1037  1037 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-07 12:06:27.743  1037  1534 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
09-07 12:06:27.743  1037  1534 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 12:06:27.743  1037  1534 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-07 12:06:27.743  1037  1534 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-07 12:06:27.744  1592  2035 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-07 12:06:27.734  7271  7271 W dsqn    : type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-07 12:06:27.734  7271  7271 W dsqn    : type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-07 12:06:27.751  1037  1525 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
09-07 12:06:27.757  7271  7271 E DSQN    : DSQN ssw
,09-07 12:06:27.763  7240  7240 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-07 12:06:27.763  7240  7240 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:6:27
,09-07 12:06:27.787  1037  1774 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7276 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-07 12:06:27.788  1037  1774 I ActivityManager: Killing 2113:com.lge.music/u0a34 (adj 15): empty #17
,09-07 12:06:27.797   309  7270 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
09-07 12:06:27.802   313   313 V AudioFlinger: 2113 died, releasing its sessions
09-07 12:06:27.802   313   313 V AudioFlinger:  pid 1840 @ 0
09-07 12:06:27.802   313   313 V AudioFlinger:  pid 3161 @ 1
09-07 12:06:27.802   313   313 V AudioFlinger:  pid 3161 @ 2
,09-07 12:06:27.835   309  7270 D libc-netbsd: res_queryN name = clients3.google.com succeed
,09-07 12:06:27.845  1805  7275 I CheckinService: active receiver: enabled
09-07 12:06:27.855  1037  7259 D DhcpStateMachine: DHCPV4 request on wlan0
,09-07 12:06:27.856  1037  7259 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
09-07 12:06:27.856  1037  7259 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
09-07 12:06:27.858  1037  1564 W libprocessgroup: failed to open /acct/uid_10034/pid_2113/cgroup.procs: No such file or directory
09-07 12:06:27.854  7294  7294 W dhcpcd  : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-07 12:06:27.864  1805  7275 I CheckinService: Preparing to send checkin request
09-07 12:06:27.864  1805  7275 I EventLogService: Accumulating logs since 1473242648756
09-07 12:06:27.854  7294  7294 W dhcpcd  : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-07 12:06:27.870  1592  1592 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,09-07 12:06:27.874  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 12:06:27.874   309   893 D LGDataListener: argv[0]=dsqncommand
09-07 12:06:27.874   309   893 D LGDataListener: argv[1]=wlan0
09-07 12:06:27.874   309   893 D LGDataListener: argv[2]=1
09-07 12:06:27.875   309   893 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
09-07 12:06:27.875  1037  1117 D DSQN    : DSQM DsqnNotification wlan0  1
09-07 12:06:27.876  1037  1117 D DSQN    : start to monitor internet connection
09-07 12:06:27.877  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 12:06:27.884  7294  7294 I dhcpcd  : version 5.5.6 starting
09-07 12:06:27.886  7294  7294 E dhcpcd  : get_duid: m
09-07 12:06:27.886  7294  7294 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
09-07 12:06:27.886  7294  7294 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,09-07 12:06:27.924  1037  7258 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 07 Sep 2016 10:06:27 GMT], X-Android-Received-Millis=[1473242787923], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473242787879]}
09-07 12:06:27.924  1037  7258 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-07 12:06:27.924  1037  7258 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
09-07 12:06:27.924  1037  1534 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
09-07 12:06:27.924  1037  1534 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
09-07 12:06:27.924  1037  1534 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-07 12:06:27.924  1037  1534 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-07 12:06:27.924  1037  1534 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-07 12:06:27.924  1037  1534 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
09-07 12:06:27.924  1805  7275 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
09-07 12:06:27.924  1037  1534 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,09-07 12:06:27.925  1037  1534 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 12:06:27.925  1037  1534 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-07 12:06:27.925  1037  1534 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-07 12:06:27.925  1037  1534 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 12:06:27.925  1592  2035 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-07 12:06:27.926  1037  1527 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 12:06:27.926  1037  1527 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-07 12:06:27.926  1037  1534 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-07 12:06:27.927  1840  1840 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 12:06:27.927  1840  1840 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,09-07 12:06:27.950  1592  1592 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-07 12:06:27.951  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 12:06:27.952  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 12:06:27.953  7294  7294 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-07 12:06:27.953  7294  7294 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-07 12:06:27.953  7294  7294 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-07 12:06:27.953  7294  7294 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
,09-07 12:06:27.953  7294  7294 D dhcpcd  : wlan0: sending REQUEST (xid 0xc1ddc82f), next in 3.83 seconds
09-07 12:06:27.984   278   433 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-07 12:06:27.984   278   433 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-07 12:06:27.984   278   433 W Vold    : Returning OperationFailed - no handler for errno 0
09-07 12:06:27.984  7294  7294 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
09-07 12:06:27.985  7276  7305 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,09-07 12:06:27.987   278   433 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-07 12:06:27.987   278   433 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-07 12:06:27.987   278   433 W Vold    : Returning OperationFailed - no handler for errno 0
09-07 12:06:27.988  7276  7305 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
09-07 12:06:27.997   278   433 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-07 12:06:27.997   278   433 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-07 12:06:27.997   278   433 W Vold    : Returning OperationFailed - no handler for errno 0
09-07 12:06:27.998  7276  7307 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,09-07 12:06:28.002   278   433 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-07 12:06:28.002   278   433 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-07 12:06:28.002   278   433 W Vold    : Returning OperationFailed - no handler for errno 0
09-07 12:06:28.004  7276  7307 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
09-07 12:06:28.005  7294  7294 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
09-07 12:06:28.005  7294  7294 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
09-07 12:06:28.006  7294  7294 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
09-07 12:06:28.006  7294  7294 D dhcpcd  : wlan0: adding default route via 192.168.1.1
09-07 12:06:28.006  7294  7294 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-07 12:06:28.006  7294  7294 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-07 12:06:28.007  7294  7294 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-07 12:06:28.007  7294  7294 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
09-07 12:06:28.050  1037  1965 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7315 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,09-07 12:06:28.101  7315  7315 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,09-07 12:06:28.102  7315  7315 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
09-07 12:06:28.132  7315  7315 I MultiDex: VM with version 2.1.0 has multidex support
09-07 12:06:28.132  7315  7315 I MultiDex: install
09-07 12:06:28.133  7315  7315 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,09-07 12:06:28.141  7315  7315 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
09-07 12:06:28.218  7276  7276 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,09-07 12:06:28.227  7276  7276 I LibraryLoader: Loading: webviewchromium
09-07 12:06:28.231  7276  7276 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 2454-2458)
09-07 12:06:28.231  7276  7276 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-07 12:06:28.240  7276  7276 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3e49d60}
,09-07 12:06:28.244  7276  7276 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-07 12:06:28.245  7276  7276 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,09-07 12:06:28.262  1037  7259 D DhcpStateMachine: DHCPV4 succeeded on wlan0
09-07 12:06:28.262  7276  7276 I BrowserStartupController: Initializing chromium process, renderers=0
,09-07 12:06:28.263  1037  7259 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
09-07 12:06:28.263  7276  7276 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-07 12:06:28.263  1037  7259 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-07 12:06:28.264  1037  7259 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
09-07 12:06:28.264  1037  7259 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
09-07 12:06:28.264  1037  7259 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-07 12:06:28.264  1037  7259 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
,09-07 12:06:28.264  1037  7259 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
09-07 12:06:28.265  1037  7259 D DhcpStateMachine: RunningState
09-07 12:06:28.278  7276  7276 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
09-07 12:06:28.279  7276  7276 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
09-07 12:06:28.279  7276  7276 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
,09-07 12:06:28.284   313  1370 V AudioPolicyService: registerClient() client 0xb558a6e0, uid 10093
09-07 12:06:28.285  7276  7367 W AudioManagerAndroid: Requires BLUETOOTH permission
09-07 12:06:28.298  7276  7276 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-07 12:06:28.298  7276  7276 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-07 12:06:28.298  7276  7276 I Adreno-EGL: Build Date: 12/12/14 금
09-07 12:06:28.298  7276  7276 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-07 12:06:28.298  7276  7276 I Adreno-EGL: Remote Branch: 
09-07 12:06:28.298  7276  7276 I Adreno-EGL: Local Patches: 
09-07 12:06:28.298  7276  7276 I Adreno-EGL: Reconstruct Branch: 
,09-07 12:06:28.504  1037  1875 I art     : Explicit concurrent mark sweep GC freed 104421(5MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/64MB, paused 1.788ms total 119.908ms
,09-07 12:06:28.537  7276  7276 I NSApplication: Starting up...
,09-07 12:06:28.556  7382  7382 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,09-07 12:06:28.599  1037  1929 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7389 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,09-07 12:06:28.602  1037  1929 I ActivityManager: Killing 6120:com.android.vending/u0a44 (adj 15): empty #17
09-07 12:06:28.656  7382  7382 I dex2oat : dex2oat took 99.429ms (threads: 4)
,09-07 12:06:28.673  7315  7334 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-07 12:06:28.673  7315  7334 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-07 12:06:28.673  7315  7334 I Adreno-EGL: Build Date: 12/12/14 금
09-07 12:06:28.673  7315  7334 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-07 12:06:28.673  7315  7334 I Adreno-EGL: Remote Branch: 
09-07 12:06:28.673  7315  7334 I Adreno-EGL: Local Patches: 
09-07 12:06:28.673  7315  7334 I Adreno-EGL: Reconstruct Branch: 
,09-07 12:06:28.717  1037  1965 D WifiServiceImplEx: setWifiEnabled: false pid=6798, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-07 12:06:28.717  1037  1965 D WifiService: setWifiEnabled: false pid=6798, uid=10118
,09-07 12:06:28.718  1037  1965 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-07 12:06:28.736  1037  1774 W libprocessgroup: failed to open /acct/uid_10044/pid_6120/cgroup.procs: No such file or directory
09-07 12:06:28.740  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-07 12:06:28.741  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-07 12:06:28.741  1037  1037 D Ulp_jni : JNI:system_update. Event-4
09-07 12:06:28.741  1037  1527 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
,09-07 12:06:28.743  1037  1527 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
09-07 12:06:28.743  1037  1527 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
09-07 12:06:28.744  1037  1527 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
09-07 12:06:28.745  1037  1534 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
09-07 12:06:28.745  1037  1527 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
09-07 12:06:28.745  1037  1527 E WifiStateMachine: WifiStateMachine: Leaving Connected state
09-07 12:06:28.745  1037  1527 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-07 12:06:28.745  1037  1527 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-07 12:06:28.747  1037  1527 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-07 12:06:28.747  1037  1527 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-07 12:06:28.765  1037  1527 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-07 12:06:28.765  7389  7389 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-07 12:06:28.767  1037  1526 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-07 12:06:28.767  1037  1526 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-07 12:06:28.767  1037  1527 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-07 12:06:28.767  7161  7161 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-07 12:06:28.767  1037  1527 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-07 12:06:28.767  1037  1527 D WifiNative-wlan0: doBoolean: SET ps 1
09-07 12:06:28.768  1037  1527 D WifiNative-wlan0: SET ps 1: returned true
,09-07 12:06:28.768  1037  7259 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-07 12:06:28.769   309   894 D CommandListener: Clearing all IP addresses on wlan0
09-07 12:06:28.777  7315  7334 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-07 12:06:28.777  7315  7334 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-07 12:06:28.777  7315  7334 I Adreno-EGL: Build Date: 12/12/14 금
09-07 12:06:28.777  7315  7334 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-07 12:06:28.777  7315  7334 I Adreno-EGL: Remote Branch: 
09-07 12:06:28.777  7315  7334 I Adreno-EGL: Local Patches: 
09-07 12:06:28.777  7315  7334 I Adreno-EGL: Reconstruct Branch: 
09-07 12:06:28.797  1037  1526 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-07 12:06:28.797  1037  1526 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-07 12:06:28.797  1037  1526 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@1ca6b677
09-07 12:06:28.797  1037  1527 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 12:06:28.798  1037  1526 D LGWifiP2pService: P2pDisablingState
09-07 12:06:28.798  1037  1526 D LGWifiP2pService: P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
09-07 12:06:28.798  1037  1526 D LGWifiP2pService: p2p socket connection lost
09-07 12:06:28.798  1037  1526 D LGWifiP2pService: P2pDisabledState
09-07 12:06:28.798  1037  1527 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 12:06:28.798  1037  1527 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 12:06:28.798  1037  1527 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 12:06:28.799  1037  1527 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 12:06:28.799  1037  1527 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 12:06:28.800  1037  1527 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
09-07 12:06:28.800  1037  1527 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-07 12:06:28.800  1037  1526 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-07 12:06:28.800  1037  1526 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-07 12:06:28.800  7161  7161 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-07 12:06:28.800  1037  1534 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-07 12:06:28.800  1037  1534 D ConnectivityService: ignoring duplicate network state non-change
09-07 12:06:28.800  1037  1534 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
,09-07 12:06:28.802  1037  1527 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-07 12:06:28.803  1037  1527 D WifiNative-wlan0: doBoolean: SET ps 1
09-07 12:06:28.804  1037  1527 D WifiNative-wlan0: SET ps 1: returned true
09-07 12:06:28.804  1037  1037 D WifiHS20: hidePasspointNotification off =false
09-07 12:06:28.805  1592  1592 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 12:06:28.805  1592  1592 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-07 12:06:28.806  1930  1930 V WfdStateTracker: handleWifiStateChangedEvent: 0
09-07 12:06:28.806  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 12:06:28.810  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 12:06:28.810  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 12:06:28.810  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-07 12:06:28.810  1037  1037 D WifiHS20: hidePasspointNotification off =false
09-07 12:06:28.816  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 12:06:28.816  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 12:06:28.816  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-07 12:06:28.817  1037  1037 D WifiScanningService: SCAN_AVAILABLE : 1
09-07 12:06:28.817  1037  1545 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-07 12:06:28.817  1037  1037 D RttService: SCAN_AVAILABLE : 1
09-07 12:06:28.817  1037  1546 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-07 12:06:28.819  1930  1930 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-07 12:06:28.819  1930  1930 D WfdsService: WifiP2pState is changed : false
09-07 12:06:28.820  1930  2316 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
09-07 12:06:28.820  1930  2316 D WfdsService: Set the WFDS Monitor: false
09-07 12:06:28.821  1930  2316 D WfdsMonitor: WFDS Monitor is stopped
09-07 12:06:28.821  1930  2316 D WfdsService: STATE : WfdsDisabledState - enter
09-07 12:06:28.821  1930  7191 D CtrlSupplicant: Received on exit socket, terminate
09-07 12:06:28.821  1930  7191 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
09-07 12:06:28.821  1930  7191 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
09-07 12:06:28.821  1930  7191 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
09-07 12:06:28.821  1930  2317 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
09-07 12:06:28.821  1930  2316 W WfdsService: DefaultState - msg [9445378] is not handled
09-07 12:06:28.829  1592  1592 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 12:06:28.829  1592  1592 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-07 12:06:28.832  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-07 12:06:28.844  7315  7334 D LgDataFeature: LgDataFeature() Constructor: none
09-07 12:06:28.844  7315  7334 D LgDataFeature: LgDataFeature() Constructor Done, null
09-07 12:06:28.849   309   894 D CommandListener: Clearing all IP addresses on wlan0
09-07 12:06:28.849  1037  1534 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
09-07 12:06:28.849  1037  1534 D DSQN    : disableDataServiceNotify
09-07 12:06:28.849  1037  1534 D DSQN    : stop dsqn bin
09-07 12:06:28.850  1037  1527 D WifiNative-p2p0: doBoolean: TERMINATE
09-07 12:06:28.850  1037  1527 D WifiNative-p2p0: TERMINATE: returned true
09-07 12:06:28.850  1037  1527 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-07 12:06:28.850  1037  1527 E WifiStateMachine: useWiFiOffloading() : false
09-07 12:06:28.850  1037  1527 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,09-07 12:06:28.852  1037  1037 D WifiHS20: hidePasspointNotification off =false
09-07 12:06:28.852  1037  1527 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-07 12:06:28.852  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 12:06:28.852  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 12:06:28.852  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-07 12:06:28.854  7315  7334 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-07 12:06:28.854  7315  7334 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-07 12:06:28.854  7315  7334 I Adreno-EGL: Build Date: 12/12/14 금
09-07 12:06:28.854  7315  7334 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-07 12:06:28.854  7315  7334 I Adreno-EGL: Remote Branch: 
09-07 12:06:28.854  7315  7334 I Adreno-EGL: Local Patches: 
09-07 12:06:28.854  7315  7334 I Adreno-EGL: Reconstruct Branch: 
09-07 12:06:28.854  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
09-07 12:06:28.854  1930  1930 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
09-07 12:06:28.854  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-07 12:06:28.854  1037  1037 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
09-07 12:06:28.855  1592  1592 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-07 12:06:28.855  1592  1592 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-07 12:06:28.861  6798  6798 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 12:06:28.862  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 12:06:28.862  6798  6798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 12:06:28.862  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:06:28.862  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 12:06:28.862  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 12:06:28.862  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 12:06:28.862  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 12:06:28.862  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 12:06:28.862  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 12:06:28.862  6798  6798 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 12:06:28.862  6798  6798 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 12:06:28.864  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-07 12:06:28.866  6798  6798 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 12:06:28.866  6798  6798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 12:06:28.866  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:06:28.866  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 12:06:28.866  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 12:06:28.866  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 12:06:28.866  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 12:06:28.866  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 12:06:28.866  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 12:06:28.866  6798  6798 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 12:06:28.866  6798  6798 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 12:06:28.866  1037  1534 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
09-07 12:06:28.866  1037  1534 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 12:06:28.866  1037  1534 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-07 12:06:28.866  1037  1534 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
09-07 12:06:28.866  1037  1534 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
09-07 12:06:28.867  1037  7258 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-07 12:06:28.867  1037  7258 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-07 12:06:28.867  1037  7258 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-07 12:06:28.867  1037  1534 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
09-07 12:06:28.867  1037  1534 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-07 12:06:28.867  1037  1534 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-07 12:06:28.867  1592  2035 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-07 12:06:28.867  1037  1534 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-07 12:06:28.867  1037  1534 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CO,NNECTIVITY_CHANGE_IMMEDIATE
09-07 12:06:28.867  1037  1534 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-07 12:06:28.867  1037  1534 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 12:06:28.867  1037  1534 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 12:06:28.868  1037  1534 D NetworkManagementService: Removing idletimer
09-07 12:06:28.868  1037  1534 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 12:06:28.868  1037  1525 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-07 12:06:28.868  1037  1037 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-07 12:06:28.869  1037  1037 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-07 12:06:28.869  1037  1037 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-07 12:06:28.869  1037  1037 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-07 12:06:28.869  1037  1527 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 12:06:28.869  1037  1527 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-07 12:06:28.870  1037  1037 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-07 12:06:28.871  1037  1525 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-07 12:06:28.871  1037  1037 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-07 12:06:28.871  1037  1037 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-07 12:06:28.871  1037  1037 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-07 12:06:28.871  1840  1840 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 12:06:28.871  1840  1840 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,09-07 12:06:28.900  1592  1592 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-07 12:06:28.901  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 12:06:28.902  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 12:06:28.914  1592  1592 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-07 12:06:28.915  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 12:06:28.915  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-07 12:06:28.943  7161  7161 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-07 12:06:28.943  7161  7161 I wpa_supplicant: monitor socket send errors count : 1
09-07 12:06:28.943  7161  7161 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1930-4\x00 that cannot receive messages
,09-07 12:06:28.944  1037  7190 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
09-07 12:06:28.944  1037  7190 D WifiMonitor: Dropping event because (p2p0) is stopped
09-07 12:06:28.965  7161  7161 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-07 12:06:28.966  7161  7161 W wpa_supplicant: USIM:  scard_deinit function
09-07 12:06:28.968  1037  1119 D Tethering: InitialState.processMessage what=4
,09-07 12:06:28.969  1037  7190 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
09-07 12:06:28.969  1037  7190 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-07 12:06:28.969  1037  1119 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-07 12:06:28.969  1037  7190 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-07 12:06:28.969  1037  7190 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
09-07 12:06:28.972  1037  7190 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-07 12:06:28.972  1037  7190 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-07 12:06:28.974  1037  1527 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=183189
09-07 12:06:28.975  1037  1527 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=183191
09-07 12:06:28.976  1037  7259 D DhcpStateMachine: StoppedState
09-07 12:06:28.976  1037  7259 D DhcpStateMachine: StoppedState{ when=-172ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-07 12:06:28.976  1037  1527 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
09-07 12:06:28.978  1037  1527 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-07 12:06:28.979  1037  1527 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=183194  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-07 12:06:28.980  1037  1527 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=183196  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
,09-07 12:06:28.982  1037  1527 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
09-07 12:06:28.983  1037  1527 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
,09-07 12:06:29.071  6497  6497 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-07 12:06:29.073  6497  6937 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,09-07 12:06:29.095  2163  2163 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-07 12:06:29.100  7161  7161 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-07 12:06:29.101  7105  7105 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-07 12:06:29.101  7105  7105 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-07 12:06:29.101  7105  7105 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-07 12:06:29.101  7105  7105 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-07 12:06:29.102  1037  7190 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
09-07 12:06:29.102  1037  7190 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-TERMINATING 
09-07 12:06:29.102  1037  7190 D WifiMonitor: Disconnecting from the supplicant, no more events
09-07 12:06:29.105  1037  1527 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 45 0
09-07 12:06:29.109  1930  1930 D WfdsService: Supplicant Connection state is changed : false
09-07 12:06:29.109  1037  1527 D WifiOffDelayIfNotUsed: stopMonitoring
09-07 12:06:29.110  1037  1527 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-07 12:06:29.110  1037  1527 E WifiStateMachine: useWiFiOffloading() : false
09-07 12:06:29.110  1037  1527 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-07 12:06:29.110  1930  2316 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
09-07 12:06:29.110  1930  2316 D WfdsService: Set the WFDS Monitor: false
,09-07 12:06:29.110  1930  2316 D WfdsMonitor: WFDS Monitor is stopped
09-07 12:06:29.113  7105  7105 I AppUp4:CustModeStarterReceiver: onReceive
09-07 12:06:29.114  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 12:06:29.114  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
09-07 12:06:29.114  1037  1532 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
09-07 12:06:29.114  1037  1532 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
09-07 12:06:29.117  1930  1930 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-07 12:06:29.118  2488  2488 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 12:06:29.118  6798  6798 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 12:06:29.118  6798  6798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 12:06:29.118  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:06:29.118  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 12:06:29.118  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 12:06:29.118  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 12:06:29.118  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 12:06:29.118  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 12:06:29.118  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 12:06:29.118  6798  6798 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 12:06:29.118  6798  6798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 12:06:29.118  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:06:29.118  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 12:06:29.118  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 12:06:29.118  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 12:06:29.118  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 12:06:29.118  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 12:06:29.118  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 12:06:29.121  7105  7105 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@3e0cc071
09-07 12:06:29.121  7105  7105 D AppUp4:CustFacade: isCustomizationCompleted : false
09-07 12:06:29.121  7105  7105 D AppUp4:CustFacade: isPhone : true
09-07 12:06:29.121  7105  7105 D AppUp4:CustModeStarterReceiver: begin check event
09-07 12:06:29.121  7105  7105 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-07 12:06:29.126  4760  4760 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-07 12:06:29.126  4760  4760 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-07 12:06:29.127  4760  4760 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDevice,ActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-07 12:06:29.129  4760  4760 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-07 12:06:29.136  4760  7429 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-07 12:06:29.138  4760  7430 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-07 12:06:29.138  4760  7430 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-07 12:06:29.140  7132  7132 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,09-07 12:06:29.156  3161  3161 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-07 12:06:29.157  3161  3161 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
,09-07 12:06:29.158  3161  3161 I LgeMiscReceiver: networkInfo.isConnected() = false
09-07 12:06:29.159  7132  7432 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 12:06:29.161  7172  7172 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-07 12:06:29.161  7172  7172 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-07 12:06:29.161   309  7437 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
09-07 12:06:29.162  1037  1117 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
09-07 12:06:29.162  1805  7275 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
09-07 12:06:29.174  7240  7240 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:6:29
,09-07 12:06:29.176  7240  7240 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-07 12:06:29.176  7240  7240 D Weather.Utils: 2 : All the weather widget is gone.
09-07 12:06:29.177  7008  7435 W FormManager: Network not available. Please check & try again.
09-07 12:06:29.177  7240  7240 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-07 12:06:29.177  7240  7240 D WeatherAncestor: connectivity changed - connection : true
09-07 12:06:29.177  7240  7240 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@1c5cfed7
09-07 12:06:29.178  7240  7240 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-07 12:06:29.178  7240  7240 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-07 12:06:29.178  7240  7240 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-07 12:06:29.178  7240  7240 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-07 12:06:29.178  7240  7240 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:6:29
09-07 12:06:29.184  7008  7438 V FormManager: Network unavailable.
09-07 12:06:29.185  1805  7275 I CheckinService: active receiver: disabled
,09-07 12:06:29.207  7008  7438 V FormManager: Network unavailable.
,09-07 12:06:29.239  6889  6889 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-07 12:06:29.239  6889  6889 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-07 12:06:29.239  6889  6889 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
,09-07 12:06:29.240  6889  6889 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-07 12:06:29.240  6889  6889 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-07 12:06:29.241  6889  6889 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-07 12:06:29.241  6889  6889 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-07 12:06:29.241  6889  6889 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-07 12:06:29.241  6889  6889 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-07 12:06:29.241  6889  6889 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-07 12:06:29.241  6889  6889 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-07 12:06:29.250  6938  6938 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-07 12:06:29.255  6889  6889 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-07 12:06:29.261  7008  7440 W FormManager: Network not available. Please check & try again.
09-07 12:06:29.266  7008  7441 V FormManager: Network unavailable.
09-07 12:06:29.269  6889  6889 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-07 12:06:29.277  7008  7441 V FormManager: Network unavailable.
09-07 12:06:29.308  6938  6938 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-07 12:06:29.312  6889  6889 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-07 12:06:29.326  7008  7443 W FormManager: Network not available. Please check & try again.
,09-07 12:06:29.326  7008  7444 V FormManager: Network unavailable.
09-07 12:06:29.327  6889  6889 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 12:06:29.342  7008  7444 V FormManager: Network unavailable.
,09-07 12:06:29.364  4760  4760 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-07 12:06:29.365  4760  4760 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,09-07 12:06:29.370  4760  4760 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-07 12:06:29.375  4760  4760 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-07 12:06:29.394  4760  7445 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-07 12:06:29.407  4760  7446 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
,09-07 12:06:29.407  4760  7446 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-07 12:06:29.451  1037  2001 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7447 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,09-07 12:06:29.474  6718  7084 D UEI.SmartControl: Internal timer expired: 2
09-07 12:06:29.474  6718  7084 D UEI.SmartControl: unbind internal service
,09-07 12:06:29.591  7447  7447 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-07 12:06:29.592  7447  7447 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,09-07 12:06:29.608  7447  7447 V [BNRBootReceiver]: Boot Receiver Return
09-07 12:06:29.612  7447  7447 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,09-07 12:06:29.620  6497  6497 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-07 12:06:29.629  6889  6889 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-07 12:06:29.634  6718  7078 D serial_port: close(fd = 24)
09-07 12:06:29.637  6718  7078 I UEI.SmartControl: Serial port is closed.
09-07 12:06:29.642  6889  6889 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-07 12:06:29.657  6971  6971 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-07 12:06:29.657  6971  6971 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-07 12:06:29.659  6971  6971 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-07 12:06:29.665  6497  6497 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-07 12:06:29.676  6889  6889 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-07 12:06:29.692  6889  6889 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 12:06:29.704  6971  6971 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-07 12:06:29.704  6971  6971 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-07 12:06:29.708  6971  6971 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-07 12:06:29.714  6889  6889 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
09-07 12:06:29.718  6889  6889 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
09-07 12:06:29.724  6497  6497 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-07 12:06:29.739  6889  6889 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-07 12:06:29.749  6889  6889 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 12:06:29.759  6971  6971 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-07 12:06:29.760  6971  6971 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-07 12:06:29.761  6971  6971 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-07 12:06:29.769  6497  6497 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-07 12:06:29.782  6889  6889 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-07 12:06:29.791  6889  6889 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 12:06:29.800  6971  6971 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-07 12:06:29.801  6971  6971 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-07 12:06:29.802  6971  6971 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-07 12:06:29.808  6497  6497 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-07 12:06:29.818  6889  6889 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-07 12:06:29.828  6889  6889 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 12:06:29.836  6971  6971 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-07 12:06:29.838  6971  6971 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-07 12:06:29.838  6971  6971 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-07 12:06:29.844  6497  6497 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-07 12:06:29.855  6889  6889 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-07 12:06:29.865  6889  6889 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 12:06:29.874  6971  6971 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-07 12:06:29.874  6971  6971 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-07 12:06:29.875  6971  6971 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-07 12:06:29.879  6497  6497 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-07 12:06:29.893  6889  6889 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-07 12:06:29.899  6889  6889 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 12:06:29.908  6971  6971 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-07 12:06:29.908  6971  6971 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-07 12:06:29.909  6971  6971 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-07 12:06:29.919  6497  6497 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-07 12:06:29.933  6889  6889 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-07 12:06:29.939  6889  6889 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 12:06:29.947  6971  6971 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-07 12:06:29.948  6971  6971 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-07 12:06:29.953  6971  6971 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-07 12:06:29.958  6497  6497 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-07 12:06:29.968  6889  6889 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-07 12:06:29.977  6889  6889 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 12:06:29.987  6971  6971 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-07 12:06:29.988  6971  6971 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-07 12:06:29.989  6971  6971 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-07 12:06:29.996  6497  6497 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-07 12:06:30.001  6938  6938 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,09-07 12:06:30.009  1037  1533 D WifiService: New client listening to asynchronous messages
09-07 12:06:30.010  6938  6938 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-07 12:06:30.015  6889  6889 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-07 12:06:30.021  6889  6889 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 12:06:30.029  6971  6971 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-07 12:06:30.029  6971  6971 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-07 12:06:30.033  6971  6971 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-07 12:06:30.034  6971  6971 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,09-07 12:06:30.034  6971  6971 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-07 12:06:30.040  6497  6497 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-07 12:06:30.044  6938  6938 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,09-07 12:06:30.047  6938  6938 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-07 12:06:30.052  6889  6889 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-07 12:06:30.059  6889  6889 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 12:06:30.067  6971  6971 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-07 12:06:30.068  6971  6971 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-07 12:06:30.069  6971  6971 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-07 12:06:30.069  6971  6971 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-07 12:06:30.070  6971  6971 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-07 12:06:30.073  1037  1774 I ActivityManager: Killing 6911:com.lge.lifetracker/u0a37 (adj 15): empty #17
,09-07 12:06:30.093  1037  1564 W libprocessgroup: failed to open /acct/uid_10037/pid_6911/cgroup.procs: No such file or directory
,09-07 12:06:30.101  2163  2163 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
09-07 12:06:30.115  2163  2163 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,09-07 12:06:30.116  2163  2163 D c       : Getting all permits...
09-07 12:06:30.116  2163  2163 D a       : Opening database...
09-07 12:06:30.122  2163  2163 D a       : Opening database auth.proximity.permit_store...
09-07 12:06:30.123  2163  2163 D a       : Closing database...
09-07 12:06:30.134  6497  6497 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-07 12:06:30.138  6938  6938 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-07 12:06:30.138  6938  6938 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-07 12:06:30.138  6938  6938 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-07 12:06:30.142  6889  6889 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-07 12:06:30.148  6889  6889 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 12:06:30.156  6971  6971 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-07 12:06:30.156  6971  6971 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-07 12:06:30.158  6971  6971 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-07 12:06:30.162  6497  6497 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-07 12:06:30.169  6938  6938 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-07 12:06:30.169  6938  6938 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-07 12:06:30.169  6938  6938 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-07 12:06:30.173  6889  6889 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-07 12:06:30.180  6889  6889 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 12:06:30.187  6971  6971 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-07 12:06:30.188  6971  6971 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-07 12:06:30.190  6971  6971 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-07 12:06:30.196  6497  6497 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-07 12:06:30.199  6938  6938 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-07 12:06:30.199  6938  6938 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,09-07 12:06:30.199  6938  6938 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-07 12:06:30.204  6889  6889 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-07 12:06:30.210  6889  6889 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 12:06:30.217  6971  6971 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-07 12:06:30.219  6971  6971 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-07 12:06:30.220  6971  6971 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-07 12:06:30.229  6938  6938 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-07 12:06:30.233  6889  6889 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-07 12:06:30.240  6889  6889 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 12:06:30.249  7008  7475 W FormManager: Network not available. Please check & try again.
,09-07 12:06:30.252  7008  7476 V FormManager: Network unavailable.
09-07 12:06:30.259  7008  7476 V FormManager: Network unavailable.
09-07 12:06:30.262  4760  4760 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-07 12:06:30.262  4760  4760 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-07 12:06:30.264  4760  4760 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-07 12:06:30.269  4760  4760 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-07 12:06:30.279  6938  6938 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
09-07 12:06:30.279  6938  6938 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-07 12:06:30.279  6938  6938 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-07 12:06:30.282  4760  7477 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-07 12:06:30.285  4760  7479 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-07 12:06:30.285  4760  7479 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-07 12:06:30.290  6889  6889 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-07 12:06:30.301  6889  6889 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 12:06:30.302  7008  7481 V FormManager: Network unavailable.
09-07 12:06:30.306  7008  7480 W FormManager: Network not available. Please check & try again.
09-07 12:06:30.316  7008  7481 V FormManager: Network unavailable.
09-07 12:06:30.319  2163  2163 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,09-07 12:06:30.643  1037  1527 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:69008115] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-07 12:06:30.644  1037  1527 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:69008116] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,09-07 12:06:30.737  1037  1534 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-07 12:06:30.753  1037  1119 D Tethering: MasterInitialState.processMessage what=3
09-07 12:06:30.758  1037  1099 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-07 12:06:30.761  6798  6798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 12:06:30.766  6798  6798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 12:06:30.771  6497  6497 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-07 12:06:30.773  6497  6937 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-07 12:06:30.792  5859  5859 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,09-07 12:06:30.814  2163  2163 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-07 12:06:30.846  1037  1099 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-07 12:06:30.856  7105  7105 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-07 12:06:30.856  7105  7105 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-07 12:06:30.857  7105  7105 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-07 12:06:30.857  7105  7105 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-07 12:06:30.859  7105  7105 I AppUp4:CustModeStarterReceiver: onReceive
,09-07 12:06:30.866  7105  7105 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@3e0cc071
09-07 12:06:30.866  7105  7105 D AppUp4:CustFacade: isCustomizationCompleted : false
09-07 12:06:30.866  7105  7105 D AppUp4:CustFacade: isPhone : true
09-07 12:06:30.867  7105  7105 D AppUp4:CustModeStarterReceiver: begin check event
09-07 12:06:30.868  7105  7105 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-07 12:06:30.872  4760  4760 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-07 12:06:30.873  4760  4760 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-07 12:06:30.874  4760  4760 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-07 12:06:30.880  4760  4760 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-07 12:06:30.888  7132  7132 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,09-07 12:06:30.923  3161  3161 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-07 12:06:30.923  3161  3161 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-07 12:06:30.923  3161  3161 I LgeMiscReceiver: networkInfo.isConnected() = true
09-07 12:06:30.923  3161  3161 D PhoneState: setPdpRejectCasuse : false
,09-07 12:06:30.931  4760  7506 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-07 12:06:30.934  7172  7172 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-07 12:06:30.935  7172  7172 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-07 12:06:30.937  7132  7510 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 12:06:30.942  7008  7509 W FormManager: Network not available. Please check & try again.
,09-07 12:06:30.943  7008  7511 V FormManager: Network unavailable.
09-07 12:06:30.947  4760  7513 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-07 12:06:30.947  4760  7513 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-07 12:06:30.949  7240  7240 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:6:30
09-07 12:06:30.951  7240  7240 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-07 12:06:30.951  7240  7240 D Weather.Utils: 2 : All the weather widget is gone.
09-07 12:06:30.952  7240  7240 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-07 12:06:30.952  7240  7240 D WeatherAncestor: connectivity changed - connection : true
09-07 12:06:30.952  7240  7240 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@1c5cfed7
09-07 12:06:30.953  7240  7240 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-07 12:06:30.953  7240  7240 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-07 12:06:30.953  7240  7240 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-07 12:06:30.953  7240  7240 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-07 12:06:30.953  7240  7240 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:6:30
,09-07 12:06:30.956  7008  7511 V FormManager: Network unavailable.
09-07 12:06:31.743  1037  1774 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 12:06:31.744  1037  1774 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,09-07 12:06:31.772  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-07 12:06:31.773  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-07 12:06:31.773  1037  1037 D Ulp_jni : JNI:system_update. Event-4
,09-07 12:06:31.777  1037  1119 D BluetoothManagerService: Message: 1
09-07 12:06:31.777  1037  1119 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
09-07 12:06:31.812  1037  1119 D BluetoothManagerService: Message: 20
09-07 12:06:31.812  1037  1119 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@19c4d7f3:true
,09-07 12:06:31.817  7039  7039 D BluetoothAdapterState: make
09-07 12:06:31.821  7039  7039 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
09-07 12:06:31.822  7039  7039 I bluedroid-qcom: init
09-07 12:06:31.823  7039  7526 I BluetoothAdapterState: Entering OffState
09-07 12:06:31.823  7039  7039 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-07 12:06:31.824  7039  7039 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-07 12:06:31.824  7039  7039 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-07 12:06:31.824  7039  7039 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-07 12:06:31.824  7039  7039 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
09-07 12:06:31.826  7039  7039 I bluedroid-qcom: get_profile_interface socket
09-07 12:06:31.826  7039  7039 I bluedroid-qcom: get_profile_interface map_client
,09-07 12:06:31.831  7039  7530 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
09-07 12:06:31.824  7529  7529 W bdaddr_loader: type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-07 12:06:31.824  7529  7529 W bdaddr_loader: type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-07 12:06:31.842  7529  7529 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
,09-07 12:06:31.848  1037  1037 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
09-07 12:06:31.848  1037  1119 D BluetoothManagerService: Message: 40
09-07 12:06:31.848  1037  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
09-07 12:06:31.849  7039  7055 I bluedroid-qcom: config_hci_snoop_log
09-07 12:06:31.850  1037  1119 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
09-07 12:06:31.851  1037  1119 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
09-07 12:06:31.855  7529  7529 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
09-07 12:06:31.855  7529  7529 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,09-07 12:06:31.858  7529  7529 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
09-07 12:06:31.863  7039  7526 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
09-07 12:06:31.863  7039  7526 D BluetoothAdapterProperties: Setting state to 11
09-07 12:06:31.863  7039  7526 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-07 12:06:31.865  7529  7529 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
09-07 12:06:31.865  7529  7529 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
09-07 12:06:31.867  1037  1119 D BluetoothManagerService: Message: 60
09-07 12:06:31.867  1037  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
09-07 12:06:31.867  1037  1119 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
,09-07 12:06:31.869  1037  1534 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-07 12:06:31.872  7039  7530 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
09-07 12:06:31.875  7039  7526 I LGBluetoothServiceJni: classInitNative: succeeds
09-07 12:06:31.879  1037  1534 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-07 12:06:31.882  1930  1930 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-07 12:06:31.887  1592  1592 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-07 12:06:31.891  6798  6798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 12:06:31.897  6798  6798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 12:06:31.903  7039  7530 D BluetoothAdapterProperties: Name is: G3
09-07 12:06:31.908  6889  6889 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
,09-07 12:06:31.921  7039  7039 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-07 12:06:31.923  7039  7039 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-07 12:06:31.923  7039  7039 V BluetoothPbapReceiver: ***********state = 11
,09-07 12:06:31.924  1037  1099 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-07 12:06:31.924  1037  1119 D Tethering: MasterInitialState.processMessage what=3
09-07 12:06:31.926  7039  7526 D BluetoothBondStateMachine: make
09-07 12:06:31.929  1037  1037 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-07 12:06:31.929  1037  1037 D BluetoothManagerService: Stored Bluetooth name: G3
09-07 12:06:31.930  1037  1119 D Tethering: MasterInitialState.processMessage what=3
09-07 12:06:31.931  6798  6798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 12:06:31.933  6798  6798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 12:06:31.934  7039  7526 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c5cfed7
09-07 12:06:31.934  7039  7526 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
09-07 12:06:31.934  7039  7526 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c5cfed7
09-07 12:06:31.934  7039  7526 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
09-07 12:06:31.935  7039  7526 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
09-07 12:06:31.935  6798  6798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 12:06:31.936  7039  7547 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-07 12:06:31.939  2163  2163 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-07 12:06:31.941  6497  6497 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-07 12:06:31.944  6798  6798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 12:06:31.945  7039  7526 E BluetoothAdapterService: File transfer profiles supported!!
09-07 12:06:31.945  6497  6937 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-07 12:06:31.993  1037  1053 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7549 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,09-07 12:06:32.002  5859  5859 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
09-07 12:06:32.006  1037  1099 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-07 12:06:32.008  7039  7039 D HeadsetService: Received start request. Starting profile...
09-07 12:06:32.008  1037  1099 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 12:06:32.009  1037  1099 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 12:06:32.009  7039  7039 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
09-07 12:06:32.010  7039  7039 D LGBluetoothHfpAdapter: Version 1.6
,09-07 12:06:32.013  5859  5859 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
09-07 12:06:32.013  7039  7526 E BluetoothAdapterService: File transfer profiles supported!!
09-07 12:06:32.017  7039  7039 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-07 12:06:32.019  7039  7039 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-07 12:06:32.020  7039  7039 D HeadsetStateMachine: make
09-07 12:06:32.020  7039  7526 E BluetoothAdapterService: File transfer profiles supported!!
09-07 12:06:32.029  7039  7526 E BluetoothAdapterService: File transfer profiles supported!!
,09-07 12:06:32.036  2163  2163 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
09-07 12:06:32.039  7039  7526 E BluetoothAdapterService: File transfer profiles supported!!
09-07 12:06:32.045  7105  7105 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-07 12:06:32.046  7105  7105 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,09-07 12:06:32.046  7105  7105 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-07 12:06:32.046  7105  7105 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-07 12:06:32.049  7039  7526 E BluetoothAdapterService: File transfer profiles supported!!
09-07 12:06:32.052  7105  7105 I AppUp4:CustModeStarterReceiver: onReceive
,09-07 12:06:32.054  7039  7039 D LgDataFeature: LgDataFeature() Constructor: none
09-07 12:06:32.054  7039  7039 D LgDataFeature: LgDataFeature() Constructor Done, null
09-07 12:06:32.056  7105  7105 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@3e0cc071
09-07 12:06:32.056  7105  7105 D AppUp4:CustFacade: isCustomizationCompleted : false
09-07 12:06:32.056  7105  7105 D AppUp4:CustFacade: isPhone : true
09-07 12:06:32.056  7105  7105 D AppUp4:CustModeStarterReceiver: begin check event
09-07 12:06:32.056  7105  7105 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-07 12:06:32.060  4760  4760 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-07 12:06:32.061  4760  4760 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,09-07 12:06:32.063  4760  4760 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-07 12:06:32.066  7039  7039 D HeadsetStateMachine: max_hf_connections = 1
,09-07 12:06:32.066  7039  7039 I bluedroid-qcom: get_profile_interface handsfree
09-07 12:06:32.068  7039  7526 E BluetoothAdapterService: File transfer profiles supported!!
09-07 12:06:32.068  7039  7039 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
,09-07 12:06:32.068  4760  4760 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-07 12:06:32.069   313  2153 V AudioPolicyService: registerClient() client 0xb558aba0, uid 1002
09-07 12:06:32.069   313   313 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
09-07 12:06:32.069   313   313 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-07 12:06:32.069   313   313 V AudioPolicyManagerEx: getOutput() returns output 2
09-07 12:06:32.069  7039  7039 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
09-07 12:06:32.070   313  1370 V AudioFlinger: registerClient() client 0xb1433160, pid 7039
09-07 12:06:32.070   313  1365 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-07 12:06:32.070   313  1365 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-07 12:06:32.070  1037  1053 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-07 12:06:32.070  1037  1053 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-07 12:06:32.070  3161  3176 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-07 12:06:32.070  3161  3176 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-07 12:06:32.070  7039  7039 V ToneGenerator: Create Track: 0xb4928080
09-07 12:06:32.070  7039  7039 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
09-07 12:06:32.070  7039  7039 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
09-07 12:06:32.070  7039  7056 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-07 12:06:32.070  7039  7056 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
09-07 12:06:32.071   313  1366 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-07 12:06:32.071   313  1366 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-07 12:06:32.071   313  2153 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-07 12:06:32.071   313  2153 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
09-07 12:06:32.071   313  2153 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-07 12:06:32.071   313  2153 V AudioPolicyManagerEx: getOutput() returns output 2
09-07 12:06:32.071  7039  7055 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-07 12:06:32.071  1592  2085 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-07 12:06:32.071  7039  7055 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
09-07 12:06:32.071  1592  2085 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-07 12:06:32.071  1037  2039 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-07 12:06:32.071  1037  2039 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-07 12:06:32.071  1592  2085 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-07 12:06:32.071  1592  2085 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-07 12:06:32.071  3161  3177 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-07 12:06:32.071  3161  3177 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-07 12:06:32.071   313  2152 I AudioFlinger: isAudioPlaybackHookOn() false
09-07 12:06:32.071   313  2153 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-07 12:06:32.071   313  2153 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
0,9-07 12:06:32.071  1840  3324 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-07 12:06:32.071   313  2153 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-07 12:06:32.071  1840  3324 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-07 12:06:32.071   313  2153 V AudioPolicyManagerEx: getOutput() returns output 2
09-07 12:06:32.071  7039  7039 V AudioSystem: getLatency() output 2, latency 50
09-07 12:06:32.072  7039  7039 V AudioSystem: getFrameCount() output 2, frameCount 960
09-07 12:06:32.072  7039  7039 V AudioTrack: createTrack_l() output 2 afLatency 50
09-07 12:06:32.072   313  1371 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-07 12:06:32.072   313  1371 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-07 12:06:32.072   313  1371 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-07 12:06:32.072   313  1371 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-07 12:06:32.072   313  1371 V AudioFlinger: createTrack() lSessionId: 22
09-07 12:06:32.071  1840  3324 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-07 12:06:32.073  1840  3324 V AudioSystem: ioConfigChanged() opening already existing output! 4
,09-07 12:06:32.081  7039  7039 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
09-07 12:06:32.083   313  1371 V AudioFlinger: acquiring 22 from 7039, for 7039
09-07 12:06:32.083   313  1371 V AudioFlinger:  added new entry for 22
09-07 12:06:32.084  7039  7039 V ToneGenerator: ToneGenerator INIT OK, time: 186312
09-07 12:06:32.084  7039  7039 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c5cfed7
09-07 12:06:32.085  7039  7566 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
09-07 12:06:32.085  7039  7566 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-07 12:06:32.085  7039  7566 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-07 12:06:32.085  7039  7566 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
09-07 12:06:32.086   313  2152 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7039
09-07 12:06:32.086  7039  7039 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c5cfed7
09-07 12:06:32.087   313  2152 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
09-07 12:06:32.087   313  2152 V voice   : voice_set_parameters: enter: bt_samplerate=8000
09-07 12:06:32.087   313  2152 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
09-07 12:06:32.087   313  2152 V compress_voip: voice_extn_compress_voip_set_parameters: exit
09-07 12:06:32.087   313  2152 V voice   : voice_set_parameters: exit with code(0)
09-07 12:06:32.087   313  2152 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
09-07 12:06:32.087   313  2152 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
09-07 12:06:32.087   313  2152 V msm8974_platform: platform_set_parameters: exit with code(0)
09-07 12:06:32.087   313  2152 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
09-07 12:06:32.087   313  2152 V audio_hw_primary: adev_set_parameters: exit with code(0)
09-07 12:06:32.087   313  2152 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
09-07 12:06:32.087  7039  7566 V ToneGenerator: ToneGenerator destructor
09-07 12:06:32.087  7039  7566 V ToneGenerator: stopTone
09-07 12:06:32.087  7039  7566 V ToneGenerator: Delete Track: 0xb4928080
09-07 12:06:32.088  7039  7039 D A2dpService: Received start request. Starting profile...
09-07 12:06:32.088  7039  7566 V AudioTrack: ~AudioTrack, releasing session id from 7039 on behalf of 7039
09-07 12:06:32.088   313  1370 V AudioFlinger: releasing 22 from 7039 for 7039
09-07 12:06:32.088   313  1370 V AudioFlinger:  decremented refcount to 0
,09-07 12:06:32.088   313  1370 V AudioFlinger: purging stale effects
09-07 12:06:32.089   313  1370 V AudioPolicyService: AudioCommandThread() adding release output 2
09-07 12:06:32.089   313  1370 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
09-07 12:06:32.089   313  1273 V AudioPolicyService: AudioCommandThread() waking up
09-07 12:06:32.089  7039  7039 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-07 12:06:32.089   313  1273 V AudioPolicyService: AudioCommandThread() processing release output 2
09-07 12:06:32.089   313  1273 V AudioPolicyManager: releaseOutput() 2
09-07 12:06:32.089   313  1273 V AudioPolicyService: AudioCommandThread() going to sleep
09-07 12:06:32.089   313  1370 V AudioFlinger: PlaybackThread::Track destructor
09-07 12:06:32.089   313  1370 V AudioFlinger: removeClient_l() pid 7039, calling pid 313
09-07 12:06:32.089  7039  7039 V Avrcp   : make
09-07 12:06:32.090  7039  7039 D Avrcp   : [BTUI] Use Native AVRCP : init jni
09-07 12:06:32.090  7039  7039 I bluedroid-qcom: get_profile_interface avrcp
09-07 12:06:32.093  7132  7132 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
09-07 12:06:32.094  7039  7526 V LGMDMManager: Create singleton instance
09-07 12:06:32.095  7039  7526 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
09-07 12:06:32.103  7039  7039 V AudioManager: registerRemoteController: size of Media player list: 0
09-07 12:06:32.103  4760  7569 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-07 12:06:32.105  7039  7039 E AudioManager: No RCC entry present to update
09-07 12:06:32.105  7039  7039 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-07 12:06:32.109  7039  7039 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
09-07 12:06:32.110  7039  7039 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
09-07 12:06:32.110  7039  7039 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
09-07 12:06:32.111  4760  7571 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-07 12:06:32.112  4760  7571 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-07 12:06:32.114  7039  7039 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
09-07 12:06:32.155  3161  3161 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-07 12:06:32.155  3161  3161 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-07 12:06:32.155  3161  3161 I LgeMiscReceiver: networkInfo.isConnected() = false
,09-07 12:06:32.157  7549  7549 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
09-07 12:06:32.157  7549  7549 W LG Account v2.2: No ProfileInfo entries
09-07 12:06:32.158  7549  7549 I LG Account v2.2: isEnabled: false
09-07 12:06:32.158  7549  7549 I Feature : [Lifetracker]ver: 4.21.112(40211120)
09-07 12:06:32.158  7549  7549 I Feature : [Lifetracker]Country: EU
09-07 12:06:32.158  7549  7549 I Feature : [Lifetracker]Operator: OPEN
09-07 12:06:32.158  7549  7549 I Feature : [Lifetracker]Ranking support: false
09-07 12:06:32.158  7549  7549 I Feature : [Lifetracker]Comfort support: false
09-07 12:06:32.158  7549  7549 I Feature : [Lifetracker]Accessory: true
09-07 12:06:32.158  7549  7549 I Feature : [Lifetracker]Health device: true
09-07 12:06:32.158  7549  7549 I Feature : [Lifetracker]Extra Pedometer: false
09-07 12:06:32.158  7549  7549 I Feature : [Lifetracker]Blood glucose device: false
09-07 12:06:32.158  7549  7549 I Feature : [Lifetracker]Device Number: 3
09-07 12:06:32.159  7008  7574 W FormManager: Network not available. Please check & try again.
09-07 12:06:32.160  7172  7172 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-07 12:06:32.161  7172  7172 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-07 12:06:32.162  7132  7576 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 12:06:32.169  7008  7575 V FormManager: Network unavailable.
,09-07 12:06:32.175  7008  7575 V FormManager: Network unavailable.
09-07 12:06:32.177  6889  6889 D BluetoothPermissionRequest: onReceive
09-07 12:06:32.180  7240  7240 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:6:32
,09-07 12:06:32.182  7240  7240 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-07 12:06:32.182  7240  7240 D Weather.Utils: 2 : All the weather widget is gone.
09-07 12:06:32.183  7240  7240 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-07 12:06:32.183  7240  7240 D WeatherAncestor: connectivity changed - connection : true
09-07 12:06:32.183  7240  7240 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@1c5cfed7
09-07 12:06:32.183  7240  7240 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-07 12:06:32.183  7240  7240 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-07 12:06:32.183  7240  7240 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-07 12:06:32.183  7240  7240 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-07 12:06:32.184  7240  7240 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:6:32
09-07 12:06:32.184  6889  6889 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-07 12:06:32.194  1037  1964 V SIM_STK : Menu title from STK is T-Mobile
09-07 12:06:32.194  1037  1964 V SIM_STK : Menu title from STK is T-Mobile
,09-07 12:06:32.206  6497  6497 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,09-07 12:06:32.206  6497  6937 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-07 12:06:32.217  2163  2163 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-07 12:06:32.227  7105  7105 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-07 12:06:32.227  7105  7105 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-07 12:06:32.227  7105  7105 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-07 12:06:32.227  7105  7105 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-07 12:06:32.228  7105  7105 I AppUp4:CustModeStarterReceiver: onReceive
09-07 12:06:32.232  7105  7105 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@3e0cc071
,09-07 12:06:32.232  7105  7105 D AppUp4:CustFacade: isCustomizationCompleted : false
09-07 12:06:32.232  7105  7105 D AppUp4:CustFacade: isPhone : true
09-07 12:06:32.232  7105  7105 D AppUp4:CustModeStarterReceiver: begin check event
09-07 12:06:32.232  7105  7105 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-07 12:06:32.235  4760  4760 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-07 12:06:32.236  4760  4760 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-07 12:06:32.237  4760  4760 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-07 12:06:32.239  4760  4760 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-07 12:06:32.244  7132  7132 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
09-07 12:06:32.245  4760  7580 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-07 12:06:32.250  4760  7581 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-07 12:06:32.250  4760  7581 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,09-07 12:06:32.257  7132  7582 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 12:06:32.262  3161  3161 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-07 12:06:32.262  3161  3161 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-07 12:06:32.262  3161  3161 I LgeMiscReceiver: networkInfo.isConnected() = false
,09-07 12:06:32.264  7172  7172 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-07 12:06:32.264  7172  7172 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-07 12:06:32.272  7008  7586 V FormManager: Network unavailable.
09-07 12:06:32.274  7008  7584 W FormManager: Network not available. Please check & try again.
,09-07 12:06:32.275  7240  7240 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:6:32
,09-07 12:06:32.277  7008  7586 V FormManager: Network unavailable.
09-07 12:06:32.277  7240  7240 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-07 12:06:32.277  7240  7240 D Weather.Utils: 2 : All the weather widget is gone.
09-07 12:06:32.278  7240  7240 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-07 12:06:32.278  7240  7240 D WeatherAncestor: connectivity changed - connection : true
09-07 12:06:32.278  7240  7240 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@1c5cfed7
09-07 12:06:32.279  7240  7240 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-07 12:06:32.279  7240  7240 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-07 12:06:32.279  7240  7240 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-07 12:06:32.279  7240  7240 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-07 12:06:32.279  7240  7240 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:6:32
09-07 12:06:32.286  1037  1893 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,09-07 12:06:32.293  7039  7039 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
09-07 12:06:32.297  7039  7039 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-07 12:06:32.297  7039  7039 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-07 12:06:32.297  7039  7039 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-07 12:06:32.297  7039  7039 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-07 12:06:32.298  7039  7039 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-07 12:06:32.298  7039  7039 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-07 12:06:32.298  7039  7039 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-07 12:06:32.298  7039  7039 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-07 12:06:32.298  7039  7039 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
,09-07 12:06:32.298  7039  7039 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-07 12:06:32.298  7039  7039 I BluetoothA2dpServiceJni: classInitNative
09-07 12:06:32.298  7039  7039 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-07 12:06:32.298  7039  7039 D A2dpStateMachine: make
09-07 12:06:32.299  7039  7039 I bluedroid-qcom: get_profile_interface a2dp
09-07 12:06:32.299  7039  7588 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
09-07 12:06:32.301  7039  7039 I LGBluetoothA2dpServiceJni: classInitNative: succeeds,
09-07 12:06:32.301  7039  7039 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
09-07 12:06:32.302  7039  7039 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c5cfed7
09-07 12:06:32.302  7039  7587 D A2dpStateMachine: Enter Disconnected: -2
09-07 12:06:32.302  7039  7039 I BluetoothHidServiceJni: classInitNative: succeeds
09-07 12:06:32.304  7039  7039 D HidService: Received start request. Starting profile...
09-07 12:06:32.304  7039  7039 I bluedroid-qcom: get_profile_interface hidhost
09-07 12:06:32.304  7039  7039 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c5cfed7
09-07 12:06:32.304  7039  7039 I BluetoothHealthServiceJni: classInitNative: succeeds
09-07 12:06:32.306  7039  7039 D HealthService: Received start request. Starting profile...
09-07 12:06:32.307  7039  7039 I bluedroid-qcom: get_profile_interface health
09-07 12:06:32.307  7039  7039 I LGBluetoothHealthServiceJni: classInitNative: succeeds
09-07 12:06:32.307  7039  7039 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c5cfed7
09-07 12:06:32.308  7039  7039 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-07 12:06:32.309  7039  7039 D PanService: Received start request. Starting profile...
09-07 12:06:32.309  7039  7039 D BluetoothPanServiceJni: initializeNative(L110): pan
09-07 12:06:32.309  7039  7039 I bluedroid-qcom: get_profile_interface pan
,09-07 12:06:32.313  7039  7039 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
09-07 12:06:32.313  7039  7039 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c5cfed7
09-07 12:06:32.313  7039  7039 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
09-07 12:06:32.316  7039  7039 D BtGatt.DebugUtils: handleDebugAction() action=null
09-07 12:06:32.317  7039  7039 D BtGatt.GattService: Received start request. Starting profile...
09-07 12:06:32.317  7039  7039 D BtGatt.GattService: start()
09-07 12:06:32.317  7039  7039 I bluedroid-qcom: get_profile_interface gatt
09-07 12:06:32.317  7039  7039 D BtGatt.AdvertiseManager: advertise manager created
09-07 12:06:32.320  7039  7039 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c5cfed7
09-07 12:06:32.320  7039  7039 D HeadsetStateMachine: Proxy object connected
09-07 12:06:32.321  7039  7039 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
09-07 12:06:32.321  7039  7039 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
09-07 12:06:32.322  7039  7039 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c5cfed7
,09-07 12:06:32.322  7039  7039 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
09-07 12:06:32.323  7039  7039 V BluetoothMapService: BluetoothMapBinder()
09-07 12:06:32.323  7039  7039 D BluetoothMapService: Received start request. Starting profile...
09-07 12:06:32.323  7039  7039 D BluetoothMapService: start()
09-07 12:06:32.325  7039  7039 D BluetoothMapEmailSettingsLoader: Found 0 applications
09-07 12:06:32.325  7039  7039 D BluetoothMapEmailAppObserver: createReceiver()
09-07 12:06:32.326  7039  7039 D BluetoothMapEmailAppObserver: initObservers()
09-07 12:06:32.326  7039  7039 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
09-07 12:06:32.331  7039  7039 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c5cfed7
09-07 12:06:32.333  7039  7039 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-07 12:06:32.333  7039  7566 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-07 12:06:32.334  7039  7566 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-07 12:06:32.334  7039  7566 D HeadsetStateMachine: Disconnected process message: 11, size: 0
09-07 12:06:32.335  7039  7039 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-07 12:06:32.337  7039  7039 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-07 12:06:32.339  7039  7039 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-07 12:06:32.339  7039  7039 V PanService: [BTUI] SIM Extra State :ABSENT
09-07 12:06:32.341  7039  7039 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-07 12:06:32.342  7039  7039 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
09-07 12:06:32.342  7039  7039 V BluetoothMapService: Handler(): got msg=1
09-07 12:06:32.343  7039  7526 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
09-07 12:06:32.343  7039  7526 I bluedroid-qcom: enable
09-07 12:06:32.343  7039  7596 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
09-07 12:06:32.343  7039  7596 I bt-btu  : btu_task pending for preload complete event
09-07 12:06:32.343  7039  7526 I bt_hci_bdroid: init
09-07 12:06:32.344  7039  7039 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-07 12:06:32.344  7039  7526 I bt_vendor: bt-vendor : init
09-07 12:06:32.344  7039  7526 I bt_vendor: bt-vendor : get_bt_soc_type
09-07 12:06:32.345  7039  7526 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-07 12:06:32.345  7039  7526 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
09-07 12:06:32.345  7039  7526 D bt_userial_mct: userial_init
,09-07 12:06:32.345  7039  7526 D bt_hci_bdroid: set_power 1
09-07 12:06:32.345  7039  7526 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-07 12:06:32.345  7039  7526 I bt_vendor: Starting hciattach daemon
09-07 12:06:32.345  7039  7526 I bt_vendor: try to set true
09-07 12:06:32.346  7039  7039 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-07 12:06:32.346  7039  7039 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-07 12:06:32.346  7039  7039 V BluetoothSapReceiver: SapReceiver onReceive 
09-07 12:06:32.346  7039  7039 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-07 12:06:32.346  7039  7039 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
09-07 12:06:32.334  7599  7599 W sh      : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-07 12:06:32.334  7599  7599 W sh      : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-07 12:06:32.365  7600  7600 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,09-07 12:06:32.418  7606  7606 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,09-07 12:06:32.430  7607  7607 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
09-07 12:06:32.454  7609  7609 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-07 12:06:32.478  7610  7610 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,09-07 12:06:32.502  7611  7611 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-07 12:06:32.526  7612  7612 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,09-07 12:06:32.567  7614  7614 I libmdmdetect: ESOC framework not supported
09-07 12:06:32.568  7614  7614 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,09-07 12:06:32.579  7614  7614 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
09-07 12:06:32.579  7614  7614 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
09-07 12:06:32.579  7614  7614 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
09-07 12:06:32.579  7614  7614 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
09-07 12:06:32.579  7614  7614 D bthci_qcomm_common: [BTUI]     LE: Class 2
09-07 12:06:32.579  7614  7614 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
09-07 12:06:32.579  7614  7614 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
09-07 12:06:32.614  7614  7618 E QC-QMI  : qmi_client [7614] 14: failed to locate client data
09-07 12:06:32.614   482   482 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
09-07 12:06:32.614   482   482 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
,09-07 12:06:32.665  7619  7619 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,09-07 12:06:32.682  7620  7620 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-07 12:06:32.698  7039  7526 I bt_vendor: bluetooth satus is on
09-07 12:06:32.698  7039  7526 D bt_hci_bdroid: preload
09-07 12:06:32.699  7039  7598 D bt_userial_mct: userial_open(port:0)
09-07 12:06:32.699  7039  7598 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,09-07 12:06:32.702  7039  7598 I bt_vendor: Done intiailizing UART
09-07 12:06:32.703  7039  7598 I bt_vendor: Done intiailizing UART
,09-07 12:06:32.703  7039  7598 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
09-07 12:06:32.704  7039  7598 I bt_vendor: Bluetooth Firmware and transport layer are initialized
09-07 12:06:32.704  7039  7596 I bt-btu  : btu_task received preload complete event
09-07 12:06:32.704  7039  7622 D bt_userial_mct: Entering userial_read_thread()
09-07 12:06:32.704  7039  7596 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
09-07 12:06:32.705  7039  7596 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
09-07 12:06:32.707  7039  7596 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
09-07 12:06:32.710  7039  7596 I         : BTE_InitTraceLevels -- TRC_HCI
09-07 12:06:32.710  7039  7596 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-07 12:06:32.710  7039  7596 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-07 12:06:32.710  7039  7596 I         : BTE_InitTraceLevels -- TRC_AVDT
09-07 12:06:32.710  7039  7596 I         : BTE_InitTraceLevels -- TRC_AVRC
09-07 12:06:32.710  7039  7596 I         : BTE_InitTraceLevels -- TRC_A2D
09-07 12:06:32.710  7039  7596 I         : BTE_InitTraceLevels -- TRC_BNEP
09-07 12:06:32.710  7039  7596 I         : BTE_InitTraceLevels -- TRC_BTM
09-07 12:06:32.710  7039  7596 I         : BTE_InitTraceLevels -- TRC_HID_HOST
09-07 12:06:32.710  7039  7596 I         : BTE_InitTraceLevels -- TRC_GAP
09-07 12:06:32.710  7039  7596 I         : BTE_InitTraceLevels -- TRC_PAN
09-07 12:06:32.710  7039  7596 I         : BTE_InitTraceLevels -- TRC_SDP
09-07 12:06:32.710  7039  7596 I         : BTE_InitTraceLevels -- TRC_GATT
,09-07 12:06:32.710  7039  7596 I         : BTE_InitTraceLevels -- TRC_SMP
09-07 12:06:32.710  7039  7596 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-07 12:06:32.710  7039  7596 I         : BTE_InitTraceLevels -- TRC_BTIF
09-07 12:06:32.771  7039  7596 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
,09-07 12:06:32.771  7039  7596 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01f3061 
,09-07 12:06:32.771  7039  7596 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01f3061 
,09-07 12:06:32.820  7039  7530 E bt-btif : Calling BTA_HhEnable
09-07 12:06:32.821  7039  7530 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
09-07 12:06:32.821  7039  7596 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
09-07 12:06:32.821  7039  7596 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
,09-07 12:06:32.821  7039  7596 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
09-07 12:06:32.821  7039  7530 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
09-07 12:06:32.822  7039  7596 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
09-07 12:06:32.822  7039  7596 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
09-07 12:06:32.825  1037  1037 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-07 12:06:32.826  7039  7530 D BluetoothAdapterProperties: Name is: G3
09-07 12:06:32.829  1037  1037 D BluetoothManagerService: Stored Bluetooth name: G3
09-07 12:06:32.829  7039  7530 D BluetoothAdapterProperties: Scan Mode:20
09-07 12:06:32.830  7039  7530 D BluetoothAdapterProperties: Discoverable Timeout:120
09-07 12:06:32.831  7039  7530 D bt_hci_bdroid: postload
09-07 12:06:32.832  7039  7530 D bte_conf: Device ID record 1 : primary
09-07 12:06:32.832  7039  7530 D bte_conf:   vendorId            = 00c4
09-07 12:06:32.832  7039  7530 D bte_conf:   vendorIdSource      = 0001
09-07 12:06:32.833  7039  7530 D bte_conf:   product             = 13a1
09-07 12:06:32.833  7039  7530 D bte_conf:   version             = 1000
09-07 12:06:32.833  7039  7530 D bte_conf:   clientExecutableURL = 
09-07 12:06:32.833  7039  7530 D bte_conf:   serviceDescription  = 
09-07 12:06:32.833  7039  7530 D bte_conf:   documentationURL    = 
09-07 12:06:32.833  7039  7530 D bte_conf: bte_load_did_conf no section named DID2.
09-07 12:06:32.835  7039  7598 D bt_hci_bdroid: Used up Tx Cmd credits
09-07 12:06:32.840  7039  7598 D bt_hci_bdroid: Used up Tx Cmd credits
09-07 12:06:32.840  7039  7526 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-07 12:06:32.840  7039  7598 D bt_hci_bdroid: Used up Tx Cmd credits
09-07 12:06:32.840  7039  7526 D BluetoothAdapterProperties: ScanMode =  20
09-07 12:06:32.841  7039  7596 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
09-07 12:06:32.841  7039  7526 D BluetoothAdapterProperties: State =  11
09-07 12:06:32.841  7039  7526 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
09-07 12:06:32.841  7039  7530 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-07 12:06:32.842  7039  7526 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
09-07 12:06:32.842  7039  7526 D BluetoothAdapterProperties: Setting state to 12
,09-07 12:06:32.824  7624  7624 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-07 12:06:32.846  7039  7530 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-07 12:06:32.834  7624  7624 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-07 12:06:32.848  7039  7526 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-07 12:06:32.848  1037  1119 D BluetoothManagerService: Message: 60
09-07 12:06:32.849  1037  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
09-07 12:06:32.849  1037  1119 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
09-07 12:06:32.849  1037  1119 D BluetoothA2dp: onBluetoothStateChange: up=true
09-07 12:06:32.850  7039  7526 I BluetoothAdapterState: Entering On State
09-07 12:06:32.851  7039  7596 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-07 12:06:32.851  7039  7596 W bt-smp  : Plain text(LSB ~ MSB) = 11 60 4f 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-07 12:06:32.851  7039  7596 W bt-smp  : Encrypted text(LSB ~ MSB) = 46 09 89 2d 05 f2 6f dc 12 c8 58 14 51 31 9d b2 
09-07 12:06:32.853  7039  7598 D bt_hci_bdroid: Used up Tx Cmd credits
09-07 12:06:32.854  7039  7596 W bt-btm  : Stopping oneshot timer
09-07 12:06:32.855  7039  7622 E bt_mct  : hci lib postload completed
,09-07 12:06:32.857  7039  7526 D LGBluetoothServiceAdapter: [BTUI] OnState
09-07 12:06:32.857  7039  7526 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
09-07 12:06:32.857  7039  7526 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
09-07 12:06:32.859  7039  7526 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
09-07 12:06:32.860  6798  6798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 12:06:32.860  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:06:32.860  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 12:06:32.860  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 12:06:32.860  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 12:06:32.860  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 12:06:32.860  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 12:06:32.860  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 12:06:32.864  1037  1037 D BluetoothA2dp: Proxy object connected
09-07 12:06:32.864  6798  6798 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 12:06:32.865  6889  6906 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-07 12:06:32.868  7039  7530 D BluetoothAdapterProperties: Discoverable Timeout:120
09-07 12:06:32.868  7039  7530 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
09-07 12:06:32.870  1037  1119 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 12:06:32.871  6889  6906 D BluetoothPbap: onBluetoothStateChange: up=true
09-07 12:06:32.875  1037  1037 D BluetoothHeadset: Proxy object connected
09-07 12:06:32.877  6889  6908 D BluetoothPan: onBluetoothStateChange on: true
09-07 12:06:32.877  6889  6908 D BluetoothPan: onBluetoothStateChange call bindService
09-07 12:06:32.878  6798  6798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 12:06:32.878  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:06:32.878  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 12:06:32.878  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 12:06:32.878  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 12:06:32.878  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 12:06:32.878  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 12:06:32.878  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 12:06:32.880  6889  6889 D BluetoothInputDevice: Proxy object connected
09-07 12:06:32.880  6889  6889 D HidProfile: Bluetooth service connected
09-07 12:06:32.881  6798  6798 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 12:06:32.885  1840  3324 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 12:06:32.885  6889  6889 D BluetoothPan: BluetoothPAN Proxy object connected
09-07 12:06:32.885  6889  6889 D PanProfile: Bluetooth service connected
09-07 12:06:32.887  1840  3324 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 12:06:32.887  1840  1840 D BluetoothHeadset: Proxy object connected
09-07 12:06:32.888  7039  7596 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-07 12:06:32.888  7039  7596 W bt-smp  : Plain text(LSB ~ MSB) = 12 98 5f 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-07 12:06:32.889  7039  7596 W bt-smp  : Encrypted text(LSB ~ MSB) = 08 c4 97 c3 c3 19 7f 71 50 8b 2e e5 61 e0 d5 bb 
09-07 12:06:32.889  7039  7596 W bt-btm  : Stopping oneshot timer
09-07 12:06:32.889  1840  1840 D BluetoothHeadset: Proxy object connected
09-07 12:06:32.890  6889  6908 D BluetoothMap: onBluetoothStateChange: up=true
,09-07 12:06:32.894  1840  1856 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 12:06:32.896  1840  1840 D BluetoothHeadset: Proxy object connected
09-07 12:06:32.898  1037  1119 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
09-07 12:06:32.898  1037  1037 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
09-07 12:06:32.898  1037  1119 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
09-07 12:06:32.900  1592  1592 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-07 12:06:32.900  7039  7526 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
09-07 12:06:32.902  1930  1930 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-07 12:06:32.902  1930  2132 D LGBluetoothAPIService: Message: 1
,09-07 12:06:32.902  1930  2132 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
09-07 12:06:32.906  1037  1119 D BluetoothManagerService: Message: 40
09-07 12:06:32.906  1037  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
09-07 12:06:32.907  7039  7596 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-07 12:06:32.907  7039  7596 W bt-smp  : Plain text(LSB ~ MSB) = 43 5e 6c 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-07 12:06:32.907  7039  7596 W bt-smp  : Encrypted text(LSB ~ MSB) = 45 f5 65 ec 2e fc e7 89 0c 88 12 96 85 87 b1 60 
09-07 12:06:32.907  7039  7596 W bt-btm  : Stopping oneshot timer
09-07 12:06:32.910  7039  7039 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-07 12:06:32.910  7039  7039 D BluetoothMapService: STATE_ON
09-07 12:06:32.910  7039  7039 V BluetoothMapService: Handler(): got msg=1
09-07 12:06:32.911  7039  7039 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
09-07 12:06:32.912  7039  7634 D BluetoothMapMasInstance: MAS initSocket()
09-07 12:06:32.913  7039  7634 D BluetoothMapMasInstance:   masId = 00
09-07 12:06:32.913  7039  7634 D BluetoothMapMasInstance:   msgTypes = 0e
09-07 12:06:32.913  7039  7634 D BluetoothMapMasInstance:   masName = SMS/MMS
09-07 12:06:32.913  7039  7634 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
09-07 12:06:32.920  1037  1564 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 12:06:32.920  7039  7596 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-07 12:06:32.920  7039  7596 W bt-smp  : Plain text(LSB ~ MSB) = 9e bc 45 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-07 12:06:32.920  7039  7596 W bt-smp  : Encrypted text(LSB ~ MSB) = 94 b5 47 13 6d 26 e3 79 44 35 c0 1a f0 50 60 81 
09-07 12:06:32.920  7039  7596 W bt-btm  : Stopping oneshot timer
,09-07 12:06:32.921  7039  7634 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-07 12:06:32.923  7039  7634 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
09-07 12:06:32.924  7039  7634 V BluetoothMapMasInstance: Succeed to create listening socket 
09-07 12:06:32.924  7039  7634 D BluetoothMapMasInstance: Accepting socket connection...
09-07 12:06:32.926  7635  7635 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
09-07 12:06:32.929  6889  6889 D BluetoothMap: Proxy object connected
09-07 12:06:32.929  6889  6889 D MapProfile: Bluetooth service connected
09-07 12:06:32.929  6889  6889 D BluetoothMap: getConnectedDevices()
09-07 12:06:32.929  1930  2132 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
09-07 12:06:32.930  7039  7530 D BluetoothAdapterProperties: Scan Mode:21
09-07 12:06:32.930  7039  7530 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
09-07 12:06:32.931  7039  7039 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c5cfed7
09-07 12:06:32.931  7039  7039 V BluetoothPbapService: Pbap Service onCreate
09-07 12:06:32.931  7039  7039 V BluetoothPbapService: Starting PBAP service
09-07 12:06:32.931  6798  6798 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
09-07 12:06:32.932  7039  7039 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
09-07 12:06:32.933  7039  7039 V BluetoothPbapService: Pbap Service onBind
,09-07 12:06:32.935  7039  7039 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-07 12:06:32.935  7039  7039 V BluetoothPbapService: state: 12
09-07 12:06:32.935  6798  6798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 12:06:32.936  7039  7596 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-07 12:06:32.936  7039  7596 W bt-smp  : Plain text(LSB ~ MSB) = 12 57 4f 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-07 12:06:32.936  7039  7596 W bt-smp  : Encrypted text(LSB ~ MSB) = 5d 05 df b7 c9 bd 6f fa 78 6f 66 29 77 36 84 5c 
09-07 12:06:32.936  7039  7596 W bt-btm  : Stopping oneshot timer
09-07 12:06:32.937  6798  6798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 12:06:32.937  7039  7531 V BluetoothMapService: getConnectedDevices()
09-07 12:06:32.938  7039  7039 D LGBluetoothAPIServer: [BTUI] onCreate()
09-07 12:06:32.938  7039  7039 D LGBluetoothAPIServer: [BTUI] onBind()
09-07 12:06:32.939  7039  7039 V BluetoothPbapService: Handler(): got msg=1
09-07 12:06:32.940  7039  7039 V BluetoothPbapService: Pbap Service startRfcommSocketListener
09-07 12:06:32.940  1930  1930 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
09-07 12:06:32.941  1930  2132 D LGBluetoothAPIService: Message: 100
09-07 12:06:32.941  1930  2132 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
09-07 12:06:32.941  6798  6798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 12:06:32.942  7039  7637 V BluetoothPbapService: Pbap Service initSocket
09-07 12:06:32.943  1037  1694 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 12:06:32.945  7039  7637 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-07 12:06:32.946  6798  6798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 12:06:32.949  7039  7637 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
,09-07 12:06:32.949  7039  7637 V BluetoothPbapService: Succeed to create listening socket 
09-07 12:06:32.950  7039  7637 V BluetoothPbapService: Accepting socket connection...
09-07 12:06:32.950  6889  6889 D LocalBluetoothProfileManager: Adding local A2DP profile
09-07 12:06:32.952  1037  1119 D BluetoothManagerService: Message: 30
09-07 12:06:32.954  6889  6889 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-07 12:06:32.956  1037  1119 D BluetoothManagerService: Message: 30
09-07 12:06:32.964  6889  6889 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
,09-07 12:06:32.966  6889  6889 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-07 12:06:32.970  6889  6889 D BluetoothPbap: Proxy object connected
09-07 12:06:32.970  7039  7039 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-07 12:06:32.970  7039  7039 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,09-07 12:06:32.970  7039  7039 V BluetoothPbapReceiver: ***********state = 12
09-07 12:06:32.971  6889  6889 D PbapServerProfile: Bluetooth service connected
,09-07 12:06:32.971  6889  6889 D BluetoothA2dp: Proxy object connected
09-07 12:06:32.974  6889  6889 D A2dpProfile: Bluetooth service connected
09-07 12:06:32.974  2163  2163 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-07 12:06:32.974  2163  2163 D c       : Getting all permits...
09-07 12:06:32.974  2163  2163 D a       : Opening database...
09-07 12:06:32.975  6889  6889 D BluetoothHeadset: Proxy object connected
09-07 12:06:32.976  6889  6889 D HeadsetProfile: Bluetooth service connected
09-07 12:06:32.978  2163  2163 D a       : Opening database auth.proximity.permit_store...
09-07 12:06:32.979  2163  2163 D a       : Closing database...
,09-07 12:06:32.991  6889  6889 D DockEventReceiver: finishStartingService: stopping service
09-07 12:06:32.997  6889  6889 D BluetoothPermissionRequest: onReceive
,09-07 12:06:32.999  6889  6889 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-07 12:06:33.001  6889  6889 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-07 12:06:33.005  7039  7039 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
09-07 12:06:33.006  7039  7039 I LGBluetoothOppAdapter: [BTUI] startOppService()
09-07 12:06:33.012  7039  7039 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,09-07 12:06:33.013  7276  7308 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
09-07 12:06:33.034  7039  7039 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,09-07 12:06:33.034  7039  7039 V BtOppService: onCreate
09-07 12:06:33.039  7039  7039 V BluetoothOppNotification: send message
09-07 12:06:33.043  7039  7039 V BtOppService: Starting RfcommListener
09-07 12:06:33.055  7039  7644 V BtOppService: Deleted complete outbound shares, number =  0
09-07 12:06:33.056  7039  7644 V BtOppService: Deleted complete inbound failed shares, number = 0
09-07 12:06:33.057  7039  7039 D BluetoothOppPreference: Dumping Names:  
09-07 12:06:33.057  7039  7039 D BluetoothOppPreference: {}
09-07 12:06:33.057  7039  7039 D BluetoothOppPreference: Dumping Channels:  
09-07 12:06:33.057  7039  7039 D BluetoothOppPreference: {}
,09-07 12:06:33.058  7039  7039 V BtOppService: onStartCommand
09-07 12:06:33.065  7039  7647 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-07 12:06:33.066  7039  7039 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-07 12:06:33.066  7039  7644 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
09-07 12:06:33.066  7039  7039 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-07 12:06:33.067  7039  7647 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-07 12:06:33.069  7039  7644 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1dea4bc0 on behalf of 
,09-07 12:06:33.074  7039  7647 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3656f0f9 on behalf of 
09-07 12:06:33.074  7039  7039 V BluetoothOppNotification: new notify threadi!
09-07 12:06:33.077  7039  7039 V BluetoothOppNotification: send delay message
09-07 12:06:33.078  7039  7039 V BtOppService: start RfcommListener
09-07 12:06:33.082  7039  7647 V BluetoothOppNotification: update too frequent, put in queue
09-07 12:06:33.082  7039  7648 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,09-07 12:06:33.084  7039  7647 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
,09-07 12:06:33.084  7039  7648 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3a06a83e on behalf of 
09-07 12:06:33.086  7039  7648 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-07 12:06:33.087  7039  7039 V BtOppService: RfcommListener started
09-07 12:06:33.087  7039  7039 V BtOppService: ContentObserver received notification
09-07 12:06:33.089  7039  7649 V BtOppRfcommListener: Starting RFCOMM listener....
09-07 12:06:33.090  7039  7039 V BtOppService: ContentObserver received notification
09-07 12:06:33.090  1037  1874 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 12:06:33.091  7039  7649 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-07 12:06:33.092  7039  7649 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
09-07 12:06:33.093  7039  7649 V BtOppRfcommListener: Started RFCOMM listener....
09-07 12:06:33.093  7039  7649 I BtOppRfcommListener: Accept thread started.
09-07 12:06:33.093  7039  7649 V BtOppRfcommListener: Accepting connection...
09-07 12:06:33.093  7039  7648 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-07 12:06:33.094  7039  7650 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-07 12:06:33.095  7039  7650 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-07 12:06:33.097  7039  7650 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1a0cb69f on behalf of 
09-07 12:06:33.098  7039  7648 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@150863ec on behalf of 
09-07 12:06:33.100  7039  7648 V BluetoothOppNotification: outbound: succ-0  fail-0
,09-07 12:06:33.102  7039  7650 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-07 12:06:33.105  7039  7648 V BluetoothOppNotification: outbound notification was removed.
09-07 12:06:33.105  7039  7648 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-07 12:06:33.110  7039  7039 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c5cfed7
09-07 12:06:33.110  7039  7039 V BluetoothFtpService: Ftp Service onCreate
,09-07 12:06:33.111  7039  7039 I BluetoothFtpService: Ftp Service onCreate
09-07 12:06:33.111  7039  7039 V BluetoothFtpService: Ftp Service onStartCommand
09-07 12:06:33.111  7039  7039 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-07 12:06:33.112  7039  7039 V BluetoothFtpService: Starting Listening on sockets
09-07 12:06:33.112  7039  7648 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@13c10a4a on behalf of 
09-07 12:06:33.112  7039  7039 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-07 12:06:33.113  7039  7039 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-07 12:06:33.113  7039  7039 V BluetoothSapReceiver: SapReceiver onReceive 
09-07 12:06:33.113  7039  7039 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
,09-07 12:06:33.113  7039  7039 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
,09-07 12:06:33.113  7039  7039 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-07 12:06:33.114  7039  7648 V BluetoothOppNotification: inbound: succ-0  fail-0
09-07 12:06:33.115  7039  7648 V BluetoothOppNotification: inbound notification was removed.
09-07 12:06:33.116  7039  7648 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-07 12:06:33.116  7039  7039 V BluetoothFtpService: Handler(): got msg=1
09-07 12:06:33.117  7039  7039 V BluetoothFtpService: Ftp Service startRfcommSocketListener
09-07 12:06:33.117  7039  7039 V BluetoothFtpService: Ftp Service initSocket
09-07 12:06:33.118  7039  7648 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@39901dbb on behalf of 
09-07 12:06:33.127  1037  1893 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 12:06:33.128  7039  7039 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 12:06:33.130  7039  7039 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=79
09-07 12:06:33.130  7039  7039 V BluetoothFtpService: Succeed to create listening socket on channel 20
09-07 12:06:33.133  7039  7651 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
09-07 12:06:33.150  7039  7039 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c5cfed7
09-07 12:06:33.150  7039  7039 V BluetoothSapService: Sap Service onCreate
,09-07 12:06:33.153  7039  7039 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-07 12:06:33.153  7039  7039 V BluetoothSapService: state: 12
09-07 12:06:33.153  7039  7039 V BluetoothSapService: Starting SAP server process
09-07 12:06:33.156  7039  7039 V BluetoothSapService: SAP Service startRfcommListenerThread
09-07 12:06:33.144  7652  7652 W sapd    : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-07 12:06:33.144  7652  7652 W sapd    : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-07 12:06:33.158  7039  7653 V BluetoothSapService: Sap Service initRfcommSocket
09-07 12:06:33.159  1037  1911 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 12:06:33.163  7039  7653 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 12:06:33.167  7039  7653 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
,09-07 12:06:33.167  7039  7653 V BluetoothSapService: Succeed to create listening socket 
,09-07 12:06:33.167  7039  7653 V BluetoothSapService: Accepting socket connection...
09-07 12:06:33.179  7652  7652 V BT_SAP  : Event pipe created
09-07 12:06:33.179  7652  7652 V BT_SAP  : create_server_socket qcom.sap.server
09-07 12:06:33.179  7652  7652 V BT_SAP  : created socket fd 6
,09-07 12:06:33.799  1037  1526 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-07 12:06:33.799  1037  1526 D LGWifiP2pService: DefaultState{ when=-2ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,09-07 12:06:33.853  1037  1527 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
09-07 12:06:33.854  1037  1527 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,09-07 12:06:34.078  7039  7039 V BluetoothOppNotification: new notify threadi!
09-07 12:06:34.079  7039  7039 V BluetoothOppNotification: send delay message
,09-07 12:06:34.086  7039  7663 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-07 12:06:34.091  1037  1911 I ActivityManager: Killing 7447:com.lge.bnr/1000 (adj 15): empty #17
09-07 12:06:34.097  7039  7663 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3418da97 on behalf of 
,09-07 12:06:34.110  7039  7663 V BluetoothOppNotification: mUpdateCompleteNotification = true
,09-07 12:06:34.120  7039  7663 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-07 12:06:34.121  7039  7663 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@28f94484 on behalf of 
09-07 12:06:34.123  7039  7663 V BluetoothOppNotification: outbound: succ-0  fail-0
,09-07 12:06:34.126  7039  7663 V BluetoothOppNotification: outbound notification was removed.
09-07 12:06:34.126  7039  7663 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-07 12:06:34.164  1037  1564 W libprocessgroup: failed to open /acct/uid_1000/pid_7447/cgroup.procs: No such file or directory
,09-07 12:06:34.291  1037  1052 I art     : Explicit concurrent mark sweep GC freed 94418(4MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 3.135ms total 157.410ms
,09-07 12:06:34.305  1037  1874 I ActivityManager: Killing 6718:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,09-07 12:06:34.316  7039  7663 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@271a946d on behalf of 
09-07 12:06:34.316  7039  7663 V BluetoothOppNotification: inbound: succ-0  fail-0
,09-07 12:06:34.329  6971  6971 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
09-07 12:06:34.330  6971  6971 W System.err: android.os.DeadObjectException
09-07 12:06:34.330  6971  6971 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-07 12:06:34.330  6971  6971 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-07 12:06:34.330  6971  6971 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
09-07 12:06:34.330  6971  6971 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
09-07 12:06:34.330  6971  6971 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-07 12:06:34.330  6971  6971 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-07 12:06:34.330  6971  6971 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-07 12:06:34.330  6971  6971 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-07 12:06:34.330  6971  6971 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-07 12:06:34.331  6971  6971 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-07 12:06:34.331  6971  6971 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 12:06:34.331  6971  6971 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 12:06:34.331  6971  6971 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-07 12:06:34.331  6971  6971 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-07 12:06:34.331  6971  6971 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
09-07 12:06:34.331  6971  6971 W System.err: android.os.DeadObjectException
09-07 12:06:34.331  6971  6971 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-07 12:06:34.331  6971  6971 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-07 12:06:34.331  6971  6971 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
09-07 12:06:34.331  6971  6971 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
09-07 12:06:34.331  6971  6971 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-07 12:06:34.331  6971  6971 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-07 12:06:34.332  6971  6971 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-07 12:06:34.333  6971  6971 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-07 12:06:34.333  6971  6971 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-07 12:06:34.333  6971  6971 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-07 12:06:34.333  6971  6971 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 12:06:34.333  6971  6971 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 12:06:34.333  6971  6971 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-07 12:06:34.333  6971  6971 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-07 12:06:34.333  6971  6971 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
09-07 12:06:34.333  6971  6971 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
09-07 12:06:34.334  7039  7663 V BluetoothOppNotification: inbound notification was removed.
09-07 12:06:34.334  7039  7663 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.,
09-07 12:06:34.335  7039  7663 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@38d898a2 on behalf of 
09-07 12:06:34.339  1037  1964 W libprocessgroup: failed to open /acct/uid_1000/pid_6718/cgroup.procs: No such file or directory
09-07 12:06:34.340  1037  1964 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,09-07 12:06:34.349  6971  6971 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
09-07 12:06:34.350  6971  6971 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
09-07 12:06:34.405  1037  1052 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7669 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-07 12:06:34.406  6971  6971 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,09-07 12:06:34.430   351   351 I art     : Explicit concurrent mark sweep GC freed 708(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 517us total 26.619ms
,09-07 12:06:34.451   351   351 I art     : Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 432us total 19.734ms
,09-07 12:06:34.471   351   351 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 412us total 19.063ms
,09-07 12:06:34.488  7669  7669 D UEI.SmartControl: Quickset Services start...
09-07 12:06:34.490  7669  7669 I UEI.SmartControl: Manufacture = LGE
09-07 12:06:34.490  7669  7669 D UEI.SmartControl: Id = LGNevo
,09-07 12:06:34.494  7669  7669 D UEI.SmartControl: File observer start...
09-07 12:06:34.494  7669  7669 E UEI.SmartControl: IR Port is disabled: false
09-07 12:06:34.495  7669  7669 D UEI.SmartControl: Starting file observer...
09-07 12:06:34.495  7669  7669 D UEI.SmartControl: Extracting JNI libs...
09-07 12:06:34.495  7669  7669 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
09-07 12:06:34.594  7669  7669 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
09-07 12:06:34.594  7669  7669 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
09-07 12:06:34.594  7669  7669 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,09-07 12:06:34.622  7669  7669 I UEI.SmartControl: --- Selecting new region: 6
,09-07 12:06:34.624  7669  7669 I UEI.SmartControl: Model = LG-D855
09-07 12:06:34.625  7669  7669 D UEI.SmartControl: QS Service created
,09-07 12:06:34.637  7669  7669 I UEI.SmartControl: Service initServices...
,09-07 12:06:34.640  7669  7669 D UEI.SmartControl: QS start get config
,09-07 12:06:34.676  7669  7669 D UEI.SmartControl: Loading JNI Libs...
,09-07 12:06:34.787  1037  1929 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-07 12:06:34.788  1037  1929 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@7cb9dda mBinding = false
,09-07 12:06:34.810  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-07 12:06:34.810  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-07 12:06:34.810  1037  1037 D Ulp_jni : JNI:system_update. Event-4
09-07 12:06:34.810  1037  1119 D BluetoothManagerService: Message: 2
09-07 12:06:34.811  1037  1119 D BluetoothManagerService: Sending off request.
09-07 12:06:34.813  7039  7626 D LGBluetoothServiceAdapter: [BTUI] Precleanup
09-07 12:06:34.814  7039  7526 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
09-07 12:06:34.815  7039  7526 D BluetoothAdapterProperties: Setting state to 13
09-07 12:06:34.815  7039  7526 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-07 12:06:34.816  7039  7526 D BluetoothAdapterProperties: onBluetoothDisable()
09-07 12:06:34.816  7039  7526 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-07 12:06:34.817  7039  7530 D BluetoothAdapterProperties: Scan Mode:20
09-07 12:06:34.817  7039  7526 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-07 12:06:34.820  7039  7634 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
09-07 12:06:34.820  7039  7634 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-07 12:06:34.820  7039  7634 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
09-07 12:06:34.820  7039  7634 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
09-07 12:06:34.820  7039  7634 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
09-07 12:06:34.820  7039  7634 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
09-07 12:06:34.820  7039  7634 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
09-07 12:06:34.820  7039  7634 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
09-07 12:06:34.821  7039  7637 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-07 12:06:34.828  7039  7649 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-07 12:06:34.830  7039  7651 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-07 12:06:34.831  7039  7653 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-07 12:06:34.832  7039  7596 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
09-07 12:06:34.832  7039  7596 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
09-07 12:06:34.834  7039  7526 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-07 12:06:34.839  7039  7596 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-07 12:06:34.839  7039  7596 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-07 12:06:34.839  7039  7596 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-07 12:06:34.839  7039  7596 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-07 12:06:34.839  7039  7596 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-07 12:06:34.839  7039  7596 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-07 12:06:34.839  7039  7596 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-07 12:06:34.839  7039  7596 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-07 12:06:34.839  7039  7596 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-07 12:06:34.839  7039  7596 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
09-07 12:06:34.839  7039  7596 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
09-07 12:06:34.840  7039  7596 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
,09-07 12:06:34.845  6798  6798 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 12:06:34.845  6798  6798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 12:06:34.845  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:06:34.845  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 12:06:34.845  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 12:06:34.845  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 12:06:34.845  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 12:06:34.845  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 12:06:34.845  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 12:06:34.846  1037  1119 D BluetoothManagerService: Message: 60
09-07 12:06:34.846  1037  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
09-07 12:06:34.846  1037  1119 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
09-07 12:06:34.846  6798  6798 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 12:06:34.846  6798  6798 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 12:06:34.849  1930  1930 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-07 12:06:34.850  1592  1592 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-07 12:06:34.853  6889  6889 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
,09-07 12:06:34.858  6798  6798 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 12:06:34.858  6798  6798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 12:06:34.858  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:06:34.858  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 12:06:34.858  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 12:06:34.858  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 12:06:34.858  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 12:06:34.858  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 12:06:34.858  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 12:06:34.861  6798  6798 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 12:06:34.861  6798  6798 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 12:06:34.863  6798  6798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 12:06:34.865  6798  6798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 12:06:34.865  7039  7039 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-07 12:06:34.865  7039  7039 D BluetoothMapService: STATE_TURNING_OFF
09-07 12:06:34.865  7039  7039 V BluetoothMapService: Handler(): got msg=4
09-07 12:06:34.865  7039  7039 D BluetoothMapService: MAP Service closeService in
09-07 12:06:34.865  7039  7039 D BluetoothMapMasInstance: MAP Service shutdown
09-07 12:06:34.866  7039  7039 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-07 12:06:34.866  7039  7039 V BluetoothMapService: MAP Service closeService out
09-07 12:06:34.867  7039  7039 V BtOppService: Receiver DISABLED_ACTION 
09-07 12:06:34.867  7039  7039 I BtOppRfcommListener: stopping Accept Thread
,09-07 12:06:34.867  7039  7039 V BtOppRfcommListener: close mBtServerSocket
09-07 12:06:34.868  7039  7649 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-07 12:06:34.868  7039  7039 V BtOppRfcommListener: waiting for thread to terminate
09-07 12:06:34.869  7039  7039 V BtOppRfcommListener: done waiting for thread to terminate
09-07 12:06:34.870  6889  6889 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-07 12:06:34.877  7039  7039 V BtOppService: onDestroy
09-07 12:06:34.884  7039  7039 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
09-07 12:06:34.884  6889  6889 D DockEventReceiver: finishStartingService: stopping service
,09-07 12:06:34.884  7039  7039 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-07 12:06:34.886  7039  7039 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-07 12:06:34.886  7039  7039 V BluetoothPbapReceiver: ***********state = 13
09-07 12:06:34.887  7039  7039 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
09-07 12:06:34.888  7039  7039 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-07 12:06:34.888  7039  7039 V BluetoothPbapService: state: 13
09-07 12:06:34.888  7039  7039 V BluetoothPbapService: Pbap Service closeService in
09-07 12:06:34.889  7039  7039 V BluetoothPbapService: successfully stopped pbap service
09-07 12:06:34.889  7039  7039 V BluetoothPbapService: Pbap Service closeService out
09-07 12:06:34.890  6889  6889 D BluetoothPbap: Proxy object disconnected
09-07 12:06:34.890  6889  6889 D PbapServerProfile: Bluetooth service disconnected
09-07 12:06:34.890  7039  7039 V BluetoothPbapService: Pbap Service onDestroy
09-07 12:06:34.890  7039  7039 V BluetoothPbapService: Pbap Service closeService in
09-07 12:06:34.890  7039  7039 V BluetoothPbapService: Pbap Service closeService out
09-07 12:06:34.890  7039  7039 D LGBluetoothPbapAdapter: [BTUI] cleanup
09-07 12:06:34.893  2163  2163 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-07 12:06:34.907  6889  6889 D LGBluetoothAuthorization: [BTUI] cancel All Notification
09-07 12:06:34.910  6889  6889 D BluetoothPermissionRequest: onReceive
09-07 12:06:34.910  6889  6889 D LGBluetoothAuthorization: [BTUI] cancel All Notification
09-07 12:06:34.914  6889  6889 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,09-07 12:06:34.916  7039  7039 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
09-07 12:06:34.917  7039  7039 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
09-07 12:06:34.917  7039  7039 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
09-07 12:06:34.920  7039  7039 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-07 12:06:34.920  7039  7039 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-07 12:06:34.920  7039  7039 V BluetoothFtpService: Ftp Service onStartCommand
09-07 12:06:34.920  7039  7039 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-07 12:06:34.920  7039  7039 V BluetoothFtpService: Ftp Service closeService
09-07 12:06:34.921  7039  7039 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
09-07 12:06:34.922  7039  7039 V BluetoothFtpService: successfully stopped ftp service
09-07 12:06:34.922  7039  7039 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-07 12:06:34.923  7039  7039 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-07 12:06:34.923  7039  7039 V BluetoothSapReceiver: SapReceiver onReceive 
09-07 12:06:34.923  7039  7039 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-07 12:06:34.923  7039  7039 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
09-07 12:06:34.923  7039  7039 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-07 12:06:34.924  7039  7039 V BluetoothFtpService: Ftp Service onDestroy
09-07 12:06:34.924  7039  7039 V BluetoothFtpService: Ftp Service closeService
09-07 12:06:34.927  7039  7039 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-07 12:06:34.927  7039  7039 V BluetoothSapService: state: 13
09-07 12:06:34.927  7039  7039 V BluetoothSapService: Stopping SAP server process
09-07 12:06:34.928  7039  7039 V BluetoothSapService: Sap Service closeSapService in
09-07 12:06:34.928  7039  7039 V BluetoothSapService: Close listen Socket : 
09-07 12:06:34.928  7039  7039 V BluetoothSapService: Close rfcomm Socket : 
09-07 12:06:34.928  7039  7039 V BluetoothSapService: Close sapd  Socket : 
09-07 12:06:34.930  7039  7039 V BluetoothSapService: Sap Service closeSapService out
09-07 12:06:34.930  7039  7039 V BluetoothSapService: Sap Service onDestroy
,09-07 12:06:34.930  7039  7039 V BluetoothSapService: Sap Service closeSapService in
09-07 12:06:34.930  7039  7039 V BluetoothSapService: Close listen Socket : 
09-07 12:06:34.931  7039  7039 V BluetoothSapService: Close rfcomm Socket : 
09-07 12:06:34.931  7039  7039 V BluetoothSapService: Close sapd  Socket : 
09-07 12:06:34.931  7039  7039 V BluetoothSapService: Sap Service closeSapService out
09-07 12:06:35.007  7669  7669 I UEI.SmartControl: Supports setup maps: true
,09-07 12:06:35.010  7669  7669 D UEI.SmartControl: QS start statue = true Error code = 0
09-07 12:06:35.010  7669  7669 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-07 12:06:35.010  7669  7669 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-07 12:06:35.010  7669  7669 I UEI.SmartControl: ### init IR Blaster...
09-07 12:06:35.016  7669  7669 D serial_port: Configuring serial port
09-07 12:06:35.020  7669  7669 E UEI.SmartControl: UEIBLaster setting for 616
09-07 12:06:35.020  7669  7669 I UEI.SmartControl: Setting serial record hearder size = 2
09-07 12:06:35.020  7669  7669 I UEI.SmartControl: configuring settings for MAXQ616
09-07 12:06:35.020  7669  7669 I UEI.SmartControl: Get version...
09-07 12:06:35.037  7669  7718 D UEI.SmartControl: serial port data available: 21
,09-07 12:06:35.065  7669  7669 D UEI.SmartControl: MAXQ616 A2-X4 software.
09-07 12:06:35.065  7669  7669 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-07 12:06:35.066  7669  7669 I UEI.SmartControl: QS saving settings...
,09-07 12:06:35.067  7669  7669 D UEI.SmartControl: IR Blaster version: 25672567
09-07 12:06:35.084  7669  7718 D UEI.SmartControl: serial port data available: 4
,09-07 12:06:35.126  7669  7722 I UEI.SmartControl: Device manager: loading config....
09-07 12:06:35.128  7669  7722 D UEI.SmartControl: ----------- loading internal config...
,09-07 12:06:35.129  7669  7669 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,09-07 12:06:35.133  7669  7669 E UEI.SmartControl: Services init done
,09-07 12:06:35.133  7669  7669 D UEI.SmartControl: QS Service init finished
09-07 12:06:35.141  7669  7669 D UEI.SmartControl: QS Service version name: 2.1.91
09-07 12:06:35.141  7669  7669 D UEI.SmartControl: QS Service version code: 201091
09-07 12:06:35.144  7669  7669 D UEI.SmartControl: Service requested: Control
,09-07 12:06:35.151  7669  7722 E UEI.SmartControl: Loading SETTINGS...
,09-07 12:06:35.155  7669  7669 D UEI.SmartControl: Request IControl service: devices are loaded...
09-07 12:06:35.158  6971  6971 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
09-07 12:06:35.160  7669  7722 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
09-07 12:06:35.161  7669  7693 I UEI.SmartControl: ------ IControl API: 11
,09-07 12:06:35.164  7669  7693 I UEI.SmartControl: Registering callback...
09-07 12:06:35.165  7669  7695 I UEI.SmartControl: ------ IControl API: 19
09-07 12:06:35.167  1037  2001 I ActivityManager: Killing 6971:com.lge.qremote/u0a112 (adj 15): empty #17
,09-07 12:06:35.169  7669  7695 I UEI.SmartControl: Registering Services Ready callback...
09-07 12:06:35.169  7669  7695 I UEI.SmartControl: Notify client services are ready...
09-07 12:06:35.183  7669  7721 I UEI.SmartControl: Notify AllClients services are ready: 0
09-07 12:06:35.183  7669  7721 D UEI.SmartControl: -----service ready thread exits
,09-07 12:06:35.255  1037  1893 W libprocessgroup: failed to open /acct/uid_10112/pid_6971/cgroup.procs: No such file or directory
,09-07 12:06:35.259  7669  7669 D UEI.SmartControl: Internal service binding...
,09-07 12:06:35.738  7039  7530 D bt_hci_bdroid: cleanup
,09-07 12:06:35.745  7039  7598 I bt_lpm  : LPM is already off!!!
09-07 12:06:35.746  7039  7622 I bt_userial_mct: exiting userial_read_thread
09-07 12:06:35.746  7039  7622 D bt_userial_mct: Leaving userial_evt_read_thread()
09-07 12:06:35.748  7039  7596 W bt-btif : ag scb idx 1 not allocated
09-07 12:06:35.748  7039  7596 E bt-btif : BTA AG is already disabled, ignoring ...
09-07 12:06:35.748  7039  7596 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-07 12:06:35.748  7039  7596 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-07 12:06:35.748  7039  7596 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-07 12:06:35.748  7039  7596 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-07 12:06:35.748  7039  7596 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-07 12:06:35.748  7039  7596 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-07 12:06:35.748  7039  7596 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-07 12:06:35.749  7039  7596 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-07 12:06:35.749  7039  7596 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-07 12:06:35.749  7039  7596 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-07 12:06:35.749  7039  7596 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-07 12:06:35.749  7039  7596 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-07 12:06:35.749  7039  7596 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-07 12:06:35.749  7039  7596 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-07 12:06:35.749  7039  7596 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-07 12:06:35.749  7039  7596 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-07 12:06:35.749  7039  7596 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-07 12:06:35.749  7039  7596 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-07 12:06:35.749  7039  7596 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-07 12:06:35.754  7039  7530 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-07 12:06:35.754  7039  7598 I bt_vendor: hw_epilog_process
09-07 12:06:35.755  7039  7530 D bt_hci_bdroid: cleanup Finalizing cleanup
09-07 12:06:35.755  7039  7530 D bt_userial_mct: userial_close
09-07 12:06:35.755  7039  7530 E bt_userial_mct: pthread_join() FAILED result:3
09-07 12:06:35.755  7039  7530 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
09-07 12:06:35.762  7039  7530 D bt_hci_bdroid: set_power 0
09-07 12:06:35.762  7039  7530 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-07 12:06:35.762  7039  7530 I bt_vendor: bluetooth satus is on
09-07 12:06:35.763  7039  7530 I bt_vendor: bt-vendor : resetting BT status
09-07 12:06:35.763  7039  7530 I bt_vendor: Starting hciattach daemon
09-07 12:06:35.763  7039  7530 I bt_vendor: try to set false
,09-07 12:06:35.768  7039  7530 I bt_vendor: Starting hciattach daemon
09-07 12:06:35.769  7039  7530 I bt_vendor: try to set false
09-07 12:06:35.771  7039  7530 I bt_vendor: cleanup
09-07 12:06:35.772  7039  7596 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-07 12:06:35.772  7039  7530 I GKI_LINUX: GKI_exit_task 0 done
09-07 12:06:35.772  7039  7530 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
09-07 12:06:35.774  7039  7526 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-07 12:06:35.779  7039  7039 D HeadsetService: Received stop request...Stopping profile...
,09-07 12:06:35.785  7039  7526 D BluetoothAdapterState: Stopping profile services that were post enabled
09-07 12:06:35.786  7039  7039 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-07 12:06:35.786  7039  7039 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-07 12:06:35.786  7039  7039 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c5cfed7
09-07 12:06:35.787  7039  7566 D HeadsetStateMachine: Exit Disconnected: -1
09-07 12:06:35.792  1840  1840 D BluetoothHeadset: Proxy object disconnected
09-07 12:06:35.792  1840  1840 D BluetoothHeadset: Proxy object disconnected
09-07 12:06:35.792  1840  1840 D BluetoothHeadset: Proxy object disconnected
,09-07 12:06:35.796  1037  1037 D BluetoothHeadset: Proxy object disconnected
09-07 12:06:35.796  1037  1037 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-07 12:06:35.797  7039  7039 D A2dpService: Received stop request...Stopping profile...
09-07 12:06:35.798  7039  7587 D A2dpStateMachine: Exit Disconnected: -1
09-07 12:06:35.800  7039  7039 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
09-07 12:06:35.801  7039  7039 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
09-07 12:06:35.801  7039  7039 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
09-07 12:06:35.801  7039  7039 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c5cfed7
09-07 12:06:35.804  1037  1037 D BluetoothA2dp: Proxy object disconnected
09-07 12:06:35.804  1037  1037 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,09-07 12:06:35.806  7039  7039 D HidService: Received stop request...Stopping profile...
09-07 12:06:35.806  7039  7039 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c5cfed7
09-07 12:06:35.809  7039  7039 D HealthService: Received stop request...Stopping profile...
09-07 12:06:35.809  7039  7039 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c5cfed7
09-07 12:06:35.813  7039  7039 D PanService: Received stop request...Stopping profile...
09-07 12:06:35.813  7039  7039 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c5cfed7
09-07 12:06:35.815  7039  7039 D BtGatt.DebugUtils: handleDebugAction() action=null
09-07 12:06:35.816  7039  7039 D BtGatt.GattService: Received stop request...Stopping profile...
09-07 12:06:35.816  7039  7039 D BtGatt.GattService: stop()
09-07 12:06:35.816  7039  7039 D BtGatt.AdvertiseManager: advertise clients cleared
,09-07 12:06:35.819  7039  7039 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c5cfed7
09-07 12:06:35.821  7039  7039 D BluetoothMapService: Received stop request...Stopping profile...
09-07 12:06:35.821  7039  7039 D BluetoothMapService: stop()
09-07 12:06:35.821  7039  7039 D BluetoothMapEmailAppObserver: deinitObservers()
09-07 12:06:35.821  7039  7039 D BluetoothMapEmailAppObserver: removeReceiver()
09-07 12:06:35.823  7039  7039 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c5cfed7
09-07 12:06:35.824  7039  7039 D HeadsetStateMachine: Unbinding service...
09-07 12:06:35.826  7039  7039 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-07 12:06:35.826  7039  7039 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-07 12:06:35.826  7039  7039 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-07 12:06:35.826  7039  7039 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-07 12:06:35.826  7039  7039 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-07 12:06:35.826  7039  7039 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-07 12:06:35.826  7039  7039 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-07 12:06:35.826  7039  7039 I BluetoothA2dpServiceJni: cleanupNative
09-07 12:06:35.827  7039  7588 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-07 12:06:35.827  7039  7039 I GKI_LINUX: GKI_exit_task 2 done
09-07 12:06:35.827  7039  7039 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-07 12:06:35.828  7039  7039 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-07 12:06:35.828  7039  7039 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-07 12:06:35.828  7039  7039 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,09-07 12:06:35.831  7039  7039 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-07 12:06:35.831  7039  7039 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-07 12:06:35.831  7039  7039 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-07 12:06:35.831  7039  7039 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-07 12:06:35.833  7039  7039 V BluetoothMapService: Handler(): got msg=4
09-07 12:06:35.833  7039  7039 D BluetoothMapService: MAP Service closeService in
09-07 12:06:35.833  7039  7039 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-07 12:06:35.833  7039  7039 V BluetoothMapService: MAP Service closeService out
09-07 12:06:35.836  7039  7526 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
09-07 12:06:35.836  7039  7526 D BluetoothAdapterProperties: Setting state to 10
09-07 12:06:35.836  7039  7526 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-07 12:06:35.837  7039  7039 D BluetoothMapService: cleanup()
09-07 12:06:35.837  7039  7039 D BluetoothMapService: MAP Service closeService in
09-07 12:06:35.837  7039  7039 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-07 12:06:35.837  7039  7039 V BluetoothMapService: MAP Service closeService out
09-07 12:06:35.838  1037  1119 D BluetoothManagerService: Message: 60
09-07 12:06:35.838  1037  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
09-07 12:06:35.838  1037  1119 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
09-07 12:06:35.838  1037  1119 D BluetoothA2dp: onBluetoothStateChange: up=false
09-07 12:06:35.839  7039  7526 I BluetoothAdapterState: Entering OffState
09-07 12:06:35.841  6889  6906 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-07 12:06:35.845  1037  1119 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 12:06:35.845  6889  6906 D BluetoothPbap: onBluetoothStateChange: up=false
09-07 12:06:35.847  6889  6906 D BluetoothPan: onBluetoothStateChange on: false
09-07 12:06:35.848  1840  1856 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 12:06:35.848  1840  1855 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 12:06:35.849  6889  6906 D BluetoothA2dp: onBluetoothStateChange: up=false
09-07 12:06:35.849  6889  6906 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 12:06:35.850  6889  6906 D BluetoothMap: onBluetoothStateChange: up=false
09-07 12:06:35.851  1840  2417 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 12:06:35.851  1037  1119 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
09-07 12:06:35.852  1037  1119 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
09-07 12:06:35.854  1037  1119 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
09-07 12:06:35.854  1037  1119 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
09-07 12:06:35.854  1037  1119 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@7cb9dda mBinding = false
,09-07 12:06:35.856  1037  1119 D BluetoothManagerService: Sending unbind request.
09-07 12:06:35.861  7039  7530 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
09-07 12:06:35.862  7039  7039 I GKI_LINUX: GKI_exit_task 1 done
09-07 12:06:35.862  7039  7039 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
09-07 12:06:35.863  7039  7039 I BluetoothServiceJni: cleanupNative: return from cleanup
09-07 12:06:35.863  7039  7039 I art     : --- WEIRD: removing null entry 248
09-07 12:06:35.863  7039  7039 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
09-07 12:06:35.863  7039  7039 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
09-07 12:06:35.864  7039  7039 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
09-07 12:06:35.865  1037  1119 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
,09-07 12:06:35.869  7039  7039 I art     : System.exit called, status: 0
09-07 12:06:35.869  7039  7039 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
09-07 12:06:35.888   313  2152 V AudioFlinger: 7039 died, releasing its sessions
09-07 12:06:35.888   313  2152 V AudioFlinger:  pid 1840 @ 0
09-07 12:06:35.888   313  2152 V AudioFlinger:  pid 3161 @ 1
09-07 12:06:35.888   313  2152 V AudioFlinger:  pid 3161 @ 2
,09-07 12:06:35.899  1930  1930 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
09-07 12:06:35.899  1930  2132 D LGBluetoothAPIService: Message: 101
09-07 12:06:35.899  1930  2132 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
09-07 12:06:35.900  1930  2132 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
09-07 12:06:35.900  1930  2132 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
09-07 12:06:35.900  6889  6889 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
,09-07 12:06:35.952  1037  1564 I ActivityManager: Process com.android.bluetooth (pid 7039) has died
,09-07 12:06:35.953  1037  1564 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 1000ms
09-07 12:06:35.953  1037  1564 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 11000ms
,09-07 12:06:35.961  1930  1930 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-07 12:06:35.961  1930  2132 D LGBluetoothAPIService: Message: 2
09-07 12:06:35.961  1930  2132 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
09-07 12:06:35.963  1592  1592 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-07 12:06:35.966  6798  6798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 12:06:35.966  6889  6889 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
09-07 12:06:35.966  6889  6889 D LGBluetoothEventManager: [BTUI] clear device connection state
09-07 12:06:35.967  6798  6798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 12:06:35.973  6889  6889 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-07 12:06:35.976  1592  1592 D BluetoothAdapter: 897859369: getState() :  mService = null. Returning STATE_OFF
09-07 12:06:35.976  1592  1592 D BluetoothAdapter: 897859369: getState() :  mService = null. Returning STATE_OFF
09-07 12:06:36.059  1037  1964 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7753 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,09-07 12:06:36.062  6889  6889 D DockEventReceiver: finishStartingService: stopping service
,09-07 12:06:36.147  7753  7753 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
09-07 12:06:36.148  7753  7753 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-07 12:06:36.148  7753  7753 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
09-07 12:06:36.149  7753  7753 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-07 12:06:36.170  7753  7753 D BluetoothAdapterApp: Loading JNI Library
,09-07 12:06:36.207  7753  7753 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@399992df Instance Count = 1
,09-07 12:06:36.214  7753  7753 D BluetoothAdapterApp: onCreate
09-07 12:06:36.240  7753  7753 D ProfileConfigQcom: [BTUI] HeadsetService is supported
09-07 12:06:36.240  7753  7753 D ProfileConfigQcom: Adding HeadsetService
09-07 12:06:36.241  7753  7753 D ProfileConfigQcom: [BTUI] A2dpService is supported
09-07 12:06:36.241  7753  7753 D ProfileConfigQcom: Adding A2dpService
09-07 12:06:36.241  7753  7753 D ProfileConfigQcom: [BTUI] HidService is supported
09-07 12:06:36.241  7753  7753 D ProfileConfigQcom: Adding HidService
09-07 12:06:36.242  7753  7753 D ProfileConfigQcom: [BTUI] HealthService is supported
09-07 12:06:36.242  7753  7753 D ProfileConfigQcom: Adding HealthService
,09-07 12:06:36.242  7753  7753 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
09-07 12:06:36.244  7753  7753 D ProfileConfigQcom: [BTUI] PanService is supported
09-07 12:06:36.244  7753  7753 D ProfileConfigQcom: Adding PanService
09-07 12:06:36.244  7753  7753 D ProfileConfigQcom: [BTUI] GattService is supported
09-07 12:06:36.244  7753  7753 D ProfileConfigQcom: Adding GattService
09-07 12:06:36.245  7753  7753 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
09-07 12:06:36.245  7753  7753 D ProfileConfigQcom: Adding BluetoothMapService
09-07 12:06:36.245  7753  7753 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
09-07 12:06:36.249  7753  7753 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-07 12:06:36.250  7753  7753 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-07 12:06:36.251  7753  7753 V BluetoothPbapReceiver: ***********state = 10
09-07 12:06:36.253  7753  7753 V LGMDMManagerInternal: Create singleton instance
09-07 12:06:36.341  7753  7753 D LGBluetoothAPIServer: [BTUI] onCreate()
09-07 12:06:36.341  7753  7753 D LGBluetoothAPIServer: [BTUI] onBind()
,09-07 12:06:36.346  2163  2163 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-07 12:06:36.347  1930  1930 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
09-07 12:06:36.347  1930  2132 D LGBluetoothAPIService: Message: 100
09-07 12:06:36.347  1930  2132 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
09-07 12:06:36.366  6889  6889 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,09-07 12:06:36.371  6889  6889 D BluetoothPermissionRequest: onReceive
09-07 12:06:36.373  6889  6889 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-07 12:06:36.373  6889  6889 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
09-07 12:06:36.375  6889  6889 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-07 12:06:36.379  7753  7753 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,09-07 12:06:36.385  7753  7753 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-07 12:06:36.388  7753  7753 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-07 12:06:36.388  7753  7753 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-07 12:06:36.388  7753  7753 V BluetoothSapReceiver: SapReceiver onReceive 
09-07 12:06:36.389  7753  7753 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-07 12:06:36.390  7753  7753 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
09-07 12:06:36.392  6988  6988 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,09-07 12:06:37.811  6798  6867 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 12:06:37.811  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 12:06:37.920  1592  1592 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,09-07 12:06:37.982  1037  1427 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-07 12:06:38.018  1037  1100 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7782 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,09-07 12:06:38.029  1592  1592 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
09-07 12:06:38.030  1592  1592 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,09-07 12:06:38.062  2021  2021 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,09-07 12:06:38.086  2021  2021 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,09-07 12:06:38.103  1037  1037 D administrator: Handling package changes for user 0
,09-07 12:06:38.119  7782  7782 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-07 12:06:38.210  7782  7782 D LgDataFeature: LgDataFeature() Constructor: none
09-07 12:06:38.210  7782  7782 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-07 12:06:38.213  1037  1037 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
,09-07 12:06:38.213  1037  1037 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
09-07 12:06:38.253  1037  1099 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-07 12:06:38.257  1037  1099 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,09-07 12:06:38.266  2021  2021 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,09-07 12:06:38.267  2488  2488 V GmsNetworkLocationProvi: DISABLE
09-07 12:06:38.297  2488  2488 E GCoreFlp: Bound FusedProviderService with LocationManager
,09-07 12:06:38.356  7782  7828 I Babel   : MmsConfig: mnc/mcc: 0/0
09-07 12:06:38.356  7782  7828 I Babel   : MmsConfig.loadMmsSettings
09-07 12:06:38.362  7782  7828 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,09-07 12:06:38.362  7782  7828 I Babel   : MmsConfig.loadFromDatabase
,09-07 12:06:38.377  7782  7828 E Babel   : canonicalizeMccMnc: invalid mccmnc 
09-07 12:06:38.377  7782  7828 I Babel   : MmsConfig.loadFromResources
09-07 12:06:38.380  7782  7828 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
09-07 12:06:38.380  7782  7828 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
09-07 12:06:38.388  7782  7782 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-07 12:06:38.409  7782  7826 W AudioCapabilities: Unsupported mime audio/evrc
09-07 12:06:38.413  7782  7826 W AudioCapabilities: Unsupported mime audio/qcelp
09-07 12:06:38.414  1805  7830 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
09-07 12:06:38.414  1805  7830 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
09-07 12:06:38.415  7782  7826 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-07 12:06:38.416  7105  7105 I AppUp4:CustModeStarterReceiver: onReceive
09-07 12:06:38.419  7105  7105 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@3e0cc071
09-07 12:06:38.419  7105  7105 D AppUp4:CustFacade: isCustomizationCompleted : false
09-07 12:06:38.419  7105  7105 D AppUp4:CustFacade: isPhone : true
09-07 12:06:38.420  7105  7105 D AppUp4:CustModeStarterReceiver: begin check event
09-07 12:06:38.420  7105  7105 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
09-07 12:06:38.426  1805  5244 I Icing   : updateResources: need to parse e{com.google.android.gms}
,09-07 12:06:38.444  7782  7826 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,09-07 12:06:38.447  7782  7826 W AudioCapabilities: Unsupported mime audio/qcelp
09-07 12:06:38.448  7782  7826 W AudioCapabilities: Unsupported mime audio/evrc
09-07 12:06:38.458  1037  1964 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7833 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,09-07 12:06:38.461  1037  1964 I ActivityManager: Killing 6938:com.lge.sync/1000 (adj 15): empty #17
09-07 12:06:38.470  1037  1533 D WifiService: Client connection lost with reason: 4
,09-07 12:06:38.475  7782  7826 W VideoCapabilities: Unsupported mime video/x-ms-wmv
09-07 12:06:38.478  7782  7826 W VideoCapabilities: Unsupported mime video/divx
09-07 12:06:38.480  7782  7826 W VideoCapabilities: Unsupported mime video/divx311
,09-07 12:06:38.482  7782  7826 W VideoCapabilities: Unsupported mime video/divx4
09-07 12:06:38.486  7782  7826 W VideoCapabilities: Unsupported mime video/mp4v-esdp
09-07 12:06:38.518  7782  7826 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-07 12:06:38.520  1037  2039 W libprocessgroup: failed to open /acct/uid_1000/pid_6938/cgroup.procs: No such file or directory
09-07 12:06:38.524  1037  1099 D LocationProviderProxy: applying state to connected service
09-07 12:06:38.525  7782  7826 W AudioCapabilities: Unsupported mime audio/eac3
09-07 12:06:38.526  7782  7826 W AudioCapabilities: Unsupported mime audio/ac3
09-07 12:06:38.528  7782  7826 W AudioCapabilities: Unsupported mime audio/g726
09-07 12:06:38.529  7782  7826 W AudioCapabilities: Unsupported mime audio/wma-voice
09-07 12:06:38.530  7782  7826 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,09-07 12:06:38.531  7782  7826 W AudioCapabilities: Unsupported mime audio/adpcm
09-07 12:06:38.533  7782  7826 W VideoCapabilities: Unsupported mime video/theora
09-07 12:06:38.535  7782  7826 W VideoCapabilities: Unsupported mime video/mjpg
09-07 12:06:38.556  7833  7833 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-07 12:06:38.556  7833  7833 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-07 12:06:38.556  7833  7833 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
09-07 12:06:38.557  7833  7833 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
09-07 12:06:38.557  7833  7833 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,09-07 12:06:38.627  7833  7833 I SystemConfig: BUILD Country: EU
09-07 12:06:38.628  7833  7833 I SystemConfig: BUILD Operator: OPEN
,09-07 12:06:38.670  1037  1874 I ActivityManager: Killing 7132:com.lge.email/u0a23 (adj 15): empty #17
,09-07 12:06:38.784  1037  1964 W libprocessgroup: failed to open /acct/uid_10023/pid_7132/cgroup.procs: No such file or directory
,09-07 12:06:38.795  7833  7851 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
09-07 12:06:38.795  7833  7851 I SystemConfig: existFile = false
09-07 12:06:38.795  7833  7851 I SystemConfig: canReadFile = false
09-07 12:06:38.796  7833  7851 I SystemConfig: systemFeature RCS result false
09-07 12:06:38.796  7833  7851 D SystemConfig: refreshRcsSupport() :false
09-07 12:06:38.866  1037  1929 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7856 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,09-07 12:06:38.873  1037  1534 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
,09-07 12:06:38.945  7856  7856 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-07 12:06:38.945  7856  7856 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-07 12:06:38.945  7856  7856 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
09-07 12:06:38.946  7856  7856 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,09-07 12:06:39.057  7856  7856 I AppConfig: Total System Memory = 2995761152
,09-07 12:06:39.070  7856  7856 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
09-07 12:06:39.154  1037  1911 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7878 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-07 12:06:39.159  1037  1911 I ActivityManager: Killing 7008:com.lge.formmanager/u0a26 (adj 15): empty #17
09-07 12:06:39.215  1037  1774 W libprocessgroup: failed to open /acct/uid_10026/pid_7008/cgroup.procs: No such file or directory
,09-07 12:06:39.398  7878  7878 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,09-07 12:06:39.485  7878  7878 D LgDataFeature: LgDataFeature() Constructor: none
,09-07 12:06:39.485  7878  7878 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-07 12:06:39.529  7878  7878 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,09-07 12:06:39.549  7878  7878 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,09-07 12:06:39.550  7878  7878 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,09-07 12:06:39.567  7878  7878 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-07 12:06:39.567  7878  7878 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,09-07 12:06:39.585  1037  1694 I ActivityManager: Killing 6497:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,09-07 12:06:39.745  1037  1911 W libprocessgroup: failed to open /acct/uid_1000/pid_6497/cgroup.procs: No such file or directory,
,09-07 12:06:39.768  3290  7293 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,09-07 12:06:39.770  5062  7933 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
09-07 12:06:39.775  3290  7293 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@34bc5f45 on behalf of 7878
09-07 12:06:39.821  1037  1774 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7934 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,09-07 12:06:39.859  7878  7878 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,09-07 12:06:39.886  7878  7878 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
09-07 12:06:39.956  7934  7934 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,09-07 12:06:39.978  7934  7934 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
09-07 12:06:39.978  7934  7934 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
,09-07 12:06:39.978  7934  7934 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
09-07 12:06:39.978  7934  7934 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
09-07 12:06:39.978  7934  7934 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
09-07 12:06:39.978  7934  7934 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,09-07 12:06:39.994  1037  1874 I ActivityManager: Killing 7172:com.google.android.setupwizard/u0a46 (adj 15): empty #17
09-07 12:06:40.077  1037  1965 W libprocessgroup: failed to open /acct/uid_10046/pid_7172/cgroup.procs: No such file or directory
,09-07 12:06:40.125  7669  7723 D UEI.SmartControl: Internal timer expired: 1
09-07 12:06:40.126  7669  7723 D UEI.SmartControl: unbind internal service
,09-07 12:06:40.133  7669  7669 D UEI.SmartControl: Service.onUnbind: IControl
09-07 12:06:40.134  7669  7669 D UEI.SmartControl: Service.onDestroy
09-07 12:06:40.134  7669  7669 D UEI.SmartControl: Lock is in USE false
09-07 12:06:40.135  7669  7669 D UEI.SmartControl: unbind internal service
09-07 12:06:40.136  7669  7669 D serial_port: close(fd = 25)
09-07 12:06:40.140  7669  7669 I UEI.SmartControl: Serial port is closed.
09-07 12:06:40.140  7669  7669 I UEI.SmartControl: Serial port is closed.
09-07 12:06:40.142  7669  7669 D UEI.SmartControl: Blaster closed
09-07 12:06:40.142  7669  7669 D UEI.SmartControl: Shut down QS...
09-07 12:06:40.143  7669  7669 D UEI.SmartControl: Stopping QS lib
09-07 12:06:40.144  7669  7669 D UEI.SmartControl: QS lib stop result = true
09-07 12:06:40.144  7669  7669 D UEI.SmartControl: Stopped QS lib
09-07 12:06:40.144  7669  7669 D UEI.SmartControl: Stopped file observer...
09-07 12:06:40.144  7669  7669 D UEI.SmartControl: QS shutdown complete
,09-07 12:06:40.329  1037  2002 V SIM_STK : Menu title from STK is T-Mobile
,09-07 12:06:40.366  5062  7933 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 596 ms] updated apps [took 596 ms] 
,09-07 12:06:40.827  6798  6867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 12:06:40.828  6798  6867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@242079db added. We now have 6 listener(s)
09-07 12:06:40.828  6798  6867 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 12:06:40.836  6798  6867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 12:06:40.836  6798  6867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2156cc78 added. We now have 7 listener(s)
09-07 12:06:40.836  6798  6867 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 12:06:40.837  6798  6867 I System.out: IsBluetoothEnabled
09-07 12:06:40.838  1037  1929 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 12:06:40.838  1037  1929 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
09-07 12:06:40.839  1037  1119 D BluetoothManagerService: Message: 2
09-07 12:06:40.842  6798  6867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 12:06:40.842  1037  1965 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 12:06:40.843  1037  1965 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,09-07 12:06:40.863  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-07 12:06:40.864  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-07 12:06:40.864  1037  1037 D Ulp_jni : JNI:system_update. Event-4
09-07 12:06:40.865  1037  1119 D BluetoothManagerService: Message: 1
09-07 12:06:40.865  1037  1119 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
09-07 12:06:40.890  1037  1119 D BluetoothManagerService: Message: 20
09-07 12:06:40.890  1037  1119 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d256268:true
,09-07 12:06:40.894  7753  7753 D BluetoothAdapterState: make
09-07 12:06:40.899  7753  7753 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
09-07 12:06:40.899  7753  7753 I bluedroid-qcom: init
09-07 12:06:40.901  7753  7980 I BluetoothAdapterState: Entering OffState
09-07 12:06:40.901  7753  7753 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-07 12:06:40.901  7753  7753 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-07 12:06:40.901  7753  7753 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-07 12:06:40.901  7753  7753 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-07 12:06:40.902  7753  7753 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
09-07 12:06:40.904  7753  7753 I bluedroid-qcom: get_profile_interface socket
09-07 12:06:40.904  7753  7753 I bluedroid-qcom: get_profile_interface map_client
,09-07 12:06:40.908  7753  7984 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
09-07 12:06:40.894  7983  7983 W bdaddr_loader: type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-07 12:06:40.904  7983  7983 W bdaddr_loader: type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-07 12:06:40.916  7753  7984 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
09-07 12:06:40.923  1037  1037 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-07 12:06:40.923  1037  1037 D BluetoothManagerService: Stored Bluetooth name: G3
,09-07 12:06:40.928  7983  7983 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
09-07 12:06:40.928  7983  7983 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
09-07 12:06:40.928  7983  7983 I LGFTMITEM: [GET_FTM][id=8], offset=16384
09-07 12:06:40.930  1037  1037 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
09-07 12:06:40.931  1037  1119 D BluetoothManagerService: Message: 40
09-07 12:06:40.931  1037  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
09-07 12:06:40.932  7753  7768 I bluedroid-qcom: config_hci_snoop_log
09-07 12:06:40.933  1037  1119 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
09-07 12:06:40.933  1037  1119 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
09-07 12:06:40.934  7983  7983 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
09-07 12:06:40.936  7753  7984 D BluetoothAdapterProperties: Name is: G3
,09-07 12:06:40.940  7983  7983 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
09-07 12:06:40.940  7983  7983 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
09-07 12:06:40.946  7753  7980 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
09-07 12:06:40.947  7753  7980 D BluetoothAdapterProperties: Setting state to 11
09-07 12:06:40.947  7753  7980 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-07 12:06:40.948  1037  1119 D BluetoothManagerService: Message: 60
,09-07 12:06:40.948  1037  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
09-07 12:06:40.948  1037  1119 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
,09-07 12:06:40.954  1930  1930 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-07 12:06:40.955  1592  1592 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-07 12:06:40.970  6798  6798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 12:06:40.979  6889  6889 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
09-07 12:06:40.984  7753  7980 I LGBluetoothServiceJni: classInitNative: succeeds
,09-07 12:06:40.989  7753  7753 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-07 12:06:40.989  7753  7753 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-07 12:06:40.989  7753  7753 V BluetoothPbapReceiver: ***********state = 11
09-07 12:06:40.994  7753  7980 D BluetoothBondStateMachine: make
09-07 12:06:40.994  2163  2163 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-07 12:06:40.997  7753  7980 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a8833c4
09-07 12:06:40.997  7753  7980 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
09-07 12:06:40.997  7753  7980 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a8833c4
09-07 12:06:40.998  7753  7980 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
09-07 12:06:40.998  7753  7980 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
09-07 12:06:40.999  7753  7994 I BluetoothBondStateMachine: StableState(): Entering Off State
09-07 12:06:41.006  7753  7980 E BluetoothAdapterService: File transfer profiles supported!!
,09-07 12:06:41.012  6889  6889 D BluetoothPermissionRequest: onReceive
09-07 12:06:41.019  7753  7980 E BluetoothAdapterService: File transfer profiles supported!!
,09-07 12:06:41.020  7753  7753 D HeadsetService: Received start request. Starting profile...
09-07 12:06:41.021  7753  7753 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
09-07 12:06:41.021  7753  7753 D LGBluetoothHfpAdapter: Version 1.6
09-07 12:06:41.027  6889  6889 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-07 12:06:41.027  7753  7980 E BluetoothAdapterService: File transfer profiles supported!!
09-07 12:06:41.030  7753  7753 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,09-07 12:06:41.034  7753  7753 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-07 12:06:41.034  7753  7980 E BluetoothAdapterService: File transfer profiles supported!!
09-07 12:06:41.035  7753  7753 D HeadsetStateMachine: make
09-07 12:06:41.052  7753  7980 E BluetoothAdapterService: File transfer profiles supported!!
,09-07 12:06:41.062  7753  7980 E BluetoothAdapterService: File transfer profiles supported!!
09-07 12:06:41.074  7753  7980 E BluetoothAdapterService: File transfer profiles supported!!
,09-07 12:06:41.076  7753  7753 D LgDataFeature: LgDataFeature() Constructor: none
09-07 12:06:41.077  7753  7753 D LgDataFeature: LgDataFeature() Constructor Done, null
09-07 12:06:41.082  7753  7753 D HeadsetStateMachine: max_hf_connections = 1
09-07 12:06:41.083  7753  7753 I bluedroid-qcom: get_profile_interface handsfree
09-07 12:06:41.085  7753  7753 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
09-07 12:06:41.086   313  1370 V AudioPolicyService: registerClient() client 0xb558ace0, uid 1002
09-07 12:06:41.086   313  2153 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
09-07 12:06:41.086   313  2153 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-07 12:06:41.086   313  2153 V AudioPolicyManagerEx: getOutput() returns output 2
09-07 12:06:41.086  7753  7753 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
,09-07 12:06:41.087   313   313 V AudioFlinger: registerClient() client 0xb5581778, pid 7753
09-07 12:06:41.087   313  1366 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-07 12:06:41.087   313  1366 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-07 12:06:41.087   313  1365 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-07 12:06:41.087   313  1365 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-07 12:06:41.088  1592  2083 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-07 12:06:41.088  1592  2083 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-07 12:06:41.088  1592  2083 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-07 12:06:41.088  1592  2083 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-07 12:06:41.088  1840  2444 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-07 12:06:41.088  1840  2444 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-07 12:06:41.088  1840  2444 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-07 12:06:41.088  1840  2444 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-07 12:06:41.088  3161  3176 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-07 12:06:41.088  3161  3176 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-07 12:06:41.088  3161  3176 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-07 12:06:41.088  3161  3176 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-07 12:06:41.088  7753  7768 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-07 12:06:41.088  1037  1774 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-07 12:06:41.088  1037  1774 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-07 12:06:41.088  1037  1774 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-07 12:06:41.088  1037  1774 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-07 12:06:41.088  7753  7753 V ToneGenerator: Create Track: 0xb4928a80
09-07 12:06:41.088  7753  7753 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
09-07 12:06:41.089  7753  7753 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
09-07 12:06:41.089  7753  7768 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
09-07 12:06:41.089   313  2152 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-07 12:06:41.089  7753  7768 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-07 12:06:41.089   313  2152 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
09-07 12:06:41.089   313  2152 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-07 12:06:41.089  7753  7768 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
09-07 12:06:41.089   313  2152 V AudioPolicyManagerEx: getOutput() returns output 2
09-07 12:06:41.089   313  1370 I AudioFlinger: isAudioPlaybackHookOn() false
09-07 12:06:41.089   313  2153 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-07 12:06:41.089   313  2153 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
09-07 12:06:41.089   313  2153 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-07 12:06:41.089   313  2153 V AudioPolicyManagerEx: getOutput() returns output 2
09-07 12:06:41.090  7753  7753 V AudioSystem: getLatency() output 2, latency 50
09-07 12:06:41.090  7753  7753 V AudioSystem: getFrameCount() output 2, frameCount 960
09-07 12:06:41.090  7753  7753 V AudioTrack: createTrack_l() output 2 afLatency 50
09-07 12:06:41.090   313   313 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-07 12,:06:41.090   313   313 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-07 12:06:41.090   313   313 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-07 12:06:41.090   313   313 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-07 12:06:41.090   313   313 V AudioFlinger: createTrack() lSessionId: 23
09-07 12:06:41.091  7753  7753 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
09-07 12:06:41.091   313   313 V AudioFlinger: acquiring 23 from 7753, for 7753
09-07 12:06:41.091   313   313 V AudioFlinger:  added new entry for 23
09-07 12:06:41.091  7753  7753 V ToneGenerator: ToneGenerator INIT OK, time: 195319
09-07 12:06:41.091  7753  7753 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a8833c4
09-07 12:06:41.092  7753  8001 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
09-07 12:06:41.092  7753  8001 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-07 12:06:41.093  7753  8001 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-07 12:06:41.093  7753  8001 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
09-07 12:06:41.093  7753  7753 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a8833c4
09-07 12:06:41.094   313  1371 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7753
09-07 12:06:41.094   313  1371 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
09-07 12:06:41.094   313  1371 V voice   : voice_set_parameters: enter: bt_samplerate=8000
09-07 12:06:41.094   313  1371 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
09-07 12:06:41.094   313  1371 V compress_voip: voice_extn_compress_voip_set_parameters: exit
09-07 12:06:41.094   313  1371 V voice   : voice_set_parameters: exit with code(0)
09-07 12:06:41.094   313  1371 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
09-07 12:06:41.094   313  1371 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
09-07 12:06:41.094   313  1371 V msm8974_platform: platform_set_parameters: exit with code(0)
09-07 12:06:41.094   313  1371 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
09-07 12:06:41.094   313  1371 V audio_hw_primary: adev_set_parameters: exit with code(0)
09-07 12:06:41.094   313  1371 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
09-07 12:06:41.095  7753  8001 V ToneGenerator: ToneGenerator destructor
09-07 12:06:41.095  7753  8001 V ToneGenerator: stopTone
09-07 12:06:41.095  7753  8001 V ToneGenerator: Delete Track: 0xb4928a80
09-07 12:06:41.095  7753  7753 D A2dpService: Received start request. Starting profile...
09-07 12:06:41.096  7753  8001 V AudioTrack: ~AudioTrack, releasing session id from 7753 on behalf of 7753
09-07 12:06:41.096   313  2153 V AudioPolicyService: AudioCommandThread() adding release output 2
09-07 12:06:41.096   313  2153 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
09-07 12:06:41.096   313   313 V AudioFlinger: releasing 23 from 7753 for 7753
09-07 12:06:41.096   313   313 V AudioFlinger:  decremented refcount to 0
09-07 12:06:41.096   313  1273 V AudioPolicyService: AudioCommandThread() waking up
09-07 12:06:41.096   313   313 V AudioFlinger: purging stale effects
09-07 12:06:41.096   313  1273 V AudioPolicyService: AudioCommandThread() processing release output 2
09-07 12:06:41.096   313  1273 V AudioPolicyManager: releaseOutput() 2
09-07 12:06:41.096   313  1273 V AudioPolicyService: AudioCommandThread() going to sleep
09-07 12:06:41.096   313  2153 V AudioFlinger: PlaybackThread::Track destructor
09-07 12:06:41.096   313  2153 V AudioFlinger: removeClient_l() pid 7753, calling pid 313
09-07 12:06:41.096  7753  7753 I BluetoothAvrcpServiceJni: classIni,tNative: succeeds
09-07 12:06:41.097  7753  7753 V Avrcp   : make
09-07 12:06:41.098  7753  7753 D Avrcp   : [BTUI] Use Native AVRCP : init jni
09-07 12:06:41.098  7753  7753 I bluedroid-qcom: get_profile_interface avrcp
09-07 12:06:41.098  1037  1053 W Process : Unable to open /proc/8003/status
09-07 12:06:41.102  7753  7980 V LGMDMManager: Create singleton instance
09-07 12:06:41.104  7753  7980 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
09-07 12:06:41.110  7753  7753 V AudioManager: registerRemoteController: size of Media player list: 0
09-07 12:06:41.113  7753  7753 E AudioManager: No RCC entry present to update
09-07 12:06:41.113  7753  7753 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-07 12:06:41.117  7753  7753 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
09-07 12:06:41.119  7753  7753 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
09-07 12:06:41.119  7753  7753 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
09-07 12:06:41.124  7753  7753 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,09-07 12:06:41.254  1037  1965 V SIM_STK : Menu title from STK is T-Mobile
09-07 12:06:41.254  1037  1965 V SIM_STK : Menu title from STK is T-Mobile
,09-07 12:06:41.370  1037  1052 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,09-07 12:06:41.380  7753  7753 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
09-07 12:06:41.385  7753  7753 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-07 12:06:41.386  7753  7753 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-07 12:06:41.386  7753  7753 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-07 12:06:41.386  7753  7753 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-07 12:06:41.388  7753  7753 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-07 12:06:41.388  7753  7753 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-07 12:06:41.389  7753  7753 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-07 12:06:41.389  7753  7753 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
,09-07 12:06:41.389  7753  7753 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-07 12:06:41.389  7753  7753 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-07 12:06:41.391  7753  7753 I BluetoothA2dpServiceJni: classInitNative
09-07 12:06:41.391  7753  7753 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-07 12:06:41.392  7753  7753 D A2dpStateMachine: make
09-07 12:06:41.397  7753  7753 I bluedroid-qcom: get_profile_interface a2dp
09-07 12:06:41.399  7753  8015 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
09-07 12:06:41.406  7753  7753 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
09-07 12:06:41.406  7753  7753 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
09-07 12:06:41.407  7753  7753 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a8833c4
09-07 12:06:41.408  7753  7753 I BluetoothHidServiceJni: classInitNative: succeeds
09-07 12:06:41.408  7753  8014 D A2dpStateMachine: Enter Disconnected: -2
09-07 12:06:41.410  7753  7753 D HidService: Received start request. Starting profile...
09-07 12:06:41.410  7753  7753 I bluedroid-qcom: get_profile_interface hidhost
09-07 12:06:41.410  7753  7753 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a8833c4
09-07 12:06:41.411  7753  7753 I BluetoothHealthServiceJni: classInitNative: succeeds
09-07 12:06:41.413  7753  7753 D HealthService: Received start request. Starting profile...
09-07 12:06:41.415  7753  7753 I bluedroid-qcom: get_profile_interface health
09-07 12:06:41.415  7753  7753 I LGBluetoothHealthServiceJni: classInitNative: succeeds
09-07 12:06:41.415  7753  7753 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a8833c4
09-07 12:06:41.416  7753  7753 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-07 12:06:41.419  7753  7753 D PanService: Received start request. Starting profile...
09-07 12:06:41.419  7753  7753 D BluetoothPanServiceJni: initializeNative(L110): pan
09-07 12:06:41.419  7753  7753 I bluedroid-qcom: get_profile_interface pan
09-07 12:06:41.427  7753  7753 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
09-07 12:06:41.427  7753  7753 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a8833c4
09-07 12:06:41.429  7753  7753 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
09-07 12:06:41.435  7753  7753 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-07 12:06:41.435  7753  7753 D BtGatt.GattService: Received start request. Starting profile...
09-07 12:06:41.435  7753  7753 D BtGatt.GattService: start()
09-07 12:06:41.435  7753  7753 I bluedroid-qcom: get_profile_interface gatt
09-07 12:06:41.436  7753  7753 D BtGatt.AdvertiseManager: advertise manager created
09-07 12:06:41.443  7753  7753 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a8833c4
09-07 12:06:41.444  7753  7753 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a8833c4
09-07 12:06:41.445  7753  7753 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
09-07 12:06:41.446  7753  7753 V BluetoothMapService: BluetoothMapBinder()
,09-07 12:06:41.447  7753  7753 D BluetoothMapService: Received start request. Starting profile...
09-07 12:06:41.447  7753  7753 D BluetoothMapService: start()
09-07 12:06:41.450  7753  7753 D BluetoothMapEmailSettingsLoader: Found 0 applications
09-07 12:06:41.451  7753  7753 D BluetoothMapEmailAppObserver: createReceiver()
09-07 12:06:41.452  7753  7753 D BluetoothMapEmailAppObserver: initObservers()
09-07 12:06:41.452  7753  7753 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
09-07 12:06:41.462  7753  7753 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a8833c4
,09-07 12:06:41.464  7753  7753 D HeadsetStateMachine: Proxy object connected
09-07 12:06:41.465  7753  7753 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
09-07 12:06:41.465  7753  7753 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
09-07 12:06:41.470  7753  7753 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-07 12:06:41.471  7753  8001 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-07 12:06:41.471  7753  8001 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-07 12:06:41.472  7753  8001 D HeadsetStateMachine: Disconnected process message: 11, size: 0
09-07 12:06:41.476  7753  7753 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,09-07 12:06:41.480  7753  7753 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-07 12:06:41.483  7753  7753 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-07 12:06:41.487  7753  7753 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-07 12:06:41.487  7753  7753 V PanService: [BTUI] SIM Extra State :ABSENT
09-07 12:06:41.491  7753  7753 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,09-07 12:06:41.496  7753  7753 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
09-07 12:06:41.497  7753  7753 V BluetoothMapService: Handler(): got msg=1
09-07 12:06:41.498  7753  7753 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-07 12:06:41.498  7753  7753 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-07 12:06:41.498  7753  7753 V BluetoothSapReceiver: SapReceiver onReceive 
09-07 12:06:41.498  7753  7753 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-07 12:06:41.498  7753  7753 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
09-07 12:06:41.498  7753  7980 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
09-07 12:06:41.498  7753  7980 I bluedroid-qcom: enable
09-07 12:06:41.499  7753  7980 I bt_hci_bdroid: init
09-07 12:06:41.500  7753  7980 I bt_vendor: bt-vendor : init
09-07 12:06:41.501  7753  7980 I bt_vendor: bt-vendor : get_bt_soc_type
09-07 12:06:41.501  7753  7980 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-07 12:06:41.501  7753  7980 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
09-07 12:06:41.501  7753  7980 D bt_userial_mct: userial_init
09-07 12:06:41.501  7753  8022 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
09-07 12:06:41.501  7753  8022 I bt-btu  : btu_task pending for preload complete event
09-07 12:06:41.501  7753  7980 D bt_hci_bdroid: set_power 1
09-07 12:06:41.501  7753  7980 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-07 12:06:41.501  7753  7980 I bt_vendor: Starting hciattach daemon
09-07 12:06:41.501  7753  7980 I bt_vendor: try to set true
09-07 12:06:41.494  8025  8025 W sh      : type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-07 12:06:41.494  8025  8025 W sh      : type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-07 12:06:41.531  8026  8026 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,09-07 12:06:41.600  8032  8032 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,09-07 12:06:41.613  8033  8033 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-07 12:06:41.652  8035  8035 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-07 12:06:41.664  8036  8036 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
09-07 12:06:41.678  8037  8037 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-07 12:06:41.690  8038  8038 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,09-07 12:06:41.712  8040  8040 I libmdmdetect: ESOC framework not supported
09-07 12:06:41.713  8040  8040 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,09-07 12:06:41.724  8040  8040 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
09-07 12:06:41.724  8040  8040 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
09-07 12:06:41.724  8040  8040 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
09-07 12:06:41.724  8040  8040 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
09-07 12:06:41.724  8040  8040 D bthci_qcomm_common: [BTUI]     LE: Class 2
09-07 12:06:41.724  8040  8040 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
09-07 12:06:41.724  8040  8040 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
09-07 12:06:41.762  8040  8041 E QC-QMI  : qmi_client [8040] 15: failed to locate client data
,09-07 12:06:41.767   482   482 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
09-07 12:06:41.768   482   482 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
09-07 12:06:41.806  8042  8042 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,09-07 12:06:41.819  8043  8043 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-07 12:06:41.858  7753  7980 I bt_vendor: bluetooth satus is on
,09-07 12:06:41.859  7753  7980 D bt_hci_bdroid: preload
09-07 12:06:41.859  7753  8024 D bt_userial_mct: userial_open(port:0)
09-07 12:06:41.859  7753  8024 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,09-07 12:06:41.864  7753  8024 I bt_vendor: Done intiailizing UART
,09-07 12:06:41.868  7753  8024 I bt_vendor: Done intiailizing UART
09-07 12:06:41.868  7753  8024 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
09-07 12:06:41.869  7753  8024 I bt_vendor: Bluetooth Firmware and transport layer are initialized
09-07 12:06:41.869  7753  8022 I bt-btu  : btu_task received preload complete event
09-07 12:06:41.871  7753  8022 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
09-07 12:06:41.871  7753  8022 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
09-07 12:06:41.872  7753  8045 D bt_userial_mct: Entering userial_read_thread()
09-07 12:06:41.878  7753  8022 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
,09-07 12:06:41.891  7753  8022 I         : BTE_InitTraceLevels -- TRC_HCI
,09-07 12:06:41.891  7753  8022 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-07 12:06:41.891  7753  8022 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-07 12:06:41.891  7753  8022 I         : BTE_InitTraceLevels -- TRC_AVDT
09-07 12:06:41.891  7753  8022 I         : BTE_InitTraceLevels -- TRC_AVRC
09-07 12:06:41.891  7753  8022 I         : BTE_InitTraceLevels -- TRC_A2D
09-07 12:06:41.891  7753  8022 I         : BTE_InitTraceLevels -- TRC_BNEP
09-07 12:06:41.891  7753  8022 I         : BTE_InitTraceLevels -- TRC_BTM
09-07 12:06:41.891  7753  8022 I         : BTE_InitTraceLevels -- TRC_HID_HOST
09-07 12:06:41.891  7753  8022 I         : BTE_InitTraceLevels -- TRC_GAP
09-07 12:06:41.891  7753  8022 I         : BTE_InitTraceLevels -- TRC_PAN
09-07 12:06:41.891  7753  8022 I         : BTE_InitTraceLevels -- TRC_SDP
09-07 12:06:41.891  7753  8022 I         : BTE_InitTraceLevels -- TRC_GATT
,09-07 12:06:41.891  7753  8022 I         : BTE_InitTraceLevels -- TRC_SMP
,09-07 12:06:41.891  7753  8022 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-07 12:06:41.891  7753  8022 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-07 12:06:42.009  7753  8022 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled,
09-07 12:06:42.009  7753  8022 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01f3061 
09-07 12:06:42.009  7753  8022 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01f3061 ,
,09-07 12:06:42.059  7753  7984 E bt-btif : Calling BTA_HhEnable
09-07 12:06:42.059  7753  7984 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
09-07 12:06:42.060  7753  7984 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,09-07 12:06:42.065  7753  8022 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
09-07 12:06:42.065  7753  8022 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
09-07 12:06:42.065  7753  8022 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
09-07 12:06:42.066  7753  8022 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
09-07 12:06:42.066  7753  8022 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
09-07 12:06:42.068  1037  1037 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-07 12:06:42.069  1037  1037 D BluetoothManagerService: Stored Bluetooth name: G3
09-07 12:06:42.070  7753  7984 D BluetoothAdapterProperties: Name is: G3
09-07 12:06:42.072  7753  7984 D BluetoothAdapterProperties: Scan Mode:20
09-07 12:06:42.073  7753  7984 D BluetoothAdapterProperties: Discoverable Timeout:120
09-07 12:06:42.073  7753  7984 D bt_hci_bdroid: postload
09-07 12:06:42.074  7753  8022 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
,09-07 12:06:42.081  7753  7984 D bte_conf: Device ID record 1 : primary
09-07 12:06:42.081  7753  7984 D bte_conf:   vendorId            = 00c4
09-07 12:06:42.081  7753  7984 D bte_conf:   vendorIdSource      = 0001
09-07 12:06:42.081  7753  7984 D bte_conf:   product             = 13a1
09-07 12:06:42.082  7753  7984 D bte_conf:   version             = 1000
09-07 12:06:42.083  7753  7984 D bte_conf:   clientExecutableURL = 
09-07 12:06:42.083  7753  7984 D bte_conf:   serviceDescription  = 
09-07 12:06:42.083  7753  7984 D bte_conf:   documentationURL    = 
09-07 12:06:42.083  7753  7984 D bte_conf: bte_load_did_conf no section named DID2.
09-07 12:06:42.086  7753  7980 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-07 12:06:42.086  7753  7980 D BluetoothAdapterProperties: ScanMode =  20
09-07 12:06:42.086  7753  7980 D BluetoothAdapterProperties: State =  11
09-07 12:06:42.086  7753  7980 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
09-07 12:06:42.087  7753  7980 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
09-07 12:06:42.087  7753  7980 D BluetoothAdapterProperties: Setting state to 12
09-07 12:06:42.087  7753  7980 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-07 12:06:42.088  7753  7984 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-07 12:06:42.074  8050  8050 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-07 12:06:42.094  1037  1119 D BluetoothManagerService: Message: 60
09-07 12:06:42.094  1037  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
09-07 12:06:42.094  1037  1119 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
09-07 12:06:42.094  1037  1119 D BluetoothA2dp: onBluetoothStateChange: up=true
09-07 12:06:42.095  7753  7980 I BluetoothAdapterState: Entering On State
09-07 12:06:42.084  8050  8050 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-07 12:06:42.104  7753  7980 D LGBluetoothServiceAdapter: [BTUI] OnState
09-07 12:06:42.104  7753  7980 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
09-07 12:06:42.104  7753  7980 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,09-07 12:06:42.108  7753  7980 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
09-07 12:06:42.108  7753  7984 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-07 12:06:42.135  1037  1037 D BluetoothA2dp: Proxy object connected
,09-07 12:06:42.140  7753  7984 D BluetoothAdapterProperties: Discoverable Timeout:120
09-07 12:06:42.140  7753  7984 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
09-07 12:06:42.145  7753  7980 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
09-07 12:06:42.146  7753  8024 D bt_hci_bdroid: Used up Tx Cmd credits
09-07 12:06:42.158  6798  6798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 12:06:42.158  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:06:42.158  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 12:06:42.158  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 12:06:42.158  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 12:06:42.158  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 12:06:42.158  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 12:06:42.158  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 12:06:42.163  6798  6798 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 12:06:42.163  7753  8024 D bt_hci_bdroid: Used up Tx Cmd credits
09-07 12:06:42.193  8055  8055 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,09-07 12:06:42.198  7753  8024 D bt_hci_bdroid: Used up Tx Cmd credits
09-07 12:06:42.198  7753  8024 D bt_hci_bdroid: Used up Tx Cmd credits
09-07 12:06:42.202  7753  8024 D bt_hci_bdroid: Used up Tx Cmd credits
09-07 12:06:42.203  7753  8045 E bt_mct  : hci lib postload completed
09-07 12:06:42.203  6889  6906 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-07 12:06:42.207  1037  1119 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 12:06:42.209  7753  8022 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-07 12:06:42.209  7753  8022 W bt-smp  : Plain text(LSB ~ MSB) = 3e 8a 42 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-07 12:06:42.209  7753  8022 W bt-smp  : Encrypted text(LSB ~ MSB) = be d6 4e 93 f2 7c c4 53 37 5a f5 27 c5 65 20 a1 
09-07 12:06:42.209  7753  8022 W bt-btm  : Stopping oneshot timer
,09-07 12:06:42.212  1037  1037 D BluetoothHeadset: Proxy object connected
09-07 12:06:42.214  6889  6906 D BluetoothPbap: onBluetoothStateChange: up=true
09-07 12:06:42.217  6889  6908 D BluetoothPan: onBluetoothStateChange on: true
09-07 12:06:42.217  6889  6908 D BluetoothPan: onBluetoothStateChange call bindService
09-07 12:06:42.222  1840  1856 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-07 12:06:42.226  7753  8022 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-07 12:06:42.226  7753  8022 W bt-smp  : Plain text(LSB ~ MSB) = ad 24 4d 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-07 12:06:42.226  7753  8022 W bt-smp  : Encrypted text(LSB ~ MSB) = af 0b 26 44 4c b6 09 6e 09 93 26 7f da c8 9c aa 
09-07 12:06:42.226  7753  8022 W bt-btm  : Stopping oneshot timer
09-07 12:06:42.227  1840  1840 D BluetoothHeadset: Proxy object connected
09-07 12:06:42.227  1840  3324 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 12:06:42.228  6889  6889 D BluetoothInputDevice: Proxy object connected
09-07 12:06:42.228  6889  6889 D HidProfile: Bluetooth service connected
09-07 12:06:42.230  1840  1840 D BluetoothHeadset: Proxy object connected
09-07 12:06:42.231  6889  7778 D BluetoothA2dp: onBluetoothStateChange: up=true
09-07 12:06:42.233  6889  6908 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 12:06:42.237  6889  7778 D BluetoothMap: onBluetoothStateChange: up=true
,09-07 12:06:42.241  7753  8022 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-07 12:06:42.241  7753  8022 W bt-smp  : Plain text(LSB ~ MSB) = df 7d 61 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-07 12:06:42.241  7753  8022 W bt-smp  : Encrypted text(LSB ~ MSB) = 52 43 8e f8 f3 65 f3 e2 71 46 56 41 17 b2 51 34 
09-07 12:06:42.241  7753  8022 W bt-btm  : Stopping oneshot timer
09-07 12:06:42.249  1840  2444 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-07 12:06:42.257  6889  6889 D BluetoothPan: BluetoothPAN Proxy object connected
09-07 12:06:42.257  6889  6889 D PanProfile: Bluetooth service connected
09-07 12:06:42.258  1840  1840 D BluetoothHeadset: Proxy object connected
09-07 12:06:42.259  1037  1119 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
09-07 12:06:42.259  1037  1119 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
09-07 12:06:42.260  6889  6889 D BluetoothA2dp: Proxy object connected
09-07 12:06:42.260  6889  6889 D A2dpProfile: Bluetooth service connected
09-07 12:06:42.260  1037  1037 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
09-07 12:06:42.261  1037  1119 D BluetoothManagerService: Message: 40
09-07 12:06:42.261  1037  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
09-07 12:06:42.261  1592  1592 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-07 12:06:42.262  7753  8022 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-07 12:06:42.262  7753  8022 W bt-smp  : Plain text(LSB ~ MSB) = af 43 6a 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-07 12:06:42.262  7753  8022 W bt-smp  : Encrypted text(LSB ~ MSB) = 09 1b 93 bb db 01 3f d4 18 8e 15 0f 97 31 bf d4 
09-07 12:06:42.262  7753  8022 W bt-btm  : Stopping oneshot timer
09-07 12:06:42.265  1930  1930 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,09-07 12:06:42.267  1930  2132 D LGBluetoothAPIService: Message: 1
09-07 12:06:42.267  1930  2132 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
09-07 12:06:42.267  1930  2132 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
09-07 12:06:42.268  6798  6798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 12:06:42.268  1930  2132 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
09-07 12:06:42.270  6889  6889 D BluetoothHeadset: Proxy object connected
09-07 12:06:42.270  6889  6889 D HeadsetProfile: Bluetooth service connected
09-07 12:06:42.271  7753  8022 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-07 12:06:42.271  7753  8022 W bt-smp  : Plain text(LSB ~ MSB) = 09 41 6d 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-07 12:06:42.271  7753  8022 W bt-smp  : Encrypted text(LSB ~ MSB) = 33 71 cb 60 8e 26 49 37 52 ca da ee ab af 8b 2a 
09-07 12:06:42.271  7753  8022 W bt-btm  : Stopping oneshot timer
09-07 12:06:42.273  7753  7753 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-07 12:06:42.273  7753  7753 D BluetoothMapService: STATE_ON
09-07 12:06:42.273  7753  7753 V BluetoothMapService: Handler(): got msg=1
09-07 12:06:42.274  7753  7753 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
09-07 12:06:42.276  6889  6889 D BluetoothMap: Proxy object connected
09-07 12:06:42.276  6889  6889 D MapProfile: Bluetooth service connected
09-07 12:06:42.276  6889  6889 D BluetoothMap: getConnectedDevices()
09-07 12:06:42.276  7753  7768 V BluetoothMapService: getConnectedDevices()
09-07 12:06:42.279  7753  8071 D BluetoothMapMasInstance: MAS initSocket()
09-07 12:06:42.279  7753  8071 D BluetoothMapMasInstance:   masId = 00
09-07 12:06:42.279  7753  8071 D BluetoothMapMasInstance:   msgTypes = 0e
09-07 12:06:42.279  7753  8071 D BluetoothMapMasInstance:   masName = SMS/MMS
09-07 12:06:42.279  7753  8071 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
09-07 12:06:42.280  6889  6889 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
,09-07 12:06:42.282  1037  1964 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 12:06:42.282  6889  6889 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-07 12:06:42.283  7753  8071 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-07 12:06:42.286  7753  7984 D BluetoothAdapterProperties: Scan Mode:21
09-07 12:06:42.286  7753  7984 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
09-07 12:06:42.286  7753  8071 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
09-07 12:06:42.287  7753  8071 V BluetoothMapMasInstance: Succeed to create listening socket 
09-07 12:06:42.287  7753  8071 D BluetoothMapMasInstance: Accepting socket connection...
09-07 12:06:42.289  7753  7753 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a8833c4
09-07 12:06:42.290  7753  7753 V BluetoothPbapService: Pbap Service onCreate
09-07 12:06:42.290  7753  7753 V BluetoothPbapService: Starting PBAP service
09-07 12:06:42.290  6798  6798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 12:06:42.291  7753  7753 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
09-07 12:06:42.291  7753  7753 V BluetoothPbapService: Pbap Service onBind
,09-07 12:06:42.294  7753  7753 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-07 12:06:42.294  7753  7753 V BluetoothPbapService: state: 12
09-07 12:06:42.295  7753  7753 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-07 12:06:42.295  7753  7753 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-07 12:06:42.295  7753  7753 V BluetoothPbapReceiver: ***********state = 12
09-07 12:06:42.296  7753  7753 V BluetoothPbapService: Handler(): got msg=1
09-07 12:06:42.296  7753  7753 V BluetoothPbapService: Pbap Service startRfcommSocketListener
09-07 12:06:42.297  7753  8074 V BluetoothPbapService: Pbap Service initSocket
09-07 12:06:42.299  2163  2163 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-07 12:06:42.299  1037  2002 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 12:06:42.299  2163  2163 D c       : Getting all permits...
09-07 12:06:42.299  2163  2163 D a       : Opening database...
09-07 12:06:42.302  6889  6889 D DockEventReceiver: finishStartingService: stopping service
09-07 12:06:42.302  2163  2163 D a       : Opening database auth.proximity.permit_store...
09-07 12:06:42.303  6889  6889 D BluetoothPbap: Proxy object connected
09-07 12:06:42.303  2163  2163 D a       : Closing database...
09-07 12:06:42.303  6889  6889 D PbapServerProfile: Bluetooth service connected
09-07 12:06:42.303  7753  8074 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 12:06:42.307  7753  8074 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
09-07 12:06:42.307  7753  8074 V BluetoothPbapService: Succeed to create listening socket 
09-07 12:06:42.307  7753  8074 V BluetoothPbapService: Accepting socket connection...
09-07 12:06:42.313  6889  6889 D BluetoothPermissionRequest: onReceive
09-07 12:06:42.315  6889  6889 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,09-07 12:06:42.316  6889  6889 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-07 12:06:42.319  7753  7753 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
09-07 12:06:42.321  7753  7753 I LGBluetoothOppAdapter: [BTUI] startOppService()
09-07 12:06:42.326  7753  7753 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,09-07 12:06:42.352  7753  7753 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,09-07 12:06:42.352  7753  7753 V BtOppService: onCreate
,09-07 12:06:42.478  1037  1893 I art     : Explicit concurrent mark sweep GC freed 27508(1350KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 1.571ms total 122.270ms
,09-07 12:06:42.483  7753  7753 V BluetoothOppNotification: send message
09-07 12:06:42.486  7753  7753 V BtOppService: Starting RfcommListener
09-07 12:06:42.490  7753  7753 D BluetoothOppPreference: Dumping Names:  
,09-07 12:06:42.490  7753  7753 D BluetoothOppPreference: {}
09-07 12:06:42.490  7753  7753 D BluetoothOppPreference: Dumping Channels:  
09-07 12:06:42.491  7753  7753 D BluetoothOppPreference: {}
09-07 12:06:42.495  7753  7753 V BtOppService: onStartCommand
09-07 12:06:42.499  7753  7753 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-07 12:06:42.499  7753  7753 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-07 12:06:42.502  7753  7753 V BluetoothOppNotification: new notify threadi!
,09-07 12:06:42.503  7753  7753 V BluetoothOppNotification: send delay message
09-07 12:06:42.504  7753  7753 V BtOppService: start RfcommListener
09-07 12:06:42.505  7753  8079 V BtOppService: Deleted complete outbound shares, number =  0
09-07 12:06:42.507  7753  8082 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-07 12:06:42.512  7753  8079 V BtOppService: Deleted complete inbound failed shares, number = 0
09-07 12:06:42.512  7753  7753 V BtOppService: RfcommListener started
09-07 12:06:42.514  7753  8079 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
09-07 12:06:42.514  7753  8083 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,09-07 12:06:42.515  7753  8079 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1dea4bc0 on behalf of 
09-07 12:06:42.515  7753  8082 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-07 12:06:42.517  7753  8084 V BtOppRfcommListener: Starting RFCOMM listener....
09-07 12:06:42.518  1037  1964 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 12:06:42.519  7753  8084 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-07 12:06:42.520  7753  8084 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
09-07 12:06:42.520  7753  8084 V BtOppRfcommListener: Started RFCOMM listener....
09-07 12:06:42.520  7753  8084 I BtOppRfcommListener: Accept thread started.
09-07 12:06:42.521  7753  8084 V BtOppRfcommListener: Accepting connection...
09-07 12:06:42.521  7753  8083 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3656f0f9 on behalf of 
09-07 12:06:42.521  7753  8082 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3a06a83e on behalf of 
09-07 12:06:42.522  7753  8083 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-07 12:06:42.523  7753  8082 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-07 12:06:42.523  7753  8083 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-07 12:06:42.524  7753  8083 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1a0cb69f on behalf of 
09-07 12:06:42.525  7753  8083 V BluetoothOppNotification: outbound: succ-0  fail-0
,09-07 12:06:42.527  7753  8083 V BluetoothOppNotification: outbound notification was removed.
09-07 12:06:42.527  7753  8083 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-07 12:06:42.528  7753  8083 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@150863ec on behalf of 
,09-07 12:06:42.528  7753  8083 V BluetoothOppNotification: inbound: succ-0  fail-0
09-07 12:06:42.531  7753  8083 V BluetoothOppNotification: inbound notification was removed.
09-07 12:06:42.531  7753  8083 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-07 12:06:42.532  7753  8083 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@378ca3b5 on behalf of 
09-07 12:06:42.539  7753  7753 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a8833c4
09-07 12:06:42.539  7753  7753 V BluetoothFtpService: Ftp Service onCreate
09-07 12:06:42.539  7753  7753 I BluetoothFtpService: Ftp Service onCreate
09-07 12:06:42.539  7753  7753 V BluetoothFtpService: Ftp Service onStartCommand
09-07 12:06:42.539  7753  7753 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-07 12:06:42.540  7753  7753 V BluetoothFtpService: Starting Listening on sockets
09-07 12:06:42.540  7753  7753 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-07 12:06:42.540  7753  7753 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-07 12:06:42.540  7753  7753 V BluetoothSapReceiver: SapReceiver onReceive 
09-07 12:06:42.540  7753  7753 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-07 12:06:42.540  7753  7753 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
09-07 12:06:42.540  7753  7753 V BluetoothSapReceiver: Calling SAP service start service with action = null
,09-07 12:06:42.542  7753  7753 V BtOppService: ContentObserver received notification
,09-07 12:06:42.542  7753  7753 V BtOppService: ContentObserver received notification
09-07 12:06:42.543  7753  7753 V BluetoothFtpService: Handler(): got msg=1
09-07 12:06:42.543  7753  7753 V BluetoothFtpService: Ftp Service startRfcommSocketListener
09-07 12:06:42.543  7753  7753 V BluetoothFtpService: Ftp Service initSocket
09-07 12:06:42.545  7753  8085 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-07 12:06:42.545  7753  8085 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-07 12:06:42.545  1037  1694 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 12:06:42.546  7753  8085 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@39901dbb on behalf of 
09-07 12:06:42.546  7753  7753 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-07 12:06:42.546  7753  7753 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=81 mFd=78
09-07 12:06:42.546  7753  8085 V BluetoothOppNotification: update too frequent, put in queue
09-07 12:06:42.547  7753  7753 V BluetoothFtpService: Succeed to create listening socket on channel 20
09-07 12:06:42.548  7753  8086 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
09-07 12:06:42.552  7753  8085 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
,09-07 12:06:42.556  7753  7753 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a8833c4
09-07 12:06:42.556  7753  7753 V BluetoothSapService: Sap Service onCreate
09-07 12:06:42.557  7753  7753 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,09-07 12:06:42.557  7753  7753 V BluetoothSapService: state: 12
09-07 12:06:42.557  7753  7753 V BluetoothSapService: Starting SAP server process
09-07 12:06:42.558  7753  7753 V BluetoothSapService: SAP Service startRfcommListenerThread
09-07 12:06:42.544  8087  8087 W sapd    : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-07 12:06:42.544  8087  8087 W sapd    : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-07 12:06:42.559  7753  8088 V BluetoothSapService: Sap Service initRfcommSocket
09-07 12:06:42.560  1037  1964 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 12:06:42.560  7753  8088 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-07 12:06:42.561  7753  8088 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=81
,09-07 12:06:42.561  7753  8088 V BluetoothSapService: Succeed to create listening socket 
09-07 12:06:42.561  7753  8088 V BluetoothSapService: Accepting socket connection...
09-07 12:06:42.565  8087  8087 V BT_SAP  : Event pipe created
09-07 12:06:42.566  8087  8087 V BT_SAP  : create_server_socket qcom.sap.server
09-07 12:06:42.566  8087  8087 V BT_SAP  : created socket fd 6
,09-07 12:06:42.905  6798  6867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 12:06:42.905  6798  6867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:06:42.905  6798  6867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 12:06:42.905  6798  6867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 12:06:42.905  6798  6867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 12:06:42.905  6798  6867 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 12:06:42.905  6798  6867 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 12:06:42.905  6798  6867 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 12:06:42.909  6798  6867 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 12:06:42.912  6798  6867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 12:06:42.912  6798  6867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@111cf51 added. We now have 8 listener(s)
09-07 12:06:42.912  6798  6867 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 12:06:42.920  1037  1874 D WifiServiceImplEx: setWifiEnabled: false pid=6798, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-07 12:06:42.921  1037  1874 D WifiService: setWifiEnabled: false pid=6798, uid=10118
09-07 12:06:42.921  1037  1874 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-07 12:06:42.929  6798  6867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 12:06:42.930  1037  1564 D WifiServiceImplEx: setWifiEnabled: true pid=6798, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-07 12:06:42.930  1037  1564 D WifiService: setWifiEnabled: true pid=6798, uid=10118
09-07 12:06:42.930  1037  1564 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-07 12:06:42.947  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
,09-07 12:06:42.948  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-07 12:06:42.948  1037  1037 D Ulp_jni : JNI:system_update. Event-4
09-07 12:06:42.949  1037  1527 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
09-07 12:06:42.949  1037  1527 I LGFTMITEM: [GET_FTM][id=6], offset=12288
09-07 12:06:42.952  1037  1527 E WifiUtil: wfc_util_ffile_check_copy(): pid[1037] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
09-07 12:06:42.952  1037  1527 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-07 12:06:42.952  1037  1527 E WifiUtil: wfc_util_ffile_check_copy(): pid[1037] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
09-07 12:06:42.952  1037  1527 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
,09-07 12:06:42.952  1037  1527 I WifiUtil: Intf0MacAddress=C49A027FFB5D
09-07 12:06:42.952  1037  1527 E WifiHW  : unknown target_country: EU , set to default
,09-07 12:06:42.952  1037  1527 E WifiHW  : [wifi_ensure_config_files] default country1 = GB,
09-07 12:06:42.952  1037  1527 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
09-07 12:06:42.952  1037  1527 I WifiUtil: gEnableBmps=1
09-07 12:06:43.508  7753  7753 V BluetoothOppNotification: new notify threadi!
,09-07 12:06:43.509  7753  7753 V BluetoothOppNotification: send delay message
,09-07 12:06:43.556   309   894 D SoftapController: Softap fwReload - Ok
,09-07 12:06:43.662  1037  1527 E NetdConnector: NDC Command {84 softap fwreload wlan0 STA} took too long (705ms)
09-07 12:06:43.662  7753  8107 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-07 12:06:43.664  7753  8107 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3418da97 on behalf of 
,09-07 12:06:43.666  7753  8107 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-07 12:06:43.669  7753  8107 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-07 12:06:43.670   309   894 D CommandListener: Setting iface cfg
09-07 12:06:43.670   309   894 D CommandListener: Trying to bring down wlan0
09-07 12:06:43.671  7753  8107 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@28f94484 on behalf of 
09-07 12:06:43.671   309   894 D CommandListener: Clearing all IP addresses on wlan0
09-07 12:06:43.673  7753  8107 V BluetoothOppNotification: outbound: succ-0  fail-0
09-07 12:06:43.675  7753  8107 V BluetoothOppNotification: outbound notification was removed.
09-07 12:06:43.675  1037  1119 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-07 12:06:43.675  7753  8107 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
,09-07 12:06:43.679  6889  6889 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-07 12:06:43.679  6889  6889 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-07 12:06:43.679  6889  6889 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-07 12:06:43.679  6889  6889 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-07 12:06:43.680  6889  6889 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-07 12:06:43.680  6889  6889 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-07 12:06:43.680  6889  6889 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
09-07 12:06:43.680  6889  6889 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-07 12:06:43.681  6889  6889 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-07 12:06:43.681  6889  6889 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-07 12:06:43.681  6889  6889 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
09-07 12:06:43.681  6889  6889 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-07 12:06:43.684  7753  8107 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@271a946d on behalf of 
09-07 12:06:43.685  1037  1527 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
09-07 12:06:43.685  7753  8107 V BluetoothOppNotification: inbound: succ-0  fail-0
09-07 12:06:43.685  1037  1119 D Tethering: InitialState.processMessage what=4
09-07 12:06:43.686  1037  1119 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-07 12:06:43.690  6889  6889 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,09-07 12:06:43.690  6889  6889 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-07 12:06:43.690  6889  6889 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-07 12:06:43.690  6889  6889 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-07 12:06:43.684  8125  8125 W wpa_supplicant: type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-07 12:06:43.694  7753  8107 V BluetoothOppNotification: inbound notification was removed.
09-07 12:06:43.694  7753  8107 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-07 12:06:43.695  1037  1527 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-07 12:06:43.695  1037  1527 E WifiStateMachine: useWiFiOffloading() : false
09-07 12:06:43.695  1037  1527 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-07 12:06:43.695  7753  8107 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@38d898a2 on behalf of 
09-07 12:06:43.696  1037  1527 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-07 12:06:43.696  1037  1527 D WifiMonitor: connecting to supplicant
09-07 12:06:43.698  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
09-07 12:06:43.699  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 12:06:43.700  1930  1930 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
09-07 12:06:43.700  6889  6889 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-07 12:06:43.702  6889  6889 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-07 12:06:43.702  6889  6889 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-07 12:06:43.702  6889  6889 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-07 12:06:43.702  6889  6889 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-07 12:06:43.702  6889  6889 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-07 12:06:43.702  6889  6889 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-07 12:06:43.705  6798  6798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 12:06:43.684  8125  8125 W wpa_supplicant: type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-07 12:06:43.716  8125  8125 I wpa_supplicant: Successfully initialized wpa_supplicant
09-07 12:06:43.745  1037  1052 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8126 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,09-07 12:06:43.752  8125  8125 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-07 12:06:43.753  8125  8125 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,09-07 12:06:43.800  8125  8125 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-07 12:06:43.838  8125  8125 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,09-07 12:06:43.845  1037  1527 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
09-07 12:06:43.845  1037  1527 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
09-07 12:06:43.846  1037  1527 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
09-07 12:06:43.846  1037  1527 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
09-07 12:06:43.847  1037  1527 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-07 12:06:43.847  1037  1527 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-07 12:06:43.848  1037  1527 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-07 12:06:43.848  1037  1527 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-07 12:06:43.849  1037  1527 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
09-07 12:06:43.849  1037  1527 D WifiNative-wlan0: doString: [DRIVER MACADDR]
09-07 12:06:43.850  1037  1527 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
09-07 12:06:43.850  1037  1527 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
09-07 12:06:43.850  1037  1527 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
,09-07 12:06:43.863  8125  8125 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
,09-07 12:06:43.864  1037  8149 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-07 12:06:43.864  1037  8149 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-07 12:06:43.864  1037  8149 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
09-07 12:06:43.864  1037  8149 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
09-07 12:06:43.864  1037  8149 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
09-07 12:06:43.864  1037  8149 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
09-07 12:06:43.894  1037  1694 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8150 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-07 12:06:43.898  1037  1527 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-07 12:06:43.898  1037  1527 E WifiStateMachine: useWiFiOffloading() : false
09-07 12:06:43.898  1037  1527 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-07 12:06:43.898  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 12:06:43.898  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 12:06:43.898  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 12:06:43.898  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 12:06:43.899  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-07 12:06:43.900  1037  1527 D WifiNative-wlan0: doBoolean: SET update_config 1
09-07 12:06:43.902  1037  1527 D WifiNative-wlan0: SET update_config 1: returned true
09-07 12:06:43.902  1037  1527 D WifiConfigStore: Loading config and enabling all networks 
09-07 12:06:43.902  1037  1527 D WifiNative-wlan0: doString: [LIST_NETWORKS]
09-07 12:06:43.903  1037  1527 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
09-07 12:06:43.904  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 12:06:43.905  1930  1930 D WfdService: Waiting for WifiP2p enabling
09-07 12:06:43.914  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
09-07 12:06:43.914  1037  1532 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
09-07 12:06:43.915  6798  6798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 12:06:43.915  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:06:43.915  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 12:06:43.915  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 12:06:43.915  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 12:06:43.915  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 12:06:43.915  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 12:06:43.915  6798  6798 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 12:06:43.917  6798  6798 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-07 12:06:43.918  1037  1527 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
09-07 12:06:43.930  1037  1527 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
09-07 12:06:43.931  1037  1527 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,09-07 12:06:43.932  1037  1527 D WifiStateMachine: enableVerboseLogging : level 2
09-07 12:06:43.932  1037  1527 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
09-07 12:06:43.933  1037  1527 D WifiNative-wlan0: SET device_name g3_global_com: returned true
09-07 12:06:43.933  1037  1527 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
09-07 12:06:43.933  1037  1527 D WifiNative-wlan0: SET manufacturer LGE: returned true
09-07 12:06:43.933  1037  1527 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
09-07 12:06:43.934  1037  1527 D WifiNative-wlan0: SET model_name LG-D855: returned true
09-07 12:06:43.934  1037  1527 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
09-07 12:06:43.935  1037  1527 D WifiNative-wlan0: SET model_number LG-D855: returned true
09-07 12:06:43.935  1037  1527 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
09-07 12:06:43.935  1037  1527 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
09-07 12:06:43.935  1037  1527 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
09-07 12:06:43.936  1037  1527 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
09-07 12:06:43.936  1037  1527 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
09-07 12:06:43.937  1037  1527 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
,09-07 12:06:43.938  1930  1930 D WfdsService: Supplicant Connection state is changed : true
09-07 12:06:43.938  1037  1527 D WifiStateMachine: Setting OUI to DA-A1-19
09-07 12:06:43.938  7782  7782 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 12:06:43.938  1037  1527 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
09-07 12:06:43.939  1037  1527 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
09-07 12:06:43.939  1037  1527 D WifiNative-HAL: Setting external_sim to 1
09-07 12:06:43.939  1037  1527 D WifiNative-wlan0: doBoolean: SET external_sim 1
09-07 12:06:43.940  1037  1527 D WifiNative-wlan0: SET external_sim 1: returned true
09-07 12:06:43.940  1037  1527 I WifiNative-HAL: startHal
09-07 12:06:43.940  1037  1527 D wifi    : setting scan oui 0xaf6111e0
09-07 12:06:43.940  1037  1527 D WifiStateMachine: Setting OUI to DA-A1-19
09-07 12:06:43.940  1037  1527 I WifiNative-HAL: startHal
09-07 12:06:43.940  1037  1527 D wifi    : setting scan oui 0xaf6111e0
09-07 12:06:43.940  1037  1527 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
09-07 12:06:43.941  1037  1527 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
09-07 12:06:43.941  1037  1527 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
09-07 12:06:43.942  8125  8125 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
09-07 12:06:43.942  1930  2316 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
09-07 12:06:43.942  1930  2316 D WfdsService: Set the WFDS Monitor: true
09-07 12:06:43.942  1930  2316 D WfdsMonitor: WfdsMonitorThread create
09-07 12:06:43.942  1930  2316 D WfdsMonitor: WFDS Monitor is created and started
09-07 12:06:43.942  1930  2316 D WfdsService: WiFi: Supplicant connection re-established
09-07 12:06:43.942  1037  1527 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
09-07 12:06:43.942  8126  8147 W FormManager: Network not available. Please check & try again.
09-07 12:06:43.942  1037  1527 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-07 12:06:43.943  8125  8125 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-07 12:06:43.943  1930  8168 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
09-07 12:06:43.943  1037  1527 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-07 12:06:43.943  1037  1527 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
09-07 12:06:43.943  1930  8168 E CtrlSupplicant: Succeed to open control connection
09-07 12:06:43.943  8125  8125 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
09-07 12:06:43.944  1930  8168 E CtrlSupplicant: Succeed to open monitor connection
09-07 12:06:43.944  1930  8168 D WfdsMonitor: Supplicant connection established
09-07 12:06:43.944  1037  1527 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
09-07 12:06:43.944  1037  1527 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-07 12:06:43.944  1930  2316 D WfdsService: Connected to the supplicant for wfds
09-07 12:06:43.944  8125  8125 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-07 12:06:43.945  1037  1527 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-07 12:06:43.945  1037  1527 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-07 12:06:43.945  8125  8125 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-07 12:06:43.946  1037  1527 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-07 12:06:43.946  1037  1527 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
09-07 12:06:43.946  8125  8125 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
09-07 12:06:43.946  8126  8148 V FormManager: Network unavailable.
09-07 12:06:43.946  1037  1527 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
09-07 12:06:43.946  1037  1527 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-07 12:06:43.947  8125  8125 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
,09-07 12:06:43.947  1037  1527 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-07 12:06:43.948  1037  1527 E WifiNative: : [198,163,341 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
09-07 12:06:43.948  1037  1527 D WifiNative-wlan0: doBoolean: RECONNECT
09-07 12:06:43.948  1037  1527 D WifiNative-wlan0: RECONNECT: returned true
09-07 12:06:43.949  1037  1527 D WifiNative-wlan0: doString: [STATUS]
09-07 12:06:43.949  1037  8149 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-07 12:06:43.949  1037  8149 E WifiMonitor: WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-07 12:06:43.949  8126  8148 V FormManager: Network unavailable.
09-07 12:06:43.950  1037  1527 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-07 12:06:43.950  1037  1527 D WifiNative-wlan0: doBoolean: SET ps 1
09-07 12:06:43.950  1037  1527 D WifiNative-wlan0: SET ps 1: returned true
09-07 12:06:43.950  1037  1526 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
09-07 12:06:43.951  1037  1037 D WifiScanningService: SCAN_AVAILABLE : 3
09-07 12:06:43.951  1037  1037 D RttService: SCAN_AVAILABLE : 3
09-07 12:06:43.952  1037  1546 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-07 12:06:43.952  1037  1545 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-07 12:06:43.952  1037  1545 I WifiNative-HAL: startHal
09-07 12:06:43.952  1037  1545 D wifi    : getting scan capabilities on interface[1] = 0xaf6111e0
09-07 12:06:43.952  1037  1545 D wifi    : failed to get capabilities : -3
09-07 12:06:43.952  1037  1545 E WifiScanningService: could not get scan capabilities
09-07 12:06:43.953  1037  1527 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
09-07 12:06:43.953  1037  1527 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
09-07 12:06:43.953   309   894 D CommandListener: Setting iface cfg
09-07 12:06:43.953   309   894 D CommandListener: Trying to bring up p2p0
09-07 12:06:43.953  1037  1527 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
09-07 12:06:43.953  1037  1526 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-07 12:06:43.953  1037  1526 D LGWifiP2pService: P2pEnablingState
09-07 12:06:43.953  1037  1526 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
09-07 12:06:43.953  1037  1526 D LGWifiP2pService: P2p socket connection successful
09-07 12:06:43.954  1037  1526 D LGWifiP2pService: P2pEnabledState
09-07 12:06:43.954  1037  1527 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
09-07 12:06:43.954  1037  1526 D LGWifiP2pService: sending p2p connection changed broadcast
09-07 12:06:43.955  1930  1930 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
09-07 12:06:43.955  1930  1930 D WfdsService: WifiP2pState is changed : true
09-07 12:06:43.955  1930  2316 D WfdsService: Receive the WFDS_ENABLE Method
09-07 12:06:43.955  1930  2316 D WfdsService: Set the WFDS Monitor: true
09-07 12:06:43.955  1930  2316 D WfdsService: Connected to the supplicant for wfds
09-07 12:06:43.955  1930  2316 D WfdsJNI : doCommand: WFDS_SET TRUE
09-07 12:06:43.955  1037  1526 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
09-07 12:06:43.955  8125  8125 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
09-07 12:06:43.955  1930  2316 D WfdsService: selectPreferredScanChannel [36]
09-07 12:06:43.956  1930  2316 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
09-07 12:06:43.956  1930  1930 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
09-07 12:06:43.95,7  1930  1930 D WfdsService: isConnected: false
09-07 12:06:43.958  1037  1526 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
09-07 12:06:43.958  1037  1526 D WifiNative-p2p0: doBoolean: SET device_name G3
09-07 12:06:43.958  1037  1526 D WifiNative-p2p0: SET device_name G3: returned true
09-07 12:06:43.958  1037  1526 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
09-07 12:06:43.959  1037  1526 D LGWifiP2pService: before postfix = G3
09-07 12:06:43.959  1037  1526 D WifiServerServiceExt: postfix byte check : 2
09-07 12:06:43.959  1037  1526 D LGWifiP2pService: after postfix = G3
09-07 12:06:43.959  1037  1526 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
09-07 12:06:43.959  1037  1526 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
09-07 12:06:43.959  1037  1526 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
09-07 12:06:43.959  1037  1526 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
09-07 12:06:43.959  1037  1526 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
09-07 12:06:43.960  1037  1526 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
09-07 12:06:43.960  1037  1526 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
09-07 12:06:43.960  1037  1526 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
09-07 12:06:43.960  1037  1526 D WifiNative-HAL: p2pGetDeviceAddress
09-07 12:06:43.960  1037  1526 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
09-07 12:06:43.964  6798  6867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 12:06:43.964  6798  6867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:06:43.964  6798  6867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 12:06:43.964  6798  6867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 12:06:43.964  6798  6867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 12:06:43.964  6798  6867 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 12:06:43.964  6798  6867 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 12:06:43.964  6798  6867 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 12:06:43.964  1930  1930 I WfdStateTracker: handleP2pThisDeviceChanged
09-07 12:06:43.964  1930  1930 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
09-07 12:06:43.964  1930  1930 D WfdsService: Update P2p Interface State: 3
09-07 12:06:43.964  1037  1526 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
09-07 12:06:43.964  1037  1526 D WifiNative-p2p0: doBoolean: P2P_FLUSH
09-07 12:06:43.965  1037  1527 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=198180  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-07 12:06:43.965  1037  1526 D WifiNative-p2p0: P2P_FLUSH: returned true
09-07 12:06:43.965  1037  1526 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
09-07 12:06:43.965  1037  1526 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
09-07 12:06:43.965  1037  1526 D WifiNative-p2p0: doString: [LIST_NETWORKS]
09-07 12:06:43.965  6798  6867 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-07 12:06:43.966  1037  1526 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
09-07 12:06:43.966  1037  1526 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
09-07 12:06:43.967  1592  1592 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 12:06:43.967  1592  1592 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-07 12:06:43.968  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 12:06:43.968  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 12:06:43.969  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 12:06:43.969  1037  1527 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=198184  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-07 12:06:43.969  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-07 12:06:43.969  1037  1527 E WifiStateMachine:  DisconnectedState what:132106 1 0
09-07 12:06:43.970  1037  1527 E WifiStateMachine:  ConnectModeState what:132106 1 0
09-07 12:06:43.970  1037  1527 E WifiStateMachine:  DriverStartedState what:132106 1 0
09-07 12:06:43.970  1037  1527 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
09-07 12:06:43.976  6798  6867 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
09-07 12:06:43.977  1037  1965 I ActivityManager: Killing 7194:com.android.chrome/u0a57 (adj 15): empty #17
09-07 12:06:43.978  6798  6867 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
09-07 12:06:43.978  8125  8125 E wpa_supplicant: nWIFIDualbandAPConnection: 1
09-07 12:06:43.979  1037  1527 E WifiStateMachine:  DisconnectedState what:132096 -100 0
09-07 12:06:43.979  1037  1527 E WifiStateMachine:  ConnectModeState what:132096 -100 0
09-07 12:06:43.980  1037  1527 E WifiStateMachine:  DriverStartedState what:132096 -100 0
09-07 12:06:43.980  1037  1527 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
09-07 12:06:43.980  8125  8125 E wpa_supplicant: disconnect_rssi_lvl: -100
09-07 12:06:43.980  6798  6867 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@416dbeb Bundle[{}]
09-07 12:06:43.980  1037  1526 D WifiNative-p2p0: SAVE_CONFIG: returned true
09-07 12:06:43.980  1037  1526 D LGWifiP2pService: sending p2p persistent groups changed broadcast
09-07 12:06:43.980  1037  1527 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
09-07 12:06:43.981  6798  6867 I io.jxcore.node.LifeCycleMonitor: start: OK
09-07 12:06:43.981  1037  1527 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
09-07 12:06:43.981  6798  6867 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-07 12:06:43.981  1037  1527 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
09-07 12:06:43.981  1037  1527 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
09-07 12:06:43.981  6798  6867 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-07 12:06:43.981  8125  8125 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-07 12:06:43.982  8125  8125 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-07 12:06:43.982  8125  8125 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-07 12:06:43.982  8125  8125 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 12:06:43.982  1930  8168 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-07 12:06:43.983  8125  8125 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 12:06:43.983  1930  8168 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-07 12:06:43.984  1037  8149 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-07 12:06:43.984  1037  8149 E WifiMonitor: WifiMonitor:wlan0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-07 12:06:43.984  1037  8149 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-07 12:06:43.984  1037  8149 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-07 12:06:43.984  1037  8149 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-07 12:06:43.984  1037  8149 E WifiMonitor: WifiMonitor:p2p0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 12:06:43.984  1037  8149 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 12:06:43.984  1037  8149 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 12:06:43.984  1037  8149 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-07 12:06:43.984  1037  8149 E WifiMonitor: WifiMonitor:p2p0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 12:06:43.984  1037  8149 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 12:06:43.984  1037  8149 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 12:06:43.984  1037  1527 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
09-07 12:06:43.985  1037  1527 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
09-07 12:06:43.985  1037  1527 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
09-07 12:06:43.985  1037  1527 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
09-07 12:06:43.985  1037  1527 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
09-07 12:06:43.985  8125  8125 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
09-07 12:06:43.985  8125  8125 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-07 12:06:43.985  6798  6867 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-07 12:06:43.986  1037  8149 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
09-07 12:06:43.986  6798  6867 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-07 12:06:43.986  1037  8149 E WifiMonitor: WifiMonitor:wlan0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-07 12:06:43.986  1037  8149 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-07 12:06:43.986  1037  8149 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-07 12:06:43.986  1037  1527 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
09-07 12:06:43.986  1037  1527 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
09-07 12:06:43.987  1037  1527 D WifiNative-wlan0: BSS_FLUSH 0: returned true
09-07 12:06:43.987  1037  1527 D WifiNative-wlan0: doBoolean: SCAN
09-07 12:06:43.987  6798  6867 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
09-07 12:06:43.987  1037  1527 D WifiNative-wlan0: SCAN: returned false
09-07 12:06:43.987  1037  1527 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=198203  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-07 12:06:43.993  6798  6867 I System.out: Running OutgoingSocketThread
,09-07 12:06:43.995  6798  8169 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 901)
09-07 12:06:43.996  6798  8169 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 40095
09-07 12:06:43.996  6798  8169 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
09-07 12:06:44.017  8150  8150 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-07 12:06:44.033  1037  1526 D LGWifiP2pService: InactiveState
,09-07 12:06:44.033  1037  1526 D LGWifiP2pService: InactiveState{ when=-68ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
,09-07 12:06:44.034  1037  1526 D LGWifiP2pService: P2pEnabledState{ when=-69ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-07 12:06:44.034  1037  1526 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
09-07 12:06:44.036  8125  8125 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-07 12:06:44.037  8125  8125 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-07 12:06:44.037  1930  8168 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-07 12:06:44.037  1037  8149 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-07 12:06:44.037  1037  8149 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-07 12:06:44.037  1037  8149 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-07 12:06:44.037  1037  8149 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-07 12:06:44.038  8125  8125 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-07 12:06:44.038  1037  1874 W libprocessgroup: failed to open /acct/uid_10057/pid_7194/cgroup.procs: No such file or directory
09-07 12:06:44.038  8125  8125 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 12:06:44.038  1037  1526 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
09-07 12:06:44.038  1037  1526 D LGWifiP2pService: InactiveState{ when=-54ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-07 12:06:44.038  8125  8125 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 12:06:44.038  1037  1526 D LGWifiP2pService: P2pEnabledState{ when=-54ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-07 12:06:44.039  1930  8168 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-07 12:06:44.039  1930  8168 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-07 12:06:44.039  1037  8149 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-07 12:06:44.039  1037  1527 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=198253  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-07 12:06:44.039  1037  8149 E WifiMonitor: WifiMonitor:p2p0 cnt=53 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,09-07 12:06:44.039  1037  8149 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 12:06:44.039  1037  8149 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 12:06:44.040  1037  8149 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-07 12:06:44.040  1037  8149 E WifiMonitor: WifiMonitor:p2p0 cnt=54 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 12:06:44.040  1037  8149 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 12:06:44.040  1037  8149 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 12:06:44.040  1037  1526 D LGWifiP2pService: InactiveState{ when=-5ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-07 12:06:44.040  1037  1526 D LGWifiP2pService: P2pEnabledState{ when=-7ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-07 12:06:44.040  1037  1526 D LGWifiP2pService: DefaultState{ when=-7ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-07 12:06:44.041  1037  1527 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-07 12:06:44.042  1037  1526 D LGWifiP2pService: InactiveState{ when=-9ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
,09-07 12:06:44.042  1037  1526 D LGWifiP2pService: P2pEnabledState{ when=-9ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-07 12:06:44.042  1037  1526 D LGWifiP2pService: DefaultState{ when=-9ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-07 12:06:44.043  1037  1526 D LGWifiP2pService: InactiveState{ when=-9ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-07 12:06:44.043  1037  1527 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-07 12:06:44.043  1930  2316 W WfdsService: DefaultState - msg [9441285] is not handled
,09-07 12:06:44.043  1037  1526 D LGWifiP2pService: P2pEnabledState{ when=-10ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-07 12:06:44.043  1037  1526 D LGWifiP2pService: DefaultState{ when=-10ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-07 12:06:44.044  1037  1527 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-07 12:06:44.045  1037  1526 D LGWifiP2pService: InactiveState{ when=-11ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-07 12:06:44.045  1592  1592 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false],
09-07 12:06:44.045  1037  1526 D LGWifiP2pService: P2pEnabledState{ when=-12ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-07 12:06:44.045  1592  1592 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-07 12:06:44.045  1037  1527 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-07 12:06:44.045  1037  1526 D LGWifiP2pService: DefaultState{ when=-12ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-07 12:06:44.046  1037  1527 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-07 12:06:44.048  1037  1037 E WifiServerServiceExt: No p2p device connected,
09-07 12:06:44.049  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 12:06:44.049  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 12:06:44.049  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-07 12:06:44.049  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-07 12:06:44.054  6889  6889 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-07 12:06:44.056  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-07 12:06:44.056  1037  1037 D WifiServerServiceExt: setSupplicantStateSCANNING
09-07 12:06:44.057  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-07 12:06:44.057  1037  1037 D WifiServerServiceExt: setSupplicantStateSCANNING
,09-07 12:06:44.063  6889  6889 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 12:06:44.064  1037  1052 I ActivityManager: Killing 7218:com.lge.drmservice/u0a62 (adj 15): empty #17
09-07 12:06:44.104  1037  1774 W libprocessgroup: failed to open /acct/uid_10062/pid_7218/cgroup.procs: No such file or directory
,09-07 12:06:44.140  8150  8150 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-07 12:06:44.145  6889  6889 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-07 12:06:44.150  8126  8173 W FormManager: Network not available. Please check & try again.
,09-07 12:06:44.154  8126  8174 V FormManager: Network unavailable.
09-07 12:06:44.154  6889  6889 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 12:06:44.162  8126  8174 V FormManager: Network unavailable.
09-07 12:06:44.174  4760  4760 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,09-07 12:06:44.174  4760  4760 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-07 12:06:44.180  4760  4760 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-07 12:06:44.182  4760  4760 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-07 12:06:44.187  4760  8175 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-07 12:06:44.192  4760  8176 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-07 12:06:44.193  4760  8176 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-07 12:06:44.254  1037  2002 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8177 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,09-07 12:06:44.358  8177  8177 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-07 12:06:44.359  8177  8177 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,09-07 12:06:44.371  8177  8177 V [BNRBootReceiver]: Boot Receiver Return
09-07 12:06:44.372  8177  8177 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-07 12:06:44.434  1037  1964 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8198 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-07 12:06:44.437  1037  1964 I ActivityManager: Killing 7240:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
09-07 12:06:44.493  1037  1965 W libprocessgroup: failed to open /acct/uid_10085/pid_7240/cgroup.procs: No such file or directory
,09-07 12:06:44.521  8198  8198 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-07 12:06:44.549  8198  8198 D PluginManager: init()
,09-07 12:06:44.596  1037  8149 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
,09-07 12:06:44.596  1037  8149 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
09-07 12:06:44.596  8125  8125 E wpa_supplicant: USIM:  scard_init function
09-07 12:06:44.596  1037  8149 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
09-07 12:06:44.596  1037  8149 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: WPS-AP-AVAILABLE 
09-07 12:06:44.597  1037  8149 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
09-07 12:06:44.597  8125  8125 I wpa_supplicant: Trying to associate with SSID 'NG700'
09-07 12:06:44.601  1037  1527 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
09-07 12:06:44.601  1037  1527 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
09-07 12:06:44.602  1037  1527 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
,09-07 12:06:44.603  1037  8149 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
09-07 12:06:44.603  1037  8149 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
09-07 12:06:44.604  1037  1527 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
09-07 12:06:44.604  1037  1527 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
09-07 12:06:44.614  1037  1527 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=198829  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-07 12:06:44.615  1037  1527 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=198830  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,09-07 12:06:44.618  1592  1592 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 12:06:44.618  1592  1592 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-07 12:06:44.619  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 12:06:44.622  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 12:06:44.622  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 12:06:44.623  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-07 12:06:44.623  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-07 12:06:44.623  1037  1037 D WifiServerServiceExt: setSupplicantStateASSOCIATING
09-07 12:06:44.708  1037  8149 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
09-07 12:06:44.708  8125  8125 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
09-07 12:06:44.708  1037  8149 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
09-07 12:06:44.708  1037  8149 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
09-07 12:06:44.709  1037  8149 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: Associated with f4:f2:6d:22:99:3e
,09-07 12:06:44.713  1037  1527 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=198929  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
,09-07 12:06:44.714  1037  1527 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=198930  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-07 12:06:44.715  1037  1527 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=198930
09-07 12:06:44.715  1037  1527 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=198931
09-07 12:06:44.715  1037  1527 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=198931
,09-07 12:06:44.716  1037  1527 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=198932
09-07 12:06:44.716  1037  1527 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=198932
09-07 12:06:44.718  1037  8149 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-07 12:06:44.718  1037  8149 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-07 12:06:44.719  1037  1119 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-07 12:06:44.719  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-07 12:06:44.719  1037  1037 D WifiServerServiceExt: setSupplicantStateASSOCIATED
09-07 12:06:44.720  1037  1527 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=198936  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-07 12:06:44.724  1037  1527 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=198940  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-07 12:06:44.725  1037  1527 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
09-07 12:06:44.726  1037  1527 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
09-07 12:06:44.726  1037  1527 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
09-07 12:06:44.726  1037  1527 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
09-07 12:06:44.727  1037  1527 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,09-07 12:06:44.730  8125  8125 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-07 12:06:44.730  8125  8125 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-07 12:06:44.732  1037  8149 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-07 12:06:44.733  1037  8149 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-07 12:06:44.733  1037  8149 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
09-07 12:06:44.733  1037  8149 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-07 12:06:44.733  1037  8149 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-07 12:06:44.733  1037  8149 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
09-07 12:06:44.733  1037  8149 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-07 12:06:44.733  1037  8149 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-07 12:06:44.734  1037  8149 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-07 12:06:44.734  1037  8149 E WifiMonitor: WifiMonitor:wlan0 cnt=64 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-07 12:06:44.735  1592  1592 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 12:06:44.735  1592  1592 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-07 12:06:44.737  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 12:06:44.740  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 12:06:44.741  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 12:06:44.741  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,09-07 12:06:44.744  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 12:06:44.744  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 12:06:44.744  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
09-07 12:06:44.745  1037  1527 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 61 0 rt=198961  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-07 12:06:44.746  1037  1527 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 61 0 rt=198962  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-07 12:06:44.747  1037  1527 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=198962
09-07 12:06:44.747  1037  1527 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=198963
09-07 12:06:44.747  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-07 12:06:44.747  1037  1037 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
09-07 12:06:44.748  1037  1527 D WifiNative-wlan0: doString: [STATUS]
,09-07 12:06:44.748  1037  8149 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-07 12:06:44.748  1037  8149 E WifiMonitor: WifiMonitor:wlan0 cnt=65 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-07 12:06:44.749  1037  1527 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-07 12:06:44.750  1037  1527 I WifiServiceExtension: setVHTCapabilityType  : false
09-07 12:06:44.756  1037  1527 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
09-07 12:06:44.756  1037  1527 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,09-07 12:06:44.759  1592  1592 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 12:06:44.759  1592  1592 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-07 12:06:44.764  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 12:06:44.764  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 12:06:44.765  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,09-07 12:06:44.766  1037  1527 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
09-07 12:06:44.766  1037  1527 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-07 12:06:44.767  1037  1527 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-07 12:06:44.767  1037  1534 D ConnectivityService: Got NetworkAgent Messenger
09-07 12:06:44.767  1037  1534 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-07 12:06:44.767  1037  1534 D ConnectivityService: NetworkAgent connected
09-07 12:06:44.767  1037  1527 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-07 12:06:44.767  1037  1527 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-07 12:06:44.768  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 12:06:44.770  1592  1592 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 12:06:44.770  1592  1592 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-07 12:06:44.770  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 12:06:44.770  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 12:06:44.770  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-07 12:06:44.771  1037  1527 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-07 12:06:44.771  1037  1527 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-07 12:06:44.771  1037  1527 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-07 12:06:44.771  1037  1527 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-07 12:06:44.771  1037  1527 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-07 12:06:44.771  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 12:06:44.773  1592  1592 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 12:06:44.773  1592  1592 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-07 12:06:44.774  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 12:06:44.775  1037  1527 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-07 12:06:44.778   309   894 D CommandListener: Setting iface cfg
,09-07 12:06:44.783  1037  1527 E WifiStateMachine: Start Dhcp Watchdog 3
09-07 12:06:44.783  1037  8216 D DhcpStateMachine: StoppedState
09-07 12:06:44.783  1037  8216 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
09-07 12:06:44.783  1037  8216 D DhcpStateMachine: WaitBeforeStartState
09-07 12:06:44.784  1037  1527 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=198999  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-07 12:06:44.784  1037  1527 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=199000  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-07 12:06:44.785  1037  1527 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=199000  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-07 12:06:44.788  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-07 12:06:44.788  1037  1037 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
09-07 12:06:44.788  1037  1527 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 65 0 rt=199004  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-07 12:06:44.789  1037  1527 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 65 0 rt=199004  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-07 12:06:44.789  1037  1527 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 65 0 rt=199005  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-07 12:06:44.790  1037  1527 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14145] from screen [on:0 period:69022262] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-07 12:06:44.791  1037  1527 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:69022263] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-07 12:06:44.791  1037  1527 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,09-07 12:06:44.796  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 12:06:44.797  1037  1534 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
09-07 12:06:44.797  1037  1527 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 12:06:44.797  1037  1527 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 12:06:44.798  1037  1527 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 12:06:44.798  1037  1527 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 12:06:44.798  1037  1527 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 12:06:44.799  1037  1527 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 12:06:44.800  1037  1534 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-07 12:06:44.800  1037  1527 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=112,0,0
09-07 12:06:44.800  1037  1527 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=112,0,0
09-07 12:06:44.800  1037  1527 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
09-07 12:06:44.801  8125  8125 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
09-07 12:06:44.801  1037  1527 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
09-07 12:06:44.801  1037  1527 D WifiNative-wlan0: doBoolean: SET ps 0
09-07 12:06:44.802  1037  1527 D WifiNative-wlan0: SET ps 0: returned true
09-07 12:06:44.802  1037  1527 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
09-07 12:06:44.802  8125  8125 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
09-07 12:06:44.803  1037  1527 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
09-07 12:06:44.803  1037  1527 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
09-07 12:06:44.803  1037  1527 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-07 12:06:44.803  1037  1527 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-07 12:06:44.804  1037  1526 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1ab572c9 target=com.android.internal.util.StateMachine$SmHandler }
09-07 12:06:44.804  1037  1526 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1ab572c9 target=com.android.internal.util.StateMachine$SmHandler }
,09-07 12:06:44.804  1037  8216 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,09-07 12:06:44.804  1037  8216 D DhcpStateMachine: DHCP Start wake lock is acquired.
09-07 12:06:44.804   309   894 D CommandListener: Setting iface cfg
09-07 12:06:44.804   309   894 D CommandListener: Trying to bring up wlan0
,09-07 12:06:44.806  1037  1527 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
09-07 12:06:44.807  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-07 12:06:44.807  1037  1037 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-07 12:06:44.808  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-07 12:06:44.808  1037  1037 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-07 12:06:44.809  1037  1527 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 12:06:44.810  1037  1527 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 12:06:44.810  1037  1527 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 12:06:44.810  1037  1527 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 12:06:44.811  1037  1527 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 12:06:44.811  1037  1527 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 12:06:44.812  1037  1534 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-07 12:06:44.812  1037  1527 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-07 12:06:44.812  1037  1527 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-07 12:06:44.813  1037  1526 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-07 12:06:44.813  1037  1526 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-07 12:06:44.813  1037  1527 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-07 12:06:44.813  8125  8125 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-07 12:06:44.813  1037  1527 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-07 12:06:44.814  1037  1527 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
09-07 12:06:44.814  8125  8125 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
09-07 12:06:44.814  1037  1527 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
09-07 12:06:44.814  1037  1527 D WifiNative-wlan0: doBoolean: SET ps 1
09-07 12:06:44.830  1037  1527 D WifiNative-wlan0: SET ps 1: returned true
09-07 12:06:44.831  1037  1534 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-07 12:06:44.831  1037  1527 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-07 12:06:44.832  1037  1527 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-07 12:06:44.832  1037  1527 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-07 12:06:44.833  1037  1534 D ConnectivityService: ignoring duplicate network state non-change
,09-07 12:06:44.836  1592  1592 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 12:06:44.836  1592  1592 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-07 12:06:44.839  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 12:06:44.839  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 12:06:44.839  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-07 12:06:44.842  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 12:06:44.845  1037  1534 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-07 12:06:44.845  1037  1534 D ConnectivityService: Adding iface wlan0 to network 102
,09-07 12:06:44.850  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 12:06:44.851  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 12:06:44.851  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-07 12:06:44.855  1037  1037 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,09-07 12:06:44.857  1930  1930 V WfdStateTracker: handleWifiStateChangedEvent: 1
,09-07 12:06:44.858  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 12:06:44.858  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 12:06:44.858  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-07 12:06:44.861  1037  1527 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-07 12:06:44.862  1037  1037 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-07 12:06:44.865  1592  1592 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 12:06:44.865  1592  1592 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-07 12:06:44.866  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 12:06:44.867  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 12:06:44.867  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 12:06:44.867  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-07 12:06:44.870  1592  1592 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 12:06:44.870  1592  1592 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-07 12:06:44.870  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-07 12:06:44.872  1037  1534 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-07 12:06:44.872  1037  1534 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
09-07 12:06:44.873  1037  1534 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
09-07 12:06:44.874   309   894 E Netd    : netlink response contains error (File exists)
,09-07 12:06:44.874  1037  1534 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
09-07 12:06:44.875  1037  1534 D ConnectivityService: addLocalRoutetoDefaultNetwork
09-07 12:06:44.875  1037  1534 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
09-07 12:06:44.875  1037  1534 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-07 12:06:44.876  1037  1534 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-07 12:06:44.876  1037  1534 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-07 12:06:44.876  1037  1534 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
09-07 12:06:44.876  1037  1534 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
09-07 12:06:44.876  1037  1534 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-07 12:06:44.877  1037  1534 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-07 12:06:44.877  1037  1534 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-07 12:06:44.877  1037  1534 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 12:06:44.877  1037  1534 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
09-07 12:06:44.877  1037  1534 D ConnectivityService: currentScore = 0, newScore = 20
09-07 12:06:44.877  1037  8215 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-07 12:06:44.877  1037  1534 D ConnectivityService:    accepting network in place of null
09-07 12:06:44.877  1037  8215 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
09-07 12:06:44.877  1037  1534 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 12:06:44.877  1037  8215 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-07 12:06:44.877  1037  8215 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-07 12:06:44.878  1592  1592 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 12:06:44.878  1592  1592 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-07 12:06:44.878  1037  1527 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 12:06:44.878  1037  1527 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-07 12:06:44.878  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 12:06:44.881  1840  1840 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 12:06:44.881  1840  1840 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-07 12:06:44.882  1037  1534 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,209715,2,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-07 12:06:44.882  1037  1534 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
09-07 12:06:44.882  1037  1534 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-07 12:06:44.882  1037  1534 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-07 12:06:44.882  1037  1534 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
09-07 12:06:44.882   309  8225 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
09-07 12:06:44.883  1037  1534 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
09-07 12:06:44.884  1037  1534 D ConnectivityService: validation of new default Network = false
09-07 12:06:44.884  1037  1534 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
09-07 12:06:44.884  1037  1534 D DSQN    : enableDataServiceNotify 
09-07 12:06:44.884  1037  1534 D DSQN    : start dsqn bin
09-07 12:06:44.886  1037  1037 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
,09-07 12:06:44.889  1037  1037 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-07 12:06:44.889  1037  1037 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-07 12:06:44.889  1037  1037 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-07 12:06:44.891  1037  1534 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
09-07 12:06:44.892  1037  1534 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 12:06:44.892  1037  1534 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-07 12:06:44.892  1037  1534 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-07 12:06:44.893  1592  2035 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-07 12:06:44.884  8227  8227 W dsqn    : type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-07 12:06:44.884  8227  8227 W dsqn    : type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-07 12:06:44.897  1037  1525 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
09-07 12:06:44.912  8227  8227 E DSQN    : DSQN ssw
,09-07 12:06:44.922  1592  1592 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-07 12:06:44.923  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 12:06:44.924  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 12:06:44.937   309  8225 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,09-07 12:06:44.971   309  8225 D libc-netbsd: res_queryN name = clients3.google.com succeed
,09-07 12:06:44.996  6798  6867 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 902)
09-07 12:06:44.997  6798  6867 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 902)
09-07 12:06:44.999   309   893 D LGDataListener: argv[0]=dsqncommand
09-07 12:06:44.999   309   893 D LGDataListener: argv[1]=wlan0
09-07 12:06:44.999   309   893 D LGDataListener: argv[2]=1
09-07 12:06:44.999   309   893 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
09-07 12:06:44.999  1037  1117 D DSQN    : DSQM DsqnNotification wlan0  1
09-07 12:06:44.999  1037  1117 D DSQN    : start to monitor internet connection
,09-07 12:06:45.007  1037  8216 D DhcpStateMachine: DHCPV4 request on wlan0
09-07 12:06:45.007  6798  6867 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 907)
09-07 12:06:45.009  1037  8216 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
09-07 12:06:45.009  1037  8216 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
09-07 12:06:45.009  6798  6867 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-07 12:06:45.010  6798  6867 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 908)
09-07 12:06:45.004  8233  8233 W dhcpcd  : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-07 12:06:45.004  8233  8233 W dhcpcd  : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-07 12:06:45.025  6798  6867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 12:06:45.025  6798  6867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b6623b6 added. We now have 2 listener(s)
09-07 12:06:45.026  1037  2002 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 12:06:45.031  1037  8215 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 07 Sep 2016 10:06:44 GMT], X-Android-Received-Millis=[1473242805030], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473242804997]}
09-07 12:06:45.031  1037  8215 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
,09-07 12:06:45.032  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-07 12:06:45.032  1037  8215 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
09-07 12:06:45.032  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 12:06:45.032  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 12:06:45.033  6798  6867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 12:06:45.033  6798  6867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e22d8b7 added. We now have 9 listener(s)
09-07 12:06:45.033  8233  8233 I dhcpcd  : version 5.5.6 starting
09-07 12:06:45.033  6798  6867 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 12:06:45.033  1037  1534 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
09-07 12:06:45.033  1037  1534 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
09-07 12:06:45.033  1037  1534 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-07 12:06:45.033  1037  1534 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-07 12:06:45.033  1037  1534 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-07 12:06:45.034  8233  8233 E dhcpcd  : get_duid: m
09-07 12:06:45.034  8233  8233 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
09-07 12:06:45.034  8233  8233 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
09-07 12:06:45.034  1037  1534 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
,09-07 12:06:45.034  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-07 12:06:45.034  1037  1534 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
09-07 12:06:45.034  1037  1534 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 12:06:45.034  1037  1534 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-07 12:06:45.036  1037  1534 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-07 12:06:45.037  1592  2035 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-07 12:06:45.037  1037  1534 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 12:06:45.038  6798  6867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 12:06:45.039  1037  1527 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 12:06:45.039  1037  1527 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-07 12:06:45.039  1840  1840 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 12:06:45.039  1840  1840 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-07 12:06:45.039  1037  1534 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-07 12:06:45.043  6798  6867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 12:06:45.043  6798  6867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:06:45.043  6798  6867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 12:06:45.043  6798  6867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 12:06:45.043  6798  6867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 12:06:45.043  6798  6867 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 12:06:45.043  6798  6867 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 12:06:45.043  6798  6867 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 12:06:45.044  6798  6867 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 12:06:45.045  6798  6867 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 12:06:45.045  6798  6867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 12:06:45.045  6798  6867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28530f8d added. We now have 3 listener(s)
09-07 12:06:45.047  6798  6798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 12:06:45.047  1037  1053 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-07 12:06:45.051  6798  6798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 12:06:45.056  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-07 12:06:45.056  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 12:06:45.056  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 12:06:45.056  6798  6867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 12:06:45.056  6798  6867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e28c542 added. We now have 10 listener(s)
09-07 12:06:45.056  6798  6867 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 12:06:45.056  6798  6867 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 12:06:45.056  6798  6867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 12:06:45.056  6798  6867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 12:06:45.056  6798  6867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:06:45.056  6798  6867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:06:45.056  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 12:06:45.056  6798  6867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 12:06:45.056  6798  6867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b6623b6 removed from the list
09-07 12:06:45.056  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:06:45.057  6798  6867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e22d8b7 removed from the list
09-07 12:06:45.057  6798  6867 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:06:45.057  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:06:45.057  6798  6867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:06:45.057  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:06:45.059  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 12:06:45.060  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 12:06:45.060  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:06:45.060  6798  6867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e22d8b7 not in the list
09-07 12:06:45.060  6798  6867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:06:45.060  6798  6867 D org.thaliproject.p2p.btconnector,lib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:06:45.060  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 12:06:45.060  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 12:06:45.060  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 12:06:45.060  6798  6867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e28c542 removed from the list
09-07 12:06:45.060  6798  6867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:06:45.060  6798  6867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:06:45.060  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:06:45.060  6798  6867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 12:06:45.060  6798  6867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28530f8d removed from the list
09-07 12:06:45.061  6798  6867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 12:06:45.061  6798  6867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6824953 added. We now have 2 listener(s)
09-07 12:06:45.061  1037  1564 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 12:06:45.064  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-07 12:06:45.064  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 12:06:45.064  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 12:06:45.064  6798  6867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 12:06:45.064  6798  6867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@102b290 added. We now have 9 listener(s)
09-07 12:06:45.064  6798  6867 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 12:06:45.065  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-07 12:06:45.067  6798  6867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 12:06:45.072  6798  6867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 12:06:45.072  6798  6867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:06:45.072  6798  6867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 12:06:45.072  6798  6867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 12:06:45.072  6798  6867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 12:06:45.072  6798  6867 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 12:06:45.072  6798  6867 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 12:06:45.072  6798  6867 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 12:06:45.073  1592  1592 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-07 12:06:45.074  6798  6867 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 12:06:45.074  6798  6867 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 12:06:45.075  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 12:06:45.075  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 12:06:45.076  6798  6798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 12:06:45.078  6798  6798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 12:06:45.078  6798  6867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 12:06:45.078  6798  6867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c81f38e added. We now have 3 listener(s)
09-07 12:06:45.078  1037  1929 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 12:06:45.080  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-07 12:06:45.080  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 12:06:45.080  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 12:06:45.081  8233  8233 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-07 12:06:45.081  8233  8233 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-07 12:06:45.081  8233  8233 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,09-07 12:06:45.081  8233  8233 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
09-07 12:06:45.081  8233  8233 D dhcpcd  : wlan0: sending REQUEST (xid 0x744c5c16), next in 4.11 seconds
09-07 12:06:45.081  6798  6867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 12:06:45.081  6798  6867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@95e27af added. We now have 10 listener(s)
09-07 12:06:45.081  6798  6867 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 12:06:45.082  6798  6867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 12:06:45.082  6798  6867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-07 12:06:45.082  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-07 12:06:45.082  6798  6867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 12:06:45.082  6798  6867 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-07 12:06:45.084  6798  6867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-07 12:06:45.085  1037  2039 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-07 12:06:45.088  6798  6867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-07 12:06:45.088  6798  6867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-07 12:06:45.089  6798  6867 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-07 12:06:45.090  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 12:06:45.091  6798  6867 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-07 12:06:45.091  6798  6867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 12:06:45.091  6798  6867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 12:06:45.092  6798  6867 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 12:06:45.092  6798  6867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 12:06:45.092  6798  6867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 12:06:45.092  6798  6867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:06:45.092  6798  6867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:06:45.092  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 12:06:45.092  6798  6867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 12:06:45.092  6798  6867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6824953 removed from the list
09-07 12:06:45.093  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:06:45.093  6798  6867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@102b290 removed from the list
09-07 12:06:45.093  6798  6867 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:06:45.093  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:06:45.093  8198  8198 W ExternalStrings: load override strings
09-07 12:06:45.093  8198  8198 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
09-07 12:06:45.093  8198  8198 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
09-07 12:06:45.093  8198  8198 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
09-07 12:06:45.093  8198  8198 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
09-07 12:06:45.093  8198  8198 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
09-07 12:06:45.093  8198  8198 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
09-07 12:06:45.093  8198  8198 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
09-07 12:06:45.093  8198  8198 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
09-07 12:06:45.093  8198  8198 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
09-07 12:06:45.093  8198  8,198 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
09-07 12:06:45.093  8198  8198 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
09-07 12:06:45.093  8198  8198 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 12:06:45.093  8198  8198 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
09-07 12:06:45.093  8198  8198 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-07 12:06:45.093  8198  8198 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 12:06:45.093  8198  8198 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 12:06:45.093  8198  8198 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-07 12:06:45.093  8198  8198 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-07 12:06:45.094  6798  6867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:06:45.094  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:06:45.094  8198  8198 D StatusProvider: onCreate
,09-07 12:06:45.095  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 12:06:45.095  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 12:06:45.095  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:06:45.095  6798  6867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@102b290 not in the list
09-07 12:06:45.095  6798  6867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:06:45.095  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:06:45.095  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 12:06:45.096  6798  6867 D BluetoothLeScanner: could not find callback wrapper
09-07 12:06:45.096  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 12:06:45.096  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 12:06:45.096  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:06:45.096  6798  6867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@95e27af removed from the list
09-07 12:06:45.096  6798  6867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:06:45.096  6798  6867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:06:45.096  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:06:45.096  6798  6867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 12:06:45.096  6798  6867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c81f38e removed from the list
09-07 12:06:45.096  6798  6867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 12:06:45.096  6798  6867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c2dba9a added. We now have 2 listener(s)
09-07 12:06:45.096  1037  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 12:06:45.098  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-07 12:06:45.098  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 12:06:45.098  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 12:06:45.098  6798  6867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 12:06:45.098  6798  6867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6f8fcb added. We now have 9 listener(s)
09-07 12:06:45.098  6798  6867 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 12:06:45.098  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-07 12:06:45.099  6798  6867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothM,anager: bind: Binding a new listener
09-07 12:06:45.101  6798  6867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 12:06:45.101  6798  6867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:06:45.101  6798  6867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 12:06:45.101  6798  6867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 12:06:45.101  6798  6867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 12:06:45.101  6798  6867 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 12:06:45.101  6798  6867 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 12:06:45.101  6798  6867 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 12:06:45.102  6798  6867 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 12:06:45.103  6798  6867 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 12:06:45.103  6798  6867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 12:06:45.103  6798  6867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35942ec1 added. We now have 3 listener(s)
09-07 12:06:45.103  1037  1929 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 12:06:45.104  6798  6798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 12:06:45.105  6798  6798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 12:06:45.105  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-07 12:06:45.105  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 12:06:45.106  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 12:06:45.106  6798  6867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 12:06:45.106  6798  6867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@209ce666 added. We now have 10 listener(s)
09-07 12:06:45.106  6798  6867 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 12:06:45.106  6798  6867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only,
09-07 12:06:45.106  6798  6867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 12:06:45.106  6798  6867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-07 12:06:45.106  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-07 12:06:45.106  6798  6867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 12:06:45.106  6798  6867 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-07 12:06:45.108  6798  6867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-07 12:06:45.108  1037  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 12:06:45.110  6798  6867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-07 12:06:45.110  6798  6867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-07 12:06:45.111  6798  6867 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-07 12:06:45.111  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 12:06:45.113  6798  6867 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-07 12:06:45.113  6798  6867 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 12:06:45.113  6798  6867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 12:06:45.113  6798  6867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 12:06:45.113  6798  6867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:06:45.113  6798  6867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 12:06:45.113  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 12:06:45.113  6798  6867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 12:06:45.113  6798  6867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c2dba9a removed from the list
09-07 12:06:45.113  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 12:06:45.113  6798  6867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6f8fcb removed from the list
09-07 12:06:45.113  6798  6867 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:06:45.113  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:06:45.113  6798  6867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:06:45.113  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:06:45.115  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 12:06:45.115  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 12:06:45.115  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:06:45.115  6798  6867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6f8fcb not in the list
09-07 12:06:45.115  6798  6867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:06:45.115  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:06:45.115  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 12:06:45.116  6798  6867 D BluetoothLeScanner: could not find callback wrapper
09-07 12:06:45.116  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 12:06:45.116  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 12:06:45.116  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:06:45.116  6798  6867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@209ce666 removed from the list
09-07 12:06:45.116  6798  6867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:06:45.116  6798  6867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:06:45.116  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:06:45.116  6798  6867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 12:06:45.116  6798  6867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35942ec1 removed from the list
09-07 12:06:45.116  6798  6867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 12:06:45.116  6798  6867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ef3f5fd added. We now have 2 listener(s)
09-07 12:06:45.116  1037  1964 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 12:06:45.118  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-07 12:06:45.118  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 12:06:45.118  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdent,ityString: 
09-07 12:06:45.118  6798  6867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 12:06:45.118  6798  6867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@118102f2 added. We now have 9 listener(s)
09-07 12:06:45.118  6798  6867 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 12:06:45.118  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-07 12:06:45.119  6798  6867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 12:06:45.121  6798  6867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 12:06:45.121  6798  6867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:06:45.121  6798  6867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 12:06:45.121  6798  6867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 12:06:45.121  6798  6867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 12:06:45.121  6798  6867 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 12:06:45.121  6798  6867 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 12:06:45.121  6798  6867 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 12:06:45.122  6798  6867 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 12:06:45.122  6798  6867 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 12:06:45.123  6798  6798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 12:06:45.124  6798  6867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 12:06:45.124  6798  6867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1eafdfc0 added. We now have 3 listener(s)
09-07 12:06:45.124  6798  6798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 12:06:45.124  1037  1774 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 12:06:45.126  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-07 12:06:45.126  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 12:06:45.126  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 12:06:45.126  6798  6867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 12:06:45.126  6798  6867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@358ef4f9 added. We now have 10 listener(s)
09-07 12:06:45.126  6798  6867 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 12:06:45.126  6798  6867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 12:06:45.126  6798  6867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Execut,ing: Start operation: Should affect listening to advertisements only
09-07 12:06:45.126  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-07 12:06:45.126  6798  6867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 12:06:45.126  6798  6867 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-07 12:06:45.128  6798  6867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-07 12:06:45.128  1037  2002 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 12:06:45.130  8233  8233 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
09-07 12:06:45.131  6798  6867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-07 12:06:45.131  6798  6867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-07 12:06:45.132  6798  6867 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-07 12:06:45.132  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 12:06:45.133  6798  6867 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-07 12:06:45.134  6798  6867 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 12:06:45.134  6798  6867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 12:06:45.134  6798  6867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 12:06:45.135  6798  6867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:06:45.135  6798  6867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:06:45.135  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 12:06:45.135  6798  6867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 12:06:45.135  6798  6867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ef3f5fd removed from the list
09-07 12:06:45.135  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:06:45.135  6798  6867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@118102f2 removed from the list
09-07 12:06:45.135  6798  6867 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:06:45.135  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:06:45.135  6798  6867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:06:45.135  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:06:45.135  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 12:06:45.135  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 12:06:45.135  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:06:45.135  6798  6867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@118102f2 not in the list
09-07 12:06:45.135  6798  6867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:06:45.135  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:06:45.136  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 12:06:45.136  6798  6867 D BluetoothLeScanner: could not find callback wrapper
09-07 12:06:45.136  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 12:06:45.136  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 12:06:45.136  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:06:45.136  6798  6867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@358ef4f9 removed from the list
09-07 12:06:45.136  6798  6867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:06:45.136  6798  6867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:06:45.136  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:06:45.136  6798  6867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 12:06:45.136  6798  6867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1eafdfc0 removed from the list
09-07 12:06:45.137  6798  6867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 12:06:45.137  6798  6867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e9337ec added. We now have 2 listener(s)
09-07 12:06:45.137  1037  1964 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 12:06:45.138  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-07 12:06:45.138  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 12:06:45.138  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 12:06:45.138  6798  6867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 12:06:45.138  6798  6867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c40e7b5 added. We now have 9 listener(s)
09-07 12:06:45.138  6798  6867 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 12:06:45.138  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-07 12:06:45.140  6798  6867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 12:06:45.142  8198  8198 V Signer  : override build config not found
09-07 12:06:45.143  6798  6867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 12:06:45.143  6798  6867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:06:45.143  6798  6867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 12:06:45.143  6798  6867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 12:06:45.143  6798  6867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 12:06:45.143  6798  6867 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 12:06:45.143  6798  6867 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 12:06:45.143  6798  6867 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 12:06:45.143  8198  8198 D Signer  : value of property debug is false
09-07 12:06:45.143  6798  6867 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 12:06:45.144  6798  6867 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 12:06:45.144  6798  6867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 12:06:45.144  6798  6867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@306801bb added. We now have 3 listener(s)
09-07 12:06:45.144  1037  1911 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 12:06:45.145  6798  6798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 12:06:45.146  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-07 12:06:45.146  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 12:06:45.146  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 12:06:45.146  6798  6867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 12:06:45.146  6798  6867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e71e6d8 added. We now have 10 listener(s)
09-07 12:06:45.146  6798  6867 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 12:06:45.146  6798  6798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 12:06:45.146  6798  6867 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 12:06:45.147  6798  6867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 12:06:45.147  6798  6867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 12:06:45.147  6798  6867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:06:45.147  6798  6867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:06:45.147  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 12:06:45.147  6798  6867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 12:06:45.147  6798  6867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e9337ec removed from the list
09-07 12:06:45.147  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:06:45.147  6798  6867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c40e7b5 removed from the list
09-07 12:06:45.147  6798  6867 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:06:45.147  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:06:45.147  6798  6867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:06:45.147  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:06:45.148  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 12:06:45.148  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 12:06:45.148  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:06:45.148  6798  6867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c40e7b5 not in the list
09-07 12:06:45.148  6798  6867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:06:45.148  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:06:45.148  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 12:06:45.148  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 12:06:45.148  6798  6867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:06:45.148  6798  6867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e71e6d8 removed from the list
09-07 12:06:45.148  6798  6867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:06:45.148  6798  6867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:06:45.148  6798  6867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:06:45.148  6798  6867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 12:06:45.148  6798  6867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@306801bb removed from the list
09-07 12:06:45.149  6798  6867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-07 12:06:45.149  6798  6867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-07 12:06:45.149  6798  6867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-07 12:06:45.149  6798  6867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 12:06:45.149  6798  6867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-07 12:06:45.149  6798  6867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-07 12:06:45.155  6798  8240 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 915, name: My test thread name)
09-07 12:06:45.156  6798  8240 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 915, thread name: My test thread name)
09-07 12:06:45.156  6798  8240 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 915, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
09-07 12:06:45.158  6798  8241 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 917, name: My test thread name)
09-07 12:06:45.159  6798  8241 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 917, thread name: My test thread name)
09-07 12:06:45.159  6798  8241 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 917, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
09-07 12:06:45.162  6798  6867 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
09-07 12:06:45.162  6798  6867 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-07 12:06:45.162  6798  6867 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-07 12:06:45.162  6798  6867 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-07 12:06:45.163  6798  6867 D com.test.thalitest.ThaliTestRunner: Total duration: 23042 ms
09-07 12:06:45.165  6798  6867 I jxcore-log: *Native tests were executed*
09-07 12:06:45.165  6798  6867 I jxcore-log: 
09-07 12:06:45.165  6798  6867 I jxcore-log: Total number of executed tests:  80
09-07 12:06:45.165  6798  6867 I jxcore-log: 
09-07 12:06:45.165  6798  6867 I jxcore-log: Number of passed tests:  80
09-07 12:06:45.165  6798  6867 I jxcore-log: 
09-07 12:06:45.165  6798  6867 I jxcore-log: Number of failed tests:  0
09-07 12:06:45.165  6798  6867 I jxcore-log: 
09-07 12:06:45.165  6798  6867 I jxcore-log: Number of ignored tests:  0
09-07 12:06:45.165  6798  6867 I jxcore-log: 
09-07 12:06:45.166  6798  6867 I jxcore-log: Total duration:  23042
09-07 12:06:45.166  6798  6867 I jxcore-log: 
09-07 12:06:45.166  6798  6867 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-07 12:06:45.166  6798  6867 I jxcore-log: 
,09-07 12:06:45.171  6798  6867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 12:06:45.171  6798  6867 I jxcore-log: 
09-07 12:06:45.173  6798  6867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 12:06:45.173  6798  6867 I jxcore-log: 
09-07 12:06:45.174  6798  6867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 12:06:45.174  6798  6867 I jxcore-log: 
09-07 12:06:45.174  6798  6867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 12:06:45.174  6798  6867 I jxcore-log: 
09-07 12:06:45.175  6798  6867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 12:06:45.175  6798  6867 I jxcore-log: 
09-07 12:06:45.176  6798  6867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 12:06:45.176  6798  6867 I jxcore-log: 
09-07 12:06:45.178  6798  6867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-07 12:06:45.178  6798  6867 I jxcore-log: 
09-07 12:06:45.179  6798  6867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-07 12:06:45.179  6798  6867 I jxcore-log: 
09-07 12:06:45.179  6798  6867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-07 12:06:45.179  6798  6867 I jxcore-log: 
09-07 12:06:45.180  6798  6867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-07 12:06:45.180  6798  6867 I jxcore-log: 
09-07 12:06:45.181  6798  6867 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-07 12:06:45.181  6798  6867 I jxcore-log: 
09-07 12:06:45.181  6798  6867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-07 12:06:45.181  6798  6867 I jxcore-log: 
09-07 12:06:45.182  6798  6867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-07 12:06:45.182  6798  6867 I jxcore-log: 
09-07 12:06:45.182  6798  6867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-07 12:06:45.182  6798  6867 I jxcore-log: 
09-07 12:06:45.183  6798  6867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-07 12:06:45.183  6798  6867 I jxcore-log: 
09-07 12:06:45.183  6798  6798 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-07 12:06:45.183  6798  6867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-07 12:06:45.183  6798  6867 I jxcore-log: 
09-07 12:06:45.183  8198  8198 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
09-07 12:06:45.183  8233  8233 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
09-07 12:06:45.183  8233  8233 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
09-07 12:06:45.184  8198  8198 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
09-07 12:06:45.184  8233  8233 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
09-07 12:06:45.184  8233  8233 D dhcpcd  : wlan0: adding default route via 192.168.1.1
09-07 12:06:45.184  6798  6867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-07 12:06:45.184  6798  6867 I jxcore-log: 
09-07 12:06:45.184  8198  8198 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
09-07 12:06:45.184  8233  8233 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-07 12:06:45.184  8198  8198 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
09-07 12:06:45.184  8233  8233 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-07 12:06:45.184  8233  8233 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-07 12:06:45.184  6798  6867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-07 12:06:45.184  6798  6867 I jxcore-log: 
09-07 12:06:45.184  8233  8233 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
09-07 12:06:45.184  8198  8198 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
09-07 12:06:45.185  8198  8198 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
09-07 12:06:45.185  6798  6867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-07 12:06:45.185  6798  6867 I jxcore-log: 
09-07 12:06:45.185  6798  6867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-07 12:06:45.185  6798  6867 I jxcore-log: 
09-07 12:06:45.186  6798  6867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-07 12:06:45.186  6798  6867 I jxcore-log: 
09-07 12:06:45.186  6798  6867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-07 12:06:45.186  6798  6867 I jxcore-log: 
09-07 12:06:45.187  6798  6867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-07 12:06:45.187  6798  6867 I jxcore-log: 
09-07 12:06:45.187  6798  6867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 12:06:45.187  6798  6867 I jxcore-log: 
09-07 12:06:45.188  6798  6867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 12:06:45.188  6798  6867 I jxcore-log: 
09-07 12:06:45.188  6798  6867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 12:06:45.188  6798  6867 I jxcore-log: 
09-07 12:06:45.188  6798  6867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 12:06:45.188  6798  6867 I jxcore-log: 
09-07 12:06:45.189  6798  6867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 12:06:45.189  6798  6867 I jxcore-log: 
09-07 12:06:45.191  8198  8198 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
09-07 12:06:45.191  8198  8198 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
09-07 12:06:45.192  8198  8198 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
09-07 12:06:45.192  8198  8198 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
09-07 12:06:45.192  8198  8198 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
09-07 12:06:45.192  8198  8198 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
09-07 12:06:45.193  8198  8198 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
09-07 12:06:45.206  8198  8198 V LGMDMManager: Create singleton instance
,09-07 12:06:45.266  8198  8198 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
,09-07 12:06:45.313  8198  8198 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-07 12:06:45.315  8198  8260 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-07 12:06:45.320  6889  6889 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-07 12:06:45.325  6889  6889 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-07 12:06:45.374  1037  1564 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=8269 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,09-07 12:06:45.375  1037  1564 I ActivityManager: Killing 7276:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
09-07 12:06:45.388   351   351 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 259us total 13.456ms
,09-07 12:06:45.400   351   351 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 233us total 11.503ms
09-07 12:06:45.411   351   351 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 232us total 10.930ms
,09-07 12:06:45.416  1037  8216 D DhcpStateMachine: DHCPV4 succeeded on wlan0
09-07 12:06:45.417  1037  8216 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
09-07 12:06:45.417  1037  8216 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-07 12:06:45.417  1037  8216 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
09-07 12:06:45.417  1037  8216 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
09-07 12:06:45.417  1037  8216 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-07 12:06:45.417  1037  8216 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
09-07 12:06:45.417  1037  8216 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
09-07 12:06:45.417  1037  8216 D DhcpStateMachine: RunningState
09-07 12:06:45.439  8198  8259 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,09-07 12:06:45.493  8250  8250 D AndroidRuntime: 
09-07 12:06:45.493  8250  8250 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,09-07 12:06:45.497  8250  8250 D AndroidRuntime: CheckJNI is OFF
09-07 12:06:45.655  1037  1875 W libprocessgroup: failed to open /acct/uid_10093/pid_7276/cgroup.procs: No such file or directory
,09-07 12:06:45.714  8269  8269 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-07 12:06:45.731  8250  8250 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-07 12:06:45.744  1037  1100 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
09-07 12:06:45.744  1037  1100 I ActivityManager: Killing 6798:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,09-07 12:06:45.804  1037  1929 I WindowState: WIN DEATH: Window{8d3ed7d u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-07 12:06:45.805  1037  1533 D WifiService: Client connection lost with reason: 4
,09-07 12:06:45.813  1037  1929 D InputDispatcher: Window went away: Window{8d3ed7d u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-07 12:06:45.897  8198  8259 D LgDataFeature: LgDataFeature() Constructor: none
,09-07 12:06:45.897  8198  8259 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-07 12:06:46.022  8198  8259 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
,09-07 12:06:46.036  1037  1100 I ActivityManager:   Force finishing activity ActivityRecord{3293505e u0 com.test.thalitest/.MainActivity t6}
,09-07 12:06:46.062   346   356 E GBMv2   : DFP En is all cleared set to be enabled
09-07 12:06:46.068  1037  2001 W ActivityManager: Spurious death for ProcessRecord{9b009a9 6798:com.test.thalitest/u0a118}, curProc for 6798: null
,09-07 12:06:46.069  1037  1125 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
09-07 12:06:46.073  8269  8269 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,09-07 12:06:46.074  1037  1125 I ActivityManager:   Force finishing activity ActivityRecord{3293505e u0 com.test.thalitest/.MainActivity t6 f}
09-07 12:06:46.074  1037  1125 W ActivityManager: Duplicate finish request for ActivityRecord{3293505e u0 com.test.thalitest/.MainActivity t6 f}
,09-07 12:06:46.103  2021  2021 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
09-07 12:06:46.104  1930  4431 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
09-07 12:06:46.104  1930  4431 D SplitWindowPolicy: topRunningActivity=ActivityInfo{aadbf14 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
09-07 12:06:46.104  2021  2021 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
,09-07 12:06:46.111  1930  1946 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
09-07 12:06:46.111  2021  2021 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
09-07 12:06:46.112  1930  1946 D SplitWindowPolicy: topRunningActivity=ActivityInfo{19aaa3bd co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
09-07 12:06:46.112  2021  2131 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
09-07 12:06:46.121  1894  1894 D ActionManagerService: notifyUserLog: 1000003
09-07 12:06:46.121  2021  2021 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
09-07 12:06:46.122  3809  4935 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
09-07 12:06:46.123  1592  1592 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,09-07 12:06:46.126  1984  1984 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
09-07 12:06:46.127  3809  3809 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
09-07 12:06:46.128  7753  7753 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
09-07 12:06:46.129  7753  7753 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
09-07 12:06:46.132  2488  2595 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-07 12:06:46.134  2021  2021 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
09-07 12:06:46.142  4944  4944 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,09-07 12:06:46.142  4944  4944 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
09-07 12:06:46.143  4944  4944 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
09-07 12:06:46.143  4944  4944 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
09-07 12:06:46.143  4944  4944 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-07 12:06:46.143  4944  4944 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-07 12:06:46.143  4944  4944 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-07 12:06:46.143  4944  4944 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-07 12:06:46.143  4944  4944 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 12:06:46.143  4944  4944 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 12:06:46.143  4944  4944 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-07 12:06:46.143  4944  4944 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-07 12:06:46.155  1037  1427 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-07 12:06:46.160  5062  5062 I art     : Explicit concurrent mark sweep GC freed 8196(467KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 11.174ms total 72.729ms
,09-07 12:06:46.164  8269  8269 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
09-07 12:06:46.165  8269  8269 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
09-07 12:06:46.165  8269  8269 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
09-07 12:06:46.165  8269  8269 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
09-07 12:06:46.165  8269  8269 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
09-07 12:06:46.167  8269  8269 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
09-07 12:06:46.189  1037  1893 V SIM_STK : Menu title from STK is T-Mobile
,09-07 12:06:46.196  2021  2021 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
09-07 12:06:46.197  2021  2021 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
09-07 12:06:46.200  8269  8269 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
09-07 12:06:46.211  1037  1037 D administrator: Handling package changes for user 0
,09-07 12:06:46.215  1592  1592 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
09-07 12:06:46.215  2021  2021 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
09-07 12:06:46.216  1894  1894 D ActionManagerService: notifyUserLog: 1000004
09-07 12:06:46.216  3809  4935 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
09-07 12:06:46.217  1592  1641 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-07 12:06:46.217  1592  1641 D KeyguardModel: createShortcutInfo...
09-07 12:06:46.218  3809  4936 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-07 12:06:46.220  2021  2021 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
09-07 12:06:46.220  2021  2021 I GBoardWebViewUtils: , create_time: 1430832262123
09-07 12:06:46.220  2021  2021 I GBoardWebViewUtils: , expire_time: 0
09-07 12:06:46.220  2021  2021 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
09-07 12:06:46.220  2021  2021 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
09-07 12:06:46.220  2021  2021 I GBoardWebViewUtils: , display: false
09-07 12:06:46.220  2021  2021 I GBoardWebViewUtils: , animation: false }
09-07 12:06:46.220  2021  2021 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
09-07 12:06:46.220  2021  2021 I GBoardWebViewUtils: , create_time: 1430832262287
09-07 12:06:46.220  2021  2021 I GBoardWebViewUtils: , expire_time: 0
09-07 12:06:46.220  2021  2021 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
09-07 12:06:46.220  2021  2021 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
09-07 12:06:46.220  2021  2021 I GBoardWebViewUtils: , display: false
09-07 12:06:46.220  2021  2021 I GBoardWebViewUtils: , animation: false }
09-07 12:06:46.220  2021  2021 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1472828323135
09-07 12:06:46.220  2021  2021 I GBoardWebViewUtils: , create_time: 1472828323917
09-07 12:06:46.220  2021  2021 I GBoardWebViewUtils: , expire_time: 0
09-07 12:06:46.220  2021  2021 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide.html?id=guide_1111111111116_1472828323135&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
09-07 12:06:46.220  2021  2021 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
09-07 12:06:46.220  2021  2021 I GBoardWebViewUtils: , display: false
09-07 12:06:46.220  2021  2021 I GBoardWebViewUtils: , animation: false }
09-07 12:06:46.221  8198  8259 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
09-07 12:06:46.227  1592  1641 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
,09-07 12:06:46.227  1592  1641 D KeyguardModel: createShortcutInfo...
09-07 12:06:46.231  1592  1641 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
09-07 12:06:46.231  1592  1641 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-07 12:06:46.233  1592  1641 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
09-07 12:06:46.239  2021  8316 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
09-07 12:06:46.240  1592  1641 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-07 12:06:46.240  1592  1641 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-07 12:06:46.240  1592  1641 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
09-07 12:06:46.241  1592  1592 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
09-07 12:06:46.242  1592  1592 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
09-07 12:06:46.245  1592  1641 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-07 12:06:46.245  1592  1641 D KeyguardModel: createShortcutInfo...
,09-07 12:06:46.247  2021  2021 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
09-07 12:06:46.250  1592  1641 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
09-07 12:06:46.250  1592  1641 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-07 12:06:46.251  1592  1641 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-07 12:06:46.251  1592  1641 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
09-07 12:06:46.252  1037  2039 V SIM_STK : Menu title from STK is T-Mobile
09-07 12:06:46.252  1037  2039 V SIM_STK : Menu title from STK is T-Mobile
09-07 12:06:46.298  1857  1857 D SplitUIManager: split_name #11 / not available #0
09-07 12:06:46.298  1857  1857 D SplitUIService: removed split : 
,09-07 12:06:46.309  1592  1641 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-07 12:06:46.309  1592  1641 D KeyguardModel: createShortcutInfo...
09-07 12:06:46.313  1592  1641 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-07 12:06:46.314  1592  1641 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-07 12:06:46.314  1592  1641 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
09-07 12:06:46.314  1592  1641 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-07 12:06:46.323  1592  1641 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-07 12:06:46.323  1592  1641 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
09-07 12:06:46.324  1037  1694 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
09-07 12:06:46.324  8198  8259 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
09-07 12:06:46.325  7753  7753 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
09-07 12:06:46.325  7753  7753 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-07 12:06:46.325  7753  7753 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-07 12:06:46.325  7753  7753 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-07 12:06:46.325  7753  7753 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-07 12:06:46.325  7753  7753 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
,09-07 12:06:46.325  7753  7753 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-07 12:06:46.325  7753  7753 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-07 12:06:46.325  7753  7753 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-07 12:06:46.325  7753  7753 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-07 12:06:46.325  7753  7753 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-07 12:06:46.326  2021  2021 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,09-07 12:06:46.327  1592  1641 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-07 12:06:46.327  1592  1641 D KeyguardModel: createShortcutInfo...
09-07 12:06:46.328  2021  2021 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
09-07 12:06:46.336  1592  1592 D KeyguardModel: handleShortcutListChanged...
09-07 12:06:46.336  1592  1592 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
09-07 12:06:46.338  1857  1857 D SplitUIManager: split_name #11 / not available #0
09-07 12:06:46.338  8269  8269 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-07 12:06:46.338  1857  1857 I SplitUIService: split app #11
09-07 12:06:46.339  1037  1774 V SIM_STK : Menu title from STK is T-Mobile
09-07 12:06:46.340  1592  1641 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-07 12:06:46.340  1592  1641 D KeyguardModel: createShortcutInfo...
,09-07 12:06:46.342  8198  8259 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
09-07 12:06:46.343  8198  8259 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
09-07 12:06:46.343  8198  8259 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
09-07 12:06:46.343  8198  8259 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
09-07 12:06:46.344  8269  8269 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-07 12:06:46.346  1592  1641 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-07 12:06:46.346  1592  1641 D KeyguardModel: createShortcutInfo...
09-07 12:06:46.347  1592  1641 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-07 12:06:46.347  1592  1641 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
09-07 12:06:46.348  1592  1641 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-07 12:06:46.348  1592  1641 D KeyguardModel: createShortcutInfo...
09-07 12:06:46.349  1592  1641 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-07 12:06:46.349  1592  1641 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
09-07 12:06:46.350  1592  1641 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-07 12:06:46.350  1592  1641 D KeyguardModel: createShortcutInfo...
09-07 12:06:46.351  1592  1641 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-07 12:06:46.351  1592  1641 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
09-07 12:06:46.355  1592  1641 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-07 12:06:46.355  1592  1641 D KeyguardModel: createShortcutInfo...
,09-07 12:06:46.365  8198  8259 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
09-07 12:06:46.366  8198  8259 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
09-07 12:06:46.368  1592  1592 D KeyguardModel: handleShortcutListChanged...
09-07 12:06:46.368  1592  1592 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
09-07 12:06:46.371  1037  1037 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
09-07 12:06:46.371  1037  1037 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-07 12:06:46.371  1037  1037 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-07 12:06:46.373  1037  1566 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
09-07 12:06:46.383  1037  1527 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-07 12:06:46.383  1037  1527 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-07 12:06:46.383  1037  1527 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-07 12:06:46.383  8269  8269 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-07 12:06:46.383  1037  1527 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,09-07 12:06:46.384  1037  1527 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-07 12:06:46.384  1037  1527 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-07 12:06:46.384  1037  1099 W InputMethodInfo: Duplicated subtype definition found: , voice
09-07 12:06:46.385  8269  8269 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
09-07 12:06:46.386  1037  1534 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
09-07 12:06:46.386  1037  1534 D ConnectivityService: identical MTU - not setting
09-07 12:06:46.386  1037  1534 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-07 12:06:46.386  1037  1534 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-07 12:06:46.386  1037  1534 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 12:06:46.386  1037  1534 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-07 12:06:46.386  1037  1534 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
09-07 12:06:46.387  1592  2035 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
09-07 12:06:46.391  8198  8198 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-07 12:06:46.391  8198  8260 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-07 12:06:46.397  2021  2021 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
09-07 12:06:46.397  6889  6889 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-07 12:06:46.401  2021  2021 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-07 12:06:46.402  2021  2021 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
09-07 12:06:46.403  2021  2021 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
09-07 12:06:46.404  2021  2021 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
09-07 12:06:46.405  2021  2021 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
,09-07 12:06:46.413  6889  6889 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 12:06:46.414  8269  8269 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
09-07 12:06:46.431  2021  2021 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
09-07 12:06:46.432  2021  2021 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,09-07 12:06:46.433  2021  2299 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
09-07 12:06:46.433  2021  2299 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
09-07 12:06:46.437  1037  1120 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{33dc7aba u0 com.lge.launcher2/.Launcher t5} time:200665
,09-07 12:06:46.437  8269  8269 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-07 12:06:46.437  8269  8269 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-07 12:06:46.438  8269  8269 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-07 12:06:46.440  6889  6889 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
09-07 12:06:46.441  6889  6889 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
09-07 12:06:46.443  8198  8198 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-07 12:06:46.443  8198  8260 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,09-07 12:06:46.447  6889  6889 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-07 12:06:46.451  2021  2021 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
09-07 12:06:46.452  2021  2021 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
09-07 12:06:46.452  2021  2021 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,09-07 12:06:46.459  6889  6889 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 12:06:46.461  2021  2021 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
09-07 12:06:46.462  2667  2667 D [Concierge]Service: onStartCommand(). Type : 8
09-07 12:06:46.462  2667  2667 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
09-07 12:06:46.463  2667  2667 D [Concierge]Service: Update widget ID : 11
09-07 12:06:46.464  8269  8269 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-07 12:06:46.464  8269  8269 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-07 12:06:46.464  8269  8269 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-07 12:06:46.466  6889  6889 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-07 12:06:46.466  6889  6889 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-07 12:06:46.466  6889  6889 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-07 12:06:46.466  2021  2021 D [Concierge]WidgetView: change position of spinner
09-07 12:06:46.466  6889  6889 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-07 12:06:46.466  6889  6889 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-07 12:06:46.467  2021  2021 I [Concierge]WidgetView: initWebView(). Time : 1473242806467
09-07 12:06:46.467  6889  6889 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-07 12:06:46.467  6889  6889 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
09-07 12:06:46.467  6889  6889 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-07 12:06:46.467  6889  6889 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-07 12:06:46.467  6889  6889 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-07 12:06:46.467  6889  6889 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
09-07 12:06:46.467  6889  6889 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-07 12:06:46.467  2667  2667 D [Concierge]Service: onStartCommand(). Type : 0
09-07 12:06:46.470  8198  8198 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-07 12:06:46.475  6889  6889 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-07 12:06:46.476  8198  8260 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-07 12:06:46.479  6889  6889 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 12:06:46.483  1037  1125 I art     : Explicit concurrent mark sweep GC freed 81023(4MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/65MB, paused 22.821ms total 375.679ms
09-07 12:06:46.484  8269  8269 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-07 12:06:46.484  8269  8269 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-07 12:06:46.484  8269  8269 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-07 12:06:46.486  8198  8198 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-07 12:06:46.486  8198  8260 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-07 12:06:46.491  2021  2021 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 804326956
09-07 12:06:46.491  2021  2021 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
09-07 12:06:46.491  2021  2021 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
09-07 12:06:46.494  6889  6889 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-07 12:06:46.495  2021  2021 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@8c33fac
09-07 12:06:46.495  2021  2021 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
09-07 12:06:46.496  2021  2021 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
,09-07 12:06:46.496  2021  2021 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-07 12:06:46.502  2021  2021 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
09-07 12:06:46.503  2021  2021 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
09-07 12:06:46.503  2021  2021 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
09-07 12:06:46.503  2021  2021 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1473242633986, New one : 1473242806467
09-07 12:06:46.503  2021  2021 D [Concierge]WidgetView: Unregister all receivers
09-07 12:06:46.503  2021  2021 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
09-07 12:06:46.504  6889  6889 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 12:06:46.504  2021  2021 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-07 12:06:46.505  2021  2021 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
09-07 12:06:46.506  2021  2021 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
09-07 12:06:46.507  2021  2021 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
09-07 12:06:46.508  2021  2021 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
,09-07 12:06:46.509  8269  8269 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-07 12:06:46.509  8269  8269 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-07 12:06:46.509  8269  8269 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-07 12:06:46.510  2021  2021 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
09-07 12:06:46.512  8198  8198 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-07 12:06:46.512  8198  8260 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-07 12:06:46.513  2021  2021 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-07 12:06:46.513  2021  2021 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-07 12:06:46.516  6889  6889 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-07 12:06:46.521  6889  6889 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 12:06:46.526  8269  8269 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-07 12:06:46.526  8269  8269 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-07 12:06:46.526  8269  8269 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-07 12:06:46.530  8198  8198 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-07 12:06:46.547  2021  2021 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
09-07 12:06:46.555  2021  2021 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
09-07 12:06:46.555  2021  2021 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
09-07 12:06:46.558  2021  2021 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,09-07 12:06:46.560  6889  6889 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-07 12:06:46.564  6889  6889 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 12:06:46.568  8269  8269 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-07 12:06:46.568  8269  8269 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-07 12:06:46.568  8269  8269 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-07 12:06:46.575  8198  8198 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-07 12:06:46.577  2021  2021 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@18fc6e52 time:200805
09-07 12:06:46.584  6889  6889 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-07 12:06:46.587  6889  6889 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 12:06:46.590  8269  8269 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-07 12:06:46.591  8269  8269 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-07 12:06:46.595  8269  8269 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-07 12:06:46.596  8198  8198 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-07 12:06:46.601  6889  6889 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-07 12:06:46.604  6889  6889 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 12:06:46.607  8269  8269 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-07 12:06:46.608  8269  8269 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-07 12:06:46.608  8269  8269 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-07 12:06:46.610  8198  8198 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-07 12:06:46.613  8250  8250 D AndroidRuntime: Shutting down VM
09-07 12:06:46.614  8150  8150 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,09-07 12:06:46.632  1037  1125 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8329 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,09-07 12:06:46.636  8150  8150 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
09-07 12:06:46.639  6889  6889 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-07 12:06:46.645  6889  6889 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 12:06:46.648  8269  8269 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-07 12:06:46.648  8269  8269 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-07 12:06:46.653  8269  8269 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-07 12:06:46.655  8269  8269 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-07 12:06:46.655  8269  8269 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-07 12:06:46.655  1037  1099 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-07 12:06:46.660  1037  1099 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
09-07 12:06:46.660  8198  8198 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-07 12:06:46.663  8150  8150 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,09-07 12:06:46.663  2021  2021 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
09-07 12:06:46.663  8150  8150 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
09-07 12:06:46.665  6889  6889 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-07 12:06:46.668  6889  6889 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 12:06:46.676  8269  8269 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-07 12:06:46.676  8269  8269 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-07 12:06:46.676  8269  8269 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-07 12:06:46.677  8269  8269 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-07 12:06:46.677  8269  8269 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-07 12:06:46.682  1037  1774 I ActivityManager: Killing 7315:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
09-07 12:06:46.730  2021  2021 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,09-07 12:06:46.763  1037  2001 W libprocessgroup: failed to open /acct/uid_10005/pid_7315/cgroup.procs: No such file or directory
,09-07 12:06:46.768  2021  2915 I GBoardtInterface: onReloaded()
09-07 12:06:46.769  8198  8198 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
09-07 12:06:46.773  2021  2021 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
09-07 12:06:46.773  8198  8198 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
09-07 12:06:46.776  3809  4936 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-07 12:06:46.779  1805  1805 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
,09-07 12:06:46.786  3809  3825 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-07 12:06:46.794  2163  2163 I ConfigService: onCreate
09-07 12:06:46.796  2163  2163 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
,09-07 12:06:46.802  2163  2163 I ConfigService: onBind returning update interface
,09-07 12:06:46.805  1805  1805 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
09-07 12:06:46.805  2163  2163 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
09-07 12:06:46.805  2163  2163 I ConfigService: onBind returning config service
09-07 12:06:46.810  1894  1894 D ActionManagerService: notifyUserLog: 1000001
09-07 12:06:46.811  3809  4935 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
09-07 12:06:46.811  3809  4935 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
,09-07 12:06:46.815  1894  1894 D ActionManagerService: notifyUserLog: 1000001
09-07 12:06:46.817  3809  4935 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
09-07 12:06:46.817  3809  4935 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
09-07 12:06:46.817  3809  4935 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
09-07 12:06:46.817  3809  4935 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
09-07 12:06:46.818  3809  4936 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-07 12:06:46.821  2021  2021 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
09-07 12:06:46.821  2021  2021 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
09-07 12:06:46.824  2021  2021 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
09-07 12:06:46.824  2021  2021 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
,09-07 12:06:46.827  1805  1805 I ConfigFetchService: service connected
09-07 12:06:46.827  1805  1805 I ConfigClient: service connected
,09-07 12:06:46.829  2021  2021 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide2.html?id=guide_1111111111116_1472828323135&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
09-07 12:06:46.829  2021  2021 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide2.html?id=guide_1111111111116_1472828323135&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
09-07 12:06:46.834  2163  2163 I ConfigService: onDestroy
09-07 12:06:46.840  1805  8348 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,09-07 12:06:46.865  5896  8353 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
,09-07 12:06:46.872  1805  8355 I PeopleContactsSync: CP2 sync disabled
09-07 12:06:46.875  1805  5244 I Icing   : doRemovePackageData com.test.thalitest
09-07 12:06:46.895  1805  8354 W GmsApplication: Using Auth Proxy for data requests.
,09-07 12:06:46.899  1805  8354 W GmsApplication: Using Auth Proxy for data requests.
09-07 12:06:46.916  7105  7105 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
,09-07 12:06:46.929  2355  8358 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-07 12:06:46.961  1037  1893 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8359 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,09-07 12:06:46.995  8359  8359 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-07 12:06:46.996  8359  8359 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-07 12:06:46.996  8359  8359 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-07 12:06:46.997  8359  8359 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,09-07 12:06:47.004  2163  4658 I art     : Explicit concurrent mark sweep GC freed 6151(371KB) AllocSpace objects, 0(0B) LOS objects, 52% free, 29MB/61MB, paused 1.365ms total 16.477ms
09-07 12:06:47.054  8359  8359 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,09-07 12:06:47.063  8359  8359 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
09-07 12:06:47.098  8359  8359 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-07 12:06:47.120  8359  8359 D LgDataFeature: LgDataFeature() Constructor: none
,09-07 12:06:47.120  8359  8359 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-07 12:06:47.180  8359  8359 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,09-07 12:06:47.188  7856  7856 E SharedPreferencesImpl: Couldn't rename file /data/data/com.android.gallery3d/shared_prefs/com.android.gallery3d_preferences.xml to backup file /data/data/com.android.gallery3d/shared_prefs/com.android.gallery3d_preferences.xml.bak
09-07 12:06:47.189  1037  2002 I ActivityManager: Killing 7669:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
09-07 12:06:47.214  2021  2915 I GBoardtInterface: exportHTML()

```
