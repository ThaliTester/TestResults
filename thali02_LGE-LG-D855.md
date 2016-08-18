#### Test 8180285668baf36_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-18 14:10:00.063  1605  1605 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-18 14:10:00.063  1605  1605 I KeyguardUpdateMonitor: called onTimeUpdated()
08-18 14:10:00.064  1605  1605 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-18 14:10:00.064  1605  1605 I [SystemUI]Clock: called onTimeUpdated()
,08-18 14:10:00.078  1605  1605 I LgeClockWidgetControlView: called onTimeUpdated()
08-18 14:10:00.078  1605  1605 I [SystemUI]DateView: called onTimeUpdated()
08-18 14:10:00.080  1605  1605 I [SystemUI]DateView: called onTimeUpdated()
08-18 14:10:00.081  1605  1605 D KeyguardUpdateMonitor: handleTimeUpdate
08-18 14:10:00.389  6802  6802 D AndroidRuntime: 
08-18 14:10:00.389  6802  6802 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-18 14:10:00.394  6802  6802 D AndroidRuntime: CheckJNI is OFF
08-18 14:10:00.599  6802  6802 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-18 14:10:00.609  1034  1971 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-18 14:10:00.624  1944  1960 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-18 14:10:00.630  1034  1971 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-18 14:10:00.631  1034  1971 D ActivityManager: setTaskToReturnTo : TaskRecord{3177b4e4 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-18 14:10:00.632  1034  1971 D ActivityManager: setTaskToReturnTo : TaskRecord{3177b4e4 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-18 14:10:00.633  1034  1971 D WindowStateEx: AppWindowTokenEx init.. 
08-18 14:10:00.634   331   350 E GBMv2   : DFP En is all cleared set to be enabled
08-18 14:10:00.663  1034  1971 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6817 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-18 14:10:00.666  6802  6802 D AndroidRuntime: Shutting down VM
08-18 14:10:00.727  1944  1959 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-18 14:10:00.727  1944  1959 D SplitWindowPolicy: topRunningActivity=ActivityInfo{f1b5269 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-18 14:10:00.729  1944  2561 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-18 14:10:00.729  1944  2561 D SplitWindowPolicy: topRunningActivity=ActivityInfo{27f444ee co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-18 14:10:00.794  6817  6817 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-18 14:10:00.877  6817  6817 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-18 14:10:00.884  6817  6817 I LibraryLoader: Loading: webviewchromium
08-18 14:10:00.887  6817  6817 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 1627-1631)
08-18 14:10:00.888  6817  6817 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-18 14:10:00.903  6817  6817 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3ef530ff}
,08-18 14:10:00.904  6817  6817 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-18 14:10:00.904  6817  6817 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,08-18 14:10:00.913  6817  6817 I BrowserStartupController: Initializing chromium process, renderers=0
08-18 14:10:00.914  6817  6817 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-18 14:10:00.923  6817  6817 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-18 14:10:00.924  6817  6817 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-18 14:10:00.925  6817  6817 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
,08-18 14:10:00.927   314  2148 V AudioPolicyService: registerClient() client 0xb558ae40, uid 10118
08-18 14:10:00.935  6817  6817 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-18 14:10:00.935  6817  6817 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-18 14:10:00.935  6817  6817 I Adreno-EGL: Build Date: 12/12/14 금
08-18 14:10:00.935  6817  6817 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-18 14:10:00.935  6817  6817 I Adreno-EGL: Remote Branch: 
08-18 14:10:00.935  6817  6817 I Adreno-EGL: Local Patches: 
08-18 14:10:00.935  6817  6817 I Adreno-EGL: Reconstruct Branch: 
,08-18 14:10:00.940  1034  1101 D BluetoothManagerService: Message: 20
08-18 14:10:00.940  1034  1101 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2df78a4e:true
08-18 14:10:01.073  6817  6862 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-18 14:10:01.078  6817  6817 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-18 14:10:01.096  6817  6817 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-18 14:10:01.101  6817  6817 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-18 14:10:01.104  6817  6817 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-18 14:10:01.107  6817  6817 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-18 14:10:01.107  6817  6817 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-18 14:10:01.121  6817  6817 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-18 14:10:01.131  6817  6817 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-18 14:10:01.131  6817  6817 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-18 14:10:01.185  6817  6878 D OpenGLRenderer: Render dirty regions requested: true
08-18 14:10:01.185  6817  6878 I OpenGLRenderer: Initialized EGL, version 1.4
08-18 14:10:01.192  6817  6878 D OpenGLRenderer: Enabling debug mode 0
,08-18 14:10:01.202  6817  6817 D Atlas   : Validating map...
08-18 14:10:01.206  1034  1810 D SplitWindow: check instance of lgWin Window{20e67798 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-18 14:10:01.268  6817  6876 D LgDataFeature: LgDataFeature() Constructor: none
08-18 14:10:01.268  6817  6876 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-18 14:10:01.326  1034  1103 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +602ms (total +692ms)
08-18 14:10:01.328  1034  1103 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{156dad4d u0 com.test.thalitest/.MainActivity t6} time:182072
,08-18 14:10:01.334  6817  6817 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@30b2d7da time:182078
08-18 14:10:01.442  6817  6817 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-18 14:10:01.474  6817  6817 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-18 14:10:01.474  6817  6817 I chromium: 
,08-18 14:10:01.493  6817  6876 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-18 14:10:01.493  6817  6876 I chromium: 
,08-18 14:10:01.584  6817  6892 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435161600
,08-18 14:10:01.596  6817  6892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-18 14:10:01.596  6817  6892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-18 14:10:01.596  6817  6892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-18 14:10:01.596  6817  6892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-18 14:10:01.596  6817  6892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-18 14:10:01.596  6817  6892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14cef57e added. We now have 1 listener(s)
,08-18 14:10:01.601  1034  1935 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-18 14:10:01.603  6817  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
,08-18 14:10:01.605  6817  6892 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-18 14:10:01.607  6817  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-18 14:10:01.607  6817  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-18 14:10:01.613  6817  6892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-18 14:10:01.613  6817  6892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-18 14:10:01.613  6817  6892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-18 14:10:01.613  6817  6892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-18 14:10:01.613  6817  6892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-18 14:10:01.613  6817  6892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-18 14:10:01.613  6817  6892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-18 14:10:01.613  6817  6892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-18 14:10:01.613  6817  6892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-18 14:10:01.613  6817  6892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-18 14:10:01.613  6817  6892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-18 14:10:01.613  6817  6892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-18 14:10:01.613  6817  6892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-18 14:10:01.613  6817  6892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-18 14:10:01.613  6817  6892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@382641f5 added. We now have 1 listener(s)
08-18 14:10:01.613  6817  6892 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-18 14:10:01.619  1034  1546 D WifiService: New client listening to asynchronous messages
08-18 14:10:01.622  6817  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-18 14:10:01.622  6817  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-18 14:10:01.624  6817  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-18 14:10:01.624  6817  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-18 14:10:01.624  6817  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-18 14:10:01.628  6817  6892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-18 14:10:01.629  1034  1943 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-18 14:10:01.629  6817  6892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
,08-18 14:10:01.642  6817  6892 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-18 14:10:01.643  6817  6892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-18 14:10:01.643  6817  6892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 14:10:01.643  6817  6892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-18 14:10:01.643  6817  6892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 14:10:01.643  6817  6892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-18 14:10:01.643  6817  6892 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-18 14:10:01.643  6817  6892 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-18 14:10:01.643  6817  6892 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-18 14:10:01.643  6817  6892 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-18 14:10:01.644  6817  6892 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-18 14:10:01.648  6817  6892 I io.jxcore.node.LifeCycleMonitor: start: OK
08-18 14:10:01.649  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 14:10:01.651  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 14:10:01.677  6817  6817 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-18 14:10:02.000   331   352 E GBMv2   : DFP En is all cleared set to be enabled
,08-18 14:10:02.000   331   352 E GBMv2   : Set value is all cleared set the max
,08-18 14:10:02.000   331   352 I GBMv2   : DFP Enabled. Ignore VFP set
,08-18 14:10:02.591  6817  6895 W jxcore-log: Initializing JXcore engine
08-18 14:10:02.591  6817  6895 W jxcore-log: JXcore engine is ready
,08-18 14:10:02.664  6895  6895 W Thread-777: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[7476]" dev="sockfs" ino=7476 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-18 14:10:02.664  6895  6895 W Thread-777: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-18 14:10:02.664  6895  6895 W Thread-777: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[7649]" dev="sockfs" ino=7649 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-18 14:10:02.664  6895  6895 W Thread-777: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-18 14:10:02.664  6895  6895 W Thread-777: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[33172]" dev="sockfs" ino=33172 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-18 14:10:02.710  6817  6895 W jxcore-log: Starting JXcore engine
,08-18 14:10:02.868  6817  6895 W jxcore-log: Platform android
08-18 14:10:02.868  6817  6895 W jxcore-log: 
08-18 14:10:02.868  6817  6895 W jxcore-log: Process ARCH arm
08-18 14:10:02.868  6817  6895 W jxcore-log: 
,08-18 14:10:03.213  6817  6895 I jxcore-log: JXcore Cordova bridge is ready!
08-18 14:10:03.213  6817  6895 I jxcore-log: 
08-18 14:10:03.214  6817  6895 W jxcore-log: JXcore engine is started
,08-18 14:10:03.225  6817  6892 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-18 14:10:03.232  6817  6817 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-18 14:10:12.728  6817  6895 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-18 14:10:12.728  6817  6895 I jxcore-log: 
,08-18 14:10:12.731  6817  6895 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-18 14:10:12.731  6817  6895 I jxcore-log: 
08-18 14:10:12.737  6817  6895 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-18 14:10:12.737  6817  6895 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 14:10:12.737  6817  6895 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-18 14:10:12.737  6817  6895 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 14:10:12.737  6817  6895 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-18 14:10:12.737  6817  6895 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-18 14:10:12.737  6817  6895 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-18 14:10:12.737  6817  6895 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-18 14:10:12.740  6817  6895 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-18 14:10:12.741  6817  6895 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-18 14:10:12.741  6817  6895 I jxcore-log: 
,08-18 14:10:12.743  6817  6895 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-18 14:10:12.743  6817  6895 I jxcore-log: 
08-18 14:10:13.248  6817  6895 D ExecuteNativeTests: Running unit tests
,08-18 14:10:13.328  6817  6895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-18 14:10:13.328  6817  6895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@abc70ce added. We now have 2 listener(s)
08-18 14:10:13.329  1034  2054 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-18 14:10:13.330  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-18 14:10:13.330  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-18 14:10:13.330  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-18 14:10:13.330  6817  6895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-18 14:10:13.330  6817  6895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9eefbef added. We now have 2 listener(s)
08-18 14:10:13.330  6817  6895 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-18 14:10:13.333  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-18 14:10:13.336  6817  6895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-18 14:10:13.338  6817  6895 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-18 14:10:13.338  6817  6895 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 14:10:13.338  6817  6895 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-18 14:10:13.338  6817  6895 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 14:10:13.338  6817  6895 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-18 14:10:13.338  6817  6895 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-18 14:10:13.338  6817  6895 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-18 14:10:13.338  6817  6895 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-18 14:10:13.339  6817  6895 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-18 14:10:13.339  6817  6895 D io.jxcore.node.ConnectivityMonitor: start: OK
08-18 14:10:13.342  6817  6895 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-18 14:10:13.342  6817  6895 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-18 14:10:13.342  6817  6895 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-18 14:10:13.344  6817  6895 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-18 14:10:13.344  6817  6895 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-18 14:10:13.344  6817  6895 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-18 14:10:13.344  6817  6895 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-18 14:10:13.344  6817  6895 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-18 14:10:13.345  6817  6895 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-18 14:10:13.346  6817  6895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-18 14:10:13.346  6817  6895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-18 14:10:13.349  6817  6895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 14:10:13.349  6817  6895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:10:13.349  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-18 14:10:13.350  6817  6895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-18 14:10:13.350  6817  6895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@abc70ce removed from the list
08-18 14:10:13.350  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:10:13.350  6817  6895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9eefbef removed from the list
08-18 14:10:13.350  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 14:10:13.352  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 14:10:13.352  6817  6895 D io.jxcore.node.ConnectivityMonitor: stop
08-18 14:10:13.352  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:10:13.353  6817  6895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:10:13.353  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:10:13.353  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 14:10:13.353  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 14:10:13.353  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:10:13.353  6817  6895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9eefbef not in the list
08-18 14:10:13.355  6817  6895 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-18 14:10:13.356  6817  6895 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-18 14:10:13.356  6817  6895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-18 14:10:13.356  6817  6895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-18 14:10:13.356  6817  6895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 14:10:13.356  6817  6895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:10:13.356  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:10:13.356  6817  6895 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@abc70ce not in the list
08-18 14:10:13.356  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:10:13.356  6817  6895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9eefbef not in the list
08-18 14:10:13.356  6817  6895 D io.jxcore.node.ConnectivityMonitor: stop
08-18 14:10:13.356  6817  6895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.Blu,etoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:10:13.356  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:10:13.356  6817  6895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:10:13.356  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:10:13.357  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 14:10:13.357  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 14:10:13.357  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:10:13.357  6817  6895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9eefbef not in the list
,08-18 14:10:13.361  6817  6895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-18 14:10:13.361  6817  6895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-18 14:10:13.361  6817  6895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-18 14:10:13.361  6817  6895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-18 14:10:13.361  6817  6895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-18 14:10:13.362  6817  6895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-18 14:10:13.362  6817  6895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-18 14:10:13.362  6817  6895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-18 14:10:13.362  6817  6895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-18 14:10:13.362  6817  6895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-18 14:10:13.362  6817  6895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-18 14:10:13.362  6817  6895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-18 14:10:13.362  6817  6895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-18 14:10:13.362  6817  6895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-18 14:10:13.362  6817  6895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-18 14:10:13.362  6817  6895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-18 14:10:13.362  6817  6895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-18 14:10:13.362  6817  6895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-18 14:10:13.362  6817  6895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-18 14:10:13.362  6817  6895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-18 14:10:13.362  6817  6895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-18 14:10:13.362  6817  6895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-18 14:10:13.362  6817  6895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-18 14:10:13.362  6817  6895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-18 14:10:13.362  6817  6895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-18 14:10:13.362  6817  6895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-18 14:10:13.362  6817  6895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 3,5:2510:2510:2510:2510:2510]
08-18 14:10:13.362  6817  6895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-18 14:10:13.362  6817  6895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-18 14:10:13.362  6817  6895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-18 14:10:13.362  6817  6895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-18 14:10:13.362  6817  6895 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-18 14:10:13.362  6817  6895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-18 14:10:13.362  6817  6895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-18 14:10:13.363  6817  6895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 14:10:13.363  6817  6895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:10:13.363  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:10:13.365  6817  6895 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@abc70ce not in the list
,08-18 14:10:13.365  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:10:13.365  6817  6895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9eefbef not in the list
08-18 14:10:13.365  6817  6895 D io.jxcore.node.ConnectivityMonitor: stop
08-18 14:10:13.365  6817  6895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:10:13.365  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:10:13.365  6817  6895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:10:13.365  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:10:13.366  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 14:10:13.366  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 14:10:13.366  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:10:13.366  6817  6895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9eefbef not in the list
,08-18 14:10:13.366  6817  6895 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-18 14:10:13.367  6817  6895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-18 14:10:13.370  6817  6895 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-18 14:10:13.370  6817  6895 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 14:10:13.370  6817  6895 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-18 14:10:13.370  6817  6895 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 14:10:13.370  6817  6895 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-18 14:10:13.370  6817  6895 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-18 14:10:13.370  6817  6895 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-18 14:10:13.370  6817  6895 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-18 14:10:13.370  6817  6895 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-18 14:10:13.371  6817  6895 D io.jxcore.node.ConnectivityMonitor: start: OK
08-18 14:10:13.372  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-18 14:10:13.373  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 14:10:13.373  6817  6895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-18 14:10:13.373  6817  6895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-18 14:10:13.373  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-18 14:10:13.373  6817  6895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-18 14:10:13.373  6817  6895 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-18 14:10:13.376  6817  6895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-18 14:10:13.376  1034  1623 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-18 14:10:13.380  6817  6895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-18 14:10:13.383  6817  6895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-18 14:10:13.385  6817  6895 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
08-18 14:10:13.386  6817  6895 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-18 14:10:13.386  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-18 14:10:13.387  6817  6895 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-18 14:10:13.387  6817  6895 I io.jxcore.node.ConnectionHelper: start: OK
08-18 14:10:13.389  6817  6895 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-18 14:10:13.389  6817  6895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-18 14:10:13.389  6817  6895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-18 14:10:13.389  6817  6895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 14:10:13.389  6817  6895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:10:13.389  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-18 14:10:13.389  6817  6895 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@abc70ce not in the list
08-18 14:10:13.390  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:10:13.390  6817  6895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9eefbef not in the list
08-18 14:10:13.390  6817  6895 D io.jxcore.node.ConnectivityMonitor: stop
08-18 14:10:13.390  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:10:13.390  6817  6895 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-18 14:10:13.391  6817  6895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-18 14:10:13.393  6817  6895 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-18 14:10:13.393  6817  6895 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 14:10:13.393  6817  6895 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-18 14:10:13.393  6817  6895 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 14:10:13.393  6817  6895 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-18 14:10:13.393  6817  6895 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-18 14:10:13.393  6817  6895 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-18 14:10:13.393  6817  6895 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-18 14:10:13.394  6817  6895 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-18 14:10:13.394  6817  6895 D io.jxcore.node.ConnectivityMonitor: start: OK
08-18 14:10:13.395  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-18 14:10:13.396  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 14:10:13.396  6817  6895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-18 14:10:13.396  6817  6895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-18 14:10:13.396  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-18 14:10:13.396  6817  6895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-18 14:10:13.396  6817  6895 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-18 14:10:13.474  1034  2035 I art     : Explicit concurrent mark sweep GC freed 33906(1668KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 1.360ms total 71.702ms
,08-18 14:10:13.478  6817  6895 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-18 14:10:13.478  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-18 14:10:13.479  6817  6895 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-18 14:10:13.479  6817  6895 I io.jxcore.node.ConnectionHelper: start: OK
08-18 14:10:13.480  6817  6895 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-18 14:10:13.480  6817  6895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-18 14:10:13.481  6817  6895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-18 14:10:13.481  6817  6895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 14:10:13.481  6817  6895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:10:13.481  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-18 14:10:13.481  6817  6895 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@abc70ce not in the list
08-18 14:10:13.481  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:10:13.481  6817  6895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9eefbef not in the list
08-18 14:10:13.481  6817  6895 D io.jxcore.node.ConnectivityMonitor: stop
08-18 14:10:13.481  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:10:13.481  6817  6895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:10:13.481  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:10:13.482  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 14:10:13.482  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 14:10:13.483  6817  6895 D BluetoothLeScanner: could not find callback wrapper
08-18 14:10:13.483  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-18 14:10:13.483  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:10:13.483  6817  6895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9eefbef not in the list
08-18 14:10:13.484  6817  6895 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-18 14:10:13.485  6817  6895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-18 14:10:13.487  6817  6895 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-18 14:10:13.487  6817  6895 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 14:10:13.487  6817  6895 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-18 14:10:13.487  6817  6895 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 14:10:13.487  6817  6895 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-18 14:10:13.487  6817  6895 V io.jxcore.node.ConnectivityMonitor:     - BSSID name:, f4:f2:6d:22:99:3e
08-18 14:10:13.487  6817  6895 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-18 14:10:13.487  6817  6895 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-18 14:10:13.493  6817  6895 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-18 14:10:13.493  6817  6895 D io.jxcore.node.ConnectivityMonitor: start: OK
08-18 14:10:13.494  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 14:10:13.495  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 14:10:13.495  6817  6895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-18 14:10:13.495  6817  6895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-18 14:10:13.495  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-18 14:10:13.495  6817  6895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-18 14:10:13.495  6817  6895 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-18 14:10:13.498  6817  6895 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-18 14:10:13.499  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-18 14:10:13.500  6817  6895 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-18 14:10:13.500  6817  6895 I io.jxcore.node.ConnectionHelper: start: OK
08-18 14:10:13.500  6817  6895 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-18 14:10:13.500  6817  6895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-18 14:10:13.500  6817  6895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-18 14:10:13.501  6817  6895 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-18 14:10:13.501  6817  6895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-18 14:10:13.501  6817  6895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-18 14:10:13.501  6817  6895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 14:10:13.501  6817  6895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:10:13.501  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-18 14:10:13.501  6817  6895 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@abc70ce not in the list
08-18 14:10:13.501  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:10:13.501  6817  6895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9eefbef not in the list
08-18 14:10:13.501  6817  6895 D io.jxcore.node.ConnectivityMonitor: stop
08-18 14:10:13.501  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:10:13.501  6817  6895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:10:13.501  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:10:13.502  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 14:10:13.502  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 14:10:13.502  6817  6895 D BluetoothLeScanner: could not find callback wrapper
08-18 14:10:13.502  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-18 14:10:13.502  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:10:13.502  6817  6895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9eefbef not in the list
08-18 14:10:13.503  6817  6895 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-18 14:10:13.503  6817  6895 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-18 14:10:13.503  6817  6895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-18 14:10:13.503  6817  6895 V io.jxcore,.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-18 14:10:13.503  6817  6895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 14:10:13.503  6817  6895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:10:13.503  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:10:13.503  6817  6895 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@abc70ce not in the list
08-18 14:10:13.503  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:10:13.503  6817  6895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9eefbef not in the list
08-18 14:10:13.503  6817  6895 D io.jxcore.node.ConnectivityMonitor: stop
08-18 14:10:13.503  6817  6895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:10:13.503  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:10:13.503  6817  6895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:10:13.503  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:10:13.504  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 14:10:13.504  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 14:10:13.504  6817  6895 D BluetoothLeScanner: could not find callback wrapper
08-18 14:10:13.504  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-18 14:10:13.505  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:10:13.505  6817  6895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9eefbef not in the list
08-18 14:10:13.505  6817  6895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-18 14:10:13.505  6817  6895 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-18 14:10:13.505  6817  6895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-18 14:10:13.505  6817  6895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-18 14:10:13.506  6817  6895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 14:10:13.506  6817  6895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:10:13.506  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:10:13.506  6817  6895 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@abc70ce not in the list
08-18 14:10:13.506  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:10:13.506  6817  6895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9eefbef not in the list
08-18 14:10:13.506  6817 , 6895 D io.jxcore.node.ConnectivityMonitor: stop
08-18 14:10:13.506  6817  6895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:10:13.506  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:10:13.506  6817  6895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:10:13.506  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:10:13.507  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 14:10:13.507  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 14:10:13.507  6817  6895 D BluetoothLeScanner: could not find callback wrapper
08-18 14:10:13.507  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-18 14:10:13.507  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:10:13.507  6817  6895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9eefbef not in the list
08-18 14:10:13.508  6817  6895 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-18 14:10:13.508  6817  6895 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-18 14:10:13.508  6817  6895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-18 14:10:13.508  6817  6895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-18 14:10:13.508  6817  6895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 14:10:13.508  6817  6895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:10:13.508  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:10:13.508  6817  6895 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@abc70ce not in the list
08-18 14:10:13.508  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:10:13.508  6817  6895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9eefbef not in the list
08-18 14:10:13.508  6817  6895 D io.jxcore.node.ConnectivityMonitor: stop
08-18 14:10:13.508  6817  6895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:10:13.508  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:10:13.508  6817  6895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:10:13.508  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:10:13.509  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 14:10:13.509  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 14:10:13.512  6817  6895 D BluetoothLeScanner: could not find callback wrapper
08-18 14:10:13.512  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-18 14:10:13.512  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:10:13.512  6817  6895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9eefbef not in the list
08-18 14:10:13.513  6817  6895 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-18 14:10:13.513  6817  6895 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-18 14:10:13.513  6817  6895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-18 14:10:13.513  6817  6895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-18 14:10:13.513  6817  6895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 14:10:13.513  6817  6895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:10:13.513  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:10:13.513  6817  6895 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@abc70ce not in the list
08-18 14:10:13.513  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:10:13.513  6817  6895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9eefbef not in the list
08-18 14:10:13.513  6817  6895 D io.jxcore.node.ConnectivityMonitor: stop
08-18 14:10:13.513  6817  6895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:10:13.513  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:10:13.513  6817  6895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:10:13.513  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:10:13.515  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 14:10:13.515  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 14:10:13.515  6817  6895 D BluetoothLeScanner: could not find callback wrapper
08-18 14:10:13.515  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-18 14:10:13.515  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:10:13.515  6817  6895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9eefbef not in the list
08-18 14:10:13.515  6817  6895 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-18 14:10:13.516  6817  6895 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-18 14:10:13.516  6817  6895 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-18 14:10:13.516  6817  6895 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-18 14:10:13.517  6817  6895 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-18 14:10:13.517  6817  6895 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-18 14:10:13.517  6817  6895 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-18 14:10:13.517  6817  6895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-18 14:10:13.517  6817  6895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-18 14:10:13.517  6817  6895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 14:10:13.517  6817  6895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:10:13.517  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:10:13.517  6817  6895 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@abc70ce not in the list
08-18 14:10:13.517  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:10:13.517  6817  6895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9eefbef not in the list
08-18 14:10:13.517  6817  6895 D io.jxcore.node.ConnectivityMonitor: stop
08-18 14:10:13.517  6817  6895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:10:13.517  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:10:13.517  6817  6895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:10:13.517  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:10:13.520  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 14:10:13.520  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 14:10:13.520  6817  6895 D BluetoothLeScanner: could not find callback wrapper
08-18 14:10:13.520  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-18 14:10:13.520  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:10:13.520  6817  6895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9eefbef not in the list
08-18 14:10:13.521  6817  6895 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-18 14:10:13.521  6817  6895 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-18 14:10:13.521  6817  6895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-18 14:10:13.525  6817  6895 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-18 14:10:13.526  6817  6895 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-18 14:10:13.526  6817  6895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-18 14:10:13.526  6817  6895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-18 14:10:13.526  6817  6895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-18 14:10:13.526  6817  6895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-18 14:10:13.526  6817  6895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-18 14:10:13.526  6817  6895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-18 14:10:13.526  6817  6895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-18 14:10:13.526  6817  6895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-18 14:10:13.526  6817  6895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-18 14:10:13.526  6817  6895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-18 14:10:13.526  6817  6895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-18 14:10:13.526  6817  6895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-18 14:10:13.526  6817  6895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-18 14:10:13.526  6817  6895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-18 14:10:13.526  6817  6895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-18 14:10:13.526  6817  6895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-18 14:10:13.526  6817  6895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-18 14:10:13.526  6817  6895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-18 14:10:13.527  6817  6895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-18 14:10:13.527  6817  6895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-18 14:10:13.527  6817  6895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-18 14:10:13.527  6817  6895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-18 14:10:13.527  6817  6895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-18 14:10:13.527  6817  6895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-18 14:10:13.527  6817  6895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-18 14:10:13.527  6817  6895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-18 14:10:13.527  6817  6895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-18 14:10:13.527  6817  6895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-18 14:10:13.527  6817  6895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-18 14:10:13.527  6817  6895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-18 14:10:13.527  6817  6895 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-18 14:10:13.527  6817  6895 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-18 14:10:13.527  6817  6895 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-18 14:10:13.528  6817  6895 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-18 14:10:13.528  6817  6895 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-18 14:10:13.528  6817  6895 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-18 14:10:13.528  6817  6895 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-18 14:10:13.528  6817  6895 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-18 14:10:13.528  6817  6895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-18 14:10:13.530  6817  6895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-18 14:10:13.530  6817  6895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-18 14:10:13.530  6817  6895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-18 14:10:13.531  6817  6895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-18 14:10:13.531  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-18 14:10:13.531  6817  6895 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-18 14:10:13.531  6817  6895 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-18 14:10:13.531  6817  6895 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-18 14:10:13.531  6817  6895 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-18 14:10:13.531  6817  6895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-18 14:10:13.531  6817  6895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-18 14:10:13.532  6817  6895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 14:10:13.532  6817  6895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:10:13.532  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:10:13.532  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-18 14:10:13.532  6817  6896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 841)
,08-18 14:10:13.536  6817  6895 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@abc70ce not in the list
08-18 14:10:13.537  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:10:13.537  6817  6895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9eefbef not in the list
08-18 14:10:13.537  6817  6895 D io.jxcore.node.ConnectivityMonitor: stop
08-18 14:10:13.537  6817  6895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:10:13.537  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:10:13.537  6817  6895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:10:13.537  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:10:13.538  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 14:10:13.538  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 14:10:13.539  6817  6895 D BluetoothLeScanner: could not find callback wrapper
08-18 14:10:13.539  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-18 14:10:13.539  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:10:13.539  6817  6895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9eefbef not in the list
08-18 14:10:13.540  6817  6895 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-18 14:10:13.540  6817  6895 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-18 14:10:13.540  6817  6895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-18 14:10:13.540  6817  6895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-18 14:10:13.541  6817  6897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 841
08-18 14:10:13.541  6817  6897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 841)
08-18 14:10:13.541  6817  6897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 841)
08-18 14:10:13.546  6817  6895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 14:10:13.546  6817  6895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:10:13.546  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:10:13.546  6817  6895 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@abc70ce not in the list
08-18 14:10:13.546  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:10:13.546  6817  6895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9eefbef not in the list
08-18 14:10:13.546  6817  6895 D io.jxcore.node.ConnectivityMonitor: stop
08-18 14:10:13.546  6817  6895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:10:13.546  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:10:13.546  6817  6895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:10:13.546  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:10:13.549  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 14:10:13.549  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 14:10:13.550  6817  6895 D BluetoothLeScanner: could not find callback wrapper
08-18 14:10:13.550  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-18 14:10:13.550  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:10:13.550  6817  6895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9eefbef not in the list
08-18 14:10:13.551  6817  6895 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-18 14:10:13.556  6817  6895 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-18 14:10:13.556  6817  6895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-18 14:10:13.556  6817  6895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-18 14:10:13.556  6817  6895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 14:10:13.556  6817  6895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:10:13.556  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:10:13.556  6817  6895 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@abc70ce not in the list
08-18 14:10:13.556  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:10:13.557  6817  6895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9eefbef not in the list
08-18 14:10:13.557  6817  6895 D io.jxcore.node.ConnectivityMonitor: stop
08-18 14:10:13.557  6817  6895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:10:13.557  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:10:13.557  6817  6895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:10:13.557  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:10:13.557  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 14:10:13.557  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 14:10:13.557  6817  6895 D BluetoothLeScanner: could not find callback wrapper
08-18 14:10:13.557  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-18 14:10:13.557  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:10:13.557  6817  6895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9eefbef not in the list
08-18 14:10:13.558  6817  6895 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-18 14:10:13.558  6817  6895 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-18 14:10:13.558  6817  6895 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-18 14:10:13.558  6817  6895 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-18 14:10:13.558  6817  6895 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-18 14:10:13.558  6817  6895 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-18 14:10:13.558  6817  6895 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-18 14:10:13.558  6817  6895 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-18 14:10:13.558  6817  6895 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-18 14:10:13.558  6817  6895 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-18 14:10:13.558  6817  6895 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-18 14:10:13.558  6817  6895 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-18 14:10:13.559  6817  6895 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-18 14:10:13.559  6817  6895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-18 14:10:13.559  6817  6895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-18 14:10:13.559  6817  6895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 14:10:13.559  6817  6895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:10:13.559  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:10:13.559  6817  6895 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@abc70ce not in the list
08-18 14:10:13.559  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:10:13.559  6817  6895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9eefbef not in the list
08-18 14:10:13.559  6817  6895 D io.jxcore.node.ConnectivityMonitor: stop
08-18 14:10:13.559  6817  6895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:10:13.559  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:10:13.559  6817  6895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:10:13.559  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:10:13.559  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 14:10:13.559  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 14:10:13.560  6817  6895 D BluetoothLeScanner: could not find callback wrapper
08-18 14:10:13.560  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-18 14:10:13.560  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:10:13.560  6817  6895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9eefbef not in the list
08-18 14:10:13.560  6817  6895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 14:10:13.560  6817  6895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:10:13.560  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:10:13.560  6817  6895 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@abc70ce not in the list
08-18 14:10:13.560  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:10:13.560  6817  6895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9eefbef not in the list
08-18 14:10:13.560  6817  6895 D io.jxcore.node.ConnectivityMonitor: stop
08-18 14:10:13.560  6817  6895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:10:13.560  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:10:13.560  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:10:13.560  6817  6895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9eefbef not in the list
08-18 14:10:13.560  6817  6895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 14:10:13.560  6817  6895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:10:13.560  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:10:13.561  6817  6895 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@abc70ce not in the list
08-18 14:10:13.561  6817  6895 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-18 14:10:13.561  6817  6895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-18 14:10:13.561  6817  6895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-18 14:10:13.561  6817  6895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 14:10:13.561  6817  6895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:10:13.561  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:10:13.561  6817  6895 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@abc70ce not in the list
08-18 14:10:13.561  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:10:13.561  6817  6895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9eefbef not in the list
08-18 14:10:13.561  6817  6895 D io.jxcore.node.ConnectivityMonitor: stop
08-18 14:10:13.561  6817  6895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:10:13.561  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:10:13.561  6817  6895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:10:13.561  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:10:13.561  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 14:10:13.561  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 14:10:13.562  6817  6895 D BluetoothLeScanner: could not find callback wrapper
08-18 14:10:13.562  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-18 14:10:13.562  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:10:13.562  6817  6895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9eefbef not in the list
08-18 14:10:13.563  6817  6895 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-18 14:10:13.563  6817  6895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-18 14:10:13.563  6817  6895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-18 14:10:13.564  6817  6895 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-18 14:10:13.564  6817  6895 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-18 14:10:13.564  6817  6817 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-18 14:10:13.564  6817  6895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-18 14:10:13.564  6817  6895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-18 14:10:13.565  6817  6895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 14:10:13.565  6817  6895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-18 14:10:13.565  6817  6895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-18 14:10:13.565  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-18 14:10:13.565  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:10:13.565  6817  6895 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-18 14:10:13.565  6817  6817 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-18 14:10:13.565  6817  6895 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@abc70ce not in the list
08-18 14:10:13.565  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:10:13.565  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-18 14:10:13.565  6817  6895 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-18 14:10:13.565  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-18 14:10:13.566  6817  6895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-18 14:10:13.572  6817  6895 D BluetoothLeScanner: could not find callback wrapper
08-18 14:10:13.572  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-18 14:10:13.572  6817  6895 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-18 14:10:13.572  6817  6895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:10:13.572  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:10:13.574  6817  6895 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-18 14:10:13.574  6817  6817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-18 14:10:13.575  6817  6817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-18 14:10:13.575  6817  6817 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-18 14:10:13.575  6817  6895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9eefbef not in the list
08-18 14:10:13.575  6817  6895 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-18 14:10:13.575  6817  6895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-18 14:10:13.575  6817  6895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-18 14:10:13.575  6817  6895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 14:10:13.575  6817  6895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:10:13.575  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:10:13.575  6817  6895 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@abc70ce not in the list
08-18 14:10:13.575  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:10:13.575  6817  6895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9eefbef not in the list
08-18 14:10:13.575  6817  6895 D io.jxcore.node.ConnectivityMonitor: stop
08-18 14:10:13.575  6817  6895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:10:13.575  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:10:13.575  6817  6895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:10:13.576  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:10:13.576  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 14:10:13.576  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 14:10:13.576  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:10:13.576  6817  6895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9eefbef not in the list
08-18 14:10:13.578  6817  6895 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-18 14:10:13.579  6817  6898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-18 14:10:13.579  6817  6898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-18 14:10:13.580  6817  6895 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-18 14:10:13.580  6817  6895 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-18 14:10:13.581  6817  6895 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-18 14:10:13.582  6817  6895 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-18 14:10:13.582  6817  6895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-18 14:10:13.582  6817  6895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-18 14:10:13.582  6817  6895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 14:10:13.582  6817  6895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:10:13.582  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:10:13.582  6817  6895 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@abc70ce not in the list
08-18 14:10:13.582  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:10:13.582  6817  6895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9eefbef not in the list
08-18 14:10:13.582  6817  6895 D io.jxcore.node.ConnectivityMonitor: stop
08-18 14:10:13.582  6817  6895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:10:13.582  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:10:13.583  6817  6895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:10:13.583  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:10:13.583  6817  6817 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-18 14:10:13.584  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 14:10:13.584  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 14:10:13.584  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:10:13.584  6817  6895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9eefbef not in the list
08-18 14:10:13.586  1034  1810 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-18 14:10:13.587  1034  1901 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-18 14:10:13.590  1034  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-18 14:10:13.590  6817  6895 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-18 14:10:13.590  6817  6895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-18 14:10:13.590  6817  6895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-18 14:10:13.590  6817  6895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 14:10:13.590  6817  6895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:10:13.590  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:10:13.590  6817  6895 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@abc70ce not in the list
08-18 14:10:13.590  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:10:13.590  6817  6895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9eefbef not in the list
08-18 14:10:13.590  6817  6895 D io.jxcore.node.ConnectivityMonitor: stop
08-18 14:10:13.590  6817  6895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:10:13.590  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:10:13.590  6817  6895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:10:13.590  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:10:13.591  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 14:10:13.591  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 14:10:13.591  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:10:13.591  6817  6895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9eefbef not in the list
08-18 14:10:13.592  6817  6895 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-18 14:10:13.592  6817  6895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-18 14:10:13.592  6817  6895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-18 14:10:13.592  6817  6895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 14:10:13.592  6817  6895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:10:13.592  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:10:13.592  6817  6895 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@abc70ce not in the list
08-18 14:10:13.592  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:10:13.592  6817  6895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9eefbef not in the list
08-18 14:10:13.592  6817  6895 D io.jxcore.node.ConnectivityMonitor: stop
08-18 14:10:13.592  6817  6895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:10:13.592  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:10:13.592  6817  6895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:10:13.592  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:10:13.593  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 14:10:13.593  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 14:10:13.593  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:10:13.593  6817  6895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9eefbef not in the list
08-18 14:10:13.594  6817  6895 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-18 14:10:13.594  6817  6895 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-18 14:10:13.594  6817  6895 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-18 14:10:13.594  6817  6895 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-18 14:10:13.594  6817  6895 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-18 14:10:13.594  6817  6895 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-18 14:10:13.595  6817  6895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-18 14:10:13.595  6817  6895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-18 14:10:13.596  6817  6895 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-18 14:10:13.596  6817  6895 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-18 14:10:13.596  6817  6895 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-18 14:10:13.596  6817  6895 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-18 14:10:13.596  6817  6895 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-18 14:10:13.596  6817  6895 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-18 14:10:13.596  6817  6895 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-18 14:10:13.596  6817  6895 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-18 14:10:13.597  6817  6895 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-18 14:10:13.597  6817  6895 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-18 14:10:13.597  6817  6895 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-18 14:10:13.597  6817  6895 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-18 14:10:13.598  6817  6895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-18 14:10:13.598  6817  6895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@39a67994 added. We now have 2 listener(s)
08-18 14:10:13.598  6817  6895 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-18 14:10:13.599  6817  6895 D BluetoothAdapter: enable(): BT is already enabled..!
08-18 14:10:13.600  1034  2023 D WifiServiceImplEx: setWifiEnabled: true pid=6817, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-18 14:10:13.600  1034  2023 D WifiService: setWifiEnabled: true pid=6817, uid=10118
08-18 14:10:13.600  1034  2023 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-18 14:10:13.601  6817  6895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-18 14:10:13.601  6817  6895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@21650c3d added. We now have 3 listener(s)
08-18 14:10:13.601  6817  6895 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-18 14:10:13.605  6817  6895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-18 14:10:13.605  6817  6895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@35eefc32 added. We now have 4 listener(s)
08-18 14:10:13.605  6817  6895 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-18 14:10:13.607  6817  6895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-18 14:10:13.607  6817  6895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@844cd83 added. We now have 5 listener(s)
08-18 14:10:13.607  6817  6895 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-18 14:10:13.608  1034  2023 D WifiServiceImplEx: setWifiEnabled: false pid=6817, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-18 14:10:13.608  1034  2023 D WifiService: setWifiEnabled: false pid=6817, uid=10118
08-18 14:10:13.608  1034  2023 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-18 14:10:13.627  1034  1540 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-18 14:10:13.627  1034  1540 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
,08-18 14:10:13.628  1034  1540 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-18 14:10:13.628  1034  1540 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-18 14:10:13.628  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-18 14:10:13.628  1034  1540 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-18 14:10:13.628  1034  1540 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-18 14:10:13.628  1034  1540 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-18 14:10:13.628  1034  1540 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-18 14:10:13.629  1034  1540 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-18 14:10:13.629  1034  1540 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-18 14:10:13.630  1034  2035 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-18 14:10:13.630  1034  2035 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@2b47355b mBinding = false
08-18 14:10:13.630  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-18 14:10:13.630  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-18 14:10:13.635  1034  1540 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-18 14:10:13.635  1034  1540 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-18 14:10:13.636  1034  1539 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-18 14:10:13.636  1034  1539 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-18 14:10:13.636  2686  2686 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-18 14:10:13.636  1034  1540 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-18 14:10:13.636  1034  1540 D WifiNative-wlan0: doBoolean: SET ps 1
08-18 14:10:13.637  1034  1540 D WifiNative-wlan0: SET ps 1: returned true
08-18 14:10:13.637  1034  2827 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-18 14:10:13.637   309   903 D CommandListener: Clearing all IP addresses on wlan0
08-18 14:10:13.646  6817  6896 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
08-18 14:10:13.647  6817  6896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 841)
,08-18 14:10:13.655  1034  1101 D BluetoothManagerService: Message: 2
08-18 14:10:13.656  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-18 14:10:13.657  1034  1101 D BluetoothManagerService: Sending off request.
08-18 14:10:13.658  3895  4023 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-18 14:10:13.658  6817  6895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-18 14:10:13.660  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-18 14:10:13.660  6817  6895 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-18 14:10:13.660  6817  6895 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 14:10:13.660  6817  6895 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-18 14:10:13.660  6817  6895 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 14:10:13.660  6817  6895 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-18 14:10:13.660  6817  6895 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-18 14:10:13.660  6817  6895 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-18 14:10:13.660  6817  6895 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-18 14:10:13.661  6817  6895 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-18 14:10:13.661  6817  6895 D io.jxcore.node.ConnectivityMonitor: start: OK
08-18 14:10:13.662  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-18 14:10:13.662  3895  3975 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-18 14:10:13.662  3895  3975 D BluetoothAdapterProperties: Setting state to 13
08-18 14:10:13.662  3895  3975 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-18 14:10:13.663  3895  3975 D BluetoothAdapterProperties: onBluetoothDisable()
08-18 14:10:13.663  3895  3975 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-18 14:10:13.664  6817  6817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-18 14:10:13.664  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-18 14:10:13.664  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 14:10:13.664  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-18 14:10:13.664  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 14:10:13.664  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-18 14:10:13.664  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-18 14:10:13.664  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-18 14:10:13.664  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-18 14:10:13.665  6817  6817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-18 14:10:13.665  6817  6817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-18 14:10:13.665  1034  1101 D BluetoothManagerService: Message: 60
08-18 14:10:13.665  1034  1101 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-18 14:10:13.665  1034  1101 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-18 14:10:13.671  3895  3895 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-18 14:10:13.672  3895  3895 D BluetoothMapService: STATE_TURNING_OFF
08-18 14:10:13.672  3895  3895 V BtOppService: Receiver DISABLED_ACTION 
08-18 14:10:13.672  3895  3895 V BluetoothMapService: Handler(): got msg=4
08-18 14:10:13.672  3895  3895 D BluetoothMapService: MAP Service closeService in
08-18 14:10:13.672  3895  3895 D BluetoothMapMasInstance: MAP Service shutdown
,08-18 14:10:13.674  3895  4227 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-18 14:10:13.674  3895  4227 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-18 14:10:13.674  3895  4227 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-18 14:10:13.674  3895  4227 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-18 14:10:13.674  3895  4227 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-18 14:10:13.674  3895  4227 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-18 14:10:13.674  3895  4227 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-18 14:10:13.674  3895  4227 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,08-18 14:10:13.675  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-18 14:10:13.676  3895  3895 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-18 14:10:13.676  3895  3895 V BluetoothMapService: MAP Service closeService out
08-18 14:10:13.676  3895  3895 I BtOppRfcommListener: stopping Accept Thread
08-18 14:10:13.676  3895  3895 V BtOppRfcommListener: close mBtServerSocket
08-18 14:10:13.676  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 14:10:13.676  3895  3895 V BtOppRfcommListener: waiting for thread to terminate
08-18 14:10:13.676  1944  1944 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-18 14:10:13.677  3895  4263 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-18 14:10:13.677  3895  4263 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-18 14:10:13.677  3895  3895 V BtOppRfcommListener: done waiting for thread to terminate
08-18 14:10:13.678  1034  1547 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-18 14:10:13.678  1034  1547 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
08-18 14:10:13.686  6817  6817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-18 14:10:13.686  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-18 14:10:13.686  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 14:10:13.686  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-18 14:10:13.686  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 14:10:13.686  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-18 14:10:13.686  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-18 14:10:13.686  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-18 14:10:13.686  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-18 14:10:13.688  6817  6817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-18 14:10:13.688  6817  6817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-18 14:10:13.690  6817  6817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-18 14:10:13.690  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-18 14:10:13.690  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 14:10:13.690  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-18 14:10:13.690  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 14:10:13.690  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-18 14:10:13.690  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-18 14:10:13.690  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-18 14:10:13.690  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-18 14:10:13.690  1034  1051 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
08-18 14:10:13.691  1034  2824 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-18 14:10:13.691  1034  2824 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-18 14:10:13.691  1034  2824 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-18 14:10:13.691  1034  2824 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
08-18 14:10:13.691  1034  2824 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
08-18 14:10:13.694  6817  6817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-18 14:10:13.694  6817  6817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-18 14:10:13.721  1034  1547 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-18 14:10:13.721  1034  1547 D DSQN    : disableDataServiceNotify
08-18 14:10:13.721  1034  1547 D DSQN    : stop dsqn bin
08-18 14:10:13.722   309  6912 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-18 14:10:13.724  1034  2824 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
08-18 14:10:13.725  1034  1099 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-18 14:10:13.730  1034  1547 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-18 14:10:13.730  1034  1547 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-18 14:10:13.730  1034  1547 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-18 14:10:13.730  1034  1547 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-18 14:10:13.731  1034  1547 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-18 14:10:13.731  1034  1547 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-18 14:10:13.731  1034  1547 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-18 14:10:13.732  1034  1547 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-18 14:10:13.732  1034  2824 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-18 14:10:13.732  1034  2824 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-18 14:10:13.732  1034  2824 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-18 14:10:13.733  1034  1092 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6913 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-18 14:10:13.733  1605  1818 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-18 14:10:13.736  3895  3978 D BluetoothAdapterProperties: Scan Mode:20
08-18 14:10:13.737  3895  3975 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-18 14:10:13.737  3895  3895 V BtOppService: onDestroy
08-18 14:10:13.737  3895  4266 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-18 14:10:13.737  3895  3975 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-18 14:10:13.738  3895  3895 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-18 14:10:13.738  3895  4228 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-18 14:10:13.739  3895  4087 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-18 14:10:13.739  3895  4087 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-18 14:10:13.740  3895  4087 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-18 14:10:13.740  3895  4087 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-18 14:10:13.740  3895  4087 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-18 14:10:13.740  3895  4087 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-18 14:10:13.740  3895  4087 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-18 14:10:13.740  3895  4087 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-18 14:10:13.740  3895  4087 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-18 14:10:13.740  3895  4087 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-18 14:10:13.740  3895  4087 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-18 14:10:13.740  3895  4087 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-18 14:10:13.740  3895  4087 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-18 14:10:13.740  3895  4087 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-18 14:10:13.740  3895  4264 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-18 14:10:13.746  1944  1944 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-18 14:10:13.747  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-18 14:10:13.747  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-18 14:10:13.747  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-18 14:10:13.747  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-18 14:10:13.761  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-18 14:10:13.761  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-18 14:10:13.762  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-18 14:10:13.784  1034  1092 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6934 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-18 14:10:13.785  1034  1547 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-18 14:10:13.785  1034  1547 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-18 14:10:13.786  1034  1547 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-18 14:10:13.787  1034  1547 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-18 14:10:13.787  1034  1547 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-18 14:10:13.787  1034  1547 D NetworkManagementService: Removing idletimer
08-18 14:10:13.789  1855  1855 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-18 14:10:13.789  1855  1855 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-18 14:10:13.790  6817  6817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-18 14:10:13.790  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-18 14:10:13.790  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 14:10:13.790  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-18 14:10:13.790  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 14:10:13.790  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-18 14:10:13.790  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-18 14:10:13.790  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-18 14:10:13.790  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-18 14:10:13.791  1034  1034 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-18 14:10:13.791  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-18 14:10:13.791  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-18 14:10:13.791  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-18 14:10:13.792  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-18 14:10:13.793  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-18 14:10:13.793  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-18 14:10:13.794  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-18 14:10:13.794  1034  1538 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-18 14:10:13.796  1034  1538 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-18 14:10:13.797  1034  1034 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-18 14:10:13.797  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-18 14:10:13.797  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, f,ailover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-18 14:10:13.797  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,08-18 14:10:13.801  1034  1547 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-18 14:10:13.802  1034  1547 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-18 14:10:13.804  1034  1539 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-18 14:10:13.804  1034  1539 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-18 14:10:13.804  1034  1539 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@27dd61b5
08-18 14:10:13.804  1034  1540 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-18 14:10:13.804  1034  1539 D LGWifiP2pService: P2pDisablingState
08-18 14:10:13.804  1034  1539 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-18 14:10:13.804  1034  1539 D LGWifiP2pService: p2p socket connection lost
08-18 14:10:13.804  1034  1540 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-18 14:10:13.804  1034  1539 D LGWifiP2pService: P2pDisabledState
08-18 14:10:13.805  1034  1540 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-18 14:10:13.805  1034  1540 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-18 14:10:13.806  1034  1540 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-18 14:10:13.806  1034  1540 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-18 14:10:13.806  1034  1540 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-18 14:10:13.809  1034  1034 D WifiScanningService: SCAN_AVAILABLE : 1
08-18 14:10:13.809  1034  1034 D RttService: SCAN_AVAILABLE : 1
08-18 14:10:13.809  1034  1559 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,08-18 14:10:13.810  1034  1558 D WifiScanningService: DefaultState got{ when=-2ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-18 14:10:13.812  1034  1540 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-18 14:10:13.815  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 14:10:13.816  1944  1944 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-18 14:10:13.816  1944  1944 D WfdsService: WifiP2pState is changed : false
08-18 14:10:13.817  1944  2342 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-18 14:10:13.817  1944  2342 D WfdsService: Set the WFDS Monitor: false
08-18 14:10:13.817  1944  2342 D WfdsMonitor: WFDS Monitor is stopped
08-18 14:10:13.817  1944  2743 D CtrlSupplicant: Received on exit socket, terminate
08-18 14:10:13.818  1944  2743 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-18 14:10:13.818  1944  2342 D WfdsService: STATE : WfdsDisabledState - enter
08-18 14:10:13.818  1944  2743 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-18 14:10:13.818  1944  2743 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-18 14:10:13.818  1944  2342 W WfdsService: DefaultState - msg [9445378] is not handled
08-18 14:10:13.818  1034  1540 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-18 14:10:13.818  1944  2344 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-18 14:10:13.818  6913  6913 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-18 14:10:13.818  6913  6913 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-18 14:10:13.818  1034  1540 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-18 14:10:13.818  1034  1540 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-18 14:10:13.818  6913  6913 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-18 14:10:13.818  1034  1540 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-18 14:10:13.819  6913  6913 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-18 14:10:13.819  1034  1540 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-18 14:10:13.819  1034  1539 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-18 14:10:13.819  1034  1539 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-18 14:10:13.819  1034  1540 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-18 14:10:13.819  2686  2686 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-18 14:10:13.820  6913  6913 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-18 14:10:13.820  1034  1540 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-18 14:10:13.820  1034  1540 D WifiNative-wlan0: doBoolean: SET ps 1
08-18 14:10:13.820  6913  6913 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-18 14:10:13.820  1034  1540 D WifiNative-wlan0: SET ps 1: returned true
08-18 14:10:13.820   309   903 D CommandListener: Clearing all IP addresses on wlan0
08-18 14:10:13.823  1034  1540 D WifiNative-p2p0: doBoolean: TERMINATE
08-18 14:10:13.824  1034  1540 D WifiNative-p2p0: TERMINATE: returned true
08-18 14:10:13.824  1034  1540 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-18 14:10:13.824  1034  1540 E Wif,iStateMachine: useWiFiOffloading() : false
08-18 14:10:13.824  1034  1540 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-18 14:10:13.825  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-18 14:10:13.827  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-18 14:10:13.827  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-18 14:10:13.827  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,08-18 14:10:13.833  1944  1944 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6,
08-18 14:10:13.836  6817  6817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-18 14:10:13.837  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-18 14:10:13.837  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 14:10:13.837  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-18 14:10:13.837  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-18 14:10:13.837  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-18 14:10:13.837  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-18 14:10:13.837  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-18 14:10:13.837  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-18 14:10:13.837  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-18 14:10:13.838  6817  6817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-18 14:10:13.838  6817  6817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-18 14:10:13.845  1034  2827 D DhcpStateMachine: StoppedState
08-18 14:10:13.845  1034  2827 D DhcpStateMachine: StoppedState{ when=-25ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,08-18 14:10:13.848  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-18 14:10:13.848  1034  1034 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-18 14:10:13.848  6817  6817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-18 14:10:13.848  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-18 14:10:13.848  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 14:10:13.848  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-18 14:10:13.848  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-18 14:10:13.848  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-18 14:10:13.848  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-18 14:10:13.848  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-18 14:10:13.848  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-18 14:10:13.849  6817  6817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-18 14:10:13.849  6817  6817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-18 14:10:13.850  1034  1540 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-18 14:10:13.851  1034  1540 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-18 14:10:13.851  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-18 14:10:13.852  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-18 14:10:13.853  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-18 14:10:13.853  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-18 14:10:13.853  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-18 14:10:13.854  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-18 14:10:13.901  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-18 14:10:13.901  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-18 14:10:13.902  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-18 14:10:13.902  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-18 14:10:13.902  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-18 14:10:13.903  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-18 14:10:13.904  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-18 14:10:13.907  6934  6934 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-18 14:10:13.907  6934  6934 W LG Account v2.2: No ProfileInfo entries
08-18 14:10:13.907  6934  6934 I LG Account v2.2: isEnabled: false
08-18 14:10:13.907  6934  6934 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-18 14:10:13.907  6934  6934 I Feature : [Lifetracker]Country: EU
08-18 14:10:13.907  6934  6934 I Feature : [Lifetracker]Operator: OPEN
08-18 14:10:13.907  6934  6934 I Feature : [Lifetracker]Ranking support: false
08-18 14:10:13.907  6934  6934 I Feature : [Lifetracker]Comfort support: false
08-18 14:10:13.907  6934  6934 I Feature : [Lifetracker]Accessory: true
08-18 14:10:13.907  6934  6934 I Feature : [Lifetracker]Health device: true
08-18 14:10:13.907  6934  6934 I Feature : [Lifetracker]Extra Pedometer: false
08-18 14:10:13.907  6934  6934 I Feature : [Lifetracker]Blood glucose device: false
08-18 14:10:13.908  6934  6934 I Feature : [Lifetracker]Device Number: 3
08-18 14:10:13.916  6505  6505 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-18 14:10:13.918  2686  2686 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-18 14:10:13.918  2686  2686 I wpa_supplicant: monitor socket send errors count : 1
,08-18 14:10:13.918  2686  2686 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1944-2\x00 that cannot receive messages
,08-18 14:10:13.919  1034  2738 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
,08-18 14:10:13.919  1034  2738 D WifiMonitor: Dropping event because (p2p0) is stopped
08-18 14:10:13.940  6913  6913 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-18 14:10:13.947  1034  2013 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6956 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-18 14:10:13.948  1034  2013 I ActivityManager: Killing 6303:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-18 14:10:13.956  2686  2686 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-18 14:10:13.957  2686  2686 W wpa_supplicant: USIM:  scard_deinit function
08-18 14:10:13.957  1034  1101 D Tethering: InitialState.processMessage what=4
08-18 14:10:13.958  1034  2738 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-18 14:10:13.958  1034  2738 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-18 14:10:13.958  1034  2738 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-18 14:10:13.958  1034  2738 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-18 14:10:13.958   348   348 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 221us total 11.162ms
08-18 14:10:13.959  1034  2738 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-18 14:10:13.959  1034  2738 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-18 14:10:13.959  1034  1540 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=194688
08-18 14:10:13.959  1034  1540 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=194688
08-18 14:10:13.959  1034  1540 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=194688  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-18 14:10:13.960  1034  1540 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=194689  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-18 14:10:13.968   348   348 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 199us total 9.580ms
08-18 14:10:13.978   348   348 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 183us total 9.564ms
,08-18 14:10:13.988  1034  1101 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-18 14:10:13.988  1034  2023 W libprocessgroup: failed to open /acct/uid_10014/pid_6303/cgroup.procs: No such file or directory
,08-18 14:10:13.992  1034  1101 D BluetoothManagerService: Message: 20
08-18 14:10:13.992  1034  1101 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1234eec2:true
08-18 14:10:13.994  3895  3895 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-18 14:10:13.994  3895  3895 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-18 14:10:13.994  3895  3895 V BluetoothPbapReceiver: ***********state = 13
08-18 14:10:13.995  1034  1540 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-18 14:10:13.995  1034  1540 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-18 14:10:13.995  3895  3895 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-18 14:10:13.998  3895  3895 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-18 14:10:13.998  3895  3895 V BluetoothPbapService: state: 13
08-18 14:10:13.998  3895  3895 V BluetoothPbapService: Pbap Service closeService in
08-18 14:10:14.000  2161  2161 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-18 14:10:14.000  3895  3895 V BluetoothPbapService: successfully stopped pbap service
08-18 14:10:14.000  3895  3895 V BluetoothPbapService: Pbap Service closeService out
08-18 14:10:14.001  3895  3895 V BluetoothPbapService: Pbap Service onDestroy
08-18 14:10:14.001  3895  3895 V BluetoothPbapService: Pbap Service closeService in
08-18 14:10:14.001  3895  3895 V BluetoothPbapService: Pbap Service closeService out
,08-18 14:10:14.001  3895  3895 D LGBluetoothPbapAdapter: [BTUI] cleanup
,08-18 14:10:14.003  1034  1101 D BluetoothManagerService: Message: 30
08-18 14:10:14.008  1034  1101 D BluetoothManagerService: Message: 30
08-18 14:10:14.009  6913  6913 D LocalBluetoothProfileManager: Adding local MAP profile
08-18 14:10:14.010  6913  6913 D BluetoothMap: Create BluetoothMap proxy object
08-18 14:10:14.010  1034  1101 D BluetoothManagerService: Message: 30
08-18 14:10:14.012  1034  1101 D BluetoothManagerService: Message: 30
,08-18 14:10:14.013  6913  6913 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-18 14:10:14.014  6913  6913 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
08-18 14:10:14.022  6913  6913 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
08-18 14:10:14.025  6913  6913 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
,08-18 14:10:14.027  2686  2686 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-18 14:10:14.027  1034  2738 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-18 14:10:14.027  1034  2738 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
08-18 14:10:14.027  1034  2738 D WifiMonitor: Disconnecting from the supplicant, no more events
08-18 14:10:14.028  1034  1540 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
08-18 14:10:14.030  6913  6913 D DockEventReceiver: finishStartingService: stopping service
08-18 14:10:14.038  6956  6956 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-18 14:10:14.039  6913  6913 D BluetoothInputDevice: Proxy object connected
08-18 14:10:14.040  6913  6913 D HidProfile: Bluetooth service connected
08-18 14:10:14.041  6913  6913 D BluetoothPan: BluetoothPAN Proxy object connected
08-18 14:10:14.041  6913  6913 D PanProfile: Bluetooth service connected
08-18 14:10:14.042  6913  6913 D BluetoothMap: Proxy object connected
08-18 14:10:14.042  6956  6956 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-18 14:10:14.042  6956  6956 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-18 14:10:14.042  6913  6913 D MapProfile: Bluetooth service connected
08-18 14:10:14.042  6913  6913 D BluetoothMap: getConnectedDevices()
08-18 14:10:14.043  6913  6913 D BluetoothMap: Bluetooth is Not enabled
08-18 14:10:14.043  6913  6913 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-18 14:10:14.043  1034  1901 I ActivityManager: Killing 6406:com.android.defcontainer/u0a4 (adj 15): empty #17
08-18 14:10:14.044  6913  6913 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-18 14:10:14.074  1034  1577 W libprocessgroup: failed to open /acct/uid_10004/pid_6406/cgroup.procs: No such file or directory
,08-18 14:10:14.076  6817  6817 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-18 14:10:14.084  6913  6913 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-18 14:10:14.122  6913  6913 D LgDataFeature: LgDataFeature() Constructor: none
,08-18 14:10:14.122  6913  6913 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-18 14:10:14.130  1034  1540 D WifiOffDelayIfNotUsed: stopMonitoring
,08-18 14:10:14.130  1034  1540 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-18 14:10:14.130  1034  1540 E WifiStateMachine: useWiFiOffloading() : false
08-18 14:10:14.130  1034  1540 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-18 14:10:14.132  1944  1944 D WfdsService: Supplicant Connection state is changed : false
08-18 14:10:14.132  1944  2342 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-18 14:10:14.132  1944  2342 D WfdsService: Set the WFDS Monitor: false
08-18 14:10:14.132  1944  2342 D WfdsMonitor: WFDS Monitor is stopped
08-18 14:10:14.133  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-18 14:10:14.134  6913  6913 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-18 14:10:14.135  6913  6913 D BluetoothPermissionRequest: onReceive
08-18 14:10:14.135  1944  1944 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-18 14:10:14.137  2503  2503 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-18 14:10:14.139  6913  6913 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-18 14:10:14.142  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 14:10:14.143  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-18 14:10:14.143  1034  1545 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-18 14:10:14.144  1034  1545 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-18 14:10:14.147  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-18 14:10:14.157  1034  1943 I ActivityManager: Killing 6553:com.google.android.partnersetup/u0a8 (adj 15): empty #17
08-18 14:10:14.164  6913  6913 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-18 14:10:14.189  3895  3895 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-18 14:10:14.189  3895  3895 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,08-18 14:10:14.189  1034  1577 W libprocessgroup: failed to open /acct/uid_10008/pid_6553/cgroup.procs: No such file or directory
,08-18 14:10:14.189  3895  3895 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-18 14:10:14.263  1034  1943 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6984 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
08-18 14:10:14.264  3895  3895 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-18 14:10:14.265  3895  3895 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,08-18 14:10:14.268  3895  3895 V BluetoothFtpService: Ftp Service onStartCommand
08-18 14:10:14.268  3895  3895 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-18 14:10:14.269  3895  3895 V BluetoothFtpService: Ftp Service closeService
08-18 14:10:14.269  3895  3895 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-18 14:10:14.272  3895  3895 V BluetoothFtpService: successfully stopped ftp service
08-18 14:10:14.273  3895  3895 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-18 14:10:14.273  3895  3895 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-18 14:10:14.273  3895  3895 V BluetoothSapReceiver: SapReceiver onReceive 
08-18 14:10:14.273  3895  3895 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-18 14:10:14.273  3895  3895 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-18 14:10:14.273  3895  3895 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-18 14:10:14.275  3895  3895 V BluetoothFtpService: Ftp Service onDestroy
08-18 14:10:14.275  3895  3895 V BluetoothFtpService: Ftp Service closeService
08-18 14:10:14.334  1034  2054 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7001 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-18 14:10:14.334  3895  3895 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,08-18 14:10:14.334  3895  3895 V BluetoothSapService: state: 13
08-18 14:10:14.334  3895  3895 V BluetoothSapService: Stopping SAP server process
08-18 14:10:14.335  3895  3895 V BluetoothSapService: Sap Service closeSapService in
08-18 14:10:14.335  3895  3895 V BluetoothSapService: Close listen Socket : 
,08-18 14:10:14.335  3895  3895 V BluetoothSapService: Close rfcomm Socket : 
08-18 14:10:14.335  3895  3895 V BluetoothSapService: Close sapd  Socket : 
08-18 14:10:14.342  3895  3895 V BluetoothSapService: Sap Service closeSapService out
08-18 14:10:14.343  3895  3895 V BluetoothSapService: Sap Service onDestroy
08-18 14:10:14.343  3895  3895 V BluetoothSapService: Sap Service closeSapService in
08-18 14:10:14.343  3895  3895 V BluetoothSapService: Close listen Socket : 
08-18 14:10:14.343  3895  3895 V BluetoothSapService: Close rfcomm Socket : 
08-18 14:10:14.343  3895  3895 V BluetoothSapService: Close sapd  Socket : 
08-18 14:10:14.344  3895  3895 V BluetoothSapService: Sap Service closeSapService out
08-18 14:10:14.374  6984  6984 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-18 14:10:14.392  7001  7001 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-18 14:10:14.398  6984  6984 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
08-18 14:10:14.411  1034  1989 I ActivityManager: Killing 6065:com.lge.appbox.client/u0a11 (adj 15): empty #17
,08-18 14:10:14.434  6984  6984 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,08-18 14:10:14.434  6984  6984 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-18 14:10:14.435  6984  6984 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-18 14:10:14.435  6984  6984 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-18 14:10:14.435  6984  6984 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-18 14:10:14.437  6984  6984 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-18 14:10:14.441  6984  6984 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-18 14:10:14.521  1034  1622 W libprocessgroup: failed to open /acct/uid_10011/pid_6065/cgroup.procs: No such file or directory
,08-18 14:10:14.549  6984  6984 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-18 14:10:14.566  6984  6984 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-18 14:10:14.603  6984  6984 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-18 14:10:14.609  6505  6505 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-18 14:10:14.613  6956  6956 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-18 14:10:14.613  6956  6956 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-18 14:10:14.613  6956  6956 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-18 14:10:14.614  6984  6984 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-18 14:10:14.617  6913  6913 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-18 14:10:14.619  6984  6984 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
,08-18 14:10:14.625  6913  6913 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-18 14:10:14.632  6984  6984 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-18 14:10:14.633  6984  6984 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-18 14:10:14.637  6984  6984 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-18 14:10:14.641  6505  6505 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-18 14:10:14.645  6956  6956 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-18 14:10:14.645  6956  6956 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-18 14:10:14.645  6956  6956 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-18 14:10:14.649  6913  6913 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-18 14:10:14.660  6913  6913 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-18 14:10:14.671  6984  6984 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-18 14:10:14.672  6984  6984 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-18 14:10:14.677  6984  6984 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-18 14:10:14.745  3895  3978 D bt_hci_bdroid: cleanup
,08-18 14:10:14.746  3895  4090 I bt_lpm  : LPM is already off!!!
08-18 14:10:14.746  3895  4216 I bt_userial_mct: exiting userial_read_thread
08-18 14:10:14.746  3895  4216 D bt_userial_mct: Leaving userial_evt_read_thread()
08-18 14:10:14.747  3895  3978 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-18 14:10:14.747  3895  4090 I bt_vendor: hw_epilog_process
08-18 14:10:14.748  1034  2013 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7024 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
08-18 14:10:14.749  3895  3978 D bt_hci_bdroid: cleanup Finalizing cleanup
08-18 14:10:14.749  3895  3978 D bt_userial_mct: userial_close
08-18 14:10:14.749  3895  3978 E bt_userial_mct: pthread_join() FAILED result:3
08-18 14:10:14.749  3895  3978 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-18 14:10:14.750  3895  4087 W bt-btif : ag scb idx 1 not allocated
08-18 14:10:14.750  3895  4087 E bt-btif : BTA AG is already disabled, ignoring ...
08-18 14:10:14.750  3895  4087 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-18 14:10:14.750  3895  4087 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-18 14:10:14.750  3895  4087 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-18 14:10:14.750  3895  4087 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-18 14:10:14.750  3895  4087 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-18 14:10:14.750  3895  4087 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-18 14:10:14.750  3895  4087 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-18 14:10:14.750  3895  4087 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-18 14:10:14.750  3895  4087 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-18 14:10:14.750  3895  4087 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-18 14:10:14.750  3895  4087 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-18 14:10:14.750  3895  4087 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-18 14:10:14.750  3895  4087 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-18 14:10:14.750  3895  4087 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-18 14:10:14.751  3895  4087 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-18 14:10:14.751  3895  4087 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-18 14:10:14.751  3895  4087 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-18 14:10:14.751  3895  4087 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-18 14:10:14.751  3895  4087 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
,08-18 14:10:14.837  3895  3978 D bt_hci_bdroid: set_power 0
08-18 14:10:14.837  3895  3978 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-18 14:10:14.837  3895  3978 I bt_vendor: bluetooth satus is on
08-18 14:10:14.837  3895  3978 I bt_vendor: bt-vendor : resetting BT status
08-18 14:10:14.837  3895  3978 I bt_vendor: Starting hciattach daemon
08-18 14:10:14.837  3895  3978 I bt_vendor: try to set false
08-18 14:10:14.839  3895  3978 I bt_vendor: Starting hciattach daemon
08-18 14:10:14.839  3895  3978 I bt_vendor: try to set false
08-18 14:10:14.840  3895  3978 I bt_vendor: cleanup
,08-18 14:10:14.841  3895  4087 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-18 14:10:14.847  3895  3978 I GKI_LINUX: GKI_exit_task 0 done
08-18 14:10:14.847  3895  3978 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-18 14:10:14.849  3895  3975 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-18 14:10:14.852  3895  3895 D HeadsetService: Received stop request...Stopping profile...
08-18 14:10:14.853  3895  3895 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-18 14:10:14.853  3895  3895 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-18 14:10:14.853  3895  3895 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@278dbecc
08-18 14:10:14.854  3895  4011 D HeadsetStateMachine: Exit Disconnected: -1
,08-18 14:10:14.855  1855  1855 D BluetoothHeadset: Proxy object disconnected
08-18 14:10:14.856  1855  1855 D BluetoothHeadset: Proxy object disconnected
08-18 14:10:14.856  1855  1855 D BluetoothHeadset: Proxy object disconnected
08-18 14:10:14.857  1034  1034 D BluetoothHeadset: Proxy object disconnected
08-18 14:10:14.857  1034  1034 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-18 14:10:14.857  3895  3895 D A2dpService: Received stop request...Stopping profile...
08-18 14:10:14.858  3895  4068 D A2dpStateMachine: Exit Disconnected: -1
,08-18 14:10:14.859  3895  3895 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-18 14:10:14.862  3895  3975 D BluetoothAdapterState: Stopping profile services that were post enabled
08-18 14:10:14.862  3895  3895 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-18 14:10:14.862  3895  3895 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-18 14:10:14.862  3895  3895 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@278dbecc
08-18 14:10:14.862  1034  1034 D BluetoothA2dp: Proxy object disconnected
08-18 14:10:14.862  1034  1034 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-18 14:10:14.863  3895  3895 D HidService: Received stop request...Stopping profile...
08-18 14:10:14.863  3895  3895 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@278dbecc
08-18 14:10:14.865  3895  3895 D HeadsetStateMachine: Unbinding service...
08-18 14:10:14.865  6913  6913 D BluetoothInputDevice: Proxy object disconnected
08-18 14:10:14.866  6913  6913 D HidProfile: Bluetooth service disconnected
08-18 14:10:14.866  3895  3895 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-18 14:10:14.866  3895  3895 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-18 14:10:14.866  3895  3895 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-18 14:10:14.866  3895  3895 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-18 14:10:14.866  3895  3895 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-18 14:10:14.866  3895  3895 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-18 14:10:14.866  3895  3895 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
,08-18 14:10:14.868  3895  3895 D HealthService: Received stop request...Stopping profile...
08-18 14:10:14.868  3895  3895 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@278dbecc
08-18 14:10:14.871  3895  3895 D PanService: Received stop request...Stopping profile...
08-18 14:10:14.872  3895  3895 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@278dbecc
08-18 14:10:14.873  3895  3895 D BtGatt.DebugUtils: handleDebugAction() action=null
08-18 14:10:14.873  3895  3895 D BtGatt.GattService: Received stop request...Stopping profile...
08-18 14:10:14.873  3895  3895 D BtGatt.GattService: stop()
08-18 14:10:14.873  3895  3895 D BtGatt.AdvertiseManager: advertise clients cleared
08-18 14:10:14.875  6913  6913 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-18 14:10:14.875  6913  6913 D PanProfile: Bluetooth service disconnected
08-18 14:10:14.875  3895  3895 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@278dbecc
08-18 14:10:14.877  3895  3895 D BluetoothMapService: Received stop request...Stopping profile...
08-18 14:10:14.877  3895  3895 D BluetoothMapService: stop()
08-18 14:10:14.877  3895  3895 D BluetoothMapEmailAppObserver: deinitObservers()
08-18 14:10:14.878  3895  3895 D BluetoothMapEmailAppObserver: removeReceiver()
,08-18 14:10:14.879  3895  3895 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@278dbecc
08-18 14:10:14.880  6913  6913 D BluetoothMap: Proxy object disconnected
08-18 14:10:14.880  6913  6913 D MapProfile: Bluetooth service disconnected
08-18 14:10:14.881  3895  3895 I BluetoothA2dpServiceJni: cleanupNative
08-18 14:10:14.881  3895  4069 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-18 14:10:14.882  3895  3895 I GKI_LINUX: GKI_exit_task 2 done
,08-18 14:10:14.882  3895  3895 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-18 14:10:14.882  3895  3895 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-18 14:10:14.882  3895  3895 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-18 14:10:14.883  3895  3895 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-18 14:10:14.883  3895  3895 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-18 14:10:14.883  3895  3895 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-18 14:10:14.884  3895  3895 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-18 14:10:14.884  3895  3895 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-18 14:10:14.885  3895  3895 V BluetoothMapService: Handler(): got msg=4
08-18 14:10:14.885  3895  3895 D BluetoothMapService: MAP Service closeService in
08-18 14:10:14.885  3895  3895 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-18 14:10:14.885  3895  3895 V BluetoothMapService: MAP Service closeService out
08-18 14:10:14.886  3895  3975 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-18 14:10:14.886  3895  3975 D BluetoothAdapterProperties: Setting state to 10
08-18 14:10:14.886  3895  3975 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-18 14:10:14.886  3895  3895 D BluetoothMapService: cleanup()
08-18 14:10:14.886  3895  3895 D BluetoothMapService: MAP Service closeService in
08-18 14:10:14.886  3895  3895 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-18 14:10:14.886  3895  3895 V BluetoothMapService: MAP Service closeService out
08-18 14:10:14.887  1034  1101 D BluetoothManagerService: Message: 60
08-18 14:10:14.887  1034  1101 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-18 14:10:14.887  1034  1101 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-18 14:10:14.888  3895  3975 I BluetoothAdapterState: Entering OffState
08-18 14:10:14.888  6913  6933 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-18 14:10:14.889  1034  1101 D BluetoothHeadset: onBluetoothStateChange: up=false
08-18 14:10:14.889  1855  1870 D BluetoothHeadset: onBluetoothStateChange: up=false
08-18 14:10:14.890  1855  1871 D BluetoothHeadset: onBluetoothStateChange: up=false
08-18 14:10:14.890  1855  2482 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-18 14:10:14.891  6913  6932 D BluetoothPbap: onBluetoothStateChange: up=false
08-18 14:10:14.891  1034  1101 D BluetoothA2dp: onBluetoothStateChange: up=false
08-18 14:10:14.892  6913  6933 D BluetoothMap: onBluetoothStateChange: up=false
08-18 14:10:14.892  6913  6932 D BluetoothPan: onBluetoothStateChange on: false
08-18 14:10:14.893  1034  1101 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-18 14:10:14.893  1034  1101 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-18 14:10:14.896  1034  1101 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
,08-18 14:10:14.896  1034  1101 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-18 14:10:14.896  1034  1101 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@2b47355b mBinding = false
08-18 14:10:14.897  1034  1101 D BluetoothManagerService: Sending unbind request.
08-18 14:10:14.899  1034  1101 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-18 14:10:14.906  3895  3978 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-18 14:10:14.906  3895  3895 I GKI_LINUX: GKI_exit_task 1 done
08-18 14:10:14.906  3895  3895 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-18 14:10:14.907  3895  3895 I BluetoothServiceJni: cleanupNative: return from cleanup
08-18 14:10:14.907  3895  3895 I art     : --- WEIRD: removing null entry 246
08-18 14:10:14.908  3895  3895 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-18 14:10:14.908  3895  3895 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-18 14:10:14.908  6913  6913 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-18 14:10:14.909  6913  6913 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-18 14:10:14.909  6913  6913 D LGBluetoothEventManager: [BTUI] clear device connection state
08-18 14:10:14.910  6956  6956 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-18 14:10:14.911  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-18 14:10:14.912  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 14:10:14.913  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 14:10:14.913  6913  6913 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-18 14:10:14.916  1944  1944 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-18 14:10:14.917  1944  2130 D LGBluetoothAPIService: Message: 2
08-18 14:10:14.917  1944  2130 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@2e160d8f mBinding = false
08-18 14:10:14.917  1944  2130 D LGBluetoothAPIService: Sending unbind request.
08-18 14:10:14.918  3895  3895 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-18 14:10:14.919  1605  1605 D BluetoothAdapter: 176580471: getState() :  mService = null. Returning STATE_OFF
08-18 14:10:14.919  1605  1605 D BluetoothAdapter: 176580471: getState() :  mService = null. Returning STATE_OFF
08-18 14:10:14.921  3895  3895 I art     : System.exit called, status: 0
08-18 14:10:14.922  3895  3895 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-18 14:10:14.941   314  2149 V AudioFlinger: 3895 died, releasing its sessions
08-18 14:10:14.941   314  2149 V AudioFlinger:  pid 1855 @ 0
08-18 14:10:14.942   314  2149 V AudioFlinger:  pid 3466 @ 1
08-18 14:10:14.942   314  2149 V AudioFlinger:  pid 3466 @ 2
08-18 14:10:14.942  6913  6913 D DockEventReceiver: finishStartingService: stopping service
,08-18 14:10:14.943  6913  6913 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-18 14:10:14.951  6913  6913 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-18 14:10:14.951  6913  6913 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-18 14:10:14.996  1034  1623 I ActivityManager: Process com.android.bluetooth (pid 3895) has died
08-18 14:10:14.997  1034  1623 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,08-18 14:10:15.019  2161  2161 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-18 14:10:15.021  7024  7045 W FormManager: Network not available. Please check & try again.
,08-18 14:10:15.045  7024  7046 V FormManager: Network unavailable.
,08-18 14:10:15.054  7024  7046 V FormManager: Network unavailable.
08-18 14:10:15.066  6913  6913 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,08-18 14:10:15.067  6913  6913 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
,08-18 14:10:15.067  6913  6913 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-18 14:10:15.068  6913  6913 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-18 14:10:15.069  6913  6913 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-18 14:10:15.087  6913  6913 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-18 14:10:15.087  6913  6913 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-18 14:10:15.087  6913  6913 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-18 14:10:15.087  6913  6913 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-18 14:10:15.088  6913  6913 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-18 14:10:15.088  6913  6913 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-18 14:10:15.089  6913  6913 D BluetoothPermissionRequest: onReceive
,08-18 14:10:15.093  6913  6913 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-18 14:10:15.094  6913  6913 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-18 14:10:15.098  6913  6913 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-18 14:10:15.156  1034  2023 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7056 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-18 14:10:15.159  1034  2023 I ActivityManager: Killing 6087:com.android.contacts/u0a19 (adj 15): empty #17
08-18 14:10:15.264  1034  2054 W libprocessgroup: failed to open /acct/uid_10019/pid_6087/cgroup.procs: No such file or directory
,08-18 14:10:15.285  4340  4340 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-18 14:10:15.285  4340  4340 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-18 14:10:15.292  4340  4340 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-18 14:10:15.295  4340  4340 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-18 14:10:15.304  6956  6956 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-18 14:10:15.305  6956  6956 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-18 14:10:15.305  6956  6956 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-18 14:10:15.306  7056  7056 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-18 14:10:15.307  7056  7056 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-18 14:10:15.307  7056  7056 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-18 14:10:15.308  7056  7056 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-18 14:10:15.312  6913  6913 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-18 14:10:15.319  6913  6913 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-18 14:10:15.328  7056  7056 D BluetoothAdapterApp: Loading JNI Library
08-18 14:10:15.338  6984  6984 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-18 14:10:15.339  6984  6984 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-18 14:10:15.339  6984  6984 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,08-18 14:10:15.360  4340  7079 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-18 14:10:15.362  7056  7056 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@128d75d Instance Count = 1
08-18 14:10:15.369  7056  7056 D BluetoothAdapterApp: onCreate
,08-18 14:10:15.376  4340  7081 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-18 14:10:15.376  4340  7081 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-18 14:10:15.389  7024  7082 W FormManager: Network not available. Please check & try again.
08-18 14:10:15.392  7024  7083 V FormManager: Network unavailable.
08-18 14:10:15.394  7024  7083 V FormManager: Network unavailable.
08-18 14:10:15.403  6984  6984 D LgDataFeature: LgDataFeature() Constructor: none
,08-18 14:10:15.403  6984  6984 D LgDataFeature: LgDataFeature() Constructor Done, null
08-18 14:10:15.403  7056  7056 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-18 14:10:15.404  7056  7056 D ProfileConfigQcom: Adding HeadsetService
08-18 14:10:15.404  7056  7056 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-18 14:10:15.404  7056  7056 D ProfileConfigQcom: Adding A2dpService
08-18 14:10:15.404  7056  7056 D ProfileConfigQcom: [BTUI] HidService is supported
08-18 14:10:15.404  7056  7056 D ProfileConfigQcom: Adding HidService
08-18 14:10:15.405  7056  7056 D ProfileConfigQcom: [BTUI] HealthService is supported
08-18 14:10:15.405  7056  7056 D ProfileConfigQcom: Adding HealthService
08-18 14:10:15.405  7056  7056 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-18 14:10:15.406  7056  7056 D ProfileConfigQcom: [BTUI] PanService is supported
08-18 14:10:15.406  7056  7056 D ProfileConfigQcom: Adding PanService
08-18 14:10:15.406  7056  7056 D ProfileConfigQcom: [BTUI] GattService is supported
08-18 14:10:15.407  7056  7056 D ProfileConfigQcom: Adding GattService
08-18 14:10:15.407  7056  7056 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-18 14:10:15.407  7056  7056 D ProfileConfigQcom: Adding BluetoothMapService
08-18 14:10:15.407  7056  7056 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-18 14:10:15.409  7056  7056 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-18 14:10:15.411  6984  6984 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-18 14:10:15.413  6913  6913 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-18 14:10:15.413  6984  6984 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-18 14:10:15.413  6984  6984 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-18 14:10:15.413  6984  6984 V SoundPool: doLoad: loading sample sampleID=1
08-18 14:10:15.414  6984  6984 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-18 14:10:15.414  6984  7098 V SoundPool: Start decode
08-18 14:10:15.414  6984  7098 V MediaPlayer[Native]: decode(31, 10857164, 17813)
,08-18 14:10:15.415  7056  7056 V LGMDMManagerInternal: Create singleton instance
08-18 14:10:15.418   314  2148 V MediaPlayerService: decode(23, 10857164, 17813)
08-18 14:10:15.418   314  2148 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-18 14:10:15.418   314  2148 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-18 14:10:15.418   314  2148 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-18 14:10:15.418   314  2148 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-18 14:10:15.418   314  2148 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-18 14:10:15.418   314  2148 V MediaPlayerService: player type = 3
08-18 14:10:15.418   314  2148 V AwesomePlayer: AwesomePlayer create()
08-18 14:10:15.419   314  2148 V AwesomePlayer: reset_l() 
08-18 14:10:15.419   314  2148 V AwesomePlayer: cancelPlayerEvents
08-18 14:10:15.419   314  2148 V AwesomePlayer: setAudioSink() 
08-18 14:10:15.419   314  2148 V AwesomePlayer: reset_l() 
08-18 14:10:15.419  6711  6711 D UEI.SmartControl: QS Service created
08-18 14:10:15.419   314  2148 V AudioCache: notify(0xb5474bc0, 8, 0, 0)
08-18 14:10:15.419   314  2148 V AudioCache: ignored
08-18 14:10:15.419   314  2148 V AwesomePlayer: cancelPlayerEvents
08-18 14:10:15.419   314  2148 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-18 14:10:15.419   314  2148 V AwesomePlayer: setDataSource_l dataSource
08-18 14:10:15.419   314  2148 V LGParserOSAL: SniffLGParser start
08-18 14:10:15.419   314  2148 V LGParserOSAL: MainType:5, SubType=0
08-18 14:10:15.419   314  2148 V LGParserOSAL: #### check Mime : application/ogg
08-18 14:10:15.419   314  2148 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-18 14:10:15.419   314  2148 E MediaExtractor: Use LGExtractor :application/ogg 
08-18 14:10:15.426  6984  6984 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-18 14:10:15.430  6984  6984 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-18 14:10:15.430  6984  6984 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-18 14:10:15.435  6711  6711 I UEI.SmartControl: Service initServices...
08-18 14:10:15.435  6711  6711 D UEI.SmartControl: QS start get config
08-18 14:10:15.441  6984  6984 V LGMDMManager: Create singleton instance
08-18 14:10:15.472   314  2148 V LGParserOSAL: supported mime: application/ogg
08-18 14:10:15.472   314  2148 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-18 14:10:15.472   314  2148 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-18 14:10:15.472   314  2148 V AwesomePlayer: mBitrate = -1 bits/sec
08-18 14:10:15.472   314  2148 V AwesomePlayer: AudioTrack Setting
08-18 14:10:15.472   314  2148 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-18 14:10:15.472   314  2148 V AwesomePlayer: setAudioSource() 
08-18 14:10:15.472   314  2148 V MediaPlayerService: prepare
08-18 14:10:15.472   314  2148 V AwesomePlayer: prepareAsync_l() 
08-18 14:10:15.472   314  2148 V MediaPlayerService: wait for prepare
08-18 14:10:15.473   314  7099 V AwesomePlayer: onPrepareAsyncEvent() 
08-18 14:10:15.473   314  7099 V AwesomePlayer: initAudioDecoder() 
08-18 14:10:15.473   314  7099 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-18 14:10:15.473   314  7099 V AudioSystem: isOffloadSupported()
08-18 14:10:15.473   314  7099 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-18 14:10:15.473   314  7099 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-18 14:10:15.473   314  7099 I AudioFlinger: isAudioPlaybackHookOn() false
08-18 14:10:15.473   314  7099 V AwesomePlayer: getUseOffload() = 0 
08-18 14:10:15.473   314  7099 V OMXCodec: OMXCodec::Create
08-18 14:10:15.473   314  7099 V OMXCodec: findMatchingCodecs()
08-18 14:10:15.473   314  7099 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-18 14:10:15.473   314  7099 V OMXCodec: matchingCodecs.size()=1
08-18 14:10:15.473   314  7099 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,08-18 14:10:15.474   314  7099 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-18 14:10:15.474   314  7099 V LGCodecAdapter: LG Codec Adapter start
08-18 14:10:15.474   314  7099 V OMXCodec: OMXCodec Createtor
08-18 14:10:15.474   314  7099 V OMXCodec: setComponentRole
08-18 14:10:15.474   314  7099 V OMXCodec: configureCodec protected=0
08-18 14:10:15.474   314  7099 V LGCodecAdapter: called getLGCodecSpecificData
08-18 14:10:15.474   314  7099 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-18 14:10:15.474   314  7099 V LGCodecOSAL: Called LGconfigureCodecMETA
08-18 14:10:15.474   314  7099 V LGCodecOSAL: Called LGconfigureCodecMSG
08-18 14:10:15.474   314  7099 V LGCodecOSAL: Not support LGCodec
08-18 14:10:15.474   314  7099 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-18 14:10:15.474   314  7099 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-18 14:10:15.474   314  7099 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-18 14:10:15.474   314  7099 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-18 14:10:15.474   314  7099 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-18 14:10:15.474   314  7099 V AudioSystem: isOffloadSupported()
08-18 14:10:15.474   314  7099 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-18 14:10:15.474   314  7099 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-18 14:10:15.474   314  7099 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-18 14:10:15.474   314  7099 V OMXCodec: init()
08-18 14:10:15.474   314  7099 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-18 14:10:15.474   314  7099 V OMXCodec: allocateBuffers
08-18 14:10:15.474   314  7099 V OMXCodec: allocateBuffersOnPort portIndex=0
08-18 14:10:15.474   314  7099 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-18 14:10:15.475   314  7099 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on input port
08-18 14:10:15.475   314  7099 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on input port
08-18 14:10:15.475   314  7099 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on input port
08-18 14:10:15.475   314  7099 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on input port
08-18 14:10:15.475   314  7099 V OMXCodec: allocateBuffersOnPort portIndex=1
08-18 14:10:15.475   314  7099 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-18 14:10:15.475   314  7099 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57c10b0 on output port
08-18 14:10:15.475   314  7099 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57c12e0 on output port
08-18 14:10:15.475   314  7099 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57c14c0 on output port
08-18 14:10:15.475   314  7099 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57c1650 on output port
08-18 14:10:15.475   314  7099 V OMXCodec: init() mAsyncCompletion wait!!! 
08-18 14:10:15.477   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
,08-18 14:10:15.477   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-18 14:10:15.477   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-18 14:10:15.477   314  7099 V OMXCodec: init() mAsyncCompletion wait!!! 
08-18 14:10:15.477   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-18 14:10:15.477   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-18 14:10:15.477   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-18 14:10:15.477   314  7099 V OMXCodec: init() mAsyncCompletion wait free! 
08-18 14:10:15.477   314  7099 V AwesomePlayer: finishAsyncPrepare_l() 
08-18 14:10:15.477   314  7099 V AudioCache: notify(0xb5474bc0, 5, 0, 0)
08-18 14:10:15.477   314  7099 V AudioCache: ignored
08-18 14:10:15.477   314  7099 V AudioCache: notify(0xb5474bc0, 1, 0, 0)
08-18 14:10:15.477   314  7099 V AudioCache: prepared
08-18 14:10:15.477   314  2148 V AudioCache: wait - success
08-18 14:10:15.477   314  2148 V MediaPlayerService: start
08-18 14:10:15.477   314  2148 V AwesomePlayer: play_l() 
08-18 14:10:15.478   314  2148 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-18 14:10:15.478   314  2148 V AwesomePlayer: createAudioPlayer_l
08-18 14:10:15.478   314  2148 V AwesomePlayer: seekAudioIfNecessary_l() 
08-18 14:10:15.478   314  2148 V AwesomePlayer: startAudioPlayer_l() 
,08-18 14:10:15.478   314  2148 D AudioPlayer: start of Playback, useOffload 0
08-18 14:10:15.478   314  2148 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-18 14:10:15.478   314  2148 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-18 14:10:15.486   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-18 14:10:15.486   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-18 14:10:15.486   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-18 14:10:15.486   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-18 14:10:15.486   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-18 14:10:15.486   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-18 14:10:15.486   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044806832
08-18 14:10:15.486   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-18 14:10:15.486   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044807392
08-18 14:10:15.486   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-18 14:10:15.486   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044807872
,08-18 14:10:15.486   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-18 14:10:15.486   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044808272
08-18 14:10:15.486   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-18 14:10:15.486   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-18 14:10:15.486   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-18 14:10:15.486   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-18 14:10:15.486   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-18 14:10:15.486   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-18 14:10:15.487   314  7101 V OMXCodec: allocateBuffersOnPort portIndex=1
08-18 14:10:15.487   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-18 14:10:15.487   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57c14c0 on output port
08-18 14:10:15.487   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57c12e0 on output port
08-18 14:10:15.487   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57c10b0 on output port
08-18 14:10:15.487   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57c1790 on output port
08-18 14:10:15.487   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-18 14:10:15.487   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-18 14:10:15.487   314  2148 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-18 14:10:15.488   314  2148 V AudioCache: notify(0xb5474bc0, 6, 0, 0)
08-18 14:10:15.488   314  2148 V AudioCache: ignored
08-18 14:10:15.488   314  2148 V MediaPlayerService: wait for playback complete
08-18 14:10:15.489   314  7102 V AudioCache: write(0xb16ae000, 4096)
08-18 14:10:15.489   314  7102 V AudioCache: memcpy(0xaf006000, 0xb16ae000, 4096)
08-18 14:10:15.493   314  7102 V AudioCache: write(0xb16ae000, 4096)
08-18 14:10:15.493   314  7102 V AudioCache: memcpy(0xaf007000, 0xb16ae000, 4096)
08-18 14:10:15.494   314  7102 V AudioCache: write(0xb16ae000, 4096)
08-18 14:10:15.494   314  7102 V AudioCache: memcpy(0xaf008000, 0xb16ae000, 4096)
08-18 14:10:15.494   314  7102 V AudioCache: write(0xb16ae000, 4096)
08-18 14:10:15.494   314  7102 V AudioCache: memcpy(0xaf009000, 0xb16ae000, 4096)
08-18 14:10:15.494   314  7102 V AudioCache: write(0xb16ae000, 4096)
08-18 14:10:15.494   314  7102 V AudioCache: memcpy(0xaf00a000, 0xb16ae000, 4096)
08-18 14:10:15.494   314  7102 V AudioCache: write(0xb16ae000, 4096)
08-18 14:10:15.494   314  7102 V AudioCache: memcpy(0xaf00b000, 0xb16ae000, 4096)
08-18 14:10:15.494   314  7102 V AudioCache: write(0xb16ae000, 4096)
08-18 14:10:15.494   314  7102 V AudioCache: memcpy(0xaf00c000, 0xb16ae000, 4096)
08-18 14:10:15.495  7056  7056 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-18 14:10:15.496   314  7102 V AudioCache: write(0xb16ae000, 4096)
08-18 14:10:15.496   314  7102 V AudioCache: memcpy(0xaf00d000, 0xb16ae000, 4096)
08-18 14:10:15.496   314  7102 V AudioCache: write(0xb16ae000, 4096)
08-18 14:10:15.496   314  7102 V AudioCache: memcpy(0xaf00e000, 0xb16ae000, 4096)
08-18 14:10:15.497   314  7102 V AudioCache: write(0xb16ae000, 4096)
08-18 14:10:15.497   314  7102 V AudioCache: memcpy(0xaf00f000, 0xb16ae000, 4096)
08-18 14:10:15.497  6984  6984 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-18 14:10:15.498   314  7102 V AudioCache: write(0xb16ae000, 4096)
08-18 14:10:15.498   314  7102 V AudioCache: memcpy(0xaf010000, 0xb16ae000, 4096)
08-18 14:10:15.498  6984  6984 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-18 14:10:15.498   314  7102 V AudioC,ache: write(0xb16ae000, 4096)
08-18 14:10:15.498   314  7102 V AudioCache: memcpy(0xaf011000, 0xb16ae000, 4096)
08-18 14:10:15.498  7056  7056 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-18 14:10:15.499   314  7102 V AudioCache: write(0xb16ae000, 4096)
08-18 14:10:15.499   314  7102 V AudioCache: memcpy(0xaf012000, 0xb16ae000, 4096)
08-18 14:10:15.499  7056  7056 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-18 14:10:15.499  7056  7056 V BluetoothSapReceiver: SapReceiver onReceive 
08-18 14:10:15.499  6984  6984 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:5002
08-18 14:10:15.499   314  7102 V AudioCache: write(0xb16ae000, 4096)
08-18 14:10:15.499   314  7102 V AudioCache: memcpy(0xaf013000, 0xb16ae000, 4096)
08-18 14:10:15.500   314  7102 V AudioCache: write(0xb16ae000, 4096)
,08-18 14:10:15.500   314  7102 V AudioCache: memcpy(0xaf014000, 0xb16ae000, 4096)
,08-18 14:10:15.500   314  7102 V AudioCache: write(0xb16ae000, 4096)
08-18 14:10:15.500   314  7102 V AudioCache: memcpy(0xaf015000, 0xb16ae000, 4096)
08-18 14:10:15.500  7056  7056 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-18 14:10:15.501  7056  7056 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-18 14:10:15.501   314  7102 V AudioCache: write(0xb16ae000, 4096)
,08-18 14:10:15.501   314  7102 V AudioCache: memcpy(0xaf016000, 0xb16ae000, 4096)
08-18 14:10:15.501   314  7102 V AudioCache: write(0xb16ae000, 4096)
08-18 14:10:15.501   314  7102 V AudioCache: memcpy(0xaf017000, 0xb16ae000, 4096)
08-18 14:10:15.502   314  7102 V AudioCache: write(0xb16ae000, 4096)
08-18 14:10:15.502   314  7102 V AudioCache: memcpy(0xaf018000, 0xb16ae000, 4096)
08-18 14:10:15.502   314  7102 V AudioCache: write(0xb16ae000, 4096)
,08-18 14:10:15.503   314  7102 V AudioCache: memcpy(0xaf019000, 0xb16ae000, 4096)
08-18 14:10:15.503   314  7102 V AudioCache: write(0xb16ae000, 4096)
08-18 14:10:15.503   314  7102 V AudioCache: memcpy(0xaf01a000, 0xb16ae000, 4096)
08-18 14:10:15.504   314  7102 V AudioCache: write(0xb16ae000, 4096)
08-18 14:10:15.504   314  7102 V AudioCache: memcpy(0xaf01b000, 0xb16ae000, 4096)
,08-18 14:10:15.505   314  7102 V AudioCache: write(0xb16ae000, 4096)
08-18 14:10:15.505   314  7102 V AudioCache: memcpy(0xaf01c000, 0xb16ae000, 4096)
08-18 14:10:15.506   314  7102 V AudioCache: write(0xb16ae000, 4096)
08-18 14:10:15.506   314  7102 V AudioCache: memcpy(0xaf01d000, 0xb16ae000, 4096)
08-18 14:10:15.506   314  7102 V AudioCache: write(0xb16ae000, 4096)
,08-18 14:10:15.506   314  7102 V AudioCache: memcpy(0xaf01e000, 0xb16ae000, 4096)
08-18 14:10:15.507   314  7102 V AudioCache: write(0xb16ae000, 4096)
08-18 14:10:15.507   314  7102 V AudioCache: memcpy(0xaf01f000, 0xb16ae000, 4096)
08-18 14:10:15.507   314  7102 V AudioCache: write(0xb16ae000, 4096)
08-18 14:10:15.507   314  7102 V AudioCache: memcpy(0xaf020000, 0xb16ae000, 4096)
08-18 14:10:15.507   314  7102 V AudioCache: write(0xb16ae000, 4096)
,08-18 14:10:15.507   314  7102 V AudioCache: memcpy(0xaf021000, 0xb16ae000, 4096)
08-18 14:10:15.508   314  7102 V AudioCache: write(0xb16ae000, 4096)
08-18 14:10:15.508   314  7102 V AudioCache: memcpy(0xaf022000, 0xb16ae000, 4096)
08-18 14:10:15.508   314  7102 V AudioCache: write(0xb16ae000, 4096)
,08-18 14:10:15.508   314  7102 V AudioCache: memcpy(0xaf023000, 0xb16ae000, 4096)
08-18 14:10:15.509  7001  7001 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-18 14:10:15.509   314  7102 V AudioCache: write(0xb16ae000, 4096)
08-18 14:10:15.509   314  7102 V AudioCache: memcpy(0xaf024000, 0xb16ae000, 4096)
08-18 14:10:15.509   314  7102 V AudioCache: write(0xb16ae000, 4096)
,08-18 14:10:15.509   314  7102 V AudioCache: memcpy(0xaf025000, 0xb16ae000, 4096)
08-18 14:10:15.509   314  7102 V AudioCache: write(0xb16ae000, 4096)
08-18 14:10:15.510   314  7102 V AudioCache: memcpy(0xaf026000, 0xb16ae000, 4096)
08-18 14:10:15.510   314  7102 V AudioCache: write(0xb16ae000, 4096)
,08-18 14:10:15.510   314  7102 V AudioCache: memcpy(0xaf027000, 0xb16ae000, 4096)
08-18 14:10:15.510   314  7102 V AudioCache: write(0xb16ae000, 4096)
08-18 14:10:15.510   314  7102 V AudioCache: memcpy(0xaf028000, 0xb16ae000, 4096)
08-18 14:10:15.511   314  7102 V AudioCache: write(0xb16ae000, 4096)
,08-18 14:10:15.511   314  7102 V AudioCache: memcpy(0xaf029000, 0xb16ae000, 4096)
08-18 14:10:15.511   314  7102 V AudioCache: write(0xb16ae000, 4096)
08-18 14:10:15.511   314  7102 V AudioCache: memcpy(0xaf02a000, 0xb16ae000, 4096)
08-18 14:10:15.512   314  7102 V AudioCache: write(0xb16ae000, 4096)
,08-18 14:10:15.512   314  7102 V AudioCache: memcpy(0xaf02b000, 0xb16ae000, 4096)
08-18 14:10:15.512   314  7102 V AudioCache: write(0xb16ae000, 4096)
08-18 14:10:15.512   314  7102 V AudioCache: memcpy(0xaf02c000, 0xb16ae000, 4096)
08-18 14:10:15.512   314  7102 V AudioCache: write(0xb16ae000, 4096)
08-18 14:10:15.512   314  7102 V AudioCache: memcpy(0xaf02d000, 0xb16ae000, 4096)
,08-18 14:10:15.513   314  7102 V AudioCache: write(0xb16ae000, 4096)
08-18 14:10:15.513   314  7102 V AudioCache: memcpy(0xaf02e000, 0xb16ae000, 4096)
08-18 14:10:15.513   314  7102 V AudioCache: write(0xb16ae000, 4096)
08-18 14:10:15.513   314  7102 V AudioCache: memcpy(0xaf02f000, 0xb16ae000, 4096)
,08-18 14:10:15.514   314  7102 V AudioCache: write(0xb16ae000, 4096)
08-18 14:10:15.514   314  7102 V AudioCache: memcpy(0xaf030000, 0xb16ae000, 4096)
08-18 14:10:15.514   314  7102 V AudioCache: write(0xb16ae000, 4096)
08-18 14:10:15.514   314  7102 V AudioCache: memcpy(0xaf031000, 0xb16ae000, 4096)
,08-18 14:10:15.514   314  7102 V AudioCache: write(0xb16ae000, 4096)
08-18 14:10:15.514   314  7102 V AudioCache: memcpy(0xaf032000, 0xb16ae000, 4096)
08-18 14:10:15.515   314  7102 V AudioCache: write(0xb16ae000, 4096)
08-18 14:10:15.515   314  7102 V AudioCache: memcpy(0xaf033000, 0xb16ae000, 4096)
,08-18 14:10:15.515   314  7102 V AudioCache: write(0xb16ae000, 4096)
08-18 14:10:15.515   314  7102 V AudioCache: memcpy(0xaf034000, 0xb16ae000, 4096)
08-18 14:10:15.515   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-18 14:10:15.515   314  7102 V AudioCache: write(0xb16ae000, 4096)
08-18 14:10:15.515   314  7102 V AudioCache: memcpy(0xaf035000, 0xb16ae000, 4096)
08-18 14:10:15.515   314  7102 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-18 14:10:15.515   314  7102 V AudioCache: write(0xb16ae000, 4096)
08-18 14:10:15.515   314  7102 V AudioCache: memcpy(0xaf036000, 0xb16ae000, 4096)
08-18 14:10:15.515   314  7102 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-18 14:10:15.515   314  7102 V AudioCache: write(0xb16ae000, 4096)
08-18 14:10:15.515   314  7102 V AudioCache: memcpy(0xaf037000, 0xb16ae000, 4096)
,08-18 14:10:15.515   314  7102 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-18 14:10:15.515   314  7102 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-18 14:10:15.515   314  7102 V AwesomePlayer: postAudioEOS() 
08-18 14:10:15.515   314  7102 V AudioCache: write(0xb16ae000, 280)
08-18 14:10:15.515   314  7102 V AudioCache: memcpy(0xaf038000, 0xb16ae000, 280)
08-18 14:10:15.519   314  7099 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-18 14:10:15.519   314  7099 V AwesomePlayer: onStreamDone
08-18 14:10:15.519   314  7099 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-18 14:10:15.519   314  7099 V AudioCache: notify(0xb5474bc0, 2, 0, 0)
08-18 14:10:15.519   314  7099 V AudioCache: playback complete
08-18 14:10:15.519   314  7099 V AwesomePlayer: pause_l() 
,08-18 14:10:15.519   314  2148 V AudioCache: wait - success
08-18 14:10:15.519   314  7099 V AudioCache: notify(0xb5474bc0, 7, 0, 0)
08-18 14:10:15.519   314  7099 V AudioCache: ignored
08-18 14:10:15.519   314  2148 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-18 14:10:15.519   314  7099 V AwesomePlayer: cancelPlayerEvents
08-18 14:10:15.519   314  7099 D AudioPlayer: Pause Playback at 1068125
08-18 14:10:15.519   314  2148 V AwesomePlayer: reset_l() 
08-18 14:10:15.519   314  2148 V AudioCache: notify(0xb5474bc0, 8, 0, 0)
08-18 14:10:15.519   314  2148 V AudioCache: ignored
08-18 14:10:15.519   314  2148 V AwesomePlayer: cancelPlayerEvents
08-18 14:10:15.519   314  2148 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-18 14:10:15.519   314  2148 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
,08-18 14:10:15.519   314  2148 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-18 14:10:15.519   314  2148 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-18 14:10:15.519   314  2148 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-18 14:10:15.519   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-18 14:10:15.519   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-18 14:10:15.519   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-18 14:10:15.519   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c90 on port 0
08-18 14:10:15.519   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-18 14:10:15.519   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 0
08-18 14:10:15.519   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-18 14:10:15.520   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 0
,08-18 14:10:15.520   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1,
08-18 14:10:15.520   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 0
08-18 14:10:15.520   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-18 14:10:15.520   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-18 14:10:15.520   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57c1790 on port 1
08-18 14:10:15.520   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-18 14:10:15.520   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57c10b0 on port 1
08-18 14:10:15.520   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-18 14:10:15.520   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57c12e0 on port 1
08-18 14:10:15.520   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-18 14:10:15.520   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57c14c0 on port 1
08-18 14:10:15.520   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
,08-18 14:10:15.520   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-18 14:10:15.520   314  2148 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-18 14:10:15.520   314  2148 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-18 14:10:15.520   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-18 14:10:15.520   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-18 14:10:15.520   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-18 14:10:15.520   314  2148 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-18 14:10:15.520   314  2148 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-18 14:10:15.520   314  2148 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-18 14:10:15.521   314  2148 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-18 14:10:15.521   314  2148 D AudioPlayer: AudioPlayer releasing audio source
08-18 14:10:15.521   314  2148 D AudioPlayer: AudioPlayer done releasing audio source
,08-18 14:10:15.521   314  2148 V AwesomePlayer: reset_l() 
08-18 14:10:15.521   314  2148 V AwesomePlayer: cancelPlayerEvents
08-18 14:10:15.521   314  2148 V AwesomePlayer: ~AwesomePlayer call
08-18 14:10:15.521   314  2148 V AwesomePlayer: reset_l() 
08-18 14:10:15.521   314  2148 V AwesomePlayer: cancelPlayerEvents
08-18 14:10:15.521  6984  7098 V SoundPool: close(31)
08-18 14:10:15.521  6984  7098 V SoundPool: pointer = 0x9fe60000, size = 205080, sampleRate = 48000, numChannels = 2
08-18 14:10:15.708  6711  6711 I UEI.SmartControl: Supports setup maps: true
08-18 14:10:15.711  6711  6711 D UEI.SmartControl: QS start statue = true Error code = 0
08-18 14:10:15.711  6711  6711 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-18 14:10:15.711  6711  6711 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-18 14:10:15.711  6711  6711 I UEI.SmartControl: ### init IR Blaster...
,08-18 14:10:15.714  6711  6711 D serial_port: Configuring serial port
08-18 14:10:15.714  6711  6711 E UEI.SmartControl: UEIBLaster setting for 616
08-18 14:10:15.714  6711  6711 I UEI.SmartControl: Setting serial record hearder size = 2
08-18 14:10:15.714  6711  6711 I UEI.SmartControl: configuring settings for MAXQ616
08-18 14:10:15.714  6711  6711 I UEI.SmartControl: Get version...
08-18 14:10:15.731  6711  7105 D UEI.SmartControl: serial port data available: 21
,08-18 14:10:15.756  6711  6711 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-18 14:10:15.756  6711  6711 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-18 14:10:15.756  6711  6711 I UEI.SmartControl: QS saving settings...
,08-18 14:10:15.757  6711  6711 D UEI.SmartControl: IR Blaster version: 25672567
,08-18 14:10:15.773  6711  7105 D UEI.SmartControl: serial port data available: 4
,08-18 14:10:15.804  6711  7111 I UEI.SmartControl: Device manager: loading config....
08-18 14:10:15.805  6711  7111 D UEI.SmartControl: ----------- loading internal config...
08-18 14:10:15.806  6711  6711 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-18 14:10:15.811  6711  6711 E UEI.SmartControl: Services init done
08-18 14:10:15.811  6711  6711 D UEI.SmartControl: QS Service init finished
08-18 14:10:15.813  6711  6711 D UEI.SmartControl: QS Service version name: 2.1.91
08-18 14:10:15.813  6711  6711 D UEI.SmartControl: QS Service version code: 201091
08-18 14:10:15.815  6711  6711 D UEI.SmartControl: Service requested: Control
08-18 14:10:15.817  6711  7111 E UEI.SmartControl: Loading SETTINGS...
08-18 14:10:15.821  6711  6711 D UEI.SmartControl: Request IControl service: devices are loaded...
,08-18 14:10:15.824  6711  6711 D UEI.SmartControl: Internal service binding...
08-18 14:10:15.825  6984  6984 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-18 14:10:15.827  6711  7111 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-18 14:10:15.828  6711  6726 I UEI.SmartControl: ------ IControl API: 11
08-18 14:10:15.828  6711  6726 D UEI.SmartControl: File observer start...
08-18 14:10:15.829  6711  6726 E UEI.SmartControl: IR Port is disabled: false
08-18 14:10:15.830  6711  6726 D UEI.SmartControl: Starting file observer...
,08-18 14:10:15.834  6711  6726 I UEI.SmartControl: Registering callback...
08-18 14:10:15.835  6711  6727 I UEI.SmartControl: ------ IControl API: 19
08-18 14:10:15.837  6711  6727 I UEI.SmartControl: Registering Services Ready callback...
08-18 14:10:15.837  6711  6727 I UEI.SmartControl: Notify client services are ready...
08-18 14:10:15.838  6984  6999 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-18 14:10:15.839  6984  7096 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-18 14:10:15.839  6984  7096 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-18 14:10:15.840  6984  6984 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-18 14:10:15.841  6984  6984 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-18 14:10:15.841  6711  6760 I UEI.SmartControl: ------ IControl API: 8
08-18 14:10:15.842  6711  7110 I UEI.SmartControl: Notify AllClients services are ready: 0
08-18 14:10:15.842  6711  7110 D UEI.SmartControl: -----service ready thread exits
08-18 14:10:15.842  6984  7000 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-18 14:10:15.842  6984  7096 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-18 14:10:15.843  6984  7096 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-18 14:10:15.844  6984  6984 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-18 14:10:15.845  6984  6984 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-18 14:10:15.845  6984  6984 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-18 14:10:15.846  6984  6984 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
,08-18 14:10:15.848  6984  6984 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-18 14:10:15.849  6984  6984 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-18 14:10:15.850  6984  6984 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-18 14:10:15.857  6984  6984 D QRemote : [RemoteControlManager.java:327:handleMessage()] oooooo 140510:retrieveDevices already complete. Do nothing
08-18 14:10:15.858  6984  6984 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,08-18 14:10:15.858  6984  6984 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-18 14:10:15.859  6984  6984 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-18 14:10:15.860  6984  6984 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-18 14:10:15.860  6984  6984 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-18 14:10:15.861  6984  6984 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-18 14:10:15.862  6984  6984 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-18 14:10:15.863  6984  6984 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1471522215863]
08-18 14:10:15.866  6984  6984 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-18 14:10:15.868  1034  2013 I ActivityManager: Killing 6113:com.android.gallery3d/u0a27 (adj 15): empty #17
08-18 14:10:15.897  6984  7113 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-18 14:10:15.917  1034  2013 I ActivityManager: Killing 6598:com.lge.email/u0a23 (adj 15): empty #18
,08-18 14:10:15.969  1034  1622 W libprocessgroup: failed to open /acct/uid_10027/pid_6113/cgroup.procs: No such file or directory
,08-18 14:10:15.987  1034  1623 W libprocessgroup: failed to open /acct/uid_10023/pid_6598/cgroup.procs: No such file or directory
,08-18 14:10:15.988  6984  6984 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-18 14:10:15.992  6984  6984 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-18 14:10:15.994  6984  6984 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-18 14:10:15.995  6984  6984 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
,08-18 14:10:15.996  6984  6984 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-18 14:10:15.997  6984  6984 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-18 14:10:15.999  6984  6984 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-18 14:10:16.014  6984  6984 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-18 14:10:16.667  1034  1051 D WifiServiceImplEx: setWifiEnabled: true pid=6817, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-18 14:10:16.668  1034  1051 D WifiService: setWifiEnabled: true pid=6817, uid=10118
08-18 14:10:16.668  1034  1051 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-18 14:10:16.676   304   304 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x6 conn_h=0xb6403090
08-18 14:10:16.676   304   304 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
08-18 14:10:16.676   304   304 I rmt_storage: wakelock acquired: 1, error no: 42
08-18 14:10:16.677   304   913 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
,08-18 14:10:16.719  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-18 14:10:16.719  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-18 14:10:16.719  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-18 14:10:16.721  1034  1540 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-18 14:10:16.721  1034  1540 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-18 14:10:16.724  1034  1540 E WifiUtil: wfc_util_ffile_check_copy(): pid[1034] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-18 14:10:16.724  1034  1540 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-18 14:10:16.724  1034  1540 E WifiUtil: wfc_util_ffile_check_copy(): pid[1034] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-18 14:10:16.724  1034  1540 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-18 14:10:16.724  1034  1540 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-18 14:10:16.724  1034  1540 E WifiHW  : unknown target_country: EU , set to default
08-18 14:10:16.724  1034  1540 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-18 14:10:16.724  1034  1540 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-18 14:10:16.724  1034  1540 I WifiUtil: gEnableBmps=1
08-18 14:10:16.786   304   913 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 1572864
08-18 14:10:16.786   304   913 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
08-18 14:10:16.786   304   913 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 22
08-18 14:10:16.786   304   913 I rmt_storage: 
,08-18 14:10:16.791   304   304 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x0x6 conn_h=0x0xb6403090
08-18 14:10:16.791   891   908 E Diag_Lib: [IMS_FATAL]| 3347 | 908 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
08-18 14:10:16.793  1034  1547 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-18 14:10:16.797  1034  1101 D Tethering: MasterInitialState.processMessage what=3
08-18 14:10:16.805  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-18 14:10:16.809  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 14:10:16.810  1034  1547 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-18 14:10:16.815  1034  1101 D Tethering: MasterInitialState.processMessage what=3
08-18 14:10:16.817  1034  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-18 14:10:16.824  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-18 14:10:16.827  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 14:10:16.828  6505  6505 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-18 14:10:16.831  6505  6955 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-18 14:10:16.847  5802  5802 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-18 14:10:16.855  5802  5802 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-18 14:10:16.884  1034  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-18 14:10:16.892  2161  2161 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-18 14:10:16.892  1034  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-18 14:10:16.893  1034  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-18 14:10:16.954  1034  2035 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7137 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-18 14:10:17.055  7137  7137 I AppUp4:AppBoxCP: onCreate
,08-18 14:10:17.056  7137  7137 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,08-18 14:10:17.067  7137  7137 I AppUp4:DB:  setFingerPrint start
,08-18 14:10:17.068  7137  7137 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-18 14:10:17.077  7137  7137 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-18 14:10:17.077  7137  7137 I AppUp4:DB:  SDK version = 21
08-18 14:10:17.077  7137  7137 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-18 14:10:17.079  7137  7137 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
,08-18 14:10:17.080  7137  7137 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-18 14:10:17.081  7137  7137 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-18 14:10:17.083  7137  7137 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-18 14:10:17.083  7137  7137 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-18 14:10:17.091  7137  7137 I AppUp4:CustModeStarterReceiver: onReceive
,08-18 14:10:17.136  7137  7137 D LgDataFeature: LgDataFeature() Constructor: none
,08-18 14:10:17.136  7137  7137 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-18 14:10:17.145  7137  7137 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@3ef530ff
,08-18 14:10:17.145  7137  7137 D AppUp4:CustFacade: isCustomizationCompleted : false
08-18 14:10:17.145  7137  7137 D AppUp4:CustFacade: isPhone : true
,08-18 14:10:17.146  7137  7137 D AppUp4:CustModeStarterReceiver: begin check event
08-18 14:10:17.147  7137  7137 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-18 14:10:17.147  7137  7137 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-18 14:10:17.148  7137  7156 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-18 14:10:17.149  7137  7156 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-18 14:10:17.149  7137  7156 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-18 14:10:17.151  1034  1971 I ActivityManager: Killing 6633:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,08-18 14:10:17.218  1034  1989 W libprocessgroup: failed to open /acct/uid_10061/pid_6633/cgroup.procs: No such file or directory
,08-18 14:10:17.220  4340  4340 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-18 14:10:17.220  4340  4340 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-18 14:10:17.222  4340  4340 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-18 14:10:17.239  4340  4340 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-18 14:10:17.256  4340  7170 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-18 14:10:17.267  4340  7171 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-18 14:10:17.268  4340  7171 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-18 14:10:17.291  1034  1935 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7172 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-18 14:10:17.359  7172  7172 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-18 14:10:17.359  7172  7172 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-18 14:10:17.361  7172  7172 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-18 14:10:17.361  7172  7172 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-18 14:10:17.406  1034  1101 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-18 14:10:17.406  1034  1101 D Tethering: InitialState.processMessage what=4
,08-18 14:10:17.415  1034  1101 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-18 14:10:17.420   309   903 D SoftapController: Softap fwReload - Ok
08-18 14:10:17.423  1034  1540 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (691ms)
08-18 14:10:17.429   309   903 D CommandListener: Setting iface cfg
08-18 14:10:17.429   309   903 D CommandListener: Trying to bring down wlan0
,08-18 14:10:17.430   309   903 D CommandListener: Clearing all IP addresses on wlan0
08-18 14:10:17.432  1034  1540 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-18 14:10:17.436  1034  1540 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-18 14:10:17.436  1034  1540 E WifiStateMachine: useWiFiOffloading() : false
08-18 14:10:17.436  1034  1540 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-18 14:10:17.434  7196  7196 W wpa_supplicant: type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-18 14:10:17.434  7196  7196 W wpa_supplicant: type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-18 14:10:17.439  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-18 14:10:17.441  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-18 14:10:17.442  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 14:10:17.443  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 14:10:17.444  1034  1540 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-18 14:10:17.444  1034  1540 D WifiMonitor: connecting to supplicant
,08-18 14:10:17.449  1944  1944 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-18 14:10:17.462  7196  7196 I wpa_supplicant: Successfully initialized wpa_supplicant
08-18 14:10:17.486  7172  7172 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-18 14:10:17.491  7196  7196 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-18 14:10:17.492  7196  7196 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
08-18 14:10:17.503  7172  7172 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-18 14:10:17.541  7172  7172 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-18 14:10:17.559  7196  7196 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-18 14:10:17.584  7172  7172 D LgDataFeature: LgDataFeature() Constructor: none
08-18 14:10:17.584  7172  7172 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-18 14:10:17.599  7196  7196 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-18 14:10:17.606  1034  1540 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
,08-18 14:10:17.607  1034  1540 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
,08-18 14:10:17.607  1034  1540 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-18 14:10:17.608  1034  1540 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
,08-18 14:10:17.608  1034  1540 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-18 14:10:17.609  1034  1540 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-18 14:10:17.609  1034  1540 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
,08-18 14:10:17.610  1034  1540 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-18 14:10:17.610  1034  1540 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
,08-18 14:10:17.610  1034  1540 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-18 14:10:17.611  1034  1540 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-18 14:10:17.611  1034  1540 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-18 14:10:17.611  1034  1540 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-18 14:10:17.612  1034  1540 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-18 14:10:17.612  1034  1540 E WifiStateMachine: useWiFiOffloading() : false
08-18 14:10:17.612  1034  1540 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-18 14:10:17.612  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-18 14:10:17.613  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-18 14:10:17.613  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-18 14:10:17.613  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-18 14:10:17.613  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-18 14:10:17.613  1034  1540 D WifiNative-wlan0: doBoolean: SET update_config 1
,08-18 14:10:17.613  7196  7196 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-18 14:10:17.614  1034  1540 D WifiNative-wlan0: SET update_config 1: returned true
08-18 14:10:17.614  1034  1540 D WifiConfigStore: Loading config and enabling all networks 
,08-18 14:10:17.614  1034  1540 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-18 14:10:17.615  1034  1540 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any,	
08-18 14:10:17.615  1944  1944 D WfdService: Waiting for WifiP2p enabling
08-18 14:10:17.615  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-18 14:10:17.617  7196  7196 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-18 14:10:17.618  6817  6817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-18 14:10:17.618  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-18 14:10:17.618  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 14:10:17.618  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-18 14:10:17.618  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 14:10:17.618  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-18 14:10:17.618  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-18 14:10:17.618  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-18 14:10:17.618  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-18 14:10:17.618  6817  6817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-18 14:10:17.618  6817  6817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-18 14:10:17.619  1034  7205 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
,08-18 14:10:17.619  6817  6817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-18 14:10:17.619  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-18 14:10:17.619  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 14:10:17.619  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
,08-18 14:10:17.619  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 14:10:17.619  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-18 14:10:17.619  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-18 14:10:17.619  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-18 14:10:17.619  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-18 14:10:17.619  6817  6817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
08-18 14:10:17.619  6817  6817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-18 14:10:17.619  1034  7205 D WifiMonitor: Dropping event because (p2p0) is stopped
08-18 14:10:17.620  1034  7205 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
,08-18 14:10:17.620  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-18 14:10:17.620  1034  1545 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-18 14:10:17.620  1034  7205 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
,08-18 14:10:17.622  1034  7205 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-18 14:10:17.623  1034  1540 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-18 14:10:17.623  1034  7205 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
,08-18 14:10:17.623  1034  7205 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-18 14:10:17.623  1034  7205 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,08-18 14:10:17.631  1034  1540 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-18 14:10:17.632  1034  1540 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-18 14:10:17.632  1034  1540 D WifiStateMachine: enableVerboseLogging : level 2
08-18 14:10:17.633  1034  1540 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-18 14:10:17.633  1034  1540 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-18 14:10:17.633  1034  1540 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-18 14:10:17.634  1034  1540 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-18 14:10:17.634  1034  1540 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-18 14:10:17.634  1034  1540 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-18 14:10:17.634  1034  1540 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-18 14:10:17.635  1034  1540 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-18 14:10:17.635  1034  1540 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-18 14:10:17.635  1034  1540 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-18 14:10:17.635  1034  1540 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-18 14:10:17.636  1034  1540 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
,08-18 14:10:17.636  1034  1540 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-18 14:10:17.636  1034  1540 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-18 14:10:17.637  1034  1540 D WifiStateMachine: Setting OUI to DA-A1-19
08-18 14:10:17.637  1034  1540 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-18 14:10:17.637  1944  1944 D WfdsService: Supplicant Connection state is changed : true
08-18 14:10:17.637  1944  2342 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-18 14:10:17.637  1944  2342 D WfdsService: Set the WFDS Monitor: true
08-18 14:10:17.638  1944  2342 D WfdsMonitor: WfdsMonitorThread create
08-18 14:10:17.638  1944  2342 D WfdsMonitor: WFDS Monitor is created and started
08-18 14:10:17.638  1944  2342 D WfdsService: WiFi: Supplicant connection re-established
08-18 14:10:17.638  1034  1540 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-18 14:10:17.638  1034  1540 D WifiNative-HAL: Setting external_sim to 1
08-18 14:10:17.638  1034  1540 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-18 14:10:17.639  1034  1540 D WifiNative-wlan0: SET external_sim 1: returned true
08-18 14:10:17.639  1034  1540 I WifiNative-HAL: startHal
08-18 14:10:17.639  1034  1540 D wifi    : setting scan oui 0xaf7092a0
08-18 14:10:17.639  1034  1540 D WifiStateMachine: Setting OUI to DA-A1-19
08-18 14:10:17.639  1034  1540 I WifiNative-HAL: startHal
08-18 14:10:17.639  1034  1540 D wifi    : setting scan oui 0xaf7092a0
08-18 14:10:17.639  1034  1540 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-18 14:10:17.641  1034  1540 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-18 14:10:17.641  1034  1540 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-18 14:10:17.641  1944  7206 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-18 14:10:17.641  7196  7196 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-18 14:10:17.641  1944  7206 E CtrlSupplicant: Succeed to open control connection
08-18 14:10:17.641  1034  1540 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-18 14:10:17.641  1944  7206 E CtrlSupplicant: Succeed to open monitor connection
08-18 14:10:17.642  1034  1540 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-18 14:10:17.642  7196  7196 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-18 14:10:17.642  1944  7206 D WfdsMonitor: Supplicant connection established
08-18 14:10:17.642  1034  1540 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-18 14:10:17.642  1034  1540 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-18 14:10:17.642  7196  7196 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-18 14:10:17.642  1944  2342 D WfdsService: Connected to the supplicant for wfds
08-18 14:10:17.643  1034  1540 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-18 14:10:17.643  1034  1540 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-18 14:10:17.643  7196  7196 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-18 14:10:17.643  1034  1540 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-18 14:10:17.643  1034  1540 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-18 14:10:17.643  7196  7196 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-18 14:10:17.644  1034  1540 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-18 14:10:17.644  1034  1540 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-18 14:10:17.644  7196  7196 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-18 14:10:17.644  1034  1540 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-18 14:10:17.644  1034  1540 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-18 14:10:17.644  7196  7196 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-18 14:10:17.644  1034  1540 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-18 14:10:17.645  1034  1540 E WifiNative: : [198,374,031 us] RECO,NNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-18 14:10:17.645  1034  1540 D WifiNative-wlan0: doBoolean: RECONNECT
08-18 14:10:17.646  1034  1540 D WifiNative-wlan0: RECONNECT: returned true
08-18 14:10:17.646  1034  1540 D WifiNative-wlan0: doString: [STATUS]
08-18 14:10:17.647  1034  7205 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-18 14:10:17.647  1034  7205 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-18 14:10:17.647  1034  1540 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-18 14:10:17.647  1034  1540 D WifiNative-wlan0: doBoolean: SET ps 1
08-18 14:10:17.648  1034  1540 D WifiNative-wlan0: SET ps 1: returned true
08-18 14:10:17.648  1034  1539 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-18 14:10:17.648  1034  1034 D WifiScanningService: SCAN_AVAILABLE : 3
08-18 14:10:17.648  1034  1034 D RttService: SCAN_AVAILABLE : 3
08-18 14:10:17.648  1034  1558 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-18 14:10:17.648  1034  1558 I WifiNative-HAL: startHal
08-18 14:10:17.648  1034  1558 D wifi    : getting scan capabilities on interface[1] = 0xaf7092a0
08-18 14:10:17.648  1034  1558 D wifi    : failed to get capabilities : -3
08-18 14:10:17.648  1034  1558 E WifiScanningService: could not get scan capabilities
08-18 14:10:17.648  1034  1559 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-18 14:10:17.649  1034  1540 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-18 14:10:17.649  1034  1540 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-18 14:10:17.649  1034  1540 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-18 14:10:17.649   309   903 D CommandListener: Setting iface cfg
08-18 14:10:17.650   309   903 D CommandListener: Trying to bring up p2p0
08-18 14:10:17.650  1034  1539 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-18 14:10:17.650  1034  1540 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-18 14:10:17.650  1034  1539 D LGWifiP2pService: P2pEnablingState
08-18 14:10:17.650  1034  1539 D LGWifiP2pService: P2pEnablingState{ when=-1ms what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-18 14:10:17.650  1034  1539 D LGWifiP2pService: P2p socket connection successful
08-18 14:10:17.650  1034  1539 D LGWifiP2pService: P2pEnabledState
08-18 14:10:17.650  1034  1540 E WifiStateMachine:  DisconnectedState what:132106 1 0
,08-18 14:10:17.651  1034  1540 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-18 14:10:17.651  1034  1540 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-18 14:10:17.651  1034  1540 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-18 14:10:17.651  7196  7196 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-18 14:10:17.651  1944  1944 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-18 14:10:17.651  1944  1944 D WfdsService: WifiP2pState is changed : true
08-18 14:10:17.652  1944  2342 D WfdsService: Receive the WFDS_ENABLE Method
08-18 14:10:17.652  1944  2342 D WfdsService: Set the WFDS Monitor: true
,08-18 14:10:17.652  1944  2342 D WfdsService: Connected to the supplicant for wfds
08-18 14:10:17.652  1944  2342 D WfdsJNI : doCommand: WFDS_SET TRUE
08-18 14:10:17.652  7196  7196 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-18 14:10:17.652  1944  2342 D WfdsService: selectPreferredScanChannel [36]
08-18 14:10:17.652  1944  2342 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-18 14:10:17.652  1034  1540 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-18 14:10:17.653  1034  1540 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-18 14:10:17.653  1034  1540 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-18 14:10:17.653  1034  1540 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-18 14:10:17.653  7196  7196 E wpa_supplicant: disconnect_rssi_lvl: -100
08-18 14:10:17.653  1034  1539 D LGWifiP2pService: sending p2p connection changed broadcast
08-18 14:10:17.653  1034  1539 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-18 14:10:17.654  1034  1539 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-18 14:10:17.654  1034  1539 D WifiNative-p2p0: doBoolean: SET device_name G3
08-18 14:10:17.654  1034  1539 D WifiNative-p2p0: SET device_name G3: returned true
08-18 14:10:17.654  1034  1539 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-18 14:10:17.654  1034  1539 D LGWifiP2pService: before postfix = G3
08-18 14:10:17.654  1034  1539 D WifiServerServiceExt: postfix byte check : 2
08-18 14:10:17.654  1034  1539 D LGWifiP2pService: after postfix = G3
08-18 14:10:17.654  1034  1539 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-18 14:10:17.655  1034  1539 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-18 14:10:17.655  1034  1539 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-18 14:10:17.655  1944  1944 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-18 14:10:17.655  1034  1539 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-18 14:10:17.655  1034  1539 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-18 14:10:17.655  1944  1944 D WfdsService: isConnected: false
08-18 14:10:17.656  1034  1539 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-18 14:10:17.656  1034  1539 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-18 14:10:17.656  1034  1539 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-18 14:10:17.656  1034  1539 D WifiNative-HAL: p2pGetDeviceAddress
08-18 14:10:17.656  1034  1539 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-18 14:10:17.657  1034  1539 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-18 14:10:17.657  1034  1539 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-18 14:10:17.657  1034  1539 D WifiNative-p2p0: P2P_FLUSH: returned true
08-18 14:10:17.657  1034  1539 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-18 14:10:17.657  1034  1539 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-18 14:10:17.658  1034  1539 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-18 14:10:17.658  1034  1539 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-18 14:10:17.658  1034  1539 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-18 14:10:17.658  1944  1944 I WfdStateTracker: handleP2pThisDeviceChanged
08-18 14:10:17.658  1944  1944 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-18 14:10:17.658  1944  1944 D WfdsService: Update P2p Interface State: 3
08-18 14:10:17.658  1034  1540 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=198383  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-18 14:10:17.659  1034  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=198388  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-18 14:10:17.660  1034  1540 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-18 14:10:17.66,0  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-18 14:10:17.660  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-18 14:10:17.660  1034  1540 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-18 14:10:17.661  1034  1540 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-18 14:10:17.661  1034  1540 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-18 14:10:17.661  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-18 14:10:17.662  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-18 14:10:17.662  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-18 14:10:17.662  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-18 14:10:17.668  1034  1539 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-18 14:10:17.668  1034  1539 D LGWifiP2pService: sending p2p persistent groups changed broadcast
,08-18 14:10:17.668  1034  1539 D LGWifiP2pService: InactiveState
08-18 14:10:17.668  1034  1539 D LGWifiP2pService: InactiveState{ when=-11ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-18 14:10:17.668  1034  1539 D LGWifiP2pService: P2pEnabledState{ when=-11ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-18 14:10:17.668  1034  1539 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-18 14:10:17.669  7196  7196 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-18 14:10:17.671  7196  7196 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-18 14:10:17.671  1944  7206 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-18 14:10:17.672  1034  7205 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-18 14:10:17.672  1034  7205 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-18 14:10:17.672  1034  7205 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-18 14:10:17.672  1034  7205 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-18 14:10:17.672  7196  7196 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-18 14:10:17.672  7196  7196 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-18 14:10:17.672  1034  1539 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-18 14:10:17.672  1034  1539 D LGWifiP2pService: InactiveState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-18 14:10:17.672  1034  1539 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-18 14:10:17.672  1034  1539 D LGWifiP2pService: DefaultState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-18 14:10:17.673  1034  1539 D LGWifiP2pService: InactiveState{ when=-4ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-18 14:10:17.673  1034  1539 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-18 14:10:17.673  1034  1539 D LGWifiP2pService: DefaultState{ when=-4ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-18 14:10:17.673  1034  1539 D LGWifiP2pService: InactiveState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-18 14:10:17.673  7196  7196 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-18 14:10:17.673  1034  1539 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-18 14:10:17.673  1034  1539 D LGWifiP2pService: DefaultState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-18 14:10:17.673  1034  1539 D LGWifiP2pService: InactiveState{ when=-5ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-18 14:10:17.673  1034  1539 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-18 14:10:17.673  1034  1539 D LGWifiP2pService: DefaultState{ when=-5ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-18 14:10:17.673  1034  1034 E WifiServerServiceExt: No p2p device connected
08-18 14:10:17.673  1944  2342 W WfdsService: DefaultState - msg [9441285] is not handled
08-18 14:10:17.673  1944  7206 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-18 14:10:17.673  1944  7206 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-18 14:10:17.674  1034  7205 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-18 14:10:17.674  1034  7205 E WifiMonitor: WifiMonitor:p2p0 cnt=26 disp,atchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-18 14:10:17.674  1034  7205 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-18 14:10:17.674  1034  7205 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-18 14:10:17.674  1034  7205 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-18 14:10:17.674  1034  7205 E WifiMonitor: WifiMonitor:p2p0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-18 14:10:17.674  1034  7205 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-18 14:10:17.674  1034  7205 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-18 14:10:17.674  7196  7196 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-18 14:10:17.675  7196  7196 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-18 14:10:17.675  1034  7205 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-18 14:10:17.675  1034  7205 E WifiMonitor: WifiMonitor:wlan0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-18 14:10:17.675  1034  7205 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-18 14:10:17.675  1034  7205 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-18 14:10:17.675  7196  7196 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-18 14:10:17.675  7196  7196 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-18 14:10:17.676  1034  1540 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-18 14:10:17.676  1944  7206 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-18 14:10:17.676  1034  1540 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-18 14:10:17.677  7196  7196 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-18 14:10:17.677  1034  1540 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-18 14:10:17.677  1034  1540 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-18 14:10:17.677  1034  1540 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-18 14:10:17.677  1944  7206 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-18 14:10:17.677  1034  7205 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-18 14:10:17.677  1034  7205 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-18 14:10:17.677  1034  7205 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-18 14:10:17.677  1034  7205 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-18 14:10:17.678  1034  7205 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-18 14:10:17.678  1034  7205 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-18 14:10:17.678  1034  7205 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-18 14:10:17.678  1034  7205 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-18 14:10:17.678  1034  1539 D LGWifiP2pService: InactiveState{ when=-2ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-18 14:10:17.678  1034  1539 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-18 14:10:17.678  7196  7196 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-18 14:10:17.678  7196  7196 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-18 14:10:17.679  1034  7205 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-18 14:10:17.679  1034  ,7205 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-18 14:10:17.679  1034  1540 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-18 14:10:17.679  1034  1540 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-18 14:10:17.679  1034  7205 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-18 14:10:17.679  1034  1540 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-18 14:10:17.679  1034  1540 D WifiNative-wlan0: doBoolean: SCAN
08-18 14:10:17.679  1034  7205 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-18 14:10:17.679  1034  1540 D WifiNative-wlan0: SCAN: returned false
08-18 14:10:17.680  1034  1540 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=198409  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-18 14:10:17.681  1034  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=198410  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-18 14:10:17.681  1034  1540 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-18 14:10:17.681  1034  1540 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-18 14:10:17.681  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-18 14:10:17.682  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-18 14:10:17.682  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-18 14:10:17.682  1034  1540 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-18 14:10:17.682  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-18 14:10:17.682  1034  1540 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-18 14:10:17.682  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-18 14:10:17.682  1034  1540 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-18 14:10:17.683  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-18 14:10:17.683  1034  1034 D WifiServerServiceExt: setSupplicantStateSCANNING
08-18 14:10:17.683  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-18 14:10:17.684  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-18 14:10:17.684  1034  1034 D WifiServerServiceExt: setSupplicantStateSCANNING
08-18 14:10:17.718  7172  7172 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-18 14:10:17.741  3466  3466 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-18 14:10:17.741  3466  3466 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-18 14:10:17.741  3466  3466 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-18 14:10:17.750  7172  7172 I HubEmail: JNI_OnLoad()
08-18 14:10:17.750  7172  7172 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-18 14:10:17.750  7172  7172 I HubEmail: registerNatives()
08-18 14:10:17.750  7172  7172 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-18 14:10:17.750  7172  7172 I HubEmail: registerNativeMethods()
08-18 14:10:17.750  7172  7172 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-18 14:10:17.750  7172  7172 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
08-18 14:10:17.800  1034  2035 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7214 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-18 14:10:17.809  7024  7210 W FormManager: Network not available. Please check & try again.
08-18 14:10:17.813  7172  7213 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-18 14:10:17.818  7024  7212 V FormManager: Network unavailable.
08-18 14:10:17.823  7024  7212 V FormManager: Network unavailable.
08-18 14:10:17.835  1034  2035 I ActivityManager: Killing 6173:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,08-18 14:10:17.867  1034  1989 W libprocessgroup: failed to open /acct/uid_10080/pid_6173/cgroup.procs: No such file or directory
08-18 14:10:17.918  7214  7214 D LgDataFeature: LgDataFeature() Constructor: none
08-18 14:10:17.918  7214  7214 D LgDataFeature: LgDataFeature() Constructor Done, null
08-18 14:10:17.921  7214  7214 D PhoneMonitor: Register our PhoneStateListener
,08-18 14:10:17.937  7214  7214 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-18 14:10:17.939  7214  7214 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-18 14:10:17.962  7214  7214 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
08-18 14:10:17.963  7214  7214 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
,08-18 14:10:17.965  7214  7214 D TelephonyAutoProfiling: [parse] Load xml
08-18 14:10:17.971  7214  7214 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-18 14:10:17.971  7214  7214 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-18 14:10:17.971  7214  7214 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-18 14:10:17.971  7214  7214 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-18 14:10:17.972  7214  7214 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-18 14:10:17.972  7214  7214 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-18 14:10:17.972  7214  7214 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-18 14:10:17.972  7214  7214 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-18 14:10:17.972  7214  7214 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-18 14:10:17.972  7214  7214 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-18 14:10:17.972  7214  7214 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-18 14:10:17.972  7214  7214 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-18 14:10:17.972  7214  7214 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-18 14:10:17.972  7214  7214 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-18 14:10:17.973  7214  7214 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
,08-18 14:10:17.973  7214  7214 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-18 14:10:17.973  7214  7214 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-18 14:10:17.985  1034  1051 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7234 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-18 14:10:17.987  7214  7214 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-18 14:10:17.988  1034  1051 I ActivityManager: Killing 6203:com.google.android.apps.plus/u0a97 (adj 15): empty #17
08-18 14:10:18.047  1034  2013 W libprocessgroup: failed to open /acct/uid_10097/pid_6203/cgroup.procs: No such file or directory
,08-18 14:10:18.183  1034  7205 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-18 14:10:18.183  1034  7205 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-18 14:10:18.183  7196  7196 E wpa_supplicant: USIM:  scard_init function
08-18 14:10:18.184  1034  7205 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-18 14:10:18.184  1034  7205 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: WPS-AP-AVAILABLE 
08-18 14:10:18.184  1034  7205 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-18 14:10:18.184  1034  1540 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=11 bcn=0
08-18 14:10:18.184  7196  7196 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-18 14:10:18.184  1034  1540 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=11 bcn=0
08-18 14:10:18.185  1034  1540 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=11 bcn=0
,08-18 14:10:18.185  1034  1540 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=11 bcn=0
08-18 14:10:18.185  1034  7205 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-18 14:10:18.185  1034  1540 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-18 14:10:18.186  1034  7205 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-18 14:10:18.203  1034  1540 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=198932  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-18 14:10:18.209  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-18 14:10:18.209  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-18 14:10:18.209  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-18 14:10:18.209  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-18 14:10:18.209  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-18 14:10:18.210  1034  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=198939  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-18 14:10:18.210  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-18 14:10:18.212  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-18 14:10:18.212  1034  1034 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-18 14:10:18.304  7196  7196 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-18 14:10:18.307  1034  7205 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-18 14:10:18.307  1034  7205 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-18 14:10:18.307  1034  7205 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-18 14:10:18.308  1034  7205 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-18 14:10:18.308  1034  7205 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-18 14:10:18.308  1034  7205 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-18 14:10:18.310  1034  1540 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=199038  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-18 14:10:18.310  1034  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=199039  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-18 14:10:18.313  1034  7205 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-18 14:10:18.313  7196  7196 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-18 14:10:18.314  1034  7205 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-18 14:10:18.314  7196  7196 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-18 14:10:18.315  1034  7205 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-18 14:10:18.315  1034  7205 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-18 14:10:18.315  1034  7205 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-18 14:10:18.318  1034  7205 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-18 14:10:18.318  1034  7205 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-18 14:10:18.319  1034  7205 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-18 14:10:18.319  1034  1540 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=199048
08-18 14:10:18.319  1034  7205 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-18 14:10:18.319  1034  7205 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-18 14:10:18.319  1034  1540 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=199048
08-18 14:10:18.320  1034  1540 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=199049
08-18 14:10:18.320  1034  1540 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=199049
08-18 14:10:18.321  1034  1540 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=199050
,08-18 14:10:18.321  1034  1540 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=199050  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-18 14:10:18.341  1034  1810 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7255 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,08-18 14:10:18.343  1034  1810 I ActivityManager: Killing 6670:com.lge.eula/1000 (adj 15): empty #17
08-18 14:10:18.388  1034  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=199117  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
,08-18 14:10:18.391  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-18 14:10:18.391  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-18 14:10:18.392  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-18 14:10:18.392  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-18 14:10:18.392  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-18 14:10:18.393  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-18 14:10:18.394  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-18 14:10:18.394  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-18 14:10:18.394  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-18 14:10:18.395  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-18 14:10:18.395  1034  1034 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-18 14:10:18.395  1034  1540 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=199124  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-18 14:10:18.396  1034  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=199125  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-18 14:10:18.396  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-18 14:10:18.396  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-18 14:10:18.396  1034  1540 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=199125
08-18 14:10:18.397  1034  1540 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=199126
08-18 14:10:18.397  1034  1540 D WifiNative-wlan0: doString: [STATUS]
08-18 14:10:18.398  1034  7205 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-18 14:10:18.398  1034  7205 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-18 14:10:18.398  1034  1540 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-18 14:10:18.400  1034  1540 I WifiServiceExtension: setVHTCapabilityType  : false
08-18 14:10:18.402  1034  1577 W libprocessgroup: failed to open /acct/uid_1000/pid_6670/cgroup.procs: No such file or directory
08-18 14:10:18.403  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-18 14:10:18.406  1034  1101 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-18 14:10:18.407  1034  1387 D PowerManagerServiceEx: acquireWakeLockInternal: lock=299530809, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1034
08-18 14:10:18.410  1034  1387 V AlarmManager: RTC_WAKEUP set : Alarm{2c59987e type 0 when 1471522217848 android} when 1471522217848
08-18 14:10:18.410  1034  1540 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-18 14:10:18.410  1034  1540 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-18 14:10:18.410  1034  1387 V AlarmManager: ELAPSED_WAKEUP set : Alarm{1e1081df type 2 when 199061 com.google.android.gms} when 199061
08-18 14:10:18.419  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-18 14:10:18.419  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-18 14:10:18.419  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-18 14:10:18.420  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-18 14:10:18.420  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-18 14:10:18.420  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,08-18 14:10:18.424  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-18 14:10:18.424  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-18 14:10:18.425  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-18 14:10:18.427  1034  1540 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-18 14:10:18.427  1034  1540 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-18 14:10:18.427  1034  1540 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-18 14:10:18.427  1034  1547 D ConnectivityService: Got NetworkAgent Messenger
08-18 14:10:18.427  1034  1547 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-18 14:10:18.427  1034  1540 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-18 14:10:18.427  1034  1547 D ConnectivityService: NetworkAgent connected
08-18 14:10:18.427  1034  1540 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-18 14:10:18.432  1034  1540 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-18 14:10:18.432  1034  1540 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-18 14:10:18.432  1034  1540 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-18 14:10:18.433  1034  1540 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-18 14:10:18.433  1034  1540 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,08-18 14:10:18.438  1034  1540 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-18 14:10:18.439   309   903 D CommandListener: Setting iface cfg
08-18 14:10:18.442  1034  7273 D DhcpStateMachine: StoppedState
08-18 14:10:18.442  1034  1540 E WifiStateMachine: Start Dhcp Watchdog 2
08-18 14:10:18.442  1034  7273 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-18 14:10:18.442  1034  7273 D DhcpStateMachine: WaitBeforeStartState
08-18 14:10:18.442  1034  1540 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=199171  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-18 14:10:18.443  1034  1540 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=199172  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-18 14:10:18.443  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-18 14:10:18.443  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-18 14:10:18.443  1034  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=199172  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-18 14:10:18.444  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-18 14:10:18.445  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-18 14:10:18.445  1034  1034 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
,08-18 14:10:18.447  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-18 14:10:18.447  1034  1034 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-18 14:10:18.448  1034  1540 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=199177  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-18 14:10:18.449  1034  1540 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=199177  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-18 14:10:18.449  1034  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=199178  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-18 14:10:18.450  1034  1540 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-18 14:10:18.450  1034  1540 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-18 14:10:18.450  1034  1540 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-18 14:10:18.451  1034  1540 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-18 14:10:18.451  1034  1540 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-18 14:10:18.452  1034  1540 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-18 14:10:18.453  1034  1540 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:153108] from screen [on:0 period:-1651564075] gl rssi=-49 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-18 14:10:18.454  1034  1540 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1651564074] gl rssi=-49 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-18 14:10:18.454  1034  1540 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-18 14:10:18.457  2642  2642 D [Concierge]Service: onStartCommand(). Type : 9
,08-18 14:10:18.464  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-18 14:10:18.465  1034  1540 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-18 14:10:18.466  1034  1540 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-18 14:10:18.466  1034  1547 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-18 14:10:18.466  1034  1540 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-18 14:10:18.467  1034  1540 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-18 14:10:18.467  1034  1540 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-18 14:10:18.468  1034  1540 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-18 14:10:18.468  1034  1547 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-18 14:10:18.468  1034  1540 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=117,0,0
08-18 14:10:18.469  1034  1540 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=117,0,0
08-18 14:10:18.469  1034  1540 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-18 14:10:18.469  7196  7196 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-18 14:10:18.470  1034  1540 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-18 14:10:18.470  1034  1540 D WifiNative-wlan0: doBoolean: SET ps 0
,08-18 14:10:18.472  1034  1540 D WifiNative-wlan0: SET ps 0: returned true
08-18 14:10:18.472  1034  1540 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-18 14:10:18.472  7196  7196 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-18 14:10:18.473  1034  1540 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-18 14:10:18.473  1034  1539 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1bfda406 target=com.android.internal.util.StateMachine$SmHandler }
08-18 14:10:18.474  1034  1539 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1bfda406 target=com.android.internal.util.StateMachine$SmHandler }
08-18 14:10:18.474  1034  7273 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-18 14:10:18.474  1034  7273 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-18 14:10:18.474  1034  1540 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-18 14:10:18.474  1034  1540 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-18 14:10:18.474  1034  1540 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-18 14:10:18.475   309   903 D CommandListener: Setting iface cfg
08-18 14:10:18.475   309   903 D CommandListener: Trying to bring up wlan0
08-18 14:10:18.476  1034  1540 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-18 14:10:18.478  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-18 14:10:18.478  1034  1034 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-18 14:10:18.529  1034  1971 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7278 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-18 14:10:18.530  1034  1971 I ActivityManager: Killing 6687:com.lge.bnr/1000 (adj 15): empty #17
,08-18 14:10:18.639  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
,08-18 14:10:18.639  1034  1034 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-18 14:10:18.641  1034  1540 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-18 14:10:18.643  1034  1540 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-18 14:10:18.645  1034  1540 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-18 14:10:18.647  1034  1540 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-18 14:10:18.649  1034  1540 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-18 14:10:18.651  1034  1540 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-18 14:10:18.652  1034  1547 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,08-18 14:10:18.654  1034  1540 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-18 14:10:18.656  1034  1540 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-18 14:10:18.657  1034  1540 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-18 14:10:18.657  1034  1539 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-18 14:10:18.657  7196  7196 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-18 14:10:18.658  1034  1539 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-18 14:10:18.660  1034  1540 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-18 14:10:18.660  1034  1540 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-18 14:10:18.661  7196  7196 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-18 14:10:18.661  1034  1901 W libprocessgroup: failed to open /acct/uid_1000/pid_6687/cgroup.procs: No such file or directory
08-18 14:10:18.664  1034  1540 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-18 14:10:18.664  1034  1540 D WifiNative-wlan0: doBoolean: SET ps 1
08-18 14:10:18.676  1034  7273 D DhcpStateMachine: DHCPV4 request on wlan0
,08-18 14:10:18.679  1034  1540 D WifiNative-wlan0: SET ps 1: returned true
08-18 14:10:18.680  1034  1540 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-18 14:10:18.680  1034  1540 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-18 14:10:18.680  1034  1540 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-18 14:10:18.682  1034  1547 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-18 14:10:18.682  1034  1547 D ConnectivityService: ignoring duplicate network state non-change
08-18 14:10:18.682  1034  1547 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-18 14:10:18.684  1034  7273 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-18 14:10:18.684  1034  1547 D ConnectivityService: Adding iface wlan0 to network 101
08-18 14:10:18.684  1034  7273 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-18 14:10:18.684  7297  7297 W dhcpcd  : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-18 14:10:18.684  7297  7297 W dhcpcd  : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-18 14:10:18.694  1034  1540 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-18 14:10:18.701  7297  7297 I dhcpcd  : version 5.5.6 starting
08-18 14:10:18.703  7297  7297 E dhcpcd  : get_duid: m
08-18 14:10:18.703  7297  7297 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-18 14:10:18.704  7297  7297 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,08-18 14:10:18.716  1034  1547 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-18 14:10:18.717  1034  1547 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-18 14:10:18.720  1034  1547 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-18 14:10:18.721   309   903 E Netd    : netlink response contains error (File exists)
08-18 14:10:18.722  1034  1547 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-18 14:10:18.722  1034  1547 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-18 14:10:18.723  1034  1547 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-18 14:10:18.723  1034  1547 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-18 14:10:18.724  1034  1547 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-18 14:10:18.724  1034  1547 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-18 14:10:18.724  1034  1547 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-18 14:10:18.725  1034  7272 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-18 14:10:18.725  1034  7272 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-18 14:10:18.725  1034  7272 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-18 14:10:18.725  1034  7272 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-18 14:10:18.725  7278  7278 I art     : Almond Protected OAT
08-18 14:10:18.727  1034  1547 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-18 14:10:18.727  1034  1547 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-18 14:10:18.727  1034  1547 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-18 14:10:18.727  1034  1547 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-18 14:10:18.727  1034  1547 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-18 14:10:18.727   309  7304 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-18 14:10:18.728  1034  1547 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-18 14:10:18.728  1034  1547 D ConnectivityService: currentScore = 0, newScore = 20
08-18 14:10:18.728  1034  1547 D ConnectivityService:    accepting network in place of null
08-18 14:10:18.728  1034  1547 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-18 14:10:18.729  1034  1540 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-18 14:10:18.729  1034  1540 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-18 14:10:18.729  1855  1855 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-18 14:10:18.730  1855  1855 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-18 14:10:18.730  1034  1547 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", ,roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-18 14:10:18.730  1034  1547 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-18 14:10:18.730  1034  1547 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-18 14:10:18.730  1034  1547 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-18 14:10:18.730  1034  1547 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-18 14:10:18.731  1034  1547 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-18 14:10:18.732  1034  1547 D ConnectivityService: validation of new default Network = false
08-18 14:10:18.732  1034  1547 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-18 14:10:18.733  1034  1547 D DSQN    : enableDataServiceNotify 
08-18 14:10:18.733  1034  1547 D DSQN    : start dsqn bin
08-18 14:10:18.734  7306  7306 W dsqn    : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-18 14:10:18.734  7306  7306 W dsqn    : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-18 14:10:18.747  1034  1547 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-18 14:10:18.747  1034  1547 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-18 14:10:18.747  1034  1547 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-18 14:10:18.747  1034  1547 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-18 14:10:18.748  1605  1818 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-18 14:10:18.748  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-18 14:10:18.748  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-18 14:10:18.749  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-18 14:10:18.750  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-18 14:10:18.750  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-18 14:10:18.750  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-18 14:10:18.751  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-18 14:10:18.751  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-18 14:10:18.752  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-18 14:10:18.752  1034  1034 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-18 14:10:18.757  1944  1944 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-18 14:10:18.760  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-18 14:10:18.760  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-18 14:10:18.760  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-18 14:10:18.761  1034  1034 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-18 14:10:18.763  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-18 14:10:18.763  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-18 14:10:18.763  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-18 14:10:18.763  1034  1034 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-18 14:10:18.763  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-18 14:10:18.763  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-18 14:10:18.763  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-18 14:10:18.769  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-18 14:10:18.769  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-18 14:10:18.770  7297  7297 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-18 14:10:18.771  7306  7306 E DSQN    : DSQN ssw
08-18 14:10:18.771  7297  7297 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-18 14:10:18.771  7297  7297 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-18 14:10:18.771  7297  7297 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
08-18 14:10:18.771  7297  7297 D dhcpcd  : wlan0: sending REQUEST (xid 0x937c9b1d), next in 4.92 seconds
08-18 14:10:18.773  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-18 14:10:18.775  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-18 14:10:18.775  1605  1605 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-18 14:10:18.775  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-18 14:10:18.785  1034  1538 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-18 14:10:18.785  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-18 14:10:18.785   309  7304 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-18 14:10:18.785  1605  1605 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-18 14:10:18.786  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-18 14:10:18.789  7278  7278 D WeatherApplication: removeAccount
08-18 14:10:18.790  7278  7278 D WeatherApplication: Account.length = 0
08-18 14:10:18.791  7278  7278 E WeatherApplication: OPERATOR:OPEN
08-18 14:10:18.794  1820  7312 I CheckinService: active receiver: enabled
08-18 14:10:18.795  7278  7278 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:10:18
08-18 14:10:18.805  1034  1539 D LGWifiP2pService: InactiveState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-18 14:10:18.805  1034  1539 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-18 14:10:18.805  1034  1539 D LGWifiP2pService: DefaultState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,08-18 14:10:18.808  7297  7297 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,08-18 14:10:18.819   309  7304 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-18 14:10:18.825  1034  1540 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-18 14:10:18.825  1034  1540 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-18 14:10:18.826  1034  1540 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
08-18 14:10:18.826  1034  1540 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-18 14:10:18.826  1034  1540 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
,08-18 14:10:18.826  1034  1540 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
08-18 14:10:18.836  7297  7297 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
08-18 14:10:18.836  7297  7297 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
08-18 14:10:18.836  7297  7297 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-18 14:10:18.836  7297  7297 D dhcpcd  : wlan0: adding default route via 192.168.1.1
,08-18 14:10:18.837  7297  7297 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,08-18 14:10:18.846   309   902 D LGDataListener: argv[0]=dsqncommand
08-18 14:10:18.846   309   902 D LGDataListener: argv[1]=wlan0
08-18 14:10:18.846   309   902 D LGDataListener: argv[2]=1
08-18 14:10:18.846   309   902 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-18 14:10:18.846  1034  1099 D DSQN    : DSQM DsqnNotification wlan0  1
08-18 14:10:18.846  1034  1099 D DSQN    : start to monitor internet connection
08-18 14:10:18.873  1034  7272 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 18 Aug 2016 12:10:18 GMT], X-Android-Received-Millis=[1471522218873], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1471522218845]}
08-18 14:10:18.873  1034  7272 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
,08-18 14:10:18.873  1034  7272 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-18 14:10:18.873  1034  1547 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-18 14:10:18.873  1034  1547 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-18 14:10:18.874  1034  1547 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-18 14:10:18.874  1034  1547 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-18 14:10:18.874  1034  1547 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-18 14:10:18.874  1034  1547 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-18 14:10:18.874  1034  1547 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-18 14:10:18.874  1034  1547 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-18 14:10:18.874  1034  1547 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-18 14:10:18.874  1034  1547 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-18 14:10:18.875  1034  1547 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-18 14:10:18.875  1605  1818 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-18 14:10:18.875  1034  1540 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-18 14:10:18.875  1034  1540 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-18 14:10:18.875  1855  1855 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-18 14:10:18.875  1034  1547 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-18 14:10:18.875  1855  1855 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-18 14:10:18.959  7297  7297 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
,08-18 14:10:18.959  7297  7297 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-18 14:10:18.959  7297  7297 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-18 14:10:18.964  1820  7312 I CheckinService: Preparing to send checkin request
08-18 14:10:18.964  1820  7312 I EventLogService: Accumulating logs since 1471522077339
08-18 14:10:18.968  7278  7278 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-18 14:10:18.968  7278  7278 D Weather.Utils: 2 : All the weather widget is gone.
08-18 14:10:18.971  7278  7278 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-18 14:10:18.974  7278  7278 D WeatherAncestor: connectivity changed - connection : true
08-18 14:10:18.975  7278  7278 D WeatherService: 2 : isServiceAlived():false forecastCache:null
08-18 14:10:18.979  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-18 14:10:18.980  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-18 14:10:18.980  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-18 14:10:18.989  7278  7278 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-18 14:10:18.989  7278  7278 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-18 14:10:18.989  7278  7278 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
,08-18 14:10:19.003  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-18 14:10:19.004  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-18 14:10:19.004  7278  7278 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-18 14:10:19.005  7278  7278 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:10:19
08-18 14:10:19.005  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-18 14:10:19.030  1034  2013 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7322 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-18 14:10:19.030  1034  2013 I ActivityManager: Killing 2132:com.lge.music/u0a34 (adj 15): empty #17
,08-18 14:10:19.040   348   348 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 196us total 10.569ms
08-18 14:10:19.049   348   348 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 187us total 9.040ms
,08-18 14:10:19.056   314  2149 V AudioFlinger: 2132 died, releasing its sessions
08-18 14:10:19.056   314  2149 V AudioFlinger:  pid 1855 @ 0
08-18 14:10:19.056   314  2149 V AudioFlinger:  pid 3466 @ 1
08-18 14:10:19.056   314  2149 V AudioFlinger:  pid 3466 @ 2
08-18 14:10:19.059   348   348 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 187us total 8.956ms
08-18 14:10:19.087  1034  1943 W libprocessgroup: failed to open /acct/uid_10034/pid_2132/cgroup.procs: No such file or directory
08-18 14:10:19.087  1820  7312 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-18 14:10:19.174   279   365 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-18 14:10:19.174   279   365 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-18 14:10:19.174   279   365 W Vold    : Returning OperationFailed - no handler for errno 0
08-18 14:10:19.174  7322  7355 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-18 14:10:19.176   279   365 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-18 14:10:19.176   279   365 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-18 14:10:19.176   279   365 W Vold    : Returning OperationFailed - no handler for errno 0
08-18 14:10:19.176  7322  7355 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,08-18 14:10:19.198   279   365 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-18 14:10:19.198   279   365 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-18 14:10:19.198   279   365 W Vold    : Returning OperationFailed - no handler for errno 0
08-18 14:10:19.198  7322  7359 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-18 14:10:19.199  1034  1623 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7361 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
08-18 14:10:19.200   279   365 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-18 14:10:19.200   279   365 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-18 14:10:19.200   279   365 W Vold    : Returning OperationFailed - no handler for errno 0
08-18 14:10:19.201  7322  7359 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,08-18 14:10:19.248  7361  7361 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-18 14:10:19.248  7361  7361 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-18 14:10:19.278  7361  7361 I MultiDex: VM with version 2.1.0 has multidex support
08-18 14:10:19.278  7361  7361 I MultiDex: install
08-18 14:10:19.278  7361  7361 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-18 14:10:19.288  7361  7361 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,08-18 14:10:19.290  1034  7273 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-18 14:10:19.291  1034  7273 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-18 14:10:19.292  1034  7273 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-18 14:10:19.292  1034  7273 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
08-18 14:10:19.292  1034  7273 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-18 14:10:19.292  1034  7273 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-18 14:10:19.292  1034  7273 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-18 14:10:19.292  1034  7273 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-18 14:10:19.292  1034  7273 D DhcpStateMachine: RunningState
08-18 14:10:19.394  7322  7322 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-18 14:10:19.401  7322  7322 I LibraryLoader: Loading: webviewchromium
,08-18 14:10:19.403  7322  7322 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 144-147)
08-18 14:10:19.403  7322  7322 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-18 14:10:19.408  7322  7322 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {67697a6}
,08-18 14:10:19.410  7322  7322 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-18 14:10:19.410  7322  7322 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-18 14:10:19.423  7322  7322 I BrowserStartupController: Initializing chromium process, renderers=0
,08-18 14:10:19.424  7322  7322 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-18 14:10:19.439  7322  7322 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-18 14:10:19.439  7322  7322 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-18 14:10:19.439  7322  7322 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
,08-18 14:10:19.443   314   314 V AudioPolicyService: registerClient() client 0xb558a380, uid 10093
08-18 14:10:19.444  7322  7400 W AudioManagerAndroid: Requires BLUETOOTH permission
08-18 14:10:19.453  7322  7322 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-18 14:10:19.453  7322  7322 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-18 14:10:19.453  7322  7322 I Adreno-EGL: Build Date: 12/12/14 금
08-18 14:10:19.453  7322  7322 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-18 14:10:19.453  7322  7322 I Adreno-EGL: Remote Branch: 
08-18 14:10:19.453  7322  7322 I Adreno-EGL: Local Patches: 
08-18 14:10:19.453  7322  7322 I Adreno-EGL: Reconstruct Branch: 
,08-18 14:10:19.649  1034  2054 I art     : Explicit concurrent mark sweep GC freed 107284(5MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 1.365ms total 107.709ms
,08-18 14:10:19.651  7322  7322 I NSApplication: Starting up...
08-18 14:10:19.678  7361  7377 D LgDataFeature: LgDataFeature() Constructor: none
,08-18 14:10:19.678  7361  7377 D LgDataFeature: LgDataFeature() Constructor Done, null
08-18 14:10:19.702  1034  1971 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7415 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-18 14:10:19.703  1034  1971 I ActivityManager: Killing 6135:com.android.vending/u0a44 (adj 15): empty #17
,08-18 14:10:19.732  7414  7414 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-18 14:10:19.746  1034  1547 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-18 14:10:19.766  1034  1051 W libprocessgroup: failed to open /acct/uid_10044/pid_6135/cgroup.procs: No such file or directory
,08-18 14:10:19.785  1034  1623 D WifiServiceImplEx: setWifiEnabled: false pid=6817, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-18 14:10:19.786  1034  1623 D WifiService: setWifiEnabled: false pid=6817, uid=10118
08-18 14:10:19.786  1034  1623 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-18 14:10:19.798  1034  1540 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-18 14:10:19.800  1034  1540 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
,08-18 14:10:19.800  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-18 14:10:19.800  7414  7414 I dex2oat : dex2oat took 68.075ms (threads: 4)
08-18 14:10:19.800  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-18 14:10:19.800  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-18 14:10:19.801  1034  1540 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-18 14:10:19.801  1034  1540 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-18 14:10:19.802  1034  1540 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-18 14:10:19.802  1034  1540 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-18 14:10:19.802  1034  1540 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-18 14:10:19.802  1034  1540 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-18 14:10:19.803  1034  1540 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-18 14:10:19.803  1034  1540 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-18 14:10:19.807  1034  1540 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-18 14:10:19.807  1034  1540 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-18 14:10:19.807  1034  1539 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-18 14:10:19.807  7196  7196 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-18 14:10:19.807  1034  1539 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-18 14:10:19.807  1034  1540 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-18 14:10:19.807  1034  1540 D WifiNative-wlan0: doBoolean: SET ps 1
08-18 14:10:19.808  1034  1540 D WifiNative-wlan0: SET ps 1: returned true
08-18 14:10:19.808  1034  7273 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-18 14:10:19.812   309   903 D CommandListener: Clearing all IP addresses on wlan0
,08-18 14:10:19.812  7415  7415 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-18 14:10:19.823  7361  7377 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-18 14:10:19.823  7361  7377 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-18 14:10:19.823  7361  7377 I Adreno-EGL: Build Date: 12/12/14 금
08-18 14:10:19.823  7361  7377 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-18 14:10:19.823  7361  7377 I Adreno-EGL: Remote Branch: 
08-18 14:10:19.823  7361  7377 I Adreno-EGL: Local Patches: 
08-18 14:10:19.823  7361  7377 I Adreno-EGL: Reconstruct Branch: 
08-18 14:10:19.839  1034  1547 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-18 14:10:19.839  1034  1547 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
,08-18 14:10:19.844  1034  1540 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
,08-18 14:10:19.844  1034  1540 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-18 14:10:19.844  1034  1540 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-18 14:10:19.845  1034  1540 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-18 14:10:19.845  1034  1540 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-18 14:10:19.846  1034  1540 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-18 14:10:19.848  1944  1944 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-18 14:10:19.850  1034  1539 D LGWifiP2pService: InactiveState{ when=-7ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-18 14:10:19.850  1034  1539 D LGWifiP2pService: P2pEnabledState{ when=-7ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-18 14:10:19.850  1034  1539 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@27dd61b5
08-18 14:10:19.851  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-18 14:10:19.852  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-18 14:10:19.852  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-18 14:10:19.854  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-18 14:10:19.860  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-18 14:10:19.860  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-18 14:10:19.860  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-18 14:10:19.861  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-18 14:10:19.863  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-18 14:10:19.863  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-18 14:10:19.863  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-18 14:10:19.863  1034  1034 D WifiScanningService: SCAN_AVAILABLE : 1
08-18 14:10:19.863  1034  1558 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-18 14:10:19.864  1034  1034 D RttService: SCAN_AVAILABLE : 1
08-18 14:10:19.864  1034  1559 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-18 14:10:19.866  1034  1540 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,08-18 14:10:19.867  1034  1539 D LGWifiP2pService: P2pDisablingState
08-18 14:10:19.867  1034  1539 D LGWifiP2pService: P2pDisablingState{ when=-17ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-18 14:10:19.867  1034  1539 D LGWifiP2pService: p2p socket connection lost
08-18 14:10:19.867  1034  1539 D LGWifiP2pService: P2pDisabledState
08-18 14:10:19.868  1034  1540 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-18 14:10:19.868  1034  1540 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-18 14:10:19.868  1034  1539 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-18 14:10:19.868  1034  1539 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-18 14:10:19.868  7196  7196 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-18 14:10:19.868  1034  1540 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-18 14:10:19.868  1034  1540 D WifiNative-wlan0: doBoolean: SET ps 1
08-18 14:10:19.869  1034  1540 D WifiNative-wlan0: SET ps 1: returned true
08-18 14:10:19.870  1944  1944 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-18 14:10:19.870  1944  1944 D WfdsService: WifiP2pState is changed : false
08-18 14:10:19.870  1944  2342 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-18 14:10:19.870  1944  2342 D WfdsService: Set the WFDS Monitor: false
08-18 14:10:19.871  1944  2342 D WfdsMonitor: WFDS Monitor is stopped
08-18 14:10:19.871  1944  2342 D WfdsService: STATE : WfdsDisabledState - enter
08-18 14:10:19.871  1944  2344 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-18 14:10:19.871  1944  7206 D CtrlSupplicant: Received on exit socket, terminate
08-18 14:10:19.871  1944  7206 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-18 14:10:19.871  1944  7206 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-18 14:10:19.871  1944  7206 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-18 14:10:19.872  1944  2342 W WfdsService: DefaultState - msg [9445378] is not handled
08-18 14:10:19.874   309   903 D CommandListener: Clearing all IP addresses on wlan0
08-18 14:10:19.874  1034  1547 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-18 14:10:19.874  1034  1547 D DSQN    : disableDataServiceNotify
08-18 14:10:19.874  1034  1547 D DSQN    : stop dsqn bin
08-18 14:10:19.875  1034  1540 D WifiNative-p2p0: doBoolean: TERMINATE
08-18 14:10:19.875  1034  1540 D WifiNative-p2p0: TERMINATE: returned true
08-18 14:10:19.875  1034  1540 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-18 14:10:19.875  1034  1540 E WifiStateMachine: useWiFiOffloading() : false
08-18 14:10:19.875  1034  1540 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-18 14:10:19.879  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-18 14:10:19.879  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-18 14:10:19.879  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-18 14:10:19.879  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,08-18 14:10:19.881  1944  1944 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-18 14:10:19.881  1034  1547 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-18 14:10:19.881  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-18 14:10:19.881  1034  1547 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-18 14:10:19.881  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-18 14:10:19.881  1034  1547 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-18 14:10:19.881  1034  1034 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-18 14:10:19.882  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-18 14:10:19.882  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-18 14:10:19.882  1034  1547 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-18 14:10:19.883  6817  6817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-18 14:10:19.883  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-18 14:10:19.883  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 14:10:19.883  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-18 14:10:19.883  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-18 14:10:19.883  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-18 14:10:19.883  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-18 14:10:19.883  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-18 14:10:19.883  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-18 14:10:19.883  6817  6817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-18 14:10:19.883  6817  6817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-18 14:10:19.883  1034  1547 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-18 14:10:19.883  1605  1818 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-18 14:10:19.883  1034  1547 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-18 14:10:19.883  1034  1547 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-18 14:10:19.884  1034  1547 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECT,IVITY_CHANGE_IMMEDIATE
08-18 14:10:19.884  6817  6817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-18 14:10:19.884  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-18 14:10:19.884  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 14:10:19.884  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-18 14:10:19.884  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-18 14:10:19.884  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-18 14:10:19.884  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-18 14:10:19.884  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-18 14:10:19.884  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-18 14:10:19.884  6817  6817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-18 14:10:19.884  6817  6817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-18 14:10:19.884  1034  1547 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-18 14:10:19.884  1034  1547 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-18 14:10:19.884  1034  7272 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-18 14:10:19.884  1034  7272 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-18 14:10:19.884  1034  7272 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-18 14:10:19.884  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-18 14:10:19.885  1034  1034 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-18 14:10:19.885  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-18 14:10:19.885  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-18 14:10:19.885  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-18 14:10:19.885  1034  1538 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-18 14:10:19.885  1034  1547 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-18 14:10:19.885  1034  1547 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-18 14:10:19.886  1034  1547 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-18 14:10:19.886  1034  1547 D NetworkManagementService: Removing idletimer
08-18 14:10:19.886  1034  1547 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-18 14:10:19.886  1034  1547 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-18 14:10:19.886  1034  1540 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTER,NET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-18 14:10:19.886  1855  1855 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-18 14:10:19.886  1034  1540 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-18 14:10:19.886  1855  1855 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-18 14:10:19.887  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-18 14:10:19.887  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-18 14:10:19.887  1034  1034 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-18 14:10:19.887  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-18 14:10:19.887  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-18 14:10:19.887  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-18 14:10:19.887  1034  1538 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-18 14:10:19.887  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-18 14:10:19.889  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-18 14:10:19.909  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-18 14:10:19.911  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-18 14:10:19.911  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-18 14:10:19.928  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-18 14:10:19.929  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-18 14:10:19.929  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-18 14:10:19.957  7196  7196 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-18 14:10:19.957  7196  7196 I wpa_supplicant: monitor socket send errors count : 1
08-18 14:10:19.957  7196  7196 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1944-4\x00 that cannot receive messages
08-18 14:10:19.958  1034  7205 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-18 14:10:19.958  1034  7205 D WifiMonitor: Dropping event because (p2p0) is stopped
,08-18 14:10:19.979  7361  7377 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-18 14:10:19.979  7361  7377 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-18 14:10:19.979  7361  7377 I Adreno-EGL: Build Date: 12/12/14 금
08-18 14:10:19.979  7361  7377 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-18 14:10:19.979  7361  7377 I Adreno-EGL: Remote Branch: 
08-18 14:10:19.979  7361  7377 I Adreno-EGL: Local Patches: 
08-18 14:10:19.979  7361  7377 I Adreno-EGL: Reconstruct Branch: 
,08-18 14:10:19.995  7196  7196 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-18 14:10:19.996  1034  1101 D Tethering: InitialState.processMessage what=4
08-18 14:10:19.996  7196  7196 W wpa_supplicant: USIM:  scard_deinit function
08-18 14:10:19.997  1034  1101 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-18 14:10:19.998  1034  7205 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
,08-18 14:10:19.998  1034  7205 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-18 14:10:19.998  1034  7205 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-18 14:10:19.998  1034  7205 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-18 14:10:19.999  1034  7205 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-18 14:10:19.999  1034  7205 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-18 14:10:19.999  1034  1540 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-18 14:10:20.000  1034  1540 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-18 14:10:20.000  1034  1540 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=200729
08-18 14:10:20.000  1034  1540 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=200729
08-18 14:10:20.001  1034  1540 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=200730  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-18 14:10:20.001  1034  1540 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=200730  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-18 14:10:20.014  1034  7273 D DhcpStateMachine: StoppedState
08-18 14:10:20.014  1034  7273 D DhcpStateMachine: StoppedState{ when=-145ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-18 14:10:20.015  1034  1540 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-18 14:10:20.015  1034  1540 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
,08-18 14:10:20.037  6505  6505 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-18 14:10:20.039  6505  6955 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-18 14:10:20.049  2161  2161 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-18 14:10:20.057  7137  7137 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-18 14:10:20.057  7137  7137 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,08-18 14:10:20.057  7137  7137 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-18 14:10:20.057  7137  7137 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-18 14:10:20.058  7137  7137 I AppUp4:CustModeStarterReceiver: onReceive
,08-18 14:10:20.060  7137  7137 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@3ef530ff
08-18 14:10:20.060  7137  7137 D AppUp4:CustFacade: isCustomizationCompleted : false
08-18 14:10:20.060  7137  7137 D AppUp4:CustFacade: isPhone : true
08-18 14:10:20.061  7137  7137 D AppUp4:CustModeStarterReceiver: begin check event
08-18 14:10:20.061  7137  7137 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-18 14:10:20.061  7361  7377 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-18 14:10:20.061  7361  7377 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-18 14:10:20.061  7361  7377 I Adreno-EGL: Build Date: 12/12/14 금
08-18 14:10:20.061  7361  7377 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-18 14:10:20.061  7361  7377 I Adreno-EGL: Remote Branch: 
08-18 14:10:20.061  7361  7377 I Adreno-EGL: Local Patches: 
08-18 14:10:20.061  7361  7377 I Adreno-EGL: Reconstruct Branch: 
08-18 14:10:20.064  4340  4340 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-18 14:10:20.064  4340  4340 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-18 14:10:20.065  4340  4340 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-18 14:10:20.067  4340  4340 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-18 14:10:20.070  4340  7448 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-18 14:10:20.073  7172  7172 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-18 14:10:20.074  4340  7449 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-18 14:10:20.074  4340  7449 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-18 14:10:20.084  7172  7451 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-18 14:10:20.099  3466  3466 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-18 14:10:20.099  3466  3466 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-18 14:10:20.099  3466  3466 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-18 14:10:20.102  7214  7214 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-18 14:10:20.102  7024  7453 W FormManager: Network not available. Please check & try again.
08-18 14:10:20.102  7214  7214 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-18 14:10:20.109  7278  7278 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:10:20
08-18 14:10:20.109  7278  7278 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-18 14:10:20.109  7278  7278 D Weather.Utils: 2 : All the weather widget is gone.
08-18 14:10:20.110  7024  7454 V FormManager: Network unavailable.
08-18 14:10:20.110  7278  7278 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-18 14:10:20.110  7278  7278 D WeatherAncestor: connectivity changed - connection : true
08-18 14:10:20.110  7278  7278 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@25449515
08-18 14:10:20.110  7278  7278 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-18 14:10:20.110  7278  7278 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-18 14:10:20.110  7278  7278 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-18 14:10:20.110  7278  7278 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-18 14:10:20.111  7278  7278 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:10:20
,08-18 14:10:20.116  7024  7454 V FormManager: Network unavailable.
08-18 14:10:20.117  7196  7196 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-18 14:10:20.117  1034  7205 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-18 14:10:20.117  1034  7205 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-TERMINATING 
08-18 14:10:20.117  1034  7205 D WifiMonitor: Disconnecting from the supplicant, no more events
08-18 14:10:20.118  1034  1540 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 45 0
08-18 14:10:20.140  6913  6913 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,08-18 14:10:20.140  6913  6913 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-18 14:10:20.140  6913  6913 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-18 14:10:20.140  6913  6913 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-18 14:10:20.141  6913  6913 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-18 14:10:20.143  6913  6913 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-18 14:10:20.143  6913  6913 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-18 14:10:20.143  6913  6913 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-18 14:10:20.143  6913  6913 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-18 14:10:20.144  6913  6913 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-18 14:10:20.144  6913  6913 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-18 14:10:20.150  6956  6956 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-18 14:10:20.153  6913  6913 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-18 14:10:20.157  7024  7462 W FormManager: Network not available. Please check & try again.
08-18 14:10:20.158  6913  6913 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-18 14:10:20.163  7024  7463 V FormManager: Network unavailable.
08-18 14:10:20.166  7024  7463 V FormManager: Network unavailable.
,08-18 14:10:20.170  6956  6956 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-18 14:10:20.173  6913  6913 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-18 14:10:20.177  7024  7464 W FormManager: Network not available. Please check & try again.
08-18 14:10:20.177  6913  6913 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-18 14:10:20.188  7024  7465 V FormManager: Network unavailable.
,08-18 14:10:20.191  4340  4340 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-18 14:10:20.191  4340  4340 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-18 14:10:20.191  7024  7465 V FormManager: Network unavailable.
08-18 14:10:20.192  4340  4340 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-18 14:10:20.193  4340  4340 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-18 14:10:20.199  4340  7466 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-18 14:10:20.204  4340  7467 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-18 14:10:20.204  4340  7467 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-18 14:10:20.232  1034  1989 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7468 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
08-18 14:10:20.233  1034  1540 D WifiOffDelayIfNotUsed: stopMonitoring
08-18 14:10:20.234  1034  1540 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-18 14:10:20.234  1034  1540 E WifiStateMachine: useWiFiOffloading() : false
08-18 14:10:20.234  1034  1540 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-18 14:10:20.236  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-18 14:10:20.236  1034  1545 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-18 14:10:20.236  1034  1545 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-18 14:10:20.236  1944  1944 D WfdsService: Supplicant Connection state is changed : false
08-18 14:10:20.236  1944  2342 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-18 14:10:20.236  1944  2342 D WfdsService: Set the WFDS Monitor: false
08-18 14:10:20.236  1944  2342 D WfdsMonitor: WFDS Monitor is stopped
08-18 14:10:20.237  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-18 14:10:20.237  1944  1944 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-18 14:10:20.240  2503  2503 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-18 14:10:20.240  6817  6817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-18 14:10:20.240  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-18 14:10:20.240  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 14:10:20.240  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-18 14:10:20.240  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-18 14:10:20.240  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-18 14:10:20.240  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-18 14:10:20.240  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-18 14:10:20.240  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-18 14:10:20.241  6817  6817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-18 14:10:20.241  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-18 14:10:20.241  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 14:10:20.241  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-18 14:10:20.241  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-18 14:10:20.241  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-18 14:10:20.241  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-18 14:10:20.241  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-18 14:10:20.241  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-18 14:10:20.316  7468  7468 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-18 14:10:20.316  7468  7468 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-18 14:10:20.321  7468  7468 V [BNRBootReceiver]: Boot Receiver Return
08-18 14:10:20.322  7468  7468 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-18 14:10:20.324  6505  6505 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-18 14:10:20.329  6913  6913 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-18 14:10:20.335  6913  6913 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-18 14:10:20.338   309  7487 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-18 14:10:20.338  1034  1099 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-18 14:10:20.338  1820  7312 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,08-18 14:10:20.343  6984  6984 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-18 14:10:20.343  6984  6984 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-18 14:10:20.344  6984  6984 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-18 14:10:20.348  1820  7312 I CheckinService: active receiver: disabled
08-18 14:10:20.348  6505  6505 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-18 14:10:20.365  6913  6913 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-18 14:10:20.371  6913  6913 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-18 14:10:20.377  6984  6984 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-18 14:10:20.377  6984  6984 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-18 14:10:20.378  6984  6984 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-18 14:10:20.382  6913  6913 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-18 14:10:20.385  6913  6913 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-18 14:10:20.390  6505  6505 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-18 14:10:20.403  6913  6913 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-18 14:10:20.412  6913  6913 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-18 14:10:20.422  6984  6984 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-18 14:10:20.423  6984  6984 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-18 14:10:20.424  6984  6984 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-18 14:10:20.428  6505  6505 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-18 14:10:20.443  6913  6913 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-18 14:10:20.457  6913  6913 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-18 14:10:20.471  6984  6984 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-18 14:10:20.472  6984  6984 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-18 14:10:20.473  6984  6984 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-18 14:10:20.481  6505  6505 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-18 14:10:20.503  6913  6913 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-18 14:10:20.520  6913  6913 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-18 14:10:20.545  6984  6984 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-18 14:10:20.547  6984  6984 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-18 14:10:20.548  6984  6984 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-18 14:10:20.553  1034  1901 I ActivityManager: Killing 6934:com.lge.lifetracker/u0a37 (adj 15): empty #17
08-18 14:10:20.557  1034  1540 E WifiStateMachine:  InitialState CMD_START_SCAN -2 -2 ic=1 proc(ms):6 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=20000 [on:0 tx:0 rx:0 period:2092] from screen [on:0 period:-1651561971]
08-18 14:10:20.559  1034  1540 E WifiStateMachine:  DefaultState CMD_START_SCAN -2 -2 ic=1 proc(ms):8 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=20000 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1651561969]
,08-18 14:10:20.588  1034  1935 W libprocessgroup: failed to open /acct/uid_10037/pid_6934/cgroup.procs: No such file or directory
,08-18 14:10:20.594   309  7492 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-18 14:10:20.595  1034  1099 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-18 14:10:20.602  6505  6505 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-18 14:10:20.604  1034  1034 D PowerManagerServiceEx: releaseWakeLockInternal: lock=299530809 [*alarm*], flags=0x0
08-18 14:10:20.618  6913  6913 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-18 14:10:20.624  6913  6913 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-18 14:10:20.631  6984  6984 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-18 14:10:20.632  6984  6984 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-18 14:10:20.632  6984  6984 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-18 14:10:20.638  6505  6505 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-18 14:10:20.648  6913  6913 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-18 14:10:20.654  6913  6913 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-18 14:10:20.662  6984  6984 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-18 14:10:20.663  6984  6984 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-18 14:10:20.663  6984  6984 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-18 14:10:20.672  6505  6505 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-18 14:10:20.688  6913  6913 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-18 14:10:20.698  6913  6913 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-18 14:10:20.711  6984  6984 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-18 14:10:20.712  6984  6984 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-18 14:10:20.721  6984  6984 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-18 14:10:20.731  6505  6505 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-18 14:10:20.744  6913  6913 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-18 14:10:20.752  6913  6913 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-18 14:10:20.762  6984  6984 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-18 14:10:20.763  6984  6984 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-18 14:10:20.764  6984  6984 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-18 14:10:20.768  6505  6505 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-18 14:10:20.774  6956  6956 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-18 14:10:20.785  1034  1546 D WifiService: New client listening to asynchronous messages
,08-18 14:10:20.785  6956  6956 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-18 14:10:20.791  6913  6913 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-18 14:10:20.798  6913  6913 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-18 14:10:20.805  6711  7112 D UEI.SmartControl: Internal timer expired: 4
08-18 14:10:20.805  6711  7112 D UEI.SmartControl: unbind internal service
08-18 14:10:20.812  6984  6984 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-18 14:10:20.813  6984  6984 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-18 14:10:20.815  6984  6984 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-18 14:10:20.817  6984  6984 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-18 14:10:20.818  6984  6984 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,08-18 14:10:20.830  6505  6505 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-18 14:10:20.842  6956  6956 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-18 14:10:20.847  6956  6956 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-18 14:10:20.855  6913  6913 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-18 14:10:20.868  6913  6913 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-18 14:10:20.883  6711  7106 D serial_port: close(fd = 24)
,08-18 14:10:20.885  6984  6984 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-18 14:10:20.886  6984  6984 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-18 14:10:20.888  6984  6984 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-18 14:10:20.890  6984  6984 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-18 14:10:20.891  6711  7106 I UEI.SmartControl: Serial port is closed.
08-18 14:10:20.891  6984  6984 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-18 14:10:20.903  2161  2161 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,08-18 14:10:20.919  2161  2161 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-18 14:10:20.919  2161  2161 D c       : Getting all permits...
08-18 14:10:20.919  2161  2161 D a       : Opening database...
08-18 14:10:20.924  2161  2161 D a       : Opening database auth.proximity.permit_store...
08-18 14:10:20.925  2161  2161 D a       : Closing database...
08-18 14:10:20.942  6505  6505 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-18 14:10:20.947  6956  6956 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-18 14:10:20.947  6956  6956 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-18 14:10:20.947  6956  6956 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-18 14:10:20.953  6913  6913 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-18 14:10:20.960  6913  6913 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-18 14:10:20.967  6984  6984 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-18 14:10:20.967  6984  6984 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-18 14:10:20.970  6984  6984 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-18 14:10:20.976  6505  6505 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-18 14:10:20.982  6956  6956 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-18 14:10:20.983  6956  6956 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-18 14:10:20.983  6956  6956 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-18 14:10:20.986  6913  6913 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-18 14:10:20.993  6913  6913 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-18 14:10:21.000  6984  6984 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-18 14:10:21.000  6984  6984 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-18 14:10:21.002  6984  6984 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-18 14:10:21.007  6505  6505 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-18 14:10:21.012  6956  6956 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-18 14:10:21.012  6956  6956 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-18 14:10:21.012  6956  6956 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-18 14:10:21.019  6913  6913 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-18 14:10:21.028  6913  6913 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-18 14:10:21.037  6984  6984 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-18 14:10:21.038  6984  6984 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-18 14:10:21.040  6984  6984 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-18 14:10:21.058  6956  6956 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-18 14:10:21.066  6913  6913 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-18 14:10:21.076  7024  7497 W FormManager: Network not available. Please check & try again.
08-18 14:10:21.079  7024  7498 V FormManager: Network unavailable.
08-18 14:10:21.079  6913  6913 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-18 14:10:21.088  7024  7498 V FormManager: Network unavailable.
,08-18 14:10:21.101  4340  4340 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-18 14:10:21.101  4340  4340 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-18 14:10:21.103  4340  4340 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-18 14:10:21.105  4340  4340 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-18 14:10:21.115  6956  6956 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-18 14:10:21.115  6956  6956 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-18 14:10:21.115  6956  6956 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-18 14:10:21.116  4340  7499 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-18 14:10:21.118  6913  6913 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-18 14:10:21.125  4340  7503 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
,08-18 14:10:21.125  4340  7503 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-18 14:10:21.130  6913  6913 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-18 14:10:21.130  7024  7501 W FormManager: Network not available. Please check & try again.
08-18 14:10:21.137  7024  7502 V FormManager: Network unavailable.
,08-18 14:10:21.145  7024  7502 V FormManager: Network unavailable.
08-18 14:10:21.147  2161  2161 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
08-18 14:10:21.466  1034  1540 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:906] from screen [on:0 period:-1651561062] gl rssi=-49 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-18 14:10:21.467  1034  1540 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1651561061] gl rssi=-49 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-18 14:10:21.732  1034  1547 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-18 14:10:21.748  1034  1101 D Tethering: MasterInitialState.processMessage what=3
08-18 14:10:21.756  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-18 14:10:21.760  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 14:10:21.763  1034  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-18 14:10:21.767  6505  6505 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-18 14:10:21.768  6505  6955 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-18 14:10:21.780  5802  5802 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-18 14:10:21.799  2161  2161 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-18 14:10:21.818  7137  7137 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-18 14:10:21.818  7137  7137 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-18 14:10:21.819  7137  7137 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-18 14:10:21.819  7137  7137 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-18 14:10:21.823  7137  7137 I AppUp4:CustModeStarterReceiver: onReceive
08-18 14:10:21.827  7137  7137 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@3ef530ff
08-18 14:10:21.827  7137  7137 D AppUp4:CustFacade: isCustomizationCompleted : false
08-18 14:10:21.827  7137  7137 D AppUp4:CustFacade: isPhone : true
08-18 14:10:21.828  7137  7137 D AppUp4:CustModeStarterReceiver: begin check event
08-18 14:10:21.828  7137  7137 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-18 14:10:21.833  4340  4340 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-18 14:10:21.833  4340  4340 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-18 14:10:21.834  4340  4340 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-18 14:10:21.840  4340  4340 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-18 14:10:21.848  7172  7172 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-18 14:10:21.878  3466  3466 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-18 14:10:21.878  3466  3466 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-18 14:10:21.878  3466  3466 I LgeMiscReceiver: networkInfo.isConnected() = true
08-18 14:10:21.878  3466  3466 D PhoneState: setPdpRejectCasuse : false
,08-18 14:10:21.884  7214  7214 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-18 14:10:21.884  7214  7214 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-18 14:10:21.898  1034  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-18 14:10:21.906  4340  7512 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-18 14:10:21.914  4340  7527 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-18 14:10:21.915  4340  7527 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-18 14:10:21.921  7024  7526 W FormManager: Network not available. Please check & try again.
08-18 14:10:21.921  7278  7278 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:10:21
08-18 14:10:21.923  7172  7511 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-18 14:10:21.925  7278  7278 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-18 14:10:21.925  7278  7278 D Weather.Utils: 2 : All the weather widget is gone.
08-18 14:10:21.926  7278  7278 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-18 14:10:21.926  7278  7278 D WeatherAncestor: connectivity changed - connection : true
08-18 14:10:21.926  7278  7278 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@25449515
08-18 14:10:21.927  7278  7278 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-18 14:10:21.927  7278  7278 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-18 14:10:21.927  7278  7278 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-18 14:10:21.927  7278  7278 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-18 14:10:21.928  7278  7278 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:10:21
,08-18 14:10:21.927  7024  7529 V FormManager: Network unavailable.
,08-18 14:10:21.938  7024  7529 V FormManager: Network unavailable.
08-18 14:10:22.800  1034  2054 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-18 14:10:22.801  1034  2054 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-18 14:10:22.833  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-18 14:10:22.834  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-18 14:10:22.834  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-18 14:10:22.834  1034  1101 D BluetoothManagerService: Message: 1
08-18 14:10:22.834  1034  1101 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-18 14:10:22.861  1034  1101 D BluetoothManagerService: Message: 20
08-18 14:10:22.861  1034  1101 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@179c6c6:true
,08-18 14:10:22.865  7056  7056 D BluetoothAdapterState: make
08-18 14:10:22.879  7056  7056 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-18 14:10:22.879  7056  7056 I bluedroid-qcom: init
,08-18 14:10:22.883  7056  7543 I BluetoothAdapterState: Entering OffState
08-18 14:10:22.883  7056  7056 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-18 14:10:22.884  7056  7056 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-18 14:10:22.884  7056  7056 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-18 14:10:22.884  7056  7056 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-18 14:10:22.884  7056  7056 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-18 14:10:22.886  1034  1547 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-18 14:10:22.884  7546  7546 W bdaddr_loader: type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-18 14:10:22.892  1034  1101 D Tethering: MasterInitialState.processMessage what=3
08-18 14:10:22.884  7546  7546 W bdaddr_loader: type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-18 14:10:22.907  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-18 14:10:22.910  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 14:10:22.912  7546  7546 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-18 14:10:22.912  7546  7546 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-18 14:10:22.912  7546  7546 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-18 14:10:22.913  1034  1547 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-18 14:10:22.914  7546  7546 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-18 14:10:22.920  7546  7546 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-18 14:10:22.920  7546  7546 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
,08-18 14:10:22.924  1034  1101 D Tethering: MasterInitialState.processMessage what=3
08-18 14:10:22.925  7056  7056 I bluedroid-qcom: get_profile_interface socket
08-18 14:10:22.925  7056  7056 I bluedroid-qcom: get_profile_interface map_client
08-18 14:10:22.929  7056  7547 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-18 14:10:22.931  7056  7547 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-18 14:10:22.939  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-18 14:10:22.942  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 14:10:22.945  1034  1034 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-18 14:10:22.945  1034  1101 D BluetoothManagerService: Message: 40
08-18 14:10:22.945  1034  1101 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-18 14:10:22.946  7056  7071 I bluedroid-qcom: config_hci_snoop_log
08-18 14:10:22.948  1034  1101 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-18 14:10:22.948  1034  1101 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-18 14:10:22.952  7056  7547 D BluetoothAdapterProperties: Name is: G3
,08-18 14:10:22.959  7056  7543 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-18 14:10:22.959  7056  7543 D BluetoothAdapterProperties: Setting state to 11
,08-18 14:10:22.960  7056  7543 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-18 14:10:22.962  1034  1101 D BluetoothManagerService: Message: 60
08-18 14:10:22.962  1034  1101 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
,08-18 14:10:22.962  1034  1101 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-18 14:10:22.965  7056  7543 I LGBluetoothServiceJni: classInitNative: succeeds
,08-18 14:10:22.972  1034  1034 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-18 14:10:22.972  1034  1034 D BluetoothManagerService: Stored Bluetooth name: G3
,08-18 14:10:22.974  1944  1944 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-18 14:10:22.975  6505  6505 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-18 14:10:22.976  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-18 14:10:22.977  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 14:10:22.979  6505  6955 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-18 14:10:22.982  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 14:10:22.984  1034  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-18 14:10:22.987  6913  6913 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-18 14:10:23.000  5802  5802 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-18 14:10:23.000  7056  7543 D BluetoothBondStateMachine: make
08-18 14:10:23.005  7056  7056 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-18 14:10:23.006  7056  7056 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-18 14:10:23.006  5802  5802 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-18 14:10:23.006  7056  7056 V BluetoothPbapReceiver: ***********state = 11
08-18 14:10:23.009  7056  7543 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25449515
08-18 14:10:23.009  7056  7543 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-18 14:10:23.009  7056  7543 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25449515
08-18 14:10:23.009  7056  7543 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-18 14:10:23.010  7056  7543 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-18 14:10:23.011  7056  7565 I BluetoothBondStateMachine: StableState(): Entering Off State
08-18 14:10:23.012  2161  2161 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-18 14:10:23.014  7056  7543 E BluetoothAdapterService: File transfer profiles supported!!
08-18 14:10:23.021  7056  7543 E BluetoothAdapterService: File transfer profiles supported!!
08-18 14:10:23.023  7056  7056 D HeadsetService: Received start request. Starting profile...
08-18 14:10:23.023  7056  7056 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-18 14:10:23.024  7056  7056 D LGBluetoothHfpAdapter: Version 1.6
08-18 14:10:23.028  7056  7056 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-18 14:10:23.029  7056  7056 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-18 14:10:23.030  7056  7056 D HeadsetStateMachine: make
08-18 14:10:23.036  7056  7543 E BluetoothAdapterService: File transfer profiles supported!!
08-18 14:10:23.061  1034  2023 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7568 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-18 14:10:23.068  7056  7543 E BluetoothAdapterService: File transfer profiles supported!!
08-18 14:10:23.071  7056  7056 D LgDataFeature: LgDataFeature() Constructor: none
08-18 14:10:23.071  7056  7056 D LgDataFeature: LgDataFeature() Constructor Done, null
08-18 14:10:23.074  2161  2161 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-18 14:10:23.077  7056  7543 E BluetoothAdapterService: File transfer profiles supported!!
,08-18 14:10:23.081  1034  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-18 14:10:23.081  7056  7056 D HeadsetStateMachine: max_hf_connections = 1
08-18 14:10:23.081  7056  7056 I bluedroid-qcom: get_profile_interface handsfree
08-18 14:10:23.081  1034  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-18 14:10:23.081  1034  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-18 14:10:23.082  7056  7056 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-18 14:10:23.084   314  2148 V AudioPolicyService: registerClient() client 0xb558ab20, uid 1002
08-18 14:10:23.084   314  2149 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-18 14:10:23.084   314  2149 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-18 14:10:23.084   314  2149 V AudioPolicyManagerEx: getOutput() returns output 2
,08-18 14:10:23.084  7056  7056 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-18 14:10:23.085   314   314 V AudioFlinger: registerClient() client 0xb55816b8, pid 7056
08-18 14:10:23.085   314  1381 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-18 14:10:23.085   314  1381 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-18 14:10:23.086   314  1379 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-18 14:10:23.086   314  1379 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-18 14:10:23.086  7056  7072 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-18 14:10:23.086  7056  7072 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-18 14:10:23.086  7056  7072 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-18 14:10:23.086  7056  7056 V ToneGenerator: Create Track: 0xb4928a80
08-18 14:10:23.086  7056  7056 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-18 14:10:23.086  7056  7072 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-18 14:10:23.086  7056  7056 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-18 14:10:23.086  1605  1630 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-18 14:10:23.086  1855  1870 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-18 14:10:23.086  1605  1630 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-18 14:10:23.086  1855  1870 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-18 14:10:23.086  1605  1630 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-18 14:10:23.086  1855  1870 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-18 14:10:23.087  1605  1630 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-18 14:10:23.087  1855  1870 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-18 14:10:23.087  1034  1050 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-18 14:10:23.087  1034  1050 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-18 14:10:23.087  3466  3488 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-18 14:10:23.087  3466  3488 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-18 14:10:23.087   314  1385 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-18 14:10:23.087  3466  3488 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-18 14:10:23.087   314  1385 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-18 14:10:23.087   314  1385 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-18 14:10:23.087  3466  3488 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-18 14:10:23.087   314  1385 V AudioPolicyManagerEx: getOutput() returns output 2
08-18 14:10:23.087  1034  1050 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-18 14:10:23.087  1034  1050 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-18 14:10:23.087   314  2148 I AudioFlinger: isAudioPlaybackHookOn() false
08-18 14:10:23.087   314  2149 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-18 14:10:23.087   314  2149 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-18 14:10:23.087   314  2149 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
,08-18 14:10:23.087   314  2149 V AudioPolicyManagerEx: getOutput() returns output 2
08-18 14:10:23.087  7056  7056 V AudioSystem: getLatency() output 2, latency 50
08-18 14:10:23.087  7056  7056 V AudioSystem: getFrameCount() output 2, frameCount 960
08-18 14:10:23.087  7056  7056 V AudioTrack: createTrack_l() output 2 afLatency 50
08-18 14:10:23.088   314  2148 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-18 14:10:23.088   314  2148 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-18 14:10:23.088   314  2148 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-18 14:10:23.088   314  2148 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-18 14:10:23.088   314  2148 V AudioFlinger: createTrack() lSessionId: 22
08-18 14:10:23.093  7056  7056 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-18 14:10:23.094   314  1386 V AudioFlinger: acquiring 22 from 7056, for 7056
08-18 14:10:23.094   314  1386 V AudioFlinger:  added new entry for 22
08-18 14:10:23.094  7056  7056 V ToneGenerator: ToneGenerator INIT OK, time: 203838
08-18 14:10:23.094  7056  7056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25449515
08-18 14:10:23.095  7056  7567 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-18 14:10:23.095  7056  7567 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-18 14:10:23.095  7056  7567 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-18 14:10:23.095  7056  7567 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-18 14:10:23.096   314   314 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7056
08-18 14:10:23.096  7056  7056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25449515
08-18 14:10:23.097   314   314 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-18 14:10:23.097   314   314 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-18 14:10:23.097   314   314 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-18 14:10:23.097   314   314 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-18 14:10:23.097   314   314 V voice   : voice_set_parameters: exit with code(0)
08-18 14:10:23.097   314   314 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-18 14:10:23.097   314   314 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-18 14:10:23.097   314   314 V msm8974_platform: platform_set_parameters: exit with code(0)
08-18 14:10:23.097   314   314 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-18 14:10:23.097   314   314 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-18 14:10:23.097   314   314 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-18 14:10:23.098  7056  7567 V ToneGenerator: ToneGenerator destructor
08-18 14:10:23.098  7056  7567 V ToneGenerator: stopTone
08-18 14:10:23.098  7056  7567 V ToneGenerator: Delete Track: 0xb4928a80
08-18 14:10:23.098  7056  7056 D A2dpService: Received start request. Starting profile...
08-18 14:10:23.099  7056  7543 E BluetoothAdapterService: File transfer profiles supported!!
08-18 14:10:23.099  7056  7056 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-18 14:10:23.099  7056  7567 V AudioTrack: ~AudioTrack, releasing session id from 7056 on behalf of 7056
08-18 14:10:23.099   314  2148 V AudioFlinger: releasing 22 from 7056 for 7056
08-18 14:10:23.099   314  2148 V AudioFlinger:  decremented refcount to 0
08-18 14:10:23.100   314  2148 V AudioFlinger: purging stale effects
08-18 14:10:23.100   314  2148 V AudioPolicyService: AudioCommandThread() adding release output 2
08-18 14:10:23.100   314  2148 V AudioPolicyService:, inserting command: 6 at index 0, num commands 0
08-18 14:10:23.100   314  1259 V AudioPolicyService: AudioCommandThread() waking up
08-18 14:10:23.100   314  1259 V AudioPolicyService: AudioCommandThread() processing release output 2
08-18 14:10:23.100   314  1259 V AudioPolicyManager: releaseOutput() 2
08-18 14:10:23.100   314  1259 V AudioPolicyService: AudioCommandThread() going to sleep
08-18 14:10:23.100   314  2148 V AudioFlinger: PlaybackThread::Track destructor
08-18 14:10:23.100   314  2148 V AudioFlinger: removeClient_l() pid 7056, calling pid 314
08-18 14:10:23.100  7137  7137 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-18 14:10:23.100  7137  7137 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-18 14:10:23.100  7137  7137 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-18 14:10:23.100  7056  7056 V Avrcp   : make
08-18 14:10:23.100  7137  7137 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-18 14:10:23.101  7056  7056 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-18 14:10:23.101  7056  7056 I bluedroid-qcom: get_profile_interface avrcp
08-18 14:10:23.103  7056  7543 E BluetoothAdapterService: File transfer profiles supported!!
08-18 14:10:23.105  7137  7137 I AppUp4:CustModeStarterReceiver: onReceive
08-18 14:10:23.115  7056  7543 V LGMDMManager: Create singleton instance
08-18 14:10:23.115  7137  7137 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@3ef530ff
08-18 14:10:23.116  7137  7137 D AppUp4:CustFacade: isCustomizationCompleted : false
08-18 14:10:23.116  7137  7137 D AppUp4:CustFacade: isPhone : true
08-18 14:10:23.116  7137  7137 D AppUp4:CustModeStarterReceiver: begin check event
08-18 14:10:23.116  7137  7137 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-18 14:10:23.118  7056  7056 V AudioManager: registerRemoteController: size of Media player list: 0
08-18 14:10:23.120  7056  7056 E AudioManager: No RCC entry present to update
08-18 14:10:23.120  7056  7056 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-18 14:10:23.120  4340  4340 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-18 14:10:23.120  4340  4340 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-18 14:10:23.120  7056  7543 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-18 14:10:23.121  4340  4340 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-18 14:10:23.122  7056  7056 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-18 14:10:23.123  7056  7056 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-18 14:10:23.123  7056  7056 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-18 14:10:23.126  4340  4340 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-18 14:10:23.126  7056  7056 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-18 14:10:23.130  4340  7589 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-18 14:10:23.133  4340  7590 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-18 14:10:23.133  4340  7590 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-18 14:10:23.179  7172  7172 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-18 14:10:23.197  7172  7591 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-18 14:10:23.206  3466  3466 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-18 14:10:23.206  3466  3466 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-18 14:10:23.206  3466  3466 I LgeMiscReceiver: networkInfo.isConnected() = false
08-18 14:10:23.208  7214  7214 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-18 14:10:23.209  7214  7214 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-18 14:10:23.211  7568  7568 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-18 14:10:23.211  7568  7568 W LG Account v2.2: No ProfileInfo entries
08-18 14:10:23.211  7568  7568 I LG Account v2.2: isEnabled: false
08-18 14:10:23.212  7568  7568 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-18 14:10:23.212  7568  7568 I Feature : [Lifetracker]Country: EU
08-18 14:10:23.212  7568  7568 I Feature : [Lifetracker]Operator: OPEN
08-18 14:10:23.212  7568  7568 I Feature : [Lifetracker]Ranking support: false
08-18 14:10:23.212  7568  7568 I Feature : [Lifetracker]Comfort support: false
08-18 14:10:23.212  7568  7568 I Feature : [Lifetracker]Accessory: true
08-18 14:10:23.212  7568  7568 I Feature : [Lifetracker]Health device: true
08-18 14:10:23.212  7568  7568 I Feature : [Lifetracker]Extra Pedometer: false
08-18 14:10:23.212  7568  7568 I Feature : [Lifetracker]Blood glucose device: false
08-18 14:10:23.212  7568  7568 I Feature : [Lifetracker]Device Number: 3
08-18 14:10:23.214  7024  7593 W FormManager: Network not available. Please check & try again.
08-18 14:10:23.223  7024  7595 V FormManager: Network unavailable.
08-18 14:10:23.225  7278  7278 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:10:23
,08-18 14:10:23.227  6913  6913 D BluetoothPermissionRequest: onReceive
08-18 14:10:23.229  1034  1901 V SIM_STK : Menu title from STK is T-Mobile
08-18 14:10:23.229  1034  1901 V SIM_STK : Menu title from STK is T-Mobile
08-18 14:10:23.231  6913  6913 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-18 14:10:23.233  7278  7278 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-18 14:10:23.233  7278  7278 D Weather.Utils: 2 : All the weather widget is gone.
08-18 14:10:23.234  7278  7278 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-18 14:10:23.234  7278  7278 D WeatherAncestor: connectivity changed - connection : true
08-18 14:10:23.234  7278  7278 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@25449515
08-18 14:10:23.234  7024  7595 V FormManager: Network unavailable.
08-18 14:10:23.235  7278  7278 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-18 14:10:23.235  7278  7278 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-18 14:10:23.235  7278  7278 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-18 14:10:23.235  7278  7278 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-18 14:10:23.235  7278  7278 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:10:23
,08-18 14:10:23.254  6505  6505 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-18 14:10:23.255  6505  6955 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-18 14:10:23.263  2161  2161 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-18 14:10:23.268  7137  7137 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-18 14:10:23.268  7137  7137 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-18 14:10:23.268  7137  7137 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
,08-18 14:10:23.268  7137  7137 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-18 14:10:23.270  7137  7137 I AppUp4:CustModeStarterReceiver: onReceive
08-18 14:10:23.272  7137  7137 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@3ef530ff
08-18 14:10:23.272  7137  7137 D AppUp4:CustFacade: isCustomizationCompleted : false
08-18 14:10:23.273  7137  7137 D AppUp4:CustFacade: isPhone : true
08-18 14:10:23.273  7137  7137 D AppUp4:CustModeStarterReceiver: begin check event
08-18 14:10:23.273  7137  7137 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-18 14:10:23.275  4340  4340 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-18 14:10:23.275  4340  4340 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-18 14:10:23.277  4340  4340 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-18 14:10:23.279  4340  4340 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-18 14:10:23.282  4340  7598 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-18 14:10:23.285  4340  7599 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-18 14:10:23.285  4340  7599 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-18 14:10:23.285  7172  7172 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-18 14:10:23.294  1034  1989 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-18 14:10:23.301  7172  7600 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-18 14:10:23.302  7024  7602 W FormManager: Network not available. Please check & try again.
08-18 14:10:23.302  7056  7056 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-18 14:10:23.307  7056  7056 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-18 14:10:23.308  3466  3466 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-18 14:10:23.308  3466  3466 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
,08-18 14:10:23.308  3466  3466 I LgeMiscReceiver: networkInfo.isConnected() = false
08-18 14:10:23.308  7056  7056 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-18 14:10:23.308  7056  7056 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-18 14:10:23.308  7056  7056 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-18 14:10:23.308  7056  7056 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-18 14:10:23.308  7056  7056 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-18 14:10:23.308  7056  7056 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-18 14:10:23.308  7056  7056 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-18 14:10:23.308  7056  7056 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-18 14:10:23.309  7056  7056 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-18 14:10:23.309  7056  7056 I BluetoothA2dpServiceJni: classInitNative
08-18 14:10:23.309  7056  7056 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-18 14:10:23.309  7056  7056 D A2dpStateMachine: make
08-18 14:10:23.311  7214  7214 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-18 14:10:23.311  7214  7214 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-18 14:10:23.311  7056  7056 I bluedroid-qcom: get_profile_interface a2dp
08-18 14:10:23.311  7056  7606 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-18 14:10:23.313  7056  7056 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-18 14:10:23.313  7056  7056 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-18 14:10:23.314  7056  7056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25449515
08-18 14:10:23.314  7056  7605 D A2dpStateMachine: Enter Disconnected: -2
08-18 14:10:23.315  7056  7056 I BluetoothHidServiceJni: classInitNative: succeeds
08-18 14:10:23.316  7056  7056 D HidService: Received start request. Starting profile...
08-18 14:10:23.316  7056  7056 I bluedroid-qcom: get_profile_interface hidhost
08-18 14:10:23.316  7056  7056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25449515
08-18 14:10:23.317  7056  7056 I BluetoothHealthServiceJni: classInitNative: succeeds
08-18 14:10:23.318  7056  7056 D HealthService: Received start request. Starting profile...
08-18 14:10:23.318  7024  7603 V FormManager: Network unavailable.
08-18 14:10:23.319  7056  7056 I bluedroid-qcom: get_profile_interface health
08-18 14:10:23.320  7056  7056 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-18 14:10:23.320  7056  7056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25449515
08-18 14:10:23.320  7056  7056 D HeadsetStateMachine: Proxy object connected
08-18 14:10:23.320  7056  7056 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-18 14:10:23.321  7056  7056 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-18 14:10:23.322  7278  7278 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:10:23
08-18 14:10:23.322  7056  7056 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-18 14:10:23.326  7056  7056 D PanService: Received start request. Starting profile...
08-18 14:10:23.326  7056  7056 D BluetoothPanServiceJni: initializeNative(L110): pan
08-18 14:10:23.327  7056  7056 I bluedroid-qcom: get_profile_interface pan
08-18 14:10:23.327  7024  7603 V FormManager: Network unavailable.
08-18 14:10:23.328  7278  7278 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-18 14:10:23.328  7278  7278 D Weather.Utils: 2 : All the weather widget is gone.
08-18 14:10:23.329  7278  7278 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-18 14:10:23.329  7278  7278 D WeatherAncestor: connectivity changed - connection : true
08-18 14:10:23.329  7278  7278 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@25449515
08-18 14:10:23.330  7278  7278 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-18 14:10:23.330  7278  7278 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-18 14:10:23.330  7278  7278 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-18 14:10:23.330  7278  7278 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-18 14:10:23.330  7278  7278 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:10:23
08-18 14:10:23.333  7056  7056 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-18 14:10:23.334  7056  7056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25449515
,08-18 14:10:23.339  7056  7056 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-18 14:10:23.339  7056  7567 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-18 14:10:23.340  7056  7567 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-18 14:10:23.340  7056  7567 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-18 14:10:23.340  7056  7056 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-18 14:10:23.347  7056  7056 D BtGatt.DebugUtils: handleDebugAction() action=null
08-18 14:10:23.348  7056  7056 D BtGatt.GattService: Received start request. Starting profile...
,08-18 14:10:23.348  7056  7056 D BtGatt.GattService: start()
08-18 14:10:23.348  7056  7056 I bluedroid-qcom: get_profile_interface gatt
08-18 14:10:23.349  7056  7056 D BtGatt.AdvertiseManager: advertise manager created
08-18 14:10:23.354  7056  7056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25449515
08-18 14:10:23.356  7056  7056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25449515
08-18 14:10:23.356  7056  7056 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-18 14:10:23.358  7056  7056 V BluetoothMapService: BluetoothMapBinder()
08-18 14:10:23.358  7056  7056 D BluetoothMapService: Received start request. Starting profile...
08-18 14:10:23.358  7056  7056 D BluetoothMapService: start()
08-18 14:10:23.362  7056  7056 D BluetoothMapEmailSettingsLoader: Found 0 applications
,08-18 14:10:23.362  7056  7056 D BluetoothMapEmailAppObserver: createReceiver()
08-18 14:10:23.363  7056  7056 D BluetoothMapEmailAppObserver: initObservers()
08-18 14:10:23.363  7056  7056 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-18 14:10:23.373  7056  7056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25449515
,08-18 14:10:23.377  7056  7056 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-18 14:10:23.380  7056  7056 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-18 14:10:23.383  7056  7056 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-18 14:10:23.384  7056  7056 V PanService: [BTUI] SIM Extra State :ABSENT
08-18 14:10:23.387  7056  7056 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-18 14:10:23.392  7056  7056 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
,08-18 14:10:23.392  7056  7056 V BluetoothMapService: Handler(): got msg=1
08-18 14:10:23.393  7056  7543 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-18 14:10:23.393  7056  7543 I bluedroid-qcom: enable
,08-18 14:10:23.394  7056  7613 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-18 14:10:23.394  7056  7613 I bt-btu  : btu_task pending for preload complete event
08-18 14:10:23.394  7056  7543 I bt_hci_bdroid: init
08-18 14:10:23.396  7056  7056 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-18 14:10:23.396  7056  7543 I bt_vendor: bt-vendor : init
08-18 14:10:23.396  7056  7543 I bt_vendor: bt-vendor : get_bt_soc_type
08-18 14:10:23.396  7056  7543 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-18 14:10:23.396  7056  7543 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-18 14:10:23.396  7056  7543 D bt_userial_mct: userial_init
08-18 14:10:23.397  7056  7543 D bt_hci_bdroid: set_power 1
08-18 14:10:23.397  7056  7543 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
,08-18 14:10:23.397  7056  7543 I bt_vendor: Starting hciattach daemon
08-18 14:10:23.397  7056  7543 I bt_vendor: try to set true
08-18 14:10:23.399  7056  7056 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-18 14:10:23.399  7056  7056 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-18 14:10:23.400  7056  7056 V BluetoothSapReceiver: SapReceiver onReceive 
08-18 14:10:23.400  7056  7056 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-18 14:10:23.400  7056  7056 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-18 14:10:23.394  7616  7616 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-18 14:10:23.394  7616  7616 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-18 14:10:23.432  7617  7617 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-18 14:10:23.533  7623  7623 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-18 14:10:23.547  7624  7624 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-18 14:10:23.576  7626  7626 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-18 14:10:23.589  7627  7627 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-18 14:10:23.602  7628  7628 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
08-18 14:10:23.617  7629  7629 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-18 14:10:23.647  7634  7634 I libmdmdetect: ESOC framework not supported
08-18 14:10:23.648  7634  7634 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-18 14:10:23.655  7634  7634 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-18 14:10:23.655  7634  7634 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-18 14:10:23.655  7634  7634 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-18 14:10:23.655  7634  7634 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-18 14:10:23.655  7634  7634 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-18 14:10:23.655  7634  7634 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-18 14:10:23.655  7634  7634 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-18 14:10:23.690  7634  7635 E QC-QMI  : qmi_client [7634] 14: failed to locate client data
,08-18 14:10:23.692   474   474 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-18 14:10:23.692   474   474 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
08-18 14:10:23.720  7639  7639 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-18 14:10:23.734  7640  7640 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-18 14:10:23.749  7056  7543 I bt_vendor: bluetooth satus is on
08-18 14:10:23.749  7056  7543 D bt_hci_bdroid: preload
,08-18 14:10:23.750  7056  7615 D bt_userial_mct: userial_open(port:0)
08-18 14:10:23.751  7056  7615 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-18 14:10:23.754  7056  7615 I bt_vendor: Done intiailizing UART
08-18 14:10:23.755  7056  7615 I bt_vendor: Done intiailizing UART
08-18 14:10:23.755  7056  7615 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-18 14:10:23.755  7056  7615 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-18 14:10:23.755  7056  7642 D bt_userial_mct: Entering userial_read_thread()
08-18 14:10:23.756  7056  7613 I bt-btu  : btu_task received preload complete event
08-18 14:10:23.756  7056  7613 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-18 14:10:23.757  7056  7613 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-18 14:10:23.759  7056  7613 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-18 14:10:23.763  7056  7613 I         : BTE_InitTraceLevels -- TRC_HCI
08-18 14:10:23.764  7056  7613 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-18 14:10:23.764  7056  7613 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-18 14:10:23.764  7056  7613 I         : BTE_InitTraceLevels -- TRC_AVDT
08-18 14:10:23.764  7056  7613 I         : BTE_InitTraceLevels -- TRC_AVRC
08-18 14:10:23.764  7056  7613 I         : BTE_InitTraceLevels -- TRC_A2D
08-18 14:10:23.764  7056  7613 I         : BTE_InitTraceLevels -- TRC_BNEP
08-18 14:10:23.764  7056  7613 I         : BTE_InitTraceLevels -- TRC_BTM
08-18 14:10:23.764  7056  7613 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-18 14:10:23.764  7056  7613 I         : BTE_InitTraceLevels -- TRC_GAP
08-18 14:10:23.764  7056  7613 I         : BTE_InitTraceLevels -- TRC_PAN
08-18 14:10:23.764  7056  7613 I         : BTE_InitTraceLevels -- TRC_SDP
08-18 14:10:23.764  7056  7613 I         : BTE_InitTraceLevels -- TRC_GATT
08-18 14:10:23.764  7056  7613 I         : BTE_InitTraceLevels -- TRC_SMP
08-18 14:10:23.764  7056  7613 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-18 14:10:23.764  7056  7613 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-18 14:10:23.798  1034  1092 W ProcessCpuTracker: Skipping unknown process pid 7553
08-18 14:10:23.798  1034  1092 W ProcessCpuTracker: Skipping unknown process pid 7554
,08-18 14:10:23.799  1034  1092 W ProcessCpuTracker: Skipping unknown process pid 7564
,08-18 14:10:23.800  1034  1092 W ProcessCpuTracker: Skipping unknown process pid 7587
,08-18 14:10:23.801  1034  1092 W ProcessCpuTracker: Skipping unknown process pid 7636
08-18 14:10:23.833  7056  7613 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-18 14:10:23.833  7056  7613 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0174061 
08-18 14:10:23.833  7056  7613 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0174061 
,08-18 14:10:23.859  7056  7547 E bt-btif : Calling BTA_HhEnable
08-18 14:10:23.859  7056  7547 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-18 14:10:23.860  7056  7547 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-18 14:10:23.862  7056  7613 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
,08-18 14:10:23.862  7056  7613 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
,08-18 14:10:23.862  7056  7613 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
,08-18 14:10:23.862  7056  7613 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-18 14:10:23.862  7056  7613 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-18 14:10:23.863  7056  7547 D BluetoothAdapterProperties: Name is: G3
08-18 14:10:23.865  1034  1034 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-18 14:10:23.866  1034  1034 D BluetoothManagerService: Stored Bluetooth name: G3
08-18 14:10:23.867  7056  7547 D BluetoothAdapterProperties: Scan Mode:20
08-18 14:10:23.867  7056  7547 D BluetoothAdapterProperties: Discoverable Timeout:120
08-18 14:10:23.868  7056  7547 D bt_hci_bdroid: postload
08-18 14:10:23.869  7056  7615 D bt_hci_bdroid: Used up Tx Cmd credits
08-18 14:10:23.870  7056  7613 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-18 14:10:23.870  7056  7547 D bte_conf: Device ID record 1 : primary
08-18 14:10:23.870  7056  7547 D bte_conf:   vendorId            = 00c4
08-18 14:10:23.870  7056  7547 D bte_conf:   vendorIdSource      = 0001
08-18 14:10:23.871  7056  7547 D bte_conf:   product             = 13a1
08-18 14:10:23.871  7056  7547 D bte_conf:   version             = 1000
08-18 14:10:23.871  7056  7547 D bte_conf:   clientExecutableURL = 
08-18 14:10:23.871  7056  7547 D bte_conf:   serviceDescription  = 
08-18 14:10:23.871  7056  7547 D bte_conf:   documentationURL    = 
08-18 14:10:23.871  7056  7547 D bte_conf: bte_load_did_conf no section named DID2.
08-18 14:10:23.872  7056  7615 D bt_hci_bdroid: Used up Tx Cmd credits
08-18 14:10:23.873  7056  7615 D bt_hci_bdroid: Used up Tx Cmd credits
08-18 14:10:23.873  7056  7615 D bt_hci_bdroid: Used up Tx Cmd credits
08-18 14:10:23.878  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 14:10:23.881  7056  7613 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
,08-18 14:10:23.886  7056  7642 E bt_mct  : hci lib postload completed
08-18 14:10:23.887  7056  7543 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-18 14:10:23.888  7056  7543 D BluetoothAdapterProperties: ScanMode =  20
08-18 14:10:23.888  7056  7543 D BluetoothAdapterProperties: State =  11
08-18 14:10:23.884  7056  7613 W bt-smp  : Plain text(LSB ~ MSB) = d1 6c 59 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-18 14:10:23.888  7056  7613 W bt-smp  : Encrypted text(LSB ~ MSB) = 0a 40 f4 c8 c4 1a a2 0b 2d 5d da b0 f8 84 e7 29 
08-18 14:10:23.888  7056  7543 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-18 14:10:23.888  7056  7613 W bt-btm  : Stopping oneshot timer
08-18 14:10:23.888  7056  7543 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-18 14:10:23.888  7056  7543 D BluetoothAdapterProperties: Setting state to 12
08-18 14:10:23.888  7056  7543 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-18 14:10:23.874  7644  7644 W sh      : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-18 14:10:23.884  7644  7644 W sh      : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-18 14:10:23.889  7056  7547 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-18 14:10:23.890  7056  7547 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-18 14:10:23.890  1034  1101 D BluetoothManagerService: Message: 60
08-18 14:10:23.890  1034  1101 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-18 14:10:23.890  1034  1101 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
08-18 14:10:23.893  7056  7543 I BluetoothAdapterState: Entering On State
,08-18 14:10:23.904  7056  7547 D BluetoothAdapterProperties: Discoverable Timeout:120
08-18 14:10:23.904  7056  7547 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-18 14:10:23.908  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-18 14:10:23.908  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 14:10:23.908  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-18 14:10:23.908  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-18 14:10:23.908  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-18 14:10:23.908  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-18 14:10:23.908  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-18 14:10:23.908  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-18 14:10:23.913  6817  6817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-18 14:10:23.917  7056  7543 D LGBluetoothServiceAdapter: [BTUI] OnState
08-18 14:10:23.917  7056  7543 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-18 14:10:23.917  7056  7543 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-18 14:10:23.917  7056  7613 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-18 14:10:23.917  7056  7613 W bt-smp  : Plain text(LSB ~ MSB) = b3 88 5c 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-18 14:10:23.917  7056  7613 W bt-smp  : Encrypted text(LSB ~ MSB) = 63 0c a4 4c bd 70 f9 ef dd 51 2e 50 76 f2 5d d1 
08-18 14:10:23.917  7056  7613 W bt-btm  : Stopping oneshot timer
08-18 14:10:23.919  7056  7543 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-18 14:10:23.924  6913  6933 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-18 14:10:23.929  1034  1101 D BluetoothHeadset: onBluetoothStateChange: up=true
08-18 14:10:23.932  6913  6913 D BluetoothInputDevice: Proxy object connected
08-18 14:10:23.932  6913  6913 D HidProfile: Bluetooth service connected
08-18 14:10:23.934  1855  2482 D BluetoothHeadset: onBluetoothStateChange: up=true
08-18 14:10:23.934  7056  7613 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-18 14:10:23.934  7056  7613 W bt-smp  : Plain text(LSB ~ MSB) = e1 2a 63 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-18 14:10:23.934  7056  7613 W bt-smp  : Encrypted text(LSB ~ MSB) = c9 25 86 19 9f 4d 7c 11 b8 ba ff 58 1d e7 ac 40 
08-18 14:10:23.934  7056  7613 W bt-btm  : Stopping oneshot timer
08-18 14:10:23.936  1034  1034 D BluetoothHeadset: Proxy object connected
,08-18 14:10:23.941  1855  1855 D BluetoothHeadset: Proxy object connected
08-18 14:10:23.942  7056  7543 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-18 14:10:23.943  1855  2737 D BluetoothHeadset: onBluetoothStateChange: up=true
08-18 14:10:23.945  1855  1855 D BluetoothHeadset: Proxy object connected
08-18 14:10:23.946  1855  1870 D BluetoothHeadset: onBluetoothStateChange: up=true
08-18 14:10:23.948  7056  7613 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-18 14:10:23.948  7056  7613 W bt-smp  : Plain text(LSB ~ MSB) = 41 d9 67 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-18 14:10:23.948  7056  7613 W bt-smp  : Encrypted text(LSB ~ MSB) = f5 28 7d aa e6 c7 f2 c7 6d 8a dd e1 22 cd 27 b6 
08-18 14:10:23.948  7056  7613 W bt-btm  : Stopping oneshot timer
08-18 14:10:23.949  1855  1855 D BluetoothHeadset: Proxy object connected
08-18 14:10:23.949  6913  6933 D BluetoothPbap: onBluetoothStateChange: up=true
08-18 14:10:23.951  1034  1101 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-18 14:10:23.957  1034  1034 D BluetoothA2dp: Proxy object connected
08-18 14:10:23.959  6913  6932 D BluetoothMap: onBluetoothStateChange: up=true
08-18 14:10:23.962  7056  7613 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-18 14:10:23.962  7056  7613 W bt-smp  : Plain text(LSB ~ MSB) = f4 35 6e 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-18 14:10:23.962  7056  7613 W bt-smp  : Encrypted text(LSB ~ MSB) = 94 c4 7b ae 68 79 17 df 9f 35 66 ee c5 57 e1 9c 
08-18 14:10:23.962  7056  7613 W bt-btm  : Stopping oneshot timer
08-18 14:10:23.962  7649  7649 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-18 14:10:23.963  6913  6913 D BluetoothMap: Proxy object connected
08-18 14:10:23.963  6913  6913 D MapProfile: Bluetooth service connected
08-18 14:10:23.963  6913  6913 D BluetoothMap: getConnectedDevices()
,08-18 14:10:23.966  6913  6933 D BluetoothPan: onBluetoothStateChange on: true
08-18 14:10:23.966  6913  6933 D BluetoothPan: onBluetoothStateChange call bindService
08-18 14:10:23.967  7056  7072 V BluetoothMapService: getConnectedDevices()
08-18 14:10:23.969  1034  1101 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-18 14:10:23.970  1034  1101 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-18 14:10:23.970  6913  6913 D BluetoothPan: BluetoothPAN Proxy object connected
08-18 14:10:23.970  6913  6913 D PanProfile: Bluetooth service connected
08-18 14:10:23.972  1034  1034 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-18 14:10:23.972  1034  1101 D BluetoothManagerService: Message: 40
08-18 14:10:23.972  1034  1101 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-18 14:10:23.976  1944  1944 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-18 14:10:23.977  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-18 14:10:23.978  1944  2130 D LGBluetoothAPIService: Message: 1
08-18 14:10:23.978  1944  2130 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-18 14:10:23.988  6817  6817 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
,08-18 14:10:23.994  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-18 14:10:23.994  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 14:10:23.994  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-18 14:10:23.994  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-18 14:10:23.994  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-18 14:10:23.994  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-18 14:10:23.994  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-18 14:10:23.994  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-18 14:10:23.995  7056  7056 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-18 14:10:23.995  7056  7056 D BluetoothMapService: STATE_ON
08-18 14:10:23.995  1944  2130 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-18 14:10:23.996  6913  6913 D LocalBluetoothProfileManager: Adding local A2DP profile
08-18 14:10:23.998  1034  1101 D BluetoothManagerService: Message: 30
08-18 14:10:23.999  6817  6817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-18 14:10:24.000  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-18 14:10:24.007  6913  6913 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-18 14:10:24.010  1034  1101 D BluetoothManagerService: Message: 30
08-18 14:10:24.013  7056  7056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25449515
08-18 14:10:24.013  7056  7056 V BluetoothPbapService: Pbap Service onCreate
08-18 14:10:24.013  7056  7056 V BluetoothPbapService: Starting PBAP service
08-18 14:10:24.014  7056  7056 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-18 14:10:24.015  7056  7056 V BluetoothPbapService: Pbap Service onBind
08-18 14:10:24.015  6913  6913 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-18 14:10:24.016  7056  7056 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-18 14:10:24.016  7056  7056 V BluetoothPbapService: state: 12
08-18 14:10:24.017  6913  6913 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-18 14:10:24.018  7056  7056 D LGBluetoothAPIServer: [BTUI] onCreate()
08-18 14:10:24.019  7056  7056 D LGBluetoothAPIServer: [BTUI] onBind()
08-18 14:10:24.024  6913  6913 D BluetoothA2dp: Proxy object connected
08-18 14:10:24.024  6913  6913 D A2dpProfile: Bluetooth service connected
08-18 14:10:24.027  7056  7056 V BluetoothMapService: Handler(): got msg=1
08-18 14:10:24.028  7056  7056 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-18 14:10:24.028  1944  1944 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-18 14:10:24.028  7056  7056 V BluetoothPbapService: Handler(): got msg=1
,08-18 14:10:24.028  1944  2130 D LGBluetoothAPIService: Message: 100
08-18 14:10:24.028  1944  2130 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-18 14:10:24.029  7056  7056 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-18 14:10:24.029  6913  6913 D BluetoothHeadset: Proxy object connected
08-18 14:10:24.029  7056  7664 D BluetoothMapMasInstance: MAS initSocket()
08-18 14:10:24.030  7056  7056 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-18 14:10:24.030  7056  7056 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-18 14:10:24.030  7056  7056 V BluetoothPbapReceiver: ***********state = 12
08-18 14:10:24.030  7056  7664 D BluetoothMapMasInstance:   masId = 00
08-18 14:10:24.030  7056  7664 D BluetoothMapMasInstance:   msgTypes = 0e
08-18 14:10:24.030  7056  7664 D BluetoothMapMasInstance:   masName = SMS/MMS
08-18 14:10:24.030  7056  7664 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-18 14:10:24.030  6913  6913 D HeadsetProfile: Bluetooth service connected
08-18 14:10:24.031  1034  1577 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-18 14:10:24.033  7056  7664 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-18 14:10:24.034  2161  2161 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-18 14:10:24.035  7056  7664 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-18 14:10:24.035  7056  7664 V BluetoothMapMasInstance: Succeed to create listening socket 
08-18 14:10:24.035  7056  7664 D BluetoothMapMasInstance: Accepting socket connection...
08-18 14:10:24.035  2161  2161 D c       : Getting all permits...
08-18 14:10:24.035  2161  2161 D a       : Opening database...
08-18 14:10:24.036  7056  7547 D BluetoothAdapterProperties: Scan Mode:21
08-18 14:10:24.036  7056  7547 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-18 14:10:24.035  7056  7665 V BluetoothPbapService: Pbap Service initSocket
08-18 14:10:24.037  1034  1810 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-18 14:10:24.041  7056  7665 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-18 14:10:24.041  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-18 14:10:24.043  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 14:10:24.043  2161  2161 D a       : Opening database auth.proximity.permit_store...
08-18 14:10:24.044  2161  2161 D a       : Closing database...
,08-18 14:10:24.045  6913  6913 D BluetoothPbap: Proxy object connected
08-18 14:10:24.046  7056  7665 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-18 14:10:24.046  7056  7665 V BluetoothPbapService: Succeed to create listening socket 
08-18 14:10:24.046  7056  7665 V BluetoothPbapService: Accepting socket connection...
08-18 14:10:24.049  6913  6913 D PbapServerProfile: Bluetooth service connected
08-18 14:10:24.052  6913  6913 D DockEventReceiver: finishStartingService: stopping service
08-18 14:10:24.057  6913  6913 D BluetoothPermissionRequest: onReceive
,08-18 14:10:24.059  6913  6913 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-18 14:10:24.060  6913  6913 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-18 14:10:24.064  7056  7056 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-18 14:10:24.065  7056  7056 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-18 14:10:24.072  7056  7056 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-18 14:10:24.089  7056  7056 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-18 14:10:24.089  7056  7056 V BtOppService: onCreate
,08-18 14:10:24.093  7056  7056 V BluetoothOppNotification: send message
08-18 14:10:24.098  7056  7056 V BtOppService: Starting RfcommListener
,08-18 14:10:24.102  7056  7056 D BluetoothOppPreference: Dumping Names:  
08-18 14:10:24.102  7056  7056 D BluetoothOppPreference: {}
08-18 14:10:24.102  7056  7056 D BluetoothOppPreference: Dumping Channels:  
08-18 14:10:24.102  7056  7056 D BluetoothOppPreference: {}
08-18 14:10:24.103  7056  7056 V BtOppService: onStartCommand
08-18 14:10:24.104  7056  7672 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-18 14:10:24.106  7056  7056 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-18 14:10:24.106  7056  7056 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,08-18 14:10:24.110  7056  7669 V BtOppService: Deleted complete outbound shares, number =  0
08-18 14:10:24.111  7056  7669 V BtOppService: Deleted complete inbound failed shares, number = 0
08-18 14:10:24.111  7056  7056 V BluetoothOppNotification: new notify threadi!
08-18 14:10:24.112  7056  7669 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-18 14:10:24.112  7056  7672 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-18 14:10:24.113  7056  7056 V BluetoothOppNotification: send delay message
08-18 14:10:24.114  7056  7056 V BtOppService: start RfcommListener
08-18 14:10:24.114  7056  7669 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@b9ae106 on behalf of 
08-18 14:10:24.117  7056  7673 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-18 14:10:24.118  7056  7672 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3225d3c7 on behalf of 
08-18 14:10:24.119  7056  7056 V BtOppService: RfcommListener started
,08-18 14:10:24.121  7056  7056 V BtOppService: ContentObserver received notification
08-18 14:10:24.123  7056  7674 V BtOppRfcommListener: Starting RFCOMM listener....
08-18 14:10:24.124  1034  1622 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-18 14:10:24.125  7056  7674 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-18 14:10:24.126  7056  7674 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
08-18 14:10:24.126  7056  7674 V BtOppRfcommListener: Started RFCOMM listener....
08-18 14:10:24.127  7056  7674 I BtOppRfcommListener: Accept thread started.
08-18 14:10:24.127  7056  7674 V BtOppRfcommListener: Accepting connection...
08-18 14:10:24.127  7056  7673 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@338bfdf4 on behalf of 
08-18 14:10:24.127  7056  7673 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-18 14:10:24.129  7056  7673 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-18 14:10:24.130  7056  7672 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-18 14:10:24.130  7056  7672 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-18 14:10:24.132  7056  7672 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@38b3a91d on behalf of 
08-18 14:10:24.132  7056  7672 V BluetoothOppNotification: update too frequent, put in queue
08-18 14:10:24.132  7056  7673 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@b740792 on behalf of 
,08-18 14:10:24.136  7056  7672 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-18 14:10:24.139  7056  7056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25449515
08-18 14:10:24.139  7056  7056 V BluetoothFtpService: Ftp Service onCreate
08-18 14:10:24.139  7056  7056 I BluetoothFtpService: Ftp Service onCreate
08-18 14:10:24.139  7056  7056 V BluetoothFtpService: Ftp Service onStartCommand
08-18 14:10:24.139  7056  7056 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-18 14:10:24.139  7056  7056 V BluetoothFtpService: Starting Listening on sockets
08-18 14:10:24.139  7056  7673 V BluetoothOppNotification: outbound: succ-0  fail-0
08-18 14:10:24.140  7056  7056 V BtOppService: ContentObserver received notification
08-18 14:10:24.140  7056  7056 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-18 14:10:24.140  7056  7056 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-18 14:10:24.140  7056  7056 V BluetoothSapReceiver: SapReceiver onReceive 
08-18 14:10:24.140  7056  7056 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
,08-18 14:10:24.140  7056  7056 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-18 14:10:24.140  7056  7056 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-18 14:10:24.141  7056  7675 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-18 14:10:24.141  7056  7675 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-18 14:10:24.141  7056  7673 V BluetoothOppNotification: outbound notification was removed.
08-18 14:10:24.141  7056  7673 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-18 14:10:24.142  7056  7675 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1650560 on behalf of 
08-18 14:10:24.142  7056  7056 V BluetoothFtpService: Handler(): got msg=1
08-18 14:10:24.143  7056  7675 V BluetoothOppNotification: update too frequent, put in queue
08-18 14:10:24.146  7056  7056 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-18 14:10:24.146  7056  7056 V BluetoothFtpService: Ftp Service initSocket
08-18 14:10:24.146  7056  7675 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-18 14:10:24.147  7056  7673 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@27e6ba19 on behalf of 
08-18 14:10:24.148  7056  7673 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-18 14:10:24.150  7056  7673 V BluetoothOppNotification: inbound notification was removed.
,08-18 14:10:24.150  7056  7673 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-18 14:10:24.150  1034  1989 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-18 14:10:24.151  7056  7056 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-18 14:10:24.151  7056  7673 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@12470ade on behalf of 
08-18 14:10:24.152  7056  7056 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=79
08-18 14:10:24.152  7056  7056 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-18 14:10:24.154  7056  7676 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-18 14:10:24.165  7056  7056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25449515
08-18 14:10:24.165  7056  7056 V BluetoothSapService: Sap Service onCreate
,08-18 14:10:24.167  7056  7056 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-18 14:10:24.167  7056  7056 V BluetoothSapService: state: 12
08-18 14:10:24.167  7056  7056 V BluetoothSapService: Starting SAP server process
08-18 14:10:24.169  7056  7056 V BluetoothSapService: SAP Service startRfcommListenerThread
08-18 14:10:24.164  7677  7677 W sapd    : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-18 14:10:24.164  7677  7677 W sapd    : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-18 14:10:24.171  7056  7678 V BluetoothSapService: Sap Service initRfcommSocket
08-18 14:10:24.171  1034  2054 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-18 14:10:24.172  7056  7678 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-18 14:10:24.173  7056  7678 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-18 14:10:24.173  7056  7678 V BluetoothSapService: Succeed to create listening socket 
08-18 14:10:24.173  7056  7678 V BluetoothSapService: Accepting socket connection...
08-18 14:10:24.179  7677  7677 V BT_SAP  : Event pipe created
08-18 14:10:24.179  7677  7677 V BT_SAP  : create_server_socket qcom.sap.server
08-18 14:10:24.179  7677  7677 V BT_SAP  : created socket fd 6
,08-18 14:10:24.275  1034  1577 I art     : Explicit concurrent mark sweep GC freed 92571(4MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 1.898ms total 92.470ms
,08-18 14:10:24.283  7322  7358 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
08-18 14:10:24.869  1034  1539 D LGWifiP2pService: P2pDisabledState{ when=-2ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-18 14:10:24.869  1034  1539 D LGWifiP2pService: DefaultState{ when=-2ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-18 14:10:24.879  1034  1540 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
08-18 14:10:24.881  1034  1540 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
08-18 14:10:25.062  1034  2054 I ActivityManager: Killing 7468:com.lge.bnr/1000 (adj 15): empty #17
,08-18 14:10:25.097  1034  2013 W libprocessgroup: failed to open /acct/uid_1000/pid_7468/cgroup.procs: No such file or directory
,08-18 14:10:25.115  7056  7056 V BluetoothOppNotification: new notify threadi!
08-18 14:10:25.116  7056  7056 V BluetoothOppNotification: send delay message
,08-18 14:10:25.119  7056  7690 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-18 14:10:25.120  7056  7690 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@30b4f6ea on behalf of 
08-18 14:10:25.121  7056  7690 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-18 14:10:25.123  7056  7690 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-18 14:10:25.124  7056  7690 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3449ddb on behalf of 
08-18 14:10:25.124  7056  7690 V BluetoothOppNotification: outbound: succ-0  fail-0
08-18 14:10:25.126  7056  7690 V BluetoothOppNotification: outbound notification was removed.
08-18 14:10:25.126  7056  7690 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-18 14:10:25.127  7056  7690 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3eb22078 on behalf of 
08-18 14:10:25.127  7056  7690 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-18 14:10:25.132  7056  7690 V BluetoothOppNotification: inbound notification was removed.
,08-18 14:10:25.132  7056  7690 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-18 14:10:25.134  7056  7690 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@c8c9351 on behalf of 
,08-18 14:10:25.339  1034  1971 I ActivityManager: Killing 6711:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,08-18 14:10:25.369  6984  6984 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-18 14:10:25.370  6984  6984 W System.err: android.os.DeadObjectException
08-18 14:10:25.370  6984  6984 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-18 14:10:25.370  6984  6984 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-18 14:10:25.370  6984  6984 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-18 14:10:25.370  6984  6984 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-18 14:10:25.370  6984  6984 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-18 14:10:25.370  6984  6984 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-18 14:10:25.370  6984  6984 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-18 14:10:25.370  6984  6984 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-18 14:10:25.370  6984  6984 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-18 14:10:25.370  6984  6984 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-18 14:10:25.370  6984  6984 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-18 14:10:25.370  6984  6984 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-18 14:10:25.370  6984  6984 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-18 14:10:25.370  6984  6984 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-18 14:10:25.371  6984  6984 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-18 14:10:25.371  6984  6984 W System.err: android.os.DeadObjectException
08-18 14:10:25.371  6984  6984 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-18 14:10:25.371  6984  6984 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-18 14:10:25.371  6984  6984 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-18 14:10:25.371  6984  6984 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-18 14:10:25.371  6984  6984 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-18 14:10:25.371  6984  6984 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-18 14:10:25.371  6984  6984 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-18 14:10:25.371  6984  6984 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-18 14:10:25.371  6984  6984 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-18 14:10:25.371  6984  6984 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-18 14:10:25.372  6984  6984 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-18 14:10:25.372  6984  6984 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-18 14:10:25.372  6984  6984 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-18 14:10:25.372  6984  6984 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-18 14:10:25.372  6984  6984 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-18 14:10:25.372  6984  6984 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,08-18 14:10:25.406  1034  2054 W libprocessgroup: failed to open /acct/uid_1000/pid_6711/cgroup.procs: No such file or directory
,08-18 14:10:25.409  1034  2054 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
08-18 14:10:25.413  6984  6984 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-18 14:10:25.413  6984  6984 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-18 14:10:25.455  1034  1623 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7691 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-18 14:10:25.456  6984  6984 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-18 14:10:25.546  7691  7691 D UEI.SmartControl: Quickset Services start...
,08-18 14:10:25.550  7691  7691 I UEI.SmartControl: Manufacture = LGE
,08-18 14:10:25.551  7691  7691 D UEI.SmartControl: Id = LGNevo
08-18 14:10:25.552  7691  7691 D UEI.SmartControl: File observer start...
08-18 14:10:25.553  7691  7691 E UEI.SmartControl: IR Port is disabled: false
08-18 14:10:25.553  7691  7691 D UEI.SmartControl: Starting file observer...
08-18 14:10:25.553  7691  7691 D UEI.SmartControl: Extracting JNI libs...
08-18 14:10:25.553  7691  7691 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
,08-18 14:10:25.663  7691  7691 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-18 14:10:25.664  7691  7691 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-18 14:10:25.664  7691  7691 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-18 14:10:25.703  7691  7691 I UEI.SmartControl: --- Selecting new region: 6
08-18 14:10:25.705  7691  7691 I UEI.SmartControl: Model = LG-D855
08-18 14:10:25.707  7691  7691 D UEI.SmartControl: QS Service created
,08-18 14:10:25.724  7691  7691 I UEI.SmartControl: Service initServices...
,08-18 14:10:25.729  7691  7691 D UEI.SmartControl: QS start get config
08-18 14:10:25.768  7691  7691 D UEI.SmartControl: Loading JNI Libs...
,08-18 14:10:25.849  1034  2035 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-18 14:10:25.849  1034  2035 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@b8ae379 mBinding = false
,08-18 14:10:25.869  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-18 14:10:25.869  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-18 14:10:25.871  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-18 14:10:25.872  1034  1101 D BluetoothManagerService: Message: 2
08-18 14:10:25.873  1034  1101 D BluetoothManagerService: Sending off request.
08-18 14:10:25.873  7056  7071 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-18 14:10:25.874  7056  7543 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-18 14:10:25.874  7056  7543 D BluetoothAdapterProperties: Setting state to 13
08-18 14:10:25.874  7056  7543 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-18 14:10:25.875  7056  7543 D BluetoothAdapterProperties: onBluetoothDisable()
08-18 14:10:25.876  7056  7543 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-18 14:10:25.877  7056  7547 D BluetoothAdapterProperties: Scan Mode:20
08-18 14:10:25.877  7056  7543 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-18 14:10:25.878  7056  7674 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-18 14:10:25.878  7056  7543 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-18 14:10:25.880  7056  7664 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-18 14:10:25.880  7056  7664 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-18 14:10:25.880  7056  7664 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-18 14:10:25.880  7056  7664 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-18 14:10:25.880  7056  7664 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-18 14:10:25.880  7056  7664 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-18 14:10:25.880  7056  7664 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-18 14:10:25.880  7056  7664 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-18 14:10:25.881  7056  7678 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-18 14:10:25.881  7056  7613 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-18 14:10:25.881  7056  7613 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-18 14:10:25.882  7056  7665 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-18 14:10:25.882  7056  7676 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-18 14:10:25.883  1034  1101 D BluetoothManagerService: Message: 60
08-18 14:10:25.883  1034  1101 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-18 14:10:25.883  1034  1101 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-18 14:10:25.884  7056  7613 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-18 14:10:25.884  7056  7613 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-18 14:10:25.884  7056  7613 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-18 14:10:25.884  7056  7613 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-18 14:10:25.884  7056  7613 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-18 14:10:25.884  7056  7613 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-18 14:10:25.884  7056  7613 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-18 14:10:25.884  7056  7613 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-18 14:10:25.884  7056  7613 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-18 14:10:25.884  7056  7613 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-18 14:10:25.884  7056  7613 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-18 14:10:25.884  7056  7613 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-18 14:10:25.887  6817  6817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is ,disabled - will return stored value
08-18 14:10:25.887  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-18 14:10:25.887  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 14:10:25.887  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-18 14:10:25.887  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-18 14:10:25.887  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-18 14:10:25.887  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-18 14:10:25.887  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-18 14:10:25.887  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-18 14:10:25.889  6817  6817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-18 14:10:25.889  6817  6817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-18 14:10:25.889  1944  1944 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-18 14:10:25.891  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-18 14:10:25.891  6817  6817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-18 14:10:25.891  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-18 14:10:25.891  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 14:10:25.891  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-18 14:10:25.891  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-18 14:10:25.891  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-18 14:10:25.891  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-18 14:10:25.891  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-18 14:10:25.891  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-18 14:10:25.892  6817  6817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-18 14:10:25.892  6817  6817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-18 14:10:25.894  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 14:10:25.895  7056  7056 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-18 14:10:25.895  7056  7056 D BluetoothMapService: STATE_TURNING_OFF
08-18 14:10:25.895  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 14:10:25.896  7056  7056 V BtOppService: Receiver DISABLED_ACTION 
08-18 14:10:25.896  7056  7056 V BluetoothMapService: Handler(): got msg=4
08-18 14:10:25.897  7056  7056 D BluetoothMapService: MAP Service closeService in
08-18 14:10:25.897  7056  7056 D BluetoothMapMasInstance: MAP Service shutdown
08-18 14:10:25.897  7056  7056 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-18 14:10:25.897  7056  7056 V BluetoothMapService: MAP Service closeService out
08-18 14:10:25.897  7056  7056 I BtOppRfcommListener: stopping Accept Thread
08-18 14:10:25.897  7056  7056 V BtOppRfcommListener: close mBtServerSocket
08-18 14:10:25.898  7056  7674 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-18 14:10:25.898  7056  7056 V BtOppRfcommListener: waiting for thread to terminate
08-18 14:10:25.898  7056  7056 V BtOppRfcommListener: done waiting for thread to terminate
08-18 14:10:25.901  6913  6913 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
08-18 14:10:25.907  7056  7056 V BtOppService: onDestroy
08-18 14:10:25.907  6913  6913 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-18 14:10:25.919  7056  7056 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
,08-18 14:10:25.923  7056  7056 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-18 14:10:25.923  7056  7056 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-18 14:10:25.923  7056  7056 V BluetoothPbapReceiver: ***********state = 13
08-18 14:10:25.925  7056  7056 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-18 14:10:25.925  7056  7056 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-18 14:10:25.925  7056  7056 V BluetoothPbapService: state: 13
08-18 14:10:25.925  7056  7056 V BluetoothPbapService: Pbap Service closeService in
08-18 14:10:25.926  6913  6913 D DockEventReceiver: finishStartingService: stopping service
08-18 14:10:25.928  2161  2161 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-18 14:10:25.930  6913  6913 D BluetoothPbap: Proxy object disconnected
08-18 14:10:25.930  6913  6913 D PbapServerProfile: Bluetooth service disconnected
08-18 14:10:25.931  7056  7056 V BluetoothPbapService: successfully stopped pbap service
08-18 14:10:25.931  7056  7056 V BluetoothPbapService: Pbap Service closeService out
08-18 14:10:25.931  7056  7056 V BluetoothPbapService: Pbap Service onDestroy
08-18 14:10:25.931  7056  7056 V BluetoothPbapService: Pbap Service closeService in
08-18 14:10:25.931  7056  7056 V BluetoothPbapService: Pbap Service closeService out
08-18 14:10:25.931  7056  7056 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-18 14:10:25.944  6913  6913 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-18 14:10:25.949  6913  6913 D BluetoothPermissionRequest: onReceive
08-18 14:10:25.949  6913  6913 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-18 14:10:25.955  6913  6913 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-18 14:10:25.959  7056  7056 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-18 14:10:25.959  7056  7056 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-18 14:10:25.960  7056  7056 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-18 14:10:25.964  7056  7056 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-18 14:10:25.964  7056  7056 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-18 14:10:25.965  7056  7056 V BluetoothFtpService: Ftp Service onStartCommand
08-18 14:10:25.965  7056  7056 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-18 14:10:25.965  7056  7056 V BluetoothFtpService: Ftp Service closeService
08-18 14:10:25.965  7056  7056 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
,08-18 14:10:25.966  7056  7056 V BluetoothFtpService: successfully stopped ftp service
08-18 14:10:25.967  7056  7056 V BluetoothFtpService: Ftp Service onDestroy
08-18 14:10:25.967  7056  7056 V BluetoothFtpService: Ftp Service closeService
08-18 14:10:25.974  7056  7056 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-18 14:10:25.974  7056  7056 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-18 14:10:25.974  7056  7056 V BluetoothSapReceiver: SapReceiver onReceive 
08-18 14:10:25.974  7056  7056 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-18 14:10:25.974  7056  7056 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-18 14:10:25.974  7056  7056 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-18 14:10:25.977  7056  7056 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-18 14:10:25.977  7056  7056 V BluetoothSapService: state: 13
08-18 14:10:25.977  7056  7056 V BluetoothSapService: Stopping SAP server process
08-18 14:10:25.980  7056  7056 V BluetoothSapService: Sap Service closeSapService in
08-18 14:10:25.980  7056  7056 V BluetoothSapService: Close listen Socket : 
,08-18 14:10:25.981  7056  7056 V BluetoothSapService: Close rfcomm Socket : 
08-18 14:10:25.981  7056  7056 V BluetoothSapService: Close sapd  Socket : 
08-18 14:10:25.983  7056  7056 V BluetoothSapService: Sap Service closeSapService out
08-18 14:10:25.983  7056  7056 V BluetoothSapService: Sap Service onDestroy
08-18 14:10:25.983  7056  7056 V BluetoothSapService: Sap Service closeSapService in
08-18 14:10:25.983  7056  7056 V BluetoothSapService: Close listen Socket : 
08-18 14:10:25.983  7056  7056 V BluetoothSapService: Close rfcomm Socket : 
08-18 14:10:25.983  7056  7056 V BluetoothSapService: Close sapd  Socket : 
,08-18 14:10:25.984  7056  7056 V BluetoothSapService: Sap Service closeSapService out
,08-18 14:10:26.039  7691  7691 I UEI.SmartControl: Supports setup maps: true
,08-18 14:10:26.042  7691  7691 D UEI.SmartControl: QS start statue = true Error code = 0
08-18 14:10:26.042  7691  7691 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-18 14:10:26.042  7691  7691 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-18 14:10:26.042  7691  7691 I UEI.SmartControl: ### init IR Blaster...
08-18 14:10:26.047  7691  7691 D serial_port: Configuring serial port
08-18 14:10:26.050  7691  7691 E UEI.SmartControl: UEIBLaster setting for 616
08-18 14:10:26.050  7691  7691 I UEI.SmartControl: Setting serial record hearder size = 2
08-18 14:10:26.050  7691  7691 I UEI.SmartControl: configuring settings for MAXQ616
08-18 14:10:26.050  7691  7691 I UEI.SmartControl: Get version...
08-18 14:10:26.067  7691  7728 D UEI.SmartControl: serial port data available: 21
,08-18 14:10:26.096  7691  7691 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-18 14:10:26.096  7691  7691 I UEI.SmartControl: IR Blaster version: 256702256704300002
,08-18 14:10:26.097  7691  7691 I UEI.SmartControl: QS saving settings...
,08-18 14:10:26.100  7691  7691 D UEI.SmartControl: IR Blaster version: 25672567
08-18 14:10:26.118  7691  7728 D UEI.SmartControl: serial port data available: 4
,08-18 14:10:26.155  7691  7732 I UEI.SmartControl: Device manager: loading config....
,08-18 14:10:26.157  7691  7732 D UEI.SmartControl: ----------- loading internal config...
08-18 14:10:26.160  7691  7691 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-18 14:10:26.163  7691  7691 E UEI.SmartControl: Services init done
08-18 14:10:26.163  7691  7691 D UEI.SmartControl: QS Service init finished
08-18 14:10:26.164  7691  7691 D UEI.SmartControl: QS Service version name: 2.1.91
08-18 14:10:26.164  7691  7691 D UEI.SmartControl: QS Service version code: 201091
08-18 14:10:26.165  7691  7691 D UEI.SmartControl: Service requested: Control
08-18 14:10:26.173  7691  7732 E UEI.SmartControl: Loading SETTINGS...
,08-18 14:10:26.176  7691  7691 D UEI.SmartControl: Request IControl service: devices are loaded...
08-18 14:10:26.182  6984  6984 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-18 14:10:26.183  7691  7706 I UEI.SmartControl: ------ IControl API: 11
08-18 14:10:26.185  7691  7706 I UEI.SmartControl: Registering callback...
08-18 14:10:26.186  7691  7707 I UEI.SmartControl: ------ IControl API: 19
08-18 14:10:26.187  1034  2054 I ActivityManager: Killing 6984:com.lge.qremote/u0a112 (adj 15): empty #17
08-18 14:10:26.188  7691  7707 I UEI.SmartControl: Registering Services Ready callback...
,08-18 14:10:26.195  7691  7732 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-18 14:10:26.212  7691  7731 I UEI.SmartControl: Notify AllClients services are ready: 0
,08-18 14:10:26.213  7691  7731 D UEI.SmartControl: -----service ready thread exits
08-18 14:10:26.247  1034  2023 W libprocessgroup: failed to open /acct/uid_10112/pid_6984/cgroup.procs: No such file or directory
,08-18 14:10:26.248  7691  7691 D UEI.SmartControl: Internal service binding...
,08-18 14:10:26.789  7056  7547 D bt_hci_bdroid: cleanup
,08-18 14:10:26.798  7056  7642 I bt_userial_mct: exiting userial_read_thread
08-18 14:10:26.798  7056  7642 D bt_userial_mct: Leaving userial_evt_read_thread()
08-18 14:10:26.799  7056  7615 I bt_lpm  : LPM is already off!!!
08-18 14:10:26.799  7056  7613 W bt-btif : ag scb idx 1 not allocated
08-18 14:10:26.799  7056  7613 E bt-btif : BTA AG is already disabled, ignoring ...
08-18 14:10:26.799  7056  7613 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-18 14:10:26.799  7056  7613 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-18 14:10:26.799  7056  7613 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-18 14:10:26.799  7056  7613 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-18 14:10:26.799  7056  7613 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-18 14:10:26.799  7056  7613 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-18 14:10:26.799  7056  7613 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-18 14:10:26.799  7056  7613 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-18 14:10:26.799  7056  7613 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-18 14:10:26.799  7056  7613 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-18 14:10:26.799  7056  7613 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-18 14:10:26.799  7056  7613 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-18 14:10:26.800  7056  7613 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-18 14:10:26.800  7056  7613 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-18 14:10:26.800  7056  7613 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-18 14:10:26.800  7056  7613 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-18 14:10:26.800  7056  7613 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-18 14:10:26.800  7056  7613 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-18 14:10:26.800  7056  7613 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-18 14:10:26.801  7056  7547 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-18 14:10:26.801  7056  7615 I bt_vendor: hw_epilog_process
08-18 14:10:26.801  7056  7547 D bt_hci_bdroid: cleanup Finalizing cleanup
08-18 14:10:26.801  7056  7547 D bt_userial_mct: userial_close
08-18 14:10:26.801  7056  7547 E bt_userial_mct: pthread_join() FAILED result:3
08-18 14:10:26.801  7056  7547 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-18 14:10:26.807  7056  7547 D bt_hci_bdroid: set_power 0
08-18 14:10:26.807  7056  7547 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-18 14:10:26.807  7056  7547 I bt_vendor: bluetooth satus is on
08-18 14:10:26.807  7056  7547 I bt_vendor: bt-vendor : resetting BT status
08-18 14:10:26.807  7056  7547 I bt_vendor: Starting hciattach daemon
08-18 14:10:26.807  7056  7547 I bt_vendor: try to set false
,08-18 14:10:26.814  7056  7547 I bt_vendor: Starting hciattach daemon
08-18 14:10:26.814  7056  7547 I bt_vendor: try to set false
08-18 14:10:26.815  7056  7547 I bt_vendor: cleanup
08-18 14:10:26.816  7056  7613 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-18 14:10:26.817  7056  7547 I GKI_LINUX: GKI_exit_task 0 done
08-18 14:10:26.817  7056  7547 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-18 14:10:26.818  7056  7543 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-18 14:10:26.823  7056  7056 D HeadsetService: Received stop request...Stopping profile...
,08-18 14:10:26.828  7056  7056 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-18 14:10:26.828  7056  7056 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-18 14:10:26.828  7056  7056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25449515
08-18 14:10:26.830  7056  7567 D HeadsetStateMachine: Exit Disconnected: -1
08-18 14:10:26.832  1034  1034 D BluetoothHeadset: Proxy object disconnected
08-18 14:10:26.833  1034  1034 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-18 14:10:26.833  1855  1855 D BluetoothHeadset: Proxy object disconnected
08-18 14:10:26.833  1855  1855 D BluetoothHeadset: Proxy object disconnected
08-18 14:10:26.834  1855  1855 D BluetoothHeadset: Proxy object disconnected
08-18 14:10:26.836  7056  7056 D A2dpService: Received stop request...Stopping profile...
,08-18 14:10:26.841  7056  7605 D A2dpStateMachine: Exit Disconnected: -1
08-18 14:10:26.843  7056  7543 D BluetoothAdapterState: Stopping profile services that were post enabled
08-18 14:10:26.843  7056  7056 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-18 14:10:26.845  7056  7056 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-18 14:10:26.845  7056  7056 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-18 14:10:26.845  7056  7056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25449515
08-18 14:10:26.847  1034  1034 D BluetoothA2dp: Proxy object disconnected
08-18 14:10:26.847  1034  1034 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-18 14:10:26.848  7056  7056 D HidService: Received stop request...Stopping profile...
08-18 14:10:26.848  7056  7056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25449515
,08-18 14:10:26.852  7056  7056 D HealthService: Received stop request...Stopping profile...
08-18 14:10:26.852  7056  7056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25449515
08-18 14:10:26.855  7056  7056 D PanService: Received stop request...Stopping profile...
08-18 14:10:26.856  7056  7056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25449515
08-18 14:10:26.857  7056  7056 D HeadsetStateMachine: Unbinding service...
08-18 14:10:26.858  7056  7056 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-18 14:10:26.858  7056  7056 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-18 14:10:26.858  7056  7056 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-18 14:10:26.858  7056  7056 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-18 14:10:26.858  7056  7056 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-18 14:10:26.858  7056  7056 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-18 14:10:26.858  7056  7056 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-18 14:10:26.859  7056  7056 D BtGatt.DebugUtils: handleDebugAction() action=null
08-18 14:10:26.860  7056  7056 D BtGatt.GattService: Received stop request...Stopping profile...
08-18 14:10:26.860  7056  7056 D BtGatt.GattService: stop()
08-18 14:10:26.860  7056  7056 D BtGatt.AdvertiseManager: advertise clients cleared
,08-18 14:10:26.864  7056  7056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25449515
08-18 14:10:26.866  7056  7056 D BluetoothMapService: Received stop request...Stopping profile...
08-18 14:10:26.866  7056  7056 D BluetoothMapService: stop()
08-18 14:10:26.867  7056  7056 D BluetoothMapEmailAppObserver: deinitObservers()
08-18 14:10:26.867  7056  7056 D BluetoothMapEmailAppObserver: removeReceiver()
08-18 14:10:26.867  7056  7056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25449515
08-18 14:10:26.869  7056  7056 I BluetoothA2dpServiceJni: cleanupNative
08-18 14:10:26.869  7056  7606 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-18 14:10:26.869  7056  7056 I GKI_LINUX: GKI_exit_task 2 done
08-18 14:10:26.869  7056  7056 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-18 14:10:26.870  7056  7056 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-18 14:10:26.870  7056  7056 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-18 14:10:26.870  7056  7056 V BluetoothMapService: Handler(): got msg=4
08-18 14:10:26.870  7056  7056 D BluetoothMapService: MAP Service closeService in
08-18 14:10:26.870  7056  7056 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-18 14:10:26.870  7056  7056 V BluetoothMapService: MAP Service closeService out
08-18 14:10:26.871  7056  7543 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-18 14:10:26.871  7056  7543 D BluetoothAdapterProperties: Setting state to 10
08-18 14:10:26.871  7056  7543 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-18 14:10:26.873  1034  1101 D BluetoothManagerService: Message: 60
08-18 14:10:26.873  1034  1101 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-18 14:10:26.873  1034  1101 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
,08-18 14:10:26.877  7056  7056 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-18 14:10:26.878  7056  7056 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-18 14:10:26.878  7056  7056 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-18 14:10:26.879  7056  7543 I BluetoothAdapterState: Entering OffState
08-18 14:10:26.879  6913  6932 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-18 14:10:26.880  7056  7056 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-18 14:10:26.880  7056  7056 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-18 14:10:26.882  7056  7056 D BluetoothMapService: cleanup()
08-18 14:10:26.882  7056  7056 D BluetoothMapService: MAP Service closeService in
08-18 14:10:26.882  7056  7056 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-18 14:10:26.882  7056  7056 V BluetoothMapService: MAP Service closeService out
08-18 14:10:26.883  1034  1101 D BluetoothHeadset: onBluetoothStateChange: up=false
08-18 14:10:26.883  6913  6932 D BluetoothA2dp: onBluetoothStateChange: up=false
08-18 14:10:26.884  1855  2482 D BluetoothHeadset: onBluetoothStateChange: up=false
08-18 14:10:26.884  1855  1870 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-18 14:10:26.890  1855  2737 D BluetoothHeadset: onBluetoothStateChange: up=false
08-18 14:10:26.891  6913  6932 D BluetoothHeadset: onBluetoothStateChange: up=false
08-18 14:10:26.892  6913  6932 D BluetoothPbap: onBluetoothStateChange: up=false
08-18 14:10:26.892  1034  1101 D BluetoothA2dp: onBluetoothStateChange: up=false
08-18 14:10:26.893  6913  6932 D BluetoothMap: onBluetoothStateChange: up=false
08-18 14:10:26.893  6913  6932 D BluetoothPan: onBluetoothStateChange on: false
08-18 14:10:26.894  1034  1101 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-18 14:10:26.894  1034  1101 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-18 14:10:26.896  1034  1101 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-18 14:10:26.896  1034  1101 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-18 14:10:26.896  1034  1101 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@b8ae379 mBinding = false
,08-18 14:10:26.899  1034  1101 D BluetoothManagerService: Sending unbind request.
08-18 14:10:26.904  7056  7547 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-18 14:10:26.905  7056  7056 I GKI_LINUX: GKI_exit_task 1 done
08-18 14:10:26.905  7056  7056 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-18 14:10:26.905  7056  7056 I BluetoothServiceJni: cleanupNative: return from cleanup
08-18 14:10:26.905  7056  7056 I art     : --- WEIRD: removing null entry 248
08-18 14:10:26.905  7056  7056 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-18 14:10:26.905  7056  7056 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-18 14:10:26.907  7056  7056 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-18 14:10:26.908  1034  1101 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
,08-18 14:10:26.912  7056  7056 I art     : System.exit called, status: 0
08-18 14:10:26.912  7056  7056 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-18 14:10:26.931   314   314 V AudioFlinger: 7056 died, releasing its sessions
08-18 14:10:26.931   314   314 V AudioFlinger:  pid 1855 @ 0
08-18 14:10:26.931   314   314 V AudioFlinger:  pid 3466 @ 1
08-18 14:10:26.931   314   314 V AudioFlinger:  pid 3466 @ 2
,08-18 14:10:26.935  1944  1944 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
08-18 14:10:26.935  1944  2130 D LGBluetoothAPIService: Message: 101
08-18 14:10:26.935  1944  2130 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
08-18 14:10:26.935  1944  2130 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
08-18 14:10:26.935  1944  2130 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
08-18 14:10:26.938  6913  6913 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-18 14:10:26.986  1034  1901 I ActivityManager: Process com.android.bluetooth (pid 7056) has died
08-18 14:10:26.986  1034  1901 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 1000ms
08-18 14:10:26.987  1034  1901 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 11000ms
,08-18 14:10:26.994  1944  1944 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-18 14:10:26.994  1944  2130 D LGBluetoothAPIService: Message: 2
08-18 14:10:26.994  1944  2130 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
08-18 14:10:26.995  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-18 14:10:26.999  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-18 14:10:27.000  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 14:10:27.004  6913  6913 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-18 14:10:27.004  6913  6913 D LGBluetoothEventManager: [BTUI] clear device connection state
08-18 14:10:27.009  6913  6913 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-18 14:10:27.011  1605  1605 D BluetoothAdapter: 176580471: getState() :  mService = null. Returning STATE_OFF
08-18 14:10:27.011  1605  1605 D BluetoothAdapter: 176580471: getState() :  mService = null. Returning STATE_OFF
,08-18 14:10:27.061  1034  1622 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7763 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
08-18 14:10:27.063  6913  6913 D DockEventReceiver: finishStartingService: stopping service
,08-18 14:10:27.150  7763  7763 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-18 14:10:27.150  7763  7763 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-18 14:10:27.151  7763  7763 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-18 14:10:27.151  7763  7763 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-18 14:10:27.174  7763  7763 D BluetoothAdapterApp: Loading JNI Library
,08-18 14:10:27.211  7763  7763 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@128d75d Instance Count = 1
,08-18 14:10:27.218  7763  7763 D BluetoothAdapterApp: onCreate
08-18 14:10:27.245  7763  7763 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-18 14:10:27.245  7763  7763 D ProfileConfigQcom: Adding HeadsetService
08-18 14:10:27.245  7763  7763 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-18 14:10:27.246  7763  7763 D ProfileConfigQcom: Adding A2dpService
08-18 14:10:27.246  7763  7763 D ProfileConfigQcom: [BTUI] HidService is supported
08-18 14:10:27.246  7763  7763 D ProfileConfigQcom: Adding HidService
,08-18 14:10:27.246  7763  7763 D ProfileConfigQcom: [BTUI] HealthService is supported
08-18 14:10:27.247  7763  7763 D ProfileConfigQcom: Adding HealthService
,08-18 14:10:27.247  7763  7763 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-18 14:10:27.249  7763  7763 D ProfileConfigQcom: [BTUI] PanService is supported
08-18 14:10:27.249  7763  7763 D ProfileConfigQcom: Adding PanService
08-18 14:10:27.249  7763  7763 D ProfileConfigQcom: [BTUI] GattService is supported
08-18 14:10:27.249  7763  7763 D ProfileConfigQcom: Adding GattService
08-18 14:10:27.250  7763  7763 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
,08-18 14:10:27.250  7763  7763 D ProfileConfigQcom: Adding BluetoothMapService
08-18 14:10:27.250  7763  7763 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-18 14:10:27.251  7763  7763 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-18 14:10:27.253  7763  7763 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-18 14:10:27.253  7763  7763 V BluetoothPbapReceiver: ***********state = 10
08-18 14:10:27.255  7763  7763 V LGMDMManagerInternal: Create singleton instance
08-18 14:10:27.363  7763  7763 D LGBluetoothAPIServer: [BTUI] onCreate()
08-18 14:10:27.363  7763  7763 D LGBluetoothAPIServer: [BTUI] onBind()
,08-18 14:10:27.368  2161  2161 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-18 14:10:27.370  1944  1944 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-18 14:10:27.371  1944  2130 D LGBluetoothAPIService: Message: 100
08-18 14:10:27.371  1944  2130 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-18 14:10:27.386  6913  6913 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,08-18 14:10:27.391  6913  6913 D BluetoothPermissionRequest: onReceive
08-18 14:10:27.393  6913  6913 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-18 14:10:27.393  6913  6913 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-18 14:10:27.395  6913  6913 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-18 14:10:27.400  7763  7763 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,08-18 14:10:27.405  7763  7763 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-18 14:10:27.408  7763  7763 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-18 14:10:27.409  7763  7763 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-18 14:10:27.409  7763  7763 V BluetoothSapReceiver: SapReceiver onReceive 
08-18 14:10:27.410  7763  7763 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-18 14:10:27.411  7763  7763 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-18 14:10:27.413  7001  7001 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-18 14:10:28.893  6817  6895 D io.jxcore.node.ConnectivityMonitor: stop
,08-18 14:10:28.893  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-18 14:10:29.024  1605  1605 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-18 14:10:29.048  1034  1442 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-18 14:10:29.135  1034  1092 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7792 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-18 14:10:29.142  1605  1605 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
08-18 14:10:29.142  1605  1605 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
08-18 14:10:29.153  1034  1034 D administrator: Handling package changes for user 0
,08-18 14:10:29.171  2036  2036 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-18 14:10:29.199  2036  2036 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-18 14:10:29.231  7792  7792 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-18 14:10:29.308  7792  7792 D LgDataFeature: LgDataFeature() Constructor: none
08-18 14:10:29.308  7792  7792 D LgDataFeature: LgDataFeature() Constructor Done, null
08-18 14:10:29.309  1034  1034 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
,08-18 14:10:29.309  1034  1034 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
08-18 14:10:29.374  1034  1091 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-18 14:10:29.380  1034  1091 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-18 14:10:29.390  2036  2036 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-18 14:10:29.390  7792  7836 I Babel   : MmsConfig: mnc/mcc: 0/0
08-18 14:10:29.390  7792  7836 I Babel   : MmsConfig.loadMmsSettings
,08-18 14:10:29.391  2503  2503 V GmsNetworkLocationProvi: DISABLE
08-18 14:10:29.394  7792  7836 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-18 14:10:29.394  7792  7836 I Babel   : MmsConfig.loadFromDatabase
,08-18 14:10:29.418  1034  1091 D LocationProviderProxy: applying state to connected service
,08-18 14:10:29.421  2503  2503 E GCoreFlp: Bound FusedProviderService with LocationManager
08-18 14:10:29.427  7792  7836 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-18 14:10:29.427  7792  7836 I Babel   : MmsConfig.loadFromResources
08-18 14:10:29.429  7792  7836 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-18 14:10:29.429  7792  7836 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,08-18 14:10:29.446  7792  7792 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-18 14:10:29.458  7792  7833 W AudioCapabilities: Unsupported mime audio/evrc
,08-18 14:10:29.459  7792  7833 W AudioCapabilities: Unsupported mime audio/qcelp
08-18 14:10:29.461  7792  7833 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-18 14:10:29.472  7792  7833 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,08-18 14:10:29.474  1820  7840 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-18 14:10:29.474  1820  7840 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
08-18 14:10:29.475  7792  7833 W AudioCapabilities: Unsupported mime audio/qcelp
08-18 14:10:29.479  7792  7833 W AudioCapabilities: Unsupported mime audio/evrc
08-18 14:10:29.479  7137  7137 I AppUp4:CustModeStarterReceiver: onReceive
08-18 14:10:29.483  7137  7137 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@3ef530ff
08-18 14:10:29.483  7137  7137 D AppUp4:CustFacade: isCustomizationCompleted : false
,08-18 14:10:29.483  7137  7137 D AppUp4:CustFacade: isPhone : true
08-18 14:10:29.483  7137  7137 D AppUp4:CustModeStarterReceiver: begin check event
08-18 14:10:29.484  7137  7137 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
,08-18 14:10:29.485  1820  4806 I Icing   : updateResources: need to parse e{com.google.android.gms}
08-18 14:10:29.500  7792  7833 W VideoCapabilities: Unsupported mime video/x-ms-wmv
08-18 14:10:29.502  7792  7833 W VideoCapabilities: Unsupported mime video/divx
,08-18 14:10:29.504  7792  7833 W VideoCapabilities: Unsupported mime video/divx311
08-18 14:10:29.517  7792  7833 W VideoCapabilities: Unsupported mime video/divx4
,08-18 14:10:29.521  1034  2035 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7843 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,08-18 14:10:29.524  7792  7833 W VideoCapabilities: Unsupported mime video/mp4v-esdp
08-18 14:10:29.526  1034  1623 I ActivityManager: Killing 6956:com.lge.sync/1000 (adj 15): empty #17
08-18 14:10:29.546  1034  1546 D WifiService: Client connection lost with reason: 4
,08-18 14:10:29.547  7792  7833 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
08-18 14:10:29.551  7792  7833 W AudioCapabilities: Unsupported mime audio/eac3
08-18 14:10:29.552  7792  7833 W AudioCapabilities: Unsupported mime audio/ac3
08-18 14:10:29.553  7792  7833 W AudioCapabilities: Unsupported mime audio/g726
08-18 14:10:29.553  7792  7833 W AudioCapabilities: Unsupported mime audio/wma-voice
08-18 14:10:29.554  7792  7833 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-18 14:10:29.555  7792  7833 W AudioCapabilities: Unsupported mime audio/adpcm
08-18 14:10:29.557  7792  7833 W VideoCapabilities: Unsupported mime video/theora
08-18 14:10:29.558  7792  7833 W VideoCapabilities: Unsupported mime video/mjpg
,08-18 14:10:29.601  1034  1935 W libprocessgroup: failed to open /acct/uid_1000/pid_6956/cgroup.procs: No such file or directory
08-18 14:10:29.634  7843  7843 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-18 14:10:29.635  7843  7843 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-18 14:10:29.635  7843  7843 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-18 14:10:29.637  7843  7843 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-18 14:10:29.638  7843  7843 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-18 14:10:29.720  7843  7843 I SystemConfig: BUILD Country: EU
08-18 14:10:29.720  7843  7843 I SystemConfig: BUILD Operator: OPEN
,08-18 14:10:29.764  1034  2054 I ActivityManager: Killing 7172:com.lge.email/u0a23 (adj 15): empty #17
,08-18 14:10:29.873  1034  1810 W libprocessgroup: failed to open /acct/uid_10023/pid_7172/cgroup.procs: No such file or directory
,08-18 14:10:29.888  1034  1547 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
,08-18 14:10:29.918  1034  1943 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7863 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-18 14:10:29.922  7843  7861 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-18 14:10:29.923  7843  7861 I SystemConfig: existFile = false
08-18 14:10:29.923  7843  7861 I SystemConfig: canReadFile = false
08-18 14:10:29.923  7843  7861 I SystemConfig: systemFeature RCS result false
08-18 14:10:29.923  7843  7861 D SystemConfig: refreshRcsSupport() :false
,08-18 14:10:29.982  7863  7863 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-18 14:10:29.983  7863  7863 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-18 14:10:29.983  7863  7863 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-18 14:10:29.983  7863  7863 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-18 14:10:30.058  7863  7863 I AppConfig: Total System Memory = 2995761152
,08-18 14:10:30.065  7863  7863 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
08-18 14:10:30.138  1034  1622 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7882 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-18 14:10:30.138  1034  1622 I ActivityManager: Killing 7024:com.lge.formmanager/u0a26 (adj 15): empty #17
,08-18 14:10:30.197  1034  1577 W libprocessgroup: failed to open /acct/uid_10026/pid_7024/cgroup.procs: No such file or directory
,08-18 14:10:30.427  7882  7882 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-18 14:10:30.494  7882  7882 D LgDataFeature: LgDataFeature() Constructor: none
,08-18 14:10:30.494  7882  7882 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-18 14:10:30.551  7882  7882 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-18 14:10:30.584  7882  7882 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-18 14:10:30.586  7882  7882 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-18 14:10:30.603  7882  7882 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-18 14:10:30.603  7882  7882 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-18 14:10:30.627  1034  2023 I ActivityManager: Killing 6505:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,08-18 14:10:30.672  1034  1810 W libprocessgroup: failed to open /acct/uid_1000/pid_6505/cgroup.procs: No such file or directory
,08-18 14:10:30.677  3539  4545 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-18 14:10:30.683  3539  4545 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@2b57b973 on behalf of 7882
08-18 14:10:30.687  4623  7922 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,08-18 14:10:30.745  1034  1622 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7923 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-18 14:10:30.773   348   348 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 443us total 22.451ms
,08-18 14:10:30.793   348   348 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 419us total 19.152ms
08-18 14:10:30.808  7882  7882 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-18 14:10:30.813   348   348 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 426us total 19.532ms
08-18 14:10:30.854  7882  7882 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-18 14:10:30.872  7923  7923 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-18 14:10:30.902  7923  7923 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
,08-18 14:10:30.902  7923  7923 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-18 14:10:30.902  7923  7923 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-18 14:10:30.902  7923  7923 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-18 14:10:30.902  7923  7923 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-18 14:10:30.902  7923  7923 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,08-18 14:10:30.929  1034  1989 I ActivityManager: Killing 7214:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,08-18 14:10:30.967  1034  1051 W libprocessgroup: failed to open /acct/uid_10046/pid_7214/cgroup.procs: No such file or directory
,08-18 14:10:31.157  7691  7733 D UEI.SmartControl: Internal timer expired: 1
08-18 14:10:31.157  7691  7733 D UEI.SmartControl: unbind internal service
,08-18 14:10:31.164  1034  2013 V SIM_STK : Menu title from STK is T-Mobile
08-18 14:10:31.164  7691  7691 D UEI.SmartControl: Service.onUnbind: IControl
08-18 14:10:31.166  7691  7691 D UEI.SmartControl: Service.onDestroy
08-18 14:10:31.167  7691  7691 D UEI.SmartControl: Lock is in USE false
08-18 14:10:31.167  7691  7691 D UEI.SmartControl: unbind internal service
08-18 14:10:31.169  7691  7691 D serial_port: close(fd = 25)
08-18 14:10:31.173  7691  7691 I UEI.SmartControl: Serial port is closed.
,08-18 14:10:31.173  7691  7691 I UEI.SmartControl: Serial port is closed.
08-18 14:10:31.173  7691  7691 D UEI.SmartControl: Blaster closed
08-18 14:10:31.174  7691  7691 D UEI.SmartControl: Shut down QS...
08-18 14:10:31.174  7691  7691 D UEI.SmartControl: Stopping QS lib
08-18 14:10:31.175  7691  7691 D UEI.SmartControl: QS lib stop result = true
08-18 14:10:31.175  7691  7691 D UEI.SmartControl: Stopped QS lib
08-18 14:10:31.176  7691  7691 D UEI.SmartControl: Stopped file observer...
08-18 14:10:31.176  7691  7691 D UEI.SmartControl: QS shutdown complete
08-18 14:10:31.194  4623  7922 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 507 ms] updated apps [took 507 ms] 
,08-18 14:10:31.910  6817  6895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-18 14:10:31.910  6817  6895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2e9b2f39 added. We now have 6 listener(s)
08-18 14:10:31.910  6817  6895 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-18 14:10:31.920  6817  6895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-18 14:10:31.920  6817  6895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1f8ca97e added. We now have 7 listener(s)
08-18 14:10:31.920  6817  6895 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-18 14:10:31.920  6817  6895 I System.out: IsBluetoothEnabled
08-18 14:10:31.921  1034  1989 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-18 14:10:31.921  1034  1989 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
08-18 14:10:31.922  1034  1101 D BluetoothManagerService: Message: 2
08-18 14:10:31.925  6817  6895 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 14:10:31.927  1034  1943 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-18 14:10:31.927  1034  1943 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-18 14:10:31.945  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-18 14:10:31.946  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,08-18 14:10:31.946  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-18 14:10:31.949  1034  1101 D BluetoothManagerService: Message: 1
08-18 14:10:31.949  1034  1101 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-18 14:10:31.974  1034  1101 D BluetoothManagerService: Message: 20
08-18 14:10:31.974  1034  1101 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1c94b49f:true
,08-18 14:10:31.978  7763  7763 D BluetoothAdapterState: make
08-18 14:10:31.983  7763  7763 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-18 14:10:31.983  7763  7763 I bluedroid-qcom: init
08-18 14:10:31.984  7763  7962 I BluetoothAdapterState: Entering OffState
08-18 14:10:31.985  7763  7763 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-18 14:10:31.985  7763  7763 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-18 14:10:31.985  7763  7763 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-18 14:10:31.985  7763  7763 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-18 14:10:31.985  7763  7763 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-18 14:10:31.987  7763  7763 I bluedroid-qcom: get_profile_interface socket
08-18 14:10:31.987  7763  7763 I bluedroid-qcom: get_profile_interface map_client
,08-18 14:10:31.992  7763  7966 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-18 14:10:31.994  7763  7966 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-18 14:10:31.984  7965  7965 W bdaddr_loader: type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-18 14:10:31.994  7965  7965 W bdaddr_loader: type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-18 14:10:32.007  1034  1034 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-18 14:10:32.007  1034  1034 D BluetoothManagerService: Stored Bluetooth name: G3
,08-18 14:10:32.011  7965  7965 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-18 14:10:32.011  7965  7965 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-18 14:10:32.011  7965  7965 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-18 14:10:32.012  1034  1034 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-18 14:10:32.013  1034  1101 D BluetoothManagerService: Message: 40
08-18 14:10:32.013  1034  1101 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-18 14:10:32.014  7763  7778 I bluedroid-qcom: config_hci_snoop_log
08-18 14:10:32.015  1034  1101 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-18 14:10:32.015  1034  1101 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-18 14:10:32.015  7965  7965 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-18 14:10:32.019  7763  7966 D BluetoothAdapterProperties: Name is: G3
08-18 14:10:32.021  7965  7965 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-18 14:10:32.021  7965  7965 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
,08-18 14:10:32.029  7763  7962 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-18 14:10:32.029  7763  7962 D BluetoothAdapterProperties: Setting state to 11
08-18 14:10:32.029  7763  7962 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-18 14:10:32.030  1034  1101 D BluetoothManagerService: Message: 60
08-18 14:10:32.030  1034  1101 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-18 14:10:32.030  1034  1101 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-18 14:10:32.033  7763  7962 I LGBluetoothServiceJni: classInitNative: succeeds
08-18 14:10:32.040  1944  1944 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-18 14:10:32.043  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 14:10:32.042  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-18 14:10:32.049  6913  6913 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-18 14:10:32.054  7763  7763 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-18 14:10:32.054  7763  7763 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-18 14:10:32.054  7763  7763 V BluetoothPbapReceiver: ***********state = 11
,08-18 14:10:32.076  2161  2161 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-18 14:10:32.076  7763  7962 D BluetoothBondStateMachine: make
08-18 14:10:32.080  7763  7962 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26de102a
08-18 14:10:32.080  7763  7962 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-18 14:10:32.080  7763  7962 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26de102a
08-18 14:10:32.080  7763  7962 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-18 14:10:32.081  7763  7962 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-18 14:10:32.082  7763  7980 I BluetoothBondStateMachine: StableState(): Entering Off State
08-18 14:10:32.086  7763  7962 E BluetoothAdapterService: File transfer profiles supported!!
08-18 14:10:32.097  7763  7763 D HeadsetService: Received start request. Starting profile...
08-18 14:10:32.097  7763  7763 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-18 14:10:32.097  6913  6913 D BluetoothPermissionRequest: onReceive
08-18 14:10:32.098  7763  7763 D LGBluetoothHfpAdapter: Version 1.6
08-18 14:10:32.099  7763  7962 E BluetoothAdapterService: File transfer profiles supported!!
08-18 14:10:32.101  7763  7763 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-18 14:10:32.102  7763  7763 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-18 14:10:32.103  7763  7763 D HeadsetStateMachine: make
08-18 14:10:32.103  6913  6913 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-18 14:10:32.121  7763  7962 E BluetoothAdapterService: File transfer profiles supported!!
,08-18 14:10:32.130  7763  7962 E BluetoothAdapterService: File transfer profiles supported!!
,08-18 14:10:32.137  7763  7962 E BluetoothAdapterService: File transfer profiles supported!!
,08-18 14:10:32.143  7763  7962 E BluetoothAdapterService: File transfer profiles supported!!
08-18 14:10:32.146  7763  7763 D LgDataFeature: LgDataFeature() Constructor: none
08-18 14:10:32.146  7763  7763 D LgDataFeature: LgDataFeature() Constructor Done, null
08-18 14:10:32.148  7763  7962 E BluetoothAdapterService: File transfer profiles supported!!
08-18 14:10:32.151  7763  7763 D HeadsetStateMachine: max_hf_connections = 1
08-18 14:10:32.151  7763  7763 I bluedroid-qcom: get_profile_interface handsfree
08-18 14:10:32.154  7763  7763 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-18 14:10:32.154   314  1385 V AudioPolicyService: registerClient() client 0xb558a540, uid 1002
08-18 14:10:32.155   314  2149 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-18 14:10:32.155   314  2149 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-18 14:10:32.155   314  2149 V AudioPolicyManagerEx: getOutput() returns output 2
08-18 14:10:32.155  7763  7763 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-18 14:10:32.155   314  1386 V AudioFlinger: registerClient() client 0xb5581610, pid 7763
,08-18 14:10:32.156   314  1379 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-18 14:10:32.156   314  1379 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-18 14:10:32.157  3466  3488 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-18 14:10:32.157  3466  3488 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-18 14:10:32.157  1034  1943 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-18 14:10:32.157  1034  1943 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-18 14:10:32.157  1855  2737 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-18 14:10:32.157  1855  2737 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-18 14:10:32.157  1605  1628 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-18 14:10:32.157  1605  1628 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-18 14:10:32.157   314  1381 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-18 14:10:32.157   314  1381 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-18 14:10:32.158  1855  2482 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-18 14:10:32.158  1855  2482 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-18 14:10:32.158  1034  1050 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-18 14:10:32.158  1605  2280 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-18 14:10:32.158  3466  3486 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-18 14:10:32.158  3466  3486 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-18 14:10:32.158  7763  7778 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-18 14:10:32.158  7763  7778 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-18 14:10:32.158  7763  7778 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-18 14:10:32.158  1605  2280 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-18 14:10:32.158  7763  7778 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-18 14:10:32.158  1034  1050 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-18 14:10:32.159  7763  7763 V ToneGenerator: Create Track: 0xb4928080
08-18 14:10:32.159  7763  7763 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-18 14:10:32.159  7763  7763 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-18 14:10:32.159   314   314 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-18 14:10:32.159   314   314 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-18 14:10:32.159   314   314 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-18 14:10:32.160   314   314 V AudioPolicyManagerEx: getOutput() returns output 2
08-18 14:10:32.161   314  1385 I AudioFlinger: isAudioPlaybackHookOn() false
08-18 14:10:32.161   314  2149 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-18 14:10:32.161   314  2149 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-18 14:10:32.161   314  2149 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-18 14:10:32.161   314  2149 V AudioPolicyManagerEx: getOutput() returns output 2
08-18 14:10:32.161  7763  7763 V AudioSystem: getLatency() output 2, latency 50
08-18 14:10:32.161  7763  7763 V AudioSystem: getFrameCount() output 2, frameCount 960
08-18 14:10:32.161  7763  7763 V AudioTrack: createTrack_l() output 2 afLatency 50
08-18 14:10:32.161   314  1386 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-18 14:10:32.161   314  1386 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), ,curLvl = 31 
08-18 14:10:32.161   314  1386 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-18 14:10:32.161   314  1386 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-18 14:10:32.161   314  1386 V AudioFlinger: createTrack() lSessionId: 23
08-18 14:10:32.162  7763  7763 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-18 14:10:32.162   314  1386 V AudioFlinger: acquiring 23 from 7763, for 7763
08-18 14:10:32.162   314  1386 V AudioFlinger:  added new entry for 23
08-18 14:10:32.163  7763  7763 V ToneGenerator: ToneGenerator INIT OK, time: 212906
08-18 14:10:32.163  7763  7763 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26de102a
08-18 14:10:32.164  7763  7982 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-18 14:10:32.164  7763  7982 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-18 14:10:32.164  7763  7982 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-18 14:10:32.165  7763  7763 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26de102a
08-18 14:10:32.165  7763  7982 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-18 14:10:32.165   314  2148 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7763
,08-18 14:10:32.169  7763  7763 D A2dpService: Received start request. Starting profile...
,08-18 14:10:32.170  7763  7763 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-18 14:10:32.171  7763  7763 V Avrcp   : make
08-18 14:10:32.171  7763  7962 V LGMDMManager: Create singleton instance
08-18 14:10:32.171  7763  7763 D Avrcp   : [BTUI] Use Native AVRCP : init jni
,08-18 14:10:32.172  7763  7763 I bluedroid-qcom: get_profile_interface avrcp
08-18 14:10:32.174  7763  7962 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-18 14:10:32.176   314  2148 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-18 14:10:32.176   314  2148 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-18 14:10:32.176   314  2148 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
,08-18 14:10:32.176   314  2148 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-18 14:10:32.176   314  2148 V voice   : voice_set_parameters: exit with code(0)
08-18 14:10:32.176   314  2148 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-18 14:10:32.176   314  2148 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-18 14:10:32.176   314  2148 V msm8974_platform: platform_set_parameters: exit with code(0)
,08-18 14:10:32.176   314  2148 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-18 14:10:32.176   314  2148 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-18 14:10:32.176   314  2148 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-18 14:10:32.177  7763  7982 V ToneGenerator: ToneGenerator destructor
08-18 14:10:32.177  7763  7982 V ToneGenerator: stopTone
,08-18 14:10:32.177  7763  7982 V ToneGenerator: Delete Track: 0xb4928080
08-18 14:10:32.177   314   314 V AudioPolicyService: AudioCommandThread() adding release output 2
08-18 14:10:32.177   314   314 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-18 14:10:32.177   314  1259 V AudioPolicyService: AudioCommandThread() waking up
08-18 14:10:32.177   314  1259 V AudioPolicyService: AudioCommandThread() processing release output 2
,08-18 14:10:32.177   314  1259 V AudioPolicyManager: releaseOutput() 2
08-18 14:10:32.177   314  1259 V AudioPolicyService: AudioCommandThread() going to sleep
08-18 14:10:32.177   314   314 V AudioFlinger: PlaybackThread::Track destructor
08-18 14:10:32.177   314   314 V AudioFlinger: removeClient_l() pid 7763, calling pid 314
08-18 14:10:32.178  7763  7982 V AudioTrack: ~AudioTrack, releasing session id from 7763 on behalf of 7763
,08-18 14:10:32.178   314  1386 V AudioFlinger: releasing 23 from 7763 for 7763
08-18 14:10:32.178   314  1386 V AudioFlinger:  decremented refcount to 0
08-18 14:10:32.178   314  1386 V AudioFlinger: purging stale effects
08-18 14:10:32.180  7763  7763 V AudioManager: registerRemoteController: size of Media player list: 0
08-18 14:10:32.182  7763  7763 E AudioManager: No RCC entry present to update
08-18 14:10:32.182  7763  7763 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-18 14:10:32.185  7763  7763 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-18 14:10:32.187  7763  7763 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-18 14:10:32.187  7763  7763 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-18 14:10:32.191  7763  7763 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-18 14:10:32.343  1034  2035 V SIM_STK : Menu title from STK is T-Mobile
08-18 14:10:32.343  1034  2035 V SIM_STK : Menu title from STK is T-Mobile
,08-18 14:10:32.469  1034  1901 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-18 14:10:32.479  7763  7763 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-18 14:10:32.483  7763  7763 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
,08-18 14:10:32.483  7763  7763 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-18 14:10:32.483  7763  7763 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-18 14:10:32.483  7763  7763 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-18 14:10:32.483  7763  7763 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-18 14:10:32.483  7763  7763 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-18 14:10:32.483  7763  7763 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-18 14:10:32.483  7763  7763 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-18 14:10:32.484  7763  7763 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-18 14:10:32.484  7763  7763 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-18 14:10:32.484  7763  7763 I BluetoothA2dpServiceJni: classInitNative
08-18 14:10:32.484  7763  7763 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-18 14:10:32.484  7763  7763 D A2dpStateMachine: make
08-18 14:10:32.487  7763  7763 I bluedroid-qcom: get_profile_interface a2dp
08-18 14:10:32.488  7763  7993 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-18 14:10:32.490  7763  7763 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-18 14:10:32.490  7763  7763 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-18 14:10:32.491  7763  7763 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26de102a
08-18 14:10:32.491  7763  7991 D A2dpStateMachine: Enter Disconnected: -2
08-18 14:10:32.491  7763  7763 I BluetoothHidServiceJni: classInitNative: succeeds
08-18 14:10:32.493  7763  7763 D HidService: Received start request. Starting profile...
08-18 14:10:32.493  7763  7763 I bluedroid-qcom: get_profile_interface hidhost
08-18 14:10:32.493  7763  7763 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26de102a
08-18 14:10:32.493  7763  7763 I BluetoothHealthServiceJni: classInitNative: succeeds
08-18 14:10:32.494  7763  7763 D HealthService: Received start request. Starting profile...
08-18 14:10:32.497  7763  7763 I bluedroid-qcom: get_profile_interface health
08-18 14:10:32.497  7763  7763 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-18 14:10:32.497  7763  7763 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26de102a
08-18 14:10:32.498  7763  7763 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-18 14:10:32.500  7763  7763 D PanService: Received start request. Starting profile...
08-18 14:10:32.500  7763  7763 D BluetoothPanServiceJni: initializeNative(L110): pan
08-18 14:10:32.500  7763  7763 I bluedroid-qcom: get_profile_interface pan
,08-18 14:10:32.515  7763  7763 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-18 14:10:32.516  7763  7763 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26de102a
08-18 14:10:32.518  7763  7763 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
,08-18 14:10:32.524  7763  7763 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-18 14:10:32.525  7763  7763 D BtGatt.GattService: Received start request. Starting profile...
08-18 14:10:32.525  7763  7763 D BtGatt.GattService: start()
08-18 14:10:32.525  7763  7763 I bluedroid-qcom: get_profile_interface gatt
08-18 14:10:32.525  7763  7763 D BtGatt.AdvertiseManager: advertise manager created
08-18 14:10:32.533  7763  7763 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26de102a
08-18 14:10:32.534  7763  7763 D HeadsetStateMachine: Proxy object connected
08-18 14:10:32.534  7763  7763 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
,08-18 14:10:32.534  7763  7763 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-18 14:10:32.537  7763  7763 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26de102a
08-18 14:10:32.537  7763  7763 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-18 14:10:32.538  7763  7763 V BluetoothMapService: BluetoothMapBinder()
08-18 14:10:32.538  7763  7763 D BluetoothMapService: Received start request. Starting profile...
08-18 14:10:32.538  7763  7763 D BluetoothMapService: start()
08-18 14:10:32.541  7763  7763 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-18 14:10:32.541  7763  7763 D BluetoothMapEmailAppObserver: createReceiver()
08-18 14:10:32.542  7763  7763 D BluetoothMapEmailAppObserver: initObservers()
08-18 14:10:32.542  7763  7763 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-18 14:10:32.548  7763  7763 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26de102a
,08-18 14:10:32.550  7763  7763 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-18 14:10:32.551  7763  7982 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-18 14:10:32.551  7763  7982 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-18 14:10:32.551  7763  7982 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-18 14:10:32.552  7763  7763 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-18 14:10:32.556  7763  7763 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-18 14:10:32.558  7763  7763 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-18 14:10:32.561  7763  7763 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-18 14:10:32.561  7763  7763 V PanService: [BTUI] SIM Extra State :ABSENT
,08-18 14:10:32.566  7763  7763 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-18 14:10:32.569  7763  7763 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-18 14:10:32.569  7763  7763 V BluetoothMapService: Handler(): got msg=1
08-18 14:10:32.569  7763  7962 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-18 14:10:32.569  7763  7763 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-18 14:10:32.569  7763  7962 I bluedroid-qcom: enable
08-18 14:10:32.569  7763  7763 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-18 14:10:32.569  7763  7763 V BluetoothSapReceiver: SapReceiver onReceive 
08-18 14:10:32.570  7763  7763 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-18 14:10:32.570  7763  7962 I bt_hci_bdroid: init
08-18 14:10:32.570  7763  7763 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-18 14:10:32.570  7763  7962 I bt_vendor: bt-vendor : init
08-18 14:10:32.570  7763  7962 I bt_vendor: bt-vendor : get_bt_soc_type
08-18 14:10:32.570  7763  7962 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-18 14:10:32.570  7763  7962 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-18 14:10:32.570  7763  7962 D bt_userial_mct: userial_init
08-18 14:10:32.571  7763  7962 D bt_hci_bdroid: set_power 1
08-18 14:10:32.571  7763  7962 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-18 14:10:32.571  7763  7962 I bt_vendor: Starting hciattach daemon
08-18 14:10:32.571  7763  7962 I bt_vendor: try to set true
08-18 14:10:32.564  8006  8006 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-18 14:10:32.564  8006  8006 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-18 14:10:32.572  7763  8003 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,08-18 14:10:32.582  7763  8003 I bt-btu  : btu_task pending for preload complete event
08-18 14:10:32.593  8007  8007 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-18 14:10:32.667  8013  8013 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-18 14:10:32.687  8014  8014 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-18 14:10:32.712  8016  8016 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-18 14:10:32.724  8017  8017 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
08-18 14:10:32.735  8018  8018 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-18 14:10:32.747  8019  8019 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
08-18 14:10:32.768  8021  8021 I libmdmdetect: ESOC framework not supported
08-18 14:10:32.769  8021  8021 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-18 14:10:32.777  8021  8021 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,08-18 14:10:32.777  8021  8021 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
,08-18 14:10:32.777  8021  8021 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-18 14:10:32.777  8021  8021 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
,08-18 14:10:32.777  8021  8021 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-18 14:10:32.777  8021  8021 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-18 14:10:32.777  8021  8021 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
,08-18 14:10:32.813  8021  8022 E QC-QMI  : qmi_client [8021] 15: failed to locate client data
08-18 14:10:32.813   474   474 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
,08-18 14:10:32.813   474   474 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,08-18 14:10:32.859  8023  8023 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-18 14:10:32.873  8024  8024 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-18 14:10:32.923  7763  7962 I bt_vendor: bluetooth satus is on
,08-18 14:10:32.923  7763  7962 D bt_hci_bdroid: preload
,08-18 14:10:32.924  7763  8005 D bt_userial_mct: userial_open(port:0)
08-18 14:10:32.924  7763  8005 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-18 14:10:32.928  7763  8005 I bt_vendor: Done intiailizing UART
08-18 14:10:32.932  7763  8005 I bt_vendor: Done intiailizing UART
08-18 14:10:32.932  7763  8005 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-18 14:10:32.933  7763  8005 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-18 14:10:32.933  7763  8003 I bt-btu  : btu_task received preload complete event
08-18 14:10:32.935  7763  8003 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
,08-18 14:10:32.935  7763  8003 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-18 14:10:32.935  7763  8026 D bt_userial_mct: Entering userial_read_thread()
,08-18 14:10:32.942  7763  8003 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
,08-18 14:10:32.953  7763  8003 I         : BTE_InitTraceLevels -- TRC_HCI
,08-18 14:10:32.953  7763  8003 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-18 14:10:32.953  7763  8003 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-18 14:10:32.953  7763  8003 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-18 14:10:32.953  7763  8003 I         : BTE_InitTraceLevels -- TRC_AVRC
08-18 14:10:32.953  7763  8003 I         : BTE_InitTraceLevels -- TRC_A2D
08-18 14:10:32.953  7763  8003 I         : BTE_InitTraceLevels -- TRC_BNEP
08-18 14:10:32.953  7763  8003 I         : BTE_InitTraceLevels -- TRC_BTM
,08-18 14:10:32.953  7763  8003 I         : BTE_InitTraceLevels -- TRC_HID_HOST,
,08-18 14:10:32.953  7763  8003 I         : BTE_InitTraceLevels -- TRC_GAP
,08-18 14:10:32.953  7763  8003 I         : BTE_InitTraceLevels -- TRC_PAN
08-18 14:10:32.954  7763  8003 I         : BTE_InitTraceLevels -- TRC_SDP
08-18 14:10:32.954  7763  8003 I         : BTE_InitTraceLevels -- TRC_GATT
,08-18 14:10:32.954  7763  8003 I         : BTE_InitTraceLevels -- TRC_SMP,
08-18 14:10:32.954  7763  8003 I         : BTE_InitTraceLevels -- TRC_BTAPP,
08-18 14:10:32.954  7763  8003 I         : BTE_InitTraceLevels -- TRC_BTIF,
,08-18 14:10:33.056  7763  8003 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled,
,08-18 14:10:33.075  7763  8003 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0174061 
08-18 14:10:33.077  7763  8003 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0174061 
08-18 14:10:33.092  7763  7966 E bt-btif : Calling BTA_HhEnable
08-18 14:10:33.092  7763  7966 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-18 14:10:33.092  7763  7966 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-18 14:10:33.096  7763  7966 D BluetoothAdapterProperties: Name is: G3
08-18 14:10:33.098  1034  1034 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-18 14:10:33.098  1034  1034 D BluetoothManagerService: Stored Bluetooth name: G3
08-18 14:10:33.098  7763  7966 D BluetoothAdapterProperties: Scan Mode:20
08-18 14:10:33.099  7763  7966 D BluetoothAdapterProperties: Discoverable Timeout:120
08-18 14:10:33.099  7763  7966 D bt_hci_bdroid: postload
08-18 14:10:33.100  7763  7966 D bte_conf: Device ID record 1 : primary
08-18 14:10:33.100  7763  7966 D bte_conf:   vendorId            = 00c4
08-18 14:10:33.100  7763  7966 D bte_conf:   vendorIdSource      = 0001
08-18 14:10:33.100  7763  7966 D bte_conf:   product             = 13a1
08-18 14:10:33.100  7763  7966 D bte_conf:   version             = 1000
08-18 14:10:33.100  7763  7966 D bte_conf:   clientExecutableURL = 
08-18 14:10:33.100  7763  7966 D bte_conf:   serviceDescription  = 
08-18 14:10:33.100  7763  7966 D bte_conf:   documentationURL    = 
08-18 14:10:33.100  7763  8005 D bt_hci_bdroid: Used up Tx Cmd credits
08-18 14:10:33.100  7763  7966 D bte_conf: bte_load_did_conf no section named DID2.
08-18 14:10:33.104  8031  8031 W sh      : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-18 14:10:33.111  7763  7962 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-18 14:10:33.112  7763  7962 D BluetoothAdapterProperties: ScanMode =  20
08-18 14:10:33.112  7763  7962 D BluetoothAdapterProperties: State =  11
08-18 14:10:33.113  7763  7962 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-18 14:10:33.113  7763  7962 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-18 14:10:33.113  7763  7962 D BluetoothAdapterProperties: Setting state to 12
08-18 14:10:33.113  7763  7962 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-18 14:10:33.114  7763  7966 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-18 14:10:33.114  8031  8031 W sh      : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-18 14:10:33.120  7763  7962 I BluetoothAdapterState: Entering On State
,08-18 14:10:33.127  1034  1101 D BluetoothManagerService: Message: 60
08-18 14:10:33.127  1034  1101 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-18 14:10:33.127  1034  1101 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
08-18 14:10:33.127  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 14:10:33.140  7763  8003 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-18 14:10:33.140  7763  8003 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-18 14:10:33.140  7763  8003 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-18 14:10:33.140  7763  8003 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-18 14:10:33.140  7763  8003 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-18 14:10:33.140  7763  8003 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
,08-18 14:10:33.149  7763  7966 D BluetoothAdapterProperties: Discoverable Timeout:120
08-18 14:10:33.149  7763  7966 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-18 14:10:33.150  7763  7966 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-18 14:10:33.157  7763  7962 D LGBluetoothServiceAdapter: [BTUI] OnState
08-18 14:10:33.157  7763  7962 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-18 14:10:33.157  7763  7962 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,08-18 14:10:33.160  7763  7962 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-18 14:10:33.161  7763  8005 D bt_hci_bdroid: Used up Tx Cmd credits
08-18 14:10:33.185  7763  7962 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
,08-18 14:10:33.199  7763  8005 D bt_hci_bdroid: Used up Tx Cmd credits
,08-18 14:10:33.202  6913  6933 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-18 14:10:33.202  7763  8026 E bt_mct  : hci lib postload completed
08-18 14:10:33.207  1034  1101 D BluetoothHeadset: onBluetoothStateChange: up=true
08-18 14:10:33.209  1034  1034 D BluetoothHeadset: Proxy object connected
08-18 14:10:33.211  7763  8003 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-18 14:10:33.211  7763  8003 W bt-smp  : Plain text(LSB ~ MSB) = 02 f1 70 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-18 14:10:33.211  7763  8003 W bt-smp  : Encrypted text(LSB ~ MSB) = e5 4e 83 58 c0 12 9c ec 95 e0 74 a5 e7 c7 b1 74 
,08-18 14:10:33.211  7763  8003 W bt-btm  : Stopping oneshot timer
,08-18 14:10:33.214  6913  6932 D BluetoothA2dp: onBluetoothStateChange: up=true
08-18 14:10:33.219  1855  1871 D BluetoothHeadset: onBluetoothStateChange: up=true
08-18 14:10:33.224  8045  8045 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,08-18 14:10:33.228  1855  1855 D BluetoothHeadset: Proxy object connected
,08-18 14:10:33.228  6913  6913 D BluetoothInputDevice: Proxy object connected
08-18 14:10:33.229  6913  6913 D HidProfile: Bluetooth service connected
08-18 14:10:33.229  1855  2482 D BluetoothHeadset: onBluetoothStateChange: up=true
08-18 14:10:33.232  1855  1855 D BluetoothHeadset: Proxy object connected
08-18 14:10:33.232  6913  6913 D BluetoothA2dp: Proxy object connected
08-18 14:10:33.232  6913  6913 D A2dpProfile: Bluetooth service connected
08-18 14:10:33.233  1855  2737 D BluetoothHeadset: onBluetoothStateChange: up=true
08-18 14:10:33.235  1855  1855 D BluetoothHeadset: Proxy object connected
08-18 14:10:33.235  6913  7650 D BluetoothHeadset: onBluetoothStateChange: up=true
08-18 14:10:33.238  7763  8003 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-18 14:10:33.238  7763  8003 W bt-smp  : Plain text(LSB ~ MSB) = d9 ad 6d 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-18 14:10:33.238  7763  8003 W bt-smp  : Encrypted text(LSB ~ MSB) = b7 a4 b3 26 c3 2d a8 f7 38 37 b5 51 3f 32 5c c0 
08-18 14:10:33.238  7763  8003 W bt-btm  : Stopping oneshot timer
,08-18 14:10:33.240  6913  6913 D BluetoothHeadset: Proxy object connected
08-18 14:10:33.240  6913  6913 D HeadsetProfile: Bluetooth service connected
08-18 14:10:33.241  6913  6933 D BluetoothPbap: onBluetoothStateChange: up=true
08-18 14:10:33.243  1034  1101 D BluetoothA2dp: onBluetoothStateChange: up=true
08-18 14:10:33.244  1034  1034 D BluetoothA2dp: Proxy object connected
08-18 14:10:33.245  6913  6932 D BluetoothMap: onBluetoothStateChange: up=true
,08-18 14:10:33.250  6913  7650 D BluetoothPan: onBluetoothStateChange on: true
08-18 14:10:33.250  6913  7650 D BluetoothPan: onBluetoothStateChange call bindService
08-18 14:10:33.250  6913  6913 D BluetoothMap: Proxy object connected
08-18 14:10:33.251  6913  6913 D MapProfile: Bluetooth service connected
08-18 14:10:33.251  6913  6913 D BluetoothMap: getConnectedDevices()
,08-18 14:10:33.252  7763  8003 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-18 14:10:33.252  7763  8003 W bt-smp  : Plain text(LSB ~ MSB) = 15 d4 60 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-18 14:10:33.252  7763  8003 W bt-smp  : Encrypted text(LSB ~ MSB) = 2c ca 7d fb fd a2 79 b0 86 85 4b b1 37 45 d6 4d 
08-18 14:10:33.252  7763  8003 W bt-btm  : Stopping oneshot timer
08-18 14:10:33.254  7763  7778 V BluetoothMapService: getConnectedDevices()
08-18 14:10:33.258  6913  6913 D BluetoothPan: BluetoothPAN Proxy object connected
08-18 14:10:33.258  6913  6913 D PanProfile: Bluetooth service connected
08-18 14:10:33.259  1034  1101 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-18 14:10:33.259  1034  1101 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-18 14:10:33.262  1944  1944 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-18 14:10:33.262  1944  2130 D LGBluetoothAPIService: Message: 1
08-18 14:10:33.262  1944  2130 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-18 14:10:33.262  7763  8003 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-18 14:10:33.262  1944  2130 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
08-18 14:10:33.262  7763  8003 W bt-smp  : Plain text(LSB ~ MSB) = a4 27 61 00 00 00 00 00 00 00 00 00 00 00 00 00 
,08-18 14:10:33.262  1944  2130 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-18 14:10:33.262  7763  8003 W bt-smp  : Encrypted text(LSB ~ MSB) = 3f d1 e0 6d ea 7d 86 7a 49 29 3c 7d f0 c3 06 d9 
08-18 14:10:33.263  7763  8003 W bt-btm  : Stopping oneshot timer
08-18 14:10:33.266  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-18 14:10:33.276  7763  7763 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-18 14:10:33.276  7763  7763 D BluetoothMapService: STATE_ON
,08-18 14:10:33.276  7763  7763 V BluetoothMapService: Handler(): got msg=1
08-18 14:10:33.278  7763  7763 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-18 14:10:33.279  7763  8003 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-18 14:10:33.279  7763  8003 W bt-smp  : Plain text(LSB ~ MSB) = 15 40 53 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-18 14:10:33.279  7763  8003 W bt-smp  : Encrypted text(LSB ~ MSB) = 43 b4 84 39 4c 11 22 37 22 34 b6 f9 36 4f 29 31 
08-18 14:10:33.279  7763  8003 W bt-btm  : Stopping oneshot timer
08-18 14:10:33.286  7763  8055 D BluetoothMapMasInstance: MAS initSocket()
08-18 14:10:33.287  7763  8055 D BluetoothMapMasInstance:   masId = 00
08-18 14:10:33.287  7763  8055 D BluetoothMapMasInstance:   msgTypes = 0e
08-18 14:10:33.287  7763  8055 D BluetoothMapMasInstance:   masName = SMS/MMS
08-18 14:10:33.287  7763  8055 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-18 14:10:33.289  1034  1623 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-18 14:10:33.289  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-18 14:10:33.289  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 14:10:33.289  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-18 14:10:33.289  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-18 14:10:33.289  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-18 14:10:33.289  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-18 14:10:33.289  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-18 14:10:33.289  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-18 14:10:33.292  7763  8055 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-18 14:10:33.297  7763  8055 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-18 14:10:33.297  7763  8055 V BluetoothMapMasInstance: Succeed to create listening socket 
08-18 14:10:33.297  7763  8055 D BluetoothMapMasInstance: Accepting socket connection...
08-18 14:10:33.298  7763  7966 D BluetoothAdapterProperties: Scan Mode:21
08-18 14:10:33.298  7763  7966 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-18 14:10:33.299  6913  6913 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-18 14:10:33.301  7763  7763 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26de102a
08-18 14:10:33.302  7763  7763 V BluetoothPbapService: Pbap Service onCreate
08-18 14:10:33.302  7763  7763 V BluetoothPbapService: Starting PBAP service
08-18 14:10:33.303  6817  6817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-18 14:10:33.304  7763  7763 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-18 14:10:33.304  7763  7763 V BluetoothPbapService: Pbap Service onBind
,08-18 14:10:33.305  6913  6913 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-18 14:10:33.305  7763  7763 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-18 14:10:33.305  7763  7763 V BluetoothPbapService: state: 12
08-18 14:10:33.305  7763  7763 V BluetoothPbapService: Handler(): got msg=1
08-18 14:10:33.306  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 14:10:33.306  7763  7763 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-18 14:10:33.308  7763  8058 V BluetoothPbapService: Pbap Service initSocket
08-18 14:10:33.309  1034  1943 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-18 14:10:33.309  6913  6913 D BluetoothPbap: Proxy object connected
08-18 14:10:33.309  6913  6913 D PbapServerProfile: Bluetooth service connected
08-18 14:10:33.311  7763  8058 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-18 14:10:33.311  7763  7763 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-18 14:10:33.311  7763  7763 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-18 14:10:33.311  7763  7763 V BluetoothPbapReceiver: ***********state = 12
08-18 14:10:33.312  7763  8058 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-18 14:10:33.312  7763  8058 V BluetoothPbapService: Succeed to create listening socket 
08-18 14:10:33.312  7763  8058 V BluetoothPbapService: Accepting socket connection...
08-18 14:10:33.315  2161  2161 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-18 14:10:33.316  6913  6913 D DockEventReceiver: finishStartingService: stopping service
,08-18 14:10:33.316  2161  2161 D c       : Getting all permits...
08-18 14:10:33.316  2161  2161 D a       : Opening database...
08-18 14:10:33.320  2161  2161 D a       : Opening database auth.proximity.permit_store...
08-18 14:10:33.321  2161  2161 D a       : Closing database...
08-18 14:10:33.331  6913  6913 D BluetoothPermissionRequest: onReceive
,08-18 14:10:33.333  6913  6913 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,08-18 14:10:33.335  6913  6913 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-18 14:10:33.338  7763  7763 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-18 14:10:33.339  7763  7763 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-18 14:10:33.345  7763  7763 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-18 14:10:33.366  7763  7763 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-18 14:10:33.367  7763  7763 V BtOppService: onCreate
08-18 14:10:33.371  7763  7763 V BluetoothOppNotification: send message
08-18 14:10:33.375  7763  7763 V BtOppService: Starting RfcommListener
08-18 14:10:33.381  7763  7763 D BluetoothOppPreference: Dumping Names:  
08-18 14:10:33.381  7763  7763 D BluetoothOppPreference: {}
08-18 14:10:33.381  7763  7763 D BluetoothOppPreference: Dumping Channels:  
08-18 14:10:33.381  7763  7763 D BluetoothOppPreference: {}
08-18 14:10:33.382  7763  7763 V BtOppService: onStartCommand
08-18 14:10:33.387  7763  7763 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-18 14:10:33.387  7763  7763 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-18 14:10:33.388  7763  8065 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
,08-18 14:10:33.396  7763  7763 V BluetoothOppNotification: new notify threadi!
08-18 14:10:33.397  7763  7763 V BluetoothOppNotification: send delay message
08-18 14:10:33.397  7763  7763 V BtOppService: start RfcommListener
08-18 14:10:33.400  7763  7763 V BtOppService: RfcommListener started
08-18 14:10:33.400  7763  8062 V BtOppService: Deleted complete outbound shares, number =  0
08-18 14:10:33.401  7763  8067 V BtOppRfcommListener: Starting RFCOMM listener....
08-18 14:10:33.402  1034  1810 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-18 14:10:33.402  7763  8062 V BtOppService: Deleted complete inbound failed shares, number = 0
08-18 14:10:33.403  7763  8067 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-18 14:10:33.403  7763  8062 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-18 14:10:33.404  7763  8067 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
08-18 14:10:33.404  7763  8066 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-18 14:10:33.404  7763  8067 V BtOppRfcommListener: Started RFCOMM listener....
08-18 14:10:33.404  7763  8067 I BtOppRfcommListener: Accept thread started.
08-18 14:10:33.404  7763  8067 V BtOppRfcommListener: Accepting connection...
08-18 14:10:33.405  7763  8065 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-18 14:10:33.406  7763  8062 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@b9ae106 on behalf of 
08-18 14:10:33.406  7763  8066 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3225d3c7 on behalf of 
08-18 14:10:33.407  7763  8065 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@338bfdf4 on behalf of 
08-18 14:10:33.415  7763  7763 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26de102a
08-18 14:10:33.416  7763  7763 V BluetoothFtpService: Ftp Service onCreate
08-18 14:10:33.416  7763  7763 I BluetoothFtpService: Ftp Service onCreate
08-18 14:10:33.416  7763  7763 V BluetoothFtpService: Ftp Service onStartCommand
08-18 14:10:33.416  7763  7763 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-18 14:10:33.416  7763  7763 V BluetoothFtpService: Starting Listening on sockets
08-18 14:10:33.417  7763  7763 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-18 14:10:33.417  7763  7763 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-18 14:10:33.417  7763  7763 V BluetoothSapReceiver: SapReceiver onReceive 
08-18 14:10:33.417  7763  7763 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-18 14:10:33.417  7763  7763 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-18 14:10:33.417  7763  7763 V BluetoothSapReceiver: Calling SAP service start service with action = null
,08-18 14:10:33.420  7763  8066 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-18 14:10:33.420  7763  7763 V BtOppService: ContentObserver received notification
08-18 14:10:33.421  7763  7763 V BtOppService: ContentObserver received notification
08-18 14:10:33.421  7763  7763 V BluetoothFtpService: Handler(): got msg=1
08-18 14:10:33.421  7763  7763 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-18 14:10:33.422  7763  7763 V BluetoothFtpService: Ftp Service initSocket
08-18 14:10:33.422  7763  8065 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-18 14:10:33.422  7763  8065 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-18 14:10:33.423  7763  8065 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@b740792 on behalf of 
08-18 14:10:33.424  7763  8066 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-18 14:10:33.425  7763  8065 V BluetoothOppNotification: update too frequent, put in queue
08-18 14:10:33.425  1034  1050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-18 14:10:33.427  7763  7763 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-18 14:10:33.427  7763  8065 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-18 14:10:33.427  7763  8066 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@27a1e563 on behalf of 
08-18 14:10:33.428  7763  7763 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=81 mFd=78
08-18 14:10:33.428  7763  7763 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-18 14:10:33.429  7763  8066 V BluetoothOppNotification: outbound: succ-0  fail-0
08-18 14:10:33.429  7763  8068 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-18 14:10:33.436  7763  8066 V BluetoothOppNotification: outbound notification was removed.
08-18 14:10:33.437  7763  8066 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
,08-18 14:10:33.439  7763  8066 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1650560 on behalf of 
08-18 14:10:33.440  7763  8066 V BluetoothOppNotification: inbound: succ-0  fail-0
08-18 14:10:33.444  7763  7763 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26de102a
08-18 14:10:33.444  7763  7763 V BluetoothSapService: Sap Service onCreate
08-18 14:10:33.447  7763  7763 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-18 14:10:33.447  7763  7763 V BluetoothSapService: state: 12
08-18 14:10:33.448  7763  7763 V BluetoothSapService: Starting SAP server process
08-18 14:10:33.448  1034  1034 I art     : Explicit concurrent mark sweep GC freed 28180(1382KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 2.683ms total 188.007ms
08-18 14:10:33.448  1034  1034 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-18 14:10:33.449  1034  1101 D BluetoothManagerService: Message: 40
08-18 14:10:33.449  1034  1101 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,08-18 14:10:33.444  8069  8069 W sapd    : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-18 14:10:33.444  8069  8069 W sapd    : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-18 14:10:33.449  7763  7763 V BluetoothSapService: SAP Service startRfcommListenerThread
08-18 14:10:33.451  7763  8070 V BluetoothSapService: Sap Service initRfcommSocket
08-18 14:10:33.451  7763  8066 V BluetoothOppNotification: inbound notification was removed.
08-18 14:10:33.451  7763  8066 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-18 14:10:33.452  1034  1935 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-18 14:10:33.454  7763  8070 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-18 14:10:33.454  7763  8070 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=81
08-18 14:10:33.455  7763  8070 V BluetoothSapService: Succeed to create listening socket 
08-18 14:10:33.455  7763  8070 V BluetoothSapService: Accepting socket connection...
08-18 14:10:33.460  7763  8066 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2c05178c on behalf of 
08-18 14:10:33.470  8069  8069 V BT_SAP  : Event pipe created
08-18 14:10:33.470  8069  8069 V BT_SAP  : create_server_socket qcom.sap.server
08-18 14:10:33.470  8069  8069 V BT_SAP  : created socket fd 6
,08-18 14:10:33.974  6817  6895 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-18 14:10:33.974  6817  6895 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 14:10:33.974  6817  6895 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-18 14:10:33.974  6817  6895 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-18 14:10:33.974  6817  6895 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-18 14:10:33.974  6817  6895 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-18 14:10:33.974  6817  6895 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-18 14:10:33.974  6817  6895 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-18 14:10:33.988  6817  6895 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-18 14:10:33.990  6817  6895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-18 14:10:33.990  6817  6895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1ffcbedf added. We now have 8 listener(s)
08-18 14:10:33.990  6817  6895 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-18 14:10:33.995  1034  2023 D WifiServiceImplEx: setWifiEnabled: false pid=6817, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-18 14:10:33.995  1034  2023 D WifiService: setWifiEnabled: false pid=6817, uid=10118
08-18 14:10:33.995  1034  2023 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-18 14:10:34.003  6817  6895 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 14:10:34.005  1034  1810 D WifiServiceImplEx: setWifiEnabled: true pid=6817, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-18 14:10:34.005  1034  1810 D WifiService: setWifiEnabled: true pid=6817, uid=10118
08-18 14:10:34.005  1034  1810 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-18 14:10:34.026  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-18 14:10:34.026  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-18 14:10:34.026  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-18 14:10:34.027  1034  1540 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-18 14:10:34.028  1034  1540 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-18 14:10:34.030  1034  1540 E WifiUtil: wfc_util_ffile_check_copy(): pid[1034] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-18 14:10:34.030  1034  1540 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-18 14:10:34.030  1034  1540 E WifiUtil: wfc_util_ffile_check_copy(): pid[1034] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-18 14:10:34.030  1034  1540 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-18 14:10:34.030  1034  1540 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-18 14:10:34.030  1034  1540 E WifiHW  : unknown target_country: EU , set to default
08-18 14:10:34.030  1034  1540 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-18 14:10:34.030  1034  1540 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-18 14:10:34.031  1034  1540 I WifiUtil: gEnableBmps=1
08-18 14:10:34.401  7763  7763 V BluetoothOppNotification: new notify threadi!
08-18 14:10:34.401  7763  7763 V BluetoothOppNotification: send delay message
,08-18 14:10:34.409  7763  8089 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-18 14:10:34.411  7763  8089 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@d9fded5 on behalf of 
08-18 14:10:34.411  7763  8089 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-18 14:10:34.412  7763  8089 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-18 14:10:34.413  7763  8089 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@30b4f6ea on behalf of 
08-18 14:10:34.414  7763  8089 V BluetoothOppNotification: outbound: succ-0  fail-0
,08-18 14:10:34.419  7763  8089 V BluetoothOppNotification: outbound notification was removed.
08-18 14:10:34.419  7763  8089 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-18 14:10:34.420  7763  8089 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3449ddb on behalf of 
08-18 14:10:34.421  7763  8089 V BluetoothOppNotification: inbound: succ-0  fail-0
08-18 14:10:34.422  7763  8089 V BluetoothOppNotification: inbound notification was removed.
08-18 14:10:34.422  7763  8089 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-18 14:10:34.423  7763  8089 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3eb22078 on behalf of 
08-18 14:10:34.587  1034  1101 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-18 14:10:34.587  1034  1101 D Tethering: InitialState.processMessage what=4
08-18 14:10:34.588  1034  1101 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-18 14:10:34.600   309   903 D SoftapController: Softap fwReload - Ok
08-18 14:10:34.606  1034  1540 E NetdConnector: NDC Command {84 softap fwreload wlan0 STA} took too long (570ms)
,08-18 14:10:34.612   309   903 D CommandListener: Setting iface cfg
08-18 14:10:34.612   309   903 D CommandListener: Trying to bring down wlan0
08-18 14:10:34.616   309   903 D CommandListener: Clearing all IP addresses on wlan0
08-18 14:10:34.628  1034  1540 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,08-18 14:10:34.624  8091  8091 W wpa_supplicant: type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-18 14:10:34.644  8091  8091 W wpa_supplicant: type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-18 14:10:34.677  1034  1540 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-18 14:10:34.677  1034  1540 E WifiStateMachine: useWiFiOffloading() : false
08-18 14:10:34.677  1034  1540 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-18 14:10:34.687  1034  1540 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-18 14:10:34.687  1034  1540 D WifiMonitor: connecting to supplicant
08-18 14:10:34.690  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-18 14:10:34.700  1944  1944 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-18 14:10:34.702  6913  6913 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-18 14:10:34.703  6913  6913 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-18 14:10:34.703  6913  6913 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-18 14:10:34.703  6913  6913 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,08-18 14:10:34.713  8091  8091 I wpa_supplicant: Successfully initialized wpa_supplicant
08-18 14:10:34.717  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
,08-18 14:10:34.721  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-18 14:10:34.722  6913  6913 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-18 14:10:34.723  6913  6913 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-18 14:10:34.723  6913  6913 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-18 14:10:34.723  6913  6913 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-18 14:10:34.723  6913  6913 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-18 14:10:34.723  6913  6913 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-18 14:10:34.723  6913  6913 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-18 14:10:34.726  6913  6913 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-18 14:10:34.726  6913  6913 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-18 14:10:34.726  6913  6913 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-18 14:10:34.726  6913  6913 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-18 14:10:34.727  6913  6913 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-18 14:10:34.727  6913  6913 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-18 14:10:34.728  6913  6913 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-18 14:10:34.728  6913  6913 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-18 14:10:34.728  6913  6913 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-18 14:10:34.728  6913  6913 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-18 14:10:34.728  6913  6913 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-18 14:10:34.753  8091  8091 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-18 14:10:34.753  8091  8091 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-18 14:10:34.769  1034  1989 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8109 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-18 14:10:34.817  8091  8091 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-18 14:10:34.870  8091  8091 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-18 14:10:34.878  8091  8091 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-18 14:10:34.880  1034  1540 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-18 14:10:34.880  1034  8131 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-18 14:10:34.880  1034  8131 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-18 14:10:34.880  1034  1540 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-18 14:10:34.880  1034  8131 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-18 14:10:34.881  1034  8131 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-18 14:10:34.881  1034  1540 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-18 14:10:34.882  1034  1540 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-18 14:10:34.882  1034  1540 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-18 14:10:34.883  1034  1540 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-18 14:10:34.884  1034  1540 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
,08-18 14:10:34.884  1034  1540 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-18 14:10:34.885  1034  1540 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-18 14:10:34.886  1034  1540 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-18 14:10:34.886  1034  1540 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-18 14:10:34.905  1034  1051 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8132 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-18 14:10:34.907  1034  1540 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-18 14:10:34.907  1034  1540 E WifiStateMachine: useWiFiOffloading() : false
08-18 14:10:34.907  1034  1540 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-18 14:10:34.908  1034  1540 D WifiNative-wlan0: doBoolean: SET update_config 1
08-18 14:10:34.909  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-18 14:10:34.909  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-18 14:10:34.909  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-18 14:10:34.909  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-18 14:10:34.909  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-18 14:10:34.910  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-18 14:10:34.912  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-18 14:10:34.912  1034  1545 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-18 14:10:34.912  1944  1944 D WfdService: Waiting for WifiP2p enabling
08-18 14:10:34.915  1034  1540 D WifiNative-wlan0: SET update_config 1: returned true
08-18 14:10:34.915  1034  1540 D WifiConfigStore: Loading config and enabling all networks 
08-18 14:10:34.915  1034  1540 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-18 14:10:34.916  1034  1540 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-18 14:10:34.920  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-18 14:10:34.920  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 14:10:34.920  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-18 14:10:34.920  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 14:10:34.920  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-18 14:10:34.920  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-18 14:10:34.920  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-18 14:10:34.920  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-18 14:10:34.922  8109  8129 W FormManager: Network not available. Please check & try again.
08-18 14:10:34.923  6817  6817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-18 14:10:34.925  1034  1540 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-18 14:10:34.930  8109  8130 V FormManager: Network unavailable.
,08-18 14:10:34.934  8109  8130 V FormManager: Network unavailable.
,08-18 14:10:34.948  1034  1540 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-18 14:10:34.948  1034  1540 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-18 14:10:34.950  1034  1540 D WifiStateMachine: enableVerboseLogging : level 2
08-18 14:10:34.950  1034  1540 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-18 14:10:34.950  1034  1540 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-18 14:10:34.950  1034  1540 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-18 14:10:34.951  1034  1540 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-18 14:10:34.951  1034  1540 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-18 14:10:34.951  1034  1540 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-18 14:10:34.952  1034  1540 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-18 14:10:34.952  1034  1540 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-18 14:10:34.952  1034  1540 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-18 14:10:34.953  1034  1540 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-18 14:10:34.953  1034  1540 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-18 14:10:34.953  1034  1540 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-18 14:10:34.953  1034  1540 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-18 14:10:34.954  1034  1540 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-18 14:10:34.955  1944  1944 D WfdsService: Supplicant Connection state is changed : true
08-18 14:10:34.955  1034  1540 D WifiStateMachine: Setting OUI to DA-A1-19
08-18 14:10:34.955  1034  1540 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-18 14:10:34.956  1034  1540 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-18 14:10:34.956  1034  2035 I ActivityManager: Killing 7234:com.android.chrome/u0a57 (adj 15): empty #17
08-18 14:10:34.956  1034  1540 D WifiNative-HAL: Setting external_sim to 1
08-18 14:10:34.956  1944  2342 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-18 14:10:34.956  1944  2342 D WfdsService: Set the WFDS Monitor: true
08-18 14:10:34.956  1944  2342 D WfdsMonitor: WfdsMonitorThread create
08-18 14:10:34.956  1034  1540 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-18 14:10:34.956  1944  2342 D WfdsMonitor: WFDS Monitor is created and started
08-18 14:10:34.956  1944  2342 D WfdsService: WiFi: Supplicant connection re-established
08-18 14:10:34.957  1034  1540 D WifiNative-wlan0: SET external_sim 1: returned true
08-18 14:10:34.957  1034  1540 I WifiNative-HAL: startHal
08-18 14:10:34.957  1034  1540 D wifi    : setting scan oui 0xaf7092a0
08-18 14:10:34.957  1034  1540 D WifiStateMachine: Setting OUI to DA-A1-19
08-18 14:10:34.957  1034  1540 I WifiNative-HAL: startHal
,08-18 14:10:34.957  1034  1540 D wifi    : setting scan oui 0xaf7092a0
08-18 14:10:34.958  1944  8150 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-18 14:10:34.958  1034  1540 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-18 14:10:34.958  1944  8150 E CtrlSupplicant: Succeed to open control connection
08-18 14:10:34.958  1944  8150 E CtrlSupplicant: Succeed to open monitor connection
08-18 14:10:34.958  1944  8150 D WfdsMonitor: Supplicant connection established
08-18 14:10:34.958  1034  1540 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-18 14:10:34.959  1034  1540 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-18 14:10:34.959  8091  8091 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-18 14:10:34.959  1944  2342 D WfdsService: Connected to the supplicant for wfds
08-18 14:10:34.959  1034  1540 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-18 14:10:34.959  1034  1540 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
,08-18 14:10:34.959  8091  8091 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-18 14:10:34.959  1034  1540 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-18 14:10:34.959  1034  1540 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-18 14:10:34.960  8091  8091 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-18 14:10:34.960  1034  1540 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-18 14:10:34.960  1034  1540 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-18 14:10:34.960  8091  8091 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-18 14:10:34.960  1034  1540 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-18 14:10:34.960  1034  1540 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-18 14:10:34.960  8091  8091 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-18 14:10:34.961  1034  1540 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-18 14:10:34.961  1034  1540 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-18 14:10:34.961  8091  8091 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-18 14:10:34.961  1034  1540 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-18 14:10:34.961  1034  1540 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-18 14:10:34.961  8091  8091 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-18 14:10:34.961  1034  1540 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-18 14:10:34.961  7792  7792 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-18 14:10:34.962  1034  1540 E WifiNative: : [215,691,041 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-18 14:10:34.962  1034  1540 D WifiNative-wlan0: doBoolean: RECONNECT
08-18 14:10:34.963  1034  1540 D WifiNative-wlan0: RECONNECT: returned true
08-18 14:10:34.963  1034  1540 D WifiNative-wlan0: doString: [STATUS]
08-18 14:10:34.963  1034  8131 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-18 14:10:34.963  1034  8131 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-18 14:10:34.964  1034  1540 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-18 14:10:34.964  1034  1540 D WifiNative-wlan0: doBoolean: SET ps 1
08-18 14:10:34.964  1034  1540 D WifiNative-wlan0: SET ps 1: returned true
08-18 14:10:34.964  1034  1539 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-18 14:10:34.967   309   903 D CommandListener: Setting iface cfg
08-18 14:10:34.967   309   903 D CommandListener: Trying to bring up p2p0
08-18 14:10:34.968  1034  1539 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-18 14:10:34.968  1034  1539 D LGWifiP2pService: P2pEnablingState
08-18 14:10:34.968  1034  1539 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-18 14:10:34.968  1034  1539 D LGWifiP2pService: P2p socket connection successful
08-18 14:10:34.968  1034  1539 D LGWifiP2pService: P2pEnabledState
,08-18 14:10:35.001  1034  1539 D LGWifiP2pService: sending p2p connection changed broadcast
08-18 14:10:35.001  1034  1539 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-18 14:10:35.002  1034  2023 W libprocessgroup: failed to open /acct/uid_10057/pid_7234/cgroup.procs: No such file or directory
08-18 14:10:35.002  1034  1539 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-18 14:10:35.002  1034  1539 D WifiNative-p2p0: doBoolean: SET device_name G3
08-18 14:10:35.002  1034  1539 D WifiNative-p2p0: SET device_name G3: returned true
08-18 14:10:35.002  1034  1539 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-18 14:10:35.002  1034  1539 D LGWifiP2pService: before postfix = G3
08-18 14:10:35.002  1034  1539 D WifiServerServiceExt: postfix byte check : 2
08-18 14:10:35.002  1034  1539 D LGWifiP2pService: after postfix = G3
08-18 14:10:35.002  1034  1539 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-18 14:10:35.003  1034  1539 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-18 14:10:35.003  1034  1539 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-18 14:10:35.003  1034  1539 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-18 14:10:35.004  1034  1539 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-18 14:10:35.004  1034  1539 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-18 14:10:35.004  1034  1539 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-18 14:10:35.004  1034  1539 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-18 14:10:35.004  1034  1539 D WifiNative-HAL: p2pGetDeviceAddress
08-18 14:10:35.005  1944  1944 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-18 14:10:35.005  1034  1539 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-18 14:10:35.005  1944  1944 D WfdsService: WifiP2pState is changed : true
08-18 14:10:35.005  1944  2342 D WfdsService: Receive the WFDS_ENABLE Method
08-18 14:10:35.005  1944  2342 D WfdsService: Set the WFDS Monitor: true
08-18 14:10:35.005  1944  2342 D WfdsService: Connected to the supplicant for wfds
08-18 14:10:35.005  1944  2342 D WfdsJNI : doCommand: WFDS_SET TRUE
08-18 14:10:35.005  8091  8091 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-18 14:10:35.005  1944  2342 D WfdsService: selectPreferredScanChannel [36]
08-18 14:10:35.005  1944  2342 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-18 14:10:35.006  1944  1944 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-18 14:10:35.007  1944  1944 D WfdsService: isConnected: false
08-18 14:10:35.007  1034  1539 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-18 14:10:35.007  1034  1539 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-18 14:10:35.007  1034  1034 D WifiScanningService: SCAN_AVAILABLE : 3
08-18 14:10:35.007  1034  1034 D RttService: SCAN_AVAILABLE : 3
08-18 14:10:35.008  1034  1558 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-18 14:10:35.008  1034  1558 I WifiNative-HAL: startHal
08-18 14:10:35.008  1034  1539 D WifiNative-p2p0: P2P_FLUSH: returned true
08-18 14:10:35.008  1034  1540 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-18 14:10:35.008  1034  1539 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-18 14:10:35.008  1034  1558 D wifi    : getting scan capabilities on interface[1] = 0xaf7092a0
08-18 14:10:35.008  1034  1558 D wifi    : failed to get capabilities : -3
08-18 14:10:35.008  1034  1558 E WifiScanningService: could not get scan capabilities
08-18 14:10:35.008  1034  1540 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-18 14:10:35.009  1034  1539 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-18 14:10:35.009  1034  1539 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-18 14:10:35.009  1034  1540 E WifiStateMa,chine:  ConnectModeState CMD_START_DRIVER 0 0
08-18 14:10:35.009  1944  1944 I WfdStateTracker: handleP2pThisDeviceChanged
08-18 14:10:35.009  1944  1944 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-18 14:10:35.009  1034  1539 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-18 14:10:35.009  1034  1539 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-18 14:10:35.009  1034  1540 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-18 14:10:35.009  1944  1944 D WfdsService: Update P2p Interface State: 3
08-18 14:10:35.010  1034  1540 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-18 14:10:35.010  1034  1559 D RttService: DefaultState got{ when=-3ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-18 14:10:35.010  1034  1540 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-18 14:10:35.010  1034  1540 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-18 14:10:35.011  1034  1540 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
,08-18 14:10:35.022  8091  8091 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-18 14:10:35.022  1034  1539 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-18 14:10:35.022  1034  1539 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-18 14:10:35.022  1034  1539 D LGWifiP2pService: InactiveState
08-18 14:10:35.022  1034  1539 D LGWifiP2pService: InactiveState{ when=-14ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-18 14:10:35.022  1034  1539 D LGWifiP2pService: P2pEnabledState{ when=-14ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-18 14:10:35.023  1034  1539 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-18 14:10:35.023  8091  8091 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-18 14:10:35.023  1034  1539 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-18 14:10:35.023  1034  1539 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-18 14:10:35.023  1034  1539 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-18 14:10:35.023  1034  1539 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-18 14:10:35.023  8091  8091 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-18 14:10:35.024  1034  8131 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-18 14:10:35.024  1034  8131 E WifiMonitor: WifiMonitor:p2p0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-18 14:10:35.024  1034  8131 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-18 14:10:35.024  1034  8131 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-18 14:10:35.024  1944  8150 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-18 14:10:35.024  8091  8091 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-18 14:10:35.024  8091  8091 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,08-18 14:10:35.025  8091  8091 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-18 14:10:35.025  1944  8150 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-18 14:10:35.025  1944  8150 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-18 14:10:35.025  1034  8131 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-18 14:10:35.026  1034  8131 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-18 14:10:35.026  1034  8131 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-18 14:10:35.026  1034  8131 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-18 14:10:35.026  1034  8131 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-18 14:10:35.026  1034  8131 E WifiMonitor: WifiMonitor:p2p0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-18 14:10:35.026  1034  8131 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-18 14:10:35.026  1034  8131 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-18 14:10:35.026  1034  1539 D LGWifiP2pService: InactiveState{ when=-4ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-18 14:10:35.026  1034  1539 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-18 14:10:35.026  1034  1539 D LGWifiP2pService: DefaultState{ when=-4ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-18 14:10:35.027  1944  2342 W WfdsService: DefaultState - msg [9441285] is not handled
08-18 14:10:35.027  1034  1539 D LGWifiP2pService: InactiveState{ when=-5ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-18 14:10:35.027  1034  1539 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-18 14:10:35.027  1034  1539 D LGWifiP2pService: DefaultState{ when=-5ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
,08-18 14:10:35.027  1034  1539 D LGWifiP2pService: InactiveState{ when=-5ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-18 14:10:35.027  1034  1539 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-18 14:10:35.027  1034  1539 D LGWifiP2pService: DefaultState{ when=-5ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-18 14:10:35.027  1034  1034 E WifiServerServiceExt: No p2p device connected
08-18 14:10:35.028  1034  1540 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-18 14:10:35.028  1034  1540 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-18 14:10:35.029  1034  1540 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-18 14:10:35.029  1034  1540 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-18 14:10:35.029  8091  8091 E wpa_supplicant: disconnect_rssi_lvl: -100
08-18 14:10:35.029  1034  1540 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-18 14:10:35.030  1034  1540 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-18 14:10:35.030  1034  1540 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-18 14:10:35.030  1034  1540 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-18 14:10:35.031  8091  8091 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-18 14:10:35.031  8091  8091 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-18 14:10:35.032  1034  8131 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-18 14:10:35.032  1034  8131 E WifiMonitor: WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-18 14:10:35.032  1034  8131 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-18 14:10:35.032  1034  8131 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-18 14:10:35.032  8091  8091 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-18 14:10:35.032  8091  8091 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-18 14:10:35.032  1034  1540 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-18 14:10:35.033  8091  8091 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-18 14:10:35.033  1034  1539 D LGWifiP2pService: InactiveState{ when=0 what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-18 14:10:35.033  1034  1539 D LGWifiP2pService: P2pEnabledState{ when=0 what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-18 14:10:35.033  8132  8132 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-18 14:10:35.033  1944  8150 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-18 14:10:35.033  1944  8150 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-18 14:10:35.033  1034  8131 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-18 14:10:35.033  1034  8131 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-18 14:10:35.034  1034  8131 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-18 14:10:35.034  1034  1540 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-18 14:10:35.034  1034  8131 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-18 14:10:35.034  1034  8131 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-18 14:10:35.034  1034  8131 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-18 14:10:35.034  1034  8131 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-18 14:10:35.034  1034  8131 E WifiMonitor,: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-18 14:10:35.034  1034  1540 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-18 14:10:35.034  1034  1540 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-18 14:10:35.034  1034  1540 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-18 14:10:35.034  8091  8091 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-18 14:10:35.034  8091  8091 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-18 14:10:35.035  1034  8131 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-18 14:10:35.035  1034  8131 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-18 14:10:35.035  1034  8131 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-18 14:10:35.035  1034  8131 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-18 14:10:35.035  1034  1540 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-18 14:10:35.035  1034  1540 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-18 14:10:35.036  1034  1540 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-18 14:10:35.036  1034  1540 D WifiNative-wlan0: doBoolean: SCAN
08-18 14:10:35.036  1034  1540 D WifiNative-wlan0: SCAN: returned false
08-18 14:10:35.036  1034  1540 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=215765  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-18 14:10:35.037  6913  6913 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-18 14:10:35.037  1034  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=215766  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-18 14:10:35.038  1034  1540 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-18 14:10:35.038  1034  1540 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-18 14:10:35.039  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-18 14:10:35.039  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-18 14:10:35.039  1034  1540 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-18 14:10:35.040  1034  1540 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-18 14:10:35.040  1034  1540 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-18 14:10:35.040  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-18 14:10:35.040  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-18 14:10:35.040  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-18 14:10:35.041  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-18 14:10:35.041  1034  1034 D WifiServerServiceExt: setSupplicantStateSCANNING
08-18 14:10:35.043  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-18 14:10:35.044  6817  6895 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-18 14:10:35.044  6817  6895 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 14:10:35.044  6817  6895 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-18 14:10:35.044  6817  6895 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 14:10:35.044  6817  6895 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-18 14:10:35.044  6817  6895 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-18 14:10:35.044  6817  6895 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-18 14:10:35.044  6817  6895 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-18 14:10:35.047  6817  6895 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-18 14:10:35.051  6913  6913 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-18 14:10:35.052  1034  1908 I ActivityManager: Killing 7255:com.lge.drmservice/u0a62 (adj 15): empty #17
08-18 14:10:35.053  6817  6895 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-18 14:10:35.054  6817  6895 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-18 14:10:35.056  6817  6895 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@2f03dc9 Bundle[{}]
08-18 14:10:35.057  6817  6895 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-18 14:10:35.057  6817  6895 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-18 14:10:35.058  6817  6895 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-18 14:10:35.059  6817  6895 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-18 14:10:35.059  6817  6895 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-18 14:10:35.060  6817  6895 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-18 14:10:35.067  6817  6895 I System.out: Running OutgoingSocketThread
08-18 14:10:35.068  6817  8153 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 872)
08-18 14:10:35.069  6817  8153 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 45734
08-18 14:10:35.069  6817  8153 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-18 14:10:35.088  1034  2023 W libprocessgroup: failed to open /acct/uid_10062/pid_7255/cgroup.procs: No such file or directory
,08-18 14:10:35.106  8132  8132 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-18 14:10:35.112  6913  6913 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-18 14:10:35.114  8109  8155 W FormManager: Network not available. Please check & try again.
08-18 14:10:35.118  8109  8156 V FormManager: Network unavailable.
,08-18 14:10:35.121  6913  6913 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-18 14:10:35.130  8109  8156 V FormManager: Network unavailable.
,08-18 14:10:35.147  4340  4340 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-18 14:10:35.148  4340  4340 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-18 14:10:35.149  4340  4340 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-18 14:10:35.154  4340  4340 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-18 14:10:35.159  4340  8157 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-18 14:10:35.164  4340  8158 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
,08-18 14:10:35.164  4340  8158 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-18 14:10:35.235  1034  1622 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8159 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-18 14:10:35.355  8159  8159 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-18 14:10:35.355  8159  8159 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-18 14:10:35.365  8159  8159 V [BNRBootReceiver]: Boot Receiver Return
,08-18 14:10:35.368  8159  8159 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-18 14:10:35.438  1034  2023 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8180 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-18 14:10:35.440  1034  2023 I ActivityManager: Killing 7278:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
08-18 14:10:35.469  1034  8131 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
,08-18 14:10:35.470  1034  8131 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-18 14:10:35.470  1034  8131 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-18 14:10:35.470  8091  8091 E wpa_supplicant: USIM:  scard_init function
08-18 14:10:35.470  1034  8131 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: WPS-AP-AVAILABLE 
08-18 14:10:35.470  1034  8131 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-18 14:10:35.470  8091  8091 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-18 14:10:35.471  1034  8131 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-18 14:10:35.471  1034  8131 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-18 14:10:35.476  1034  1540 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-18 14:10:35.477  1034  1540 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-18 14:10:35.477  1034  1540 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-18 14:10:35.478  1034  1540 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-18 14:10:35.478  1034  1540 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-18 14:10:35.507  1034  1051 W libprocessgroup: failed to open /acct/uid_10085/pid_7278/cgroup.procs: No such file or directory
,08-18 14:10:35.511  1034  1540 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=216240  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-18 14:10:35.518  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-18 14:10:35.518  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-18 14:10:35.519  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-18 14:10:35.520  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-18 14:10:35.520  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-18 14:10:35.520  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
,08-18 14:10:35.523  1034  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=216252  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-18 14:10:35.527  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-18 14:10:35.527  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-18 14:10:35.527  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-18 14:10:35.527  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-18 14:10:35.527  1034  1034 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-18 14:10:35.542  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-18 14:10:35.542  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-18 14:10:35.543  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-18 14:10:35.545  8180  8180 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-18 14:10:35.567  8180  8180 D PluginManager: init()
,08-18 14:10:35.584  1034  8131 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-18 14:10:35.584  8091  8091 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-18 14:10:35.584  1034  8131 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-18 14:10:35.584  1034  8131 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-18 14:10:35.585  1034  8131 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-18 14:10:35.585  1034  1540 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=216314  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-18 14:10:35.585  1034  8131 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-18 14:10:35.585  1034  8131 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-18 14:10:35.586  1034  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=216314  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-18 14:10:35.588  1034  1540 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=216317
08-18 14:10:35.588  1034  1540 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=216317
08-18 14:10:35.588  1034  1540 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=216317
08-18 14:10:35.589  1034  1540 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=216318
08-18 14:10:35.590  1034  1540 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=216319
08-18 14:10:35.590  1034  1540 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=216319  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
,08-18 14:10:35.593  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-18 14:10:35.593  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-18 14:10:35.593  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-18 14:10:35.596  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-18 14:10:35.596  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-18 14:10:35.597  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-18 14:10:35.599  1034  1101 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-18 14:10:35.599  8091  8091 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-18 14:10:35.600  8091  8091 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-18 14:10:35.601  1034  8131 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-18 14:10:35.601  1034  8131 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-18 14:10:35.601  1034  8131 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-18 14:10:35.601  1034  8131 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-18 14:10:35.601  1034  8131 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-18 14:10:35.601  1034  8131 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-18 14:10:35.601  1034  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=216330  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-18 14:10:35.601  1034  8131 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-18 14:10:35.601  1034  8131 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-18 14:10:35.602  1034  8131 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-18 14:10:35.602  1034  8131 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-18 14:10:35.602  1034  1540 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
08-18 14:10:35.603  1034  1540 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-18 14:10:35.603  1034  1540 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-18 14:10:35.604  1034  1540 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-18 14:10:35.604  1034  1540 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-18 14:10:35.605  1034  1540 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=216333  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-18 14:10:35.605  1034  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=216334  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-18 14:10:35.606  1034  1540 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=216335
08-18 14:10:35.607  1034  1540 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=216336
08-18 14:10,:35.607  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-18 14:10:35.607  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-18 14:10:35.607  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-18 14:10:35.607  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-18 14:10:35.607  1034  1034 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-18 14:10:35.607  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-18 14:10:35.607  1034  1034 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-18 14:10:35.607  1034  1540 D WifiNative-wlan0: doString: [STATUS]
08-18 14:10:35.608  1034  8131 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-18 14:10:35.608  1034  8131 E WifiMonitor: WifiMonitor:wlan0 cnt=64 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,08-18 14:10:35.609  1034  1540 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-18 14:10:35.611  1034  1540 I WifiServiceExtension: setVHTCapabilityType  : false
08-18 14:10:35.618  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-18 14:10:35.618  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-18 14:10:35.619  1034  1540 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-18 14:10:35.619  1034  1540 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-18 14:10:35.619  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-18 14:10:35.623  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-18 14:10:35.624  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-18 14:10:35.624  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,08-18 14:10:35.630  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-18 14:10:35.630  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-18 14:10:35.630  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-18 14:10:35.631  1034  1540 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-18 14:10:35.631  1034  1547 D ConnectivityService: Got NetworkAgent Messenger
08-18 14:10:35.631  1034  1547 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-18 14:10:35.631  1034  1547 D ConnectivityService: NetworkAgent connected
08-18 14:10:35.631  1034  1540 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-18 14:10:35.631  1034  1540 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-18 14:10:35.632  1034  1540 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-18 14:10:35.632  1034  1540 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-18 14:10:35.639  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-18 14:10:35.639  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-18 14:10:35.640  1034  1540 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-18 14:10:35.640  1034  1540 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-18 14:10:35.640  1034  1540 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
,08-18 14:10:35.641  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-18 14:10:35.642  1034  1540 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-18 14:10:35.642  1034  1540 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-18 14:10:35.644  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-18 14:10:35.644  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-18 14:10:35.645  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-18 14:10:35.646  1034  1540 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-18 14:10:35.647   309   903 D CommandListener: Setting iface cfg
08-18 14:10:35.649  1034  1540 E WifiStateMachine: Start Dhcp Watchdog 3
08-18 14:10:35.650  1034  8204 D DhcpStateMachine: StoppedState
08-18 14:10:35.650  1034  8204 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-18 14:10:35.650  1034  8204 D DhcpStateMachine: WaitBeforeStartState
08-18 14:10:35.650  1034  1540 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=216379  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-18 14:10:35.651  1034  1540 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=216380  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-18 14:10:35.651  1034  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=216380  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-18 14:10:35.652  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-18 14:10:35.652  1034  1034 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
,08-18 14:10:35.655  1034  1540 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=216384  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-18 14:10:35.656  1034  1540 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=216385  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-18 14:10:35.656  1034  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=216385  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-18 14:10:35.658  1034  1540 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14191] from screen [on:0 period:-1651546870] gl rssi=-49 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-18 14:10:35.659  1034  1540 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1651546869] gl rssi=-49 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-18 14:10:35.659  1034  1540 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-18 14:10:35.662  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-18 14:10:35.663  1034  1547 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
08-18 14:10:35.664  1034  1540 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-18 14:10:35.664  1034  1540 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-18 14:10:35.664  1034  1540 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-18 14:10:35.665  1034  1540 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-18 14:10:35.665  1034  1540 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-18 14:10:35.666  1034  1540 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-18 14:10:35.667  1034  1547 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-18 14:10:35.667  1034  1540 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=126,0,0
08-18 14:10:35.667  1034  1540 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=126,0,0
08-18 14:10:35.667  1034  1540 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-18 14:10:35.668  8091  8091 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-18 14:10:35.668  1034  1540 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-18 14:10:35.668  1034  1540 D WifiNative-wlan0: doBoolean: SET ps 0
08-18 14:10:35.668  1034  1540 D WifiNative-wlan0: SET ps 0: returned true
08-18 14:10:35.669  1034  1540 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-18 14:10:35.669  8091  8091 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-18 14:10:35.669  1034  1540 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
,08-18 14:10:35.669  1034  1539 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@38d305d4 target=com.android.internal.util.StateMachine$SmHandler }
08-18 14:10:35.669  1034  1539 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@38d305d4 target=com.android.internal.util.StateMachine$SmHandler }
08-18 14:10:35.669  1034  1540 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-18 14:10:35.669  1034  1540 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-18 14:10:35.669  1034  8204 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-18 14:10:35.669  1034  8204 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-18 14:10:35.670  1034  1540 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-18 14:10:35.670   309   903 D CommandListener: Setting iface cfg
08-18 14:10:35.671   309   903 D CommandListener: Trying to bring up wlan0
08-18 14:10:35.672  1034  1540 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-18 14:10:35.673  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-18 14:10:35.673  1034  1034 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-18 14:10:35.673  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-18 14:10:35.673  1034  1034 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-18 14:10:35.674  1034  1540 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-18 14:10:35.674  1034  1540 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-18 14:10:35.675  1034  1540 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-18 14:10:35.675  1034  1540 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-18 14:10:35.676  1034  1540 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-18 14:10:35.676  1034  1540 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-18 14:10:35.676  1034  1547 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-18 14:10:35.677  1034  1540 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-18 14:10:35.677  1034  1540 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-18 14:10:35.678  1034  1539 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-18 14:10:35.678  1034  1539 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-18 14:10:35.678  1034  1540 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-18 14:10:35.678  8091  8091 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-18 14:10:35.678  1034  1540 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-18 14:10:35.678  1034  1540 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-18 14:10:35.678  8091  8091 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-18 14:10:35.679  1034  1540 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-18 14:10:35.679  1034  1540 D WifiNative-wlan0: doBoolean: SET ps 1
08-18 14:10:35.697  1034  1540 D WifiNative-wlan0: SET ps 1: returned true
,08-18 14:10:35.697  1034  1540 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-18 14:10:35.698  1034  1540 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-18 14:10:35.698  1034  1540 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-18 14:10:35.699  1034  1547 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-18 14:10:35.699  1034  1547 D ConnectivityService: ignoring duplicate network state non-change
08-18 14:10:35.702  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-18 14:10:35.702  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-18 14:10:35.703  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-18 14:10:35.703  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-18 14:10:35.703  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-18 14:10:35.704  1034  1547 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-18 14:10:35.705  1034  1547 D ConnectivityService: Adding iface wlan0 to network 102
08-18 14:10:35.705  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-18 14:10:35.708  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-18 14:10:35.708  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-18 14:10:35.708  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-18 14:10:35.710  1034  1540 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-18 14:10:35.711  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-18 14:10:35.711  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-18 14:10:35.712  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-18 14:10:35.713  1034  1034 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-18 14:10:35.716  1944  1944 V WfdStateTracker: handleWifiStateChangedEvent: 1
,08-18 14:10:35.718  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-18 14:10:35.718  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-18 14:10:35.718  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-18 14:10:35.719  1034  1034 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-18 14:10:35.724  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-18 14:10:35.724  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-18 14:10:35.724  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-18 14:10:35.729  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-18 14:10:35.729  1605  1605 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-18 14:10:35.730  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-18 14:10:35.732  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-18 14:10:35.733  1605  1605 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-18 14:10:35.733  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-18 14:10:35.741  1034  1547 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-18 14:10:35.741  1034  1547 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-18 14:10:35.742  1034  1547 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
08-18 14:10:35.743   309   903 E Netd    : netlink response contains error (File exists)
08-18 14:10:35.743  1034  1547 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-18 14:10:35.745  1034  1547 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-18 14:10:35.745  1034  1547 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
08-18 14:10:35.745  1034  1547 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
08-18 14:10:35.746  1034  1547 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-18 14:10:35.746  1034  1547 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-18 14:10:35.746  1034  1547 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-18 14:10:35.746  1034  1547 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-18 14:10:35.746  1034  1547 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-18 14:10:35.746  1034  8203 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-18 14:10:35.746  1034  8203 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-18 14:10:35.746  1034  1547 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-18 14:10:35.746  1034  1547 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-18 14:10:35.746  1034  8203 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-18 14:10:35.746  1034  1547 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-18 14:10:35.746  1034  8203 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-18 14:10:35.746  1034  1547 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-18 14:10:35.746  1034  1547 D ConnectivityService: currentScore = 0, newScore = 20
08-18 14:10:35.746  1034  1547 D ConnectivityService:    accepting network in place of null
08-18 14:10:35.746  1034  1547 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-18 14:10:35.749  1034  1547 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-18 14:10:35.749  1034  1547 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-18 14:10:35.749  1855  1855 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-18 14:10:35.749  1034  1547 D, ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-18 14:10:35.749  1034  1540 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-18 14:10:35.749  1855  1855 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-18 14:10:35.749  1034  1540 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-18 14:10:35.749  1034  1547 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-18 14:10:35.749  1034  1547 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-18 14:10:35.750  1034  1547 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-18 14:10:35.751  1034  1547 D ConnectivityService: validation of new default Network = false
08-18 14:10:35.751  1034  1547 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-18 14:10:35.751  1034  1547 D DSQN    : enableDataServiceNotify 
08-18 14:10:35.751  1034  1547 D DSQN    : start dsqn bin
08-18 14:10:35.751  1034  1034 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-18 14:10:35.752  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-18 14:10:35.752  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-18 14:10:35.752  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-18 14:10:35.752   309  8208 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-18 14:10:35.753   309  8208 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-18 14:10:35.760  1034  1547 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-18 14:10:35.760  1034  1547 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-18 14:10:35.760  1034  1547 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-18 14:10:35.754  8209  8209 W dsqn    : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-18 14:10:35.754  8209  8209 W dsqn    : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-18 14:10:35.761  1034  1547 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-18 14:10:35.762  1605  1818 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-18 14:10:35.771  1034  1538 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,08-18 14:10:35.775  8209  8209 E DSQN    : DSQN ssw
,08-18 14:10:35.779  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-18 14:10:35.779  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-18 14:10:35.780  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-18 14:10:35.800   309  8208 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-18 14:10:35.833   309   902 D LGDataListener: argv[0]=dsqncommand
08-18 14:10:35.833   309   902 D LGDataListener: argv[1]=wlan0
,08-18 14:10:35.833   309   902 D LGDataListener: argv[2]=1
08-18 14:10:35.833   309   902 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-18 14:10:35.833  1034  1099 D DSQN    : DSQM DsqnNotification wlan0  1
08-18 14:10:35.834  1034  1099 D DSQN    : start to monitor internet connection
,08-18 14:10:35.867  1034  8203 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 18 Aug 2016 12:10:35 GMT], X-Android-Received-Millis=[1471522235866], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1471522235832]}
08-18 14:10:35.867  1034  8203 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-18 14:10:35.867  1034  8203 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-18 14:10:35.868  1034  1547 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
08-18 14:10:35.868  1034  1547 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-18 14:10:35.868  1034  1547 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-18 14:10:35.868  1034  1547 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-18 14:10:35.868  1034  1547 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
,08-18 14:10:35.868  1034  1547 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-18 14:10:35.868  1034  1547 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-18 14:10:35.868  1034  1547 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-18 14:10:35.868  1034  1547 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-18 14:10:35.869  1034  1547 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-18 14:10:35.869  1034  1547 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-18 14:10:35.869  1034  1547 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-18 14:10:35.870  1034  1540 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-18 14:10:35.870  1034  1540 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-18 14:10:35.870  1855  1855 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-18 14:10:35.871  1605  1818 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-18 14:10:35.871  1855  1855 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-18 14:10:35.873  1034  8204 D DhcpStateMachine: DHCPV4 request on wlan0
,08-18 14:10:35.875  1034  8204 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-18 14:10:35.875  1034  8204 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-18 14:10:35.884  8215  8215 W dhcpcd  : type=1400 audit(0.0:195): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-18 14:10:35.884  8215  8215 W dhcpcd  : type=1400 audit(0.0:196): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-18 14:10:35.903  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-18 14:10:35.904  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-18 14:10:35.905  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-18 14:10:35.913  8215  8215 I dhcpcd  : version 5.5.6 starting
,08-18 14:10:35.918  8215  8215 E dhcpcd  : get_duid: m
,08-18 14:10:35.918  8215  8215 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-18 14:10:35.918  8215  8215 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-18 14:10:36.023  8215  8215 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-18 14:10:36.024  8215  8215 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
,08-18 14:10:36.024  8215  8215 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-18 14:10:36.024  8215  8215 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
08-18 14:10:36.025  8215  8215 D dhcpcd  : wlan0: sending REQUEST (xid 0x29eb2551), next in 4.68 seconds
,08-18 14:10:36.070  6817  6895 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 873)
,08-18 14:10:36.070  6817  6895 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 873)
,08-18 14:10:36.080  8215  8215 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,08-18 14:10:36.082  6817  6895 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 878)
08-18 14:10:36.085  6817  6895 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-18 14:10:36.085  6817  6895 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 879)
,08-18 14:10:36.096  6817  6895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-18 14:10:36.096  6817  6895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@203f672c added. We now have 2 listener(s)
08-18 14:10:36.097  1034  1908 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-18 14:10:36.104  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-18 14:10:36.105  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-18 14:10:36.105  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-18 14:10:36.105  6817  6895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-18 14:10:36.105  6817  6895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47685f5 added. We now have 9 listener(s)
08-18 14:10:36.105  6817  6895 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-18 14:10:36.106  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-18 14:10:36.108  6817  6895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-18 14:10:36.111  6817  6895 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-18 14:10:36.111  6817  6895 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 14:10:36.111  6817  6895 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-18 14:10:36.111  6817  6895 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 14:10:36.111  6817  6895 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-18 14:10:36.111  6817  6895 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-18 14:10:36.111  6817  6895 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-18 14:10:36.111  6817  6895 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-18 14:10:36.111  8215  8215 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
08-18 14:10:36.112  8215  8215 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
08-18 14:10:36.112  8215  8215 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-18 14:10:36.113  6817  6895 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-18 14:10:36.113  8215  8215 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-18 14:10:36.113  6817  6895 D io.jxcore.node.ConnectivityMonitor: start: OK
08-18 14:10:36.113  6817  6895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-18 14:10:36.113  6817  6895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@241869fb added. We now have 3 listener(s)
08-18 14:10:36.113  8215  8215 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-18 14:10:36.113  1034  1908 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-18 14:10:36.114  8215  8215 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-18 14:10:36.114  8215  8215 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-18 14:10:36.114  8215  8215 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-18 14:10:36.114  8180  8180 W ExternalStrings: load override strings
08-18 14:10:36.114  8180  8180 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
08-18 14:10:36.114  8180  8180 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
08-18 14:10:36.114  8180  8180 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
08-18 14:10:36.114  8180  8180 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
08-18 14:10:36.114  8180  8180 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
08-18 14:10:36.114  8180  8180 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
08-18 14:10:36.114  8180  8180 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
08-18 14:10:36.114  8180  8180 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-18 14:10:36.114  8180  8180 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-18 14:10:36.114  8180  8180 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-18 14:10:36.114  8180  8180 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-18 14:10:36.114  8180  8180 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-18 14:10:36.114  8180  8180 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
08-18 14:10:36.114  8180  8180 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-18 14:10:36.114  8180  8180 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
08-18 14:10:36.114  8180  8180 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-18 14:10:36.114  8180  8180 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-18 14:10:36.114  8180  8180 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-18 14:10:36.114  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 14:10:36.116  8180  8180 D StatusProvider: onCreate
08-18 14:10:36.116  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 14:10:36.121  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC addr,ess: "58:3F:54:73:BA:17"
08-18 14:10:36.121  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-18 14:10:36.121  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-18 14:10:36.122  6817  6895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-18 14:10:36.122  6817  6895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d1ca18 added. We now have 10 listener(s)
08-18 14:10:36.122  6817  6895 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-18 14:10:36.122  6817  6895 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-18 14:10:36.123  6817  6895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-18 14:10:36.123  6817  6895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-18 14:10:36.123  6817  6895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 14:10:36.123  6817  6895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:10:36.123  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-18 14:10:36.123  6817  6895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-18 14:10:36.123  6817  6895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@203f672c removed from the list
08-18 14:10:36.123  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:10:36.123  6817  6895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47685f5 removed from the list
08-18 14:10:36.123  6817  6895 D io.jxcore.node.ConnectivityMonitor: stop
08-18 14:10:36.124  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:10:36.124  6817  6895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:10:36.124  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-18 14:10:36.126  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 14:10:36.126  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 14:10:36.126  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:10:36.127  6817  6895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47685f5 not in the list
08-18 14:10:36.127  6817  6895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:10:36.127  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:10:36.136  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 14:10:36.136  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 14:10:36.136  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:10:36.136  6817  6895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d1ca18 removed from the list
08-18 14:10:36.136  6817  6895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 14:10:36.136  6817  6895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:10:36.136  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:10:36.136  6817  6895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-18 14:10:36.137  6817  6895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@241869fb removed from the list
08-18 14:10:36.137  6817  6895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-18 14:10:36.137  6817  6895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@18768c71 added. We now have 2 listener(s)
08-18 14:10:36.138  1034  1935 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-18 14:10:36.140  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-18 14:10:36.140  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-18 14:10:36.140  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-18 14:10:36.140  6817  6895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-18 14:10:36.140  6817  6895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19aa6a56 added. We now have 9 listener(s)
08-18 14:10:36.140  6817  6895 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-18 14:10:36.140  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-18 14:10:36.143  6817  6895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-18 14:10:36.147  6817  6895 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-18 14:10:36.147  6817  6895 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 14:10:36.147  6817  6895 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-18 14:10:36.147  6817  6895 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 14:10:36.147  6817  6895 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-18 14:10:36.147  6817  6895 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-18 14:10:36.147  6817  6895 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-18 14:10:36.147  6817  6895 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-18 14:10:36.148  6817  6895 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-18 14:10:36.148  6817  6895 D io.jxcore.node.ConnectivityMonitor: start: OK
08-18 14:10:36.150  6817  6895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-18 14:10:36.151  6817  6895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15256fc4 added. We now have 3 listener(s)
08-18 14:10:36.151  8180  8180 V Signer  : override build config not found
08-18 14:10:36.151  1034  1935 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-18 14:10:36.151  8180  8180 D Signer  : value of property debug is false
,08-18 14:10:36.155  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 14:10:36.155  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-18 14:10:36.155  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-18 14:10:36.155  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-18 14:10:36.155  6817  6895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-18 14:10:36.155  6817  6895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e967ead added. We now have 10 listener(s)
08-18 14:10:36.155  6817  6895 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-18 14:10:36.155  6817  6895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-18 14:10:36.155  6817  6895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-18 14:10:36.155  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-18 14:10:36.155  6817  6895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-18 14:10:36.155  6817  6895 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-18 14:10:36.157  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 14:10:36.159  6817  6895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-18 14:10:36.159  1034  1935 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-18 14:10:36.163  6817  6895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-18 14:10:36.164  6817  6895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-18 14:10:36.165  6817  6895 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-18 14:10:36.165  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-18 14:10:36.166  6817  6895 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-18 14:10:36.166  6817  6895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-18 14:10:36.166  6817  6895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-18 14:10:36.168  6817  6895 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-18 14:10:36.168  6817  6895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-18 14:10:36.168  6817  6895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-18 14:10:36.168  6817  6895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 14:10:36.168  6817  6895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:10:36.168  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-18 14:10:36.168  6817  6895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-18 14:10:36.168  6817  6895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@18768c71 removed from the list
08-18 14:10:36.168  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:10:36.168  6817  6895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19aa6a56 removed from the list
08-18 14:10:36.168  6817  6895 D io.jxcore.node.ConnectivityMonitor: stop
08-18 14:10:36.168  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:10:36.168  6817  6895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:10:36.168  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:10:36.169  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 14:10:36.169  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 14:10:36.169  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:10:36.169  6817  6895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19aa6a56 not in the list
08-18 14:10:36.169  6817  6895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:10:36.169  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:10:36.170  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 14:10:36.171  6817  6895 D BluetoothLeScanner: could not find callback wrapper
08-18 14:10:36.172  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-18 14:10:36.172  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 14:10:36.172  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:10:36.172  6817  6895 V org.thaliproject.p2p.btconnectorlib.DiscoveryMa,nagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e967ead removed from the list
08-18 14:10:36.172  6817  6895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 14:10:36.172  6817  6895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:10:36.172  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:10:36.172  6817  6895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-18 14:10:36.172  6817  6895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15256fc4 removed from the list
08-18 14:10:36.174  6817  6895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-18 14:10:36.174  6817  6895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26ebc430 added. We now have 2 listener(s)
08-18 14:10:36.174  1034  1577 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-18 14:10:36.176  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-18 14:10:36.176  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-18 14:10:36.176  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-18 14:10:36.176  6817  6895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-18 14:10:36.176  6817  6895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@154958a9 added. We now have 9 listener(s)
08-18 14:10:36.176  6817  6895 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-18 14:10:36.176  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-18 14:10:36.178  6817  6895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-18 14:10:36.180  6817  6895 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-18 14:10:36.180  6817  6895 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 14:10:36.180  6817  6895 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-18 14:10:36.180  6817  6895 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 14:10:36.180  6817  6895 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-18 14:10:36.180  6817  6895 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-18 14:10:36.180  6817  6895 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-18 14:10:36.180  6817  6895 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-18 14:10:36.180  6817  6895 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-18 14:10:36.181  6817  6895 D io.jxcore.node.ConnectivityMonitor: start: OK
08-18 14:10:36.182  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 14:10:36.183  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 14:10:36.183  6817  6895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-18 14:10:36.183  6817  6895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b391dcf added. We now have 3 listener(s)
08-18 14:10:36.183  1034  1810 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-18 14:10:36.185  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-18 14:10:36.185  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-18 14:10:36.185  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-18 14:10:36.185  6817  6895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-18 14:10:36.185  6817  6895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b80f35c added. We now have 10 listener(s)
08-18 14:10:36.185  6817  6895 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-18 14:10:36.185  6817  6895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-18 14:10:36.185  6817  6895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-18 14:10:36.185  6817  6895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-18 14:10:36.185  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-18 14:10:36.185  6817  6895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-18 14:10:36.186  6817  6895 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-18 14:10:36.188  6817  6895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-18 14:10:36.188  1034  2023 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-18 14:10:36.191  6817  6895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-18 14:10:36.192  6817  6895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-18 14:10:36.193  6817  6895 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-18 14:10:36.193  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-18 14:10:36.194  6817  6895 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-18 14:10:36.194  6817  6895 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-18 14:10:36.194  6817  6895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-18 14:10:36.194  6817  6895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-18 14:10:36.194  6817  6895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 14:10:36.194  6817  6895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:10:36.194  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-18 14:10:36.194  6817  6895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-18 14:10:36.195  6817  6895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26ebc430 removed from the list
08-18 14:10:36.195  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:10:36.195  6817  6895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@154958a9 removed from the list
08-18 14:10:36.195  6817  6895 D io.jxcore.node.ConnectivityMonitor: stop
08-18 14:10:36.195  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:10:36.195  6817  6895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:10:36.195  8180  8180 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
08-18 14:10:36.195  8180  8180 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
08-18 14:10:36.195  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:10:36.196  8180  8180 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
08-18 14:10:36.196  8180  8180 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
,08-18 14:10:36.197  8180  8180 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
08-18 14:10:36.197  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 14:10:36.197  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 14:10:36.197  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:10:36.197  6817  6895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@154958a9 not in the list
08-18 14:10:36.197  6817  6895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:10:36.197  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:10:36.197  8180  8180 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
08-18 14:10:36.197  8180  8180 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
08-18 14:10:36.197  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 14:10:36.197  8180  8180 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
08-18 14:10:36.197  6817  6895 D BluetoothLeScanner: could not find callback wrapper
08-18 14:10:36.198  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-18 14:10:36.198  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 14:10:36.198  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:10:36.198  6817  6895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b80f35c removed from the list
08-18 14:10:36.198  6817  6895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 14:10:36.198  6817  6895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:10:36.198  8180  8180 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
08-18 14:10:36.198  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:10:36.198  6817  6895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-18 14:10:36.198  6817  6895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b391dcf removed from the list
08-18 14:10:36.198  8180  8180 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
08-18 14:10:36.198  8180  8180 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
08-18 14:10:36.198  6817  6895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-18 14:10:36.198  6817  6895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1fd3c7eb added. We now have 2 listener(s)
08-18 14:10:36.198  1034  1577 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-18 14:10:36.198  8180  8180 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
08-18 14:10:36.199  8180  8180 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
08-18 14:10:36.199  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-18 14:10:36.200  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothCon,nector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-18 14:10:36.200  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-18 14:10:36.200  6817  6895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-18 14:10:36.200  6817  6895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed7e948 added. We now have 9 listener(s)
08-18 14:10:36.200  6817  6895 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-18 14:10:36.200  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-18 14:10:36.202  6817  6895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-18 14:10:36.203  6817  6895 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-18 14:10:36.203  6817  6895 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 14:10:36.203  6817  6895 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-18 14:10:36.203  6817  6895 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 14:10:36.203  6817  6895 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-18 14:10:36.203  6817  6895 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-18 14:10:36.203  6817  6895 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-18 14:10:36.203  6817  6895 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-18 14:10:36.204  6817  6895 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-18 14:10:36.204  6817  6895 D io.jxcore.node.ConnectivityMonitor: start: OK
08-18 14:10:36.205  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 14:10:36.206  6817  6895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-18 14:10:36.206  6817  6895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c501506 added. We now have 3 listener(s)
08-18 14:10:36.208  1034  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-18 14:10:36.208  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 14:10:36.210  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-18 14:10:36.210  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-18 14:10:36.210  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-18 14:10:36.210  6817  6895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-18 14:10:36.210  6817  6895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d24f7c7 added. We now have 10 listener(s)
08-18 14:10:36.210  6817  6895 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-18 14:10:36.210  6817  6895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discove,ry: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-18 14:10:36.210  6817  6895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-18 14:10:36.210  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-18 14:10:36.210  6817  6895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-18 14:10:36.210  6817  6895 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-18 14:10:36.212  6817  6895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-18 14:10:36.212  1034  2023 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-18 14:10:36.214  8180  8180 V LGMDMManager: Create singleton instance
08-18 14:10:36.215  6817  6895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-18 14:10:36.216  6817  6895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-18 14:10:36.217  6817  6895 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-18 14:10:36.218  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-18 14:10:36.219  6817  6895 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-18 14:10:36.221  6817  6895 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-18 14:10:36.221  6817  6895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-18 14:10:36.221  6817  6895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-18 14:10:36.222  6817  6895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 14:10:36.222  6817  6895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:10:36.222  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-18 14:10:36.222  6817  6895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-18 14:10:36.222  6817  6895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1fd3c7eb removed from the list
08-18 14:10:36.222  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:10:36.222  6817  6895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed7e948 removed from the list
08-18 14:10:36.222  6817  6895 D io.jxcore.node.ConnectivityMonitor: stop
08-18 14:10:36.222  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:10:36.222  6817  6895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:10:36.222  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:10:36.223  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 14:10:36.223  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 14:10:36.223  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:10:36.223  6817  6895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed7e948 not in the list
08-18 14:10:36.223  6817  6895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:10:36.223  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:10:36.223  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 14:10:36.224  6817  6895 D BluetoothLeScanner: could not find callback wrapper
08-18 14:10:36.224  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-18 14:10:36.224  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 14:10:36.224  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:10:36.224  6817  6895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d24f7c7 removed from the list
08-18 14:10:36.224  6817  6895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 14:10:36.224  6817  6895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:10:36.224  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:10:36.224  6817  6895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-18 14:10:36.224  6817  6895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c501506 removed from the list
08-18 14:10:36.225  6817  6895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-18 14:10:36.225  6817  6895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34487b92 added. We now have 2 listener(s)
08-18 14:10:36.226  1034  1623 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-18 14:10:36.227  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-18 14:10:36.227  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-18 14:10:36.227  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-18 14:10:36.227  6817  6895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-18 14:10:36.227  6817  6895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d6f4963 added. We now have 9 listener(s)
08-18 14:10:36.227  6817  6895 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-18 14:10:36.228  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-18 14:10:36.230  6817  6895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-18 14:10:36.233  6817  6895 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-18 14:10:36.233  6817  6895 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 14:10:36.233  6817  6895 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-18 14:10:36.233  6817  6895 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 14:10:36.233  6817  6895 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-18 14:10:36.233  6817  6895 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-18 14:10:36.233  6817  6895 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-18 14:10:36.233  6817  6895 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-18 14:10:36.234  6817  6895 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-18 14:10:36.235  6817  6895 D io.jxcore.node.ConnectivityMonitor: start: OK
08-18 14:10:36.236  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 14:10:36.237  6817  6895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-18 14:10:36.237  6817  6895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f4cbe19 added. We now have 3 listener(s)
08-18 14:10:36.238  1034  1050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-18 14:10:36.238  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 14:10:36.240  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-18 14:10:36.240  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-18 14:10:36.240  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-18 14:10:36.240  6817  6895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-18 14:10:36.240  6817  6895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25eebede added. We now have 10 listener(s)
08-18 14:10:36.240  6817  6895 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-18 14:10:36.241  6817  6895 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-18 14:10:36.241  6817  6895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-18 14:10:36.241  6817  6895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-18 14:10:36.241  6817  6895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 14:10:36.241  6817  6895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:10:36.241  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-18 14:10:36.241  6817  6895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-18 14:10:36.241  6817  6895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34487b92 removed from the list
08-18 14:10:36.241  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:10:36.241  6817  6895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d6f4963 removed from the list
08-18 14:10:36.241  6817  6895 D io.jxcore.node.ConnectivityMonitor: stop
08-18 14:10:36.241  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:10:36.241  6817  6895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:10:36.241  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:10:36.242  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 14:10:36.242  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 14:10:36.242  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:10:36.242  6817  6895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d6f4963 not in the list
08-18 14:10:36.242  6817  6895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:10:36.242  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-18 14:10:36.243  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 14:10:36.243  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 14:10:36.243  6817  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:10:36.243  6817  6895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25eebede removed from the list
08-18 14:10:36.243  6817  6895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 14:10:36.243  6817  6895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:10:36.243  6817  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:10:36.243  6817  6895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-18 14:10:36.243  6817  6895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f4cbe19 removed from the list
08-18 14:10:36.244  6817  6895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-18 14:10:36.244  6817  6895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-18 14:10:36.244  6817  6895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-18 14:10:36.245  6817  6895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-18 14:10:36.245  6817  6895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-18 14:10:36.245  6817  6895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-18 14:10:36.255  6817  8236 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 886, name: My test thread name)
08-18 14:10:36.255  6817  8236 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 886, thread name: My test thread name)
08-18 14:10:36.255  6817  8236 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 886, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-18 14:10:36.259  6817  8238 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 888, name: My test thread name)
08-18 14:10:36.259  6817  8238 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 888, thread name: My test thread name)
08-18 14:10:36.259  6817  8238 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 888, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-18 14:10:36.261  6817  6895 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-18 14:10:36.261  6817  6895 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-18 14:10:36.261  6817  6895 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-18 14:10:36.261  6817  6895 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-18 14:10:36.261  6817  6895 D com.test.thalitest.ThaliTestRunner: Total duration: 22936 ms
08-18 14:10:36.262  6817  6895 I jxcore-log: Total number of executed tests:  80
08-18 14:10:36.262  6817  6895 I jxcore-log: 
08-18 14:10:36.262  6817  6895 I jxcore-log: Number of passed tests:  80
08-18 14:10:36.262  6817  6895 I jxcore-log: 
08-18 14:10:36.262  6817  6895 I jxcore-log: Number of failed tests:  0
08-18 14:10:36.262  6817  6895 I jxcore-log: 
08-18 14:10:36.263  6817  6895 I jxcore-log: Number of ignored tests:  0
08-18 14:10:36.263  6817  6895 I jxcore-log: 
08-18 14:10:36.263  6817  6895 I jxcore-log: Total duration:  22936
08-18 14:10:36.263  6817  6895 I jxcore-log: 
08-18 14:10:36.263  6817  6895 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-18 14:10:36.263  6817  6895 I jxcore-log: 
08-18 14:10:36.267  6817  6895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-18 14:10:36.267  6817  6895 I jxcore-log: 
08-18 14:10:36.270  6817  6895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-18 14:10:36.270  6817  6895 I jxcore-log: 
08-18 14:10:36.271  6817  6895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-18 14:10:36.271  6817  6895 I jxcore-log: 
08-18 14:10:36.272  6817  6895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-18 14:10:36.272  6817  6895 I jxcore-log: 
08-18 14:10:36.273  6817  6895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-18 14:10:36.273  6817  6895 I jxcore-log: 
08-18 14:10:36.274  6817  6895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-18 14:10:36.274  6817  6895 I jxcore-log: 
08-18 14:10:36.276  6817  6817 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
08-18 14:10:36.276  6817  6895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-18 14:10:36.276  6817  6895 I jxcore-log: 
08-18 14:10:36.278  6817  6895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-18 14:10:36.278  6817  6895 I jxcore-log: 
08-18 14:10:36.279  6817  6895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-18 14:10:36.279  6817  6895 I jxcore-log: 
08-18 14:10:36.279  8180  8180 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
08-18 14:10:36.280  6817  6895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-18 14:10:36.280  6817  6895 I jxcore-log: 
08-18 14:10:36.281  6817  6895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-18 14:10:36.281  6817  6895 I jxcore-log: 
08-18 14:10:36.282  6817  6895 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-18 14:10:36.282  6817  6895 I jxcore-log: 
08-18 14:10:36.283  6817  6895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-18 14:10:36.283  6817  6895 I jxcore-log: 
08-18 14:10:36.283  6817  6895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-18 14:10:36.283  6817  6895 I jxcore-log: 
,08-18 14:10:36.284  6817  6895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-18 14:10:36.284  6817  6895 I jxcore-log: 
,08-18 14:10:36.285  6817  6895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-18 14:10:36.285  6817  6895 I jxcore-log: 
08-18 14:10:36.285  6817  6895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-18 14:10:36.285  6817  6895 I jxcore-log: 
08-18 14:10:36.286  6817  6895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-18 14:10:36.286  6817  6895 I jxcore-log: 
08-18 14:10:36.287  6817  6895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-18 14:10:36.287  6817  6895 I jxcore-log: 
08-18 14:10:36.287  6817  6895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-18 14:10:36.287  6817  6895 I jxcore-log: 
08-18 14:10:36.288  6817  6895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-18 14:10:36.288  6817  6895 I jxcore-log: 
08-18 14:10:36.289  6817  6895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-18 14:10:36.289  6817  6895 I jxcore-log: 
08-18 14:10:36.289  6817  6895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-18 14:10:36.289  6817  6895 I jxcore-log: 
08-18 14:10:36.290  6817  6895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-18 14:10:36.290  6817  6895 I jxcore-log: 
08-18 14:10:36.290  6817  6895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-18 14:10:36.290  6817  6895 I jxcore-log: 
08-18 14:10:36.291  6817  6895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-18 14:10:36.291  6817  6895 I jxcore-log: 
08-18 14:10:36.291  6817  6895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-18 14:10:36.291  6817  6895 I jxcore-log: 
08-18 14:10:36.292  6817  6895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-18 14:10:36.292  6817  6895 I jxcore-log: 
08-18 14:10:36.293  6817  6895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-18 14:10:36.293  6817  6895 I jxcore-log: 
08-18 14:10:36.327  8180  8180 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-18 14:10:36.329  8180  8246 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-18 14:10:36.342  6913  6913 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-18 14:10:36.350  6913  6913 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-18 14:10:36.406  1034  1810 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=8251 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
08-18 14:10:36.407  1034  1810 I ActivityManager: Killing 7322:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,08-18 14:10:36.494  1034  8204 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-18 14:10:36.495  1034  8204 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-18 14:10:36.495  1034  8204 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-18 14:10:36.495  1034  8204 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
08-18 14:10:36.495  1034  8204 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-18 14:10:36.495  1034  8204 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-18 14:10:36.495  1034  8204 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-18 14:10:36.495  1034  8204 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-18 14:10:36.495  1034  8204 D DhcpStateMachine: RunningState
08-18 14:10:36.528  8180  8245 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-18 14:10:36.559  8249  8249 D AndroidRuntime: 
08-18 14:10:36.559  8249  8249 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-18 14:10:36.562  8249  8249 D AndroidRuntime: CheckJNI is OFF
08-18 14:10:36.588  1034  1971 W libprocessgroup: failed to open /acct/uid_10093/pid_7322/cgroup.procs: No such file or directory
,08-18 14:10:36.618  8251  8251 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-18 14:10:36.664  8251  8251 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-18 14:10:36.687  8249  8249 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-18 14:10:36.696  1034  1092 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-18 14:10:36.697  1034  1092 I ActivityManager: Killing 6817:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
08-18 14:10:36.714  8251  8251 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-18 14:10:36.714  8251  8251 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-18 14:10:36.714  8251  8251 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-18 14:10:36.715  8251  8251 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-18 14:10:36.715  8251  8251 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
,08-18 14:10:36.717  8251  8251 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,08-18 14:10:36.770  1034  1546 D WifiService: Client connection lost with reason: 4
08-18 14:10:36.770  1034  2054 I WindowState: WIN DEATH: Window{20e67798 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-18 14:10:36.774  1034  2054 D InputDispatcher: Window went away: Window{20e67798 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-18 14:10:36.775  8251  8251 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-18 14:10:36.812  8180  8245 D LgDataFeature: LgDataFeature() Constructor: none
08-18 14:10:36.812  8180  8245 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-18 14:10:36.893  8180  8245 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
,08-18 14:10:36.991  1034  1092 I ActivityManager:   Force finishing activity ActivityRecord{156dad4d u0 com.test.thalitest/.MainActivity t6}
,08-18 14:10:37.036  1034  2013 W ActivityManager: Spurious death for ProcessRecord{30a6c9a0 6817:com.test.thalitest/u0a118}, curProc for 6817: null
,08-18 14:10:37.038   331   350 E GBMv2   : DFP En is all cleared set to be enabled
08-18 14:10:37.042  1034  1117 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-18 14:10:37.042  1944  2561 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-18 14:10:37.042  1944  2561 D SplitWindowPolicy: topRunningActivity=ActivityInfo{d63c1fa co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-18 14:10:37.045  1944  1960 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-18 14:10:37.046  1944  1960 D SplitWindowPolicy: topRunningActivity=ActivityInfo{19eff3ab co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-18 14:10:37.053  8251  8251 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-18 14:10:37.054  1034  1117 I ActivityManager:   Force finishing activity ActivityRecord{156dad4d u0 com.test.thalitest/.MainActivity t6 f}
08-18 14:10:37.054  1034  1117 W ActivityManager: Duplicate finish request for ActivityRecord{156dad4d u0 com.test.thalitest/.MainActivity t6 f}
08-18 14:10:37.058  8251  8251 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-18 14:10:37.086  8180  8245 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
,08-18 14:10:37.089  2036  2036 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-18 14:10:37.089  8251  8251 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-18 14:10:37.091  2036  2036 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-18 14:10:37.092  1605  1605 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-18 14:10:37.098  8251  8251 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-18 14:10:37.100  3835  3835 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
,08-18 14:10:37.105  1997  1997 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-18 14:10:37.106  7763  7763 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-18 14:10:37.106  7763  7763 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-18 14:10:37.106  2036  2036 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-18 14:10:37.107  2503  2620 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-18 14:10:37.108  2036  2129 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
08-18 14:10:37.118  1034  1442 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-18 14:10:37.122  8251  8251 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-18 14:10:37.132  4623  4623 I art     : Explicit concurrent mark sweep GC freed 8244(471KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 563us total 71.288ms
08-18 14:10:37.157  1034  1935 V SIM_STK : Menu title from STK is T-Mobile
,08-18 14:10:37.166  4520  4520 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-18 14:10:37.169  4520  4520 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-18 14:10:37.169  4520  4520 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-18 14:10:37.169  4520  4520 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-18 14:10:37.169  4520  4520 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-18 14:10:37.169  4520  4520 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-18 14:10:37.169  4520  4520 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-18 14:10:37.169  4520  4520 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-18 14:10:37.169  4520  4520 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-18 14:10:37.169  4520  4520 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-18 14:10:37.169  4520  4520 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-18 14:10:37.169  4520  4520 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-18 14:10:37.180  1034  1034 D administrator: Handling package changes for user 0
08-18 14:10:37.181  8180  8245 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
08-18 14:10:37.183  6913  6913 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-18 14:10:37.184  8180  8245 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
,08-18 14:10:37.184  8180  8245 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-18 14:10:37.187  6913  6913 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-18 14:10:37.202  8180  8245 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
,08-18 14:10:37.204  8180  8245 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
08-18 14:10:37.209  8180  8245 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
08-18 14:10:37.209  8180  8180 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-18 14:10:37.210  8180  8246 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-18 14:10:37.221  1605  1654 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-18 14:10:37.221  1605  1654 D KeyguardModel: createShortcutInfo...
,08-18 14:10:37.222  2036  2036 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-18 14:10:37.223  2036  2036 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-18 14:10:37.224  1907  1907 D ActionManagerService: notifyUserLog: 1000003
08-18 14:10:37.225  3835  4510 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-18 14:10:37.225  8180  8245 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
08-18 14:10:37.226  1605  1654 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-18 14:10:37.226  1605  1654 D KeyguardModel: createShortcutInfo...
08-18 14:10:37.232  1605  1654 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-18 14:10:37.232  1605  1654 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-18 14:10:37.233  1605  1654 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,08-18 14:10:37.234  1605  1654 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-18 14:10:37.243  1605  1654 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-18 14:10:37.243  1605  1654 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-18 14:10:37.244  1605  1654 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-18 14:10:37.244  1605  1654 D KeyguardModel: createShortcutInfo...
08-18 14:10:37.249  1605  1654 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-18 14:10:37.249  1605  1654 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-18 14:10:37.250  1605  1605 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-18 14:10:37.251  6913  6913 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-18 14:10:37.251  2036  2036 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-18 14:10:37.252  2036  2036 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-18 14:10:37.252  1605  1654 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-18 14:10:37.253  1605  1654 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-18 14:10:37.258  2036  2036 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-18 14:10:37.259  1907  1907 D ActionManagerService: notifyUserLog: 1000004
08-18 14:10:37.259  3835  4510 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-18 14:10:37.259  1605  1654 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-18 14:10:37.259  1605  1654 D KeyguardModel: createShortcutInfo...
08-18 14:10:37.260  3835  3850 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,08-18 14:10:37.264  6913  6913 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-18 14:10:37.264  1605  1654 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-18 14:10:37.264  1605  1654 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-18 14:10:37.265  2036  2036 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-18 14:10:37.265  2036  2036 I GBoardWebViewUtils: , create_time: 1430832262123
08-18 14:10:37.265  2036  2036 I GBoardWebViewUtils: , expire_time: 0
08-18 14:10:37.265  2036  2036 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-18 14:10:37.265  2036  2036 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-18 14:10:37.265  2036  2036 I GBoardWebViewUtils: , display: false
08-18 14:10:37.265  2036  2036 I GBoardWebViewUtils: , animation: false }
08-18 14:10:37.265  2036  2036 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-18 14:10:37.265  2036  2036 I GBoardWebViewUtils: , create_time: 1430832262287
08-18 14:10:37.265  2036  2036 I GBoardWebViewUtils: , expire_time: 0
08-18 14:10:37.265  2036  2036 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-18 14:10:37.265  2036  2036 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-18 14:10:37.265  2036  2036 I GBoardWebViewUtils: , display: false
08-18 14:10:37.265  2036  2036 I GBoardWebViewUtils: , animation: false }
08-18 14:10:37.265  2036  2036 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1471007225619
08-18 14:10:37.265  2036  2036 I GBoardWebViewUtils: , create_time: 1471007226523
08-18 14:10:37.265  2036  2036 I GBoardWebViewUtils: , expire_time: 0
08-18 14:10:37.265  2036  2036 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide.html?id=guide_1111111111116_1471007225619&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-18 14:10:37.265  2036  2036 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-18 14:10:37.265  2036  2036 I GBoardWebViewUtils: , display: false
08-18 14:10:37.265  2036  2036 I GBoardWebViewUtils: , animation: false }
08-18 14:10:37.265  1605  1654 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-18 14:10:37.265  1605  1654 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-18 14:10:37.267  1605  1654 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-18 14:10:37.267  1605  1654 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-18 14:10:37.273  2036  8294 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-18 14:10:37.274  1605  1654 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-18 14:10:37.274  1605  1654 D KeyguardModel: createShortcutInfo...
,08-18 14:10:37.275  8251  8251 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-18 14:10:37.275  8251  8251 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-18 14:10:37.281  1872  1872 D SplitUIManager: split_name #11 / not available #0
08-18 14:10:37.281  1872  1872 D SplitUIService: removed split : 
08-18 14:10:37.282  8251  8251 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-18 14:10:37.284  1034  1051 V SIM_STK : Menu title from STK is T-Mobile
08-18 14:10:37.284  1034  1051 V SIM_STK : Menu title from STK is T-Mobile
08-18 14:10:37.290  2036  2036 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-18 14:10:37.291  8180  8180 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-18 14:10:37.292  2036  2036 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-18 14:10:37.298  8180  8246 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-18 14:10:37.303  1872  1872 D SplitUIManager: split_name #11 / not available #0
08-18 14:10:37.303  1872  1872 I SplitUIService: split app #11
,08-18 14:10:37.305  1034  1091 W InputMethodInfo: Duplicated subtype definition found: , voice
08-18 14:10:37.306  1605  1605 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-18 14:10:37.306  1605  1605 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-18 14:10:37.309  1605  1605 D KeyguardModel: handleShortcutListChanged...
08-18 14:10:37.309  1605  1605 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-18 14:10:37.325  6913  6913 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-18 14:10:37.335  6913  6913 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-18 14:10:37.338  8251  8251 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-18 14:10:37.338  8251  8251 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-18 14:10:37.339  8251  8251 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-18 14:10:37.341  8180  8180 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-18 14:10:37.342  8180  8246 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-18 14:10:37.360  1034  1935 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-18 14:10:37.361  7763  7763 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-18 14:10:37.361  7763  7763 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-18 14:10:37.361  7763  7763 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-18 14:10:37.361  7763  7763 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-18 14:10:37.361  7763  7763 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-18 14:10:37.361  7763  7763 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-18 14:10:37.362  7763  7763 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-18 14:10:37.362  7763  7763 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-18 14:10:37.362  7763  7763 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-18 14:10:37.362  7763  7763 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-18 14:10:37.362  7763  7763 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-18 14:10:37.363  2036  2036 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
,08-18 14:10:37.365  1605  1654 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-18 14:10:37.365  1605  1654 D KeyguardModel: createShortcutInfo...
08-18 14:10:37.365  6913  6913 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-18 14:10:37.370  1034  1971 V SIM_STK : Menu title from STK is T-Mobile
08-18 14:10:37.371  1605  1654 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-18 14:10:37.371  1605  1654 D KeyguardModel: createShortcutInfo...
08-18 14:10:37.372  1605  1654 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-18 14:10:37.372  1605  1654 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-18 14:10:37.373  1605  1654 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-18 14:10:37.373  1605  1654 D KeyguardModel: createShortcutInfo...
08-18 14:10:37.374  1605  1654 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-18 14:10:37.374  1605  1654 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-18 14:10:37.375  1605  1654 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-18 14:10:37.376  1605  1654 D KeyguardModel: createShortcutInfo...
,08-18 14:10:37.387  1605  1654 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-18 14:10:37.387  1605  1654 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-18 14:10:37.388  1605  1654 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-18 14:10:37.388  1605  1654 D KeyguardModel: createShortcutInfo...
08-18 14:10:37.392  1605  1605 D KeyguardModel: handleShortcutListChanged...
08-18 14:10:37.392  1605  1605 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-18 14:10:37.395  1034  1034 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-18 14:10:37.395  1034  1034 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-18 14:10:37.395  1034  1034 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-18 14:10:37.398  6913  6913 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-18 14:10:37.408  1034  1579 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-18 14:10:37.422  8251  8251 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-18 14:10:37.422  8251  8251 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-18 14:10:37.423  8251  8251 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-18 14:10:37.424  6913  6913 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-18 14:10:37.424  6913  6913 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-18 14:10:37.425  6913  6913 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-18 14:10:37.425  6913  6913 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-18 14:10:37.425  6913  6913 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-18 14:10:37.433  6913  6913 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-18 14:10:37.433  6913  6913 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-18 14:10:37.433  6913  6913 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-18 14:10:37.433  6913  6913 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-18 14:10:37.433  6913  6913 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-18 14:10:37.433  6913  6913 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-18 14:10:37.433  6913  6913 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-18 14:10:37.439  2036  2036 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
08-18 14:10:37.441  8180  8180 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-18 14:10:37.441  8180  8246 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-18 14:10:37.443  2036  2036 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-18 14:10:37.445  2036  2036 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
,08-18 14:10:37.446  2036  2036 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-18 14:10:37.447  2036  2036 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-18 14:10:37.448  2036  2036 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-18 14:10:37.461  6913  6913 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-18 14:10:37.468  6913  6913 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-18 14:10:37.472  8251  8251 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-18 14:10:37.472  8251  8251 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-18 14:10:37.473  8251  8251 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-18 14:10:37.474  8180  8180 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-18 14:10:37.475  8180  8246 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-18 14:10:37.478  2036  2036 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-18 14:10:37.478  2036  2036 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-18 14:10:37.478  6913  6913 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-18 14:10:37.478  1034  1103 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1e861a80 u0 com.lge.launcher2/.Launcher t5} time:218222
08-18 14:10:37.482  6913  6913 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-18 14:10:37.485  2036  2261 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-18 14:10:37.485  2036  2261 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-18 14:10:37.486  8251  8251 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-18 14:10:37.486  8251  8251 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-18 14:10:37.486  8251  8251 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-18 14:10:37.488  8180  8180 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-18 14:10:37.489  8180  8246 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-18 14:10:37.492  2036  2036 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-18 14:10:37.493  2036  2036 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-18 14:10:37.494  2036  2036 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-18 14:10:37.495  6913  6913 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-18 14:10:37.498  6913  6913 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-18 14:10:37.505  2036  2036 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
,08-18 14:10:37.507  2642  2642 D [Concierge]Service: onStartCommand(). Type : 8
08-18 14:10:37.507  2642  2642 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-18 14:10:37.509  2642  2642 D [Concierge]Service: Update widget ID : 11
08-18 14:10:37.509  2036  2036 D [Concierge]WidgetView: change position of spinner
08-18 14:10:37.514  2036  2036 I [Concierge]WidgetView: initWebView(). Time : 1471522237514
08-18 14:10:37.514  2642  2642 D [Concierge]Service: onStartCommand(). Type : 0
08-18 14:10:37.515  8251  8251 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-18 14:10:37.515  8251  8251 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-18 14:10:37.516  8251  8251 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-18 14:10:37.523  8180  8180 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-18 14:10:37.523  8180  8246 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-18 14:10:37.527  1034  1540 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-18 14:10:37.528  1034  1540 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-18 14:10:37.528  1034  1540 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-18 14:10:37.528  1034  1540 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-18 14:10:37.529  1034  1540 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-18 14:10:37.529  1034  1540 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-18 14:10:37.529  1034  1547 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
08-18 14:10:37.529  1034  1547 D ConnectivityService: identical MTU - not setting
08-18 14:10:37.529  1034  1547 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-18 14:10:37.530  1034  1547 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-18 14:10:37.530  1034  1547 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-18 14:10:37.530  1034  1547 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-18 14:10:37.530  1034  1547 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-18 14:10:37.531  1034  1117 I art     : Explicit concurrent mark sweep GC freed 81234(4MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 43MB/65MB, paused 1.658ms total 308.470ms
08-18 14:10:37.531  1605  1818 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-18 14:10:37.534  6913  6913 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-18 14:10:37.539  6913  6913 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-18 14:10:37.541  2036  2036 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 800306056
08-18 14:10:37.542  2036  2036 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-18 14:10:37.542  2036  2036 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-18 14:10:37.545  2036  2036 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@22d5efee
08-18 14:10:37.545  2036  2036 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-18 14:10:37.547  8251  8251 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-18 14:10:37.547  2036  2036 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-18 14:10:37.547  8251  8251 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-18 14:10:37.547  2036  2036 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-18 14:10:37.551  8251  8251 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-18 14:10:37.557  2036  2036 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-18 14:10:37.557  2036  2036 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-18 14:10:37.557  2036  2036 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-18 14:10:37.559  2036  2036 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1471522047449, New one : 1471522237514
08-18 14:10:37.560  2036  2036 D [Concierge]WidgetView: Unregister all receivers
,08-18 14:10:37.560  2036  2036 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-18 14:10:37.560  8180  8180 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-18 14:10:37.560  2036  2036 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-18 14:10:37.563  2036  2036 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-18 14:10:37.565  2036  2036 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-18 14:10:37.566  8249  8249 D AndroidRuntime: Shutting down VM
08-18 14:10:37.567  2036  2036 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-18 14:10:37.569  2036  2036 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-18 14:10:37.570  2036  2036 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-18 14:10:37.576  2036  2036 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-18 14:10:37.577  2036  2036 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-18 14:10:37.626  1034  1117 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8302 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-18 14:10:37.635  6913  6913 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-18 14:10:37.652  6913  6913 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-18 14:10:37.657  1034  2035 I ActivityManager: Killing 7361:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
08-18 14:10:37.659  2036  2036 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-18 14:10:37.668  2036  2036 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-18 14:10:37.668  2036  2036 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
,08-18 14:10:37.671  2036  2036 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-18 14:10:37.689  2036  2036 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1bf48690 time:218433
,08-18 14:10:37.705  1034  1091 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-18 14:10:37.709  1034  1091 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-18 14:10:37.768  1034  1908 W libprocessgroup: failed to open /acct/uid_10005/pid_7361/cgroup.procs: No such file or directory
,08-18 14:10:37.769  8251  8251 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-18 14:10:37.771  8251  8251 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-18 14:10:37.774  2036  2036 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-18 14:10:37.776  8251  8251 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-18 14:10:37.784  8180  8180 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-18 14:10:37.787  8132  8132 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-18 14:10:37.789  2036  2036 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
08-18 14:10:37.792  8132  8132 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-18 14:10:37.798  6913  6913 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-18 14:10:37.805  6913  6913 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-18 14:10:37.814  8251  8251 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-18 14:10:37.814  8251  8251 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-18 14:10:37.815  8251  8251 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-18 14:10:37.815  8251  8251 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-18 14:10:37.817  8251  8251 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-18 14:10:37.822  8180  8180 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-18 14:10:37.825  8132  8132 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-18 14:10:37.826  8132  8132 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,08-18 14:10:37.830  6913  6913 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-18 14:10:37.835  6913  6913 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-18 14:10:37.843  8251  8251 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-18 14:10:37.844  8251  8251 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-18 14:10:37.845  8251  8251 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-18 14:10:37.845  8251  8251 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-18 14:10:37.846  8251  8251 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-18 14:10:37.849  2036  2940 I GBoardtInterface: onReloaded()
08-18 14:10:37.851  2036  2036 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-18 14:10:37.852  8180  8180 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-18 14:10:37.855  3835  3850 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-18 14:10:37.861  8251  8251 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-18 14:10:37.861  3835  4506 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-18 14:10:37.862  8251  8251 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-18 14:10:37.863  8251  8251 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,08-18 14:10:37.871  1907  1907 D ActionManagerService: notifyUserLog: 1000001
08-18 14:10:37.873  3835  4510 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-18 14:10:37.873  3835  4510 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-18 14:10:37.882  1907  1907 D ActionManagerService: notifyUserLog: 1000001
08-18 14:10:37.884  3835  4510 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-18 14:10:37.884  3835  4510 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-18 14:10:37.884  3835  4510 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-18 14:10:37.884  3835  4510 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
,08-18 14:10:37.885  3835  3850 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-18 14:10:37.890  2036  2036 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-18 14:10:37.890  2036  2036 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-18 14:10:37.894  2036  2036 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-18 14:10:37.894  2036  2036 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-18 14:10:37.897  2036  2036 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide2.html?id=guide_1111111111116_1471007225619&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-18 14:10:37.897  2036  2036 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide2.html?id=guide_1111111111116_1471007225619&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
,08-18 14:10:37.929  8251  8251 D LgDataFeature: LgDataFeature() Constructor: none
08-18 14:10:37.929  8251  8251 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-18 14:10:37.939  8251  8251 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-18 14:10:37.941  8251  8251 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-18 14:10:37.941  8251  8251 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-18 14:10:37.941  8251  8251 V SoundPool: doLoad: loading sample sampleID=1
08-18 14:10:37.941  8251  8324 V SoundPool: Start decode
08-18 14:10:37.941  8251  8324 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-18 14:10:37.941   314  2148 V MediaPlayerService: decode(23, 10857164, 17813)
08-18 14:10:37.941   314  2148 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-18 14:10:37.941   314  2148 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-18 14:10:37.941   314  2148 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-18 14:10:37.942   314  2148 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-18 14:10:37.942   314  2148 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-18 14:10:37.942   314  2148 V MediaPlayerService: player type = 3
08-18 14:10:37.942   314  2148 V AwesomePlayer: AwesomePlayer create()
08-18 14:10:37.942   314  2148 V AwesomePlayer: reset_l() 
08-18 14:10:37.942   314  2148 V AwesomePlayer: cancelPlayerEvents
08-18 14:10:37.942   314  2148 V AwesomePlayer: setAudioSink() 
08-18 14:10:37.942   314  2148 V AwesomePlayer: reset_l() 
08-18 14:10:37.942   314  2148 V AudioCache: notify(0xb5474580, 8, 0, 0)
08-18 14:10:37.942   314  2148 V AudioCache: ignored
08-18 14:10:37.942   314  2148 V AwesomePlayer: cancelPlayerEvents
08-18 14:10:37.942   314  2148 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-18 14:10:37.942   314  2148 V AwesomePlayer: setDataSource_l dataSource
08-18 14:10:37.942   314  2148 V LGParserOSAL: SniffLGParser start
08-18 14:10:37.942   314  2148 V LGParserOSAL: MainType:5, SubType=0
08-18 14:10:37.942   314  2148 V LGParserOSAL: #### check Mime : application/ogg
08-18 14:10:37.942   314  2148 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-18 14:10:37.942   314  2148 E MediaExtractor: Use LGExtractor :application/ogg 
08-18 14:10:37.946  8251  8251 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,08-18 14:10:37.950  7691  7691 D UEI.SmartControl: QS Service created
08-18 14:10:37.957  8251  8251 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-18 14:10:37.958  8251  8251 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-18 14:10:37.958  7691  7691 I UEI.SmartControl: Service initServices...
08-18 14:10:37.958  8251  8251 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-18 14:10:37.971  8251  8251 V LGMDMManager: Create singleton instance
,08-18 14:10:37.982   314  2148 V LGParserOSAL: supported mime: application/ogg
08-18 14:10:37.982   314  2148 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-18 14:10:37.982   314  2148 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-18 14:10:37.982   314  2148 V AwesomePlayer: mBitrate = -1 bits/sec
08-18 14:10:37.983   314  2148 V AwesomePlayer: AudioTrack Setting
08-18 14:10:37.983   314  2148 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-18 14:10:37.983   314  2148 V AwesomePlayer: setAudioSource() 
08-18 14:10:37.983   314  2148 V MediaPlayerService: prepare
08-18 14:10:37.983   314  2148 V AwesomePlayer: prepareAsync_l() 
08-18 14:10:37.983   314  2148 V MediaPlayerService: wait for prepare
08-18 14:10:37.983   314  8325 V AwesomePlayer: onPrepareAsyncEvent() 
08-18 14:10:37.983   314  8325 V AwesomePlayer: initAudioDecoder() 
08-18 14:10:37.983   314  8325 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-18 14:10:37.983   314  8325 V AudioSystem: isOffloadSupported()
08-18 14:10:37.983   314  8325 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-18 14:10:37.983   314  8325 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-18 14:10:37.983   314  8325 I AudioFlinger: isAudioPlaybackHookOn() false
08-18 14:10:37.983   314  8325 V AwesomePlayer: getUseOffload() = 0 
08-18 14:10:37.983   314  8325 V OMXCodec: OMXCodec::Create
08-18 14:10:37.983   314  8325 V OMXCodec: findMatchingCodecs()
08-18 14:10:37.983   314  8325 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-18 14:10:37.983   314  8325 V OMXCodec: matchingCodecs.size()=1
08-18 14:10:37.983   314  8325 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-18 14:10:37.984   314  8325 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-18 14:10:37.984   314  8325 V LGCodecAdapter: LG Codec Adapter start
08-18 14:10:37.984   314  8325 V OMXCodec: OMXCodec Createtor
08-18 14:10:37.984   314  8325 V OMXCodec: setComponentRole
08-18 14:10:37.984   314  8325 V OMXCodec: configureCodec protected=0
08-18 14:10:37.984   314  8325 V LGCodecAdapter: called getLGCodecSpecificData
08-18 14:10:37.984   314  8325 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-18 14:10:37.984   314  8325 V LGCodecOSAL: Called LGconfigureCodecMETA
08-18 14:10:37.984   314  8325 V LGCodecOSAL: Called LGconfigureCodecMSG
08-18 14:10:37.984   314  8325 V LGCodecOSAL: Not support LGCodec
08-18 14:10:37.984   314  8325 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-18 14:10:37.984   314  8325 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-18 14:10:37.984   314  8325 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-18 14:10:37.985   314  8325 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-18 14:10:37.985   314  8325 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-18 14:10:37.985   314  8325 V AudioSystem: isOffloadSupported()
08-18 14:10:37.985   314  8325 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-18 14:10:37.985   314  8325 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-18 14:10:37.985   314  8325 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-18 14:10:37.985   314  8325 V OMXCodec: init()
08-18 14:10:37.985   314  8325 V OMXCodec: [OMX.google.vorbis.decoder] set,State mState=1 , newState=2
08-18 14:10:37.985   314  8325 V OMXCodec: allocateBuffers
08-18 14:10:37.985   314  8325 V OMXCodec: allocateBuffersOnPort portIndex=0
08-18 14:10:37.985   314  8325 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-18 14:10:37.985   314  8325 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on input port
08-18 14:10:37.985   314  8325 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on input port
08-18 14:10:37.985   314  8325 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on input port
08-18 14:10:37.985   314  8325 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on input port
08-18 14:10:37.985   314  8325 V OMXCodec: allocateBuffersOnPort portIndex=1
08-18 14:10:37.985   314  8325 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-18 14:10:37.985   314  8325 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7fb0 on output port
08-18 14:10:37.985   314  8325 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57c11f0 on output port
08-18 14:10:37.985   314  8325 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57c12e0 on output port
08-18 14:10:37.985   314  8325 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57c14c0 on output port
08-18 14:10:37.985   314  8325 V OMXCodec: init() mAsyncCompletion wait!!! 
08-18 14:10:37.985   314  8327 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-18 14:10:37.985   314  8327 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-18 14:10:37.986   314  8327 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-18 14:10:37.986   314  8325 V OMXCodec: init() mAsyncCompletion wait!!! 
08-18 14:10:37.986   314  8327 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-18 14:10:37.986   314  8327 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-18 14:10:37.986   314  8327 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-18 14:10:37.986   314  8325 V OMXCodec: init() mAsyncCompletion wait free! 
08-18 14:10:37.986   314  8325 V AwesomePlayer: finishAsyncPrepare_l() 
08-18 14:10:37.986   314  8325 V AudioCache: notify(0xb5474580, 5, 0, 0)
08-18 14:10:37.986   314  8325 V AudioCache: ignored
08-18 14:10:37.986   314  8325 V AudioCache: notify(0xb5474580, 1, 0, 0)
08-18 14:10:37.986   314  8325 V AudioCache: prepared
08-18 14:10:37.986   314  2148 V AudioCache: wait - success
08-18 14:10:37.986   314  2148 V MediaPlayerService: start
08-18 14:10:37.986   314  2148 V AwesomePlayer: play_l() 
08-18 14:10:37.986   314  2148 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-18 14:10:37.986   314  2148 V AwesomePlayer: createAudioPlayer_l
08-18 14:10:37.986   314  2148 V AwesomePlayer: seekAudioIfNecessary_l() 
08-18 14:10:37.986   314  2148 V AwesomePlayer: startAudioPlayer_l() 
08-18 14:10:37.986   314  2148 D AudioPlayer: start of Playback, useOffload 0
08-18 14:10:37.986   314  2148 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-18 14:10:37.986   314  2148 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-18 14:10:37.989   314  8327 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-18 14:10:37.989   314  8327 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-18 14:10:37.989   314  8327 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
,08-18 14:10:37.989   314  8327 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-18 14:10:37.989   314  8327 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-18 14:10:37.989   314  8327 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-18 14:10:37.989   314  8327 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041886128
08-18 14:10:37.989   314  8327 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-18 14:10:37.989   314  8327 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044807152
08-18 14:10:37.989   314  8327 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-18 14:10:37.989   314  8327 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044807392
08-18 14:10:37.989   314  8327 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-18 14:10:37.989   314  8327 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044807872
08-18 14:10:37.989   314  8327 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-18 14:10:37.989   314  8327 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-18 14:10:37.989   314  8327 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-18 14:10:37.989   314  8327 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-18 14:10:37.989   314  8327 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-18 14:10:37.990   314  8327 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-18 14:10:37.990   314  8327 V OMXCodec: allocateBuffersOnPort portIndex=1
08-18 14:10:37.990   314  8327 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-18 14:10:37.990   314  8327 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57c12e0 on output port
08-18 14:10:37.990   314  8327 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57c11f0 on output port
08-18 14:10:37.990   314  8327 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7fb0 on output port
08-18 14:10:37.990   314  8327 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f1f0 on output port
08-18 14:10:37.990   314  8327 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-18 14:10:37.990   314  8327 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-18 14:10:37.991   314  2148 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-18 14:10:37.991   314  2148 V AudioCache: notify(0xb5474580, 6, 0, 0)
08-18 14:10:37.991   314  2148 V AudioCache: ignored
08-18 14:10:37.992   314  2148 V MediaPlayerService: wait for playback complete
08-18 14:10:37.992   314  8328 V AudioCache: write(0xb16f7000, 4096)
08-18 14:10:37.992   314  8328 V AudioCache: memcpy(0xaf006000, 0xb16f7000, 4096)
08-18 14:10:37.995   314  8328 V AudioCache: write(0xb16f7000, 4096)
08-18 14:10:37.995   314  8328 V AudioCache: memcpy(0xaf007000, 0xb16f7000, 4096)
08-18 14:10:37.996   314  8328 V AudioCache: write(0xb16f7000, 4096)
08-18 14:10:37.996   314  8328 V AudioCache: memcpy(0xaf008000, 0xb16f7000, 4096)
08-18 14:10:37.996   314  8328 V AudioCache: write(0xb16f7000, 4096)
08-18 14:10:37.997   314  8328 V AudioCache: memcpy(0xaf009000, 0xb16f7000, 4096)
08-18 14:10:37.997   314  8328 V AudioCache: write(0xb16f7000, 4096)
08-18 14:10:37.997   314  8328 V AudioCache: memcpy(0xaf00a000, 0xb16f7000, 4096)
08-18 14:10:37.997   314  8328 V AudioCache: write(0xb16f7000, 4096)
08-18 14:10:37.997   314  8328 V AudioCache: memcpy(0xaf00b000, 0xb16f7000, 4096)
08-18 14:10:37.997   314  8328 V AudioCache: write(0xb16f7000, 4096)
08-18 14:10:37.997   314  8328 V AudioCache: memcpy(0xaf00c000, 0xb16f7000, 4096)
08-18 14:10:37.997   314  8328 V AudioCache: write(0xb16f7000, 4096)
08-18 14:10:37.997   314  8328 V AudioCache: memcpy(0xaf00d000, 0xb16f7000, 4096)
08-18 14:10:37.998   314  8328 V AudioCache,: write(0xb16f7000, 4096)
08-18 14:10:37.998   314  8328 V AudioCache: memcpy(0xaf00e000, 0xb16f7000, 4096)
08-18 14:10:37.998   314  8328 V AudioCache: write(0xb16f7000, 4096)
08-18 14:10:37.998   314  8328 V AudioCache: memcpy(0xaf00f000, 0xb16f7000, 4096)
08-18 14:10:37.998   314  8328 V AudioCache: write(0xb16f7000, 4096)
08-18 14:10:37.998   314  8328 V AudioCache: memcpy(0xaf010000, 0xb16f7000, 4096)
08-18 14:10:37.999   314  8328 V AudioCache: write(0xb16f7000, 4096)
08-18 14:10:37.999   314  8328 V AudioCache: memcpy(0xaf011000, 0xb16f7000, 4096)
08-18 14:10:37.999   314  8328 V AudioCache: write(0xb16f7000, 4096)
08-18 14:10:37.999   314  8328 V AudioCache: memcpy(0xaf012000, 0xb16f7000, 4096)
08-18 14:10:37.999   314  8328 V AudioCache: write(0xb16f7000, 4096)
08-18 14:10:37.999   314  8328 V AudioCache: memcpy(0xaf013000, 0xb16f7000, 4096)
08-18 14:10:38.000   314  8328 V AudioCache: write(0xb16f7000, 4096)
08-18 14:10:38.000   314  8328 V AudioCache: memcpy(0xaf014000, 0xb16f7000, 4096)
08-18 14:10:38.000   314  8328 V AudioCache: write(0xb16f7000, 4096)
08-18 14:10:38.000   314  8328 V AudioCache: memcpy(0xaf015000, 0xb16f7000, 4096)
08-18 14:10:38.004   314  8328 V AudioCache: write(0xb16f7000, 4096)
08-18 14:10:38.004   314  8328 V AudioCache: memcpy(0xaf016000, 0xb16f7000, 4096)
,08-18 14:10:38.006   314  8328 V AudioCache: write(0xb16f7000, 4096)
08-18 14:10:38.006   314  8328 V AudioCache: memcpy(0xaf017000, 0xb16f7000, 4096)
08-18 14:10:38.007   314  8328 V AudioCache: write(0xb16f7000, 4096)
08-18 14:10:38.007   314  8328 V AudioCache: memcpy(0xaf018000, 0xb16f7000, 4096)
08-18 14:10:38.008   314  8328 V AudioCache: write(0xb16f7000, 4096)
08-18 14:10:38.008   314  8328 V AudioCache: memcpy(0xaf019000, 0xb16f7000, 4096)
08-18 14:10:38.008   314  8328 V AudioCache: write(0xb16f7000, 4096)
08-18 14:10:38.008   314  8328 V AudioCache: memcpy(0xaf01a000, 0xb16f7000, 4096)
08-18 14:10:38.010   314  8328 V AudioCache: write(0xb16f7000, 4096)
08-18 14:10:38.010   314  8328 V AudioCache: memcpy(0xaf01b000, 0xb16f7000, 4096)
08-18 14:10:38.010   314  8328 V AudioCache: write(0xb16f7000, 4096)
08-18 14:10:38.010   314  8328 V AudioCache: memcpy(0xaf01c000, 0xb16f7000, 4096)
08-18 14:10:38.010   314  8328 V AudioCache: write(0xb16f7000, 4096)
08-18 14:10:38.010   314  8328 V AudioCache: memcpy(0xaf01d000, 0xb16f7000, 4096)
08-18 14:10:38.011   314  8328 V AudioCache: write(0xb16f7000, 4096)
08-18 14:10:38.011   314  8328 V AudioCache: memcpy(0xaf01e000, 0xb16f7000, 4096)
08-18 14:10:38.011   314  8328 V AudioCache: write(0xb16f7000, 4096)
08-18 14:10:38.011   314  8328 V AudioCache: memcpy(0xaf01f000, 0xb16f7000, 4096)
08-18 14:10:38.011   314  8328 V AudioCache: write(0xb16f7000, 4096)
08-18 14:10:38.011   314  8328 V AudioCache: memcpy(0xaf020000, 0xb16f7000, 4096)
08-18 14:10:38.011   314  8328 V AudioCache: write(0xb16f7000, 4096)
08-18 14:10:38.011   314  8328 V AudioCache: memcpy(0xaf021000, 0xb16f7000, 4096)
08-18 14:10:38.011   314  8328 V AudioCache: write(0xb16f7000, 4096)
08-18 14:10:38.011   314  8328 V AudioCache: memcpy(0xaf022000, 0xb16f7000, 4096)
08-18 14:10:38.012   314  8328 V AudioCache: write(0xb16f7000, 4096)
08-18 14:10:38.012   314  8328 V AudioCache: memcpy(0xaf023000, 0xb16f7000, 4096)
08-18 14:10:38.012   314  8328 V AudioCache: write(0xb16f7000, 4096)
08-18 14:10:38.012   314  8328 V AudioCache: memcpy(0xaf024000, 0xb16f7000, 4096)
08-18 14:10:38.013   314  8328 V AudioCache: write(0xb16f7000, 4096)
08-18 14:10:38.013   314  8328 V AudioCache: memcpy(0xaf025000, 0xb16f7000, 4096)
08-18 14:10:38.013   314  8328 V AudioCache: write(0xb16f7000, 4096)
08-18 14:10:38.013   314  8328 V AudioCache: memcpy(0xaf026000, 0xb16f7000, 4096)
08-18 14:10:38.013   314  8328 V AudioCache: write(0xb16f7000, 4096)
08-18 14:10:38.013   314  8328 V AudioCache: memcpy(0xaf027000, 0xb16f7000, 4096)
08-18 14:10:38.013   314  8328 V AudioCache: write(0xb16f7000, 4096)
08-18 14:10:38.013   314  8328 V AudioCache: memcpy(0xaf028000, 0xb16f7000, 4096)
08-18 14:10:38.014   314  8328 V AudioCache: write(0xb16f7000, 4096)
08-18 14:10:38.014   314  8328 V AudioCache: memcpy(0xaf029000, 0xb16f7000, 4096)
08-18 14:10:38.014   314  8328 V AudioCache: write(0xb16f7000, 4096)
08-18 14:10:38.014   314  8328 V AudioCache: memcpy(0xaf02a000, 0xb16f7000, 4096)
08-18 14:10:38.015   314  8328 V AudioCache: write(0xb16f7000, 4096)
08-18 14:10:38.015   314  8328 V AudioCache: memcpy(0xaf02b000, 0xb16f7000, 4096)
08-18 14:10:38.015   314  8328 V AudioCache: write(0xb16f7000, 4096)
08-18 14:10:38.015   314  8328 V AudioCache: memcpy(0xaf02c000, 0xb16f7000, 4096)
08-18 14:10:38.016   314  8328 V AudioCache: write(0xb16f7000, 4096)
08-18 14:10:38.016   314  8328 V AudioCache: memcpy(0xaf02d000, 0xb16f7000, 4096)
08-18 14:10:38.016   314  8328 V AudioCache: write(0xb16f7000, 4096)
08-18 14:10:38.016   314  8328 V AudioCache: memcpy(0xaf02e000, 0xb16f7000, 4096)
,08-18 14:10:38.016   314  8328 V AudioCache: write(0xb16f7000, 4096)
08-18 14:10:38.016   314  8328 V AudioCache: memcpy(0xaf02f000, 0xb16f7000, 4096)
08-18 14:10:38.016   314  8328 V AudioCache: write(0xb16f7000, 4096)
08-18 14:10:38.016   314  8328 V AudioCache: memcpy(0xaf030000, 0xb16f7000, 4096)
08-18 14:10:38.019  7691  7691 D UEI.SmartControl: QS start get config
08-18 14:10:38.021   314  8328 V AudioCache: write(0xb16f7000, 4096)
08-18 14:10:38.021   314  8328 V AudioCache: memcpy(0xaf031000, 0xb16f7000, 4096)
08-18 14:10:38.021   314  8328 V AudioCache: write(0xb16f7000, 4096)
08-18 14:10:38.021   314  8328 V AudioCache: memcpy(0xaf032000, 0xb16f7000, 4096)
08-18 14:10:38.021   314  8328 V AudioCache: write(0xb16f7000, 4096)
08-18 14:10:38.021   314  8328 V AudioCache: memcpy(0xaf033000, 0xb16f7000, 4096)
08-18 14:10:38.021   314  8328 V AudioCache: write(0xb16f7000, 4096)
08-18 14:10:38.021   314  8328 V AudioCache: memcpy(0xaf034000, 0xb16f7000, 4096)
08-18 14:10:38.022   314  8327 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-18 14:10:38.022   314  8328 V AudioCache: write(0xb16f7000, 4096)
08-18 14:10:38.022   314  8328 V AudioCache: memcpy(0xaf035000, 0xb16f7000, 4096)
08-18 14:10:38.022   314  8328 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-18 14:10:38.022   314  8328 V AudioCache: write(0xb16f7000, 4096)
08-18 14:10:38.022   314  8328 V AudioCache: memcpy(0xaf036000, 0xb16f7000, 4096)
08-18 14:10:38.022   314  8328 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-18 14:10:38.022   314  8328 V AudioCache: write(0xb16f7000, 4096)
08-18 14:10:38.022   314  8328 V AudioCache: memcpy(0xaf037000, 0xb16f7000, 4096)
08-18 14:10:38.022   314  8328 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-18 14:10:38.022   314  8328 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-18 14:10:38.022   314  8328 V AwesomePlayer: postAudioEOS() 
08-18 14:10:38.022   314  8328 V AudioCache: write(0xb16f7000, 280)
08-18 14:10:38.022   314  8328 V AudioCache: memcpy(0xaf038000, 0xb16f7000, 280)
08-18 14:10:38.024   314  8325 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-18 14:10:38.024   314  8325 V AwesomePlayer: onStreamDone
08-18 14:10:38.024   314  8325 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-18 14:10:38.024   314  8325 V AudioCache: notify(0xb5474580, 2, 0, 0)
08-18 14:10:38.024   314  8325 V AudioCache: playback complete
08-18 14:10:38.024   314  8325 V AwesomePlayer: pause_l() 
08-18 14:10:38.024   314  8325 V AudioCache: notify(0xb5474580, 7, 0, 0)
08-18 14:10:38.024   314  8325 V AudioCache: ignored
08-18 14:10:38.024   314  8325 V AwesomePlayer: cancelPlayerEvents
08-18 14:10:38.024   314  2148 V AudioCache: wait - success
08-18 14:10:38.024   314  2148 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-18 14:10:38.024   314  8325 D AudioPlayer: Pause Playback at 1068125
08-18 14:10:38.025   314  2148 V AwesomePlayer: reset_l() 
08-18 14:10:38.026   314  2148 V AudioCache: notify(0xb5474580, 8, 0, 0)
08-18 14:10:38.026   314  2148 V AudioCache: ignored
08-18 14:10:38.026   314  2148 V AwesomePlayer: cancelPlayerEvents
08-18 14:10:38.026   314  2148 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-18 14:10:38.026   314  2148 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
,08-18 14:10:38.026   314  2148 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-18 14:10:38.026   314  2148 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-18 14:10:38.026   314  2148 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-18 14:10:38.026   314  8327 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-18 14:10:38.026   314  8327 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-18 14:10:38.026   314  8327 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-18 14:10:38.026   314  8327 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c90 on port 0
08-18 14:10:38.026   314  8327 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-18 14:10:38.026   314  8327 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 0
08-18 14:10:38.026   314  8327 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-18 14:10:38.026   314  8327 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 0
08-18 14:10:38.026   314  8327 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-18 14:10:38.026   314  8327 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 0
08-18 14:10:38.026   314  8327 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-18 14:10:38.026   314  8327 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-18 14:10:38.026   314  8327 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f1f0 on port 1
08-18 14:10:38.026   314  8327 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-18 14:10:38.026   314  8327 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7fb0 on port 1
08-18 14:10:38.026   314  8327 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-18 14:10:38.027   314  8327 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57c11f0 on port 1
08-18 14:10:38.027   314  8327 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-18 14:10:38.027   314  8327 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57c12e0 on port 1
08-18 14:10:38.027   314  8327 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-18 14:10:38.027   314  8327 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-18 14:10:38.027   314  8327 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-18 14:10:38.027   314  8327 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-18 14:10:38.027   314  8327 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-18 14:10:38.028   314  2148 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-18 14:10:38.028   314  2148 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-18 14:10:38.028   314  2148 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-18 14:10:38.029   314  2148 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
,08-18 14:10:38.029   314  2148 D AudioPlayer: AudioPlayer releasing audio source
08-18 14:10:38.029   314  2148 D AudioPlayer: AudioPlayer done releasing audio source
08-18 14:10:38.029   314  2148 V AwesomePlayer: reset_l() 
08-18 14:10:38.029   314  2148 V AwesomePlayer: cancelPlayerEvents
08-18 14:10:38.029   314  2148 V AwesomePlayer: ~AwesomePlayer call
08-18 14:10:38.029   314  2148 V AwesomePlayer: reset_l() 
08-18 14:10:38.029   314  2148 V AwesomePlayer: cancelPlayerEvents
08-18 14:10:38.029  8251  8324 V SoundPool: close(31)
08-18 14:10:38.029  8251  8324 V SoundPool: pointer = 0x9fe5e000, size = 205080, sampleRate = 48000, numChannels = 2
08-18 14:10:38.058  8251  8251 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-18 14:10:38.058  8251  8251 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,08-18 14:10:38.060  8251  8251 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:5843
08-18 14:10:38.062  8180  8180 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-18 14:10:38.065  1820  1820 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-18 14:10:38.071  2161  2161 I ConfigService: onCreate
08-18 14:10:38.072  2161  2161 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
,08-18 14:10:38.075  1820  1820 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,08-18 14:10:38.077  1820  3990 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.gms/shared_prefs/config_removals.xml to backup file /data/data/com.google.android.gms/shared_prefs/config_removals.xml.bak
08-18 14:10:38.078  2161  8329 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/config.db'.
08-18 14:10:38.078  2161  8329 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-18 14:10:38.078  2161  8329 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-18 14:10:38.078  2161  8329 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-18 14:10:38.078  2161  8329 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-18 14:10:38.078  2161  8329 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-18 14:10:38.078  2161  8329 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-18 14:10:38.078  2161  8329 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-18 14:10:38.078  2161  8329 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-18 14:10:38.078  2161  8329 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-18 14:10:38.078  2161  8329 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-18 14:10:38.078  2161  8329 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-18 14:10:38.078  2161  8329 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-18 14:10:38.078  2161  8329 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-18 14:10:38.078  2161  8329 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-18 14:10:38.078  2161  8329 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:36)
08-18 14:10:38.078  2161  8329 E SQLiteDatabase: 	at com.google.android.gms.config.h.run(SourceFile:121)
08-18 14:10:38.078  2161  8329 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
08-18 14:10:38.078  2161  8329 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
08-18 14:10:38.078  2161  8329 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-18 14:10:38.078  2161  8329 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-18 14:10:38.078  2161  8329 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-18 14:10:38.078  2161  8329 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-18 14:10:38.078  2161  8329 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-18 14:10:38.078  2161  8329 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-18 14:10:38.078  2161  8329 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-18 14:10:38.078  2161  8329 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-18 14:10:38.078  2161  8329 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-18 14:10:38.078  2161  8329 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-18 14:10:38.078  2161  8329 E SQLiteOpenHelper: 	at android.app.ContextIm,pl.openOrCreateDatabase(ContextImpl.java:1213)
08-18 14:10:38.078  2161  8329 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-18 14:10:38.078  2161  8329 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-18 14:10:38.078  2161  8329 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-18 14:10:38.078  2161  8329 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:36)
08-18 14:10:38.078  2161  8329 E SQLiteOpenHelper: 	at com.google.android.gms.config.h.run(SourceFile:121)
08-18 14:10:38.078  2161  8329 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
08-18 14:10:38.082  2161  8329 W SQLiteOpenHelper: Opened config.db in read-only mode
08-18 14:10:38.082  2161  2161 I ConfigService: onBind returning update interface
08-18 14:10:38.083  2161  2161 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-18 14:10:38.083  2161  2161 I ConfigService: onBind returning config service
08-18 14:10:38.087  2161  2161 I ConfigService: onDestroy
08-18 14:10:38.089  1820  8330 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,08-18 14:10:38.100  7137  7137 E SQLiteLog: (3850) statement aborts at 24: [INSERT INTO exclude_apps(package) VALUES (?)] disk I/O error
08-18 14:10:38.101  7137  7137 E SQLiteDatabase: Error inserting package=com.test.thalitest
08-18 14:10:38.101  7137  7137 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-18 14:10:38.101  7137  7137 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
08-18 14:10:38.101  7137  7137 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:787)
08-18 14:10:38.101  7137  7137 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:926)
08-18 14:10:38.101  7137  7137 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
08-18 14:10:38.101  7137  7137 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1572)
08-18 14:10:38.101  7137  7137 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1442)
08-18 14:10:38.101  7137  7137 E SQLiteDatabase: 	at com.lge.appbox.databases.AppBoxContentProvider.insert(AppBoxContentProvider.java:220)
08-18 14:10:38.101  7137  7137 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:238)
08-18 14:10:38.101  7137  7137 E SQLiteDatabase: 	at android.content.ContentResolver.insert(ContentResolver.java:1223)
08-18 14:10:38.101  7137  7137 E SQLiteDatabase: 	at com.lge.appbox.manager.PreloadListManagerHelper.addExcludeApp(PreloadListManagerHelper.java:134)
08-18 14:10:38.101  7137  7137 E SQLiteDatabase: 	at com.lge.appbox.manager.PreloadListManagerHelper.addExcludeAppInternal(PreloadListManagerHelper.java:115)
08-18 14:10:38.101  7137  7137 E SQLiteDatabase: 	at com.lge.appbox.manager.PreloadListManagerHelper.onRemoveAppEvent(PreloadListManagerHelper.java:100)
08-18 14:10:38.101  7137  7137 E SQLiteDatabase: 	at com.lge.appbox.manager.PreloadListManagerHelper.updateExDb(PreloadListManagerHelper.java:65)
08-18 14:10:38.101  7137  7137 E SQLiteDatabase: 	at com.lge.appbox.manager.PreloadListManagerHelper.onReceive(PreloadListManagerHelper.java:46)
08-18 14:10:38.101  7137  7137 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2586)
08-18 14:10:38.101  7137  7137 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:148)
08-18 14:10:38.101  7137  7137 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1360)
08-18 14:10:38.101  7137  7137 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-18 14:10:38.101  7137  7137 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-18 14:10:38.101  7137  7137 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-18 14:10:38.101  7137  7137 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-18 14:10:38.101  7137  7137 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-18 14:10:38.101  7137  7137 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-18 14:10:38.101  7137  7137 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)

```
