#### Test 8359176442466a2_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
09-01 11:16:00.096  1602  1602 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-01 11:16:00.096  1602  1602 I KeyguardUpdateMonitor: called onTimeUpdated()
09-01 11:16:00.096  1602  1602 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
09-01 11:16:00.097  1602  1602 I [SystemUI]Clock: called onTimeUpdated()
,09-01 11:16:00.110  1602  1602 I LgeClockWidgetControlView: called onTimeUpdated()
09-01 11:16:00.110  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
09-01 11:16:00.113  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
09-01 11:16:00.113  1602  1602 D KeyguardUpdateMonitor: handleTimeUpdate
09-01 11:16:00.419  6667  6667 D AndroidRuntime: 
09-01 11:16:00.419  6667  6667 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-01 11:16:00.423  6667  6667 D AndroidRuntime: CheckJNI is OFF
09-01 11:16:00.629  6667  6667 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-01 11:16:00.640  1034  1993 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-01 11:16:00.656  1939  1956 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
09-01 11:16:00.662  1034  1993 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
09-01 11:16:00.663  1034  1993 D ActivityManager: setTaskToReturnTo : TaskRecord{3f7d28d8 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-01 11:16:00.663  1034  1993 D ActivityManager: setTaskToReturnTo : TaskRecord{3f7d28d8 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-01 11:16:00.665  1034  1993 D WindowStateEx: AppWindowTokenEx init.. 
09-01 11:16:00.666   343   351 E GBMv2   : DFP En is all cleared set to be enabled
09-01 11:16:00.694  1034  1993 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6682 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-01 11:16:00.697  6667  6667 D AndroidRuntime: Shutting down VM
09-01 11:16:00.758  1939  1955 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
09-01 11:16:00.759  1939  1955 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1e5641cb co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
09-01 11:16:00.759  1939  2948 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
09-01 11:16:00.760  1939  2948 D SplitWindowPolicy: topRunningActivity=ActivityInfo{20c80da8 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
09-01 11:16:00.833  6682  6682 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
,09-01 11:16:00.914  6682  6682 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,09-01 11:16:00.922  6682  6682 I LibraryLoader: Loading: webviewchromium
09-01 11:16:00.925  6682  6682 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 4493-4496)
09-01 11:16:00.925  6682  6682 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-01 11:16:00.940  6682  6682 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1ac480b1}
,09-01 11:16:00.941  6682  6682 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-01 11:16:00.942  6682  6682 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
09-01 11:16:00.950  6682  6682 I BrowserStartupController: Initializing chromium process, renderers=0
09-01 11:16:00.951  6682  6682 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-01 11:16:00.966  6682  6682 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,09-01 11:16:00.966  6682  6682 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
,09-01 11:16:00.967  6682  6682 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
09-01 11:16:00.975   313   313 V AudioPolicyService: registerClient() client 0xb57ccf60, uid 10118
09-01 11:16:00.978  6682  6682 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-01 11:16:00.978  6682  6682 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-01 11:16:00.978  6682  6682 I Adreno-EGL: Build Date: 12/12/14 금
09-01 11:16:00.978  6682  6682 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-01 11:16:00.978  6682  6682 I Adreno-EGL: Remote Branch: 
09-01 11:16:00.978  6682  6682 I Adreno-EGL: Local Patches: 
09-01 11:16:00.978  6682  6682 I Adreno-EGL: Reconstruct Branch: 
,09-01 11:16:00.989  1034  1096 D BluetoothManagerService: Message: 20
09-01 11:16:00.989  1034  1096 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2d5d3ea2:true
,09-01 11:16:01.091  6682  6727 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,09-01 11:16:01.096  6682  6682 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
09-01 11:16:01.112  6682  6682 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-01 11:16:01.117  6682  6682 W AwContents: onDetachedFromWindow called when already detached. Ignoring
09-01 11:16:01.120  6682  6682 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
09-01 11:16:01.123  6682  6682 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
09-01 11:16:01.123  6682  6682 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
09-01 11:16:01.136  6682  6682 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,09-01 11:16:01.142  6682  6682 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-01 11:16:01.142  6682  6682 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-01 11:16:01.166  6682  6745 D OpenGLRenderer: Render dirty regions requested: true
09-01 11:16:01.166  6682  6745 I OpenGLRenderer: Initialized EGL, version 1.4
09-01 11:16:01.172  6682  6745 D OpenGLRenderer: Enabling debug mode 0
09-01 11:16:01.186  6682  6682 D Atlas   : Validating map...
,09-01 11:16:01.191  1034  1779 D SplitWindow: check instance of lgWin Window{3cd53e4c u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-01 11:16:01.223  6682  6743 D LgDataFeature: LgDataFeature() Constructor: none
,09-01 11:16:01.223  6682  6743 D LgDataFeature: LgDataFeature() Constructor Done, null
09-01 11:16:01.319  1034  1097 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +561ms (total +652ms)
09-01 11:16:01.319  6682  6682 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1d11d334 time:164891
,09-01 11:16:01.321  1034  1097 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{19cc6431 u0 com.test.thalitest/.MainActivity t6} time:164893
09-01 11:16:01.458  6682  6682 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-01 11:16:01.564  6682  6743 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
09-01 11:16:01.564  6682  6743 I chromium: 
,09-01 11:16:01.696  6682  6756 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435157504
,09-01 11:16:01.712  6682  6756 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-01 11:16:01.712  6682  6756 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-01 11:16:01.712  6682  6756 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-01 11:16:01.712  6682  6756 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-01 11:16:01.712  6682  6756 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-01 11:16:01.712  6682  6756 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@50bf1b8 added. We now have 1 listener(s)
09-01 11:16:01.718  1034  2030 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:16:01.721  6682  6756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
09-01 11:16:01.724  6682  6756 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,09-01 11:16:01.725  6682  6756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 11:16:01.726  6682  6756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-01 11:16:01.730  6682  6682 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
09-01 11:16:01.730  6682  6682 I chromium: 
09-01 11:16:01.734  6682  6756 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-01 11:16:01.734  6682  6756 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-01 11:16:01.734  6682  6756 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-01 11:16:01.734  6682  6756 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
09-01 11:16:01.734  6682  6756 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-01 11:16:01.734  6682  6756 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-01 11:16:01.734  6682  6756 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-01 11:16:01.734  6682  6756 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-01 11:16:01.734  6682  6756 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-01 11:16:01.734  6682  6756 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-01 11:16:01.734  6682  6756 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-01 11:16:01.734  6682  6756 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-01 11:16:01.734  6682  6756 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-01 11:16:01.734  6682  6756 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-01 11:16:01.734  6682  6756 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d12ef7 added. We now have 1 listener(s)
09-01 11:16:01.734  6682  6756 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 11:16:01.739  1034  1543 D WifiService: New client listening to asynchronous messages
,09-01 11:16:01.745  6682  6756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-01 11:16:01.745  6682  6756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-01 11:16:01.747  6682  6756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-01 11:16:01.748  6682  6756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-01 11:16:01.748  6682  6756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-01 11:16:01.914  1034  1780 I art     : Explicit concurrent mark sweep GC freed 31175(1414KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 2.630ms total 155.940ms
,09-01 11:16:01.918  6682  6756 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 11:16:01.919  1034  2048 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:16:01.919  6682  6756 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
09-01 11:16:01.928  6682  6756 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
09-01 11:16:01.928  6682  6756 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 11:16:01.928  6682  6756 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:16:01.928  6682  6756 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-01 11:16:01.928  6682  6756 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:16:01.928  6682  6756 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:16:01.928  6682  6756 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 11:16:01.928  6682  6756 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 11:16:01.928  6682  6756 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-01 11:16:01.928  6682  6756 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-01 11:16:01.929  6682  6756 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-01 11:16:01.932  6682  6756 I io.jxcore.node.LifeCycleMonitor: start: OK
09-01 11:16:01.934  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:16:01.937  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:16:01.985  6682  6682 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-01 11:16:02.209   343   353 E GBMv2   : DFP En is all cleared set to be enabled
09-01 11:16:02.209   343   353 E GBMv2   : Set value is all cleared set the max
09-01 11:16:02.210   343   353 I GBMv2   : DFP Enabled. Ignore VFP set
,09-01 11:16:02.640  6682  6759 W jxcore-log: Initializing JXcore engine
09-01 11:16:02.640  6682  6759 W jxcore-log: JXcore engine is ready
,09-01 11:16:02.668  6759  6759 W Thread-767: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[10334]" dev="sockfs" ino=10334 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
09-01 11:16:02.668  6759  6759 W Thread-767: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
09-01 11:16:02.668  6759  6759 W Thread-767: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[10034]" dev="sockfs" ino=10034 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
09-01 11:16:02.668  6759  6759 W Thread-767: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
09-01 11:16:02.668  6759  6759 W Thread-767: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[33121]" dev="sockfs" ino=33121 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,09-01 11:16:02.692  6682  6759 W jxcore-log: Starting JXcore engine
09-01 11:16:02.770  6682  6759 W jxcore-log: Platform android
09-01 11:16:02.770  6682  6759 W jxcore-log: 
09-01 11:16:02.770  6682  6759 W jxcore-log: Process ARCH arm
09-01 11:16:02.770  6682  6759 W jxcore-log: 
,09-01 11:16:02.962  6682  6759 I jxcore-log: JXcore Cordova bridge is ready!
09-01 11:16:02.962  6682  6759 I jxcore-log: 
09-01 11:16:02.962  6682  6759 W jxcore-log: JXcore engine is started
,09-01 11:16:02.971  6682  6756 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
09-01 11:16:02.973  6682  6682 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-01 11:16:13.969  6682  6759 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-01 11:16:13.969  6682  6759 I jxcore-log: 
09-01 11:16:13.972  6682  6759 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-01 11:16:13.972  6682  6759 I jxcore-log: 
,09-01 11:16:13.979  6682  6759 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 11:16:13.979  6682  6759 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:16:13.979  6682  6759 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-01 11:16:13.979  6682  6759 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:16:13.979  6682  6759 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:16:13.979  6682  6759 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 11:16:13.979  6682  6759 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 11:16:13.979  6682  6759 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-01 11:16:13.982  6682  6759 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-01 11:16:13.987  6682  6759 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-01 11:16:13.987  6682  6759 I jxcore-log: 
,09-01 11:16:13.992  6682  6759 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-01 11:16:13.992  6682  6759 I jxcore-log: 
09-01 11:16:14.949  6682  6759 D executeNativeTests: Running unit tests
,09-01 11:16:15.085  6682  6759 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-01 11:16:15.085  6682  6759 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b3aea88 added. We now have 2 listener(s)
,09-01 11:16:15.088  1034  2030 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:16:15.091  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-01 11:16:15.091  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 11:16:15.091  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-01 11:16:15.091  6682  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 11:16:15.091  6682  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bb7c21 added. We now have 2 listener(s)
09-01 11:16:15.091  6682  6759 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 11:16:15.092  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-01 11:16:15.095  6682  6759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 11:16:15.099  6682  6759 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 11:16:15.099  6682  6759 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:16:15.099  6682  6759 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-01 11:16:15.099  6682  6759 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:16:15.099  6682  6759 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:16:15.099  6682  6759 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 11:16:15.099  6682  6759 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 11:16:15.099  6682  6759 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-01 11:16:15.104  6682  6759 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-01 11:16:15.104  6682  6759 D io.jxcore.node.ConnectivityMonitor: start: OK
09-01 11:16:15.106  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:16:15.108  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:16:15.111  6682  6759 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-01 11:16:15.115  6682  6759 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-01 11:16:15.115  6682  6759 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-01 11:16:15.120  6682  6759 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-01 11:16:15.121  6682  6759 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-01 11:16:15.121  6682  6759 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-01 11:16:15.121  6682  6759 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-01 11:16:15.121  6682  6759 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-01 11:16:15.122  6682  6759 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:16:15.123  6682  6759 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:16:15.123  6682  6759 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-01 11:16:15.126  6682  6759 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:16:15.129  6682  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:16:15.129  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 11:16:15.130  6682  6759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-01 11:16:15.130  6682  6759 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b3aea88 removed from the list
09-01 11:16:15.130  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:16:15.130  6682  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bb7c21 removed from the list
09-01 11:16:15.130  6682  6759 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:16:15.130  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:16:15.132  6682  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:16:15.132  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:16:15.133  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:16:15.133  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:16:15.133  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:16:15.133  6682  6759 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bb7c21 not in the list
09-01 11:16:15.135  6682  6759 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-01 11:16:15.136  6682  6759 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:16:15.136  6682  6759 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:16:15.136  6682  6759 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:16:15.136  6682  6759 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:16:15.136  6682  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:16:15.136  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:16:15.136  6682  6759 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b3aea88 not in the list
09-01 11:16:15.136  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:16:15.136  6682  6759 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bb7c21 not in the list
09-01 11:16:15.136  6682  6759 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:16:15.137  6682  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:16:15.137  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01, 11:16:15.137  6682  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:16:15.137  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 11:16:15.141  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:16:15.141  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:16:15.141  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:16:15.141  6682  6759 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bb7c21 not in the list
09-01 11:16:15.150  6682  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-01 11:16:15.150  6682  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-01 11:16:15.150  6682  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-01 11:16:15.150  6682  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-01 11:16:15.150  6682  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-01 11:16:15.150  6682  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-01 11:16:15.150  6682  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-01 11:16:15.150  6682  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-01 11:16:15.150  6682  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-01 11:16:15.150  6682  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-01 11:16:15.150  6682  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-01 11:16:15.150  6682  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-01 11:16:15.150  6682  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-01 11:16:15.150  6682  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-01 11:16:15.150  6682  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-01 11:16:15.150  6682  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-01 11:16:15.150  6682  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-01 11:16:15.150  6682  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-01 11:16:15.151  6682  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-01 11:16:15.151  6682  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-01 11:16:15.151  6682  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-01 11:16:15.151  6682  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-01 11:16:15.151  6682  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-01 11:16:15.151  6682  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingC,onnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-01 11:16:15.151  6682  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-01 11:16:15.151  6682  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-01 11:16:15.151  6682  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-01 11:16:15.151  6682  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-01 11:16:15.151  6682  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-01 11:16:15.151  6682  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-01 11:16:15.151  6682  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-01 11:16:15.151  6682  6759 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:16:15.151  6682  6759 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:16:15.151  6682  6759 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-01 11:16:15.157  6682  6759 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:16:15.157  6682  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:16:15.157  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:16:15.157  6682  6759 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b3aea88 not in the list
09-01 11:16:15.157  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:16:15.157  6682  6759 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bb7c21 not in the list
09-01 11:16:15.157  6682  6759 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:16:15.157  6682  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:16:15.157  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:16:15.157  6682  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:16:15.157  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:16:15.160  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:16:15.160  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:16:15.160  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:16:15.160  6682  6759 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bb7c21 not in the list
09-01 11:16:15.161  6682  6759 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-01 11:16:15.163  6682  6759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 11:16:15.166  6682  6759 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 11:16:15.166  6682  6759 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:16:15.166  6682  6759 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-01 11:16:15.166  6682  6759 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:16:15.166  6682  6759 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:16:15.166  6682  6759 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 11:16:15.166  6682  6759 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 11:16:15.166  6682  6759 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-01 11:16:15.171  6682  6759 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-01 11:16:15.171  6682  6759 D io.jxcore.node.ConnectivityMonitor: start: OK
09-01 11:16:15.173  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:16:15.175  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:16:15.175  6682  6759 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-01 11:16:15.176  6682  6759 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-01 11:16:15.176  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-01 11:16:15.176  6682  6759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 11:16:15.176  6682  6759 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-01 11:16:15.181  6682  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-01 11:16:15.183  1034  1049 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:16:15.190  6682  6759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-01 11:16:15.196  6682  6759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-01 11:16:15.201  6682  6759 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
09-01 11:16:15.202  6682  6759 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-01 11:16:15.203  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 11:16:15.205  6682  6759 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-01 11:16:15.206  6682  6759 I io.jxcore.node.ConnectionHelper: start: OK
09-01 11:16:15.210  6682  6759 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:16:15.210  6682  6759 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:16:15.210  6682  6759 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-01 11:16:15.213  6682  6759 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:16:15.213  6682  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:16:15.213  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 11:16:15.213  6682  6759 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b3aea88 not in the list
09-01 11:16:15.213  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:16:15.213  6682  6759 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bb7c21 not in the list
09-01 11:16:15.213  6682  6759 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:16:15.213  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:16:15.214  6682  6759 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-01 11:16:15.216  6682  6759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 11:16:15.219  6682  6759 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 11:16:15.219  6682  6759 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:16:15.219  6682  6759 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-01 11:16:15.219  6682  6759 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:16:15.219  6682  6759 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:16:15.219  6682  6759 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 11:16:15.219  6682  6759 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 11:16:15.219  6682  6759 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-01 11:16:15.221  6682  6759 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-01 11:16:15.221  6682  6759 D io.jxcore.node.ConnectivityMonitor: start: OK
09-01 11:16:15.223  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:16:15.227  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:16:15.228  6682  6759 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-01 11:16:15.228  6682  6759 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-01 11:16:15.228  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-01 11:16:15.228  6682  6759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 11:16:15.228  6682  6759 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-01 11:16:15.232  6682  6759 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-01 11:16:15.233  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 11:16:15.234  6682  6759 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,09-01 11:16:15.237  6682  6759 I io.jxcore.node.ConnectionHelper: start: OK
09-01 11:16:15.239  6682  6759 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:16:15.239  6682  6759 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:16:15.239  6682  6759 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:16:15.239  6682  6759 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:16:15.239  6682  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:16:15.239  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 11:16:15.239  6682  6759 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b3aea88 not in the list
09-01 11:16:15.239  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:16:15.239  6682  6759 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bb7c21 not in the list
09-01 11:16:15.239  6682  6759 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:16:15.239  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:16:15.240  6682  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:16:15.240  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:16:15.241  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:16:15.241  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:16:15.243  6682  6759 D BluetoothLeScanner: could not find callback wrapper
09-01 11:16:15.243  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-01 11:16:15.243  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:16:15.243  6682  6759 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bb7c21 not in the list
09-01 11:16:15.244  6682  6759 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-01 11:16:15.246  6682  6759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-01 11:16:15.253  6682  6759 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 11:16:15.253  6682  6759 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:16:15.253  6682  6759 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-01 11:16:15.253  6682  6759 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:16:15.253  6682  6759 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:16:15.253  6682  6759 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 11:16:15.253  6682  6759 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 11:16:15.253  6682  6759 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-01 11:16:15.255  6682  6759 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-01 11:16:15.255  6682  6759 D io.jxcore.node.ConnectivityMonitor: start: OK
09-01 11:16:15.257  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:16:15.258  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:16:15.260  6682  6759 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-01 11:16:15.260  6682  6759 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-01 11:16:15.260  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-01 11:16:15.260  6682  6759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 11:16:15.260  6682  6759 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-01 11:16:15.265  6682  6759 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-01 11:16:15.266  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 11:16:15.267  6682  6759 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-01 11:16:15.267  6682  6759 I io.jxcore.node.ConnectionHelper: start: OK
09-01 11:16:15.267  6682  6759 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:16:15.267  6682  6759 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:16:15.267  6682  6759 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:16:15.271  6682  6759 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:16:15.271  6682  6759 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:16:15.272  6682  6759 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:16:15.272  6682  6759 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:16:15.272  6682  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:16:15.272  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 11:16:15.272  6682  6759 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b3aea88 not in the list
09-01 11:16:15.272  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:16:15.272  6682  6759 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bb7c21 not in the list
09-01 11:16:15.272  6682  6759 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:16:15.272  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:16:15.274  6682  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:16:15.274  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:16:15.275  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:16:15.275  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:16:15.276,  6682  6759 D BluetoothLeScanner: could not find callback wrapper
09-01 11:16:15.276  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-01 11:16:15.276  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:16:15.276  6682  6759 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bb7c21 not in the list
09-01 11:16:15.277  6682  6759 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-01 11:16:15.277  6682  6759 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:16:15.277  6682  6759 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:16:15.277  6682  6759 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:16:15.277  6682  6759 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:16:15.277  6682  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:16:15.277  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:16:15.277  6682  6759 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b3aea88 not in the list
09-01 11:16:15.277  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:16:15.277  6682  6759 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bb7c21 not in the list
09-01 11:16:15.277  6682  6759 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:16:15.277  6682  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:16:15.278  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:16:15.278  6682  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:16:15.278  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:16:15.279  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:16:15.279  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:16:15.280  6682  6759 D BluetoothLeScanner: could not find callback wrapper
09-01 11:16:15.280  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-01 11:16:15.280  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:16:15.280  6682  6759 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bb7c21 not in the list
09-01 11:16:15.281  6682  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-01 11:16:15.282  6682  6759 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:16:15.282  6682  6759 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:16:15.282  6682  6759 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:16:15.282  6682  6759 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:16:15.282  6682  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:16:15.282  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:16:15.282  6682  6759 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b3aea88 not in the list
09-01 11:16:15.282  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:16:15.282  6682  6759 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bb7c21 not in the list
09-01 11:16:15.282  6682  6759 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:16:15.282  6682  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:16:15.282  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:16:15.282  6682  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:16:15.282  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:16:15.284  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:16:15.284  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:16:15.286  6682  6759 D BluetoothLeScanner: could not find callback wrapper
09-01 11:16:15.286  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-01 11:16:15.286  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:16:15.286  6682  6759 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bb7c21 not in the list
09-01 11:16:15.287  6682  6759 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-01 11:16:15.287  6682  6759 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:16:15.287  6682  6759 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:16:15.287  6682  6759 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:16:15.287  6682  6759 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:16:15.287  6682  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:16:15.287  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:16:15.287  6682  6759 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b3aea88 not in the list
09-01 11:16:15.287  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:16:15.288  6682  6759 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bb7c21 not in the list
09-01 11:16:15.288  6682  6759 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:16:15.288  6682  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:16:15.288  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:16:15.288  6682  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:16:15.288  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:16:15.295  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:16:15.298  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:16:15.303  6682  6759 D BluetoothLeScanner: could not find callback wrapper
09-01 11:16:15.303  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-01 11:16:15.303  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:16:15.304  6682  6759 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bb7c21 not in the list
09-01 11:16:15.305  6682  6759 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-01 11:16:15.305  6682  6759 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:16:15.305  6682  6759 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:16:15.305  6682  6759 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:16:15.305  6682  6759 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:16:15.305  6682  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:16:15.306  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:16:15.306  6682  6759 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b3aea88 not in the list
09-01 11:16:15.306  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:16:15.306  6682  6759 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bb7c21 not in the list
09-01 11:16:15.306  6682  6759 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:16:15.306  6682  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:16:15.306  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:16:15.306  6682  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:16:15.306  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:16:15.307  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:16:15.307  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:16:15.309  6682  6759 D BluetoothLeScanner: could not find callback wrapper
09-01 11:16:15.309  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-01 11:16:15.309  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:16:15.309  6682  6759 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bb7c21 not in the list
09-01 11:16:15.310  6682  6759 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-01 11:16:15.314  6682  6759 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-01 11:16:15.314  6682  6759 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-01 11:16:15.315  6682  6759 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-01 11:16:15.315  6682  6759 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-01 11:16:15.315  6682  6759 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-01 11:16:15.315  6682  6759 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:16:15.315  6682  6759 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:16:15.315  6682  6759 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:16:15.316  6682  6759 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:16:15.316  6682  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:16:15.316  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:16:15.316  6682  6759 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b3aea88 not in the list
09-01 11:16:15.316  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:16:15.316  6682  6759 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bb7c21 not in the list
09-01 11:16:15.316  6682  6759 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:16:15.316  6682  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:16:15.316  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:16:15.316  6682  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:16:15.316  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:16:15.330  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:16:15.331  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:16:15.332  6682  6759 D BluetoothLeScanner: could not find callback wrapper
09-01 11:16:15.332  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-01 11:16:15.332  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:16:15.332  6682  6759 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bb7c21 not in the list
09-01 11:16:15.335  6682  6759 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-01 11:16:15.335  6682  6759 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-01 11:16:15.335  6682  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-01 11:16:15.344  6682  6759 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-01 11:16:15.344  6682  6759 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-01 11:16:15.345  6682  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-01 11:16:15.345  6682  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-01 11:16:15.345  6682  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-01 11:16:15.345  6682  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-01 11:16:15.345  6682  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-01 11:16:15.345  6682  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-01 11:16:15.345  6682  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-01 11:16:15.345  6682  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-01 11:16:15.345  6682  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-01 11:16:15.345  6682  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-01 11:16:15.346  6682  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-01 11:16:15.346  6682  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-01 11:16:15.346  6682  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-01 11:16:15.346  6682  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-01 11:16:15.346  6682  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-01 11:16:15.346  6682  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-01 11:16:15.346  6682  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-01 11:16:15.346  6682  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-01 11:16:15.346  6682  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-01 11:16:15.347  6682  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-01 11:16:15.347  6682  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-01 11:16:15.347  6682  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-01 11:16:15.347  6682  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-01 11:16:15.347  6682  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-01 11:16:15.347  6682  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-01 11:16:15.347  6682  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-01 11:16:15.347  6682  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-01 11:16:15.347  6682  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-01 11:16:15.348  6682  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-01 11:16:15.348  6682  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-01 11:16:15.348  6682  6759 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-01 11:16:15.348  6682  6759 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-01 11:16:15.349  6682  6759 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-01 11:16:15.349  6682  6759 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-01 11:16:15.349  6682  6759 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-01 11:16:15.349  6682  6759 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-01 11:16:15.350  6682  6759 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-01 11:16:15.350  6682  6759 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-01 11:16:15.350  6682  6759 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-01 11:16:15.352  6682  6759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,09-01 11:16:15.355  6682  6759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-01 11:16:15.356  6682  6759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-01 11:16:15.357  6682  6759 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-01 11:16:15.358  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-01 11:16:15.359  6682  6759 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-01 11:16:15.359  6682  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 831)
09-01 11:16:15.359  6682  6759 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-01 11:16:15.359  6682  6759 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-01 11:16:15.360  6682  6759 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:16:15.360  6682  6759 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:16:15.360  6682  6759 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:16:15.360  6682  6759 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:16:15.360  6682  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:16:15.360  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:16:15.361  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-01 11:16:15.361  6682  6759 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b3aea88 not in the list
09-01 11:16:15.361  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:16:15.361  6682  6759 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bb7c21 not in the list
09-01 11:16:15.361  6682  6759 D io.jxcore.node.ConnectivityMonitor: stop
,09-01 11:16:15.361  6682  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:16:15.362  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:16:15.362  6682  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:16:15.362  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 11:16:15.363  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:16:15.363  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:16:15.363  6682  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 831
09-01 11:16:15.363  6682  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 831)
09-01 11:16:15.363  6682  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 831)
09-01 11:16:15.363  6682  6759 D BluetoothLeScanner: could not find callback wrapper
09-01 11:16:15.363  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-01 11:16:15.363  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:16:15.363  6682  6759 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bb7c21 not in the list
09-01 11:16:15.364  6682  6759 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-01 11:16:15.365  6682  6759 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:16:15.365  6682  6759 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:16:15.365  6682  6759 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:16:15.365  6682  6759 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:16:15.366  6682  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:16:15.366  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:16:15.366  6682  6759 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b3aea88 not in the list
,09-01 11:16:15.366  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:16:15.366  6682  6759 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bb7c21 not in the list
09-01 11:16:15.366  6682  6759 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:16:15.366  6682  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:16:15.366  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:16:15.366  6682  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:16:15.366  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:16:15.367  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:16:15.367  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-01 11:16:15.368  6682  6759 D BluetoothLeScanner: could not find callback wrapper,
09-01 11:16:15.368  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-01 11:16:15.368  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:16:15.368  6682  6759 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bb7c21 not in the list
,09-01 11:16:15.369  6682  6759 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-01 11:16:15.370  6682  6759 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:16:15.370  6682  6759 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:16:15.370  6682  6759 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:16:15.371  6682  6759 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:16:15.371  6682  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:16:15.371  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:16:15.371  6682  6759 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b3aea88 not in the list
09-01 11:16:15.371  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-01 11:16:15.371  6682  6759 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bb7c21 not in the list
09-01 11:16:15.371  6682  6759 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:16:15.371  6682  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:16:15.374  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:16:15.374  6682  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:16:15.374  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:16:15.375  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:16:15.375  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:16:15.376  6682  6759 D BluetoothLeScanner: could not find callback wrapper
09-01 11:16:15.376  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-01 11:16:15.376  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:16:15.376  6682  6759 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bb7c21 not in the list
09-01 11:16:15.377  6682  6759 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-01 11:16:15.377  6682  6759 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-01 11:16:15.378  6682  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-01 11:16:15.378  6682  6759 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-01 11:16:15.378  6682  6759 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-01 11:16:15.388  6682  6759 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-01 11:16:15.388  6682  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-01 11:16:15.388  6682  6759 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-01 11:16:15.388  6682  6759 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55,
09-01 11:16:15.388  6682  6759 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-01 11:16:15.388  6682  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-01 11:16:15.388  6682  6759 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-01 11:16:15.389  6682  6759 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:16:15.389  6682  6759 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:16:15.389  6682  6759 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-01 11:16:15.390  6682  6759 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:16:15.390  6682  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:16:15.390  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:16:15.390  6682  6759 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b3aea88 not in the list
09-01 11:16:15.390  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:16:15.390  6682  6759 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bb7c21 not in the list
09-01 11:16:15.390  6682  6759 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:16:15.390  6682  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:16:15.390  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 11:16:15.391  6682  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:16:15.391  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:16:15.392  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:16:15.392  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:16:15.393  6682  6759 D BluetoothLeScanner: could not find callback wrapper
09-01 11:16:15.393  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-01 11:16:15.393  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:16:15.393  6682  6759 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bb7c21 not in the list
09-01 11:16:15.394  6682  6759 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:16:15.394  6682  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:16:15.394  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:16:15.394  6682  6759 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b3aea88 not in the list
09-01 11:16:15.394  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:16:15.394  6682  6759 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bb7c21 not in the list
09-01 11:16:15.394  6682  6759 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:16:15.394  6682  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:16:15.394  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:16:15.394  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:16:15.394  6682  6759 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bb7c21 not in the list
09-01 11:16:15.394  6682  6759 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:16:15.394  6682  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:16:15.394  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:16:15.394  6682  6759 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b3aea88 not in the list
09-01 11:16:15.394  6682  6759 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-01 11:16:15.395  6682  6759 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:16:15.395  6682  6759 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:16:15.396  6682  6759 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:16:15.396  6682  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:16:15.396  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:16:15.396  6682  6759 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b3aea88 not in the list
09-01 11:16:15.396  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:16:15.396  6682  6759 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bb7c21 not in the list
09-01 11:16:15.396  6682  6759 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:16:15.396  6682  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:16:15.396  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:16:15.396  6682  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:16:15.396  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:16:15.397  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:16:15.397  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:16:15.398  6682  6759 D BluetoothLeScanner: could not find callback wrapper
09-01 11:16:15.398  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-01 11:16:15.398  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:16:15.398  6682  6759 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bb7c21 not in the list
09-01 11:16:15.400  6682  6759 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-01 11:16:15.401  6682  6759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 11:16:15.402  6682  6759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-01 11:16:15.402  6682  6759 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-01 11:16:15.403  6682  6759 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-01 11:16:15.403  6682  6682 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-01 11:16:15.403  6682  6759 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-01 11:16:15.403  6682  6759 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-01 11:16:15.405  6682  6759 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:16:15.405  6682  6759 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-01 11:16:15.405  6682  6759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothCon,nector: stopListeningForIncomingConnections: Stopping...
09-01 11:16:15.405  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-01 11:16:15.405  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:16:15.405  6682  6759 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-01 11:16:15.406  6682  6682 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-01 11:16:15.406  1034  2030 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:16:15.408  6682  6759 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b3aea88 not in the list
09-01 11:16:15.408  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:16:15.409  6682  6781 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-01 11:16:15.409  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-01 11:16:15.409  6682  6759 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-01 11:16:15.409  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-01 11:16:15.411  3884  4315 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=82
09-01 11:16:15.412  6682  6781 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-01 11:16:15.413  6682  6759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-01 11:16:15.413  6682  6781 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-01 11:16:15.414  6682  6781 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-01 11:16:15.414  6682  6759 D BluetoothLeScanner: could not find callback wrapper
09-01 11:16:15.414  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-01 11:16:15.414  6682  6759 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-01 11:16:15.414  6682  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:16:15.414  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:16:15.415  6682  6759 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-01 11:16:15.415  6682  6759 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bb7c21 not in the list
09-01 11:16:15.415  6682  6682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-01 11:16:15.415  6682  6682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-01 11:16:15.415  6682  6759 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:16:15.416  6682  6759 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:16:15.416  6682  6682 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-01 11:16:15.416  6682  6759 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:16:15.416  6682  6759 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:16:15.416  6682  6682 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-01 11:16:15.416  6682  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:16:15.416  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:16:15.416  6682  6759 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b3aea88 not in the list
09-01 11:16:15.416  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:16:15.416  6682  6759 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib,.DiscoveryManager@8bb7c21 not in the list
09-01 11:16:15.416  6682  6759 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:16:15.416  6682  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:16:15.416  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:16:15.416  6682  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:16:15.416  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:16:15.417  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:16:15.417  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:16:15.417  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:16:15.417  6682  6759 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bb7c21 not in the list
09-01 11:16:15.418  6682  6759 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-01 11:16:15.419  6682  6759 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-01 11:16:15.419  6682  6759 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-01 11:16:15.419  6682  6759 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-01 11:16:15.419  6682  6759 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-01 11:16:15.419  6682  6759 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:16:15.419  6682  6759 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:16:15.420  6682  6759 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:16:15.420  6682  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:16:15.420  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:16:15.420  6682  6759 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b3aea88 not in the list
09-01 11:16:15.420  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:16:15.420  6682  6759 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bb7c21 not in the list
09-01 11:16:15.420  6682  6759 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:16:15.420  6682  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:16:15.420  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:16:15.420  6682  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-01 11:16:15.420  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:16:15.422  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:16:15.422  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:16:15.422  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:16:15.422  6682  6759 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bb7c21 not in the list
,09-01 11:16:15.424  1034  2048 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
09-01 11:16:15.425  1034  1959 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:16:15.426  1034  1779 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:16:15.427  6682  6759 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:16:15.427  6682  6759 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-01 11:16:15.427  6682  6759 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:16:15.428  6682  6759 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:16:15.428  6682  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:16:15.428  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:16:15.428  6682  6759 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b3aea88 not in the list
09-01 11:16:15.428  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:16:15.428  6682  6759 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bb7c21 not in the list
09-01 11:16:15.428  6682  6759 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:16:15.428  6682  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-01 11:16:15.428  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:16:15.428  6682  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:16:15.428  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:16:15.430  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:16:15.430  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:16:15.430  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:16:15.430  6682  6759 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bb7c21 not in the list,
09-01 11:16:15.431  6682  6759 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:16:15.431  6682  6759 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:16:15.431  6682  6759 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:16:15.432  6682  6759 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:16:15.432  6682  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-01 11:16:15.432  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:16:15.432  6682  6759 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b3aea88 not in the list
09-01 11:16:15.432  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:16:15.432  6682  6759 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bb7c21 not in the list
09-01 11:16:15.432  6682  6759 D io.jxcore.node.ConnectivityMonitor: stop
,09-01 11:16:15.432  6682  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:16:15.432  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:16:15.432  6682  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:16:15.432  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:16:15.433  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-01 11:16:15.433  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:16:15.433  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:16:15.433  6682  6759 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bb7c21 not in the list
09-01 11:16:15.435  6682  6759 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-01 11:16:15.435  6682  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,09-01 11:16:15.435  6682  6759 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-01 11:16:15.435  6682  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-01 11:16:15.436  6682  6759 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
,09-01 11:16:15.436  6682  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left,
09-01 11:16:15.438  6682  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-01 11:16:15.438  6682  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-01 11:16:15.439  6682  6759 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-01 11:16:15.440  6682  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-01 11:16:15.440  6682  6759 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-01 11:16:15.440  6682  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-01 11:16:15.440  6682  6759 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-01 11:16:15.440  6682  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-01 11:16:15.441  6682  6759 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-01 11:16:15.441  6682  6759 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-01 11:16:15.442  6682  6759 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-01 11:16:15.442  6682  6759 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-01 11:16:15.442  6682  6759 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-01 11:16:15.442  6682  6759 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-01 11:16:15.444  6682  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 11:16:15.444  6682  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@45fea1e added. We now have 2 listener(s)
09-01 11:16:15.444  6682  6759 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 11:16:15.446  6682  6759 D BluetoothAdapter: enable(): BT is already enabled..!
09-01 11:16:15.447  1034  1049 D WifiServiceImplEx: setWifiEnabled: true pid=6682, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,09-01 11:16:15.447  1034  1049 D WifiService: setWifiEnabled: true pid=6682, uid=10118
09-01 11:16:15.447  1034  1049 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-01 11:16:15.449  6682  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 11:16:15.449  6682  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@76002ff added. We now have 3 listener(s)
09-01 11:16:15.449  6682  6759 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 11:16:15.453  6682  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 11:16:15.453  6682  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@350528cc added. We now have 4 listener(s)
09-01 11:16:15.454  6682  6759 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 11:16:15.455  6682  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 11:16:15.456  6682  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3f68b715 added. We now have 5 listener(s)
09-01 11:16:15.456  6682  6759 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 11:16:15.458  1034  1049 D WifiServiceImplEx: setWifiEnabled: false pid=6682, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-01 11:16:15.458  1034  1049 D WifiService: setWifiEnabled: false pid=6682, uid=10118
09-01 11:16:15.458  1034  1049 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-01 11:16:15.472  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-01 11:16:15.472  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-01 11:16:15.472  1034  1034 D Ulp_jni : JNI:system_update. Event-4
09-01 11:16:15.473  1034  1537 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
09-01 11:16:15.474  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
09-01 11:16:15.474  1034  1537 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
09-01 11:16:15.475  1034  1537 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
09-01 11:16:15.475  1034  1537 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
09-01 11:16:15.475  1034  1537 E WifiStateMachine: WifiStateMachine: Leaving Connected state
09-01 11:16:15.475  1034  1537 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-01 11:16:15.475  1034  1537 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-01 11:16:15.476  1034  1537 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-01 11:16:15.476  1034  1537 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-01 11:16:15.476  6682  6774 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
09-01 11:16:15.477  6682  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 831)
09-01 11:16:15.477  1034  1959 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:16:15.477  1034  1959 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@3c13a85f mBinding = false
09-01 11:16:15.484  1034  1537 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-01 11:16:15.484  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-01 11:16:15.484  1034  1536 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:16:15.484  1034  1536 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,09-01 11:16:15.484  2733  2733 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-01 11:16:15.485  1034  1537 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-01 11:16:15.485  1034  1537 D WifiNative-wlan0: doBoolean: SET ps 1
,09-01 11:16:15.485  1034  1537 D WifiNative-wlan0: SET ps 1: returned true
09-01 11:16:15.486  1034  2863 D DhcpStateMachine: RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:16:15.488   309   893 D CommandListener: Clearing all IP addresses on wlan0
09-01 11:16:15.489  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-01 11:16:15.489  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-01 11:16:15.489  1034  1034 D Ulp_jni : JNI:system_update. Event-4
09-01 11:16:15.489  1034  1096 D BluetoothManagerService: Message: 2
09-01 11:16:15.490  1034  1096 D BluetoothManagerService: Sending off request.
09-01 11:16:15.491  3884  4315 D LGBluetoothServiceAdapter: [BTUI] Precleanup
09-01 11:16:15.491  3884  3964 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
09-01 11:16:15.491  3884  3964 D BluetoothAdapterProperties: Setting state to 13
09-01 11:16:15.491  3884  3964 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-01 11:16:15.492  3884  3964 D BluetoothAdapterProperties: onBluetoothDisable()
09-01 11:16:15.492  3884  3964 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-01 11:16:15.498  3884  3967 D BluetoothAdapterProperties: Scan Mode:20
09-01 11:16:15.498  3884  3964 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,09-01 11:16:15.499  3884  4269 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-01 11:16:15.500  3884  3964 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-01 11:16:15.501  3884  4343 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-01 11:16:15.501  3884  4344 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-01 11:16:15.502  3884  4346 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-01 11:16:15.503  3884  4073 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
09-01 11:16:15.503  3884  4265 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
09-01 11:16:15.503  3884  4265 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-01 11:16:15.503  3884  4265 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
09-01 11:16:15.503  3884  4265 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
09-01 11:16:15.503  3884  4265 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
09-01 11:16:15.503  3884  4265 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
09-01 11:16:15.503  3884  4265 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
09-01 11:16:15.503  3884  4265 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
09-01 11:16:15.503  3884  4073 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
09-01 11:16:15.503  1034  1893 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
09-01 11:16:15.503  1034  2862 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:16:15.503  1034  2862 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:16:15.503  1034  2862 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
09-01 11:16:15.503  1034  2862 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
,09-01 11:16:15.504  1034  2862 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-01 11:16:15.506  3884  4073 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-01 11:16:15.506  3884  4073 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-01 11:16:15.506  3884  4073 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-01 11:16:15.506  3884  4073 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-01 11:16:15.506  3884  4073 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-01 11:16:15.506  3884  4073 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-01 11:16:15.506  3884  4073 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-01 11:16:15.507  3884  4073 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-01 11:16:15.507  3884  4073 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-01 11:16:15.507  3884  4073 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
09-01 11:16:15.507   309  6788 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
09-01 11:16:15.507  3884  4073 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
09-01 11:16:15.507  3884  4073 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-01 11:16:15.507  1034  1094 D DSQN    : Dns fail occured do internet check.
09-01 11:16:15.508  1034  1034 D DSQN    : EVENT_INTERNET_CHECK_REQUEST received
09-01 11:16:15.508  1034  1034 D DSQN    : try Internet connection check
09-01 11:16:15.509  1034  2862 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
09-01 11:16:15.511  6682  6759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-01 11:16:15.515  1034  1544 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-01 11:16:15.515  1034  1544 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
09-01 11:16:15.515  1034  1096 D BluetoothManagerService: Message: 60
09-01 11:16:15.515  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
09-01 11:16:15.515  1034  1096 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
09-01 11:16:15.516  6682  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:16:15.516  6682  6759 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 11:16:15.516  6682  6759 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:16:15.516  6682  6759 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-01 11:16:15.516  6682  6759 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:16:15.516  6682  6759 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 11:16:15.516  6682  6759 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:16:15.516  6682  6759 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 11:16:15.516  6682  6759 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-01 11:16:15.519  6682  6682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-01 11:16:15.519  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:16:15.519  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:16:15.519  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-01 11:16:15.519  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:16:15.519  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 11:16:15.519  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:16:15.519  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 11:16:15.519  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-01 11:16:15.522  6682  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:16:15.522  6682  6759 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-01 11:16:15.522  6682  6759 D io.jxcore.node.ConnectivityMonitor: start: OK
09-01 11:16:15.523  6682  6682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:16:15.523  6682  6682 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-01 11:16:15.525  6682  6682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:16:15.525  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:16:15.525  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:16:15.525  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-01 11:16:15.525  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:16:15.525  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 11:16:15.525  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:16:15.525  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:16:15.525  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-01 11:16:15.526  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:16:15.527  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:16:15.559  1034  1544 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
09-01 11:16:15.559  1034  1544 D DSQN    : disableDataServiceNotify
09-01 11:16:15.559  1034  1544 D DSQN    : stop dsqn bin
09-01 11:16:15.560   309  6810 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
09-01 11:16:15.560  1034  1092 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6795 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
09-01 11:16:15.560  1034  6790 D DSQN    : ThreadTCPConnectionCheck DNS fail internet is not possible
,09-01 11:16:15.561  1034  6789 D DSQN    : ThreadInternetCheck internet check NOK 
09-01 11:16:15.561  1034  6789 D DSQN    : InternetcheckProgress is not set don't send DS quality intent
09-01 11:16:15.562  1034  1094 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
09-01 11:16:15.563  1034  1034 D WifiHS20: hidePasspointNotification off =false
09-01 11:16:15.564  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-01 11:16:15.564  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-01 11:16:15.565  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:16:15.565  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:16:15.565  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-01 11:16:15.565  1939  1939 V WfdStateTracker: handleWifiStateChangedEvent: 0
09-01 11:16:15.566  1034  1536 D LGWifiP2pService: InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:16:15.566  1034  1536 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:16:15.566  1034  1536 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@2c370b7
09-01 11:16:15.566  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:16:15.567  1034  1537 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:16:15.567  1034  1537 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:16:15.567  1034  1544 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-01 11:16:15.567  1034  1544 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-01 11:16:15.567  1034  1544 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-01 11:16:15.567  1034  1537 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:16:15.567  1034  1544 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
09-01 11:16:15.567  1034  1537 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:16:15.567  1034  1536 D LGWifiP2pService: P2pDisablingState
09-01 11:16:15.568  1034  1536 D LGWifiP2pService: P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:16:15.568  1034  1544 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
09-01 11:16:15.568  1034  1536 D LGWifiP2pService: p2p socket connection lost
09-01 11:16:15.568  1034  1536 D LGWifiP2pService: P2pDisabledState
09-01 11:16:15.568  1034  2862 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:16:15.568  1034  2862 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:16:15.568  1034  2862 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-01 11:16:15.568  1034  1537 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:16:15.569  1034  1537 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:16:15.569  1602  2075 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-01 11,:16:15.569  1034  1537 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-01 11:16:15.569  1034  1544 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
09-01 11:16:15.569  1034  1544 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-01 11:16:15.569  1034  1544 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-01 11:16:15.570  1034  1537 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:16:15.570  1034  1544 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-01 11:16:15.570  1034  1537 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:16:15.570  1034  1544 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-01 11:16:15.570  1034  1544 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-01 11:16:15.570  1034  1537 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:16:15.570  1034  1544 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-01 11:16:15.570  1034  1544 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-01 11:16:15.571  1034  1544 D NetworkManagementService: Removing idletimer
09-01 11:16:15.571  1850  1850 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-01 11:16:15.571  1850  1850 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-01 11:16:15.571  1034  1544 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:16:15.571  1034  1544 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-01 11:16:15.572  1034  1034 D WifiHS20: hidePasspointNotification off =false
09-01 11:16:15.574  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:16:15.574  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:16:15.574  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-01 11:16:15.575  1034  1034 D WifiScanningService: SCAN_AVAILABLE : 1
09-01 11:16:15.575  1034  1555 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:16:15.575  1034  1034 D RttService: SCAN_AVAILABLE : 1
09-01 11:16:15.575  1034  1556 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHa,ndler }
09-01 11:16:15.576  1939  1939 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-01 11:16:15.576  1939  1939 D WfdsService: WifiP2pState is changed : false
09-01 11:16:15.576  1034  1034 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-01 11:16:15.577  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-01 11:16:15.577  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-01 11:16:15.577  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-01 11:16:15.577  1939  2284 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
09-01 11:16:15.577  1939  2284 D WfdsService: Set the WFDS Monitor: false
09-01 11:16:15.578  1034  1034 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-01 11:16:15.578  1939  2284 D WfdsMonitor: WFDS Monitor is stopped
09-01 11:16:15.578  1939  2284 D WfdsService: STATE : WfdsDisabledState - enter
09-01 11:16:15.578  1939  2288 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
09-01 11:16:15.578  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-01 11:16:15.578  1034  1535 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-01 11:16:15.578  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-01 11:16:15.578  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-01 11:16:15.578  1034  1535 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-01 11:16:15.579  1034  1537 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
09-01 11:16:15.580  1939  1939 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:16:15.580  1034  1536 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:16:15.580  1034  1536 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:16:15.580  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-01 11:16:15.580  2733  2733 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-01 11:16:15.580  1939  2770 D CtrlSupplicant: Received on exit socket, terminate
09-01 11:16:15.580  1939  2770 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
09-01 11:16:15.580  1939  2770 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
09-01 11:16:15.580  1939  2770 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
09-01 11:16:15.581  1034  1537 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-01 11:16:15.581  1034  1537 D WifiNative-wlan0: doBoolean: SET ps 1
09-01 11:16:15.581  1034  1537 D WifiNative-wlan0: SET ps 1: returned true
09-01 11:16:15.582  3884  3884 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:16:15.582   309   893 D CommandListener: Clearing all IP addresses on wlan0
09-01 11:16:15.582  3884  3884 D BluetoothMapService: STATE_TURNING_OFF
09-01 11:16:15.582  3884  3884 V BluetoothMapService: Handler(): got msg=4
09-01 11:16:15.582  3884  3884 D BluetoothMapService: MAP Service closeService in
09-01 11:16:15.582  3884  3884 D BluetoothMapMasInstance: MAP Service shutdown
09-01 11:16:15.582  3884  3884 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-01 11:16:15.582  3884  3884 V BluetoothMapService: MAP Service closeService out
09-01 11:16:15.583  3884  3884 V BtOppService: Receiver DISABLED_ACTION 
09-01 11:16:15.583  3884  3884 I BtOppRfcommListener: stopping Accept Thread
09-01 11:16:15.583  3884  3884 V BtOppRfcommListener: close mBtServerSocket
09-01 11:16:15.583  3884  3884 V BtOppRfcommListener: waiting for thread to terminate
09-01 11:16:15.583  3884  4343 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-01 11:16:15.584  3884  3884 V BtOppRfcommListener: done waiting for thread to terminate
09-01 11:16:15.585  1939  2284 W WfdsService: DefaultState - msg [9445378] is not handled
09-01 11:16:15.587  6682  6682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:16:15.587  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:16:15.587  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:16:15.587  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-01 11:16:15.587  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:16:15.587  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 11:16:15.587  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:16:15.587  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:16:15.587  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 11:16:15.589  6682  6682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:16:15.589  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:16:15.589  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:16:15.589  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-01 11:16:15.589  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:16:15.589  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 11:16:15.589  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:16:15.589  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:16:15.589  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 11:16:15.592  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-01 11:16:15.592  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-01 11:16:15.593  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-01 11:16:15.619  1034  1092 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6814 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-01 11:16:15.621  1034  1537 D WifiNative-p2p0: doBoolean: TERMINATE
09-01 11:16:15.622  1034  1537 D WifiNative-p2p0: TERMINATE: returned true
09-01 11:16:15.623  1034  1537 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-01 11:16:15.623  1034  1537 E WifiStateMachine: useWiFiOffloading() : false
09-01 11:16:15.623  1034  1537 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-01 11:16:15.624  3884  3884 V BtOppService: onDestroy
09-01 11:16:15.624  1034  1537 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-01 11:16:15.624  1034  1537 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-01 11:16:15.625  1034  1034 D WifiHS20: hidePasspointNotification off =false
09-01 11:16:15.626  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:16:15.627  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:16:15.627  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-01 11:16:15.627  1939  1939 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
09-01 11:16:15.629  3884  3884 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
09-01 11:16:15.630  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
09-01 11:16:15.630  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-01 11:16:15.630  1034  1034 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
09-01 11:16:15.632  6682  6682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:16:15.632  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:16:15.632  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:16:15.632  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-01 11:16:15.632  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 11:16:15.632  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 11:16:15.632  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:16:15.632  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:16:15.632  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 11:16:15.632  6682  6682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:16:15.633  6682  6682 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-01 11:16:15.639  6682  6682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:16:15.639  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:16:15.639  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:16:15.639  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-01 11:16:15.639  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 11:16:15.639  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 11:16:15.639  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:16:15.639  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:16:15.639  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 11:16:15.640  6682  6682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:16:15.640  6682  6682 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-01 11:16:15.658  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,09-01 11:16:15.660  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:16:15.661  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-01 11:16:15.686  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-01 11:16:15.687  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:16:15.688  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:16:15.688  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-01 11:16:15.693  6814  6814 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-01 11:16:15.693  6814  6814 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
09-01 11:16:15.694  6814  6814 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-01 11:16:15.694  6814  6814 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
09-01 11:16:15.695  6814  6814 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-01 11:16:15.695  6814  6814 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-01 11:16:15.726  6795  6795 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
09-01 11:16:15.726  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-01 11:16:15.726  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-01 11:16:15.727  6795  6795 W LG Account v2.2: No ProfileInfo entries
09-01 11:16:15.727  6795  6795 I LG Account v2.2: isEnabled: false
09-01 11:16:15.727  6795  6795 I Feature : [Lifetracker]ver: 4.21.112(40211120)
09-01 11:16:15.727  6795  6795 I Feature : [Lifetracker]Country: EU
,09-01 11:16:15.727  6795  6795 I Feature : [Lifetracker]Operator: OPEN
09-01 11:16:15.727  6795  6795 I Feature : [Lifetracker]Ranking support: false
09-01 11:16:15.727  6795  6795 I Feature : [Lifetracker]Comfort support: false
09-01 11:16:15.727  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:16:15.728  6795  6795 I Feature : [Lifetracker]Accessory: true
09-01 11:16:15.728  6795  6795 I Feature : [Lifetracker]Health device: true
09-01 11:16:15.729  2733  2733 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-01 11:16:15.729  2733  2733 I wpa_supplicant: monitor socket send errors count : 1
09-01 11:16:15.729  2733  2733 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1939-2\x00 that cannot receive messages
09-01 11:16:15.729  1034  2863 D DhcpStateMachine: StoppedState
09-01 11:16:15.729  1034  2863 D DhcpStateMachine: StoppedState{ when=-148ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:16:15.731  1034  2768 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
09-01 11:16:15.731  1034  2768 D WifiMonitor: Dropping event because (p2p0) is stopped
09-01 11:16:15.731  1034  1537 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
09-01 11:16:15.731  6795  6795 I Feature : [Lifetracker]Extra Pedometer: false
09-01 11:16:15.731  6795  6795 I Feature : [Lifetracker]Blood glucose device: false
09-01 11:16:15.731  6795  6795 I Feature : [Lifetracker]Device Number: 3
09-01 11:16:15.731  1034  1537 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
09-01 11:16:15.747  6350  6350 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-01 11:16:15.755  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:16:15.773  1034  1096 D Tethering: InitialState.processMessage what=4
09-01 11:16:15.773  2733  2733 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-01 11:16:15.774  1034  2768 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
09-01 11:16:15.774  1034  2768 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-01 11:16:15.774  1034  2768 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-01 11:16:15.775  2733  2733 W wpa_supplicant: USIM:  scard_deinit function
09-01 11:16:15.775  1034  2768 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
09-01 11:16:15.775  1034  2768 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-01 11:16:15.775  1034  2768 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-01 11:16:15.775  1034  1537 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=179336
09-01 11:16:15.776  1034  1537 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=179336
09-01 11:16:15.776  1034  1537 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=179337  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-01 11:16:15.777  1034  1537 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=179337  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-01 11:16:15.796  1034  1050 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6834 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-01 11:16:15.797  1034  1050 I ActivityManager: Killing 6247:com.android.defcontainer/u0a4 (adj 15): empty #17
09-01 11:16:15.849  1034  1096 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-01 11:16:15.850  1034  1779 W libprocessgroup: failed to open /acct/uid_10004/pid_6247/cgroup.procs: No such file or directory
09-01 11:16:15.850  1034  1537 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
09-01 11:16:15.851  1034  1537 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-01 11:16:15.869  2733  2733 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-01 11:16:15.869  1034  2768 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
09-01 11:16:15.870  1034  2768 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
09-01 11:16:15.870  1034  2768 D WifiMonitor: Disconnecting from the supplicant, no more events
09-01 11:16:15.870  1034  1537 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
,09-01 11:16:15.917  6682  6682 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-01 11:16:15.925  6834  6834 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-01 11:16:15.931  6834  6834 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-01 11:16:15.932  6834  6834 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-01 11:16:15.936  1034  1050 I ActivityManager: Killing 6394:com.google.android.partnersetup/u0a8 (adj 15): empty #17
09-01 11:16:15.954  6814  6814 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,09-01 11:16:15.998  1034  1993 W libprocessgroup: failed to open /acct/uid_10008/pid_6394/cgroup.procs: No such file or directory
,09-01 11:16:16.001  1034  1537 D WifiOffDelayIfNotUsed: stopMonitoring
09-01 11:16:16.001  1034  1537 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-01 11:16:16.001  1034  1537 E WifiStateMachine: useWiFiOffloading() : false
09-01 11:16:16.001  1034  1537 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-01 11:16:16.005  3884  3884 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-01 11:16:16.006  3884  3884 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:16:16.006  3884  3884 V BluetoothPbapReceiver: ***********state = 13
09-01 11:16:16.010  1939  1939 D WfdsService: Supplicant Connection state is changed : false
09-01 11:16:16.010  3884  3884 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
09-01 11:16:16.010  1939  2284 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
09-01 11:16:16.010  1939  2284 D WfdsService: Set the WFDS Monitor: false
09-01 11:16:16.010  1939  2284 D WfdsMonitor: WFDS Monitor is stopped
09-01 11:16:16.011  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
09-01 11:16:16.011  1939  1939 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
,09-01 11:16:16.012  1034  1541 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
,09-01 11:16:16.012  1034  1541 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
09-01 11:16:16.014  3884  3884 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:16:16.014  3884  3884 V BluetoothPbapService: state: 13
09-01 11:16:16.014  3884  3884 V BluetoothPbapService: Pbap Service closeService in
09-01 11:16:16.016  2470  2470 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:16:16.018  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:16:16.019  3884  3884 V BluetoothPbapService: successfully stopped pbap service
09-01 11:16:16.020  3884  3884 V BluetoothPbapService: Pbap Service closeService out
09-01 11:16:16.020  2180  2180 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-01 11:16:16.020  3884  3884 V BluetoothPbapService: Pbap Service onDestroy
09-01 11:16:16.020  3884  3884 V BluetoothPbapService: Pbap Service closeService in
09-01 11:16:16.020  3884  3884 V BluetoothPbapService: Pbap Service closeService out
09-01 11:16:16.020  3884  3884 D LGBluetoothPbapAdapter: [BTUI] cleanup
09-01 11:16:16.021  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:16:16.021  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:16:16.027  6814  6814 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-01 11:16:16.061  6814  6814 D LgDataFeature: LgDataFeature() Constructor: none
,09-01 11:16:16.061  6814  6814 D LgDataFeature: LgDataFeature() Constructor Done, null
09-01 11:16:16.070  6814  6814 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-01 11:16:16.079  1034  1096 D BluetoothManagerService: Message: 20
,09-01 11:16:16.079  1034  1096 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2b5179d6:true
09-01 11:16:16.092  1034  1096 D BluetoothManagerService: Message: 30
,09-01 11:16:16.098  1034  1096 D BluetoothManagerService: Message: 30
09-01 11:16:16.102  6814  6814 D LocalBluetoothProfileManager: Adding local MAP profile
,09-01 11:16:16.106  6814  6814 D BluetoothMap: Create BluetoothMap proxy object
09-01 11:16:16.107  1034  1096 D BluetoothManagerService: Message: 30
,09-01 11:16:16.116  1034  1096 D BluetoothManagerService: Message: 30
09-01 11:16:16.119  6814  6814 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-01 11:16:16.120  6814  6814 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
09-01 11:16:16.137  6814  6814 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,09-01 11:16:16.143  6814  6814 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
09-01 11:16:16.160  6814  6814 D DockEventReceiver: finishStartingService: stopping service
,09-01 11:16:16.182  6814  6814 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,09-01 11:16:16.192  6814  6814 D BluetoothInputDevice: Proxy object connected
09-01 11:16:16.194  6814  6814 D HidProfile: Bluetooth service connected
09-01 11:16:16.197  6814  6814 D BluetoothPan: BluetoothPAN Proxy object connected
,09-01 11:16:16.199  6814  6814 D PanProfile: Bluetooth service connected
,09-01 11:16:16.201  6814  6814 D BluetoothMap: Proxy object connected
09-01 11:16:16.203  6814  6814 D MapProfile: Bluetooth service connected
09-01 11:16:16.203  6814  6814 D BluetoothMap: getConnectedDevices()
09-01 11:16:16.205  6814  6814 D BluetoothMap: Bluetooth is Not enabled
09-01 11:16:16.205  6814  6814 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
09-01 11:16:16.211  6814  6814 D BluetoothPermissionRequest: onReceive
,09-01 11:16:16.216  6814  6814 D LGBluetoothAuthorization: [BTUI] cancel All Notification
09-01 11:16:16.231  1034  2022 I ActivityManager: Killing 6038:com.lge.appbox.client/u0a11 (adj 15): empty #17
,09-01 11:16:16.236  6814  6814 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-01 11:16:16.317  3884  3884 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
,09-01 11:16:16.317  3884  3884 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
09-01 11:16:16.319  3884  3884 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
09-01 11:16:16.324  1034  1952 W libprocessgroup: failed to open /acct/uid_10011/pid_6038/cgroup.procs: No such file or directory
09-01 11:16:16.351  3884  3884 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:16:16.352  3884  3884 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,09-01 11:16:16.355  3884  3884 V BluetoothFtpService: Ftp Service onStartCommand
09-01 11:16:16.355  3884  3884 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:16:16.356  3884  3884 V BluetoothFtpService: Ftp Service closeService
09-01 11:16:16.357  3884  3884 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
09-01 11:16:16.361  3884  3884 V BluetoothFtpService: successfully stopped ftp service
09-01 11:16:16.361  3884  3884 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-01 11:16:16.361  3884  3884 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-01 11:16:16.361  3884  3884 V BluetoothSapReceiver: SapReceiver onReceive 
09-01 11:16:16.361  3884  3884 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:16:16.362  3884  3884 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
09-01 11:16:16.362  3884  3884 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-01 11:16:16.363  3884  3884 V BluetoothFtpService: Ftp Service onDestroy
09-01 11:16:16.363  3884  3884 V BluetoothFtpService: Ftp Service closeService
09-01 11:16:16.414  1034  1780 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6868 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,09-01 11:16:16.418  3884  3884 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:16:16.420  3884  3884 V BluetoothSapService: state: 13
09-01 11:16:16.420  3884  3884 V BluetoothSapService: Stopping SAP server process
09-01 11:16:16.423  3884  3884 V BluetoothSapService: Sap Service closeSapService in
09-01 11:16:16.423  3884  3884 V BluetoothSapService: Close listen Socket : 
09-01 11:16:16.423  3884  3884 V BluetoothSapService: Close rfcomm Socket : 
09-01 11:16:16.423  3884  3884 V BluetoothSapService: Close sapd  Socket : 
09-01 11:16:16.426  3884  3884 V BluetoothSapService: Sap Service closeSapService out
,09-01 11:16:16.428  3884  3884 V BluetoothSapService: Sap Service onDestroy
09-01 11:16:16.428  3884  3884 V BluetoothSapService: Sap Service closeSapService in
09-01 11:16:16.428  3884  3884 V BluetoothSapService: Close listen Socket : 
09-01 11:16:16.428  3884  3884 V BluetoothSapService: Close rfcomm Socket : 
09-01 11:16:16.428  3884  3884 V BluetoothSapService: Close sapd  Socket : 
09-01 11:16:16.482  1034  1780 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6895 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-01 11:16:16.484  3884  3884 V BluetoothSapService: Sap Service closeSapService out
,09-01 11:16:16.505   349   349 I art     : Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 449us total 23.197ms
,09-01 11:16:16.508  3884  3967 D bt_hci_bdroid: cleanup
09-01 11:16:16.508  3884  4253 I bt_userial_mct: exiting userial_read_thread
09-01 11:16:16.508  3884  4253 D bt_userial_mct: Leaving userial_evt_read_thread()
09-01 11:16:16.508  3884  4075 I bt_lpm  : LPM is already off!!!
09-01 11:16:16.509  3884  4073 W bt-btif : ag scb idx 1 not allocated
09-01 11:16:16.509  3884  4073 E bt-btif : BTA AG is already disabled, ignoring ...
09-01 11:16:16.509  3884  4073 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-01 11:16:16.509  3884  4073 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-01 11:16:16.509  3884  4073 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-01 11:16:16.509  3884  4073 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-01 11:16:16.509  3884  4073 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-01 11:16:16.509  3884  4073 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-01 11:16:16.509  3884  4073 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-01 11:16:16.509  3884  4073 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-01 11:16:16.509  3884  4073 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-01 11:16:16.509  3884  4073 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-01 11:16:16.509  3884  4073 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-01 11:16:16.509  3884  4073 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-01 11:16:16.509  3884  4073 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-01 11:16:16.509  3884  4073 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-01 11:16:16.509  3884  4073 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-01 11:16:16.509  3884  4073 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-01 11:16:16.509  3884  4073 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-01 11:16:16.509  3884  4073 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-01 11:16:16.509  3884  4073 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-01 11:16:16.509  3884  3967 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-01 11:16:16.509  3884  4075 I bt_vendor: hw_epilog_process
09-01 11:16:16.510  3884  3967 D bt_hci_bdroid: cleanup Finalizing cleanup
09-01 11:16:16.510  3884  3967 D bt_userial_mct: userial_close
09-01 11:16:16.510  3884  3967 E bt_userial_mct: pthread_join() FAILED result:3
09-01 11:16:16.510  3884  3967 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
09-01 11:16:16.529   349   349 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 410us total 22.250ms
,09-01 11:16:16.530  6868  6868 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-01 11:16:16.548   349   349 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 420us total 19.323ms
,09-01 11:16:16.555  6895  6895 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-01 11:16:16.562  1034  1034 D DSQN    : EVENT_INTERNET_CHECK_ENABLE received
09-01 11:16:16.570  1034  1893 I ActivityManager: Killing 6061:com.android.contacts/u0a19 (adj 15): empty #17
,09-01 11:16:16.598  3884  3967 D bt_hci_bdroid: set_power 0
09-01 11:16:16.598  3884  3967 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-01 11:16:16.598  3884  3967 I bt_vendor: bluetooth satus is on
09-01 11:16:16.598  3884  3967 I bt_vendor: bt-vendor : resetting BT status
09-01 11:16:16.598  3884  3967 I bt_vendor: Starting hciattach daemon
09-01 11:16:16.598  3884  3967 I bt_vendor: try to set false
09-01 11:16:16.599  3884  3967 I bt_vendor: Starting hciattach daemon
,09-01 11:16:16.599  3884  3967 I bt_vendor: try to set false
,09-01 11:16:16.599  3884  3967 I bt_vendor: cleanup
09-01 11:16:16.600  3884  4073 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-01 11:16:16.600  3884  3967 I GKI_LINUX: GKI_exit_task 0 done
09-01 11:16:16.600  3884  3967 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
09-01 11:16:16.602  3884  3964 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-01 11:16:16.611  1034  1049 W libprocessgroup: failed to open /acct/uid_10019/pid_6061/cgroup.procs: No such file or directory
,09-01 11:16:16.615  3884  3884 D HeadsetService: Received stop request...Stopping profile...
09-01 11:16:16.616  3884  3884 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-01 11:16:16.616  3884  3884 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-01 11:16:16.616  3884  3884 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ec6e996
09-01 11:16:16.616  3884  3994 D HeadsetStateMachine: Exit Disconnected: -1
09-01 11:16:16.616  6868  6868 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
09-01 11:16:16.616  1034  1034 D BluetoothHeadset: Proxy object disconnected
09-01 11:16:16.616  1034  1034 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-01 11:16:16.617  3884  3884 D A2dpService: Received stop request...Stopping profile...
09-01 11:16:16.617  1850  1850 D BluetoothHeadset: Proxy object disconnected
09-01 11:16:16.618  1850  1850 D BluetoothHeadset: Proxy object disconnected
09-01 11:16:16.618  3884  4036 D A2dpStateMachine: Exit Disconnected: -1
09-01 11:16:16.619  1850  1850 D BluetoothHeadset: Proxy object disconnected
09-01 11:16:16.620  3884  3884 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
09-01 11:16:16.624  3884  3884 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
,09-01 11:16:16.624  3884  3884 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
09-01 11:16:16.624  3884  3884 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ec6e996
09-01 11:16:16.625  1034  1034 D BluetoothA2dp: Proxy object disconnected
09-01 11:16:16.625  1034  1034 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-01 11:16:16.626  3884  3884 D HidService: Received stop request...Stopping profile...
09-01 11:16:16.626  3884  3884 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ec6e996
09-01 11:16:16.627  3884  3884 D HeadsetStateMachine: Unbinding service...
09-01 11:16:16.627  6814  6814 D BluetoothInputDevice: Proxy object disconnected
09-01 11:16:16.627  6814  6814 D HidProfile: Bluetooth service disconnected
09-01 11:16:16.628  3884  3964 D BluetoothAdapterState: Stopping profile services that were post enabled
09-01 11:16:16.628  3884  3884 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-01 11:16:16.628  3884  3884 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-01 11:16:16.628  3884  3884 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-01 11:16:16.628  3884  3884 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-01 11:16:16.628  3884  3884 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-01 11:16:16.628  3884  3884 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-01 11:16:16.628  3884  3884 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-01 11:16:16.628  3884  3884 D HealthService: Received stop request...Stopping profile...
09-01 11:16:16.628  3884  3884 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ec6e996
09-01 11:16:16.629  3884  3884 D PanService: Received stop request...Stopping profile...
09-01 11:16:16.630  3884  3884 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ec6e996
09-01 11:16:16.630  3884  3884 D BtGatt.DebugUtils: handleDebugAction() action=null
09-01 11:16:16.631  3884  3884 D BtGatt.GattService: Received stop request...Stopping profile...
09-01 11:16:16.631  6814  6814 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-01 11:16:16.631  3884  3884 D BtGatt.GattService: stop()
09-01 11:16:16.631  6814  6814 D PanProfile: Bluetooth service disconnected
09-01 11:16:16.631  3884  3884 D BtGatt.AdvertiseManager: advertise clients cleared
09-01 11:16:16.632  3884  3884 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ec6e996
09-01 11:16:16.632  3884  3884 I BluetoothA2dpServiceJni: cleanupNative
09-01 11:16:16.632  3884  4037 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-01 11:16:16.633  3884  3884 I GKI_LINUX: GKI_exit_task 2 done
09-01 11:16:16.633  3884  3884 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-01 11:16:16.633  3884  3884 D BluetoothMapService: Received stop request...Stopping profile...
09-01 11:16:16.633  3884  3884 D BluetoothMapService: stop()
09-01 11:16:16.634  3884  3884 D BluetoothMapEmailAppObserver: deinitObservers()
09-01 11:16:16.634  3884  3884 D BluetoothMapEmailAppObserver: removeReceiver()
09-01 11:16:16.635  3884  3884 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ec6e996
09-01 11:16:16.636  3884  3884 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-01 11:16:16.636  3884  3884 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-01 11:16:16.636  3884  3884 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-01 11:16:16.636  3884  3884 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-01 11:16:16.636  3884  3884 W LGBluetoothHealthServiceJni: Cleaning up, Bluetooth Health object
09-01 11:16:16.636  3884  3884 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-01 11:16:16.636  3884  3884 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-01 11:16:16.638  3884  3884 V BluetoothMapService: Handler(): got msg=4
09-01 11:16:16.638  3884  3884 D BluetoothMapService: MAP Service closeService in
09-01 11:16:16.638  3884  3884 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-01 11:16:16.638  3884  3884 V BluetoothMapService: MAP Service closeService out
09-01 11:16:16.638  3884  3964 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
09-01 11:16:16.639  3884  3964 D BluetoothAdapterProperties: Setting state to 10
09-01 11:16:16.639  3884  3964 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-01 11:16:16.639  1034  1096 D BluetoothManagerService: Message: 60
09-01 11:16:16.639  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
09-01 11:16:16.639  1034  1096 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
09-01 11:16:16.639  3884  3964 I BluetoothAdapterState: Entering OffState
09-01 11:16:16.639  3884  3884 D BluetoothMapService: cleanup()
09-01 11:16:16.639  3884  3884 D BluetoothMapService: MAP Service closeService in
09-01 11:16:16.639  3884  3884 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-01 11:16:16.639  3884  3884 V BluetoothMapService: MAP Service closeService out
,09-01 11:16:16.640  1850  2452 D BluetoothHeadset: onBluetoothStateChange: up=false
09-01 11:16:16.641  6814  6814 D BluetoothMap: Proxy object disconnected
09-01 11:16:16.641  6814  6814 D MapProfile: Bluetooth service disconnected
09-01 11:16:16.641  1850  1866 D BluetoothHeadset: onBluetoothStateChange: up=false
09-01 11:16:16.642  1034  1096 D BluetoothHeadset: onBluetoothStateChange: up=false
09-01 11:16:16.642  6814  6830 D BluetoothPan: onBluetoothStateChange on: false
09-01 11:16:16.642  1034  1096 D BluetoothA2dp: onBluetoothStateChange: up=false
09-01 11:16:16.643  1850  4446 D BluetoothHeadset: onBluetoothStateChange: up=false
09-01 11:16:16.643  6814  6829 D BluetoothPbap: onBluetoothStateChange: up=false
09-01 11:16:16.644  6814  6830 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-01 11:16:16.645  6814  6829 D BluetoothMap: onBluetoothStateChange: up=false
09-01 11:16:16.645  1034  1096 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
09-01 11:16:16.645  1034  1096 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
09-01 11:16:16.648  1034  1096 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
09-01 11:16:16.648  1034  1096 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
09-01 11:16:16.648  1034  1096 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@3c13a85f mBinding = false
09-01 11:16:16.648  1034  1096 D BluetoothManagerService: Sending unbind request.
09-01 11:16:16.649  1034  1096 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
09-01 11:16:16.650  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-01 11:16:16.651  1939  1939 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:16:16.652  1939  2084 D LGBluetoothAPIService: Message: 2
09-01 11:16:16.653  1939  2084 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@214730c1 mBinding = false
09-01 11:16:16.653  1939  2084 D LGBluetoothAPIService: Sending unbind request.
,09-01 11:16:16.655  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:16:16.657  6814  6814 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,09-01 11:16:16.659  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:16:16.659  6814  6814 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
09-01 11:16:16.659  6814  6814 D LGBluetoothEventManager: [BTUI] clear device connection state
09-01 11:16:16.659  1602  1602 D BluetoothAdapter: 521901550: getState() :  mService = null. Returning STATE_OFF
09-01 11:16:16.659  1602  1602 D BluetoothAdapter: 521901550: getState() :  mService = null. Returning STATE_OFF
09-01 11:16:16.660  3884  3967 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
09-01 11:16:16.662  6814  6814 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-01 11:16:16.662  3884  3884 I GKI_LINUX: GKI_exit_task 1 done
09-01 11:16:16.662  3884  3884 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
09-01 11:16:16.665  3884  3884 I BluetoothServiceJni: cleanupNative: return from cleanup
09-01 11:16:16.665  3884  3884 I art     : --- WEIRD: removing null entry 246
09-01 11:16:16.665  3884  3884 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
09-01 11:16:16.665  3884  3884 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
,09-01 11:16:16.668  3884  3884 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
09-01 11:16:16.669  3884  3884 I art     : System.exit called, status: 0
09-01 11:16:16.669  6814  6814 D DockEventReceiver: finishStartingService: stopping service
09-01 11:16:16.669  3884  3884 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
09-01 11:16:16.678  6868  6868 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
09-01 11:16:16.679  6868  6868 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
,09-01 11:16:16.679  6868  6868 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
09-01 11:16:16.679  6868  6868 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
09-01 11:16:16.680  6868  6868 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
09-01 11:16:16.682  6868  6868 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
09-01 11:16:16.687  6868  6868 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
09-01 11:16:16.693  6868  6868 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-01 11:16:16.696  6868  6868 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-01 11:16:16.704  6814  6814 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
09-01 11:16:16.704   313   313 V AudioFlinger: 3884 died, releasing its sessions
09-01 11:16:16.704   313   313 V AudioFlinger:  pid 1850 @ 0
09-01 11:16:16.704   313   313 V AudioFlinger:  pid 3463 @ 1
09-01 11:16:16.704   313   313 V AudioFlinger:  pid 3463 @ 2
,09-01 11:16:16.769  1034  1893 I ActivityManager: Process com.android.bluetooth (pid 3884) has died
09-01 11:16:16.769  1034  1893 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,09-01 11:16:16.777  6868  6868 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-01 11:16:16.782  2180  2180 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-01 11:16:16.784  6350  6350 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-01 11:16:16.787  6868  6868 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
09-01 11:16:16.796  6868  6868 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
09-01 11:16:16.801  6834  6834 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-01 11:16:16.801  6834  6834 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,09-01 11:16:16.801  6834  6834 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-01 11:16:16.810  6814  6814 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-01 11:16:16.821  6814  6814 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-01 11:16:16.827  6814  6814 D BluetoothPermissionRequest: onReceive
,09-01 11:16:16.829  6814  6814 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-01 11:16:16.829  6814  6814 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
09-01 11:16:16.832  6814  6814 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,09-01 11:16:16.907  1034  1050 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6920 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
09-01 11:16:16.921  6868  6868 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-01 11:16:16.922  6868  6868 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-01 11:16:16.926  6868  6868 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-01 11:16:16.930  6350  6350 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-01 11:16:16.933  6834  6834 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-01 11:16:16.933  6834  6834 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-01 11:16:16.933  6834  6834 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-01 11:16:16.937  6814  6814 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-01 11:16:16.946  6814  6814 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-01 11:16:16.953  6868  6868 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-01 11:16:16.954  6868  6868 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-01 11:16:16.955  6868  6868 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-01 11:16:17.038  1034  1049 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6937 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,09-01 11:16:17.073  6920  6920 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
09-01 11:16:17.074  6920  6920 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-01 11:16:17.074  6920  6920 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
09-01 11:16:17.075  6920  6920 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-01 11:16:17.094  6920  6920 D BluetoothAdapterApp: Loading JNI Library
,09-01 11:16:17.120  6834  6834 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-01 11:16:17.124  6814  6814 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-01 11:16:17.130  6814  6814 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-01 11:16:17.130  6920  6920 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@3bade51f Instance Count = 1
09-01 11:16:17.139  6920  6920 D BluetoothAdapterApp: onCreate
,09-01 11:16:17.146  6814  6814 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-01 11:16:17.147  6814  6814 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-01 11:16:17.147  6814  6814 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-01 11:16:17.147  6814  6814 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-01 11:16:17.148  6814  6814 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-01 11:16:17.150  6937  6956 W FormManager: Network not available. Please check & try again.
09-01 11:16:17.156  6814  6814 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-01 11:16:17.157  6814  6814 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-01 11:16:17.157  6814  6814 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
,09-01 11:16:17.157  6814  6814 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-01 11:16:17.157  6814  6814 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-01 11:16:17.157  6814  6814 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-01 11:16:17.164  4322  4322 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,09-01 11:16:17.164  4322  4322 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-01 11:16:17.164  6920  6920 D ProfileConfigQcom: [BTUI] HeadsetService is supported
09-01 11:16:17.165  6920  6920 D ProfileConfigQcom: Adding HeadsetService
09-01 11:16:17.165  6920  6920 D ProfileConfigQcom: [BTUI] A2dpService is supported
09-01 11:16:17.165  6920  6920 D ProfileConfigQcom: Adding A2dpService
09-01 11:16:17.165  6920  6920 D ProfileConfigQcom: [BTUI] HidService is supported
09-01 11:16:17.165  6920  6920 D ProfileConfigQcom: Adding HidService
09-01 11:16:17.165  6937  6957 V FormManager: Network unavailable.
09-01 11:16:17.166  6920  6920 D ProfileConfigQcom: [BTUI] HealthService is supported
09-01 11:16:17.166  6920  6920 D ProfileConfigQcom: Adding HealthService
09-01 11:16:17.166  6920  6920 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
09-01 11:16:17.167  4322  4322 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-01 11:16:17.167  6920  6920 D ProfileConfigQcom: [BTUI] PanService is supported
09-01 11:16:17.167  6920  6920 D ProfileConfigQcom: Adding PanService
09-01 11:16:17.167  6920  6920 D ProfileConfigQcom: [BTUI] GattService is supported
09-01 11:16:17.167  6920  6920 D ProfileConfigQcom: Adding GattService
09-01 11:16:17.168  6920  6920 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
09-01 11:16:17.168  6937  6957 V FormManager: Network unavailable.
09-01 11:16:17.168  6920  6920 D ProfileConfigQcom: Adding BluetoothMapService
09-01 11:16:17.168  6920  6920 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
09-01 11:16:17.170  6920  6920 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
09-01 11:16:17.174  6814  6814 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
09-01 11:16:17.174  4322  4322 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-01 11:16:17.179  6920  6920 V LGMDMManagerInternal: Create singleton instance
09-01 11:16:17.181  6834  6834 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
09-01 11:16:17.182  6834  6834 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,09-01 11:16:17.182  6834  6834 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-01 11:16:17.183  4322  6961 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-01 11:16:17.184  4322  6962 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-01 11:16:17.185  4322  6962 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-01 11:16:17.185  6814  6814 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-01 11:16:17.195  6937  6964 V FormManager: Network unavailable.
09-01 11:16:17.193  6937  6963 W FormManager: Network not available. Please check & try again.
09-01 11:16:17.197  6937  6964 V FormManager: Network unavailable.
09-01 11:16:17.198  6814  6814 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-01 11:16:17.203  1034  2048 I ActivityManager: Killing 6446:com.lge.email/u0a23 (adj 15): empty #17
,09-01 11:16:17.259  1034  1049 W libprocessgroup: failed to open /acct/uid_10023/pid_6446/cgroup.procs: No such file or directory
,09-01 11:16:17.264  6920  6920 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:16:17.271  6920  6920 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-01 11:16:17.272  6920  6920 V BluetoothSapReceiver: [BTUI] region:EU country:EU
,09-01 11:16:17.272  6920  6920 V BluetoothSapReceiver: SapReceiver onReceive 
09-01 11:16:17.276  6920  6920 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:16:17.276  6920  6920 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
09-01 11:16:17.277  6868  6868 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
09-01 11:16:17.278  6868  6868 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
09-01 11:16:17.279  6868  6868 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
09-01 11:16:17.291  6895  6895 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
09-01 11:16:17.293  1034  1779 I ActivityManager: Killing 6084:com.android.gallery3d/u0a27 (adj 15): empty #17
,09-01 11:16:17.320  6868  6868 D LgDataFeature: LgDataFeature() Constructor: none
09-01 11:16:17.321  6868  6868 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-01 11:16:17.330  6868  6868 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
09-01 11:16:17.331  6868  6868 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
09-01 11:16:17.331  6868  6868 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
09-01 11:16:17.331  6868  6868 V SoundPool: doLoad: loading sample sampleID=1
09-01 11:16:17.331  6868  6868 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
09-01 11:16:17.335  6868  6968 V SoundPool: Start decode
09-01 11:16:17.335  6868  6968 V MediaPlayer[Native]: decode(31, 10857164, 17813)
,09-01 11:16:17.338   313  2203 V MediaPlayerService: decode(23, 10857164, 17813)
,09-01 11:16:17.338   313  2203 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
09-01 11:16:17.338   313  2203 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
09-01 11:16:17.339   313  2203 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
09-01 11:16:17.339   313  2203 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
09-01 11:16:17.339   313  2203 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
,09-01 11:16:17.339   313  2203 V MediaPlayerService: player type = 3
09-01 11:16:17.339   313  2203 V AwesomePlayer: AwesomePlayer create()
09-01 11:16:17.340   313  2203 V AwesomePlayer: reset_l() 
09-01 11:16:17.340   313  2203 V AwesomePlayer: cancelPlayerEvents
09-01 11:16:17.340   313  2203 V AwesomePlayer: setAudioSink() 
09-01 11:16:17.340   313  2203 V AwesomePlayer: reset_l() 
09-01 11:16:17.340   313  2203 V AudioCache: notify(0xb0409740, 8, 0, 0)
09-01 11:16:17.340   313  2203 V AudioCache: ignored
09-01 11:16:17.341   313  2203 V AwesomePlayer: cancelPlayerEvents
09-01 11:16:17.341   313  2203 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
09-01 11:16:17.341   313  2203 V AwesomePlayer: setDataSource_l dataSource
09-01 11:16:17.341   313  2203 V LGParserOSAL: SniffLGParser start
09-01 11:16:17.341   313  2203 V LGParserOSAL: MainType:5, SubType=0
09-01 11:16:17.341   313  2203 V LGParserOSAL: #### check Mime : application/ogg
09-01 11:16:17.341   313  2203 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
09-01 11:16:17.341   313  2203 E MediaExtractor: Use LGExtractor :application/ogg 
09-01 11:16:17.370  1034  2022 W libprocessgroup: failed to open /acct/uid_10027/pid_6084/cgroup.procs: No such file or directory
,09-01 11:16:17.378  6868  6868 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
09-01 11:16:17.379  6559  6559 D UEI.SmartControl: QS Service created
09-01 11:16:17.382  6868  6868 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,09-01 11:16:17.383  6868  6868 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
09-01 11:16:17.396  6559  6559 I UEI.SmartControl: Service initServices...
09-01 11:16:17.396  6559  6559 D UEI.SmartControl: QS start get config
,09-01 11:16:17.406   313  2203 V LGParserOSAL: supported mime: application/ogg
09-01 11:16:17.406   313  2203 V AwesomePlayer: setDataSource_l() extractor countTracks=1
09-01 11:16:17.406   313  2203 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
09-01 11:16:17.406   313  2203 V AwesomePlayer: mBitrate = -1 bits/sec
09-01 11:16:17.407   313  2203 V AwesomePlayer: AudioTrack Setting
,09-01 11:16:17.407   313  2203 V AwesomePlayer: AudioTrack Setting channelCount = 2
09-01 11:16:17.407   313  2203 V AwesomePlayer: setAudioSource() 
09-01 11:16:17.407   313  2203 V MediaPlayerService: prepare
09-01 11:16:17.407   313  2203 V AwesomePlayer: prepareAsync_l() 
09-01 11:16:17.407   313  2203 V MediaPlayerService: wait for prepare
09-01 11:16:17.407   313  6969 V AwesomePlayer: onPrepareAsyncEvent() 
09-01 11:16:17.407   313  6969 V AwesomePlayer: initAudioDecoder() 
09-01 11:16:17.407   313  6969 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-01 11:16:17.408   313  6969 V AudioSystem: isOffloadSupported()
09-01 11:16:17.408   313  6969 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-01 11:16:17.408   313  6969 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-01 11:16:17.408   313  6969 I AudioFlinger: isAudioPlaybackHookOn() false
09-01 11:16:17.408   313  6969 V AwesomePlayer: getUseOffload() = 0 
09-01 11:16:17.408   313  6969 V OMXCodec: OMXCodec::Create
09-01 11:16:17.408   313  6969 V OMXCodec: findMatchingCodecs()
09-01 11:16:17.408   313  6969 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
09-01 11:16:17.408   313  6969 V OMXCodec: matchingCodecs.size()=1
09-01 11:16:17.409   313  6969 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
09-01 11:16:17.413   313  6969 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
09-01 11:16:17.413   313  6969 V LGCodecAdapter: LG Codec Adapter start
09-01 11:16:17.413   313  6969 V OMXCodec: OMXCodec Createtor
09-01 11:16:17.413   313  6969 V OMXCodec: setComponentRole
09-01 11:16:17.413   313  6969 V OMXCodec: configureCodec protected=0
09-01 11:16:17.413   313  6969 V LGCodecAdapter: called getLGCodecSpecificData
09-01 11:16:17.413   313  6969 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
09-01 11:16:17.413   313  6969 V LGCodecOSAL: Called LGconfigureCodecMETA
09-01 11:16:17.413   313  6969 V LGCodecOSAL: Called LGconfigureCodecMSG
09-01 11:16:17.413   313  6969 V LGCodecOSAL: Not support LGCodec
09-01 11:16:17.413   313  6969 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-01 11:16:17.413   313  6969 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
09-01 11:16:17.413   313  6969 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
09-01 11:16:17.413  6868  6868 V LGMDMManager: Create singleton instance
09-01 11:16:17.413   313  6969 I AwesomePlayer: Could not offload audio decode, try pcm offload
09-01 11:16:17.413   313  6969 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-01 11:16:17.413   313  6969 V AudioSystem: isOffloadSupported()
09-01 11:16:17.413   313  6969 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-01 11:16:17.413   313  6969 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-01 11:16:17.413   313  6969 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
09-01 11:16:17.413   313  6969 V OMXCodec: init()
09-01 11:16:17.413   313  6969 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
09-01 11:16:17.413   313  6969 V OMXCodec: allocateBuffers
09-01 11:16:17.413   313  6969 V OMXCodec: allocateBuffersOnPort portIndex=0
09-01 11:16:17.413   313  6969 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
09-01 11:16:17.414   313  6969 V OMXCodec: [OMX.googl,e.vorbis.decoder] allocated buffer 0xb54f7650 on input port
09-01 11:16:17.414   313  6969 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7970 on input port
09-01 11:16:17.414   313  6969 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on input port
09-01 11:16:17.414   313  6969 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on input port
09-01 11:16:17.414   313  6969 V OMXCodec: allocateBuffersOnPort portIndex=1
09-01 11:16:17.414   313  6969 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-01 11:16:17.414   313  6969 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on output port
09-01 11:16:17.414   313  6969 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
09-01 11:16:17.414   313  6969 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on output port
09-01 11:16:17.414   313  6969 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7e20 on output port
09-01 11:16:17.414   313  6969 V OMXCodec: init() mAsyncCompletion wait!!! 
09-01 11:16:17.414   313  6971 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-01 11:16:17.414   313  6971 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-01 11:16:17.415   313  6971 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
09-01 11:16:17.418   313  6971 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
09-01 11:16:17.418   313  6971 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
09-01 11:16:17.418   313  6971 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
09-01 11:16:17.418   313  6969 V OMXCodec: init() mAsyncCompletion wait free! 
09-01 11:16:17.418   313  6969 V AwesomePlayer: finishAsyncPrepare_l() 
09-01 11:16:17.418   313  6969 V AudioCache: notify(0xb0409740, 5, 0, 0)
09-01 11:16:17.418   313  6969 V AudioCache: ignored
09-01 11:16:17.418   313  6969 V AudioCache: notify(0xb0409740, 1, 0, 0)
09-01 11:16:17.418   313  6969 V AudioCache: prepared
09-01 11:16:17.418   313  2203 V AudioCache: wait - success
,09-01 11:16:17.418   313  2203 V MediaPlayerService: start
09-01 11:16:17.418   313  2203 V AwesomePlayer: play_l() 
09-01 11:16:17.418   313  2203 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
09-01 11:16:17.418   313  2203 V AwesomePlayer: createAudioPlayer_l
09-01 11:16:17.418   313  2203 V AwesomePlayer: seekAudioIfNecessary_l() 
09-01 11:16:17.418   313  2203 V AwesomePlayer: startAudioPlayer_l() 
09-01 11:16:17.418   313  2203 D AudioPlayer: start of Playback, useOffload 0
09-01 11:16:17.419   313  2203 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-01 11:16:17.419   313  2203 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
,09-01 11:16:17.421   313  6971 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
09-01 11:16:17.421   313  6971 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
09-01 11:16:17.421   313  6971 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
09-01 11:16:17.421   313  6971 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
09-01 11:16:17.421   313  6971 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
09-01 11:16:17.421   313  6971 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-01 11:16:17.421   313  6971 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884848
09-01 11:16:17.421   313  6971 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-01 11:16:17.421   313  6971 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885008
,09-01 11:16:17.421   313  6971 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-01 11:16:17.422   313  6971 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885088
09-01 11:16:17.422   313  6971 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-01 11:16:17.422   313  6971 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885728
09-01 11:16:17.422   313  6971 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-01 11:16:17.422   313  6971 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
09-01 11:16:17.422   313  6971 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-01 11:16:17.422   313  6971 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
09-01 11:16:17.422   313  6971 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
09-01 11:16:17.422   313  6971 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
09-01 11:16:17.422   313  6971 V OMXCodec: allocateBuffersOnPort portIndex=1
09-01 11:16:17.422   313  6971 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,09-01 11:16:17.422   313  6971 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on output port
09-01 11:16:17.422   313  6971 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
09-01 11:16:17.422   313  6971 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on output port
09-01 11:16:17.422   313  6971 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57c01f0 on output port
09-01 11:16:17.422   313  6971 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
09-01 11:16:17.422   313  6971 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
09-01 11:16:17.423   313  2203 V AudioCache: open(48000, 2, 0x0, 1, 4)
09-01 11:16:17.423   313  2203 V AudioCache: notify(0xb0409740, 6, 0, 0)
09-01 11:16:17.423   313  2203 V AudioCache: ignored
09-01 11:16:17.424   313  2203 V MediaPlayerService: wait for playback complete
09-01 11:16:17.424   313  6972 V AudioCache: write(0xb16db000, 4096)
09-01 11:16:17.424   313  6972 V AudioCache: memcpy(0xac300000, 0xb16db000, 4096)
,09-01 11:16:17.426   313  6972 V AudioCache: write(0xb16db000, 4096)
09-01 11:16:17.426   313  6972 V AudioCache: memcpy(0xac301000, 0xb16db000, 4096)
09-01 11:16:17.426   313  6972 V AudioCache: write(0xb16db000, 4096)
09-01 11:16:17.426   313  6972 V AudioCache: memcpy(0xac302000, 0xb16db000, 4096)
09-01 11:16:17.426   313  6972 V AudioCache: write(0xb16db000, 4096)
09-01 11:16:17.426   313  6972 V AudioCache: memcpy(0xac303000, 0xb16db000, 4096)
09-01 11:16:17.427   313  6972 V AudioCache: write(0xb16db000, 4096)
09-01 11:16:17.427   313  6972 V AudioCache: memcpy(0xac304000, 0xb16db000, 4096)
09-01 11:16:17.428   313  6972 V AudioCache: write(0xb16db000, 4096)
,09-01 11:16:17.429   313  6972 V AudioCache: memcpy(0xac305000, 0xb16db000, 4096)
09-01 11:16:17.429   313  6972 V AudioCache: write(0xb16db000, 4096)
09-01 11:16:17.429   313  6972 V AudioCache: memcpy(0xac306000, 0xb16db000, 4096)
09-01 11:16:17.429   313  6972 V AudioCache: write(0xb16db000, 4096)
09-01 11:16:17.429   313  6972 V AudioCache: memcpy(0xac307000, 0xb16db000, 4096)
,09-01 11:16:17.430   313  6972 V AudioCache: write(0xb16db000, 4096)
,09-01 11:16:17.430   313  6972 V AudioCache: memcpy(0xac308000, 0xb16db000, 4096)
09-01 11:16:17.430   313  6972 V AudioCache: write(0xb16db000, 4096)
09-01 11:16:17.430   313  6972 V AudioCache: memcpy(0xac309000, 0xb16db000, 4096)
09-01 11:16:17.431   313  6972 V AudioCache: write(0xb16db000, 4096)
09-01 11:16:17.431   313  6972 V AudioCache: memcpy(0xac30a000, 0xb16db000, 4096)
09-01 11:16:17.431   313  6972 V AudioCache: write(0xb16db000, 4096)
09-01 11:16:17.431   313  6972 V AudioCache: memcpy(0xac30b000, 0xb16db000, 4096)
09-01 11:16:17.431   313  6972 V AudioCache: write(0xb16db000, 4096)
,09-01 11:16:17.431   313  6972 V AudioCache: memcpy(0xac30c000, 0xb16db000, 4096)
09-01 11:16:17.432   313  6972 V AudioCache: write(0xb16db000, 4096)
09-01 11:16:17.432   313  6972 V AudioCache: memcpy(0xac30d000, 0xb16db000, 4096)
09-01 11:16:17.432   313  6972 V AudioCache: write(0xb16db000, 4096)
09-01 11:16:17.432   313  6972 V AudioCache: memcpy(0xac30e000, 0xb16db000, 4096)
09-01 11:16:17.433   313  6972 V AudioCache: write(0xb16db000, 4096)
09-01 11:16:17.433   313  6972 V AudioCache: memcpy(0xac30f000, 0xb16db000, 4096)
,09-01 11:16:17.433   313  6972 V AudioCache: write(0xb16db000, 4096)
09-01 11:16:17.433   313  6972 V AudioCache: memcpy(0xac310000, 0xb16db000, 4096)
09-01 11:16:17.434   313  6972 V AudioCache: write(0xb16db000, 4096)
09-01 11:16:17.434   313  6972 V AudioCache: memcpy(0xac311000, 0xb16db000, 4096)
09-01 11:16:17.435   313  6972 V AudioCache: write(0xb16db000, 4096)
09-01 11:16:17.435   313  6972 V AudioCache: memcpy(0xac312000, 0xb16db000, 4096)
09-01 11:16:17.435   313  6972 V AudioCache: write(0xb16db000, 4096)
09-01 11:16:17.435   313  6972 V AudioCache: memcpy(0xac313000, 0xb16db000, 4096)
09-01 11:16:17.436   313  6972 V AudioCache: write(0xb16db000, 4096)
,09-01 11:16:17.436   313  6972 V AudioCache: memcpy(0xac314000, 0xb16db000, 4096)
09-01 11:16:17.437   313  6972 V AudioCache: write(0xb16db000, 4096)
09-01 11:16:17.437   313  6972 V AudioCache: memcpy(0xac315000, 0xb16db000, 4096)
09-01 11:16:17.437   313  6972 V AudioCache: write(0xb16db000, 4096)
09-01 11:16:17.437   313  6972 V AudioCache: memcpy(0xac316000, 0xb16db000, 4096)
09-01 11:16:17.438   313  6972 V AudioCache: write(0xb16db000, 4096)
09-01 11:16:17.438   313  6972 V AudioCache: memcpy(0xac317000, 0xb16db000, 4096)
09-01 11:16:17.439   313  6972 V AudioCache: write(0xb16db000, 4096)
,09-01 11:16:17.439   313  6972 V AudioCache: memcpy(0xac318000, 0xb16db000, 4096)
09-01 11:16:17.439   313  6972 V AudioCache: write(0xb16db000, 4096)
09-01 11:16:17.439   313  6972 V AudioCache: memcpy(0xac319000, 0xb16db000, 4096)
,09-01 11:16:17.440   313  6972 V AudioCache: write(0xb16db000, 4096)
09-01 11:16:17.440   313  6972 V AudioCache: memcpy(0xac31a000, 0xb16db000, 4096)
09-01 11:16:17.441   313  6972 V AudioCache: write(0xb16db000, 4096)
09-01 11:16:17.441   313  6972 V AudioCache: memcpy(0xac31b000, 0xb16db000, 4096)
09-01 11:16:17.442   313  6972 V AudioCache: write(0xb16db000, 4096)
09-01 11:16:17.442   313  6972 V AudioCache: memcpy(0xac31c000, 0xb16db000, 4096)
09-01 11:16:17.442   313  6972 V AudioCache: write(0xb16db000, 4096)
09-01 11:16:17.442   313  6972 V AudioCache: memcpy(0xac31d000, 0xb16db000, 4096)
09-01 11:16:17.443   313  6972 V AudioCache: write(0xb16db000, 4096)
09-01 11:16:17.443   313  6972 V AudioCache: memcpy(0xac31e000, 0xb16db000, 4096)
09-01 11:16:17.444   313  6972 V AudioCache: write(0xb16db000, 4096)
09-01 11:16:17.444   313  6972 V AudioCache: memcpy(0xac31f000, 0xb16db000, 4096)
09-01 11:16:17.445   313  6972 V AudioCache: write(0xb16db000, 4096)
09-01 11:16:17.445   313  6972 V AudioCache: memcpy(0xac320000, 0xb16db000, 4096)
09-01 11:16:17.445   313  6972 V AudioCache: write(0xb16db000, 4096)
,09-01 11:16:17.445   313  6972 V AudioCache: memcpy(0xac321000, 0xb16db000, 4096)
09-01 11:16:17.446   313  6972 V AudioCache: write(0xb16db000, 4096)
09-01 11:16:17.446   313  6972 V AudioCache: memcpy(0xac322000, 0xb16db000, 4096)
09-01 11:16:17.447   313  6972 V AudioCache: write(0xb16db000, 4096)
09-01 11:16:17.447   313  6972 V AudioCache: memcpy(0xac323000, 0xb16db000, 4096)
09-01 11:16:17.448   313  6972 V AudioCache: write(0xb16db000, 4096)
09-01 11:16:17.448   313  6972 V AudioCache: memcpy(0xac324000, 0xb16db000, 4096)
09-01 11:16:17.449   313  6972 V AudioCache: write(0xb16db000, 4096)
09-01 11:16:17.449   313  6972 V AudioCache: memcpy(0xac325000, 0xb16db000, 4096)
09-01 11:16:17.449   313  6972 V AudioCache: write(0xb16db000, 4096)
09-01 11:16:17.449   313  6972 V AudioCache: memcpy(0xac326000, 0xb16db000, 4096)
09-01 11:16:17.450   313  6972 V AudioCache: write(0xb16db000, 4096)
09-01 11:16:17.450   313  6972 V AudioCache: memcpy(0xac327000, 0xb16db000, 4096)
09-01 11:16:17.451   313  6972 V AudioCache: write(0xb16db000, 4096)
09-01 11:16:17.451   313  6972 V AudioCache: memcpy(0xac328000, 0xb16db000, 4096)
09-01 11:16:17.451   313  6972 V AudioCache: write(0xb16db000, 4096)
09-01 11:16:17.451   313  6972 V AudioCache: memcpy(0xac329000, 0xb16db000, 4096)
09-01 11:16:17.452   313  6972 V AudioCache: write(0xb16db000, 4096)
09-01 11:16:17.452   313  6972 V AudioCache: memcpy(0xac32a000, 0xb16db000, 4096)
09-01 11:16:17.452   313  6972 V AudioCache: write(0xb16db000, 4096)
09-01 11:16:17.452   313  6972 V AudioCache: memcpy(0xac32b000, 0xb16db000, 4096)
09-01 11:16:17.453   313  6972 V AudioCache: write(0xb16db000, 4096)
09-01 11:16:17.453   313  6972 V AudioCache: memcpy(0xac32c000, 0xb16db000, 4096)
09-01 11:16:17.453   313  6972 V AudioCache: write(0xb16db000, 4096)
09-01 11:16:17.453   313  6972 V AudioCache: memcpy(0xac32d000, 0xb16db000, 4096)
09-01 11:16:17.453   313  6972 V AudioCache: write(0xb16db000, 4096)
09-01 11:16:17.454   313  6972 V AudioCache: memcpy(0xac32e000, 0xb16db000, 4096)
09-01 11:16:17.454   313  6972 V AudioCache: write(0xb16db000, 4096)
09-01 11:16:17.454   313  6972 V AudioCache: memcpy(0xac32f000, 0xb16db000, 4096)
09-01 11:16:17.454   313  6972 V AudioCache: write(0xb16db000, 4096)
09-01 11:16:17.454   313  6972 V AudioCache: memcpy(0xac330000, 0xb16db000, 4096)
09-01 11:16:17.455   313  6972 V AudioCache: write(0xb16db000, 4096)
09-01 11:16:17.455   313  6972 V AudioCache: memcpy(0xac331000, 0xb16db000, 4096)
09-01 11:16:17.455   313  6971 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
09-01 11:16:17.455   313  6972 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
09-01 11:16:17.455   313  6972 V AwesomePlayer: postAudioEOS() 
09-01 11:16:17.455   313  6972 V AudioCache: write(0xb16db000, 280)
09-01 11:16:17.455   313  6972 V AudioCache: memcpy(0xac332000, 0xb16db000, 280)
09-01 11:16:17.457   313  6969 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
09-01 11:16:17.457   313  6969 V AwesomePlayer: onStreamDone
09-01 11:16:17.457   313  6969 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
09-01 11:16:17.457   313  6969 V AudioCache: notify(0xb0409740, 2, 0, 0)
09-01 11:16:17.457   313  6969 V AudioCache: playback complete
09-01 11:16:17.457   313  6969 V AwesomePlayer: pause_l() 
09-01 11:16:17.457   313  6969 V AudioCache: notify(0xb0409740, 7, 0, 0)
09-01 11:16:17.457   313  6969 V AudioCache: ignored
09-01 11:16:17.457   313  6969 V AwesomePlayer: cancelPlayerEvents
09-01 11:16:17.457   313  2203 V AudioCache: wait - success
09-01 11:16:17.457   313  2203 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
09-01 11:16:17.457   313  6969 D AudioPlayer: Pause Playback at 1068125
09-01 11:16:17.458   313  2203 V AwesomePlayer: reset_l() 
09-01 11:16:17.458   313  2203 V AudioCache: notify(0xb0409740, 8, 0, 0)
09-01 11:16:17.458   313  2203 V AudioCache: ignored
09-01 11:16:17.458   313  2203 V AwesomePlayer: cancelPlayerEvents
09-01 11:16:17.458   313  2203 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
09-01 11:16:17.458   313  2203 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
09-01 11:16:17.458   313  2203 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
09-01 11:16:17.458   313  2203 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
09-01 11:16:17.458   313  2203 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-01 11:16:17.458   313  6971 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
,09-01 11:16:17.458   313  6971 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-01 11:16:17.458   313  6971 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
09-01 11:16:17.458   313  6971 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 0
09-01 11:16:17.458   313  6971 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
09-01 11:16:17.458   313  6971 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 0
09-01 11:16:17.458   313  6971 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
09-01 11:16:17.459   313  6971 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7970 on port 0
,09-01 11:16:17.459   313  6971 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
09-01 11:16:17.459   313  6971 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7650 on port 0
,09-01 11:16:17.459   313  6971 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
09-01 11:16:17.459   313  6971 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-01 11:16:17.459   313  6971 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57c01f0 on port 1
09-01 11:16:17.459   313  6971 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
09-01 11:16:17.459   313  6971 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 1
09-01 11:16:17.459   313  6971 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
,09-01 11:16:17.459   313  6971 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 1
09-01 11:16:17.459   313  6971 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
09-01 11:16:17.459   313  6971 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ba0 on port 1
09-01 11:16:17.459   313  6971 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-01 11:16:17.459   313  6971 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
09-01 11:16:17.459   313  2203 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-01 11:16:17.459   313  2203 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-01 11:16:17.459   313  6971 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
09-01 11:16:17.459   313  6971 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
09-01 11:16:17.459   313  6971 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
09-01 11:16:17.459   313  2203 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-01 11:16:17.459   313  2203 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
09-01 11:16:17.460   313  2203 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
09-01 11:16:17.461   313  2203 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
09-01 11:16:17.461   313  2203 D AudioPlayer: AudioPlayer releasing audio source
09-01 11:16:17.461   313  2203 D AudioPlayer: AudioPlayer done releasing audio source
09-01 11:16:17.461   313  2203 V AwesomePlayer: reset_l() 
09-01 11:16:17.461   313  2203 V AwesomePlayer: cancelPlayerEvents
09-01 11:16:17.461   313  2203 V AwesomePlayer: ~AwesomePlayer call
09-01 11:16:17.461   313  2203 V AwesomePlayer: reset_l() 
09-01 11:16:17.462   313  2203 V AwesomePlayer: cancelPlayerEvents
09-01 11:16:17.462  6868  6968 V SoundPool: close(31)
09-01 11:16:17.462  6868  6968 V SoundPool: pointer = 0xa0026000, size = 205080, sampleRate = 48000, numChannels = 2
09-01 11:16:17.505  6868  6868 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
09-01 11:16:17.506  6868  6868 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,09-01 11:16:17.509  6868  6868 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:2458,
,09-01 11:16:17.859  6559  6559 I UEI.SmartControl: Supports setup maps: true
,09-01 11:16:17.863  6559  6559 D UEI.SmartControl: QS start statue = true Error code = 0
09-01 11:16:17.863  6559  6559 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-01 11:16:17.863  6559  6559 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-01 11:16:17.864  6559  6559 I UEI.SmartControl: ### init IR Blaster...
09-01 11:16:17.867  6559  6559 D serial_port: Configuring serial port
09-01 11:16:17.867  6559  6559 E UEI.SmartControl: UEIBLaster setting for 616
09-01 11:16:17.867  6559  6559 I UEI.SmartControl: Setting serial record hearder size = 2
09-01 11:16:17.867  6559  6559 I UEI.SmartControl: configuring settings for MAXQ616
09-01 11:16:17.868  6559  6559 I UEI.SmartControl: Get version...
09-01 11:16:17.886  6559  6979 D UEI.SmartControl: serial port data available: 21
,09-01 11:16:17.912  6559  6559 D UEI.SmartControl: MAXQ616 A2-X4 software.
09-01 11:16:17.912  6559  6559 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-01 11:16:17.912  6559  6559 I UEI.SmartControl: QS saving settings...
09-01 11:16:17.913  6559  6559 D UEI.SmartControl: IR Blaster version: 25672567
,09-01 11:16:17.931  6559  6979 D UEI.SmartControl: serial port data available: 4
,09-01 11:16:17.964  6559  6982 I UEI.SmartControl: Device manager: loading config....
09-01 11:16:17.965  6559  6982 D UEI.SmartControl: ----------- loading internal config...
09-01 11:16:17.966  6559  6559 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,09-01 11:16:17.970  6559  6559 E UEI.SmartControl: Services init done
09-01 11:16:17.970  6559  6559 D UEI.SmartControl: QS Service init finished
09-01 11:16:17.979  6559  6559 D UEI.SmartControl: QS Service version name: 2.1.91
09-01 11:16:17.979  6559  6559 D UEI.SmartControl: QS Service version code: 201091
09-01 11:16:17.981  6559  6559 D UEI.SmartControl: Service requested: Control
,09-01 11:16:17.982  6559  6982 E UEI.SmartControl: Loading SETTINGS...
09-01 11:16:17.986  6559  6559 D UEI.SmartControl: Request IControl service: devices are loaded...
09-01 11:16:17.990  6559  6559 D UEI.SmartControl: Internal service binding...
09-01 11:16:17.991  6868  6868 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
09-01 11:16:17.993  6559  6621 I UEI.SmartControl: ------ IControl API: 11
09-01 11:16:17.993  6559  6621 D UEI.SmartControl: File observer start...
,09-01 11:16:17.994  6559  6621 E UEI.SmartControl: IR Port is disabled: false
09-01 11:16:17.994  6559  6621 D UEI.SmartControl: Starting file observer...
09-01 11:16:17.999  6559  6621 I UEI.SmartControl: Registering callback...
09-01 11:16:17.999  6559  6575 I UEI.SmartControl: ------ IControl API: 19
09-01 11:16:18.000  6559  6575 I UEI.SmartControl: Registering Services Ready callback...
09-01 11:16:18.000  6559  6982 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
09-01 11:16:18.023  6559  6981 I UEI.SmartControl: Notify AllClients services are ready: 0
09-01 11:16:18.023  6559  6981 D UEI.SmartControl: -----service ready thread exits
,09-01 11:16:18.024  6868  6884 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
09-01 11:16:18.025  6868  6966 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
09-01 11:16:18.025  6868  6966 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
09-01 11:16:18.026  6868  6868 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
09-01 11:16:18.026  6868  6868 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
09-01 11:16:18.027  6559  6574 I UEI.SmartControl: ------ IControl API: 8
09-01 11:16:18.029  6868  6868 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
09-01 11:16:18.030  6868  6868 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
09-01 11:16:18.030  6868  6868 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
09-01 11:16:18.031  6868  6868 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
09-01 11:16:18.032  6868  6868 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
09-01 11:16:18.032  6868  6868 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
09-01 11:16:18.034  6868  6868 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
09-01 11:16:18.037  6868  6868 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,09-01 11:16:18.039  6868  6868 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,09-01 11:16:18.040  6868  6868 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-01 11:16:18.040  6868  6868 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
09-01 11:16:18.041  6868  6868 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
09-01 11:16:18.043  6868  6868 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
09-01 11:16:18.043  6868  6868 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
09-01 11:16:18.044  6868  6868 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1472721378044]
09-01 11:16:18.048  6868  6868 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
09-01 11:16:18.051  1034  1917 I ActivityManager: Killing 6151:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,09-01 11:16:18.082  6868  6984 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,09-01 11:16:18.089  1034  1650 W libprocessgroup: failed to open /acct/uid_10080/pid_6151/cgroup.procs: No such file or directory
09-01 11:16:18.094  6868  6868 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,09-01 11:16:18.095  6868  6868 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,09-01 11:16:18.095  6868  6868 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
09-01 11:16:18.096  6868  6868 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
09-01 11:16:18.096  6868  6868 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
09-01 11:16:18.096  6868  6868 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
09-01 11:16:18.097  6868  6868 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
09-01 11:16:18.106  6868  6868 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,09-01 11:16:18.532  1034  1050 D WifiServiceImplEx: setWifiEnabled: true pid=6682, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-01 11:16:18.534  1034  1050 D WifiService: setWifiEnabled: true pid=6682, uid=10118
09-01 11:16:18.534  1034  1050 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-01 11:16:18.563  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-01 11:16:18.563  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-01 11:16:18.563  1034  1034 D Ulp_jni : JNI:system_update. Event-4
09-01 11:16:18.565  1034  1537 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
09-01 11:16:18.565  1034  1537 I LGFTMITEM: [GET_FTM][id=6], offset=12288
09-01 11:16:18.568  1034  1537 E WifiUtil: wfc_util_ffile_check_copy(): pid[1034] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
09-01 11:16:18.568  1034  1537 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-01 11:16:18.568  1034  1537 E WifiUtil: wfc_util_ffile_check_copy(): pid[1034] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
09-01 11:16:18.568  1034  1537 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-01 11:16:18.568  1034  1537 I WifiUtil: Intf0MacAddress=C49A027FFB5D
09-01 11:16:18.568  1034  1537 E WifiHW  : unknown target_country: EU , set to default
09-01 11:16:18.568  1034  1537 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
09-01 11:16:18.568  1034  1537 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
09-01 11:16:18.568  1034  1537 I WifiUtil: gEnableBmps=1
09-01 11:16:18.571  1034  1544 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-01 11:16:18.582  1034  1096 D Tethering: MasterInitialState.processMessage what=3
09-01 11:16:18.589  1034  1544 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-01 11:16:18.593  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:16:18.594  1034  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-01 11:16:18.595  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:16:18.600  1034  1096 D Tethering: MasterInitialState.processMessage what=3
09-01 11:16:18.608  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:16:18.612  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:16:18.613  6350  6350 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-01 11:16:18.616  6350  6833 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-01 11:16:18.626  5783  5783 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,09-01 11:16:18.634  5783  5783 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
09-01 11:16:18.653  2180  2180 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-01 11:16:18.685  1034  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-01 11:16:18.729  1034  1952 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7003 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
09-01 11:16:18.734  1034  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-01 11:16:18.734  1034  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-01 11:16:18.815  7003  7003 I AppUp4:AppBoxCP: onCreate
,09-01 11:16:18.816  7003  7003 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,09-01 11:16:18.827  7003  7003 I AppUp4:DB:  setFingerPrint start
,09-01 11:16:18.827  7003  7003 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
09-01 11:16:18.836  7003  7003 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
09-01 11:16:18.836  7003  7003 I AppUp4:DB:  SDK version = 21
09-01 11:16:18.836  7003  7003 I AppUp4:DB:  beforefinger == newfinger no write in DB
,09-01 11:16:18.838  7003  7003 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
09-01 11:16:18.840  7003  7003 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-01 11:16:18.840  7003  7003 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-01 11:16:18.843  7003  7003 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-01 11:16:18.843  7003  7003 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-01 11:16:18.852  7003  7003 I AppUp4:CustModeStarterReceiver: onReceive
,09-01 11:16:18.903  7003  7003 D LgDataFeature: LgDataFeature() Constructor: none
09-01 11:16:18.904  7003  7003 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-01 11:16:18.915  7003  7003 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1ac480b1
09-01 11:16:18.916  7003  7003 D AppUp4:CustFacade: isCustomizationCompleted : false
09-01 11:16:18.916  7003  7003 D AppUp4:CustFacade: isPhone : true
09-01 11:16:18.917  7003  7003 D AppUp4:CustModeStarterReceiver: begin check event
09-01 11:16:18.918  7003  7003 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
09-01 11:16:18.919  7003  7003 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
09-01 11:16:18.920  7003  7023 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
,09-01 11:16:18.920  7003  7023 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
09-01 11:16:18.921  7003  7023 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
09-01 11:16:18.928  1034  2022 I ActivityManager: Killing 6483:com.google.android.apps.docs/u0a61 (adj 15): empty #17
09-01 11:16:18.998  1034  1780 W libprocessgroup: failed to open /acct/uid_10061/pid_6483/cgroup.procs: No such file or directory
,09-01 11:16:19.003  4322  4322 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-01 11:16:19.003  4322  4322 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-01 11:16:19.005  4322  4322 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-01 11:16:19.009  4322  4322 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-01 11:16:19.015  4322  7031 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-01 11:16:19.024  4322  7032 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-01 11:16:19.024  4322  7032 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-01 11:16:19.063  1034  1917 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7033 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,09-01 11:16:19.151  7033  7033 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-01 11:16:19.151  7033  7033 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-01 11:16:19.153  7033  7033 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-01 11:16:19.153  7033  7033 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,09-01 11:16:19.243  7033  7033 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,09-01 11:16:19.258  7033  7033 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,09-01 11:16:19.313  1034  1096 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-01 11:16:19.313  1034  1096 D Tethering: InitialState.processMessage what=4
09-01 11:16:19.314  1034  1096 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-01 11:16:19.319   309   893 D SoftapController: Softap fwReload - Ok
09-01 11:16:19.321  1034  1537 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (744ms)
09-01 11:16:19.324   309   893 D CommandListener: Setting iface cfg
09-01 11:16:19.324   309   893 D CommandListener: Trying to bring down wlan0
09-01 11:16:19.325   309   893 D CommandListener: Clearing all IP addresses on wlan0
09-01 11:16:19.328  1034  1537 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
09-01 11:16:19.330  1034  1537 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-01 11:16:19.330  1034  1537 E WifiStateMachine: useWiFiOffloading() : false
09-01 11:16:19.330  1034  1537 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-01 11:16:19.333  1939  1939 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
09-01 11:16:19.334  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:16:19.334  7033  7033 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-01 11:16:19.318  7064  7064 W wpa_supplicant: type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-01 11:16:19.318  7064  7064 W wpa_supplicant: type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-01 11:16:19.341  1034  1537 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-01 11:16:19.341  1034  1537 D WifiMonitor: connecting to supplicant
09-01 11:16:19.344  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:16:19.345  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:16:19.345  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
,09-01 11:16:19.361  7064  7064 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-01 11:16:19.384  7033  7033 D LgDataFeature: LgDataFeature() Constructor: none
09-01 11:16:19.385  7033  7033 D LgDataFeature: LgDataFeature() Constructor Done, null
09-01 11:16:19.394  7064  7064 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-01 11:16:19.394  7064  7064 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,09-01 11:16:19.515  7064  7064 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-01 11:16:19.530  7033  7033 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,09-01 11:16:19.580  3463  3463 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-01 11:16:19.580  3463  3463 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-01 11:16:19.581  3463  3463 I LgeMiscReceiver: networkInfo.isConnected() = false
09-01 11:16:19.582  7064  7064 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,09-01 11:16:19.588  7064  7064 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
09-01 11:16:19.588  7064  7064 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
09-01 11:16:19.590  1034  1537 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
09-01 11:16:19.591  1034  1537 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
09-01 11:16:19.591  1034  1537 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
09-01 11:16:19.592  1034  1537 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
09-01 11:16:19.592  1034  7077 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
09-01 11:16:19.593  1034  7077 D WifiMonitor: Dropping event because (p2p0) is stopped
09-01 11:16:19.593  1034  7077 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
09-01 11:16:19.593  1034  7077 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
09-01 11:16:19.593  1034  7077 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
09-01 11:16:19.593  1034  1537 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-01 11:16:19.593  1034  7077 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
09-01 11:16:19.594  1034  1537 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-01 11:16:19.594  1034  1537 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
09-01 11:16:19.594  1034  1537 D WifiNative-wlan0: doString: [DRIVER MACADDR]
09-01 11:16:19.595  1034  1537 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
09-01 11:16:19.595  1034  1537 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
09-01 11:16:19.595  7033  7033 I HubEmail: JNI_OnLoad()
09-01 11:16:19.595  7033  7033 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-01 11:16:19.595  7033  7033 I HubEmail: registerNatives()
09-01 11:16:19.595  1034  1537 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
09-01 11:16:19.595  7033  7033 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-01 11:16:19.595  7033  7033 I HubEmail: registerNativeMethods()
09-01 11:16:19.595  7033  7033 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-01 11:16:19.596  7033  7033 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,09-01 11:16:19.643  1034  1923 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7079 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,09-01 11:16:19.648  1034  1537 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-01 11:16:19.648  1034  1537 E WifiStateMachine: useWiFiOffloading() : false
09-01 11:16:19.648  1034  1537 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-01 11:16:19.649  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:16:19.649  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:16:19.649  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:16:19.649  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:16:19.649  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-01 11:16:19.651  1034  1537 D WifiNative-wlan0: doBoolean: SET update_config 1
09-01 11:16:19.652  1034  1537 D WifiNative-wlan0: SET update_config 1: returned true
09-01 11:16:19.652  1034  1537 D WifiConfigStore: Loading config and enabling all networks 
09-01 11:16:19.652  1034  1537 D WifiNative-wlan0: doString: [LIST_NETWORKS]
09-01 11:16:19.653  1034  1537 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
09-01 11:16:19.654  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:16:19.654  6937  7075 W FormManager: Network not available. Please check & try again.
09-01 11:16:19.655  1939  1939 D WfdService: Waiting for WifiP2p enabling
,09-01 11:16:19.656  6682  6682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:16:19.656  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:16:19.656  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:16:19.656  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-01 11:16:19.656  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:16:19.656  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 11:16:19.656  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:16:19.656  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:16:19.656  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 11:16:19.656  6682  6682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:16:19.656  6682  6682 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-01 11:16:19.657  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
09-01 11:16:19.658  1034  1541 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
09-01 11:16:19.659  6682  6682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:16:19.659  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:16:19.659  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:16:19.659  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-01 11:16:19.659  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:16:19.659  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 11:16:19.659  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:16:19.659  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:16:19.659  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 11:16:19.659  6682  6682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:16:19.659  6682  6682 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-01 11:16:19.660  6937  7076 V FormManager: Network unavailable.
09-01 11:16:19.662  6937  7076 V FormManager: Network unavailable.
09-01 11:16:19.664  1034  1537 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
09-01 11:16:19.669  7033  7078 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-01 11:16:19.673  1034  1537 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
09-01 11:16:19.673  1034  1537 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-01 11:16:19.675  1034  1650 I ActivityManager: Killing 6174:com.google.android.apps.plus/u0a97 (adj 15): empty #17
09-01 11:16:19.721  1034  1537 D WifiStateMachine: enableVerboseLogging : level 2
,09-01 11:16:19.721  1034  1537 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
09-01 11:16:19.723  1034  1537 D WifiNative-wlan0: SET device_name g3_global_com: returned true
09-01 11:16:19.723  1034  1537 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
09-01 11:16:19.724  1034  1537 D WifiNative-wlan0: SET manufacturer LGE: returned true
09-01 11:16:19.724  1034  1537 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
09-01 11:16:19.725  1034  1537 D WifiNative-wlan0: SET model_name LG-D855: returned true
09-01 11:16:19.725  1034  1537 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
09-01 11:16:19.726  1034  1537 D WifiNative-wlan0: SET model_number LG-D855: returned true
09-01 11:16:19.726  1034  1537 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
09-01 11:16:19.727  1034  1893 W libprocessgroup: failed to open /acct/uid_10097/pid_6174/cgroup.procs: No such file or directory
09-01 11:16:19.728  1034  1537 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
09-01 11:16:19.728  1034  1537 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
09-01 11:16:19.729  1034  1537 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
09-01 11:16:19.729  1034  1537 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
09-01 11:16:19.730  1034  1537 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
09-01 11:16:19.733  1034  1537 D WifiStateMachine: Setting OUI to DA-A1-19
09-01 11:16:19.733  1034  1537 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
09-01 11:16:19.734  1939  1939 D WfdsService: Supplicant Connection state is changed : true
09-01 11:16:19.734  1034  1537 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
,09-01 11:16:19.734  1034  1537 D WifiNative-HAL: Setting external_sim to 1
09-01 11:16:19.734  1034  1537 D WifiNative-wlan0: doBoolean: SET external_sim 1
09-01 11:16:19.734  1939  2284 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
09-01 11:16:19.734  1939  2284 D WfdsService: Set the WFDS Monitor: true
09-01 11:16:19.734  1939  2284 D WfdsMonitor: WfdsMonitorThread create
09-01 11:16:19.735  1939  2284 D WfdsMonitor: WFDS Monitor is created and started
09-01 11:16:19.735  1939  2284 D WfdsService: WiFi: Supplicant connection re-established
09-01 11:16:19.736  1034  1537 D WifiNative-wlan0: SET external_sim 1: returned true
09-01 11:16:19.736  1034  1537 I WifiNative-HAL: startHal
09-01 11:16:19.736  1034  1537 D wifi    : setting scan oui 0x956cb220
09-01 11:16:19.737  1034  1537 D WifiStateMachine: Setting OUI to DA-A1-19
09-01 11:16:19.737  1034  1537 I WifiNative-HAL: startHal
09-01 11:16:19.737  1034  1537 D wifi    : setting scan oui 0x956cb220
09-01 11:16:19.737  1034  1537 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
09-01 11:16:19.738  1939  7096 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
09-01 11:16:19.738  1034  1537 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
09-01 11:16:19.739  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
09-01 11:16:19.739  7064  7064 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
09-01 11:16:19.739  1034  1537 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
09-01 11:16:19.739  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-01 11:16:19.739  1939  7096 E CtrlSupplicant: Succeed to open control connection
09-01 11:16:19.740  7064  7064 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-01 11:16:19.740  1939  7096 E CtrlSupplicant: Succeed to open monitor connection
09-01 11:16:19.741  1939  7096 D WfdsMonitor: Supplicant connection established
09-01 11:16:19.741  1034  1537 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-01 11:16:19.741  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
09-01 11:16:19.741  1939  2284 D WfdsService: Connected to the supplicant for wfds
09-01 11:16:19.741  7064  7064 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
09-01 11:16:19.742  1034  1537 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
09-01 11:16:19.742  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-01 11:16:19.743  7064  7064 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-01 11:16:19.743  1034  1537 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-01 11:16:19.743  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-01 11:16:19.744  7064  7064 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-01 11:16:19.744  1034  1537 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-01 11:16:19.745  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
09-01 11:16:19.745  7064  7064 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
09-01 11:16:19.746  1034  1537 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
09-01 11:16:19.746  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-01 11:16:19.747  7064  7064 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-01 11:16:19.748  1034  1537 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
,09-01 11:16:19.752  1034  1537 E WifiNative: : [183,309,468 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
09-01 11:16:19.752  1034  1537 D WifiNative-wlan0: doBoolean: RECONNECT
09-01 11:16:19.753  1034  1537 D WifiNative-wlan0: RECONNECT: returned true
09-01 11:16:19.753  1034  1537 D WifiNative-wlan0: doString: [STATUS]
09-01 11:16:19.755  1034  7077 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
,09-01 11:16:19.755  1034  7077 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-01 11:16:19.755  1034  1537 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-01 11:16:19.755  1034  1537 D WifiNative-wlan0: doBoolean: SET ps 1
09-01 11:16:19.756  1034  1537 D WifiNative-wlan0: SET ps 1: returned true
09-01 11:16:19.757  1034  1536 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:16:19.759  1034  1034 D WifiScanningService: SCAN_AVAILABLE : 3
09-01 11:16:19.759  1034  1034 D RttService: SCAN_AVAILABLE : 3
09-01 11:16:19.759  1034  1555 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:16:19.759  1034  1555 I WifiNative-HAL: startHal
09-01 11:16:19.759  1034  1555 D wifi    : getting scan capabilities on interface[1] = 0x956cb220
09-01 11:16:19.759  1034  1555 D wifi    : failed to get capabilities : -3
,09-01 11:16:19.759  1034  1555 E WifiScanningService: could not get scan capabilities
09-01 11:16:19.760  1034  1556 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:16:19.760   309   893 D CommandListener: Setting iface cfg
09-01 11:16:19.760  1034  1537 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
09-01 11:16:19.760   309   893 D CommandListener: Trying to bring up p2p0
09-01 11:16:19.760  1034  1536 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-01 11:16:19.760  1034  1536 D LGWifiP2pService: P2pEnablingState
09-01 11:16:19.760  1034  1537 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
09-01 11:16:19.760  1034  1536 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:16:19.760  1034  1536 D LGWifiP2pService: P2p socket connection successful
09-01 11:16:19.760  1034  1536 D LGWifiP2pService: P2pEnabledState
,09-01 11:16:19.761  1034  1536 D LGWifiP2pService: sending p2p connection changed broadcast
,09-01 11:16:19.763  1034  1536 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
09-01 11:16:19.763  1939  1939 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
09-01 11:16:19.763  1939  1939 D WfdsService: WifiP2pState is changed : true
09-01 11:16:19.764  1939  2284 D WfdsService: Receive the WFDS_ENABLE Method
09-01 11:16:19.764  1939  2284 D WfdsService: Set the WFDS Monitor: true
09-01 11:16:19.764  1939  2284 D WfdsService: Connected to the supplicant for wfds
09-01 11:16:19.764  1939  2284 D WfdsJNI : doCommand: WFDS_SET TRUE
09-01 11:16:19.764  7064  7064 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
09-01 11:16:19.764  1939  2284 D WfdsService: selectPreferredScanChannel [36]
09-01 11:16:19.764  1939  2284 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
09-01 11:16:19.764  1034  1536 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
09-01 11:16:19.764  1034  1536 D WifiNative-p2p0: doBoolean: SET device_name G3
09-01 11:16:19.765  1034  1536 D WifiNative-p2p0: SET device_name G3: returned true
09-01 11:16:19.765  1939  1939 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
09-01 11:16:19.765  1034  1536 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
09-01 11:16:19.765  1034  1536 D LGWifiP2pService: before postfix = G3
09-01 11:16:19.765  1034  1536 D WifiServerServiceExt: postfix byte check : 2
09-01 11:16:19.765  1034  1536 D LGWifiP2pService: after postfix = G3
09-01 11:16:19.765  1034  1536 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
09-01 11:16:19.765  1939  1939 D WfdsService: isConnected: false
09-01 11:16:19.766  1034  1537 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
09-01 11:16:19.766  1034  1536 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
09-01 11:16:19.766  1034  1536 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
09-01 11:16:19.767  1034  1536 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
09-01 11:16:19.767  1034  1536 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
09-01 11:16:19.767  1034  1536 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
09-01 11:16:19.767  1034  1536 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
09-01 11:16:19.768  1034  1536 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
09-01 11:16:19.768  1034  1536 D WifiNative-HAL: p2pGetDeviceAddress
09-01 11:16:19.768  1034  1537 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
09-01 11:16:19.768  1034  1536 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
09-01 11:16:19.768  1034  1537 E WifiStateMachine:  DisconnectedState what:132106 1 0
09-01 11:16:19.768  1034  1536 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
09-01 11:16:19.768  1034  1536 D WifiNative-p2p0: doBoolean: P2P_FLUSH
09-01 11:16:19.769  1034  1537 E WifiStateMachine:  ConnectModeState what:132106 1 0
09-01 11:16:19.769  1034  1537 E WifiStateMachine:  DriverStartedState what:132106 1 0
09-01 11:16:19.769  1034  1537 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
09-01 11:16:19.769  7064  7064 E wpa_supplicant: nWIFIDualbandAPConnection: 1
09-01 11:16:19.770  1034  1536 D WifiNative-p2p0: P2P_FLUSH: returned true
09-01 11:16:19.770  1034  1536 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
09-01 11:16:19.770  1939  1939 I WfdStateTracker: handleP2pThisDeviceChanged
09-01 11:16:19.770  1939  1939 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
09-01 11:16:19.770  1939  1939 D WfdsService: Update P2p Interface State: 3
09-01 11:16:19.770  1034  1536 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
09-01 11:16:19.770  1034  1536 D WifiNative-p2p0: doString: [LIST_NETWORKS]
09-01 11:16:19.771  1034  1536 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
09-01 11:16:19.771  1034  1536 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
09-01 11:16:19.771  1034  1537 E WifiStateMa,chine:  DisconnectedState what:132096 -100 0
09-01 11:16:19.771  1034  1537 E WifiStateMachine:  ConnectModeState what:132096 -100 0
09-01 11:16:19.772  1034  1537 E WifiStateMachine:  DriverStartedState what:132096 -100 0
09-01 11:16:19.772  1034  1537 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
09-01 11:16:19.781  7064  7064 E wpa_supplicant: disconnect_rssi_lvl: -100
09-01 11:16:19.782  1034  1536 D WifiNative-p2p0: SAVE_CONFIG: returned true
09-01 11:16:19.782  1034  1536 D LGWifiP2pService: sending p2p persistent groups changed broadcast
09-01 11:16:19.782  1034  1536 D LGWifiP2pService: InactiveState
09-01 11:16:19.782  1034  1537 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
09-01 11:16:19.782  1034  1536 D LGWifiP2pService: InactiveState{ when=-12ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:16:19.782  1034  1536 D LGWifiP2pService: P2pEnabledState{ when=-12ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:16:19.782  1034  1536 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
09-01 11:16:19.782  1034  1537 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
09-01 11:16:19.783  1034  1537 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
09-01 11:16:19.783  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
09-01 11:16:19.783  7064  7064 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
,09-01 11:16:19.783  7064  7064 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-01 11:16:19.784  1939  7096 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-01 11:16:19.784  1034  7077 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-01 11:16:19.784  1034  7077 E WifiMonitor: WifiMonitor:p2p0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-01 11:16:19.784  1034  7077 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-01 11:16:19.784  1034  7077 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-01 11:16:19.784  7064  7064 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-01 11:16:19.784  7064  7064 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:16:19.785  1939  7096 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-01 11:16:19.785  1034  7077 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-01 11:16:19.785  1034  7077 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:16:19.785  1034  7077 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:16:19.785  1034  7077 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:16:19.785  7064  7064 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:16:19.786  1939  7096 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-01 11:16:19.786  1034  7077 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-01 11:16:19.786  1034  7077 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:16:19.786  1034  7077 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:16:19.786  1034  7077 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:16:19.787  1034  1536 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
09-01 11:16:19.787  1034  1536 D LGWifiP2pService: InactiveState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:16:19.787  1034  1536 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:16:19.787  1034  1536 D LGWifiP2pService: DefaultState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:16:19.787  1034  1536 D LGWifiP2pService: InactiveState{ when=-5ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:16:19.787  1034  1536 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:16:19.787  1034  1536 D LGWifiP2pService: DefaultState{ when=-5ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:16:19.787  1034  1536 D LGWifiP2pService: InactiveState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:16:19.788  1034  1536 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:16:19.788  1034  1536 D LGWifiP2pService: DefaultState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:16:19.788  1939  2284 W WfdsService: DefaultState - msg [9441285] is not handled
09-01 11:16:19.788  1034  1536 D LGWifiP2pService: InactiveState{ when=-5ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:16:19.788  1034  1536 D LGWifiP2pService: P2pEnabledState{ when=-6ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:16:19.,789  1034  1536 D LGWifiP2pService: DefaultState{ when=-6ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:16:19.789  1034  1034 E WifiServerServiceExt: No p2p device connected
09-01 11:16:19.789  7064  7064 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-01 11:16:19.790  7064  7064 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-01 11:16:19.790  7064  7064 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-01 11:16:19.791  7064  7064 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:16:19.791  1034  1537 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
09-01 11:16:19.791  7064  7064 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:16:19.791  1034  7077 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-01 11:16:19.791  1034  7077 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-01 11:16:19.792  1034  7077 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-01 11:16:19.792  1034  1536 D LGWifiP2pService: InactiveState{ when=0 what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:16:19.792  1034  7077 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-01 11:16:19.792  1034  7077 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-01 11:16:19.792  1034  1536 D LGWifiP2pService: P2pEnabledState{ when=0 what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:16:19.792  1034  7077 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:16:19.792  1034  7077 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:16:19.792  1034  7077 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:16:19.792  1034  7077 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-01 11:16:19.792  1034  7077 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:16:19.792  1034  7077 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:16:19.792  1034  7077 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:16:19.792  1939  7096 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-01 11:16:19.792  1939  7096 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-01 11:16:19.792  1034  1537 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
09-01 11:16:19.793  1034  1537 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
,09-01 11:16:19.793  1034  1537 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
09-01 11:16:19.793  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
,09-01 11:16:19.794  7064  7064 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
09-01 11:16:19.794  7064  7064 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-01 11:16:19.794  1034  7077 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
,09-01 11:16:19.794  1034  7077 E WifiMonitor: WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-01 11:16:19.794  1034  7077 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-01 11:16:19.794  1034  7077 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-01 11:16:19.795  1034  1537 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
09-01 11:16:19.795  1034  1537 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
09-01 11:16:19.796  1034  1537 D WifiNative-wlan0: BSS_FLUSH 0: returned true
09-01 11:16:19.796  1034  1537 D WifiNative-wlan0: doBoolean: SCAN
09-01 11:16:19.796  1034  1537 D WifiNative-wlan0: SCAN: returned false
09-01 11:16:19.797  1034  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=183357  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-01 11:16:19.800  1034  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=183360  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-01 11:16:19.800  1034  1537 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-01 11:16:19.801  1034  1537 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-01 11:16:19.801  1034  1537 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-01 11:16:19.801  1034  1537 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-01 11:16:19.801  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-01 11:16:19.802  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-01 11:16:19.802  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:16:19.802  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:16:19.802  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-01 11:16:19.803  1034  1537 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-01 11:16:19.803  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:16:19.803  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-01 11:16:19.803  1034  1034 D WifiServerServiceExt: setSupplicantStateSCANNING
09-01 11:16:19.823  7079  7079 D LgDataFeature: LgDataFeature() Constructor: none
09-01 11:16:19.823  7079  7079 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-01 11:16:19.826  7079  7079 D PhoneMonitor: Register our PhoneStateListener
,09-01 11:16:19.838  7079  7079 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-01 11:16:19.841  7079  7079 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,09-01 11:16:19.854  7079  7079 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,09-01 11:16:19.856  7079  7079 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
09-01 11:16:19.857  7079  7079 D TelephonyAutoProfiling: [parse] Load xml
09-01 11:16:19.860  7079  7079 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
09-01 11:16:19.860  7079  7079 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
09-01 11:16:19.860  7079  7079 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
09-01 11:16:19.860  7079  7079 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
09-01 11:16:19.860  7079  7079 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
09-01 11:16:19.860  7079  7079 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
09-01 11:16:19.860  7079  7079 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
09-01 11:16:19.860  7079  7079 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
09-01 11:16:19.860  7079  7079 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
09-01 11:16:19.860  7079  7079 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
09-01 11:16:19.860  7079  7079 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
09-01 11:16:19.860  7079  7079 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
09-01 11:16:19.860  7079  7079 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
09-01 11:16:19.860  7079  7079 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
09-01 11:16:19.860  7079  7079 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
09-01 11:16:19.861  7079  7079 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
09-01 11:16:19.861  7079  7079 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,09-01 11:16:19.868  7079  7079 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
09-01 11:16:19.911  1034  1952 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7100 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-01 11:16:19.912  1034  1952 I ActivityManager: Killing 6524:com.lge.eula/1000 (adj 15): empty #17
09-01 11:16:19.969  1034  1959 W libprocessgroup: failed to open /acct/uid_1000/pid_6524/cgroup.procs: No such file or directory
,09-01 11:16:20.154  7064  7064 E wpa_supplicant: USIM:  scard_init function
09-01 11:16:20.155  1034  7077 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
09-01 11:16:20.155  7064  7064 I wpa_supplicant: Trying to associate with SSID 'NG700'
09-01 11:16:20.155  1034  7077 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
09-01 11:16:20.156  1034  7077 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
09-01 11:16:20.156  1034  7077 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: WPS-AP-AVAILABLE 
09-01 11:16:20.156  1034  7077 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
,09-01 11:16:20.158  1034  1537 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
09-01 11:16:20.159  1034  1537 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
09-01 11:16:20.161  1034  1537 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
09-01 11:16:20.164  1034  7077 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
09-01 11:16:20.164  1034  7077 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
09-01 11:16:20.165  1034  1537 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
09-01 11:16:20.165  1034  1537 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
09-01 11:16:20.182  1034  2048 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7121 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,09-01 11:16:20.183  1034  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=183744  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,09-01 11:16:20.184  1034  2048 I ActivityManager: Killing 6541:com.lge.bnr/1000 (adj 15): empty #17
09-01 11:16:20.241  1034  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=183802  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-01 11:16:20.243  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-01 11:16:20.243  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-01 11:16:20.247  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:16:20.249  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:16:20.249  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:16:20.249  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-01 11:16:20.253  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:16:20.253  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:16:20.253  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-01 11:16:20.253  1034  1574 W libprocessgroup: failed to open /acct/uid_1000/pid_6541/cgroup.procs: No such file or directory
,09-01 11:16:20.262  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-01 11:16:20.262  1034  1034 D WifiServerServiceExt: setSupplicantStateASSOCIATING
09-01 11:16:20.272  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-01 11:16:20.272  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-01 11:16:20.273  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:16:20.291  7064  7064 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
09-01 11:16:20.293  1034  7077 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
09-01 11:16:20.293  1034  7077 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
09-01 11:16:20.293  1034  7077 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
09-01 11:16:20.293  1034  7077 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: Associated with f4:f2:6d:22:99:3e
09-01 11:16:20.293  1034  7077 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-01 11:16:20.293  1034  7077 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,09-01 11:16:20.294  1034  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=183855  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-01 11:16:20.295  1034  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=183855  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-01 11:16:20.295  1034  1537 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=183856
09-01 11:16:20.296  1034  1096 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-01 11:16:20.296  1034  1537 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=183856
09-01 11:16:20.296  1034  1537 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=183857
09-01 11:16:20.297  1034  1537 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=183857
09-01 11:16:20.297  1034  1537 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=183858
09-01 11:16:20.298  1034  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=183858  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-01 11:16:20.300  7064  7064 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-01 11:16:20.300  7064  7064 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-01 11:16:20.301  1034  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=183861  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-01 11:16:20.301  1034  7077 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-01 11:16:20.301  1034  7077 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-01 11:16:20.302  1034  7077 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
09-01 11:16:20.302  1034  7077 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-01 11:16:20.302  1034  7077 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-01 11:16:20.302  1034  7077 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
,09-01 11:16:20.302  1034  7077 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-01 11:16:20.302  1034  7077 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-01 11:16:20.302  1034  7077 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-01 11:16:20.302  1034  7077 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-01 11:16:20.304  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:16:20.304  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:16:20.304  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,09-01 11:16:20.306  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-01 11:16:20.306  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-01 11:16:20.308  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:16:20.309  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:16:20.309  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:16:20.309  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
09-01 11:16:20.309  1034  1537 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
09-01 11:16:20.310  1034  1537 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
09-01 11:16:20.311  1034  1537 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
09-01 11:16:20.311  1034  1537 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
09-01 11:16:20.312  1034  1537 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-01 11:16:20.312  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-01 11:16:20.312  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-01 11:16:20.312  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-01 11:16:20.313  1034  1034 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
09-01 11:16:20.313  1034  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=183873  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-01 11:16:20.314  1034  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=183874  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-01 11:16:20.314  1034  1537 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=183875
09-01 11:16:20.314  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:16:20.315  1034  1537 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=183875
09-01 11:16:20.316  1034  1537 D WifiNative-wlan0: doString: [STATUS]
09-01 11:16:20.316  1034  7077 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-01 11:16:20.316  1034  7077 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,09-01 11:16:20.319  1034  1537 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-01 11:16:20.321  1034  1537 I WifiServiceExtension: setVHTCapabilityType  : false
09-01 11:16:20.377  1034  2022 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7138 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-01 11:16:20.379  1034  2022 I ActivityManager: Killing 6576:com.lge.clock/u0a10 (adj 15): empty #17
,09-01 11:16:20.429  1034  1537 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
,09-01 11:16:20.429  1034  1537 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
09-01 11:16:20.430  1034  1987 W libprocessgroup: failed to open /acct/uid_10010/pid_6576/cgroup.procs: No such file or directory
09-01 11:16:20.435  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-01 11:16:20.435  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-01 11:16:20.437  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:16:20.437  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:16:20.437  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:16:20.437  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,09-01 11:16:20.441  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:16:20.441  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:16:20.441  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-01 11:16:20.451  1034  1537 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
09-01 11:16:20.451  1034  1544 D ConnectivityService: Got NetworkAgent Messenger
09-01 11:16:20.451  1034  1537 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-01 11:16:20.451  1034  1537 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-01 11:16:20.451  1034  1544 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-01 11:16:20.452  1034  1537 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-01 11:16:20.452  1034  1544 D ConnectivityService: NetworkAgent connected
09-01 11:16:20.452  1034  1537 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-01 11:16:20.459  1034  1537 D WifiNative-wlan0: SAVE_CONFIG: returned true
,09-01 11:16:20.459  1034  1537 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-01 11:16:20.459  1034  1537 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-01 11:16:20.460  1034  1537 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-01 11:16:20.460  1034  1537 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-01 11:16:20.460  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-01 11:16:20.460  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-01 11:16:20.463  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:16:20.464  1034  1537 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-01 11:16:20.465   309   893 D CommandListener: Setting iface cfg
09-01 11:16:20.469  1034  1537 E WifiStateMachine: Start Dhcp Watchdog 2
09-01 11:16:20.469  1034  7156 D DhcpStateMachine: StoppedState
09-01 11:16:20.469  1034  7156 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:16:20.469  1034  7156 D DhcpStateMachine: WaitBeforeStartState
09-01 11:16:20.469  1034  1537 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=184030  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-01 11:16:20.470  1034  1537 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=184030  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-01 11:16:20.470  1034  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=184031  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-01 11:16:20.471  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-01 11:16:20.471  1034  1034 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
09-01 11:16:20.472  1034  1537 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=184032  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-01 11:16:20.472  1034  1537 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=184033  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-01 11:16:20.473  1034  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=184033  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-01 11:16:20.474  1034  1537 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:138198] from screen [on:0 period:-452402054] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
09-01 11:16:20.475  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-452402053] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
09-01 11:16:20.475  1034  1537 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,09-01 11:16:20.479  1034  1544 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
09-01 11:16:20.480  1034  1537 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:16:20.480  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:16:20.481  1034  1537 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:16:20.481  1034  1537 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:16:20.482  1034  1537 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:16:20.482  1034  1537 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:16:20.482  1034  1544 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-01 11:16:20.483  1034  1537 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=115,0,0
09-01 11:16:20.483  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=115,0,0
09-01 11:16:20.483  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
09-01 11:16:20.484  7064  7064 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
09-01 11:16:20.484  1034  1537 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
09-01 11:16:20.484  1034  1537 D WifiNative-wlan0: doBoolean: SET ps 0
09-01 11:16:20.484  1034  1537 D WifiNative-wlan0: SET ps 0: returned true
09-01 11:16:20.485  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
09-01 11:16:20.485  7064  7064 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
09-01 11:16:20.485  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:16:20.485  1034  1537 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
09-01 11:16:20.485  1034  1536 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@208445ce target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:16:20.485  1034  1536 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@208445ce target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:16:20.486  1034  7156 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:16:20.486  1034  7156 D DhcpStateMachine: DHCP Start wake lock is acquired.
09-01 11:16:20.486  1034  1537 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
09-01 11:16:20.486  1034  1537 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-01 11:16:20.486  1034  1537 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-01 11:16:20.487   309   893 D CommandListener: Setting iface cfg
09-01 11:16:20.488   309   893 D CommandListener: Trying to bring up wlan0
,09-01 11:16:20.489  1034  1537 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
09-01 11:16:20.490  1034  1537 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:16:20.490  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:16:20.491  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-01 11:16:20.491  1034  1537 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:16:20.491  1034  1034 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-01 11:16:20.492  1034  1537 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:16:20.492  7138  7138 I art     : Almond Protected OAT
09-01 11:16:20.492  1034  1537 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:16:20.493  1034  1537 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:16:20.494  1034  1537 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-01 11:16:20.495  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-01 11:16:20.495  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-01 11:16:20.495  1034  1544 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-01 11:16:20.495  7064  7064 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-01 11:16:20.495  1034  1536 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:16:20.495  1034  1536 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:16:20.495  1034  1537 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-01 11:16:20.495  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
09-01 11:16:20.496  7064  7064 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
09-01 11:16:20.496  1034  1537 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
09-01 11:16:20.496  1034  1537 D WifiNative-wlan0: doBoolean: SET ps 1
09-01 11:16:20.513  1034  1537 D WifiNative-wlan0: SET ps 1: returned true
,09-01 11:16:20.516  1034  1537 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-01 11:16:20.517  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-01 11:16:20.517  1034  1537 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-01 11:16:20.518  1034  1544 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-01 11:16:20.519  1034  1544 D ConnectivityService: ignoring duplicate network state non-change
09-01 11:16:20.524  1034  1544 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-01 11:16:20.525  1034  1544 D ConnectivityService: Adding iface wlan0 to network 101
09-01 11:16:20.529  1034  1537 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-01 11:16:20.550  1034  1544 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-01 11:16:20.550  1034  1544 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-01 11:16:20.551  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-01 11:16:20.551  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-01 11:16:20.552  1034  1544 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
09-01 11:16:20.553   309   893 E Netd    : netlink response contains error (File exists)
09-01 11:16:20.553  1034  1544 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
09-01 11:16:20.554  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:16:20.555  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:16:20.555  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:16:20.555  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-01 11:16:20.556  1034  1544 D ConnectivityService: addLocalRoutetoDefaultNetwork
09-01 11:16:20.556  1034  1544 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
09-01 11:16:20.556  1034  1544 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
09-01 11:16:20.559  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:16:20.560  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:16:20.560  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-01 11:16:20.560  1034  1034 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-01 11:16:20.562  1939  1939 V WfdStateTracker: handleWifiStateChangedEvent: 1
09-01 11:16:20.563  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:16:20.563  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:16:20.564  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-01 11:16:20.564  1034  1034 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,09-01 11:16:20.567  1034  1536 D LGWifiP2pService: InactiveState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:16:20.568  1034  1536 D LGWifiP2pService: P2pEnabledState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:16:20.568  1034  1536 D LGWifiP2pService: DefaultState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:16:20.569  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:16:20.569  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:16:20.569  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-01 11:16:20.569  1034  1544 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-01 11:16:20.569  1034  1544 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-01 11:16:20.569  1034  1544 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-01 11:16:20.569  1034  1544 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
09-01 11:16:20.569  1034  1544 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-01 11:16:20.569  1034  7155 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:16:20.569  1034  7155 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
09-01 11:16:20.569  1034  1544 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-01 11:16:20.569  7138  7138 D WeatherApplication: removeAccount
09-01 11:16:20.569  1034  1544 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-01 11:16:20.570  1034  7155 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:16:20.570  1034  1544 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-01 11:16:20.570  1034  7155 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-01 11:16:20.570  1034  1544 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
09-01 11:16:20.570  1034  1544 D ConnectivityService: currentScore = 0, newScore = 20
09-01 11:16:20.570  1034  1544 D ConnectivityService:    accepting network in place of null
09-01 11:16:20.570  1034  1544 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-01 11:16:20.570  1034  1537 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-01 11:16:20.570  1034  1537 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-01 11:16:20.571  7138  7138 D WeatherApplication: Account.length = 0
09-01 11:16:20.571  7138  7138 E WeatherApplication: OPERATOR:OPEN
09-01 11:16:20.572  1850  1850 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-01 11:16:20.572  1850  1850 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DU,N&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-01 11:16:20.577  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-01 11:16:20.577  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-01 11:16:20.578   309  7165 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
,09-01 11:16:20.579  1034  1544 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-01 11:16:20.579  1034  1544 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-01 11:16:20.579  1034  1544 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-01 11:16:20.580  1034  1544 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-01 11:16:20.580  1034  1544 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
09-01 11:16:20.580  7138  7138 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:16:20
09-01 11:16:20.580  1034  1544 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
09-01 11:16:20.582  1034  1544 D ConnectivityService: validation of new default Network = false
09-01 11:16:20.582  1034  1544 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
09-01 11:16:20.582  1034  1544 D DSQN    : enableDataServiceNotify 
09-01 11:16:20.582  1034  1544 D DSQN    : start dsqn bin
09-01 11:16:20.583  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:16:20.585  1034  1034 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
09-01 11:16:20.585  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-01 11:16:20.585  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-01 11:16:20.585  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-01 11:16:20.578  7167  7167 W dsqn    : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-01 11:16:20.578  7167  7167 W dsqn    : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-01 11:16:20.592  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-01 11:16:20.593  1602  1602 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-01 11:16:20.593  1602  1602 D StatusBar.NetworkController: refr,eshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:16:20.594  1034  1535 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,09-01 11:16:20.597  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-01 11:16:20.597  1602  1602 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-01 11:16:20.590  1034  1544 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
09-01 11:16:20.597  1034  1544 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-01 11:16:20.597  1034  1544 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-01 11:16:20.597  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:16:20.600  1034  1544 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-01 11:16:20.600  1602  2075 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-01 11:16:20.605  7167  7167 E DSQN    : DSQN ssw
09-01 11:16:20.607  7138  7138 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-01 11:16:20.607  7138  7138 D Weather.Utils: 2 : All the weather widget is gone.
,09-01 11:16:20.613  7138  7138 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-01 11:16:20.617  7138  7138 D WeatherAncestor: connectivity changed - connection : true
,09-01 11:16:20.622  1034  1537 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
,09-01 11:16:20.622  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-01 11:16:20.622  1815  7171 I CheckinService: active receiver: enabled
09-01 11:16:20.623  1034  1537 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
09-01 11:16:20.623  1034  1537 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-01 11:16:20.623  1034  1537 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-01 11:16:20.623  7138  7138 D WeatherService: 2 : isServiceAlived():false forecastCache:null
09-01 11:16:20.624  1034  1537 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
,09-01 11:16:20.646  1815  7171 I CheckinService: Preparing to send checkin request
09-01 11:16:20.646  1815  7171 I EventLogService: Accumulating logs since 1472721253974
09-01 11:16:20.647  7138  7138 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-01 11:16:20.648  7138  7138 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-01 11:16:20.648  7138  7138 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
09-01 11:16:20.649  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-01 11:16:20.650  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:16:20.651  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:16:20.657   309  7165 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,09-01 11:16:20.667  7138  7138 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-01 11:16:20.668  7138  7138 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:16:20
,09-01 11:16:20.687  1034  7156 D DhcpStateMachine: DHCPV4 request on wlan0
,09-01 11:16:20.688  1034  7156 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
09-01 11:16:20.688  1034  7156 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
09-01 11:16:20.690   309  7165 D libc-netbsd: res_queryN name = clients3.google.com succeed
09-01 11:16:20.678  7174  7174 W dhcpcd  : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-01 11:16:20.678  7174  7174 W dhcpcd  : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-01 11:16:20.699   309   892 D LGDataListener: argv[0]=dsqncommand
09-01 11:16:20.699   309   892 D LGDataListener: argv[1]=wlan0
09-01 11:16:20.699   309   892 D LGDataListener: argv[2]=1
09-01 11:16:20.699   309   892 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
09-01 11:16:20.699  1034  1094 D DSQN    : DSQM DsqnNotification wlan0  1
09-01 11:16:20.699  1034  1094 D DSQN    : start to monitor internet connection
09-01 11:16:20.707  1034  7155 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 01 Sep 2016 09:16:20 GMT], X-Android-Received-Millis=[1472721380707], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472721380698]}
09-01 11:16:20.707  1034  7155 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-01 11:16:20.707  1034  7155 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
09-01 11:16:20.707  1034  1544 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
09-01 11:16:20.707  1034  1544 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
09-01 11:16:20.708  1034  1544 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-01 11:16:20.708  1034  1544 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-01 11:16:20.708  1034  1544 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-01 11:16:20.708  1034  1544 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
09-01 11:16:20.708  1034  1544 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
09-01 11:16:20.708  1034  1544 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-01 11:16:20.708  1034  1544 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-01 11:16:20.708  1034  1544 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-01 11:16:20.709  1034  1544 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-01 11:16:20.709  1034  1544 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-01 11:16:20.709  1034  1537 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-01 11:16:20.709  1034  1537 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-01 11:16:20.710  7174  7174 I dhcpcd  : version 5.5.6 starting
09-01 11:16:20.710  1602  2075 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-01 11:16:20.710  1850  1850 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-01 11:16:20.710  1850  1850 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-01 11:16:20.712  7174  7174 E dhcpcd  : get_duid: m
09-01 11:16:20.712  7174  7174 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
09-01 11:16:20.712  7174  7174 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
09-01 11:16:20.718  1034  1993 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7177 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-01 11:16:20.719  1034  1993 I ActivityManager: Killing 2153:com.lge.music/u0a34 (adj 15): empty #17
,09-01 11:16:20.732   313  1385 V AudioFlinger: 2153 died, releasing its sessions
09-01 11:16:20.733   313  1385 V AudioFlinger:  pid 1850 @ 0
09-01 11:16:20.733   313  1385 V AudioFlinger:  pid 3463 @ 1
09-01 11:16:20.733   313  1385 V AudioFlinger:  pid 3463 @ 2
,09-01 11:16:20.764  7174  7174 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
,09-01 11:16:20.764  7174  7174 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
,09-01 11:16:20.764  7174  7174 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-01 11:16:20.764  7174  7174 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
09-01 11:16:20.764  7174  7174 D dhcpcd  : wlan0: sending REQUEST (xid 0xd7d819af), next in 4.61 seconds
09-01 11:16:20.769  1034  2048 W libprocessgroup: failed to open /acct/uid_10034/pid_2153/cgroup.procs: No such file or directory
09-01 11:16:20.777  1815  7171 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
09-01 11:16:20.778  7174  7174 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,09-01 11:16:20.789  7174  7174 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
09-01 11:16:20.789  7174  7174 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
,09-01 11:16:20.789  7174  7174 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
09-01 11:16:20.789  7174  7174 D dhcpcd  : wlan0: adding default route via 192.168.1.1
09-01 11:16:20.790  7174  7174 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-01 11:16:20.790  7174  7174 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-01 11:16:20.790  7174  7174 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-01 11:16:20.790  7174  7174 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,09-01 11:16:20.801  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-01 11:16:20.803  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:16:20.804  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-01 11:16:20.890   278   441 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-01 11:16:20.890   278   441 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-01 11:16:20.890   278   441 W Vold    : Returning OperationFailed - no handler for errno 0
09-01 11:16:20.890  7177  7210 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
09-01 11:16:20.892   278   441 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-01 11:16:20.892   278   441 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-01 11:16:20.892   278   441 W Vold    : Returning OperationFailed - no handler for errno 0
09-01 11:16:20.893  7177  7210 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,09-01 11:16:20.903  1034  1917 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7216 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
09-01 11:16:20.920   278   441 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,09-01 11:16:20.920   278   441 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-01 11:16:20.920   278   441 W Vold    : Returning OperationFailed - no handler for errno 0
09-01 11:16:20.921  7177  7221 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
09-01 11:16:20.933   278   441 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-01 11:16:20.933   278   441 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-01 11:16:20.933   278   441 W Vold    : Returning OperationFailed - no handler for errno 0
09-01 11:16:20.933  7177  7221 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
09-01 11:16:20.949  7216  7216 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,09-01 11:16:20.949  7216  7216 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
09-01 11:16:20.970  7216  7216 I MultiDex: VM with version 2.1.0 has multidex support
09-01 11:16:20.970  7216  7216 I MultiDex: install
09-01 11:16:20.970  7216  7216 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,09-01 11:16:20.980  7216  7216 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,09-01 11:16:21.090  1034  7156 D DhcpStateMachine: DHCPV4 succeeded on wlan0
09-01 11:16:21.091  1034  7156 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
,09-01 11:16:21.091  1034  7156 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-01 11:16:21.091  1034  7156 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
09-01 11:16:21.091  1034  7156 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
09-01 11:16:21.091  1034  7156 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-01 11:16:21.091  1034  7156 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
09-01 11:16:21.091  1034  7156 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
09-01 11:16:21.092  1034  7156 D DhcpStateMachine: RunningState
09-01 11:16:21.095  7177  7177 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,09-01 11:16:21.133  1034  2048 I art     : Explicit concurrent mark sweep GC freed 105406(5MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/65MB, paused 8.378ms total 109.576ms
,09-01 11:16:21.138  7177  7177 I LibraryLoader: Loading: webviewchromium
09-01 11:16:21.140  7177  7177 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 4709-4712)
09-01 11:16:21.140  7177  7177 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-01 11:16:21.144  7177  7177 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2792eea0}
09-01 11:16:21.145  7177  7177 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-01 11:16:21.146  7177  7177 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
09-01 11:16:21.157  7177  7177 I BrowserStartupController: Initializing chromium process, renderers=0
09-01 11:16:21.158  7177  7177 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-01 11:16:21.167   313  1386 V AudioPolicyService: registerClient() client 0xb558a2c0, uid 10093
09-01 11:16:21.168  7177  7177 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,09-01 11:16:21.169  7177  7177 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
09-01 11:16:21.169  7177  7177 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
09-01 11:16:21.171  7177  7263 W AudioManagerAndroid: Requires BLUETOOTH permission
09-01 11:16:21.177  7177  7177 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-01 11:16:21.177  7177  7177 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-01 11:16:21.177  7177  7177 I Adreno-EGL: Build Date: 12/12/14 금
09-01 11:16:21.177  7177  7177 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-01 11:16:21.177  7177  7177 I Adreno-EGL: Remote Branch: 
09-01 11:16:21.177  7177  7177 I Adreno-EGL: Local Patches: 
09-01 11:16:21.177  7177  7177 I Adreno-EGL: Reconstruct Branch: 
09-01 11:16:21.220  7177  7177 I NSApplication: Starting up...
,09-01 11:16:21.271  1034  1050 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7276 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,09-01 11:16:21.273  1034  1050 I ActivityManager: Killing 6108:com.android.vending/u0a44 (adj 15): empty #17
09-01 11:16:21.284  7216  7235 D LgDataFeature: LgDataFeature() Constructor: none
09-01 11:16:21.284  7216  7235 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-01 11:16:21.291   349   349 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 538us total 17.516ms
09-01 11:16:21.307   349   349 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 342us total 15.703ms
,09-01 11:16:21.321   349   349 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 453us total 12.953ms
,09-01 11:16:21.330  1034  1574 W libprocessgroup: failed to open /acct/uid_10044/pid_6108/cgroup.procs: No such file or directory
09-01 11:16:21.362  7276  7276 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-01 11:16:21.450  7293  7293 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,09-01 11:16:21.516  7293  7293 I dex2oat : dex2oat took 65.840ms (threads: 4)
,09-01 11:16:21.533  7216  7235 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-01 11:16:21.533  7216  7235 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-01 11:16:21.533  7216  7235 I Adreno-EGL: Build Date: 12/12/14 금
09-01 11:16:21.533  7216  7235 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-01 11:16:21.533  7216  7235 I Adreno-EGL: Remote Branch: 
09-01 11:16:21.533  7216  7235 I Adreno-EGL: Local Patches: 
09-01 11:16:21.533  7216  7235 I Adreno-EGL: Reconstruct Branch: 
,09-01 11:16:21.567  1034  1650 D WifiServiceImplEx: setWifiEnabled: false pid=6682, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-01 11:16:21.567  1034  1650 D WifiService: setWifiEnabled: false pid=6682, uid=10118
09-01 11:16:21.567  1034  1650 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-01 11:16:21.578  1034  1537 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
09-01 11:16:21.578  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-01 11:16:21.578  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
09-01 11:16:21.578  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-01 11:16:21.578  1034  1034 D Ulp_jni : JNI:system_update. Event-4
09-01 11:16:21.578  1034  1537 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
09-01 11:16:21.578  1034  1537 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
09-01 11:16:21.579  1034  1537 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
09-01 11:16:21.579  1034  1537 E WifiStateMachine: WifiStateMachine: Leaving Connected state
09-01 11:16:21.579  1034  1537 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-01 11:16:21.579  1034  1537 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-01 11:16:21.579  1034  1537 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-01 11:16:21.579  1034  1537 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,09-01 11:16:21.584  1034  1537 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-01 11:16:21.584  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-01 11:16:21.584  7064  7064 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-01 11:16:21.585  1034  1536 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:16:21.585  1034  1536 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:16:21.585  1034  1537 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-01 11:16:21.585  1034  1537 D WifiNative-wlan0: doBoolean: SET ps 1
09-01 11:16:21.585  1034  1537 D WifiNative-wlan0: SET ps 1: returned true
09-01 11:16:21.586   309   893 D CommandListener: Clearing all IP addresses on wlan0
09-01 11:16:21.586  1034  7156 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:16:21.597  1034  1544 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-01 11:16:21.612  1034  1544 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-01 11:16:21.613  1034  1544 D ConnectivityService: ignoring duplicate network state non-change
09-01 11:16:21.613  1034  1544 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
09-01 11:16:21.613  1034  1537 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:16:21.615  1034  1536 D LGWifiP2pService: InactiveState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:16:21.615  1034  1536 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:16:21.615  1034  1536 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@2c370b7
,09-01 11:16:21.615  1034  1034 D WifiHS20: hidePasspointNotification off =false
09-01 11:16:21.617  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-01 11:16:21.617  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-01 11:16:21.618  1939  1939 V WfdStateTracker: handleWifiStateChangedEvent: 0
09-01 11:16:21.619  1034  1537 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:16:21.623  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:16:21.623  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:16:21.623  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:16:21.623  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-01 11:16:21.623  1034  1034 D WifiHS20: hidePasspointNotification off =false
09-01 11:16:21.623  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:16:21.623  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:16:21.623  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-01 11:16:21.623  1034  1034 D WifiScanningService: SCAN_AVAILABLE : 1
09-01 11:16:21.623  1034  1034 D RttService: SCAN_AVAILABLE : 1
09-01 11:16:21.624  1034  1536 D LGWifiP2pService: P2pDisablingState
09-01 11:16:21.624  1034  1536 D LGWifiP2pService: P2pDisablingState{ when=-9ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:16:21.624  1034  1536 D LGWifiP2pService: p2p socket connection lost
09-01 11:16:21.624  1034  1536 D LGWifiP2pService: P2pDisabledState
09-01 11:16:21.624  1034  1555 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:16:21.624  1034  1556 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-01 11:16:21.620  1034  1537 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:16:21.629  1939  1939 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-01 11:16:21.629  1939  1939 D WfdsService: WifiP2pState is changed : false
09-01 11:16:21.629  1939  2284 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
09-01 11:16:21.629  1939  2284 D WfdsService: Set the WFDS Monitor: false
09-01 11:16:21.630  1034  1537 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:16:21.631  1939  2284 D WfdsMonitor: WFDS Monitor is stopped
09-01 11:16:21.631  1034  1537 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:16:21.631  1939  2284 D WfdsService: STATE : WfdsDisabledState - enter
09-01 11:16:21.631  1939  7096 D CtrlSupplicant: Received on exit socket, terminate
09-01 11:16:21.631  1939  7096 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
09-01 11:16:21.631  1939  7096 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
09-01 11:16:21.631  1939  7096 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
09-01 11:16:21.631  1034  1537 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:16:21.631  1034  1537 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-01 11:16:21.631  1939  2288 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
09-01 11:16:21.631  1939  2284 W WfdsService: DefaultState - msg [9445378] is not handled
,09-01 11:16:21.632  1034  1537 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
09-01 11:16:21.633  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-01 11:16:21.633  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-01 11:16:21.634  1034  1536 D LGWifiP2pService: P2pDisabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:16:21.634  1034  1536 D LGWifiP2pService: DefaultState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:16:21.634  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-01 11:16:21.634  7064  7064 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-01 11:16:21.635  1034  1537 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-01 11:16:21.635  1034  1537 D WifiNative-wlan0: doBoolean: SET ps 1
09-01 11:16:21.635  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:16:21.635  1034  1537 D WifiNative-wlan0: SET ps 1: returned true
09-01 11:16:21.657  6350  6350 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-01 11:16:21.659  6350  6833 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,09-01 11:16:21.662   309   893 D CommandListener: Clearing all IP addresses on wlan0
09-01 11:16:21.663  1034  1544 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
09-01 11:16:21.663  1034  1544 D DSQN    : disableDataServiceNotify
09-01 11:16:21.663  1034  1544 D DSQN    : stop dsqn bin
09-01 11:16:21.665  1034  1537 D WifiNative-p2p0: doBoolean: TERMINATE
09-01 11:16:21.666  1034  1537 D WifiNative-p2p0: TERMINATE: returned true
09-01 11:16:21.666  1034  1537 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-01 11:16:21.666  1034  1537 E WifiStateMachine: useWiFiOffloading() : false
09-01 11:16:21.666  1034  1537 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-01 11:16:21.666  1034  1034 D WifiHS20: hidePasspointNotification off =false
09-01 11:16:21.667  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:16:21.667  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:16:21.667  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-01 11:16:21.667  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-01 11:16:21.667  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-01 11:16:21.668  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:16:21.668  1034  1544 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
09-01 11:16:21.668  1034  1544 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-01 11:16:21.668  1034  1544 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-01 11:16:21.669  1034  1544 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
09-01 11:16:21.669  1939  1939 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
09-01 11:16:21.670  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-01 11:16:21.671  6682  6682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:16:21.671  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:16:21.671  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:16:21.671  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-01 11:16:21.671  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 11:16:21.671  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 11:16:21.671  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:16:21.671  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:16:21.671  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-01 11:16:21.671  6682  6682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:16:21.671  6682  6682 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-01 11:16:21.672  6682  6682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:16:21.672  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:16:21.672  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:16:21.672  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-01 11:16:21.672  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 11:16:21.672  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 11:16:21.672  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:16:21.672  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:16:21.672  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-01 11:16:21.672  6682  6682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:16:21.672  6682  6682 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-01 11:16:21.673  1034  1544 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
09-01 11:16:21.673  1034  1544 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
09-01 11:16:21.673  1034  1544 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgen,tInfo [WIFI () - 101] isDefaultNetwork=true
09-01 11:16:21.673  1034  1544 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-01 11:16:21.673  1034  7155 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:16:21.673  1034  7155 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:16:21.673  1034  7155 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-01 11:16:21.674  1602  2075 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-01 11:16:21.674  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
09-01 11:16:21.674  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-01 11:16:21.674  1034  1034 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
09-01 11:16:21.675  1034  1544 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-01 11:16:21.676  1034  1535 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-01 11:16:21.677  1034  1034 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-01 11:16:21.677  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-01 11:16:21.677  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-01 11:16:21.677  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-01 11:16:21.675  1034  1544 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-01 11:16:21.677  1034  1544 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-01 11:16:21.677  1034  1544 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-01 11:16:21.677  1034  1544 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-01 11:16:21.678  1034  1537 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-01 11:16:21.678  1034  1544 D NetworkManagementService: Removing idletimer
09-01 11:16:21.678  1034  1537 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-01 11:16:21.678  1034  1544 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:16:21.678  1850  1850 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-01 11:16:21.678  1850  1850 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-01 11:16:21.678  1034  1535 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-01 11:16:21.678  1034  1034 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-01 11:16:21.679  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-01 11:16:21.679  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-01 11:16:2,1.679  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-01 11:16:21.682  2180  2180 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
09-01 11:16:21.698  7003  7003 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-01 11:16:21.698  7003  7003 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-01 11:16:21.698  7003  7003 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-01 11:16:21.698  7003  7003 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-01 11:16:21.699  7216  7235 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-01 11:16:21.699  7216  7235 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-01 11:16:21.699  7216  7235 I Adreno-EGL: Build Date: 12/12/14 금
09-01 11:16:21.699  7216  7235 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-01 11:16:21.699  7216  7235 I Adreno-EGL: Remote Branch: 
09-01 11:16:21.699  7216  7235 I Adreno-EGL: Local Patches: 
09-01 11:16:21.699  7216  7235 I Adreno-EGL: Reconstruct Branch: 
09-01 11:16:21.700  7003  7003 I AppUp4:CustModeStarterReceiver: onReceive
09-01 11:16:21.704  7003  7003 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1ac480b1
09-01 11:16:21.704  7003  7003 D AppUp4:CustFacade: isCustomizationCompleted : false
09-01 11:16:21.704  7003  7003 D AppUp4:CustFacade: isPhone : true
09-01 11:16:21.705  7003  7003 D AppUp4:CustModeStarterReceiver: begin check event
09-01 11:16:21.705  7003  7003 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-01 11:16:21.709  4322  4322 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-01 11:16:21.709  4322  4322 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-01 11:16:21.712  4322  4322 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-01 11:16:21.715  4322  4322 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-01 11:16:21.718  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-01 11:16:21.719  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:16:21.719  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:16:21.723  4322  7315 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-01 11:16:21.724  7033  7033 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
09-01 11:16:21.726  4322  7318 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-01 11:16:21.726  4322  7318 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-01 11:16:21.740  7064  7064 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-01 11:16:21.740  7064  7064 I wpa_supplicant: monitor socket send errors count : 1
09-01 11:16:21.740  7064  7064 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1939-4\x00 that cannot receive messages
,09-01 11:16:21.742  1034  7077 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
09-01 11:16:21.742  1034  7077 D WifiMonitor: Dropping event because (p2p0) is stopped
09-01 11:16:21.746  7033  7321 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:16:21.747  3463  3463 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-01 11:16:21.747  3463  3463 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-01 11:16:21.747  3463  3463 I LgeMiscReceiver: networkInfo.isConnected() = false
09-01 11:16:21.750  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-01 11:16:21.751  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:16:21.751  7079  7079 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-01 11:16:21.751  7079  7079 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-01 11:16:21.751  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:16:21.754  6937  7322 W FormManager: Network not available. Please check & try again.
,09-01 11:16:21.759  7138  7138 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:16:21
09-01 11:16:21.759  6937  7323 V FormManager: Network unavailable.
09-01 11:16:21.761  6937  7323 V FormManager: Network unavailable.
09-01 11:16:21.762  7138  7138 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-01 11:16:21.762  7138  7138 D Weather.Utils: 2 : All the weather widget is gone.
09-01 11:16:21.762  7064  7064 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-01 11:16:21.763  7138  7138 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-01 11:16:21.763  7138  7138 D WeatherAncestor: connectivity changed - connection : true
09-01 11:16:21.763  7138  7138 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@15e15917
09-01 11:16:21.763  7064  7064 W wpa_supplicant: USIM:  scard_deinit function
09-01 11:16:21.764  1034  1096 D Tethering: InitialState.processMessage what=4
09-01 11:16:21.764  7138  7138 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-01 11:16:21.764  7138  7138 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-01 11:16:21.764  7138  7138 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-01 11:16:21.764  7138  7138 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-01 11:16:21.764  7138  7138 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:16:21
09-01 11:16:21.764  1034  1096 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-01 11:16:21.764  1034  7077 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
09-01 11:16:21.764  1034  7077 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-01 11:16:21.764  1034  7077 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-01 11:16:21.764  1034  7077 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
09-01 11:16:21.764  1034  7077 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-01 11:16:21.764  1034  7077 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-01 11:16:21.767  1034  1537 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
09-01 11:16:21.767  1034  1537 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,09-01 11:16:21.768  1034  1537 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=185328
09-01 11:16:21.769  1034  1537 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=185330
09-01 11:16:21.770  1034  1537 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=185330  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-01 11:16:21.770  1034  1537 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=185331  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-01 11:16:21.773  7216  7235 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-01 11:16:21.773  7216  7235 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-01 11:16:21.773  7216  7235 I Adreno-EGL: Build Date: 12/12/14 금
09-01 11:16:21.773  7216  7235 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-01 11:16:21.773  7216  7235 I Adreno-EGL: Remote Branch: 
09-01 11:16:21.773  7216  7235 I Adreno-EGL: Local Patches: 
09-01 11:16:21.773  7216  7235 I Adreno-EGL: Reconstruct Branch: 
09-01 11:16:21.781  6814  6814 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-01 11:16:21.781  6814  6814 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-01 11:16:21.781  6814  6814 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-01 11:16:21.781  6814  6814 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,09-01 11:16:21.782  6814  6814 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-01 11:16:21.783  6814  6814 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-01 11:16:21.783  6814  6814 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-01 11:16:21.783  6814  6814 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-01 11:16:21.783  6814  6814 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-01 11:16:21.783  6814  6814 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-01 11:16:21.783  6814  6814 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-01 11:16:21.790  6834  6834 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-01 11:16:21.791  6814  6814 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-01 11:16:21.796  6937  7327 W FormManager: Network not available. Please check & try again.
09-01 11:16:21.797  6814  6814 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-01 11:16:21.800  1034  7156 D DhcpStateMachine: StoppedState
09-01 11:16:21.800  1034  7156 D DhcpStateMachine: StoppedState{ when=-165ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:16:21.801  1034  1537 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
09-01 11:16:21.801  1034  1537 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
09-01 11:16:21.803  6937  7328 V FormManager: Network unavailable.
,09-01 11:16:21.805  6937  7328 V FormManager: Network unavailable.
09-01 11:16:21.807  6834  6834 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-01 11:16:21.809  6814  6814 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-01 11:16:21.812  6937  7329 W FormManager: Network not available. Please check & try again.
09-01 11:16:21.813  6814  6814 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-01 11:16:21.817  6937  7330 V FormManager: Network unavailable.
,09-01 11:16:21.822  6937  7330 V FormManager: Network unavailable.
09-01 11:16:21.823  4322  4322 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-01 11:16:21.823  4322  4322 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-01 11:16:21.824  4322  4322 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-01 11:16:21.827  4322  4322 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-01 11:16:21.831  4322  7331 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-01 11:16:21.832  4322  7332 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-01 11:16:21.832  4322  7332 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-01 11:16:21.860  1034  1780 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7333 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,09-01 11:16:21.902  7064  7064 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-01 11:16:21.902  1034  7077 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
09-01 11:16:21.902  1034  7077 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-TERMINATING 
09-01 11:16:21.903  1034  7077 D WifiMonitor: Disconnecting from the supplicant, no more events
09-01 11:16:21.903  1034  1537 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 44 0
,09-01 11:16:21.922  7333  7333 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-01 11:16:21.923  7333  7333 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
09-01 11:16:21.927  7333  7333 V [BNRBootReceiver]: Boot Receiver Return
09-01 11:16:21.927  7333  7333 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-01 11:16:21.930  6350  6350 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-01 11:16:21.938  6814  6814 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-01 11:16:21.943  6814  6814 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-01 11:16:21.952  6868  6868 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-01 11:16:21.952  6868  6868 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-01 11:16:21.953  6868  6868 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-01 11:16:21.956  6814  6814 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
09-01 11:16:21.958  6814  6814 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
09-01 11:16:21.961  6350  6350 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-01 11:16:21.973  6814  6814 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-01 11:16:21.978  6814  6814 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-01 11:16:21.984  6868  6868 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-01 11:16:21.985  6868  6868 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-01 11:16:21.986  6868  6868 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-01 11:16:21.989  6350  6350 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-01 11:16:22.000  6814  6814 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-01 11:16:22.004  1939  1939 D WfdsService: Supplicant Connection state is changed : false
09-01 11:16:22.004  1939  2284 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
09-01 11:16:22.004  1939  2284 D WfdsService: Set the WFDS Monitor: false
09-01 11:16:22.004  1939  2284 D WfdsMonitor: WFDS Monitor is stopped
09-01 11:16:22.004  1034  1537 D WifiOffDelayIfNotUsed: stopMonitoring
09-01 11:16:22.005  1034  1537 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-01 11:16:22.005  1034  1537 E WifiStateMachine: useWiFiOffloading() : false
09-01 11:16:22.005  1034  1537 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-01 11:16:22.006  1939  1939 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-01 11:16:22.007  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:16:22.008  2470  2470 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:16:22.008  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
09-01 11:16:22.009  1034  1541 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
09-01 11:16:22.009  1034  1541 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
09-01 11:16:22.009  6682  6682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:16:22.009  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:16:22.009  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:16:22.009  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-01 11:16:22.009  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 11:16:22.009  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 11:16:22.009  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:16:22.009  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:16:22.009  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 11:16:22.010  6682  6682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:16:22.010  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:16:22.010  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:16:22.010  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-01 11:16:22.010  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 11:16:22.010  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 11:16:22.010  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:16:22.010  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:16:22.010  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 11:16:22.013  6814  6814 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-01 11:16:22.022  6868  6868 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-01 11:16:22.023  6868  6868 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-01 11:16:22.023  6868  6868 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-01 11:16:22.030  6350  6350 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-01 11:16:22.036  6814  6814 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-01 11:16:22.047  6814  6814 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-01 11:16:22.054  6868  6868 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-01 11:16:22.055  6868  6868 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-01 11:16:22.055  6868  6868 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-01 11:16:22.059  6350  6350 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-01 11:16:22.075  6814  6814 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-01 11:16:22.099  6814  6814 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-01 11:16:22.108  6868  6868 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-01 11:16:22.109  6868  6868 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-01 11:16:22.109  6868  6868 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-01 11:16:22.113  6350  6350 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-01 11:16:22.116   309  7352 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
09-01 11:16:22.117  1034  1094 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
09-01 11:16:22.118  1815  7171 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,09-01 11:16:22.127  6814  6814 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-01 11:16:22.131  1815  7171 I CheckinService: active receiver: disabled
09-01 11:16:22.135  6814  6814 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-01 11:16:22.147  6868  6868 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-01 11:16:22.148  6868  6868 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-01 11:16:22.149  6868  6868 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-01 11:16:22.154  6350  6350 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-01 11:16:22.164  6814  6814 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-01 11:16:22.172  6814  6814 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-01 11:16:22.182  6868  6868 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-01 11:16:22.182  6868  6868 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-01 11:16:22.183  6868  6868 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-01 11:16:22.194  6350  6350 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-01 11:16:22.216  6814  6814 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-01 11:16:22.225  6814  6814 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-01 11:16:22.239  6868  6868 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-01 11:16:22.240  6868  6868 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-01 11:16:22.247  6868  6868 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-01 11:16:22.257  6350  6350 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-01 11:16:22.272  6814  6814 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-01 11:16:22.284  6814  6814 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-01 11:16:22.296  6868  6868 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-01 11:16:22.297  6868  6868 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-01 11:16:22.300  6868  6868 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-01 11:16:22.308  6350  6350 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-01 11:16:22.317  6834  6834 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,09-01 11:16:22.334  1034  1543 D WifiService: New client listening to asynchronous messages
09-01 11:16:22.337  6834  6834 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-01 11:16:22.345  6814  6814 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-01 11:16:22.360  6814  6814 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-01 11:16:22.379  6868  6868 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-01 11:16:22.382  6868  6868 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-01 11:16:22.385  6868  6868 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-01 11:16:22.388  6868  6868 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-01 11:16:22.389  6868  6868 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-01 11:16:22.402  6350  6350 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-01 11:16:22.416  6834  6834 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-01 11:16:22.419  6834  6834 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-01 11:16:22.429  6814  6814 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-01 11:16:22.436  6814  6814 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-01 11:16:22.450  6868  6868 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-01 11:16:22.451  6868  6868 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-01 11:16:22.453  6868  6868 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-01 11:16:22.454  6868  6868 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-01 11:16:22.455  6868  6868 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-01 11:16:22.459  1034  2022 I ActivityManager: Killing 6795:com.lge.lifetracker/u0a37 (adj 15): empty #17
09-01 11:16:22.512  1034  1650 W libprocessgroup: failed to open /acct/uid_10037/pid_6795/cgroup.procs: No such file or directory
,09-01 11:16:22.519  1034  1379 D PowerManagerServiceEx: acquireWakeLockInternal: lock=757214362, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1034
09-01 11:16:22.520  2180  2180 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
09-01 11:16:22.539  2180  2180 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,09-01 11:16:22.540  2180  2180 D c       : Getting all permits...
09-01 11:16:22.540  2180  2180 D a       : Opening database...
09-01 11:16:22.551  2180  2180 D a       : Opening database auth.proximity.permit_store...
09-01 11:16:22.553  2180  2180 D a       : Closing database...
,09-01 11:16:22.559  2606  2606 D [Concierge]Service: onStartCommand(). Type : 9
09-01 11:16:22.577  6350  6350 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-01 11:16:22.582  6834  6834 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,09-01 11:16:22.582  6834  6834 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-01 11:16:22.582  6834  6834 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-01 11:16:22.586  6814  6814 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-01 11:16:22.595  6814  6814 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-01 11:16:22.602  6868  6868 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-01 11:16:22.602  6868  6868 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-01 11:16:22.604  6868  6868 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-01 11:16:22.607  6350  6350 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-01 11:16:22.611  6834  6834 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-01 11:16:22.611  6834  6834 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-01 11:16:22.611  6834  6834 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-01 11:16:22.615  6814  6814 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-01 11:16:22.621  6814  6814 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-01 11:16:22.628  6868  6868 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-01 11:16:22.629  6868  6868 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-01 11:16:22.630  6868  6868 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-01 11:16:22.635  6350  6350 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-01 11:16:22.639  6834  6834 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-01 11:16:22.639  6834  6834 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-01 11:16:22.639  6834  6834 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-01 11:16:22.643  6814  6814 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-01 11:16:22.651  6814  6814 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-01 11:16:22.659  6868  6868 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-01 11:16:22.660  6868  6868 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-01 11:16:22.662  6868  6868 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-01 11:16:22.673  6834  6834 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-01 11:16:22.678  6814  6814 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-01 11:16:22.683  6937  7360 W FormManager: Network not available. Please check & try again.
,09-01 11:16:22.685  6814  6814 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-01 11:16:22.705  6937  7361 V FormManager: Network unavailable.
,09-01 11:16:22.711  4322  4322 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-01 11:16:22.711  4322  4322 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-01 11:16:22.712  6937  7361 V FormManager: Network unavailable.
09-01 11:16:22.713  4322  4322 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-01 11:16:22.717  4322  4322 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-01 11:16:22.724  4322  7362 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-01 11:16:22.729  4322  7363 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-01 11:16:22.730  4322  7363 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-01 11:16:22.732  6834  6834 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
09-01 11:16:22.732  6834  6834 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-01 11:16:22.732  6834  6834 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-01 11:16:22.735  6814  6814 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-01 11:16:22.743  6814  6814 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-01 11:16:22.754  6937  7365 W FormManager: Network not available. Please check & try again.
,09-01 11:16:22.760  6937  7366 V FormManager: Network unavailable.
09-01 11:16:22.765  2180  2180 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
09-01 11:16:22.767  6937  7366 V FormManager: Network unavailable.
09-01 11:16:22.785  6868  6868 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
,09-01 11:16:22.786  6868  6868 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:2458
,09-01 11:16:22.786  1034  1034 D PowerManagerServiceEx: releaseWakeLockInternal: lock=757214362 [*alarm*], flags=0x0
,09-01 11:16:22.965  6559  6983 D UEI.SmartControl: Internal timer expired: 4
09-01 11:16:22.965  6559  6983 D UEI.SmartControl: unbind internal service
,09-01 11:16:23.003  6559  6980 D serial_port: close(fd = 24)
,09-01 11:16:23.009  6559  6980 I UEI.SmartControl: Serial port is closed.
,09-01 11:16:23.483  1034  1537 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-452399046] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-01 11:16:23.485  1034  1537 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-452399043] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,09-01 11:16:23.582  1034  1544 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-01 11:16:23.595  1034  1096 D Tethering: MasterInitialState.processMessage what=3
09-01 11:16:23.606  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:16:23.610  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:16:23.613  1034  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-01 11:16:23.616  6350  6350 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-01 11:16:23.617  6350  6833 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-01 11:16:23.627  5783  5783 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,09-01 11:16:23.647  2180  2180 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-01 11:16:23.666  7003  7003 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-01 11:16:23.666  7003  7003 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-01 11:16:23.666  7003  7003 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-01 11:16:23.666  7003  7003 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,09-01 11:16:23.671  7003  7003 I AppUp4:CustModeStarterReceiver: onReceive
09-01 11:16:23.675  7003  7003 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1ac480b1
09-01 11:16:23.675  7003  7003 D AppUp4:CustFacade: isCustomizationCompleted : false
09-01 11:16:23.675  7003  7003 D AppUp4:CustFacade: isPhone : true
09-01 11:16:23.675  7003  7003 D AppUp4:CustModeStarterReceiver: begin check event
09-01 11:16:23.675  7003  7003 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-01 11:16:23.681  4322  4322 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-01 11:16:23.681  4322  4322 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-01 11:16:23.683  4322  4322 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-01 11:16:23.688  4322  4322 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-01 11:16:23.696  7033  7033 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,09-01 11:16:23.719  4322  7375 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-01 11:16:23.726  7033  7374 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:16:23.735  4322  7376 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-01 11:16:23.735  4322  7376 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,09-01 11:16:23.749  1034  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-01 11:16:23.755  6937  7377 W FormManager: Network not available. Please check & try again.
09-01 11:16:23.756  6937  7378 V FormManager: Network unavailable.
09-01 11:16:23.771  3463  3463 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-01 11:16:23.771  3463  3463 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-01 11:16:23.771  3463  3463 I LgeMiscReceiver: networkInfo.isConnected() = true
09-01 11:16:23.771  3463  3463 D PhoneState: setPdpRejectCasuse : false
,09-01 11:16:23.774  6937  7378 V FormManager: Network unavailable.
09-01 11:16:23.777  7079  7079 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-01 11:16:23.777  7079  7079 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-01 11:16:23.790  7138  7138 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:16:23
,09-01 11:16:23.792  7138  7138 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,09-01 11:16:23.792  7138  7138 D Weather.Utils: 2 : All the weather widget is gone.
,09-01 11:16:23.793  7138  7138 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,09-01 11:16:23.793  7138  7138 D WeatherAncestor: connectivity changed - connection : true
09-01 11:16:23.793  7138  7138 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@15e15917
09-01 11:16:23.794  7138  7138 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-01 11:16:23.794  7138  7138 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
,09-01 11:16:23.794  7138  7138 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-01 11:16:23.794  7138  7138 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-01 11:16:23.794  7138  7138 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:16:23
09-01 11:16:24.581  1034  1780 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:16:24.582  1034  1780 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,09-01 11:16:24.612  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-01 11:16:24.612  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-01 11:16:24.612  1034  1034 D Ulp_jni : JNI:system_update. Event-4
,09-01 11:16:24.615  1034  1096 D BluetoothManagerService: Message: 1
09-01 11:16:24.615  1034  1096 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
,09-01 11:16:24.645  1034  1096 D BluetoothManagerService: Message: 20
09-01 11:16:24.645  1034  1096 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@9a90445:true
,09-01 11:16:24.648  6920  6920 D BluetoothAdapterState: make
09-01 11:16:24.653  6920  6920 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
09-01 11:16:24.653  6920  6920 I bluedroid-qcom: init
09-01 11:16:24.654  6920  7407 I BluetoothAdapterState: Entering OffState
09-01 11:16:24.655  6920  6920 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-01 11:16:24.655  6920  6920 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-01 11:16:24.655  6920  6920 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-01 11:16:24.655  6920  6920 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-01 11:16:24.655  6920  6920 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
09-01 11:16:24.657  6920  6920 I bluedroid-qcom: get_profile_interface socket
09-01 11:16:24.657  6920  6920 I bluedroid-qcom: get_profile_interface map_client
,09-01 11:16:24.648  7410  7410 W bdaddr_loader: type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-01 11:16:24.663  6920  7411 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
09-01 11:16:24.666  6920  7411 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
09-01 11:16:24.648  7410  7410 W bdaddr_loader: type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-01 11:16:24.675  7410  7410 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
09-01 11:16:24.675  7410  7410 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
09-01 11:16:24.675  7410  7410 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,09-01 11:16:24.679  1034  1034 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-01 11:16:24.680  1034  1034 D BluetoothManagerService: Stored Bluetooth name: G3
09-01 11:16:24.680  1034  1544 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-01 11:16:24.684  1034  1096 D Tethering: MasterInitialState.processMessage what=3
09-01 11:16:24.685  7410  7410 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
09-01 11:16:24.686  1034  1544 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-01 11:16:24.689  1034  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-01 11:16:24.693  7410  7410 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
09-01 11:16:24.693  7410  7410 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
09-01 11:16:24.699  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:16:24.699  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:16:24.702  6920  7411 D BluetoothAdapterProperties: Name is: G3
,09-01 11:16:24.706  6350  6350 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-01 11:16:24.707  6350  6833 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-01 11:16:24.712  1034  1096 D Tethering: MasterInitialState.processMessage what=3
09-01 11:16:24.720  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:16:24.723  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:16:24.732  1034  1034 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,09-01 11:16:24.734  1034  1096 D BluetoothManagerService: Message: 40
09-01 11:16:24.734  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,09-01 11:16:24.735  6920  6936 I bluedroid-qcom: config_hci_snoop_log
09-01 11:16:24.737  1034  1096 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
09-01 11:16:24.737  1034  1096 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
09-01 11:16:24.753  5783  5783 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,09-01 11:16:24.760  6920  7407 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
09-01 11:16:24.761  6920  7407 D BluetoothAdapterProperties: Setting state to 11
09-01 11:16:24.761  6920  7407 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-01 11:16:24.763  1034  1096 D BluetoothManagerService: Message: 60
09-01 11:16:24.763  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
09-01 11:16:24.763  1034  1096 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
09-01 11:16:24.764  6920  7407 I LGBluetoothServiceJni: classInitNative: succeeds
09-01 11:16:24.766  1034  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-01 11:16:24.766  1939  1939 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:16:24.768  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,09-01 11:16:24.775  6814  6814 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
09-01 11:16:24.775  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:16:24.776  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:16:24.783  6920  7407 D BluetoothBondStateMachine: make
09-01 11:16:24.789  6920  6920 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-01 11:16:24.791  6920  6920 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:16:24.791  6920  6920 V BluetoothPbapReceiver: ***********state = 11
09-01 11:16:24.792  5783  5783 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,09-01 11:16:24.795  6920  7407 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15e15917
,09-01 11:16:24.795  6920  7407 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
09-01 11:16:24.795  6920  7407 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15e15917
09-01 11:16:24.795  6920  7407 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
09-01 11:16:24.796  6920  7429 I BluetoothBondStateMachine: StableState(): Entering Off State
09-01 11:16:24.796  6920  7407 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
09-01 11:16:24.797  2180  2180 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-01 11:16:24.803  6920  7407 E BluetoothAdapterService: File transfer profiles supported!!
09-01 11:16:24.848  1034  1923 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7430 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,09-01 11:16:24.862  6920  7407 E BluetoothAdapterService: File transfer profiles supported!!
09-01 11:16:24.863  2180  2180 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-01 11:16:24.869  6920  6920 D HeadsetService: Received start request. Starting profile...
09-01 11:16:24.869  6920  6920 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
09-01 11:16:24.870  6920  6920 D LGBluetoothHfpAdapter: Version 1.6
09-01 11:16:24.872  6920  7407 E BluetoothAdapterService: File transfer profiles supported!!
09-01 11:16:24.873  6920  6920 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-01 11:16:24.875  6920  6920 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-01 11:16:24.875  6920  6920 D HeadsetStateMachine: make
09-01 11:16:24.884  6920  7407 E BluetoothAdapterService: File transfer profiles supported!!
,09-01 11:16:24.893  6920  7407 E BluetoothAdapterService: File transfer profiles supported!!
09-01 11:16:24.897  7003  7003 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-01 11:16:24.898  1034  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-01 11:16:24.898  1034  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-01 11:16:24.899  7003  7003 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-01 11:16:24.899  7003  7003 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-01 11:16:24.899  7003  7003 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-01 11:16:24.900  6920  7407 E BluetoothAdapterService: File transfer profiles supported!!
,09-01 11:16:24.905  6920  6920 D LgDataFeature: LgDataFeature() Constructor: none
09-01 11:16:24.905  6920  6920 D LgDataFeature: LgDataFeature() Constructor Done, null
09-01 11:16:24.908  7003  7003 I AppUp4:CustModeStarterReceiver: onReceive
09-01 11:16:24.911  6920  6920 D HeadsetStateMachine: max_hf_connections = 1
09-01 11:16:24.911  6920  6920 I bluedroid-qcom: get_profile_interface handsfree
09-01 11:16:24.912  7003  7003 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1ac480b1
09-01 11:16:24.912  7003  7003 D AppUp4:CustFacade: isCustomizationCompleted : false
09-01 11:16:24.912  7003  7003 D AppUp4:CustFacade: isPhone : true
,09-01 11:16:24.913  6920  6920 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
09-01 11:16:24.913  7003  7003 D AppUp4:CustModeStarterReceiver: begin check event
09-01 11:16:24.913  6920  7407 E BluetoothAdapterService: File transfer profiles supported!!
09-01 11:16:24.914   313  2203 V AudioPolicyService: registerClient() client 0xb57ccce0, uid 1002
09-01 11:16:24.914   313  1385 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
09-01 11:16:24.914   313  1385 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-01 11:16:24.914   313  1385 V AudioPolicyManagerEx: getOutput() returns output 2
09-01 11:16:24.914  6920  6920 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
09-01 11:16:24.915   313  1386 V AudioFlinger: registerClient() client 0xb55814f0, pid 6920
09-01 11:16:24.915   313  1381 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-01 11:16:24.915   313  1381 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-01 11:16:24.916  6920  6935 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-01 11:16:24.916  1602  2066 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-01 11:16:24.916  1602  2066 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-01 11:16:24.916  1850  1865 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-01 11:16:24.916  1850  1865 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-01 11:16:24.916  1034  1779 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-01 11:16:24.916  1034  1779 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-01 11:16:24.916  3463  3479 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-01 11:16:24.916  3463  3479 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-01 11:16:24.916  6920  6920 V ToneGenerator: Create Track: 0xb4928080
09-01 11:16:24.916  6920  6920 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
09-01 11:16:24.916  6920  6935 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
09-01 11:16:24.916  6920  6920 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
09-01 11:16:24.916   313  1380 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-01 11:16:24.916   313  2203 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-01 11:16:24.916   313  1380 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-01 11:16:24.916   313  2203 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
09-01 11:16:24.916   313  2203 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-01 11:16:24.916   313  2203 V AudioPolicyManagerEx: getOutput() returns output 2
09-01 11:16:24.917  6920  7428 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-01 11:16:24.917  6920  7428 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
09-01 11:16:24.917  1602  1623 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-01 11:16:24.917  1602  1623 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-01 11:16:24.917  1034  1574 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-01 11:16:24.917  3463  3483 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-01 11:16:24.917  1034  1574 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-01 11:16:24.917  3463  3483 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-01 11:16:24.917  1850  4447 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-01 11:16:24.917  1850  4447 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-01 11:16:24.918   313  1385 I AudioFlinger: isAudioPlaybackHook,On() false
09-01 11:16:24.918   313  1386 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-01 11:16:24.918   313  1386 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
09-01 11:16:24.918   313  1386 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-01 11:16:24.918   313  1386 V AudioPolicyManagerEx: getOutput() returns output 2
09-01 11:16:24.918  6920  6920 V AudioSystem: getLatency() output 2, latency 50
09-01 11:16:24.918  6920  6920 V AudioSystem: getFrameCount() output 2, frameCount 960
09-01 11:16:24.918  6920  6920 V AudioTrack: createTrack_l() output 2 afLatency 50
09-01 11:16:24.918   313  2202 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-01 11:16:24.918   313  2202 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-01 11:16:24.918   313  2202 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-01 11:16:24.918   313  2202 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-01 11:16:24.918   313  2202 V AudioFlinger: createTrack() lSessionId: 22
09-01 11:16:24.919  6920  6920 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
09-01 11:16:24.919  7003  7003 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-01 11:16:24.920   313  2202 V AudioFlinger: acquiring 22 from 6920, for 6920
09-01 11:16:24.920   313  2202 V AudioFlinger:  added new entry for 22
09-01 11:16:24.920  6920  6920 V ToneGenerator: ToneGenerator INIT OK, time: 188492
09-01 11:16:24.920  6920  6920 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15e15917
09-01 11:16:24.921  6920  7440 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
09-01 11:16:24.921  6920  7440 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-01 11:16:24.921  6920  7440 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-01 11:16:24.921  6920  7440 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
09-01 11:16:24.921   313  2203 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6920
09-01 11:16:24.921  6920  6920 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15e15917
09-01 11:16:24.923  6920  6920 D A2dpService: Received start request. Starting profile...
09-01 11:16:24.923   313  2203 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
09-01 11:16:24.923   313  2203 V voice   : voice_set_parameters: enter: bt_samplerate=8000
09-01 11:16:24.923   313  2203 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
09-01 11:16:24.923   313  2203 V compress_voip: voice_extn_compress_voip_set_parameters: exit
09-01 11:16:24.923   313  2203 V voice   : voice_set_parameters: exit with code(0)
09-01 11:16:24.923   313  2203 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
09-01 11:16:24.923   313  2203 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
09-01 11:16:24.923   313  2203 V msm8974_platform: platform_set_parameters: exit with code(0)
09-01 11:16:24.923  6920  6920 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-01 11:16:24.923   313  2203 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
09-01 11:16:24.924   313  2203 V audio_hw_primary: adev_set_parameters: exit with code(0)
09-01 11:16:24.924   313  2203 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
09-01 11:16:24.924  6920  7440 V ToneGenerator: ToneGenerator destructor
09-01 11:16:24.924  6920  7440 V ToneGenerator: stopTone
09-01 11:16:24.924  6920  7440 V ToneGenerator: Delete Track: 0xb4928080
09-01 11:16:24.924  6920  6920 V Avrcp   : make
09-01 11:16:24.925  6920  6920 D Avrcp   : [BTUI] Use Native AVRCP : init jni
09-01 11:16:24.925  6920  6920 I bluedroid-qcom: get_profile_interface avrcp
09-01 11:16:24.926  4322  4322 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-01 11:16:24.926  4322  4322 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-01 11:16:24.928  6920  7440 V AudioTrack: ~AudioTrack, releasing session id from 6920 on behalf of 6920
09-01 11:16:24.928   313   313 V AudioFlinger: releasing 22 from 6920 for 6920
09-01 11:16:24.928   313   313 V AudioFlinger:  decremented refcount to 0
09-01 11:16:24.928   313   313 V AudioFlinger: purging stale effects
09-01 11:16:24.929   313   313 V AudioPolicyService: AudioCommandThread() adding release output 2
09-01 11:16:24.929   313   313 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
09-01 11:16:24.929   313  1258 V AudioPolicyService: AudioCommandThread() waking up
09-01 11:16:24.929   313  1258 V AudioPolicyService: AudioCommandThread() processing release output 2
09-01 11:16:24.929   313  1258 V AudioPolicyManager: releaseOutput() 2
09-01 11:16:24.929   313  1258 V AudioPolicyService: AudioCommandThread() going to sleep
09-01 11:16:24.929   313   313 V AudioFlinger: PlaybackThread::Track destructor
09-01 11:16:24.929   313   313 V AudioFlinger: removeClient_l() pid 6920, calling pid 313
09-01 11:16:24.931  4322  4322 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-01 11:16:24.931  6920  6920 V AudioManager: registerRemoteController: size of Media player list: 0
09-01 11:16:24.933  6920  6920 E AudioManager: No RCC entry present to update
09-01 11:16:24.933  6920  6920 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-01 11:16:24.933  4322  4322 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-01 11:16:24.935  6920  7407 V LGMDMManager: Create singleton instance
09-01 11:16:24.936  6920  6920 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
09-01 11:16:24.937  6920  7407 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
09-01 11:16:24.937  6920  6920 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
09-01 11:16:24.937  6920  6920 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
09-01 11:16:24.939  4322  7452 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-01 11:16:24.941  6920  6920 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
09-01 11:16:24.942  7033  7033 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,09-01 11:16:24.947  4322  7454 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-01 11:16:24.947  4322  7454 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-01 11:16:25.005  3463  3463 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-01 11:16:25.005  3463  3463 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-01 11:16:25.005  3463  3463 I LgeMiscReceiver: networkInfo.isConnected() = false
09-01 11:16:25.006  7033  7455 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-01 11:16:25.010  7079  7079 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-01 11:16:25.010  7079  7079 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-01 11:16:25.012  6937  7457 W FormManager: Network not available. Please check & try again.
09-01 11:16:25.016  6937  7458 V FormManager: Network unavailable.
09-01 11:16:25.018  6937  7458 V FormManager: Network unavailable.
09-01 11:16:25.029  7138  7138 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:16:25
,09-01 11:16:25.032  7138  7138 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-01 11:16:25.032  7138  7138 D Weather.Utils: 2 : All the weather widget is gone.
09-01 11:16:25.032  7138  7138 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-01 11:16:25.033  7138  7138 D WeatherAncestor: connectivity changed - connection : true
09-01 11:16:25.033  7138  7138 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@15e15917
09-01 11:16:25.033  7138  7138 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-01 11:16:25.033  7138  7138 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-01 11:16:25.034  7138  7138 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-01 11:16:25.034  7138  7138 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-01 11:16:25.034  7138  7138 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:16:25
,09-01 11:16:25.044  1034  1923 V SIM_STK : Menu title from STK is T-Mobile
09-01 11:16:25.044  1034  1923 V SIM_STK : Menu title from STK is T-Mobile
09-01 11:16:25.046  7430  7430 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
09-01 11:16:25.046  7430  7430 W LG Account v2.2: No ProfileInfo entries
09-01 11:16:25.046  7430  7430 I LG Account v2.2: isEnabled: false
09-01 11:16:25.046  7430  7430 I Feature : [Lifetracker]ver: 4.21.112(40211120)
09-01 11:16:25.046  7430  7430 I Feature : [Lifetracker]Country: EU
09-01 11:16:25.047  7430  7430 I Feature : [Lifetracker]Operator: OPEN
09-01 11:16:25.047  7430  7430 I Feature : [Lifetracker]Ranking support: false
09-01 11:16:25.047  7430  7430 I Feature : [Lifetracker]Comfort support: false
09-01 11:16:25.047  7430  7430 I Feature : [Lifetracker]Accessory: true
09-01 11:16:25.047  7430  7430 I Feature : [Lifetracker]Health device: true
09-01 11:16:25.047  7430  7430 I Feature : [Lifetracker]Extra Pedometer: false
09-01 11:16:25.047  7430  7430 I Feature : [Lifetracker]Blood glucose device: false
09-01 11:16:25.047  7430  7430 I Feature : [Lifetracker]Device Number: 3
,09-01 11:16:25.061  6814  6814 D BluetoothPermissionRequest: onReceive
,09-01 11:16:25.065  6814  6814 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-01 11:16:25.065  6350  6350 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-01 11:16:25.066  6350  6833 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-01 11:16:25.076  2180  2180 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-01 11:16:25.084  7003  7003 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-01 11:16:25.084  7003  7003 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-01 11:16:25.084  7003  7003 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
,09-01 11:16:25.084  7003  7003 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-01 11:16:25.085  7003  7003 I AppUp4:CustModeStarterReceiver: onReceive
,09-01 11:16:25.089  7003  7003 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1ac480b1
09-01 11:16:25.089  7003  7003 D AppUp4:CustFacade: isCustomizationCompleted : false
09-01 11:16:25.089  7003  7003 D AppUp4:CustFacade: isPhone : true
09-01 11:16:25.090  7003  7003 D AppUp4:CustModeStarterReceiver: begin check event
09-01 11:16:25.090  7003  7003 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
,09-01 11:16:25.092  4322  4322 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-01 11:16:25.092  4322  4322 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-01 11:16:25.094  4322  4322 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-01 11:16:25.095  4322  4322 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-01 11:16:25.100  4322  7462 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-01 11:16:25.101  7033  7033 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
09-01 11:16:25.103  4322  7463 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-01 11:16:25.104  4322  7463 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-01 11:16:25.120  3463  3463 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-01 11:16:25.120  3463  3463 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
,09-01 11:16:25.120  3463  3463 I LgeMiscReceiver: networkInfo.isConnected() = false
,09-01 11:16:25.126  7079  7079 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-01 11:16:25.126  7079  7079 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-01 11:16:25.127  7033  7467 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:16:25.129  6937  7466 W FormManager: Network not available. Please check & try again.
09-01 11:16:25.133  1034  2022 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,09-01 11:16:25.140  6920  6920 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
09-01 11:16:25.144  6920  6920 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-01 11:16:25.144  7138  7138 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:16:25
09-01 11:16:25.144  6920  6920 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-01 11:16:25.145  6920  6920 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
,09-01 11:16:25.145  6920  6920 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-01 11:16:25.145  6920  6920 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-01 11:16:25.145  6920  6920 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-01 11:16:25.145  6920  6920 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-01 11:16:25.145  6920  6920 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-01 11:16:25.145  6920  6920 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-01 11:16:25.145  6920  6920 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-01 11:16:25.145  6937  7468 V FormManager: Network unavailable.
09-01 11:16:25.145  6920  6920 I BluetoothA2dpServiceJni: classInitNative
09-01 11:16:25.145  6920  6920 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-01 11:16:25.145  6920  6920 D A2dpStateMachine: make
09-01 11:16:25.147  6920  6920 I bluedroid-qcom: get_profile_interface a2dp
09-01 11:16:25.147  6920  7470 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,09-01 11:16:25.149  7138  7138 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-01 11:16:25.149  7138  7138 D Weather.Utils: 2 : All the weather widget is gone.
09-01 11:16:25.150  7138  7138 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-01 11:16:25.150  7138  7138 D WeatherAncestor: connectivity changed - connection : true
09-01 11:16:25.150  7138  7138 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@15e15917
09-01 11:16:25.150  6920  6920 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
09-01 11:16:25.150  6920  6920 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
09-01 11:16:25.151  7138  7138 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-01 11:16:25.151  7138  7138 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-01 11:16:25.151  7138  7138 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-01 11:16:25.151  7138  7138 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-01 11:16:25.152  6920  6920 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15e15917
09-01 11:16:25.152  6920  7469 D A2dpStateMachine: Enter Disconnected: -2
09-01 11:16:25.152  7138  7138 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:16:25
09-01 11:16:25.152  6937  7468 V FormManager: Network unavailable.
09-01 11:16:25.155  6920  6920 I BluetoothHidServiceJni: classInitNative: succeeds
09-01 11:16:25.157  6920  6920 D HidService: Received start request. Starting profile...
09-01 11:16:25.158  6920  6920 I bluedroid-qcom: get_profile_interface hidhost
09-01 11:16:25.158  6920  6920 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15e15917
09-01 11:16:25.158  6920  6920 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-01 11:16:25.160  6920  6920 D HealthService: Received start request. Starting profile...
09-01 11:16:25.162  6920  6920 I bluedroid-qcom: get_profile_interface health
09-01 11:16:25.162  6920  6920 I LGBluetoothHealthServiceJni: classInitNative: succeeds
09-01 11:16:25.162  6920  6920 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15e15917
09-01 11:16:25.163  6920  6920 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-01 11:16:25.164  6920  6920 D PanService: Received start request. Starting profile...
09-01 11:16:25.164  6920  6920 D BluetoothPanServiceJni: initializeNative(L110): pan
09-01 11:16:25.164  6920  6920 I bluedroid-qcom: get_profile_interface pan
09-01 11:16:25.169  6920  6920 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
09-01 11:16:25.169  6920  6920 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15e15917
09-01 11:16:25.170  6920  6920 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
09-01 11:16:25.174  6920  6920 D BtGatt.DebugUtils: handleDebugAction() action=null
09-01 11:16:25.174  6920  6920 D BtGatt.GattService: Received start request. Starting profile...
09-01 11:16:25.174  6920  6920 D BtGatt.GattService: start()
09-01 11:16:25.174  6920  6920 I bluedroid-qcom: get_profile_interface gatt
09-01 11:16:25.174  6920  6920 D BtGatt.AdvertiseManager: advertise manager created
,09-01 11:16:25.179  6920  6920 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15e15917
09-01 11:16:25.179  6920  6920 D HeadsetStateMachine: Proxy object connected
09-01 11:16:25.180  6920  6920 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
09-01 11:16:25.180  6920  6920 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
09-01 11:16:25.182  6920  6920 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15e15917
09-01 11:16:25.182  6920  6920 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
09-01 11:16:25.183  6920  6920 V BluetoothMapService: BluetoothMapBinder()
09-01 11:16:25.184  6920  6920 D BluetoothMapService: Received start request. Starting profile...
09-01 11:16:25.184  6920  6920 D BluetoothMapService: start()
09-01 11:16:25.187  6920  6920 D BluetoothMapEmailSettingsLoader: Found 0 applications
09-01 11:16:25.187  6920  6920 D BluetoothMapEmailAppObserver: createReceiver()
09-01 11:16:25.188  6920  6920 D BluetoothMapEmailAppObserver: initObservers()
09-01 11:16:25.188  6920  6920 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
,09-01 11:16:25.194  6920  6920 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15e15917
09-01 11:16:25.197  6920  6920 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-01 11:16:25.198  6920  7440 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-01 11:16:25.198  6920  7440 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-01 11:16:25.199  6920  7440 D HeadsetStateMachine: Disconnected process message: 11, size: 0
,09-01 11:16:25.202  6920  6920 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-01 11:16:25.205  6920  6920 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-01 11:16:25.208  6920  6920 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-01 11:16:25.209  6920  6920 V PanService: [BTUI] SIM Extra State :ABSENT
09-01 11:16:25.212  6920  6920 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,09-01 11:16:25.216  6920  6920 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
09-01 11:16:25.216  6920  6920 V BluetoothMapService: Handler(): got msg=1
09-01 11:16:25.217  6920  7407 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
09-01 11:16:25.217  6920  7407 I bluedroid-qcom: enable
09-01 11:16:25.218  6920  7477 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
09-01 11:16:25.218  6920  7477 I bt-btu  : btu_task pending for preload complete event
09-01 11:16:25.219  6920  7407 I bt_hci_bdroid: init
09-01 11:16:25.222  6920  7407 I bt_vendor: bt-vendor : init
09-01 11:16:25.222  6920  7407 I bt_vendor: bt-vendor : get_bt_soc_type
09-01 11:16:25.222  6920  7407 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-01 11:16:25.222  6920  7407 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
09-01 11:16:25.222  6920  7407 D bt_userial_mct: userial_init
09-01 11:16:25.222  6920  6920 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:16:25.222  6920  7407 D bt_hci_bdroid: set_power 1
09-01 11:16:25.222  6920  7407 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-01 11:16:25.223  6920  7407 I bt_vendor: Starting hciattach daemon
09-01 11:16:25.223  6920  7407 I bt_vendor: try to set true
09-01 11:16:25.224  6920  6920 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-01 11:16:25.224  6920  6920 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-01 11:16:25.224  6920  6920 V BluetoothSapReceiver: SapReceiver onReceive 
09-01 11:16:25.225  6920  6920 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:16:25.225  6920  6920 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
,09-01 11:16:25.208  7480  7480 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-01 11:16:25.208  7480  7480 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-01 11:16:25.275  7481  7481 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,09-01 11:16:25.361  7487  7487 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,09-01 11:16:25.384  7488  7488 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-01 11:16:25.426  7490  7490 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-01 11:16:25.447  7491  7491 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,09-01 11:16:25.464  7495  7495 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-01 11:16:25.477  7496  7496 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
09-01 11:16:25.500  7498  7498 I libmdmdetect: ESOC framework not supported
09-01 11:16:25.501  7498  7498 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,09-01 11:16:25.509  7498  7498 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,09-01 11:16:25.509  7498  7498 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
09-01 11:16:25.509  7498  7498 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
09-01 11:16:25.509  7498  7498 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
09-01 11:16:25.509  7498  7498 D bthci_qcomm_common: [BTUI]     LE: Class 2
09-01 11:16:25.509  7498  7498 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
09-01 11:16:25.509  7498  7498 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
09-01 11:16:25.544  7498  7499 E QC-QMI  : qmi_client [7498] 14: failed to locate client data
09-01 11:16:25.545   448   448 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
09-01 11:16:25.546   448   448 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
,09-01 11:16:25.578  7500  7500 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,09-01 11:16:25.596  7501  7501 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-01 11:16:25.626  6920  7407 I bt_vendor: bluetooth satus is on
09-01 11:16:25.626  6920  7407 D bt_hci_bdroid: preload
09-01 11:16:25.626  6920  7479 D bt_userial_mct: userial_open(port:0)
,09-01 11:16:25.626  6920  7479 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
09-01 11:16:25.627  1034  1092 W ProcessCpuTracker: Skipping unknown process pid 7480
,09-01 11:16:25.627  1034  1092 W ProcessCpuTracker: Skipping unknown process pid 7501
09-01 11:16:25.629  6920  7479 I bt_vendor: Done intiailizing UART
09-01 11:16:25.630  6920  7479 I bt_vendor: Done intiailizing UART
09-01 11:16:25.630  6920  7479 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
09-01 11:16:25.630  6920  7479 I bt_vendor: Bluetooth Firmware and transport layer are initialized
09-01 11:16:25.630  6920  7503 D bt_userial_mct: Entering userial_read_thread()
09-01 11:16:25.631  6920  7477 I bt-btu  : btu_task received preload complete event
09-01 11:16:25.631  6920  7477 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
09-01 11:16:25.631  6920  7477 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
09-01 11:16:25.633  6920  7477 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
09-01 11:16:25.637  6920  7477 I         : BTE_InitTraceLevels -- TRC_HCI
09-01 11:16:25.637  6920  7477 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-01 11:16:25.637  6920  7477 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-01 11:16:25.637  6920  7477 I         : BTE_InitTraceLevels -- TRC_AVDT
09-01 11:16:25.637  6920  7477 I         : BTE_InitTraceLevels -- TRC_AVRC
09-01 11:16:25.637  6920  7477 I         : BTE_InitTraceLevels -- TRC_A2D
09-01 11:16:25.637  6920  7477 I         : BTE_InitTraceLevels -- TRC_BNEP
09-01 11:16:25.637  6920  7477 I         : BTE_InitTraceLevels -- TRC_BTM
09-01 11:16:25.637  6920  7477 I         : BTE_InitTraceLevels -- TRC_HID_HOST
09-01 11:16:25.637  6920  7477 I         : BTE_InitTraceLevels -- TRC_GAP
09-01 11:16:25.637  6920  7477 I         : BTE_InitTraceLevels -- TRC_PAN
09-01 11:16:25.637  6920  7477 I         : BTE_InitTraceLevels -- TRC_SDP
09-01 11:16:25.637  6920  7477 I         : BTE_InitTraceLevels -- TRC_GATT
09-01 11:16:25.637  6920  7477 I         : BTE_InitTraceLevels -- TRC_SMP
09-01 11:16:25.637  6920  7477 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-01 11:16:25.637  6920  7477 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-01 11:16:25.714  6920  7477 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
09-01 11:16:25.714  6920  7477 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0234061 
09-01 11:16:25.715  6920  7477 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0234061 
,09-01 11:16:25.767  6920  7411 E bt-btif : Calling BTA_HhEnable
09-01 11:16:25.767  6920  7411 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
,09-01 11:16:25.773  6920  7411 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
09-01 11:16:25.775  6920  7477 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
09-01 11:16:25.775  6920  7477 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
09-01 11:16:25.776  6920  7477 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
09-01 11:16:25.777  6920  7477 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
09-01 11:16:25.777  6920  7477 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
09-01 11:16:25.779  1034  1034 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-01 11:16:25.779  6920  7411 D BluetoothAdapterProperties: Name is: G3
09-01 11:16:25.780  1034  1034 D BluetoothManagerService: Stored Bluetooth name: G3
09-01 11:16:25.781  6920  7411 D BluetoothAdapterProperties: Scan Mode:20
,09-01 11:16:25.781  6920  7411 D BluetoothAdapterProperties: Discoverable Timeout:120
09-01 11:16:25.782  6920  7411 D bt_hci_bdroid: postload
09-01 11:16:25.783  6920  7411 D bte_conf: Device ID record 1 : primary
,09-01 11:16:25.783  6920  7411 D bte_conf:   vendorId            = 00c4
09-01 11:16:25.783  6920  7411 D bte_conf:   vendorIdSource      = 0001
09-01 11:16:25.783  6920  7411 D bte_conf:   product             = 13a1
09-01 11:16:25.783  6920  7411 D bte_conf:   version             = 1000
09-01 11:16:25.783  6920  7411 D bte_conf:   clientExecutableURL = 
09-01 11:16:25.783  6920  7411 D bte_conf:   serviceDescription  = 
09-01 11:16:25.783  6920  7411 D bte_conf:   documentationURL    = 
09-01 11:16:25.783  6920  7411 D bte_conf: bte_load_did_conf no section named DID2.
09-01 11:16:25.785  6920  7479 D bt_hci_bdroid: Used up Tx Cmd credits
09-01 11:16:25.785  6920  7477 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
09-01 11:16:25.787  6920  7407 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-01 11:16:25.787  6920  7407 D BluetoothAdapterProperties: ScanMode =  20
09-01 11:16:25.787  6920  7407 D BluetoothAdapterProperties: State =  11
09-01 11:16:25.787  6920  7407 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
09-01 11:16:25.778  7508  7508 W sh      : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-01 11:16:25.789  6920  7407 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
09-01 11:16:25.790  6920  7407 D BluetoothAdapterProperties: Setting state to 12
09-01 11:16:25.790  6920  7407 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-01 11:16:25.778  7508  7508 W sh      : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-01 11:16:25.790  6920  7411 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-01 11:16:25.790  1034  1096 D BluetoothManagerService: Message: 60
09-01 11:16:25.790  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
09-01 11:16:25.790  1034  1096 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
09-01 11:16:25.791  6920  7411 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-01 11:16:25.800  6920  7479 D bt_hci_bdroid: Used up Tx Cmd credits
,09-01 11:16:25.805  6920  7407 I BluetoothAdapterState: Entering On State
09-01 11:16:25.810  6920  7407 D LGBluetoothServiceAdapter: [BTUI] OnState
09-01 11:16:25.810  6920  7407 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
09-01 11:16:25.810  6920  7407 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
09-01 11:16:25.811  6920  7407 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
09-01 11:16:25.813  6920  7503 E bt_mct  : hci lib postload completed
09-01 11:16:25.813  1850  4446 D BluetoothHeadset: onBluetoothStateChange: up=true
09-01 11:16:25.818  6920  7411 D BluetoothAdapterProperties: Discoverable Timeout:120
09-01 11:16:25.818  6920  7411 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
09-01 11:16:25.820  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:16:25.820  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:16:25.820  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-01 11:16:25.820  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 11:16:25.820  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:16:25.820  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:16:25.820  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:16:25.820  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 11:16:25.822  6920  7477 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-01 11:16:25.822  6920  7477 W bt-smp  : Plain text(LSB ~ MSB) = 97 ed 49 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-01 11:16:25.822  6920  7477 W bt-smp  : Encrypted text(LSB ~ MSB) = af 40 45 e7 1a bd b5 e8 14 d3 cc bf 5c 03 49 17 
09-01 11:16:25.822  6920  7477 W bt-btm  : Stopping oneshot timer
09-01 11:16:25.823  6682  6682 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-01 11:16:25.830  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:16:25.830  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:16:25.830  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-01 11:16:25.830  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 11:16:25.830  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:16:25.830  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:16:25.830  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:16:25.830  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 11:16:25.832  6682  6682 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-01 11:16:25.835  1850  1850 D BluetoothHeadset: Proxy object connected
09-01 11:16:25.836  1850  2452 D BluetoothHeadset: onBluetoothStateChange: up=true
09-01 11:16:25.838  1850  1850 D BluetoothHeadset: Proxy object connected
,09-01 11:16:25.840  1034  1096 D BluetoothHeadset: onBluetoothStateChange: up=true
09-01 11:16:25.848  6920  7477 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-01 11:16:25.849  6920  7477 W bt-smp  : Plain text(LSB ~ MSB) = da 83 57 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-01 11:16:25.849  6920  7477 W bt-smp  : Encrypted text(LSB ~ MSB) = 71 fa 81 30 a2 06 a4 00 5e d7 b5 ca c4 a0 d6 1c 
09-01 11:16:25.849  6920  7477 W bt-btm  : Stopping oneshot timer
09-01 11:16:25.852  1034  1034 D BluetoothHeadset: Proxy object connected
,09-01 11:16:25.856  6814  6829 D BluetoothPan: onBluetoothStateChange on: true
09-01 11:16:25.856  6814  6829 D BluetoothPan: onBluetoothStateChange call bindService
09-01 11:16:25.863  1034  1096 D BluetoothA2dp: onBluetoothStateChange: up=true
09-01 11:16:25.863  7513  7513 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
09-01 11:16:25.864  6920  7407 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
,09-01 11:16:25.866  6920  7477 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-01 11:16:25.866  6920  7477 W bt-smp  : Plain text(LSB ~ MSB) = 92 ba 4e 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-01 11:16:25.866  6920  7477 W bt-smp  : Encrypted text(LSB ~ MSB) = 80 14 9c e9 36 e1 8c 85 f4 87 7b b3 31 ca a6 b0 
09-01 11:16:25.867  6920  7477 W bt-btm  : Stopping oneshot timer
09-01 11:16:25.869  1034  1034 D BluetoothA2dp: Proxy object connected
09-01 11:16:25.875  1850  4447 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-01 11:16:25.879  1850  1850 D BluetoothHeadset: Proxy object connected
09-01 11:16:25.880  6814  6830 D BluetoothPbap: onBluetoothStateChange: up=true
,09-01 11:16:25.880  6814  6814 D BluetoothPan: BluetoothPAN Proxy object connected
09-01 11:16:25.880  6814  6814 D PanProfile: Bluetooth service connected
09-01 11:16:25.883  6814  7514 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-01 11:16:25.883  6920  7477 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-01 11:16:25.883  6920  7477 W bt-smp  : Plain text(LSB ~ MSB) = 74 13 6e 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-01 11:16:25.883  6920  7477 W bt-smp  : Encrypted text(LSB ~ MSB) = 09 d2 67 44 9d 56 28 a6 5d dd 63 8d e3 86 d5 7a 
09-01 11:16:25.884  6920  7477 W bt-btm  : Stopping oneshot timer
09-01 11:16:25.888  6814  6829 D BluetoothMap: onBluetoothStateChange: up=true
,09-01 11:16:25.892  6814  6814 D BluetoothInputDevice: Proxy object connected
09-01 11:16:25.892  6814  6814 D HidProfile: Bluetooth service connected
09-01 11:16:25.895  1034  1096 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
09-01 11:16:25.895  1034  1096 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
09-01 11:16:25.896  6814  6814 D BluetoothMap: Proxy object connected
09-01 11:16:25.896  6814  6814 D MapProfile: Bluetooth service connected
09-01 11:16:25.896  6814  6814 D BluetoothMap: getConnectedDevices()
09-01 11:16:25.897  1034  1034 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
09-01 11:16:25.897  1939  1939 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:16:25.897  1034  1096 D BluetoothManagerService: Message: 40
09-01 11:16:25.897  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
09-01 11:16:25.897  1939  2084 D LGBluetoothAPIService: Message: 1
09-01 11:16:25.897  1939  2084 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
09-01 11:16:25.899  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-01 11:16:25.900  6920  7477 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-01 11:16:25.900  6920  7477 W bt-smp  : Plain text(LSB ~ MSB) = d9 2e 5f 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-01 11:16:25.900  6920  7477 W bt-smp  : Encrypted text(LSB ~ MSB) = 1d c4 61 f2 42 25 4b 34 fe 66 40 a6 8a 5b a3 c5 
09-01 11:16:25.900  6920  7477 W bt-btm  : Stopping oneshot timer
09-01 11:16:25.901  6920  6936 V BluetoothMapService: getConnectedDevices()
,09-01 11:16:25.906  6682  6682 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
09-01 11:16:25.910  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:16:25.911  1939  2084 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
09-01 11:16:25.912  6920  6920 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:16:25.912  6920  6920 D BluetoothMapService: STATE_ON
09-01 11:16:25.914  6920  6920 D LGBluetoothAPIServer: [BTUI] onCreate()
,09-01 11:16:25.914  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:16:25.914  6920  6920 D LGBluetoothAPIServer: [BTUI] onBind()
09-01 11:16:25.916  1939  1939 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
09-01 11:16:25.916  1939  2084 D LGBluetoothAPIService: Message: 100
09-01 11:16:25.916  1939  2084 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
09-01 11:16:25.919  6814  6814 D LocalBluetoothProfileManager: Adding local A2DP profile
09-01 11:16:25.921  1034  1096 D BluetoothManagerService: Message: 30
09-01 11:16:25.926  6814  6814 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-01 11:16:25.926  7177  7213 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,09-01 11:16:25.929  1034  1096 D BluetoothManagerService: Message: 30
09-01 11:16:25.933  6920  6920 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15e15917
09-01 11:16:25.933  6814  6814 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
09-01 11:16:25.933  6920  6920 V BluetoothPbapService: Pbap Service onCreate
09-01 11:16:25.933  6920  6920 V BluetoothPbapService: Starting PBAP service
09-01 11:16:25.934  6814  6814 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-01 11:16:25.934  6920  6920 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
09-01 11:16:25.934  6920  6920 V BluetoothMapService: Handler(): got msg=1
09-01 11:16:25.935  6920  6920 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
09-01 11:16:25.936  6920  6920 V BluetoothPbapService: Pbap Service onBind
09-01 11:16:25.937  6920  6920 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:16:25.937  6920  6920 V BluetoothPbapService: state: 12
09-01 11:16:25.937  6920  6920 V BluetoothPbapService: Handler(): got msg=1
09-01 11:16:25.937  6920  7529 D BluetoothMapMasInstance: MAS initSocket()
09-01 11:16:25.937  6920  6920 V BluetoothPbapService: Pbap Service startRfcommSocketListener
09-01 11:16:25.938  6920  7529 D BluetoothMapMasInstance:   masId = 00
09-01 11:16:25.938  6920  7529 D BluetoothMapMasInstance:   msgTypes = 0e
09-01 11:16:25.938  6920  7529 D BluetoothMapMasInstance:   masName = SMS/MMS
09-01 11:16:25.938  6920  7529 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
,09-01 11:16:25.939  6814  6814 D BluetoothA2dp: Proxy object connected
09-01 11:16:25.939  6814  6814 D A2dpProfile: Bluetooth service connected
09-01 11:16:25.940  6920  6920 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-01 11:16:25.940  6920  6920 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:16:25.940  6920  6920 V BluetoothPbapReceiver: ***********state = 12
09-01 11:16:25.943  6814  6814 D BluetoothHeadset: Proxy object connected
09-01 11:16:25.943  2180  2180 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-01 11:16:25.943  2180  2180 D c       : Getting all permits...
09-01 11:16:25.943  2180  2180 D a       : Opening database...
09-01 11:16:25.943  6814  6814 D HeadsetProfile: Bluetooth service connected
09-01 11:16:25.945  1034  1952 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:16:25.946  6920  7529 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-01 11:16:25.946  6920  7530 V BluetoothPbapService: Pbap Service initSocket
09-01 11:16:25.946  6920  7529 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
09-01 11:16:25.947  2180  2180 D a       : Opening database auth.proximity.permit_store...
09-01 11:16:25.947  6920  7529 V BluetoothMapMasInstance: Succeed to create listening socket 
09-01 11:16:25.947  6920  7529 D BluetoothMapMasInstance: Accepting socket connection...
09-01 11:16:25.947  6920  7411 D BluetoothAdapterProperties: Scan Mode:21
09-01 11:16:25.947  6920  7411 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
09-01 11:16:25.947  2180  2180 D a       : Closing database...
09-01 11:16:25.949  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:16:25.950  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:16:25.951  1034  1987 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:16:25.953  6920  7530 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-01 11:16:25.956  6920  7530 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
09-01 11:16:25.956  6920  7530 V BluetoothPbapService: Succeed to create listening socket 
09-01 11:16:25.956  6920  7530 V BluetoothPbapService: Accepting socket connection...
09-01 11:16:25.959  6814  6814 D DockEventReceiver: finishStartingService: stopping service
09-01 11:16:25.960  6814  6814 D BluetoothPbap: Proxy object connected
,09-01 11:16:25.961  6814  6814 D PbapServerProfile: Bluetooth service connected
09-01 11:16:25.964  6814  6814 D BluetoothPermissionRequest: onReceive
09-01 11:16:25.965  6814  6814 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-01 11:16:25.967  6814  6814 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-01 11:16:25.969  6920  6920 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
09-01 11:16:25.970  6920  6920 I LGBluetoothOppAdapter: [BTUI] startOppService()
09-01 11:16:25.975  6920  6920 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,09-01 11:16:25.991  6920  6920 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-01 11:16:25.991  6920  6920 V BtOppService: onCreate
,09-01 11:16:25.996  6920  6920 V BluetoothOppNotification: send message
09-01 11:16:25.998  6920  6920 V BtOppService: Starting RfcommListener
09-01 11:16:26.001  6920  6920 D BluetoothOppPreference: Dumping Names:  
09-01 11:16:26.001  6920  6920 D BluetoothOppPreference: {}
09-01 11:16:26.001  6920  6920 D BluetoothOppPreference: Dumping Channels:  
09-01 11:16:26.001  6920  6920 D BluetoothOppPreference: {}
09-01 11:16:26.002  6920  6920 V BtOppService: onStartCommand
09-01 11:16:26.003  6920  7538 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-01 11:16:26.005  6920  6920 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:16:26.005  6920  6920 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,09-01 11:16:26.009  6920  6920 V BluetoothOppNotification: new notify threadi!
,09-01 11:16:26.010  6920  6920 V BluetoothOppNotification: send delay message
09-01 11:16:26.010  6920  6920 V BtOppService: start RfcommListener
09-01 11:16:26.013  6920  6920 V BtOppService: RfcommListener started
09-01 11:16:26.014  6920  7540 V BtOppRfcommListener: Starting RFCOMM listener....
09-01 11:16:26.015  1034  1049 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:16:26.016  6920  7540 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-01 11:16:26.018  6920  7540 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
09-01 11:16:26.019  6920  7540 V BtOppRfcommListener: Started RFCOMM listener....
,09-01 11:16:26.019  6920  7540 I BtOppRfcommListener: Accept thread started.
09-01 11:16:26.019  6920  7540 V BtOppRfcommListener: Accepting connection...
09-01 11:16:26.021  6920  7538 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-01 11:16:26.022  6920  7535 V BtOppService: Deleted complete outbound shares, number =  0
09-01 11:16:26.022  6920  7539 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-01 11:16:26.024  6920  7535 V BtOppService: Deleted complete inbound failed shares, number = 0
09-01 11:16:26.025  6920  7535 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
09-01 11:16:26.025  6920  7539 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@109a3d00 on behalf of 
09-01 11:16:26.026  6920  7535 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3e422939 on behalf of 
09-01 11:16:26.026  6920  7539 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-01 11:16:26.026  6920  7538 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@5d11b7e on behalf of 
09-01 11:16:26.029  6920  7538 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-01 11:16:26.029  6920  7538 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-01 11:16:26.030  6920  6920 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15e15917
09-01 11:16:26.030  6920  6920 V BluetoothFtpService: Ftp Service onCreate
09-01 11:16:26.030  6920  7538 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@31dd48df on behalf of 
09-01 11:16:26.030  6920  6920 I BluetoothFtpService: Ftp Service onCreate
,09-01 11:16:26.031  6920  6920 V BluetoothFtpService: Ftp Service onStartCommand
09-01 11:16:26.031  6920  6920 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:16:26.031  6920  6920 V BluetoothFtpService: Starting Listening on sockets
09-01 11:16:26.031  6920  7539 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-01 11:16:26.032  6920  6920 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-01 11:16:26.032  6920  7538 V BluetoothOppNotification: update too frequent, put in queue
09-01 11:16:26.032  6920  6920 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-01 11:16:26.032  6920  6920 V BluetoothSapReceiver: SapReceiver onReceive 
09-01 11:16:26.032  6920  6920 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:16:26.032  6920  6920 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
09-01 11:16:26.032  6920  6920 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-01 11:16:26.033  6920  7538 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-01 11:16:26.035  6920  6920 V BtOppService: ContentObserver received notification
09-01 11:16:26.035  6920  6920 V BtOppService: ContentObserver received notification
09-01 11:16:26.035  6920  7539 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@931ff5 on behalf of 
09-01 11:16:26.035  6920  6920 V BluetoothFtpService: Handler(): got msg=1
09-01 11:16:26.036  6920  6920 V BluetoothFtpService: Ftp Service startRfcommSocketListener
09-01 11:16:26.036  6920  6920 V BluetoothFtpService: Ftp Service initSocket
09-01 11:16:26.038  6920  7541 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-01 11:16:26.038  6920  7539 V BluetoothOppNotification: outbound: succ-0  fail-0
09-01 11:16:26.038  6920  7541 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-01 11:16:26.040  6920  7541 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3edf718a on behalf of 
09-01 11:16:26.040  6920  7539 V BluetoothOppNotification: outbound notification was removed.
09-01 11:16:26.040  6920  7539 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-01 11:16:26.041  6920  7541 V BluetoothOppNotification: update too frequent, put in queue
09-01 11:16:26.042  1034  1574 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:16:26.043  6920  6920 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-01 11:16:26.044  6920  7541 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-01 11:16:26.046  6920  6920 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=78
09-01 11:16:26.046  6920  6920 V BluetoothFtpService: Succeed to create listening socket on channel 20
09-01 11:16:26.048  6920  7542 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
09-01 11:16:26.068  6920  6920 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15e15917
09-01 11:16:26.068  6920  6920 V BluetoothSapService: Sap Service onCreate
09-01 11:16:26.071  6920  6920 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:16:26.071  6920  6920 V BluetoothSapService: state: 12
,09-01 11:16:26.071  6920  6920 V BluetoothSapService: Starting SAP server process
09-01 11:16:26.058  7543  7543 W sapd    : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-01 11:16:26.058  7543  7543 W sapd    : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-01 11:16:26.074  6920  6920 V BluetoothSapService: SAP Service startRfcommListenerThread
09-01 11:16:26.077  6920  7544 V BluetoothSapService: Sap Service initRfcommSocket
09-01 11:16:26.078  1034  1993 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:16:26.079  6920  7544 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-01 11:16:26.081  6920  7544 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
09-01 11:16:26.081  6920  7544 V BluetoothSapService: Succeed to create listening socket 
09-01 11:16:26.081  6920  7544 V BluetoothSapService: Accepting socket connection...
,09-01 11:16:26.085  7543  7543 V BT_SAP  : Event pipe created
09-01 11:16:26.085  7543  7543 V BT_SAP  : create_server_socket qcom.sap.server
09-01 11:16:26.085  7543  7543 V BT_SAP  : created socket fd 6
09-01 11:16:26.162  1034  1050 I art     : Explicit concurrent mark sweep GC freed 92533(4MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 1.807ms total 120.019ms
,09-01 11:16:26.162  1034  1047 I art     : WaitForGcToComplete blocked for 29.122ms for cause HeapTrim
,09-01 11:16:26.162  6920  7539 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@11cb1c56 on behalf of 
09-01 11:16:26.163  6920  7539 V BluetoothOppNotification: inbound: succ-0  fail-0
09-01 11:16:26.164  6920  7539 V BluetoothOppNotification: inbound notification was removed.
09-01 11:16:26.164  6920  7539 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-01 11:16:26.165  6920  7539 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@36a174d7 on behalf of 
09-01 11:16:26.627  1034  1536 D LGWifiP2pService: P2pDisabledState{ when=-3ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:16:26.627  1034  1536 D LGWifiP2pService: DefaultState{ when=-3ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,09-01 11:16:26.655  1034  1650 I ActivityManager: Killing 7333:com.lge.bnr/1000 (adj 15): empty #17
,09-01 11:16:26.669  1034  1537 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
09-01 11:16:26.669  1034  1537 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,09-01 11:16:26.689  1034  1050 W libprocessgroup: failed to open /acct/uid_1000/pid_7333/cgroup.procs: No such file or directory
,09-01 11:16:27.013  6920  6920 V BluetoothOppNotification: new notify threadi!
,09-01 11:16:27.013  6920  6920 V BluetoothOppNotification: send delay message
,09-01 11:16:27.025  6920  7555 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,09-01 11:16:27.029  6920  7555 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@29a271c4 on behalf of 
09-01 11:16:27.034  6920  7555 V BluetoothOppNotification: mUpdateCompleteNotification = true
,09-01 11:16:27.041  6920  7555 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-01 11:16:27.042  6920  7555 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3a6c58ad on behalf of 
09-01 11:16:27.042  6920  7555 V BluetoothOppNotification: outbound: succ-0  fail-0
09-01 11:16:27.045  6920  7555 V BluetoothOppNotification: outbound notification was removed.
09-01 11:16:27.046  6920  7555 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-01 11:16:27.047  6920  7555 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@25f4a7e2 on behalf of 
09-01 11:16:27.047  6920  7555 V BluetoothOppNotification: inbound: succ-0  fail-0
09-01 11:16:27.049  6920  7555 V BluetoothOppNotification: inbound notification was removed.
09-01 11:16:27.049  6920  7555 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-01 11:16:27.050  6920  7555 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2f1e8773 on behalf of 
,09-01 11:16:27.113  1034  2022 I ActivityManager: Killing 6834:com.lge.sync/1000 (adj 15): empty #17
,09-01 11:16:27.140  1034  1543 D WifiService: Client connection lost with reason: 4
,09-01 11:16:27.149  1034  1650 W libprocessgroup: failed to open /acct/uid_1000/pid_6834/cgroup.procs: No such file or directory
,09-01 11:16:27.633  1034  2048 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:16:27.633  1034  2048 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@26d8c861 mBinding = false
,09-01 11:16:27.667  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-01 11:16:27.667  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-01 11:16:27.668  1034  1034 D Ulp_jni : JNI:system_update. Event-4
,09-01 11:16:27.671  1034  1096 D BluetoothManagerService: Message: 2
09-01 11:16:27.672  1034  1096 D BluetoothManagerService: Sending off request.
09-01 11:16:27.672  6920  6935 D LGBluetoothServiceAdapter: [BTUI] Precleanup
09-01 11:16:27.673  6920  7407 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
09-01 11:16:27.673  6920  7407 D BluetoothAdapterProperties: Setting state to 13
09-01 11:16:27.673  6920  7407 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-01 11:16:27.674  6920  7407 D BluetoothAdapterProperties: onBluetoothDisable()
09-01 11:16:27.674  6920  7407 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-01 11:16:27.676  6920  7411 D BluetoothAdapterProperties: Scan Mode:20
09-01 11:16:27.677  6920  7407 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-01 11:16:27.678  6920  7407 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-01 11:16:27.679  6920  7529 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
09-01 11:16:27.679  6920  7529 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-01 11:16:27.679  6920  7529 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
09-01 11:16:27.679  6920  7529 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
09-01 11:16:27.679  6920  7529 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
09-01 11:16:27.679  6920  7529 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
09-01 11:16:27.679  6920  7529 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
09-01 11:16:27.679  6920  7529 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
09-01 11:16:27.682  6920  7530 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-01 11:16:27.685  6920  7540 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-01 11:16:27.685  6920  7544 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-01 11:16:27.686  6920  7477 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
09-01 11:16:27.687  6920  7542 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-01 11:16:27.687  6920  7477 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
09-01 11:16:27.689  6920  7477 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-01 11:16:27.689  6920  7477 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-01 11:16:27.689  6920  7477 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-01 11:16:27.689  6920  7477 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-01 11:16:27.689  6920  7477 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-01 11:16:27.689  6920  7477 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-01 11:16:27.689  6920  7477 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-01 11:16:27.689  6920  7477 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-01 11:16:27.689  6920  7477 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-01 11:16:27.689  6920  7477 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
09-01 11:16:27.689  6920  7477 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
09-01 11:16:27.689  6920  7477 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-01 11:16:27.699  6682  6682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:16:27.699  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:16:27.699  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:16:27.699  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-01 11:16:27.699  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 11:16:27.699  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 11:16:27.699  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:16:27.699  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:16:27.699  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-01 11:16:27.707  6682  6682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:16:27.707  6682  6682 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-01 11:16:27.711  6682  6682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:16:27.711  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:16:27.711  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:16:27.711  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-01 11:16:27.711  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 11:16:27.711  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 11:16:27.711  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:16:27.711  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:16:27.711  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 11:16:27.713  6682  6682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:16:27.713  6682  6682 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-01 11:16:27.716  1034  1096 D BluetoothManagerService: Message: 60
09-01 11:16:27.716  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
09-01 11:16:27.716  1034  1096 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
09-01 11:16:27.719  1939  1939 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:16:27.721  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-01 11:16:27.725  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:16:27.730  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:16:27.731  6920  6920 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:16:27.732  6920  6920 D BluetoothMapService: STATE_TURNING_OFF
09-01 11:16:27.732  6920  6920 V BluetoothMapService: Handler(): got msg=4
09-01 11:16:27.732  6920  6920 D BluetoothMapService: MAP Service closeService in
09-01 11:16:27.732  6920  6920 D BluetoothMapMasInstance: MAP Service shutdown
09-01 11:16:27.732  6920  6920 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-01 11:16:27.732  6920  6920 V BluetoothMapService: MAP Service closeService out
09-01 11:16:27.733  6920  6920 V BtOppService: Receiver DISABLED_ACTION 
09-01 11:16:27.734  6920  6920 I BtOppRfcommListener: stopping Accept Thread
09-01 11:16:27.734  6920  6920 V BtOppRfcommListener: close mBtServerSocket
09-01 11:16:27.734  6920  7540 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-01 11:16:27.735  6920  6920 V BtOppRfcommListener: waiting for thread to terminate
09-01 11:16:27.735  6920  6920 V BtOppRfcommListener: done waiting for thread to terminate
09-01 11:16:27.739  6814  6814 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
,09-01 11:16:27.753  6814  6814 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,09-01 11:16:27.756  6920  6920 V BtOppService: onDestroy
09-01 11:16:27.757  6920  6920 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
09-01 11:16:27.762  6920  6920 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-01 11:16:27.762  6920  6920 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:16:27.762  6920  6920 V BluetoothPbapReceiver: ***********state = 13
09-01 11:16:27.764  6920  6920 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
09-01 11:16:27.766  6920  6920 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:16:27.766  6920  6920 V BluetoothPbapService: state: 13
09-01 11:16:27.766  6920  6920 V BluetoothPbapService: Pbap Service closeService in
,09-01 11:16:27.771  2180  2180 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-01 11:16:27.773  6920  6920 V BluetoothPbapService: successfully stopped pbap service
09-01 11:16:27.773  6920  6920 V BluetoothPbapService: Pbap Service closeService out
09-01 11:16:27.774  6920  6920 V BluetoothPbapService: Pbap Service onDestroy
09-01 11:16:27.774  6920  6920 V BluetoothPbapService: Pbap Service closeService in
09-01 11:16:27.774  6920  6920 V BluetoothPbapService: Pbap Service closeService out
09-01 11:16:27.774  6920  6920 D LGBluetoothPbapAdapter: [BTUI] cleanup
,09-01 11:16:27.805  6814  6814 D DockEventReceiver: finishStartingService: stopping service,
,09-01 11:16:27.807  6814  6814 D BluetoothPbap: Proxy object disconnected
09-01 11:16:27.807  6814  6814 D PbapServerProfile: Bluetooth service disconnected
09-01 11:16:27.813  6814  6814 D LGBluetoothAuthorization: [BTUI] cancel All Notification
09-01 11:16:27.818  6814  6814 D BluetoothPermissionRequest: onReceive
09-01 11:16:27.818  6814  6814 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,09-01 11:16:27.825  6814  6814 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-01 11:16:27.829  6920  6920 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
09-01 11:16:27.829  6920  6920 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
09-01 11:16:27.830  6920  6920 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
09-01 11:16:27.833  6920  6920 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,09-01 11:16:27.834  6920  6920 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-01 11:16:27.835  6920  6920 V BluetoothFtpService: Ftp Service onStartCommand
09-01 11:16:27.835  6920  6920 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:16:27.835  6920  6920 V BluetoothFtpService: Ftp Service closeService
09-01 11:16:27.835  6920  6920 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
09-01 11:16:27.838  6920  6920 V BluetoothFtpService: successfully stopped ftp service
09-01 11:16:27.838  6920  6920 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-01 11:16:27.838  6920  6920 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-01 11:16:27.838  6920  6920 V BluetoothSapReceiver: SapReceiver onReceive 
09-01 11:16:27.839  6920  6920 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:16:27.839  6920  6920 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
09-01 11:16:27.839  6920  6920 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-01 11:16:27.840  6920  6920 V BluetoothFtpService: Ftp Service onDestroy
09-01 11:16:27.840  6920  6920 V BluetoothFtpService: Ftp Service closeService
09-01 11:16:27.843  6920  6920 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:16:27.843  6920  6920 V BluetoothSapService: state: 13
09-01 11:16:27.843  6920  6920 V BluetoothSapService: Stopping SAP server process
09-01 11:16:27.845  6920  6920 V BluetoothSapService: Sap Service closeSapService in
09-01 11:16:27.845  6920  6920 V BluetoothSapService: Close listen Socket : 
09-01 11:16:27.845  6920  6920 V BluetoothSapService: Close rfcomm Socket : 
09-01 11:16:27.845  6920  6920 V BluetoothSapService: Close sapd  Socket : 
,09-01 11:16:27.848  6920  6920 V BluetoothSapService: Sap Service closeSapService out
,09-01 11:16:27.848  6920  6920 V BluetoothSapService: Sap Service onDestroy
09-01 11:16:27.848  6920  6920 V BluetoothSapService: Sap Service closeSapService in
09-01 11:16:27.848  6920  6920 V BluetoothSapService: Close listen Socket : 
09-01 11:16:27.848  6920  6920 V BluetoothSapService: Close rfcomm Socket : 
09-01 11:16:27.848  6920  6920 V BluetoothSapService: Close sapd  Socket : 
09-01 11:16:27.849  6920  6920 V BluetoothSapService: Sap Service closeSapService out
09-01 11:16:28.650  6920  7411 D bt_hci_bdroid: cleanup
,09-01 11:16:28.659  6920  7479 I bt_lpm  : LPM is already off!!!
09-01 11:16:28.662  6920  7503 I bt_userial_mct: exiting userial_read_thread
09-01 11:16:28.662  6920  7503 D bt_userial_mct: Leaving userial_evt_read_thread()
09-01 11:16:28.663  6920  7477 W bt-btif : ag scb idx 1 not allocated
09-01 11:16:28.663  6920  7477 E bt-btif : BTA AG is already disabled, ignoring ...
09-01 11:16:28.663  6920  7477 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-01 11:16:28.663  6920  7477 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-01 11:16:28.663  6920  7477 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-01 11:16:28.663  6920  7477 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-01 11:16:28.663  6920  7477 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-01 11:16:28.663  6920  7477 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-01 11:16:28.663  6920  7477 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-01 11:16:28.663  6920  7477 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-01 11:16:28.663  6920  7477 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-01 11:16:28.663  6920  7477 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-01 11:16:28.663  6920  7477 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-01 11:16:28.663  6920  7477 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-01 11:16:28.663  6920  7477 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-01 11:16:28.664  6920  7477 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-01 11:16:28.664  6920  7477 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-01 11:16:28.664  6920  7477 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-01 11:16:28.664  6920  7477 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-01 11:16:28.664  6920  7477 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-01 11:16:28.664  6920  7477 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-01 11:16:28.667  6920  7411 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
,09-01 11:16:28.672  6920  7479 I bt_vendor: hw_epilog_process
09-01 11:16:28.673  6920  7411 D bt_hci_bdroid: cleanup Finalizing cleanup
09-01 11:16:28.673  6920  7411 D bt_userial_mct: userial_close
09-01 11:16:28.673  6920  7411 E bt_userial_mct: pthread_join() FAILED result:3
09-01 11:16:28.673  6920  7411 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
09-01 11:16:28.679  6920  7411 D bt_hci_bdroid: set_power 0
09-01 11:16:28.679  6920  7411 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-01 11:16:28.679  6920  7411 I bt_vendor: bluetooth satus is on
09-01 11:16:28.679  6920  7411 I bt_vendor: bt-vendor : resetting BT status
09-01 11:16:28.679  6920  7411 I bt_vendor: Starting hciattach daemon
09-01 11:16:28.679  6920  7411 I bt_vendor: try to set false
09-01 11:16:28.680  6920  7411 I bt_vendor: Starting hciattach daemon
09-01 11:16:28.680  6920  7411 I bt_vendor: try to set false
,09-01 11:16:28.685  6920  7411 I bt_vendor: cleanup
09-01 11:16:28.686  6920  7477 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-01 11:16:28.686  6920  7411 I GKI_LINUX: GKI_exit_task 0 done
09-01 11:16:28.686  6920  7411 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
09-01 11:16:28.688  6920  7407 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-01 11:16:28.692  6920  6920 D HeadsetService: Received stop request...Stopping profile...
09-01 11:16:28.695  6920  6920 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-01 11:16:28.695  6920  6920 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-01 11:16:28.695  6920  6920 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15e15917
,09-01 11:16:28.697  6920  7440 D HeadsetStateMachine: Exit Disconnected: -1
09-01 11:16:28.701  1850  1850 D BluetoothHeadset: Proxy object disconnected
09-01 11:16:28.701  1850  1850 D BluetoothHeadset: Proxy object disconnected
09-01 11:16:28.701  1850  1850 D BluetoothHeadset: Proxy object disconnected
09-01 11:16:28.702  1034  1034 D BluetoothHeadset: Proxy object disconnected
09-01 11:16:28.702  1034  1034 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-01 11:16:28.704  6920  6920 D A2dpService: Received stop request...Stopping profile...
09-01 11:16:28.704  6920  7469 D A2dpStateMachine: Exit Disconnected: -1
09-01 11:16:28.708  6920  7407 D BluetoothAdapterState: Stopping profile services that were post enabled
,09-01 11:16:28.712  6920  6920 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
09-01 11:16:28.713  6920  6920 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
09-01 11:16:28.713  6920  6920 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
09-01 11:16:28.713  6920  6920 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15e15917
09-01 11:16:28.715  1034  1034 D BluetoothA2dp: Proxy object disconnected
09-01 11:16:28.715  1034  1034 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-01 11:16:28.716  6920  6920 D HidService: Received stop request...Stopping profile...
09-01 11:16:28.717  6920  6920 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15e15917
09-01 11:16:28.721  6920  6920 D HeadsetStateMachine: Unbinding service...
,09-01 11:16:28.723  6920  6920 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-01 11:16:28.723  6920  6920 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-01 11:16:28.724  6920  6920 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-01 11:16:28.724  6920  6920 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-01 11:16:28.724  6920  6920 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-01 11:16:28.724  6920  6920 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-01 11:16:28.724  6920  6920 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-01 11:16:28.726  6920  6920 D HealthService: Received stop request...Stopping profile...
09-01 11:16:28.726  6920  6920 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15e15917
09-01 11:16:28.728  6920  6920 D PanService: Received stop request...Stopping profile...
09-01 11:16:28.730  6920  6920 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15e15917
09-01 11:16:28.732  6920  6920 D BtGatt.DebugUtils: handleDebugAction() action=null
09-01 11:16:28.732  6920  6920 D BtGatt.GattService: Received stop request...Stopping profile...
09-01 11:16:28.732  6920  6920 D BtGatt.GattService: stop()
09-01 11:16:28.732  6920  6920 D BtGatt.AdvertiseManager: advertise clients cleared
,09-01 11:16:28.736  6920  6920 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15e15917
09-01 11:16:28.738  6920  6920 D BluetoothMapService: Received stop request...Stopping profile...
09-01 11:16:28.738  6920  6920 D BluetoothMapService: stop()
09-01 11:16:28.739  6920  6920 D BluetoothMapEmailAppObserver: deinitObservers()
09-01 11:16:28.739  6920  6920 D BluetoothMapEmailAppObserver: removeReceiver()
09-01 11:16:28.740  6920  6920 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15e15917
09-01 11:16:28.742  6920  6920 I BluetoothA2dpServiceJni: cleanupNative
09-01 11:16:28.742  6920  7470 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-01 11:16:28.743  6920  6920 I GKI_LINUX: GKI_exit_task 2 done
09-01 11:16:28.743  6920  6920 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-01 11:16:28.743  6920  6920 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-01 11:16:28.743  6920  6920 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-01 11:16:28.743  6920  6920 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-01 11:16:28.744  6920  6920 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-01 11:16:28.744  6920  6920 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-01 11:16:28.744  6920  6920 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-01 11:16:28.744  6920  6920 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-01 11:16:28.753  6920  6920 V BluetoothMapService: Handler(): got msg=4
09-01 11:16:28.753  6920  6920 D BluetoothMapService: MAP Service closeService in
09-01 11:16:28.753  6920  6920 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-01 11:16:28.753  6920  6920 V BluetoothMapService: MAP Service closeService out
09-01 11:16:28.755  6920  7407 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
09-01 11:16:28.755  6920  7407 D BluetoothAdapterProperties: Setting state to 10
09-01 11:16:28.755  6920  7407 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-01 11:16:28.755  6920  6920 D BluetoothMapService: cleanup()
09-01 11:16:28.755  6920  6920 D BluetoothMapService: MAP Service closeService in
09-01 11:16:28.756  6920  6920 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-01 11:16:28.756  6920  6920 V BluetoothMapService: MAP Service closeService out
09-01 11:16:28.757  1034  1096 D BluetoothManagerService: Message: 60
09-01 11:16:28.757  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
09-01 11:16:28.757  1034  1096 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
,09-01 11:16:28.759  6920  7407 I BluetoothAdapterState: Entering OffState
09-01 11:16:28.759  6814  7524 D BluetoothHeadset: onBluetoothStateChange: up=false
09-01 11:16:28.760  1850  4446 D BluetoothHeadset: onBluetoothStateChange: up=false
09-01 11:16:28.761  1850  1865 D BluetoothHeadset: onBluetoothStateChange: up=false
09-01 11:16:28.761  1034  1096 D BluetoothHeadset: onBluetoothStateChange: up=false
09-01 11:16:28.762  6814  7524 D BluetoothPan: onBluetoothStateChange on: false
09-01 11:16:28.762  1034  1096 D BluetoothA2dp: onBluetoothStateChange: up=false
09-01 11:16:28.762  1850  1866 D BluetoothHeadset: onBluetoothStateChange: up=false
09-01 11:16:28.763  6814  7524 D BluetoothPbap: onBluetoothStateChange: up=false
09-01 11:16:28.764  6814  7524 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-01 11:16:28.764  6814  7524 D BluetoothMap: onBluetoothStateChange: up=false
09-01 11:16:28.765  6814  7524 D BluetoothA2dp: onBluetoothStateChange: up=false
09-01 11:16:28.767  1034  1096 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
09-01 11:16:28.767  1034  1096 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
09-01 11:16:28.769  1034  1096 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
09-01 11:16:28.769  1034  1096 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
09-01 11:16:28.769  1034  1096 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@26d8c861 mBinding = false
,09-01 11:16:28.772  1034  1096 D BluetoothManagerService: Sending unbind request.
09-01 11:16:28.776  6920  7411 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
09-01 11:16:28.778  6920  6920 I GKI_LINUX: GKI_exit_task 1 done
09-01 11:16:28.778  6920  6920 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
09-01 11:16:28.778  6920  6920 I BluetoothServiceJni: cleanupNative: return from cleanup
09-01 11:16:28.778  6920  6920 I art     : --- WEIRD: removing null entry 248
09-01 11:16:28.778  6920  6920 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
09-01 11:16:28.778  6920  6920 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
09-01 11:16:28.780  6920  6920 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
09-01 11:16:28.781  1034  1096 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
,09-01 11:16:28.785  6920  6920 I art     : System.exit called, status: 0
09-01 11:16:28.785  6920  6920 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
09-01 11:16:28.813  1939  1939 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,09-01 11:16:28.814  1939  2084 D LGBluetoothAPIService: Message: 2
09-01 11:16:28.814  1939  2084 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@1270c066 mBinding = false
09-01 11:16:28.814  1939  2084 D LGBluetoothAPIService: Sending unbind request.
09-01 11:16:28.817   313  2203 V AudioFlinger: 6920 died, releasing its sessions
09-01 11:16:28.817   313  2203 V AudioFlinger:  pid 1850 @ 0
09-01 11:16:28.817   313  2203 V AudioFlinger:  pid 3463 @ 1
,09-01 11:16:28.817   313  2203 V AudioFlinger:  pid 3463 @ 2
09-01 11:16:28.818  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-01 11:16:28.819  6814  6814 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
09-01 11:16:28.821  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:16:28.822  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:16:28.823  6814  6814 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
09-01 11:16:28.823  6814  6814 D LGBluetoothEventManager: [BTUI] clear device connection state
09-01 11:16:28.827  1602  1602 D BluetoothAdapter: 521901550: getState() :  mService = null. Returning STATE_OFF
09-01 11:16:28.827  1602  1602 D BluetoothAdapter: 521901550: getState() :  mService = null. Returning STATE_OFF
,09-01 11:16:28.830  1034  1893 W ActivityManager: Exception when unbinding service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer
09-01 11:16:28.830  1034  1893 W ActivityManager: android.os.DeadObjectException
09-01 11:16:28.830  1034  1893 W ActivityManager: 	at android.os.BinderProxy.transactNative(Native Method)
09-01 11:16:28.830  1034  1893 W ActivityManager: 	at android.os.BinderProxy.transact(Binder.java:496)
09-01 11:16:28.830  1034  1893 W ActivityManager: 	at android.app.ApplicationThreadProxy.scheduleUnbindService(ApplicationThreadNative.java:917)
09-01 11:16:28.830  1034  1893 W ActivityManager: 	at com.android.server.am.ActiveServices.removeConnectionLocked(ActiveServices.java:1776)
09-01 11:16:28.830  1034  1893 W ActivityManager: 	at com.android.server.am.ActiveServices.unbindServiceLocked(ActiveServices.java:901)
09-01 11:16:28.830  1034  1893 W ActivityManager: 	at com.android.server.am.ActivityManagerService.unbindService(ActivityManagerService.java:15417)
09-01 11:16:28.830  1034  1893 W ActivityManager: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:963)
09-01 11:16:28.830  1034  1893 W ActivityManager: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2560)
09-01 11:16:28.830  1034  1893 W ActivityManager: 	at com.android.server.am.ActivityManagerServiceEx.onTransact(ActivityManagerServiceEx.java:421)
09-01 11:16:28.830  1034  1893 W ActivityManager: 	at android.os.Binder.execTransact(Binder.java:446)
09-01 11:16:28.831  6814  6814 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-01 11:16:28.918  1034  1993 I ActivityManager: Process com.android.bluetooth (pid 6920) has died
09-01 11:16:28.919  1034  1993 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms
,09-01 11:16:29.014  1034  2048 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7604 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a,
09-01 11:16:29.016  6814  6814 D DockEventReceiver: finishStartingService: stopping service
,09-01 11:16:29.101  7604  7604 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
09-01 11:16:29.101  7604  7604 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-01 11:16:29.102  7604  7604 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
09-01 11:16:29.103  7604  7604 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-01 11:16:29.124  7604  7604 D BluetoothAdapterApp: Loading JNI Library
,09-01 11:16:29.161  7604  7604 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@3bade51f Instance Count = 1
,09-01 11:16:29.168  7604  7604 D BluetoothAdapterApp: onCreate
,09-01 11:16:29.193  7604  7604 D ProfileConfigQcom: [BTUI] HeadsetService is supported
09-01 11:16:29.193  7604  7604 D ProfileConfigQcom: Adding HeadsetService
09-01 11:16:29.193  7604  7604 D ProfileConfigQcom: [BTUI] A2dpService is supported
09-01 11:16:29.193  7604  7604 D ProfileConfigQcom: Adding A2dpService
,09-01 11:16:29.193  7604  7604 D ProfileConfigQcom: [BTUI] HidService is supported
09-01 11:16:29.193  7604  7604 D ProfileConfigQcom: Adding HidService
09-01 11:16:29.194  7604  7604 D ProfileConfigQcom: [BTUI] HealthService is supported
09-01 11:16:29.194  7604  7604 D ProfileConfigQcom: Adding HealthService
,09-01 11:16:29.194  7604  7604 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
09-01 11:16:29.195  7604  7604 D ProfileConfigQcom: [BTUI] PanService is supported
09-01 11:16:29.195  7604  7604 D ProfileConfigQcom: Adding PanService
09-01 11:16:29.195  7604  7604 D ProfileConfigQcom: [BTUI] GattService is supported
09-01 11:16:29.196  7604  7604 D ProfileConfigQcom: Adding GattService
09-01 11:16:29.196  7604  7604 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
09-01 11:16:29.196  7604  7604 D ProfileConfigQcom: Adding BluetoothMapService
09-01 11:16:29.196  7604  7604 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
09-01 11:16:29.197  7604  7604 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-01 11:16:29.198  7604  7604 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:16:29.199  7604  7604 V BluetoothPbapReceiver: ***********state = 10
,09-01 11:16:29.200  7604  7604 V LGMDMManagerInternal: Create singleton instance
09-01 11:16:29.272  2180  2180 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-01 11:16:29.279  6814  6814 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
09-01 11:16:29.281  1034  1779 I ActivityManager: Killing 6559:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
09-01 11:16:29.310  6868  6868 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
09-01 11:16:29.310  6868  6868 W System.err: android.os.DeadObjectException
09-01 11:16:29.310  6868  6868 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-01 11:16:29.310  6868  6868 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-01 11:16:29.310  6868  6868 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
09-01 11:16:29.310  6868  6868 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
09-01 11:16:29.311  6868  6868 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-01 11:16:29.311  6868  6868 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-01 11:16:29.311  6868  6868 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-01 11:16:29.311  6868  6868 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-01 11:16:29.311  6868  6868 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-01 11:16:29.311  6868  6868 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-01 11:16:29.311  6868  6868 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 11:16:29.311  6868  6868 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-01 11:16:29.311  6868  6868 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-01 11:16:29.311  6868  6868 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-01 11:16:29.311  6868  6868 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
09-01 11:16:29.311  6868  6868 W System.err: android.os.DeadObjectException
09-01 11:16:29.313  6868  6868 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-01 11:16:29.313  6868  6868 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-01 11:16:29.313  6868  6868 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
09-01 11:16:29.313  6868  6868 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
09-01 11:16:29.313  6868  6868 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-01 11:16:29.313  6868  6868 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-01 11:16:29.313  6868  6868 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-01 11:16:29.313  6868  6868 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-01 11:16:29.314  6868  6868 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-01 11:16:29.314  6868  6868 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-01 11:16:29.314  6868  6868 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 11:16:29.314  6868  6868 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-01 11:16:29.314  6868  6868 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
,09-01 11:16:29.314  6868  6868 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-01 11:16:29.314  6868  6868 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
09-01 11:16:29.315  6868  6868 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
09-01 11:16:29.390  1034  1050 W libprocessgroup: failed to open /acct/uid_1000/pid_6559/cgroup.procs: No such file or directory
,09-01 11:16:29.392  1034  1050 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
09-01 11:16:29.402  6868  6868 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
09-01 11:16:29.403  6868  6868 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
09-01 11:16:29.483  1034  1917 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7627 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-01 11:16:29.485  6868  6868 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,09-01 11:16:29.502  6814  6814 D BluetoothPermissionRequest: onReceive
,09-01 11:16:29.505  6814  6814 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-01 11:16:29.505  6814  6814 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
09-01 11:16:29.507  6814  6814 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-01 11:16:29.514  7604  7604 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,09-01 11:16:29.520  7604  7604 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:16:29.525  7604  7604 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-01 11:16:29.525  7604  7604 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-01 11:16:29.526  7604  7604 V BluetoothSapReceiver: SapReceiver onReceive 
09-01 11:16:29.527  7604  7604 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:16:29.527  7604  7604 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
09-01 11:16:29.531  6895  6895 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,09-01 11:16:29.569  7627  7627 D UEI.SmartControl: Quickset Services start...
09-01 11:16:29.572  7627  7627 I UEI.SmartControl: Manufacture = LGE
09-01 11:16:29.572  7627  7627 D UEI.SmartControl: Id = LGNevo
,09-01 11:16:29.577  7627  7627 D UEI.SmartControl: File observer start...
09-01 11:16:29.578  7627  7627 E UEI.SmartControl: IR Port is disabled: false
09-01 11:16:29.578  7627  7627 D UEI.SmartControl: Starting file observer...
09-01 11:16:29.579  7627  7627 D UEI.SmartControl: Extracting JNI libs...
09-01 11:16:29.579  7627  7627 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
,09-01 11:16:29.683  7627  7627 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
09-01 11:16:29.683  7627  7627 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
09-01 11:16:29.683  7627  7627 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,09-01 11:16:29.722  7627  7627 I UEI.SmartControl: --- Selecting new region: 6
,09-01 11:16:29.724  7627  7627 I UEI.SmartControl: Model = LG-D855
,09-01 11:16:29.726  7627  7627 D UEI.SmartControl: QS Service created
09-01 11:16:29.743  7627  7627 I UEI.SmartControl: Service initServices...
,09-01 11:16:29.749  7627  7627 D UEI.SmartControl: QS start get config
,09-01 11:16:29.790  7627  7627 D UEI.SmartControl: Loading JNI Libs...
,09-01 11:16:30.036  7627  7627 I UEI.SmartControl: Supports setup maps: true,
,09-01 11:16:30.039  7627  7627 D UEI.SmartControl: QS start statue = true Error code = 0
,09-01 11:16:30.039  7627  7627 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-01 11:16:30.039  7627  7627 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
,09-01 11:16:30.040  7627  7627 I UEI.SmartControl: ### init IR Blaster...
,09-01 11:16:30.045  7627  7627 D serial_port: Configuring serial port
,09-01 11:16:30.049  7627  7627 E UEI.SmartControl: UEIBLaster setting for 616
09-01 11:16:30.049  7627  7627 I UEI.SmartControl: Setting serial record hearder size = 2
09-01 11:16:30.049  7627  7627 I UEI.SmartControl: configuring settings for MAXQ616
09-01 11:16:30.049  7627  7627 I UEI.SmartControl: Get version...
09-01 11:16:30.068  7627  7648 D UEI.SmartControl: serial port data available: 21
,09-01 11:16:30.095  7627  7627 D UEI.SmartControl: MAXQ616 A2-X4 software.
,09-01 11:16:30.095  7627  7627 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-01 11:16:30.095  7627  7627 I UEI.SmartControl: QS saving settings...
,09-01 11:16:30.096  7627  7627 D UEI.SmartControl: IR Blaster version: 25672567
,09-01 11:16:30.113  7627  7648 D UEI.SmartControl: serial port data available: 4
,09-01 11:16:30.155  7627  7651 I UEI.SmartControl: Device manager: loading config....
,09-01 11:16:30.157  7627  7651 D UEI.SmartControl: ----------- loading internal config...
,09-01 11:16:30.164  7627  7627 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,09-01 11:16:30.168  7627  7627 E UEI.SmartControl: Services init done
09-01 11:16:30.169  7627  7627 D UEI.SmartControl: QS Service init finished
09-01 11:16:30.172  7627  7627 D UEI.SmartControl: QS Service version name: 2.1.91
09-01 11:16:30.173  7627  7627 D UEI.SmartControl: QS Service version code: 201091
09-01 11:16:30.175  7627  7627 D UEI.SmartControl: Service requested: Control
,09-01 11:16:30.182  7627  7651 E UEI.SmartControl: Loading SETTINGS...
09-01 11:16:30.186  7627  7627 D UEI.SmartControl: Request IControl service: devices are loaded...
09-01 11:16:30.190  7627  7651 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
09-01 11:16:30.191  1034  2022 I ActivityManager: Killing 6868:com.lge.qremote/u0a112 (adj 15): empty #17
,09-01 11:16:30.212  7627  7650 I UEI.SmartControl: Notify AllClients services are ready: 0
09-01 11:16:30.212  7627  7650 D UEI.SmartControl: -----service ready thread exits
,09-01 11:16:30.229  1034  1780 W libprocessgroup: failed to open /acct/uid_10112/pid_6868/cgroup.procs: No such file or directory
,09-01 11:16:30.231  7627  7627 D UEI.SmartControl: Internal service binding...
09-01 11:16:30.716  1034  1427 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-01 11:16:30.738  1602  1602 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,09-01 11:16:30.751  6682  6759 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:16:30.751  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 11:16:30.786  2031  2031 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,09-01 11:16:30.827  1034  1092 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7657 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,09-01 11:16:30.863  1602  1602 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
,09-01 11:16:30.867  1602  1602 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
09-01 11:16:30.874  2031  2031 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,09-01 11:16:30.899  1034  1034 D administrator: Handling package changes for user 0
,09-01 11:16:30.903  7657  7657 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-01 11:16:30.995  7657  7657 D LgDataFeature: LgDataFeature() Constructor: none
09-01 11:16:30.996  7657  7657 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-01 11:16:31.011  1034  1034 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
,09-01 11:16:31.011  1034  1034 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,09-01 11:16:31.037  1034  1091 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-01 11:16:31.042  1034  1091 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
09-01 11:16:31.049  2470  2470 V GmsNetworkLocationProvi: DISABLE
09-01 11:16:31.050  2031  2031 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,09-01 11:16:31.084  2470  2470 E GCoreFlp: Bound FusedProviderService with LocationManager
,09-01 11:16:31.112  7657  7702 I Babel   : MmsConfig: mnc/mcc: 0/0
09-01 11:16:31.112  7657  7702 I Babel   : MmsConfig.loadMmsSettings
,09-01 11:16:31.114  7657  7702 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
09-01 11:16:31.114  7657  7702 I Babel   : MmsConfig.loadFromDatabase
09-01 11:16:31.121  1034  1091 D LocationProviderProxy: applying state to connected service
,09-01 11:16:31.131  7657  7702 E Babel   : canonicalizeMccMnc: invalid mccmnc 
09-01 11:16:31.132  7657  7702 I Babel   : MmsConfig.loadFromResources
09-01 11:16:31.133  7657  7702 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
09-01 11:16:31.133  7657  7702 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
09-01 11:16:31.150  7657  7657 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-01 11:16:31.157  7657  7701 W AudioCapabilities: Unsupported mime audio/evrc
09-01 11:16:31.158  7657  7701 W AudioCapabilities: Unsupported mime audio/qcelp
09-01 11:16:31.160  7657  7701 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
09-01 11:16:31.173  7657  7701 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,09-01 11:16:31.173  1815  7705 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
09-01 11:16:31.173  1815  7705 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
09-01 11:16:31.174  7657  7701 W AudioCapabilities: Unsupported mime audio/qcelp
09-01 11:16:31.177  7657  7701 W AudioCapabilities: Unsupported mime audio/evrc
09-01 11:16:31.181  7003  7003 I AppUp4:CustModeStarterReceiver: onReceive
,09-01 11:16:31.186  1815  4784 I Icing   : updateResources: need to parse e{com.google.android.gms}
09-01 11:16:31.186  7003  7003 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1ac480b1
09-01 11:16:31.186  7003  7003 D AppUp4:CustFacade: isCustomizationCompleted : false
09-01 11:16:31.186  7003  7003 D AppUp4:CustFacade: isPhone : true
09-01 11:16:31.188  7003  7003 D AppUp4:CustModeStarterReceiver: begin check event
09-01 11:16:31.188  7003  7003 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
09-01 11:16:31.192  7657  7701 W VideoCapabilities: Unsupported mime video/x-ms-wmv
09-01 11:16:31.193  7657  7701 W VideoCapabilities: Unsupported mime video/divx
09-01 11:16:31.195  7657  7701 W VideoCapabilities: Unsupported mime video/divx311
09-01 11:16:31.197  7657  7701 W VideoCapabilities: Unsupported mime video/divx4
,09-01 11:16:31.209  7657  7701 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,09-01 11:16:31.224  1034  1779 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7708 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
09-01 11:16:31.228  1034  1893 I ActivityManager: Killing 7033:com.lge.email/u0a23 (adj 15): empty #17
09-01 11:16:31.234  7657  7701 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-01 11:16:31.238  7657  7701 W AudioCapabilities: Unsupported mime audio/eac3
09-01 11:16:31.238  7657  7701 W AudioCapabilities: Unsupported mime audio/ac3
09-01 11:16:31.239  7657  7701 W AudioCapabilities: Unsupported mime audio/g726
09-01 11:16:31.240  7657  7701 W AudioCapabilities: Unsupported mime audio/wma-voice
09-01 11:16:31.240  7657  7701 W AudioCapabilities: Unsupported mime audio/x-ms-wma
09-01 11:16:31.241  7657  7701 W AudioCapabilities: Unsupported mime audio/adpcm
09-01 11:16:31.242  7657  7701 W VideoCapabilities: Unsupported mime video/theora
09-01 11:16:31.244  7657  7701 W VideoCapabilities: Unsupported mime video/mjpg
,09-01 11:16:31.343  1034  1959 W libprocessgroup: failed to open /acct/uid_10023/pid_7033/cgroup.procs: No such file or directory
09-01 11:16:31.389  7708  7708 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-01 11:16:31.390  7708  7708 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-01 11:16:31.390  7708  7708 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
09-01 11:16:31.391  7708  7708 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
09-01 11:16:31.392  7708  7708 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-01 11:16:31.474  7708  7708 I SystemConfig: BUILD Country: EU
09-01 11:16:31.474  7708  7708 I SystemConfig: BUILD Operator: OPEN
,09-01 11:16:31.539  1034  1917 I ActivityManager: Killing 6937:com.lge.formmanager/u0a26 (adj 15): empty #17
,09-01 11:16:31.632  1034  1952 W libprocessgroup: failed to open /acct/uid_10026/pid_6937/cgroup.procs: No such file or directory
,09-01 11:16:31.686  1034  1544 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
,09-01 11:16:31.704  1034  1917 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7731 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,09-01 11:16:31.710  7708  7729 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
09-01 11:16:31.711  7708  7729 I SystemConfig: existFile = false
09-01 11:16:31.711  7708  7729 I SystemConfig: canReadFile = false
09-01 11:16:31.711  7708  7729 I SystemConfig: systemFeature RCS result false
09-01 11:16:31.711  7708  7729 D SystemConfig: refreshRcsSupport() :false
,09-01 11:16:31.792  7731  7731 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-01 11:16:31.792  7731  7731 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-01 11:16:31.793  7731  7731 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
09-01 11:16:31.793  7731  7731 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-01 11:16:31.905  7731  7731 I AppConfig: Total System Memory = 2995761152
,09-01 11:16:31.917  7731  7731 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
09-01 11:16:32.026  1034  1923 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7753 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-01 11:16:32.032  1034  1923 I ActivityManager: Killing 6350:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,09-01 11:16:32.079  1034  1959 W libprocessgroup: failed to open /acct/uid_1000/pid_6350/cgroup.procs: No such file or directory
,09-01 11:16:32.258  7753  7753 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,09-01 11:16:32.326  7753  7753 D LgDataFeature: LgDataFeature() Constructor: none
09-01 11:16:32.326  7753  7753 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-01 11:16:32.381  7753  7753 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,09-01 11:16:32.401  7753  7753 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,09-01 11:16:32.402  7753  7753 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
09-01 11:16:32.431  7753  7753 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-01 11:16:32.432  7753  7753 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,09-01 11:16:32.452  1034  1987 I ActivityManager: Killing 7079:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,09-01 11:16:32.546  1034  1650 W libprocessgroup: failed to open /acct/uid_10046/pid_7079/cgroup.procs: No such file or directory
,09-01 11:16:32.555  2844  2861 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
09-01 11:16:32.560  2844  2861 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@f4b85 on behalf of 7753
09-01 11:16:32.577  4633  7807 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,09-01 11:16:32.582  7753  7753 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
09-01 11:16:32.622  1034  1049 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7809 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,09-01 11:16:32.675  7753  7753 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
09-01 11:16:32.711  7809  7809 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,09-01 11:16:32.732  7809  7809 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
09-01 11:16:32.732  7809  7809 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
,09-01 11:16:32.732  7809  7809 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
,09-01 11:16:32.732  7809  7809 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
09-01 11:16:32.733  7809  7809 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
09-01 11:16:32.733  7809  7809 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
09-01 11:16:32.751  1034  2048 I ActivityManager: Killing 7100:com.android.chrome/u0a57 (adj 15): empty #17
,09-01 11:16:32.829  1034  1574 W libprocessgroup: failed to open /acct/uid_10057/pid_7100/cgroup.procs: No such file or directory
,09-01 11:16:33.065  1034  2030 V SIM_STK : Menu title from STK is T-Mobile
,09-01 11:16:33.094  4633  7807 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 517 ms] updated apps [took 517 ms] 
,09-01 11:16:33.866  6682  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-01 11:16:33.867  6682  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@193bd01b added. We now have 6 listener(s)
09-01 11:16:33.867  6682  6759 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-01 11:16:33.881  6682  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 11:16:33.881  6682  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7c205b8 added. We now have 7 listener(s)
09-01 11:16:33.882  6682  6759 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 11:16:33.886  6682  6759 I System.out: IsBluetoothEnabled
09-01 11:16:33.889  1034  1952 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:16:33.889  1034  1952 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
,09-01 11:16:33.891  1034  1096 D BluetoothManagerService: Message: 2
09-01 11:16:33.894  6682  6759 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:16:33.896  1034  1917 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:16:33.896  1034  1917 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
09-01 11:16:33.911  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-01 11:16:33.911  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-01 11:16:33.911  1034  1034 D Ulp_jni : JNI:system_update. Event-4
,09-01 11:16:33.914  1034  1096 D BluetoothManagerService: Message: 1
09-01 11:16:33.914  1034  1096 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
,09-01 11:16:33.943  1034  1096 D BluetoothManagerService: Message: 20
09-01 11:16:33.943  1034  1096 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@28d17b92:true
,09-01 11:16:33.947  7604  7604 D BluetoothAdapterState: make
09-01 11:16:33.952  7604  7604 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
09-01 11:16:33.952  7604  7604 I bluedroid-qcom: init
09-01 11:16:33.953  7604  7853 I BluetoothAdapterState: Entering OffState
09-01 11:16:33.953  7604  7604 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-01 11:16:33.954  7604  7604 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-01 11:16:33.954  7604  7604 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-01 11:16:33.954  7604  7604 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-01 11:16:33.954  7604  7604 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
09-01 11:16:33.956  7604  7604 I bluedroid-qcom: get_profile_interface socket
09-01 11:16:33.956  7604  7604 I bluedroid-qcom: get_profile_interface map_client
,09-01 11:16:33.948  7856  7856 W bdaddr_loader: type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-01 11:16:33.962  7604  7857 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
09-01 11:16:33.964  7604  7857 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
09-01 11:16:33.948  7856  7856 W bdaddr_loader: type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-01 11:16:33.975  7856  7856 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
09-01 11:16:33.975  7856  7856 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
09-01 11:16:33.975  7856  7856 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,09-01 11:16:33.979  1034  1034 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-01 11:16:33.980  1034  1034 D BluetoothManagerService: Stored Bluetooth name: G3
09-01 11:16:33.981  1034  1034 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
09-01 11:16:33.982  1034  1096 D BluetoothManagerService: Message: 40
09-01 11:16:33.982  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
09-01 11:16:33.982  7604  7621 I bluedroid-qcom: config_hci_snoop_log
09-01 11:16:33.984  1034  1096 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
09-01 11:16:33.984  1034  1096 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
09-01 11:16:33.984  7856  7856 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
09-01 11:16:33.987  7604  7857 D BluetoothAdapterProperties: Name is: G3
09-01 11:16:33.993  7856  7856 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
09-01 11:16:33.993  7856  7856 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
,09-01 11:16:33.998  7604  7853 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
09-01 11:16:33.999  7604  7853 D BluetoothAdapterProperties: Setting state to 11
09-01 11:16:33.999  7604  7853 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-01 11:16:34.000  7604  7853 I LGBluetoothServiceJni: classInitNative: succeeds
09-01 11:16:34.004  1034  1096 D BluetoothManagerService: Message: 60
09-01 11:16:34.005  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
09-01 11:16:34.005  1034  1096 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
09-01 11:16:34.009  1939  1939 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,09-01 11:16:34.011  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-01 11:16:34.014  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:16:34.032  7604  7853 D BluetoothBondStateMachine: make
,09-01 11:16:34.035  7604  7853 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15e15917
09-01 11:16:34.035  7604  7853 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
,09-01 11:16:34.035  7604  7853 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15e15917
09-01 11:16:34.035  7604  7853 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
09-01 11:16:34.019  6814  6814 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
09-01 11:16:34.036  7604  7853 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
09-01 11:16:34.039  7604  7870 I BluetoothBondStateMachine: StableState(): Entering Off State
09-01 11:16:34.041  7604  7604 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-01 11:16:34.041  7604  7604 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:16:34.041  7604  7604 V BluetoothPbapReceiver: ***********state = 11
09-01 11:16:34.045  2180  2180 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-01 11:16:34.046  7604  7853 E BluetoothAdapterService: File transfer profiles supported!!
,09-01 11:16:34.061  7604  7853 E BluetoothAdapterService: File transfer profiles supported!!
09-01 11:16:34.063  7604  7604 D HeadsetService: Received start request. Starting profile...
09-01 11:16:34.063  7604  7604 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
09-01 11:16:34.063  7604  7604 D LGBluetoothHfpAdapter: Version 1.6
09-01 11:16:34.067  7604  7604 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,09-01 11:16:34.069  6814  6814 D BluetoothPermissionRequest: onReceive
09-01 11:16:34.070  7604  7604 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-01 11:16:34.071  7604  7604 D HeadsetStateMachine: make
09-01 11:16:34.077  7604  7853 E BluetoothAdapterService: File transfer profiles supported!!
09-01 11:16:34.078  6814  6814 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-01 11:16:34.090  7604  7853 E BluetoothAdapterService: File transfer profiles supported!!
,09-01 11:16:34.096  7604  7853 E BluetoothAdapterService: File transfer profiles supported!!
09-01 11:16:34.101  7604  7853 E BluetoothAdapterService: File transfer profiles supported!!
09-01 11:16:34.106  7604  7853 E BluetoothAdapterService: File transfer profiles supported!!
,09-01 11:16:34.112  7604  7604 D LgDataFeature: LgDataFeature() Constructor: none
09-01 11:16:34.112  7604  7604 D LgDataFeature: LgDataFeature() Constructor Done, null
09-01 11:16:34.117  7604  7604 D HeadsetStateMachine: max_hf_connections = 1
09-01 11:16:34.117  7604  7604 I bluedroid-qcom: get_profile_interface handsfree
,09-01 11:16:34.120  7604  7604 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
09-01 11:16:34.121   313  1385 V AudioPolicyService: registerClient() client 0xb57f5780, uid 1002
09-01 11:16:34.121   313  1386 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
09-01 11:16:34.121   313  1386 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-01 11:16:34.121   313  1386 V AudioPolicyManagerEx: getOutput() returns output 2
09-01 11:16:34.121  7604  7604 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
09-01 11:16:34.122   313   313 V AudioFlinger: registerClient() client 0xb1433178, pid 7604
09-01 11:16:34.122   313  1380 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-01 11:16:34.122   313  1380 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-01 11:16:34.122  7604  7604 V ToneGenerator: Create Track: 0xb4928080
09-01 11:16:34.122  7604  7604 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
09-01 11:16:34.122  7604  7604 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
09-01 11:16:34.123   313  1385 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-01 11:16:34.123  3463  3479 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-01 11:16:34.123  3463  3479 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-01 11:16:34.123   313  1385 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
09-01 11:16:34.123   313  1385 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-01 11:16:34.123   313  1385 V AudioPolicyManagerEx: getOutput() returns output 2
09-01 11:16:34.123  1034  2030 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-01 11:16:34.123  1034  2030 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-01 11:16:34.123   313  1381 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-01 11:16:34.123   313  1381 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-01 11:16:34.123  7604  7604 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
09-01 11:16:34.123  1602  1618 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-01 11:16:34.123  1602  1618 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-01 11:16:34.124  1850  1865 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-01 11:16:34.124  1850  1865 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-01 11:16:34.124  1602  2066 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-01 11:16:34.124  1850  4447 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-01 11:16:34.124  1602  2066 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-01 11:16:34.124  1850  4447 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-01 11:16:34.124  3463  3483 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-01 11:16:34.124  1034  2022 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-01 11:16:34.124  3463  3483 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-01 11:16:34.124  1034  2022 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-01 11:16:34.125  7604  7621 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-01 11:16:34.125  7604  7621 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
09-01 11:16:34.125  7604  7853 V LGMDMManager: Create singleton instance
09-01 11:16:34.125  7604  7621 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-01 11:16:34.125  7604  7621 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
09-01 11:16:34.125   313  1386 I AudioFlinger: isAudi,oPlaybackHookOn() false
09-01 11:16:34.125   313  2202 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-01 11:16:34.125   313  2202 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
09-01 11:16:34.125   313  2202 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-01 11:16:34.125   313  2202 V AudioPolicyManagerEx: getOutput() returns output 2
09-01 11:16:34.126  7604  7604 V AudioSystem: getLatency() output 2, latency 50
09-01 11:16:34.126  7604  7604 V AudioSystem: getFrameCount() output 2, frameCount 960
09-01 11:16:34.126  7604  7604 V AudioTrack: createTrack_l() output 2 afLatency 50
09-01 11:16:34.126   313   313 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-01 11:16:34.126   313   313 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-01 11:16:34.126   313   313 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-01 11:16:34.126   313   313 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-01 11:16:34.126   313   313 V AudioFlinger: createTrack() lSessionId: 23
09-01 11:16:34.127  7604  7604 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
09-01 11:16:34.128  7604  7853 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
09-01 11:16:34.128   313   313 V AudioFlinger: acquiring 23 from 7604, for 7604
09-01 11:16:34.128   313   313 V AudioFlinger:  added new entry for 23
09-01 11:16:34.128  7604  7604 V ToneGenerator: ToneGenerator INIT OK, time: 197700
09-01 11:16:34.128  7604  7604 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15e15917
09-01 11:16:34.129  7604  7875 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
,09-01 11:16:34.129  7604  7875 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
,09-01 11:16:34.130  7604  7875 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-01 11:16:34.130  7604  7875 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
09-01 11:16:34.130   313  1385 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7604
09-01 11:16:34.131   313  1385 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
09-01 11:16:34.131   313  1385 V voice   : voice_set_parameters: enter: bt_samplerate=8000
,09-01 11:16:34.131   313  1385 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
09-01 11:16:34.131   313  1385 V compress_voip: voice_extn_compress_voip_set_parameters: exit
09-01 11:16:34.131   313  1385 V voice   : voice_set_parameters: exit with code(0)
09-01 11:16:34.131   313  1385 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
09-01 11:16:34.131   313  1385 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
09-01 11:16:34.131   313  1385 V msm8974_platform: platform_set_parameters: exit with code(0)
09-01 11:16:34.131   313  1385 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
09-01 11:16:34.131   313  1385 V audio_hw_primary: adev_set_parameters: exit with code(0)
09-01 11:16:34.131   313  1385 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
09-01 11:16:34.132  7604  7875 V ToneGenerator: ToneGenerator destructor
09-01 11:16:34.132  7604  7875 V ToneGenerator: stopTone
09-01 11:16:34.132  7604  7875 V ToneGenerator: Delete Track: 0xb4928080
09-01 11:16:34.132  7604  7875 V AudioTrack: ~AudioTrack, releasing session id from 7604 on behalf of 7604
09-01 11:16:34.132  7604  7604 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15e15917
09-01 11:16:34.132   313  1386 V AudioFlinger: releasing 23 from 7604 for 7604
09-01 11:16:34.132   313  1386 V AudioFlinger:  decremented refcount to 0
09-01 11:16:34.132   313  1386 V AudioFlinger: purging stale effects
09-01 11:16:34.132   313  1386 V AudioPolicyService: AudioCommandThread() adding release output 2
09-01 11:16:34.132   313  1386 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
09-01 11:16:34.132   313  1258 V AudioPolicyService: AudioCommandThread() waking up
09-01 11:16:34.132   313  1258 V AudioPolicyService: AudioCommandThread() processing release output 2
09-01 11:16:34.132   313  1258 V AudioPolicyManager: releaseOutput() 2
09-01 11:16:34.132   313  1258 V AudioPolicyService: AudioCommandThread() going to sleep
09-01 11:16:34.132   313  1386 V AudioFlinger: PlaybackThread::Track destructor
09-01 11:16:34.133   313  1386 V AudioFlinger: removeClient_l() pid 7604, calling pid 313
09-01 11:16:34.133  1034  1917 W Process : Unable to open /proc/7877/status
09-01 11:16:34.135  7604  7604 D A2dpService: Received start request. Starting profile...
09-01 11:16:34.136  7604  7604 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-01 11:16:34.137  7604  7604 V Avrcp   : make
09-01 11:16:34.137  7604  7604 D Avrcp   : [BTUI] Use Native AVRCP : init jni
09-01 11:16:34.137  7604  7604 I bluedroid-qcom: get_profile_interface avrcp
09-01 11:16:34.147  7604  7604 V AudioManager: registerRemoteController: size of Media player list: 0
09-01 11:16:34.149  7604  7604 E AudioManager: No RCC entry present to update
09-01 11:16:34.149  7604  7604 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-01 11:16:34.154  7604  7604 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
09-01 11:16:34.155  7604  7604 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
09-01 11:16:34.155  7604  7604 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
09-01 11:16:34.161  7604  7604 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,09-01 11:16:34.324  1034  2048 V SIM_STK : Menu title from STK is T-Mobile
,09-01 11:16:34.324  1034  2048 V SIM_STK : Menu title from STK is T-Mobile
,09-01 11:16:34.501  1034  2030 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,09-01 11:16:34.515  7604  7604 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,09-01 11:16:34.524  7604  7604 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-01 11:16:34.524  7604  7604 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-01 11:16:34.525  7604  7604 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-01 11:16:34.525  7604  7604 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-01 11:16:34.525  7604  7604 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-01 11:16:34.525  7604  7604 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-01 11:16:34.525  7604  7604 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-01 11:16:34.525  7604  7604 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-01 11:16:34.525  7604  7604 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-01 11:16:34.525  7604  7604 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-01 11:16:34.526  7604  7604 I BluetoothA2dpServiceJni: classInitNative
09-01 11:16:34.526  7604  7604 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-01 11:16:34.526  7604  7604 D A2dpStateMachine: make
09-01 11:16:34.529  7604  7604 I bluedroid-qcom: get_profile_interface a2dp
09-01 11:16:34.529  7604  7890 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
09-01 11:16:34.533  7604  7604 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
09-01 11:16:34.533  7604  7604 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
,09-01 11:16:34.537  7604  7604 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15e15917
09-01 11:16:34.541  7604  7604 I BluetoothHidServiceJni: classInitNative: succeeds
09-01 11:16:34.543  7604  7889 D A2dpStateMachine: Enter Disconnected: -2
09-01 11:16:34.545  7604  7604 D HidService: Received start request. Starting profile...
09-01 11:16:34.545  7604  7604 I bluedroid-qcom: get_profile_interface hidhost
09-01 11:16:34.545  7604  7604 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15e15917
09-01 11:16:34.546  7604  7604 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-01 11:16:34.550  7604  7604 D HealthService: Received start request. Starting profile...
09-01 11:16:34.552  7604  7604 I bluedroid-qcom: get_profile_interface health
09-01 11:16:34.552  7604  7604 I LGBluetoothHealthServiceJni: classInitNative: succeeds
09-01 11:16:34.553  7604  7604 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15e15917
09-01 11:16:34.554  7604  7604 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-01 11:16:34.557  7604  7604 D PanService: Received start request. Starting profile...
09-01 11:16:34.557  7604  7604 D BluetoothPanServiceJni: initializeNative(L110): pan
09-01 11:16:34.557  7604  7604 I bluedroid-qcom: get_profile_interface pan
09-01 11:16:34.565  7604  7604 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
09-01 11:16:34.565  7604  7604 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15e15917
,09-01 11:16:34.569  7604  7604 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
09-01 11:16:34.576  7604  7604 D BtGatt.DebugUtils: handleDebugAction() action=null
09-01 11:16:34.576  7604  7604 D BtGatt.GattService: Received start request. Starting profile...
09-01 11:16:34.577  7604  7604 D BtGatt.GattService: start()
09-01 11:16:34.577  7604  7604 I bluedroid-qcom: get_profile_interface gatt
09-01 11:16:34.577  7604  7604 D BtGatt.AdvertiseManager: advertise manager created
,09-01 11:16:34.586  7604  7604 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15e15917
09-01 11:16:34.589  7604  7604 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15e15917
09-01 11:16:34.590  7604  7604 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
09-01 11:16:34.591  7604  7604 V BluetoothMapService: BluetoothMapBinder()
,09-01 11:16:34.593  7604  7604 D BluetoothMapService: Received start request. Starting profile...
09-01 11:16:34.593  7604  7604 D BluetoothMapService: start()
09-01 11:16:34.597  7604  7604 D BluetoothMapEmailSettingsLoader: Found 0 applications
09-01 11:16:34.597  7604  7604 D BluetoothMapEmailAppObserver: createReceiver()
09-01 11:16:34.598  7604  7604 D BluetoothMapEmailAppObserver: initObservers()
09-01 11:16:34.599  7604  7604 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
09-01 11:16:34.609  7604  7604 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15e15917
,09-01 11:16:34.611  7604  7604 D HeadsetStateMachine: Proxy object connected
09-01 11:16:34.612  7604  7604 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
09-01 11:16:34.612  7604  7604 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
09-01 11:16:34.614  7604  7875 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-01 11:16:34.615  7604  7875 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-01 11:16:34.615  7604  7875 D HeadsetStateMachine: Disconnected process message: 11, size: 0
09-01 11:16:34.620  7604  7604 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,09-01 11:16:34.625  7604  7604 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-01 11:16:34.627  7604  7604 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:16:34.633  7604  7604 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,09-01 11:16:34.637  7604  7604 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-01 11:16:34.638  7604  7604 V PanService: [BTUI] SIM Extra State :ABSENT
09-01 11:16:34.641  7604  7604 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-01 11:16:34.644  7604  7604 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
,09-01 11:16:34.646  7604  7604 V BluetoothMapService: Handler(): got msg=1
09-01 11:16:34.647  7604  7853 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
09-01 11:16:34.647  7604  7853 I bluedroid-qcom: enable
09-01 11:16:34.648  7604  7853 I bt_hci_bdroid: init
09-01 11:16:34.649  7604  7853 I bt_vendor: bt-vendor : init
09-01 11:16:34.649  7604  7853 I bt_vendor: bt-vendor : get_bt_soc_type
09-01 11:16:34.649  7604  7853 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-01 11:16:34.649  7604  7853 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
09-01 11:16:34.649  7604  7853 D bt_userial_mct: userial_init
09-01 11:16:34.650  7604  7604 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-01 11:16:34.650  7604  7604 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-01 11:16:34.650  7604  7604 V BluetoothSapReceiver: SapReceiver onReceive 
09-01 11:16:34.650  7604  7604 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:16:34.650  7604  7604 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
09-01 11:16:34.656  7604  7897 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
09-01 11:16:34.656  7604  7897 I bt-btu  : btu_task pending for preload complete event
,09-01 11:16:34.659  7604  7853 D bt_hci_bdroid: set_power 1
09-01 11:16:34.659  7604  7853 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-01 11:16:34.659  7604  7853 I bt_vendor: Starting hciattach daemon
09-01 11:16:34.659  7604  7853 I bt_vendor: try to set true
09-01 11:16:34.648  7900  7900 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-01 11:16:34.648  7900  7900 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-01 11:16:34.692  7909  7909 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,09-01 11:16:34.701  1034  1379 V AlarmManager: ELAPSED_WAKEUP set : Alarm{1ebc4ed8 type 2 when 198255 com.google.android.gms} when 198255
09-01 11:16:34.712   309  7913 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,09-01 11:16:34.728  1034  1094 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,09-01 11:16:34.758  7924  7924 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,09-01 11:16:34.769  7925  7925 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
09-01 11:16:34.801  7929  7929 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-01 11:16:34.819  7930  7930 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,09-01 11:16:34.842  7931  7931 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-01 11:16:34.856  7933  7933 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,09-01 11:16:34.882  7935  7935 I libmdmdetect: ESOC framework not supported
,09-01 11:16:34.890  7935  7935 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
09-01 11:16:34.901  7935  7935 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
09-01 11:16:34.901  7935  7935 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
09-01 11:16:34.901  7935  7935 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
09-01 11:16:34.901  7935  7935 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
09-01 11:16:34.901  7935  7935 D bthci_qcomm_common: [BTUI]     LE: Class 2
09-01 11:16:34.901  7935  7935 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
09-01 11:16:34.901  7935  7935 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
,09-01 11:16:34.953  7935  7936 E QC-QMI  : qmi_client [7935] 15: failed to locate client data
,09-01 11:16:34.954   448   448 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
,09-01 11:16:34.954   448   448 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
09-01 11:16:35.019  7940  7940 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,09-01 11:16:35.060  7941  7941 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-01 11:16:35.116  7604  7853 I bt_vendor: bluetooth satus is on
09-01 11:16:35.116  7604  7853 D bt_hci_bdroid: preload
09-01 11:16:35.116  7604  7899 D bt_userial_mct: userial_open(port:0)
09-01 11:16:35.116  7604  7899 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,09-01 11:16:35.121  7604  7899 I bt_vendor: Done intiailizing UART
09-01 11:16:35.125  7604  7899 I bt_vendor: Done intiailizing UART
,09-01 11:16:35.126  7604  7899 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
09-01 11:16:35.126  7604  7899 I bt_vendor: Bluetooth Firmware and transport layer are initialized
09-01 11:16:35.126  7604  7946 D bt_userial_mct: Entering userial_read_thread()
09-01 11:16:35.126  7604  7897 I bt-btu  : btu_task received preload complete event
09-01 11:16:35.127  7604  7897 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
09-01 11:16:35.127  7604  7897 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
09-01 11:16:35.133  7604  7897 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
,09-01 11:16:35.142  7604  7897 I         : BTE_InitTraceLevels -- TRC_HCI
09-01 11:16:35.143  7604  7897 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-01 11:16:35.143  7604  7897 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-01 11:16:35.143  7604  7897 I         : BTE_InitTraceLevels -- TRC_AVDT
09-01 11:16:35.143  7604  7897 I         : BTE_InitTraceLevels -- TRC_AVRC
09-01 11:16:35.143  7604  7897 I         : BTE_InitTraceLevels -- TRC_A2D
09-01 11:16:35.143  7604  7897 I         : BTE_InitTraceLevels -- TRC_BNEP
09-01 11:16:35.143  7604  7897 I         : BTE_InitTraceLevels -- TRC_BTM
09-01 11:16:35.151  7604  7897 I         : BTE_InitTraceLevels -- TRC_HID_HOST
09-01 11:16:35.151  7604  7897 I         : BTE_InitTraceLevels -- TRC_GAP
09-01 11:16:35.151  7604  7897 I         : BTE_InitTraceLevels -- TRC_PAN
09-01 11:16:35.151  7604  7897 I         : BTE_InitTraceLevels -- TRC_SDP
09-01 11:16:35.151  7604  7897 I         : BTE_InitTraceLevels -- TRC_GATT
09-01 11:16:35.151  7604  7897 I         : BTE_InitTraceLevels -- TRC_SMP
09-01 11:16:35.152  7604  7897 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-01 11:16:35.152  7604  7897 I         : BTE_InitTraceLevels -- TRC_BTIF
09-01 11:16:35.153  7627  7652 D UEI.SmartControl: Internal timer expired: 1
09-01 11:16:35.154  7627  7652 D UEI.SmartControl: unbind internal service
09-01 11:16:35.156  7627  7627 D UEI.SmartControl: Service.onUnbind: IControl
09-01 11:16:35.157  7627  7627 D UEI.SmartControl: Service.onDestroy
09-01 11:16:35.157  7627  7627 D UEI.SmartControl: Lock is in USE false
09-01 11:16:35.157  7627  7627 D UEI.SmartControl: unbind internal service
09-01 11:16:35.157  7627  7627 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@2b6f76ed
09-01 11:16:35.158  7627  7627 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
09-01 11:16:35.158  7627  7627 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
09-01 11:16:35.158  7627  7627 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
09-01 11:16:35.158  7627  7627 W System.err: 	at com.uei.control.Service.c(Unknown Source)
09-01 11:16:35.158  7627  7627 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
09-01 11:16:35.158  7627  7627 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
09-01 11:16:35.159  7627  7627 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
09-01 11:16:35.159  7627  7627 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
09-01 11:16:35.159  7627  7627 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 11:16:35.159  7627  7627 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-01 11:16:35.159  7627  7627 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-01 11:16:35.159  7627  7627 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 11:16:35.159  7627  7627 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-01 11:16:35.159  7627  7627 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-01 11:16:35.159  7627  7627 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-01 11:16:35.159  7627  7627 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@2b6f76ed
09-01 11:16:35.162  7627  7627 D serial_port: close(fd = 25)
,09-01 11:16:35.170  7627  7627 I UEI.SmartControl: Serial port is closed.
09-01 11:16:35.170  7627  7627 I UEI.SmartControl: Serial port is closed.
09-01 11:16:35.170  7627  7627 D UEI.SmartControl: Blaster closed
09-01 11:16:35.171  7627  7627 D UEI.SmartControl: Shut down QS...
09-01 11:16:35.171  7627  7627 D UEI.SmartControl: Stopping QS lib
09-01 11:16:35.171  7627  7627 D UEI.SmartControl: QS lib stop result = true
09-01 11:16:35.171  7627  7627 D UEI.SmartControl: Stopped QS lib
09-01 11:16:35.172  7627  7627 D UEI.SmartControl: Stopped file observer...
09-01 11:16:35.172  7627  7627 D UEI.SmartControl: QS shutdown complete
09-01 11:16:35.206  7604  7897 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
09-01 11:16:35.206  7604  7897 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0234061 
09-01 11:16:35.206  7604  7897 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0234061 
,09-01 11:16:35.232  7604  7857 E bt-btif : Calling BTA_HhEnable
09-01 11:16:35.232  7604  7857 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
09-01 11:16:35.232  7604  7857 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,09-01 11:16:35.236  7604  7897 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
09-01 11:16:35.236  7604  7897 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
09-01 11:16:35.236  7604  7897 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
09-01 11:16:35.239  1034  1034 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-01 11:16:35.240  1034  1034 D BluetoothManagerService: Stored Bluetooth name: G3
09-01 11:16:35.236  7604  7897 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
09-01 11:16:35.240  7604  7897 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
09-01 11:16:35.241  7604  7857 D BluetoothAdapterProperties: Name is: G3
09-01 11:16:35.243  7604  7857 D BluetoothAdapterProperties: Scan Mode:20
09-01 11:16:35.243  7604  7857 D BluetoothAdapterProperties: Discoverable Timeout:120
09-01 11:16:35.243  7604  7857 D bt_hci_bdroid: postload
09-01 11:16:35.244  7604  7899 D bt_hci_bdroid: Used up Tx Cmd credits
09-01 11:16:35.247  7604  7857 D bte_conf: Device ID record 1 : primary
09-01 11:16:35.247  7604  7857 D bte_conf:   vendorId            = 00c4
09-01 11:16:35.247  7604  7857 D bte_conf:   vendorIdSource      = 0001
09-01 11:16:35.247  7604  7857 D bte_conf:   product             = 13a1
09-01 11:16:35.247  7604  7857 D bte_conf:   version             = 1000
09-01 11:16:35.247  7604  7857 D bte_conf:   clientExecutableURL = 
09-01 11:16:35.247  7604  7857 D bte_conf:   serviceDescription  = 
09-01 11:16:35.247  7604  7857 D bte_conf:   documentationURL    = 
09-01 11:16:35.247  7604  7857 D bte_conf: bte_load_did_conf no section named DID2.
,09-01 11:16:35.256  7604  7897 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
09-01 11:16:35.258  7604  7899 D bt_hci_bdroid: Used up Tx Cmd credits
09-01 11:16:35.262  7604  7899 D bt_hci_bdroid: Used up Tx Cmd credits
,09-01 11:16:35.265  7604  7853 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-01 11:16:35.265  7604  7853 D BluetoothAdapterProperties: ScanMode =  20
09-01 11:16:35.265  7604  7853 D BluetoothAdapterProperties: State =  11
09-01 11:16:35.266  7604  7853 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
09-01 11:16:35.266  7604  7853 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
09-01 11:16:35.266  7604  7853 D BluetoothAdapterProperties: Setting state to 12
09-01 11:16:35.266  7604  7853 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-01 11:16:35.267  7604  7857 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-01 11:16:35.258  7951  7951 W sh      : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-01 11:16:35.258  7951  7951 W sh      : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-01 11:16:35.276  7604  7853 I BluetoothAdapterState: Entering On State
,09-01 11:16:35.283  7604  7897 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-01 11:16:35.283  7604  7897 W bt-smp  : Plain text(LSB ~ MSB) = 1b 25 7d 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-01 11:16:35.283  7604  7897 W bt-smp  : Encrypted text(LSB ~ MSB) = 3d e4 a5 9e 15 b8 95 4f 7e 00 ca cc df 54 83 43 
09-01 11:16:35.284  7604  7899 D bt_hci_bdroid: Used up Tx Cmd credits
09-01 11:16:35.284  7604  7897 W bt-btm  : Stopping oneshot timer
09-01 11:16:35.284  7604  7946 E bt_mct  : hci lib postload completed
09-01 11:16:35.285  1034  1096 D BluetoothManagerService: Message: 60
09-01 11:16:35.285  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
09-01 11:16:35.285  1034  1096 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
09-01 11:16:35.287  7604  7857 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-01 11:16:35.308  7604  7857 D BluetoothAdapterProperties: Discoverable Timeout:120
09-01 11:16:35.309  7604  7857 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
,09-01 11:16:35.318  7604  7897 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-01 11:16:35.318  7604  7897 W bt-smp  : Plain text(LSB ~ MSB) = e8 3d 78 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-01 11:16:35.318  7604  7897 W bt-smp  : Encrypted text(LSB ~ MSB) = a0 22 c0 31 cd a0 79 ee f4 43 0a c5 5b aa 23 67 
09-01 11:16:35.319  7604  7897 W bt-btm  : Stopping oneshot timer
09-01 11:16:35.324  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:16:35.324  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:16:35.324  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-01 11:16:35.324  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 11:16:35.324  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:16:35.324  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:16:35.324  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:16:35.324  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-01 11:16:35.327  7604  7853 D LGBluetoothServiceAdapter: [BTUI] OnState
09-01 11:16:35.327  7604  7853 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
09-01 11:16:35.327  7604  7853 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
09-01 11:16:35.332  7604  7853 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
09-01 11:16:35.332  7604  7853 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
09-01 11:16:35.333  7604  7897 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-01 11:16:35.333  7604  7897 W bt-smp  : Plain text(LSB ~ MSB) = 3c 6e 53 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-01 11:16:35.333  7604  7897 W bt-smp  : Encrypted text(LSB ~ MSB) = 16 82 00 a8 43 4f a6 00 74 98 ac 32 39 34 e2 10 
09-01 11:16:35.333  7604  7897 W bt-btm  : Stopping oneshot timer
09-01 11:16:35.337  6682  6682 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-01 11:16:35.346  7604  7897 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-01 11:16:35.346  7604  7897 W bt-smp  : Plain text(LSB ~ MSB) = 38 e3 70 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-01 11:16:35.347  7604  7897 W bt-smp  : Encrypted text(LSB ~ MSB) = d3 bf 12 4b ff 5c e6 83 02 01 27 a8 91 7e 7c 52 
09-01 11:16:35.347  7604  7897 W bt-btm  : Stopping oneshot timer
09-01 11:16:35.369  6814  6830 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-01 11:16:35.386  7604  7897 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-01 11:16:35.386  7604  7897 W bt-smp  : Plain text(LSB ~ MSB) = 37 81 50 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-01 11:16:35.386  7604  7897 W bt-smp  : Encrypted text(LSB ~ MSB) = a6 d2 6e 15 65 91 14 df 6d 73 5e fa f9 6b 02 e6 
09-01 11:16:35.386  7604  7897 W bt-btm  : Stopping oneshot timer
,09-01 11:16:35.400  7956  7956 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,09-01 11:16:35.408  1850  2452 D BluetoothHeadset: onBluetoothStateChange: up=true
09-01 11:16:35.410  1850  1850 D BluetoothHeadset: Proxy object connected
09-01 11:16:35.411  1850  1865 D BluetoothHeadset: onBluetoothStateChange: up=true
09-01 11:16:35.414  1850  1850 D BluetoothHeadset: Proxy object connected
09-01 11:16:35.416  1034  1096 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-01 11:16:35.419  1034  1034 D BluetoothHeadset: Proxy object connected
09-01 11:16:35.419  6814  6830 D BluetoothPan: onBluetoothStateChange on: true
09-01 11:16:35.419  6814  6830 D BluetoothPan: onBluetoothStateChange call bindService
09-01 11:16:35.424  1034  1096 D BluetoothA2dp: onBluetoothStateChange: up=true
09-01 11:16:35.426  1034  1034 D BluetoothA2dp: Proxy object connected
09-01 11:16:35.427  1850  1866 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-01 11:16:35.432  6814  6814 D BluetoothHeadset: Proxy object connected
09-01 11:16:35.432  6814  6814 D HeadsetProfile: Bluetooth service connected
09-01 11:16:35.432  1850  1850 D BluetoothHeadset: Proxy object connected
09-01 11:16:35.437  6814  6829 D BluetoothPbap: onBluetoothStateChange: up=true
09-01 11:16:35.442  6814  7514 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-01 11:16:35.449  6814  6814 D BluetoothPan: BluetoothPAN Proxy object connected
09-01 11:16:35.449  6814  6814 D PanProfile: Bluetooth service connected
09-01 11:16:35.461  6814  6830 D BluetoothMap: onBluetoothStateChange: up=true
,09-01 11:16:35.463  6814  6814 D BluetoothInputDevice: Proxy object connected
09-01 11:16:35.463  6814  6814 D HidProfile: Bluetooth service connected
09-01 11:16:35.465  6814  6829 D BluetoothA2dp: onBluetoothStateChange: up=true
09-01 11:16:35.466  6814  6814 D BluetoothMap: Proxy object connected
09-01 11:16:35.466  6814  6814 D MapProfile: Bluetooth service connected
09-01 11:16:35.466  6814  6814 D BluetoothMap: getConnectedDevices()
09-01 11:16:35.467  7604  7620 V BluetoothMapService: getConnectedDevices()
09-01 11:16:35.468  1034  1096 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
09-01 11:16:35.469  1034  1096 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
09-01 11:16:35.472  1939  1939 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:16:35.472  1939  2084 D LGBluetoothAPIService: Message: 1
09-01 11:16:35.472  1939  2084 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
09-01 11:16:35.473  6814  6814 D BluetoothA2dp: Proxy object connected
09-01 11:16:35.473  6814  6814 D A2dpProfile: Bluetooth service connected
09-01 11:16:35.478  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,09-01 11:16:35.490  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:16:35.497  1939  2084 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
,09-01 11:16:35.499  7604  7604 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:16:35.499  7604  7604 D BluetoothMapService: STATE_ON
09-01 11:16:35.501  7604  7604 D LGBluetoothAPIServer: [BTUI] onCreate()
09-01 11:16:35.501  7604  7604 D LGBluetoothAPIServer: [BTUI] onBind()
09-01 11:16:35.503  1939  1939 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
09-01 11:16:35.503  1939  2084 D LGBluetoothAPIService: Message: 100
09-01 11:16:35.503  1939  2084 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
09-01 11:16:35.505  6814  6814 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
09-01 11:16:35.506  6814  6814 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,09-01 11:16:35.520  6814  6814 D DockEventReceiver: finishStartingService: stopping service
09-01 11:16:35.521  7604  7604 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15e15917
09-01 11:16:35.521  7604  7604 V BluetoothPbapService: Pbap Service onCreate
09-01 11:16:35.521  7604  7604 V BluetoothPbapService: Starting PBAP service
,09-01 11:16:35.525  7604  7604 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
09-01 11:16:35.525  7604  7604 V BluetoothPbapService: Pbap Service onBind
09-01 11:16:35.526  7604  7604 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:16:35.526  6814  6814 D BluetoothPbap: Proxy object connected
09-01 11:16:35.526  6814  6814 D PbapServerProfile: Bluetooth service connected
09-01 11:16:35.526  7604  7604 V BluetoothPbapService: state: 12
09-01 11:16:35.527  7604  7604 V BluetoothMapService: Handler(): got msg=1
09-01 11:16:35.527  7604  7604 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
09-01 11:16:35.528  7604  7604 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-01 11:16:35.528  7604  7604 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:16:35.528  7604  7604 V BluetoothPbapReceiver: ***********state = 12
09-01 11:16:35.528  7604  7976 D BluetoothMapMasInstance: MAS initSocket()
09-01 11:16:35.529  7604  7976 D BluetoothMapMasInstance:   masId = 00
09-01 11:16:35.529  7604  7976 D BluetoothMapMasInstance:   msgTypes = 0e
09-01 11:16:35.529  7604  7976 D BluetoothMapMasInstance:   masName = SMS/MMS
09-01 11:16:35.529  7604  7976 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
09-01 11:16:35.531  1034  1650 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:16:35.531  2180  2180 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-01 11:16:35.532  7604  7604 V BluetoothPbapService: Handler(): got msg=1
09-01 11:16:35.532  2180  2180 D c       : Getting all permits...
09-01 11:16:35.532  2180  2180 D a       : Opening database...
09-01 11:16:35.535  7604  7604 V BluetoothPbapService: Pbap Service startRfcommSocketListener
,09-01 11:16:35.536  2180  2180 D a       : Opening database auth.proximity.permit_store...
09-01 11:16:35.536  7604  7977 V BluetoothPbapService: Pbap Service initSocket
09-01 11:16:35.537  2180  2180 D a       : Closing database...
09-01 11:16:35.538  7604  7976 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-01 11:16:35.541  1034  1893 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:16:35.542  7604  7976 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
09-01 11:16:35.542  7604  7976 V BluetoothMapMasInstance: Succeed to create listening socket 
09-01 11:16:35.542  7604  7976 D BluetoothMapMasInstance: Accepting socket connection...
09-01 11:16:35.542  7604  7857 D BluetoothAdapterProperties: Scan Mode:21
09-01 11:16:35.543  7604  7857 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
09-01 11:16:35.543  7604  7977 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-01 11:16:35.546  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:16:35.553  7604  7977 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
,09-01 11:16:35.554  7604  7977 V BluetoothPbapService: Succeed to create listening socket 
09-01 11:16:35.554  7604  7977 V BluetoothPbapService: Accepting socket connection...
09-01 11:16:35.556  6814  6814 D BluetoothPermissionRequest: onReceive
09-01 11:16:35.558  6814  6814 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-01 11:16:35.560  6814  6814 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-01 11:16:35.563  7604  7604 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
09-01 11:16:35.565  7604  7604 I LGBluetoothOppAdapter: [BTUI] startOppService()
,09-01 11:16:35.572  7604  7604 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
09-01 11:16:35.594  7604  7604 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,09-01 11:16:35.594  7604  7604 V BtOppService: onCreate
,09-01 11:16:35.599  7604  7604 V BluetoothOppNotification: send message
09-01 11:16:35.601  7604  7604 V BtOppService: Starting RfcommListener
09-01 11:16:35.607  7604  7604 D BluetoothOppPreference: Dumping Names:  
09-01 11:16:35.607  7604  7604 D BluetoothOppPreference: {}
09-01 11:16:35.607  7604  7604 D BluetoothOppPreference: Dumping Channels:  
09-01 11:16:35.607  7604  7604 D BluetoothOppPreference: {}
09-01 11:16:35.607  7604  7604 V BtOppService: onStartCommand
09-01 11:16:35.610  7604  7985 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-01 11:16:35.612  7604  7985 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
,09-01 11:16:35.613  7604  7982 V BtOppService: Deleted complete outbound shares, number =  0
09-01 11:16:35.614  7604  7604 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:16:35.614  7604  7604 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-01 11:16:35.615  7604  7982 V BtOppService: Deleted complete inbound failed shares, number = 0
09-01 11:16:35.615  7604  7982 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
09-01 11:16:35.615  7604  7985 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@109a3d00 on behalf of 
09-01 11:16:35.617  7604  7985 V BluetoothOppNotification: update too frequent, put in queue
09-01 11:16:35.618  7604  7982 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3e422939 on behalf of 
09-01 11:16:35.619  7604  7604 V BluetoothOppNotification: new notify threadi!
09-01 11:16:35.619  7604  7985 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-01 11:16:35.619  7604  7985 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-01 11:16:35.620  7604  7604 V BluetoothOppNotification: send delay message
09-01 11:16:35.620  7604  7604 V BtOppService: start RfcommListener
09-01 11:16:35.620  7604  7986 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-01 11:16:35.622  7604  7986 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@5d11b7e on behalf of 
09-01 11:16:35.622  7604  7985 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@31dd48df on behalf of 
,09-01 11:16:35.622  7604  7986 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-01 11:16:35.624  7604  7604 V BtOppService: RfcommListener started
09-01 11:16:35.624  7604  7986 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-01 11:16:35.625  7604  7986 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@22e6292c on behalf of 
09-01 11:16:35.628  7604  7604 V BtOppService: ContentObserver received notification
09-01 11:16:35.628  7604  7604 V BtOppService: ContentObserver received notification
09-01 11:16:35.628  7604  7987 V BtOppRfcommListener: Starting RFCOMM listener....
09-01 11:16:35.629  1034  1917 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:16:35.631  7604  7987 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-01 11:16:35.631  7604  7985 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-01 11:16:35.631  7604  7985 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-01 11:16:35.633  7604  7985 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@931ff5 on behalf of 
09-01 11:16:35.633  7604  7987 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=75
09-01 11:16:35.633  7604  7987 V BtOppRfcommListener: Started RFCOMM listener....
09-01 11:16:35.634  7604  7987 I BtOppRfcommListener: Accept thread started.
09-01 11:16:35.634  7604  7987 V BtOppRfcommListener: Accepting connection...
09-01 11:16:35.634  7604  7985 V BluetoothOppNotification: update too frequent, put in queue
09-01 11:16:35.635  7604  7985 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
,09-01 11:16:35.637  7604  7986 V BluetoothOppNotification: outbound: succ-0  fail-0
09-01 11:16:35.639  7604  7604 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15e15917
09-01 11:16:35.639  7604  7604 V BluetoothFtpService: Ftp Service onCreate
09-01 11:16:35.639  7604  7604 I BluetoothFtpService: Ftp Service onCreate
09-01 11:16:35.639  1034  1034 I art     : Explicit concurrent mark sweep GC freed 28556(1416KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 2.457ms total 165.610ms
09-01 11:16:35.639  7604  7604 V BluetoothFtpService: Ftp Service onStartCommand
09-01 11:16:35.640  7604  7986 V BluetoothOppNotification: outbound notification was removed.
09-01 11:16:35.640  7604  7604 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:16:35.640  1034  1034 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
09-01 11:16:35.640  7604  7986 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-01 11:16:35.640  7604  7604 V BluetoothFtpService: Starting Listening on sockets
09-01 11:16:35.640  7604  7604 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-01 11:16:35.640  1034  1096 D BluetoothManagerService: Message: 40
09-01 11:16:35.640  7604  7604 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-01 11:16:35.640  7604  7604 V BluetoothSapReceiver: SapReceiver onReceive 
09-01 11:16:35.640  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
09-01 11:16:35.640  7604  7604 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:16:35.641  7604  7986 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@347793fb on behalf of 
09-01 11:16:35.641  7604  7986 V BluetoothOppNotification: inbound: succ-0  fail-0
09-01 11:16:35.641  7604  7604 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
09-01 11:16:35.641  7604  7604 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-01 11:16:35.642  7604  7986 V BluetoothOppNotification: inbound notification was removed.
09-01 11:16:35.642  7604  7986 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-01 11:16:35.643  7604  7986 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3522ac18 on behalf of 
09-01 11:16:35.643  7604  7604 V BluetoothFtpService: Handler(): got msg=1
09-01 11:16:35.644  7604  7604 V BluetoothFtpService: Ftp Service startRfcommSocketListener
09-01 11:16:35.644  7604  7604 V BluetoothFtpService: Ftp Service initSocket
09-01 11:16:35.646  1034  1780 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:16:35.646  7604  7604 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-01 11:16:35.650  7604  7604 V BluetoothFtpService: Succeed to create listening socket on channel 20
,09-01 11:16:35.653  7604  7988 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
09-01 11:16:35.666  7604  7604 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15e15917
09-01 11:16:35.666  7604  7604 V BluetoothSapService: Sap Service onCreate
09-01 11:16:35.668  7604  7604 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:16:35.668  7604  7604 V BluetoothSapService: state: 12
09-01 11:16:35.668  7604  7604 V BluetoothSapService: Starting SAP server process
,09-01 11:16:35.658  7989  7989 W sapd    : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-01 11:16:35.658  7989  7989 W sapd    : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-01 11:16:35.671  7604  7604 V BluetoothSapService: SAP Service startRfcommListenerThread
09-01 11:16:35.674  7604  7990 V BluetoothSapService: Sap Service initRfcommSocket
09-01 11:16:35.675  1034  1987 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:16:35.677  7989  7989 V BT_SAP  : Event pipe created
09-01 11:16:35.677  7989  7989 V BT_SAP  : create_server_socket qcom.sap.server
09-01 11:16:35.677  7989  7989 V BT_SAP  : created socket fd 6
09-01 11:16:35.677  7604  7990 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-01 11:16:35.679  7604  7990 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
09-01 11:16:35.680  7604  7990 V BluetoothSapService: Succeed to create listening socket 
09-01 11:16:35.680  7604  7990 V BluetoothSapService: Accepting socket connection...
,09-01 11:16:35.946  6682  6759 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:16:35.946  6682  6759 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:16:35.946  6682  6759 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-01 11:16:35.946  6682  6759 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 11:16:35.946  6682  6759 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:16:35.946  6682  6759 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:16:35.946  6682  6759 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:16:35.946  6682  6759 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-01 11:16:35.963  6682  6759 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-01 11:16:35.967  6682  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 11:16:35.967  6682  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@faaaf91 added. We now have 8 listener(s)
09-01 11:16:35.967  6682  6759 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 11:16:35.971  1034  1987 D WifiServiceImplEx: setWifiEnabled: false pid=6682, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-01 11:16:35.971  1034  1987 D WifiService: setWifiEnabled: false pid=6682, uid=10118
09-01 11:16:35.971  1034  1987 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-01 11:16:35.976  6682  6759 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:16:35.977  1034  1780 D WifiServiceImplEx: setWifiEnabled: true pid=6682, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-01 11:16:35.977  1034  1780 D WifiService: setWifiEnabled: true pid=6682, uid=10118
09-01 11:16:35.977  1034  1780 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-01 11:16:35.990  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-01 11:16:35.991  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-01 11:16:35.993  1034  1537 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
09-01 11:16:35.993  1034  1537 I LGFTMITEM: [GET_FTM][id=6], offset=12288
09-01 11:16:35.994  1034  1034 D Ulp_jni : JNI:system_update. Event-4
09-01 11:16:35.996  1034  1537 E WifiUtil: wfc_util_ffile_check_copy(): pid[1034] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
09-01 11:16:35.996  1034  1537 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-01 11:16:35.996  1034  1537 E WifiUtil: wfc_util_ffile_check_copy(): pid[1034] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
09-01 11:16:35.996  1034  1537 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-01 11:16:35.996  1034  1537 I WifiUtil: Intf0MacAddress=C49A027FFB5D
09-01 11:16:35.996  1034  1537 E WifiHW  : unknown target_country: EU , set to default
09-01 11:16:35.996  1034  1537 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
09-01 11:16:35.996  1034  1537 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
09-01 11:16:35.996  1034  1537 I WifiUtil: gEnableBmps=1
,09-01 11:16:36.595   309   893 D SoftapController: Softap fwReload - Ok
,09-01 11:16:36.609  1034  1096 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-01 11:16:36.613  1034  1537 E NetdConnector: NDC Command {83 softap fwreload wlan0 STA} took too long (610ms)
09-01 11:16:36.621  7604  7604 V BluetoothOppNotification: new notify threadi!
09-01 11:16:36.621  7604  7604 V BluetoothOppNotification: send delay message
,09-01 11:16:36.625   309   893 D CommandListener: Setting iface cfg
09-01 11:16:36.625   309   893 D CommandListener: Trying to bring down wlan0
09-01 11:16:36.635   309   893 D CommandListener: Clearing all IP addresses on wlan0
,09-01 11:16:36.641  1034  1537 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
09-01 11:16:36.638  8011  8011 W wpa_supplicant: type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-01 11:16:36.659  1034  1537 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-01 11:16:36.659  1034  1537 E WifiStateMachine: useWiFiOffloading() : false
09-01 11:16:36.659  1034  1537 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-01 11:16:36.648  8011  8011 W wpa_supplicant: type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-01 11:16:36.667  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
09-01 11:16:36.679  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-01 11:16:36.688  1939  1939 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
09-01 11:16:36.698  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:16:36.717  1034  1537 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-01 11:16:36.718  1034  1537 D WifiMonitor: connecting to supplicant
,09-01 11:16:36.719  6814  6814 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-01 11:16:36.719  6814  6814 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-01 11:16:36.720  6814  6814 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-01 11:16:36.720  6814  6814 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-01 11:16:36.722  7604  8010 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-01 11:16:36.723  7604  8010 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@29a271c4 on behalf of 
09-01 11:16:36.723  6814  6814 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-01 11:16:36.724  7604  8010 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-01 11:16:36.725  6814  6814 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-01 11:16:36.725  6814  6814 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
09-01 11:16:36.725  6814  6814 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-01 11:16:36.725  6814  6814 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-01 11:16:36.726  6814  6814 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-01 11:16:36.726  6814  6814 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
09-01 11:16:36.727  6814  6814 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-01 11:16:36.728  7604  8010 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-01 11:16:36.731  8011  8011 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-01 11:16:36.752  7604  8010 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3a6c58ad on behalf of 
09-01 11:16:36.752  7604  8010 V BluetoothOppNotification: outbound: succ-0  fail-0
09-01 11:16:36.754  7604  8010 V BluetoothOppNotification: outbound notification was removed.
09-01 11:16:36.754  7604  8010 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-01 11:16:36.756  7604  8010 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@25f4a7e2 on behalf of 
09-01 11:16:36.756  7604  8010 V BluetoothOppNotification: inbound: succ-0  fail-0
09-01 11:16:36.758  7604  8010 V BluetoothOppNotification: inbound notification was removed.
09-01 11:16:36.758  7604  8010 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-01 11:16:36.759  7604  8010 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2f1e8773 on behalf of 
,09-01 11:16:36.771  8011  8011 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-01 11:16:36.771  8011  8011 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,09-01 11:16:36.773  1034  1993 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8028 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
09-01 11:16:36.775  1034  1096 D Tethering: InitialState.processMessage what=4
09-01 11:16:36.775  1034  1096 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-01 11:16:36.826  8011  8011 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-01 11:16:36.871  1034  1952 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8051 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-01 11:16:36.877  8028  8049 W FormManager: Network not available. Please check & try again.
09-01 11:16:36.882  8028  8050 V FormManager: Network unavailable.
09-01 11:16:36.883  8028  8050 V FormManager: Network unavailable.
,09-01 11:16:36.889   349   349 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 378us total 16.739ms
09-01 11:16:36.900  8011  8011 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
09-01 11:16:36.903   349   349 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 286us total 13.666ms
,09-01 11:16:36.905  8011  8011 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
09-01 11:16:36.906  1034  1537 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
09-01 11:16:36.907  1034  8069 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
09-01 11:16:36.907  1034  8069 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
09-01 11:16:36.907  1034  8069 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
09-01 11:16:36.907  1034  8069 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
09-01 11:16:36.907  1034  1537 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
09-01 11:16:36.908  1034  1537 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
09-01 11:16:36.909  1034  1537 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
09-01 11:16:36.909  1034  1537 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-01 11:16:36.909  1034  1537 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-01 11:16:36.910  1034  1537 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-01 11:16:36.911  1034  1537 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-01 11:16:36.911  1034  1537 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
09-01 11:16:36.911  1034  1537 D WifiNative-wlan0: doString: [DRIVER MACADDR]
09-01 11:16:36.912  1034  1537 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
09-01 11:16:36.912  1034  1537 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
09-01 11:16:36.912  1034  1537 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
09-01 11:16:36.913  1034  1537 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-01 11:16:36.913  1034  1537 E WifiStateMachine: useWiFiOffloading() : false
09-01 11:16:36.913  1034  1537 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-01 11:16:36.913  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:16:36.913  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:16:36.913  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:16:36.914  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:16:36.914  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-01 11:16:36.914  1034  1537 D WifiNative-wlan0: doBoolean: SET update_config 1
,09-01 11:16:36.915  1034  1537 D WifiNative-wlan0: SET update_config 1: returned true
09-01 11:16:36.915  1034  1537 D WifiConfigStore: Loading config and enabling all networks 
09-01 11:16:36.915  1034  1537 D WifiNative-wlan0: doString: [LIST_NETWORKS]
09-01 11:16:36.915  1034  1537 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
09-01 11:16:36.917   349   349 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 249us total 12.318ms
09-01 11:16:36.917  1939  1939 D WfdService: Waiting for WifiP2p enabling
09-01 11:16:36.918  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:16:36.919  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
09-01 11:16:36.920  1034  1541 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
09-01 11:16:36.922  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:16:36.922  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:16:36.922  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-01 11:16:36.922  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:16:36.922  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:16:36.922  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:16:36.922  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:16:36.922  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 11:16:36.922  1034  1537 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
09-01 11:16:36.923  6682  6682 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-01 11:16:36.929  1034  1537 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
09-01 11:16:36.929  1034  1537 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-01 11:16:36.930  1034  1537 D WifiStateMachine: enableVerboseLogging : level 2
09-01 11:16:36.930  1034  1537 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
09-01 11:16:36.930  1034  1537 D WifiNative-wlan0: SET device_name g3_global_com: returned true
09-01 11:16:36.930  1034  1537 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
09-01 11:16:36.930  1034  1537 D WifiNative-wlan0: SET manufacturer LGE: returned true
09-01 11:16:36.931  1034  1537 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
09-01 11:16:36.931  1034  1537 D WifiNative-wlan0: SET model_name LG-D855: returned true
09-01 11:16:36.931  1034  1537 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
,09-01 11:16:36.931  1034  1537 D WifiNative-wlan0: SET model_number LG-D855: returned true
09-01 11:16:36.931  1034  1537 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
09-01 11:16:36.931  1034  1537 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
09-01 11:16:36.931  1034  1537 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
09-01 11:16:36.932  1034  1537 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
09-01 11:16:36.932  1034  1537 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
09-01 11:16:36.932  1034  1537 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
09-01 11:16:36.933  1939  1939 D WfdsService: Supplicant Connection state is changed : true
09-01 11:16:36.933  1939  2284 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
09-01 11:16:36.933  1034  1537 D WifiStateMachine: Setting OUI to DA-A1-19
09-01 11:16:36.933  1939  2284 D WfdsService: Set the WFDS Monitor: true
,09-01 11:16:36.933  1939  2284 D WfdsMonitor: WfdsMonitorThread create
09-01 11:16:36.933  1034  1537 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
09-01 11:16:36.933  1939  2284 D WfdsMonitor: WFDS Monitor is created and started
09-01 11:16:36.933  1939  2284 D WfdsService: WiFi: Supplicant connection re-established
09-01 11:16:36.933  7657  7657 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:16:36.933  1034  1537 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
09-01 11:16:36.933  1034  1537 D WifiNative-HAL: Setting external_sim to 1
,09-01 11:16:36.933  1034  1537 D WifiNative-wlan0: doBoolean: SET external_sim 1
09-01 11:16:36.934  1034  1537 D WifiNative-wlan0: SET external_sim 1: returned true
09-01 11:16:36.934  1034  1537 I WifiNative-HAL: startHal
09-01 11:16:36.934  1034  1537 D wifi    : setting scan oui 0x956cb220
09-01 11:16:36.934  1034  1537 D WifiStateMachine: Setting OUI to DA-A1-19
09-01 11:16:36.934  1034  1537 I WifiNative-HAL: startHal
09-01 11:16:36.934  1939  8071 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
09-01 11:16:36.934  1034  1537 D wifi    : setting scan oui 0x956cb220
09-01 11:16:36.934  1034  1537 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
09-01 11:16:36.934  1939  8071 E CtrlSupplicant: Succeed to open control connection
09-01 11:16:36.935  1034  1537 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
09-01 11:16:36.935  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
09-01 11:16:36.935  1939  8071 E CtrlSupplicant: Succeed to open monitor connection
09-01 11:16:36.935  8011  8011 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
09-01 11:16:36.935  1939  8071 D WfdsMonitor: Supplicant connection established
09-01 11:16:36.935  1939  2284 D WfdsService: Connected to the supplicant for wfds
09-01 11:16:36.935  1034  1537 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
09-01 11:16:36.935  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
,09-01 11:16:36.935  8011  8011 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-01 11:16:36.935  1034  1537 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-01 11:16:36.936  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
09-01 11:16:36.936  8011  8011 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
09-01 11:16:36.936  1034  1537 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
09-01 11:16:36.936  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-01 11:16:36.936  8011  8011 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-01 11:16:36.936  1034  1537 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-01 11:16:36.936  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-01 11:16:36.936  8011  8011 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-01 11:16:36.936  1034  1537 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-01 11:16:36.936  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
09-01 11:16:36.937  8011  8011 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
09-01 11:16:36.937  1034  1537 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
09-01 11:16:36.937  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-01 11:16:36.937  8011  8011 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-01 11:16:36.937  1034  1537 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-01 11:16:36.938  1034  1537 E WifiNative: : [200,497,982 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
09-01 11:16:36.938  1034  1537 D WifiNative-wlan0: doBoolean: RECONNECT
09-01 11:16:36.938  1034  1537 D WifiNative-wlan0: RECONNECT: returned true
09-01 11:16:36.938  1034  1537 D WifiNative-wlan0: doString: [STATUS]
09-01 11:16:36.938  1034  8069 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-01 11:16:36.938  1034  8069 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-01 11:16:36.938  1034  1537 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-01 11:16:36.939  1034  1537 D WifiNative-wlan0: doBoolean: SET ps 1
09-01 11:16:36.939  1034  1537 D WifiNative-wlan0: SET ps 1: returned true
09-01 11:16:36.939  1034  1536 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:16:36.939  1034  1034 D WifiScanningService: SCAN_AVAILABLE : 3
09-01 11:16:36.940  1034  1034 D RttService: SCAN_AVAILABLE : 3
09-01 11:16:36.940  1034  1556 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:16:36.940  1034  1555 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:16:36.940  1034  1555 I WifiNative-HAL: startHal
09-01 11:16:36.940  1034  1555 D wifi    : getting scan capabilities on interface[1] = 0x956cb220
09-01 11:16:36.940  8051  8051 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-01 11:16:36.940  1034  1555 D wifi    : failed to get capabilities : -3
09-01 11:16:36.940  1034  1555 E WifiScanningService: could not get scan capabilities
09-01 11:16:36.940   309   893 D CommandListener: Setting iface cfg
09-01 11:16:36.940   309   893 D CommandListener: Trying to bring up p2p0
09-01 11:16:36.941  1034  1536 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-01 11:16:36.941  1034  1536 D LGWifiP2pService: P2pEnablingState
09-01 11:16:36.941  1034  1536 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:16:36.941  1034  1536 D LGWifiP,2pService: P2p socket connection successful
09-01 11:16:36.941  1034  1536 D LGWifiP2pService: P2pEnabledState
09-01 11:16:36.941  1034  1537 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
09-01 11:16:36.941  1034  1537 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
09-01 11:16:36.941  1034  1537 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
09-01 11:16:36.942  1034  1537 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
09-01 11:16:36.942  1034  1536 D LGWifiP2pService: sending p2p connection changed broadcast
09-01 11:16:36.942  1034  1536 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
09-01 11:16:36.942  1034  1537 E WifiStateMachine:  DisconnectedState what:132106 1 0
09-01 11:16:36.943  1034  1537 E WifiStateMachine:  ConnectModeState what:132106 1 0
09-01 11:16:36.943  1034  1537 E WifiStateMachine:  DriverStartedState what:132106 1 0
09-01 11:16:36.943  1034  1537 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
09-01 11:16:36.943  1939  1939 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
09-01 11:16:36.943  8011  8011 E wpa_supplicant: nWIFIDualbandAPConnection: 1
09-01 11:16:36.943  1939  1939 D WfdsService: WifiP2pState is changed : true
09-01 11:16:36.943  1034  1537 E WifiStateMachine:  DisconnectedState what:132096 -100 0
09-01 11:16:36.943  1939  2284 D WfdsService: Receive the WFDS_ENABLE Method
09-01 11:16:36.943  1939  2284 D WfdsService: Set the WFDS Monitor: true
09-01 11:16:36.943  1939  2284 D WfdsService: Connected to the supplicant for wfds
09-01 11:16:36.944  1939  2284 D WfdsJNI : doCommand: WFDS_SET TRUE
,09-01 11:16:36.944  8011  8011 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
09-01 11:16:36.944  1939  2284 D WfdsService: selectPreferredScanChannel [36]
09-01 11:16:36.944  1939  2284 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
09-01 11:16:36.944  1939  1939 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
09-01 11:16:36.944  1034  1537 E WifiStateMachine:  ConnectModeState what:132096 -100 0
09-01 11:16:36.944  1034  1537 E WifiStateMachine:  DriverStartedState what:132096 -100 0
09-01 11:16:36.944  1939  1939 D WfdsService: isConnected: false
09-01 11:16:36.944  1034  1537 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
09-01 11:16:36.944  8011  8011 E wpa_supplicant: disconnect_rssi_lvl: -100
09-01 11:16:36.945  1034  1537 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
09-01 11:16:36.945  1034  1537 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
,09-01 11:16:36.945  1034  1537 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
09-01 11:16:36.945  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
09-01 11:16:36.945  6814  6814 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-01 11:16:36.945  1034  1536 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
09-01 11:16:36.946  1034  1536 D WifiNative-p2p0: doBoolean: SET device_name G3
09-01 11:16:36.946  1034  1536 D WifiNative-p2p0: SET device_name G3: returned true
09-01 11:16:36.946  1034  1536 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
09-01 11:16:36.946  1034  1536 D LGWifiP2pService: before postfix = G3
09-01 11:16:36.946  1034  1536 D WifiServerServiceExt: postfix byte check : 2
,09-01 11:16:36.946  1034  1536 D LGWifiP2pService: after postfix = G3
09-01 11:16:36.946  1034  1536 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
09-01 11:16:36.946  1034  1536 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
09-01 11:16:36.946  1034  1536 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
09-01 11:16:36.947  8011  8011 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-01 11:16:36.947  8011  8011 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-01 11:16:36.947  8011  8011 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-01 11:16:36.948  8011  8011 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:16:36.948  1034  1537 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
09-01 11:16:36.948  8011  8011 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,09-01 11:16:36.949  1939  8071 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-01 11:16:36.949  1939  8071 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-01 11:16:36.949  1034  8069 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-01 11:16:36.949  1034  8069 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-01 11:16:36.949  1034  8069 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-01 11:16:36.949  1034  8069 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-01 11:16:36.949  1034  8069 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-01 11:16:36.949  1034  8069 E WifiMonitor: WifiMonitor:p2p0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,09-01 11:16:36.949  1034  8069 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:16:36.949  1034  8069 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:16:36.949  1034  1537 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
09-01 11:16:36.949  1034  8069 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-01 11:16:36.949  1034  8069 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:16:36.949  1034  8069 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:16:36.949  1034  8069 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:16:36.949  1034  1536 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
,09-01 11:16:36.950  1034  1536 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
09-01 11:16:36.950  1034  1537 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
09-01 11:16:36.950  1034  1536 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
09-01 11:16:36.950  1034  1536 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
09-01 11:16:36.950  1034  1537 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
09-01 11:16:36.950  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
09-01 11:16:36.950  1034  1536 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
09-01 11:16:36.950  8011  8011 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
,09-01 11:16:36.950  8011  8011 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-01 11:16:36.950  1034  8069 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
09-01 11:16:36.951  1034  8069 E WifiMonitor: WifiMonitor:wlan0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-01 11:16:36.951  1034  8069 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-01 11:16:36.951  1034  8069 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-01 11:16:36.951  1034  1536 D WifiNative-HAL: p2pGetDeviceAddress
09-01 11:16:36.951  1034  1537 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
09-01 11:16:36.951  1034  1537 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
,09-01 11:16:36.951  1034  1537 D WifiNative-wlan0: BSS_FLUSH 0: returned true
09-01 11:16:36.951  1034  1537 D WifiNative-wlan0: doBoolean: SCAN
09-01 11:16:36.951  1034  1537 D WifiNative-wlan0: SCAN: returned false
09-01 11:16:36.952  1034  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=200512  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-01 11:16:36.952  1034  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=200513  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-01 11:16:36.952  1034  1537 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-01 11:16:36.953  1034  1537 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-01 11:16:36.953  1034  1537 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
,09-01 11:16:36.953  1034  1537 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-01 11:16:36.954  6814  6814 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-01 11:16:36.954  1034  1536 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
09-01 11:16:36.954  1034  1537 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-01 11:16:36.954  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-01 11:16:36.954  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-01 11:16:36.955  1034  1780 I ActivityManager: Killing 7121:com.lge.drmservice/u0a62 (adj 15): empty #17
09-01 11:16:36.955  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-01 11:16:36.956  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:16:36.956  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-01 11:16:36.956  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-01 11:16:36.990  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION,
09-01 11:16:36.990  1034  1034 D WifiServerServiceExt: setSupplicantStateSCANNING,
,09-01 11:16:36.990  1034  1536 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
09-01 11:16:36.990  1034  1536 D WifiNative-p2p0: doBoolean: P2P_FLUSH
09-01 11:16:36.992  1034  1536 D WifiNative-p2p0: P2P_FLUSH: returned true
09-01 11:16:36.993  1034  1536 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
09-01 11:16:36.993  1034  1536 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
,09-01 11:16:36.994  1034  1536 D WifiNative-p2p0: doString: [LIST_NETWORKS]
09-01 11:16:36.994  1034  1536 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
09-01 11:16:36.995  1034  1536 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
09-01 11:16:36.995  1034  2030 W libprocessgroup: failed to open /acct/uid_10062/pid_7121/cgroup.procs: No such file or directory
09-01 11:16:36.996  1939  1939 I WfdStateTracker: handleP2pThisDeviceChanged
09-01 11:16:36.996  1939  1939 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
09-01 11:16:36.996  1939  1939 D WfdsService: Update P2p Interface State: 3
09-01 11:16:37.001  6814  6814 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-01 11:16:37.001  6814  6814 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-01 11:16:37.001  6814  6814 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-01 11:16:37.002  6814  6814 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-01 11:16:37.002  6814  6814 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-01 11:16:37.002  6814  6814 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-01 11:16:37.002  6814  6814 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-01 11:16:37.002  6814  6814 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
,09-01 11:16:37.002  6814  6814 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-01 11:16:37.002  6814  6814 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-01 11:16:37.002  6814  6814 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-01 11:16:37.008  8051  8051 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-01 11:16:37.008  6682  6759 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:16:37.008  6682  6759 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:16:37.008  6682  6759 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-01 11:16:37.008  6682  6759 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:16:37.008  6682  6759 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:16:37.008  6682  6759 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:16:37.008  6682  6759 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:16:37.008  6682  6759 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 11:16:37.008  1034  1536 D WifiNative-p2p0: SAVE_CONFIG: returned true
09-01 11:16:37.008  1034  1536 D LGWifiP2pService: sending p2p persistent groups changed broadcast
09-01 11:16:37.009  1034  1536 D LGWifiP2pService: InactiveState
09-01 11:16:37.009  1034  1536 D LGWifiP2pService: InactiveState{ when=-62ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:16:37.009  1034  1536 D LGWifiP2pService: P2pEnabledState{ when=-62ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:16:37.009  1034  1536 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
09-01 11:16:37.011  6682  6759 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-01 11:16:37.011  8011  8011 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-01 11:16:37.012  8011  8011 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,09-01 11:16:37.012  1034  8069 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-01 11:16:37.012  1034  8069 E WifiMonitor: WifiMonitor:p2p0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-01 11:16:37.012  1034  8069 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-01 11:16:37.012  1034  8069 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-01 11:16:37.013  8011  8011 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-01 11:16:37.014  8011  8011 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:16:37.014  1034  1536 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
09-01 11:16:37.014  1034  1536 D LGWifiP2pService: InactiveState{ when=-20ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:16:37.014  1034  8069 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-01 11:16:37.014  1034  1536 D LGWifiP2pService: P2pEnabledState{ when=-20ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:16:37.014  1034  8069 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:16:37.014  1034  8069 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:16:37.014  1034  8069 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:16:37.014  1034  1536 D LGWifiP2pService: InactiveState{ when=-5ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:16:37.014  1034  1536 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:16:37.014  1034  1536 D LGWifiP2pService: DefaultState{ when=-5ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:16:37.014  6682  6759 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
09-01 11:16:37.015  6682  6759 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
09-01 11:16:37.015  8011  8011 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:16:37.015  1034  8069 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-01 11:16:37.015  1034  8069 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:16:37.015  1034  8069 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:16:37.015  1034  8069 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:16:37.015  1939  8071 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-01 11:16:37.015  1939  8071 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-01 11:16:37.015  1939  8071 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-01 11:16:37.016  6682  6759 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1218222b Bundle[{}]
09-01 11:16:37.017  1034  1536 D LGWifiP2pService: InactiveState{ when=-7ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:16:37.017  1034  1536 D LGWifiP2pService: P2pEnabledState{ when=-7ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:16:37.017  1034  1536 D LGWifiP2pService: DefaultState{ when=-8ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:16:37.017  6814  6814 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-01 11:16:37.017  6682  6759 I io.jxcore.node.LifeCycleMonitor: start: OK
09-01 11:16:37.017  1034  1536 D LGWifiP2pService: InactiveState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-01 ,11:16:37.017  6682  6759 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-01 11:16:37.017  1034  1536 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:16:37.018  1034  1536 D LGWifiP2pService: DefaultState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:16:37.018  6682  6759 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-01 11:16:37.018  1939  2284 W WfdsService: DefaultState - msg [9441285] is not handled
09-01 11:16:37.018  6682  6759 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-01 11:16:37.019  6682  6759 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-01 11:16:37.019  6682  6759 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
09-01 11:16:37.020  1034  1536 D LGWifiP2pService: InactiveState{ when=-6ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:16:37.020  1034  1536 D LGWifiP2pService: P2pEnabledState{ when=-6ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:16:37.020  1034  1536 D LGWifiP2pService: DefaultState{ when=-6ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:16:37.021  1034  1034 E WifiServerServiceExt: No p2p device connected
09-01 11:16:37.023  6682  6759 I System.out: Running OutgoingSocketThread
09-01 11:16:37.024  8028  8075 V FormManager: Network unavailable.
,09-01 11:16:37.026  6682  8076 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 861)
09-01 11:16:37.028  6682  8076 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 54161
09-01 11:16:37.028  6682  8076 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
09-01 11:16:37.029  8028  8075 V FormManager: Network unavailable.
09-01 11:16:37.030  8028  8074 W FormManager: Network not available. Please check & try again.
09-01 11:16:37.031  6814  6814 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-01 11:16:37.040  4322  4322 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-01 11:16:37.041  4322  4322 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-01 11:16:37.042  4322  4322 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-01 11:16:37.043  4322  4322 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-01 11:16:37.050  4322  8077 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-01 11:16:37.050  4322  8078 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-01 11:16:37.051  4322  8078 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-01 11:16:37.083  1034  1779 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8079 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,09-01 11:16:37.199  8079  8079 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-01 11:16:37.199  8079  8079 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,09-01 11:16:37.209  8079  8079 V [BNRBootReceiver]: Boot Receiver Return
09-01 11:16:37.213  8079  8079 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-01 11:16:37.262  1034  1049 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8097 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-01 11:16:37.263  1034  1049 I ActivityManager: Killing 7138:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
09-01 11:16:37.329  1034  1993 W libprocessgroup: failed to open /acct/uid_10085/pid_7138/cgroup.procs: No such file or directory
,09-01 11:16:37.363  8097  8097 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-01 11:16:37.398  8097  8097 D PluginManager: init()
,09-01 11:16:37.506  1034  8069 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
09-01 11:16:37.507  1034  8069 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
09-01 11:16:37.507  8011  8011 E wpa_supplicant: USIM:  scard_init function
09-01 11:16:37.507  1034  8069 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
09-01 11:16:37.507  1034  8069 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: WPS-AP-AVAILABLE 
09-01 11:16:37.507  1034  8069 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
09-01 11:16:37.508  8011  8011 I wpa_supplicant: Trying to associate with SSID 'NG700'
09-01 11:16:37.510  1034  1537 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
09-01 11:16:37.511  1034  1537 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
,09-01 11:16:37.513  1034  1537 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
09-01 11:16:37.514  1034  8069 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
09-01 11:16:37.514  1034  8069 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
09-01 11:16:37.515  1034  1537 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
09-01 11:16:37.515  1034  1537 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
09-01 11:16:37.522  1034  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=201082  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-01 11:16:37.524  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-01 11:16:37.524  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-01 11:16:37.524  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:16:37.525  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:16:37.525  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-01 11:16:37.526  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-01 11:16:37.533  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:16:37.533  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:16:37.533  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-01 11:16:37.533  1034  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=201094  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-01 11:16:37.534  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-01 11:16:37.534  1034  1034 D WifiServerServiceExt: setSupplicantStateASSOCIATING
09-01 11:16:37.550  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-01 11:16:37.550  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-01 11:16:37.551  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:16:37.644  8011  8011 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
09-01 11:16:37.645  1034  8069 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
09-01 11:16:37.646  1034  8069 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
09-01 11:16:37.647  1034  8069 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
09-01 11:16:37.647  1034  8069 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: Associated with f4:f2:6d:22:99:3e
09-01 11:16:37.651  1034  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=201211  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
,09-01 11:16:37.652  1034  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=201212  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-01 11:16:37.653  1034  1537 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=201213
09-01 11:16:37.654  1034  1537 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=201214
09-01 11:16:37.654  1034  1537 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=201215
09-01 11:16:37.655  1034  1537 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=201216
09-01 11:16:37.656  1034  1537 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=201216
09-01 11:16:37.657  1034  1096 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-01 11:16:37.657  1034  8069 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-01 11:16:37.657  1034  8069 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,09-01 11:16:37.660  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-01 11:16:37.660  1034  1034 D WifiServerServiceExt: setSupplicantStateASSOCIATED
09-01 11:16:37.662  1034  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=201223  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-01 11:16:37.667  8011  8011 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-01 11:16:37.667  8011  8011 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-01 11:16:37.669  1034  8069 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-01 11:16:37.669  1034  8069 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-01 11:16:37.669  1034  8069 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
09-01 11:16:37.669  1034  8069 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-01 11:16:37.669  1034  8069 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-01 11:16:37.669  1034  8069 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
09-01 11:16:37.669  1034  8069 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-01 11:16:37.669  1034  8069 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-01 11:16:37.671  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:16:37.671  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:16:37.671  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,09-01 11:16:37.672  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-01 11:16:37.672  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:16:37.672  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
09-01 11:16:37.673  1034  8069 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-01 11:16:37.673  1034  8069 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-01 11:16:37.674  1034  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=201234  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-01 11:16:37.674  1034  1537 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
09-01 11:16:37.675  1034  1537 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
09-01 11:16:37.675  1034  1537 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
09-01 11:16:37.675  1034  1537 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
09-01 11:16:37.676  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-01 11:16:37.676  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-01 11:16:37.676  1034  1537 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-01 11:16:37.677  1034  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=201237  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-01 11:16:37.677  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:16:37.678  1034  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=201238  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-01 11:16:37.678  1034  1537 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=201239
09-01 11:16:37.679  1034  1537 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=201240
09-01 11:16:37.680  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-01 11:16:37.680  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-01 11:16:37.680  1034  1537 D WifiNative-wlan0: doString: [STATUS]
09-01 11:16:37.680  1034  8069 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-01 11:16:37.680  1034  8069 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-01 11:16:37.680  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:16:37.681  1034  1537 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-01 11:16:37.683  1034  1537 I WifiServiceExtension: setVHTCapabilityType  : false
,09-01 11:16:37.690  1034  1537 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
09-01 11:16:37.690  1034  1537 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
09-01 11:16:37.693  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:16:37.693  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:16:37.693  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-01 11:16:37.699  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-01 11:16:37.699  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-01 11:16:37.700  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:16:37.701  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:16:37.701  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-01 11:16:37.703  1034  1537 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
09-01 11:16:37.703  1034  1537 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-01 11:16:37.703  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:16:37.703  1034  1537 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-01 11:16:37.703  1034  1544 D ConnectivityService: Got NetworkAgent Messenger
09-01 11:16:37.703  1034  1544 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-01 11:16:37.703  1034  1544 D ConnectivityService: NetworkAgent connected
09-01 11:16:37.704  1034  1537 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-01 11:16:37.704  1034  1537 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-01 11:16:37.704  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-01 11:16:37.704  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-01 11:16:37.707  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:16:37.708  1034  1537 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-01 11:16:37.708  1034  1537 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-01 11:16:37.709  1034  1537 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-01 11:16:37.709  1034  1537 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-01 11:16:37.709  1034  1537 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-01 11:16:37.712  1034  1537 D WifiNative-wlan0: SAVE_CONFIG: returned true
,09-01 11:16:37.715   309   893 D CommandListener: Setting iface cfg
09-01 11:16:37.718  1034  1537 E WifiStateMachine: Start Dhcp Watchdog 3
09-01 11:16:37.718  1034  8118 D DhcpStateMachine: StoppedState
09-01 11:16:37.718  1034  1537 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=201279  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-01 11:16:37.719  1034  8118 D DhcpStateMachine: StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
,09-01 11:16:37.719  1034  8118 D DhcpStateMachine: WaitBeforeStartState
09-01 11:16:37.719  1034  1537 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=201279  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-01 11:16:37.719  1034  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=201280  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-01 11:16:37.720  1034  1537 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=201281  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-01 11:16:37.721  1034  1537 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=201281  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-01 11:16:37.721  1034  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=201282  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-01 11:16:37.722  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-01 11:16:37.722  1034  1034 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
09-01 11:16:37.722  1034  1537 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14236] from screen [on:0 period:-452384806] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-01 11:16:37.723  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-452384805] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-01 11:16:37.723  1034  1537 D WifiNative-wlan0: doString: [SIGNAL_POLL]
09-01 11:16:37.727  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:16:37.729  1034  1544 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
09-01 11:16:37.729  1034  1537 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:16:37.730  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:16:37.730  1034  1537 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:16:37.731  1034  1537 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:16:37.731  1034  1537 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:16:37.731  1034  1537 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:16:37.732  1034  1544 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-01 11:16:37.733  1034  1537 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=123,0,0
09-01 11:16:37.733  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=123,0,0
09-01 11:16:37.733  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
09-01 11:16:37.733  8011  8011 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
09-01 11:16:37.734  1034  1537 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
09-01 11:16:37.734  1034  1537 D WifiNative-wlan0: doBoolean: SET ps 0
09-01 11:16:37.734  1034  1537 D WifiNative-wlan0: SET ps 0: returned true
09-01 11:16:37.734  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
09-01 11:16:37.734  8011  8011 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
09-01 11:16:37.735  1034  1537 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
09-01 11:16:37.735  1034  1537 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
09-01 11:16:37.735  1034  1537 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-01 11:16:37.735  1034  1537 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
,09-01 11:16:37.736   309   893 D CommandListener: Setting iface cfg
09-01 11:16:37.736   309   893 D CommandListener: Trying to bring up wlan0
09-01 11:16:37.737  1034  1536 D LGWifiP2pService: InactiveState{ when=-2ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@36e84f47 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:16:37.737  1034  1536 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@36e84f47 target=com.android.internal.util.StateMachine$SmHandler }
,09-01 11:16:37.738  1034  8118 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:16:37.738  1034  8118 D DhcpStateMachine: DHCP Start wake lock is acquired.
09-01 11:16:37.738  1034  1537 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
09-01 11:16:37.739  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-01 11:16:37.739  1034  1034 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-01 11:16:37.740  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-01 11:16:37.740  1034  1034 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-01 11:16:37.741  1034  1537 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:16:37.741  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:16:37.742  1034  1537 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:16:37.742  1034  1537 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:16:37.743  1034  1537 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:16:37.743  1034  1537 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:16:37.744  1034  1544 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-01 11:16:37.744  1034  1537 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-01 11:16:37.744  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-01 11:16:37.744  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-01 11:16:37.744  1034  1536 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:16:37.744  1034  1536 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:16:37.745  8011  8011 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-01 11:16:37.745  1034  1537 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-01 11:16:37.745  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
09-01 11:16:37.745  8011  8011 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
09-01 11:16:37.745  1034  1537 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
09-01 11:16:37.745  1034  1537 D WifiNative-wlan0: doBoolean: SET ps 1
09-01 11:16:37.761  1034  1537 D WifiNative-wlan0: SET ps 1: returned true
09-01 11:16:37.761  1034  1544 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-01 11:16:37.762  1034  1537 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-01 11:16:37.762  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-01 11:16:37.762  1034  1537 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-01 11:16:37.763  1034  1544 D ConnectivityService: ignoring duplicate network state non-change
,09-01 11:16:37.765  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-01 11:16:37.766  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-01 11:16:37.767  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:16:37.767  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:16:37.767  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-01 11:16:37.767  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:16:37.767  1034  1544 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-01 11:16:37.769  1034  1544 D ConnectivityService: Adding iface wlan0 to network 102
09-01 11:16:37.772  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:16:37.773  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:16:37.773  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-01 11:16:37.777  1034  1537 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-01 11:16:37.780  1034  1034 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-01 11:16:37.785  1939  1939 V WfdStateTracker: handleWifiStateChangedEvent: 1
09-01 11:16:37.789  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-01 11:16:37.789  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-01 11:16:37.789  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:16:37.789  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:16:37.789  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,09-01 11:16:37.790  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:16:37.791  1034  1034 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-01 11:16:37.793  1034  1544 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-01 11:16:37.793  1034  1544 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
09-01 11:16:37.794  1034  1544 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
09-01 11:16:37.794  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-01 11:16:37.794   309   893 E Netd    : netlink response contains error (File exists)
09-01 11:16:37.794  1602  1602 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-01 11:16:37.794  1034  1544 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
09-01 11:16:37.794  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:16:37.795  1034  1544 D ConnectivityService: addLocalRoutetoDefaultNetwork
09-01 11:16:37.795  1034  1544 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
09-01 11:16:37.795  1034  1544 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
09-01 11:16:37.795  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:16:37.795  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:16:37.795  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-01 11:16:37.795  1034  1544 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-01 11:16:37.795  1034  1544 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-01 11:16:37.795  1034  1544 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
09-01 11:16:37.796  1034  1544 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
09-01 11:16:37.796  1034  1544 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-01 11:16:37.796  1034  1544 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-01 11:16:37.796  1034  1544 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-01 11:16:37.796  1034  1544 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-01 11:16:37.796  1034  1544 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
09-01 11:16:37.796  1034  1544 D ConnectivityService: currentScore = 0, newScore = 20
09-01 11:16:37.796  1034  1544 D ConnectivityService:    accepting network in place of null
09-01 11:16:37.796  1034  1544 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-01 11:16:37.796  1034  8117 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:16:37.796  1034  8117 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
09-01 11:16:37.796  1034  8117 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 ar,g1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:16:37.797  1034  1537 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-01 11:16:37.797  1034  1537 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-01 11:16:37.797  1034  8117 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-01 11:16:37.797  1850  1850 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-01 11:16:37.797  1850  1850 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-01 11:16:37.798  1034  1544 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-01 11:16:37.798  1034  1544 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
09-01 11:16:37.798  1034  1544 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-01 11:16:37.799   309  8128 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
09-01 11:16:37.803  1034  1544 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-01 11:16:37.803  1034  1544 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
09-01 11:16:37.803  1034  1544 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
09-01 11:16:37.804  1034  1544 D ConnectivityService: validation of new default Network = false
09-01 11:16:37.804  1034  1544 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
09-01 11:16:37.804  1034  1544 D DSQN    : enableDataServiceNotify 
09-01 11:16:37.804  1034  1544 D DSQN    : start dsqn bin
,09-01 11:16:37.807  1034  1034 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
09-01 11:16:37.807  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-01 11:16:37.807  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-01 11:16:37.807  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-01 11:16:37.809  1034  1544 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
09-01 11:16:37.809  1034  1544 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-01 11:16:37.809  1034  1544 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-01 11:16:37.809  1034  1544 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-01 11:16:37.798  8129  8129 W dsqn    : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-01 11:16:37.798  8129  8129 W dsqn    : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-01 11:16:37.809  1602  2075 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-01 11:16:37.812  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-01 11:16:37.812  1602  1602 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-01 11:16:37.812  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:16:37.823  1034  1535 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
09-01 11:16:37.824  8129  8129 E DSQN    : DSQN ssw
,09-01 11:16:37.834  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-01 11:16:37.835  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:16:37.835  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-01 11:16:37.850   309  8128 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,09-01 11:16:37.884   309  8128 D libc-netbsd: res_queryN name = clients3.google.com succeed
,09-01 11:16:37.898   309   892 D LGDataListener: argv[0]=dsqncommand
09-01 11:16:37.898   309   892 D LGDataListener: argv[1]=wlan0
09-01 11:16:37.898   309   892 D LGDataListener: argv[2]=1
09-01 11:16:37.898   309   892 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
09-01 11:16:37.899  1034  1094 D DSQN    : DSQM DsqnNotification wlan0  1
09-01 11:16:37.899  1034  1094 D DSQN    : start to monitor internet connection
,09-01 11:16:37.902  8097  8097 W ExternalStrings: load override strings
09-01 11:16:37.902  8097  8097 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
09-01 11:16:37.902  8097  8097 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
09-01 11:16:37.902  8097  8097 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
09-01 11:16:37.902  8097  8097 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
09-01 11:16:37.902  8097  8097 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
09-01 11:16:37.902  8097  8097 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
09-01 11:16:37.902  8097  8097 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
09-01 11:16:37.902  8097  8097 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
09-01 11:16:37.902  8097  8097 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
09-01 11:16:37.902  8097  8097 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
09-01 11:16:37.902  8097  8097 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
09-01 11:16:37.902  8097  8097 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 11:16:37.902  8097  8097 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
09-01 11:16:37.902  8097  8097 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-01 11:16:37.902  8097  8097 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 11:16:37.902  8097  8097 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-01 11:16:37.902  8097  8097 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-01 11:16:37.902  8097  8097 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-01 11:16:37.910  1034  8117 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 01 Sep 2016 09:16:37 GMT], X-Android-Received-Millis=[1472721397909], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472721397897]}
09-01 11:16:37.910  1034  8117 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-01 11:16:37.910  1034  8117 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
09-01 11:16:37.911  8097  8097 D StatusProvider: onCreate
09-01 11:16:37.912  1034  1544 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
09-01 11:16:37.913  1034  1544 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
,09-01 11:16:37.914  1034  1544 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-01 11:16:37.914  1034  1544 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-01 11:16:37.914  1034  1544 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-01 11:16:37.914  1034  1544 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
09-01 11:16:37.914  1034  1544 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
09-01 11:16:37.915  1034  1544 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-01 11:16:37.915  1034  1544 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-01 11:16:37.916  1034  1544 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-01 11:16:37.916  1034  1544 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-01 11:16:37.917  1034  1537 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-01 11:16:37.917  1034  1537 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-01 11:16:37.918  1602  2075 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-01 11:16:37.919  1034  1544 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-01 11:16:37.919  1850  1850 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-01 11:16:37.919  1850  1850 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-01 11:16:37.940  1034  8118 D DhcpStateMachine: DHCPV4 request on wlan0
,09-01 11:16:37.945  1034  8118 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
09-01 11:16:37.945  1034  8118 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
09-01 11:16:37.938  8135  8135 W dhcpcd  : type=1400 audit(0.0:195): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-01 11:16:37.938  8135  8135 W dhcpcd  : type=1400 audit(0.0:196): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-01 11:16:37.968  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-01 11:16:37.969  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:16:37.970  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-01 11:16:37.975  8135  8135 I dhcpcd  : version 5.5.6 starting
09-01 11:16:37.980  8135  8135 E dhcpcd  : get_duid: m
09-01 11:16:37.981  8135  8135 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
09-01 11:16:37.981  8135  8135 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,09-01 11:16:38.026  6682  6759 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 862)
09-01 11:16:38.027  6682  6759 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 862)
,09-01 11:16:38.037  6682  6759 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 867)
09-01 11:16:38.040  6682  6759 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-01 11:16:38.040  6682  6759 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 868)
,09-01 11:16:38.049  6682  6759 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-01 11:16:38.049  6682  6759 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8511ef6 added. We now have 2 listener(s)
09-01 11:16:38.049  1034  1650 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:16:38.050  8135  8135 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-01 11:16:38.050  8135  8135 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-01 11:16:38.050  8135  8135 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-01 11:16:38.050  8135  8135 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
09-01 11:16:38.051  8135  8135 D dhcpcd  : wlan0: sending REQUEST (xid 0xe0629f62), next in 3.71 seconds
09-01 11:16:38.051  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,09-01 11:16:38.052  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 11:16:38.052  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-01 11:16:38.052  6682  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 11:16:38.052  6682  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a3d52f7 added. We now have 9 listener(s)
09-01 11:16:38.052  6682  6759 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 11:16:38.052  8097  8097 V Signer  : override build config not found
09-01 11:16:38.052  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-01 11:16:38.052  8097  8097 D Signer  : value of property debug is false
09-01 11:16:38.055  6682  6759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 11:16:38.059  6682  6759 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 11:16:38.059  6682  6759 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:16:38.059  6682  6759 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-01 11:16:38.059  6682  6759 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:16:38.059  6682  6759 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:16:38.059  6682  6759 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 11:16:38.059  6682  6759 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 11:16:38.059  6682  6759 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-01 11:16:38.060  6682  6759 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-01 11:16:38.061  6682  6759 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-01 11:16:38.061  6682  6759 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-01 11:16:38.061  6682  6759 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3939b3cd added. We now have 3 listener(s)
09-01 11:16:38.062  1034  1917 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:16:38.062  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:16:38.064  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:16:38.065  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,09-01 11:16:38.066  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 11:16:38.066  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-01 11:16:38.066  6682  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 11:16:38.066  6682  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe83482 added. We now have 10 listener(s)
09-01 11:16:38.066  6682  6759 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 11:16:38.066  6682  6759 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:16:38.066  6682  6759 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:16:38.066  6682  6759 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:16:38.066  6682  6759 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:16:38.066  6682  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:16:38.066  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 11:16:38.066  6682  6759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-01 11:16:38.066  6682  6759 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8511ef6 removed from the list
09-01 11:16:38.066  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:16:38.066  6682  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a3d52f7 removed from the list
09-01 11:16:38.067  6682  6759 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:16:38.067  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:16:38.067  6682  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:16:38.067  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:16:38.068  8135  8135 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
09-01 11:16:38.068  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:16:38.068  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:16:38.068  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:16:38.068  6682  6759 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a3d52f7 not in the list
09-01 11:16:38.068  6682  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:16:38.068  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:16:38.069  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:16:38.069  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01, 11:16:38.069  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:16:38.069  6682  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe83482 removed from the list
09-01 11:16:38.069  6682  6759 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:16:38.069  6682  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:16:38.069  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:16:38.070  6682  6759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-01 11:16:38.070  6682  6759 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3939b3cd removed from the list
09-01 11:16:38.070  6682  6759 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-01 11:16:38.070  6682  6759 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@246a2793 added. We now have 2 listener(s)
09-01 11:16:38.071  1034  1780 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:16:38.073  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-01 11:16:38.073  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 11:16:38.073  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-01 11:16:38.073  6682  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 11:16:38.073  6682  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7f3d3d0 added. We now have 9 listener(s)
09-01 11:16:38.073  6682  6759 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 11:16:38.074  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-01 11:16:38.076  6682  6759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 11:16:38.079  6682  6759 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 11:16:38.079  6682  6759 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
,09-01 11:16:38.079  6682  6759 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-01 11:16:38.079  6682  6759 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:16:38.079  6682  6759 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:16:38.079  6682  6759 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 11:16:38.079  6682  6759 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 11:16:38.079  6682  6759 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-01 11:16:38.081  6682  6759 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-01 11:16:38.081  6682  6759 D io.jxcore.node.ConnectivityMonitor: start: OK
09-01 11:16:38.081  6682  6759 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-01 11:16:38.081  6682  6759 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2de916ce added. We now have 3 listener(s)
09-01 11:16:38.082  1034  2022 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:16:38.084  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:16:38.085  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:16:38.087  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-01 11:16:38.087  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 11:16:38.087  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-01 11:16:38.087  6682  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-01 11:16:38.087  6682  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@285a9ef added. We now have 10 listener(s)
09-01 11:16:38.087  6682  6759 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 11:16:38.087  6682  6759 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-01 11:16:38.087  6682  6759 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-01 11:16:38.087  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-01 11:16:38.087  6682  6759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-01 11:16:38.088  6682  6759 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-01 11:16:38.088  8135  8135 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
09-01 11:16:38.088  8135  8135 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
09-01 11:16:38.088  8135  8135 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
,09-01 11:16:38.088  8135  8135 D dhcpcd  : wlan0: adding default route via 192.168.1.1
09-01 11:16:38.089  8135  8135 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-01 11:16:38.089  8135  8135 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-01 11:16:38.089  8135  8135 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-01 11:16:38.089  8135  8135 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,09-01 11:16:38.091  6682  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-01 11:16:38.091  1034  1993 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-01 11:16:38.102  6682  6759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-01 11:16:38.103  6682  6759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-01 11:16:38.105  6682  6759 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-01 11:16:38.106  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 11:16:38.108  6682  6759 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-01 11:16:38.108  6682  6759 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:16:38.108  6682  6759 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:16:38.111  6682  6759 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:16:38.111  6682  6759 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:16:38.111  6682  6759 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:16:38.111  6682  6759 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:16:38.111  6682  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:16:38.111  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 11:16:38.111  6682  6759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-01 11:16:38.111  6682  6759 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@246a2793 removed from the list
09-01 11:16:38.111  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:16:38.111  6682  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7f3d3d0 removed from the list
09-01 11:16:38.111  6682  6759 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:16:38.111  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:16:38.112  6682  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:16:38.112  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:16:38.113  8097  8097 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
09-01 11:16:38.113  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:16:38.113  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:16:38.113  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:16:38.113  6682  6759 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7f3d3d0 not in the list
09-01 11:16:38.113  6682  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:16:38.113  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:16:38.113  8097  8097 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
09-01 11:16:38.113  8097  8097 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
09-01 11:16:38.114  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:16:38.114  6682  6759 D Bluetoo,thLeScanner: could not find callback wrapper
09-01 11:16:38.114  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-01 11:16:38.114  8097  8097 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
09-01 11:16:38.114  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:16:38.114  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:16:38.114  6682  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@285a9ef removed from the list
09-01 11:16:38.114  6682  6759 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:16:38.114  6682  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:16:38.114  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:16:38.114  8097  8097 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
09-01 11:16:38.115  6682  6759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-01 11:16:38.115  6682  6759 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2de916ce removed from the list
09-01 11:16:38.115  8097  8097 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
09-01 11:16:38.115  8097  8097 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
09-01 11:16:38.115  8097  8097 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
09-01 11:16:38.115  8097  8097 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
09-01 11:16:38.116  6682  6759 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-01 11:16:38.116  6682  6759 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1203d1da added. We now have 2 listener(s)
09-01 11:16:38.116  8097  8097 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
,09-01 11:16:38.116  1034  1893 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:16:38.116  8097  8097 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
09-01 11:16:38.116  8097  8097 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
09-01 11:16:38.116  8097  8097 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
09-01 11:16:38.119  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-01 11:16:38.119  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 11:16:38.119  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-01 11:16:38.120  6682  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 11:16:38.120  6682  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e2cf60b added. We now have 9 listener(s)
09-01 11:16:38.120  6682  6759 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 11:16:38.120  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-01 11:16:38.123  6682  6759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-01 11:16:38.131  6682  6759 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 11:16:38.131  6682  6759 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:16:38.131  6682  6759 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-01 11:16:38.131  6682  6759 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:16:38.131  6682  6759 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:16:38.131  6682  6759 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 11:16:38.131  6682  6759 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 11:16:38.131  6682  6759 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-01 11:16:38.133  6682  6759 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-01 11:16:38.133  6682  6759 D io.jxcore.node.ConnectivityMonitor: start: OK
09-01 11:16:38.133  6682  6759 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-01 11:16:38.133  6682  6759 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29459f01 added. We now have 3 listener(s)
09-01 11:16:38.133  1034  1893 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:16:38.135  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:16:38.136  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,09-01 11:16:38.136  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 11:16:38.136  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-01 11:16:38.136  6682  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 11:16:38.136  6682  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4dd31a6 added. We now have 10 listener(s)
09-01 11:16:38.136  6682  6759 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 11:16:38.136  6682  6759 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-01 11:16:38.137  6682  6759 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-01 11:16:38.137  6682  6759 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-01 11:16:38.137  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-01 11:16:38.137  6682  6759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 11:16:38.137  6682  6759 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-01 11:16:38.138  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:16:38.141  6682  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-01 11:16:38.141  1034  1650 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:16:38.142  8097  8097 V LGMDMManager: Create singleton instance
09-01 11:16:38.148  6682  6759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-01 11:16:38.149  6682  6759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-01 11:16:38.150  6682  6759 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-01 11:16:38.151  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 11:16:38.152  6682  6759 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-01 11:16:38.152  6682  6759 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:16:38.152  6682  6759 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:16:38.152  6682  6759 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:16:38.152  6682  6759 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:16:38.152  6682  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:16:38.152  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 11:16:38.152  6682  6759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-01 11:16:38.152  6682  6759 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1203d1da removed from the list
09-01 11:16:38.152  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:16:38.152  6682  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e2cf60b removed from the list
09-01 11:16:38.152  6682  6759 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:16:38.152  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:16:38.158  6682  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:16:38.158  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:16:38.159  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:16:38.159  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:16:38.159  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:16:38.159  6682  6759 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e2cf60b not in the list
09-01 11:16:38.159  6682  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:16:38.159  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:16:38.160  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-01 11:16:38.168  6682  6759 D BluetoothLeScanner: could not find callback wrapper
09-01 11:16:38.168  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-01 11:16:38.168  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:16:38.168  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:16:38.168  6682  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4dd31a6 removed from the list
09-01 11:16:38.168  6682  6759 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:16:38.168  6682  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:16:38.168  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:16:38.168  6682  6759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-01 11:16:38.168  6682  6759 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29459f01 removed from the list
09-01 11:16:38.169  6682  6759 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-01 11:16:38.169  6682  6759 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5ec2a3d added. We now have 2 listener(s)
09-01 11:16:38.170  1034  1779 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:16:38.172  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-01 11:16:38.172  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-01 11:16:38.172  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-01 11:16:38.172  6682  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 11:16:38.172  6682  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@229ac232 added. We now have 9 listener(s)
09-01 11:16:38.172  6682  6759 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 11:16:38.173  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-01 11:16:38.175  6682  6759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 11:16:38.178  6682  6759 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 11:16:38.178  6682  6759 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:16:38.178  6682  6759 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-01 11:16:38.178  6682  6759 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:16:38.178  6682  6759 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:16:38.178  6682  6759 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 11:16:38.178  6682  6759 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 11:16:38.178  6682  6759 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-01 11:16:38.180  6682  6759 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-01 11:16:38.180  6682  6759 D io.jxcore.node.ConnectivityMonitor: start: OK
09-01 11:16:38.180  6682  6759 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-01 11:16:38.180  6682  6759 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25cbd100 added. We now have 3 listener(s)
09-01 11:16:38.180  1034  1574 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:16:38.183  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-01 11:16:38.183  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 11:16:38.183  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-01 11:16:38.183  6682  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 11:16:38.183  6682  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17762d39 added. We now have 10 listener(s)
09-01 11:16:38.183  6682  6759 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 11:16:38.183  6682  6759 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-01 11:16:38.183  6682  6759 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-01 11:16:38.183  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-01 11:16:38.183  6682  6759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 11:16:38.183  6682  6759 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-01 11:16:38.186  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:16:38.189  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:16:38.189  6682  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-01 11:16:38.189  1034  1917 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:16:38.192  6682  6759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-01 11:16:38.192  6682  6759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-01 11:16:38.193  6682  6759 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-01 11:16:38.194  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 11:16:38.195  6682  6759 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,09-01 11:16:38.197  6682  6759 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:16:38.197  6682  6759 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:16:38.197  6682  6759 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:16:38.197  6682  6759 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:16:38.197  6682  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:16:38.197  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 11:16:38.197  6682  6759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-01 11:16:38.198  6682  6759 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5ec2a3d removed from the list
09-01 11:16:38.198  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:16:38.198  6682  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@229ac232 removed from the list
09-01 11:16:38.198  6682  6759 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:16:38.198  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:16:38.198  6682  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:16:38.198  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 11:16:38.199  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:16:38.199  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:16:38.199  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:16:38.199  6682  6759 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@229ac232 not in the list
09-01 11:16:38.199  6682  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:16:38.199  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:16:38.200  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:16:38.200  6682  6759 D BluetoothLeScanner: could not find callback wrapper
09-01 11:16:38.200  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-01 11:16:38.200  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:16:38.200  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:16:38.200  6682  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17762d39 removed from the list
09-01 11:16:38.200  6682  6759 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:16:38.200  6682  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:16:38.200  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:16:38.200  6682  6759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-01 11:16:38.200  6682  6759 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25cbd100 removed from the list
09-01 11:16:38.201  6682  6759 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-01 11:16:38.201  6682  6759 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b9cfd2c added. We now have 2 listener(s)
09-01 11:16:38.202  1034  1049 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:16:38.203  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-01 11:16:38.203  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 11:16:38.203  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-01 11:16:38.203  6682  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 11:16:38.203  6682  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@130363f5 added. We now have 9 listener(s)
09-01 11:16:38.204  6682  6759 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 11:16:38.204  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-01 11:16:38.205  6682  6759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.Blueto,othManager: bind: Binding a new listener
09-01 11:16:38.208  6682  6759 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 11:16:38.208  6682  6759 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:16:38.208  6682  6759 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-01 11:16:38.208  6682  6759 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:16:38.208  6682  6759 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:16:38.208  6682  6759 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 11:16:38.208  6682  6759 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 11:16:38.208  6682  6759 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-01 11:16:38.209  6682  6759 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-01 11:16:38.210  6682  6759 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-01 11:16:38.211  6682  6759 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-01 11:16:38.211  6682  6759 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@156b77fb added. We now have 3 listener(s)
09-01 11:16:38.211  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:16:38.211  1034  1959 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:16:38.213  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:16:38.214  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-01 11:16:38.214  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 11:16:38.214  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-01 11:16:38.214  6682  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 11:16:38.214  6682  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2472c018 added. We now have 10 listener(s)
09-01 11:16:38.214  6682  6759 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 11:16:38.214  6682  6759 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-01 11:16:38.214  6682  6759 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:16:38.214  6682  6759 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:16:38.218  6682  6759 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:16:38.218  6682  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:16:38.218  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 11:16:38.218  6682  6759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-01 11:16:38.218  6682  6759 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b9cfd2c removed from the list
09-01 11:16:38.218  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:16:38.218  6682  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@130363f5 removed from the list
09-01 11:16:38.218  6682  6759 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:16:38.218  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:16:38.219  6682  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:16:38.219  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:16:38.219  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:16:38.219  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:16:38.219  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:16:38.219  6682  6759 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@130363f5 not in the list
09-01 11:16:38.219  6682  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:16:38.220  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:16:38.220  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:16:38.220  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:16:38.220  6682  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:16:38.220  6682  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2472c018 removed from the list
09-01 11:16:38.220  6682  6759 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:16:38.220  6682  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:16:38.220  6682  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:16:38.220  6682  6759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-01 11:16:38.220  6682  6759 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@156b77fb removed fro,m the list
09-01 11:16:38.221  6682  6759 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-01 11:16:38.221  6682  6759 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-01 11:16:38.222  6682  6759 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-01 11:16:38.222  6682  6759 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-01 11:16:38.222  6682  6759 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-01 11:16:38.222  6682  6759 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-01 11:16:38.232  6682  8157 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 875, name: My test thread name)
09-01 11:16:38.232  6682  8157 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 875, thread name: My test thread name)
09-01 11:16:38.232  6682  8157 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 875, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-01 11:16:38.235  8097  8097 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
09-01 11:16:38.236  6682  8158 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 877, name: My test thread name)
09-01 11:16:38.236  6682  8158 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 877, thread name: My test thread name)
09-01 11:16:38.236  6682  8158 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 877, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
09-01 11:16:38.239  6682  6759 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
09-01 11:16:38.239  6682  6759 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-01 11:16:38.239  6682  6759 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-01 11:16:38.239  6682  6759 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-01 11:16:38.239  6682  6759 D com.test.thalitest.ThaliTestRunner: Total duration: 23158 ms
09-01 11:16:38.241  6682  6759 I jxcore-log: *Native tests were executed*
09-01 11:16:38.241  6682  6759 I jxcore-log: 
09-01 11:16:38.241  6682  6759 I jxcore-log: Total number of executed tests:  80
09-01 11:16:38.241  6682  6759 I jxcore-log: 
,09-01 11:16:38.241  6682  6759 I jxcore-log: Number of passed tests:  80
09-01 11:16:38.241  6682  6759 I jxcore-log: 
09-01 11:16:38.242  6682  6759 I jxcore-log: Number of failed tests:  0
09-01 11:16:38.242  6682  6759 I jxcore-log: 
09-01 11:16:38.242  6682  6759 I jxcore-log: Number of ignored tests:  0
09-01 11:16:38.242  6682  6759 I jxcore-log: 
09-01 11:16:38.242  6682  6759 I jxcore-log: Total duration:  23158
09-01 11:16:38.242  6682  6759 I jxcore-log: 
09-01 11:16:38.243  6682  6759 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-01 11:16:38.243  6682  6759 I jxcore-log: 
09-01 11:16:38.246  6682  6759 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 11:16:38.246  6682  6759 I jxcore-log: 
09-01 11:16:38.251  6682  6759 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 11:16:38.251  6682  6759 I jxcore-log: 
09-01 11:16:38.252  6682  6759 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 11:16:38.252  6682  6759 I jxcore-log: 
09-01 11:16:38.254  6682  6759 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 11:16:38.254  6682  6759 I jxcore-log: 
09-01 11:16:38.255  6682  6759 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 11:16:38.255  6682  6759 I jxcore-log: 
09-01 11:16:38.256  6682  6682 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-01 11:16:38.257  6682  6759 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-01 11:16:38.257  6682  6759 I jxcore-log: 
,09-01 11:16:38.261  6682  6759 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-01 11:16:38.261  6682  6759 I jxcore-log: 
09-01 11:16:38.263  6682  6759 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-01 11:16:38.263  6682  6759 I jxcore-log: 
09-01 11:16:38.264  6682  6759 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-01 11:16:38.264  6682  6759 I jxcore-log: 
09-01 11:16:38.265  6682  6759 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-01 11:16:38.265  6682  6759 I jxcore-log: 
09-01 11:16:38.266  6682  6759 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-01 11:16:38.266  6682  6759 I jxcore-log: 
09-01 11:16:38.267  6682  6759 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-01 11:16:38.267  6682  6759 I jxcore-log: 
09-01 11:16:38.268  6682  6759 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-01 11:16:38.268  6682  6759 I jxcore-log: 
09-01 11:16:38.269  6682  6759 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-01 11:16:38.269  6682  6759 I jxcore-log: 
09-01 11:16:38.269  6682  6759 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-01 11:16:38.269  6682  6759 I jxcore-log: 
09-01 11:16:38.270  6682  6759 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-01 11:16:38.270  6682  6759 I jxcore-log: 
09-01 11:16:38.271  6682  6759 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-01 11:16:38.271  6682  6759 I jxcore-log: 
09-01 11:16:38.271  6682  6759 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-01 11:16:38.271  6682  6759 I jxcore-log: 
09-01 11:16:38.272  6682  6759 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-01 11:16:38.272  6682  6759 I jxcore-log: 
09-01 11:16:38.273  6682  6759 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-01 11:16:38.273  6682  6759 I jxcore-log: 
09-01 11:16:38.273  6682  6759 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-01 11:16:38.273  6682  6759 I jxcore-log: 
09-01 11:16:38.274  6682  6759 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-01 11:16:38.274  6682  6759 I jxcore-log: 
09-01 11:16:38.275  6682  6759 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 11:16:38.275  6682  6759 I jxcore-log: 
09-01 11:16:38.275  6682  6759 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 11:16:38.275  6682  6759 I jxcore-log: 
09-01 11:16:38.276  6682  6759 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 11:16:38.276  6682  6759 I jxcore-log: 
,09-01 11:16:38.277  6682  6759 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 11:16:38.277  6682  6759 I jxcore-log: 
09-01 11:16:38.278  6682  6759 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 11:16:38.278  6682  6759 I jxcore-log: 
09-01 11:16:38.285  8097  8097 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-01 11:16:38.285  8097  8166 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-01 11:16:38.293  6814  6814 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-01 11:16:38.300  6814  6814 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-01 11:16:38.349  1034  1959 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=8169 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,09-01 11:16:38.351  1034  1959 I ActivityManager: Killing 7177:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,09-01 11:16:38.357  1034  8118 D DhcpStateMachine: DHCPV4 succeeded on wlan0
09-01 11:16:38.358  1034  8118 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
09-01 11:16:38.358  1034  8118 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-01 11:16:38.359  1034  8118 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
09-01 11:16:38.359  1034  8118 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
09-01 11:16:38.359  1034  8118 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-01 11:16:38.359  1034  8118 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
09-01 11:16:38.359  1034  8118 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
09-01 11:16:38.359  1034  8118 D DhcpStateMachine: RunningState
09-01 11:16:38.448  8097  8165 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,09-01 11:16:38.501  8172  8172 D AndroidRuntime: 
09-01 11:16:38.501  8172  8172 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,09-01 11:16:38.504  8172  8172 D AndroidRuntime: CheckJNI is OFF
09-01 11:16:38.580  1034  1987 W libprocessgroup: failed to open /acct/uid_10093/pid_7177/cgroup.procs: No such file or directory
,09-01 11:16:38.603  8169  8169 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-01 11:16:38.641  8169  8169 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,09-01 11:16:38.670  8169  8169 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
09-01 11:16:38.670  8169  8169 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
09-01 11:16:38.670  8169  8169 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
09-01 11:16:38.671  8169  8169 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
09-01 11:16:38.671  8169  8169 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
09-01 11:16:38.673  8169  8169 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
09-01 11:16:38.674  8172  8172 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-01 11:16:38.681  8169  8169 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
09-01 11:16:38.684  1034  1092 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
09-01 11:16:38.685  1034  1092 I ActivityManager: Killing 6682:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
09-01 11:16:38.691  8097  8165 D LgDataFeature: LgDataFeature() Constructor: none
09-01 11:16:38.691  8097  8165 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-01 11:16:38.720  8169  8169 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-01 11:16:38.722  1034  1993 I WindowState: WIN DEATH: Window{3cd53e4c u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-01 11:16:38.722  1034  1543 D WifiService: Client connection lost with reason: 4
09-01 11:16:38.725  8169  8169 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-01 11:16:38.726  1034  1993 D InputDispatcher: Window went away: Window{3cd53e4c u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-01 11:16:38.875  8097  8165 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
,09-01 11:16:38.962  1034  1092 I ActivityManager:   Force finishing activity ActivityRecord{19cc6431 u0 com.test.thalitest/.MainActivity t6}
,09-01 11:16:39.002   343   351 E GBMv2   : DFP En is all cleared set to be enabled
,09-01 11:16:39.006  1034  1917 W ActivityManager: Spurious death for ProcessRecord{2b0444c3 6682:com.test.thalitest/u0a118}, curProc for 6682: null
09-01 11:16:39.008  1034  1102 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
09-01 11:16:39.008  8169  8169 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-01 11:16:39.013  1034  1102 I ActivityManager:   Force finishing activity ActivityRecord{19cc6431 u0 com.test.thalitest/.MainActivity t6 f}
09-01 11:16:39.014  1034  1102 W ActivityManager: Duplicate finish request for ActivityRecord{19cc6431 u0 com.test.thalitest/.MainActivity t6 f}
09-01 11:16:39.014  8169  8169 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
09-01 11:16:39.021  8169  8169 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
,09-01 11:16:39.041  1602  1602 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
09-01 11:16:39.043  1034  1537 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-01 11:16:39.044  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-01 11:16:39.044  1034  1537 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-01 11:16:39.045  1034  1537 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-01 11:16:39.045  1034  1537 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-01 11:16:39.046  1034  1537 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-01 11:16:39.047  1034  1544 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
09-01 11:16:39.047  1034  1544 D ConnectivityService: identical MTU - not setting
09-01 11:16:39.047  1034  1544 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-01 11:16:39.047  1034  1544 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-01 11:16:39.047  1034  1544 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-01 11:16:39.047  1034  1544 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-01 11:16:39.049  1034  1544 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
09-01 11:16:39.051  1602  2075 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,09-01 11:16:39.052  1994  1994 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
09-01 11:16:39.061  2470  2662 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-01 11:16:39.071  1034  1427 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-01 11:16:39.087  3827  3827 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
,09-01 11:16:39.091  7604  7604 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
09-01 11:16:39.091  7604  7604 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
09-01 11:16:39.093  6814  6814 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
09-01 11:16:39.093  1939  1955 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
09-01 11:16:39.093  1939  1955 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2fd517fd co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
09-01 11:16:39.099  1939  2948 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
09-01 11:16:39.100  1939  2948 D SplitWindowPolicy: topRunningActivity=ActivityInfo{15b87cf2 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
09-01 11:16:39.100  2031  2031 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
09-01 11:16:39.102  2031  2031 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
09-01 11:16:39.105  6814  6814 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
,09-01 11:16:39.113  4633  4633 I art     : Explicit concurrent mark sweep GC freed 8187(469KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 1.491ms total 90.743ms
09-01 11:16:39.121  1034  1779 V SIM_STK : Menu title from STK is T-Mobile
,09-01 11:16:39.142  1034  1091 W InputMethodInfo: Duplicated subtype definition found: , voice
,09-01 11:16:39.160  1034  1034 D administrator: Handling package changes for user 0
,09-01 11:16:39.159  4517  4517 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
09-01 11:16:39.163  4517  4517 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
09-01 11:16:39.163  4517  4517 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
09-01 11:16:39.163  4517  4517 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
09-01 11:16:39.163  4517  4517 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-01 11:16:39.163  4517  4517 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-01 11:16:39.163  4517  4517 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-01 11:16:39.164  4517  4517 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-01 11:16:39.164  4517  4517 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 11:16:39.167  4517  4517 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-01 11:16:39.167  4517  4517 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-01 11:16:39.167  4517  4517 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-01 11:16:39.185  8097  8165 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
,09-01 11:16:39.194  8097  8165 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
09-01 11:16:39.197  2031  2031 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
09-01 11:16:39.198  8097  8165 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
09-01 11:16:39.198  2031  2083 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
,09-01 11:16:39.201  8097  8165 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
09-01 11:16:39.204  8097  8165 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
09-01 11:16:39.204  8097  8165 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
09-01 11:16:39.210  1602  1660 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-01 11:16:39.210  1602  1660 D KeyguardModel: createShortcutInfo...
09-01 11:16:39.212  2031  2031 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
,09-01 11:16:39.213  1902  1902 D ActionManagerService: notifyUserLog: 1000003
09-01 11:16:39.214  3827  4508 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
09-01 11:16:39.214  8097  8097 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-01 11:16:39.215  8097  8166 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-01 11:16:39.215  2031  2031 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
09-01 11:16:39.217  8097  8165 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
09-01 11:16:39.217  2031  2031 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
09-01 11:16:39.218  1602  1660 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-01 11:16:39.218  1602  1660 D KeyguardModel: createShortcutInfo...
09-01 11:16:39.218  1602  1602 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
09-01 11:16:39.219  8097  8165 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
09-01 11:16:39.219  2031  2031 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
09-01 11:16:39.224  1902  1902 D ActionManagerService: notifyUserLog: 1000004
09-01 11:16:39.224  2031  2031 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
09-01 11:16:39.224  3827  4508 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
09-01 11:16:39.225  3827  4509 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,09-01 11:16:39.229  1602  1660 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
,09-01 11:16:39.229  1602  1660 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-01 11:16:39.229  1602  1660 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
09-01 11:16:39.230  1602  1660 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-01 11:16:39.232  1602  1660 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-01 11:16:39.233  1602  1660 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
09-01 11:16:39.236  2031  2031 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
09-01 11:16:39.236  2031  2031 I GBoardWebViewUtils: , create_time: 1430832262123
09-01 11:16:39.236  2031  2031 I GBoardWebViewUtils: , expire_time: 0
09-01 11:16:39.236  2031  2031 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
09-01 11:16:39.236  2031  2031 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
09-01 11:16:39.236  2031  2031 I GBoardWebViewUtils: , display: false
09-01 11:16:39.236  2031  2031 I GBoardWebViewUtils: , animation: false }
09-01 11:16:39.236  2031  2031 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
09-01 11:16:39.236  2031  2031 I GBoardWebViewUtils: , create_time: 1430832262287
09-01 11:16:39.236  2031  2031 I GBoardWebViewUtils: , expire_time: 0
09-01 11:16:39.236  2031  2031 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
09-01 11:16:39.236  2031  2031 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
09-01 11:16:39.236  2031  2031 I GBoardWebViewUtils: , display: false
09-01 11:16:39.236  2031  2031 I GBoardWebViewUtils: , animation: false }
09-01 11:16:39.236  2031  2031 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1472216587976
09-01 11:16:39.236  2031  2031 I GBoardWebViewUtils: , create_time: 1472216588858
09-01 11:16:39.236  2031  2031 I GBoardWebViewUtils: , expire_time: 0
09-01 11:16:39.236  2031  2031 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
09-01 11:16:39.236  2031  2031 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
09-01 11:16:39.236  2031  2031 I GBoardWebViewUtils: , display: false
09-01 11:16:39.236  2031  2031 I GBoardWebViewUtils: , animation: false }
,09-01 11:16:39.255  1034  1959 V SIM_STK : Menu title from STK is T-Mobile
09-01 11:16:39.255  1034  1959 V SIM_STK : Menu title from STK is T-Mobile
09-01 11:16:39.259  1602  1602 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
09-01 11:16:39.259  1602  1602 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
09-01 11:16:39.260  6814  6814 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-01 11:16:39.260  1602  1660 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-01 11:16:39.261  1602  1660 D KeyguardModel: createShortcutInfo...
09-01 11:16:39.266  1602  1660 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
09-01 11:16:39.266  1602  1660 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-01 11:16:39.267  1602  1660 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-01 11:16:39.267  1602  1660 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,09-01 11:16:39.272  1602  1660 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-01 11:16:39.272  1602  1660 D KeyguardModel: createShortcutInfo...
09-01 11:16:39.272  1867  1867 D SplitUIManager: split_name #11 / not available #0
09-01 11:16:39.272  1867  1867 D SplitUIService: removed split : 
09-01 11:16:39.280  1602  1660 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-01 11:16:39.280  1602  1660 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-01 11:16:39.280  1602  1660 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
09-01 11:16:39.280  1602  1660 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-01 11:16:39.285  2031  8231 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
09-01 11:16:39.289  1602  1660 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-01 11:16:39.289  1602  1660 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
09-01 11:16:39.291  1602  1660 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-01 11:16:39.291  1602  1660 D KeyguardModel: createShortcutInfo...
,09-01 11:16:39.301  2031  2031 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-01 11:16:39.301  2031  2031 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
09-01 11:16:39.303  6814  6814 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-01 11:16:39.305  1602  1602 D KeyguardModel: handleShortcutListChanged...
09-01 11:16:39.305  1602  1602 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
09-01 11:16:39.307  8169  8169 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-01 11:16:39.307  8169  8169 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-01 11:16:39.308  8169  8169 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-01 11:16:39.310  8097  8097 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-01 11:16:39.311  8097  8166 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-01 11:16:39.313  1602  1660 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-01 11:16:39.313  1602  1660 D KeyguardModel: createShortcutInfo...
09-01 11:16:39.316  6814  6814 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-01 11:16:39.317  1034  1779 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
09-01 11:16:39.318  7604  7604 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
09-01 11:16:39.318  7604  7604 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-01 11:16:39.318  7604  7604 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-01 11:16:39.319  7604  7604 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-01 11:16:39.319  7604  7604 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-01 11:16:39.319  7604  7604 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-01 11:16:39.319  7604  7604 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-01 11:16:39.319  7604  7604 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-01 11:16:39.319  7604  7604 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-01 11:16:39.319  7604  7604 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-01 11:16:39.319  7604  7604 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-01 11:16:39.322  1602  1660 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-01 11:16:39.322  1602  1660 D KeyguardModel: createShortcutInfo...
09-01 11:16:39.324  1034  2030 V SIM_STK : Menu title from STK is T-Mobile
,09-01 11:16:39.348  1602  1660 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-01 11:16:39.348  1602  1660 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
,09-01 11:16:39.349  1602  1660 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-01 11:16:39.349  1602  1660 D KeyguardModel: createShortcutInfo...
09-01 11:16:39.357  1867  1867 D SplitUIManager: split_name #11 / not available #0
09-01 11:16:39.357  1867  1867 I SplitUIService: split app #11
09-01 11:16:39.358  1602  1660 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-01 11:16:39.358  1602  1660 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,09-01 11:16:39.361  1602  1660 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-01 11:16:39.361  1602  1660 D KeyguardModel: createShortcutInfo...
09-01 11:16:39.362  6814  6814 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-01 11:16:39.364  1602  1660 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-01 11:16:39.364  1602  1660 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
09-01 11:16:39.365  1602  1660 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-01 11:16:39.365  1602  1660 D KeyguardModel: createShortcutInfo...
09-01 11:16:39.370  1034  1034 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
09-01 11:16:39.370  1034  1034 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-01 11:16:39.370  1034  1034 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-01 11:16:39.371  8169  8169 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-01 11:16:39.371  8169  8169 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-01 11:16:39.371  8169  8169 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-01 11:16:39.372  1034  1577 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
,09-01 11:16:39.374  1602  1602 D KeyguardModel: handleShortcutListChanged...
09-01 11:16:39.374  1602  1602 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
09-01 11:16:39.376  6814  6814 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-01 11:16:39.376  6814  6814 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-01 11:16:39.376  6814  6814 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-01 11:16:39.376  6814  6814 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-01 11:16:39.376  6814  6814 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-01 11:16:39.377  6814  6814 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-01 11:16:39.377  6814  6814 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
09-01 11:16:39.377  6814  6814 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-01 11:16:39.377  6814  6814 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-01 11:16:39.377  6814  6814 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-01 11:16:39.377  6814  6814 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
09-01 11:16:39.377  6814  6814 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-01 11:16:39.380  8097  8097 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-01 11:16:39.380  8097  8166 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-01 11:16:39.383  2031  2031 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
,09-01 11:16:39.386  6814  6814 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-01 11:16:39.391  6814  6814 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-01 11:16:39.401  8169  8169 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-01 11:16:39.401  8169  8169 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-01 11:16:39.401  8169  8169 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-01 11:16:39.403  8097  8097 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-01 11:16:39.406  8097  8166 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-01 11:16:39.406  6814  6814 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-01 11:16:39.413  6814  6814 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-01 11:16:39.421  8169  8169 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-01 11:16:39.421  8169  8169 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-01 11:16:39.421  8169  8169 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-01 11:16:39.424  8097  8166 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-01 11:16:39.424  8097  8097 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-01 11:16:39.431  6814  6814 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-01 11:16:39.440  6814  6814 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-01 11:16:39.444  8169  8169 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-01 11:16:39.445  8169  8169 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-01 11:16:39.445  8169  8169 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-01 11:16:39.446  8097  8097 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-01 11:16:39.454  1034  1102 I art     : Explicit concurrent mark sweep GC freed 82584(4MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/65MB, paused 2.097ms total 242.457ms
,09-01 11:16:39.477  2031  2031 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,09-01 11:16:39.482  2031  2031 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-01 11:16:39.483  2031  2031 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
09-01 11:16:39.485  2031  2031 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
09-01 11:16:39.486  2031  2031 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
09-01 11:16:39.487  2031  2031 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
09-01 11:16:39.500  6814  6814 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-01 11:16:39.504  1034  1097 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{30027bec u0 com.lge.launcher2/.Launcher t5} time:203076
09-01 11:16:39.505  6814  6814 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-01 11:16:39.508  8169  8169 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-01 11:16:39.508  8169  8169 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-01 11:16:39.508  8169  8169 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-01 11:16:39.511  2031  2031 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
09-01 11:16:39.511  2031  2031 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-01 11:16:39.513  8097  8097 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-01 11:16:39.518  2031  2156 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
09-01 11:16:39.518  2031  2156 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
09-01 11:16:39.521  6814  6814 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-01 11:16:39.524  6814  6814 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-01 11:16:39.527  8169  8169 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-01 11:16:39.527  8169  8169 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-01 11:16:39.528  2031  2031 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
09-01 11:16:39.529  2031  2031 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
09-01 11:16:39.529  2031  2031 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,09-01 11:16:39.531  8169  8169 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-01 11:16:39.533  8097  8097 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-01 11:16:39.536  6814  6814 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-01 11:16:39.537  2031  2031 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
09-01 11:16:39.538  2606  2606 D [Concierge]Service: onStartCommand(). Type : 8
09-01 11:16:39.538  2606  2606 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
09-01 11:16:39.539  2606  2606 D [Concierge]Service: Update widget ID : 11
09-01 11:16:39.540  6814  6814 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-01 11:16:39.541  2031  2031 D [Concierge]WidgetView: change position of spinner
,09-01 11:16:39.543  8169  8169 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-01 11:16:39.543  8169  8169 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-01 11:16:39.543  8169  8169 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-01 11:16:39.545  2606  2606 D [Concierge]Service: onStartCommand(). Type : 0
09-01 11:16:39.545  8097  8097 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-01 11:16:39.546  2031  2031 I [Concierge]WidgetView: initWebView(). Time : 1472721399546
09-01 11:16:39.548  8051  8051 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-01 11:16:39.550  8051  8051 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
09-01 11:16:39.552  6814  6814 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-01 11:16:39.555  6814  6814 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-01 11:16:39.558  8169  8169 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-01 11:16:39.558  8169  8169 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-01 11:16:39.559  8169  8169 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-01 11:16:39.559  8169  8169 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-01 11:16:39.559  8169  8169 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-01 11:16:39.562  8097  8097 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-01 11:16:39.564  8051  8051 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,09-01 11:16:39.564  8051  8051 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
09-01 11:16:39.566  6814  6814 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-01 11:16:39.569  6814  6814 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-01 11:16:39.573  8169  8169 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-01 11:16:39.573  8169  8169 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-01 11:16:39.573  8169  8169 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-01 11:16:39.574  8169  8169 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-01 11:16:39.574  8172  8172 D AndroidRuntime: Shutting down VM
09-01 11:16:39.574  8169  8169 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-01 11:16:39.576  2031  2031 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 357150620
,09-01 11:16:39.577  2031  2031 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
09-01 11:16:39.577  2031  2031 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
09-01 11:16:39.577  8097  8097 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
09-01 11:16:39.581  2031  2031 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@20a544ec
09-01 11:16:39.581  2031  2031 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
09-01 11:16:39.582  2031  2031 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
09-01 11:16:39.583  2031  2031 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-01 11:16:39.588  2031  2031 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
,09-01 11:16:39.588  2031  2031 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
09-01 11:16:39.589  2031  2031 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
09-01 11:16:39.597  1034  1102 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8239 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
09-01 11:16:39.599  2031  2031 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1472721225001, New one : 1472721399546
09-01 11:16:39.600  2031  2031 D [Concierge]WidgetView: Unregister all receivers
09-01 11:16:39.600  2031  2031 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
,09-01 11:16:39.600  2031  2031 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-01 11:16:39.602  2031  2031 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
09-01 11:16:39.604  1034  1091 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-01 11:16:39.604  2031  2031 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
09-01 11:16:39.605  2031  2031 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
09-01 11:16:39.606  2031  2031 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
09-01 11:16:39.607  2031  2031 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
09-01 11:16:39.608  2031  2031 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-01 11:16:39.608  2031  2031 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-01 11:16:39.613  1034  1091 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,09-01 11:16:39.615  8169  8169 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
09-01 11:16:39.619  8169  8169 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
09-01 11:16:39.619  8169  8169 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
09-01 11:16:39.643  8169  8169 D LgDataFeature: LgDataFeature() Constructor: none
09-01 11:16:39.643  8169  8169 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-01 11:16:39.649  8169  8169 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
09-01 11:16:39.650  8169  8169 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
09-01 11:16:39.650  8169  8169 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
09-01 11:16:39.650  8169  8169 V SoundPool: doLoad: loading sample sampleID=1
09-01 11:16:39.650  8169  8169 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
09-01 11:16:39.652  7627  7627 D UEI.SmartControl: QS Service created
09-01 11:16:39.655  8169  8169 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,09-01 11:16:39.658  8169  8169 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-01 11:16:39.658  8169  8169 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
09-01 11:16:39.660  7627  7627 I UEI.SmartControl: Service initServices...
09-01 11:16:39.660  7627  7627 D UEI.SmartControl: QS start get config
09-01 11:16:39.664  2031  2031 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
09-01 11:16:39.665  8169  8169 V LGMDMManager: Create singleton instance
09-01 11:16:39.670  8169  8259 V SoundPool: Start decode
09-01 11:16:39.670  8169  8259 V MediaPlayer[Native]: decode(31, 10857164, 17813)
09-01 11:16:39.670   313  2202 V MediaPlayerService: decode(23, 10857164, 17813)
09-01 11:16:39.670   313  2202 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
09-01 11:16:39.670   313  2202 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
09-01 11:16:39.670   313  2202 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
09-01 11:16:39.670   313  2202 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
09-01 11:16:39.670   313  2202 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
09-01 11:16:39.670   313  2202 V MediaPlayerService: player type = 3
09-01 11:16:39.670   313  2202 V AwesomePlayer: AwesomePlayer create()
09-01 11:16:39.670   313  2202 V AwesomePlayer: reset_l() 
09-01 11:16:39.671   313  2202 V AwesomePlayer: cancelPlayerEvents
09-01 11:16:39.671   313  2202 V AwesomePlayer: setAudioSink() 
09-01 11:16:39.671   313  2202 V AwesomePlayer: reset_l() 
09-01 11:16:39.671   313  2202 V AudioCache: notify(0xb5474740, 8, 0, 0)
09-01 11:16:39.671   313  2202 V AudioCache: ignored
09-01 11:16:39.671   313  2202 V AwesomePlayer: cancelPlayerEvents
09-01 11:16:39.671   313  2202 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
09-01 11:16:39.671   313  2202 V AwesomePlayer: setDataSource_l dataSource
09-01 11:16:39.671   313  2202 V LGParserOSAL: SniffLGParser start
09-01 11:16:39.671   313  2202 V LGParserOSAL: MainType:5, SubType=0
09-01 11:16:39.671   313  2202 V LGParserOSAL: #### check Mime : application/ogg
09-01 11:16:39.671   313  2202 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
09-01 11:16:39.671   313  2202 E MediaExtractor: Use LGExtractor :application/ogg 
09-01 11:16:39.671  2031  2031 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
09-01 11:16:39.671  2031  2031 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
09-01 11:16:39.672  2031  2031 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,09-01 11:16:39.675  2031  2031 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-01 11:16:39.700   313  2202 V LGParserOSAL: supported mime: application/ogg
09-01 11:16:39.701   313  2202 V AwesomePlayer: setDataSource_l() extractor countTracks=1
09-01 11:16:39.701   313  2202 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
09-01 11:16:39.701   313  2202 V AwesomePlayer: mBitrate = -1 bits/sec
09-01 11:16:39.701   313  2202 V AwesomePlayer: AudioTrack Setting
09-01 11:16:39.701   313  2202 V AwesomePlayer: AudioTrack Setting channelCount = 2
09-01 11:16:39.701   313  2202 V AwesomePlayer: setAudioSource() 
09-01 11:16:39.701   313  2202 V MediaPlayerService: prepare
09-01 11:16:39.701   313  2202 V AwesomePlayer: prepareAsync_l() 
09-01 11:16:39.701   313  2202 V MediaPlayerService: wait for prepare
09-01 11:16:39.701   313  8260 V AwesomePlayer: onPrepareAsyncEvent() 
09-01 11:16:39.701   313  8260 V AwesomePlayer: initAudioDecoder() 
09-01 11:16:39.701   313  8260 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-01 11:16:39.701   313  8260 V AudioSystem: isOffloadSupported()
09-01 11:16:39.701   313  8260 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-01 11:16:39.701   313  8260 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-01 11:16:39.701   313  8260 I AudioFlinger: isAudioPlaybackHookOn() false
09-01 11:16:39.701   313  8260 V AwesomePlayer: getUseOffload() = 0 
09-01 11:16:39.701   313  8260 V OMXCodec: OMXCodec::Create
09-01 11:16:39.701   313  8260 V OMXCodec: findMatchingCodecs()
09-01 11:16:39.701   313  8260 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
09-01 11:16:39.701   313  8260 V OMXCodec: matchingCodecs.size()=1
09-01 11:16:39.701   313  8260 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
09-01 11:16:39.702   313  8260 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
09-01 11:16:39.702   313  8260 V LGCodecAdapter: LG Codec Adapter start
09-01 11:16:39.702   313  8260 V OMXCodec: OMXCodec Createtor
09-01 11:16:39.702   313  8260 V OMXCodec: setComponentRole
09-01 11:16:39.702   313  8260 V OMXCodec: configureCodec protected=0
09-01 11:16:39.702   313  8260 V LGCodecAdapter: called getLGCodecSpecificData
09-01 11:16:39.702   313  8260 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
09-01 11:16:39.702   313  8260 V LGCodecOSAL: Called LGconfigureCodecMETA
09-01 11:16:39.702   313  8260 V LGCodecOSAL: Called LGconfigureCodecMSG
09-01 11:16:39.702   313  8260 V LGCodecOSAL: Not support LGCodec
09-01 11:16:39.702   313  8260 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-01 11:16:39.702   313  8260 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
09-01 11:16:39.702   313  8260 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
09-01 11:16:39.702   313  8260 I AwesomePlayer: Could not offload audio decode, try pcm offload
09-01 11:16:39.702   313  8260 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-01 11:16:39.702   313  8260 V AudioSystem: isOffloadSupported()
09-01 11:16:39.702   313  8260 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-01 11:16:39.702   313  8260 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-01 11:16:39.702   313  8260 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
09-01 11:16:39.702 ,  313  8260 V OMXCodec: init()
09-01 11:16:39.702   313  8260 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
09-01 11:16:39.702   313  8260 V OMXCodec: allocateBuffers
09-01 11:16:39.702   313  8260 V OMXCodec: allocateBuffersOnPort portIndex=0
09-01 11:16:39.702   313  8260 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
09-01 11:16:39.702   313  8260 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7650 on input port
09-01 11:16:39.702   313  8260 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7970 on input port
09-01 11:16:39.702   313  8260 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on input port
09-01 11:16:39.702   313  8260 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on input port
09-01 11:16:39.702   313  8260 V OMXCodec: allocateBuffersOnPort portIndex=1
09-01 11:16:39.702   313  8260 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-01 11:16:39.703   313  8260 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on output port
09-01 11:16:39.703   313  8260 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
09-01 11:16:39.703   313  8260 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on output port
09-01 11:16:39.703   313  8260 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on output port
09-01 11:16:39.703   313  8260 V OMXCodec: init() mAsyncCompletion wait!!! 
09-01 11:16:39.704  2031  2031 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3b812de1 time:203276
,09-01 11:16:39.705   313  8262 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-01 11:16:39.705   313  8262 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-01 11:16:39.705   313  8262 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
09-01 11:16:39.705   313  8262 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
09-01 11:16:39.705   313  8262 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
09-01 11:16:39.705   313  8262 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
09-01 11:16:39.706   313  8260 V OMXCodec: init() mAsyncCompletion wait free! 
09-01 11:16:39.706   313  8260 V AwesomePlayer: finishAsyncPrepare_l() 
09-01 11:16:39.706   313  8260 V AudioCache: notify(0xb5474740, 5, 0, 0)
09-01 11:16:39.706   313  8260 V AudioCache: ignored
09-01 11:16:39.706   313  8260 V AudioCache: notify(0xb5474740, 1, 0, 0)
09-01 11:16:39.706   313  8260 V AudioCache: prepared
09-01 11:16:39.706   313  2202 V AudioCache: wait - success
09-01 11:16:39.706   313  2202 V MediaPlayerService: start
09-01 11:16:39.706   313  2202 V AwesomePlayer: play_l() 
09-01 11:16:39.706   313  2202 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
09-01 11:16:39.706   313  2202 V AwesomePlayer: createAudioPlayer_l
09-01 11:16:39.706   313  2202 V AwesomePlayer: seekAudioIfNecessary_l() 
09-01 11:16:39.706   313  2202 V AwesomePlayer: startAudioPlayer_l() 
09-01 11:16:39.706   313  2202 D AudioPlayer: start of Playback, useOffload 0
09-01 11:16:39.706   313  2202 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-01 11:16:39.706   313  2202 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-01 11:16:39.708   313  8262 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
09-01 11:16:39.708   313  8262 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
09-01 11:16:39.708   313  8262 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
09-01 11:16:39.708   313  8262 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
09-01 11:16:39.708   313  8262 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
09-01 11:16:39.708   313  8262 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-01 11:16:39.708   313  8262 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884848
09-01 11:16:39.708   313  8262 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-01 11:16:39.708   313  8262 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885008
09-01 11:16:39.708   313  8262 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-01 11:16:39.708   313  8262 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885088
09-01 11:16:39.708   313  8262 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-01 11:16:39.708   313  8262 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885328
09-01 11:16:39.708   313  8262 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-01 11:16:39.708   313  8262 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
09-01 11:16:39.708   313  8262 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-01 11:16:39.708   313  8262 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
09-01 11:16:39.708   313  8262 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
09-01 11:16:39.708   313  8262 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
09-01 11:16:39.708   313  8262 V OMXCodec: allocateBuffersOnPort portIndex=1
09-01 11:16:39.709   313  8262 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-01 11:16:39.709   313  8262 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on output port
0,9-01 11:16:39.709   313  8262 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
09-01 11:16:39.709   313  8262 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on output port
09-01 11:16:39.709   313  8262 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57c0100 on output port
09-01 11:16:39.709   313  8262 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
09-01 11:16:39.709   313  8262 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
09-01 11:16:39.709   313  2202 V AudioCache: open(48000, 2, 0x0, 1, 4)
09-01 11:16:39.709   313  2202 V AudioCache: notify(0xb5474740, 6, 0, 0)
09-01 11:16:39.709   313  2202 V AudioCache: ignored
09-01 11:16:39.710   313  2202 V MediaPlayerService: wait for playback complete
09-01 11:16:39.710  8169  8169 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
09-01 11:16:39.710  8169  8169 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
09-01 11:16:39.711   313  8263 V AudioCache: write(0xb1789000, 4096)
09-01 11:16:39.711   313  8263 V AudioCache: memcpy(0xac300000, 0xb1789000, 4096)
09-01 11:16:39.711  8169  8169 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:2908
09-01 11:16:39.712   313  8263 V AudioCache: write(0xb1789000, 4096)
09-01 11:16:39.712   313  8263 V AudioCache: memcpy(0xac301000, 0xb1789000, 4096)
09-01 11:16:39.712   313  8263 V AudioCache: write(0xb1789000, 4096)
09-01 11:16:39.712   313  8263 V AudioCache: memcpy(0xac302000, 0xb1789000, 4096)
09-01 11:16:39.713  8097  8097 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
09-01 11:16:39.713   313  8263 V AudioCache: write(0xb1789000, 4096)
09-01 11:16:39.713   313  8263 V AudioCache: memcpy(0xac303000, 0xb1789000, 4096)
09-01 11:16:39.714   313  8263 V AudioCache: write(0xb1789000, 4096)
09-01 11:16:39.714   313  8263 V AudioCache: memcpy(0xac304000, 0xb1789000, 4096)
09-01 11:16:39.714   313  8263 V AudioCache: write(0xb1789000, 4096)
09-01 11:16:39.714   313  8263 V AudioCache: memcpy(0xac305000, 0xb1789000, 4096)
09-01 11:16:39.714   313  8263 V AudioCache: write(0xb1789000, 4096)
09-01 11:16:39.714   313  8263 V AudioCache: memcpy(0xac306000, 0xb1789000, 4096)
09-01 11:16:39.715  1815  1815 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
09-01 11:16:39.716   313  8263 V AudioCache: write(0xb1789000, 4096)
09-01 11:16:39.716   313  8263 V AudioCache: memcpy(0xac307000, 0xb1789000, 4096)
09-01 11:16:39.716   313  8263 V AudioCache: write(0xb1789000, 4096)
09-01 11:16:39.716   313  8263 V AudioCache: memcpy(0xac308000, 0xb1789000, 4096)
09-01 11:16:39.716   313  8263 V AudioCache: write(0xb1789000, 4096)
09-01 11:16:39.716   313  8263 V AudioCache: memcpy(0xac309000, 0xb1789000, 4096)
09-01 11:16:39.716   313  8263 V AudioCache: write(0xb1789000, 4096)
09-01 11:16:39.716   313  8263 V AudioCache: memcpy(0xac30a000, 0xb1789000, 4096)
09-01 11:16:39.718   313  8263 V AudioCache: write(0xb1789000, 4096)
09-01 11:16:39.718   313  8263 V AudioCache: memcpy(0xac30b000, 0xb1789000, 4096)
09-01 11:16:39.718   313  8263 V AudioCache: write(0xb1789000, 4096)
09-01 11:16:39.718   313  8263 V AudioCache: memcpy(0xac30c000, 0xb1789000, 4096)
09-01 11:16:39.718   313  8263 V AudioCache: write(0xb1789000, 4096)
09-01 11:16:39.718   313  8263 V AudioCache: memcpy(0xac30d000, 0xb1789000, 4096)
09-01 11:16:39.720  2180  2180 I ConfigService: onCreate
09-01 11:16:39.720   313  8263 V AudioCache: write(0xb1789000, 4096)
09-01 11:16:39.720   313  8263 V AudioCache: memcpy(0xac30e000, 0xb1789000, 4096)
09-01 11:16:39.720   313  8263 V AudioCache: write(0xb1789000, 4096)
09-01 11:16:39.720   313  8263 V ,AudioCache: memcpy(0xac30f000, 0xb1789000, 4096)
09-01 11:16:39.720  2180  2180 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
09-01 11:16:39.720   313  8263 V AudioCache: write(0xb1789000, 4096)
09-01 11:16:39.720   313  8263 V AudioCache: memcpy(0xac310000, 0xb1789000, 4096)
09-01 11:16:39.721   313  8263 V AudioCache: write(0xb1789000, 4096)
09-01 11:16:39.721   313  8263 V AudioCache: memcpy(0xac311000, 0xb1789000, 4096)
09-01 11:16:39.721   313  8263 V AudioCache: write(0xb1789000, 4096)
09-01 11:16:39.721   313  8263 V AudioCache: memcpy(0xac312000, 0xb1789000, 4096)
09-01 11:16:39.721   313  8263 V AudioCache: write(0xb1789000, 4096)
09-01 11:16:39.721   313  8263 V AudioCache: memcpy(0xac313000, 0xb1789000, 4096)
09-01 11:16:39.722   313  8263 V AudioCache: write(0xb1789000, 4096)
09-01 11:16:39.722   313  8263 V AudioCache: memcpy(0xac314000, 0xb1789000, 4096)
09-01 11:16:39.722   313  8263 V AudioCache: write(0xb1789000, 4096)
09-01 11:16:39.722   313  8263 V AudioCache: memcpy(0xac315000, 0xb1789000, 4096)
09-01 11:16:39.722  1815  1815 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
09-01 11:16:39.723  2180  2180 I ConfigService: onBind returning update interface
09-01 11:16:39.724   313  8263 V AudioCache: write(0xb1789000, 4096)
09-01 11:16:39.724   313  8263 V AudioCache: memcpy(0xac316000, 0xb1789000, 4096)
09-01 11:16:39.724  2180  2180 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
09-01 11:16:39.724  2180  2180 I ConfigService: onBind returning config service
09-01 11:16:39.724   313  8263 V AudioCache: write(0xb1789000, 4096)
09-01 11:16:39.724   313  8263 V AudioCache: memcpy(0xac317000, 0xb1789000, 4096)
09-01 11:16:39.724   313  8263 V AudioCache: write(0xb1789000, 4096)
09-01 11:16:39.725   313  8263 V AudioCache: memcpy(0xac318000, 0xb1789000, 4096)
09-01 11:16:39.725   313  8263 V AudioCache: write(0xb1789000, 4096)
09-01 11:16:39.725   313  8263 V AudioCache: memcpy(0xac319000, 0xb1789000, 4096)
09-01 11:16:39.725   313  8263 V AudioCache: write(0xb1789000, 4096)
09-01 11:16:39.725   313  8263 V AudioCache: memcpy(0xac31a000, 0xb1789000, 4096)
09-01 11:16:39.726   313  8263 V AudioCache: write(0xb1789000, 4096)
09-01 11:16:39.726   313  8263 V AudioCache: memcpy(0xac31b000, 0xb1789000, 4096)
09-01 11:16:39.726   313  8263 V AudioCache: write(0xb1789000, 4096)
09-01 11:16:39.726   313  8263 V AudioCache: memcpy(0xac31c000, 0xb1789000, 4096)
09-01 11:16:39.727   313  8263 V AudioCache: write(0xb1789000, 4096)
09-01 11:16:39.727   313  8263 V AudioCache: memcpy(0xac31d000, 0xb1789000, 4096)
09-01 11:16:39.727   313  8263 V AudioCache: write(0xb1789000, 4096)
09-01 11:16:39.727   313  8263 V AudioCache: memcpy(0xac31e000, 0xb1789000, 4096)
09-01 11:16:39.727   313  8263 V AudioCache: write(0xb1789000, 4096)
09-01 11:16:39.727   313  8263 V AudioCache: memcpy(0xac31f000, 0xb1789000, 4096)
09-01 11:16:39.730   313  8263 V AudioCache: write(0xb1789000, 4096)
09-01 11:16:39.730   313  8263 V AudioCache: memcpy(0xac320000, 0xb1789000, 4096)
09-01 11:16:39.730   313  8263 V AudioCache: write(0xb1789000, 4096)
09-01 11:16:39.730   313  8263 V AudioCache: memcpy(0xac321000, 0xb1789000, 4096)
09-01 11:16:39.731   313  8263 V AudioCache: write(0xb1789000, 4096)
09-01 11:16:39.731   313  8263 V AudioCache: memcpy(0xac322000, 0xb1789000, 4096)
09-01 11:16:39.731   313  8263 V AudioCache: write(0xb1789000, 4096)
09-01 11:16:39.731   313  8263 V AudioCache: memcpy(0xac323000, 0xb1789000, 4096)
09-01 11:16:39.731   313  8263 V AudioCache: write(0xb1789000, 4096)
09-01 11:16:39.731   313  8263 V AudioCache: memcpy(0xac324000, 0xb1789000, 4096)
09-01 11:16:39.732   313  8263 V AudioCache: write(0xb1789000, 4096)
09-01 11:16:39.732   313  8263 V AudioCache: memcpy(0xac325000, 0xb1789000, 4096)
09-01 11:16:39.732   313  8263 V AudioCache: write(0xb1789000, 4096)
09-01 11:16:39.732   313  8263 V AudioCache: memcpy(0xac326000, 0xb1789000, 4096)
09-01 11:16:39.732   313  8263 V AudioCache: write(0xb1789000, 4096)
09-01 11:16:39.733   313  8263 V AudioCache: memcpy(0xac327000, 0xb1789000, 4096)
09-01 11:16:39.733   313  8263 V AudioCache: write(0xb1789000, 4096)
09-01 11:16:39.733   313  8263 V AudioCache: memcpy(0xac328000, 0xb1789000, 4096)
09-01 11:16:39.733   313  8263 V AudioCache: write(0xb1789000, 4096)
09-01 11:16:39.733   313  8263 V AudioCache: memcpy(0xac329000, 0xb1789000, 4096)
09-01 11:16:39.734   313  8263 V AudioCache: write(0xb1789000, 4096)
09-01 11:16:39.734   313  8263 V AudioCache: memcpy(0xac32a000, 0xb1789000, 4096)
09-01 11:16:39.734   313  8263 V AudioCache: write(0xb1789000, 4096)
09-01 11:16:39.734   313  8263 V AudioCache: memcpy(0xac32b000, 0xb1789000, 4096)
09-01 11:16:39.735   313  8263 V AudioCache: write(0xb1789000, 4096)
09-01 11:16:39.735   313  8263 V AudioCache: memcpy(0xac32c000, 0xb1789000, 4096)
09-01 11:16:39.735   313  8263 V AudioCache: write(0xb1789000, 4096)
09-01 11:16:39.735   313  8263 V AudioCache: memcpy(0xac32d000, 0xb1789000, 4096)
09-01 11:16:39.735   313  8263 V AudioCache: write(0xb1789000, 4096)
09-01 11:16:39.735   313  8263 V AudioCache: memcpy(0xac32e000, 0xb1789000, 4096)
09-01 11:16:39.736   313  8263 V AudioCache: write(0xb1789000, 4096)
09-01 11:16:39.736   313  8263 V AudioCache: memcpy(0xac32f000, 0xb1789000, 4096)
09-01 11:16:39.736   313  8263 V AudioCache: write(0xb1789000, 4096)
09-01 11:16:39.736   313  8263 V AudioCache: memcpy(0xac330000, 0xb1789000, 4096)
09-01 11:16:39.736   313  8263 V AudioCache: write(0xb1789000, 4096)
09-01 11:16:39.736   313  8263 V AudioCache: memcpy(0xac331000, 0xb1789000, 4096)
09-01 11:16:39.737   313  8262 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
09-01 11:16:39.737   313  8263 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
09-01 11:16:39.737   313  8263 V AwesomePlayer: postAudioEOS() 
09-01 11:16:39.737   313  8263 V AudioCache: write(0xb1789000, 280)
09-01 11:16:39.737   313  8263 V AudioCache: memcpy(0xac332000, 0xb1789000, 280)
09-01 11:16:39.738   313  8260 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
,09-01 11:16:39.738   313  8260 V AwesomePlayer: onStreamDone
09-01 11:16:39.738   313  8260 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
09-01 11:16:39.738   313  8260 V AudioCache: notify(0xb5474740, 2, 0, 0)
09-01 11:16:39.738   313  8260 V AudioCache: playback complete
09-01 11:16:39.738   313  8260 V AwesomePlayer: pause_l() 
09-01 11:16:39.738   313  8260 V AudioCache: notify(0xb5474740, 7, 0, 0)
09-01 11:16:39.738   313  2202 V AudioCache: wait - success
09-01 11:16:39.738   313  8260 V AudioCache: ignored
09-01 11:16:39.738   313  2202 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
09-01 11:16:39.738   313  8260 V AwesomePlayer: cancelPlayerEvents
09-01 11:16:39.742  2180  2180 I ConfigService: onDestroy
09-01 11:16:39.742   313  8260 D AudioPlayer: Pause Playback at 1068125
09-01 11:16:39.743   313  2202 V AwesomePlayer: reset_l() 
09-01 11:16:39.743   313  2202 V AudioCache: notify(0xb5474740, 8, 0, 0)
09-01 11:16:39.743   313  2202 V AudioCache: ignored
09-01 11:16:39.743   313  2202 V AwesomePlayer: cancelPlayerEvents
09-01 11:16:39.743   313  2202 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
09-01 11:16:39.743   313  2202 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
09-01 11:16:39.743   313  2202 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
09-01 11:16:39.743   313  2202 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
09-01 11:16:39.743   313  2202 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-01 11:16:39.743   313  8262 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-01 11:16:39.743   313  8262 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-01 11:16:39.743   313  8262 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
09-01 11:16:39.743   313  8262 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 0
09-01 11:16:39.743   313  8262 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
09-01 11:16:39.743   313  8262 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 0
09-01 11:16:39.743   313  8262 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
09-01 11:16:39.743   313  8262 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7970 on port 0
09-01 11:16:39.743   313  8262 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
09-01 11:16:39.743   313  8262 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7650 on port 0
09-01 11:16:39.743   313  8262 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
09-01 11:16:39.743   313  8262 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-01 11:16:39.743   313  8262 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57c0100 on port 1
09-01 11:16:39.743   313  8262 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
09-01 11:16:39.743   313  8262 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 1
09-01 11:16:39.743   313  8262 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
09-01 11:16:39.743   313  8262 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 1
09-01 11:16:39.743   313  8262 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
09-01 11:16:39.743   313  8262 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ba0 on port 1
09-01 11:16:39.743   313  8262 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-01 11:16:39.744   313  8262 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
09-01 11:16:39.744   313  2202 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-01 11:16:39.744   313  2202 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-01 11:16:39.744   313  8262 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
09-01 11:16:39.744   313  8262 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
09-01 11:16:39.744   313  8262 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
09-01 11:16:39.744   313  2202 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-01 11:16:39.744   313  2202 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
09-01 11:16:39.744   313  2202 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
09-01 11:16:39.744   313  2202 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
09-01 11:16:39.744   313  2202 D AudioPlayer: AudioPlayer releasing audio source
09-01 11:16:39.744   313  2202 D AudioPlayer: AudioPlayer done releasing audio source
09-01 11:16:39.744   313  2202 V AwesomePlayer: reset_l() 
09-01 11:16:39.744   313  2202 V AwesomePlayer: cancelPlayerEvents
09-01 11:16:39.744   313  2202 V AwesomePlayer: ~AwesomePlayer call
09-01 11:16:39.745   313  2202 V AwesomePlayer: reset_l() 
09-01 11:16:39.745   313  2202 V AwesomePlayer: cancelPlayerEvents
09-01 11:16:39.745  8169  8259 V SoundPool: close(31)
09-01 11:16:39.745  8169  8259 V SoundPool: pointer = 0xa0026000, size = 205080, sampleRate = 48000, numChannels = 2
09-01 11:16:39.752  1815  8265 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
09-01 11:16:39.776  5969  8271 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
09-01 11:16:39.779  1815  8272 I PeopleContactsSync: CP2 sync disabled
09-01 11:16:39.791  1815  4784 I Icing   : doRemovePackageData com.test.thalitest
,09-01 11:16:39.796  1815  8270 W GmsApplication: Using Auth Proxy for data requests.
09-01 11:16:39.799  1815  8270 W GmsApplication: Using Auth Proxy for data requests.
09-01 11:16:39.814  2031  2031 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,09-01 11:16:39.822  7003  7003 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
,09-01 11:16:39.836  2353  8275 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
09-01 11:16:39.842  2180  2198 I art     : Explicit concurrent mark sweep GC freed 6158(368KB) AllocSpace objects, 0(0B) LOS objects, 52% free, 29MB/61MB, paused 586us total 16.269ms
,09-01 11:16:39.854  2031  2866 I GBoardtInterface: onReloaded()
,09-01 11:16:39.856  2031  2031 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
09-01 11:16:39.865  1034  1959 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8277 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
09-01 11:16:39.867  3827  4509 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,09-01 11:16:39.870  3827  3843 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-01 11:16:39.877  1902  1902 D ActionManagerService: notifyUserLog: 1000001
09-01 11:16:39.878  3827  4508 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
,09-01 11:16:39.878  3827  4508 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
09-01 11:16:39.881  1902  1902 D ActionManagerService: notifyUserLog: 1000001
09-01 11:16:39.882  3827  4508 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
09-01 11:16:39.882  3827  4508 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
09-01 11:16:39.882  3827  4508 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
09-01 11:16:39.883  3827  4508 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
09-01 11:16:39.883  3827  4509 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-01 11:16:39.885  2031  2031 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
09-01 11:16:39.885  2031  2031 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
09-01 11:16:39.887  2031  2031 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
09-01 11:16:39.887  2031  2031 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
09-01 11:16:39.889  2031  2031 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
09-01 11:16:39.889  2031  2031 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
,09-01 11:16:39.910  8277  8277 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-01 11:16:39.911  8277  8277 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-01 11:16:39.912  8277  8277 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-01 11:16:39.912  8277  8277 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,09-01 11:16:39.997  8277  8277 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,09-01 11:16:40.007  8277  8277 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
09-01 11:16:40.032  8277  8277 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-01 11:16:40.036  7627  7627 E UEI.SmartControl: unzip: java.io.IOException: write failed: EBADF (Bad file number)
09-01 11:16:40.037  7627  7627 I UEI.SmartControl: Specific region DB is not found, use default...
09-01 11:16:40.053  8277  8277 D LgDataFeature: LgDataFeature() Constructor: none
,09-01 11:16:40.053  8277  8277 D LgDataFeature: LgDataFeature() Constructor Done, null
09-01 11:16:40.059  7627  7627 E UEI.SmartControl: unzip: java.io.FileNotFoundException: /data/data/com.uei.lg.quicksetsdk.maxq616/app_korea/dac1a: open failed: EROFS (Read-only file system)
09-01 11:16:40.060  7627  7627 I UEI.SmartControl: Supports setup maps: true
09-01 11:16:40.060  7627  7627 W System.err: java.lang.NullPointerException: Attempt to get length of null array
09-01 11:16:40.060  7627  7627 W System.err: 	at com.uei.control.core.ab.b(Unknown Source)
09-01 11:16:40.060  7627  7627 W System.err: 	at com.uei.control.core.ab.a(Unknown Source)
09-01 11:16:40.060  7627  7627 W System.err: 	at com.uei.control.core.ab.a(Unknown Source)
09-01 11:16:40.060  7627  7627 W System.err: 	at com.uei.control.Service.a(Unknown Source)
09-01 11:16:40.060  7627  7627 W System.err: 	at com.uei.control.Service.onCreate(Unknown Source)
09-01 11:16:40.060  7627  7627 W System.err: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2738)
09-01 11:16:40.060  7627  7627 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
09-01 11:16:40.060  7627  7627 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
09-01 11:16:40.060  7627  7627 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 11:16:40.060  7627  7627 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-01 11:16:40.060  7627  7627 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-01 11:16:40.060  7627  7627 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 11:16:40.060  7627  7627 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-01 11:16:40.060  7627  7627 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-01 11:16:40.060  7627  7627 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-01 11:16:40.061  7627  7627 E UEI.SmartControl: java.lang.NullPointerException: Attempt to get length of null array
09-01 11:16:40.061  7627  7627 E UEI.SmartControl: 	at com.uei.control.core.ab.b(Unknown Source)
09-01 11:16:40.061  7627  7627 E UEI.SmartControl: 	at com.uei.control.core.ab.a(Unknown Source)
09-01 11:16:40.061  7627  7627 E UEI.SmartControl: 	at com.uei.control.core.ab.a(Unknown Source)
09-01 11:16:40.061  7627  7627 E UEI.SmartControl: 	at com.uei.control.Service.a(Unknown Source)
09-01 11:16:40.061  7627  7627 E UEI.SmartControl: 	at com.uei.control.Service.onCreate(Unknown Source)
09-01 11:16:40.061  7627  7627 E UEI.SmartControl: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2738)
09-01 11:16:40.061  7627  7627 E UEI.SmartControl: 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
09-01 11:16:40.061  7627  7627 E UEI.SmartControl: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
09-01 11:16:40.061  7627  7627 E UEI.SmartControl: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 11:16:40.061  7627  7627 E UEI.SmartControl: 	at android.os.Looper.loop(Looper.java:135)
09-01 11:16:40.061  7627  7627 E UEI.SmartControl: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-01 11:16:40.061  7627  7627 E UEI.SmartControl: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 11:16:40.061  7627  7627 E UEI.SmartControl: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-01 11:16:40.061  7627  7627 E UEI.SmartControl: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-01 11:16:40.061  7627  7627 E UEI.SmartControl: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-01 11:16:40.061  7627  7627 E UEI.SmartControl: 
09-01 11:16:40.061  7627  7627 E UEI.SmartControl: java.lang.NullPointerException: Attempt to get length of null array
09-01 11:16:40.061  7627  7627 E UEI.SmartControl: 	at com.uei.control.core.ab.b(Unknown Source)
09-01 11:16:40.061  7,627  7627 E UEI.SmartControl: 	at com.uei.control.core.ab.a(Unknown Source)
09-01 11:16:40.061  7627  7627 E UEI.SmartControl: 	at com.uei.control.core.ab.a(Unknown Source)
09-01 11:16:40.061  7627  7627 E UEI.SmartControl: 	at com.uei.control.Service.a(Unknown Source)
09-01 11:16:40.061  7627  7627 E UEI.SmartControl: 	at com.uei.control.Service.onCreate(Unknown Source)
09-01 11:16:40.061  7627  7627 E UEI.SmartControl: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2738)
09-01 11:16:40.061  7627  7627 E UEI.SmartControl: 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
09-01 11:16:40.061  7627  7627 E UEI.SmartControl: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
09-01 11:16:40.061  7627  7627 E UEI.SmartControl: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 11:16:40.061  7627  7627 E UEI.SmartControl: 	at android.os.Looper.loop(Looper.java:135)
09-01 11:16:40.061  7627  7627 E UEI.SmartControl: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-01 11:16:40.061  7627  7627 E UEI.SmartControl: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 11:16:40.061  7627  7627 E UEI.SmartControl: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-01 11:16:40.061  7627  7627 E UEI.SmartControl: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-01 11:16:40.061  7627  7627 E UEI.SmartControl: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-01 11:16:40.061  7627  7627 I UEI.SmartControl: ### init IR Blaster...
09-01 11:16:40.065  7627  7627 D serial_port: Configuring serial port
09-01 11:16:40.065  7627  7627 E UEI.SmartControl: UEIBLaster setting for 616
09-01 11:16:40.065  7627  7627 I UEI.SmartControl: Setting serial record hearder size = 2
09-01 11:16:40.065  7627  7627 I UEI.SmartControl: configuring settings for MAXQ616
09-01 11:16:40.065  7627  7627 I UEI.SmartControl: Get version...
,09-01 11:16:40.081  7627  8298 D UEI.SmartControl: serial port data available: 21
,09-01 11:16:40.104  8277  8277 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
09-01 11:16:40.110  7731  7731 E SharedPreferencesImpl: Couldn't rename file /data/data/com.android.gallery3d/shared_prefs/com.android.gallery3d_preferences.xml to backup file /data/data/com.android.gallery3d/shared_prefs/com.android.gallery3d_preferences.xml.bak

```
