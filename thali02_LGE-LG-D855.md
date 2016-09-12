#### Test 830701775d60530_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
09-12 14:43:00.107  1599  1599 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-12 14:43:00.107  1599  1599 I KeyguardUpdateMonitor: called onTimeUpdated()
,09-12 14:43:00.113  1599  1599 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
09-12 14:43:00.114  1599  1599 I [SystemUI]Clock: called onTimeUpdated()
09-12 14:43:00.120  1599  1599 I LgeClockWidgetControlView: called onTimeUpdated()
09-12 14:43:00.120  1599  1599 I [SystemUI]DateView: called onTimeUpdated()
09-12 14:43:00.121  1599  1599 I [SystemUI]DateView: called onTimeUpdated()
09-12 14:43:00.122  1599  1599 D KeyguardUpdateMonitor: handleTimeUpdate
09-12 14:43:00.411  6649  6649 D AndroidRuntime: 
09-12 14:43:00.411  6649  6649 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-12 14:43:00.414  6649  6649 D AndroidRuntime: CheckJNI is OFF
09-12 14:43:00.541  6649  6649 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-12 14:43:00.546  1032  1997 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-12 14:43:00.555  1941  1956 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
09-12 14:43:00.568  1032  1997 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
09-12 14:43:00.571  1032  1997 D ActivityManager: setTaskToReturnTo : TaskRecord{3fb760ac #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-12 14:43:00.571  1032  1997 D ActivityManager: setTaskToReturnTo : TaskRecord{3fb760ac #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-12 14:43:00.574  1032  1997 D WindowStateEx: AppWindowTokenEx init.. 
09-12 14:43:00.575   331   393 E GBMv2   : DFP En is all cleared set to be enabled
09-12 14:43:00.602  1032  1997 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6669 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-12 14:43:00.603  6649  6649 D AndroidRuntime: Shutting down VM
09-12 14:43:00.656  1941  1956 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
09-12 14:43:00.657  1941  1956 D SplitWindowPolicy: topRunningActivity=ActivityInfo{22d5b36f co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
09-12 14:43:00.658  1941  1957 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
09-12 14:43:00.658  1941  1957 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2883687c co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
,09-12 14:43:00.718  6669  6669 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
09-12 14:43:00.826  6669  6669 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,09-12 14:43:00.836  6669  6669 I LibraryLoader: Loading: webviewchromium
09-12 14:43:00.839  6669  6669 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 447-451)
,09-12 14:43:00.840  6669  6669 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-12 14:43:00.856  6669  6669 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {344495f5}
,09-12 14:43:00.858  6669  6669 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-12 14:43:00.859  6669  6669 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
09-12 14:43:00.869  6669  6669 I BrowserStartupController: Initializing chromium process, renderers=0
,09-12 14:43:00.870  6669  6669 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-12 14:43:00.888  6669  6669 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,09-12 14:43:00.891  6669  6669 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
09-12 14:43:00.891  6669  6669 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
09-12 14:43:00.896   311  2164 V AudioPolicyService: registerClient() client 0xb558a840, uid 10118
09-12 14:43:00.900  1032  1094 D BluetoothManagerService: Message: 20
09-12 14:43:00.900  1032  1094 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@252697d6:true
,09-12 14:43:00.911  6669  6669 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-12 14:43:00.911  6669  6669 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-12 14:43:00.911  6669  6669 I Adreno-EGL: Build Date: 12/12/14 금
09-12 14:43:00.911  6669  6669 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-12 14:43:00.911  6669  6669 I Adreno-EGL: Remote Branch: 
09-12 14:43:00.911  6669  6669 I Adreno-EGL: Local Patches: 
09-12 14:43:00.911  6669  6669 I Adreno-EGL: Reconstruct Branch: 
09-12 14:43:00.982  6669  6699 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,09-12 14:43:00.989  6669  6669 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
09-12 14:43:01.007  6669  6669 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-12 14:43:01.013  6669  6669 W AwContents: onDetachedFromWindow called when already detached. Ignoring
09-12 14:43:01.017  6669  6669 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
09-12 14:43:01.021  6669  6669 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
09-12 14:43:01.021  6669  6669 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,09-12 14:43:01.037  6669  6669 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,09-12 14:43:01.044  6669  6669 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-12 14:43:01.044  6669  6669 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-12 14:43:01.078  6669  6711 D OpenGLRenderer: Render dirty regions requested: true
09-12 14:43:01.078  6669  6711 I OpenGLRenderer: Initialized EGL, version 1.4
09-12 14:43:01.084  6669  6711 D OpenGLRenderer: Enabling debug mode 0
,09-12 14:43:01.091  6669  6669 D Atlas   : Validating map...
09-12 14:43:01.095  1032  1048 D SplitWindow: check instance of lgWin Window{b82bae0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-12 14:43:01.170  6669  6709 D LgDataFeature: LgDataFeature() Constructor: none
09-12 14:43:01.170  6669  6709 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-12 14:43:01.189  1032  1095 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +534ms (total +613ms)
09-12 14:43:01.189  1032  1095 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3190c175 u0 com.test.thalitest/.MainActivity t6} time:180802
,09-12 14:43:01.190  6669  6669 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@363d3948 time:180802
09-12 14:43:01.331  6669  6669 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
09-12 14:43:01.331  6669  6669 I chromium: 
,09-12 14:43:01.372  6669  6669 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-12 14:43:01.444  6669  6709 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
09-12 14:43:01.444  6669  6709 I chromium: 
,09-12 14:43:01.580  6669  6722 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435141120
,09-12 14:43:01.595  6669  6722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-12 14:43:01.595  6669  6722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-12 14:43:01.595  6669  6722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-12 14:43:01.595  6669  6722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-12 14:43:01.595  6669  6722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-12 14:43:01.595  6669  6722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f7a3b8c added. We now have 1 listener(s)
09-12 14:43:01.601  1032  1048 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-12 14:43:01.604  6669  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
09-12 14:43:01.607  6669  6722 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-12 14:43:01.609  6669  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 14:43:01.609  6669  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 14:43:01.617  6669  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-12 14:43:01.617  6669  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-12 14:43:01.617  6669  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-12 14:43:01.617  6669  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
09-12 14:43:01.617  6669  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-12 14:43:01.617  6669  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-12 14:43:01.617  6669  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-12 14:43:01.617  6669  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-12 14:43:01.617  6669  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-12 14:43:01.617  6669  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-12 14:43:01.617  6669  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-12 14:43:01.617  6669  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-12 14:43:01.617  6669  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-12 14:43:01.617  6669  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-12 14:43:01.617  6669  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f8711db added. We now have 1 listener(s)
,09-12 14:43:01.618  6669  6722 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 14:43:01.624  1032  1454 D WifiService: New client listening to asynchronous messages
09-12 14:43:01.628  6669  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-12 14:43:01.628  6669  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-12 14:43:01.630  6669  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-12 14:43:01.630  6669  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-12 14:43:01.630  6669  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-12 14:43:01.634  6669  6722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 14:43:01.635  1032  1572 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 14:43:01.636  6669  6722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
09-12 14:43:01.644  6669  6722 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
09-12 14:43:01.645  6669  6722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 14:43:01.645  6669  6722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 14:43:01.645  6669  6722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 14:43:01.645  6669  6722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 14:43:01.645  6669  6722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 14:43:01.645  6669  6722 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 14:43:01.645  6669  6722 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 14:43:01.645  6669  6722 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 14:43:01.645  6669  6722 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-12 14:43:01.645  6669  6722 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 14:43:01.646  6669  6722 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-12 14:43:01.650  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 14:43:01.652  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 14:43:01.687  6669  6669 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-12 14:43:02.262   331   397 E GBMv2   : DFP En is all cleared set to be enabled
,09-12 14:43:02.262   331   397 E GBMv2   : Set value is all cleared set the max
09-12 14:43:02.262   331   397 I GBMv2   : DFP Enabled. Ignore VFP set
,09-12 14:43:02.423  6669  6725 W jxcore-log: Initializing JXcore engine
,09-12 14:43:02.425  6669  6725 W jxcore-log: JXcore engine is ready
09-12 14:43:02.451  6725  6725 W Thread-762: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[9921]" dev="sockfs" ino=9921 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
09-12 14:43:02.451  6725  6725 W Thread-762: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
09-12 14:43:02.451  6725  6725 W Thread-762: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[10377]" dev="sockfs" ino=10377 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,09-12 14:43:02.451  6725  6725 W Thread-762: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
09-12 14:43:02.451  6725  6725 W Thread-762: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[31589]" dev="sockfs" ino=31589 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
09-12 14:43:02.476  6669  6725 W jxcore-log: Starting JXcore engine
,09-12 14:43:02.551  6669  6725 W jxcore-log: Platform android
09-12 14:43:02.551  6669  6725 W jxcore-log: 
09-12 14:43:02.551  6669  6725 W jxcore-log: Process ARCH arm
09-12 14:43:02.551  6669  6725 W jxcore-log: 
,09-12 14:43:02.747  6669  6725 I jxcore-log: JXcore Cordova bridge is ready!
09-12 14:43:02.747  6669  6725 I jxcore-log: 
09-12 14:43:02.748  6669  6725 W jxcore-log: JXcore engine is started
,09-12 14:43:02.757  6669  6722 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
09-12 14:43:02.762  6669  6669 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-12 14:43:12.336  6669  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-12 14:43:12.336  6669  6725 I jxcore-log: 
,09-12 14:43:12.340  6669  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-12 14:43:12.340  6669  6725 I jxcore-log: 
,09-12 14:43:12.344  6669  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 14:43:12.344  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 14:43:12.344  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 14:43:12.344  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 14:43:12.344  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 14:43:12.344  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 14:43:12.344  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 14:43:12.344  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 14:43:12.346  6669  6725 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 14:43:12.349  6669  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-12 14:43:12.349  6669  6725 I jxcore-log: 
09-12 14:43:12.351  6669  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-12 14:43:12.351  6669  6725 I jxcore-log: 
,09-12 14:43:12.852  6669  6725 D executeNativeTests: Running unit tests,
,09-12 14:43:12.933  6669  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-12 14:43:12.933  6669  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@165175c added. We now have 2 listener(s)
,09-12 14:43:12.934  1032  1780 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 14:43:12.936  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-12 14:43:12.936  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 14:43:12.936  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 14:43:12.936  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 14:43:12.936  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12512a65 added. We now have 2 listener(s)
09-12 14:43:12.936  6669  6725 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 14:43:12.936  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 14:43:12.939  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 14:43:12.941  6669  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 14:43:12.941  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 14:43:12.941  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 14:43:12.941  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 14:43:12.941  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 14:43:12.941  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 14:43:12.941  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 14:43:12.941  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 14:43:12.942  6669  6725 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 14:43:12.942  6669  6725 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 14:43:12.943  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 14:43:12.944  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 14:43:12.947  6669  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-12 14:43:12.950  6669  6725 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-12 14:43:12.950  6669  6725 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-12 14:43:12.951  6669  6725 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out,
09-12 14:43:12.952  6669  6725 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-12 14:43:12.952  6669  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect,
,09-12 14:43:12.952  6669  6725 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1,
09-12 14:43:12.952  6669  6725 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1,
,09-12 14:43:12.953  6669  6725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 14:43:12.954  6669  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
09-12 14:43:12.954  6669  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 14:43:12.954  6669  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 14:43:12.954  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:43:12.954  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 14:43:12.954  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...,
09-12 14:43:12.954  6669  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@165175c removed from the list
09-12 14:43:12.954  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:43:12.955  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12512a65 removed from the list
09-12 14:43:12.955  6669  6725 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 14:43:12.955  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:43:12.955  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:43:12.955  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:43:12.956  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 14:43:12.956  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 14:43:12.956  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:43:12.956  6669  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12512a65 not in the list
09-12 14:43:12.958  6669  6725 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-12 14:43:12.958  6669  6725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 14:43:12.958  6669  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 14:43:12.958  6669  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 14:43:12.958  6669  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 14:43:12.958  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:43:12.958  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:43:12.958  6669  6725 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@165175c not in the list
09-12 14:43:12.958  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
09-12 14:43:12.958  6669  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12512a65 not in the list
09-12 14:43:12.958  6669  6725 D io.jxcore.node.ConnectivityMonitor: stop
09-12 14:43:12.958  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:43:12.958  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 14:43:12.958  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:43:12.958  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:43:12.959  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 14:43:12.959  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 14:43:12.959  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:43:12.959  6669  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12512a65 not in the list
09-12 14:43:12.964  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-12 14:43:12.964  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-12 14:43:12.964  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-12 14:43:12.964  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210],
09-12 14:43:12.964  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-12 14:43:12.964  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-12 14:43:12.964  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-12 14:43:12.964  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-12 14:43:12.964  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710],
09-12 14:43:12.965  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-12 14:43:12.965  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-12 14:43:12.965  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-12 14:43:12.965  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-12 14:43:12.965  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210],
09-12 14:43:12.965  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-12 14:43:12.965  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-12 14:43:12.965  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-12 14:43:12.965  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,09-12 14:43:12.965  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-12 14:43:12.965  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-12 14:43:12.965  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-12 14:43:12.965  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-12 14:43:12.965  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-12 14:43:12.965  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210],
09-12 14:43:12.965  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-12 14:43:12.965  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-12 14:43:12.965  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-12 14:43:12.965  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-12 14:43:12.965  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,09-12 14:43:12.965  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-12 14:43:12.965  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-12 14:43:12.965  6669  6725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 14:43:12.965  6669  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 14:43:12.965  6669  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 14:43:12.966  6669  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 14:43:12.966  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:43:12.966  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:43:12.966  6669  6725 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@165175c not in the list
,09-12 14:43:12.966  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:43:12.966  6669  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12512a65 not in the list
09-12 14:43:12.966  6669  6725 D io.jxcore.node.ConnectivityMonitor: stop
09-12 14:43:12.966  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:43:12.966  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 14:43:12.966  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:43:12.966  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:43:12.967  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 14:43:12.967  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 14:43:12.967  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 14:43:12.967  6669  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12512a65 not in the list
09-12 14:43:12.968  6669  6725 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-12 14:43:12.971  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 14:43:12.973  6669  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 14:43:12.973  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 14:43:12.973  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 14:43:12.973  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 14:43:12.973  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 14:43:12.973  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 14:43:12.973  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 14:43:12.973  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 14:43:12.976  6669  6725 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 14:43:12.976  6669  6725 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 14:43:12.977  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 14:43:12.978  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 14:43:12.978  6669  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only,
09-12 14:43:12.979  6669  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 14:43:12.979  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 14:43:12.979  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 14:43:12.979  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-12 14:43:12.982  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-12 14:43:12.983  1032  1932 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 14:43:12.989  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-12 14:43:12.996  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 14:43:12.998  6669  6725 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
09-12 14:43:12.999  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-12 14:43:12.999  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 14:43:13.000  6669  6725 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-12 14:43:13.001  6669  6725 I io.jxcore.node.ConnectionHelper: start: OK
09-12 14:43:13.003  6669  6725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 14:43:13.003  6669  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 14:43:13.003  6669  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 14:43:13.003  6669  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 14:43:13.003  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:43:13.003  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 14:43:13.004  6669  6725 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@165175c not in the list
09-12 14:43:13.004  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:43:13.004  6669  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12512a65 not in the list
09-12 14:43:13.004  6669  6725 D io.jxcore.node.ConnectivityMonitor: stop
09-12 14:43:13.004  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:43:13.004  6669  6725 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-12 14:43:13.005  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 14:43:13.007  6669  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 14:43:13.007  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 14:43:13.007  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 14:43:13.007  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 14:43:13.007  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 14:43:13.007  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 14:43:13.007  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 14:43:13.007  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 14:43:13.009  6669  6725 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 14:43:13.009  6669  6725 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 14:43:13.010  6669  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 14:43:13.010  6669  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 14:43:13.010  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 14:43:13.010  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 14:43:13.010  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-12 14:43:13.011  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 14:43:13.013  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 14:43:13.014  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-12 14:43:13.014  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 14:43:13.015  6669  6725 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-12 14:43:13.015  6669  6725 I io.jxcore.node.ConnectionHelper: start: OK
09-12 14:43:13.016  6669  6725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 14:43:13.016  6669  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 14:43:13.016  6669  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 14:43:13.016  6669  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 14:43:13.016  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:43:13.017  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 14:43:13.017  6669  6725 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@165175c not in the list
09-12 14:43:13.017  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:43:13.017  6669  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12512a65 not in the list
09-12 14:43:13.017  6669  6725 D io.jxcore.node.ConnectivityMonitor: stop
09-12 14:43:13.017  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:43:13.017  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:43:13.017  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:43:13.017  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 14:43:13.017  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 14:43:13.018  6669  6725 D BluetoothLeScanner: could not find callback wrapper
09-12 14:43:13.019  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 14:43:13.019  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:43:13.019  6669  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12512a65 not in the list
09-12 14:43:13.019  6669  6725 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-12 14:43:13.020  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 14:43:13.024  6669  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 14:43:13.024  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 14:43:13.024  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 14:43:13.024  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 14:43:13.024  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 14:43:13.024  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 14:43:13.024  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 14:43:13.024  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 14:43:13.026  6669  6725 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 14:43:13.026  6669  6725 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 14:43:13.027  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 14:43:13.028  6669  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 14:43:13.028  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 14:43:13.028  6669  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 14:43:13.028  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 14:43:13.028  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 14:43:13.028  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-12 14:43:13.031  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-12 14:43:13.032  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 14:43:13.033  6669  6725 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-12 14:43:13.033  6669  6725 I io.jxcore.node.ConnectionHelper: start: OK
09-12 14:43:13.033  6669  6725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 14:43:13.033  6669  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 14:43:13.033  6669  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 14:43:13.034  6669  6725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 14:43:13.034  6669  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 14:43:13.034  6669  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 14:43:13.034  6669  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 14:43:13.034  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:43:13.034  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 14:43:13.034  6669  6725 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@165175c not in the list
09-12 14:43:13.034  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:43:13.035  6669  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12512a65 not in the list
09-12 14:43:13.035  6669  6725 D io.jxcore.node.ConnectivityMonitor: stop
09-12 14:43:13.035  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:43:13.035  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:43:13.035  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:43:13.036  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 14:43:13.036  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 14:43:13.037  6669  6725 D BluetoothLeScanner: could not find callback wrapper
09-12 14:43:13.037  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 14:43:13.037  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:43:13.037  6669  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12512a65 not in the list
09-12 14:43:13.037  6669  6725 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-12 14:43:13.037  6669  6725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 14:43:13.037  6669  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 14:43:13.037  6669  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 14:43:13.038  6669  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 14:43:13.038  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:43:13.038  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:43:13.038  6669  6725 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@165175c not in the list
09-12 14:43:13.038  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:43:13.038  6669  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12512a65 not in the list
09-12 14:43:13.038  6669  6725 D io.jxcore.node.ConnectivityMonitor: stop
09-12 14:43:13.038  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:43:13.038  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:43:13.038  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:43:13.038  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:43:13.038  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 14:43:13.038  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 14:43:13.039  6669  6725 D BluetoothLeScanner: could not find callback wrapper
09-12 14:43:13.039  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 14:43:13.039  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:43:13.039  6669  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12512a65 not in the list
09-12 14:43:13.039  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-12 14:43:13.040  6669  6725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 14:43:13.040  6669  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 14:43:13.040  6669  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 14:43:13.040  6669  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 14:43:13.040  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:43:13.040  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:43:13.040  6669  6725 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@165175c not in the list
09-12 14:43:13.040  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:43:13.040  6669  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12512a65 not in the list
09-12 14:43:13.040  6669  6725 D io.jxcore.node.ConnectivityMonitor: stop
09-12 14:43:13.040  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:43:13.040  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:43:13.040  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:43:13.040  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:43:13.041  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 14:43:13.041  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 14:43:13.041  6669  6725 D BluetoothLeScanner: could not find callback wrapper
09-12 14:43:13.041  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 14:43:13.041  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:43:13.041  6669  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12512a65 not in the list
09-12 14:43:13.042  6669  6725 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-12 14:43:13.042  6669  6725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 14:43:13.042  6669  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 14:43:13.042  6669  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 14:43:13.042  6669  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 14:43:13.042  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:43:13.042  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:43:13.043  6669  6725 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@165175c not in the list
09-12 14:43:13.043  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:43:13.043  6669  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12512a65 not in the list
09-12 14:43:13.043  6669  6725 D io.jxcore.node.ConnectivityMonitor: stop
09-12 14:43:13.043  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:43:13.043  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:43:13.043  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:43:13.043  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:43:13.046  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 14:43:13.046  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 14:43:13.048  6669  6725 D BluetoothLeScanner: could not find callback wrapper
09-12 14:43:13.048  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 14:43:13.048  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:43:13.048  6669  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12512a65 not in the list
09-12 14:43:13.050  6669  6725 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-12 14:43:13.050  6669  6725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 14:43:13.050  6669  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 14:43:13.050  6669  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 14:43:13.050  6669  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 14:43:13.050  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:43:13.050  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:43:13.050  6669  6725 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@165175c not in the list
09-12 14:43:13.050  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:43:13.050  6669  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12512a65 not in the list
09-12 14:43:13.050  6669  6725 D io.jxcore.node.ConnectivityMonitor: stop
09-12 14:43:13.050  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:43:13.050  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:43:13.050  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:43:13.050  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:43:13.051  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 14:43:13.051  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 14:43:13.051  6669  6725 D BluetoothLeScanner: could not find callback wrapper
09-12 14:43:13.051  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 14:43:13.051  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:43:13.051  6669  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12512a65 not in the list
09-12 14:43:13.052  6669  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-12 14:43:13.053  6669  6725 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-12 14:43:13.053  6669  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-12 14:43:13.053  6669  6725 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-12 14:43:13.053  6669  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-12 14:43:13.053  6669  6725 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-12 14:43:13.053  6669  6725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 14:43:13.053  6669  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 14:43:13.053  6669  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 14:43:13.053  6669  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 14:43:13.053  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:43:13.053  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:43:13.053  6669  6725 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@165175c not in the list
09-12 14:43:13.053  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:43:13.053  6669  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12512a65 not in the list
09-12 14:43:13.053  6669  6725 D io.jxcore.node.ConnectivityMonitor: stop
09-12 14:43:13.053  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:43:13.053  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:43:13.054  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:43:13.054  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:43:13.054  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 14:43:13.054  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 14:43:13.055  6669  6725 D BluetoothLeScanner: could not find callback wrapper
09-12 14:43:13.055  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 14:43:13.055  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:43:13.055  6669  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12512a65 not in the list
09-12 14:43:13.056  6669  6725 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 14:43:13.056  6669  6725 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-12 14:43:13.056  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-12 14:43:13.059  6669  6725 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 14:43:13.059  6669  6725 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-12 14:43:13.059  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-12 14:43:13.059  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-12 14:43:13.059  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-12 14:43:13.059  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-12 14:43:13.059  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-12 14:43:13.059  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-12 14:43:13.059  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-12 14:43:13.059  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-12 14:43:13.059  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-12 14:43:13.059  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-12 14:43:13.059  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-12 14:43:13.059  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-12 14:43:13.059  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-12 14:43:13.059  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-12 14:43:13.059  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-12 14:43:13.059  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-12 14:43:13.059  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-12 14:43:13.059  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-12 14:43:13.059  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-12 14:43:13.059  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-12 14:43:13.059  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-12 14:43:13.059  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-12 14:43:13.059  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-12 14:43:13.059  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-12 14:43:13.059  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-12 14:43:13.059  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-12 14:43:13.060  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-12 14:43:13.060  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-12 14:43:13.060  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-12 14:43:13.060  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-12 14:43:13.060  6669  6725 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-12 14:43:13.060  6669  6725 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-12 14:43:13.060  6669  6725 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-12 14:43:13.060  6669  6725 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 14:43:13.061  6669  6725 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-12 14:43:13.061  6669  6725 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-12 14:43:13.061  6669  6725 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 14:43:13.061  6669  6725 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-12 14:43:13.061  6669  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-12 14:43:13.062  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-12 14:43:13.063  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
,09-12 14:43:13.063  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-12 14:43:13.064  6669  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-12 14:43:13.064  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-12 14:43:13.064  6669  6725 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-12 14:43:13.064  6669  6725 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 14:43:13.064  6669  6725 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-12 14:43:13.064  6669  6725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 14:43:13.064  6669  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 14:43:13.064  6669  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 14:43:13.065  6669  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 14:43:13.065  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:43:13.065  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:43:13.065  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-12 14:43:13.065  6669  6725 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@165175c not in the list
09-12 14:43:13.065  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:43:13.065  6669  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12512a65 not in the list
09-12 14:43:13.065  6669  6725 D io.jxcore.node.ConnectivityMonitor: stop
09-12 14:43:13.065  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:43:13.065  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:43:13.065  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:43:13.066  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:43:13.067  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 14:43:13.069  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 14:43:13.071  6669  6725 D BluetoothLeScanner: could not find callback wrapper
09-12 14:43:13.071  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 14:43:13.071  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:43:13.071  6669  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12512a65 not in the list
09-12 14:43:13.072  6669  6725 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-12 14:43:13.072  6669  6725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 14:43:13.072  6669  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 14:43:13.072  6669  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 14:43:13.072  6669  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 14:43:13.072  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:43:13.072  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:43:13.072  6669  6725 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@165175c not in the list
09-12 14:43:13.072  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:43:13.072  6669  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12512a65 not in the list
09-12 14:43:13.072  6669  6725 D io.jxcore.node.ConnectivityMonitor: stop
09-12 14:43:13.072  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:43:13.072  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:43:13.072  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:43:13.072  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:43:13.073  6669  6730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 826)
09-12 14:43:13.073  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 14:43:13.073  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 14:43:13.074  6669  6725 D BluetoothLeScanner: could not find callback wrapper
09-12 14:43:13.074  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 14:43:13.074  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:43:13.074  6669  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12512a65 not in the list
09-12 14:43:13.076  6669  6725 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-12 14:43:13.076  6669  6725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 14:43:13.076  6669  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 14:43:13.076  6669  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 14:43:13.076  6669  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 14:43:13.076  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:43:13.076  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:43:13.076  6669  6725 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@165175c not in the list
09-12 14:43:13.076  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:43:13.076  6669  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12512a65 not in the list
09-12 14:43:13.076  6669  6725 D io.jxcore.node.ConnectivityMonitor: stop
09-12 14:43:13.076  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:43:13.076  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:43:13.076  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:43:13.076  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:43:13.078  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 14:43:13.078  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 14:43:13.079  6669  6725 D BluetoothLeScanner: could not find callback wrapper
09-12 14:43:13.079  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 14:43:13.079  6669  6731 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 826
09-12 14:43:13.079  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:43:13.079  6669  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12512a65 not in the list
09-12 14:43:13.080  6669  6731 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 826)
09-12 14:43:13.081  6669  6731 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 826)
09-12 14:43:13.082  6669  6725 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-12 14:43:13.082  6669  6725 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-12 14:43:13.082  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-12 14:43:13.082  6669  6725 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-12 14:43:13.082  6669  6725 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-12 14:43:13.083  6669  6725 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-12 14:43:13.083  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-12 14:43:13.083  6669  6725 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-12 14:43:13.083  6669  6725 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-12 14:43:13.083  6669  6725 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-12 14:43:13.083  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-12 14:43:13.083  6669  6725 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-12 14:43:13.083  6669  6725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 14:43:13.083  6669  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 14:43:13.083  6669  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 14:43:13.083  6669  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 14:43:13.083  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:43:13.083  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:43:13.084  6669  6725 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@165175c not in the list
09-12 14:43:13.084  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:43:13.084  6669  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12512a65 not in the list
09-12 14:43:13.084  6669  6725 D io.jxcore.node.ConnectivityMonitor: stop
09-12 14:43:13.084  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:43:13.084  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:43:13.084  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:43:13.084  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:43:13.084  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 14:43:13.084  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 14:43:13.085  6669  6725 D BluetoothLeScanner: could not find callback wrapper
09-12 14:43:13.085  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 14:43:13.085  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:43:13.085  6669  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12512a65 not in the list
09-12 14:43:13.085  6669  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 14:43:13.085  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:43:13.085  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:43:13.085  6669  6725 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@165175c not in the list
09-12 14:43:13.085  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:43:13.085  6669  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12512a65 not in the list
09-12 14:43:13.085  6669  6725 D io.jxcore.node.ConnectivityMonitor: stop
09-12 14:43:13.085  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:43:13.085  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:43:13.086  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:43:13.086  6669  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12512a65 not in the list
09-12 14:43:13.086  6669  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 14:43:13.086  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:43:13.086  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:43:13.086  6669  6725 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@165175c not in the list
09-12 14:43:13.086  6669  6725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 14:43:13.086  6669  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 14:43:13.086  6669  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 14:43:13.086  6669  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 14:43:13.086  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:43:13.086  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:43:13.087  6669  6725 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@165175c not in the list
09-12 14:43:13.087  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:43:13.087  6669  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12512a65 not in the list
09-12 14:43:13.087  6669  6725 D io.jxcore.node.ConnectivityMonitor: stop
09-12 14:43:13.087  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:43:13.087  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:43:13.087  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:43:13.087  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:43:13.087  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 14:43:13.087  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 14:43:13.088  6669  6725 D BluetoothLeScanner: could not find callback wrapper
09-12 14:43:13.088  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 14:43:13.088  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:43:13.088  6669  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12512a65 not in the list
09-12 14:43:13.089  6669  6725 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-12 14:43:13.089  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 14:43:13.090  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-12 14:43:13.090  6669  6725 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-12 14:43:13.090  6669  6725 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-12 14:43:13.091  6669  6669 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-12 14:43:13.092  6669  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-12 14:43:13.092  6669  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-12 14:43:13.093  6669  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 14:43:13.093  6669  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-12 14:43:13.093  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-12 14:43:13.093  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-12 14:43:13.093  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:43:13.093  6669  6725 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-12 14:43:13.094  6669  6669 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-12 14:43:13.094  6669  6725 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@165175c not in the list
09-12 14:43:13.094  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:43:13.094  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 14:43:13.094  6669  6725 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 14:43:13.094  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 14:43:13.095  6669  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-12 14:43:13.095  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-12 14:43:13.095  6669  6733 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-12 14:43:13.096  6669  6725 D BluetoothLeScanner: could not find callback wrapper
09-12 14:43:13.096  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 14:43:13.096  6669  6725 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 14:43:13.096  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:43:13.096  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:43:13.097  6669  6725 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 14:43:13.097  6669  6669 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 14:43:13.097  6669  6669 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 14:43:13.097  6669  6669 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-12 14:43:13.097  6669  6669 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 14:43:13.097  6669  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12512a65 not in the list
09-12 14:43:13.097  6669  6725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 14:43:13.097  6669  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 14:43:13.097  6669  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 14:43:13.105  6669  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 14:43:13.105  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:43:13.105  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:43:13.105  6669  6725 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@165175c not in the list
09-12 14:43:13.105  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:43:13.105  6669  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12512a65 not in the list
09-12 14:43:13.105  6669  6725 D io.jxcore.node.ConnectivityMonitor: stop
09-12 14:43:13.105  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:43:13.105  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:43:13.105  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:43:13.105  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:43:13.106  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 14:43:13.106  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 14:43:13.106  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:43:13.106  6669  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12512a65 not in the list
09-12 14:43:13.107  6669  6725 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-12 14:43:13.107  6669  6725 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-12 14:43:13.107  6669  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-12 14:43:13.107  6669  6725 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-12 14:43:13.108  6669  6725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 14:43:13.108  6669  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 14:43:13.108  6669  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 14:43:13.108  6669  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 14:43:13.108  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:43:13.108  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:43:13.108  6669  6725 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@165175c not in the list
09-12 14:43:13.108  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:43:13.108  6669  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12512a65 not in the list
09-12 14:43:13.108  6669  6725 D io.jxcore.node.ConnectivityMonitor: stop
09-12 14:43:13.108  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:43:13.108  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:43:13.108  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:43:13.108  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:43:13.115  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 14:43:13.115  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 14:43:13.115  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:43:13.115  6669  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12512a65 not in the list
09-12 14:43:13.116  1032  1976 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 14:43:13.117  1032  1904 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 14:43:13.118  1032  1966 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 14:43:13.118  6669  6725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 14:43:13.118  6669  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 14:43:13.118  6669  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 14:43:13.118  6669  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 14:43:13.118  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:43:13.118  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:43:13.119  6669  6725 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@165175c not in the list
09-12 14:43:13.119  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:43:13.119  6669  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12512a65 not in the list
09-12 14:43:13.119  6669  6725 D io.jxcore.node.ConnectivityMonitor: stop
09-12 14:43:13.119  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:43:13.119  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:43:13.119  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:43:13.119  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:43:13.120  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 14:43:13.120  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 14:43:13.120  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:43:13.120  6669  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12512a65 not in the list
09-12 14:43:13.121  6669  6725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 14:43:13.121  6669  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 14:43:13.121  6669  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 14:43:13.121  6669  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 14:43:13.121  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:43:13.121  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:43:13.121  6669  6725 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@165175c not in the list
09-12 14:43:13.121  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:43:13.121  6669  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12512a65 not in the list
09-12 14:43:13.121  6669  6725 D io.jxcore.node.ConnectivityMonitor: stop
09-12 14:43:13.121  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:43:13.121  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:43:13.121  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:43:13.121  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 14:43:13.124  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 14:43:13.124  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 14:43:13.124  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:43:13.124  6669  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12512a65 not in the list
09-12 14:43:13.125  6669  6725 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-12 14:43:13.126  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-12 14:43:13.126  6669  6725 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-12 14:43:13.126  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-12 14:43:13.126  6669  6725 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-12 14:43:13.126  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-12 14:43:13.129  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-12 14:43:13.129  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-12 14:43:13.129  6669  6725 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-12 14:43:13.130  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-12 14:43:13.130  6669  6725 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-12 14:43:13.130  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-12 14:43:13.130  6669  6725 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-12 14:43:13.130  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-12 14:43:13.131  6669  6725 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-12 14:43:13.131  6669  6725 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-12 14:43:13.132  6669  6725 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-12 14:43:13.132  6669  6725 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-12 14:43:13.132  6669  6725 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-12 14:43:13.132  6669  6725 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-12 14:43:13.133  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 14:43:13.133  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3097bf92 added. We now have 2 listener(s)
09-12 14:43:13.133  6669  6725 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 14:43:13.135  6669  6725 D BluetoothAdapter: enable(): BT is already enabled..!
09-12 14:43:13.136  1032  1780 D WifiServiceImplEx: setWifiEnabled: true pid=6669, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-12 14:43:13.136  1032  1780 D WifiService: setWifiEnabled: true pid=6669, uid=10118
09-12 14:43:13.136  1032  1780 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-12 14:43:13.138  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 14:43:13.138  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@29e73d63 added. We now have 3 listener(s)
09-12 14:43:13.138  6669  6725 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 14:43:13.142  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 14:43:13.142  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@29bb7d60 added. We now have 4 listener(s)
09-12 14:43:13.142  6669  6725 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 14:43:13.143  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 14:43:13.143  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3d47d219 added. We now have 5 listener(s)
09-12 14:43:13.144  6669  6725 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 14:43:13.146  1032  1048 D WifiServiceImplEx: setWifiEnabled: false pid=6669, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-12 14:43:13.146  1032  1048 D WifiService: setWifiEnabled: false pid=6669, uid=10118
09-12 14:43:13.146  1032  1048 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-12 14:43:13.164  1032  1650 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 14:43:13.165  1032  1396 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
09-12 14:43:13.165  1032  1650 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@29feacc3 mBinding = false
09-12 14:43:13.165  1032  1396 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
09-12 14:43:13.165  1032  1396 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
09-12 14:43:13.165  1032  1396 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
09-12 14:43:13.165  1032  1032 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-12 14:43:13.165  1032  1396 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
09-12 14:43:13.165  1032  1396 E WifiStateMachine: WifiStateMachine: Leaving Connected state
09-12 14:43:13.165  1032  1396 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-12 14:43:13.165  1032  1396 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-12 14:43:13.166  1032  1032 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-12 14:43:13.166  1032  1032 D Ulp_jni : JNI:system_update. Event-4
09-12 14:43:13.166  1032  1396 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-12 14:43:13.166  1032  1396 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-12 14:43:13.174  6669  6730 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
09-12 14:43:13.175  6669  6730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 826)
,09-12 14:43:13.177  1032  1396 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-12 14:43:13.177  1032  1387 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-12 14:43:13.177  1032  1387 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-12 14:43:13.177  1032  1396 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-12 14:43:13.177  2653  2653 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-12 14:43:13.179  1032  1396 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-12 14:43:13.179  1032  1396 D WifiNative-wlan0: doBoolean: SET ps 1
09-12 14:43:13.179  1032  1094 D BluetoothManagerService: Message: 2
09-12 14:43:13.179  1032  1396 D WifiNative-wlan0: SET ps 1: returned true
09-12 14:43:13.179  1032  2827 D DhcpStateMachine: RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-12 14:43:13.180  1032  1032 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-12 14:43:13.180  1032  1032 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-12 14:43:13.180  1032  1032 D Ulp_jni : JNI:system_update. Event-4
09-12 14:43:13.181  1032  1094 D BluetoothManagerService: Sending off request.
09-12 14:43:13.182  3863  3881 D LGBluetoothServiceAdapter: [BTUI] Precleanup
09-12 14:43:13.182  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 14:43:13.183   306   892 D CommandListener: Clearing all IP addresses on wlan0
09-12 14:43:13.184  3863  3956 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
09-12 14:43:13.184  3863  3956 D BluetoothAdapterProperties: Setting state to 13
09-12 14:43:13.184  3863  3956 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-12 14:43:13.185  3863  3956 D BluetoothAdapterProperties: onBluetoothDisable()
09-12 14:43:13.185  3863  3956 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-12 14:43:13.186  1032  1094 D BluetoothManagerService: Message: 60
09-12 14:43:13.186  1032  1094 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
09-12 14:43:13.186  1032  1094 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
09-12 14:43:13.188  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 14:43:13.188  6669  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 14:43:13.188  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 14:43:13.188  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 14:43:13.188  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 14:43:13.188  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 14:43:13.188  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 14:43:13.188  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 14:43:13.188  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 14:43:13.196  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-12 14:43:13.196  1599  1599 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-12 14:43:13.198  3863  3863 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-12 14:43:13.198  3863  3863 D BluetoothMapService: STATE_TURNING_OFF
09-12 14:43:13.198  3863  3863 V BluetoothMapService: Handler(): got msg=4
09-12 14:43:13.198  3863  3863 D BluetoothMapService: MAP Service closeService in
09-12 14:43:13.198  3863  3863 D BluetoothMapMasInstance: MAP Service shutdown
09-12 14:43:13.199  3863  4269 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
09-12 14:43:13.199  3863  4269 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-12 14:43:13.199  3863  4269 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
09-12 14:43:13.199  3863  4269 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
09-12 14:43:13.199  3863  4269 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
09-12 14:43:13.199  3863  4269 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
09-12 14:43:13.199  3863  4269 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
09-12 14:43:13.199  3863  4269 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
09-12 14:43:13.200  3863  3863 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-12 14:43:13.200  3863  3863 V BluetoothMapService: MAP Service closeService out
09-12 14:43:13.200  3863  3863 V BtOppService: Receiver DISABLED_ACTION 
09-12 14:43:13.200  3863  3863 I BtOppRfcommListener: stopping Accept Thread
09-12 14:43:13.200  3863  3863 V BtOppRfcommListener: close mBtServerSocket
09-12 14:43:13.200  3863  3863 V BtOppRfcommListener: waiting for thread to terminate
09-12 14:43:13.201  3863  4327 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-12 14:43:13.201  3863  4327 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-12 14:43:13.201  3863  3863 V BtOppRfcommListener: done waiting for thread to terminate
,09-12 14:43:13.221  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 14:43:13.221  6669  6725 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 14:43:13.221  6669  6725 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 14:43:13.223  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 14:43:13.224  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 14:43:13.225  6669  6669 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 14:43:13.225  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 14:43:13.225  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 14:43:13.225  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 14:43:13.225  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 14:43:13.225  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 14:43:13.225  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 14:43:13.225  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 14:43:13.225  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 14:43:13.226  6669  6669 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 14:43:13.226  6669  6669 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 14:43:13.227  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 14:43:13.227  1032  1466 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-12 14:43:13.228  1032  1466 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,09-12 14:43:13.243  1032  1090 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6738 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-12 14:43:13.245  1032  1396 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 14:43:13.245  1032  1396 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 14:43:13.245  1032  1396 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 14:43:13.245  1032  1396 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 14:43:13.245  1032  1396 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 14:43:13.246  1032  1396 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 14:43:13.246  1032  1396 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 14:43:13.247  1032  1396 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 14:43:13.247  1032  1396 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 14:43:13.247  1032  1396 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-12 14:43:13.248  3863  3863 V BtOppService: onDestroy
,09-12 14:43:13.248  3863  3863 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
09-12 14:43:13.251  1941  1941 V WfdStateTracker: handleWifiStateChangedEvent: 0
09-12 14:43:13.252  1032  1032 D WifiHS20: hidePasspointNotification off =false
09-12 14:43:13.254  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 14:43:13.254  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 14:43:13.254  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-12 14:43:13.254  1032  1032 D WifiHS20: hidePasspointNotification off =false
09-12 14:43:13.255  1032  1387 D LGWifiP2pService: InactiveState{ when=-11ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-12 14:43:13.255  1032  1387 D LGWifiP2pService: P2pEnabledState{ when=-11ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-12 14:43:13.256  1032  1387 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@29a6779b
,09-12 14:43:13.276  1032  1466 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
09-12 14:43:13.276  1032  1466 D DSQN    : disableDataServiceNotify
09-12 14:43:13.276  1032  1466 D DSQN    : stop dsqn bin
09-12 14:43:13.279  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 14:43:13.279  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 14:43:13.279  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-12 14:43:13.280  1032  1032 D WifiScanningService: SCAN_AVAILABLE : 1
09-12 14:43:13.280  1032  1553 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-12 14:43:13.280  1032  1032 D RttService: SCAN_AVAILABLE : 1
09-12 14:43:13.281  1032  1554 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-12 14:43:13.283  1032  1466 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-12 14:43:13.284  1032  1466 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 14:43:13.284  1032  1466 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-12 14:43:13.284  1032  1387 D LGWifiP2pService: P2pDisablingState
09-12 14:43:13.284  1032  1466 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
09-12 14:43:13.284  1032  1466 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
09-12 14:43:13.284  1032  1387 D LGWifiP2pService: P2pDisablingState{ when=-28ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
09-12 14:43:13.284  1032  1387 D LGWifiP2pService: p2p socket connection lost
09-12 14:43:13.284  1032  1387 D LGWifiP2pService: P2pDisabledState
09-12 14:43:13.284  1032  1466 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
09-12 14:43:13.284  1032  1466 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-12 14:43:13.284  1032  1466 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-12 14:43:13.285  1032  1396 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
09-12 14:43:13.285  1032  1396 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-12 14:43:13.285  1032  2816 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-12 14:43:13.285  1032  1387 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-12 14:43:13.285  1032  2816 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,09-12 14:43:13.285  2653  2653 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-12 14:43:13.285  1032  1387 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-12 14:43:13.285  1032  2816 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-12 14:43:13.286  1599  2069 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-12 14:43:13.287  1032  1396 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-12 14:43:13.287  1032  1396 D WifiNative-wlan0: doBoolean: SET ps 1
09-12 14:43:13.287  1032  1396 D WifiNative-wlan0: SET ps 1: returned true
09-12 14:43:13.288   306   892 D CommandListener: Clearing all IP addresses on wlan0
09-12 14:43:13.288  1032  1466 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-12 14:43:13.288  1032  1466 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-12 14:43:13.288  1032  1466 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-12 14:43:13.289  1032  1466 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 14:43:13.289  1032  1466 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 14:43:13.289  1032  1466 D NetworkManagementService: Removing idletimer
09-12 14:43:13.289  1852  1852 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 14:43:13.289  1032  1466 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 14:43:13.289  1852  1852 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-12 14:43:13.290  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-12 14:43:13.290  1941  1941 D WfdsService: WifiP2pState is changed : false
09-12 14:43:13.290  1032  1386 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-12 14:43:13.290  1032  1386 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-12 14:43:13.291  1941  2410 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
09-12 14:43:13.291  1941  2410 D WfdsService: Set the WFDS Monitor: false
09-12 14:43:13.291  1032  1032 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-12 14:43:13.291  1941  2410 D WfdsMonitor: WFDS Monitor is stopped
09-12 14:43:13.291  1941  2410 D WfdsService: STATE : WfdsDisabledState - enter
09-12 14:43:13.291  1941  2725 D CtrlSupplicant: Received on exit socket, terminate
09-12 14:43:13.291  1941  2725 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
09-12 14:43:13.291  1941  2411 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
09-12 14:43:13.291  1941  2725 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
09-12 14:43:13.292  1941  2725 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
09-12 14:43:13.292  1941  2410 W WfdsService: DefaultState - msg [9445378] is not handled
09-12 14:43:13.293  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 14:43:13.293  1599  1599 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-12 14:43:13.294  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!!, Set no data type icon / Roaming
09-12 14:43:13.294  1032  1396 D WifiNative-p2p0: doBoolean: TERMINATE
09-12 14:43:13.294  1032  1396 D WifiNative-p2p0: TERMINATE: returned true
09-12 14:43:13.294  1032  1396 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-12 14:43:13.294  1032  1396 E WifiStateMachine: useWiFiOffloading() : false
09-12 14:43:13.294  1032  1396 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,09-12 14:43:13.301  1032  1396 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 14:43:13.301  1032  1396 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-12 14:43:13.303  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
09-12 14:43:13.311  6669  6669 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 14:43:13.311  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 14:43:13.311  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 14:43:13.311  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 14:43:13.311  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 14:43:13.311  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 14:43:13.311  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 14:43:13.311  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 14:43:13.311  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 14:43:13.311  1032  1780 I art     : Explicit concurrent mark sweep GC freed 38965(1786KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 3.970ms total 120.132ms
09-12 14:43:13.312  6669  6669 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 14:43:13.312  6669  6669 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 14:43:13.312  6356  6356 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-12 14:43:13.313  1032  1032 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-12 14:43:13.313  1032  1032 D WifiHS20: hidePasspointNotification off =false
09-12 14:43:13.313  1032  1466 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-12 14:43:13.314  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 14:43:13.314  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 14:43:13.314  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-12 14:43:13.314  1032  1032 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
09-12 14:43:13.314  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-12 14:43:13.314  1032  1032 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
09-12 14:43:13.314  1032  1032 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-12 14:43:13.314  1032  1032 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-12 14:43:13.314  1032  1032 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-12 14:43:13.314  1032  1032 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-12 14:43:13.314  1032  1032 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-12 14:43:13.314  1032  1032 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-12 14:43:13.317  6669  6669 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 14:43:13.317  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 14:43:13.317  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 14:43:13.317  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 14:43:13.317  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 14:43:13.317  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 14:43:13.317  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 14:43:13.317  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 14:43:13.317  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 14:43:13.318  6669  6669 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 14:43:13.318  6669  6669 D io,.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 14:43:13.330  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 14:43:13.330  1599  1599 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-12 14:43:13.333  6738  6738 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-12 14:43:13.333  6738  6738 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
09-12 14:43:13.333  6738  6738 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-12 14:43:13.333  6738  6738 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
09-12 14:43:13.335  6738  6738 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-12 14:43:13.335  6738  6738 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-12 14:43:13.336  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 14:43:13.347  1032  1049 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6766 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-12 14:43:13.348  3863  3960 D BluetoothAdapterProperties: Scan Mode:20
09-12 14:43:13.348  3863  3956 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-12 14:43:13.349  3863  3956 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-12 14:43:13.350  3863  4270 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-12 14:43:13.350  3863  4085 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
09-12 14:43:13.350  3863  4085 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
09-12 14:43:13.351  3863  4085 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-12 14:43:13.351  3863  4085 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-12 14:43:13.351  3863  4085 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-12 14:43:13.351  3863  4085 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-12 14:43:13.351  3863  4085 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-12 14:43:13.351  3863  4085 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-12 14:43:13.351  3863  4085 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 14:43:13.351  3863  4085 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-12 14:43:13.351  3863  4085 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-12 14:43:13.351  3863  4085 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
09-12 14:43:13.351  3863  4085 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
09-12 14:43:13.351  3863  4085 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-12 14:43:13.351  3863  4328 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-12 14:43:13.351  3863  4330 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-12 14:43:13.354  6669  6669 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 14:43:13.354  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 14:43:13.354  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 14:43:13.354  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 14:43:13.354  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 14:43:13.354  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 14:43:13.354  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 14:43:13.354  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 14:43:13.354  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 14:43:13.358  6669  6669 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 14:43:13.358  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 14:43:13.358  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 14:43:13.358  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 14:43:13.358  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 14:43:13.358  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 14:43:13.358  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 14:43:13.358  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 14:43:13.358  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 14:43:13.376  1599  1599 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-12 14:43:13.377  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 14:43:13.378  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-12 14:43:13.384  1032  2827 D DhcpStateMachine: StoppedState
09-12 14:43:13.384  1032  2827 D DhcpStateMachine: StoppedState{ when=-96ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-12 14:43:13.389  1032  1396 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
09-12 14:43:13.389  1032  1396 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
,09-12 14:43:13.398  1599  1599 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-12 14:43:13.399  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 14:43:13.399  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 14:43:13.400  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-12 14:43:13.400  1599  1599 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-12 14:43:13.400  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 14:43:13.401  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 14:43:13.408  2653  2653 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-12 14:43:13.408  2653  2653 I wpa_supplicant: monitor socket send errors count : 1
09-12 14:43:13.408  2653  2653 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1941-2\x00 that cannot receive messages
,09-12 14:43:13.409  1032  2698 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
09-12 14:43:13.409  1032  2698 D WifiMonitor: Dropping event because (p2p0) is stopped
09-12 14:43:13.423  6766  6766 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,09-12 14:43:13.429  6766  6766 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-12 14:43:13.429  6766  6766 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-12 14:43:13.430  1032  1976 I ActivityManager: Killing 5909:com.android.providers.calendar/u0a14 (adj 15): empty #17
09-12 14:43:13.444  6738  6738 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,09-12 14:43:13.455  2653  2653 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-12 14:43:13.455  1032  2698 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
,09-12 14:43:13.455  1032  2698 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-12 14:43:13.455  1032  2698 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-12 14:43:13.455  1032  2698 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
09-12 14:43:13.455  2653  2653 W wpa_supplicant: USIM:  scard_deinit function
09-12 14:43:13.456  1032  2698 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-12 14:43:13.456  1032  2698 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-12 14:43:13.456  1032  1094 D Tethering: InitialState.processMessage what=4
09-12 14:43:13.456  1032  1396 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=193056
09-12 14:43:13.456  1032  1396 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=193056
09-12 14:43:13.457  1032  1396 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=193056  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-12 14:43:13.457  1032  1396 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=193057  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-12 14:43:13.459  1032  1997 W libprocessgroup: failed to open /acct/uid_10014/pid_5909/cgroup.procs: No such file or directory
09-12 14:43:13.462  1032  1094 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-12 14:43:13.463  1032  1396 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
09-12 14:43:13.463  1032  1396 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-12 14:43:13.463  3863  3863 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-12 14:43:13.463  3863  3863 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-12 14:43:13.463  3863  3863 V BluetoothPbapReceiver: ***********state = 13
09-12 14:43:13.464  3863  3863 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
09-12 14:43:13.465  3863  3863 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-12 14:43:13.465  3863  3863 V BluetoothPbapService: state: 13
09-12 14:43:13.465  3863  3863 V BluetoothPbapService: Pbap Service closeService in
,09-12 14:43:13.467  2208  2208 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-12 14:43:13.467  3863  3863 V BluetoothPbapService: successfully stopped pbap service
09-12 14:43:13.468  3863  3863 V BluetoothPbapService: Pbap Service closeService out
09-12 14:43:13.468  3863  3863 V BluetoothPbapService: Pbap Service onDestroy
09-12 14:43:13.468  3863  3863 V BluetoothPbapService: Pbap Service closeService in
09-12 14:43:13.468  3863  3863 V BluetoothPbapService: Pbap Service closeService out
09-12 14:43:13.468  3863  3863 D LGBluetoothPbapAdapter: [BTUI] cleanup
09-12 14:43:13.472  6738  6738 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-12 14:43:13.491  6738  6738 D LgDataFeature: LgDataFeature() Constructor: none
09-12 14:43:13.491  6738  6738 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-12 14:43:13.496  1032  1774 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6787 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
09-12 14:43:13.500  6738  6738 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-12 14:43:13.504  1032  1094 D BluetoothManagerService: Message: 20
09-12 14:43:13.504  1032  1094 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@181f6b35:true
,09-12 14:43:13.511  1032  1094 D BluetoothManagerService: Message: 30
09-12 14:43:13.514  1032  1094 D BluetoothManagerService: Message: 30
09-12 14:43:13.515  6738  6738 D LocalBluetoothProfileManager: Adding local MAP profile
09-12 14:43:13.516  6738  6738 D BluetoothMap: Create BluetoothMap proxy object
09-12 14:43:13.516  1032  1094 D BluetoothManagerService: Message: 30
09-12 14:43:13.519  1032  1094 D BluetoothManagerService: Message: 30
,09-12 14:43:13.520  6738  6738 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
09-12 14:43:13.521  6738  6738 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
09-12 14:43:13.529  6738  6738 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
09-12 14:43:13.531  6738  6738 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
,09-12 14:43:13.538  6738  6738 D DockEventReceiver: finishStartingService: stopping service
09-12 14:43:13.555  6738  6738 D BluetoothInputDevice: Proxy object connected
,09-12 14:43:13.555  6738  6738 D HidProfile: Bluetooth service connected
09-12 14:43:13.557  6738  6738 D BluetoothPan: BluetoothPAN Proxy object connected
09-12 14:43:13.558  6738  6738 D PanProfile: Bluetooth service connected
09-12 14:43:13.558  6738  6738 D BluetoothMap: Proxy object connected
09-12 14:43:13.559  6738  6738 D MapProfile: Bluetooth service connected
09-12 14:43:13.559  6738  6738 D BluetoothMap: getConnectedDevices()
09-12 14:43:13.560  6738  6738 D BluetoothMap: Bluetooth is Not enabled
09-12 14:43:13.560  6738  6738 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
09-12 14:43:13.568  2653  2653 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-12 14:43:13.568  1032  2698 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
09-12 14:43:13.568  1032  2698 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
09-12 14:43:13.568  1032  2698 D WifiMonitor: Disconnecting from the supplicant, no more events
,09-12 14:43:13.569  1032  1396 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
09-12 14:43:13.585  1032  1932 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6811 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,09-12 14:43:13.588  1032  1932 I ActivityManager: Killing 6227:com.android.defcontainer/u0a4 (adj 15): empty #17
09-12 14:43:13.597  6669  6669 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-12 14:43:13.629  1032  1966 W libprocessgroup: failed to open /acct/uid_10004/pid_6227/cgroup.procs: No such file or directory
,09-12 14:43:13.634  6787  6787 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
,09-12 14:43:13.635  6787  6787 W LG Account v2.2: No ProfileInfo entries
09-12 14:43:13.635  6787  6787 I LG Account v2.2: isEnabled: false
09-12 14:43:13.635  6787  6787 I Feature : [Lifetracker]ver: 4.21.112(40211120)
09-12 14:43:13.635  6787  6787 I Feature : [Lifetracker]Country: EU
09-12 14:43:13.635  6787  6787 I Feature : [Lifetracker]Operator: OPEN
09-12 14:43:13.635  6787  6787 I Feature : [Lifetracker]Ranking support: false
09-12 14:43:13.635  6787  6787 I Feature : [Lifetracker]Comfort support: false
09-12 14:43:13.635  6787  6787 I Feature : [Lifetracker]Accessory: true
09-12 14:43:13.635  6787  6787 I Feature : [Lifetracker]Health device: true
09-12 14:43:13.635  6787  6787 I Feature : [Lifetracker]Extra Pedometer: false
09-12 14:43:13.636  6787  6787 I Feature : [Lifetracker]Blood glucose device: false
09-12 14:43:13.636  6787  6787 I Feature : [Lifetracker]Device Number: 3
09-12 14:43:13.657  6738  6738 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,09-12 14:43:13.660  6811  6811 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-12 14:43:13.669  6738  6738 D BluetoothPermissionRequest: onReceive
09-12 14:43:13.672  1032  1396 D WifiOffDelayIfNotUsed: stopMonitoring
09-12 14:43:13.672  1032  1396 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-12 14:43:13.672  1032  1396 E WifiStateMachine: useWiFiOffloading() : false
09-12 14:43:13.672  1032  1396 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-12 14:43:13.672  1941  1941 D WfdsService: Supplicant Connection state is changed : false
09-12 14:43:13.674  1941  2410 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
09-12 14:43:13.674  1941  2410 D WfdsService: Set the WFDS Monitor: false
09-12 14:43:13.674  1941  2410 D WfdsMonitor: WFDS Monitor is stopped
,09-12 14:43:13.675  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-12 14:43:13.676  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 14:43:13.679  2504  2504 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 14:43:13.682  6738  6738 D LGBluetoothAuthorization: [BTUI] cancel All Notification
09-12 14:43:13.684  1032  1032 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
09-12 14:43:13.684  1032  1441 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
09-12 14:43:13.684  1032  1441 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
09-12 14:43:13.684  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 14:43:13.688  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 14:43:13.701  6811  6811 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,09-12 14:43:13.703  6738  6738 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-12 14:43:13.706  1032  2012 I ActivityManager: Killing 6391:com.google.android.partnersetup/u0a8 (adj 15): empty #17
09-12 14:43:13.735  3863  3863 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
09-12 14:43:13.736  3863  3863 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,09-12 14:43:13.736  3863  3863 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
,09-12 14:43:13.741  1032  1903 W libprocessgroup: failed to open /acct/uid_10008/pid_6391/cgroup.procs: No such file or directory
09-12 14:43:13.744  3863  3863 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-12 14:43:13.744  3863  3863 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-12 14:43:13.745  3863  3863 V BluetoothFtpService: Ftp Service onStartCommand
09-12 14:43:13.745  3863  3863 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-12 14:43:13.746  3863  3863 V BluetoothFtpService: Ftp Service closeService
09-12 14:43:13.746  3863  3863 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
09-12 14:43:13.749  3863  3863 V BluetoothFtpService: successfully stopped ftp service
09-12 14:43:13.750  3863  3863 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-12 14:43:13.750  3863  3863 V BluetoothSapReceiver: [BTUI] region:EU country:EU
,09-12 14:43:13.750  3863  3863 V BluetoothSapReceiver: SapReceiver onReceive 
09-12 14:43:13.750  3863  3863 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-12 14:43:13.750  3863  3863 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
09-12 14:43:13.750  3863  3863 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-12 14:43:13.751  3863  3863 V BluetoothFtpService: Ftp Service onDestroy
09-12 14:43:13.751  3863  3863 V BluetoothFtpService: Ftp Service closeService
09-12 14:43:13.766  6811  6811 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
09-12 14:43:13.766  6811  6811 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
09-12 14:43:13.767  6811  6811 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
09-12 14:43:13.767  6811  6811 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
09-12 14:43:13.767  6811  6811 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
,09-12 14:43:13.769  6811  6811 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,09-12 14:43:13.774  6811  6811 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
09-12 14:43:13.792  1032  1997 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6830 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-12 14:43:13.793  3863  3863 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-12 14:43:13.793  3863  3863 V BluetoothSapService: state: 13
09-12 14:43:13.793  3863  3863 V BluetoothSapService: Stopping SAP server process
09-12 14:43:13.795  3863  3863 V BluetoothSapService: Sap Service closeSapService in
09-12 14:43:13.795  3863  3863 V BluetoothSapService: Close listen Socket : 
09-12 14:43:13.795  3863  3863 V BluetoothSapService: Close rfcomm Socket : 
09-12 14:43:13.795  3863  3863 V BluetoothSapService: Close sapd  Socket : 
09-12 14:43:13.796  3863  3863 V BluetoothSapService: Sap Service closeSapService out
09-12 14:43:13.796  3863  3863 V BluetoothSapService: Sap Service onDestroy
09-12 14:43:13.796  3863  3863 V BluetoothSapService: Sap Service closeSapService in
09-12 14:43:13.796  3863  3863 V BluetoothSapService: Close listen Socket : 
09-12 14:43:13.796  3863  3863 V BluetoothSapService: Close rfcomm Socket : 
09-12 14:43:13.796  3863  3863 V BluetoothSapService: Close sapd  Socket : 
09-12 14:43:13.797  3863  3863 V BluetoothSapService: Sap Service closeSapService out
09-12 14:43:13.800  6811  6811 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-12 14:43:13.802  6811  6811 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-12 14:43:13.818  6811  6811 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-12 14:43:13.819  6811  6811 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
09-12 14:43:13.820  6356  6356 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-12 14:43:13.823  6766  6766 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-12 14:43:13.823  6766  6766 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-12 14:43:13.823  6766  6766 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-12 14:43:13.826  6738  6738 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-12 14:43:13.826  6811  6811 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
09-12 14:43:13.830  6738  6738 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-12 14:43:13.836  6811  6811 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-12 14:43:13.836  6811  6811 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-12 14:43:13.838  6811  6811 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-12 14:43:13.840  6356  6356 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-12 14:43:13.845  6766  6766 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-12 14:43:13.845  6766  6766 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-12 14:43:13.845  6766  6766 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-12 14:43:13.848  6738  6738 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-12 14:43:13.854  6738  6738 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-12 14:43:13.860  6811  6811 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-12 14:43:13.860  6811  6811 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-12 14:43:13.861  6811  6811 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-12 14:43:13.861  6830  6830 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-12 14:43:13.922  1032  1780 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6850 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
09-12 14:43:13.924  1032  1780 I ActivityManager: Killing 6020:com.lge.appbox.client/u0a11 (adj 15): empty #17
,09-12 14:43:13.954   335   335 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 466us total 28.856ms
,09-12 14:43:13.976   335   335 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 413us total 20.616ms
,09-12 14:43:13.995   335   335 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 370us total 18.470ms
,09-12 14:43:14.006  1032  1650 W libprocessgroup: failed to open /acct/uid_10011/pid_6020/cgroup.procs: No such file or directory
,09-12 14:43:14.051  6766  6766 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-12 14:43:14.055  6738  6738 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-12 14:43:14.064  6738  6738 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-12 14:43:14.099  6850  6869 W FormManager: Network not available. Please check & try again.
,09-12 14:43:14.099  6738  6738 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-12 14:43:14.099  6738  6738 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-12 14:43:14.100  6738  6738 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-12 14:43:14.100  6738  6738 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-12 14:43:14.101  6738  6738 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,09-12 14:43:14.113  6738  6738 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-12 14:43:14.113  6738  6738 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-12 14:43:14.113  6738  6738 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-12 14:43:14.113  6738  6738 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-12 14:43:14.113  6738  6738 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-12 14:43:14.114  6738  6738 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,09-12 14:43:14.122  4334  4334 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-12 14:43:14.122  4334  4334 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-12 14:43:14.123  6850  6870 V FormManager: Network unavailable.
09-12 14:43:14.124  4334  4334 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-12 14:43:14.128  4334  4334 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-12 14:43:14.131  6850  6870 V FormManager: Network unavailable.
,09-12 14:43:14.136  6766  6766 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
09-12 14:43:14.136  6766  6766 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-12 14:43:14.136  6766  6766 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-12 14:43:14.138  6738  6738 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-12 14:43:14.139  4334  6873 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-12 14:43:14.144  6738  6738 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-12 14:43:14.145  4334  6874 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-12 14:43:14.145  4334  6874 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-12 14:43:14.166  6850  6875 W FormManager: Network not available. Please check & try again.
09-12 14:43:14.167  6811  6811 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,09-12 14:43:14.168  6811  6811 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
09-12 14:43:14.169  6811  6811 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
09-12 14:43:14.172  6850  6876 V FormManager: Network unavailable.
09-12 14:43:14.175  6850  6876 V FormManager: Network unavailable.
09-12 14:43:14.182  1032  1976 I ActivityManager: Killing 6041:com.android.contacts/u0a19 (adj 15): empty #17
,09-12 14:43:14.214  6811  6811 D LgDataFeature: LgDataFeature() Constructor: none
,09-12 14:43:14.214  6811  6811 D LgDataFeature: LgDataFeature() Constructor Done, null
09-12 14:43:14.223  6811  6811 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
09-12 14:43:14.227  6811  6811 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
09-12 14:43:14.227  6811  6811 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
09-12 14:43:14.227  6811  6811 V SoundPool: doLoad: loading sample sampleID=1
09-12 14:43:14.227  6811  6879 V SoundPool: Start decode
09-12 14:43:14.227  6811  6879 V MediaPlayer[Native]: decode(31, 10857164, 17813)
,09-12 14:43:14.229   311  2165 V MediaPlayerService: decode(22, 10857164, 17813)
,09-12 14:43:14.229   311  2165 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
09-12 14:43:14.229   311  2165 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
09-12 14:43:14.229   311  2165 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
09-12 14:43:14.230   311  2165 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
09-12 14:43:14.230   311  2165 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
09-12 14:43:14.230   311  2165 V MediaPlayerService: player type = 3
09-12 14:43:14.230   311  2165 V AwesomePlayer: AwesomePlayer create()
09-12 14:43:14.230  6811  6811 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
09-12 14:43:14.232   311  2165 V AwesomePlayer: reset_l() 
09-12 14:43:14.232   311  2165 V AwesomePlayer: cancelPlayerEvents
09-12 14:43:14.232   311  2165 V AwesomePlayer: setAudioSink() 
09-12 14:43:14.232   311  2165 V AwesomePlayer: reset_l() 
09-12 14:43:14.232   311  2165 V AudioCache: notify(0xb1018100, 8, 0, 0)
09-12 14:43:14.232   311  2165 V AudioCache: ignored
09-12 14:43:14.232   311  2165 V AwesomePlayer: cancelPlayerEvents
09-12 14:43:14.232   311  2165 D Utils   : printFileName fd(23) -> /data/preload/LGQRemote/LGQRemote.apk
09-12 14:43:14.232   311  2165 V AwesomePlayer: setDataSource_l dataSource
09-12 14:43:14.232   311  2165 V LGParserOSAL: SniffLGParser start
09-12 14:43:14.232   311  2165 V LGParserOSAL: MainType:5, SubType=0
09-12 14:43:14.232   311  2165 V LGParserOSAL: #### check Mime : application/ogg
09-12 14:43:14.232   311  2165 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
09-12 14:43:14.232   311  2165 E MediaExtractor: Use LGExtractor :application/ogg 
09-12 14:43:14.240  1032  1903 W libprocessgroup: failed to open /acct/uid_10019/pid_6041/cgroup.procs: No such file or directory
,09-12 14:43:14.247  6811  6811 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,09-12 14:43:14.249  6811  6811 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-12 14:43:14.249  6550  6550 D UEI.SmartControl: QS Service created
,09-12 14:43:14.249  6811  6811 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
09-12 14:43:14.264  6811  6811 V LGMDMManager: Create singleton instance
,09-12 14:43:14.279  6550  6550 I UEI.SmartControl: Service initServices...
,09-12 14:43:14.279  6550  6550 D UEI.SmartControl: QS start get config
09-12 14:43:14.298   311  2165 V LGParserOSAL: supported mime: application/ogg
09-12 14:43:14.298   311  2165 V AwesomePlayer: setDataSource_l() extractor countTracks=1
09-12 14:43:14.298   311  2165 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
09-12 14:43:14.299   311  2165 V AwesomePlayer: mBitrate = -1 bits/sec
09-12 14:43:14.299   311  2165 V AwesomePlayer: AudioTrack Setting
,09-12 14:43:14.299   311  2165 V AwesomePlayer: AudioTrack Setting channelCount = 2
09-12 14:43:14.299   311  2165 V AwesomePlayer: setAudioSource() 
09-12 14:43:14.299   311  2165 V MediaPlayerService: prepare
09-12 14:43:14.299   311  2165 V AwesomePlayer: prepareAsync_l() 
09-12 14:43:14.299   311  2165 V MediaPlayerService: wait for prepare
09-12 14:43:14.299   311  6880 V AwesomePlayer: onPrepareAsyncEvent() 
09-12 14:43:14.299   311  6880 V AwesomePlayer: initAudioDecoder() 
09-12 14:43:14.299   311  6880 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-12 14:43:14.299   311  6880 V AudioSystem: isOffloadSupported()
09-12 14:43:14.299   311  6880 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-12 14:43:14.299   311  6880 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-12 14:43:14.299   311  6880 I AudioFlinger: isAudioPlaybackHookOn() false
09-12 14:43:14.299   311  6880 V AwesomePlayer: getUseOffload() = 0 
09-12 14:43:14.299   311  6880 V OMXCodec: OMXCodec::Create
,09-12 14:43:14.299   311  6880 V OMXCodec: findMatchingCodecs()
09-12 14:43:14.299   311  6880 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
09-12 14:43:14.300   311  6880 V OMXCodec: matchingCodecs.size()=1
,09-12 14:43:14.300   311  6880 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
09-12 14:43:14.302   311  6880 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
09-12 14:43:14.302   311  6880 V LGCodecAdapter: LG Codec Adapter start
,09-12 14:43:14.302   311  6880 V OMXCodec: OMXCodec Createtor
09-12 14:43:14.302   311  6880 V OMXCodec: setComponentRole
09-12 14:43:14.302   311  6880 V OMXCodec: configureCodec protected=0
,09-12 14:43:14.302   311  6880 V LGCodecAdapter: called getLGCodecSpecificData
09-12 14:43:14.302   311  6880 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
09-12 14:43:14.302   311  6880 V LGCodecOSAL: Called LGconfigureCodecMETA
,09-12 14:43:14.302   311  6880 V LGCodecOSAL: Called LGconfigureCodecMSG
09-12 14:43:14.302   311  6880 V LGCodecOSAL: Not support LGCodec
09-12 14:43:14.302   311  6880 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
,09-12 14:43:14.302   311  6880 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
09-12 14:43:14.302   311  6880 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
09-12 14:43:14.302   311  6880 I AwesomePlayer: Could not offload audio decode, try pcm offload,
09-12 14:43:14.302   311  6880 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-12 14:43:14.302   311  6880 V AudioSystem: isOffloadSupported()
09-12 14:43:14.302   311  6880 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0,
09-12 14:43:14.302   311  6880 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-12 14:43:14.302   311  6880 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
09-12 14:43:14.302   311  6880 V OMXCodec: init()
,09-12 14:43:14.302   311  6880 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
09-12 14:43:14.302   311  6880 V OMXCodec: allocateBuffers
09-12 14:43:14.302   311  6880 V OMXCodec: allocateBuffersOnPort portIndex=0,
09-12 14:43:14.302   311  6880 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
09-12 14:43:14.302   311  6880 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7650 on input port
09-12 14:43:14.303   311  6880 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7740 on input port
,09-12 14:43:14.303   311  6880 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7790 on input port
09-12 14:43:14.303   311  6880 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f78d0 on input port
,09-12 14:43:14.303   311  6880 V OMXCodec: allocateBuffersOnPort portIndex=1
09-12 14:43:14.303   311  6880 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port,
,09-12 14:43:14.303   311  6880 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7970 on output port
09-12 14:43:14.303   311  6880 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on output port
09-12 14:43:14.303   311  6880 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on output port
09-12 14:43:14.303   311  6880 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ec0 on output port,
09-12 14:43:14.303   311  6880 V OMXCodec: init() mAsyncCompletion wait!!! 
09-12 14:43:14.303   311  6882 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-12 14:43:14.303   311  6882 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-12 14:43:14.303   311  6882 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
09-12 14:43:14.303   311  6880 V OMXCodec: init() mAsyncCompletion wait!!! ,
,09-12 14:43:14.303   311  6882 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
09-12 14:43:14.303   311  6882 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
09-12 14:43:14.303   311  6882 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
09-12 14:43:14.303   311  6880 V OMXCodec: init() mAsyncCompletion wait free! 
09-12 14:43:14.303   311  6880 V AwesomePlayer: finishAsyncPrepare_l() 
09-12 14:43:14.303   311  6880 V AudioCache: notify(0xb1018100, 5, 0, 0)
09-12 14:43:14.303   311  6880 V AudioCache: ignored
09-12 14:43:14.303   311  6880 V AudioCache: notify(0xb1018100, 1, 0, 0)
,09-12 14:43:14.303   311  6880 V AudioCache: prepared
09-12 14:43:14.303   311  2165 V AudioCache: wait - success
09-12 14:43:14.303   311  2165 V MediaPlayerService: start
09-12 14:43:14.303   311  2165 V AwesomePlayer: play_l() 
09-12 14:43:14.303   311  2165 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
09-12 14:43:14.303   311  2165 V AwesomePlayer: createAudioPlayer_l
09-12 14:43:14.303   311  2165 V AwesomePlayer: seekAudioIfNecessary_l() 
09-12 14:43:14.303   311  2165 V AwesomePlayer: startAudioPlayer_l() 
,09-12 14:43:14.303   311  2165 D AudioPlayer: start of Playback, useOffload 0
09-12 14:43:14.303   311  2165 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-12 14:43:14.304   311  2165 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-12 14:43:14.306   311  6882 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
09-12 14:43:14.306   311  6882 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
09-12 14:43:14.306   311  6882 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
,09-12 14:43:14.306   311  6882 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
09-12 14:43:14.306   311  6882 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
09-12 14:43:14.306   311  6882 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-12 14:43:14.306   311  6882 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884528
09-12 14:43:14.306   311  6882 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-12 14:43:14.306   311  6882 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884768
09-12 14:43:14.306   311  6882 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-12 14:43:14.306   311  6882 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884848
,09-12 14:43:14.306   311  6882 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-12 14:43:14.306   311  6882 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885888
09-12 14:43:14.306   311  6882 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-12 14:43:14.306   311  6882 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
09-12 14:43:14.306   311  6882 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-12 14:43:14.306   311  6882 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
09-12 14:43:14.306   311  6882 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
09-12 14:43:14.306   311  6882 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
,09-12 14:43:14.306   311  6882 V OMXCodec: allocateBuffersOnPort portIndex=1
09-12 14:43:14.306   311  6882 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-12 14:43:14.306   311  6882 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on output port
09-12 14:43:14.306   311  6882 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on output port
09-12 14:43:14.306   311  6882 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7970 on output port
09-12 14:43:14.306   311  6882 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57fd560 on output port
09-12 14:43:14.306   311  6882 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
09-12 14:43:14.306   311  6882 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
,09-12 14:43:14.307   311  2165 V AudioCache: open(48000, 2, 0x0, 1, 4)
09-12 14:43:14.307   311  2165 V AudioCache: notify(0xb1018100, 6, 0, 0)
09-12 14:43:14.307   311  2165 V AudioCache: ignored
09-12 14:43:14.307   311  2165 V MediaPlayerService: wait for playback complete
09-12 14:43:14.308   311  6883 V AudioCache: write(0xb178a000, 4096)
09-12 14:43:14.308   311  6883 V AudioCache: memcpy(0xaf104000, 0xb178a000, 4096)
09-12 14:43:14.309   311  6883 V AudioCache: write(0xb178a000, 4096)
09-12 14:43:14.309   311  6883 V AudioCache: memcpy(0xaf105000, 0xb178a000, 4096)
,09-12 14:43:14.309   311  6883 V AudioCache: write(0xb178a000, 4096)
09-12 14:43:14.309   311  6883 V AudioCache: memcpy(0xaf106000, 0xb178a000, 4096)
09-12 14:43:14.309   311  6883 V AudioCache: write(0xb178a000, 4096)
09-12 14:43:14.309   311  6883 V AudioCache: memcpy(0xaf107000, 0xb178a000, 4096)
09-12 14:43:14.309   311  6883 V AudioCache: write(0xb178a000, 4096)
09-12 14:43:14.310   311  6883 V AudioCache: memcpy(0xaf108000, 0xb178a000, 4096)
09-12 14:43:14.310   311  6883 V AudioCache: write(0xb178a000, 4096)
09-12 14:43:14.310   311  6883 V AudioCache: memcpy(0xaf109000, 0xb178a000, 4096)
,09-12 14:43:14.310   311  6883 V AudioCache: write(0xb178a000, 4096)
09-12 14:43:14.310   311  6883 V AudioCache: memcpy(0xaf10a000, 0xb178a000, 4096)
09-12 14:43:14.310   311  6883 V AudioCache: write(0xb178a000, 4096)
09-12 14:43:14.310   311  6883 V AudioCache: memcpy(0xaf10b000, 0xb178a000, 4096)
09-12 14:43:14.311   311  6883 V AudioCache: write(0xb178a000, 4096)
09-12 14:43:14.311   311  6883 V AudioCache: memcpy(0xaf10c000, 0xb178a000, 4096)
09-12 14:43:14.311   311  6883 V AudioCache: write(0xb178a000, 4096)
09-12 14:43:14.311   311  6883 V AudioCache: memcpy(0xaf10d000, 0xb178a000, 4096)
,09-12 14:43:14.311   311  6883 V AudioCache: write(0xb178a000, 4096)
09-12 14:43:14.311   311  6883 V AudioCache: memcpy(0xaf10e000, 0xb178a000, 4096)
09-12 14:43:14.312   311  6883 V AudioCache: write(0xb178a000, 4096)
09-12 14:43:14.312   311  6883 V AudioCache: memcpy(0xaf10f000, 0xb178a000, 4096)
09-12 14:43:14.312   311  6883 V AudioCache: write(0xb178a000, 4096)
09-12 14:43:14.312   311  6883 V AudioCache: memcpy(0xaf110000, 0xb178a000, 4096)
09-12 14:43:14.312   311  6883 V AudioCache: write(0xb178a000, 4096)
09-12 14:43:14.312   311  6883 V AudioCache: memcpy(0xaf111000, 0xb178a000, 4096)
09-12 14:43:14.313   311  6883 V AudioCache: write(0xb178a000, 4096)
09-12 14:43:14.313   311  6883 V AudioCache: memcpy(0xaf112000, 0xb178a000, 4096)
09-12 14:43:14.313   311  6883 V AudioCache: write(0xb178a000, 4096)
09-12 14:43:14.313   311  6883 V AudioCache: memcpy(0xaf113000, 0xb178a000, 4096)
09-12 14:43:14.313   311  6883 V AudioCache: write(0xb178a000, 4096)
09-12 14:43:14.313   311  6883 V AudioCache: memcpy(0xaf114000, 0xb178a000, 4096)
09-12 14:43:14.313   311  6883 V AudioCache: write(0xb178a000, 4096)
09-12 14:43:14.314   311  6883 V AudioCache: memcpy(0xaf115000, 0xb178a000, 4096)
09-12 14:43:14.314   311  6883 V AudioCache: write(0xb178a000, 4096)
09-12 14:43:14.314   311  6883 V AudioCache: memcpy(0xaf116000, 0xb178a000, 4096)
09-12 14:43:14.314   311  6883 V AudioCache: write(0xb178a000, 4096)
09-12 14:43:14.314   311  6883 V AudioCache: memcpy(0xaf117000, 0xb178a000, 4096)
09-12 14:43:14.314   311  6883 V AudioCache: write(0xb178a000, 4096)
09-12 14:43:14.314   311  6883 V AudioCache: memcpy(0xaf118000, 0xb178a000, 4096)
09-12 14:43:14.315   311  6883 V AudioCache: write(0xb178a000, 4096)
09-12 14:43:14.315   311  6883 V AudioCache: memcpy(0xaf119000, 0xb178a000, 4096)
09-12 14:43:14.315   311  6883 V AudioCache: write(0xb178a000, 4096)
09-12 14:43:14.315   311  6883 V AudioCache: memcpy(0xaf11a000, 0xb178a000, 4096)
09-12 14:43:14.315   311  6883 V AudioCache: write(0xb178a000, 4096)
09-12 14:43:14.315   311  6883 V AudioCache: memcpy(0xaf11b000, 0xb178a000, 4096)
09-12 14:43:14.316   311  6883 V AudioCache: write(0xb178a000, 4096)
09-12 14:43:14.316   311  6883 V AudioCache: memcpy(0xaf11c000, 0xb178a000, 4096)
09-12 14:43:14.316   311  6883 V AudioCache: write(0xb178a000, 4096)
09-12 14:43:14.316   311  6883 V AudioCache: memcpy(0xaf11d000, 0xb178a000, 4096)
09-12 14:43:14.316   311  6883 V AudioCache: write(0xb178a000, 4096)
09-12 14:43:14.316   311  6883 V AudioCache: memcpy(0xaf11e000, 0xb178a000, 4096)
09-12 14:43:14.317   311  6883 V AudioCache: write(0xb178a000, 4096)
09-12 14:43:14.317   311  6883 V AudioCache: memcpy(0xaf11f000, 0xb178a000, 4096)
09-12 14:43:14.317   311  6883 V AudioCache: write(0xb178a000, 4096)
09-12 14:43:14.317   311  6883 V AudioCache: memcpy(0xaf120000, 0xb178a000, 4096)
09-12 14:43:14.318   311  6883 V AudioCache: write(0xb178a000, 4096)
09-12 14:43:14.318   311  6883 V AudioCache: memcpy(0xaf121000, 0xb178a000, 4096)
09-12 14:43:14.318   311  6883 V AudioCache: write(0xb178a000, 4096)
09-12 14:43:14.318   311  6883 V AudioCache: memcpy(0xaf122000, 0xb178a000, 4096)
09-12 14:43:14.319   311  6883 V AudioCache: write(0xb178a000, 4096)
09-12 14:43:14.319   311  6883 V AudioCache: memcpy(0xaf123000, 0xb178a000, 4096)
09-12 14:43:14.319   311  6883 V AudioCache: write(0xb178a000, 4096)
09-12 14:43:14.320   311  6883 V AudioCache: memcpy(0xaf124000, 0xb178a000, 4096)
09-12 14:43:14.320   311  6883 V AudioCache: write(0xb178a000, 4096)
09-12 14:43:14.320   311  6883 V AudioCache: memcpy(0xaf125000, 0xb178a000, 4096)
09-12 14:43:14.321   311  6883 V AudioCache: write(0xb178a000, 4096)
09-12 14:43:14.321   311  6883 V AudioCache: memcpy(0xaf126000, 0xb178a000, 4096)
09-12 14:43:14.321   311  6883 V AudioCache: write(0xb178a000, 4096)
09-12 14:43:14.321   311  6883 V AudioCache: memcpy(0xaf127000, 0xb178a000, 4096)
09-12 14:43:14.322   311  6883 V AudioCache: write(0xb178a000, 4096)
09-12 14:43:14.322   311  6883 V AudioCache: memcpy(0xaf128000, 0xb178a000, 4096)
09-12 14:43:14.322   311  6883 V AudioCache: write(0xb178a000, 4096)
09-12 14:43:14.322   311  6883 V AudioCache: memcpy(0xaf129000, 0xb178a000, 4096)
09-12 14:43:14.323   311  6883 V AudioCache: write(0xb178a000, 4096)
09-12 14:43:14.323   311  6883 V AudioCache: memcpy(0xaf12a000, 0xb178a000, 4096)
09-12 14:43:14.324   311  6883 V AudioCache: write(0xb178a000, 4096)
09-12 14:43:14.324   311  6883 V AudioCache: memcpy(0xaf12b000, 0xb178a000, 4096)
09-12 14:43:14.324   311  6883 V AudioCache: write(0xb178a000, 4096)
09-12 14:43:14.324   311  6883 V AudioCache: memcpy(0xaf12c000, 0xb178a000, 4096)
09-12 14:43:14.325   311  6883 V AudioCache: write(0xb178a000, 4096)
09-12 14:43:14.325   311  6883 V AudioCache: memcpy(0xaf12d000, 0xb178a000, 4096)
09-12 14:43:14.325   311  6883 V AudioCache: write(0xb178a000, 4096)
09-12 14:43:14.325   311  6883 V AudioCache: memcpy(0xaf12e000, 0xb178a000, 4096)
09-12 14:43:14.326   311  6883 V AudioCache: write(0xb178a000, 4096)
09-12 14:43:14.326   311  6883 V AudioCache: memcpy(0xaf12f000, 0xb178a000, 4096)
09-12 14:43:14.326   311  6883 V AudioCache: write(0xb178a000, 4096)
09-12 14:43:14.326   311  6883 V AudioCache: memcpy(0xaf130000, 0xb178a000, 4096)
09-12 14:43:14.327   311  6883 V AudioCache: write(0xb178a000, 4096)
09-12 14:43:14.327   311  6883 V AudioCache: memcpy(0xaf131000, 0xb178a000, 4096)
09-12 14:43:14.327   311  6883 V AudioCache: write(0xb178a000, 4096)
09-12 14:43:14.327   311  6883 V AudioCache: memcpy(0xaf132000, 0xb178a000, 4096)
09-12 14:43:14.328   311  6883 V AudioCache: write(0xb178a000, 4096)
09-12 14:43:14.328   311  6883 V AudioCache: memcpy(0xaf133000, 0xb178a000, 4096)
09-12 14:43:14.328   311  6883 V AudioCache: write(0xb178a000, 4096)
09-12 14:43:14.328   311  6883 V AudioCache: memcpy(0xaf134000, 0xb178a000, 4096)
09-12 14:43:14.329   311  6883 V AudioCache: write(0xb178a000, 4096)
09-12 14:43:14.329   311  6883 V AudioCache: memcpy(0xaf135000, 0xb178a000, 4096)
09-12 14:43:14.329   311  6882 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
09-12 14:43:14.329   311  6883 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
09-12 14:43:14.329   311  6883 V AwesomePlayer: postAudioEOS() 
09-12 14:43:14.329   311  6883 V AudioCache: write(0xb178a000, 280)
09-12 14:43:14.329   311  6883 V AudioCache: memcpy(0xaf136000, 0xb178a000, 280)
09-12 14:43:14.333  6811  6811 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
09-12 14:43:14.334  6811  6811 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
09-12 14:43:14.335  6811  6811 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:817
09-12 14:43:14.336   311  6880 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
09-12 14:43:14.336   311  6880 V AwesomePlayer: onStreamDone
09-12 14:43:14.336   311  6880 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
09-12 14:43:14.336   311  6880 V AudioCache: notify(0xb1018100, 2, 0, 0)
09-12 14:43:14.336   311  6880 V AudioCache: playback complete
09-12 14:43:14.336   311  6880 V AwesomePlayer: pause_l() 
09-12 14:43:14.336   311  6880 V AudioCache: notify(0xb1018100, 7, 0, 0)
09-12 14:43:14.336   311  6880 V AudioCache: ignored
09-12 14:43:14.336   311  6880 V AwesomePlayer: cancelPlayerEvents
09-12 14:43:14.336   311  6880 D AudioPlayer: Pause Playback at 1068125
09-12 14:43:14.338   311  2165 V AudioCache: wait - success
09-12 14:43:14.338   311  2165 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
09-12 14:43:14.338   311  2165 V AwesomePlayer: reset_l() 
09-12 14:43:14.338   311  2165 V AudioCache: notify(0xb1018100, 8, 0, 0)
09-12 14:43:14.338   311  2165 V AudioCache: ignored
09-12 14:43:14.338   311  2165 V AwesomePlayer: cancelPlayerEvents
09-12 14:43:14.338   311  2165 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
09-12 14:43:14.338   311  2165 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
09-12 14:43:14.338   311  2165 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
09-12 14:43:14.338   311  2165 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
09-12 14:43:14.338   311  2165 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-12 14:43:14.338   311  6882 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-12 14:43:14.338   311  6882 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-12 14:43:14.338   311  6882 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
09-12 14:43:14.338   311  6882 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f78d0 on port 0
09-12 14:43:14.338   311  6882 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
09-12 14:43:14.338   311  6882 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7790 on port 0
09-12 14:43:14.338   311  6882 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
09-12 14:43:14.338   311  6882 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7740 on port 0
09-12 14:43:14.338   311  6882 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
09-12 14:43:14.338   311  6882 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7650 on port 0
09-12 14:43:14.338   311  6882 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
09-12 14:43:14.338   311  6882 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-12 14:43:14.338   311  6882 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57fd560 on port 1
09-12 14:43:14.338   311  6882 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
09-12 14:43:14.338   311  6882 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7970 on port 1
09-12 14:43:14.338   311  6882 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
09-12 14:43:14.338   311  6882 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 1
09-12 14:43:14.338   311  6882 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
09-12 14:43:14.338   311  6882 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 1
09-12 14:43:14.338   311  6882 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-12 14:43:14.338   311  6882 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
09-12 14:43:14.339   311  2165 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-12 14:43:14.339   311  2165 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-12 14:43:14.339   311  6882 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
09-12 14:43:14.339   311  6882 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
09-12 14:43:14.339   311  6882 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
09-12 14:43:14.339   311  2165 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-12 14:43:14.339   311  2165 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
09-12 14:43:14.339   311  2165 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
09-12 14:43:14.339   311  2165 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
09-12 14:43:14.340   311  2165 D AudioPlayer: AudioPlayer releasing audio source
09-12 14:43:14.340   311  2165 D AudioPlayer: AudioPlayer done releasing audio source
09-12 14:43:14.340   311  2165 V AwesomePlayer: reset_l() 
09-12 14:43:14.340   311  2165 V AwesomePlayer: cancelPlayerEvents
09-12 14:43:14.340   311  2165 V AwesomePlayer: ~AwesomePlayer call
09-12 14:43:14.340   311  2165 V AwesomePlayer: reset_l() 
09-12 14:43:14.340   311  2165 V AwesomePlayer: cancelPlayerEvents
09-12 14:43:14.340  6811  6879 V SoundPool: close(31)
09-12 14:43:14.340  6811  6879 V SoundPool: pointer = 0xa0000000, size = 205080, sampleRate = 48000, numChannels = 2
,09-12 14:43:14.353  3863  3960 D bt_hci_bdroid: cleanup
09-12 14:43:14.353  3863  4252 I bt_userial_mct: exiting userial_read_thread
09-12 14:43:14.353  3863  4252 D bt_userial_mct: Leaving userial_evt_read_thread()
09-12 14:43:14.353  3863  4088 I bt_lpm  : LPM is already off!!!
09-12 14:43:14.353  3863  4085 W bt-btif : ag scb idx 1 not allocated
09-12 14:43:14.353  3863  4085 E bt-btif : BTA AG is already disabled, ignoring ...
09-12 14:43:14.353  3863  4085 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-12 14:43:14.353  3863  4085 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-12 14:43:14.353  3863  3960 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-12 14:43:14.353  3863  4085 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-12 14:43:14.353  3863  4085 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 14:43:14.353  3863  4085 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-12 14:43:14.353  3863  4085 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,09-12 14:43:14.353  3863  4088 I bt_vendor: hw_epilog_process
09-12 14:43:14.353  3863  4085 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-12 14:43:14.353  3863  4085 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-12 14:43:14.353  3863  4085 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-12 14:43:14.353  3863  4085 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-12 14:43:14.353  3863  4085 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-12 14:43:14.353  3863  4085 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-12 14:43:14.353  3863  4085 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
,09-12 14:43:14.353  3863  4085 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-12 14:43:14.353  3863  4085 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-12 14:43:14.353  3863  4085 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-12 14:43:14.353  3863  4085 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-12 14:43:14.353  3863  4085 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-12 14:43:14.353  3863  4085 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-12 14:43:14.354  3863  3960 D bt_hci_bdroid: cleanup Finalizing cleanup
,09-12 14:43:14.354  3863  3960 D bt_userial_mct: userial_close
09-12 14:43:14.354  3863  3960 E bt_userial_mct: pthread_join() FAILED result:3
09-12 14:43:14.354  3863  3960 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,09-12 14:43:14.487  3863  3960 D bt_hci_bdroid: set_power 0
09-12 14:43:14.487  3863  3960 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-12 14:43:14.487  3863  3960 I bt_vendor: bluetooth satus is on
,09-12 14:43:14.487  3863  3960 I bt_vendor: bt-vendor : resetting BT status
09-12 14:43:14.488  3863  3960 I bt_vendor: Starting hciattach daemon
09-12 14:43:14.488  3863  3960 I bt_vendor: try to set false
09-12 14:43:14.489  3863  3960 I bt_vendor: Starting hciattach daemon
09-12 14:43:14.489  3863  3960 I bt_vendor: try to set false
,09-12 14:43:14.489  3863  3960 I bt_vendor: cleanup
09-12 14:43:14.490  3863  4085 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
,09-12 14:43:14.491  3863  3960 I GKI_LINUX: GKI_exit_task 0 done
09-12 14:43:14.491  3863  3960 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
09-12 14:43:14.492  3863  3956 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,09-12 14:43:14.495  3863  3863 D HeadsetService: Received stop request...Stopping profile...
09-12 14:43:14.500  3863  3863 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
,09-12 14:43:14.500  3863  3863 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-12 14:43:14.501  3863  3863 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1762af8a,
09-12 14:43:14.501  3863  3956 D BluetoothAdapterState: Stopping profile services that were post enabled
09-12 14:43:14.501  3863  3990 D HeadsetStateMachine: Exit Disconnected: -1
09-12 14:43:14.503  1032  1032 D BluetoothHeadset: Proxy object disconnected
09-12 14:43:14.503  1852  1852 D BluetoothHeadset: Proxy object disconnected
09-12 14:43:14.503  1032  1032 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-12 14:43:14.503  1852  1852 D BluetoothHeadset: Proxy object disconnected
,09-12 14:43:14.503  1852  1852 D BluetoothHeadset: Proxy object disconnected
09-12 14:43:14.504  3863  3863 D A2dpService: Received stop request...Stopping profile...
09-12 14:43:14.506  3863  4044 D A2dpStateMachine: Exit Disconnected: -1
09-12 14:43:14.507  3863  3863 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
,09-12 14:43:14.509  3863  3863 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
09-12 14:43:14.509  3863  3863 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
09-12 14:43:14.509  3863  3863 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1762af8a
09-12 14:43:14.510  1032  1032 D BluetoothA2dp: Proxy object disconnected
09-12 14:43:14.510  1032  1032 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-12 14:43:14.510  3863  3863 D HidService: Received stop request...Stopping profile...
09-12 14:43:14.510  3863  3863 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1762af8a
09-12 14:43:14.512  3863  3863 D HealthService: Received stop request...Stopping profile...
09-12 14:43:14.512  6738  6738 D BluetoothInputDevice: Proxy object disconnected
,09-12 14:43:14.512  3863  3863 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1762af8a
09-12 14:43:14.512  6738  6738 D HidProfile: Bluetooth service disconnected
09-12 14:43:14.513  3863  3863 D PanService: Received stop request...Stopping profile...
09-12 14:43:14.514  3863  3863 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1762af8a
09-12 14:43:14.515  6738  6738 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-12 14:43:14.515  6738  6738 D PanProfile: Bluetooth service disconnected
09-12 14:43:14.515  3863  3863 D BtGatt.DebugUtils: handleDebugAction() action=null
09-12 14:43:14.515  3863  3863 D BtGatt.GattService: Received stop request...Stopping profile...
09-12 14:43:14.515  3863  3863 D BtGatt.GattService: stop()
09-12 14:43:14.516  3863  3863 D BtGatt.AdvertiseManager: advertise clients cleared
09-12 14:43:14.517  3863  3863 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1762af8a
09-12 14:43:14.519  3863  3863 D BluetoothMapService: Received stop request...Stopping profile...
09-12 14:43:14.519  3863  3863 D BluetoothMapService: stop()
09-12 14:43:14.519  3863  3863 D BluetoothMapEmailAppObserver: deinitObservers()
09-12 14:43:14.520  3863  3863 D BluetoothMapEmailAppObserver: removeReceiver()
,09-12 14:43:14.520  3863  3863 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1762af8a
09-12 14:43:14.522  3863  3863 D HeadsetStateMachine: Unbinding service...
09-12 14:43:14.522  6738  6738 D BluetoothMap: Proxy object disconnected
09-12 14:43:14.522  6738  6738 D MapProfile: Bluetooth service disconnected
09-12 14:43:14.523  3863  3863 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-12 14:43:14.523  3863  3863 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-12 14:43:14.523  3863  3863 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-12 14:43:14.523  3863  3863 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-12 14:43:14.523  3863  3863 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-12 14:43:14.523  3863  3863 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-12 14:43:14.523  3863  3863 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-12 14:43:14.523  3863  3863 I BluetoothA2dpServiceJni: cleanupNative
09-12 14:43:14.524  3863  4045 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-12 14:43:14.524  3863  3863 I GKI_LINUX: GKI_exit_task 2 done
09-12 14:43:14.524  3863  3863 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-12 14:43:14.524  3863  3863 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-12 14:43:14.524  3863  3863 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-12 14:43:14.525  3863  3863 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-12 14:43:14.525  3863  3863 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-12 14:43:14.525  3863  3863 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-12 14:43:14.526  3863  3863 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-12 14:43:14.526  3863  3863 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-12 14:43:14.527  3863  3863 V BluetoothMapService: Handler(): got msg=4
09-12 14:43:14.527  3863  3863 D BluetoothMapService: MAP Service closeService in
09-12 14:43:14.527  3863  3863 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-12 14:43:14.527  3863  3863 V BluetoothMapService: MAP Service closeService out
09-12 14:43:14.527  3863  3956 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
09-12 14:43:14.527  3863  3956 D BluetoothAdapterProperties: Setting state to 10
09-12 14:43:14.527  3863  3956 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-12 14:43:14.528  3863  3863 D BluetoothMapService: cleanup()
09-12 14:43:14.528  3863  3863 D BluetoothMapService: MAP Service closeService in
09-12 14:43:14.528  3863  3863 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-12 14:43:14.528  3863  3863 V BluetoothMapService: MAP Service closeService out
09-12 14:43:14.528  1032  1094 D BluetoothManagerService: Message: 60
09-12 14:43:14.528  1032  1094 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
09-12 14:43:14.528  1032  1094 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
09-12 14:43:14.528  1032  1094 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 14:43:14.528  3863  3956 I BluetoothAdapterState: Entering OffState
09-12 14:43:14.529  6738  6755 D BluetoothMap: onBluetoothStateChange: up=false
09-12 14:43:14.530  6738  6763 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-12 14:43:14.531  1032  1094 D BluetoothA2dp: onBluetoothStateChange: up=false
09-12 14:43:14.531  1852  2404 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-12 14:43:14.532  1852  3986 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 14:43:14.533  6738  6755 D BluetoothPbap: onBluetoothStateChange: up=false
09-12 14:43:14.533  1852  1867 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 14:43:14.534  6738  6763 D BluetoothPan: onBluetoothStateChange on: false
09-12 14:43:14.535  1032  1094 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
09-12 14:43:14.535  1032  1094 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
,09-12 14:43:14.537  1032  1094 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
09-12 14:43:14.537  1032  1094 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
09-12 14:43:14.537  1032  1094 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@29feacc3 mBinding = false
09-12 14:43:14.538  1032  1094 D BluetoothManagerService: Sending unbind request.
09-12 14:43:14.540  1032  1094 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
09-12 14:43:14.543  6738  6738 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-12 14:43:14.544  6738  6738 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
09-12 14:43:14.544  6738  6738 D LGBluetoothEventManager: [BTUI] clear device connection state
09-12 14:43:14.544  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-12 14:43:14.544  1941  2276 D LGBluetoothAPIService: Message: 2
09-12 14:43:14.545  1941  2276 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@15b17505 mBinding = false
09-12 14:43:14.545  1941  2276 D LGBluetoothAPIService: Sending unbind request.
09-12 14:43:14.545  1599  1599 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,09-12 14:43:14.548  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 14:43:14.549  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 14:43:14.550  6738  6738 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-12 14:43:14.550  3863  3960 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
09-12 14:43:14.551  3863  3863 I GKI_LINUX: GKI_exit_task 1 done
09-12 14:43:14.551  3863  3863 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
09-12 14:43:14.551  3863  3863 I BluetoothServiceJni: cleanupNative: return from cleanup
09-12 14:43:14.551  3863  3863 I art     : --- WEIRD: removing null entry 246
09-12 14:43:14.551  3863  3863 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
09-12 14:43:14.551  3863  3863 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
09-12 14:43:14.552  1599  1599 D BluetoothAdapter: 848992557: getState() :  mService = null. Returning STATE_OFF
09-12 14:43:14.552  1599  1599 D BluetoothAdapter: 848992557: getState() :  mService = null. Returning STATE_OFF
09-12 14:43:14.554  3863  3863 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
09-12 14:43:14.556  3863  3863 I art     : System.exit called, status: 0
09-12 14:43:14.556  3863  3863 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-12 14:43:14.559  6738  6738 D DockEventReceiver: finishStartingService: stopping service
09-12 14:43:14.576   311  1394 V AudioFlinger: 3863 died, releasing its sessions
09-12 14:43:14.576   311  1394 V AudioFlinger:  pid 1852 @ 0
,09-12 14:43:14.576   311  1394 V AudioFlinger:  pid 3309 @ 1
09-12 14:43:14.576   311  1394 V AudioFlinger:  pid 3309 @ 2
09-12 14:43:14.576  6738  6738 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
09-12 14:43:14.639  1032  1904 I ActivityManager: Process com.android.bluetooth (pid 3863) has died
,09-12 14:43:14.640  1032  1904 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
09-12 14:43:14.648  2208  2208 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-12 14:43:14.667  6738  6738 D BluetoothPermissionRequest: onReceive
,09-12 14:43:14.669  6738  6738 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-12 14:43:14.670  6738  6738 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
09-12 14:43:14.673  6738  6738 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-12 14:43:14.676  6550  6550 I UEI.SmartControl: Supports setup maps: true
09-12 14:43:14.682  6550  6550 D UEI.SmartControl: QS start statue = true Error code = 0
09-12 14:43:14.682  6550  6550 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-12 14:43:14.682  6550  6550 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-12 14:43:14.682  6550  6550 I UEI.SmartControl: ### init IR Blaster...
,09-12 14:43:14.687  6550  6550 D serial_port: Configuring serial port
,09-12 14:43:14.687  6550  6550 E UEI.SmartControl: UEIBLaster setting for 616
09-12 14:43:14.687  6550  6550 I UEI.SmartControl: Setting serial record hearder size = 2
09-12 14:43:14.687  6550  6550 I UEI.SmartControl: configuring settings for MAXQ616
09-12 14:43:14.687  6550  6550 I UEI.SmartControl: Get version...
09-12 14:43:14.706  6550  6887 D UEI.SmartControl: serial port data available: 21
,09-12 14:43:14.733  6550  6550 D UEI.SmartControl: MAXQ616 A2-X4 software.
09-12 14:43:14.733  6550  6550 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-12 14:43:14.733  6550  6550 I UEI.SmartControl: QS saving settings...
,09-12 14:43:14.735  6550  6550 D UEI.SmartControl: IR Blaster version: 25672567
09-12 14:43:14.751  1032  1650 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6889 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,09-12 14:43:14.753  6550  6887 D UEI.SmartControl: serial port data available: 4
09-12 14:43:14.782  6550  6907 I UEI.SmartControl: Device manager: loading config....
09-12 14:43:14.783  6550  6550 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,09-12 14:43:14.783  6550  6907 D UEI.SmartControl: ----------- loading internal config...
09-12 14:43:14.784  6550  6550 E UEI.SmartControl: Services init done
09-12 14:43:14.784  6550  6550 D UEI.SmartControl: QS Service init finished
09-12 14:43:14.785  6550  6550 D UEI.SmartControl: QS Service version name: 2.1.91
09-12 14:43:14.785  6550  6550 D UEI.SmartControl: QS Service version code: 201091
09-12 14:43:14.785  6550  6550 D UEI.SmartControl: Service requested: Control
09-12 14:43:14.791  6550  6907 E UEI.SmartControl: Loading SETTINGS...
09-12 14:43:14.796  6550  6550 D UEI.SmartControl: Request IControl service: devices are loaded...
,09-12 14:43:14.798  6550  6550 D UEI.SmartControl: Internal service binding...
09-12 14:43:14.798  6811  6811 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
09-12 14:43:14.799  6550  6565 I UEI.SmartControl: ------ IControl API: 11
09-12 14:43:14.800  6550  6565 D UEI.SmartControl: File observer start...
09-12 14:43:14.800  6550  6565 E UEI.SmartControl: IR Port is disabled: false
09-12 14:43:14.800  6550  6565 D UEI.SmartControl: Starting file observer...
09-12 14:43:14.800  6550  6907 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
09-12 14:43:14.802  6550  6565 I UEI.SmartControl: Registering callback...
09-12 14:43:14.803  6550  6566 I UEI.SmartControl: ------ IControl API: 19
09-12 14:43:14.805  6550  6566 I UEI.SmartControl: Registering Services Ready callback...
09-12 14:43:14.805  6550  6566 I UEI.SmartControl: Notify client services are ready...
09-12 14:43:14.806  6811  6826 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
09-12 14:43:14.807  6811  6877 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
09-12 14:43:14.807  6811  6877 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
09-12 14:43:14.808  6811  6811 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
09-12 14:43:14.808  6811  6811 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
09-12 14:43:14.809  6550  6565 I UEI.SmartControl: ------ IControl API: 8
,09-12 14:43:14.815  6811  6811 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
09-12 14:43:14.816  6811  6811 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
09-12 14:43:14.816  6811  6811 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
09-12 14:43:14.816  6811  6811 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
09-12 14:43:14.817  6811  6811 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
09-12 14:43:14.818  6811  6811 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
09-12 14:43:14.819  6811  6811 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
09-12 14:43:14.822  6550  6906 I UEI.SmartControl: Notify AllClients services are ready: 0
09-12 14:43:14.822  6550  6906 D UEI.SmartControl: -----service ready thread exits
09-12 14:43:14.822  6811  6827 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
09-12 14:43:14.823  6811  6877 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
09-12 14:43:14.823  6811  6877 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
,09-12 14:43:14.828  6811  6811 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
09-12 14:43:14.828  6811  6811 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
09-12 14:43:14.829  6811  6811 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-12 14:43:14.830  6811  6811 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
09-12 14:43:14.831  6811  6811 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
09-12 14:43:14.832  6811  6811 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
09-12 14:43:14.832  6811  6811 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
09-12 14:43:14.833  6811  6811 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1473684194833]
09-12 14:43:14.835  6811  6811 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
09-12 14:43:14.835  6811  6811 D QRemote : [RemoteControlManager.java:327:handleMessage()] oooooo 140510:retrieveDevices already complete. Do nothing
09-12 14:43:14.836  6889  6889 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
09-12 14:43:14.836  6889  6889 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-12 14:43:14.837  6889  6889 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
09-12 14:43:14.838  6889  6889 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-12 14:43:14.841  1032  1932 I ActivityManager: Killing 6444:com.lge.email/u0a23 (adj 15): empty #17
09-12 14:43:14.865  6889  6889 D BluetoothAdapterApp: Loading JNI Library
,09-12 14:43:14.870  6811  6909 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
09-12 14:43:14.902  6889  6889 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@21a75d83 Instance Count = 1
,09-12 14:43:14.910  1032  1780 W libprocessgroup: failed to open /acct/uid_10023/pid_6444/cgroup.procs: No such file or directory
,09-12 14:43:14.914  6889  6889 D BluetoothAdapterApp: onCreate
09-12 14:43:14.918  6811  6811 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,09-12 14:43:14.920  6811  6811 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-12 14:43:14.921  6811  6811 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
09-12 14:43:14.922  6811  6811 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
09-12 14:43:14.922  6811  6811 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
09-12 14:43:14.923  6811  6811 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
09-12 14:43:14.924  6811  6811 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
09-12 14:43:14.941  6889  6889 D ProfileConfigQcom: [BTUI] HeadsetService is supported
,09-12 14:43:14.941  6889  6889 D ProfileConfigQcom: Adding HeadsetService
09-12 14:43:14.941  6889  6889 D ProfileConfigQcom: [BTUI] A2dpService is supported
09-12 14:43:14.941  6889  6889 D ProfileConfigQcom: Adding A2dpService
09-12 14:43:14.942  6889  6889 D ProfileConfigQcom: [BTUI] HidService is supported
09-12 14:43:14.942  6889  6889 D ProfileConfigQcom: Adding HidService
09-12 14:43:14.942  6889  6889 D ProfileConfigQcom: [BTUI] HealthService is supported
09-12 14:43:14.942  6889  6889 D ProfileConfigQcom: Adding HealthService
09-12 14:43:14.942  6889  6889 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
09-12 14:43:14.943  6889  6889 D ProfileConfigQcom: [BTUI] PanService is supported
09-12 14:43:14.944  6889  6889 D ProfileConfigQcom: Adding PanService
09-12 14:43:14.944  6889  6889 D ProfileConfigQcom: [BTUI] GattService is supported
09-12 14:43:14.944  6889  6889 D ProfileConfigQcom: Adding GattService
09-12 14:43:14.944  6889  6889 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
09-12 14:43:14.944  6889  6889 D ProfileConfigQcom: Adding BluetoothMapService
09-12 14:43:14.945  6889  6889 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
09-12 14:43:14.946  6889  6889 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
09-12 14:43:14.951  6738  6738 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
09-12 14:43:14.954  6811  6811 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
09-12 14:43:14.956  6889  6889 V LGMDMManagerInternal: Create singleton instance
,09-12 14:43:15.061  6889  6889 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,09-12 14:43:15.065  6889  6889 V BluetoothSapReceiver: [BTUI] checkServiceStart
,09-12 14:43:15.065  6889  6889 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-12 14:43:15.066  6889  6889 V BluetoothSapReceiver: SapReceiver onReceive 
09-12 14:43:15.067  6889  6889 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-12 14:43:15.067  6889  6889 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
09-12 14:43:15.084  6830  6830 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,09-12 14:43:15.089  1032  1780 I ActivityManager: Killing 6067:com.android.gallery3d/u0a27 (adj 15): empty #17
09-12 14:43:15.140  1032  1774 W libprocessgroup: failed to open /acct/uid_10027/pid_6067/cgroup.procs: No such file or directory
,09-12 14:43:16.226  1032  1904 D WifiServiceImplEx: setWifiEnabled: true pid=6669, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,09-12 14:43:16.234  1032  1904 D WifiService: setWifiEnabled: true pid=6669, uid=10118
09-12 14:43:16.234  1032  1904 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-12 14:43:16.256  1032  1032 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-12 14:43:16.256  1032  1032 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-12 14:43:16.257  1032  1032 D Ulp_jni : JNI:system_update. Event-4
09-12 14:43:16.258  1032  1396 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
09-12 14:43:16.258  1032  1396 I LGFTMITEM: [GET_FTM][id=6], offset=12288
09-12 14:43:16.261  1032  1396 E WifiUtil: wfc_util_ffile_check_copy(): pid[1032] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
09-12 14:43:16.261  1032  1396 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-12 14:43:16.261  1032  1396 E WifiUtil: wfc_util_ffile_check_copy(): pid[1032] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
09-12 14:43:16.261  1032  1396 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-12 14:43:16.261  1032  1396 I WifiUtil: Intf0MacAddress=C49A027FFB5D
09-12 14:43:16.261  1032  1396 E WifiHW  : unknown target_country: EU , set to default
09-12 14:43:16.261  1032  1396 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
09-12 14:43:16.261  1032  1396 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
09-12 14:43:16.261  1032  1396 I WifiUtil: gEnableBmps=1
09-12 14:43:16.291  1032  1466 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-12 14:43:16.296  1032  1094 D Tethering: MasterInitialState.processMessage what=3
09-12 14:43:16.305  1032  1466 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-12 14:43:16.311  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 14:43:16.313  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 14:43:16.318  1032  1089 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-12 14:43:16.321  1032  1094 D Tethering: MasterInitialState.processMessage what=3
09-12 14:43:16.330  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 14:43:16.333  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 14:43:16.334  6356  6356 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-12 14:43:16.337  6356  6765 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-12 14:43:16.349  5772  5772 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,09-12 14:43:16.358  5772  5772 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,09-12 14:43:16.376  2208  2208 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-12 14:43:16.412  1032  1089 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-12 14:43:16.450  1032  1572 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6934 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,09-12 14:43:16.454  1032  1089 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 14:43:16.455  1032  1089 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-12 14:43:16.518  6934  6934 I AppUp4:AppBoxCP: onCreate
,09-12 14:43:16.519  6934  6934 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
09-12 14:43:16.529  6934  6934 I AppUp4:DB:  setFingerPrint start
09-12 14:43:16.530  6934  6934 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
,09-12 14:43:16.538  6934  6934 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
,09-12 14:43:16.538  6934  6934 I AppUp4:DB:  SDK version = 21
09-12 14:43:16.539  6934  6934 I AppUp4:DB:  beforefinger == newfinger no write in DB
09-12 14:43:16.541  6934  6934 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
09-12 14:43:16.542  6934  6934 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-12 14:43:16.542  6934  6934 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-12 14:43:16.545  6934  6934 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-12 14:43:16.545  6934  6934 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,09-12 14:43:16.555  6934  6934 I AppUp4:CustModeStarterReceiver: onReceive
09-12 14:43:16.607  6934  6934 D LgDataFeature: LgDataFeature() Constructor: none
09-12 14:43:16.607  6934  6934 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-12 14:43:16.616  6934  6934 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@344495f5
09-12 14:43:16.617  6934  6934 D AppUp4:CustFacade: isCustomizationCompleted : false
09-12 14:43:16.617  6934  6934 D AppUp4:CustFacade: isPhone : true
09-12 14:43:16.617  6934  6934 D AppUp4:CustModeStarterReceiver: begin check event
09-12 14:43:16.618  6934  6934 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
09-12 14:43:16.618  6934  6934 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
09-12 14:43:16.619  6934  6956 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
09-12 14:43:16.619  6934  6956 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
09-12 14:43:16.620  6934  6956 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
09-12 14:43:16.623  1032  1932 I ActivityManager: Killing 6131:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,09-12 14:43:16.681  1032  1650 W libprocessgroup: failed to open /acct/uid_10080/pid_6131/cgroup.procs: No such file or directory
09-12 14:43:16.682  4334  4334 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,09-12 14:43:16.687  4334  4334 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-12 14:43:16.687  1032  1376 D PowerManagerServiceEx: acquireWakeLockInternal: lock=55543020, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1032
09-12 14:43:16.689  1032  1376 V AlarmManager: ELAPSED_WAKEUP set : Alarm{3664c4cd type 2 when 196265 com.google.android.gms} when 196265
09-12 14:43:16.694  4334  4334 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-12 14:43:16.699  4334  4334 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-12 14:43:16.711  4334  6958 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-12 14:43:16.716  4334  6959 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-12 14:43:16.716  4334  6959 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,09-12 14:43:16.782  1032  1780 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6960 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,09-12 14:43:16.798  2591  2591 D [Concierge]Service: onStartCommand(). Type : 9
,09-12 14:43:16.857  6960  6960 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-12 14:43:16.857  6960  6960 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-12 14:43:16.859  6960  6960 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-12 14:43:16.860  6960  6960 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-12 14:43:16.956  6960  6960 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,09-12 14:43:16.971  1032  1094 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-12 14:43:16.971  1032  1094 D Tethering: InitialState.processMessage what=4
,09-12 14:43:16.974   306   892 D SoftapController: Softap fwReload - Ok
09-12 14:43:16.975  1032  1396 E NetdConnector: NDC Command {52 softap fwreload wlan0 STA} took too long (708ms)
09-12 14:43:16.977   306   892 D CommandListener: Setting iface cfg
09-12 14:43:16.977   306   892 D CommandListener: Trying to bring down wlan0
09-12 14:43:16.978   306   892 D CommandListener: Clearing all IP addresses on wlan0
09-12 14:43:16.979  1032  1094 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-12 14:43:16.981  1032  1396 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
09-12 14:43:16.971  6985  6985 W wpa_supplicant: type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-12 14:43:16.971  6985  6985 W wpa_supplicant: type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-12 14:43:16.990  6960  6960 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,09-12 14:43:17.016  6985  6985 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-12 14:43:17.032  6960  6960 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-12 14:43:17.040  6985  6985 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-12 14:43:17.041  6985  6985 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,09-12 14:43:17.061  6960  6960 D LgDataFeature: LgDataFeature() Constructor: none
,09-12 14:43:17.062  6960  6960 D LgDataFeature: LgDataFeature() Constructor Done, null
09-12 14:43:17.082  1032  1396 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-12 14:43:17.082  1032  1396 E WifiStateMachine: useWiFiOffloading() : false
09-12 14:43:17.082  1032  1396 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-12 14:43:17.082  1032  1396 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-12 14:43:17.082  1032  1396 D WifiMonitor: connecting to supplicant
,09-12 14:43:17.083  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 14:43:17.084  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
09-12 14:43:17.086  1032  1032 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
09-12 14:43:17.086  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 14:43:17.087  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 14:43:17.104  6985  6985 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-12 14:43:17.139  6960  6960 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,09-12 14:43:17.156  6985  6985 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,09-12 14:43:17.164  3309  3309 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-12 14:43:17.164  3309  3309 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-12 14:43:17.164  3309  3309 I LgeMiscReceiver: networkInfo.isConnected() = false
09-12 14:43:17.170  6985  6985 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
,09-12 14:43:17.171  1032  1396 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
09-12 14:43:17.172  1032  1396 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
09-12 14:43:17.172  6960  6960 I HubEmail: JNI_OnLoad()
09-12 14:43:17.172  1032  1396 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
09-12 14:43:17.172  6960  6960 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-12 14:43:17.172  6960  6960 I HubEmail: registerNatives()
09-12 14:43:17.172  6960  6960 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-12 14:43:17.172  6960  6960 I HubEmail: registerNativeMethods()
09-12 14:43:17.172  6960  6960 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-12 14:43:17.172  1032  1396 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
09-12 14:43:17.173  6960  6960 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
09-12 14:43:17.173  1032  1396 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-12 14:43:17.173  1032  1396 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-12 14:43:17.174  1032  1396 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-12 14:43:17.174  6985  6985 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
09-12 14:43:17.174  1032  1396 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-12 14:43:17.174  1032  6992 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
09-12 14:43:17.174  1032  1396 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
09-12 14:43:17.174  1032  6992 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
09-12 14:43:17.175  1032  1396 D WifiNative-wlan0: doString: [DRIVER MACADDR]
09-12 14:43:17.175  1032  6992 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
09-12 14:43:17.175  1032  6992 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
09-12 14:43:17.175  1032  1396 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
09-12 14:43:17.175  1032  6992 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
09-12 14:43:17.175  1032  1396 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
09-12 14:43:17.175  1032  1396 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
09-12 14:43:17.175  1032  6992 D WifiMonitor: Dropping event because (p2p0) is stopped
09-12 14:43:17.200  1032  1932 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6996 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,09-12 14:43:17.203  1032  1396 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-12 14:43:17.203  1032  1396 E WifiStateMachine: useWiFiOffloading() : false
09-12 14:43:17.203  1032  1396 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-12 14:43:17.204  1032  1396 D WifiNative-wlan0: doBoolean: SET update_config 1
09-12 14:43:17.204  1032  1396 D WifiNative-wlan0: SET update_config 1: returned true
09-12 14:43:17.204  1032  1396 D WifiConfigStore: Loading config and enabling all networks 
09-12 14:43:17.204  1032  1396 D WifiNative-wlan0: doString: [LIST_NETWORKS]
09-12 14:43:17.204  1032  1396 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
09-12 14:43:17.205  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 14:43:17.205  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-12 14:43:17.206  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 14:43:17.206  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 14:43:17.206  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-12 14:43:17.206  1941  1941 D WfdService: Waiting for WifiP2p enabling
09-12 14:43:17.208  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 14:43:17.208  6669  6669 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 14:43:17.209  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 14:43:17.209  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 14:43:17.209  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 14:43:17.209  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 14:43:17.209  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 14:43:17.209  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 14:43:17.209  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 14:43:17.209  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 14:43:17.209  6669  6669 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 14:43:17.209  6669  6669 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-12 14:43:17.209  6850  6993 W FormManager: Network not available. Please check & try again.
09-12 14:43:17.210  1032  1032 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
09-12 14:43:17.210  1032  1441 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
09-12 14:43:17.210  6669  6669 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 14:43:17.210  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 14:43:17.210  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 14:43:17.210  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 14:43:17.210  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 14:43:17.210  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 14:43:17.210  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 14:43:17.210  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 14:43:17.210  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 14:43:17.210  6669  6669 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 14:43:17.211  6669  6669 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-12 14:43:17.211  6850  6994 V FormManager: Network unavailable.
09-12 14:43:17.212  6850  6,994 V FormManager: Network unavailable.
09-12 14:43:17.213  1032  1396 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
,09-12 14:43:17.220  1032  1940 I ActivityManager: Killing 6479:com.google.android.apps.docs/u0a61 (adj 15): empty #17
09-12 14:43:17.222  1032  1396 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
09-12 14:43:17.222  1032  1396 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-12 14:43:17.280  6960  6995 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-12 14:43:17.281  1032  1396 D WifiStateMachine: enableVerboseLogging : level 2
09-12 14:43:17.282  1032  1396 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
09-12 14:43:17.282  1032  1396 D WifiNative-wlan0: SET device_name g3_global_com: returned true
09-12 14:43:17.283  1032  1396 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
09-12 14:43:17.284  1032  1396 D WifiNative-wlan0: SET manufacturer LGE: returned true
09-12 14:43:17.284  1032  1396 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
09-12 14:43:17.285  1032  1396 D WifiNative-wlan0: SET model_name LG-D855: returned true
09-12 14:43:17.285  1032  1396 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
09-12 14:43:17.286  1032  1396 D WifiNative-wlan0: SET model_number LG-D855: returned true
09-12 14:43:17.286  1032  1396 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
09-12 14:43:17.287  1032  1396 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
09-12 14:43:17.288  1032  1396 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
09-12 14:43:17.289  1032  1396 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
09-12 14:43:17.289  1032  1396 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
09-12 14:43:17.290  1032  1396 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
09-12 14:43:17.293  1032  1780 W libprocessgroup: failed to open /acct/uid_10061/pid_6479/cgroup.procs: No such file or directory
09-12 14:43:17.293  1032  1396 D WifiStateMachine: Setting OUI to DA-A1-19
09-12 14:43:17.293  1032  1396 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
,09-12 14:43:17.294  1032  1396 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
09-12 14:43:17.295  1941  1941 D WfdsService: Supplicant Connection state is changed : true
09-12 14:43:17.295  1941  2410 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
09-12 14:43:17.295  1032  1396 D WifiNative-HAL: Setting external_sim to 1
09-12 14:43:17.295  1941  2410 D WfdsService: Set the WFDS Monitor: true
09-12 14:43:17.295  1032  1396 D WifiNative-wlan0: doBoolean: SET external_sim 1
09-12 14:43:17.295  1941  2410 D WfdsMonitor: WfdsMonitorThread create
09-12 14:43:17.296  1941  2410 D WfdsMonitor: WFDS Monitor is created and started
09-12 14:43:17.296  1941  2410 D WfdsService: WiFi: Supplicant connection re-established
09-12 14:43:17.296  1032  1396 D WifiNative-wlan0: SET external_sim 1: returned true
09-12 14:43:17.296  1032  1396 I WifiNative-HAL: startHal
09-12 14:43:17.296  1032  1396 D wifi    : setting scan oui 0x957915c0
,09-12 14:43:17.298  1032  1396 D WifiStateMachine: Setting OUI to DA-A1-19
09-12 14:43:17.298  1032  1396 I WifiNative-HAL: startHal
09-12 14:43:17.298  1032  1396 D wifi    : setting scan oui 0x957915c0
09-12 14:43:17.299  1032  1396 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
09-12 14:43:17.303  1032  1396 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
09-12 14:43:17.303  1032  1396 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
09-12 14:43:17.304  6985  6985 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
09-12 14:43:17.304  1941  7013 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
09-12 14:43:17.304  1941  7013 E CtrlSupplicant: Succeed to open control connection
09-12 14:43:17.305  1941  7013 E CtrlSupplicant: Succeed to open monitor connection
09-12 14:43:17.305  1032  1396 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
09-12 14:43:17.305  1032  1396 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-12 14:43:17.305  6985  6985 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-12 14:43:17.306  1032  1396 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-12 14:43:17.306  1032  1396 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
09-12 14:43:17.307  6985  6985 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
09-12 14:43:17.305  1941  7013 D WfdsMonitor: Supplicant connection established
09-12 14:43:17.307  1941  2410 D WfdsService: Connected to the supplicant for wfds
09-12 14:43:17.308  1032  1396 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
09-12 14:43:17.308  1032  1396 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-12 14:43:17.308  6985  6985 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-12 14:43:17.308  1032  1396 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-12 14:43:17.308  1032  1396 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-12 14:43:17.309  6985  6985 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-12 14:43:17.309  1032  1396 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-12 14:43:17.309  1032  1396 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
09-12 14:43:17.309  6985  6985 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
09-12 14:43:17.310  1032  1396 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
09-12 14:43:17.310  1032  1396 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-12 14:43:17.310  6985  6985 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-12 14:43:17.310  1032  1396 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-12 14:43:17.311  1032  1396 E WifiNative: : [196,910,915 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
09-12 14:43:17.312  1032  1396 D WifiNative-wlan0: doBoolean: RECONNECT
09-12 14:43:17.312  1032  1396 D WifiNative-wlan0: RECONNECT: returned true
,09-12 14:43:17.312  1032  1396 D WifiNative-wlan0: doString: [STATUS]
09-12 14:43:17.313  1032  1396 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-12 14:43:17.313  1032  1396 D WifiNative-wlan0: doBoolean: SET ps 1
09-12 14:43:17.314  1032  1396 D WifiNative-wlan0: SET ps 1: returned true
09-12 14:43:17.314  1032  6992 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-12 14:43:17.314  1032  6992 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-12 14:43:17.314  1032  1387 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
09-12 14:43:17.315  1032  1032 D WifiScanningService: SCAN_AVAILABLE : 3
,09-12 14:43:17.315  1032  1032 D RttService: SCAN_AVAILABLE : 3
,09-12 14:43:17.316  1032  1553 D WifiScanningService: DefaultState got{ when=-2ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-12 14:43:17.316  1032  1553 I WifiNative-HAL: startHal
09-12 14:43:17.317  1032  1396 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
09-12 14:43:17.317  1032  1553 D wifi    : getting scan capabilities on interface[1] = 0x957915c0
09-12 14:43:17.317  1032  1553 D wifi    : failed to get capabilities : -3
09-12 14:43:17.317  1032  1553 E WifiScanningService: could not get scan capabilities
09-12 14:43:17.317  1032  1554 D RttService: DefaultState got{ when=-2ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-12 14:43:17.317  1032  1396 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
09-12 14:43:17.318  1032  1396 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
09-12 14:43:17.318  1032  1396 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
09-12 14:43:17.318   306   892 D CommandListener: Setting iface cfg
09-12 14:43:17.319   306   892 D CommandListener: Trying to bring up p2p0
09-12 14:43:17.319  1032  1396 E WifiStateMachine:  DisconnectedState what:132106 1 0
09-12 14:43:17.319  1032  1387 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-12 14:43:17.319  1032  1387 D LGWifiP2pService: P2pEnablingState
09-12 14:43:17.319  1032  1396 E WifiStateMachine:  ConnectModeState what:132106 1 0
09-12 14:43:17.319  1032  1387 D LGWifiP2pService: P2pEnablingState{ when=-1ms what=147457 target=com.android.internal.util.StateMachine$SmHandler }
09-12 14:43:17.319  1032  1387 D LGWifiP2pService: P2p socket connection successful
09-12 14:43:17.319  1032  1387 D LGWifiP2pService: P2pEnabledState
09-12 14:43:17.320  1032  1396 E WifiStateMachine:  DriverStartedState what:132106 1 0
09-12 14:43:17.320  1032  1396 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
09-12 14:43:17.320  6985  6985 E wpa_supplicant: nWIFIDualbandAPConnection: 1
09-12 14:43:17.320  1032  1387 D LGWifiP2pService: sending p2p connection changed broadcast
09-12 14:43:17.321  1032  1387 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
09-12 14:43:17.321  1032  1396 E WifiStateMachine:  DisconnectedState what:132096 -100 0
09-12 14:43:17.322  1032  1396 E WifiStateMachine:  ConnectModeState what:132096 -100 0
09-12 14:43:17.322  1032  1396 E WifiStateMachine:  DriverStartedState what:132096 -100 0
09-12 14:43:17.322  1032  1396 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
09-12 14:43:17.323  6985  6985 E wpa_supplicant: disconnect_rssi_lvl: -100
09-12 14:43:17.323  1032  1396 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
09-12 14:43:17.324  1032  1396 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
09-12 14:43:17.324  1032  1396 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
09-12 14:43:17.324  1032  1396 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
09-12 14:43:17.325  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
09-12 14:43:17.325  1941  1941 D WfdsService: WifiP2pState is changed : true
,09-12 14:43:17.326  1941  1941 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
09-12 14:43:17.326  1941  2410 D WfdsService: Receive the WFDS_ENABLE Method
09-12 14:43:17.326  1941  2410 D WfdsService: Set the WFDS Monitor: true
09-12 14:43:17.326  1941  2410 D WfdsService: Connected to the supplicant for wfds
09-12 14:43:17.326  1941  2410 D WfdsJNI : doCommand: WFDS_SET TRUE
09-12 14:43:17.326  1032  1387 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
09-12 14:43:17.326  6985  6985 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
09-12 14:43:17.327  1941  2410 D WfdsService: selectPreferredScanChannel [36]
09-12 14:43:17.327  1941  2410 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
09-12 14:43:17.327  1032  1387 D WifiNative-p2p0: doBoolean: SET device_name G3
09-12 14:43:17.327  6985  6985 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-12 14:43:17.328  1941  1941 D WfdsService: isConnected: false
09-12 14:43:17.328  6985  6985 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-12 14:43:17.329  6985  6985 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-12 14:43:17.329  6985  6985 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 14:43:17.329  1032  6992 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-12 14:43:17.329  6985  6985 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 14:43:17.330  1032  6992 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-12 14:43:17.330  1032  6992 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-12 14:43:17.330  1032  6992 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-12 14:43:17.330  1032  6992 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-12 14:43:17.330  1032  6992 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 14:43:17.330  1032  6992 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 14:43:17.330  1032  6992 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 14:43:17.330  1032  6992 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-12 14:43:17.330  1032  6992 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 14:43:17.330  1032  6992 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 14:43:17.330  1032  6992 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 14:43:17.330  1941  7013 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-12 14:43:17.330  1941  7013 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-12 14:43:17.331  1032  1396 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
09-12 14:43:17.331  1032  1387 D WifiNative-p2p0: SET device_name G3: returned true
09-12 14:43:17.331  1032  1387 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
09-12 14:43:17.331  1032  1387 D LGWifiP2pService: before postfix = G3
09-12 14:43:17.331  1032  1387 D WifiServerServiceExt: postfix byte check : 2
09-12 14:43:17.331  1032  1396 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
09-12 14:43:17.331  1032  1387 D LGWifiP2pService: after postfix = G3
09-12 14:43:17.331  1032  1387 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
09-12 14:43:17.332  1032  1396 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
09-12 14:43:17.332  1032  1387 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
09-12 14:43:17.332  1032  1387 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
09-12 14:43:17.332  1032  139,6 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
09-12 14:43:17.332  1032  1396 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
09-12 14:43:17.332  1032  1387 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
09-12 14:43:17.332  1032  1387 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
09-12 14:43:17.332  6985  6985 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
09-12 14:43:17.332  6985  6985 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-12 14:43:17.333  1032  6992 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
09-12 14:43:17.333  1032  6992 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-12 14:43:17.333  1032  6992 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-12 14:43:17.333  1032  6992 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-12 14:43:17.333  1032  1396 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
09-12 14:43:17.334  1032  1396 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
09-12 14:43:17.334  1032  1387 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
09-12 14:43:17.334  1032  1387 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
09-12 14:43:17.334  1032  1387 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
09-12 14:43:17.334  1032  1387 D WifiNative-HAL: p2pGetDeviceAddress
09-12 14:43:17.335  1032  1387 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
09-12 14:43:17.335  1032  1396 D WifiNative-wlan0: BSS_FLUSH 0: returned true
09-12 14:43:17.335  1032  1396 D WifiNative-wlan0: doBoolean: SCAN
09-12 14:43:17.335  1032  1387 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
09-12 14:43:17.335  1032  1387 D WifiNative-p2p0: doBoolean: P2P_FLUSH
09-12 14:43:17.336  1941  1941 I WfdStateTracker: handleP2pThisDeviceChanged
09-12 14:43:17.336  1032  1396 D WifiNative-wlan0: SCAN: returned false
09-12 14:43:17.336  1941  1941 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
09-12 14:43:17.337  1941  1941 D WfdsService: Update P2p Interface State: 3
09-12 14:43:17.337  1032  1387 D WifiNative-p2p0: P2P_FLUSH: returned true
09-12 14:43:17.337  1032  1387 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
09-12 14:43:17.337  1032  1396 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=196937  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-12 14:43:17.337  1032  1387 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
09-12 14:43:17.337  1032  1387 D WifiNative-p2p0: doString: [LIST_NETWORKS]
09-12 14:43:17.338  1032  1387 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
09-12 14:43:17.338  1032  1387 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
,09-12 14:43:17.342  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 14:43:17.342  1599  1599 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-12 14:43:17.343  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 14:43:17.345  1032  1396 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=196945  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-12 14:43:17.346  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 14:43:17.346  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 14:43:17.346  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-12 14:43:17.346  1032  1396 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-12 14:43:17.347  1032  1396 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-12 14:43:17.348  1032  1396 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-12 14:43:17.348  1032  1387 D WifiNative-p2p0: SAVE_CONFIG: returned true
09-12 14:43:17.348  1032  1387 D LGWifiP2pService: sending p2p persistent groups changed broadcast
09-12 14:43:17.348  1032  1387 D LGWifiP2pService: InactiveState
09-12 14:43:17.348  1032  1396 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-12 14:43:17.348  1032  1387 D LGWifiP2pService: InactiveState{ when=-18ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-12 14:43:17.348  1032  1387 D LGWifiP2pService: P2pEnabledState{ when=-18ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-12 14:43:17.348  1032  1387 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
09-12 14:43:17.349  1032  1396 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-12 14:43:17.349  6985  6985 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-12 14:43:17.350  6985  6985 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-12 14:43:17.350  1941  7013 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-12 14:43:17.351  6985  6985 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-12 14:43:17.351  6985  6985 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 14:43:17.351  1941  7013 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-12 14:43:17.351  1032  1387 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
09-12 14:43:17.351  1032  1387 D LGWifiP2pService: InactiveState{ when=-13ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-12 14:43:17.351  1032  6992 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-12 14:43:17.351  1032  6992 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-12 14:43:17.351  1032  1387 D LGWifiP2pService: P2pEnabledState{ when=-13ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-12 14:43:17.351  1032  6992 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-12 14:43:17.351  1032  1387 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-12 14:43:17.351  1032  6992 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-12 14:43:17.351  1032  1387 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-12 14:43:17.351  6985  6985 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 14:43:17.351  1032  1387 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.Sta,teMachine$SmHandler }
09-12 14:43:17.351  1032  6992 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-12 14:43:17.352  1032  6992 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 14:43:17.352  1032  1387 D LGWifiP2pService: InactiveState{ when=-3ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-12 14:43:17.352  1032  6992 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 14:43:17.352  1032  6992 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 14:43:17.352  1032  1387 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-12 14:43:17.352  1032  1387 D LGWifiP2pService: DefaultState{ when=-3ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-12 14:43:17.352  1032  6992 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-12 14:43:17.352  1032  6992 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 14:43:17.352  1032  1387 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-12 14:43:17.352  1032  6992 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 14:43:17.352  1032  6992 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 14:43:17.352  1032  1387 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-12 14:43:17.352  1032  1387 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-12 14:43:17.352  1032  1387 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-12 14:43:17.352  1941  7013 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-12 14:43:17.352  1032  1387 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-12 14:43:17.352  1032  1387 D LGWifiP2pService: DefaultState{ when=-2ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-12 14:43:17.353  1941  2410 W WfdsService: DefaultState - msg [9441285] is not handled
,09-12 14:43:17.353  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-12 14:43:17.353  1032  1032 D WifiServerServiceExt: setSupplicantStateSCANNING
09-12 14:43:17.353  1032  1032 E WifiServerServiceExt: No p2p device connected
09-12 14:43:17.395  6996  6996 D LgDataFeature: LgDataFeature() Constructor: none
,09-12 14:43:17.395  6996  6996 D LgDataFeature: LgDataFeature() Constructor Done, null
09-12 14:43:17.398  6996  6996 D PhoneMonitor: Register our PhoneStateListener
09-12 14:43:17.409  6996  6996 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,09-12 14:43:17.411  6996  6996 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-12 14:43:17.423  6996  6996 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,09-12 14:43:17.424  6996  6996 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
09-12 14:43:17.426  6996  6996 D TelephonyAutoProfiling: [parse] Load xml
,09-12 14:43:17.432  6996  6996 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
09-12 14:43:17.433  6996  6996 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
09-12 14:43:17.433  6996  6996 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
09-12 14:43:17.433  6996  6996 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
09-12 14:43:17.433  6996  6996 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
09-12 14:43:17.433  6996  6996 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
09-12 14:43:17.433  6996  6996 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
,09-12 14:43:17.433  6996  6996 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
09-12 14:43:17.433  6996  6996 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
09-12 14:43:17.433  6996  6996 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
09-12 14:43:17.433  6996  6996 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
09-12 14:43:17.434  6996  6996 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
09-12 14:43:17.434  6996  6996 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
09-12 14:43:17.434  6996  6996 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
09-12 14:43:17.434  6996  6996 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
09-12 14:43:17.434  6996  6996 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
09-12 14:43:17.434  6996  6996 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,09-12 14:43:17.442  6996  6996 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
09-12 14:43:17.464  1032  1048 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7016 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-12 14:43:17.464  1032  1048 I ActivityManager: Killing 6159:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,09-12 14:43:17.528  1032  1650 W libprocessgroup: failed to open /acct/uid_10097/pid_6159/cgroup.procs: No such file or directory
,09-12 14:43:17.796  1032  1650 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7040 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,09-12 14:43:17.802  1032  1650 I ActivityManager: Killing 6512:com.lge.eula/1000 (adj 15): empty #17
09-12 14:43:17.829  1032  6992 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
09-12 14:43:17.830  1032  6992 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
09-12 14:43:17.830  1032  6992 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
09-12 14:43:17.830  1032  6992 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: WPS-AP-AVAILABLE 
09-12 14:43:17.830  6985  6985 E wpa_supplicant: USIM:  scard_init function
09-12 14:43:17.830  1032  6992 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
09-12 14:43:17.830  6985  6985 I wpa_supplicant: Trying to associate with SSID 'NG700'
,09-12 14:43:17.832  1032  6992 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
09-12 14:43:17.832  1032  6992 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
09-12 14:43:17.834  1032  1396 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-12 14:43:17.834  1032  1396 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-12 14:43:17.835  1032  1396 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-12 14:43:17.835  1032  1396 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-12 14:43:17.836  1032  1396 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
09-12 14:43:17.858  1032  1774 W libprocessgroup: failed to open /acct/uid_1000/pid_6512/cgroup.procs: No such file or directory
,09-12 14:43:17.863  1032  1396 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=197463  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-12 14:43:17.866  1032  1396 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=197466  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-12 14:43:17.867  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 14:43:17.867  1599  1599 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-12 14:43:17.868  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 14:43:17.868  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 14:43:17.868  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-12 14:43:17.871  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 14:43:17.871  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 14:43:17.871  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-12 14:43:17.871  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-12 14:43:17.871  1032  1032 D WifiServerServiceExt: setSupplicantStateASSOCIATING
,09-12 14:43:17.875  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-12 14:43:17.882  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 14:43:17.882  1599  1599 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-12 14:43:17.883  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-12 14:43:17.942  6985  6985 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
09-12 14:43:17.942  1032  6992 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
09-12 14:43:17.942  1032  6992 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
,09-12 14:43:17.943  1032  6992 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
09-12 14:43:17.943  1032  6992 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: Associated with f4:f2:6d:22:99:3e
09-12 14:43:17.943  1032  6992 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-12 14:43:17.943  1032  6992 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-12 14:43:17.946  1032  1396 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=197545  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-12 14:43:17.947  1032  1396 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=197547  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-12 14:43:17.949  1032  1396 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=197549
09-12 14:43:17.950  1032  1396 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=197550
09-12 14:43:17.951  1032  1396 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=197551
09-12 14:43:17.952  1032  1396 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=197552
09-12 14:43:17.953  1032  1396 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=197553
,09-12 14:43:17.955  1032  1396 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=197554  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-12 14:43:17.956  1032  6992 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-12 14:43:17.956  1032  6992 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-12 14:43:17.957  6985  6985 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-12 14:43:17.957  6985  6985 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-12 14:43:17.959  1032  6992 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
09-12 14:43:17.959  1032  6992 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-12 14:43:17.959  1032  6992 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-12 14:43:17.960  1032  6992 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
09-12 14:43:17.961  1032  6992 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-12 14:43:17.961  1032  6992 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-12 14:43:17.961  1032  6992 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-12 14:43:17.961  1032  6992 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-12 14:43:17.984  1032  1774 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7067 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-12 14:43:17.985  1032  1774 I ActivityManager: Killing 6529:com.lge.bnr/1000 (adj 15): empty #17
,09-12 14:43:18.019  1032  1094 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-12 14:43:18.019  1032  1572 W libprocessgroup: failed to open /acct/uid_1000/pid_6529/cgroup.procs: No such file or directory
09-12 14:43:18.027  1032  1396 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=197627  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-12 14:43:18.028  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 14:43:18.028  1599  1599 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-12 14:43:18.029  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 14:43:18.029  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 14:43:18.029  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-12 14:43:18.029  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-12 14:43:18.033  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-12 14:43:18.033  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 14:43:18.033  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
09-12 14:43:18.034  1032  1396 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=197634  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-12 14:43:18.034  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-12 14:43:18.034  1032  1032 D WifiServerServiceExt: setSupplicantStateASSOCIATED
09-12 14:43:18.035  1032  1396 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=197635  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-12 14:43:18.036  1032  1396 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=197636
09-12 14:43:18.036  1032  1396 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=197636
09-12 14:43:18.037  1032  1396 D WifiNative-wlan0: doString: [STATUS]
09-12 14:43:18.037  1032  6992 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-12 14:43:18.037  1032  6992 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-12 14:43:18.038  1032  1396 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-12 14:43:18.040  1032  1396 I WifiServiceExtension: setVHTCapabilityType  : false
09-12 14:43:18.044  1032  1396 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
09-12 14:43:18.044  1032  1396 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,09-12 14:43:18.048  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 14:43:18.048  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 14:43:18.048  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-12 14:43:18.051  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 14:43:18.051  1599  1599 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-12 14:43:18.053  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 14:43:18.053  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 14:43:18.053  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-12 14:43:18.053  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 14:43:18.054  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 14:43:18.055  1599  1599 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-12 14:43:18.055  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 14:43:18.056  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 14:43:18.056  1599  1599 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-12 14:43:18.057  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 14:43:18.059  1032  1396 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
09-12 14:43:18.059  1032  1466 D ConnectivityService: Got NetworkAgent Messenger
09-12 14:43:18.060  1032  1466 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-12 14:43:18.060  1032  1466 D ConnectivityService: NetworkAgent connected
09-12 14:43:18.060  1032  1396 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-12 14:43:18.060  1032  1396 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-12 14:43:18.060  7067  7067 I art     : Almond Protected OAT
,09-12 14:43:18.061  1032  1396 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-12 14:43:18.061  1032  1396 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-12 14:43:18.066  1032  1396 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-12 14:43:18.066  1032  1396 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-12 14:43:18.066  1032  1396 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-12 14:43:18.067  1032  1396 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-12 14:43:18.067  1032  1396 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-12 14:43:18.071  1032  1396 D WifiNative-wlan0: SAVE_CONFIG: returned true
,09-12 14:43:18.073   306   892 D CommandListener: Setting iface cfg
09-12 14:43:18.075  1032  7087 D DhcpStateMachine: StoppedState
09-12 14:43:18.075  1032  1396 E WifiStateMachine: Start Dhcp Watchdog 2
09-12 14:43:18.075  1032  7087 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
09-12 14:43:18.076  1032  7087 D DhcpStateMachine: WaitBeforeStartState
09-12 14:43:18.076  1032  1396 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=197676  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-12 14:43:18.077  1032  1396 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=197677  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-12 14:43:18.077  1032  1396 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=197677  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-12 14:43:18.078  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-12 14:43:18.078  1032  1032 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
09-12 14:43:18.079  1032  1396 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
09-12 14:43:18.079  1032  1396 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
09-12 14:43:18.080  1032  1396 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
09-12 14:43:18.080  1032  1396 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
,09-12 14:43:18.081  1032  1396 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
09-12 14:43:18.081  1032  1396 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-12 14:43:18.082  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-12 14:43:18.082  1032  1032 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
09-12 14:43:18.083  1032  1396 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=197682  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-12 14:43:18.083  1032  1396 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=197683  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-12 14:43:18.084  1032  1396 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=197684  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-12 14:43:18.085  1032  1396 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:151292] from screen [on:0 period:510415557] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
09-12 14:43:18.086  1032  1396 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:510415558] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
09-12 14:43:18.086  1032  1396 D WifiNative-wlan0: doString: [SIGNAL_POLL]
09-12 14:43:18.089  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 14:43:18.090  1032  1466 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
09-12 14:43:18.090  1032  1396 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 14:43:18.091  1032  1396 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 14:43:18.091  1032  1396 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 14:43:18.091  1032  1396 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 14:43:18.091  1032  1396 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 14:43:18.092  1032  1396 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 14:43:18.092  1032  1466 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-12 14:43:18.092  1032  1396 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=122,0,0
09-12 14:43:18.092  1032  1396 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=122,0,0
09-12 14:43:18.092  1032  1396 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
09-12 14:43:18.093  6985  6985 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
09-12 14:43:18.093  1032  1396 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
09-12 14:43:18.093  1032  1396 D WifiNative-wlan0: doBoolean: SET ps 0
09-12 14:43:18.094  1032  1396 D WifiNative-wlan0: SET ps 0: returned true
09-12 14:43:18.094  1032  1396 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
09-12 14:43:18.094  6985  6985 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
09-12 14:43:18.094  1032  1396 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
09-12 14:43:18.094  1032  1396 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
09-12 14:43:18.094  1032  1396 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-12 14:43:18.094  1032  1396 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-12 14:43:18.094  1032  1387 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@20307042 target=com.android.internal.util.StateMachine$SmHandler }
09-12 14:43:18.094  1032  1387 D LGWifiP2pService: P2pEnabledState{ ,when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@20307042 target=com.android.internal.util.StateMachine$SmHandler }
09-12 14:43:18.095  1032  7087 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
09-12 14:43:18.095  1032  7087 D DhcpStateMachine: DHCP Start wake lock is acquired.
09-12 14:43:18.095   306   892 D CommandListener: Setting iface cfg
09-12 14:43:18.095   306   892 D CommandListener: Trying to bring up wlan0
09-12 14:43:18.096  1032  1396 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
09-12 14:43:18.096  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-12 14:43:18.096  1032  1032 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-12 14:43:18.097  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
,09-12 14:43:18.097  1032  1032 D WifiServerServiceExt: setSupplicantStateCOMPLETED
,09-12 14:43:18.098  1032  1396 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 14:43:18.098  1032  1396 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 14:43:18.099  1032  1396 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 14:43:18.099  1032  1396 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,09-12 14:43:18.100  1032  1396 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 14:43:18.100  1032  1396 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 14:43:18.101  1032  1466 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-12 14:43:18.101  1032  1396 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-12 14:43:18.102  1032  1396 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
,09-12 14:43:18.102  1032  1387 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-12 14:43:18.102  1032  1387 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-12 14:43:18.102  1032  1396 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-12 14:43:18.102  6985  6985 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
,09-12 14:43:18.103  1032  1396 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-12 14:43:18.103  1032  1396 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
09-12 14:43:18.103  6985  6985 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
09-12 14:43:18.103  1032  1396 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
09-12 14:43:18.103  1032  1396 D WifiNative-wlan0: doBoolean: SET ps 1
,09-12 14:43:18.110  7067  7067 D WeatherApplication: removeAccount
09-12 14:43:18.111  7067  7067 D WeatherApplication: Account.length = 0
09-12 14:43:18.111  7067  7067 E WeatherApplication: OPERATOR:OPEN
,09-12 14:43:18.115  7067  7067 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:43:18
09-12 14:43:18.118  7067  7067 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-12 14:43:18.118  7067  7067 D Weather.Utils: 2 : All the weather widget is gone.
09-12 14:43:18.119  1032  1396 D WifiNative-wlan0: SET ps 1: returned true
09-12 14:43:18.120  1032  1466 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-12 14:43:18.120  7067  7067 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-12 14:43:18.120  1032  1396 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-12 14:43:18.120  1032  1396 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-12 14:43:18.120  1032  1396 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-12 14:43:18.121  1032  1466 D ConnectivityService: ignoring duplicate network state non-change
09-12 14:43:18.122  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 14:43:18.123  1599  1599 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-12 14:43:18.123  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 14:43:18.124  7067  7067 D WeatherAncestor: connectivity changed - connection : true
,09-12 14:43:18.125  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 14:43:18.125  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 14:43:18.125  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-12 14:43:18.126  7067  7067 D WeatherService: 2 : isServiceAlived():false forecastCache:null
09-12 14:43:18.127  1032  1466 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-12 14:43:18.128  1032  1466 D ConnectivityService: Adding iface wlan0 to network 101
09-12 14:43:18.131  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 14:43:18.131  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 14:43:18.131  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,09-12 14:43:18.140  1032  1396 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-12 14:43:18.144  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 14:43:18.144  1599  1599 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-12 14:43:18.145  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 14:43:18.145  1032  1032 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-12 14:43:18.146  7067  7067 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-12 14:43:18.147  7067  7067 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-12 14:43:18.147  7067  7067 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
09-12 14:43:18.149  1032  1466 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-12 14:43:18.149  1032  1466 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
09-12 14:43:18.150  1032  1466 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
09-12 14:43:18.151   306   892 E Netd    : netlink response contains error (File exists)
09-12 14:43:18.151  1032  1466 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-12 14:43:18.152  1032  1466 D ConnectivityService: addLocalRoutetoDefaultNetwork
09-12 14:43:18.152  1032  1466 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
09-12 14:43:18.152  1032  1466 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
09-12 14:43:18.152  1941  1941 V WfdStateTracker: handleWifiStateChangedEvent: 1
,09-12 14:43:18.159  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 14:43:18.159  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 14:43:18.159  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-12 14:43:18.159  1032  1032 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-12 14:43:18.162  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 14:43:18.162  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 14:43:18.162  1032  1466 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-12 14:43:18.162  1032  1466 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-12 14:43:18.162  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-12 14:43:18.162  1032  1466 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-12 14:43:18.162  1032  1466 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
09-12 14:43:18.162  1032  1466 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-12 14:43:18.162  1032  7086 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-12 14:43:18.162  1032  1466 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-12 14:43:18.162  1032  7086 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
09-12 14:43:18.162  1032  1466 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-12 14:43:18.162  1032  1466 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 14:43:18.162  1032  7086 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-12 14:43:18.162  1032  1466 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
09-12 14:43:18.162  1032  1466 D ConnectivityService: currentScore = 0, newScore = 20
09-12 14:43:18.162  1032  1466 D ConnectivityService:    accepting network in place of null
09-12 14:43:18.162  1032  7086 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-12 14:43:18.162  1032  1466 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 14:43:18.163  1852  1852 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 14:43:18.163  1032  1396 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 14:43:18.163  1852  1852 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-12 14:43:18.163  1032  1396 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBa,ndwidth>=1048576Kbps]
09-12 14:43:18.163  1032  1466 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-12 14:43:18.163  1032  1466 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-12 14:43:18.164  1032  1466 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-12 14:43:18.164  1032  1466 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-12 14:43:18.164  1032  1466 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
09-12 14:43:18.164  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 14:43:18.164  1599  1599 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-12 14:43:18.164  1032  1466 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
09-12 14:43:18.164   306  7092 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
09-12 14:43:18.164  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 14:43:18.165  1032  1466 D ConnectivityService: validation of new default Network = false
09-12 14:43:18.165  1032  1466 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
09-12 14:43:18.165  1032  1466 D DSQN    : enableDataServiceNotify 
09-12 14:43:18.165  1032  1466 D DSQN    : start dsqn bin
09-12 14:43:18.169  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-12 14:43:18.169  1599  1599 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-12 14:43:18.169  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 14:43:18.169  1032  1466 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
09-12 14:43:18.169  1032  1466 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 14:43:18.169  1032  1466 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-12 14:43:18.170  1032  1466 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-12 14:43:18.161  7093  7093 W dsqn    : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-12 14:43:18.161  7093  7093 W dsqn    : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-12 14:43:18.174  1032  1032 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
09-12 14:43:18.174  1032  1032 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-12 14:43:18.174  1032  1032 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-12 14:43:18.174  1032  1032 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-12 14:43:18.178  1599  2069 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-12 14:43:18.186  7067  7067 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-12 14:43:18.186  7067  7067 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:43:18
09-12 14:43:18.186  7093  7093 E DSQN    : DSQN ssw
,09-12 14:43:18.219  1032  1774 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7098 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-12 14:43:18.219  1032  1774 I ActivityManager: Killing 2120:com.lge.music/u0a34 (adj 15): empty #17
,09-12 14:43:18.220   306  7092 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
09-12 14:43:18.234   311  2165 V AudioFlinger: 2120 died, releasing its sessions
09-12 14:43:18.234   311  2165 V AudioFlinger:  pid 1852 @ 0
09-12 14:43:18.234   311  2165 V AudioFlinger:  pid 3309 @ 1
09-12 14:43:18.234   311  2165 V AudioFlinger:  pid 3309 @ 2
,09-12 14:43:18.252   306  7092 D libc-netbsd: res_queryN name = clients3.google.com succeed
,09-12 14:43:18.258  1816  7097 I CheckinService: active receiver: enabled
,09-12 14:43:18.267  1816  7097 I CheckinService: Preparing to send checkin request
09-12 14:43:18.267  1816  7097 I EventLogService: Accumulating logs since 1473684057523
09-12 14:43:18.271  1032  1903 W libprocessgroup: failed to open /acct/uid_10034/pid_2120/cgroup.procs: No such file or directory
09-12 14:43:18.276  1032  1386 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
09-12 14:43:18.277   306   891 D LGDataListener: argv[0]=dsqncommand
09-12 14:43:18.277   306   891 D LGDataListener: argv[1]=wlan0
09-12 14:43:18.277   306   891 D LGDataListener: argv[2]=1
09-12 14:43:18.277   306   891 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
09-12 14:43:18.277  1032  1092 D DSQN    : DSQM DsqnNotification wlan0  1
09-12 14:43:18.277  1032  1092 D DSQN    : start to monitor internet connection
09-12 14:43:18.284  1032  1387 D LGWifiP2pService: InactiveState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-12 14:43:18.284  1032  1387 D LGWifiP2pService: P2pEnabledState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-12 14:43:18.284  1032  1387 D LGWifiP2pService: DefaultState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,09-12 14:43:18.296  1032  1396 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-12 14:43:18.296  1032  1396 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-12 14:43:18.297  1032  1396 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
,09-12 14:43:18.297  1032  1396 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-12 14:43:18.297  1032  1396 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-12 14:43:18.298  1032  7087 D DhcpStateMachine: DHCPV4 request on wlan0
09-12 14:43:18.298  1032  7087 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
09-12 14:43:18.298  1032  7087 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
09-12 14:43:18.299  1032  1396 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
09-12 14:43:18.291  7119  7119 W dhcpcd  : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-12 14:43:18.291  7119  7119 W dhcpcd  : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-12 14:43:18.304  1599  1599 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-12 14:43:18.305  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 14:43:18.305  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 14:43:18.306  1032  7086 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 12 Sep 2016 12:43:18 GMT], X-Android-Received-Millis=[1473684198306], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473684198277]}
09-12 14:43:18.307  1032  7086 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-12 14:43:18.307  1032  7086 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
09-12 14:43:18.307  1032  1466 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
09-12 14:43:18.307  1032  1466 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
09-12 14:43:18.307  1032  1466 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-12 14:43:18.307  1032  1466 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-12 14:43:18.307  1032  1466 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-12 14:43:18.307  1032  1466 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
09-12 14:43:18.307  1032  1466 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
09-12 14:43:18.307  1032  1466 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 14:43:18.307  1032  1466 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-12 14:43:18.308  1032  1466 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-12 14:43:18.309  1032  1466 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 14:43:18.309  1599  2069 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-12 14:43:18.309  1032  1466 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-12 14:43:18.309  1032  1396 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 14:43:18.309  1032  1396 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps],
09-12 14:43:18.309  1852  1852 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 14:43:18.309  1852  1852 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,09-12 14:43:18.310  7119  7119 I dhcpcd  : version 5.5.6 starting
09-12 14:43:18.313  7119  7119 E dhcpcd  : get_duid: m
09-12 14:43:18.313  7119  7119 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
09-12 14:43:18.313  7119  7119 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
09-12 14:43:18.316  1816  7097 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
09-12 14:43:18.336  1599  1599 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-12 14:43:18.336  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 14:43:18.337  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-12 14:43:18.356  7119  7119 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
,09-12 14:43:18.356  7119  7119 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-12 14:43:18.356  7119  7119 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-12 14:43:18.357  7119  7119 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
09-12 14:43:18.357  7119  7119 D dhcpcd  : wlan0: sending REQUEST (xid 0xcec546cb), next in 4.22 seconds
,09-12 14:43:18.358  1032  1090 W ProcessCpuTracker: Skipping unknown process pid 7120
,09-12 14:43:18.374   279   441 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,09-12 14:43:18.374   279   441 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-12 14:43:18.374   279   441 W Vold    : Returning OperationFailed - no handler for errno 0
09-12 14:43:18.375  7098  7127 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
09-12 14:43:18.376   279   441 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-12 14:43:18.376   279   441 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-12 14:43:18.376   279   441 W Vold    : Returning OperationFailed - no handler for errno 0
09-12 14:43:18.376  7098  7127 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
09-12 14:43:18.383   279   441 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-12 14:43:18.383   279   441 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-12 14:43:18.383   279   441 W Vold    : Returning OperationFailed - no handler for errno 0
09-12 14:43:18.384  7098  7129 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,09-12 14:43:18.386   279   441 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-12 14:43:18.386   279   441 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-12 14:43:18.386   279   441 W Vold    : Returning OperationFailed - no handler for errno 0
09-12 14:43:18.386  7119  7119 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
09-12 14:43:18.386  7098  7129 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
09-12 14:43:18.407  7119  7119 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
09-12 14:43:18.407  7119  7119 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
09-12 14:43:18.407  7119  7119 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
09-12 14:43:18.408  7119  7119 D dhcpcd  : wlan0: adding default route via 192.168.1.1
09-12 14:43:18.408  7119  7119 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-12 14:43:18.408  7119  7119 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-12 14:43:18.408  7119  7119 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-12 14:43:18.408  7119  7119 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,09-12 14:43:18.439  1032  1774 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7137 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,09-12 14:43:18.467  7137  7137 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,09-12 14:43:18.468  7137  7137 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
09-12 14:43:18.486  7137  7137 I MultiDex: VM with version 2.1.0 has multidex support
,09-12 14:43:18.486  7137  7137 I MultiDex: install
,09-12 14:43:18.486  7137  7137 I MultiDex: VM has multidex support, MultiDex support library is disabled.
09-12 14:43:18.493  7137  7137 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
09-12 14:43:18.605  7098  7098 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,09-12 14:43:18.612  7098  7098 I LibraryLoader: Loading: webviewchromium
09-12 14:43:18.614  7098  7098 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 8223-8227)
09-12 14:43:18.614  7098  7098 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-12 14:43:18.625  7098  7098 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1790a1f4}
09-12 14:43:18.626  7098  7098 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-12 14:43:18.627  7098  7098 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
09-12 14:43:18.636  7098  7098 I BrowserStartupController: Initializing chromium process, renderers=0
,09-12 14:43:18.636  7098  7098 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-12 14:43:18.649  7098  7098 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
09-12 14:43:18.649  7098  7098 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
09-12 14:43:18.649  7098  7098 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
,09-12 14:43:18.662   311  1395 V AudioPolicyService: registerClient() client 0xb558a4c0, uid 10093
09-12 14:43:18.668  7098  7098 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-12 14:43:18.668  7098  7098 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-12 14:43:18.668  7098  7098 I Adreno-EGL: Build Date: 12/12/14 금
09-12 14:43:18.668  7098  7098 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-12 14:43:18.668  7098  7098 I Adreno-EGL: Remote Branch: 
09-12 14:43:18.668  7098  7098 I Adreno-EGL: Local Patches: 
09-12 14:43:18.668  7098  7098 I Adreno-EGL: Reconstruct Branch: 
,09-12 14:43:18.670  7098  7190 W AudioManagerAndroid: Requires BLUETOOTH permission
09-12 14:43:18.703  1032  7087 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,09-12 14:43:18.706  1032  7087 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
,09-12 14:43:18.706  1032  7087 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-12 14:43:18.707  1032  7087 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
09-12 14:43:18.707  1032  7087 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
09-12 14:43:18.707  1032  7087 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-12 14:43:18.707  1032  7087 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
09-12 14:43:18.707  1032  7087 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
09-12 14:43:18.708  1032  7087 D DhcpStateMachine: RunningState
09-12 14:43:18.737  7098  7098 I NSApplication: Starting up...
,09-12 14:43:18.784  1032  1903 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7203 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
09-12 14:43:18.785  1032  2031 I ActivityManager: Killing 6090:com.android.vending/u0a44 (adj 15): empty #17
,09-12 14:43:18.829  1032  1966 W libprocessgroup: failed to open /acct/uid_10044/pid_6090/cgroup.procs: No such file or directory
,09-12 14:43:18.867  7203  7203 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-12 14:43:18.950  7220  7220 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
09-12 14:43:19.025  7220  7220 I dex2oat : dex2oat took 75.358ms (threads: 4)
,09-12 14:43:19.032  1032  1966 I art     : Explicit concurrent mark sweep GC freed 100618(4MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/64MB, paused 1.380ms total 91.333ms
09-12 14:43:19.039  7137  7154 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-12 14:43:19.039  7137  7154 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-12 14:43:19.039  7137  7154 I Adreno-EGL: Build Date: 12/12/14 금
09-12 14:43:19.039  7137  7154 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-12 14:43:19.039  7137  7154 I Adreno-EGL: Remote Branch: 
09-12 14:43:19.039  7137  7154 I Adreno-EGL: Local Patches: 
09-12 14:43:19.039  7137  7154 I Adreno-EGL: Reconstruct Branch: 
,09-12 14:43:19.124  7137  7154 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-12 14:43:19.124  7137  7154 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-12 14:43:19.124  7137  7154 I Adreno-EGL: Build Date: 12/12/14 금
09-12 14:43:19.124  7137  7154 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-12 14:43:19.124  7137  7154 I Adreno-EGL: Remote Branch: 
09-12 14:43:19.124  7137  7154 I Adreno-EGL: Local Patches: 
09-12 14:43:19.124  7137  7154 I Adreno-EGL: Reconstruct Branch: 
,09-12 14:43:19.159  6356  6356 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,09-12 14:43:19.165  6356  6765 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-12 14:43:19.170  1032  1466 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
09-12 14:43:19.187  2208  2208 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-12 14:43:19.191  7137  7154 D LgDataFeature: LgDataFeature() Constructor: none
09-12 14:43:19.191  7137  7154 D LgDataFeature: LgDataFeature() Constructor Done, null
09-12 14:43:19.195  1032  1932 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10005
09-12 14:43:19.195  1032  7086 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-12 14:43:19.195  1032  7086 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-12 14:43:19.195  1032  7086 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
09-12 14:43:19.195  1032  7086 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-12 14:43:19.195  1032  7086 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-12 14:43:19.199  6934  6934 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-12 14:43:19.199  6934  6934 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-12 14:43:19.199  6934  6934 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-12 14:43:19.199  6934  6934 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-12 14:43:19.204  6934  6934 I AppUp4:CustModeStarterReceiver: onReceive
,09-12 14:43:19.207   306  7236 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-12 14:43:19.207  6934  6934 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@344495f5
09-12 14:43:19.207  6934  6934 D AppUp4:CustFacade: isCustomizationCompleted : false
09-12 14:43:19.207  6934  6934 D AppUp4:CustFacade: isPhone : true
09-12 14:43:19.207   306  7236 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
09-12 14:43:19.208  6934  6934 D AppUp4:CustModeStarterReceiver: begin check event
09-12 14:43:19.208  6934  6934 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
,09-12 14:43:19.213  4334  4334 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-12 14:43:19.213  4334  4334 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-12 14:43:19.215  4334  4334 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-12 14:43:19.219  4334  4334 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-12 14:43:19.220  1032  7086 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 12 Sep 2016 12:43:19 GMT], X-Android-Received-Millis=[1473684199219], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473684199196]}
09-12 14:43:19.220  1032  7086 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-12 14:43:19.220  1032  7086 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
,09-12 14:43:19.221  1032  1466 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
09-12 14:43:19.221  1032  1466 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
09-12 14:43:19.221  1032  1466 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-12 14:43:19.221  1032  1466 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-12 14:43:19.221  1032  1466 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-12 14:43:19.221  1032  1466 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
09-12 14:43:19.221  1032  1466 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
09-12 14:43:19.221  1032  1466 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 14:43:19.221  1032  1466 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-12 14:43:19.222  1032  1466 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-12 14:43:19.223  1599  2069 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-12 14:43:19.226  3416  3416 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
09-12 14:43:19.230  3416  3416 V DownloadManager: DownloadService onCreate
09-12 14:43:19.232  3416  7241 I DownloadManager: in removeSpuriousFiles
,09-12 14:43:19.232  4334  7239 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-12 14:43:19.233  3416  7241 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
09-12 14:43:19.235  4334  7240 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-12 14:43:19.235  4334  7240 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-12 14:43:19.236  6960  6960 D eas_req : ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
09-12 14:43:19.238  4334  7239 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
09-12 14:43:19.238   306  7236 D libc-netbsd: res_queryN name = mtalk.google.com succeed
09-12 14:43:19.241  3416  7241 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@31a56f89 on behalf of 3416
09-12 14:43:19.243  4334  7239 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
,09-12 14:43:19.245  4334  4334 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
09-12 14:43:19.246  4334  4334 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
09-12 14:43:19.246  4334  4334 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
09-12 14:43:19.247  3416  3416 V DownloadManager: DownloadService onStartCommand
09-12 14:43:19.249  3416  7241 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
09-12 14:43:19.249  3416  7241 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
09-12 14:43:19.249  4334  4334 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
09-12 14:43:19.249  3416  7241 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
09-12 14:43:19.249  3416  7241 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
09-12 14:43:19.249  3416  7241 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
09-12 14:43:19.249  3416  7241 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
09-12 14:43:19.249  3416  7241 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk,
09-12 14:43:19.249  3416  7241 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
09-12 14:43:19.249  3416  7241 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
09-12 14:43:19.249  3416  7241 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
09-12 14:43:19.251  3416  7241 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
09-12 14:43:19.251  3416  7242 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
09-12 14:43:19.252  3416  7242 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@34c99fbc on behalf of 3416
09-12 14:43:19.252  3416  7241 I DownloadManager: in trimDatabase
09-12 14:43:19.254  3416  7242 V DownloadManager: processing inserted download 1
09-12 14:43:19.256  4334  4334 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
,09-12 14:43:19.258  3416  7241 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
09-12 14:43:19.259  3416  7241 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@2fec7b45 on behalf of 3416
09-12 14:43:19.262  3309  3309 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-12 14:43:19.262  3309  3309 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-12 14:43:19.262  3309  3309 I LgeMiscReceiver: networkInfo.isConnected() = false
09-12 14:43:19.262  1032  2031 D WifiServiceImplEx: setWifiEnabled: false pid=6669, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-12 14:43:19.263  1032  2031 D WifiService: setWifiEnabled: false pid=6669, uid=10118
09-12 14:43:19.263  1032  2031 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-12 14:43:19.263  3416  7242 V DownloadManager: processing inserted download 4
09-12 14:43:19.264  3416  7242 V DownloadManager: processing inserted download 7
09-12 14:43:19.265  3416  7242 V DownloadManager: processing inserted download 8
09-12 14:43:19.266  6996  6996 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-12 14:43:19.266  6996  6996 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-12 14:43:19.268  3416  7242 V DownloadManager: processing inserted download 9
,09-12 14:43:19.273  1032  1396 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
09-12 14:43:19.273  1032  1396 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
09-12 14:43:19.273  1032  1032 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-12 14:43:19.273  1032  1396 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
09-12 14:43:19.274  1032  1032 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-12 14:43:19.274  1032  1032 D Ulp_jni : JNI:system_update. Event-4
09-12 14:43:19.274  1032  1396 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
09-12 14:43:19.274  3416  7242 V DownloadManager: processing inserted download 10
09-12 14:43:19.274  1032  1396 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
09-12 14:43:19.274  1032  1396 E WifiStateMachine: WifiStateMachine: Leaving Connected state
09-12 14:43:19.274  1032  1396 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-12 14:43:19.274  1032  1396 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-12 14:43:19.275  1032  1396 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-12 14:43:19.275  1032  1396 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-12 14:43:19.275  3416  7242 V DownloadManager: processing inserted download 11
09-12 14:43:19.277  6960  7245 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 14:43:19.278  3416  7242 V DownloadManager: processing inserted download 12
09-12 14:43:19.279  1032  1396 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-12 14:43:19.279  1032  1396 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-12 14:43:19.279  1032  1387 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-12 14:43:19.279  6985  6985 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-12 14:43:19.280  1032  1387 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,09-12 14:43:19.280  1032  1396 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-12 14:43:19.280  1032  1396 D WifiNative-wlan0: doBoolean: SET ps 1
09-12 14:43:19.280  3416  7242 V DownloadManager: processing inserted download 13
09-12 14:43:19.280  1032  1396 D WifiNative-wlan0: SET ps 1: returned true
09-12 14:43:19.280  1032  7087 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-12 14:43:19.280   306   892 D CommandListener: Clearing all IP addresses on wlan0
09-12 14:43:19.293  3416  7242 V DownloadManager: processing inserted download 14
09-12 14:43:19.294  3416  7242 V DownloadManager: processing inserted download 16
09-12 14:43:19.300  3416  3416 V DownloadManager: DownloadService onDestroy
,09-12 14:43:19.309  1032  1396 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 14:43:19.309  1032  1396 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 14:43:19.309  1032  1396 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 14:43:19.310  1032  1396 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 14:43:19.310  1032  1396 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 14:43:19.310  1032  1396 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 14:43:19.310  1032  1466 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-12 14:43:19.310  1032  1466 D ConnectivityService: ignoring duplicate network state non-change
09-12 14:43:19.310  1032  1466 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
09-12 14:43:19.311  1032  1032 D WifiHS20: hidePasspointNotification off =false
,09-12 14:43:19.312  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 14:43:19.313  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 14:43:19.313  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-12 14:43:19.313  1032  1032 D WifiHS20: hidePasspointNotification off =false
09-12 14:43:19.314  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 14:43:19.314  1032  1387 D LGWifiP2pService: InactiveState{ when=-5ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-12 14:43:19.314  1032  1387 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-12 14:43:19.314  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 14:43:19.314  1032  1387 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@29a6779b
09-12 14:43:19.314  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-12 14:43:19.314  1032  1032 D WifiScanningService: SCAN_AVAILABLE : 1
09-12 14:43:19.314  1032  1032 D RttService: SCAN_AVAILABLE : 1
09-12 14:43:19.314  1032  1387 D LGWifiP2pService: P2pDisablingState
09-12 14:43:19.314  1032  1387 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
09-12 14:43:19.314  1032  1387 D LGWifiP2pService: p2p socket connection lost
09-12 14:43:19.314  1032  1387 D LGWifiP2pService: P2pDisabledState
09-12 14:43:19.314  1032  1553 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-12 14:43:19.314  1032  1554 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-12 14:43:19.316  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 14:43:19.316  1599  1599 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-12 14:43:19.316  1941  1941 V WfdStateTracker: handleWifiStateChangedEvent: 0
09-12 14:43:19.317  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 14:43:19.321  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-12 14:43:19.321  1941  1941 D WfdsService: WifiP2pState is changed : false
09-12 14:43:19.321  1941  2410 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
09-12 14:43:19.321  1941  2410 D WfdsService: Set the WFDS Monitor: false
09-12 14:43:19.322  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 14:43:19.322  1599  1599 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-12 14:43:19.322  1032  1396 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-12 14:43:19.322  1941  2410 D WfdsMonitor: WFDS Monitor is stopped
09-12 14:43:19.322  1941  2410 D WfdsService: STATE : WfdsDisabledState - enter
09-12 14:43:19.322  1941  7013 D CtrlSupplicant: Received on exit socket, terminate
09-12 14:43:19.322  1941  7013 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
09-12 14:43:19.322  1941  7013 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection c,losed]
09-12 14:43:19.322  1032  1396 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
09-12 14:43:19.322  1941  7013 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
09-12 14:43:19.322  1032  1387 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-12 14:43:19.322  1032  1387 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-12 14:43:19.322  1941  2411 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
09-12 14:43:19.323  1032  1396 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-12 14:43:19.323  6985  6985 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-12 14:43:19.323  1941  2410 W WfdsService: DefaultState - msg [9445378] is not handled
,09-12 14:43:19.323  1032  1396 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-12 14:43:19.323  1032  1396 D WifiNative-wlan0: doBoolean: SET ps 1
09-12 14:43:19.325  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 14:43:19.327  1032  1396 D WifiNative-wlan0: SET ps 1: returned true
09-12 14:43:19.335  6850  7249 V FormManager: Network unavailable.
,09-12 14:43:19.339  6850  7249 V FormManager: Network unavailable.
09-12 14:43:19.340  6850  7249 V FormManager: Network unavailable.
09-12 14:43:19.343  7067  7067 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:43:19
09-12 14:43:19.345  7067  7067 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-12 14:43:19.345  7067  7067 D Weather.Utils: 2 : All the weather widget is gone.
09-12 14:43:19.346  7067  7067 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-12 14:43:19.346  7067  7067 D WeatherAncestor: connectivity changed - connection : true
09-12 14:43:19.346  7067  7067 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@153cf9fb
,09-12 14:43:19.347  7067  7067 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-12 14:43:19.347  7067  7067 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-12 14:43:19.347  7067  7067 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-12 14:43:19.347  7067  7067 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-12 14:43:19.347  7067  7067 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:43:19
,09-12 14:43:19.349   306   892 D CommandListener: Clearing all IP addresses on wlan0
09-12 14:43:19.349  1032  1466 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
09-12 14:43:19.349  1032  1466 D DSQN    : disableDataServiceNotify
09-12 14:43:19.349  1032  1466 D DSQN    : stop dsqn bin
09-12 14:43:19.353  1032  1466 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
09-12 14:43:19.353  1032  1466 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 14:43:19.353  1032  1466 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-12 14:43:19.354  1032  1466 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
09-12 14:43:19.354  1032  1466 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
09-12 14:43:19.354  1032  1466 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
09-12 14:43:19.354  1032  1466 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-12 14:43:19.354  1032  1466 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-12 14:43:19.354  1599  2069 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-12 14:43:19.354  1032  7086 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-12 14:43:19.354  1032  7086 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-12 14:43:19.355  1032  7086 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-12 14:43:19.358  1032  1466 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-12 14:43:19.358  1032  1466 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-12 14:43:19.358  1032  1396 D WifiNative-p2p0: doBoolean: TERMINATE
09-12 14:43:19.359  1032  1396 D WifiNative-p2p0: TERMINATE: returned true
09-12 14:43:19.359  1032  1396 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-12 14:43:19.359  1032  1396 E WifiStateMachine: useWiFiOffloading() : false
09-12 14:43:19.359  1032  1396 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,09-12 14:43:19.360  1032  1386 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-12 14:43:19.361  1032  1032 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-12 14:43:19.361  1032  1032 D WifiHS20: hidePasspointNotification off =false
09-12 14:43:19.361  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 14:43:19.361  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 14:43:19.361  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-12 14:43:19.361  1032  1032 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-12 14:43:19.361  1032  1032 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-12 14:43:19.361  1032  1032 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-12 14:43:19.363  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
09-12 14:43:19.365  1032  1032 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
09-12 14:43:19.365  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-12 14:43:19.365  1032  1032 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
09-12 14:43:19.366  1032  1466 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-12 14:43:19.366  1032  1386 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-12 14:43:19.366  1032  1466 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 14:43:19.366  1032  1466 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 14:43:19.366  1032  1032 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-12 14:43:19.366  1032  1466 D NetworkManagementService: Removing idletimer
09-12 14:43:19.366  1032  1032 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-12 14:43:19.366  1032  1466 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 14:43:19.366  1032  1032 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-12 14:43:19.366  1032  1032 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-12 14:43:19.367  1032  1396 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 14:43:19.367  1852  1852 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 14:43:19.367  1032  1396 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-12 14:43:19.367  1852  1852 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-12 14:43:19.368  6669  6669 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 14:43:19.368  6669  6669 V io.jxcore.nod,e.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 14:43:19.368  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 14:43:19.368  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 14:43:19.368  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 14:43:19.368  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 14:43:19.368  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 14:43:19.368  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 14:43:19.368  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 14:43:19.368  6669  6669 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 14:43:19.368  6669  6669 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 14:43:19.368  6669  6669 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 14:43:19.368  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 14:43:19.368  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 14:43:19.368  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 14:43:19.368  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 14:43:19.368  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 14:43:19.368  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 14:43:19.368  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 14:43:19.368  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 14:43:19.368  6669  6669 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 14:43:19.368  6669  6669 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 14:43:19.369  7137  7154 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-12 14:43:19.369  7137  7154 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-12 14:43:19.369  7137  7154 I Adreno-EGL: Build Date: 12/12/14 금
09-12 14:43:19.369  7137  7154 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-12 14:43:19.369  7137  7154 I Adreno-EGL: Remote Branch: 
09-12 14:43:19.369  7137  7154 I Adreno-EGL: Local Patches: 
09-12 14:43:19.369  7137  7154 I Adreno-EGL: Reconstruct Branch: 
,09-12 14:43:19.390  1599  1599 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-12 14:43:19.392  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 14:43:19.392  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 14:43:19.393  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-12 14:43:19.393  1599  1599 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-12 14:43:19.394  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 14:43:19.394  1032  1032 D PowerManagerServiceEx: releaseWakeLockInternal: lock=55543020 [*alarm*], flags=0x0
,09-12 14:43:19.396  6738  6738 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-12 14:43:19.396  6738  6738 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-12 14:43:19.396  6738  6738 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-12 14:43:19.396  6738  6738 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-12 14:43:19.397  6738  6738 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-12 14:43:19.398  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 14:43:19.402  6738  6738 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-12 14:43:19.402  6738  6738 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
09-12 14:43:19.402  6738  6738 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-12 14:43:19.402  6738  6738 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-12 14:43:19.402  6738  6738 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-12 14:43:19.402  6738  6738 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
09-12 14:43:19.402  6738  6738 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-12 14:43:19.409  6766  6766 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-12 14:43:19.414  6738  6738 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-12 14:43:19.421  6850  7261 V FormManager: Network unavailable.
09-12 14:43:19.421  6850  7260 W FormManager: Network not available. Please check & try again.
,09-12 14:43:19.423  6738  6738 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-12 14:43:19.428  6985  6985 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,09-12 14:43:19.428  6985  6985 I wpa_supplicant: monitor socket send errors count : 1
09-12 14:43:19.428  6985  6985 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1941-4\x00 that cannot receive messages
09-12 14:43:19.429  1032  6992 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
09-12 14:43:19.429  1032  6992 D WifiMonitor: Dropping event because (p2p0) is stopped
09-12 14:43:19.430  1599  1599 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-12 14:43:19.431  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 14:43:19.432  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-12 14:43:19.435  6850  7261 V FormManager: Network unavailable.
09-12 14:43:19.437  6766  6766 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-12 14:43:19.439  6738  6738 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-12 14:43:19.444  6850  7263 W FormManager: Network not available. Please check & try again.
09-12 14:43:19.444  6738  6738 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-12 14:43:19.447  6850  7264 V FormManager: Network unavailable.
,09-12 14:43:19.451  6850  7264 V FormManager: Network unavailable.
09-12 14:43:19.456  4334  4334 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-12 14:43:19.457  4334  4334 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-12 14:43:19.457  4334  4334 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-12 14:43:19.459  4334  4334 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-12 14:43:19.459   306  7266 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,09-12 14:43:19.459  1032  1092 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
09-12 14:43:19.460  1816  7097 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
09-12 14:43:19.464  6985  6985 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-12 14:43:19.464  1032  6992 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
09-12 14:43:19.464  1032  6992 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-12 14:43:19.464  1032  6992 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-12 14:43:19.464  1032  6992 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
09-12 14:43:19.464  6985  6985 W wpa_supplicant: USIM:  scard_deinit function
09-12 14:43:19.465  1032  1396 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=199064
09-12 14:43:19.465  1032  6992 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-12 14:43:19.465  1032  6992 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-12 14:43:19.465  1032  1396 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=199065
09-12 14:43:19.465  1032  1396 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=199065  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-12 14:43:19.466  1032  1396 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=199065  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-12 14:43:19.466  1032  1094 D Tethering: InitialState.processMessage what=4
09-12 14:43:19.468  4334  7267 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-12 14:43:19.469  4334  7268 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-12 14:43:19.469  4334  7268 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-12 14:43:19.491  1032  7087 D DhcpStateMachine: StoppedState
09-12 14:43:19.491  1032  7087 D DhcpStateMachine: StoppedState{ when=-163ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,09-12 14:43:19.493  1032  1932 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7269 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
09-12 14:43:19.495  1032  1094 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-12 14:43:19.496  1032  1396 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
09-12 14:43:19.497  1032  1396 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-12 14:43:19.497  1816  7097 I CheckinService: active receiver: disabled
09-12 14:43:19.497  1032  1396 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
09-12 14:43:19.498  1032  1396 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
,09-12 14:43:19.509   335   335 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 356us total 15.287ms
09-12 14:43:19.524   335   335 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 289us total 15.121ms
,09-12 14:43:19.539   335   335 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 286us total 13.538ms
,09-12 14:43:19.555  7269  7269 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-12 14:43:19.555  7269  7269 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,09-12 14:43:19.558  6985  6985 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-12 14:43:19.558  1032  6992 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
09-12 14:43:19.558  1032  6992 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-TERMINATING 
09-12 14:43:19.558  1032  6992 D WifiMonitor: Disconnecting from the supplicant, no more events
09-12 14:43:19.558  1032  1396 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 44 0
09-12 14:43:19.560  7269  7269 V [BNRBootReceiver]: Boot Receiver Return
09-12 14:43:19.562  7269  7269 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,09-12 14:43:19.562  6356  6356 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-12 14:43:19.566  6738  6738 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-12 14:43:19.570  6738  6738 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-12 14:43:19.576  6811  6811 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-12 14:43:19.577  6811  6811 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-12 14:43:19.578  6811  6811 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-12 14:43:19.580  6738  6738 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,09-12 14:43:19.583  6738  6738 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
09-12 14:43:19.585  6356  6356 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-12 14:43:19.591  6738  6738 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-12 14:43:19.596  6738  6738 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-12 14:43:19.600  6811  6811 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-12 14:43:19.601  6811  6811 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-12 14:43:19.602  6811  6811 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-12 14:43:19.605  6356  6356 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-12 14:43:19.614  6738  6738 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-12 14:43:19.620  6738  6738 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-12 14:43:19.627  6811  6811 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-12 14:43:19.629  6811  6811 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-12 14:43:19.630  6811  6811 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-12 14:43:19.635  6356  6356 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-12 14:43:19.647  6738  6738 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-12 14:43:19.660  6738  6738 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-12 14:43:19.661  1032  1396 D WifiOffDelayIfNotUsed: stopMonitoring
09-12 14:43:19.661  1941  1941 D WfdsService: Supplicant Connection state is changed : false
09-12 14:43:19.661  1032  1396 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-12 14:43:19.661  1032  1396 E WifiStateMachine: useWiFiOffloading() : false
09-12 14:43:19.661  1032  1396 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-12 14:43:19.661  1941  2410 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
09-12 14:43:19.661  1941  2410 D WfdsService: Set the WFDS Monitor: false
09-12 14:43:19.661  1941  2410 D WfdsMonitor: WFDS Monitor is stopped
09-12 14:43:19.664  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 14:43:19.664  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-12 14:43:19.667  2504  2504 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 14:43:19.671  6669  6669 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 14:43:19.671  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 14:43:19.671  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 14:43:19.671  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 14:43:19.671  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 14:43:19.671  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 14:43:19.671  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 14:43:19.671  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 14:43:19.671  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 14:43:19.673  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 14:43:19.680  1032  1032 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
09-12 14:43:19.681  1032  1441 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
09-12 14:43:19.681  1032  1441 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
09-12 14:43:19.690  6811  6811 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-12 14:43:19.690  6811  6811 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-12 14:43:19.690  6811  6811 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-12 14:43:19.695  6356  6356 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-12 14:43:19.705  6738  6738 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-12 14:43:19.715  6738  6738 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-12 14:43:19.724  6811  6811 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-12 14:43:19.724  6811  6811 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-12 14:43:19.724  6811  6811 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-12 14:43:19.729  6356  6356 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-12 14:43:19.739  6738  6738 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-12 14:43:19.748  6738  6738 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-12 14:43:19.760  6811  6811 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-12 14:43:19.760  6811  6811 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-12 14:43:19.761  6811  6811 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-12 14:43:19.768  6356  6356 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-12 14:43:19.784  6550  6908 D UEI.SmartControl: Internal timer expired: 2
09-12 14:43:19.784  6738  6738 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-12 14:43:19.784  6550  6908 D UEI.SmartControl: unbind internal service
,09-12 14:43:19.799  6738  6738 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-12 14:43:19.817  6811  6811 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-12 14:43:19.818  6811  6811 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-12 14:43:19.819  6811  6811 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-12 14:43:19.836  6356  6356 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-12 14:43:19.862  6738  6738 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-12 14:43:19.870  6738  6738 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-12 14:43:19.874  6550  6888 D serial_port: close(fd = 24)
09-12 14:43:19.878  6550  6888 I UEI.SmartControl: Serial port is closed.
,09-12 14:43:19.886  6811  6811 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-12 14:43:19.886  6811  6811 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-12 14:43:19.890  6811  6811 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-12 14:43:19.895  6356  6356 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-12 14:43:19.906  6738  6738 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-12 14:43:19.917  6738  6738 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-12 14:43:19.927  6811  6811 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-12 14:43:19.927  6811  6811 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-12 14:43:19.928  6811  6811 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-12 14:43:19.933  6356  6356 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-12 14:43:19.941  6766  6766 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,09-12 14:43:19.955  1032  1454 D WifiService: New client listening to asynchronous messages
,09-12 14:43:19.955  6766  6766 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-12 14:43:19.964  6738  6738 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-12 14:43:19.977  6738  6738 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-12 14:43:19.992  6811  6811 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-12 14:43:19.993  6811  6811 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-12 14:43:19.995  6811  6811 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-12 14:43:19.998  6811  6811 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-12 14:43:19.999  6811  6811 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-12 14:43:20.011  6356  6356 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-12 14:43:20.020  6766  6766 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-12 14:43:20.024  6766  6766 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-12 14:43:20.033  6738  6738 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-12 14:43:20.048  6738  6738 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-12 14:43:20.067  6811  6811 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-12 14:43:20.068  6811  6811 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-12 14:43:20.071  6811  6811 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-12 14:43:20.073  6811  6811 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-12 14:43:20.074  6811  6811 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-12 14:43:20.081  1032  1572 I ActivityManager: Killing 6787:com.lge.lifetracker/u0a37 (adj 15): empty #17
,09-12 14:43:20.150  1032  1780 W libprocessgroup: failed to open /acct/uid_10037/pid_6787/cgroup.procs: No such file or directory
,09-12 14:43:20.154  2208  2208 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,09-12 14:43:20.171  2208  2208 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,09-12 14:43:20.172  2208  2208 D c       : Getting all permits...
09-12 14:43:20.172  2208  2208 D a       : Opening database...
09-12 14:43:20.181  2208  2208 D a       : Opening database auth.proximity.permit_store...
09-12 14:43:20.182  2208  2208 D a       : Closing database...
09-12 14:43:20.195  6356  6356 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-12 14:43:20.200  6766  6766 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-12 14:43:20.200  6766  6766 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-12 14:43:20.200  6766  6766 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-12 14:43:20.204  6738  6738 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-12 14:43:20.212  6738  6738 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-12 14:43:20.221  6811  6811 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-12 14:43:20.222  6811  6811 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-12 14:43:20.225  6811  6811 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-12 14:43:20.230  6356  6356 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-12 14:43:20.235  6766  6766 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-12 14:43:20.235  6766  6766 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-12 14:43:20.235  6766  6766 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-12 14:43:20.240  6738  6738 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-12 14:43:20.249  6738  6738 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-12 14:43:20.261  6811  6811 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-12 14:43:20.262  6811  6811 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-12 14:43:20.265  6811  6811 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-12 14:43:20.271  6356  6356 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-12 14:43:20.279  6766  6766 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,09-12 14:43:20.279  6766  6766 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-12 14:43:20.279  6766  6766 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-12 14:43:20.284  6738  6738 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-12 14:43:20.293  6738  6738 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-12 14:43:20.301  6811  6811 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-12 14:43:20.302  6811  6811 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-12 14:43:20.305  6811  6811 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-12 14:43:20.319  6766  6766 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-12 14:43:20.324  6738  6738 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-12 14:43:20.331  6850  7295 V FormManager: Network unavailable.
09-12 14:43:20.332  6850  7294 W FormManager: Network not available. Please check & try again.
,09-12 14:43:20.335  6850  7295 V FormManager: Network unavailable.
09-12 14:43:20.337  6738  6738 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-12 14:43:20.356  6738  6738 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-12 14:43:20.356  6738  6738 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-12 14:43:20.357  6738  6738 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-12 14:43:20.357  6738  6738 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-12 14:43:20.358  6738  6738 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,09-12 14:43:20.358  6738  6738 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-12 14:43:20.358  6738  6738 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-12 14:43:20.358  6738  6738 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-12 14:43:20.358  6738  6738 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-12 14:43:20.359  6738  6738 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-12 14:43:20.359  6738  6738 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-12 14:43:20.366  2208  2208 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
09-12 14:43:20.389  4334  4334 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-12 14:43:20.390  4334  4334 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,09-12 14:43:20.393  4334  4334 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-12 14:43:20.396  4334  4334 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-12 14:43:20.407  4334  7296 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-12 14:43:20.409  6766  6766 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
09-12 14:43:20.409  6766  6766 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,09-12 14:43:20.409  6766  6766 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-12 14:43:20.414  4334  7297 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-12 14:43:20.414  4334  7297 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-12 14:43:20.416  6738  6738 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-12 14:43:20.428  6850  7299 W FormManager: Network not available. Please check & try again.
09-12 14:43:20.430  6738  6738 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-12 14:43:20.436  6850  7300 V FormManager: Network unavailable.
,09-12 14:43:20.447  6850  7300 V FormManager: Network unavailable.
,09-12 14:43:21.093  1032  1396 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:510418565] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,09-12 14:43:21.095  1032  1396 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:510418567] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,09-12 14:43:21.166  1032  1466 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-12 14:43:21.180  1032  1094 D Tethering: MasterInitialState.processMessage what=3
09-12 14:43:21.188  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 14:43:21.191  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 14:43:21.195  1032  1089 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-12 14:43:21.198  6356  6356 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-12 14:43:21.200  6356  6765 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,09-12 14:43:21.212  5772  5772 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,09-12 14:43:21.231  2208  2208 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-12 14:43:21.250  6934  6934 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-12 14:43:21.250  6934  6934 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-12 14:43:21.250  6934  6934 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-12 14:43:21.250  6934  6934 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,09-12 14:43:21.254  6934  6934 I AppUp4:CustModeStarterReceiver: onReceive
09-12 14:43:21.258  6934  6934 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@344495f5
09-12 14:43:21.258  6934  6934 D AppUp4:CustFacade: isCustomizationCompleted : false
09-12 14:43:21.258  6934  6934 D AppUp4:CustFacade: isPhone : true
09-12 14:43:21.259  6934  6934 D AppUp4:CustModeStarterReceiver: begin check event
09-12 14:43:21.259  6934  6934 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-12 14:43:21.264  4334  4334 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-12 14:43:21.264  4334  4334 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,09-12 14:43:21.269  4334  4334 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-12 14:43:21.271  4334  4334 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-12 14:43:21.279  6960  6960 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,09-12 14:43:21.310  3309  3309 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-12 14:43:21.310  3309  3309 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-12 14:43:21.310  3309  3309 I LgeMiscReceiver: networkInfo.isConnected() = true
09-12 14:43:21.310  3309  3309 D PhoneState: setPdpRejectCasuse : false
,09-12 14:43:21.316  6996  6996 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-12 14:43:21.316  6996  6996 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-12 14:43:21.327  1032  1089 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-12 14:43:21.337  4334  7309 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-12 14:43:21.339  4334  7323 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-12 14:43:21.339  4334  7323 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-12 14:43:21.346  6960  7308 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-12 14:43:21.353  7067  7067 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:43:21
,09-12 14:43:21.355  7067  7067 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-12 14:43:21.355  7067  7067 D Weather.Utils: 2 : All the weather widget is gone.
09-12 14:43:21.355  7067  7067 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-12 14:43:21.355  7067  7067 D WeatherAncestor: connectivity changed - connection : true
09-12 14:43:21.356  7067  7067 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@153cf9fb
09-12 14:43:21.357  7067  7067 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-12 14:43:21.357  7067  7067 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-12 14:43:21.357  7067  7067 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-12 14:43:21.357  7067  7067 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-12 14:43:21.357  6850  7325 W FormManager: Network not available. Please check & try again.
09-12 14:43:21.357  7067  7067 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:43:21
,09-12 14:43:21.365  6850  7327 V FormManager: Network unavailable.
09-12 14:43:21.372  6850  7327 V FormManager: Network unavailable.
,09-12 14:43:22.274  1032  1650 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-12 14:43:22.275  1032  1650 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,09-12 14:43:22.305  1032  1032 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-12 14:43:22.306  1032  1032 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-12 14:43:22.306  1032  1032 D Ulp_jni : JNI:system_update. Event-4
,09-12 14:43:22.309  1032  1094 D BluetoothManagerService: Message: 1
09-12 14:43:22.309  1032  1094 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
09-12 14:43:22.342  1032  1094 D BluetoothManagerService: Message: 20
09-12 14:43:22.342  1032  1094 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@9619c5a:true
,09-12 14:43:22.346  6889  6889 D BluetoothAdapterState: make
09-12 14:43:22.351  6889  6889 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
09-12 14:43:22.351  6889  6889 I bluedroid-qcom: init
09-12 14:43:22.352  6889  7340 I BluetoothAdapterState: Entering OffState
09-12 14:43:22.352  6889  6889 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-12 14:43:22.353  6889  6889 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-12 14:43:22.353  6889  6889 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-12 14:43:22.353  6889  6889 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-12 14:43:22.353  6889  6889 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
09-12 14:43:22.355  6889  6889 I bluedroid-qcom: get_profile_interface socket
09-12 14:43:22.355  6889  6889 I bluedroid-qcom: get_profile_interface map_client
,09-12 14:43:22.359  6889  7344 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
09-12 14:43:22.359  1032  1466 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-12 14:43:22.351  7343  7343 W bdaddr_loader: type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-12 14:43:22.351  7343  7343 W bdaddr_loader: type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-12 14:43:22.368  1032  1094 D Tethering: MasterInitialState.processMessage what=3
09-12 14:43:22.369  1032  1466 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-12 14:43:22.381  7343  7343 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
09-12 14:43:22.381  7343  7343 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
09-12 14:43:22.381  7343  7343 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,09-12 14:43:22.385  7343  7343 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
09-12 14:43:22.387  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 14:43:22.389  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 14:43:22.391  7343  7343 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
09-12 14:43:22.391  7343  7343 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
09-12 14:43:22.397  1032  1094 D Tethering: MasterInitialState.processMessage what=3
,09-12 14:43:22.402  6889  7344 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
09-12 14:43:22.411  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 14:43:22.415  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 14:43:22.417  1032  1032 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
09-12 14:43:22.418  1032  1094 D BluetoothManagerService: Message: 40
09-12 14:43:22.418  1032  1094 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
09-12 14:43:22.419  6889  6904 I bluedroid-qcom: config_hci_snoop_log
09-12 14:43:22.420  1032  1094 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
09-12 14:43:22.420  1032  1094 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
09-12 14:43:22.424  6889  7344 D BluetoothAdapterProperties: Name is: G3
,09-12 14:43:22.435  1032  1032 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-12 14:43:22.435  6356  6356 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-12 14:43:22.435  1032  1032 D BluetoothManagerService: Stored Bluetooth name: G3
09-12 14:43:22.436  6889  7340 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
09-12 14:43:22.436  6889  7340 D BluetoothAdapterProperties: Setting state to 11
09-12 14:43:22.437  6889  7340 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,09-12 14:43:22.439  6356  6765 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-12 14:43:22.441  1032  1089 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-12 14:43:22.442  5772  5772 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
09-12 14:43:22.442  1032  1094 D BluetoothManagerService: Message: 60
09-12 14:43:22.442  1032  1094 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
09-12 14:43:22.442  1032  1094 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
09-12 14:43:22.444  6889  7340 I LGBluetoothServiceJni: classInitNative: succeeds
09-12 14:43:22.453  6889  7340 D BluetoothBondStateMachine: make
,09-12 14:43:22.458  5772  5772 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
09-12 14:43:22.459  6889  7360 I BluetoothBondStateMachine: StableState(): Entering Off State
09-12 14:43:22.459  6889  7340 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@153cf9fb
09-12 14:43:22.460  6889  7340 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
09-12 14:43:22.460  6889  7340 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@153cf9fb
09-12 14:43:22.460  6889  7340 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
09-12 14:43:22.460  6889  7340 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
09-12 14:43:22.461  1032  1089 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-12 14:43:22.462  1032  1089 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 14:43:22.462  1032  1089 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 14:43:22.463  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-12 14:43:22.465  6889  7340 E BluetoothAdapterService: File transfer profiles supported!!
09-12 14:43:22.465  6738  6738 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
09-12 14:43:22.465  1599  1599 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,09-12 14:43:22.468  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 14:43:22.471  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 14:43:22.474  6889  7340 E BluetoothAdapterService: File transfer profiles supported!!
09-12 14:43:22.475  6889  6889 D HeadsetService: Received start request. Starting profile...
09-12 14:43:22.476  6889  6889 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
09-12 14:43:22.476  6889  6889 D LGBluetoothHfpAdapter: Version 1.6
,09-12 14:43:22.479  6889  6889 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-12 14:43:22.481  6889  6889 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-12 14:43:22.482  6889  6889 D HeadsetStateMachine: make
09-12 14:43:22.485  6889  7340 E BluetoothAdapterService: File transfer profiles supported!!
09-12 14:43:22.492  6889  7340 E BluetoothAdapterService: File transfer profiles supported!!
09-12 14:43:22.502  6889  7340 E BluetoothAdapterService: File transfer profiles supported!!
,09-12 14:43:22.502  2208  2208 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
09-12 14:43:22.512  6889  7340 E BluetoothAdapterService: File transfer profiles supported!!
09-12 14:43:22.513  6934  6934 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-12 14:43:22.514  6934  6934 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-12 14:43:22.514  6934  6934 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-12 14:43:22.514  6934  6934 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,09-12 14:43:22.517  6934  6934 I AppUp4:CustModeStarterReceiver: onReceive
09-12 14:43:22.519  6889  7340 E BluetoothAdapterService: File transfer profiles supported!!
09-12 14:43:22.520  6889  6889 D LgDataFeature: LgDataFeature() Constructor: none
09-12 14:43:22.520  6889  6889 D LgDataFeature: LgDataFeature() Constructor Done, null
09-12 14:43:22.524  6889  6889 D HeadsetStateMachine: max_hf_connections = 1
09-12 14:43:22.524  6889  6889 I bluedroid-qcom: get_profile_interface handsfree
09-12 14:43:22.526  6889  6889 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
09-12 14:43:22.527   311  1394 V AudioPolicyService: registerClient() client 0xb558a6c0, uid 1002
,09-12 14:43:22.527   311  2165 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
09-12 14:43:22.527   311  2165 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-12 14:43:22.527   311  2165 V AudioPolicyManagerEx: getOutput() returns output 2
09-12 14:43:22.527  6889  6889 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
09-12 14:43:22.528   311  1395 V AudioFlinger: registerClient() client 0xb5581610, pid 6889
09-12 14:43:22.528   311  1390 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-12 14:43:22.528   311  1390 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-12 14:43:22.529  6889  6905 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-12 14:43:22.529  1032  1966 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-12 14:43:22.529  1032  1966 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-12 14:43:22.529   311  1389 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-12 14:43:22.529   311  1389 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-12 14:43:22.529  1599  2167 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-12 14:43:22.529  1599  2167 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-12 14:43:22.529  1599  2167 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-12 14:43:22.529  1599  2167 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-12 14:43:22.529  1032  1940 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-12 14:43:22.529  1032  1940 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-12 14:43:22.529  1852  1867 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-12 14:43:22.529  1852  1867 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-12 14:43:22.529  1852  1867 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-12 14:43:22.529  1852  1867 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-12 14:43:22.529  6934  6934 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@344495f5
09-12 14:43:22.529  3309  3327 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-12 14:43:22.529  6934  6934 D AppUp4:CustFacade: isCustomizationCompleted : false
09-12 14:43:22.529  3309  3327 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-12 14:43:22.529  6934  6934 D AppUp4:CustFacade: isPhone : true
09-12 14:43:22.529  3309  3327 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-12 14:43:22.529  3309  3327 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-12 14:43:22.530  6934  6934 D AppUp4:CustModeStarterReceiver: begin check event
09-12 14:43:22.530  6934  6934 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-12 14:43:22.530  6889  6905 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
09-12 14:43:22.530  6889  6905 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-12 14:43:22.530  6889  6905 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
09-12 14:43:22.530  6889  6889 V ToneGenerator: Create Track: 0xb4928a80
09-12 14:43:22.530  6889  6889 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
09-12 14:43:22.530  6889  6889 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
09-12 14:43:22.530   311   311 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-12 14:43:22.530   311   311 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
09-12 14:43:22.530   311   311 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-12 14:43:22.530   311   311 V AudioPolicyManagerEx: ge,tOutput() returns output 2
09-12 14:43:22.531   311  1394 I AudioFlinger: isAudioPlaybackHookOn() false
09-12 14:43:22.531   311  2165 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-12 14:43:22.531   311  2165 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
09-12 14:43:22.531   311  2165 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-12 14:43:22.531   311  2165 V AudioPolicyManagerEx: getOutput() returns output 2
09-12 14:43:22.531  6889  6889 V AudioSystem: getLatency() output 2, latency 50
09-12 14:43:22.531  6889  6889 V AudioSystem: getFrameCount() output 2, frameCount 960
09-12 14:43:22.531  6889  6889 V AudioTrack: createTrack_l() output 2 afLatency 50
09-12 14:43:22.532   311  2164 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-12 14:43:22.532   311  2164 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-12 14:43:22.532   311  2164 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-12 14:43:22.532   311  2164 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-12 14:43:22.532   311  2164 V AudioFlinger: createTrack() lSessionId: 20
09-12 14:43:22.532  6889  6889 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
09-12 14:43:22.532  4334  4334 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-12 14:43:22.532   311  2164 V AudioFlinger: acquiring 20 from 6889, for 6889
09-12 14:43:22.532   311  2164 V AudioFlinger:  added new entry for 20
09-12 14:43:22.533  6889  6889 V ToneGenerator: ToneGenerator INIT OK, time: 202145
09-12 14:43:22.533  6889  6889 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@153cf9fb
09-12 14:43:22.533  4334  4334 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-12 14:43:22.533  6889  7363 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
09-12 14:43:22.533  6889  7363 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-12 14:43:22.533  6889  7363 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-12 14:43:22.533  6889  7363 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
09-12 14:43:22.534   311   311 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6889
09-12 14:43:22.534   311   311 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
09-12 14:43:22.534  4334  4334 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-12 14:43:22.534   311   311 V voice   : voice_set_parameters: enter: bt_samplerate=8000
09-12 14:43:22.534   311   311 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
09-12 14:43:22.534   311   311 V compress_voip: voice_extn_compress_voip_set_parameters: exit
09-12 14:43:22.534   311   311 V voice   : voice_set_parameters: exit with code(0)
09-12 14:43:22.534   311   311 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
09-12 14:43:22.534   311   311 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
09-12 14:43:22.534  6889  7340 V LGMDMManager: Create singleton instance
09-12 14:43:22.534   311   311 V msm8974_platform: platform_set_parameters: exit with code(0)
09-12 14:43:22.534   311   311 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
09-12 14:43:22.534   311   311 V audio_hw_primary: adev_set_parameters: exit with code(0)
,09-12 14:43:22.534   311   311 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
09-12 14:43:22.536  6889  6889 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@153cf9fb
09-12 14:43:22.536  6889  7363 V ToneGenerator: ToneGenerator destructor
09-12 14:43:22.536  6889  7363 V ToneGenerator: stopTone
09-12 14:43:22.536  6889  7363 V ToneGenerator: Delete Track: 0xb4928a80
09-12 14:43:22.537  6889  6889 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-12 14:43:22.537  6889  7363 V AudioTrack: ~AudioTrack, releasing session id from 6889 on behalf of 6889
,09-12 14:43:22.538   311  1394 V AudioPolicyService: AudioCommandThread() adding release output 2
09-12 14:43:22.538   311  1395 V AudioFlinger: releasing 20 from 6889 for 6889
09-12 14:43:22.538   311  1394 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
09-12 14:43:22.538   311  1395 V AudioFlinger:  decremented refcount to 0
09-12 14:43:22.538   311  1394 V AudioFlinger: PlaybackThread::Track destructor
09-12 14:43:22.538   311  1225 V AudioPolicyService: AudioCommandThread() waking up
09-12 14:43:22.538  4334  4334 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-12 14:43:22.538   311  1225 V AudioPolicyService: AudioCommandThread() processing release output 2
09-12 14:43:22.538   311  1394 V AudioFlinger: removeClient_l() pid 6889, calling pid 311
09-12 14:43:22.538   311  1225 V AudioPolicyManager: releaseOutput() 2
09-12 14:43:22.538   311  1225 V AudioPolicyService: AudioCommandThread() going to sleep
09-12 14:43:22.538   311  1395 V AudioFlinger: purging stale effects
09-12 14:43:22.538  6889  6889 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-12 14:43:22.540  1032  1940 W Process : Unable to open /proc/7365/status
09-12 14:43:22.542  6889  6889 V BluetoothPbapReceiver: ***********state = 11
09-12 14:43:22.543  6889  7340 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
09-12 14:43:22.546  4334  7366 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-12 14:43:22.546  6889  6889 D A2dpService: Received start request. Starting profile...
09-12 14:43:22.546  2208  2208 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-12 14:43:22.547  6889  6889 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-12 14:43:22.547  4334  7367 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-12 14:43:22.547  4334  7367 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-12 14:43:22.548  6889  6889 V Avrcp   : make
09-12 14:43:22.548  6889  6889 D Avrcp   : [BTUI] Use Native AVRCP : init jni
09-12 14:43:22.548  6889  6889 I bluedroid-qcom: get_profile_interface avrcp
09-12 14:43:22.550  6960  6960 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,09-12 14:43:22.584  1032  1903 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7369 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,09-12 14:43:22.593  6889  6889 V AudioManager: registerRemoteController: size of Media player list: 0
09-12 14:43:22.594  6889  6889 E AudioManager: No RCC entry present to update
09-12 14:43:22.594  6889  6889 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-12 14:43:22.597  6889  6889 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
09-12 14:43:22.598  6889  6889 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
09-12 14:43:22.598  6889  6889 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
,09-12 14:43:22.601  6889  6889 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,09-12 14:43:22.650  6960  7389 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 14:43:22.662  3309  3309 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-12 14:43:22.662  3309  3309 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-12 14:43:22.662  3309  3309 I LgeMiscReceiver: networkInfo.isConnected() = false
,09-12 14:43:22.664  6850  7390 W FormManager: Network not available. Please check & try again.
09-12 14:43:22.666  6996  6996 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-12 14:43:22.667  6996  6996 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-12 14:43:22.673  6850  7391 V FormManager: Network unavailable.
,09-12 14:43:22.681  7067  7067 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:43:22
09-12 14:43:22.682  6850  7391 V FormManager: Network unavailable.
09-12 14:43:22.683  7067  7067 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-12 14:43:22.683  7067  7067 D Weather.Utils: 2 : All the weather widget is gone.
09-12 14:43:22.683  7067  7067 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-12 14:43:22.683  7067  7067 D WeatherAncestor: connectivity changed - connection : true
09-12 14:43:22.683  7067  7067 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@153cf9fb
09-12 14:43:22.685  7067  7067 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
,09-12 14:43:22.685  7067  7067 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
,09-12 14:43:22.685  7067  7067 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-12 14:43:22.685  7067  7067 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-12 14:43:22.687  7067  7067 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:43:22
09-12 14:43:22.703  6356  6356 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,09-12 14:43:22.708  6356  6765 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-12 14:43:22.714  2208  2208 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
09-12 14:43:22.721  1032  1903 V SIM_STK : Menu title from STK is T-Mobile
09-12 14:43:22.721  7369  7369 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
09-12 14:43:22.721  1032  1903 V SIM_STK : Menu title from STK is T-Mobile
09-12 14:43:22.722  7369  7369 W LG Account v2.2: No ProfileInfo entries
09-12 14:43:22.722  7369  7369 I LG Account v2.2: isEnabled: false
09-12 14:43:22.722  7369  7369 I Feature : [Lifetracker]ver: 4.21.112(40211120)
09-12 14:43:22.722  7369  7369 I Feature : [Lifetracker]Country: EU
09-12 14:43:22.722  7369  7369 I Feature : [Lifetracker]Operator: OPEN
09-12 14:43:22.722  7369  7369 I Feature : [Lifetracker]Ranking support: false
09-12 14:43:22.722  7369  7369 I Feature : [Lifetracker]Comfort support: false
09-12 14:43:22.722  7369  7369 I Feature : [Lifetracker]Accessory: true
09-12 14:43:22.722  7369  7369 I Feature : [Lifetracker]Health device: true
09-12 14:43:22.722  7369  7369 I Feature : [Lifetracker]Extra Pedometer: false
09-12 14:43:22.722  7369  7369 I Feature : [Lifetracker]Blood glucose device: false
09-12 14:43:22.722  7369  7369 I Feature : [Lifetracker]Device Number: 3
09-12 14:43:22.723  6934  6934 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-12 14:43:22.723  6934  6934 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-12 14:43:22.723  6934  6934 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-12 14:43:22.723  6934  6934 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,09-12 14:43:22.729  6934  6934 I AppUp4:CustModeStarterReceiver: onReceive
09-12 14:43:22.731  6738  6738 D BluetoothPermissionRequest: onReceive
09-12 14:43:22.732  6934  6934 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@344495f5
09-12 14:43:22.732  6934  6934 D AppUp4:CustFacade: isCustomizationCompleted : false
09-12 14:43:22.732  6934  6934 D AppUp4:CustFacade: isPhone : true
09-12 14:43:22.732  6934  6934 D AppUp4:CustModeStarterReceiver: begin check event
09-12 14:43:22.732  6934  6934 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-12 14:43:22.735  4334  4334 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-12 14:43:22.735  4334  4334 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,09-12 14:43:22.736  4334  4334 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-12 14:43:22.737  6738  6738 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-12 14:43:22.740  4334  4334 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-12 14:43:22.745  4334  7395 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-12 14:43:22.747  6960  6960 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,09-12 14:43:22.750  4334  7396 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-12 14:43:22.750  4334  7396 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-12 14:43:22.761  6850  7399 W FormManager: Network not available. Please check & try again.
,09-12 14:43:22.766  3309  3309 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-12 14:43:22.766  3309  3309 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-12 14:43:22.766  3309  3309 I LgeMiscReceiver: networkInfo.isConnected() = false
09-12 14:43:22.768  6960  7397 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 14:43:22.769  6996  6996 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-12 14:43:22.769  6996  6996 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-12 14:43:22.772  6850  7400 V FormManager: Network unavailable.
09-12 14:43:22.779  6850  7400 V FormManager: Network unavailable.
,09-12 14:43:22.783  7067  7067 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:43:22
09-12 14:43:22.784  7067  7067 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-12 14:43:22.784  7067  7067 D Weather.Utils: 2 : All the weather widget is gone.
09-12 14:43:22.785  7067  7067 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-12 14:43:22.785  7067  7067 D WeatherAncestor: connectivity changed - connection : true
09-12 14:43:22.785  7067  7067 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@153cf9fb
09-12 14:43:22.786  7067  7067 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-12 14:43:22.786  7067  7067 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-12 14:43:22.786  7067  7067 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-12 14:43:22.786  7067  7067 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-12 14:43:22.786  7067  7067 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:43:22
09-12 14:43:22.789  1032  1903 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
09-12 14:43:22.794  6889  6889 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,09-12 14:43:22.797  6889  6889 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-12 14:43:22.798  6889  6889 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-12 14:43:22.798  6889  6889 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-12 14:43:22.798  6889  6889 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-12 14:43:22.798  6889  6889 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-12 14:43:22.798  6889  6889 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-12 14:43:22.798  6889  6889 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-12 14:43:22.798  6889  6889 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-12 14:43:22.798  6889  6889 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-12 14:43:22.798  6889  6889 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-12 14:43:22.798  6889  6889 I BluetoothA2dpServiceJni: classInitNative
09-12 14:43:22.799  6889  6889 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-12 14:43:22.799  6889  6889 D A2dpStateMachine: make
09-12 14:43:22.800  6889  6889 I bluedroid-qcom: get_profile_interface a2dp
09-12 14:43:22.800  6889  7403 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
09-12 14:43:22.802  6889  6889 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
09-12 14:43:22.802  6889  6889 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
09-12 14:43:22.803  6889  6889 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@153cf9fb
09-12 14:43:22.803  6889  7402 D A2dpStateMachine: Enter Disconnected: -2
09-12 14:43:22.804  6889  6889 I BluetoothHidServiceJni: classInitNative: succeeds
09-12 14:43:22.806  6889  6889 D HidService: Received start request. Starting profile...
09-12 14:43:22.806  6889  6889 I bluedroid-qcom: get_profile_interface hidhost
09-12 14:43:22.806  6889  6889 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@153cf9fb
09-12 14:43:22.806  6889  6889 I BluetoothHealthServiceJni: classInitNative: succeeds
09-12 14:43:22.808  6889  6889 D HealthService: Received start request. Starting profile...
,09-12 14:43:22.811  6889  6889 I bluedroid-qcom: get_profile_interface health
09-12 14:43:22.811  6889  6889 I LGBluetoothHealthServiceJni: classInitNative: succeeds
09-12 14:43:22.811  6889  6889 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@153cf9fb
09-12 14:43:22.812  6889  6889 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-12 14:43:22.814  6889  6889 D PanService: Received start request. Starting profile...
09-12 14:43:22.814  6889  6889 D BluetoothPanServiceJni: initializeNative(L110): pan
09-12 14:43:22.814  6889  6889 I bluedroid-qcom: get_profile_interface pan
09-12 14:43:22.821  6889  6889 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
09-12 14:43:22.821  6889  6889 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@153cf9fb
,09-12 14:43:22.822  6889  6889 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
,09-12 14:43:22.829  6889  6889 D BtGatt.DebugUtils: handleDebugAction() action=null
09-12 14:43:22.830  6889  6889 D BtGatt.GattService: Received start request. Starting profile...
09-12 14:43:22.830  6889  6889 D BtGatt.GattService: start()
09-12 14:43:22.830  6889  6889 I bluedroid-qcom: get_profile_interface gatt
09-12 14:43:22.831  6889  6889 D BtGatt.AdvertiseManager: advertise manager created
09-12 14:43:22.840  6889  6889 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@153cf9fb
09-12 14:43:22.841  6889  6889 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@153cf9fb
,09-12 14:43:22.842  6889  6889 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
09-12 14:43:22.843  6889  6889 V BluetoothMapService: BluetoothMapBinder()
09-12 14:43:22.844  6889  6889 D BluetoothMapService: Received start request. Starting profile...
09-12 14:43:22.844  6889  6889 D BluetoothMapService: start()
09-12 14:43:22.848  6889  6889 D BluetoothMapEmailSettingsLoader: Found 0 applications
09-12 14:43:22.848  6889  6889 D BluetoothMapEmailAppObserver: createReceiver()
09-12 14:43:22.850  6889  6889 D BluetoothMapEmailAppObserver: initObservers()
09-12 14:43:22.850  6889  6889 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
,09-12 14:43:22.864  6889  6889 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@153cf9fb
09-12 14:43:22.864  6889  6889 D HeadsetStateMachine: Proxy object connected
09-12 14:43:22.866  6889  6889 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
09-12 14:43:22.866  6889  6889 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
,09-12 14:43:22.872  6889  6889 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-12 14:43:22.873  6889  7363 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-12 14:43:22.874  6889  7363 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-12 14:43:22.874  6889  7363 D HeadsetStateMachine: Disconnected process message: 11, size: 0
09-12 14:43:22.876  6889  6889 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-12 14:43:22.880  6889  6889 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,09-12 14:43:22.886  6889  6889 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-12 14:43:22.886  6889  6889 V PanService: [BTUI] SIM Extra State :ABSENT
09-12 14:43:22.892  6889  6889 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-12 14:43:22.897  6889  6889 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
09-12 14:43:22.897  6889  6889 V BluetoothMapService: Handler(): got msg=1
09-12 14:43:22.899  6889  7340 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
09-12 14:43:22.899  6889  7340 I bluedroid-qcom: enable
09-12 14:43:22.900  6889  7340 I bt_hci_bdroid: init
,09-12 14:43:22.901  6889  6889 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-12 14:43:22.903  6889  7340 I bt_vendor: bt-vendor : init
09-12 14:43:22.903  6889  7340 I bt_vendor: bt-vendor : get_bt_soc_type
09-12 14:43:22.903  6889  7340 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-12 14:43:22.903  6889  6889 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-12 14:43:22.903  6889  7340 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
09-12 14:43:22.903  6889  6889 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-12 14:43:22.903  6889  7340 D bt_userial_mct: userial_init
09-12 14:43:22.903  6889  6889 V BluetoothSapReceiver: SapReceiver onReceive 
09-12 14:43:22.904  6889  6889 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-12 14:43:22.904  6889  7410 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
09-12 14:43:22.904  6889  6889 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
09-12 14:43:22.904  6889  7410 I bt-btu  : btu_task pending for preload complete event
09-12 14:43:22.908  6889  7340 D bt_hci_bdroid: set_power 1
09-12 14:43:22.908  6889  7340 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-12 14:43:22.908  6889  7340 I bt_vendor: Starting hciattach daemon
09-12 14:43:22.908  6889  7340 I bt_vendor: try to set true
09-12 14:43:22.901  7413  7413 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-12 14:43:22.901  7413  7413 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file,
09-12 14:43:22.937  7414  7414 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,09-12 14:43:23.050  7420  7420 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,09-12 14:43:23.064  7421  7421 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
09-12 14:43:23.090  7423  7423 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-12 14:43:23.111  7424  7424 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,09-12 14:43:23.126  7425  7425 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
09-12 14:43:23.140  7426  7426 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,09-12 14:43:23.176  7428  7428 I libmdmdetect: ESOC framework not supported
,09-12 14:43:23.178  7428  7428 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
09-12 14:43:23.190  7428  7428 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
09-12 14:43:23.190  7428  7428 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
09-12 14:43:23.190  7428  7428 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
09-12 14:43:23.190  7428  7428 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
09-12 14:43:23.190  7428  7428 D bthci_qcomm_common: [BTUI]     LE: Class 2
09-12 14:43:23.190  7428  7428 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
09-12 14:43:23.190  7428  7428 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
09-12 14:43:23.238  7428  7429 E QC-QMI  : qmi_client [7428] 14: failed to locate client data
09-12 14:43:23.238   481   481 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
09-12 14:43:23.239   481   481 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
,09-12 14:43:23.309  7436  7436 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,09-12 14:43:23.332  7437  7437 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-12 14:43:23.365  6889  7340 I bt_vendor: bluetooth satus is on
09-12 14:43:23.365  6889  7340 D bt_hci_bdroid: preload
,09-12 14:43:23.368  6889  7412 D bt_userial_mct: userial_open(port:0)
09-12 14:43:23.368  6889  7412 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
09-12 14:43:23.372  6889  7412 I bt_vendor: Done intiailizing UART
09-12 14:43:23.381  6889  7412 I bt_vendor: Done intiailizing UART
09-12 14:43:23.381  6889  7412 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
09-12 14:43:23.381  6889  7412 I bt_vendor: Bluetooth Firmware and transport layer are initialized
,09-12 14:43:23.387  6889  7410 I bt-btu  : btu_task received preload complete event
09-12 14:43:23.388  6889  7410 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
09-12 14:43:23.388  6889  7410 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
09-12 14:43:23.390  6889  7410 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
09-12 14:43:23.392  6889  7453 D bt_userial_mct: Entering userial_read_thread()
09-12 14:43:23.393  6889  7410 I         : BTE_InitTraceLevels -- TRC_HCI
09-12 14:43:23.393  6889  7410 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-12 14:43:23.393  6889  7410 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-12 14:43:23.393  6889  7410 I         : BTE_InitTraceLevels -- TRC_AVDT
09-12 14:43:23.393  6889  7410 I         : BTE_InitTraceLevels -- TRC_AVRC
09-12 14:43:23.393  6889  7410 I         : BTE_InitTraceLevels -- TRC_A2D
09-12 14:43:23.393  6889  7410 I         : BTE_InitTraceLevels -- TRC_BNEP
09-12 14:43:23.393  6889  7410 I         : BTE_InitTraceLevels -- TRC_BTM
09-12 14:43:23.393  6889  7410 I         : BTE_InitTraceLevels -- TRC_HID_HOST
09-12 14:43:23.393  6889  7410 I         : BTE_InitTraceLevels -- TRC_GAP
09-12 14:43:23.393  6889  7410 I         : BTE_InitTraceLevels -- TRC_PAN
09-12 14:43:23.394  6889  7410 I         : BTE_InitTraceLevels -- TRC_SDP
09-12 14:43:23.394  6889  7410 I         : BTE_InitTraceLevels -- TRC_GATT
09-12 14:43:23.394  6889  7410 I         : BTE_InitTraceLevels -- TRC_SMP
09-12 14:43:23.394  6889  7410 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-12 14:43:23.394  6889  7410 I         : BTE_InitTraceLevels -- TRC_BTIF
09-12 14:43:23.404  7098  7130 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,09-12 14:43:23.444  6889  7410 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
09-12 14:43:23.444  6889  7410 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa020e061 
09-12 14:43:23.444  6889  7410 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa020e061 
,09-12 14:43:23.456  6889  7344 E bt-btif : Calling BTA_HhEnable
09-12 14:43:23.456  6889  7344 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
09-12 14:43:23.457  6889  7344 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,09-12 14:43:23.460  6889  7410 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
,09-12 14:43:23.460  6889  7410 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
09-12 14:43:23.460  6889  7410 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
09-12 14:43:23.461  6889  7410 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
09-12 14:43:23.461  6889  7410 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
09-12 14:43:23.462  6889  7344 D BluetoothAdapterProperties: Name is: G3
09-12 14:43:23.462  1032  1032 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-12 14:43:23.462  1032  1032 D BluetoothManagerService: Stored Bluetooth name: G3
09-12 14:43:23.463  6889  7344 D BluetoothAdapterProperties: Scan Mode:20
09-12 14:43:23.463  6889  7344 D BluetoothAdapterProperties: Discoverable Timeout:120
09-12 14:43:23.463  6889  7344 D bt_hci_bdroid: postload
09-12 14:43:23.464  6889  7344 D bte_conf: Device ID record 1 : primary
09-12 14:43:23.464  6889  7344 D bte_conf:   vendorId            = 00c4
09-12 14:43:23.464  6889  7344 D bte_conf:   vendorIdSource      = 0001
09-12 14:43:23.464  6889  7344 D bte_conf:   product             = 13a1
09-12 14:43:23.464  6889  7344 D bte_conf:   version             = 1000
09-12 14:43:23.464  6889  7344 D bte_conf:   clientExecutableURL = 
09-12 14:43:23.464  6889  7344 D bte_conf:   serviceDescription  = 
09-12 14:43:23.464  6889  7344 D bte_conf:   documentationURL    = 
09-12 14:43:23.464  6889  7344 D bte_conf: bte_load_did_conf no section named DID2.
09-12 14:43:23.465  6889  7412 D bt_hci_bdroid: Used up Tx Cmd credits
09-12 14:43:23.466  6889  7410 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
09-12 14:43:23.468  6889  7412 D bt_hci_bdroid: Used up Tx Cmd credits
09-12 14:43:23.469  6889  7340 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-12 14:43:23.469  6889  7340 D BluetoothAdapterProperties: ScanMode =  20
09-12 14:43:23.469  6889  7340 D BluetoothAdapterProperties: State =  11
09-12 14:43:23.470  6889  7340 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
09-12 14:43:23.470  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 14:43:23.472  6889  7412 D bt_hci_bdroid: Used up Tx Cmd credits
09-12 14:43:23.473  6889  7412 D bt_hci_bdroid: Used up Tx Cmd credits
09-12 14:43:23.473  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 14:43:23.474  6889  7340 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
09-12 14:43:23.461  7459  7459 W sh      : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-12 14:43:23.461  7459  7459 W sh      : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-12 14:43:23.474  6889  7340 D BluetoothAdapterProperties: Setting state to 12
09-12 14:43:23.474  6889  7340 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-12 14:43:23.475  6889  7344 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-12 14:43:23.475  1032  1094 D BluetoothManagerService: Message: 60
,09-12 14:43:23.475  1032  1094 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12,
,09-12 14:43:23.475  1032  1094 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
09-12 14:43:23.476  6889  7453 E bt_mct  : hci lib postload completed
09-12 14:43:23.476  6889  7340 I BluetoothAdapterState: Entering On State
09-12 14:43:23.479  6889  7340 D LGBluetoothServiceAdapter: [BTUI] OnState
09-12 14:43:23.479  6889  7340 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
09-12 14:43:23.479  6889  7340 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
09-12 14:43:23.480  6889  7344 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-12 14:43:23.484  6889  7410 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-12 14:43:23.484  6889  7410 W bt-smp  : Plain text(LSB ~ MSB) = 8b bc 48 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-12 14:43:23.484  6889  7410 W bt-smp  : Encrypted text(LSB ~ MSB) = ee 13 24 11 cd ef 54 c4 ec f2 c3 33 01 32 01 17 
09-12 14:43:23.484  6889  7410 W bt-btm  : Stopping oneshot timer
09-12 14:43:23.489  6889  7340 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
,09-12 14:43:23.495  1032  1094 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-12 14:43:23.508  6889  7344 D BluetoothAdapterProperties: Discoverable Timeout:120
09-12 14:43:23.508  6889  7344 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
09-12 14:43:23.519  1032  1032 D BluetoothHeadset: Proxy object connected
09-12 14:43:23.519  6738  6763 D BluetoothMap: onBluetoothStateChange: up=true
,09-12 14:43:23.523  6738  6755 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-12 14:43:23.525  6738  6738 D BluetoothMap: Proxy object connected
09-12 14:43:23.525  6738  6738 D MapProfile: Bluetooth service connected
09-12 14:43:23.525  6738  6738 D BluetoothMap: getConnectedDevices()
09-12 14:43:23.526  6889  7340 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
09-12 14:43:23.527  6889  6905 V BluetoothMapService: getConnectedDevices()
09-12 14:43:23.528  6889  7410 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-12 14:43:23.528  6889  7410 W bt-smp  : Plain text(LSB ~ MSB) = cd 24 7c 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-12 14:43:23.528  6889  7410 W bt-smp  : Encrypted text(LSB ~ MSB) = 6a 4d 50 d0 23 2f 59 9d ac 28 e9 03 53 c6 e1 59 
09-12 14:43:23.528  6889  7410 W bt-btm  : Stopping oneshot timer
09-12 14:43:23.529  1032  1094 D BluetoothA2dp: onBluetoothStateChange: up=true
09-12 14:43:23.531  1032  1032 D BluetoothA2dp: Proxy object connected
09-12 14:43:23.532  1852  2404 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 14:43:23.533  6738  6738 D BluetoothInputDevice: Proxy object connected
,09-12 14:43:23.533  6738  6738 D HidProfile: Bluetooth service connected
09-12 14:43:23.537  1852  1852 D BluetoothHeadset: Proxy object connected
09-12 14:43:23.538  1852  1867 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 14:43:23.539  1852  1852 D BluetoothHeadset: Proxy object connected
09-12 14:43:23.540  6738  7473 D BluetoothPbap: onBluetoothStateChange: up=true
09-12 14:43:23.541  6889  7410 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-12 14:43:23.541  6889  7410 W bt-smp  : Plain text(LSB ~ MSB) = f4 9f 64 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-12 14:43:23.541  6889  7410 W bt-smp  : Encrypted text(LSB ~ MSB) = 1f 35 1d 06 9b 54 1e aa 37 2f a4 60 c8 4c 28 6e 
09-12 14:43:23.541  6889  7410 W bt-btm  : Stopping oneshot timer
09-12 14:43:23.542  1852  1868 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 14:43:23.543  1852  1852 D BluetoothHeadset: Proxy object connected
09-12 14:43:23.544  6738  6755 D BluetoothPan: onBluetoothStateChange on: true
09-12 14:43:23.544  6738  6755 D BluetoothPan: onBluetoothStateChange call bindService
,09-12 14:43:23.547  6738  6738 D BluetoothPan: BluetoothPAN Proxy object connected
09-12 14:43:23.547  6738  6738 D PanProfile: Bluetooth service connected
09-12 14:43:23.548  1032  1094 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
09-12 14:43:23.548  1032  1094 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
09-12 14:43:23.550  1032  1032 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
09-12 14:43:23.550  6889  7410 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-12 14:43:23.550  6889  7410 W bt-smp  : Plain text(LSB ~ MSB) = 27 46 4e 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-12 14:43:23.550  6889  7410 W bt-smp  : Encrypted text(LSB ~ MSB) = ed 31 8c 2e fe bb e2 ee d9 9b 4c 94 e3 bf 7f bb 
09-12 14:43:23.550  6889  7410 W bt-btm  : Stopping oneshot timer
09-12 14:43:23.551  1599  1599 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-12 14:43:23.551  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-12 14:43:23.551  1941  2276 D LGBluetoothAPIService: Message: 1
09-12 14:43:23.551  1941  2276 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
09-12 14:43:23.552  1032  1094 D BluetoothManagerService: Message: 40
09-12 14:43:23.552  1032  1094 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
09-12 14:43:23.556  6669  6669 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
,09-12 14:43:23.559  6889  6889 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-12 14:43:23.559  6889  6889 D BluetoothMapService: STATE_ON
09-12 14:43:23.560  7476  7476 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
09-12 14:43:23.561  6889  6889 D LGBluetoothAPIServer: [BTUI] onCreate()
09-12 14:43:23.561  6889  6889 D LGBluetoothAPIServer: [BTUI] onBind()
09-12 14:43:23.562  6889  7410 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-12 14:43:23.562  6889  7410 W bt-smp  : Plain text(LSB ~ MSB) = 63 e5 79 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-12 14:43:23.562  6889  7410 W bt-smp  : Encrypted text(LSB ~ MSB) = 27 56 da d8 ff dd eb 0c e0 7c 78 e0 ae 68 13 53 
09-12 14:43:23.562  6889  6889 V BluetoothMapService: Handler(): got msg=1
09-12 14:43:23.562  6889  7410 W bt-btm  : Stopping oneshot timer
09-12 14:43:23.563  6889  6889 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
09-12 14:43:23.563  1941  1941 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
09-12 14:43:23.563  1941  2276 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
09-12 14:43:23.563  1941  2276 D LGBluetoothAPIService: Message: 100
09-12 14:43:23.563  1941  2276 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
09-12 14:43:23.564  6738  6738 D LocalBluetoothProfileManager: Adding local A2DP profile
09-12 14:43:23.564  6889  7478 D BluetoothMapMasInstance: MAS initSocket()
09-12 14:43:23.565  6889  7478 D BluetoothMapMasInstance:   masId = 00
09-12 14:43:23.565  6889  7478 D BluetoothMapMasInstance:   msgTypes = 0e
09-12 14:43:23.565  6889  7478 D BluetoothMapMasInstance:   masName = SMS/MMS
09-12 14:43:23.565  6889  7478 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
09-12 14:43:23.566  1032  1997 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 14:43:23.567  6889  7478 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 14:43:23.567  1032  1094 D BluetoothManagerService: Message: 30
09-12 14:43:23.568  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 14:43:23.568  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 14:43:23.568  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 14:43:23.568  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 14:43:23.568  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 14:43:23.568  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 14:43:23.568  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 14:43:23.568  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 14:43:23.570  6889  7478 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
09-12 14:43:23.570  6889  7478 V BluetoothMapMasInstance: Succeed to create listening socket 
09-12 14:43:23.570  6889  7478 D BluetoothMapMasInstance: Accepting socket connection...
09-12 14:43:23.572  6738  6738 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-12 14:43:23.572  6889  7344 D BluetoothAdapterProperties: Scan Mode:21
09-12 14:43:23.572  6669  6669 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 14:43:23.572  6889  7344 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
09-12 14:43:23.575  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 14:43:23.575  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 14:43:23.575  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 14:43:23.575  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 14:43:23.575  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 14:43:23.575  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 14:43:23.575  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 14:43:23.575  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 14:43:23.576  1032  1094 D BluetoothManagerService: Message: 30
09-12 14:43:23.577  6669  6669 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 14:43:23.578  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 14:43:23.580  6889  6889 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@153cf9fb
09-12 14:43:23.580  6889  6889 V BluetoothPbapService: Pbap Service onCreate
09-12 14:43:23.581  6889  6889 V BluetoothPbapService: Starting PBAP service
09-12 14:43:23.582  6889  6889 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
09-12 14:43:23.582  6889  6889 V BluetoothPbapService: Pbap Service onBind
,09-12 14:43:23.582  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 14:43:23.583  6889  6889 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-12 14:43:23.583  6889  6889 V BluetoothPbapService: state: 12
09-12 14:43:23.583  6889  6889 V BluetoothPbapService: Handler(): got msg=1
09-12 14:43:23.583  6738  6738 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
09-12 14:43:23.583  6889  6889 V BluetoothPbapService: Pbap Service startRfcommSocketListener
09-12 14:43:23.584  6889  7479 V BluetoothPbapService: Pbap Service initSocket
09-12 14:43:23.585  1032  1940 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 14:43:23.585  6738  6738 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-12 14:43:23.587  6889  7479 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 14:43:23.588  6738  6738 D BluetoothA2dp: Proxy object connected
09-12 14:43:23.588  6889  6889 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-12 14:43:23.588  6889  6889 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-12 14:43:23.588  6889  6889 V BluetoothPbapReceiver: ***********state = 12
09-12 14:43:23.588  6738  6738 D A2dpProfile: Bluetooth service connected
09-12 14:43:23.589  6889  7479 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
09-12 14:43:23.589  6889  7479 V BluetoothPbapService: Succeed to create listening socket 
09-12 14:43:23.589  6889  7479 V BluetoothPbapService: Accepting socket connection...
09-12 14:43:23.591  6738  6738 D BluetoothHeadset: Proxy object connected
09-12 14:43:23.591  2208  2208 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-12 14:43:23.591  2208  2208 D c       : Getting all permits...
09-12 14:43:23.591  2208  2208 D a       : Opening database...
09-12 14:43:23.592  6738  6738 D HeadsetProfile: Bluetooth service connected
09-12 14:43:23.593  6738  6738 D BluetoothPbap: Proxy object connected
09-12 14:43:23.593  6738  6738 D PbapServerProfile: Bluetooth service connected
,09-12 14:43:23.594  2208  2208 D a       : Opening database auth.proximity.permit_store...
09-12 14:43:23.595  2208  2208 D a       : Closing database...
09-12 14:43:23.596  6738  6738 D DockEventReceiver: finishStartingService: stopping service
09-12 14:43:23.606  6738  6738 D BluetoothPermissionRequest: onReceive
,09-12 14:43:23.608  6738  6738 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-12 14:43:23.609  6738  6738 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-12 14:43:23.611  6889  6889 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
09-12 14:43:23.612  6889  6889 I LGBluetoothOppAdapter: [BTUI] startOppService()
09-12 14:43:23.618  6889  6889 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,09-12 14:43:23.637  6889  6889 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,09-12 14:43:23.637  6889  6889 V BtOppService: onCreate
,09-12 14:43:23.642  6889  6889 V BluetoothOppNotification: send message
09-12 14:43:23.648  6889  6889 V BtOppService: Starting RfcommListener
,09-12 14:43:23.654  6889  7484 V BtOppService: Deleted complete outbound shares, number =  0
09-12 14:43:23.655  6889  6889 D BluetoothOppPreference: Dumping Names:  
09-12 14:43:23.655  6889  6889 D BluetoothOppPreference: {}
09-12 14:43:23.655  6889  6889 D BluetoothOppPreference: Dumping Channels:  
09-12 14:43:23.655  6889  6889 D BluetoothOppPreference: {}
09-12 14:43:23.656  6889  6889 V BtOppService: onStartCommand
09-12 14:43:23.657  6889  7484 V BtOppService: Deleted complete inbound failed shares, number = 0
09-12 14:43:23.659  6889  7484 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
09-12 14:43:23.660  6889  7484 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@268c2a54 on behalf of 
09-12 14:43:23.662  6889  7487 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-12 14:43:23.662  6889  7487 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
,09-12 14:43:23.665  6889  6889 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-12 14:43:23.665  6889  6889 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-12 14:43:23.666  6889  7487 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2f8bcdfd on behalf of 
09-12 14:43:23.667  6889  7487 V BluetoothOppNotification: update too frequent, put in queue
09-12 14:43:23.668  6889  7487 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-12 14:43:23.669  6889  6889 V BluetoothOppNotification: new notify threadi!
09-12 14:43:23.670  6889  6889 V BluetoothOppNotification: send delay message
09-12 14:43:23.670  6889  6889 V BtOppService: start RfcommListener
09-12 14:43:23.673  6889  7488 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-12 14:43:23.674  6889  6889 V BtOppService: RfcommListener started
09-12 14:43:23.674  6889  6889 V BtOppService: ContentObserver received notification
09-12 14:43:23.675  6889  7489 V BtOppRfcommListener: Starting RFCOMM listener....
09-12 14:43:23.675  6889  6889 V BtOppService: ContentObserver received notification
,09-12 14:43:23.677  1032  1940 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-12 14:43:23.677  6889  7490 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-12 14:43:23.678  6889  7490 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-12 14:43:23.678  6889  7489 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 14:43:23.678  6889  7488 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@25f7faf2 on behalf of 
09-12 14:43:23.680  6889  7490 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@237c543 on behalf of 
09-12 14:43:23.680  6889  7488 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-12 14:43:23.681  6889  7490 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-12 14:43:23.682  6889  7489 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
09-12 14:43:23.682  6889  7488 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-12 14:43:23.684  6889  7488 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@4ab97c0 on behalf of 
09-12 14:43:23.685  6889  7489 V BtOppRfcommListener: Started RFCOMM listener....
09-12 14:43:23.685  6889  7489 I BtOppRfcommListener: Accept thread started.
09-12 14:43:23.685  6889  7489 V BtOppRfcommListener: Accepting connection...
09-12 14:43:23.688  6889  7488 V BluetoothOppNotification: outbound: succ-0  fail-0
,09-12 14:43:23.690  6889  7488 V BluetoothOppNotification: outbound notification was removed.
,09-12 14:43:23.691  6889  7488 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-12 14:43:23.694  6889  7488 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@23cc4cf9 on behalf of 
09-12 14:43:23.695  6889  6889 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@153cf9fb
09-12 14:43:23.696  6889  6889 V BluetoothFtpService: Ftp Service onCreate
09-12 14:43:23.696  6889  6889 I BluetoothFtpService: Ftp Service onCreate
09-12 14:43:23.696  6889  6889 V BluetoothFtpService: Ftp Service onStartCommand
09-12 14:43:23.697  6889  6889 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-12 14:43:23.697  6889  6889 V BluetoothFtpService: Starting Listening on sockets
09-12 14:43:23.697  6889  7488 V BluetoothOppNotification: inbound: succ-0  fail-0
09-12 14:43:23.698  6889  6889 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-12 14:43:23.698  6889  6889 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-12 14:43:23.698  6889  6889 V BluetoothSapReceiver: SapReceiver onReceive 
09-12 14:43:23.698  6889  6889 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-12 14:43:23.698  6889  6889 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
09-12 14:43:23.699  6889  6889 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-12 14:43:23.699  6889  7488 V BluetoothOppNotification: inbound notification was removed.
09-12 14:43:23.699  6889  7488 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-12 14:43:23.701  6889  6889 V BluetoothFtpService: Handler(): got msg=1
,09-12 14:43:23.702  6889  6889 V BluetoothFtpService: Ftp Service startRfcommSocketListener
09-12 14:43:23.702  6889  6889 V BluetoothFtpService: Ftp Service initSocket
09-12 14:43:23.708  6889  7488 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1087729f on behalf of 
09-12 14:43:23.710  1032  1932 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 14:43:23.711  6889  6889 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 14:43:23.712  6889  6889 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=78
09-12 14:43:23.712  6889  6889 V BluetoothFtpService: Succeed to create listening socket on channel 20
09-12 14:43:23.714  6889  7491 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
,09-12 14:43:23.728  6889  6889 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@153cf9fb
,09-12 14:43:23.729  6889  6889 V BluetoothSapService: Sap Service onCreate
09-12 14:43:23.731  6889  6889 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-12 14:43:23.731  6889  6889 V BluetoothSapService: state: 12
09-12 14:43:23.732  6889  6889 V BluetoothSapService: Starting SAP server process
09-12 14:43:23.734  6889  6889 V BluetoothSapService: SAP Service startRfcommListenerThread
09-12 14:43:23.721  7492  7492 W sapd    : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-12 14:43:23.721  7492  7492 W sapd    : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-12 14:43:23.735  6889  7493 V BluetoothSapService: Sap Service initRfcommSocket
09-12 14:43:23.736  1032  1940 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 14:43:23.737  6889  7493 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 14:43:23.740  6889  7493 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
09-12 14:43:23.741  6889  7493 V BluetoothSapService: Succeed to create listening socket 
09-12 14:43:23.741  6889  7493 V BluetoothSapService: Accepting socket connection...
,09-12 14:43:23.761  7492  7492 V BT_SAP  : Event pipe created
,09-12 14:43:23.761  7492  7492 V BT_SAP  : create_server_socket qcom.sap.server
09-12 14:43:23.761  7492  7492 V BT_SAP  : created socket fd 6
,09-12 14:43:24.184  1032  1997 I ActivityManager: Killing 7269:com.lge.bnr/1000 (adj 15): empty #17
,09-12 14:43:24.219  1032  1966 W libprocessgroup: failed to open /acct/uid_1000/pid_7269/cgroup.procs: No such file or directory
,09-12 14:43:24.316  1032  1387 D LGWifiP2pService: P2pDisabledState{ when=-2ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,09-12 14:43:24.316  1032  1387 D LGWifiP2pService: DefaultState{ when=-2ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,09-12 14:43:24.363  1032  1396 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
,09-12 14:43:24.365  1032  1396 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,09-12 14:43:24.465  1032  1774 I ActivityManager: Killing 6550:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,09-12 14:43:24.489  6811  6811 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
09-12 14:43:24.490  6811  6811 W System.err: android.os.DeadObjectException
09-12 14:43:24.490  6811  6811 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-12 14:43:24.490  6811  6811 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-12 14:43:24.490  6811  6811 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
09-12 14:43:24.490  6811  6811 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
09-12 14:43:24.490  6811  6811 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-12 14:43:24.490  6811  6811 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-12 14:43:24.490  6811  6811 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-12 14:43:24.490  6811  6811 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-12 14:43:24.490  6811  6811 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-12 14:43:24.490  6811  6811 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-12 14:43:24.490  6811  6811 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 14:43:24.491  6811  6811 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 14:43:24.491  6811  6811 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-12 14:43:24.491  6811  6811 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-12 14:43:24.491  6811  6811 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
09-12 14:43:24.491  6811  6811 W System.err: android.os.DeadObjectException
09-12 14:43:24.491  6811  6811 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-12 14:43:24.491  6811  6811 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-12 14:43:24.491  6811  6811 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
09-12 14:43:24.491  6811  6811 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
09-12 14:43:24.491  6811  6811 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-12 14:43:24.491  6811  6811 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-12 14:43:24.492  6811  6811 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-12 14:43:24.492  6811  6811 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-12 14:43:24.492  6811  6811 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-12 14:43:24.492  6811  6811 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-12 14:43:24.492  6811  6811 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 14:43:24.492  6811  6811 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 14:43:24.492  6811  6811 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-12 14:43:24.492  6811  6811 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-12 14:43:24.492  6811  6811 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
09-12 14:43:24.492  6811  6811 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,09-12 14:43:24.526  1032  1904 W libprocessgroup: failed to open /acct/uid_1000/pid_6550/cgroup.procs: No such file or directory
,09-12 14:43:24.526  1032  1904 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,09-12 14:43:24.546  6811  6811 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
09-12 14:43:24.546  6811  6811 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,09-12 14:43:24.602  1032  1650 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7503 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-12 14:43:24.657  6811  6811 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
09-12 14:43:24.671  6889  6889 V BluetoothOppNotification: new notify threadi!
09-12 14:43:24.671  6889  6889 V BluetoothOppNotification: send delay message
,09-12 14:43:24.685  6889  7520 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,09-12 14:43:24.711  6889  7520 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@22fa99bb on behalf of 
,09-12 14:43:24.717  6889  7520 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-12 14:43:24.719  6889  7520 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-12 14:43:24.721  6889  7520 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@212c9ed8 on behalf of 
09-12 14:43:24.722  6889  7520 V BluetoothOppNotification: outbound: succ-0  fail-0
09-12 14:43:24.727  6889  7520 V BluetoothOppNotification: outbound notification was removed.
09-12 14:43:24.728  6889  7520 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
,09-12 14:43:24.730  6889  7520 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2b75a231 on behalf of 
,09-12 14:43:24.731  6889  7520 V BluetoothOppNotification: inbound: succ-0  fail-0
09-12 14:43:24.733  6889  7520 V BluetoothOppNotification: inbound notification was removed.
09-12 14:43:24.733  6889  7520 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-12 14:43:24.734  6889  7520 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3b672d16 on behalf of 
09-12 14:43:24.822  1032  1976 I art     : Explicit concurrent mark sweep GC freed 93475(4MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 1.844ms total 160.729ms
,09-12 14:43:24.865  7503  7503 D UEI.SmartControl: Quickset Services start...
,09-12 14:43:24.867  7503  7503 I UEI.SmartControl: Manufacture = LGE
09-12 14:43:24.868  7503  7503 D UEI.SmartControl: Id = LGNevo
,09-12 14:43:24.870  7503  7503 D UEI.SmartControl: File observer start...
09-12 14:43:24.870  7503  7503 E UEI.SmartControl: IR Port is disabled: false
09-12 14:43:24.871  7503  7503 D UEI.SmartControl: Starting file observer...
09-12 14:43:24.871  7503  7503 D UEI.SmartControl: Extracting JNI libs...
09-12 14:43:24.871  7503  7503 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
09-12 14:43:24.963  7503  7503 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
09-12 14:43:24.964  7503  7503 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
09-12 14:43:24.964  7503  7503 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,09-12 14:43:25.031  7503  7503 I UEI.SmartControl: --- Selecting new region: 6
,09-12 14:43:25.034  7503  7503 I UEI.SmartControl: Model = LG-D855
09-12 14:43:25.036  7503  7503 D UEI.SmartControl: QS Service created
09-12 14:43:25.056  7503  7503 I UEI.SmartControl: Service initServices...
,09-12 14:43:25.062  7503  7503 D UEI.SmartControl: QS start get config
09-12 14:43:25.122  7503  7503 D UEI.SmartControl: Loading JNI Libs...
,09-12 14:43:25.311  1032  1650 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 14:43:25.312  1032  1650 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@2b0d515d mBinding = false
,09-12 14:43:25.336  1032  1032 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-12 14:43:25.336  1032  1032 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,09-12 14:43:25.336  1032  1032 D Ulp_jni : JNI:system_update. Event-4
09-12 14:43:25.337  1032  1094 D BluetoothManagerService: Message: 2
09-12 14:43:25.339  1032  1094 D BluetoothManagerService: Sending off request.
09-12 14:43:25.340  6889  6904 D LGBluetoothServiceAdapter: [BTUI] Precleanup
09-12 14:43:25.341  6889  7340 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
09-12 14:43:25.341  6889  7340 D BluetoothAdapterProperties: Setting state to 13
09-12 14:43:25.341  6889  7340 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-12 14:43:25.341  6889  7340 D BluetoothAdapterProperties: onBluetoothDisable()
09-12 14:43:25.342  6889  7340 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-12 14:43:25.343  6889  7344 D BluetoothAdapterProperties: Scan Mode:20
09-12 14:43:25.343  6889  7340 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-12 14:43:25.344  6889  7340 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-12 14:43:25.344  6889  7478 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
09-12 14:43:25.344  6889  7478 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-12 14:43:25.344  6889  7478 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
09-12 14:43:25.344  6889  7478 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
09-12 14:43:25.344  6889  7478 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
09-12 14:43:25.344  6889  7478 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
09-12 14:43:25.344  6889  7478 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
09-12 14:43:25.344  6889  7478 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
09-12 14:43:25.345  6889  7479 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-12 14:43:25.350  6889  7410 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
,09-12 14:43:25.353  6889  7493 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-12 14:43:25.355  6889  7491 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-12 14:43:25.355  6889  7489 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-12 14:43:25.355  6889  7410 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
09-12 14:43:25.358  6889  7410 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-12 14:43:25.358  6889  7410 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-12 14:43:25.358  6889  7410 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-12 14:43:25.358  6889  7410 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
,09-12 14:43:25.358  6889  7410 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-12 14:43:25.358  6889  7410 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-12 14:43:25.358  6889  7410 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 14:43:25.358  6889  7410 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-12 14:43:25.358  6889  7410 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-12 14:43:25.358  6889  7410 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
09-12 14:43:25.358  6889  7410 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
09-12 14:43:25.358  6889  7410 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-12 14:43:25.359  1032  1094 D BluetoothManagerService: Message: 60
09-12 14:43:25.359  1032  1094 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
09-12 14:43:25.360  1032  1094 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
09-12 14:43:25.363  1599  1599 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-12 14:43:25.365  6889  6889 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-12 14:43:25.365  6889  6889 D BluetoothMapService: STATE_TURNING_OFF
09-12 14:43:25.365  6889  6889 V BluetoothMapService: Handler(): got msg=4
09-12 14:43:25.365  6889  6889 D BluetoothMapService: MAP Service closeService in
09-12 14:43:25.365  6889  6889 D BluetoothMapMasInstance: MAP Service shutdown
09-12 14:43:25.365  6889  6889 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-12 14:43:25.365  6889  6889 V BluetoothMapService: MAP Service closeService out
09-12 14:43:25.366  6889  6889 V BtOppService: Receiver DISABLED_ACTION 
,09-12 14:43:25.366  6889  6889 I BtOppRfcommListener: stopping Accept Thread
09-12 14:43:25.366  6889  6889 V BtOppRfcommListener: close mBtServerSocket
09-12 14:43:25.366  6889  6889 V BtOppRfcommListener: waiting for thread to terminate
09-12 14:43:25.366  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-12 14:43:25.367  6669  6669 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 14:43:25.367  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 14:43:25.367  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 14:43:25.367  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 14:43:25.367  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 14:43:25.367  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 14:43:25.367  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 14:43:25.367  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 14:43:25.367  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 14:43:25.367  6889  7489 I BtOppRfcommListener: BluetoothSocket listen thread finished,
,09-12 14:43:25.368  6889  6889 V BtOppRfcommListener: done waiting for thread to terminate
09-12 14:43:25.369  6889  6889 V BtOppService: onDestroy
09-12 14:43:25.369  6669  6669 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 14:43:25.369  6669  6669 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 14:43:25.370  6889  6889 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
09-12 14:43:25.372  6669  6669 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 14:43:25.372  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 14:43:25.372  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 14:43:25.372  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 14:43:25.372  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 14:43:25.372  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 14:43:25.372  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 14:43:25.372  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 14:43:25.372  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 14:43:25.372  6669  6669 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 14:43:25.372  6669  6669 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 14:43:25.372  6738  6738 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
09-12 14:43:25.373  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 14:43:25.374  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 14:43:25.378  6738  6738 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,09-12 14:43:25.387  6889  6889 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-12 14:43:25.387  6889  6889 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-12 14:43:25.387  6889  6889 V BluetoothPbapReceiver: ***********state = 13
09-12 14:43:25.388  6889  6889 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
09-12 14:43:25.390  6889  6889 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-12 14:43:25.390  6889  6889 V BluetoothPbapService: state: 13
09-12 14:43:25.390  6889  6889 V BluetoothPbapService: Pbap Service closeService in
09-12 14:43:25.391  6889  6889 V BluetoothPbapService: successfully stopped pbap service
09-12 14:43:25.391  6889  6889 V BluetoothPbapService: Pbap Service closeService out
09-12 14:43:25.391  6889  6889 V BluetoothPbapService: Pbap Service onDestroy
09-12 14:43:25.391  6889  6889 V BluetoothPbapService: Pbap Service closeService in
09-12 14:43:25.391  6889  6889 V BluetoothPbapService: Pbap Service closeService out
09-12 14:43:25.391  6889  6889 D LGBluetoothPbapAdapter: [BTUI] cleanup
09-12 14:43:25.392  2208  2208 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-12 14:43:25.402  6738  6738 D DockEventReceiver: finishStartingService: stopping service
09-12 14:43:25.403  6738  6738 D BluetoothPbap: Proxy object disconnected
09-12 14:43:25.403  6738  6738 D PbapServerProfile: Bluetooth service disconnected
09-12 14:43:25.406  6738  6738 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,09-12 14:43:25.410  6738  6738 D BluetoothPermissionRequest: onReceive
09-12 14:43:25.410  6738  6738 D LGBluetoothAuthorization: [BTUI] cancel All Notification
09-12 14:43:25.414  6738  6738 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-12 14:43:25.418  6889  6889 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
,09-12 14:43:25.418  6889  6889 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
09-12 14:43:25.420  6889  6889 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
09-12 14:43:25.423  6889  6889 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-12 14:43:25.423  6889  6889 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-12 14:43:25.423  6889  6889 V BluetoothFtpService: Ftp Service onStartCommand
09-12 14:43:25.423  6889  6889 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-12 14:43:25.424  6889  6889 V BluetoothFtpService: Ftp Service closeService
09-12 14:43:25.424  6889  6889 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
09-12 14:43:25.425  6889  6889 V BluetoothFtpService: successfully stopped ftp service
09-12 14:43:25.425  6889  6889 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-12 14:43:25.425  6889  6889 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-12 14:43:25.425  6889  6889 V BluetoothSapReceiver: SapReceiver onReceive 
09-12 14:43:25.425  6889  6889 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-12 14:43:25.425  6889  6889 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
09-12 14:43:25.425  6889  6889 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-12 14:43:25.426  6889  6889 V BluetoothFtpService: Ftp Service onDestroy
09-12 14:43:25.426  6889  6889 V BluetoothFtpService: Ftp Service closeService
09-12 14:43:25.429  6889  6889 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-12 14:43:25.429  6889  6889 V BluetoothSapService: state: 13
09-12 14:43:25.429  6889  6889 V BluetoothSapService: Stopping SAP server process
09-12 14:43:25.429  6889  6889 V BluetoothSapService: Sap Service closeSapService in
09-12 14:43:25.430  6889  6889 V BluetoothSapService: Close listen Socket : 
09-12 14:43:25.430  6889  6889 V BluetoothSapService: Close rfcomm Socket : 
09-12 14:43:25.430  6889  6889 V BluetoothSapService: Close sapd  Socket : 
09-12 14:43:25.432  6889  6889 V BluetoothSapService: Sap Service closeSapService out
09-12 14:43:25.432  6889  6889 V BluetoothSapService: Sap Service onDestroy
09-12 14:43:25.432  6889  6889 V BluetoothSapService: Sap Service closeSapService in
09-12 14:43:25.432  6889  6889 V BluetoothSapService: Close listen Socket : 
09-12 14:43:25.432  6889  6889 V BluetoothSapService: Close rfcomm Socket : 
09-12 14:43:25.432  6889  6889 V BluetoothSapService: Close sapd  Socket : 
,09-12 14:43:25.433  6889  6889 V BluetoothSapService: Sap Service closeSapService out
,09-12 14:43:25.465  7503  7503 I UEI.SmartControl: Supports setup maps: true
09-12 14:43:25.468  7503  7503 D UEI.SmartControl: QS start statue = true Error code = 0
09-12 14:43:25.468  7503  7503 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-12 14:43:25.468  7503  7503 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
,09-12 14:43:25.468  7503  7503 I UEI.SmartControl: ### init IR Blaster...
,09-12 14:43:25.472  7503  7503 D serial_port: Configuring serial port
09-12 14:43:25.475  7503  7503 E UEI.SmartControl: UEIBLaster setting for 616
09-12 14:43:25.475  7503  7503 I UEI.SmartControl: Setting serial record hearder size = 2
09-12 14:43:25.475  7503  7503 I UEI.SmartControl: configuring settings for MAXQ616
09-12 14:43:25.475  7503  7503 I UEI.SmartControl: Get version...
09-12 14:43:25.491  7503  7557 D UEI.SmartControl: serial port data available: 21
,09-12 14:43:25.518  7503  7503 D UEI.SmartControl: MAXQ616 A2-X4 software.
09-12 14:43:25.518  7503  7503 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-12 14:43:25.519  7503  7503 I UEI.SmartControl: QS saving settings...
09-12 14:43:25.520  7503  7503 D UEI.SmartControl: IR Blaster version: 25672567
,09-12 14:43:25.536  7503  7557 D UEI.SmartControl: serial port data available: 4
,09-12 14:43:25.577  7503  7561 I UEI.SmartControl: Device manager: loading config....
09-12 14:43:25.577  7503  7503 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
09-12 14:43:25.578  7503  7561 D UEI.SmartControl: ----------- loading internal config...
09-12 14:43:25.580  7503  7503 E UEI.SmartControl: Services init done
09-12 14:43:25.580  7503  7503 D UEI.SmartControl: QS Service init finished
,09-12 14:43:25.586  7503  7503 D UEI.SmartControl: QS Service version name: 2.1.91
,09-12 14:43:25.587  7503  7503 D UEI.SmartControl: QS Service version code: 201091
09-12 14:43:25.588  7503  7503 D UEI.SmartControl: Service requested: Control
09-12 14:43:25.594  7503  7503 D UEI.SmartControl: Request IControl service: devices are loaded...
09-12 14:43:25.600  6811  6811 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
,09-12 14:43:25.600  1032  1904 I ActivityManager: Killing 6811:com.lge.qremote/u0a112 (adj 15): empty #17
09-12 14:43:25.600  7503  7561 E UEI.SmartControl: Loading SETTINGS...
09-12 14:43:25.601  7503  7519 I UEI.SmartControl: ------ IControl API: 11
09-12 14:43:25.604  7503  7519 I UEI.SmartControl: Registering callback...
09-12 14:43:25.621  7503  7561 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,09-12 14:43:25.635  7503  7560 I UEI.SmartControl: Notify AllClients services are ready: 0
09-12 14:43:25.635  7503  7560 D UEI.SmartControl: -----service ready thread exits
,09-12 14:43:25.659  1032  1932 W libprocessgroup: failed to open /acct/uid_10112/pid_6811/cgroup.procs: No such file or directory
09-12 14:43:25.661  7503  7503 D UEI.SmartControl: Internal service binding...
,09-12 14:43:26.262  6889  7344 D bt_hci_bdroid: cleanup
,09-12 14:43:26.269  6889  7412 I bt_lpm  : LPM is already off!!!
09-12 14:43:26.272  6889  7410 W bt-btif : ag scb idx 1 not allocated
09-12 14:43:26.272  6889  7410 E bt-btif : BTA AG is already disabled, ignoring ...
09-12 14:43:26.272  6889  7410 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-12 14:43:26.272  6889  7410 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-12 14:43:26.272  6889  7410 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-12 14:43:26.272  6889  7410 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 14:43:26.272  6889  7410 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-12 14:43:26.272  6889  7410 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-12 14:43:26.272  6889  7410 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-12 14:43:26.272  6889  7410 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-12 14:43:26.272  6889  7410 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-12 14:43:26.273  6889  7410 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 14:43:26.273  6889  7410 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-12 14:43:26.273  6889  7410 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-12 14:43:26.273  6889  7410 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-12 14:43:26.273  6889  7410 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-12 14:43:26.273  6889  7410 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-12 14:43:26.273  6889  7410 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 14:43:26.273  6889  7410 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-12 14:43:26.273  6889  7410 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-12 14:43:26.273  6889  7410 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-12 14:43:26.276  6889  7453 I bt_userial_mct: exiting userial_read_thread
09-12 14:43:26.276  6889  7453 D bt_userial_mct: Leaving userial_evt_read_thread()
09-12 14:43:26.279  6889  7344 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
,09-12 14:43:26.282  6889  7412 I bt_vendor: hw_epilog_process
09-12 14:43:26.283  6889  7344 D bt_hci_bdroid: cleanup Finalizing cleanup
09-12 14:43:26.283  6889  7344 D bt_userial_mct: userial_close
09-12 14:43:26.283  6889  7344 E bt_userial_mct: pthread_join() FAILED result:3
09-12 14:43:26.283  6889  7344 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
09-12 14:43:26.289  6889  7344 D bt_hci_bdroid: set_power 0
09-12 14:43:26.289  6889  7344 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-12 14:43:26.289  6889  7344 I bt_vendor: bluetooth satus is on
09-12 14:43:26.289  6889  7344 I bt_vendor: bt-vendor : resetting BT status
09-12 14:43:26.289  6889  7344 I bt_vendor: Starting hciattach daemon
09-12 14:43:26.289  6889  7344 I bt_vendor: try to set false
09-12 14:43:26.291  6889  7344 I bt_vendor: Starting hciattach daemon
09-12 14:43:26.291  6889  7344 I bt_vendor: try to set false
,09-12 14:43:26.296  6889  7344 I bt_vendor: cleanup
09-12 14:43:26.296  6889  7410 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-12 14:43:26.297  6889  7344 I GKI_LINUX: GKI_exit_task 0 done
09-12 14:43:26.297  6889  7344 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
09-12 14:43:26.298  6889  7340 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-12 14:43:26.303  6889  6889 D HeadsetService: Received stop request...Stopping profile...
09-12 14:43:26.304  6889  6889 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-12 14:43:26.304  6889  6889 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-12 14:43:26.304  6889  6889 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@153cf9fb
,09-12 14:43:26.307  6889  7363 D HeadsetStateMachine: Exit Disconnected: -1
09-12 14:43:26.311  1852  1852 D BluetoothHeadset: Proxy object disconnected
09-12 14:43:26.311  1852  1852 D BluetoothHeadset: Proxy object disconnected
09-12 14:43:26.311  1852  1852 D BluetoothHeadset: Proxy object disconnected
09-12 14:43:26.312  1032  1032 D BluetoothHeadset: Proxy object disconnected
09-12 14:43:26.314  1032  1032 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-12 14:43:26.315  6889  6889 D A2dpService: Received stop request...Stopping profile...
09-12 14:43:26.316  6889  7402 D A2dpStateMachine: Exit Disconnected: -1
09-12 14:43:26.319  6889  6889 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
,09-12 14:43:26.323  6889  6889 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
09-12 14:43:26.323  6889  6889 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
09-12 14:43:26.323  6889  6889 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@153cf9fb
09-12 14:43:26.326  1032  1032 D BluetoothA2dp: Proxy object disconnected
09-12 14:43:26.326  1032  1032 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-12 14:43:26.326  6889  7340 D BluetoothAdapterState: Stopping profile services that were post enabled
09-12 14:43:26.327  6889  6889 D HidService: Received stop request...Stopping profile...
09-12 14:43:26.327  6889  6889 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@153cf9fb
09-12 14:43:26.329  6889  6889 D HeadsetStateMachine: Unbinding service...
09-12 14:43:26.331  6889  6889 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-12 14:43:26.331  6889  6889 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-12 14:43:26.331  6889  6889 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-12 14:43:26.332  6889  6889 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-12 14:43:26.332  6889  6889 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-12 14:43:26.332  6889  6889 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-12 14:43:26.332  6889  6889 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
,09-12 14:43:26.335  6889  6889 D HealthService: Received stop request...Stopping profile...
09-12 14:43:26.335  6889  6889 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@153cf9fb
09-12 14:43:26.337  6889  6889 D PanService: Received stop request...Stopping profile...
09-12 14:43:26.338  6889  6889 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@153cf9fb
09-12 14:43:26.339  6889  6889 D BtGatt.DebugUtils: handleDebugAction() action=null
09-12 14:43:26.340  6889  6889 D BtGatt.GattService: Received stop request...Stopping profile...
09-12 14:43:26.340  6889  6889 D BtGatt.GattService: stop()
09-12 14:43:26.340  6889  6889 D BtGatt.AdvertiseManager: advertise clients cleared
09-12 14:43:26.341  6889  6889 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@153cf9fb
09-12 14:43:26.343  6889  6889 I BluetoothA2dpServiceJni: cleanupNative
,09-12 14:43:26.345  6889  7403 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-12 14:43:26.345  6889  6889 I GKI_LINUX: GKI_exit_task 2 done
09-12 14:43:26.346  6889  6889 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-12 14:43:26.347  6889  6889 D BluetoothMapService: Received stop request...Stopping profile...
09-12 14:43:26.347  6889  6889 D BluetoothMapService: stop()
09-12 14:43:26.348  6889  6889 D BluetoothMapEmailAppObserver: deinitObservers()
09-12 14:43:26.348  6889  6889 D BluetoothMapEmailAppObserver: removeReceiver()
09-12 14:43:26.349  6889  6889 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@153cf9fb
09-12 14:43:26.350  6889  6889 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-12 14:43:26.350  6889  6889 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-12 14:43:26.350  6889  6889 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-12 14:43:26.351  6889  6889 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-12 14:43:26.351  6889  6889 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-12 14:43:26.351  6889  6889 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-12 14:43:26.351  6889  6889 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-12 14:43:26.352  6889  6889 V BluetoothMapService: Handler(): got msg=4
09-12 14:43:26.352  6889  6889 D BluetoothMapService: MAP Service closeService in
09-12 14:43:26.352  6889  6889 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-12 14:43:26.352  6889  6889 V BluetoothMapService: MAP Service closeService out
09-12 14:43:26.353  6889  7340 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
09-12 14:43:26.353  6889  7340 D BluetoothAdapterProperties: Setting state to 10
09-12 14:43:26.353  6889  7340 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-12 14:43:26.355  1032  1094 D BluetoothManagerService: Message: 60
09-12 14:43:26.355  1032  1094 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
09-12 14:43:26.355  1032  1094 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
09-12 14:43:26.355  1032  1094 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-12 14:43:26.360  6889  7340 I BluetoothAdapterState: Entering OffState
09-12 14:43:26.362  6738  6755 D BluetoothMap: onBluetoothStateChange: up=false
09-12 14:43:26.364  6889  6889 D BluetoothMapService: cleanup()
09-12 14:43:26.364  6889  6889 D BluetoothMapService: MAP Service closeService in
09-12 14:43:26.364  6889  6889 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-12 14:43:26.364  6889  6889 V BluetoothMapService: MAP Service closeService out
09-12 14:43:26.365  6738  6755 D BluetoothA2dp: onBluetoothStateChange: up=false
09-12 14:43:26.367  6738  6755 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-12 14:43:26.369  6738  6755 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-12 14:43:26.370  1032  1094 D BluetoothA2dp: onBluetoothStateChange: up=false
09-12 14:43:26.370  1852  1867 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 14:43:26.371  1852  1868 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 14:43:26.371  6738  6755 D BluetoothPbap: onBluetoothStateChange: up=false
09-12 14:43:26.372  1852  3986 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 14:43:26.372  6738  6755 D BluetoothPan: onBluetoothStateChange on: false
09-12 14:43:26.373  1032  1094 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
09-12 14:43:26.373  1032  1094 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
09-12 14:43:26.375  1032  1094 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
09-12 14:43:26.375  1032  1094 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
09-12 14:43:26.375  1032  1094 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@2b0d515d mBinding = false
09-12 14:43:26.376  1032  1094 D BluetoothManagerService: Sending unbind request.
09-12 14:43:26.380  6889  7344 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,09-12 14:43:26.384  6889  6889 I GKI_LINUX: GKI_exit_task 1 done
09-12 14:43:26.384  6889  6889 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
09-12 14:43:26.384  6889  6889 I BluetoothServiceJni: cleanupNative: return from cleanup
09-12 14:43:26.384  6889  6889 I art     : --- WEIRD: removing null entry 248
09-12 14:43:26.384  6889  6889 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
09-12 14:43:26.384  6889  6889 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
09-12 14:43:26.385  6889  6889 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
09-12 14:43:26.387  1032  1094 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
09-12 14:43:26.389  6889  6889 I art     : System.exit called, status: 0
09-12 14:43:26.389  6889  6889 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
09-12 14:43:26.408   311   311 V AudioFlinger: 6889 died, releasing its sessions
09-12 14:43:26.408   311   311 V AudioFlinger:  pid 1852 @ 0
09-12 14:43:26.408   311   311 V AudioFlinger:  pid 3309 @ 1
09-12 14:43:26.408   311   311 V AudioFlinger:  pid 3309 @ 2
,09-12 14:43:26.412  1941  1941 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
09-12 14:43:26.412  1941  2276 D LGBluetoothAPIService: Message: 101
09-12 14:43:26.413  1941  2276 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
09-12 14:43:26.413  1941  2276 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
09-12 14:43:26.413  1941  2276 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
09-12 14:43:26.414  6738  6738 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
09-12 14:43:26.420  1032  1572 I ActivityManager: Process com.android.bluetooth (pid 6889) has died
09-12 14:43:26.420  1032  1572 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms
09-12 14:43:26.421  1032  1572 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 14000ms
,09-12 14:43:26.431  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-12 14:43:26.431  1941  2276 D LGBluetoothAPIService: Message: 2
09-12 14:43:26.431  1941  2276 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
09-12 14:43:26.432  1599  1599 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,09-12 14:43:26.434  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 14:43:26.435  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 14:43:26.436  6738  6738 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
09-12 14:43:26.436  6738  6738 D LGBluetoothEventManager: [BTUI] clear device connection state
09-12 14:43:26.438  6738  6738 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-12 14:43:26.446  1599  1599 D BluetoothAdapter: 848992557: getState() :  mService = null. Returning STATE_OFF
09-12 14:43:26.446  1599  1599 D BluetoothAdapter: 848992557: getState() :  mService = null. Returning STATE_OFF
09-12 14:43:26.488  1032  1932 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7591 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,09-12 14:43:26.492  6738  6738 D DockEventReceiver: finishStartingService: stopping service
,09-12 14:43:26.545  7591  7591 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
09-12 14:43:26.545  7591  7591 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-12 14:43:26.546  7591  7591 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
09-12 14:43:26.546  7591  7591 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-12 14:43:26.574  7591  7591 D BluetoothAdapterApp: Loading JNI Library
,09-12 14:43:26.611  7591  7591 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@21a75d83 Instance Count = 1
,09-12 14:43:26.617  7591  7591 D BluetoothAdapterApp: onCreate
09-12 14:43:26.642  7591  7591 D ProfileConfigQcom: [BTUI] HeadsetService is supported
09-12 14:43:26.642  7591  7591 D ProfileConfigQcom: Adding HeadsetService
09-12 14:43:26.643  7591  7591 D ProfileConfigQcom: [BTUI] A2dpService is supported
09-12 14:43:26.643  7591  7591 D ProfileConfigQcom: Adding A2dpService
09-12 14:43:26.643  7591  7591 D ProfileConfigQcom: [BTUI] HidService is supported
09-12 14:43:26.643  7591  7591 D ProfileConfigQcom: Adding HidService
09-12 14:43:26.643  7591  7591 D ProfileConfigQcom: [BTUI] HealthService is supported
,09-12 14:43:26.644  7591  7591 D ProfileConfigQcom: Adding HealthService
09-12 14:43:26.644  7591  7591 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
09-12 14:43:26.645  7591  7591 D ProfileConfigQcom: [BTUI] PanService is supported
09-12 14:43:26.646  7591  7591 D ProfileConfigQcom: Adding PanService
09-12 14:43:26.646  7591  7591 D ProfileConfigQcom: [BTUI] GattService is supported
09-12 14:43:26.646  7591  7591 D ProfileConfigQcom: Adding GattService
09-12 14:43:26.646  7591  7591 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
09-12 14:43:26.646  7591  7591 D ProfileConfigQcom: Adding BluetoothMapService
09-12 14:43:26.647  7591  7591 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
09-12 14:43:26.648  7591  7591 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-12 14:43:26.649  7591  7591 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-12 14:43:26.650  7591  7591 V BluetoothPbapReceiver: ***********state = 10
09-12 14:43:26.651  7591  7591 V LGMDMManagerInternal: Create singleton instance
09-12 14:43:26.720  2208  2208 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-12 14:43:26.735  7591  7591 D LGBluetoothAPIServer: [BTUI] onCreate()
09-12 14:43:26.735  7591  7591 D LGBluetoothAPIServer: [BTUI] onBind()
09-12 14:43:26.736  6738  6738 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
09-12 14:43:26.737  6738  6738 D BluetoothPermissionRequest: onReceive
09-12 14:43:26.738  1941  1941 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
09-12 14:43:26.738  1941  2276 D LGBluetoothAPIService: Message: 100
,09-12 14:43:26.738  1941  2276 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
09-12 14:43:26.744  6738  6738 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-12 14:43:26.744  6738  6738 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
09-12 14:43:26.748  6738  6738 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-12 14:43:26.759  7591  7591 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,09-12 14:43:26.765  7591  7591 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-12 14:43:26.772  7591  7591 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-12 14:43:26.774  7591  7591 V BluetoothSapReceiver: [BTUI] region:EU country:EU
,09-12 14:43:26.775  7591  7591 V BluetoothSapReceiver: SapReceiver onReceive 
09-12 14:43:26.778  7591  7591 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-12 14:43:26.778  7591  7591 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
09-12 14:43:26.783  6830  6830 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
09-12 14:43:28.303  1599  1599 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,09-12 14:43:28.341  6669  6725 D io.jxcore.node.ConnectivityMonitor: stop
09-12 14:43:28.341  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 14:43:28.378  1032  1378 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-12 14:43:28.415  1032  1090 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7620 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,09-12 14:43:28.452  2032  2032 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,09-12 14:43:28.458  1032  1032 D administrator: Handling package changes for user 0
09-12 14:43:28.468  1599  1599 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
,09-12 14:43:28.471  1599  1599 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,09-12 14:43:28.486  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-12 14:43:28.506  7620  7620 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-12 14:43:28.573  1032  1032 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
,09-12 14:43:28.573  1032  1032 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
09-12 14:43:28.586  7620  7620 D LgDataFeature: LgDataFeature() Constructor: none
09-12 14:43:28.586  7620  7620 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-12 14:43:28.614  1032  1089 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-12 14:43:28.622  1032  1089 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
09-12 14:43:28.629  2032  2032 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
09-12 14:43:28.629  2504  2504 V GmsNetworkLocationProvi: DISABLE
,09-12 14:43:28.655  2504  2504 E GCoreFlp: Bound FusedProviderService with LocationManager
,09-12 14:43:28.656  1032  1089 D LocationProviderProxy: applying state to connected service
,09-12 14:43:28.728  7620  7665 I Babel   : MmsConfig: mnc/mcc: 0/0
09-12 14:43:28.729  7620  7665 I Babel   : MmsConfig.loadMmsSettings
09-12 14:43:28.735  7620  7665 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
09-12 14:43:28.735  7620  7665 I Babel   : MmsConfig.loadFromDatabase
,09-12 14:43:28.751  7620  7665 E Babel   : canonicalizeMccMnc: invalid mccmnc 
09-12 14:43:28.751  7620  7665 I Babel   : MmsConfig.loadFromResources
09-12 14:43:28.755  7620  7620 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 14:43:28.757  7620  7665 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
09-12 14:43:28.759  7620  7665 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,09-12 14:43:28.777  7620  7663 W AudioCapabilities: Unsupported mime audio/evrc
09-12 14:43:28.780  7620  7663 W AudioCapabilities: Unsupported mime audio/qcelp
09-12 14:43:28.785  1816  7668 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
09-12 14:43:28.785  1816  7668 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
,09-12 14:43:28.787  7620  7663 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
09-12 14:43:28.792  6934  6934 I AppUp4:CustModeStarterReceiver: onReceive
,09-12 14:43:28.799  1816  4765 I Icing   : updateResources: need to parse e{com.google.android.gms}
,09-12 14:43:28.799  6934  6934 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@344495f5
09-12 14:43:28.799  6934  6934 D AppUp4:CustFacade: isCustomizationCompleted : false
09-12 14:43:28.799  6934  6934 D AppUp4:CustFacade: isPhone : true
09-12 14:43:28.800  6934  6934 D AppUp4:CustModeStarterReceiver: begin check event
09-12 14:43:28.800  6934  6934 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
09-12 14:43:28.805  7620  7663 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
09-12 14:43:28.807  7620  7663 W AudioCapabilities: Unsupported mime audio/qcelp
09-12 14:43:28.809  7620  7663 W AudioCapabilities: Unsupported mime audio/evrc
09-12 14:43:28.819  7620  7663 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,09-12 14:43:28.822  7620  7663 W VideoCapabilities: Unsupported mime video/divx
09-12 14:43:28.823  7620  7663 W VideoCapabilities: Unsupported mime video/divx311
09-12 14:43:28.825  7620  7663 W VideoCapabilities: Unsupported mime video/divx4
09-12 14:43:28.829  7620  7663 W VideoCapabilities: Unsupported mime video/mp4v-esdp
09-12 14:43:28.840  7620  7663 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-12 14:43:28.843  1032  1904 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7671 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
09-12 14:43:28.845  7620  7663 W AudioCapabilities: Unsupported mime audio/eac3
09-12 14:43:28.846  7620  7663 W AudioCapabilities: Unsupported mime audio/ac3
09-12 14:43:28.847  1032  1966 I ActivityManager: Killing 6766:com.lge.sync/1000 (adj 15): empty #17
09-12 14:43:28.855  7620  7663 W AudioCapabilities: Unsupported mime audio/g726
,09-12 14:43:28.857  1032  1454 D WifiService: Client connection lost with reason: 4
,09-12 14:43:28.858  7620  7663 W AudioCapabilities: Unsupported mime audio/wma-voice
09-12 14:43:28.859  7620  7663 W AudioCapabilities: Unsupported mime audio/x-ms-wma
09-12 14:43:28.859  7620  7663 W AudioCapabilities: Unsupported mime audio/adpcm
09-12 14:43:28.861  7620  7663 W VideoCapabilities: Unsupported mime video/theora
09-12 14:43:28.862  7620  7663 W VideoCapabilities: Unsupported mime video/mjpg
09-12 14:43:28.989  1032  1932 W libprocessgroup: failed to open /acct/uid_1000/pid_6766/cgroup.procs: No such file or directory
,09-12 14:43:29.026  7671  7671 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-12 14:43:29.026  7671  7671 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-12 14:43:29.026  7671  7671 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,09-12 14:43:29.028  7671  7671 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
09-12 14:43:29.028  7671  7671 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-12 14:43:29.113  7671  7671 I SystemConfig: BUILD Country: EU
09-12 14:43:29.113  7671  7671 I SystemConfig: BUILD Operator: OPEN
,09-12 14:43:29.155  1032  1976 I ActivityManager: Killing 6960:com.lge.email/u0a23 (adj 15): empty #17
,09-12 14:43:29.308  1032  1650 W libprocessgroup: failed to open /acct/uid_10023/pid_6960/cgroup.procs: No such file or directory
,09-12 14:43:29.369  1032  1466 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
,09-12 14:43:29.396  1032  1976 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7691 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,09-12 14:43:29.402  7671  7689 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
09-12 14:43:29.402  7671  7689 I SystemConfig: existFile = false
,09-12 14:43:29.402  7671  7689 I SystemConfig: canReadFile = false
09-12 14:43:29.403  7671  7689 I SystemConfig: systemFeature RCS result false
09-12 14:43:29.403  7671  7689 D SystemConfig: refreshRcsSupport() :false
,09-12 14:43:29.486  7691  7691 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-12 14:43:29.487  7691  7691 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-12 14:43:29.487  7691  7691 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
09-12 14:43:29.488  7691  7691 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-12 14:43:29.591  7691  7691 I AppConfig: Total System Memory = 2995761152
,09-12 14:43:29.601  7691  7691 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
09-12 14:43:29.698  1032  2012 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7713 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-12 14:43:29.703  1032  2012 I ActivityManager: Killing 6850:com.lge.formmanager/u0a26 (adj 15): empty #17
09-12 14:43:29.748  1032  1572 W libprocessgroup: failed to open /acct/uid_10026/pid_6850/cgroup.procs: No such file or directory
,09-12 14:43:29.912  7713  7713 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,09-12 14:43:29.991  7713  7713 D LgDataFeature: LgDataFeature() Constructor: none
09-12 14:43:29.991  7713  7713 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-12 14:43:30.048  7713  7713 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,09-12 14:43:30.069  7713  7713 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,09-12 14:43:30.071  7713  7713 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
09-12 14:43:30.103  7713  7713 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-12 14:43:30.104  7713  7713 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,09-12 14:43:30.128  1032  1774 I ActivityManager: Killing 6356:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,09-12 14:43:30.160  1032  1997 W libprocessgroup: failed to open /acct/uid_1000/pid_6356/cgroup.procs: No such file or directory
,09-12 14:43:30.165  3416  4488 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
09-12 14:43:30.167  3416  4488 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@9ac27cb on behalf of 7713
09-12 14:43:30.173  4614  7753 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,09-12 14:43:30.179  7713  7713 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
09-12 14:43:30.217  1032  1049 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7755 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,09-12 14:43:30.251  7713  7713 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,09-12 14:43:30.311  7755  7755 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,09-12 14:43:30.334  7755  7755 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
09-12 14:43:30.334  7755  7755 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
09-12 14:43:30.334  7755  7755 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
09-12 14:43:30.334  7755  7755 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
09-12 14:43:30.334  7755  7755 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
09-12 14:43:30.334  7755  7755 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,09-12 14:43:30.357  1032  2012 I ActivityManager: Killing 6996:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,09-12 14:43:30.390  1032  1572 W libprocessgroup: failed to open /acct/uid_10046/pid_6996/cgroup.procs: No such file or directory
,09-12 14:43:30.559  1032  1940 V SIM_STK : Menu title from STK is T-Mobile
,09-12 14:43:30.575  7503  7562 D UEI.SmartControl: Internal timer expired: 1
,09-12 14:43:30.575  7503  7562 D UEI.SmartControl: unbind internal service
,09-12 14:43:30.582  7503  7503 D UEI.SmartControl: Service.onUnbind: IControl
09-12 14:43:30.583  7503  7503 D UEI.SmartControl: Service.onDestroy
,09-12 14:43:30.583  7503  7503 D UEI.SmartControl: Lock is in USE false
09-12 14:43:30.583  7503  7503 D UEI.SmartControl: unbind internal service
09-12 14:43:30.583  7503  7503 D serial_port: close(fd = 25)
,09-12 14:43:30.587  7503  7503 I UEI.SmartControl: Serial port is closed.
09-12 14:43:30.588  7503  7503 I UEI.SmartControl: Serial port is closed.
09-12 14:43:30.588  7503  7503 D UEI.SmartControl: Blaster closed
09-12 14:43:30.588  7503  7503 D UEI.SmartControl: Shut down QS...
09-12 14:43:30.588  7503  7503 D UEI.SmartControl: Stopping QS lib
09-12 14:43:30.588  7503  7503 D UEI.SmartControl: QS lib stop result = true
09-12 14:43:30.588  7503  7503 D UEI.SmartControl: Stopped QS lib
09-12 14:43:30.589  7503  7503 D UEI.SmartControl: Stopped file observer...
09-12 14:43:30.589  7503  7503 D UEI.SmartControl: QS shutdown complete
09-12 14:43:30.592  4614  7753 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 419 ms] updated apps [took 419 ms] 
,09-12 14:43:31.465  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 14:43:31.465  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@10864cbf added. We now have 6 listener(s),
,09-12 14:43:31.466  6669  6725 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 14:43:31.481  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 14:43:31.481  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f4b0f8c added. We now have 7 listener(s)
09-12 14:43:31.481  6669  6725 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 14:43:31.482  6669  6725 I System.out: IsBluetoothEnabled
09-12 14:43:31.483  1032  1903 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 14:43:31.484  1032  1903 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
09-12 14:43:31.484  1032  1094 D BluetoothManagerService: Message: 2
09-12 14:43:31.488  6669  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 14:43:31.490  1032  1997 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 14:43:31.490  1032  1997 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,09-12 14:43:31.508  1032  1032 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-12 14:43:31.508  1032  1032 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-12 14:43:31.509  1032  1032 D Ulp_jni : JNI:system_update. Event-4
09-12 14:43:31.510  1032  1094 D BluetoothManagerService: Message: 1
09-12 14:43:31.510  1032  1094 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
09-12 14:43:31.536  1032  1094 D BluetoothManagerService: Message: 20
09-12 14:43:31.536  1032  1094 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5bc8852:true
,09-12 14:43:31.540  7591  7591 D BluetoothAdapterState: make
09-12 14:43:31.545  7591  7591 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
09-12 14:43:31.545  7591  7591 I bluedroid-qcom: init
09-12 14:43:31.546  7591  7799 I BluetoothAdapterState: Entering OffState
09-12 14:43:31.547  7591  7591 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-12 14:43:31.547  7591  7591 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-12 14:43:31.547  7591  7591 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-12 14:43:31.547  7591  7591 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-12 14:43:31.547  7591  7591 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
09-12 14:43:31.549  7591  7591 I bluedroid-qcom: get_profile_interface socket
09-12 14:43:31.549  7591  7591 I bluedroid-qcom: get_profile_interface map_client
,09-12 14:43:31.554  7591  7803 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
09-12 14:43:31.556  7591  7803 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
09-12 14:43:31.551  7802  7802 W bdaddr_loader: type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-12 14:43:31.551  7802  7802 W bdaddr_loader: type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-12 14:43:31.566  7802  7802 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
09-12 14:43:31.566  7802  7802 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
09-12 14:43:31.566  7802  7802 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,09-12 14:43:31.571  1032  1032 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-12 14:43:31.571  1032  1032 D BluetoothManagerService: Stored Bluetooth name: G3
09-12 14:43:31.574  1032  1032 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
09-12 14:43:31.574  1032  1094 D BluetoothManagerService: Message: 40
09-12 14:43:31.574  1032  1094 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
09-12 14:43:31.575  7591  7606 I bluedroid-qcom: config_hci_snoop_log
09-12 14:43:31.576  1032  1094 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
09-12 14:43:31.576  1032  1094 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
09-12 14:43:31.577  7591  7803 D BluetoothAdapterProperties: Name is: G3
09-12 14:43:31.578  7802  7802 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
,09-12 14:43:31.586  7802  7802 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
09-12 14:43:31.586  7802  7802 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
09-12 14:43:31.591  7591  7799 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
09-12 14:43:31.591  7591  7799 D BluetoothAdapterProperties: Setting state to 11
09-12 14:43:31.591  7591  7799 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,09-12 14:43:31.594  7591  7799 I LGBluetoothServiceJni: classInitNative: succeeds
09-12 14:43:31.598  1032  1094 D BluetoothManagerService: Message: 60
09-12 14:43:31.598  1032  1094 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
09-12 14:43:31.598  1032  1094 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
09-12 14:43:31.602  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,09-12 14:43:31.605  1599  1599 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-12 14:43:31.608  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 14:43:31.611  6738  6738 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
09-12 14:43:31.614  7591  7591 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-12 14:43:31.614  7591  7591 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-12 14:43:31.614  7591  7591 V BluetoothPbapReceiver: ***********state = 11
09-12 14:43:31.627  2208  2208 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-12 14:43:31.630  7591  7799 D BluetoothBondStateMachine: make
09-12 14:43:31.635  7591  7816 I BluetoothBondStateMachine: StableState(): Entering Off State
09-12 14:43:31.635  7591  7799 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32431a18
09-12 14:43:31.635  7591  7799 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
09-12 14:43:31.635  7591  7799 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32431a18
09-12 14:43:31.636  7591  7799 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
09-12 14:43:31.637  7591  7799 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
09-12 14:43:31.642  7591  7799 E BluetoothAdapterService: File transfer profiles supported!!
09-12 14:43:31.652  7591  7591 D HeadsetService: Received start request. Starting profile...
09-12 14:43:31.653  7591  7591 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
09-12 14:43:31.653  7591  7591 D LGBluetoothHfpAdapter: Version 1.6
09-12 14:43:31.653  7591  7799 E BluetoothAdapterService: File transfer profiles supported!!
,09-12 14:43:31.656  7591  7591 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-12 14:43:31.658  7591  7591 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-12 14:43:31.658  7591  7591 D HeadsetStateMachine: make
09-12 14:43:31.662  6738  6738 D BluetoothPermissionRequest: onReceive
09-12 14:43:31.664  7591  7799 E BluetoothAdapterService: File transfer profiles supported!!
09-12 14:43:31.666  6738  6738 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,09-12 14:43:31.671  7591  7799 E BluetoothAdapterService: File transfer profiles supported!!
09-12 14:43:31.676  7591  7799 E BluetoothAdapterService: File transfer profiles supported!!
09-12 14:43:31.681  7591  7799 E BluetoothAdapterService: File transfer profiles supported!!
,09-12 14:43:31.686  7591  7591 D LgDataFeature: LgDataFeature() Constructor: none
09-12 14:43:31.686  7591  7591 D LgDataFeature: LgDataFeature() Constructor Done, null
09-12 14:43:31.687  7591  7799 E BluetoothAdapterService: File transfer profiles supported!!
09-12 14:43:31.690  7591  7591 D HeadsetStateMachine: max_hf_connections = 1
09-12 14:43:31.690  7591  7591 I bluedroid-qcom: get_profile_interface handsfree
09-12 14:43:31.692  7591  7591 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
,09-12 14:43:31.693   311  2165 V AudioPolicyService: registerClient() client 0xb101fb80, uid 1002
09-12 14:43:31.693   311  2164 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
09-12 14:43:31.693   311  2164 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-12 14:43:31.693   311  2164 V AudioPolicyManagerEx: getOutput() returns output 2
09-12 14:43:31.693  7591  7591 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
09-12 14:43:31.694   311  1394 V AudioFlinger: registerClient() client 0xb57cc268, pid 7591
09-12 14:43:31.694   311  1389 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-12 14:43:31.694   311  1389 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-12 14:43:31.694  1599  2525 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-12 14:43:31.694  1599  2525 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-12 14:43:31.694  3309  3325 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-12 14:43:31.694  3309  3325 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-12 14:43:31.695   311  1390 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-12 14:43:31.695   311  1390 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-12 14:43:31.695  1032  2012 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-12 14:43:31.695  1032  2012 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-12 14:43:31.695  1032  2012 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-12 14:43:31.695  1032  2012 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-12 14:43:31.695  1599  2167 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-12 14:43:31.695  1599  2167 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-12 14:43:31.695  3309  3327 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-12 14:43:31.695  3309  3327 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-12 14:43:31.695  7591  7606 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-12 14:43:31.695  7591  7606 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
09-12 14:43:31.695  7591  7606 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-12 14:43:31.695  7591  7606 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
09-12 14:43:31.697  1852  2404 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-12 14:43:31.697  1852  2404 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-12 14:43:31.697  1852  2404 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-12 14:43:31.697  1852  2404 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-12 14:43:31.698  7591  7591 V ToneGenerator: Create Track: 0xb4928080
09-12 14:43:31.698  7591  7591 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
09-12 14:43:31.698  7591  7591 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
09-12 14:43:31.698   311   311 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-12 14:43:31.698   311   311 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
09-12 14:43:31.698   311   311 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-12 14:43:31.698   311   311 V AudioPolicyManagerEx: getOutput() returns output 2
09-12 14:43:31.698   311  2165 I AudioFlinger: isAudioPlaybackHookOn() false
09-12 14:43:31.698   311  2164 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-12 14:43:31.698   311  2164 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
09-12 14:43:31.698   31,1  2164 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-12 14:43:31.698   311  2164 V AudioPolicyManagerEx: getOutput() returns output 2
09-12 14:43:31.699  7591  7591 V AudioSystem: getLatency() output 2, latency 50
09-12 14:43:31.699  7591  7591 V AudioSystem: getFrameCount() output 2, frameCount 960
09-12 14:43:31.699  7591  7591 V AudioTrack: createTrack_l() output 2 afLatency 50
09-12 14:43:31.699   311  1394 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-12 14:43:31.699   311  1394 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-12 14:43:31.699   311  1394 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-12 14:43:31.699   311  1394 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-12 14:43:31.699   311  1394 V AudioFlinger: createTrack() lSessionId: 21
09-12 14:43:31.700  7591  7591 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
09-12 14:43:31.700   311  1394 V AudioFlinger: acquiring 21 from 7591, for 7591
09-12 14:43:31.700   311  1394 V AudioFlinger:  added new entry for 21
09-12 14:43:31.700  7591  7591 V ToneGenerator: ToneGenerator INIT OK, time: 211313
09-12 14:43:31.700  7591  7591 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32431a18
09-12 14:43:31.701  7591  7822 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
09-12 14:43:31.701  7591  7822 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-12 14:43:31.701  7591  7822 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-12 14:43:31.701  7591  7822 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
09-12 14:43:31.701   311  1395 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7591
09-12 14:43:31.702   311  1395 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
09-12 14:43:31.702   311  1395 V voice   : voice_set_parameters: enter: bt_samplerate=8000
09-12 14:43:31.702   311  1395 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
09-12 14:43:31.702   311  1395 V compress_voip: voice_extn_compress_voip_set_parameters: exit
09-12 14:43:31.702   311  1395 V voice   : voice_set_parameters: exit with code(0)
09-12 14:43:31.702   311  1395 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
09-12 14:43:31.702   311  1395 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
09-12 14:43:31.702  7591  7591 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32431a18
09-12 14:43:31.702   311  1395 V msm8974_platform: platform_set_parameters: exit with code(0)
09-12 14:43:31.702   311  1395 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
09-12 14:43:31.702   311  1395 V audio_hw_primary: adev_set_parameters: exit with code(0),
09-12 14:43:31.702   311  1395 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
09-12 14:43:31.702  7591  7822 V ToneGenerator: ToneGenerator destructor
09-12 14:43:31.702  7591  7822 V ToneGenerator: stopTone
09-12 14:43:31.702  7591  7822 V ToneGenerator: Delete Track: 0xb4928080
09-12 14:43:31.704  7591  7591 D A2dpService: Received start request. Starting profile...
,09-12 14:43:31.704  7591  7822 V AudioTrack: ~AudioTrack, releasing session id from 7591 on behalf of 7591
09-12 14:43:31.704   311   311 V AudioFlinger: releasing 21 from 7591 for 7591
09-12 14:43:31.704   311   311 V AudioFlinger:  decremented refcount to 0
09-12 14:43:31.704   311   311 V AudioFlinger: purging stale effects
09-12 14:43:31.704   311   311 V AudioPolicyService: AudioCommandThread() adding release output 2
09-12 14:43:31.704   311   311 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
09-12 14:43:31.704   311  1225 V AudioPolicyService: AudioCommandThread() waking up
09-12 14:43:31.705   311  1225 V AudioPolicyService: AudioCommandThread() processing release output 2
09-12 14:43:31.705   311  1225 V AudioPolicyManager: releaseOutput() 2
09-12 14:43:31.705   311  1225 V AudioPolicyService: AudioCommandThread() going to sleep
09-12 14:43:31.705   311   311 V AudioFlinger: PlaybackThread::Track destructor
09-12 14:43:31.705   311   311 V AudioFlinger: removeClient_l() pid 7591, calling pid 311
09-12 14:43:31.706  1032  1650 W Process : Unable to open /proc/7823/status
09-12 14:43:31.707  7591  7591 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-12 14:43:31.708  7591  7591 V Avrcp   : make
09-12 14:43:31.708  7591  7591 D Avrcp   : [BTUI] Use Native AVRCP : init jni
09-12 14:43:31.708  7591  7591 I bluedroid-qcom: get_profile_interface avrcp
09-12 14:43:31.719  7591  7799 V LGMDMManager: Create singleton instance
,09-12 14:43:31.720  7591  7799 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
09-12 14:43:31.722  7591  7591 V AudioManager: registerRemoteController: size of Media player list: 0
09-12 14:43:31.724  7591  7591 E AudioManager: No RCC entry present to update
09-12 14:43:31.724  7591  7591 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-12 14:43:31.728  7591  7591 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
09-12 14:43:31.729  7591  7591 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
09-12 14:43:31.729  7591  7591 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
09-12 14:43:31.732  7591  7591 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,09-12 14:43:31.833  1032  1774 V SIM_STK : Menu title from STK is T-Mobile
09-12 14:43:31.833  1032  1774 V SIM_STK : Menu title from STK is T-Mobile
,09-12 14:43:31.908  1032  1049 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,09-12 14:43:31.917  7591  7591 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
09-12 14:43:31.921  7591  7591 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-12 14:43:31.922  7591  7591 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-12 14:43:31.922  7591  7591 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-12 14:43:31.922  7591  7591 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-12 14:43:31.922  7591  7591 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-12 14:43:31.922  7591  7591 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-12 14:43:31.922  7591  7591 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-12 14:43:31.922  7591  7591 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-12 14:43:31.922  7591  7591 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-12 14:43:31.922  7591  7591 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-12 14:43:31.923  7591  7591 I BluetoothA2dpServiceJni: classInitNative
09-12 14:43:31.923  7591  7591 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-12 14:43:31.923  7591  7591 D A2dpStateMachine: make
,09-12 14:43:31.926  7591  7591 I bluedroid-qcom: get_profile_interface a2dp
09-12 14:43:31.926  7591  7828 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
09-12 14:43:31.929  7591  7591 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
09-12 14:43:31.929  7591  7591 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
09-12 14:43:31.930  7591  7591 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32431a18
09-12 14:43:31.931  7591  7591 I BluetoothHidServiceJni: classInitNative: succeeds
09-12 14:43:31.931  7591  7826 D A2dpStateMachine: Enter Disconnected: -2
09-12 14:43:31.933  7591  7591 D HidService: Received start request. Starting profile...
09-12 14:43:31.933  7591  7591 I bluedroid-qcom: get_profile_interface hidhost
09-12 14:43:31.933  7591  7591 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32431a18
09-12 14:43:31.933  7591  7591 I BluetoothHealthServiceJni: classInitNative: succeeds
09-12 14:43:31.935  7591  7591 D HealthService: Received start request. Starting profile...
09-12 14:43:31.939  7591  7591 I bluedroid-qcom: get_profile_interface health
,09-12 14:43:31.940  7591  7591 I LGBluetoothHealthServiceJni: classInitNative: succeeds
09-12 14:43:31.940  7591  7591 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32431a18
,09-12 14:43:31.944  7591  7591 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-12 14:43:31.948  7591  7591 D PanService: Received start request. Starting profile...
09-12 14:43:31.948  7591  7591 D BluetoothPanServiceJni: initializeNative(L110): pan
09-12 14:43:31.948  7591  7591 I bluedroid-qcom: get_profile_interface pan
09-12 14:43:31.962  7591  7591 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
09-12 14:43:31.962  7591  7591 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32431a18
,09-12 14:43:31.963  7591  7591 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
09-12 14:43:31.974  7591  7591 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-12 14:43:31.975  7591  7591 D BtGatt.GattService: Received start request. Starting profile...
09-12 14:43:31.975  7591  7591 D BtGatt.GattService: start()
09-12 14:43:31.975  7591  7591 I bluedroid-qcom: get_profile_interface gatt
09-12 14:43:31.976  7591  7591 D BtGatt.AdvertiseManager: advertise manager created
09-12 14:43:31.989  7591  7591 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32431a18
,09-12 14:43:31.991  7591  7591 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32431a18
09-12 14:43:31.992  7591  7591 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
09-12 14:43:31.993  7591  7591 V BluetoothMapService: BluetoothMapBinder()
09-12 14:43:31.993  7591  7591 D BluetoothMapService: Received start request. Starting profile...
09-12 14:43:31.993  7591  7591 D BluetoothMapService: start()
09-12 14:43:31.997  7591  7591 D BluetoothMapEmailSettingsLoader: Found 0 applications
09-12 14:43:31.997  7591  7591 D BluetoothMapEmailAppObserver: createReceiver()
09-12 14:43:31.999  7591  7591 D BluetoothMapEmailAppObserver: initObservers()
09-12 14:43:31.999  7591  7591 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
,09-12 14:43:32.009  7591  7591 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32431a18
09-12 14:43:32.009  7591  7591 D HeadsetStateMachine: Proxy object connected
09-12 14:43:32.010  7591  7591 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
09-12 14:43:32.010  7591  7591 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
09-12 14:43:32.012  7591  7822 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-12 14:43:32.013  7591  7822 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-12 14:43:32.014  7591  7822 D HeadsetStateMachine: Disconnected process message: 11, size: 0
,09-12 14:43:32.017  7591  7591 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-12 14:43:32.021  7591  7591 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-12 14:43:32.028  7591  7591 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,09-12 14:43:32.032  7591  7591 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-12 14:43:32.038  7591  7591 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-12 14:43:32.039  7591  7591 V PanService: [BTUI] SIM Extra State :ABSENT
09-12 14:43:32.042  7591  7591 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,09-12 14:43:32.046  7591  7591 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
09-12 14:43:32.046  7591  7591 V BluetoothMapService: Handler(): got msg=1
09-12 14:43:32.047  7591  7799 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
09-12 14:43:32.047  7591  7799 I bluedroid-qcom: enable
09-12 14:43:32.048  7591  7799 I bt_hci_bdroid: init
09-12 14:43:32.048  7591  7591 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-12 14:43:32.048  7591  7591 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-12 14:43:32.048  7591  7591 V BluetoothSapReceiver: SapReceiver onReceive 
09-12 14:43:32.048  7591  7591 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-12 14:43:32.048  7591  7591 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
09-12 14:43:32.050  7591  7799 I bt_vendor: bt-vendor : init
09-12 14:43:32.050  7591  7799 I bt_vendor: bt-vendor : get_bt_soc_type
09-12 14:43:32.050  7591  7799 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-12 14:43:32.050  7591  7799 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
09-12 14:43:32.050  7591  7799 D bt_userial_mct: userial_init
09-12 14:43:32.051  7591  7799 D bt_hci_bdroid: set_power 1
09-12 14:43:32.051  7591  7799 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-12 14:43:32.051  7591  7799 I bt_vendor: Starting hciattach daemon
09-12 14:43:32.051  7591  7799 I bt_vendor: try to set true
09-12 14:43:32.054  7591  7841 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
09-12 14:43:32.054  7591  7841 I bt-btu  : btu_task pending for preload complete event
,09-12 14:43:32.041  7844  7844 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-12 14:43:32.051  7844  7844 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-12 14:43:32.080  7845  7845 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,09-12 14:43:32.146  7851  7851 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,09-12 14:43:32.156  7852  7852 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-12 14:43:32.174  7854  7854 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
09-12 14:43:32.184  7855  7855 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,09-12 14:43:32.194  7856  7856 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
09-12 14:43:32.203  7857  7857 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,09-12 14:43:32.223  7859  7859 I libmdmdetect: ESOC framework not supported
09-12 14:43:32.224  7859  7859 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,09-12 14:43:32.231  7859  7859 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
09-12 14:43:32.231  7859  7859 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
09-12 14:43:32.231  7859  7859 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
09-12 14:43:32.231  7859  7859 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
09-12 14:43:32.231  7859  7859 D bthci_qcomm_common: [BTUI]     LE: Class 2
09-12 14:43:32.231  7859  7859 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
09-12 14:43:32.231  7859  7859 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
09-12 14:43:32.275  7859  7860 E QC-QMI  : qmi_client [7859] 15: failed to locate client data
09-12 14:43:32.275   481   481 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
09-12 14:43:32.275   481   481 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,09-12 14:43:32.308  7865  7865 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,09-12 14:43:32.322  7867  7867 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-12 14:43:32.354  7591  7799 I bt_vendor: bluetooth satus is on
,09-12 14:43:32.355  7591  7799 D bt_hci_bdroid: preload
,09-12 14:43:32.355  7591  7843 D bt_userial_mct: userial_open(port:0)
,09-12 14:43:32.355  7591  7843 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,09-12 14:43:32.359  7591  7843 I bt_vendor: Done intiailizing UART
09-12 14:43:32.363  7591  7843 I bt_vendor: Done intiailizing UART
,09-12 14:43:32.363  7591  7843 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
09-12 14:43:32.364  7591  7843 I bt_vendor: Bluetooth Firmware and transport layer are initialized
09-12 14:43:32.364  7591  7869 D bt_userial_mct: Entering userial_read_thread()
09-12 14:43:32.364  7591  7841 I bt-btu  : btu_task received preload complete event
,09-12 14:43:32.364  7591  7841 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
,09-12 14:43:32.365  7591  7841 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
09-12 14:43:32.367  7591  7841 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
09-12 14:43:32.376  7591  7841 I         : BTE_InitTraceLevels -- TRC_HCI
09-12 14:43:32.376  7591  7841 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-12 14:43:32.376  7591  7841 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-12 14:43:32.376  7591  7841 I         : BTE_InitTraceLevels -- TRC_AVDT
09-12 14:43:32.376  7591  7841 I         : BTE_InitTraceLevels -- TRC_AVRC
09-12 14:43:32.376  7591  7841 I         : BTE_InitTraceLevels -- TRC_A2D
,09-12 14:43:32.376  7591  7841 I         : BTE_InitTraceLevels -- TRC_BNEP
09-12 14:43:32.376  7591  7841 I         : BTE_InitTraceLevels -- TRC_BTM
09-12 14:43:32.376  7591  7841 I         : BTE_InitTraceLevels -- TRC_HID_HOST
09-12 14:43:32.376  7591  7841 I         : BTE_InitTraceLevels -- TRC_GAP
,09-12 14:43:32.376  7591  7841 I         : BTE_InitTraceLevels -- TRC_PAN
09-12 14:43:32.376  7591  7841 I         : BTE_InitTraceLevels -- TRC_SDP
09-12 14:43:32.376  7591  7841 I         : BTE_InitTraceLevels -- TRC_GATT
09-12 14:43:32.376  7591  7841 I         : BTE_InitTraceLevels -- TRC_SMP
,09-12 14:43:32.376  7591  7841 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-12 14:43:32.377  7591  7841 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-12 14:43:32.473  7591  7841 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
,09-12 14:43:32.473  7591  7841 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa020e061 
,09-12 14:43:32.473  7591  7841 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa020e061 
,09-12 14:43:32.523  7591  7803 E bt-btif : Calling BTA_HhEnable
,09-12 14:43:32.524  7591  7803 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
,09-12 14:43:32.524  7591  7803 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
09-12 14:43:32.528  1032  1032 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-12 14:43:32.528  1032  1032 D BluetoothManagerService: Stored Bluetooth name: G3
09-12 14:43:32.530  7591  7841 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
09-12 14:43:32.530  7591  7841 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
09-12 14:43:32.530  7591  7841 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
09-12 14:43:32.530  7591  7841 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
09-12 14:43:32.530  7591  7841 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
,09-12 14:43:32.535  7591  7803 D BluetoothAdapterProperties: Name is: G3
,09-12 14:43:32.539  7591  7803 D BluetoothAdapterProperties: Scan Mode:20
09-12 14:43:32.539  7591  7803 D BluetoothAdapterProperties: Discoverable Timeout:120
09-12 14:43:32.540  7591  7803 D bt_hci_bdroid: postload
09-12 14:43:32.541  7591  7843 D bt_hci_bdroid: Used up Tx Cmd credits
09-12 14:43:32.543  7591  7841 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
,09-12 14:43:32.560  7591  7803 D bte_conf: Device ID record 1 : primary
09-12 14:43:32.560  7591  7803 D bte_conf:   vendorId            = 00c4
09-12 14:43:32.560  7591  7803 D bte_conf:   vendorIdSource      = 0001
09-12 14:43:32.560  7591  7803 D bte_conf:   product             = 13a1
09-12 14:43:32.560  7591  7803 D bte_conf:   version             = 1000
09-12 14:43:32.560  7591  7803 D bte_conf:   clientExecutableURL = 
09-12 14:43:32.562  7591  7803 D bte_conf:   serviceDescription  = 
09-12 14:43:32.562  7591  7803 D bte_conf:   documentationURL    = 
09-12 14:43:32.562  7591  7803 D bte_conf: bte_load_did_conf no section named DID2.
09-12 14:43:32.564  7591  7799 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-12 14:43:32.565  7591  7799 D BluetoothAdapterProperties: ScanMode =  20
09-12 14:43:32.565  7591  7799 D BluetoothAdapterProperties: State =  11
09-12 14:43:32.565  7591  7799 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
09-12 14:43:32.565  7591  7799 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
09-12 14:43:32.565  7591  7799 D BluetoothAdapterProperties: Setting state to 12
09-12 14:43:32.565  7591  7799 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-12 14:43:32.566  7591  7803 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-12 14:43:32.566  7591  7803 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-12 14:43:32.561  7877  7877 W sh      : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-12 14:43:32.561  7877  7877 W sh      : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-12 14:43:32.578  1032  1094 D BluetoothManagerService: Message: 60
09-12 14:43:32.578  1032  1094 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
09-12 14:43:32.578  1032  1094 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
09-12 14:43:32.578  1032  1094 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 14:43:32.583  7591  7843 D bt_hci_bdroid: Used up Tx Cmd credits
,09-12 14:43:32.589  7591  7843 D bt_hci_bdroid: Used up Tx Cmd credits
09-12 14:43:32.596  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 14:43:32.599  7591  7841 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-12 14:43:32.599  7591  7841 W bt-smp  : Plain text(LSB ~ MSB) = b4 71 6e 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-12 14:43:32.599  7591  7841 W bt-smp  : Encrypted text(LSB ~ MSB) = 43 4e 08 ad 9e 34 64 8a dc f8 09 53 c7 f5 59 54 
09-12 14:43:32.599  7591  7843 D bt_hci_bdroid: Used up Tx Cmd credits
09-12 14:43:32.599  7591  7841 W bt-btm  : Stopping oneshot timer
09-12 14:43:32.600  7591  7803 D BluetoothAdapterProperties: Discoverable Timeout:120
09-12 14:43:32.600  7591  7803 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
09-12 14:43:32.600  7591  7799 I BluetoothAdapterState: Entering On State
09-12 14:43:32.615  7591  7799 D LGBluetoothServiceAdapter: [BTUI] OnState
09-12 14:43:32.615  7591  7799 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
09-12 14:43:32.615  7591  7799 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,09-12 14:43:32.619  7591  7869 E bt_mct  : hci lib postload completed
09-12 14:43:32.620  7591  7799 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
09-12 14:43:32.620  1032  1032 D BluetoothHeadset: Proxy object connected
09-12 14:43:32.665  7882  7882 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,09-12 14:43:32.671  7591  7799 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
09-12 14:43:32.671  6738  7473 D BluetoothMap: onBluetoothStateChange: up=true
09-12 14:43:32.675  6738  7473 D BluetoothA2dp: onBluetoothStateChange: up=true
09-12 14:43:32.680  6738  6763 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-12 14:43:32.684  6738  6763 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-12 14:43:32.686  7591  7841 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-12 14:43:32.686  7591  7841 W bt-smp  : Plain text(LSB ~ MSB) = 47 3f 70 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-12 14:43:32.686  7591  7841 W bt-smp  : Encrypted text(LSB ~ MSB) = b2 cb b7 ea 10 0b 12 35 d7 c1 39 5e 3f 14 fe 59 
09-12 14:43:32.686  7591  7841 W bt-btm  : Stopping oneshot timer
09-12 14:43:32.687  6738  6738 D BluetoothMap: Proxy object connected
09-12 14:43:32.687  6738  6738 D MapProfile: Bluetooth service connected
09-12 14:43:32.687  6738  6738 D BluetoothMap: getConnectedDevices()
09-12 14:43:32.688  1032  1094 D BluetoothA2dp: onBluetoothStateChange: up=true
09-12 14:43:32.689  1032  1032 D BluetoothA2dp: Proxy object connected
09-12 14:43:32.690  1852  1868 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 14:43:32.697  1852  1852 D BluetoothHeadset: Proxy object connected
,09-12 14:43:32.700  1852  2404 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 14:43:32.702  7591  7841 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-12 14:43:32.702  7591  7841 W bt-smp  : Plain text(LSB ~ MSB) = 97 40 48 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-12 14:43:32.702  7591  7841 W bt-smp  : Encrypted text(LSB ~ MSB) = 4f 1a 3f 53 8b 43 a2 51 d5 d8 60 13 5f 01 ff d5 
09-12 14:43:32.702  7591  7841 W bt-btm  : Stopping oneshot timer
09-12 14:43:32.704  1852  1852 D BluetoothHeadset: Proxy object connected
09-12 14:43:32.705  6738  6755 D BluetoothPbap: onBluetoothStateChange: up=true
09-12 14:43:32.707  1852  3986 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 14:43:32.709  1852  1852 D BluetoothHeadset: Proxy object connected
,09-12 14:43:32.712  7591  7841 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-12 14:43:32.712  7591  7841 W bt-smp  : Plain text(LSB ~ MSB) = 69 25 6b 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-12 14:43:32.712  7591  7841 W bt-smp  : Encrypted text(LSB ~ MSB) = d8 87 e5 8d 05 4a d0 7e 4a fb eb ea 8a 50 c8 4d 
09-12 14:43:32.712  7591  7841 W bt-btm  : Stopping oneshot timer
09-12 14:43:32.714  7591  7606 V BluetoothMapService: getConnectedDevices()
09-12 14:43:32.715  6738  6763 D BluetoothPan: onBluetoothStateChange on: true
09-12 14:43:32.715  6738  6763 D BluetoothPan: onBluetoothStateChange call bindService
09-12 14:43:32.721  1032  1032 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,09-12 14:43:32.723  1032  1094 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
,09-12 14:43:32.723  1032  1094 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
09-12 14:43:32.729  1599  1599 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-12 14:43:32.741  6738  6738 D BluetoothA2dp: Proxy object connected
09-12 14:43:32.741  6738  6738 D A2dpProfile: Bluetooth service connected
,09-12 14:43:32.745  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-12 14:43:32.745  1032  1094 D BluetoothManagerService: Message: 40
09-12 14:43:32.745  1032  1094 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
09-12 14:43:32.745  1941  2276 D LGBluetoothAPIService: Message: 1
09-12 14:43:32.745  1941  2276 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
09-12 14:43:32.746  1941  2276 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
09-12 14:43:32.746  1941  2276 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
09-12 14:43:32.746  7591  7841 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-12 14:43:32.746  7591  7841 W bt-smp  : Plain text(LSB ~ MSB) = f7 d5 5e 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-12 14:43:32.746  7591  7841 W bt-smp  : Encrypted text(LSB ~ MSB) = ae eb 24 09 64 b4 4a d0 68 0d bd 7a bf 63 27 78 
09-12 14:43:32.746  7591  7841 W bt-btm  : Stopping oneshot timer
09-12 14:43:32.755  7591  7591 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-12 14:43:32.756  7591  7591 D BluetoothMapService: STATE_ON
,09-12 14:43:32.757  6738  6738 D BluetoothHeadset: Proxy object connected
09-12 14:43:32.760  6738  6738 D HeadsetProfile: Bluetooth service connected
09-12 14:43:32.762  6738  6738 D BluetoothInputDevice: Proxy object connected
09-12 14:43:32.762  6738  6738 D HidProfile: Bluetooth service connected
09-12 14:43:32.763  6738  6738 D BluetoothPan: BluetoothPAN Proxy object connected
09-12 14:43:32.763  6738  6738 D PanProfile: Bluetooth service connected
09-12 14:43:32.773  7591  7591 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32431a18
09-12 14:43:32.773  7591  7591 V BluetoothPbapService: Pbap Service onCreate
09-12 14:43:32.773  7591  7591 V BluetoothPbapService: Starting PBAP service
,09-12 14:43:32.774  6738  6738 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
09-12 14:43:32.775  7591  7591 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
09-12 14:43:32.776  7591  7591 V BluetoothPbapService: Pbap Service onBind
09-12 14:43:32.776  6738  6738 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-12 14:43:32.778  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 14:43:32.778  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 14:43:32.778  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 14:43:32.778  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 14:43:32.778  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 14:43:32.778  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 14:43:32.778  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 14:43:32.778  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 14:43:32.780  6669  6669 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 14:43:32.783  7591  7591 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-12 14:43:32.783  7591  7591 V BluetoothPbapService: state: 12
09-12 14:43:32.783  7591  7591 V BluetoothMapService: Handler(): got msg=1
09-12 14:43:32.784  7591  7591 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
09-12 14:43:32.784  7591  7591 V BluetoothPbapService: Handler(): got msg=1
09-12 14:43:32.786  7591  7591 V BluetoothPbapService: Pbap Service startRfcommSocketListener
,09-12 14:43:32.788  7591  7591 V BluetoothPbapReceiver: PbapReceiver onReceive 
,09-12 14:43:32.788  7591  7591 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-12 14:43:32.788  7591  7591 V BluetoothPbapReceiver: ***********state = 12
09-12 14:43:32.789  7591  7901 D BluetoothMapMasInstance: MAS initSocket()
09-12 14:43:32.790  7591  7901 D BluetoothMapMasInstance:   masId = 00
09-12 14:43:32.790  7591  7901 D BluetoothMapMasInstance:   msgTypes = 0e
09-12 14:43:32.790  7591  7901 D BluetoothMapMasInstance:   masName = SMS/MMS
09-12 14:43:32.790  7591  7901 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
09-12 14:43:32.791  6738  6738 D DockEventReceiver: finishStartingService: stopping service
09-12 14:43:32.792  6738  6738 D BluetoothPbap: Proxy object connected
09-12 14:43:32.792  6738  6738 D PbapServerProfile: Bluetooth service connected
09-12 14:43:32.793  7591  7903 V BluetoothPbapService: Pbap Service initSocket
09-12 14:43:32.795  1032  1966 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 14:43:32.795  1032  2031 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 14:43:32.797  7591  7901 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 14:43:32.798  7591  7903 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 14:43:32.800  2208  2208 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-12 14:43:32.800  2208  2208 D c       : Getting all permits...
09-12 14:43:32.800  2208  2208 D a       : Opening database...
09-12 14:43:32.801  7591  7901 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
09-12 14:43:32.802  7591  7901 V BluetoothMapMasInstance: Succeed to create listening socket 
09-12 14:43:32.802  7591  7901 D BluetoothMapMasInstance: Accepting socket connection...
09-12 14:43:32.802  7591  7903 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
09-12 14:43:32.802  7591  7903 V BluetoothPbapService: Succeed to create listening socket 
09-12 14:43:32.802  7591  7903 V BluetoothPbapService: Accepting socket connection...
09-12 14:43:32.803  7591  7803 D BluetoothAdapterProperties: Scan Mode:21
09-12 14:43:32.803  7591  7803 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
09-12 14:43:32.804  2208  2208 D a       : Opening database auth.proximity.permit_store...
09-12 14:43:32.805  2208  2208 D a       : Closing database...
09-12 14:43:32.805  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 14:43:32.817  6738  6738 D BluetoothPermissionRequest: onReceive
,09-12 14:43:32.819  6738  6738 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,09-12 14:43:32.821  6738  6738 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-12 14:43:32.824  7591  7591 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
09-12 14:43:32.825  7591  7591 I LGBluetoothOppAdapter: [BTUI] startOppService()
09-12 14:43:32.834  7591  7591 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,09-12 14:43:32.858  7591  7591 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-12 14:43:32.858  7591  7591 V BtOppService: onCreate
,09-12 14:43:32.865  7591  7591 V BluetoothOppNotification: send message
09-12 14:43:32.869  7591  7591 V BtOppService: Starting RfcommListener
09-12 14:43:32.877  7591  7591 D BluetoothOppPreference: Dumping Names:  
09-12 14:43:32.877  7591  7591 D BluetoothOppPreference: {}
,09-12 14:43:32.877  7591  7591 D BluetoothOppPreference: Dumping Channels:  
09-12 14:43:32.877  7591  7591 D BluetoothOppPreference: {}
,09-12 14:43:32.880  7591  7591 V BtOppService: onStartCommand
,09-12 14:43:32.882  7591  7909 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-12 14:43:32.883  7591  7909 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-12 14:43:32.884  7591  7906 V BtOppService: Deleted complete outbound shares, number =  0
09-12 14:43:32.885  7591  7909 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@268c2a54 on behalf of 
09-12 14:43:32.886  7591  7909 V BluetoothOppNotification: update too frequent, put in queue
09-12 14:43:32.887  7591  7591 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-12 14:43:32.887  7591  7906 V BtOppService: Deleted complete inbound failed shares, number = 0
09-12 14:43:32.888  7591  7591 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-12 14:43:32.888  7591  7909 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-12 14:43:32.888  7591  7909 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-12 14:43:32.889  7591  7906 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
09-12 14:43:32.889  7591  7909 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2f8bcdfd on behalf of 
,09-12 14:43:32.892  7591  7909 V BluetoothOppNotification: update too frequent, put in queue
09-12 14:43:32.893  7591  7591 V BluetoothOppNotification: new notify threadi!
09-12 14:43:32.894  7591  7906 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@25f7faf2 on behalf of 
09-12 14:43:32.895  7591  7591 V BluetoothOppNotification: send delay message
09-12 14:43:32.897  7591  7909 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-12 14:43:32.898  7591  7591 V BtOppService: start RfcommListener
09-12 14:43:32.900  7591  7910 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-12 14:43:32.902  7591  7591 V BtOppService: RfcommListener started
09-12 14:43:32.903  7591  7591 V BtOppService: ContentObserver received notification
09-12 14:43:32.905  7591  7591 V BtOppService: ContentObserver received notification
09-12 14:43:32.905  7591  7911 V BtOppRfcommListener: Starting RFCOMM listener....
,09-12 14:43:32.910  1032  1976 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 14:43:32.911  7591  7912 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-12 14:43:32.911  7591  7912 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-12 14:43:32.915  7591  7911 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 14:43:32.917  7591  7911 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
09-12 14:43:32.918  7591  7911 V BtOppRfcommListener: Started RFCOMM listener....
09-12 14:43:32.918  7591  7911 I BtOppRfcommListener: Accept thread started.
09-12 14:43:32.918  7591  7911 V BtOppRfcommListener: Accepting connection...
09-12 14:43:32.927  7591  7591 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32431a18
,09-12 14:43:32.927  7591  7591 V BluetoothFtpService: Ftp Service onCreate
09-12 14:43:32.927  7591  7591 I BluetoothFtpService: Ftp Service onCreate
09-12 14:43:32.928  7591  7591 V BluetoothFtpService: Ftp Service onStartCommand
09-12 14:43:32.928  7591  7591 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-12 14:43:32.928  7591  7591 V BluetoothFtpService: Starting Listening on sockets
09-12 14:43:32.928  7591  7591 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-12 14:43:32.928  7591  7591 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-12 14:43:32.928  7591  7591 V BluetoothSapReceiver: SapReceiver onReceive 
09-12 14:43:32.928  7591  7591 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-12 14:43:32.929  7591  7591 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
09-12 14:43:32.929  7591  7591 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-12 14:43:33.028  1032  1903 I art     : Explicit concurrent mark sweep GC freed 27699(1348KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 2.511ms total 124.728ms
09-12 14:43:33.029  7591  7591 V BluetoothFtpService: Handler(): got msg=1
09-12 14:43:33.031  7591  7910 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@4ab97c0 on behalf of 
,09-12 14:43:33.033  7591  7912 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@23cc4cf9 on behalf of 
09-12 14:43:33.033  7591  7591 V BluetoothFtpService: Ftp Service startRfcommSocketListener
09-12 14:43:33.033  7591  7591 V BluetoothFtpService: Ftp Service initSocket
09-12 14:43:33.034  1032  1932 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 14:43:33.035  7591  7910 V BluetoothOppNotification: mUpdateCompleteNotification = true
,09-12 14:43:33.038  7591  7591 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 14:43:33.039  7591  7591 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=78
09-12 14:43:33.039  7591  7591 V BluetoothFtpService: Succeed to create listening socket on channel 20
09-12 14:43:33.041  7591  7912 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-12 14:43:33.043  7591  7910 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-12 14:43:33.046  7591  7910 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3f06d43e on behalf of 
09-12 14:43:33.046  7591  7910 V BluetoothOppNotification: outbound: succ-0  fail-0
,09-12 14:43:33.051  7591  7910 V BluetoothOppNotification: outbound notification was removed.
09-12 14:43:33.051  7591  7910 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-12 14:43:33.052  7591  7914 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
09-12 14:43:33.052  7591  7910 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1087729f on behalf of 
09-12 14:43:33.054  7591  7910 V BluetoothOppNotification: inbound: succ-0  fail-0
09-12 14:43:33.056  7591  7910 V BluetoothOppNotification: inbound notification was removed.
09-12 14:43:33.056  7591  7910 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-12 14:43:33.057  7591  7910 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@14926fec on behalf of 
09-12 14:43:33.065  7591  7591 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32431a18
09-12 14:43:33.065  7591  7591 V BluetoothSapService: Sap Service onCreate
,09-12 14:43:33.067  7591  7591 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-12 14:43:33.067  7591  7591 V BluetoothSapService: state: 12
09-12 14:43:33.067  7591  7591 V BluetoothSapService: Starting SAP server process
09-12 14:43:33.069  7591  7591 V BluetoothSapService: SAP Service startRfcommListenerThread
09-12 14:43:33.070  7591  7916 V BluetoothSapService: Sap Service initRfcommSocket
09-12 14:43:33.070  1032  1049 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 14:43:33.071  7591  7916 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 14:43:33.061  7917  7917 W sapd    : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-12 14:43:33.072  7591  7916 V BluetoothSapService: Succeed to create listening socket 
09-12 14:43:33.072  7591  7916 V BluetoothSapService: Accepting socket connection...
09-12 14:43:33.061  7917  7917 W sapd    : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-12 14:43:33.081  7917  7917 V BT_SAP  : Event pipe created
09-12 14:43:33.081  7917  7917 V BT_SAP  : create_server_socket qcom.sap.server
09-12 14:43:33.081  7917  7917 V BT_SAP  : created socket fd 6
,09-12 14:43:33.543  6669  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 14:43:33.543  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 14:43:33.543  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 14:43:33.543  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 14:43:33.543  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 14:43:33.543  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 14:43:33.543  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 14:43:33.543  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 14:43:33.547  6669  6725 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 14:43:33.549  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 14:43:33.549  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@33fa76d5 added. We now have 8 listener(s)
09-12 14:43:33.549  6669  6725 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 14:43:33.551  1032  1932 D WifiServiceImplEx: setWifiEnabled: false pid=6669, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-12 14:43:33.551  1032  1932 D WifiService: setWifiEnabled: false pid=6669, uid=10118
09-12 14:43:33.551  1032  1932 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-12 14:43:33.567  6669  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 14:43:33.571  1032  1048 D WifiServiceImplEx: setWifiEnabled: true pid=6669, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-12 14:43:33.572  1032  1048 D WifiService: setWifiEnabled: true pid=6669, uid=10118
09-12 14:43:33.572  1032  1048 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-12 14:43:33.588  1032  1396 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
09-12 14:43:33.588  1032  1396 I LGFTMITEM: [GET_FTM][id=6], offset=12288
,09-12 14:43:33.592  1032  1032 D LocationManagerService: getAllProviders()=[passive, gps, network]
,09-12 14:43:33.592  1032  1032 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-12 14:43:33.592  1032  1032 D Ulp_jni : JNI:system_update. Event-4
09-12 14:43:33.593  1032  1396 E WifiUtil: wfc_util_ffile_check_copy(): pid[1032] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
09-12 14:43:33.593  1032  1396 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-12 14:43:33.593  1032  1396 E WifiUtil: wfc_util_ffile_check_copy(): pid[1032] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
09-12 14:43:33.593  1032  1396 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-12 14:43:33.593  1032  1396 I WifiUtil: Intf0MacAddress=C49A027FFB5D
09-12 14:43:33.593  1032  1396 E WifiHW  : unknown target_country: EU , set to default
09-12 14:43:33.593  1032  1396 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
09-12 14:43:33.593  1032  1396 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
09-12 14:43:33.593  1032  1396 I WifiUtil: gEnableBmps=1
09-12 14:43:33.897  7591  7591 V BluetoothOppNotification: new notify threadi!
09-12 14:43:33.899  7591  7591 V BluetoothOppNotification: send delay message
,09-12 14:43:33.916  7591  7930 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,09-12 14:43:33.921  7591  7930 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@212c9ed8 on behalf of 
,09-12 14:43:33.929  7591  7930 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-12 14:43:33.930  7591  7930 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-12 14:43:33.932  7591  7930 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2b75a231 on behalf of 
09-12 14:43:33.932  7591  7930 V BluetoothOppNotification: outbound: succ-0  fail-0
09-12 14:43:33.934  7591  7930 V BluetoothOppNotification: outbound notification was removed.
09-12 14:43:33.934  7591  7930 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-12 14:43:33.935  7591  7930 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3b672d16 on behalf of 
09-12 14:43:33.936  7591  7930 V BluetoothOppNotification: inbound: succ-0  fail-0
,09-12 14:43:33.939  7591  7930 V BluetoothOppNotification: inbound notification was removed.
09-12 14:43:33.939  7591  7930 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-12 14:43:33.940  7591  7930 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2faf1697 on behalf of 
09-12 14:43:34.226   306   892 D SoftapController: Softap fwReload - Ok
,09-12 14:43:34.233  1032  1396 E NetdConnector: NDC Command {83 softap fwreload wlan0 STA} took too long (635ms)
09-12 14:43:34.243  1032  1094 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-12 14:43:34.243  1032  1094 D Tethering: InitialState.processMessage what=4
,09-12 14:43:34.254   306   892 D CommandListener: Setting iface cfg
09-12 14:43:34.254   306   892 D CommandListener: Trying to bring down wlan0
09-12 14:43:34.265   306   892 D CommandListener: Clearing all IP addresses on wlan0
,09-12 14:43:34.274  1032  1094 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-12 14:43:34.284  1032  1396 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,09-12 14:43:34.281  7938  7938 W wpa_supplicant: type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-12 14:43:34.291  7938  7938 W wpa_supplicant: type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-12 14:43:34.308  1032  1396 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-12 14:43:34.308  1032  1396 E WifiStateMachine: useWiFiOffloading() : false
09-12 14:43:34.308  1032  1396 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-12 14:43:34.328  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
,09-12 14:43:34.331  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 14:43:34.344  1032  1396 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-12 14:43:34.344  1032  1396 D WifiMonitor: connecting to supplicant
,09-12 14:43:34.348  1032  1032 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
09-12 14:43:34.350  6738  6738 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-12 14:43:34.350  6738  6738 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-12 14:43:34.350  6738  6738 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-12 14:43:34.350  6738  6738 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-12 14:43:34.354  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 14:43:34.356  6738  6738 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-12 14:43:34.359  6738  6738 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-12 14:43:34.359  6738  6738 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-12 14:43:34.359  6738  6738 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-12 14:43:34.359  6738  6738 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-12 14:43:34.359  6738  6738 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-12 14:43:34.359  6738  6738 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-12 14:43:34.362  6738  6738 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-12 14:43:34.362  6738  6738 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-12 14:43:34.362  6738  6738 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-12 14:43:34.362  6738  6738 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-12 14:43:34.362  7938  7938 I wpa_supplicant: Successfully initialized wpa_supplicant
09-12 14:43:34.364  6738  6738 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,09-12 14:43:34.367  6738  6738 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-12 14:43:34.367  6738  6738 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-12 14:43:34.367  6738  6738 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-12 14:43:34.367  6738  6738 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-12 14:43:34.367  6738  6738 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-12 14:43:34.367  6738  6738 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-12 14:43:34.399  7938  7938 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-12 14:43:34.399  7938  7938 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,09-12 14:43:34.420  1032  1976 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7957 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,09-12 14:43:34.477  7938  7938 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-12 14:43:34.503  7938  7938 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,09-12 14:43:34.508  7938  7938 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
09-12 14:43:34.511  1032  7978 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
09-12 14:43:34.511  1032  7978 D WifiMonitor: Dropping event because (p2p0) is stopped
09-12 14:43:34.511  1032  1396 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
09-12 14:43:34.513  1032  1396 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
09-12 14:43:34.514  1032  1396 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
09-12 14:43:34.515  1032  1396 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
09-12 14:43:34.516  1032  1396 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-12 14:43:34.518  1032  1396 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,09-12 14:43:34.519  1032  1396 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-12 14:43:34.520  1032  1904 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7979 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-12 14:43:34.520  1032  1396 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,09-12 14:43:34.524  1032  1396 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
09-12 14:43:34.524  1032  1396 D WifiNative-wlan0: doString: [DRIVER MACADDR]
09-12 14:43:34.525  7957  7976 W FormManager: Network not available. Please check & try again.
09-12 14:43:34.527  1032  1396 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
09-12 14:43:34.527  1032  1396 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
09-12 14:43:34.527  1032  1396 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
09-12 14:43:34.529  1032  1396 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-12 14:43:34.529  1032  1396 E WifiStateMachine: useWiFiOffloading() : false
09-12 14:43:34.529  1032  1396 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-12 14:43:34.529  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 14:43:34.529  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 14:43:34.529  1032  7978 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-12 14:43:34.529  1032  7978 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-12 14:43:34.529  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-12 14:43:34.529  7938  7938 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
09-12 14:43:34.529  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 14:43:34.530  1032  7978 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
09-12 14:43:34.530  1032  7978 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
09-12 14:43:34.530  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-12 14:43:34.530  1032  7978 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
09-12 14:43:34.530  1032  7978 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
09-12 14:43:34.531  1941  1941 D WfdService: Waiting for WifiP2p enabling
09-12 14:43:34.531  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 14:43:34.533  1032  1032 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
09-12 14:43:34.533  1032  1396 D WifiNative-wlan0: doBoolean: SET update_config 1
09-12 14:43:34.533  1032  1441 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
09-12 14:43:34.533  1032  1396 D WifiNative-wlan0: SET update_config 1: returned true
09-12 14:43:34.533  1032  1396 D WifiConfigStore: Loading config and enabling all networks 
09-12 14:43:34.534  1032  1396 D WifiNative-wlan0: doString: [LIST_NETWORKS]
09-12 14:43:34.534  1032  1396 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
09-12 14:43:34.537  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 14:43:34.537  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 14:43:34.537  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 14:43:34.537  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 14:43:34.537  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 14:43:34.537  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 14:43:34.537  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 14:43:34.537  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 14:43:34.538  6669  6669 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-12 14:43:34.541  1032  1396 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
09-12 14:43:34.545  7957  7977 V FormManager: Network unavailable.
09-12 14:43:34.548  7957  7977 V FormManager: Network unavailable.
09-12 14:43:34.550  1032  1396 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
09-12 14:43:34.550  1032  1396 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,09-12 14:43:34.552  1032  1396 D WifiStateMachine: enableVerboseLogging : level 2
09-12 14:43:34.552  1032  1396 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
09-12 14:43:34.552  1032  1396 D WifiNative-wlan0: SET device_name g3_global_com: returned true
09-12 14:43:34.552  1032  1396 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
09-12 14:43:34.553  1032  1396 D WifiNative-wlan0: SET manufacturer LGE: returned true
09-12 14:43:34.553  1032  1396 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
09-12 14:43:34.553  1032  1396 D WifiNative-wlan0: SET model_name LG-D855: returned true
09-12 14:43:34.553  1032  1396 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
09-12 14:43:34.554  1032  1396 D WifiNative-wlan0: SET model_number LG-D855: returned true
09-12 14:43:34.554  1032  1396 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
09-12 14:43:34.554  1032  1396 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
09-12 14:43:34.554  1032  1396 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
09-12 14:43:34.555  1032  1396 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
09-12 14:43:34.555  1032  1396 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
09-12 14:43:34.555  1032  1396 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
09-12 14:43:34.556  1032  1396 D WifiStateMachine: Setting OUI to DA-A1-19
09-12 14:43:34.556  1032  1396 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
09-12 14:43:34.557  1032  1396 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
09-12 14:43:34.557  1032  1396 D WifiNative-HAL: Setting external_sim to 1
09-12 14:43:34.557  1032  1396 D WifiNative-wlan0: doBoolean: SET external_sim 1
09-12 14:43:34.557  1032  1396 D WifiNative-wlan0: SET external_sim 1: returned true
09-12 14:43:34.557  1032  1396 I WifiNative-HAL: startHal
09-12 14:43:34.557  1032  1396 D wifi    : setting scan oui 0x957915c0
09-12 14:43:34.557  1032  1396 D WifiStateMachine: Setting OUI to DA-A1-19
09-12 14:43:34.557  1032  1396 I WifiNative-HAL: startHal
09-12 14:43:34.558  1032  1396 D wifi    : setting scan oui 0x957915c0
09-12 14:43:34.558  1032  1396 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
09-12 14:43:34.558  1032  1396 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
09-12 14:43:34.558  1032  1396 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
09-12 14:43:34.559  7938  7938 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
09-12 14:43:34.559  1032  1396 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
09-12 14:43:34.559  1032  1396 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-12 14:43:34.559  7938  7938 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-12 14:43:34.559  1941  1941 D WfdsService: Supplicant Connection state is changed : true
,09-12 14:43:34.560  1032  1396 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-12 14:43:34.560  1941  2410 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
09-12 14:43:34.560  1032  1396 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
09-12 14:43:34.560  1941  2410 D WfdsService: Set the WFDS Monitor: true
09-12 14:43:34.560  1941  2410 D WfdsMonitor: WfdsMonitorThread create
09-12 14:43:34.560  7938  7938 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
09-12 14:43:34.560  7620  7620 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 14:43:34.560  1941  2410 D WfdsMonitor: WFDS Monitor is created and started
09-12 14:43:34.560  1941  2410 D WfdsService: WiFi: Supplicant connection re-established
09-12 14:43:34.560  1032  1774 I ActivityManager: Killing 7016:com.android.chrome/u0a57 (adj 15): empty #17
09-12 14:43:34.560  1032  1396 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
09-12 14:43:34.560  1032  1396 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-12 14:43:34.560  7938  7938 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-12 14:43:34.561  1032  1396 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-12 14:43:34.561  1032  1396 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-12 14:43:34.561  7938  7938 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-12 14:43:34.561  1941  7997 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
09-12 14:43:34.561  1032  1396 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-12 14:43:34.561  1032  1396 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
09-12 14:43:34.561  1941  7997 E CtrlSupplicant: Succeed to open control connection
09-12 14:43:34.561  7938  7938 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
09-12 14:43:34.562  1941  7997 E CtrlSupplicant: Succeed to open monitor connection
09-12 14:43:34.562  1032  1396 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
09-12 14:43:34.562  1032  1396 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-12 14:43:34.562  1941  7997 D WfdsMonitor: Supplicant connection established
09-12 14:43:34.562  7938  7938 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-12 14:43:34.562  1941  2410 D WfdsService: Connected to the supplicant for wfds
09-12 14:43:34.564  1032  1396 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-12 14:43:34.565  1032  1396 E WifiNative: : [214,164,884 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
09-12 14:43:34.565  1032  1396 D WifiNative-wlan0: doBoolean: RECONNECT
09-12 14:43:34.566  1032  1396 D WifiNative-wlan0: RECONNECT: returned true
09-12 14:43:34.566  1032  1396 D WifiNative-wlan0: doString: [STATUS]
09-12 14:43:34.566  1032  7978 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-12 14:43:34.566  1032  7978 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-12 14:43:34.568  1032  1396 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-12 14:43:34.568  1032  1396 D WifiNative-wlan0: doBoolean: SET ps 1
09-12 14:43:34.568  1032  1396 D WifiNative-wlan0: SET ps 1: returned true
09-12 14:43:34.568  1032  1387 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
,09-12 14:43:34.569   306   892 D CommandListener: Setting iface cfg
09-12 14:43:34.569   306   892 D CommandListener: Trying to bring up p2p0
09-12 14:43:34.569  1032  1387 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-12 14:43:34.570  1032  1387 D LGWifiP2pService: P2pEnablingState
09-12 14:43:34.570  1032  1387 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
09-12 14:43:34.570  1032  1387 D LGWifiP2pService: P2p socket connection successful
09-12 14:43:34.570  1032  1387 D LGWifiP2pService: P2pEnabledState
09-12 14:43:34.588  7979  7979 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-12 14:43:34.598  1032  1387 D LGWifiP2pService: sending p2p connection changed broadcast
09-12 14:43:34.599  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
09-12 14:43:34.599  1032  1997 W libprocessgroup: failed to open /acct/uid_10057/pid_7016/cgroup.procs: No such file or directory
09-12 14:43:34.599  1941  1941 D WfdsService: WifiP2pState is changed : true
09-12 14:43:34.599  1941  2410 D WfdsService: Receive the WFDS_ENABLE Method
09-12 14:43:34.599  1941  2410 D WfdsService: Set the WFDS Monitor: true
09-12 14:43:34.600  1941  2410 D WfdsService: Connected to the supplicant for wfds
09-12 14:43:34.600  1941  2410 D WfdsJNI : doCommand: WFDS_SET TRUE
09-12 14:43:34.600  7938  7938 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
09-12 14:43:34.600  1941  2410 D WfdsService: selectPreferredScanChannel [36]
09-12 14:43:34.600  1941  2410 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
,09-12 14:43:34.605  6669  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 14:43:34.605  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 14:43:34.605  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 14:43:34.605  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 14:43:34.605  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 14:43:34.605  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 14:43:34.605  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 14:43:34.605  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 14:43:34.606  6738  6738 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-12 14:43:34.606  6669  6725 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-12 14:43:34.608  1032  1396 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
09-12 14:43:34.608  1032  1387 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
09-12 14:43:34.608  1032  1396 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
09-12 14:43:34.608  1032  1387 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
09-12 14:43:34.608  1032  1387 D WifiNative-p2p0: doBoolean: SET device_name G3
09-12 14:43:34.608  1032  1396 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
09-12 14:43:34.608  1032  1387 D WifiNative-p2p0: SET device_name G3: returned true
09-12 14:43:34.608  1032  1387 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
09-12 14:43:34.608  1032  1387 D LGWifiP2pService: before postfix = G3
09-12 14:43:34.608  1032  1387 D WifiServerServiceExt: postfix byte check : 2
09-12 14:43:34.609  1032  1387 D LGWifiP2pService: after postfix = G3
09-12 14:43:34.609  1032  1387 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
09-12 14:43:34.609  1032  1396 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
09-12 14:43:34.609  1032  1387 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
09-12 14:43:34.609  1032  1387 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
09-12 14:43:34.609  1032  1387 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
09-12 14:43:34.609  1032  1387 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
09-12 14:43:34.609  1032  1396 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=214209  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-12 14:43:34.609  1032  1387 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
09-12 14:43:34.609  1032  1387 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
09-12 14:43:34.610  1032  1387 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
09-12 14:43:34.610  1032  1387 D WifiNative-HAL: p2pGetDeviceAddress
09-12 14:43:34.610  1032  1387 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
09-12 14:43:34.610  1032  1396 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=214210  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-12 14:43:34.610  1032  1387 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
09-12 14:43:34.610  1032  1387 D WifiNative-p2p0: doBoolean: P2P_FLUSH
09-12 14:43:34.610  1032  1387 D WifiNative-p2p0: P2P_FLUSH: returned true
09-12 14:43:34.610  1032  1387 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
09-12 14:43:34.610  6669  6725 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
09-12 14:43:34.610  1032  1396 E WifiStateMachine:  DisconnectedState what:132106 1 0
09-12 14:43:34.610  1032  1387 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returne,d true
09-12 14:43:34.611  1032  1387 D WifiNative-p2p0: doString: [LIST_NETWORKS]
09-12 14:43:34.611  1032  1396 E WifiStateMachine:  ConnectModeState what:132106 1 0
09-12 14:43:34.611  1032  1387 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
09-12 14:43:34.611  1032  1387 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
09-12 14:43:34.611  6669  6725 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
09-12 14:43:34.611  1032  1396 E WifiStateMachine:  DriverStartedState what:132106 1 0
09-12 14:43:34.611  1032  1396 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
09-12 14:43:34.613  6669  6725 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@e38adcf Bundle[{}]
09-12 14:43:34.613  1941  1941 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
09-12 14:43:34.613  6669  6725 I io.jxcore.node.LifeCycleMonitor: start: OK
09-12 14:43:34.613  6669  6725 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-12 14:43:34.614  1032  1032 D WifiScanningService: SCAN_AVAILABLE : 3
09-12 14:43:34.614  1032  1032 D RttService: SCAN_AVAILABLE : 3
09-12 14:43:34.614  1941  1941 D WfdsService: isConnected: false
09-12 14:43:34.614  6669  6725 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-12 14:43:34.614  1032  1553 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-12 14:43:34.614  1032  1553 I WifiNative-HAL: startHal
09-12 14:43:34.614  1032  1554 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-12 14:43:34.614  6669  6725 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-12 14:43:34.615  6669  6725 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-12 14:43:34.615  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 14:43:34.615  1599  1599 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-12 14:43:34.616  6669  6725 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
09-12 14:43:34.616  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 14:43:34.617  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 14:43:34.617  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 14:43:34.617  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-12 14:43:34.618  1941  1941 I WfdStateTracker: handleP2pThisDeviceChanged
09-12 14:43:34.619  1941  1941 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
09-12 14:43:34.619  1941  1941 D WfdsService: Update P2p Interface State: 3
09-12 14:43:34.622  7938  7938 E wpa_supplicant: nWIFIDualbandAPConnection: 1
09-12 14:43:34.622  1032  1387 D WifiNative-p2p0: SAVE_CONFIG: returned true
09-12 14:43:34.622  1032  1387 D LGWifiP2pService: sending p2p persistent groups changed broadcast
09-12 14:43:34.622  1032  1387 D LGWifiP2pService: InactiveState
09-12 14:43:34.622  1032  1387 D LGWifiP2pService: InactiveState{ when=-11ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-12 14:43:34.622  1032  1387 D LGWifiP2pService: P2pEnabledState{ when=-12ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-12 14:43:34.622  1032  1387 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
09-12 14:43:34.622  1032  1396 E WifiStateMachine:  DisconnectedState what:132096 -100 0
09-12 14:43:34.623  1032  1396 E WifiStateMachine:  ConnectModeState what:132096 -100 0
09-12 14:43:34.623  7938  7938 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-12 14:43:34.623  7,938  7938 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-12 14:43:34.623  1032  1396 E WifiStateMachine:  DriverStartedState what:132096 -100 0
09-12 14:43:34.623  1032  1396 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
09-12 14:43:34.624  7938  7938 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-12 14:43:34.624  7938  7938 E wpa_supplicant: disconnect_rssi_lvl: -100
09-12 14:43:34.624  7938  7938 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 14:43:34.624  7938  7938 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 14:43:34.624  1032  1396 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
09-12 14:43:34.625  1032  1396 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
09-12 14:43:34.625  1941  7997 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-12 14:43:34.625  1941  7997 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-12 14:43:34.625  1032  7978 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-12 14:43:34.625  1941  7997 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-12 14:43:34.625  1032  7978 E WifiMonitor: WifiMonitor:p2p0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-12 14:43:34.625  1032  7978 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-12 14:43:34.625  1032  1396 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
09-12 14:43:34.625  1032  7978 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-12 14:43:34.625  1032  1396 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
09-12 14:43:34.625  1032  7978 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-12 14:43:34.625  1032  1387 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
09-12 14:43:34.625  1032  7978 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 14:43:34.625  1032  7978 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 14:43:34.625  1032  7978 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 14:43:34.625  1032  1387 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-12 14:43:34.625  1032  7978 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-12 14:43:34.625  1032  1387 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-12 14:43:34.625  1032  7978 E WifiMonitor: WifiMonitor:p2p0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 14:43:34.625  1032  1387 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-12 14:43:34.625  1032  7978 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 14:43:34.625  1032  7978 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 14:43:34.626  1032  1387 D LGWifiP2pService: InactiveState{ when=0 what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-12 14:43:34.626  1032  1553 D wifi    : getting scan capabilities on interface[1] = 0x957915c0
09-12 14:43:34.626  1032  1553 D wifi    : failed to get capabilities : -3
09-12 14:43:34.626  1032  1553 E WifiScanningService: could not get scan capabilities
09-12 14:43:34.626  1032  1387 D LGWifiP2pService: P2pEnabledState{ when=0 what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-12 14:43:34.626  1032  1387 D LGWifiP2pService: DefaultState{ when=0 what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-12 14:43:34.626  1032  1387 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-12 14:43:34.626  1032  1387 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-12 14:43:34.626  1032  1387 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-12 14:43:34.626  1941  2410 W WfdsService: DefaultState - msg [9441285] is not handled
09-12 14:43:34.626  1032  1387 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-12 14:43:34.626  1032  1387 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-12 14:43:34.626  1032  1387 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-12 14:43:34.627  1032  1032 E WifiServerServiceExt: No p2p device connected
09-12 14:43:34.627  6669  6725 I System.out: Running OutgoingSocketThread
09-12 14:43:34.628  6738  6738 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-12 14:43:34.628  7938  7938 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-12 14:43:34.629  1032  1903 I ActivityManager: Killing 7040:com.lge.drmservice/u0a62 (adj 15): empty #17
09-12 14:43:34.629  7938  7938 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-12 14:43:34.630  6669  8000 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 857)
09-12 14:43:34.630  7938  7938 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-12 14:43:34.630  7938  7938 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 14:43:34.631  1032  1396 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
09-12 14:43:34.631  6669  8000 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 40138
09-12 14:43:34.631  1032  7978 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-12 14:43:34.631  1032  7978 E WifiMonitor: WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-12 14:43:34.631  6669  8000 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
09-12 14:43:34.631  1032  7978 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-12 14:43:34.631  1032  7978 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-12 14:43:34.631  1032  7978 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-12 14:43:34.631  1032  7978 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 14:43:34.631  7938  7938 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 14:43:34.631  1032  7978 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 14:43:34.631  1032  7978 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 14:43:34.631  1032  1396 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
09-12 14:43:34.631  1032  7978 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-12 14:43:34.631  1032  7978 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 14:43:34.631  1032  7978 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 14:43:34.631  1032  7978 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 14:43:34.631  1032  1396 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
09-12 14:43:34.631  1032  1387 D LGWifiP2pService: InactiveState{ when=-1ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-12 14:43:34.631  1032  1387 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-12 14:43:34.632  1032  1396 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
09-12 14:43:34.632  1032  1396 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
09-12 14:43:34.632  1941  7997 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-12 14:43:34.632  7938  7938 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
09-12 14:43:34.632  1941  7997 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-12 14:43:34.632  7938  7938 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-12 14:43:34.632  1032  7978 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
09-12 14:43:34.632  1032  7978 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-12 14:43:34.632  1032  7978 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-12 14:43:34.632  1032  7978 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-12 14:43:34.633  1032  1396 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
09-12 14:43:34.633  1032  1396 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
09-12 14:43:34.633  1032  1396 D WifiNative-wlan0: BSS_FLUSH 0: returned true
09-12 14:43:34.634  1032  1396 D WifiNative-wlan0: doBoolean: SCAN
09-12 14:43:34.634  1032  1396 D WifiNative-wlan0: SCAN: returned false
09-12 14:43:34.634  1032  1396 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=214234  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-12 14:43:34.659  1032  1049 W libprocessgroup: failed to open /acct/uid_10062/pid_7040/cgroup.procs: No such file or directory
,09-12 14:43:34.660  1032  1396 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=214260  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-12 14:43:34.660  1032  1396 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-12 14:43:34.661  1032  1396 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-12 14:43:34.661  1032  1396 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-12 14:43:34.662  1032  1396 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-12 14:43:34.662  1032  1396 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-12 14:43:34.664  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 14:43:34.664  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 14:43:34.664  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 14:43:34.664  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-12 14:43:34.664  1599  1599 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-12 14:43:34.664  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-12 14:43:34.665  1032  1032 D WifiServerServiceExt: setSupplicantStateSCANNING
09-12 14:43:34.666  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 14:43:34.667  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-12 14:43:34.667  1032  1032 D WifiServerServiceExt: setSupplicantStateSCANNING
09-12 14:43:34.675  7979  7979 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-12 14:43:34.678  6738  6738 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-12 14:43:34.681  7957  8002 W FormManager: Network not available. Please check & try again.
09-12 14:43:34.684  6738  6738 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-12 14:43:34.686  7957  8003 V FormManager: Network unavailable.
09-12 14:43:34.690  7957  8003 V FormManager: Network unavailable.
,09-12 14:43:34.701  4334  4334 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-12 14:43:34.701  4334  4334 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-12 14:43:34.702  4334  4334 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-12 14:43:34.705  4334  4334 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-12 14:43:34.710  4334  8004 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-12 14:43:34.713  4334  8005 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-12 14:43:34.713  4334  8005 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-12 14:43:34.793  1032  1903 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8006 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,09-12 14:43:34.816   335   335 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 433us total 20.954ms
,09-12 14:43:34.834   335   335 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 366us total 17.195ms
,09-12 14:43:34.850   335   335 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 294us total 14.468ms
,09-12 14:43:34.912  8006  8006 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-12 14:43:34.912  8006  8006 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
09-12 14:43:34.923  8006  8006 V [BNRBootReceiver]: Boot Receiver Return
09-12 14:43:34.925  8006  8006 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-12 14:43:34.989  1032  1049 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8024 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-12 14:43:34.990  1032  1049 I ActivityManager: Killing 7067:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
,09-12 14:43:35.039  1032  1940 W libprocessgroup: failed to open /acct/uid_10085/pid_7067/cgroup.procs: No such file or directory
,09-12 14:43:35.063  8024  8024 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-12 14:43:35.089  8024  8024 D PluginManager: init()
,09-12 14:43:35.260  7938  7938 E wpa_supplicant: USIM:  scard_init function
09-12 14:43:35.261  7938  7938 I wpa_supplicant: Trying to associate with SSID 'NG700'
,09-12 14:43:35.263  1032  7978 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
09-12 14:43:35.264  1032  7978 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
09-12 14:43:35.264  1032  7978 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
09-12 14:43:35.264  1032  7978 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: WPS-AP-AVAILABLE 
09-12 14:43:35.264  1032  7978 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
09-12 14:43:35.264  1032  7978 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
09-12 14:43:35.264  1032  7978 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
09-12 14:43:35.265  1032  1396 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
09-12 14:43:35.266  1032  1396 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
09-12 14:43:35.268  1032  1396 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
09-12 14:43:35.269  1032  1396 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
09-12 14:43:35.269  1032  1396 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
09-12 14:43:35.276  1032  1396 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=214875  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,09-12 14:43:35.280  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 14:43:35.280  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 14:43:35.280  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-12 14:43:35.280  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 14:43:35.280  1599  1599 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-12 14:43:35.282  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 14:43:35.282  1032  1396 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=214881  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-12 14:43:35.285  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-12 14:43:35.285  1032  1032 D WifiServerServiceExt: setSupplicantStateASSOCIATING
09-12 14:43:35.378  1032  7978 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
09-12 14:43:35.378  7938  7938 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
09-12 14:43:35.378  1032  7978 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
09-12 14:43:35.379  1032  7978 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
09-12 14:43:35.379  1032  7978 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: Associated with f4:f2:6d:22:99:3e
09-12 14:43:35.381  1032  1396 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=214980  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-12 14:43:35.381  1032  1396 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=214981  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-12 14:43:35.382  1032  1396 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=214982
09-12 14:43:35.382  1032  1396 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=214982
,09-12 14:43:35.385  1032  7978 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
,09-12 14:43:35.385  1032  7978 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-12 14:43:35.386  1032  1396 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=214986
09-12 14:43:35.386  1032  1396 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=214986
09-12 14:43:35.387  1032  1396 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=214987
09-12 14:43:35.389  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-12 14:43:35.389  1032  1032 D WifiServerServiceExt: setSupplicantStateASSOCIATED
09-12 14:43:35.390  1032  1094 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-12 14:43:35.393  1032  1396 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=214992  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-12 14:43:35.395  1032  1396 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=214994  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-12 14:43:35.395  1032  7978 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-12 14:43:35.395  1032  7978 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-12 14:43:35.395  1032  1396 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
09-12 14:43:35.396  1032  1396 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
,09-12 14:43:35.396  7938  7938 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-12 14:43:35.396  1032  7978 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
09-12 14:43:35.396  7938  7938 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-12 14:43:35.396  1032  7978 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-12 14:43:35.396  1032  1396 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
09-12 14:43:35.396  1032  7978 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-12 14:43:35.396  1032  7978 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
09-12 14:43:35.396  1032  7978 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-12 14:43:35.396  1032  7978 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-12 14:43:35.397  1032  1396 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
09-12 14:43:35.397  1032  7978 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-12 14:43:35.397  1032  7978 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-12 14:43:35.397  1032  1396 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-12 14:43:35.399  1032  1396 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=214999  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-12 14:43:35.403  1032  1396 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=215002  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-12 14:43:35.403  1032  1396 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=215003
09-12 14:43:35.404  1032  1396 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=215003
09-12 14:43:35.404  1032  1396 D WifiNative-wlan0: doString: [STATUS]
09-12 14:43:35.404  1032  7978 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-12 14:43:35.404  1032  7978 E WifiMonitor: WifiMonitor:wlan0 cnt=64 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-12 14:43:35.405  1032  1396 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-12 14:43:35.406  1032  1396 I WifiServiceExtension: setVHTCapabilityType  : false
09-12 14:43:35.413  1032  1396 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
09-12 14:43:35.413  1032  1396 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,09-12 14:43:35.422  1032  1396 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
09-12 14:43:35.423  1032  1466 D ConnectivityService: Got NetworkAgent Messenger
09-12 14:43:35.423  1032  1466 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-12 14:43:35.423  1032  1466 D ConnectivityService: NetworkAgent connected
09-12 14:43:35.423  1032  1396 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-12 14:43:35.423  1032  1396 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-12 14:43:35.424  1032  1396 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-12 14:43:35.424  1032  1396 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-12 14:43:35.430  1032  1396 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-12 14:43:35.430  1032  1396 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-12 14:43:35.430  1032  1396 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-12 14:43:35.430  1032  1396 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-12 14:43:35.431  1032  1396 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-12 14:43:35.434  1032  1396 D WifiNative-wlan0: SAVE_CONFIG: returned true
,09-12 14:43:35.436   306   892 D CommandListener: Setting iface cfg
09-12 14:43:35.441  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 14:43:35.441  1599  1599 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-12 14:43:35.443  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 14:43:35.444  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 14:43:35.444  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 14:43:35.445  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,09-12 14:43:35.449  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 14:43:35.449  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 14:43:35.450  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
09-12 14:43:35.450  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-12 14:43:35.450  1032  1032 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
09-12 14:43:35.458  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 14:43:35.458  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 14:43:35.458  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-12 14:43:35.463  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 14:43:35.463  1599  1599 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-12 14:43:35.465  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 14:43:35.468  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 14:43:35.468  1599  1599 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-12 14:43:35.468  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 14:43:35.468  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 14:43:35.469  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-12 14:43:35.469  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 14:43:35.469  1032  1396 E WifiStateMachine: Start Dhcp Watchdog 3
,09-12 14:43:35.470  1032  1396 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=215070  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-12 14:43:35.470  1032  1396 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=215070  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-12 14:43:35.471  1032  1396 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=215071  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-12 14:43:35.472  1032  1396 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=215071  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-12 14:43:35.472  1032  1396 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=215072  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-12 14:43:35.473  1032  1396 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=215072  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-12 14:43:35.474  1032  1396 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14378] from screen [on:0 period:510432946] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-12 14:43:35.475  1032  1396 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:510432947] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-12 14:43:35.475  1032  1396 D WifiNative-wlan0: doString: [SIGNAL_POLL]
09-12 14:43:35.475  1032  8045 D DhcpStateMachine: StoppedState
09-12 14:43:35.476  1032  8045 D DhcpStateMachine: StoppedState{ when=-6ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
09-12 14:43:35.476  1032  8045 D DhcpStateMachine: WaitBeforeStartState
09-12 14:43:35.476  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-12 14:43:35.476  1032  1032 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
09-12 14:43:35.477  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 14:43:35.477  1599  1599 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-12 14:43:35.479  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 14:43:35.479  1032  1466 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
09-12 14:43:35.480  1032  1396 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 14:43:35.480  1032  1396 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 14:43:35.481  1032  1396 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
,09-12 14:43:35.481  1032  1396 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,09-12 14:43:35.485  1032  1396 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 14:43:35.486  1032  1396 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 14:43:35.486  1032  1466 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-12 14:43:35.487  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-12 14:43:35.487  1032  1032 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-12 14:43:35.488  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-12 14:43:35.488  1032  1032 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-12 14:43:35.488  1032  1396 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=136,0,0
09-12 14:43:35.489  1032  1396 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=136,0,0
09-12 14:43:35.489  1032  1396 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
09-12 14:43:35.489  7938  7938 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
09-12 14:43:35.489  1032  1396 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
09-12 14:43:35.490  1032  1396 D WifiNative-wlan0: doBoolean: SET ps 0
09-12 14:43:35.490  1032  1396 D WifiNative-wlan0: SET ps 0: returned true
09-12 14:43:35.490  1032  1396 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
09-12 14:43:35.490  7938  7938 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
09-12 14:43:35.491  1032  1396 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
09-12 14:43:35.491  1032  1396 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
09-12 14:43:35.491  1032  1396 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-12 14:43:35.491  1032  1387 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@13a61d2b target=com.android.internal.util.StateMachine$SmHandler }
09-12 14:43:35.491  1032  1387 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@13a61d2b target=com.android.internal.util.StateMachine$SmHandler }
09-12 14:43:35.491  1032  1396 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-12 14:43:35.491  1032  8045 D DhcpStateMachine: WaitBeforeStartState{ when=-1ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
09-12 14:43:35.491  1032  8045 D DhcpStateMachine: DHCP Start wake lock is acquired.
09-12 14:43:35.492   306   892 D CommandListener: Setting iface cfg
09-12 14:43:35.492   306   892 D CommandListener: Trying to bring up wlan0
09-12 14:43:35.493  1032  1396 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
09-12 14:43:35.493  1032  1396 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK 
09-12 14:43:35.494  1032  1396 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK 
09-12 14:43:35.494  1032  1396 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-12 14:43:35.494  1032  1387 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-12 14:43:35.494  1032  1387 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-12 14:43:35.494  7938  7938 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-12 14:43:35.494  1032  1396 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-12 14:43:35.494  1032  1396 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
09-12 14:43:35.495  7938  7938 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
09-12 14:43:35.495  1032  1396 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
09-12 14:43:35.495  1032  1396 D WifiNative-wlan0: doBoolean: SET ps 1
,09-12 14:43:35.505  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 14:43:35.518  1032  1396 D WifiNative-wlan0: SET ps 1: returned true
09-12 14:43:35.518  1032  1466 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
,09-12 14:43:35.518  1032  1396 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-12 14:43:35.519  1032  1396 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-12 14:43:35.519  1032  1396 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-12 14:43:35.520  1032  1396 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,09-12 14:43:35.520  1032  1396 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-12 14:43:35.520  1032  1396 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-12 14:43:35.521  1032  1466 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-12 14:43:35.521  1032  1396 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-12 14:43:35.522  1032  1396 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
,09-12 14:43:35.522  1032  1396 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-12 14:43:35.522  1032  1466 D ConnectivityService: ignoring duplicate network state non-change
09-12 14:43:35.526  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 14:43:35.526  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 14:43:35.526  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-12 14:43:35.526  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 14:43:35.527  1599  1599 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-12 14:43:35.528  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 14:43:35.531  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 14:43:35.531  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 14:43:35.531  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-12 14:43:35.532  1032  1466 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-12 14:43:35.533  1032  1466 D ConnectivityService: Adding iface wlan0 to network 102
09-12 14:43:35.536  1032  1032 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-12 14:43:35.537  1941  1941 V WfdStateTracker: handleWifiStateChangedEvent: 1
09-12 14:43:35.539  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 14:43:35.539  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 14:43:35.539  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-12 14:43:35.540  1032  1032 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-12 14:43:35.541  1032  1396 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-12 14:43:35.544  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 14:43:35.544  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 14:43:35.544  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-12 14:43:35.552  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 14:43:35.552  1599  1599 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-12 14:43:35.554  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 14:43:35.557  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-12 14:43:35.557  1599  1599 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-12 14:43:35.557  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 14:43:35.561  1032  1466 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-12 14:43:35.561  1032  1466 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
09-12 14:43:35.561  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 14:43:35.561  1599  1599 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-12 14:43:35.561  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 14:43:35.562  1032  1466 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
09-12 14:43:35.562   306   892 E Netd    : netlink response contains error (File exists)
09-12 14:43:35.563  1032  1466 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
09-12 14:43:35.564  1032  1466 D ConnectivityService: addLocalRoutetoDefaultNetwork
09-12 14:43:35.564  1032  1466 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
09-12 14:43:35.564  1032  1466 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
09-12 14:43:35.565  1032  1466 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-12 14:43:35.565  1032  1466 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-12 14:43:35.565  1032  1466 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
09-12 14:43:35.565  1032  1466 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
09-12 14:43:35.565  1032  1466 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-12 14:43:35.565  1032  8044 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-12 14:43:35.565  1032  1466 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-12 14:43:35.565  1032  8044 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
09-12 14:43:35.565  1032  1466 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-12 14:43:35.565  1032  1466 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 14:43:35.565  1032  8044 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-12 14:43:35.565  1032  1466 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
09-12 14:43:35.565  1032  1466 D ConnectivityService: currentScore = 0, newScore = 20
09-12 14:43:35.565  1032  1466 D ConnectivityService:    accepting network in place of null
09-12 14:43:35.565  1032  8044 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-12 14:43:35.565  1032  1466 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 14:43:35.566  1032  1396 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 14:43:35.566  1032  1396 D WIFI    :   my score=60, my filter=[ Transports: WIFI Ca,pabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-12 14:43:35.567  1032  1466 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-12 14:43:35.567  1032  1466 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
09-12 14:43:35.568  1032  1466 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-12 14:43:35.568   306  8055 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
,09-12 14:43:35.570  1852  1852 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 14:43:35.570  1852  1852 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-12 14:43:35.572  1032  1466 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-12 14:43:35.573  1032  1466 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
09-12 14:43:35.573  1032  1466 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
09-12 14:43:35.574  1032  1032 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
09-12 14:43:35.574  1032  1032 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-12 14:43:35.574  1032  1032 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-12 14:43:35.574  1032  1032 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-12 14:43:35.574  1032  1466 D ConnectivityService: validation of new default Network = false
09-12 14:43:35.574  1032  1466 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
09-12 14:43:35.574  1032  1466 D DSQN    : enableDataServiceNotify 
09-12 14:43:35.574  1032  1466 D DSQN    : start dsqn bin
09-12 14:43:35.578  1032  1466 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
09-12 14:43:35.578  1032  1466 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 14:43:35.578  1032  1466 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-12 14:43:35.578  1032  1466 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-12 14:43:35.571  8056  8056 W dsqn    : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-12 14:43:35.571  8056  8056 W dsqn    : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-12 14:43:35.580  1599  2069 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-12 14:43:35.588  1032  1386 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
09-12 14:43:35.593  8056  8056 E DSQN    : DSQN ssw
,09-12 14:43:35.599  1599  1599 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,09-12 14:43:35.599  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 14:43:35.600  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 14:43:35.625   306  8055 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,09-12 14:43:35.628  6669  6725 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 858)
,09-12 14:43:35.628  6669  6725 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 858)
09-12 14:43:35.631  6669  6725 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 863)
09-12 14:43:35.631  6669  6725 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-12 14:43:35.631  6669  6725 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 864)
09-12 14:43:35.633  6669  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 14:43:35.633  6669  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f97aeea added. We now have 2 listener(s)
09-12 14:43:35.634  1032  1932 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 14:43:35.635  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-12 14:43:35.635  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 14:43:35.635  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 14:43:35.636  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 14:43:35.636  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ddcf5db added. We now have 9 listener(s)
09-12 14:43:35.636  6669  6725 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 14:43:35.636  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-12 14:43:35.637  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 14:43:35.642  6669  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 14:43:35.642  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 14:43:35.642  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 14:43:35.642  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 14:43:35.642  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 14:43:35.642  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 14:43:35.642  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 14:43:35.642  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 14:43:35.643  6669  6725 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 14:43:35.643  6669  6725 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 14:43:35.643  6669  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 14:43:35.643  6669  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19f8ab51 added. We now have 3 listener(s)
09-12 14:43:35.644  1032  1932 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 14:43:35.646  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-12 14:43:35.646  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 14:43:35.646  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 14:43:35.646  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 14:43:35.646  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24b9cfb6 added. We now have 10 listener(s)
09-12 14:43:35.646  6669  6725 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 14:43:35.646  6669  6725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 14:43:35.646  6669  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 14:43:35.646  6669  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 14:43:35.646  6669  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 14:43:35.646  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:43:35.646  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 14:43:35.646  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 14:43:35.646  6669  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f97aeea removed from the list
09-12 14:43:35.646  6669  6725 I org.thaliproject.p2p.btconnectorlib.Disc,overyManager: dispose
09-12 14:43:35.646  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ddcf5db removed from the list
09-12 14:43:35.648  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 14:43:35.648  6669  6725 D io.jxcore.node.ConnectivityMonitor: stop
09-12 14:43:35.648  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:43:35.649  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:43:35.649  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:43:35.650  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 14:43:35.650  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 14:43:35.650  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:43:35.650  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 14:43:35.650  6669  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ddcf5db not in the list
09-12 14:43:35.650  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:43:35.650  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:43:35.651  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 14:43:35.651  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 14:43:35.651  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:43:35.652  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24b9cfb6 removed from the list
09-12 14:43:35.652  6669  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 14:43:35.652  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:43:35.652  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:43:35.652  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 14:43:35.652  6669  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19f8ab51 removed from the list
,09-12 14:43:35.654  6669  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 14:43:35.654  6669  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d2b14b7 added. We now have 2 listener(s)
09-12 14:43:35.655  1032  1976 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 14:43:35.658  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-12 14:43:35.658  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 14:43:35.658  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 14:43:35.658  8024  8024 W ExternalStrings: load override strings
09-12 14:43:35.658  8024  8024 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
09-12 14:43:35.658  8024  8024 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
09-12 14:43:35.658  8024  8024 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
09-12 14:43:35.658  8024  8024 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
09-12 14:43:35.658  8024  8024 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
09-12 14:43:35.658  8024  8024 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
09-12 14:43:35.658  8024  8024 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
09-12 14:43:35.658  8024  8024 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
09-12 14:43:35.658  8024  8024 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
09-12 14:43:35.658  8024  8024 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
09-12 14:43:35.658  8024  8024 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
09-12 14:43:35.658  8024  8024 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 14:43:35.658  8024  8024 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
09-12 14:43:35.658  8024  8024 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-12 14:43:35.658  8024  8024 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 14:43:35.658  8024  8024 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 14:43:35.658  8024  8024 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-12 14:43:35.658  8024  8024 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-12 14:43:35.659  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 14:43:35.659  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@831c424 added. We now have 9 listener(s)
09-12 14:43:35.659  6669  6725 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 14:43:35.659  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-12 14:43:35.660  8024  8024 D StatusProvider: onCreate
09-12 14:43:35.662  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 14:43:35.666  6669  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 14:43:35.666  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 14:43:35.666  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 14:43:35.666  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 14:43:35.666  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 14:43:35.666  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 14:43:35.666  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 14:43:35.666  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 14:43:35.668  6669  6725 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 14:43:35.668  6669  6725 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 14:43:35.668  6669  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 14:43:35.668  6669  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@70b3142 added. We now have 3 listener(s)
09-12 14:43:35.668  1032  1049 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 14:43:35.670   306  8055 D libc-netbsd: res_queryN name = clients3.google.com succeed
09-12 14:43:35.670  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 14:43:35.671  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 14:43:35.672  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-12 14:43:35.672  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 14:43:35.672  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 14:43:35.672  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 14:43:35.672  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d24553 added. We now have 10 listener(s)
09-12 14:43:35.672  6669  6725 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 14:43:35.672  6669  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 14:43:35.672  6669  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 14:43:35.672  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 14:43:35.672  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 14:43:35.672  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-12 14:43:35.674  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-12 14:43:35.674  1032  1904 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 14:43:35.677  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-12 14:43:35.677  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-12 14:43:35.678  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-12 14:43:35.679  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 14:43:35.680  6669  6725 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,09-12 14:43:35.680  6669  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 14:43:35.680  6669  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 14:43:35.681  6669  6725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 14:43:35.681  6669  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 14:43:35.681  6669  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 14:43:35.682  6669  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 14:43:35.682  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:43:35.682  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 14:43:35.682  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 14:43:35.682  6669  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d2b14b7 removed from the list
09-12 14:43:35.682  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:43:35.682  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@831c424 removed from the list
09-12 14:43:35.682  6669  6725 D io.jxcore.node.ConnectivityMonitor: stop
09-12 14:43:35.682  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 14:43:35.687  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 14:43:35.687  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 14:43:35.688  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 14:43:35.688  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 14:43:35.688  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:43:35.688  6669  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@831c424 not in the list
09-12 14:43:35.688  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 14:43:35.688  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:43:35.689  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 14:43:35.689  6669  6725 D BluetoothLeScanner: could not find callback wrapper
,09-12 14:43:35.689  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 14:43:35.689  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 14:43:35.689  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 14:43:35.689  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d24553 removed from the list
09-12 14:43:35.689  6669  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 14:43:35.689  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 14:43:35.689  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:43:35.689  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 14:43:35.689  6669  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@70b3142 removed from the list
,09-12 14:43:35.690  6669  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 14:43:35.690  6669  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f1f1f8e added. We now have 2 listener(s)
09-12 14:43:35.690  1032  1572 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 14:43:35.691  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-12 14:43:35.691  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 14:43:35.691  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 14:43:35.691  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 14:43:35.691  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31b1e3af added. We now have 9 listener(s)
09-12 14:43:35.691  6669  6725 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 14:43:35.692  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-12 14:43:35.693  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 14:43:35.695  1032  8045 D DhcpStateMachine: DHCPV4 request on wlan0
09-12 14:43:35.695  6669  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 14:43:35.695  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 14:43:35.695  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 14:43:35.695  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 14:43:35.695  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 14:43:35.695  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 14:43:35.695  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 14:43:35.695  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 14:43:35.696  1032  8045 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
09-12 14:43:35.696  1032  8045 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
09-12 14:43:35.696  6669  6725 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 14:43:35.696  6669  6725 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 14:43:35.698  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 14:43:35.699   306   891 D LGDataListener: argv[0]=dsqncommand
09-12 14:43:35.699   306   891 D LGDataListener: argv[1]=wlan0
09-12 14:43:35.699   306   891 D LGDataListener: argv[2]=1
,09-12 14:43:35.699   306   891 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1,
09-12 14:43:35.699  1032  1092 D DSQN    : DSQM DsqnNotification wlan0  1
09-12 14:43:35.699  1032  1092 D DSQN    : start to monitor internet connection
09-12 14:43:35.699  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
09-12 14:43:35.700  6669  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 14:43:35.700  6669  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b87bf45 added. We now have 3 listener(s)
,09-12 14:43:35.700  1032  1904 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 14:43:35.701  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,09-12 14:43:35.701  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 14:43:35.701  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-12 14:43:35.702  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 14:43:35.702  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1971a69a added. We now have 10 listener(s)
09-12 14:43:35.702  6669  6725 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 14:43:35.702  6669  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 14:43:35.702  6669  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 14:43:35.702  6669  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only,
09-12 14:43:35.702  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 14:43:35.702  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 14:43:35.702  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-12 14:43:35.691  8062  8062 W dhcpcd  : type=1400 audit(0.0:195): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-12 14:43:35.691  8062  8062 W dhcpcd  : type=1400 audit(0.0:196): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-12 14:43:35.712  8062  8062 I dhcpcd  : version 5.5.6 starting
09-12 14:43:35.713  8062  8062 E dhcpcd  : get_duid: m
09-12 14:43:35.713  8062  8062 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
09-12 14:43:35.713  8062  8062 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
09-12 14:43:35.713  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-12 14:43:35.714  1032  1932 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 14:43:35.716  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-12 14:43:35.716  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-12 14:43:35.717  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-12 14:43:35.718  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 14:43:35.719  6669  6725 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-12 14:43:35.719  6669  6725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 14:43:35.719  6669  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 14:43:35.719  6669  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 14:43:35.719  6669  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 14:43:35.719  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:43:35.719  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 14:43:35.719  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 14:43:35.719  6669  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f1f1f8e removed from the list
09-12 14:43:35.719  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:43:35.719  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31b1e3af removed from the list
09-12 14:43:35.719  6669  6725 D io.jxcore.node.ConnectivityMonitor: stop
09-12 14:43:35.719  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:43:35.720  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:43:35.720  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:43:35.720  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 14:43:35.720  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 14:43:35.720  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:43:35.720  6669  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31b1e3af not in the list
09-12 14:43:35.720  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:43:35.720  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:43:35.721  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 14:43:35.721  6669  6725 D BluetoothLeScanner: could not find callback wrapper
09-12 14:43:35.721  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 14:43:35.721  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 14:43:35.721  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:43:35.721  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1971a69a removed from the list
09-12 14:43:35.721  6669  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 14:43:35.721  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:43:35.721  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:43:35.721  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 14:43:35.721  6669  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b87bf45 removed from the list
09-12 14:43:35.721  6669  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 14:43:35.721  6669  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33ea0ac1 added. We now have 2 listener(s)
09-12 14:43:35.722  1032  1780 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 14:43:35.723  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-12 14:43:35.723  1032  8044 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 12 Sep 2016 12:43:35 GMT], X-Android-Received-Millis=[1473684215723], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473684215699]}
09-12 14:43:35.723  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 14:43:35.723  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 14:43:35.723  1032  8044 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-12 14:43:35.723  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 14:43:35.723  1032  8044 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
09-12 14:43:35.723  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c339266 added. We now have 9 listener(s)
09-12 14:43:35.723  6669  6725 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 14:43:35.724  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-12 14:43:35.724  1032  1466 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
09-12 14:43:35.724  1032  1466 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
09-12 14:43:35.724  1032  1466 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-12 14:43:35.724  1032  1466 D ConnectivityService:   chec,king if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-12 14:43:35.724  1032  1466 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-12 14:43:35.724  1032  1466 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
09-12 14:43:35.724  1032  1466 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
09-12 14:43:35.724  1032  1466 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 14:43:35.724  1032  1466 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-12 14:43:35.724  1032  1466 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-12 14:43:35.724  1032  1466 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 14:43:35.725  1032  1466 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-12 14:43:35.725  1599  2069 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-12 14:43:35.725  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 14:43:35.726  1032  1396 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 14:43:35.726  1032  1396 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-12 14:43:35.726  1852  1852 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 14:43:35.726  1852  1852 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-12 14:43:35.728  6669  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 14:43:35.728  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 14:43:35.728  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 14:43:35.728  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 14:43:35.728  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 14:43:35.728  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 14:43:35.728  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 14:43:35.728  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 14:43:35.733  6669  6725 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 14:43:35.733  6669  6725 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 14:43:35.734  6669  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 14:43:35.734  6669  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ba07e54 added. We now have 3 listener(s)
09-12 14:43:35.734  1032  1904 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 14:43:35.735  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 14:43:35.736  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 14:43:35.738  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-12 14:43:35.738  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 14:43:35.738  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 14:43:35.738  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 14:43:35.738  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12cb91fd added. We now have 10 listener(s)
09-12 14:43:35.738  6669  6725 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 14:43:35.738  6669  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 14:43:35.738  6669  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 14:43:35.739  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 14:43:35.739  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 14:43:35.739  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-12 14:43:35.741  1599  1599 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-12 14:43:35.742  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-12 14:43:35.742  1032  1903 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 14:43:35.742  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 14:43:35.742  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-12 14:43:35.745  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-12 14:43:35.745  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-12 14:43:35.746  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-12 14:43:35.746  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 14:43:35.748  6669  6725 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-12 14:43:35.750  8024  8024 V Signer  : override build config not found
09-12 14:43:35.750  8024  8024 D Signer  : value of property debug is false
09-12 14:43:35.750  6669  6725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 14:43:35.750  6669  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 14:43:35.750  6669  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 14:43:35.750  6669  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 14:43:35.750  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:43:35.750  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 14:43:35.750  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 14:43:35.750  6669  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33ea0ac1 removed from the list
09-12 14:43:35.750  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:43:35.750  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c339266 removed from the list
09-12 14:43:35.750  6669  6725 D io.jxcore.node.ConnectivityMonitor: stop
09-12 14:43:35.750  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:43:35.750  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:43:35.750  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:43:35.751  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 14:43:35.751  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 14:43:35.751  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:43:35.751  6669  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c339266 not in the list
09-12 14:43:35.751  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:43:35.751  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:43:35.751  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 14:43:35.752  6669  6725 D BluetoothLeScanner: could not find callback wrappe,r
09-12 14:43:35.752  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 14:43:35.752  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 14:43:35.752  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:43:35.752  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12cb91fd removed from the list
09-12 14:43:35.752  6669  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 14:43:35.752  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:43:35.752  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:43:35.752  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 14:43:35.752  6669  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ba07e54 removed from the list
09-12 14:43:35.752  6669  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 14:43:35.753  6669  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38b12bc0 added. We now have 2 listener(s)
09-12 14:43:35.753  1032  2012 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 14:43:35.754  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-12 14:43:35.754  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 14:43:35.754  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 14:43:35.754  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 14:43:35.754  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@354450f9 added. We now have 9 listener(s)
09-12 14:43:35.754  6669  6725 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 14:43:35.755  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-12 14:43:35.756  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 14:43:35.761  6669  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 14:43:35.761  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 14:43:35.761  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 14:43:35.761  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 14:43:35.761  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 14:43:35.761  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 14:43:35.761  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 14:43:35.761  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 14:43:35.762  6669  6725 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 14:43:35.762  6669  6725 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 14:43:35.762  6669  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 14:43:35.762  6669  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3529169f added. We now have 3 listener(s)
09-12 14:43:35.762  1032  1048 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 14:43:35.763  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 14:43:35.764  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-12 14:43:35.764  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 14:43:35.764  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 14:43:35.764  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 14:43:35.764  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@55d43ec added. We now have 10 listener(s)
09-12 14:43:35.764  6669  6725 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 14:43:35.765  6669  6725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 14:43:35.765  6669  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 14:43:35.765  6669  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 14:43:35.765  6669  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 14:43:35.765  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:43:35.765  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 14:43:35.765  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 14:43:35.765  6669  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38b12bc0 removed from the list
09-12 14:43:35.765  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:43:35.765  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@354450f9 removed from the list
09-12 14:43:35.765  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 14:43:35.765  6669  6725 D io.jxcore.node.ConnectivityMonitor: stop
09-12 14:43:35.765  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:43:35.765  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:43:35.765  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:43:35.766  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 14:43:35.766  6669  6725 I org.thaliproject.p2p.btconnect,orlib.DiscoveryManager: stopDiscovery
09-12 14:43:35.766  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:43:35.766  6669  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@354450f9 not in the list
09-12 14:43:35.766  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:43:35.766  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:43:35.766  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 14:43:35.766  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 14:43:35.766  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:43:35.766  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@55d43ec removed from the list
09-12 14:43:35.766  6669  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 14:43:35.766  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:43:35.766  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:43:35.766  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 14:43:35.766  6669  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3529169f removed from the list
09-12 14:43:35.767  6669  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-12 14:43:35.767  6669  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-12 14:43:35.767  6669  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-12 14:43:35.767  6669  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 14:43:35.768  6669  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-12 14:43:35.768  6669  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-12 14:43:35.774  6669  8069 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 871, name: My test thread name)
09-12 14:43:35.774  6669  8069 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 871, thread name: My test thread name)
09-12 14:43:35.775  6669  8069 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 871, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-12 14:43:35.778  8062  8062 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-12 14:43:35.778  8062  8062 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-12 14:43:35.778  8062  8062 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-12 14:43:35.778  6669  8070 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 873, name: My test thread name)
09-12 14:43:35.778  8062  8062 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
,09-12 14:43:35.778  6669  8070 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 873, thread name: My test thread name)
09-12 14:43:35.778  6669  8070 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 873, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
09-12 14:43:35.778  8062  8062 D dhcpcd  : wlan0: sending REQUEST (xid 0x1f311df9), next in 4.84 seconds
09-12 14:43:35.780  6669  6725 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
09-12 14:43:35.780  6669  6725 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-12 14:43:35.780  6669  6725 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-12 14:43:35.780  6669  6725 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-12 14:43:35.780  6669  6725 D com.test.thalitest.ThaliTestRunner: Total duration: 22850 ms
09-12 14:43:35.781  6669  6725 I jxcore-log: *Native tests were executed*
09-12 14:43:35.781  6669  6725 I jxcore-log: 
09-12 14:43:35.781  6669  6725 I jxcore-log: Total number of executed tests:  80
09-12 14:43:35.781  6669  6725 I jxcore-log: 
09-12 14:43:35.781  6669  6725 I jxcore-log: Number of passed tests:  80
09-12 14:43:35.781  6669  6725 I jxcore-log: 
09-12 14:43:35.781  6669  6725 I jxcore-log: Number of failed tests:  0
09-12 14:43:35.781  6669  6725 I jxcore-log: 
09-12 14:43:35.781  6669  6725 I jxcore-log: Number of ignored tests:  0
09-12 14:43:35.781  6669  6725 I jxcore-log: 
09-12 14:43:35.782  6669  6725 I jxcore-log: Total duration:  22850
09-12 14:43:35.782  6669  6725 I jxcore-log: 
09-12 14:43:35.782  6669  6725 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-12 14:43:35.782  6669  6725 I jxcore-log: 
09-12 14:43:35.785  6669  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 14:43:35.785  6669  6725 I jxcore-log: 
09-12 14:43:35.787  6669  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 14:43:35.787  6669  6725 I jxcore-log: 
09-12 14:43:35.788  6669  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 14:43:35.788  6669  6725 I jxcore-log: 
09-12 14:43:35.788  6669  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 14:43:35.788  6669  6725 I jxcore-log: 
09-12 14:43:35.789  6669  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 14:43:35.789  6669  6725 I jxcore-log: 
,09-12 14:43:35.790  6669  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 14:43:35.790  6669  6725 I jxcore-log: 
09-12 14:43:35.792  6669  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 14:43:35.792  6669  6725 I jxcore-log: 
,09-12 14:43:35.793  6669  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 14:43:35.793  6669  6725 I jxcore-log: 
09-12 14:43:35.793  6669  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 14:43:35.793  6669  6725 I jxcore-log: 
09-12 14:43:35.794  6669  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-12 14:43:35.794  6669  6725 I jxcore-log: 
09-12 14:43:35.795  6669  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 14:43:35.795  6669  6725 I jxcore-log: 
09-12 14:43:35.795  6669  6669 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-12 14:43:35.795  6669  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 14:43:35.795  6669  6725 I jxcore-log: 
09-12 14:43:35.796  6669  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 14:43:35.796  6669  6725 I jxcore-log: 
09-12 14:43:35.796  8024  8024 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
09-12 14:43:35.796  8024  8024 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
09-12 14:43:35.796  6669  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 14:43:35.796  6669  6725 I jxcore-log: 
09-12 14:43:35.797  8024  8024 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
09-12 14:43:35.797  8024  8024 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
,09-12 14:43:35.797  8024  8024 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
09-12 14:43:35.797  8024  8024 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
09-12 14:43:35.797  6669  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 14:43:35.797  6669  6725 I jxcore-log: 
,09-12 14:43:35.797  8024  8024 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
09-12 14:43:35.797  8024  8024 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
09-12 14:43:35.797  8024  8024 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
,09-12 14:43:35.798  8024  8024 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
09-12 14:43:35.798  8024  8024 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
09-12 14:43:35.798  6669  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 14:43:35.798  6669  6725 I jxcore-log: 
,09-12 14:43:35.798  8024  8024 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
09-12 14:43:35.798  8024  8024 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
09-12 14:43:35.798  6669  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 14:43:35.798  6669  6725 I jxcore-log: 
,09-12 14:43:35.799  6669  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 14:43:35.799  6669  6725 I jxcore-log: 
09-12 14:43:35.799  6669  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 14:43:35.799  6669  6725 I jxcore-log: 
09-12 14:43:35.800  6669  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 14:43:35.800  6669  6725 I jxcore-log: 
09-12 14:43:35.800  6669  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-12 14:43:35.800  6669  6725 I jxcore-log: 
,09-12 14:43:35.801  6669  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-12 14:43:35.801  6669  6725 I jxcore-log: 
09-12 14:43:35.801  6669  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 14:43:35.801  6669  6725 I jxcore-log: 
,09-12 14:43:35.802  6669  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 14:43:35.802  6669  6725 I jxcore-log: 
09-12 14:43:35.802  6669  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 14:43:35.802  6669  6725 I jxcore-log: 
09-12 14:43:35.802  6669  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 14:43:35.802  6669  6725 I jxcore-log: 
,09-12 14:43:35.803  6669  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 14:43:35.803  6669  6725 I jxcore-log: 
09-12 14:43:35.804  8024  8024 V LGMDMManager: Create singleton instance
09-12 14:43:35.831  8062  8062 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,09-12 14:43:35.839  8024  8024 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
,09-12 14:43:35.857  8062  8062 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
09-12 14:43:35.858  8062  8062 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
,09-12 14:43:35.858  8062  8062 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
09-12 14:43:35.859  8062  8062 D dhcpcd  : wlan0: adding default route via 192.168.1.1
09-12 14:43:35.859  8062  8062 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-12 14:43:35.860  8062  8062 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-12 14:43:35.860  8062  8062 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-12 14:43:35.860  8062  8062 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
09-12 14:43:35.926  8024  8024 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-12 14:43:35.927  8024  8079 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-12 14:43:35.939  6738  6738 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-12 14:43:35.945  6738  6738 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-12 14:43:35.990  1032  1976 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=8089 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
09-12 14:43:35.991  1032  1976 I ActivityManager: Killing 7098:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,09-12 14:43:36.067  8073  8073 D AndroidRuntime: 
09-12 14:43:36.067  8073  8073 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,09-12 14:43:36.069  8073  8073 D AndroidRuntime: CheckJNI is OFF
09-12 14:43:36.079  8024  8077 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,09-12 14:43:36.104  1032  8045 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,09-12 14:43:36.106  1032  8045 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
09-12 14:43:36.106  1032  8045 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
,09-12 14:43:36.106  1032  8045 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
09-12 14:43:36.106  1032  8045 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
09-12 14:43:36.106  1032  8045 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-12 14:43:36.106  1032  8045 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
09-12 14:43:36.106  1032  8045 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
09-12 14:43:36.106  1032  8045 D DhcpStateMachine: RunningState
09-12 14:43:36.191  8073  8073 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-12 14:43:36.369  1032  1780 W libprocessgroup: failed to open /acct/uid_10093/pid_7098/cgroup.procs: No such file or directory
,09-12 14:43:36.376  1032  1090 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
09-12 14:43:36.376  1032  1090 I ActivityManager: Killing 6669:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,09-12 14:43:36.416  8089  8089 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-12 14:43:36.429  1032  1774 I WindowState: WIN DEATH: Window{b82bae0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-12 14:43:36.430  1032  1454 D WifiService: Client connection lost with reason: 4
09-12 14:43:36.437  1032  1774 D InputDispatcher: Window went away: Window{b82bae0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-12 14:43:36.498  1032  1090 I ActivityManager:   Force finishing activity ActivityRecord{3190c175 u0 com.test.thalitest/.MainActivity t6}
,09-12 14:43:36.521   331   393 E GBMv2   : DFP En is all cleared set to be enabled
09-12 14:43:36.533  1032  1650 W ActivityManager: Spurious death for ProcessRecord{1be18d0b 6669:com.test.thalitest/u0a118}, curProc for 6669: null
09-12 14:43:36.534  1941  1956 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
09-12 14:43:36.535  1941  1956 D SplitWindowPolicy: topRunningActivity=ActivityInfo{32dc9068 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
,09-12 14:43:36.538  1032  1114 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
09-12 14:43:36.539  1941  1957 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
09-12 14:43:36.540  1941  1957 D SplitWindowPolicy: topRunningActivity=ActivityInfo{34595c81 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
09-12 14:43:36.542  1032  1114 I ActivityManager:   Force finishing activity ActivityRecord{3190c175 u0 com.test.thalitest/.MainActivity t6 f}
09-12 14:43:36.542  1032  1114 W ActivityManager: Duplicate finish request for ActivityRecord{3190c175 u0 com.test.thalitest/.MainActivity t6 f}
09-12 14:43:36.547  8089  8089 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,09-12 14:43:36.604  2032  2032 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
09-12 14:43:36.606  2032  2032 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
09-12 14:43:36.610  1599  1599 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
09-12 14:43:36.613  1994  1994 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
09-12 14:43:36.618  7591  7591 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
09-12 14:43:36.618  7591  7591 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
09-12 14:43:36.618  3800  3800 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
,09-12 14:43:36.622  4496  4496 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
09-12 14:43:36.623  4496  4496 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
09-12 14:43:36.623  4496  4496 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
09-12 14:43:36.623  4496  4496 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
09-12 14:43:36.623  4496  4496 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-12 14:43:36.623  4496  4496 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-12 14:43:36.623  4496  4496 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-12 14:43:36.623  4496  4496 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-12 14:43:36.624  4496  4496 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 14:43:36.624  4496  4496 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 14:43:36.624  4496  4496 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-12 14:43:36.624  4496  4496 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-12 14:43:36.650  2504  2657 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-12 14:43:36.665  1032  1378 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-12 14:43:36.675  4614  4614 I art     : Explicit concurrent mark sweep GC freed 8207(470KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 662us total 108.506ms
09-12 14:43:36.699  8089  8089 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,09-12 14:43:36.699  8089  8089 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
09-12 14:43:36.699  8089  8089 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
09-12 14:43:36.700  8089  8089 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
09-12 14:43:36.700  8089  8089 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
09-12 14:43:36.701  8089  8089 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
09-12 14:43:36.704  8089  8089 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
09-12 14:43:36.706  2032  2032 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
09-12 14:43:36.707  2032  2138 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
09-12 14:43:36.708  1599  1651 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-12 14:43:36.708  1599  1651 D KeyguardModel: createShortcutInfo...
09-12 14:43:36.708  1599  1599 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
09-12 14:43:36.711  1905  1905 D ActionManagerService: notifyUserLog: 1000003
09-12 14:43:36.712  3800  4490 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
09-12 14:43:36.712  2032  2032 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
09-12 14:43:36.715  1599  1651 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-12 14:43:36.715  1599  1651 D KeyguardModel: createShortcutInfo...
09-12 14:43:36.719  2032  2032 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,09-12 14:43:36.720  1032  1572 V SIM_STK : Menu title from STK is T-Mobile
09-12 14:43:36.721  1599  1651 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
09-12 14:43:36.721  2032  2032 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
09-12 14:43:36.721  1599  1651 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-12 14:43:36.722  1599  1651 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
09-12 14:43:36.722  2032  2032 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
09-12 14:43:36.724  1599  1651 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-12 14:43:36.724  1599  1651 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-12 14:43:36.725  1599  1651 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
09-12 14:43:36.725  1905  1905 D ActionManagerService: notifyUserLog: 1000004
09-12 14:43:36.725  2032  2032 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
09-12 14:43:36.726  3800  4490 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
09-12 14:43:36.726  3800  4483 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-12 14:43:36.727  1599  1651 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-12 14:43:36.727  1599  1651 D KeyguardModel: createShortcutInfo...
09-12 14:43:36.732  1599  1651 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
09-12 14:43:36.732  1599  1651 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-12 14:43:36.733  2032  2032 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
09-12 14:43:36.733  2032  2032 I GBoardWebViewUtils: , create_time: 1430832262123
09-12 14:43:36.733  2032  2032 I GBoardWebViewUtils: , expire_time: 0
09-12 14:43:36.733  2032  2032 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
09-12 14:43:36.733  2032  2032 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
09-12 14:43:36.733  2032  2032 I GBoardWebViewUtils: , display: false
09-12 14:43:36.733  2032  2032 I GBoardWebViewUtils: , animation: false }
09-12 14:43:36.733  2032  2032 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
09-12 14:43:36.733  2032  2032 I GBoardWebViewUtils: , create_time: 1430832262287
09-12 14:43:36.733  2032  2032 I GBoardWebViewUtils: , expire_time: 0
09-12 14:43:36.733  2032  2032 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
09-12 14:43:36.733  2032  2032 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
09-12 14:43:36.733  2032  2032 I GBoardWebViewUtils: , display: false
09-12 14:43:36.733  2032  2032 I GBoardWebViewUtils: , animation: false }
09-12 14:43:36.734  2032  2032 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1473420112499
09-12 14:43:36.734  2032  2032 I GBoardWebViewUtils: , create_time: 1473420113195
09-12 14:43:36.734  2032  2032 I GBoardWebViewUtils: , expire_time: 0
09-12 14:43:36.734  2032  2032 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide.html?id=guide_1111111111116_1473420112499&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
09-12 14:43:36.734  2032  2032 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
09-12 14:43:36.734  2032  2032 I GBoardWebViewUtils: , display: false
09-12 14:43:36.734  2032  2032 I GBoardWebViewUtils: , animation: false }
09-12 14:43:36.738  1599  1599 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
09-12 14:43:36.738  1599  1599 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
09-12 14:43:36.738  1599  1651 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-12 14:43:36.739  1599  1651 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
09-12 14:43:36.739  1599  1651 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-12 14:43:36.739  1599  1651 D KeyguardModel: createShortcutInfo...
09-12 14:43:36.741  2032  8155 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
09-12 14:43:36.748  8089  8089 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-12 14:43:36.749  1032  1032 D administrator: Handling package changes for user 0
09-12 14:43:36.751  1599  1651 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-12 14:43:36.751  1599  1651 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-12 14:43:36.751  1599  1651 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
09-12 14:43:36.751  1599  1651 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-12 14:43:36.752  8089  8089 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-12 14:43:36.752  1032  1089 W InputMethodInfo: Duplicated subtype definition found: , voice
09-12 14:43:36.755  1599  1651 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-12 14:43:36.755  1599  1651 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
09-12 14:43:36.762  1032  1780 V SIM_STK : Menu title from STK is T-Mobile
09-12 14:43:36.762  1032  1780 V SIM_STK : Menu title from STK is T-Mobile
09-12 14:43:36.764  2032  2032 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-12 14:43:36.764  2032  2032 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
,09-12 14:43:36.770  1599  1651 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-12 14:43:36.770  1599  1651 D KeyguardModel: createShortcutInfo...
09-12 14:43:36.775  1599  1599 D KeyguardModel: handleShortcutListChanged...
09-12 14:43:36.775  1599  1599 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
09-12 14:43:36.781  1869  1869 D SplitUIManager: split_name #11 / not available #0
,09-12 14:43:36.781  1869  1869 D SplitUIService: removed split : 
09-12 14:43:36.787  1599  1651 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-12 14:43:36.787  1599  1651 D KeyguardModel: createShortcutInfo...
09-12 14:43:36.788  1599  1651 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-12 14:43:36.788  1599  1651 D KeyguardModel: createShortcutInfo...
09-12 14:43:36.789  1599  1651 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-12 14:43:36.789  1599  1651 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
,09-12 14:43:36.791  1599  1651 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-12 14:43:36.791  1599  1651 D KeyguardModel: createShortcutInfo...
09-12 14:43:36.792  1599  1651 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-12 14:43:36.792  1599  1651 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
09-12 14:43:36.793  1599  1651 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-12 14:43:36.793  1599  1651 D KeyguardModel: createShortcutInfo...
09-12 14:43:36.794  1599  1651 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-12 14:43:36.794  1599  1651 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
09-12 14:43:36.795  1599  1651 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-12 14:43:36.795  1599  1651 D KeyguardModel: createShortcutInfo...
09-12 14:43:36.799  8089  8089 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-12 14:43:36.801  8089  8089 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
09-12 14:43:36.812  1032  1572 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
09-12 14:43:36.813  7591  7591 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
09-12 14:43:36.813  7591  7591 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-12 14:43:36.813  7591  7591 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-12 14:43:36.813  7591  7591 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-12 14:43:36.813  7591  7591 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-12 14:43:36.813  7591  7591 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-12 14:43:36.813  1869  1869 D SplitUIManager: split_name #11 / not available #0
09-12 14:43:36.813  1869  1869 I SplitUIService: split app #11
09-12 14:43:36.813  7591  7591 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-12 14:43:36.813  7591  7591 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-12 14:43:36.813  7591  7591 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-12 14:43:36.813  7591  7591 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-12 14:43:36.813  7591  7591 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-12 14:43:36.814  8024  8024 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-12 14:43:36.814  8024  8079 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-12 14:43:36.815  8024  8077 D LgDataFeature: LgDataFeature() Constructor: none
09-12 14:43:36.815  8024  8077 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-12 14:43:36.824  8089  8089 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
09-12 14:43:36.825  6738  6738 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-12 14:43:36.836  2032  2032 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
09-12 14:43:36.841  1599  1599 D KeyguardModel: handleShortcutListChanged...
09-12 14:43:36.841  1599  1599 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
09-12 14:43:36.853  6738  6738 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-12 14:43:36.863  8089  8089 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-12 14:43:36.863  8089  8089 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-12 14:43:36.864  1032  1032 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
09-12 14:43:36.864  1032  1032 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-12 14:43:36.864  1032  1032 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-12 14:43:36.865  8089  8089 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-12 14:43:36.869  1032  1574 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
09-12 14:43:36.869  6738  6738 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
09-12 14:43:36.871  1032  1932 V SIM_STK : Menu title from STK is T-Mobile
09-12 14:43:36.871  6738  6738 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
,09-12 14:43:36.873  8024  8024 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-12 14:43:36.873  8024  8079 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-12 14:43:36.878  6738  6738 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-12 14:43:36.880   324   407 I ThermalEngine: Thermal-Server: Thermal received msg from  override
09-12 14:43:36.880  3237  8162 I Thermal-Lib: Thermal-Lib-Client: Client request sent
09-12 14:43:36.882  6738  6738 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-12 14:43:36.887  8089  8089 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-12 14:43:36.887  8089  8089 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-12 14:43:36.887  8089  8089 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-12 14:43:36.889  6738  6738 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-12 14:43:36.889  6738  6738 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-12 14:43:36.889  6738  6738 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-12 14:43:36.889  6738  6738 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-12 14:43:36.890  6738  6738 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-12 14:43:36.890  6738  6738 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-12 14:43:36.890  6738  6738 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
09-12 14:43:36.890  6738  6738 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-12 14:43:36.890  6738  6738 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-12 14:43:36.890  6738  6738 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-12 14:43:36.890  6738  6738 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
09-12 14:43:36.891  6738  6738 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-12 14:43:36.892  8024  8024 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-12 14:43:36.892  8024  8079 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-12 14:43:36.898  6738  6738 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-12 14:43:36.902  6738  6738 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-12 14:43:36.907  8089  8089 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-12 14:43:36.907  8089  8089 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-12 14:43:36.908  8089  8089 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-12 14:43:36.914  8024  8024 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-12 14:43:36.914  8024  8079 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-12 14:43:36.922  2032  2032 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
09-12 14:43:36.925  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,09-12 14:43:36.926  6738  6738 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-12 14:43:36.927  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
09-12 14:43:36.928  1032  1114 I art     : Explicit concurrent mark sweep GC freed 79619(4MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/65MB, paused 2.551ms total 244.536ms
09-12 14:43:36.928  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
09-12 14:43:36.929  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
09-12 14:43:36.930  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
,09-12 14:43:36.947  1032  1095 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{140b7b44 u0 com.lge.launcher2/.Launcher t5} time:216559
,09-12 14:43:36.950  6738  6738 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-12 14:43:36.973  8073  8073 D AndroidRuntime: Shutting down VM
,09-12 14:43:36.974  2032  2032 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
09-12 14:43:36.974  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-12 14:43:36.976  2032  2202 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
09-12 14:43:36.976  2032  2202 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
09-12 14:43:36.989  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
,09-12 14:43:36.990  2032  2032 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
09-12 14:43:36.990  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-12 14:43:36.997  2032  2032 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
09-12 14:43:37.009  8024  8077 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
,09-12 14:43:37.016  1032  1114 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8166 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
09-12 14:43:37.020  8089  8089 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-12 14:43:37.020  8089  8089 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-12 14:43:37.020  8089  8089 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-12 14:43:37.023  2032  2032 D [Concierge]WidgetView: change position of spinner
09-12 14:43:37.023  8024  8024 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-12 14:43:37.023  8024  8079 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-12 14:43:37.023  2591  2591 D [Concierge]Service: onStartCommand(). Type : 8
09-12 14:43:37.023  2591  2591 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
09-12 14:43:37.024  2032  2032 I [Concierge]WidgetView: initWebView(). Time : 1473684217024
09-12 14:43:37.028  2591  2591 D [Concierge]Service: Update widget ID : 11
,09-12 14:43:37.028  2591  2591 D [Concierge]Service: onStartCommand(). Type : 0
09-12 14:43:37.033  6738  6738 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-12 14:43:37.037  6738  6738 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-12 14:43:37.041  8089  8089 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-12 14:43:37.041  8089  8089 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-12 14:43:37.041  8089  8089 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-12 14:43:37.043  8024  8024 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-12 14:43:37.043  8024  8079 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-12 14:43:37.049  6738  6738 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-12 14:43:37.052  6738  6738 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-12 14:43:37.058  2032  2032 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 688423620
,09-12 14:43:37.058  2032  2032 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
09-12 14:43:37.059  2032  2032 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
09-12 14:43:37.061  2032  2032 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@c783780
09-12 14:43:37.061  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
09-12 14:43:37.063  2032  2032 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
09-12 14:43:37.063  1032  1049 I ActivityManager: Killing 7137:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
09-12 14:43:37.063  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-12 14:43:37.065  8024  8077 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
09-12 14:43:37.068  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
09-12 14:43:37.069  2032  2032 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
09-12 14:43:37.070  8024  8077 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
09-12 14:43:37.070  8024  8077 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
09-12 14:43:37.070  8024  8077 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
09-12 14:43:37.071  8024  8077 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
09-12 14:43:37.071  8024  8077 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
09-12 14:43:37.073  8024  8077 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
,09-12 14:43:37.075  8024  8077 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
,09-12 14:43:37.112  1032  1089 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-12 14:43:37.115  1032  1089 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
09-12 14:43:37.118  8089  8089 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-12 14:43:37.118  8089  8089 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-12 14:43:37.118  1032  1572 W libprocessgroup: failed to open /acct/uid_10005/pid_7137/cgroup.procs: No such file or directory
09-12 14:43:37.119  8089  8089 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-12 14:43:37.119  2032  2032 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1473684029398, New one : 1473684217024
09-12 14:43:37.119  2032  2032 D [Concierge]WidgetView: Unregister all receivers
09-12 14:43:37.119  2032  2032 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
09-12 14:43:37.122  2032  2032 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
09-12 14:43:37.122  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-12 14:43:37.123  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
,09-12 14:43:37.124  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
09-12 14:43:37.125  8024  8024 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-12 14:43:37.125  8024  8079 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-12 14:43:37.126  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
09-12 14:43:37.127  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
09-12 14:43:37.128  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
09-12 14:43:37.129  2032  2032 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
09-12 14:43:37.130  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-12 14:43:37.130  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-12 14:43:37.141  6738  6738 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-12 14:43:37.148  6738  6738 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-12 14:43:37.151  8089  8089 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-12 14:43:37.152  8089  8089 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-12 14:43:37.162  2032  2032 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
09-12 14:43:37.169  2032  2032 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
09-12 14:43:37.169  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
09-12 14:43:37.171  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,09-12 14:43:37.171  8089  8089 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-12 14:43:37.173  8024  8024 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-12 14:43:37.173  8024  8079 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-12 14:43:37.178  6738  6738 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-12 14:43:37.186  6738  6738 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-12 14:43:37.189  8089  8089 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-12 14:43:37.190  8089  8089 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-12 14:43:37.190  8089  8089 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-12 14:43:37.190  2032  2032 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@215d0025 time:216803
09-12 14:43:37.192  8024  8024 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-12 14:43:37.192  8024  8079 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-12 14:43:37.195  7979  7979 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,09-12 14:43:37.197  7979  7979 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
09-12 14:43:37.199  6738  6738 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-12 14:43:37.205  6738  6738 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-12 14:43:37.209  8089  8089 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-12 14:43:37.209  8089  8089 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-12 14:43:37.209  8089  8089 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-12 14:43:37.210  8089  8089 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-12 14:43:37.210  8089  8089 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,09-12 14:43:37.213  8024  8024 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-12 14:43:37.228  7979  7979 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-12 14:43:37.229  7979  7979 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,09-12 14:43:37.230  6738  6738 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-12 14:43:37.233  6738  6738 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-12 14:43:37.237  8089  8089 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-12 14:43:37.237  8089  8089 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-12 14:43:37.238  8089  8089 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-12 14:43:37.238  8089  8089 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-12 14:43:37.238  8089  8089 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-12 14:43:37.240  8024  8024 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
09-12 14:43:37.241  8024  8024 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
,09-12 14:43:37.242  1816  1816 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
09-12 14:43:37.246  2208  2208 I ConfigService: onCreate
09-12 14:43:37.247  2208  2208 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
09-12 14:43:37.248  1816  1816 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
09-12 14:43:37.251  2208  2208 I ConfigService: onBind returning update interface
09-12 14:43:37.251  2208  2208 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
09-12 14:43:37.251  2208  2208 I ConfigService: onBind returning config service
,09-12 14:43:37.297  2208  2208 I ConfigService: onDestroy
,09-12 14:43:37.299  1816  8191 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
09-12 14:43:37.318  2032  2032 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,09-12 14:43:37.356  2032  2939 I GBoardtInterface: onReloaded()
,09-12 14:43:37.360  2032  2032 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
09-12 14:43:37.364  5951  8196 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
09-12 14:43:37.366  3800  4483 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-12 14:43:37.368  3800  3815 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,09-12 14:43:37.378  1905  1905 D ActionManagerService: notifyUserLog: 1000001
09-12 14:43:37.379  1816  4765 I Icing   : doRemovePackageData com.test.thalitest
09-12 14:43:37.380  3800  4490 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
,09-12 14:43:37.380  3800  4490 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
09-12 14:43:37.380  1816  8198 I PeopleContactsSync: CP2 sync disabled
09-12 14:43:37.384  1905  1905 D ActionManagerService: notifyUserLog: 1000001
09-12 14:43:37.385  3800  3815 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-12 14:43:37.386  3800  4490 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
09-12 14:43:37.386  3800  4490 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
09-12 14:43:37.386  3800  4490 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
09-12 14:43:37.386  3800  4490 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
09-12 14:43:37.387  2032  2032 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
09-12 14:43:37.387  2032  2032 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
09-12 14:43:37.391  6934  6934 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
,09-12 14:43:37.393  2032  2032 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
09-12 14:43:37.393  2032  2032 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
,09-12 14:43:37.395  2032  2032 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide2.html?id=guide_1111111111116_1473420112499&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
09-12 14:43:37.395  2032  2032 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide2.html?id=guide_1111111111116_1473420112499&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
09-12 14:43:37.398  1032  1396 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-12 14:43:37.398  1032  1396 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-12 14:43:37.398  1032  1396 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-12 14:43:37.399  1032  1396 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-12 14:43:37.399  1032  1396 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-12 14:43:37.399  1032  1396 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-12 14:43:37.399  1032  1466 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
09-12 14:43:37.399  1032  1466 D ConnectivityService: identical MTU - not setting
09-12 14:43:37.399  1032  1466 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-12 14:43:37.400  1032  1466 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-12 14:43:37.400  1032  1466 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 14:43:37.400  1032  1466 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-12 14:43:37.400  1032  1466 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
09-12 14:43:37.401  1599  2069 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
09-12 14:43:37.404  2336  2449 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,09-12 14:43:37.405  2336  2449 D ContactsProvider2ForLG: performBackgroundTask SQLiteDiskIOException during query
09-12 14:43:37.405  2336  2449 D ContactsProvider2ForLG: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-12 14:43:37.405  2336  2449 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
09-12 14:43:37.405  2336  2449 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:560)
09-12 14:43:37.405  2336  2449 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
09-12 14:43:37.405  2336  2449 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
09-12 14:43:37.405  2336  2449 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
09-12 14:43:37.405  2336  2449 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
09-12 14:43:37.405  2336  2449 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:394)
09-12 14:43:37.405  2336  2449 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:363)
09-12 14:43:37.405  2336  2449 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:974)
09-12 14:43:37.405  2336  2449 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactsProvider2ForLG.performBackgroundTask(ContactsProvider2ForLG.java:375)
09-12 14:43:37.405  2336  2449 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:748)
09-12 14:43:37.405  2336  2449 D ContactsProvider2ForLG: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 14:43:37.405  2336  2449 D ContactsProvider2ForLG: 	at android.os.Looper.loop(Looper.java:135)
09-12 14:43:37.405  2336  2449 D ContactsProvider2ForLG: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-12 14:43:37.409  1816  8199 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
09-12 14:43:37.409  1816  8199 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 14:43:37.409  1816  8199 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 14:43:37.409  1816  8199 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
09-12 14:43:37.409  1816  8199 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
09-12 14:43:37.409  1816  8199 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 14:43:37.409  1816  8199 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 14:43:37.409  1816  8199 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 14:43:37.409  1816  8199 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
09-12 14:43:37.409  1816  8199 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
09-12 14:43:37.409  1816  8199 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
09-12 14:43:37.409  1816  8199 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
09-12 14:43:37.409  1816  8199 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
09-12 14:43:37.409  1816  8199 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(,SQLiteOpenHelper.java:223)
09-12 14:43:37.409  1816  8199 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-12 14:43:37.409  1816  8199 E SQLiteDatabase: 	at com.google.android.gms.drive.database.k.b(SourceFile:502)
09-12 14:43:37.409  1816  8199 E SQLiteDatabase: 	at com.google.android.gms.drive.database.k.a(SourceFile:496)
09-12 14:43:37.409  1816  8199 E SQLiteDatabase: 	at com.google.android.gms.drive.database.l.run(SourceFile:519)
--------- beginning of crash
09-12 14:43:37.410  1816  8199 E AndroidRuntime: FATAL EXCEPTION: Open database in background
09-12 14:43:37.410  1816  8199 E AndroidRuntime: Process: com.google.android.gms, PID: 1816
09-12 14:43:37.410  1816  8199 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 14:43:37.410  1816  8199 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 14:43:37.410  1816  8199 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
09-12 14:43:37.410  1816  8199 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
09-12 14:43:37.410  1816  8199 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 14:43:37.410  1816  8199 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 14:43:37.410  1816  8199 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 14:43:37.410  1816  8199 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
09-12 14:43:37.410  1816  8199 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
09-12 14:43:37.410  1816  8199 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
09-12 14:43:37.410  1816  8199 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
09-12 14:43:37.410  1816  8199 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
09-12 14:43:37.410  1816  8199 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 14:43:37.410  1816  8199 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-12 14:43:37.410  1816  8199 E AndroidRuntime: 	at com.google.android.gms.drive.database.k.b(SourceFile:502)
09-12 14:43:37.410  1816  8199 E AndroidRuntime: 	at com.google.android.gms.drive.database.k.a(SourceFile:496)
09-12 14:43:37.410  1816  8199 E AndroidRuntime: 	at com.google.android.gms.drive.database.l.run(SourceFile:519)
09-12 14:43:37.413  2336  8200 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
09-12 14:43:37.414  1032  8201 E DropBoxManagerService: Can't write: system_app_crash
09-12 14:43:37.414  1032  8201 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
09-12 14:43:37.414  1032  8201 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
09-12 14:43:37.414  1032  8201 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-12 14:43:37.414  1032  8201 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-12 14:43:37.414  1032  8201 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-12 14:43:37.414  1032  8201 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
09-12 14:43:37.414  1032  8201 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
09-12 14:43:37.414  1032  8201 E DropBoxManagerS,ervice: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-12 14:43:37.414  1032  8201 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-12 14:43:37.414  1032  8201 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-12 14:43:37.414  1032  8201 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-12 14:43:37.414  1032  8201 E DropBoxManagerService: 	... 5 more
09-12 14:43:37.419  2336  8200 E SQLiteLog: (3850) statement aborts at 37: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
09-12 14:43:37.420  2336  8200 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
09-12 14:43:37.420  2336  8200 E AndroidRuntime: Process: android.process.acore, PID: 2336
09-12 14:43:37.420  2336  8200 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-12 14:43:37.420  2336  8200 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-12 14:43:37.420  2336  8200 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:739)
09-12 14:43:37.420  2336  8200 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:892)
09-12 14:43:37.420  2336  8200 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-12 14:43:37.420  2336  8200 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1600)
09-12 14:43:37.420  2336  8200 E AndroidRuntime: 	at com.android.providers.contacts.util.DbModifierWithNotification.delete(DbModifierWithNotification.java:161)
09-12 14:43:37.420  2336  8200 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailContentTable.delete(VoicemailContentTable.java:229)
09-12 14:43:37.420  2336  8200 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailContentProvider.delete(VoicemailContentProvider.java:135)
09-12 14:43:37.420  2336  8200 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
09-12 14:43:37.420  2336  8200 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1315)
09-12 14:43:37.420  2336  8200 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-12 14:43:37.420  2336  8200 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-12 14:43:37.420  2336  8200 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
09-12 14:43:37.420  2336  8200 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 14:43:37.420  2336  8200 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
09-12 14:43:37.420  2336  8200 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-12 14:43:37.440  1032  1774 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8202 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,09-12 14:43:37.443  1816  8199 I Process : Sending signal. PID: 1816 SIG: 9
09-12 14:43:37.443  2336  8200 I Process : Sending signal. PID: 2336 SIG: 9
09-12 14:43:37.447  1032  8210 E DropBoxManagerService: Can't write: system_app_crash
09-12 14:43:37.447  1032  8210 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
09-12 14:43:37.447  1032  8210 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
09-12 14:43:37.447  1032  8210 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-12 14:43:37.447  1032  8210 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-12 14:43:37.447  1032  8210 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-12 14:43:37.447  1032  8210 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
09-12 14:43:37.447  1032  8210 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
09-12 14:43:37.447  1032  8210 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-12 14:43:37.447  1032  8210 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-12 14:43:37.447  1032  8210 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-12 14:43:37.447  1032  8210 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-12 14:43:37.447  1032  8210 E DropBoxManagerService: 	... 5 more
09-12 14:43:37.450  4496  4535 E SQLiteLog: (3850) statement aborts at 13: [INSERT INTO t001(f004,f005,f002,f003,f006) VALUES (?,?,?,?,?)] disk I/O error
09-12 14:43:37.453  4496  4535 E SQLiteDatabase: Error inserting f004=13 f005=8202 f002=1473684217444 f003=com.lge.email f006=10023
09-12 14:43:37.453  4496  4535 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-12 14:43:37.453  4496  4535 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
09-12 14:43:37.453  4496  4535 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:787)
09-12 14:43:37.453  4496  4535 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:926)
09-12 14:43:37.453  4496  4535 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
09-12 14:43:37.453  4496  4535 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1572)
09-12 14:43:37.453  4496  4535 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1442)
09-12 14:43:37.453  4496  4535 E SQLiteDatabase: 	at com.lge.mlt.MptCommonLogProvider.insert(MptCommonLogProvider.java:706)
09-12 14:43:37.453  4496  4535 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:238)
09-12 14:43:37.453  4496  4535 E SQLiteDatabase: 	at android.content.ContentResolver.insert(ContentResolver.java:1223)
09-12 14:43:37.453  4496  4535 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService.insertProcessInfoLog(MltMonitorService.java:2584)
09-12 14:43:37.453  4496  4535 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService.access$2700(MltMonitorService.java:38)
09-12 14:43:37.453  4496  4535 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService$DbFlushManager$1.handleMessage(MltMonitorService.java:3409)
09-12 14:43:37.453  4496  4535 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 14:43:37.453  4496  4535 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
09-12 14:43:37.453  4496  4535 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService$DbFlushManager.run(MltMonitorService.java:3518)

```
