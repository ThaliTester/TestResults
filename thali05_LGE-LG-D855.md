#### Test 79751015e87fad4_thali05_LGE-LG-D855 Logs


```
--------- beginning of main
08-05 14:14:00.070  1600  1600 I [SystemUI]Clock: called onTimeUpdated()
08-05 14:14:00.079  1600  1600 I LgeClockWidgetControlView: called onTimeUpdated()
08-05 14:14:00.079  1600  1600 I [SystemUI]DateView: called onTimeUpdated()
08-05 14:14:00.083  1600  1600 I [SystemUI]DateView: called onTimeUpdated()
08-05 14:14:00.083  1600  1600 D KeyguardUpdateMonitor: handleTimeUpdate
,08-05 14:14:01.981  6908  6908 D AndroidRuntime: 
08-05 14:14:01.981  6908  6908 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-05 14:14:01.986  6908  6908 D AndroidRuntime: CheckJNI is OFF
08-05 14:14:02.108  6908  6908 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-05 14:14:02.113  1030  1733 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-05 14:14:02.123  1938  1954 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-05 14:14:02.126  1030  1733 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-05 14:14:02.127  1030  1733 D ActivityManager: setTaskToReturnTo : TaskRecord{3fa9a0f8 #40 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-05 14:14:02.127  1030  1733 D ActivityManager: setTaskToReturnTo : TaskRecord{3fa9a0f8 #40 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-05 14:14:02.129  1030  1733 D WindowStateEx: AppWindowTokenEx init.. 
08-05 14:14:02.129   334   342 E GBMv2   : DFP En is all cleared set to be enabled
08-05 14:14:02.149  1030  1733 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6923 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-05 14:14:02.151  6908  6908 D AndroidRuntime: Shutting down VM
08-05 14:14:02.205  1938  2662 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-05 14:14:02.206  1938  2662 D SplitWindowPolicy: topRunningActivity=ActivityInfo{11e7388f co.....MainActivity}, taskId=40, activityType=0, bIsSplit=false
08-05 14:14:02.206  1938  1955 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-05 14:14:02.207  1938  1955 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2048d71c co.....MainActivity}, taskId=40, activityType=0, bIsSplit=false
08-05 14:14:02.283  6923  6923 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-05 14:14:02.379  6923  6923 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
08-05 14:14:02.388  6923  6923 I LibraryLoader: Loading: webviewchromium
08-05 14:14:02.391  6923  6923 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 8135-8139)
08-05 14:14:02.391  6923  6923 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-05 14:14:02.407  6923  6923 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {12a5f815}
08-05 14:14:02.408  6923  6923 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-05 14:14:02.409  6923  6923 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-05 14:14:02.419  6923  6923 I BrowserStartupController: Initializing chromium process, renderers=0
08-05 14:14:02.420  6923  6923 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-05 14:14:02.430   312   312 V AudioPolicyService: registerClient() client 0xb558a7e0, uid 10118
08-05 14:14:02.430  6923  6923 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-05 14:14:02.431  6923  6923 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-05 14:14:02.432  6923  6923 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-05 14:14:02.435  1030  1094 D BluetoothManagerService: Message: 20
08-05 14:14:02.436  1030  1094 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@10f0f5c2:true
08-05 14:14:02.449  6923  6923 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-05 14:14:02.449  6923  6923 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-05 14:14:02.449  6923  6923 I Adreno-EGL: Build Date: 12/12/14 금
08-05 14:14:02.449  6923  6923 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-05 14:14:02.449  6923  6923 I Adreno-EGL: Remote Branch: 
08-05 14:14:02.449  6923  6923 I Adreno-EGL: Local Patches: 
08-05 14:14:02.449  6923  6923 I Adreno-EGL: Reconstruct Branch: 
08-05 14:14:02.516  6923  6957 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
08-05 14:14:02.520  6923  6923 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-05 14:14:02.536  6923  6923 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-05 14:14:02.541  6923  6923 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-05 14:14:02.544  6923  6923 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-05 14:14:02.547  6923  6923 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-05 14:14:02.547  6923  6923 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-05 14:14:02.560  6923  6923 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
08-05 14:14:02.565  6923  6923 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-05 14:14:02.566  6923  6923 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-05 14:14:02.602  6923  6971 D OpenGLRenderer: Render dirty regions requested: true
08-05 14:14:02.603  6923  6971 I OpenGLRenderer: Initialized EGL, version 1.4
08-05 14:14:02.608  6923  6971 D OpenGLRenderer: Enabling debug mode 0
08-05 14:14:02.615  6923  6923 D Atlas   : Validating map...
08-05 14:14:02.618  1030  1951 D SplitWindow: check instance of lgWin Window{3c0a046c u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-05 14:14:02.652  6923  6968 D LgDataFeature: LgDataFeature() Constructor: none
08-05 14:14:02.652  6923  6968 D LgDataFeature: LgDataFeature() Constructor Done, null
08-05 14:14:02.750  6923  6923 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2dd081e8 time:328498
08-05 14:14:02.750  1030  1095 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +545ms (total +620ms)
08-05 14:14:02.751  1030  1095 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{21549d1 u0 com.test.thalitest/.MainActivity t40} time:328499
08-05 14:14:02.888  6923  6923 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
08-05 14:14:03.030  6923  6981 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435150848
08-05 14:14:03.046  6923  6981 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-05 14:14:03.046  6923  6981 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-05 14:14:03.046  6923  6981 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-05 14:14:03.046  6923  6981 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-05 14:14:03.046  6923  6981 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-05 14:14:03.046  6923  6981 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2829222c added. We now have 1 listener(s)
08-05 14:14:03.053  1030  1653 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 14:14:03.056  6923  6981 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-05 14:14:03.059  6923  6981 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-05 14:14:03.063  6923  6981 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 14:14:03.063  6923  6981 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 14:14:03.072  6923  6981 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-05 14:14:03.072  6923  6981 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-05 14:14:03.072  6923  6981 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-05 14:14:03.072  6923  6981 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-05 14:14:03.072  6923  6981 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-05 14:14:03.072  6923  6981 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-05 14:14:03.072  6923  6981 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-05 14:14:03.072  6923  6981 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-05 14:14:03.072  6923  6981 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-05 14:14:03.072  6923  6981 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-05 14:14:03.072  6923  6981 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-05 14:14:03.072  6923  6981 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-05 14:14:03.072  6923  6981 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-05 14:14:03.072  6923  6981 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-05 14:14:03.072  6923  6981 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30ada0fb added. We now have 1 listener(s)
08-05 14:14:03.074  6923  6981 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 14:14:03.079  1030  1401 D WifiService: New client listening to asynchronous messages
08-05 14:14:03.083  6923  6981 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-05 14:14:03.083  6923  6981 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-05 14:14:03.085  6923  6981 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-05 14:14:03.085  6923  6981 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-05 14:14:03.086  6923  6981 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-05 14:14:03.090  6923  6981 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 14:14:03.091  1030  1733 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 14:14:03.093  6923  6981 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-05 14:14:03.112  6923  6981 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-05 14:14:03.112  6923  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 14:14:03.112  6923  6981 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 14:14:03.112  6923  6981 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 14:14:03.112  6923  6981 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 14:14:03.112  6923  6981 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 14:14:03.112  6923  6981 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 14:14:03.112  6923  6981 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 14:14:03.112  6923  6981 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 14:14:03.112  6923  6981 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-05 14:14:03.112  6923  6981 D io.jxcore.node.ConnectivityMonitor: start: OK
08-05 14:14:03.114  6923  6981 I io.jxcore.node.LifeCycleMonitor: start: OK
08-05 14:14:03.117  6923  6923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 14:14:03.124  6923  6923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 14:14:03.158  6923  6968 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-05 14:14:03.158  6923  6968 I chromium: 
,08-05 14:14:03.227  6923  6923 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-05 14:14:03.313  6923  6923 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-05 14:14:03.313  6923  6923 I chromium: 
,08-05 14:14:04.103   334   344 E GBMv2   : DFP En is all cleared set to be enabled
,08-05 14:14:04.103   334   344 E GBMv2   : Set value is all cleared set the max
08-05 14:14:04.103   334   344 I GBMv2   : DFP Enabled. Ignore VFP set
,08-05 14:14:04.177  6923  6984 W jxcore-log: Initializing JXcore engine
08-05 14:14:04.178  6923  6984 W jxcore-log: JXcore engine is ready
,08-05 14:14:04.250  6984  6984 W Thread-812: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[6129]" dev="sockfs" ino=6129 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-05 14:14:04.250  6984  6984 W Thread-812: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,08-05 14:14:04.250  6984  6984 W Thread-812: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[10466]" dev="sockfs" ino=10466 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-05 14:14:04.250  6984  6984 W Thread-812: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-05 14:14:04.250  6984  6984 W Thread-812: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[31322]" dev="sockfs" ino=31322 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-05 14:14:04.272  6923  6984 W jxcore-log: Starting JXcore engine
,08-05 14:14:04.379  6923  6984 W jxcore-log: Platform android
08-05 14:14:04.379  6923  6984 W jxcore-log: 
08-05 14:14:04.379  6923  6984 W jxcore-log: Process ARCH arm
08-05 14:14:04.379  6923  6984 W jxcore-log: 
,08-05 14:14:04.632  6923  6984 I jxcore-log: JXcore Cordova bridge is ready!
08-05 14:14:04.632  6923  6984 I jxcore-log: 
08-05 14:14:04.632  6923  6984 W jxcore-log: JXcore engine is started
,08-05 14:14:04.642  6923  6981 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-05 14:14:04.645  6923  6923 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-05 14:14:08.795  1030  3563 I LocationManagerService: remove 16528ada
08-05 14:14:08.796  1030  3563 D LocationManagerService: provider request: passive ProviderRequest[ON interval=0]
08-05 14:14:08.796  1030  3563 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-05 14:14:08.797  1030  3563 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
08-05 14:14:08.798  1030  3563 D LocationManagerService: getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
08-05 14:14:08.799  1030  3563 D LocationManagerService: getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,08-05 14:14:20.349  6923  6984 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-05 14:14:20.349  6923  6984 I jxcore-log: 
08-05 14:14:20.352  6923  6984 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-05 14:14:20.352  6923  6984 I jxcore-log: 
,08-05 14:14:20.356  6923  6984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 14:14:20.356  6923  6984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 14:14:20.356  6923  6984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 14:14:20.356  6923  6984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 14:14:20.356  6923  6984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 14:14:20.356  6923  6984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 14:14:20.356  6923  6984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 14:14:20.356  6923  6984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 14:14:20.359  6923  6984 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-05 14:14:20.361  6923  6984 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-05 14:14:20.361  6923  6984 I jxcore-log: 
,08-05 14:14:20.363  6923  6984 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-05 14:14:20.363  6923  6984 I jxcore-log: 
08-05 14:14:20.697  6923  6984 D ExecuteNativeTests: Running unit tests
,08-05 14:14:20.778  6923  6984 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-05 14:14:20.778  6923  6984 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c999dec added. We now have 2 listener(s)
08-05 14:14:20.779  1030  1045 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-05 14:14:20.783  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-05 14:14:20.783  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 14:14:20.783  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 14:14:20.783  6923  6984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 14:14:20.783  6923  6984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c0e55b5 added. We now have 2 listener(s)
08-05 14:14:20.783  6923  6984 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 14:14:20.783  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-05 14:14:20.785  6923  6984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 14:14:20.790  6923  6984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 14:14:20.790  6923  6984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 14:14:20.790  6923  6984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 14:14:20.790  6923  6984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 14:14:20.790  6923  6984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 14:14:20.790  6923  6984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 14:14:20.790  6923  6984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 14:14:20.790  6923  6984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 14:14:20.791  6923  6984 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-05 14:14:20.791  6923  6984 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-05 14:14:20.795  6923  6923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 14:14:20.797  6923  6923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 14:14:20.802  6923  6984 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-05 14:14:20.807  6923  6984 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-05 14:14:20.807  6923  6984 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-05 14:14:20.813  6923  6984 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-05 14:14:20.814  6923  6984 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-05 14:14:20.814  6923  6984 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-05 14:14:20.814  6923  6984 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-05 14:14:20.814  6923  6984 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-05 14:14:20.815  6923  6984 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 14:14:20.815  6923  6984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 14:14:20.816  6923  6984 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 14:14:20.816  6923  6984 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 14:14:20.816  6923  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:20.816  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 14:14:20.816  6923  6984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 14:14:20.816  6923  6984 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c999dec removed from the list
08-05 14:14:20.816  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:20.817  6923  6984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c0e55b5 removed from the list
08-05 14:14:20.817  6923  6984 D io.jxcore.node.ConnectivityMonitor: stop
08-05 14:14:20.817  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:20.818  6923  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:20.818  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-05 14:14:20.820  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 14:14:20.820  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 14:14:20.820  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:20.820  6923  6984 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c0e55b5 not in the list
08-05 14:14:20.823  6923  6984 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-05 14:14:20.823  6923  6984 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 14:14:20.823  6923  6984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 14:14:20.823  6923  6984 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 14:14:20.823  6923  6984 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 14:14:20.823  6923  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:20.823  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:20.823  6923  6984 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c999dec not in the list
08-05 14:14:20.823  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-05 14:14:20.824  6923  6984 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c0e55b5 not in the list
08-05 14:14:20.824  6923  6984 D io.jxcore.node.ConnectivityMonitor: stop
08-05 14:14:20.824  6923  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:20.824  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:20.824  6923  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:20.824  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:20.824  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 14:14:20.824  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 14:14:20.824  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:20.824  6923  6984 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c0e55b5 not in the list
08-05 14:14:20.829  6923  6984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-05 14:14:20.829  6923  6984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-05 14:14:20.829  6923  6984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-05 14:14:20.829  6923  6984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-05 14:14:20.829  6923  6984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-05 14:14:20.829  6923  6984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-05 14:14:20.829  6923  6984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-05 14:14:20.829  6923  6984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-05 14:14:20.829  6923  6984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-05 14:14:20.829  6923  6984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-05 14:14:20.829  6923  6984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-05 14:14:20.829  6923  6984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-05 14:14:20.829  6923  6984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-05 14:14:20.829  6923  6984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-05 14:14:20.829  6923  6984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-05 14:14:20.829  6923  6984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-05 14:14:20.829  6923  6984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-05 14:14:20.829  6923  6984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnecti,ons: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-05 14:14:20.829  6923  6984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-05 14:14:20.829  6923  6984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-05 14:14:20.829  6923  6984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-05 14:14:20.829  6923  6984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-05 14:14:20.829  6923  6984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-05 14:14:20.829  6923  6984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-05 14:14:20.829  6923  6984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-05 14:14:20.829  6923  6984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-05 14:14:20.829  6923  6984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-05 14:14:20.829  6923  6984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-05 14:14:20.829  6923  6984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,08-05 14:14:20.829  6923  6984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-05 14:14:20.829  6923  6984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-05 14:14:20.829  6923  6984 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 14:14:20.829  6923  6984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 14:14:20.829  6923  6984 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-05 14:14:20.831  6923  6984 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 14:14:20.831  6923  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:20.831  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:20.831  6923  6984 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c999dec not in the list
08-05 14:14:20.831  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:20.831  6923  6984 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c0e55b5 not in the list
08-05 14:14:20.831  6923  6984 D io.jxcore.node.ConnectivityMonitor: stop
08-05 14:14:20.831  6923  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:20.831  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:20.831  6923  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:20.831  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:20.832  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 14:14:20.832  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 14:14:20.832  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:20.832  6923  6984 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c0e55b5 not in the list
08-05 14:14:20.833  6923  6984 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-05 14:14:20.835  6923  6984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 14:14:20.837  6923  6984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 14:14:20.837  6923  6984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 14:14:20.837  6923  6984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 14:14:20.837  6923  6984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 14:14:20.837  6923  6984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 14:14:20.837  6923  6984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 14:14:20.837  6923  6984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 14:14:20.837  6923  6984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 14:14:20.838  6923  6984 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-05 14:14:20.838  6923  6984 D io.jxcore.node.ConnectivityMonitor: start: OK
08-05 14:14:20.839  6923  6923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 14:14:20.840  6923  6923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 14:14:20.840  6923  6984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-05 14:14:20.840  6923  6984 V io.jxcore.n,ode.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-05 14:14:20.840  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-05 14:14:20.840  6923  6984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 14:14:20.840  6923  6984 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-05 14:14:20.844  6923  6984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-05 14:14:20.844  1030  1915 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-05 14:14:20.851  6923  6984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-05 14:14:20.857  6923  6984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-05 14:14:20.859  6923  6984 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
08-05 14:14:20.859  6923  6984 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-05 14:14:20.860  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 14:14:20.861  6923  6984 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-05 14:14:20.862  6923  6984 I io.jxcore.node.ConnectionHelper: start: OK
08-05 14:14:20.864  6923  6984 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 14:14:20.864  6923  6984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 14:14:20.864  6923  6984 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 14:14:20.864  6923  6984 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 14:14:20.864  6923  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:20.864  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 14:14:20.864  6923  6984 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c999dec not in the list
08-05 14:14:20.864  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:20.864  6923  6984 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c0e55b5 not in the list
08-05 14:14:20.864  6923  6984 D io.jxcore.node.ConnectivityMonitor: stop
08-05 14:14:20.864  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:20.864  6923  6984 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-05 14:14:20.865  6923  6984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 14:14:20.868  6923  6984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 14:14:20.868  6923  6984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 14:14:20.868  6923  6984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 14:14:20.868  6923  6984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 14:14:20.868  6923  6984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 14:14:20.868  6923  6984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 14:14:20.868  6923  6984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 14:14:20.868  6923  6984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-05 14:14:20.870  6923  6984 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-05 14:14:20.870  6923  6984 D io.jxcore.node.ConnectivityMonitor: start: OK
08-05 14:14:20.871  6923  6923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 14:14:20.871  6923  6984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-05 14:14:20.871  6923  6984 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-05 14:14:20.871  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-05 14:14:20.871  6923  6984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 14:14:20.871  6923  6984 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-05 14:14:20.874  6923  6923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 14:14:20.875  6923  6984 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-05 14:14:20.875  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 14:14:20.876  6923  6984 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-05 14:14:20.876  6923  6984 I io.jxcore.node.ConnectionHelper: start: OK
08-05 14:14:20.878  6923  6984 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 14:14:20.878  6923  6984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 14:14:20.878  6923  6984 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 14:14:20.878  6923  6984 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 14:14:20.878  6923  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:20.878  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 14:14:20.878  6923  6984 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c999dec not in the list
08-05 14:14:20.878  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:20.878  6923  6984 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c0e55b5 not in the list
08-05 14:14:20.878  6923  6984 D io.jxcore.node.ConnectivityMonitor: stop
08-05 14:14:20.878  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:20.879  6923  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:20.879  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-05 14:14:20.880  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 14:14:20.880  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 14:14:20.882  6923  6984 D BluetoothLeScanner: could not find callback wrapper
08-05 14:14:20.882  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 14:14:20.882  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:20.882  6923  6984 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c0e55b5 not in the list
08-05 14:14:20.882  6923  6984 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-05 14:14:20.884  6923  6984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 14:14:20.886  6923  6984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 14:14:20.886  6923  6984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 14:14:20.886  6923  6984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 14:14:20.886  6923  6984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 14:14:20.886  6923  6984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 14:14:20.886  6923  6984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 14:14:20.886  6923  6984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 14:14:20.886  6923  6984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 14:14:20.887  6923  6984 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-05 14:14:20.887  6923  6984 D io.jxcore.node.ConnectivityMonitor: start: OK
08-05 14:14:20.888  6923  6984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-05 14:14:20.888  6923  6984 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-05 14:14:20.888  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-05 14:14:20.888  6923  6984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 14:14:20.888  6923  6984 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-05 14:14:20.888  6923  6923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 14:14:20.891  6923  6923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 14:14:20.892  6923  6984 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-05 14:14:20.892  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 14:14:20.894  6923  6984 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-05 14:14:20.894  6923  6984 I io.jxcore.node.ConnectionHelper: start: OK
08-05 14:14:20.894  6923  6984 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 14:14:20.894  6923  6984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 14:14:20.894  6923  6984 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 14:14:20.895  6923  6984 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 14:14:20.895  6923  6984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 14:14:20.895  6923  6984 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 14:14:20.895  6923  6984 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 14:14:20.895  6923  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:20.895  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 14:14:20.895  6923  6984 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c999dec not in the list
08-05 14:14:20.895  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:20.895  6923  6984 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c0e55b5 not in the list
08-05 14:14:20.895  6923  6984 D io.jxcore.node.ConnectivityMonitor: stop
08-05 14:14:20.895  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:20.895  6923  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:20.895  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:20.896  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 14:14:20.896  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 14:14:20.896  6923  6984 D BluetoothLeScanner: could not find callback wrapper
08-05 14:14:20.896  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 14:14:20.896  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:20.896  6923  6984 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c0e55b5 not in the list
08-05 14:14:20.897  6923  6984 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-05 14:14:20.897  6923  6984 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 14:14:20.897  6923  6984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discov,ery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 14:14:20.897  6923  6984 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 14:14:20.897  6923  6984 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 14:14:20.897  6923  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:20.897  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:20.897  6923  6984 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c999dec not in the list
08-05 14:14:20.897  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:20.897  6923  6984 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c0e55b5 not in the list
08-05 14:14:20.897  6923  6984 D io.jxcore.node.ConnectivityMonitor: stop
08-05 14:14:20.897  6923  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:20.897  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:20.897  6923  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:20.897  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:20.898  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 14:14:20.898  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 14:14:20.898  6923  6984 D BluetoothLeScanner: could not find callback wrapper
08-05 14:14:20.898  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 14:14:20.898  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:20.898  6923  6984 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c0e55b5 not in the list
08-05 14:14:20.899  6923  6984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-05 14:14:20.899  6923  6984 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 14:14:20.899  6923  6984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 14:14:20.899  6923  6984 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 14:14:20.899  6923  6984 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 14:14:20.899  6923  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:20.899  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:20.899  6923  6984 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c999dec not in the list
08-05 14:14:20.899  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:20.899  6923  6984 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c0e55b5 not in the list
08-05 14:14:20.899  6923  6984 D io.jxcore.node.ConnectivityMonitor: stop
08-05 14:14:20.899  6923  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:20.899  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:20.899  6923  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:20.899  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:20.900  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 14:14:20.900  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 14:14:20.900  6923  6984 D BluetoothLeScanner: could not find callback wrapper
08-05 14:14:20.900  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 14:14:20.900  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:20.900  6923  6984 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c0e55b5 not in the list
08-05 14:14:20.901  6923  6984 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-05 14:14:20.901  6923  6984 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 14:14:20.901  6923  6984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 14:14:20.901  6923  6984 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 14:14:20.901  6923  6984 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 14:14:20.901  6923  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:20.901  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:20.901  6923  6984 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c999dec not in the list
08-05 14:14:20.901  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:20.901  6923  6984 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c0e55b5 not in the list
08-05 14:14:20.901  6923  6984 D io.jxcore.node.ConnectivityMonitor: stop
08-05 14:14:20.901  6923  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:20.901  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:20.901  6923  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:20.901  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:20.902  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 14:14:20.902  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 14:14:20.907  6923  6984 D BluetoothLeScanner: could not find callback wrapper
08-05 14:14:20.907  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 14:14:20.907  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:20.907  6923  6984 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c0e55b5 not in the list
08-05 14:14:20.908  6923  6984 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-05 14:14:20.908  6923  6984 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 14:14:20.908  6923  6984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 14:14:20.908  6923  6984 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 14:14:20.909  6923  6984 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 14:14:20.909  6923  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:20.909  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:20.909  6923  6984 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c999dec not in the list
08-05 14:14:20.909  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:20.909  6923  6984 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c0e55b5 not in the list
08-05 14:14:20.909  6923  6984 D io.jxcore.node.ConnectivityMonitor: stop
08-05 14:14:20.909  6923  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:20.909  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:20.909  6923  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:20.909  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:20.909  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 14:14:20.909  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 14:14:20.910  6923  6984 D BluetoothLeScanner: could not find callback wrapper
08-05 14:14:20.910  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 14:14:20.910  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:20.910  6923  6984 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c0e55b5 not in the list
08-05 14:14:20.911  6923  6984 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-05 14:14:20.912  6923  6984 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-05 14:14:20.912  6923  6984 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-05 14:14:20.912  6923  6984 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-05 14:14:20.912  6923  6984 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-05 14:14:20.912  6923  6984 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-05 14:14:20.913  6923  6984 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 14:14:20.913  6923  6984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 14:14:20.913  6923  6984 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 14:14:20.913  6923  6984 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 14:14:20.913  6923  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:20.913  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:20.913  6923  6984 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c999dec not in the list
08-05 14:14:20.913  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:20.913  6923  6984 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c0e55b5 not in the list
08-05 14:14:20.913  6923  6984 D io.jxcore.node.ConnectivityMonitor: stop
08-05 14:14:20.913  6923  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:20.913  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:20.913  6923  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:20.913  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:20.914  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 14:14:20.914  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 14:14:20.914  6923  6984 D BluetoothLeScanner: could not find callback wrapper
08-05 14:14:20.914  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 14:14:20.914  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:20.915  6923  6984 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c0e55b5 not in the list
08-05 14:14:20.915  6923  6984 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-05 14:14:20.915  6923  6984 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-05 14:14:20.916  6923  6984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-05 14:14:20.921  6923  6984 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-05 14:14:20.921  6923  6984 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-05 14:14:20.921  6923  6984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-05 14:14:20.921  6923  6984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-05 14:14:20.921  6923  6984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-05 14:14:20.921  6923  6984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-05 14:14:20.921  6923  6984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-05 14:14:20.922  6923  6984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-05 14:14:20.922  6923  6984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-05 14:14:20.922  6923  6984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-05 14:14:20.922  6923  6984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-05 14:14:20.922  6923  6984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-05 14:14:20.922  6923  6984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-05 14:14:20.922  6923  6984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-05 14:14:20.922  6923  6984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-05 14:14:20.922  6923  6984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-05 14:14:20.922  6923  6984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-05 14:14:20.922  6923  6984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-05 14:14:20.922  6923  6984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-05 14:14:20.922  6923  6984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-05 14:14:20.922  6923  6984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-05 14:14:20.922  6923  6984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-05 14:14:20.922  6923  6984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-05 14:14:20.922  6923  6984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-05 14:14:20.922  6923  6984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-05 14:14:20.922  6923  6984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-05 14:14:20.923  6923  6984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-05 14:14:20.923  6923  6984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-05 14:14:20.923  6923  6984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-05 14:14:20.923  6923  6984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-05 14:14:20.923  6923  6984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-05 14:14:20.923  6923  6984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-05 14:14:20.923  6923  6984 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-05 14:14:20.923  6923  6984 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-05 14:14:20.923  6923  6984 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-05 14:14:20.923  6923  6984 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-05 14:14:20.923  6923  6984 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-05 14:14:20.923  6923  6984 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-05 14:14:20.924  6923  6984 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-05 14:14:20.924  6923  6984 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-05 14:14:20.924  6923  6984 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-05 14:14:20.927  6923  6984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,08-05 14:14:20.928  6923  6984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-05 14:14:20.929  6923  6984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-05 14:14:20.930  6923  6984 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-05 14:14:20.932  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-05 14:14:20.932  6923  6984 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-05 14:14:20.932  6923  6985 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 876)
08-05 14:14:20.933  6923  6984 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-05 14:14:20.933  6923  6984 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-05 14:14:20.933  6923  6984 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 14:14:20.934  6923  6984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 14:14:20.934  6923  6984 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 14:14:20.935  6923  6984 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 14:14:20.935  6923  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:20.935  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:20.936  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-05 14:14:20.936  6923  6984 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c999dec not in the list
08-05 14:14:20.937  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:20.937  6923  6984 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c0e55b5 not in the list
08-05 14:14:20.937  6923  6984 D io.jxcore.node.ConnectivityMonitor: stop
08-05 14:14:20.937  6923  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:20.937  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:20.938  6923  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:20.938  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:20.939  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 14:14:20.939  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 14:14:20.940  6923  6984 D BluetoothLeScanner: could not find callback wrapper
08-05 14:14:20.940  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 14:14:20.940  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:20.940  6923  6984 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c0e55b5 not in the list
08-05 14:14:20.941  6923  6984 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-05 14:14:20.941  6923  6984 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 14:14:20.941  6923  6984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 14:14:20.941  6923  6984 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 14:14:20.943  6923  6986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 876
08-05 14:14:20.943  6923  6986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 876)
08-05 14:14:20.944  6923  6984 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 14:14:20.944  6923  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:20.944  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:20.944  6923  6984 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c999dec not in the list
08-05 14:14:20.944  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:20.944  6923  6984 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c0e55b5 not in the list
08-05 14:14:20.944  6923  6984 D io.jxcore.node.ConnectivityMonitor: stop
08-05 14:14:20.944  6923  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:20.944  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:20.944  6923  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:20.944  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:20.943  6923  6986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 876)
08-05 14:14:20.946  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 14:14:20.946  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 14:14:20.946  6923  6984 D BluetoothLeScanner: could not find callback wrapper
08-05 14:14:20.946  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 14:14:20.947  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:20.947  6923  6984 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c0e55b5 not in the list
08-05 14:14:20.948  6923  6984 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-05 14:14:20.948  6923  6984 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 14:14:20.948  6923  6984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 14:14:20.948  6923  6984 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 14:14:20.949  6923  6984 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 14:14:20.949  6923  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:20.949  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:20.949  6923  6984 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c999dec not in the list
08-05 14:14:20.949  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:20.949  6923  6984 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c0e55b5 not in the list
08-05 14:14:20.949  6923  6984 D io.jxcore.node.ConnectivityMonitor: stop
08-05 14:14:20.949  6923  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:20.949  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:20.949  6923  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:20.949  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:20.951  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 14:14:20.951  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 14:14:20.952  6923  6984 D BluetoothLeScanner: could not find callback wrapper
08-05 14:14:20.952  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 14:14:20.952  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:20.952  6923  6984 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c0e55b5 not in the list
08-05 14:14:20.953  6923  6984 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-05 14:14:20.953  6923  6984 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-05 14:14:20.953  6923  6984 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-05 14:14:20.953  6923  6984 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-05 14:14:20.953  6923  6984 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-05 14:14:20.954  6923  6984 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-05 14:14:20.954  6923  6984 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-05 14:14:20.954  6923  6984 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-05 14:14:20.954  6923  6984 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-05 14:14:20.954  6923  6984 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-05 14:14:20.954  6923  6984 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-05 14:14:20.954  6923  6984 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-05 14:14:20.954  6923  6984 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 14:14:20.954  6923  6984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 14:14:20.954  6923  6984 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 14:14:20.954  6923  6984 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 14:14:20.954  6923  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:20.954  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:20.954  6923  6984 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c999dec not in the list
08-05 14:14:20.954  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:20.955  6923  6984 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c0e55b5 not in the list
08-05 14:14:20.955  6923  6984 D io.jxcore.node.ConnectivityMonitor: stop
08-05 14:14:20.955  6923  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:20.955  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:20.955  6923  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:20.955  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:20.957  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 14:14:20.957  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-05 14:14:20.961  6923  6984 D BluetoothLeScanner: could not find callback wrapper
08-05 14:14:20.961  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 14:14:20.961  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:20.961  6923  6984 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c0e55b5 not in the list
08-05 14:14:20.962  6923  6984 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 14:14:20.962  6923  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:20.962  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:20.963  6923  6984 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c999dec not in the list
08-05 14:14:20.963  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:20.963  6923  6984 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c0e55b5 not in the list
08-05 14:14:20.963  6923  6984 D io.jxcore.node.ConnectivityMonitor: stop
08-05 14:14:20.963  6923  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:20.963  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:20.963  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:20.964  6923  6984 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c0e55b5 not in the list
08-05 14:14:20.964  6923  6984 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 14:14:20.964  6923  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:20.964  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:20.964  6923  6984 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c999dec not in the list
08-05 14:14:20.964  6923  6984 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 14:14:20.964  6923  6984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 14:14:20.965  6923  6984 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 14:14:20.965  6923  6984 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 14:14:20.965  6923  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:20.965  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:20.965  6923  6984 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c999dec not in the list
08-05 14:14:20.965  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:20.965  6923  6984 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: L,istener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c0e55b5 not in the list
08-05 14:14:20.965  6923  6984 D io.jxcore.node.ConnectivityMonitor: stop
08-05 14:14:20.965  6923  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:20.965  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:20.965  6923  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:20.965  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:20.971  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 14:14:20.971  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 14:14:20.972  6923  6984 D BluetoothLeScanner: could not find callback wrapper
08-05 14:14:20.972  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 14:14:20.972  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:20.972  6923  6984 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c0e55b5 not in the list
08-05 14:14:20.974  6923  6984 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-05 14:14:20.974  6923  6984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 14:14:20.975  6923  6984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-05 14:14:20.976  6923  6984 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-05 14:14:20.976  6923  6984 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-05 14:14:20.977  6923  6923 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-05 14:14:20.977  6923  6984 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,08-05 14:14:20.977  6923  6984 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-05 14:14:20.978  6923  6984 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 14:14:20.978  6923  6984 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-05 14:14:20.978  6923  6984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-05 14:14:20.978  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-05 14:14:20.978  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:20.978  6923  6984 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-05 14:14:20.979  6923  6923 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED,
08-05 14:14:20.979  6923  6984 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c999dec not in the list
08-05 14:14:20.979  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:20.979  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-05 14:14:20.979  6923  6984 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-05 14:14:20.979  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-05 14:14:20.980  6923  6984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-05 14:14:20.990  6923  6984 D BluetoothLeScanner: could not find callback wrapper
08-05 14:14:20.990  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 14:14:20.990  6923  6984 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-05 14:14:20.991  6923  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:20.991  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:20.991  6923  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,08-05 14:14:20.992  6923  6987 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-05 14:14:21.001  6923  6984 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-05 14:14:21.002  6923  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-05 14:14:21.002  6923  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-05 14:14:21.002  6923  6923 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-05 14:14:21.002  6923  6923 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-05 14:14:21.002  6923  6984 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c0e55b5 not in the list
08-05 14:14:21.002  6923  6984 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 14:14:21.002  6923  6984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 14:14:21.002  6923  6984 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-05 14:14:21.003  6923  6984 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 14:14:21.003  6923  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:21.003  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:21.003  6923  6984 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c999dec not in the list
08-05 14:14:21.004  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:21.004  6923  6984 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c0e55b5 not in the list
08-05 14:14:21.004  6923  6984 D io.jxcore.node.ConnectivityMonitor: stop
08-05 14:14:21.004  6923  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:21.004  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:21.004  6923  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:21.004  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:21.005  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 14:14:21.005  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 14:14:21.005  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:21.005  6923  6984 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c0e55b5 not in the list
08-05 14:14:21.006  6923  6984 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-05 14:14:21.007  6923  6984 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-05 14:14:21.007  6923  6984 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-05 14:14:21.009  6923  6984 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-05 14:14:21.009  6923  6984 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 14:14:21.009  6923  6984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 14:14:21.009  6923  6984 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 14:14:21.010  6923  6984 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 14:14:21.010  6923  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:21.010  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:21.010  6923  6984 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c999dec not in the list
08-05 14:14:21.010  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:21.010  6923  6984 E org.thali,project.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c0e55b5 not in the list
08-05 14:14:21.010  6923  6984 D io.jxcore.node.ConnectivityMonitor: stop
08-05 14:14:21.010  6923  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:21.010  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:21.010  6923  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:21.010  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:21.012  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 14:14:21.012  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 14:14:21.012  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:21.012  6923  6984 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c0e55b5 not in the list
08-05 14:14:21.013  1030  1046 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 14:14:21.014  1030  1592 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-05 14:14:21.015  1030  1986 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 14:14:21.016  6923  6984 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 14:14:21.016  6923  6984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 14:14:21.016  6923  6984 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 14:14:21.017  6923  6984 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 14:14:21.017  6923  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:21.017  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:21.017  6923  6984 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c999dec not in the list
08-05 14:14:21.017  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:21.017  6923  6984 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c0e55b5 not in the list
08-05 14:14:21.017  6923  6984 D io.jxcore.node.ConnectivityMonitor: stop
08-05 14:14:21.017  6923  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-05 14:14:21.017  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:21.017  6923  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:21.017  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:21.018  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-05 14:14:21.018  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-05 14:14:21.018  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:21.018  6923  6984 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c0e55b5 not in the list
08-05 14:14:21.020  6923  6984 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 14:14:21.020  6923  6984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 14:14:21.020  6923  6984 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 14:14:21.020  6923  6984 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 14:14:21.020  6923  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-05 14:14:21.022  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:21.023  6923  6984 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c999dec not in the list
08-05 14:14:21.023  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:21.023  6923  6984 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c0e55b5 not in the list
08-05 14:14:21.023  6923  6984 D io.jxcore.node.ConnectivityMonitor: stop
08-05 14:14:21.023  6923  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:21.023  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:21.023  6923  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:21.023  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:21.024  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 14:14:21.024  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 14:14:21.024  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:21.024  6923  6984 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c0e55b5 not in the list
08-05 14:14:21.027  6923  6984 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-05 14:14:21.027  6923  6984 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-05 14:14:21.028  6923  6984 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-05 14:14:21.028  6923  6984 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-05 14:14:21.028  6923  6984 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-05 14:14:21.028  6923  6984 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-05 14:14:21.030  6923  6984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-05 14:14:21.030  6923  6984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-05 14:14:21.032  6923  6984 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-05 14:14:21.032  6923  6984 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-05 14:14:21.032  6923  6984 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-05 14:14:21.032  6923  6984 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-05 14:14:21.032  6923  6984 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-05 14:14:21.032  6923  6984 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-05 14:14:21.034  6923  6984 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-05 14:14:21.034  6923  6984 D io.jxc,ore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-05 14:14:21.034  6923  6984 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-05 14:14:21.035  6923  6984 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-05 14:14:21.035  6923  6984 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-05 14:14:21.035  6923  6984 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-05 14:14:21.036  6923  6984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 14:14:21.036  6923  6984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@10dca2a2 added. We now have 2 listener(s)
08-05 14:14:21.036  6923  6984 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-05 14:14:21.039  6923  6984 D BluetoothAdapter: enable(): BT is already enabled..!
08-05 14:14:21.041  1030  1045 D WifiServiceImplEx: setWifiEnabled: true pid=6923, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-05 14:14:21.042  1030  1045 D WifiService: setWifiEnabled: true pid=6923, uid=10118
08-05 14:14:21.042  1030  1045 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-05 14:14:21.045  6923  6984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 14:14:21.045  6923  6984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@12cacb33 added. We now have 3 listener(s)
08-05 14:14:21.046  6923  6984 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 14:14:21.056  6923  6984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 14:14:21.056  6923  6984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@26b43ef0 added. We now have 4 listener(s)
08-05 14:14:21.056  6923  6984 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-05 14:14:21.058  6923  6984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-05 14:14:21.058  6923  6984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@38c1c69 added. We now have 5 listener(s)
08-05 14:14:21.058  6923  6984 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 14:14:21.066  1030  1046 D WifiServiceImplEx: setWifiEnabled: false pid=6923, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-05 14:14:21.066  1030  1046 D WifiService: setWifiEnabled: false pid=6923, uid=10118
08-05 14:14:21.067  1030  1046 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-05 14:14:21.070  6923  6985 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
08-05 14:14:21.071  6923  6985 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 876)
,08-05 14:14:21.087  1030  1030 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-05 14:14:21.087  1030  1030 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-05 14:14:21.087  1030  1030 D Ulp_jni : JNI:system_update. Event-4
08-05 14:14:21.088  1030  1389 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-05 14:14:21.089  1030  1389 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-05 14:14:21.089  1030  1389 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-05 14:14:21.089  1030  1735 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 14:14:21.089  1030  1389 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-05 14:14:21.089  1030  1735 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@1b3f02ff mBinding = false
08-05 14:14:21.089  1030  1389 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-05 14:14:21.089  1030  1389 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-05 14:14:21.090  1030  1389 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-05 14:14:21.090  1030  1389 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-05 14:14:21.091  1030  1389 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-05 14:14:21.091  1030  1389 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-05 14:14:21.104  1030  1389 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-05 14:14:21.105  1030  1389 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-05 14:14:21.105  1030  1387 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-05 14:14:21.105  1030  1387 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-05 14:14:21.105  2712  2712 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-05 14:14:21.105  1030  1389 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-05 14:14:21.105  1030  1389 D WifiNative-wlan0: doBoolean: SET ps 1
08-05 14:14:21.106  1030  1389 D WifiNative-wlan0: SET ps 1: returned true
08-05 14:14:21.106  1030  2860 D DhcpStateMachine: RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-05 14:14:21.106   308   895 D CommandListener: Clearing all IP addresses on wlan0
,08-05 14:14:21.118  1030  1030 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-05 14:14:21.119  1030  1030 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-05 14:14:21.119  1030  1030 D Ulp_jni : JNI:system_update. Event-4
08-05 14:14:21.120  1030  1094 D BluetoothManagerService: Message: 2
08-05 14:14:21.122  1030  1094 D BluetoothManagerService: Sending off request.
08-05 14:14:21.123  4329  4939 D LGBluetoothServiceAdapter: [BTUI] Precleanup
,08-05 14:14:21.124  4329  4428 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-05 14:14:21.124  4329  4428 D BluetoothAdapterProperties: Setting state to 13
08-05 14:14:21.124  4329  4428 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-05 14:14:21.124  4329  4428 D BluetoothAdapterProperties: onBluetoothDisable()
08-05 14:14:21.125  4329  4428 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-05 14:14:21.126  1030  1094 D BluetoothManagerService: Message: 60
08-05 14:14:21.126  1030  1094 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-05 14:14:21.126  1030  1094 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-05 14:14:21.129  1600  1600 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-05 14:14:21.130  1938  1938 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-05 14:14:21.131  4329  4329 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-05 14:14:21.132  4329  4329 D BluetoothMapService: STATE_TURNING_OFF
08-05 14:14:21.132  4329  4329 V BluetoothMapService: Handler(): got msg=4
08-05 14:14:21.132  4329  4329 D BluetoothMapService: MAP Service closeService in
08-05 14:14:21.132  4329  4329 D BluetoothMapMasInstance: MAP Service shutdown
08-05 14:14:21.133  4329  4693 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-05 14:14:21.133  4329  4693 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-05 14:14:21.133  4329  4693 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-05 14:14:21.133  4329  4693 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-05 14:14:21.133  4329  4693 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-05 14:14:21.133  4329  4693 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-05 14:14:21.133  4329  4693 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-05 14:14:21.133  4329  4693 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-05 14:14:21.134  4329  4329 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-05 14:14:21.134  4329  4329 V BluetoothMapService: MAP Service closeService out
,08-05 14:14:21.134  4329  4329 V BtOppService: Receiver DISABLED_ACTION 
08-05 14:14:21.135  4329  4329 I BtOppRfcommListener: stopping Accept Thread
,08-05 14:14:21.135  4329  4329 V BtOppRfcommListener: close mBtServerSocket
08-05 14:14:21.135  4329  4747 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-05 14:14:21.135  4329  4747 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-05 14:14:21.136  4329  4329 V BtOppRfcommListener: waiting for thread to terminate
08-05 14:14:21.136  4329  4329 V BtOppRfcommListener: done waiting for thread to terminate
08-05 14:14:21.139  1030  1403 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-05 14:14:21.139  1030  1403 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
08-05 14:14:21.143  6923  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 14:14:21.143  6923  6923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 14:14:21.143  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 14:14:21.143  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 14:14:21.143  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 14:14:21.143  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 14:14:21.143  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 14:14:21.143  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 14:14:21.143  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 14:14:21.143  6923  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 14:14:21.143  6923  6923 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-05 14:14:21.175  1030  1045 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
08-05 14:14:21.176  1030  2858 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-05 14:14:21.176  1030  2858 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-05 14:14:21.176  1030  2858 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-05 14:14:21.176  1030  2858 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
08-05 14:14:21.176  1030  2858 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
,08-05 14:14:21.185  1030  1403 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-05 14:14:21.185  1030  1403 D DSQN    : disableDataServiceNotify
08-05 14:14:21.185  1030  1403 D DSQN    : stop dsqn bin
08-05 14:14:21.186   308  7001 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-05 14:14:21.186  1030  2858 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
08-05 14:14:21.187  1030  1092 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-05 14:14:21.192  1030  1089 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=7002 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-05 14:14:21.193  4329  4432 D BluetoothAdapterProperties: Scan Mode:20
08-05 14:14:21.193  4329  4428 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-05 14:14:21.194  4329  4694 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-05 14:14:21.194  4329  4428 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-05 14:14:21.194  4329  4556 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-05 14:14:21.194  4329  4556 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-05 14:14:21.195  4329  4751 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-05 14:14:21.196  4329  4749 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-05 14:14:21.196  1030  1387 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-05 14:14:21.196  1030  1387 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-05 14:14:21.196  1030  1387 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@232e26bb
08-05 14:14:21.196  1030  1389 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 14:14:21.196  1030  1387 D LGWifiP2pService: P2pDisablingState
08-05 14:14:21.196  1030  1389 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 14:14:21.197  1030  1387 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-05 14:14:21.197  1030  1387 D LGWifiP2pService: p2p socket connection lost
08-05 14:14:21.197  1030  1389 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 14:14:21.197  1030  1387 D LGWifiP2pService: P2pDisabledState
08-05 14:14:21.197  1030  1389 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 14:14:21.197  4329  4556 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-05 14:14:21.197  4329  4556 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-05 14:14:21.197  4329  4556 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-05 14:14:21.197  4329  4556 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-05 14:14:21.197  4329  4556 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-05 14:14:21.197  1030  1389 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 14:14:21.197  4329  4556 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-05 14:14:21.197  4329  4556 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-05 14:14:21.197  4329  4556 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-05 14:14:21.197  4329  4556 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-05 14:14:21.197  4329  4556 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-05 14:14:21.197  4329  4556 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-05 14:14:21.197  4329  4556 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-05 14:14:21.198  1030  1389 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 14:14:21.198  4329  4329 V BtOppService: onDestroy
08-05 14:14:21.198  1030  1389 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-05 14:14:21.199  4329  4329 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-05 14:14:21.202  1030  1389 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 14:14:21.202  1030  1030 D WifiHS20: hidePasspointNotification off =false
08-05 14:14:21.203  6923  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothMan,ager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 14:14:21.203  6923  6923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 14:14:21.203  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 14:14:21.203  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 14:14:21.203  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 14:14:21.203  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 14:14:21.203  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 14:14:21.203  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 14:14:21.203  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 14:14:21.203  1030  1389 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 14:14:21.204  6923  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 14:14:21.204  6923  6923 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-05 14:14:21.204  6923  6984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 14:14:21.204  1030  1389 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 14:14:21.205  1938  1938 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-05 14:14:21.206  1030  1389 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-05 14:14:21.206  6923  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 14:14:21.206  6923  6984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 14:14:21.206  6923  6984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 14:14:21.206  6923  6984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 14:14:21.206  6923  6984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 14:14:21.206  6923  6984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 14:14:21.206  6923  6984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 14:14:21.206  6923  6984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 14:14:21.206  6923  6984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 14:14:21.206  1030  1387 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-05 14:14:21.206  1030  1387 D LGWifiP2pService: DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-05 14:14:21.207  1030  1389 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-05 14:14:21.207  2712  2712 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-05 14:14:21.208  6923  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 14:14:21.208  1030  1389 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-05 14:14:21.208  6923  6984 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-05 14:14:21.208  1030  1389 D WifiNative-wlan0: doBoolean,: SET ps 1
08-05 14:14:21.208  6923  6984 D io.jxcore.node.ConnectivityMonitor: start: OK
08-05 14:14:21.209  1030  1389 D WifiNative-wlan0: SET ps 1: returned true
08-05 14:14:21.210  6923  6923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 14:14:21.210   308   895 D CommandListener: Clearing all IP addresses on wlan0
08-05 14:14:21.211  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 14:14:21.211  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 14:14:21.211  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-05 14:14:21.212  6923  6923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 14:14:21.215  1030  1030 D WifiHS20: hidePasspointNotification off =false
08-05 14:14:21.215  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 14:14:21.215  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 14:14:21.215  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-05 14:14:21.217  1030  1030 D WifiScanningService: SCAN_AVAILABLE : 1
08-05 14:14:21.217  1030  1553 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-05 14:14:21.217  1030  1030 D RttService: SCAN_AVAILABLE : 1
08-05 14:14:21.218  1030  1554 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-05 14:14:21.220  1938  1938 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-05 14:14:21.220  1938  1938 D WfdsService: WifiP2pState is changed : false
08-05 14:14:21.220  1938  2301 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-05 14:14:21.220  1938  2301 D WfdsService: Set the WFDS Monitor: false
08-05 14:14:21.242  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 14:14:21.242  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 14:14:21.243  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 14:14:21.244  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 14:14:21.244  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 14:14:21.245  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 14:14:21.257  1030  1089 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7024 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-05 14:14:21.257  1030  1389 D WifiNative-p2p0: doBoolean: TERMINATE
08-05 14:14:21.258  1030  1389 D WifiNative-p2p0: TERMINATE: returned true
08-05 14:14:21.258  1030  1389 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-05 14:14:21.258  1030  1389 E WifiStateMachine: useWiFiOffloading() : false
08-05 14:14:21.258  1030  1389 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-05 14:14:21.260  1030  1030 D WifiHS20: hidePasspointNotification off =false
08-05 14:14:21.260  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 14:14:21.260  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 14:14:21.260  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-05 14:14:21.262  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-05 14:14:21.262  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 14:14:21.264  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 14:14:21.264  1938  1938 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-05 14:14:21.265  6923  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 14:14:21.265  6923  6923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 14:14:21.265  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 14:14:21.265  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 14:14:21.265  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 14:14:21.265  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 14:14:21.265  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 14:14:21.265  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 14:14:21.265  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 14:14:21.266  6923  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 14:14:21.266  6923  6923 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-05 14:14:21.266  1030  1030 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-05 14:14:21.266  1030  1030 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 14:14:21.266  1030  1030 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-05 14:14:21.272  6923  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 14:14:21.272  6923  6923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 14:14:21.272  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 14:14:21.272  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 14:14:21.272  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 14:14:21.272  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - is B,luetooth enabled: false
08-05 14:14:21.272  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 14:14:21.272  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 14:14:21.272  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 14:14:21.275  6923  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 14:14:21.275  6923  6923 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-05 14:14:21.279  1938  2301 D WfdsMonitor: WFDS Monitor is stopped
08-05 14:14:21.279  1938  2301 D WfdsService: STATE : WfdsDisabledState - enter
08-05 14:14:21.280  1938  2302 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-05 14:14:21.280  1030  1403 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-05 14:14:21.280  1030  1403 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 14:14:21.280  1030  1403 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 14:14:21.280  1938  2771 D CtrlSupplicant: Received on exit socket, terminate
08-05 14:14:21.280  1938  2771 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-05 14:14:21.280  1938  2771 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-05 14:14:21.280  1938  2771 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-05 14:14:21.281  1030  1403 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 14:14:21.281  1030  1403 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-05 14:14:21.281  1600  1825 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-05 14:14:21.281  1030  2858 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-05 14:14:21.281  1030  2858 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-05 14:14:21.281  1030  2858 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-05 14:14:21.282  1938  2301 W WfdsService: DefaultState - msg [9445378] is not handled
08-05 14:14:21.283  1030  1403 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-05 14:14:21.283  1030  1403 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-05 14:14:21.283  1030  1403 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-05 14:14:21.285  1030  1030 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-05 14:14:21.285  1030  1030 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-05 14:14:21.286  1030  1030 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-05 14:14:21.286  1030  1030 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-05 14:14:21.286  1030  1386 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-05 14:14:21.286  1030  1403 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-05 14:14:21.287  1030  1403 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-05 14:14:21.288  1030  1386 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-05 14:14:21.288  1030  1030 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-05 14:14:21.288  1030  1030 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-05 14:14:21.289  1030  1030 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-05 14:14:21.289  1030  1030 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-05 14:14:21.289  1030  1403 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-05 14:14:21.289  1030  1403 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 14:14:21.289  1030  1403 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 14:14:21.289  1849  1849 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 14:14:21.289  1849  1849 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-05 14:14:21.290  1030  1389 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 14:14:21.290  1030  1389 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-05 14:14:21.290  1030  1403 D NetworkManagementService: Removing idletimer
08-05 14:14:21.290  1030  1403 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 14:14:21.291  7002  7002 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-05 14:14:21.291  7002  7002 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-05 14:14:21.291  7002  7002 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-05 14:14:21.291  7002  7002 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-05 14:14:21.291  1030  1403 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-05 14:14:21.292  7002  7002 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-05 14:14:21.293  7002  7002 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-05 14:14:21.303  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-05 14:14:21.323  1600  1600 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-05 14:14:21.323  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 14:14:21.324  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-05 14:14:21.337  1600  1600 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-05 14:14:21.338  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 14:14:21.339  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 14:14:21.365  1030  2860 D DhcpStateMachine: StoppedState
,08-05 14:14:21.365  1030  2860 D DhcpStateMachine: StoppedState{ when=-155ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-05 14:14:21.365  1030  1389 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-05 14:14:21.365  1030  1389 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-05 14:14:21.369  7024  7024 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-05 14:14:21.370  7024  7024 W LG Account v2.2: No ProfileInfo entries
08-05 14:14:21.370  7024  7024 I LG Account v2.2: isEnabled: false
08-05 14:14:21.370  7024  7024 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-05 14:14:21.370  7024  7024 I Feature : [Lifetracker]Country: EU
08-05 14:14:21.370  7024  7024 I Feature : [Lifetracker]Operator: OPEN
08-05 14:14:21.370  7024  7024 I Feature : [Lifetracker]Ranking support: false
08-05 14:14:21.370  7024  7024 I Feature : [Lifetracker]Comfort support: false
08-05 14:14:21.370  7024  7024 I Feature : [Lifetracker]Accessory: true
08-05 14:14:21.370  7024  7024 I Feature : [Lifetracker]Health device: true
08-05 14:14:21.371  7024  7024 I Feature : [Lifetracker]Extra Pedometer: false
08-05 14:14:21.371  7024  7024 I Feature : [Lifetracker]Blood glucose device: false
08-05 14:14:21.371  7024  7024 I Feature : [Lifetracker]Device Number: 3
08-05 14:14:21.377  7002  7002 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-05 14:14:21.380  4329  4329 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-05 14:14:21.380  4329  4329 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 14:14:21.380  4329  4329 V BluetoothPbapReceiver: ***********state = 13
08-05 14:14:21.380  6408  6408 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 14:14:21.382  1030  1094 D BluetoothManagerService: Message: 20
08-05 14:14:21.383  1030  1094 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@38ac1ef6:true
08-05 14:14:21.383  2712  2712 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-05 14:14:21.383  2712  2712 I wpa_supplicant: monitor socket send errors count : 1
08-05 14:14:21.383  2712  2712 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1938-2\x00 that cannot receive messages
08-05 14:14:21.383  4329  4329 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-05 14:14:21.384  1030  2768 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-05 14:14:21.384  1030  2768 D WifiMonitor: Dropping event because (p2p0) is stopped
,08-05 14:14:21.420  1030  1045 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7045 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-05 14:14:21.421  4329  4329 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-05 14:14:21.421  4329  4329 V BluetoothPbapService: state: 13
08-05 14:14:21.421  4329  4329 V BluetoothPbapService: Pbap Service closeService in
08-05 14:14:21.422  2712  2712 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-05 14:14:21.422  4329  4329 V BluetoothPbapService: successfully stopped pbap service
,08-05 14:14:21.422  4329  4329 V BluetoothPbapService: Pbap Service closeService out
,08-05 14:14:21.422  4329  4329 V BluetoothPbapService: Pbap Service onDestroy
08-05 14:14:21.422  4329  4329 V BluetoothPbapService: Pbap Service closeService in
08-05 14:14:21.422  1030  2768 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-05 14:14:21.422  4329  4329 V BluetoothPbapService: Pbap Service closeService out
08-05 14:14:21.423  1030  2768 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-05 14:14:21.423  4329  4329 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-05 14:14:21.423  1030  2768 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-05 14:14:21.423  2712  2712 W wpa_supplicant: USIM:  scard_deinit function
08-05 14:14:21.423  1030  1045 I ActivityManager: Killing 6250:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-05 14:14:21.426  1030  2768 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-05 14:14:21.426  1030  2768 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-05 14:14:21.426  1030  2768 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-05 14:14:21.427  1030  1389 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=347167
08-05 14:14:21.428  1030  1389 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=347168
08-05 14:14:21.428  1030  1389 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=347168  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-05 14:14:21.429  1030  1389 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=347169  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-05 14:14:21.431  1030  1094 D Tethering: InitialState.processMessage what=4
08-05 14:14:21.475  2185  2185 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-05 14:14:21.480  1030  1094 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-05 14:14:21.481  1030  1992 W libprocessgroup: failed to open /acct/uid_10014/pid_6250/cgroup.procs: No such file or directory
08-05 14:14:21.481  1030  1094 D BluetoothManagerService: Message: 30
08-05 14:14:21.482  2712  2712 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-05 14:14:21.484  1030  2768 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-05 14:14:21.484  1030  2768 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
08-05 14:14:21.484  1030  2768 D WifiMonitor: Disconnecting from the supplicant, no more events
08-05 14:14:21.485  1030  1389 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
08-05 14:14:21.488  1030  1094 D BluetoothManagerService: Message: 30
,08-05 14:14:21.492  7002  7002 D LocalBluetoothProfileManager: Adding local MAP profile
08-05 14:14:21.494  7002  7002 D BluetoothMap: Create BluetoothMap proxy object
08-05 14:14:21.495  1030  1094 D BluetoothManagerService: Message: 30
08-05 14:14:21.502  1030  1094 D BluetoothManagerService: Message: 30
,08-05 14:14:21.504  6923  6923 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-05 14:14:21.505  7002  7002 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-05 14:14:21.506  7002  7002 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
08-05 14:14:21.522  7002  7002 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,08-05 14:14:21.526  7002  7002 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
08-05 14:14:21.534  7002  7002 D DockEventReceiver: finishStartingService: stopping service
08-05 14:14:21.536  7002  7002 D BluetoothInputDevice: Proxy object connected
,08-05 14:14:21.537  7002  7002 D HidProfile: Bluetooth service connected
08-05 14:14:21.538  7002  7002 D BluetoothPan: BluetoothPAN Proxy object connected
08-05 14:14:21.539  7002  7002 D PanProfile: Bluetooth service connected
08-05 14:14:21.546  7045  7045 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-05 14:14:21.549  7002  7002 D BluetoothMap: Proxy object connected
,08-05 14:14:21.550  7002  7002 D MapProfile: Bluetooth service connected
08-05 14:14:21.550  7002  7002 D BluetoothMap: getConnectedDevices()
08-05 14:14:21.552  7002  7002 D BluetoothMap: Bluetooth is Not enabled
08-05 14:14:21.552  7002  7002 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-05 14:14:21.555  7045  7045 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-05 14:14:21.555  7002  7002 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-05 14:14:21.555  7045  7045 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-05 14:14:21.558  1030  1915 I ActivityManager: Killing 2122:com.lge.music/u0a34 (adj 15): empty #17
08-05 14:14:21.581   312  1399 V AudioFlinger: 2122 died, releasing its sessions
08-05 14:14:21.581   312  1399 V AudioFlinger:  pid 1849 @ 0
08-05 14:14:21.581   312  1399 V AudioFlinger:  pid 3317 @ 1
08-05 14:14:21.581   312  1399 V AudioFlinger:  pid 3317 @ 2
,08-05 14:14:21.607  1030  1951 W libprocessgroup: failed to open /acct/uid_10034/pid_2122/cgroup.procs: No such file or directory
,08-05 14:14:21.610  1030  1389 D WifiOffDelayIfNotUsed: stopMonitoring
08-05 14:14:21.610  1030  1389 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-05 14:14:21.610  1030  1389 E WifiStateMachine: useWiFiOffloading() : false
08-05 14:14:21.610  1030  1389 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-05 14:14:21.621  1938  1938 D WfdsService: Supplicant Connection state is changed : false
08-05 14:14:21.622  1938  2301 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-05 14:14:21.622  1938  2301 D WfdsService: Set the WFDS Monitor: false
08-05 14:14:21.622  1938  2301 D WfdsMonitor: WFDS Monitor is stopped
08-05 14:14:21.622  1938  1938 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
,08-05 14:14:21.625  2504  2504 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-05 14:14:21.626  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 14:14:21.626  1030  1030 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-05 14:14:21.627  1030  1393 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-05 14:14:21.627  1030  1393 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-05 14:14:21.627  6923  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 14:14:21.628  6923  6923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 14:14:21.628  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 14:14:21.628  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 14:14:21.628  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 14:14:21.628  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 14:14:21.628  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 14:14:21.628  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 14:14:21.628  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 14:14:21.630  6923  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 14:14:21.630  6923  6923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 14:14:21.630  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 14:14:21.630  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 14:14:21.630  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 14:14:21.630  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 14:14:21.630  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 14:14:21.630  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 14:14:21.630  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 14:14:21.633  7002  7002 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-05 14:14:21.675  7002  7002 D LgDataFeature: LgDataFeature() Constructor: none
08-05 14:14:21.675  7002  7002 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-05 14:14:21.686  7002  7002 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 14:14:21.688  7002  7002 D BluetoothPermissionRequest: onReceive
,08-05 14:14:21.692  7002  7002 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-05 14:14:21.699  1030  1957 I ActivityManager: Killing 6365:com.android.defcontainer/u0a4 (adj 15): empty #17
08-05 14:14:21.705  7002  7002 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-05 14:14:21.743  1030  1917 W libprocessgroup: failed to open /acct/uid_10004/pid_6365/cgroup.procs: No such file or directory
,08-05 14:14:21.744  4329  4329 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-05 14:14:21.744  4329  4329 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-05 14:14:21.745  4329  4329 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-05 14:14:21.823  1030  1389 E WifiStateMachine:  InitialState CMD_TETHER_STATE_CHANGE 0 0
08-05 14:14:21.825  1030  1389 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-05 14:14:21.836  1030  1957 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7079 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
08-05 14:14:21.838  4329  4329 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-05 14:14:21.842  4329  4329 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-05 14:14:21.843  4329  4329 V BluetoothFtpService: Ftp Service onStartCommand
08-05 14:14:21.843  4329  4329 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-05 14:14:21.844  4329  4329 V BluetoothFtpService: Ftp Service closeService
08-05 14:14:21.844  4329  4329 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-05 14:14:21.847  4329  4329 V BluetoothFtpService: successfully stopped ftp service
08-05 14:14:21.848  4329  4329 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-05 14:14:21.848  4329  4329 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-05 14:14:21.848  4329  4329 V BluetoothSapReceiver: SapReceiver onReceive 
08-05 14:14:21.848  4329  4329 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 14:14:21.848  4329  4329 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-05 14:14:21.848  4329  4329 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-05 14:14:21.849  4329  4329 V BluetoothFtpService: Ftp Service onDestroy
08-05 14:14:21.849  4329  4329 V BluetoothFtpService: Ftp Service closeService
08-05 14:14:21.891  1030  1733 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7096 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-05 14:14:21.904  4329  4329 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-05 14:14:21.904  4329  4329 V BluetoothSapService: state: 13
08-05 14:14:21.904  4329  4329 V BluetoothSapService: Stopping SAP server process
,08-05 14:14:21.905  4329  4329 V BluetoothSapService: Sap Service closeSapService in
08-05 14:14:21.906  4329  4329 V BluetoothSapService: Close listen Socket : 
08-05 14:14:21.906  4329  4329 V BluetoothSapService: Close rfcomm Socket : 
08-05 14:14:21.906  4329  4329 V BluetoothSapService: Close sapd  Socket : 
08-05 14:14:21.907  4329  4329 V BluetoothSapService: Sap Service closeSapService out
08-05 14:14:21.907  4329  4329 V BluetoothSapService: Sap Service onDestroy
08-05 14:14:21.907  4329  4329 V BluetoothSapService: Sap Service closeSapService in
08-05 14:14:21.907  4329  4329 V BluetoothSapService: Close listen Socket : 
08-05 14:14:21.907  4329  4329 V BluetoothSapService: Close rfcomm Socket : 
08-05 14:14:21.908  4329  4329 V BluetoothSapService: Close sapd  Socket : 
08-05 14:14:21.908  4329  4329 V BluetoothSapService: Sap Service closeSapService out
08-05 14:14:21.932  7079  7079 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-05 14:14:21.967  7079  7079 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-05 14:14:21.971  7096  7096 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-05 14:14:21.989  1030  1992 I ActivityManager: Killing 6457:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,08-05 14:14:22.006  7079  7079 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,08-05 14:14:22.006  7079  7079 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-05 14:14:22.007  7079  7079 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-05 14:14:22.007  7079  7079 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-05 14:14:22.007  7079  7079 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-05 14:14:22.009  7079  7079 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-05 14:14:22.015  7079  7079 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-05 14:14:22.049  1030  1934 W libprocessgroup: failed to open /acct/uid_10008/pid_6457/cgroup.procs: No such file or directory
,08-05 14:14:22.062  7079  7079 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 14:14:22.067  7079  7079 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-05 14:14:22.095  7079  7079 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-05 14:14:22.098  6408  6408 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 14:14:22.101  7079  7079 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-05 14:14:22.104  7045  7045 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-05 14:14:22.104  7045  7045 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-05 14:14:22.104  7045  7045 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-05 14:14:22.108  7002  7002 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 14:14:22.114  7002  7002 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 14:14:22.115  7079  7079 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-05 14:14:22.124  7079  7079 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-05 14:14:22.125  7079  7079 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 14:14:22.128  7079  7079 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-05 14:14:22.132  6408  6408 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 14:14:22.137  7045  7045 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-05 14:14:22.137  7045  7045 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-05 14:14:22.137  7045  7045 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-05 14:14:22.145  7002  7002 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 14:14:22.155  7002  7002 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-05 14:14:22.165  7079  7079 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-05 14:14:22.169  7079  7079 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 14:14:22.172  7079  7079 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-05 14:14:22.202  4329  4432 D bt_hci_bdroid: cleanup
,08-05 14:14:22.202  4329  4558 I bt_lpm  : LPM is already off!!!
08-05 14:14:22.203  4329  4556 W bt-btif : ag scb idx 1 not allocated
08-05 14:14:22.203  4329  4556 E bt-btif : BTA AG is already disabled, ignoring ...
08-05 14:14:22.203  4329  4556 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-05 14:14:22.203  4329  4556 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-05 14:14:22.203  4329  4556 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-05 14:14:22.203  4329  4556 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-05 14:14:22.203  4329  4556 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-05 14:14:22.203  4329  4556 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-05 14:14:22.203  4329  4556 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-05 14:14:22.203  4329  4556 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-05 14:14:22.203  4329  4556 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-05 14:14:22.203  4329  4556 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-05 14:14:22.203  4329  4556 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-05 14:14:22.203  4329  4556 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-05 14:14:22.203  4329  4556 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-05 14:14:22.203  4329  4556 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-05 14:14:22.204  4329  4556 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-05 14:14:22.204  4329  4556 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-05 14:14:22.204  4329  4556 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-05 14:14:22.204  4329  4556 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-05 14:14:22.204  4329  4556 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-05 14:14:22.206  4329  4680 I bt_userial_mct: exiting userial_read_thread
08-05 14:14:22.206  4329  4680 D bt_userial_mct: Leaving userial_evt_read_thread()
08-05 14:14:22.207  4329  4432 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-05 14:14:22.207  4329  4558 I bt_vendor: hw_epilog_process
08-05 14:14:22.208  4329  4432 D bt_hci_bdroid: cleanup Finalizing cleanup
08-05 14:14:22.208  4329  4432 D bt_userial_mct: userial_close
08-05 14:14:22.208  4329  4432 E bt_userial_mct: pthread_join() FAILED result:3
08-05 14:14:22.208  4329  4432 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-05 14:14:22.243  1030  1915 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7117 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-05 14:14:22.271  4329  4432 D bt_hci_bdroid: set_power 0
08-05 14:14:22.272  4329  4432 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-05 14:14:22.272  4329  4432 I bt_vendor: bluetooth satus is on
08-05 14:14:22.272  4329  4432 I bt_vendor: bt-vendor : resetting BT status
08-05 14:14:22.272  4329  4432 I bt_vendor: Starting hciattach daemon
08-05 14:14:22.272  4329  4432 I bt_vendor: try to set false
08-05 14:14:22.273  4329  4432 I bt_vendor: Starting hciattach daemon
08-05 14:14:22.273  4329  4432 I bt_vendor: try to set false
08-05 14:14:22.273  4329  4432 I bt_vendor: cleanup
08-05 14:14:22.274  4329  4556 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-05 14:14:22.274  4329  4432 I GKI_LINUX: GKI_exit_task 0 done
08-05 14:14:22.274  4329  4432 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,08-05 14:14:22.276  4329  4428 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-05 14:14:22.278  4329  4329 D HeadsetService: Received stop request...Stopping profile...
08-05 14:14:22.279  4329  4329 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
,08-05 14:14:22.279  4329  4329 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-05 14:14:22.279  4329  4329 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@377f372a
08-05 14:14:22.280  4329  4507 D HeadsetStateMachine: Exit Disconnected: -1
08-05 14:14:22.280  1849  1849 D BluetoothHeadset: Proxy object disconnected
08-05 14:14:22.280  1849  1849 D BluetoothHeadset: Proxy object disconnected
08-05 14:14:22.281  1849  1849 D BluetoothHeadset: Proxy object disconnected
08-05 14:14:22.281  1030  1030 D BluetoothHeadset: Proxy object disconnected
08-05 14:14:22.281  1030  1030 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-05 14:14:22.282  4329  4329 D A2dpService: Received stop request...Stopping profile...
08-05 14:14:22.282  4329  4541 D A2dpStateMachine: Exit Disconnected: -1
08-05 14:14:22.282  4329  4329 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-05 14:14:22.285  4329  4329 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-05 14:14:22.285  4329  4329 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-05 14:14:22.285  4329  4329 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@377f372a
08-05 14:14:22.286  4329  4329 D HidService: Received stop request...Stopping profile...
,08-05 14:14:22.287  4329  4329 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@377f372a
08-05 14:14:22.287  4329  4428 D BluetoothAdapterState: Stopping profile services that were post enabled
08-05 14:14:22.288  1030  1030 D BluetoothA2dp: Proxy object disconnected
08-05 14:14:22.288  1030  1030 D AudioService: onServiceDisconnected: Bluetooth profile: 2,
08-05 14:14:22.288  4329  4329 D HealthService: Received stop request...Stopping profile...
08-05 14:14:22.288  4329  4329 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@377f372a
,08-05 14:14:22.291  4329  4329 D HeadsetStateMachine: Unbinding service...
08-05 14:14:22.292  4329  4329 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-05 14:14:22.292  4329  4329 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-05 14:14:22.292  4329  4329 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-05 14:14:22.292  4329  4329 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-05 14:14:22.292  4329  4329 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-05 14:14:22.292  4329  4329 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-05 14:14:22.292  4329  4329 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-05 14:14:22.293  4329  4329 D PanService: Received stop request...Stopping profile...
08-05 14:14:22.293  7002  7002 D BluetoothInputDevice: Proxy object disconnected
08-05 14:14:22.294  4329  4329 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@377f372a
08-05 14:14:22.295  4329  4329 D BtGatt.DebugUtils: handleDebugAction() action=null
08-05 14:14:22.295  4329  4329 D BtGatt.GattService: Received stop request...Stopping profile...
08-05 14:14:22.295  4329  4329 D BtGatt.GattService: stop()
08-05 14:14:22.295  4329  4329 D BtGatt.AdvertiseManager: advertise clients cleared
08-05 14:14:22.296  4329  4329 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@377f372a
08-05 14:14:22.297  4329  4329 I BluetoothA2dpServiceJni: cleanupNative
08-05 14:14:22.297  7002  7002 D HidProfile: Bluetooth service disconnected
08-05 14:14:22.297  4329  4542 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-05 14:14:22.298  4329  4329 I GKI_LINUX: GKI_exit_task 2 done
08-05 14:14:22.298  4329  4329 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-05 14:14:22.302  4329  4329 D BluetoothMapService: Received stop request...Stopping profile...
08-05 14:14:22.302  4329  4329 D BluetoothMapService: stop()
08-05 14:14:22.303  4329  4329 D BluetoothMapEmailAppObserver: deinitObservers()
08-05 14:14:22.303  4329  4329 D BluetoothMapEmailAppObserver: removeReceiver()
08-05 14:14:22.303  4329  4329 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@377f372a
,08-05 14:14:22.304  4329  4329 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-05 14:14:22.304  4329  4329 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-05 14:14:22.305  4329  4329 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-05 14:14:22.305  4329  4329 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-05 14:14:22.305  4329  4329 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-05 14:14:22.305  4329  4329 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-05 14:14:22.305  4329  4329 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-05 14:14:22.306  7002  7002 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-05 14:14:22.306  7002  7002 D PanProfile: Bluetooth service disconnected
08-05 14:14:22.307  4329  4329 V BluetoothMapService: Handler(): got msg=4
08-05 14:14:22.307  4329  4329 D BluetoothMapService: MAP Service closeService in
08-05 14:14:22.307  4329  4329 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-05 14:14:22.307  4329  4329 V BluetoothMapService: MAP Service closeService out
08-05 14:14:22.307  4329  4428 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-05 14:14:22.308  4329  4428 D BluetoothAdapterProperties: Setting state to 10
08-05 14:14:22.308  4329  4428 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-05 14:14:22.308  4329  4329 D BluetoothMapService: cleanup()
08-05 14:14:22.308  4329  4329 D BluetoothMapService: MAP Service closeService in
08-05 14:14:22.308  4329  4329 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-05 14:14:22.308  4329  4329 V BluetoothMapService: MAP Service closeService out
08-05 14:14:22.308  4329  4428 I BluetoothAdapterState: Entering OffState
08-05 14:14:22.308  1030  1094 D BluetoothManagerService: Message: 60
08-05 14:14:22.308  1030  1094 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-05 14:14:22.308  1030  1094 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-05 14:14:22.309  7002  7022 D BluetoothMap: onBluetoothStateChange: up=false
08-05 14:14:22.309  7002  7002 D BluetoothMap: Proxy object disconnected
08-05 14:14:22.309  7002  7002 D MapProfile: Bluetooth service disconnected
08-05 14:14:22.314  7002  7064 D BluetoothPbap: onBluetoothStateChange: up=false
08-05 14:14:22.314  1849  2673 D BluetoothHeadset: onBluetoothStateChange: up=false
08-05 14:14:22.315  1030  1094 D BluetoothHeadset: onBluetoothStateChange: up=false
08-05 14:14:22.315  7002  7023 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-05 14:14:22.316  7002  7022 D BluetoothPan: onBluetoothStateChange on: false
08-05 14:14:22.316  1030  1094 D BluetoothA2dp: onBluetoothStateChange: up=false
08-05 14:14:22.316  1849  1864 D BluetoothHeadset: onBluetoothStateChange: up=false
08-05 14:14:22.317  1849  1865 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-05 14:14:22.319  1030  1094 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-05 14:14:22.319  1030  1094 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-05 14:14:22.321  1030  1094 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-05 14:14:22.322  1030  1094 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-05 14:14:22.322  1030  1094 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@1b3f02ff mBinding = false
08-05 14:14:22.322  1030  1094 D BluetoothManagerService: Sending unbind request.
08-05 14:14:22.323  1030  1094 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-05 14:14:22.326  1600  1600 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-05 14:14:22.329  1938  1938 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-05 14:14:22.330  1938  2121 D LGBluetoothAPIService: Message: 2
08-05 14:14:22.330  1938  2121 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@2c364f25 mBinding = false
08-05 14:14:22.330  1938  2121 D LGBluetoothAPIService: Sending unbind request.
08-05 14:14:22.332  6923  6923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 14:14:22.333  6923  6923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 14:14:22.333  4329  4432 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-05 14:14:22.334  4329  4329 I GKI_LINUX: GKI_exit_task 1 done
08-05 14:14:22.334  4329  4329 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-05 14:14:22.334  4329  4329 I BluetoothServiceJni: cleanupNative: return from cleanup
08-05 14:14:22.334  4329  4329 I art     : --- WEIRD: removing null entry 246
08-05 14:14:22.334  4329  4329 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-05 14:14:22.334  4329  4329 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-05 14:14:22.335  4329  4329 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-05 14:14:22.336  1600  1600 D BluetoothAdapter: 87351117: getState() :  mService = null. Returning STATE_OFF
08-05 14:14:22.336  1600  1600 D BluetoothAdapter: 87351117: getState() :  mService = null. Returning STATE_OFF
08-05 14:14:22.337  7002  7002 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-05 14:14:22.338  4329  4329 I art     : System.exit called, status: 0
08-05 14:14:22.338  4329  4329 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-05 14:14:22.339  7002  7002 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-05 14:14:22.339  7002  7002 D LGBluetoothEventManager: [BTUI] clear device connection state
08-05 14:14:22.340  7002  7002 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-05 14:14:22.347  7002  7002 D DockEventReceiver: finishStartingService: stopping service
08-05 14:14:22.357   312  2161 V AudioFlinger: 4329 died, releasing its sessions
08-05 14:14:22.357   312  2161 V AudioFlinger:  pid 1849 @ 0
08-05 14:14:22.357   312  2161 V AudioFlinger:  pid 3317 @ 1
08-05 14:14:22.357   312  2161 V AudioFlinger:  pid 3317 @ 2
08-05 14:14:22.357  7002  7002 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
,08-05 14:14:22.391  1030  1592 I ActivityManager: Process com.android.bluetooth (pid 4329) has died
,08-05 14:14:22.392  1030  1592 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,08-05 14:14:22.397  2185  2185 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-05 14:14:22.410  7045  7045 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-05 14:14:22.423  7002  7002 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-05 14:14:22.430  7117  7142 W FormManager: Network not available. Please check & try again.
08-05 14:14:22.436  7002  7002 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-05 14:14:22.440  7002  7002 D BluetoothPermissionRequest: onReceive
,08-05 14:14:22.444  7002  7002 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-05 14:14:22.445  7002  7002 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-05 14:14:22.446  7002  7002 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-05 14:14:22.490  1030  1986 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7146 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-05 14:14:22.501  7117  7143 V FormManager: Network unavailable.
08-05 14:14:22.519   338   338 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 463us total 27.178ms
08-05 14:14:22.519  7117  7143 V FormManager: Network unavailable.
08-05 14:14:22.522  7002  7002 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-05 14:14:22.522  7002  7002 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
,08-05 14:14:22.522  7002  7002 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-05 14:14:22.523  7002  7002 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-05 14:14:22.523  7002  7002 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-05 14:14:22.541   338   338 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 570us total 21.102ms
08-05 14:14:22.547  7002  7002 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-05 14:14:22.547  7002  7002 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-05 14:14:22.547  7002  7002 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-05 14:14:22.547  7002  7002 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-05 14:14:22.548  7002  7002 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-05 14:14:22.548  7002  7002 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-05 14:14:22.550  1030  1957 I ActivityManager: Killing 6506:com.lge.appbox.client/u0a11 (adj 15): empty #17
08-05 14:14:22.560  7146  7146 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-05 14:14:22.560  7146  7146 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-05 14:14:22.561  7146  7146 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-05 14:14:22.562  7146  7146 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-05 14:14:22.563   338   338 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 448us total 21.179ms
08-05 14:14:22.579  7146  7146 D BluetoothAdapterApp: Loading JNI Library
,08-05 14:14:22.604  1030  2014 W libprocessgroup: failed to open /acct/uid_10011/pid_6506/cgroup.procs: No such file or directory
,08-05 14:14:22.605  4803  4803 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-05 14:14:22.605  4803  4803 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-05 14:14:22.607  4803  4803 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 14:14:22.609  4803  4803 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 14:14:22.617  7045  7045 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-05 14:14:22.617  7045  7045 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-05 14:14:22.617  7045  7045 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-05 14:14:22.619  7146  7146 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@14b798a3 Instance Count = 1
,08-05 14:14:22.623  4803  7167 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-05 14:14:22.624  7002  7002 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-05 14:14:22.625  7146  7146 D BluetoothAdapterApp: onCreate
,08-05 14:14:22.628  4803  7165 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-05 14:14:22.630  4803  7167 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-05 14:14:22.634  7117  7168 W FormManager: Network not available. Please check & try again.
08-05 14:14:22.635  7002  7002 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 14:14:22.643  7117  7169 V FormManager: Network unavailable.
,08-05 14:14:22.648  7117  7169 V FormManager: Network unavailable.
08-05 14:14:22.648  7146  7146 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-05 14:14:22.648  7146  7146 D ProfileConfigQcom: Adding HeadsetService
08-05 14:14:22.649  7146  7146 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-05 14:14:22.649  7146  7146 D ProfileConfigQcom: Adding A2dpService
08-05 14:14:22.649  7146  7146 D ProfileConfigQcom: [BTUI] HidService is supported
08-05 14:14:22.649  7146  7146 D ProfileConfigQcom: Adding HidService
,08-05 14:14:22.649  7146  7146 D ProfileConfigQcom: [BTUI] HealthService is supported
08-05 14:14:22.650  7146  7146 D ProfileConfigQcom: Adding HealthService
08-05 14:14:22.650  7146  7146 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-05 14:14:22.650  7146  7146 D ProfileConfigQcom: [BTUI] PanService is supported
08-05 14:14:22.651  7146  7146 D ProfileConfigQcom: Adding PanService
08-05 14:14:22.651  7146  7146 D ProfileConfigQcom: [BTUI] GattService is supported
08-05 14:14:22.651  7146  7146 D ProfileConfigQcom: Adding GattService
08-05 14:14:22.651  7146  7146 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-05 14:14:22.651  7146  7146 D ProfileConfigQcom: Adding BluetoothMapService
08-05 14:14:22.652  7146  7146 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-05 14:14:22.655  7146  7146 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,08-05 14:14:22.656  7079  7079 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-05 14:14:22.657  7079  7079 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-05 14:14:22.658  7079  7079 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-05 14:14:22.690  7079  7079 D LgDataFeature: LgDataFeature() Constructor: none
08-05 14:14:22.690  7079  7079 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-05 14:14:22.696  7079  7079 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-05 14:14:22.696  7079  7079 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-05 14:14:22.696  7079  7079 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-05 14:14:22.696  7079  7079 V SoundPool: doLoad: loading sample sampleID=1
08-05 14:14:22.697  7079  7079 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-05 14:14:22.699  7079  7174 V SoundPool: Start decode
08-05 14:14:22.699  7079  7174 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-05 14:14:22.700   312  2154 V MediaPlayerService: decode(22, 10857164, 17813)
08-05 14:14:22.700   312  2154 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-05 14:14:22.700   312  2154 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-05 14:14:22.700   312  2154 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-05 14:14:22.700   312  2154 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-05 14:14:22.700   312  2154 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-05 14:14:22.700   312  2154 V MediaPlayerService: player type = 3
08-05 14:14:22.700   312  2154 V AwesomePlayer: AwesomePlayer create()
08-05 14:14:22.700   312  2154 V AwesomePlayer: reset_l() 
08-05 14:14:22.700   312  2154 V AwesomePlayer: cancelPlayerEvents
08-05 14:14:22.700   312  2154 V AwesomePlayer: setAudioSink() 
08-05 14:14:22.700   312  2154 V AwesomePlayer: reset_l() 
08-05 14:14:22.700   312  2154 V AudioCache: notify(0xb5474800, 8, 0, 0)
08-05 14:14:22.700   312  2154 V AudioCache: ignored
08-05 14:14:22.700   312  2154 V AwesomePlayer: cancelPlayerEvents
08-05 14:14:22.700   312  2154 D Utils   : printFileName fd(23) -> /data/preload/LGQRemote/LGQRemote.apk
08-05 14:14:22.700   312  2154 V AwesomePlayer: setDataSource_l dataSource
08-05 14:14:22.700   312  2154 V LGParserOSAL: SniffLGParser start
08-05 14:14:22.701   312  2154 V LGParserOSAL: MainType:5, SubType=0
08-05 14:14:22.701   312  2154 V LGParserOSAL: #### check Mime : application/ogg
08-05 14:14:22.701   312  2154 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-05 14:14:22.701   312  2154 E MediaExtractor: Use LGExtractor :application/ogg 
08-05 14:14:22.733   312  2154 V LGParserOSAL: supported mime: application/ogg
08-05 14:14:22.733   312  2154 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-05 14:14:22.733   312  2154 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-05 14:14:22.733   312  2154 V AwesomePlayer: mBitrate = -1 bits/sec
08-05 14:14:22.733   312  2154 V AwesomePlayer: AudioTrack Setting
08-05 14:14:22.733   312  2154 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-05 14:14:22.733   312  2154 V AwesomePlayer: setAudioSource() 
08-05 14:14:22.733   312  2154 V MediaPlayerService: prepare
08-05 14:14:22.733   312  2154 V AwesomePlayer: prepareAsync_l() 
08-05 14:14:22.733   312  2154 V MediaPlayerService: wait for prepare
08-05 14:14:22.735   312  7175 V AwesomePlayer: onPrepareAsyncEvent() 
08-05 14:14:22.735   312  7175 V AwesomePlayer: initAudioDecoder() 
08-05 14:14:22.735   312  7175 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-05 14:14:22.735   312  7175 V AudioSystem: isOffloadSupported()
,08-05 14:14:22.736   312  7175 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-05 14:14:22.736   312  7175 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-05 14:14:22.736   312  7175 I AudioFlinger: isAudioPlaybackHookOn() false
08-05 14:14:22.736   312  7175 V AwesomePlayer: getUseOffload() = 0 
08-05 14:14:22.736   312  7175 V OMXCodec: OMXCodec::Create
08-05 14:14:22.736   312  7175 V OMXCodec: findMatchingCodecs()
08-05 14:14:22.736   312  7175 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-05 14:14:22.736   312  7175 V OMXCodec: matchingCodecs.size()=1
08-05 14:14:22.736   312  7175 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-05 14:14:22.740   312  7175 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-05 14:14:22.740   312  7175 V LGCodecAdapter: LG Codec Adapter start
08-05 14:14:22.741   312  7175 V OMXCodec: OMXCodec Createtor
08-05 14:14:22.741   312  7175 V OMXCodec: setComponentRole
08-05 14:14:22.741   312  7175 V OMXCodec: configureCodec protected=0
08-05 14:14:22.741   312  7175 V LGCodecAdapter: called getLGCodecSpecificData
08-05 14:14:22.741   312  7175 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-05 14:14:22.741   312  7175 V LGCodecOSAL: Called LGconfigureCodecMETA
08-05 14:14:22.741   312  7175 V LGCodecOSAL: Called LGconfigureCodecMSG
08-05 14:14:22.741   312  7175 V LGCodecOSAL: Not support LGCodec
08-05 14:14:22.741   312  7175 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-05 14:14:22.741   312  7175 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-05 14:14:22.741   312  7175 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-05 14:14:22.742   312  7175 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-05 14:14:22.742   312  7175 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-05 14:14:22.742   312  7175 V AudioSystem: isOffloadSupported()
08-05 14:14:22.742   312  7175 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
,08-05 14:14:22.742   312  7175 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-05 14:14:22.742   312  7175 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-05 14:14:22.742   312  7175 V OMXCodec: init()
08-05 14:14:22.742   312  7175 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-05 14:14:22.742   312  7175 V OMXCodec: allocateBuffers
08-05 14:14:22.742   312  7175 V OMXCodec: allocateBuffersOnPort portIndex=0
08-05 14:14:22.742   312  7175 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-05 14:14:22.743   312  7175 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb100d240 on input port
08-05 14:14:22.743   312  7175 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb100d290 on input port
08-05 14:14:22.743   312  7175 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb100d2e0 on input port
08-05 14:14:22.743   312  7175 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb100d330 on input port
08-05 14:14:22.743   312  7175 V OMXCodec: allocateBuffersOnPort portIndex=1
08-05 14:14:22.743   312  7175 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-05 14:14:22.743   312  7175 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb100d380 on output port
08-05 14:14:22.744   312  7175 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb100d600 on output port
08-05 14:14:22.744   312  7175 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb100d7e0 on output port
08-05 14:14:22.744   312  7175 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb100d880 on output port
08-05 14:14:22.744   312  7175 V OMXCodec: init() mAsyncCompletion wait!!! 
08-05 14:14:22.744   312  7177 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-05 14:14:22.744   312  7177 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-05 14:14:22.744   312  7177 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-05 14:14:22.744   312  7175 V OMXCodec: init() mAsyncCompletion wait!!! 
08-05 14:14:22.744   312  7177 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-05 14:14:22.744   312  7177 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-05 14:14:22.744   312  7177 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-05 14:14:22.744   312  7175 V OMXCodec: init() mAsyncCompletion wait free! 
,08-05 14:14:22.744   312  7175 V AwesomePlayer: finishAsyncPrepare_l() 
08-05 14:14:22.744   312  7175 V AudioCache: notify(0xb5474800, 5, 0, 0)
08-05 14:14:22.744   312  7175 V AudioCache: ignored
08-05 14:14:22.744   312  7175 V AudioCache: notify(0xb5474800, 1, 0, 0)
08-05 14:14:22.744   312  7175 V AudioCache: prepared
08-05 14:14:22.744   312  2154 V AudioCache: wait - success
08-05 14:14:22.744   312  2154 V MediaPlayerService: start
08-05 14:14:22.744   312  2154 V AwesomePlayer: play_l() 
08-05 14:14:22.744   312  2154 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
,08-05 14:14:22.744   312  2154 V AwesomePlayer: createAudioPlayer_l
08-05 14:14:22.744   312  2154 V AwesomePlayer: seekAudioIfNecessary_l() 
08-05 14:14:22.744   312  2154 V AwesomePlayer: startAudioPlayer_l() 
08-05 14:14:22.744   312  2154 D AudioPlayer: start of Playback, useOffload 0
08-05 14:14:22.744   312  2154 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-05 14:14:22.744   312  2154 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-05 14:14:22.746   312  7177 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-05 14:14:22.746   312  7177 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-05 14:14:22.746   312  7177 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-05 14:14:22.746   312  7177 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
,08-05 14:14:22.746   312  7177 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-05 14:14:22.746   312  7177 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-05 14:14:22.746   312  7177 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2969621376
08-05 14:14:22.746   312  7177 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-05 14:14:22.746   312  7177 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2969622016
08-05 14:14:22.746   312  7177 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-05 14:14:22.747   312  7177 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2969622496
08-05 14:14:22.747   312  7177 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-05 14:14:22.747   312  7177 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2969622656
,08-05 14:14:22.747   312  7177 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-05 14:14:22.747   312  7177 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-05 14:14:22.747   312  7177 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-05 14:14:22.747   312  7177 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-05 14:14:22.747   312  7177 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-05 14:14:22.747   312  7177 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-05 14:14:22.747   312  7177 V OMXCodec: allocateBuffersOnPort portIndex=1
08-05 14:14:22.747   312  7177 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,08-05 14:14:22.747   312  7177 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb100d7e0 on output port
,08-05 14:14:22.747   312  7177 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb100d600 on output port
08-05 14:14:22.747   312  7177 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb100d380 on output port
08-05 14:14:22.747   312  7177 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f330 on output port
08-05 14:14:22.747   312  7177 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-05 14:14:22.747   312  7177 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-05 14:14:22.754   312  2154 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-05 14:14:22.754   312  2154 V AudioCache: notify(0xb5474800, 6, 0, 0)
08-05 14:14:22.754   312  2154 V AudioCache: ignored
08-05 14:14:22.755   312  2154 V MediaPlayerService: wait for playback complete
08-05 14:14:22.756   312  7178 V AudioCache: write(0xb16ba000, 4096)
08-05 14:14:22.756   312  7178 V AudioCache: memcpy(0xaf0f9000, 0xb16ba000, 4096)
08-05 14:14:22.758   312  7178 V AudioCache: write(0xb16ba000, 4096)
08-05 14:14:22.758   312  7178 V AudioCache: memcpy(0xaf0fa000, 0xb16ba000, 4096)
08-05 14:14:22.759   312  7178 V AudioCache: write(0xb16ba000, 4096)
08-05 14:14:22.759   312  7178 V AudioCache: memcpy(0xaf0fb000, 0xb16ba000, 4096)
08-05 14:14:22.760   312  7178 V AudioCache: write(0xb16ba000, 4096)
08-05 14:14:22.760   312  7178 V AudioCache: memcpy(0xaf0fc000, 0xb16ba000, 4096)
,08-05 14:14:22.762   312  7178 V AudioCache: write(0xb16ba000, 4096),
08-05 14:14:22.762   312  7178 V AudioCache: memcpy(0xaf0fd000, 0xb16ba000, 4096)
08-05 14:14:22.763   312  7178 V AudioCache: write(0xb16ba000, 4096)
08-05 14:14:22.763   312  7178 V AudioCache: memcpy(0xaf0fe000, 0xb16ba000, 4096)
08-05 14:14:22.764   312  7178 V AudioCache: write(0xb16ba000, 4096)
08-05 14:14:22.764   312  7178 V AudioCache: memcpy(0xaf0ff000, 0xb16ba000, 4096)
08-05 14:14:22.764   312  7178 V AudioCache: write(0xb16ba000, 4096)
08-05 14:14:22.764   312  7178 V AudioCache: memcpy(0xaf100000, 0xb16ba000, 4096)
08-05 14:14:22.764   312  7178 V AudioCache: write(0xb16ba000, 4096)
08-05 14:14:22.764   312  7178 V AudioCache: memcpy(0xaf101000, 0xb16ba000, 4096)
,08-05 14:14:22.767   312  7178 V AudioCache: write(0xb16ba000, 4096)
08-05 14:14:22.767   312  7178 V AudioCache: memcpy(0xaf102000, 0xb16ba000, 4096)
08-05 14:14:22.767   312  7178 V AudioCache: write(0xb16ba000, 4096)
08-05 14:14:22.767   312  7178 V AudioCache: memcpy(0xaf103000, 0xb16ba000, 4096)
08-05 14:14:22.768   312  7178 V AudioCache: write(0xb16ba000, 4096)
08-05 14:14:22.768   312  7178 V AudioCache: memcpy(0xaf104000, 0xb16ba000, 4096)
08-05 14:14:22.769   312  7178 V AudioCache: write(0xb16ba000, 4096)
08-05 14:14:22.769   312  7178 V AudioCache: memcpy(0xaf105000, 0xb16ba000, 4096)
08-05 14:14:22.770   312  7178 V AudioCache: write(0xb16ba000, 4096)
08-05 14:14:22.770   312  7178 V AudioCache: memcpy(0xaf106000, 0xb16ba000, 4096)
,08-05 14:14:22.772   312  7178 V AudioCache: write(0xb16ba000, 4096)
08-05 14:14:22.772   312  7178 V AudioCache: memcpy(0xaf107000, 0xb16ba000, 4096)
,08-05 14:14:22.773   312  7178 V AudioCache: write(0xb16ba000, 4096)
08-05 14:14:22.773   312  7178 V AudioCache: memcpy(0xaf108000, 0xb16ba000, 4096)
08-05 14:14:22.773   312  7178 V AudioCache: write(0xb16ba000, 4096)
08-05 14:14:22.773   312  7178 V AudioCache: memcpy(0xaf109000, 0xb16ba000, 4096)
08-05 14:14:22.775   312  7178 V AudioCache: write(0xb16ba000, 4096)
08-05 14:14:22.775   312  7178 V AudioCache: memcpy(0xaf10a000, 0xb16ba000, 4096)
08-05 14:14:22.775  1030  1992 I art     : Explicit concurrent mark sweep GC freed 63452(2MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 1.511ms total 115.810ms
08-05 14:14:22.777  6778  6778 D UEI.SmartControl: QS Service created
08-05 14:14:22.777  7002  7002 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-05 14:14:22.778  7146  7146 V LGMDMManagerInternal: Create singleton instance
08-05 14:14:22.782   312  7178 V AudioCache: write(0xb16ba000, 4096)
08-05 14:14:22.782   312  7178 V AudioCache: memcpy(0xaf10b000, 0xb16ba000, 4096)
08-05 14:14:22.782   312  7178 V AudioCache: write(0xb16ba000, 4096)
08-05 14:14:22.782   312  7178 V AudioCache: memcpy(0xaf10c000, 0xb16ba000, 4096)
08-05 14:14:22.783   312  7178 V AudioCache: write(0xb16ba000, 4096)
08-05 14:14:22.783   312  7178 V AudioCache: memcpy(0xaf10d000, 0xb16ba000, 4096)
08-05 14:14:22.783   312  7178 V AudioCache: write(0xb16ba000, 4096)
08-05 14:14:22.783   312  7178 V AudioCache: memcpy(0xaf10e000, 0xb16ba000, 4096)
08-05 14:14:22.783   312  7178 V AudioCache: write(0xb16ba000, 4096)
08-05 14:14:22.783   312  7178 V AudioCache: memcpy(0xaf10f000, 0xb16ba000, 4096)
08-05 14:14:22.784   312  7178 V AudioCache: write(0xb16ba000, 4096)
08-05 14:14:22.784   312  7178 V AudioCache: memcpy(0xaf110000, 0xb16ba000, 4096)
08-05 14:14:22.784   312  7178 V AudioCache: write(0xb16ba000, 4096)
08-05 14:14:22.784   312  7178 V AudioCache: memcpy(0xaf111000, 0xb16ba000, 4096)
08-05 14:14:22.784   312  7178 V AudioCache: write(0xb16ba000, 4096)
08-05 14:14:22.784   312  7178 V AudioCache: memcpy(0xaf112000, 0xb16ba000, 4096)
08-05 14:14:22.785   312  7178 V AudioCache: write(0xb16ba000, 4096)
08-05 14:14:22.785   312  7178 V AudioCache: memcpy(0xaf113000, 0xb16ba000, 4096)
08-05 14:14:22.785   312  7178 V AudioCache: write(0xb16ba000, 4096)
08-05 14:14:22.785   312  7178 V AudioCache: memcpy(0xaf114000, 0xb16ba000, 4096)
08-05 14:14:22.786   312  7178 V AudioCache: write(0xb16ba000, 4096)
08-05 14:14:22.786   312  7178 V AudioCache: memcpy(0xaf115000, 0xb16ba000, 4096)
08-05 14:14:22.786   312  7178 V AudioCache: write(0xb16ba000, 4096)
08-05 14:14:22.786   312  7178 V AudioCache: memcpy(0xaf116000, 0xb16ba000, 4096)
08-05 14:14:22.786   312  7178 V AudioCache: write(0xb16ba000, 4096)
08-05 14:14:22.786   312  7178 V AudioCache: memcpy(0xaf117000, 0xb16ba000, 4096)
08-05 14:14:22.787   312  7178 V AudioCache: write(0xb16ba000, 4096)
08-05 14:14:22.787   312  7178 V AudioCache: memcpy(0xaf118000, 0xb16ba000, 4096)
08-05 14:14:22.787   312  7178 V AudioCache: write(0xb16ba000, 4096)
08-05 14:14:22.787   312  7178 V AudioCache: memcpy(0xaf119000, 0xb16ba000, 4096)
08-05 14:14:22.787   312  7178 V AudioCache: write(0xb16ba000, 4096)
08-05 14:14:22.787   312  7178 V AudioCache: memcpy(0xaf11a000, 0xb16ba000, 4096)
08-05 14:14:22.787  6778  6778 I UEI.SmartControl: Service initServices...
08-05 14:14:22.788  6778  6778 D UEI.SmartControl: QS start get config
08-05 14:14:22.788   312  7178 V AudioCache: write(0xb16ba000, 4096)
08-05 14:14:22.788   312  7178 V AudioCache: memcpy(0xaf11b000, 0xb16ba000, 4096)
08-05 14:14:22.791  7079  7079 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-05 14:14:22.795  7079  7079 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-05 14:14:22.796  7079  7079 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-05 14:14:22.804   312  7178 V AudioCache: write(0xb16ba000, 4096)
,08-05 14:14:22.804   312  7178 V AudioCache: memcpy(0xaf11c000, 0xb16ba000, 4096)
08-05 14:14:22.805   312  7178 V AudioCache: write(0xb16ba000, 4096)
08-05 14:14:22.805   312  7178 V AudioCache: memcpy(0xaf11d000, 0xb16ba000, 4096)
08-05 14:14:22.805   312  7178 V AudioCache: write(0xb16ba000, 4096)
08-05 14:14:22.805   312  7178 V AudioCache: memcpy(0xaf11e000, 0xb16ba000, 4096)
08-05 14:14:22.806   312  7178 V AudioCache: write(0xb16ba000, 4096)
08-05 14:14:22.806   312  7178 V AudioCache: memcpy(0xaf11f000, 0xb16ba000, 4096)
08-05 14:14:22.806   312  7178 V AudioCache: write(0xb16ba000, 4096)
08-05 14:14:22.806   312  7178 V AudioCache: memcpy(0xaf120000, 0xb16ba000, 4096)
08-05 14:14:22.807   312  7178 V AudioCache: write(0xb16ba000, 4096)
08-05 14:14:22.807   312  7178 V AudioCache: memcpy(0xaf121000, 0xb16ba000, 4096)
08-05 14:14:22.808   312  7178 V AudioCache: write(0xb16ba000, 4096)
08-05 14:14:22.808   312  7178 V AudioCache: memcpy(0xaf122000, 0xb16ba000, 4096)
08-05 14:14:22.808  7079  7079 V LGMDMManager: Create singleton instance
08-05 14:14:22.808   312  7178 V AudioCache: write(0xb16ba000, 4096)
08-05 14:14:22.808   312  7178 V AudioCache: memcpy(0xaf123000, 0xb16ba000, 4096)
08-05 14:14:22.809   312  7178 V AudioCache: write(0xb16ba000, 4096)
08-05 14:14:22.809   312  7178 V AudioCache: memcpy(0xaf124000, 0xb16ba000, 4096)
08-05 14:14:22.810   312  7178 V AudioCache: write(0xb16ba000, 4096)
08-05 14:14:22.810   312  7178 V AudioCache: memcpy(0xaf125000, 0xb16ba000, 4096)
08-05 14:14:22.811   312  7178 V AudioCache: write(0xb16ba000, 4096)
08-05 14:14:22.811   312  7178 V AudioCache: memcpy(0xaf126000, 0xb16ba000, 4096)
08-05 14:14:22.813   312  7178 V AudioCache: write(0xb16ba000, 4096)
08-05 14:14:22.813   312  7178 V AudioCache: memcpy(0xaf127000, 0xb16ba000, 4096)
08-05 14:14:22.814   312  7178 V AudioCache: write(0xb16ba000, 4096)
08-05 14:14:22.814   312  7178 V AudioCache: memcpy(0xaf128000, 0xb16ba000, 4096)
08-05 14:14:22.815   312  7178 V AudioCache: write(0xb16ba000, 4096)
08-05 14:14:22.815   312  7178 V AudioCache: memcpy(0xaf129000, 0xb16ba000, 4096)
08-05 14:14:22.817   312  7178 V AudioCache: write(0xb16ba000, 4096)
08-05 14:14:22.817   312  7178 V AudioCache: memcpy(0xaf12a000, 0xb16ba000, 4096)
08-05 14:14:22.817   312  7177 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
,08-05 14:14:22.817   312  7178 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-05 14:14:22.817   312  7178 V AwesomePlayer: postAudioEOS() 
08-05 14:14:22.817   312  7178 V AudioCache: write(0xb16ba000, 280)
08-05 14:14:22.817   312  7178 V AudioCache: memcpy(0xaf12b000, 0xb16ba000, 280)
08-05 14:14:22.819   312  7175 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-05 14:14:22.819   312  7175 V AwesomePlayer: onStreamDone
08-05 14:14:22.819   312  7175 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-05 14:14:22.819   312  7175 V AudioCache: notify(0xb5474800, 2, 0, 0)
08-05 14:14:22.819   312  7175 V AudioCache: playback complete
08-05 14:14:22.819   312  7175 V AwesomePlayer: pause_l() 
08-05 14:14:22.819   312  2154 V AudioCache: wait - success
08-05 14:14:22.819   312  2154 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-05 14:14:22.819   312  7175 V AudioCache: notify(0xb5474800, 7, 0, 0)
08-05 14:14:22.819   312  7175 V AudioCache: ignored
08-05 14:14:22.819   312  7175 V AwesomePlayer: cancelPlayerEvents
08-05 14:14:22.820   312  7175 D AudioPlayer: Pause Playback at 1068125
08-05 14:14:22.820   312  2154 V AwesomePlayer: reset_l() 
08-05 14:14:22.820   312  2154 V AudioCache: notify(0xb5474800, 8, 0, 0)
08-05 14:14:22.820   312  2154 V AudioCache: ignored
08-05 14:14:22.820   312  2154 V AwesomePlayer: cancelPlayerEvents
08-05 14:14:22.820   312  2154 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-05 14:14:22.820   312  2154 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-05 14:14:22.820   312  2154 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-05 14:14:22.820   312  2154 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-05 14:14:22.820   312  2154 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-05 14:14:22.821   312  7177 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-05 14:14:22.821   312  7177 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-05 14:14:22.821   312  7177 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-05 14:14:22.821   312  7177 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb100d330 on port 0
08-05 14:14:22.821   312  7177 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-05 14:14:22.821   312  7177 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb100d2e0 on port 0
08-05 14:14:22.821   312  7177 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-05 14:14:22.821   312  7177 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb100d290 on port 0
08-05 14:14:22.822   312  7177 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-05 14:14:22.822   312  7177 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb100d240 on port 0
08-05 14:14:22.822   312  7177 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-05 14:14:22.822   312  7177 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-05 14:14:22.822   312  7177 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f330 on port 1
08-05 14:14:22.822   312  7177 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-05 14:14:22.822   312  7177 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb100d380 on port 1
08-05 14:14:22.822   312  7177 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-05 14:14:22.822   312  7177 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb100d600 on port 1
08-05 14:14:22.822   312  7177 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-05 14:14:22.822   312  7177 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb100d7e0 on port 1
08-05 14:14:22.822   312  7177 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-05 14:14:22.822   312  7177 V OMXCodec,: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-05 14:14:22.822   312  2154 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-05 14:14:22.822   312  2154 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-05 14:14:22.822   312  7177 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-05 14:14:22.822   312  7177 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-05 14:14:22.822   312  7177 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-05 14:14:22.822   312  2154 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-05 14:14:22.822   312  2154 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-05 14:14:22.822   312  2154 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-05 14:14:22.823  7146  7146 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-05 14:14:22.824   312  2154 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-05 14:14:22.824   312  2154 D AudioPlayer: AudioPlayer releasing audio source
08-05 14:14:22.824   312  2154 D AudioPlayer: AudioPlayer done releasing audio source
08-05 14:14:22.824   312  2154 V AwesomePlayer: reset_l() 
08-05 14:14:22.824   312  2154 V AwesomePlayer: cancelPlayerEvents
08-05 14:14:22.824   312  2154 V AwesomePlayer: ~AwesomePlayer call
08-05 14:14:22.824   312  2154 V AwesomePlayer: reset_l() 
08-05 14:14:22.824   312  2154 V AwesomePlayer: cancelPlayerEvents
08-05 14:14:22.824  7079  7174 V SoundPool: close(31)
08-05 14:14:22.824  7079  7174 V SoundPool: pointer = 0x9ffd4000, size = 205080, sampleRate = 48000, numChannels = 2
08-05 14:14:22.825  7146  7146 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-05 14:14:22.825  7146  7146 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-05 14:14:22.825  7146  7146 V BluetoothSapReceiver: SapReceiver onReceive 
08-05 14:14:22.826  7146  7146 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 14:14:22.826  7146  7146 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-05 14:14:22.832  7096  7096 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-05 14:14:22.873  7079  7079 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,08-05 14:14:22.874  7079  7079 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,08-05 14:14:22.877  7079  7079 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:8919
08-05 14:14:23.061  6778  6778 I UEI.SmartControl: Supports setup maps: true
08-05 14:14:23.064  6778  6778 D UEI.SmartControl: QS start statue = true Error code = 0
08-05 14:14:23.064  6778  6778 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-05 14:14:23.064  6778  6778 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-05 14:14:23.064  6778  6778 I UEI.SmartControl: ### init IR Blaster...
,08-05 14:14:23.068  6778  6778 D serial_port: Configuring serial port
,08-05 14:14:23.068  6778  6778 E UEI.SmartControl: UEIBLaster setting for 616
,08-05 14:14:23.068  6778  6778 I UEI.SmartControl: Setting serial record hearder size = 2
08-05 14:14:23.068  6778  6778 I UEI.SmartControl: configuring settings for MAXQ616
08-05 14:14:23.068  6778  6778 I UEI.SmartControl: Get version...
08-05 14:14:23.087  6778  7180 D UEI.SmartControl: serial port data available: 21
,08-05 14:14:23.113  6778  6778 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-05 14:14:23.113  6778  6778 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-05 14:14:23.113  6778  6778 I UEI.SmartControl: QS saving settings...
08-05 14:14:23.115  6778  6778 D UEI.SmartControl: IR Blaster version: 25672567
,08-05 14:14:23.132  6778  7180 D UEI.SmartControl: serial port data available: 4
08-05 14:14:23.164  6778  7186 I UEI.SmartControl: Device manager: loading config....
,08-05 14:14:23.166  6778  6778 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-05 14:14:23.168  6778  7186 D UEI.SmartControl: ----------- loading internal config...
08-05 14:14:23.169  6778  6778 E UEI.SmartControl: Services init done
08-05 14:14:23.169  6778  6778 D UEI.SmartControl: QS Service init finished
,08-05 14:14:23.176  6778  6778 D UEI.SmartControl: QS Service version name: 2.1.91
08-05 14:14:23.177  6778  6778 D UEI.SmartControl: QS Service version code: 201091
08-05 14:14:23.179  6778  6778 D UEI.SmartControl: Service requested: Control
08-05 14:14:23.184  6778  7186 E UEI.SmartControl: Loading SETTINGS...
,08-05 14:14:23.184  6778  6778 D UEI.SmartControl: Request IControl service: devices are loaded...
08-05 14:14:23.188  6778  6778 D UEI.SmartControl: Internal service binding...
08-05 14:14:23.189  7079  7079 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-05 14:14:23.193  6778  6794 I UEI.SmartControl: ------ IControl API: 11
08-05 14:14:23.193  6778  6794 D UEI.SmartControl: File observer start...
08-05 14:14:23.195  6778  6794 E UEI.SmartControl: IR Port is disabled: false
08-05 14:14:23.195  6778  6794 D UEI.SmartControl: Starting file observer...
08-05 14:14:23.198  6778  6794 I UEI.SmartControl: Registering callback...
,08-05 14:14:23.201  6778  7186 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-05 14:14:23.202  6778  6793 I UEI.SmartControl: ------ IControl API: 19
08-05 14:14:23.205  6778  6793 I UEI.SmartControl: Registering Services Ready callback...
08-05 14:14:23.222  6778  7185 I UEI.SmartControl: Notify AllClients services are ready: 0
,08-05 14:14:23.222  6778  7185 D UEI.SmartControl: -----service ready thread exits
08-05 14:14:23.223  7079  7095 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-05 14:14:23.224  7079  7172 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-05 14:14:23.224  7079  7172 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-05 14:14:23.225  7079  7079 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-05 14:14:23.226  7079  7079 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-05 14:14:23.226  6778  6794 I UEI.SmartControl: ------ IControl API: 8
08-05 14:14:23.229  7079  7079 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-05 14:14:23.230  7079  7079 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-05 14:14:23.230  7079  7079 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-05 14:14:23.231  7079  7079 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-05 14:14:23.232  7079  7079 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-05 14:14:23.233  7079  7079 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-05 14:14:23.236  7079  7079 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
,08-05 14:14:23.239  7079  7079 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-05 14:14:23.239  7079  7079 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-05 14:14:23.240  7079  7079 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-05 14:14:23.241  7079  7079 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-05 14:14:23.242  7079  7079 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-05 14:14:23.243  7079  7079 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-05 14:14:23.244  7079  7079 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-05 14:14:23.245  7079  7079 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1470399263245]
08-05 14:14:23.249  7079  7079 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-05 14:14:23.251  1030  1733 I ActivityManager: Killing 6554:com.lge.email/u0a23 (adj 15): empty #17
,08-05 14:14:23.282  7079  7188 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-05 14:14:23.291  1030  1733 I ActivityManager: Killing 6527:com.android.contacts/u0a19 (adj 15): empty #18
,08-05 14:14:23.321  1030  1735 W libprocessgroup: failed to open /acct/uid_10023/pid_6554/cgroup.procs: No such file or directory
,08-05 14:14:23.329  1030  1917 W libprocessgroup: failed to open /acct/uid_10019/pid_6527/cgroup.procs: No such file or directory
08-05 14:14:23.330  7079  7079 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-05 14:14:23.330  7079  7079 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-05 14:14:23.331  7079  7079 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-05 14:14:23.331  7079  7079 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-05 14:14:23.332  7079  7079 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-05 14:14:23.333  7079  7079 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-05 14:14:23.334  7079  7079 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
,08-05 14:14:23.353  7079  7079 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-05 14:14:24.214  1030  1951 D WifiServiceImplEx: setWifiEnabled: true pid=6923, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-05 14:14:24.216  1030  1951 D WifiService: setWifiEnabled: true pid=6923, uid=10118
08-05 14:14:24.216  1030  1951 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-05 14:14:24.240  1030  1030 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-05 14:14:24.240  1030  1030 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-05 14:14:24.240  1030  1030 D Ulp_jni : JNI:system_update. Event-4
08-05 14:14:24.242  1030  1389 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-05 14:14:24.242  1030  1389 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-05 14:14:24.245  1030  1389 E WifiUtil: wfc_util_ffile_check_copy(): pid[1030] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-05 14:14:24.245  1030  1389 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-05 14:14:24.245  1030  1389 E WifiUtil: wfc_util_ffile_check_copy(): pid[1030] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-05 14:14:24.245  1030  1389 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-05 14:14:24.245  1030  1389 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-05 14:14:24.245  1030  1389 E WifiHW  : unknown target_country: EU , set to default
08-05 14:14:24.245  1030  1389 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-05 14:14:24.245  1030  1389 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-05 14:14:24.245  1030  1389 I WifiUtil: gEnableBmps=1
08-05 14:14:24.290  1030  1403 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-05 14:14:24.308  1030  1094 D Tethering: MasterInitialState.processMessage what=3
08-05 14:14:24.319  6923  6923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 14:14:24.324  6923  6923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 14:14:24.327  1030  1403 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-05 14:14:24.330  1030  1094 D Tethering: MasterInitialState.processMessage what=3
08-05 14:14:24.332  1030  1088 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-05 14:14:24.340  6923  6923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 14:14:24.343  6923  6923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 14:14:24.345  6408  6408 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-05 14:14:24.350  6408  7043 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-05 14:14:24.358  5875  5875 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-05 14:14:24.367  5875  5875 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-05 14:14:24.394  2185  2185 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-05 14:14:24.443  1030  1088 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-05 14:14:24.483  1030  1045 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7196 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-05 14:14:24.487  1030  1088 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 14:14:24.487  1030  1088 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:24.548  7196  7196 I AppUp4:AppBoxCP: onCreate
08-05 14:14:24.549  7196  7196 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,08-05 14:14:24.560  7196  7196 I AppUp4:DB:  setFingerPrint start
,08-05 14:14:24.560  7196  7196 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-05 14:14:24.569  7196  7196 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-05 14:14:24.569  7196  7196 I AppUp4:DB:  SDK version = 21
,08-05 14:14:24.569  7196  7196 I AppUp4:DB:  beforefinger == newfinger no write in DB
,08-05 14:14:24.571  7196  7196 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
,08-05 14:14:24.572  7196  7196 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-05 14:14:24.573  7196  7196 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,08-05 14:14:24.575  7196  7196 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-05 14:14:24.576  7196  7196 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-05 14:14:24.581  7196  7196 I AppUp4:CustModeStarterReceiver: onReceive
08-05 14:14:24.619  7196  7196 D LgDataFeature: LgDataFeature() Constructor: none
08-05 14:14:24.619  7196  7196 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-05 14:14:24.629  7196  7196 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@12a5f815
,08-05 14:14:24.629  7196  7196 D AppUp4:CustFacade: isCustomizationCompleted : false
08-05 14:14:24.629  7196  7196 D AppUp4:CustFacade: isPhone : true
08-05 14:14:24.630  7196  7196 D AppUp4:CustModeStarterReceiver: begin check event
,08-05 14:14:24.631  7196  7196 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-05 14:14:24.632  7196  7196 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
,08-05 14:14:24.633  7196  7228 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-05 14:14:24.633  7196  7228 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-05 14:14:24.634  7196  7228 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
,08-05 14:14:24.636  1030  1592 I ActivityManager: Killing 6578:com.android.gallery3d/u0a27 (adj 15): empty #17
08-05 14:14:24.695  1030  1992 W libprocessgroup: failed to open /acct/uid_10027/pid_6578/cgroup.procs: No such file or directory
,08-05 14:14:24.697  4803  4803 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,08-05 14:14:24.697  4803  4803 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-05 14:14:24.702  4803  4803 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 14:14:24.709  4803  4803 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 14:14:24.719  4803  7231 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-05 14:14:24.724  4803  7232 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-05 14:14:24.724  4803  7232 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-05 14:14:24.779  1030  1045 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7236 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-05 14:14:24.854  7236  7236 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-05 14:14:24.855  7236  7236 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-05 14:14:24.856  7236  7236 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-05 14:14:24.857  7236  7236 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-05 14:14:24.947  7236  7236 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-05 14:14:24.978  7236  7236 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-05 14:14:25.006  1030  1094 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-05 14:14:25.014  1030  1094 D Tethering: InitialState.processMessage what=4
08-05 14:14:25.014   308   895 D SoftapController: Softap fwReload - Ok
08-05 14:14:25.016  1030  1389 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (767ms)
08-05 14:14:25.016  1030  1094 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-05 14:14:25.018   308   895 D CommandListener: Setting iface cfg
08-05 14:14:25.018   308   895 D CommandListener: Trying to bring down wlan0
08-05 14:14:25.019   308   895 D CommandListener: Clearing all IP addresses on wlan0
08-05 14:14:25.021  1030  1389 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,08-05 14:14:25.025  1030  1389 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-05 14:14:25.025  1030  1389 E WifiStateMachine: useWiFiOffloading() : false
08-05 14:14:25.025  1030  1389 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-05 14:14:25.025  1030  1389 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-05 14:14:25.025  1030  1389 D WifiMonitor: connecting to supplicant
08-05 14:14:25.026  1030  1389 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
08-05 14:14:25.027  1030  1030 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-05 14:14:25.030  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 14:14:25.031  6923  6923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 14:14:25.032  6923  6923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 14:14:25.030  7263  7263 W wpa_supplicant: type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 14:14:25.030  7263  7263 W wpa_supplicant: type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 14:14:25.033  1938  1938 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
,08-05 14:14:25.030  7263  7263 W wpa_supplicant: type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 14:14:25.058  7263  7263 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-05 14:14:25.087  7236  7236 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-05 14:14:25.090  7263  7263 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-05 14:14:25.091  7263  7263 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-05 14:14:25.133  7236  7236 D LgDataFeature: LgDataFeature() Constructor: none
,08-05 14:14:25.133  7236  7236 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-05 14:14:25.171  7263  7263 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-05 14:14:25.230  7263  7263 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-05 14:14:25.234  7263  7263 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-05 14:14:25.239  7263  7263 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
,08-05 14:14:25.285  7236  7236 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-05 14:14:25.333  7117  7274 W FormManager: Network not available. Please check & try again.
,08-05 14:14:25.335  7236  7236 I HubEmail: JNI_OnLoad()
,08-05 14:14:25.335  7236  7236 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-05 14:14:25.335  7236  7236 I HubEmail: registerNatives()
08-05 14:14:25.335  7236  7236 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-05 14:14:25.335  7236  7236 I HubEmail: registerNativeMethods()
08-05 14:14:25.335  7236  7236 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-05 14:14:25.336  7236  7236 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
08-05 14:14:25.341  3317  3317 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-05 14:14:25.341  3317  3317 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-05 14:14:25.341  3317  3317 I LgeMiscReceiver: networkInfo.isConnected() = false
08-05 14:14:25.408  1030  1957 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7281 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-05 14:14:25.418  7236  7277 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 14:14:25.421  7117  7275 V FormManager: Network unavailable.
08-05 14:14:25.425  7117  7275 V FormManager: Network unavailable.
,08-05 14:14:25.438  1030  1917 I ActivityManager: Killing 6637:com.google.android.apps.docs/u0a61 (adj 15): empty #17
08-05 14:14:25.492  1030  1986 W libprocessgroup: failed to open /acct/uid_10061/pid_6637/cgroup.procs: No such file or directory
,08-05 14:14:25.584  7281  7281 D LgDataFeature: LgDataFeature() Constructor: none
08-05 14:14:25.584  7281  7281 D LgDataFeature: LgDataFeature() Constructor Done, null
08-05 14:14:25.588  7281  7281 D PhoneMonitor: Register our PhoneStateListener
,08-05 14:14:25.613  1030  1376 D PowerManagerServiceEx: acquireWakeLockInternal: lock=48785473, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1030
,08-05 14:14:25.614  1030  1376 V AlarmManager: ELAPSED_WAKEUP set : Alarm{219665bc type 2 when 351352 com.google.android.gms} when 351352
,08-05 14:14:25.624  7281  7281 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-05 14:14:25.626  7281  7281 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-05 14:14:25.656  7281  7281 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
08-05 14:14:25.657  7281  7281 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-05 14:14:25.662  7281  7281 D TelephonyAutoProfiling: [parse] Load xml
,08-05 14:14:25.667  7281  7281 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-05 14:14:25.667  7281  7281 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-05 14:14:25.667  7281  7281 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-05 14:14:25.667  7281  7281 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-05 14:14:25.667  7281  7281 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-05 14:14:25.668  7281  7281 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-05 14:14:25.668  7281  7281 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-05 14:14:25.668  7281  7281 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-05 14:14:25.668  7281  7281 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-05 14:14:25.668  7281  7281 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-05 14:14:25.668  7281  7281 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-05 14:14:25.668  7281  7281 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-05 14:14:25.668  7281  7281 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-05 14:14:25.668  7281  7281 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-05 14:14:25.668  7281  7281 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-05 14:14:25.668  7281  7281 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-05 14:14:25.668  7281  7281 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
08-05 14:14:25.674  7263  7263 E wpa_supplicant: USIM:  scard_init function
08-05 14:14:25.675  7263  7263 I wpa_supplicant: Trying to associate with SSID 'NG700'
,08-05 14:14:25.688  7281  7281 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,08-05 14:14:25.693  1030  1733 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7300 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-05 14:14:25.696  1030  1733 I ActivityManager: Killing 6693:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
08-05 14:14:25.742  1030  1934 W libprocessgroup: failed to open /acct/uid_10080/pid_6693/cgroup.procs: No such file or directory
,08-05 14:14:25.760  2572  2572 D [Concierge]Service: onStartCommand(). Type : 9
,08-05 14:14:25.788  7263  7263 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-05 14:14:25.794  1030  1094 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-05 14:14:25.796  7263  7263 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-05 14:14:25.796  7263  7263 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,08-05 14:14:25.992  1030  1957 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7323 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
08-05 14:14:25.995  1030  1957 I ActivityManager: Killing 6744:com.lge.eula/1000 (adj 15): empty #17
,08-05 14:14:26.029  1030  1389 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-05 14:14:26.029  1030  1389 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-05 14:14:26.030  1030  1389 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
,08-05 14:14:26.030  1030  1389 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-05 14:14:26.031  1030  1389 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-05 14:14:26.031  1030  1389 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-05 14:14:26.032  1030  1389 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-05 14:14:26.033  1030  1389 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-05 14:14:26.033  1030  1389 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-05 14:14:26.034  1030  1389 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-05 14:14:26.034  1030  1389 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-05 14:14:26.034  1030  1389 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-05 14:14:26.035  1030  1389 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-05 14:14:26.035  1030  1389 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-05 14:14:26.035  1030  1389 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-05 14:14:26.053  1030  2014 W libprocessgroup: failed to open /acct/uid_1000/pid_6744/cgroup.procs: No such file or directory
,08-05 14:14:26.058  1030  1389 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-05 14:14:26.058  1030  1389 E WifiStateMachine: useWiFiOffloading() : false
08-05 14:14:26.058  1030  1389 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-05 14:14:26.058  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 14:14:26.058  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 14:14:26.059  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 14:14:26.059  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 14:14:26.059  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-05 14:14:26.064  1030  1389 D WifiNative-wlan0: doBoolean: SET update_config 1
08-05 14:14:26.065  1030  1389 D WifiNative-wlan0: SET update_config 1: returned true
08-05 14:14:26.065  1030  1389 D WifiConfigStore: Loading config and enabling all networks 
08-05 14:14:26.065  1030  1389 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-05 14:14:26.066  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 14:14:26.067  1030  1030 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-05 14:14:26.067  1030  1389 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	[CURRENT]
,08-05 14:14:26.068  1030  1393 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-05 14:14:26.069  6923  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 14:14:26.069  6923  6923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 14:14:26.069  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 14:14:26.069  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 14:14:26.069  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 14:14:26.069  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 14:14:26.069  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 14:14:26.069  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 14:14:26.069  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 14:14:26.069  6923  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 14:14:26.070  6923  6923 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-05 14:14:26.072  1938  1938 D WfdService: Waiting for WifiP2p enabling
08-05 14:14:26.072  6923  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 14:14:26.072  6923  6923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 14:14:26.072  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 14:14:26.072  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 14:14:26.072  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 14:14:26.072  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 14:14:26.072  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 14:14:26.072  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 14:14:26.072  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 14:14:26.073  6923  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-05 14:14:26.073  6923  6923 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-05 14:14:26.076  1030  1389 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-05 14:14:26.087  1030  1389 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-05 14:14:26.087  1030  1389 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-05 14:14:26.088  1030  1389 D WifiStateMachine: enableVerboseLogging : level 2
08-05 14:14:26.088  1030  1389 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-05 14:14:26.089  1030  1389 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-05 14:14:26.089  1030  1389 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-05 14:14:26.089  1030  1389 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-05 14:14:26.089  1030  1389 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-05 14:14:26.090  1030  1389 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-05 14:14:26.090  1030  1389 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
,08-05 14:14:26.090  1030  1389 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-05 14:14:26.091  1030  1389 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-05 14:14:26.091  1030  1389 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-05 14:14:26.091  1030  1389 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-05 14:14:26.092  1030  1389 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-05 14:14:26.092  1030  1389 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-05 14:14:26.093  1030  1389 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-05 14:14:26.093  1030  1389 D WifiStateMachine: Setting OUI to DA-A1-19
08-05 14:14:26.093  1030  1389 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-05 14:14:26.094  1030  1389 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-05 14:14:26.094  1030  1389 D WifiNative-HAL: Setting external_sim to 1
08-05 14:14:26.094  1938  1938 D WfdsService: Supplicant Connection state is changed : true
08-05 14:14:26.094  1030  1389 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-05 14:14:26.094  1938  2301 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
,08-05 14:14:26.094  1938  2301 D WfdsService: Set the WFDS Monitor: true
08-05 14:14:26.094  1938  2301 D WfdsMonitor: WfdsMonitorThread create
08-05 14:14:26.094  1938  2301 D WfdsMonitor: WFDS Monitor is created and started
08-05 14:14:26.094  1938  2301 D WfdsService: WiFi: Supplicant connection re-established
08-05 14:14:26.094  1030  1389 D WifiNative-wlan0: SET external_sim 1: returned true
08-05 14:14:26.094  1030  1389 I WifiNative-HAL: startHal
08-05 14:14:26.095  1030  1389 D wifi    : setting scan oui 0xaf69dc20
08-05 14:14:26.095  1938  7343 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
,08-05 14:14:26.095  1030  1389 D WifiStateMachine: Setting OUI to DA-A1-19
08-05 14:14:26.095  1030  1389 I WifiNative-HAL: startHal
08-05 14:14:26.095  1030  1389 D wifi    : setting scan oui 0xaf69dc20
08-05 14:14:26.095  1938  7343 E CtrlSupplicant: Succeed to open control connection
08-05 14:14:26.095  1030  1389 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-05 14:14:26.096  1938  7343 E CtrlSupplicant: Succeed to open monitor connection
08-05 14:14:26.096  1938  7343 D WfdsMonitor: Supplicant connection established
08-05 14:14:26.097  1938  2301 D WfdsService: Connected to the supplicant for wfds
08-05 14:14:26.097  1030  1389 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-05 14:14:26.097  1030  1389 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-05 14:14:26.097  7263  7263 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-05 14:14:26.097  1030  1389 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-05 14:14:26.098  1030  1389 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-05 14:14:26.098  7263  7263 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-05 14:14:26.098  1030  1389 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-05 14:14:26.098  1030  1389 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-05 14:14:26.099  7263  7263 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-05 14:14:26.099  1030  1389 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-05 14:14:26.099  1030  1389 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-05 14:14:26.099  7263  7263 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-05 14:14:26.100  1030  1389 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-05 14:14:26.100  1030  1389 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-05 14:14:26.100  7263  7263 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-05 14:14:26.100  1030  1389 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-05 14:14:26.100  1030  1389 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-05 14:14:26.100  7263  7263 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-05 14:14:26.101  1030  1389 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-05 14:14:26.101  1030  1389 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-05 14:14:26.101  7263  7263 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-05 14:14:26.102  1030  1389 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-05 14:14:26.103  1030  1389 E WifiNative: : [351,842,318 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-05 14:14:26.103  1030  1389 D WifiNative-wlan0: doBoolean: RECONNECT
08-05 14:14:26.103  1030  1389 D WifiNative-wlan0: RECONNECT: returned true
08-05 14:14:26.103  1030  1389 D WifiNative-wlan0: doString: [STATUS]
,08-05 14:14:26.104  1030  7342 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-05 14:14:26.104  1030  7342 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-05 14:14:26.105  1030  1389 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-05 14:14:26.105  1030  1389 D WifiNative-wlan0: doBoolean: SET ps 1
08-05 14:14:26.105  1030  1389 D WifiNative-wlan0: SET ps 1: returned true
08-05 14:14:26.106  1030  1387 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-05 14:14:26.107  1030  1030 D WifiScanningService: SCAN_AVAILABLE : 3
08-05 14:14:26.107  1030  1030 D RttService: SCAN_AVAILABLE : 3
08-05 14:14:26.107  1030  1553 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-05 14:14:26.107  1030  1553 I WifiNative-HAL: startHal
08-05 14:14:26.107  1030  1553 D wifi    : getting scan capabilities on interface[1] = 0xaf69dc20
08-05 14:14:26.107  1030  1553 D wifi    : failed to get capabilities : -3
08-05 14:14:26.107  1030  1553 E WifiScanningService: could not get scan capabilities
08-05 14:14:26.107  1030  1554 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-05 14:14:26.108   308   895 D CommandListener: Setting iface cfg
08-05 14:14:26.108   308   895 D CommandListener: Trying to bring up p2p0
08-05 14:14:26.108  1030  1389 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-05 14:14:26.108  1030  1387 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-05 14:14:26.108  1030  1387 D LGWifiP2pService: P2pEnablingState
08-05 14:14:26.108  1030  1387 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-05 14:14:26.108  1030  1387 D LGWifiP2pService: P2p socket connection successful
08-05 14:14:26.108  1030  1387 D LGWifiP2pService: P2pEnabledState
08-05 14:14:26.108  1030  1389 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-05 14:14:26.109  1030  1389 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-05 14:14:26.109  1030  1389 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-05 14:14:26.110  1938  1938 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-05 14:14:26.110  1938  1938 D WfdsService: WifiP2pState is changed : true
08-05 14:14:26.110  1030  1389 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-05 14:14:26.110  1938  2301 D WfdsService: Receive the WFDS_ENABLE Method
08-05 14:14:26.110  1938  2301 D WfdsService: Set the WFDS Monitor: true
08-05 14:14:26.110  1938  2301 D WfdsService: Connected to the supplicant for wfds
08-05 14:14:26.110  1938  2301 D WfdsJNI : doCommand: WFDS_SET TRUE
08-05 14:14:26.110  1030  1389 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-05 14:14:26.110  7263  7263 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-05 14:14:26.111  1938  2301 D WfdsService: selectPreferredScanChannel [36]
08-05 14:14:26.111  1030  1389 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-05 14:14:26.111  1938  2301 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-05 14:14:26.111  1030  1389 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-05 14:14:26.111  7263  7263 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-05 14:14:26.112  1030  1389 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-05 14:14:26.112  1030  1389 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-05 14:14:26.112  1030  1389 E WifiStateMachine:  DriverStartedState what:132096, -100 0
08-05 14:14:26.112  1030  1389 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-05 14:14:26.113  7263  7263 E wpa_supplicant: disconnect_rssi_lvl: -100
08-05 14:14:26.113  1030  1387 D LGWifiP2pService: sending p2p connection changed broadcast
08-05 14:14:26.113  1030  1387 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-05 14:14:26.114  1030  1389 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-05 14:14:26.114  1030  1389 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-05 14:14:26.114  1030  1389 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-05 14:14:26.114  1030  1389 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-05 14:14:26.115  1938  1938 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
,08-05 14:14:26.116  7263  7263 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-05 14:14:26.116  1938  1938 D WfdsService: isConnected: false
08-05 14:14:26.116  7263  7263 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 14:14:26.117  7263  7263 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-05 14:14:26.117  7263  7263 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 14:14:26.118  7263  7263 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 14:14:26.119  1030  7342 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-05 14:14:26.119  1030  7342 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 14:14:26.119  1030  7342 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 14:14:26.119  1030  7342 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 14:14:26.119  1030  7342 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 14:14:26.119  1030  7342 E WifiMonitor: WifiMonitor:p2p0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 14:14:26.119  1030  7342 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 14:14:26.119  1030  7342 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 14:14:26.119  1030  7342 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 14:14:26.119  1030  7342 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 14:14:26.119  1030  7342 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 14:14:26.119  1030  7342 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 14:14:26.119  1938  7343 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 14:14:26.119  1938  7343 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 14:14:26.120  1030  1389 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-05 14:14:26.120  1030  1387 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-05 14:14:26.120  1030  1387 D WifiNative-p2p0: doBoolean: SET device_name G3
08-05 14:14:26.121  1030  1387 D WifiNative-p2p0: SET device_name G3: returned true
08-05 14:14:26.121  1030  1387 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-05 14:14:26.121  1030  1387 D LGWifiP2pService: before postfix = G3
08-05 14:14:26.121  1030  1387 D WifiServerServiceExt: postfix byte check : 2
08-05 14:14:26.121  1030  1387 D LGWifiP2pService: after postfix = G3
08-05 14:14:26.121  1030  1387 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-05 14:14:26.122  1030  1387 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-05 14:14:26.122  1030  1387 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-05 14:14:26.122  1030  1389 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-05 14:14:26.123  1030  1387 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-05 14:14:26.123  1030  1389 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-05 14:14:26.123  1030  1387 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-05 14:14:26.123  1030  1389 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-05 14:14:26.123  1030  1389 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-05 14:14:26.123  1030  1387 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-05 14:14:26.123  1030  1387 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-05 14:14:26.124  1030  1387 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-05 ,14:14:26.124  1030  1387 D WifiNative-HAL: p2pGetDeviceAddress
08-05 14:14:26.124  7263  7263 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-05 14:14:26.124  7263  7263 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-05 14:14:26.125  1030  1389 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-05 14:14:26.125  1030  1389 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-05 14:14:26.125  1030  7342 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-05 14:14:26.125  1030  7342 E WifiMonitor: WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-05 14:14:26.125  1030  7342 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-05 14:14:26.125  1030  1389 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-05 14:14:26.125  1030  1389 D WifiNative-wlan0: doBoolean: SCAN
08-05 14:14:26.126  7263  7263 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-05 14:14:26.125  1030  7342 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-05 14:14:26.126  1030  7342 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-05 14:14:26.126  1030  7342 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-05 14:14:26.126  1030  7342 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-05 14:14:26.126  1030  7342 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-05 14:14:26.126  1030  1389 D WifiNative-wlan0: SCAN: returned true
08-05 14:14:26.127  1030  1389 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=351867  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-05 14:14:26.128  1030  1387 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
,08-05 14:14:26.173  1030  1957 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7344 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-05 14:14:26.174  1030  1957 I ActivityManager: Killing 5646:com.lge.bnr/1000 (adj 15): empty #17
08-05 14:14:26.234  1030  1387 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-05 14:14:26.234  1030  1387 D WifiNative-p2p0: doBoolean: P2P_FLUSH
,08-05 14:14:26.236  1030  1389 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=351976  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-05 14:14:26.237  1030  1387 D WifiNative-p2p0: P2P_FLUSH: returned true
08-05 14:14:26.237  1030  1387 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-05 14:14:26.238  1030  1387 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-05 14:14:26.238  1030  1387 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-05 14:14:26.239  1030  1387 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-05 14:14:26.239  1030  1387 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-05 14:14:26.240  1938  1938 I WfdStateTracker: handleP2pThisDeviceChanged
08-05 14:14:26.240  1938  1938 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
,08-05 14:14:26.240  1938  1938 D WfdsService: Update P2p Interface State: 3
08-05 14:14:26.241  1030  1389 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-05 14:14:26.243  1030  1389 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-05 14:14:26.244  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 14:14:26.244  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 14:14:26.246  1030  1389 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-05 14:14:26.246  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 14:14:26.247  1030  1389 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-05 14:14:26.249  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 14:14:26.249  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 14:14:26.250  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,08-05 14:14:26.254  1030  1389 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-05 14:14:26.254  1030  1387 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-05 14:14:26.254  1030  1387 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-05 14:14:26.264  1030  2014 W libprocessgroup: failed to open /acct/uid_1000/pid_5646/cgroup.procs: No such file or directory
,08-05 14:14:26.266  1030  1387 D LGWifiP2pService: InactiveState
08-05 14:14:26.266  1030  1387 D LGWifiP2pService: InactiveState{ when=-145ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-05 14:14:26.267  1030  1387 D LGWifiP2pService: P2pEnabledState{ when=-145ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-05 14:14:26.267  1030  1387 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-05 14:14:26.268  7263  7263 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-05 14:14:26.268  1030  1389 E WifiStateMachine:  DisconnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-05 14:14:26.268  1030  1389 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
08-05 14:14:26.268  7263  7263 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 14:14:26.269  1938  7343 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-05 14:14:26.269  1030  1389 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-05 14:14:26.269  1030  7342 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-05 14:14:26.269  1030  7342 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 14:14:26.269  1030  1030 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 14:14:26.269  1030  1389 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-05 14:14:26.269  7263  7263 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-05 14:14:26.269  1030  1030 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-05 14:14:26.269  1030  7342 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 14:14:26.269  7263  7263 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 14:14:26.269  1030  7342 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 14:14:26.269  1030  7342 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 14:14:26.269  1030  1389 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
08-05 14:14:26.269  1030  7342 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 14:14:26.270  1030  7342 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 14:14:26.270  1030  7342 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 14:14:26.270  7263  7263 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 14:14:26.271  1030  1387 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-05 14:14:26.271  1938  7343 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 14:14:26.271  1938  7343 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 14:14:26.271  1030  1387 D LGWifiP2pService: InactiveState{ when=-75ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-05 14:14:26.271  1030  1387 D LGWifiP2pService: P2pEnabledState{ when=-75ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-05 14:14:26.271  1030  1387 D LGWifiP2pService: DefaultState{ when=-75ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-05 14:14:26.272  1030  7342 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 14:14:26.272  1030  1387 D LGWifiP2pService: InactiveState{ when=-33ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-05 14:14:26.272  1030  7342 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 14:14:26.272  1030  1387 D LGWifiP2pService: P2pEnabledState{ when=-33ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-05 14:14:26.272  1,030  7342 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 14:14:26.272  1030  7342 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 14:14:26.272  1030  1387 D LGWifiP2pService: InactiveState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-05 14:14:26.272  1030  1387 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-05 14:14:26.272  1030  1387 D LGWifiP2pService: DefaultState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-05 14:14:26.272  1030  1387 D LGWifiP2pService: InactiveState{ when=-6ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-05 14:14:26.272  1030  1387 D LGWifiP2pService: P2pEnabledState{ when=-6ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-05 14:14:26.272  1030  1387 D LGWifiP2pService: DefaultState{ when=-6ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-05 14:14:26.272  1030  1387 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-05 14:14:26.272  1030  1387 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-05 14:14:26.274  1030  1387 D LGWifiP2pService: DefaultState{ when=-2ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-05 14:14:26.274  1030  1387 D LGWifiP2pService: InactiveState{ when=-2ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-05 14:14:26.274  1938  2301 W WfdsService: DefaultState - msg [9441285] is not handled
08-05 14:14:26.274  1030  1387 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-05 14:14:26.275  1030  1387 D LGWifiP2pService: DefaultState{ when=-3ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-05 14:14:26.275  1030  1030 E WifiServerServiceExt: No p2p device connected
,08-05 14:14:26.302  7344  7344 I art     : Almond Protected OAT
,08-05 14:14:26.363  7344  7344 D WeatherApplication: removeAccount
,08-05 14:14:26.364  7344  7344 D WeatherApplication: Account.length = 0
08-05 14:14:26.364  7344  7344 E WeatherApplication: OPERATOR:OPEN
08-05 14:14:26.375  7344  7344 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:14:26
08-05 14:14:26.380  7344  7344 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,08-05 14:14:26.380  7344  7344 D Weather.Utils: 2 : All the weather widget is gone.
08-05 14:14:26.386  7344  7344 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,08-05 14:14:26.393  7344  7344 D WeatherAncestor: connectivity changed - connection : true
,08-05 14:14:26.397  7344  7344 D WeatherService: 2 : isServiceAlived():false forecastCache:null
,08-05 14:14:26.420  7344  7344 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-05 14:14:26.421  7344  7344 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
,08-05 14:14:26.421  7344  7344 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
,08-05 14:14:26.447  7344  7344 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-05 14:14:26.448  7344  7344 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:14:26
,08-05 14:14:26.527  1030  1733 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7362 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-05 14:14:26.528  1030  1733 I ActivityManager: Killing 6715:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,08-05 14:14:26.593  1030  1957 W libprocessgroup: failed to open /acct/uid_10097/pid_6715/cgroup.procs: No such file or directory
,08-05 14:14:26.717   278   434 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-05 14:14:26.717   278   434 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-05 14:14:26.717   278   434 W Vold    : Returning OperationFailed - no handler for errno 0
08-05 14:14:26.720  7362  7383 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,08-05 14:14:26.723   278   434 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-05 14:14:26.723   278   434 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-05 14:14:26.723   278   434 W Vold    : Returning OperationFailed - no handler for errno 0
08-05 14:14:26.725  7362  7383 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-05 14:14:26.747   278   434 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-05 14:14:26.747   278   434 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-05 14:14:26.747   278   434 W Vold    : Returning OperationFailed - no handler for errno 0
08-05 14:14:26.748  7362  7386 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,08-05 14:14:26.753   278   434 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-05 14:14:26.753   278   434 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-05 14:14:26.753   278   434 W Vold    : Returning OperationFailed - no handler for errno 0
08-05 14:14:26.754  7362  7386 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-05 14:14:27.019  7362  7362 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-05 14:14:27.033  7362  7362 I LibraryLoader: Loading: webviewchromium
,08-05 14:14:27.037  7362  7362 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 2780-2785)
,08-05 14:14:27.037  7362  7362 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-05 14:14:27.047  7362  7362 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1156eea6}
08-05 14:14:27.049  7362  7362 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-05 14:14:27.049  7362  7362 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,08-05 14:14:27.065  7362  7362 I BrowserStartupController: Initializing chromium process, renderers=0
,08-05 14:14:27.066  7362  7362 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-05 14:14:27.089  7362  7362 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-05 14:14:27.091  7362  7362 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-05 14:14:27.093  7362  7362 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-05 14:14:27.094   312  1399 V AudioPolicyService: registerClient() client 0xb14e7d00, uid 10093
,08-05 14:14:27.097  7362  7407 W AudioManagerAndroid: Requires BLUETOOTH permission
08-05 14:14:27.118  7362  7362 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-05 14:14:27.118  7362  7362 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-05 14:14:27.118  7362  7362 I Adreno-EGL: Build Date: 12/12/14 금
08-05 14:14:27.118  7362  7362 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-05 14:14:27.118  7362  7362 I Adreno-EGL: Remote Branch: 
08-05 14:14:27.118  7362  7362 I Adreno-EGL: Local Patches: 
08-05 14:14:27.118  7362  7362 I Adreno-EGL: Reconstruct Branch: 
,08-05 14:14:27.218  7362  7362 I NSApplication: Starting up...
,08-05 14:14:27.291  1030  1045 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7420 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-05 14:14:27.293  1030  1045 I ActivityManager: Killing 6599:com.android.vending/u0a44 (adj 15): empty #17
,08-05 14:14:27.353  1030  1733 D WifiServiceImplEx: setWifiEnabled: false pid=6923, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-05 14:14:27.353  1030  1733 D WifiService: setWifiEnabled: false pid=6923, uid=10118
08-05 14:14:27.354  1030  1733 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-05 14:14:27.355  1030  1917 W libprocessgroup: failed to open /acct/uid_10044/pid_6599/cgroup.procs: No such file or directory
,08-05 14:14:27.373  1030  1030 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-05 14:14:27.373  1030  1030 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-05 14:14:27.373  1030  1030 D Ulp_jni : JNI:system_update. Event-4
08-05 14:14:27.374  1030  1389 E WifiStateMachine:  DisconnectedState CMD_STOP_SUPPLICANT 0 0
08-05 14:14:27.375  1030  1389 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-05 14:14:27.375  1030  1389 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-05 14:14:27.375  1030  1389 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-05 14:14:27.382  1030  1387 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-05 14:14:27.382  1030  1030 D WifiScanningService: SCAN_AVAILABLE : 1
08-05 14:14:27.382  1030  1387 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-05 14:14:27.382  1030  1387 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@232e26bb
08-05 14:14:27.382  1030  1030 D RttService: SCAN_AVAILABLE : 1
08-05 14:14:27.382  1030  1553 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-05 14:14:27.382  1030  1387 D LGWifiP2pService: P2pDisablingState
08-05 14:14:27.382  1030  1554 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-05 14:14:27.382  1030  1387 D LGWifiP2pService: P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-05 14:14:27.382  1030  1387 D LGWifiP2pService: p2p socket connection lost
08-05 14:14:27.382  1030  1387 D LGWifiP2pService: P2pDisabledState
08-05 14:14:27.383  1030  1389 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
,08-05 14:14:27.384  1938  1938 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-05 14:14:27.384  1938  1938 D WfdsService: WifiP2pState is changed : false
08-05 14:14:27.384  1938  2301 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-05 14:14:27.384  1938  2301 D WfdsService: Set the WFDS Monitor: false
08-05 14:14:27.385  1938  2301 D WfdsMonitor: WFDS Monitor is stopped
08-05 14:14:27.385  1938  2301 D WfdsService: STATE : WfdsDisabledState - enter
08-05 14:14:27.385  1938  7343 D CtrlSupplicant: Received on exit socket, terminate
08-05 14:14:27.385  1938  7343 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-05 14:14:27.385  1938  7343 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-05 14:14:27.385  1938  2302 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-05 14:14:27.385  1938  7343 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-05 14:14:27.388   308   895 D CommandListener: Clearing all IP addresses on wlan0
08-05 14:14:27.388  1938  2301 W WfdsService: DefaultState - msg [9445378] is not handled
08-05 14:14:27.390  1030  1030 D WifiHS20: hidePasspointNotification off =false
08-05 14:14:27.391  7420  7420 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-05 14:14:27.391  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-05 14:14:27.392  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 14:14:27.392  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 14:14:27.392  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-05 14:14:27.392  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 14:14:27.393  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 14:14:27.395  1030  1389 D WifiNative-p2p0: doBoolean: TERMINATE
08-05 14:14:27.396  1030  1389 D WifiNative-p2p0: TERMINATE: returned true
08-05 14:14:27.396  1030  1389 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-05 14:14:27.396  1030  1389 E WifiStateMachine: useWiFiOffloading() : false
08-05 14:14:27.396  1030  1389 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-05 14:14:27.397  1030  1030 D WifiHS20: hidePasspointNotification off =false
,08-05 14:14:27.398  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 14:14:27.399  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 14:14:27.399  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-05 14:14:27.402  1938  1938 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-05 14:14:27.404  6923  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 14:14:27.404  6923  6923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 14:14:27.404  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 14:14:27.404  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 14:14:27.404  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 14:14:27.404  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 14:14:27.404  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 14:14:27.404  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 14:14:27.404  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 14:14:27.404  6923  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 14:14:27.404  6923  6923 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-05 14:14:27.405  1030  1030 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-05 14:14:27.405  1030  1030 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 14:14:27.405  1030  1030 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-05 14:14:27.405  6923  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-05 14:14:27.405  6923  6923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 14:14:27.405  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 14:14:27.405  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 14:14:27.405  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 14:14:27.405  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 14:14:27.405  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 14:14:27.405  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 14:14:27.405  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 14:14:27.405  6923  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 14:14:27.406  6923  6923 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-05 14:14:27.413  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-05 14:14:27.413  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 14:14:27.422  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-05 14:14:27.425  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 14:14:27.486  7263  7263 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-05 14:14:27.486  7263  7263 I wpa_supplicant: monitor socket send errors count : 1
08-05 14:14:27.486  7263  7263 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1938-4\x00 that cannot receive messages
08-05 14:14:27.488  1030  7342 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-05 14:14:27.488  1030  7342 D WifiMonitor: Dropping event because (p2p0) is stopped
08-05 14:14:27.733  6408  6408 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-05 14:14:27.734  6408  7043 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-05 14:14:27.755  2185  2185 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-05 14:14:27.763  7196  7196 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
,08-05 14:14:27.763  7196  7196 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-05 14:14:27.764  7196  7196 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-05 14:14:27.764  7196  7196 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-05 14:14:27.765  7196  7196 I AppUp4:CustModeStarterReceiver: onReceive
,08-05 14:14:27.770  7196  7196 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@12a5f815
08-05 14:14:27.770  7196  7196 D AppUp4:CustFacade: isCustomizationCompleted : false
08-05 14:14:27.770  7196  7196 D AppUp4:CustFacade: isPhone : true
08-05 14:14:27.771  7196  7196 D AppUp4:CustModeStarterReceiver: begin check event
08-05 14:14:27.772  7196  7196 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-05 14:14:27.776  4803  4803 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-05 14:14:27.777  4803  4803 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-05 14:14:27.778  4803  4803 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 14:14:27.781  4803  4803 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 14:14:27.789  7236  7236 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-05 14:14:27.789  4803  7455 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-05 14:14:27.792  4803  7457 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-05 14:14:27.792  4803  7457 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-05 14:14:27.811  7236  7459 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-05 14:14:27.814  7263  7263 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-05 14:14:27.815  1030  7342 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-05 14:14:27.815  1030  7342 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-05 14:14:27.815  1030  7342 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-05 14:14:27.815  1030  7342 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-05 14:14:27.815  7263  7263 W wpa_supplicant: USIM:  scard_deinit function
08-05 14:14:27.815  1030  7342 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
,08-05 14:14:27.816  1030  1389 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=353556
08-05 14:14:27.817  1030  1389 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=353557
08-05 14:14:27.817  1030  7342 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-05 14:14:27.818  1030  1389 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 32 0 rt=353558  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-05 14:14:27.818  1030  1389 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 32 0 rt=353558  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-05 14:14:27.819  1030  1094 D Tethering: InitialState.processMessage what=4
08-05 14:14:27.823  3317  3317 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-05 14:14:27.823  3317  3317 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-05 14:14:27.823  3317  3317 I LgeMiscReceiver: networkInfo.isConnected() = false
08-05 14:14:27.823  1030  1094 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-05 14:14:27.825  1030  1389 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-05 14:14:27.825  1030  1389 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-05 14:14:27.831  7281  7281 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-05 14:14:27.833  7281  7281 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-05 14:14:27.834  7117  7461 W FormManager: Network not available. Please check & try again.
08-05 14:14:27.845  7344  7344 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:14:27
,08-05 14:14:27.849  7117  7462 V FormManager: Network unavailable.
08-05 14:14:27.850  7344  7344 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-05 14:14:27.850  7344  7344 D Weather.Utils: 2 : All the weather widget is gone.
08-05 14:14:27.852  7117  7462 V FormManager: Network unavailable.
08-05 14:14:27.853  7344  7344 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-05 14:14:27.853  7344  7344 D WeatherAncestor: connectivity changed - connection : true
,08-05 14:14:27.853  7344  7344 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3875791b
08-05 14:14:27.858  7344  7344 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-05 14:14:27.858  7344  7344 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-05 14:14:27.858  7344  7344 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-05 14:14:27.859  7344  7344 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-05 14:14:27.859  7344  7344 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:14:27
,08-05 14:14:27.890  7002  7002 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-05 14:14:27.890  7002  7002 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-05 14:14:27.891  7002  7002 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-05 14:14:27.891  7002  7002 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-05 14:14:27.891  7002  7002 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-05 14:14:27.892  7002  7002 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-05 14:14:27.892  7002  7002 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-05 14:14:27.892  7002  7002 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-05 14:14:27.892  7002  7002 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-05 14:14:27.892  7002  7002 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-05 14:14:27.893  7002  7002 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-05 14:14:27.902  7045  7045 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-05 14:14:27.906  7002  7002 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-05 14:14:27.910  7117  7470 W FormManager: Network not available. Please check & try again.
08-05 14:14:27.914  7117  7471 V FormManager: Network unavailable.
08-05 14:14:27.914  7263  7263 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-05 14:14:27.915  1030  7342 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-05 14:14:27.915  1030  7342 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-TERMINATING 
08-05 14:14:27.915  1030  7342 D WifiMonitor: Disconnecting from the supplicant, no more events
08-05 14:14:27.916  1030  1389 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 33 0
08-05 14:14:27.918  7117  7471 V FormManager: Network unavailable.
08-05 14:14:27.920  7002  7002 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 14:14:27.941   308  7475 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-05 14:14:27.941  1030  1092 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-05 14:14:27.947  7045  7045 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-05 14:14:27.950  7002  7002 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-05 14:14:27.954  7117  7477 W FormManager: Network not available. Please check & try again.
,08-05 14:14:27.959  7002  7002 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 14:14:27.959  7117  7478 V FormManager: Network unavailable.
08-05 14:14:27.965  7117  7478 V FormManager: Network unavailable.
,08-05 14:14:27.978  4803  4803 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-05 14:14:27.978  4803  4803 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-05 14:14:27.980  4803  4803 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-05 14:14:27.982  4803  4803 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 14:14:27.988  4803  7479 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-05 14:14:27.990  4803  7480 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-05 14:14:27.990  4803  7480 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-05 14:14:28.054  1030  1951 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7481 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-05 14:14:28.060  1938  1938 D WfdsService: Supplicant Connection state is changed : false
08-05 14:14:28.060  1030  1389 D WifiOffDelayIfNotUsed: stopMonitoring
08-05 14:14:28.060  1030  1389 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-05 14:14:28.060  1030  1389 E WifiStateMachine: useWiFiOffloading() : false
08-05 14:14:28.060  1030  1389 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-05 14:14:28.061  1938  2301 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-05 14:14:28.061  1938  2301 D WfdsService: Set the WFDS Monitor: false
08-05 14:14:28.061  1938  2301 D WfdsMonitor: WFDS Monitor is stopped
08-05 14:14:28.063  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 14:14:28.064  1938  1938 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-05 14:14:28.067  6923  6923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 14:14:28.069  6923  6923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 14:14:28.070  1030  1030 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-05 14:14:28.070  1030  1393 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-05 14:14:28.071  1030  1393 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-05 14:14:28.072  2504  2504 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-05 14:14:28.165  6778  7187 D UEI.SmartControl: Internal timer expired: 2
08-05 14:14:28.165  6778  7187 D UEI.SmartControl: unbind internal service
,08-05 14:14:28.191  7481  7481 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-05 14:14:28.191  7481  7481 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-05 14:14:28.200  7481  7481 V [BNRBootReceiver]: Boot Receiver Return
08-05 14:14:28.200  7481  7481 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-05 14:14:28.208  6408  6408 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-05 14:14:28.224  7002  7002 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-05 14:14:28.224  6778  7181 D serial_port: close(fd = 24)
,08-05 14:14:28.229  6778  7181 I UEI.SmartControl: Serial port is closed.
08-05 14:14:28.235  7002  7002 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 14:14:28.248  7079  7079 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 14:14:28.248  7079  7079 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 14:14:28.249  7079  7079 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-05 14:14:28.256  6408  6408 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 14:14:28.265  7045  7045 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-05 14:14:28.265  7045  7045 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,08-05 14:14:28.265  7045  7045 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-05 14:14:28.274  7002  7002 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 14:14:28.285  7002  7002 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 14:14:28.297  7079  7079 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 14:14:28.298  7079  7079 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-05 14:14:28.301  7079  7079 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-05 14:14:28.308  6408  6408 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 14:14:28.317  7045  7045 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-05 14:14:28.317  7045  7045 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-05 14:14:28.318  7045  7045 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-05 14:14:28.324  7002  7002 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 14:14:28.335  7002  7002 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 14:14:28.342  7079  7079 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 14:14:28.342  7079  7079 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 14:14:28.344  7079  7079 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-05 14:14:28.354  7045  7045 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-05 14:14:28.361  7002  7002 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-05 14:14:28.367  7117  7500 W FormManager: Network not available. Please check & try again.
,08-05 14:14:28.373  7002  7002 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 14:14:28.380  7117  7501 V FormManager: Network unavailable.
08-05 14:14:28.392  7117  7501 V FormManager: Network unavailable.
,08-05 14:14:28.401  7079  7079 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
08-05 14:14:28.402  7079  7079 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:8919
08-05 14:14:28.406  1030  1030 D PowerManagerServiceEx: releaseWakeLockInternal: lock=48785473 [*alarm*], flags=0x0
,08-05 14:14:28.407  4803  4803 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-05 14:14:28.408  4803  4803 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-05 14:14:28.409  1030  1733 I ActivityManager: Killing 7024:com.lge.lifetracker/u0a37 (adj 15): empty #17
08-05 14:14:28.411  4803  4803 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 14:14:28.466  1030  1592 W libprocessgroup: failed to open /acct/uid_10037/pid_7024/cgroup.procs: No such file or directory
,08-05 14:14:28.466  4803  4803 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 14:14:28.477  4803  7503 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-05 14:14:28.479  4803  7504 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
,08-05 14:14:28.479  4803  7504 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-05 14:14:28.481  7045  7045 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-05 14:14:28.481  7045  7045 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-05 14:14:28.481  7045  7045 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-05 14:14:28.492  7002  7002 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-05 14:14:28.497  7117  7506 W FormManager: Network not available. Please check & try again.
08-05 14:14:28.500  7002  7002 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 14:14:28.511  7117  7507 V FormManager: Network unavailable.
,08-05 14:14:28.524  7117  7507 V FormManager: Network unavailable.
,08-05 14:14:30.376  1030  1934 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 14:14:30.377  1030  1934 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-05 14:14:30.406  1030  1030 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-05 14:14:30.407  1030  1030 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-05 14:14:30.407  1030  1030 D Ulp_jni : JNI:system_update. Event-4
08-05 14:14:30.408  1030  1094 D BluetoothManagerService: Message: 1
08-05 14:14:30.408  1030  1094 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-05 14:14:30.435  1030  1094 D BluetoothManagerService: Message: 20
08-05 14:14:30.435  1030  1094 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@cedf202:true
,08-05 14:14:30.439  7146  7146 D BluetoothAdapterState: make
08-05 14:14:30.444  7146  7146 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-05 14:14:30.444  7146  7146 I bluedroid-qcom: init
08-05 14:14:30.445  7146  7523 I BluetoothAdapterState: Entering OffState
08-05 14:14:30.446  7146  7146 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-05 14:14:30.446  7146  7146 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-05 14:14:30.446  7146  7146 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-05 14:14:30.446  7146  7146 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-05 14:14:30.446  7146  7146 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-05 14:14:30.448  7146  7146 I bluedroid-qcom: get_profile_interface socket
08-05 14:14:30.448  7146  7146 I bluedroid-qcom: get_profile_interface map_client
,08-05 14:14:30.453  7146  7527 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-05 14:14:30.450  7526  7526 W bdaddr_loader: type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 14:14:30.450  7526  7526 W bdaddr_loader: type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 14:14:30.465  7146  7527 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-05 14:14:30.472  1030  1030 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-05 14:14:30.472  1030  1030 D BluetoothManagerService: Stored Bluetooth name: G3
08-05 14:14:30.473  1030  1030 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-05 14:14:30.473  1030  1094 D BluetoothManagerService: Message: 40
08-05 14:14:30.473  1030  1094 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-05 14:14:30.474  7146  7162 I bluedroid-qcom: config_hci_snoop_log
08-05 14:14:30.476  7526  7526 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-05 14:14:30.477  7526  7526 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-05 14:14:30.477  7526  7526 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-05 14:14:30.477  1030  1094 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-05 14:14:30.477  1030  1094 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-05 14:14:30.479  7526  7526 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
,08-05 14:14:30.486  7526  7526 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-05 14:14:30.486  7526  7526 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-05 14:14:30.492  7146  7523 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,08-05 14:14:30.495  7146  7527 D BluetoothAdapterProperties: Name is: G3
08-05 14:14:30.495  7146  7523 D BluetoothAdapterProperties: Setting state to 11
08-05 14:14:30.495  7146  7523 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-05 14:14:30.496  1030  1094 D BluetoothManagerService: Message: 60
08-05 14:14:30.496  1030  1094 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-05 14:14:30.496  1030  1094 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-05 14:14:30.500  1938  1938 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-05 14:14:30.501  1600  1600 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-05 14:14:30.505  7002  7002 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
,08-05 14:14:30.509  6923  6923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 14:14:30.513  6923  6923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 14:14:30.522  7146  7146 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-05 14:14:30.523  7146  7146 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 14:14:30.523  7146  7146 V BluetoothPbapReceiver: ***********state = 11
,08-05 14:14:30.530  2185  2185 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-05 14:14:30.552  7146  7523 I LGBluetoothServiceJni: classInitNative: succeeds
,08-05 14:14:30.594  1030  2014 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7543 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-05 14:14:30.598  7146  7523 D BluetoothBondStateMachine: make
08-05 14:14:30.600  7146  7523 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3875791b
08-05 14:14:30.600  7146  7523 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-05 14:14:30.600  7146  7523 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3875791b
08-05 14:14:30.600  7146  7523 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-05 14:14:30.600  7146  7523 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-05 14:14:30.603  7146  7523 E BluetoothAdapterService: File transfer profiles supported!!
08-05 14:14:30.605  7146  7554 I BluetoothBondStateMachine: StableState(): Entering Off State
08-05 14:14:30.609  7146  7523 E BluetoothAdapterService: File transfer profiles supported!!
08-05 14:14:30.610  7146  7146 D HeadsetService: Received start request. Starting profile...
,08-05 14:14:30.610  7146  7146 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-05 14:14:30.611  7146  7146 D LGBluetoothHfpAdapter: Version 1.6
08-05 14:14:30.613  7146  7146 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-05 14:14:30.614  7146  7146 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-05 14:14:30.614  7146  7146 D HeadsetStateMachine: make
08-05 14:14:30.616  7146  7523 E BluetoothAdapterService: File transfer profiles supported!!
08-05 14:14:30.625  7146  7523 E BluetoothAdapterService: File transfer profiles supported!!
,08-05 14:14:30.640  7146  7523 E BluetoothAdapterService: File transfer profiles supported!!
08-05 14:14:30.641  7146  7146 D LgDataFeature: LgDataFeature() Constructor: none
08-05 14:14:30.641  7146  7146 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-05 14:14:30.750  1030  1733 I art     : Explicit concurrent mark sweep GC freed 70090(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 1.931ms total 114.495ms
,08-05 14:14:30.767  7146  7146 D HeadsetStateMachine: max_hf_connections = 1
08-05 14:14:30.767  7146  7146 I bluedroid-qcom: get_profile_interface handsfree
08-05 14:14:30.771  7146  7523 E BluetoothAdapterService: File transfer profiles supported!!
08-05 14:14:30.773  7146  7146 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-05 14:14:30.773   312  1400 V AudioPolicyService: registerClient() client 0xb558a600, uid 1002
08-05 14:14:30.773   312  2154 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-05 14:14:30.773   312  2154 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
,08-05 14:14:30.773   312  2154 V AudioPolicyManagerEx: getOutput() returns output 2
08-05 14:14:30.774  7146  7146 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-05 14:14:30.774   312  1399 V AudioFlinger: registerClient() client 0xb14337d8, pid 7146
08-05 14:14:30.774   312  1394 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-05 14:14:30.774   312  1394 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-05 14:14:30.779  7146  7146 V ToneGenerator: Create Track: 0xb4928080
08-05 14:14:30.779  1030  1951 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-05 14:14:30.779  1030  1951 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-05 14:14:30.779  7146  7146 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-05 14:14:30.779  7146  7146 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-05 14:14:30.779   312  1395 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-05 14:14:30.779   312  1395 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-05 14:14:30.779  1030  1045 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-05 14:14:30.779  1030  1045 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-05 14:14:30.779  7146  7163 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-05 14:14:30.779  7146  7163 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-05 14:14:30.779  7146  7163 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-05 14:14:30.779   312  2154 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-05 14:14:30.779  7146  7163 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-05 14:14:30.779   312  2154 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-05 14:14:30.779   312  2154 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-05 14:14:30.779   312  2154 V AudioPolicyManagerEx: getOutput() returns output 2
08-05 14:14:30.780   312  1400 I AudioFlinger: isAudioPlaybackHookOn() false
08-05 14:14:30.780  1600  1617 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-05 14:14:30.780  1600  1617 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-05 14:14:30.780  1600  1617 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-05 14:14:30.780  1600  1617 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-05 14:14:30.780  3317  3334 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-05 14:14:30.780  3317  3334 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-05 14:14:30.780  3317  3334 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-05 14:14:30.780  3317  3334 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-05 14:14:30.780   312  2154 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-05 14:14:30.780   312  2154 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-05 14:14:30.780   312  2154 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-05 14:14:30.780   312  2154 V AudioPolicyManagerEx: getOutput() returns output 2
08-05 14:14:30.780  1849  4460 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-05 14:14:30.780  1849  4460 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-05 14:14:30.780  1849  4460 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-05 14:14:30.780  1849  4460 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-05 14:14:30.781  7146  7146 V AudioSystem: getLatency() output 2, latency 50
08-05 14:14:30.781  7146  7146 V AudioSystem: getFrameCount() output 2, frameCount 960
08-,05 14:14:30.781  7146  7146 V AudioTrack: createTrack_l() output 2 afLatency 50
08-05 14:14:30.781   312  1400 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-05 14:14:30.781   312  1400 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-05 14:14:30.781   312  1400 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-05 14:14:30.781   312  1400 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-05 14:14:30.781   312  1400 V AudioFlinger: createTrack() lSessionId: 20
08-05 14:14:30.783  7146  7146 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-05 14:14:30.783   312  2154 V AudioFlinger: acquiring 20 from 7146, for 7146
08-05 14:14:30.783   312  2154 V AudioFlinger:  added new entry for 20
08-05 14:14:30.783  7146  7146 V ToneGenerator: ToneGenerator INIT OK, time: 356532
08-05 14:14:30.783  7146  7146 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3875791b
08-05 14:14:30.784  7146  7562 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-05 14:14:30.784  7146  7562 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-05 14:14:30.784  7146  7562 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-05 14:14:30.784  7146  7562 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
,08-05 14:14:30.785  7146  7146 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3875791b
08-05 14:14:30.785  7146  7523 E BluetoothAdapterService: File transfer profiles supported!!
08-05 14:14:30.786   312  1400 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7146
08-05 14:14:30.787   312  1400 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-05 14:14:30.787   312  1400 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-05 14:14:30.787   312  1400 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-05 14:14:30.787   312  1400 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-05 14:14:30.787   312  1400 V voice   : voice_set_parameters: exit with code(0)
08-05 14:14:30.787   312  1400 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-05 14:14:30.787   312  1400 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-05 14:14:30.787   312  1400 V msm8974_platform: platform_set_parameters: exit with code(0)
08-05 14:14:30.787   312  1400 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-05 14:14:30.787  7146  7146 D A2dpService: Received start request. Starting profile...
08-05 14:14:30.787   312  1400 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-05 14:14:30.787   312  1400 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-05 14:14:30.787  7146  7562 V ToneGenerator: ToneGenerator destructor
08-05 14:14:30.787  7146  7562 V ToneGenerator: stopTone
08-05 14:14:30.787  7146  7562 V ToneGenerator: Delete Track: 0xb4928080
08-05 14:14:30.788  7146  7562 V AudioTrack: ~AudioTrack, releasing session id from 7146 on behalf of 7146
08-05 14:14:30.788   312   312 V AudioFlinger: releasing 20 from 7146 for 7146
08-05 14:14:30.788   312   312 V AudioFlinger:  decremented refcount to 0
08-05 14:14:30.788   312   312 V AudioFlinger: purging stale effects
08-05 14:14:30.788   312   312 V AudioPolicyService: AudioCommandThread() adding release output 2
08-05 14:14:30.788   312   312 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-05 14:14:30.788   312  1216 V AudioPolicyService: AudioCommandThread() waking up
08-05 14:14:30.788   312  1216 V AudioPolicyService: AudioCommandThread() processing release output 2
08-05 14:14:30.788   312  1216 V AudioPolicyManager: releaseOutput() 2
08-05 14:14:30.788   312  1216 V AudioPolicyService: AudioCommandThread() going to sleep
08-05 14:14:30.788   312   312 V AudioFlinger: PlaybackThread::Track destructor
08-05 14:14:30.788   312   312 V AudioFlinger: removeClient_l() pid 7146, calling pid 312
08-05 14:14:30.788  7146  7146 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-05 14:14:30.789  1030  1735 W Process : Unable to open /proc/7565/status
08-05 14:14:30.789  7146  7146 V Avrcp   : make
08-05 14:14:30.790  7146  7146 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-05 14:14:30.790  7146  7146 I bluedroid-qcom: get_profile_interface avrcp
08-05 14:14:30.801  7146  7146 V AudioManager: registerRemoteController: size of Media player list: 0
,08-05 14:14:30.803  7146  7146 E AudioManager: No RCC entry present to update
08-05 14:14:30.803  7146  7146 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-05 14:14:30.806  7146  7146 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-05 14:14:30.807  7146  7146 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-05 14:14:30.807  7146  7146 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-05 14:14:30.810  7146  7146 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-05 14:14:30.812  7146  7523 V LGMDMManager: Create singleton instance
08-05 14:14:30.813  7146  7523 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-05 14:14:30.840  7543  7543 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-05 14:14:30.841  7543  7543 W LG Account v2.2: No ProfileInfo entries
08-05 14:14:30.841  7543  7543 I LG Account v2.2: isEnabled: false
08-05 14:14:30.841  7543  7543 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-05 14:14:30.841  7543  7543 I Feature : [Lifetracker]Country: EU
08-05 14:14:30.841  7543  7543 I Feature : [Lifetracker]Operator: OPEN
08-05 14:14:30.841  7543  7543 I Feature : [Lifetracker]Ranking support: false
08-05 14:14:30.841  7543  7543 I Feature : [Lifetracker]Comfort support: false
08-05 14:14:30.841  7543  7543 I Feature : [Lifetracker]Accessory: true
,08-05 14:14:30.842  7543  7543 I Feature : [Lifetracker]Health device: true
08-05 14:14:30.842  7543  7543 I Feature : [Lifetracker]Extra Pedometer: false
,08-05 14:14:30.842  7543  7543 I Feature : [Lifetracker]Blood glucose device: false
,08-05 14:14:30.842  7543  7543 I Feature : [Lifetracker]Device Number: 3
08-05 14:14:30.849  7002  7002 D BluetoothPermissionRequest: onReceive
08-05 14:14:30.852  7002  7002 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-05 14:14:30.883  1030  1653 V SIM_STK : Menu title from STK is T-Mobile
08-05 14:14:30.883  1030  1653 V SIM_STK : Menu title from STK is T-Mobile
,08-05 14:14:30.952  1030  1934 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-05 14:14:30.958  7146  7146 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-05 14:14:30.962  7146  7146 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-05 14:14:30.962  7146  7146 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-05 14:14:30.962  7146  7146 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-05 14:14:30.962  7146  7146 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-05 14:14:30.962  7146  7146 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-05 14:14:30.962  7146  7146 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-05 14:14:30.962  7146  7146 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-05 14:14:30.962  7146  7146 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-05 14:14:30.962  7146  7146 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-05 14:14:30.963  7146  7146 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-05 14:14:30.963  7146  7146 I BluetoothA2dpServiceJni: classInitNative
08-05 14:14:30.963  7146  7146 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-05 14:14:30.963  7146  7146 D A2dpStateMachine: make
08-05 14:14:30.966  7146  7146 I bluedroid-qcom: get_profile_interface a2dp
08-05 14:14:30.966  7146  7571 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-05 14:14:30.969  7146  7146 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
,08-05 14:14:30.969  7146  7146 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-05 14:14:30.970  7146  7146 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3875791b
08-05 14:14:30.970  7146  7570 D A2dpStateMachine: Enter Disconnected: -2
08-05 14:14:30.971  7146  7146 I BluetoothHidServiceJni: classInitNative: succeeds
08-05 14:14:30.975  7146  7146 D HidService: Received start request. Starting profile...
08-05 14:14:30.975  7146  7146 I bluedroid-qcom: get_profile_interface hidhost
08-05 14:14:30.975  7146  7146 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3875791b
08-05 14:14:30.977  7146  7146 I BluetoothHealthServiceJni: classInitNative: succeeds
08-05 14:14:30.981  7146  7146 D HealthService: Received start request. Starting profile...
08-05 14:14:30.986  7146  7146 I bluedroid-qcom: get_profile_interface health
,08-05 14:14:30.986  7146  7146 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-05 14:14:30.987  7146  7146 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3875791b
08-05 14:14:30.989  7146  7146 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-05 14:14:30.993  7146  7146 D PanService: Received start request. Starting profile...
08-05 14:14:30.993  7146  7146 D BluetoothPanServiceJni: initializeNative(L110): pan
08-05 14:14:30.993  7146  7146 I bluedroid-qcom: get_profile_interface pan
08-05 14:14:31.006  7146  7146 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
,08-05 14:14:31.006  7146  7146 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3875791b
08-05 14:14:31.007  7146  7146 D HeadsetStateMachine: Proxy object connected
08-05 14:14:31.009  7146  7146 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-05 14:14:31.009  7146  7146 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-05 14:14:31.012  7146  7146 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-05 14:14:31.018  7146  7146 D BtGatt.DebugUtils: handleDebugAction() action=null
08-05 14:14:31.019  7146  7146 D BtGatt.GattService: Received start request. Starting profile...
08-05 14:14:31.019  7146  7146 D BtGatt.GattService: start()
08-05 14:14:31.019  7146  7146 I bluedroid-qcom: get_profile_interface gatt
08-05 14:14:31.019  7146  7146 D BtGatt.AdvertiseManager: advertise manager created
,08-05 14:14:31.034  7146  7146 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3875791b
,08-05 14:14:31.038  7146  7562 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-05 14:14:31.039  7146  7562 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-05 14:14:31.040  7146  7562 D HeadsetStateMachine: Disconnected process message: 11, size: 0
,08-05 14:14:31.044  7146  7146 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-05 14:14:31.046  7146  7146 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3875791b
08-05 14:14:31.046  7146  7146 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-05 14:14:31.047  7146  7146 V BluetoothMapService: BluetoothMapBinder()
08-05 14:14:31.048  7146  7146 D BluetoothMapService: Received start request. Starting profile...
08-05 14:14:31.048  7146  7146 D BluetoothMapService: start()
08-05 14:14:31.052  7146  7146 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-05 14:14:31.052  7146  7146 D BluetoothMapEmailAppObserver: createReceiver()
08-05 14:14:31.054  7146  7146 D BluetoothMapEmailAppObserver: initObservers()
08-05 14:14:31.054  7146  7146 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
,08-05 14:14:31.075  7146  7146 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3875791b
,08-05 14:14:31.083  7146  7146 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-05 14:14:31.088  7146  7146 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-05 14:14:31.093  7146  7146 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-05 14:14:31.093  7146  7146 V PanService: [BTUI] SIM Extra State :ABSENT
08-05 14:14:31.097  7146  7146 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-05 14:14:31.101  7146  7146 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-05 14:14:31.101  7146  7146 V BluetoothMapService: Handler(): got msg=1
08-05 14:14:31.103  7146  7523 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-05 14:14:31.103  7146  7523 I bluedroid-qcom: enable
,08-05 14:14:31.103  7146  7581 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-05 14:14:31.103  7146  7523 I bt_hci_bdroid: init
08-05 14:14:31.105  7146  7146 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-05 14:14:31.107  7146  7523 I bt_vendor: bt-vendor : init
08-05 14:14:31.107  7146  7523 I bt_vendor: bt-vendor : get_bt_soc_type
08-05 14:14:31.107  7146  7523 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-05 14:14:31.107  7146  7523 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-05 14:14:31.107  7146  7523 D bt_userial_mct: userial_init
08-05 14:14:31.107  7146  7581 I bt-btu  : btu_task pending for preload complete event
08-05 14:14:31.108  7146  7523 D bt_hci_bdroid: set_power 1
,08-05 14:14:31.108  7146  7523 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-05 14:14:31.108  7146  7523 I bt_vendor: Starting hciattach daemon
08-05 14:14:31.110  7584  7584 W sh      : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-05 14:14:31.110  7584  7584 W sh      : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 14:14:31.108  7146  7523 I bt_vendor: try to set true
08-05 14:14:31.108  7146  7146 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-05 14:14:31.109  7146  7146 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-05 14:14:31.109  7146  7146 V BluetoothSapReceiver: SapReceiver onReceive 
08-05 14:14:31.109  7146  7146 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 14:14:31.109  7146  7146 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
,08-05 14:14:31.147  7585  7585 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-05 14:14:31.266  7591  7591 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-05 14:14:31.280  7592  7592 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-05 14:14:31.298  1030  1403 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
,08-05 14:14:31.310  7594  7594 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-05 14:14:31.332  7595  7595 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-05 14:14:31.346  7596  7596 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-05 14:14:31.372  7597  7597 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-05 14:14:31.394  7599  7599 I libmdmdetect: ESOC framework not supported
08-05 14:14:31.395  7599  7599 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-05 14:14:31.404  7599  7599 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,08-05 14:14:31.404  7599  7599 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-05 14:14:31.404  7599  7599 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-05 14:14:31.404  7599  7599 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-05 14:14:31.404  7599  7599 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-05 14:14:31.404  7599  7599 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-05 14:14:31.404  7599  7599 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-05 14:14:31.444  7599  7600 E QC-QMI  : qmi_client [7599] 14: failed to locate client data
,08-05 14:14:31.445   463   463 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-05 14:14:31.445   463   463 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
08-05 14:14:31.504  7601  7601 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-05 14:14:31.519  7602  7602 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-05 14:14:31.562  7146  7523 I bt_vendor: bluetooth satus is on
,08-05 14:14:31.562  7146  7523 D bt_hci_bdroid: preload
08-05 14:14:31.562  7146  7583 D bt_userial_mct: userial_open(port:0)
08-05 14:14:31.562  7146  7583 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-05 14:14:31.567  7146  7583 I bt_vendor: Done intiailizing UART
08-05 14:14:31.571  7146  7583 I bt_vendor: Done intiailizing UART
08-05 14:14:31.571  7146  7583 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-05 14:14:31.572  7146  7583 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-05 14:14:31.572  7146  7607 D bt_userial_mct: Entering userial_read_thread()
08-05 14:14:31.572  7146  7581 I bt-btu  : btu_task received preload complete event
08-05 14:14:31.573  7146  7581 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-05 14:14:31.573  7146  7581 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
,08-05 14:14:31.575  7146  7581 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-05 14:14:31.580  7146  7581 I         : BTE_InitTraceLevels -- TRC_HCI
08-05 14:14:31.580  7146  7581 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-05 14:14:31.580  7146  7581 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-05 14:14:31.580  7146  7581 I         : BTE_InitTraceLevels -- TRC_AVDT
08-05 14:14:31.580  7146  7581 I         : BTE_InitTraceLevels -- TRC_AVRC
08-05 14:14:31.580  7146  7581 I         : BTE_InitTraceLevels -- TRC_A2D
08-05 14:14:31.580  7146  7581 I         : BTE_InitTraceLevels -- TRC_BNEP
08-05 14:14:31.580  7146  7581 I         : BTE_InitTraceLevels -- TRC_BTM
08-05 14:14:31.580  7146  7581 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-05 14:14:31.580  7146  7581 I         : BTE_InitTraceLevels -- TRC_GAP
08-05 14:14:31.580  7146  7581 I         : BTE_InitTraceLevels -- TRC_PAN
08-05 14:14:31.580  7146  7581 I         : BTE_InitTraceLevels -- TRC_SDP
08-05 14:14:31.580  7146  7581 I         : BTE_InitTraceLevels -- TRC_GATT
08-05 14:14:31.580  7146  7581 I         : BTE_InitTraceLevels -- TRC_SMP
08-05 14:14:31.580  7146  7581 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-05 14:14:31.580  7146  7581 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-05 14:14:31.649  7146  7581 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled,
08-05 14:14:31.649  7146  7581 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01e2061 
08-05 14:14:31.649  7146  7581 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01e2061 
,08-05 14:14:31.667  7146  7527 E bt-btif : Calling BTA_HhEnable
08-05 14:14:31.667  7146  7527 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-05 14:14:31.667  7146  7527 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-05 14:14:31.671  7146  7581 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-05 14:14:31.671  7146  7581 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-05 14:14:31.671  7146  7581 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-05 14:14:31.671  7146  7581 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-05 14:14:31.673  1030  1030 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-05 14:14:31.673  1030  1030 D BluetoothManagerService: Stored Bluetooth name: G3
08-05 14:14:31.671  7146  7581 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-05 14:14:31.674  7146  7527 D BluetoothAdapterProperties: Name is: G3
08-05 14:14:31.677  7146  7527 D BluetoothAdapterProperties: Scan Mode:20
08-05 14:14:31.678  7146  7527 D BluetoothAdapterProperties: Discoverable Timeout:120
08-05 14:14:31.678  7146  7527 D bt_hci_bdroid: postload
08-05 14:14:31.678  7146  7583 D bt_hci_bdroid: Used up Tx Cmd credits
08-05 14:14:31.680  7146  7581 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-05 14:14:31.682  7146  7527 D bte_conf: Device ID record 1 : primary
08-05 14:14:31.682  7146  7527 D bte_conf:   vendorId            = 00c4
08-05 14:14:31.682  7146  7527 D bte_conf:   vendorIdSource      = 0001
08-05 14:14:31.682  7146  7527 D bte_conf:   product             = 13a1
08-05 14:14:31.682  7146  7527 D bte_conf:   version             = 1000
08-05 14:14:31.682  7146  7527 D bte_conf:   clientExecutableURL = 
08-05 14:14:31.682  7146  7527 D bte_conf:   serviceDescription  = 
08-05 14:14:31.682  7146  7527 D bte_conf:   documentationURL    = 
08-05 14:14:31.682  7146  7527 D bte_conf: bte_load_did_conf no section named DID2.
,08-05 14:14:31.686  7146  7581 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-05 14:14:31.686  7146  7581 W bt-smp  : Plain text(LSB ~ MSB) = 7e 0c 54 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-05 14:14:31.686  7146  7581 W bt-smp  : Encrypted text(LSB ~ MSB) = 8a c9 9e e7 5f a4 71 e1 0f 3a 4f 22 88 80 63 9c 
08-05 14:14:31.686  7146  7583 D bt_hci_bdroid: Used up Tx Cmd credits
08-05 14:14:31.686  7146  7581 W bt-btm  : Stopping oneshot timer
08-05 14:14:31.689  7146  7583 D bt_hci_bdroid: Used up Tx Cmd credits
08-05 14:14:31.689  7146  7583 D bt_hci_bdroid: Used up Tx Cmd credits
08-05 14:14:31.689  7146  7523 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-05 14:14:31.690  7146  7523 D BluetoothAdapterProperties: ScanMode =  20
08-05 14:14:31.690  7146  7523 D BluetoothAdapterProperties: State =  11
08-05 14:14:31.690  7146  7523 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-05 14:14:31.690  7146  7523 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-05 14:14:31.690  7146  7523 D BluetoothAdapterProperties: Setting state to 12
08-05 14:14:31.691  7146  7523 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-05 14:14:31.690  7612  7612 W sh      : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 14:14:31.695  1030  1094 D BluetoothManagerService: Message: 60
08-05 14:14:31.695  1030  1094 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-05 14:14:31.695  1030  1094 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
,08-05 14:14:31.690  7612  7612 W sh      : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 14:14:31.702  7146  7583 D bt_hci_bdroid: Used up Tx Cmd credits
08-05 14:14:31.702  7146  7607 E bt_mct  : hci lib postload completed
08-05 14:14:31.703  7146  7527 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-05 14:14:31.703  7146  7527 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-05 14:14:31.731  6923  6923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 14:14:31.731  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 14:14:31.731  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 14:14:31.731  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 14:14:31.731  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 14:14:31.731  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 14:14:31.731  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 14:14:31.731  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-05 14:14:31.735  7146  7581 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-05 14:14:31.735  7146  7581 W bt-smp  : Plain text(LSB ~ MSB) = 07 d7 73 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-05 14:14:31.735  7146  7581 W bt-smp  : Encrypted text(LSB ~ MSB) = c0 f3 80 b2 e6 d7 5e b7 86 72 a1 d7 56 cc 47 46 
08-05 14:14:31.735  7146  7581 W bt-btm  : Stopping oneshot timer
08-05 14:14:31.741  7146  7527 D BluetoothAdapterProperties: Discoverable Timeout:120
08-05 14:14:31.743  7146  7527 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-05 14:14:31.744  7146  7523 I BluetoothAdapterState: Entering On State
,08-05 14:14:31.752  6923  6923 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-05 14:14:31.762  6923  6923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 14:14:31.762  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 14:14:31.762  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 14:14:31.762  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 14:14:31.762  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 14:14:31.762  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 14:14:31.762  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 14:14:31.762  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-05 14:14:31.765  7146  7581 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-05 14:14:31.765  7146  7581 W bt-smp  : Plain text(LSB ~ MSB) = 9b 27 71 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-05 14:14:31.765  7146  7581 W bt-smp  : Encrypted text(LSB ~ MSB) = 80 73 9a 37 33 f0 8a a6 38 75 87 29 51 c3 d6 b0 
08-05 14:14:31.765  7146  7581 W bt-btm  : Stopping oneshot timer
08-05 14:14:31.773  6923  6923 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-05 14:14:31.778  7146  7581 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-05 14:14:31.778  7146  7581 W bt-smp  : Plain text(LSB ~ MSB) = dd 40 5c 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-05 14:14:31.778  7146  7581 W bt-smp  : Encrypted text(LSB ~ MSB) = 54 bb 90 d8 6e 4e dd 86 8c 2b 01 8b 04 58 dd 69 
,08-05 14:14:31.782  7146  7581 W bt-btm  : Stopping oneshot timer
08-05 14:14:31.794  7146  7523 D LGBluetoothServiceAdapter: [BTUI] OnState
08-05 14:14:31.794  7146  7523 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-05 14:14:31.794  7146  7523 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,08-05 14:14:31.800  7146  7523 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-05 14:14:31.800  7146  7523 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-05 14:14:31.801  7002  7022 D BluetoothMap: onBluetoothStateChange: up=true
08-05 14:14:31.810  7002  7064 D BluetoothPbap: onBluetoothStateChange: up=true
,08-05 14:14:31.815  7626  7626 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-05 14:14:31.818  7146  7581 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-05 14:14:31.818  7146  7581 W bt-smp  : Plain text(LSB ~ MSB) = 3a 7a 4a 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-05 14:14:31.818  7146  7581 W bt-smp  : Encrypted text(LSB ~ MSB) = 1f b8 00 8d 68 48 9c 3f b0 5a b1 db e5 36 1a 86 
08-05 14:14:31.818  1849  2673 D BluetoothHeadset: onBluetoothStateChange: up=true
08-05 14:14:31.818  7146  7581 W bt-btm  : Stopping oneshot timer
08-05 14:14:31.821  1030  1094 D BluetoothHeadset: onBluetoothStateChange: up=true
08-05 14:14:31.822  7002  7023 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-05 14:14:31.823  1030  1030 D BluetoothHeadset: Proxy object connected
,08-05 14:14:31.823  1849  1849 D BluetoothHeadset: Proxy object connected
08-05 14:14:31.825  7002  7002 D BluetoothMap: Proxy object connected
08-05 14:14:31.825  7002  7002 D MapProfile: Bluetooth service connected
08-05 14:14:31.825  7002  7002 D BluetoothMap: getConnectedDevices()
08-05 14:14:31.826  7002  7022 D BluetoothPan: onBluetoothStateChange on: true
08-05 14:14:31.826  7002  7022 D BluetoothPan: onBluetoothStateChange call bindService
,08-05 14:14:31.828  1030  1094 D BluetoothA2dp: onBluetoothStateChange: up=true
08-05 14:14:31.830  7146  7162 V BluetoothMapService: getConnectedDevices()
08-05 14:14:31.831  1030  1030 D BluetoothA2dp: Proxy object connected
08-05 14:14:31.832  1849  1865 D BluetoothHeadset: onBluetoothStateChange: up=true
08-05 14:14:31.833  7002  7002 D BluetoothInputDevice: Proxy object connected
08-05 14:14:31.833  7002  7002 D HidProfile: Bluetooth service connected
08-05 14:14:31.835  1849  1849 D BluetoothHeadset: Proxy object connected
08-05 14:14:31.835  1849  2673 D BluetoothHeadset: onBluetoothStateChange: up=true
08-05 14:14:31.837  1849  1849 D BluetoothHeadset: Proxy object connected
08-05 14:14:31.837  1030  1094 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-05 14:14:31.837  1030  1094 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-05 14:14:31.838  1030  1030 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,08-05 14:14:31.843  1600  1600 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-05 14:14:31.845  1938  1938 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-05 14:14:31.845  1938  2121 D LGBluetoothAPIService: Message: 1
08-05 14:14:31.845  1938  2121 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-05 14:14:31.846  1030  1094 D BluetoothManagerService: Message: 40
08-05 14:14:31.846  1030  1094 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-05 14:14:31.851  6923  6923 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
08-05 14:14:31.854  6923  6923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 14:14:31.857  7002  7002 D BluetoothPan: BluetoothPAN Proxy object connected
08-05 14:14:31.857  6923  6923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 14:14:31.858  7146  7146 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-05 14:14:31.858  7146  7146 D BluetoothMapService: STATE_ON
08-05 14:14:31.859  7002  7002 D PanProfile: Bluetooth service connected
08-05 14:14:31.859  7146  7146 D LGBluetoothAPIServer: [BTUI] onCreate()
08-05 14:14:31.859  7146  7146 D LGBluetoothAPIServer: [BTUI] onBind()
08-05 14:14:31.860  1938  1938 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-05 14:14:31.860  1938  2121 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-05 14:14:31.861  1938  2121 D LGBluetoothAPIService: Message: 100
08-05 14:14:31.861  1938  2121 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-05 14:14:31.864  7002  7002 D LocalBluetoothProfileManager: Adding local A2DP profile
08-05 14:14:31.867  1030  1094 D BluetoothManagerService: Message: 30
,08-05 14:14:31.869  7002  7002 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-05 14:14:31.871  7362  7385 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
08-05 14:14:31.872  1030  1094 D BluetoothManagerService: Message: 30
08-05 14:14:31.874  7146  7146 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3875791b
08-05 14:14:31.874  7146  7146 V BluetoothPbapService: Pbap Service onCreate
08-05 14:14:31.874  7146  7146 V BluetoothPbapService: Starting PBAP service
08-05 14:14:31.875  7146  7146 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-05 14:14:31.875  7146  7146 V BluetoothMapService: Handler(): got msg=1
08-05 14:14:31.875  7146  7146 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-05 14:14:31.875  7146  7146 V BluetoothPbapService: Pbap Service onBind
08-05 14:14:31.876  7146  7146 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-05 14:14:31.876  7146  7146 V BluetoothPbapService: state: 12
08-05 14:14:31.876  7146  7146 V BluetoothPbapService: Handler(): got msg=1
08-05 14:14:31.876  7002  7002 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-05 14:14:31.877  7146  7146 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-05 14:14:31.877  7146  7638 D BluetoothMapMasInstance: MAS initSocket()
08-05 14:14:31.878  7146  7638 D BluetoothMapMasInstance:   masId = 00
08-05 14:14:31.878  7146  7638 D BluetoothMapMasInstance:   msgTypes = 0e
08-05 14:14:31.878  7146  7638 D BluetoothMapMasInstance:   masName = SMS/MMS
08-05 14:14:31.878  7146  7638 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-05 14:14:31.878  7002  7002 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-05 14:14:31.879  1030  1986 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 14:14:31.880  7002  7002 D BluetoothA2dp: Proxy object connected
08-05 14:14:31.881  7146  7638 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-05 14:14:31.882  7146  7639 V BluetoothPbapService: Pbap Service initSocket
08-05 14:14:31.883  7146  7146 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-05 14:14:31.883  7146  7638 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
,08-05 14:14:31.883  7146  7146 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 14:14:31.883  7146  7146 V BluetoothPbapReceiver: ***********state = 12
,08-05 14:14:31.883  7146  7638 V BluetoothMapMasInstance: Succeed to create listening socket 
08-05 14:14:31.883  7146  7638 D BluetoothMapMasInstance: Accepting socket connection...
08-05 14:14:31.883  1030  1653 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 14:14:31.884  7146  7527 D BluetoothAdapterProperties: Scan Mode:21
08-05 14:14:31.884  7146  7527 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-05 14:14:31.885  7146  7639 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-05 14:14:31.886  7002  7002 D A2dpProfile: Bluetooth service connected
08-05 14:14:31.886  6923  6923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 14:14:31.890  6923  6923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 14:14:31.890  7146  7639 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-05 14:14:31.890  7146  7639 V BluetoothPbapService: Succeed to create listening socket 
08-05 14:14:31.890  7146  7639 V BluetoothPbapService: Accepting socket connection...
08-05 14:14:31.893  2185  2185 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-05 14:14:31.893  2185  2185 D c       : Getting all permits...
08-05 14:14:31.893  2185  2185 D a       : Opening database...
08-05 14:14:31.894  7002  7002 D BluetoothHeadset: Proxy object connected
08-05 14:14:31.895  7002  7002 D HeadsetProfile: Bluetooth service connected
08-05 14:14:31.896  2185  2185 D a       : Opening database auth.proximity.permit_store...
,08-05 14:14:31.897  7002  7002 D BluetoothPbap: Proxy object connected
08-05 14:14:31.897  2185  2185 D a       : Closing database...
08-05 14:14:31.897  7002  7002 D PbapServerProfile: Bluetooth service connected
08-05 14:14:31.904  7002  7002 D DockEventReceiver: finishStartingService: stopping service
08-05 14:14:31.909  7002  7002 D BluetoothPermissionRequest: onReceive
,08-05 14:14:31.911  7002  7002 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-05 14:14:31.912  7002  7002 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-05 14:14:31.916  7146  7146 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-05 14:14:31.917  7146  7146 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-05 14:14:31.927  7146  7146 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-05 14:14:31.955  7146  7146 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-05 14:14:31.956  7146  7146 V BtOppService: onCreate
,08-05 14:14:31.960  7146  7146 V BluetoothOppNotification: send message
08-05 14:14:31.964  7146  7146 V BtOppService: Starting RfcommListener
08-05 14:14:31.970  7146  7146 D BluetoothOppPreference: Dumping Names:  
,08-05 14:14:31.970  7146  7146 D BluetoothOppPreference: {}
08-05 14:14:31.970  7146  7146 D BluetoothOppPreference: Dumping Channels:  
08-05 14:14:31.970  7146  7146 D BluetoothOppPreference: {}
08-05 14:14:31.971  7146  7146 V BtOppService: onStartCommand
08-05 14:14:31.977  7146  7647 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-05 14:14:31.977  7146  7146 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-05 14:14:31.978  7146  7146 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-05 14:14:31.981  7146  7146 V BluetoothOppNotification: new notify threadi!
,08-05 14:14:31.982  7146  7146 V BluetoothOppNotification: send delay message
08-05 14:14:31.983  7146  7146 V BtOppService: start RfcommListener
,08-05 14:14:31.987  7146  7146 V BtOppService: RfcommListener started
08-05 14:14:31.992  7146  7644 V BtOppService: Deleted complete outbound shares, number =  0
08-05 14:14:31.994  7146  7649 V BtOppRfcommListener: Starting RFCOMM listener....
08-05 14:14:31.994  7146  7648 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-05 14:14:31.995  1030  1951 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 14:14:31.996  7146  7644 V BtOppService: Deleted complete inbound failed shares, number = 0
08-05 14:14:31.997  7146  7644 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-05 14:14:31.997  7146  7649 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-05 14:14:31.997  7146  7647 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-05 14:14:31.999  7146  7649 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
08-05 14:14:32.000  7146  7649 V BtOppRfcommListener: Started RFCOMM listener....
08-05 14:14:32.000  7146  7649 I BtOppRfcommListener: Accept thread started.
08-05 14:14:32.000  7146  7649 V BtOppRfcommListener: Accepting connection...
,08-05 14:14:32.003  7146  7146 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3875791b
08-05 14:14:32.003  7146  7146 V BluetoothFtpService: Ftp Service onCreate
08-05 14:14:32.003  7146  7146 I BluetoothFtpService: Ftp Service onCreate
08-05 14:14:32.003  7146  7146 V BluetoothFtpService: Ftp Service onStartCommand
08-05 14:14:32.003  7146  7146 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-05 14:14:32.004  7146  7146 V BluetoothFtpService: Starting Listening on sockets
08-05 14:14:32.004  7146  7146 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-05 14:14:32.004  7146  7146 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-05 14:14:32.004  7146  7146 V BluetoothSapReceiver: SapReceiver onReceive 
08-05 14:14:32.004  7146  7146 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 14:14:32.004  7146  7146 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-05 14:14:32.004  7146  7146 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-05 14:14:32.006  7146  7648 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@d32ac1d on behalf of 
08-05 14:14:32.006  7146  7644 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@a724e92 on behalf of 
08-05 14:14:32.008  7146  7146 V BtOppService: ContentObserver received notification
08-05 14:14:32.008  7146  7146 V BtOppService: ContentObserver received notification
08-05 14:14:32.008  7146  7146 V BluetoothFtpService: Handler(): got msg=1
08-05 14:14:32.009  7146  7146 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-05 14:14:32.009  7146  7146 V BluetoothFtpService: Ftp Service initSocket
08-05 14:14:32.011  1030  1915 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 14:14:32.013  7146  7146 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-05 14:14:32.014  7146  7648 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-05 14:14:32.017  7146  7647 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1d882063 on behalf of 
,08-05 14:14:32.018  7146  7146 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=78
08-05 14:14:32.018  7146  7146 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-05 14:14:32.019  7146  7647 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-05 14:14:32.020  7146  7647 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-05 14:14:32.021  7146  7648 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-05 14:14:32.022  7146  7651 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-05 14:14:32.022  7146  7648 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3c662460 on behalf of 
08-05 14:14:32.022  7146  7647 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@18d2ed19 on behalf of 
08-05 14:14:32.023  7146  7648 V BluetoothOppNotification: outbound: succ-0  fail-0
08-05 14:14:32.024  7146  7647 V BluetoothOppNotification: update too frequent, put in queue
08-05 14:14:32.025  7146  7648 V BluetoothOppNotification: outbound notification was removed.
08-05 14:14:32.025  7146  7648 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-05 14:14:32.026  7146  7647 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-05 14:14:32.027  7146  7648 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1062c1de on behalf of 
08-05 14:14:32.027  7146  7648 V BluetoothOppNotification: inbound: succ-0  fail-0
08-05 14:14:32.029  7146  7648 V BluetoothOppNotification: inbound notification was removed.
08-05 14:14:32.029  7146  7648 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-05 14:14:32.030  7146  7648 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@20d25fbf on behalf of 
,08-05 14:14:32.049  7146  7146 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3875791b
,08-05 14:14:32.049  7146  7146 V BluetoothSapService: Sap Service onCreate
08-05 14:14:32.051  7146  7146 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-05 14:14:32.051  7146  7146 V BluetoothSapService: state: 12
08-05 14:14:32.051  7146  7146 V BluetoothSapService: Starting SAP server process
08-05 14:14:32.053  7146  7146 V BluetoothSapService: SAP Service startRfcommListenerThread
08-05 14:14:32.050  7652  7652 W sapd    : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 14:14:32.050  7652  7652 W sapd    : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 14:14:32.056  7146  7653 V BluetoothSapService: Sap Service initRfcommSocket
08-05 14:14:32.057  1030  1917 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 14:14:32.058  7146  7653 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-05 14:14:32.060  7146  7653 V BluetoothSapService: Succeed to create listening socket 
08-05 14:14:32.060  7146  7653 V BluetoothSapService: Accepting socket connection...
08-05 14:14:32.067  7652  7652 V BT_SAP  : Event pipe created
08-05 14:14:32.067  7652  7652 V BT_SAP  : create_server_socket qcom.sap.server
08-05 14:14:32.067  7652  7652 V BT_SAP  : created socket fd 6
,08-05 14:14:32.385  1030  1387 D LGWifiP2pService: P2pDisabledState{ when=-2ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-05 14:14:32.385  1030  1387 D LGWifiP2pService: DefaultState{ when=-2ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-05 14:14:32.402  1030  1389 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
08-05 14:14:32.402  1030  1389 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-05 14:14:32.735  1030  1046 I ActivityManager: Killing 7196:com.lge.appbox.client/u0a11 (adj 15): empty #17
,08-05 14:14:32.781  1030  1917 W libprocessgroup: failed to open /acct/uid_10011/pid_7196/cgroup.procs: No such file or directory
,08-05 14:14:32.984  7146  7146 V BluetoothOppNotification: new notify threadi!
08-05 14:14:32.985  7146  7146 V BluetoothOppNotification: send delay message
,08-05 14:14:32.996  7146  7663 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-05 14:14:32.998  7146  7663 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@325738db on behalf of 
08-05 14:14:32.999  7146  7663 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-05 14:14:33.002  7146  7663 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,08-05 14:14:33.006  7146  7663 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@16d81f78 on behalf of 
,08-05 14:14:33.007  7146  7663 V BluetoothOppNotification: outbound: succ-0  fail-0
,08-05 14:14:33.008  7146  7663 V BluetoothOppNotification: outbound notification was removed.
08-05 14:14:33.008  7146  7663 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-05 14:14:33.009  7146  7663 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@226c2651 on behalf of 
08-05 14:14:33.010  7146  7663 V BluetoothOppNotification: inbound: succ-0  fail-0
08-05 14:14:33.012  7146  7663 V BluetoothOppNotification: inbound notification was removed.
08-05 14:14:33.012  7146  7663 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-05 14:14:33.013  7146  7663 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@f5f2eb6 on behalf of 
08-05 14:14:33.425  1030  1046 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 14:14:33.425  1030  1046 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@38051fbe mBinding = false
,08-05 14:14:33.458  1030  1030 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-05 14:14:33.458  1030  1030 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,08-05 14:14:33.458  1030  1030 D Ulp_jni : JNI:system_update. Event-4
08-05 14:14:33.459  1030  1094 D BluetoothManagerService: Message: 2
08-05 14:14:33.460  1030  1094 D BluetoothManagerService: Sending off request.
08-05 14:14:33.460  7146  7630 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-05 14:14:33.461  7146  7523 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-05 14:14:33.461  7146  7523 D BluetoothAdapterProperties: Setting state to 13
08-05 14:14:33.461  7146  7523 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-05 14:14:33.462  7146  7523 D BluetoothAdapterProperties: onBluetoothDisable()
08-05 14:14:33.462  7146  7523 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-05 14:14:33.464  7146  7527 D BluetoothAdapterProperties: Scan Mode:20
08-05 14:14:33.466  7146  7523 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-05 14:14:33.470  7146  7523 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-05 14:14:33.475  7146  7639 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-05 14:14:33.475  7146  7649 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-05 14:14:33.476  7146  7651 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-05 14:14:33.476  7146  7653 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-05 14:14:33.477  7146  7581 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-05 14:14:33.477  7146  7581 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-05 14:14:33.478  7146  7638 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-05 14:14:33.478  7146  7638 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-05 14:14:33.478  7146  7638 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-05 14:14:33.478  7146  7638 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-05 14:14:33.478  7146  7638 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-05 14:14:33.478  7146  7638 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-05 14:14:33.478  7146  7638 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-05 14:14:33.478  7146  7638 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-05 14:14:33.483  7146  7581 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-05 14:14:33.483  7146  7581 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-05 14:14:33.483  7146  7581 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-05 14:14:33.483  7146  7581 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-05 14:14:33.483  7146  7581 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-05 14:14:33.483  7146  7581 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-05 14:14:33.483  7146  7581 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-05 14:14:33.483  7146  7581 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-05 14:14:33.484  7146  7581 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-05 14:14:33.484  7146  7581 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-05 14:14:33.484  7146  7581 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-05 14:14:33.484  7146  7581 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
,08-05 14:14:33.496  6923  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 14:14:33.497  6923  6923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 14:14:33.497  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 14:14:33.497  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 14:14:33.497  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 14:14:33.497  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 14:14:33.497  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 14:14:33.497  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 14:14:33.497  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-05 14:14:33.501  6923  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 14:14:33.501  6923  6923 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-05 14:14:33.504  6923  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 14:14:33.504  6923  6923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 14:14:33.504  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 14:14:33.504  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 14:14:33.504  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 14:14:33.504  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 14:14:33.504  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 14:14:33.504  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 14:14:33.504  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 14:14:33.506  6923  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 14:14:33.506  6923  6923 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-05 14:14:33.508  1030  1094 D BluetoothManagerService: Message: 60
08-05 14:14:33.508  1030  1094 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-05 14:14:33.508  1030  1094 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-05 14:14:33.512  1938  1938 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-05 14:14:33.517  1600  1600 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-05 14:14:33.522  6923  6923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 14:14:33.523  6923  6923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 14:14:33.524  7146  7146 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-05 14:14:33.525  7146  7146 D BluetoothMapService: STATE_TURNING_OFF
08-05 14:14:33.525  7146  7146 V BluetoothMapService: Handler(): got msg=4
08-05 14:14:33.525  7146  7146 D BluetoothMapService: MAP Service closeService in
08-05 14:14:33.525  7146  7146 D BluetoothMapMasInstance: MAP Service shutdown
08-05 14:14:33.525  7146  7146 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-05 14:14:33.525  7146  7146 V BluetoothMapService: MAP Service closeService out
,08-05 14:14:33.530  7146  7146 V BtOppService: Receiver DISABLED_ACTION 
08-05 14:14:33.530  7146  7146 I BtOppRfcommListener: stopping Accept Thread
08-05 14:14:33.530  7146  7146 V BtOppRfcommListener: close mBtServerSocket
08-05 14:14:33.531  7146  7649 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-05 14:14:33.531  7146  7146 V BtOppRfcommListener: waiting for thread to terminate
08-05 14:14:33.532  7146  7146 V BtOppRfcommListener: done waiting for thread to terminate
08-05 14:14:33.534  7002  7002 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
08-05 14:14:33.545  7002  7002 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-05 14:14:33.552  7146  7146 V BtOppService: onDestroy
08-05 14:14:33.554  7146  7146 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-05 14:14:33.557  7146  7146 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-05 14:14:33.557  7146  7146 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 14:14:33.557  7146  7146 V BluetoothPbapReceiver: ***********state = 13
08-05 14:14:33.559  7146  7146 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
,08-05 14:14:33.565  7146  7146 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-05 14:14:33.565  7146  7146 V BluetoothPbapService: state: 13
08-05 14:14:33.565  7146  7146 V BluetoothPbapService: Pbap Service closeService in
08-05 14:14:33.567  2185  2185 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-05 14:14:33.568  7146  7146 V BluetoothPbapService: successfully stopped pbap service
08-05 14:14:33.568  7146  7146 V BluetoothPbapService: Pbap Service closeService out
08-05 14:14:33.569  7146  7146 V BluetoothPbapService: Pbap Service onDestroy
08-05 14:14:33.569  7146  7146 V BluetoothPbapService: Pbap Service closeService in
,08-05 14:14:33.569  7146  7146 V BluetoothPbapService: Pbap Service closeService out
08-05 14:14:33.569  7146  7146 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-05 14:14:33.594  7002  7002 D DockEventReceiver: finishStartingService: stopping service
,08-05 14:14:33.602  7002  7002 D BluetoothPbap: Proxy object disconnected
08-05 14:14:33.602  7002  7002 D PbapServerProfile: Bluetooth service disconnected
08-05 14:14:33.606  7002  7002 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-05 14:14:33.611  7002  7002 D BluetoothPermissionRequest: onReceive
08-05 14:14:33.611  7002  7002 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-05 14:14:33.619  7002  7002 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-05 14:14:33.622  7146  7146 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-05 14:14:33.622  7146  7146 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-05 14:14:33.622  7146  7146 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-05 14:14:33.626  7146  7146 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-05 14:14:33.626  7146  7146 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-05 14:14:33.627  7146  7146 V BluetoothFtpService: Ftp Service onStartCommand
08-05 14:14:33.627  7146  7146 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-05 14:14:33.628  7146  7146 V BluetoothFtpService: Ftp Service closeService
08-05 14:14:33.628  7146  7146 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
,08-05 14:14:33.630  7146  7146 V BluetoothFtpService: successfully stopped ftp service
08-05 14:14:33.631  7146  7146 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-05 14:14:33.631  7146  7146 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-05 14:14:33.631  7146  7146 V BluetoothSapReceiver: SapReceiver onReceive 
08-05 14:14:33.631  7146  7146 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 14:14:33.631  7146  7146 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-05 14:14:33.631  7146  7146 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-05 14:14:33.633  7146  7146 V BluetoothFtpService: Ftp Service onDestroy
08-05 14:14:33.633  7146  7146 V BluetoothFtpService: Ftp Service closeService
08-05 14:14:33.640  7146  7146 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-05 14:14:33.640  7146  7146 V BluetoothSapService: state: 13
08-05 14:14:33.640  7146  7146 V BluetoothSapService: Stopping SAP server process
08-05 14:14:33.641  7146  7146 V BluetoothSapService: Sap Service closeSapService in
08-05 14:14:33.642  7146  7146 V BluetoothSapService: Close listen Socket : 
08-05 14:14:33.642  7146  7146 V BluetoothSapService: Close rfcomm Socket : 
08-05 14:14:33.642  7146  7146 V BluetoothSapService: Close sapd  Socket : 
,08-05 14:14:33.646  7146  7146 V BluetoothSapService: Sap Service closeSapService out
,08-05 14:14:33.646  7146  7146 V BluetoothSapService: Sap Service onDestroy
,08-05 14:14:33.646  7146  7146 V BluetoothSapService: Sap Service closeSapService in
08-05 14:14:33.646  7146  7146 V BluetoothSapService: Close listen Socket : 
08-05 14:14:33.646  7146  7146 V BluetoothSapService: Close rfcomm Socket : 
08-05 14:14:33.646  7146  7146 V BluetoothSapService: Close sapd  Socket : 
08-05 14:14:33.648  7146  7146 V BluetoothSapService: Sap Service closeSapService out
08-05 14:14:34.384  7146  7527 D bt_hci_bdroid: cleanup
,08-05 14:14:34.394  7146  7583 I bt_lpm  : LPM is already off!!!
08-05 14:14:34.395  7146  7607 I bt_userial_mct: exiting userial_read_thread
08-05 14:14:34.395  7146  7607 D bt_userial_mct: Leaving userial_evt_read_thread()
08-05 14:14:34.395  7146  7581 W bt-btif : ag scb idx 1 not allocated
08-05 14:14:34.395  7146  7581 E bt-btif : BTA AG is already disabled, ignoring ...
08-05 14:14:34.396  7146  7581 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-05 14:14:34.396  7146  7581 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-05 14:14:34.396  7146  7581 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-05 14:14:34.396  7146  7581 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-05 14:14:34.396  7146  7581 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-05 14:14:34.396  7146  7581 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-05 14:14:34.396  7146  7581 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-05 14:14:34.396  7146  7581 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-05 14:14:34.396  7146  7581 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-05 14:14:34.396  7146  7581 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-05 14:14:34.396  7146  7581 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-05 14:14:34.396  7146  7581 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-05 14:14:34.396  7146  7581 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-05 14:14:34.396  7146  7581 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-05 14:14:34.396  7146  7581 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-05 14:14:34.396  7146  7581 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-05 14:14:34.396  7146  7581 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-05 14:14:34.396  7146  7581 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-05 14:14:34.396  7146  7581 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-05 14:14:34.397  7146  7527 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-05 14:14:34.397  7146  7583 I bt_vendor: hw_epilog_process
08-05 14:14:34.397  7146  7527 D bt_hci_bdroid: cleanup Finalizing cleanup
08-05 14:14:34.397  7146  7527 D bt_userial_mct: userial_close
08-05 14:14:34.397  7146  7527 E bt_userial_mct: pthread_join() FAILED result:3
08-05 14:14:34.397  7146  7527 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-05 14:14:34.401  7146  7527 D bt_hci_bdroid: set_power 0
08-05 14:14:34.401  7146  7527 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-05 14:14:34.401  7146  7527 I bt_vendor: bluetooth satus is on
08-05 14:14:34.401  7146  7527 I bt_vendor: bt-vendor : resetting BT status
08-05 14:14:34.401  7146  7527 I bt_vendor: Starting hciattach daemon
08-05 14:14:34.401  7146  7527 I bt_vendor: try to set false
08-05 14:14:34.405  7146  7527 I bt_vendor: Starting hciattach daemon
08-05 14:14:34.405  7146  7527 I bt_vendor: try to set false
08-05 14:14:34.405  7146  7527 I bt_vendor: cleanup
08-05 14:14:34.406  7146  7581 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
,08-05 14:14:34.410  7146  7527 I GKI_LINUX: GKI_exit_task 0 done
08-05 14:14:34.410  7146  7527 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-05 14:14:34.412  7146  7523 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-05 14:14:34.418  7146  7523 D BluetoothAdapterState: Stopping profile services that were post enabled
,08-05 14:14:34.422  7146  7146 D HeadsetService: Received stop request...Stopping profile...
08-05 14:14:34.424  7146  7146 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-05 14:14:34.424  7146  7146 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-05 14:14:34.424  7146  7146 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3875791b
08-05 14:14:34.425  7146  7562 D HeadsetStateMachine: Exit Disconnected: -1
08-05 14:14:34.428  1030  1030 D BluetoothHeadset: Proxy object disconnected
08-05 14:14:34.428  1030  1030 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-05 14:14:34.429  1849  1849 D BluetoothHeadset: Proxy object disconnected
08-05 14:14:34.429  1849  1849 D BluetoothHeadset: Proxy object disconnected
08-05 14:14:34.429  1849  1849 D BluetoothHeadset: Proxy object disconnected
08-05 14:14:34.429  7146  7146 D A2dpService: Received stop request...Stopping profile...
08-05 14:14:34.430  7146  7570 D A2dpStateMachine: Exit Disconnected: -1
08-05 14:14:34.432  7146  7146 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
,08-05 14:14:34.437  7146  7146 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-05 14:14:34.438  7146  7146 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-05 14:14:34.438  7146  7146 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3875791b
08-05 14:14:34.439  1030  1030 D BluetoothA2dp: Proxy object disconnected
08-05 14:14:34.439  1030  1030 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-05 14:14:34.440  7146  7146 D HidService: Received stop request...Stopping profile...
08-05 14:14:34.440  7146  7146 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3875791b
08-05 14:14:34.442  7146  7146 D HealthService: Received stop request...Stopping profile...
08-05 14:14:34.442  7146  7146 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3875791b
08-05 14:14:34.445  7146  7146 D PanService: Received stop request...Stopping profile...
,08-05 14:14:34.449  7146  7146 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3875791b
08-05 14:14:34.451  7146  7146 D BtGatt.DebugUtils: handleDebugAction() action=null
08-05 14:14:34.452  7146  7146 D BtGatt.GattService: Received stop request...Stopping profile...
08-05 14:14:34.452  7146  7146 D BtGatt.GattService: stop()
08-05 14:14:34.452  7146  7146 D BtGatt.AdvertiseManager: advertise clients cleared
08-05 14:14:34.453  7146  7146 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3875791b
08-05 14:14:34.454  7146  7146 D BluetoothMapService: Received stop request...Stopping profile...
08-05 14:14:34.454  7146  7146 D BluetoothMapService: stop()
08-05 14:14:34.455  7146  7146 D BluetoothMapEmailAppObserver: deinitObservers()
08-05 14:14:34.455  7146  7146 D BluetoothMapEmailAppObserver: removeReceiver()
08-05 14:14:34.456  7146  7146 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3875791b
08-05 14:14:34.457  7146  7146 D HeadsetStateMachine: Unbinding service...
08-05 14:14:34.460  7146  7146 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-05 14:14:34.460  7146  7146 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-05 14:14:34.460  7146  7146 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-05 14:14:34.460  7146  7146 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-05 14:14:34.461  7146  7146 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-05 14:14:34.461  7146  7146 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-05 14:14:34.461  7146  7146 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-05 14:14:34.461  7146  7146 I BluetoothA2dpServiceJni: cleanupNative
,08-05 14:14:34.464  7146  7571 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-05 14:14:34.464  7146  7146 I GKI_LINUX: GKI_exit_task 2 done
08-05 14:14:34.464  7146  7146 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-05 14:14:34.465  7146  7146 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-05 14:14:34.465  7146  7146 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-05 14:14:34.465  7146  7146 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-05 14:14:34.465  7146  7146 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-05 14:14:34.466  7146  7146 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-05 14:14:34.466  7146  7146 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-05 14:14:34.466  7146  7146 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-05 14:14:34.469  7146  7146 V BluetoothMapService: Handler(): got msg=4
08-05 14:14:34.469  7146  7146 D BluetoothMapService: MAP Service closeService in
08-05 14:14:34.469  7146  7146 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-05 14:14:34.469  7146  7146 V BluetoothMapService: MAP Service closeService out
08-05 14:14:34.469  7146  7523 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-05 14:14:34.470  7146  7523 D BluetoothAdapterProperties: Setting state to 10
08-05 14:14:34.470  7146  7523 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-05 14:14:34.471  7146  7146 D BluetoothMapService: cleanup()
08-05 14:14:34.471  7146  7146 D BluetoothMapService: MAP Service closeService in
08-05 14:14:34.471  7146  7146 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-05 14:14:34.471  7146  7146 V BluetoothMapService: MAP Service closeService out
08-05 14:14:34.477  1030  1094 D BluetoothManagerService: Message: 60
08-05 14:14:34.477  1030  1094 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-05 14:14:34.477  1030  1094 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
,08-05 14:14:34.483  7146  7523 I BluetoothAdapterState: Entering OffState
08-05 14:14:34.485  7002  7064 D BluetoothMap: onBluetoothStateChange: up=false
08-05 14:14:34.485  7002  7064 D BluetoothPbap: onBluetoothStateChange: up=false
08-05 14:14:34.486  1849  1865 D BluetoothHeadset: onBluetoothStateChange: up=false
08-05 14:14:34.487  1030  1094 D BluetoothHeadset: onBluetoothStateChange: up=false
08-05 14:14:34.487  7002  7627 D BluetoothHeadset: onBluetoothStateChange: up=false
08-05 14:14:34.488  7002  7627 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-05 14:14:34.488  7002  7627 D BluetoothA2dp: onBluetoothStateChange: up=false
08-05 14:14:34.489  7002  7064 D BluetoothPan: onBluetoothStateChange on: false
08-05 14:14:34.489  1030  1094 D BluetoothA2dp: onBluetoothStateChange: up=false
08-05 14:14:34.493  1849  2439 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-05 14:14:34.496  1849  1864 D BluetoothHeadset: onBluetoothStateChange: up=false
08-05 14:14:34.497  1030  1094 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-05 14:14:34.497  1030  1094 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-05 14:14:34.500  1030  1094 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-05 14:14:34.500  1030  1094 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-05 14:14:34.500  1030  1094 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@38051fbe mBinding = false
08-05 14:14:34.501  1030  1094 D BluetoothManagerService: Sending unbind request.
08-05 14:14:34.506  7146  7527 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-05 14:14:34.508  7146  7146 I GKI_LINUX: GKI_exit_task 1 done
,08-05 14:14:34.508  7146  7146 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
,08-05 14:14:34.509  7146  7146 I BluetoothServiceJni: cleanupNative: return from cleanup
08-05 14:14:34.509  7146  7146 I art     : --- WEIRD: removing null entry 248
08-05 14:14:34.509  7146  7146 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-05 14:14:34.509  7146  7146 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
,08-05 14:14:34.510  7146  7146 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-05 14:14:34.512  1030  1094 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-05 14:14:34.514  7146  7146 I art     : System.exit called, status: 0
08-05 14:14:34.514  7146  7146 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-05 14:14:34.537   312  1399 V AudioFlinger: 7146 died, releasing its sessions
08-05 14:14:34.537   312  1399 V AudioFlinger:  pid 1849 @ 0
08-05 14:14:34.537   312  1399 V AudioFlinger:  pid 3317 @ 1
08-05 14:14:34.537   312  1399 V AudioFlinger:  pid 3317 @ 2
,08-05 14:14:34.539  1938  1938 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
08-05 14:14:34.540  1938  2121 D LGBluetoothAPIService: Message: 101
08-05 14:14:34.540  1938  2121 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
08-05 14:14:34.540  1938  2121 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
,08-05 14:14:34.541  1938  2121 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
,08-05 14:14:34.543  7002  7002 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-05 14:14:34.621  1030  1735 I ActivityManager: Process com.android.bluetooth (pid 7146) has died
08-05 14:14:34.622  1030  1735 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 1000ms
,08-05 14:14:34.622  1030  1735 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 10999ms
08-05 14:14:34.627  1938  1938 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-05 14:14:34.628  1938  2121 D LGBluetoothAPIService: Message: 2
08-05 14:14:34.628  1938  2121 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
08-05 14:14:34.628  1600  1600 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-05 14:14:34.630  6923  6923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 14:14:34.632  7002  7002 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-05 14:14:34.632  7002  7002 D LGBluetoothEventManager: [BTUI] clear device connection state
08-05 14:14:34.632  6923  6923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 14:14:34.636  1600  1600 D BluetoothAdapter: 87351117: getState() :  mService = null. Returning STATE_OFF
08-05 14:14:34.636  1600  1600 D BluetoothAdapter: 87351117: getState() :  mService = null. Returning STATE_OFF
,08-05 14:14:34.638  7002  7002 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-05 14:14:34.687  1030  1653 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7714 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-05 14:14:34.690  7002  7002 D DockEventReceiver: finishStartingService: stopping service
,08-05 14:14:34.722   338   338 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 451us total 35.992ms
08-05 14:14:34.733  7714  7714 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-05 14:14:34.733  7714  7714 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-05 14:14:34.733  7714  7714 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-05 14:14:34.734  7714  7714 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-05 14:14:34.741   338   338 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 403us total 18.973ms
08-05 14:14:34.750  7714  7714 D BluetoothAdapterApp: Loading JNI Library
,08-05 14:14:34.759   338   338 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 355us total 17.306ms
08-05 14:14:34.782  7714  7714 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@14b798a3 Instance Count = 1
,08-05 14:14:34.788  7714  7714 D BluetoothAdapterApp: onCreate
08-05 14:14:34.809  7714  7714 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-05 14:14:34.809  7714  7714 D ProfileConfigQcom: Adding HeadsetService
08-05 14:14:34.809  7714  7714 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-05 14:14:34.810  7714  7714 D ProfileConfigQcom: Adding A2dpService
08-05 14:14:34.810  7714  7714 D ProfileConfigQcom: [BTUI] HidService is supported
08-05 14:14:34.810  7714  7714 D ProfileConfigQcom: Adding HidService
08-05 14:14:34.810  7714  7714 D ProfileConfigQcom: [BTUI] HealthService is supported
08-05 14:14:34.810  7714  7714 D ProfileConfigQcom: Adding HealthService
08-05 14:14:34.810  7714  7714 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-05 14:14:34.811  7714  7714 D ProfileConfigQcom: [BTUI] PanService is supported
08-05 14:14:34.811  7714  7714 D ProfileConfigQcom: Adding PanService
08-05 14:14:34.811  7714  7714 D ProfileConfigQcom: [BTUI] GattService is supported
08-05 14:14:34.812  7714  7714 D ProfileConfigQcom: Adding GattService
08-05 14:14:34.812  7714  7714 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-05 14:14:34.812  7714  7714 D ProfileConfigQcom: Adding BluetoothMapService
08-05 14:14:34.812  7714  7714 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-05 14:14:34.813  7714  7714 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-05 14:14:34.814  7714  7714 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 14:14:34.814  7714  7714 V BluetoothPbapReceiver: ***********state = 10
,08-05 14:14:34.815  7714  7714 V LGMDMManagerInternal: Create singleton instance
,08-05 14:14:34.878  7714  7714 D LGBluetoothAPIServer: [BTUI] onCreate()
,08-05 14:14:34.879  7714  7714 D LGBluetoothAPIServer: [BTUI] onBind()
,08-05 14:14:34.889  2185  2185 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-05 14:14:34.892  1938  1938 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
,08-05 14:14:34.892  1938  2121 D LGBluetoothAPIService: Message: 100
08-05 14:14:34.892  1938  2121 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
,08-05 14:14:34.913  7002  7002 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,08-05 14:14:34.915  7002  7002 D BluetoothPermissionRequest: onReceive
08-05 14:14:34.917  7002  7002 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-05 14:14:34.917  7002  7002 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-05 14:14:34.919  7002  7002 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-05 14:14:34.925  7714  7714 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,08-05 14:14:34.932  7714  7714 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-05 14:14:34.936  7714  7714 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-05 14:14:34.936  7714  7714 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-05 14:14:34.936  7714  7714 V BluetoothSapReceiver: SapReceiver onReceive 
08-05 14:14:34.938  7714  7714 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
,08-05 14:14:34.938  7714  7714 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
,08-05 14:14:34.940  7096  7096 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-05 14:14:36.542  6923  6984 D io.jxcore.node.ConnectivityMonitor: stop
08-05 14:14:36.542  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-05 14:14:37.658  1030  1376 V AlarmManager: ELAPSED_WAKEUP set : Alarm{5b92135 type 2 when 363393 com.google.android.gms} when 363393
,08-05 14:14:37.677   308  7742 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-05 14:14:37.678  1030  1092 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-05 14:14:39.557  6923  6984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-05 14:14:39.558  6923  6984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1ddce78f added. We now have 6 listener(s)
08-05 14:14:39.558  6923  6984 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-05 14:14:39.571  6923  6984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 14:14:39.574  6923  6984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2d365a1c added. We now have 7 listener(s)
08-05 14:14:39.574  6923  6984 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 14:14:39.575  6923  6984 I System.out: IsBluetoothEnabled
,08-05 14:14:39.578  1030  1992 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 14:14:39.578  1030  1992 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
08-05 14:14:39.578  1030  1094 D BluetoothManagerService: Message: 2
08-05 14:14:39.582  6923  6984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 14:14:39.583  1030  1735 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 14:14:39.583  1030  1735 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-05 14:14:39.600  1030  1030 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-05 14:14:39.601  1030  1030 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-05 14:14:39.601  1030  1030 D Ulp_jni : JNI:system_update. Event-4
08-05 14:14:39.602  1030  1094 D BluetoothManagerService: Message: 1
08-05 14:14:39.602  1030  1094 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-05 14:14:39.626  1030  1094 D BluetoothManagerService: Message: 20
08-05 14:14:39.626  1030  1094 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5736896:true
,08-05 14:14:39.630  7714  7714 D BluetoothAdapterState: make
08-05 14:14:39.635  7714  7714 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-05 14:14:39.635  7714  7714 I bluedroid-qcom: init
08-05 14:14:39.637  7714  7746 I BluetoothAdapterState: Entering OffState
08-05 14:14:39.637  7714  7714 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-05 14:14:39.637  7714  7714 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-05 14:14:39.637  7714  7714 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-05 14:14:39.637  7714  7714 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-05 14:14:39.637  7714  7714 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-05 14:14:39.639  7714  7714 I bluedroid-qcom: get_profile_interface socket
08-05 14:14:39.639  7714  7714 I bluedroid-qcom: get_profile_interface map_client
,08-05 14:14:39.644  7714  7750 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-05 14:14:39.640  7749  7749 W bdaddr_loader: type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 14:14:39.648  7714  7750 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-05 14:14:39.640  7749  7749 W bdaddr_loader: type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 14:14:39.655  1030  1030 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-05 14:14:39.655  1030  1030 D BluetoothManagerService: Stored Bluetooth name: G3
,08-05 14:14:39.663  1030  1030 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-05 14:14:39.663  1030  1094 D BluetoothManagerService: Message: 40
08-05 14:14:39.663  1030  1094 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-05 14:14:39.664  7714  7730 I bluedroid-qcom: config_hci_snoop_log
08-05 14:14:39.666  7749  7749 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-05 14:14:39.666  7749  7749 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-05 14:14:39.666  7749  7749 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-05 14:14:39.667  1030  1094 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-05 14:14:39.667  1030  1094 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-05 14:14:39.669  7749  7749 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
,08-05 14:14:39.674  7749  7749 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-05 14:14:39.674  7749  7749 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-05 14:14:39.676  7714  7750 D BluetoothAdapterProperties: Name is: G3
08-05 14:14:39.680  7714  7746 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-05 14:14:39.680  7714  7746 D BluetoothAdapterProperties: Setting state to 11
08-05 14:14:39.680  7714  7746 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,08-05 14:14:39.684  7714  7746 I LGBluetoothServiceJni: classInitNative: succeeds
08-05 14:14:39.685  1030  1094 D BluetoothManagerService: Message: 60
08-05 14:14:39.685  1030  1094 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-05 14:14:39.685  1030  1094 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-05 14:14:39.689  1938  1938 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-05 14:14:39.690  1600  1600 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-05 14:14:39.693  6923  6923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 14:14:39.699  7002  7002 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
,08-05 14:14:39.704  7714  7714 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-05 14:14:39.705  7714  7714 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 14:14:39.705  7714  7714 V BluetoothPbapReceiver: ***********state = 11
08-05 14:14:39.710  2185  2185 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-05 14:14:39.734  7714  7746 D BluetoothBondStateMachine: make
,08-05 14:14:39.739  7714  7746 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1accfab8
08-05 14:14:39.739  7714  7746 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-05 14:14:39.739  7714  7764 I BluetoothBondStateMachine: StableState(): Entering Off State
08-05 14:14:39.739  7714  7746 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1accfab8
08-05 14:14:39.740  7714  7746 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-05 14:14:39.741  7714  7746 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-05 14:14:39.744  7002  7002 D BluetoothPermissionRequest: onReceive
08-05 14:14:39.746  7714  7746 E BluetoothAdapterService: File transfer profiles supported!!
08-05 14:14:39.749  7002  7002 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-05 14:14:39.756  7714  7714 D HeadsetService: Received start request. Starting profile...
08-05 14:14:39.757  7714  7746 E BluetoothAdapterService: File transfer profiles supported!!
08-05 14:14:39.757  7714  7714 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-05 14:14:39.757  7714  7714 D LGBluetoothHfpAdapter: Version 1.6
08-05 14:14:39.761  7714  7714 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-05 14:14:39.763  7714  7714 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-05 14:14:39.763  7714  7746 E BluetoothAdapterService: File transfer profiles supported!!
08-05 14:14:39.763  7714  7714 D HeadsetStateMachine: make
,08-05 14:14:39.769  7714  7746 E BluetoothAdapterService: File transfer profiles supported!!
,08-05 14:14:39.774  7714  7746 E BluetoothAdapterService: File transfer profiles supported!!
,08-05 14:14:39.780  7714  7746 E BluetoothAdapterService: File transfer profiles supported!!
08-05 14:14:39.784  7714  7746 E BluetoothAdapterService: File transfer profiles supported!!
08-05 14:14:39.798  7714  7714 D LgDataFeature: LgDataFeature() Constructor: none
,08-05 14:14:39.798  7714  7714 D LgDataFeature: LgDataFeature() Constructor Done, null
08-05 14:14:39.798  7714  7746 V LGMDMManager: Create singleton instance
08-05 14:14:39.800  7714  7746 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-05 14:14:39.801  7714  7714 D HeadsetStateMachine: max_hf_connections = 1
08-05 14:14:39.801  7714  7714 I bluedroid-qcom: get_profile_interface handsfree
08-05 14:14:39.803  7714  7714 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-05 14:14:39.804   312  2154 V AudioPolicyService: registerClient() client 0xb101dc00, uid 1002
08-05 14:14:39.804   312  2161 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-05 14:14:39.804   312  2161 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-05 14:14:39.804   312  2161 V AudioPolicyManagerEx: getOutput() returns output 2
08-05 14:14:39.805  7714  7714 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-05 14:14:39.805   312   312 V AudioFlinger: registerClient() client 0xb5581808, pid 7714
08-05 14:14:39.806  7714  7714 V ToneGenerator: Create Track: 0xb4928080
08-05 14:14:39.806  7714  7714 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-05 14:14:39.806  7714  7714 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-05 14:14:39.806   312  1395 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-05 14:14:39.806   312  1395 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-05 14:14:39.806   312  1399 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-05 14:14:39.806   312  1399 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-05 14:14:39.806   312  1399 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-05 14:14:39.806   312  1399 V AudioPolicyManagerEx: getOutput() returns output 2
08-05 14:14:39.806   312  1394 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-05 14:14:39.806   312  1394 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-05 14:14:39.807  1030  1915 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-05 14:14:39.807  1030  1915 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-05 14:14:39.807  1030  1915 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-05 14:14:39.807  1030  1915 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-05 14:14:39.807  1600  1619 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-05 14:14:39.807  1600  1619 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-05 14:14:39.807  1600  1619 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-05 14:14:39.807  1600  1619 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-05 14:14:39.808  1849  1864 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-05 14:14:39.808  1849  1864 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-05 14:14:39.808  1849  1864 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-05 14:14:39.808  1849  1864 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-05 14:14:39.808  3317  3333 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-05 14:14:39.808  3317  3333 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-05 14:14:39.808  3317  3333 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-05 14:14:39.808  3317  3333 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-05 14:14:39.808  7714  7714 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-05 14:14:39.808  7714  7729 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-05 14:14:39.808  7714  7729 V AudioSystem: ioConfigCh,anged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-05 14:14:39.808  7714  7729 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-05 14:14:39.809  7714  7729 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-05 14:14:39.809   312  2161 I AudioFlinger: isAudioPlaybackHookOn() false
08-05 14:14:39.809   312  1400 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-05 14:14:39.809   312  1400 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-05 14:14:39.809   312  1400 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-05 14:14:39.809   312  1400 V AudioPolicyManagerEx: getOutput() returns output 2
08-05 14:14:39.809  7714  7714 V AudioSystem: getLatency() output 2, latency 50
08-05 14:14:39.809  7714  7714 V AudioSystem: getFrameCount() output 2, frameCount 960
08-05 14:14:39.809  7714  7714 V AudioTrack: createTrack_l() output 2 afLatency 50
08-05 14:14:39.809   312  1399 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-05 14:14:39.809   312  1399 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-05 14:14:39.809   312  1399 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-05 14:14:39.809   312  1399 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-05 14:14:39.809   312  1399 V AudioFlinger: createTrack() lSessionId: 21
08-05 14:14:39.810  7714  7714 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-05 14:14:39.810   312  1399 V AudioFlinger: acquiring 21 from 7714, for 7714
08-05 14:14:39.810   312  1399 V AudioFlinger:  added new entry for 21
08-05 14:14:39.810  7714  7714 V ToneGenerator: ToneGenerator INIT OK, time: 365559
08-05 14:14:39.810  7714  7714 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1accfab8
08-05 14:14:39.812  7714  7768 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
,08-05 14:14:39.812  7714  7768 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-05 14:14:39.812  7714  7768 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-05 14:14:39.812  7714  7768 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-05 14:14:39.812   312   312 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7714
08-05 14:14:39.812  7714  7714 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1accfab8
08-05 14:14:39.814   312   312 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-05 14:14:39.814   312   312 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-05 14:14:39.814   312   312 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-05 14:14:39.814   312   312 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-05 14:14:39.814   312   312 V voice   : voice_set_parameters: exit with code(0)
08-05 14:14:39.814   312   312 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-05 14:14:39.814   312   312 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-05 14:14:39.814   312   312 V msm8974_platform: platform_set_parameters: exit with code(0)
08-05 14:14:39.814   312   312 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-05 14:14:39.814   312   312 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-05 14:14:39.814   312   312 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-05 14:14:39.814  7714  7714 D A2dpService: Received start request. Starting profile...
08-05 14:14:39.815  7714  7714 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-05 14:14:39.816  7714  7714 V Avrcp   : make
08-05 14:14:39.816  7714  7714 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-05 14:14:39.816  7714  7714 I bluedroid-qcom: get_profile_interface avrcp
08-05 14:14:39.816  7714  7768 V ToneGenerator: ToneGenerator destructor
08-05 14:14:39.816  7714  7768 V ToneGenerator: stopTone
08-05 14:14:39.816  7714  7768 V ToneGenerator: Delete Track: 0xb4928080
08-05 14:14:39.817  7714  7768 V AudioTrack: ~AudioTrack, releasing session id from 7714 on behalf of 7714
08-05 14:14:39.817   312  1400 V AudioFlinger: releasing 21 from 7714 for 7714
08-05 14:14:39.817   312  1400 V AudioFlinger:  decremented refcount to 0
08-05 14:14:39.817   312  1400 V AudioFlinger: purging stale effects
08-05 14:14:39.817   312  1400 V AudioPolicyService: AudioCommandThread() adding release output 2
08-05 14:14:39.817   312  1400 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-05 14:14:39.817   312  1216 V AudioPolicyService: AudioCommandThread() waking up
08-05 14:14:39.817   312  1216 V AudioPolicyService: AudioCommandThread() processing release output 2
08-05 14:14:39.818   312  1216 V AudioPolicyManager: releaseOutput() 2
08-05 14:14:39.818   312  1216 V AudioPolicyService: AudioCommandThread() going to sleep
08-05 14:14:39.818   312  1400 V AudioFlinger: PlaybackThread::Track destructor
08-05 14:14:39.818   312  1400 V AudioFlinger: removeClient_l() pid 7714, calling pid 312
08-05 14:14:39.826  7714  7714 V AudioManager: registerRemoteController: size of Media player list: 0
,08-05 14:14:39.829  7714  7714 E AudioManager: No RCC entry present to update
08-05 14:14:39.829  7714  7714 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-05 14:14:39.833  7714  7714 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-05 14:14:39.834  7714  7714 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-05 14:14:39.834  7714  7714 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-05 14:14:39.837  7714  7714 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-05 14:14:39.933  1030  1735 V SIM_STK : Menu title from STK is T-Mobile
08-05 14:14:39.933  1030  1735 V SIM_STK : Menu title from STK is T-Mobile
,08-05 14:14:40.012  1030  1951 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-05 14:14:40.021  7714  7714 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,08-05 14:14:40.025  7714  7714 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-05 14:14:40.025  7714  7714 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-05 14:14:40.025  7714  7714 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-05 14:14:40.025  7714  7714 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-05 14:14:40.025  7714  7714 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-05 14:14:40.025  7714  7714 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-05 14:14:40.025  7714  7714 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-05 14:14:40.025  7714  7714 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-05 14:14:40.026  7714  7714 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-05 14:14:40.026  7714  7714 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-05 14:14:40.026  7714  7714 I BluetoothA2dpServiceJni: classInitNative
08-05 14:14:40.026  7714  7714 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-05 14:14:40.026  7714  7714 D A2dpStateMachine: make
08-05 14:14:40.029  7714  7714 I bluedroid-qcom: get_profile_interface a2dp
08-05 14:14:40.030  7714  7774 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,08-05 14:14:40.033  7714  7714 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-05 14:14:40.033  7714  7714 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-05 14:14:40.033  7714  7714 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1accfab8
08-05 14:14:40.034  7714  7714 I BluetoothHidServiceJni: classInitNative: succeeds
08-05 14:14:40.035  7714  7773 D A2dpStateMachine: Enter Disconnected: -2
08-05 14:14:40.036  7714  7714 D HidService: Received start request. Starting profile...
08-05 14:14:40.036  7714  7714 I bluedroid-qcom: get_profile_interface hidhost
08-05 14:14:40.036  7714  7714 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1accfab8
08-05 14:14:40.037  7714  7714 I BluetoothHealthServiceJni: classInitNative: succeeds
08-05 14:14:40.038  7714  7714 D HealthService: Received start request. Starting profile...
,08-05 14:14:40.041  7714  7714 I bluedroid-qcom: get_profile_interface health
08-05 14:14:40.042  7714  7714 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-05 14:14:40.042  7714  7714 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1accfab8
08-05 14:14:40.042  7714  7714 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-05 14:14:40.044  7714  7714 D PanService: Received start request. Starting profile...
08-05 14:14:40.044  7714  7714 D BluetoothPanServiceJni: initializeNative(L110): pan
08-05 14:14:40.044  7714  7714 I bluedroid-qcom: get_profile_interface pan
,08-05 14:14:40.052  7714  7714 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-05 14:14:40.052  7714  7714 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1accfab8
08-05 14:14:40.052  7714  7714 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-05 14:14:40.056  7714  7714 D BtGatt.DebugUtils: handleDebugAction() action=null
08-05 14:14:40.056  7714  7714 D BtGatt.GattService: Received start request. Starting profile...
08-05 14:14:40.057  7714  7714 D BtGatt.GattService: start()
08-05 14:14:40.057  7714  7714 I bluedroid-qcom: get_profile_interface gatt
08-05 14:14:40.057  7714  7714 D BtGatt.AdvertiseManager: advertise manager created
,08-05 14:14:40.069  7714  7714 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1accfab8
,08-05 14:14:40.073  7714  7714 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1accfab8
,08-05 14:14:40.074  7714  7714 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
,08-05 14:14:40.076  7714  7714 V BluetoothMapService: BluetoothMapBinder()
08-05 14:14:40.078  7714  7714 D BluetoothMapService: Received start request. Starting profile...
08-05 14:14:40.078  7714  7714 D BluetoothMapService: start()
08-05 14:14:40.085  7714  7714 D BluetoothMapEmailSettingsLoader: Found 0 applications
,08-05 14:14:40.085  7714  7714 D BluetoothMapEmailAppObserver: createReceiver()
08-05 14:14:40.088  7714  7714 D BluetoothMapEmailAppObserver: initObservers()
08-05 14:14:40.088  7714  7714 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-05 14:14:40.099  7714  7714 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1accfab8
08-05 14:14:40.099  7714  7714 D HeadsetStateMachine: Proxy object connected
,08-05 14:14:40.100  7714  7714 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
,08-05 14:14:40.100  7714  7714 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-05 14:14:40.102  7714  7768 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-05 14:14:40.102  7714  7768 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-05 14:14:40.103  7714  7768 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-05 14:14:40.106  7714  7714 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-05 14:14:40.108  7714  7714 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-05 14:14:40.113  7714  7714 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-05 14:14:40.116  7714  7714 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-05 14:14:40.119  7714  7714 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-05 14:14:40.119  7714  7714 V PanService: [BTUI] SIM Extra State :ABSENT
08-05 14:14:40.122  7714  7714 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-05 14:14:40.124  7714  7714 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-05 14:14:40.124  7714  7714 V BluetoothMapService: Handler(): got msg=1
08-05 14:14:40.125  7714  7714 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-05 14:14:40.125  7714  7714 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-05 14:14:40.125  7714  7714 V BluetoothSapReceiver: SapReceiver onReceive 
08-05 14:14:40.125  7714  7746 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-05 14:14:40.125  7714  7714 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 14:14:40.125  7714  7746 I bluedroid-qcom: enable
08-05 14:14:40.125  7714  7714 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-05 14:14:40.126  7714  7746 I bt_hci_bdroid: init
08-05 14:14:40.128  7714  7784 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-05 14:14:40.128  7714  7784 I bt-btu  : btu_task pending for preload complete event
,08-05 14:14:40.130  7714  7746 I bt_vendor: bt-vendor : init
,08-05 14:14:40.130  7714  7746 I bt_vendor: bt-vendor : get_bt_soc_type
08-05 14:14:40.130  7714  7746 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-05 14:14:40.130  7714  7746 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-05 14:14:40.130  7714  7746 D bt_userial_mct: userial_init
08-05 14:14:40.130  7714  7746 D bt_hci_bdroid: set_power 1
08-05 14:14:40.130  7714  7746 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-05 14:14:40.130  7714  7746 I bt_vendor: Starting hciattach daemon
08-05 14:14:40.130  7714  7746 I bt_vendor: try to set true
08-05 14:14:40.130  7787  7787 W sh      : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 14:14:40.130  7787  7787 W sh      : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 14:14:40.167  7788  7788 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-05 14:14:40.267  7794  7794 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-05 14:14:40.284  7795  7795 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-05 14:14:40.311  7797  7797 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-05 14:14:40.330  7798  7798 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-05 14:14:40.344  7799  7799 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-05 14:14:40.358  7800  7800 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-05 14:14:40.400  7802  7802 I libmdmdetect: ESOC framework not supported
,08-05 14:14:40.402  7802  7802 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-05 14:14:40.411  7802  7802 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-05 14:14:40.411  7802  7802 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-05 14:14:40.411  7802  7802 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-05 14:14:40.412  7802  7802 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-05 14:14:40.412  7802  7802 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-05 14:14:40.412  7802  7802 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-05 14:14:40.412  7802  7802 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-05 14:14:40.456  7802  7806 E QC-QMI  : qmi_client [7802] 15: failed to locate client data
,08-05 14:14:40.467   463   463 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-05 14:14:40.467   463   463 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
08-05 14:14:40.493  7810  7810 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-05 14:14:40.508  7811  7811 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-05 14:14:40.533  7714  7746 I bt_vendor: bluetooth satus is on
08-05 14:14:40.533  7714  7746 D bt_hci_bdroid: preload
,08-05 14:14:40.535  7714  7786 D bt_userial_mct: userial_open(port:0)
08-05 14:14:40.535  7714  7786 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-05 14:14:40.539  7714  7786 I bt_vendor: Done intiailizing UART
08-05 14:14:40.540  7714  7786 I bt_vendor: Done intiailizing UART
08-05 14:14:40.540  7714  7786 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-05 14:14:40.540  7714  7786 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-05 14:14:40.541  7714  7784 I bt-btu  : btu_task received preload complete event
08-05 14:14:40.541  7714  7784 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-05 14:14:40.541  7714  7784 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-05 14:14:40.543  7714  7813 D bt_userial_mct: Entering userial_read_thread()
08-05 14:14:40.544  7714  7784 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-05 14:14:40.547  7714  7784 I         : BTE_InitTraceLevels -- TRC_HCI
08-05 14:14:40.547  7714  7784 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-05 14:14:40.547  7714  7784 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-05 14:14:40.547  7714  7784 I         : BTE_InitTraceLevels -- TRC_AVDT
08-05 14:14:40.547  7714  7784 I         : BTE_InitTraceLevels -- TRC_AVRC
08-05 14:14:40.547  7714  7784 I         : BTE_InitTraceLevels -- TRC_A2D
08-05 14:14:40.547  7714  7784 I         : BTE_InitTraceLevels -- TRC_BNEP
08-05 14:14:40.547  7714  7784 I         : BTE_InitTraceLevels -- TRC_BTM
08-05 14:14:40.547  7714  7784 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-05 14:14:40.547  7714  7784 I         : BTE_InitTraceLevels -- TRC_GAP
08-05 14:14:40.547  7714  7784 I         : BTE_InitTraceLevels -- TRC_PAN
08-05 14:14:40.547  7714  7784 I         : BTE_InitTraceLevels -- TRC_SDP
08-05 14:14:40.547  7714  7784 I         : BTE_InitTraceLevels -- TRC_GATT
08-05 14:14:40.547  7714  7784 I         : BTE_InitTraceLevels -- TRC_SMP
08-05 14:14:40.547  7714  7784 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-05 14:14:40.547  7714  7784 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-05 14:14:40.652  7714  7784 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
,08-05 14:14:40.652  7714  7784 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01e2061 
08-05 14:14:40.652  7714  7784 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01e2061 
,08-05 14:14:40.708  7714  7750 E bt-btif : Calling BTA_HhEnable
,08-05 14:14:40.708  7714  7750 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-05 14:14:40.709  7714  7750 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-05 14:14:40.718  7714  7784 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-05 14:14:40.718  7714  7784 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-05 14:14:40.718  7714  7784 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-05 14:14:40.718  7714  7784 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-05 14:14:40.718  7714  7784 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-05 14:14:40.723  1030  1030 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-05 14:14:40.724  1030  1030 D BluetoothManagerService: Stored Bluetooth name: G3
08-05 14:14:40.729  7714  7750 D BluetoothAdapterProperties: Name is: G3
,08-05 14:14:40.735  7714  7750 D BluetoothAdapterProperties: Scan Mode:20
08-05 14:14:40.735  7714  7750 D BluetoothAdapterProperties: Discoverable Timeout:120
08-05 14:14:40.735  7714  7750 D bt_hci_bdroid: postload
08-05 14:14:40.735  7714  7786 D bt_hci_bdroid: Used up Tx Cmd credits
08-05 14:14:40.736  7714  7750 D bte_conf: Device ID record 1 : primary
08-05 14:14:40.736  7714  7750 D bte_conf:   vendorId            = 00c4
08-05 14:14:40.736  7714  7750 D bte_conf:   vendorIdSource      = 0001
08-05 14:14:40.736  7714  7750 D bte_conf:   product             = 13a1
08-05 14:14:40.736  7714  7750 D bte_conf:   version             = 1000
08-05 14:14:40.736  7714  7750 D bte_conf:   clientExecutableURL = 
08-05 14:14:40.736  7714  7750 D bte_conf:   serviceDescription  = 
08-05 14:14:40.736  7714  7750 D bte_conf:   documentationURL    = 
08-05 14:14:40.736  7714  7750 D bte_conf: bte_load_did_conf no section named DID2.
08-05 14:14:40.737  7714  7784 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-05 14:14:40.740  7714  7746 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-05 14:14:40.740  7714  7746 D BluetoothAdapterProperties: ScanMode =  20
08-05 14:14:40.740  7714  7746 D BluetoothAdapterProperties: State =  11
08-05 14:14:40.740  7714  7746 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-05 14:14:40.741  7714  7746 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-05 14:14:40.741  7714  7746 D BluetoothAdapterProperties: Setting state to 12
08-05 14:14:40.741  7714  7746 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-05 14:14:40.743  7714  7750 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-05 14:14:40.743  7714  7750 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-05 14:14:40.740  7815  7815 W sh      : type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 14:14:40.750  7815  7815 W sh      : type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 14:14:40.761  1030  1094 D BluetoothManagerService: Message: 60
08-05 14:14:40.761  1030  1094 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
,08-05 14:14:40.764  7714  7746 I BluetoothAdapterState: Entering On State
08-05 14:14:40.766  7714  7746 D LGBluetoothServiceAdapter: [BTUI] OnState
08-05 14:14:40.766  7714  7746 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-05 14:14:40.766  7714  7746 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-05 14:14:40.767  7714  7746 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-05 14:14:40.768  7714  7784 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-05 14:14:40.768  7714  7784 W bt-smp  : Plain text(LSB ~ MSB) = bf 60 4d 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-05 14:14:40.768  7714  7784 W bt-smp  : Encrypted text(LSB ~ MSB) = 59 d3 29 e9 c7 c1 de 5c 18 bf 26 5e b3 73 1f b3 
08-05 14:14:40.768  7714  7786 D bt_hci_bdroid: Used up Tx Cmd credits
08-05 14:14:40.768  7714  7784 W bt-btm  : Stopping oneshot timer
08-05 14:14:40.772  7714  7786 D bt_hci_bdroid: Used up Tx Cmd credits
08-05 14:14:40.775  7714  7786 D bt_hci_bdroid: Used up Tx Cmd credits
,08-05 14:14:40.778  7714  7813 E bt_mct  : hci lib postload completed
08-05 14:14:40.772  1030  1094 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
08-05 14:14:40.795  6923  6923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 14:14:40.795  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 14:14:40.795  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 14:14:40.795  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 14:14:40.795  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 14:14:40.795  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 14:14:40.795  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 14:14:40.795  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-05 14:14:40.801  7714  7750 D BluetoothAdapterProperties: Discoverable Timeout:120
08-05 14:14:40.801  7714  7750 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-05 14:14:40.808  7714  7784 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-05 14:14:40.808  7714  7784 W bt-smp  : Plain text(LSB ~ MSB) = 8f 4b 70 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-05 14:14:40.808  7714  7784 W bt-smp  : Encrypted text(LSB ~ MSB) = e4 0f 40 03 e7 0b 5b 14 f3 43 33 9d e7 57 60 70 
,08-05 14:14:40.810  7714  7784 W bt-btm  : Stopping oneshot timer
08-05 14:14:40.811  6923  6923 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-05 14:14:40.818  7714  7746 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-05 14:14:40.818  7002  7022 D BluetoothMap: onBluetoothStateChange: up=true
08-05 14:14:40.849  7820  7820 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,08-05 14:14:40.864  7002  7022 D BluetoothPbap: onBluetoothStateChange: up=true
,08-05 14:14:40.872  7714  7784 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-05 14:14:40.872  7714  7784 W bt-smp  : Plain text(LSB ~ MSB) = 7d 6f 74 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-05 14:14:40.872  7714  7784 W bt-smp  : Encrypted text(LSB ~ MSB) = 0c ea 93 37 68 1f 7b f5 5d 20 15 13 e6 a3 5b aa 
08-05 14:14:40.872  7714  7784 W bt-btm  : Stopping oneshot timer
08-05 14:14:40.877  1849  4460 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-05 14:14:40.885  1849  1849 D BluetoothHeadset: Proxy object connected
08-05 14:14:40.886  1030  1094 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-05 14:14:40.887  1030  1030 D BluetoothHeadset: Proxy object connected
08-05 14:14:40.888  7002  7023 D BluetoothHeadset: onBluetoothStateChange: up=true
08-05 14:14:40.891  7002  7002 D BluetoothMap: Proxy object connected
08-05 14:14:40.891  7002  7002 D MapProfile: Bluetooth service connected
08-05 14:14:40.891  7002  7002 D BluetoothMap: getConnectedDevices()
08-05 14:14:40.892  7714  7784 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-05 14:14:40.892  7714  7784 W bt-smp  : Plain text(LSB ~ MSB) = 9f 6d 4f 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-05 14:14:40.892  7714  7784 W bt-smp  : Encrypted text(LSB ~ MSB) = ac 9e 3c ff 1b 1c 27 dd 45 33 10 e7 d5 61 2d f2 
08-05 14:14:40.892  7714  7784 W bt-btm  : Stopping oneshot timer
,08-05 14:14:40.897  7002  7064 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-05 14:14:40.901  7714  7729 V BluetoothMapService: getConnectedDevices()
08-05 14:14:40.902  7002  7022 D BluetoothA2dp: onBluetoothStateChange: up=true
08-05 14:14:40.906  7002  7002 D BluetoothHeadset: Proxy object connected
08-05 14:14:40.906  7002  7002 D HeadsetProfile: Bluetooth service connected
,08-05 14:14:40.908  7002  7002 D BluetoothInputDevice: Proxy object connected
08-05 14:14:40.908  7002  7002 D HidProfile: Bluetooth service connected
08-05 14:14:40.909  7002  7023 D BluetoothPan: onBluetoothStateChange on: true
08-05 14:14:40.909  7002  7023 D BluetoothPan: onBluetoothStateChange call bindService
08-05 14:14:40.910  7714  7784 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-05 14:14:40.910  7714  7784 W bt-smp  : Plain text(LSB ~ MSB) = a0 fb 6a 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-05 14:14:40.910  7714  7784 W bt-smp  : Encrypted text(LSB ~ MSB) = ae 35 cd 49 fd ff 97 a0 55 5e ac 16 fc 7e 4f 4f 
08-05 14:14:40.911  7714  7784 W bt-btm  : Stopping oneshot timer
08-05 14:14:40.912  1030  1094 D BluetoothA2dp: onBluetoothStateChange: up=true
08-05 14:14:40.912  7002  7002 D BluetoothA2dp: Proxy object connected
08-05 14:14:40.912  7002  7002 D A2dpProfile: Bluetooth service connected
08-05 14:14:40.913  1030  1030 D BluetoothA2dp: Proxy object connected
08-05 14:14:40.913  1849  2439 D BluetoothHeadset: onBluetoothStateChange: up=true
08-05 14:14:40.914  7002  7002 D BluetoothPan: BluetoothPAN Proxy object connected
08-05 14:14:40.914  7002  7002 D PanProfile: Bluetooth service connected
08-05 14:14:40.916  1849  1849 D BluetoothHeadset: Proxy object connected
08-05 14:14:40.916  1849  2673 D BluetoothHeadset: onBluetoothStateChange: up=true
08-05 14:14:40.918  1849  1849 D BluetoothHeadset: Proxy object connected
08-05 14:14:40.919  1030  1094 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
,08-05 14:14:40.919  1030  1030 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-05 14:14:40.919  1030  1094 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-05 14:14:40.921  1600  1600 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-05 14:14:40.921  1938  1938 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-05 14:14:40.924  1938  2121 D LGBluetoothAPIService: Message: 1
08-05 14:14:40.924  1938  2121 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-05 14:14:40.924  1938  2121 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
08-05 14:14:40.924  1938  2121 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-05 14:14:40.925  1030  1094 D BluetoothManagerService: Message: 40
08-05 14:14:40.925  1030  1094 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-05 14:14:40.927  6923  6923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 14:14:40.928  7714  7714 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-05 14:14:40.928  7714  7714 D BluetoothMapService: STATE_ON
08-05 14:14:40.929  7002  7002 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-05 14:14:40.931  7002  7002 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-05 14:14:40.938  7002  7002 D DockEventReceiver: finishStartingService: stopping service
,08-05 14:14:40.944  7714  7714 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1accfab8
08-05 14:14:40.944  7714  7714 V BluetoothPbapService: Pbap Service onCreate
08-05 14:14:40.944  7714  7714 V BluetoothPbapService: Starting PBAP service
08-05 14:14:40.948  7714  7714 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-05 14:14:40.948  7714  7714 V BluetoothMapService: Handler(): got msg=1
08-05 14:14:40.948  7714  7714 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-05 14:14:40.949  7714  7714 V BluetoothPbapService: Pbap Service onBind
08-05 14:14:40.950  7714  7839 D BluetoothMapMasInstance: MAS initSocket()
08-05 14:14:40.950  7714  7714 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-05 14:14:40.950  7714  7714 V BluetoothPbapService: state: 12
08-05 14:14:40.950  7714  7714 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-05 14:14:40.950  7714  7714 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 14:14:40.950  7714  7714 V BluetoothPbapReceiver: ***********state = 12
08-05 14:14:40.951  7714  7839 D BluetoothMapMasInstance:   masId = 00
08-05 14:14:40.951  7714  7839 D BluetoothMapMasInstance:   msgTypes = 0e
08-05 14:14:40.951  7714  7839 D BluetoothMapMasInstance:   masName = SMS/MMS
08-05 14:14:40.951  7714  7839 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-05 14:14:40.952  7714  7714 V BluetoothPbapService: Handler(): got msg=1
08-05 14:14:40.952  7714  7714 V BluetoothPbapService: Pbap Service startRfcommSocketListener
,08-05 14:14:40.953  7002  7002 D BluetoothPbap: Proxy object connected
08-05 14:14:40.953  7002  7002 D PbapServerProfile: Bluetooth service connected
08-05 14:14:40.953  1030  1592 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 14:14:40.954  2185  2185 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-05 14:14:40.954  2185  2185 D c       : Getting all permits...
08-05 14:14:40.954  2185  2185 D a       : Opening database...
08-05 14:14:40.954  7714  7839 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-05 14:14:40.955  7714  7840 V BluetoothPbapService: Pbap Service initSocket
08-05 14:14:40.955  1030  1986 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 14:14:40.955  7714  7840 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-05 14:14:40.956  7714  7839 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-05 14:14:40.956  7714  7839 V BluetoothMapMasInstance: Succeed to create listening socket 
08-05 14:14:40.956  7714  7750 D BluetoothAdapterProperties: Scan Mode:21
08-05 14:14:40.956  7714  7839 D BluetoothMapMasInstance: Accepting socket connection...
08-05 14:14:40.956  7714  7750 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-05 14:14:40.957  7714  7840 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-05 14:14:40.957  7714  7840 V BluetoothPbapService: Succeed to create listening socket 
08-05 14:14:40.957  7714  7840 V BluetoothPbapService: Accepting socket connection...
08-05 14:14:40.959  6923  6923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 14:14:40.961  2185  2185 D a       : Opening database auth.proximity.permit_store...
08-05 14:14:40.962  2185  2185 D a       : Closing database...
08-05 14:14:40.973  7002  7002 D BluetoothPermissionRequest: onReceive
,08-05 14:14:40.974  7002  7002 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-05 14:14:40.976  7002  7002 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-05 14:14:40.978  7714  7714 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-05 14:14:40.979  7714  7714 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-05 14:14:40.985  7714  7714 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-05 14:14:41.003  7714  7714 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-05 14:14:41.004  7714  7714 V BtOppService: onCreate
,08-05 14:14:41.008  7714  7714 V BluetoothOppNotification: send message
,08-05 14:14:41.011  7714  7714 V BtOppService: Starting RfcommListener
08-05 14:14:41.019  7714  7714 D BluetoothOppPreference: Dumping Names:  
08-05 14:14:41.019  7714  7714 D BluetoothOppPreference: {}
08-05 14:14:41.019  7714  7714 D BluetoothOppPreference: Dumping Channels:  
08-05 14:14:41.019  7714  7714 D BluetoothOppPreference: {}
08-05 14:14:41.020  7714  7714 V BtOppService: onStartCommand
,08-05 14:14:41.024  7714  7714 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-05 14:14:41.024  7714  7714 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-05 14:14:41.026  7714  7848 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-05 14:14:41.028  7714  7714 V BluetoothOppNotification: new notify threadi!
08-05 14:14:41.028  7714  7714 V BluetoothOppNotification: send delay message
08-05 14:14:41.029  7714  7714 V BtOppService: start RfcommListener
08-05 14:14:41.031  7714  7848 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
,08-05 14:14:41.032  7714  7845 V BtOppService: Deleted complete outbound shares, number =  0
08-05 14:14:41.034  7714  7848 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@c692cf4 on behalf of 
08-05 14:14:41.035  7714  7845 V BtOppService: Deleted complete inbound failed shares, number = 0
08-05 14:14:41.035  7714  7845 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-05 14:14:41.036  7714  7845 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@d32ac1d on behalf of 
08-05 14:14:41.037  7714  7714 V BtOppService: RfcommListener started
08-05 14:14:41.039  7714  7849 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-05 14:14:41.040  7714  7848 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-05 14:14:41.042  7714  7850 V BtOppRfcommListener: Starting RFCOMM listener....
08-05 14:14:41.042  7714  7849 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@a724e92 on behalf of 
08-05 14:14:41.043  1030  1951 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 14:14:41.043  7714  7849 V BluetoothOppNotification: mUpdateCompleteNotification = true
,08-05 14:14:41.044  7714  7849 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-05 14:14:41.044  7714  7850 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-05 14:14:41.046  7714  7850 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
08-05 14:14:41.047  7714  7850 V BtOppRfcommListener: Started RFCOMM listener....
08-05 14:14:41.047  7714  7850 I BtOppRfcommListener: Accept thread started.
08-05 14:14:41.047  7714  7850 V BtOppRfcommListener: Accepting connection...
08-05 14:14:41.046  7714  7849 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1d882063 on behalf of 
08-05 14:14:41.049  7714  7849 V BluetoothOppNotification: outbound: succ-0  fail-0
08-05 14:14:41.050  7714  7849 V BluetoothOppNotification: outbound notification was removed.
08-05 14:14:41.050  7714  7849 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-05 14:14:41.052  7714  7849 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3c662460 on behalf of 
08-05 14:14:41.053  7714  7849 V BluetoothOppNotification: inbound: succ-0  fail-0
08-05 14:14:41.055  7714  7849 V BluetoothOppNotification: inbound notification was removed.
,08-05 14:14:41.055  7714  7849 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-05 14:14:41.057  7714  7849 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@18d2ed19 on behalf of 
08-05 14:14:41.064  7714  7714 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1accfab8
08-05 14:14:41.064  7714  7714 V BluetoothFtpService: Ftp Service onCreate
08-05 14:14:41.064  7714  7714 I BluetoothFtpService: Ftp Service onCreate
08-05 14:14:41.064  7714  7714 V BluetoothFtpService: Ftp Service onStartCommand
08-05 14:14:41.064  7714  7714 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-05 14:14:41.065  7714  7714 V BluetoothFtpService: Starting Listening on sockets
08-05 14:14:41.065  7714  7714 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-05 14:14:41.065  7714  7714 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-05 14:14:41.065  7714  7714 V BluetoothSapReceiver: SapReceiver onReceive 
08-05 14:14:41.065  7714  7714 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 14:14:41.065  7714  7714 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-05 14:14:41.066  7714  7714 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-05 14:14:41.068  7714  7714 V BtOppService: ContentObserver received notification
08-05 14:14:41.068  7714  7714 V BtOppService: ContentObserver received notification
08-05 14:14:41.068  7714  7714 V BluetoothFtpService: Handler(): got msg=1
,08-05 14:14:41.069  7714  7714 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-05 14:14:41.069  7714  7714 V BluetoothFtpService: Ftp Service initSocket
08-05 14:14:41.070  7714  7851 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-05 14:14:41.070  7714  7851 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-05 14:14:41.072  7714  7851 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@20d25fbf on behalf of 
08-05 14:14:41.072  7714  7851 V BluetoothOppNotification: update too frequent, put in queue
08-05 14:14:41.074  1030  1733 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 14:14:41.074  7714  7851 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-05 14:14:41.075  7714  7714 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-05 14:14:41.076  7714  7714 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=78
08-05 14:14:41.076  7714  7714 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-05 14:14:41.078  7714  7852 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-05 14:14:41.104  7714  7714 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1accfab8
,08-05 14:14:41.104  7714  7714 V BluetoothSapService: Sap Service onCreate
08-05 14:14:41.108  7714  7714 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-05 14:14:41.108  7714  7714 V BluetoothSapService: state: 12
08-05 14:14:41.108  7714  7714 V BluetoothSapService: Starting SAP server process
08-05 14:14:41.110  7714  7714 V BluetoothSapService: SAP Service startRfcommListenerThread
08-05 14:14:41.100  7853  7853 W sapd    : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 14:14:41.100  7853  7853 W sapd    : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 14:14:41.113  7714  7854 V BluetoothSapService: Sap Service initRfcommSocket
08-05 14:14:41.114  1030  1951 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 14:14:41.116  7714  7854 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-05 14:14:41.119  7714  7854 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
,08-05 14:14:41.119  7714  7854 V BluetoothSapService: Succeed to create listening socket 
08-05 14:14:41.119  7714  7854 V BluetoothSapService: Accepting socket connection...
08-05 14:14:41.124  7853  7853 V BT_SAP  : Event pipe created
08-05 14:14:41.124  7853  7853 V BT_SAP  : create_server_socket qcom.sap.server
08-05 14:14:41.124  7853  7853 V BT_SAP  : created socket fd 6
08-05 14:14:41.631  6923  6984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 14:14:41.631  6923  6984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 14:14:41.631  6923  6984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 14:14:41.631  6923  6984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 14:14:41.631  6923  6984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 14:14:41.631  6923  6984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 14:14:41.631  6923  6984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 14:14:41.631  6923  6984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-05 14:14:41.645  6923  6984 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-05 14:14:41.648  6923  6984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 14:14:41.648  6923  6984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1d411625 added. We now have 8 listener(s)
08-05 14:14:41.648  6923  6984 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 14:14:41.651  1030  1592 D WifiServiceImplEx: setWifiEnabled: false pid=6923, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-05 14:14:41.652  1030  1592 D WifiService: setWifiEnabled: false pid=6923, uid=10118
08-05 14:14:41.652  1030  1592 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-05 14:14:41.659  6923  6984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 14:14:41.662  1030  1735 D WifiServiceImplEx: setWifiEnabled: true pid=6923, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-05 14:14:41.663  1030  1735 D WifiService: setWifiEnabled: true pid=6923, uid=10118
08-05 14:14:41.663  1030  1735 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-05 14:14:41.681  1030  1030 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-05 14:14:41.681  1030  1030 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-05 14:14:41.682  1030  1030 D Ulp_jni : JNI:system_update. Event-4
08-05 14:14:41.683  1030  1389 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-05 14:14:41.683  1030  1389 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-05 14:14:41.686  1030  1389 E WifiUtil: wfc_util_ffile_check_copy(): pid[1030] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
,08-05 14:14:41.686  1030  1389 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010],
08-05 14:14:41.686  1030  1389 E WifiUtil: wfc_util_ffile_check_copy(): pid[1030] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
,08-05 14:14:41.686  1030  1389 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
,08-05 14:14:41.686  1030  1389 I WifiUtil: Intf0MacAddress=C49A027FFB5D
,08-05 14:14:41.686  1030  1389 E WifiHW  : unknown target_country: EU , set to default
,08-05 14:14:41.686  1030  1389 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
,08-05 14:14:41.686  1030  1389 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-05 14:14:41.686  1030  1389 I WifiUtil: gEnableBmps=1,
,08-05 14:14:42.031  7714  7714 V BluetoothOppNotification: new notify threadi!,
,08-05 14:14:42.065  7714  7714 V BluetoothOppNotification: send delay message,
,08-05 14:14:42.080  7714  7867 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-05 14:14:42.100  7714  7867 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@325738db on behalf of 
08-05 14:14:42.101  7714  7867 V BluetoothOppNotification: mUpdateCompleteNotification = true
,08-05 14:14:42.106  7714  7867 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-05 14:14:42.107  7714  7867 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@16d81f78 on behalf of 
08-05 14:14:42.108  7714  7867 V BluetoothOppNotification: outbound: succ-0  fail-0
08-05 14:14:42.110  7714  7867 V BluetoothOppNotification: outbound notification was removed.
08-05 14:14:42.110  7714  7867 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-05 14:14:42.112  7714  7867 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@226c2651 on behalf of 
08-05 14:14:42.112  7714  7867 V BluetoothOppNotification: inbound: succ-0  fail-0
08-05 14:14:42.115  7714  7867 V BluetoothOppNotification: inbound notification was removed.
08-05 14:14:42.115  7714  7867 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,08-05 14:14:42.118  7714  7867 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@f5f2eb6 on behalf of 
08-05 14:14:42.285   308   895 D SoftapController: Softap fwReload - Ok
,08-05 14:14:42.289  1030  1094 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-05 14:14:42.289  1030  1094 D Tethering: InitialState.processMessage what=4
08-05 14:14:42.292  1030  1389 E NetdConnector: NDC Command {67 softap fwreload wlan0 STA} took too long (603ms)
,08-05 14:14:42.309   308   895 D CommandListener: Setting iface cfg
08-05 14:14:42.309   308   895 D CommandListener: Trying to bring down wlan0
08-05 14:14:42.323  1030  1094 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-05 14:14:42.329   308   895 D CommandListener: Clearing all IP addresses on wlan0
,08-05 14:14:42.348  1030  1389 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-05 14:14:42.360  7875  7875 W wpa_supplicant: type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-05 14:14:42.369  1030  1389 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-05 14:14:42.369  1030  1389 E WifiStateMachine: useWiFiOffloading() : false
08-05 14:14:42.369  1030  1389 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-05 14:14:42.360  7875  7875 W wpa_supplicant: type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 14:14:42.375  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-05 14:14:42.385  1938  1938 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-05 14:14:42.402  6923  6923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 14:14:42.404  1030  1389 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-05 14:14:42.404  1030  1389 D WifiMonitor: connecting to supplicant
08-05 14:14:42.406  1030  1030 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-05 14:14:42.407  7002  7002 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-05 14:14:42.407  7002  7002 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-05 14:14:42.407  7002  7002 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-05 14:14:42.407  7002  7002 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-05 14:14:42.408  7002  7002 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-05 14:14:42.410  7002  7002 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-05 14:14:42.410  7002  7002 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-05 14:14:42.410  7002  7002 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-05 14:14:42.410  7002  7002 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-05 14:14:42.410  7002  7002 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-05 14:14:42.411  7002  7002 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-05 14:14:42.414  7002  7002 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-05 14:14:42.414  7002  7002 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-05 14:14:42.414  7002  7002 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-05 14:14:42.414  7002  7002 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-05 14:14:42.415  7002  7002 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-05 14:14:42.415  7002  7002 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-05 14:14:42.416  7002  7002 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-05 14:14:42.416  7002  7002 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
,08-05 14:14:42.416  7002  7002 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-05 14:14:42.422  7002  7002 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-05 14:14:42.422  7002  7002 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-05 14:14:42.423  7875  7875 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-05 14:14:42.430  7045  7045 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-05 14:14:42.433  7002  7002 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-05 14:14:42.439  7002  7002 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-05 14:14:42.455  7117  7895 V FormManager: Network unavailable.
08-05 14:14:42.456  7117  7894 W FormManager: Network not available. Please check & try again.
08-05 14:14:42.457  7875  7875 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-05 14:14:42.457  7875  7875 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
08-05 14:14:42.458  7117  7895 V FormManager: Network unavailable.
,08-05 14:14:42.534  7875  7875 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-05 14:14:42.554  7875  7875 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-05 14:14:42.561  1030  1389 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
,08-05 14:14:42.562  1030  1389 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
,08-05 14:14:42.563  1030  1389 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-05 14:14:42.563  1030  1389 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
,08-05 14:14:42.563  1030  1389 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-05 14:14:42.564  1030  1389 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-05 14:14:42.564  1030  1389 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-05 14:14:42.565  1030  1389 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-05 14:14:42.565  1030  1389 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-05 14:14:42.565  1030  1389 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-05 14:14:42.566  1030  1389 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-05 14:14:42.566  1030  1389 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-05 14:14:42.566  1030  1389 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-05 14:14:42.567  1030  1389 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-05 14:14:42.567  1030  1389 E WifiStateMachine: useWiFiOffloading() : false
08-05 14:14:42.567  1030  1389 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-05 14:14:42.567  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 14:14:42.567  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 14:14:42.567  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-05 14:14:42.567  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.,
08-05 14:14:42.567  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,08-05 14:14:42.568  1030  1389 D WifiNative-wlan0: doBoolean: SET update_config 1
,08-05 14:14:42.568  1030  1389 D WifiNative-wlan0: SET update_config 1: returned true
,08-05 14:14:42.568  1030  1389 D WifiConfigStore: Loading config and enabling all networks 
08-05 14:14:42.569  1030  1389 D WifiNative-wlan0: doString: [LIST_NETWORKS]
,08-05 14:14:42.569  1030  1389 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any,	
08-05 14:14:42.570  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-05 14:14:42.570  1938  1938 D WfdService: Waiting for WifiP2p enabling
,08-05 14:14:42.579  1030  1389 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-05 14:14:42.580  6923  6923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 14:14:42.580  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 14:14:42.580  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 14:14:42.580  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 14:14:42.580  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 14:14:42.580  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 14:14:42.580  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 14:14:42.580  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 14:14:42.584  1030  1030 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-05 14:14:42.584  6923  6923 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-05 14:14:42.585  1030  1393 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-05 14:14:42.593  1030  7897 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-05 14:14:42.593  1030  7897 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-05 14:14:42.593  7875  7875 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-05 14:14:42.594  1030  7897 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-05 14:14:42.594  1030  7897 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-05 14:14:42.594  1030  7897 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-05 14:14:42.594  1030  7897 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-05 14:14:42.596  1030  1389 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-05 14:14:42.596  1030  1389 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-05 14:14:42.597  7045  7045 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-05 14:14:42.598  1030  1389 D WifiStateMachine: enableVerboseLogging : level 2
08-05 14:14:42.598  1030  1389 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-05 14:14:42.599  1030  1389 D WifiNative-wlan0: SET device_name g3_global_com: returned true
,08-05 14:14:42.599  1030  1389 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-05 14:14:42.599  1030  1389 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-05 14:14:42.599  1030  1389 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-05 14:14:42.600  1030  1389 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-05 14:14:42.600  1030  1389 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-05 14:14:42.600  1030  1389 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-05 14:14:42.600  1030  1389 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-05 14:14:42.601  1030  1389 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-05 14:14:42.601  1030  1389 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
,08-05 14:14:42.601  1030  1389 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-05 14:14:42.601  1030  1389 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-05 14:14:42.602  1030  1389 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-05 14:14:42.604  7002  7002 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-05 14:14:42.605  1030  1389 D WifiStateMachine: Setting OUI to DA-A1-19
08-05 14:14:42.605  1030  1389 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-05 14:14:42.606  1938  1938 D WfdsService: Supplicant Connection state is changed : true
08-05 14:14:42.606  1030  1389 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-05 14:14:42.606  1030  1389 D WifiNative-HAL: Setting external_sim to 1
08-05 14:14:42.606  1938  2301 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-05 14:14:42.606  1030  1389 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-05 14:14:42.606  1938  2301 D WfdsService: Set the WFDS Monitor: true
08-05 14:14:42.607  1938  2301 D WfdsMonitor: WfdsMonitorThread create
08-05 14:14:42.607  1938  2301 D WfdsMonitor: WFDS Monitor is created and started
08-05 14:14:42.607  1938  2301 D WfdsService: WiFi: Supplicant connection re-established
08-05 14:14:42.607  1030  1389 D WifiNative-wlan0: SET external_sim 1: returned true
08-05 14:14:42.607  1030  1389 I WifiNative-HAL: startHal
08-05 14:14:42.607  1030  1389 D wifi    : setting scan oui 0xaf69dc20
08-05 14:14:42.608  1938  7901 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-05 14:14:42.608  1030  1389 D WifiStateMachine: Setting OUI to DA-A1-19
08-05 14:14:42.608  1030  1389 I WifiNative-HAL: startHal
08-05 14:14:42.608  1030  1389 D wifi    : setting scan oui 0xaf69dc20
08-05 14:14:42.608  1030  1389 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-05 14:14:42.608  1030  1389 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-05 14:14:42.609  1030  1389 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-05 14:14:42.609  7875  7875 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-05 14:14:42.609  1030  1389 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-05 14:14:42.609  1030  1389 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-05 14:14:42.610  7875  7875 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-05 14:14:42.610  1030  1389 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-05 14:14:42.610  1030  1389 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-05 14:14:42.610  7875  7875 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-05 14:14:42.610  1030  1389 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-05 14:14:42.610  1030  1389 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-05 14:14:42.610  7875  7875 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-05 14:14:42.611  1030  1389 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-05 14:14:42.611  1030  1389 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-05 14:14:42.611  7875  7875 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-05 14:14:42.612  1030  1389 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-05 14:14:42.612  1030  1389 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-05 14:14:42.612  7875  7875 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-05 14:14:42.612  1030  1389 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-05 14:14:42.612  1030  1389 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-05 14:14:42.613  7875  7875 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-05 14:14:42.613  1030  1389 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
,08-05 14:14:42.614  1030  1389 E WifiNative: : [368,353,487 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-05 14:14:42.614  1030  1389 D WifiNative-wlan0: doBoolean: RECONNECT
08-05 14:14:42.614  1938  7901 E CtrlSupplicant: Succeed to open control connection
08-05 14:14:42.614  1938  7901 E CtrlSupplicant: Succeed to open monitor connection
08-05 14:14:42.615  1938  7901 D WfdsMonitor: Supplicant connection established
08-05 14:14:42.615  1938  2301 D WfdsService: Connected to the supplicant for wfds
08-05 14:14:42.615  1030  1389 D WifiNative-wlan0: RECONNECT: returned true
08-05 14:14:42.615  1030  1389 D WifiNative-wlan0: doString: [STATUS]
08-05 14:14:42.616  1030  7897 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-05 14:14:42.616  1030  7897 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-05 14:14:42.616  1030  1389 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-05 14:14:42.616  1030  1389 D WifiNative-wlan0: doBoolean: SET ps 1
08-05 14:14:42.617  1030  1389 D WifiNative-wlan0: SET ps 1: returned true
08-05 14:14:42.617  1030  1387 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-05 14:14:42.619   308   895 D CommandListener: Setting iface cfg
08-05 14:14:42.619  1030  1030 D WifiScanningService: SCAN_AVAILABLE : 3
08-05 14:14:42.619   308   895 D CommandListener: Trying to bring up p2p0
08-05 14:14:42.619  1030  1030 D RttService: SCAN_AVAILABLE : 3
08-05 14:14:42.619  1030  1387 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-05 14:14:42.619  1030  1389 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-05 14:14:42.619  1030  1553 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-05 14:14:42.619  1030  1387 D LGWifiP2pService: P2pEnablingState
08-05 14:14:42.619  1030  1553 I WifiNative-HAL: startHal
08-05 14:14:42.619  1030  1387 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-05 14:14:42.619  1030  1553 D wifi    : getting scan capabilities on interface[1] = 0xaf69dc20
08-05 14:14:42.619  1030  1387 D LGWifiP2pService: P2p socket connection successful
08-05 14:14:42.619  1030  1553 D wifi    : failed to get capabilities : -3
08-05 14:14:42.619  1030  1553 E WifiScanningService: could not get scan capabilities
08-05 14:14:42.620  1030  1387 D LGWifiP2pService: P2pEnabledState
08-05 14:14:42.620  1030  1389 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-05 14:14:42.620  1030  1389 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-05 14:14:42.620  1030  1554 D RttService: DefaultState got{ when=-2ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-05 14:14:42.620  1030  1387 D LGWifiP2pService: sending p2p connection changed broadcast
08-05 14:14:42.621  1938  1938 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-05 14:14:42.623  1030  1387 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-05 14:14:42.623  1938  1938 D WfdsService: WifiP2pState is changed : true
08-05 14:14:42.623  1030  1387 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-05 14:14:42.623  1030  1387 D WifiNative-p2p0: doBoolean: SET device_name G3
08-05 14:14:42.624  1938  2301 D WfdsService: Receive the WFDS_ENABLE Method
08-05 14:14:42.624  1938  2301 D WfdsService: Set the WFDS Monitor: true
08-05 14:14:42.624  1938  2301 D WfdsService: Connected to the supplicant for wfds
08-05 14:14:42.624  1938  2301 D WfdsJNI : doCommand: WFDS_SET TRUE
,08-05 14:14:42.624  7875  7875 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-05 14:14:42.624  1938  2301 D WfdsService: selectPreferredScanChannel [36]
08-05 14:14:42.624  1938  2301 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-05 14:14:42.624  1030  1387 D WifiNative-p2p0: SET device_name G3: returned true
08-05 14:14:42.624  1030  1387 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
,08-05 14:14:42.624  1030  1387 D LGWifiP2pService: before postfix = G3
08-05 14:14:42.624  1030  1387 D WifiServerServiceExt: postfix byte check : 2
08-05 14:14:42.624  1030  1389 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-05 14:14:42.624  1030  1387 D LGWifiP2pService: after postfix = G3
08-05 14:14:42.624  1030  1387 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-05 14:14:42.625  1030  1387 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-05 14:14:42.625  1030  1387 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5,
08-05 14:14:42.625  1030  1387 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-05 14:14:42.625  1030  1387 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-05 14:14:42.626  1938  1938 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-05 14:14:42.627  1030  1387 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-05 14:14:42.627  1030  1387 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-05 14:14:42.627  1030  1387 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
,08-05 14:14:42.627  1030  1387 D WifiNative-HAL: p2pGetDeviceAddress
,08-05 14:14:42.627  1030  1387 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-05 14:14:42.628  1030  1387 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-05 14:14:42.628  1030  1387 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-05 14:14:42.628  1938  1938 D WfdsService: isConnected: false
08-05 14:14:42.629  1938  1938 I WfdStateTracker: handleP2pThisDeviceChanged
08-05 14:14:42.629  1938  1938 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-05 14:14:42.630  1938  1938 D WfdsService: Update P2p Interface State: 3
08-05 14:14:42.630  1030  1387 D WifiNative-p2p0: P2P_FLUSH: returned true
08-05 14:14:42.630  1030  1387 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-05 14:14:42.630  1030  1387 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-05 14:14:42.630  1030  1387 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-05 14:14:42.631  1030  1387 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-05 14:14:42.631  1030  1387 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-05 14:14:42.631  7002  7002 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 14:14:42.632  1030  1389 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-05 14:14:42.632  1030  1389 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-05 14:14:42.633  1030  1389 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-05 14:14:42.633  1030  1389 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-05 14:14:42.636  7117  7899 W FormManager: Network not available. Please check & try again.
08-05 14:14:42.639  7875  7875 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-05 14:14:42.639  1030  1387 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-05 14:14:42.640  1030  1387 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-05 14:14:42.640  1030  1387 D LGWifiP2pService: InactiveState
08-05 14:14:42.640  1030  1389 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-05 14:14:42.640  1030  1387 D LGWifiP2pService: InactiveState{ when=-9ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-05 14:14:42.640  1030  1387 D LGWifiP2pService: P2pEnabledState{ when=-9ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-05 14:14:42.640  1030  1387 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-05 14:14:42.640  1030  1389 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-05 14:14:42.641  1030  1389 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-05 14:14:42.641  1030  1389 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-05 14:14:42.641  7875  7875 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-05 14:14:42.641  7875  7875 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 14:14:42.642  1938  7901 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
,08-05 14:14:42.642  7875  7875 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-05 14:14:42.642  7875  7875 E wpa_supplicant: disconnect_rssi_lvl: -100
08-05 14:14:42.642  7875  7875 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 14:14:42.643  1030  1389 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=368383  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-05 14:14:42.643  7875  7875 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 14:14:42.644  1030  7897 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-05 14:14:42.644  1030  7897 E WifiMonitor: WifiMonitor:p2p0 cnt=36 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 14:14:42.644  1030  7897 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 14:14:42.644  1030  7897 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 14:14:42.644  1030  7897 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 14:14:42.644  1030  7897 E WifiMonitor: WifiMonitor:p2p0 cnt=37 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 14:14:42.644  1030  7897 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 14:14:42.644  1030  7897 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 14:14:42.644  1030  7897 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 14:14:42.644  1030  7897 E WifiMonitor: WifiMonitor:p2p0 cnt=38 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 14:14:42.644  1030  7897 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 14:14:42.644  7117  7900 V FormManager: Network unavailable.
08-05 14:14:42.644  1030  7897 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 14:14:42.644  1938  7901 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 14:14:42.645  1938  7901 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 14:14:42.645  1030  1387 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-05 14:14:42.645  1030  1387 D LGWifiP2pService: InactiveState{ when=-6ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-05 14:14:42.645  1030  1387 D LGWifiP2pService: P2pEnabledState{ when=-6ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-05 14:14:42.645  1030  1387 D LGWifiP2pService: DefaultState{ when=-6ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-05 14:14:42.645  1030  1387 D LGWifiP2pService: InactiveState{ when=-6ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-05 14:14:42.645  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 14:14:42.645  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 14:14:42.645  1030  1387 D LGWifiP2pService: P2pEnabledState{ when=-6ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-05 14:14:42.645  1030  1387 D LGWifiP2pService: DefaultState{ when=-6ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-05 14:14:42.646  1030  1387 D LGWifiP2pService: InactiveState{ when=-6ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-05 14:14:42.646  1030  1387 D LGWifiP2pService: P2pEnabledState{ when=-6ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-05 14:14:42.646  1030  1387 D LGWifiP2pService: DefaultState{ when=-6ms what=139287 arg2=5 target=com.android.inter,nal.util.StateMachine$SmHandler }
08-05 14:14:42.646  1030  1387 D LGWifiP2pService: InactiveState{ when=-6ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-05 14:14:42.646  1030  1387 D LGWifiP2pService: P2pEnabledState{ when=-6ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-05 14:14:42.646  1030  1387 D LGWifiP2pService: DefaultState{ when=-7ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-05 14:14:42.647  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 14:14:42.647  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 14:14:42.647  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 14:14:42.647  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-05 14:14:42.647  1030  1030 E WifiServerServiceExt: No p2p device connected
08-05 14:14:42.647  1938  2301 W WfdsService: DefaultState - msg [9441285] is not handled
08-05 14:14:42.648  1030  1389 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=368388  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-05 14:14:42.648  1030  1389 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-05 14:14:42.649  1030  1389 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-05 14:14:42.649  1030  1389 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-05 14:14:42.649  1030  1389 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-05 14:14:42.652  7875  7875 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-05 14:14:42.652  7875  7875 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 14:14:42.653  7875  7875 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-05 14:14:42.653  7875  7875 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 14:14:42.653  1030  7897 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-05 14:14:42.653  1030  7897 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 14:14:42.653  1030  7897 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 14:14:42.653  1030  7897 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,08-05 14:14:42.653  1030  7897 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 14:14:42.653  1030  1389 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-05 14:14:42.653  1030  7897 E WifiMonitor: WifiMonitor:p2p0 cnt=40 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 14:14:42.653  1030  7897 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 14:14:42.653  1030  7897 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,08-05 14:14:42.654  7875  7875 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 14:14:42.654  1938  7901 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 14:14:42.654  1938  7901 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 14:14:42.654  1030  1389 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-05 14:14:42.654  1030  7897 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 14:14:42.654  1030  7897 E WifiMonitor: WifiMonitor:p2p0 cnt=41 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 14:14:42.654  1030  7897 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 14:14:42.654  1030  7897 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 14:14:42.654  1030  1389 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-05 14:14:42.655  1030  1387 D LGWifiP2pService: InactiveState{ when=-1ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-05 14:14:42.655  1030  1387 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-05 14:14:42.655  7117  7900 V FormManager: Network unavailable.
08-05 14:14:42.657  4803  4803 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-05 14:14:42.658  4803  4803 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-05 14:14:42.658  1030  1389 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-05 14:14:42.658  1030  1389 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-05 14:14:42.658  7875  7875 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-05 14:14:42.658  7875  7875 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-05 14:14:42.659  1030  1389 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-05 14:14:42.659  1030  1389 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-05 14:14:42.659  4803  4803 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-05 14:14:42.659  1030  1389 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-05 14:14:42.660  1030  1389 D WifiNative-wlan0: doBoolean: SCAN
08-05 14:14:42.660  1030  1389 D WifiNative-wlan0: SCAN: returned false
08-05 14:14:42.661  1030  1389 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=368401  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-05 14:14:42.661  1030  7897 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-05 14:14:42.661  1030  7897 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-05 14:14:42.661  1030  7897 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-05 14:14:42.661  1030  7897 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-05 14:14:42.663  1030  1389 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=368403  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-05 14:14:42.664  1030  1389 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-05 14:14:42.664  1030  1389 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-05 14:14:42.665  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 14:14:42.665  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 14:14:42.665  1030  1389 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-05 14:14:42.665  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-05 14:14:42.665  1030  1389 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-05 14:14:42.666  1030  1389 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-05 14:14:42.666  1030  1030 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 14:14:42.666  1030  1030 D WifiServerServiceExt: setSupplicantStateSCANNING
08-05 14:14:42.668  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 14:14:42.668  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 14:14:42.668  1030  1030 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 14:14:42.668  1030  1030 D WifiServerServiceExt: setSupplicantStateSCANNING
08-05 14:14:42.669  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-05 14:14:42.670  4803  4803 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 14:14:42.676  7481  7481 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-05 14:14:42.676  7481  7481 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
08-05 14:14:42.676  7481  7481 V [BNRBootReceiver]: Boot Receiver Return
08-05 14:14:42.677  4803  7902 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-05 14:14:42.678  4803  7903 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-05 14:14:42.678  4803  7903 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-05 14:14:42.680  6408  6408 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-05 14:14:42.689  7002  7002 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 14:14:42.694  7002  7002 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 14:14:42.695  6923  6984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 14:14:42.695  6923  6984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 14:14:42.695  6923  6984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 14:14:42.695  6923  6984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 14:14:42.695  6923  6984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 14:14:42.695  6923  6984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 14:14:42.695  6923  6984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 14:14:42.695  6923  6984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 14:14:42.700  6923  6984 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-05 14:14:42.700  7079  7079 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 14:14:42.700  7079  7079 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 14:14:42.701  7079  7079 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-05 14:14:42.704  6923  6984 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-05 14:14:42.705  6923  6984 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-05 14:14:42.705  6408  6408 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 14:14:42.707  6923  6984 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@373f02ef Bundle[{}]
08-05 14:14:42.708  6923  6984 I io.jxcore.node.LifeCycleMonitor: start: OK
08-05 14:14:42.708  6923  6984 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-05 14:14:42.709  6923  6984 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-05 14:14:42.710  6923  6984 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-05 14:14:42.710  6923  6984 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-05 14:14:42.711  6923  6984 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-05 14:14:42.712  7002  7002 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 14:14:42.717  6923  6984 I System.out: Running OutgoingSocketThread
08-05 14:14:42.718  7002  7002 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 14:14:42.720  6923  7904 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 906)
08-05 14:14:42.722  6923  7904 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 50278
08-05 14:14:42.723  7079  7079 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 14:14:42.724  7079  7079 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 14:14:42.724  6923  7904 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-05 14:14:42.725  7079  7079 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-05 14:14:43.133  7875  7875 E wpa_supplicant: USIM:  scard_init function
08-05 14:14:43.133  7875  7875 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-05 14:14:43.135  1030  7897 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-05 14:14:43.135  1030  7897 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-05 14:14:43.135  1030  7897 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-05 14:14:43.135  1030  7897 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: WPS-AP-AVAILABLE 
08-05 14:14:43.135  1030  7897 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-05 14:14:43.136  1030  7897 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-05 14:14:43.136  1030  7897 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-05 14:14:43.136  1030  1389 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=6 bcn=0
08-05 14:14:43.137  1030  1389 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=6 bcn=0
08-05 14:14:43.137  1030  1389 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=6 bcn=0
08-05 14:14:43.138  1030  1389 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=6 bcn=0
,08-05 14:14:43.138  1030  1389 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
,08-05 14:14:43.167  1030  1389 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=368907  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-05 14:14:43.174  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 14:14:43.174  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 14:14:43.175  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 14:14:43.181  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 14:14:43.181  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 14:14:43.181  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,08-05 14:14:43.185  1030  1389 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=368925  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-05 14:14:43.186  1030  1030 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 14:14:43.186  1030  1030 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-05 14:14:43.190  7002  7002 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-05 14:14:43.201  7002  7002 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-05 14:14:43.206  6408  6408 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-05 14:14:43.219  7002  7002 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 14:14:43.227  7002  7002 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 14:14:43.235  7079  7079 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 14:14:43.236  7079  7079 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 14:14:43.236  7079  7079 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-05 14:14:43.260  7875  7875 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-05 14:14:43.268  1030  7897 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-05 14:14:43.268  1030  7897 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-05 14:14:43.269  1030  7897 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-05 14:14:43.269  1030  7897 E WifiMonitor: WifiMonitor:wlan0 cnt=47 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-05 14:14:43.269  1030  7897 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-05 14:14:43.269  1030  7897 E WifiMonitor: WifiMonitor:wlan0 cnt=48 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-05 14:14:43.275  7875  7875 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-05 14:14:43.275  7875  7875 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,08-05 14:14:43.282  1030  1389 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=369021  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-05 14:14:43.283  1030  1389 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=369023  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-05 14:14:43.284  1030  7897 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-05 14:14:43.284  1030  7897 E WifiMonitor: WifiMonitor:wlan0 cnt=49 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-05 14:14:43.284  1030  7897 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-05 14:14:43.284  1030  7897 E WifiMonitor: WifiMonitor:wlan0 cnt=50 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-05 14:14:43.284  1030  7897 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-05 14:14:43.284  1030  7897 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-05 14:14:43.284  1030  7897 E WifiMonitor: WifiMonitor:wlan0 cnt=51 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-05 14:14:43.285  1030  7897 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-05 14:14:43.285  1030  7897 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-05 14:14:43.285  1030  7897 E WifiMonitor: WifiMonitor:wlan0 cnt=52 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-05 14:14:43.287  1030  1389 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 47 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=369027
08-05 14:14:43.288  1030  1389 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 47 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=369028
08-05 14:14:43.288  1030  1389 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 47 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=369028
08-05 14:14:43.289  1030  1389 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 47 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=369029
08-05 14:14:43.289  1030  1389 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 47 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=369029
08-05 14:14:43.290  1030  1389 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 48 0 rt=369029  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
,08-05 14:14:43.306  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 14:14:43.306  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-05 14:14:43.309  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 14:14:43.311  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 14:14:43.311  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 14:14:43.311  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-05 14:14:43.314  6408  6408 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-05 14:14:43.316  1030  1389 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 48 0 rt=369056  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-05 14:14:43.321  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 14:14:43.321  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-05 14:14:43.321  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-05 14:14:43.328  1030  1094 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-05 14:14:43.329  1030  1389 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 49 0 rt=369069  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-05 14:14:43.330  1030  1030 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 14:14:43.330  1030  1030 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-05 14:14:43.330  1030  1389 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 49 0 rt=369070  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-05 14:14:43.331  1030  1389 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=369071
08-05 14:14:43.332  1030  1389 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=369072
08-05 14:14:43.332  1030  1389 D WifiNative-wlan0: doString: [STATUS]
08-05 14:14:43.333  1030  7897 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-05 14:14:43.333  1030  7897 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,08-05 14:14:43.335  7002  7002 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-05 14:14:43.336  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 14:14:43.336  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 14:14:43.336  1030  1389 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-05 14:14:43.337  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 14:14:43.338  1030  1389 I WifiServiceExtension: setVHTCapabilityType  : false
08-05 14:14:43.342  7002  7002 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 14:14:43.345  1030  1389 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-05 14:14:43.345  1030  1389 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-05 14:14:43.350  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 14:14:43.350  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 14:14:43.350  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,08-05 14:14:43.354  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 14:14:43.354  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 14:14:43.354  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-05 14:14:43.357  1030  1389 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-05 14:14:43.357  1030  1389 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-05 14:14:43.358  1030  1403 D ConnectivityService: Got NetworkAgent Messenger
08-05 14:14:43.358  1030  1403 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-05 14:14:43.358  1030  1403 D ConnectivityService: NetworkAgent connected
08-05 14:14:43.359  1030  1389 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-05 14:14:43.361  1030  1389 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-05 14:14:43.361  1030  1389 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-05 14:14:43.362  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 14:14:43.362  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-05 14:14:43.363  7079  7079 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 14:14:43.363  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 14:14:43.363  7079  7079 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 14:14:43.364  7079  7079 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-05 14:14:43.366  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 14:14:43.366  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 14:14:43.367  1030  1389 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-05 14:14:43.367  1030  1389 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-05 14:14:43.367  1030  1389 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-05 14:14:43.367  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 14:14:43.367  1030  1389 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-05 14:14:43.367  1030  1389 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-05 14:14:43.370  1030  1389 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-05 14:14:43.370  6408  6408 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 14:14:43.372   308   895 D CommandListener: Setting iface cfg
08-05 14:14:43.375  1030  1389 E WifiStateMachine: Start Dhcp Watchdog 2
08-05 14:14:43.375  1030  7932 D DhcpStateMachine: StoppedState
08-05 14:14:43.375  1030  7932 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-05 14:14:43.375  1030  7932 D DhcpStateMachine: WaitBeforeStartState
,08-05 14:14:43.375  1030  1389 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 52 0 rt=369115  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-05 14:14:43.376  1030  1389 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 52 0 rt=369116  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-05 14:14:43.376  1030  1389 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 52 0 rt=369116  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-05 14:14:43.377  1030  1030 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 14:14:43.377  1030  1030 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-05 14:14:43.378  1030  1389 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-05 14:14:43.378  1030  1389 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-05 14:14:43.379  1030  1389 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-05 14:14:43.379  1030  1389 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-05 14:14:43.380  1030  1389 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-05 14:14:43.380  1030  1389 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-05 14:14:43.381  1030  1030 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 14:14:43.382  1030  1030 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-05 14:14:43.382  7002  7002 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-05 14:14:43.382  1030  1389 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 53 0 rt=369122  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-05 14:14:43.383  1030  1389 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 53 0 rt=369123  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-05 14:14:43.383  1030  1389 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 53 0 rt=369123  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-05 14:14:43.384  1030  1389 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:322927] from screen [on:0 period:1520468152] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-05 14:14:43.385  1030  1389 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1520468153] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-05 14:14:43.385  1030  1389 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-05 14:14:43.388  7002  7002 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-05 14:14:43.390  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 14:14:43.391  1030  1389 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 14:14:43.391  1030  1403 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-05 14:14:43.391  1030  1389 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 14:14:43.392  1030  1389 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 14:14:43.392  1030  1389 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 14:14:43.393  1030  1389 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 14:14:43.393  1030  1389 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 14:14:43.393  1030  1403 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-05 14:14:43.394  1030  1389 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=139,0,0
08-05 14:14:43.394  1030  1389 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=139,0,0
08-05 14:14:43.394  1030  1389 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-05 14:14:43.394  7079  7079 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 14:14:43.394  7875  7875 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-05 14:14:43.395  7079  7079 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 14:14:43.395  1030  1389 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-05 14:14:43.395  1030  1389 D WifiNative-wlan0: doBoolean: SET ps 0
08-05 14:14:43.395  7079  7079 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-05 14:14:43.397  7002  7002 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-05 14:14:43.397  7002  7002 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-05 14:14:43.397  1030  1389 D WifiNative-wlan0: SET ps 0: returned true
08-05 14:14:43.397  7002  7002 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-05 14:14:43.397  1030  1389 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-05 14:14:43.397  7002  7002 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-05 14:14:43.397  7875  7875 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-05 14:14:43.398  1030  1389 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-05 14:14:43.398  1030  1389 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-05 14:14:43.398  1030  1389 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-05 14:14:43.398  1030  1389 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-05 14:14:43.398  1030  1387 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@ac3b0c0 target=com.android.internal.util.StateMachine$SmHandler }
08-05 14:14:43.398  1030  1387 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@ac3b0c0 target=com.android.internal.util.StateMachine$SmHandler }
08-05 14:14:43.398  1030  7932 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-05 14:14:43.398  1030  7932 D DhcpStateMachine: DHCP Start wake lock is acquired.
,08-05 14:14:43.399  7002  7002 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-05 14:14:43.400   308   895 D CommandListener: Setting iface cfg
08-05 14:14:43.401   308   895 D CommandListener: Trying to bring up wlan0
08-05 14:14:43.401  1030  1389 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-05 14:14:43.402  7002  7002 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-05 14:14:43.402  7002  7002 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-05 14:14:43.402  7002  7002 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-05 14:14:43.402  7002  7002 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-05 14:14:43.402  7002  7002 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-05 14:14:43.402  1030  1030 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 14:14:43.402  1030  1030 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-05 14:14:43.402  7002  7002 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-05 14:14:43.402  7002  7002 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-05 14:14:43.403  1030  1389 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK 
08-05 14:14:43.403  1030  1030 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 14:14:43.403  1030  1030 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-05 14:14:43.403  1030  1389 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK 
08-05 14:14:43.403  1030  1389 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-05 14:14:43.403  1030  1387 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-05 14:14:43.403  1030  1387 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-05 14:14:43.403  7875  7875 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-05 14:14:43.404  1030  1389 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-05 14:14:43.404  1030  1389 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-05 14:14:43.404  7875  7875 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-05 14:14:43.404  1030  1389 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-05 14:14:43.404  1030  1389 D WifiNative-wlan0: doBoolean: SET ps 1
08-05 14:14:43.407  6408  6408 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 14:14:43.412  7002  7002 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 14:14:43.415  7002  7002 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 14:14:43.420  7079  7079 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 14:14:43.420  7079  7079 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-05 14:14:43.420  7079  7079 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-05 14:14:43.422  1030  1389 D WifiNative-wlan0: SET ps 1: returned true
08-05 14:14:43.423  1030  1389 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-05 14:14:43.423  1030  1389 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-05 14:14:43.423  6408  6408 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 14:14:43.423  1030  1389 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-05 14:14:43.424  1030  1403 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-05 14:14:43.424  1030  1389 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-05 14:14:43.424  1030  1389 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-05 14:14:43.424  1030  1389 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-05 14:14:43.425  1030  1403 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-05 14:14:43.425  1030  1389 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-05 14:14:43.425  1030  1389 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-05 14:14:43.425  1030  1389 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-05 14:14:43.426  1030  1403 D ConnectivityService: ignoring duplicate network state non-change
08-05 14:14:43.429  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 14:14:43.429  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 14:14:43.430  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 14:14:43.430  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 14:14:43.430  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 14:14:43.430  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-05 14:14:43.432  1030  1403 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-05 14:14:43.432  1030  1403 D ConnectivityService: Adding iface wlan0 to network 101
,08-05 14:14:43.437  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-05 14:14:43.437  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 14:14:43.437  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-05 14:14:43.441  1030  1030 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-05 14:14:43.442  1938  1938 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-05 14:14:43.444  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 14:14:43.444  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 14:14:43.444  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-05 14:14:43.444  1030  1389 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-05 14:14:43.445  1030  1030 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-05 14:14:43.445  7002  7002 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-05 14:14:43.447  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 14:14:43.447  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 14:14:43.447  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,08-05 14:14:43.450  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 14:14:43.450  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 14:14:43.451  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 14:14:43.452  1030  1403 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-05 14:14:43.452  1030  1403 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-05 14:14:43.453  1030  1403 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-05 14:14:43.453   308   895 E Netd    : netlink response contains error (File exists)
08-05 14:14:43.454  1030  1403 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-05 14:14:43.454  1030  1403 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-05 14:14:43.454  1030  1403 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-05 14:14:43.454  1030  1403 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-05 14:14:43.455  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 14:14:43.455  1600  1600 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-05 14:14:43.455  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 14:14:43.455  1030  1403 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-05 14:14:43.455  1030  1403 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-05 14:14:43.455  1030  1403 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-05 14:14:43.455  1030  1403 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-05 14:14:43.455  1030  7931 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-05 14:14:43.455  1030  1403 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-05 14:14:43.455  1030  7931 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-05 14:14:43.455  1030  1403 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 14:14:43.456  1030  1403 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-05 14:14:43.456  1030  7931 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-05 14:14:43.456  1030  1403 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 14:14:43.456  1030  7931 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-05 14:14:43.456  1030  1403 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-05 14:14:43.456  1030  1403 D ConnectivityService: currentScore = 0, newScore = 20
08-05 14:14:43.456  1030  1403 D ConnectivityService:    accepting network in place of null
08-05 14:14:43.456  1030  1403 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08,-05 14:14:43.456  1849  1849 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 14:14:43.456  1849  1849 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-05 14:14:43.457  1030  1389 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 14:14:43.457  1030  1389 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-05 14:14:43.458  1030  1403 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-05 14:14:43.458  1030  1403 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-05 14:14:43.458   308  7936 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-05 14:14:43.458  1030  1403 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-05 14:14:43.460  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 14:14:43.460  1600  1600 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-05 14:14:43.460  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 14:14:43.462  7002  7002 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-05 14:14:43.466  1030  1030 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
,08-05 14:14:43.466  1030  1030 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-05 14:14:43.466  1030  1030 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-05 14:14:43.466  1030  1030 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-05 14:14:43.468  1030  1403 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-05 14:14:43.468  1030  1403 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-05 14:14:43.469  1030  1403 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-05 14:14:43.470  1030  1403 D ConnectivityService: validation of new default Network = false
08-05 14:14:43.470  1030  1403 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-05 14:14:43.470  1030  1403 D DSQN    : enableDataServiceNotify 
08-05 14:14:43.470  1030  1403 D DSQN    : start dsqn bin
08-05 14:14:43.474  1030  1403 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-05 14:14:43.474  1030  1403 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 14:14:43.474  1030  1403 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 14:14:43.474  1030  1403 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 14:14:43.470  7937  7937 W dsqn    : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 14:14:43.470  7937  7937 W dsqn    : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-05 14:14:43.476  1600  1825 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-05 14:14:43.481  7079  7079 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 14:14:43.481  7079  7079 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 14:14:43.481  7079  7079 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-05 14:14:43.488  7937  7937 E DSQN    : DSQN ssw
,08-05 14:14:43.493  6408  6408 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 14:14:43.497  1813  7940 I CheckinService: active receiver: enabled
,08-05 14:14:43.505  1813  7940 I CheckinService: Preparing to send checkin request
08-05 14:14:43.506  1813  7940 I EventLogService: Accumulating logs since 1470398956672
08-05 14:14:43.509  1030  1386 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-05 14:14:43.510  7002  7002 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-05 14:14:43.514  7002  7002 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 14:14:43.520  7079  7079 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-05 14:14:43.520  7079  7079 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 14:14:43.521   308  7936 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-05 14:14:43.521  1600  1600 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-05 14:14:43.522  7079  7079 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-05 14:14:43.522  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 14:14:43.523  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 14:14:43.524  6408  6408 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 14:14:43.529  7002  7002 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 14:14:43.534  7002  7002 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 14:14:43.538  7079  7079 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 14:14:43.539  7079  7079 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 14:14:43.539  7079  7079 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-05 14:14:43.542  6408  6408 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 14:14:43.544  7045  7045 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-05 14:14:43.546  7045  7045 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-05 14:14:43.549  7002  7002 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-05 14:14:43.554  7002  7002 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 14:14:43.556  1813  7940 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-05 14:14:43.560  7079  7079 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 14:14:43.560  7079  7079 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 14:14:43.561   308  7936 D libc-netbsd: res_queryN name = clients3.google.com succeed
08-05 14:14:43.561  7079  7079 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-05 14:14:43.562  7079  7079 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-05 14:14:43.562  7079  7079 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-05 14:14:43.567  6408  6408 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-05 14:14:43.573  7045  7045 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-05 14:14:43.573  7045  7045 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-05 14:14:43.576  7002  7002 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-05 14:14:43.579  7002  7002 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-05 14:14:43.587  7079  7079 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-05 14:14:43.587  7079  7079 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 14:14:43.588  7079  7079 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-05 14:14:43.588  7079  7079 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-05 14:14:43.589  7079  7079 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-05 14:14:43.607  1030  7932 D DhcpStateMachine: DHCPV4 request on wlan0
,08-05 14:14:43.608  1030  7932 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-05 14:14:43.608  1030  7932 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-05 14:14:43.611   308   894 D LGDataListener: argv[0]=dsqncommand
08-05 14:14:43.611   308   894 D LGDataListener: argv[1]=wlan0
08-05 14:14:43.611   308   894 D LGDataListener: argv[2]=1
08-05 14:14:43.611   308   894 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-05 14:14:43.612  1030  1092 D DSQN    : DSQM DsqnNotification wlan0  1
08-05 14:14:43.612  1030  1092 D DSQN    : start to monitor internet connection
08-05 14:14:43.610  7946  7946 W dhcpcd  : type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 14:14:43.610  7946  7946 W dhcpcd  : type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 14:14:43.624  7946  7946 I dhcpcd  : version 5.5.6 starting
,08-05 14:14:43.626  7946  7946 E dhcpcd  : get_duid: m
08-05 14:14:43.626  7946  7946 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-05 14:14:43.626  7946  7946 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-05 14:14:43.657  1030  7931 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 05 Aug 2016 12:14:43 GMT], X-Android-Received-Millis=[1470399283657], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1470399283611]}
08-05 14:14:43.658  1030  7931 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-05 14:14:43.658  1030  7931 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-05 14:14:43.658  1030  1403 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-05 14:14:43.658  1030  1403 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-05 14:14:43.658  1030  1403 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-05 14:14:43.658  1030  1403 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 14:14:43.658  1030  1403 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-05 14:14:43.658  1030  1403 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-05 14:14:43.659  1030  1403 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-05 14:14:43.659  1030  1403 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 14:14:43.659  1030  1403 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 14:14:43.659  1030  1403 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 14:14:43.659  1030  1403 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 14:14:43.660  1600  1825 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-05 14:14:43.660  1030  1403 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-05 14:14:43.660  1030  1389 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 14:14:43.660  1030  1389 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-05 14:14:43.661  1849  1849 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 14:14:43.661  1849  1849 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,08-05 14:14:43.690  1600  1600 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-05 14:14:43.691  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 14:14:43.693  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 14:14:43.719  6923  6984 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 907)
08-05 14:14:43.719  6923  6984 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 907)
,08-05 14:14:43.724  6923  6984 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 912)
08-05 14:14:43.725  7946  7946 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-05 14:14:43.725  6923  6984 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-05 14:14:43.725  6923  6984 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 913)
08-05 14:14:43.725  7946  7946 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-05 14:14:43.726  7946  7946 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-05 14:14:43.726  7946  7946 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
08-05 14:14:43.727  7946  7946 D dhcpcd  : wlan0: sending REQUEST (xid 0xf5487f5c), next in 4.83 seconds
08-05 14:14:43.729  6923  6984 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 14:14:43.729  6923  6984 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f13e3fa added. We now have 2 listener(s)
08-05 14:14:43.729  1030  1046 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 14:14:43.732  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-05 14:14:43.732  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 14:14:43.732  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 14:14:43.732  6923  6984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 14:14:43.732  6923  6984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@84a6dab added. We now have 9 listener(s)
08-05 14:14:43.732  6923  6984 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-05 14:14:43.733  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-05 14:14:43.736  6923  6984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 14:14:43.743  6923  6984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 14:14:43.743  6923  6984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 14:14:43.743  6923  6984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 14:14:43.743  6923  6984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 14:14:43.743  6923  6984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 14:14:43.743  6923  6984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 14:14:43.743  6923  6984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 14:14:43.743  6923  6984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 14:14:43.747  6923  6984 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-05 14:14:43.748  6923  6984 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-05 14:14:43.748  6923  6984 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 14:14:43.748  6923  6984 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c91efa1 added. We now have 3 listener(s)
08-05 14:14:43.748  1030  1951 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 14:14:43.749  6923  6923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 14:14:43.751  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-05 14:14:43.751  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 14:14:43.751  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 14:14:43.751  6923  6923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 14:14:43.751  6923  6984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 14:14:43.751  6923  6984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38ac45c6 added. We now have 10 listener(s)
08-05 14:14:43.751  6923  6984 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 14:14:43.751  6923  6984 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 14:14:43.751  6923  6984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 14:14:43.751  6923  6984 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 14:14:43.751  6923  6984 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 14:14:43.751  6923  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:43.751  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 14:14:43.751  6923  6984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 14:14:43.751  6923  6984 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f13e3fa removed from the list
08-05 14:14:43.752  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:43.752  6923  6984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@84a6dab removed from the list
08-05 14:14:43.752  6923  6984 D io.jxcore.node.ConnectivityMonitor: stop
08-05 14:14:43.752  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:43.752  6923  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:43.752  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:43.752  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 14:14:43.752  6923  6984 I org.thaliproject.p2p.btconnecto,rlib.DiscoveryManager: stopDiscovery
08-05 14:14:43.752  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:43.753  6923  6984 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@84a6dab not in the list
08-05 14:14:43.753  6923  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:43.753  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:43.753  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 14:14:43.753  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 14:14:43.753  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:43.753  6923  6984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38ac45c6 removed from the list
08-05 14:14:43.753  6923  6984 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 14:14:43.753  6923  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:43.753  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:43.753  6923  6984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 14:14:43.753  6923  6984 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c91efa1 removed from the list
08-05 14:14:43.754  6923  6984 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 14:14:43.754  6923  6984 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bc03987 added. We now have 2 listener(s)
08-05 14:14:43.754  1030  1992 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 14:14:43.755  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-05 14:14:43.755  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 14:14:43.755  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 14:14:43.755  6923  6984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 14:14:43.755  6923  6984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27c9d0b4 added. We now have 9 listener(s)
08-05 14:14:43.755  6923  6984 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 14:14:43.756  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-05 14:14:43.757  6923  6984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 14:14:43.760  6923  6984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 14:14:43.760  6923  6984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 14:14:43.760  6923  6984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertis,ement supported: NOT_SUPPORTED
08-05 14:14:43.760  6923  6984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 14:14:43.760  6923  6984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 14:14:43.760  6923  6984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 14:14:43.760  6923  6984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 14:14:43.760  6923  6984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 14:14:43.761  6923  6984 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-05 14:14:43.761  6923  6984 D io.jxcore.node.ConnectivityMonitor: start: OK
08-05 14:14:43.762  6923  6923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 14:14:43.762  6923  6984 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 14:14:43.762  6923  6984 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@716f852 added. We now have 3 listener(s)
08-05 14:14:43.763  1030  1045 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 14:14:43.763  6923  6923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 14:14:43.765  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-05 14:14:43.765  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 14:14:43.765  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 14:14:43.766  6923  6984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 14:14:43.766  6923  6984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25dce723 added. We now have 10 listener(s)
08-05 14:14:43.766  6923  6984 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 14:14:43.766  6923  6984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-05 14:14:43.766  6923  6984 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-05 14:14:43.766  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-05 14:14:43.766  6923  6984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 14:14:43.766  6923  6984 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-05 14:14:43.769  6923  6984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-05 14:14:43.769  1030  1957 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 14:14:43.770  7946  7946 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
08-05 14:14:43.771  6923  6984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-05 14:14:43.772  6923  6984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-05 14:14:43.773  6923  6984 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-05 14:14:43.773  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 14:14:43.774  6923  6984 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-05 14:14:43.774  6923  6984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 14:14:43.774  6923  6984 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 14:14:43.775  6923  6984 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 14:14:43.775  6923  6984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 14:14:43.775  6923  6984 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 14:14:43.776  6923  6984 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 14:14:43.776  6923  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:43.776  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 14:14:43.776  6923  6984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 14:14:43.776  6923  6984 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bc03987 removed from the list
08-05 14:14:43.776  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:43.776  6923  6984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27c9d0b4 removed from the list
08-05 14:14:43.776  6923  6984 D io.jxcore.node.ConnectivityMonitor: stop
08-05 14:14:43.776  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:43.776  6923  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:43.776  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:43.777  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 14:14:43.777  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 14:14:43.777  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:43.777  6923  6984 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27c9d0b4 not in the list
08-05 14:14:43.777  6923  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:43.777  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:43.778  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 14:14:43.778  6923  6984 D BluetoothLeScanner: could not find callback wrapper
08-05 14:14:43.778  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 14:14:43.778  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 14:14:43.778  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:43.778  6923  6984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25dce723 removed from the list
08-05 14:14:43.778  6923  6984 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 14:14:43.778  6923  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:43.778  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:43.778  6923  6984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 14:14:43.778  6923  6984 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@716f852 removed from the list
08-05 14:14:43.779  6923  6984 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 14:14:43.779  6923  6984 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@208479e added. We now have 2 listener(s)
08-05 14:14:43.779  1030  1992 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 14:14:43.781  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-05 14:14:43.781  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 14:14:43.781  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 14:14:43.781  6923  6984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 14:14:43.781  6923  6984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@258cd27f added. We now have 9 listener(s)
08-05 14:14:43.781  6923  6984 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 14:14:43.781  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-05 14:14:43.783  1030  1653 I art     : Explicit concurrent mark sweep GC freed 75479(3MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/64MB, paused 1.782ms total 191.348ms
08-05 14:14:43.783  6923  6984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 14:14:43.789  6923  6984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 14:14:43.789  6923  6984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 14:14:43.789  6923  6984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 14:14:43.789  6923  6984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 14:14:43.789  6923  6984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 14:14:43.789  6923  6984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 14:14:43.789  6923  6984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 14:14:43.789  6923  6984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-05 14:14:43.791  7946  7946 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
08-05 14:14:43.791  7946  7946 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
08-05 14:14:43.791  6923  6984 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-05 14:14:43.791  7946  7946 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-05 14:14:43.791  6923  6984 D io.jxcore.node.ConnectivityMonitor: start: OK
08-05 14:14:43.791  6923  6984 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 14:14:43.792  6923  6984 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@239cd295 added. We now have 3 listener(s)
08-05 14:14:43.792  7946  7946 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-05 14:14:43.792  7946  7946 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-05 14:14:43.792  7946  7946 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-05 14:14:43.792  1030  1986 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 14:14:43.792  7946  7946 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-05 14:14:43.792  7946  7946 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-05 14:14:43.793  6923  6923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 14:14:43.794  6923  6923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 14:14:43.796  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-05 14:14:43.796  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 14:14:43.796  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 14:14:43.796  6923  6984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 14:14:43.796  6923  6984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@262d3faa added. We now have 10 listener(s)
08-05 14:14:43.796  6923  6984 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 14:14:43.796  6923  6984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-05 14:14:43.796  6923  6984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-05 14:14:43.796  6923  6984 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-05 14:14:43.796  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-05 14:14:43.796  6923  6984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 14:14:43.796  6923  6984 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-05 14:14:43.799  6923  6984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-05 14:14:43.799  1030  1733 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 14:14:43.802  6923  6984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-05 14:14:43.802  6923  6984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-05 14:14:43.803  6923  6984 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-05 14:14:43.803  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 14:14:43.804  6923  6984 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-05 14:14:43.804  6923  6984 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 14:14:43.804  6923  6984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 14:14:43.804  6923  6984 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 14:14:43.805  6923  6984 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 14:14:43.805  6923  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:43.805  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 14:14:43.805  6923  6984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 14:14:43.805  6923  6984 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@208479e removed from the list
08-05 14:14:43.805  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:43.805  6923  6984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@258cd27f removed from the list
08-05 14:14:43.805  6923  6984 D io.jxcore.node.ConnectivityMonitor: stop
08-05 14:14:43.805  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:43.806  6923  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:43.806  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:43.807  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 14:14:43.807  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 14:14:43.807  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:43.807  6923  6984 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@258cd27f not in the list
08-05 14:14:43.807  6923  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:43.807  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:43.808  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 14:14:43.809  6923  6984 D BluetoothLeScanner: could not find callback wrapper
08-05 14:14:43.809  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 14:14:43.809  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 14:14:43.809  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:43.809  6923  6984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@262d3faa removed from the list
08-05 14:14:43.809  6923  6984 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 14:14:43.809  6923  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:43.809  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:43.809  6923  6984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 14:14:43.809  6923  6984 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@239cd295 removed from the list
08-05 14:14:43.810  6923  6984 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 14:14:43.811  6923  6984 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35c50311 added. We now have 2 listener(s)
08-05 14:14:43.811  1030  1735 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 14:14:43.814  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-05 14:14:43.814  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 14:14:43.815  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 14:14:43.815  6923  6984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 14:14:43.815  6923  6984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1bf7ac76 added. We now have 9 listener(s)
08-05 14:14:43.815  6923  6984 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 14:14:43.818  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-05 14:14:43.821  6923  6984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 14:14:43.831  6923  6984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 14:14:43.831  6923  6984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 14:14:43.831  6923  6984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 14:14:43.831  6923  6984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 14:14:43.831  6923  6984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 14:14:43.831  6923  6984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 14:14:43.831  6923  6984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 14:14:43.831  6923  6984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-05 14:14:43.833  6923  6984 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-05 14:14:43.833  6923  6984 D io.jxcore.node.ConnectivityMonitor: start: OK
08-05 14:14:43.833  6923  6984 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 14:14:43.833  6923  6984 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@18dccee4 added. We now have 3 listener(s)
08-05 14:14:43.833  1030  1934 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 14:14:43.835  6923  6923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 14:14:43.835  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-05 14:14:43.835  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 14:14:43.835  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 14:14:43.835  6923  6984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 14:14:43.835  6923  6984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@565bf4d added. We now have 10 listener(s)
08-05 14:14:43.835  6923  6984 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 14:14:43.835  6923  6984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-05 14:14:43.835  6923  6984 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-05 14:14:43.835  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-05 14:14:43.835  6923  6984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 14:14:43.835  6923  6984 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-05 14:14:43.837  6923  6923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 14:14:43.837  6923  6984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-05 14:14:43.882  1030  1733 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7962 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
08-05 14:14:43.882  1030  1957 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-05 14:14:43.892  6923  6984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-05 14:14:43.893  6923  6984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-05 14:14:43.894  6923  6984 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-05 14:14:43.895  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 14:14:43.896  6923  6984 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-05 14:14:43.899  6923  6984 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 14:14:43.899  6923  6984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 14:14:43.899  6923  6984 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 14:14:43.899  6923  6984 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 14:14:43.899  6923  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:43.899  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 14:14:43.899  6923  6984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 14:14:43.899  6923  6984 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35c50311 removed from the list
08-05 14:14:43.899  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:43.899  6923  6984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1bf7ac76 removed from the list
08-05 14:14:43.899  6923  6984 D io.jxcore.node.ConnectivityMonitor: stop
08-05 14:14:43.899  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:43.899  6923  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:43.899  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:43.900  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 14:14:43.900  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 14:14:43.900  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:43.900  6923  6984 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1bf7ac76 not in the list
08-05 14:14:43.900  6923  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:43.900  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:43.901  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 14:14:43.901  6923  6984 D BluetoothLeScanner: could not find callback wrapper
08-05 14:14:43.901  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 14:14:43.901  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 14:14:43.901  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:43.901  6923  6984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@565bf4d removed from the list
08-05 14:14:43.901  6923  6984 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 14:14:43.901  6923  6984 W org.thaliproject.p2p.btc,onnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:43.901  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:43.901  6923  6984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 14:14:43.901  6923  6984 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@18dccee4 removed from the list
08-05 14:14:43.902  6923  6984 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 14:14:43.902  6923  6984 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1909f550 added. We now have 2 listener(s)
08-05 14:14:43.902  1030  1592 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 14:14:43.904  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-05 14:14:43.904  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 14:14:43.904  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 14:14:43.904  6923  6984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 14:14:43.904  6923  6984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ddc0349 added. We now have 9 listener(s)
08-05 14:14:43.904  6923  6984 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 14:14:43.905  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-05 14:14:43.907  6923  6984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-05 14:14:43.911  6923  6984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 14:14:43.911  6923  6984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 14:14:43.911  6923  6984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 14:14:43.911  6923  6984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 14:14:43.911  6923  6984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 14:14:43.911  6923  6984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 14:14:43.911  6923  6984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 14:14:43.911  6923  6984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 14:14:43.912  6923  6984 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-05 14:14:43.912  6923  6984 D io.jxcore.node.ConnectivityMonitor: start: OK
08-05 14:14:43.913  6923  6984 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 14:14:43.913  6923  6984 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3345596f added. We now have 3 listener(s)
08-05 14:14:43.914  1030  1733 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 14:14:43.915  6923  6923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 14:14:43.916  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-05 14:14:43.916  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 14:14:43.916  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 14:14:43.916  6923  6923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 14:14:43.916  6923  6984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 14:14:43.916  6923  6984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10a1167c added. We now have 10 listener(s)
08-05 14:14:43.916  6923  6984 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 14:14:43.917  6923  6984 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 14:14:43.917  6923  6984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 14:14:43.917  6923  6984 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 14:14:43.917  6923  6984 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-05 14:14:43.917  6923  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:43.917  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 14:14:43.917  6923  6984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 14:14:43.917  6923  6984 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1909f550 removed from the list
08-05 14:14:43.917  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:43.917  6923  6984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ddc0349 removed from the list
08-05 14:14:43.917  6923  6984 D io.jxcore.node.ConnectivityMonitor: stop
08-05 14:14:43.917  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:43.918  6923  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:43.918  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:43.921  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 14:14:43.921  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 14:14:43.921  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:43.921  6923  6984 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ddc0349 not in the list
08-05 14:14:43.921  6923  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:43.921  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-05 14:14:43.922  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 14:14:43.922  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 14:14:43.922  6923  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:43.922  6923  6984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10a1167c removed from the list
08-05 14:14:43.922  6923  6984 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 14:14:43.922  6923  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:43.922  6923  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:43.922  6923  6984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 14:14:43.922  6923  6984 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3345596f removed from the list
08-05 14:14:43.923  6923  6984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-05 14:14:43.923  6923  6984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-05 14:14:43.923  6923  6984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-05 14:14:43.924  6923  6984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-05 14:14:43.924  6923  6984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-05 14:14:43.924  6923  6984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-05 14:14:43.934  6923  7983 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 920, name: My test thread name)
08-05 14:14:43.934  6923  7983 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 920, thread name: My test thread name)
08-05 14:14:43.935  6923  7983 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 920, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-05 14:14:43.938  6923  7984 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 922, name: My test thread name)
08-05 14:14:43.938  6923  7984 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 922, thread name: My test thread name)
08-05 14:14:43.938  6923  7984 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 922, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-05 14:14:43.940  6923  6984 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-05 14:14:43.940  6923  6984 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-05 14:14:43.940  6923  6984 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-05 14:14:43.940  6923  6984 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-05 14:14:43.941  6923  6984 D com.test.thalitest.ThaliTestRunner: Total duration: 23165 ms
08-05 14:14:43.942  6923  6984 I jxcore-log: Total number of executed tests:  80
08-05 14:14:43.942  6923  6984 I jxcore-log: 
08-05 14:14:43.942  6923  6984 I jxcore-log: Number of passed tests:  80
08-05 14:14:43.942  6923  6984 I jxcore-log: 
08-05 14:14:43.942  6923  6984 I jxcore-log: Number of failed tests:  0
08-05 14:14:43.942  6923  6984 I jxcore-log: 
08-05 14:14:43.942  6923  6984 I jxcore-log: Number of ignored tests:  0
08-05 14:14:43.942  6923  6984 I jxcore-log: 
08-05 14:14:43.943  6923  6984 I jxcore-log: Total duration:  23165
08-05 14:14:43.943  6923  6984 I jxcore-log: 
08-05 14:14:43.945  6923  6984 I jxcore-log: Unit Test app is loaded
08-05 14:14:43.945  6923  6984 I jxcore-log: 
08-05 14:14:43.952  6923  6984 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 14:14:43.952  6923  6984 I jxcore-log: 
,08-05 14:14:43.956  6923  6984 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 14:14:43.956  6923  6984 I jxcore-log: 
08-05 14:14:43.957  6923  6984 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 14:14:43.957  6923  6984 I jxcore-log: 
08-05 14:14:43.958  7962  7962 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-05 14:14:43.958  6923  6984 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 14:14:43.958  6923  6984 I jxcore-log: 
08-05 14:14:43.958  7962  7962 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
08-05 14:14:43.959  6923  6984 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 14:14:43.959  6923  6984 I jxcore-log: 
08-05 14:14:43.960  6923  6923 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
08-05 14:14:43.961  6923  6984 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 14:14:43.961  6923  6984 I jxcore-log: 
08-05 14:14:43.964  6923  6984 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-05 14:14:43.964  6923  6984 I jxcore-log: 
,08-05 14:14:43.966  6923  6984 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-05 14:14:43.966  6923  6984 I jxcore-log: 
08-05 14:14:43.967  6923  6984 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-05 14:14:43.967  6923  6984 I jxcore-log: 
08-05 14:14:43.968  6923  6984 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-05 14:14:43.968  6923  6984 I jxcore-log: 
08-05 14:14:43.969  6923  6984 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-05 14:14:43.969  6923  6984 I jxcore-log: 
08-05 14:14:43.970  6923  6984 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-05 14:14:43.970  6923  6984 I jxcore-log: 
08-05 14:14:43.971  6923  6984 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-05 14:14:43.971  6923  6984 I jxcore-log: 
08-05 14:14:43.972  6923  6984 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-05 14:14:43.972  6923  6984 I jxcore-log: 
08-05 14:14:43.972  6923  6984 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-05 14:14:43.972  6923  6984 I jxcore-log: 
08-05 14:14:43.973  6923  6984 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-05 14:14:43.973  6923  6984 I jxcore-log: 
08-05 14:14:43.974  6923  6984 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-05 14:14:43.974  6923  6984 I jxcore-log: 
08-05 14:14:43.974  6923  6984 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-05 14:14:43.974  6923  6984 I jxcore-log: 
08-05 14:14:43.975  6923  6984 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-05 14:14:43.975  6923  6984 I jxcore-log: 
,08-05 14:14:43.976  6923  6984 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-05 14:14:43.976  6923  6984 I jxcore-log: 
08-05 14:14:43.976  6923  6984 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-05 14:14:43.976  6923  6984 I jxcore-log: 
08-05 14:14:43.977  6923  6984 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-05 14:14:43.977  6923  6984 I jxcore-log: 
08-05 14:14:43.978  6923  6984 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-05 14:14:43.978  6923  6984 I jxcore-log: 
08-05 14:14:43.979  6923  6984 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 14:14:43.979  6923  6984 I jxcore-log: 
08-05 14:14:43.979  6923  6984 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 14:14:43.979  6923  6984 I jxcore-log: 
08-05 14:14:43.980  6923  6984 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 14:14:43.980  6923  6984 I jxcore-log: 
08-05 14:14:43.980  6923  6984 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 14:14:43.980  6923  6984 I jxcore-log: 
08-05 14:14:43.981  6923  6984 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 14:14:43.981  6923  6984 I jxcore-log: 
08-05 14:14:43.983  6923  6984 I jxcore-log: My device name is: LGE-LG-D855
08-05 14:14:43.983  6923  6984 I jxcore-log: 
08-05 14:14:43.984  6923  6984 I jxcore-log: WARN testUtils: myNameCallback not set!
08-05 14:14:43.984  6923  6984 I jxcore-log: 
08-05 14:14:43.985  7962  7962 I MultiDex: VM with version 2.1.0 has multidex support
08-05 14:14:43.985  7962  7962 I MultiDex: install
08-05 14:14:43.986  7962  7962 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-05 14:14:44.003  7962  7962 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,08-05 14:14:44.007  2185  2185 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-05 14:14:44.013  2185  2185 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
08-05 14:14:44.014  2185  2185 D c       : Getting all permits...
08-05 14:14:44.014  2185  2185 D a       : Opening database...
,08-05 14:14:44.015  1030  7932 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-05 14:14:44.016  1030  7932 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-05 14:14:44.016  1030  7932 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-05 14:14:44.017  1030  7932 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
08-05 14:14:44.017  1030  7932 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-05 14:14:44.017  1030  7932 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-05 14:14:44.017  1030  7932 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-05 14:14:44.017  1030  7932 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-05 14:14:44.017  2185  2185 D a       : Opening database auth.proximity.permit_store...
,08-05 14:14:44.017  1030  7932 D DhcpStateMachine: RunningState
,08-05 14:14:44.017  2185  2185 D a       : Closing database...
,08-05 14:14:44.381  7962  7979 D LgDataFeature: LgDataFeature() Constructor: none
08-05 14:14:44.381  7962  7979 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-05 14:14:44.566  7998  7998 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-05 14:14:44.655  7998  7998 I dex2oat : dex2oat took 88.931ms (threads: 4)
,08-05 14:14:44.671  7962  7979 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-05 14:14:44.671  7962  7979 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-05 14:14:44.671  7962  7979 I Adreno-EGL: Build Date: 12/12/14 금
08-05 14:14:44.671  7962  7979 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-05 14:14:44.671  7962  7979 I Adreno-EGL: Remote Branch: 
08-05 14:14:44.671  7962  7979 I Adreno-EGL: Local Patches: 
08-05 14:14:44.671  7962  7979 I Adreno-EGL: Reconstruct Branch: 
,08-05 14:14:44.704  1030  1389 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-05 14:14:44.704  1030  1389 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-05 14:14:44.704  1030  1389 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-05 14:14:44.705  1030  1389 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-05 14:14:44.705  1030  1389 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-05 14:14:44.706  1030  1389 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-05 14:14:44.708  1030  1403 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
,08-05 14:14:44.708  1030  1403 D ConnectivityService: identical MTU - not setting
08-05 14:14:44.708  1030  1403 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-05 14:14:44.709  1030  1403 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-05 14:14:44.709  1030  1403 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 14:14:44.709  1030  1403 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 14:14:44.711  1030  1403 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 14:14:44.718  1600  1825 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-05 14:14:44.797  7962  7979 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-05 14:14:44.797  7962  7979 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-05 14:14:44.797  7962  7979 I Adreno-EGL: Build Date: 12/12/14 금
08-05 14:14:44.797  7962  7979 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-05 14:14:44.797  7962  7979 I Adreno-EGL: Remote Branch: 
08-05 14:14:44.797  7962  7979 I Adreno-EGL: Local Patches: 
08-05 14:14:44.797  7962  7979 I Adreno-EGL: Reconstruct Branch: 
,08-05 14:14:44.897  7962  7979 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-05 14:14:44.897  7962  7979 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-05 14:14:44.897  7962  7979 I Adreno-EGL: Build Date: 12/12/14 금
08-05 14:14:44.897  7962  7979 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-05 14:14:44.897  7962  7979 I Adreno-EGL: Remote Branch: 
08-05 14:14:44.897  7962  7979 I Adreno-EGL: Local Patches: 
08-05 14:14:44.897  7962  7979 I Adreno-EGL: Reconstruct Branch: 
,08-05 14:14:44.997   308  8006 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-05 14:14:44.997   308  8006 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
,08-05 14:14:45.038   308  8006 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,08-05 14:14:45.206  1813  7940 I CheckinTask: Sending checkin request (7782 bytes)
,08-05 14:14:45.460  1813  7940 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,08-05 14:14:45.469  1813  7940 I CheckinService: active receiver: disabled
,08-05 14:14:45.504  2185  2185 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-05 14:14:45.520  2185  2185 I GCM     : GCM config loaded
,08-05 14:14:45.542  7281  7281 V SetupWizard: Connected to Gservices successfully
,08-05 14:14:45.546   308  8018 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-05 14:14:45.546   308  8018 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
08-05 14:14:45.579   308  8018 D libc-netbsd: res_queryN name = mtalk.google.com succeed
,08-05 14:14:45.926  2185  8021 D GCM     : Connected
,08-05 14:14:45.970  2185  8021 D GCM     : Message class com.google.e.a.a.q
,08-05 14:14:46.393  1030  1389 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=69.5, 0.0, 0.0  rx=58.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1520471160] gl rssi=-38 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-05 14:14:46.393  1030  1389 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=69.5, 0.0, 0.0  rx=58.5 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1520471161] gl rssi=-38 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-05 14:14:46.394  1030  1389 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-05 14:14:46.412  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-05 14:14:46.444  1030  1390 V WifiInternetCheck: Single check msg out of sync, ignoring.
,08-05 14:14:46.471  1030  1403 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-05 14:14:46.479  1030  1094 D Tethering: MasterInitialState.processMessage what=3
,08-05 14:14:46.503  6923  6923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 14:14:46.503  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 14:14:46.503  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 14:14:46.503  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 14:14:46.503  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 14:14:46.503  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 14:14:46.503  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 14:14:46.503  6923  6923 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-05 14:14:46.507  6923  6923 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-05 14:14:46.509  6408  6408 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-05 14:14:46.511  6408  7043 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-05 14:14:46.516  1030  1088 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-05 14:14:46.524  5875  5875 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
08-05 14:14:46.548  2185  2185 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-05 14:14:46.577  1030  1733 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10005
,08-05 14:14:46.578  1030  7931 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-2ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-05 14:14:46.579  1030  7931 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-05 14:14:46.579  1030  7931 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-05 14:14:46.579  1030  7931 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-05 14:14:46.579  1030  7931 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-05 14:14:46.585  1030  1088 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 14:14:46.599  1030  2014 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=8034 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-05 14:14:46.625  1030  7931 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 05 Aug 2016 12:14:46 GMT], X-Android-Received-Millis=[1470399286624], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1470399286580]}
08-05 14:14:46.625  1030  7931 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-05 14:14:46.625  1030  7931 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-05 14:14:46.625  1030  1403 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-05 14:14:46.625  1030  1403 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-05 14:14:46.625  1030  1403 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-05 14:14:46.625  1030  1403 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 14:14:46.625  1030  1403 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-05 14:14:46.625  1030  1403 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-05 14:14:46.625  1030  1403 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-05 14:14:46.625  1030  1403 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 14:14:46.625  1030  1403 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 14:14:46.625  1030  1403 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 14:14:46.626  1600  1825 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-05 14:14:46.662  8034  8034 I AppUp4:AppBoxCP: onCreate
,08-05 14:14:46.662  8034  8034 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
08-05 14:14:46.668  8034  8034 I AppUp4:DB:  setFingerPrint start
08-05 14:14:46.668  8034  8034 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-05 14:14:46.673  8034  8034 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-05 14:14:46.673  8034  8034 I AppUp4:DB:  SDK version = 21
08-05 14:14:46.673  8034  8034 I AppUp4:DB:  beforefinger == newfinger no write in DB
,08-05 14:14:46.674  8034  8034 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
,08-05 14:14:46.675  8034  8034 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-05 14:14:46.675  8034  8034 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-05 14:14:46.677  8034  8034 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-05 14:14:46.677  8034  8034 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-05 14:14:46.679  8034  8034 I AppUp4:CustModeStarterReceiver: onReceive
08-05 14:14:46.702  8034  8034 D LgDataFeature: LgDataFeature() Constructor: none
08-05 14:14:46.702  8034  8034 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-05 14:14:46.711  8034  8034 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@12a5f815
08-05 14:14:46.711  8034  8034 D AppUp4:CustFacade: isCustomizationCompleted : false
08-05 14:14:46.711  8034  8034 D AppUp4:CustFacade: isPhone : true
08-05 14:14:46.711  8034  8034 D AppUp4:CustModeStarterReceiver: begin check event
08-05 14:14:46.712  8034  8034 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-05 14:14:46.712  8034  8034 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-05 14:14:46.712  8034  8054 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-05 14:14:46.713  8034  8054 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-05 14:14:46.713  8034  8054 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-05 14:14:46.717  1030  1986 I ActivityManager: Killing 7236:com.lge.email/u0a23 (adj 15): empty #17
,08-05 14:14:46.773  6923  6984 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-05 14:14:46.773  6923  6984 I jxcore-log: 
,08-05 14:14:46.825  4803  4803 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-05 14:14:46.826  4803  4803 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-05 14:14:46.827  1030  1653 W libprocessgroup: failed to open /acct/uid_10023/pid_7236/cgroup.procs: No such file or directory
08-05 14:14:46.830  4803  4803 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-05 14:14:46.839  4803  4803 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 14:14:46.849  3478  3478 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,08-05 14:14:46.856  3478  3478 V DownloadManager: DownloadService onCreate
08-05 14:14:46.858  4803  8057 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-05 14:14:46.865  4803  8060 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-05 14:14:46.866  4803  8060 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-05 14:14:46.871  3478  8058 I DownloadManager: in removeSpuriousFiles
,08-05 14:14:46.874  4803  8057 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
08-05 14:14:46.876  3478  8058 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
08-05 14:14:46.876  3478  8058 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@1011b12e on behalf of 3478
08-05 14:14:46.877  3478  8058 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
08-05 14:14:46.877  3478  8058 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
08-05 14:14:46.877  3478  8058 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
08-05 14:14:46.877  3478  8058 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
08-05 14:14:46.877  3478  8058 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
08-05 14:14:46.877  3478  8058 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
08-05 14:14:46.877  3478  8058 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
08-05 14:14:46.877  3478  8058 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
08-05 14:14:46.878  3478  8058 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
08-05 14:14:46.878  3478  8058 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
08-05 14:14:46.878  3478  8058 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
08-05 14:14:46.879  3478  8058 I DownloadManager: in trimDatabase
08-05 14:14:46.879  3478  8058 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
08-05 14:14:46.880  3478  8058 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@3318a4cf on behalf of 3478
08-05 14:14:46.912  1030  1917 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=8063 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-05 14:14:46.919  3478  3478 V DownloadManager: DownloadService onStartCommand
08-05 14:14:46.920  3478  8059 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
08-05 14:14:46.922  3478  8059 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@51a3565 on behalf of 3478
08-05 14:14:46.924  3478  8059 V DownloadManager: processing inserted download 1
08-05 14:14:46.925  4803  8057 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
08-05 14:14:46.925  3478  8059 V DownloadManager: processing inserted download 4
08-05 14:14:46.926  3478  8059 V DownloadManager: processing inserted download 7
08-05 14:14:46.927  4803  4803 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
08-05 14:14:46.927  3478  8059 V DownloadManager: processing inserted download 8
08-05 14:14:46.928  4803  4803 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
08-05 14:14:46.928  4803  4803 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
08-05 14:14:46.928  3478  8059 V DownloadManager: processing inserted download 9
08-05 14:14:46.929  3478  8059 V DownloadManager: processing inserted download 10
08-05 14:14:46.930  4803  4803 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
08-05 14:14:46.930  3478  8059 V DownloadManager: processing inserted download 11
08-05 14:14:46.934  4803  4803 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
08-05 14:14:46.933  3478  8059 V DownloadManager: processing inserted download 12
08-05 14:14:46.941  3478  8059 V DownloadManager: processing inserted download 13
08-05 14:14:46.943  3478  8059 V DownloadManager: processing inserted download 14
08-05 14:14:46.944  3478  8059 V DownloadManager: processing inserted download 16
08-05 14:14:46.947  3478  3478 V DownloadManager: DownloadService onDestroy
,08-05 14:14:46.973  8063  8063 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-05 14:14:46.973  8063  8063 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-05 14:14:46.975  8063  8063 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-05 14:14:46.975  8063  8063 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-05 14:14:47.049  8063  8063 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-05 14:14:47.059  8063  8063 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-05 14:14:47.092  8063  8063 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-05 14:14:47.116  8063  8063 D LgDataFeature: LgDataFeature() Constructor: none
08-05 14:14:47.117  8063  8063 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-05 14:14:47.205  8063  8063 D eas_req : ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-05 14:14:47.237  3317  3317 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-05 14:14:47.237  3317  3317 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-05 14:14:47.237  3317  3317 I LgeMiscReceiver: networkInfo.isConnected() = true
08-05 14:14:47.237  3317  3317 D PhoneState: setPdpRejectCasuse : false
,08-05 14:14:47.244  7281  7281 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-05 14:14:47.245  7281  7281 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-05 14:14:47.256  7344  7344 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:14:47
,08-05 14:14:47.263  7344  7344 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-05 14:14:47.263  7344  7344 D Weather.Utils: 2 : All the weather widget is gone.
08-05 14:14:47.263  7344  7344 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-05 14:14:47.264  7344  7344 D WeatherAncestor: connectivity changed - connection : true
08-05 14:14:47.264  7344  7344 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3875791b
08-05 14:14:47.265  7344  7344 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-05 14:14:47.265  7344  7344 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-05 14:14:47.265  7344  7344 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-05 14:14:47.265  7344  7344 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-05 14:14:47.265  7344  7344 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:14:47
08-05 14:14:47.278  8063  8063 I HubEmail: JNI_OnLoad()
08-05 14:14:47.278  8063  8063 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-05 14:14:47.278  8063  8063 I HubEmail: registerNatives()
08-05 14:14:47.278  8063  8063 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-05 14:14:47.278  8063  8063 I HubEmail: registerNativeMethods()
08-05 14:14:47.278  8063  8063 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-05 14:14:47.278  8063  8063 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,08-05 14:14:47.286   308  8093 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-05 14:14:47.286   308  8093 D libc-netbsd: res_queryN name = static-avc.lglime.com, class = 1, type = 1
08-05 14:14:47.302  8063  8094 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-05 14:14:47.325   308  8093 D libc-netbsd: res_queryN name = static-avc.lglime.com succeed
,08-05 14:14:47.415  7117  8090 V FormManager: There are no updated forms. The schedule will be deleted.
,08-05 14:14:47.424  7117  8090 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
,08-05 14:14:47.459  1030  1735 I ActivityManager: Killing 7543:com.lge.lifetracker/u0a37 (adj 15): empty #17
,08-05 14:14:47.488  6923  6984 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-05 14:14:47.488  6923  6984 I jxcore-log: 
,08-05 14:14:47.510  6923  6984 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-05 14:14:47.510  6923  6984 I jxcore-log: 
,08-05 14:14:47.563  1030  2014 W libprocessgroup: failed to open /acct/uid_10037/pid_7543/cgroup.procs: No such file or directory
,08-05 14:14:47.660   308  8099 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-05 14:14:47.660   308  8099 D libc-netbsd: res_queryN name = www.google.com, class = 1, type = 1
,08-05 14:14:47.693   308  8099 D libc-netbsd: res_queryN name = www.google.com succeed
,08-05 14:14:47.701   308  8101 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-05 14:14:47.702   308  8101 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-05 14:14:47.702   308  8101 D libc-netbsd: res_queryN name = clients3.google.com succeed
08-05 14:14:47.787  1030  1391 V WifiInternetCheck: isHttpConnectionAvailable - We got a valid response : 204
,08-05 14:14:49.121  6923  6984 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-05 14:14:49.121  6923  6984 I jxcore-log: 
,08-05 14:14:49.351  6923  6984 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
08-05 14:14:49.351  6923  6984 I jxcore-log: 
,08-05 14:14:49.356  6923  6984 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
08-05 14:14:49.356  6923  6984 I jxcore-log: 
,08-05 14:14:49.374  6923  6984 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
08-05 14:14:49.374  6923  6984 I jxcore-log: 
,08-05 14:14:49.378  6923  6984 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
08-05 14:14:49.378  6923  6984 I jxcore-log: 
,08-05 14:14:49.421  1030  1389 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=50.2, 0.0, 0.0  rx=41.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1520474189] gl rssi=-38 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-05 14:14:49.422  1030  1389 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=50.2, 0.0, 0.0  rx=41.8 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1520474190] gl rssi=-38 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-05 14:14:49.422  1030  1389 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-05 14:14:49.984  1030  1653 I ActivityManager: Killing 7096:com.lge.settings.easy/1000 (adj 15): empty #17
,08-05 14:14:50.063  1030  1045 W libprocessgroup: failed to open /acct/uid_1000/pid_7096/cgroup.procs: No such file or directory
,08-05 14:14:50.101  6923  6984 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
08-05 14:14:50.101  6923  6984 I jxcore-log: 
,08-05 14:14:50.122  6923  6984 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
08-05 14:14:50.122  6923  6984 I jxcore-log: 
,08-05 14:14:50.137  6923  6984 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
08-05 14:14:50.137  6923  6984 I jxcore-log: 
,08-05 14:14:50.149  6923  6984 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
08-05 14:14:50.149  6923  6984 I jxcore-log: 
,08-05 14:14:50.216  6923  6984 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
08-05 14:14:50.216  6923  6984 I jxcore-log: 
,08-05 14:14:50.284  6923  6984 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
08-05 14:14:50.284  6923  6984 I jxcore-log: 
,08-05 14:14:50.293  6923  6984 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
08-05 14:14:50.293  6923  6984 I jxcore-log: 
,08-05 14:14:50.459  6923  6984 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
08-05 14:14:50.459  6923  6984 I jxcore-log: 
,08-05 14:14:50.506  6923  6984 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
08-05 14:14:50.506  6923  6984 I jxcore-log: 
08-05 14:14:50.511  6923  6984 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
08-05 14:14:50.511  6923  6984 I jxcore-log: 
,08-05 14:14:50.521  6923  6984 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
08-05 14:14:50.521  6923  6984 I jxcore-log: 
08-05 14:14:50.546  6923  6984 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
08-05 14:14:50.546  6923  6984 I jxcore-log: 
,08-05 14:14:50.643  6923  6984 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
08-05 14:14:50.643  6923  6984 I jxcore-log: 
,08-05 14:14:50.658  6923  6984 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
08-05 14:14:50.658  6923  6984 I jxcore-log: 
,08-05 14:14:50.687  6923  6984 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
08-05 14:14:50.687  6923  6984 I jxcore-log: 
,08-05 14:14:50.700  6923  6984 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
08-05 14:14:50.700  6923  6984 I jxcore-log: 
08-05 14:14:50.718  6923  6984 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
08-05 14:14:50.718  6923  6984 I jxcore-log: 
,08-05 14:14:50.752  6923  6984 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
08-05 14:14:50.752  6923  6984 I jxcore-log: 
,08-05 14:14:50.758  6923  6984 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
08-05 14:14:50.758  6923  6984 I jxcore-log: 
,08-05 14:14:50.961  6923  6984 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
08-05 14:14:50.961  6923  6984 I jxcore-log: 
,08-05 14:14:50.972  6923  6984 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
08-05 14:14:50.973  6923  6984 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
08-05 14:14:50.973  6923  6984 I jxcore-log: 
08-05 14:14:51.030  6923  6984 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 14:14:51.030  6923  6984 I jxcore-log: 
,08-05 14:14:52.439  1030  1389 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=33.6, 0.0, 0.0  rx=26.4 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1520477206] gl rssi=-38 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-05 14:14:52.450  1030  1389 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=33.6, 0.0, 0.0  rx=26.4 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:1520477217] gl rssi=-38 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-05 14:14:52.450  1030  1389 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-05 14:14:53.553  1600  1600 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-05 14:14:53.640  1030  1089 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=8119 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-05 14:14:53.649  1600  1600 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
08-05 14:14:53.650  1600  1600 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
08-05 14:14:53.685  2029  2029 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-05 14:14:53.696  1030  1030 D administrator: Handling package changes for user 0
08-05 14:14:53.699  1030  1378 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-05 14:14:53.709  2029  2029 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-05 14:14:53.729  8119  8119 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-05 14:14:53.762  1030  1030 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
,08-05 14:14:53.762  1030  1030 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
08-05 14:14:53.794  8119  8119 D LgDataFeature: LgDataFeature() Constructor: none
08-05 14:14:53.794  8119  8119 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-05 14:14:53.795  1030  1088 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-05 14:14:53.799  1030  1088 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-05 14:14:53.805  2029  2029 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-05 14:14:53.806  2504  2504 V GmsNetworkLocationProvi: DISABLE
08-05 14:14:53.840  2504  2504 E GCoreFlp: Bound FusedProviderService with LocationManager
,08-05 14:14:53.867  1030  1088 D LocationProviderProxy: applying state to connected service
,08-05 14:14:53.898  8119  8164 I Babel   : MmsConfig: mnc/mcc: 0/0
08-05 14:14:53.898  8119  8164 I Babel   : MmsConfig.loadMmsSettings
08-05 14:14:53.900  8119  8164 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-05 14:14:53.900  8119  8164 I Babel   : MmsConfig.loadFromDatabase
08-05 14:14:53.923  8119  8162 W AudioCapabilities: Unsupported mime audio/evrc
,08-05 14:14:53.927  8119  8162 W AudioCapabilities: Unsupported mime audio/qcelp
08-05 14:14:53.933  8119  8164 E Babel   : canonicalizeMccMnc: invalid mccmnc 
,08-05 14:14:53.934  8119  8164 I Babel   : MmsConfig.loadFromResources
08-05 14:14:53.935  8119  8162 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-05 14:14:53.939  8119  8164 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
,08-05 14:14:53.940  8119  8164 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,08-05 14:14:53.957  8119  8119 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-05 14:14:53.961  8119  8162 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
08-05 14:14:53.963  8119  8162 W AudioCapabilities: Unsupported mime audio/qcelp
08-05 14:14:53.964  8119  8162 W AudioCapabilities: Unsupported mime audio/evrc
,08-05 14:14:53.992  8119  8162 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-05 14:14:53.997  1813  8165 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-05 14:14:53.998  1813  8165 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
08-05 14:14:53.998  8034  8034 I AppUp4:CustModeStarterReceiver: onReceive
,08-05 14:14:54.004  8119  8162 W VideoCapabilities: Unsupported mime video/divx
08-05 14:14:54.004  8034  8034 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@12a5f815
08-05 14:14:54.004  8034  8034 D AppUp4:CustFacade: isCustomizationCompleted : false
08-05 14:14:54.004  8034  8034 D AppUp4:CustFacade: isPhone : true
08-05 14:14:54.005  8034  8034 D AppUp4:CustModeStarterReceiver: begin check event
08-05 14:14:54.006  8034  8034 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-05 14:14:54.013  8119  8162 W VideoCapabilities: Unsupported mime video/divx311
08-05 14:14:54.013  1813  5154 I Icing   : updateResources: need to parse e{com.google.android.gms}
08-05 14:14:54.022  8119  8162 W VideoCapabilities: Unsupported mime video/divx4
,08-05 14:14:54.033  8119  8162 W VideoCapabilities: Unsupported mime video/mp4v-esdp
08-05 14:14:54.048  1030  1045 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=8169 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,08-05 14:14:54.052  1030  1045 I ActivityManager: Killing 7481:com.lge.bnr/1000 (adj 15): empty #17
08-05 14:14:54.063  8119  8162 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-05 14:14:54.066  8119  8162 W AudioCapabilities: Unsupported mime audio/eac3
08-05 14:14:54.067  8119  8162 W AudioCapabilities: Unsupported mime audio/ac3
08-05 14:14:54.068  8119  8162 W AudioCapabilities: Unsupported mime audio/g726
08-05 14:14:54.069  8119  8162 W AudioCapabilities: Unsupported mime audio/wma-voice
08-05 14:14:54.071  8119  8162 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-05 14:14:54.072  8119  8162 W AudioCapabilities: Unsupported mime audio/adpcm
08-05 14:14:54.073  8119  8162 W VideoCapabilities: Unsupported mime video/theora
08-05 14:14:54.075  8119  8162 W VideoCapabilities: Unsupported mime video/mjpg
,08-05 14:14:54.163  1030  1735 W libprocessgroup: failed to open /acct/uid_1000/pid_7481/cgroup.procs: No such file or directory
,08-05 14:14:54.169  1030  1376 V AlarmManager: ELAPSED_WAKEUP set : Alarm{17543807 type 2 when 379817 com.google.android.gms} when 379817
08-05 14:14:54.222  8169  8169 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-05 14:14:54.224  8169  8169 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-05 14:14:54.225  8169  8169 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-05 14:14:54.228  8169  8169 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-05 14:14:54.229  8169  8169 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-05 14:14:54.316  8169  8169 I SystemConfig: BUILD Country: EU
08-05 14:14:54.316  8169  8169 I SystemConfig: BUILD Operator: OPEN
,08-05 14:14:54.369  1030  1951 I ActivityManager: Killing 7045:com.lge.sync/1000 (adj 15): empty #17
,08-05 14:14:54.469  1030  1045 W libprocessgroup: failed to open /acct/uid_1000/pid_7045/cgroup.procs: No such file or directory
,08-05 14:14:54.486  8169  8188 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-05 14:14:54.488  8169  8188 I SystemConfig: existFile = false
,08-05 14:14:54.488  8169  8188 I SystemConfig: canReadFile = false
08-05 14:14:54.488  8169  8188 I SystemConfig: systemFeature RCS result false
08-05 14:14:54.489  8169  8188 D SystemConfig: refreshRcsSupport() :false
08-05 14:14:54.547  1030  1046 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=8190 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-05 14:14:54.627  8190  8190 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-05 14:14:54.628  8190  8190 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-05 14:14:54.628  8190  8190 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-05 14:14:54.628  8190  8190 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-05 14:14:54.728  8190  8190 I AppConfig: Total System Memory = 2995761152
,08-05 14:14:54.754  8190  8190 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
,08-05 14:14:54.857  1030  1986 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8215 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-05 14:14:54.861  1030  1986 I ActivityManager: Killing 6778:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
08-05 14:14:54.885  7079  7079 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
,08-05 14:14:54.888  7079  7079 W System.err: android.os.DeadObjectException
,08-05 14:14:54.888  7079  7079 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-05 14:14:54.889  7079  7079 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-05 14:14:54.889  7079  7079 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-05 14:14:54.889  7079  7079 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-05 14:14:54.889  7079  7079 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-05 14:14:54.889  7079  7079 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-05 14:14:54.889  7079  7079 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-05 14:14:54.889  7079  7079 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-05 14:14:54.890  7079  7079 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-05 14:14:54.890  7079  7079 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-05 14:14:54.890  7079  7079 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 14:14:54.890  7079  7079 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-05 14:14:54.890  7079  7079 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-05 14:14:54.890  7079  7079 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-05 14:14:54.890  7079  7079 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-05 14:14:54.890  7079  7079 W System.err: android.os.DeadObjectException
08-05 14:14:54.890  7079  7079 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-05 14:14:54.891  7079  7079 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-05 14:14:54.891  7079  7079 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-05 14:14:54.891  7079  7079 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-05 14:14:54.891  7079  7079 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-05 14:14:54.891  7079  7079 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-05 14:14:54.891  7079  7079 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-05 14:14:54.891  7079  7079 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-05 14:14:54.891  7079  7079 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-05 14:14:54.892  7079  7079 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-05 14:14:54.892  7079  7079 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 14:14:54.892  7079  7079 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
,08-05 14:14:54.892  7079  7079 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-05 14:14:54.892  7079  7079 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-05 14:14:54.892  7079  7079 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-05 14:14:54.892  7079  7079 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-05 14:14:54.972  1030  1951 W libprocessgroup: failed to open /acct/uid_1000/pid_6778/cgroup.procs: No such file or directory
08-05 14:14:54.973  1030  1951 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
08-05 14:14:54.993  7079  7079 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-05 14:14:54.993  7079  7079 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,08-05 14:14:55.044  1030  1917 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=8232 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-05 14:14:55.050  7079  7079 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-05 14:14:55.130  8232  8232 D UEI.SmartControl: Quickset Services start...
08-05 14:14:55.132  8232  8232 I UEI.SmartControl: Manufacture = LGE
08-05 14:14:55.132  8232  8232 D UEI.SmartControl: Id = LGNevo
08-05 14:14:55.134  8232  8232 D UEI.SmartControl: File observer start...
08-05 14:14:55.135  8232  8232 E UEI.SmartControl: IR Port is disabled: false
08-05 14:14:55.135  8232  8232 D UEI.SmartControl: Starting file observer...
08-05 14:14:55.136  8232  8232 D UEI.SmartControl: Extracting JNI libs...
08-05 14:14:55.136  8232  8232 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
,08-05 14:14:55.214  8232  8232 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-05 14:14:55.214  8232  8232 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-05 14:14:55.214  8232  8232 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-05 14:14:55.227  8215  8215 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-05 14:14:55.238  8232  8232 I UEI.SmartControl: --- Selecting new region: 6
,08-05 14:14:55.240  8232  8232 I UEI.SmartControl: Model = LG-D855
,08-05 14:14:55.242  8232  8232 D UEI.SmartControl: QS Service created
08-05 14:14:55.253  8232  8232 I UEI.SmartControl: Service initServices...
,08-05 14:14:55.256  8232  8232 D UEI.SmartControl: QS start get config
08-05 14:14:55.295  8232  8232 D UEI.SmartControl: Loading JNI Libs...
,08-05 14:14:55.353  8215  8215 D LgDataFeature: LgDataFeature() Constructor: none
,08-05 14:14:55.353  8215  8215 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-05 14:14:55.434  8215  8215 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-05 14:14:55.456  8215  8215 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-05 14:14:55.461  8215  8215 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-05 14:14:55.472  1030  1389 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=21.3, 0.0, 0.0  rx=16.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1520480240] gl rssi=-38 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-05 14:14:55.475  1030  1389 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=21.3, 0.0, 0.0  rx=16.7 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:1520480242] gl rssi=-38 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-05 14:14:55.475  1030  1389 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-05 14:14:55.484  8215  8215 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-05 14:14:55.484  8215  8215 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
08-05 14:14:55.515  1030  1951 I ActivityManager: Killing 7002:com.android.settings/1000 (adj 15): empty #17
,08-05 14:14:55.515  3478  4106 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-05 14:14:55.517  3478  4106 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@3a4beeb on behalf of 8215
08-05 14:14:55.603  8232  8232 I UEI.SmartControl: Supports setup maps: true
,08-05 14:14:55.607  8232  8232 D UEI.SmartControl: QS start statue = true Error code = 0
08-05 14:14:55.608  8232  8232 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-05 14:14:55.608  8232  8232 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-05 14:14:55.608  8232  8232 I UEI.SmartControl: ### init IR Blaster...
08-05 14:14:55.614  8232  8232 D serial_port: Configuring serial port
08-05 14:14:55.618  8232  8232 E UEI.SmartControl: UEIBLaster setting for 616
08-05 14:14:55.618  8232  8232 I UEI.SmartControl: Setting serial record hearder size = 2
08-05 14:14:55.619  8232  8232 I UEI.SmartControl: configuring settings for MAXQ616
08-05 14:14:55.619  8232  8232 I UEI.SmartControl: Get version...
,08-05 14:14:55.629  1030  1592 W libprocessgroup: failed to open /acct/uid_1000/pid_7002/cgroup.procs: No such file or directory
08-05 14:14:55.632  5091  8286 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,08-05 14:14:55.637  8232  8285 D UEI.SmartControl: serial port data available: 21
08-05 14:14:55.665  8232  8232 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-05 14:14:55.665  8232  8232 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-05 14:14:55.665  8232  8232 I UEI.SmartControl: QS saving settings...
08-05 14:14:55.665  8232  8232 D UEI.SmartControl: IR Blaster version: 25672567
,08-05 14:14:55.682  8232  8285 D UEI.SmartControl: serial port data available: 4
,08-05 14:14:55.697  1030  1957 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=8288 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-05 14:14:55.726  8232  8306 I UEI.SmartControl: Device manager: loading config....
08-05 14:14:55.727  8232  8306 D UEI.SmartControl: ----------- loading internal config...
08-05 14:14:55.727  8215  8215 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-05 14:14:55.738  8232  8232 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-05 14:14:55.740  8232  8232 E UEI.SmartControl: Services init done
08-05 14:14:55.740  8232  8232 D UEI.SmartControl: QS Service init finished
08-05 14:14:55.741  8232  8232 D UEI.SmartControl: QS Service version name: 2.1.91
08-05 14:14:55.741  8232  8232 D UEI.SmartControl: QS Service version code: 201091
08-05 14:14:55.742  8232  8232 D UEI.SmartControl: Service requested: Control
08-05 14:14:55.742  8232  8306 E UEI.SmartControl: Loading SETTINGS...
08-05 14:14:55.747  7079  7079 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
,08-05 14:14:55.748  8232  8247 I UEI.SmartControl: ------ IControl API: 11
08-05 14:14:55.749  8232  8247 I UEI.SmartControl: Registering callback...
08-05 14:14:55.750  8232  8248 I UEI.SmartControl: ------ IControl API: 19
08-05 14:14:55.751  8232  8248 I UEI.SmartControl: Registering Services Ready callback...
08-05 14:14:55.754  8232  8232 D UEI.SmartControl: Internal service binding...
08-05 14:14:55.764  8215  8215 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-05 14:14:55.766  1030  1045 I ActivityManager: Killing 7079:com.lge.qremote/u0a112 (adj 15): empty #17
08-05 14:14:55.769  8232  8306 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-05 14:14:55.781  8232  8305 I UEI.SmartControl: Notify AllClients services are ready: 0
08-05 14:14:55.782  8232  8305 D UEI.SmartControl: -----service ready thread exits
,08-05 14:14:55.785  8288  8288 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-05 14:14:55.894  1030  1951 W libprocessgroup: failed to open /acct/uid_10112/pid_7079/cgroup.procs: No such file or directory
,08-05 14:14:55.927  8288  8288 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-05 14:14:55.927  8288  8288 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-05 14:14:55.927  8288  8288 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-05 14:14:55.927  8288  8288 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-05 14:14:55.927  8288  8288 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-05 14:14:55.927  8288  8288 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,08-05 14:14:55.950   308  8320 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-05 14:14:55.950   308  8320 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
08-05 14:14:55.951   308  8320 D libc-netbsd: res_queryN name = mtalk.google.com succeed
08-05 14:14:56.066  1030  1957 I art     : Explicit concurrent mark sweep GC freed 38855(1908KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 2.257ms total 110.509ms
,08-05 14:14:56.076  1030  1733 I ActivityManager: Killing 8063:com.lge.email/u0a23 (adj 15): empty #17
08-05 14:14:56.131  1030  1045 W libprocessgroup: failed to open /acct/uid_10023/pid_8063/cgroup.procs: No such file or directory
,08-05 14:14:56.288  2185  8322 D GCM     : Connected
,08-05 14:14:56.316  2185  8322 D GCM     : Message class com.google.e.a.a.q
,08-05 14:14:56.354  1030  1915 V SIM_STK : Menu title from STK is T-Mobile
,08-05 14:14:56.376  5091  8286 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 744 ms] updated apps [took 744 ms] 
,08-05 14:14:58.493  1030  1389 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=11.2, 0.0, 0.0  rx=8.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1520483261] gl rssi=-38 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-05 14:14:58.496  1030  1389 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=11.2, 0.0, 0.0  rx=8.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1520483264] gl rssi=-38 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-05 14:14:58.497  1030  1389 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-05 14:15:00.052  1600  1600 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-05 14:15:00.052  1600  1600 I KeyguardUpdateMonitor: called onTimeUpdated()
08-05 14:15:00.052  1600  1600 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-05 14:15:00.052  1600  1600 I [SystemUI]Clock: called onTimeUpdated()
,08-05 14:15:00.057  1600  1600 I LgeClockWidgetControlView: called onTimeUpdated()
,08-05 14:15:00.057  1600  1600 I [SystemUI]DateView: called onTimeUpdated()
,08-05 14:15:00.057  1600  1600 I [SystemUI]DateView: called onTimeUpdated()
08-05 14:15:00.058  1600  1600 D KeyguardUpdateMonitor: handleTimeUpdate
08-05 14:15:00.736  8232  8308 D UEI.SmartControl: Internal timer expired: 1
,08-05 14:15:00.749  8232  8308 D UEI.SmartControl: unbind internal service
08-05 14:15:00.769  8232  8232 D UEI.SmartControl: Service.onUnbind: IControl
,08-05 14:15:00.775  8232  8232 D UEI.SmartControl: Service.onDestroy
08-05 14:15:00.776  8232  8232 D UEI.SmartControl: Lock is in USE false
08-05 14:15:00.776  8232  8232 D UEI.SmartControl: unbind internal service
08-05 14:15:00.777  8232  8287 D serial_port: close(fd = 25)
08-05 14:15:00.782  8232  8287 I UEI.SmartControl: Serial port is closed.
,08-05 14:15:00.785  8232  8232 I UEI.SmartControl: Serial port is closed.
,08-05 14:15:00.785  8232  8232 I UEI.SmartControl: Serial port is closed.
08-05 14:15:00.786  8232  8232 D UEI.SmartControl: Blaster closed
08-05 14:15:00.786  8232  8232 D UEI.SmartControl: Shut down QS...
08-05 14:15:00.786  8232  8232 D UEI.SmartControl: Stopping QS lib
08-05 14:15:00.787  8232  8232 D UEI.SmartControl: QS lib stop result = true
08-05 14:15:00.787  8232  8232 D UEI.SmartControl: Stopped QS lib
,08-05 14:15:00.787  8232  8232 D UEI.SmartControl: Stopped file observer...,
08-05 14:15:00.787  8232  8232 D UEI.SmartControl: QS shutdown complete
,08-05 14:15:01.224  1030  1376 D PowerManagerServiceEx: acquireWakeLockInternal: lock=48785473, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1030
,08-05 14:15:01.291  1030  1089 I ActivityManager: Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=8332 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,08-05 14:15:01.325  2572  2572 D [Concierge]Service: onStartCommand(). Type : 9
,08-05 14:15:01.462  8332  8332 I DigitalAppWidgetProvider: onReceive: com.android.deskclock.ON_QUARTER_HOUR
,08-05 14:15:01.467  8332  8332 V DigitalAppWidgetProvider: startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@2881c71e
08-05 14:15:01.468  1030  1030 D PowerManagerServiceEx: releaseWakeLockInternal: lock=48785473 [*alarm*], flags=0x0
08-05 14:15:01.470  1030  1653 I ActivityManager: Killing 7117:com.lge.formmanager/u0a26 (adj 15): empty #17
08-05 14:15:01.520  1030  1389 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=10.1, 0.0, 0.0  rx=8.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1520486288] gl rssi=-38 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-05 14:15:01.521  1030  1389 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=10.1, 0.0, 0.0  rx=8.7 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1520486289] gl rssi=-38 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-05 14:15:01.521  1030  1389 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-05 14:15:01.526  1030  1045 W libprocessgroup: failed to open /acct/uid_10026/pid_7117/cgroup.procs: No such file or directory
08-05 14:15:04.539  1030  1389 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=6.0, 0.0, 0.0  rx=4.8 bcn=0 [on:0 tx:0 rx:0 period:3009] from screen [on:0 period:1520489306] gl rssi=-38 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-05 14:15:04.553  1030  1389 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=6.0, 0.0, 0.0  rx=4.8 bcn=0 [on:0 tx:0 rx:0 period:15] from screen [on:0 period:1520489321] gl rssi=-38 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-05 14:15:04.553  1030  1389 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-05 14:15:07.569  1030  1389 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=3.0, 0.0, 0.0  rx=2.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1520492337] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-05 14:15:07.583  1030  1389 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=3.0, 0.0, 0.0  rx=2.4 bcn=0 [on:0 tx:0 rx:0 period:14] from screen [on:0 period:1520492351] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-05 14:15:07.583  1030  1389 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-05 14:15:07.906  6923  6984 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-05 14:15:07.906  6923  6984 I jxcore-log: 
,08-05 14:15:08.256  8374  8374 D AndroidRuntime: 
08-05 14:15:08.256  8374  8374 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-05 14:15:08.264  8374  8374 D AndroidRuntime: CheckJNI is OFF
08-05 14:15:08.396  8374  8374 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-05 14:15:08.409  1030  1089 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
,08-05 14:15:08.410  1030  1089 I ActivityManager: Killing 6923:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,08-05 14:15:08.470  1030  1986 I WindowState: WIN DEATH: Window{3c0a046c u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-05 14:15:08.472  1030  1401 D WifiService: Client connection lost with reason: 4
08-05 14:15:08.479  1030  1986 D InputDispatcher: Window went away: Window{3c0a046c u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-05 14:15:08.635  1030  1089 I ActivityManager:   Force finishing activity ActivityRecord{21549d1 u0 com.test.thalitest/.MainActivity t40}
,08-05 14:15:08.669   334   342 E GBMv2   : DFP En is all cleared set to be enabled
,08-05 14:15:08.673  1030  1917 W ActivityManager: Spurious death for ProcessRecord{282c3832 6923:com.test.thalitest/u0a118}, curProc for 6923: null
08-05 14:15:08.674  1030  1101 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-05 14:15:08.677  1030  1101 I ActivityManager:   Force finishing activity ActivityRecord{21549d1 u0 com.test.thalitest/.MainActivity t40 f}
08-05 14:15:08.677  1030  1101 W ActivityManager: Duplicate finish request for ActivityRecord{21549d1 u0 com.test.thalitest/.MainActivity t40 f}
,08-05 14:15:08.698  1938  1954 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-05 14:15:08.698  1938  1954 D SplitWindowPolicy: topRunningActivity=ActivityInfo{309a4908 co.....Launcher}, taskId=39, activityType=1, bIsSplit=false
,08-05 14:15:08.700  1938  2662 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-05 14:15:08.702  1938  2662 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3821b8a1 co.....Launcher}, taskId=39, activityType=1, bIsSplit=false
08-05 14:15:08.704  2029  2029 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-05 14:15:08.706  2029  2029 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-05 14:15:08.709  1600  1600 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-05 14:15:08.720  1993  1993 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-05 14:15:08.724  1030  1378 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-05 14:15:08.725  3840  3840 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-05 14:15:08.726  2504  2678 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-05 14:15:08.731  7714  7714 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-05 14:15:08.731  7714  7714 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-05 14:15:08.760  1030  1917 V SIM_STK : Menu title from STK is T-Mobile
,08-05 14:15:08.768  5091  5091 I art     : Explicit concurrent mark sweep GC freed 8045(465KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 623us total 82.543ms
08-05 14:15:08.782  6408  6408 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
,08-05 14:15:08.805  4984  4984 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-05 14:15:08.805  4984  4984 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-05 14:15:08.806  4984  4984 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-05 14:15:08.806  4984  4984 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-05 14:15:08.806  4984  4984 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-05 14:15:08.806  4984  4984 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-05 14:15:08.806  4984  4984 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-05 14:15:08.806  4984  4984 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-05 14:15:08.806  4984  4984 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 14:15:08.806  4984  4984 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-05 14:15:08.806  4984  4984 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-05 14:15:08.806  4984  4984 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-05 14:15:08.810  1030  1088 W InputMethodInfo: Duplicated subtype definition found: , voice
08-05 14:15:08.811  1813  1813 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-05 14:15:08.813  2029  2029 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-05 14:15:08.814  2029  2120 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
08-05 14:15:08.817  1900  1900 D ActionManagerService: notifyUserLog: 1000003
08-05 14:15:08.817  3840  4974 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-05 14:15:08.819  2029  2029 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-05 14:15:08.834  1030  1030 I art     : Explicit concurrent mark sweep GC freed 16583(1082KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 2.774ms total 139.035ms
,08-05 14:15:08.838  1866  1866 D SplitUIManager: split_name #11 / not available #0
08-05 14:15:08.838  1866  1866 D SplitUIService: removed split : 
08-05 14:15:08.843  2185  2185 I ConfigService: onCreate
08-05 14:15:08.846  1813  1813 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,08-05 14:15:08.847  2185  2185 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-05 14:15:08.850  2029  2029 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-05 14:15:08.851  2029  2029 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-05 14:15:08.852  2029  2029 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-05 14:15:08.852  1600  1652 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-05 14:15:08.852  1600  1652 D KeyguardModel: createShortcutInfo...
08-05 14:15:08.855  1600  1600 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-05 14:15:08.860  2185  2185 I ConfigService: onBind returning update interface
,08-05 14:15:08.862  2185  2185 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-05 14:15:08.862  2185  2185 I ConfigService: onBind returning config service
08-05 14:15:08.865  1600  1652 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-05 14:15:08.865  1600  1652 D KeyguardModel: createShortcutInfo...
08-05 14:15:08.865  2029  2029 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-05 14:15:08.866  1900  1900 D ActionManagerService: notifyUserLog: 1000004
08-05 14:15:08.867  3840  4974 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-05 14:15:08.867  3840  4973 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-05 14:15:08.868  1600  1652 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-05 14:15:08.869  1600  1652 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-05 14:15:08.869  1600  1652 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-05 14:15:08.869  2029  2029 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-05 14:15:08.869  2029  2029 I GBoardWebViewUtils: , create_time: 1430832262123
08-05 14:15:08.869  2029  2029 I GBoardWebViewUtils: , expire_time: 0
08-05 14:15:08.869  2029  2029 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-05 14:15:08.869  2029  2029 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-05 14:15:08.869  2029  2029 I GBoardWebViewUtils: , display: false
08-05 14:15:08.869  2029  2029 I GBoardWebViewUtils: , animation: false }
08-05 14:15:08.869  2029  2029 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-05 14:15:08.869  2029  2029 I GBoardWebViewUtils: , create_time: 1430832262287
08-05 14:15:08.869  2029  2029 I GBoardWebViewUtils: , expire_time: 0
08-05 14:15:08.869  2029  2029 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-05 14:15:08.869  2029  2029 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-05 14:15:08.869  2029  2029 I GBoardWebViewUtils: , display: false
08-05 14:15:08.869  2029  2029 I GBoardWebViewUtils: , animation: false }
08-05 14:15:08.869  2029  2029 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1470393742816
08-05 14:15:08.869  2029  2029 I GBoardWebViewUtils: , create_time: 1470393743569
08-05 14:15:08.869  2029  2029 I GBoardWebViewUtils: , expire_time: 0
08-05 14:15:08.869  2029  2029 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide.html?id=guide_1111111111116_1470393742816&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-05 14:15:08.869  2029  2029 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-05 14:15:08.869  2029  2029 I GBoardWebViewUtils: , display: false
08-05 14:15:08.869  2029  2029 I GBoardWebViewUtils: , animation: false }
08-05 14:15:08.872  1600  1652 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-05 14:15:08.872  1600  1652 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-05 14:15:08.872  1600  1652 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-05 14:15:08.874  2029  8408 D Wallp,aperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-05 14:15:08.874  1600  1652 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-05 14:15:08.874  1600  1652 D KeyguardModel: createShortcutInfo...
08-05 14:15:08.877  1600  1652 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-05 14:15:08.877  1600  1652 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-05 14:15:08.878  1600  1652 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-05 14:15:08.878  1600  1652 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-05 14:15:08.882  1600  1652 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-05 14:15:08.882  1600  1652 D KeyguardModel: createShortcutInfo...
08-05 14:15:08.882  1866  1866 D SplitUIManager: split_name #11 / not available #0
08-05 14:15:08.882  1866  1866 I SplitUIService: split app #11
08-05 14:15:08.886  1030  1653 V SIM_STK : Menu title from STK is T-Mobile
08-05 14:15:08.886  1030  1653 V SIM_STK : Menu title from STK is T-Mobile
08-05 14:15:08.890  1600  1600 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-05 14:15:08.890  1600  1600 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,08-05 14:15:08.898  2029  2029 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-05 14:15:08.898  1600  1652 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-05 14:15:08.898  1600  1652 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-05 14:15:08.898  2029  2029 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-05 14:15:08.898  1600  1652 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,08-05 14:15:08.898  1600  1652 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-05 14:15:08.911  1600  1652 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-05 14:15:08.911  1600  1652 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-05 14:15:08.913  1600  1652 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-05 14:15:08.913  1600  1652 D KeyguardModel: createShortcutInfo...
08-05 14:15:08.918  1600  1600 D KeyguardModel: handleShortcutListChanged...
08-05 14:15:08.918  1600  1600 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-05 14:15:08.922  1600  1652 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-05 14:15:08.922  1600  1652 D KeyguardModel: createShortcutInfo...
08-05 14:15:08.924  1030  1957 V SIM_STK : Menu title from STK is T-Mobile
08-05 14:15:08.924  1600  1652 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-05 14:15:08.924  1600  1652 D KeyguardModel: createShortcutInfo...
08-05 14:15:08.926  1600  1652 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-05 14:15:08.926  1600  1652 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-05 14:15:08.932  1600  1652 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-05 14:15:08.932  1600  1652 D KeyguardModel: createShortcutInfo...
08-05 14:15:08.934  1600  1652 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-05 14:15:08.934  1600  1652 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,08-05 14:15:08.935  1600  1652 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-05 14:15:08.935  1600  1652 D KeyguardModel: createShortcutInfo...
08-05 14:15:08.936  1600  1652 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-05 14:15:08.937  1600  1652 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,08-05 14:15:08.944  1600  1652 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-05 14:15:08.944  1600  1652 D KeyguardModel: createShortcutInfo...
08-05 14:15:08.951  1030  1915 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-05 14:15:08.951  7714  7714 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-05 14:15:08.951  7714  7714 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-05 14:15:08.951  7714  7714 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-05 14:15:08.951  7714  7714 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-05 14:15:08.951  7714  7714 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-05 14:15:08.951  7714  7714 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-05 14:15:08.951  7714  7714 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-05 14:15:08.951  7714  7714 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-05 14:15:08.951  7714  7714 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-05 14:15:08.952  7714  7714 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-05 14:15:08.952  7714  7714 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-05 14:15:08.964  2029  2029 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
,08-05 14:15:08.970  2185  2185 I ConfigService: onDestroy
08-05 14:15:08.978  1813  8410 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,08-05 14:15:08.985  1600  1600 D KeyguardModel: handleShortcutListChanged...
08-05 14:15:08.985  1600  1600 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-05 14:15:09.001  8034  8034 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
,08-05 14:15:09.007  5907  8414 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
08-05 14:15:09.021  2343  8416 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-05 14:15:09.023  1030  1101 I art     : Explicit concurrent mark sweep GC freed 6759(516KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 2.111ms total 163.107ms
08-05 14:15:09.040  1030  1030 D administrator: Handling package changes for user 0
08-05 14:15:09.041   338   338 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 206us total 10.506ms
,08-05 14:15:09.041  1030  1934 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8418 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
08-05 14:15:09.047   322   404 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-05 14:15:09.048  3266  8435 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-05 14:15:09.058   338   338 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 185us total 15.832ms
,08-05 14:15:09.060  2029  2029 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,08-05 14:15:09.063  2029  2029 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-05 14:15:09.065  2029  2029 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-05 14:15:09.067  2029  2029 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-05 14:15:09.068  2029  2029 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-05 14:15:09.069  2029  2029 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-05 14:15:09.070   338   338 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 191us total 9.998ms
08-05 14:15:09.072  1813  8436 I PeopleContactsSync: CP2 sync disabled
08-05 14:15:09.075  1813  5154 I Icing   : doRemovePackageData com.test.thalitest
,08-05 14:15:09.086  2029  2029 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-05 14:15:09.086  2029  2029 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-05 14:15:09.086  1030  1095 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3c245605 u0 com.lge.launcher2/.Launcher t39} time:394834
08-05 14:15:09.086  2029  2170 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-05 14:15:09.086  2029  2170 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-05 14:15:09.099  1813  8417 W GmsApplication: Using Auth Proxy for data requests.
,08-05 14:15:09.102  2029  2029 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-05 14:15:09.102  2029  2029 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-05 14:15:09.103  2029  2029 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-05 14:15:09.105  1813  8417 W GmsApplication: Using Auth Proxy for data requests.
08-05 14:15:09.110  2029  2029 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-05 14:15:09.111  2572  2572 D [Concierge]Service: onStartCommand(). Type : 8
08-05 14:15:09.111  2572  2572 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-05 14:15:09.111  2572  2572 D [Concierge]Service: Update widget ID : 11
08-05 14:15:09.113  2029  2029 D [Concierge]WidgetView: change position of spinner
,08-05 14:15:09.116  2029  2029 I [Concierge]WidgetView: initWebView(). Time : 1470399309116
08-05 14:15:09.116  2572  2572 D [Concierge]Service: onStartCommand(). Type : 0
08-05 14:15:09.118  8418  8418 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-05 14:15:09.118  8418  8418 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-05 14:15:09.119  8418  8418 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-05 14:15:09.119  8418  8418 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-05 14:15:09.127  2029  2029 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 976849568
08-05 14:15:09.127  2029  2029 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-05 14:15:09.128  2029  2029 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-05 14:15:09.130  2029  2029 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@3dc111d9
08-05 14:15:09.130  2029  2029 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
,08-05 14:15:09.132  2029  2029 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-05 14:15:09.132  2029  2029 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-05 14:15:09.137  2029  2029 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-05 14:15:09.137  2029  2029 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-05 14:15:09.138  2029  2029 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1470398941529, New one : 1470399309116
08-05 14:15:09.138  2029  2029 D [Concierge]WidgetView: Unregister all receivers
08-05 14:15:09.138  2029  2029 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-05 14:15:09.142  2029  2029 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-05 14:15:09.144  2029  2029 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-05 14:15:09.145  2029  2029 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
,08-05 14:15:09.147  2029  2029 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-05 14:15:09.148  2029  2029 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-05 14:15:09.149  2029  2029 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-05 14:15:09.150  2029  2029 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-05 14:15:09.150  2029  2029 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-05 14:15:09.158  1030  1030 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-05 14:15:09.158  1030  1030 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-05 14:15:09.158  1030  1030 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-05 14:15:09.161  1030  1574 D TaskPersister: removeObsoleteFile: deleting file=40_task.xml
,08-05 14:15:09.179  2029  2029 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-05 14:15:09.187  2029  2029 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-05 14:15:09.187  2029  2029 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-05 14:15:09.188  2029  2029 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-05 14:15:09.188  2029  2029 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-05 14:15:09.205  8374  8374 D AndroidRuntime: Shutting down VM
,08-05 14:15:09.214  2029  2029 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@31b24a45 time:394963
08-05 14:15:09.217  8418  8418 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-05 14:15:09.225  8418  8418 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
08-05 14:15:09.250  8418  8418 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-05 14:15:09.255  1030  1088 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-05 14:15:09.259  1030  1088 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-05 14:15:09.260  2029  2029 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-05 14:15:09.270  8418  8418 D LgDataFeature: LgDataFeature() Constructor: none
,08-05 14:15:09.271  8418  8418 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-05 14:15:09.316  8418  8418 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,08-05 14:15:09.324  1030  1951 I ActivityManager: Killing 7281:com.google.android.setupwizard/u0a46 (adj 15): empty #17
08-05 14:15:09.341  2029  2029 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-05 14:15:09.375  2029  2890 I GBoardtInterface: onReloaded()
,08-05 14:15:09.376  2029  2029 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-05 14:15:09.382  1993  1993 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-05 14:15:09.382  1993  1993 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
08-05 14:15:09.382  1030  1915 W libprocessgroup: failed to open /acct/uid_10046/pid_7281/cgroup.procs: No such file or directory
08-05 14:15:09.384  3840  3855 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-05 14:15:09.385  1993  1993 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
08-05 14:15:09.387  6408  6408 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
,08-05 14:15:09.388  3840  4973 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-05 14:15:09.417  1030  1592 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=8447 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-05 14:15:09.448  1030  1101 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8464 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-05 14:15:09.455  1900  1900 D ActionManagerService: notifyUserLog: 1000001
08-05 14:15:09.457  3840  4974 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-05 14:15:09.457  3840  4974 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-05 14:15:09.459  1900  1900 D ActionManagerService: notifyUserLog: 1000001
08-05 14:15:09.460  3840  4974 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-05 14:15:09.460  3840  4974 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
,08-05 14:15:09.460  3840  4974 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-05 14:15:09.460  3840  4974 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-05 14:15:09.462  3840  3855 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-05 14:15:09.464  2029  2029 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-05 14:15:09.464  2029  2029 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-05 14:15:09.467  2029  2029 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-05 14:15:09.467  2029  2029 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-05 14:15:09.469  2029  2029 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide2.html?id=guide_1111111111116_1470393742816&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-05 14:15:09.469  2029  2029 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide2.html?id=guide_1111111111116_1470393742816&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-05 14:15:09.489  1030  1992 I ActivityManager: Killing 7300:com.android.chrome/u0a57 (adj 15): empty #17
,08-05 14:15:09.496  8447  8447 E SQLiteDatabase: Failed to open database '/data/data/com.lge.lifetracker/databases/lifetracker2.db'.
08-05 14:15:09.496  8447  8447 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-05 14:15:09.496  8447  8447 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-05 14:15:09.496  8447  8447 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-05 14:15:09.496  8447  8447 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-05 14:15:09.496  8447  8447 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-05 14:15:09.496  8447  8447 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-05 14:15:09.496  8447  8447 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-05 14:15:09.496  8447  8447 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-05 14:15:09.496  8447  8447 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-05 14:15:09.496  8447  8447 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-05 14:15:09.496  8447  8447 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-05 14:15:09.496  8447  8447 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-05 14:15:09.496  8447  8447 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-05 14:15:09.496  8447  8447 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-05 14:15:09.496  8447  8447 E SQLiteDatabase: 	at com.lge.lifetracker.core.provider.LifetrackerProvider2.onCreate(LifetrackerProvider2.java:56)
08-05 14:15:09.496  8447  8447 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
08-05 14:15:09.496  8447  8447 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
08-05 14:15:09.496  8447  8447 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
08-05 14:15:09.496  8447  8447 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-05 14:15:09.496  8447  8447 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-05 14:15:09.496  8447  8447 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-05 14:15:09.496  8447  8447 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-05 14:15:09.496  8447  8447 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 14:15:09.496  8447  8447 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-05 14:15:09.496  8447  8447 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-05 14:15:09.496  8447  8447 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 14:15:09.496  8447  8447 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-05 14:15:09.496  8447  8447 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-05 14:15:09.496  8447  8447 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-05 14:15:09.496  8447  8447 E LifetrackerProvider2: Unable to open database for writing.
08-05 14:15:09.496  8447  8447 E LifetrackerProvider2: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-05 14:15:09.496  8447  8447 E Lifetra,ckerProvider2: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-05 14:15:09.496  8447  8447 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-05 14:15:09.496  8447  8447 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-05 14:15:09.496  8447  8447 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-05 14:15:09.496  8447  8447 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-05 14:15:09.496  8447  8447 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-05 14:15:09.496  8447  8447 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-05 14:15:09.496  8447  8447 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-05 14:15:09.496  8447  8447 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-05 14:15:09.496  8447  8447 E LifetrackerProvider2: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-05 14:15:09.496  8447  8447 E LifetrackerProvider2: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-05 14:15:09.496  8447  8447 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-05 14:15:09.496  8447  8447 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-05 14:15:09.496  8447  8447 E LifetrackerProvider2: 	at com.lge.lifetracker.core.provider.LifetrackerProvider2.onCreate(LifetrackerProvider2.java:56)
08-05 14:15:09.496  8447  8447 E LifetrackerProvider2: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
08-05 14:15:09.496  8447  8447 E LifetrackerProvider2: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
08-05 14:15:09.496  8447  8447 E LifetrackerProvider2: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
08-05 14:15:09.496  8447  8447 E LifetrackerProvider2: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-05 14:15:09.496  8447  8447 E LifetrackerProvider2: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-05 14:15:09.496  8447  8447 E LifetrackerProvider2: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-05 14:15:09.496  8447  8447 E LifetrackerProvider2: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-05 14:15:09.496  8447  8447 E LifetrackerProvider2: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 14:15:09.496  8447  8447 E LifetrackerProvider2: 	at android.os.Looper.loop(Looper.java:135)
08-05 14:15:09.496  8447  8447 E LifetrackerProvider2: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-05 14:15:09.496  8447  8447 E LifetrackerProvider2: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 14:15:09.496  8447  8447 E LifetrackerProvider2: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-05 14:15:09.496  8447  8447 E LifetrackerProvider2: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-05 14:15:09.496  8447  8447 E LifetrackerProvider2: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-05 14:15:09.507  8447  8447 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-05 14:15:09.508  8447  8447 W LG Account v2.2: No ProfileInfo entries
08-05 14:15:09.508  8447  8447 I LG Account v2.2: isEnabled: false
08-05 14:15:09.508  8447  8447 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-05 14:15:09.508  8447  8447 I Feature : [Lifetracker]Country: EU
08-05 14:15:09.508  8447  8447 I Feature : [Lifetracker]Operator: OPEN
08-05 14:15:09.508  8447  8447 I Feature : [Lifetracker]Ranking support: false
08-05 14:15:09.508  8447  8447 I Feature : [Lifetracker]Comfort support: false
08-05 14:15:09.508  8447  8447 I Feature : [Lifetracker]Accessory: true
08-05 14:15:09.508  8447  8447 I Feature : [Lifetracker]Health device: true
08-05 14:15:09.508  8447  8447 I Feature : [Lifetracker]Extra Pedometer: false
08-05 14:15:09.508  8447  8447 I Feature : [Lifetracker]Blood glucose device: false
08-05 14:15:09.508  8447  8447 I Feature : [Lifetracker]Device Number: 3
08-05 14:15:09.509  8447  8447 D CoreEventReceiver: [onReceive] Action=android.intent.action.PACKAGE_REMOVED

```
