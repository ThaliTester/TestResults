#### Test 807613749c91828_thali02_LGE-LG-D855 Logs


```
--------- beginning of system
08-17 10:25:24.751  1037  1037 D PowerManagerServiceEx: releaseWakeLockInternal: lock=657475144 [*alarm*], flags=0x0
,--------- beginning of main
08-17 10:25:33.627  6757  6757 D AndroidRuntime: 
08-17 10:25:33.627  6757  6757 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-17 10:25:33.634  6757  6757 D AndroidRuntime: CheckJNI is OFF
08-17 10:25:33.836  6757  6757 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-17 10:25:33.847  1037  1658 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-17 10:25:33.864  1970  1994 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-17 10:25:33.869  1037  1658 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-17 10:25:33.871  1037  1658 D ActivityManager: setTaskToReturnTo : TaskRecord{270843b9 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-17 10:25:33.871  1037  1658 D ActivityManager: setTaskToReturnTo : TaskRecord{270843b9 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-17 10:25:33.872  1037  1658 D WindowStateEx: AppWindowTokenEx init.. 
08-17 10:25:33.873   340   353 E GBMv2   : DFP En is all cleared set to be enabled
08-17 10:25:33.901  1037  1658 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6772 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-17 10:25:33.904  6757  6757 D AndroidRuntime: Shutting down VM
08-17 10:25:33.960  1970  2750 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-17 10:25:33.960  1970  2750 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1d7ec0bd co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-17 10:25:33.961  1970  1993 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-17 10:25:33.961  1970  1993 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3cdfd6b2 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-17 10:25:34.007  6772  6772 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-17 10:25:34.101  6772  6772 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-17 10:25:34.115  6772  6772 I LibraryLoader: Loading: webviewchromium
,08-17 10:25:34.124  6772  6772 I LibraryLoader: Time to load native libraries: 11 ms (timestamps 1294-1305)
08-17 10:25:34.125  6772  6772 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-17 10:25:34.165  6772  6772 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {38e3d673}
,08-17 10:25:34.166  6772  6772 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-17 10:25:34.166  6772  6772 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-17 10:25:34.179  6772  6772 I BrowserStartupController: Initializing chromium process, renderers=0
,08-17 10:25:34.180  6772  6772 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-17 10:25:34.193   324   324 V AudioPolicyService: registerClient() client 0xb558a380, uid 10118
08-17 10:25:34.193  6772  6772 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-17 10:25:34.194  6772  6772 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-17 10:25:34.194  6772  6772 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-17 10:25:34.202  1037  1120 D BluetoothManagerService: Message: 20
08-17 10:25:34.202  1037  1120 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3628da7b:true
08-17 10:25:34.216  6772  6772 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-17 10:25:34.216  6772  6772 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-17 10:25:34.216  6772  6772 I Adreno-EGL: Build Date: 12/12/14 금
08-17 10:25:34.216  6772  6772 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-17 10:25:34.216  6772  6772 I Adreno-EGL: Remote Branch: 
08-17 10:25:34.216  6772  6772 I Adreno-EGL: Local Patches: 
08-17 10:25:34.216  6772  6772 I Adreno-EGL: Reconstruct Branch: 
,08-17 10:25:34.306  6772  6813 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
08-17 10:25:34.308  6772  6772 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,08-17 10:25:34.328  6772  6772 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-17 10:25:34.334  6772  6772 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-17 10:25:34.337  6772  6772 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-17 10:25:34.341  6772  6772 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-17 10:25:34.341  6772  6772 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,08-17 10:25:34.358  6772  6772 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
08-17 10:25:34.364  6772  6772 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-17 10:25:34.364  6772  6772 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-17 10:25:34.401  6772  6825 D OpenGLRenderer: Render dirty regions requested: true
08-17 10:25:34.402  6772  6825 I OpenGLRenderer: Initialized EGL, version 1.4
,08-17 10:25:34.419  6772  6825 D OpenGLRenderer: Enabling debug mode 0
,08-17 10:25:34.434  6772  6772 D Atlas   : Validating map...
,08-17 10:25:34.442  1037  2113 D SplitWindow: check instance of lgWin Window{258e799d u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-17 10:25:34.522  6772  6823 D LgDataFeature: LgDataFeature() Constructor: none
08-17 10:25:34.522  6772  6823 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-17 10:25:34.568  1037  1121 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +609ms (total +694ms)
08-17 10:25:34.569  1037  1121 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3d3d63fe u0 com.test.thalitest/.MainActivity t6} time:311750
08-17 10:25:34.569  6772  6772 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3945cbde time:311751
,08-17 10:25:34.737  6772  6772 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-17 10:25:34.813  6772  6823 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-17 10:25:34.813  6772  6823 I chromium: 
,08-17 10:25:34.963  6772  6839 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435153408
,08-17 10:25:34.972  6772  6772 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-17 10:25:34.972  6772  6772 I chromium: 
08-17 10:25:34.986  6772  6839 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-17 10:25:34.986  6772  6839 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-17 10:25:34.986  6772  6839 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-17 10:25:34.986  6772  6839 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-17 10:25:34.986  6772  6839 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-17 10:25:34.986  6772  6839 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37c6a42 added. We now have 1 listener(s)
08-17 10:25:34.993  1037  2117 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 10:25:34.996  6772  6839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-17 10:25:34.999  6772  6839 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-17 10:25:35.001  6772  6839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 10:25:35.001  6772  6839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 10:25:35.010  6772  6839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-17 10:25:35.010  6772  6839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-17 10:25:35.010  6772  6839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-17 10:25:35.010  6772  6839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-17 10:25:35.010  6772  6839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-17 10:25:35.010  6772  6839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-17 10:25:35.010  6772  6839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-17 10:25:35.010  6772  6839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-17 10:25:35.010  6772  6839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-17 10:25:35.010  6772  6839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-17 10:25:35.010  6772  6839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-17 10:25:35.010  6772  6839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-17 10:25:35.010  6772  6839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-17 10:25:35.010  6772  6839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-17 10:25:35.010  6772  6839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e3dc089 added. We now have 1 listener(s)
08-17 10:25:35.010  6772  6839 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 10:25:35.015  1037  1547 D WifiService: New client listening to asynchronous messages
08-17 10:25:35.020  6772  6839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-17 10:25:35.020  6772  6839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-17 10:25:35.020  6772  6839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-17 10:25:35.020  6772  6839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-17 10:25:35.021  6772  6839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-17 10:25:35.026  6772  6839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 10:25:35.026  1037  1658 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 10:25:35.027  6772  6839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-17 10:25:35.039  6772  6839 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-17 10:25:35.039  6772  6839 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 10:25:35.039  6772  6839 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:25:35.039  6772  6839 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 10:25:35.039  6772  6839 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 10:25:35.039  6772  6839 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 10:25:35.039  6772  6839 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 10:25:35.039  6772  6839 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 10:25:35.039  6772  6839 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 10:25:35.039  6772  6839 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-17 10:25:35.040  6772  6839 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 10:25:35.043  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:25:35.044  6772  6839 I io.jxcore.node.LifeCycleMonitor: start: OK
08-17 10:25:35.045  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:25:35.084  6772  6772 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-17 10:25:35.680   340   355 E GBMv2   : DFP En is all cleared set to be enabled
08-17 10:25:35.681   340   355 E GBMv2   : Set value is all cleared set the max
08-17 10:25:35.681   340   355 I GBMv2   : DFP Enabled. Ignore VFP set
,08-17 10:25:35.849  6772  6842 W jxcore-log: Initializing JXcore engine
08-17 10:25:35.849  6772  6842 W jxcore-log: JXcore engine is ready
,08-17 10:25:35.879  6842  6842 W Thread-772: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[9917]" dev="sockfs" ino=9917 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-17 10:25:35.879  6842  6842 W Thread-772: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-17 10:25:35.879  6842  6842 W Thread-772: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[8599]" dev="sockfs" ino=8599 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-17 10:25:35.879  6842  6842 W Thread-772: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-17 10:25:35.879  6842  6842 W Thread-772: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[31913]" dev="sockfs" ino=31913 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,08-17 10:25:35.900  6772  6842 W jxcore-log: Starting JXcore engine
08-17 10:25:35.975  6772  6842 W jxcore-log: Platform android
08-17 10:25:35.975  6772  6842 W jxcore-log: 
08-17 10:25:35.976  6772  6842 W jxcore-log: Process ARCH arm
08-17 10:25:35.976  6772  6842 W jxcore-log: 
,08-17 10:25:36.293  6772  6842 I jxcore-log: JXcore Cordova bridge is ready!
08-17 10:25:36.293  6772  6842 I jxcore-log: 
,08-17 10:25:36.294  6772  6842 W jxcore-log: JXcore engine is started
08-17 10:25:36.302  6772  6839 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-17 10:25:36.307  6772  6772 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-17 10:25:53.214  6772  6842 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-17 10:25:53.214  6772  6842 I jxcore-log: 
,08-17 10:25:53.217  6772  6842 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-17 10:25:53.217  6772  6842 I jxcore-log: 
08-17 10:25:53.222  6772  6842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 10:25:53.222  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:25:53.222  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 10:25:53.222  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 10:25:53.222  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 10:25:53.222  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 10:25:53.222  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 10:25:53.222  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 10:25:53.226  6772  6842 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 10:25:53.228  6772  6842 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-17 10:25:53.228  6772  6842 I jxcore-log: 
,08-17 10:25:53.231  6772  6842 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-17 10:25:53.231  6772  6842 I jxcore-log: 
,08-17 10:25:53.563  6772  6842 I jxcore-log: Running unit tests
08-17 10:25:53.563  6772  6842 I jxcore-log: 
08-17 10:25:53.564  6772  6842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-17 10:25:53.565  6772  6842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34c79c4c added. We now have 2 listener(s)
08-17 10:25:53.565  1037  1740 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 10:25:53.567  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-17 10:25:53.567  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 10:25:53.567  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 10:25:53.567  6772  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 10:25:53.567  6772  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3964e495 added. We now have 2 listener(s)
08-17 10:25:53.567  6772  6842 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 10:25:53.568  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 10:25:53.570  6772  6842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 10:25:53.572  6772  6842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 10:25:53.572  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:25:53.572  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 10:25:53.572  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 10:25:53.572  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 10:25:53.572  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 10:25:53.572  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 10:25:53.572  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 10:25:53.574  6772  6842 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 10:25:53.574  6772  6842 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 10:25:53.575  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:25:53.576  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:25:53.577  6772  6842 D ExecuteNativeTests: Running unit tests
08-17 10:25:53.660  6772  6842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 10:25:53.661  6772  6842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3677ff8b added. We now have 3 listener(s)
08-17 10:25:53.661  1037  1053 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-17 10:25:53.662  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-17 10:25:53.662  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 10:25:53.663  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 10:25:53.663  6772  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 10:25:53.663  6772  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31765868 added. We now have 3 listener(s)
08-17 10:25:53.663  6772  6842 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 10:25:53.663  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-17 10:25:53.665  6772  6842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 10:25:53.669  6772  6842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 10:25:53.669  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:25:53.669  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
,08-17 10:25:53.669  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 10:25:53.669  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
,08-17 10:25:53.669  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 10:25:53.669  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 10:25:53.669  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 10:25:53.669  6772  6842 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 10:25:53.670  6772  6842 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 10:25:53.671  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:25:53.673  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-17 10:25:53.674  6772  6842 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-17 10:25:53.675  6772  6842 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-17 10:25:53.675  6772  6842 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-17 10:25:53.675  6772  6842 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-17 10:25:53.677  6772  6842 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-17 10:25:53.679  6772  6842 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-17 10:25:53.679  6772  6842 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-17 10:25:53.679  6772  6842 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-17 10:25:53.679  6772  6842 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-17 10:25:53.679  6772  6842 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-17 10:25:53.680  6772  6842 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
08-17 10:25:53.680  6772  6842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 10:25:53.680  6772  6842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 10:25:53.681  6772  6842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 10:25:53.681  6772  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:25:53.681  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 10:25:53.681  6772  6842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 10:25:53.681  6772  6842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3677ff8b removed from the list
08-17 10:25:53.681  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:25:53.681  6772  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31765868 removed from the list
08-17 10:25:53.681  6772  6842 D io.jxcore.node.ConnectivityMonitor: stop
08-17 10:25:53.681  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:25:53.682  6772  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:25:53.682  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:25:53.683  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 10:25:53.683  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 10:25:53.683  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:25:53.683  6772  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31765868 not in the list
08-17 10:25:53.684  6772  6842 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-17 10:25:53.686  6772  6842 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 10:25:53.686  6772  6842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 10:25:53.686  6772  6842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 10:25:53.686  6772  6842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 10:25:53.686  6772  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:25:53.686  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:25:53.687  6772  6842 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3677ff8b not in the list
08-17 10:25:53.687  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:25:53.687  6772  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31765868 not in the list
08-17 10:25:53.687  6772  6842 D io.jxcore.node.ConnectivityMonitor: stop
08-17 10:25:53.687  6772  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:25:53.687  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:25:53.687  6772  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:25:53.687  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:25:53.687  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 10:25:53.687  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 10:25:53.687  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:25:53.688  6772  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31765868 not in the list
08-17 10:25:53.692  6772  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-17 10:25:53.692  6772  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-17 10:25:53.692  6772  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-17 10:25:53.692  6772  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-17 10:25:53.692  6772  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-17 10:25:53.692  6772  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410,:410:410:410]
08-17 10:25:53.692  6772  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-17 10:25:53.692  6772  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-17 10:25:53.692  6772  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-17 10:25:53.693  6772  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-17 10:25:53.693  6772  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-17 10:25:53.693  6772  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-17 10:25:53.693  6772  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-17 10:25:53.693  6772  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-17 10:25:53.693  6772  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-17 10:25:53.693  6772  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-17 10:25:53.693  6772  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-17 10:25:53.693  6772  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-17 10:25:53.693  6772  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-17 10:25:53.693  6772  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-17 10:25:53.693  6772  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-17 10:25:53.693  6772  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-17 10:25:53.693  6772  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-17 10:25:53.693  6772  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-17 10:25:53.693  6772  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-17 10:25:53.693  6772  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-17 10:25:53.693  6772  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-17 10:25:53.693  6772  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-17 10:25:53.693  6772  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-17 10:25:53.693  6772  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-17 10:25:53.693  6772  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-17 10:25:53.693  6772  6842 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 10:25:53.693  6772  6842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, ,discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 10:25:53.693  6772  6842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 10:25:53.694  6772  6842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 10:25:53.694  6772  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:25:53.694  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:25:53.694  6772  6842 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3677ff8b not in the list
08-17 10:25:53.694  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:25:53.694  6772  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31765868 not in the list
08-17 10:25:53.694  6772  6842 D io.jxcore.node.ConnectivityMonitor: stop
08-17 10:25:53.694  6772  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:25:53.694  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:25:53.694  6772  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:25:53.694  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:25:53.694  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 10:25:53.694  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 10:25:53.694  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:25:53.695  6772  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31765868 not in the list
08-17 10:25:53.695  6772  6842 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-17 10:25:53.698  6772  6842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 10:25:53.704  6772  6842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 10:25:53.704  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:25:53.704  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 10:25:53.704  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 10:25:53.704  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 10:25:53.704  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 10:25:53.704  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 10:25:53.704  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 10:25:53.708  6772  6842 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 10:25:53.708  6772  6842 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 10:25:53.709  6772  6842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 10:25:53.709  6772  6842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 10:25:53.709  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:25:53.710  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 10:25:53.710  6772  6842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 10:25:53.710  6772  6842 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-17 10:25:53.711  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:25:53.717  6772  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-17 10:25:53.718  1037  1816 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 10:25:53.722  6772  6842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-17 10:25:53.726  6772  6842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-17 10:25:53.727  6772  6842 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
08-17 10:25:53.728  6772  6842 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-17 10:25:53.729  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-17 10:25:53.730  6772  6842 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-17 10:25:53.731  6772  6842 I io.jxcore.node.ConnectionHelper: start: OK
08-17 10:25:57.870  1037  3542 I LocationManagerService: remove 1663fcc7
08-17 10:25:57.871  1037  3542 D LocationManagerService: provider request: passive ProviderRequest[ON interval=0]
08-17 10:25:57.871  1037  3542 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-17 10:25:57.872  1037  3542 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-17 10:25:57.882  1037  3542 D LocationManagerService: getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
08-17 10:25:57.883  1037  3542 D LocationManagerService: getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,08-17 10:25:58.742  6772  6842 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 10:25:58.742  6772  6842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 10:25:58.742  6772  6842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 10:25:58.750  6772  6842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 10:25:58.750  6772  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:25:58.750  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 10:25:58.750  6772  6842 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3677ff8b not in the list
08-17 10:25:58.750  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:25:58.750  6772  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31765868 not in the list
08-17 10:25:58.750  6772  6842 D io.jxcore.node.ConnectivityMonitor: stop
08-17 10:25:58.750  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:26:00.049  1605  1605 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-17 10:26:00.049  1605  1605 I KeyguardUpdateMonitor: called onTimeUpdated()
08-17 10:26:00.049  1605  1605 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-17 10:26:00.050  1605  1605 I [SystemUI]Clock: called onTimeUpdated()
,08-17 10:26:00.062  1605  1605 I LgeClockWidgetControlView: called onTimeUpdated()
08-17 10:26:00.062  1605  1605 I [SystemUI]DateView: called onTimeUpdated()
08-17 10:26:00.065  1605  1605 I [SystemUI]DateView: called onTimeUpdated()
08-17 10:26:00.067  1605  1605 D KeyguardUpdateMonitor: handleTimeUpdate
08-17 10:26:03.752  6772  6842 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-17 10:26:03.766  6772  6842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 10:26:03.773  6772  6842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 10:26:03.773  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:26:03.773  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 10:26:03.773  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 10:26:03.773  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 10:26:03.773  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 10:26:03.773  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 10:26:03.773  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 10:26:03.776  6772  6842 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 10:26:03.777  6772  6842 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 10:26:03.779  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:26:03.781  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:26:03.781  6772  6842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 10:26:03.782  6772  6842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 10:26:03.782  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 10:26:03.782  6772  6842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 10:26:03.782  6772  6842 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-17 10:26:03.787  6772  6842 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-17 10:26:03.789  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 10:26:03.791  6772  6842 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-17 10:26:03.792  6772  6842 I io.jxcore.node.ConnectionHelper: start: OK
08-17 10:26:03.794  6772  6842 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 10:26:03.794  6772  6842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 10:26:03.794  6772  6842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 10:26:03.795  6772  6842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 10:26:03.795  6772  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:26:03.795  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 10:26:03.795  6772  6842 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3677ff8b not in the list
08-17 10:26:03.795  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:26:03.795  6772  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31765868 not in the list
08-17 10:26:03.795  6772  6842 D io.jxcore.node.ConnectivityMonitor: stop
08-17 10:26:03.795  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:26:03.796  6772  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:26:03.796  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:26:03.797  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 10:26:03.797  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 10:26:03.799  6772  6842 D BluetoothLeScanner: could not find callback wrapper
08-17 10:26:03.799  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 10:26:03.799  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:26:03.799  6772  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31765868 not in the list
08-17 10:26:03.800  6772  6842 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-17 10:26:03.806  6772  6842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 10:26:03.810  6772  6842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 10:26:03.810  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:26:03.810  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 10:26:03.810  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 10:26:03.810  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 10:26:03.810  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 10:26:03.810  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 10:26:03.810  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 10:26:03.813  6772  6842 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 10:26:03.813  6772  6842 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 10:26:03.816  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:26:03.818  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:26:03.819  6772  6842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 10:26:03.819  6772  6842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 10:26:03.819  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 10:26:03.819  6772  6842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 10:26:03.819  6772  6842 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-17 10:26:03.824  6772  6842 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-17 10:26:03.826  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 10:26:03.829  6772  6842 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-17 10:26:03.829  6772  6842 I io.jxcore.node.ConnectionHelper: start: OK
08-17 10:26:08.830  6772  6842 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 10:26:08.830  6772  6842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 10:26:08.830  6772  6842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 10:26:09.249  1037  1384 D PowerManagerServiceEx: acquireWakeLockInternal: lock=657475144, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,08-17 10:26:09.413  2637  2637 D [Concierge]Service: onStartCommand(). Type : 9
,08-17 10:26:09.440  1037  1037 D PowerManagerServiceEx: releaseWakeLockInternal: lock=657475144 [*alarm*], flags=0x0
,08-17 10:26:09.467  1037  2117 I art     : Explicit concurrent mark sweep GC freed 28831(1357KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/64MB, paused 1.969ms total 193.319ms
,08-17 10:26:13.841  6772  6842 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 10:26:13.842  6772  6842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 10:26:13.842  6772  6842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 10:26:13.850  6772  6842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 10:26:13.850  6772  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:26:13.850  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 10:26:13.850  6772  6842 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3677ff8b not in the list
08-17 10:26:13.850  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:26:13.850  6772  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31765868 not in the list
08-17 10:26:13.850  6772  6842 D io.jxcore.node.ConnectivityMonitor: stop
08-17 10:26:13.850  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:26:13.851  6772  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:26:13.851  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:26:13.852  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 10:26:13.853  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 10:26:13.853  6772  6842 D BluetoothLeScanner: could not find callback wrapper
08-17 10:26:13.853  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 10:26:13.853  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:26:13.853  6772  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31765868 not in the list
08-17 10:26:13.854  6772  6842 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-17 10:26:13.855  6772  6842 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 10:26:13.855  6772  6842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 10:26:13.855  6772  6842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 10:26:13.855  6772  6842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 10:26:13.855  6772  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:26:13.856  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:26:13.856  6772  6842 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3677ff8b not in the list
08-17 10:26:13.856  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:26:13.856  6772  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31765868 not in the list
08-17 10:26:13.856  6772  6842 D io.jxcore.node.ConnectivityMonitor: stop
08-17 10:26:13.856  6772  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:26:13.856  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.Blu,etoothManager: release: 2 listener(s) left
08-17 10:26:13.856  6772  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:26:13.856  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 10:26:13.861  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 10:26:13.861  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 10:26:13.862  6772  6842 D BluetoothLeScanner: could not find callback wrapper
08-17 10:26:13.862  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 10:26:13.862  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:26:13.862  6772  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31765868 not in the list
08-17 10:26:13.864  6772  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-17 10:26:13.864  6772  6842 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 10:26:13.864  6772  6842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 10:26:13.864  6772  6842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 10:26:13.865  6772  6842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 10:26:13.865  6772  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:26:13.865  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:26:13.865  6772  6842 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3677ff8b not in the list
08-17 10:26:13.865  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:26:13.865  6772  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31765868 not in the list
08-17 10:26:13.865  6772  6842 D io.jxcore.node.ConnectivityMonitor: stop
08-17 10:26:13.865  6772  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:26:13.865  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:26:13.865  6772  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:26:13.865  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:26:13.867  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 10:26:13.867  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 10:26:13.867  6772  6842 D BluetoothLeScanner: could not find callback wrapper
08-17 10:26:13.867  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 10:26:13.867  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:26:13.867  6772  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31765868 not in the list
08-17 10:26:13.868  6772  6842 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-17 10:26:13.869  6772  6842 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 10:26:13.869  6772  6842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: ,false, is advertising: false - Stop operation: Should start/stop everything
08-17 10:26:13.869  6772  6842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 10:26:13.870  6772  6842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 10:26:13.870  6772  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:26:13.870  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:26:13.870  6772  6842 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3677ff8b not in the list
08-17 10:26:13.870  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:26:13.871  6772  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31765868 not in the list
08-17 10:26:13.871  6772  6842 D io.jxcore.node.ConnectivityMonitor: stop
08-17 10:26:13.871  6772  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:26:13.871  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:26:13.871  6772  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:26:13.871  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 10:26:13.876  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 10:26:13.876  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 10:26:13.877  6772  6842 D BluetoothLeScanner: could not find callback wrapper
08-17 10:26:13.877  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 10:26:13.877  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:26:13.877  6772  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31765868 not in the list
08-17 10:26:13.879  6772  6842 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-17 10:26:13.879  6772  6842 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 10:26:13.879  6772  6842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 10:26:13.879  6772  6842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 10:26:13.879  6772  6842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 10:26:13.880  6772  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:26:13.880  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:26:13.880  6772  6842 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3677ff8b not in the list
08-17 10:26:13.880  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:26:13.880  6772  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31765868 not in the list
08-17 10:26:13.880  6772  6842 D io.jxcore.node.ConnectivityMonitor: stop
08-17 10:26:13.880  6772  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:26:13.880  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:26:13.880  6772  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:26:13.880  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:26:13.881  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 10:26:13.881  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 10:26:13.883  6772  6842 D BluetoothLeScanner: could not find callback wrapper
08-17 10:26:13.883  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 10:26:13.883  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:26:13.883  6772  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31765868 not in the list
08-17 10:26:13.884  6772  6842 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-17 10:26:13.890  6772  6842 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-17 10:26:13.890  6772  6842 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-17 10:26:13.890  6772  6842 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-17 10:26:13.890  6772  6842 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-17 10:26:13.891  6772  6842 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-17 10:26:13.891  6772  6842 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-17 10:26:13.891  6772  6842 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-17 10:26:13.891  6772  6842 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-17 10:26:13.892  6772  6842 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 10:26:13.893  6772  6842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 10:26:13.893  6772  6842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 10:26:13.894  6772  6842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 10:26:13.894  6772  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:26:13.895  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:26:13.895  6772  6842 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3677ff8b not in the list
08-17 10:26:13.895  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:26:13.895  6772  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31765868 not in the list
08-17 10:26:13.895  6772  6842 D io.jxcore.node.ConnectivityMonitor: stop
08-17 10:26:13.895  6772  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:26:13.895  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:26:13.895  6772  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:26:13.895  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:26:13.897  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 10:26:13.897  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 10:26:13.903  6772  6842 D BluetoothLeScanner: could not find callback wrapper
08-17 10:26:13.903  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 10:26:13.903  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:26:13.904  6772  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31765868 not in the list
08-17 10:26:13.905  6772  6842 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-17 10:26:13.905  6772  6842 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-17 10:26:13.905  6772  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-17 10:26:13.913  6772  6842 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-17 10:26:13.914  6772  6842 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-17 10:26:13.914  6772  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-17 10:26:13.914  6772  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-17 10:26:13.914  6772  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-17 10:26:13.914  6772  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-17 10:26:13.914  6772  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-17 10:26:13.914  6772  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-17 10:26:13.914  6772  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-17 10:26:13.914  6772  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-17 10:26:13.914  6772  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-17 10:26:13.914  6772  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-17 10:26:13.914  6772  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-17 10:26:13.914  6772  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-17 10:26:13.914  6772  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-17 10:26:13.914  6772  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-17 10:26:13.914  6772  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-17 10:26:13.914  6772  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-17 10:26:13.914  6772  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-17 10:26:13.915  6772  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-17 10:26:13.915  6772  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:,1810:1810:1810]
08-17 10:26:13.915  6772  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-17 10:26:13.915  6772  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-17 10:26:13.915  6772  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-17 10:26:13.915  6772  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-17 10:26:13.915  6772  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-17 10:26:13.915  6772  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-17 10:26:13.915  6772  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-17 10:26:13.915  6772  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-17 10:26:13.915  6772  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-17 10:26:13.915  6772  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-17 10:26:13.915  6772  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910],
08-17 10:26:13.915  6772  6842 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-17 10:26:13.915  6772  6842 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-17 10:26:13.916  6772  6842 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-17 10:26:13.916  6772  6842 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-17 10:26:13.916  6772  6842 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-17 10:26:13.916  6772  6842 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection,
08-17 10:26:13.916  6772  6842 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-17 10:26:13.916  6772  6842 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-17 10:26:13.916  6772  6842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,08-17 10:26:13.926  6772  6842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-17 10:26:13.927  6772  6842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-17 10:26:13.927  6772  6842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-17 10:26:13.928  6772  6842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-17 10:26:13.928  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-17 10:26:13.930  6772  6842 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-17 10:26:13.930  6772  6842 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-17 10:26:13.930  6772  6842 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-17 10:26:13.930  6772  6842 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 10:26:13.930  6772  6842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 10:26:13.931  6772  6842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 10:26:13.933  6772  6842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 10:26:13.933  6772  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:26:13.933  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:26:13.935  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-17 10:26:13.935  6772  6842 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3677ff8b not in the list
08-17 10:26:13.935  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:26:13.935  6772  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31765868 not in the list
08-17 10:26:13.935  6772  6842 D io.jxcore.node.ConnectivityMonitor: stop
08-17 10:26:13.935  6772  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:26:13.935  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:26:13.936  6772  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:26:13.936  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:26:13.936  6772  6878 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 836)
08-17 10:26:13.940  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 10:26:13.940  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 10:26:13.941  6772  6842 D BluetoothLeScanner: could not find callback wrapper
08-17 10:26:13.941  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 10:26:13.941  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:26:13.941  6772  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31765868 not in the list
08-17 10:26:13.943  6772  6842 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-17 10:26:13.943  6772  6842 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 10:26:13.943  6772  6842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 10:26:13.943  6772  6842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 10:26:13.945  6772  6879 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 836
08-17 10:26:13.946  6772  6879 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 836)
08-17 10:26:13.946  6772  6879 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 836)
,08-17 10:26:13.949  6772  6842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 10:26:13.949  6772  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:26:13.949  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:26:13.950  6772  6842 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3677ff8b not in the list
08-17 10:26:13.950  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:26:13.950  6772  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31765868 not in the list
08-17 10:26:13.950  6772  6842 D io.jxcore.node.ConnectivityMonitor: stop
08-17 10:26:13.950  6772  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:26:13.950  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:26:13.950  6772  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:26:13.950  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:26:13.959  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 10:26:13.959  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 10:26:13.962  6772  6842 D BluetoothLeScanner: could not find callback wrapper
08-17 10:26:13.962  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 10:26:13.962  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:26:13.962  6772  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31765868 not in the list
08-17 10:26:13.964  6772  6842 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-17 10:26:13.965  6772  6842 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 10:26:13.965  6772  6842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 10:26:13.965  6772  6842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 10:26:13.965  6772  6842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 10:26:13.965  6772  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:26:13.965  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:26:13.965  6772  6842 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3677ff8b not in the list
08-17 10:26:13.966  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:26:13.966  6772  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31765868 not in the list
08-17 10:26:13.966  6772  6842 D io.jxcore.node.ConnectivityMonitor: stop
08-17 10:26:13.966  6772  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:26:13.966  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:26:13.966  6772  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:26:13.966  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:26:13.967  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 10:26:13.967  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 10:26:13.968  6772  6842 D BluetoothLeScanner: could not find callback wrapper
08-17 10:26:13.968  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 10:26:13.968  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:26:13.968  6772  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31765868 not in the list
08-17 10:26:13.969  6772  6842 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-17 10:26:13.969  6772  6842 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-17 10:26:13.969  6772  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-17 10:26:13.969  6772  6842 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection,: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-17 10:26:13.969  6772  6842 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-17 10:26:13.969  6772  6842 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-17 10:26:13.970  6772  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-17 10:26:13.970  6772  6842 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-17 10:26:13.970  6772  6842 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-17 10:26:13.970  6772  6842 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-17 10:26:13.970  6772  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-17 10:26:13.970  6772  6842 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-17 10:26:13.970  6772  6842 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 10:26:13.970  6772  6842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 10:26:13.970  6772  6842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 10:26:13.973  6772  6842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
08-17 10:26:13.973  6772  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:26:13.973  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:26:13.973  6772  6842 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3677ff8b not in the list
08-17 10:26:13.973  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:26:13.973  6772  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31765868 not in the list
08-17 10:26:13.973  6772  6842 D io.jxcore.node.ConnectivityMonitor: stop
08-17 10:26:13.973  6772  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:26:13.973  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:26:13.973  6772  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:26:13.974  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 10:26:13.981  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 10:26:13.981  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 10:26:13.982  6772  6842 D BluetoothLeScanner: could not find callback wrapper
08-17 10:26:13.982  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 10:26:13.982  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:26:13.982  6772  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31765868 not in the list
08-17 10:26:13.983  6772  6842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 10:26:13.983  6772  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:26:13.983  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:26:13.983  6772  6842 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3677ff8b not in the list
08-17 10:26:13.983  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:26:13.983  6772  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31765868 not in the list
08-17 10:26:13.983  6772  6842 D io.jxcore.node.ConnectivityMonitor: stop
08-17 10:26:13.983  6772  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:26:13.983  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:26:14.074  6772  6878 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
08-17 10:26:14.074  6772  6878 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 836)
,08-17 10:26:14.321  1037  1099 W ProcessCpuTracker: Skipping unknown process pid 6884
,08-17 10:26:14.322  1037  1099 W ProcessCpuTracker: Skipping unknown process pid 6887
08-17 10:26:18.985  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:26:18.985  6772  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31765868 not in the list
08-17 10:26:18.985  6772  6842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 10:26:18.985  6772  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:26:18.985  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:26:18.985  6772  6842 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3677ff8b not in the list
08-17 10:26:18.986  6772  6842 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 10:26:18.986  6772  6842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 10:26:18.986  6772  6842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 10:26:18.996  6772  6842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 10:26:18.996  6772  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:26:18.996  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 10:26:18.996  6772  6842 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3677ff8b not in the list
08-17 10:26:18.996  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:26:18.996  6772  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31765868 not in the list
08-17 10:26:18.996  6772  6842 D io.jxcore.node.ConnectivityMonitor: stop
08-17 10:26:18.996  6772  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:26:18.996  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:26:18.997  6772  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:26:18.997  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:26:19.000  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 10:26:19.001  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 10:26:19.002  6772  6842 D BluetoothLeScanner: could not find callback wrapper
08-17 10:26:19.002  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 10:26:19.002  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:26:19.002  6772  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31765868 not in the list
,08-17 10:26:19.008  6772  6842 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-17 10:26:19.008  6772  6842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 10:26:19.009  6772  6842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-17 10:26:19.010  6772  6842 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-17 10:26:19.011  6772  6842 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-17 10:26:19.011  6772  6772 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-17 10:26:19.011  6772  6842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-17 10:26:19.012  6772  6842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-17 10:26:19.013  6772  6842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 10:26:19.013  6772  6842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-17 10:26:19.013  6772  6842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-17 10:26:19.013  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-17 10:26:19.013  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:26:19.013  6772  6842 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-17 10:26:19.016  6772  6905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-17 10:26:19.016  6772  6905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,08-17 10:26:19.019  6772  6772 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-17 10:26:19.019  6772  6842 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3677ff8b not in the list
08-17 10:26:19.020  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:26:19.020  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-17 10:26:19.020  6772  6842 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 10:26:19.020  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-17 10:26:19.021  6772  6842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-17 10:26:19.023  6772  6842 D BluetoothLeScanner: could not find callback wrapper
08-17 10:26:19.023  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 10:26:19.023  6772  6842 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-17 10:26:19.023  6772  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:26:19.023  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:26:19.025  6772  6842 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 10:26:19.025  6772  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 10:26:19.025  6772  6772 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-17 10:26:19.025  6772  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 10:26:19.025  6772  6772 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 10:26:19.027  6772  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31765868 not in the list
08-17 10:26:19.027  6772  6842 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 10:26:19.027  6772  6842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 10:26:19.027  6772  6842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 10:26:19.027  6772  6842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 10:26:19.027  6772  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:26:19.027  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:26:19.028  6772  6842 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3677ff8b not in the list
08-17 10:26:19.028  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:26:19.028  6772  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31765868 not in the list
08-17 10:26:19.028  6772  6842 D io.jxcore.node.ConnectivityMonitor: stop
08-17 10:26:19.028  6772 , 6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:26:19.028  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:26:19.028  6772  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:26:19.028  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:26:19.029  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 10:26:19.029  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 10:26:19.029  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:26:19.029  6772  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31765868 not in the list
08-17 10:26:19.031  6772  6842 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,08-17 10:26:19.035  6772  6842 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-17 10:26:19.035  6772  6842 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-17 10:26:19.037  6772  6842 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-17 10:26:19.037  6772  6842 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-17 10:26:19.039  6772  6842 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 10:26:19.040  6772  6842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 10:26:19.040  6772  6842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 10:26:19.041  6772  6842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 10:26:19.041  6772  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:26:19.041  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:26:19.041  6772  6842 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3677ff8b not in the list
08-17 10:26:19.041  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:26:19.041  6772  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31765868 not in the list
08-17 10:26:19.041  6772  6842 D io.jxcore.node.ConnectivityMonitor: stop
08-17 10:26:19.042  6772  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:26:19.042  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:26:19.042  6772  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:26:19.042  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 10:26:19.046  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 10:26:19.046  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 10:26:19.046  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:26:19.046  6772  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31765868 not in the list
08-17 10:26:19.049  1037  1816 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 10:26:19.052  1037  2117 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 10:26:19.053  1037  2113 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 10:26:19.054  6772  6842 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 10:26:19.054  6772  6842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 10:26:19.054  6772  6842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 10:26:19.056  6772  6842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 10:26:19.056  6772  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:26:19.056  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:26:19.056  6772  6842 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3677ff8b not in the list
08-17 10:26:19.056  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:26:19.057  6772  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31765868 not in the list
08-17 10:26:19.057  6772  6842 D io.jxcore.node.ConnectivityMonitor: stop
08-17 10:26:19.057  6772  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:26:19.057  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:26:19.057  6772  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:26:19.057  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:26:19.058  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 10:26:19.058  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 10:26:19.058  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:26:19.059  6772  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31765868 not in the list
08-17 10:26:19.060  6772  6842 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 10:26:19.060  6772  6842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 10:26:19.060  6772  6842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 10:26:19.061  6772  6842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 10:26:19.061  6772  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:26:19.061  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:26:19.061  6772  6842 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3677ff8b not in the list
08-17 10:26:19.061  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:26:19.061  6772  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31765868 not in the list
08-17 10:26:19.061  6772  6842 D io.jxcore.node.ConnectivityMonitor: stop
08-17 10:26:19.061  6772  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:26:19.061  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:26:19.061  6772  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager:, release: The given listener does not exist in the list - probably already removed
08-17 10:26:19.061  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:26:19.063  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 10:26:19.063  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 10:26:19.063  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:26:19.063  6772  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31765868 not in the list
08-17 10:26:19.065  6772  6842 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-17 10:26:19.065  6772  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-17 10:26:19.065  6772  6842 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-17 10:26:19.065  6772  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-17 10:26:19.065  6772  6842 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
,08-17 10:26:19.065  6772  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-17 10:26:19.068  6772  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-17 10:26:19.068  6772  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-17 10:26:19.069  6772  6842 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-17 10:26:19.070  6772  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-17 10:26:19.070  6772  6842 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
,08-17 10:26:19.070  6772  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-17 10:26:19.070  6772  6842 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-17 10:26:19.070  6772  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-17 10:26:19.071  6772  6842 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-17 10:26:19.071  6772  6842 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,08-17 10:26:19.072  6772  6842 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-17 10:26:19.072  6772  6842 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-17 10:26:19.072  6772  6842 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-17 10:26:19.072  6772  6842 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-17 10:26:19.073  6772  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 10:26:19.073  6772  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f1b42b9 added. We now have 3 listener(s)
08-17 10:26:19.074  6772  6842 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 10:26:19.083  6772  6842 D BluetoothAdapter: enable(): BT is already enabled..!
08-17 10:26:19.085  1037  1999 D WifiServiceImplEx: setWifiEnabled: true pid=6772, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-17 10:26:19.086  1037  1999 D WifiService: setWifiEnabled: true pid=6772, uid=10118
08-17 10:26:19.086  1037  1999 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-17 10:26:19.526  6772  6772 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-17 10:26:24.094  6772  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 10:26:24.094  6772  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1105f6fe added. We now have 4 listener(s)
08-17 10:26:24.094  6772  6842 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 10:26:24.111  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:26:24.112  6772  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1105f6fe removed from the list
08-17 10:26:24.112  6772  6842 D io.jxcore.node.ConnectivityMonitor: stop
08-17 10:26:24.112  6772  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:26:24.112  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:26:24.113  6772  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 10:26:24.113  6772  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@173fbe5f added. We now have 4 listener(s)
08-17 10:26:24.113  6772  6842 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 10:26:24.117  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:26:24.117  6772  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@173fbe5f removed from the list
08-17 10:26:24.117  6772  6842 D io.jxcore.node.ConnectivityMonitor: stop
08-17 10:26:24.117  6772  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:26:24.117  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:26:24.119  6772  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 10:26:24.119  6772  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2e9f30ac added. We now have 4 listener(s)
08-17 10:26:24.119  6772  6842 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 10:26:24.121  1037  1963 D WifiServiceImplEx: setWifiEnabled: false pid=6772, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-17 10:26:24.122  1037  1963 D WifiService: setWifiEnabled: false pid=6772, uid=10118
08-17 10:26:24.122  1037  1963 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-17 10:26:24.144  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-17 10:26:24.145  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-17 10:26:24.145  1037  1037 D Ulp_jni : JNI:system_update. Event-4
08-17 10:26:24.147  1037  1541 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-17 10:26:24.148  1037  1541 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-17 10:26:24.148  1037  1541 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-17 10:26:24.149  1037  1541 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-17 10:26:24.150  1037  1541 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-17 10:26:24.150  1037  1541 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-17 10:26:24.150  1037  1541 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-17 10:26:24.150  1037  1541 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-17 10:26:24.151  1037  1541 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-17 10:26:24.151  1037  1541 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,08-17 10:26:24.157  1037  1740 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 10:26:24.158  1037  1740 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@133e95c3 mBinding = false
08-17 10:26:24.160  1037  1541 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-17 10:26:24.161  1037  1540 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-17 10:26:24.161  1037  1540 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-17 10:26:24.161  1037  1541 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-17 10:26:24.161  2658  2658 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-17 10:26:24.162  1037  1541 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-17 10:26:24.162  1037  1541 D WifiNative-wlan0: doBoolean: SET ps 1
08-17 10:26:24.165  1037  1541 D WifiNative-wlan0: SET ps 1: returned true
,08-17 10:26:24.169  1037  2800 D DhcpStateMachine: RunningState{ when=-4ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-17 10:26:24.175   320   896 D CommandListener: Clearing all IP addresses on wlan0
08-17 10:26:24.204  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-17 10:26:24.205  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-17 10:26:24.205  1037  1037 D Ulp_jni : JNI:system_update. Event-4
,08-17 10:26:24.207  1037  1120 D BluetoothManagerService: Message: 2
08-17 10:26:24.210  1037  1120 D BluetoothManagerService: Sending off request.
08-17 10:26:24.211  3915  3933 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-17 10:26:24.218  6772  6842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 10:26:24.264  6772  6842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 10:26:24.264  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:26:24.264  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 10:26:24.264  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 10:26:24.264  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 10:26:24.264  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 10:26:24.264  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 10:26:24.264  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 10:26:24.271  3915  4001 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-17 10:26:24.271  3915  4001 D BluetoothAdapterProperties: Setting state to 13
08-17 10:26:24.271  3915  4001 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-17 10:26:24.272  1037  1548 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-17 10:26:24.272  1037  1120 D BluetoothManagerService: Message: 60
08-17 10:26:24.272  1037  1120 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-17 10:26:24.272  1037  1548 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
08-17 10:26:24.272  1037  1120 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-17 10:26:24.272  6772  6842 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 10:26:24.272  6772  6842 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 10:26:24.273  3915  4001 D BluetoothAdapterProperties: onBluetoothDisable()
08-17 10:26:24.274  3915  4001 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-17 10:26:24.276  1037  2028 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
,08-17 10:26:24.277  1037  2796 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-17 10:26:24.277  1037  2796 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-17 10:26:24.277  1037  2796 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-17 10:26:24.277  1037  2796 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-17 10:26:24.277  1037  2796 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
,08-17 10:26:24.293  1037  1540 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-17 10:26:24.293  1037  1540 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-17 10:26:24.293  1037  1540 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@dc8b449
08-17 10:26:24.293  1037  1541 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 10:26:24.294  1037  1541 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 10:26:24.294  1037  1540 D LGWifiP2pService: P2pDisablingState
08-17 10:26:24.294  1037  1540 D LGWifiP2pService: P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-17 10:26:24.294  1037  1540 D LGWifiP2pService: p2p socket connection lost
08-17 10:26:24.294  1037  1540 D LGWifiP2pService: P2pDisabledState
08-17 10:26:24.294  1037  1541 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 10:26:24.295  6772  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 10:26:24.295  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:26:24.295  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:26:24.295  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 10:26:24.295  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 10:26:24.295  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 10:26:24.295  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 10:26:24.295  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 10:26:24.295  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 10:26:24.295  1037  1541 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 10:26:24.295  1037  1541 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 10:26:24.295  6772  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 10:26:24.296  1037  1541 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 10:26:24.296  6772  6772 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-17 10:26:24.296  1037  1541 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-17 10:26:24.297  1037  1541 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-17 10:26:24.298  3915  4006 D BluetoothAdapterProperties: Scan Mode:20
08-17 10:26:24.298  3915  4001 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-17 10:26:24.299  3915  4312 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-17 10:26:24.299  3915  4001 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-17 10:26:24.300  3915  4278 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-17 10:26:24.300  3915  4278 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-17 10:26:24.300  3915  4278 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-17 10:26:24.300  3915  4278 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-17 10:26:24.300  3915  4278 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-17 10:26:24.300  3915  4278 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-17 10:26:24.300  3915  4278 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-17 10:26:24.300  3915  4278 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-17 10:26:24.301  3915  4314 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-17 10:26:24.301  3915  4339 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-17 10:26:24.301  3915  4124 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-17 10:26:24.301  3915  4124 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-17 10:26:24.302  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:26:24.303  3915  4124 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-17 10:26:24.303  3915  4124 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-17 10:26:24.303  3915  4124 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-17 10:26:24.303  3915  4124 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-17 10:26:24.303  3915  4124 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 10:26:24.303  3915  4124 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-17 10:26:24.303  3915  4124 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 10:26:24.303  3915  4124 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-17 10:26:24.303  3915  4124 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-17 10:26:24.303  3915  4124 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-17 10:26:24.303 , 3915  4124 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-17 10:26:24.303  3915  4124 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
,08-17 10:26:24.307  3915  4281 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-17 10:26:24.309  1037  1540 D LGWifiP2pService: P2pDisabledState{ when=-12ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-17 10:26:24.309  1037  1540 D LGWifiP2pService: DefaultState{ when=-12ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-17 10:26:24.310  1037  1541 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-17 10:26:24.310  2658  2658 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-17 10:26:24.310  1037  1541 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-17 10:26:24.310  1037  1541 D WifiNative-wlan0: doBoolean: SET ps 1
08-17 10:26:24.311  1037  1037 D WifiHS20: hidePasspointNotification off =false
08-17 10:26:24.311  1037  1541 D WifiNative-wlan0: SET ps 1: returned true
08-17 10:26:24.314  1970  1970 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-17 10:26:24.315  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 10:26:24.316  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-17 10:26:24.317  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 10:26:24.317  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 10:26:24.317  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 10:26:24.317  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-17 10:26:24.318  1037  1037 D WifiHS20: hidePasspointNotification off =false
,08-17 10:26:24.323  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 10:26:24.323  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 10:26:24.323  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-17 10:26:24.325  1037  1037 D WifiScanningService: SCAN_AVAILABLE : 1
08-17 10:26:24.326  1037  1559 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-17 10:26:24.327  1037  1037 D RttService: SCAN_AVAILABLE : 1
08-17 10:26:24.327  1037  1560 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-17 10:26:24.330  1970  1970 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
,08-17 10:26:24.332  1970  1970 D WfdsService: WifiP2pState is changed : false
08-17 10:26:24.332  1970  2334 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-17 10:26:24.332  1970  2334 D WfdsService: Set the WFDS Monitor: false
08-17 10:26:24.334   320   896 D CommandListener: Clearing all IP addresses on wlan0
08-17 10:26:24.334  1037  1548 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-17 10:26:24.334  1037  1548 D DSQN    : disableDataServiceNotify
08-17 10:26:24.335  1037  1548 D DSQN    : stop dsqn bin
08-17 10:26:24.335   320  6932 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-17 10:26:24.336  6772  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 10:26:24.336  1037  2796 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
08-17 10:26:24.336  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:26:24.336  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:26:24.336  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 10:26:24.336  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 10:26:24.336  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 10:26:24.336  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 10:26:24.336  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 10:26:24.336  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 10:26:24.337  1037  1118 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-17 10:26:24.337  6772  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 10:26:24.337  6772  6772 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-17 10:26:24.338  1970  2334 D WfdsMonitor: WFDS Monitor is stopped
08-17 10:26:24.338  1970  2334 D WfdsService: STATE : WfdsDisabledState - enter
08-17 10:26:24.338  1970  2737 D CtrlSupplicant: Received on exit socket, terminate
08-17 10:26:24.338  1970  2737 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-17 10:26:24.338  1970  2737 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-17 10:26:24.338  1970  2737 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-17 10:26:24.339  1970  2335 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-17 10:26:24.340  1970  2334 W WfdsService: DefaultState - msg [9445378] is not handled
08-17 10:26:24.341  6772  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 10:26:24.341  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:26:24.341  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:26:24.341  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 10:26:24.341  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 10:26:24.341  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 10:26:24.341  6772  6772 V io.jxcore.node.Connec,tivityMonitor:     - BSSID name: null
08-17 10:26:24.341  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 10:26:24.341  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 10:26:24.341  6772  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 10:26:24.341  6772  6772 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-17 10:26:24.343  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:26:24.344  1037  1548 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-17 10:26:24.344  1037  1548 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 10:26:24.344  1037  1548 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-17 10:26:24.345  1037  1548 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-17 10:26:24.345  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 10:26:24.345  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-17 10:26:24.346  1037  1548 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-17 10:26:24.346  1605  1817 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-17 10:26:24.346  1037  1541 D WifiNative-p2p0: doBoolean: TERMINATE
08-17 10:26:24.346  1037  1548 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-17 10:26:24.346  1037  1548 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-17 10:26:24.346  1037  2796 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-17 10:26:24.347  1037  2796 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-17 10:26:24.347  1037  2796 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-17 10:26:24.347  1970  1970 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-17 10:26:24.348  1037  1541 D WifiNative-p2p0: TERMINATE: returned true
08-17 10:26:24.348  1037  1541 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-17 10:26:24.348  1037  1541 E WifiStateMachine: useWiFiOffloading() : false
08-17 10:26:24.348  1037  1541 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-17 10:26:24.348  1037  1548 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-17 10:26:24.348  6446  6446 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-17 10:26:24.349  3915  3915 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-17 10:26:24.349  3915  3915 D BluetoothMapService: STATE_TURNING_OFF
08-17 10:26:24.349  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 10:26:24.349  3915  3915 V BluetoothMapService: Handler(): got msg=4
08-17 10:26:24.349  3915  3915 D BluetoothMapService: MAP Service closeService in
08-17 10:26:24.350  3915  3915 D BluetoothMapMasInstance: MAP Service shutdown
08-17 ,10:26:24.350  3915  3915 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-17 10:26:24.350  3915  3915 V BluetoothMapService: MAP Service closeService out
08-17 10:26:24.351  3915  3915 V BtOppService: Receiver DISABLED_ACTION 
08-17 10:26:24.351  3915  3915 I BtOppRfcommListener: stopping Accept Thread
08-17 10:26:24.351  3915  3915 V BtOppRfcommListener: close mBtServerSocket
08-17 10:26:24.351  3915  3915 V BtOppRfcommListener: waiting for thread to terminate
08-17 10:26:24.351  3915  4312 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-17 10:26:24.351  3915  3915 V BtOppRfcommListener: done waiting for thread to terminate
08-17 10:26:24.374  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-17 10:26:24.389  1037  1099 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6934 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-17 10:26:24.391  1037  1037 D WifiHS20: hidePasspointNotification off =false
08-17 10:26:24.392  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 10:26:24.392  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 10:26:24.392  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-17 10:26:24.393  1970  1970 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-17 10:26:24.401  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-17 10:26:24.401  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-17 10:26:24.403  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 10:26:24.404  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 10:26:24.431  1037  1999 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6951 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-17 10:26:24.433  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-17 10:26:24.433  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-17 10:26:24.433  1037  1037 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-17 10:26:24.433  3915  3915 V BtOppService: onDestroy
08-17 10:26:24.433  2658  2658 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-17 10:26:24.433  2658  2658 I wpa_supplicant: monitor socket send errors count : 1
08-17 10:26:24.433  2658  2658 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1970-2\x00 that cannot receive messages
08-17 10:26:24.435  1037  2728 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-17 10:26:24.435  1037  2728 D WifiMonitor: Dropping event because (p2p0) is stopped
08-17 10:26:24.437  1037  1548 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-17 10:26:24.437  1037  1548 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-17 10:26:24.437  3915  3915 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-17 10:26:24.438  1037  1539 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-17 10:26:24.438  1037  1037 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-17 10:26:24.438  1037  1037 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-17 10:26:24.438  1037  1037 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-17 10:26:24.438  1037  1037 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-17 10:26:24.440  1037  1548 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-17 10:26:24.440  1037  1548 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 10:26:24.440  1037  1548 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 10:26:24.441  1037  1539 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-17 10:26:24.441  1037  1541 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 10:26:24.441  1037  1541 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-17 10:26:24.441  1037  1037 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-17 10:26:24.441  1037  1037 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-17 10:26:24.442  1037  1037 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-17 10:26:24.442  1037  1037 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-17 10:26:24.443  1037  1548 D NetworkManagementService: Removing idletimer
08-17 10:26:24.444  1037  1548 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-17 10:26:24.446  1037  1548 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-17 10:26:24.447  1882  1882 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 10:26:24.447  6772  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 10:26:24.447  1882  1882 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-17 10:26:24.447  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:26:24.447  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:26:24.447  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 10:26:24.447  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 10:26:24.447  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 10:26:24.447  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 10:26:24.447  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 10:26:24.447  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 10:26:24.451  6772  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 10:26:24.451  6772  6772 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 10:26:24.452  6772  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 10:26:24.452  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:26:24.452  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:26:24.452  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 10:26:24.452  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 10:26:24.452  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 10:26:24.452  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 10:26:24.452  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 10:26:24.452  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 10:26:24.453  6772  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 10:26:24.453  6772  6772 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 10:26:24.454  6772  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 10:26:24.454  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:26:24.454  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:26:24.454  6772  6772 V io.jxcore.node.Connectivi,tyMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 10:26:24.454  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 10:26:24.454  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 10:26:24.454  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 10:26:24.454  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 10:26:24.454  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 10:26:24.454  6772  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 10:26:24.454  6772  6772 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 10:26:24.456  6772  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 10:26:24.456  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:26:24.456  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:26:24.456  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 10:26:24.456  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 10:26:24.456  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 10:26:24.456  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 10:26:24.456  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 10:26:24.456  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 10:26:24.456  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:26:24.457  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:26:24.459  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-17 10:26:24.460  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 10:26:24.461  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 10:26:24.464  6934  6934 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-17 10:26:24.465  6934  6934 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-17 10:26:24.465  6934  6934 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-17 10:26:24.465  6934  6934 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-17 10:26:24.466  6934  6934 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,08-17 10:26:24.467  6934  6934 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-17 10:26:24.467  1037  2800 D DhcpStateMachine: StoppedState
08-17 10:26:24.467  1037  2800 D DhcpStateMachine: StoppedState{ when=-156ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-17 10:26:24.468  1037  1541 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-17 10:26:24.469  1037  1541 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-17 10:26:24.471  2658  2658 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-17 10:26:24.472  2658  2658 W wpa_supplicant: USIM:  scard_deinit function
08-17 10:26:24.472  1037  2728 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-17 10:26:24.472  1037  2728 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-17 10:26:24.472  1037  2728 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-17 10:26:24.473  1037  2728 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-17 10:26:24.473  1037  2728 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-17 10:26:24.473  1037  2728 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-17 10:26:24.473  1037  1541 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=361643
08-17 10:26:24.473  1037  1120 D Tethering: InitialState.processMessage what=4
08-17 10:26:24.473  1037  1541 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=361643
08-17 10:26:24.474  1037  1541 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=361643  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-17 10:26:24.474  1037  1541 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=361644  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-17 10:26:24.475  1037  1120 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-17 10:26:24.476  1037  1541 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-17 10:26:24.476  1037  1541 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-17 10:26:24.488  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-17 10:26:24.489  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 10:26:24.489  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-17 10:26:24.507  6951  6951 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-17 10:26:24.511  6951  6951 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-17 10:26:24.511  6951  6951 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-17 10:26:24.513  1037  1983 I ActivityManager: Killing 6229:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-17 10:26:24.532  1037  1658 W libprocessgroup: failed to open /acct/uid_10014/pid_6229/cgroup.procs: No such file or directory
,08-17 10:26:24.581  6934  6934 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-17 10:26:24.581  2658  2658 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-17 10:26:24.581  1037  2728 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-17 10:26:24.582  1037  2728 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
08-17 10:26:24.582  1037  2728 D WifiMonitor: Disconnecting from the supplicant, no more events
08-17 10:26:24.584  3915  3915 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-17 10:26:24.584  3915  3915 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-17 10:26:24.584  3915  3915 V BluetoothPbapReceiver: ***********state = 13
08-17 10:26:24.585  1037  1541 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
08-17 10:26:24.586  3915  3915 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-17 10:26:24.588  3915  3915 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-17 10:26:24.588  3915  3915 V BluetoothPbapService: state: 13
08-17 10:26:24.588  3915  3915 V BluetoothPbapService: Pbap Service closeService in
08-17 10:26:24.593  6934  6934 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-17 10:26:24.594  3915  3915 V BluetoothPbapService: successfully stopped pbap service
08-17 10:26:24.594  3915  3915 V BluetoothPbapService: Pbap Service closeService out
08-17 10:26:24.594  3915  3915 V BluetoothPbapService: Pbap Service onDestroy
08-17 10:26:24.594  3915  3915 V BluetoothPbapService: Pbap Service closeService in
08-17 10:26:24.594  3915  3915 V BluetoothPbapService: Pbap Service closeService out
08-17 10:26:24.594  3915  3915 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-17 10:26:24.594  2249  2249 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-17 10:26:24.650  6934  6934 D LgDataFeature: LgDataFeature() Constructor: none
08-17 10:26:24.651  6934  6934 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-17 10:26:24.663  6934  6934 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-17 10:26:24.664  1037  2044 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6972 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-17 10:26:24.674  1037  1120 D BluetoothManagerService: Message: 20
08-17 10:26:24.674  1037  1120 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3bd388ca:true
08-17 10:26:24.688  1970  1970 D WfdsService: Supplicant Connection state is changed : false
08-17 10:26:24.688  1970  2334 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
,08-17 10:26:24.689  1970  2334 D WfdsService: Set the WFDS Monitor: false
08-17 10:26:24.689  1037  1120 D BluetoothManagerService: Message: 30
08-17 10:26:24.689  1970  2334 D WfdsMonitor: WFDS Monitor is stopped
08-17 10:26:24.690  1037  1541 D WifiOffDelayIfNotUsed: stopMonitoring
08-17 10:26:24.690  1037  1541 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-17 10:26:24.690  1037  1541 E WifiStateMachine: useWiFiOffloading() : false
08-17 10:26:24.690  1037  1541 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-17 10:26:24.693  1970  1970 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-17 10:26:24.693  2512  2512 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 10:26:24.694  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 10:26:24.697  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-17 10:26:24.698  1037  1546 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-17 10:26:24.698  1037  1546 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-17 10:26:24.700  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 10:26:24.701  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:26:24.706  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:26:24.709  1037  1120 D BluetoothManagerService: Message: 30
08-17 10:26:24.717  6934  6934 D LocalBluetoothProfileManager: Adding local MAP profile
08-17 10:26:24.719  6934  6934 D BluetoothMap: Create BluetoothMap proxy object
,08-17 10:26:24.719  1037  1120 D BluetoothManagerService: Message: 30
08-17 10:26:24.723  1037  1120 D BluetoothManagerService: Message: 30
,08-17 10:26:24.725  6934  6934 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-17 10:26:24.726  6934  6934 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
08-17 10:26:24.740  6934  6934 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,08-17 10:26:24.747  6934  6934 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
,08-17 10:26:24.761  6934  6934 D DockEventReceiver: finishStartingService: stopping service
,08-17 10:26:24.781  6934  6934 D BluetoothInputDevice: Proxy object connected
,08-17 10:26:24.785  6934  6934 D HidProfile: Bluetooth service connected
08-17 10:26:24.786  6934  6934 D BluetoothPan: BluetoothPAN Proxy object connected
08-17 10:26:24.788  6934  6934 D PanProfile: Bluetooth service connected
08-17 10:26:24.789  6934  6934 D BluetoothMap: Proxy object connected
08-17 10:26:24.789  6934  6934 D MapProfile: Bluetooth service connected
08-17 10:26:24.789  6934  6934 D BluetoothMap: getConnectedDevices()
08-17 10:26:24.790  6934  6934 D BluetoothMap: Bluetooth is Not enabled
08-17 10:26:24.790  6934  6934 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-17 10:26:24.824  1037  1983 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6996 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
08-17 10:26:24.826  1037  1983 I ActivityManager: Killing 6369:com.android.defcontainer/u0a4 (adj 15): empty #17
,08-17 10:26:24.843   344   344 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 365us total 19.630ms
,08-17 10:26:24.858   344   344 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 276us total 14.354ms
,08-17 10:26:24.872   344   344 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 257us total 12.907ms
,08-17 10:26:24.900  1037  1578 W libprocessgroup: failed to open /acct/uid_10004/pid_6369/cgroup.procs: No such file or directory
,08-17 10:26:24.907  6972  6972 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-17 10:26:24.907  6972  6972 W LG Account v2.2: No ProfileInfo entries
,08-17 10:26:24.907  6972  6972 I LG Account v2.2: isEnabled: false
08-17 10:26:24.907  6972  6972 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-17 10:26:24.907  6972  6972 I Feature : [Lifetracker]Country: EU
08-17 10:26:24.908  6972  6972 I Feature : [Lifetracker]Operator: OPEN
08-17 10:26:24.908  6972  6972 I Feature : [Lifetracker]Ranking support: false
08-17 10:26:24.908  6972  6972 I Feature : [Lifetracker]Comfort support: false
08-17 10:26:24.908  6972  6972 I Feature : [Lifetracker]Accessory: true
08-17 10:26:24.908  6972  6972 I Feature : [Lifetracker]Health device: true
08-17 10:26:24.908  6972  6972 I Feature : [Lifetracker]Extra Pedometer: false
08-17 10:26:24.908  6972  6972 I Feature : [Lifetracker]Blood glucose device: false
08-17 10:26:24.908  6972  6972 I Feature : [Lifetracker]Device Number: 3
08-17 10:26:24.922  6934  6934 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-17 10:26:24.930  6934  6934 D BluetoothPermissionRequest: onReceive
08-17 10:26:24.932  6996  6996 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-17 10:26:24.934  6934  6934 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-17 10:26:24.948  6934  6934 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-17 10:26:24.951  1037  1963 I ActivityManager: Killing 2191:com.lge.music/u0a34 (adj 15): empty #17
,08-17 10:26:24.972   324  4037 V AudioFlinger: 2191 died, releasing its sessions
08-17 10:26:24.972  1037  1037 D MediaSessionService: clear user.mLastMediaButtonReceiver
08-17 10:26:24.972   324  4037 V AudioFlinger:  pid 1882 @ 0
08-17 10:26:24.972   324  4037 V AudioFlinger:  pid 3438 @ 1
08-17 10:26:24.972   324  4037 V AudioFlinger:  pid 3438 @ 2
,08-17 10:26:24.992  3915  3915 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
,08-17 10:26:24.993  3915  3915 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-17 10:26:24.993  3915  3915 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
,08-17 10:26:24.994  1037  1816 W libprocessgroup: failed to open /acct/uid_10034/pid_2191/cgroup.procs: No such file or directory
08-17 10:26:24.998  6996  6996 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
08-17 10:26:25.002  3915  3915 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-17 10:26:25.002  3915  3915 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-17 10:26:25.007  3915  3915 V BluetoothFtpService: Ftp Service onStartCommand
08-17 10:26:25.008  3915  3915 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-17 10:26:25.008  3915  3915 V BluetoothFtpService: Ftp Service closeService
08-17 10:26:25.008  3915  3915 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
,08-17 10:26:25.011  3915  3915 V BluetoothFtpService: successfully stopped ftp service
08-17 10:26:25.011  3915  3915 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-17 10:26:25.012  3915  3915 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-17 10:26:25.012  3915  3915 V BluetoothSapReceiver: SapReceiver onReceive 
08-17 10:26:25.012  3915  3915 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-17 10:26:25.012  3915  3915 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-17 10:26:25.012  3915  3915 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-17 10:26:25.014  3915  3915 V BluetoothFtpService: Ftp Service onDestroy
08-17 10:26:25.014  3915  3915 V BluetoothFtpService: Ftp Service closeService
08-17 10:26:25.070  6996  6996 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-17 10:26:25.070  6996  6996 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-17 10:26:25.070  6996  6996 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-17 10:26:25.071  6996  6996 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-17 10:26:25.071  6996  6996 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-17 10:26:25.072  1037  1578 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7015 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-17 10:26:25.073  6996  6996 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-17 10:26:25.073  3915  3915 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-17 10:26:25.073  3915  3915 V BluetoothSapService: state: 13
08-17 10:26:25.073  3915  3915 V BluetoothSapService: Stopping SAP server process
,08-17 10:26:25.078  3915  3915 V BluetoothSapService: Sap Service closeSapService in
08-17 10:26:25.078  3915  3915 V BluetoothSapService: Close listen Socket : 
08-17 10:26:25.078  3915  3915 V BluetoothSapService: Close rfcomm Socket : 
08-17 10:26:25.078  3915  3915 V BluetoothSapService: Close sapd  Socket : 
08-17 10:26:25.079  3915  3915 V BluetoothSapService: Sap Service closeSapService out
08-17 10:26:25.079  3915  3915 V BluetoothSapService: Sap Service onDestroy
08-17 10:26:25.079  3915  3915 V BluetoothSapService: Sap Service closeSapService in
08-17 10:26:25.079  3915  3915 V BluetoothSapService: Close listen Socket : 
08-17 10:26:25.079  3915  3915 V BluetoothSapService: Close rfcomm Socket : 
08-17 10:26:25.079  3915  3915 V BluetoothSapService: Close sapd  Socket : 
08-17 10:26:25.080  3915  3915 V BluetoothSapService: Sap Service closeSapService out
08-17 10:26:25.082  6996  6996 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-17 10:26:25.092  6996  6996 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-17 10:26:25.095  6996  6996 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-17 10:26:25.109  6996  6996 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-17 10:26:25.113  6446  6446 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-17 10:26:25.115  6996  6996 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-17 10:26:25.116  6951  6951 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-17 10:26:25.117  6951  6951 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-17 10:26:25.117  6951  6951 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-17 10:26:25.118  6996  6996 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-17 10:26:25.120  6934  6934 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-17 10:26:25.126  6934  6934 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 10:26:25.135  6996  6996 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-17 10:26:25.136  6996  6996 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-17 10:26:25.137  6996  6996 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-17 10:26:25.143  6446  6446 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-17 10:26:25.147  6951  6951 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-17 10:26:25.147  6951  6951 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-17 10:26:25.147  6951  6951 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-17 10:26:25.150  7015  7015 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-17 10:26:25.152  6934  6934 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-17 10:26:25.157  6934  6934 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-17 10:26:25.163  6996  6996 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-17 10:26:25.164  6996  6996 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-17 10:26:25.165  6996  6996 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-17 10:26:25.224  1037  1985 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7035 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
08-17 10:26:25.226  1037  1985 I ActivityManager: Killing 6480:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,08-17 10:26:25.305  3915  4006 D bt_hci_bdroid: cleanup
,08-17 10:26:25.305  3915  4126 I bt_lpm  : LPM is already off!!!
08-17 10:26:25.305  3915  4124 W bt-btif : ag scb idx 1 not allocated
08-17 10:26:25.305  3915  4124 E bt-btif : BTA AG is already disabled, ignoring ...
08-17 10:26:25.305  3915  4124 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-17 10:26:25.305  3915  4124 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 10:26:25.305  3915  4124 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-17 10:26:25.305  3915  4124 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 10:26:25.306  3915  4124 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-17 10:26:25.306  3915  4124 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-17 10:26:25.306  3915  4124 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-17 10:26:25.306  3915  4124 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 10:26:25.306  3915  4124 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-17 10:26:25.306  3915  4124 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 10:26:25.306  3915  4124 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-17 10:26:25.306  3915  4124 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-17 10:26:25.306  3915  4124 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-17 10:26:25.306  3915  4124 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 10:26:25.306  3915  4124 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-17 10:26:25.306  3915  4124 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 10:26:25.306  3915  4124 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-17 10:26:25.306  3915  4124 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-17 10:26:25.306  3915  4124 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-17 10:26:25.306  3915  4269 I bt_userial_mct: exiting userial_read_thread
08-17 10:26:25.306  3915  4269 D bt_userial_mct: Leaving userial_evt_read_thread()
08-17 10:26:25.307  3915  4006 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-17 10:26:25.307  3915  4126 I bt_vendor: hw_epilog_process
08-17 10:26:25.307  3915  4006 D bt_hci_bdroid: cleanup Finalizing cleanup
08-17 10:26:25.308  3915  4006 D bt_userial_mct: userial_close
08-17 10:26:25.308  3915  4006 E bt_userial_mct: pthread_join() FAILED result:3
08-17 10:26:25.308  3915  4006 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-17 10:26:25.308  1037  2044 W libprocessgroup: failed to open /acct/uid_10008/pid_6480/cgroup.procs: No such file or directory
08-17 10:26:25.372  6951  6951 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-17 10:26:25.379  6934  6934 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-17 10:26:25.381  3915  4006 D bt_hci_bdroid: set_power 0
08-17 10:26:25.381  3915  4006 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,08-17 10:26:25.381  3915  4006 I bt_vendor: bluetooth satus is on
08-17 10:26:25.381  3915  4006 I bt_vendor: bt-vendor : resetting BT status
08-17 10:26:25.381  3915  4006 I bt_vendor: Starting hciattach daemon
08-17 10:26:25.381  3915  4006 I bt_vendor: try to set false
08-17 10:26:25.382  3915  4006 I bt_vendor: Starting hciattach daemon
08-17 10:26:25.382  3915  4006 I bt_vendor: try to set false
08-17 10:26:25.383  3915  4006 I bt_vendor: cleanup
08-17 10:26:25.384  3915  4124 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-17 10:26:25.385  3915  4006 I GKI_LINUX: GKI_exit_task 0 done
08-17 10:26:25.385  3915  4006 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-17 10:26:25.387  3915  4001 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,08-17 10:26:25.391  3915  3915 D HeadsetService: Received stop request...Stopping profile...
08-17 10:26:25.392  6934  6934 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 10:26:25.393  3915  3915 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-17 10:26:25.393  3915  3915 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-17 10:26:25.393  3915  3915 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@344b8930
08-17 10:26:25.394  3915  4028 D HeadsetStateMachine: Exit Disconnected: -1
08-17 10:26:25.402  1037  1037 D BluetoothHeadset: Proxy object disconnected
08-17 10:26:25.402  1037  1037 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-17 10:26:25.403  3915  3915 D A2dpService: Received stop request...Stopping profile...
,08-17 10:26:25.404  3915  3915 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
,08-17 10:26:25.406  3915  4088 D A2dpStateMachine: Exit Disconnected: -1
08-17 10:26:25.409  1882  1882 D BluetoothHeadset: Proxy object disconnected
08-17 10:26:25.409  1882  1882 D BluetoothHeadset: Proxy object disconnected
08-17 10:26:25.409  1882  1882 D BluetoothHeadset: Proxy object disconnected
,08-17 10:26:25.412  3915  4001 D BluetoothAdapterState: Stopping profile services that were post enabled
08-17 10:26:25.413  3915  3915 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-17 10:26:25.413  3915  3915 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-17 10:26:25.413  3915  3915 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@344b8930
08-17 10:26:25.414  1037  1037 D BluetoothA2dp: Proxy object disconnected
08-17 10:26:25.414  1037  1037 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-17 10:26:25.416  3915  3915 D HidService: Received stop request...Stopping profile...
08-17 10:26:25.416  3915  3915 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@344b8930
08-17 10:26:25.417  7035  7055 W FormManager: Network not available. Please check & try again.
,08-17 10:26:25.419  6934  6934 D BluetoothInputDevice: Proxy object disconnected
,08-17 10:26:25.419  6934  6934 D HidProfile: Bluetooth service disconnected
08-17 10:26:25.420  3915  3915 D HealthService: Received stop request...Stopping profile...
08-17 10:26:25.422  3915  3915 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@344b8930
08-17 10:26:25.424  3915  3915 D PanService: Received stop request...Stopping profile...
08-17 10:26:25.424  3915  3915 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@344b8930
08-17 10:26:25.426  3915  3915 D HeadsetStateMachine: Unbinding service...
08-17 10:26:25.428  3915  3915 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-17 10:26:25.428  3915  3915 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-17 10:26:25.428  3915  3915 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-17 10:26:25.428  3915  3915 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-17 10:26:25.429  3915  3915 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-17 10:26:25.429  3915  3915 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-17 10:26:25.429  3915  3915 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-17 10:26:25.429  3915  3915 D BtGatt.DebugUtils: handleDebugAction() action=null
08-17 10:26:25.429  6934  6934 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-17 10:26:25.429  6934  6934 D PanProfile: Bluetooth service disconnected
08-17 10:26:25.429  3915  3915 D BtGatt.GattService: Received stop request...Stopping profile...
08-17 10:26:25.429  3915  3915 D BtGatt.GattService: stop()
08-17 10:26:25.430  3915  3915 D BtGatt.AdvertiseManager: advertise clients cleared
08-17 10:26:25.431  3915  3915 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@344b8930
08-17 10:26:25.432  7035  7056 V FormManager: Network unavailable.
,08-17 10:26:25.433  3915  3915 D BluetoothMapService: Received stop request...Stopping profile...
08-17 10:26:25.433  3915  3915 D BluetoothMapService: stop()
08-17 10:26:25.434  3915  3915 D BluetoothMapEmailAppObserver: deinitObservers()
08-17 10:26:25.435  6934  6934 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-17 10:26:25.435  3915  3915 D BluetoothMapEmailAppObserver: removeReceiver()
08-17 10:26:25.435  6934  6934 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-17 10:26:25.435  6934  6934 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-17 10:26:25.435  6934  6934 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-17 10:26:25.437  3915  3915 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@344b8930
08-17 10:26:25.437  7035  7056 V FormManager: Network unavailable.
08-17 10:26:25.437  6934  6934 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-17 10:26:25.439  3915  3915 I BluetoothA2dpServiceJni: cleanupNative
08-17 10:26:25.439  3915  4090 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-17 10:26:25.439  3915  3915 I GKI_LINUX: GKI_exit_task 2 done
08-17 10:26:25.439  3915  3915 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-17 10:26:25.440  3915  3915 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-17 10:26:25.440  3915  3915 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-17 10:26:25.440  3915  3915 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-17 10:26:25.440  3915  3915 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-17 10:26:25.440  3915  3915 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-17 10:26:25.440  3915  3915 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-17 10:26:25.440  3915  3915 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-17 10:26:25.441  3915  3915 V BluetoothMapService: Handler(): got msg=4
08-17 10:26:25.441  3915  3915 D BluetoothMapService: MAP Service closeService in
08-17 10:26:25.441  3915  3915 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-17 10:26:25.441  3915  3915 V BluetoothMapService: MAP Service closeService out
08-17 10:26:25.442  3915  3915 D BluetoothMapService: cleanup()
08-17 10:26:25.442  3915  3915 D BluetoothMapService: MAP Service closeService in
08-17 10:26:25.442  3915  3915 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-17 10:26:25.442  3915  3915 V BluetoothMapService: MAP Service closeService out
08-17 10:26:25.442  3915  4001 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-17 10:26:25.442  3915  4001 D BluetoothAdapterProperties: Setting state to 10
08-17 10:26:25.442  3915  4001 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-17 10:26:25.443  1037  1120 D BluetoothManagerService: Message: 60
08-17 10:26:25.443  1037  1120 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-17 10:26:25.443  1037  1120 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-17 10:26:25.443  3915  4001 I BluetoothAdapterState: Entering OffState
08-17 10:26:25.443  6934  6950 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-17 10:26:25.446  6934  6949 D BluetoothPbap: onBluetoothStateChange: up=false
08-17 10:26:25.448  6934  6950 D BluetoothMap: onBluetoothStateChange: up=false
08-17 10:26:25.449  6934  6934 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-17 10:26:25.449  1882  2572 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-17 10:26:25.450  1037  1120 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 10:26:25.450  1882  2571 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 10:26:25.450  6934  6934 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-17 10:26:25.450  6934  6934 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-17 10:26:25.450  6934  6934 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-17 10:26:25.451  6934  6934 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-17 10:26:25.451  6934  6949 D BluetoothPan: onBluetoothStateChange on: false
08-17 10:26:25.451  6934  6934 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-17 10:26:25.451  1882  1897 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 10:26:25.455  4343  4343 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-17 10:26:25.455  4343  4343 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-17 10:26:25.456  1037  1120 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-17 10:26:25.457  1037  1963 I ActivityManager: Killing 6007:com.lge.appbox.client/u0a11 (adj 15): empty #17
08-17 10:26:25.457  4343  4343 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-17 10:26:25.486  1037  1120 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-17 10:26:25.486  1037  1120 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
,08-17 10:26:25.488  1037  2117 W libprocessgroup: failed to open /acct/uid_10011/pid_6007/cgroup.procs: No such file or directory
08-17 10:26:25.489  4343  4343 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-17 10:26:25.489  1037  1120 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-17 10:26:25.490  1037  1120 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-17 10:26:25.490  1037  1120 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@133e95c3 mBinding = false
08-17 10:26:25.491  1037  1120 D BluetoothManagerService: Sending unbind request.
08-17 10:26:25.493  1037  1120 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-17 10:26:25.501  3915  4006 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-17 10:26:25.502  3915  3915 I GKI_LINUX: GKI_exit_task 1 done
08-17 10:26:25.502  3915  3915 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-17 10:26:25.502  3915  3915 I BluetoothServiceJni: cleanupNative: return from cleanup
08-17 10:26:25.503  3915  3915 I art     : --- WEIRD: removing null entry 246
08-17 10:26:25.503  3915  3915 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-17 10:26:25.503  3915  3915 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-17 10:26:25.503  4343  7059 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-17 10:26:25.505  3915  3915 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-17 10:26:25.508  3915  3915 I art     : System.exit called, status: 0
08-17 10:26:25.508  3915  3915 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-17 10:26:25.509  1970  1970 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-17 10:26:25.509  1970  2183 D LGBluetoothAPIService: Message: 2
08-17 10:26:25.509  4343  7060 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-17 10:26:25.509  1970  2183 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@1e64d603 mBinding = false
08-17 10:26:25.509  4343  7060 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-17 10:26:25.509  1970  2183 D LGBluetoothAPIService: Sending unbind request.
08-17 10:26:25.512  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-17 10:26:25.512  6934  6934 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-17 10:26:25.513  6934  6934 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-17 10:26:25.513  6934  6934 D LGBluetoothEventManager: [BTUI] clear device connection state
08-17 10:26:25.514  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:26:25.515  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:26:25.516  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 10:26:25.520  6934  6934 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-17 10:26:25.522  1605  1605 D BluetoothAdapter: 171690696: getState() :  mService = null. Returning STATE_OFF
08-17 10:26:25.522  1605  1605 D BluetoothAdapter: 171690696: getState() :  mService = null. Returning STATE_OFF
08-17 10:26:25.529  6951  6951 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-17 10:26:25.529  6951  6951 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-17 10:26:25.529  6951  6951 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-17 10:26:25.535  6934  6934 D DockEventReceiver: finishStartingService: stopping service
,08-17 10:26:25.536  6934  6934 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-17 10:26:25.542  7035  7064 W FormManager: Network not available. Please check & try again.
08-17 10:26:25.544   324   324 V AudioFlinger: 3915 died, releasing its sessions
08-17 10:26:25.545   324   324 V AudioFlinger:  pid 1882 @ 0
08-17 10:26:25.545   324   324 V AudioFlinger:  pid 3438 @ 1
08-17 10:26:25.545   324   324 V AudioFlinger:  pid 3438 @ 2
08-17 10:26:25.545  7035  7065 V FormManager: Network unavailable.
,08-17 10:26:25.549  6934  6934 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-17 10:26:25.549  6934  6934 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-17 10:26:25.558  1037  1054 I ActivityManager: Process com.android.bluetooth (pid 3915) has died
08-17 10:26:25.559  1037  1054 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,08-17 10:26:25.567  2249  2249 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-17 10:26:25.570  7035  7065 V FormManager: Network unavailable.
08-17 10:26:25.587  6934  6934 D BluetoothPermissionRequest: onReceive
,08-17 10:26:25.592  6934  6934 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-17 10:26:25.592  6934  6934 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-17 10:26:25.598  6934  6934 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-17 10:26:25.674  1037  1999 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7066 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
08-17 10:26:25.691  6996  6996 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,08-17 10:26:25.693  6996  6996 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-17 10:26:25.694  6996  6996 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-17 10:26:25.740  6996  6996 D LgDataFeature: LgDataFeature() Constructor: none
08-17 10:26:25.740  6996  6996 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-17 10:26:25.747  6996  6996 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-17 10:26:25.750  6996  6996 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-17 10:26:25.750  6996  6996 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-17 10:26:25.750  6996  6996 V SoundPool: doLoad: loading sample sampleID=1
08-17 10:26:25.752  6996  7085 V SoundPool: Start decode
08-17 10:26:25.752  6996  7085 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-17 10:26:25.754   324  4037 V MediaPlayerService: decode(23, 10857164, 17813)
08-17 10:26:25.754   324  4037 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-17 10:26:25.754  6996  6996 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-17 10:26:25.754   324  4037 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-17 10:26:25.754   324  4037 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-17 10:26:25.754   324  4037 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-17 10:26:25.754   324  4037 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-17 10:26:25.754   324  4037 V MediaPlayerService: player type = 3
08-17 10:26:25.754   324  4037 V AwesomePlayer: AwesomePlayer create()
,08-17 10:26:25.757   324  4037 V AwesomePlayer: reset_l() 
08-17 10:26:25.757   324  4037 V AwesomePlayer: cancelPlayerEvents
08-17 10:26:25.757   324  4037 V AwesomePlayer: setAudioSink() 
08-17 10:26:25.757   324  4037 V AwesomePlayer: reset_l() 
08-17 10:26:25.757   324  4037 V AudioCache: notify(0xb5474dc0, 8, 0, 0)
08-17 10:26:25.757   324  4037 V AudioCache: ignored
08-17 10:26:25.757   324  4037 V AwesomePlayer: cancelPlayerEvents
08-17 10:26:25.758   324  4037 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-17 10:26:25.759   324  4037 V AwesomePlayer: setDataSource_l dataSource
08-17 10:26:25.759   324  4037 V LGParserOSAL: SniffLGParser start
08-17 10:26:25.759   324  4037 V LGParserOSAL: MainType:5, SubType=0
08-17 10:26:25.759   324  4037 V LGParserOSAL: #### check Mime : application/ogg
08-17 10:26:25.759   324  4037 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-17 10:26:25.759   324  4037 E MediaExtractor: Use LGExtractor :application/ogg 
08-17 10:26:25.767  6694  6694 D UEI.SmartControl: QS Service created
08-17 10:26:25.767  6996  6996 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-17 10:26:25.771  6996  6996 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,08-17 10:26:25.772  6996  6996 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-17 10:26:25.773  7066  7066 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-17 10:26:25.773  7066  7066 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-17 10:26:25.774  7066  7066 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-17 10:26:25.774  7066  7066 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-17 10:26:25.791  6996  6996 V LGMDMManager: Create singleton instance
,08-17 10:26:25.800   324  4037 V LGParserOSAL: supported mime: application/ogg
08-17 10:26:25.800   324  4037 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-17 10:26:25.800   324  4037 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-17 10:26:25.800   324  4037 V AwesomePlayer: mBitrate = -1 bits/sec
08-17 10:26:25.800   324  4037 V AwesomePlayer: AudioTrack Setting
08-17 10:26:25.800   324  4037 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-17 10:26:25.800   324  4037 V AwesomePlayer: setAudioSource() 
08-17 10:26:25.800   324  4037 V MediaPlayerService: prepare
08-17 10:26:25.800   324  4037 V AwesomePlayer: prepareAsync_l() 
08-17 10:26:25.800   324  4037 V MediaPlayerService: wait for prepare
08-17 10:26:25.800   324  7086 V AwesomePlayer: onPrepareAsyncEvent() 
08-17 10:26:25.800   324  7086 V AwesomePlayer: initAudioDecoder() 
08-17 10:26:25.800   324  7086 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-17 10:26:25.800   324  7086 V AudioSystem: isOffloadSupported()
08-17 10:26:25.800   324  7086 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-17 10:26:25.800   324  7086 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-17 10:26:25.800   324  7086 I AudioFlinger: isAudioPlaybackHookOn() false
08-17 10:26:25.800   324  7086 V AwesomePlayer: getUseOffload() = 0 
08-17 10:26:25.800   324  7086 V OMXCodec: OMXCodec::Create
08-17 10:26:25.800   324  7086 V OMXCodec: findMatchingCodecs()
08-17 10:26:25.800   324  7086 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-17 10:26:25.800   324  7086 V OMXCodec: matchingCodecs.size()=1
08-17 10:26:25.800   324  7086 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-17 10:26:25.801  7066  7066 D BluetoothAdapterApp: Loading JNI Library
08-17 10:26:25.802   324  7086 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-17 10:26:25.802   324  7086 V LGCodecAdapter: LG Codec Adapter start
08-17 10:26:25.802   324  7086 V OMXCodec: OMXCodec Createtor
08-17 10:26:25.802   324  7086 V OMXCodec: setComponentRole
08-17 10:26:25.802   324  7086 V OMXCodec: configureCodec protected=0
08-17 10:26:25.802   324  7086 V LGCodecAdapter: called getLGCodecSpecificData
08-17 10:26:25.802   324  7086 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-17 10:26:25.802   324  7086 V LGCodecOSAL: Called LGconfigureCodecMETA
08-17 10:26:25.802   324  7086 V LGCodecOSAL: Called LGconfigureCodecMSG
08-17 10:26:25.802   324  7086 V LGCodecOSAL: Not support LGCodec
08-17 10:26:25.802   324  7086 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-17 10:26:25.802   324  7086 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-17 10:26:25.802   324  7086 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-17 10:26:25.802   324  7086 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-17 10:26:25.802   324  7086 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-17 10:26:25.803   324  7086 V AudioSystem: isOffloadSupported()
08-17 10:26:25.803   324  7086 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-17 10:26:25.803   324  7086 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-17 10:26:25.803   324  7086 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-17 10:26:25.803   324  7086 V OMXCodec: init(),
08-17 10:26:25.803   324  7086 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-17 10:26:25.803   324  7086 V OMXCodec: allocateBuffers
08-17 10:26:25.803   324  7086 V OMXCodec: allocateBuffersOnPort portIndex=0
08-17 10:26:25.803   324  7086 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-17 10:26:25.803   324  7086 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f970 on input port
08-17 10:26:25.803   324  7086 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f9c0 on input port
08-17 10:26:25.803   324  7086 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa10 on input port
08-17 10:26:25.803   324  7086 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa60 on input port
08-17 10:26:25.803   324  7086 V OMXCodec: allocateBuffersOnPort portIndex=1
08-17 10:26:25.803   324  7086 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-17 10:26:25.803   324  7086 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fab0 on output port
08-17 10:26:25.803   324  7086 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fb50 on output port
08-17 10:26:25.803   324  7086 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fc40 on output port
08-17 10:26:25.803   324  7086 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fd30 on output port
08-17 10:26:25.803   324  7086 V OMXCodec: init() mAsyncCompletion wait!!! 
08-17 10:26:25.803   324  7088 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-17 10:26:25.803   324  7088 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-17 10:26:25.803   324  7088 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-17 10:26:25.803   324  7086 V OMXCodec: init() mAsyncCompletion wait!!! 
08-17 10:26:25.803   324  7088 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-17 10:26:25.804   324  7088 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-17 10:26:25.804   324  7088 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-17 10:26:25.804   324  7086 V OMXCodec: init() mAsyncCompletion wait free! 
08-17 10:26:25.804   324  7086 V AwesomePlayer: finishAsyncPrepare_l() 
08-17 10:26:25.804   324  7086 V AudioCache: notify(0xb5474dc0, 5, 0, 0)
08-17 10:26:25.804   324  7086 V AudioCache: ignored
08-17 10:26:25.804   324  7086 V AudioCache: notify(0xb5474dc0, 1, 0, 0)
,08-17 10:26:25.804   324  7086 V AudioCache: prepared
08-17 10:26:25.804   324  4037 V AudioCache: wait - success
08-17 10:26:25.804   324  4037 V MediaPlayerService: start
08-17 10:26:25.804   324  4037 V AwesomePlayer: play_l() 
08-17 10:26:25.804   324  4037 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-17 10:26:25.804   324  4037 V AwesomePlayer: createAudioPlayer_l
08-17 10:26:25.804   324  4037 V AwesomePlayer: seekAudioIfNecessary_l() 
08-17 10:26:25.804   324  4037 V AwesomePlayer: startAudioPlayer_l() 
08-17 10:26:25.804   324  4037 D AudioPlayer: start of Playback, useOffload 0
08-17 10:26:25.804   324  4037 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-17 10:26:25.804   324  4037 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-17 10:26:25.807  6694  6694 I UEI.SmartControl: Service initServices...
08-17 10:26:25.807  6694  6694 D UEI.SmartControl: QS start get config
08-17 10:26:25.807   324  7088 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-17 10:26:25.808   324  7088 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-17 10:26:25.808   324  7088 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-17 10:26:25.808   324  7088 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-17 10:26:25.808   324  7088 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-17 10:26:25.808   324  7088 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-17 10:26:25.808   324  7088 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048496
08-17 10:26:25.808   324  7088 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-17 10:26:25.808   324  7088 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048656
08-17 10:26:25.808   324  7088 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-17 10:26:25.808   324  7088 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048896
08-17 10:26:25.808   324  7088 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-17 10:26:25.808   324  7088 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957049136
08-17 10:26:25.808   324  7088 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-17 10:26:25.808   324  7088 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-17 10:26:25.808   324  7088 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-17 10:26:25.808   324  7088 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-17 10:26:25.808   324  7088 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-17 10:26:25.808   324  7088 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-17 10:26:25.808   324  7088 V OMXCodec: allocateBuffersOnPort portIndex=1
08-17 10:26:25.808   324  7088 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-17 10:26:25.808   324  7088 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fc40 on output port
08-17 10:26:25.808   324  7088 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fb50 on output port
08-17 10:26:25.808   324  7088 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fab0 on output port
08-17 10:26:25.809   324  7088 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb17ff420 on output port
08-17 10:26:25.809   324  7088 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-17 10:26:25.809   324  7088 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-17 10:26:25.809   324  4037 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-17 10:26:25.810   324  4037 V AudioCache: notify(0xb5474dc0, 6, 0, 0)
08-17 10:26:25.810   324  4037 V AudioCache: ignored
08-17 10:26:25.810   32,4  4037 V MediaPlayerService: wait for playback complete
08-17 10:26:25.812   324  7089 V AudioCache: write(0xb57c5000, 4096)
08-17 10:26:25.812   324  7089 V AudioCache: memcpy(0xac300000, 0xb57c5000, 4096)
08-17 10:26:25.814   324  7089 V AudioCache: write(0xb57c5000, 4096)
08-17 10:26:25.814   324  7089 V AudioCache: memcpy(0xac301000, 0xb57c5000, 4096)
08-17 10:26:25.815   324  7089 V AudioCache: write(0xb57c5000, 4096)
08-17 10:26:25.815   324  7089 V AudioCache: memcpy(0xac302000, 0xb57c5000, 4096)
08-17 10:26:25.816   324  7089 V AudioCache: write(0xb57c5000, 4096)
08-17 10:26:25.816   324  7089 V AudioCache: memcpy(0xac303000, 0xb57c5000, 4096)
08-17 10:26:25.816   324  7089 V AudioCache: write(0xb57c5000, 4096)
08-17 10:26:25.816   324  7089 V AudioCache: memcpy(0xac304000, 0xb57c5000, 4096)
08-17 10:26:25.817   324  7089 V AudioCache: write(0xb57c5000, 4096)
08-17 10:26:25.817   324  7089 V AudioCache: memcpy(0xac305000, 0xb57c5000, 4096)
08-17 10:26:25.817   324  7089 V AudioCache: write(0xb57c5000, 4096)
08-17 10:26:25.817   324  7089 V AudioCache: memcpy(0xac306000, 0xb57c5000, 4096)
08-17 10:26:25.818   324  7089 V AudioCache: write(0xb57c5000, 4096)
08-17 10:26:25.818   324  7089 V AudioCache: memcpy(0xac307000, 0xb57c5000, 4096)
08-17 10:26:25.819   324  7089 V AudioCache: write(0xb57c5000, 4096)
08-17 10:26:25.819   324  7089 V AudioCache: memcpy(0xac308000, 0xb57c5000, 4096)
,08-17 10:26:25.819   324  7089 V AudioCache: write(0xb57c5000, 4096)
08-17 10:26:25.820   324  7089 V AudioCache: memcpy(0xac309000, 0xb57c5000, 4096)
08-17 10:26:25.823   324  7089 V AudioCache: write(0xb57c5000, 4096)
08-17 10:26:25.823   324  7089 V AudioCache: memcpy(0xac30a000, 0xb57c5000, 4096)
08-17 10:26:25.824   324  7089 V AudioCache: write(0xb57c5000, 4096)
08-17 10:26:25.824   324  7089 V AudioCache: memcpy(0xac30b000, 0xb57c5000, 4096)
08-17 10:26:25.824   324  7089 V AudioCache: write(0xb57c5000, 4096)
08-17 10:26:25.824   324  7089 V AudioCache: memcpy(0xac30c000, 0xb57c5000, 4096)
08-17 10:26:25.825   324  7089 V AudioCache: write(0xb57c5000, 4096)
08-17 10:26:25.825   324  7089 V AudioCache: memcpy(0xac30d000, 0xb57c5000, 4096)
08-17 10:26:25.826   324  7089 V AudioCache: write(0xb57c5000, 4096)
08-17 10:26:25.826   324  7089 V AudioCache: memcpy(0xac30e000, 0xb57c5000, 4096)
08-17 10:26:25.826   324  7089 V AudioCache: write(0xb57c5000, 4096)
08-17 10:26:25.826   324  7089 V AudioCache: memcpy(0xac30f000, 0xb57c5000, 4096)
08-17 10:26:25.827   324  7089 V AudioCache: write(0xb57c5000, 4096)
08-17 10:26:25.827   324  7089 V AudioCache: memcpy(0xac310000, 0xb57c5000, 4096)
08-17 10:26:25.828   324  7089 V AudioCache: write(0xb57c5000, 4096)
08-17 10:26:25.828   324  7089 V AudioCache: memcpy(0xac311000, 0xb57c5000, 4096)
08-17 10:26:25.828   324  7089 V AudioCache: write(0xb57c5000, 4096)
08-17 10:26:25.828   324  7089 V AudioCache: memcpy(0xac312000, 0xb57c5000, 4096)
08-17 10:26:25.829   324  7089 V AudioCache: write(0xb57c5000, 4096)
08-17 10:26:25.829   324  7089 V AudioCache: memcpy(0xac313000, 0xb57c5000, 4096)
08-17 10:26:25.830   324  7089 V AudioCache: write(0xb57c5000, 4096)
08-17 10:26:25.830   324  7089 V AudioCache: memcpy(0xac314000, 0xb57c5000, 4096)
08-17 10:26:25.830   324  7089 V AudioCache: write(0xb57c5000, 4096)
08-17 10:26:25.830   324  7089 V AudioCache: memcpy(0xac315000, 0xb57c5000, 4096)
08-17 10:26:25.831   324  7089 V AudioCache: write(0xb57c5000, 4096)
08-17 10:26:25.831   324  7089 V AudioCache: memcpy(0xac316000, 0xb57c5000, 4096)
08-17 10:26:25.831  7066  7066 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@76c4d71 Instance Count = 1
08-17 10:26:25.832   324  7089 V AudioCache: write(0xb57c5000, 4096)
08-17 10:26:25.832   324  7089 V AudioCache: memcpy(0xac317000, 0xb57c5000, 4096)
08-17 10:26:25.832   324  7089 V AudioCache: write(0xb57c5000, 4096)
08-17 10:26:25.832   324  7089 V AudioCache: memcpy(0xac318000, 0xb57c5000, 4096)
08-17 10:26:25.833   324  7089 V AudioCache: write(0xb57c5000, 4096)
08-17 10:26:25.833   324  7089 V AudioCache: memcpy(0xac319000, 0xb57c5000, 4096)
08-17 10:26:25.834   324  7089 V AudioCache: write(0xb57c5000, 4096)
08-17 10:26:25.834   324  7089 V AudioCache: memcpy(0xac31a000, 0xb57c5000, 4096)
08-17 10:26:25.834   324  7089 V AudioCache: write(0xb57c5000, 4096)
08-17 10:26:25.834   324  7089 V AudioCache: memcpy(0xac31b000, 0xb57c5000, 4096)
08-17 10:26:25.834   324  7089 V AudioCache: write(0xb57c5000, 4096)
08-17 10:26:25.834   324  7089 V AudioCache: memcpy(0xac31c000, 0xb57c5000, 4096)
08-17 10:26:25.834   324  7089 V AudioCache: write(0xb57c5000, 4096)
08-17 10:26:25.834   324  7089 V AudioCache: memcpy(0xac31d000, 0xb57c5000, 4096)
08-17 10:26:25.835   324  7089 V AudioCache: write(0xb57c5000, 4096)
08-17 10:26:25.835   324  7089 V AudioCache: memcpy(0xac31e000, 0xb57c5000, 4096)
08-17 10:26:25.835   324  7089 V AudioCache: write(0xb57c5000, 4096)
08-17 10:26:25.835   324  7089 V AudioCache: memcpy(0xac31f000, 0xb57c5000, 4096)
,08-17 10:26:25.837   324  7089 V AudioCache: write(0xb57c5000, 4096)
08-17 10:26:25.837   324  7089 V AudioCache: memcpy(0xac320000, 0xb57c5000, 4096)
08-17 10:26:25.837   324  7089 V AudioCache: write(0xb57c5000, 4096)
08-17 10:26:25.837   324  7089 V AudioCache: memcpy(0xac321000, 0xb57c5000, 4096)
08-17 10:26:25.837   324  7089 V AudioCache: write(0xb57c5000, 4096)
08-17 10:26:25.837   324  7089 V AudioCache: memcpy(0xac322000, 0xb57c5000, 4096)
08-17 10:26:25.838   324  7089 V AudioCache: write(0xb57c5000, 4096)
08-17 10:26:25.838   324  7089 V AudioCache: memcpy(0xac323000, 0xb57c5000, 4096)
08-17 10:26:25.839   324  7089 V AudioCache: write(0xb57c5000, 4096)
08-17 10:26:25.839   324  7089 V AudioCache: memcpy(0xac324000, 0xb57c5000, 4096)
08-17 10:26:25.839   324  7089 V AudioCache: write(0xb57c5000, 4096)
08-17 10:26:25.839   324  7089 V AudioCache: memcpy(0xac325000, 0xb57c5000, 4096)
08-17 10:26:25.840   324  7089 V AudioCache: write(0xb57c5000, 4096)
08-17 10:26:25.840   324  7089 V AudioCache: memcpy(0xac326000, 0xb57c5000, 4096)
08-17 10:26:25.840  7066  7066 D BluetoothAdapterApp: onCreate
,08-17 10:26:25.840   324  7089 V AudioCache: write(0xb57c5000, 4096)
08-17 10:26:25.840   324  7089 V AudioCache: memcpy(0xac327000, 0xb57c5000, 4096)
08-17 10:26:25.841   324  7089 V AudioCache: write(0xb57c5000, 4096)
08-17 10:26:25.841   324  7089 V AudioCache: memcpy(0xac328000, 0xb57c5000, 4096)
08-17 10:26:25.841   324  7089 V AudioCache: write(0xb57c5000, 4096)
08-17 10:26:25.841   324  7089 V AudioCache: memcpy(0xac329000, 0xb57c5000, 4096)
08-17 10:26:25.842   324  7089 V AudioCache: write(0xb57c5000, 4096)
08-17 10:26:25.842   324  7089 V AudioCache: memcpy(0xac32a000, 0xb57c5000, 4096)
08-17 10:26:25.842   324  7089 V AudioCache: write(0xb57c5000, 4096)
08-17 10:26:25.842   324  7089 V AudioCache: memcpy(0xac32b000, 0xb57c5000, 4096)
08-17 10:26:25.843   324  7089 V AudioCache: write(0xb57c5000, 4096)
08-17 10:26:25.843   324  7089 V AudioCache: memcpy(0xac32c000, 0xb57c5000, 4096)
08-17 10:26:25.843   324  7089 V AudioCache: write(0xb57c5000, 4096)
08-17 10:26:25.843   324  7089 V AudioCache: memcpy(0xac32d000, 0xb57c5000, 4096)
08-17 10:26:25.843   324  7089 V AudioCache: write(0xb57c5000, 4096)
08-17 10:26:25.843   324  7089 V AudioCache: memcpy(0xac32e000, 0xb57c5000, 4096)
08-17 10:26:25.844   324  7089 V AudioCache: write(0xb57c5000, 4096)
08-17 10:26:25.844   324  7089 V AudioCache: memcpy(0xac32f000, 0xb57c5000, 4096)
08-17 10:26:25.844   324  7089 V AudioCache: write(0xb57c5000, 4096)
08-17 10:26:25.844   324  7089 V AudioCache: memcpy(0xac330000, 0xb57c5000, 4096)
08-17 10:26:25.845   324  7089 V AudioCache: write(0xb57c5000, 4096)
08-17 10:26:25.845   324  7089 V AudioCache: memcpy(0xac331000, 0xb57c5000, 4096)
08-17 10:26:25.845   324  7088 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-17 10:26:25.845   324  7089 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-17 10:26:25.845   324  7089 V AwesomePlayer: postAudioEOS() 
08-17 10:26:25.845   324  7089 V AudioCache: write(0xb57c5000, 280)
08-17 10:26:25.845   324  7089 V AudioCache: memcpy(0xac332000, 0xb57c5000, 280)
08-17 10:26:25.847   324  7086 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-17 10:26:25.847   324  7086 V AwesomePlayer: onStreamDone
08-17 10:26:25.847   324  7086 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-17 10:26:25.847   324  7086 V AudioCache: notify(0xb5474dc0, 2, 0, 0)
08-17 10:26:25.847   324  7086 V AudioCache: playback complete
08-17 10:26:25.847   324  7086 V AwesomePlayer: pause_l() 
08-17 10:26:25.847   324  7086 V AudioCache: notify(0xb5474dc0, 7, 0, 0)
08-17 10:26:25.847   324  7086 V AudioCache: ignored
08-17 10:26:25.847   324  7086 V AwesomePlayer: cancelPlayerEvents
08-17 10:26:25.847   324  4037 V AudioCache: wait - success
08-17 10:26:25.847   324  4037 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-17 10:26:25.847   324  7086 D AudioPlayer: Pause Playback at 1068125
08-17 10:26:25.847   324  4037 V AwesomePlayer: reset_l() 
08-17 10:26:25.847   324  4037 V AudioCache: notify(0xb5474dc0, 8, 0, 0)
08-17 10:26:25.847   324  4037 V AudioCache: ignored
08-17 10:26:25.847   324  4037 V AwesomePlayer: cancelPlayerEvents
08-17 10:26:25.847   324  4037 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-17 10:26:25.847   324  4037 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-17 10:26:25.847   324  4037 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-17 10:26:25.847   324  4037 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-17 10:26:25.847   324  4037 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-17 10:26:25.848   324  7088 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-17 10:26:25.848   324  7088 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-17 10:26:25.849   324  7088 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-17 10:26:25.849   324  7088 V OMXCodec: [OMX.google.vorbis.decoder] freeing ,buffer 0xb040fa60 on port 0
08-17 10:26:25.849   324  7088 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-17 10:26:25.849   324  7088 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fa10 on port 0
08-17 10:26:25.849   324  7088 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-17 10:26:25.849   324  7088 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f9c0 on port 0
08-17 10:26:25.849   324  7088 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-17 10:26:25.849   324  7088 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f970 on port 0
08-17 10:26:25.849   324  7088 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-17 10:26:25.850   324  7088 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-17 10:26:25.850   324  7088 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb17ff420 on port 1
08-17 10:26:25.850   324  7088 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-17 10:26:25.850   324  7088 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fab0 on port 1
08-17 10:26:25.850   324  7088 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-17 10:26:25.850   324  7088 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fb50 on port 1
08-17 10:26:25.850   324  7088 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-17 10:26:25.850   324  7088 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fc40 on port 1
08-17 10:26:25.850   324  7088 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-17 10:26:25.850   324  7088 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-17 10:26:25.850   324  4037 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-17 10:26:25.850   324  4037 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-17 10:26:25.850   324  7088 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-17 10:26:25.850   324  7088 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-17 10:26:25.850   324  7088 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-17 10:26:25.850   324  4037 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-17 10:26:25.850   324  4037 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-17 10:26:25.850   324  4037 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-17 10:26:25.851   324  4037 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-17 10:26:25.851   324  4037 D AudioPlayer: AudioPlayer releasing audio source
08-17 10:26:25.851   324  4037 D AudioPlayer: AudioPlayer done releasing audio source
08-17 10:26:25.851   324  4037 V AwesomePlayer: reset_l() 
08-17 10:26:25.851   324  4037 V AwesomePlayer: cancelPlayerEvents
08-17 10:26:25.851   324  4037 V AwesomePlayer: ~AwesomePlayer call
08-17 10:26:25.851   324  4037 V AwesomePlayer: reset_l() 
08-17 10:26:25.851   324  4037 V AwesomePlayer: cancelPlayerEvents
,08-17 10:26:25.851  6996  7085 V SoundPool: close(31)
08-17 10:26:25.851  6996  7085 V SoundPool: pointer = 0x9fe63000, size = 205080, sampleRate = 48000, numChannels = 2
08-17 10:26:25.860  7066  7066 D ProfileConfigQcom: [BTUI] HeadsetService is supported
,08-17 10:26:25.860  7066  7066 D ProfileConfigQcom: Adding HeadsetService
08-17 10:26:25.861  7066  7066 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-17 10:26:25.861  7066  7066 D ProfileConfigQcom: Adding A2dpService
08-17 10:26:25.861  7066  7066 D ProfileConfigQcom: [BTUI] HidService is supported
08-17 10:26:25.861  7066  7066 D ProfileConfigQcom: Adding HidService
08-17 10:26:25.861  7066  7066 D ProfileConfigQcom: [BTUI] HealthService is supported
08-17 10:26:25.861  7066  7066 D ProfileConfigQcom: Adding HealthService
08-17 10:26:25.861  7066  7066 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-17 10:26:25.863  7066  7066 D ProfileConfigQcom: [BTUI] PanService is supported
08-17 10:26:25.863  7066  7066 D ProfileConfigQcom: Adding PanService
08-17 10:26:25.863  7066  7066 D ProfileConfigQcom: [BTUI] GattService is supported
08-17 10:26:25.863  7066  7066 D ProfileConfigQcom: Adding GattService
08-17 10:26:25.863  7066  7066 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-17 10:26:25.863  7066  7066 D ProfileConfigQcom: Adding BluetoothMapService
08-17 10:26:25.864  7066  7066 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-17 10:26:25.865  7066  7066 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-17 10:26:25.869  6934  6934 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-17 10:26:25.870  7066  7066 V LGMDMManagerInternal: Create singleton instance
08-17 10:26:25.878  6996  6996 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,08-17 10:26:25.881  6996  6996 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-17 10:26:25.884  6996  6996 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:1484
08-17 10:26:25.922  7066  7066 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-17 10:26:25.927  7066  7066 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-17 10:26:25.927  7066  7066 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-17 10:26:25.927  7066  7066 V BluetoothSapReceiver: SapReceiver onReceive 
08-17 10:26:25.928  7066  7066 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-17 10:26:25.928  7066  7066 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-17 10:26:25.936  7015  7015 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-17 10:26:26.068  6694  6694 I UEI.SmartControl: Supports setup maps: true
,08-17 10:26:26.071  6694  6694 D UEI.SmartControl: QS start statue = true Error code = 0
,08-17 10:26:26.071  6694  6694 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-17 10:26:26.071  6694  6694 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-17 10:26:26.071  6694  6694 I UEI.SmartControl: ### init IR Blaster...
08-17 10:26:26.074  6694  6694 D serial_port: Configuring serial port
,08-17 10:26:26.075  6694  6694 E UEI.SmartControl: UEIBLaster setting for 616
08-17 10:26:26.075  6694  6694 I UEI.SmartControl: Setting serial record hearder size = 2
08-17 10:26:26.075  6694  6694 I UEI.SmartControl: configuring settings for MAXQ616
08-17 10:26:26.075  6694  6694 I UEI.SmartControl: Get version...
08-17 10:26:26.093  6694  7092 D UEI.SmartControl: serial port data available: 21
,08-17 10:26:26.120  6694  6694 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-17 10:26:26.120  6694  6694 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-17 10:26:26.120  6694  6694 I UEI.SmartControl: QS saving settings...
,08-17 10:26:26.122  6694  6694 D UEI.SmartControl: IR Blaster version: 25672567
08-17 10:26:26.139  6694  7092 D UEI.SmartControl: serial port data available: 4
,08-17 10:26:26.172  6694  7098 I UEI.SmartControl: Device manager: loading config....
08-17 10:26:26.173  6694  7098 D UEI.SmartControl: ----------- loading internal config...
,08-17 10:26:26.182  6694  6694 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-17 10:26:26.184  6694  6694 E UEI.SmartControl: Services init done
08-17 10:26:26.184  6694  6694 D UEI.SmartControl: QS Service init finished
08-17 10:26:26.185  6694  7098 E UEI.SmartControl: Loading SETTINGS...
08-17 10:26:26.187  6694  6694 D UEI.SmartControl: QS Service version name: 2.1.91
08-17 10:26:26.187  6694  6694 D UEI.SmartControl: QS Service version code: 201091
08-17 10:26:26.188  6694  6694 D UEI.SmartControl: Service requested: Control
08-17 10:26:26.190  6694  6694 D UEI.SmartControl: Internal service binding...
,08-17 10:26:26.192  6996  6996 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-17 10:26:26.193  6694  6710 I UEI.SmartControl: ------ IControl API: 11
08-17 10:26:26.193  6694  6710 D UEI.SmartControl: File observer start...
08-17 10:26:26.194  6694  6710 E UEI.SmartControl: IR Port is disabled: false
08-17 10:26:26.194  6694  6710 D UEI.SmartControl: Starting file observer...
08-17 10:26:26.194  6694  6710 I UEI.SmartControl: Registering callback...
08-17 10:26:26.195  6694  6709 I UEI.SmartControl: ------ IControl API: 19
08-17 10:26:26.195  6694  7098 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-17 10:26:26.196  6694  6709 I UEI.SmartControl: Registering Services Ready callback...
08-17 10:26:26.213  6694  7097 I UEI.SmartControl: Notify AllClients services are ready: 0
,08-17 10:26:26.214  6996  7011 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
,08-17 10:26:26.215  6996  7083 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-17 10:26:26.216  6996  7083 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-17 10:26:26.216  6694  7097 D UEI.SmartControl: -----service ready thread exits
08-17 10:26:26.217  6996  6996 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-17 10:26:26.217  6996  6996 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-17 10:26:26.217  6694  6710 I UEI.SmartControl: ------ IControl API: 8
08-17 10:26:26.219  6996  6996 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-17 10:26:26.219  6996  6996 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-17 10:26:26.219  6996  6996 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-17 10:26:26.220  6996  6996 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-17 10:26:26.221  6996  6996 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-17 10:26:26.221  6996  6996 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-17 10:26:26.222  6996  6996 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-17 10:26:26.228  6996  6996 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-17 10:26:26.229  6996  6996 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,08-17 10:26:26.232  6996  6996 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-17 10:26:26.233  6996  6996 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-17 10:26:26.234  6996  6996 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-17 10:26:26.236  6996  6996 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-17 10:26:26.237  6996  6996 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-17 10:26:26.239  6996  6996 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1471422386238]
08-17 10:26:26.241  6996  6996 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
,08-17 10:26:26.245  1037  1578 I ActivityManager: Killing 6526:com.lge.email/u0a23 (adj 15): empty #17
08-17 10:26:26.271  6996  7103 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-17 10:26:26.289  1037  1578 I ActivityManager: Killing 6029:com.android.contacts/u0a19 (adj 15): empty #18
,08-17 10:26:26.317  1037  1999 W libprocessgroup: failed to open /acct/uid_10023/pid_6526/cgroup.procs: No such file or directory
,08-17 10:26:26.323  1037  1658 W libprocessgroup: failed to open /acct/uid_10019/pid_6029/cgroup.procs: No such file or directory
08-17 10:26:26.328  6996  6996 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-17 10:26:26.329  6996  6996 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-17 10:26:26.330  6996  6996 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-17 10:26:26.331  6996  6996 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-17 10:26:26.331  6996  6996 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-17 10:26:26.332  6996  6996 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-17 10:26:26.333  6996  6996 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-17 10:26:26.342  6996  6996 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-17 10:26:27.440  1037  1548 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-17 10:26:27.456  1037  1120 D Tethering: MasterInitialState.processMessage what=3
08-17 10:26:27.469  1037  1097 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-17 10:26:27.475  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:26:27.477  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:26:27.479  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:26:27.481  1037  1548 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-17 10:26:27.483  6446  6446 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-17 10:26:27.489  6446  6933 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-17 10:26:27.499  1037  1120 D Tethering: MasterInitialState.processMessage what=3
,08-17 10:26:27.505  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:26:27.506  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:26:27.507  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:26:27.515  5293  5293 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-17 10:26:27.526  5293  5293 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-17 10:26:27.542  2249  2249 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-17 10:26:27.619  1037  1578 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7107 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-17 10:26:27.623  1037  1097 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-17 10:26:27.625  1037  1097 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 10:26:27.625  1037  1097 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-17 10:26:27.696  7107  7107 I AppUp4:AppBoxCP: onCreate
08-17 10:26:27.697  7107  7107 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,08-17 10:26:27.710  7107  7107 I AppUp4:DB:  setFingerPrint start
08-17 10:26:27.711  7107  7107 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-17 10:26:27.719  7107  7107 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-17 10:26:27.719  7107  7107 I AppUp4:DB:  SDK version = 21
08-17 10:26:27.719  7107  7107 I AppUp4:DB:  beforefinger == newfinger no write in DB
,08-17 10:26:27.721  7107  7107 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-17 10:26:27.723  7107  7107 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-17 10:26:27.723  7107  7107 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-17 10:26:27.726  7107  7107 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-17 10:26:27.726  7107  7107 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-17 10:26:27.733  7107  7107 I AppUp4:CustModeStarterReceiver: onReceive
,08-17 10:26:27.775  7107  7107 D LgDataFeature: LgDataFeature() Constructor: none
,08-17 10:26:27.775  7107  7107 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-17 10:26:27.783  7107  7107 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@38e3d673
,08-17 10:26:27.783  7107  7107 D AppUp4:CustFacade: isCustomizationCompleted : false
08-17 10:26:27.783  7107  7107 D AppUp4:CustFacade: isPhone : true
08-17 10:26:27.784  7107  7107 D AppUp4:CustModeStarterReceiver: begin check event
08-17 10:26:27.785  7107  7107 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-17 10:26:27.786  7107  7107 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-17 10:26:27.787  7107  7140 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-17 10:26:27.787  7107  7140 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-17 10:26:27.788  7107  7140 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
,08-17 10:26:27.792  1037  2028 I ActivityManager: Killing 6052:com.android.gallery3d/u0a27 (adj 15): empty #17
08-17 10:26:27.822  1037  1053 W libprocessgroup: failed to open /acct/uid_10027/pid_6052/cgroup.procs: No such file or directory
,08-17 10:26:27.824  4343  4343 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-17 10:26:27.825  4343  4343 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-17 10:26:27.829  4343  4343 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-17 10:26:27.831  4343  4343 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-17 10:26:27.839  4343  7143 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-17 10:26:27.844  4343  7144 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-17 10:26:27.844  4343  7144 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-17 10:26:27.884  1037  1816 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7145 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-17 10:26:27.983  7145  7145 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-17 10:26:27.984  7145  7145 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-17 10:26:27.986  7145  7145 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-17 10:26:27.986  7145  7145 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-17 10:26:28.097  7145  7145 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-17 10:26:28.114  7145  7145 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-17 10:26:28.167  7145  7145 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-17 10:26:28.205  7145  7145 D LgDataFeature: LgDataFeature() Constructor: none
08-17 10:26:28.205  7145  7145 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-17 10:26:28.330  7145  7145 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-17 10:26:28.363  3438  3438 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-17 10:26:28.363  3438  3438 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-17 10:26:28.363  3438  3438 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-17 10:26:28.412  1037  2113 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7177 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-17 10:26:28.426  7035  7175 W FormManager: Network not available. Please check & try again.
,08-17 10:26:28.434  7145  7145 I HubEmail: JNI_OnLoad()
08-17 10:26:28.434  7145  7145 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-17 10:26:28.434  7145  7145 I HubEmail: registerNatives()
08-17 10:26:28.434  7145  7145 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-17 10:26:28.434  7145  7145 I HubEmail: registerNativeMethods()
08-17 10:26:28.434  7145  7145 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-17 10:26:28.435  7145  7145 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
08-17 10:26:28.436  7035  7176 V FormManager: Network unavailable.
08-17 10:26:28.439  7035  7176 V FormManager: Network unavailable.
08-17 10:26:28.450  1037  1658 I ActivityManager: Killing 6125:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,08-17 10:26:28.474  1037  1054 W libprocessgroup: failed to open /acct/uid_10080/pid_6125/cgroup.procs: No such file or directory
08-17 10:26:28.479  7145  7194 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 10:26:28.537  7177  7177 D LgDataFeature: LgDataFeature() Constructor: none
08-17 10:26:28.537  7177  7177 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-17 10:26:28.540  7177  7177 D PhoneMonitor: Register our PhoneStateListener
08-17 10:26:28.562  7177  7177 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-17 10:26:28.564  7177  7177 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-17 10:26:28.577  7177  7177 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,08-17 10:26:28.579  7177  7177 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-17 10:26:28.581  7177  7177 D TelephonyAutoProfiling: [parse] Load xml
08-17 10:26:28.584  7177  7177 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-17 10:26:28.584  7177  7177 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-17 10:26:28.584  7177  7177 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-17 10:26:28.584  7177  7177 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-17 10:26:28.584  7177  7177 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-17 10:26:28.584  7177  7177 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-17 10:26:28.584  7177  7177 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-17 10:26:28.584  7177  7177 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-17 10:26:28.584  7177  7177 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-17 10:26:28.585  7177  7177 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-17 10:26:28.585  7177  7177 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-17 10:26:28.585  7177  7177 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-17 10:26:28.585  7177  7177 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-17 10:26:28.585  7177  7177 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-17 10:26:28.585  7177  7177 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-17 10:26:28.585  7177  7177 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-17 10:26:28.585  7177  7177 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-17 10:26:28.597  7177  7177 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-17 10:26:28.617  1037  2044 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7197 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-17 10:26:28.617  1037  2044 I ActivityManager: Killing 6566:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,08-17 10:26:28.691  1037  1740 W libprocessgroup: failed to open /acct/uid_10061/pid_6566/cgroup.procs: No such file or directory
,08-17 10:26:28.946  1037  1740 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7223 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,08-17 10:26:28.951  1037  1740 I ActivityManager: Killing 6162:com.google.android.apps.plus/u0a97 (adj 15): empty #17
08-17 10:26:29.007  1037  1985 W libprocessgroup: failed to open /acct/uid_10097/pid_6162/cgroup.procs: No such file or directory
,08-17 10:26:29.126  1037  1983 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7240 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-17 10:26:29.132  1037  1983 I ActivityManager: Killing 6643:com.lge.eula/1000 (adj 15): empty #17
08-17 10:26:29.179  1037  1740 W libprocessgroup: failed to open /acct/uid_1000/pid_6643/cgroup.procs: No such file or directory
,08-17 10:26:29.219  7240  7240 I art     : Almond Protected OAT
,08-17 10:26:29.272  7240  7240 D WeatherApplication: removeAccount
,08-17 10:26:29.273  7240  7240 D WeatherApplication: Account.length = 0
08-17 10:26:29.274  7240  7240 E WeatherApplication: OPERATOR:OPEN
08-17 10:26:29.281  1037  1054 D WifiServiceImplEx: setWifiEnabled: true pid=6772, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-17 10:26:29.281  1037  1054 D WifiService: setWifiEnabled: true pid=6772, uid=10118
08-17 10:26:29.281  1037  1054 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-17 10:26:29.281  7240  7240 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:26:29
08-17 10:26:29.286  7240  7240 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,08-17 10:26:29.287  7240  7240 D Weather.Utils: 2 : All the weather widget is gone.
08-17 10:26:29.291  7240  7240 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-17 10:26:29.294  7240  7240 D WeatherAncestor: connectivity changed - connection : true
08-17 10:26:29.295  7240  7240 D WeatherService: 2 : isServiceAlived():false forecastCache:null
08-17 10:26:29.298  1037  1540 D LGWifiP2pService: P2pDisabledState{ when=-5ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-17 10:26:29.298  1037  1540 D LGWifiP2pService: DefaultState{ when=-5ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-17 10:26:29.299  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-17 10:26:29.299  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-17 10:26:29.299  1037  1037 D Ulp_jni : JNI:system_update. Event-4
08-17 10:26:29.300  1037  1541 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-17 10:26:29.300  1037  1541 I LGFTMITEM: [GET_FTM][id=6], offset=12288
,08-17 10:26:29.302  1037  1541 E WifiUtil: wfc_util_ffile_check_copy(): pid[1037] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-17 10:26:29.302  1037  1541 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-17 10:26:29.302  1037  1541 E WifiUtil: wfc_util_ffile_check_copy(): pid[1037] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-17 10:26:29.302  1037  1541 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-17 10:26:29.302  1037  1541 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-17 10:26:29.303  1037  1541 E WifiHW  : unknown target_country: EU , set to default
08-17 10:26:29.303  1037  1541 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-17 10:26:29.303  1037  1541 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-17 10:26:29.303  1037  1541 I WifiUtil: gEnableBmps=1
08-17 10:26:29.307  7240  7240 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-17 10:26:29.307  7240  7240 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-17 10:26:29.308  7240  7240 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
08-17 10:26:29.333  7240  7240 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-17 10:26:29.333  7240  7240 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:26:29
,08-17 10:26:29.373  1037  1963 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7259 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-17 10:26:29.376  1037  1963 I ActivityManager: Killing 6663:com.lge.bnr/1000 (adj 15): empty #17
08-17 10:26:29.429  1037  1983 W libprocessgroup: failed to open /acct/uid_1000/pid_6663/cgroup.procs: No such file or directory
,08-17 10:26:29.546   278   352 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-17 10:26:29.546   278   352 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-17 10:26:29.546   278   352 W Vold    : Returning OperationFailed - no handler for errno 0
08-17 10:26:29.546  7259  7281 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-17 10:26:29.548   278   352 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-17 10:26:29.548   278   352 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-17 10:26:29.548   278   352 W Vold    : Returning OperationFailed - no handler for errno 0
08-17 10:26:29.548  7259  7281 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,08-17 10:26:29.558   278   352 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-17 10:26:29.558   278   352 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-17 10:26:29.558   278   352 W Vold    : Returning OperationFailed - no handler for errno 0
08-17 10:26:29.559  7259  7283 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-17 10:26:29.570   278   352 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,08-17 10:26:29.570   278   352 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-17 10:26:29.570   278   352 W Vold    : Returning OperationFailed - no handler for errno 0
,08-17 10:26:29.573  7259  7283 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-17 10:26:29.814  7259  7259 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-17 10:26:29.825  7259  7259 I LibraryLoader: Loading: webviewchromium
08-17 10:26:29.829  7259  7259 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 7006-7011)
08-17 10:26:29.830  7259  7259 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-17 10:26:29.836  7259  7259 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {c9c408c}
08-17 10:26:29.837  7259  7259 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-17 10:26:29.838  7259  7259 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-17 10:26:29.853  7259  7259 I BrowserStartupController: Initializing chromium process, renderers=0
08-17 10:26:29.854  7259  7259 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-17 10:26:29.876   324  1389 V AudioPolicyService: registerClient() client 0xb1021ba0, uid 10093
08-17 10:26:29.876  7259  7259 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-17 10:26:29.877  7259  7313 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-17 10:26:29.878  7259  7259 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-17 10:26:29.879  7259  7259 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-17 10:26:29.901  7259  7259 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-17 10:26:29.901  7259  7259 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-17 10:26:29.901  7259  7259 I Adreno-EGL: Build Date: 12/12/14 금
08-17 10:26:29.901  7259  7259 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-17 10:26:29.901  7259  7259 I Adreno-EGL: Remote Branch: 
08-17 10:26:29.901  7259  7259 I Adreno-EGL: Local Patches: 
08-17 10:26:29.901  7259  7259 I Adreno-EGL: Reconstruct Branch: 
,08-17 10:26:29.986  7259  7259 I NSApplication: Starting up...
,08-17 10:26:30.012   320   896 D SoftapController: Softap fwReload - Ok
,08-17 10:26:30.013  1037  1541 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (706ms)
08-17 10:26:30.023   320   896 D CommandListener: Setting iface cfg
08-17 10:26:30.023   320   896 D CommandListener: Trying to bring down wlan0
08-17 10:26:30.023   320   896 D CommandListener: Clearing all IP addresses on wlan0
08-17 10:26:30.025  1037  1541 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-17 10:26:30.029  1037  1541 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-17 10:26:30.029  1037  1541 E WifiStateMachine: useWiFiOffloading() : false
08-17 10:26:30.029  1037  1541 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-17 10:26:30.019  7327  7327 W wpa_supplicant: type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 10:26:30.019  7327  7327 W wpa_supplicant: type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 10:26:30.059  7327  7327 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-17 10:26:30.064  1037  1054 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7328 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-17 10:26:30.066  1037  1053 I ActivityManager: Killing 6074:com.android.vending/u0a44 (adj 15): empty #17
08-17 10:26:30.089   344   344 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 444us total 29.594ms
,08-17 10:26:30.112  7327  7327 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-17 10:26:30.112   344   344 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 410us total 19.646ms
08-17 10:26:30.112  7327  7327 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-17 10:26:30.134   344   344 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 410us total 20.720ms
,08-17 10:26:30.171  7327  7327 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-17 10:26:30.180  1037  1120 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-17 10:26:30.180  1037  1120 D Tethering: InitialState.processMessage what=4
08-17 10:26:30.180  1037  1541 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-17 10:26:30.180  1037  1541 D WifiMonitor: connecting to supplicant
08-17 10:26:30.180  1037  1120 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-17 10:26:30.182  1037  2044 W libprocessgroup: failed to open /acct/uid_10044/pid_6074/cgroup.procs: No such file or directory
,08-17 10:26:30.191  7327  7327 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
08-17 10:26:30.198  1037  1541 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
,08-17 10:26:30.198  1037  1541 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-17 10:26:30.199  1037  1541 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-17 10:26:30.199  1037  1541 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-17 10:26:30.200  1037  1541 E WifiStateMachine:  SupplicantStartingState CMD_STOP_SUPPLICANT_FAILED 1 0
08-17 10:26:30.200  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 10:26:30.200  1037  1541 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
08-17 10:26:30.200  1970  1970 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-17 10:26:30.201  1037  1541 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-17 10:26:30.201  1037  1541 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-17 10:26:30.204  1037  1541 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-17 10:26:30.204  1037  1541 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-17 10:26:30.204  1037  1541 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-17 10:26:30.205  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
,08-17 10:26:30.205  6772  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 10:26:30.205  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:26:30.205  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:26:30.205  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 10:26:30.205  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 10:26:30.205  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 10:26:30.205  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 10:26:30.205  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 10:26:30.205  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 10:26:30.205  6772  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 10:26:30.206  6772  6772 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-17 10:26:30.206  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 10:26:30.206  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 10:26:30.206  6772  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 10:26:30.207  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:26:30.207  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:26:30.207  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 10:26:30.207  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 10:26:30.207  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 10:26:30.207  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 10:26:30.207  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 10:26:30.207  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 10:26:30.207  6772  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 10:26:30.207  6772  6772 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-17 10:26:30.207  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 10:26:30.207  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 10:26:30.207  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-17 10:26:30.207  1037  1541 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-17 10:26:30.207  1037  1541 E WifiStateMachine: useWiFiOffloading() : false
08-17 10:26:30.207  1037  1541 E WifiState,Machine: CONFIG_LGE_WLAN_PATH : true
08-17 10:26:30.208  1037  1541 D WifiNative-wlan0: doBoolean: SET update_config 1
08-17 10:26:30.209  6772  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 10:26:30.209  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:26:30.209  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:26:30.209  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 10:26:30.209  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 10:26:30.209  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 10:26:30.209  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 10:26:30.209  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 10:26:30.209  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 10:26:30.209  6772  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 10:26:30.209  1037  1541 D WifiNative-wlan0: SET update_config 1: returned true
08-17 10:26:30.209  6772  6772 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-17 10:26:30.209  1037  1541 D WifiConfigStore: Loading config and enabling all networks 
08-17 10:26:30.209  1037  1541 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-17 10:26:30.210  1037  1541 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-17 10:26:30.211  1970  1970 D WfdService: Waiting for WifiP2p enabling
08-17 10:26:30.212  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-17 10:26:30.212  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:26:30.212  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:26:30.213  1037  1546 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-17 10:26:30.213  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:26:30.215  7327  7327 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-17 10:26:30.215  1037  7351 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-17 10:26:30.216  1037  7351 D WifiMonitor: Dropping event because (p2p0) is stopped
,08-17 10:26:30.221  1037  1541 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-17 10:26:30.222  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 10:26:30.231  1037  1541 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
,08-17 10:26:30.232  1037  1541 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-17 10:26:30.232  1037  1541 D WifiStateMachine: enableVerboseLogging : level 2
08-17 10:26:30.233  1037  1541 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-17 10:26:30.233  1037  1541 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-17 10:26:30.233  1037  1541 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-17 10:26:30.233  1037  1541 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-17 10:26:30.233  1037  1541 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-17 10:26:30.234  1037  1541 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-17 10:26:30.234  1037  1541 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-17 10:26:30.234  1037  1541 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-17 10:26:30.234  1037  1541 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-17 10:26:30.235  1037  1541 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-17 10:26:30.235  1037  1541 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-17 10:26:30.235  1037  1541 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-17 10:26:30.236  1037  1541 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-17 10:26:30.236  1037  1541 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-17 10:26:30.236  1037  1541 D WifiStateMachine: Setting OUI to DA-A1-19
,08-17 10:26:30.237  1037  1541 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-17 10:26:30.237  1970  1970 D WfdsService: Supplicant Connection state is changed : true
08-17 10:26:30.237  7328  7328 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-17 10:26:30.237  1970  2334 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-17 10:26:30.237  1970  2334 D WfdsService: Set the WFDS Monitor: true
08-17 10:26:30.237  1970  2334 D WfdsMonitor: WfdsMonitorThread create
08-17 10:26:30.237  1970  2334 D WfdsMonitor: WFDS Monitor is created and started
08-17 10:26:30.237  1970  2334 D WfdsService: WiFi: Supplicant connection re-established
08-17 10:26:30.237  1037  1541 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-17 10:26:30.238  1037  1541 D WifiNative-HAL: Setting external_sim to 1
08-17 10:26:30.238  1037  1541 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-17 10:26:30.238  1970  7352 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-17 10:26:30.238  1037  1541 D WifiNative-wlan0: SET external_sim 1: returned true
08-17 10:26:30.238  1037  1541 I WifiNative-HAL: startHal
08-17 10:26:30.239  1037  1541 D wifi    : setting scan oui 0xaf653660
08-17 10:26:30.239  1970  7352 E CtrlSupplicant: Succeed to open control connection
08-17 10:26:30.239  1037  1541 D WifiStateMachine: Setting OUI to DA-A1-19
08-17 10:26:30.239  1970  7352 E CtrlSupplicant: Succeed to open monitor connection
08-17 10:26:30.239  1037  1541 I WifiNative-HAL: startHal
08-17 10:26:30.239  1037  7351 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-17 10:26:30.240  1037  7351 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-17 10:26:30.240  7327  7327 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-17 10:26:30.240  1037  1541 D wifi    : setting scan oui 0xaf653660
,08-17 10:26:30.240  1970  7352 D WfdsMonitor: Supplicant connection established
08-17 10:26:30.240  1037  7351 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-17 10:26:30.240  1037  7351 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-17 10:26:30.240  1037  1541 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-17 10:26:30.240  1037  7351 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-17 10:26:30.240  1037  7351 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-17 10:26:30.241  1037  1541 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-17 10:26:30.241  1037  1541 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-17 10:26:30.241  1970  2334 D WfdsService: Connected to the supplicant for wfds
08-17 10:26:30.241  7327  7327 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-17 10:26:30.241  1037  1541 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-17 10:26:30.241  1037  1541 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-17 10:26:30.242  7327  7327 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-17 10:26:30.242  1037  1541 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-17 10:26:30.242  1037  1541 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-17 10:26:30.242  7327  7327 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-17 10:26:30.243  1037  1541 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-17 10:26:30.243  1037  1541 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-17 10:26:30.243  7327  7327 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-17 10:26:30.243  1037  1541 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-17 10:26:30.243  1037  1541 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-17 10:26:30.244  7327  7327 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-17 10:26:30.244  1037  1541 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-17 10:26:30.244  1037  1541 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-17 10:26:30.244  7327  7327 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
,08-17 10:26:30.245  1037  1541 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-17 10:26:30.245  1037  1541 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-17 10:26:30.245  7327  7327 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-17 10:26:30.245  1037  1541 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-17 10:26:30.246  1037  1541 E WifiNative: : [367,415,133 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-17 10:26:30.246  1037  1541 D WifiNative-wlan0: doBoolean: RECONNECT
08-17 10:26:30.246  1037  1541 D WifiNative-wlan0: RECONNECT: returned true
08-17 10:26:30.246  1037  1541 D WifiNative-wlan0: doString: [STATUS]
08-17 10:26:30.247  1037  7351 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-17 10:26:30.247  1037  7351 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-17 10:26:30.248  1037  1541 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-17 10:26:30.248  1037  1541 D WifiNative-wlan0: doBoolean: SET ps 1
08-17 10:26:30.249  1037  1541 D WifiNative-wlan0: SET ps 1: returned true
08-17 10:26:30.249  1037  1540 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
,08-17 10:26:30.251   320   896 D CommandListener: Setting iface cfg
08-17 10:26:30.251   320   896 D CommandListener: Trying to bring up p2p0
08-17 10:26:30.251  1037  1540 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-17 10:26:30.252  1037  1037 D WifiScanningService: SCAN_AVAILABLE : 3
08-17 10:26:30.252  1037  1540 D LGWifiP2pService: P2pEnablingState
08-17 10:26:30.252  1037  1540 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-17 10:26:30.252  1037  1037 D RttService: SCAN_AVAILABLE : 3
08-17 10:26:30.252  1037  1540 D LGWifiP2pService: P2p socket connection successful
,08-17 10:26:30.252  1037  1540 D LGWifiP2pService: P2pEnabledState
08-17 10:26:30.252  1037  1560 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-17 10:26:30.252  1037  1559 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-17 10:26:30.252  1037  1559 I WifiNative-HAL: startHal
08-17 10:26:30.252  1037  1559 D wifi    : getting scan capabilities on interface[1] = 0xaf653660
08-17 10:26:30.253  1037  1559 D wifi    : failed to get capabilities : -3
08-17 10:26:30.253  1037  1559 E WifiScanningService: could not get scan capabilities
08-17 10:26:30.254  1970  1970 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-17 10:26:30.254  1970  1970 D WfdsService: WifiP2pState is changed : true
08-17 10:26:30.254  1970  2334 D WfdsService: Receive the WFDS_ENABLE Method
08-17 10:26:30.254  1970  2334 D WfdsService: Set the WFDS Monitor: true
08-17 10:26:30.254  1970  2334 D WfdsService: Connected to the supplicant for wfds
08-17 10:26:30.254  1037  1540 D LGWifiP2pService: sending p2p connection changed broadcast
08-17 10:26:30.254  1970  2334 D WfdsJNI : doCommand: WFDS_SET TRUE
08-17 10:26:30.255  7327  7327 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-17 10:26:30.255  1970  2334 D WfdsService: selectPreferredScanChannel [36]
08-17 10:26:30.255  1970  2334 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-17 10:26:30.255  1037  1541 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-17 10:26:30.256  1037  1540 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-17 10:26:30.256  1037  1541 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-17 10:26:30.256  1037  1540 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-17 10:26:30.256  1037  1540 D WifiNative-p2p0: doBoolean: SET device_name G3
08-17 10:26:30.256  1037  1541 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-17 10:26:30.257  1037  1540 D WifiNative-p2p0: SET device_name G3: returned true
08-17 10:26:30.257  1037  1540 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-17 10:26:30.257  1037  1540 D LGWifiP2pService: before postfix = G3
08-17 10:26:30.257  1037  1540 D WifiServerServiceExt: postfix byte check : 2
08-17 10:26:30.257  1037  1540 D LGWifiP2pService: after postfix = G3
08-17 10:26:30.257  1037  1540 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-17 10:26:30.257  1037  1541 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-17 10:26:30.257  1037  1540 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-17 10:26:30.257  1037  1540 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-17 10:26:30.257  1037  1541 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
08-17 10:26:30.258  1970  1970 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-17 10:26:30.258  1037  1541 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-17 10:26:30.258  1037  1541 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-17 10:26:30.258  1970  1970 D WfdsService: isConnected: false
08-17 10:26:30.258  1037  1540 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-17 10:26:30.258  1037  1540 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-17 10:26:30.258  1037  1541 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-17 10:26:30.259  1037  1540 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-17 10:26:30.259  1037  1540 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-17 10:26:30.259  1037  1541 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-17 10:26:30.259  1037  1540 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-17 10:26:30.259  1037  1540 D WifiNative-HAL: p2pGetDeviceAddress
08-17 10:26:30.259  1037  1540 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-17 10:26:30.259  1037  1541 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-17 10:26:30.260  1037  1541 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-17 10:26:30.261  1970  1970 I WfdStateTracker: handleP2pThisDeviceChanged
08-17 10:26:30.261  1970  1970 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-17 10:26:30.261  1970  1970 D WfdsService: Update P2p Interface State: 3
08-17 10:26:30.261  1037  1540 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-17 10:26:30.261  1037  1540 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-17 10:26:30.261  1037  1541 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-17 10:26:30.261  1037  1541 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-17 10:26:30.261  7327  7327 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-17 10:26:30.261  1037  1540 D WifiNative-p2p0: P2P_FLUSH: returned true
08-17 10:26:30.261  1037  1540 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-17 10:26:30.261  1037  1541 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-17 10:26:30.262  1037  1541 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-17 10:26:30.262  1037  1541 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-17 10:26:30.262  1037  1541 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-17 10:26:30.262  7327  7327 E wpa_supplicant: disconnect_rssi_lvl: -100
,08-17 10:26:30.263  1037  1541 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=367433  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,08-17 10:26:30.266  1037  1540 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-17 10:26:30.266  1037  1540 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-17 10:26:30.266  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 10:26:30.267  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 10:26:30.267  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-17 10:26:30.268  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 10:26:30.268  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-17 10:26:30.268  1037  1541 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=367437  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-17 10:26:30.268  1037  1541 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-17 10:26:30.269  1037  1540 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-17 10:26:30.269  1037  1541 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-17 10:26:30.269  1037  1540 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-17 10:26:30.269  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-17 10:26:30.269  1037  1541 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-17 10:26:30.269  1037  1541 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-17 10:26:30.277  1037  1540 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-17 10:26:30.277  1037  1540 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-17 10:26:30.277  1037  1540 D LGWifiP2pService: InactiveState
08-17 10:26:30.278  1037  1540 D LGWifiP2pService: InactiveState{ when=-11ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-17 10:26:30.278  1037  1540 D LGWifiP2pService: P2pEnabledState{ when=-11ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-17 10:26:30.278  1037  1540 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-17 10:26:30.279  7327  7327 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
,08-17 10:26:30.280  7327  7327 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-17 10:26:30.280  1970  7352 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-17 10:26:30.280  1037  7351 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-17 10:26:30.280  1037  7351 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,08-17 10:26:30.281  1037  7351 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-17 10:26:30.281  1037  7351 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-17 10:26:30.281  7327  7327 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-17 10:26:30.281  7327  7327 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 10:26:30.281  1970  7352 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-17 10:26:30.281  1037  7351 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-17 10:26:30.281  1037  1540 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-17 10:26:30.281  1037  7351 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 10:26:30.281  1037  7351 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 10:26:30.281  1037  7351 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,08-17 10:26:30.281  1037  1540 D LGWifiP2pService: InactiveState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-17 10:26:30.281  1037  1540 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-17 10:26:30.281  1037  1540 D LGWifiP2pService: DefaultState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-17 10:26:30.282  1037  1540 D LGWifiP2pService: InactiveState{ when=-4ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-17 10:26:30.282  1037  1540 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-17 10:26:30.282  1037  1540 D LGWifiP2pService: DefaultState{ when=-4ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-17 10:26:30.282  7327  7327 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 10:26:30.282  1970  7352 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-17 10:26:30.282  1037  1540 D LGWifiP2pService: InactiveState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-17 10:26:30.282  1037  7351 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-17 10:26:30.282  1037  1540 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-17 10:26:30.282  1037  7351 E WifiMonitor: WifiMonitor:p2p0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 10:26:30.282  1037  1540 D LGWifiP2pService: DefaultState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-17 10:26:30.282  1037  7351 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 10:26:30.282  1037  7351 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 10:26:30.283  1970  2334 W WfdsService: DefaultState - msg [9441285] is not handled
08-17 10:26:30.284  7327  7327 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-17 10:26:30.284  1037  1540 D LGWifiP2pService: InactiveState{ when=-6ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-17 10:26:30.284  1037  1540 D LGWifiP2pService: P2pEnabledState{ when=-6ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-17 10:26:30.284  1037  1540 D LGWifiP2pService: DefaultState{ when=-6ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-17 10:26:30.284  1037  1037 E WifiServerServiceExt: No p2p device connected
08-17 10:26:30.284  7327  7327 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-17 10:26:30.285  7327  7327 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-17 10:26:30.285  7327  7327 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 10:26:30.285  1970  7352 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-17 10:26:30.286  7327  7327 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 10:26:30.286  1970  7352 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-17 10:26:30.287  1037  7351 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-17 10:26:30.287  1037  7351 E WifiMonitor: WifiMonitor:wlan0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-17 10:26:30.287  1037  7351 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-17 10:26:30.287  1037  7351 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-17 10:26:30.287  1037  7351 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-17 10:26:30.287  1037  7351 E WifiMo,nitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 10:26:30.287  1037  7351 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 10:26:30.287  1037  7351 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 10:26:30.287  1037  7351 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-17 10:26:30.287  1037  7351 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 10:26:30.287  1037  7351 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 10:26:30.287  1037  7351 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 10:26:30.288  1037  1541 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-17 10:26:30.289  1037  1540 D LGWifiP2pService: InactiveState{ when=-1ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-17 10:26:30.289  1037  1540 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-17 10:26:30.289  1037  1541 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-17 10:26:30.289  1037  1541 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-17 10:26:30.289  1037  1541 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-17 10:26:30.290  1037  1541 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-17 10:26:30.290  7327  7327 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-17 10:26:30.290  7327  7327 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-17 10:26:30.291  1037  7351 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-17 10:26:30.291  1037  7351 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-17 10:26:30.291  1037  7351 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-17 10:26:30.291  1037  7351 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-17 10:26:30.291  1037  1541 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-17 10:26:30.291  1037  1541 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-17 10:26:30.292  1037  1541 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-17 10:26:30.292  1037  1541 D WifiNative-wlan0: doBoolean: SCAN
08-17 10:26:30.292  1037  1541 D WifiNative-wlan0: SCAN: returned false
08-17 10:26:30.293  1037  1541 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=367463  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,08-17 10:26:30.295  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 10:26:30.295  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-17 10:26:30.297  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 10:26:30.297  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 10:26:30.297  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 10:26:30.298  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-17 10:26:30.299  1037  1541 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=367468  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-17 10:26:30.299  1037  1541 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-17 10:26:30.299  1037  1541 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-17 10:26:30.300  1037  1541 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-17 10:26:30.300  1037  1541 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-17 10:26:30.301  1037  1541 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-17 10:26:30.302  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-17 10:26:30.302  1037  1037 D WifiServerServiceExt: setSupplicantStateSCANNING
08-17 10:26:30.303  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-17 10:26:30.303  1037  1037 D WifiServerServiceExt: setSupplicantStateSCANNING
,08-17 10:26:30.443  1037  1053 I art     : Explicit concurrent mark sweep GC freed 70612(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 2.279ms total 135.202ms
,08-17 10:26:30.570  6446  6446 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-17 10:26:30.575  6446  6933 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-17 10:26:30.606  2249  2249 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-17 10:26:30.623  7107  7107 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
,08-17 10:26:30.623  7107  7107 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-17 10:26:30.623  7107  7107 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-17 10:26:30.623  7107  7107 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-17 10:26:30.625  7107  7107 I AppUp4:CustModeStarterReceiver: onReceive
,08-17 10:26:30.629  7107  7107 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@38e3d673
08-17 10:26:30.629  7107  7107 D AppUp4:CustFacade: isCustomizationCompleted : false
08-17 10:26:30.629  7107  7107 D AppUp4:CustFacade: isPhone : true
08-17 10:26:30.630  7107  7107 D AppUp4:CustModeStarterReceiver: begin check event
08-17 10:26:30.630  7107  7107 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-17 10:26:30.634  4343  4343 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-17 10:26:30.634  4343  4343 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-17 10:26:30.636  4343  4343 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-17 10:26:30.639  4343  4343 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-17 10:26:30.645  7145  7145 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-17 10:26:30.650  4343  7366 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-17 10:26:30.656  4343  7367 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-17 10:26:30.656  4343  7367 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-17 10:26:30.681  7035  7371 W FormManager: Network not available. Please check & try again.
,08-17 10:26:30.684  7035  7373 V FormManager: Network unavailable.
08-17 10:26:30.689  3438  3438 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-17 10:26:30.690  3438  3438 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-17 10:26:30.690  3438  3438 I LgeMiscReceiver: networkInfo.isConnected() = false
08-17 10:26:30.691  7035  7373 V FormManager: Network unavailable.
08-17 10:26:30.694  7177  7177 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-17 10:26:30.694  7177  7177 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-17 10:26:30.696  7145  7372 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 10:26:30.714  7240  7240 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:26:30
,08-17 10:26:30.717  7240  7240 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-17 10:26:30.717  7240  7240 D Weather.Utils: 2 : All the weather widget is gone.
08-17 10:26:30.718  7240  7240 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-17 10:26:30.718  7240  7240 D WeatherAncestor: connectivity changed - connection : true
08-17 10:26:30.718  7240  7240 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@131639a9
08-17 10:26:30.719  7240  7240 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-17 10:26:30.719  7240  7240 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-17 10:26:30.719  7240  7240 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-17 10:26:30.719  7240  7240 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-17 10:26:30.719  7240  7240 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:26:30
08-17 10:26:30.750  6934  6934 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-17 10:26:30.750  6934  6934 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-17 10:26:30.750  6934  6934 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-17 10:26:30.750  6934  6934 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-17 10:26:30.752  6934  6934 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-17 10:26:30.753  6934  6934 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-17 10:26:30.753  6934  6934 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-17 10:26:30.753  6934  6934 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-17 10:26:30.753  6934  6934 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-17 10:26:30.753  6934  6934 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-17 10:26:30.754  6934  6934 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-17 10:26:30.764  6951  6951 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-17 10:26:30.768  6934  6934 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-17 10:26:30.776  6934  6934 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 10:26:30.792  7035  7377 W FormManager: Network not available. Please check & try again.
,08-17 10:26:30.801  6951  6951 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-17 10:26:30.803  7035  7378 V FormManager: Network unavailable.
08-17 10:26:30.807  6934  6934 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-17 10:26:30.808  7035  7378 V FormManager: Network unavailable.
,08-17 10:26:30.814  6934  6934 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 10:26:30.827  7035  7379 W FormManager: Network not available. Please check & try again.
,08-17 10:26:30.830  4343  4343 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-17 10:26:30.830  4343  4343 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-17 10:26:30.832  7035  7380 V FormManager: Network unavailable.
08-17 10:26:30.832  4343  4343 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-17 10:26:30.835  4343  4343 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-17 10:26:30.835  7035  7380 V FormManager: Network unavailable.
08-17 10:26:30.843  4343  7381 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-17 10:26:30.844  7327  7327 E wpa_supplicant: USIM:  scard_init function
08-17 10:26:30.844  7327  7327 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-17 10:26:30.846  4343  7386 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-17 10:26:30.846  4343  7386 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-17 10:26:30.848  1037  7351 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-17 10:26:30.849  1037  7351 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-17 10:26:30.849  1037  7351 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-17 10:26:30.849  1037  7351 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: WPS-AP-AVAILABLE 
08-17 10:26:30.849  1037  7351 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-17 10:26:30.849  1037  7351 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-17 10:26:30.849  1037  7351 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-17 10:26:30.850  1037  1541 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-17 10:26:30.850  1037  1541 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-17 10:26:30.859  1037  1541 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-17 10:26:30.859  1037  1541 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-17 10:26:30.859  1037  1541 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
,08-17 10:26:30.886  1037  1816 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7388 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-17 10:26:30.893  1037  1541 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=368062  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-17 10:26:30.896  1037  1541 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=368066  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-17 10:26:30.898  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 10:26:30.898  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 10:26:30.898  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 10:26:30.898  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-17 10:26:30.898  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,08-17 10:26:30.900  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-17 10:26:30.901  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-17 10:26:30.901  1037  1037 D WifiServerServiceExt: setSupplicantStateASSOCIATING
,08-17 10:26:30.956  7327  7327 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-17 10:26:30.957  1037  1120 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-17 10:26:30.958  1037  7351 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-17 10:26:30.959  1037  7351 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-17 10:26:30.959  1037  7351 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-17 10:26:30.959  1037  7351 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-17 10:26:30.959  1037  1541 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
08-17 10:26:30.959  1037  7351 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-17 10:26:30.959  1037  7351 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-17 10:26:30.960  1037  1541 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-17 10:26:30.960  1037  1541 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-17 10:26:30.961  1037  1541 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-17 10:26:30.966  1037  1541 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-17 10:26:30.967  1037  1541 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=368136  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-17 10:26:30.968  1037  1541 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=368137  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-17 10:26:30.968  1037  7351 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-17 10:26:30.968  1037  7351 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-17 10:26:30.969  1037  1541 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=368138
08-17 10:26:30.969  7327  7327 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-17 10:26:30.969  1037  1541 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=368139
08-17 10:26:30.969  7327  7327 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-17 10:26:30.969  1037  1541 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=368139
08-17 10:26:30.971  1037  1541 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=368140
,08-17 10:26:30.972  1037  1541 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=368142
08-17 10:26:30.973  1037  1541 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=368142  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-17 10:26:30.973  1037  7351 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-17 10:26:30.973  1037  7351 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-17 10:26:30.974  1037  7351 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-17 10:26:30.974  1037  7351 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-17 10:26:30.974  1037  7351 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-17 10:26:30.974  1037  7351 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-17 10:26:30.975  1037  7351 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-17 10:26:30.975  1037  7351 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-17 10:26:30.977  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 10:26:30.977  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-17 10:26:30.978  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 10:26:30.978  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 10:26:30.978  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-17 10:26:30.978  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 10:26:30.982  1037  1541 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=368151  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
,08-17 10:26:30.983  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 10:26:30.983  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 10:26:30.983  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-17 10:26:30.983  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-17 10:26:30.983  1037  1037 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-17 10:26:30.984  1037  1541 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=368154  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-17 10:26:30.985  1037  1541 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=368154  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-17 10:26:30.985  1037  1541 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=368155
08-17 10:26:30.986  1037  1541 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=368156
08-17 10:26:30.987  1037  1541 D WifiNative-wlan0: doString: [STATUS]
08-17 10:26:30.987  1037  7351 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-17 10:26:30.987  1037  7351 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-17 10:26:30.988  1037  1541 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-17 10:26:30.990  1037  1541 I WifiServiceExtension: setVHTCapabilityType  : false
08-17 10:26:30.999  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 10:26:30.999  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-17 10:26:31.000  1037  1541 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-17 10:26:31.000  1037  1541 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-17 10:26:31.001  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 10:26:31.003  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 10:26:31.003  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 10:26:31.003  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-17 10:26:31.007  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 10:26:31.007  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 10:26:31.007  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,08-17 10:26:31.010  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 10:26:31.011  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-17 10:26:31.011  1037  1541 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-17 10:26:31.011  1037  1548 D ConnectivityService: Got NetworkAgent Messenger
08-17 10:26:31.011  1037  1548 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-17 10:26:31.011  1037  1548 D ConnectivityService: NetworkAgent connected
08-17 10:26:31.011  1037  1541 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-17 10:26:31.011  1037  1541 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-17 10:26:31.012  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 10:26:31.012  1037  1541 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-17 10:26:31.012  1037  1541 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-17 10:26:31.014  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 10:26:31.014  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-17 10:26:31.015  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 10:26:31.016  1037  1541 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-17 10:26:31.016  1037  1541 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-17 10:26:31.016  1037  1541 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-17 10:26:31.018  1037  1541 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-17 10:26:31.018  1037  1541 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-17 10:26:31.022  1037  1541 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-17 10:26:31.023   320   896 D CommandListener: Setting iface cfg
08-17 10:26:31.027  1037  1541 E WifiStateMachine: Start Dhcp Watchdog 2
08-17 10:26:31.027  1037  7407 D DhcpStateMachine: StoppedState
08-17 10:26:31.027  1037  7407 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-17 10:26:31.027  1037  7407 D DhcpStateMachine: WaitBeforeStartState
08-17 10:26:31.028  1037  1541 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=368197  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-17 10:26:31.028  1037  1541 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=368198  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-17 10:26:31.029  1037  1541 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=368198  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-17 10:26:31.030  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-17 10:26:31.030  1037  1037 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-17 10:26:31.030  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-17 10:26:31.030  1037  1037 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-17 10:26:31.031  1037  1541 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=368200  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-17 10:26:31.031  1037  1541 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=368201  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-17 10:26:31.032  7388  7388 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-17 10:26:31.032  1037  1541 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=368201  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-17 10:26:31.032  7388  7388 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
08-17 10:26:31.033  1037  1541 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:322363] from screen [on:0 period:-1751391495] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-17 10:26:31.034  1037  1541 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1751391494] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-17 10:26:31.034  1037  1541 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-17 10:26:31.038  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 10:26:31.038  7388  7388 V [BNRBootReceiver]: Boot Receiver Return
08-17 10:26:31.038  7388  7388 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-17 10:26:31.038  1037  1548 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-17 10:26:31.039  1037  1541 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 10:26:31.040  1037  1541 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 10:26:31.040  1037  1541 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 10:26:31.041  1037  1541 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 10:26:31.041  1037  1541 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 10:26:31.041  1037  1541 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 10:26:31.042  1037  1548 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-17 10:26:31.042  1037  1541 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=147,0,0
08-17 10:26:31.042  6446  6446 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-17 10:26:31.043  1037  1541 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=147,0,0
08-17 10:26:31.043  1037  1541 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-17 10:26:31.044  7327  7327 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-17 10:26:31.044  1037  1541 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-17 10:26:31.044  1037  1541 D WifiNative-wlan0: doBoolean: SET ps 0
08-17 10:26:31.045  1037  1541 D WifiNative-wlan0: SET ps 0: returned true
08-17 10:26:31.045  1037  1541 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-17 10:26:31.045  7327  7327 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-17 10:26:31.045  1037  1541 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-17 10:26:31.046  1037  1541 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-17 10:26:31.046  1037  1541 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-17 10:26:31.046  1037  1540 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@347be5fa target=com.android.internal.util.StateMachine$SmHandler }
,08-17 10:26:31.046  1037  1541 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-17 10:26:31.046  1037  1540 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@347be5fa target=com.android.internal.util.StateMachine$SmHandler }
,08-17 10:26:31.047  1037  7407 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-17 10:26:31.047  1037  7407 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-17 10:26:31.048  6934  6934 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-17 10:26:31.048   320   896 D CommandListener: Setting iface cfg
08-17 10:26:31.048   320   896 D CommandListener: Trying to bring up wlan0
08-17 10:26:31.049  1037  1541 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-17 10:26:31.050  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-17 10:26:31.050  1037  1037 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-17 10:26:31.051  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-17 10:26:31.051  1037  1037 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-17 10:26:31.051  1037  1541 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 10:26:31.053  1037  1541 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 10:26:31.053  1037  1541 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 10:26:31.054  1037  1541 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 10:26:31.055  6934  6934 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 10:26:31.055  1037  1541 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 10:26:31.055  1037  1541 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 10:26:31.056  1037  1548 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-17 10:26:31.057  1037  1541 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-17 10:26:31.057  1037  1541 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-17 10:26:31.057  1037  1541 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-17 10:26:31.057  7327  7327 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-17 10:26:31.057  1037  1540 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-17 10:26:31.057  1037  1540 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,08-17 10:26:31.059  1037  1541 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-17 10:26:31.059  1037  1541 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-17 10:26:31.059  7327  7327 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-17 10:26:31.059  1037  1541 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-17 10:26:31.059  1037  1541 D WifiNative-wlan0: doBoolean: SET ps 1
08-17 10:26:31.063  6996  6996 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-17 10:26:31.064  6996  6996 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-17 10:26:31.065  6996  6996 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-17 10:26:31.068  6446  6446 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-17 10:26:31.076  6934  6934 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-17 10:26:31.076  1037  1541 D WifiNative-wlan0: SET ps 1: returned true
08-17 10:26:31.077  1037  1548 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-17 10:26:31.077  1037  1541 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-17 10:26:31.078  1037  1541 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-17 10:26:31.078  1037  1541 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-17 10:26:31.078  1037  1548 D ConnectivityService: ignoring duplicate network state non-change
,08-17 10:26:31.082  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 10:26:31.082  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-17 10:26:31.083  6934  6934 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 10:26:31.083  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 10:26:31.083  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 10:26:31.083  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-17 10:26:31.084  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 10:26:31.085  1037  1548 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-17 10:26:31.086  1037  1548 D ConnectivityService: Adding iface wlan0 to network 101
08-17 10:26:31.088  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 10:26:31.088  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 10:26:31.088  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-17 10:26:31.093  1037  1541 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-17 10:26:31.095  1037  1037 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-17 10:26:31.098  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 10:26:31.098  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 10:26:31.098  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-17 10:26:31.098  1037  1037 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-17 10:26:31.100  1970  1970 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-17 10:26:31.103  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 10:26:31.103  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 10:26:31.103  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-17 10:26:31.105  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 10:26:31.105  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-17 10:26:31.106  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-17 10:26:31.109  6996  6996 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-17 10:26:31.109  6996  6996 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-17 10:26:31.109  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 10:26:31.110  1605  1605 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-17 10:26:31.110  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 10:26:31.110  6996  6996 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-17 10:26:31.115  1037  1548 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-17 10:26:31.115  1037  1548 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-17 10:26:31.115  6934  6934 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-17 10:26:31.116  1037  1548 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-17 10:26:31.116  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-17 10:26:31.116  1605  1605 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-17 10:26:31.116  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 10:26:31.117   320   896 E Netd    : netlink response contains error (File exists)
08-17 10:26:31.117  1037  1548 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-17 10:26:31.118  1037  1548 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-17 10:26:31.118  1037  1548 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-17 10:26:31.118  1037  1548 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-17 10:26:31.119  1037  1548 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-17 10:26:31.119  1037  1548 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-17 10:26:31.119  1037  1548 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-17 10:26:31.119  1037  1548 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-17 10:26:31.119  1037  1548 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-17 10:26:31.119  1037  1548 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-17 10:26:31.120  1037  1548 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-17 10:26:31.120  1037  1548 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 10:26:31.120  1037  1548 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-17 10:26:31.120  1037  1548 D ConnectivityService: currentScore = 0, newScore = 20
08-17 10:26:31.120  1037  1548 D ConnectivityService:    accepting network in place of null
08-17 10:26:31.120  1037  1548 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 10:26:31.120  1037  1541 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 10:26:31.120  1037  1541 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-17 10:26:31.121  1882  1882 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 10:26:31.121  1882  1882 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-17 10:26:31.122  1037  7406 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
,08-17 10:26:31.122  1037  7406 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-17 10:26:31.122  1037  7406 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-17 10:26:31.122  1037  7406 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-17 10:26:31.123  1037  1548 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-17 10:26:31.123  1037  1548 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-17 10:26:31.123  1037  1548 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-17 10:26:31.123  1037  1548 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-17 10:26:31.124  1037  1548 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-17 10:26:31.124   320  7412 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-17 10:26:31.125  1037  1548 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-17 10:26:31.125  1037  1548 D ConnectivityService: validation of new default Network = false
08-17 10:26:31.126  1037  1548 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-17 10:26:31.126  1037  1548 D DSQN    : enableDataServiceNotify 
08-17 10:26:31.126  1037  1548 D DSQN    : start dsqn bin
08-17 10:26:31.128  1037  1037 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-17 10:26:31.128  1037  1037 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-17 10:26:31.128  1037  1037 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-17 10:26:31.128  1037  1037 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-17 10:26:31.132  6934  6934 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
,08-17 10:26:31.134  1037  1548 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-17 10:26:31.134  1037  1548 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 10:26:31.134  1037  1548 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-17 10:26:31.135  1037  1548 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-17 10:26:31.135  1605  1817 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-17 10:26:31.119  7413  7413 W dsqn    : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 10:26:31.119  7413  7413 W dsqn    : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 10:26:31.139  6446  6446 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-17 10:26:31.151  7413  7413 E DSQN    : DSQN ssw
,08-17 10:26:31.156  6934  6934 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-17 10:26:31.161  1037  1539 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,08-17 10:26:31.167  6934  6934 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 10:26:31.175  6996  6996 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-17 10:26:31.175  6996  6996 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-17 10:26:31.175  6996  6996 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-17 10:26:31.179   320  7412 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-17 10:26:31.180  6694  7102 D UEI.SmartControl: Internal timer expired: 2
08-17 10:26:31.180  6694  7102 D UEI.SmartControl: unbind internal service
08-17 10:26:31.181  6934  6934 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-17 10:26:31.181  6934  6934 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-17 10:26:31.181  6934  6934 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-17 10:26:31.181  6934  6934 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-17 10:26:31.182  6934  6934 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-17 10:26:31.182  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-17 10:26:31.182  6934  6934 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-17 10:26:31.182  6934  6934 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-17 10:26:31.183  6934  6934 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-17 10:26:31.183  6934  6934 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-17 10:26:31.183  6934  6934 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-17 10:26:31.183  6934  6934 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-17 10:26:31.183  6934  6934 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-17 10:26:31.183  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 10:26:31.184  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 10:26:31.186  6446  6446 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-17 10:26:31.187  1847  7417 I CheckinService: active receiver: enabled
,08-17 10:26:31.201  1847  7417 I CheckinService: Preparing to send checkin request
08-17 10:26:31.201  1847  7417 I EventLogService: Accumulating logs since 1471422080174
08-17 10:26:31.204  6934  6934 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-17 10:26:31.211  6934  6934 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 10:26:31.212   320  7412 D libc-netbsd: res_queryN name = clients3.google.com succeed
08-17 10:26:31.218  6996  6996 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-17 10:26:31.218  6996  6996 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-17 10:26:31.219  6996  6996 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-17 10:26:31.223  6446  6446 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-17 10:26:31.230  6934  6934 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-17 10:26:31.238  6934  6934 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 10:26:31.244   320   895 D LGDataListener: argv[0]=dsqncommand
08-17 10:26:31.244   320   895 D LGDataListener: argv[1]=wlan0
08-17 10:26:31.244   320   895 D LGDataListener: argv[2]=1
08-17 10:26:31.244   320   895 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-17 10:26:31.244  1037  1118 D DSQN    : DSQM DsqnNotification wlan0  1
08-17 10:26:31.244  1037  1118 D DSQN    : start to monitor internet connection
08-17 10:26:31.246  6996  6996 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-17 10:26:31.247  6996  6996 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-17 10:26:31.247  6996  6996 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-17 10:26:31.249  1037  7407 D DhcpStateMachine: DHCPV4 request on wlan0
08-17 10:26:31.250  1037  7407 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-17 10:26:31.250  1037  7407 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-17 10:26:31.254  6446  6446 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-17 10:26:31.239  7421  7421 W dhcpcd  : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-17 10:26:31.239  7421  7421 W dhcpcd  : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 10:26:31.256  1847  7417 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
08-17 10:26:31.264  7421  7421 I dhcpcd  : version 5.5.6 starting
08-17 10:26:31.265  6934  6934 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-17 10:26:31.267  7421  7421 E dhcpcd  : get_duid: m
08-17 10:26:31.267  7421  7421 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-17 10:26:31.267  7421  7421 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-17 10:26:31.271  1037  7406 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 17 Aug 2016 08:26:31 GMT], X-Android-Received-Millis=[1471422391270], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1471422391243]}
08-17 10:26:31.271  1037  7406 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-17 10:26:31.271  1037  7406 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-17 10:26:31.271  1037  1548 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-17 10:26:31.271  1037  1548 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-17 10:26:31.272  1037  1548 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-17 10:26:31.272  6694  7096 D serial_port: close(fd = 24)
08-17 10:26:31.272  1037  1548 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-17 10:26:31.272  1037  1548 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
,08-17 10:26:31.272  1037  1548 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-17 10:26:31.272  1037  1548 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-17 10:26:31.272  1037  1548 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 10:26:31.272  1037  1548 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-17 10:26:31.272  1037  1548 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-17 10:26:31.273  1037  1548 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 10:26:31.273  1037  1548 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-17 10:26:31.273  1037  1541 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 10:26:31.273  1037  1541 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-17 10:26:31.274  1605  1817 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-17 10:26:31.274  1882  1882 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 10:26:31.274  1882  1882 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-17 10:26:31.276  6694  7096 I UEI.SmartControl: Serial port is closed.
08-17 10:26:31.279  6934  6934 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-17 10:26:31.296  6996  6996 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-17 10:26:31.297  6996  6996 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-17 10:26:31.300  6996  6996 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-17 10:26:31.305  6446  6446 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-17 10:26:31.316  6934  6934 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-17 10:26:31.338  6934  6934 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 10:26:31.339  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-17 10:26:31.340  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 10:26:31.341  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 10:26:31.344  7421  7421 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-17 10:26:31.344  7421  7421 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-17 10:26:31.344  7421  7421 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-17 10:26:31.344  7421  7421 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
08-17 10:26:31.344  7421  7421 D dhcpcd  : wlan0: sending REQUEST (xid 0xd06cd69b), next in 4.75 seconds
,08-17 10:26:31.350  6996  6996 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-17 10:26:31.350  6996  6996 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-17 10:26:31.351  6996  6996 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-17 10:26:31.363  6446  6446 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-17 10:26:31.375  6934  6934 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-17 10:26:31.377  7421  7421 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
08-17 10:26:31.382  6934  6934 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 10:26:31.391  6996  6996 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-17 10:26:31.392  6996  6996 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-17 10:26:31.396  6996  6996 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-17 10:26:31.398  7421  7421 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
08-17 10:26:31.398  7421  7421 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
08-17 10:26:31.399  7421  7421 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-17 10:26:31.399  7421  7421 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-17 10:26:31.399  7421  7421 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,08-17 10:26:31.400  7421  7421 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-17 10:26:31.400  7421  7421 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-17 10:26:31.400  7421  7421 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-17 10:26:31.463  1037  1963 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7432 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-17 10:26:31.482  6446  6446 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-17 10:26:31.496  6934  6934 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-17 10:26:31.503  6934  6934 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 10:26:31.513  6996  6996 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-17 10:26:31.513  6996  6996 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-17 10:26:31.514  6996  6996 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-17 10:26:31.521  6446  6446 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-17 10:26:31.527  6951  6951 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-17 10:26:31.532  6951  6951 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-17 10:26:31.541  6934  6934 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-17 10:26:31.548  6934  6934 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 10:26:31.555  6996  6996 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-17 10:26:31.555  7432  7432 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-17 10:26:31.555  6996  6996 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-17 10:26:31.555  7432  7432 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
08-17 10:26:31.556  6996  6996 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,08-17 10:26:31.557  6996  6996 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-17 10:26:31.558  6996  6996 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-17 10:26:31.563  6446  6446 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-17 10:26:31.567  6951  6951 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-17 10:26:31.568  6951  6951 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-17 10:26:31.572  6934  6934 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-17 10:26:31.581  6934  6934 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 10:26:31.587  6996  6996 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-17 10:26:31.588  7432  7432 I MultiDex: VM with version 2.1.0 has multidex support
08-17 10:26:31.588  6996  6996 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-17 10:26:31.588  7432  7432 I MultiDex: install
08-17 10:26:31.588  7432  7432 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-17 10:26:31.589  6996  6996 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-17 10:26:31.590  6996  6996 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-17 10:26:31.590  6996  6996 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-17 10:26:31.592  1037  2117 I ActivityManager: Killing 6972:com.lge.lifetracker/u0a37 (adj 15): empty #17
08-17 10:26:31.640  1037  1740 W libprocessgroup: failed to open /acct/uid_10037/pid_6972/cgroup.procs: No such file or directory
,08-17 10:26:31.647  7432  7432 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,08-17 10:26:31.651  2249  2249 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-17 10:26:31.654  1037  7407 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-17 10:26:31.656  1037  7407 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-17 10:26:31.656  1037  7407 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
,08-17 10:26:31.656  1037  7407 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
08-17 10:26:31.656  1037  7407 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-17 10:26:31.656  1037  7407 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-17 10:26:31.657  1037  7407 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-17 10:26:31.657  1037  7407 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-17 10:26:31.657  1037  7407 D DhcpStateMachine: RunningState
08-17 10:26:31.664  2249  2249 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
08-17 10:26:31.664  2249  2249 D c       : Getting all permits...
08-17 10:26:31.664  2249  2249 D a       : Opening database...
08-17 10:26:31.668  2249  2249 D a       : Opening database auth.proximity.permit_store...
,08-17 10:26:31.669  2249  2249 D a       : Closing database...
08-17 10:26:32.096  7432  7450 D LgDataFeature: LgDataFeature() Constructor: none
,08-17 10:26:32.096  7432  7450 D LgDataFeature: LgDataFeature() Constructor Done, null
08-17 10:26:32.136  1037  1548 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-17 10:26:32.445  7474  7474 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-17 10:26:32.499  7474  7474 I dex2oat : dex2oat took 54.675ms (threads: 4)
,08-17 10:26:32.510  7432  7450 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-17 10:26:32.510  7432  7450 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-17 10:26:32.510  7432  7450 I Adreno-EGL: Build Date: 12/12/14 금
08-17 10:26:32.510  7432  7450 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-17 10:26:32.510  7432  7450 I Adreno-EGL: Remote Branch: 
08-17 10:26:32.510  7432  7450 I Adreno-EGL: Local Patches: 
08-17 10:26:32.510  7432  7450 I Adreno-EGL: Reconstruct Branch: 
08-17 10:26:32.606  7432  7450 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-17 10:26:32.606  7432  7450 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-17 10:26:32.606  7432  7450 I Adreno-EGL: Build Date: 12/12/14 금
08-17 10:26:32.606  7432  7450 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-17 10:26:32.606  7432  7450 I Adreno-EGL: Remote Branch: 
08-17 10:26:32.606  7432  7450 I Adreno-EGL: Local Patches: 
08-17 10:26:32.606  7432  7450 I Adreno-EGL: Reconstruct Branch: 
,08-17 10:26:32.686  7432  7450 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-17 10:26:32.686  7432  7450 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-17 10:26:32.686  7432  7450 I Adreno-EGL: Build Date: 12/12/14 금
08-17 10:26:32.686  7432  7450 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-17 10:26:32.686  7432  7450 I Adreno-EGL: Remote Branch: 
08-17 10:26:32.686  7432  7450 I Adreno-EGL: Local Patches: 
08-17 10:26:32.686  7432  7450 I Adreno-EGL: Reconstruct Branch: 
,08-17 10:26:32.709  1037  1541 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-17 10:26:32.710  1037  1541 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-17 10:26:32.710  1037  1541 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-17 10:26:32.711  1037  1541 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-17 10:26:32.711  1037  1541 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-17 10:26:32.712  1037  1541 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-17 10:26:32.712  1037  1548 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
08-17 10:26:32.712  1037  1548 D ConnectivityService: identical MTU - not setting
08-17 10:26:32.713  1037  1548 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-17 10:26:32.713  1037  1548 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-17 10:26:32.713  1037  1548 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 10:26:32.713  1037  1548 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-17 10:26:32.713  1037  1548 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-17 10:26:32.714  1605  1817 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-17 10:26:32.852   320  7483 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-17 10:26:32.855   320  7483 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
,08-17 10:26:32.891   320  7483 D libc-netbsd: res_queryN name = android.clients.google.com succeed,
,08-17 10:26:33.085  1847  7417 I CheckinTask: Sending checkin request (7859 bytes)
,08-17 10:26:33.290  1847  7417 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,08-17 10:26:33.309  1847  7417 I CheckinService: active receiver: disabled
,08-17 10:26:33.332  2249  2249 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-17 10:26:33.352  2249  2249 I GCM     : GCM config loaded
,08-17 10:26:33.372   320  7491 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-17 10:26:33.375   320  7491 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
08-17 10:26:33.381  7177  7177 V SetupWizard: Connected to Gservices successfully
08-17 10:26:33.413   320  7491 D libc-netbsd: res_queryN name = mtalk.google.com succeed
,08-17 10:26:33.676  2249  7493 D GCM     : Connected
,08-17 10:26:33.708  2249  7493 D GCM     : Message class com.google.e.a.a.q
,08-17 10:26:34.040  1037  1541 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=73.5, 0.0, 0.0  rx=83.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1751388488] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-17 10:26:34.041  1037  1541 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=73.5, 0.0, 0.0  rx=83.5 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1751388487] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-17 10:26:34.041  1037  1541 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-17 10:26:34.051  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 10:26:34.100  1037  1542 V WifiInternetCheck: Single check msg out of sync, ignoring.
,08-17 10:26:34.125  1037  1548 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-17 10:26:34.133  1037  1120 D Tethering: MasterInitialState.processMessage what=3
08-17 10:26:34.144  6772  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 10:26:34.144  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:26:34.144  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:26:34.144  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 10:26:34.144  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 10:26:34.144  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 10:26:34.144  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 10:26:34.144  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 10:26:34.144  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 10:26:34.144  6772  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 10:26:34.144  6772  6772 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 10:26:34.151  6772  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 10:26:34.151  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:26:34.151  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:26:34.151  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 10:26:34.151  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 10:26:34.151  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 10:26:34.151  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 10:26:34.151  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 10:26:34.151  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 10:26:34.151  6772  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 10:26:34.151  6772  6772 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 10:26:34.158  6772  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 10:26:34.162  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:26:34.162  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:26:34.162  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 10:26:34.162  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 10:26:34.162  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 10:26:34.162  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 10:26:34.162  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 10:26:34.162  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 10:26:34.162  6772  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 10:26:34.163  6772  6772 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 10:26:34.167  1037  1097 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-17 10:26:34.170  6446  6446 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-17 10:26:34.171  6446  6933 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-17 10:26:34.185  5293  5293 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,08-17 10:26:34.216  2249  2249 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-17 10:26:34.234  7107  7107 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-17 10:26:34.234  7107  7107 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-17 10:26:34.234  7107  7107 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-17 10:26:34.234  7107  7107 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-17 10:26:34.244  7107  7107 I AppUp4:CustModeStarterReceiver: onReceive
,08-17 10:26:34.250  7107  7107 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@38e3d673
08-17 10:26:34.250  7107  7107 D AppUp4:CustFacade: isCustomizationCompleted : false
08-17 10:26:34.250  7107  7107 D AppUp4:CustFacade: isPhone : true
08-17 10:26:34.251  7107  7107 D AppUp4:CustModeStarterReceiver: begin check event
08-17 10:26:34.251  7107  7107 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-17 10:26:34.256  4343  4343 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-17 10:26:34.256  4343  4343 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-17 10:26:34.258  4343  4343 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-17 10:26:34.260  4343  4343 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-17 10:26:34.269  3484  3484 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
08-17 10:26:34.274  7145  7145 D eas_req : ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-17 10:26:34.279  3484  3484 V DownloadManager: DownloadService onCreate
08-17 10:26:34.294  3484  7495 I DownloadManager: in removeSpuriousFiles
08-17 10:26:34.295  3484  7495 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,08-17 10:26:34.307  3484  7495 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@3294cea7 on behalf of 3484
,08-17 10:26:34.316  3484  3484 V DownloadManager: DownloadService onStartCommand
08-17 10:26:34.321  3484  7495 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
08-17 10:26:34.321  3484  7495 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
08-17 10:26:34.321  3484  7495 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
08-17 10:26:34.321  3484  7495 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
08-17 10:26:34.322  3484  7495 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
08-17 10:26:34.322  3484  7495 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
08-17 10:26:34.322  3484  7495 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
08-17 10:26:34.322  3484  7495 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
08-17 10:26:34.322  3484  7495 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
08-17 10:26:34.322  3484  7495 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
08-17 10:26:34.323  3484  7495 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
08-17 10:26:34.323  3484  7496 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
08-17 10:26:34.328  1037  1053 D WifiServiceImplEx: setWifiEnabled: false pid=6772, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-17 10:26:34.329  1037  1053 D WifiService: setWifiEnabled: false pid=6772, uid=10118
08-17 10:26:34.329  1037  1053 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-17 10:26:34.335  7145  7498 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-17 10:26:34.337  3484  7495 I DownloadManager: in trimDatabase
08-17 10:26:34.338  3484  7495 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
08-17 10:26:34.340  1037  1097 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 10:26:34.344  1037  1054 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10005
08-17 10:26:34.344  1037  7406 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-17 10:26:34.345  1037  7406 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-17 10:26:34.345  1037  7406 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-17 10:26:34.345  1037  7406 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-17 10:26:34.345  1037  7406 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
,08-17 10:26:34.347  1037  1541 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-17 10:26:34.347  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-17 10:26:34.347  1037  1541 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-17 10:26:34.348  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-17 10:26:34.348  1037  1037 D Ulp_jni : JNI:system_update. Event-4
08-17 10:26:34.350  1037  1541 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-17 10:26:34.350  1037  1541 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-17 10:26:34.351  1037  1541 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-17 10:26:34.351  1037  1541 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-17 10:26:34.351  1037  1541 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-17 10:26:34.351  1037  1541 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-17 10:26:34.352  1037  1541 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-17 10:26:34.352  1037  1541 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-17 10:26:34.352  4343  7517 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-17 10:26:34.352  4343  7517 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-17 10:26:34.353  3484  7495 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@1987e7f2 on behalf of 3484
08-17 10:26:34.359  4343  7504 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-17 10:26:34.360  1037  1541 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-17 10:26:34.360  1037  1541 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-17 10:26:34.360  7327  7327 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-17 10:26:34.360  1037  1540 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-17 10:26:34.360  1037  1540 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-17 10:26:34.361  1037  1541 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-17 10:26:34.361  1037  1541 D WifiNative-wlan0: doBoolean: SET ps 1
08-17 10:26:34.361  1037  1541 D WifiNative-wlan0: SET ps 1: returned true
08-17 10:26:34.361   320   896 D CommandListener: Clearing all IP addresses on wlan0
08-17 10:26:34.368  3438  3438 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-17 10:26:34.369  3438  3438 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
,08-17 10:26:34.369  3438  3438 I LgeMiscReceiver: networkInfo.isConnected() = true
08-17 10:26:34.369  3438  3438 D PhoneState: setPdpRejectCasuse : false
08-17 10:26:34.369  1037  7407 D DhcpStateMachine: RunningState{ when=-8ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-17 10:26:34.373   320  7522 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-17 10:26:34.373  1037  7406 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
08-17 10:26:34.374  1037  1118 D DSQN    : Dns fail occured do internet check.
08-17 10:26:34.374  1037  1037 D DSQN    : EVENT_INTERNET_CHECK_REQUEST received
08-17 10:26:34.375  1037  1037 D DSQN    : try Internet connection check
08-17 10:26:34.376  7177  7177 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-17 10:26:34.377  7177  7177 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-17 10:26:34.386   320  7525 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-17 10:26:34.386  1037  7524 D DSQN    : ThreadTCPConnectionCheck DNS fail internet is not possible
08-17 10:26:34.387  1037  1118 D DSQN    : Dns timeout INTERNET_CHECK already in progress ignore!
08-17 10:26:34.389  1037  7523 D DSQN    : ThreadInternetCheck internet check NOK 
08-17 10:26:34.389  1037  7523 D DSQN    : L3_DATA_SERVICE_QUALITY STATUS 0 DataEnabled: false
08-17 10:26:34.389  1037  7523 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 com.android.server.DataServiceQualityMonitor.sendDSqualityIntent:1103 com.android.server.DataServiceQualityMonitor.access$200:55 com.android.server.DataServiceQualityMonitor$ThreadInternetCheck.run:921 <bottom of call stack> 
08-17 10:26:34.390  1037  1548 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-17 10:26:34.390  1037  1548 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
08-17 10:26:34.393  7240  7240 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:26:34
08-17 10:26:34.394  7240  7240 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-17 10:26:34.394  7240  7240 D Weather.Utils: 2 : All the weather widget is gone.
08-17 10:26:34.395  7240  7240 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-17 10:26:34.395  7240  7240 D WeatherAncestor: connectivity changed - connection : true
08-17 10:26:34.395  7240  7240 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@131639a9
08-17 10:26:34.396  7240  7240 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-17 10:26:34.396  7240  7240 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-17 10:26:34.396  7240  7240 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-17 10:26:34.396  7240  7240 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-17 10:26:34.396  7240  7240 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:26:34
08-17 10:26:34.398  1037  1037 D WifiHS20: hidePasspointNotification off =false
08-17 10:26:34.400  4343  7504 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,08-17 10:26:34.402  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 10:26:34.402  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-17 10:26:34.402  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 10:26:34.402  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 10:26:34.403  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-17 10:26:34.403  1037  1037 D WifiDataContinuityService: L3_DATA_SERVICE_QUALITY_ACTION, resultStatus : 0
08-17 10:26:34.404  1970  1970 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-17 10:26:34.406  1037  1541 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 10:26:34.406  1037  1541 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 10:26:34.406  1037  1541 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 10:26:34.407  1037  1541 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 10:26:34.407  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 10:26:34.407  1037  1541 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 10:26:34.407  1037  1541 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 10:26:34.407  1037  1541 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-17 10:26:34.408  1037  1540 D LGWifiP2pService: InactiveState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-17 10:26:34.408  1037  1540 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-17 10:26:34.408  1037  1540 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@dc8b449
08-17 10:26:34.408  1037  1540 D LGWifiP2pService: P2pDisablingState
08-17 10:26:34.410  1037  1540 D LGWifiP2pService: P2pDisablingState{ when=-2ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-17 10:26:34.410  1037  1540 D LGWifiP2pService: p2p socket connection lost
08-17 10:26:34.410  1037  1540 D LGWifiP2pService: P2pDisabledState
08-17 10:26:34.410  1970  1994 D WifiServiceExtension: isInternetCheckAvailable return false
08-17 10:26:34.410  3484  7496 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@1eb5ae43 on behalf of 3484
08-17 10:26:34.411  1037  1037 D WifiHS20: hidePasspointNotification off =false
08-17 10:26:34.411  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 10:26:34.411  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 10:26:34.411  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-17 10:26:34.411  1037  1037 D WifiScanningService: SCAN_AVAILABLE : 1
08-17 10:26:34.412  1037  1037 D RttService: SCAN_AVAILABLE : 1
08-17 10:26:34.412  1037  1559 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,08-17 10:26:34.412  1037  1560 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-17 10:26:34.412  1970  1970 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-17 10:26:34.412  1970  1970 D WfdsService: WifiP2pState is changed : false
08-17 10:26:34.412  1970  2334 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-17 10:26:34.412  1970  2334 D WfdsService: Set the WFDS Monitor: false
08-17 10:26:34.413  1970  2334 D WfdsMonitor: WFDS Monitor is stopped
08-17 10:26:34.413  1970  2334 D WfdsService: STATE : WfdsDisabledState - enter
08-17 10:26:34.413  1970  2335 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-17 10:26:34.413  1970  7352 D CtrlSupplicant: Received on exit socket, terminate
08-17 10:26:34.413  1970  7352 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-17 10:26:34.413  1970  7352 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-17 10:26:34.413  1037  1541 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-17 10:26:34.413  1970  7352 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
,08-17 10:26:34.415  1970  2334 W WfdsService: DefaultState - msg [9445378] is not handled
08-17 10:26:34.416  1037  1540 D LGWifiP2pService: P2pDisabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-17 10:26:34.416  1037  1540 D LGWifiP2pService: DefaultState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-17 10:26:34.416  1037  1541 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-17 10:26:34.416  7327  7327 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-17 10:26:34.416  1037  1541 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-17 10:26:34.416  1037  1541 D WifiNative-wlan0: doBoolean: SET ps 1
08-17 10:26:34.417  1037  1541 D WifiNative-wlan0: SET ps 1: returned true
08-17 10:26:34.418  4343  7504 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
08-17 10:26:34.422  4343  4343 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
08-17 10:26:34.422  4343  4343 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
08-17 10:26:34.422  4343  4343 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
08-17 10:26:34.426  3484  7496 V DownloadManager: processing inserted download 1
08-17 10:26:34.426   320   896 D CommandListener: Clearing all IP addresses on wlan0
,08-17 10:26:34.426  1037  1548 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-17 10:26:34.426  1037  1548 D DSQN    : disableDataServiceNotify
08-17 10:26:34.426  1037  1548 D DSQN    : stop dsqn bin
08-17 10:26:34.427  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 10:26:34.428  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-17 10:26:34.428   320  7532 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-17 10:26:34.429  4343  4343 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
08-17 10:26:34.429  1037  1118 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-17 10:26:34.430  3484  7496 V DownloadManager: processing inserted download 4
08-17 10:26:34.431  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 10:26:34.431  3484  7496 V DownloadManager: processing inserted download 7
08-17 10:26:34.432  1037  1541 D WifiNative-p2p0: doBoolean: TERMINATE
08-17 10:26:34.432  1037  1541 D WifiNative-p2p0: TERMINATE: returned true
08-17 10:26:34.432  1037  1541 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-17 10:26:34.432  1037  1541 E WifiStateMachine: useWiFiOffloading() : false
08-17 10:26:34.432  1037  1541 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-17 10:26:34.434  1037  1037 D WifiHS20: hidePasspointNotification off =false
08-17 10:26:34.434  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 10:26:34.434  1037  1548 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-17 10:26:34.434  1037  1548 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 10:26:34.434  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 10:26:34.434  1037  1548 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-17 10:26:34.434  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,08-17 10:26:34.435  1037  1548 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-17 10:26:34.435  1037  1548 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-17 10:26:34.435  1037  1548 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-17 10:26:34.435  1037  1548 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-17 10:26:34.435  1037  1548 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-17 10:26:34.435  1970  1970 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-17 10:26:34.436  1605  1817 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-17 10:26:34.436  1037  7406 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-17 10:26:34.436  1037  7406 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-17 10:26:34.436  1037  7406 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-17 10:26:34.436  1037  1548 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-17 10:26:34.436  1037  1548 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-17 10:26:34.437  1037  1548 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-17 10:26:34.437  1037  1548 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 10:26:34.437  1037  1548 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 10:26:34.437  3484  7496 V DownloadManager: processing inserted download 8
08-17 10:26:34.437  1037  1548 D NetworkManagementService: Removing idletimer
08-17 10:26:34.437  1037  1548 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 10:26:34.437  1037  1539 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-17 10:26:34.438  1882  1882 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 10:26:34.438  1882  1882 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-17 10:26:34.438  3484  7496 V DownloadManager: processing inserted download 9
08-17 10:26:34.438  1037  1541 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-17 10:26:34.438  1037  1539 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-17 10:26:34.438  1037  1541 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-17 10:26:34.438  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-17 10:26:34.439  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-17 10:26:34.439  1037  1037 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-17 10:26:34.439  1037  1037 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-17 10:26:34.439  1037  1548 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-17 10:26:34.439  7035  7514 I FormManager: Network unavailable (Unable to resolve host "static-avc.lglime.com": No address associated with hostname, URL : http://static-avc.lglime.com/avc/list/FORMMANAGER_lastUpdatedTime.json)
08-17 10:26:34.441  3484  7496 V DownloadManager: processing inserted download 10
08-17 10:26:34.441  1037  1037 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-17 10:26:34.441  1037  1037 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-17 10:26:34.441  1037  1037 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-17 10:26:34.441  1037  1037 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-17 10:26:34.441  1037  1037 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-17 10:26:34.441  1037  1037 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-17 10:26:34.441  1037  1037 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-17 10:26:34.441  3484  7496 V DownloadManager: processing inserted download 11
08-17 10:26:34.442  3484  7496 V DownloadManager: processing inserted download 12
08-17 10:26:34.444  3484  7496 V DownloadManager: processing inserted download 13
08-17 10:26:34.444  6446  6446 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-17 10:26:34.445  3484  7496 V DownloadManager: processing inserted download 14
08-17 10:26:34.445  3484  7496 V DownloadManager: processing inserted download 16
08-17 10:26:34.447  6772  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 10:26:34.447  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:26:34.447  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:26:34.447  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 10:26:34.447  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 10:26:34.447  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 10:26:34.447  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 10:26:34.447  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 10:26:34.447  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 10:26:34.447  6772  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 10:26:34.447  6772  6772 D io.jxcore.node.JXcoreExtension: notifyNetworkChang,ed: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 10:26:34.449  6951  6951 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-17 10:26:34.449  6951  6951 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-17 10:26:34.449  6951  6951 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-17 10:26:34.450  6772  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 10:26:34.450  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:26:34.450  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:26:34.450  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 10:26:34.450  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 10:26:34.450  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 10:26:34.450  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 10:26:34.450  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 10:26:34.450  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 10:26:34.450  6772  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 10:26:34.450  6772  6772 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 10:26:34.451  6772  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 10:26:34.451  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:26:34.451  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:26:34.451  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 10:26:34.451  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 10:26:34.451  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 10:26:34.451  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 10:26:34.451  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 10:26:34.451  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 10:26:34.451  6772  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 10:26:34.451  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-17 10:26:34.451  6772  6772 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 10:26:34.451  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-17 10:26:34.453  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-17 10:26:34.456  3484  3484 V DownloadManager: DownloadService onDestroy
08-17 10:26:34.456  6934  6934 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-17 10:26:34.458  7035  7514 V FormManager: Network unavailable.
08-17 10:26:34.458  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 10:26:34.461  7035  7514 V FormManager: Network unavailable.
08-17 10:26:34.463  6934  6934 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 10:26:34.464  7035  7514 V FormManager: Network unavailable.
08-17 10:26:34.461  4343  4343 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
,08-17 10:26:34.469  6996  6996 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-17 10:26:34.470  6996  6996 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-17 10:26:34.471  6996  6996 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-17 10:26:34.474  6446  6446 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-17 10:26:34.477  6951  6951 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-17 10:26:34.477  6951  6951 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-17 10:26:34.477  6951  6951 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-17 10:26:34.479  6934  6934 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-17 10:26:34.485  6934  6934 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 10:26:34.490  6996  6996 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-17 10:26:34.490  6996  6996 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-17 10:26:34.491  6996  6996 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-17 10:26:34.494  6446  6446 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-17 10:26:34.494  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-17 10:26:34.494  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 10:26:34.495  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 10:26:34.497  6951  6951 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-17 10:26:34.497  6951  6951 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-17 10:26:34.497  6951  6951 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-17 10:26:34.499  7327  7327 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-17 10:26:34.499  7327  7327 I wpa_supplicant: monitor socket send errors count : 1
08-17 10:26:34.499  7327  7327 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1970-4\x00 that cannot receive messages
08-17 10:26:34.501  1037  7351 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-17 10:26:34.501  1037  7351 D WifiMonitor: Dropping event because (p2p0) is stopped
08-17 10:26:34.501  6934  6934 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-17 10:26:34.512  6934  6934 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 10:26:34.516  6996  6996 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-17 10:26:34.516  6996  6996 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-17 10:26:34.517  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-17 10:26:34.517  6996  6996 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-17 10:26:34.518  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 10:26:34.518  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 10:26:34.523  6951  6951 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-17 10:26:34.525  7327  7327 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-17 10:26:34.525  7327  7327 W wpa_supplicant: USIM:  scard_deinit function
08-17 10:26:34.525  1037  1120 D Tethering: InitialState.processMessage what=4
08-17 10:26:34.526  1037  7351 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-17 10:26:34.526  1037  7351 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-17 10:26:34.526  1037  1120 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-17 10:26:34.526  1037  7351 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-17 10:26:34.526  1037  7351 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-17 10:26:34.526  1037  7351 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-17 10:26:34.526  1037  7351 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-17 10:26:34.527  1037  1541 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=371696
08-17 10:26:34.527  1037  1541 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=371696
08-17 10:26:34.527  1037  1541 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=371697  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-17 10:26:34.528  1037  1541 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=371697  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-17 10:26:34.528  1037  1541 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-17 10:26:34.528  1037  1541 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-17 10:26:34.530  6934  6934 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-17 10:26:34.533  6934  6934 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 10:26:34.537  7035  7535 W FormManager: Network not available. Please check & try again.
08-17 10:26:34.545  6934  6934 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,08-17 10:26:34.545  6934  6934 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-17 10:26:34.545  6934  6934 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-17 10:26:34.545  6934  6934 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-17 10:26:34.545  6934  6934 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-17 10:26:34.546  7035  7536 V FormManager: Network unavailable.
08-17 10:26:34.546  6934  6934 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-17 10:26:34.546  6934  6934 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-17 10:26:34.546  6934  6934 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-17 10:26:34.546  6934  6934 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-17 10:26:34.546  6934  6934 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-17 10:26:34.546  6934  6934 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-17 10:26:34.549  7035  7536 V FormManager: Network unavailable.
08-17 10:26:34.564  7259  7284 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,08-17 10:26:34.577  1037  7407 D DhcpStateMachine: StoppedState
,08-17 10:26:34.577  1037  7407 D DhcpStateMachine: StoppedState{ when=-160ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-17 10:26:34.577  1037  1541 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-17 10:26:34.578  1037  1541 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
,08-17 10:26:34.589  7327  7327 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-17 10:26:34.589  1037  7351 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-17 10:26:34.590  1037  7351 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-TERMINATING 
08-17 10:26:34.590  1037  7351 D WifiMonitor: Disconnecting from the supplicant, no more events
08-17 10:26:34.590  1037  1541 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 45 0
,08-17 10:26:34.692  1970  1970 D WfdsService: Supplicant Connection state is changed : false
,08-17 10:26:34.693  1970  2334 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-17 10:26:34.693  1970  2334 D WfdsService: Set the WFDS Monitor: false
08-17 10:26:34.693  1970  2334 D WfdsMonitor: WFDS Monitor is stopped
08-17 10:26:34.695  1037  1541 D WifiOffDelayIfNotUsed: stopMonitoring
08-17 10:26:34.695  1037  1541 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-17 10:26:34.695  1037  1541 E WifiStateMachine: useWiFiOffloading() : false
08-17 10:26:34.695  1037  1541 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-17 10:26:34.697  4343  4343 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,08-17 10:26:34.697  4343  4343 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-17 10:26:34.698  1970  1970 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-17 10:26:34.698  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 10:26:34.699  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-17 10:26:34.700  1037  1546 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-17 10:26:34.700  1037  1546 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-17 10:26:34.703  2512  2512 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 10:26:34.703  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:26:34.705  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:26:34.705  4343  4343 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-17 10:26:34.706  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 10:26:34.712  4343  4343 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-17 10:26:34.724  4343  7539 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-17 10:26:34.725  6951  6951 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-17 10:26:34.725  6951  6951 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-17 10:26:34.725  6951  6951 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-17 10:26:34.731  4343  7543 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-17 10:26:34.731  4343  7543 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-17 10:26:34.731  6934  6934 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-17 10:26:34.735  7035  7541 W FormManager: Network not available. Please check & try again.
08-17 10:26:34.738  7035  7542 V FormManager: Network unavailable.
,08-17 10:26:34.740  7035  7542 V FormManager: Network unavailable.
08-17 10:26:34.742  6934  6934 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 10:26:35.573  1037  1658 I ActivityManager: Killing 7015:com.lge.settings.easy/1000 (adj 15): empty #17
,08-17 10:26:35.605  1037  1999 W libprocessgroup: failed to open /acct/uid_1000/pid_7015/cgroup.procs: No such file or directory
,08-17 10:26:37.054  1037  1541 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1751385474] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-17 10:26:37.056  1037  1541 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1751385472] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-17 10:26:37.439  1037  1548 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-17 10:26:37.453  1037  1120 D Tethering: MasterInitialState.processMessage what=3
08-17 10:26:37.469  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 10:26:37.474  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:26:37.476  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:26:37.478  1037  1548 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-17 10:26:37.480  1037  1097 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-17 10:26:37.483  1037  1120 D Tethering: MasterInitialState.processMessage what=3
,08-17 10:26:37.495  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:26:37.497  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 10:26:37.500  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:26:37.502  6446  6446 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-17 10:26:37.504  6446  6933 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-17 10:26:37.515  5293  5293 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-17 10:26:37.525  5293  5293 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-17 10:26:37.540  2249  2249 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-17 10:26:37.559  7107  7107 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-17 10:26:37.559  7107  7107 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-17 10:26:37.559  7107  7107 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-17 10:26:37.559  7107  7107 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-17 10:26:37.563  7107  7107 I AppUp4:CustModeStarterReceiver: onReceive
08-17 10:26:37.567  7107  7107 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@38e3d673
08-17 10:26:37.567  7107  7107 D AppUp4:CustFacade: isCustomizationCompleted : false
08-17 10:26:37.567  7107  7107 D AppUp4:CustFacade: isPhone : true
08-17 10:26:37.567  7107  7107 D AppUp4:CustModeStarterReceiver: begin check event
08-17 10:26:37.568  7107  7107 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-17 10:26:37.572  4343  4343 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-17 10:26:37.573  4343  4343 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-17 10:26:37.574  4343  4343 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-17 10:26:37.580  4343  4343 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-17 10:26:37.587  7145  7145 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-17 10:26:37.616  1037  1097 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-17 10:26:37.622  1037  1097 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 10:26:37.622  1037  1097 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 10:26:37.627  4343  7567 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-17 10:26:37.628  4343  7572 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,08-17 10:26:37.628  4343  7572 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-17 10:26:37.636  7035  7569 W FormManager: Network not available. Please check & try again.
08-17 10:26:37.638  7145  7566 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-17 10:26:37.639  7035  7570 V FormManager: Network unavailable.
08-17 10:26:37.644  3438  3438 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-17 10:26:37.644  3438  3438 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-17 10:26:37.644  3438  3438 I LgeMiscReceiver: networkInfo.isConnected() = false
08-17 10:26:37.646  7035  7570 V FormManager: Network unavailable.
08-17 10:26:37.650  7177  7177 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-17 10:26:37.650  7177  7177 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-17 10:26:37.662  7240  7240 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:26:37
,08-17 10:26:37.664  7240  7240 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-17 10:26:37.664  7240  7240 D Weather.Utils: 2 : All the weather widget is gone.
08-17 10:26:37.665  7240  7240 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-17 10:26:37.665  7240  7240 D WeatherAncestor: connectivity changed - connection : true
08-17 10:26:37.665  7240  7240 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@131639a9
08-17 10:26:37.666  7240  7240 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-17 10:26:37.666  7240  7240 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-17 10:26:37.666  7240  7240 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-17 10:26:37.666  7240  7240 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-17 10:26:37.666  7240  7240 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:26:37
08-17 10:26:37.697  6446  6446 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-17 10:26:37.699  6446  6933 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-17 10:26:37.721  2249  2249 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-17 10:26:37.732  7107  7107 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-17 10:26:37.732  7107  7107 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-17 10:26:37.733  7107  7107 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-17 10:26:37.733  7107  7107 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-17 10:26:37.735  7107  7107 I AppUp4:CustModeStarterReceiver: onReceive
,08-17 10:26:37.741  7107  7107 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@38e3d673
08-17 10:26:37.741  7107  7107 D AppUp4:CustFacade: isCustomizationCompleted : false
08-17 10:26:37.741  7107  7107 D AppUp4:CustFacade: isPhone : true
08-17 10:26:37.742  7107  7107 D AppUp4:CustModeStarterReceiver: begin check event
,08-17 10:26:37.742  7107  7107 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-17 10:26:37.748  4343  4343 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-17 10:26:37.749  4343  4343 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-17 10:26:37.751  4343  4343 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-17 10:26:37.755  4343  4343 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-17 10:26:37.764  7145  7145 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-17 10:26:37.768  4343  7577 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-17 10:26:37.774  4343  7578 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-17 10:26:37.775  4343  7578 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-17 10:26:37.792  7145  7579 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-17 10:26:37.799  3438  3438 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,08-17 10:26:37.799  3438  3438 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-17 10:26:37.799  3438  3438 I LgeMiscReceiver: networkInfo.isConnected() = false
08-17 10:26:37.805  7035  7582 W FormManager: Network not available. Please check & try again.
,08-17 10:26:37.808  7177  7177 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-17 10:26:37.808  7177  7177 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-17 10:26:37.822  7035  7583 V FormManager: Network unavailable.
,08-17 10:26:37.834  7240  7240 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:26:37
08-17 10:26:37.836  7035  7583 V FormManager: Network unavailable.
,08-17 10:26:37.836  7240  7240 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-17 10:26:37.836  7240  7240 D Weather.Utils: 2 : All the weather widget is gone.
08-17 10:26:37.837  7240  7240 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-17 10:26:37.837  7240  7240 D WeatherAncestor: connectivity changed - connection : true
08-17 10:26:37.837  7240  7240 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@131639a9
08-17 10:26:37.839  7240  7240 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-17 10:26:37.839  7240  7240 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-17 10:26:37.839  7240  7240 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-17 10:26:37.839  7240  7240 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-17 10:26:37.840  7240  7240 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:26:37
08-17 10:26:37.860  1037  2044 I ActivityManager: Killing 7388:com.lge.bnr/1000 (adj 15): empty #17
,08-17 10:26:37.916  1037  1963 W libprocessgroup: failed to open /acct/uid_1000/pid_7388/cgroup.procs: No such file or directory
,08-17 10:26:39.352  1037  1578 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-17 10:26:39.352  1037  1578 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-17 10:26:39.383  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-17 10:26:39.384  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-17 10:26:39.384  1037  1037 D Ulp_jni : JNI:system_update. Event-4
08-17 10:26:39.384  1037  1120 D BluetoothManagerService: Message: 1
08-17 10:26:39.385  1037  1120 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-17 10:26:39.411  1037  1120 D BluetoothManagerService: Message: 20
08-17 10:26:39.411  1037  1120 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2d535d0a:true
,08-17 10:26:39.415  1037  1540 D LGWifiP2pService: P2pDisabledState{ when=-6ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-17 10:26:39.415  1037  1540 D LGWifiP2pService: DefaultState{ when=-6ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-17 10:26:39.416  7066  7066 D BluetoothAdapterState: make
08-17 10:26:39.421  7066  7066 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-17 10:26:39.421  7066  7066 I bluedroid-qcom: init
08-17 10:26:39.423  7066  7595 I BluetoothAdapterState: Entering OffState
08-17 10:26:39.423  7066  7066 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-17 10:26:39.423  7066  7066 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-17 10:26:39.423  7066  7066 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-17 10:26:39.423  7066  7066 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-17 10:26:39.423  7066  7066 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-17 10:26:39.425  7066  7066 I bluedroid-qcom: get_profile_interface socket
08-17 10:26:39.425  7066  7066 I bluedroid-qcom: get_profile_interface map_client
,08-17 10:26:39.430  7066  7599 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-17 10:26:39.434  7066  7599 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-17 10:26:39.420  7598  7598 W bdaddr_loader: type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 10:26:39.420  7598  7598 W bdaddr_loader: type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 10:26:39.439  1037  1541 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
08-17 10:26:39.440  1037  1541 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-17 10:26:39.448  7598  7598 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-17 10:26:39.448  7598  7598 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-17 10:26:39.448  7598  7598 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-17 10:26:39.451  1037  1037 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-17 10:26:39.452  1037  1037 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-17 10:26:39.452  1037  1037 D BluetoothManagerService: Stored Bluetooth name: G3
,08-17 10:26:39.454  1037  1120 D BluetoothManagerService: Message: 40
08-17 10:26:39.454  1037  1120 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-17 10:26:39.456  7066  7081 I bluedroid-qcom: config_hci_snoop_log
08-17 10:26:39.457  1037  1120 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-17 10:26:39.457  1037  1120 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-17 10:26:39.458  7598  7598 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-17 10:26:39.466  7598  7598 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-17 10:26:39.466  7598  7598 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
,08-17 10:26:39.471  7066  7595 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-17 10:26:39.471  7066  7599 D BluetoothAdapterProperties: Name is: G3
08-17 10:26:39.471  7066  7595 D BluetoothAdapterProperties: Setting state to 11
08-17 10:26:39.472  7066  7595 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-17 10:26:39.472  1037  1120 D BluetoothManagerService: Message: 60
08-17 10:26:39.472  1037  1120 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-17 10:26:39.472  1037  1120 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-17 10:26:39.474  7066  7595 I LGBluetoothServiceJni: classInitNative: succeeds
08-17 10:26:39.480  1970  1970 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-17 10:26:39.483  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-17 10:26:39.492  6934  6934 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
,08-17 10:26:39.497  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:26:39.498  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:26:39.499  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:26:39.504  7066  7066 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-17 10:26:39.505  7066  7066 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-17 10:26:39.505  7066  7066 V BluetoothPbapReceiver: ***********state = 11
08-17 10:26:39.510  7066  7595 D BluetoothBondStateMachine: make
,08-17 10:26:39.515  2249  2249 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-17 10:26:39.534  7066  7595 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@131639a9
08-17 10:26:39.535  7066  7595 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-17 10:26:39.535  7066  7595 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@131639a9
,08-17 10:26:39.536  7066  7600 I BluetoothBondStateMachine: StableState(): Entering Off State
08-17 10:26:39.536  7066  7595 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-17 10:26:39.538  7066  7595 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-17 10:26:39.545  7066  7595 E BluetoothAdapterService: File transfer profiles supported!!
08-17 10:26:39.580  1037  1999 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7617 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-17 10:26:39.589  7066  7066 D HeadsetService: Received start request. Starting profile...
,08-17 10:26:39.589  7066  7066 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-17 10:26:39.590  7066  7066 D LGBluetoothHfpAdapter: Version 1.6
08-17 10:26:39.593  7066  7066 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-17 10:26:39.594  7066  7066 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-17 10:26:39.595  7066  7066 D HeadsetStateMachine: make
08-17 10:26:39.598  7066  7595 E BluetoothAdapterService: File transfer profiles supported!!
08-17 10:26:39.605  7066  7595 E BluetoothAdapterService: File transfer profiles supported!!
08-17 10:26:39.611  7066  7595 E BluetoothAdapterService: File transfer profiles supported!!
,08-17 10:26:39.620  7066  7595 E BluetoothAdapterService: File transfer profiles supported!!
08-17 10:26:39.625  7066  7595 E BluetoothAdapterService: File transfer profiles supported!!
,08-17 10:26:39.632  7066  7595 E BluetoothAdapterService: File transfer profiles supported!!
08-17 10:26:39.638  7066  7066 D LgDataFeature: LgDataFeature() Constructor: none
,08-17 10:26:39.638  7066  7066 D LgDataFeature: LgDataFeature() Constructor Done, null
08-17 10:26:39.643  7066  7066 D HeadsetStateMachine: max_hf_connections = 1
08-17 10:26:39.643  7066  7066 I bluedroid-qcom: get_profile_interface handsfree
08-17 10:26:39.645  7066  7066 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-17 10:26:39.645   324  4037 V AudioPolicyService: registerClient() client 0xb04104c0, uid 1002
08-17 10:26:39.647   324  1389 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-17 10:26:39.647   324  1389 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-17 10:26:39.647   324  1389 V AudioPolicyManagerEx: getOutput() returns output 2
08-17 10:26:39.647  7066  7066 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-17 10:26:39.647   324  1388 V AudioFlinger: registerClient() client 0xb1433040, pid 7066
08-17 10:26:39.648   324  1382 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-17 10:26:39.648   324  1382 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-17 10:26:39.649   324  1383 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-17 10:26:39.649   324  1383 V AudioSystem: ioConfigChanged() opening already existing output! 4
,08-17 10:26:39.650  7066  7066 V ToneGenerator: Create Track: 0xb4928080
08-17 10:26:39.650  7066  7082 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
,08-17 10:26:39.650  7066  7066 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-17 10:26:39.650  7066  7082 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-17 10:26:39.650  7066  7066 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-17 10:26:39.650  7066  7082 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-17 10:26:39.650  7066  7082 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-17 10:26:39.650  1037  1985 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-17 10:26:39.650  1037  1985 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-17 10:26:39.651   324   324 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-17 10:26:39.651   324   324 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-17 10:26:39.651   324   324 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-17 10:26:39.651   324   324 V AudioPolicyManagerEx: getOutput() returns output 2
08-17 10:26:39.652  1605  1939 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-17 10:26:39.652  1605  1939 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-17 10:26:39.652  1605  1939 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-17 10:26:39.652  1605  1939 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-17 10:26:39.652  1882  2572 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-17 10:26:39.652  1882  2572 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-17 10:26:39.652  1882  2572 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-17 10:26:39.652  1882  2572 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-17 10:26:39.652  3438  3454 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
,08-17 10:26:39.652  3438  3454 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-17 10:26:39.652  3438  3454 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-17 10:26:39.652  3438  3454 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-17 10:26:39.653  1037  1985 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-17 10:26:39.653  1037  1985 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-17 10:26:39.653   324   324 I AudioFlinger: isAudioPlaybackHookOn() false
08-17 10:26:39.653   324   324 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-17 10:26:39.653   324   324 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-17 10:26:39.653   324   324 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-17 10:26:39.653   324   324 V AudioPolicyManagerEx: getOutput() returns output 2
08-17 10:26:39.654  7066  7066 V AudioSystem: getLatency() output 2, latency 50
08-17 10:26:39.654  7066  7066 V AudioSystem: getFrameCount() output 2, frameCount 960
08-17 10:26:39.654  7066  7066 V AudioTrack: createTrack_l() output 2 afLatency 50
08-17 10:26:39.654   324  1389 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-17 10:26:39.654   324  1389 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-17 10:26:39.654   324  1389 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-17 10:26:39.654   324  1389 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-17 10:26:39.654   324  1389 V AudioFlinger: createTrack() lSessionId: 22
08-17 10:26:39.654  7066  7595 V LGMDMManager: Create singleton instance
08-17 10:26:39.655  7066  7066 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-17 10:26:39.655   324  4037 V AudioFlinger: acquiring 22 from 7066, for 7066
08-17 10:26:39.655   324  4037 V AudioFlinger:  added new entry for 22
08-17 10:26:39.656  7066  7066 V ToneGenerator: ToneGenerator INIT OK, time: 376837
08-17 10:26:39.656  7066  7066 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@131639a9
08-17 10:26:39.656  7066  7626 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-17 10:26:39.657  7066  7626 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-17 10:26:39.657  7066  7626 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-17 10:26:39.657  7066  7066 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@131639a9
08-17 10:26:39.658  7066  7626 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-17 10:26:39.658  7066  7595 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-17 10:26:39.658   324  1388 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7066
08-17 10:26:39.658   324  1388 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-17 10:26:39.658   324  1388 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-17 10:26:39.658   324  1388 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-17 10:26:39.658   324  1388 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-17 10:26:39.658   324  1388 V voice   : voice_set_parameters: exit with code(0)
08-17 10:26:39.658   324  1388 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-17 10:26:39.658   324  1388 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-17 10:26:39.659   324  1388 V msm8974_platform: platform_set_parameters: exit with code(0)
08-17 10:26:39.659   324  1388 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-17 10:26:39.659   324  1388 V audio_hw_primary: adev_set_parameters: e,xit with code(0)
08-17 10:26:39.659   324  1388 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-17 10:26:39.659  7066  7066 D A2dpService: Received start request. Starting profile...
08-17 10:26:39.659  7066  7626 V ToneGenerator: ToneGenerator destructor
08-17 10:26:39.659  7066  7626 V ToneGenerator: stopTone
08-17 10:26:39.659  7066  7626 V ToneGenerator: Delete Track: 0xb4928080
08-17 10:26:39.659  7066  7066 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-17 10:26:39.660  7066  7626 V AudioTrack: ~AudioTrack, releasing session id from 7066 on behalf of 7066
08-17 10:26:39.660   324   324 V AudioFlinger: releasing 22 from 7066 for 7066
08-17 10:26:39.660   324   324 V AudioFlinger:  decremented refcount to 0
08-17 10:26:39.660   324   324 V AudioFlinger: purging stale effects
08-17 10:26:39.660   324   324 V AudioPolicyService: AudioCommandThread() adding release output 2
08-17 10:26:39.660   324   324 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-17 10:26:39.660   324   324 V AudioFlinger: PlaybackThread::Track destructor
,08-17 10:26:39.660   324  1275 V AudioPolicyService: AudioCommandThread() waking up
08-17 10:26:39.660   324   324 V AudioFlinger: removeClient_l() pid 7066, calling pid 324
08-17 10:26:39.660   324  1275 V AudioPolicyService: AudioCommandThread() processing release output 2
08-17 10:26:39.660   324  1275 V AudioPolicyManager: releaseOutput() 2
08-17 10:26:39.660   324  1275 V AudioPolicyService: AudioCommandThread() going to sleep
08-17 10:26:39.660  7066  7066 V Avrcp   : make
08-17 10:26:39.661  7066  7066 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-17 10:26:39.661  7066  7066 I bluedroid-qcom: get_profile_interface avrcp
08-17 10:26:39.670  7066  7066 V AudioManager: registerRemoteController: size of Media player list: 0
08-17 10:26:39.672  7066  7066 E AudioManager: No RCC entry present to update
08-17 10:26:39.672  7066  7066 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-17 10:26:39.675  7066  7066 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
,08-17 10:26:39.676  7066  7066 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-17 10:26:39.676  7066  7066 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-17 10:26:39.680  7066  7066 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-17 10:26:39.737  7617  7617 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-17 10:26:39.737  7617  7617 W LG Account v2.2: No ProfileInfo entries
,08-17 10:26:39.738  7617  7617 I LG Account v2.2: isEnabled: false
08-17 10:26:39.738  7617  7617 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-17 10:26:39.738  7617  7617 I Feature : [Lifetracker]Country: EU
08-17 10:26:39.738  7617  7617 I Feature : [Lifetracker]Operator: OPEN
08-17 10:26:39.738  7617  7617 I Feature : [Lifetracker]Ranking support: false
08-17 10:26:39.738  7617  7617 I Feature : [Lifetracker]Comfort support: false
08-17 10:26:39.738  7617  7617 I Feature : [Lifetracker]Accessory: true
08-17 10:26:39.738  7617  7617 I Feature : [Lifetracker]Health device: true
08-17 10:26:39.738  7617  7617 I Feature : [Lifetracker]Extra Pedometer: false
08-17 10:26:39.738  7617  7617 I Feature : [Lifetracker]Blood glucose device: false
08-17 10:26:39.738  7617  7617 I Feature : [Lifetracker]Device Number: 3
08-17 10:26:39.756  6934  6934 D BluetoothPermissionRequest: onReceive
,08-17 10:26:39.767  6934  6934 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-17 10:26:39.819  1037  1053 V SIM_STK : Menu title from STK is T-Mobile
08-17 10:26:39.820  1037  1053 V SIM_STK : Menu title from STK is T-Mobile
,08-17 10:26:39.895  1037  1658 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-17 10:26:39.904  7066  7066 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-17 10:26:39.908  7066  7066 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-17 10:26:39.908  7066  7066 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-17 10:26:39.908  7066  7066 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-17 10:26:39.908  7066  7066 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-17 10:26:39.908  7066  7066 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-17 10:26:39.908  7066  7066 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-17 10:26:39.908  7066  7066 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-17 10:26:39.908  7066  7066 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-17 10:26:39.909  7066  7066 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-17 10:26:39.909  7066  7066 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-17 10:26:39.909  7066  7066 I BluetoothA2dpServiceJni: classInitNative
08-17 10:26:39.909  7066  7066 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-17 10:26:39.909  7066  7066 D A2dpStateMachine: make
08-17 10:26:39.912  7066  7066 I bluedroid-qcom: get_profile_interface a2dp
,08-17 10:26:39.913  7066  7643 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-17 10:26:39.918  7066  7066 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-17 10:26:39.918  7066  7066 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-17 10:26:39.921  7066  7066 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@131639a9
08-17 10:26:39.922  7066  7642 D A2dpStateMachine: Enter Disconnected: -2
08-17 10:26:39.924  7066  7066 I BluetoothHidServiceJni: classInitNative: succeeds
,08-17 10:26:39.929  7066  7066 D HidService: Received start request. Starting profile...
08-17 10:26:39.929  7066  7066 I bluedroid-qcom: get_profile_interface hidhost
08-17 10:26:39.929  7066  7066 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@131639a9
08-17 10:26:39.930  7066  7066 I BluetoothHealthServiceJni: classInitNative: succeeds
08-17 10:26:39.932  7066  7066 D HealthService: Received start request. Starting profile...
08-17 10:26:39.936  7066  7066 I bluedroid-qcom: get_profile_interface health
08-17 10:26:39.936  7066  7066 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-17 10:26:39.936  7066  7066 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@131639a9
08-17 10:26:39.937  7066  7066 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-17 10:26:39.940  7066  7066 D PanService: Received start request. Starting profile...
,08-17 10:26:39.940  7066  7066 D BluetoothPanServiceJni: initializeNative(L110): pan
08-17 10:26:39.940  7066  7066 I bluedroid-qcom: get_profile_interface pan
08-17 10:26:39.947  7066  7066 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-17 10:26:39.948  7066  7066 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@131639a9
08-17 10:26:39.949  7066  7066 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-17 10:26:39.955  7066  7066 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-17 10:26:39.955  7066  7066 D BtGatt.GattService: Received start request. Starting profile...
08-17 10:26:39.955  7066  7066 D BtGatt.GattService: start()
08-17 10:26:39.955  7066  7066 I bluedroid-qcom: get_profile_interface gatt
08-17 10:26:39.956  7066  7066 D BtGatt.AdvertiseManager: advertise manager created
08-17 10:26:39.967  7066  7066 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@131639a9
,08-17 10:26:39.972  7066  7066 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@131639a9
08-17 10:26:39.973  7066  7066 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-17 10:26:39.975  7066  7066 V BluetoothMapService: BluetoothMapBinder()
08-17 10:26:39.976  7066  7066 D BluetoothMapService: Received start request. Starting profile...
08-17 10:26:39.976  7066  7066 D BluetoothMapService: start()
08-17 10:26:39.980  7066  7066 D BluetoothMapEmailSettingsLoader: Found 0 applications
,08-17 10:26:39.980  7066  7066 D BluetoothMapEmailAppObserver: createReceiver()
08-17 10:26:39.982  7066  7066 D BluetoothMapEmailAppObserver: initObservers()
08-17 10:26:39.982  7066  7066 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-17 10:26:39.992  7066  7066 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@131639a9
08-17 10:26:39.992  7066  7066 D HeadsetStateMachine: Proxy object connected
08-17 10:26:39.993  7066  7066 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-17 10:26:39.993  7066  7066 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
,08-17 10:26:39.999  7066  7066 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-17 10:26:39.999  7066  7626 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-17 10:26:40.000  7066  7626 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-17 10:26:40.001  7066  7626 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-17 10:26:40.003  7066  7066 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-17 10:26:40.006  7066  7066 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-17 10:26:40.010  7066  7066 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-17 10:26:40.011  7066  7066 V PanService: [BTUI] SIM Extra State :ABSENT
08-17 10:26:40.014  7066  7066 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-17 10:26:40.017  7066  7066 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-17 10:26:40.017  7066  7066 V BluetoothMapService: Handler(): got msg=1
08-17 10:26:40.018  7066  7595 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-17 10:26:40.019  7066  7595 I bluedroid-qcom: enable
,08-17 10:26:40.019  7066  7595 I bt_hci_bdroid: init
,08-17 10:26:40.020  7066  7653 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-17 10:26:40.020  7066  7653 I bt-btu  : btu_task pending for preload complete event
08-17 10:26:40.022  7066  7066 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-17 10:26:40.023  7066  7595 I bt_vendor: bt-vendor : init
08-17 10:26:40.023  7066  7595 I bt_vendor: bt-vendor : get_bt_soc_type
08-17 10:26:40.024  7066  7595 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-17 10:26:40.024  7066  7595 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-17 10:26:40.024  7066  7595 D bt_userial_mct: userial_init
08-17 10:26:40.024  7066  7595 D bt_hci_bdroid: set_power 1
08-17 10:26:40.024  7066  7595 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-17 10:26:40.024  7066  7595 I bt_vendor: Starting hciattach daemon
08-17 10:26:40.024  7066  7595 I bt_vendor: try to set true
08-17 10:26:40.026  7066  7066 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-17 10:26:40.026  7066  7066 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-17 10:26:40.026  7066  7066 V BluetoothSapReceiver: SapReceiver onReceive 
08-17 10:26:40.026  7066  7066 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-17 10:26:40.026  7066  7066 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-17 10:26:40.009  7656  7656 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 10:26:40.009  7656  7656 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 10:26:40.056  7657  7657 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-17 10:26:40.110  1037  2074 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7661 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-17 10:26:40.140  7673  7673 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-17 10:26:40.152  7679  7679 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-17 10:26:40.175  7683  7683 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-17 10:26:40.186  7684  7684 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-17 10:26:40.186  7661  7661 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-17 10:26:40.205  7685  7685 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-17 10:26:40.210  1037  2117 I ActivityManager: Killing 6694:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
08-17 10:26:40.218  7690  7690 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
08-17 10:26:40.234  6996  6996 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-17 10:26:40.235  6996  6996 W System.err: android.os.DeadObjectException
,08-17 10:26:40.235  6996  6996 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-17 10:26:40.235  6996  6996 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-17 10:26:40.235  6996  6996 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-17 10:26:40.235  6996  6996 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-17 10:26:40.235  6996  6996 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-17 10:26:40.235  6996  6996 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-17 10:26:40.235  6996  6996 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-17 10:26:40.235  6996  6996 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-17 10:26:40.236  6996  6996 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-17 10:26:40.236  6996  6996 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-17 10:26:40.236  6996  6996 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 10:26:40.236  6996  6996 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 10:26:40.236  6996  6996 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-17 10:26:40.236  6996  6996 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-17 10:26:40.236  6996  6996 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-17 10:26:40.237  6996  6996 W System.err: android.os.DeadObjectException
08-17 10:26:40.238  6996  6996 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-17 10:26:40.238  6996  6996 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-17 10:26:40.238  6996  6996 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
,08-17 10:26:40.239  6996  6996 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-17 10:26:40.239  6996  6996 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-17 10:26:40.239  6996  6996 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-17 10:26:40.239  6996  6996 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-17 10:26:40.239  6996  6996 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-17 10:26:40.239  6996  6996 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-17 10:26:40.239  6996  6996 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-17 10:26:40.239  6996  6996 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 10:26:40.239  6996  6996 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 10:26:40.240  6996  6996 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-17 10:26:40.240  6996  6996 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-17 10:26:40.240  6996  6996 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-17 10:26:40.241  6996  6996 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-17 10:26:40.242  7692  7692 I libmdmdetect: ESOC framework not supported
,08-17 10:26:40.244  7692  7692 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
08-17 10:26:40.254  7692  7692 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,08-17 10:26:40.254  7692  7692 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
,08-17 10:26:40.254  7692  7692 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
,08-17 10:26:40.254  7692  7692 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
,08-17 10:26:40.254  7692  7692 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-17 10:26:40.254  7692  7692 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-17 10:26:40.254  7692  7692 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-17 10:26:40.294  7692  7694 E QC-QMI  : qmi_client [7692] 14: failed to locate client data
08-17 10:26:40.295   479   479 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
,08-17 10:26:40.295   479   479 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
,08-17 10:26:40.329  1037  2028 W libprocessgroup: failed to open /acct/uid_1000/pid_6694/cgroup.procs: No such file or directory
,08-17 10:26:40.330  1037  2028 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-17 10:26:40.346  6996  6996 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-17 10:26:40.347  6996  6996 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,08-17 10:26:40.372  7695  7695 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-17 10:26:40.396  7697  7697 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-17 10:26:40.427  7066  7595 I bt_vendor: bluetooth satus is on
,08-17 10:26:40.427  7066  7595 D bt_hci_bdroid: preload
08-17 10:26:40.428  7066  7655 D bt_userial_mct: userial_open(port:0)
08-17 10:26:40.428  7066  7655 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-17 10:26:40.431  7066  7655 I bt_vendor: Done intiailizing UART
08-17 10:26:40.432  7066  7655 I bt_vendor: Done intiailizing UART
08-17 10:26:40.432  7066  7655 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-17 10:26:40.432  7066  7655 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-17 10:26:40.432  7066  7708 D bt_userial_mct: Entering userial_read_thread()
08-17 10:26:40.433  7066  7653 I bt-btu  : btu_task received preload complete event
08-17 10:26:40.433  7066  7653 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-17 10:26:40.433  7066  7653 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-17 10:26:40.435  7066  7653 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-17 10:26:40.438  1037  1999 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7700 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-17 10:26:40.438  6996  6996 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-17 10:26:40.440  7066  7653 I         : BTE_InitTraceLevels -- TRC_HCI
08-17 10:26:40.440  7066  7653 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-17 10:26:40.440  7066  7653 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-17 10:26:40.440  7066  7653 I         : BTE_InitTraceLevels -- TRC_AVDT
08-17 10:26:40.440  7066  7653 I         : BTE_InitTraceLevels -- TRC_AVRC
08-17 10:26:40.440  7066  7653 I         : BTE_InitTraceLevels -- TRC_A2D
08-17 10:26:40.440  7066  7653 I         : BTE_InitTraceLevels -- TRC_BNEP
08-17 10:26:40.440  7066  7653 I         : BTE_InitTraceLevels -- TRC_BTM
08-17 10:26:40.440  7066  7653 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-17 10:26:40.440  7066  7653 I         : BTE_InitTraceLevels -- TRC_GAP
08-17 10:26:40.440  7066  7653 I         : BTE_InitTraceLevels -- TRC_PAN
08-17 10:26:40.441  7066  7653 I         : BTE_InitTraceLevels -- TRC_SDP
08-17 10:26:40.441  7066  7653 I         : BTE_InitTraceLevels -- TRC_GATT
08-17 10:26:40.441  7066  7653 I         : BTE_InitTraceLevels -- TRC_SMP
08-17 10:26:40.441  7066  7653 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-17 10:26:40.441  7066  7653 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-17 10:26:40.504  7066  7653 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-17 10:26:40.505  7066  7653 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0179061 
08-17 10:26:40.505  7066  7653 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0179061 
,08-17 10:26:40.526  7066  7599 E bt-btif : Calling BTA_HhEnable
08-17 10:26:40.526  7066  7653 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-17 10:26:40.526  7066  7653 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-17 10:26:40.526  7066  7599 E bt-btif : L2CAP - L2CA_Register() called for PSM: 0x0017
08-17 10:26:40.526  7066  7653 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-17 10:26:40.526  7066  7653 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-17 10:26:40.526  7066  7653 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-17 10:26:40.527  7066  7599 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-17 10:26:40.528  1037  1037 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-17 10:26:40.528  7066  7599 D BluetoothAdapterProperties: Name is: G3
08-17 10:26:40.528  1037  1037 D BluetoothManagerService: Stored Bluetooth name: G3
08-17 10:26:40.529  7066  7599 D BluetoothAdapterProperties: Scan Mode:20
08-17 10:26:40.529  7066  7599 D BluetoothAdapterProperties: Discoverable Timeout:120
08-17 10:26:40.529  7066  7599 D bt_hci_bdroid: postload
08-17 10:26:40.530  7066  7599 D bte_conf: Device ID record 1 : primary
08-17 10:26:40.530  7066  7599 D bte_conf:   vendorId            = 00c4
,08-17 10:26:40.519  7722  7722 W sh      : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 10:26:40.519  7722  7722 W sh      : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 10:26:40.530  7066  7599 D bte_conf:   vendorIdSource      = 0001
08-17 10:26:40.530  7066  7599 D bte_conf:   product             = 13a1
08-17 10:26:40.530  7066  7599 D bte_conf:   version             = 1000
08-17 10:26:40.530  7066  7599 D bte_conf:   clientExecutableURL = 
08-17 10:26:40.530  7066  7599 D bte_conf:   serviceDescription  = 
08-17 10:26:40.530  7066  7599 D bte_conf:   documentationURL    = 
08-17 10:26:40.530  7066  7599 D bte_conf: bte_load_did_conf no section named DID2.
08-17 10:26:40.530  7066  7653 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-17 10:26:40.530  7066  7655 D bt_hci_bdroid: Used up Tx Cmd credits
08-17 10:26:40.532  7066  7655 D bt_hci_bdroid: Used up Tx Cmd credits
08-17 10:26:40.532  7066  7595 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-17 10:26:40.533  7066  7595 D BluetoothAdapterProperties: ScanMode =  20
08-17 10:26:40.533  7066  7595 D BluetoothAdapterProperties: State =  11
08-17 10:26:40.536  7066  7655 D bt_hci_bdroid: Used up Tx Cmd credits
08-17 10:26:40.536  7066  7655 D bt_hci_bdroid: Used up Tx Cmd credits
08-17 10:26:40.537  7066  7655 D bt_hci_bdroid: Used up Tx Cmd credits
08-17 10:26:40.538  7066  7708 E bt_mct  : hci lib postload completed
08-17 10:26:40.538  7066  7599 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-17 10:26:40.540  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:26:40.541  7066  7595 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-17 10:26:40.541  7066  7595 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-17 10:26:40.542  7066  7595 D BluetoothAdapterProperties: Setting state to 12
08-17 10:26:40.542  7066  7595 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-17 10:26:40.542  7066  7599 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-17 10:26:40.547  7066  7653 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-17 10:26:40.547  7066  7653 W bt-smp  : Plain text(LSB ~ MSB) = 3f e2 46 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-17 10:26:40.547  7066  7653 W bt-smp  : Encrypted text(LSB ~ MSB) = c6 15 02 c1 f1 e1 ba 97 4d 36 be 74 93 f2 b1 45 
08-17 10:26:40.547  7066  7653 W bt-btm  : Stopping oneshot timer
08-17 10:26:40.554  1037  1120 D BluetoothManagerService: Message: 60
08-17 10:26:40.554  1037  1120 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-17 10:26:40.554  1037  1120 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
08-17 10:26:40.555  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:26:40.555  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:26:40.555  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 10:26:40.555  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 10:26:40.555  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 10:26:40.555  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 10:26:40.555  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 10:26:40.555  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 10:26:40.557  7066  7599 D BluetoothAdapterProperties: Discoverable Timeout:120
08-17 10:26:40.557  7066  7599 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
,08-17 10:26:40.558  7066  7595 I BluetoothAdapterState: Entering On State
,08-17 10:26:40.561  6772  6772 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 10:26:40.562  7066  7595 D LGBluetoothServiceAdapter: [BTUI] OnState
08-17 10:26:40.562  7066  7595 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-17 10:26:40.562  7066  7595 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-17 10:26:40.563  6934  6950 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-17 10:26:40.563  7066  7595 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-17 10:26:40.567  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:26:40.567  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:26:40.567  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 10:26:40.567  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 10:26:40.567  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 10:26:40.567  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 10:26:40.567  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 10:26:40.567  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 10:26:40.567  6934  6950 D BluetoothPbap: onBluetoothStateChange: up=true
08-17 10:26:40.568  6772  6772 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 10:26:40.569  6934  6934 D BluetoothInputDevice: Proxy object connected
08-17 10:26:40.569  6934  6934 D HidProfile: Bluetooth service connected
08-17 10:26:40.570  7066  7653 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-17 10:26:40.570  7066  7653 W bt-smp  : Plain text(LSB ~ MSB) = 28 f7 42 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-17 10:26:40.570  7066  7653 W bt-smp  : Encrypted text(LSB ~ MSB) = cc 78 c7 f4 0e a2 f9 e0 3e fb da 28 11 02 c3 6d 
08-17 10:26:40.570  7066  7653 W bt-btm  : Stopping oneshot timer
08-17 10:26:40.575  7700  7700 D UEI.SmartControl: Quickset Services start...
08-17 10:26:40.578  7700  7700 I UEI.SmartControl: Manufacture = LGE
08-17 10:26:40.578  7700  7700 D UEI.SmartControl: Id = LGNevo
,08-17 10:26:40.580  7700  7700 D UEI.SmartControl: File observer start...
08-17 10:26:40.580  7700  7700 E UEI.SmartControl: IR Port is disabled: false
08-17 10:26:40.581  7700  7700 D UEI.SmartControl: Starting file observer...
08-17 10:26:40.581  7700  7700 D UEI.SmartControl: Extracting JNI libs...
08-17 10:26:40.581  7700  7700 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-17 10:26:40.583  7066  7653 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-17 10:26:40.583  7066  7653 W bt-smp  : Plain text(LSB ~ MSB) = 08 23 6e 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-17 10:26:40.584  7066  7653 W bt-smp  : Encrypted text(LSB ~ MSB) = 16 1a 1b 86 a0 4d 89 37 f3 bf 7b 7b 7d b5 52 06 
08-17 10:26:40.584  7066  7653 W bt-btm  : Stopping oneshot timer
08-17 10:26:40.595  7066  7653 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-17 10:26:40.595  7066  7653 W bt-smp  : Plain text(LSB ~ MSB) = 26 30 54 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-17 10:26:40.595  7066  7653 W bt-smp  : Encrypted text(LSB ~ MSB) = 0b 6c a3 c8 29 99 29 93 2a 03 9b e8 dd 4d b9 a9 
08-17 10:26:40.595  7066  7653 W bt-btm  : Stopping oneshot timer
,08-17 10:26:40.597  7729  7729 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-17 10:26:40.608  7066  7595 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
,08-17 10:26:40.611  7066  7653 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-17 10:26:40.611  7066  7653 W bt-smp  : Plain text(LSB ~ MSB) = 63 6c 5e 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-17 10:26:40.611  7066  7653 W bt-smp  : Encrypted text(LSB ~ MSB) = 6d ac 4e ba 95 6a af 40 4d 2a 7a ec 1a e1 a5 50 
08-17 10:26:40.611  7066  7653 W bt-btm  : Stopping oneshot timer
08-17 10:26:40.691  7700  7700 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-17 10:26:40.691  7700  7700 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-17 10:26:40.692  7700  7700 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-17 10:26:40.721  7700  7700 I UEI.SmartControl: --- Selecting new region: 6
,08-17 10:26:40.722  7700  7700 I UEI.SmartControl: Model = LG-D855
08-17 10:26:40.724  7700  7700 D UEI.SmartControl: QS Service created
,08-17 10:26:40.732  1037  1120 I art     : Explicit concurrent mark sweep GC freed 129609(6MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/64MB, paused 2.204ms total 160.346ms
08-17 10:26:40.732  6934  7355 D BluetoothMap: onBluetoothStateChange: up=true
08-17 10:26:40.734  1882  2571 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 10:26:40.735  6934  6934 D BluetoothMap: Proxy object connected
08-17 10:26:40.735  6934  6934 D MapProfile: Bluetooth service connected
08-17 10:26:40.735  6934  6934 D BluetoothMap: getConnectedDevices()
08-17 10:26:40.736  1037  1120 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 10:26:40.737  1882  1898 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 10:26:40.739  1882  1882 D BluetoothHeadset: Proxy object connected
08-17 10:26:40.739  1037  1037 D BluetoothHeadset: Proxy object connected
,08-17 10:26:40.740  7066  7081 V BluetoothMapService: getConnectedDevices()
08-17 10:26:40.743  7700  7700 I UEI.SmartControl: Service initServices...
08-17 10:26:40.744  1882  1882 D BluetoothHeadset: Proxy object connected
08-17 10:26:40.745  6934  6950 D BluetoothPan: onBluetoothStateChange on: true
08-17 10:26:40.745  6934  6950 D BluetoothPan: onBluetoothStateChange call bindService
08-17 10:26:40.746  7700  7700 D UEI.SmartControl: QS start get config
08-17 10:26:40.746  1882  2572 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 10:26:40.748  6934  6934 D BluetoothPan: BluetoothPAN Proxy object connected
08-17 10:26:40.748  6934  6934 D PanProfile: Bluetooth service connected
08-17 10:26:40.751  1882  1882 D BluetoothHeadset: Proxy object connected
,08-17 10:26:40.755  1037  1120 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-17 10:26:40.760  1037  1120 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-17 10:26:40.760  1037  1037 D BluetoothA2dp: Proxy object connected
08-17 10:26:40.760  1037  1120 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-17 10:26:40.762  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-17 10:26:40.764  1970  1970 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-17 10:26:40.764  1970  2183 D LGBluetoothAPIService: Message: 1
08-17 10:26:40.764  1970  2183 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
,08-17 10:26:40.769  1037  1037 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-17 10:26:40.770  1970  2183 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-17 10:26:40.770  1037  1120 D BluetoothManagerService: Message: 40
08-17 10:26:40.770  1037  1120 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-17 10:26:40.771  7066  7066 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-17 10:26:40.771  7066  7066 D BluetoothMapService: STATE_ON
08-17 10:26:40.772  7066  7066 D LGBluetoothAPIServer: [BTUI] onCreate()
08-17 10:26:40.772  7066  7066 D LGBluetoothAPIServer: [BTUI] onBind()
08-17 10:26:40.774  6772  6772 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
08-17 10:26:40.774  1970  1970 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-17 10:26:40.774  1970  2183 D LGBluetoothAPIService: Message: 100
08-17 10:26:40.774  1970  2183 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-17 10:26:40.779  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:26:40.779  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:26:40.779  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 10:26:40.779  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 10:26:40.779  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 10:26:40.779  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 10:26:40.779  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 10:26:40.779  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 10:26:40.779  6934  6934 D LocalBluetoothProfileManager: Adding local A2DP profile
08-17 10:26:40.781  6772  6772 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 10:26:40.784  1037  1120 D BluetoothManagerService: Message: 30
08-17 10:26:40.784  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:26:40.786  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:26:40.787  6934  6934 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-17 10:26:40.788  7066  7066 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@131639a9
08-17 10:26:40.788  7066  7066 V BluetoothPbapService: Pbap Service onCreate
08-17 10:26:40.788  7066  7066 V BluetoothPbapService: Starting PBAP service
08-17 10:26:40.789  7066  7066 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-17 10:26:40.789  7066  7066 V BluetoothMapService: Handler(): got msg=1
08-17 10:26:40.789  7066  7066 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-17 10:26:40.790  7700  7700 D UEI.SmartControl: Loading JNI Libs...
08-17 10:26:40.790  7066  7066 V BluetoothPbapService: Pbap Service onBind
,08-17 10:26:40.790  1037  1120 D BluetoothManagerService: Message: 30
08-17 10:26:40.790  7066  7066 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-17 10:26:40.790  7066  7066 V BluetoothPbapService: state: 12
08-17 10:26:40.791  7066  7066 V BluetoothPbapService: Handler(): got msg=1
08-17 10:26:40.791  7066  7066 V BluetoothPbapService: Pbap Service startRfcommSocketListener
,08-17 10:26:40.792  7066  7738 D BluetoothMapMasInstance: MAS initSocket()
08-17 10:26:40.792  7066  7739 V BluetoothPbapService: Pbap Service initSocket
08-17 10:26:40.793  1037  1658 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 10:26:40.793  7066  7738 D BluetoothMapMasInstance:   masId = 00
08-17 10:26:40.793  7066  7738 D BluetoothMapMasInstance:   msgTypes = 0e
08-17 10:26:40.793  7066  7738 D BluetoothMapMasInstance:   masName = SMS/MMS
08-17 10:26:40.793  7066  7738 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-17 10:26:40.794  1037  2113 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 10:26:40.794  7066  7739 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 10:26:40.794  7066  7739 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-17 10:26:40.795  7066  7739 V BluetoothPbapService: Succeed to create listening socket 
08-17 10:26:40.795  7066  7739 V BluetoothPbapService: Accepting socket connection...
08-17 10:26:40.796  7066  7599 D BluetoothAdapterProperties: Scan Mode:21
08-17 10:26:40.796  7066  7599 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-17 10:26:40.796  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:26:40.798  7066  7738 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 10:26:40.798  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:26:40.799  6934  6934 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-17 10:26:40.799  7066  7738 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-17 10:26:40.799  7066  7738 V BluetoothMapMasInstance: Succeed to create listening socket 
08-17 10:26:40.799  7066  7738 D BluetoothMapMasInstance: Accepting socket connection...
08-17 10:26:40.799  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:26:40.800  6934  6934 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-17 10:26:40.801  6934  6934 D BluetoothA2dp: Proxy object connected
08-17 10:26:40.801  6934  6934 D A2dpProfile: Bluetooth service connected
08-17 10:26:40.802  7066  7066 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-17 10:26:40.802  7066  7066 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-17 10:26:40.802  7066  7066 V BluetoothPbapReceiver: ***********state = 12
,08-17 10:26:40.805  6934  6934 D BluetoothPbap: Proxy object connected
08-17 10:26:40.805  6934  6934 D PbapServerProfile: Bluetooth service connected
08-17 10:26:40.805  6934  6934 D BluetoothHeadset: Proxy object connected
08-17 10:26:40.805  2249  2249 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-17 10:26:40.805  2249  2249 D c       : Getting all permits...
08-17 10:26:40.806  2249  2249 D a       : Opening database...
08-17 10:26:40.806  6934  6934 D HeadsetProfile: Bluetooth service connected
08-17 10:26:40.809  2249  2249 D a       : Opening database auth.proximity.permit_store...
08-17 10:26:40.809  2249  2249 D a       : Closing database...
08-17 10:26:40.810  6934  6934 D DockEventReceiver: finishStartingService: stopping service
08-17 10:26:40.817  6934  6934 D BluetoothPermissionRequest: onReceive
,08-17 10:26:40.819  6934  6934 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-17 10:26:40.820  6934  6934 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-17 10:26:40.821  7066  7066 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-17 10:26:40.822  7066  7066 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-17 10:26:40.827  7066  7066 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
08-17 10:26:40.836  1037  1384 V AlarmManager: ELAPSED_WAKEUP set : Alarm{1894890f type 2 when 378004 com.google.android.gms} when 378004
,08-17 10:26:40.838   320  7744 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-17 10:26:40.838  1037  1118 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-17 10:26:40.838  6996  6996 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
08-17 10:26:40.839  6996  6996 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:1484
08-17 10:26:40.845  7066  7066 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-17 10:26:40.845  7066  7066 V BtOppService: onCreate
,08-17 10:26:40.848  7066  7066 V BluetoothOppNotification: send message
08-17 10:26:40.851  7066  7066 V BtOppService: Starting RfcommListener
08-17 10:26:40.853  7066  7066 D BluetoothOppPreference: Dumping Names:  
08-17 10:26:40.853  7066  7066 D BluetoothOppPreference: {}
08-17 10:26:40.853  7066  7066 D BluetoothOppPreference: Dumping Channels:  
08-17 10:26:40.853  7066  7066 D BluetoothOppPreference: {}
08-17 10:26:40.854  7066  7066 V BtOppService: onStartCommand
08-17 10:26:40.855  7066  7748 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-17 10:26:40.856  7066  7745 V BtOppService: Deleted complete outbound shares, number =  0
08-17 10:26:40.856  7066  7748 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-17 10:26:40.856  7066  7066 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-17 10:26:40.856  7066  7066 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-17 10:26:40.857  7066  7745 V BtOppService: Deleted complete inbound failed shares, number = 0
08-17 10:26:40.857  7066  7745 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-17 10:26:40.857  7066  7748 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2498834a on behalf of 
08-17 10:26:40.858  7066  7745 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@222ca2bb on behalf of 
08-17 10:26:40.858  7066  7066 V BluetoothOppNotification: new notify threadi!
08-17 10:26:40.859  7066  7066 V BluetoothOppNotification: send delay message
08-17 10:26:40.859  7066  7066 V BtOppService: start RfcommListener
08-17 10:26:40.860  7066  7749 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-17 10:26:40.861  7066  7066 V BtOppService: RfcommListener started
08-17 10:26:40.861  7066  7066 V BtOppService: ContentObserver received notification
08-17 10:26:40.861  7066  7066 V BtOppService: ContentObserver received notification
08-17 10:26:40.861  7066  7750 V BtOppRfcommListener: Starting RFCOMM listener....
08-17 10:26:40.862  1037  2044 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 10:26:40.862  7066  7750 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 10:26:40.863  7066  7750 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=75
08-17 10:26:40.864  7066  7750 V BtOppRfcommListener: Started RFCOMM listener....
08-17 10:26:40.864  7066  7750 I BtOppRfcommListener: Accept thread started.
08-17 10:26:40.864  7066  7750 V BtOppRfcommListener: Accepting connection...
08-17 10:26:40.868  7066  7066 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@131639a9
08-17 10:26:40.868  7066  7066 V BluetoothFtpService: Ftp Service onCreate
08-17 10:26:40.868  7066  7066 I BluetoothFtpService: Ftp Service onCreate
,08-17 10:26:40.868  7066  7066 V BluetoothFtpService: Ftp Service onStartCommand
08-17 10:26:40.868  7066  7066 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-17 10:26:40.868  7066  7066 V BluetoothFtpService: Starting Listening on sockets
08-17 10:26:40.869  7066  7066 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-17 10:26:40.869  7066  7066 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-17 10:26:40.869  7066  7066 V BluetoothSapReceiver: SapReceiver onReceive 
08-17 10:26:40.869  7066  7066 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-17 10:26:40.869  7066  7066 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-17 10:26:40.869  7066  7066 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-17 10:26:40.869  7066  7748 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-17 10:26:40.870  7066  7748 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-17 10:26:40.870  7066  7066 V BluetoothFtpService: Handler(): got msg=1
08-17 10:26:40.871  7066  7749 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@22655331 on behalf of 
08-17 10:26:40.871  7066  7066 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-17 10:26:40.871  7066  7066 V BluetoothFtpService: Ftp Service initSocket
08-17 10:26:40.871  7066  7749 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-17 10:26:40.873  1037  2044 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 10:26:40.873  7066  7748 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@d638a16 on behalf of 
08-17 10:26:40.873  7066  7066 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 10:26:40.874  7066  7748 V BluetoothOppNotification: update too frequent, put in queue
08-17 10:26:40.874  7066  7066 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-17 10:26:40.874  7066  7066 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-17 10:26:40.874  7066  7748 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-17 10:26:40.874  7066  7749 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,08-17 10:26:40.876  7066  7751 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-17 10:26:40.877  7066  7749 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2a78af97 on behalf of 
08-17 10:26:40.878  7066  7749 V BluetoothOppNotification: outbound: succ-0  fail-0
08-17 10:26:40.879  7066  7749 V BluetoothOppNotification: outbound notification was removed.
08-17 10:26:40.879  7066  7749 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-17 10:26:40.879  7066  7749 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@acf584 on behalf of 
08-17 10:26:40.880  7066  7749 V BluetoothOppNotification: inbound: succ-0  fail-0
08-17 10:26:40.880  7066  7749 V BluetoothOppNotification: inbound notification was removed.
08-17 10:26:40.881  7066  7749 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-17 10:26:40.881  7066  7749 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@248af16d on behalf of 
08-17 10:26:40.882  7066  7066 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@131639a9
08-17 10:26:40.882  7066  7066 V BluetoothSapService: Sap Service onCreate
08-17 10:26:40.884  7066  7066 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-17 10:26:40.884  7066  7066 V BluetoothSapService: state: 12
08-17 10:26:40.884  7066  7066 V BluetoothSapService: Starting SAP server process
08-17 10:26:40.884  7066  7066 V BluetoothSapService: SAP Service startRfcommListenerThread
08-17 10:26:40.869  7752  7752 W sapd    : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 10:26:40.886  7066  7753 V BluetoothSapService: Sap Service initRfcommSocket
,08-17 10:26:40.869  7752  7752 W sapd    : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 10:26:40.887  1037  1054 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 10:26:40.887  7066  7753 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 10:26:40.888  7066  7753 V BluetoothSapService: Succeed to create listening socket 
08-17 10:26:40.888  7066  7753 V BluetoothSapService: Accepting socket connection...
08-17 10:26:40.896  7752  7752 V BT_SAP  : Event pipe created
08-17 10:26:40.896  7752  7752 V BT_SAP  : create_server_socket qcom.sap.server
08-17 10:26:40.896  7752  7752 V BT_SAP  : created socket fd 6
08-17 10:26:41.216  7700  7700 I UEI.SmartControl: Supports setup maps: true
,08-17 10:26:41.223  7700  7700 D UEI.SmartControl: QS start statue = true Error code = 0
08-17 10:26:41.223  7700  7700 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-17 10:26:41.223  7700  7700 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-17 10:26:41.224  7700  7700 I UEI.SmartControl: ### init IR Blaster...
08-17 10:26:41.230  7700  7700 D serial_port: Configuring serial port
,08-17 10:26:41.239  7700  7700 E UEI.SmartControl: UEIBLaster setting for 616
08-17 10:26:41.239  7700  7700 I UEI.SmartControl: Setting serial record hearder size = 2
08-17 10:26:41.240  7700  7700 I UEI.SmartControl: configuring settings for MAXQ616
08-17 10:26:41.240  7700  7700 I UEI.SmartControl: Get version...
08-17 10:26:41.257  7700  7760 D UEI.SmartControl: serial port data available: 21
,08-17 10:26:41.282  1605  1605 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-17 10:26:41.298  1037  1037 D administrator: Handling package changes for user 0
08-17 10:26:41.336  1037  1099 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7766 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-17 10:26:41.342  1605  1605 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
08-17 10:26:41.344  1605  1605 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
08-17 10:26:41.353  2096  2096 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-17 10:26:41.379  7700  7700 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-17 10:26:41.379  7700  7700 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-17 10:26:41.379  7700  7700 I UEI.SmartControl: QS saving settings...
,08-17 10:26:41.383  7700  7700 D UEI.SmartControl: IR Blaster version: 25672567
08-17 10:26:41.394  2096  2096 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-17 10:26:41.402  7766  7766 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-17 10:26:41.408  7700  7760 D UEI.SmartControl: serial port data available: 4
,08-17 10:26:41.414  1037  1444 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-17 10:26:41.419  1037  1037 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-17 10:26:41.419  1037  1037 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-17 10:26:41.437  7700  7792 I UEI.SmartControl: Device manager: loading config....
08-17 10:26:41.438  7700  7792 D UEI.SmartControl: ----------- loading internal config...
08-17 10:26:41.438  7700  7700 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-17 10:26:41.443  7700  7700 E UEI.SmartControl: Services init done
08-17 10:26:41.443  7700  7700 D UEI.SmartControl: QS Service init finished
08-17 10:26:41.444  7700  7700 D UEI.SmartControl: QS Service version name: 2.1.91
08-17 10:26:41.444  7700  7700 D UEI.SmartControl: QS Service version code: 201091
08-17 10:26:41.444  7700  7700 D UEI.SmartControl: Service requested: Control
08-17 10:26:41.448  7700  7792 E UEI.SmartControl: Loading SETTINGS...
08-17 10:26:41.451  7700  7700 D UEI.SmartControl: Request IControl service: devices are loaded...
08-17 10:26:41.452  7700  7792 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-17 10:26:41.453  1037  1999 I ActivityManager: Killing 6951:com.lge.sync/1000 (adj 15): empty #17
,08-17 10:26:41.454  6996  6996 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
,08-17 10:26:41.455  7700  7717 I UEI.SmartControl: ------ IControl API: 11
08-17 10:26:41.456  7700  7717 I UEI.SmartControl: Registering callback...
08-17 10:26:41.460  7700  7716 I UEI.SmartControl: ------ IControl API: 19
08-17 10:26:41.460  7700  7716 I UEI.SmartControl: Registering Services Ready callback...
08-17 10:26:41.479  1037  1097 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-17 10:26:41.480  7700  7791 I UEI.SmartControl: Notify AllClients services are ready: 0
08-17 10:26:41.480  6996  7012 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-17 10:26:41.481  6996  7083 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-17 10:26:41.481  6996  7083 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-17 10:26:41.481  6996  6996 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-17 10:26:41.481  7700  7791 D UEI.SmartControl: -----service ready thread exits
08-17 10:26:41.481  6996  6996 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-17 10:26:41.481  7700  7717 I UEI.SmartControl: ------ IControl API: 8
08-17 10:26:41.482  6996  6996 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-17 10:26:41.482  6996  6996 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-17 10:26:41.482  6996  6996 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-17 10:26:41.482  6996  6996 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-17 10:26:41.482  6996  6996 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-17 10:26:41.483  6996  6996 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-17 10:26:41.484  1037  1097 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-17 10:26:41.501  7766  7766 D LgDataFeature: LgDataFeature() Constructor: none
,08-17 10:26:41.502  7766  7766 D LgDataFeature: LgDataFeature() Constructor Done, null
08-17 10:26:41.530  7700  7700 D UEI.SmartControl: Internal service binding...
,08-17 10:26:41.532  1037  2117 W libprocessgroup: failed to open /acct/uid_1000/pid_6951/cgroup.procs: No such file or directory
,08-17 10:26:41.541  6996  6996 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-17 10:26:41.541  2096  2096 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-17 10:26:41.544  2512  2512 V GmsNetworkLocationProvi: DISABLE
,08-17 10:26:41.584  1037  1097 D LocationProviderProxy: applying state to connected service
,08-17 10:26:41.589  2512  2512 E GCoreFlp: Bound FusedProviderService with LocationManager
,08-17 10:26:41.672  7766  7805 I Babel   : MmsConfig: mnc/mcc: 0/0
,08-17 10:26:41.672  7766  7805 I Babel   : MmsConfig.loadMmsSettings
08-17 10:26:41.678  7766  7805 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-17 10:26:41.678  7766  7805 I Babel   : MmsConfig.loadFromDatabase
,08-17 10:26:41.712  7766  7766 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 10:26:41.715  7766  7805 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-17 10:26:41.715  7766  7805 I Babel   : MmsConfig.loadFromResources
,08-17 10:26:41.719  7766  7805 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-17 10:26:41.720  7766  7805 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,08-17 10:26:41.735  7766  7803 W AudioCapabilities: Unsupported mime audio/evrc
08-17 10:26:41.738  7766  7803 W AudioCapabilities: Unsupported mime audio/qcelp
08-17 10:26:41.740  7766  7803 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-17 10:26:41.752  1847  7807 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,08-17 10:26:41.752  1847  7807 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
08-17 10:26:41.755  7107  7107 I AppUp4:CustModeStarterReceiver: onReceive
08-17 10:26:41.759  7766  7803 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
08-17 10:26:41.761  7107  7107 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@38e3d673
08-17 10:26:41.761  7107  7107 D AppUp4:CustFacade: isCustomizationCompleted : false
08-17 10:26:41.761  7107  7107 D AppUp4:CustFacade: isPhone : true
08-17 10:26:41.761  7107  7107 D AppUp4:CustModeStarterReceiver: begin check event
08-17 10:26:41.762  7107  7107 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-17 10:26:41.767  7766  7803 W AudioCapabilities: Unsupported mime audio/qcelp
08-17 10:26:41.767  1847  4701 I Icing   : updateResources: need to parse e{com.google.android.gms}
,08-17 10:26:41.768  7766  7803 W AudioCapabilities: Unsupported mime audio/evrc
,08-17 10:26:41.787  7766  7803 W VideoCapabilities: Unsupported mime video/x-ms-wmv
08-17 10:26:41.790  7766  7803 W VideoCapabilities: Unsupported mime video/divx
08-17 10:26:41.793  7766  7803 W VideoCapabilities: Unsupported mime video/divx311
,08-17 10:26:41.796  7766  7803 W VideoCapabilities: Unsupported mime video/divx4
08-17 10:26:41.802  7766  7803 W VideoCapabilities: Unsupported mime video/mp4v-esdp
08-17 10:26:41.806  1037  1983 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7810 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,08-17 10:26:41.811  1037  1985 I ActivityManager: Killing 7145:com.lge.email/u0a23 (adj 15): empty #17
08-17 10:26:41.842  7766  7803 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-17 10:26:41.846  7766  7803 W AudioCapabilities: Unsupported mime audio/eac3
08-17 10:26:41.846  7766  7803 W AudioCapabilities: Unsupported mime audio/ac3
08-17 10:26:41.847  7766  7803 W AudioCapabilities: Unsupported mime audio/g726
08-17 10:26:41.848  7766  7803 W AudioCapabilities: Unsupported mime audio/wma-voice
08-17 10:26:41.849  7766  7803 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-17 10:26:41.849  7766  7803 W AudioCapabilities: Unsupported mime audio/adpcm
08-17 10:26:41.851  7766  7803 W VideoCapabilities: Unsupported mime video/theora
08-17 10:26:41.852  7766  7803 W VideoCapabilities: Unsupported mime video/mjpg
08-17 10:26:41.860  7066  7066 V BluetoothOppNotification: new notify threadi!
08-17 10:26:41.860  7066  7066 V BluetoothOppNotification: send delay message
08-17 10:26:41.861  7066  7827 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-17 10:26:41.862  7066  7827 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2ff23769 on behalf of 
08-17 10:26:41.863  7066  7827 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-17 10:26:41.864  7066  7827 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-17 10:26:41.869  7066  7827 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3b39c5ee on behalf of 
08-17 10:26:41.870  7066  7827 V BluetoothOppNotification: outbound: succ-0  fail-0
08-17 10:26:41.871  7066  7827 V BluetoothOppNotification: outbound notification was removed.
08-17 10:26:41.871  7066  7827 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-17 10:26:41.873  7066  7827 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@15fbfa8f on behalf of 
08-17 10:26:41.873  7066  7827 V BluetoothOppNotification: inbound: succ-0  fail-0
08-17 10:26:41.874  7066  7827 V BluetoothOppNotification: inbound notification was removed.
08-17 10:26:41.874  7066  7827 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,08-17 10:26:41.876  7066  7827 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3c3b711c on behalf of 
08-17 10:26:41.893  1037  2117 W libprocessgroup: failed to open /acct/uid_10023/pid_7145/cgroup.procs: No such file or directory
,08-17 10:26:41.918  7810  7810 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-17 10:26:41.918  7810  7810 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-17 10:26:41.918  7810  7810 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-17 10:26:41.920  7810  7810 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-17 10:26:41.920  7810  7810 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,08-17 10:26:42.009  7810  7810 I SystemConfig: BUILD Country: EU
08-17 10:26:42.010  7810  7810 I SystemConfig: BUILD Operator: OPEN
,08-17 10:26:42.056  1037  1963 I ActivityManager: Killing 7035:com.lge.formmanager/u0a26 (adj 15): empty #17
,08-17 10:26:42.196  1037  1999 W libprocessgroup: failed to open /acct/uid_10026/pid_7035/cgroup.procs: No such file or directory
,08-17 10:26:42.209  7810  7829 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-17 10:26:42.209  7810  7829 I SystemConfig: existFile = false
08-17 10:26:42.209  7810  7829 I SystemConfig: canReadFile = false
08-17 10:26:42.209  7810  7829 I SystemConfig: systemFeature RCS result false
08-17 10:26:42.210  7810  7829 D SystemConfig: refreshRcsSupport() :false
,08-17 10:26:42.245  1037  1963 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7834 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-17 10:26:42.308  7834  7834 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-17 10:26:42.309  7834  7834 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-17 10:26:42.309  7834  7834 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-17 10:26:42.309  7834  7834 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-17 10:26:42.428  7834  7834 I AppConfig: Total System Memory = 2995761152
,08-17 10:26:42.440  7834  7834 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
08-17 10:26:42.522  1037  1983 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7853 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-17 10:26:42.524  1037  1983 I ActivityManager: Killing 6446:com.wsandroid.suite.lge/1000 (adj 15): empty #17
08-17 10:26:42.570  1037  1816 W libprocessgroup: failed to open /acct/uid_1000/pid_6446/cgroup.procs: No such file or directory
,08-17 10:26:42.616  1037  1099 W ProcessCpuTracker: Skipping unknown process pid 7761
08-17 10:26:42.617  1037  1099 W ProcessCpuTracker: Skipping unknown process pid 7764
,08-17 10:26:42.768  7853  7853 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-17 10:26:42.850  7853  7853 D LgDataFeature: LgDataFeature() Constructor: none
08-17 10:26:42.850  7853  7853 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-17 10:26:42.897  7853  7853 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-17 10:26:42.922  7853  7853 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-17 10:26:42.924  7853  7853 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-17 10:26:42.939  7853  7853 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-17 10:26:42.940  7853  7853 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-17 10:26:42.957  1037  2074 I ActivityManager: Killing 7177:com.google.android.setupwizard/u0a46 (adj 15): empty #17
08-17 10:26:42.988  1037  1658 W libprocessgroup: failed to open /acct/uid_10046/pid_7177/cgroup.procs: No such file or directory
,08-17 10:26:42.995  3484  5848 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-17 10:26:42.996  3484  5848 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@39addf9 on behalf of 7853
08-17 10:26:43.007  4606  7902 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,08-17 10:26:43.013  7853  7853 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
08-17 10:26:43.076  1037  1983 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7905 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-17 10:26:43.116  7853  7853 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-17 10:26:43.165  7905  7905 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-17 10:26:43.192  7905  7905 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-17 10:26:43.192  7905  7905 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-17 10:26:43.192  7905  7905 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-17 10:26:43.192  7905  7905 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-17 10:26:43.192  7905  7905 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-17 10:26:43.192  7905  7905 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,08-17 10:26:43.205  6996  6996 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-17 10:26:43.206  6996  6996 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-17 10:26:43.208  6996  6996 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-17 10:26:43.210  6996  6996 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,08-17 10:26:43.212  6996  6996 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-17 10:26:43.214  6996  6996 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-17 10:26:43.215  6996  6996 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-17 10:26:43.216  6996  6996 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1471422403215]
08-17 10:26:43.220  1037  2113 I ActivityManager: Killing 7197:com.android.chrome/u0a57 (adj 15): empty #17
08-17 10:26:43.231  6996  7927 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-17 10:26:43.326  6996  6996 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,08-17 10:26:43.329  6996  6996 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,08-17 10:26:43.330  6996  6996 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-17 10:26:43.331  6996  6996 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-17 10:26:43.332  6996  6996 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-17 10:26:43.333  6996  6996 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-17 10:26:43.334  6996  6996 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-17 10:26:43.334  1037  1985 W libprocessgroup: failed to open /acct/uid_10057/pid_7197/cgroup.procs: No such file or directory
08-17 10:26:43.345  6996  6996 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-17 10:26:43.571  1037  1054 V SIM_STK : Menu title from STK is T-Mobile
,08-17 10:26:43.594  4606  7902 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 586 ms] updated apps [took 586 ms] 
,08-17 10:26:44.402  1037  1963 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-17 10:26:44.402  1037  1963 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@1add06ab mBinding = false
,08-17 10:26:44.430  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-17 10:26:44.430  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-17 10:26:44.430  1037  1037 D Ulp_jni : JNI:system_update. Event-4
,08-17 10:26:44.433  1037  1120 D BluetoothManagerService: Message: 2
08-17 10:26:44.434  1037  1120 D BluetoothManagerService: Sending off request.
08-17 10:26:44.435  7066  7081 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-17 10:26:44.436  7066  7595 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-17 10:26:44.436  7066  7595 D BluetoothAdapterProperties: Setting state to 13
08-17 10:26:44.436  7066  7595 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-17 10:26:44.437  7066  7595 D BluetoothAdapterProperties: onBluetoothDisable()
08-17 10:26:44.437  7066  7595 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-17 10:26:44.439  7066  7599 D BluetoothAdapterProperties: Scan Mode:20
08-17 10:26:44.441  7066  7595 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-17 10:26:44.442  7066  7739 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-17 10:26:44.443  7066  7738 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-17 10:26:44.443  7066  7738 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-17 10:26:44.443  7066  7738 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-17 10:26:44.443  7066  7738 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-17 10:26:44.443  7066  7738 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-17 10:26:44.443  7066  7738 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-17 10:26:44.443  7066  7738 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-17 10:26:44.443  7066  7738 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,08-17 10:26:44.447  7066  7750 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-17 10:26:44.448  7066  7751 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-17 10:26:44.449  1037  1548 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
08-17 10:26:44.449  7066  7753 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-17 10:26:44.450  7066  7595 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-17 10:26:44.453  7066  7653 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-17 10:26:44.453  7066  7653 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-17 10:26:44.455  7066  7653 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-17 10:26:44.455  7066  7653 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-17 10:26:44.455  7066  7653 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-17 10:26:44.455  7066  7653 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-17 10:26:44.455  7066  7653 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 10:26:44.455  7066  7653 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-17 10:26:44.455  7066  7653 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 10:26:44.455  7066  7653 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-17 10:26:44.455  7066  7653 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-17 10:26:44.455  7066  7653 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-17 10:26:44.455  7066  7653 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-17 10:26:44.455  7066  7653 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-17 10:26:44.466  6772  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 10:26:44.466  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:26:44.466  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:26:44.466  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 10:26:44.466  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 10:26:44.466  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 10:26:44.466  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 10:26:44.466  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 10:26:44.466  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 10:26:44.471  6772  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 10:26:44.471  6772  6772 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 10:26:44.475  6772  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 10:26:44.475  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:26:44.475  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:26:44.475  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 10:26:44.475  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 10:26:44.475  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 10:26:44.475  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 10:26:44.475  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 10:26:44.475  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 10:26:44.475  6772  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 10:26:44.475  6772  6772 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 10:26:44.478  6772  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 10:26:44.481  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:26:44.481  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:26:44.481  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 10:26:44.481  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 10:26:44.481  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 10:26:44.481  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 10:26:44.481  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 10:26:44.481  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 10:26:44.482  6772  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 10:26:44.482  6772  6772 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 10:26:44.483  1037  1120 D BluetoothManagerService: Message: 60
08-17 10:26:44.483  1037  1120 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-17 10:26:44.483  1037  1120 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-17 10:26:44.486  1970  1970 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-17 10:26:44.487  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-17 10:26:44.492  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 10:26:44.496  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:26:44.505  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 10:26:44.513  7066  7066 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-17 10:26:44.513  7066  7066 D BluetoothMapService: STATE_TURNING_OFF
08-17 10:26:44.513  7066  7066 V BluetoothMapService: Handler(): got msg=4
08-17 10:26:44.513  7066  7066 D BluetoothMapService: MAP Service closeService in
08-17 10:26:44.513  7066  7066 D BluetoothMapMasInstance: MAP Service shutdown
08-17 10:26:44.514  7066  7066 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-17 10:26:44.514  7066  7066 V BluetoothMapService: MAP Service closeService out
08-17 10:26:44.515  7066  7066 V BtOppService: Receiver DISABLED_ACTION 
08-17 10:26:44.515  7066  7066 I BtOppRfcommListener: stopping Accept Thread
08-17 10:26:44.515  7066  7066 V BtOppRfcommListener: close mBtServerSocket
08-17 10:26:44.516  7066  7750 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-17 10:26:44.516  7066  7066 V BtOppRfcommListener: waiting for thread to terminate
08-17 10:26:44.516  7066  7066 V BtOppRfcommListener: done waiting for thread to terminate
08-17 10:26:44.522  6934  6934 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
,08-17 10:26:44.526  6934  6934 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-17 10:26:44.534  7066  7066 V BtOppService: onDestroy
08-17 10:26:44.537  7066  7066 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
,08-17 10:26:44.542  7066  7066 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-17 10:26:44.542  7066  7066 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-17 10:26:44.542  7066  7066 V BluetoothPbapReceiver: ***********state = 13
08-17 10:26:44.544  7066  7066 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-17 10:26:44.545  7066  7066 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-17 10:26:44.545  7066  7066 V BluetoothPbapService: state: 13
08-17 10:26:44.545  7066  7066 V BluetoothPbapService: Pbap Service closeService in
08-17 10:26:44.548  2249  2249 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-17 10:26:44.554  7066  7066 V BluetoothPbapService: successfully stopped pbap service
,08-17 10:26:44.554  7066  7066 V BluetoothPbapService: Pbap Service closeService out
08-17 10:26:44.555  7066  7066 V BluetoothPbapService: Pbap Service onDestroy
08-17 10:26:44.555  7066  7066 V BluetoothPbapService: Pbap Service closeService in
08-17 10:26:44.555  7066  7066 V BluetoothPbapService: Pbap Service closeService out
08-17 10:26:44.555  7066  7066 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-17 10:26:44.576  6934  6934 D DockEventReceiver: finishStartingService: stopping service
,08-17 10:26:44.579  6934  6934 D BluetoothPbap: Proxy object disconnected
08-17 10:26:44.579  6934  6934 D PbapServerProfile: Bluetooth service disconnected
08-17 10:26:44.587  6934  6934 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-17 10:26:44.594  6934  6934 D BluetoothPermissionRequest: onReceive
08-17 10:26:44.594  6934  6934 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-17 10:26:44.600  6934  6934 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-17 10:26:44.604  7066  7066 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-17 10:26:44.604  7066  7066 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,08-17 10:26:44.606  7066  7066 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-17 10:26:44.610  7066  7066 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-17 10:26:44.610  7066  7066 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-17 10:26:44.611  7066  7066 V BluetoothFtpService: Ftp Service onStartCommand
08-17 10:26:44.612  7066  7066 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-17 10:26:44.612  7066  7066 V BluetoothFtpService: Ftp Service closeService
08-17 10:26:44.612  7066  7066 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-17 10:26:44.614  7066  7066 V BluetoothFtpService: successfully stopped ftp service
08-17 10:26:44.614  7066  7066 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-17 10:26:44.614  7066  7066 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-17 10:26:44.614  7066  7066 V BluetoothSapReceiver: SapReceiver onReceive 
08-17 10:26:44.615  7066  7066 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-17 10:26:44.615  7066  7066 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-17 10:26:44.615  7066  7066 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-17 10:26:44.616  7066  7066 V BluetoothFtpService: Ftp Service onDestroy
08-17 10:26:44.616  7066  7066 V BluetoothFtpService: Ftp Service closeService
,08-17 10:26:44.620  7066  7066 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,08-17 10:26:44.620  7066  7066 V BluetoothSapService: state: 13
08-17 10:26:44.620  7066  7066 V BluetoothSapService: Stopping SAP server process
08-17 10:26:44.622  7066  7066 V BluetoothSapService: Sap Service closeSapService in
08-17 10:26:44.622  7066  7066 V BluetoothSapService: Close listen Socket : 
08-17 10:26:44.622  7066  7066 V BluetoothSapService: Close rfcomm Socket : 
08-17 10:26:44.622  7066  7066 V BluetoothSapService: Close sapd  Socket : 
,08-17 10:26:44.623  7066  7066 V BluetoothSapService: Sap Service closeSapService out,
08-17 10:26:44.623  7066  7066 V BluetoothSapService: Sap Service onDestroy
,08-17 10:26:44.623  7066  7066 V BluetoothSapService: Sap Service closeSapService in
08-17 10:26:44.623  7066  7066 V BluetoothSapService: Close listen Socket : 
08-17 10:26:44.623  7066  7066 V BluetoothSapService: Close rfcomm Socket : 
08-17 10:26:44.623  7066  7066 V BluetoothSapService: Close sapd  Socket : 
08-17 10:26:44.625  7066  7066 V BluetoothSapService: Sap Service closeSapService out
,08-17 10:26:45.456  7066  7599 D bt_hci_bdroid: cleanup
,08-17 10:26:45.470  7066  7655 I bt_lpm  : LPM is already off!!!
08-17 10:26:45.471  7066  7708 I bt_userial_mct: exiting userial_read_thread
08-17 10:26:45.471  7066  7708 D bt_userial_mct: Leaving userial_evt_read_thread()
,08-17 10:26:45.471  7066  7653 W bt-btif : ag scb idx 1 not allocated
08-17 10:26:45.471  7066  7653 E bt-btif : BTA AG is already disabled, ignoring ...
,08-17 10:26:45.471  7066  7653 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-17 10:26:45.471  7066  7653 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 10:26:45.471  7066  7653 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-17 10:26:45.471  7066  7653 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 10:26:45.471  7066  7653 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-17 10:26:45.471  7066  7653 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-17 10:26:45.471  7066  7653 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-17 10:26:45.472  7066  7653 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 10:26:45.472  7066  7653 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-17 10:26:45.472  7066  7653 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 10:26:45.472  7066  7653 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-17 10:26:45.472  7066  7653 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-17 10:26:45.472  7066  7653 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-17 10:26:45.472  7066  7653 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 10:26:45.472  7066  7653 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-17 10:26:45.472  7066  7653 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 10:26:45.472  7066  7653 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-17 10:26:45.472  7066  7653 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-17 10:26:45.474  7066  7653 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-17 10:26:45.474  7066  7599 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-17 10:26:45.474  7066  7655 I bt_vendor: hw_epilog_process
08-17 10:26:45.474  7066  7599 D bt_hci_bdroid: cleanup Finalizing cleanup
08-17 10:26:45.474  7066  7599 D bt_userial_mct: userial_close
08-17 10:26:45.474  7066  7599 E bt_userial_mct: pthread_join() FAILED result:3
08-17 10:26:45.475  7066  7599 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-17 10:26:45.479  7066  7599 D bt_hci_bdroid: set_power 0
08-17 10:26:45.479  7066  7599 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-17 10:26:45.479  7066  7599 I bt_vendor: bluetooth satus is on
08-17 10:26:45.479  7066  7599 I bt_vendor: bt-vendor : resetting BT status
08-17 10:26:45.479  7066  7599 I bt_vendor: Starting hciattach daemon
08-17 10:26:45.479  7066  7599 I bt_vendor: try to set false
,08-17 10:26:45.486  7066  7599 I bt_vendor: Starting hciattach daemon
08-17 10:26:45.486  7066  7599 I bt_vendor: try to set false
08-17 10:26:45.488  7066  7599 I bt_vendor: cleanup
08-17 10:26:45.489  7066  7653 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-17 10:26:45.490  7066  7599 I GKI_LINUX: GKI_exit_task 0 done
08-17 10:26:45.490  7066  7599 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-17 10:26:45.492  7066  7595 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-17 10:26:45.499  7066  7066 D HeadsetService: Received stop request...Stopping profile...
,08-17 10:26:45.504  7066  7595 D BluetoothAdapterState: Stopping profile services that were post enabled
08-17 10:26:45.504  7066  7066 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-17 10:26:45.504  7066  7066 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-17 10:26:45.504  7066  7066 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@131639a9
08-17 10:26:45.505  7066  7626 D HeadsetStateMachine: Exit Disconnected: -1
08-17 10:26:45.509  1882  1882 D BluetoothHeadset: Proxy object disconnected
08-17 10:26:45.509  1882  1882 D BluetoothHeadset: Proxy object disconnected
08-17 10:26:45.509  1037  1037 D BluetoothHeadset: Proxy object disconnected
08-17 10:26:45.509  1037  1037 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-17 10:26:45.510  7066  7066 D A2dpService: Received stop request...Stopping profile...
08-17 10:26:45.512  7066  7642 D A2dpStateMachine: Exit Disconnected: -1
,08-17 10:26:45.515  7066  7066 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-17 10:26:45.516  7066  7066 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-17 10:26:45.516  7066  7066 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-17 10:26:45.516  7066  7066 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@131639a9
08-17 10:26:45.519  1037  1037 D BluetoothA2dp: Proxy object disconnected
08-17 10:26:45.519  1037  1037 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-17 10:26:45.519  7066  7066 D HidService: Received stop request...Stopping profile...
08-17 10:26:45.519  7066  7066 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@131639a9
08-17 10:26:45.521  7066  7066 D HealthService: Received stop request...Stopping profile...
08-17 10:26:45.522  7066  7066 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@131639a9
08-17 10:26:45.524  7066  7066 D PanService: Received stop request...Stopping profile...
,08-17 10:26:45.527  7066  7066 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@131639a9
08-17 10:26:45.529  7066  7066 D BtGatt.DebugUtils: handleDebugAction() action=null
08-17 10:26:45.530  7066  7066 D BtGatt.GattService: Received stop request...Stopping profile...
08-17 10:26:45.530  7066  7066 D BtGatt.GattService: stop()
08-17 10:26:45.530  7066  7066 D BtGatt.AdvertiseManager: advertise clients cleared
08-17 10:26:45.531  7066  7066 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@131639a9
08-17 10:26:45.532  7066  7066 D BluetoothMapService: Received stop request...Stopping profile...
08-17 10:26:45.532  7066  7066 D BluetoothMapService: stop()
08-17 10:26:45.533  7066  7066 D BluetoothMapEmailAppObserver: deinitObservers()
08-17 10:26:45.533  7066  7066 D BluetoothMapEmailAppObserver: removeReceiver()
08-17 10:26:45.534  7066  7066 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@131639a9
08-17 10:26:45.534  1882  1882 D BluetoothHeadset: Proxy object disconnected
08-17 10:26:45.535  7066  7066 D HeadsetStateMachine: Unbinding service...
08-17 10:26:45.538  7066  7066 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-17 10:26:45.538  7066  7066 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-17 10:26:45.538  7066  7066 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-17 10:26:45.538  7066  7066 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-17 10:26:45.538  7066  7066 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-17 10:26:45.538  7066  7066 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-17 10:26:45.538  7066  7066 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-17 10:26:45.539  7066  7066 I BluetoothA2dpServiceJni: cleanupNative
,08-17 10:26:45.541  7066  7643 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-17 10:26:45.542  7066  7066 I GKI_LINUX: GKI_exit_task 2 done
08-17 10:26:45.542  7066  7066 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-17 10:26:45.543  7066  7066 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-17 10:26:45.543  7066  7066 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-17 10:26:45.543  7066  7066 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-17 10:26:45.543  7066  7066 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-17 10:26:45.543  7066  7066 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-17 10:26:45.544  7066  7066 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-17 10:26:45.544  7066  7066 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-17 10:26:45.545  7066  7066 V BluetoothMapService: Handler(): got msg=4
08-17 10:26:45.545  7066  7066 D BluetoothMapService: MAP Service closeService in
08-17 10:26:45.545  7066  7066 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-17 10:26:45.545  7066  7066 V BluetoothMapService: MAP Service closeService out
08-17 10:26:45.546  7066  7595 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-17 10:26:45.546  7066  7595 D BluetoothAdapterProperties: Setting state to 10
08-17 10:26:45.546  7066  7595 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-17 10:26:45.547  7066  7066 D BluetoothMapService: cleanup()
08-17 10:26:45.547  7066  7066 D BluetoothMapService: MAP Service closeService in
08-17 10:26:45.547  7066  7066 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-17 10:26:45.547  7066  7066 V BluetoothMapService: MAP Service closeService out
08-17 10:26:45.549  1037  1120 D BluetoothManagerService: Message: 60
08-17 10:26:45.549  1037  1120 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-17 10:26:45.549  1037  1120 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-17 10:26:45.550  7066  7595 I BluetoothAdapterState: Entering OffState
,08-17 10:26:45.555  6934  6949 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-17 10:26:45.555  6934  6949 D BluetoothPbap: onBluetoothStateChange: up=false
08-17 10:26:45.556  6934  6949 D BluetoothMap: onBluetoothStateChange: up=false
08-17 10:26:45.557  6934  6949 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 10:26:45.557  1882  2572 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 10:26:45.558  1037  1120 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 10:26:45.558  6934  6949 D BluetoothA2dp: onBluetoothStateChange: up=false
08-17 10:26:45.559  1882  2571 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 10:26:45.561  6934  6949 D BluetoothPan: onBluetoothStateChange on: false
08-17 10:26:45.561  1882  1897 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-17 10:26:45.563  1037  1120 D BluetoothA2dp: onBluetoothStateChange: up=false
08-17 10:26:45.564  1037  1120 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-17 10:26:45.564  1037  1120 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-17 10:26:45.568  1037  1120 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-17 10:26:45.568  1037  1120 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-17 10:26:45.568  1037  1120 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@1add06ab mBinding = false
08-17 10:26:45.569  1037  1120 D BluetoothManagerService: Sending unbind request.
08-17 10:26:45.573  7066  7599 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-17 10:26:45.576  7066  7066 I GKI_LINUX: GKI_exit_task 1 done
08-17 10:26:45.576  7066  7066 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-17 10:26:45.577  7066  7066 I BluetoothServiceJni: cleanupNative: return from cleanup
08-17 10:26:45.577  7066  7066 I art     : --- WEIRD: removing null entry 248
08-17 10:26:45.577  7066  7066 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-17 10:26:45.577  7066  7066 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-17 10:26:45.578  7066  7066 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-17 10:26:45.579  1037  1120 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-17 10:26:45.581  7066  7066 I art     : System.exit called, status: 0
08-17 10:26:45.581  7066  7066 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-17 10:26:45.601   324  1388 V AudioFlinger: 7066 died, releasing its sessions
08-17 10:26:45.601   324  1388 V AudioFlinger:  pid 1882 @ 0
08-17 10:26:45.601   324  1388 V AudioFlinger:  pid 3438 @ 1
08-17 10:26:45.601   324  1388 V AudioFlinger:  pid 3438 @ 2
,08-17 10:26:45.605  1970  1970 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
08-17 10:26:45.606  1970  2183 D LGBluetoothAPIService: Message: 101
08-17 10:26:45.606  1970  2183 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
08-17 10:26:45.606  1970  2183 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
08-17 10:26:45.606  1970  2183 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
08-17 10:26:45.607  6934  6934 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-17 10:26:45.649  1037  1578 I ActivityManager: Process com.android.bluetooth (pid 7066) has died
08-17 10:26:45.649  1037  1578 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms
08-17 10:26:45.649  1037  1578 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 14000ms
,08-17 10:26:45.656  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 10:26:45.657  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:26:45.657  1970  1970 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-17 10:26:45.658  1970  2183 D LGBluetoothAPIService: Message: 2
,08-17 10:26:45.658  1970  2183 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
08-17 10:26:45.658  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:26:45.658  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-17 10:26:45.659  6934  6934 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-17 10:26:45.659  6934  6934 D LGBluetoothEventManager: [BTUI] clear device connection state
08-17 10:26:45.662  6934  6934 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-17 10:26:45.664  1605  1605 D BluetoothAdapter: 171690696: getState() :  mService = null. Returning STATE_OFF
08-17 10:26:45.664  1605  1605 D BluetoothAdapter: 171690696: getState() :  mService = null. Returning STATE_OFF
,08-17 10:26:45.732  1037  2113 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7983 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-17 10:26:45.733  6934  6934 D DockEventReceiver: finishStartingService: stopping service
,08-17 10:26:45.760   344   344 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 467us total 28.542ms
,08-17 10:26:45.782   344   344 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 455us total 21.069ms
,08-17 10:26:45.787  7983  7983 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-17 10:26:45.787  7983  7983 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-17 10:26:45.788  7983  7983 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-17 10:26:45.788  7983  7983 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-17 10:26:45.806  7983  7983 D BluetoothAdapterApp: Loading JNI Library
,08-17 10:26:45.824   344   344 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 450us total 39.162ms
,08-17 10:26:45.843  7983  7983 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@76c4d71 Instance Count = 1
,08-17 10:26:45.849  7983  7983 D BluetoothAdapterApp: onCreate
,08-17 10:26:45.876  7983  7983 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-17 10:26:45.876  7983  7983 D ProfileConfigQcom: Adding HeadsetService
08-17 10:26:45.877  7983  7983 D ProfileConfigQcom: [BTUI] A2dpService is supported
,08-17 10:26:45.877  7983  7983 D ProfileConfigQcom: Adding A2dpService
08-17 10:26:45.877  7983  7983 D ProfileConfigQcom: [BTUI] HidService is supported
08-17 10:26:45.877  7983  7983 D ProfileConfigQcom: Adding HidService
08-17 10:26:45.878  7983  7983 D ProfileConfigQcom: [BTUI] HealthService is supported
08-17 10:26:45.878  7983  7983 D ProfileConfigQcom: Adding HealthService
08-17 10:26:45.878  7983  7983 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-17 10:26:45.879  7983  7983 D ProfileConfigQcom: [BTUI] PanService is supported
08-17 10:26:45.879  7983  7983 D ProfileConfigQcom: Adding PanService
08-17 10:26:45.879  7983  7983 D ProfileConfigQcom: [BTUI] GattService is supported
08-17 10:26:45.880  7983  7983 D ProfileConfigQcom: Adding GattService
08-17 10:26:45.880  7983  7983 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-17 10:26:45.880  7983  7983 D ProfileConfigQcom: Adding BluetoothMapService
08-17 10:26:45.880  7983  7983 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-17 10:26:45.881  7983  7983 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-17 10:26:45.883  7983  7983 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-17 10:26:45.883  7983  7983 V BluetoothPbapReceiver: ***********state = 10
08-17 10:26:45.885  7983  7983 V LGMDMManagerInternal: Create singleton instance
08-17 10:26:45.983  2249  2249 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-17 10:26:45.986  6934  6934 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-17 10:26:45.989  7983  7983 D LGBluetoothAPIServer: [BTUI] onCreate()
08-17 10:26:45.990  7983  7983 D LGBluetoothAPIServer: [BTUI] onBind()
08-17 10:26:46.005  1970  1970 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
,08-17 10:26:46.005  1970  2183 D LGBluetoothAPIService: Message: 100
08-17 10:26:46.005  1970  2183 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-17 10:26:46.009  6934  6934 D BluetoothPermissionRequest: onReceive
08-17 10:26:46.013  6934  6934 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-17 10:26:46.013  6934  6934 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-17 10:26:46.017  6934  6934 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-17 10:26:46.024  7983  7983 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-17 10:26:46.030  7983  7983 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-17 10:26:46.034  7983  7983 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-17 10:26:46.034  7983  7983 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-17 10:26:46.034  7983  7983 V BluetoothSapReceiver: SapReceiver onReceive 
08-17 10:26:46.036  7983  7983 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-17 10:26:46.036  7983  7983 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-17 10:26:46.047  7661  7661 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-17 10:26:46.438  7700  7793 D UEI.SmartControl: Internal timer expired: 1
08-17 10:26:46.439  7700  7793 D UEI.SmartControl: unbind internal service
,08-17 10:26:46.651  7700  7765 D serial_port: close(fd = 25)
,08-17 10:26:46.663  7700  7765 I UEI.SmartControl: Serial port is closed.
,08-17 10:26:47.047  1037  1384 V AlarmManager: ELAPSED_WAKEUP set : Alarm{37ae72c6 type 2 when 384210 com.google.android.gms} when 384210
,08-17 10:26:47.064   320  8014 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-17 10:26:47.072  1037  1118 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-17 10:26:49.519  6772  6842 D io.jxcore.node.ConnectivityMonitor: stop
08-17 10:26:49.519  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 10:26:49.531  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:26:49.531  6772  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2e9f30ac removed from the list
08-17 10:26:49.531  6772  6842 D io.jxcore.node.ConnectivityMonitor: stop
08-17 10:26:49.531  6772  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:26:49.531  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:26:49.532  6772  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 10:26:49.532  6772  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1b46850a added. We now have 4 listener(s)
08-17 10:26:49.532  6772  6842 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 10:26:49.533  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:26:49.533  6772  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1b46850a removed from the list
08-17 10:26:49.533  6772  6842 D io.jxcore.node.ConnectivityMonitor: stop
08-17 10:26:49.533  6772  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:26:49.533  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:26:49.534  6772  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 10:26:49.534  6772  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@94be17b added. We now have 4 listener(s)
08-17 10:26:49.534  6772  6842 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 10:26:49.536  1037  1658 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 10:26:49.536  1037  1658 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
08-17 10:26:49.537  1037  1120 D BluetoothManagerService: Message: 2
,08-17 10:26:54.546  6772  6842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 10:26:54.555  1037  1963 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 10:26:54.555  1037  1963 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-17 10:26:54.579  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-17 10:26:54.579  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-17 10:26:54.579  1037  1037 D Ulp_jni : JNI:system_update. Event-4
08-17 10:26:54.580  1037  1120 D BluetoothManagerService: Message: 1
08-17 10:26:54.580  1037  1120 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-17 10:26:54.607  1037  1120 D BluetoothManagerService: Message: 20
08-17 10:26:54.607  1037  1120 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1309a023:true
,08-17 10:26:54.611  7983  7983 D BluetoothAdapterState: make
08-17 10:26:54.616  7983  7983 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-17 10:26:54.616  7983  7983 I bluedroid-qcom: init
08-17 10:26:54.617  7983  8018 I BluetoothAdapterState: Entering OffState
08-17 10:26:54.618  7983  7983 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-17 10:26:54.618  7983  7983 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-17 10:26:54.618  7983  7983 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-17 10:26:54.618  7983  7983 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-17 10:26:54.618  7983  7983 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-17 10:26:54.620  7983  7983 I bluedroid-qcom: get_profile_interface socket
08-17 10:26:54.620  7983  7983 I bluedroid-qcom: get_profile_interface map_client
,08-17 10:26:54.625  7983  8022 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-17 10:26:54.609  8021  8021 W bdaddr_loader: type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 10:26:54.619  8021  8021 W bdaddr_loader: type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 10:26:54.640  1037  1037 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,08-17 10:26:54.642  1037  1120 D BluetoothManagerService: Message: 40
08-17 10:26:54.642  1037  1120 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-17 10:26:54.643  7983  7999 I bluedroid-qcom: config_hci_snoop_log
08-17 10:26:54.645  1037  1120 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-17 10:26:54.645  1037  1120 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-17 10:26:54.647  8021  8021 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-17 10:26:54.647  8021  8021 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-17 10:26:54.647  8021  8021 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-17 10:26:54.650  8021  8021 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-17 10:26:54.652  7983  8022 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-17 10:26:54.657  8021  8021 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-17 10:26:54.657  8021  8021 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-17 10:26:54.659  1037  1037 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-17 10:26:54.659  1037  1037 D BluetoothManagerService: Stored Bluetooth name: G3
08-17 10:26:54.660  7983  8022 D BluetoothAdapterProperties: Name is: G3
08-17 10:26:54.663  7983  8018 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-17 10:26:54.663  7983  8018 D BluetoothAdapterProperties: Setting state to 11
08-17 10:26:54.664  7983  8018 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-17 10:26:54.664  1037  1120 D BluetoothManagerService: Message: 60
08-17 10:26:54.665  1037  1120 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-17 10:26:54.665  1037  1120 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-17 10:26:54.667  7983  8018 I LGBluetoothServiceJni: classInitNative: succeeds
,08-17 10:26:54.672  1970  1970 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-17 10:26:54.673  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-17 10:26:54.677  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:26:54.681  6934  6934 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
,08-17 10:26:54.684  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:26:54.688  7983  7983 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-17 10:26:54.688  7983  7983 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-17 10:26:54.688  7983  7983 V BluetoothPbapReceiver: ***********state = 11
08-17 10:26:54.693  2249  2249 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-17 10:26:54.720  7983  8018 D BluetoothBondStateMachine: make
,08-17 10:26:54.723  6934  6934 D BluetoothPermissionRequest: onReceive
08-17 10:26:54.724  7983  8018 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27be3b2e
08-17 10:26:54.725  7983  8018 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-17 10:26:54.725  7983  8038 I BluetoothBondStateMachine: StableState(): Entering Off State
08-17 10:26:54.725  7983  8018 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27be3b2e
08-17 10:26:54.725  7983  8018 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-17 10:26:54.725  7983  8018 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-17 10:26:54.727  6934  6934 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-17 10:26:54.733  7983  8018 E BluetoothAdapterService: File transfer profiles supported!!
,08-17 10:26:54.735  7983  7983 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-17 10:26:54.738  7983  7983 V BluetoothSapReceiver: [BTUI] checkServiceStart
,08-17 10:26:54.738  7983  7983 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-17 10:26:54.738  7983  7983 V BluetoothSapReceiver: SapReceiver onReceive 
08-17 10:26:54.739  7983  7983 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-17 10:26:54.739  7983  7983 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-17 10:26:54.742  7983  8018 E BluetoothAdapterService: File transfer profiles supported!!
08-17 10:26:54.749  7983  7983 D HeadsetService: Received start request. Starting profile...
08-17 10:26:54.750  7983  7983 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-17 10:26:54.750  7983  7983 D LGBluetoothHfpAdapter: Version 1.6
08-17 10:26:54.754  7983  7983 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-17 10:26:54.755  7983  7983 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-17 10:26:54.756  7983  7983 D HeadsetStateMachine: make
08-17 10:26:54.757  7983  8018 E BluetoothAdapterService: File transfer profiles supported!!
,08-17 10:26:54.763  7983  8018 E BluetoothAdapterService: File transfer profiles supported!!
08-17 10:26:54.771  7983  8018 E BluetoothAdapterService: File transfer profiles supported!!
,08-17 10:26:54.777  7983  8018 E BluetoothAdapterService: File transfer profiles supported!!
08-17 10:26:54.784  7983  8018 E BluetoothAdapterService: File transfer profiles supported!!
,08-17 10:26:54.797  7983  7983 D LgDataFeature: LgDataFeature() Constructor: none
,08-17 10:26:54.797  7983  7983 D LgDataFeature: LgDataFeature() Constructor Done, null
08-17 10:26:54.802  7983  7983 D HeadsetStateMachine: max_hf_connections = 1
08-17 10:26:54.802  7983  7983 I bluedroid-qcom: get_profile_interface handsfree
08-17 10:26:54.804  7983  7983 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-17 10:26:54.805   324  1388 V AudioPolicyService: registerClient() client 0xb04107c0, uid 1002
08-17 10:26:54.805   324  4037 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-17 10:26:54.805   324  4037 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-17 10:26:54.805   324  4037 V AudioPolicyManagerEx: getOutput() returns output 2
08-17 10:26:54.806  7983  7983 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-17 10:26:54.806   324   324 V AudioFlinger: registerClient() client 0xb101faf0, pid 7983
08-17 10:26:54.806   324  1383 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-17 10:26:54.806   324  1383 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-17 10:26:54.807  7983  7983 V ToneGenerator: Create Track: 0xb4928080
08-17 10:26:54.807  7983  7983 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-17 10:26:54.807  7983  7983 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
,08-17 10:26:54.807   324  1389 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-17 10:26:54.807   324  1389 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-17 10:26:54.807   324  1389 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-17 10:26:54.807   324  1389 V AudioPolicyManagerEx: getOutput() returns output 2
08-17 10:26:54.807  7983  7983 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-17 10:26:54.807  3438  3453 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
,08-17 10:26:54.807  3438  3453 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-17 10:26:54.807   324  1382 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-17 10:26:54.807   324  1382 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-17 10:26:54.807  3438  3454 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-17 10:26:54.807  3438  3454 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-17 10:26:54.808  1882  1898 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-17 10:26:54.808  1882  1898 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-17 10:26:54.808  1882  1898 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-17 10:26:54.808  1882  1898 V AudioSystem: ioConfigChanged() opening already existing output! 2
,08-17 10:26:54.808  1605  1622 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-17 10:26:54.808  1605  1622 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-17 10:26:54.808  1605  1622 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-17 10:26:54.808  1605  1622 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-17 10:26:54.808   324  4037 I AudioFlinger: isAudioPlaybackHookOn() false
08-17 10:26:54.809  7983  8018 V LGMDMManager: Create singleton instance
08-17 10:26:54.810  1037  1985 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-17 10:26:54.810  1037  1985 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-17 10:26:54.810  1037  1985 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-17 10:26:54.810  1037  1985 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-17 10:26:54.810  7983  7999 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-17 10:26:54.810  7983  7999 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-17 10:26:54.810  7983  7999 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-17 10:26:54.810  7983  7999 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-17 10:26:54.810   324  1388 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-17 10:26:54.810   324  1388 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-17 10:26:54.810   324  1388 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-17 10:26:54.810   324  1388 V AudioPolicyManagerEx: getOutput() returns output 2
08-17 10:26:54.810  7983  7983 V AudioSystem: getLatency() output 2, latency 50
08-17 10:26:54.810  7983  7983 V AudioSystem: getFrameCount() output 2, frameCount 960
08-17 10:26:54.811  7983  7983 V AudioTrack: createTrack_l() output 2 afLatency 50
08-17 10:26:54.811   324  1389 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-17 10:26:54.811   324  1389 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-17 10:26:54.811   324  1389 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-17 10:26:54.811   324  1389 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-17 10:26:54.811   324  1389 V AudioFlinger: createTrack() lSessionId: 23
08-17 10:26:54.813  7983  7983 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
,08-17 10:26:54.814   324   324 V AudioFlinger: acquiring 23 from 7983, for 7983
,08-17 10:26:54.814   324   324 V AudioFlinger:  added new entry for 23
08-17 10:26:54.815  7983  7983 V ToneGenerator: ToneGenerator INIT OK, time: 391996
08-17 10:26:54.815  7983  7983 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27be3b2e
08-17 10:26:54.816  7983  8041 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-17 10:26:54.816  7983  8041 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-17 10:26:54.816  7983  8041 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-17 10:26:54.816  7983  8041 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-17 10:26:54.816   324  4037 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7983
08-17 10:26:54.820   324  4037 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-17 10:26:54.820   324  4037 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-17 10:26:54.820   324  4037 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-17 10:26:54.820   324  4037 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-17 10:26:54.820   324  4037 V voice   : voice_set_parameters: exit with code(0)
08-17 10:26:54.820   324  4037 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-17 10:26:54.820   324  4037 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-17 10:26:54.820   324  4037 V msm8974_platform: platform_set_parameters: exit with code(0)
08-17 10:26:54.820   324  4037 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-17 10:26:54.820   324  4037 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-17 10:26:54.820   324  4037 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-17 10:26:54.821  7983  8041 V ToneGenerator: ToneGenerator destructor
08-17 10:26:54.821  7983  8041 V ToneGenerator: stopTone
08-17 10:26:54.821  7983  8018 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-17 10:26:54.821  7983  8041 V ToneGenerator: Delete Track: 0xb4928080
08-17 10:26:54.821   324  1388 V AudioPolicyService: AudioCommandThread() adding release output 2
08-17 10:26:54.821   324  1388 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-17 10:26:54.821   324  1388 V AudioFlinger: PlaybackThread::Track destructor
08-17 10:26:54.821   324  1275 V AudioPolicyService: AudioCommandThread() waking up
08-17 10:26:54.821   324  1388 V AudioFlinger: removeClient_l() pid 7983, calling pid 324
08-17 10:26:54.821   324  1275 V AudioPolicyService: AudioCommandThread() processing release output 2
08-17 10:26:54.821   324  1275 V AudioPolicyManager: releaseOutput() 2
08-17 10:26:54.821   324  1275 V AudioPolicyService: AudioCommandThread() going to sleep
08-17 10:26:54.822  7983  8041 V AudioTrack: ~AudioTrack, releasing session id from 7983 on behalf of 7983
08-17 10:26:54.822   324  4037 V AudioFlinger: releasing 23 from 7983 for 7983
08-17 10:26:54.822   324  4037 V AudioFlinger:  decremented refcount to 0
08-17 10:26:54.822   324  4037 V AudioFlinger: purging stale effects
08-17 10:26:54.960  1037  1999 I art     : Explicit concurrent mark sweep GC freed 27830(1319KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 3.194ms total 152.174ms
,08-17 10:26:54.964  7983  7983 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27be3b2e
08-17 10:26:54.969  7983  7983 D A2dpService: Received start request. Starting profile...
08-17 10:26:54.971  7983  7983 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-17 10:26:54.973  7983  7983 V Avrcp   : make
,08-17 10:26:54.975  7983  7983 D Avrcp   : [BTUI] Use Native AVRCP : init jni
,08-17 10:26:54.975  7983  7983 I bluedroid-qcom: get_profile_interface avrcp
08-17 10:26:54.992  7983  7983 V AudioManager: registerRemoteController: size of Media player list: 0
,08-17 10:26:54.994  7983  7983 E AudioManager: No RCC entry present to update
,08-17 10:26:54.994  7983  7983 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-17 10:26:54.998  7983  7983 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-17 10:26:55.000  7983  7983 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-17 10:26:55.000  7983  7983 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-17 10:26:55.004  7983  7983 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-17 10:26:55.126  1037  2028 V SIM_STK : Menu title from STK is T-Mobile
08-17 10:26:55.126  1037  2028 V SIM_STK : Menu title from STK is T-Mobile
,08-17 10:26:55.243  1037  1740 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-17 10:26:55.262  7983  7983 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,08-17 10:26:55.269  7983  7983 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-17 10:26:55.270  7983  7983 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-17 10:26:55.270  7983  7983 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-17 10:26:55.270  7983  7983 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-17 10:26:55.270  7983  7983 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-17 10:26:55.270  7983  7983 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-17 10:26:55.270  7983  7983 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-17 10:26:55.270  7983  7983 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-17 10:26:55.270  7983  7983 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-17 10:26:55.271  7983  7983 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-17 10:26:55.271  7983  7983 I BluetoothA2dpServiceJni: classInitNative
08-17 10:26:55.271  7983  7983 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-17 10:26:55.271  7983  7983 D A2dpStateMachine: make
08-17 10:26:55.274  7983  7983 I bluedroid-qcom: get_profile_interface a2dp
08-17 10:26:55.274  7983  8050 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-17 10:26:55.277  7983  7983 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-17 10:26:55.277  7983  7983 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-17 10:26:55.278  7983  7983 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27be3b2e
08-17 10:26:55.279  7983  8049 D A2dpStateMachine: Enter Disconnected: -2
08-17 10:26:55.279  7983  7983 I BluetoothHidServiceJni: classInitNative: succeeds
,08-17 10:26:55.283  7983  7983 D HidService: Received start request. Starting profile...
08-17 10:26:55.283  7983  7983 I bluedroid-qcom: get_profile_interface hidhost
08-17 10:26:55.283  7983  7983 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27be3b2e
08-17 10:26:55.286  7983  7983 I BluetoothHealthServiceJni: classInitNative: succeeds
08-17 10:26:55.290  7983  7983 D HealthService: Received start request. Starting profile...
08-17 10:26:55.292  7983  7983 I bluedroid-qcom: get_profile_interface health
08-17 10:26:55.292  7983  7983 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-17 10:26:55.292  7983  7983 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27be3b2e
08-17 10:26:55.293  7983  7983 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-17 10:26:55.294  7983  7983 D PanService: Received start request. Starting profile...
08-17 10:26:55.295  7983  7983 D BluetoothPanServiceJni: initializeNative(L110): pan
08-17 10:26:55.295  7983  7983 I bluedroid-qcom: get_profile_interface pan
,08-17 10:26:55.303  7983  7983 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-17 10:26:55.303  7983  7983 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27be3b2e
08-17 10:26:55.305  7983  7983 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
,08-17 10:26:55.311  7983  7983 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-17 10:26:55.312  7983  7983 D BtGatt.GattService: Received start request. Starting profile...
08-17 10:26:55.312  7983  7983 D BtGatt.GattService: start()
08-17 10:26:55.312  7983  7983 I bluedroid-qcom: get_profile_interface gatt
08-17 10:26:55.312  7983  7983 D BtGatt.AdvertiseManager: advertise manager created
08-17 10:26:55.323  7983  7983 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27be3b2e
08-17 10:26:55.324  7983  7983 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27be3b2e
08-17 10:26:55.325  7983  7983 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-17 10:26:55.326  7983  7983 V BluetoothMapService: BluetoothMapBinder()
08-17 10:26:55.326  7983  7983 D BluetoothMapService: Received start request. Starting profile...
,08-17 10:26:55.326  7983  7983 D BluetoothMapService: start()
,08-17 10:26:55.330  7983  7983 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-17 10:26:55.330  7983  7983 D BluetoothMapEmailAppObserver: createReceiver()
08-17 10:26:55.331  7983  7983 D BluetoothMapEmailAppObserver: initObservers()
08-17 10:26:55.332  7983  7983 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-17 10:26:55.341  7983  7983 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27be3b2e
08-17 10:26:55.341  7983  7983 D HeadsetStateMachine: Proxy object connected
08-17 10:26:55.342  7983  7983 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-17 10:26:55.342  7983  7983 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
,08-17 10:26:55.348  7983  7983 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-17 10:26:55.349  7983  8041 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-17 10:26:55.350  7983  8041 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-17 10:26:55.351  7983  8041 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-17 10:26:55.353  7983  7983 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-17 10:26:55.356  7983  7983 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-17 10:26:55.363  7983  7983 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-17 10:26:55.363  7983  7983 V PanService: [BTUI] SIM Extra State :ABSENT
08-17 10:26:55.367  7983  7983 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-17 10:26:55.371  7983  7983 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-17 10:26:55.371  7983  7983 V BluetoothMapService: Handler(): got msg=1
08-17 10:26:55.373  7983  8018 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-17 10:26:55.373  7983  8018 I bluedroid-qcom: enable
08-17 10:26:55.373  7983  8018 I bt_hci_bdroid: init
,08-17 10:26:55.376  7983  8057 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-17 10:26:55.376  7983  8057 I bt-btu  : btu_task pending for preload complete event
08-17 10:26:55.377  7983  8018 I bt_vendor: bt-vendor : init
08-17 10:26:55.377  7983  8018 I bt_vendor: bt-vendor : get_bt_soc_type
08-17 10:26:55.377  7983  8018 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-17 10:26:55.377  7983  8018 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-17 10:26:55.378  7983  8018 D bt_userial_mct: userial_init
08-17 10:26:55.378  7983  8018 D bt_hci_bdroid: set_power 1
08-17 10:26:55.378  7983  8018 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
,08-17 10:26:55.378  7983  8018 I bt_vendor: Starting hciattach daemon
08-17 10:26:55.379  7983  8018 I bt_vendor: try to set true
08-17 10:26:55.369  8060  8060 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 10:26:55.369  8060  8060 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-17 10:26:55.421  8061  8061 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-17 10:26:55.549  8067  8067 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-17 10:26:55.563  8068  8068 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-17 10:26:55.620  8070  8070 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-17 10:26:55.638  8071  8071 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-17 10:26:55.656  8072  8072 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-17 10:26:55.672  8073  8073 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-17 10:26:55.698  8078  8078 I libmdmdetect: ESOC framework not supported
,08-17 10:26:55.701  8078  8078 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-17 10:26:55.709  8078  8078 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-17 10:26:55.710  8078  8078 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-17 10:26:55.710  8078  8078 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-17 10:26:55.710  8078  8078 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-17 10:26:55.710  8078  8078 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-17 10:26:55.710  8078  8078 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-17 10:26:55.710  8078  8078 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-17 10:26:55.757  8078  8079 E QC-QMI  : qmi_client [8078] 15: failed to locate client data
08-17 10:26:55.760   479   479 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-17 10:26:55.760   479   479 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,08-17 10:26:55.806  8083  8083 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 ,
,08-17 10:26:55.821  8084  8084 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-17 10:26:55.883  7983  8018 I bt_vendor: bluetooth satus is on
,08-17 10:26:55.883  7983  8018 D bt_hci_bdroid: preload
08-17 10:26:55.889  7983  8059 D bt_userial_mct: userial_open(port:0)
08-17 10:26:55.889  7983  8059 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-17 10:26:55.896  7983  8059 I bt_vendor: Done intiailizing UART
,08-17 10:26:55.900  7983  8059 I bt_vendor: Done intiailizing UART
,08-17 10:26:55.900  7983  8059 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
,08-17 10:26:55.900  7983  8059 I bt_vendor: Bluetooth Firmware and transport layer are initialized
,08-17 10:26:55.903  7983  8057 I bt-btu  : btu_task received preload complete event
08-17 10:26:55.904  7983  8057 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-17 10:26:55.905  7983  8057 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
,08-17 10:26:55.918  7983  8086 D bt_userial_mct: Entering userial_read_thread()
,08-17 10:26:55.924  7983  8057 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-17 10:26:55.927  7983  8057 I         : BTE_InitTraceLevels -- TRC_HCI
08-17 10:26:55.927  7983  8057 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-17 10:26:55.927  7983  8057 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-17 10:26:55.927  7983  8057 I         : BTE_InitTraceLevels -- TRC_AVDT
08-17 10:26:55.927  7983  8057 I         : BTE_InitTraceLevels -- TRC_AVRC
08-17 10:26:55.927  7983  8057 I         : BTE_InitTraceLevels -- TRC_A2D
08-17 10:26:55.927  7983  8057 I         : BTE_InitTraceLevels -- TRC_BNEP
08-17 10:26:55.927  7983  8057 I         : BTE_InitTraceLevels -- TRC_BTM
08-17 10:26:55.927  7983  8057 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-17 10:26:55.927  7983  8057 I         : BTE_InitTraceLevels -- TRC_GAP
08-17 10:26:55.927  7983  8057 I         : BTE_InitTraceLevels -- TRC_PAN
08-17 10:26:55.927  7983  8057 I         : BTE_InitTraceLevels -- TRC_SDP
08-17 10:26:55.928  7983  8057 I         : BTE_InitTraceLevels -- TRC_GATT
08-17 10:26:55.928  7983  8057 I         : BTE_InitTraceLevels -- TRC_SMP
08-17 10:26:55.928  7983  8057 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-17 10:26:55.928  7983  8057 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-17 10:26:56.039  7983  8057 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
,08-17 10:26:56.039  7983  8057 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0179061 
08-17 10:26:56.039  7983  8057 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0179061 
,08-17 10:26:56.089  7983  8022 E bt-btif : Calling BTA_HhEnable
,08-17 10:26:56.090  7983  8022 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-17 10:26:56.090  7983  8022 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-17 10:26:56.099  7983  8057 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
,08-17 10:26:56.100  7983  8057 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-17 10:26:56.100  7983  8057 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-17 10:26:56.100  7983  8057 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-17 10:26:56.100  7983  8057 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-17 10:26:56.104  1037  1037 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-17 10:26:56.109  7983  8022 D BluetoothAdapterProperties: Name is: G3
,08-17 10:26:56.120  7983  8022 D BluetoothAdapterProperties: Scan Mode:20
08-17 10:26:56.120  7983  8022 D BluetoothAdapterProperties: Discoverable Timeout:120
08-17 10:26:56.120  7983  8022 D bt_hci_bdroid: postload
08-17 10:26:56.121  7983  8059 D bt_hci_bdroid: Used up Tx Cmd credits
08-17 10:26:56.122  7983  8022 D bte_conf: Device ID record 1 : primary
08-17 10:26:56.122  7983  8022 D bte_conf:   vendorId            = 00c4
08-17 10:26:56.122  7983  8022 D bte_conf:   vendorIdSource      = 0001
08-17 10:26:56.122  7983  8022 D bte_conf:   product             = 13a1
08-17 10:26:56.122  7983  8022 D bte_conf:   version             = 1000
08-17 10:26:56.122  7983  8022 D bte_conf:   clientExecutableURL = 
08-17 10:26:56.122  7983  8022 D bte_conf:   serviceDescription  = 
08-17 10:26:56.122  7983  8022 D bte_conf:   documentationURL    = 
08-17 10:26:56.122  7983  8022 D bte_conf: bte_load_did_conf no section named DID2.
08-17 10:26:56.124  7983  8057 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
,08-17 10:26:56.126  7983  8059 D bt_hci_bdroid: Used up Tx Cmd credits
08-17 10:26:56.129  7983  8018 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-17 10:26:56.129  7983  8018 D BluetoothAdapterProperties: ScanMode =  20
08-17 10:26:56.130  7983  8018 D BluetoothAdapterProperties: State =  11
08-17 10:26:56.130  7983  8018 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-17 10:26:56.130  7983  8018 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-17 10:26:56.130  7983  8018 D BluetoothAdapterProperties: Setting state to 12
08-17 10:26:56.131  7983  8018 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-17 10:26:56.131  7983  8022 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-17 10:26:56.131  7983  8022 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-17 10:26:56.119  8088  8088 W sh      : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 10:26:56.119  8088  8088 W sh      : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-17 10:26:56.142  7983  8018 I BluetoothAdapterState: Entering On State
08-17 10:26:56.149  1037  1120 D BluetoothManagerService: Message: 60
08-17 10:26:56.149  1037  1120 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-17 10:26:56.149  1037  1120 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
,08-17 10:26:56.153  7983  8059 D bt_hci_bdroid: Used up Tx Cmd credits
08-17 10:26:56.163  7983  8018 D LGBluetoothServiceAdapter: [BTUI] OnState
08-17 10:26:56.163  7983  8018 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-17 10:26:56.163  7983  8018 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,08-17 10:26:56.166  7983  8018 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-17 10:26:56.167  7983  8057 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-17 10:26:56.167  7983  8057 W bt-smp  : Plain text(LSB ~ MSB) = 1b 68 5b 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-17 10:26:56.167  7983  8057 W bt-smp  : Encrypted text(LSB ~ MSB) = 48 d2 19 87 51 fa 7f 7f 2a 4a b5 31 ee 2d c7 fd 
08-17 10:26:56.167  7983  8059 D bt_hci_bdroid: Used up Tx Cmd credits
08-17 10:26:56.167  7983  8057 W bt-btm  : Stopping oneshot timer
08-17 10:26:56.168  6934  6950 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-17 10:26:56.171  7983  8086 E bt_mct  : hci lib postload completed
08-17 10:26:56.182  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:26:56.182  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:26:56.182  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 10:26:56.182  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 10:26:56.182  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 10:26:56.182  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 10:26:56.182  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 10:26:56.182  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 10:26:56.192  7983  8018 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
,08-17 10:26:56.193  7983  8022 D BluetoothAdapterProperties: Discoverable Timeout:120
08-17 10:26:56.193  7983  8022 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-17 10:26:56.196  7983  8057 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-17 10:26:56.196  7983  8057 W bt-smp  : Plain text(LSB ~ MSB) = 70 38 5c 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-17 10:26:56.196  7983  8057 W bt-smp  : Encrypted text(LSB ~ MSB) = 4c 6a 90 07 fc 1a 7a 05 09 a9 ba 73 88 97 1b e2 
,08-17 10:26:56.199  7983  8057 W bt-btm  : Stopping oneshot timer
08-17 10:26:56.200  1037  1037 D BluetoothManagerService: Stored Bluetooth name: G3
08-17 10:26:56.203  6772  6772 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 10:26:56.213  7983  8057 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-17 10:26:56.213  7983  8057 W bt-smp  : Plain text(LSB ~ MSB) = dd 49 77 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-17 10:26:56.213  7983  8057 W bt-smp  : Encrypted text(LSB ~ MSB) = ca ae af 43 ea 97 04 1e 1c 01 21 2c a3 e9 f5 5f 
,08-17 10:26:56.215  7983  8057 W bt-btm  : Stopping oneshot timer
08-17 10:26:56.217  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:26:56.217  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:26:56.217  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 10:26:56.217  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 10:26:56.217  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 10:26:56.217  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 10:26:56.217  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 10:26:56.217  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 10:26:56.221  6772  6772 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 10:26:56.235  7983  8057 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-17 10:26:56.235  7983  8057 W bt-smp  : Plain text(LSB ~ MSB) = 47 dd 4b 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-17 10:26:56.235  7983  8057 W bt-smp  : Encrypted text(LSB ~ MSB) = 07 22 64 4b 3c 26 08 5a 50 11 7b 31 11 1b b8 67 
,08-17 10:26:56.237  7983  8057 W bt-btm  : Stopping oneshot timer
08-17 10:26:56.240  6934  6949 D BluetoothPbap: onBluetoothStateChange: up=true
08-17 10:26:56.243  6934  6950 D BluetoothMap: onBluetoothStateChange: up=true
08-17 10:26:56.247  7983  8057 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-17 10:26:56.247  7983  8057 W bt-smp  : Plain text(LSB ~ MSB) = 5f 7d 69 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-17 10:26:56.247  7983  8057 W bt-smp  : Encrypted text(LSB ~ MSB) = 9e 95 f3 90 c7 9c 21 73 6a 97 ae 2f 0f 64 1e c8 
,08-17 10:26:56.250  7983  8057 W bt-btm  : Stopping oneshot timer
08-17 10:26:56.265  6934  6949 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-17 10:26:56.275  8093  8093 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-17 10:26:56.282  1882  2572 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-17 10:26:56.287  1882  1882 D BluetoothHeadset: Proxy object connected
,08-17 10:26:56.287  1037  1120 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 10:26:56.294  1037  1037 D BluetoothHeadset: Proxy object connected
08-17 10:26:56.294  6934  6934 D BluetoothInputDevice: Proxy object connected
08-17 10:26:56.295  6934  6934 D HidProfile: Bluetooth service connected
,08-17 10:26:56.299  6934  6950 D BluetoothA2dp: onBluetoothStateChange: up=true
08-17 10:26:56.301  6934  6934 D BluetoothMap: Proxy object connected
08-17 10:26:56.301  6934  6934 D MapProfile: Bluetooth service connected
08-17 10:26:56.301  6934  6934 D BluetoothMap: getConnectedDevices()
08-17 10:26:56.302  7983  8001 V BluetoothMapService: getConnectedDevices()
08-17 10:26:56.303  6934  6934 D BluetoothHeadset: Proxy object connected
08-17 10:26:56.303  6934  6934 D HeadsetProfile: Bluetooth service connected
08-17 10:26:56.305  1882  1897 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 10:26:56.310  1882  1882 D BluetoothHeadset: Proxy object connected
08-17 10:26:56.310  6934  6950 D BluetoothPan: onBluetoothStateChange on: true
08-17 10:26:56.310  6934  6950 D BluetoothPan: onBluetoothStateChange call bindService
,08-17 10:26:56.312  1882  2571 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 10:26:56.314  1882  1882 D BluetoothHeadset: Proxy object connected
08-17 10:26:56.314  1037  1120 D BluetoothA2dp: onBluetoothStateChange: up=true
08-17 10:26:56.315  1037  1037 D BluetoothA2dp: Proxy object connected
,08-17 10:26:56.317  1037  1037 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-17 10:26:56.317  1037  1120 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-17 10:26:56.317  1037  1120 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-17 10:26:56.318  1037  1120 D BluetoothManagerService: Message: 40
08-17 10:26:56.318  1037  1120 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-17 10:26:56.319  1970  1970 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-17 10:26:56.319  1970  2183 D LGBluetoothAPIService: Message: 1
08-17 10:26:56.319  1970  2183 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-17 10:26:56.319  1970  2183 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
08-17 10:26:56.319  1970  2183 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-17 10:26:56.320  6934  6934 D BluetoothA2dp: Proxy object connected
08-17 10:26:56.320  6934  6934 D A2dpProfile: Bluetooth service connected
08-17 10:26:56.321  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-17 10:26:56.328  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:26:56.331  7983  7983 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-17 10:26:56.331  7983  7983 D BluetoothMapService: STATE_ON
08-17 10:26:56.331  7983  7983 V BluetoothMapService: Handler(): got msg=1
08-17 10:26:56.332  6934  6934 D BluetoothPan: BluetoothPAN Proxy object connected
08-17 10:26:56.332  6934  6934 D PanProfile: Bluetooth service connected
08-17 10:26:56.332  7983  7983 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-17 10:26:56.332  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:26:56.337  6934  6934 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-17 10:26:56.338  6934  6934 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-17 10:26:56.339  7983  8111 D BluetoothMapMasInstance: MAS initSocket()
08-17 10:26:56.339  7983  8111 D BluetoothMapMasInstance:   masId = 00
08-17 10:26:56.339  7983  8111 D BluetoothMapMasInstance:   msgTypes = 0e
08-17 10:26:56.339  7983  8111 D BluetoothMapMasInstance:   masName = SMS/MMS
08-17 10:26:56.339  7983  8111 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-17 10:26:56.343  1037  1053 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 10:26:56.345  7983  8111 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 10:26:56.348  7983  8111 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-17 10:26:56.349  7983  8111 V BluetoothMapMasInstance: Succeed to create listening socket 
08-17 10:26:56.349  7983  8111 D BluetoothMapMasInstance: Accepting socket connection...
08-17 10:26:56.349  7983  8022 D BluetoothAdapterProperties: Scan Mode:21
08-17 10:26:56.349  7983  8022 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-17 10:26:56.353  7983  7983 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27be3b2e
08-17 10:26:56.353  7983  7983 V BluetoothPbapService: Pbap Service onCreate
08-17 10:26:56.353  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:26:56.353  7983  7983 V BluetoothPbapService: Starting PBAP service
,08-17 10:26:56.355  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:26:56.357  7983  7983 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-17 10:26:56.358  7983  7983 V BluetoothPbapService: Pbap Service onBind
08-17 10:26:56.360  7983  7983 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-17 10:26:56.360  7983  7983 V BluetoothPbapService: state: 12
08-17 10:26:56.361  7983  7983 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-17 10:26:56.361  7983  7983 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-17 10:26:56.361  6934  6934 D DockEventReceiver: finishStartingService: stopping service
,08-17 10:26:56.361  7983  7983 V BluetoothPbapReceiver: ***********state = 12
08-17 10:26:56.362  6934  6934 D BluetoothPbap: Proxy object connected
08-17 10:26:56.362  6934  6934 D PbapServerProfile: Bluetooth service connected
08-17 10:26:56.363  7983  7983 V BluetoothPbapService: Handler(): got msg=1
08-17 10:26:56.364  7983  7983 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-17 10:26:56.365  7983  8115 V BluetoothPbapService: Pbap Service initSocket
08-17 10:26:56.366  1037  1740 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 10:26:56.367  7983  8115 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 10:26:56.371  2249  2249 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-17 10:26:56.371  2249  2249 D c       : Getting all permits...
08-17 10:26:56.371  2249  2249 D a       : Opening database...
08-17 10:26:56.372  7983  8115 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-17 10:26:56.372  7983  8115 V BluetoothPbapService: Succeed to create listening socket 
08-17 10:26:56.372  7983  8115 V BluetoothPbapService: Accepting socket connection...
08-17 10:26:56.375  2249  2249 D a       : Opening database auth.proximity.permit_store...
08-17 10:26:56.377  2249  2249 D a       : Closing database...
08-17 10:26:56.387  6934  6934 D BluetoothPermissionRequest: onReceive
,08-17 10:26:56.389  6934  6934 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,08-17 10:26:56.391  6934  6934 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-17 10:26:56.393  7983  7983 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-17 10:26:56.394  7983  7983 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-17 10:26:56.400  7983  7983 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-17 10:26:56.420  7983  7983 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-17 10:26:56.421  7983  7983 V BtOppService: onCreate
,08-17 10:26:56.425  7983  7983 V BluetoothOppNotification: send message
08-17 10:26:56.429  7983  7983 V BtOppService: Starting RfcommListener
08-17 10:26:56.440  7983  7983 D BluetoothOppPreference: Dumping Names:  
08-17 10:26:56.440  7983  7983 D BluetoothOppPreference: {}
08-17 10:26:56.440  7983  7983 D BluetoothOppPreference: Dumping Channels:  
08-17 10:26:56.440  7983  7983 D BluetoothOppPreference: {}
08-17 10:26:56.442  7983  7983 V BtOppService: onStartCommand
,08-17 10:26:56.448  7983  7983 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-17 10:26:56.449  7983  7983 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-17 10:26:56.450  7983  8121 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-17 10:26:56.451  7983  8118 V BtOppService: Deleted complete outbound shares, number =  0
08-17 10:26:56.452  7983  8121 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-17 10:26:56.453  7983  8118 V BtOppService: Deleted complete inbound failed shares, number = 0
08-17 10:26:56.453  7983  8118 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-17 10:26:56.457  7983  7983 V BluetoothOppNotification: new notify threadi!
08-17 10:26:56.458  7983  8118 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2498834a on behalf of 
08-17 10:26:56.458  7983  7983 V BluetoothOppNotification: send delay message
,08-17 10:26:56.459  7983  7983 V BtOppService: start RfcommListener
08-17 10:26:56.460  7983  8122 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-17 10:26:56.461  7983  8121 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@222ca2bb on behalf of 
08-17 10:26:56.462  7983  8122 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3e3873d8 on behalf of 
08-17 10:26:56.464  7983  8122 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-17 10:26:56.464  7983  8121 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-17 10:26:56.467  7983  8122 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-17 10:26:56.468  7983  7983 V BtOppService: RfcommListener started
08-17 10:26:56.468  7983  7983 V BtOppService: ContentObserver received notification
08-17 10:26:56.469  7983  8123 V BtOppRfcommListener: Starting RFCOMM listener....
08-17 10:26:56.469  7983  7983 V BtOppService: ContentObserver received notification
08-17 10:26:56.469  1037  2044 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 10:26:56.470  7983  8123 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 10:26:56.471  7983  8123 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
,08-17 10:26:56.473  7983  8123 V BtOppRfcommListener: Started RFCOMM listener....
,08-17 10:26:56.474  7983  8122 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@22655331 on behalf of 
08-17 10:26:56.473  7983  8123 I BtOppRfcommListener: Accept thread started.
08-17 10:26:56.474  7983  8123 V BtOppRfcommListener: Accepting connection...
08-17 10:26:56.477  7983  8124 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-17 10:26:56.477  7983  8124 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-17 10:26:56.479  7983  8122 V BluetoothOppNotification: outbound: succ-0  fail-0
08-17 10:26:56.480  7983  8124 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@d638a16 on behalf of 
08-17 10:26:56.481  7983  8122 V BluetoothOppNotification: outbound notification was removed.
08-17 10:26:56.481  7983  8122 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-17 10:26:56.482  7983  8124 V BluetoothOppNotification: update too frequent, put in queue
08-17 10:26:56.485  7983  8122 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2a78af97 on behalf of 
08-17 10:26:56.486  7983  8122 V BluetoothOppNotification: inbound: succ-0  fail-0
08-17 10:26:56.486  7983  7983 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27be3b2e
,08-17 10:26:56.486  7983  7983 V BluetoothFtpService: Ftp Service onCreate
08-17 10:26:56.486  7983  7983 I BluetoothFtpService: Ftp Service onCreate
08-17 10:26:56.486  7983  7983 V BluetoothFtpService: Ftp Service onStartCommand
08-17 10:26:56.486  7983  7983 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-17 10:26:56.487  7983  7983 V BluetoothFtpService: Starting Listening on sockets
08-17 10:26:56.487  7983  7983 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-17 10:26:56.487  7983  7983 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-17 10:26:56.487  7983  7983 V BluetoothSapReceiver: SapReceiver onReceive 
,08-17 10:26:56.487  7983  7983 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-17 10:26:56.487  7983  7983 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-17 10:26:56.487  7983  7983 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-17 10:26:56.488  7983  8124 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-17 10:26:56.489  7983  8122 V BluetoothOppNotification: inbound notification was removed.
08-17 10:26:56.490  7983  7983 V BluetoothFtpService: Handler(): got msg=1
08-17 10:26:56.490  7983  8122 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-17 10:26:56.492  7983  7983 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-17 10:26:56.492  7983  7983 V BluetoothFtpService: Ftp Service initSocket
08-17 10:26:56.493  7983  8122 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@248af16d on behalf of 
08-17 10:26:56.496  1037  1054 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 10:26:56.497  7983  7983 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 10:26:56.498  7983  7983 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=78
08-17 10:26:56.498  7983  7983 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-17 10:26:56.500  7983  8125 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-17 10:26:56.515  7983  7983 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27be3b2e
08-17 10:26:56.515  7983  7983 V BluetoothSapService: Sap Service onCreate
08-17 10:26:56.517  7983  7983 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,08-17 10:26:56.517  7983  7983 V BluetoothSapService: state: 12
,08-17 10:26:56.517  7983  7983 V BluetoothSapService: Starting SAP server process
08-17 10:26:56.519  7983  7983 V BluetoothSapService: SAP Service startRfcommListenerThread
08-17 10:26:56.521  7983  8127 V BluetoothSapService: Sap Service initRfcommSocket
08-17 10:26:56.509  8126  8126 W sapd    : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 10:26:56.521  1037  1658 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 10:26:56.509  8126  8126 W sapd    : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 10:26:56.523  7983  8127 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 10:26:56.524  7983  8127 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-17 10:26:56.524  7983  8127 V BluetoothSapService: Succeed to create listening socket 
08-17 10:26:56.524  7983  8127 V BluetoothSapService: Accepting socket connection...
08-17 10:26:56.535  8126  8126 V BT_SAP  : Event pipe created
08-17 10:26:56.535  8126  8126 V BT_SAP  : create_server_socket qcom.sap.server
08-17 10:26:56.535  8126  8126 V BT_SAP  : created socket fd 6
,08-17 10:26:57.461  7983  7983 V BluetoothOppNotification: new notify threadi!
,08-17 10:26:57.462  7983  7983 V BluetoothOppNotification: send delay message
,08-17 10:26:57.475  7983  8137 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-17 10:26:57.480  7983  8137 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2ff23769 on behalf of 
08-17 10:26:57.482  7983  8137 V BluetoothOppNotification: mUpdateCompleteNotification = true
,08-17 10:26:57.485  7983  8137 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-17 10:26:57.486  7983  8137 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3b39c5ee on behalf of 
08-17 10:26:57.487  7983  8137 V BluetoothOppNotification: outbound: succ-0  fail-0
08-17 10:26:57.489  7983  8137 V BluetoothOppNotification: outbound notification was removed.
08-17 10:26:57.489  7983  8137 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-17 10:26:57.490  7983  8137 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@15fbfa8f on behalf of 
08-17 10:26:57.490  7983  8137 V BluetoothOppNotification: inbound: succ-0  fail-0
08-17 10:26:57.492  7983  8137 V BluetoothOppNotification: inbound notification was removed.
08-17 10:26:57.492  7983  8137 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-17 10:26:57.495  7983  8137 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3c3b711c on behalf of 
,08-17 10:26:59.612  6772  6842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:26:59.612  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:26:59.612  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 10:26:59.612  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 10:26:59.612  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 10:26:59.612  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 10:26:59.612  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 10:26:59.612  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 10:26:59.622  6772  6842 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 10:26:59.623  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 10:26:59.623  6772  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@94be17b removed from the list
08-17 10:26:59.623  6772  6842 D io.jxcore.node.ConnectivityMonitor: stop
08-17 10:26:59.623  6772  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:26:59.623  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:26:59.624  6772  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 10:26:59.625  6772  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3424ab98 added. We now have 4 listener(s)
08-17 10:26:59.625  6772  6842 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 10:26:59.627  1037  2074 D WifiServiceImplEx: setWifiEnabled: false pid=6772, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-17 10:26:59.627  1037  2074 D WifiService: setWifiEnabled: false pid=6772, uid=10118
,08-17 10:26:59.627  1037  2074 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-17 10:27:00.004  1037  1384 V AlarmManager: ELAPSED_WAKEUP set : Alarm{3428b4a4 type 2 when 396639 com.google.android.gms} when 396639
,08-17 10:27:00.039   320  8140 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-17 10:27:00.044  1037  1118 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-17 10:27:00.052  1605  1605 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-17 10:27:00.052  1605  1605 I KeyguardUpdateMonitor: called onTimeUpdated()
08-17 10:27:00.052  1605  1605 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-17 10:27:00.052  1605  1605 I [SystemUI]Clock: called onTimeUpdated()
,08-17 10:27:00.057  1605  1605 I LgeClockWidgetControlView: called onTimeUpdated()
,08-17 10:27:00.057  1605  1605 I [SystemUI]DateView: called onTimeUpdated()
08-17 10:27:00.058  1605  1605 I [SystemUI]DateView: called onTimeUpdated()
08-17 10:27:00.059  1605  1605 D KeyguardUpdateMonitor: handleTimeUpdate
08-17 10:27:04.637  6772  6842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 10:27:04.650  1037  1963 D WifiServiceImplEx: setWifiEnabled: true pid=6772, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-17 10:27:04.651  1037  1963 D WifiService: setWifiEnabled: true pid=6772, uid=10118
08-17 10:27:04.651  1037  1963 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-17 10:27:04.672  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-17 10:27:04.672  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-17 10:27:04.672  1037  1037 D Ulp_jni : JNI:system_update. Event-4
08-17 10:27:04.673  1037  1541 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-17 10:27:04.673  1037  1541 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-17 10:27:04.676  1037  1541 E WifiUtil: wfc_util_ffile_check_copy(): pid[1037] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-17 10:27:04.676  1037  1541 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-17 10:27:04.676  1037  1541 E WifiUtil: wfc_util_ffile_check_copy(): pid[1037] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-17 10:27:04.676  1037  1541 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-17 10:27:04.676  1037  1541 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-17 10:27:04.676  1037  1541 E WifiHW  : unknown target_country: EU , set to default
08-17 10:27:04.676  1037  1541 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-17 10:27:04.677  1037  1541 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-17 10:27:04.677  1037  1541 I WifiUtil: gEnableBmps=1
08-17 10:27:05.262  1037  1120 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-17 10:27:05.262  1037  1120 D Tethering: InitialState.processMessage what=4
08-17 10:27:05.262  1037  1120 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-17 10:27:05.272   320   896 D SoftapController: Softap fwReload - Ok
08-17 10:27:05.280  1037  1541 E NetdConnector: NDC Command {83 softap fwreload wlan0 STA} took too long (599ms)
,08-17 10:27:05.291   320   896 D CommandListener: Setting iface cfg
08-17 10:27:05.291   320   896 D CommandListener: Trying to bring down wlan0
08-17 10:27:05.292   320   896 D CommandListener: Clearing all IP addresses on wlan0
08-17 10:27:05.301  1037  1541 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,08-17 10:27:05.309  8151  8151 W wpa_supplicant: type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-17 10:27:05.324  1037  1541 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-17 10:27:05.324  1037  1541 E WifiStateMachine: useWiFiOffloading() : false
08-17 10:27:05.324  1037  1541 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-17 10:27:05.309  8151  8151 W wpa_supplicant: type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-17 10:27:05.362  1037  1541 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-17 10:27:05.362  1037  1541 D WifiMonitor: connecting to supplicant
08-17 10:27:05.374  8151  8151 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-17 10:27:05.391  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 10:27:05.396  6934  6934 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,08-17 10:27:05.396  6934  6934 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-17 10:27:05.396  6934  6934 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
,08-17 10:27:05.396  6934  6934 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,08-17 10:27:05.399  1970  1970 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-17 10:27:05.401  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-17 10:27:05.404  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:27:05.409  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:27:05.409  6934  6934 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-17 10:27:05.410  6934  6934 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-17 10:27:05.410  6934  6934 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-17 10:27:05.410  6934  6934 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-17 10:27:05.410  6934  6934 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-17 10:27:05.410  6934  6934 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-17 10:27:05.411  6934  6934 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-17 10:27:05.413  6934  6934 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-17 10:27:05.413  6934  6934 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-17 10:27:05.413  6934  6934 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-17 10:27:05.413  6934  6934 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-17 10:27:05.414  6934  6934 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-17 10:27:05.415  6934  6934 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-17 10:27:05.415  6934  6934 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-17 10:27:05.415  6934  6934 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-17 10:27:05.415  6934  6934 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-17 10:27:05.415  6934  6934 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-17 10:27:05.415  6934  6934 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-17 10:27:05.435  8151  8151 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-17 10:27:05.435  8151  8151 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-17 10:27:05.465  1037  2044 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8169 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-17 10:27:05.489  8151  8151 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-17 10:27:05.541  8151  8151 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-17 10:27:05.551  1037  1541 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-17 10:27:05.551  1037  1541 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-17 10:27:05.552  1037  1541 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-17 10:27:05.552  1037  1541 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-17 10:27:05.552  1037  1541 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-17 10:27:05.553  1037  1541 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-17 10:27:05.553  1037  1541 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-17 10:27:05.553  1037  1541 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-17 10:27:05.554  1037  1541 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-17 10:27:05.554  1037  1541 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-17 10:27:05.554  1037  1541 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-17 10:27:05.560  8151  8151 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
,08-17 10:27:05.560  1037  8190 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-17 10:27:05.560  1037  8190 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-17 10:27:05.560  1037  8190 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-17 10:27:05.561  1037  8190 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-17 10:27:05.561  1037  8190 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-17 10:27:05.561  1037  8190 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-17 10:27:05.583  1037  1983 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8192 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-17 10:27:05.586  1037  1541 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-17 10:27:05.586  1037  1541 E WifiStateMachine: useWiFiOffloading() : false
08-17 10:27:05.586  1037  1541 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-17 10:27:05.587  1037  1541 D WifiNative-wlan0: doBoolean: SET update_config 1
08-17 10:27:05.587  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 10:27:05.588  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 10:27:05.588  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 10:27:05.588  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 10:27:05.588  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-17 10:27:05.589  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 10:27:05.589  1970  1970 D WfdService: Waiting for WifiP2p enabling
08-17 10:27:05.590  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-17 10:27:05.591  1037  1546 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-17 10:27:05.593  8169  8189 W FormManager: Network not available. Please check & try again.
08-17 10:27:05.594  1037  1541 D WifiNative-wlan0: SET update_config 1: returned true
08-17 10:27:05.595  1037  1541 D WifiConfigStore: Loading config and enabling all networks 
08-17 10:27:05.595  1037  1541 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-17 10:27:05.596  1037  1541 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-17 10:27:05.597  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:27:05.597  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:27:05.597  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 10:27:05.597  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 10:27:05.597  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 10:27:05.597  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 10:27:05.597  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 10:27:05.597  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 10:27:05.599  6772  6772 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-17 10:27:05.603  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:27:05.603  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:27:05.603  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 10:27:05.603  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 10:27:05.603  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 10:27:05.603  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 10:27:05.603  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 10:27:05.603  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 10:27:05.605  8169  8191 V FormManager: Network unavailable.
08-17 10:27:05.607  6772  6772 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-17 10:27:05.609  1037  1541 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
,08-17 10:27:05.614  8169  8191 V FormManager: Network unavailable.
08-17 10:27:05.618  1037  1541 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-17 10:27:05.619  1037  1541 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-17 10:27:05.620  1037  1541 D WifiStateMachine: enableVerboseLogging : level 2
08-17 10:27:05.620  1037  1541 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-17 10:27:05.620  1037  1541 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-17 10:27:05.620  1037  1541 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-17 10:27:05.621  1037  1541 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-17 10:27:05.621  1037  1541 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-17 10:27:05.621  1037  1541 D WifiNative-wlan0: SET model_name LG-D855: returned true
,08-17 10:27:05.621  1037  1541 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-17 10:27:05.622  1037  1541 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-17 10:27:05.622  1037  1541 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-17 10:27:05.622  1037  1541 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-17 10:27:05.622  1037  1541 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-17 10:27:05.623  1037  1541 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-17 10:27:05.623  1037  1541 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
,08-17 10:27:05.623  1037  1541 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-17 10:27:05.624  1037  1541 D WifiStateMachine: Setting OUI to DA-A1-19
08-17 10:27:05.624  1037  1541 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-17 10:27:05.625  1037  1541 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-17 10:27:05.625  1037  1541 D WifiNative-HAL: Setting external_sim to 1
08-17 10:27:05.625  1037  1541 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-17 10:27:05.625  1037  1541 D WifiNative-wlan0: SET external_sim 1: returned true
08-17 10:27:05.625  1037  1541 I WifiNative-HAL: startHal
08-17 10:27:05.625  1037  1541 D wifi    : setting scan oui 0xaf653660
08-17 10:27:05.625  1970  1970 D WfdsService: Supplicant Connection state is changed : true
08-17 10:27:05.626  1970  2334 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-17 10:27:05.626  7766  7766 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 10:27:05.626  1037  1541 D WifiStateMachine: Setting OUI to DA-A1-19
08-17 10:27:05.626  1970  2334 D WfdsService: Set the WFDS Monitor: true
08-17 10:27:05.626  1037  1541 I WifiNative-HAL: startHal
08-17 10:27:05.626  1970  2334 D WfdsMonitor: WfdsMonitorThread create
08-17 10:27:05.626  1037  1541 D wifi    : setting scan oui 0xaf653660
08-17 10:27:05.626  1037  1541 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-17 10:27:05.626  1970  2334 D WfdsMonitor: WFDS Monitor is created and started
08-17 10:27:05.626  1970  2334 D WfdsService: WiFi: Supplicant connection re-established
08-17 10:27:05.627  1970  8210 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-17 10:27:05.627  1037  1541 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-17 10:27:05.627  1037  1541 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-17 10:27:05.627  8151  8151 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-17 10:27:05.627  1970  8210 E CtrlSupplicant: Succeed to open control connection
08-17 10:27:05.628  1970  8210 E CtrlSupplicant: Succeed to open monitor connection
08-17 10:27:05.628  1970  8210 D WfdsMonitor: Supplicant connection established
08-17 10:27:05.628  1970  2334 D WfdsService: Connected to the supplicant for wfds
08-17 10:27:05.629  1037  1541 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-17 10:27:05.629  1037  1541 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-17 10:27:05.629  8151  8151 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-17 10:27:05.630  1037  1541 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-17 10:27:05.630  1037  1541 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-17 10:27:05.630  8151  8151 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-17 10:27:05.630  1037  1541 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-17 10:27:05.630  1037  1541 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-17 10:27:05.630  8151  8151 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-17 10:27:05.631  1037  1541 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-17 10:27:05.631  1037  1541 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-17 10:27:05.631  8151  8151 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-17 10:27:05.631  1037  1541 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-17 10:27:05.631  1037  1541 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-17 10:27:05.632  8151  8151 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-17 10:27:05.634  1037  1541 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-17 10:27:05.634  1037  1541 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
,08-17 10:27:05.634  1037  2113 I ActivityManager: Killing 7223:com.lge.drmservice/u0a62 (adj 15): empty #17
08-17 10:27:05.634  8151  8151 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-17 10:27:05.635  1037  1541 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-17 10:27:05.635  1037  1541 E WifiNative: : [402,804,799 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-17 10:27:05.635  1037  1541 D WifiNative-wlan0: doBoolean: RECONNECT
08-17 10:27:05.636  1037  1541 D WifiNative-wlan0: RECONNECT: returned true
08-17 10:27:05.636  1037  1541 D WifiNative-wlan0: doString: [STATUS]
08-17 10:27:05.637  1037  8190 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-17 10:27:05.637  1037  8190 E WifiMonitor: WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-17 10:27:05.637  1037  1541 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-17 10:27:05.637  1037  1541 D WifiNative-wlan0: doBoolean: SET ps 1
08-17 10:27:05.638  1037  1541 D WifiNative-wlan0: SET ps 1: returned true
08-17 10:27:05.638  1037  1540 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-17 10:27:05.640   320   896 D CommandListener: Setting iface cfg
08-17 10:27:05.640   320   896 D CommandListener: Trying to bring up p2p0
08-17 10:27:05.640  1037  1540 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-17 10:27:05.640  1037  1540 D LGWifiP2pService: P2pEnablingState
08-17 10:27:05.640  1037  1540 D LGWifiP2pService: P2pEnablingState{ when=-1ms what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-17 10:27:05.640  1037  1540 D LGWifiP2pService: P2p socket connection successful
08-17 10:27:05.640  1037  1540 D LGWifiP2pService: P2pEnabledState
08-17 10:27:05.682  1037  1541 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-17 10:27:05.683  1037  1541 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-17 10:27:05.684  1037  1540 D LGWifiP2pService: sending p2p connection changed broadcast
08-17 10:27:05.684  1037  1540 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-17 10:27:05.685  1037  1541 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-17 10:27:05.685  1037  2028 W libprocessgroup: failed to open /acct/uid_10062/pid_7223/cgroup.procs: No such file or directory
,08-17 10:27:05.686  1037  1541 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-17 10:27:05.687  1037  1541 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=402856  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-17 10:27:05.688  1037  1540 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-17 10:27:05.690  1037  1540 D WifiNative-p2p0: doBoolean: SET device_name G3
08-17 10:27:05.690  1037  1540 D WifiNative-p2p0: SET device_name G3: returned true
08-17 10:27:05.690  1037  1540 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-17 10:27:05.691  1037  1540 D LGWifiP2pService: before postfix = G3
08-17 10:27:05.691  1037  1540 D WifiServerServiceExt: postfix byte check : 2
08-17 10:27:05.691  1037  1540 D LGWifiP2pService: after postfix = G3
08-17 10:27:05.691  1037  1540 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-17 10:27:05.691  1037  1540 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-17 10:27:05.691  1037  1540 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-17 10:27:05.692  1037  1540 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-17 10:27:05.692  1037  1540 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-17 10:27:05.692  1037  1540 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-17 10:27:05.692  1037  1540 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-17 10:27:05.693  1037  1541 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=402862  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-17 10:27:05.693  1037  1037 D WifiScanningService: SCAN_AVAILABLE : 3
08-17 10:27:05.693  1037  1540 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-17 10:27:05.693  1037  1540 D WifiNative-HAL: p2pGetDeviceAddress
08-17 10:27:05.693  1037  1037 D RttService: SCAN_AVAILABLE : 3
08-17 10:27:05.693  1037  1541 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-17 10:27:05.693  1037  1540 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-17 10:27:05.694  1037  1559 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-17 10:27:05.694  1037  1541 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-17 10:27:05.694  1037  1559 I WifiNative-HAL: startHal
08-17 10:27:05.694  1037  1559 D wifi    : getting scan capabilities on interface[1] = 0xaf653660
08-17 10:27:05.694  1037  1559 D wifi    : failed to get capabilities : -3
08-17 10:27:05.694  1037  1559 E WifiScanningService: could not get scan capabilities
08-17 10:27:05.694  1970  1970 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-17 10:27:05.694  1970  1970 D WfdsService: WifiP2pState is changed : true
08-17 10:27:05.694  1970  2334 D WfdsService: Receive the WFDS_ENABLE Method
08-17 10:27:05.694  1970  2334 D WfdsService: Set the WFDS Monitor: true
08-17 10:27:05.694  1037  1560 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-17 10:27:05.694  1970  2334 D WfdsService: Connected to the supplicant for wfds
08-17 10:27:05.694  1970  2334 D WfdsJNI : doCommand: WFDS_SET TRUE
08-17 10:27:05.695  8151  8151 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
,08-17 10:27:05.695  1970  2334 D WfdsService: selectPreferredScanChannel [36]
,08-17 10:27:05.695  1970  2334 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-17 10:27:05.695  1037  1541 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-17 10:27:05.695  1037  1541 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
,08-17 10:27:05.695  8151  8151 E wpa_supplicant: nWIFIDualbandAPConnection: 1
,08-17 10:27:05.696  1037  1541 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-17 10:27:05.696  1037  1541 E WifiStateMachine:  ConnectModeState what:132096 -100 0,
,08-17 10:27:05.697  1037  1541 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-17 10:27:05.697  1037  1541 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
,08-17 10:27:05.697  1970  1970 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-17 10:27:05.697  8151  8151 E wpa_supplicant: disconnect_rssi_lvl: -100
08-17 10:27:05.697  1037  1541 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-17 10:27:05.698  1970  1970 D WfdsService: isConnected: false
08-17 10:27:05.698  1037  1541 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-17 10:27:05.698  1037  1541 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-17 10:27:05.698  1037  1541 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
,08-17 10:27:05.700  8151  8151 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-17 10:27:05.701  8151  8151 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-17 10:27:05.702  1037  8190 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
,08-17 10:27:05.702  8151  8151 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-17 10:27:05.702  1037  8190 E WifiMonitor: WifiMonitor:wlan0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-17 10:27:05.702  1037  8190 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-17 10:27:05.702  1037  8190 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-17 10:27:05.702  8151  8151 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 10:27:05.702  1037  1541 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-17 10:27:05.702  1037  1541 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-17 10:27:05.702  8151  8151 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 10:27:05.703  1037  1541 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-17 10:27:05.703  1037  1541 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-17 10:27:05.703  1037  1541 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-17 10:27:05.703  8151  8151 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-17 10:27:05.703  8151  8151 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-17 10:27:05.704  1970  8210 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-17 10:27:05.704  1037  8190 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-17 10:27:05.704  1970  8210 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-17 10:27:05.704  1037  8190 E WifiMonitor: WifiMonitor:p2p0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 10:27:05.704  1037  8190 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 10:27:05.704  1037  8190 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 10:27:05.704  1037  8190 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-17 10:27:05.704  1037  8190 E WifiMonitor: WifiMonitor:p2p0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 10:27:05.704  1037  8190 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 10:27:05.705  1037  8190 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 10:27:05.705  1037  8190 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-17 10:27:05.705  1037  8190 E WifiMonitor: WifiMonitor:wlan0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-17 10:27:05.705  1037  8190 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
,08-17 10:27:05.705  1037  8190 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-17 10:27:05.705  1037  1541 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-17 10:27:05.705  1037  1541 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-17 10:27:05.705  1037  1541 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-17 10:27:05.705  1037  1541 D WifiNative-wlan0: doBoolean: SCAN
08-17 10:27:05.706  1037  1541 D WifiNative-wlan0: SCAN: returned false
08-17 10:27:05.707  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 10:27:05.707  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-17 10:27:05.709  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 10:27:05.710  1037  1541 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=402880  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-17 10:27:05.712  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 10:27:05.712  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 10:27:05.712  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-17 10:27:05.712  1037  1540 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-17 10:27:05.712  1037  1540 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-17 10:27:05.714  1037  1541 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=402883  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-17 10:27:05.714  1037  1541 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-17 10:27:05.715  1970  1970 I WfdStateTracker: handleP2pThisDeviceChanged
08-17 10:27:05.715  1037  1541 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-17 10:27:05.715  1037  1541 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
,08-17 10:27:05.716  1970  1970 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-17 10:27:05.716  1970  1970 D WfdsService: Update P2p Interface State: 3
08-17 10:27:05.716  1037  1540 D WifiNative-p2p0: P2P_FLUSH: returned true
08-17 10:27:05.717  1037  1540 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-17 10:27:05.717  1037  1540 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-17 10:27:05.717  1037  1540 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-17 10:27:05.718  1037  1540 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-17 10:27:05.718  1037  1540 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-17 10:27:05.719  1037  1541 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-17 10:27:05.719  1037  1541 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-17 10:27:05.722  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 10:27:05.722  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 10:27:05.722  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-17 10:27:05.723  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-17 10:27:05.723  1037  1037 D WifiServerServiceExt: setSupplicantStateSCANNING
08-17 10:27:05.724  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-17 10:27:05.725  1037  1037 D WifiServerServiceExt: setSupplicantStateSCANNING
08-17 10:27:05.729  1037  1540 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-17 10:27:05.729  1037  1540 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-17 10:27:05.729  1037  1540 D LGWifiP2pService: InactiveState
08-17 10:27:05.729  1037  1540 D LGWifiP2pService: InactiveState{ when=-27ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-17 10:27:05.729  1037  1540 D LGWifiP2pService: P2pEnabledState{ when=-27ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
,08-17 10:27:05.729  1037  1540 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-17 10:27:05.730  8151  8151 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-17 10:27:05.730  8151  8151 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-17 10:27:05.730  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 10:27:05.730  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-17 10:27:05.731  8151  8151 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-17 10:27:05.731  8151  8151 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 10:27:05.732  8151  8151 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 10:27:05.732  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 10:27:05.732  1970  8210 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-17 10:27:05.732  1970  8210 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-17 10:27:05.732  1970  8210 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-17 10:27:05.732  1037  8190 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-17 10:27:05.732  1037  8190 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-17 10:27:05.732  1037  8190 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-17 10:27:05.732  1037  8190 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-17 10:27:05.733  1037  8190 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-17 10:27:05.733  1037  8190 E WifiMonitor: WifiMonitor:p2p0 cnt=53 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 10:27:05.733  1037  8190 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 10:27:05.733  1037  8190 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 10:27:05.733  1037  8190 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-17 10:27:05.733  1037  8190 E WifiMonitor: WifiMonitor:p2p0 cnt=54 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 10:27:05.733  1037  8190 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 10:27:05.733  1037  8190 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 10:27:05.733  1037  1540 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-17 10:27:05.733  1037  1540 D LGWifiP2pService: InactiveState{ when=-15ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-17 10:27:05.733  1037  1540 D LGWifiP2pService: P2pEnabledState{ when=-16ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-17 10:27:05.733  1037  1540 D LGWifiP2pService: InactiveState{ when=-5ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-17 10:27:05.733  1037  1540 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-17 10:27:05.733  1037  1540 D LGWifiP2pService: DefaultState{ when=-5ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-17 10:27:05.734  1037  1540 D LGWifiP2pService: InactiveState{ when=-1ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-17 10:27:05.734  1037  1540 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-17 10:27:05.734  1037  1540 D LGWifiP2pService: DefaultState{ w,hen=-1ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-17 10:27:05.734  1037  1540 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-17 10:27:05.734  1037  1540 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-17 10:27:05.734  1037  1540 D LGWifiP2pService: DefaultState{ when=-2ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-17 10:27:05.734  1037  1540 D LGWifiP2pService: InactiveState{ when=-2ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-17 10:27:05.734  1037  1540 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-17 10:27:05.735  1037  1540 D LGWifiP2pService: DefaultState{ when=-2ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-17 10:27:05.736  1970  2334 W WfdsService: DefaultState - msg [9441285] is not handled
08-17 10:27:05.736  1037  1037 E WifiServerServiceExt: No p2p device connected
08-17 10:27:05.746  8192  8192 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-17 10:27:05.749  6934  6934 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-17 10:27:05.754  6934  6934 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 10:27:05.755  1037  1963 I ActivityManager: Killing 7240:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
08-17 10:27:05.773  1037  2028 W libprocessgroup: failed to open /acct/uid_10085/pid_7240/cgroup.procs: No such file or directory
,08-17 10:27:05.788  8192  8192 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-17 10:27:05.791  6934  6934 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-17 10:27:05.797  6934  6934 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 10:27:05.804  8169  8214 W FormManager: Network not available. Please check & try again.
,08-17 10:27:05.812  8169  8215 V FormManager: Network unavailable.
08-17 10:27:05.815  4343  4343 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-17 10:27:05.816  4343  4343 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-17 10:27:05.817  8169  8215 V FormManager: Network unavailable.
08-17 10:27:05.817  4343  4343 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-17 10:27:05.819  4343  4343 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-17 10:27:05.825  4343  8216 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-17 10:27:05.827  4343  8217 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-17 10:27:05.827  4343  8217 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-17 10:27:05.875  1037  1578 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8218 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-17 10:27:06.004  8218  8218 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-17 10:27:06.004  8218  8218 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-17 10:27:06.013  8218  8218 V [BNRBootReceiver]: Boot Receiver Return
08-17 10:27:06.017  8218  8218 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-17 10:27:06.079  1037  1740 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8236 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-17 10:27:06.081  1037  1740 I ActivityManager: Killing 7432:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
08-17 10:27:06.140  1037  8190 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-17 10:27:06.140  1037  8190 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-17 10:27:06.140  8151  8151 E wpa_supplicant: USIM:  scard_init function
08-17 10:27:06.140  1037  8190 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-17 10:27:06.140  1037  8190 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: WPS-AP-AVAILABLE 
08-17 10:27:06.141  1037  8190 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-17 10:27:06.141  8151  8151 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-17 10:27:06.142  1037  1541 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-17 10:27:06.142  1037  1541 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-17 10:27:06.142  1037  1541 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-17 10:27:06.143  1037  1541 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-17 10:27:06.143  1037  1541 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-17 10:27:06.144  1037  8190 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-17 10:27:06.144  1037  8190 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
,08-17 10:27:06.146  1037  2113 W libprocessgroup: failed to open /acct/uid_10005/pid_7432/cgroup.procs: No such file or directory
08-17 10:27:06.154  1037  1541 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=403324  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-17 10:27:06.155  1037  1541 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=403325  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-17 10:27:06.159  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-17 10:27:06.159  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-17 10:27:06.160  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 10:27:06.160  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 10:27:06.160  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-17 10:27:06.160  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-17 10:27:06.160  1037  1037 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-17 10:27:06.162  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 10:27:06.181  8236  8236 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-17 10:27:06.202  8236  8236 D PluginManager: init()
,08-17 10:27:06.255  8151  8151 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-17 10:27:06.255  1037  8190 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-17 10:27:06.255  1037  8190 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-17 10:27:06.255  1037  1120 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-17 10:27:06.255  1037  8190 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-17 10:27:06.255  1037  8190 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-17 10:27:06.256  1037  8190 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-17 10:27:06.256  1037  8190 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,08-17 10:27:06.264  1037  1541 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=403434  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-17 10:27:06.266  1037  1541 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=403435  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-17 10:27:06.267  1037  1541 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=403437
08-17 10:27:06.269  1037  1541 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=403438
08-17 10:27:06.269  1037  1541 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=403439
08-17 10:27:06.270  1037  1541 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=403439
08-17 10:27:06.270  1037  1541 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=403440
08-17 10:27:06.271  1037  1541 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=403440  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-17 10:27:06.272  1037  8190 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-17 10:27:06.272  1037  8190 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-17 10:27:06.272  8151  8151 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-17 10:27:06.272  8151  8151 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-17 10:27:06.274  1037  8190 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-17 10:27:06.274  1037  8190 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-17 10:27:06.274  1037  8190 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-17 10:27:06.274  1037  8190 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-17 10:27:06.275  1037  8190 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-17 10:27:06.275  1037  8190 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-17 10:27:06.276  1037  8190 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-17 10:27:06.276  1037  8190 E WifiMonitor: WifiMonitor:wlan0 cnt=64 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,08-17 10:27:06.277  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 10:27:06.277  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 10:27:06.277  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-17 10:27:06.280  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 10:27:06.280  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-17 10:27:06.281  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 10:27:06.282  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 10:27:06.282  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 10:27:06.282  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-17 10:27:06.283  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 10:27:06.283  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-17 10:27:06.283  1037  1541 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=403450  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-17 10:27:06.284  1037  1541 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
08-17 10:27:06.284  1037  1541 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-17 10:27:06.284  1037  1541 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-17 10:27:06.285  1037  1541 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-17 10:27:06.285  1037  1541 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-17 10:27:06.287  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 10:27:06.287  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-17 10:27:06.287  1037  1037 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-17 10:27:06.288  1037  1541 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 61 0 rt=403457  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-17 10:27:06.289  1037  1541 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 61 0 rt=403458  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-17 10:27:06.289  1037  1541 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=403459
08-17 10:27:06.290  1037  1541 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=403459
08-17 10:27:06.290  1037  1541 D WifiNative-wlan0: doString: [STATUS]
08-17 10:27:06.291  1037  8190 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-17 10:27:06.291  1037  8190 E WifiMonitor: WifiMonitor:wlan0 cnt=65 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-17 10:27:06.292  1037  1541 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
,08-17 10:27:06.294  1037  1541 I WifiServiceExtension: setVHTCapabilityType  : false
,08-17 10:27:06.299  1037  1541 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-17 10:27:06.299  1037  1541 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-17 10:27:06.306  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 10:27:06.306  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 10:27:06.306  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,08-17 10:27:06.307  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 10:27:06.308  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 10:27:06.308  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-17 10:27:06.314  1037  1541 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-17 10:27:06.314  1037  1541 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-17 10:27:06.315  1037  1548 D ConnectivityService: Got NetworkAgent Messenger
08-17 10:27:06.315  1037  1541 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-17 10:27:06.315  1037  1548 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-17 10:27:06.315  1037  1548 D ConnectivityService: NetworkAgent connected
08-17 10:27:06.315  1037  1541 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-17 10:27:06.315  1037  1541 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-17 10:27:06.320  1037  1541 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-17 10:27:06.320  1037  1541 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-17 10:27:06.320  1037  1541 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
,08-17 10:27:06.323  1037  1541 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-17 10:27:06.323  1037  1541 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-17 10:27:06.323  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 10:27:06.323  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-17 10:27:06.324  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 10:27:06.326  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 10:27:06.326  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-17 10:27:06.328  1037  1541 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-17 10:27:06.329  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 10:27:06.331   320   896 D CommandListener: Setting iface cfg
08-17 10:27:06.334  1037  1541 E WifiStateMachine: Start Dhcp Watchdog 3
08-17 10:27:06.334  1037  8257 D DhcpStateMachine: StoppedState
08-17 10:27:06.334  1037  8257 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-17 10:27:06.334  1037  8257 D DhcpStateMachine: WaitBeforeStartState
08-17 10:27:06.334  1037  1541 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=403504  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-17 10:27:06.335  1037  1541 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=403504  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-17 10:27:06.335  1037  1541 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=403505  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-17 10:27:06.336  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-17 10:27:06.336  1037  1037 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
,08-17 10:27:06.338  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-17 10:27:06.338  1037  1037 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-17 10:27:06.339  1037  1541 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 65 0 rt=403509  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-17 10:27:06.340  1037  1541 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 65 0 rt=403509  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-17 10:27:06.340  1037  1541 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 65 0 rt=403510  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-17 10:27:06.342  1037  1541 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:29284] from screen [on:0 period:-1751356187] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-17 10:27:06.342  1037  1541 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1751356186] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-17 10:27:06.342  1037  1541 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-17 10:27:06.347  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 10:27:06.348  1037  1548 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
08-17 10:27:06.348  1037  1541 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
,08-17 10:27:06.349  1037  1541 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 10:27:06.349  1037  1541 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 10:27:06.349  1037  1541 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 10:27:06.350  1037  1541 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 10:27:06.350  1037  1541 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 10:27:06.350  1037  1548 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-17 10:27:06.351  1037  1541 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=187,0,0
08-17 10:27:06.352  1037  1541 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=187,0,0
08-17 10:27:06.352  1037  1541 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-17 10:27:06.352  8151  8151 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-17 10:27:06.353  1037  1541 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-17 10:27:06.353  1037  1541 D WifiNative-wlan0: doBoolean: SET ps 0
08-17 10:27:06.353  1037  1541 D WifiNative-wlan0: SET ps 0: returned true
08-17 10:27:06.353  1037  1541 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-17 10:27:06.354  8151  8151 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-17 10:27:06.354  1037  1541 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-17 10:27:06.354  1037  1540 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@d97dc21 target=com.android.internal.util.StateMachine$SmHandler }
08-17 10:27:06.354  1037  1540 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@d97dc21 target=com.android.internal.util.StateMachine$SmHandler }
08-17 10:27:06.355  1037  1541 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-17 10:27:06.355  1037  1541 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-17 10:27:06.355  1037  1541 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-17 10:27:06.356   320   896 D CommandListener: Setting iface cfg
08-17 10:27:06.356   320   896 D CommandListener: Trying to bring up wlan0
08-17 10:27:06.356  1037  8257 D DhcpStateMachine: WaitBeforeStartState{ when=-1ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-17 10:27:06.356  1037  8257 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-17 10:27:06.357  1037  1541 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-17 10:27:06.358  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-17 10:27:06.358  1037  1037 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-17 10:27:06.360  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-17 10:27:06.360  1037  1037 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-17 10:27:06.361  1037  1541 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK 
,08-17 10:27:06.361  1037  1541 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK 
08-17 10:27:06.361  1037  1541 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-17 10:27:06.362  1037  1540 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-17 10:27:06.362  1037  1540 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,08-17 10:27:06.362  8151  8151 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-17 10:27:06.364  1037  1541 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-17 10:27:06.364  1037  1541 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-17 10:27:06.364  8151  8151 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-17 10:27:06.365  1037  1541 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-17 10:27:06.365  1037  1541 D WifiNative-wlan0: doBoolean: SET ps 1
08-17 10:27:06.380  1037  1541 D WifiNative-wlan0: SET ps 1: returned true
08-17 10:27:06.381  1037  1548 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-17 10:27:06.381  1037  1541 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-17 10:27:06.381  1037  1541 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-17 10:27:06.382  1037  1541 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-17 10:27:06.382  1037  1541 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-17 10:27:06.383  1037  1541 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-17 10:27:06.383  1037  1541 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-17 10:27:06.384  1037  1548 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-17 10:27:06.384  1037  1541 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-17 10:27:06.384  1037  1541 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-17 10:27:06.384  1037  1541 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-17 10:27:06.385  1037  1548 D ConnectivityService: ignoring duplicate network state non-change
08-17 10:27:06.388  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 10:27:06.388  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-17 10:27:06.389  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 10:27:06.391  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 10:27:06.391  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 10:27:06.391  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-17 10:27:06.393  1037  1548 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-17 10:27:06.394  1037  1548 D ConnectivityService: Adding iface wlan0 to network 102
08-17 10:27:06.398  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 10:27:06.398  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 10:27:06.398  1970  1970 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-17 10:27:06.398  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,08-17 10:27:06.406  1037  1541 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-17 10:27:06.408  1037  1037 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-17 10:27:06.409  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 10:27:06.409  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 10:27:06.409  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-17 10:27:06.409  1037  1037 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-17 10:27:06.409  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 10:27:06.409  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 10:27:06.410  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-17 10:27:06.412  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 10:27:06.412  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-17 10:27:06.413  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-17 10:27:06.416  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 10:27:06.416  1605  1605 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-17 10:27:06.417  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 10:27:06.419  1037  1548 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-17 10:27:06.419  1037  1548 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-17 10:27:06.420  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 10:27:06.420  1605  1605 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-17 10:27:06.420  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 10:27:06.421  1037  1548 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
08-17 10:27:06.421   320   896 E Netd    : netlink response contains error (File exists)
08-17 10:27:06.422  1037  1548 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-17 10:27:06.422  1037  1548 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-17 10:27:06.422  1037  1548 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
08-17 10:27:06.422  1037  1548 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
08-17 10:27:06.423  1037  1548 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-17 10:27:06.423  1037  1548 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-17 10:27:06.423  1037  1548 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-17 10:27:06.423  1037  1548 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-17 10:27:06.423  1037  1548 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-17 10:27:06.423  1037  1548 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-17 10:27:06.423  1037  1548 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-17 10:27:06.423  1037  1548 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 10:27:06.423  1037  1548 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-17 10:27:06.424  1037  1548 D ConnectivityService: currentScore = 0, newScore = 20
08-17 10:27:06.424  1037  1548 D ConnectivityService:    accepting network in place of null
08-17 10:27:06.424  1037  1548 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 10:27:06.424  1037  8256 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-17 10:27:06.424  1037  8256 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-17 10:27:06.424  1037  8256 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-17 10:27:06.424  1037  8256 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-17 10:27:,06.426  1037  1541 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 10:27:06.426  1037  1541 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-17 10:27:06.427  1882  1882 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 10:27:06.428  1882  1882 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-17 10:27:06.429   320  8265 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-17 10:27:06.429  1037  1548 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-17 10:27:06.429  1037  1548 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-17 10:27:06.429  1037  1548 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-17 10:27:06.430  1037  1037 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-17 10:27:06.431  1037  1037 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-17 10:27:06.431  1037  1037 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-17 10:27:06.431  1037  1037 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-17 10:27:06.433  1037  1548 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-17 10:27:06.433  1037  1548 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-17 10:27:06.433  1037  1548 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-17 10:27:06.435  1037  1548 D ConnectivityService: validation of new default Network = false
08-17 10:27:06.435  1037  1548 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-17 10:27:06.435  1037  1548 D DSQN    : enableDataServiceNotify 
08-17 10:27:06.435  1037  1548 D DSQN    : start dsqn bin
08-17 10:27:06.429  8267  8267 W dsqn    : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 10:27:06.429  8267  8267 W dsqn    : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-17 10:27:06.441  1037  1548 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-17 10:27:06.441  1037  1548 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 10:27:06.441  1037  1548 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-17 10:27:06.442  1037  1548 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-17 10:27:06.443  1605  1817 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-17 10:27:06.454  8267  8267 E DSQN    : DSQN ssw
,08-17 10:27:06.456  1037  1539 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-17 10:27:06.464  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-17 10:27:06.465  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 10:27:06.465  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-17 10:27:06.482   320  8265 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-17 10:27:06.513   320  8265 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-17 10:27:06.547   320   895 D LGDataListener: argv[0]=dsqncommand
08-17 10:27:06.547   320   895 D LGDataListener: argv[1]=wlan0
08-17 10:27:06.547   320   895 D LGDataListener: argv[2]=1
08-17 10:27:06.547   320   895 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-17 10:27:06.549  1037  1118 D DSQN    : DSQM DsqnNotification wlan0  1
08-17 10:27:06.549  1037  1118 D DSQN    : start to monitor internet connection
,08-17 10:27:06.557  1037  8257 D DhcpStateMachine: DHCPV4 request on wlan0
08-17 10:27:06.558  1037  8257 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-17 10:27:06.558  1037  8257 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-17 10:27:06.549  8273  8273 W dhcpcd  : type=1400 audit(0.0:195): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 10:27:06.549  8273  8273 W dhcpcd  : type=1400 audit(0.0:196): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-17 10:27:06.580  1037  8256 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 17 Aug 2016 08:27:06 GMT], X-Android-Received-Millis=[1471422426580], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1471422426546]}
08-17 10:27:06.581  1037  8256 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-17 10:27:06.581  1037  8256 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-17 10:27:06.581  1037  1548 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
,08-17 10:27:06.581  1037  1548 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-17 10:27:06.581  1037  1548 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-17 10:27:06.581  1037  1548 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-17 10:27:06.581  1037  1548 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-17 10:27:06.581  1037  1548 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-17 10:27:06.581  1037  1548 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-17 10:27:06.581  1037  1548 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 10:27:06.582  1037  1548 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-17 10:27:06.582  1037  1548 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-17 10:27:06.582  1037  1548 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 10:27:06.582  1037  1548 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-17 10:27:06.583  1037  1541 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 10:27:06.583  1037  1541 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-17 10:27:06.584  1882  1882 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 10:27:06.584  1882  1882 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-17 10:27:06.585  1605  1817 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-17 10:27:06.587  8273  8273 I dhcpcd  : version 5.5.6 starting
,08-17 10:27:06.590  8273  8273 E dhcpcd  : get_duid: m
08-17 10:27:06.590  8273  8273 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-17 10:27:06.590  8273  8273 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-17 10:27:06.605  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-17 10:27:06.606  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 10:27:06.607  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-17 10:27:06.632  8236  8236 W ExternalStrings: load override strings
08-17 10:27:06.632  8236  8236 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
08-17 10:27:06.632  8236  8236 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
08-17 10:27:06.632  8236  8236 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
08-17 10:27:06.632  8236  8236 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
08-17 10:27:06.632  8236  8236 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
08-17 10:27:06.632  8236  8236 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
08-17 10:27:06.632  8236  8236 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
08-17 10:27:06.632  8236  8236 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-17 10:27:06.632  8236  8236 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-17 10:27:06.632  8236  8236 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-17 10:27:06.632  8236  8236 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-17 10:27:06.632  8236  8236 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 10:27:06.632  8236  8236 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
08-17 10:27:06.632  8236  8236 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-17 10:27:06.632  8236  8236 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 10:27:06.632  8236  8236 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 10:27:06.632  8236  8236 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-17 10:27:06.632  8236  8236 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-17 10:27:06.633  8236  8236 D StatusProvider: onCreate
,08-17 10:27:06.658  8273  8273 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-17 10:27:06.658  8273  8273 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
,08-17 10:27:06.658  8273  8273 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,08-17 10:27:06.659  8273  8273 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
08-17 10:27:06.659  8273  8273 D dhcpcd  : wlan0: sending REQUEST (xid 0xa0b84623), next in 3.23 seconds
08-17 10:27:06.668  8236  8236 V Signer  : override build config not found
08-17 10:27:06.668  8236  8236 D Signer  : value of property debug is false
08-17 10:27:06.684  8273  8273 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,08-17 10:27:06.691  8236  8236 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
,08-17 10:27:06.692  8236  8236 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
08-17 10:27:06.692  8236  8236 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
08-17 10:27:06.692  8236  8236 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
,08-17 10:27:06.692  8236  8236 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
08-17 10:27:06.692  8236  8236 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
08-17 10:27:06.692  8236  8236 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
08-17 10:27:06.693  8236  8236 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
08-17 10:27:06.693  8236  8236 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
08-17 10:27:06.693  8236  8236 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
08-17 10:27:06.693  8236  8236 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
08-17 10:27:06.693  8236  8236 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
08-17 10:27:06.693  8236  8236 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
08-17 10:27:06.700  8236  8236 V LGMDMManager: Create singleton instance
,08-17 10:27:06.708  8273  8273 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
08-17 10:27:06.709  8273  8273 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
08-17 10:27:06.709  8273  8273 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-17 10:27:06.709  8273  8273 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-17 10:27:06.709  8273  8273 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-17 10:27:06.710  8273  8273 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-17 10:27:06.710  8273  8273 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-17 10:27:06.710  8273  8273 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-17 10:27:06.737  8236  8236 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
,08-17 10:27:06.827  8236  8236 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-17 10:27:06.841  6934  6934 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-17 10:27:06.844  8236  8288 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-17 10:27:06.849  6934  6934 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 10:27:06.859  6996  6996 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-17 10:27:06.859  6996  6996 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-17 10:27:06.860  6996  6996 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-17 10:27:06.865  8236  8236 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-17 10:27:06.866  8236  8288 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-17 10:27:06.879  6934  6934 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-17 10:27:06.890  6934  6934 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 10:27:06.897  6996  6996 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-17 10:27:06.897  6996  6996 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-17 10:27:06.898  6996  6996 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-17 10:27:06.901  6934  6934 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-17 10:27:06.910  6934  6934 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
,08-17 10:27:06.914  8236  8288 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-17 10:27:06.914  8236  8236 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-17 10:27:06.922  6934  6934 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-17 10:27:06.929  6934  6934 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 10:27:06.938  6996  6996 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-17 10:27:06.939  6996  6996 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-17 10:27:06.939  6996  6996 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-17 10:27:06.942  6934  6934 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-17 10:27:06.942  6934  6934 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-17 10:27:06.942  6934  6934 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-17 10:27:06.942  6934  6934 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-17 10:27:06.943  6934  6934 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-17 10:27:06.944  6934  6934 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-17 10:27:06.944  6934  6934 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-17 10:27:06.944  6934  6934 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-17 10:27:06.944  6934  6934 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-17 10:27:06.944  6934  6934 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-17 10:27:06.944  6934  6934 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-17 10:27:06.944  6934  6934 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-17 10:27:07.024  8236  8236 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-17 10:27:07.025  8236  8288 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-17 10:27:07.026  8236  8286 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-17 10:27:07.040  6934  6934 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-17 10:27:07.046  6934  6934 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 10:27:07.052  6996  6996 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-17 10:27:07.052  6996  6996 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-17 10:27:07.053  6996  6996 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-17 10:27:07.056  8236  8236 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-17 10:27:07.056  8236  8288 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-17 10:27:07.061  6934  6934 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-17 10:27:07.065  6934  6934 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 10:27:07.074  6996  6996 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-17 10:27:07.075  6996  6996 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-17 10:27:07.076  6996  6996 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-17 10:27:07.082  8236  8236 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-17 10:27:07.082  8236  8288 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-17 10:27:07.093  6934  6934 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-17 10:27:07.101  6934  6934 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 10:27:07.110  6996  6996 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-17 10:27:07.111  6996  6996 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-17 10:27:07.111  6996  6996 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-17 10:27:07.114  8236  8236 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-17 10:27:07.114  8236  8288 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-17 10:27:07.120  6934  6934 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-17 10:27:07.124  6934  6934 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 10:27:07.135  6996  6996 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-17 10:27:07.136  6996  6996 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-17 10:27:07.137  6996  6996 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-17 10:27:07.146  8236  8236 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-17 10:27:07.147  8236  8288 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-17 10:27:07.160  1037  8257 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-17 10:27:07.161  1037  8257 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-17 10:27:07.162  1037  8257 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-17 10:27:07.162  1037  8257 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
08-17 10:27:07.162  1037  8257 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-17 10:27:07.162  1037  8257 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-17 10:27:07.162  1037  8257 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-17 10:27:07.162  1037  8257 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-17 10:27:07.163  1037  8257 D DhcpStateMachine: RunningState
08-17 10:27:07.171  6934  6934 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-17 10:27:07.175  6934  6934 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 10:27:07.186  6996  6996 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-17 10:27:07.187  6996  6996 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-17 10:27:07.189  6996  6996 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-17 10:27:07.193  8236  8236 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-17 10:27:07.194  8236  8288 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-17 10:27:07.200  6934  6934 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-17 10:27:07.208  6934  6934 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-17 10:27:07.213  6996  6996 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-17 10:27:07.213  6996  6996 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-17 10:27:07.214  6996  6996 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-17 10:27:07.218  8236  8236 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-17 10:27:07.218  8236  8288 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-17 10:27:07.222  8192  8192 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-17 10:27:07.226  8192  8192 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,08-17 10:27:07.230  6934  6934 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-17 10:27:07.235  6934  6934 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 10:27:07.244  6996  6996 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-17 10:27:07.244  6996  6996 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-17 10:27:07.245  6996  6996 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-17 10:27:07.246  6996  6996 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-17 10:27:07.246  6996  6996 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-17 10:27:07.251  8236  8236 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-17 10:27:07.251  8236  8286 D LgDataFeature: LgDataFeature() Constructor: none
08-17 10:27:07.251  8236  8288 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-17 10:27:07.251  8236  8286 D LgDataFeature: LgDataFeature() Constructor Done, null
08-17 10:27:07.255  8192  8192 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-17 10:27:07.256  8192  8192 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,08-17 10:27:07.259  6934  6934 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-17 10:27:07.266  6934  6934 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 10:27:07.279  6996  6996 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-17 10:27:07.280  6996  6996 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-17 10:27:07.281  6996  6996 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-17 10:27:07.282  6996  6996 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-17 10:27:07.282  6996  6996 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-17 10:27:07.290  8236  8236 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-17 10:27:07.294  8236  8236 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
,08-17 10:27:07.298  8236  8236 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-17 10:27:07.300  8236  8236 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-17 10:27:07.309  8236  8236 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
,08-17 10:27:07.311  8236  8236 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-17 10:27:07.314  8236  8236 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-17 10:27:07.316  8236  8236 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-17 10:27:07.319  8236  8236 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-17 10:27:07.322  8236  8236 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
,08-17 10:27:07.325  8236  8236 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-17 10:27:07.326  1037  2044 I ActivityManager: Killing 7259:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
08-17 10:27:07.361  1037  1541 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-17 10:27:07.362  1037  1541 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-17 10:27:07.363  1037  1541 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-17 10:27:07.364  1037  1541 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-17 10:27:07.365  1037  1541 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-17 10:27:07.367  1037  1541 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-17 10:27:07.370  1037  1548 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
08-17 10:27:07.370  1037  1548 D ConnectivityService: identical MTU - not setting
08-17 10:27:07.370  1037  1548 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-17 10:27:07.370  1037  1548 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-17 10:27:07.371  1037  1548 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 10:27:07.371  1037  1548 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-17 10:27:07.371  1037  1548 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-17 10:27:07.372  1605  1817 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-17 10:27:07.383  8236  8286 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
,08-17 10:27:07.435  1037  1054 W libprocessgroup: failed to open /acct/uid_10093/pid_7259/cgroup.procs: No such file or directory
,08-17 10:27:07.461  8236  8286 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
,08-17 10:27:07.489  8236  8286 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
08-17 10:27:07.490  8236  8286 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-17 10:27:07.491  8236  8286 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
,08-17 10:27:07.494  8236  8286 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
08-17 10:27:07.495  8236  8286 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
08-17 10:27:07.504  8236  8286 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
,08-17 10:27:07.509  8236  8286 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
,08-17 10:27:09.352  1037  1541 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2447 sc=60 link=72 tx=93.5, 0.0, 0.0  rx=99.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1751353176] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-17 10:27:09.355  1037  1541 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2447 sc=60 link=72 tx=93.5, 0.0, 0.0  rx=99.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1751353173] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-17 10:27:09.355  1037  1541 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-17 10:27:09.372  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-17 10:27:09.411  1037  1542 V WifiInternetCheck: Single check msg out of sync, ignoring.
,08-17 10:27:09.435  1037  1548 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-17 10:27:09.452  1037  1120 D Tethering: MasterInitialState.processMessage what=3
08-17 10:27:09.471  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:27:09.471  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:27:09.471  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 10:27:09.471  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 10:27:09.471  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 10:27:09.471  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 10:27:09.471  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 10:27:09.471  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 10:27:09.477  6772  6772 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 10:27:09.482  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:27:09.482  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:27:09.482  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 10:27:09.482  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 10:27:09.482  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 10:27:09.482  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 10:27:09.482  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 10:27:09.482  6772  6772 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 10:27:09.483  6772  6772 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 10:27:09.490  1037  1097 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-17 10:27:09.495  8236  8236 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-17 10:27:09.506  5293  5293 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,08-17 10:27:09.529  1037  1097 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-17 10:27:09.540  8236  8286 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-17 10:27:09.554  2249  2249 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-17 10:27:09.571  1037  1985 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 102]) by 10005
,08-17 10:27:09.574  1037  8256 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-2ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-17 10:27:09.574  1037  8256 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-17 10:27:09.574  1037  8256 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-17 10:27:09.574  1037  8256 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-17 10:27:09.574  1037  8256 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-17 10:27:09.584   320  8331 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-17 10:27:09.587   320  8331 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
08-17 10:27:09.593  7107  7107 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-17 10:27:09.593  7107  7107 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-17 10:27:09.593  7107  7107 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-17 10:27:09.593  7107  7107 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-17 10:27:09.595  7107  7107 I AppUp4:CustModeStarterReceiver: onReceive
,08-17 10:27:09.602  7107  7107 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@38e3d673
08-17 10:27:09.602  7107  7107 D AppUp4:CustFacade: isCustomizationCompleted : false
08-17 10:27:09.602  7107  7107 D AppUp4:CustFacade: isPhone : true
08-17 10:27:09.602  7107  7107 D AppUp4:CustModeStarterReceiver: begin check event
08-17 10:27:09.602  7107  7107 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-17 10:27:09.607  4343  4343 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-17 10:27:09.607  4343  4343 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-17 10:27:09.609  4343  4343 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-17 10:27:09.615  1037  8256 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 17 Aug 2016 08:27:09 GMT], X-Android-Received-Millis=[1471422429614], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1471422429577]}
08-17 10:27:09.615  1037  8256 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-17 10:27:09.615  1037  8256 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-17 10:27:09.615  1037  1548 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
08-17 10:27:09.616  1037  1548 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-17 10:27:09.616  1037  1548 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-17 10:27:09.616  1037  1548 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-17 10:27:09.616  1037  1548 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-17 10:27:09.616  1037  1548 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-17 10:27:09.616  1037  1548 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-17 10:27:09.616  1037  1548 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 10:27:09.616  1037  1548 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-17 10:27:09.616  1037  1548 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-17 10:27:09.617  1605  1817 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-17 10:27:09.624   320  8331 D libc-netbsd: res_queryN name = mtalk.google.com succeed
08-17 10:27:09.626  4343  4343 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-17 10:27:09.634  3484  3484 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,08-17 10:27:09.638  3484  3484 V DownloadManager: DownloadService onCreate
08-17 10:27:09.638  4343  8344 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-17 10:27:09.643  4343  8344 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
08-17 10:27:09.643  4343  8345 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-17 10:27:09.643  4343  8345 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-17 10:27:09.644  3484  8349 I DownloadManager: in removeSpuriousFiles
08-17 10:27:09.644  3484  8349 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
08-17 10:27:09.646  3484  8349 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@2028913e on behalf of 3484
08-17 10:27:09.647  3484  8349 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
,08-17 10:27:09.648  3484  8349 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
,08-17 10:27:09.648  3484  8349 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
08-17 10:27:09.648  3484  8349 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
08-17 10:27:09.648  3484  8349 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
08-17 10:27:09.648  3484  8349 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
08-17 10:27:09.648  3484  8349 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
08-17 10:27:09.648  3484  8349 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
,08-17 10:27:09.648  3484  8349 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
08-17 10:27:09.648  3484  8349 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
,08-17 10:27:09.648  3484  8349 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
08-17 10:27:09.649  3484  8349 I DownloadManager: in trimDatabase
08-17 10:27:09.649  3484  8349 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
08-17 10:27:09.651  3484  8349 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@111af4ec on behalf of 3484
08-17 10:27:09.687  6772  6842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:27:09.687  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:27:09.687  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 10:27:09.687  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 10:27:09.687  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 10:27:09.687  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 10:27:09.687  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 10:27:09.687  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 10:27:09.688  6772  6842 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 10:27:09.689  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:27:09.689  6772  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3424ab98 removed from the list
,08-17 10:27:09.689  6772  6842 D io.jxcore.node.ConnectivityMonitor: stop
08-17 10:27:09.689  6772  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:27:09.689  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 10:27:09.689  1037  1740 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=8352 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-17 10:27:09.699  3484  3484 V DownloadManager: DownloadService onStartCommand
08-17 10:27:09.704  6772  8359 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
08-17 10:27:09.704  6772  8359 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-17 10:27:09.704  3484  8350 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,08-17 10:27:09.710  3484  8350 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@2498834a on behalf of 3484
08-17 10:27:09.712  4343  8344 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
08-17 10:27:09.716  3484  8350 V DownloadManager: processing inserted download 1
,08-17 10:27:09.717  3484  8350 V DownloadManager: processing inserted download 4
08-17 10:27:09.719  3484  8350 V DownloadManager: processing inserted download 7
08-17 10:27:09.723  3484  8350 V DownloadManager: processing inserted download 8
08-17 10:27:09.724  3484  8350 V DownloadManager: processing inserted download 9
08-17 10:27:09.725  3484  8350 V DownloadManager: processing inserted download 10
08-17 10:27:09.726  3484  8350 V DownloadManager: processing inserted download 11
08-17 10:27:09.726  3484  8350 V DownloadManager: processing inserted download 12
08-17 10:27:09.727  3484  8350 V DownloadManager: processing inserted download 13
08-17 10:27:09.728  3484  8350 V DownloadManager: processing inserted download 14
08-17 10:27:09.729  3484  8350 V DownloadManager: processing inserted download 16
,08-17 10:27:09.731  3484  3484 V DownloadManager: DownloadService onDestroy
08-17 10:27:09.731  4343  4343 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
08-17 10:27:09.732  4343  4343 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
08-17 10:27:09.732  4343  4343 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
08-17 10:27:09.733  4343  4343 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
08-17 10:27:09.737  4343  4343 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
08-17 10:27:09.750  8352  8352 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-17 10:27:09.750  8352  8352 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-17 10:27:09.751  8352  8352 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-17 10:27:09.752  8352  8352 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-17 10:27:09.830  8352  8352 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-17 10:27:09.846  8352  8352 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
08-17 10:27:09.899  8352  8352 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-17 10:27:09.938  8352  8352 D LgDataFeature: LgDataFeature() Constructor: none
08-17 10:27:09.938  8352  8352 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-17 10:27:10.124  8352  8352 D eas_req : ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-17 10:27:10.180  8352  8352 I HubEmail: JNI_OnLoad()
08-17 10:27:10.180  8352  8352 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-17 10:27:10.180  8352  8352 I HubEmail: registerNatives()
08-17 10:27:10.180  8352  8352 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-17 10:27:10.180  8352  8352 I HubEmail: registerNativeMethods()
08-17 10:27:10.180  8352  8352 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-17 10:27:10.181  8352  8352 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,08-17 10:27:10.199  8352  8386 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-17 10:27:10.208  3438  3438 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-17 10:27:10.208  3438  3438 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-17 10:27:10.208  3438  3438 I LgeMiscReceiver: networkInfo.isConnected() = true
08-17 10:27:10.208  3438  3438 D PhoneState: setPdpRejectCasuse : false
08-17 10:27:10.229   320  8389 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-17 10:27:10.231   320  8389 D libc-netbsd: res_queryN name = static-avc.lglime.com, class = 1, type = 1
08-17 10:27:10.251  1037  1053 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=8390 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-17 10:27:10.292   320  8389 D libc-netbsd: res_queryN name = static-avc.lglime.com succeed
08-17 10:27:10.328  8169  8385 V FormManager: There are no updated forms. The schedule will be deleted.
,08-17 10:27:10.331  8169  8385 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
08-17 10:27:10.352  1037  1816 I ActivityManager: Killing 7766:com.google.android.talk/u0a72 (adj 15): empty #17
,08-17 10:27:10.360  8390  8390 D LgDataFeature: LgDataFeature() Constructor: none
08-17 10:27:10.360  8390  8390 D LgDataFeature: LgDataFeature() Constructor Done, null
08-17 10:27:10.363  8390  8390 D PhoneMonitor: Register our PhoneStateListener
,08-17 10:27:10.381  1037  1658 W libprocessgroup: failed to open /acct/uid_10072/pid_7766/cgroup.procs: No such file or directory
,08-17 10:27:10.388  8390  8390 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-17 10:27:10.390  8390  8390 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-17 10:27:10.399  8390  8390 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
08-17 10:27:10.400  8390  8390 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-17 10:27:10.400  8390  8390 D TelephonyAutoProfiling: [parse] Load xml
08-17 10:27:10.402  8390  8390 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-17 10:27:10.403  8390  8390 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-17 10:27:10.403  8390  8390 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-17 10:27:10.403  8390  8390 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-17 10:27:10.403  8390  8390 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-17 10:27:10.403  8390  8390 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-17 10:27:10.403  8390  8390 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-17 10:27:10.403  8390  8390 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-17 10:27:10.403  8390  8390 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-17 10:27:10.403  8390  8390 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-17 10:27:10.403  8390  8390 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-17 10:27:10.403  8390  8390 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-17 10:27:10.403  8390  8390 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-17 10:27:10.403  8390  8390 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-17 10:27:10.403  8390  8390 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-17 10:27:10.403  8390  8390 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-17 10:27:10.403  8390  8390 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-17 10:27:10.409  8390  8390 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-17 10:27:10.429  1037  2117 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=8421 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-17 10:27:10.430  1037  2117 I ActivityManager: Killing 7810:com.android.contacts/u0a19 (adj 15): empty #17
,08-17 10:27:10.480  1037  2074 W libprocessgroup: failed to open /acct/uid_10019/pid_7810/cgroup.procs: No such file or directory
,08-17 10:27:10.516  1847  8438 I CheckinService: active receiver: enabled
,08-17 10:27:10.535  1847  8438 I CheckinService: Preparing to send checkin request
08-17 10:27:10.535  1847  8438 I EventLogService: Accumulating logs since 1471422391201
08-17 10:27:10.579  1847  8438 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-17 10:27:10.625   320  8444 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-17 10:27:10.625   320  8444 D libc-netbsd: res_queryN name = www.google.com, class = 1, type = 1
,08-17 10:27:10.656   320  8444 D libc-netbsd: res_queryN name = www.google.com succeed
,08-17 10:27:10.660   320  8446 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-17 10:27:10.661   320  8446 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-17 10:27:10.661   320  8446 D libc-netbsd: res_queryN name = clients3.google.com succeed
08-17 10:27:10.669  1037  1963 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=8447 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-17 10:27:10.715  1037  1658 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=8464 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
08-17 10:27:10.716  1037  1658 I ActivityManager: Killing 7834:com.android.gallery3d/u0a27 (adj 15): empty #17
,08-17 10:27:10.727  1037  1543 V WifiInternetCheck: isHttpConnectionAvailable - We got a valid response : 204
,08-17 10:27:10.832  1037  2028 W libprocessgroup: failed to open /acct/uid_10027/pid_7834/cgroup.procs: No such file or directory
,08-17 10:27:10.878  8447  8447 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-17 10:27:10.878  8447  8447 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-17 10:27:10.911  8447  8447 I MultiDex: VM with version 2.1.0 has multidex support
08-17 10:27:10.911  8447  8447 I MultiDex: install
08-17 10:27:10.911  8447  8447 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-17 10:27:10.952  1037  1985 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=8482 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-17 10:27:10.953  1037  1985 I ActivityManager: Killing 7853:com.android.vending/u0a44 (adj 15): empty #17
08-17 10:27:11.030  1037  1541 E WifiStateMachine:  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,08-17 10:27:11.031  1037  1541 E WifiStateMachine:  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-17 10:27:11.032  1037  1541 E WifiStateMachine:  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-17 10:27:11.033  1037  1541 E WifiStateMachine:  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-17 10:27:11.034  1037  1541 E WifiStateMachine:  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-17 10:27:11.035  1037  1541 E WifiStateMachine:  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-17 10:27:11.043  1037  1658 W libprocessgroup: failed to open /acct/uid_10044/pid_7853/cgroup.procs: No such file or directory
,08-17 10:27:11.065  8447  8447 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,08-17 10:27:11.238  1037  2074 I art     : Explicit concurrent mark sweep GC freed 78655(3MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 2.700ms total 156.303ms
,08-17 10:27:11.261  8482  8482 I art     : Almond Protected OAT
,08-17 10:27:11.308  8482  8482 D WeatherApplication: removeAccount
,08-17 10:27:11.311  8482  8482 D WeatherApplication: Account.length = 0
08-17 10:27:11.311  8482  8482 E WeatherApplication: OPERATOR:OPEN
,08-17 10:27:11.316  8482  8482 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:27:11
08-17 10:27:11.319  8482  8482 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-17 10:27:11.319  8482  8482 D Weather.Utils: 2 : All the weather widget is gone.
08-17 10:27:11.321  8482  8482 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-17 10:27:11.323  8482  8482 D WeatherAncestor: connectivity changed - connection : true
08-17 10:27:11.324  8482  8482 D WeatherService: 2 : isServiceAlived():false forecastCache:null
08-17 10:27:11.331  8482  8482 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-17 10:27:11.331  8482  8482 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-17 10:27:11.331  8482  8482 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
,08-17 10:27:11.353  8482  8482 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-17 10:27:11.353  8482  8482 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:27:11
,08-17 10:27:11.407  1037  1816 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=8501 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-17 10:27:11.414  1037  1816 I ActivityManager: Killing 7905:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
08-17 10:27:11.421   344   344 I art     : Explicit concurrent mark sweep GC freed 703(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 368us total 20.915ms
08-17 10:27:11.439   344   344 I art     : Explicit concurrent mark sweep GC freed 8(256B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 340us total 16.844ms
,08-17 10:27:11.455   344   344 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 329us total 15.333ms
,08-17 10:27:11.469  8447  8463 D LgDataFeature: LgDataFeature() Constructor: none
,08-17 10:27:11.469  8447  8463 D LgDataFeature: LgDataFeature() Constructor Done, null
08-17 10:27:11.519  1037  1740 W libprocessgroup: failed to open /acct/uid_10080/pid_7905/cgroup.procs: No such file or directory
,08-17 10:27:11.684   278   352 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-17 10:27:11.684   278   352 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-17 10:27:11.684   278   352 W Vold    : Returning OperationFailed - no handler for errno 0
,08-17 10:27:11.688  8501  8519 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-17 10:27:11.692   278   352 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-17 10:27:11.692   278   352 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-17 10:27:11.692   278   352 W Vold    : Returning OperationFailed - no handler for errno 0
08-17 10:27:11.693  8501  8519 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-17 10:27:11.705   278   352 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-17 10:27:11.705   278   352 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-17 10:27:11.705   278   352 W Vold    : Returning OperationFailed - no handler for errno 0
08-17 10:27:11.706  8501  8523 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,08-17 10:27:11.709   278   352 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-17 10:27:11.710   278   352 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-17 10:27:11.710   278   352 W Vold    : Returning OperationFailed - no handler for errno 0
08-17 10:27:11.713  8501  8523 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-17 10:27:11.799  8525  8525 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-17 10:27:11.860  8525  8525 I dex2oat : dex2oat took 61.135ms (threads: 4)
,08-17 10:27:11.877  8447  8463 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-17 10:27:11.877  8447  8463 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-17 10:27:11.877  8447  8463 I Adreno-EGL: Build Date: 12/12/14 금
08-17 10:27:11.877  8447  8463 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-17 10:27:11.877  8447  8463 I Adreno-EGL: Remote Branch: 
08-17 10:27:11.877  8447  8463 I Adreno-EGL: Local Patches: 
08-17 10:27:11.877  8447  8463 I Adreno-EGL: Reconstruct Branch: 
08-17 10:27:11.936  8501  8501 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-17 10:27:11.954  8501  8501 I LibraryLoader: Loading: webviewchromium
08-17 10:27:11.957  8501  8501 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 9134-9138)
08-17 10:27:11.957  8501  8501 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-17 10:27:11.963  8501  8501 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2f5ec7ea}
08-17 10:27:11.965  8501  8501 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-17 10:27:11.965  8501  8501 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-17 10:27:11.978  8501  8501 I BrowserStartupController: Initializing chromium process, renderers=0
,08-17 10:27:11.979  8501  8501 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-17 10:27:12.001  8501  8501 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-17 10:27:12.002  8501  8501 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-17 10:27:12.003  8501  8501 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-17 10:27:12.006   324  1389 V AudioPolicyService: registerClient() client 0xb1021b60, uid 10093
08-17 10:27:12.007  8501  8550 W AudioManagerAndroid: Requires BLUETOOTH permission
08-17 10:27:12.008  8447  8463 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-17 10:27:12.008  8447  8463 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-17 10:27:12.008  8447  8463 I Adreno-EGL: Build Date: 12/12/14 금
08-17 10:27:12.008  8447  8463 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-17 10:27:12.008  8447  8463 I Adreno-EGL: Remote Branch: 
08-17 10:27:12.008  8447  8463 I Adreno-EGL: Local Patches: 
08-17 10:27:12.008  8447  8463 I Adreno-EGL: Reconstruct Branch: 
08-17 10:27:12.029  8501  8501 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-17 10:27:12.029  8501  8501 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-17 10:27:12.029  8501  8501 I Adreno-EGL: Build Date: 12/12/14 금
08-17 10:27:12.029  8501  8501 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-17 10:27:12.029  8501  8501 I Adreno-EGL: Remote Branch: 
08-17 10:27:12.029  8501  8501 I Adreno-EGL: Local Patches: 
08-17 10:27:12.029  8501  8501 I Adreno-EGL: Reconstruct Branch: 
,08-17 10:27:12.092  8447  8463 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-17 10:27:12.092  8447  8463 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-17 10:27:12.092  8447  8463 I Adreno-EGL: Build Date: 12/12/14 금
08-17 10:27:12.092  8447  8463 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-17 10:27:12.092  8447  8463 I Adreno-EGL: Remote Branch: 
08-17 10:27:12.092  8447  8463 I Adreno-EGL: Local Patches: 
08-17 10:27:12.092  8447  8463 I Adreno-EGL: Reconstruct Branch: 
,08-17 10:27:12.112  8501  8501 I NSApplication: Starting up...
08-17 10:27:12.134  1037  1054 I ActivityManager: Killing 7617:com.lge.lifetracker/u0a37 (adj 15): empty #17
,08-17 10:27:12.261  1037  1053 W libprocessgroup: failed to open /acct/uid_10037/pid_7617/cgroup.procs: No such file or directory
,08-17 10:27:12.289  2249  2249 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,08-17 10:27:12.303  2249  2249 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
08-17 10:27:12.303  2249  2249 D c       : Getting all permits...
08-17 10:27:12.303  2249  2249 D a       : Opening database...
,08-17 10:27:12.308  2249  2249 D a       : Opening database auth.proximity.permit_store...
08-17 10:27:12.311  2249  2249 D a       : Closing database...
08-17 10:27:12.351   320  8567 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-17 10:27:12.351   320  8567 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
,08-17 10:27:12.379  1037  1541 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=52.2, 0.0, 0.0  rx=53.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1751350149] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-17 10:27:12.382  1037  1541 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=52.2, 0.0, 0.0  rx=53.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1751350146] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-17 10:27:12.382  1037  1541 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-17 10:27:12.696   320  8567 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,08-17 10:27:12.722  6772  8359 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
08-17 10:27:12.723  6772  8359 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-17 10:27:12.723  6772  8359 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-17 10:27:12.723  6772  8359 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-17 10:27:12.724  6772  8359 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,08-17 10:27:12.728  6772  8574 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
08-17 10:27:12.728  6772  8574 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-17 10:27:12.728  6772  8574 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-17 10:27:12.729  6772  8574 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-17 10:27:12.729  6772  8574 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
08-17 10:27:12.732  6772  8578 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 869, name: IncomingSocketThread/Sender)
08-17 10:27:12.734  6772  8577 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 868, name: OutgoingSocketThread/Receiver)
08-17 10:27:12.734  6772  8577 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 868, thread name: OutgoingSocketThread/Receiver)
08-17 10:27:12.734  6772  8577 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-17 10:27:12.735  6772  8577 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 868, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
08-17 10:27:12.737  6772  8579 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 870, name: IncomingSocketThread/Receiver)
08-17 10:27:12.737  6772  8579 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 870, thread name: IncomingSocketThread/Receiver)
08-17 10:27:12.737  6772  8579 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-17 10:27:12.737  6772  8579 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 870, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,08-17 10:27:12.744  6772  8576 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 867, name: OutgoingSocketThread/Sender)
08-17 10:27:12.926  1847  8438 I CheckinTask: Sending checkin request (7850 bytes)
,08-17 10:27:13.200  2249  2265 I art     : Explicit concurrent mark sweep GC freed 7279(476KB) AllocSpace objects, 4(64KB) LOS objects, 52% free, 29MB/61MB, paused 2.294ms total 38.514ms
,08-17 10:27:13.217  1847  8438 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,08-17 10:27:13.234  1847  8438 I CheckinService: active receiver: disabled
,08-17 10:27:13.256  2249  2249 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-17 10:27:13.283  2249  2249 I GCM     : GCM config loaded
,08-17 10:27:13.301   320  8582 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-17 10:27:13.304   320  8582 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
08-17 10:27:13.304   320  8582 D libc-netbsd: res_queryN name = mtalk.google.com succeed
,08-17 10:27:13.312  8390  8390 V SetupWizard: Connected to Gservices successfully
,08-17 10:27:13.667  2249  8595 D GCM     : Connected
,08-17 10:27:13.700  2249  8595 D GCM     : Message class com.google.e.a.a.q
,08-17 10:27:15.395  1037  1541 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=36.6, 0.0, 0.0  rx=34.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1751347133] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-17 10:27:15.406  1037  1541 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=36.6, 0.0, 0.0  rx=34.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1751347123] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-17 10:27:15.406  1037  1541 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-17 10:27:15.724  6772  6842 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-17 10:27:15.726  6772  6842 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-17 10:27:15.735  6772  6842 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@687e1d Bundle[{}]
08-17 10:27:15.736  6772  6842 I io.jxcore.node.LifeCycleMonitor: start: OK
08-17 10:27:15.736  6772  6842 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-17 10:27:15.737  6772  6842 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-17 10:27:15.737  6772  6842 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-17 10:27:15.738  6772  6842 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-17 10:27:15.739  6772  6842 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-17 10:27:15.746  6772  6842 I System.out: Running OutgoingSocketThread
08-17 10:27:15.748  6772  8603 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
08-17 10:27:15.748  6772  8603 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-17 10:27:16.706  8501  8521 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,08-17 10:27:17.356  1037  1578 I ActivityManager: Killing 7661:com.lge.settings.easy/1000 (adj 15): empty #17
,08-17 10:27:17.391  1037  1983 W libprocessgroup: failed to open /acct/uid_1000/pid_7661/cgroup.procs: No such file or directory
,08-17 10:27:18.421  1037  1541 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=28.3, 0.0, 0.0  rx=27.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1751344107] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-17 10:27:18.424  1037  1541 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=28.3, 0.0, 0.0  rx=27.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1751344104] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-17 10:27:18.424  1037  1541 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-17 10:27:18.761  6772  8603 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
08-17 10:27:18.761  6772  8603 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-17 10:27:18.761  6772  8603 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-17 10:27:18.765  6772  8603 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-17 10:27:18.765  6772  8603 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
08-17 10:27:18.767  6772  8606 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
08-17 10:27:18.767  6772  8606 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-17 10:27:18.767  6772  8606 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-17 10:27:18.767  6772  8606 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-17 10:27:18.767  6772  8606 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
08-17 10:27:18.770  6772  8609 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 880, name: OutgoingSocketThread/Receiver)
08-17 10:27:18.770  6772  8609 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 880, thread name: OutgoingSocketThread/Receiver)
08-17 10:27:18.770  6772  8609 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-17 10:27:18.770  6772  8609 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 880, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
08-17 10:27:18.772  6772  8608 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 879, name: OutgoingSocketThread/Sender)
08-17 10:27:18.774  6772  8611 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 882, name: IncomingSocketThread/Receiver)
08-17 10:27:18.774  6772  8611 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 882, thread name: IncomingSocketThread/Receiver)
08-17 10:27:18.774  6772  8611 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-17 10:27:18.774  6772  8611 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 882, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
08-17 10:27:18.778  6772  8610 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 881, name: IncomingSocketThread/Sender)
,08-17 10:27:20.606  1605  1605 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-17 10:27:20.702  1037  1037 D administrator: Handling package changes for user 0
,08-17 10:27:20.722  1037  1099 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=8612 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-17 10:27:20.740  1605  1605 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
,08-17 10:27:20.745  1605  1605 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
08-17 10:27:20.746  2096  2096 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
08-17 10:27:20.759  1037  1444 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-17 10:27:20.766  2096  2096 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-17 10:27:20.812  8612  8612 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-17 10:27:20.870  1037  1037 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
,08-17 10:27:20.870  1037  1037 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-17 10:27:20.908  8612  8612 D LgDataFeature: LgDataFeature() Constructor: none
08-17 10:27:20.908  8612  8612 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-17 10:27:20.934  1037  1097 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-17 10:27:20.944  1037  1097 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-17 10:27:20.954  2096  2096 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-17 10:27:20.955  2512  2512 V GmsNetworkLocationProvi: DISABLE
,08-17 10:27:20.984  1037  1097 D LocationProviderProxy: applying state to connected service
,08-17 10:27:20.988  2512  2512 E GCoreFlp: Bound FusedProviderService with LocationManager
,08-17 10:27:21.027  8612  8658 I Babel   : MmsConfig: mnc/mcc: 0/0
08-17 10:27:21.027  8612  8658 I Babel   : MmsConfig.loadMmsSettings
08-17 10:27:21.033  8612  8658 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-17 10:27:21.033  8612  8658 I Babel   : MmsConfig.loadFromDatabase
,08-17 10:27:21.053  8612  8658 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-17 10:27:21.054  8612  8658 I Babel   : MmsConfig.loadFromResources
08-17 10:27:21.055  8612  8658 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-17 10:27:21.056  8612  8658 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-17 10:27:21.061  8612  8656 W AudioCapabilities: Unsupported mime audio/evrc
,08-17 10:27:21.063  8612  8656 W AudioCapabilities: Unsupported mime audio/qcelp
,08-17 10:27:21.063  8612  8612 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-17 10:27:21.065  8612  8656 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-17 10:27:21.077  8612  8656 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,08-17 10:27:21.080  8612  8656 W AudioCapabilities: Unsupported mime audio/qcelp
08-17 10:27:21.081  8612  8656 W AudioCapabilities: Unsupported mime audio/evrc
08-17 10:27:21.092  1847  8660 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-17 10:27:21.092  1847  8660 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
,08-17 10:27:21.096  7107  7107 I AppUp4:CustModeStarterReceiver: onReceive
08-17 10:27:21.102  7107  7107 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@38e3d673
08-17 10:27:21.102  7107  7107 D AppUp4:CustFacade: isCustomizationCompleted : false
08-17 10:27:21.102  7107  7107 D AppUp4:CustFacade: isPhone : true
08-17 10:27:21.103  7107  7107 D AppUp4:CustModeStarterReceiver: begin check event
08-17 10:27:21.103  7107  7107 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
,08-17 10:27:21.106  1847  4701 I Icing   : updateResources: need to parse e{com.google.android.gms}
08-17 10:27:21.120  8612  8656 W VideoCapabilities: Unsupported mime video/x-ms-wmv
08-17 10:27:21.123  8612  8656 W VideoCapabilities: Unsupported mime video/divx
,08-17 10:27:21.134  8612  8656 W VideoCapabilities: Unsupported mime video/divx311
08-17 10:27:21.137  8612  8656 W VideoCapabilities: Unsupported mime video/divx4
,08-17 10:27:21.141  1037  2117 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=8662 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
08-17 10:27:21.150  1037  1054 I ActivityManager: Killing 8218:com.lge.bnr/1000 (adj 15): empty #17
08-17 10:27:21.151  8612  8656 W VideoCapabilities: Unsupported mime video/mp4v-esdp
08-17 10:27:21.171  8612  8656 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-17 10:27:21.179  8612  8656 W AudioCapabilities: Unsupported mime audio/eac3
08-17 10:27:21.179  8612  8656 W AudioCapabilities: Unsupported mime audio/ac3
08-17 10:27:21.180  8612  8656 W AudioCapabilities: Unsupported mime audio/g726
08-17 10:27:21.181  8612  8656 W AudioCapabilities: Unsupported mime audio/wma-voice
08-17 10:27:21.182  8612  8656 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-17 10:27:21.183  8612  8656 W AudioCapabilities: Unsupported mime audio/adpcm
08-17 10:27:21.185  8612  8656 W VideoCapabilities: Unsupported mime video/theora
08-17 10:27:21.187  8612  8656 W VideoCapabilities: Unsupported mime video/mjpg
,08-17 10:27:21.199  1037  1985 W libprocessgroup: failed to open /acct/uid_1000/pid_8218/cgroup.procs: No such file or directory
,08-17 10:27:21.217  8662  8662 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-17 10:27:21.217  8662  8662 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-17 10:27:21.217  8662  8662 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,08-17 10:27:21.219  8662  8662 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-17 10:27:21.219  8662  8662 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-17 10:27:21.281  8662  8662 I SystemConfig: BUILD Country: EU
08-17 10:27:21.281  8662  8662 I SystemConfig: BUILD Operator: OPEN
,08-17 10:27:21.325  1037  1999 I ActivityManager: Killing 8192:com.lge.sync/1000 (adj 15): empty #17
,08-17 10:27:21.438  1037  2074 W libprocessgroup: failed to open /acct/uid_1000/pid_8192/cgroup.procs: No such file or directory
,08-17 10:27:21.447  1037  1541 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=14.2, 0.0, 0.0  rx=13.5 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1751341081] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-17 10:27:21.448  1037  1541 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=14.2, 0.0, 0.0  rx=13.5 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1751341080] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-17 10:27:21.448  1037  1541 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-17 10:27:21.449  8662  8681 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-17 10:27:21.449  8662  8681 I SystemConfig: existFile = false
08-17 10:27:21.449  8662  8681 I SystemConfig: canReadFile = false
08-17 10:27:21.449  8662  8681 I SystemConfig: systemFeature RCS result false
08-17 10:27:21.449  8662  8681 D SystemConfig: refreshRcsSupport() :false
08-17 10:27:21.487  1037  1999 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=8686 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-17 10:27:21.545  8686  8686 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-17 10:27:21.545  8686  8686 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-17 10:27:21.545  8686  8686 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,08-17 10:27:21.546  8686  8686 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-17 10:27:21.646  8686  8686 I AppConfig: Total System Memory = 2995761152
,08-17 10:27:21.659  8686  8686 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
08-17 10:27:21.746  1037  2113 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8705 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-17 10:27:21.750  1037  2113 I ActivityManager: Killing 7700:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
08-17 10:27:21.756  6772  6842 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 891)
08-17 10:27:21.757  6772  6842 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-17 10:27:21.757  6772  6842 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 892)
08-17 10:27:21.762  6772  6842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 10:27:21.762  6772  6842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f758ff1 added. We now have 3 listener(s)
,08-17 10:27:21.782  6996  6996 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-17 10:27:21.782  6996  6996 W System.err: android.os.DeadObjectException
,08-17 10:27:21.782  6996  6996 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-17 10:27:21.782  6996  6996 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-17 10:27:21.782  6996  6996 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-17 10:27:21.782  6996  6996 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
,08-17 10:27:21.782  6996  6996 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-17 10:27:21.782  6996  6996 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-17 10:27:21.782  6996  6996 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-17 10:27:21.782  6996  6996 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-17 10:27:21.782  6996  6996 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-17 10:27:21.783  6996  6996 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-17 10:27:21.783  6996  6996 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 10:27:21.783  6996  6996 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 10:27:21.783  6996  6996 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-17 10:27:21.783  6996  6996 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-17 10:27:21.783  6996  6996 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-17 10:27:21.783  6996  6996 W System.err: android.os.DeadObjectException
08-17 10:27:21.783  6996  6996 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-17 10:27:21.783  6996  6996 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-17 10:27:21.783  6996  6996 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
,08-17 10:27:21.783  6996  6996 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-17 10:27:21.783  6996  6996 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-17 10:27:21.783  6996  6996 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-17 10:27:21.783  6996  6996 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-17 10:27:21.784  6996  6996 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-17 10:27:21.784  6996  6996 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-17 10:27:21.784  6996  6996 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
,08-17 10:27:21.784  6996  6996 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 10:27:21.784  6996  6996 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 10:27:21.784  6996  6996 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-17 10:27:21.784  6996  6996 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-17 10:27:21.784  6996  6996 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-17 10:27:21.784  6996  6996 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,08-17 10:27:21.977  1037  1053 W libprocessgroup: failed to open /acct/uid_1000/pid_7700/cgroup.procs: No such file or directory
08-17 10:27:21.977  1037  1740 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 10:27:21.980  1037  1053 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-17 10:27:21.984  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-17 10:27:21.984  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 10:27:21.985  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 10:27:21.985  6772  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 10:27:21.985  6772  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c4fe7d6 added. We now have 4 listener(s)
,08-17 10:27:21.985  6772  6842 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 10:27:21.985  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-17 10:27:21.988  6996  6996 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-17 10:27:21.989  6996  6996 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-17 10:27:22.051  1037  1985 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=8725 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-17 10:27:22.052  6772  6842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 10:27:22.061  6996  6996 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-17 10:27:22.061  6772  6842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 10:27:22.061  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:27:22.061  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 10:27:22.061  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 10:27:22.061  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 10:27:22.061  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 10:27:22.061  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 10:27:22.061  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 10:27:22.063  6772  6842 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 10:27:22.063  6772  6842 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 10:27:22.063  6772  6842 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 10:27:22.063  6772  6842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 10:27:22.063  6772  6842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 10:27:22.064  6772  6842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 10:27:22.064  6772  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:27:22.064  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 10:27:22.064  6772  6842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 10:27:22.064  6772  6842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f758ff1 removed from the list
08-17 10:27:22.064  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:27:22.064  6772  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c4fe7d6 removed from the list
08-17 10:27:22.064  6772  6842 D io.jxcore.node.ConnectivityMonitor: stop
08-17 10:27:22.064  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 10:27:22.068  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:27:22.068  6772  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:27:22.068  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:27:22.070  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 10:27:22.070  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 10:27:22.070  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 10:27:22.070  6772  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c4fe7d6 not in the list
,08-17 10:27:22.070  6772  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:27:22.070  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:27:22.071  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 10:27:22.071  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 10:27:22.071  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:27:22.071  6772  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c4fe7d6 not in the list
08-17 10:27:22.071  6772  6842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 10:27:22.071  6772  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:27:22.071  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:27:22.072  6772  6842 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f758ff1 not in the list
08-17 10:27:22.072  6772  6842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 10:27:22.072  6772  6842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1384e944 added. We now have 3 listener(s)
08-17 10:27:22.074  1037  1658 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 10:27:22.076  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-17 10:27:22.076  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 10:27:22.076  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 10:27:22.076  6772  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 10:27:22.077  6772  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d423a2d added. We now have 4 listener(s)
08-17 10:27:22.077  6772  6842 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 10:27:22.078  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-17 10:27:22.089  6772  6842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 10:27:22.093  6772  6842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 10:27:22.093  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:27:22.093  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 10:27:22.093  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 10:27:22.093  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 10:27:22.093  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 10:27:22.093  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 10:27:22.093  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 10:27:22.094  6772  6842 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 10:27:22.095  6772  6842 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 10:27:22.095  6772  6842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 10:27:22.095  6772  6842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 10:27:22.095  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 10:27:22.095  6772  6842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 10:27:22.095  6772  6842 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-17 10:27:22.098  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:27:22.100  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 10:27:22.111  6772  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-17 10:27:22.111  1037  1578 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 10:27:22.116  6772  6842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-17 10:27:22.116  6772  6842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-17 10:27:22.118  6772  6842 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-17 10:27:22.119  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 10:27:22.120  6772  6842 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-17 10:27:22.120  6772  6842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 10:27:22.120  6772  6842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 10:27:22.159  8725  8725 D UEI.SmartControl: Quickset Services start...
,08-17 10:27:22.161  8725  8725 I UEI.SmartControl: Manufacture = LGE
08-17 10:27:22.161  8725  8725 D UEI.SmartControl: Id = LGNevo
08-17 10:27:22.162  8725  8725 D UEI.SmartControl: File observer start...
,08-17 10:27:22.166  8725  8725 E UEI.SmartControl: IR Port is disabled: false
08-17 10:27:22.166  8725  8725 D UEI.SmartControl: Starting file observer...
08-17 10:27:22.167  8725  8725 D UEI.SmartControl: Extracting JNI libs...
08-17 10:27:22.167  8725  8725 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-17 10:27:22.226  8705  8705 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-17 10:27:22.252  8725  8725 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-17 10:27:22.252  8725  8725 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-17 10:27:22.252  8725  8725 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-17 10:27:22.280  8725  8725 I UEI.SmartControl: --- Selecting new region: 6
,08-17 10:27:22.282  8725  8725 I UEI.SmartControl: Model = LG-D855
08-17 10:27:22.283  8725  8725 D UEI.SmartControl: QS Service created
08-17 10:27:22.294  8725  8725 I UEI.SmartControl: Service initServices...
,08-17 10:27:22.297  8725  8725 D UEI.SmartControl: QS start get config
08-17 10:27:22.298  8705  8705 D LgDataFeature: LgDataFeature() Constructor: none
08-17 10:27:22.298  8705  8705 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-17 10:27:22.334  8725  8725 D UEI.SmartControl: Loading JNI Libs...
,08-17 10:27:22.362  8705  8705 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-17 10:27:22.382  8705  8705 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-17 10:27:22.383  8705  8705 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-17 10:27:22.397  8705  8705 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-17 10:27:22.398  8705  8705 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-17 10:27:22.412  1037  1985 I ActivityManager: Killing 6934:com.android.settings/1000 (adj 15): empty #17
08-17 10:27:22.494  1037  2113 W libprocessgroup: failed to open /acct/uid_1000/pid_6934/cgroup.procs: No such file or directory
,08-17 10:27:22.505  3484  5848 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-17 10:27:22.506  4606  8774 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
08-17 10:27:22.509  3484  5848 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@3e3873d8 on behalf of 8705
,08-17 10:27:22.546  8725  8725 I UEI.SmartControl: Supports setup maps: true
,08-17 10:27:22.548  8725  8725 D UEI.SmartControl: QS start statue = true Error code = 0
08-17 10:27:22.549  8725  8725 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-17 10:27:22.549  8725  8725 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-17 10:27:22.549  8725  8725 I UEI.SmartControl: ### init IR Blaster...
08-17 10:27:22.553  8725  8725 D serial_port: Configuring serial port
08-17 10:27:22.556  8725  8725 E UEI.SmartControl: UEIBLaster setting for 616
08-17 10:27:22.556  8725  8725 I UEI.SmartControl: Setting serial record hearder size = 2
08-17 10:27:22.556  8725  8725 I UEI.SmartControl: configuring settings for MAXQ616
08-17 10:27:22.556  8725  8725 I UEI.SmartControl: Get version...
08-17 10:27:22.572  1037  2074 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=8777 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-17 10:27:22.575  8725  8776 D UEI.SmartControl: serial port data available: 21
08-17 10:27:22.605  8725  8725 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-17 10:27:22.605  8725  8725 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-17 10:27:22.605  8725  8725 I UEI.SmartControl: QS saving settings...
,08-17 10:27:22.607  8725  8725 D UEI.SmartControl: IR Blaster version: 25672567
08-17 10:27:22.615  8705  8705 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
08-17 10:27:22.624  8725  8776 D UEI.SmartControl: serial port data available: 4
,08-17 10:27:22.629  8705  8705 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
08-17 10:27:22.634  8777  8777 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
08-17 10:27:22.653  8777  8777 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
,08-17 10:27:22.653  8777  8777 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-17 10:27:22.653  8777  8777 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
,08-17 10:27:22.653  8777  8777 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-17 10:27:22.653  8725  8799 I UEI.SmartControl: Device manager: loading config....
08-17 10:27:22.654  8777  8777 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-17 10:27:22.654  8777  8777 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
08-17 10:27:22.654  8725  8799 D UEI.SmartControl: ----------- loading internal config...
08-17 10:27:22.655  8725  8725 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-17 10:27:22.659  8725  8725 E UEI.SmartControl: Services init done
08-17 10:27:22.660  8725  8725 D UEI.SmartControl: QS Service init finished
08-17 10:27:22.661  8725  8725 D UEI.SmartControl: QS Service version name: 2.1.91
08-17 10:27:22.661  8725  8725 D UEI.SmartControl: QS Service version code: 201091
08-17 10:27:22.662  8725  8725 D UEI.SmartControl: Service requested: Control
08-17 10:27:22.663  8725  8799 E UEI.SmartControl: Loading SETTINGS...
08-17 10:27:22.669  1037  2044 I ActivityManager: Killing 6996:com.lge.qremote/u0a112 (adj 15): empty #17
,08-17 10:27:22.671  8725  8725 D UEI.SmartControl: Request IControl service: devices are loaded...
08-17 10:27:22.671  8725  8799 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-17 10:27:22.693  8725  8798 I UEI.SmartControl: Notify AllClients services are ready: 0
08-17 10:27:22.693  8725  8798 D UEI.SmartControl: -----service ready thread exits
,08-17 10:27:22.763  1037  2028 W ActivityManager: Failure sending service ComponentInfo{com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service} to connection android.os.BinderProxy@1774802d (in com.lge.qremote)
08-17 10:27:22.763  1037  2028 W ActivityManager: android.os.DeadObjectException
08-17 10:27:22.763  1037  2028 W ActivityManager: 	at android.os.BinderProxy.transactNative(Native Method)
08-17 10:27:22.763  1037  2028 W ActivityManager: 	at android.os.BinderProxy.transact(Binder.java:496)
08-17 10:27:22.763  1037  2028 W ActivityManager: 	at android.app.IServiceConnection$Stub$Proxy.connected(IServiceConnection.java:92)
08-17 10:27:22.763  1037  2028 W ActivityManager: 	at com.android.server.am.ActiveServices.publishServiceLocked(ActiveServices.java:870)
08-17 10:27:22.763  1037  2028 W ActivityManager: 	at com.android.server.am.ActivityManagerService.publishService(ActivityManagerService.java:15431)
08-17 10:27:22.763  1037  2028 W ActivityManager: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:974)
08-17 10:27:22.763  1037  2028 W ActivityManager: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2560)
08-17 10:27:22.763  1037  2028 W ActivityManager: 	at com.android.server.am.ActivityManagerServiceEx.onTransact(ActivityManagerServiceEx.java:421)
08-17 10:27:22.763  1037  2028 W ActivityManager: 	at android.os.Binder.execTransact(Binder.java:446)
,08-17 10:27:22.768  1037  2028 I ActivityManager: Killing 8352:com.lge.email/u0a23 (adj 15): empty #17
08-17 10:27:22.827  8725  8725 D UEI.SmartControl: Internal service binding...
,08-17 10:27:22.828  1037  1816 W libprocessgroup: failed to open /acct/uid_10112/pid_6996/cgroup.procs: No such file or directory
08-17 10:27:22.835  1037  1054 W libprocessgroup: failed to open /acct/uid_10023/pid_8352/cgroup.procs: No such file or directory
08-17 10:27:23.060  1037  1999 V SIM_STK : Menu title from STK is T-Mobile
,08-17 10:27:23.074  4606  8774 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 568 ms] updated apps [took 568 ms] 
,08-17 10:27:24.465  1037  1541 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=7.1, 0.0, 0.0  rx=6.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1751338063] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-17 10:27:24.468  1037  1541 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=7.1, 0.0, 0.0  rx=6.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1751338060] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-17 10:27:24.468  1037  1541 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-17 10:27:25.121  6772  6842 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 10:27:25.122  6772  6842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 10:27:25.122  6772  6842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 10:27:25.132  6772  6842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 10:27:25.133  6772  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:27:25.133  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 10:27:25.133  6772  6842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 10:27:25.133  6772  6842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1384e944 removed from the list
08-17 10:27:25.133  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:27:25.133  6772  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d423a2d removed from the list
08-17 10:27:25.134  6772  6842 D io.jxcore.node.ConnectivityMonitor: stop
08-17 10:27:25.134  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:27:25.136  6772  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:27:25.137  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:27:25.141  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 10:27:25.141  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 10:27:25.145  6772  6842 D BluetoothLeScanner: could not find callback wrapper
08-17 10:27:25.145  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 10:27:25.145  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:27:25.145  6772  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d423a2d not in the list
08-17 10:27:25.145  6772  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:27:25.145  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:27:25.146  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 10:27:25.147  6772  6842 D BluetoothLeScanner: could not find callback wrapper
08-17 10:27:25.147  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 10:27:25.147  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 10:27:25.147  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:27:25.147  6772  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d423a2d not in the list
08-17 10:27:25.147  6772  6842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 10:27:25.147  6772  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:27:25.147  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:27:25.147  6772  6842 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1384e944 not in the list
08-17 10:27:25.148  6772  6842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 10:27:25.148  6772  6842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35b54c29 added. We now have 3 listener(s)
08-17 10:27:25.149  1037  1983 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 10:27:25.151  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-17 10:27:25.152  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 10:27:25.152  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 10:27:25.152  6772  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 10:27:25.152  6772  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c1c1bae added. We now have 4 listener(s)
08-17 10:27:25.152  6772  6842 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 10:27:25.154  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 10:27:25.161  6772  6842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 10:27:25.165  6772  6842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 10:27:25.165  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:27:25.165  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 10:27:25.165  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 10:27:25.165  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 10:27:25.165  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 10:27:25.165  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 10:27:25.165  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 10:27:25.168  6772  6842 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 10:27:25.168  6772  6842 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 10:27:25.172  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:27:25.174  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:27:25.174  6772  6842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-17 10:27:25.175  6772  6842 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
08-17 10:27:25.175  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
08-17 10:27:25.179  6772  6842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-17 10:27:25.179  6772  6842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
08-17 10:27:25.179  6772  6842 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-17 10:27:25.179  6772  6842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 10:27:25.182  6772  6842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-17 10:27:25.186  6772  6842 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-17 10:27:25.186  6772  6842 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-17 10:27:25.186  6772  6772 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-17 10:27:25.188  6772  6842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-17 10:27:25.188  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
08-17 10:27:25.188  6772  6842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 10:27:25.188  6772  6842 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-17 10:27:25.193  6772  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-17 10:27:25.194  1037  1658 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 10:27:25.200  6772  6842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-17 10:27:25.202  6772  6842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-17 10:27:25.204  6772  6842 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-17 10:27:25.205  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-17 10:27:25.207  1037  1054 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 10:27:25.209  6772  6842 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-17 10:27:25.211  6772  8811 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 10:27:25.214  7983  8106 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=82
,08-17 10:27:25.215  6772  8811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,08-17 10:27:27.501  1037  1541 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=3.5, 0.0, 0.0  rx=3.4 bcn=0 [on:0 tx:0 rx:0 period:3008] from screen [on:0 period:-1751335027] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-17 10:27:27.512  1037  1541 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=3.5, 0.0, 0.0  rx=3.4 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1751335016] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-17 10:27:27.512  1037  1541 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-17 10:27:27.655  8725  8800 D UEI.SmartControl: Internal timer expired: 1
08-17 10:27:27.655  8725  8800 D UEI.SmartControl: unbind internal service
,08-17 10:27:27.662  8725  8725 D UEI.SmartControl: Service.onUnbind: IControl
08-17 10:27:27.663  8725  8725 D UEI.SmartControl: Service.onDestroy
08-17 10:27:27.663  8725  8725 D UEI.SmartControl: Lock is in USE false
08-17 10:27:27.663  8725  8725 D UEI.SmartControl: unbind internal service
08-17 10:27:27.663  8725  8725 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@159b66cf
08-17 10:27:27.663  8725  8725 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
08-17 10:27:27.664  8725  8725 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
08-17 10:27:27.664  8725  8725 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
08-17 10:27:27.664  8725  8725 W System.err: 	at com.uei.control.Service.c(Unknown Source)
08-17 10:27:27.664  8725  8725 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
08-17 10:27:27.664  8725  8725 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
08-17 10:27:27.664  8725  8725 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
08-17 10:27:27.664  8725  8725 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
08-17 10:27:27.664  8725  8725 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 10:27:27.664  8725  8725 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-17 10:27:27.664  8725  8725 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-17 10:27:27.664  8725  8725 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 10:27:27.664  8725  8725 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 10:27:27.664  8725  8725 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-17 10:27:27.664  8725  8725 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-17 10:27:27.664  8725  8725 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@159b66cf
08-17 10:27:27.667  8725  8725 D serial_port: close(fd = 25)
08-17 10:27:27.672  8725  8725 I UEI.SmartControl: Serial port is closed.
08-17 10:27:27.672  8725  8725 I UEI.SmartControl: Serial port is closed.
08-17 10:27:27.672  8725  8725 D UEI.SmartControl: Blaster closed
08-17 10:27:27.672  8725  8725 D UEI.SmartControl: Shut down QS...
08-17 10:27:27.672  8725  8725 D UEI.SmartControl: Stopping QS lib
08-17 10:27:27.673  8725  8725 D UEI.SmartControl: QS lib stop result = true
08-17 10:27:27.673  8725  8725 D UEI.SmartControl: Stopped QS lib
,08-17 10:27:27.676  8725  8725 D UEI.SmartControl: Stopped file observer...
08-17 10:27:27.676  8725  8725 D UEI.SmartControl: QS shutdown complete
08-17 10:27:28.212  6772  6842 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 10:27:28.212  6772  6842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 10:27:28.213  6772  6842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-17 10:27:28.213  6772  6842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-17 10:27:28.213  6772  6842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-17 10:27:28.213  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,08-17 10:27:28.223  6772  8811 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-17 10:27:28.223  6772  8811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-17 10:27:28.223  6772  8811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-17 10:27:28.224  6772  6772 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-17 10:27:28.225  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 10:27:28.225  6772  6842 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-17 10:27:28.225  6772  6772 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-17 10:27:28.225  6772  6842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-17 10:27:28.225  6772  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:27:28.226  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 10:27:28.230  6772  6772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 10:27:28.230  6772  6772 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-17 10:27:28.231  6772  6842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 10:27:28.232  6772  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:27:28.232  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 10:27:28.232  6772  6842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 10:27:28.232  6772  6842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35b54c29 removed from the list
08-17 10:27:28.232  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:27:28.232  6772  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c1c1bae removed from the list
08-17 10:27:28.232  6772  6842 D io.jxcore.node.ConnectivityMonitor: stop
08-17 10:27:28.232  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 10:27:28.235  6772  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:27:28.235  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:27:28.237  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 10:27:28.237  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 10:27:28.237  6772  6842 D BluetoothLeScanner: could not find callback wrapper
08-17 10:27:28.237  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 10:27:28.237  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:27:28.237  6772  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c1c1bae not in the list
08-17 10:27:28.237  6772  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:27:28.237  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:27:28.239  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 10:27:28.239  6772  6842 D BluetoothLeScanner: could not find callback wrapper
08-17 10:27:28.239  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 10:27:28.239  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 10:27:28.239  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:27:28.239  6772  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c1c1bae not in the list
08-17 10:27:28.239  6772  6842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 10:27:28.240  6772  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:27:28.240  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:27:28.240  6772  6842 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35b54c29 not in the list
08-17 10:27:28.242  6772  6842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 10:27:28.242  6772  6842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@201244ba added. We now have 3 listener(s)
08-17 10:27:28.243  1037  1054 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-17 10:27:28.249  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-17 10:27:28.249  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 10:27:28.250  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 10:27:28.250  6772  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 10:27:28.250  6772  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a941f6b added. We now have 4 listener(s)
08-17 10:27:28.250  6772  6842 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 10:27:28.250  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-17 10:27:28.254  6772  6842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 10:27:28.259  6772  6842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 10:27:28.259  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:27:28.259  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 10:27:28.259  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 10:27:28.259  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 10:27:28.259  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 10:27:28.259  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 10:27:28.259  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 10:27:28.263  6772  6842 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 10:27:28.263  6772  6842 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 10:27:28.265  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:27:28.267  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:27:28.268  6772  6842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 10:27:28.268  6772  6842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 10:27:28.268  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 10:27:28.268  6772  6842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 10:27:28.268  6772  6842 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-17 10:27:28.272  6772  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-17 10:27:28.274  1037  1053 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 10:27:28.279  6772  6842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-17 10:27:28.280  6772  6842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-17 10:27:28.282  6772  6842 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-17 10:27:28.282  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 10:27:28.284  6772  6842 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-17 10:27:29.771  1037  1985 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 102]) by 10005
,08-17 10:27:29.774  1037  8256 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-4ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-17 10:27:29.774  1037  8256 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-4ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-17 10:27:29.774  1037  8256 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-17 10:27:29.775  1037  8256 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
08-17 10:27:29.775  1037  8256 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-17 10:27:29.815  1037  8256 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 17 Aug 2016 08:27:29 GMT], X-Android-Received-Millis=[1471422449815], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1471422449779]}
08-17 10:27:29.815  1037  8256 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-17 10:27:29.815  1037  8256 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
,08-17 10:27:29.820  1037  1548 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
,08-17 10:27:29.820  1037  1548 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-17 10:27:29.820  1037  1548 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-17 10:27:29.820  1037  1548 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-17 10:27:29.820  1037  1548 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-17 10:27:29.821  1037  1548 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-17 10:27:29.821  1037  1548 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-17 10:27:29.821  1037  1548 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 10:27:29.821  1037  1548 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,08-17 10:27:29.822  1037  1548 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-17 10:27:29.822  1605  1817 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-17 10:27:30.529  1037  1541 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=1.8, 0.0, 0.0  rx=1.7 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1751331999] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-17 10:27:30.532  1037  1541 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=1.8, 0.0, 0.0  rx=1.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1751331996] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-17 10:27:30.533  1037  1541 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-17 10:27:31.292  6772  6842 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 10:27:31.293  6772  6842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 10:27:31.293  6772  6842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 10:27:31.301  6772  6842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 10:27:31.301  6772  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:27:31.301  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 10:27:31.301  6772  6842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 10:27:31.301  6772  6842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@201244ba removed from the list
08-17 10:27:31.301  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:27:31.301  6772  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a941f6b removed from the list
08-17 10:27:31.301  6772  6842 D io.jxcore.node.ConnectivityMonitor: stop
08-17 10:27:31.302  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:27:31.303  6772  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:27:31.303  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:27:31.304  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 10:27:31.304  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 10:27:31.305  6772  6842 D BluetoothLeScanner: could not find callback wrapper
08-17 10:27:31.305  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 10:27:31.305  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:27:31.305  6772  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a941f6b not in the list
08-17 10:27:31.305  6772  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:27:31.305  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:27:31.306  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 10:27:31.307  6772  6842 D BluetoothLeScanner: could not find callback wrapper
08-17 10:27:31.307  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 10:27:31.307  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 10:27:31.307  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:27:31.307  6772  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a941f6b not in the list
08-17 10:27:31.307  6772  6842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 10:27:31.307  6772  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:27:31.307  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:27:31.307  6772  6842 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@201244ba not in the list
08-17 10:27:31.308  6772  6842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 10:27:31.308  677,2  6842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c534747 added. We now have 3 listener(s)
08-17 10:27:31.309  1037  2074 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 10:27:31.315  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-17 10:27:31.315  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 10:27:31.315  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 10:27:31.315  6772  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 10:27:31.315  6772  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7172b74 added. We now have 4 listener(s)
08-17 10:27:31.315  6772  6842 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 10:27:31.320  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-17 10:27:31.324  6772  6842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 10:27:31.329  6772  6842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 10:27:31.329  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:27:31.329  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 10:27:31.329  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 10:27:31.329  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 10:27:31.329  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 10:27:31.329  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 10:27:31.329  6772  6842 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 10:27:31.333  6772  6842 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 10:27:31.333  6772  6842 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 10:27:31.335  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:27:31.337  6772  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:27:31.339  6772  6842 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 10:27:31.339  6772  6842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 10:27:31.339  6772  6842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 10:27:31.339  6772  6842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 10:27:31.340  6772  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:27:31.340  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 10:27:31.340  6772  6842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 10:27:31.340  6772  6842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c534747 removed from the list
08-17 10:27:31.340  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:27:31.340  6772  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7172b74 removed from the list
08-17 10:27:31.340  6772  6842 D io.jxcore.node.ConnectivityMonitor: stop
08-17 10:27:31.340  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:27:31.341  6772  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:27:31.341  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 10:27:31.345  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 10:27:31.345  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 10:27:31.345  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:27:31.345  6772  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7172b74 not in the list
08-17 10:27:31.345  6772  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:27:31.345  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:27:31.346  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 10:27:31.346  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 10:27:31.346  6772  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:27:31.346  6772  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7172b74 not in the list
08-17 10:27:31.346  6772  6842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 10:27:31.346  6772  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:27:31.346  6772  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:27:31.346  6772  6842 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c534747 not in the list
08-17 10:27:31.348  6772  6842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-17 10:27:31.348  6772  6842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-17 10:27:31.348  6772  6842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-17 10:27:31.349  6772  6842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 10:27:31.349  6772  6842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-17 10:27:31.349  6772  6842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-17 10:27:33.370  6772  8812 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 901, name: My test thread name)
,08-17 10:27:33.557  1037  1541 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=3.4, 0.0, 0.0  rx=1.8 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1751328971] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-17 10:27:33.569  1037  1541 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=3.4, 0.0, 0.0  rx=1.8 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1751328959] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-17 10:27:33.570  1037  1541 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-17 10:27:35.367  6772  6842 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 901
08-17 10:27:35.367  6772  6842 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 901, name: My test thread name)
,08-17 10:27:35.382  6772  8813 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 902, name: My test thread name)
08-17 10:27:35.383  6772  8813 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 902, thread name: My test thread name)
08-17 10:27:35.383  6772  8813 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 902, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
08-17 10:27:35.385  6772  6842 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-17 10:27:35.390  6772  8814 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 906, name: My test thread name)
08-17 10:27:35.391  6772  8814 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 906, thread name: My test thread name): Test exception.
08-17 10:27:35.391  6772  8814 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 906, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
08-17 10:27:35.395  6772  6842 I jxcore-log: Total number of executed tests:  82
08-17 10:27:35.395  6772  6842 I jxcore-log: 
08-17 10:27:35.395  6772  6842 I jxcore-log: Number of passed tests:  82
08-17 10:27:35.395  6772  6842 I jxcore-log: 
08-17 10:27:35.395  6772  6842 I jxcore-log: Number of failed tests:  0
08-17 10:27:35.395  6772  6842 I jxcore-log: 
08-17 10:27:35.395  6772  6842 I jxcore-log: Number of ignored tests:  0
08-17 10:27:35.395  6772  6842 I jxcore-log: 
08-17 10:27:35.396  6772  6842 I jxcore-log: Total duration:  101734
08-17 10:27:35.396  6772  6842 I jxcore-log: 
08-17 10:27:35.401  6772  6842 I jxcore-log: Unit Test app is loaded
08-17 10:27:35.401  6772  6842 I jxcore-log: 
,08-17 10:27:35.421  6772  8812 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 901, name: My test thread name), during the lifetime of the thread the total number of bytes read was 154 and the total number of bytes written 154
,08-17 10:27:35.427  6772  6842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 10:27:35.427  6772  6842 I jxcore-log: 
08-17 10:27:35.439  6772  6842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 10:27:35.439  6772  6842 I jxcore-log: 
08-17 10:27:35.441  6772  6842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 10:27:35.441  6772  6842 I jxcore-log: 
08-17 10:27:35.442  6772  6842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 10:27:35.442  6772  6842 I jxcore-log: 
08-17 10:27:35.443  6772  6842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 10:27:35.443  6772  6842 I jxcore-log: 
08-17 10:27:35.444  6772  6842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 10:27:35.444  6772  6842 I jxcore-log: 
08-17 10:27:35.447  6772  6842 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-17 10:27:35.447  6772  6842 I jxcore-log: 
,08-17 10:27:35.452  6772  6772 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
08-17 10:27:35.454  6772  6842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-17 10:27:35.454  6772  6842 I jxcore-log: 
08-17 10:27:35.455  6772  6842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 10:27:35.455  6772  6842 I jxcore-log: 
08-17 10:27:35.456  6772  6842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-17 10:27:35.456  6772  6842 I jxcore-log: 
08-17 10:27:35.457  6772  6842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-17 10:27:35.457  6772  6842 I jxcore-log: 
08-17 10:27:35.458  6772  6842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 10:27:35.458  6772  6842 I jxcore-log: 
08-17 10:27:35.460  6772  6842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 10:27:35.460  6772  6842 I jxcore-log: 
08-17 10:27:35.461  6772  6842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 10:27:35.461  6772  6842 I jxcore-log: 
08-17 10:27:35.462  6772  6842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-17 10:27:35.462  6772  6842 I jxcore-log: 
08-17 10:27:35.462  6772  6842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-17 10:27:35.462  6772  6842 I jxcore-log: 
08-17 10:27:35.463  6772  6842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-17 10:27:35.463  6772  6842 I jxcore-log: 
08-17 10:27:35.464  6772  6842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 10:27:35.464  6772  6842 I jxcore-log: 
08-17 10:27:35.465  6772  6842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 10:27:35.465  6772  6842 I jxcore-log: 
08-17 10:27:35.466  6772  6842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 10:27:35.466  6772  6842 I jxcore-log: 
08-17 10:27:35.466  6772  6842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 10:27:35.466  6772  6842 I jxcore-log: 
08-17 10:27:35.467  6772  6842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 10:27:35.467  6772  6842 I jxcore-log: 
08-17 10:27:35.468  6772  6842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 10:27:35.468  6772  6842 I jxcore-log: 
08-17 10:27:35.471  6772  6842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
0,8-17 10:27:35.471  6772  6842 I jxcore-log: 
08-17 10:27:35.472  6772  6842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-17 10:27:35.472  6772  6842 I jxcore-log: 
08-17 10:27:35.473  6772  6842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-17 10:27:35.473  6772  6842 I jxcore-log: 
08-17 10:27:35.474  6772  6842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 10:27:35.474  6772  6842 I jxcore-log: 
08-17 10:27:35.475  6772  6842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 10:27:35.475  6772  6842 I jxcore-log: 
08-17 10:27:35.475  6772  6842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 10:27:35.475  6772  6842 I jxcore-log: 
08-17 10:27:35.476  6772  6842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-17 10:27:35.476  6772  6842 I jxcore-log: 
08-17 10:27:35.477  6772  6842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-17 10:27:35.477  6772  6842 I jxcore-log: 
08-17 10:27:35.478  6772  6842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-17 10:27:35.478  6772  6842 I jxcore-log: 
,08-17 10:27:35.483  6772  6842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-17 10:27:35.483  6772  6842 I jxcore-log: 
08-17 10:27:35.484  6772  6842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-17 10:27:35.484  6772  6842 I jxcore-log: 
08-17 10:27:35.485  6772  6842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 10:27:35.485  6772  6842 I jxcore-log: 
08-17 10:27:35.486  6772  6842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 10:27:35.486  6772  6842 I jxcore-log: 
08-17 10:27:35.487  6772  6842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 10:27:35.487  6772  6842 I jxcore-log: 
08-17 10:27:35.488  6772  6842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 10:27:35.488  6772  6842 I jxcore-log: 
08-17 10:27:35.489  6772  6842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 10:27:35.489  6772  6842 I jxcore-log: 
08-17 10:27:35.490  6772  6842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 10:27:35.490  6772  6842 I jxcore-log: 
08-17 10:27:35.490  6772  6842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 10:27:35.490  6772  6842 I jxcore-log: 
08-17 10:27:35.491  6772  6842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 10:27:35.491  6772  6842 I jxcore-log: 
08-17 10:27:35.495  6772  6842 I jxcore-log: My device name is: LGE-LG-D855
08-17 10:27:35.495  6772  6842 I jxcore-log: 
08-17 10:27:35.495  6772  6842 I jxcore-log: WARN testUtils: myNameCallback not set!
08-17 10:27:35.495  6772  6842 I jxcore-log: 
,08-17 10:27:36.406  1037  1384 D PowerManagerServiceEx: acquireWakeLockInternal: lock=657475144, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,08-17 10:27:36.415  1037  1384 V AlarmManager: ELAPSED_WAKEUP set : Alarm{feaffbe type 2 when 433575 com.google.android.gms} when 433575
08-17 10:27:36.434   320  8816 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-17 10:27:36.437   320  8816 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
08-17 10:27:36.437   320  8816 D libc-netbsd: res_queryN name = mtalk.google.com succeed
08-17 10:27:36.451  2637  2637 D [Concierge]Service: onStartCommand(). Type : 9
,08-17 10:27:36.481  1037  1037 D PowerManagerServiceEx: releaseWakeLockInternal: lock=657475144 [*alarm*], flags=0x0
,08-17 10:27:36.586  1037  1541 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=1.7, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1751325942] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-17 10:27:36.592  1037  1541 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=1.7, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:5] from screen [on:0 period:-1751325937] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-17 10:27:36.592  1037  1541 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-17 10:27:36.762  2249  8828 D GCM     : Connected
,08-17 10:27:36.783  2249  8828 D GCM     : Message class com.google.e.a.a.q
,08-17 10:27:39.600  1037  1541 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=3.3, 0.0, 0.0  rx=2.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1751322928] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-17 10:27:39.601  1037  1541 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=3.3, 0.0, 0.0  rx=2.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1751322927] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-17 10:27:39.601  1037  1541 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-17 10:27:39.803  6772  6842 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js
08-17 10:27:39.803  6772  6842 I jxcore-log: 
,08-17 10:27:39.827  6772  6842 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
08-17 10:27:39.829  6772  6842 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
08-17 10:27:39.829  6772  6842 I jxcore-log: 
,08-17 10:27:42.622  1037  1541 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=3.2, 0.0, 0.0  rx=3.5 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1751319906] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-17 10:27:42.625  1037  1541 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=3.2, 0.0, 0.0  rx=3.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1751319903] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-17 10:27:42.625  1037  1541 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-17 10:27:45.649  1037  1541 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=5.1, 0.0, 0.0  rx=4.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1751316880] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-17 10:27:45.652  1037  1541 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=5.1, 0.0, 0.0  rx=4.7 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1751316876] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-17 10:27:45.652  1037  1541 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-17 10:27:46.335  1037  1541 E WifiStateMachine:  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 3 0
,08-17 10:27:46.337  1037  1541 E WifiStateMachine:  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 3 0
08-17 10:27:46.338  1037  1541 E WifiStateMachine:  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 3 0
,08-17 10:27:46.348  1037  1541 E WifiStateMachine:  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 3 0
,08-17 10:27:46.349  1037  1541 E WifiStateMachine:  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 3 0
08-17 10:27:46.352  1037  1541 E WifiStateMachine:  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 3 0
08-17 10:27:48.677  1037  1541 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=2.5, 0.0, 0.0  rx=2.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1751313851] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-17 10:27:48.690  1037  1541 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=2.5, 0.0, 0.0  rx=2.4 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1751313838] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-17 10:27:48.690  1037  1541 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-17 10:27:48.796  6772  6842 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-17 10:27:48.796  6772  6842 I jxcore-log: 
,08-17 10:27:49.148  8844  8844 D AndroidRuntime: 
08-17 10:27:49.148  8844  8844 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-17 10:27:49.154  8844  8844 D AndroidRuntime: CheckJNI is OFF
08-17 10:27:49.367  8844  8844 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-17 10:27:49.382  1037  1099 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-17 10:27:49.383  1037  1099 I ActivityManager: Killing 6772:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,08-17 10:27:49.436  1037  1983 I WindowState: WIN DEATH: Window{258e799d u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-17 10:27:49.439  1037  1547 D WifiService: Client connection lost with reason: 4
08-17 10:27:49.453  1037  1983 D InputDispatcher: Window went away: Window{258e799d u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-17 10:27:49.601  1037  1099 I ActivityManager:   Force finishing activity ActivityRecord{3d3d63fe u0 com.test.thalitest/.MainActivity t6}
,08-17 10:27:49.627   340   353 E GBMv2   : DFP En is all cleared set to be enabled
,08-17 10:27:49.630  1037  1985 W ActivityManager: Spurious death for ProcessRecord{2beef81f 6772:com.test.thalitest/u0a118}, curProc for 6772: null
08-17 10:27:49.631  1037  1126 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
,08-17 10:27:49.637  1037  1126 I ActivityManager:   Force finishing activity ActivityRecord{3d3d63fe u0 com.test.thalitest/.MainActivity t6 f}
08-17 10:27:49.637  1037  1126 W ActivityManager: Duplicate finish request for ActivityRecord{3d3d63fe u0 com.test.thalitest/.MainActivity t6 f}
,08-17 10:27:49.689  2096  2096 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-17 10:27:49.690  1970  1994 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
,08-17 10:27:49.691  2096  2096 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-17 10:27:49.691  1970  1994 D SplitWindowPolicy: topRunningActivity=ActivityInfo{c56dac co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-17 10:27:49.692  2096  2096 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-17 10:27:49.692  2096  2182 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
08-17 10:27:49.695  1970  1993 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-17 10:27:49.696  1970  1993 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3a824a75 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-17 10:27:49.702  1605  1605 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-17 10:27:49.712  4606  4606 I art     : Explicit concurrent mark sweep GC freed 15477(888KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 574us total 67.482ms
,08-17 10:27:49.716  1037  1444 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-17 10:27:49.724  3862  3862 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
,08-17 10:27:49.725  2045  2045 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-17 10:27:49.725  2512  2618 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-17 10:27:49.736  7983  7983 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-17 10:27:49.736  7983  7983 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-17 10:27:49.787  4500  4500 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,08-17 10:27:49.787  4500  4500 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-17 10:27:49.787  4500  4500 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-17 10:27:49.787  4500  4500 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-17 10:27:49.787  4500  4500 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-17 10:27:49.788  4500  4500 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-17 10:27:49.788  4500  4500 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-17 10:27:49.788  4500  4500 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-17 10:27:49.788  4500  4500 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 10:27:49.788  4500  4500 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 10:27:49.788  4500  4500 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-17 10:27:49.788  4500  4500 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-17 10:27:49.790  2096  2096 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-17 10:27:49.791  1933  1933 D ActionManagerService: notifyUserLog: 1000003
08-17 10:27:49.793  3862  4494 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-17 10:27:49.793  2096  2096 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-17 10:27:49.794  2096  2096 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-17 10:27:49.795  2096  2096 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-17 10:27:49.799  1605  1605 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
,08-17 10:27:49.801  2096  2096 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-17 10:27:49.802  1933  1933 D ActionManagerService: notifyUserLog: 1000004
08-17 10:27:49.802  3862  4494 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-17 10:27:49.804  3862  4489 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-17 10:27:49.807  2096  2096 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-17 10:27:49.807  2096  2096 I GBoardWebViewUtils: , create_time: 1430832262123
08-17 10:27:49.807  2096  2096 I GBoardWebViewUtils: , expire_time: 0
08-17 10:27:49.807  2096  2096 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-17 10:27:49.807  2096  2096 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-17 10:27:49.807  2096  2096 I GBoardWebViewUtils: , display: false
08-17 10:27:49.807  2096  2096 I GBoardWebViewUtils: , animation: false }
08-17 10:27:49.807  2096  2096 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-17 10:27:49.807  2096  2096 I GBoardWebViewUtils: , create_time: 1430832262287
08-17 10:27:49.807  2096  2096 I GBoardWebViewUtils: , expire_time: 0
08-17 10:27:49.807  2096  2096 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-17 10:27:49.807  2096  2096 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-17 10:27:49.807  2096  2096 I GBoardWebViewUtils: , display: false
08-17 10:27:49.807  2096  2096 I GBoardWebViewUtils: , animation: false }
08-17 10:27:49.807  2096  2096 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1471007225619
08-17 10:27:49.807  2096  2096 I GBoardWebViewUtils: , create_time: 1471007226523
08-17 10:27:49.807  2096  2096 I GBoardWebViewUtils: , expire_time: 0
08-17 10:27:49.807  2096  2096 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide.html?id=guide_1111111111116_1471007225619&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-17 10:27:49.807  2096  2096 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-17 10:27:49.807  2096  2096 I GBoardWebViewUtils: , display: false
08-17 10:27:49.807  2096  2096 I GBoardWebViewUtils: , animation: false }
08-17 10:27:49.814  1037  1054 V SIM_STK : Menu title from STK is T-Mobile
08-17 10:27:49.816  2096  8876 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
,08-17 10:27:49.818  1605  1605 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-17 10:27:49.818  1605  1605 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-17 10:27:49.819  8236  8236 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-17 10:27:49.833  2096  2096 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-17 10:27:49.834  2096  2096 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
,08-17 10:27:49.853  1847  1847 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
,08-17 10:27:49.864  2249  2249 I ConfigService: onCreate
08-17 10:27:49.865  2249  2249 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-17 10:27:49.868  1899  1899 D SplitUIManager: split_name #11 / not available #0
,08-17 10:27:49.869  1899  1899 D SplitUIService: removed split : 
08-17 10:27:49.871  1847  1847 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-17 10:27:49.873  2249  2249 I ConfigService: onBind returning update interface
08-17 10:27:49.873  2249  2249 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-17 10:27:49.873  2249  2249 I ConfigService: onBind returning config service
08-17 10:27:49.898  1037  1037 I art     : Explicit concurrent mark sweep GC freed 53897(3MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 43MB/65MB, paused 1.890ms total 224.800ms
08-17 10:27:49.898  1037  1126 I art     : WaitForGcToComplete blocked for 221.722ms for cause Explicit
,08-17 10:27:49.928  2249  2249 I ConfigService: onDestroy
08-17 10:27:49.928  1847  8880 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,08-17 10:27:49.947  1037  1037 D administrator: Handling package changes for user 0
,08-17 10:27:49.948  1899  1899 D SplitUIManager: split_name #11 / not available #0
08-17 10:27:49.948  1899  1899 I SplitUIService: split app #11
08-17 10:27:49.964  1037  2074 V SIM_STK : Menu title from STK is T-Mobile
,08-17 10:27:49.965  1037  2074 V SIM_STK : Menu title from STK is T-Mobile
08-17 10:27:50.027  1037  1054 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-17 10:27:50.028  5938  8886 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
08-17 10:27:50.030  2096  2096 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
08-17 10:27:50.033  2096  2096 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-17 10:27:50.034  2096  2096 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-17 10:27:50.035  2096  2096 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-17 10:27:50.037  2096  2096 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-17 10:27:50.038  2096  2096 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-17 10:27:50.039  7983  7983 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-17 10:27:50.039  7983  7983 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-17 10:27:50.039  7983  7983 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-17 10:27:50.039  7983  7983 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-17 10:27:50.039  7983  7983 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-17 10:27:50.039  7983  7983 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-17 10:27:50.039  7983  7983 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-17 10:27:50.039  7983  7983 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-17 10:27:50.039  7983  7983 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-17 10:27:50.039  7983  7983 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-17 10:27:50.039  7983  7983 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-17 10:27:50.050  1847  8885 W GmsApplication: Using Auth Proxy for data requests.
,08-17 10:27:50.053  1037  1121 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1ad8880e u0 com.lge.launcher2/.Launcher t5} time:447234
08-17 10:27:50.053  7107  7107 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
08-17 10:27:50.055  1847  8887 I PeopleContactsSync: CP2 sync disabled
08-17 10:27:50.059  2096  2096 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-17 10:27:50.060  2096  2096 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-17 10:27:50.060  2096  2096 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-17 10:27:50.064  2096  2268 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-17 10:27:50.064  2096  2268 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-17 10:27:50.065  1847  4701 I Icing   : doRemovePackageData com.test.thalitest
08-17 10:27:50.067  1847  8885 W GmsApplication: Using Auth Proxy for data requests.
08-17 10:27:50.068  1037  1999 V SIM_STK : Menu title from STK is T-Mobile
08-17 10:27:50.080  2096  2096 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
,08-17 10:27:50.082  2096  2096 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-17 10:27:50.082  2096  2096 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-17 10:27:50.096  2096  2096 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
,08-17 10:27:50.097  2226  8890 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-17 10:27:50.107  1037  1037 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
,08-17 10:27:50.107  1037  1037 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-17 10:27:50.107  1037  1037 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-17 10:27:50.114  1037  1999 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8892 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-17 10:27:50.118  2096  2096 D [Concierge]WidgetView: change position of spinner
08-17 10:27:50.119  2637  2637 D [Concierge]Service: onStartCommand(). Type : 8
08-17 10:27:50.119  2637  2637 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-17 10:27:50.120  2637  2637 D [Concierge]Service: Update widget ID : 11
08-17 10:27:50.122  1037  1580 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-17 10:27:50.123  2096  2096 I [Concierge]WidgetView: initWebView(). Time : 1471422470123
08-17 10:27:50.125  2637  2637 D [Concierge]Service: onStartCommand(). Type : 0
,08-17 10:27:50.128   334   418 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-17 10:27:50.129  3191  8908 I Thermal-Lib: Thermal-Lib-Client: Client request sent
,08-17 10:27:50.151  1037  1126 I art     : Explicit concurrent mark sweep GC freed 8216(424KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 2.084ms total 251.257ms
08-17 10:27:50.153  1037  1740 I art     : WaitForGcToComplete blocked for 360.607ms for cause Explicit
08-17 10:27:50.158  2096  2096 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 735655738
08-17 10:27:50.159  2096  2096 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-17 10:27:50.159  2096  2096 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-17 10:27:50.161  2096  2096 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@224687d6
08-17 10:27:50.162  2096  2096 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-17 10:27:50.162  2096  2096 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-17 10:27:50.162  2096  2096 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-17 10:27:50.180  2096  2096 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-17 10:27:50.181  2096  2096 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-17 10:27:50.181  2096  2096 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-17 10:27:50.182  2096  2096 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1471422050876, New one : 1471422470123
08-17 10:27:50.182  2096  2096 D [Concierge]WidgetView: Unregister all receivers
08-17 10:27:50.182  2096  2096 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
,08-17 10:27:50.183  2096  2096 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-17 10:27:50.184  2096  2096 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-17 10:27:50.185  2096  2096 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-17 10:27:50.186  2096  2096 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-17 10:27:50.187  2096  2096 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-17 10:27:50.189  2096  2096 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-17 10:27:50.194  1847  8883 I art     : Explicit concurrent mark sweep GC freed 43515(2MB) AllocSpace objects, 29(464KB) LOS objects, 51% free, 30MB/62MB, paused 1.183ms total 35.753ms
,08-17 10:27:50.200  1847  1859 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/history_query.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
08-17 10:27:50.200  1847  1859 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/help_responses.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
08-17 10:27:50.202  1847  1859 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/metrics.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
08-17 10:27:50.202  2096  2096 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-17 10:27:50.202  2096  2096 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-17 10:27:50.232  2096  2096 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-17 10:27:50.239  2096  2096 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-17 10:27:50.239  2096  2096 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-17 10:27:50.240  2096  2096 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-17 10:27:50.241  8892  8892 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-17 10:27:50.241  8892  8892 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-17 10:27:50.242  8892  8892 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-17 10:27:50.242  8892  8892 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-17 10:27:50.265  2096  2096 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@5f8a23 time:447447
,08-17 10:27:50.268  8844  8844 D AndroidRuntime: Shutting down VM
08-17 10:27:50.268  8844  8844 W art     : No such thread id for suspend: 13
08-17 10:27:50.310  1037  1740 I art     : Explicit concurrent mark sweep GC freed 2889(180KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 1.509ms total 155.444ms
,08-17 10:27:50.312  1037  1126 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8912 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
08-17 10:27:50.313  1605  1657 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-17 10:27:50.313  1605  1657 D KeyguardModel: createShortcutInfo...
08-17 10:27:50.315  1605  1657 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-17 10:27:50.315  1605  1657 D KeyguardModel: createShortcutInfo...
08-17 10:27:50.317  1037  1097 W InputMethodInfo: Duplicated subtype definition found: , voice
08-17 10:27:50.318  1605  1657 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-17 10:27:50.318  1605  1657 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-17 10:27:50.318  1605  1657 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-17 10:27:50.319  1605  1657 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-17 10:27:50.320  1605  1657 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-17 10:27:50.320  1605  1657 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-17 10:27:50.321  1605  1657 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-17 10:27:50.321  1605  1657 D KeyguardModel: createShortcutInfo...
08-17 10:27:50.324  1605  1657 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-17 10:27:50.324  1605  1657 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-17 10:27:50.327  1605  1657 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-17 10:27:50.327  1605  1657 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-17 10:27:50.328  1605  1657 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-17 10:27:50.328  1605  1657 D KeyguardModel: createShortcutInfo...
08-17 10:27:50.332  1605  1657 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-17 10:27:50.333  1605  1657 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-17 10:27:50.333  1605  1657 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-17 10:27:50.333  1605  1657 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-17 10:27:50.333  1605  1657 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-17 10:27:50.333  1605  1657 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-17 10:27:50.334  1605  1657 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-17 10:27:50.334  1605  1657 D KeyguardModel: createShortcutInfo...
08-17 10:27:50.339  1605  1605 D KeyguardModel: handleShortcutListChanged...
08-17 10:27:50.339  1605  1605 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,08-17 10:27:50.344  1605  1657 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-17 10:27:50.344  1605  1657 D KeyguardModel: createShortcutInfo...
08-17 10:27:50.346  1605  1657 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-17 10:27:50.346  1605  1657 D KeyguardModel: createShortcutInfo...
08-17 10:27:50.347  1605  1657 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-17 10:27:50.347  1605  1657 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-17 10:27:50.348  1605  1657 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-17 10:27:50.348  1605  1657 D KeyguardModel: createShortcutInfo...
08-17 10:27:50.349  1605  1657 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-17 10:27:50.349  1605  1657 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-17 10:27:50.350  1605  1657 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-17 10:27:50.350  1605  1657 D KeyguardModel: createShortcutInfo...
08-17 10:27:50.351  1605  1657 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-17 10:27:50.351  1605  1657 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-17 10:27:50.352  1605  1657 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-17 10:27:50.352  1605  1657 D KeyguardModel: createShortcutInfo...
08-17 10:27:50.354  8892  8892 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-17 10:27:50.369  8892  8892 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
08-17 10:27:50.369  1605  1605 D KeyguardModel: handleShortcutListChanged...
08-17 10:27:50.369  1605  1605 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-17 10:27:50.373  1037  2113 I ActivityManager: Killing 8169:com.lge.formmanager/u0a26 (adj 15): empty #17
,08-17 10:27:50.402  8892  8892 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-17 10:27:50.459  1037  1097 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-17 10:27:50.463  1037  1097 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-17 10:27:50.466  2096  2096 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
08-17 10:27:50.489  1037  1985 W libprocessgroup: failed to open /acct/uid_10026/pid_8169/cgroup.procs: No such file or directory
,08-17 10:27:50.491  2096  2096 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-17 10:27:50.507  8892  8892 D LgDataFeature: LgDataFeature() Constructor: none
08-17 10:27:50.507  8892  8892 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-17 10:27:50.509  2096  2947 I GBoardtInterface: onReloaded()
08-17 10:27:50.512  2096  2096 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-17 10:27:50.513  3862  4489 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-17 10:27:50.515  3862  3877 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-17 10:27:50.520  1933  1933 D ActionManagerService: notifyUserLog: 1000001
08-17 10:27:50.521  3862  4494 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-17 10:27:50.521  3862  4494 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-17 10:27:50.524  1933  1933 D ActionManagerService: notifyUserLog: 1000001
08-17 10:27:50.525  3862  4494 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-17 10:27:50.525  3862  4494 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-17 10:27:50.525  3862  4494 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-17 10:27:50.525  3862  4494 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-17 10:27:50.527  3862  4489 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,08-17 10:27:50.530  2096  2096 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-17 10:27:50.530  2096  2096 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-17 10:27:50.532  2096  2096 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-17 10:27:50.532  2096  2096 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-17 10:27:50.534  2096  2096 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide2.html?id=guide_1111111111116_1471007225619&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-17 10:27:50.534  2096  2096 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide2.html?id=guide_1111111111116_1471007225619&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
,08-17 10:27:50.563  8892  8892 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)

```
