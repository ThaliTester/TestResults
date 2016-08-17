#### Test 8135127732cb2b8_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-17 14:26:00.049  1590  1590 I [SystemUI]Clock: called onTimeUpdated()
08-17 14:26:00.059  1590  1590 I LgeClockWidgetControlView: called onTimeUpdated()
08-17 14:26:00.059  1590  1590 I [SystemUI]DateView: called onTimeUpdated()
08-17 14:26:00.061  1590  1590 I [SystemUI]DateView: called onTimeUpdated()
08-17 14:26:00.063  1590  1590 D KeyguardUpdateMonitor: handleTimeUpdate
,08-17 14:26:25.694  6710  6710 D AndroidRuntime: 
08-17 14:26:25.694  6710  6710 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-17 14:26:25.700  6710  6710 D AndroidRuntime: CheckJNI is OFF
08-17 14:26:25.821  6710  6710 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-17 14:26:25.826  1036  1964 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-17 14:26:25.837  1929  1945 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-17 14:26:25.841  1036  1964 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-17 14:26:25.841  1036  1964 D ActivityManager: setTaskToReturnTo : TaskRecord{23fbdac4 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-17 14:26:25.842  1036  1964 D ActivityManager: setTaskToReturnTo : TaskRecord{23fbdac4 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-17 14:26:25.843  1036  1964 D WindowStateEx: AppWindowTokenEx init.. 
08-17 14:26:25.844   352   370 E GBMv2   : DFP En is all cleared set to be enabled
08-17 14:26:25.864  1036  1964 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6725 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-17 14:26:25.865  6710  6710 D AndroidRuntime: Shutting down VM
08-17 14:26:25.929  1929  1945 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-17 14:26:25.929  1929  1945 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2b552b8 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-17 14:26:25.932  1929  1944 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-17 14:26:25.932  1929  1944 D SplitWindowPolicy: topRunningActivity=ActivityInfo{18b87891 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-17 14:26:26.006  6725  6725 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-17 14:26:26.072  6725  6725 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-17 14:26:26.079  6725  6725 I LibraryLoader: Loading: webviewchromium
08-17 14:26:26.082  6725  6725 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 7843-7845)
08-17 14:26:26.082  6725  6725 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-17 14:26:26.113  6725  6725 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3f8bc126}
,08-17 14:26:26.114  6725  6725 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-17 14:26:26.115  6725  6725 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,08-17 14:26:26.126  6725  6725 I BrowserStartupController: Initializing chromium process, renderers=0
,08-17 14:26:26.127  6725  6725 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-17 14:26:26.138   335  1372 V AudioPolicyService: registerClient() client 0xb1008800, uid 10118
,08-17 14:26:26.139  6725  6725 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-17 14:26:26.140  6725  6725 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-17 14:26:26.140  6725  6725 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-17 14:26:26.144  1036  1103 D BluetoothManagerService: Message: 20
08-17 14:26:26.144  1036  1103 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@25df812e:true
08-17 14:26:26.159  6725  6725 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-17 14:26:26.159  6725  6725 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-17 14:26:26.159  6725  6725 I Adreno-EGL: Build Date: 12/12/14 금
08-17 14:26:26.159  6725  6725 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-17 14:26:26.159  6725  6725 I Adreno-EGL: Remote Branch: 
08-17 14:26:26.159  6725  6725 I Adreno-EGL: Local Patches: 
08-17 14:26:26.159  6725  6725 I Adreno-EGL: Reconstruct Branch: 
,08-17 14:26:26.242  6725  6760 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-17 14:26:26.248  6725  6725 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-17 14:26:26.267  6725  6725 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-17 14:26:26.272  6725  6725 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-17 14:26:26.275  6725  6725 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-17 14:26:26.278  6725  6725 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-17 14:26:26.278  6725  6725 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-17 14:26:26.291  6725  6725 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-17 14:26:26.298  6725  6725 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-17 14:26:26.298  6725  6725 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-17 14:26:26.342  6725  6772 D OpenGLRenderer: Render dirty regions requested: true
08-17 14:26:26.342  6725  6772 I OpenGLRenderer: Initialized EGL, version 1.4
08-17 14:26:26.354  6725  6772 D OpenGLRenderer: Enabling debug mode 0
,08-17 14:26:26.361  6725  6725 D Atlas   : Validating map...
08-17 14:26:26.364  1036  1560 D SplitWindow: check instance of lgWin Window{1c2b6f78 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-17 14:26:26.411  6725  6770 D LgDataFeature: LgDataFeature() Constructor: none
,08-17 14:26:26.411  6725  6770 D LgDataFeature: LgDataFeature() Constructor Done, null
08-17 14:26:26.501  1036  1104 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +574ms (total +657ms)
,08-17 14:26:26.504  1036  1104 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{67c0dad u0 com.test.thalitest/.MainActivity t6} time:308267
08-17 14:26:26.508  6725  6725 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@176f22d time:308272
08-17 14:26:26.674  6725  6725 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-17 14:26:26.805  6725  6783 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435048448
,08-17 14:26:26.818  6725  6783 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-17 14:26:26.818  6725  6783 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-17 14:26:26.818  6725  6783 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-17 14:26:26.818  6725  6783 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-17 14:26:26.818  6725  6783 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-17 14:26:26.818  6725  6783 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25d08f61 added. We now have 1 listener(s)
08-17 14:26:26.822  1036  2001 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-17 14:26:26.824  6725  6783 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-17 14:26:26.825  6725  6783 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-17 14:26:26.826  6725  6783 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 14:26:26.827  6725  6783 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 14:26:26.832  6725  6783 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-17 14:26:26.832  6725  6783 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-17 14:26:26.832  6725  6783 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-17 14:26:26.832  6725  6783 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-17 14:26:26.832  6725  6783 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-17 14:26:26.832  6725  6783 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-17 14:26:26.832  6725  6783 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-17 14:26:26.832  6725  6783 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-17 14:26:26.832  6725  6783 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-17 14:26:26.832  6725  6783 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-17 14:26:26.832  6725  6783 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-17 14:26:26.832  6725  6783 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-17 14:26:26.832  6725  6783 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-17 14:26:26.832  6725  6783 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-17 14:26:26.832  6725  6783 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f21c374 added. We now have 1 listener(s)
08-17 14:26:26.833  6725  6783 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 14:26:26.839  1036  1529 D WifiService: New client listening to asynchronous messages
,08-17 14:26:26.843  6725  6783 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-17 14:26:26.843  6725  6783 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-17 14:26:26.843  6725  6783 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-17 14:26:26.843  6725  6783 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-17 14:26:26.843  6725  6783 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-17 14:26:26.849  6725  6783 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 14:26:26.849  1036  1638 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 14:26:26.850  6725  6783 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-17 14:26:26.860  6725  6783 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-17 14:26:26.860  6725  6783 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 14:26:26.860  6725  6783 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:26:26.860  6725  6783 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 14:26:26.860  6725  6783 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:26:26.860  6725  6783 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 14:26:26.860  6725  6783 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 14:26:26.860  6725  6783 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 14:26:26.860  6725  6783 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 14:26:26.860  6725  6783 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-17 14:26:26.860  6725  6783 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 14:26:26.863  6725  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:26:26.864  6725  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:26:26.865  6725  6783 I io.jxcore.node.LifeCycleMonitor: start: OK
08-17 14:26:26.893  6725  6725 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-17 14:26:26.906  6725  6770 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-17 14:26:26.906  6725  6770 I chromium: 
,08-17 14:26:27.036   352   372 E GBMv2   : DFP En is all cleared set to be enabled
08-17 14:26:27.036   352   372 E GBMv2   : Set value is all cleared set the max
08-17 14:26:27.036   352   372 I GBMv2   : DFP Enabled. Ignore VFP set
,08-17 14:26:27.050  6725  6725 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-17 14:26:27.050  6725  6725 I chromium: 
,08-17 14:26:27.851  6725  6786 W jxcore-log: Initializing JXcore engine
,08-17 14:26:27.851  6725  6786 W jxcore-log: JXcore engine is ready
,08-17 14:26:27.917  6786  6786 W Thread-777: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[10767]" dev="sockfs" ino=10767 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-17 14:26:27.917  6786  6786 W Thread-777: type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-17 14:26:27.917  6786  6786 W Thread-777: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[10879]" dev="sockfs" ino=10879 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-17 14:26:27.917  6786  6786 W Thread-777: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-17 14:26:27.917  6786  6786 W Thread-777: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[31617]" dev="sockfs" ino=31617 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,08-17 14:26:27.959  6725  6786 W jxcore-log: Starting JXcore engine
,08-17 14:26:28.070  6725  6786 W jxcore-log: Platform android
08-17 14:26:28.070  6725  6786 W jxcore-log: 
08-17 14:26:28.070  6725  6786 W jxcore-log: Process ARCH arm
08-17 14:26:28.070  6725  6786 W jxcore-log: 
,08-17 14:26:28.353  6725  6786 I jxcore-log: JXcore Cordova bridge is ready!
08-17 14:26:28.353  6725  6786 I jxcore-log: 
08-17 14:26:28.355  6725  6786 W jxcore-log: JXcore engine is started
,08-17 14:26:28.364  6725  6783 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-17 14:26:28.366  6725  6725 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-17 14:26:44.675  6725  6786 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-17 14:26:44.675  6725  6786 I jxcore-log: 
,08-17 14:26:44.678  6725  6786 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-17 14:26:44.678  6725  6786 I jxcore-log: 
08-17 14:26:44.682  6725  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 14:26:44.682  6725  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:26:44.682  6725  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 14:26:44.682  6725  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:26:44.682  6725  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 14:26:44.682  6725  6786 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 14:26:44.682  6725  6786 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 14:26:44.682  6725  6786 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 14:26:44.685  6725  6786 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 14:26:44.687  6725  6786 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-17 14:26:44.687  6725  6786 I jxcore-log: 
08-17 14:26:44.689  6725  6786 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-17 14:26:44.689  6725  6786 I jxcore-log: 
,08-17 14:26:45.029  6725  6786 D ExecuteNativeTests: Running unit tests
,08-17 14:26:45.112  6725  6786 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded,
08-17 14:26:45.112  6725  6786 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32897572 added. We now have 2 listener(s)
08-17 14:26:45.113  1036  2001 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
08-17 14:26:45.115  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-17 14:26:45.115  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-17 14:26:45.115  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 14:26:45.115  6725  6786 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 14:26:45.115  6725  6786 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e7bedc3 added. We now have 2 listener(s)
08-17 14:26:45.115  6725  6786 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 14:26:45.116  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-17 14:26:45.119  6725  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 14:26:45.121  6725  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 14:26:45.121  6725  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:26:45.121  6725  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 14:26:45.121  6725  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:26:45.121  6725  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 14:26:45.121  6725  6786 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 14:26:45.121  6725  6786 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 14:26:45.121  6725  6786 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 14:26:45.121  6725  6786 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 14:26:45.121  6725  6786 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 14:26:45.123  6725  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:26:45.123  6725  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:26:45.130  6725  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-17 14:26:45.135  6725  6786 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-17 14:26:45.136  6725  6786 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-17 14:26:45.140  6725  6786 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-17 14:26:45.141  6725  6786 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-17 14:26:45.141  6725  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-17 14:26:45.141  6725  6786 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-17 14:26:45.141  6725  6786 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-17 14:26:45.142  6725  6786 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:26:45.143  6725  6786 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:26:45.143  6725  6786 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:26:45.143  6725  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:26:45.143  6725  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:26:45.143  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 14:26:45.143  6725  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 14:26:45.144  6725  6786 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32897572 removed from the list
08-17 14:26:45.144  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:26:45.144  6725  6786 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e7bedc3 removed from the list
08-17 14:26:45.144  6725  6786 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:26:45.144  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:26:45.144  6725  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:26:45.144  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:26:45.145  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:26:45.145  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:26:45.145  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:26:45.145  6725  6786 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e7bedc3 not in the list
08-17 14:26:45.146  6725  6786 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-17 14:26:45.147  6725  6786 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:26:45.147  6725  6786 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:26:45.147  672,5  6786 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 14:26:45.149  6725  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:26:45.149  6725  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:26:45.149  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:26:45.149  6725  6786 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32897572 not in the list
08-17 14:26:45.149  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:26:45.149  6725  6786 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e7bedc3 not in the list
08-17 14:26:45.149  6725  6786 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:26:45.149  6725  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:26:45.149  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:26:45.149  6725  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:26:45.149  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:26:45.150  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:26:45.150  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:26:45.150  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:26:45.150  6725  6786 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e7bedc3 not in the list
08-17 14:26:45.154  6725  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-17 14:26:45.154  6725  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-17 14:26:45.154  6725  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-17 14:26:45.154  6725  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-17 14:26:45.154  6725  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-17 14:26:45.154  6725  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-17 14:26:45.154  6725  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-17 14:26:45.154  6725  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-17 14:26:45.154  6725  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-17 14:26:45.154  6725  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-17 14:26:45.154  6725  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-17 14:26:45.154  6725  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-17 14:26:45.154  6725  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,08-17 14:26:45.154  6725  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-17 14:26:45.154  6725  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-17 14:26:45.154  6725  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-17 14:26:45.154  6725  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-17 14:26:45.154  6725  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-17 14:26:45.154  6725  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-17 14:26:45.155  6725  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-17 14:26:45.155  6725  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-17 14:26:45.155  6725  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-17 14:26:45.155  6725  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-17 14:26:45.155  6725  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-17 14:26:45.155  6725  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-17 14:26:45.155  6725  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-17 14:26:45.155  6725  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-17 14:26:45.155  6725  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-17 14:26:45.155  6725  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-17 14:26:45.155  6725  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-17 14:26:45.155  6725  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-17 14:26:45.155  6725  6786 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:26:45.155  6725  6786 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:26:45.155  6725  6786 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:26:45.155  6725  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:26:45.155  6725  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:26:45.155  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:26:45.155  6725  6786 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32897572 not in the list
08-17 14:26:45.155  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:26:45.155  6725  6786 E org.thaliproject.p2p.,btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e7bedc3 not in the list
08-17 14:26:45.155  6725  6786 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:26:45.155  6725  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:26:45.156  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:26:45.156  6725  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:26:45.156  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:26:45.156  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:26:45.156  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:26:45.156  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:26:45.156  6725  6786 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e7bedc3 not in the list
08-17 14:26:45.157  6725  6786 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-17 14:26:45.160  6725  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 14:26:45.163  6725  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 14:26:45.163  6725  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:26:45.163  6725  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 14:26:45.163  6725  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:26:45.163  6725  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 14:26:45.163  6725  6786 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 14:26:45.163  6725  6786 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 14:26:45.163  6725  6786 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 14:26:45.164  6725  6786 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 14:26:45.164  6725  6786 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 14:26:45.165  6725  6786 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 14:26:45.165  6725  6786 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 14:26:45.165  6725  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:26:45.165  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 14:26:45.165  6725  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 14:26:45.165  6725  6786 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-17 14:26:45.166  6725  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:26:45.169  6725  6786 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-17 14:26:45.169  1036  1874 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-17 14:26:45.174  6725  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-17 14:26:45.178  6725  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-17 14:26:45.179  6725  6786 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
08-17 14:26:45.180  6725  6786 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-17 14:26:45.180  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 14:26:45.181  6725  6786 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-17 14:26:45.181  6725  6786 I io.jxcore.node.ConnectionHelper: start: OK
,08-17 14:26:45.184  6725  6786 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:26:45.184  6725  6786 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:26:45.184  6725  6786 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:26:45.184  6725  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 14:26:45.184  6725  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:26:45.184  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 14:26:45.184  6725  6786 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32897572 not in the list
08-17 14:26:45.184  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:26:45.184  6725  6786 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e7bedc3 not in the list
08-17 14:26:45.184  6725  6786 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:26:45.184  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:26:45.185  6725  6786 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-17 14:26:45.186  6725  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 14:26:45.188  6725  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 14:26:45.188  6725  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:26:45.188  6725  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 14:26:45.188  6725  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:26:45.188  6725  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 14:26:45.188  6725  6786 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 14:26:45.188  6725  6786 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 14:26:45.188  6725  6786 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 14:26:45.188  6725  6786 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 14:26:45.189  6725  6786 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 14:26:45.190  6725  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:26:45.191  6725  6786 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 14:26:45.191  6725  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:26:45.191  6725  6786 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 14:26:45.191  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 14:26:45.191  6725  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 14:26:45.191  6725  6786 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-17 14:26:45.194  6725  6786 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-17 14:26:45.194  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 14:26:45.195  6725  6786 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-17 14:26:45.195  6725  6786 I io.jxcore.node.ConnectionHelper: start: OK
08-17 14:26:45.196  6725  6786 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:26:45.196  6725  6786 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:26:45.196  6725  6786 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:26:45.197  6725  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:26:45.197  6725  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:26:45.197  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 14:26:45.197  6725  6786 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32897572 not in the list
08-17 14:26:45.197  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:26:45.197  6725  6786 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e7bedc3 not in the list
08-17 14:26:45.197  6725  6786 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:26:45.197  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:26:45.197  6725  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:26:45.197  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:26:45.198  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:26:45.198  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:26:45.199  6725  6786 D BluetoothLeScanner: could not find callback wrapper
08-17 14:26:45.199  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 14:26:45.199  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:26:45.199  6725  6786 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e7bedc3 not in the list
08-17 14:26:45.199  6725  6786 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-17 14:26:45.200  6725  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 14:26:45.202  6725  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 14:26:45.202  6725  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:26:45.202  6725  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 14:26:45.202  6725  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:26:45.202  6725  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 14:26:45.202  6725  6786 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 14:26:45.202  6725  6786 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-,17 14:26:45.202  6725  6786 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 14:26:45.203  6725  6786 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 14:26:45.203  6725  6786 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 14:26:45.204  6725  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:26:45.205  6725  6786 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 14:26:45.205  6725  6786 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 14:26:45.205  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 14:26:45.205  6725  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 14:26:45.205  6725  6786 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-17 14:26:45.210  6725  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:26:45.284  1036  1052 I art     : Explicit concurrent mark sweep GC freed 25404(1326KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 1.458ms total 77.903ms
,08-17 14:26:45.289  6725  6786 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-17 14:26:45.290  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 14:26:45.292  6725  6786 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-17 14:26:45.292  6725  6786 I io.jxcore.node.ConnectionHelper: start: OK
08-17 14:26:45.292  6725  6786 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:26:45.292  6725  6786 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:26:45.292  6725  6786 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:26:45.294  6725  6786 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:26:45.294  6725  6786 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:26:45.294  6725  6786 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:26:45.294  6725  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:26:45.295  6725  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 14:26:45.299  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 14:26:45.299  6725  6786 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32897572 not in the list
08-17 14:26:45.299  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:26:45.299  6725  6786 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e7bedc3 not in the list
08-17 14:26:45.299  6725  6786 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:26:45.299  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:26:45.300  6725  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:26:45.300  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:26:45.301  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:26:45.301  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:26:45.302  6725  6786 D BluetoothLeScanner: could not find callback wrapper
08-17 14:26:45.302  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 14:26:45.302  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:26:45.302  6725  6786 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e7bedc3 not in the list
08-17 14:26:45.303  6725  6786 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-17 14:26:45.303  6725  6786 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:26:45.303  6725  6786 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:26:45.304  6725  6786 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:26:45.304  6725  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:26:45.304  6725  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:26:45.304  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:26:45.304  6725  6786 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32897572 not in the list
08-17 14:26:45.304  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:26:45.304  6725  6786 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e7bedc3 not in the list
08-17 14:26:45.304  6725  6786 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:26:45.304  6725  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:26:45.304  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 14:26:45.304  6725  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:26:45.304  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:26:45.305  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:26:45.305  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:26:45.306  6725  6786 D BluetoothLeScanner: could not find callback wrapper
,08-17 14:26:45.306  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 14:26:45.306  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:26:45.306  6725  6786 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e7bedc3 not in the list
08-17 14:26:45.307  6725  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-17 14:26:45.307  6725  6786 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:26:45.307  6725  6786 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:26:45.307  6725  6786 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:26:45.308  6725  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
08-17 14:26:45.308  6725  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:26:45.308  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:26:45.308  6725  6786 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32897572 not in the list
08-17 14:26:45.308  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 14:26:45.308  6725  6786 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e7bedc3 not in the list
08-17 14:26:45.308  6725  6786 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:26:45.308  6725  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:26:45.308  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:26:45.308  6725  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:26:45.308  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:26:45.310  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:26:45.310  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 14:26:45.311  6725  6786 D BluetoothLeScanner: could not find callback wrapper
08-17 14:26:45.311  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 14:26:45.311  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:26:45.311  6725  6786 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e7bedc3 not in the list
08-17 14:26:45.313  6725  6786 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-17 14:26:45.314  6725  6786 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:26:45.314  6725  6786 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:26:45.314  6725  6786 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:26:45.315  6725  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:26:45.315  6725  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:26:45.315  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:26:45.315  6725  6786 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32897572 not in the list
08-17 14:26:45.315  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:26:45.315  6725  6786 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e7bedc3 not in the list
08-17 14:26:45.315  6725  6786 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:26:45.315  6725  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:26:45.315  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:26:45.315  6725  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:26:45.315  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:26:45.317  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:26:45.317  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:26:45.317  6725  6786 D BluetoothLeScanner: could not find callback wrapper
08-17 14:26:45.317  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 14:26:45.317  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:26:45.317  6725  6786 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e7bedc3 not in the list
08-17 14:26:45.318  6725  6786 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-17 14:26:45.319  6725  6786 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:26:45.319  6725  6786 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:26:45.319  6725  6786 V io.jxcore.node.StartStopOperationH,andler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:26:45.319  6725  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:26:45.319  6725  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:26:45.319  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:26:45.319  6725  6786 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32897572 not in the list
08-17 14:26:45.319  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:26:45.319  6725  6786 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e7bedc3 not in the list
08-17 14:26:45.319  6725  6786 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:26:45.319  6725  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:26:45.319  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:26:45.319  6725  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:26:45.319  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:26:45.320  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:26:45.320  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:26:45.321  6725  6786 D BluetoothLeScanner: could not find callback wrapper
08-17 14:26:45.321  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 14:26:45.321  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:26:45.321  6725  6786 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e7bedc3 not in the list
08-17 14:26:45.322  6725  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-17 14:26:45.324  6725  6786 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-17 14:26:45.324  6725  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-17 14:26:45.324  6725  6786 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-17 14:26:45.324  6725  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-17 14:26:45.324  6725  6786 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-17 14:26:45.324  6725  6786 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:26:45.324  6725  6786 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:26:45.324  6725  6786 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:26:45.325  6725  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:26:45.326  6725  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:26:45.326  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:26:45.326  6725  6786 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32897572 not in the list
08-17 14:26:45.326  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:26:45.326  6725  6786 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e7bedc3 not in the list
08-17 14:26:45.326  6725  6786 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:26:45.326  6725  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:26:45.326  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:26:45.326  6725  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:26:45.326  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:26:45.328  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:26:45.328  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:26:45.329  6725  6786 D BluetoothLeScanner: could not find callback wrapper
08-17 14:26:45.329  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 14:26:45.329  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:26:45.329  6725  6786 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e7bedc3 not in the list
08-17 14:26:45.330  6725  6786 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-17 14:26:45.330  6725  6786 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-17 14:26:45.330  6725  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-17 14:26:45.333  6725  6786 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-17 14:26:45.334  6725  6786 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-17 14:26:45.334  6725  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-17 14:26:45.334  6725  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-17 14:26:45.334  6725  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-17 14:26:45.334  6725  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-17 14:26:45.334  6725  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-17 14:26:45.334  6725  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-17 14:26:45.334  6725  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-17 14:26:45.334  6725  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-17 14:26:45.334  6725  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-17 14:26:45.334  6725  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-17 14:26:45.334  6725  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-17 14:26:45.334  6725  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-17 14:26:45.334  6725  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-17 14:26:45.334  6725  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-17 14:26:45.334  6725  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-17 14:26:45.334  6725  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-17 14:26:45.335  6725  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-17 14:26:45.335  6725  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-17 14:26:45.335  6725  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-17 14:26:45.335  6725  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-17 14:26:45.335  6725  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-17 14:26:45.335  6725  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-17 14:26:45.335  6725  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-17 14:26:45.335  6725  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-17 14:26:45.335  6725  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-17 14:26:45.335  6725  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-17 14:26:45.335  6725  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-17 14:26:45.335  6725  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-17 14:26:45.335  6725  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-17 14:26:45.335  6725  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-17 14:26:45.335  6725  6786 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-17 14:26:45.335  6725  6786 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-17 14:26:45.336  6725  6786 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-17 14:26:45.336  6725  6786 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-17 14:26:45.336  6725  6786 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-17 14:26:45.336  6725  6786 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-17 14:26:45.336  6725  6786 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-17 14:26:45.336  6725  6786 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-17 14:26:45.336  6725  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-17 14:26:45.338  6725  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-17 14:26:45.339  6725  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-17 14:26:45.339  6725  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-17 14:26:45.341  6725  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-17 14:26:45.341  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-17 14:26:45.342  6725  6786 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-17 14:26:45.342  6725  6786 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-17 14:26:45.342  6725  6786 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-17 14:26:45.342  6725  6786 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:26:45.342  6725  6786 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:26:45.342  6725  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 842)
08-17 14:26:45.342  6725  6786 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:26:45.343  6725  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
08-17 14:26:45.343  6725  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:26:45.343  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:26:45.344  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-17 14:26:45.344  6725  6786 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32897572 not in the list
08-17 14:26:45.344  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:26:45.344  6725  6786 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e7bedc3 not in the list
08-17 14:26:45.344  6725  6786 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:26:45.344  6725  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:26:45.344  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:26:45.344  6725  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:26:45.344  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:26:45.346  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:26:45.348  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:26:45.348  6725  6786 D BluetoothLeScanner: could not find callback wrapper
08-17 14:26:45.348  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 14:26:45.348  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:26:45.348  6725  6786 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e7bedc3 not in the list
08-17 14:26:45.350  6725  6786 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-17 14:26:45.352  6725  6786 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:26:45.353  6725  6786 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:26:45.353  6725  6786 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:26:45.353  6725  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:26:45.353  6725  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 842
08-17 14:26:45.353  6725  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:26:45.353  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:26:45.353  6725  6786 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32897572 not in the list
08-17 14:26:45.353  6725  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 842)
08-17 14:26:45.353  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:26:45.353  6725  6786 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e7bedc3 not in the list
08-17 14:26:45.353  6725  6786 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:26:45.353  6725  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:26:45.353  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:26:45.353  6725  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 842)
08-17 14:26:45.353  6725  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:26:45.353  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:26:45.354  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:26:45.354  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:26:45.355  6725  6786 D BluetoothLeScanner: could not find callback wrapper
08-17 14:26:45.355  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 14:26:45.355  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:26:45.355  6725  6786 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e7bedc3 not in the list
08-17 14:26:45.357  6725  6786 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-17 14:26:45.357  6725  6786 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:26:45.357  6725  6786 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:26:45.357  6725  6786 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:26:45.357  6725  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:26:45.358  6725  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:26:45.358  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:26:45.358  6725  6786 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32897572 not in the list
08-17 14:26:45.358  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:26:45.358  6725  6786 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e7bedc3 not in the list
08-17 14:26:45.358  6725  6786 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:26:45.358  6725  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:26:45.358  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:26:45.358  6725  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:26:45.358  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:26:45.359  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:26:45.359  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:26:45.361  6725  6786 D BluetoothLeScanner: could not find callback wrapper
08-17 14:26:45.361  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 14:26:45.361  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:26:45.361  6725  6786 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e7bedc3 not in the list
08-17 14:26:45.362  6725  6786 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-17 14:26:45.362  6725  6786 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-17 14:26:45.362  6725  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-17 14:26:45.362  6725  6786 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-17 14:26:45.363  6725  6786 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-17 14:26:45.363  6725  6786 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-17 14:26:45.363  6725  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-17 14:26:45.363  6725  6786 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-17 14:26:45.363  6725  6786 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-17 14:26:45.363  6725  6786 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-17 14:26:45.363  6725  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-17 14:26:45.363  6725  6786 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-17 14:26:45.363  6725  6786 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:26:45.363  6725  6786 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:26:45.363  6725  6786 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:26:45.364  6725  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:26:45.364  6725  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:26:45.364  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:26:45.365  6725  6786 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32897572 not in the list
08-17 14:26:45.365  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:26:45.365  6725  6786 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e7bedc3 not in the list
08-17 14:26:45.365  6725  6786 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:26:45.365  6725  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:26:45.365  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:26:45.365  6725  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:26:45.365  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:26:45.372  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:26:45.372  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:26:45.372  6725  6786 D BluetoothLeScanner: could not find callback wrapper
08-17 14:26:45.372  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 14:26:45.373  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:26:45.373  6725  6786 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e7bedc3 not in the list
08-17 14:26:45.373  6725  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:26:45.373  6725  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:26:45.376  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:26:45.376  6725  6786 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32897572 not in the list
08-17 14:26:45.376  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:26:45.376  6725  6786 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e7bedc3 not in the list
08-17 14:26:45.376  6725  6786 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:26:45.376  6725  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:26:45.376  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:26:45.376  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:26:45.376  6725  6786 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e7bedc3 not in the list
08-17 14:26:45.377  6725  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:26:45.377  6725  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:26:45.377  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:26:45.377  6725  6786 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32897572 not in the list
08-17 14:26:45.377  6725  6786 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:26:45.377  6725  6786 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:26:45.377  6725  6786 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:26:45.378  6725  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:26:45.378  6725  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:26:45.378  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:26:45.378  6725  6786 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32897572 not in the list
08-17 14:26:45.378  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:26:45.378  6725  6786 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e7bedc3 not in the list
08-17 14:26:45.378  6725  6786 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:26:45.378  6725  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:26:45.378  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:26:45.378  6725  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:26:45.378  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:26:45.379  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:26:45.379  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:26:45.380  6725  6786 D BluetoothLeScanner: could not find callback wrapper
08-17 14:26:45.380  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 14:26:45.380  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:26:45.380  6725  6786 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e7bedc3 not in the list
08-17 14:26:45.382  6725  6786 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-17 14:26:45.383  6725  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 14:26:45.383  6725  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-17 14:26:45.384  6725  6786 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-17 14:26:45.384  6725  6786 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-17 14:26:45.385  6725  6725 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-17 14:26:45.386  6725  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-17 14:26:45.386  1036  2000 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 14:26:45.386  6725  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-17 14:26:45.387  6725  6805 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 14:26:45.387  6725  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:26:45.387  6725  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-17 14:26:45.388  6725  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-17 14:26:45.388  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-17 14:26:45.388  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:26:45.388  6725  6786 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-17 14:26:45.388  6725  6725 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-17 14:26:45.388  6725  6786 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32897572 not in the list
08-17 14:26:45.388  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:26:45.388  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-17 14:26:45.388  6725  6786 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 14:26:45.389  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-17 14:26:45.390  6725  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-17 14:26:45.391  3845  3978 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=82
,08-17 14:26:45.392  6725  6786 D BluetoothLeScanner: could not find callback wrapper
08-17 14:26:45.392  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 14:26:45.392  6725  6786 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-17 14:26:45.392  6725  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:26:45.392  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:26:45.393  6725  6786 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 14:26:45.394  6725  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 14:26:45.394  6725  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 14:26:45.394  6725  6725 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 14:26:45.394  6725  6786 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e7bedc3 not in the list
08-17 14:26:45.395  6725  6786 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:26:45.395  6725  6786 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:26:45.395  6725  6786 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:26:45.395  6725  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:26:45.395  6725  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:26:45.395  6725  6805 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-17 14:26:45.395  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:26:45.395  6725  6786 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32897572 not in the list
08-17 14:26:45.395  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:26:45.395  6725  6805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-17 14:26:45.396  6725  6786 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e7bedc3 not in the list
08-17 14:26:45.396  6725  6786 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:26:45.396  6725  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:26:45.396  6725  6805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-17 14:26:45.396  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:26:45.396  6725  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:26:45.396  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:26:45.397  6725  6725 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-17 14:26:45.398  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:26:45.398  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:26:45.398  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:26:45.398  6725  6786 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e7bedc3 not in the list
08-17 14:26:45.400  6725  6786 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-17 14:26:45.400  6725  6786 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-17 14:26:45.400  6725  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-17 14:26:45.401  6725  6786 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-17 14:26:45.402  6725  6786 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:26:45.402  6725  6786 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:26:45.402  6725  6786 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:26:45.402  6725  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:26:45.402  6725  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:26:45.402  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:26:45.402  6725  6786 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32897572 not in the list
08-17 14:26:45.402  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:26:45.402  6725  6786 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e7bedc3 not in the list
08-17 14:26:45.402  6725  6786 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:26:45.402  6725  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:26:45.402  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:26:45.402  6725  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:26:45.402  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:26:45.403  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:26:45.403  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:26:45.403  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:26:45.403  6725  6786 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e7bedc3 not in the list
08-17 14:26:45.405  1036  1640 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 14:26:45.406  1036  1909 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 14:26:45.407  1036  1928 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 14:26:45.408  6725  6786 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:26:45.408  6725  6786 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:26:45.408  6725  6786 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:26:45.409  6725  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:26:45.409  6725  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:26:45.409  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:26:45.409  6725  6786 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32897572 not in the list
08-17 14:26:45.409  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:26:45.409  6725  6786 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e7bedc3 not in the list
08-17 14:26:45.409  6725  6786 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:26:45.409  6725  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:26:45.409  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:26:45.409  6725  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:26:45.409  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:26:45.411  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:26:45.411  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:26:45.411  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:26:45.411  6725  6786 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e7bedc3 not in the list
08-17 14:26:45.412  6725  6786 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:26:45.413  6725  6786 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:26:45.413  6725  6786 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:26:45.413  6725  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:26:45.413  6725  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:26:45.413  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:26:45.413  6725  6786 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32897572 not in the list
08-17 14:26:45.413  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:26:45.413  6725  6786 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e7bedc3 not in the list
08-17 14:26:45.413  6725  6786 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:26:45.413  6725  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:26:45.413  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:26:45.413  6725  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:26:45.413  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:26:45.415  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:26:45.415  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:26:45.415  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:26:45.415  6725  6786 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e7bedc3 not in the list
08-17 14:26:45.417  6725  6786 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-17 14:26:45.417  6725  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-17 14:26:45.417  6725  6786 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-17 14:26:45.417  6725  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-17 14:26:45.417  6725  6786 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-17 14:26:45.417  6725  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-17 14:26:45.420  6725  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-17 14:26:45.420  6725  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-17 14:26:45.421  6725  6786 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-17 14:26:45.421  6725  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-17 14:26:45.421  6725  6786 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-17 14:26:45.421  6725  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-17 14:26:45.421  6725  6786 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-17 14:26:45.421  6725  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-17 14:26:45.422  6725  6786 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-17 14:26:45.422  6725  6786 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-17 14:26:45.423  6725  6786 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-17 14:26:45.423  6725  6786 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-17 14:26:45.423  6725  6786 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-17 14:26:45.423  6725  6786 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-17 14:26:45.425  6725  6786 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 14:26:45.425  6725  6786 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2c022d58 added. We now have 2 listener(s)
08-17 14:26:45.425  6725  6786 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 14:26:45.427  6725  6786 D BluetoothAdapter: enable(): BT is already enabled..!
08-17 14:26:45.428  1036  1638 D WifiServiceImplEx: setWifiEnabled: true pid=6725, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-17 14:26:45.429  1036  1638 D WifiService: setWifiEnabled: true pid=6725, uid=10118
08-17 14:26:45.429  1036  1638 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-17 14:26:45.430  6725  6786 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 14:26:45.430  6725  6786 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@10ce4eb1 added. We now have 3 listener(s)
08-17 14:26:45.430  6725  6786 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 14:26:45.435  6725  6786 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 14:26:45.435  6725  6786 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@11b79f96 added. We now have 4 listener(s)
08-17 14:26:45.435  6725  6786 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 14:26:45.437  6725  6786 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 14:26:45.438  6725  6786 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1d2d717 added. We now have 5 listener(s)
,08-17 14:26:45.438  6725  6786 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 14:26:45.440  1036  1560 D WifiServiceImplEx: setWifiEnabled: false pid=6725, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-17 14:26:45.440  1036  1560 D WifiService: setWifiEnabled: false pid=6725, uid=10118
08-17 14:26:45.440  1036  1560 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-17 14:26:45.460  6725  6803 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
08-17 14:26:45.460  6725  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 842)
,08-17 14:26:45.463  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-17 14:26:45.463  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-17 14:26:45.463  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-17 14:26:45.464  1036  2000 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 14:26:45.464  1036  1523 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-17 14:26:45.465  1036  2000 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@1c0d0bb mBinding = false
08-17 14:26:45.465  1036  1523 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-17 14:26:45.465  1036  1523 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-17 14:26:45.466  1036  1523 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-17 14:26:45.466  1036  1523 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-17 14:26:45.467  1036  1523 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-17 14:26:45.467  1036  1523 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-17 14:26:45.467  1036  1523 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-17 14:26:45.467  1036  1523 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-17 14:26:45.467  1036  1523 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-17 14:26:45.486  1036  1523 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-17 14:26:45.486  1036  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-17 14:26:45.487  2698  2698 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-17 14:26:45.487  1036  1522 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:26:45.487  1036  1522 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,08-17 14:26:45.487  1036  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-17 14:26:45.488  1036  1523 D WifiNative-wlan0: doBoolean: SET ps 1
08-17 14:26:45.488  1036  1523 D WifiNative-wlan0: SET ps 1: returned true
08-17 14:26:45.488  1036  2814 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:26:45.494   331   894 D CommandListener: Clearing all IP addresses on wlan0
08-17 14:26:45.497  1036  1103 D BluetoothManagerService: Message: 2
,08-17 14:26:45.498  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-17 14:26:45.498  6725  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 14:26:45.499  1036  1103 D BluetoothManagerService: Sending off request.
08-17 14:26:45.500  3845  3865 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-17 14:26:45.501  3845  3939 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-17 14:26:45.501  3845  3939 D BluetoothAdapterProperties: Setting state to 13
08-17 14:26:45.501  3845  3939 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-17 14:26:45.501  6725  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 14:26:45.501  6725  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:26:45.501  6725  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 14:26:45.501  6725  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:26:45.501  6725  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 14:26:45.501  6725  6786 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 14:26:45.501  6725  6786 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 14:26:45.501  6725  6786 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 14:26:45.501  3845  3939 D BluetoothAdapterProperties: onBluetoothDisable()
08-17 14:26:45.502  6725  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:26:45.502  3845  3939 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-17 14:26:45.502  6725  6786 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 14:26:45.502  6725  6786 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 14:26:45.504  6725  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:26:45.504  6725  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 14:26:45.504  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:26:45.504  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 14:26:45.504  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:26:45.504  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 14:26:45.504  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 14:26:45.504  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 14:26:45.504  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 14:26:45.504  6725  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:26:45.504  6725  6725 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 14:26:45.505  3845  3945 D BluetoothAdapterProperties: Scan Mode:20
08-17 14:26:45.505  3845  3939 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-17 14:26:45.506  3845  4238 V BluetoothFtpS,ervice:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-17 14:26:45.507  3845  3939 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-17 14:26:45.507  6725  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:26:45.509  3845  4200 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-17 14:26:45.509  3845  4200 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-17 14:26:45.509  3845  4200 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-17 14:26:45.509  3845  4200 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-17 14:26:45.509  3845  4200 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-17 14:26:45.509  3845  4200 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-17 14:26:45.509  3845  4200 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-17 14:26:45.509  3845  4200 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-17 14:26:45.510  3845  4201 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-17 14:26:45.510  3845  4237 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-17 14:26:45.511  3845  4249 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-17 14:26:45.511  3845  4034 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-17 14:26:45.512  3845  4034 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-17 14:26:45.513  3845  4034 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-17 14:26:45.513  3845  4034 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-17 14:26:45.513  3845  4034 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-17 14:26:45.513  3845  4034 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-17 14:26:45.513  3845  4034 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 14:26:45.513  3845  4034 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-17 14:26:45.513  3845  4034 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 14:26:45.513  3845  4034 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-17 14:26:45.513  3845  4034 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-17 14:26:45.513  3845  4034 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-17 14:26:45.513  3845  4034 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-17 14:26:45.514  3845  4034 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-17 14:26:45.514  1036  1103 D BluetoothManagerService: Message: 60
08-17 14:26:45.514  1036  1103 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-17 14:26:45.514  1036  1103 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-17 14:26:45.518  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-17 14:26:45.518  1036  1036 D Ulp_jni : JNI:system_update. Event-4
,08-17 14:26:45.523  6725  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:26:45.523  6725  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 14:26:45.523  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:26:45.523  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 14:26:45.523  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:26:45.523  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 14:26:45.523  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 14:26:45.523  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 14:26:45.523  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 14:26:45.524  6725  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:26:45.524  6725  6725 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 14:26:45.525  6725  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:26:45.534  1036  1909 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
,08-17 14:26:45.537  1036  1530 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-17 14:26:45.538  1036  1530 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
08-17 14:26:45.540  1036  2810 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-6ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:26:45.540  1036  2810 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-6ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:26:45.540  1036  2810 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-17 14:26:45.541  1036  2810 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-1ms what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:26:45.541  1036  2810 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
,08-17 14:26:45.556  1036  1099 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6817 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-17 14:26:45.557  1929  1929 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:26:45.558  1590  1590 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-17 14:26:45.559  3845  3845 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:26:45.559  3845  3845 D BluetoothMapService: STATE_TURNING_OFF
08-17 14:26:45.559  3845  3845 V BluetoothMapService: Handler(): got msg=4
08-17 14:26:45.559  3845  3845 D BluetoothMapService: MAP Service closeService in
08-17 14:26:45.559  3845  3845 D BluetoothMapMasInstance: MAP Service shutdown
08-17 14:26:45.560  3845  3845 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-17 14:26:45.560  3845  3845 V BluetoothMapService: MAP Service closeService out
08-17 14:26:45.561  3845  3845 V BtOppService: Receiver DISABLED_ACTION 
08-17 14:26:45.561  3845  3845 I BtOppRfcommListener: stopping Accept Thread
08-17 14:26:45.561  3845  3845 V BtOppRfcommListener: close mBtServerSocket
08-17 14:26:45.561  3845  3845 V BtOppRfcommListener: waiting for thread to terminate
08-17 14:26:45.561  6725  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:26:45.561  6725  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 14:26:45.561  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:26:45.561  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 14:26:45.561  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:26:45.561  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 14:26:45.561  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 14:26:45.561  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 14:26:45.561  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 14:26:45.562  6725  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:26:45.562  6725  6725 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-17 14:26:45.564  6725  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:26:45.564  6725  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 14:26:45.564  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:26:45.564  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 14:26:45.564  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:26:45.564  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 14:26:45.564  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 14:26:45.564  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 14:26:45.564  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 14:26:45.565  6725  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:26:45.565  6725  6725 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-17 14:26:45.565  3845  4237 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-17 14:26:45.565  3845  3845 V BtOppRfcommL,istener: done waiting for thread to terminate
08-17 14:26:45.579  1036  1530 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
,08-17 14:26:45.580   331  6835 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-17 14:26:45.580  1036  1530 D DSQN    : disableDataServiceNotify
,08-17 14:26:45.580  1036  1530 D DSQN    : stop dsqn bin
08-17 14:26:45.580  1036  2810 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
08-17 14:26:45.582  1036  1101 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-17 14:26:45.604  1036  1099 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6837 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-17 14:26:45.607  3845  3845 V BtOppService: onDestroy
08-17 14:26:45.609  1036  1522 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:26:45.609  1036  1522 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:26:45.609  1036  1523 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 14:26:45.609  1036  1522 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@335234
08-17 14:26:45.609  1036  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 14:26:45.609  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-17 14:26:45.610  1036  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 14:26:45.610  3845  3845 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-17 14:26:45.610  1036  1523 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 14:26:45.611  1036  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 14:26:45.611  1036  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 14:26:45.611  1036  1523 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-17 14:26:45.611  1929  1929 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-17 14:26:45.612  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:26:45.612  1036  1523 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 14:26:45.612  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:26:45.612  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-17 14:26:45.612  1036  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 14:26:45.612  1036  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 14:26:45.612  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-17 14:26:45.615  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:26:45.615  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:26:45.615  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-17 14:26:45.616  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 1
08-17 14:26:45.616  1036  1036 D RttService: SCAN_AVAILABLE : 1
08-17 14:26:45.616  1036  1542 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:26:45.616  1036  1541 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:26:45.617  1036  1522 D LGWifiP2pService: P2pDisablingState
08-17 14:26:45.617  1036  1522 D LGWifiP2pService: P2pDisablingState{ when=-8ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:26:45.617  1036  1522 D LGWifiP2pService: p2p socket connection lost
08-17 14:26:45.617  1036  1522 D LGWifiP2pService: P2pDisabledState
08-17 14:26:45.618  1036  1523 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
,08-17 14:26:45.618  1036  1522 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:26:45.618  1036  1522 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:26:45.618  1036  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-17 14:26:45.618  2698  2698 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-17 14:26:45.619  1036  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-17 14:26:45.619  1036  1523 D WifiNative-wlan0: doBoolean: SET ps 1
08-17 14:26:45.620  1929  1929 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-17 14:26:45.620  1929  1929 D WfdsService: WifiP2pState is changed : false
08-17 14:26:45.620  1929  2234 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-17 14:26:45.620  1929  2234 D WfdsService: Set the WFDS Monitor: false
08-17 14:26:45.621  1929  2234 D WfdsMonitor: WFDS Monitor is stopped
08-17 14:26:45.621  1929  2234 D WfdsService: STATE : WfdsDisabledState - enter
08-17 14:26:45.621  1929  2744 D CtrlSupplicant: Received on exit socket, terminate
08-17 14:26:45.621  1929  2744 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-17 14:26:45.621  1929  2744 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-17 14:26:45.621  1929  2744 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-17 14:26:45.621  1929  2234 W WfdsService: DefaultState - msg [9445378] is not handled
08-17 14:26:45.621  1036  1523 D WifiNative-wlan0: SET ps 1: returned true
08-17 14:26:45.621  1929  2235 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-17 14:26:45.622   331   894 D CommandListener: Clearing all IP addresses on wlan0
08-17 14:26:45.624  1036  1523 D WifiNative-p2p0: doBoolean: TERMINATE
08-17 14:26:45.625  1036  1523 D WifiNative-p2p0: TERMINATE: returned true
08-17 14:26:45.625  1036  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-17 14:26:45.625  1036  1523 E WifiStateMachine: useWiFiOffloading() : false
08-17 14:26:45.625  1036  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-17 14:26:45.626  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-17 14:26:45.626  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:26:45.626  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:26:45.626  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-17 14:26:45.631  1036  1530 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-17 14:26:45.631  1036  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 14:26:45.631  1036  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-17 14:26:45.631  1036  1530 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-17 14:26:45.632  1036  1530 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-17 14:26:45.632  1036  1530 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-17 14:26:45.632  1036  1530 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-17 14:26:45.632  1036  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-17 14:26:45.632  1929  1929 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-17 14:26:45.632  1036  2810 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:26:45.632  1036  2810 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:26:45.633  1036  2810 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-17 14:26:45.633  1590  2061 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-17 14:26:45.633  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-17 14:26:45.633  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-17 14:26:45.633  1036  1036 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-17 14:26:45.634  6725  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:26:45.634  6725  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 14:26:45.634  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:26:45.634  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 14:26:45.634  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 14:26:45.634  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 14:26:45.634  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 14:26:45.634  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 14:26:45.634  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 14:26:45.635  6725  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 14:26:45.635  6725  6725 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 14:26:45.636  1036  1521 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-17 14:26:45.638  1036  1530 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-17 14:26:45.638  1036  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-17 14:26:45.638  1036  1530 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-17 14:26:45.638  1036  1530 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 14:26:45.638  1036  1530 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 14:26:45.638  1036  1530 D NetworkManagementService: Removing idletimer
08-17 14:26:45.639  1036  1530 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:26:45.639  1839  1839 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 14:26:45.639  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-17 14:26:45.639  1839  1839 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-17 14:26:45.639  1036  1523 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 14:26:45.639  1036  1530 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-17 14:26:45.639  1036  1523 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-17 14:26:45.640  1036  1521 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-17 14:26:45.641  6725  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:26:45.641  6725  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 14:26:45.641  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:26:45.641  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 14:26:45.641  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 14:26:45.641  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 14:26:45.641  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 14:26:45.641  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 14:26:45.641  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 14:26:45.642  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-17 14:26:45.642  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-17 14:26:45.642  6725  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:26:45.642  6725  6725 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17, 14:26:45.642  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-17 14:26:45.642  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-17 14:26:45.642  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-17 14:26:45.642  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-17 14:26:45.642  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-17 14:26:45.652  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 14:26:45.652  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-17 14:26:45.653  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 14:26:45.656  6837  6837 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-17 14:26:45.656  6837  6837 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-17 14:26:45.656  6837  6837 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-17 14:26:45.656  6837  6837 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-17 14:26:45.657  6837  6837 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-17 14:26:45.657  6837  6837 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-17 14:26:45.668  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 14:26:45.668  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-17 14:26:45.669  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-17 14:26:45.675  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-17 14:26:45.675  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-17 14:26:45.675  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 14:26:45.676  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-17 14:26:45.688  1590  1590 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-17 14:26:45.689  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 14:26:45.689  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 14:26:45.694  1036  2814 D DhcpStateMachine: StoppedState
08-17 14:26:45.694  1036  2814 D DhcpStateMachine: StoppedState{ when=-73ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:26:45.696  1036  1523 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-17 14:26:45.697  1036  1523 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-17 14:26:45.697  6817  6817 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-17 14:26:45.697  6817  6817 W LG Account v2.2: No ProfileInfo entries
08-17 14:26:45.698  6817  6817 I LG Account v2.2: isEnabled: false
08-17 14:26:45.698  6817  6817 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-17 14:26:45.698  6817  6817 I Feature : [Lifetracker]Country: EU
08-17 14:26:45.698  6817  6817 I Feature : [Lifetracker]Operator: OPEN
08-17 14:26:45.698  6817  6817 I Feature : [Lifetracker]Ranking support: false
08-17 14:26:45.698  6817  6817 I Feature : [Lifetracker]Comfort support: false
08-17 14:26:45.698  6817  6817 I Feature : [Lifetracker]Accessory: true
08-17 14:26:45.698  6817  6817 I Feature : [Lifetracker]Health device: true
08-17 14:26:45.698  6817  6817 I Feature : [Lifetracker]Extra Pedometer: false
08-17 14:26:45.698  6817  6817 I Feature : [Lifetracker]Blood glucose device: false
08-17 14:26:45.698  6817  6817 I Feature : [Lifetracker]Device Number: 3
08-17 14:26:45.701  1590  1590 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-17 14:26:45.702  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 14:26:45.702  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 14:26:45.707  6461  6461 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-17 14:26:45.727  2698  2698 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-17 14:26:45.727  2698  2698 I wpa_supplicant: monitor socket send errors count : 1
08-17 14:26:45.727  2698  2698 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1929-2\x00 that cannot receive messages
,08-17 14:26:45.729  1036  2740 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-17 14:26:45.729  1036  2740 D WifiMonitor: Dropping event because (p2p0) is stopped
08-17 14:26:45.738  1036  1909 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6858 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-17 14:26:45.739  1036  1909 I ActivityManager: Killing 6212:com.android.providers.calendar/u0a14 (adj 15): empty #17
,08-17 14:26:45.745  6837  6837 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-17 14:26:45.750   356   356 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 195us total 9.556ms
08-17 14:26:45.760   356   356 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 181us total 8.878ms
,08-17 14:26:45.766  2698  2698 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-17 14:26:45.767  2698  2698 W wpa_supplicant: USIM:  scard_deinit function
08-17 14:26:45.767  1036  1103 D Tethering: InitialState.processMessage what=4
08-17 14:26:45.767  1036  2740 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-17 14:26:45.767  1036  2740 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-17 14:26:45.767  1036  2740 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-17 14:26:45.768  1036  2740 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-17 14:26:45.768  1036  2740 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-17 14:26:45.768  1036  2740 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-17 14:26:45.768  1036  1523 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=327519
08-17 14:26:45.769  1036  1523 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=327519
08-17 14:26:45.769  1036  1523 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=327520  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-17 14:26:45.770  1036  1523 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=327520  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-17 14:26:45.770   356   356 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 209us total 9.751ms
08-17 14:26:45.854  1036  1640 W libprocessgroup: failed to open /acct/uid_10014/pid_6212/cgroup.procs: No such file or directory
,08-17 14:26:45.868  1036  1103 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-17 14:26:45.876  1036  1103 D BluetoothManagerService: Message: 20
08-17 14:26:45.877  1036  1103 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3ad517a2:true
,08-17 14:26:45.879  2698  2698 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-17 14:26:45.880  1036  2740 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-17 14:26:45.880  1036  2740 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
08-17 14:26:45.880  1036  2740 D WifiMonitor: Disconnecting from the supplicant, no more events
08-17 14:26:45.883  1036  1523 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
08-17 14:26:45.892  3845  3845 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-17 14:26:45.893  3845  3845 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:26:45.893  3845  3845 V BluetoothPbapReceiver: ***********state = 13
08-17 14:26:45.895  6725  6725 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-17 14:26:45.897  3845  3845 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
,08-17 14:26:45.899  3845  3845 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:26:45.899  3845  3845 V BluetoothPbapService: state: 13
08-17 14:26:45.899  3845  3845 V BluetoothPbapService: Pbap Service closeService in
08-17 14:26:45.901  2162  2162 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-17 14:26:45.901  1036  1103 D BluetoothManagerService: Message: 30
08-17 14:26:45.903  3845  3845 V BluetoothPbapService: successfully stopped pbap service
08-17 14:26:45.903  3845  3845 V BluetoothPbapService: Pbap Service closeService out
08-17 14:26:45.903  3845  3845 V BluetoothPbapService: Pbap Service onDestroy
08-17 14:26:45.903  3845  3845 V BluetoothPbapService: Pbap Service closeService in
08-17 14:26:45.903  3845  3845 V BluetoothPbapService: Pbap Service closeService out
08-17 14:26:45.903  3845  3845 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-17 14:26:45.910  1036  1103 D BluetoothManagerService: Message: 30
,08-17 14:26:45.913  6837  6837 D LocalBluetoothProfileManager: Adding local MAP profile
08-17 14:26:45.915  6837  6837 D BluetoothMap: Create BluetoothMap proxy object
08-17 14:26:45.915  1036  1103 D BluetoothManagerService: Message: 30
08-17 14:26:45.920  1036  1103 D BluetoothManagerService: Message: 30
08-17 14:26:45.922  6837  6837 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-17 14:26:45.923  6837  6837 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
,08-17 14:26:45.939  6837  6837 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,08-17 14:26:45.943  6837  6837 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
08-17 14:26:45.954  6837  6837 D DockEventReceiver: finishStartingService: stopping service
,08-17 14:26:45.955  6837  6837 D BluetoothInputDevice: Proxy object connected
08-17 14:26:45.956  6837  6837 D HidProfile: Bluetooth service connected
,08-17 14:26:45.959  6858  6858 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-17 14:26:45.964  6858  6858 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-17 14:26:45.964  6858  6858 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-17 14:26:45.967  1036  1909 I ActivityManager: Killing 2142:com.lge.music/u0a34 (adj 15): empty #17
08-17 14:26:45.970  6837  6837 D BluetoothPan: BluetoothPAN Proxy object connected
08-17 14:26:45.972  6837  6837 D PanProfile: Bluetooth service connected
,08-17 14:26:45.974  6837  6837 D BluetoothMap: Proxy object connected
08-17 14:26:45.975  6837  6837 D MapProfile: Bluetooth service connected
,08-17 14:26:45.976  6837  6837 D BluetoothMap: getConnectedDevices()
08-17 14:26:45.976  6837  6837 D BluetoothMap: Bluetooth is Not enabled
08-17 14:26:45.977  6837  6837 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-17 14:26:45.987   335  1371 V AudioFlinger: 2142 died, releasing its sessions
08-17 14:26:45.987   335  1371 V AudioFlinger:  pid 1839 @ 0
08-17 14:26:45.987   335  1371 V AudioFlinger:  pid 3400 @ 1
08-17 14:26:45.988   335  1371 V AudioFlinger:  pid 3400 @ 2
,08-17 14:26:46.009  1036  1964 W libprocessgroup: failed to open /acct/uid_10034/pid_2142/cgroup.procs: No such file or directory
,08-17 14:26:46.026  6837  6837 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-17 14:26:46.026  1036  1523 D WifiOffDelayIfNotUsed: stopMonitoring
,08-17 14:26:46.027  1036  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-17 14:26:46.027  1036  1523 E WifiStateMachine: useWiFiOffloading() : false
08-17 14:26:46.027  1036  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-17 14:26:46.027  1929  1929 D WfdsService: Supplicant Connection state is changed : false
08-17 14:26:46.029  1929  2234 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-17 14:26:46.029  1929  2234 D WfdsService: Set the WFDS Monitor: false
08-17 14:26:46.029  1929  2234 D WfdsMonitor: WFDS Monitor is stopped
08-17 14:26:46.031  1929  1929 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-17 14:26:46.031  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 14:26:46.037  2472  2472 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-17 14:26:46.043  6725  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:26:46.043  6725  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 14:26:46.043  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:26:46.043  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 14:26:46.043  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 14:26:46.043  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 14:26:46.043  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 14:26:46.043  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 14:26:46.043  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 14:26:46.046  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-17 14:26:46.047  1036  1528 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-17 14:26:46.047  1036  1528 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-17 14:26:46.048  6725  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:26:46.048  6725  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 14:26:46.048  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:26:46.048  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 14:26:46.048  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 14:26:46.048  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 14:26:46.048  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 14:26:46.048  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 14:26:46.048  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 14:26:46.085  6837  6837 D LgDataFeature: LgDataFeature() Constructor: none
08-17 14:26:46.086  6837  6837 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-17 14:26:46.096  6837  6837 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 14:26:46.097  6837  6837 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-17 14:26:46.103  6837  6837 D BluetoothPermissionRequest: onReceive
08-17 14:26:46.105  6837  6837 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-17 14:26:46.116  6837  6837 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-17 14:26:46.116  1036  1946 I ActivityManager: Killing 6394:com.android.defcontainer/u0a4 (adj 15): empty #17
,08-17 14:26:46.157  1036  1980 W libprocessgroup: failed to open /acct/uid_10004/pid_6394/cgroup.procs: No such file or directory
,08-17 14:26:46.160  3845  3845 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-17 14:26:46.160  3845  3845 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-17 14:26:46.162  3845  3845 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-17 14:26:46.231  1036  1909 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6887 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-17 14:26:46.234  3845  3845 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:26:46.235  3845  3845 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-17 14:26:46.235  1036  1523 E WifiStateMachine:  InitialState CMD_TETHER_STATE_CHANGE 0 0
,08-17 14:26:46.235  1036  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-17 14:26:46.237  3845  3845 V BluetoothFtpService: Ftp Service onStartCommand
08-17 14:26:46.238  3845  3845 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:26:46.238  3845  3845 V BluetoothFtpService: Ftp Service closeService
08-17 14:26:46.239  3845  3845 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-17 14:26:46.240  3845  3845 V BluetoothFtpService: successfully stopped ftp service
08-17 14:26:46.241  3845  3845 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-17 14:26:46.241  3845  3845 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-17 14:26:46.241  3845  3845 V BluetoothSapReceiver: SapReceiver onReceive 
08-17 14:26:46.241  3845  3845 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:26:46.242  3845  3845 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-17 14:26:46.242  3845  3845 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-17 14:26:46.244  3845  3845 V BluetoothFtpService: Ftp Service onDestroy
08-17 14:26:46.244  3845  3845 V BluetoothFtpService: Ftp Service closeService
08-17 14:26:46.320  1036  1980 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6904 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-17 14:26:46.330  3845  3845 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:26:46.330  3845  3845 V BluetoothSapService: state: 13
08-17 14:26:46.331  3845  3845 V BluetoothSapService: Stopping SAP server process
08-17 14:26:46.332  3845  3845 V BluetoothSapService: Sap Service closeSapService in
08-17 14:26:46.332  3845  3845 V BluetoothSapService: Close listen Socket : 
08-17 14:26:46.332  3845  3845 V BluetoothSapService: Close rfcomm Socket : 
08-17 14:26:46.332  3845  3845 V BluetoothSapService: Close sapd  Socket : 
08-17 14:26:46.332  1036  1365 D PowerManagerServiceEx: acquireWakeLockInternal: lock=822491364, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
08-17 14:26:46.333  3845  3845 V BluetoothSapService: Sap Service closeSapService out
,08-17 14:26:46.333  3845  3845 V BluetoothSapService: Sap Service onDestroy
08-17 14:26:46.333  3845  3845 V BluetoothSapService: Sap Service closeSapService in
,08-17 14:26:46.333  3845  3845 V BluetoothSapService: Close listen Socket : 
08-17 14:26:46.333  3845  3845 V BluetoothSapService: Close rfcomm Socket : 
08-17 14:26:46.333  3845  3845 V BluetoothSapService: Close sapd  Socket : 
08-17 14:26:46.334  3845  3845 V BluetoothSapService: Sap Service closeSapService out
08-17 14:26:46.334  1036  1365 V AlarmManager: ELAPSED_WAKEUP set : Alarm{39ca5b95 type 2 when 328050 com.google.android.gms} when 328050
08-17 14:26:46.351  6887  6887 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-17 14:26:46.376  6887  6887 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-17 14:26:46.403  6904  6904 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-17 14:26:46.420  6887  6887 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-17 14:26:46.420  1036  1051 I ActivityManager: Killing 6508:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,08-17 14:26:46.420  6887  6887 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-17 14:26:46.421  6887  6887 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-17 14:26:46.421  6887  6887 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-17 14:26:46.421  6887  6887 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-17 14:26:46.423  6887  6887 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-17 14:26:46.429  6887  6887 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-17 14:26:46.459  1036  1946 W libprocessgroup: failed to open /acct/uid_10008/pid_6508/cgroup.procs: No such file or directory
,08-17 14:26:46.469  6887  6887 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-17 14:26:46.473  6887  6887 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-17 14:26:46.494  2601  2601 D [Concierge]Service: onStartCommand(). Type : 9
,08-17 14:26:46.507  6887  6887 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-17 14:26:46.511  6887  6887 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-17 14:26:46.512  6461  6461 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-17 14:26:46.516  3845  3945 D bt_hci_bdroid: cleanup
08-17 14:26:46.516  3845  4034 W bt-btif : ag scb idx 1 not allocated
08-17 14:26:46.516  3845  4034 E bt-btif : BTA AG is already disabled, ignoring ...
08-17 14:26:46.516  3845  4036 I bt_lpm  : LPM is already off!!!
08-17 14:26:46.516  3845  4034 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-17 14:26:46.516  3845  4034 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 14:26:46.516  3845  4034 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-17 14:26:46.516  3845  4034 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 14:26:46.516  3845  4034 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-17 14:26:46.516  3845  4034 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-17 14:26:46.516  3845  4034 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-17 14:26:46.516  3845  4034 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 14:26:46.516  3845  4186 I bt_userial_mct: exiting userial_read_thread
08-17 14:26:46.516  3845  4034 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-17 14:26:46.516  3845  4186 D bt_userial_mct: Leaving userial_evt_read_thread()
08-17 14:26:46.516  3845  4034 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 14:26:46.516  3845  4034 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-17 14:26:46.516  3845  4034 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-17 14:26:46.517  3845  4034 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-17 14:26:46.517  3845  4034 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 14:26:46.517  3845  4034 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-17 14:26:46.517  3845  4034 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 14:26:46.517  3845  4034 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-17 14:26:46.517  3845  4034 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-17 14:26:46.517  3845  3945 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-17 14:26:46.517  3845  4034 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-17 14:26:46.517  3845  4036 I bt_vendor: hw_epilog_process
08-17 14:26:46.518  3845  3945 D bt_hci_bdroid: cleanup Finalizing cleanup
08-17 14:26:46.518  3845  3945 D bt_userial_mct: userial_close
08-17 14:26:46.518  3845  3945 E bt_userial_mct: pthread_join() FAILED result:3
08-17 14:26:46.518  3845  3945 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-17 14:26:46.518  6858  6858 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-17 14:26:46.518  6858  6858 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-17 14:26:46.518  6858  6858 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-17 14:26:46.521  6887  6887 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-17 14:26:46.526  6837  6837 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-17 14:26:46.538  6837  6837 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 14:26:46.551  6887  6887 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-17 14:26:46.553  6887  6887 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-17 14:26:46.555  6887  6887 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-17 14:26:46.558  6461  6461 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-17 14:26:46.563  6858  6858 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-17 14:26:46.563  6858  6858 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-17 14:26:46.563  6858  6858 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-17 14:26:46.569  6837  6837 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-17 14:26:46.576  6837  6837 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 14:26:46.580  3845  3945 D bt_hci_bdroid: set_power 0
08-17 14:26:46.581  3845  3945 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-17 14:26:46.581  3845  3945 I bt_vendor: bluetooth satus is on
08-17 14:26:46.581  3845  3945 I bt_vendor: bt-vendor : resetting BT status
08-17 14:26:46.581  3845  3945 I bt_vendor: Starting hciattach daemon
08-17 14:26:46.581  3845  3945 I bt_vendor: try to set false
08-17 14:26:46.582  3845  3945 I bt_vendor: Starting hciattach daemon
08-17 14:26:46.582  3845  3945 I bt_vendor: try to set false
08-17 14:26:46.582  3845  3945 I bt_vendor: cleanup
08-17 14:26:46.583  3845  4034 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
,08-17 14:26:46.583  3845  3945 I GKI_LINUX: GKI_exit_task 0 done
08-17 14:26:46.583  3845  3945 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-17 14:26:46.585  3845  3939 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-17 14:26:46.585  6887  6887 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-17 14:26:46.586  6887  6887 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-17 14:26:46.588  6887  6887 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-17 14:26:46.589  3845  3845 D HeadsetService: Received stop request...Stopping profile...
08-17 14:26:46.658  1036  1980 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6925 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-17 14:26:46.661  3845  3845 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-17 14:26:46.662  3845  3845 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-17 14:26:46.662  3845  3845 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2cbf0167
08-17 14:26:46.662  3845  3964 D HeadsetStateMachine: Exit Disconnected: -1
08-17 14:26:46.663  1036  1036 D BluetoothHeadset: Proxy object disconnected
08-17 14:26:46.663  1839  1839 D BluetoothHeadset: Proxy object disconnected
08-17 14:26:46.663  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-17 14:26:46.664  1839  1839 D BluetoothHeadset: Proxy object disconnected
08-17 14:26:46.664  1839  1839 D BluetoothHeadset: Proxy object disconnected
08-17 14:26:46.666  3845  3845 D A2dpService: Received stop request...Stopping profile...
08-17 14:26:46.666  3845  4016 D A2dpStateMachine: Exit Disconnected: -1
08-17 14:26:46.668  3845  3845 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-17 14:26:46.669  3845  3939 D BluetoothAdapterState: Stopping profile services that were post enabled
08-17 14:26:46.670  3845  3845 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-17 14:26:46.670  3845  3845 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-17 14:26:46.670  3845  3845 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2cbf0167
08-17 14:26:46.672  1036  1036 D BluetoothA2dp: Proxy object disconnected
08-17 14:26:46.672  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-17 14:26:46.673  3845  3845 D HidService: Received stop request...Stopping profile...
08-17 14:26:46.673  3845  3845 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2cbf0167
08-17 14:26:46.675  6837  6837 D BluetoothInputDevice: Proxy object disconnected
08-17 14:26:46.676  6837  6837 D HidProfile: Bluetooth service disconnected
08-17 14:26:46.677  3845  3845 D HealthService: Received stop request...Stopping profile...
08-17 14:26:46.677  3845  3845 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2cbf0167
08-17 14:26:46.679  3845  3845 D HeadsetStateMachine: Unbinding service...
08-17 14:26:46.680  3845  3845 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-17 14:26:46.680  3845  3845 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-17 14:26:46.680  3845  3845 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-17 14:26:46.680  3845  3845 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-17 14:26:46.680  3845  3845 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-17 14:26:46.680  3845  3845 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-17 14:26:46.680  3845  3845 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-17 14:26:46.681  3845  3845 D PanService: Received stop request...Stopping profile...
,08-17 14:26:46.682  3845  3845 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2cbf0167
08-17 14:26:46.683  3845  3845 D BtGatt.DebugUtils: handleDebugAction() action=null
08-17 14:26:46.683  6837  6837 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-17 14:26:46.684  6837  6837 D PanProfile: Bluetooth service disconnected
08-17 14:26:46.684  3845  3845 D BtGatt.GattService: Received stop request...Stopping profile...
08-17 14:26:46.684  3845  3845 D BtGatt.GattService: stop()
08-17 14:26:46.684  3845  3845 D BtGatt.AdvertiseManager: advertise clients cleared
,08-17 14:26:46.686  3845  3845 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2cbf0167
08-17 14:26:46.689  3845  3845 D BluetoothMapService: Received stop request...Stopping profile...
08-17 14:26:46.689  3845  3845 D BluetoothMapService: stop()
08-17 14:26:46.690  3845  3845 D BluetoothMapEmailAppObserver: deinitObservers()
,08-17 14:26:46.690  3845  3845 D BluetoothMapEmailAppObserver: removeReceiver()
08-17 14:26:46.691  3845  3845 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2cbf0167
08-17 14:26:46.693  3845  3845 I BluetoothA2dpServiceJni: cleanupNative
08-17 14:26:46.693  3845  4018 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-17 14:26:46.693  3845  3845 I GKI_LINUX: GKI_exit_task 2 done
08-17 14:26:46.693  6837  6837 D BluetoothMap: Proxy object disconnected
08-17 14:26:46.693  3845  3845 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-17 14:26:46.693  6837  6837 D MapProfile: Bluetooth service disconnected
08-17 14:26:46.694  3845  3845 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-17 14:26:46.694  3845  3845 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-17 14:26:46.694  3845  3845 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-17 14:26:46.694  3845  3845 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-17 14:26:46.694  3845  3845 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-17 14:26:46.694  3845  3845 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-17 14:26:46.694  3845  3845 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-17 14:26:46.696  3845  3845 V BluetoothMapService: Handler(): got msg=4
08-17 14:26:46.696  3845  3845 D BluetoothMapService: MAP Service closeService in
08-17 14:26:46.696  3845  3845 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-17 14:26:46.696  3845  3845 V BluetoothMapService: MAP Service closeService out
08-17 14:26:46.697  3845  3845 D BluetoothMapService: cleanup()
08-17 14:26:46.697  3845  3845 D BluetoothMapService: MAP Service closeService in
08-17 14:26:46.697  3845  3845 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-17 14:26:46.697  3845  3845 V BluetoothMapService: MAP Service closeService out
08-17 14:26:46.697  3845  3939 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-17 14:26:46.697  3845  3939 D BluetoothAdapterProperties: Setting state to 10
08-17 14:26:46.697  3845  3939 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-17 14:26:46.697  1036  1103 D BluetoothManagerService: Message: 60
08-17 14:26:46.698  1036  1103 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-17 14:26:46.698  1036  1103 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-17 14:26:46.698  3845  3939 I BluetoothAdapterState: Entering OffState
08-17 14:26:46.698  6837  6852 D BluetoothPbap: onBluetoothStateChange: up=false
08-17 14:26:46.699  1839  1855 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 14:26:46.699  1839  2394 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-17 14:26:46.701  6837  6853 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-17 14:26:46.701  6837  6852 D BluetoothPan: onBluetoothStateChange on: false
08-17 14:26:46.702  1036  1103 D BluetoothA2dp: onBluetoothStateChange: up=false
08-17 14:26:46.702  1839  1854 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 14:26:46.703  6837  6853 D BluetoothMap: onBluetoothStateChange: up=false
08-17 14:26:46.703  1036  1103 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 14:26:46.705  1036  1103 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-17 14:26:46.705  1036  1103 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-17 14:26:46.707  1036  1103 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-17 14:26:46.707  1036  1103 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-17 14:26:46.708  1036  1103 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@1c0d0bb mBinding = false
08-17 14:26:46.708  1036  1103 D BluetoothManagerService: Sending unbind request.
08-17 14:26:46.709  1036  1103 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
,08-17 14:26:46.713  1590  1590 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-17 14:26:46.714  1929  1929 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:26:46.714  1929  2116 D LGBluetoothAPIService: Message: 2
08-17 14:26:46.714  1929  2116 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@c6db3f6 mBinding = false
08-17 14:26:46.715  1929  2116 D LGBluetoothAPIService: Sending unbind request.
08-17 14:26:46.716  6837  6837 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-17 14:26:46.717  6725  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:26:46.717  6837  6837 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-17 14:26:46.717  6837  6837 D LGBluetoothEventManager: [BTUI] clear device connection state
08-17 14:26:46.718  6725  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:26:46.724  1590  1590 D BluetoothAdapter: 1063439583: getState() :  mService = null. Returning STATE_OFF
08-17 14:26:46.724  1590  1590 D BluetoothAdapter: 1063439583: getState() :  mService = null. Returning STATE_OFF
08-17 14:26:46.728  6837  6837 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-17 14:26:46.732  3845  3945 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-17 14:26:46.732  3845  3845 I GKI_LINUX: GKI_exit_task 1 done
08-17 14:26:46.732  3845  3845 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-17 14:26:46.733  3845  3845 I BluetoothServiceJni: cleanupNative: return from cleanup
08-17 14:26:46.733  3845  3845 I art     : --- WEIRD: removing null entry 246
08-17 14:26:46.733  3845  3845 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-17 14:26:46.733  3845  3845 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-17 14:26:46.734  3845  3845 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-17 14:26:46.738  6837  6837 D DockEventReceiver: finishStartingService: stopping service
08-17 14:26:46.739  3845  3845 I art     : System.exit called, status: 0
08-17 14:26:46.739  3845  3845 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-17 14:26:46.759   335  2176 V AudioFlinger: 3845 died, releasing its sessions
08-17 14:26:46.759   335  2176 V AudioFlinger:  pid 1839 @ 0
08-17 14:26:46.759   335  2176 V AudioFlinger:  pid 3400 @ 1
08-17 14:26:46.759   335  2176 V AudioFlinger:  pid 3400 @ 2
08-17 14:26:46.760  6837  6837 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
,08-17 14:26:46.837  1036  2000 I ActivityManager: Process com.android.bluetooth (pid 3845) has died
08-17 14:26:46.837  1036  2000 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,08-17 14:26:46.849  2162  2162 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-17 14:26:46.883  6858  6858 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-17 14:26:46.898  6837  6837 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-17 14:26:46.911  6837  6837 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 14:26:46.911  6837  6837 D BluetoothPermissionRequest: onReceive
08-17 14:26:46.918  6837  6837 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-17 14:26:46.919  6837  6837 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
,08-17 14:26:46.921  6837  6837 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-17 14:26:46.925  6925  6946 W FormManager: Network not available. Please check & try again.
08-17 14:26:46.980  1036  1964 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6948 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-17 14:26:47.012  6837  6837 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-17 14:26:47.012  6837  6837 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-17 14:26:47.012  6837  6837 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-17 14:26:47.012  6837  6837 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-17 14:26:47.014  6925  6947 V FormManager: Network unavailable.
08-17 14:26:47.014  6837  6837 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-17 14:26:47.019  6925  6947 V FormManager: Network unavailable.
08-17 14:26:47.027  6837  6837 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
,08-17 14:26:47.028  6837  6837 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-17 14:26:47.028  6837  6837 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-17 14:26:47.029  6837  6837 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-17 14:26:47.029  6837  6837 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-17 14:26:47.029  6837  6837 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-17 14:26:47.040  4312  4312 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,08-17 14:26:47.040  4312  4312 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-17 14:26:47.043  4312  4312 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-17 14:26:47.043  1036  1051 I ActivityManager: Killing 5999:com.lge.appbox.client/u0a11 (adj 15): empty #17
08-17 14:26:47.054  6948  6948 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-17 14:26:47.055  6948  6948 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-17 14:26:47.055  6948  6948 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
,08-17 14:26:47.056  6948  6948 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-17 14:26:47.076  6948  6948 D BluetoothAdapterApp: Loading JNI Library
,08-17 14:26:47.113  6948  6948 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@1a94487c Instance Count = 1
,08-17 14:26:47.122  1036  1909 W libprocessgroup: failed to open /acct/uid_10011/pid_5999/cgroup.procs: No such file or directory
08-17 14:26:47.124  4312  4312 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-17 14:26:47.127  6948  6948 D BluetoothAdapterApp: onCreate
,08-17 14:26:47.139  6858  6858 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-17 14:26:47.139  6858  6858 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-17 14:26:47.139  6858  6858 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-17 14:26:47.142  6837  6837 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-17 14:26:47.143  4312  6967 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-17 14:26:47.147  4312  6969 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-17 14:26:47.147  4312  6969 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-17 14:26:47.153  6837  6837 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 14:26:47.160  6925  6970 W FormManager: Network not available. Please check & try again.
,08-17 14:26:47.164  6925  6971 V FormManager: Network unavailable.
08-17 14:26:47.167  6948  6948 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-17 14:26:47.167  6948  6948 D ProfileConfigQcom: Adding HeadsetService
08-17 14:26:47.167  6948  6948 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-17 14:26:47.168  6948  6948 D ProfileConfigQcom: Adding A2dpService
08-17 14:26:47.168  6948  6948 D ProfileConfigQcom: [BTUI] HidService is supported
08-17 14:26:47.168  6948  6948 D ProfileConfigQcom: Adding HidService
08-17 14:26:47.168  6948  6948 D ProfileConfigQcom: [BTUI] HealthService is supported
08-17 14:26:47.168  6925  6971 V FormManager: Network unavailable.
08-17 14:26:47.169  6948  6948 D ProfileConfigQcom: Adding HealthService
08-17 14:26:47.169  6948  6948 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-17 14:26:47.170  6948  6948 D ProfileConfigQcom: [BTUI] PanService is supported
08-17 14:26:47.170  6948  6948 D ProfileConfigQcom: Adding PanService
,08-17 14:26:47.170  6948  6948 D ProfileConfigQcom: [BTUI] GattService is supported
,08-17 14:26:47.170  6948  6948 D ProfileConfigQcom: Adding GattService
08-17 14:26:47.170  6948  6948 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-17 14:26:47.171  6948  6948 D ProfileConfigQcom: Adding BluetoothMapService
08-17 14:26:47.171  6948  6948 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-17 14:26:47.173  6948  6948 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-17 14:26:47.174  1036  1036 D PowerManagerServiceEx: releaseWakeLockInternal: lock=822491364 [*alarm*], flags=0x0
08-17 14:26:47.174   331  6974 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-17 14:26:47.175  1036  1101 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-17 14:26:47.177  6837  6837 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-17 14:26:47.182  6887  6887 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-17 14:26:47.183  6948  6948 V LGMDMManagerInternal: Create singleton instance
08-17 14:26:47.184  6887  6887 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-17 14:26:47.184  6887  6887 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-17 14:26:47.226  6887  6887 D LgDataFeature: LgDataFeature() Constructor: none
08-17 14:26:47.227  6887  6887 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-17 14:26:47.232  6887  6887 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-17 14:26:47.234  6887  6887 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-17 14:26:47.234  6887  6887 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-17 14:26:47.234  6887  6887 V SoundPool: doLoad: loading sample sampleID=1
08-17 14:26:47.235  6887  6887 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-17 14:26:47.235  6887  6977 V SoundPool: Start decode
08-17 14:26:47.235  6887  6977 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-17 14:26:47.235   335  1371 V MediaPlayerService: decode(23, 10857164, 17813)
08-17 14:26:47.235   335  1371 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-17 14:26:47.235   335  1371 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-17 14:26:47.235   335  1371 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-17 14:26:47.235   335  1371 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-17 14:26:47.235   335  1371 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-17 14:26:47.235   335  1371 V MediaPlayerService: player type = 3
08-17 14:26:47.236   335  1371 V AwesomePlayer: AwesomePlayer create()
08-17 14:26:47.236   335  1371 V AwesomePlayer: reset_l() 
08-17 14:26:47.236   335  1371 V AwesomePlayer: cancelPlayerEvents
08-17 14:26:47.236   335  1371 V AwesomePlayer: setAudioSink() 
08-17 14:26:47.236   335  1371 V AwesomePlayer: reset_l() 
08-17 14:26:47.236   335  1371 V AudioCache: notify(0xb5474cc0, 8, 0, 0)
08-17 14:26:47.236   335  1371 V AudioCache: ignored
08-17 14:26:47.236   335  1371 V AwesomePlayer: cancelPlayerEvents
08-17 14:26:47.236   335  1371 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-17 14:26:47.236   335  1371 V AwesomePlayer: setDataSource_l dataSource
08-17 14:26:47.236   335  1371 V LGParserOSAL: SniffLGParser start
08-17 14:26:47.236   335  1371 V LGParserOSAL: MainType:5, SubType=0
08-17 14:26:47.236   335  1371 V LGParserOSAL: #### check Mime : application/ogg
08-17 14:26:47.236   335  1371 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-17 14:26:47.236   335  1371 E MediaExtractor: Use LGExtractor :application/ogg 
08-17 14:26:47.245  6663  6663 D UEI.SmartControl: QS Service created
08-17 14:26:47.246  6887  6887 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-17 14:26:47.249  6948  6948 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-17 14:26:47.252  6948  6948 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-17 14:26:47.252  6948  6948 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-17 14:26:47.252  6948  6948 V BluetoothSapReceiver: SapReceiver onReceive 
08-17 14:26:47.253  6948  6948 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:26:47.253  6948  6948 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-17 14:26:47.259  6904  6904 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-17 14:26:47.261  6887  6887 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-17 14:26:47.262  6887  6887 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,08-17 14:26:47.270  6887  6887 V LGMDMManager: Create singleton instance
08-17 14:26:47.271  6663  6663 I UEI.SmartControl: Service initServices...
08-17 14:26:47.272  6663  6663 D UEI.SmartControl: QS start get config
08-17 14:26:47.275   335  1371 V LGParserOSAL: supported mime: application/ogg
08-17 14:26:47.275   335  1371 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-17 14:26:47.275   335  1371 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-17 14:26:47.275   335  1371 V AwesomePlayer: mBitrate = -1 bits/sec
08-17 14:26:47.275   335  1371 V AwesomePlayer: AudioTrack Setting
08-17 14:26:47.275   335  1371 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-17 14:26:47.275   335  1371 V AwesomePlayer: setAudioSource() 
08-17 14:26:47.275   335  1371 V MediaPlayerService: prepare
08-17 14:26:47.275   335  1371 V AwesomePlayer: prepareAsync_l() 
08-17 14:26:47.275   335  1371 V MediaPlayerService: wait for prepare
08-17 14:26:47.275   335  6979 V AwesomePlayer: onPrepareAsyncEvent() 
08-17 14:26:47.275   335  6979 V AwesomePlayer: initAudioDecoder() 
08-17 14:26:47.275   335  6979 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-17 14:26:47.275   335  6979 V AudioSystem: isOffloadSupported()
08-17 14:26:47.275   335  6979 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-17 14:26:47.275   335  6979 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-17 14:26:47.275   335  6979 I AudioFlinger: isAudioPlaybackHookOn() false
08-17 14:26:47.275   335  6979 V AwesomePlayer: getUseOffload() = 0 
08-17 14:26:47.275   335  6979 V OMXCodec: OMXCodec::Create
08-17 14:26:47.275   335  6979 V OMXCodec: findMatchingCodecs()
08-17 14:26:47.275   335  6979 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-17 14:26:47.275   335  6979 V OMXCodec: matchingCodecs.size()=1
08-17 14:26:47.275   335  6979 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-17 14:26:47.277   335  6979 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-17 14:26:47.277   335  6979 V LGCodecAdapter: LG Codec Adapter start
08-17 14:26:47.277   335  6979 V OMXCodec: OMXCodec Createtor
08-17 14:26:47.277   335  6979 V OMXCodec: setComponentRole
08-17 14:26:47.277   335  6979 V OMXCodec: configureCodec protected=0
08-17 14:26:47.277   335  6979 V LGCodecAdapter: called getLGCodecSpecificData
08-17 14:26:47.277   335  6979 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-17 14:26:47.277   335  6979 V LGCodecOSAL: Called LGconfigureCodecMETA
08-17 14:26:47.277   335  6979 V LGCodecOSAL: Called LGconfigureCodecMSG
08-17 14:26:47.277   335  6979 V LGCodecOSAL: Not support LGCodec
08-17 14:26:47.278   335  6979 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-17 14:26:47.278   335  6979 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-17 14:26:47.278   335  6979 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-17 14:26:47.278   335  6979 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-17 14:26:47.278   335  6979 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-17 14:26:47.278   335  6979 V AudioSystem: isOffloadSupported()
08-17 14:26:47.278   335  6979 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-17 14:26:47.278   335  6979 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returni,ng false
08-17 14:26:47.278   335  6979 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-17 14:26:47.278   335  6979 V OMXCodec: init()
08-17 14:26:47.278   335  6979 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-17 14:26:47.278   335  6979 V OMXCodec: allocateBuffers
08-17 14:26:47.278   335  6979 V OMXCodec: allocateBuffersOnPort portIndex=0
08-17 14:26:47.278   335  6979 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-17 14:26:47.278   335  6979 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on input port
08-17 14:26:47.278   335  6979 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on input port
08-17 14:26:47.278   335  6979 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on input port
08-17 14:26:47.278   335  6979 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on input port
08-17 14:26:47.278   335  6979 V OMXCodec: allocateBuffersOnPort portIndex=1
08-17 14:26:47.278   335  6979 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-17 14:26:47.278   335  6979 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
08-17 14:26:47.278   335  6979 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d30 on output port
08-17 14:26:47.279   335  6979 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7dd0 on output port
08-17 14:26:47.279   335  6979 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7f10 on output port
08-17 14:26:47.279   335  6979 V OMXCodec: init() mAsyncCompletion wait!!! 
08-17 14:26:47.279   335  6981 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-17 14:26:47.279   335  6981 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-17 14:26:47.279   335  6981 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
,08-17 14:26:47.284   335  6979 V OMXCodec: init() mAsyncCompletion wait!!! 
08-17 14:26:47.284   335  6981 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-17 14:26:47.284   335  6981 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-17 14:26:47.284   335  6981 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-17 14:26:47.284   335  6979 V OMXCodec: init() mAsyncCompletion wait free! 
08-17 14:26:47.284   335  6979 V AwesomePlayer: finishAsyncPrepare_l() 
08-17 14:26:47.284   335  6979 V AudioCache: notify(0xb5474cc0, 5, 0, 0)
08-17 14:26:47.284   335  6979 V AudioCache: ignored
08-17 14:26:47.284   335  6979 V AudioCache: notify(0xb5474cc0, 1, 0, 0)
08-17 14:26:47.284   335  6979 V AudioCache: prepared
08-17 14:26:47.284   335  1371 V AudioCache: wait - success
08-17 14:26:47.284   335  1371 V MediaPlayerService: start
08-17 14:26:47.284   335  1371 V AwesomePlayer: play_l() 
08-17 14:26:47.284   335  1371 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-17 14:26:47.284   335  1371 V AwesomePlayer: createAudioPlayer_l
08-17 14:26:47.284   335  1371 V AwesomePlayer: seekAudioIfNecessary_l() 
08-17 14:26:47.284   335  1371 V AwesomePlayer: startAudioPlayer_l() 
08-17 14:26:47.284   335  1371 D AudioPlayer: start of Playback, useOffload 0
08-17 14:26:47.284   335  1371 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-17 14:26:47.285   335  1371 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-17 14:26:47.287   335  6981 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-17 14:26:47.287   335  6981 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-17 14:26:47.287   335  6981 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-17 14:26:47.287   335  6981 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-17 14:26:47.287   335  6981 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-17 14:26:47.287   335  6981 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-17 14:26:47.287   335  6981 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885008
08-17 14:26:47.287   335  6981 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-17 14:26:47.287   335  6981 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885488
08-17 14:26:47.287   335  6981 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-17 14:26:47.287   335  6981 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885648
08-17 14:26:47.287   335  6981 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-17 14:26:47.287   335  6981 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885968
08-17 14:26:47.287   335  6981 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-17 14:26:47.287   335  6981 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-17 14:26:47.287   335  6981 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-17 14:26:47.287   335  6981 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-17 14:26:47.287   335  6981 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-17 14:26:47.288   335  6981 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-17 14:26:47.288   335  6981 V OMXCodec: allocateBuffersOnPort portIndex=1
08-17 14:26:47.288   335  6981 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-17 14:26:47.288   335  6981 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7dd0 on output port
08-17 14:26:47.288   335  6981 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d30 on output port
08-17 14:26:47.288   335  6981 V OMXCodec: [OMX.google.vorbis.decoder] allocated b,uffer 0xb54f7b50 on output port
08-17 14:26:47.288   335  6981 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb000f1f0 on output port
08-17 14:26:47.288   335  6981 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-17 14:26:47.288   335  6981 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-17 14:26:47.288   335  1371 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-17 14:26:47.290   335  1371 V AudioCache: notify(0xb5474cc0, 6, 0, 0)
08-17 14:26:47.290   335  1371 V AudioCache: ignored
08-17 14:26:47.291   335  1371 V MediaPlayerService: wait for playback complete
,08-17 14:26:47.298   335  6982 V AudioCache: write(0xb171b000, 4096)
08-17 14:26:47.298   335  6982 V AudioCache: memcpy(0xb0407000, 0xb171b000, 4096)
08-17 14:26:47.300   335  6982 V AudioCache: write(0xb171b000, 4096)
08-17 14:26:47.300   335  6982 V AudioCache: memcpy(0xb0408000, 0xb171b000, 4096)
08-17 14:26:47.301   335  6982 V AudioCache: write(0xb171b000, 4096)
08-17 14:26:47.301   335  6982 V AudioCache: memcpy(0xb0409000, 0xb171b000, 4096)
08-17 14:26:47.302   335  6982 V AudioCache: write(0xb171b000, 4096)
08-17 14:26:47.302   335  6982 V AudioCache: memcpy(0xb040a000, 0xb171b000, 4096)
08-17 14:26:47.303   335  6982 V AudioCache: write(0xb171b000, 4096)
08-17 14:26:47.303   335  6982 V AudioCache: memcpy(0xb040b000, 0xb171b000, 4096)
,08-17 14:26:47.305   335  6982 V AudioCache: write(0xb171b000, 4096)
08-17 14:26:47.305   335  6982 V AudioCache: memcpy(0xb040c000, 0xb171b000, 4096)
08-17 14:26:47.305   335  6982 V AudioCache: write(0xb171b000, 4096)
08-17 14:26:47.305   335  6982 V AudioCache: memcpy(0xb040d000, 0xb171b000, 4096)
08-17 14:26:47.306   335  6982 V AudioCache: write(0xb171b000, 4096)
08-17 14:26:47.306   335  6982 V AudioCache: memcpy(0xb040e000, 0xb171b000, 4096)
08-17 14:26:47.307   335  6982 V AudioCache: write(0xb171b000, 4096)
08-17 14:26:47.307   335  6982 V AudioCache: memcpy(0xb040f000, 0xb171b000, 4096)
08-17 14:26:47.308   335  6982 V AudioCache: write(0xb171b000, 4096)
08-17 14:26:47.308   335  6982 V AudioCache: memcpy(0xb0410000, 0xb171b000, 4096)
08-17 14:26:47.308   335  6982 V AudioCache: write(0xb171b000, 4096)
08-17 14:26:47.308   335  6982 V AudioCache: memcpy(0xb0411000, 0xb171b000, 4096)
08-17 14:26:47.309   335  6982 V AudioCache: write(0xb171b000, 4096)
08-17 14:26:47.309   335  6982 V AudioCache: memcpy(0xb0412000, 0xb171b000, 4096)
08-17 14:26:47.310   335  6982 V AudioCache: write(0xb171b000, 4096)
,08-17 14:26:47.310   335  6982 V AudioCache: memcpy(0xb0413000, 0xb171b000, 4096)
08-17 14:26:47.310   335  6982 V AudioCache: write(0xb171b000, 4096)
08-17 14:26:47.310   335  6982 V AudioCache: memcpy(0xb0414000, 0xb171b000, 4096)
08-17 14:26:47.311   335  6982 V AudioCache: write(0xb171b000, 4096)
08-17 14:26:47.311   335  6982 V AudioCache: memcpy(0xb0415000, 0xb171b000, 4096)
08-17 14:26:47.311   335  6982 V AudioCache: write(0xb171b000, 4096)
08-17 14:26:47.312   335  6982 V AudioCache: memcpy(0xb0416000, 0xb171b000, 4096)
08-17 14:26:47.312   335  6982 V AudioCache: write(0xb171b000, 4096)
08-17 14:26:47.312   335  6982 V AudioCache: memcpy(0xb0417000, 0xb171b000, 4096)
08-17 14:26:47.313   335  6982 V AudioCache: write(0xb171b000, 4096)
08-17 14:26:47.313   335  6982 V AudioCache: memcpy(0xb0418000, 0xb171b000, 4096)
08-17 14:26:47.313   335  6982 V AudioCache: write(0xb171b000, 4096)
08-17 14:26:47.313   335  6982 V AudioCache: memcpy(0xb0419000, 0xb171b000, 4096)
08-17 14:26:47.314   335  6982 V AudioCache: write(0xb171b000, 4096)
08-17 14:26:47.314   335  6982 V AudioCache: memcpy(0xb041a000, 0xb171b000, 4096)
08-17 14:26:47.315  6887  6887 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,08-17 14:26:47.316  6887  6887 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-17 14:26:47.316   335  6982 V AudioCache: write(0xb171b000, 4096)
08-17 14:26:47.316   335  6982 V AudioCache: memcpy(0xb041b000, 0xb171b000, 4096)
08-17 14:26:47.317   335  6982 V AudioCache: write(0xb171b000, 4096)
08-17 14:26:47.317   335  6982 V AudioCache: memcpy(0xb041c000, 0xb171b000, 4096)
08-17 14:26:47.317   335  6982 V AudioCache: write(0xb171b000, 4096)
08-17 14:26:47.317   335  6982 V AudioCache: memcpy(0xb041d000, 0xb171b000, 4096)
08-17 14:26:47.317   335  6982 V AudioCache: write(0xb171b000, 4096)
08-17 14:26:47.317   335  6982 V AudioCache: memcpy(0xb041e000, 0xb171b000, 4096)
08-17 14:26:47.318   335  6982 V AudioCache: write(0xb171b000, 4096)
08-17 14:26:47.318   335  6982 V AudioCache: memcpy(0xb041f000, 0xb171b000, 4096)
08-17 14:26:47.318  6887  6887 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:6240
08-17 14:26:47.318   335  6982 V AudioCache: write(0xb171b000, 4096)
08-17 14:26:47.318   335  6982 V AudioCache: memcpy(0xb0420000, 0xb171b000, 4096)
08-17 14:26:47.319   335  6982 V AudioCache: write(0xb171b000, 4096)
08-17 14:26:47.319   335  6982 V AudioCache: memcpy(0xb0421000, 0xb171b000, 4096)
08-17 14:26:47.319   335  6982 V AudioCache: write(0xb171b000, 4096)
08-17 14:26:47.319   335  6982 V AudioCache: memcpy(0xb0422000, 0xb171b000, 4096)
08-17 14:26:47.320   335  6982 V AudioCache: write(0xb171b000, 4096)
08-17 14:26:47.320   335  6982 V AudioCache: memcpy(0xb0423000, 0xb171b000, 4096)
08-17 14:26:47.320   335  6982 V AudioCache: write(0xb171b000, 4096)
08-17 14:26:47.320   335  6982 V AudioCache: memcpy(0xb0424000, 0xb171b000, 4096)
08-17 14:26:47.320   335  6982 V AudioCache: write(0xb171b000, 4096)
08-17 14:26:47.320   335  6982 V AudioCache: memcpy(0xb0425000, 0xb171b000, 4096)
08-17 14:26:47.321   335  6982 V AudioCache: write(0xb171b000, 4096)
08-17 14:26:47.321   335  6982 V AudioCache: memcpy(0xb0426000, 0xb171b000, 4096)
08-17 14:26:47.321   335  6982 V AudioCache: write(0xb171b000, 4096)
08-17 14:26:47.321   335  6982 V AudioCache: memcpy(0xb0427000, 0xb171b000, 4096)
08-17 14:26:47.322   335  6982 V AudioCache: write(0xb171b000, 4096)
08-17 14:26:47.322   335  6982 V AudioCache: memcpy(0xb0428000, 0xb171b000, 4096)
08-17 14:26:47.322   335  6982 V AudioCache: write(0xb171b000, 4096)
08-17 14:26:47.322   335  6982 V AudioCache: memcpy(0xb0429000, 0xb171b000, 4096)
08-17 14:26:47.322   335  6982 V AudioCache: write(0xb171b000, 4096)
08-17 14:26:47.322   335  6982 V AudioCache: memcpy(0xb042a000, 0xb171b000, 4096)
08-17 14:26:47.323   335  6982 V AudioCache: write(0xb171b000, 4096)
08-17 14:26:47.323   335  6982 V AudioCache: memcpy(0xb042b000, 0xb171b000, 4096)
08-17 14:26:47.323   335  6982 V AudioCache: write(0xb171b000, 4096)
08-17 14:26:47.323   335  6982 V AudioCache: memcpy(0xb042c000, 0xb171b000, 4096)
08-17 14:26:47.323   335  6982 V AudioCache: write(0xb171b000, 4096)
08-17 14:26:47.323   335  6982 V AudioCache: memcpy(0xb042d000, 0xb171b000, 4096)
08-17 14:26:47.323   335  6982 V AudioCache: write(0xb171b000, 4096)
08-17 14:26:47.323   335  6982 V AudioCache: memcpy(0xb042e000, 0xb171b000, 4096)
08-17 14:26:47.324   335  6982 V AudioCache: write(0xb171b000, 4096)
08-17 14:26:47.324   335  6982 V AudioCache: memcpy(0xb042f000, 0xb171b000, 4096)
08-17 14:26:47.324   335  6982 V AudioCache: write(0xb171b000, 4096)
08-17 14:26:47.324   335  6982 V AudioCache: memcpy(0xb0430000, 0xb171b000, 4096)
08-17 14:26:47.324   335  6982 V AudioCache: write(0xb171b000, 4096)
08-17 14:26:47.324   335  6982 V AudioCache: memcpy(0xb0431000, 0xb171b000, 4096)
08-17 14:26:47.324   335  6982 V AudioCache: write(0xb171b000, 4096)
08-17 14:26:47.324   335  6982 V AudioCache: memcpy(0xb0432000, 0xb171b000, 4096)
08-17 14:26:47.325   335  6982 V AudioCache: write(0xb171b000, 4096)
08-17 14:26:47.325   335  6982 V AudioCache: memcpy(0xb0433000, 0xb171b0,00, 4096)
08-17 14:26:47.325   335  6982 V AudioCache: write(0xb171b000, 4096)
08-17 14:26:47.325   335  6982 V AudioCache: memcpy(0xb0434000, 0xb171b000, 4096)
08-17 14:26:47.325   335  6982 V AudioCache: write(0xb171b000, 4096)
08-17 14:26:47.325   335  6982 V AudioCache: memcpy(0xb0435000, 0xb171b000, 4096)
08-17 14:26:47.325   335  6982 V AudioCache: write(0xb171b000, 4096)
08-17 14:26:47.325   335  6982 V AudioCache: memcpy(0xb0436000, 0xb171b000, 4096)
08-17 14:26:47.326   335  6981 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-17 14:26:47.326   335  6982 V AudioCache: write(0xb171b000, 4096)
08-17 14:26:47.326   335  6982 V AudioCache: memcpy(0xb0437000, 0xb171b000, 4096)
08-17 14:26:47.326   335  6982 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-17 14:26:47.326   335  6982 V AudioCache: write(0xb171b000, 4096)
08-17 14:26:47.326   335  6982 V AudioCache: memcpy(0xb0438000, 0xb171b000, 4096)
08-17 14:26:47.326   335  6982 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-17 14:26:47.326   335  6982 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-17 14:26:47.326   335  6982 V AwesomePlayer: postAudioEOS() 
08-17 14:26:47.326   335  6982 V AudioCache: write(0xb171b000, 280)
08-17 14:26:47.326   335  6982 V AudioCache: memcpy(0xb0439000, 0xb171b000, 280)
08-17 14:26:47.328   335  6979 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-17 14:26:47.328   335  6979 V AwesomePlayer: onStreamDone
08-17 14:26:47.328   335  6979 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-17 14:26:47.328   335  6979 V AudioCache: notify(0xb5474cc0, 2, 0, 0)
08-17 14:26:47.328   335  6979 V AudioCache: playback complete
08-17 14:26:47.328   335  6979 V AwesomePlayer: pause_l() 
08-17 14:26:47.328   335  6979 V AudioCache: notify(0xb5474cc0, 7, 0, 0)
08-17 14:26:47.328   335  6979 V AudioCache: ignored
08-17 14:26:47.328   335  6979 V AwesomePlayer: cancelPlayerEvents
08-17 14:26:47.328   335  6979 D AudioPlayer: Pause Playback at 1068125
08-17 14:26:47.328   335  1371 V AudioCache: wait - success
08-17 14:26:47.328   335  1371 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
,08-17 14:26:47.332   335  1371 V AwesomePlayer: reset_l() 
08-17 14:26:47.332   335  1371 V AudioCache: notify(0xb5474cc0, 8, 0, 0)
08-17 14:26:47.332   335  1371 V AudioCache: ignored
08-17 14:26:47.332   335  1371 V AwesomePlayer: cancelPlayerEvents
,08-17 14:26:47.332   335  1371 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
,08-17 14:26:47.332   335  1371 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-17 14:26:47.332   335  1371 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-17 14:26:47.332   335  1371 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-17 14:26:47.332   335  1371 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
,08-17 14:26:47.333   335  6981 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-17 14:26:47.333   335  6981 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
,08-17 14:26:47.333   335  6981 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-17 14:26:47.333   335  6981 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 0
08-17 14:26:47.333   335  6981 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-17 14:26:47.333   335  6981 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 0
08-17 14:26:47.333   335  6981 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-17 14:26:47.333   335  6981 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 0
08-17 14:26:47.333   335  6981 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-17 14:26:47.333   335  6981 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f79c0 on port 0
08-17 14:26:47.333   335  6981 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-17 14:26:47.333   335  6981 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-17 14:26:47.333   335  6981 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb000f1f0 on port 1
08-17 14:26:47.333   335  6981 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-17 14:26:47.333   335  6981 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 1
08-17 14:26:47.333   335  6981 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-17 14:26:47.333   335  6981 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7d30 on port 1
08-17 14:26:47.333   335  6981 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-17 14:26:47.333   335  6981 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7dd0 on port 1
08-17 14:26:47.333   335  6981 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-17 14:26:47.333   335  6981 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-17 14:26:47.333   335  1371 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-17 14:26:47.333   335  1371 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-17 14:26:47.333   335  6981 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-17 14:26:47.333   335  6981 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-17 14:26:47.333   335  6981 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-17 14:26:47.333   335  1371 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-17 14:26:47.333   335  1371 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-17 14:26:47.333   335  1371 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-17 14:26:47.334   335  1371 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-17 14:26:47.334   335  1371 D AudioPlayer: AudioPlayer releasing audio source
08-17 14:26:47.334   335  1371 D AudioPlayer: AudioPlayer done releasing audio source
08-17 14:26:47.334   335  1371 V AwesomePlayer: reset_l() 
08-17 14:26:47.334   335  1371 V AwesomePlayer: cancelPlayerEvents
08-17 14:26:47.334   335  1371 V AwesomePlayer: ~AwesomePlayer call
08-17 14:26:47.334   335  1371 V AwesomePlayer: reset_l() 
08-17 14:26:47.334   335  1371 V AwesomePlayer: cancelPlayerEvents
08-17 14:26:47.334  6887  6977 V SoundPool: close(31)
08-17 14:26:47.334  6887  6977 V SoundPool: pointer = 0x9fe60000, size = 205080, sampleRate = 48000, numChannels = 2
08-17 14:26:47.540  6663  6663 I UEI.SmartControl: Supports setup maps: true
08-17 14:26:47.542  6663  6663 D UEI.SmartControl: QS start statue = true Error code = 0
08-17 14:26:47.542  6663  6663 I UEI.SmartControl: QS version = v2.7.10.1_RC1
,08-17 14:26:47.542  6663  6663 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-17 14:26:47.542  6663  6663 I UEI.SmartControl: ### init IR Blaster...
08-17 14:26:47.546  6663  6663 D serial_port: Configuring serial port
08-17 14:26:47.546  6663  6663 E UEI.SmartControl: UEIBLaster setting for 616
08-17 14:26:47.546  6663  6663 I UEI.SmartControl: Setting serial record hearder size = 2
08-17 14:26:47.546  6663  6663 I UEI.SmartControl: configuring settings for MAXQ616
08-17 14:26:47.546  6663  6663 I UEI.SmartControl: Get version...
,08-17 14:26:47.565  6663  6983 D UEI.SmartControl: serial port data available: 21,
,08-17 14:26:47.592  6663  6663 D UEI.SmartControl: MAXQ616 A2-X4 software.,
08-17 14:26:47.592  6663  6663 I UEI.SmartControl: IR Blaster version: 256702256704300002
,08-17 14:26:47.592  6663  6663 I UEI.SmartControl: QS saving settings...,
,08-17 14:26:47.594  6663  6663 D UEI.SmartControl: IR Blaster version: 25672567
,08-17 14:26:47.611  6663  6983 D UEI.SmartControl: serial port data available: 4
,08-17 14:26:47.646  6663  6992 I UEI.SmartControl: Device manager: loading config....
,08-17 14:26:47.647  6663  6992 D UEI.SmartControl: ----------- loading internal config...
,08-17 14:26:47.649  6663  6663 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-17 14:26:47.661  6663  6663 E UEI.SmartControl: Services init done
08-17 14:26:47.661  6663  6663 D UEI.SmartControl: QS Service init finished
08-17 14:26:47.664  6663  6663 D UEI.SmartControl: QS Service version name: 2.1.91
08-17 14:26:47.664  6663  6663 D UEI.SmartControl: QS Service version code: 201091
08-17 14:26:47.665  6663  6663 D UEI.SmartControl: Service requested: Control
08-17 14:26:47.667  6663  6992 E UEI.SmartControl: Loading SETTINGS...
08-17 14:26:47.671  6887  6887 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
,08-17 14:26:47.674  6663  6663 D UEI.SmartControl: Internal service binding...
08-17 14:26:47.674  6663  6678 I UEI.SmartControl: ------ IControl API: 11
08-17 14:26:47.674  6663  6678 D UEI.SmartControl: File observer start...
08-17 14:26:47.675  6663  6678 E UEI.SmartControl: IR Port is disabled: false
08-17 14:26:47.675  6663  6678 D UEI.SmartControl: Starting file observer...
08-17 14:26:47.677  6663  6678 I UEI.SmartControl: Registering callback...
08-17 14:26:47.678  6663  6679 I UEI.SmartControl: ------ IControl API: 19
08-17 14:26:47.679  6663  6679 I UEI.SmartControl: Registering Services Ready callback...
08-17 14:26:47.682  6663  6992 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-17 14:26:47.700  6663  6991 I UEI.SmartControl: Notify AllClients services are ready: 0
,08-17 14:26:47.701  6887  6903 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-17 14:26:47.701  6887  6975 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-17 14:26:47.702  6887  6975 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-17 14:26:47.702  6887  6887 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-17 14:26:47.702  6887  6887 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-17 14:26:47.703  6663  6678 I UEI.SmartControl: ------ IControl API: 8
08-17 14:26:47.704  6663  6991 D UEI.SmartControl: -----service ready thread exits
08-17 14:26:47.705  6887  6887 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-17 14:26:47.705  6887  6887 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-17 14:26:47.705  6887  6887 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-17 14:26:47.706  6887  6887 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-17 14:26:47.707  6887  6887 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-17 14:26:47.707  6887  6887 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-17 14:26:47.708  6887  6887 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-17 14:26:47.712  6887  6887 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-17 14:26:47.714  6887  6887 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,08-17 14:26:47.716  6887  6887 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-17 14:26:47.717  6887  6887 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-17 14:26:47.718  6887  6887 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-17 14:26:47.719  6887  6887 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-17 14:26:47.719  6887  6887 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-17 14:26:47.720  6887  6887 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1471436807720]
08-17 14:26:47.723  6887  6887 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-17 14:26:47.725  1036  1638 I ActivityManager: Killing 6549:com.lge.email/u0a23 (adj 15): empty #17
08-17 14:26:47.749  6887  6994 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-17 14:26:47.795  1036  1638 I ActivityManager: Killing 6020:com.android.contacts/u0a19 (adj 15): empty #18
,08-17 14:26:47.828  1036  1964 W libprocessgroup: failed to open /acct/uid_10023/pid_6549/cgroup.procs: No such file or directory
,08-17 14:26:47.834  1036  1052 W libprocessgroup: failed to open /acct/uid_10019/pid_6020/cgroup.procs: No such file or directory
08-17 14:26:47.844  6887  6887 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,08-17 14:26:47.846  6887  6887 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-17 14:26:47.847  6887  6887 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-17 14:26:47.848  6887  6887 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-17 14:26:47.849  6887  6887 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-17 14:26:47.849  6887  6887 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-17 14:26:47.850  6887  6887 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-17 14:26:47.870  6887  6887 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-17 14:26:48.518  1036  1980 D WifiServiceImplEx: setWifiEnabled: true pid=6725, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-17 14:26:48.524  1036  1980 D WifiService: setWifiEnabled: true pid=6725, uid=10118
08-17 14:26:48.524  1036  1980 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-17 14:26:48.543  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-17 14:26:48.543  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-17 14:26:48.543  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-17 14:26:48.545  1036  1523 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-17 14:26:48.545  1036  1523 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-17 14:26:48.547  1036  1523 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-17 14:26:48.547  1036  1523 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-17 14:26:48.548  1036  1523 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-17 14:26:48.548  1036  1523 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-17 14:26:48.548  1036  1523 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-17 14:26:48.548  1036  1523 E WifiHW  : unknown target_country: EU , set to default
08-17 14:26:48.548  1036  1523 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-17 14:26:48.548  1036  1523 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-17 14:26:48.548  1036  1523 I WifiUtil: gEnableBmps=1
08-17 14:26:48.642  1036  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-17 14:26:48.660  1036  1103 D Tethering: MasterInitialState.processMessage what=3
08-17 14:26:48.675  6725  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:26:48.679  6725  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:26:48.682  1036  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-17 14:26:48.684  1036  1103 D Tethering: MasterInitialState.processMessage what=3
08-17 14:26:48.697  6725  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:26:48.701  6725  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:26:48.702  1036  1365 V AlarmManager: ELAPSED_WAKEUP set : Alarm{1fbd8e8b type 2 when 330439 com.google.android.gms} when 330439
08-17 14:26:48.703  1036  1098 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-17 14:26:48.705  6461  6461 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-17 14:26:48.709  6461  6856 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-17 14:26:48.716  5768  5768 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-17 14:26:48.725  5768  5768 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-17 14:26:48.749  2162  2162 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-17 14:26:48.779  1036  1098 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-17 14:26:48.826  1036  1980 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7008 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-17 14:26:48.833  1036  1098 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 14:26:48.833  1036  1098 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-17 14:26:48.887  7008  7008 I AppUp4:AppBoxCP: onCreate
,08-17 14:26:48.888  7008  7008 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,08-17 14:26:48.898  7008  7008 I AppUp4:DB:  setFingerPrint start
,08-17 14:26:48.898  7008  7008 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-17 14:26:48.907  7008  7008 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-17 14:26:48.907  7008  7008 I AppUp4:DB:  SDK version = 21
08-17 14:26:48.907  7008  7008 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-17 14:26:48.909  7008  7008 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
,08-17 14:26:48.911  7008  7008 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-17 14:26:48.911  7008  7008 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-17 14:26:48.913  7008  7008 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-17 14:26:48.914  7008  7008 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-17 14:26:48.920  7008  7008 I AppUp4:CustModeStarterReceiver: onReceive
08-17 14:26:48.972  7008  7008 D LgDataFeature: LgDataFeature() Constructor: none
08-17 14:26:48.973  7008  7008 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-17 14:26:48.981  7008  7008 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@3f8bc126
08-17 14:26:48.981  7008  7008 D AppUp4:CustFacade: isCustomizationCompleted : false
08-17 14:26:48.981  7008  7008 D AppUp4:CustFacade: isPhone : true
08-17 14:26:48.982  7008  7008 D AppUp4:CustModeStarterReceiver: begin check event
08-17 14:26:48.983  7008  7008 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-17 14:26:48.983  7008  7008 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-17 14:26:48.984  7008  7035 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
,08-17 14:26:48.984  7008  7035 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
,08-17 14:26:48.985  7008  7035 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-17 14:26:48.993  1036  1875 I ActivityManager: Killing 6048:com.android.gallery3d/u0a27 (adj 15): empty #17
08-17 14:26:49.123  4312  4312 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-17 14:26:49.124  4312  4312 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-17 14:26:49.124  1036  1052 W libprocessgroup: failed to open /acct/uid_10027/pid_6048/cgroup.procs: No such file or directory
,08-17 14:26:49.130  4312  4312 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-17 14:26:49.141  4312  4312 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-17 14:26:49.155  4312  7045 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-17 14:26:49.160  4312  7046 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-17 14:26:49.161  4312  7046 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-17 14:26:49.227   331   894 D SoftapController: Softap fwReload - Ok
,08-17 14:26:49.232  1036  1523 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (669ms)
08-17 14:26:49.239  1036  1051 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7048 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
08-17 14:26:49.239   331   894 D CommandListener: Setting iface cfg
08-17 14:26:49.239   331   894 D CommandListener: Trying to bring down wlan0
08-17 14:26:49.240   331   894 D CommandListener: Clearing all IP addresses on wlan0
08-17 14:26:49.245  1036  1103 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-17 14:26:49.245  1036  1103 D Tethering: InitialState.processMessage what=4
,08-17 14:26:49.247  1036  1103 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-17 14:26:49.247  1036  1523 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-17 14:26:49.249  1036  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-17 14:26:49.249  1036  1523 E WifiStateMachine: useWiFiOffloading() : false
08-17 14:26:49.249  1036  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-17 14:26:49.254  1036  1523 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-17 14:26:49.254  1036  1523 D WifiMonitor: connecting to supplicant
08-17 14:26:49.255  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 14:26:49.258  1929  1929 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
,08-17 14:26:49.259  6725  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:26:49.237  7057  7057 W wpa_supplicant: type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 14:26:49.260  6725  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:26:49.237  7057  7057 W wpa_supplicant: type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 14:26:49.260  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-17 14:26:49.282  7057  7057 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-17 14:26:49.317  7057  7057 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-17 14:26:49.318  7057  7057 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-17 14:26:49.327  7048  7048 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-17 14:26:49.327  7048  7048 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-17 14:26:49.328  7048  7048 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-17 14:26:49.328  7048  7048 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-17 14:26:49.376  7048  7048 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-17 14:26:49.385  7048  7048 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
08-17 14:26:49.415  7057  7057 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-17 14:26:49.430  7048  7048 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-17 14:26:49.469  7048  7048 D LgDataFeature: LgDataFeature() Constructor: none
08-17 14:26:49.469  7048  7048 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-17 14:26:49.508  7057  7057 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-17 14:26:49.514  7057  7057 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-17 14:26:49.514  7057  7057 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-17 14:26:49.515  1036  1523 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-17 14:26:49.516  1036  1523 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-17 14:26:49.516  1036  1523 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-17 14:26:49.516  1036  1523 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-17 14:26:49.517  1036  1523 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-17 14:26:49.517  1036  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-17 14:26:49.518  1036  1523 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-17 14:26:49.518  1036  7074 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-17 14:26:49.518  1036  1523 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-17 14:26:49.518  1036  7074 D WifiMonitor: Dropping event because (p2p0) is stopped
08-17 14:26:49.518  1036  7074 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-17 14:26:49.518  1036  7074 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-17 14:26:49.518  1036  7074 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-17 14:26:49.518  1036  7074 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-17 14:26:49.519  1036  1523 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-17 14:26:49.519  1036  1523 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-17 14:26:49.519  1036  1523 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-17 14:26:49.519  1036  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-17 14:26:49.519  1036  1523 E WifiStateMachine: useWiFiOffloading() : false
08-17 14:26:49.519  1036  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-17 14:26:49.520  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:26:49.520  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:26:49.520  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:26:49.520  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:26:49.520  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-17 14:26:49.523  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-17 14:26:49.523  1929  1929 D WfdService: Waiting for WifiP2p enabling
08-17 14:26:49.527  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-17 14:26:49.527  6725  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:26:49.527  6725  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 14:26:49.527  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:26:49.527  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 14:26:49.527  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:26:49.527  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 14:26:49.527  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 14:26:49.527  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 14:26:49.527  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 14:26:49.527  6725  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:26:49.527  6725  6725 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-17 14:26:49.527  1036  1528 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-17 14:26:49.528  6725  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:26:49.528  6725  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 14:26:49.528  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:26:49.528  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 14:26:49.528  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
,08-17 14:26:49.528  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 14:26:49.528  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 14:26:49.528  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 14:26:49.528  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 14:26:49.528  6725  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:26:49.528  6725  6725 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-17 14:26:49.534  1036  1523 D WifiNative-wlan0: doBoolean: SET update_config 1
08-17 14:26:49.534  1036  1523 D WifiNative-wlan0: SET update_config 1: returned true
08-17 14:26:49.534  1036  1523 D WifiConfigStore: Loading config and enabling all networks 
08-17 14:26:49.535  1036  1523 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-17 14:26:49.535  1036  1523 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
,08-17 14:26:49.542  1036  1523 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-17 14:26:49.552  1036  1523 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
,08-17 14:26:49.552  1036  1523 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-17 14:26:49.553  1036  1523 D WifiStateMachine: enableVerboseLogging : level 2
08-17 14:26:49.553  1036  1523 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-17 14:26:49.553  1036  1523 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-17 14:26:49.553  1036  1523 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-17 14:26:49.554  1036  1523 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-17 14:26:49.554  1036  1523 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-17 14:26:49.554  1036  1523 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-17 14:26:49.554  1036  1523 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-17 14:26:49.555  1036  1523 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-17 14:26:49.555  1036  1523 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-17 14:26:49.555  1036  1523 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-17 14:26:49.555  1036  1523 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-17 14:26:49.556  1036  1523 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-17 14:26:49.556  1036  1523 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-17 14:26:49.556  1036  1523 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-17 14:26:49.557  1929  1929 D WfdsService: Supplicant Connection state is changed : true
08-17 14:26:49.557  1929  2234 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-17 14:26:49.557  1929  2234 D WfdsService: Set the WFDS Monitor: true
08-17 14:26:49.557  1929  2234 D WfdsMonitor: WfdsMonitorThread create
08-17 14:26:49.558  1929  2234 D WfdsMonitor: WFDS Monitor is created and started
08-17 14:26:49.558  1929  2234 D WfdsService: WiFi: Supplicant connection re-established
08-17 14:26:49.558  1036  1523 D WifiStateMachine: Setting OUI to DA-A1-19
08-17 14:26:49.558  1036  1523 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-17 14:26:49.558  1036  1523 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-17 14:26:49.558  1036  1523 D WifiNative-HAL: Setting external_sim to 1
08-17 14:26:49.558  1036  1523 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-17 14:26:49.558  1036  1523 D WifiNative-wlan0: SET external_sim 1: returned true
08-17 14:26:49.558  1036  1523 I WifiNative-HAL: startHal
08-17 14:26:49.558  1036  1523 D wifi    : setting scan oui 0x95331c40
08-17 14:26:49.559  1036  1523 D WifiStateMachine: Setting OUI to DA-A1-19
08-17 14:26:49.559  1036  1523 I WifiNative-HAL: startHal
08-17 14:26:49.559  1036  1523 D wifi    : setting scan oui 0x95331c40
08-17 14:26:49.559  1036  1523 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-17 14:26:49.560  1036  1523 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-17 14:26:49.560  1036  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-17 14:26:49.560  1929  7077 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-17 14:26:49.560  7057  7057 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
,08-17 14:26:49.560  1036  1523 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
,08-17 14:26:49.560  1036  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
,08-17 14:26:49.560  7057  7057 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-17 14:26:49.561  1036  1523 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-17 14:26:49.561  1036  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
,08-17 14:26:49.561  1929  7077 E CtrlSupplicant: Succeed to open control connection
08-17 14:26:49.561  7057  7057 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-17 14:26:49.561  1036  1523 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
,08-17 14:26:49.561  1036  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-17 14:26:49.561  7057  7057 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-17 14:26:49.561  1929  7077 E CtrlSupplicant: Succeed to open monitor connection
,08-17 14:26:49.562  1036  1523 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-17 14:26:49.562  1036  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-17 14:26:49.562  7057  7057 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
,08-17 14:26:49.562  1036  1523 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
,08-17 14:26:49.562  1036  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-17 14:26:49.563  7057  7057 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-17 14:26:49.563  1929  7077 D WfdsMonitor: Supplicant connection established
,08-17 14:26:49.563  1929  2234 D WfdsService: Connected to the supplicant for wfds
08-17 14:26:49.564  1036  1523 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-17 14:26:49.564  1036  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
,08-17 14:26:49.564  7057  7057 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-17 14:26:49.565  1036  1523 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-17 14:26:49.568  1036  1523 E WifiNative: : [331,316,087 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-17 14:26:49.568  1036  1523 D WifiNative-wlan0: doBoolean: RECONNECT
,08-17 14:26:49.569  1036  1523 D WifiNative-wlan0: RECONNECT: returned true
08-17 14:26:49.569  1036  1523 D WifiNative-wlan0: doString: [STATUS]
08-17 14:26:49.570  1036  7074 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-17 14:26:49.570  1036  7074 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-17 14:26:49.571  1036  1523 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-17 14:26:49.571  1036  1523 D WifiNative-wlan0: doBoolean: SET ps 1
08-17 14:26:49.572  1036  1523 D WifiNative-wlan0: SET ps 1: returned true
,08-17 14:26:49.572  1036  1522 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:26:49.575  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 3
08-17 14:26:49.575  1036  1036 D RttService: SCAN_AVAILABLE : 3
08-17 14:26:49.575  1036  1541 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:26:49.575  1036  1541 I WifiNative-HAL: startHal
,08-17 14:26:49.576  1036  1541 D wifi    : getting scan capabilities on interface[1] = 0x95331c40
,08-17 14:26:49.576  1036  1541 D wifi    : failed to get capabilities : -3
08-17 14:26:49.575  1036  1542 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:26:49.576  1036  1541 E WifiScanningService: could not get scan capabilities
08-17 14:26:49.576  1036  1523 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-17 14:26:49.576   331   894 D CommandListener: Setting iface cfg
08-17 14:26:49.577   331   894 D CommandListener: Trying to bring up p2p0
08-17 14:26:49.577  1036  1523 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
,08-17 14:26:49.577  1036  1523 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-17 14:26:49.577  1036  1523 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-17 14:26:49.577  1036  1522 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-17 14:26:49.577  1036  1522 D LGWifiP2pService: P2pEnablingState
08-17 14:26:49.577  1036  1523 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-17 14:26:49.578  1036  1522 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:26:49.578  1036  1522 D LGWifiP2pService: P2p socket connection successful
,08-17 14:26:49.578  1036  1522 D LGWifiP2pService: P2pEnabledState
08-17 14:26:49.578  1036  1523 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-17 14:26:49.578  1036  1523 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-17 14:26:49.578  1036  1523 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-17 14:26:49.578  7057  7057 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-17 14:26:49.579  1036  1523 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-17 14:26:49.579  1036  1523 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-17 14:26:49.580  1036  1523 E WifiStateMachine:  DriverStartedState what:132096 -100 0
,08-17 14:26:49.580  1036  1523 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-17 14:26:49.580  7057  7057 E wpa_supplicant: disconnect_rssi_lvl: -100
08-17 14:26:49.580  1036  1523 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-17 14:26:49.580  1929  1929 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-17 14:26:49.581  1036  1523 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-17 14:26:49.581  1036  1523 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-17 14:26:49.581  1036  1523 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-17 14:26:49.582  7057  7057 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-17 14:26:49.583  7057  7057 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,08-17 14:26:49.583  1929  1929 D WfdsService: WifiP2pState is changed : true
08-17 14:26:49.583  1929  2234 D WfdsService: Receive the WFDS_ENABLE Method
08-17 14:26:49.583  1929  2234 D WfdsService: Set the WFDS Monitor: true
08-17 14:26:49.583  1929  2234 D WfdsService: Connected to the supplicant for wfds
08-17 14:26:49.583  1929  2234 D WfdsJNI : doCommand: WFDS_SET TRUE
08-17 14:26:49.584  7057  7057 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-17 14:26:49.584  7057  7057 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
,08-17 14:26:49.584  7057  7057 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 14:26:49.584  1929  2234 D WfdsService: selectPreferredScanChannel [36]
08-17 14:26:49.584  1929  2234 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-17 14:26:49.584  7057  7057 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 14:26:49.586  1036  1522 D LGWifiP2pService: sending p2p connection changed broadcast
08-17 14:26:49.586  1036  7074 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-17 14:26:49.586  1036  7074 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,08-17 14:26:49.586  1036  7074 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-17 14:26:49.586  1036  7074 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-17 14:26:49.587  1036  7074 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-17 14:26:49.587  1036  7074 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 14:26:49.587  1036  7074 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 14:26:49.587  1036  7074 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 14:26:49.587  1036  7074 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-17 14:26:49.587  1036  7074 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,08-17 14:26:49.587  1036  7074 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 14:26:49.587  1036  7074 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 14:26:49.587  1929  7077 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-17 14:26:49.587  1929  7077 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-17 14:26:49.587  1036  1523 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-17 14:26:49.587  1036  1523 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-17 14:26:49.588  1036  1523 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
,08-17 14:26:49.588  1036  1523 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-17 14:26:49.588  1036  1523 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-17 14:26:49.588  7057  7057 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-17 14:26:49.588  7057  7057 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-17 14:26:49.589  1036  1522 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-17 14:26:49.589  1036  7074 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-17 14:26:49.589  1036  7074 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
,08-17 14:26:49.589  1929  1929 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-17 14:26:49.589  1036  7074 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-17 14:26:49.589  1036  7074 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-17 14:26:49.589  1036  1523 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-17 14:26:49.589  1036  1523 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
,08-17 14:26:49.590  1929  1929 D WfdsService: isConnected: false
08-17 14:26:49.590  1036  1523 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-17 14:26:49.590  1036  1523 D WifiNative-wlan0: doBoolean: SCAN
08-17 14:26:49.590  1036  1523 D WifiNative-wlan0: SCAN: returned false
08-17 14:26:49.591  1036  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=331341  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-17 14:26:49.591  1036  1522 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-17 14:26:49.592  1036  1522 D WifiNative-p2p0: doBoolean: SET device_name G3
08-17 14:26:49.592  1036  1522 D WifiNative-p2p0: SET device_name G3: returned true
08-17 14:26:49.592  1036  1522 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-17 14:26:49.592  1036  1522 D LGWifiP2pService: before postfix = G3
08-17 14:26:49.592  1036  1522 D WifiServerServiceExt: postfix byte check : 2
08-17 14:26:49.592  1036  1522 D LGWifiP2pService: after postfix = G3
08-17 14:26:49.592  1036  1522 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-17 14:26:49.592  1036  1522 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-17 14:26:49.592  1036  1522 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-17 14:26:49.593  1036  1522 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-17 14:26:49.593  1036  1522 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-17 14:26:49.593  1036  1522 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-17 14:26:49.593  1036  1522 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-17 14:26:49.593  1036  1522 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-17 14:26:49.593  1036  1522 D WifiNative-HAL: p2pGetDeviceAddress
08-17 14:26:49.594  1036  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=331345  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-17 14:26:49.594  1036  1523 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-17 14:26:49.595  1036  1523 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-17 14:26:49.595  1036  1523 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-17 14:26:49.595  1036  1523 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-17 14:26:49.596  1036  1522 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-17 14:26:49.596  1036  1523 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-17 14:26:49.598  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 14:26:49.598  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-17 14:26:49.599  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 14:26:49.600  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:26:49.600  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:26:49.600  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-17 14:26:49.601  1036  1522 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-17 14:26:49.601  1036  1522 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-17 14:26:49.601  1036  1522 D WifiNative-p2p0: P2P_FLUSH: returned true
,08-17 14:26:49.601  1929  1929 I WfdStateTracker: handleP2pThisDeviceChanged
08-17 14:26:49.602  1929  1929 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-17 14:26:49.602  1036  1522 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-17 14:26:49.602  1929  1929 D WfdsService: Update P2p Interface State: 3
08-17 14:26:49.602  1036  1522 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-17 14:26:49.602  1036  1522 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-17 14:26:49.602  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-17 14:26:49.602  1036  1036 D WifiServerServiceExt: setSupplicantStateSCANNING
08-17 14:26:49.602  1036  1522 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-17 14:26:49.602  1036  1522 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
,08-17 14:26:49.612  1036  1522 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-17 14:26:49.612  1036  1522 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-17 14:26:49.612  1036  1522 D LGWifiP2pService: InactiveState
08-17 14:26:49.613  1036  1522 D LGWifiP2pService: InactiveState{ when=-25ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:26:49.613  1036  1522 D LGWifiP2pService: P2pEnabledState{ when=-25ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:26:49.613  1036  1522 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
,08-17 14:26:49.613  7057  7057 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-17 14:26:49.614  7057  7057 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-17 14:26:49.614  1036  7074 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-17 14:26:49.614  1036  7074 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-17 14:26:49.614  1036  7074 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-17 14:26:49.614  1036  7074 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-17 14:26:49.614  1929  7077 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-17 14:26:49.614  7057  7057 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-17 14:26:49.614  7057  7057 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 14:26:49.615  1036  1522 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-17 14:26:49.615  1036  1522 D LGWifiP2pService: InactiveState{ when=-13ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:26:49.615  1036  1522 D LGWifiP2pService: P2pEnabledState{ when=-13ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:26:49.615  1929  7077 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-17 14:26:49.615  7057  7057 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 14:26:49.615  1036  7074 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-17 14:26:49.615  1036  7074 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 14:26:49.615  1036  7074 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 14:26:49.615  1036  7074 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 14:26:49.615  1036  7074 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-17 14:26:49.615  1036  7074 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 14:26:49.615  1036  7074 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 14:26:49.615  1036  7074 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 14:26:49.615  1929  7077 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-17 14:26:49.615  1036  1522 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:26:49.616  1036  1522 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:26:49.616  1036  1522 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:26:49.616  1036  1522 D LGWifiP2pService: InactiveState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:26:49.616  1036  1522 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:26:49.616  1036  1522 D LGWifiP2pService: DefaultState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:26:49.616  1036  1522 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:26:49.616  1036  1522 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:26:49.616  1036  1522 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:26:49.617,  1929  2234 W WfdsService: DefaultState - msg [9441285] is not handled
08-17 14:26:49.617  1036  1522 D LGWifiP2pService: InactiveState{ when=-2ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:26:49.617  1036  1522 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:26:49.617  1036  1522 D LGWifiP2pService: DefaultState{ when=-2ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:26:49.617  1036  1036 E WifiServerServiceExt: No p2p device connected
08-17 14:26:49.631  7048  7048 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-17 14:26:49.656  3400  3400 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-17 14:26:49.656  3400  3400 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-17 14:26:49.656  3400  3400 I LgeMiscReceiver: networkInfo.isConnected() = false
08-17 14:26:49.657  7048  7048 I HubEmail: JNI_OnLoad()
08-17 14:26:49.657  7048  7048 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-17 14:26:49.657  7048  7048 I HubEmail: registerNatives()
08-17 14:26:49.657  7048  7048 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-17 14:26:49.657  7048  7048 I HubEmail: registerNativeMethods()
08-17 14:26:49.657  7048  7048 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-17 14:26:49.657  7048  7048 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,08-17 14:26:49.718  1036  1051 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7083 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-17 14:26:49.725  7048  7082 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:26:49.727  6925  7079 W FormManager: Network not available. Please check & try again.
08-17 14:26:49.734  6925  7081 V FormManager: Network unavailable.
08-17 14:26:49.739  6925  7081 V FormManager: Network unavailable.
,08-17 14:26:49.748  1036  1964 I ActivityManager: Killing 6107:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,08-17 14:26:49.784  1036  2000 W libprocessgroup: failed to open /acct/uid_10080/pid_6107/cgroup.procs: No such file or directory
,08-17 14:26:49.865  7083  7083 D LgDataFeature: LgDataFeature() Constructor: none
08-17 14:26:49.865  7083  7083 D LgDataFeature: LgDataFeature() Constructor Done, null
08-17 14:26:49.869  7083  7083 D PhoneMonitor: Register our PhoneStateListener
,08-17 14:26:49.892  7083  7083 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-17 14:26:49.897  7083  7083 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-17 14:26:49.921  7083  7083 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
08-17 14:26:49.923  7083  7083 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-17 14:26:49.924  7083  7083 D TelephonyAutoProfiling: [parse] Load xml
,08-17 14:26:49.932  7083  7083 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-17 14:26:49.932  7083  7083 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-17 14:26:49.932  7083  7083 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-17 14:26:49.932  7083  7083 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-17 14:26:49.932  7083  7083 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-17 14:26:49.932  7083  7083 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-17 14:26:49.932  7083  7083 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-17 14:26:49.933  7083  7083 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-17 14:26:49.933  7083  7083 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-17 14:26:49.933  7083  7083 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-17 14:26:49.933  7083  7083 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-17 14:26:49.933  7083  7083 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-17 14:26:49.933  7083  7083 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-17 14:26:49.933  7083  7083 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-17 14:26:49.933  7083  7083 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-17 14:26:49.933  7083  7083 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-17 14:26:49.934  7083  7083 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-17 14:26:49.945  7083  7083 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,08-17 14:26:49.955  1036  1909 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7102 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-17 14:26:49.956  1036  1909 I ActivityManager: Killing 6586:com.google.android.apps.docs/u0a61 (adj 15): empty #17
08-17 14:26:50.011  1036  1875 W libprocessgroup: failed to open /acct/uid_10061/pid_6586/cgroup.procs: No such file or directory
,08-17 14:26:50.155  1036  7074 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-17 14:26:50.155  7057  7057 E wpa_supplicant: USIM:  scard_init function
08-17 14:26:50.155  1036  7074 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
,08-17 14:26:50.156  1036  7074 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-17 14:26:50.156  1036  7074 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: WPS-AP-AVAILABLE 
08-17 14:26:50.156  1036  7074 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-17 14:26:50.157  1036  1523 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-17 14:26:50.157  1036  1523 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-17 14:26:50.157  1036  1523 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-17 14:26:50.158  1036  1523 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-17 14:26:50.158  1036  1523 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-17 14:26:50.160  7057  7057 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-17 14:26:50.162  1036  7074 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-17 14:26:50.162  1036  7074 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-17 14:26:50.179  1036  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=331929  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-17 14:26:50.182  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 14:26:50.182  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-17 14:26:50.182  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:26:50.182  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:26:50.182  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-17 14:26:50.183  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 14:26:50.185  1036  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=331935  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-17 14:26:50.187  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:26:50.187  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:26:50.187  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-17 14:26:50.189  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-17 14:26:50.189  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-17 14:26:50.203  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 14:26:50.203  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-17 14:26:50.204  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 14:26:50.243  1036  1640 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7120 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,08-17 14:26:50.244  1036  1640 I ActivityManager: Killing 6132:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,08-17 14:26:50.275  7057  7057 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-17 14:26:50.275  1036  7074 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-17 14:26:50.276  1036  7074 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
,08-17 14:26:50.278  1036  7074 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-17 14:26:50.278  1036  7074 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-17 14:26:50.278  1036  7074 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-17 14:26:50.278  1036  7074 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-17 14:26:50.281  1036  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=332031  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-17 14:26:50.282  1036  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=332033  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-17 14:26:50.284  1036  1523 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=332034
08-17 14:26:50.285  1036  1523 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=332036
08-17 14:26:50.286  1036  1523 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=332037
08-17 14:26:50.288  1036  1523 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=332039
08-17 14:26:50.289  1036  1523 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=332039
08-17 14:26:50.290  1036  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=332040  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-17 14:26:50.291  1036  7074 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-17 14:26:50.291  1036  7074 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,08-17 14:26:50.291  7057  7057 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-17 14:26:50.292  7057  7057 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-17 14:26:50.294  1036  7074 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
,08-17 14:26:50.294  1036  7074 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-17 14:26:50.294  1036  7074 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-17 14:26:50.294  1036  7074 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-17 14:26:50.294  1036  7074 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-17 14:26:50.294  1036  7074 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-17 14:26:50.295  1036  1051 W libprocessgroup: failed to open /acct/uid_10097/pid_6132/cgroup.procs: No such file or directory
08-17 14:26:50.296  1036  7074 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-17 14:26:50.297  1036  7074 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-17 14:26:50.299  1036  1103 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-17 14:26:50.306  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 14:26:50.306  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-17 14:26:50.307  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:26:50.307  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:26:50.308  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 14:26:50.308  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-17 14:26:50.311  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:26:50.311  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:26:50.312  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-17 14:26:50.313  1036  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=332064  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-17 14:26:50.315  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-17 14:26:50.315  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-17 14:26:50.316  1036  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=332067  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-17 14:26:50.317  1036  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=332067  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-17 14:26:50.317  1036  1523 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=332068
08-17 14:26:50.317  1036  1523 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=332068
08-17 14:26:50.318  1036  1523 D WifiNative-wlan0: doString: [STATUS]
,08-17 14:26:50.318  1036  7074 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-17 14:26:50.319  1036  1523 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-17 14:26:50.320  1036  7074 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-17 14:26:50.320  1036  1523 I WifiServiceExtension: setVHTCapabilityType  : false
08-17 14:26:50.329  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 14:26:50.329  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-17 14:26:50.330  1036  1523 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-17 14:26:50.330  1036  1523 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-17 14:26:50.330  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 14:26:50.335  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:26:50.335  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:26:50.335  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-17 14:26:50.336  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:26:50.336  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:26:50.336  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-17 14:26:50.344  1036  1523 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,08-17 14:26:50.344  1036  1530 D ConnectivityService: Got NetworkAgent Messenger
08-17 14:26:50.344  1036  1523 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-17 14:26:50.344  1036  1523 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-17 14:26:50.344  1036  1530 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-17 14:26:50.344  1036  1530 D ConnectivityService: NetworkAgent connected
08-17 14:26:50.344  1036  1523 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-17 14:26:50.344  1036  1523 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,08-17 14:26:50.349  1036  1523 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-17 14:26:50.349  1036  1523 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-17 14:26:50.349  1036  1523 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-17 14:26:50.350  1036  1523 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-17 14:26:50.350  1036  1523 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-17 14:26:50.351  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 14:26:50.351  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-17 14:26:50.352  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 14:26:50.354  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 14:26:50.355  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-17 14:26:50.355  1036  1523 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-17 14:26:50.356  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 14:26:50.356   331   894 D CommandListener: Setting iface cfg
08-17 14:26:50.390  1036  1980 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7139 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-17 14:26:50.391  1036  1980 I ActivityManager: Killing 6628:com.lge.eula/1000 (adj 15): empty #17
,08-17 14:26:50.439  1036  1928 W libprocessgroup: failed to open /acct/uid_1000/pid_6628/cgroup.procs: No such file or directory
08-17 14:26:50.439  1036  1523 E WifiStateMachine: Start Dhcp Watchdog 2
08-17 14:26:50.440  1036  7138 D DhcpStateMachine: StoppedState
08-17 14:26:50.440  1036  7138 D DhcpStateMachine: StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:26:50.440  1036  7138 D DhcpStateMachine: WaitBeforeStartState
08-17 14:26:50.442  1036  1523 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=332192  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,08-17 14:26:50.444  1036  1523 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=332194  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-17 14:26:50.446  1036  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=332197  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-17 14:26:50.448  1036  1523 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
,08-17 14:26:50.449  1036  1523 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-17 14:26:50.450  1036  1523 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-17 14:26:50.452  1036  1523 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-17 14:26:50.453  1036  1523 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-17 14:26:50.454  1036  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-17 14:26:50.458  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
,08-17 14:26:50.458  1036  1036 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-17 14:26:50.459  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-17 14:26:50.459  1036  1036 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-17 14:26:50.460  1036  1523 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=332211  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-17 14:26:50.461  1036  1523 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=332211  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-17 14:26:50.461  1036  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=332212  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-17 14:26:50.463  1036  1523 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:286222] from screen [on:0 period:-1736972066] gl rssi=-47 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-17 14:26:50.464  1036  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1736972065] gl rssi=-47 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-17 14:26:50.464  1036  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-17 14:26:50.467  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-17 14:26:50.469  1036  1530 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,08-17 14:26:50.469  1036  1523 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 14:26:50.470  1036  1523 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 14:26:50.470  1036  1523 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 14:26:50.471  1036  1523 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,08-17 14:26:50.471  1036  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 14:26:50.472  1036  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 14:26:50.472  1036  1530 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-17 14:26:50.472  1036  1523 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=154,0,0
08-17 14:26:50.473  1036  1523 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=154,0,0
08-17 14:26:50.473  1036  1523 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-17 14:26:50.473  7057  7057 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-17 14:26:50.474  1036  1523 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-17 14:26:50.474  1036  1523 D WifiNative-wlan0: doBoolean: SET ps 0
08-17 14:26:50.474  1036  1523 D WifiNative-wlan0: SET ps 0: returned true
08-17 14:26:50.474  1036  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-17 14:26:50.475  7057  7057 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-17 14:26:50.475  1036  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-17 14:26:50.475  1036  1522 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@45ec141 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:26:50.475  1036  1522 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@45ec141 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:26:50.475  1036  7138 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:26:50.475  1036  7138 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-17 14:26:50.476  1036  1523 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-17 14:26:50.476  1036  1523 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-17 14:26:50.476  1036  1523 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-17 14:26:50.477   331   894 D CommandListener: Setting iface cfg
08-17 14:26:50.477   331   894 D CommandListener: Trying to bring up wlan0
08-17 14:26:50.478  1036  1523 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-17 14:26:50.479  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-17 14:26:50.479  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-17 14:26:50.479  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-17 14:26:50.479  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-17 14:26:50.480  1036  1523 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK 
08-17 14:26:50.480  1036  1523 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK 
08-17 14:26:50.481  1036  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-17 14:26:50.481  1036  1522 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:26:50.481  1036  1522 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,08-17 14:26:50.481  7057  7057 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-17 14:26:50.481  1036  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-17 14:26:50.481  1036  1523 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
,08-17 14:26:50.481  7057  7057 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-17 14:26:50.482  1036  1523 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-17 14:26:50.482  1036  1523 D WifiNative-wlan0: doBoolean: SET ps 1
08-17 14:26:50.492  7139  7139 I art     : Almond Protected OAT
08-17 14:26:50.501  1036  1523 D WifiNative-wlan0: SET ps 1: returned true
08-17 14:26:50.502  1036  1530 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-17 14:26:50.502  1036  1523 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-17 14:26:50.503  1036  1523 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-17 14:26:50.504  1036  1523 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-17 14:26:50.506  1036  1523 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-17 14:26:50.507  1036  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-17 14:26:50.508  1036  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-17 14:26:50.509  1036  1530 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-17 14:26:50.510  1036  1523 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-17 14:26:50.510  1036  1523 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-17 14:26:50.511  1036  1523 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-17 14:26:50.511  1036  1530 D ConnectivityService: ignoring duplicate network state non-change
08-17 14:26:50.513  1036  1530 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-17 14:26:50.514  1036  1530 D ConnectivityService: Adding iface wlan0 to network 101
,08-17 14:26:50.519  1036  1523 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-17 14:26:50.545  7139  7139 D WeatherApplication: removeAccount
,08-17 14:26:50.547  7139  7139 D WeatherApplication: Account.length = 0
08-17 14:26:50.547  7139  7139 E WeatherApplication: OPERATOR:OPEN
08-17 14:26:50.551  7139  7139 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:26:50
08-17 14:26:50.554  7139  7139 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-17 14:26:50.554  7139  7139 D Weather.Utils: 2 : All the weather widget is gone.
08-17 14:26:50.557  7139  7139 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-17 14:26:50.559  1036  1530 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-17 14:26:50.559  1036  1530 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-17 14:26:50.560  7139  7139 D WeatherAncestor: connectivity changed - connection : true
08-17 14:26:50.560  7139  7139 D WeatherService: 2 : isServiceAlived():false forecastCache:null
08-17 14:26:50.561  1036  1530 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-17 14:26:50.562   331   894 E Netd    : netlink response contains error (File exists)
08-17 14:26:50.563  1036  1530 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-17 14:26:50.564  1036  1530 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-17 14:26:50.564  1036  1530 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-17 14:26:50.564  1036  1530 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-17 14:26:50.565  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 14:26:50.565  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-17 14:26:50.567  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 14:26:50.568  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:26:50.568  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:26:50.568  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-17 14:26:50.570  7139  7139 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-17 14:26:50.570  7139  7139 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-17 14:26:50.570  7139  7139 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
,08-17 14:26:50.574  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:26:50.574  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:26:50.574  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-17 14:26:50.574  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-17 14:26:50.577  1929  1929 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-17 14:26:50.579  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:26:50.579  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:26:50.579  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-17 14:26:50.579  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-17 14:26:50.582  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:26:50.582  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:26:50.582  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-17 14:26:50.582  1036  1530 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-17 14:26:50.582  1036  1530 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-17 14:26:50.582  1036  1530 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-17 14:26:50.582  1036  1530 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-17 14:26:50.582  1036  1530 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-17 14:26:50.582  1036  7137 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:26:50.582  1036  7137 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-17 14:26:50.582  1036  1530 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-17 14:26:50.582  1036  7137 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:26:50.582  1036  1530 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-17 14:26:50.582  1036  1530 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 14:26:50.582  1036  7137 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-17 14:26:50.583  1036  1530 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-17 14:26:50.583  1036  1530 D ConnectivityService: currentScore = 0, newScore = 20
08-17 14:26:50.583  1036  1530 D ConnectivityService:    accepting network in place of null
08-17 14:26:50.583  1036  1530 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 14:26:50.583  1036  1523 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities:, INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 14:26:50.583  1036  1523 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-17 14:26:50.583  1839  1839 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 14:26:50.584  1839  1839 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-17 14:26:50.584   331  7160 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
,08-17 14:26:50.586  1036  1530 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-17 14:26:50.586  1036  1530 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-17 14:26:50.586  1036  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-17 14:26:50.589  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 14:26:50.589  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-17 14:26:50.592  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 14:26:50.593  1036  1530 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-17 14:26:50.593  1036  1530 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-17 14:26:50.594  1036  1036 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-17 14:26:50.594  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-17 14:26:50.595  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-17 14:26:50.595  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-17 14:26:50.595  1036  1530 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,08-17 14:26:50.596  1036  1530 D ConnectivityService: validation of new default Network = false
08-17 14:26:50.596  1036  1530 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-17 14:26:50.596  1036  1530 D DSQN    : enableDataServiceNotify 
08-17 14:26:50.596  1036  1530 D DSQN    : start dsqn bin
08-17 14:26:50.598  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 14:26:50.598  1590  1590 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-17 14:26:50.598  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 14:26:50.602  1036  1530 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-17 14:26:50.602  1036  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 14:26:50.603  1036  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-17 14:26:50.603  1036  1530 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-17 14:26:50.587  7161  7161 W dsqn    : type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 14:26:50.603  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 14:26:50.603  1590  2061 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-17 14:26:50.604  1590  1590 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-17 14:26:50.604  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 14:26:50.587  7161  7161 W dsqn    : type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 14:26:50.612  7139  7139 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
,08-17 14:26:50.612  7139  7139 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:26:50
08-17 14:26:50.617  1036  1522 D LGWifiP2pService: InactiveState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:26:50.617  1036  1522 D LGWifiP2pService: P2pEnabledState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:26:50.617  1036  1522 D LGWifiP2pService: DefaultState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:26:50.619  7161  7161 E DSQN    : DSQN ssw
,08-17 14:26:50.626  1036  1523 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-17 14:26:50.626  1036  1523 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-17 14:26:50.626  1036  1523 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
08-17 14:26:50.627  1036  1523 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-17 14:26:50.627  1036  1523 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-17 14:26:50.627  1036  1523 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
08-17 14:26:50.638   331  7160 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-17 14:26:50.646  1036  1980 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7166 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-17 14:26:50.657  1036  1980 I ActivityManager: Killing 6645:com.lge.bnr/1000 (adj 15): empty #17
,08-17 14:26:50.658   356   356 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 504us total 17.370ms
08-17 14:26:50.669   331  7160 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-17 14:26:50.672   356   356 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 288us total 13.681ms
08-17 14:26:50.678  1036  7138 D DhcpStateMachine: DHCPV4 request on wlan0
08-17 14:26:50.678  1036  7138 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-17 14:26:50.678  1036  7138 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-17 14:26:50.667  7183  7183 W dhcpcd  : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 14:26:50.667  7183  7183 W dhcpcd  : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-17 14:26:50.685   356   356 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 247us total 13.041ms
08-17 14:26:50.688  7183  7183 I dhcpcd  : version 5.5.6 starting
,08-17 14:26:50.690  7183  7183 E dhcpcd  : get_duid: m
08-17 14:26:50.690  7183  7183 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-17 14:26:50.690  7183  7183 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-17 14:26:50.699   331   893 D LGDataListener: argv[0]=dsqncommand
08-17 14:26:50.699   331   893 D LGDataListener: argv[1]=wlan0
08-17 14:26:50.699   331   893 D LGDataListener: argv[2]=1
08-17 14:26:50.699   331   893 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
,08-17 14:26:50.700  1036  1101 D DSQN    : DSQM DsqnNotification wlan0  1
08-17 14:26:50.700  1036  1101 D DSQN    : start to monitor internet connection
08-17 14:26:50.708  1804  7165 I CheckinService: active receiver: enabled
,08-17 14:26:50.717  1804  7165 I CheckinService: Preparing to send checkin request
08-17 14:26:50.717  1804  7165 I EventLogService: Accumulating logs since 1471436536203
08-17 14:26:50.719  1036  1638 W libprocessgroup: failed to open /acct/uid_1000/pid_6645/cgroup.procs: No such file or directory
08-17 14:26:50.725  1036  1521 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-17 14:26:50.731  1036  7137 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 17 Aug 2016 12:26:50 GMT], X-Android-Received-Millis=[1471436810730], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1471436810699]}
08-17 14:26:50.731  1036  7137 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-17 14:26:50.731  1036  7137 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-17 14:26:50.732  1036  1530 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-17 14:26:50.732  1036  1530 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-17 14:26:50.732  1036  1530 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-17 14:26:50.732  1036  1530 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-17 14:26:50.732  1036  1530 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
,08-17 14:26:50.732  1036  1530 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-17 14:26:50.732  1036  1530 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-17 14:26:50.732  1036  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 14:26:50.732  1036  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-17 14:26:50.732  1036  1530 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-17 14:26:50.733  1036  1530 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 14:26:50.733  1036  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-17 14:26:50.733  1839  1839 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 14:26:50.733  1036  1523 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 14:26:50.733  1036  1523 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-17 14:26:50.734  1839  1839 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-17 14:26:50.734  1590  2061 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-17 14:26:50.746  1590  1590 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-17 14:26:50.747  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 14:26:50.748  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 14:26:50.749  7183  7183 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-17 14:26:50.749  7183  7183 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-17 14:26:50.749  7183  7183 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-17 14:26:50.750  7183  7183 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
08-17 14:26:50.750  7183  7183 D dhcpcd  : wlan0: sending REQUEST (xid 0xa72cea75), next in 3.85 seconds
08-17 14:26:50.764  1804  7165 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
08-17 14:26:50.766  1590  1590 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-17 14:26:50.767  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 14:26:50.768  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 14:26:50.775  7183  7183 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,08-17 14:26:50.786  7183  7183 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
08-17 14:26:50.786  7183  7183 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
08-17 14:26:50.786  7183  7183 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-17 14:26:50.786  7183  7183 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-17 14:26:50.786  7183  7183 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-17 14:26:50.787  7183  7183 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-17 14:26:50.787  7183  7183 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-17 14:26:50.787  7183  7183 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,08-17 14:26:50.824   279   364 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-17 14:26:50.824   279   364 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-17 14:26:50.824   279   364 W Vold    : Returning OperationFailed - no handler for errno 0
,08-17 14:26:50.827  7166  7197 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-17 14:26:50.829   279   364 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-17 14:26:50.829   279   364 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-17 14:26:50.829   279   364 W Vold    : Returning OperationFailed - no handler for errno 0
08-17 14:26:50.830  7166  7197 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-17 14:26:50.835   279   364 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-17 14:26:50.835   279   364 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-17 14:26:50.835   279   364 W Vold    : Returning OperationFailed - no handler for errno 0
08-17 14:26:50.836  7166  7204 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-17 14:26:50.841   279   364 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-17 14:26:50.841   279   364 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-17 14:26:50.841   279   364 W Vold    : Returning OperationFailed - no handler for errno 0
,08-17 14:26:50.844  7166  7204 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-17 14:26:50.865  1036  2001 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7207 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-17 14:26:50.906  7207  7207 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-17 14:26:50.906  7207  7207 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-17 14:26:50.934  7207  7207 I MultiDex: VM with version 2.1.0 has multidex support
,08-17 14:26:50.934  7207  7207 I MultiDex: install
08-17 14:26:50.934  7207  7207 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-17 14:26:50.944  7207  7207 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
08-17 14:26:51.057  7166  7166 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-17 14:26:51.072  7166  7166 I LibraryLoader: Loading: webviewchromium
08-17 14:26:51.075  7166  7166 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 2835-2839)
08-17 14:26:51.076  7166  7166 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-17 14:26:51.079  1036  7138 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-17 14:26:51.080  1036  7138 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-17 14:26:51.080  1036  7138 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-17 14:26:51.080  1036  7138 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
08-17 14:26:51.080  1036  7138 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-17 14:26:51.080  1036  7138 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-17 14:26:51.080  1036  7138 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-17 14:26:51.080  1036  7138 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-17 14:26:51.081  1036  7138 D DhcpStateMachine: RunningState
08-17 14:26:51.085  7166  7166 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {347d8429}
08-17 14:26:51.089  7166  7166 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-17 14:26:51.090  7166  7166 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,08-17 14:26:51.106  7166  7166 I BrowserStartupController: Initializing chromium process, renderers=0
,08-17 14:26:51.108  7166  7166 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-17 14:26:51.117   335  2176 V AudioPolicyService: registerClient() client 0xb1008360, uid 10093
08-17 14:26:51.118  7166  7256 W AudioManagerAndroid: Requires BLUETOOTH permission
08-17 14:26:51.119  7166  7166 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-17 14:26:51.120  7166  7166 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-17 14:26:51.120  7166  7166 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-17 14:26:51.145  7166  7166 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-17 14:26:51.145  7166  7166 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-17 14:26:51.145  7166  7166 I Adreno-EGL: Build Date: 12/12/14 금
08-17 14:26:51.145  7166  7166 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-17 14:26:51.145  7166  7166 I Adreno-EGL: Remote Branch: 
08-17 14:26:51.145  7166  7166 I Adreno-EGL: Local Patches: 
08-17 14:26:51.145  7166  7166 I Adreno-EGL: Reconstruct Branch: 
,08-17 14:26:51.324  7271  7271 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-17 14:26:51.376  1036  1928 I art     : Explicit concurrent mark sweep GC freed 104020(5MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 1.778ms total 161.546ms
,08-17 14:26:51.382  7166  7166 I NSApplication: Starting up...
08-17 14:26:51.404  7271  7271 I dex2oat : dex2oat took 79.870ms (threads: 4)
,08-17 14:26:51.415  7207  7227 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-17 14:26:51.415  7207  7227 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-17 14:26:51.415  7207  7227 I Adreno-EGL: Build Date: 12/12/14 금
08-17 14:26:51.415  7207  7227 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-17 14:26:51.415  7207  7227 I Adreno-EGL: Remote Branch: 
08-17 14:26:51.415  7207  7227 I Adreno-EGL: Local Patches: 
08-17 14:26:51.415  7207  7227 I Adreno-EGL: Reconstruct Branch: 
08-17 14:26:51.427  1036  1946 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7278 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-17 14:26:51.428  1036  1946 I ActivityManager: Killing 6068:com.android.vending/u0a44 (adj 15): empty #17
,08-17 14:26:51.509  7207  7227 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-17 14:26:51.509  7207  7227 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-17 14:26:51.509  7207  7227 I Adreno-EGL: Build Date: 12/12/14 금
08-17 14:26:51.509  7207  7227 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-17 14:26:51.509  7207  7227 I Adreno-EGL: Remote Branch: 
08-17 14:26:51.509  7207  7227 I Adreno-EGL: Local Patches: 
08-17 14:26:51.509  7207  7227 I Adreno-EGL: Reconstruct Branch: 
,08-17 14:26:51.522  1036  1964 W libprocessgroup: failed to open /acct/uid_10044/pid_6068/cgroup.procs: No such file or directory
08-17 14:26:51.547  1036  1946 D WifiServiceImplEx: setWifiEnabled: false pid=6725, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-17 14:26:51.548  1036  1946 D WifiService: setWifiEnabled: false pid=6725, uid=10118
08-17 14:26:51.548  1036  1946 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-17 14:26:51.552  7278  7278 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-17 14:26:51.557  1036  1523 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-17 14:26:51.557  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-17 14:26:51.557  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-17 14:26:51.557  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-17 14:26:51.557  1036  1523 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-17 14:26:51.558  1036  1523 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-17 14:26:51.558  1036  1523 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-17 14:26:51.559  1036  1523 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-17 14:26:51.559  1036  1523 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-17 14:26:51.559  1036  1523 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-17 14:26:51.559  1036  1523 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-17 14:26:51.560  1036  1523 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-17 14:26:51.560  1036  1523 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-17 14:26:51.565  1036  1523 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-17 14:26:51.565  1036  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-17 14:26:51.565  1036  1522 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:26:51.565  1036  1522 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:26:51.565  7057  7057 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
,08-17 14:26:51.565  1036  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-17 14:26:51.565  1036  1523 D WifiNative-wlan0: doBoolean: SET ps 1
08-17 14:26:51.566  1036  1523 D WifiNative-wlan0: SET ps 1: returned true
08-17 14:26:51.566  1036  7138 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:26:51.566   331   894 D CommandListener: Clearing all IP addresses on wlan0
,08-17 14:26:51.593  1036  1530 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-17 14:26:51.593  1036  1530 D ConnectivityService: ignoring duplicate network state non-change
08-17 14:26:51.593  1036  1530 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
08-17 14:26:51.595  1036  1036 D WifiHS20: hidePasspointNotification off =false
,08-17 14:26:51.616  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 14:26:51.616  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-17 14:26:51.617  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 14:26:51.618  1036  1523 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-17 14:26:51.619  1036  1522 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:26:51.619  1036  1522 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:26:51.619  1036  1522 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@335234
08-17 14:26:51.619  1036  1522 D LGWifiP2pService: P2pDisablingState
08-17 14:26:51.619  1036  1522 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:26:51.619  1036  1522 D LGWifiP2pService: p2p socket connection lost
08-17 14:26:51.619  1036  1522 D LGWifiP2pService: P2pDisabledState
08-17 14:26:51.619  1929  1929 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-17 14:26:51.619  1036  1523 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-17 14:26:51.619  1036  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-17 14:26:51.619  7057  7057 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-17 14:26:51.620  1036  1522 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:26:51.620  1036  1522 D LGWifiP2pService: DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:26:51.621  1036  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-17 14:26:51.621  1036  1523 D WifiNative-wlan0: doBoolean: SET ps 1
08-17 14:26:51.621  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:26:51.621  1036  1523 D WifiNative-wlan0: SET ps 1: returned true
08-17 14:26:51.621  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:26:51.621  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-17 14:26:51.622  1036  1036 D WifiHS20: hidePasspointNotification off =false
,08-17 14:26:51.623  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:26:51.623  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:26:51.623  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-17 14:26:51.624  1929  1929 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-17 14:26:51.624  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 1
08-17 14:26:51.624  1036  1036 D RttService: SCAN_AVAILABLE : 1
08-17 14:26:51.624  1036  1542 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:26:51.625  1929  1929 D WfdsService: WifiP2pState is changed : false
08-17 14:26:51.625  1036  1541 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:26:51.625  1929  2234 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-17 14:26:51.625  1929  2234 D WfdsService: Set the WFDS Monitor: false
08-17 14:26:51.641  1929  2234 D WfdsMonitor: WFDS Monitor is stopped
08-17 14:26:51.641  1929  2234 D WfdsService: STATE : WfdsDisabledState - enter
08-17 14:26:51.641  1929  7077 D CtrlSupplicant: Received on exit socket, terminate
08-17 14:26:51.641  1929  7077 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-17 14:26:51.641  1929  7077 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-17 14:26:51.641  1929  7077 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-17 14:26:51.641  1929  2234 W WfdsService: DefaultState - msg [9445378] is not handled
,08-17 14:26:51.641  1929  2235 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-17 14:26:51.642  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 14:26:51.642  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-17 14:26:51.642  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 14:26:51.661   331   894 D CommandListener: Clearing all IP addresses on wlan0
08-17 14:26:51.662  1036  1530 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-17 14:26:51.662  1036  1530 D DSQN    : disableDataServiceNotify
08-17 14:26:51.662  1036  1530 D DSQN    : stop dsqn bin
,08-17 14:26:51.664  1036  1523 D WifiNative-p2p0: doBoolean: TERMINATE
08-17 14:26:51.664  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-17 14:26:51.665  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-17 14:26:51.665  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-17 14:26:51.665  1036  1523 D WifiNative-p2p0: TERMINATE: returned true
08-17 14:26:51.665  1036  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-17 14:26:51.665  1036  1523 E WifiStateMachine: useWiFiOffloading() : false
08-17 14:26:51.665  1036  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-17 14:26:51.665  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:26:51.666  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:26:51.666  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,08-17 14:26:51.666  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 14:26:51.667  1929  1929 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-17 14:26:51.668  1036  1530 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-17 14:26:51.668  1036  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 14:26:51.668  1036  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-17 14:26:51.668  1036  1530 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-17 14:26:51.677  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-17 14:26:51.677  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-17 14:26:51.677  1036  1036 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-17 14:26:51.677  1036  1530 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
,08-17 14:26:51.678  1036  1530 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-17 14:26:51.678  1036  1530 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-17 14:26:51.678  1036  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-17 14:26:51.678  1036  1530 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-17 14:26:51.678  1036  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-17 14:26:51.678  1036  1530 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-17 14:26:51.678  1036  1530 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 14:26:51.678  1036  1530 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 14:26:51.678  1036  1521 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-17 14:26:51.679  1036  1530 D NetworkManagementService: Removing idletimer
08-17 14:26:51.679  1036  1530 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:26:51.679  1036  1530 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
08-17 14:26:51.679  1839  1839 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 14:26:51.679  1036  7137 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:26:51.679  1036  7137 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:26:51.679  1036  7137 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-17 14:26:51.679  1839  1839 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-17 14:26:51.680  1036  1523 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 14:26:51.680  1036  1523 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-17 14:26:51.680  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-17 14:26:51.680  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-17 14:26:51.680  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedT,oProvisioningNetwork: false] info.getType():1
08-17 14:26:51.680  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-17 14:26:51.681  1590  2061 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-17 14:26:51.681  6725  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:26:51.681  6725  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 14:26:51.681  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:26:51.681  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 14:26:51.681  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 14:26:51.681  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 14:26:51.681  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 14:26:51.681  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 14:26:51.681  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 14:26:51.681  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-17 14:26:51.681  6725  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:26:51.681  6725  6725 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 14:26:51.681  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-17 14:26:51.681  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-17 14:26:51.681  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-17 14:26:51.682  1036  1521 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-17 14:26:51.682  6725  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:26:51.682  6725  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 14:26:51.682  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:26:51.682  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 14:26:51.682  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 14:26:51.682  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 14:26:51.682  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 14:26:51.682  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 14:26:51.682  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 14:26:51.682  6725  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:26:51.682  6725  6725 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 14:26:51.685  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 14:26:51.692,  7207  7227 D LgDataFeature: LgDataFeature() Constructor: none
08-17 14:26:51.692  7207  7227 D LgDataFeature: LgDataFeature() Constructor Done, null
08-17 14:26:51.713  7207  7227 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-17 14:26:51.713  7207  7227 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-17 14:26:51.713  7207  7227 I Adreno-EGL: Build Date: 12/12/14 금
08-17 14:26:51.713  7207  7227 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-17 14:26:51.713  7207  7227 I Adreno-EGL: Remote Branch: 
08-17 14:26:51.713  7207  7227 I Adreno-EGL: Local Patches: 
08-17 14:26:51.713  7207  7227 I Adreno-EGL: Reconstruct Branch: 
,08-17 14:26:51.717  1590  1590 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-17 14:26:51.718  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 14:26:51.719  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-17 14:26:51.745  1590  1590 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-17 14:26:51.747  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 14:26:51.748  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 14:26:51.758  7057  7057 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-17 14:26:51.758  7057  7057 I wpa_supplicant: monitor socket send errors count : 1
08-17 14:26:51.758  7057  7057 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1929-4\x00 that cannot receive messages
08-17 14:26:51.759  1036  7074 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-17 14:26:51.759  1036  7074 D WifiMonitor: Dropping event because (p2p0) is stopped
,08-17 14:26:51.770  1036  7138 D DhcpStateMachine: StoppedState
08-17 14:26:51.770  1036  7138 D DhcpStateMachine: StoppedState{ when=-149ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:26:51.771  1036  1523 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-17 14:26:51.771  1036  1523 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
,08-17 14:26:51.773  1036  1365 V AlarmManager: ELAPSED_WAKEUP set : Alarm{3b1f421 type 2 when 333524 com.google.android.gms} when 333524
08-17 14:26:51.779  7057  7057 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-17 14:26:51.779  1036  7074 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-17 14:26:51.780  1036  7074 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-17 14:26:51.780  1036  7074 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-17 14:26:51.780  1036  7074 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-17 14:26:51.780  1036  1523 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=333531
08-17 14:26:51.780  7057  7057 W wpa_supplicant: USIM:  scard_deinit function
08-17 14:26:51.781  1036  1523 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=333531
08-17 14:26:51.781  1036  7074 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-17 14:26:51.781  1036  7074 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-17 14:26:51.781  1036  1103 D Tethering: InitialState.processMessage what=4
08-17 14:26:51.782  1036  1523 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=333532  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-17 14:26:51.782  1036  1523 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=333533  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-17 14:26:51.783  1036  1103 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-17 14:26:51.785  1036  1523 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-17 14:26:51.786  1036  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-17 14:26:51.823  6461  6461 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-17 14:26:51.825  6461  6856 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-17 14:26:51.835  2162  2162 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-17 14:26:51.842  7008  7008 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-17 14:26:51.842  7008  7008 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-17 14:26:51.842  7008  7008 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-17 14:26:51.842  7008  7008 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-17 14:26:51.843  7008  7008 I AppUp4:CustModeStarterReceiver: onReceive
08-17 14:26:51.845  7008  7008 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@3f8bc126
08-17 14:26:51.845  7008  7008 D AppUp4:CustFacade: isCustomizationCompleted : false
08-17 14:26:51.845  7008  7008 D AppUp4:CustFacade: isPhone : true
08-17 14:26:51.845  7008  7008 D AppUp4:CustModeStarterReceiver: begin check event
08-17 14:26:51.845  7008  7008 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-17 14:26:51.848  4312  4312 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-17 14:26:51.848  4312  4312 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-17 14:26:51.850  4312  4312 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-17 14:26:51.851  4312  4312 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-17 14:26:51.856  7048  7048 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-17 14:26:51.856  4312  7316 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-17 14:26:51.858  4312  7317 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-17 14:26:51.858  4312  7317 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-17 14:26:51.869  7048  7319 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-17 14:26:51.875  6925  7321 W FormManager: Network not available. Please check & try again.
08-17 14:26:51.879  3400  3400 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,08-17 14:26:51.879  3400  3400 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-17 14:26:51.879  3400  3400 I LgeMiscReceiver: networkInfo.isConnected() = false
08-17 14:26:51.882  7083  7083 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-17 14:26:51.883  7083  7083 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-17 14:26:51.893  7057  7057 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-17 14:26:51.893  1036  7074 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-17 14:26:51.893  1036  7074 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-TERMINATING 
08-17 14:26:51.893  1036  7074 D WifiMonitor: Disconnecting from the supplicant, no more events
08-17 14:26:51.894  1036  1523 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 44 0
08-17 14:26:51.895  6925  7322 V FormManager: Network unavailable.
08-17 14:26:51.897  7139  7139 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:26:51
,08-17 14:26:51.899  7139  7139 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-17 14:26:51.899  7139  7139 D Weather.Utils: 2 : All the weather widget is gone.
08-17 14:26:51.899  6925  7322 V FormManager: Network unavailable.
08-17 14:26:51.900  7139  7139 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-17 14:26:51.900  7139  7139 D WeatherAncestor: connectivity changed - connection : true
08-17 14:26:51.900  7139  7139 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3c6b2b14
08-17 14:26:51.900  7139  7139 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-17 14:26:51.900  7139  7139 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-17 14:26:51.900  7139  7139 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-17 14:26:51.900  7139  7139 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-17 14:26:51.900  7139  7139 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:26:51
08-17 14:26:51.910   331  7328 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-17 14:26:51.911  1804  7165 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
08-17 14:26:51.911  1036  1101 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-17 14:26:51.919  1804  7165 I CheckinService: active receiver: disabled
,08-17 14:26:51.930   331  7330 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-17 14:26:51.931  1036  1101 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-17 14:26:51.934  6837  6837 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-17 14:26:51.934  6837  6837 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-17 14:26:51.934  6837  6837 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-17 14:26:51.934  6837  6837 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-17 14:26:51.935  6837  6837 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-17 14:26:51.936  6837  6837 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-17 14:26:51.936  6837  6837 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-17 14:26:51.936  6837  6837 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-17 14:26:51.936  6837  6837 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-17 14:26:51.936  6837  6837 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-17 14:26:51.937  6837  6837 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-17 14:26:51.944  6858  6858 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-17 14:26:51.946  6837  6837 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-17 14:26:51.950  6925  7332 W FormManager: Network not available. Please check & try again.
08-17 14:26:51.952  6925  7333 V FormManager: Network unavailable.
08-17 14:26:51.953  6837  6837 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 14:26:51.954  6925  7333 V FormManager: Network unavailable.
08-17 14:26:51.970  6858  6858 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-17 14:26:51.973  6837  6837 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-17 14:26:51.979  6925  7335 W FormManager: Network not available. Please check & try again.
,08-17 14:26:51.982  6837  6837 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 14:26:51.989  6925  7336 V FormManager: Network unavailable.
08-17 14:26:51.993  6925  7336 V FormManager: Network unavailable.
08-17 14:26:51.995  1929  1929 D WfdsService: Supplicant Connection state is changed : false
08-17 14:26:51.996  1929  2234 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-17 14:26:51.996  1929  2234 D WfdsService: Set the WFDS Monitor: false
08-17 14:26:51.996  1929  2234 D WfdsMonitor: WFDS Monitor is stopped
,08-17 14:26:51.998  4312  4312 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-17 14:26:51.998  4312  4312 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-17 14:26:51.998  1036  1523 D WifiOffDelayIfNotUsed: stopMonitoring
08-17 14:26:51.998  1036  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-17 14:26:51.998  1036  1523 E WifiStateMachine: useWiFiOffloading() : false
08-17 14:26:51.998  1036  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-17 14:26:52.000  4312  4312 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-17 14:26:52.000  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 14:26:52.002  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-17 14:26:52.002  1929  1929 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-17 14:26:52.002  1036  1528 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-17 14:26:52.002  1036  1528 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-17 14:26:52.002  2472  2472 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:26:52.004  6725  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:26:52.004  6725  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 14:26:52.004  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:26:52.004  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 14:26:52.004  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 14:26:52.004  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 14:26:52.004  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 14:26:52.004  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 14:26:52.004  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 14:26:52.005  4312  4312 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-17 14:26:52.006  6725  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:26:52.013  4312  7337 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-17 14:26:52.014  4312  7338 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-17 14:26:52.014  4312  7338 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-17 14:26:52.059  1036  1051 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7339 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-17 14:26:52.188  7339  7339 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-17 14:26:52.188  7339  7339 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-17 14:26:52.197  7339  7339 V [BNRBootReceiver]: Boot Receiver Return
08-17 14:26:52.201  7339  7339 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-17 14:26:52.201  6461  6461 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-17 14:26:52.215  6837  6837 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-17 14:26:52.228  6837  6837 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 14:26:52.252  6887  6887 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-17 14:26:52.252  6887  6887 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-17 14:26:52.257  6887  6887 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-17 14:26:52.265  6837  6837 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-17 14:26:52.273  6837  6837 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-17 14:26:52.281  6461  6461 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-17 14:26:52.301  6837  6837 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-17 14:26:52.317  6837  6837 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 14:26:52.328  6887  6887 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-17 14:26:52.328  6887  6887 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-17 14:26:52.332  6887  6887 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-17 14:26:52.336  6461  6461 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-17 14:26:52.350  6837  6837 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-17 14:26:52.362  6837  6837 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 14:26:52.374  6887  6887 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-17 14:26:52.374  6887  6887 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-17 14:26:52.375  6887  6887 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-17 14:26:52.388  6461  6461 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-17 14:26:52.400  6837  6837 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-17 14:26:52.414  6837  6837 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-17 14:26:52.424  6887  6887 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-17 14:26:52.425  6887  6887 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-17 14:26:52.426  6887  6887 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-17 14:26:52.433  6461  6461 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-17 14:26:52.441  6837  6837 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-17 14:26:52.448  6837  6837 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 14:26:52.457  6887  6887 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-17 14:26:52.457  6887  6887 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-17 14:26:52.457  6887  6887 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-17 14:26:52.462  6461  6461 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-17 14:26:52.471  6837  6837 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-17 14:26:52.480  6837  6837 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 14:26:52.489  6887  6887 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-17 14:26:52.490  6887  6887 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-17 14:26:52.490  6887  6887 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-17 14:26:52.494  6461  6461 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-17 14:26:52.504  6837  6837 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-17 14:26:52.512  6837  6837 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 14:26:52.524  6887  6887 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-17 14:26:52.524  6887  6887 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-17 14:26:52.525  6887  6887 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-17 14:26:52.538  6461  6461 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-17 14:26:52.558  6837  6837 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-17 14:26:52.568  6837  6837 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 14:26:52.580  6887  6887 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-17 14:26:52.581  6887  6887 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-17 14:26:52.589  6887  6887 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-17 14:26:52.596  6461  6461 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-17 14:26:52.608  6837  6837 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-17 14:26:52.615  6837  6837 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-17 14:26:52.627  6887  6887 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-17 14:26:52.627  6887  6887 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-17 14:26:52.628  6887  6887 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-17 14:26:52.638  6461  6461 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-17 14:26:52.647  6858  6858 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-17 14:26:52.647  6663  6993 D UEI.SmartControl: Internal timer expired: 2
08-17 14:26:52.647  6663  6993 D UEI.SmartControl: unbind internal service
,08-17 14:26:52.658  1036  1529 D WifiService: New client listening to asynchronous messages
08-17 14:26:52.659  6858  6858 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-17 14:26:52.668  6837  6837 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-17 14:26:52.678  6837  6837 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-17 14:26:52.691  6887  6887 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-17 14:26:52.693  6887  6887 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-17 14:26:52.695  6887  6887 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,08-17 14:26:52.700  6887  6887 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-17 14:26:52.701  6887  6887 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-17 14:26:52.703  6663  6987 D serial_port: close(fd = 24)
08-17 14:26:52.709  6461  6461 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-17 14:26:52.710  6663  6987 I UEI.SmartControl: Serial port is closed.
08-17 14:26:52.719  6858  6858 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-17 14:26:52.722  6858  6858 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-17 14:26:52.731  6837  6837 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-17 14:26:52.741  6837  6837 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 14:26:52.755  6887  6887 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-17 14:26:52.756  6887  6887 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-17 14:26:52.759  6887  6887 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-17 14:26:52.761  6887  6887 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-17 14:26:52.762  6887  6887 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-17 14:26:52.769  1036  1909 I ActivityManager: Killing 6817:com.lge.lifetracker/u0a37 (adj 15): empty #17
,08-17 14:26:52.834  1036  1874 W libprocessgroup: failed to open /acct/uid_10037/pid_6817/cgroup.procs: No such file or directory
,08-17 14:26:52.839  2162  2162 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-17 14:26:52.854  2162  2162 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-17 14:26:52.854  2162  2162 D c       : Getting all permits...
08-17 14:26:52.854  2162  2162 D a       : Opening database...
08-17 14:26:52.859  2162  2162 D a       : Opening database auth.proximity.permit_store...
08-17 14:26:52.860  2162  2162 D a       : Closing database...
08-17 14:26:52.874  6461  6461 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-17 14:26:52.881  6858  6858 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-17 14:26:52.881  6858  6858 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-17 14:26:52.881  6858  6858 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-17 14:26:52.886  6837  6837 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-17 14:26:52.896  6837  6837 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-17 14:26:52.904  6887  6887 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-17 14:26:52.904  6887  6887 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-17 14:26:52.908  6887  6887 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-17 14:26:52.909  1036  3517 I LocationManagerService: remove 305bee2d
08-17 14:26:52.910  1036  3517 D LocationManagerService: provider request: passive ProviderRequest[ON interval=0]
08-17 14:26:52.910  1036  3517 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-17 14:26:52.910  1036  3517 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
08-17 14:26:52.911  1036  3517 D LocationManagerService: getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
08-17 14:26:52.911  1036  3517 D LocationManagerService: getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
08-17 14:26:52.912  6461  6461 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-17 14:26:52.917  6858  6858 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-17 14:26:52.917  6858  6858 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-17 14:26:52.917  6858  6858 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-17 14:26:52.920  6837  6837 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-17 14:26:52.932  6837  6837 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-17 14:26:52.942  6887  6887 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-17 14:26:52.942  6887  6887 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-17 14:26:52.944  6887  6887 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-17 14:26:52.947  6461  6461 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-17 14:26:52.952  6858  6858 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-17 14:26:52.952  6858  6858 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-17 14:26:52.952  6858  6858 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-17 14:26:52.959  6837  6837 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-17 14:26:52.966  6837  6837 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 14:26:52.974  6887  6887 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-17 14:26:52.974  6887  6887 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-17 14:26:52.975  6887  6887 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-17 14:26:52.988  6858  6858 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-17 14:26:52.993  6837  6837 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-17 14:26:53.001  6925  7371 W FormManager: Network not available. Please check & try again.
08-17 14:26:53.002  6837  6837 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 14:26:53.008  6925  7372 V FormManager: Network unavailable.
,08-17 14:26:53.011  6925  7372 V FormManager: Network unavailable.
08-17 14:26:53.024  2162  2162 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-17 14:26:53.046  4312  4312 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-17 14:26:53.047  4312  4312 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-17 14:26:53.050  4312  4312 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-17 14:26:53.052  4312  4312 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-17 14:26:53.058  4312  7376 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-17 14:26:53.063  4312  7377 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-17 14:26:53.063  6858  6858 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-17 14:26:53.063  6858  6858 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-17 14:26:53.063  6858  6858 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-17 14:26:53.063  4312  7377 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-17 14:26:53.070  6837  6837 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-17 14:26:53.080  6925  7379 W FormManager: Network not available. Please check & try again.
08-17 14:26:53.083  6837  6837 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 14:26:53.089  6925  7380 V FormManager: Network unavailable.
,08-17 14:26:53.094  6925  7380 V FormManager: Network unavailable.
,08-17 14:26:53.472  1036  1523 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1736969056] gl rssi=-47 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-17 14:26:53.475  1036  1523 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1736969054] gl rssi=-47 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-17 14:26:53.595  1036  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-17 14:26:53.614  1036  1098 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-17 14:26:53.622  1036  1103 D Tethering: MasterInitialState.processMessage what=3
,08-17 14:26:53.633  6725  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:26:53.637  6725  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:26:53.645  6461  6461 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-17 14:26:53.647  6461  6856 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-17 14:26:53.660  5768  5768 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-17 14:26:53.685  2162  2162 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-17 14:26:53.713  7008  7008 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-17 14:26:53.713  7008  7008 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-17 14:26:53.713  7008  7008 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-17 14:26:53.713  7008  7008 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-17 14:26:53.720  7008  7008 I AppUp4:CustModeStarterReceiver: onReceive
08-17 14:26:53.723  7008  7008 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@3f8bc126
08-17 14:26:53.723  7008  7008 D AppUp4:CustFacade: isCustomizationCompleted : false
08-17 14:26:53.723  7008  7008 D AppUp4:CustFacade: isPhone : true
08-17 14:26:53.724  7008  7008 D AppUp4:CustModeStarterReceiver: begin check event
08-17 14:26:53.724  7008  7008 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-17 14:26:53.730  4312  4312 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-17 14:26:53.730  4312  4312 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-17 14:26:53.732  4312  4312 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-17 14:26:53.742  4312  4312 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-17 14:26:53.753  7048  7048 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-17 14:26:53.784  3400  3400 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,08-17 14:26:53.785  3400  3400 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-17 14:26:53.785  3400  3400 I LgeMiscReceiver: networkInfo.isConnected() = true
08-17 14:26:53.785  3400  3400 D PhoneState: setPdpRejectCasuse : false
,08-17 14:26:53.797  7083  7083 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-17 14:26:53.797  7083  7083 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-17 14:26:53.804  4312  7402 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-17 14:26:53.809  4312  7405 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-17 14:26:53.809  4312  7405 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-17 14:26:53.814  7048  7388 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:26:53.815  6925  7403 W FormManager: Network not available. Please check & try again.
08-17 14:26:53.817  1036  1098 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 14:26:53.824  7139  7139 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:26:53
08-17 14:26:53.825  6925  7404 V FormManager: Network unavailable.
,08-17 14:26:53.825  7139  7139 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,08-17 14:26:53.825  7139  7139 D Weather.Utils: 2 : All the weather widget is gone.
08-17 14:26:53.826  7139  7139 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-17 14:26:53.826  7139  7139 D WeatherAncestor: connectivity changed - connection : true
08-17 14:26:53.826  7139  7139 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3c6b2b14
08-17 14:26:53.827  7139  7139 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-17 14:26:53.827  7139  7139 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-17 14:26:53.827  7139  7139 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
,08-17 14:26:53.827  7139  7139 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-17 14:26:53.827  7139  7139 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:26:53
08-17 14:26:53.827  6925  7404 V FormManager: Network unavailable.
08-17 14:26:54.559  1036  2000 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 14:26:54.560  1036  2000 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-17 14:26:54.595  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-17 14:26:54.595  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-17 14:26:54.595  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-17 14:26:54.596  1036  1103 D BluetoothManagerService: Message: 1
08-17 14:26:54.596  1036  1103 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-17 14:26:54.623  1036  1103 D BluetoothManagerService: Message: 20
08-17 14:26:54.623  1036  1103 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2af61fe7:true
,08-17 14:26:54.628  6948  6948 D BluetoothAdapterState: make
08-17 14:26:54.633  6948  6948 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-17 14:26:54.633  6948  6948 I bluedroid-qcom: init
08-17 14:26:54.634  6948  7420 I BluetoothAdapterState: Entering OffState
08-17 14:26:54.635  6948  6948 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-17 14:26:54.635  6948  6948 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-17 14:26:54.635  6948  6948 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-17 14:26:54.635  6948  6948 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-17 14:26:54.635  6948  6948 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-17 14:26:54.637  6948  6948 I bluedroid-qcom: get_profile_interface socket
08-17 14:26:54.637  6948  6948 I bluedroid-qcom: get_profile_interface map_client
,08-17 14:26:54.642  6948  7424 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-17 14:26:54.627  7423  7423 W bdaddr_loader: type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 14:26:54.637  7423  7423 W bdaddr_loader: type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 14:26:54.652  6948  7424 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-17 14:26:54.661  7423  7423 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-17 14:26:54.661  7423  7423 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-17 14:26:54.661  7423  7423 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-17 14:26:54.664  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,08-17 14:26:54.665  1036  1103 D BluetoothManagerService: Message: 40
08-17 14:26:54.665  1036  1103 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-17 14:26:54.668  6948  6965 I bluedroid-qcom: config_hci_snoop_log
08-17 14:26:54.670  1036  1103 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-17 14:26:54.670  1036  1103 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-17 14:26:54.672  7423  7423 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-17 14:26:54.677  6948  7420 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-17 14:26:54.677  6948  7420 D BluetoothAdapterProperties: Setting state to 11
08-17 14:26:54.678  6948  7420 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,08-17 14:26:54.680  1036  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-17 14:26:54.683  7423  7423 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-17 14:26:54.683  7423  7423 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-17 14:26:54.686  1036  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-17 14:26:54.686  1036  1098 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-17 14:26:54.696  6725  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:26:54.706  1036  1103 D Tethering: MasterInitialState.processMessage what=3
08-17 14:26:54.706  1036  1103 D BluetoothManagerService: Message: 60
08-17 14:26:54.706  1036  1103 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-17 14:26:54.706  1036  1103 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-17 14:26:54.707  6725  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:26:54.710  6948  7420 I LGBluetoothServiceJni: classInitNative: succeeds
,08-17 14:26:54.724  6948  7424 D BluetoothAdapterProperties: Name is: G3
08-17 14:26:54.725  1036  1103 D Tethering: MasterInitialState.processMessage what=3
08-17 14:26:54.737  1929  1929 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-17 14:26:54.738  1590  1590 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-17 14:26:54.741  6461  6461 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-17 14:26:54.745  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-17 14:26:54.745  6725  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:26:54.748  6948  7420 D BluetoothBondStateMachine: make
08-17 14:26:54.748  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
08-17 14:26:54.749  6725  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:26:54.750  6725  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:26:54.751  6725  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:26:54.752  6837  6837 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-17 14:26:54.754  5768  5768 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-17 14:26:54.756  6948  7420 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c6b2b14
08-17 14:26:54.756  6948  7420 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-17 14:26:54.756  6948  7420 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c6b2b14
08-17 14:26:54.756  6948  7420 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-17 14:26:54.756  6461  6856 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-17 14:26:54.757  6948  7420 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-17 14:26:54.758  6948  7438 I BluetoothBondStateMachine: StableState(): Entering Off State
08-17 14:26:54.761  6948  7420 E BluetoothAdapterService: File transfer profiles supported!!
08-17 14:26:54.766  6948  6948 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-17 14:26:54.770  6948  6948 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:26:54.770  6948  6948 V BluetoothPbapReceiver: ***********state = 11
,08-17 14:26:54.773  6948  7420 E BluetoothAdapterService: File transfer profiles supported!!
08-17 14:26:54.775  6948  6948 D HeadsetService: Received start request. Starting profile...
08-17 14:26:54.776  6948  6948 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-17 14:26:54.776  6948  6948 D LGBluetoothHfpAdapter: Version 1.6
08-17 14:26:54.779  6948  6948 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-17 14:26:54.781  6948  6948 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-17 14:26:54.781  6948  6948 D HeadsetStateMachine: make
08-17 14:26:54.781  6948  7420 E BluetoothAdapterService: File transfer profiles supported!!
,08-17 14:26:54.791  6948  7420 E BluetoothAdapterService: File transfer profiles supported!!
08-17 14:26:54.794  2162  2162 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-17 14:26:54.799  5768  5768 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-17 14:26:54.801  6948  7420 E BluetoothAdapterService: File transfer profiles supported!!
,08-17 14:26:54.805  1036  1098 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-17 14:26:54.830  6948  6948 D LgDataFeature: LgDataFeature() Constructor: none
,08-17 14:26:54.830  6948  6948 D LgDataFeature: LgDataFeature() Constructor Done, null
08-17 14:26:54.856  1036  1051 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7446 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-17 14:26:54.868  6948  6948 D HeadsetStateMachine: max_hf_connections = 1
08-17 14:26:54.868  6948  6948 I bluedroid-qcom: get_profile_interface handsfree
08-17 14:26:54.870  6948  7420 E BluetoothAdapterService: File transfer profiles supported!!
08-17 14:26:54.870  6948  6948 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-17 14:26:54.871   335  2182 V AudioPolicyService: registerClient() client 0xb1008620, uid 1002
08-17 14:26:54.872   335  1371 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-17 14:26:54.872   335  1371 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-17 14:26:54.872   335  1371 V AudioPolicyManagerEx: getOutput() returns output 2
08-17 14:26:54.872  6948  6948 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-17 14:26:54.873  1036  1098 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 14:26:54.873  1036  1098 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 14:26:54.874   335  2176 V AudioFlinger: registerClient() client 0xb5581b08, pid 6948
08-17 14:26:54.874   335  1367 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-17 14:26:54.874   335  1367 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-17 14:26:54.875  6948  6948 V ToneGenerator: Create Track: 0xb4928080
08-17 14:26:54.875  6948  6948 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-17 14:26:54.875  6948  6948 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-17 14:26:54.875   335  1366 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-17 14:26:54.875  1590  2094 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-17 14:26:54.875  1590  2094 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-17 14:26:54.875   335  1366 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-17 14:26:54.875   335   335 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-17 14:26:54.875   335   335 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-17 14:26:54.875   335   335 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-17 14:26:54.875   335   335 V AudioPolicyManagerEx: getOutput() returns output 2
08-17 14:26:54.875  6948  6948 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
,08-17 14:26:54.876  1036  1875 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
,08-17 14:26:54.876   335  2176 I AudioFlinger: isAudioPlaybackHookOn() false
08-17 14:26:54.876  1036  1875 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-17 14:26:54.877  1036  1875 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-17 14:26:54.877  1036  1875 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-17 14:26:54.877  1839  2630 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-17 14:26:54.877  1839  2630 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-17 14:26:54.877  1839  2630 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
,08-17 14:26:54.877  1839  2630 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-17 14:26:54.877  3400  3419 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-17 14:26:54.877  3400  3419 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-17 14:26:54.878  3400  3419 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-17 14:26:54.878  3400  3419 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-17 14:26:54.878  1590  1606 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-17 14:26:54.878  1590  1606 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-17 14:26:54.878  6948  6965 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-17 14:26:54.878  6948  6965 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-17 14:26:54.878   335  1372 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-17 14:26:54.878   335  1372 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-17 14:26:54.878  6948  6965 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-17 14:26:54.878   335  1372 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-17 14:26:54.878   335  1372 V AudioPolicyManagerEx: getOutput() returns output 2
08-17 14:26:54.878  6948  6965 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-17 14:26:54.878  6948  6948 V AudioSystem: getLatency() output 2, latency 50
08-17 14:26:54.878  6948  6948 V AudioSystem: getFrameCount() output 2, frameCount 960
08-17 14:26:54.878  6948  6948 V AudioTrack: createTrack_l() output 2 afLatency 50
08-17 14:26:54.879   335   335 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-17 14:26:54.879   335   335 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-17 14:26:54.879   335   335 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-17 14:26:54.879   335   335 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-17 14:26:54.879   335   335 V AudioFlinger: createTrack() lSessionId: 22
08-17 14:26:54.880  6948  6948 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-17 14:26:54.880   335   335 V AudioFlinger: acquiring 22 from 6948, for 6948
08-17 14:26:54.880   335   335 V AudioFlinger:  added new entry for 22
08-17 14:26:54.881  6948  6948 V ToneGenerator: ToneGenerator INIT OK, time: 336644
08-17 14:26:54.881  6948  6948 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c6b2b14
08-17 14:26:54.882  6948  7443 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-17 14:26:54.882  6948  7443 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-17 14:26:54.882  6948  7443 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-17 14:26:54.882  6948  7443 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-17 14:26:54.883   335  1371 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6948
08-17 14:26:54.883   335  1371 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-17 14:26:54.883   335  1371 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-17 14:26:54.883   335  1371 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-17 14:26:54.883   335  1371 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-17 14:26:54.883   335  1371 V voice   : voice_set_parameters: exit with code(0),
08-17 14:26:54.883   335  1371 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
,08-17 14:26:54.883   335  1371 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-17 14:26:54.883   335  1371 V msm8974_platform: platform_set_parameters: exit with code(0)
08-17 14:26:54.883   335  1371 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-17 14:26:54.883   335  1371 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-17 14:26:54.883   335  1371 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-17 14:26:54.883  6948  6948 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c6b2b14
08-17 14:26:54.883  6948  7443 V ToneGenerator: ToneGenerator destructor
08-17 14:26:54.884  6948  7443 V ToneGenerator: stopTone
08-17 14:26:54.884  6948  7443 V ToneGenerator: Delete Track: 0xb4928080
08-17 14:26:54.884  6948  7443 V AudioTrack: ~AudioTrack, releasing session id from 6948 on behalf of 6948
08-17 14:26:54.884   335  2182 V AudioFlinger: releasing 22 from 6948 for 6948
08-17 14:26:54.884   335  2182 V AudioFlinger:  decremented refcount to 0
08-17 14:26:54.884   335  2182 V AudioFlinger: purging stale effects
08-17 14:26:54.885   335  2182 V AudioPolicyService: AudioCommandThread() adding release output 2
08-17 14:26:54.885   335  2182 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-17 14:26:54.885   335  2182 V AudioFlinger: PlaybackThread::Track destructor
08-17 14:26:54.885   335  1126 V AudioPolicyService: AudioCommandThread() waking up
08-17 14:26:54.885   335  2182 V AudioFlinger: removeClient_l() pid 6948, calling pid 335
08-17 14:26:54.885   335  1126 V AudioPolicyService: AudioCommandThread() processing release output 2
08-17 14:26:54.885   335  1126 V AudioPolicyManager: releaseOutput() 2
08-17 14:26:54.885   335  1126 V AudioPolicyService: AudioCommandThread() going to sleep
08-17 14:26:54.885  6948  7420 E BluetoothAdapterService: File transfer profiles supported!!
08-17 14:26:54.886  6948  6948 D A2dpService: Received start request. Starting profile...
08-17 14:26:54.886  1036  1640 W Process : Unable to open /proc/7461/status
08-17 14:26:54.887  6948  6948 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-17 14:26:54.889  6948  6948 V Avrcp   : make
,08-17 14:26:54.889  6948  6948 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-17 14:26:54.889  6948  6948 I bluedroid-qcom: get_profile_interface avrcp
08-17 14:26:54.900  6948  6948 V AudioManager: registerRemoteController: size of Media player list: 0
08-17 14:26:54.903  6948  6948 E AudioManager: No RCC entry present to update
08-17 14:26:54.903  6948  6948 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-17 14:26:54.904  2162  2162 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-17 14:26:54.906  6948  6948 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-17 14:26:54.907  6948  6948 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-17 14:26:54.908  6948  6948 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-17 14:26:54.911  6948  7420 V LGMDMManager: Create singleton instance
08-17 14:26:54.912  6948  6948 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-17 14:26:54.915  6948  7420 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-17 14:26:54.962  7008  7008 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-17 14:26:54.962  7008  7008 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,08-17 14:26:54.964  7008  7008 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-17 14:26:54.964  7008  7008 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-17 14:26:54.965  7008  7008 I AppUp4:CustModeStarterReceiver: onReceive
08-17 14:26:54.968  7008  7008 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@3f8bc126
08-17 14:26:54.968  7008  7008 D AppUp4:CustFacade: isCustomizationCompleted : false
08-17 14:26:54.968  7008  7008 D AppUp4:CustFacade: isPhone : true
08-17 14:26:54.969  7008  7008 D AppUp4:CustModeStarterReceiver: begin check event
08-17 14:26:54.969  7008  7008 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-17 14:26:54.972  4312  4312 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-17 14:26:54.972  4312  4312 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-17 14:26:54.973  4312  4312 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-17 14:26:54.976  4312  4312 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-17 14:26:54.981  4312  7466 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-17 14:26:54.985  7048  7048 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-17 14:26:54.994  4312  7467 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-17 14:26:54.994  4312  7467 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-17 14:26:55.001  7048  7468 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-17 14:26:55.006  3400  3400 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-17 14:26:55.006  3400  3400 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-17 14:26:55.006  3400  3400 I LgeMiscReceiver: networkInfo.isConnected() = false
08-17 14:26:55.009  7083  7083 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-17 14:26:55.009  7083  7083 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-17 14:26:55.010  1036  2001 V SIM_STK : Menu title from STK is T-Mobile
08-17 14:26:55.010  1036  2001 V SIM_STK : Menu title from STK is T-Mobile
08-17 14:26:55.016  6925  7471 W FormManager: Network not available. Please check & try again.
,08-17 14:26:55.020  7446  7446 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-17 14:26:55.020  7446  7446 W LG Account v2.2: No ProfileInfo entries
08-17 14:26:55.020  7446  7446 I LG Account v2.2: isEnabled: false
08-17 14:26:55.020  7446  7446 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-17 14:26:55.020  7446  7446 I Feature : [Lifetracker]Country: EU
08-17 14:26:55.020  7446  7446 I Feature : [Lifetracker]Operator: OPEN
08-17 14:26:55.020  7446  7446 I Feature : [Lifetracker]Ranking support: false
08-17 14:26:55.020  7446  7446 I Feature : [Lifetracker]Comfort support: false
08-17 14:26:55.020  7446  7446 I Feature : [Lifetracker]Accessory: true
08-17 14:26:55.020  7446  7446 I Feature : [Lifetracker]Health device: true
08-17 14:26:55.020  7446  7446 I Feature : [Lifetracker]Extra Pedometer: false
08-17 14:26:55.020  7446  7446 I Feature : [Lifetracker]Blood glucose device: false
08-17 14:26:55.020  7446  7446 I Feature : [Lifetracker]Device Number: 3
08-17 14:26:55.024  7139  7139 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:26:55
08-17 14:26:55.027  7139  7139 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-17 14:26:55.027  7139  7139 D Weather.Utils: 2 : All the weather widget is gone.
08-17 14:26:55.028  7139  7139 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-17 14:26:55.028  7139  7139 D WeatherAncestor: connectivity changed - connection : true
08-17 14:26:55.028  7139  7139 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3c6b2b14
08-17 14:26:55.028  7139  7139 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-17 14:26:55.028  6925  7472 V FormManager: Network unavailable.
08-17 14:26:55.028  7139  7139 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-17 14:26:55.028  7139  7139 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-17 14:26:55.029  7139  7139 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-17 14:26:55.029  7139  7139 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:26:55
,08-17 14:26:55.031  6837  6837 D BluetoothPermissionRequest: onReceive
08-17 14:26:55.034  6925  7472 V FormManager: Network unavailable.
08-17 14:26:55.036  6837  6837 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-17 14:26:55.051  6461  6461 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-17 14:26:55.052  6461  6856 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-17 14:26:55.060  1036  2000 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-17 14:26:55.064  2162  2162 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-17 14:26:55.067  6948  6948 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-17 14:26:55.069  7008  7008 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-17 14:26:55.069  7008  7008 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-17 14:26:55.069  6948  6948 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-17 14:26:55.070  7008  7008 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
,08-17 14:26:55.070  7008  7008 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-17 14:26:55.070  6948  6948 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-17 14:26:55.070  6948  6948 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-17 14:26:55.070  6948  6948 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-17 14:26:55.070  6948  6948 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-17 14:26:55.070  6948  6948 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-17 14:26:55.070  6948  6948 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-17 14:26:55.070  6948  6948 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-17 14:26:55.070  6948  6948 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-17 14:26:55.070  6948  6948 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-17 14:26:55.070  7008  7008 I AppUp4:CustModeStarterReceiver: onReceive
08-17 14:26:55.071  6948  6948 I BluetoothA2dpServiceJni: classInitNative
08-17 14:26:55.071  6948  6948 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-17 14:26:55.071  6948  6948 D A2dpStateMachine: make
08-17 14:26:55.072  6948  6948 I bluedroid-qcom: get_profile_interface a2dp
08-17 14:26:55.072  6948  7476 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-17 14:26:55.073  7008  7008 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@3f8bc126
08-17 14:26:55.073  7008  7008 D AppUp4:CustFacade: isCustomizationCompleted : false
08-17 14:26:55.073  7008  7008 D AppUp4:CustFacade: isPhone : true
08-17 14:26:55.073  7008  7008 D AppUp4:CustModeStarterReceiver: begin check event
08-17 14:26:55.073  7008  7008 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-17 14:26:55.073  6948  6948 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-17 14:26:55.073  6948  6948 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-17 14:26:55.074  6948  6948 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c6b2b14
08-17 14:26:55.074  6948  6948 I BluetoothHidServiceJni: classInitNative: succeeds
08-17 14:26:55.075  6948  7475 D A2dpStateMachine: Enter Disconnected: -2
,08-17 14:26:55.076  6948  6948 D HidService: Received start request. Starting profile...
08-17 14:26:55.076  6948  6948 I bluedroid-qcom: get_profile_interface hidhost
08-17 14:26:55.076  6948  6948 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c6b2b14
08-17 14:26:55.077  6948  6948 I BluetoothHealthServiceJni: classInitNative: succeeds
08-17 14:26:55.077  6948  6948 D HealthService: Received start request. Starting profile...
08-17 14:26:55.078  4312  4312 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-17 14:26:55.078  4312  4312 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-17 14:26:55.079  4312  4312 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-17 14:26:55.079  6948  6948 I bluedroid-qcom: get_profile_interface health
08-17 14:26:55.079  6948  6948 I LGBluetoothHealthServiceJni: classInitNative: succeeds
,08-17 14:26:55.079  6948  6948 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c6b2b14
08-17 14:26:55.079  6948  6948 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-17 14:26:55.080  4312  4312 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-17 14:26:55.080  6948  6948 D PanService: Received start request. Starting profile...
08-17 14:26:55.081  6948  6948 D BluetoothPanServiceJni: initializeNative(L110): pan
08-17 14:26:55.081  6948  6948 I bluedroid-qcom: get_profile_interface pan
08-17 14:26:55.084  7048  7048 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-17 14:26:55.085  4312  7480 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-17 14:26:55.086  6948  6948 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-17 14:26:55.086  6948  6948 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c6b2b14
08-17 14:26:55.086  6948  6948 D HeadsetStateMachine: Proxy object connected
08-17 14:26:55.087  6948  6948 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-17 14:26:55.087  6948  6948 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-17 14:26:55.087  4312  7482 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-17 14:26:55.087  4312  7482 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-17 14:26:55.089  6948  6948 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-17 14:26:55.092  6948  6948 D BtGatt.DebugUtils: handleDebugAction() action=null
08-17 14:26:55.092  6948  6948 D BtGatt.GattService: Received start request. Starting profile...
08-17 14:26:55.092  6948  6948 D BtGatt.GattService: start()
08-17 14:26:55.092  6948  6948 I bluedroid-qcom: get_profile_interface gatt
08-17 14:26:55.092  6948  6948 D BtGatt.AdvertiseManager: advertise manager created
08-17 14:26:55.098  3400  3400 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-17 14:26:55.100  3400  3400 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-17 14:26:55.100  3400  3400 I LgeMiscReceiver: networkInfo.isConnected() = false
08-17 14:26:55.100  6948  6948 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c6b2b14
,08-17 14:26:55.108  7083  7083 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-17 14:26:55.108  7083  7083 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-17 14:26:55.109  6948  6948 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-17 14:26:55.109  6948  7443 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-17 14:26:55.109  6948  6948 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c6b2b14
08-17 14:26:55.110  6948  7443 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-17 14:26:55.110  6948  6948 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
,08-17 14:26:55.110  6948  7443 D HeadsetStateMachine: Disconnected process message: 11, size: 0
,08-17 14:26:55.110  6948  6948 V BluetoothMapService: BluetoothMapBinder()
08-17 14:26:55.111  6948  6948 D BluetoothMapService: Received start request. Starting profile...
08-17 14:26:55.111  6948  6948 D BluetoothMapService: start()
08-17 14:26:55.111  7048  7485 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:26:55.113  6925  7487 W FormManager: Network not available. Please check & try again.
08-17 14:26:55.117  6948  6948 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-17 14:26:55.117  6948  6948 D BluetoothMapEmailAppObserver: createReceiver()
08-17 14:26:55.117  6925  7489 V FormManager: Network unavailable.
08-17 14:26:55.118  6948  6948 D BluetoothMapEmailAppObserver: initObservers()
08-17 14:26:55.118  6948  6948 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-17 14:26:55.123  6948  6948 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c6b2b14
,08-17 14:26:55.124  7139  7139 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:26:55
08-17 14:26:55.125  7139  7139 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-17 14:26:55.125  7139  7139 D Weather.Utils: 2 : All the weather widget is gone.
08-17 14:26:55.126  6925  7489 V FormManager: Network unavailable.
08-17 14:26:55.126  7139  7139 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-17 14:26:55.126  7139  7139 D WeatherAncestor: connectivity changed - connection : true
08-17 14:26:55.126  7139  7139 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3c6b2b14
08-17 14:26:55.126  6948  6948 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-17 14:26:55.127  7139  7139 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
,08-17 14:26:55.127  7139  7139 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-17 14:26:55.127  7139  7139 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-17 14:26:55.127  7139  7139 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-17 14:26:55.127  7139  7139 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:26:55
08-17 14:26:55.129  6948  6948 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-17 14:26:55.131  6948  6948 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-17 14:26:55.132  6948  6948 V PanService: [BTUI] SIM Extra State :ABSENT
08-17 14:26:55.134  6948  6948 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-17 14:26:55.136  6948  6948 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-17 14:26:55.136  6948  6948 V BluetoothMapService: Handler(): got msg=1
08-17 14:26:55.137  6948  7420 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-17 14:26:55.137  6948  7420 I bluedroid-qcom: enable
08-17 14:26:55.137  6948  7420 I bt_hci_bdroid: init
,08-17 14:26:55.138  6948  7490 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-17 14:26:55.139  6948  7420 I bt_vendor: bt-vendor : init
08-17 14:26:55.139  6948  7420 I bt_vendor: bt-vendor : get_bt_soc_type
08-17 14:26:55.139  6948  7420 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-17 14:26:55.139  6948  7420 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-17 14:26:55.139  6948  7420 D bt_userial_mct: userial_init
08-17 14:26:55.139  6948  7490 I bt-btu  : btu_task pending for preload complete event
08-17 14:26:55.139  6948  7420 D bt_hci_bdroid: set_power 1
08-17 14:26:55.139  6948  7420 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-17 14:26:55.139  6948  7420 I bt_vendor: Starting hciattach daemon
08-17 14:26:55.139  6948  7420 I bt_vendor: try to set true
08-17 14:26:55.139  6948  6948 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:26:55.127  7493  7493 W sh      : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 14:26:55.127  7493  7493 W sh      : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 14:26:55.143  6948  6948 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-17 14:26:55.143  6948  6948 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-17 14:26:55.143  6948  6948 V BluetoothSapReceiver: SapReceiver onReceive 
08-17 14:26:55.143  6948  6948 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:26:55.143  6948  6948 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-17 14:26:55.155  7494  7494 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-17 14:26:55.201  7500  7500 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-17 14:26:55.212  7501  7501 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-17 14:26:55.234  7503  7503 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-17 14:26:55.257  7504  7504 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-17 14:26:55.272  7505  7505 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-17 14:26:55.298  7506  7506 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-17 14:26:55.336  7508  7508 I libmdmdetect: ESOC framework not supported
,08-17 14:26:55.337  7508  7508 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-17 14:26:55.344  7508  7508 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,08-17 14:26:55.344  7508  7508 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-17 14:26:55.344  7508  7508 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-17 14:26:55.344  7508  7508 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
,08-17 14:26:55.344  7508  7508 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-17 14:26:55.344  7508  7508 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-17 14:26:55.344  7508  7508 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-17 14:26:55.378  7508  7509 E QC-QMI  : qmi_client [7508] 14: failed to locate client data
08-17 14:26:55.379   460   460 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-17 14:26:55.379   460   460 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
,08-17 14:26:55.429  7510  7510 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-17 14:26:55.452  7514  7514 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-17 14:26:55.490  6948  7420 I bt_vendor: bluetooth satus is on
08-17 14:26:55.490  6948  7420 D bt_hci_bdroid: preload
,08-17 14:26:55.493  6948  7492 D bt_userial_mct: userial_open(port:0)
08-17 14:26:55.493  6948  7492 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-17 14:26:55.496  6948  7492 I bt_vendor: Done intiailizing UART
08-17 14:26:55.497  6948  7492 I bt_vendor: Done intiailizing UART
08-17 14:26:55.497  6948  7492 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-17 14:26:55.497  6948  7492 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-17 14:26:55.498  6948  7490 I bt-btu  : btu_task received preload complete event
08-17 14:26:55.498  6948  7519 D bt_userial_mct: Entering userial_read_thread()
08-17 14:26:55.498  6948  7490 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-17 14:26:55.498  6948  7490 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-17 14:26:55.500  6948  7490 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-17 14:26:55.503  6948  7490 I         : BTE_InitTraceLevels -- TRC_HCI
08-17 14:26:55.504  6948  7490 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-17 14:26:55.504  6948  7490 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-17 14:26:55.504  6948  7490 I         : BTE_InitTraceLevels -- TRC_AVDT
08-17 14:26:55.504  6948  7490 I         : BTE_InitTraceLevels -- TRC_AVRC
08-17 14:26:55.504  6948  7490 I         : BTE_InitTraceLevels -- TRC_A2D
08-17 14:26:55.504  6948  7490 I         : BTE_InitTraceLevels -- TRC_BNEP
08-17 14:26:55.504  6948  7490 I         : BTE_InitTraceLevels -- TRC_BTM
08-17 14:26:55.504  6948  7490 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-17 14:26:55.504  6948  7490 I         : BTE_InitTraceLevels -- TRC_GAP
08-17 14:26:55.504  6948  7490 I         : BTE_InitTraceLevels -- TRC_PAN
08-17 14:26:55.504  6948  7490 I         : BTE_InitTraceLevels -- TRC_SDP
08-17 14:26:55.504  6948  7490 I         : BTE_InitTraceLevels -- TRC_GATT
08-17 14:26:55.504  6948  7490 I         : BTE_InitTraceLevels -- TRC_SMP
08-17 14:26:55.504  6948  7490 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-17 14:26:55.504  6948  7490 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-17 14:26:55.558  6948  7490 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-17 14:26:55.558  6948  7490 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa016c061 
08-17 14:26:55.558  6948  7490 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa016c061 
,08-17 14:26:55.579  6948  7424 E bt-btif : Calling BTA_HhEnable
08-17 14:26:55.579  6948  7490 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-17 14:26:55.579  6948  7490 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-17 14:26:55.579  6948  7490 W bt-l2cap: btif_storage_get_adapter_property service_mask
08-17 14:26:55.579  6948  7424 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-17 14:26:55.580  6948  7490 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-17 14:26:55.580  6948  7490 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-17 14:26:55.580  6948  7424 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-17 14:26:55.583  6948  7424 D BluetoothAdapterProperties: Name is: G3
08-17 14:26:55.583  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-17 14:26:55.584  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
08-17 14:26:55.585  6948  7424 D BluetoothAdapterProperties: Scan Mode:20
08-17 14:26:55.586  6948  7424 D BluetoothAdapterProperties: Discoverable Timeout:120
08-17 14:26:55.587  6948  7424 D bt_hci_bdroid: postload
08-17 14:26:55.587  6948  7492 D bt_hci_bdroid: Used up Tx Cmd credits
08-17 14:26:55.588  6948  7490 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-17 14:26:55.589  6948  7424 D bte_conf: Device ID record 1 : primary
,08-17 14:26:55.589  6948  7424 D bte_conf:   vendorId            = 00c4
08-17 14:26:55.589  6948  7424 D bte_conf:   vendorIdSource      = 0001
08-17 14:26:55.589  6948  7424 D bte_conf:   product             = 13a1
08-17 14:26:55.589  6948  7424 D bte_conf:   version             = 1000
08-17 14:26:55.589  6948  7424 D bte_conf:   clientExecutableURL = 
08-17 14:26:55.589  6948  7424 D bte_conf:   serviceDescription  = 
08-17 14:26:55.589  6948  7424 D bte_conf:   documentationURL    = 
08-17 14:26:55.589  6948  7424 D bte_conf: bte_load_did_conf no section named DID2.
08-17 14:26:55.590  6725  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:26:55.591  6948  7490 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-17 14:26:55.591  6948  7490 W bt-smp  : Plain text(LSB ~ MSB) = eb a5 5c 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-17 14:26:55.591  6948  7490 W bt-smp  : Encrypted text(LSB ~ MSB) = 15 37 9d dc fe e9 21 8c 54 04 96 af 44 82 09 09 
08-17 14:26:55.592  6948  7490 W bt-btm  : Stopping oneshot timer
08-17 14:26:55.592  6948  7492 D bt_hci_bdroid: Used up Tx Cmd credits
08-17 14:26:55.594  6948  7492 D bt_hci_bdroid: Used up Tx Cmd credits
08-17 14:26:55.595  6948  7492 D bt_hci_bdroid: Used up Tx Cmd credits
08-17 14:26:55.597  6948  7492 D bt_hci_bdroid: Used up Tx Cmd credits
,08-17 14:26:55.587  7521  7521 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 14:26:55.587  7521  7521 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 14:26:55.603  6948  7519 E bt_mct  : hci lib postload completed
08-17 14:26:55.603  6725  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:26:55.606  6948  7420 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-17 14:26:55.607  6948  7420 D BluetoothAdapterProperties: ScanMode =  20
08-17 14:26:55.607  6948  7420 D BluetoothAdapterProperties: State =  11
08-17 14:26:55.607  6948  7420 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-17 14:26:55.607  6948  7420 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-17 14:26:55.608  6948  7420 D BluetoothAdapterProperties: Setting state to 12
,08-17 14:26:55.608  6948  7420 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-17 14:26:55.608  1036  1103 D BluetoothManagerService: Message: 60
08-17 14:26:55.608  1036  1103 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-17 14:26:55.608  1036  1103 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
08-17 14:26:55.609  6948  7424 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-17 14:26:55.609  6948  7424 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-17 14:26:55.612  6948  7420 I BluetoothAdapterState: Entering On State
08-17 14:26:55.615  6948  7420 D LGBluetoothServiceAdapter: [BTUI] OnState
08-17 14:26:55.615  6948  7420 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-17 14:26:55.615  6948  7420 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-17 14:26:55.619  6948  7420 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-17 14:26:55.625  6948  7424 D BluetoothAdapterProperties: Discoverable Timeout:120
08-17 14:26:55.625  6948  7424 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
,08-17 14:26:55.630  6948  7490 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-17 14:26:55.630  6948  7490 W bt-smp  : Plain text(LSB ~ MSB) = fb 4f 59 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-17 14:26:55.630  6948  7490 W bt-smp  : Encrypted text(LSB ~ MSB) = f5 0f a3 ad 74 d4 ec 97 89 5c d6 1b d1 7f b9 2f 
08-17 14:26:55.630  6948  7490 W bt-btm  : Stopping oneshot timer
08-17 14:26:55.632  6837  6853 D BluetoothPbap: onBluetoothStateChange: up=true
08-17 14:26:55.637  1839  1855 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 14:26:55.641  1839  1839 D BluetoothHeadset: Proxy object connected
,08-17 14:26:55.644  1839  2630 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 14:26:55.646  6948  7490 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-17 14:26:55.646  6948  7490 W bt-smp  : Plain text(LSB ~ MSB) = 79 22 4b 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-17 14:26:55.646  6948  7490 W bt-smp  : Encrypted text(LSB ~ MSB) = 24 ea b3 05 1c 23 14 aa 1e 04 74 e5 ed 8e d7 78 
08-17 14:26:55.646  6948  7490 W bt-btm  : Stopping oneshot timer
08-17 14:26:55.649  1839  1839 D BluetoothHeadset: Proxy object connected
08-17 14:26:55.650  6837  6852 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-17 14:26:55.654  6837  6853 D BluetoothPan: onBluetoothStateChange on: true
08-17 14:26:55.654  6837  6853 D BluetoothPan: onBluetoothStateChange call bindService
,08-17 14:26:55.658  6948  7490 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-17 14:26:55.658  6948  7490 W bt-smp  : Plain text(LSB ~ MSB) = c5 d5 75 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-17 14:26:55.658  6948  7490 W bt-smp  : Encrypted text(LSB ~ MSB) = df e0 20 ce 8c ba 07 4f 42 c8 46 a8 7f c3 d7 87 
08-17 14:26:55.658  6948  7490 W bt-btm  : Stopping oneshot timer
08-17 14:26:55.663  6948  7420 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-17 14:26:55.663  1036  1103 D BluetoothA2dp: onBluetoothStateChange: up=true
08-17 14:26:55.666  1036  1036 D BluetoothA2dp: Proxy object connected
,08-17 14:26:55.670  1839  1854 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 14:26:55.673  6948  7490 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-17 14:26:55.673  6948  7490 W bt-smp  : Plain text(LSB ~ MSB) = c1 9a 6c 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-17 14:26:55.673  6948  7490 W bt-smp  : Encrypted text(LSB ~ MSB) = c7 83 5f cb 2f 01 4c 48 c7 fc 05 da 4e c7 72 0d 
08-17 14:26:55.673  6948  7490 W bt-btm  : Stopping oneshot timer
08-17 14:26:55.674  1839  1839 D BluetoothHeadset: Proxy object connected
08-17 14:26:55.675  6837  6852 D BluetoothMap: onBluetoothStateChange: up=true
08-17 14:26:55.679  1036  1103 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-17 14:26:55.680  7527  7527 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-17 14:26:55.682  1036  1036 D BluetoothHeadset: Proxy object connected
08-17 14:26:55.687  1036  1103 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-17 14:26:55.687  1036  1103 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-17 14:26:55.688  6837  6837 D BluetoothInputDevice: Proxy object connected
08-17 14:26:55.688  6837  6837 D HidProfile: Bluetooth service connected
08-17 14:26:55.690  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-17 14:26:55.690  1036  1103 D BluetoothManagerService: Message: 40
08-17 14:26:55.690  1036  1103 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-17 14:26:55.691  6837  6837 D BluetoothPan: BluetoothPAN Proxy object connected
08-17 14:26:55.691  6837  6837 D PanProfile: Bluetooth service connected
,08-17 14:26:55.693  6837  6837 D BluetoothMap: Proxy object connected
08-17 14:26:55.693  6837  6837 D MapProfile: Bluetooth service connected
08-17 14:26:55.693  6837  6837 D BluetoothMap: getConnectedDevices()
08-17 14:26:55.695  6948  6965 V BluetoothMapService: getConnectedDevices()
08-17 14:26:55.717  1036  1099 W ProcessCpuTracker: Skipping unknown process pid 7521
,08-17 14:26:55.719  1929  1929 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:26:55.719  1929  2116 D LGBluetoothAPIService: Message: 1
08-17 14:26:55.719  1929  2116 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-17 14:26:55.722  1590  1590 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-17 14:26:55.727  6725  6725 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
08-17 14:26:55.734  1929  2116 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
,08-17 14:26:55.738  6948  6948 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:26:55.738  6948  6948 D BluetoothMapService: STATE_ON
08-17 14:26:55.739  6725  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 14:26:55.739  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:26:55.739  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 14:26:55.739  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 14:26:55.739  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 14:26:55.739  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 14:26:55.739  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 14:26:55.739  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 14:26:55.739  6837  6837 D LocalBluetoothProfileManager: Adding local A2DP profile
08-17 14:26:55.740  6948  6948 D LGBluetoothAPIServer: [BTUI] onCreate()
08-17 14:26:55.740  6948  6948 D LGBluetoothAPIServer: [BTUI] onBind()
08-17 14:26:55.742  6725  6725 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 14:26:55.744  1929  1929 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-17 14:26:55.744  1929  2116 D LGBluetoothAPIService: Message: 100
08-17 14:26:55.744  1929  2116 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-17 14:26:55.748  6725  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 14:26:55.748  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:26:55.748  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 14:26:55.748  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 14:26:55.748  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 14:26:55.748  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 14:26:55.748  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 14:26:55.748  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 14:26:55.749  1036  1103 D BluetoothManagerService: Message: 30
,08-17 14:26:55.751  6725  6725 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 14:26:55.754  6837  6837 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-17 14:26:55.755  6948  6948 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c6b2b14
08-17 14:26:55.755  6948  6948 V BluetoothPbapService: Pbap Service onCreate
08-17 14:26:55.755  6948  6948 V BluetoothPbapService: Starting PBAP service
08-17 14:26:55.757  6948  6948 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-17 14:26:55.757  1036  1103 D BluetoothManagerService: Message: 30
08-17 14:26:55.757  6948  6948 V BluetoothPbapService: Pbap Service onBind
08-17 14:26:55.758  6948  6948 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:26:55.758  6948  6948 V BluetoothPbapService: state: 12
08-17 14:26:55.758  6948  6948 V BluetoothMapService: Handler(): got msg=1
08-17 14:26:55.758  6948  6948 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-17 14:26:55.759  6948  6948 V BluetoothPbapService: Handler(): got msg=1
08-17 14:26:55.760  6948  6948 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-17 14:26:55.760  6948  7541 D BluetoothMapMasInstance: MAS initSocket()
08-17 14:26:55.761  6948  7541 D BluetoothMapMasInstance:   masId = 00
08-17 14:26:55.761  6948  7541 D BluetoothMapMasInstance:   msgTypes = 0e
08-17 14:26:55.761  6948  7541 D BluetoothMapMasInstance:   masName = SMS/MMS
08-17 14:26:55.761  6948  7541 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-17 14:26:55.762  1036  2001 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 14:26:55.762  6837  6837 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-17 14:26:55.763  6948  7541 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 14:26:55.763  6948  7542 V BluetoothPbapService: Pbap Service initSocket
,08-17 14:26:55.764  1036  1964 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 14:26:55.765  6948  7542 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 14:26:55.766  6948  7541 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-17 14:26:55.766  6948  7424 D BluetoothAdapterProperties: Scan Mode:21
08-17 14:26:55.766  6837  6837 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-17 14:26:55.766  6948  7541 V BluetoothMapMasInstance: Succeed to create listening socket 
08-17 14:26:55.767  6948  7424 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-17 14:26:55.767  6948  7542 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-17 14:26:55.767  6948  7542 V BluetoothPbapService: Succeed to create listening socket 
08-17 14:26:55.767  6948  7542 V BluetoothPbapService: Accepting socket connection...
08-17 14:26:55.768  6725  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:26:55.769  6725  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:26:55.770  6837  6837 D BluetoothA2dp: Proxy object connected
08-17 14:26:55.770  6837  6837 D A2dpProfile: Bluetooth service connected
08-17 14:26:55.771  6948  7541 D BluetoothMapMasInstance: Accepting socket connection...
08-17 14:26:55.773  6948  6948 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-17 14:26:55.773  6948  6948 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:26:55.773  6948  6948 V BluetoothPbapReceiver: ***********state = 12
08-17 14:26:55.774  6837  6837 D BluetoothPbap: Proxy object connected
08-17 14:26:55.775  6837  6837 D PbapServerProfile: Bluetooth service connected
08-17 14:26:55.775  6837  6837 D BluetoothHeadset: Proxy object connected
08-17 14:26:55.776  2162  2162 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-17 14:26:55.776  6837  6837 D HeadsetProfile: Bluetooth service connected
08-17 14:26:55.776  2162  2162 D c       : Getting all permits...
08-17 14:26:55.776  2162  2162 D a       : Opening database...
,08-17 14:26:55.780  2162  2162 D a       : Opening database auth.proximity.permit_store...
08-17 14:26:55.781  2162  2162 D a       : Closing database...
08-17 14:26:55.781  6837  6837 D DockEventReceiver: finishStartingService: stopping service
08-17 14:26:55.792  6837  6837 D BluetoothPermissionRequest: onReceive
,08-17 14:26:55.793  6837  6837 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-17 14:26:55.795  6837  6837 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-17 14:26:55.797  6948  6948 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-17 14:26:55.799  6948  6948 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-17 14:26:55.804  6948  6948 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-17 14:26:55.828  6948  6948 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-17 14:26:55.829  6948  6948 V BtOppService: onCreate
,08-17 14:26:55.834  6948  6948 V BluetoothOppNotification: send message
08-17 14:26:55.838  6948  6948 V BtOppService: Starting RfcommListener
08-17 14:26:55.838  7166  7201 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
08-17 14:26:55.846  6948  6948 D BluetoothOppPreference: Dumping Names:  
,08-17 14:26:55.846  6948  6948 D BluetoothOppPreference: {}
08-17 14:26:55.846  6948  6948 D BluetoothOppPreference: Dumping Channels:  
08-17 14:26:55.846  6948  6948 D BluetoothOppPreference: {}
08-17 14:26:55.847  6948  6948 V BtOppService: onStartCommand
08-17 14:26:55.851  6948  6948 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:26:55.851  6948  7551 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-17 14:26:55.851  6948  6948 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-17 14:26:55.853  6948  6948 V BluetoothOppNotification: new notify threadi!
08-17 14:26:55.854  6948  6948 V BluetoothOppNotification: send delay message
08-17 14:26:55.855  6948  6948 V BtOppService: start RfcommListener
08-17 14:26:55.857  6948  7551 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-17 14:26:55.857  6948  7552 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-17 14:26:55.858  6948  6948 V BtOppService: RfcommListener started
08-17 14:26:55.859  6948  7553 V BtOppRfcommListener: Starting RFCOMM listener....
08-17 14:26:55.860  1036  2036 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-17 14:26:55.860  6948  7547 V BtOppService: Deleted complete outbound shares, number =  0
08-17 14:26:55.861  6948  7551 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@281c4b09 on behalf of 
,08-17 14:26:55.861  6948  7553 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 14:26:55.862  6948  7553 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
08-17 14:26:55.862  6948  7553 V BtOppRfcommListener: Started RFCOMM listener....
08-17 14:26:55.862  6948  7553 I BtOppRfcommListener: Accept thread started.
08-17 14:26:55.862  6948  7553 V BtOppRfcommListener: Accepting connection...
,08-17 14:26:55.868  6948  7552 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@4dee10e on behalf of 
08-17 14:26:55.872  6948  7551 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-17 14:26:55.872  6948  7547 V BtOppService: Deleted complete inbound failed shares, number = 0
08-17 14:26:55.873  6948  7552 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-17 14:26:55.873  6948  7547 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-17 14:26:55.874  6948  7552 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-17 14:26:55.876  6948  7552 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1a4c472f on behalf of 
08-17 14:26:55.876  6948  7547 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2d84d13c on behalf of 
,08-17 14:26:55.882  6948  6948 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c6b2b14
08-17 14:26:55.882  6948  6948 V BluetoothFtpService: Ftp Service onCreate
08-17 14:26:55.883  6948  6948 I BluetoothFtpService: Ftp Service onCreate
08-17 14:26:55.883  6948  6948 V BluetoothFtpService: Ftp Service onStartCommand
,08-17 14:26:55.883  6948  6948 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:26:55.883  6948  6948 V BluetoothFtpService: Starting Listening on sockets
08-17 14:26:55.883  6948  6948 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-17 14:26:55.883  6948  6948 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-17 14:26:55.883  6948  6948 V BluetoothSapReceiver: SapReceiver onReceive 
08-17 14:26:55.883  6948  6948 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:26:55.884  6948  6948 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-17 14:26:55.884  6948  6948 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-17 14:26:55.886  6948  7552 V BluetoothOppNotification: outbound: succ-0  fail-0
08-17 14:26:55.887  6948  6948 V BtOppService: ContentObserver received notification
08-17 14:26:55.888  6948  6948 V BtOppService: ContentObserver received notification
08-17 14:26:55.888  6948  6948 V BluetoothFtpService: Handler(): got msg=1
08-17 14:26:55.888  6948  7552 V BluetoothOppNotification: outbound notification was removed.
08-17 14:26:55.888  6948  7552 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-17 14:26:55.889  6948  6948 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-17 14:26:55.889  6948  6948 V BluetoothFtpService: Ftp Service initSocket
08-17 14:26:55.889  6948  7552 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@52c001a on behalf of 
08-17 14:26:55.890  6948  7552 V BluetoothOppNotification: inbound: succ-0  fail-0
08-17 14:26:55.891  6948  7552 V BluetoothOppNotification: inbound notification was removed.
08-17 14:26:55.892  6948  7552 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-17 14:26:55.892  6948  7554 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-17 14:26:55.893  6948  7552 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@9e0274b on behalf of 
08-17 14:26:55.893  6948  7554 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
,08-17 14:26:55.897  6948  7554 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2f6bc528 on behalf of 
,08-17 14:26:55.898  6948  7554 V BluetoothOppNotification: update too frequent, put in queue
08-17 14:26:55.899  6948  7554 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-17 14:26:55.899  1036  1964 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 14:26:55.901  6948  6948 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 14:26:55.902  6948  6948 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=79
08-17 14:26:55.902  6948  6948 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-17 14:26:55.904  6948  7555 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
,08-17 14:26:55.930  6948  6948 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c6b2b14
,08-17 14:26:55.930  6948  6948 V BluetoothSapService: Sap Service onCreate
08-17 14:26:55.932  6948  6948 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:26:55.932  6948  6948 V BluetoothSapService: state: 12
08-17 14:26:55.932  6948  6948 V BluetoothSapService: Starting SAP server process
08-17 14:26:55.934  6948  6948 V BluetoothSapService: SAP Service startRfcommListenerThread
08-17 14:26:55.917  7556  7556 W sapd    : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 14:26:55.917  7556  7556 W sapd    : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 14:26:55.937  6948  7557 V BluetoothSapService: Sap Service initRfcommSocket
08-17 14:26:55.938  1036  1875 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 14:26:55.940  6948  7557 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 14:26:55.942  6948  7557 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
,08-17 14:26:55.943  6948  7557 V BluetoothSapService: Succeed to create listening socket 
,08-17 14:26:55.943  6948  7557 V BluetoothSapService: Accepting socket connection...
,08-17 14:26:55.948  7556  7556 V BT_SAP  : Event pipe created
08-17 14:26:55.948  7556  7556 V BT_SAP  : create_server_socket qcom.sap.server
08-17 14:26:55.948  7556  7556 V BT_SAP  : created socket fd 6
08-17 14:26:56.624  1036  1522 D LGWifiP2pService: P2pDisabledState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:26:56.624  1036  1522 D LGWifiP2pService: DefaultState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-17 14:26:56.667  1036  1523 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-17 14:26:56.669  1036  1523 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-17 14:26:56.842  1036  1560 I ActivityManager: Killing 7339:com.lge.bnr/1000 (adj 15): empty #17
,08-17 14:26:56.856  6948  6948 V BluetoothOppNotification: new notify threadi!
08-17 14:26:56.856  6948  6948 V BluetoothOppNotification: send delay message
08-17 14:26:56.860  6948  7567 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-17 14:26:56.918  1036  1875 W libprocessgroup: failed to open /acct/uid_1000/pid_7339/cgroup.procs: No such file or directory
,08-17 14:26:57.039  1036  1909 I art     : Explicit concurrent mark sweep GC freed 93472(4MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 2.951ms total 159.428ms
,08-17 14:26:57.046  6948  7567 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@24c0bd4 on behalf of 
08-17 14:26:57.046  6948  7567 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-17 14:26:57.054  1036  1928 I ActivityManager: Killing 6663:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,08-17 14:26:57.062  6948  7567 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-17 14:26:57.069  6887  6887 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-17 14:26:57.069  6887  6887 W System.err: android.os.DeadObjectException
08-17 14:26:57.069  6887  6887 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-17 14:26:57.069  6887  6887 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-17 14:26:57.069  6887  6887 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-17 14:26:57.069  6887  6887 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-17 14:26:57.069  6887  6887 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-17 14:26:57.069  6887  6887 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-17 14:26:57.069  6887  6887 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-17 14:26:57.069  6887  6887 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-17 14:26:57.069  6887  6887 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-17 14:26:57.069  6887  6887 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-17 14:26:57.069  6887  6887 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 14:26:57.069  6887  6887 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 14:26:57.069  6887  6887 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-17 14:26:57.069  6887  6887 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-17 14:26:57.070  6887  6887 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
,08-17 14:26:57.073  6887  6887 W System.err: android.os.DeadObjectException
08-17 14:26:57.073  6887  6887 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-17 14:26:57.073  6887  6887 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-17 14:26:57.073  6887  6887 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-17 14:26:57.073  6887  6887 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-17 14:26:57.073  6887  6887 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-17 14:26:57.073  6887  6887 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-17 14:26:57.073  6887  6887 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-17 14:26:57.073  6887  6887 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-17 14:26:57.073  6887  6887 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-17 14:26:57.073  6887  6887 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-17 14:26:57.073  6887  6887 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 14:26:57.073  6887  6887 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 14:26:57.074  6887  6887 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-17 14:26:57.074  6887  6887 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-17 14:26:57.074  6887  6887 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-17 14:26:57.074  6887  6887 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-17 14:26:57.074  6948  7567 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1ff3d17d on behalf of 
08-17 14:26:57.075  6948  7567 V BluetoothOppNotification: outbound: succ-0  fail-0
,08-17 14:26:57.087  6948  7567 V BluetoothOppNotification: outbound notification was removed.
08-17 14:26:57.087  6948  7567 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-17 14:26:57.089  6948  7567 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@28527872 on behalf of 
08-17 14:26:57.091  6948  7567 V BluetoothOppNotification: inbound: succ-0  fail-0
08-17 14:26:57.097  6948  7567 V BluetoothOppNotification: inbound notification was removed.
08-17 14:26:57.097  6948  7567 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-17 14:26:57.098  6948  7567 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@25fc34c3 on behalf of 
,08-17 14:26:57.116  1036  1874 W libprocessgroup: failed to open /acct/uid_1000/pid_6663/cgroup.procs: No such file or directory
08-17 14:26:57.117  1036  1874 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
08-17 14:26:57.119  6887  6887 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-17 14:26:57.119  6887  6887 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,08-17 14:26:57.171  1036  2001 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7574 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-17 14:26:57.173  6887  6887 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-17 14:26:57.242  7574  7574 D UEI.SmartControl: Quickset Services start...
,08-17 14:26:57.244  7574  7574 I UEI.SmartControl: Manufacture = LGE
08-17 14:26:57.244  7574  7574 D UEI.SmartControl: Id = LGNevo
08-17 14:26:57.245  7574  7574 D UEI.SmartControl: File observer start...
08-17 14:26:57.246  7574  7574 E UEI.SmartControl: IR Port is disabled: false
,08-17 14:26:57.247  7574  7574 D UEI.SmartControl: Starting file observer...
08-17 14:26:57.248  7574  7574 D UEI.SmartControl: Extracting JNI libs...
08-17 14:26:57.248  7574  7574 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-17 14:26:57.343  7574  7574 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-17 14:26:57.344  7574  7574 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-17 14:26:57.344  7574  7574 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-17 14:26:57.382  7574  7574 I UEI.SmartControl: --- Selecting new region: 6
,08-17 14:26:57.385  7574  7574 I UEI.SmartControl: Model = LG-D855
,08-17 14:26:57.387  7574  7574 D UEI.SmartControl: QS Service created
08-17 14:26:57.402  7574  7574 I UEI.SmartControl: Service initServices...
,08-17 14:26:57.406  7574  7574 D UEI.SmartControl: QS start get config
08-17 14:26:57.447  7574  7574 D UEI.SmartControl: Loading JNI Libs...
,08-17 14:26:57.608  1036  2000 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 14:26:57.608  1036  2000 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@9ecb79e mBinding = false
,08-17 14:26:57.630  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-17 14:26:57.631  1036  1103 D BluetoothManagerService: Message: 2
08-17 14:26:57.632  1036  1103 D BluetoothManagerService: Sending off request.
08-17 14:26:57.631  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-17 14:26:57.633  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-17 14:26:57.634  6948  7435 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-17 14:26:57.635  6948  7420 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-17 14:26:57.635  6948  7420 D BluetoothAdapterProperties: Setting state to 13
08-17 14:26:57.635  6948  7420 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-17 14:26:57.636  6948  7420 D BluetoothAdapterProperties: onBluetoothDisable()
08-17 14:26:57.636  6948  7420 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-17 14:26:57.638  6948  7424 D BluetoothAdapterProperties: Scan Mode:20
08-17 14:26:57.639  6948  7420 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,08-17 14:26:57.640  6948  7420 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-17 14:26:57.640  6948  7542 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-17 14:26:57.640  6948  7490 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-17 14:26:57.645  6948  7557 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-17 14:26:57.645  6948  7555 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-17 14:26:57.647  6948  7541 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-17 14:26:57.647  6948  7541 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-17 14:26:57.647  6948  7541 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-17 14:26:57.647  6948  7541 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-17 14:26:57.647  6948  7541 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-17 14:26:57.647  6948  7541 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-17 14:26:57.647  6948  7541 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-17 14:26:57.647  6948  7541 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-17 14:26:57.647  1036  1103 D BluetoothManagerService: Message: 60
08-17 14:26:57.647  1036  1103 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-17 14:26:57.647  1036  1103 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-17 14:26:57.647  6948  7553 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-17 14:26:57.647  6948  7490 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-17 14:26:57.649  1590  1590 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-17 14:26:57.652  1929  1929 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:26:57.656  6948  7490 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-17 14:26:57.656  6948  7490 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-17 14:26:57.656  6948  7490 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-17 14:26:57.656  6948  7490 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-17 14:26:57.656  6948  7490 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 14:26:57.656  6948  7490 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-17 14:26:57.656  6948  7490 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 14:26:57.656  6948  7490 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-17 14:26:57.656  6948  7490 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-17 14:26:57.657  6837  6837 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
,08-17 14:26:57.659  6948  6948 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:26:57.659  6948  6948 D BluetoothMapService: STATE_TURNING_OFF
08-17 14:26:57.659  6948  7490 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-17 14:26:57.659  6948  7490 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
,08-17 14:26:57.659  6948  6948 V BluetoothMapService: Handler(): got msg=4
08-17 14:26:57.659  6948  7490 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-17 14:26:57.659  6948  6948 D BluetoothMapService: MAP Service closeService in
08-17 14:26:57.659  6948  6948 D BluetoothMapMasInstance: MAP Service shutdown
08-17 14:26:57.659  6948  6948 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-17 14:26:57.660  6948  6948 V BluetoothMapService: MAP Service closeService out
08-17 14:26:57.660  6725  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:26:57.660  6725  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 14:26:57.660  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:26:57.660  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 14:26:57.660  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 14:26:57.660  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 14:26:57.660  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 14:26:57.660  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 14:26:57.660  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 14:26:57.660  6837  6837 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-17 14:26:57.661  6948  6948 V BtOppService: Receiver DISABLED_ACTION 
08-17 14:26:57.661  6948  6948 I BtOppRfcommListener: stopping Accept Thread
08-17 14:26:57.661  6948  6948 V BtOppRfcommListener: close mBtServerSocket
08-17 14:26:57.661  6725  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:26:57.661  6948  6948 V BtOppRfcommListener: waiting for thread to terminate
08-17 14:26:57.662  6725  6725 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 14:26:57.662  6948  7553 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-17 14:26:57.663  6948  6948 V BtOppRfcommListener: done waiting for thread to terminate
08-17 14:26:57.664  6725  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:26:57.664  6725  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 14:26:57.664  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:26:57.664  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 14:26:57.664  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 14:26:57.664  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 14:26:57.664  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 14:26:57.664  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 14:26:57.664  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 14:26:57.664  6948  6948 V BtOppServi,ce: onDestroy
08-17 14:26:57.665  6725  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:26:57.665  6725  6725 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 14:26:57.666  6725  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:26:57.667  6725  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:26:57.669  6948  6948 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-17 14:26:57.669  6948  6948 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-17 14:26:57.669  6948  6948 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:26:57.669  6948  6948 V BluetoothPbapReceiver: ***********state = 13
08-17 14:26:57.670  6837  6837 D DockEventReceiver: finishStartingService: stopping service
08-17 14:26:57.671  6948  6948 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-17 14:26:57.672  6948  6948 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:26:57.672  6948  6948 V BluetoothPbapService: state: 13
08-17 14:26:57.672  6948  6948 V BluetoothPbapService: Pbap Service closeService in
08-17 14:26:57.676  6837  6837 D BluetoothPbap: Proxy object disconnected
08-17 14:26:57.676  6837  6837 D PbapServerProfile: Bluetooth service disconnected
08-17 14:26:57.676  6948  6948 V BluetoothPbapService: successfully stopped pbap service
08-17 14:26:57.676  6948  6948 V BluetoothPbapService: Pbap Service closeService out
08-17 14:26:57.676  6948  6948 V BluetoothPbapService: Pbap Service onDestroy
08-17 14:26:57.676  6948  6948 V BluetoothPbapService: Pbap Service closeService in
08-17 14:26:57.676  6948  6948 V BluetoothPbapService: Pbap Service closeService out
08-17 14:26:57.676  6948  6948 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-17 14:26:57.678  2162  2162 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-17 14:26:57.684  6837  6837 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-17 14:26:57.687  6837  6837 D BluetoothPermissionRequest: onReceive
08-17 14:26:57.687  6837  6837 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-17 14:26:57.696  6837  6837 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-17 14:26:57.698  6948  6948 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-17 14:26:57.698  6948  6948 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,08-17 14:26:57.699  6948  6948 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-17 14:26:57.702  6948  6948 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:26:57.703  6948  6948 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-17 14:26:57.704  6948  6948 V BluetoothFtpService: Ftp Service onStartCommand
08-17 14:26:57.704  6948  6948 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:26:57.704  6948  6948 V BluetoothFtpService: Ftp Service closeService
08-17 14:26:57.704  6948  6948 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-17 14:26:57.705  6948  6948 V BluetoothFtpService: successfully stopped ftp service
08-17 14:26:57.705  6948  6948 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-17 14:26:57.705  6948  6948 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-17 14:26:57.705  6948  6948 V BluetoothSapReceiver: SapReceiver onReceive 
08-17 14:26:57.705  6948  6948 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:26:57.705  6948  6948 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-17 14:26:57.705  6948  6948 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-17 14:26:57.706  6948  6948 V BluetoothFtpService: Ftp Service onDestroy
08-17 14:26:57.706  6948  6948 V BluetoothFtpService: Ftp Service closeService
08-17 14:26:57.710  6948  6948 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:26:57.710  6948  6948 V BluetoothSapService: state: 13
08-17 14:26:57.710  6948  6948 V BluetoothSapService: Stopping SAP server process
,08-17 14:26:57.711  6948  6948 V BluetoothSapService: Sap Service closeSapService in
08-17 14:26:57.711  6948  6948 V BluetoothSapService: Close listen Socket : 
08-17 14:26:57.711  6948  6948 V BluetoothSapService: Close rfcomm Socket : 
08-17 14:26:57.711  6948  6948 V BluetoothSapService: Close sapd  Socket : 
08-17 14:26:57.715  6948  6948 V BluetoothSapService: Sap Service closeSapService out
08-17 14:26:57.715  6948  6948 V BluetoothSapService: Sap Service onDestroy
08-17 14:26:57.715  6948  6948 V BluetoothSapService: Sap Service closeSapService in
08-17 14:26:57.715  6948  6948 V BluetoothSapService: Close listen Socket : 
08-17 14:26:57.715  6948  6948 V BluetoothSapService: Close rfcomm Socket : 
08-17 14:26:57.715  6948  6948 V BluetoothSapService: Close sapd  Socket : 
08-17 14:26:57.715  6948  6948 V BluetoothSapService: Sap Service closeSapService out
08-17 14:26:57.738  7574  7574 I UEI.SmartControl: Supports setup maps: true
,08-17 14:26:57.743  7574  7574 D UEI.SmartControl: QS start statue = true Error code = 0
08-17 14:26:57.743  7574  7574 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-17 14:26:57.743  7574  7574 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-17 14:26:57.743  7574  7574 I UEI.SmartControl: ### init IR Blaster...
08-17 14:26:57.748  7574  7574 D serial_port: Configuring serial port
08-17 14:26:57.752  7574  7574 E UEI.SmartControl: UEIBLaster setting for 616
08-17 14:26:57.752  7574  7574 I UEI.SmartControl: Setting serial record hearder size = 2
08-17 14:26:57.753  7574  7574 I UEI.SmartControl: configuring settings for MAXQ616
08-17 14:26:57.753  7574  7574 I UEI.SmartControl: Get version...
,08-17 14:26:57.770  7574  7604 D UEI.SmartControl: serial port data available: 21
,08-17 14:26:57.799  7574  7574 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-17 14:26:57.799  7574  7574 I UEI.SmartControl: IR Blaster version: 256702256704300002
,08-17 14:26:57.799  7574  7574 I UEI.SmartControl: QS saving settings...
,08-17 14:26:57.801  7574  7574 D UEI.SmartControl: IR Blaster version: 25672567
08-17 14:26:57.818  7574  7604 D UEI.SmartControl: serial port data available: 4
,08-17 14:26:57.860  7574  7607 I UEI.SmartControl: Device manager: loading config....
,08-17 14:26:57.860  7574  7574 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-17 14:26:57.861  7574  7607 D UEI.SmartControl: ----------- loading internal config...
08-17 14:26:57.864  7574  7574 E UEI.SmartControl: Services init done
08-17 14:26:57.865  7574  7574 D UEI.SmartControl: QS Service init finished
08-17 14:26:57.867  7574  7574 D UEI.SmartControl: QS Service version name: 2.1.91
08-17 14:26:57.867  7574  7574 D UEI.SmartControl: QS Service version code: 201091
08-17 14:26:57.868  7574  7574 D UEI.SmartControl: Service requested: Control
08-17 14:26:57.880  7574  7607 E UEI.SmartControl: Loading SETTINGS...
,08-17 14:26:57.886  7574  7574 D UEI.SmartControl: Request IControl service: devices are loaded...
08-17 14:26:57.886  7574  7607 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-17 14:26:57.889  6887  6887 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-17 14:26:57.889  7574  7590 I UEI.SmartControl: ------ IControl API: 11
08-17 14:26:57.890  7574  7590 I UEI.SmartControl: Registering callback...
08-17 14:26:57.891  7574  7589 I UEI.SmartControl: ------ IControl API: 19
08-17 14:26:57.892  1036  1909 I ActivityManager: Killing 6887:com.lge.qremote/u0a112 (adj 15): empty #17
08-17 14:26:57.892  7574  7589 I UEI.SmartControl: Registering Services Ready callback...
08-17 14:26:57.914  7574  7606 I UEI.SmartControl: Notify AllClients services are ready: 0
,08-17 14:26:57.915  7574  7606 D UEI.SmartControl: -----service ready thread exits
08-17 14:26:57.952  1036  1874 W libprocessgroup: failed to open /acct/uid_10112/pid_6887/cgroup.procs: No such file or directory
08-17 14:26:57.953  7574  7574 D UEI.SmartControl: Internal service binding...
,08-17 14:26:58.566  6948  7424 D bt_hci_bdroid: cleanup
,08-17 14:26:58.573  6948  7519 I bt_userial_mct: exiting userial_read_thread
,08-17 14:26:58.573  6948  7519 D bt_userial_mct: Leaving userial_evt_read_thread()
08-17 14:26:58.574  6948  7492 I bt_lpm  : LPM is already off!!!
08-17 14:26:58.574  6948  7490 W bt-btif : ag scb idx 1 not allocated
08-17 14:26:58.574  6948  7490 E bt-btif : BTA AG is already disabled, ignoring ...
08-17 14:26:58.574  6948  7490 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-17 14:26:58.574  6948  7490 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 14:26:58.575  6948  7490 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-17 14:26:58.575  6948  7490 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 14:26:58.575  6948  7490 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-17 14:26:58.575  6948  7490 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-17 14:26:58.575  6948  7490 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-17 14:26:58.575  6948  7490 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 14:26:58.575  6948  7490 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-17 14:26:58.575  6948  7490 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 14:26:58.575  6948  7490 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-17 14:26:58.575  6948  7490 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-17 14:26:58.575  6948  7490 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
,08-17 14:26:58.575  6948  7490 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 14:26:58.575  6948  7490 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
,08-17 14:26:58.575  6948  7490 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration,
,08-17 14:26:58.575  6948  7490 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-17 14:26:58.575  6948  7490 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-17 14:26:58.578  6948  7424 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-17 14:26:58.579  6948  7492 I bt_vendor: hw_epilog_process
08-17 14:26:58.583  6948  7424 D bt_hci_bdroid: cleanup Finalizing cleanup,
,08-17 14:26:58.583  6948  7424 D bt_userial_mct: userial_close
08-17 14:26:58.583  6948  7424 E bt_userial_mct: pthread_join() FAILED result:3
08-17 14:26:58.583  6948  7424 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-17 14:26:58.576  6948  7490 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-17 14:26:58.606  6948  7424 D bt_hci_bdroid: set_power 0
08-17 14:26:58.606  6948  7424 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-17 14:26:58.606  6948  7424 I bt_vendor: bluetooth satus is on
08-17 14:26:58.606  6948  7424 I bt_vendor: bt-vendor : resetting BT status
08-17 14:26:58.606  6948  7424 I bt_vendor: Starting hciattach daemon
08-17 14:26:58.606  6948  7424 I bt_vendor: try to set false
,08-17 14:26:58.610  6948  7424 I bt_vendor: Starting hciattach daemon
08-17 14:26:58.610  6948  7424 I bt_vendor: try to set false
08-17 14:26:58.611  6948  7424 I bt_vendor: cleanup
08-17 14:26:58.612  6948  7490 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-17 14:26:58.612  6948  7424 I GKI_LINUX: GKI_exit_task 0 done
08-17 14:26:58.612  6948  7424 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-17 14:26:58.614  6948  7420 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-17 14:26:58.618  6948  6948 D HeadsetService: Received stop request...Stopping profile...
,08-17 14:26:58.622  6948  6948 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-17 14:26:58.622  6948  6948 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-17 14:26:58.622  6948  6948 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c6b2b14
08-17 14:26:58.628  6948  7420 D BluetoothAdapterState: Stopping profile services that were post enabled
08-17 14:26:58.629  6948  7443 D HeadsetStateMachine: Exit Disconnected: -1
08-17 14:26:58.630  1036  1036 D BluetoothHeadset: Proxy object disconnected
08-17 14:26:58.630  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-17 14:26:58.632  1839  1839 D BluetoothHeadset: Proxy object disconnected
08-17 14:26:58.632  1839  1839 D BluetoothHeadset: Proxy object disconnected
08-17 14:26:58.633  1839  1839 D BluetoothHeadset: Proxy object disconnected
08-17 14:26:58.634  6948  6948 D A2dpService: Received stop request...Stopping profile...
08-17 14:26:58.636  6948  7475 D A2dpStateMachine: Exit Disconnected: -1
08-17 14:26:58.637  6948  6948 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-17 14:26:58.639  6948  6948 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-17 14:26:58.639  6948  6948 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-17 14:26:58.639  6948  6948 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c6b2b14
08-17 14:26:58.641  6948  6948 D HidService: Received stop request...Stopping profile...
08-17 14:26:58.641  6948  6948 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c6b2b14
08-17 14:26:58.641  1036  1036 D BluetoothA2dp: Proxy object disconnected
08-17 14:26:58.641  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-17 14:26:58.646  6948  6948 D HeadsetStateMachine: Unbinding service...
08-17 14:26:58.649  6948  6948 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-17 14:26:58.649  6948  6948 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-17 14:26:58.649  6948  6948 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-17 14:26:58.649  6948  6948 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-17 14:26:58.649  6948  6948 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-17 14:26:58.649  6948  6948 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-17 14:26:58.649  6948  6948 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-17 14:26:58.650  6948  6948 D HealthService: Received stop request...Stopping profile...
08-17 14:26:58.650  6948  6948 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c6b2b14
08-17 14:26:58.652  6948  6948 D PanService: Received stop request...Stopping profile...
08-17 14:26:58.653  6948  6948 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c6b2b14
08-17 14:26:58.654  6948  6948 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-17 14:26:58.658  6948  6948 D BtGatt.GattService: Received stop request...Stopping profile...
08-17 14:26:58.658  6948  6948 D BtGatt.GattService: stop()
08-17 14:26:58.658  6948  6948 D BtGatt.AdvertiseManager: advertise clients cleared
08-17 14:26:58.660  6948  6948 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c6b2b14
08-17 14:26:58.661  6948  6948 D BluetoothMapService: Received stop request...Stopping profile...
08-17 14:26:58.661  6948  6948 D BluetoothMapService: stop()
08-17 14:26:58.664  6948  6948 D BluetoothMapEmailAppObserver: deinitObservers()
08-17 14:26:58.664  6948  6948 D BluetoothMapEmailAppObserver: removeReceiver()
08-17 14:26:58.665  6948  6948 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c6b2b14
,08-17 14:26:58.669  6948  6948 I BluetoothA2dpServiceJni: cleanupNative
08-17 14:26:58.669  6948  7476 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-17 14:26:58.669  6948  6948 I GKI_LINUX: GKI_exit_task 2 done
08-17 14:26:58.669  6948  6948 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-17 14:26:58.670  6948  6948 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-17 14:26:58.670  6948  6948 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-17 14:26:58.670  6948  6948 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-17 14:26:58.671  6948  6948 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-17 14:26:58.671  6948  6948 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-17 14:26:58.672  6948  6948 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-17 14:26:58.672  6948  6948 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-17 14:26:58.674  6948  6948 V BluetoothMapService: Handler(): got msg=4
08-17 14:26:58.674  6948  6948 D BluetoothMapService: MAP Service closeService in
08-17 14:26:58.675  6948  6948 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-17 14:26:58.675  6948  6948 V BluetoothMapService: MAP Service closeService out
08-17 14:26:58.675  6948  7420 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-17 14:26:58.675  6948  7420 D BluetoothAdapterProperties: Setting state to 10
08-17 14:26:58.675  6948  7420 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-17 14:26:58.676  6948  6948 D BluetoothMapService: cleanup()
08-17 14:26:58.676  6948  6948 D BluetoothMapService: MAP Service closeService in
08-17 14:26:58.676  6948  6948 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-17 14:26:58.676  6948  6948 V BluetoothMapService: MAP Service closeService out
08-17 14:26:58.678  1036  1103 D BluetoothManagerService: Message: 60
08-17 14:26:58.678  1036  1103 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-17 14:26:58.678  1036  1103 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
,08-17 14:26:58.681  6948  7420 I BluetoothAdapterState: Entering OffState
08-17 14:26:58.681  6837  6853 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 14:26:58.682  6837  6853 D BluetoothPbap: onBluetoothStateChange: up=false
08-17 14:26:58.683  1839  2630 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 14:26:58.684  1839  1854 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 14:26:58.685  6837  6853 D BluetoothA2dp: onBluetoothStateChange: up=false
08-17 14:26:58.685  6837  6853 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-17 14:26:58.686  6837  6853 D BluetoothPan: onBluetoothStateChange on: false
08-17 14:26:58.687  1036  1103 D BluetoothA2dp: onBluetoothStateChange: up=false
08-17 14:26:58.687  1839  2394 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 14:26:58.687  6837  6853 D BluetoothMap: onBluetoothStateChange: up=false
08-17 14:26:58.688  1036  1103 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 14:26:58.688  1036  1103 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-17 14:26:58.689  1036  1103 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-17 14:26:58.690  1036  1103 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-17 14:26:58.690  1036  1103 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-17 14:26:58.690  1036  1103 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@9ecb79e mBinding = false
,08-17 14:26:58.693  1036  1103 D BluetoothManagerService: Sending unbind request.
08-17 14:26:58.699  6948  7424 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-17 14:26:58.700  6948  6948 I GKI_LINUX: GKI_exit_task 1 done
08-17 14:26:58.700  6948  6948 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-17 14:26:58.700  6948  6948 I BluetoothServiceJni: cleanupNative: return from cleanup
08-17 14:26:58.700  6948  6948 I art     : --- WEIRD: removing null entry 248
08-17 14:26:58.700  6948  6948 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-17 14:26:58.700  6948  6948 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-17 14:26:58.701  6948  6948 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-17 14:26:58.703  1036  1103 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
,08-17 14:26:58.707  6948  6948 I art     : System.exit called, status: 0
08-17 14:26:58.707  6948  6948 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-17 14:26:58.728   335  1371 V AudioFlinger: 6948 died, releasing its sessions
08-17 14:26:58.728   335  1371 V AudioFlinger:  pid 1839 @ 0
08-17 14:26:58.728   335  1371 V AudioFlinger:  pid 3400 @ 1
08-17 14:26:58.728   335  1371 V AudioFlinger:  pid 3400 @ 2
,08-17 14:26:58.731  1929  1929 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
08-17 14:26:58.731  1929  2116 D LGBluetoothAPIService: Message: 101
08-17 14:26:58.732  1929  2116 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
08-17 14:26:58.732  1929  2116 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
08-17 14:26:58.732  1929  2116 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
08-17 14:26:58.733  6837  6837 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-17 14:26:58.736  1036  1946 I ActivityManager: Process com.android.bluetooth (pid 6948) has died
08-17 14:26:58.736  1036  1946 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 1000ms
08-17 14:26:58.736  1036  1946 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 11000ms
08-17 14:26:58.742  1929  1929 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-17 14:26:58.745  1590  1590 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-17 14:26:58.746  1929  2116 D LGBluetoothAPIService: Message: 2
08-17 14:26:58.746  1929  2116 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
08-17 14:26:58.747  6725  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:26:58.747  6725  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:26:58.753  6837  6837 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-17 14:26:58.754  6837  6837 D LGBluetoothEventManager: [BTUI] clear device connection state
08-17 14:26:58.763  1590  1590 D BluetoothAdapter: 1063439583: getState() :  mService = null. Returning STATE_OFF
08-17 14:26:58.763  1590  1590 D BluetoothAdapter: 1063439583: getState() :  mService = null. Returning STATE_OFF
,08-17 14:26:58.765  6837  6837 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-17 14:26:58.819  1036  2001 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7639 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-17 14:26:58.821  6837  6837 D DockEventReceiver: finishStartingService: stopping service
,08-17 14:26:58.874  7639  7639 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-17 14:26:58.875  7639  7639 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-17 14:26:58.875  7639  7639 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-17 14:26:58.876  7639  7639 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-17 14:26:58.893  7639  7639 D BluetoothAdapterApp: Loading JNI Library
,08-17 14:26:58.918  7639  7639 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@1a94487c Instance Count = 1
,08-17 14:26:58.923  7639  7639 D BluetoothAdapterApp: onCreate
08-17 14:26:58.941  7639  7639 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-17 14:26:58.941  7639  7639 D ProfileConfigQcom: Adding HeadsetService
08-17 14:26:58.941  7639  7639 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-17 14:26:58.941  7639  7639 D ProfileConfigQcom: Adding A2dpService
08-17 14:26:58.941  7639  7639 D ProfileConfigQcom: [BTUI] HidService is supported
,08-17 14:26:58.941  7639  7639 D ProfileConfigQcom: Adding HidService
08-17 14:26:58.942  7639  7639 D ProfileConfigQcom: [BTUI] HealthService is supported
08-17 14:26:58.942  7639  7639 D ProfileConfigQcom: Adding HealthService
08-17 14:26:58.942  7639  7639 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-17 14:26:58.943  7639  7639 D ProfileConfigQcom: [BTUI] PanService is supported
08-17 14:26:58.943  7639  7639 D ProfileConfigQcom: Adding PanService
08-17 14:26:58.943  7639  7639 D ProfileConfigQcom: [BTUI] GattService is supported
08-17 14:26:58.944  7639  7639 D ProfileConfigQcom: Adding GattService
08-17 14:26:58.944  7639  7639 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-17 14:26:58.944  7639  7639 D ProfileConfigQcom: Adding BluetoothMapService
08-17 14:26:58.944  7639  7639 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-17 14:26:58.945  7639  7639 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-17 14:26:58.946  7639  7639 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,08-17 14:26:58.947  7639  7639 V BluetoothPbapReceiver: ***********state = 10
,08-17 14:26:58.953  7639  7639 V LGMDMManagerInternal: Create singleton instance
08-17 14:26:59.052  7639  7639 D LGBluetoothAPIServer: [BTUI] onCreate()
08-17 14:26:59.052  7639  7639 D LGBluetoothAPIServer: [BTUI] onBind()
08-17 14:26:59.054  2162  2162 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-17 14:26:59.057  1929  1929 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-17 14:26:59.058  1929  2116 D LGBluetoothAPIService: Message: 100
08-17 14:26:59.058  1929  2116 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-17 14:26:59.067  6837  6837 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,08-17 14:26:59.079  6837  6837 D BluetoothPermissionRequest: onReceive
,08-17 14:26:59.081  6837  6837 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-17 14:26:59.081  6837  6837 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-17 14:26:59.083  6837  6837 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-17 14:26:59.090  7639  7639 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-17 14:26:59.099  7639  7639 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-17 14:26:59.105  7639  7639 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-17 14:26:59.106  7639  7639 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-17 14:26:59.106  7639  7639 V BluetoothSapReceiver: SapReceiver onReceive 
08-17 14:26:59.111  7639  7639 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:26:59.111  7639  7639 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-17 14:26:59.115  6904  6904 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-17 14:27:00.000  1036  1365 D PowerManagerServiceEx: acquireWakeLockInternal: lock=822491364, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
,08-17 14:27:00.049  1590  1590 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-17 14:27:00.049  1590  1590 I KeyguardUpdateMonitor: called onTimeUpdated()
08-17 14:27:00.049  1590  1590 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-17 14:27:00.049  1590  1590 I [SystemUI]Clock: called onTimeUpdated()
,08-17 14:27:00.058  1036  1099 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7667 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
08-17 14:27:00.060  1590  1590 I LgeClockWidgetControlView: called onTimeUpdated()
08-17 14:27:00.060  1590  1590 I [SystemUI]DateView: called onTimeUpdated()
08-17 14:27:00.061  1590  1590 I [SystemUI]DateView: called onTimeUpdated()
08-17 14:27:00.061  1590  1590 D KeyguardUpdateMonitor: handleTimeUpdate
08-17 14:27:00.092  2601  2601 D [Concierge]Service: onStartCommand(). Type : 9
,08-17 14:27:00.172  7667  7667 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-17 14:27:00.196  7667  7667 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-17 14:27:00.231  7667  7667 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-17 14:27:00.232  7667  7667 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-17 14:27:00.232  7667  7667 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-17 14:27:00.232  7667  7667 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-17 14:27:00.233  7667  7667 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-17 14:27:00.234  7667  7667 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,08-17 14:27:00.240  7667  7667 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-17 14:27:00.247  7667  7667 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
,08-17 14:27:00.247  7667  7667 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:6240
08-17 14:27:00.248  1036  1036 D PowerManagerServiceEx: releaseWakeLockInternal: lock=822491364 [*alarm*], flags=0x0
08-17 14:27:00.251  7667  7667 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
,08-17 14:27:00.255  7667  7667 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
,08-17 14:27:00.255  7667  7667 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-17 14:27:00.256  7667  7667 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,08-17 14:27:00.257  7667  7667 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-17 14:27:00.287  7667  7667 D LgDataFeature: LgDataFeature() Constructor: none
08-17 14:27:00.287  7667  7667 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-17 14:27:00.294  7667  7667 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-17 14:27:00.295  7667  7667 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-17 14:27:00.295  7667  7667 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-17 14:27:00.295  7667  7667 V SoundPool: doLoad: loading sample sampleID=1
08-17 14:27:00.295  7667  7667 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-17 14:27:00.298  7667  7667 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-17 14:27:00.299  7667  7667 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-17 14:27:00.299  7667  7667 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-17 14:27:00.300  7667  7704 V SoundPool: Start decode
,08-17 14:27:00.300  7667  7704 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-17 14:27:00.305   335  2176 V MediaPlayerService: decode(23, 10857164, 17813)
08-17 14:27:00.305   335  2176 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-17 14:27:00.305   335  2176 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-17 14:27:00.305   335  2176 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-17 14:27:00.305   335  2176 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-17 14:27:00.305   335  2176 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-17 14:27:00.305   335  2176 V MediaPlayerService: player type = 3
08-17 14:27:00.306   335  2176 V AwesomePlayer: AwesomePlayer create()
08-17 14:27:00.306   335  2176 V AwesomePlayer: reset_l() 
08-17 14:27:00.306   335  2176 V AwesomePlayer: cancelPlayerEvents
08-17 14:27:00.306   335  2176 V AwesomePlayer: setAudioSink() 
08-17 14:27:00.306   335  2176 V AwesomePlayer: reset_l() 
08-17 14:27:00.306   335  2176 V AudioCache: notify(0xb1009080, 8, 0, 0)
08-17 14:27:00.306   335  2176 V AudioCache: ignored
08-17 14:27:00.306   335  2176 V AwesomePlayer: cancelPlayerEvents
08-17 14:27:00.306   335  2176 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-17 14:27:00.306   335  2176 V AwesomePlayer: setDataSource_l dataSource
08-17 14:27:00.306   335  2176 V LGParserOSAL: SniffLGParser start
08-17 14:27:00.306   335  2176 V LGParserOSAL: MainType:5, SubType=0
08-17 14:27:00.306   335  2176 V LGParserOSAL: #### check Mime : application/ogg
08-17 14:27:00.306   335  2176 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-17 14:27:00.306   335  2176 E MediaExtractor: Use LGExtractor :application/ogg 
08-17 14:27:00.319  7667  7667 V LGMDMManager: Create singleton instance
,08-17 14:27:00.362  7667  7667 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,08-17 14:27:00.363   335  2176 V LGParserOSAL: supported mime: application/ogg
08-17 14:27:00.363   335  2176 V AwesomePlayer: setDataSource_l() extractor countTracks=1
,08-17 14:27:00.363   335  2176 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-17 14:27:00.363   335  2176 V AwesomePlayer: mBitrate = -1 bits/sec
08-17 14:27:00.364   335  2176 V AwesomePlayer: AudioTrack Setting
08-17 14:27:00.364   335  2176 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-17 14:27:00.364   335  2176 V AwesomePlayer: setAudioSource() 
08-17 14:27:00.364   335  2176 V MediaPlayerService: prepare
,08-17 14:27:00.364   335  2176 V AwesomePlayer: prepareAsync_l() 
08-17 14:27:00.364   335  2176 V MediaPlayerService: wait for prepare
08-17 14:27:00.364  7667  7667 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-17 14:27:00.365   335  7705 V AwesomePlayer: onPrepareAsyncEvent() 
08-17 14:27:00.365   335  7705 V AwesomePlayer: initAudioDecoder() 
08-17 14:27:00.366   335  7705 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-17 14:27:00.366   335  7705 V AudioSystem: isOffloadSupported()
08-17 14:27:00.366   335  7705 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-17 14:27:00.366   335  7705 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
,08-17 14:27:00.366   335  7705 I AudioFlinger: isAudioPlaybackHookOn() false
08-17 14:27:00.366   335  7705 V AwesomePlayer: getUseOffload() = 0 
08-17 14:27:00.366   335  7705 V OMXCodec: OMXCodec::Create
08-17 14:27:00.366   335  7705 V OMXCodec: findMatchingCodecs()
08-17 14:27:00.367  7667  7667 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:6245
08-17 14:27:00.367   335  7705 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-17 14:27:00.368   335  7705 V OMXCodec: matchingCodecs.size()=1
08-17 14:27:00.368   335  7705 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-17 14:27:00.370  7667  7667 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-17 14:27:00.371  7574  7589 I UEI.SmartControl: ------ IControl API: 11
08-17 14:27:00.371  7574  7589 I UEI.SmartControl: Registering callback...
08-17 14:27:00.371  7574  7609 I UEI.SmartControl: ------ IControl API: 19
08-17 14:27:00.371  7574  7609 I UEI.SmartControl: Registering Services Ready callback...
,08-17 14:27:00.371  7574  7609 I UEI.SmartControl: Notify client services are ready...
08-17 14:27:00.372  7667  7682 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-17 14:27:00.373  7667  7702 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-17 14:27:00.374  7667  7702 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-17 14:27:00.374  7667  7667 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
,08-17 14:27:00.374  7667  7667 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-17 14:27:00.374  7574  7590 I UEI.SmartControl: ------ IControl API: 8
08-17 14:27:00.376  7667  7667 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-17 14:27:00.376  7667  7667 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-17 14:27:00.376  7667  7667 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-17 14:27:00.377   335  7705 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-17 14:27:00.377  7667  7667 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-17 14:27:00.377   335  7705 V LGCodecAdapter: LG Codec Adapter start
08-17 14:27:00.377   335  7705 V OMXCodec: OMXCodec Createtor
08-17 14:27:00.377   335  7705 V OMXCodec: setComponentRole
08-17 14:27:00.377   335  7705 V OMXCodec: configureCodec protected=0
08-17 14:27:00.377   335  7705 V LGCodecAdapter: called getLGCodecSpecificData
08-17 14:27:00.377   335  7705 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
,08-17 14:27:00.377   335  7705 V LGCodecOSAL: Called LGconfigureCodecMETA
08-17 14:27:00.377   335  7705 V LGCodecOSAL: Called LGconfigureCodecMSG
08-17 14:27:00.377   335  7705 V LGCodecOSAL: Not support LGCodec
08-17 14:27:00.377   335  7705 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-17 14:27:00.377   335  7705 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
,08-17 14:27:00.377   335  7705 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-17 14:27:00.378   335  7705 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-17 14:27:00.378   335  7705 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-17 14:27:00.378   335  7705 V AudioSystem: isOffloadSupported()
08-17 14:27:00.378   335  7705 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-17 14:27:00.378   335  7705 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-17 14:27:00.378   335  7705 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-17 14:27:00.378   335  7705 V OMXCodec: init()
08-17 14:27:00.378   335  7705 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
,08-17 14:27:00.378   335  7705 V OMXCodec: allocateBuffers
08-17 14:27:00.378   335  7705 V OMXCodec: allocateBuffersOnPort portIndex=0
08-17 14:27:00.378   335  7705 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-17 14:27:00.378  7667  7667 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-17 14:27:00.379   335  7705 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on input port
08-17 14:27:00.379   335  7705 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on input port
08-17 14:27:00.379   335  7705 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on input port
08-17 14:27:00.379   335  7705 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on input port
08-17 14:27:00.379   335  7705 V OMXCodec: allocateBuffersOnPort portIndex=1
08-17 14:27:00.379   335  7705 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-17 14:27:00.379  7667  7667 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-17 14:27:00.379   335  7705 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d30 on output port
08-17 14:27:00.379   335  7705 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7e70 on output port
08-17 14:27:00.379   335  7705 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7fb0 on output port
08-17 14:27:00.379   335  7705 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57bc060 on output port
08-17 14:27:00.379   335  7705 V OMXCodec: init() mAsyncCompletion wait!!! 
08-17 14:27:00.379   335  7707 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-17 14:27:00.379   335  7707 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-17 14:27:00.380   335  7707 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-17 14:27:00.380   335  7705 V OMXCodec: init() mAsyncCompletion wait!!! 
08-17 14:27:00.380   335  7707 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-17 14:27:00.380   335  7707 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-17 14:27:00.380   335  7707 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-17 14:27:00.380   335  7705 V OMXCodec: init() mAsyncCompletion wait free! 
08-17 14:27:00.380   335  7705 V AwesomePlayer: finishAsyncPrepare_l() 
08-17 14:27:00.380   335  7705 V AudioCache: notify(0xb1009080, 5, 0, 0)
08-17 14:27:00.380   335  7705 V AudioCache: ignored
08-17 14:27:00.380   335  7705 V AudioCache: notify(0xb1009080, 1, 0, 0)
08-17 14:27:00.380   335  7705 V AudioCache: prepared
,08-17 14:27:00.381   335  2176 V AudioCache: wait - success
08-17 14:27:00.381   335  2176 V MediaPlayerService: start
,08-17 14:27:00.381   335  2176 V AwesomePlayer: play_l() 
08-17 14:27:00.381   335  2176 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-17 14:27:00.381   335  2176 V AwesomePlayer: createAudioPlayer_l
08-17 14:27:00.381   335  2176 V AwesomePlayer: seekAudioIfNecessary_l() 
08-17 14:27:00.381   335  2176 V AwesomePlayer: startAudioPlayer_l() 
,08-17 14:27:00.381   335  2176 D AudioPlayer: start of Playback, useOffload 0
08-17 14:27:00.381   335  2176 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-17 14:27:00.382   335  2176 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-17 14:27:00.383   335  7707 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-17 14:27:00.384   335  7707 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-17 14:27:00.384   335  7707 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-17 14:27:00.384   335  7707 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-17 14:27:00.384   335  7707 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-17 14:27:00.384   335  7707 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-17 14:27:00.384  7667  7667 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-17 14:27:00.384   335  7707 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885488
,08-17 14:27:00.384   335  7707 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-17 14:27:00.384   335  7707 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885808
08-17 14:27:00.384   335  7707 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-17 14:27:00.384   335  7707 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041886128
08-17 14:27:00.384   335  7707 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-17 14:27:00.386   335  7707 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044786272
08-17 14:27:00.386   335  7707 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-17 14:27:00.386  7667  7667 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-17 14:27:00.386   335  7707 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-17 14:27:00.386   335  7707 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-17 14:27:00.386   335  7707 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
,08-17 14:27:00.386   335  7707 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-17 14:27:00.386   335  7707 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-17 14:27:00.386   335  7707 V OMXCodec: allocateBuffersOnPort portIndex=1
08-17 14:27:00.386   335  7707 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-17 14:27:00.386  7667  7667 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-17 14:27:00.386   335  7707 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7fb0 on output port
08-17 14:27:00.386   335  7707 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7e70 on output port
08-17 14:27:00.386   335  7707 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d30 on output port
08-17 14:27:00.386   335  7707 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb000f1f0 on output port
08-17 14:27:00.386   335  7707 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-17 14:27:00.386   335  7707 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
,08-17 14:27:00.387  7667  7667 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-17 14:27:00.387   335  2176 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-17 14:27:00.387   335  2176 V AudioCache: notify(0xb1009080, 6, 0, 0)
08-17 14:27:00.387   335  2176 V AudioCache: ignored
08-17 14:27:00.387   335  2176 V MediaPlayerService: wait for playback complete
08-17 14:27:00.388  7667  7667 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-17 14:27:00.388   335  7708 V AudioCache: write(0xb16ba000, 4096)
08-17 14:27:00.388   335  7708 V AudioCache: memcpy(0xac1f9000, 0xb16ba000, 4096)
08-17 14:27:00.388  7667  7667 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-17 14:27:00.389  7667  7667 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-17 14:27:00.389  7667  7667 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-17 14:27:00.390  7667  7667 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1471436820390]
,08-17 14:27:00.391   335  7708 V AudioCache: write(0xb16ba000, 4096)
08-17 14:27:00.391   335  7708 V AudioCache: memcpy(0xac1fa000, 0xb16ba000, 4096)
08-17 14:27:00.391   335  7708 V AudioCache: write(0xb16ba000, 4096)
08-17 14:27:00.391   335  7708 V AudioCache: memcpy(0xac1fb000, 0xb16ba000, 4096)
08-17 14:27:00.392  7667  7667 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-17 14:27:00.392   335  7708 V AudioCache: write(0xb16ba000, 4096)
08-17 14:27:00.392   335  7708 V AudioCache: memcpy(0xac1fc000, 0xb16ba000, 4096)
08-17 14:27:00.392  1036  2036 I ActivityManager: Killing 6858:com.lge.sync/1000 (adj 15): empty #17
08-17 14:27:00.393   335  7708 V AudioCache: write(0xb16ba000, 4096)
08-17 14:27:00.393   335  7708 V AudioCache: memcpy(0xac1fd000, 0xb16ba000, 4096)
08-17 14:27:00.393   335  7708 V AudioCache: write(0xb16ba000, 4096)
,08-17 14:27:00.393   335  7708 V AudioCache: memcpy(0xac1fe000, 0xb16ba000, 4096)
08-17 14:27:00.394   335  7708 V AudioCache: write(0xb16ba000, 4096)
08-17 14:27:00.394   335  7708 V AudioCache: memcpy(0xac1ff000, 0xb16ba000, 4096)
08-17 14:27:00.395   335  7708 V AudioCache: write(0xb16ba000, 4096)
08-17 14:27:00.395   335  7708 V AudioCache: memcpy(0xac200000, 0xb16ba000, 4096)
08-17 14:27:00.395   335  7708 V AudioCache: write(0xb16ba000, 4096)
08-17 14:27:00.395   335  7708 V AudioCache: memcpy(0xac201000, 0xb16ba000, 4096)
08-17 14:27:00.396   335  7708 V AudioCache: write(0xb16ba000, 4096)
08-17 14:27:00.396   335  7708 V AudioCache: memcpy(0xac202000, 0xb16ba000, 4096)
08-17 14:27:00.397   335  7708 V AudioCache: write(0xb16ba000, 4096)
08-17 14:27:00.397   335  7708 V AudioCache: memcpy(0xac203000, 0xb16ba000, 4096)
08-17 14:27:00.397   335  7708 V AudioCache: write(0xb16ba000, 4096)
08-17 14:27:00.397   335  7708 V AudioCache: memcpy(0xac204000, 0xb16ba000, 4096)
,08-17 14:27:00.398   335  7708 V AudioCache: write(0xb16ba000, 4096)
08-17 14:27:00.398   335  7708 V AudioCache: memcpy(0xac205000, 0xb16ba000, 4096)
08-17 14:27:00.399   335  7708 V AudioCache: write(0xb16ba000, 4096)
08-17 14:27:00.399   335  7708 V AudioCache: memcpy(0xac206000, 0xb16ba000, 4096)
08-17 14:27:00.399   335  7708 V AudioCache: write(0xb16ba000, 4096)
08-17 14:27:00.399   335  7708 V AudioCache: memcpy(0xac207000, 0xb16ba000, 4096)
08-17 14:27:00.400   335  7708 V AudioCache: write(0xb16ba000, 4096)
08-17 14:27:00.400   335  7708 V AudioCache: memcpy(0xac208000, 0xb16ba000, 4096)
08-17 14:27:00.401   335  7708 V AudioCache: write(0xb16ba000, 4096)
08-17 14:27:00.401   335  7708 V AudioCache: memcpy(0xac209000, 0xb16ba000, 4096)
08-17 14:27:00.402   335  7708 V AudioCache: write(0xb16ba000, 4096)
08-17 14:27:00.402   335  7708 V AudioCache: memcpy(0xac20a000, 0xb16ba000, 4096)
08-17 14:27:00.403   335  7708 V AudioCache: write(0xb16ba000, 4096)
08-17 14:27:00.403   335  7708 V AudioCache: memcpy(0xac20b000, 0xb16ba000, 4096)
08-17 14:27:00.403  1036  1529 D WifiService: Client connection lost with reason: 4
08-17 14:27:00.404   335  7708 V AudioCache: write(0xb16ba000, 4096)
,08-17 14:27:00.404   335  7708 V AudioCache: memcpy(0xac20c000, 0xb16ba000, 4096)
08-17 14:27:00.405   335  7708 V AudioCache: write(0xb16ba000, 4096)
08-17 14:27:00.405   335  7708 V AudioCache: memcpy(0xac20d000, 0xb16ba000, 4096)
,08-17 14:27:00.405   335  7708 V AudioCache: write(0xb16ba000, 4096),
08-17 14:27:00.405   335  7708 V AudioCache: memcpy(0xac20e000, 0xb16ba000, 4096)
08-17 14:27:00.405   335  7708 V AudioCache: write(0xb16ba000, 4096)
08-17 14:27:00.405   335  7708 V AudioCache: memcpy(0xac20f000, 0xb16ba000, 4096)
08-17 14:27:00.405   335  7708 V AudioCache: write(0xb16ba000, 4096)
08-17 14:27:00.406   335  7708 V AudioCache: memcpy(0xac210000, 0xb16ba000, 4096)
08-17 14:27:00.408   335  7708 V AudioCache: write(0xb16ba000, 4096)
,08-17 14:27:00.408   335  7708 V AudioCache: memcpy(0xac211000, 0xb16ba000, 4096)
08-17 14:27:00.408   335  7708 V AudioCache: write(0xb16ba000, 4096)
08-17 14:27:00.408   335  7708 V AudioCache: memcpy(0xac212000, 0xb16ba000, 4096)
08-17 14:27:00.408   335  7708 V AudioCache: write(0xb16ba000, 4096)
08-17 14:27:00.408   335  7708 V AudioCache: memcpy(0xac213000, 0xb16ba000, 4096)
08-17 14:27:00.408   335  7708 V AudioCache: write(0xb16ba000, 4096)
08-17 14:27:00.408   335  7708 V AudioCache: memcpy(0xac214000, 0xb16ba000, 4096)
08-17 14:27:00.409  7667  7709 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
08-17 14:27:00.411   335  7708 V AudioCache: write(0xb16ba000, 4096)
08-17 14:27:00.411   335  7708 V AudioCache: memcpy(0xac215000, 0xb16ba000, 4096)
08-17 14:27:00.411   335  7708 V AudioCache: write(0xb16ba000, 4096)
08-17 14:27:00.411   335  7708 V AudioCache: memcpy(0xac216000, 0xb16ba000, 4096)
,08-17 14:27:00.411   335  7708 V AudioCache: write(0xb16ba000, 4096)
08-17 14:27:00.411   335  7708 V AudioCache: memcpy(0xac217000, 0xb16ba000, 4096)
08-17 14:27:00.411   335  7708 V AudioCache: write(0xb16ba000, 4096)
08-17 14:27:00.411   335  7708 V AudioCache: memcpy(0xac218000, 0xb16ba000, 4096)
08-17 14:27:00.412   335  7708 V AudioCache: write(0xb16ba000, 4096)
08-17 14:27:00.412   335  7708 V AudioCache: memcpy(0xac219000, 0xb16ba000, 4096)
08-17 14:27:00.412   335  7708 V AudioCache: write(0xb16ba000, 4096)
08-17 14:27:00.412   335  7708 V AudioCache: memcpy(0xac21a000, 0xb16ba000, 4096)
08-17 14:27:00.413   335  7708 V AudioCache: write(0xb16ba000, 4096)
08-17 14:27:00.413   335  7708 V AudioCache: memcpy(0xac21b000, 0xb16ba000, 4096)
08-17 14:27:00.414   335  7708 V AudioCache: write(0xb16ba000, 4096)
08-17 14:27:00.414   335  7708 V AudioCache: memcpy(0xac21c000, 0xb16ba000, 4096)
,08-17 14:27:00.414   335  7708 V AudioCache: write(0xb16ba000, 4096)
08-17 14:27:00.414   335  7708 V AudioCache: memcpy(0xac21d000, 0xb16ba000, 4096)
08-17 14:27:00.415   335  7708 V AudioCache: write(0xb16ba000, 4096)
08-17 14:27:00.415   335  7708 V AudioCache: memcpy(0xac21e000, 0xb16ba000, 4096)
08-17 14:27:00.415   335  7708 V AudioCache: write(0xb16ba000, 4096)
08-17 14:27:00.415   335  7708 V AudioCache: memcpy(0xac21f000, 0xb16ba000, 4096)
08-17 14:27:00.416   335  7708 V AudioCache: write(0xb16ba000, 4096)
08-17 14:27:00.416   335  7708 V AudioCache: memcpy(0xac220000, 0xb16ba000, 4096)
08-17 14:27:00.417   335  7708 V AudioCache: write(0xb16ba000, 4096)
08-17 14:27:00.417   335  7708 V AudioCache: memcpy(0xac221000, 0xb16ba000, 4096)
08-17 14:27:00.418   335  7708 V AudioCache: write(0xb16ba000, 4096)
08-17 14:27:00.418   335  7708 V AudioCache: memcpy(0xac222000, 0xb16ba000, 4096)
08-17 14:27:00.419   335  7708 V AudioCache: write(0xb16ba000, 4096)
08-17 14:27:00.419   335  7708 V AudioCache: memcpy(0xac223000, 0xb16ba000, 4096)
08-17 14:27:00.419   335  7708 V AudioCache: write(0xb16ba000, 4096)
08-17 14:27:00.419   335  7708 V AudioCache: memcpy(0xac224000, 0xb16ba000, 4096)
08-17 14:27:00.420   335  7708 V AudioCache: write(0xb16ba000, 4096)
08-17 14:27:00.420   335  7708 V AudioCache: memcpy(0xac225000, 0xb16ba000, 4096)
,08-17 14:27:00.421   335  7708 V AudioCache: write(0xb16ba000, 4096)
08-17 14:27:00.421   335  7708 V AudioCache: memcpy(0xac226000, 0xb16ba000, 4096)
08-17 14:27:00.421   335  7708 V AudioCache: write(0xb16ba000, 4096)
08-17 14:27:00.421   335  7708 V AudioCache: memcpy(0xac227000, 0xb16ba000, 4096)
,08-17 14:27:00.422   335  7708 V AudioCache: write(0xb16ba000, 4096)
08-17 14:27:00.422   335  7708 V AudioCache: memcpy(0xac228000, 0xb16ba000, 4096)
08-17 14:27:00.422   335  7708 V AudioCache: write(0xb16ba000, 4096)
08-17 14:27:00.422   335  7708 V AudioCache: memcpy(0xac229000, 0xb16ba000, 4096)
08-17 14:27:00.423   335  7708 V AudioCache: write(0xb16ba000, 4096)
08-17 14:27:00.423   335  7708 V AudioCache: memcpy(0xac22a000, 0xb16ba000, 4096)
08-17 14:27:00.423   335  7707 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-17 14:27:00.423   335  7708 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-17 14:27:00.423   335  7708 V AwesomePlayer: postAudioEOS() 
08-17 14:27:00.423   335  7708 V AudioCache: write(0xb16ba000, 280)
08-17 14:27:00.424   335  7708 V AudioCache: memcpy(0xac22b000, 0xb16ba000, 280)
08-17 14:27:00.425   335  7705 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-17 14:27:00.425   335  7705 V AwesomePlayer: onStreamDone
08-17 14:27:00.425   335  7705 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-17 14:27:00.425   335  7705 V AudioCache: notify(0xb1009080, 2, 0, 0)
08-17 14:27:00.425   335  7705 V AudioCache: playback complete
08-17 14:27:00.425   335  7705 V AwesomePlayer: pause_l() 
08-17 14:27:00.425   335  7705 V AudioCache: notify(0xb1009080, 7, 0, 0)
08-17 14:27:00.425   335  7705 V AudioCache: ignored
08-17 14:27:00.425   335  7705 V AwesomePlayer: cancelPlayerEvents
08-17 14:27:00.426   335  2176 V AudioCache: wait - success
08-17 14:27:00.426   335  2176 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-17 14:27:00.426   335  7705 D AudioPlayer: Pause Playback at 1068125
08-17 14:27:00.427   335  2176 V AwesomePlayer: reset_l() 
08-17 14:27:00.427   335  2176 V AudioCache: notify(0xb1009080, 8, 0, 0)
08-17 14:27:00.427   335  2176 V AudioCache: ignored
08-17 14:27:00.427   335  2176 V AwesomePlayer: cancelPlayerEvents
08-17 14:27:00.427   335  2176 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-17 14:27:00.427   335  2176 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-17 14:27:00.427   335  2176 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-17 14:27:00.427   335  2176 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-17 14:27:00.427   335  2176 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-17 14:27:00.428   335  7707 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-17 14:27:00.428   335  7707 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-17 14:27:00.428   335  7707 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-17 14:27:00.428   335  7707 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ba0 on port 0
08-17 14:27:00.428   335  7707 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-17 14:27:00.428   335  7707 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 0
08-17 14:27:00.428   335  7707 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-17 14:27:00.428   335  7707 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 0
08-17 14:27:00.428   335  7707 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-17 14:27:00.428   335  7707 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 0
08-17 14:27:00.428   335  7707 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-17 14:27:00.428   335  7707 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-17 14:27:00.428   335  7707 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb000f1f0 on port 1
08-17 14:27:00.428   335  7707 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-17 14:27:00.428   335  7707 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7d30 on port 1
08-17 14:27:00.428   33,5  7707 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-17 14:27:00.428   335  7707 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7e70 on port 1
08-17 14:27:00.428   335  7707 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-17 14:27:00.428   335  7707 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7fb0 on port 1
08-17 14:27:00.428   335  7707 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-17 14:27:00.428   335  7707 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-17 14:27:00.428   335  2176 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-17 14:27:00.428   335  2176 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-17 14:27:00.429   335  7707 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-17 14:27:00.429   335  7707 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-17 14:27:00.429   335  7707 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-17 14:27:00.429   335  2176 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-17 14:27:00.429   335  2176 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-17 14:27:00.429   335  2176 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-17 14:27:00.430   335  2176 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-17 14:27:00.430   335  2176 D AudioPlayer: AudioPlayer releasing audio source
08-17 14:27:00.430   335  2176 D AudioPlayer: AudioPlayer done releasing audio source
08-17 14:27:00.430   335  2176 V AwesomePlayer: reset_l() 
08-17 14:27:00.430   335  2176 V AwesomePlayer: cancelPlayerEvents
08-17 14:27:00.430   335  2176 V AwesomePlayer: ~AwesomePlayer call
08-17 14:27:00.430   335  2176 V AwesomePlayer: reset_l() 
08-17 14:27:00.430   335  2176 V AwesomePlayer: cancelPlayerEvents
08-17 14:27:00.430  7667  7704 V SoundPool: close(31)
08-17 14:27:00.430  7667  7704 V SoundPool: pointer = 0x9fe60000, size = 205080, sampleRate = 48000, numChannels = 2
08-17 14:27:00.438  1036  1909 W libprocessgroup: failed to open /acct/uid_1000/pid_6858/cgroup.procs: No such file or directory
08-17 14:27:00.442  7667  7667 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-17 14:27:00.442  7667  7667 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-17 14:27:00.443  7667  7667 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-17 14:27:00.443  7667  7667 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-17 14:27:00.443  7667  7667 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-17 14:27:00.443  7667  7667 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-17 14:27:00.443  7667  7667 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-17 14:27:00.449  7667  7667 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-17 14:27:00.632  6725  6786 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:27:00.632  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 14:27:00.812  1036  1099 W ProcessCpuTracker: Skipping unknown process pid 7684
08-17 14:27:00.813  1036  1099 W ProcessCpuTracker: Skipping unknown process pid 7687
,08-17 14:27:00.856  1590  1590 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-17 14:27:00.926  1036  1036 D administrator: Handling package changes for user 0
,08-17 14:27:00.948  1036  1099 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7720 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-17 14:27:00.954  1590  1590 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
08-17 14:27:00.955  1590  1590 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
08-17 14:27:01.003  1036  1414 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-17 14:27:01.015  2020  2020 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-17 14:27:01.048  7720  7720 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-17 14:27:01.055  2020  2020 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-17 14:27:01.072  1036  1036 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
,08-17 14:27:01.072  1036  1036 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
08-17 14:27:01.138  1036  1098 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-17 14:27:01.143  1036  1098 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-17 14:27:01.147  7720  7720 D LgDataFeature: LgDataFeature() Constructor: none
08-17 14:27:01.147  7720  7720 D LgDataFeature: LgDataFeature() Constructor Done, null
08-17 14:27:01.151  2472  2472 V GmsNetworkLocationProvi: DISABLE
,08-17 14:27:01.154  2020  2020 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-17 14:27:01.183  1036  1098 D LocationProviderProxy: applying state to connected service
,08-17 14:27:01.186  2472  2472 E GCoreFlp: Bound FusedProviderService with LocationManager
,08-17 14:27:01.246  7720  7764 I Babel   : MmsConfig: mnc/mcc: 0/0
08-17 14:27:01.246  7720  7764 I Babel   : MmsConfig.loadMmsSettings
,08-17 14:27:01.252  7720  7764 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-17 14:27:01.252  7720  7764 I Babel   : MmsConfig.loadFromDatabase
,08-17 14:27:01.271  7720  7764 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-17 14:27:01.272  7720  7764 I Babel   : MmsConfig.loadFromResources
08-17 14:27:01.273  7720  7764 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-17 14:27:01.273  7720  7764 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-17 14:27:01.278  7720  7720 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-17 14:27:01.300  7720  7763 W AudioCapabilities: Unsupported mime audio/evrc
,08-17 14:27:01.302  7720  7763 W AudioCapabilities: Unsupported mime audio/qcelp
08-17 14:27:01.306  7720  7763 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-17 14:27:01.314  1804  7767 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-17 14:27:01.314  1804  7767 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
,08-17 14:27:01.323  7008  7008 I AppUp4:CustModeStarterReceiver: onReceive
08-17 14:27:01.332  7008  7008 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@3f8bc126
08-17 14:27:01.332  7008  7008 D AppUp4:CustFacade: isCustomizationCompleted : false
08-17 14:27:01.332  7008  7008 D AppUp4:CustFacade: isPhone : true
08-17 14:27:01.332  7008  7008 D AppUp4:CustModeStarterReceiver: begin check event
08-17 14:27:01.332  7008  7008 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
,08-17 14:27:01.336  7720  7763 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
08-17 14:27:01.339  1804  4746 I Icing   : updateResources: need to parse e{com.google.android.gms}
08-17 14:27:01.339  7720  7763 W AudioCapabilities: Unsupported mime audio/qcelp
08-17 14:27:01.342  7720  7763 W AudioCapabilities: Unsupported mime audio/evrc
,08-17 14:27:01.361  7720  7763 W VideoCapabilities: Unsupported mime video/x-ms-wmv
08-17 14:27:01.364  7720  7763 W VideoCapabilities: Unsupported mime video/divx
08-17 14:27:01.367  7720  7763 W VideoCapabilities: Unsupported mime video/divx311
08-17 14:27:01.370  7720  7763 W VideoCapabilities: Unsupported mime video/divx4
08-17 14:27:01.380  7720  7763 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-17 14:27:01.383  1036  1946 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7770 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
08-17 14:27:01.387  1036  1638 I ActivityManager: Killing 7048:com.lge.email/u0a23 (adj 15): empty #17
,08-17 14:27:01.414  7720  7763 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-17 14:27:01.419  7720  7763 W AudioCapabilities: Unsupported mime audio/eac3
08-17 14:27:01.420  7720  7763 W AudioCapabilities: Unsupported mime audio/ac3
08-17 14:27:01.421  7720  7763 W AudioCapabilities: Unsupported mime audio/g726
08-17 14:27:01.422  7720  7763 W AudioCapabilities: Unsupported mime audio/wma-voice
08-17 14:27:01.423  7720  7763 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-17 14:27:01.424  7720  7763 W AudioCapabilities: Unsupported mime audio/adpcm
08-17 14:27:01.426  7720  7763 W VideoCapabilities: Unsupported mime video/theora
08-17 14:27:01.428  7720  7763 W VideoCapabilities: Unsupported mime video/mjpg
,08-17 14:27:01.559  1036  1052 W libprocessgroup: failed to open /acct/uid_10023/pid_7048/cgroup.procs: No such file or directory
,08-17 14:27:01.604  7770  7770 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-17 14:27:01.605  7770  7770 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-17 14:27:01.605  7770  7770 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,08-17 14:27:01.607  7770  7770 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-17 14:27:01.607  7770  7770 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-17 14:27:01.663  7770  7770 I SystemConfig: BUILD Country: EU
08-17 14:27:01.664  7770  7770 I SystemConfig: BUILD Operator: OPEN
,08-17 14:27:01.716  1036  2001 I ActivityManager: Killing 6925:com.lge.formmanager/u0a26 (adj 15): empty #17
,08-17 14:27:01.814  1036  2036 W libprocessgroup: failed to open /acct/uid_10026/pid_6925/cgroup.procs: No such file or directory
,08-17 14:27:01.835  7770  7792 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
,08-17 14:27:01.836  7770  7792 I SystemConfig: existFile = false
08-17 14:27:01.836  7770  7792 I SystemConfig: canReadFile = false
08-17 14:27:01.836  7770  7792 I SystemConfig: systemFeature RCS result false
08-17 14:27:01.837  7770  7792 D SystemConfig: refreshRcsSupport() :false
08-17 14:27:01.876  1036  2001 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7794 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-17 14:27:01.957  7794  7794 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-17 14:27:01.958  7794  7794 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-17 14:27:01.958  7794  7794 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,08-17 14:27:01.958  7794  7794 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-17 14:27:02.085  7794  7794 I AppConfig: Total System Memory = 2995761152
,08-17 14:27:02.098  7794  7794 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
,08-17 14:27:02.179  1036  1980 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7813 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-17 14:27:02.181  1036  1980 I ActivityManager: Killing 6461:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,08-17 14:27:02.209   356   356 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 481us total 23.736ms
,08-17 14:27:02.232   356   356 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 402us total 21.805ms
,08-17 14:27:02.258   356   356 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 185us total 24.658ms
,08-17 14:27:02.277  1036  1909 W libprocessgroup: failed to open /acct/uid_1000/pid_6461/cgroup.procs: No such file or directory
,08-17 14:27:02.453  7813  7813 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-17 14:27:02.572  7813  7813 D LgDataFeature: LgDataFeature() Constructor: none
08-17 14:27:02.572  7813  7813 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-17 14:27:02.627  7813  7813 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-17 14:27:02.649  7813  7813 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-17 14:27:02.650  7813  7813 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-17 14:27:02.667  7813  7813 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-17 14:27:02.667  7813  7813 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-17 14:27:02.693  1036  1640 I ActivityManager: Killing 7083:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,08-17 14:27:02.742  1036  1875 W libprocessgroup: failed to open /acct/uid_10046/pid_7083/cgroup.procs: No such file or directory
,08-17 14:27:02.752  4598  7859 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
08-17 14:27:02.757  3476  4485 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-17 14:27:02.760  3476  4485 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@19cd6655 on behalf of 7813
,08-17 14:27:02.827  1036  1052 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7860 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-17 14:27:02.847  7813  7813 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-17 14:27:02.858  7574  7608 D UEI.SmartControl: Internal timer expired: 1
,08-17 14:27:02.858  7574  7608 D UEI.SmartControl: unbind internal service
08-17 14:27:02.872  7813  7813 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-17 14:27:02.929  7860  7860 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-17 14:27:02.957  7860  7860 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
,08-17 14:27:02.960  7860  7860 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-17 14:27:02.960  7860  7860 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-17 14:27:02.961  7860  7860 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-17 14:27:02.961  7860  7860 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-17 14:27:02.961  7860  7860 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
08-17 14:27:02.979  1036  2000 I ActivityManager: Killing 7102:com.android.chrome/u0a57 (adj 15): empty #17
,08-17 14:27:03.012  1036  1051 W libprocessgroup: failed to open /acct/uid_10057/pid_7102/cgroup.procs: No such file or directory
,08-17 14:27:03.099  7574  7605 D serial_port: close(fd = 25)
,08-17 14:27:03.106  7574  7605 I UEI.SmartControl: Serial port is closed.
08-17 14:27:03.187  1036  2036 V SIM_STK : Menu title from STK is T-Mobile
,08-17 14:27:03.226  4598  7859 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 474 ms] updated apps [took 474 ms] 
,08-17 14:27:03.639  6725  6786 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 14:27:03.640  6725  6786 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@334824ed added. We now have 6 listener(s)
08-17 14:27:03.640  6725  6786 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 14:27:03.650  6725  6786 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 14:27:03.650  6725  6786 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d461f22 added. We now have 7 listener(s)
08-17 14:27:03.650  6725  6786 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 14:27:03.650  6725  6786 I System.out: IsBluetoothEnabled
08-17 14:27:03.651  1036  1560 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 14:27:03.651  1036  1560 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
08-17 14:27:03.652  1036  1103 D BluetoothManagerService: Message: 2
08-17 14:27:03.655  6725  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:27:03.655  1036  1980 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 14:27:03.656  1036  1980 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-17 14:27:03.675  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-17 14:27:03.676  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-17 14:27:03.676  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-17 14:27:03.676  1036  1103 D BluetoothManagerService: Message: 1
08-17 14:27:03.677  1036  1103 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-17 14:27:03.700  1036  1103 D BluetoothManagerService: Message: 20
08-17 14:27:03.701  1036  1103 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2d6f01f6:true
,08-17 14:27:03.705  7639  7639 D BluetoothAdapterState: make
08-17 14:27:03.710  7639  7639 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-17 14:27:03.710  7639  7639 I bluedroid-qcom: init
08-17 14:27:03.711  7639  7890 I BluetoothAdapterState: Entering OffState
08-17 14:27:03.711  7639  7639 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-17 14:27:03.711  7639  7639 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-17 14:27:03.712  7639  7639 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-17 14:27:03.712  7639  7639 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-17 14:27:03.712  7639  7639 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-17 14:27:03.713  7639  7639 I bluedroid-qcom: get_profile_interface socket
08-17 14:27:03.713  7639  7639 I bluedroid-qcom: get_profile_interface map_client
,08-17 14:27:03.718  7639  7894 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-17 14:27:03.707  7893  7893 W bdaddr_loader: type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 14:27:03.707  7893  7893 W bdaddr_loader: type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 14:27:03.728  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,08-17 14:27:03.730  1036  1103 D BluetoothManagerService: Message: 40
08-17 14:27:03.731  1036  1103 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-17 14:27:03.732  7639  7654 I bluedroid-qcom: config_hci_snoop_log
08-17 14:27:03.733  1036  1103 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-17 14:27:03.733  1036  1103 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-17 14:27:03.737  7893  7893 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-17 14:27:03.737  7893  7893 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-17 14:27:03.737  7893  7893 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-17 14:27:03.740  7893  7893 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
,08-17 14:27:03.747  7893  7893 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-17 14:27:03.747  7893  7893 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-17 14:27:03.750  7639  7890 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-17 14:27:03.750  7639  7890 D BluetoothAdapterProperties: Setting state to 11
08-17 14:27:03.750  7639  7890 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-17 14:27:03.751  7639  7890 I LGBluetoothServiceJni: classInitNative: succeeds
08-17 14:27:03.752  1036  1103 D BluetoothManagerService: Message: 60
08-17 14:27:03.752  1036  1103 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-17 14:27:03.752  1036  1103 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
,08-17 14:27:03.758  1590  1590 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-17 14:27:03.760  1929  1929 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:27:03.761  6725  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:27:03.764  6837  6837 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-17 14:27:03.773  7639  7639 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-17 14:27:03.774  7639  7639 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:27:03.774  7639  7639 V BluetoothPbapReceiver: ***********state = 11
,08-17 14:27:03.782  2162  2162 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-17 14:27:03.795  7639  7894 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-17 14:27:03.804  7639  7894 D BluetoothAdapterProperties: Name is: G3
08-17 14:27:03.804  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-17 14:27:03.804  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
08-17 14:27:03.808  6837  6837 D BluetoothPermissionRequest: onReceive
08-17 14:27:03.808  7639  7890 D BluetoothBondStateMachine: make
08-17 14:27:03.811  6837  6837 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-17 14:27:03.814  7639  7890 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6399fbd
08-17 14:27:03.814  7639  7890 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-17 14:27:03.814  7639  7890 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6399fbd
08-17 14:27:03.815  7639  7890 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-17 14:27:03.816  7639  7910 I BluetoothBondStateMachine: StableState(): Entering Off State
08-17 14:27:03.816  7639  7890 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-17 14:27:03.820  7639  7639 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:27:03.823  7639  7639 V BluetoothSapReceiver: [BTUI] checkServiceStart
,08-17 14:27:03.823  7639  7639 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-17 14:27:03.823  7639  7639 V BluetoothSapReceiver: SapReceiver onReceive 
08-17 14:27:03.824  7639  7639 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:27:03.824  7639  7639 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-17 14:27:03.827  7639  7890 E BluetoothAdapterService: File transfer profiles supported!!
08-17 14:27:03.840  7639  7639 D HeadsetService: Received start request. Starting profile...
08-17 14:27:03.840  7639  7890 E BluetoothAdapterService: File transfer profiles supported!!
08-17 14:27:03.840  7639  7639 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-17 14:27:03.840  7639  7639 D LGBluetoothHfpAdapter: Version 1.6
,08-17 14:27:03.843  7639  7639 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-17 14:27:03.845  7639  7639 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-17 14:27:03.845  7639  7639 D HeadsetStateMachine: make
08-17 14:27:03.845  7639  7890 E BluetoothAdapterService: File transfer profiles supported!!
08-17 14:27:03.850  7639  7890 E BluetoothAdapterService: File transfer profiles supported!!
08-17 14:27:03.855  7639  7890 E BluetoothAdapterService: File transfer profiles supported!!
,08-17 14:27:03.860  7639  7890 E BluetoothAdapterService: File transfer profiles supported!!
08-17 14:27:03.865  7639  7890 E BluetoothAdapterService: File transfer profiles supported!!
08-17 14:27:03.886  7639  7890 V LGMDMManager: Create singleton instance
,08-17 14:27:03.887  7639  7639 D LgDataFeature: LgDataFeature() Constructor: none
08-17 14:27:03.887  7639  7639 D LgDataFeature: LgDataFeature() Constructor Done, null
08-17 14:27:03.888  7639  7890 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-17 14:27:03.892  7639  7639 D HeadsetStateMachine: max_hf_connections = 1
08-17 14:27:03.892  7639  7639 I bluedroid-qcom: get_profile_interface handsfree
,08-17 14:27:03.894  7639  7639 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-17 14:27:03.895   335   335 V AudioPolicyService: registerClient() client 0xb10087c0, uid 1002
08-17 14:27:03.895   335  1372 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-17 14:27:03.895   335  1372 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-17 14:27:03.895   335  1372 V AudioPolicyManagerEx: getOutput() returns output 2
08-17 14:27:03.895  7639  7639 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
,08-17 14:27:03.895   335  2176 V AudioFlinger: registerClient() client 0xb5581b50, pid 7639
,08-17 14:27:03.896   335  1366 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-17 14:27:03.896   335  1366 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-17 14:27:03.896  1036  1640 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-17 14:27:03.896  7639  7639 V ToneGenerator: Create Track: 0xb4928a80
08-17 14:27:03.896  1036  1640 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-17 14:27:03.896  7639  7639 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-17 14:27:03.896  7639  7639 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-17 14:27:03.897  7639  7654 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-17 14:27:03.897  7639  7654 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-17 14:27:03.897   335  1367 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-17 14:27:03.897   335  1367 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-17 14:27:03.897   335   335 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-17 14:27:03.897   335   335 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-17 14:27:03.897   335   335 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-17 14:27:03.897   335   335 V AudioPolicyManagerEx: getOutput() returns output 2
08-17 14:27:03.897  1036  1964 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-17 14:27:03.897  1036  1964 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-17 14:27:03.897  7639  7895 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-17 14:27:03.897  7639  7895 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-17 14:27:03.897   335  2176 I AudioFlinger: isAudioPlaybackHookOn() false
08-17 14:27:03.898   335  2182 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-17 14:27:03.898  1590  2094 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-17 14:27:03.898   335  2182 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-17 14:27:03.898   335  2182 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-17 14:27:03.898  1590  2094 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-17 14:27:03.898   335  2182 V AudioPolicyManagerEx: getOutput() returns output 2
08-17 14:27:03.898  7639  7639 V AudioSystem: getLatency() output 2, latency 50
08-17 14:27:03.898  7639  7639 V AudioSystem: getFrameCount() output 2, frameCount 960
08-17 14:27:03.898  7639  7639 V AudioTrack: createTrack_l() output 2 afLatency 50
08-17 14:27:03.898  1839  2630 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-17 14:27:03.898  1839  2630 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-17 14:27:03.898  1839  2630 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-17 14:27:03.898  1839  2630 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-17 14:27:03.898  3400  3420 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-17 14:27:03.898  3400  3420 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-17 14:27:03.898   335  1372 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-17 14:27:03.898  3400  3420 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-17 14:27:03.898   335  1372 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-17 14:27:03.898  3400  3420 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-17 14:27:03.898   335  1372 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-17 14:27:03.898   335  1372 V AudioFlinger: [MABL_Audio,Flinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-17 14:27:03.898   335  1372 V AudioFlinger: createTrack() lSessionId: 23
08-17 14:27:03.898  1590  2094 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-17 14:27:03.898  1590  2094 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-17 14:27:03.899  7639  7639 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-17 14:27:03.900   335  1372 V AudioFlinger: acquiring 23 from 7639, for 7639
08-17 14:27:03.900   335  1372 V AudioFlinger:  added new entry for 23
08-17 14:27:03.900  7639  7639 V ToneGenerator: ToneGenerator INIT OK, time: 345664
08-17 14:27:03.900  7639  7639 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6399fbd
08-17 14:27:03.902  7639  7913 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-17 14:27:03.902  7639  7639 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6399fbd
08-17 14:27:03.902  7639  7913 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-17 14:27:03.902  7639  7913 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-17 14:27:03.903  7639  7913 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-17 14:27:03.903   335   335 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7639
08-17 14:27:03.904   335   335 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-17 14:27:03.904   335   335 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-17 14:27:03.904   335   335 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-17 14:27:03.904   335   335 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-17 14:27:03.904   335   335 V voice   : voice_set_parameters: exit with code(0)
08-17 14:27:03.904   335   335 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-17 14:27:03.904   335   335 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-17 14:27:03.904   335   335 V msm8974_platform: platform_set_parameters: exit with code(0)
08-17 14:27:03.904   335   335 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-17 14:27:03.904   335   335 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-17 14:27:03.904   335   335 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-17 14:27:03.905  7639  7639 D A2dpService: Received start request. Starting profile...
08-17 14:27:03.906  7639  7639 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-17 14:27:03.906  7639  7913 V ToneGenerator: ToneGenerator destructor
08-17 14:27:03.906  7639  7913 V ToneGenerator: stopTone
08-17 14:27:03.906  7639  7913 V ToneGenerator: Delete Track: 0xb4928a80
08-17 14:27:03.907  7639  7639 V Avrcp   : make
08-17 14:27:03.908  7639  7913 V AudioTrack: ~AudioTrack, releasing session id from 7639 on behalf of 7639
08-17 14:27:03.908   335  2182 V AudioPolicyService: AudioCommandThread() adding release output 2
08-17 14:27:03.908   335  1372 V AudioFlinger: releasing 23 from 7639 for 7639
08-17 14:27:03.908   335  2182 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-17 14:27:03.908   335  1372 V AudioFlinger:  decremented refcount to 0
08-17 14:27:03.908  7639  7639 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-17 14:27:03.908   335  1372 V AudioFlinger: purging stale effects
08-17 14:27:03.908   335  1126 V AudioPolicyService: AudioCommandThread() waking up
08-17 14:27:03.908   335  1126 V AudioPolicyService: AudioCommandThread() processing release output 2
08-17 14:27:03.908   335  1126 V AudioPolicyManager: releaseOutput() 2
08-17 14:27:03.908  7639  7639 I bluedroid-qcom: get_profile_interface avrcp
08-17 14:27:03.908   335  1126 V AudioPolicyService: AudioCommandThread() going to sleep
08-17 14:27:03.908   335  2182 V AudioFlinger: PlaybackThread::Track destructor
08-17 14:27:03.908   335  2182 V AudioFlinger: removeClient_l() pid 7639, calling pid 335
08-17 14:27:03.922  7639  7639 V AudioManager: registerRemoteController: size of Media player list: 0
08-17 14:27:03.924  7639  7639 E AudioManager: No RCC entry present to update
08-17 14:27:03.924  7639  7639 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-17 14:27:03.928  7639  7639 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-17 14:27:03.930  7639  7639 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-17 14:27:03.930  7639  7639 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-17 14:27:03.934  7639  7639 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-17 14:27:04.040  1036  1638 V SIM_STK : Menu title from STK is T-Mobile
,08-17 14:27:04.041  1036  1638 V SIM_STK : Menu title from STK is T-Mobile
,08-17 14:27:04.199  1036  1875 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-17 14:27:04.211  7639  7639 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-17 14:27:04.216  7639  7639 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-17 14:27:04.217  7639  7639 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-17 14:27:04.217  7639  7639 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-17 14:27:04.217  7639  7639 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-17 14:27:04.217  7639  7639 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-17 14:27:04.217  7639  7639 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-17 14:27:04.217  7639  7639 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-17 14:27:04.217  7639  7639 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-17 14:27:04.217  7639  7639 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-17 14:27:04.217  7639  7639 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-17 14:27:04.218  7639  7639 I BluetoothA2dpServiceJni: classInitNative
08-17 14:27:04.218  7639  7639 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-17 14:27:04.218  7639  7639 D A2dpStateMachine: make
08-17 14:27:04.219  7639  7639 I bluedroid-qcom: get_profile_interface a2dp
08-17 14:27:04.220  7639  7925 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-17 14:27:04.222  7639  7639 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-17 14:27:04.222  7639  7639 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-17 14:27:04.223  7639  7639 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6399fbd
08-17 14:27:04.225  7639  7639 I BluetoothHidServiceJni: classInitNative: succeeds
,08-17 14:27:04.226  7639  7924 D A2dpStateMachine: Enter Disconnected: -2
08-17 14:27:04.227  7639  7639 D HidService: Received start request. Starting profile...
08-17 14:27:04.228  7639  7639 I bluedroid-qcom: get_profile_interface hidhost
08-17 14:27:04.228  7639  7639 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6399fbd
08-17 14:27:04.230  7639  7639 I BluetoothHealthServiceJni: classInitNative: succeeds
08-17 14:27:04.232  7639  7639 D HealthService: Received start request. Starting profile...
08-17 14:27:04.234  7639  7639 I bluedroid-qcom: get_profile_interface health
08-17 14:27:04.234  7639  7639 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-17 14:27:04.234  7639  7639 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6399fbd
08-17 14:27:04.235  7639  7639 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-17 14:27:04.237  7639  7639 D PanService: Received start request. Starting profile...
08-17 14:27:04.238  7639  7639 D BluetoothPanServiceJni: initializeNative(L110): pan
08-17 14:27:04.238  7639  7639 I bluedroid-qcom: get_profile_interface pan
,08-17 14:27:04.248  7639  7639 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-17 14:27:04.249  7639  7639 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6399fbd
08-17 14:27:04.252  7639  7639 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-17 14:27:04.266  7639  7639 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-17 14:27:04.267  7639  7639 D BtGatt.GattService: Received start request. Starting profile...
08-17 14:27:04.267  7639  7639 D BtGatt.GattService: start()
08-17 14:27:04.267  7639  7639 I bluedroid-qcom: get_profile_interface gatt
08-17 14:27:04.267  7639  7639 D BtGatt.AdvertiseManager: advertise manager created
08-17 14:27:04.273  7639  7639 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6399fbd
08-17 14:27:04.275  7639  7639 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6399fbd
08-17 14:27:04.275  7639  7639 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-17 14:27:04.276  7639  7639 V BluetoothMapService: BluetoothMapBinder()
08-17 14:27:04.277  7639  7639 D BluetoothMapService: Received start request. Starting profile...
08-17 14:27:04.277  7639  7639 D BluetoothMapService: start()
08-17 14:27:04.280  7639  7639 D BluetoothMapEmailSettingsLoader: Found 0 applications
,08-17 14:27:04.280  7639  7639 D BluetoothMapEmailAppObserver: createReceiver()
08-17 14:27:04.282  7639  7639 D BluetoothMapEmailAppObserver: initObservers()
08-17 14:27:04.282  7639  7639 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-17 14:27:04.291  7639  7639 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6399fbd
,08-17 14:27:04.292  7639  7639 D HeadsetStateMachine: Proxy object connected
08-17 14:27:04.293  7639  7639 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-17 14:27:04.293  7639  7639 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
,08-17 14:27:04.295  7639  7913 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-17 14:27:04.295  7639  7913 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-17 14:27:04.296  7639  7913 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-17 14:27:04.301  7639  7639 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-17 14:27:04.304  7639  7639 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-17 14:27:04.309  7639  7639 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-17 14:27:04.313  7639  7639 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-17 14:27:04.313  7639  7639 V PanService: [BTUI] SIM Extra State :ABSENT
08-17 14:27:04.317  7639  7639 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-17 14:27:04.321  7639  7639 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-17 14:27:04.321  7639  7639 V BluetoothMapService: Handler(): got msg=1
08-17 14:27:04.323  7639  7890 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-17 14:27:04.323  7639  7890 I bluedroid-qcom: enable
08-17 14:27:04.323  7639  7932 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-17 14:27:04.323  7639  7932 I bt-btu  : btu_task pending for preload complete event
08-17 14:27:04.323  7639  7890 I bt_hci_bdroid: init
08-17 14:27:04.324  7639  7890 I bt_vendor: bt-vendor : init
08-17 14:27:04.324  7639  7890 I bt_vendor: bt-vendor : get_bt_soc_type
08-17 14:27:04.324  7639  7890 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-17 14:27:04.324  7639  7890 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-17 14:27:04.324  7639  7890 D bt_userial_mct: userial_init
08-17 14:27:04.325  7639  7890 D bt_hci_bdroid: set_power 1
08-17 14:27:04.325  7639  7890 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-17 14:27:04.325  7639  7890 I bt_vendor: Starting hciattach daemon
08-17 14:27:04.325  7639  7890 I bt_vendor: try to set true
08-17 14:27:04.317  7935  7935 W sh      : type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 14:27:04.317  7935  7935 W sh      : type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-17 14:27:04.356  7936  7936 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-17 14:27:04.436  7942  7942 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-17 14:27:04.449  7943  7943 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-17 14:27:04.475  7945  7945 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-17 14:27:04.487  7946  7946 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
08-17 14:27:04.499  7947  7947 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-17 14:27:04.512  7948  7948 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-17 14:27:04.533  7950  7950 I libmdmdetect: ESOC framework not supported
,08-17 14:27:04.535  7950  7950 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
08-17 14:27:04.546  7950  7950 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-17 14:27:04.546  7950  7950 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-17 14:27:04.546  7950  7950 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-17 14:27:04.546  7950  7950 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-17 14:27:04.546  7950  7950 D bthci_qcomm_common: [BTUI]     LE: Class 2
,08-17 14:27:04.546  7950  7950 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
,08-17 14:27:04.546  7950  7950 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-17 14:27:04.590  7950  7951 E QC-QMI  : qmi_client [7950] 15: failed to locate client data
,08-17 14:27:04.594   460   460 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-17 14:27:04.594   460   460 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,08-17 14:27:04.648  7952  7952 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-17 14:27:04.674  7953  7953 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-17 14:27:04.732  7639  7890 I bt_vendor: bluetooth satus is on
08-17 14:27:04.732  7639  7890 D bt_hci_bdroid: preload
08-17 14:27:04.732  7639  7934 D bt_userial_mct: userial_open(port:0)
08-17 14:27:04.732  7639  7934 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-17 14:27:04.738  7639  7934 I bt_vendor: Done intiailizing UART
08-17 14:27:04.742  7639  7934 I bt_vendor: Done intiailizing UART
08-17 14:27:04.742  7639  7934 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-17 14:27:04.742  7639  7934 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-17 14:27:04.742  7639  7932 I bt-btu  : btu_task received preload complete event
08-17 14:27:04.743  7639  7955 D bt_userial_mct: Entering userial_read_thread()
08-17 14:27:04.743  7639  7932 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-17 14:27:04.744  7639  7932 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-17 14:27:04.748  7639  7932 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
,08-17 14:27:04.756  7639  7932 I         : BTE_InitTraceLevels -- TRC_HCI
,08-17 14:27:04.756  7639  7932 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-17 14:27:04.756  7639  7932 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-17 14:27:04.756  7639  7932 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-17 14:27:04.756  7639  7932 I         : BTE_InitTraceLevels -- TRC_AVRC
08-17 14:27:04.756  7639  7932 I         : BTE_InitTraceLevels -- TRC_A2D
08-17 14:27:04.756  7639  7932 I         : BTE_InitTraceLevels -- TRC_BNEP
08-17 14:27:04.756  7639  7932 I         : BTE_InitTraceLevels -- TRC_BTM
08-17 14:27:04.756  7639  7932 I         : BTE_InitTraceLevels -- TRC_HID_HOST
,08-17 14:27:04.756  7639  7932 I         : BTE_InitTraceLevels -- TRC_GAP,
08-17 14:27:04.756  7639  7932 I         : BTE_InitTraceLevels -- TRC_PAN,
08-17 14:27:04.756  7639  7932 I         : BTE_InitTraceLevels -- TRC_SDP
08-17 14:27:04.756  7639  7932 I         : BTE_InitTraceLevels -- TRC_GATT
08-17 14:27:04.756  7639  7932 I         : BTE_InitTraceLevels -- TRC_SMP
,08-17 14:27:04.756  7639  7932 I         : BTE_InitTraceLevels -- TRC_BTAPP,
08-17 14:27:04.757  7639  7932 I         : BTE_InitTraceLevels -- TRC_BTIF,
,08-17 14:27:04.862  7639  7932 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
,08-17 14:27:04.862  7639  7932 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa016c061 
,08-17 14:27:04.862  7639  7932 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa016c061 ,
,08-17 14:27:04.928  7639  7894 E bt-btif : Calling BTA_HhEnable
,08-17 14:27:04.929  7639  7894 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-17 14:27:04.929  7639  7894 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-17 14:27:04.941  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
,08-17 14:27:04.942  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
,08-17 14:27:04.943  7639  7932 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
,08-17 14:27:04.943  7639  7932 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
,08-17 14:27:04.943  7639  7932 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-17 14:27:04.944  7639  7932 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-17 14:27:04.944  7639  7932 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-17 14:27:04.948  7639  7894 D BluetoothAdapterProperties: Name is: G3
,08-17 14:27:04.959  7639  7894 D BluetoothAdapterProperties: Scan Mode:20
08-17 14:27:04.959  7639  7894 D BluetoothAdapterProperties: Discoverable Timeout:120
08-17 14:27:04.960  7639  7894 D bt_hci_bdroid: postload
08-17 14:27:04.961  7639  7934 D bt_hci_bdroid: Used up Tx Cmd credits
08-17 14:27:04.962  7639  7894 D bte_conf: Device ID record 1 : primary
08-17 14:27:04.962  7639  7894 D bte_conf:   vendorId            = 00c4
08-17 14:27:04.962  7639  7894 D bte_conf:   vendorIdSource      = 0001
08-17 14:27:04.962  7639  7894 D bte_conf:   product             = 13a1
08-17 14:27:04.962  7639  7894 D bte_conf:   version             = 1000
08-17 14:27:04.962  7639  7894 D bte_conf:   clientExecutableURL = 
08-17 14:27:04.962  7639  7894 D bte_conf:   serviceDescription  = 
08-17 14:27:04.962  7639  7894 D bte_conf:   documentationURL    = 
08-17 14:27:04.962  7639  7894 D bte_conf: bte_load_did_conf no section named DID2.
08-17 14:27:04.963  7639  7932 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-17 14:27:04.963  7639  7934 D bt_hci_bdroid: Used up Tx Cmd credits
08-17 14:27:04.966  7639  7890 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-17 14:27:04.966  7639  7890 D BluetoothAdapterProperties: ScanMode =  20
08-17 14:27:04.967  7639  7890 D BluetoothAdapterProperties: State =  11
08-17 14:27:04.967  7639  7890 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-17 14:27:04.967  7639  7890 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-17 14:27:04.967  7639  7890 D BluetoothAdapterProperties: Setting state to 12
08-17 14:27:04.967  7639  7890 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-17 14:27:04.968  7639  7894 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-17 14:27:04.968  7639  7894 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-17 14:27:04.957  7960  7960 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 14:27:04.957  7960  7960 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 14:27:04.979  1036  1103 D BluetoothManagerService: Message: 60
08-17 14:27:04.979  1036  1103 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-17 14:27:04.979  1036  1103 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
08-17 14:27:04.980  7639  7934 D bt_hci_bdroid: Used up Tx Cmd credits
08-17 14:27:04.984  7639  7934 D bt_hci_bdroid: Used up Tx Cmd credits
,08-17 14:27:04.987  7639  7955 E bt_mct  : hci lib postload completed
08-17 14:27:04.996  7639  7932 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-17 14:27:04.996  7639  7932 W bt-smp  : Plain text(LSB ~ MSB) = 1b 59 7b 00 00 00 00 00 00 00 00 00 00 00 00 00 
,08-17 14:27:04.998  7639  7932 W bt-smp  : Encrypted text(LSB ~ MSB) = ee f2 70 06 60 31 c6 03 3a 88 14 0b 51 63 29 03 
08-17 14:27:04.999  7639  7932 W bt-btm  : Stopping oneshot timer
08-17 14:27:05.011  7639  7890 I BluetoothAdapterState: Entering On State
,08-17 14:27:05.020  7639  7890 D LGBluetoothServiceAdapter: [BTUI] OnState
08-17 14:27:05.020  7639  7890 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-17 14:27:05.020  7639  7890 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-17 14:27:05.021  7639  7890 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-17 14:27:05.024  7639  7894 D BluetoothAdapterProperties: Discoverable Timeout:120
08-17 14:27:05.024  7639  7894 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
,08-17 14:27:05.042  6725  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 14:27:05.042  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:27:05.042  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 14:27:05.042  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 14:27:05.042  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 14:27:05.042  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 14:27:05.042  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 14:27:05.042  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 14:27:05.057  7639  7932 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-17 14:27:05.057  7639  7932 W bt-smp  : Plain text(LSB ~ MSB) = b5 52 7f 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-17 14:27:05.057  7639  7932 W bt-smp  : Encrypted text(LSB ~ MSB) = 4f 43 42 ce 23 7d 3c 04 f6 be 1a c6 e3 48 7a 29 
,08-17 14:27:05.059  7639  7932 W bt-btm  : Stopping oneshot timer
08-17 14:27:05.060  7639  7890 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-17 14:27:05.061  6725  6725 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 14:27:05.061  6837  7525 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-17 14:27:05.101  7639  7932 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
,08-17 14:27:05.101  7639  7932 W bt-smp  : Plain text(LSB ~ MSB) = 07 8f 77 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-17 14:27:05.101  7639  7932 W bt-smp  : Encrypted text(LSB ~ MSB) = 29 58 07 a6 f2 c9 4a ff 12 8c 22 4e 69 15 43 9e 
08-17 14:27:05.101  7639  7932 W bt-btm  : Stopping oneshot timer
,08-17 14:27:05.109  7965  7965 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-17 14:27:05.117  7639  7932 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
,08-17 14:27:05.117  7639  7932 W bt-smp  : Plain text(LSB ~ MSB) = bc a8 74 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-17 14:27:05.117  7639  7932 W bt-smp  : Encrypted text(LSB ~ MSB) = 25 b8 f8 5f 76 97 7d 2f ca f2 9c 7d 64 43 a0 5e 
08-17 14:27:05.117  7639  7932 W bt-btm  : Stopping oneshot timer
08-17 14:27:05.129  7639  7932 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-17 14:27:05.129  7639  7932 W bt-smp  : Plain text(LSB ~ MSB) = e4 87 4b 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-17 14:27:05.129  7639  7932 W bt-smp  : Encrypted text(LSB ~ MSB) = 7b 08 7b ed 17 b2 a4 1e da e4 f9 91 0f 60 0b 58 
08-17 14:27:05.129  7639  7932 W bt-btm  : Stopping oneshot timer
,08-17 14:27:05.217  1036  1103 I art     : Explicit concurrent mark sweep GC freed 28191(1383KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 2.526ms total 140.553ms
,08-17 14:27:05.219  6837  6853 D BluetoothPbap: onBluetoothStateChange: up=true
08-17 14:27:05.222  1839  1855 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 14:27:05.223  1839  2394 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 14:27:05.223  1839  1839 D BluetoothHeadset: Proxy object connected
08-17 14:27:05.224  6837  6837 D BluetoothHeadset: Proxy object connected
08-17 14:27:05.224  6837  6837 D HeadsetProfile: Bluetooth service connected
08-17 14:27:05.225  1839  1839 D BluetoothHeadset: Proxy object connected
08-17 14:27:05.229  6837  7525 D BluetoothA2dp: onBluetoothStateChange: up=true
08-17 14:27:05.232  6837  6852 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-17 14:27:05.236  6837  7525 D BluetoothPan: onBluetoothStateChange on: true
08-17 14:27:05.236  6837  7525 D BluetoothPan: onBluetoothStateChange call bindService
08-17 14:27:05.236  6837  6837 D BluetoothA2dp: Proxy object connected
08-17 14:27:05.236  6837  6837 D A2dpProfile: Bluetooth service connected
08-17 14:27:05.240  1036  1103 D BluetoothA2dp: onBluetoothStateChange: up=true
08-17 14:27:05.242  1839  1855 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 14:27:05.242  1036  1036 D BluetoothA2dp: Proxy object connected
08-17 14:27:05.243  6837  6837 D BluetoothInputDevice: Proxy object connected
08-17 14:27:05.243  6837  6837 D HidProfile: Bluetooth service connected
08-17 14:27:05.245  6837  6837 D BluetoothPan: BluetoothPAN Proxy object connected
08-17 14:27:05.245  6837  6837 D PanProfile: Bluetooth service connected
08-17 14:27:05.245  1839  1839 D BluetoothHeadset: Proxy object connected
,08-17 14:27:05.246  6837  6853 D BluetoothMap: onBluetoothStateChange: up=true
08-17 14:27:05.251  1036  1103 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 14:27:05.251  6837  6837 D BluetoothMap: Proxy object connected
08-17 14:27:05.251  6837  6837 D MapProfile: Bluetooth service connected
08-17 14:27:05.251  6837  6837 D BluetoothMap: getConnectedDevices()
08-17 14:27:05.252  7639  7655 V BluetoothMapService: getConnectedDevices()
08-17 14:27:05.252  1036  1036 D BluetoothHeadset: Proxy object connected
08-17 14:27:05.253  1036  1103 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-17 14:27:05.253  1036  1103 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-17 14:27:05.254  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-17 14:27:05.255  1036  1103 D BluetoothManagerService: Message: 40
08-17 14:27:05.255  1036  1103 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-17 14:27:05.255  1929  1929 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:27:05.256  1929  2116 D LGBluetoothAPIService: Message: 1
08-17 14:27:05.256  1590  1590 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-17 14:27:05.256  1929  2116 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-17 14:27:05.256  1929  2116 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
08-17 14:27:05.256  1929  2116 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-17 14:27:05.259  6725  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:27:05.262  7639  7639 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-17 14:27:05.262  7639  7639 D BluetoothMapService: STATE_ON
08-17 14:27:05.263  7639  7639 V BluetoothMapService: Handler(): got msg=1
08-17 14:27:05.264  7639  7639 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-17 14:27:05.265  7639  7982 D BluetoothMapMasInstance: MAS initSocket()
08-17 14:27:05.266  7639  7982 D BluetoothMapMasInstance:   masId = 00
08-17 14:27:05.266  7639  7982 D BluetoothMapMasInstance:   msgTypes = 0e
08-17 14:27:05.266  7639  7982 D BluetoothMapMasInstance:   masName = SMS/MMS
08-17 14:27:05.266  7639  7982 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-17 14:27:05.267  6837  6837 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-17 14:27:05.267  1036  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 14:27:05.269  6837  6837 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-17 14:27:05.269  7639  7982 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 14:27:05.272  7639  7982 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-17 14:27:05.273  7639  7982 V BluetoothMapMasInstance: Succeed to create listening socket 
08-17 14:27:05.273  7639  7982 D BluetoothMapMasInstance: Accepting socket connection...
,08-17 14:27:05.274  7639  7894 D BluetoothAdapterProperties: Scan Mode:21
08-17 14:27:05.274  7639  7894 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-17 14:27:05.275  7639  7639 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6399fbd
08-17 14:27:05.275  7639  7639 V BluetoothPbapService: Pbap Service onCreate
08-17 14:27:05.275  7639  7639 V BluetoothPbapService: Starting PBAP service
08-17 14:27:05.276  7639  7639 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-17 14:27:05.277  7639  7639 V BluetoothPbapService: Pbap Service onBind
08-17 14:27:05.278  6725  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:27:05.279  7639  7639 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:27:05.279  7639  7639 V BluetoothPbapService: state: 12
08-17 14:27:05.279  7639  7639 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-17 14:27:05.279  7639  7639 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:27:05.279  7639  7639 V BluetoothPbapReceiver: ***********state = 12
08-17 14:27:05.281  7639  7639 V BluetoothPbapService: Handler(): got msg=1
08-17 14:27:05.281  7639  7639 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-17 14:27:05.283  7639  7985 V BluetoothPbapService: Pbap Service initSocket
08-17 14:27:05.283  1036  1875 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 14:27:05.283  6837  6837 D DockEventReceiver: finishStartingService: stopping service
08-17 14:27:05.284  7639  7985 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 14:27:05.284  6837  6837 D BluetoothPbap: Proxy object connected
08-17 14:27:05.284  6837  6837 D PbapServerProfile: Bluetooth service connected
08-17 14:27:05.285  2162  2162 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-17 14:27:05.285  7639  7985 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-17 14:27:05.285  7639  7985 V BluetoothPbapService: Succeed to create listening socket 
08-17 14:27:05.285  7639  7985 V BluetoothPbapService: Accepting socket connection...
08-17 14:27:05.285  2162  2162 D c       : Getting all permits...
08-17 14:27:05.285  2162  2162 D a       : Opening database...
,08-17 14:27:05.290  2162  2162 D a       : Opening database auth.proximity.permit_store...
08-17 14:27:05.291  2162  2162 D a       : Closing database...
08-17 14:27:05.301  6837  6837 D BluetoothPermissionRequest: onReceive
,08-17 14:27:05.303  6837  6837 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-17 14:27:05.305  6837  6837 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-17 14:27:05.308  7639  7639 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-17 14:27:05.309  7639  7639 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-17 14:27:05.313  7639  7639 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-17 14:27:05.328  7639  7639 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-17 14:27:05.328  7639  7639 V BtOppService: onCreate
,08-17 14:27:05.332  7639  7639 V BluetoothOppNotification: send message
08-17 14:27:05.334  7639  7639 V BtOppService: Starting RfcommListener
08-17 14:27:05.340  7639  7639 D BluetoothOppPreference: Dumping Names:  
08-17 14:27:05.340  7639  7639 D BluetoothOppPreference: {}
08-17 14:27:05.340  7639  7639 D BluetoothOppPreference: Dumping Channels:  
08-17 14:27:05.340  7639  7639 D BluetoothOppPreference: {}
08-17 14:27:05.342  7639  7639 V BtOppService: onStartCommand
,08-17 14:27:05.345  7639  7992 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-17 14:27:05.348  7639  7639 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:27:05.348  7639  7639 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-17 14:27:05.352  7639  7639 V BluetoothOppNotification: new notify threadi!
08-17 14:27:05.354  7639  7639 V BluetoothOppNotification: send delay message
,08-17 14:27:05.355  7639  7639 V BtOppService: start RfcommListener
,08-17 14:27:05.358  7639  7989 V BtOppService: Deleted complete outbound shares, number =  0
,08-17 14:27:05.359  7639  7989 V BtOppService: Deleted complete inbound failed shares, number = 0
08-17 14:27:05.360  7639  7989 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-17 14:27:05.360  7639  7992 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-17 14:27:05.361  7639  7989 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@281c4b09 on behalf of 
08-17 14:27:05.361  7639  7639 V BtOppService: RfcommListener started
08-17 14:27:05.364  7639  7993 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-17 14:27:05.364  7639  7994 V BtOppRfcommListener: Starting RFCOMM listener....
08-17 14:27:05.365  7639  7992 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@4dee10e on behalf of 
08-17 14:27:05.365  1036  1928 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-17 14:27:05.368  7639  7994 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 14:27:05.369  7639  7992 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-17 14:27:05.370  7639  7993 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1a4c472f on behalf of 
08-17 14:27:05.370  7639  7994 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
08-17 14:27:05.370  7639  7994 V BtOppRfcommListener: Started RFCOMM listener....
08-17 14:27:05.370  7639  7994 I BtOppRfcommListener: Accept thread started.
08-17 14:27:05.370  7639  7994 V BtOppRfcommListener: Accepting connection...
08-17 14:27:05.375  7639  7993 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-17 14:27:05.377  7639  7993 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-17 14:27:05.379  7639  7993 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2d84d13c on behalf of 
,08-17 14:27:05.382  7639  7993 V BluetoothOppNotification: outbound: succ-0  fail-0
08-17 14:27:05.384  7639  7639 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6399fbd
08-17 14:27:05.385  7639  7639 V BluetoothFtpService: Ftp Service onCreate
08-17 14:27:05.385  7639  7639 I BluetoothFtpService: Ftp Service onCreate
08-17 14:27:05.385  7639  7639 V BluetoothFtpService: Ftp Service onStartCommand
08-17 14:27:05.385  7639  7639 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:27:05.385  7639  7639 V BluetoothFtpService: Starting Listening on sockets
08-17 14:27:05.386  7639  7639 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-17 14:27:05.386  7639  7639 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-17 14:27:05.387  7639  7639 V BluetoothSapReceiver: SapReceiver onReceive 
08-17 14:27:05.387  7639  7639 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:27:05.387  7639  7639 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-17 14:27:05.387  7639  7639 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-17 14:27:05.387  7639  7993 V BluetoothOppNotification: outbound notification was removed.
08-17 14:27:05.387  7639  7993 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-17 14:27:05.389  7639  7993 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@52c001a on behalf of 
08-17 14:27:05.389  7639  7993 V BluetoothOppNotification: inbound: succ-0  fail-0
08-17 14:27:05.391  7639  7639 V BtOppService: ContentObserver received notification
08-17 14:27:05.391  7639  7639 V BtOppService: ContentObserver received notification
08-17 14:27:05.391  7639  7639 V BluetoothFtpService: Handler(): got msg=1
,08-17 14:27:05.392  7639  7993 V BluetoothOppNotification: inbound notification was removed.
08-17 14:27:05.392  7639  7993 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-17 14:27:05.392  7639  7639 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-17 14:27:05.393  7639  7639 V BluetoothFtpService: Ftp Service initSocket
,08-17 14:27:05.395  7639  7995 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-17 14:27:05.395  7639  7995 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-17 14:27:05.396  7639  7993 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@9e0274b on behalf of 
08-17 14:27:05.396  7639  7995 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2f6bc528 on behalf of 
08-17 14:27:05.397  7639  7995 V BluetoothOppNotification: update too frequent, put in queue
08-17 14:27:05.399  7639  7995 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-17 14:27:05.400  1036  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 14:27:05.402  7639  7639 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 14:27:05.403  7639  7639 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=79
,08-17 14:27:05.404  7639  7639 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-17 14:27:05.406  7639  7996 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-17 14:27:05.433  7639  7639 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6399fbd
08-17 14:27:05.433  7639  7639 V BluetoothSapService: Sap Service onCreate
,08-17 14:27:05.436  7639  7639 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:27:05.436  7639  7639 V BluetoothSapService: state: 12
08-17 14:27:05.436  7639  7639 V BluetoothSapService: Starting SAP server process
08-17 14:27:05.439  7639  7639 V BluetoothSapService: SAP Service startRfcommListenerThread
08-17 14:27:05.427  7997  7997 W sapd    : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 14:27:05.427  7997  7997 W sapd    : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 14:27:05.442  7639  7998 V BluetoothSapService: Sap Service initRfcommSocket
08-17 14:27:05.446  1036  1875 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 14:27:05.448  7639  7998 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 14:27:05.451  7639  7998 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-17 14:27:05.451  7639  7998 V BluetoothSapService: Succeed to create listening socket 
08-17 14:27:05.451  7639  7998 V BluetoothSapService: Accepting socket connection...
08-17 14:27:05.455  7997  7997 V BT_SAP  : Event pipe created
08-17 14:27:05.455  7997  7997 V BT_SAP  : create_server_socket qcom.sap.server
08-17 14:27:05.455  7997  7997 V BT_SAP  : created socket fd 6
08-17 14:27:05.709  6725  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 14:27:05.709  6725  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:27:05.709  6725  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 14:27:05.709  6725  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 14:27:05.709  6725  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 14:27:05.709  6725  6786 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 14:27:05.709  6725  6786 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 14:27:05.709  6725  6786 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 14:27:05.712  6725  6786 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 14:27:05.715  6725  6786 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 14:27:05.715  6725  6786 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3aa3cdb3 added. We now have 8 listener(s)
08-17 14:27:05.715  6725  6786 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 14:27:05.720  1036  2036 D WifiServiceImplEx: setWifiEnabled: false pid=6725, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-17 14:27:05.720  1036  2036 D WifiService: setWifiEnabled: false pid=6725, uid=10118
08-17 14:27:05.720  1036  2036 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-17 14:27:05.726  6725  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:27:05.728  1036  1909 D WifiServiceImplEx: setWifiEnabled: true pid=6725, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-17 14:27:05.729  1036  1909 D WifiService: setWifiEnabled: true pid=6725, uid=10118
08-17 14:27:05.729  1036  1909 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-17 14:27:05.746  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-17 14:27:05.746  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-17 14:27:05.746  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-17 14:27:05.748  1036  1523 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-17 14:27:05.748  1036  1523 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-17 14:27:05.750  1036  1523 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-17 14:27:05.750  1036  1523 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-17 14:27:05.750  1036  1523 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-17 14:27:05.751  1036  1523 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-17 14:27:05.751  1036  1523 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-17 14:27:05.751  1036  1523 E WifiHW  : unknown target_country: EU , set to default
08-17 14:27:05.751  1036  1523 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-17 14:27:05.751  1036  1523 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-17 14:27:05.751  1036  1523 I WifiUtil: gEnableBmps=1
08-17 14:27:06.344   331   894 D SoftapController: Softap fwReload - Ok
,08-17 14:27:06.362  7639  7639 V BluetoothOppNotification: new notify threadi!
08-17 14:27:06.362  7639  7639 V BluetoothOppNotification: send delay message
,08-17 14:27:06.385  1036  1103 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-17 14:27:06.387  1036  1523 E NetdConnector: NDC Command {83 softap fwreload wlan0 STA} took too long (630ms)
08-17 14:27:06.408   331   894 D CommandListener: Setting iface cfg
08-17 14:27:06.408   331   894 D CommandListener: Trying to bring down wlan0
,08-17 14:27:06.415   331   894 D CommandListener: Clearing all IP addresses on wlan0
08-17 14:27:06.435  1036  1523 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,08-17 14:27:06.463  7639  8018 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-17 14:27:06.457  8019  8019 W wpa_supplicant: type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 14:27:06.457  8019  8019 W wpa_supplicant: type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 14:27:06.466  1036  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-17 14:27:06.466  1036  1523 E WifiStateMachine: useWiFiOffloading() : false
08-17 14:27:06.466  1036  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-17 14:27:06.480  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-17 14:27:06.482  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 14:27:06.483  1929  1929 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-17 14:27:06.485  6725  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:27:06.490  1036  1523 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-17 14:27:06.490  1036  1523 D WifiMonitor: connecting to supplicant
08-17 14:27:06.493  6837  6837 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-17 14:27:06.493  6837  6837 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-17 14:27:06.494  6837  6837 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-17 14:27:06.494  6837  6837 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-17 14:27:06.494  6837  6837 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-17 14:27:06.495  6837  6837 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-17 14:27:06.495  6837  6837 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-17 14:27:06.495  6837  6837 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-17 14:27:06.495  6837  6837 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-17 14:27:06.495  6837  6837 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-17 14:27:06.495  6837  6837 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-17 14:27:06.496  6837  6837 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-17 14:27:06.498  8019  8019 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-17 14:27:06.508  7639  8018 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@24c0bd4 on behalf of 
08-17 14:27:06.510  7639  8018 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-17 14:27:06.511  7639  8018 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,08-17 14:27:06.513  7639  8018 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1ff3d17d on behalf of 
08-17 14:27:06.515  7639  8018 V BluetoothOppNotification: outbound: succ-0  fail-0
08-17 14:27:06.519  7639  8018 V BluetoothOppNotification: outbound notification was removed.
08-17 14:27:06.519  7639  8018 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-17 14:27:06.521  7639  8018 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@28527872 on behalf of 
08-17 14:27:06.523  7639  8018 V BluetoothOppNotification: inbound: succ-0  fail-0
08-17 14:27:06.526  7639  8018 V BluetoothOppNotification: inbound notification was removed.
08-17 14:27:06.526  7639  8018 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-17 14:27:06.528  7639  8018 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@25fc34c3 on behalf of 
,08-17 14:27:06.534  8019  8019 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-17 14:27:06.534  8019  8019 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
08-17 14:27:06.537  1036  1103 D Tethering: InitialState.processMessage what=4
08-17 14:27:06.547  1036  1928 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8036 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-17 14:27:06.551  1036  1103 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-17 14:27:06.626  8019  8019 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-17 14:27:06.664  1036  2001 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8057 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-17 14:27:06.669  8019  8019 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
08-17 14:27:06.672  8036  8055 W FormManager: Network not available. Please check & try again.
08-17 14:27:06.676  8019  8019 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-17 14:27:06.676  8019  8019 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
,08-17 14:27:06.677  1036  1523 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-17 14:27:06.677  1036  1523 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-17 14:27:06.678  1036  1523 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-17 14:27:06.678  1036  1523 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-17 14:27:06.679  1036  1523 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-17 14:27:06.679  1036  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-17 14:27:06.679  1036  1523 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-17 14:27:06.680  1036  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-17 14:27:06.680  1036  1523 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-17 14:27:06.680  1036  1523 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-17 14:27:06.681  1036  1523 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-17 14:27:06.681  1036  1523 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-17 14:27:06.681  1036  1523 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-17 14:27:06.682  1036  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-17 14:27:06.682  1036  1523 E WifiStateMachine: useWiFiOffloading() : false
08-17 14:27:06.682  1036  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-17 14:27:06.682  1036  8073 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-17 14:27:06.682  1036  8073 D WifiMonitor: Dropping event because (p2p0) is stopped
08-17 14:27:06.682  1036  8073 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-17 14:27:06.682  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:27:06.682  1036  8073 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-17 14:27:06.682  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:27:06.682  1036  8073 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-17 14:27:06.682  1036  8073 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-17 14:27:06.682  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:27:06.682  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:27:06.682  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-17 14:27:06.685  1036  1523 D WifiNative-wlan0: doBoolean: SET update_config 1
08-17 14:27:06.686  1036  1523 D WifiNative-wlan0: SET update_config 1: returned true
08-17 14:27:06.686  1036  1523 D WifiConfigStore: Loading config and enabling all networks 
08-17 14:27:06.686  1036  1523 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-17 14:27:06.686  1929  1929 D WfdService: Waiting for WifiP2p enabling
08-17 14:27:06.686  1036  1523 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-17 14:27:06.688  8036  8056 V FormManager: Network unavailable.
08-17 14:27:06.688  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-17 14:27:06.690  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
,08-17 14:27:06.690  1036  1528 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-17 14:27:06.691  8036  8056 V FormManager: Network unavailable.
08-17 14:27:06.692  6725  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 14:27:06.692  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:27:06.692  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 14:27:06.692  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:27:06.692  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 14:27:06.692  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 14:27:06.692  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 14:27:06.692  6725  6725 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 14:27:06.694  6725  6725 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-17 14:27:06.698  1036  1523 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-17 14:27:06.708  1036  1523 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-17 14:27:06.708  1036  1523 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-17 14:27:06.710  1036  1523 D WifiStateMachine: enableVerboseLogging : level 2
08-17 14:27:06.710  1036  1523 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-17 14:27:06.711  1036  1523 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-17 14:27:06.711  1036  1523 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-17 14:27:06.711  1036  1523 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-17 14:27:06.711  1036  1523 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-17 14:27:06.712  1036  2001 I ActivityManager: Killing 7120:com.lge.drmservice/u0a62 (adj 15): empty #17
08-17 14:27:06.712  1036  1523 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-17 14:27:06.712  1036  1523 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-17 14:27:06.713  1036  1523 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-17 14:27:06.713  1036  1523 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-17 14:27:06.713  1036  1523 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-17 14:27:06.713  1036  1523 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-17 14:27:06.713  1036  1523 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-17 14:27:06.713  1036  1523 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-17 14:27:06.714  1036  1523 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-17 14:27:06.737  1036  1523 D WifiStateMachine: Setting OUI to DA-A1-19
08-17 14:27:06.737  1036  1523 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-17 14:27:06.737  1036  1523 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-17 14:27:06.737  1036  1523 D WifiNative-HAL: Setting external_sim to 1
,08-17 14:27:06.738  1036  1523 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-17 14:27:06.738  1036  1523 D WifiNative-wlan0: SET external_sim 1: returned true
08-17 14:27:06.738  1036  1523 I WifiNative-HAL: startHal
08-17 14:27:06.738  1036  1523 D wifi    : setting scan oui 0x95331c40
08-17 14:27:06.738  1036  1523 D WifiStateMachine: Setting OUI to DA-A1-19
08-17 14:27:06.738  1036  1523 I WifiNative-HAL: startHal
08-17 14:27:06.738  1036  1523 D wifi    : setting scan oui 0x95331c40
08-17 14:27:06.739  1036  1523 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-17 14:27:06.739  1036  1523 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-17 14:27:06.739  1036  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-17 14:27:06.739  8019  8019 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-17 14:27:06.739  1036  1523 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-17 14:27:06.740  1036  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-17 14:27:06.740  8019  8019 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-17 14:27:06.740  1036  1523 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-17 14:27:06.740  1036  1946 W libprocessgroup: failed to open /acct/uid_10062/pid_7120/cgroup.procs: No such file or directory
08-17 14:27:06.740  1036  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-17 14:27:06.740  8019  8019 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-17 14:27:06.741  1036  1523 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-17 14:27:06.741  1036  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-17 14:27:06.741  8019  8019 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-17 14:27:06.741  1036  1523 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-17 14:27:06.741  1036  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-17 14:27:06.741  8019  8019 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-17 14:27:06.742  1036  1523 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-17 14:27:06.742  1036  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-17 14:27:06.742  8019  8019 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-17 14:27:06.742  1036  1523 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-17 14:27:06.742  1036  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-17 14:27:06.742  8019  8019 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
,08-17 14:27:06.743  1929  1929 D WfdsService: Supplicant Connection state is changed : true
08-17 14:27:06.743  1929  2234 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-17 14:27:06.743  1929  2234 D WfdsService: Set the WFDS Monitor: true
08-17 14:27:06.743  1929  2234 D WfdsMonitor: WfdsMonitorThread create
08-17 14:27:06.743  1929  2234 D WfdsMonitor: WFDS Monitor is created and started
08-17 14:27:06.743  1929  2234 D WfdsService: WiFi: Supplicant connection re-established
08-17 14:27:06.743  1036  1523 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-17 14:27:06.743  7720  7720 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:27:06.744  1929  8078 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-17 14:27:06.744  1036  1523 E WifiNative: : [348,494,427 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-17 14:27:06.744  1036  1523 D WifiNative-wlan0: doBoolean: RECONNECT
08-17 14:27:06.744  1036  1523 D WifiNative-wlan0: RECONNECT: returned true
08-17 14:27:06.744  1929  8078 E CtrlSupplicant: Succeed to open control connection
08-17 14:27:06.744  1036  1523 D WifiNative-wlan0: doString: [STATUS]
08-17 14:27:06.745  1929  8078 E CtrlSupplicant: Succeed to open monitor connection
08-17 14:27:06.745  1036  8073 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-17 14:27:06.745  1036  8073 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-17 14:27:06.745  1036  1523 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
,08-17 14:27:06.745  1036  1523 D WifiNative-wlan0: doBoolean: SET ps 1
08-17 14:27:06.745  1929  8078 D WfdsMonitor: Supplicant connection established
08-17 14:27:06.745  1929  2234 D WfdsService: Connected to the supplicant for wfds
08-17 14:27:06.745  1036  1523 D WifiNative-wlan0: SET ps 1: returned true
08-17 14:27:06.745  1036  1522 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:27:06.746  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 3
08-17 14:27:06.746  1036  1036 D RttService: SCAN_AVAILABLE : 3
08-17 14:27:06.746  1036  1542 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:27:06.746  1036  1541 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:27:06.746  1036  1541 I WifiNative-HAL: startHal
08-17 14:27:06.746  1036  1541 D wifi    : getting scan capabilities on interface[1] = 0x95331c40
08-17 14:27:06.746  1036  1541 D wifi    : failed to get capabilities : -3
08-17 14:27:06.746  1036  1541 E WifiScanningService: could not get scan capabilities
08-17 14:27:06.747   331   894 D CommandListener: Setting iface cfg
08-17 14:27:06.747   331   894 D CommandListener: Trying to bring up p2p0
08-17 14:27:06.747  1036  1522 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-17 14:27:06.747  1036  1522 D LGWifiP2pService: P2pEnablingState
08-17 14:27:06.747  1036  1522 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:27:06.747  1036  1522 D LGWifiP2pService: P2p socket connection successful
08-17 14:27:06.747  1036  1522 D LGWifiP2pService: P2pEnabledState
08-17 14:27:06.747  1036  1523 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-17 14:27:06.747  1036  1522 D LGWifiP2pService: sending p2p connection changed broadcast
08-17 14:27:06.748  1036  1523 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-17 14:27:06.748  1929  1929 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-17 14:27:06.748  1929  1929 D WfdsService: WifiP2pState is changed : true
08-17 14:27:06.748  1036  1523 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-17 14:27:06.748  1929  2234 D WfdsService: Receive the WFDS_ENABLE Method
08-17 14:27:06.748  1929  2234 D WfdsService: Set the WFDS Monitor: true
08-17 14:27:06.748  1929  2234 D WfdsService: Connected to the supplicant for wfds
08-17 14:27:06.748  1929  2234 D WfdsJNI : doCommand: WFDS_SET TRUE
08-17 14:27:06.748  8019  8019 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-17 14:27:06.749  1929  2234 D WfdsService: selectPreferredScanChannel [36]
08-17 14:27:06.749  1929  2234 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-17 14:27:06.749  1036  1523 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-17 14:27:06.749  1036  1523 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-17 14:27:06.750  1036  1523 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-17 14:27:06.750  1036  1523 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-17 14:27:06.750  1036  1523 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-17 14:27:06.750  8019  8019 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-17 14:27:06.750  1036  1522 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-17 14:27:06.751  1036  1522 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-17 14:27:06.751  1036  1522 D WifiNative-p2p0: doBoolean: SET device_name G3
08-17 14:27:06.751  1036  1522 D WifiNative-p2p0: SET device_name G3: returned true
08-17 14:27:06.751  1036  1522 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-17 14:27:06.751  1036  1522 D LGWifiP2pService: before postfix = G3
08-17 14:27:06.751  1036  1522 D WifiServerServiceExt: postfix byte check : 2
08-17, 14:27:06.751  1036  1522 D LGWifiP2pService: after postfix = G3
08-17 14:27:06.751  1036  1522 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-17 14:27:06.752  1036  1522 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-17 14:27:06.752  1036  1522 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-17 14:27:06.752  1036  1522 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-17 14:27:06.752  1036  1522 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-17 14:27:06.752  1036  1522 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-17 14:27:06.752  1036  1522 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-17 14:27:06.753  1036  1522 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-17 14:27:06.753  1036  1522 D WifiNative-HAL: p2pGetDeviceAddress
08-17 14:27:06.753  1036  1522 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
,08-17 14:27:06.754  1929  1929 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-17 14:27:06.755  1929  1929 D WfdsService: isConnected: false
,08-17 14:27:06.755  1036  1522 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-17 14:27:06.755  1036  1522 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-17 14:27:06.755  1929  1929 I WfdStateTracker: handleP2pThisDeviceChanged
08-17 14:27:06.755  1929  1929 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-17 14:27:06.755  1929  1929 D WfdsService: Update P2p Interface State: 3
08-17 14:27:06.755  1036  1522 D WifiNative-p2p0: P2P_FLUSH: returned true
08-17 14:27:06.755  1036  1522 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-17 14:27:06.755  1036  1522 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-17 14:27:06.755  1036  1522 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-17 14:27:06.756  1036  1522 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-17 14:27:06.756  1036  1522 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-17 14:27:06.757  1036  1523 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-17 14:27:06.757  1036  1523 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-17 14:27:06.758  1036  1523 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-17 14:27:06.758  1036  1523 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-17 14:27:06.760  6725  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 14:27:06.760  6725  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:27:06.760  6725  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 14:27:06.760  6725  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:27:06.760  6725  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 14:27:06.760  6725  6786 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 14:27:06.760  6725  6786 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 14:27:06.760  6725  6786 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 14:27:06.761  6725  6786 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-17 14:27:06.765  8019  8019 E wpa_supplicant: disconnect_rssi_lvl: -100
,08-17 14:27:06.765  1036  1522 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-17 14:27:06.765  1036  1522 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-17 14:27:06.765  1036  1522 D LGWifiP2pService: InactiveState
08-17 14:27:06.765  1036  1522 D LGWifiP2pService: InactiveState{ when=-10ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:27:06.765  1036  1522 D LGWifiP2pService: P2pEnabledState{ when=-10ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:27:06.765  1036  1522 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-17 14:27:06.766  6725  6786 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-17 14:27:06.766  8019  8019 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
,08-17 14:27:06.767  8019  8019 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-17 14:27:06.767  6725  6786 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-17 14:27:06.767  8019  8019 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-17 14:27:06.767  8019  8019 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 14:27:06.768  1036  8073 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-17 14:27:06.768  1036  8073 E WifiMonitor: WifiMonitor:p2p0 cnt=46 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,08-17 14:27:06.768  1036  8073 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-17 14:27:06.768  8019  8019 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 14:27:06.768  1036  8073 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-17 14:27:06.768  1036  8073 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-17 14:27:06.768  1036  8073 E WifiMonitor: WifiMonitor:p2p0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 14:27:06.768  1036  8073 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 14:27:06.768  1036  8073 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 14:27:06.768  1036  8073 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-17 14:27:06.768  1036  8073 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 14:27:06.768  1036  8073 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 14:27:06.768  1036  8073 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 14:27:06.769  6725  6786 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@73fc398 Bundle[{}]
08-17 14:27:06.769  1929  8078 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
,08-17 14:27:06.769  1929  8078 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-17 14:27:06.769  1929  8078 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-17 14:27:06.769  1036  1522 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-17 14:27:06.769  1036  1522 D LGWifiP2pService: InactiveState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:27:06.769  1036  1522 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:27:06.769  1036  1522 D LGWifiP2pService: DefaultState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:27:06.769  6725  6786 I io.jxcore.node.LifeCycleMonitor: start: OK
08-17 14:27:06.769  1036  1522 D LGWifiP2pService: InactiveState{ when=-4ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:27:06.769  1036  1522 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:27:06.769  1036  1522 D LGWifiP2pService: DefaultState{ when=-4ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:27:06.769  6725  6786 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-17 14:27:06.769  1036  1036 E WifiServerServiceExt: No p2p device connected
08-17 14:27:06.770  1036  1522 D LGWifiP2pService: InactiveState{ when=-5ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
,08-17 14:27:06.770  1036  1522 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:27:06.770  1036  1522 D LGWifiP2pService: DefaultState{ when=-5ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:27:06.770  6725  6786 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-17 14:27:06.770  1036  1523 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-17 14:27:06.771  1036  1523 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-17 14:27:06.771  6725  6786 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-17 14:27:06.771  1036  1523 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-17 14:27:06.771  1036  1523 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-17 14:27:06.771  6725  6786 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-17 14:27:06.772  8019  8019 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-17 14:27:06.772  6725  6786 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-17 14:27:06.772  8019  8019 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-17 14:27:06.772  1036  8073 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-17 14:27:06.772  1036  8073 E WifiMonitor: WifiMonitor:wlan0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-17 14:27:06.772  1036  8073 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-17 14:27:06.772  1036  8073 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-17 14:27:06.773  8019  8019 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-17 14:27:06.773  8019  8019 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 14:27:06.773  1929  8078 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-17 14:27:06.773  1036  1522 D LGWifiP2pService: InactiveState{ when=-8ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:27:06.773  1036  1522 D LGWifiP2pService: P2pEnabledState{ when=-8ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:27:06.773  1036  8073 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,08-17 14:27:06.773  1036  1522 D LGWifiP2pService: DefaultState{ when=-8ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:27:06.773  1036  8073 E WifiMonitor: WifiMonitor:p2p0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 14:27:06.773  1036  8073 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 14:27:06.773  1036  8073 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 14:27:06.773  1929  2234 W WfdsService: DefaultState - msg [9441285] is not handled
08-17 14:27:06.773  8019  8019 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 14:27:06.773  1036  8073 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-17 14:27:06.773  1036  1523 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-17 14:27:06.773  1036  8073 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 14:27:06.773  1036  8073 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 14:27:06.774  1036  8073 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 14:27:06.774  1036  1523 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-17 14:27:06.774  1929  8078 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-17 14:27:06.774  1036  1523 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-17 14:27:06.774  1036  1522 D LGWifiP2pService: InactiveState{ when=-1ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:27:06.774  1036  1522 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:27:06.774  1036  1523 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-17 14:27:06.774  1036  1523 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-17 14:27:06.775  8019  8019 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-17 14:27:06.775  8019  8019 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-17 14:27:06.775  1036  8073 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-17 14:27:06.775  1036  8073 E WifiMonitor: WifiMonitor:wlan0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-17 14:27:06.775  1036  8073 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-17 14:27:06.775  1036  8073 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-17 14:27:06.775  1036  1523 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-17 14:27:06.775  1036  1523 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
,08-17 14:27:06.775  8057  8057 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-17 14:27:06.776  1036  1523 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-17 14:27:06.779  6725  6786 I System.out: Running OutgoingSocketThread
08-17 14:27:06.779  6837  6837 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-17 14:27:06.779  1036  1523 D WifiNative-wlan0: doBoolean: SCAN
08-17 14:27:06.780  1036  1523 D WifiNative-wlan0: SCAN: returned false
08-17 14:27:06.780  1036  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=348531  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-17 14:27:06.782  1036  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=348533  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-17 14:27:06.782  1036  1523 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-17 14:27:06.783  1036  1523 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-17 14:27:06.783  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 14:27:06.783  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-17 14:27:06.783  1036  1523 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-17 14:27:06.784  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:27:06.784  6725  8081 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 872)
08-17 14:27:06.784  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:27:06.784  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-17 14:27:06.784  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 14:27:06.785  1036  1523 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-17 14:27:06.785  6725  8081 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 60452
08-17 14:27:06.785  6725  8081 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-17 14:27:06.785  1036  1523 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-17 14:27:06.786  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-17 14:27:06.786  1036  1036 D WifiServerServiceExt: setSupplicantStateSCANNING
08-17 14:27:06.787  6837  6837 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 14:27:06.788  1036  1928 I ActivityManager: Killing 7139:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
08-17 14:27:06.817  1036  1875 W libprocessgroup: failed to open /acct/uid_10085/pid_7139/cgroup.procs: No such file or directory
,08-17 14:27:06.829  6837  6837 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-17 14:27:06.829  6837  6837 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
,08-17 14:27:06.829  6837  6837 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-17 14:27:06.829  6837  6837 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-17 14:27:06.830  6837  6837 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-17 14:27:06.830  6837  6837 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-17 14:27:06.830  6837  6837 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-17 14:27:06.830  6837  6837 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-17 14:27:06.830  6837  6837 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-17 14:27:06.830  6837  6837 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-17 14:27:06.831  6837  6837 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-17 14:27:06.836  8057  8057 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-17 14:27:06.840  6837  6837 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-17 14:27:06.842  8036  8083 W FormManager: Network not available. Please check & try again.
08-17 14:27:06.845  6837  6837 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 14:27:06.857  8036  8084 V FormManager: Network unavailable.
,08-17 14:27:06.861  4312  4312 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-17 14:27:06.862  4312  4312 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-17 14:27:06.863  8036  8084 V FormManager: Network unavailable.
08-17 14:27:06.869  4312  4312 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-17 14:27:06.873  4312  4312 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-17 14:27:06.880  4312  8085 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-17 14:27:06.883  4312  8086 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-17 14:27:06.884  4312  8086 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-17 14:27:06.936  1036  1638 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8087 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-17 14:27:07.067  8087  8087 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-17 14:27:07.068  8087  8087 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-17 14:27:07.076  8087  8087 V [BNRBootReceiver]: Boot Receiver Return
08-17 14:27:07.077  8087  8087 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-17 14:27:07.127  1036  1052 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8108 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-17 14:27:07.128  1036  1052 I ActivityManager: Killing 7166:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,08-17 14:27:07.240  1036  1640 W libprocessgroup: failed to open /acct/uid_10093/pid_7166/cgroup.procs: No such file or directory
,08-17 14:27:07.292  8108  8108 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-17 14:27:07.332  8108  8108 D PluginManager: init()
,08-17 14:27:07.368  1036  8073 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-17 14:27:07.368  1036  8073 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-17 14:27:07.368  8019  8019 E wpa_supplicant: USIM:  scard_init function
08-17 14:27:07.368  1036  8073 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-17 14:27:07.368  1036  8073 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: WPS-AP-AVAILABLE 
08-17 14:27:07.368  1036  8073 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-17 14:27:07.369  8019  8019 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-17 14:27:07.369  1036  1523 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-17 14:27:07.369  1036  1523 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-17 14:27:07.370  1036  1523 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-17 14:27:07.370  1036  1523 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-17 14:27:07.370  1036  1523 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
,08-17 14:27:07.372  1036  8073 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-17 14:27:07.372  1036  8073 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-17 14:27:07.384  1036  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=349135  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-17 14:27:07.387  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:27:07.387  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:27:07.387  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-17 14:27:07.389  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 14:27:07.389  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-17 14:27:07.392  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 14:27:07.394  1036  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=349145  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-17 14:27:07.400  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:27:07.400  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:27:07.402  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-17 14:27:07.402  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-17 14:27:07.402  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATING
,08-17 14:27:07.415  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 14:27:07.415  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-17 14:27:07.416  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-17 14:27:07.480  8019  8019 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-17 14:27:07.481  1036  8073 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-17 14:27:07.481  1036  8073 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
,08-17 14:27:07.482  1036  1103 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-17 14:27:07.483  1036  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=349233  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-17 14:27:07.484  1036  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=349235  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-17 14:27:07.486  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-17 14:27:07.486  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-17 14:27:07.481  1036  8073 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-17 14:27:07.492  1036  8073 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-17 14:27:07.492  1036  8073 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-17 14:27:07.492  1036  8073 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-17 14:27:07.493  1036  1523 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
08-17 14:27:07.495  8019  8019 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-17 14:27:07.495  8019  8019 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-17 14:27:07.499  1036  8073 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-17 14:27:07.499  1036  8073 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,08-17 14:27:07.500  1036  8073 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-17 14:27:07.500  1036  8073 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-17 14:27:07.500  1036  8073 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-17 14:27:07.500  1036  8073 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-17 14:27:07.500  1036  8073 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-17 14:27:07.501  1036  8073 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-17 14:27:07.501  1036  8073 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-17 14:27:07.501  1036  8073 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-17 14:27:07.502  1036  1523 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
,08-17 14:27:07.504  1036  1523 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-17 14:27:07.506  1036  1523 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-17 14:27:07.507  1036  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-17 14:27:07.507  1036  1523 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=349258
08-17 14:27:07.508  1036  1523 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=349258
08-17 14:27:07.508  1036  1523 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=349259
08-17 14:27:07.508  1036  1523 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=349259
08-17 14:27:07.509  1036  1523 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=349260
08-17 14:27:07.510  1036  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=349260  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-17 14:27:07.512  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:27:07.512  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:27:07.513  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-17 14:27:07.512  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 14:27:07.514  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-17 14:27:07.514  1036  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=349265  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-17 14:27:07.515  1036  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=349265  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-17 14:27:07.515  1036  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=349266  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-17 14:27:07.516  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 14:27:07.517  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:27:07.517  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:27:07.517  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
,08-17 14:27:07.519  1036  1523 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=349270
08-17 14:27:07.519  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 14:27:07.519  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-17 14:27:07.519  1036  1523 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=349270
08-17 14:27:07.520  1036  1523 D WifiNative-wlan0: doString: [STATUS]
08-17 14:27:07.520  1036  8073 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-17 14:27:07.520  1036  8073 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-17 14:27:07.520  1036  1523 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-17 14:27:07.521  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 14:27:07.522  1036  1523 I WifiServiceExtension: setVHTCapabilityType  : false
08-17 14:27:07.526  1036  1523 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-17 14:27:07.526  1036  1523 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-17 14:27:07.529  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:27:07.529  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:27:07.529  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,08-17 14:27:07.532  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-17 14:27:07.532  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:27:07.532  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-17 14:27:07.537  1036  1365 V AlarmManager: RTC_WAKEUP set : Alarm{2131bd6d type 0 when 1471436821911 com.google.android.gms} when 1471436821911
08-17 14:27:07.537  1036  1523 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-17 14:27:07.537  1036  1530 D ConnectivityService: Got NetworkAgent Messenger
08-17 14:27:07.538  1036  1530 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-17 14:27:07.538  1036  1530 D ConnectivityService: NetworkAgent connected
08-17 14:27:07.538  1036  1523 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-17 14:27:07.538  1036  1523 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-17 14:27:07.538  1036  1523 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-17 14:27:07.538  1036  1523 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-17 14:27:07.539  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 14:27:07.539  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-17 14:27:07.541  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-17 14:27:07.543  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 14:27:07.543  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-17 14:27:07.544  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 14:27:07.545  1036  1523 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-17 14:27:07.545  1036  1523 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-17 14:27:07.545  1036  1523 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-17 14:27:07.545  1036  1523 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-17 14:27:07.546  1036  1523 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-17 14:27:07.550  1036  1523 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-17 14:27:07.551   331   894 D CommandListener: Setting iface cfg
08-17 14:27:07.554  1036  1523 E WifiStateMachine: Start Dhcp Watchdog 3
08-17 14:27:07.555  1036  1523 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=349305  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-17 14:27:07.555  1036  1523 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=349306  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-17 14:27:07.556  1036  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=349306  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-17 14:27:07.556  1036  8126 D DhcpStateMachine: StoppedState
08-17 14:27:07.556  1036  8126 D DhcpStateMachine: StoppedState{ when=-2ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:27:07.556  1036  8126 D DhcpStateMachine: WaitBeforeStartState
08-17 14:27:07.556  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-17 14:27:07.556  1036  1036 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
,08-17 14:27:07.557  1036  1523 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=349308  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-17 14:27:07.557  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-17 14:27:07.557  1036  1036 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-17 14:27:07.557  1036  1523 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=349308  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-17 14:27:07.559  1036  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=349310  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-17 14:27:07.560  1036  1523 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14073] from screen [on:0 period:-1736954968] gl rssi=-47 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-17 14:27:07.561  1036  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1736954967] gl rssi=-47 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-17 14:27:07.561  1036  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-17 14:27:07.564  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 14:27:07.565  1036  1530 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
08-17 14:27:07.566  1036  1523 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 14:27:07.566  1036  1523 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
,08-17 14:27:07.567  1036  1523 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 14:27:07.567  1036  1523 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 14:27:07.567  1036  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 14:27:07.568  1036  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 14:27:07.568  1036  1530 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-17 14:27:07.569  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-17 14:27:07.569  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-17 14:27:07.570  1036  1523 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=162,0,0
08-17 14:27:07.570  1036  1523 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=162,0,0
08-17 14:27:07.570  1036  1523 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-17 14:27:07.570  8019  8019 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-17 14:27:07.571  1036  1523 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-17 14:27:07.571  1036  1523 D WifiNative-wlan0: doBoolean: SET ps 0
08-17 14:27:07.571  1036  1523 D WifiNative-wlan0: SET ps 0: returned true
08-17 14:27:07.571  1036  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-17 14:27:07.571  8019  8019 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-17 14:27:07.572  1036  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-17 14:27:07.572  1036  1522 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1728554c target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:27:07.572  1036  1522 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1728554c target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:27:07.572  1036  8126 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:27:07.572  1036  8126 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-17 14:27:07.573  1036  1523 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-17 14:27:07.573  1036  1523 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-17 14:27:07.576  1036  1523 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-17 14:27:07.577   331   894 D CommandListener: Setting iface cfg
08-17 14:27:07.577   331   894 D CommandListener: Trying to bring up wlan0
08-17 14:27:07.578  1036  1523 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-17 14:27:07.579  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-17 14:27:07.579  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-17 14:27:07.579  1036  1523 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
,08-17 14:27:07.580  1036  1523 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 14:27:07.581  1036  1523 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 14:27:07.582  1036  1523 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 14:27:07.582  1036  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 14:27:07.583  1036  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 14:27:07.583  1036  1530 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-17 14:27:07.584  1036  1523 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-17 14:27:07.584  1036  1523 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-17 14:27:07.585  1036  1522 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:27:07.585  1036  1522 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:27:07.585  1036  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-17 14:27:07.585  8019  8019 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-17 14:27:07.585  1036  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-17 14:27:07.585  1036  1523 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-17 14:27:07.586  8019  8019 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-17 14:27:07.586  1036  1523 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-17 14:27:07.586  1036  1523 D WifiNative-wlan0: doBoolean: SET ps 1
08-17 14:27:07.602  1036  1523 D WifiNative-wlan0: SET ps 1: returned true
08-17 14:27:07.602  1036  1530 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-17 14:27:07.602  1036  1523 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-17 14:27:07.603  1036  1523 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-17 14:27:07.603  1036  1523 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-17 14:27:07.603  1036  1530 D ConnectivityService: ignoring duplicate network state non-change
,08-17 14:27:07.606  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:27:07.606  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:27:07.606  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-17 14:27:07.606  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 14:27:07.606  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-17 14:27:07.607  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 14:27:07.608  1036  1530 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-17 14:27:07.609  1036  1530 D ConnectivityService: Adding iface wlan0 to network 102
08-17 14:27:07.609  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:27:07.609  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:27:07.609  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-17 14:27:07.614  1929  1929 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-17 14:27:07.614  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-17 14:27:07.614  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:27:07.614  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:27:07.615  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,08-17 14:27:07.616  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-17 14:27:07.620  1036  1523 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-17 14:27:07.621  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:27:07.621  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:27:07.621  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,08-17 14:27:07.630  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 14:27:07.630  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-17 14:27:07.632  1036  1530 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-17 14:27:07.632  1036  1530 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-17 14:27:07.632  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 14:27:07.633  1036  1530 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
08-17 14:27:07.634  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 14:27:07.634   331   894 E Netd    : netlink response contains error (File exists)
08-17 14:27:07.634  1590  1590 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-17 14:27:07.634  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 14:27:07.634  1036  1530 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-17 14:27:07.635  1036  1530 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-17 14:27:07.635  1036  1530 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
08-17 14:27:07.635  1036  1530 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
08-17 14:27:07.636  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 14:27:07.636  1590  1590 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-17 14:27:07.636  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 14:27:07.639  1036  1530 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-17 14:27:07.639  1036  1530 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-17 14:27:07.639  1036  1530 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-17 14:27:07.639  1036  1530 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-17 14:27:07.639  1036  1530 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-17 14:27:07.639  1036  1530 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-17 14:27:07.639  1036  1530 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-17 14:27:07.639  1036  1530 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 14:27:07.639  1036  1530 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-17 14:27:07.639  1036  1530 D ConnectivityService: currentScore = 0, newScore = 20
08-17 14:27:07.639  1036  1530 D ConnectivityService:    accepting network in place of null
08-17 14:27:07.640  1036  1530 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 14:27:07.640  1036  8125 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 ,target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:27:07.640  1036  8125 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-17 14:27:07.640  1036  8125 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:27:07.640  1036  8125 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-17 14:27:07.641  1036  1523 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 14:27:07.642  1036  1523 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-17 14:27:07.643  1839  1839 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 14:27:07.643  1839  1839 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-17 14:27:07.644  1036  1530 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-17 14:27:07.644  1036  1530 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-17 14:27:07.644  1036  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-17 14:27:07.645  1036  1530 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-17 14:27:07.645  1036  1530 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-17 14:27:07.646  1036  1530 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-17 14:27:07.647  1036  1036 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-17 14:27:07.647  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-17 14:27:07.647  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-17 14:27:07.647  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-17 14:27:07.647   331  8135 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-17 14:27:07.647   331  8135 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-17 14:27:07.648  1036  1530 D ConnectivityService: validation of new default Network = false
08-17 14:27:07.648  1036  1530 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-17 14:27:07.648  1036  1530 D DSQN    : enableDataServiceNotify 
08-17 14:27:07.648  1036  1530 D DSQN    : start dsqn bin
,08-17 14:27:07.654  1036  1530 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-17 14:27:07.654  1036  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 14:27:07.655  1036  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-17 14:27:07.655  1036  1530 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-17 14:27:07.637  8136  8136 W dsqn    : type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 14:27:07.656  1590  2061 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-17 14:27:07.637  8136  8136 W dsqn    : type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 14:27:07.663  8136  8136 E DSQN    : DSQN ssw
08-17 14:27:07.670  1036  1521 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,08-17 14:27:07.675  1590  1590 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-17 14:27:07.676  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 14:27:07.677  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 14:27:07.695   331  8135 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-17 14:27:07.725   331   893 D LGDataListener: argv[0]=dsqncommand
08-17 14:27:07.725   331   893 D LGDataListener: argv[1]=wlan0
,08-17 14:27:07.725   331   893 D LGDataListener: argv[2]=1
,08-17 14:27:07.725   331   893 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-17 14:27:07.725  1036  1101 D DSQN    : DSQM DsqnNotification wlan0  1
08-17 14:27:07.725  1036  1101 D DSQN    : start to monitor internet connection
08-17 14:27:07.758  1036  8125 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 17 Aug 2016 12:27:07 GMT], X-Android-Received-Millis=[1471436827757], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1471436827724]}
08-17 14:27:07.758  1036  8125 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-17 14:27:07.759  1036  8125 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-17 14:27:07.759  1036  1530 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
,08-17 14:27:07.759  1036  1530 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-17 14:27:07.760  1036  1530 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-17 14:27:07.760  1036  1530 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-17 14:27:07.760  1036  1530 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-17 14:27:07.760  1036  1530 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-17 14:27:07.760  1036  1530 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-17 14:27:07.760  1036  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 14:27:07.761  1036  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-17 14:27:07.762  1036  1530 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-17 14:27:07.763  1590  2061 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-17 14:27:07.764  1036  1530 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 14:27:07.765  1036  1523 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 14:27:07.765  1036  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-17 14:27:07.765  1036  1523 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-17 14:27:07.766  1839  1839 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 14:27:07.766  1839  1839 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,08-17 14:27:07.776  1036  8126 D DhcpStateMachine: DHCPV4 request on wlan0
08-17 14:27:07.780  1036  8126 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-17 14:27:07.780  1036  8126 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
,08-17 14:27:07.786  6725  6786 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 873)
08-17 14:27:07.786  6725  6786 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 873)
08-17 14:27:07.777  8143  8143 W dhcpcd  : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 14:27:07.777  8143  8143 W dhcpcd  : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 14:27:07.789  6725  6786 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 878)
08-17 14:27:07.790  6725  6786 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-17 14:27:07.790  6725  6786 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 879)
08-17 14:27:07.791  6725  6786 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 14:27:07.791  6725  6786 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bdd4f70 added. We now have 2 listener(s)
08-17 14:27:07.792  1036  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 14:27:07.795  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-17 14:27:07.795  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 14:27:07.795  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 14:27:07.795  6725  6786 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 14:27:07.795  6725  6786 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c0f22e9 added. We now have 9 listener(s)
08-17 14:27:07.795  6725  6786 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 14:27:07.796  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 14:27:07.800  6725  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 14:27:07.803  6725  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 14:27:07.803  6725  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:27:07.803  6725  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 14:27:07.803  6725  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:27:07.803  6725  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 14:27:07.803  6725  6786 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 14:27:07.803  6725  6786 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 14:27:07.803  6725  6786 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 14:27:07.804  6725  6786 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 14:27:07.804  6725  6786 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 14:27:07.804  6725  6786 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 14:27:07.804  6725  6786 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a83920f added. We now have 3 listener(s)
08-17 14:27:07.805  1036  1980 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 14:27:07.808  8143  8143 I dhcpcd  : version 5.5.6 starting
08-17 14:27:07.809  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-17 14:27:07.809  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 14:27:07.809  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 14:27:07.809  6725  6786 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 14:27:07.809  6725  6786 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71ff29c added. We now have 10 listener(s)
08-17 14:27:07.809  6725  6786 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 14:27:07.809  6725  6786 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:27:07.809  6725  6786 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:27:07.809  6725  6786 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:27:07.809  6725  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:27:07.809  6725  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:27:07.809  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 14:27:07.809  6725  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 14:27:07.809  6725  6786 V org.thaliproject.p2p.btconnectorlib.Connectio,nManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bdd4f70 removed from the list
08-17 14:27:07.809  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:27:07.809  6725  6786 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c0f22e9 removed from the list
08-17 14:27:07.810  6725  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:27:07.810  6725  6786 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:27:07.810  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:27:07.810  8143  8143 E dhcpcd  : get_duid: m
08-17 14:27:07.810  8143  8143 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-17 14:27:07.810  8143  8143 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-17 14:27:07.810  6725  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:27:07.810  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:27:07.811  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:27:07.811  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:27:07.811  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:27:07.811  6725  6786 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c0f22e9 not in the list
08-17 14:27:07.811  6725  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:27:07.811  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:27:07.812  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:27:07.812  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-17 14:27:07.812  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:27:07.812  6725  6786 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71ff29c removed from the list
08-17 14:27:07.812  6725  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 14:27:07.812  6725  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:27:07.812  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:27:07.812  6725  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-17 14:27:07.812  6725  6786 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a83920f removed from the list
08-17 14:27:07.812  6725  6786 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-17 14:27:07.812  6725  6786 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@52e04a5 added. We now have 2 listener(s)
08-17 14:27:07.812  1036  1560 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 14:27:07.814  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-17 14:27:07.814  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 14:27:07.814  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 14:27:07.814  6725  6786 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 14:27:07.814  6725  6786 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36a0707a added. We now have 9 listener(s)
08-17 14:27:07.814  6725  6786 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 14:27:07.814  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-17 14:27:07.814  1590  1590 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-17 14:27:07.816  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 14:27:07.817  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-17 14:27:07.816  6725  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 14:27:07.819  8108  8108 W ExternalStrings: load override strings
08-17 14:27:07.819  8108  8108 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
08-17 14:27:07.819  8108  8108 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
08-17 14:27:07.819  8108  8108 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
08-17 14:27:07.819  8108  8108 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
08-17 14:27:07.819  8108  8108 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
08-17 14:27:07.819  8108  8108 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
08-17 14:27:07.819  8108  8108 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
08-17 14:27:07.819  8108  8108 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-17 14:27:07.819  8108  8108 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-17 14:27:07.819  8108  8108 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-17 14:27:07.819  8108  8108 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-17 14:27:07.819  8108  8108 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 14:27:07.819  8108  8108 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
08-17 14:27:07.819  8108  8108 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-17 14:27:07.819  8108  8108 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 14:27:07.819  8108  8108 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 14:27:07.819  8108  8108 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-17 14:27:07.819  8108  8108 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-17 14:27:07.820  6725  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 14:27:07.820  6725  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:27:07.820  6725  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 14:27:07.820  6725  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:27:07.820  6725  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 14:27:07.820  6725  6786 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 14:27:07.820  6725  6786 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 14:27:07.820  6725  6786 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 14:27:07.820  8108  8108 D StatusProvider: onCreate
08-17 14:27:07.821  6725  6786 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 14:27:07.821  6725  6786 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 14:27:07.821  6725  6786 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 14:27:07.821  6725  6786 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20879c88 added. We now have 3 listener(s)
08-17 14:27:07.822  1036  1928 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 14:27:07.823  6725  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:27:07.824  6725  6725 V io.jxcore.node.ConnectivityMonitor: updateConnecti,vityInfo: No relevant state changes
08-17 14:27:07.824  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-17 14:27:07.824  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 14:27:07.824  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 14:27:07.824  6725  6786 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 14:27:07.824  6725  6786 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@49f4621 added. We now have 10 listener(s)
08-17 14:27:07.824  6725  6786 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 14:27:07.825  6725  6786 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 14:27:07.825  6725  6786 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 14:27:07.825  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 14:27:07.825  6725  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 14:27:07.825  6725  6786 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-17 14:27:07.827  6725  6786 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-17 14:27:07.827  1036  1560 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 14:27:07.829  6725  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-17 14:27:07.830  6725  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-17 14:27:07.831  6725  6786 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-17 14:27:07.831  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 14:27:07.832  6725  6786 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-17 14:27:07.832  6725  6786 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:27:07.832  6725  6786 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:27:07.833  6725  6786 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:27:07.833  6725  6786 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:27:07.833  6725  6786 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:27:07.833  6725  6786 I org.thaliproject.p2p.btconnectorlib.Connec,tionManager: dispose
08-17 14:27:07.833  6725  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:27:07.833  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 14:27:07.833  6725  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 14:27:07.833  6725  6786 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@52e04a5 removed from the list
08-17 14:27:07.833  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:27:07.833  6725  6786 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36a0707a removed from the list
08-17 14:27:07.833  6725  6786 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:27:07.833  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:27:07.834  6725  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:27:07.834  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:27:07.834  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:27:07.834  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:27:07.835  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:27:07.835  6725  6786 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36a0707a not in the list
08-17 14:27:07.835  6725  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:27:07.835  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:27:07.835  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:27:07.836  6725  6786 D BluetoothLeScanner: could not find callback wrapper
08-17 14:27:07.836  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 14:27:07.836  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:27:07.836  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:27:07.836  6725  6786 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@49f4621 removed from the list
08-17 14:27:07.836  6725  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:27:07.836  6725  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:27:07.836  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:27:07.836  6725  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 14:27:07.836  6725  6786 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20879c88 removed from the list
08-17 14:27:07.836  6725  6786 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 14:27:07.836  6725  6786 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@213df934 added. We now have 2 listener(s)
08-17 14:27:07.837  1036  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 14:27:07.838  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-17 14:27:07.838  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 14:27:07.838  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 14:27:07.838  6725  6786 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 14:27:07.839  6725  6786 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b89235d added. We now have 9 listener(s)
08-17 14:27:07.839  6725  6786 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 14:27:07.839  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-17 14:27:07.840  6725  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 14:27:07.842  6725  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 14:27:07.842  6725  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:27:07.842  6725  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 14:27:07.842  6725  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:27:07.842  6725  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 14:27:07.842  6725  6786 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 14:27:07.842  6725  6786 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 14:27:07.842  6725  6786 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 14:27:07.843  6725  6786 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 14:27:07.843  6725  6786 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 14:27:07.843  6725  6786 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 14:27:07.843  6725  6786 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@193b89a3 added. We now have 3 listener(s)
08-17 14:27:07.843  1036  2036 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 14:27:07.844  6725  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:27:07.845  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-17 14:27:07.845  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 14:27:07.845  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 14:27:07.845  6725  6786 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 14:27:07.845  6725  6786 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@395b74a0 added. We now have 10 listener(s)
08-17 14:27:07.845  6725  6786 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 14:27:07.845  6725  6786 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 14:27:07.845  6725  6786 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 14:27:07.845  6725  6786 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 14:27:07.846  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 14:27:07.846  6725  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 14:27:07.846  6725  6786 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-17 14:27:07.847  6725  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:27:07.849  6725  6786 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-17 14:27:07.849  1036  1980 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 14:27:07.851  6725  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-17 14:27:07.851  6725  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-17 14:27:07.852  6725  6786 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-17 14:27:07.852  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 14:27:07.853  6725  6786 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-17 14:27:07.853  6725  6786 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:27:07.854  6725  6786 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:27:07.854  6725  6786 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:27:07.854  6725  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:27:07.854  6725  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:27:07.854  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 14:27:07.854  6725  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 14:27:07.854  6725  6786 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@213df934 removed from the list
08-17 14:27:07.854  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:27:07.854  6725  6786 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b89235d removed from the list
08-17 14:27:07.854  6725  6786 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:27:07.854  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:27:07.854  6725  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:27:07.854  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:27:07.855  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:27:07.855  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:27:07.855  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:27:07.855  6725  6786 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b89235d not in the list
08-17 14:27:07.855  6725  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:27:07.855  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:27:07.856  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:27:07.856  6725  6786 D BluetoothLeScanner: could not find callback wrapper
08-17 14:27:07.856  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 14:27:07.856  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:27:07.856  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:27:07.856  6725  6786 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@395b74a0 removed from the list
08-17 14:27:07.856  6725  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:27:07.856  6725  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:27:07.856  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:27:07.856  6725  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 14:27:07.856  6725  6786 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@193b89a3 removed from the list
08-17 14:27:07.857  6725  6786 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 14:27:07.857  6725  6786 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10731cff added. We now have 2 listener(s)
08-17 14:27:07.857  1036  1875 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 14:27:07.858  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-17 14:27:07.858  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 14:27:07.858  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 14:27:07.858  6725  6786 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 14:27:07.859  6725  6786 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@133acc added. We now have 9 listener(s)
08-17 14:27:07.859  6725  6786 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 14:27:07.859  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-17 14:27:07.860  6725  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 14:27:07.862  6725  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 14:27:07.862  6725  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:27:07.862  6725  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 14:27:07.862  6725  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:27:07.862  6725  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 14:27:07.862  6725  6786 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 14:27:07.862  6725  6786 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 14:27:07.862  6725  6786 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 14:27:07.863  6725  6786 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 14:27:07.863  6725  6786 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 14:27:07.864  6725  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:27:07.865  6725  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:27:07.865  6725  6786 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 14:27:07.865  6725  6786 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a35ec2a added. We now have 3 listener(s)
08-17 14:27:07.866  1036  1909 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 14:27:07.867  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-17 14:27:07.867  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 14:27:07.867  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 14:27:07.867  6725  6786 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 14:27:07.867  6725  6786 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9668a1b added. We now have 10 listener(s)
08-17 14:27:07.867  6725  6786 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 14:27:07.867  6725  6786 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 14:27:07.867  6725  6786 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 14:27:07.867  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 14:27:07.867  6725  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 14:27:07.867  6725  6786 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-17 14:27:07.869  8143  8143 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-17 14:27:07.869  8143  8143 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-17 14:27:07.869  8143  8143 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-17 14:27:07.869  8143  8143 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
08-17 14:27:07.869  8143  8143 D dhcpcd  : wlan0: sending REQUEST (xid 0x4abdcbe1), next in 4.80 seconds
08-17 14:27:07.870  6725  6786 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-17 14:27:07.870  1036  2000 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 14:27:07.872  6725  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-17 14:27:07.872  6725  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-17 14:27:07.873  6725  6786 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-17 14:27:07.873  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 14:27:07.874  6725  6786 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-17 14:27:07.875  6725  6786 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:27:07.875  6725  6786 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:27:07.875  6725  6786 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:27:07.875  6725  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:27:07.875  6725  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:27:07.875  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 14:27:07.875  6725  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 14:27:07.875  6725  6786 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10731cff removed from the list
08-17 14:27:07.875  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:27:07.875  6725  6786 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@133acc removed from the list
08-17 14:27:07.875  6725  6786 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:27:07.875  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:27:07.876  6725  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:27:07.876  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:27:07.876  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:27:07.876  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:27:07.876  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:27:07.876  6725  6786 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@133acc not in the list
08-17 14:27:07.876  6725  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:27:07.876  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:27:07.877  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:27:07.877  6725  6786 D BluetoothLeScanner: could not find callback wrapper
08-17 14:27:07.877  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 14:27:07.877  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:27:07.877  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:27:07.877  6725  6786 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9668a1b removed from the list
08-17 14:27:07.877  6725  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:27:07.877  6725  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:27:07.877  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:27:07.877  6725  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 14:27:07.877  6725  6786 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a35ec2a removed from the list
08-17 14:27:07.878  6725  6786 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 14:27:07.878  6725  6786 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@91ea0f6 added. We now have 2 listener(s)
08-17 14:27:07.878  1036  1560 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 14:27:07.880  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-17 14:27:07.880  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 14:27:07.880  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 14:27:07.880  6725  6786 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 14:27:07.880  6725  6786 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b59acf7 added. We now have 9 listener(s)
08-17 14:27:07.880  6725  6786 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 14:27:07.880  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-17 14:27:07.882  6725  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 14:27:07.884  6725  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 14:27:07.884  6725  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:27:07.884  6725  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 14:27:07.884  6725  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:27:07.884  6725  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 14:27:07.884  6725  6786 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 14:27:07.884  6725  6786 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 14:27:07.884  6725  6786 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 14:27:07.884  6725  6786 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 14:27:07.885  6725  6786 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 14:27:07.885  6725  6786 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 14:27:07.885  6725  6786 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ffe9dcd added. We now have 3 listener(s)
08-17 14:27:07.885  1036  1928 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 14:27:07.886  6725  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:27:07.887  6725  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:27:07.887  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-17 14:27:07.887  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 14:27:07.887  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 14:27:07.888  6725  6786 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 14:27:07.888  6725  6786 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d0bd682 added. We now have 10 listener(s)
08-17 14:27:07.888  6725  6786 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 14:27:07.888  6725  6786 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:27:07.888  6725  6786 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:27:07.888  6725  6786 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:27:07.888  6725  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:27:07.888  6725  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:27:07.888  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 14:27:07.888  6725  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 14:27:07.888  6725  6786 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@91ea0f6 removed from the list
08-17 14:27:07.888  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:27:07.888  6725  6786 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b59acf7 removed from the list
08-17 14:27:07.888  6725  6786 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:27:07.888  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:27:07.889  8108  8108 V Signer  : override build config not found
08-17 14:27:07.889  6725  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:27:07.889  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:27:07.889  8108  8108 D Signer  : value of property debug is false
08-17 14:27:07.889  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:27:07.889  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:27:07.889  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:27:07.889  6725  6786 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b59acf7 not in the list
08-17 14:27:07.889  6725  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:27:07.889  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:27:07.890  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:27:07.890  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:27:07.890  6725  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:27:07.890  6725  6786 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d0bd682 removed from the list
08-17 14:27:07.890  6725  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:27:07.890  6725  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:27:07.890  6725  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:27:07.890  6725  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 14:27:07.890  6725  6786 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ffe9dcd removed from the list
08-17 14:27:07.891  6725  6786 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-17 14:27:07.891  6725  6786 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-17 14:27:07.891  6725  6786 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-17 14:27:07.892  6725  6786 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 14:27:07.892  6725  6786 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-17 14:27:07.892  6725  6786 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-17 14:27:07.901  6725  8150 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 886, name: My test thread name)
08-17 14:27:07.901  6725  8150 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 886, thread name: My test thread name)
08-17 14:27:07.901  6725  8150 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 886, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-17 14:27:07.902  6725  8151 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 888, name: My test thread name)
08-17 14:27:07.903  6725  8151 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 888, thread name: My test thread name)
08-17 14:27:07.903  6725  8151 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 888, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-17 14:27:07.904  6725  6786 D com.test.thalitest.ThaliTestRunn,er: Total number of executed tests: 80
08-17 14:27:07.904  6725  6786 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-17 14:27:07.904  6725  6786 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-17 14:27:07.904  6725  6786 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-17 14:27:07.904  6725  6786 D com.test.thalitest.ThaliTestRunner: Total duration: 22795 ms
08-17 14:27:07.906  8143  8143 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
08-17 14:27:07.907  6725  6786 I jxcore-log: Total number of executed tests:  80
08-17 14:27:07.907  6725  6786 I jxcore-log: 
08-17 14:27:07.907  6725  6786 I jxcore-log: Number of passed tests:  80
08-17 14:27:07.907  6725  6786 I jxcore-log: 
08-17 14:27:07.907  6725  6786 I jxcore-log: Number of failed tests:  0
08-17 14:27:07.907  6725  6786 I jxcore-log: 
08-17 14:27:07.907  6725  6786 I jxcore-log: Number of ignored tests:  0
08-17 14:27:07.907  6725  6786 I jxcore-log: 
08-17 14:27:07.907  6725  6786 I jxcore-log: Total duration:  22795
08-17 14:27:07.907  6725  6786 I jxcore-log: 
08-17 14:27:07.907  6725  6786 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-17 14:27:07.907  6725  6786 I jxcore-log: 
08-17 14:27:07.911  6725  6786 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 14:27:07.911  6725  6786 I jxcore-log: 
08-17 14:27:07.913  6725  6786 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 14:27:07.913  6725  6786 I jxcore-log: 
08-17 14:27:07.914  6725  6786 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 14:27:07.914  6725  6786 I jxcore-log: 
08-17 14:27:07.915  6725  6786 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 14:27:07.915  6725  6786 I jxcore-log: 
,08-17 14:27:07.915  6725  6786 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 14:27:07.915  6725  6786 I jxcore-log: 
08-17 14:27:07.917  6725  6786 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 14:27:07.917  6725  6786 I jxcore-log: 
08-17 14:27:07.918  6725  6786 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 14:27:07.918  6725  6786 I jxcore-log: 
08-17 14:27:07.919  6725  6786 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 14:27:07.919  6725  6786 I jxcore-log: 
08-17 14:27:07.920  6725  6786 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-17 14:27:07.920  6725  6786 I jxcore-log: 
08-17 14:27:07.920  6725  6786 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-17 14:27:07.920  6725  6786 I jxcore-log: 
08-17 14:27:07.921  6725  6786 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 14:27:07.921  6725  6786 I jxcore-log: 
08-17 14:27:07.922  6725  6725 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
08-17 14:27:07.922  6725  6786 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 14:27:07.922  6725  6786 I jxcore-log: 
08-17 14:27:07.922  6725  6786 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-17 14:27:07.922  6725  6786 I jxcore-log: 
08-17 14:27:07.923  6725  6786 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-17 14:27:07.923  6725  6786 I jxcore-log: 
08-17 14:27:07.924  6725  6786 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-17 14:27:07.924  6725  6786 I jxcore-log: 
08-17 14:27:07.924  6725  6786 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 14:27:07.924  6725  6786 I jxcore-log: 
08-17 14:27:07.924  6725  6786 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 14:27:07.924  6725  6786 I jxcore-log: 
08-17 14:27:07.925  6725  6786 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-17 14:27:07.925  6725  6786 I jxcore-log: 
08-17 14:27:07.925  6725  6786 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-17 14:27:07.925  6725  6786 I jxcore-log: 
08-17 14:27:07.926  6725  6786 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 14:27:07.926  6725  6786 I jxcore-log: 
08-17 14:27:07.927  6725  6786 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 14:27:07.927  6725  6786 I jxcore-log: 
08-17 14:27:07.927  6725  6786 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-17 14:27:07.927  6725  6786 I jxcore-log: 
08-17 14:27:07.928  6725  6786 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-17 14:27:07.928  6725  6786 I jxcore-log: 
08-17 14:27:07.928  6725  6786 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-17 14:27:07.928  6725  6786 I jxcore-log: 
08-17 14:27:07.929  6725  6786 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-17 14:27:07.929  6725  6786 I jxcore-log: 
08-17 14:27:07.929  6725  6786 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 14:27:07.929  6725  6786 I jxcore-log: 
08-17 14:27:07.930  6725  6786 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 14:27:07.930  6725  6786 I jxcore-log: 
08-17 14:27:07.930  6725  6786 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 14:27:07.930  6725  6786 I jxcore-log: 
08-17 14:27:07.930  6725  6786 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 14:27:07.930  6725  6786 I jxcore-log: 
08-17 14:27:07.931  6725  6786 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 14:27:07.931  6725  6786 I jxcore-log: 
08-17 14:27:07.936  8143  8143 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
08-17 14:27:07.936  8143  8143 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
08-17 14:27:07.937  8143  8143 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-17 14:27:07.937  8143  8143 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-17 14:27:07.937  8143  8143 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-17 14:27:07.937  8143  8143 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-17 14:27:07.937  8143  8143 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-17 14:27:07.937  8143  8143 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,08-17 14:27:07.950  8108  8108 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
,08-17 14:27:07.951  8108  8108 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
08-17 14:27:07.951  8108  8108 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
08-17 14:27:07.951  8108  8108 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
08-17 14:27:07.951  8108  8108 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
08-17 14:27:07.952  8108  8108 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
08-17 14:27:07.952  8108  8108 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
08-17 14:27:07.952  8108  8108 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
08-17 14:27:07.952  8108  8108 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
08-17 14:27:07.953  8108  8108 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
08-17 14:27:07.954  8108  8108 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
08-17 14:27:07.954  8108  8108 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
08-17 14:27:07.954  8108  8108 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
08-17 14:27:07.968  8108  8108 V LGMDMManager: Create singleton instance
,08-17 14:27:08.022  8108  8108 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
,08-17 14:27:08.077  8108  8168 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-17 14:27:08.078  8108  8108 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-17 14:27:08.091  6837  6837 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-17 14:27:08.097  6837  6837 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 14:27:08.105  7667  7667 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-17 14:27:08.106  7667  7667 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-17 14:27:08.111  7667  7667 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-17 14:27:08.113  6837  6837 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-17 14:27:08.121  6837  6837 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-17 14:27:08.123  8108  8108 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-17 14:27:08.124  8108  8168 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-17 14:27:08.129  6837  6837 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-17 14:27:08.132  6837  6837 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-17 14:27:08.137  7667  7667 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-17 14:27:08.137  7667  7667 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-17 14:27:08.138  7667  7667 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-17 14:27:08.186  1036  8126 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-17 14:27:08.188  1036  8126 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-17 14:27:08.188  1036  8126 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
,08-17 14:27:08.189  1036  8126 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
08-17 14:27:08.189  1036  8126 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-17 14:27:08.189  1036  8126 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-17 14:27:08.189  1036  8126 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-17 14:27:08.189  1036  8126 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-17 14:27:08.189  1036  8126 D DhcpStateMachine: RunningState
,08-17 14:27:08.234  8108  8108 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-17 14:27:08.235  8108  8168 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-17 14:27:08.238  8108  8167 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
08-17 14:27:08.241  6837  6837 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-17 14:27:08.244  6837  6837 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 14:27:08.247  8158  8158 D AndroidRuntime: 
08-17 14:27:08.247  8158  8158 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-17 14:27:08.250  7667  7667 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-17 14:27:08.251  7667  7667 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-17 14:27:08.251  8158  8158 D AndroidRuntime: CheckJNI is OFF
08-17 14:27:08.252  7667  7667 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-17 14:27:08.259  6837  6837 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-17 14:27:08.259  6837  6837 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-17 14:27:08.259  6837  6837 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-17 14:27:08.259  6837  6837 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-17 14:27:08.259  6837  6837 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-17 14:27:08.260  6837  6837 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-17 14:27:08.260  6837  6837 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-17 14:27:08.260  6837  6837 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-17 14:27:08.260  6837  6837 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-17 14:27:08.261  6837  6837 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-17 14:27:08.261  6837  6837 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-17 14:27:08.261  6837  6837 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-17 14:27:08.264  8108  8108 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-17 14:27:08.265  8108  8168 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-17 14:27:08.275  6837  6837 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-17 14:27:08.283  6837  6837 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 14:27:08.288  7667  7667 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-17 14:27:08.288  7667  7667 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-17 14:27:08.288  7667  7667 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-17 14:27:08.293  8108  8108 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-17 14:27:08.294  8108  8168 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-17 14:27:08.300  6837  6837 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-17 14:27:08.306  6837  6837 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 14:27:08.313  7667  7667 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-17 14:27:08.313  7667  7667 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-17 14:27:08.315  7667  7667 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-17 14:27:08.317  8108  8108 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-17 14:27:08.318  8108  8168 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-17 14:27:08.328  6837  6837 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-17 14:27:08.333  6837  6837 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 14:27:08.338  7667  7667 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-17 14:27:08.338  7667  7667 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-17 14:27:08.339  7667  7667 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-17 14:27:08.342  8108  8108 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-17 14:27:08.342  8108  8168 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-17 14:27:08.351  6837  6837 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-17 14:27:08.356  6837  6837 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 14:27:08.363  7667  7667 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-17 14:27:08.363  7667  7667 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-17 14:27:08.363  7667  7667 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-17 14:27:08.365  1036  1875 I ActivityManager: Killing 7207:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
08-17 14:27:08.395  8158  8158 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-17 14:27:08.500  1036  1909 W libprocessgroup: failed to open /acct/uid_10005/pid_7207/cgroup.procs: No such file or directory
,08-17 14:27:08.507  1036  1099 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
,08-17 14:27:08.507  1036  1099 I ActivityManager: Killing 6725:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
08-17 14:27:08.554  1036  2001 I WindowState: WIN DEATH: Window{1c2b6f78 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-17 14:27:08.555  1036  1529 D WifiService: Client connection lost with reason: 4
,08-17 14:27:08.560  1036  2001 D InputDispatcher: Window went away: Window{1c2b6f78 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-17 14:27:08.580  8108  8167 D LgDataFeature: LgDataFeature() Constructor: none
,08-17 14:27:08.580  8108  8167 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-17 14:27:08.650  1036  1099 I ActivityManager:   Force finishing activity ActivityRecord{67c0dad u0 com.test.thalitest/.MainActivity t6}
,08-17 14:27:08.673   352   370 E GBMv2   : DFP En is all cleared set to be enabled
08-17 14:27:08.674  8108  8167 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
,08-17 14:27:08.678  1036  1127 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-17 14:27:08.679  1036  1127 I ActivityManager:   Force finishing activity ActivityRecord{67c0dad u0 com.test.thalitest/.MainActivity t6 f}
08-17 14:27:08.679  1036  1127 W ActivityManager: Duplicate finish request for ActivityRecord{67c0dad u0 com.test.thalitest/.MainActivity t6 f}
08-17 14:27:08.697  1036  1875 W ActivityManager: Spurious death for ProcessRecord{8f79675 6725:com.test.thalitest/u0a118}, curProc for 6725: null
,08-17 14:27:08.706  1590  1590 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-17 14:27:08.711  3783  3783 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-17 14:27:08.712  2472  2626 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-17 14:27:08.714  1983  1983 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-17 14:27:08.714  7639  7639 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-17 14:27:08.714  7639  7639 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-17 14:27:08.717  4486  4486 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-17 14:27:08.717  4486  4486 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-17 14:27:08.717  4486  4486 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-17 14:27:08.717  4486  4486 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-17 14:27:08.717  4486  4486 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-17 14:27:08.717  4486  4486 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-17 14:27:08.717  4486  4486 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-17 14:27:08.717  4486  4486 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-17 14:27:08.717  4486  4486 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 14:27:08.717  4486  4486 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 14:27:08.717  4486  4486 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-17 14:27:08.717  4486  4486 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-17 14:27:08.718  2020  2020 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-17 14:27:08.721  1036  1414 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-17 14:27:08.725  2020  2020 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-17 14:27:08.741  4598  4598 I art     : Explicit concurrent mark sweep GC freed 8269(472KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 358us total 54.588ms
,08-17 14:27:08.756  1036  1098 W InputMethodInfo: Duplicated subtype definition found: , voice
,08-17 14:27:08.765  1036  1964 V SIM_STK : Menu title from STK is T-Mobile
08-17 14:27:08.784  1036  1036 D administrator: Handling package changes for user 0
,08-17 14:27:08.787  2020  2020 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-17 14:27:08.787  1929  1945 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-17 14:27:08.787  1929  1945 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1fdb0ccd co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-17 14:27:08.788  1929  3937 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-17 14:27:08.788  1929  3937 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1b91982 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-17 14:27:08.790  2020  2089 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
08-17 14:27:08.797  7667  7667 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
,08-17 14:27:08.797  7667  7667 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:6245
08-17 14:27:08.797  8108  8167 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
08-17 14:27:08.806  8108  8167 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
08-17 14:27:08.807  8108  8167 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-17 14:27:08.808  8108  8167 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-17 14:27:08.808  8108  8167 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
08-17 14:27:08.809  8108  8167 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
,08-17 14:27:08.815  1590  1590 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-17 14:27:08.818  1590  1650 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-17 14:27:08.818  1590  1650 D KeyguardModel: createShortcutInfo...
08-17 14:27:08.818  2020  2020 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-17 14:27:08.819  1893  1893 D ActionManagerService: notifyUserLog: 1000003
,08-17 14:27:08.820  3783  4479 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-17 14:27:08.821  8108  8168 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-17 14:27:08.821  2020  2020 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-17 14:27:08.822  8108  8108 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-17 14:27:08.824  8108  8167 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
08-17 14:27:08.825  1804  8202 I CheckinService: active receiver: enabled
08-17 14:27:08.825  2020  2020 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-17 14:27:08.827  8108  8167 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
,08-17 14:27:08.855  1036  1946 V SIM_STK : Menu title from STK is T-Mobile
08-17 14:27:08.855  1036  1946 V SIM_STK : Menu title from STK is T-Mobile
,08-17 14:27:08.869  1590  1590 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-17 14:27:08.889  1036  2036 V SIM_STK : Menu title from STK is T-Mobile
,08-17 14:27:08.927  1590  1650 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-17 14:27:08.927  1590  1650 D KeyguardModel: createShortcutInfo...
,08-17 14:27:08.929  1036  2000 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-17 14:27:08.930  7639  7639 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-17 14:27:08.930  7639  7639 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-17 14:27:08.930  7639  7639 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-17 14:27:08.930  7639  7639 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-17 14:27:08.930  7639  7639 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-17 14:27:08.930  7639  7639 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-17 14:27:08.930  7639  7639 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-17 14:27:08.930  7639  7639 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-17 14:27:08.930  7639  7639 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-17 14:27:08.930  7639  7639 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-17 14:27:08.930  7639  7639 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-17 14:27:08.930  2020  2020 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-17 14:27:08.931  1590  1650 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-17 14:27:08.932  1590  1650 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-17 14:27:08.932  1590  1650 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-17 14:27:08.933  1590  1650 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-17 14:27:08.933  1590  1650 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-17 14:27:08.933  1590  1650 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-17 14:27:08.933  1804  8202 I CheckinService: Preparing to send checkin request
08-17 14:27:08.934  1804  8202 I EventLogService: Accumulating logs since 1471436810717
08-17 14:27:08.936  1036  1036 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-17 14:27:08.936  1036  1036 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-17 14:27:08.936  1036  1036 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-17 14:27:08.936  1893  1893 D ActionManagerService: notifyUserLog: 1000004
08-17 14:27:08.937  3783  4479 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-17 14:27:08.937  2020  2020 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-17 14:27:08.937  1590  1650 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
,08-17 14:27:08.938  1590  1650 D KeyguardModel: createShortcutInfo...
08-17 14:27:08.938  3783  3798 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-17 14:27:08.940  1590  1590 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-17 14:27:08.948  1590  1650 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-17 14:27:08.948  1590  1650 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-17 14:27:08.948  6837  6837 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-17 14:27:08.956  1590  1650 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-17 14:27:08.956  1590  1650 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-17 14:27:08.957  1036  1565 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-17 14:27:08.957  2020  2020 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-17 14:27:08.957  2020  2020 I GBoardWebViewUtils: , create_time: 1430832262123
08-17 14:27:08.957  2020  2020 I GBoardWebViewUtils: , expire_time: 0
08-17 14:27:08.957  2020  2020 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-17 14:27:08.957  2020  2020 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-17 14:27:08.957  2020  2020 I GBoardWebViewUtils: , display: false
08-17 14:27:08.957  2020  2020 I GBoardWebViewUtils: , animation: false }
08-17 14:27:08.957  2020  2020 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-17 14:27:08.957  2020  2020 I GBoardWebViewUtils: , create_time: 1430832262287
08-17 14:27:08.957  2020  2020 I GBoardWebViewUtils: , expire_time: 0
08-17 14:27:08.957  2020  2020 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-17 14:27:08.957  2020  2020 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-17 14:27:08.957  2020  2020 I GBoardWebViewUtils: , display: false
08-17 14:27:08.957  2020  2020 I GBoardWebViewUtils: , animation: false }
08-17 14:27:08.957  2020  2020 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1471007225619
08-17 14:27:08.957  2020  2020 I GBoardWebViewUtils: , create_time: 1471007226523
08-17 14:27:08.957  2020  2020 I GBoardWebViewUtils: , expire_time: 0
08-17 14:27:08.957  2020  2020 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide.html?id=guide_1111111111116_1471007225619&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-17 14:27:08.957  2020  2020 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-17 14:27:08.957  2020  2020 I GBoardWebViewUtils: , display: false
08-17 14:27:08.957  2020  2020 I GBoardWebViewUtils: , animation: false }
08-17 14:27:08.962  2020  2020 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-17 14:27:08.962  1590  1650 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-17 14:27:08.962  1590  1650 D KeyguardModel: createShortcutInfo...
08-17 14:27:08.963  2020  8208 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-17 14:27:08.968  1590  1650 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-17 14:27:08.968  1590  1650 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-17 14:27:08.968  1590  1650 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-17 14:27:08.968  1590  1650 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-17 14:27:08.971  1590  1650 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-17 14:27:08.971  1590  1650 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,08-17 14:27:08.975  1590  1650 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-17 14:27:08.975  1590  1650 D KeyguardModel: createShortcutInfo...
08-17 14:27:08.982  1804  8202 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
08-17 14:27:08.983  1856  1856 D SplitUIManager: split_name #11 / not available #0
08-17 14:27:08.983  2020  2020 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-17 14:27:08.984  1856  1856 D SplitUIService: removed split : 
,08-17 14:27:08.991  1590  1590 D KeyguardModel: handleShortcutListChanged...
08-17 14:27:08.991  1590  1590 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-17 14:27:08.996  1590  1650 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-17 14:27:08.996  1590  1650 D KeyguardModel: createShortcutInfo...
,08-17 14:27:09.000  6837  6837 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 14:27:08.998  1590  1650 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-17 14:27:09.000  1590  1650 D KeyguardModel: createShortcutInfo...
08-17 14:27:09.009  1590  1650 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-17 14:27:09.009  1590  1650 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
,08-17 14:27:09.016  1590  1650 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-17 14:27:09.016  1590  1650 D KeyguardModel: createShortcutInfo...
08-17 14:27:09.019  1590  1650 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-17 14:27:09.019  1590  1650 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-17 14:27:09.020  1856  1856 D SplitUIManager: split_name #11 / not available #0
08-17 14:27:09.020  1856  1856 I SplitUIService: split app #11
08-17 14:27:09.020  1590  1650 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-17 14:27:09.020  1590  1650 D KeyguardModel: createShortcutInfo...
08-17 14:27:09.021  1590  1650 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-17 14:27:09.021  1590  1650 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-17 14:27:09.023  1590  1650 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
,08-17 14:27:09.023  1590  1650 D KeyguardModel: createShortcutInfo...
,08-17 14:27:09.028  7667  7667 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-17 14:27:09.029  7667  7667 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-17 14:27:09.032  7667  7667 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-17 14:27:09.036  8108  8108 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-17 14:27:09.036  8108  8168 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-17 14:27:09.037  1590  1590 D KeyguardModel: handleShortcutListChanged...
08-17 14:27:09.037  1590  1590 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,08-17 14:27:09.044  6837  6837 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-17 14:27:09.055  6837  6837 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 14:27:09.061  7667  7667 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-17 14:27:09.062  7667  7667 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-17 14:27:09.062  7667  7667 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-17 14:27:09.070  8108  8108 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-17 14:27:09.070  8108  8168 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-17 14:27:09.078  8057  8057 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-17 14:27:09.081  8057  8057 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-17 14:27:09.084  6837  6837 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-17 14:27:09.098  6837  6837 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 14:27:09.104  7667  7667 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-17 14:27:09.105  7667  7667 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-17 14:27:09.105  7667  7667 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-17 14:27:09.106  7667  7667 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-17 14:27:09.106  7667  7667 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-17 14:27:09.114  8108  8108 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-17 14:27:09.114  8108  8168 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-17 14:27:09.119  8057  8057 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-17 14:27:09.120  8057  8057 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-17 14:27:09.125  6837  6837 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-17 14:27:09.132   346   446 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-17 14:27:09.133  3217  8213 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-17 14:27:09.134  6837  6837 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 14:27:09.138  2020  2020 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
08-17 14:27:09.142  2020  2020 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-17 14:27:09.143  2020  2020 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-17 14:27:09.144  2020  2020 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-17 14:27:09.146  2020  2020 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-17 14:27:09.146  7667  7667 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-17 14:27:09.147  7667  7667 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-17 14:27:09.147  2020  2020 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-17 14:27:09.148  7667  7667 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-17 14:27:09.149  7667  7667 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-17 14:27:09.149  7667  7667 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,08-17 14:27:09.153  8108  8108 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-17 14:27:09.157  1036  1127 I art     : Explicit concurrent mark sweep GC freed 86331(4MB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 43MB/65MB, paused 5.065ms total 218.222ms
08-17 14:27:09.161  1036  1104 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1b57d132 u0 com.lge.launcher2/.Launcher t5} time:350925
,08-17 14:27:09.165  2020  2020 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-17 14:27:09.166  2020  2020 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-17 14:27:09.167  2020  2020 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-17 14:27:09.167  2020  2140 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-17 14:27:09.167  2020  2140 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-17 14:27:09.173  8108  8108 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-17 14:27:09.176  8108  8108 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-17 14:27:09.181  2020  2020 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-17 14:27:09.182  2020  2020 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-17 14:27:09.182  2020  2020 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-17 14:27:09.184  8108  8108 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-17 14:27:09.185  8108  8108 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-17 14:27:09.188  8108  8108 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-17 14:27:09.190  8108  8108 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-17 14:27:09.191  2020  2020 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-17 14:27:09.191  8108  8108 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-17 14:27:09.191  2601  2601 D [Concierge]Service: onStartCommand(). Type : 8
08-17 14:27:09.192  2601  2601 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-17 14:27:09.192  2601  2601 D [Concierge]Service: Update widget ID : 11
08-17 14:27:09.194  2020  2020 D [Concierge]WidgetView: change position of spinner
08-17 14:27:09.211  8158  8158 D AndroidRuntime: Shutting down VM
,08-17 14:27:09.226  1804  1804 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
,08-17 14:27:09.229  2601  2601 D [Concierge]Service: onStartCommand(). Type : 0
08-17 14:27:09.229  2020  2020 I [Concierge]WidgetView: initWebView(). Time : 1471436829229
08-17 14:27:09.247  1036  1098 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-17 14:27:09.252  1036  1098 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-17 14:27:09.258  1036  1127 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8221 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-17 14:27:09.287  1036  1928 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=8238 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-17 14:27:09.292  2162  2162 I ConfigService: onCreate
08-17 14:27:09.292  2162  2162 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-17 14:27:09.296  2162  2162 I ConfigService: onBind returning update interface
08-17 14:27:09.298  1804  1804 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-17 14:27:09.298  2162  2162 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-17 14:27:09.298  2162  2162 I ConfigService: onBind returning config service
08-17 14:27:09.309  1804  1804 I ConfigFetchService: service connected
,08-17 14:27:09.310  1804  1804 I ConfigClient: service connected
08-17 14:27:09.313  2020  2020 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 496122885
08-17 14:27:09.314  2020  2020 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-17 14:27:09.314  2020  2020 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-17 14:27:09.317  2020  2020 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@38696f85
08-17 14:27:09.317  2020  2020 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-17 14:27:09.318  2020  2020 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-17 14:27:09.318  2020  2020 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-17 14:27:09.319  2162  2162 I ConfigService: onDestroy
08-17 14:27:09.321  1804  8257 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,08-17 14:27:09.323  2020  2020 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-17 14:27:09.325  2020  2020 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-17 14:27:09.325  2020  2020 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-17 14:27:09.326  2020  2020 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1471436506135, New one : 1471436829229
08-17 14:27:09.326  2020  2020 D [Concierge]WidgetView: Unregister all receivers
08-17 14:27:09.326  2020  2020 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-17 14:27:09.326  2020  2020 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-17 14:27:09.328  2020  2020 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-17 14:27:09.330  2020  2020 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-17 14:27:09.331  2020  2020 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-17 14:27:09.332  2020  2020 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-17 14:27:09.333  2020  2020 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-17 14:27:09.334  2020  2020 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-17 14:27:09.334  2020  2020 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-17 14:27:09.335  2020  2020 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-17 14:27:09.339  8238  8238 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-17 14:27:09.339  8238  8238 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-17 14:27:09.350  5931  8262 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
08-17 14:27:09.359  8238  8238 I MultiDex: VM with version 2.1.0 has multidex support
08-17 14:27:09.359  8238  8238 I MultiDex: install
08-17 14:27:09.359  8238  8238 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-17 14:27:09.364  7008  7008 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
08-17 14:27:09.365  2020  2020 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-17 14:27:09.368  1036  1928 I ActivityManager: Killing 7720:com.google.android.talk/u0a72 (adj 15): empty #17
08-17 14:27:09.371  1804  8264 I PeopleContactsSync: CP2 sync disabled
08-17 14:27:09.373  2020  2020 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-17 14:27:09.373  2020  2020 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-17 14:27:09.375  2020  2020 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-17 14:27:09.395  2020  2020 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@26c13296 time:351159
,08-17 14:27:09.428  1036  1964 W libprocessgroup: failed to open /acct/uid_10072/pid_7720/cgroup.procs: No such file or directory
,08-17 14:27:09.434  2338  8268 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-17 14:27:09.460  1036  1909 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8269 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
08-17 14:27:09.462  1804  4746 I Icing   : doRemovePackageData com.test.thalitest
,08-17 14:27:09.467  8238  8238 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
08-17 14:27:09.484  1804  8263 W GmsApplication: Using Auth Proxy for data requests.
,08-17 14:27:09.490  1804  8263 W GmsApplication: Using Auth Proxy for data requests.
08-17 14:27:09.507  1036  1523 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-17 14:27:09.507  1036  1523 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-17 14:27:09.508  1036  1523 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-17 14:27:09.508  1036  1523 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-17 14:27:09.508  1036  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-17 14:27:09.508  1036  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-17 14:27:09.509  1036  1530 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
08-17 14:27:09.509  1036  1530 D ConnectivityService: identical MTU - not setting
08-17 14:27:09.509  1036  1530 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-17 14:27:09.509  1036  1530 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-17 14:27:09.509  1036  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 14:27:09.509  1036  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-17 14:27:09.509  1036  1530 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-17 14:27:09.510  1590  2061 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-17 14:27:09.527  2162  2183 I art     : Explicit concurrent mark sweep GC freed 5111(305KB) AllocSpace objects, 0(0B) LOS objects, 52% free, 29MB/61MB, paused 663us total 17.634ms
,08-17 14:27:09.542  1804  8259 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-17 14:27:09.543  1804  8259 E DriveAsyncService: disk I/O error (code 3850)
08-17 14:27:09.543  1804  8259 E DriveAsyncService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-17 14:27:09.543  1804  8259 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-17 14:27:09.543  1804  8259 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:560)
08-17 14:27:09.543  1804  8259 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-17 14:27:09.543  1804  8259 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-17 14:27:09.543  1804  8259 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-17 14:27:09.543  1804  8259 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-17 14:27:09.543  1804  8259 E DriveAsyncService: 	at com.google.android.gms.drive.database.i.c(SourceFile:438)
08-17 14:27:09.543  1804  8259 E DriveAsyncService: 	at com.google.android.gms.drive.database.d.g(SourceFile:1384)
08-17 14:27:09.543  1804  8259 E DriveAsyncService: 	at com.google.android.gms.drive.api.a.al.a(SourceFile:15)
08-17 14:27:09.543  1804  8259 E DriveAsyncService: 	at com.google.android.gms.common.service.c.onHandleIntent(SourceFile:60)
08-17 14:27:09.543  1804  8259 E DriveAsyncService: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-17 14:27:09.543  1804  8259 E DriveAsyncService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 14:27:09.543  1804  8259 E DriveAsyncService: 	at android.os.Looper.loop(Looper.java:135)
08-17 14:27:09.543  1804  8259 E DriveAsyncService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-17 14:27:09.549  8269  8269 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-17 14:27:09.550  8269  8269 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-17 14:27:09.550  8269  8269 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-17 14:27:09.551  8269  8269 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-17 14:27:09.553  4486  4536 E SQLiteDatabase: Error inserting f004=13 f005=8269 f002=1471436829466 f003=com.lge.email f006=10023
08-17 14:27:09.553  4486  4536 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
08-17 14:27:09.553  4486  4536 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
08-17 14:27:09.553  4486  4536 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:787)
08-17 14:27:09.553  4486  4536 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:926)
08-17 14:27:09.553  4486  4536 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
08-17 14:27:09.553  4486  4536 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1572)
08-17 14:27:09.553  4486  4536 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1442)
08-17 14:27:09.553  4486  4536 E SQLiteDatabase: 	at com.lge.mlt.MptMainLogProvider.insert(MptMainLogProvider.java:1340)
08-17 14:27:09.553  4486  4536 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:238)
08-17 14:27:09.553  4486  4536 E SQLiteDatabase: 	at android.content.ContentResolver.insert(ContentResolver.java:1223)
08-17 14:27:09.553  4486  4536 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService.insertProcessInfoLog(MltMonitorService.java:2585)
08-17 14:27:09.553  4486  4536 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService.access$2700(MltMonitorService.java:38)
08-17 14:27:09.553  4486  4536 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService$DbFlushManager$1.handleMessage(MltMonitorService.java:3409)
08-17 14:27:09.553  4486  4536 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 14:27:09.553  4486  4536 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-17 14:27:09.553  4486  4536 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService$DbFlushManager.run(MltMonitorService.java:3518)
08-17 14:27:09.561  8238  8255 E DG      : Failed to touch cache.
08-17 14:27:09.561  8238  8255 E DG      : com.google.android.gms.droidguard.c.b: Failed to update last-used timestamp for com.google.android.gms.droidguard.c.ab@3f8bc126.
08-17 14:27:09.561  8238  8255 E DG      : 	at com.google.android.gms.droidguard.c.ac.a(SourceFile:117)
08-17 14:27:09.561  8238  8255 E DG      : 	at com.google.android.gms.droidguard.c.ac.b(SourceFile:41)
08-17 14:27:09.561  8238  8255 E DG      : 	at com.google.android.gms.droidguard.c.i.a(SourceFile:77)
08-17 14:27:09.561  8238  8255 E DG      : 	at com.google.android.gms.droidguard.c.k.a(SourceFile:92)
08-17 14:27:09.561  8238  8255 E DG      : 	at com.google.android.gms.droidguard.c.h.a(SourceFile:73)
08-17 14:27:09.561  8238  8255 E DG      : 	at com.google.android.gms.droidguard.c.k.a(SourceFile:92)
08-17 14:27:09.561  8238  8255 E DG      : 	at com.google.android.gms.droidguard.c.e.a(SourceFile:73)
08-17 14:27:09.561  8238  8255 E DG      : 	at com.google.android.gms.droidguard.l.a(SourceFile:208)
08-17 14:27:09.561  8238  8255 E DG      : 	at com.google.android.gms.droidguard.b.t.onTransact(SourceFile:60)
08-17 14:27:09.561  8238  8255 E DG      : 	at android.os.Binder.execTransact(Binder.java:446)
,08-17 14:27:09.586  8269  8269 E SQLiteDatabase: Failed to open database '/data/data/com.lge.email/databases/Downloads.db'.
08-17 14:27:09.586  8269  8269 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 14:27:09.586  8269  8269 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-17 14:27:09.586  8269  8269 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-17 14:27:09.586  8269  8269 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-17 14:27:09.586  8269  8269 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-17 14:27:09.586  8269  8269 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-17 14:27:09.586  8269  8269 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-17 14:27:09.586  8269  8269 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-17 14:27:09.586  8269  8269 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-17 14:27:09.586  8269  8269 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-17 14:27:09.586  8269  8269 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-17 14:27:09.586  8269  8269 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-17 14:27:09.586  8269  8269 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-17 14:27:09.586  8269  8269 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-17 14:27:09.586  8269  8269 E SQLiteDatabase: 	at com.lge.email.ui.largefile.DownloadProvider.onCreate(DownloadProvider.java:51)
08-17 14:27:09.586  8269  8269 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
08-17 14:27:09.586  8269  8269 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
08-17 14:27:09.586  8269  8269 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
08-17 14:27:09.586  8269  8269 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-17 14:27:09.586  8269  8269 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-17 14:27:09.586  8269  8269 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-17 14:27:09.586  8269  8269 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-17 14:27:09.586  8269  8269 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 14:27:09.586  8269  8269 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-17 14:27:09.586  8269  8269 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-17 14:27:09.586  8269  8269 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 14:27:09.586  8269  8269 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 14:27:09.586  8269  8269 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-17 14:27:09.586  8269  8269 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-17 14:27:09.586  8269  8269 W System.err: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 14:27:09.586  8269  8269 W System.err: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-17 14:27:09.586  8269  8269 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-17 14:27:09.586  8269  8269 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-17 14:27:09.586  8269  8269 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-17 14:27:09.586  8269  8269 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-17 14:27:09.586  8269  8269 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-17 14:27:09.586  8269  8269 W System.err: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-17 14:27:09.586  8269  8269 W System.err: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-17 14:27:09.586  8269  8269 W System.err: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-17 14:27:09.586  8269  8269 W System.err: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-17 14:27:09.586  8269  8269 W System.err: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-17 14:27:09.586  8269  8269 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-17 14:27:09.586  8269  8269 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-17 14:27:09.586  8269  8269 W System.err: 	at com.lge.email.ui.largefile.DownloadProvider.onCreate(DownloadProvider.java:51)
08-17 14:27:09.586  8269  8269 W System.err: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
08-17 14:27:09.586  8269  8269 W System.err: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
08-17 14:27:09.586  8269  8269 W System.err: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
08-17 14:27:09.586  8269  8269 W System.err: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-17 14:27:09.586  8269  8269 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-17 14:27:09.586  8269  8269 W System.err: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-17 14:27:09.586  8269  8269 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-17 14:27:09.586  8269  8269 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 14:27:09.586  8269  8269 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-17 14:27:09.586  8269  8269 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-17 14:27:09.586  8269  8269 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 14:27:09.586  8269  8269 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 14:27:09.587  8269  8269 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-17 14:27:09.587  8269  8269 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-17 14:27:09.587  2020  2020 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
08-17 14:27:09.593  8269  8269 E SQLiteDatabase: Failed to open database '/data/data/com.lge.email/databases/sqt.db'.
08-17 14:27:09.593  8269  8269 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 14:27:09.593  8269  8269 E SQLiteDatabase: 	at android.database.s,qlite.SQLiteConnection.nativeOpen(Native Method)
08-17 14:27:09.593  8269  8269 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-17 14:27:09.593  8269  8269 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-17 14:27:09.593  8269  8269 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-17 14:27:09.593  8269  8269 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-17 14:27:09.593  8269  8269 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-17 14:27:09.593  8269  8269 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-17 14:27:09.593  8269  8269 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-17 14:27:09.593  8269  8269 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-17 14:27:09.593  8269  8269 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-17 14:27:09.593  8269  8269 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-17 14:27:09.593  8269  8269 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-17 14:27:09.593  8269  8269 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-17 14:27:09.593  8269  8269 E SQLiteDatabase: 	at com.lge.email.providers.sqt.SqtProvider.onCreate(SqtProvider.java:155)
08-17 14:27:09.593  8269  8269 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
08-17 14:27:09.593  8269  8269 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
08-17 14:27:09.593  8269  8269 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
08-17 14:27:09.593  8269  8269 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-17 14:27:09.593  8269  8269 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-17 14:27:09.593  8269  8269 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-17 14:27:09.593  8269  8269 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-17 14:27:09.593  8269  8269 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 14:27:09.593  8269  8269 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-17 14:27:09.593  8269  8269 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-17 14:27:09.593  8269  8269 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 14:27:09.593  8269  8269 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 14:27:09.593  8269  8269 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-17 14:27:09.593  8269  8269 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-17 14:27:09.593  8269  8269 D AndroidRuntime: Shutting down VM
--------- beginning of crash
08-17 14:27:09.594  8269  8269 E AndroidRuntime: FATAL EXCEPTION: main
08-17 14:27:09.594  8269  8269 E AndroidRuntime: Process: com.lge.email, PID: 8269
08-17 14:27:09.594  8269  8269 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.lge.email.providers.sqt.SqtProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 14:27:09.594  8269  8269 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5017)
08-17 14:27:09.594  8269  8269 E AndroidRuntime: 	at android.,app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-17 14:27:09.594  8269  8269 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-17 14:27:09.594  8269  8269 E AndroidRuntime: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-17 14:27:09.594  8269  8269 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-17 14:27:09.594  8269  8269 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 14:27:09.594  8269  8269 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
08-17 14:27:09.594  8269  8269 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-17 14:27:09.594  8269  8269 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 14:27:09.594  8269  8269 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 14:27:09.594  8269  8269 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-17 14:27:09.594  8269  8269 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-17 14:27:09.594  8269  8269 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 14:27:09.594  8269  8269 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-17 14:27:09.594  8269  8269 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-17 14:27:09.594  8269  8269 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-17 14:27:09.594  8269  8269 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-17 14:27:09.594  8269  8269 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-17 14:27:09.594  8269  8269 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-17 14:27:09.594  8269  8269 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-17 14:27:09.594  8269  8269 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-17 14:27:09.594  8269  8269 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-17 14:27:09.594  8269  8269 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-17 14:27:09.594  8269  8269 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-17 14:27:09.594  8269  8269 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-17 14:27:09.594  8269  8269 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-17 14:27:09.594  8269  8269 E AndroidRuntime: 	at com.lge.email.providers.sqt.SqtProvider.onCreate(SqtProvider.java:155)
08-17 14:27:09.594  8269  8269 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
08-17 14:27:09.594  8269  8269 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
08-17 14:27:09.594  8269  8269 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
08-17 14:27:09.594  8269  8269 E AndroidRuntime: 	... 11 more
08-17 14:27:09.597  8269  8269 I Process : Sending signal. PID: 8269 SIG: 9

```
