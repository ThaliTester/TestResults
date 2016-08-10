#### Test 807613745de8823_thali02_LGE-LG-D855 Logs


```
--------- beginning of system
08-10 13:32:34.181  1031  1031 D PowerManagerServiceEx: releaseWakeLockInternal: lock=942226032 [*alarm*], flags=0x0
,--------- beginning of main
08-10 13:32:40.012  6714  6714 D AndroidRuntime: 
08-10 13:32:40.012  6714  6714 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-10 13:32:40.017  6714  6714 D AndroidRuntime: CheckJNI is OFF
08-10 13:32:40.139  6714  6714 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-10 13:32:40.144  1031  1578 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-10 13:32:40.154  1945  3971 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-10 13:32:40.157  1031  1578 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-10 13:32:40.158  1031  1578 D ActivityManager: setTaskToReturnTo : TaskRecord{2f622711 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-10 13:32:40.158  1031  1578 D ActivityManager: setTaskToReturnTo : TaskRecord{2f622711 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-10 13:32:40.159  1031  1578 D WindowStateEx: AppWindowTokenEx init.. 
08-10 13:32:40.160   337   361 E GBMv2   : DFP En is all cleared set to be enabled
08-10 13:32:40.179  1031  1578 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6729 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-10 13:32:40.180  6714  6714 D AndroidRuntime: Shutting down VM
08-10 13:32:40.236  1945  3971 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-10 13:32:40.236  1945  3971 D SplitWindowPolicy: topRunningActivity=ActivityInfo{10dde1c6 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-10 13:32:40.237  1945  1960 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-10 13:32:40.237  1945  1960 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2e67a587 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-10 13:32:40.310  6729  6729 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-10 13:32:40.411  6729  6729 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-10 13:32:40.422  6729  6729 I LibraryLoader: Loading: webviewchromium
,08-10 13:32:40.426  6729  6729 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 7639-7643)
08-10 13:32:40.426  6729  6729 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-10 13:32:40.443  6729  6729 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {866a964}
,08-10 13:32:40.444  6729  6729 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-10 13:32:40.445  6729  6729 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-10 13:32:40.456  6729  6729 I BrowserStartupController: Initializing chromium process, renderers=0
,08-10 13:32:40.457  6729  6729 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-10 13:32:40.468   310  2199 V AudioPolicyService: registerClient() client 0xb1019320, uid 10118
,08-10 13:32:40.469  6729  6729 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-10 13:32:40.469  6729  6729 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-10 13:32:40.470  6729  6729 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-10 13:32:40.476  1031  1096 D BluetoothManagerService: Message: 20
08-10 13:32:40.476  1031  1096 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@979e313:true
08-10 13:32:40.485  6729  6729 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-10 13:32:40.485  6729  6729 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-10 13:32:40.485  6729  6729 I Adreno-EGL: Build Date: 12/12/14 금
08-10 13:32:40.485  6729  6729 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-10 13:32:40.485  6729  6729 I Adreno-EGL: Remote Branch: 
08-10 13:32:40.485  6729  6729 I Adreno-EGL: Local Patches: 
08-10 13:32:40.485  6729  6729 I Adreno-EGL: Reconstruct Branch: 
,08-10 13:32:40.581  6729  6769 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-10 13:32:40.584  6729  6729 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-10 13:32:40.604  6729  6729 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-10 13:32:40.609  6729  6729 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-10 13:32:40.612  6729  6729 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-10 13:32:40.616  6729  6729 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-10 13:32:40.616  6729  6729 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,08-10 13:32:40.631  6729  6729 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-10 13:32:40.638  6729  6729 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-10 13:32:40.638  6729  6729 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-10 13:32:40.671  6729  6784 D OpenGLRenderer: Render dirty regions requested: true
08-10 13:32:40.671  6729  6784 I OpenGLRenderer: Initialized EGL, version 1.4
08-10 13:32:40.676  6729  6784 D OpenGLRenderer: Enabling debug mode 0
,08-10 13:32:40.687  6729  6729 D Atlas   : Validating map...
08-10 13:32:40.692  1031  1773 D SplitWindow: check instance of lgWin Window{1d002375 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-10 13:32:40.734  6729  6782 D LgDataFeature: LgDataFeature() Constructor: none
08-10 13:32:40.734  6729  6782 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-10 13:32:40.847  1031  1097 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +614ms (total +686ms)
,08-10 13:32:40.847  1031  1097 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1cd80076 u0 com.test.thalitest/.MainActivity t6} time:308065
08-10 13:32:40.855  6729  6729 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2bda4f83 time:308073
08-10 13:32:40.938  6729  6729 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-10 13:32:40.991  6729  6729 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-10 13:32:40.991  6729  6729 I chromium: 
,08-10 13:32:41.116  6729  6796 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435153408
,08-10 13:32:41.135  6729  6796 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-10 13:32:41.135  6729  6796 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-10 13:32:41.135  6729  6796 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-10 13:32:41.135  6729  6796 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-10 13:32:41.135  6729  6796 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-10 13:32:41.135  6729  6796 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c778cd7 added. We now have 1 listener(s)
,08-10 13:32:41.142  1031  1047 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 13:32:41.145  6729  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-10 13:32:41.148  6729  6796 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-10 13:32:41.149  6729  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-10 13:32:41.149  6729  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-10 13:32:41.158  6729  6796 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-10 13:32:41.158  6729  6796 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-10 13:32:41.158  6729  6796 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-10 13:32:41.158  6729  6796 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-10 13:32:41.158  6729  6796 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-10 13:32:41.158  6729  6796 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-10 13:32:41.158  6729  6796 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-10 13:32:41.158  6729  6796 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-10 13:32:41.158  6729  6796 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-10 13:32:41.158  6729  6796 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-10 13:32:41.158  6729  6796 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-10 13:32:41.158  6729  6796 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-10 13:32:41.158  6729  6796 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-10 13:32:41.158  6729  6796 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-10 13:32:41.158  6729  6796 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27f39fe2 added. We now have 1 listener(s)
08-10 13:32:41.158  6729  6796 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 13:32:41.165  1031  1544 D WifiService: New client listening to asynchronous messages
,08-10 13:32:41.170  6729  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-10 13:32:41.170  6729  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-10 13:32:41.172  6729  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-10 13:32:41.173  6729  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-10 13:32:41.173  6729  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-10 13:32:41.177  6729  6796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 13:32:41.178  1031  1944 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 13:32:41.180  6729  6796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
,08-10 13:32:41.196  6729  6796 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-10 13:32:41.197  6729  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 13:32:41.197  6729  6796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 13:32:41.197  6729  6796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 13:32:41.197  6729  6796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 13:32:41.197  6729  6796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 13:32:41.197  6729  6796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 13:32:41.197  6729  6796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 13:32:41.197  6729  6796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-10 13:32:41.197  6729  6796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-10 13:32:41.197  6729  6796 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-10 13:32:41.199  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 13:32:41.201  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 13:32:41.207  6729  6796 I io.jxcore.node.LifeCycleMonitor: start: OK
08-10 13:32:41.244  6729  6782 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-10 13:32:41.244  6729  6782 I chromium: 
,08-10 13:32:41.298  6729  6729 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-10 13:32:41.563   337   363 E GBMv2   : DFP En is all cleared set to be enabled
08-10 13:32:41.564   337   363 E GBMv2   : Set value is all cleared set the max
08-10 13:32:41.564   337   363 I GBMv2   : DFP Enabled. Ignore VFP set
,08-10 13:32:42.135  6729  6799 W jxcore-log: Initializing JXcore engine
08-10 13:32:42.135  6729  6799 W jxcore-log: JXcore engine is ready
,08-10 13:32:42.162  6799  6799 W Thread-767: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[8354]" dev="sockfs" ino=8354 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-10 13:32:42.162  6799  6799 W Thread-767: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,08-10 13:32:42.162  6799  6799 W Thread-767: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[10304]" dev="sockfs" ino=10304 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-10 13:32:42.162  6799  6799 W Thread-767: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-10 13:32:42.162  6799  6799 W Thread-767: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[31959]" dev="sockfs" ino=31959 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-10 13:32:42.191  6729  6799 W jxcore-log: Starting JXcore engine
,08-10 13:32:42.269  6729  6799 W jxcore-log: Platform android
08-10 13:32:42.269  6729  6799 W jxcore-log: 
08-10 13:32:42.269  6729  6799 W jxcore-log: Process ARCH arm
08-10 13:32:42.269  6729  6799 W jxcore-log: 
,08-10 13:32:42.648  6729  6799 I jxcore-log: JXcore Cordova bridge is ready!
08-10 13:32:42.648  6729  6799 I jxcore-log: 
08-10 13:32:42.649  6729  6799 W jxcore-log: JXcore engine is started
,08-10 13:32:42.661  6729  6796 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-10 13:32:42.664  6729  6729 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-10 13:32:58.258  6729  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-10 13:32:58.258  6729  6799 I jxcore-log: 
,08-10 13:32:58.261  6729  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-10 13:32:58.261  6729  6799 I jxcore-log: 
08-10 13:32:58.265  6729  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 13:32:58.265  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 13:32:58.265  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 13:32:58.265  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 13:32:58.265  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 13:32:58.265  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 13:32:58.265  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 13:32:58.265  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-10 13:32:58.268  6729  6799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-10 13:32:58.271  6729  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-10 13:32:58.271  6729  6799 I jxcore-log: 
,08-10 13:32:58.273  6729  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-10 13:32:58.273  6729  6799 I jxcore-log: 
08-10 13:32:58.608  6729  6799 I jxcore-log: Running unit tests
08-10 13:32:58.608  6729  6799 I jxcore-log: 
08-10 13:32:58.609  6729  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-10 13:32:58.609  6729  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@297ff754 added. We now have 2 listener(s)
08-10 13:32:58.610  1031  2006 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-10 13:32:58.611  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-10 13:32:58.611  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-10 13:32:58.611  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-10 13:32:58.611  6729  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 13:32:58.611  6729  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7d016fd added. We now have 2 listener(s)
08-10 13:32:58.611  6729  6799 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 13:32:58.613  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-10 13:32:58.617  6729  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 13:32:58.622  6729  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 13:32:58.622  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 13:32:58.622  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 13:32:58.622  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 13:32:58.622  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 13:32:58.622  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 13:32:58.622  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 13:32:58.622  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-10 13:32:58.623  6729  6799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-10 13:32:58.623  6729  6799 D io.jxcore.node.ConnectivityMonitor: start: OK
08-10 13:32:58.624  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 13:32:58.625  6729  6799 D ExecuteNativeTests: Running unit tests
08-10 13:32:58.626  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 13:32:58.702  6729  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-10 13:32:58.702  6729  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eb633 added. We now have 3 listener(s)
08-10 13:32:58.703  1031  1774 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-10 13:32:58.706  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-10 13:32:58.706  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-10 13:32:58.706  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-10 13:32:58.706  6729  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 13:32:58.707  6729  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20394df0 added. We now have 3 listener(s)
08-10 13:32:58.707  6729  6799 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 13:32:58.707  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-10 13:32:58.712  6729  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 13:32:58.715  6729  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 13:32:58.715  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 13:32:58.715  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 13:32:58.715  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 13:32:58.715  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 13:32:58.715  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 13:32:58.715  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 13:32:58.715  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-10 13:32:58.719  6729  6799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-10 13:32:58.719  6729  6799 D io.jxcore.node.ConnectivityMonitor: start: OK
08-10 13:32:58.722  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 13:32:58.722  6729  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-10 13:32:58.724  6729  6799 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-10 13:32:58.724  6729  6799 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-10 13:32:58.724  6729  6799 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-10 13:32:58.726  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 13:32:58.727  6729  6799 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-10 13:32:58.728  6729  6799 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-10 13:32:58.728  6729  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-10 13:32:58.728  6729  6799 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-10 13:32:58.728  6729  6799 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-10 13:32:58.728  6729  6799 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-10 13:32:58.729  6729  6799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 13:32:58.730  6729  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 13:32:58.730  6729  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-10 13:32:58.732  6729  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-10 13:32:58.732  6729  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 13:32:58.733  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-10 13:32:58.733  6729  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-10 13:32:58.733  6729  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eb633 removed from the list
08-10 13:32:58.733  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 13:32:58.734  6729  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20394df0 removed from the list
08-10 13:32:58.734  6729  6799 D io.jxcore.node.ConnectivityMonitor: stop
08-10 13:32:58.734  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 13:32:58.735  6729  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 13:32:58.735  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 13:32:58.736  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 13:32:58.736  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 13:32:58.736  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 13:32:58.736  6729  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20394df0 not in the list
08-10 13:32:58.738  6729  6799 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-10 13:32:58.739  6729  6799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 13:32:58.739  6729  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 13:32:58.739  6729  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 13:32:58.739  6729  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 13:32:58.739  6729  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 13:32:58.740  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 13:32:58.740  6729  6799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eb633 not in the list
08-10 13:32:58.741  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-10 13:32:58.741  6729  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20394df0 not in the list
08-10 13:32:58.741  6729  6799 D io.jxcore.node.ConnectivityMonitor: stop
08-10 13:32:58.741  6729  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 13:32:58.741  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 13:32:58.741  6729  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 13:32:58.741  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-10 13:32:58.744  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 13:32:58.744  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 13:32:58.744  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-10 13:32:58.744  6729  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20394df0 not in the list
08-10 13:32:58.761  6729  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-10 13:32:58.761  6729  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-10 13:32:58.761  6729  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-10 13:32:58.761  6729  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-10 13:32:58.761  6729  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-10 13:32:58.761  6729  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-10 13:32:58.761  6729  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-10 13:32:58.761  6729  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-10 13:32:58.762  6729  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-10 13:32:58.763  6729  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-10 13:32:58.763  6729  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-10 13:32:58.763  6729  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-10 13:32:58.763  6729  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-10 13:32:58.763  6729  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-10 13:32:58.763  6729  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-10 13:32:58.763  6729  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-10 13:32:58.763  6729  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-10 13:32:58.763  6729  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-10 13:32:58.763  6729  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-10 13:32:58.763  6729  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-10 13:32:58.763  6729  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-10 13:32:58.763  6729  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-10 13:32:58.763  6729  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-10 13:32:58.763  6729  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-10 13:32:58.763  6729  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-10 13:32:58.763  6729  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-10 13:32:58.763  6729  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-10 13:32:58.763  6729  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no pe,er name> 36:2610:2610:2610:2610:2610]
08-10 13:32:58.763  6729  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-10 13:32:58.764  6729  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-10 13:32:58.764  6729  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-10 13:32:58.764  6729  6799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 13:32:58.764  6729  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 13:32:58.764  6729  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 13:32:58.765  6729  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 13:32:58.765  6729  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 13:32:58.765  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 13:32:58.765  6729  6799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eb633 not in the list
08-10 13:32:58.765  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 13:32:58.765  6729  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20394df0 not in the list
08-10 13:32:58.765  6729  6799 D io.jxcore.node.ConnectivityMonitor: stop
08-10 13:32:58.765  6729  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 13:32:58.765  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 13:32:58.765  6729  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 13:32:58.765  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 13:32:58.767  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 13:32:58.767  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 13:32:58.767  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 13:32:58.767  6729  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20394df0 not in the list
08-10 13:32:58.768  6729  6799 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-10 13:32:58.769  6729  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 13:32:58.772  6729  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 13:32:58.772  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 13:32:58.772  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 13:32:58.772  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 13:32:58.772  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 13:32:58.772  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22,:99:3e
08-10 13:32:58.772  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 13:32:58.772  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-10 13:32:58.774  6729  6799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-10 13:32:58.774  6729  6799 D io.jxcore.node.ConnectivityMonitor: start: OK
08-10 13:32:58.775  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 13:32:58.777  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 13:32:58.777  6729  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-10 13:32:58.778  6729  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-10 13:32:58.778  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-10 13:32:58.778  6729  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 13:32:58.778  6729  6799 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-10 13:32:58.781  6729  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-10 13:32:58.782  1031  2016 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 13:32:58.790  6729  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-10 13:32:58.801  6729  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-10 13:32:58.804  6729  6799 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
,08-10 13:32:58.806  6729  6799 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-10 13:32:58.806  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-10 13:32:58.808  6729  6799 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-10 13:32:58.808  6729  6799 I io.jxcore.node.ConnectionHelper: start: OK
08-10 13:33:00.068  1605  1605 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-10 13:33:00.068  1605  1605 I KeyguardUpdateMonitor: called onTimeUpdated()
08-10 13:33:00.068  1605  1605 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-10 13:33:00.069  1605  1605 I [SystemUI]Clock: called onTimeUpdated()
,08-10 13:33:00.081  1605  1605 I LgeClockWidgetControlView: called onTimeUpdated()
08-10 13:33:00.081  1605  1605 I [SystemUI]DateView: called onTimeUpdated()
08-10 13:33:00.084  1605  1605 I [SystemUI]DateView: called onTimeUpdated()
08-10 13:33:00.085  1605  1605 D KeyguardUpdateMonitor: handleTimeUpdate
08-10 13:33:03.820  6729  6799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 13:33:03.820  6729  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 13:33:03.820  6729  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-10 13:33:03.826  6729  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 13:33:03.826  6729  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 13:33:03.826  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-10 13:33:03.826  6729  6799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eb633 not in the list
,08-10 13:33:03.826  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 13:33:03.826  6729  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20394df0 not in the list
08-10 13:33:03.826  6729  6799 D io.jxcore.node.ConnectivityMonitor: stop
08-10 13:33:03.826  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 13:33:08.143  1031  3580 I LocationManagerService: remove 2b36ab83
08-10 13:33:08.144  1031  3580 D LocationManagerService: provider request: passive ProviderRequest[ON interval=0]
08-10 13:33:08.145  1031  3580 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-10 13:33:08.146  1031  3580 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
08-10 13:33:08.147  1031  3580 D LocationManagerService: getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
08-10 13:33:08.148  1031  3580 D LocationManagerService: getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,08-10 13:33:08.828  6729  6799 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-10 13:33:08.840  6729  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 13:33:08.846  6729  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 13:33:08.846  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 13:33:08.846  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 13:33:08.846  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 13:33:08.846  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 13:33:08.846  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 13:33:08.846  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 13:33:08.846  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-10 13:33:08.850  6729  6799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-10 13:33:08.851  6729  6799 D io.jxcore.node.ConnectivityMonitor: start: OK
08-10 13:33:08.853  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 13:33:08.855  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 13:33:08.855  6729  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-10 13:33:08.855  6729  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-10 13:33:08.855  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-10 13:33:08.855  6729  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 13:33:08.855  6729  6799 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-10 13:33:09.012  1031  1890 I art     : Explicit concurrent mark sweep GC freed 27893(1321KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/64MB, paused 2.807ms total 144.102ms
,08-10 13:33:09.018  6729  6799 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-10 13:33:09.018  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-10 13:33:09.020  6729  6799 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-10 13:33:09.020  6729  6799 I io.jxcore.node.ConnectionHelper: start: OK
08-10 13:33:09.021  6729  6799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 13:33:09.022  6729  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 13:33:09.022  6729  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 13:33:09.022  6729  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 13:33:09.022  6729  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 13:33:09.022  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-10 13:33:09.022  6729  6799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eb633 not in the list
08-10 13:33:09.022  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 13:33:09.022  6729  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20394df0 not in the list
08-10 13:33:09.022  6729  6799 D io.jxcore.node.ConnectivityMonitor: stop
08-10 13:33:09.023  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 13:33:09.023  6729  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 13:33:09.023  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 13:33:09.024  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 13:33:09.024  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-10 13:33:09.027  6729  6799 D BluetoothLeScanner: could not find callback wrapper
08-10 13:33:09.027  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-10 13:33:09.027  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 13:33:09.027  6729  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20394df0 not in the list
08-10 13:33:09.028  6729  6799 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-10 13:33:09.030  6729  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 13:33:09.032  6729  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 13:33:09.032  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 13:33:09.032  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 13:33:09.032  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 13:33:09.032  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 13:33:09.032  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 13:33:09.032  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 13:33:09.032  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-10 13:33:09.033  6729  6799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-10 13:33:09.033  6729  6799 D io.jxcore.node.ConnectivityMonitor: start: OK
08-10 13:33:09.035  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 13:33:09.036  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 13:33:09.038  6729  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-10 13:33:09.038  6729  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-10 13:33:09.038  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-10 13:33:09.038  6729  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 13:33:09.038  6729  6799 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-10 13:33:09.041  6729  6799 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-10 13:33:09.042  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-10 13:33:09.052  6729  6799 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-10 13:33:09.052  6729  6799 I io.jxcore.node.ConnectionHelper: start: OK
,08-10 13:33:14.053  6729  6799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 13:33:14.053  6729  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 13:33:14.053  6729  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-10 13:33:18.693  1031  1377 D PowerManagerServiceEx: acquireWakeLockInternal: lock=942226032, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1031
,08-10 13:33:18.739  2586  2586 D [Concierge]Service: onStartCommand(). Type : 9
,08-10 13:33:18.770  1031  1031 D PowerManagerServiceEx: releaseWakeLockInternal: lock=942226032 [*alarm*], flags=0x0
,08-10 13:33:19.061  6729  6799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 13:33:19.061  6729  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 13:33:19.061  6729  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-10 13:33:19.063  6729  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 13:33:19.063  6729  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 13:33:19.063  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-10 13:33:19.063  6729  6799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eb633 not in the list
08-10 13:33:19.063  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 13:33:19.063  6729  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20394df0 not in the list
08-10 13:33:19.063  6729  6799 D io.jxcore.node.ConnectivityMonitor: stop
08-10 13:33:19.063  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 13:33:19.064  6729  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 13:33:19.064  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 13:33:19.064  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 13:33:19.064  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 13:33:19.064  6729  6799 D BluetoothLeScanner: could not find callback wrapper
08-10 13:33:19.065  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-10 13:33:19.065  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 13:33:19.065  6729  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20394df0 not in the list
08-10 13:33:19.065  6729  6799 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-10 13:33:19.065  6729  6799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 13:33:19.065  6729  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 13:33:19.065  6729  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 13:33:19.066  6729  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 13:33:19.066  6729  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 13:33:19.066  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 13:33:19.066  6729  6799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eb633 not in the list
08-10 13:33:19.066  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 13:33:19.066  6729  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20394df0 not in the list
08-10 13:33:19.066  6729  6799 D io.jxcore.node.ConnectivityMonitor: stop
08-10 13:33:19.066  6729  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 13:33:19.066  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 13:33:19.066  6729  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 13:33:19.066  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 13:33:19.066  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 13:33:19.067  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 13:33:19.067  6729  6799 D BluetoothLeScanner: could not find callback wrapper
08-10 13:33:19.067  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-10 13:33:19.067  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 13:33:19.067  6729  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20394df0 not in the list
08-10 13:33:19.068  6729  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-10 13:33:19.068  6729  6799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 13:33:19.068  6729  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 13:33:19.068  6729  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 13:33:19.069  6729  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 13:33:19.069  6729  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 13:33:19.069  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 13:33:19.069  6729  6799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eb633 not in the list
08-10 13:33:19.069  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 13:33:19.069  6729  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20394df0 not in the list
08-10 13:33:19.069  6729  6799 D io.jxcore.node.ConnectivityMonitor: stop
08-10 13:33:19.069  6729  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 13:33:19.069  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 13:33:19.069  6729  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 13:33:19.070  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 13:33:19.071  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 13:33:19.071  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 13:33:19.071  6729  6799 D BluetoothLeScanner: could not find callback wrapper
08-10 13:33:19.071  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-10 13:33:19.071  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 13:33:19.071  6729  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20394df0 not in the list
08-10 13:33:19.072  6729  6799 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-10 13:33:19.072  6729  6799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 13:33:19.072  6729  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 13:33:19.072  6729  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 13:33:19.073  6729  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 13:33:19.073  6729  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 13:33:19.073  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 13:33:19.073  6729  6799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eb633 not in the list
08-10 13:33:19.073  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 13:33:19.073  6729  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20394df0 not in the list
08-10 13:33:19.073  6729  6799 D io.jxcore.node.ConnectivityMonitor: stop
08-10 13:33:19.073  6729  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 13:33:19.073  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 13:33:19.073  6729  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 13:33:19.073  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-10 13:33:19.077  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 13:33:19.078  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 13:33:19.078  6729  6799 D BluetoothLeScanner: could not find callback wrapper
08-10 13:33:19.078  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-10 13:33:19.078  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 13:33:19.078  6729  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20394df0 not in the list
08-10 13:33:19.079  6729  6799 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-10 13:33:19.079  6729  6799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 13:33:19.079  6729  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 13:33:19.079  6729  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 13:33:19.079  6729  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 13:33:19.079  6729  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 13:33:19.079  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 13:33:19.079  6729  6799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eb633 not in the list
08-10 13:33:19.079  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 13:33:19.079  6729  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20394df0 not in the list
08-10 13:33:19.079  6729  6799 D io.jxcore.node.ConnectivityMonitor: stop
08-10 13:33:19.079  6729  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 13:33:19.079  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 13:33:19.079  6729  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 13:33:19.079  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 13:33:19.080  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 13:33:19.080  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 13:33:19.080  6729  6799 D BluetoothLeScanner: could not find callback wrapper
08-10 13:33:19.080  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-10 13:33:19.080  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 13:33:19.080  6729  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20394df0 not in the list
08-10 13:33:19.081  6729  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-10 13:33:19.083  6729  6799 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-10 13:33:19.083  6729  6799 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-10 13:33:19.083  6729  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-10 13:33:19.083  6729  6799 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-10 13:33:19.083  6729  6799 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-10 13:33:19.083  6729  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-10 13:33:19.083  6729  6799 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-10 13:33:19.083  6729  6799 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-10 13:33:19.083  6729  6799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 13:33:19.083  6729  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 13:33:19.083  6729  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 13:33:19.084  6729  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 13:33:19.084  6729  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 13:33:19.084  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 13:33:19.084  6729  6799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eb633 not in the list
08-10 13:33:19.084  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 13:33:19.084  6729  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20394df0 not in the list
08-10 13:33:19.084  6729  6799 D io.jxcore.node.ConnectivityMonitor: stop
08-10 13:33:19.084  6729  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 13:33:19.084  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 13:33:19.084  6729  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 13:33:19.084  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 13:33:19.085  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 13:33:19.085  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-10 13:33:19.089  6729  6799 D BluetoothLeScanner: could not find callback wrapper
08-10 13:33:19.089  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-10 13:33:19.089  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 13:33:19.089  6729  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20394df0 not in the list
08-10 13:33:19.090  6729  6799 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-10 13:33:19.090  6729  6799 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-10 13:33:19.090  6729  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-10 13:33:19.094  6729  6799 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-10 13:33:19.094  6729  6799 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-10 13:33:19.094  6729  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-10 13:33:19.094  6729  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-10 13:33:19.094  6729  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-10 13:33:19.094  6729  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-10 13:33:19.094  6729  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-10 13:33:19.094  6729  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-10 13:33:19.094  6729  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-10 13:33:19.094  6729  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-10 13:33:19.094  6729  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-10 13:33:19.094  6729  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-10 13:33:19.094  6729  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-10 13:33:19.094  6729  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-10 13:33:19.094  6729  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-10 13:33:19.094  6729  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-10 13:33:19.094  6729  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-10 13:33:19.094  6729  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-10 13:33:19.094  6729  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-10 13:33:19.094  6729  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-10 13:33:19.094  6729  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-10 13:33:19.094  6729  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-10 13:33:19.095  6729  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-10 13:33:19.095  6729  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-10 13:33:19.095  6729  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-10 13:33:19.095  6729  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-10 13:33:19.095  6729  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-10 13:33:19.095  6729  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-10 13:33:19.095  6729  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-10 13:33:19.095  6729  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-10 13:33:19.095  6729  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-10 13:33:19.095  6729  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-10 13:33:19.095  6729  6799 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-10 13:33:19.095  6729  6799 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-10 13:33:19.095  6729  6799 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-10 13:33:19.095  6729  6799 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-10 13:33:19.095  6729  6799 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-10 13:33:19.095  6729  6799 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-10 13:33:19.095  6729  6799 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-10 13:33:19.095  6729  6799 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-10 13:33:19.095  6729  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-10 13:33:19.097  6729  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-10 13:33:19.098  6729  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-10 13:33:19.098  6729  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-10 13:33:19.098  6729  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-10 13:33:19.098  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-10 13:33:19.098  6729  6799 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
,08-10 13:33:19.099  6729  6799 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-10 13:33:19.099  6729  6799 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-10 13:33:19.099  6729  6799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 13:33:19.099  6729  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 13:33:19.099  6729  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-10 13:33:19.103  6729  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 13:33:19.103  6729  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 13:33:19.103  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 13:33:19.103  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-10 13:33:19.103  6729  6799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eb633 not in the list
08-10 13:33:19.103  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 13:33:19.103  6729  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20394df0 not in the list
08-10 13:33:19.103  6729  6799 D io.jxcore.node.ConnectivityMonitor: stop
08-10 13:33:19.103  6729  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 13:33:19.103  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 13:33:19.104  6729  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 13:33:19.104  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 13:33:19.104  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 13:33:19.104  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 13:33:19.105  6729  6799 D BluetoothLeScanner: could not find callback wrapper
08-10 13:33:19.105  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-10 13:33:19.105  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 13:33:19.105  6729  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20394df0 not in the list
08-10 13:33:19.105  6729  6799 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-10 13:33:19.106  6729  6799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 13:33:19.106  6729  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 13:33:19.106  6729  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 13:33:19.106  6729  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 13:33:19.106  6729  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 13:33:19.106  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 13:33:19.106  6729  6799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eb633 not in the list
08-10 13:33:19.106  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 13:33:19.106  6729  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20394df0 not in the list
08-10 13:33:19.106  6729  6799 D io.jxcore.node.ConnectivityMonitor: stop
08-10 13:33:19.106  6729  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 13:33:19.106  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 13:33:19.106  6729  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 13:33:19.106  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 13:33:19.107  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 13:33:19.107  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 13:33:19.107  6729  6799 D BluetoothLeScanner: could not find callback wrapper
08-10 13:33:19.107  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-10 13:33:19.107  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 13:33:19.107  6729  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20394df0 not in the list
08-10 13:33:19.108  6729  6799 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-10 13:33:19.108  6729  6799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 13:33:19.108  6729  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 13:33:19.108  6729  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 13:33:19.108  6729  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 13:33:19.108  6729  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 13:33:19.108  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 13:33:19.108  6729  6799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eb633 not in the list
08-10 13:33:19.108  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 13:33:19.108  6729  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20394df0 not in the list
08-10 13:33:19.108  6729  6799 D io.jxcore.node.ConnectivityMonitor: stop
08-10 13:33:19.108  6729  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 13:33:19.108  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 13:33:19.108  6729  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 13:33:19.108  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 13:33:19.109  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 13:33:19.109  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 13:33:19.110  6729  6799 D BluetoothLeScanner: could not find callback wrapper
08-10 13:33:19.110  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-10 13:33:19.110  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 13:33:19.110  6729  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20394df0 not in the list
08-10 13:33:19.110  6729  6799 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-10 13:33:19.110  6729  6799 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-10 13:33:19.110  6729  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-10 13:33:19.110  6729  6799 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-10 13:33:19.110  6729  6799 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-10 13:33:19.110  6729  6799 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-10 13:33:19.110  6729  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-10 13:33:19.111  6729  6799 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-10 13:33:19.111  6729  6799 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-10 13:33:19.111  6729  6799 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-10 13:33:19.111  6729  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-10 13:33:19.111  6729  6799 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-10 13:33:19.111  6729  6799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 13:33:19.111  6729  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 13:33:19.111  6729  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-10 13:33:19.112  6729  6811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 831
,08-10 13:33:19.117  6729  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 13:33:19.117  6729  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 13:33:19.117  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 13:33:19.117  6729  6799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eb633 not in the list
08-10 13:33:19.117  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 13:33:19.117  6729  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20394df0 not in the list
08-10 13:33:19.117  6729  6799 D io.jxcore.node.ConnectivityMonitor: stop
08-10 13:33:19.117  6729  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 13:33:19.117  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 13:33:19.117  6729  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 13:33:19.117  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 13:33:19.118  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 13:33:19.118  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 13:33:19.118  6729  6799 D BluetoothLeScanner: could not find callback wrapper
08-10 13:33:19.118  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-10 13:33:19.118  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 13:33:19.118  6729  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20394df0 not in the list
08-10 13:33:19.119  6729  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 13:33:19.119  6729  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 13:33:19.119  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 13:33:19.119  6729  6799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eb633 not in the list
08-10 13:33:19.119  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 13:33:19.119  6729  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20394df0 not in the list
08-10 13:33:19.119  6729  6799 D io.jxcore.node.ConnectivityMonitor: stop
08-10 13:33:19.119  6729  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 13:33:19.119  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 13:33:19.124  6729  6810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 831)
08-10 13:33:19.124  6729  6810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 831)
08-10 13:33:24.120  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 13:33:24.,120  6729  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20394df0 not in the list
08-10 13:33:24.120  6729  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 13:33:24.120  6729  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 13:33:24.121  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 13:33:24.121  6729  6799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eb633 not in the list
08-10 13:33:24.121  6729  6799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 13:33:24.121  6729  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 13:33:24.121  6729  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 13:33:24.133  6729  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 13:33:24.133  6729  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 13:33:24.133  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 13:33:24.133  6729  6799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eb633 not in the list
08-10 13:33:24.133  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 13:33:24.133  6729  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20394df0 not in the list
08-10 13:33:24.133  6729  6799 D io.jxcore.node.ConnectivityMonitor: stop
08-10 13:33:24.133  6729  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 13:33:24.134  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 13:33:24.134  6729  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 13:33:24.134  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 13:33:24.135  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 13:33:24.135  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 13:33:24.136  6729  6799 D BluetoothLeScanner: could not find callback wrapper
08-10 13:33:24.136  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-10 13:33:24.136  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 13:33:24.137  6729  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20394df0 not in the list
08-10 13:33:24.139  6729  6799 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-10 13:33:24.139  6729  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-10 13:33:24.143  6729  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-10 13:33:24.144  6729  6799 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-10 13:33:24.144  6729  6799 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-10 13:33:24.144  6729  6729 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-10 13:33:24.145  6729  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-10 13:33:24.145  6729  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-10 13:33:24.146  6729  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 13:33:24.146  6729  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-10 13:33:24.146  6729  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-10 13:33:24.146  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-10 13:33:24.147  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 13:33:24.147  6729  6799 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-10 13:33:24.149  6729  6729 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-10 13:33:24.150  6729  6799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eb633 not in the list
08-10 13:33:24.150  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 13:33:24.150  6729  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-10 13:33:24.151  6729  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,08-10 13:33:24.153  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-10 13:33:24.153  6729  6799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-10 13:33:24.153  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-10 13:33:24.154  6729  6729 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-10 13:33:24.155  6729  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-10 13:33:24.157  6729  6799 D BluetoothLeScanner: could not find callback wrapper
08-10 13:33:24.157  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-10 13:33:24.157  6729  6799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-10 13:33:24.157  6729  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 13:33:24.157  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 13:33:24.158  6729  6799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-10 13:33:24.159  6729  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-10 13:33:24.159  6729  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-10 13:33:24.159  6729  6729 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-10 13:33:24.159  6729  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20394df0 not in the list
08-10 13:33:24.159  6729  6799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 13:33:24.159  6729  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 13:33:24.159  6729  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 13:33:24.160  6729  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 13:33:24.160  6729  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 13:33:24.160  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 13:33:24.160  6729  6799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eb633 not in the list
08-10 13:33:24.160  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 13:33:24.160  6729  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20394df0 not in the list
08-10 13:33:24.160  6729  6799 D io.jxcore.node.ConnectivityMonitor: stop
08-10 13:33:24.160  6729  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 13:33:24.160  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 13:33:24.160  6729  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release,: The given listener does not exist in the list - probably already removed
08-10 13:33:24.160  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 13:33:24.161  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 13:33:24.161  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 13:33:24.161  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 13:33:24.162  6729  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20394df0 not in the list
08-10 13:33:24.163  6729  6799 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-10 13:33:24.164  6729  6799 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-10 13:33:24.164  6729  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-10 13:33:24.169  6729  6799 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-10 13:33:24.169  6729  6799 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-10 13:33:24.169  6729  6799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 13:33:24.169  6729  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 13:33:24.169  6729  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 13:33:24.170  6729  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 13:33:24.170  6729  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 13:33:24.170  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 13:33:24.170  6729  6799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eb633 not in the list
08-10 13:33:24.170  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 13:33:24.170  6729  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20394df0 not in the list
08-10 13:33:24.170  6729  6799 D io.jxcore.node.ConnectivityMonitor: stop
08-10 13:33:24.170  6729  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 13:33:24.170  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 13:33:24.170  6729  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 13:33:24.170  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 13:33:24.175  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 13:33:24.175  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 13:33:24.175  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 13:33:24.175  6729  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20394df0 not in the list
08-10 13:33:24.178  1031  2016 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-10 13:33:24.182  1031  1578 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 13:33:24.183  1031  2006 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 13:33:24.183  6729  6799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 13:33:24.183  6729  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 13:33:24.184  6729  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 13:33:24.184  6729  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 13:33:24.184  6729  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 13:33:24.184  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 13:33:24.184  6729  6799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eb633 not in the list
08-10 13:33:24.184  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 13:33:24.184  6729  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20394df0 not in the list
08-10 13:33:24.184  6729  6799 D io.jxcore.node.ConnectivityMonitor: stop
08-10 13:33:24.184  6729  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 13:33:24.184  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 13:33:24.184  6729  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 13:33:24.184  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 13:33:24.186  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 13:33:24.186  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 13:33:24.186  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 13:33:24.186  6729  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20394df0 not in the list
08-10 13:33:24.187  6729  6799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 13:33:24.187  6729  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 13:33:24.187  6729  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 13:33:24.188  6729  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 13:33:24.188  6729  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 13:33:24.188  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 13:33:24.188  6729  6799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eb633 not in the list
08-10 1,3:33:24.188  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 13:33:24.188  6729  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20394df0 not in the list
08-10 13:33:24.188  6729  6799 D io.jxcore.node.ConnectivityMonitor: stop
08-10 13:33:24.188  6729  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 13:33:24.188  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 13:33:24.188  6729  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 13:33:24.188  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 13:33:24.190  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 13:33:24.190  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 13:33:24.190  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 13:33:24.190  6729  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20394df0 not in the list
,08-10 13:33:24.196  6729  6799 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-10 13:33:24.196  6729  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-10 13:33:24.197  6729  6799 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-10 13:33:24.197  6729  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-10 13:33:24.197  6729  6799 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-10 13:33:24.197  6729  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-10 13:33:24.199  6729  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-10 13:33:24.200  6729  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-10 13:33:24.200  6729  6799 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-10 13:33:24.201  6729  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-10 13:33:24.201  6729  6799 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-10 13:33:24.201  6729  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-10 13:33:24.201  6729  6799 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-10 13:33:24.201  6729  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-10 13:33:24.203  6729  6799 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-10 13:33:24.203  6729  6799 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-10 13:33:24.204  6729  6799 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-10 13:33:24.204  6729  6799 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-10 13:33:24.204  6729  6799 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-10 13:33:24.204  6729  6799 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-10 13:33:24.205  6729  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 13:33:24.206  6729  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1a34b2a1 added. We now have 3 listener(s)
08-10 13:33:24.206  6729  6799 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 13:33:24.207  6729  6799 D BluetoothAdapter: enable(): BT is already enabled..!
,08-10 13:33:24.211  1031  1944 D WifiServiceImplEx: setWifiEnabled: true pid=6729, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-10 13:33:24.212  1031  1944 D WifiService: setWifiEnabled: true pid=6729, uid=10118
08-10 13:33:24.212  1031  1944 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-10 13:33:24.214  6729  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 13:33:24.214  6729  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@634cc6 added. We now have 4 listener(s)
08-10 13:33:24.214  6729  6799 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 13:33:24.219  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 13:33:24.219  6729  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@634cc6 removed from the list
08-10 13:33:24.219  6729  6799 D io.jxcore.node.ConnectivityMonitor: stop
08-10 13:33:24.219  6729  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 13:33:24.219  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 13:33:24.220  6729  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 13:33:24.220  6729  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@12d03487 added. We now have 4 listener(s)
08-10 13:33:24.220  6729  6799 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-10 13:33:24.224  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 13:33:24.224  6729  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@12d03487 removed from the list
08-10 13:33:24.224  6729  6799 D io.jxcore.node.ConnectivityMonitor: stop
08-10 13:33:24.224  6729  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 13:33:24.224  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 13:33:24.225  6729  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 13:33:24.225  6729  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1a11afb4 added. We now have 4 listener(s)
08-10 13:33:24.225  6729  6799 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 13:33:24.227  1031  1944 D WifiServiceImplEx: setWifiEnabled: false pid=6729, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-10 13:33:24.228  1031  1944 D WifiService: setWifiEnabled: false pid=6729, uid=10118
08-10 13:33:24.228  1031  1944 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-10 13:33:24.240  1031  1031 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-10 13:33:24.240  1031  1031 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-10 13:33:24.241  1031  1031 D Ulp_jni : JNI:system_update. Event-4
08-10 13:33:24.243  1031  1539 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-10 13:33:24.243  1031  1539 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-10 13:33:24.244  1031  1539 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-10 13:33:24.244  1031  1539 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-10 13:33:24.244  1031  1539 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-10 13:33:24.244  1031  1539 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-10 13:33:24.245  1031  1539 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-10 13:33:24.245  1031  1539 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-10 13:33:24.246  1031  1539 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-10 13:33:24.246  1031  1539 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-10 13:33:24.247  1031  2035 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 13:33:24.248  1031  2035 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@e55db5b mBinding = false
,08-10 13:33:24.254  1031  1539 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-10 13:33:24.256  1031  1538 D LGWifiP2pService: InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-10 13:33:24.256  1031  1538 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-10 13:33:24.256  1031  1539 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-10 13:33:24.256  2742  2742 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-10 13:33:24.257  1031  1539 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-10 13:33:24.257  1031  1539 D WifiNative-wlan0: doBoolean: SET ps 1
08-10 13:33:24.259  1031  1096 D BluetoothManagerService: Message: 2
,08-10 13:33:24.262  1031  1096 D BluetoothManagerService: Sending off request.
08-10 13:33:24.263  3907  3926 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-10 13:33:24.264  3907  3993 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-10 13:33:24.264  3907  3993 D BluetoothAdapterProperties: Setting state to 13
08-10 13:33:24.264  3907  3993 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-10 13:33:24.264  3907  3993 D BluetoothAdapterProperties: onBluetoothDisable()
08-10 13:33:24.264  3907  3993 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-10 13:33:24.268  3907  3998 D BluetoothAdapterProperties: Scan Mode:20
08-10 13:33:24.269  3907  3993 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-10 13:33:24.270  3907  3993 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-10 13:33:24.271  3907  4243 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-10 13:33:24.274  3907  4320 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-10 13:33:24.274  3907  4323 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-10 13:33:24.275  3907  4318 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-10 13:33:24.276  3907  4242 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-10 13:33:24.276  3907  4242 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-10 13:33:24.276  3907  4242 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-10 13:33:24.276  3907  4242 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-10 13:33:24.276  3907  4242 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-10 13:33:24.276  3907  4242 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-10 13:33:24.276  3907  4242 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-10 13:33:24.276  3907  4242 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-10 13:33:24.279  3907  4109 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-10 13:33:24.279  3907  4109 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-10 13:33:24.283  3907  4109 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-10 13:33:24.283  3907  4109 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-10 13:33:24.283  3907  4109 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-10 13:33:24.283  3907  4109 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-10 13:33:24.283  3907  4109 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-10 13:33:24.283  3907  4109 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-10 13:33:24.283  3907  4109 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-10 13:33:24.283  3907  4109 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-10 13:33:24.283  3907  4109 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-10 13:33:24.283  3907  4109 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-10 13:33:24.283  3907  4109 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-10 13:33:24.283  3907  4109 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
,08-10 13:33:24.291  6729  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 13:33:24.291  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 13:33:24.291  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 13:33:24.291  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 13:33:24.291  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 13:33:24.291  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 13:33:24.291  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 13:33:24.291  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 13:33:24.291  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-10 13:33:24.303  6729  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 13:33:24.303  6729  6729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-10 13:33:24.312  6729  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 13:33:24.312  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 13:33:24.312  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 13:33:24.312  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 13:33:24.312  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 13:33:24.312  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 13:33:24.312  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 13:33:24.312  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 13:33:24.312  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-10 13:33:24.313  6729  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 13:33:24.313  6729  6729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-10 13:33:24.313  1031  1096 D BluetoothManagerService: Message: 60
08-10 13:33:24.313  1031  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-10 13:33:24.314  1031  1096 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-10 13:33:24.315  1031  1539 D WifiNative-wlan0: SET ps 1: returned true
,08-10 13:33:24.319  1031  2870 D DhcpStateMachine: RunningState{ when=-4ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-10 13:33:24.335   306   896 D CommandListener: Clearing all IP addresses on wlan0
08-10 13:33:24.337  1031  1031 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-10 13:33:24.338  1031  1031 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-10 13:33:24.338  1031  1031 D Ulp_jni : JNI:system_update. Event-4
,08-10 13:33:24.346  1031  1092 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6850 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-10 13:33:24.351  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-10 13:33:24.351  1945  1945 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-10 13:33:24.359  3907  3907 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-10 13:33:24.359  3907  3907 D BluetoothMapService: STATE_TURNING_OFF
08-10 13:33:24.359  3907  3907 V BluetoothMapService: Handler(): got msg=4
08-10 13:33:24.359  3907  3907 D BluetoothMapService: MAP Service closeService in
08-10 13:33:24.359  3907  3907 D BluetoothMapMasInstance: MAP Service shutdown
08-10 13:33:24.359  3907  3907 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-10 13:33:24.359  3907  3907 V BluetoothMapService: MAP Service closeService out
,08-10 13:33:24.360  3907  3907 V BtOppService: Receiver DISABLED_ACTION 
08-10 13:33:24.360  3907  3907 I BtOppRfcommListener: stopping Accept Thread
08-10 13:33:24.360  3907  3907 V BtOppRfcommListener: close mBtServerSocket
08-10 13:33:24.360  3907  3907 V BtOppRfcommListener: waiting for thread to terminate
08-10 13:33:24.361  3907  4318 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-10 13:33:24.362  3907  3907 V BtOppRfcommListener: done waiting for thread to terminate
08-10 13:33:24.366  6729  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 13:33:24.373  1031  1046 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
,08-10 13:33:24.374  1031  2869 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-10 13:33:24.374  1031  2869 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-10 13:33:24.374  1031  2869 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-10 13:33:24.374  1031  2869 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-10 13:33:24.374  1031  2869 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-10 13:33:24.378   306  6864 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-10 13:33:24.378  1031  1094 D DSQN    : Dns fail occured do internet check.
08-10 13:33:24.378  1031  2869 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
08-10 13:33:24.378  1031  1031 D DSQN    : EVENT_INTERNET_CHECK_REQUEST received
08-10 13:33:24.379  1031  1031 D DSQN    : try Internet connection check
08-10 13:33:24.380  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 13:33:24.381  6729  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 13:33:24.381  6729  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 13:33:24.381  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 13:33:24.381  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 13:33:24.381  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 13:33:24.381  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 13:33:24.381  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 13:33:24.381  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 13:33:24.381  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-10 13:33:24.381  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 13:33:24.382  6729  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 13:33:24.382  6729  6799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-10 13:33:24.382  6729  6799 D io.jxcore.node.ConnectivityMonitor: start: OK
08-10 13:33:24.394  1031  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-10 13:33:24.394  1031  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,08-10 13:33:24.422  1031  1092 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6876 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-10 13:33:24.424  3907  3907 V BtOppService: onDestroy
08-10 13:33:24.431  1031  1031 D WifiHS20: hidePasspointNotification off =false
08-10 13:33:24.431  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 13:33:24.431  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 13:33:24.431  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-10 13:33:24.431  1031  1031 D WifiHS20: hidePasspointNotification off =false
08-10 13:33:24.431  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 13:33:24.431  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 13:33:24.431  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-10 13:33:24.433  6729  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 13:33:24.433  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 13:33:24.433  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 13:33:24.433  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 13:33:24.433  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 13:33:24.433  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 13:33:24.433  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 13:33:24.433  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 13:33:24.433  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-10 13:33:24.434  3907  3907 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
,08-10 13:33:24.435  1031  1538 D LGWifiP2pService: InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-10 13:33:24.435  1031  1538 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-10 13:33:24.435  1031  1538 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@1eba7ca2
08-10 13:33:24.435  1031  1538 D LGWifiP2pService: P2pDisablingState
08-10 13:33:24.435  1031  1538 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-10 13:33:24.436  1031  1539 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 13:33:24.436  1031  1539 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 13:33:24.436  1031  1539 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 13:33:24.437  1031  1539 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 13:33:24.437  1031  1539 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 13:33:24.437  1031  1539 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 13:33:24.437  1031  1539 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-10 13:33:24.438  1031  1539 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 13:33:24.438  1031  1538 D LGWifiP2pService: p2p socket connection lost
08-10 13:33:24.438  1031  1538 D LGWifiP2pService: P2pDisabledState
08-10 13:33:24.438  1031  1539 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 13:33:24.438  1031  1539 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 13:33:24.439  1031  1539 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-10 13:33:24.439  1031  1538 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-10 13:33:24.439  1031  1538 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-10 13:33:24.439  1031  1539 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-10 13:33:24.439  2742  2742 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-10 13:33:24.440  1031  1539 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-10 13:33:24.440  1031  1539 D WifiNative-wlan0: doBoolean: SET ps 1
08-10 13:33:24.440  1031  1539 D WifiNative-wlan0: SET ps 1: returned true
08-10 13:33:24.441  1945  1945 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-10 13:33:24.441  1031  1031 D WifiScanningService: SCAN_AVAILABLE : 1
08-10 13:33:24.441  1031  1031 D RttService: SCAN_AVAILABLE : 1
08-10 13:33:24.442  1945  1945 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-10 13:33:24.442  1031  1559 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-10 13:33:24.442  1031  1560 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-10 13:33:24.444  1945  1945 D WfdsService: WifiP2pState is changed : false
08-10 13:33:24.445  1945  2312 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-10 13:33:24.445  1945  2312 D WfdsService: Set the WFDS Monitor: false
08-10 13:33:24.445  1945  2312 D WfdsMonitor: WFDS Monitor is stopped
08-10 13:33:24.445  1945  2312 D WfdsService: STATE : WfdsDisabledState - enter
08-10 13:33:24.445  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 13:33:24.445  1945  2791 D CtrlSupplicant: Received on exit socket, terminate
08-10 13:33:24.445  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWif,iLevel = 0
08-10 13:33:24.445  1945  2791 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-10 13:33:24.446  1945  2791 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-10 13:33:24.446  1945  2791 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-10 13:33:24.446  1945  2313 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-10 13:33:24.446  1945  2312 W WfdsService: DefaultState - msg [9445378] is not handled
08-10 13:33:24.447  6729  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 13:33:24.447  6729  6729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-10 13:33:24.448  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 13:33:24.449  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 13:33:24.451  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 13:33:24.451  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-10 13:33:24.451  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 13:33:24.460  1031  1545 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-10 13:33:24.460  1031  1545 D DSQN    : disableDataServiceNotify
08-10 13:33:24.460  1031  1545 D DSQN    : stop dsqn bin
08-10 13:33:24.461   306  6896 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-10 13:33:24.461   306   896 D CommandListener: Clearing all IP addresses on wlan0
08-10 13:33:24.462  1031  6874 D DSQN    : ThreadTCPConnectionCheck DNS fail internet is not possible
08-10 13:33:24.462  1031  1094 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-10 13:33:24.462  1031  6865 D DSQN    : ThreadInternetCheck internet check NOK 
08-10 13:33:24.462  1031  6865 D DSQN    : InternetcheckProgress is not set don't send DS quality intent
08-10 13:33:24.463  1031  1539 D WifiNative-p2p0: doBoolean: TERMINATE
08-10 13:33:24.464  1031  1545 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-10 13:33:24.465  1031  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 13:33:24.465  1031  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-10 13:33:24.465  1031  1545 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-10 13:33:24.465  1031  1545 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-10 13:33:24.465  1605  2072 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-10 13:33:24.465  1031  1545 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-10 13:33:24.465  1031  1545 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-10 13:33:24.465  1031  1031 D WifiHS20: hidePasspointNotification off =false
08-10 13:33:24.465  1031  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-10 13:33:24.466  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 13:33:24.466  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 13:33:24.466  1031  1545 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-10 13:33:24.466  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-10 13:33:24.466  1031  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-10 13:33:24.466  1031  1545 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-10 13:33:24.466  1031  1545 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 13:33:24.466  1031  1545 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 13:33:24.466  1031  1545 D NetworkManagementService: Removing idletimer
08-10 13:33:24.466  1031  1545 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 13:33:24.467  1031  1545 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-10 13:33:24.467  1031  2869 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-10 13:33:24.467  1031  2869 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-10 13:33:24.467  1031  2869 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-10 13:33:24.468  1856  1856 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 13:33:24.468  1856  1856 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-10 13:33:24.468  1031  1537 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-10 13:33:24.468  1031  1537 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-10 13:33:24.469  1031  1031 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-10 13:33:24.469  1031  1031 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-10 13:33:24.469  1031  1031 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-10 13:33:24.469  1031  1031 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-10 13:33:24.469  1031  1031 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-10 13:33:24.469  1031  1031 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-10 13:33:24.469  1031  1031 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-10 13:33:24.469  1031  1031 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-10 13:33:24.470  1031  1539 D WifiNative-p2p0: TERMINATE: returned true
08-10 13:33:24.470  1031  1539 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-10 13:33:24.470  1031  1539 E WifiStateMachine: useWiFiOffloading() : false
08-10 13:33:24.470  1031  1539 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-10 13:33:24.470  1031  1539 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 13:33:24.470  1031  1539 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-10 13:33:24.471  1945  1945 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-10 13:33:24.471  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-10 13:33:24.471  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-10 13:33:24.473  1031  1031 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-10 13:33:24.474  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-10 13:33:24.474  1031  1031 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-10 13:33:24.475  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 13:33:24.475  6729  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 13:33:24.476  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 13:33:24.476  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 13:33:24.476  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 13:33:24.476  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 13:33:24.476  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 13:33:24.476  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 13:33:24.476  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 13:33:24.476  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 13:33:24.476  6729  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 13:33:24.476  6729  6729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 13:33:24.479  6729  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 13:33:24.479  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 13:33:24.479  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 13:33:24.479  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 13:33:24.479  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 13:33:24.479  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 13:33:24.479  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 13:33:24.479  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 13:33:24.479  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 13:33:24.481  6729  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 13:33:24.481  6729  6729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 13:33:24.483  6729  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 13:33:24.483  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 13:33:24.483  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 13:33:24.483  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 13:33:24.483  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 13:33:24.483  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 13:33:24.483  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 13:33:24.483  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 13:33:24.483  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 13:33:24.483  6729  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 13:33:24.483  6729  6729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 13:33:24.485  6876  6876 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-10 13:33:24.486  6876  6876 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-10 13:33:24.486  6876  6876 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-10 13:33:24.486  6876  6876 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-10 13:33:24.487  6876  6876 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-10 13:33:24.487  6876  6876 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-10 13:33:24.508  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-10 13:33:24.508  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 13:33:24.509  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 13:33:24.520  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-10 13:33:24.520  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 13:33:24.521  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 13:33:24.521  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-10 13:33:24.525  6850  6850 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-10 13:33:24.526  6850  6850 W LG Account v2.2: No ProfileInfo entries
08-10 13:33:24.526  6850  6850 I LG Account v2.2: isEnabled: false
08-10 13:33:24.526  6850  6850 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-10 13:33:24.526  6850  6850 I Feature : [Lifetracker]Country: EU
,08-10 13:33:24.526  6850  6850 I Feature : [Lifetracker]Operator: OPEN
08-10 13:33:24.526  6850  6850 I Feature : [Lifetracker]Ranking support: false
08-10 13:33:24.526  6850  6850 I Feature : [Lifetracker]Comfort support: false
08-10 13:33:24.526  6850  6850 I Feature : [Lifetracker]Accessory: true
08-10 13:33:24.526  6850  6850 I Feature : [Lifetracker]Health device: true
08-10 13:33:24.526  6850  6850 I Feature : [Lifetracker]Extra Pedometer: false
08-10 13:33:24.526  6850  6850 I Feature : [Lifetracker]Blood glucose device: false
08-10 13:33:24.526  6850  6850 I Feature : [Lifetracker]Device Number: 3
08-10 13:33:24.531  1031  2870 D DhcpStateMachine: StoppedState
08-10 13:33:24.531  1031  2870 D DhcpStateMachine: StoppedState{ when=-91ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-10 13:33:24.531  1031  1539 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-10 13:33:24.531  1031  1539 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-10 13:33:24.532  6357  6357 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 13:33:24.542  2742  2742 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-10 13:33:24.542  2742  2742 I wpa_supplicant: monitor socket send errors count : 1
08-10 13:33:24.543  2742  2742 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1945-2\x00 that cannot receive messages
08-10 13:33:24.543  1031  2787 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-10 13:33:24.543  1031  2787 D WifiMonitor: Dropping event because (p2p0) is stopped
,08-10 13:33:24.564  1031  1944 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6901 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-10 13:33:24.566  1031  1944 I ActivityManager: Killing 6300:com.android.defcontainer/u0a4 (adj 15): empty #17
08-10 13:33:24.582  2742  2742 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-10 13:33:24.583  2742  2742 W wpa_supplicant: USIM:  scard_deinit function
08-10 13:33:24.583  1031  2787 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-10 13:33:24.583  1031  2787 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-10 13:33:24.583  1031  2787 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-10 13:33:24.584  1031  2787 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-10 13:33:24.584  1031  2787 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-10 13:33:24.584  1031  2787 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-10 13:33:24.584  1031  1096 D Tethering: InitialState.processMessage what=4
08-10 13:33:24.585  1031  1539 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=351791
08-10 13:33:24.585  1031  1539 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=351791
08-10 13:33:24.586  1031  1539 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=351792  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-10 13:33:24.586  1031  1539 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=351792  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-10 13:33:24.603  1031  1773 W libprocessgroup: failed to open /acct/uid_10004/pid_6300/cgroup.procs: No such file or directory
08-10 13:33:24.603  1031  1096 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-10 13:33:24.608  1031  1539 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-10 13:33:24.609  1031  1539 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-10 13:33:24.653  2742  2742 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-10 13:33:24.655  1031  2787 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-10 13:33:24.655  1031  2787 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
08-10 13:33:24.655  1031  2787 D WifiMonitor: Disconnecting from the supplicant, no more events
08-10 13:33:24.656  1031  1539 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
08-10 13:33:24.657  6901  6901 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-10 13:33:24.660  6729  6729 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-10 13:33:24.663  6901  6901 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-10 13:33:24.663  6901  6901 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-10 13:33:24.666  1031  1944 I ActivityManager: Killing 6402:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,08-10 13:33:24.677  6876  6876 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-10 13:33:24.723  1031  1047 W libprocessgroup: failed to open /acct/uid_10008/pid_6402/cgroup.procs: No such file or directory
,08-10 13:33:24.734  6876  6876 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-10 13:33:24.735  3907  3907 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-10 13:33:24.736  3907  3907 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-10 13:33:24.736  3907  3907 V BluetoothPbapReceiver: ***********state = 13
08-10 13:33:24.738  3907  3907 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
,08-10 13:33:24.742  3907  3907 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-10 13:33:24.742  3907  3907 V BluetoothPbapService: state: 13
08-10 13:33:24.742  3907  3907 V BluetoothPbapService: Pbap Service closeService in
08-10 13:33:24.747  2193  2193 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-10 13:33:24.748  3907  3907 V BluetoothPbapService: successfully stopped pbap service
08-10 13:33:24.748  3907  3907 V BluetoothPbapService: Pbap Service closeService out
08-10 13:33:24.748  3907  3907 V BluetoothPbapService: Pbap Service onDestroy
08-10 13:33:24.748  3907  3907 V BluetoothPbapService: Pbap Service closeService in
08-10 13:33:24.748  3907  3907 V BluetoothPbapService: Pbap Service closeService out
08-10 13:33:24.748  3907  3907 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-10 13:33:24.762  1031  1539 D WifiOffDelayIfNotUsed: stopMonitoring
,08-10 13:33:24.762  1945  1945 D WfdsService: Supplicant Connection state is changed : false
08-10 13:33:24.762  1031  1539 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-10 13:33:24.762  1031  1539 E WifiStateMachine: useWiFiOffloading() : false
08-10 13:33:24.762  1031  1539 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-10 13:33:24.762  1945  2312 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-10 13:33:24.763  1945  2312 D WfdsService: Set the WFDS Monitor: false
08-10 13:33:24.763  1945  2312 D WfdsMonitor: WFDS Monitor is stopped
08-10 13:33:24.765  2514  2514 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 13:33:24.766  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 13:33:24.766  1945  1945 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-10 13:33:24.767  1031  1031 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-10 13:33:24.767  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 13:33:24.767  1031  1543 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-10 13:33:24.767  1031  1543 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-10 13:33:24.769  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 13:33:24.770  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 13:33:24.777  6876  6876 D LgDataFeature: LgDataFeature() Constructor: none
08-10 13:33:24.777  6876  6876 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-10 13:33:24.784  6876  6876 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 13:33:24.792  1031  1096 D BluetoothManagerService: Message: 20
08-10 13:33:24.792  1031  1096 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1f502cc2:true
,08-10 13:33:24.799  1031  1096 D BluetoothManagerService: Message: 30
08-10 13:33:24.803  1031  1096 D BluetoothManagerService: Message: 30
08-10 13:33:24.805  6876  6876 D LocalBluetoothProfileManager: Adding local MAP profile
08-10 13:33:24.806  6876  6876 D BluetoothMap: Create BluetoothMap proxy object
08-10 13:33:24.806  1031  1096 D BluetoothManagerService: Message: 30
,08-10 13:33:24.810  1031  1096 D BluetoothManagerService: Message: 30
08-10 13:33:24.812  6876  6876 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-10 13:33:24.813  6876  6876 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
08-10 13:33:24.825  6876  6876 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,08-10 13:33:24.830  6876  6876 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
08-10 13:33:24.843  6876  6876 D DockEventReceiver: finishStartingService: stopping service
,08-10 13:33:24.859  6876  6876 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-10 13:33:24.865  6876  6876 D BluetoothInputDevice: Proxy object connected
08-10 13:33:24.866  6876  6876 D HidProfile: Bluetooth service connected
08-10 13:33:24.867  6876  6876 D BluetoothPan: BluetoothPAN Proxy object connected
08-10 13:33:24.867  6876  6876 D PanProfile: Bluetooth service connected
08-10 13:33:24.868  6876  6876 D BluetoothMap: Proxy object connected
08-10 13:33:24.869  6876  6876 D MapProfile: Bluetooth service connected
08-10 13:33:24.869  6876  6876 D BluetoothMap: getConnectedDevices()
08-10 13:33:24.869  6876  6876 D BluetoothMap: Bluetooth is Not enabled
08-10 13:33:24.869  6876  6876 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-10 13:33:24.871  6876  6876 D BluetoothPermissionRequest: onReceive
,08-10 13:33:24.879  6876  6876 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-10 13:33:24.892  1031  1773 I ActivityManager: Killing 6047:com.lge.appbox.client/u0a11 (adj 15): empty #17
08-10 13:33:24.893  6876  6876 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-10 13:33:24.914  3907  3907 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-10 13:33:24.914  3907  3907 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-10 13:33:24.915  3907  3907 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-10 13:33:24.915  1031  1944 W libprocessgroup: failed to open /acct/uid_10011/pid_6047/cgroup.procs: No such file or directory
,08-10 13:33:24.982  1031  2006 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6933 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-10 13:33:24.988  3907  3907 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-10 13:33:24.988  3907  3907 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-10 13:33:24.991  3907  3907 V BluetoothFtpService: Ftp Service onStartCommand
08-10 13:33:24.992  3907  3907 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-10 13:33:24.993  3907  3907 V BluetoothFtpService: Ftp Service closeService
08-10 13:33:24.993  3907  3907 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-10 13:33:24.994  3907  3907 V BluetoothFtpService: successfully stopped ftp service
,08-10 13:33:24.995  3907  3907 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-10 13:33:24.995  3907  3907 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-10 13:33:24.995  3907  3907 V BluetoothSapReceiver: SapReceiver onReceive 
08-10 13:33:24.995  3907  3907 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-10 13:33:24.996  3907  3907 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-10 13:33:24.996  3907  3907 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-10 13:33:24.998  3907  3907 V BluetoothFtpService: Ftp Service onDestroy
08-10 13:33:24.998  3907  3907 V BluetoothFtpService: Ftp Service closeService
08-10 13:33:25.054  1031  1908 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6950 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-10 13:33:25.064  3907  3907 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-10 13:33:25.064  3907  3907 V BluetoothSapService: state: 13
08-10 13:33:25.064  3907  3907 V BluetoothSapService: Stopping SAP server process
08-10 13:33:25.065  3907  3907 V BluetoothSapService: Sap Service closeSapService in
08-10 13:33:25.065  3907  3907 V BluetoothSapService: Close listen Socket : 
08-10 13:33:25.066  3907  3907 V BluetoothSapService: Close rfcomm Socket : 
08-10 13:33:25.066  3907  3907 V BluetoothSapService: Close sapd  Socket : 
08-10 13:33:25.067  3907  3907 V BluetoothSapService: Sap Service closeSapService out
08-10 13:33:25.067  3907  3907 V BluetoothSapService: Sap Service onDestroy
08-10 13:33:25.067  3907  3907 V BluetoothSapService: Sap Service closeSapService in
08-10 13:33:25.067  3907  3907 V BluetoothSapService: Close listen Socket : 
08-10 13:33:25.067  3907  3907 V BluetoothSapService: Close rfcomm Socket : 
08-10 13:33:25.067  3907  3907 V BluetoothSapService: Close sapd  Socket : 
08-10 13:33:25.068  3907  3907 V BluetoothSapService: Sap Service closeSapService out
,08-10 13:33:25.078   341   341 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 455us total 24.319ms
08-10 13:33:25.099   341   341 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 474us total 20.818ms
,08-10 13:33:25.103  6933  6933 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-10 13:33:25.120   341   341 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 421us total 20.249ms
,08-10 13:33:25.128  6950  6950 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-10 13:33:25.133  6933  6933 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-10 13:33:25.147  1031  2006 I ActivityManager: Killing 6067:com.android.contacts/u0a19 (adj 15): empty #17
,08-10 13:33:25.181  6933  6933 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-10 13:33:25.181  6933  6933 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-10 13:33:25.182  6933  6933 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-10 13:33:25.183  6933  6933 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-10 13:33:25.183  6933  6933 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-10 13:33:25.185  6933  6933 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,08-10 13:33:25.190  6933  6933 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-10 13:33:25.206  1031  2035 W libprocessgroup: failed to open /acct/uid_10019/pid_6067/cgroup.procs: No such file or directory
,08-10 13:33:25.216  6933  6933 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-10 13:33:25.220  6933  6933 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-10 13:33:25.257  6933  6933 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-10 13:33:25.261  6357  6357 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 13:33:25.266  6933  6933 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-10 13:33:25.270  6901  6901 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-10 13:33:25.270  6901  6901 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-10 13:33:25.270  6901  6901 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-10 13:33:25.273  6933  6933 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-10 13:33:25.275  6876  6876 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-10 13:33:25.281  6876  6876 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 13:33:25.288  6933  6933 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-10 13:33:25.288  6933  6933 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-10 13:33:25.288  3907  3998 D bt_hci_bdroid: cleanup
08-10 13:33:25.289  3907  4111 I bt_lpm  : LPM is already off!!!
,08-10 13:33:25.289  3907  4234 I bt_userial_mct: exiting userial_read_thread
08-10 13:33:25.289  3907  4234 D bt_userial_mct: Leaving userial_evt_read_thread()
08-10 13:33:25.289  3907  3998 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-10 13:33:25.290  3907  4111 I bt_vendor: hw_epilog_process
08-10 13:33:25.290  3907  3998 D bt_hci_bdroid: cleanup Finalizing cleanup
08-10 13:33:25.290  3907  3998 D bt_userial_mct: userial_close
08-10 13:33:25.290  3907  3998 E bt_userial_mct: pthread_join() FAILED result:3
08-10 13:33:25.290  3907  3998 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-10 13:33:25.290  3907  4109 W bt-btif : ag scb idx 1 not allocated
08-10 13:33:25.290  3907  4109 E bt-btif : BTA AG is already disabled, ignoring ...
08-10 13:33:25.290  3907  4109 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-10 13:33:25.290  3907  4109 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-10 13:33:25.290  3907  4109 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-10 13:33:25.290  3907  4109 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-10 13:33:25.290  3907  4109 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
,08-10 13:33:25.290  3907  4109 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-10 13:33:25.290  3907  4109 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-10 13:33:25.290  3907  4109 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-10 13:33:25.290  3907  4109 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-10 13:33:25.290  3907  4109 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-10 13:33:25.290  3907  4109 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-10 13:33:25.290  3907  4109 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-10 13:33:25.291  3907  4109 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-10 13:33:25.291  3907  4109 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-10 13:33:25.291  3907  4109 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-10 13:33:25.291  3907  4109 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-10 13:33:25.291  3907  4109 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-10 13:33:25.291  3907  4109 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-10 13:33:25.291  3907  4109 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-10 13:33:25.293  6933  6933 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-10 13:33:25.296  6357  6357 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 13:33:25.301  6901  6901 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-10 13:33:25.301  6901  6901 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-10 13:33:25.301  6901  6901 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-10 13:33:25.306  6876  6876 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-10 13:33:25.312  6876  6876 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 13:33:25.318  6933  6933 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-10 13:33:25.319  6933  6933 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-10 13:33:25.321  6933  6933 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-10 13:33:25.372  3907  3998 D bt_hci_bdroid: set_power 0
08-10 13:33:25.372  3907  3998 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-10 13:33:25.372  3907  3998 I bt_vendor: bluetooth satus is on
08-10 13:33:25.372  3907  3998 I bt_vendor: bt-vendor : resetting BT status
08-10 13:33:25.372  3907  3998 I bt_vendor: Starting hciattach daemon
08-10 13:33:25.372  3907  3998 I bt_vendor: try to set false
,08-10 13:33:25.374  3907  3998 I bt_vendor: Starting hciattach daemon
08-10 13:33:25.374  3907  3998 I bt_vendor: try to set false
08-10 13:33:25.376  3907  3998 I bt_vendor: cleanup
08-10 13:33:25.378  3907  4109 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-10 13:33:25.379  3907  3998 I GKI_LINUX: GKI_exit_task 0 done
08-10 13:33:25.379  3907  3998 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-10 13:33:25.383  3907  3993 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-10 13:33:25.385  1031  2035 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6971 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
08-10 13:33:25.393  3907  3907 D HeadsetService: Received stop request...Stopping profile...
,08-10 13:33:25.396  3907  3907 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-10 13:33:25.396  3907  3907 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-10 13:33:25.396  3907  3907 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2aac7cd
08-10 13:33:25.397  3907  4021 D HeadsetStateMachine: Exit Disconnected: -1
08-10 13:33:25.397  1031  1031 D BluetoothHeadset: Proxy object disconnected
08-10 13:33:25.398  1031  1031 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-10 13:33:25.398  1856  1856 D BluetoothHeadset: Proxy object disconnected
08-10 13:33:25.398  1856  1856 D BluetoothHeadset: Proxy object disconnected
08-10 13:33:25.398  1856  1856 D BluetoothHeadset: Proxy object disconnected
08-10 13:33:25.399  3907  3907 D A2dpService: Received stop request...Stopping profile...
08-10 13:33:25.400  3907  4097 D A2dpStateMachine: Exit Disconnected: -1
08-10 13:33:25.401  3907  3993 D BluetoothAdapterState: Stopping profile services that were post enabled
08-10 13:33:25.401  3907  3907 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-10 13:33:25.402  3907  3907 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-10 13:33:25.402  3907  3907 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-10 13:33:25.402  3907  3907 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2aac7cd
08-10 13:33:25.402  1031  1031 D BluetoothA2dp: Proxy object disconnected
08-10 13:33:25.403  1031  1031 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-10 13:33:25.403  3907  3907 D HidService: Received stop request...Stopping profile...
08-10 13:33:25.403  3907  3907 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2aac7cd
08-10 13:33:25.404  6876  6876 D BluetoothInputDevice: Proxy object disconnected
08-10 13:33:25.405  6876  6876 D HidProfile: Bluetooth service disconnected
08-10 13:33:25.405  3907  3907 D HealthService: Received stop request...Stopping profile...
08-10 13:33:25.405  3907  3907 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2aac7cd
,08-10 13:33:25.407  3907  3907 D HeadsetStateMachine: Unbinding service...
08-10 13:33:25.408  3907  3907 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-10 13:33:25.408  3907  3907 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-10 13:33:25.408  3907  3907 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-10 13:33:25.408  3907  3907 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-10 13:33:25.409  3907  3907 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-10 13:33:25.409  3907  3907 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-10 13:33:25.409  3907  3907 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-10 13:33:25.410  3907  3907 D PanService: Received stop request...Stopping profile...
08-10 13:33:25.410  3907  3907 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2aac7cd
08-10 13:33:25.411  3907  3907 D BtGatt.DebugUtils: handleDebugAction() action=null
08-10 13:33:25.411  3907  3907 D BtGatt.GattService: Received stop request...Stopping profile...
08-10 13:33:25.411  3907  3907 D BtGatt.GattService: stop()
08-10 13:33:25.412  3907  3907 D BtGatt.AdvertiseManager: advertise clients cleared
08-10 13:33:25.412  6876  6876 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-10 13:33:25.412  6876  6876 D PanProfile: Bluetooth service disconnected
08-10 13:33:25.413  3907  3907 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2aac7cd
08-10 13:33:25.414  3907  3907 D BluetoothMapService: Received stop request...Stopping profile...
08-10 13:33:25.414  3907  3907 D BluetoothMapService: stop()
08-10 13:33:25.414  3907  3907 D BluetoothMapEmailAppObserver: deinitObservers()
08-10 13:33:25.414  3907  3907 D BluetoothMapEmailAppObserver: removeReceiver()
08-10 13:33:25.415  3907  3907 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2aac7cd
08-10 13:33:25.416  6876  6876 D BluetoothMap: Proxy object disconnected
08-10 13:33:25.416  6876  6876 D MapProfile: Bluetooth service disconnected
08-10 13:33:25.416  3907  3907 I BluetoothA2dpServiceJni: cleanupNative
08-10 13:33:25.416  3907  4098 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-10 13:33:25.416  3907  3907 I GKI_LINUX: GKI_exit_task 2 done
08-10 13:33:25.416  3907  3907 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-10 13:33:25.417  3907  3907 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-10 13:33:25.417  3907  3907 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-10 13:33:25.417  3907  3907 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-10 13:33:25.417  3907  3907 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-10 13:33:25.417  3907  3907 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-10 13:33:25.418  3907  3907 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-10 13:33:25.418  3907  3907 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-10 13:33:25.419  3907  3907 V BluetoothMapService: Handler(): got msg=4
08-10 13:33:25.419  3907  3907 D BluetoothMapService: MAP Service closeService in
08-10 13:33:25.419  3907  3907 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-10 13:33:25.419  3907  3907 V BluetoothMapService: MAP Service closeService out
08-10 13:33:25.420  3907  3993 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-10 13:33:25.420  3907  3993 D BluetoothAdapterProperties: Setting state to 10
08-10 13:33:25.420  3907  3993 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-10 13:33:25.421  1031  1096 D BluetoothManagerService: Message: 60
08-10 13:33:25.421  1031  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-10 13:33:25.421  3907  3907 D BluetoothMapService: cleanup()
08-10 13:33:25.421  3907  3907 D BluetoothMapService: MAP Service closeService in
08-10 13:33:25.421  1031  1096 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-10 13:33:25.421  3907  3907 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-10 13:33:25.421  3907  3907 V BluetoothMapService: MAP Service closeService out
08-10 13:33:25.421  3907  3993 I BluetoothAdapterState: Entering OffState
08-10 13:33:25.421  1856  4044 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 13:33:25.422  1031  1096 D BluetoothA2dp: onBluetoothStateChange: up=false
08-10 13:33:25.422  6876  6892 D BluetoothPbap: onBluetoothStateChange: up=false
08-10 13:33:25.423  1856  1872 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 13:33:25.424  6876  6893 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-10 13:33:25.424  1856  4019 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 13:33:25.425  1031  1096 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 13:33:25.425  6876  6892 D BluetoothMap: onBluetoothStateChange: up=false
08-10 13:33:25.425  6876  6893 D BluetoothPan: onBluetoothStateChange on: false
08-10 13:33:25.427  1031  1096 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-10 13:33:25.427  1031  1096 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-10 13:33:25.429  1031  1096 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-10 13:33:25.429  1031  1096 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-10 13:33:25.429  1031  1096 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@e55db5b mBinding = false
08-10 13:33:25.430  1031  1096 D BluetoothManagerService: Sending unbind request.
,08-10 13:33:25.440  3907  3998 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-10 13:33:25.440  3907  3907 I GKI_LINUX: GKI_exit_task 1 done
08-10 13:33:25.440  3907  3907 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-10 13:33:25.440  3907  3907 I BluetoothServiceJni: cleanupNative: return from cleanup
08-10 13:33:25.441  3907  3907 I art     : --- WEIRD: removing null entry 246
08-10 13:33:25.441  3907  3907 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-10 13:33:25.441  3907  3907 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-10 13:33:25.442  3907  3907 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-10 13:33:25.443  1031  1096 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-10 13:33:25.444  3907  3907 I art     : System.exit called, status: 0
08-10 13:33:25.444  3907  3907 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-10 13:33:25.446  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 13:33:25.447  1945  1945 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-10 13:33:25.447  1945  2120 D LGBluetoothAPIService: Message: 2
08-10 13:33:25.447  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-10 13:33:25.447  1945  2120 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@23faccb4 mBinding = false
08-10 13:33:25.448  1945  2120 D LGBluetoothAPIService: Sending unbind request.
08-10 13:33:25.449  6876  6876 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-10 13:33:25.449  6876  6876 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-10 13:33:25.449  6876  6876 D LGBluetoothEventManager: [BTUI] clear device connection state
08-10 13:33:25.452  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 13:33:25.454  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 13:33:25.460  6876  6876 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-10 13:33:25.462  1031  1031 D DSQN    : EVENT_INTERNET_CHECK_ENABLE received
08-10 13:33:25.467   310  2199 V AudioFlinger: 3907 died, releasing its sessions
08-10 13:33:25.467   310  2199 V AudioFlinger:  pid 1856 @ 0
08-10 13:33:25.467   310  2199 V AudioFlinger:  pid 3485 @ 1
08-10 13:33:25.467   310  2199 V AudioFlinger:  pid 3485 @ 2
08-10 13:33:25.472  1031  2016 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapReceiver}
08-10 13:33:25.472  1031  2016 W BroadcastQueue: android.os.DeadObjectException
08-10 13:33:25.472  1031  2016 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
08-10 13:33:25.472  1031  2016 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
08-10 13:33:25.472  1031  2016 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:857)
08-10 13:33:25.472  1031  2016 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:252)
08-10 13:33:25.472  1031  2016 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:939)
08-10 13:33:25.472  1031  2016 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:16582)
08-10 13:33:25.472  1031  2016 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:473)
08-10 13:33:25.472  1031  2016 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2560)
08-10 13:33:25.472  1031  2016 W BroadcastQueue: 	at com.android.server.am.ActivityManagerServiceEx.onTransact(ActivityManagerServiceEx.java:421)
08-10 13:33:25.472  1031  2016 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
,08-10 13:33:25.478  1605  1605 D BluetoothAdapter: 371047941: getState() :  mService = null. Returning STATE_OFF
08-10 13:33:25.478  1605  1605 D BluetoothAdapter: 371047941: getState() :  mService = null. Returning STATE_OFF
08-10 13:33:25.522  1031  2016 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,08-10 13:33:25.582  1031  2016 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=6994 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-10 13:33:25.583  1031  1890 W ActivityManager: Spurious death for ProcessRecord{3f62302d 6994:com.android.bluetooth/1002}, curProc for 3907: null
08-10 13:33:25.585  6876  6876 D DockEventReceiver: finishStartingService: stopping service
08-10 13:33:25.586  6876  6876 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-10 13:33:25.597  6901  6901 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-10 13:33:25.600  6876  6876 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-10 13:33:25.616  6876  6876 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 13:33:25.628  6971  7014 W FormManager: Network not available. Please check & try again.
,08-10 13:33:25.638  6876  6876 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-10 13:33:25.638  6876  6876 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-10 13:33:25.638  6876  6876 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-10 13:33:25.638  6876  6876 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-10 13:33:25.639  6876  6876 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-10 13:33:25.644  6971  7015 V FormManager: Network unavailable.
,08-10 13:33:25.648  6971  7015 V FormManager: Network unavailable.
08-10 13:33:25.654  6876  6876 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-10 13:33:25.654  6876  6876 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-10 13:33:25.654  6876  6876 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-10 13:33:25.654  6876  6876 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-10 13:33:25.654  6876  6876 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-10 13:33:25.655  6876  6876 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-10 13:33:25.658  4325  4325 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-10 13:33:25.658  4325  4325 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-10 13:33:25.660  4325  4325 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-10 13:33:25.662  4325  4325 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-10 13:33:25.668  6994  6994 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-10 13:33:25.669  6994  6994 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-10 13:33:25.669  6901  6901 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-10 13:33:25.669  6901  6901 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-10 13:33:25.669  6901  6901 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-10 13:33:25.669  6994  6994 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-10 13:33:25.670  6994  6994 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-10 13:33:25.671  4325  7019 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-10 13:33:25.672  6876  6876 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-10 13:33:25.677  6971  7020 W FormManager: Network not available. Please check & try again.
08-10 13:33:25.682  6876  6876 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 13:33:25.682  4325  7021 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-10 13:33:25.682  4325  7021 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-10 13:33:25.683  6971  7022 V FormManager: Network unavailable.
,08-10 13:33:25.691  6971  7022 V FormManager: Network unavailable.
08-10 13:33:25.695  6994  6994 D BluetoothAdapterApp: Loading JNI Library
,08-10 13:33:25.699  1031  2016 I ActivityManager: Killing 6450:com.lge.email/u0a23 (adj 15): empty #17
08-10 13:33:25.731  6994  6994 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@3d3d8e2a Instance Count = 1
,08-10 13:33:25.741  1031  1774 W libprocessgroup: failed to open /acct/uid_10023/pid_6450/cgroup.procs: No such file or directory
08-10 13:33:25.744  6994  6994 D BluetoothAdapterApp: onCreate
08-10 13:33:25.746  6933  6933 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-10 13:33:25.747  6933  6933 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,08-10 13:33:25.747  6933  6933 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-10 13:33:25.769  6994  6994 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-10 13:33:25.770  6994  6994 D ProfileConfigQcom: Adding HeadsetService
08-10 13:33:25.770  6994  6994 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-10 13:33:25.771  6994  6994 D ProfileConfigQcom: Adding A2dpService
08-10 13:33:25.771  6994  6994 D ProfileConfigQcom: [BTUI] HidService is supported
08-10 13:33:25.772  6994  6994 D ProfileConfigQcom: Adding HidService
08-10 13:33:25.773  6994  6994 D ProfileConfigQcom: [BTUI] HealthService is supported
08-10 13:33:25.773  6994  6994 D ProfileConfigQcom: Adding HealthService
08-10 13:33:25.774  6994  6994 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-10 13:33:25.775  6994  6994 D ProfileConfigQcom: [BTUI] PanService is supported
,08-10 13:33:25.775  6994  6994 D ProfileConfigQcom: Adding PanService
,08-10 13:33:25.776  6994  6994 D ProfileConfigQcom: [BTUI] GattService is supported
08-10 13:33:25.776  6994  6994 D ProfileConfigQcom: Adding GattService
,08-10 13:33:25.777  6994  6994 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-10 13:33:25.777  6994  6994 D ProfileConfigQcom: Adding BluetoothMapService
08-10 13:33:25.778  6994  6994 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-10 13:33:25.780  6994  6994 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-10 13:33:25.782  6994  6994 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-10 13:33:25.783  6994  6994 V BluetoothPbapReceiver: ***********state = 10
08-10 13:33:25.784  6994  6994 V LGMDMManagerInternal: Create singleton instance
08-10 13:33:25.784  6933  6933 D LgDataFeature: LgDataFeature() Constructor: none
08-10 13:33:25.785  6933  6933 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-10 13:33:25.791  6933  6933 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
,08-10 13:33:25.792  6933  6933 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-10 13:33:25.792  6933  6933 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-10 13:33:25.792  6933  6933 V SoundPool: doLoad: loading sample sampleID=1
08-10 13:33:25.793  6933  6933 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-10 13:33:25.795  6933  7026 V SoundPool: Start decode
08-10 13:33:25.795  6933  7026 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-10 13:33:25.796  6596  6596 D UEI.SmartControl: QS Service created
08-10 13:33:25.797   310   310 V MediaPlayerService: decode(23, 10857164, 17813)
08-10 13:33:25.797   310   310 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-10 13:33:25.797   310   310 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-10 13:33:25.797   310   310 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-10 13:33:25.797   310   310 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-10 13:33:25.797   310   310 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-10 13:33:25.797   310   310 V MediaPlayerService: player type = 3
08-10 13:33:25.797   310   310 V AwesomePlayer: AwesomePlayer create()
08-10 13:33:25.798   310   310 V AwesomePlayer: reset_l() 
08-10 13:33:25.798   310   310 V AwesomePlayer: cancelPlayerEvents
08-10 13:33:25.798   310   310 V AwesomePlayer: setAudioSink() 
08-10 13:33:25.798   310   310 V AwesomePlayer: reset_l() 
08-10 13:33:25.798   310   310 V AudioCache: notify(0xb1432f00, 8, 0, 0)
08-10 13:33:25.798   310   310 V AudioCache: ignored
08-10 13:33:25.798   310   310 V AwesomePlayer: cancelPlayerEvents
08-10 13:33:25.798   310   310 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-10 13:33:25.798   310   310 V AwesomePlayer: setDataSource_l dataSource
08-10 13:33:25.798   310   310 V LGParserOSAL: SniffLGParser start
08-10 13:33:25.798   310   310 V LGParserOSAL: MainType:5, SubType=0
08-10 13:33:25.798   310   310 V LGParserOSAL: #### check Mime : application/ogg
08-10 13:33:25.798   310   310 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-10 13:33:25.798   310   310 E MediaExtractor: Use LGExtractor :application/ogg 
08-10 13:33:25.802  6933  6933 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-10 13:33:25.815  6933  6933 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-10 13:33:25.815  6933  6933 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-10 13:33:25.827  6933  6933 V LGMDMManager: Create singleton instance
,08-10 13:33:25.833   310   310 V LGParserOSAL: supported mime: application/ogg
08-10 13:33:25.833   310   310 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-10 13:33:25.833   310   310 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-10 13:33:25.833  6596  6596 I UEI.SmartControl: Service initServices...
08-10 13:33:25.833   310   310 V AwesomePlayer: mBitrate = -1 bits/sec
08-10 13:33:25.833   310   310 V AwesomePlayer: AudioTrack Setting
08-10 13:33:25.833   310   310 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-10 13:33:25.833   310   310 V AwesomePlayer: setAudioSource() 
08-10 13:33:25.833   310   310 V MediaPlayerService: prepare
08-10 13:33:25.833   310   310 V AwesomePlayer: prepareAsync_l() 
08-10 13:33:25.834   310   310 V MediaPlayerService: wait for prepare
08-10 13:33:25.834   310  7027 V AwesomePlayer: onPrepareAsyncEvent() 
08-10 13:33:25.834   310  7027 V AwesomePlayer: initAudioDecoder() 
08-10 13:33:25.834   310  7027 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-10 13:33:25.834   310  7027 V AudioSystem: isOffloadSupported()
08-10 13:33:25.834   310  7027 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-10 13:33:25.834   310  7027 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-10 13:33:25.834   310  7027 I AudioFlinger: isAudioPlaybackHookOn() false
08-10 13:33:25.834   310  7027 V AwesomePlayer: getUseOffload() = 0 
08-10 13:33:25.834   310  7027 V OMXCodec: OMXCodec::Create
08-10 13:33:25.834   310  7027 V OMXCodec: findMatchingCodecs()
08-10 13:33:25.834   310  7027 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-10 13:33:25.834   310  7027 V OMXCodec: matchingCodecs.size()=1
08-10 13:33:25.834   310  7027 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-10 13:33:25.835   310  7027 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-10 13:33:25.835  6596  6596 D UEI.SmartControl: QS start get config
08-10 13:33:25.835   310  7027 V LGCodecAdapter: LG Codec Adapter start
08-10 13:33:25.835   310  7027 V OMXCodec: OMXCodec Createtor
08-10 13:33:25.835   310  7027 V OMXCodec: setComponentRole
08-10 13:33:25.835   310  7027 V OMXCodec: configureCodec protected=0
08-10 13:33:25.836   310  7027 V LGCodecAdapter: called getLGCodecSpecificData
08-10 13:33:25.836   310  7027 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-10 13:33:25.836   310  7027 V LGCodecOSAL: Called LGconfigureCodecMETA
08-10 13:33:25.836   310  7027 V LGCodecOSAL: Called LGconfigureCodecMSG
08-10 13:33:25.836   310  7027 V LGCodecOSAL: Not support LGCodec
08-10 13:33:25.836   310  7027 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-10 13:33:25.836   310  7027 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-10 13:33:25.836   310  7027 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-10 13:33:25.836   310  7027 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-10 13:33:25.836   310  7027 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-10 13:33:25.836   310  7027 V AudioSystem: isOffloadSupported()
08-10 13:33:25.836   310  7027 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-10 13:33:25.836   310  7027 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-10 13:33:25.836   310  7027 V OMXCodec: [OMX.google.vorbis.de,coder] start mState=1
08-10 13:33:25.836   310  7027 V OMXCodec: init()
08-10 13:33:25.836   310  7027 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-10 13:33:25.836   310  7027 V OMXCodec: allocateBuffers
08-10 13:33:25.836   310  7027 V OMXCodec: allocateBuffersOnPort portIndex=0
08-10 13:33:25.836   310  7027 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-10 13:33:25.836   310  7027 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f78d0 on input port
08-10 13:33:25.836   310  7027 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7920 on input port
08-10 13:33:25.836   310  7027 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on input port
08-10 13:33:25.836   310  7027 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on input port
08-10 13:33:25.836   310  7027 V OMXCodec: allocateBuffersOnPort portIndex=1
08-10 13:33:25.836   310  7027 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-10 13:33:25.836   310  7027 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on output port
08-10 13:33:25.837   310  7027 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on output port
08-10 13:33:25.837   310  7027 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d80 on output port
08-10 13:33:25.837   310  7027 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57bd2e0 on output port
08-10 13:33:25.837   310  7027 V OMXCodec: init() mAsyncCompletion wait!!! 
08-10 13:33:25.837   310  7029 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-10 13:33:25.837   310  7029 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-10 13:33:25.837   310  7029 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-10 13:33:25.837   310  7027 V OMXCodec: init() mAsyncCompletion wait!!! 
08-10 13:33:25.837   310  7029 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-10 13:33:25.837   310  7029 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-10 13:33:25.837   310  7029 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-10 13:33:25.837   310  7027 V OMXCodec: init() mAsyncCompletion wait free! 
08-10 13:33:25.837   310  7027 V AwesomePlayer: finishAsyncPrepare_l() ,
08-10 13:33:25.837   310  7027 V AudioCache: notify(0xb1432f00, 5, 0, 0)
08-10 13:33:25.837   310  7027 V AudioCache: ignored
08-10 13:33:25.837   310  7027 V AudioCache: notify(0xb1432f00, 1, 0, 0)
,08-10 13:33:25.837   310  7027 V AudioCache: prepared
,08-10 13:33:25.837   310   310 V AudioCache: wait - success
08-10 13:33:25.837   310   310 V MediaPlayerService: start
08-10 13:33:25.837   310   310 V AwesomePlayer: play_l() 
,08-10 13:33:25.837   310   310 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-10 13:33:25.837   310   310 V AwesomePlayer: createAudioPlayer_l
08-10 13:33:25.837   310   310 V AwesomePlayer: seekAudioIfNecessary_l() 
08-10 13:33:25.837   310   310 V AwesomePlayer: startAudioPlayer_l() ,
,08-10 13:33:25.837   310   310 D AudioPlayer: start of Playback, useOffload 0
08-10 13:33:25.837   310   310 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-10 13:33:25.837   310   310 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-10 13:33:25.839   310  7029 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000),
08-10 13:33:25.839   310  7029 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1),
,08-10 13:33:25.839   310  7029 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7,
08-10 13:33:25.839   310  7029 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-10 13:33:25.839   310  7029 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-10 13:33:25.839   310  7029 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-10 13:33:25.839   310  7029 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884768
08-10 13:33:25.839   310  7029 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
,08-10 13:33:25.840   310  7029 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885328
08-10 13:33:25.840   310  7029 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-10 13:33:25.840   310  7029 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885568
08-10 13:33:25.840   310  7029 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-10 13:33:25.840   310  7029 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044791008
08-10 13:33:25.840   310  7029 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
,08-10 13:33:25.840   310  7029 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-10 13:33:25.840   310  7029 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-10 13:33:25.840   310  7029 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-10 13:33:25.840   310  7029 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-10 13:33:25.840   310  7029 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-10 13:33:25.841   310  7029 V OMXCodec: allocateBuffersOnPort portIndex=1
08-10 13:33:25.841   310  7029 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port,
08-10 13:33:25.841   310  7029 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d80 on output port
08-10 13:33:25.841   310  7029 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on output port
08-10 13:33:25.841   310  7029 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on output port
08-10 13:33:25.841   310  7029 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb000f970 on output port
08-10 13:33:25.841   310  7029 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-10 13:33:25.841   310  7029 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
,08-10 13:33:25.842   310   310 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-10 13:33:25.843   310   310 V AudioCache: notify(0xb1432f00, 6, 0, 0)
08-10 13:33:25.843   310   310 V AudioCache: ignored
08-10 13:33:25.843   310  7030 V AudioCache: write(0xb16f6000, 4096)
08-10 13:33:25.843   310   310 V MediaPlayerService: wait for playback complete
08-10 13:33:25.843   310  7030 V AudioCache: memcpy(0xac300000, 0xb16f6000, 4096),
08-10 13:33:25.844   310  7030 V AudioCache: write(0xb16f6000, 4096)
08-10 13:33:25.844   310  7030 V AudioCache: memcpy(0xac301000, 0xb16f6000, 4096)
08-10 13:33:25.844   310  7030 V AudioCache: write(0xb16f6000, 4096)
08-10 13:33:25.844   310  7030 V AudioCache: memcpy(0xac302000, 0xb16f6000, 4096)
08-10 13:33:25.845   310  7030 V AudioCache: write(0xb16f6000, 4096)
08-10 13:33:25.845   310  7030 V AudioCache: memcpy(0xac303000, 0xb16f6000, 4096)
,08-10 13:33:25.845   310  7030 V AudioCache: write(0xb16f6000, 4096)
08-10 13:33:25.845   310  7030 V AudioCache: memcpy(0xac304000, 0xb16f6000, 4096)
08-10 13:33:25.846   310  7030 V AudioCache: write(0xb16f6000, 4096)
08-10 13:33:25.846   310  7030 V AudioCache: memcpy(0xac305000, 0xb16f6000, 4096)
08-10 13:33:25.846   310  7030 V AudioCache: write(0xb16f6000, 4096)
,08-10 13:33:25.846   310  7030 V AudioCache: memcpy(0xac306000, 0xb16f6000, 4096)
08-10 13:33:25.847   310  7030 V AudioCache: write(0xb16f6000, 4096)
08-10 13:33:25.847   310  7030 V AudioCache: memcpy(0xac307000, 0xb16f6000, 4096)
08-10 13:33:25.847   310  7030 V AudioCache: write(0xb16f6000, 4096)
08-10 13:33:25.847   310  7030 V AudioCache: memcpy(0xac308000, 0xb16f6000, 4096)
08-10 13:33:25.848   310  7030 V AudioCache: write(0xb16f6000, 4096),
08-10 13:33:25.848   310  7030 V AudioCache: memcpy(0xac309000, 0xb16f6000, 4096)
08-10 13:33:25.848   310  7030 V AudioCache: write(0xb16f6000, 4096)
08-10 13:33:25.848   310  7030 V AudioCache: memcpy(0xac30a000, 0xb16f6000, 4096)
08-10 13:33:25.849   310  7030 V AudioCache: write(0xb16f6000, 4096)
08-10 13:33:25.849   310  7030 V AudioCache: memcpy(0xac30b000, 0xb16f6000, 4096)
08-10 13:33:25.849   310  7030 V AudioCache: write(0xb16f6000, 4096),
08-10 13:33:25.849   310  7030 V AudioCache: memcpy(0xac30c000, 0xb16f6000, 4096)
08-10 13:33:25.850   310  7030 V AudioCache: write(0xb16f6000, 4096)
08-10 13:33:25.850   310  7030 V AudioCache: memcpy(0xac30d000, 0xb16f6000, 4096)
08-10 13:33:25.850   310  7030 V AudioCache: write(0xb16f6000, 4096)
08-10 13:33:25.850   310  7030 V AudioCache: memcpy(0xac30e000, 0xb16f6000, 4096)
,08-10 13:33:25.850   310  7030 V AudioCache: write(0xb16f6000, 4096)
08-10 13:33:25.850   310  7030 V AudioCache: memcpy(0xac30f000, 0xb16f6000, 4096)
08-10 13:33:25.851   310  7030 V AudioCache: write(0xb16f6000, 4096)
08-10 13:33:25.851   310  7030 V AudioCache: memcpy(0xac310000, 0xb16f6000, 4096)
08-10 13:33:25.851   310  7030 V AudioCache: write(0xb16f6000, 4096)
,08-10 13:33:25.851   310  7030 V AudioCache: memcpy(0xac311000, 0xb16f6000, 4096)
08-10 13:33:25.852   310  7030 V AudioCache: write(0xb16f6000, 4096)
08-10 13:33:25.852   310  7030 V AudioCache: memcpy(0xac312000, 0xb16f6000, 4096)
08-10 13:33:25.852   310  7030 V AudioCache: write(0xb16f6000, 4096)
08-10 13:33:25.852   310  7030 V AudioCache: memcpy(0xac313000, 0xb16f6000, 4096)
08-10 13:33:25.860   310  7030 V AudioCache: write(0xb16f6000, 4096)
,08-10 13:33:25.860   310  7030 V AudioCache: memcpy(0xac314000, 0xb16f6000, 4096)
08-10 13:33:25.861   310  7030 V AudioCache: write(0xb16f6000, 4096)
08-10 13:33:25.861   310  7030 V AudioCache: memcpy(0xac315000, 0xb16f6000, 4096)
08-10 13:33:25.861   310  7030 V AudioCache: write(0xb16f6000, 4096)
08-10 13:33:25.861   310  7030 V AudioCache: memcpy(0xac316000, 0xb16f6000, 4096)
,08-10 13:33:25.861   310  7030 V AudioCache: write(0xb16f6000, 4096)
08-10 13:33:25.861   310  7030 V AudioCache: memcpy(0xac317000, 0xb16f6000, 4096)
08-10 13:33:25.862   310  7030 V AudioCache: write(0xb16f6000, 4096)
08-10 13:33:25.862   310  7030 V AudioCache: memcpy(0xac318000, 0xb16f6000, 4096)
08-10 13:33:25.863   310  7030 V AudioCache: write(0xb16f6000, 4096)
08-10 13:33:25.863   310  7030 V AudioCache: memcpy(0xac319000, 0xb16f6000, 4096)
08-10 13:33:25.863   310  7030 V AudioCache: write(0xb16f6000, 4096)
08-10 13:33:25.863   310  7030 V AudioCache: memcpy(0xac31a000, 0xb16f6000, 4096)
08-10 13:33:25.863   310  7030 V AudioCache: write(0xb16f6000, 4096)
08-10 13:33:25.863   310  7030 V AudioCache: memcpy(0xac31b000, 0xb16f6000, 4096)
08-10 13:33:25.864   310  7030 V AudioCache: write(0xb16f6000, 4096)
08-10 13:33:25.864   310  7030 V AudioCache: memcpy(0xac31c000, 0xb16f6000, 4096)
08-10 13:33:25.864   310  7030 V AudioCache: write(0xb16f6000, 4096)
08-10 13:33:25.864   310  7030 V AudioCache: memcpy(0xac31d000, 0xb16f6000, 4096)
08-10 13:33:25.865   310  7030 V AudioCache: write(0xb16f6000, 4096)
,08-10 13:33:25.865   310  7030 V AudioCache: memcpy(0xac31e000, 0xb16f6000, 4096)
08-10 13:33:25.865   310  7030 V AudioCache: write(0xb16f6000, 4096)
08-10 13:33:25.865   310  7030 V AudioCache: memcpy(0xac31f000, 0xb16f6000, 4096)
08-10 13:33:25.866   310  7030 V AudioCache: write(0xb16f6000, 4096)
08-10 13:33:25.866   310  7030 V AudioCache: memcpy(0xac320000, 0xb16f6000, 4096)
08-10 13:33:25.866   310  7030 V AudioCache: write(0xb16f6000, 4096)
08-10 13:33:25.866   310  7030 V AudioCache: memcpy(0xac321000, 0xb16f6000, 4096)
08-10 13:33:25.866   310  7030 V AudioCache: write(0xb16f6000, 4096)
08-10 13:33:25.866   310  7030 V AudioCache: memcpy(0xac322000, 0xb16f6000, 4096)
08-10 13:33:25.867   310  7030 V AudioCache: write(0xb16f6000, 4096)
08-10 13:33:25.867   310  7030 V AudioCache: memcpy(0xac323000, 0xb16f6000, 4096)
08-10 13:33:25.867   310  7030 V AudioCache: write(0xb16f6000, 4096)
08-10 13:33:25.867   310  7030 V AudioCache: memcpy(0xac324000, 0xb16f6000, 4096)
08-10 13:33:25.868   310  7030 V AudioCache: write(0xb16f6000, 4096)
08-10 13:33:25.868   310  7030 V AudioCache: memcpy(0xac325000, 0xb16f6000, 4096)
08-10 13:33:25.868   310  7030 V AudioCache: write(0xb16f6000, 4096)
08-10 13:33:25.868   310  7030 V AudioCache: memcpy(0xac326000, 0xb16f6000, 4096)
08-10 13:33:25.868   310  7030 V AudioCache: write(0xb16f6000, 4096)
08-10 13:33:25.868   310  7030 V AudioCache: memcpy(0xac327000, 0xb16f6000, 4096)
08-10 13:33:25.869   310  7030 V AudioCache: write(0xb16f6000, 4096)
08-10 13:33:25.869   310  7030 V AudioCache: memcpy(0xac328000, 0xb16f6000, 4096)
08-10 13:33:25.869   310  7030 V AudioCache: write(0xb16f6000, 4096)
08-10 13:33:25.869   310  7030 V AudioCache: memcpy(0xac329000, 0xb16f6000, 4096)
,08-10 13:33:25.870   310  7030 V AudioCache: write(0xb16f6000, 4096)
08-10 13:33:25.870   310  7030 V AudioCache: memcpy(0xac32a000, 0xb16f6000, 4096)
08-10 13:33:25.870   310  7030 V AudioCache: write(0xb16f6000, 4096)
08-10 13:33:25.870   310  7030 V AudioCache: memcpy(0xac32b000, 0xb16f6000, 4096)
08-10 13:33:25.871   310  7030 V AudioCache: write(0xb16f6000, 4096)
08-10 13:33:25.871   310  7030 V AudioCache: memcpy(0xac32c000, 0xb16f6000, 4096)
08-10 13:33:25.871   310  7030 V AudioCache: write(0xb16f6000, 4096)
08-10 13:33:25.871   310  7030 V AudioCache: memcpy(0xac32d000, 0xb16f6000, 4096)
08-10 13:33:25.871   310  7030 V AudioCache: write(0xb16f6000, 4096)
08-10 13:33:25.871   310  7030 V AudioCache: memcpy(0xac32e000, 0xb16f6000, 4096)
08-10 13:33:25.872   310  7030 V AudioCache: write(0xb16f6000, 4096)
08-10 13:33:25.872   310  7030 V AudioCache: memcpy(0xac32f000, 0xb16f6000, 4096)
08-10 13:33:25.872   310  7030 V AudioCache: write(0xb16f6000, 4096)
08-10 13:33:25.872   310  7030 V AudioCache: memcpy(0xac330000, 0xb16f6000, 4096)
08-10 13:33:25.873   310  7030 V AudioCache: write(0xb16f6000, 4096)
08-10 13:33:25.873   310  7030 V AudioCache: memcpy(0xac331000, 0xb16f6000, 4096)
08-10 13:33:25.873   310  7029 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-10 13:33:25.873   310  7030 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-10 13:33:25.873   310  7030 V AwesomePlayer: postAudioEOS() 
08-10 13:33:25.873   310  7030 V AudioCache: write(0xb16f6000, 280)
08-10 13:33:25.873   310  7030 V AudioCache: memcpy(0xac332000, 0xb16f6000, 280)
08-10 13:33:25.875   310  7027 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-10 13:33:25.875   310  7027 V AwesomePlayer: onStreamDone
08-10 13:33:25.875   310  7027 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-10 13:33:25.875   310  7027 V AudioCache: notify(0xb1432f00, 2, 0, 0)
08-10 13:33:25.875   310  7027 V AudioCache: playback complete
08-10 13:33:25.875   310  7027 V AwesomePlayer: pause_l() 
08-10 13:33:25.875   310   310 V AudioCache: wait - success
08-10 13:33:25.875   310  7027 V AudioCache: notify(0xb1432f00, 7, 0, 0)
08-10 13:33:25.875   310  7027 V AudioCache: ignored
08-10 13:33:25.875   310   310 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-10 13:33:25.875   310  7027 V AwesomePlayer: cancelPlayerEvents
08-10 13:33:25.875   310  7027 D AudioPlayer: Pause Playback at 1068125
08-10 13:33:25.876   310   310 V AwesomePlayer: reset_l() 
08-10 13:33:25.876   310   310 V AudioCache: notify(0xb1432f00, 8, 0, 0)
08-10 13:33:25.876   310   310 V AudioCache: ignored
08-10 13:33:25.876   310   310 V AwesomePlayer: cancelPlayerEvents
08-10 13:33:25.876   310   310 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-10 13:33:25.876   310   310 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-10 13:33:25.876   310   310 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-10 13:33:25.876   310   310 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-10 13:33:25.876   310   310 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-10 13:33:25.876   310  7029 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-10 13:33:25.876   310  7029 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-10 13:33:25.876   310  7029 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-10 13:33:25.876   310  7029 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 0
08-10 13:33:25.876   310  7029 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-10 13:33:25.876   310  7029 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f79c0 on port 0
08-10 13:33:25.876   310  7029 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-10 13:33:25.876   310  7029 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7920 on port 0
08,-10 13:33:25.876   310  7029 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-10 13:33:25.876   310  7029 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f78d0 on port 0
08-10 13:33:25.876   310  7029 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-10 13:33:25.876   310  7029 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-10 13:33:25.876   310  7029 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb000f970 on port 1
08-10 13:33:25.877   310  7029 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-10 13:33:25.877   310  7029 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 1
08-10 13:33:25.877   310  7029 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-10 13:33:25.877   310  7029 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c90 on port 1
08-10 13:33:25.877   310  7029 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-10 13:33:25.877   310  7029 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7d80 on port 1
08-10 13:33:25.877   310  7029 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-10 13:33:25.877   310  7029 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-10 13:33:25.877   310   310 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-10 13:33:25.877   310   310 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-10 13:33:25.877   310  7029 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-10 13:33:25.877   310  7029 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-10 13:33:25.877   310  7029 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-10 13:33:25.877   310   310 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-10 13:33:25.877   310   310 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-10 13:33:25.877   310   310 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-10 13:33:25.878   310   310 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-10 13:33:25.878   310   310 D AudioPlayer: AudioPlayer releasing audio source
08-10 13:33:25.878   310   310 D AudioPlayer: AudioPlayer done releasing audio source
08-10 13:33:25.878   310   310 V AwesomePlayer: reset_l() 
08-10 13:33:25.878   310   310 V AwesomePlayer: cancelPlayerEvents
,08-10 13:33:25.878   310   310 V AwesomePlayer: ~AwesomePlayer call
,08-10 13:33:25.878   310   310 V AwesomePlayer: reset_l() 
08-10 13:33:25.878   310   310 V AwesomePlayer: cancelPlayerEvents
08-10 13:33:25.879  6933  7026 V SoundPool: close(31)
08-10 13:33:25.879  6933  7026 V SoundPool: pointer = 0x9fe38000, size = 205080, sampleRate = 48000, numChannels = 2
08-10 13:33:25.888  2193  2193 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-10 13:33:25.891  6876  6876 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,08-10 13:33:25.897  6876  6876 D BluetoothPermissionRequest: onReceive
08-10 13:33:25.899  6876  6876 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-10 13:33:25.899  6876  6876 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-10 13:33:25.901  6876  6876 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-10 13:33:25.903  6994  6994 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,08-10 13:33:25.906  6994  6994 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-10 13:33:25.908  6994  6994 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-10 13:33:25.908  6994  6994 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-10 13:33:25.908  6994  6994 V BluetoothSapReceiver: SapReceiver onReceive 
08-10 13:33:25.909  6994  6994 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-10 13:33:25.909  6994  6994 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-10 13:33:25.914  6950  6950 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-10 13:33:25.914  6933  6933 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-10 13:33:25.915  6933  6933 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,08-10 13:33:25.918  6933  6933 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:9070
08-10 13:33:26.111  6596  6596 I UEI.SmartControl: Supports setup maps: true
08-10 13:33:26.114  6596  6596 D UEI.SmartControl: QS start statue = true Error code = 0
08-10 13:33:26.114  6596  6596 I UEI.SmartControl: QS version = v2.7.10.1_RC1
,08-10 13:33:26.114  6596  6596 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-10 13:33:26.114  6596  6596 I UEI.SmartControl: ### init IR Blaster...
08-10 13:33:26.118  6596  6596 D serial_port: Configuring serial port
08-10 13:33:26.119  6596  6596 E UEI.SmartControl: UEIBLaster setting for 616
08-10 13:33:26.119  6596  6596 I UEI.SmartControl: Setting serial record hearder size = 2
08-10 13:33:26.119  6596  6596 I UEI.SmartControl: configuring settings for MAXQ616
08-10 13:33:26.119  6596  6596 I UEI.SmartControl: Get version...
08-10 13:33:26.138  6596  7033 D UEI.SmartControl: serial port data available: 21
,08-10 13:33:26.167  6596  6596 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-10 13:33:26.167  6596  6596 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-10 13:33:26.167  6596  6596 I UEI.SmartControl: QS saving settings...
08-10 13:33:26.169  6596  6596 D UEI.SmartControl: IR Blaster version: 25672567
,08-10 13:33:26.186  6596  7033 D UEI.SmartControl: serial port data available: 4
,08-10 13:33:26.219  6596  7042 I UEI.SmartControl: Device manager: loading config....
08-10 13:33:26.220  6596  7042 D UEI.SmartControl: ----------- loading internal config...
08-10 13:33:26.221  6596  6596 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-10 13:33:26.230  6596  6596 E UEI.SmartControl: Services init done
08-10 13:33:26.230  6596  6596 D UEI.SmartControl: QS Service init finished
08-10 13:33:26.233  6596  6596 D UEI.SmartControl: QS Service version name: 2.1.91
08-10 13:33:26.233  6596  6596 D UEI.SmartControl: QS Service version code: 201091
08-10 13:33:26.234  6596  6596 D UEI.SmartControl: Service requested: Control
08-10 13:33:26.236  6596  7042 E UEI.SmartControl: Loading SETTINGS...
08-10 13:33:26.240  6596  6596 D UEI.SmartControl: Request IControl service: devices are loaded...
,08-10 13:33:26.244  6596  6596 D UEI.SmartControl: Internal service binding...
08-10 13:33:26.245  6933  6933 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-10 13:33:26.247  6596  6612 I UEI.SmartControl: ------ IControl API: 11
08-10 13:33:26.247  6596  6612 D UEI.SmartControl: File observer start...
08-10 13:33:26.248  6596  6612 E UEI.SmartControl: IR Port is disabled: false
08-10 13:33:26.248  6596  6612 D UEI.SmartControl: Starting file observer...
08-10 13:33:26.249  6596  6612 I UEI.SmartControl: Registering callback...
08-10 13:33:26.250  6596  6611 I UEI.SmartControl: ------ IControl API: 19
08-10 13:33:26.250  6596  6611 I UEI.SmartControl: Registering Services Ready callback...
08-10 13:33:26.252  6596  7042 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-10 13:33:26.277  6596  7041 I UEI.SmartControl: Notify AllClients services are ready: 0
08-10 13:33:26.277  6596  7041 D UEI.SmartControl: -----service ready thread exits
08-10 13:33:26.277  6933  6948 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
,08-10 13:33:26.278  6933  7024 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-10 13:33:26.278  6933  7024 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-10 13:33:26.279  6933  6933 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-10 13:33:26.279  6933  6933 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-10 13:33:26.280  6596  6612 I UEI.SmartControl: ------ IControl API: 8
08-10 13:33:26.281  6933  6933 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-10 13:33:26.282  6933  6933 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-10 13:33:26.282  6933  6933 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-10 13:33:26.283  6933  6933 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-10 13:33:26.283  6933  6933 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-10 13:33:26.284  6933  6933 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-10 13:33:26.285  6933  6933 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-10 13:33:26.287  6933  6933 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-10 13:33:26.288  6933  6933 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-10 13:33:26.289  6933  6933 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-10 13:33:26.289  6933  6933 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,08-10 13:33:26.290  6933  6933 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-10 13:33:26.291  6933  6933 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-10 13:33:26.292  6933  6933 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-10 13:33:26.294  6933  6933 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1470828806293]
08-10 13:33:26.298  6933  6933 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-10 13:33:26.299  1031  2373 I ActivityManager: Killing 2173:com.lge.music/u0a34 (adj 15): empty #17
08-10 13:33:26.319   310  1386 V AudioFlinger: 2173 died, releasing its sessions
08-10 13:33:26.319   310  1386 V AudioFlinger:  pid 1856 @ 0
08-10 13:33:26.319   310  1386 V AudioFlinger:  pid 3485 @ 1
08-10 13:33:26.319   310  1386 V AudioFlinger:  pid 3485 @ 2
,08-10 13:33:26.325  6933  7044 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
08-10 13:33:26.342  1031  2373 I ActivityManager: Killing 6092:com.android.gallery3d/u0a27 (adj 15): empty #18
,08-10 13:33:26.374  1031  1047 W libprocessgroup: failed to open /acct/uid_10034/pid_2173/cgroup.procs: No such file or directory
,08-10 13:33:26.377  1031  1908 W libprocessgroup: failed to open /acct/uid_10027/pid_6092/cgroup.procs: No such file or directory
08-10 13:33:26.384  6933  6933 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,08-10 13:33:26.385  6933  6933 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-10 13:33:26.385  6933  6933 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-10 13:33:26.386  6933  6933 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-10 13:33:26.386  6933  6933 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-10 13:33:26.386  6933  6933 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-10 13:33:26.387  6933  6933 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
,08-10 13:33:26.397  6933  6933 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-10 13:33:27.469  1031  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-10 13:33:27.484  1031  1096 D Tethering: MasterInitialState.processMessage what=3
08-10 13:33:27.496  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 13:33:27.501  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 13:33:27.502  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 13:33:27.506  1031  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-10 13:33:27.509  1031  1096 D Tethering: MasterInitialState.processMessage what=3
08-10 13:33:27.519  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 13:33:27.523  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 13:33:27.525  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 13:33:27.525  1031  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-10 13:33:27.527  6357  6357 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-10 13:33:27.530  6357  6900 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-10 13:33:27.543  5771  5771 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-10 13:33:27.552  5771  5771 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-10 13:33:27.572  2193  2193 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-10 13:33:27.612  1031  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-10 13:33:27.650  1031  1962 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7060 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-10 13:33:27.655  1031  1377 V AlarmManager: ELAPSED_WAKEUP set : Alarm{2fc65f9c type 2 when 354837 com.google.android.gms} when 354837
08-10 13:33:27.657  1031  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 13:33:27.657  1031  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-10 13:33:27.749  7060  7060 I AppUp4:AppBoxCP: onCreate
08-10 13:33:27.750  7060  7060 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,08-10 13:33:27.760  7060  7060 I AppUp4:DB:  setFingerPrint start
,08-10 13:33:27.761  7060  7060 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
,08-10 13:33:27.769  7060  7060 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-10 13:33:27.770  7060  7060 I AppUp4:DB:  SDK version = 21
08-10 13:33:27.770  7060  7060 I AppUp4:DB:  beforefinger == newfinger no write in DB
,08-10 13:33:27.773  7060  7060 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-10 13:33:27.776  7060  7060 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-10 13:33:27.776  7060  7060 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-10 13:33:27.781  7060  7060 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-10 13:33:27.782  7060  7060 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-10 13:33:27.790  7060  7060 I AppUp4:CustModeStarterReceiver: onReceive
,08-10 13:33:27.834  7060  7060 D LgDataFeature: LgDataFeature() Constructor: none
,08-10 13:33:27.834  7060  7060 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-10 13:33:27.844  7060  7060 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@866a964
08-10 13:33:27.845  7060  7060 D AppUp4:CustFacade: isCustomizationCompleted : false
08-10 13:33:27.845  7060  7060 D AppUp4:CustFacade: isPhone : true
08-10 13:33:27.846  7060  7060 D AppUp4:CustModeStarterReceiver: begin check event
08-10 13:33:27.847  7060  7060 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-10 13:33:27.848  7060  7060 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-10 13:33:27.849  7060  7081 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-10 13:33:27.850  7060  7081 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-10 13:33:27.850  7060  7081 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
,08-10 13:33:27.854  1031  1578 I ActivityManager: Killing 6489:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,08-10 13:33:27.936  1031  1046 W libprocessgroup: failed to open /acct/uid_10061/pid_6489/cgroup.procs: No such file or directory
,08-10 13:33:27.939  4325  4325 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-10 13:33:27.940  4325  4325 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-10 13:33:27.944  4325  4325 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-10 13:33:27.946  4325  4325 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-10 13:33:27.961  4325  7087 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-10 13:33:27.962  4325  7088 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-10 13:33:27.963  4325  7088 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-10 13:33:27.993  1031  1926 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7089 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-10 13:33:28.093  7089  7089 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-10 13:33:28.094  7089  7089 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-10 13:33:28.095  7089  7089 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-10 13:33:28.096  7089  7089 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-10 13:33:28.190  7089  7089 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-10 13:33:28.206  7089  7089 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-10 13:33:28.257  7089  7089 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-10 13:33:28.301  7089  7089 D LgDataFeature: LgDataFeature() Constructor: none
,08-10 13:33:28.301  7089  7089 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-10 13:33:28.462  7089  7089 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-10 13:33:28.505  3485  3485 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-10 13:33:28.505  3485  3485 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-10 13:33:28.505  3485  3485 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-10 13:33:28.562  1031  1890 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7117 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-10 13:33:28.573  6971  7115 W FormManager: Network not available. Please check & try again.
08-10 13:33:28.576  6971  7116 V FormManager: Network unavailable.
08-10 13:33:28.580  6971  7116 V FormManager: Network unavailable.
,08-10 13:33:28.606  7089  7089 I HubEmail: JNI_OnLoad()
08-10 13:33:28.606  7089  7089 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-10 13:33:28.606  7089  7089 I HubEmail: registerNatives()
08-10 13:33:28.606  7089  7089 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-10 13:33:28.606  7089  7089 I HubEmail: registerNativeMethods()
08-10 13:33:28.606  7089  7089 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-10 13:33:28.606  7089  7089 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,08-10 13:33:28.620  7089  7134 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-10 13:33:28.624  1031  1047 I ActivityManager: Killing 6115:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
08-10 13:33:28.700  7117  7117 D LgDataFeature: LgDataFeature() Constructor: none
08-10 13:33:28.700  7117  7117 D LgDataFeature: LgDataFeature() Constructor Done, null
08-10 13:33:28.704  7117  7117 D PhoneMonitor: Register our PhoneStateListener
,08-10 13:33:28.705  1031  1944 W libprocessgroup: failed to open /acct/uid_10080/pid_6115/cgroup.procs: No such file or directory
08-10 13:33:28.726  7117  7117 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-10 13:33:28.728  7117  7117 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-10 13:33:28.772  7117  7117 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,08-10 13:33:28.773  7117  7117 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
,08-10 13:33:28.775  7117  7117 D TelephonyAutoProfiling: [parse] Load xml
,08-10 13:33:28.782  7117  7117 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-10 13:33:28.783  7117  7117 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-10 13:33:28.783  7117  7117 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-10 13:33:28.783  7117  7117 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true,
,08-10 13:33:28.783  7117  7117 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-10 13:33:28.783  7117  7117 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
,08-10 13:33:28.783  7117  7117 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-10 13:33:28.783  7117  7117 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true,
,08-10 13:33:28.783  7117  7117 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
,08-10 13:33:28.783  7117  7117 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true,
08-10 13:33:28.784  7117  7117 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
,08-10 13:33:28.784  7117  7117 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true,
,08-10 13:33:28.784  7117  7117 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true,
,08-10 13:33:28.784  7117  7117 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
,08-10 13:33:28.784  7117  7117 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
,08-10 13:33:28.784  7117  7117 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
,08-10 13:33:28.784  7117  7117 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
08-10 13:33:28.792  1031  1578 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7144 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-10 13:33:28.792  7117  7117 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-10 13:33:28.794  1031  1578 I ActivityManager: Killing 6135:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,08-10 13:33:28.843  1031  1944 W libprocessgroup: failed to open /acct/uid_10097/pid_6135/cgroup.procs: No such file or directory
,08-10 13:33:29.081  1031  1578 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7165 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
08-10 13:33:29.082  1031  1578 I ActivityManager: Killing 6554:com.lge.eula/1000 (adj 15): empty #17
,08-10 13:33:29.133  1031  1944 W libprocessgroup: failed to open /acct/uid_1000/pid_6554/cgroup.procs: No such file or directory
,08-10 13:33:29.235  1031  1774 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7182 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-10 13:33:29.236  1031  1774 I ActivityManager: Killing 6571:com.lge.bnr/1000 (adj 15): empty #17
,08-10 13:33:29.295  1031  1578 W libprocessgroup: failed to open /acct/uid_1000/pid_6571/cgroup.procs: No such file or directory
,08-10 13:33:29.341  7182  7182 I art     : Almond Protected OAT
,08-10 13:33:29.385  1031  1908 D WifiServiceImplEx: setWifiEnabled: true pid=6729, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-10 13:33:29.386  1031  1908 D WifiService: setWifiEnabled: true pid=6729, uid=10118
08-10 13:33:29.386  1031  1908 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-10 13:33:29.399  7182  7182 D WeatherApplication: removeAccount
08-10 13:33:29.400  7182  7182 D WeatherApplication: Account.length = 0
08-10 13:33:29.401  7182  7182 E WeatherApplication: OPERATOR:OPEN
08-10 13:33:29.403  1031  1031 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-10 13:33:29.404  1031  1031 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,08-10 13:33:29.404  1031  1031 D Ulp_jni : JNI:system_update. Event-4
08-10 13:33:29.405  1031  1539 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-10 13:33:29.405  1031  1539 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-10 13:33:29.408  1031  1539 E WifiUtil: wfc_util_ffile_check_copy(): pid[1031] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-10 13:33:29.408  1031  1539 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-10 13:33:29.408  1031  1539 E WifiUtil: wfc_util_ffile_check_copy(): pid[1031] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-10 13:33:29.408  1031  1539 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-10 13:33:29.409  1031  1539 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-10 13:33:29.409  1031  1539 E WifiHW  : unknown target_country: EU , set to default
08-10 13:33:29.409  1031  1539 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-10 13:33:29.409  1031  1539 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-10 13:33:29.409  1031  1539 I WifiUtil: gEnableBmps=1
08-10 13:33:29.416  7182  7182 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:33:29
08-10 13:33:29.419  7182  7182 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-10 13:33:29.419  7182  7182 D Weather.Utils: 2 : All the weather widget is gone.
,08-10 13:33:29.423  7182  7182 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-10 13:33:29.426  7182  7182 D WeatherAncestor: connectivity changed - connection : true
08-10 13:33:29.427  7182  7182 D WeatherService: 2 : isServiceAlived():false forecastCache:null
08-10 13:33:29.436  7182  7182 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-10 13:33:29.436  7182  7182 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-10 13:33:29.436  7182  7182 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
08-10 13:33:29.440  1031  1538 D LGWifiP2pService: P2pDisabledState{ when=-5ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-10 13:33:29.440  1031  1538 D LGWifiP2pService: DefaultState{ when=-5ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,08-10 13:33:29.464  7182  7182 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-10 13:33:29.465  7182  7182 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:33:29
,08-10 13:33:29.518  1031  1962 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7201 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-10 13:33:29.521  1031  1962 I ActivityManager: Killing 5818:com.android.vending/u0a44 (adj 15): empty #17
,08-10 13:33:29.621  1031  1890 W libprocessgroup: failed to open /acct/uid_10044/pid_5818/cgroup.procs: No such file or directory
08-10 13:33:29.741   278   404 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-10 13:33:29.741   278   404 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-10 13:33:29.741   278   404 W Vold    : Returning OperationFailed - no handler for errno 0
08-10 13:33:29.744  7201  7229 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,08-10 13:33:29.749   278   404 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-10 13:33:29.749   278   404 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-10 13:33:29.749   278   404 W Vold    : Returning OperationFailed - no handler for errno 0
08-10 13:33:29.750  7201  7229 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-10 13:33:29.765   278   404 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-10 13:33:29.765   278   404 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-10 13:33:29.765   278   404 W Vold    : Returning OperationFailed - no handler for errno 0
,08-10 13:33:29.769  7201  7233 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-10 13:33:29.773   278   404 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-10 13:33:29.773   278   404 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-10 13:33:29.773   278   404 W Vold    : Returning OperationFailed - no handler for errno 0
08-10 13:33:29.774  7201  7233 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-10 13:33:30.033  7201  7201 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-10 13:33:30.056  7201  7201 I LibraryLoader: Loading: webviewchromium
,08-10 13:33:30.061  7201  7201 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 7273-7278)
08-10 13:33:30.061  7201  7201 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-10 13:33:30.071  7201  7201 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3b218139}
,08-10 13:33:30.083  7201  7201 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-10 13:33:30.084  7201  7201 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,08-10 13:33:30.100  7201  7201 I BrowserStartupController: Initializing chromium process, renderers=0
08-10 13:33:30.101  7201  7201 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-10 13:33:30.115  7201  7201 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-10 13:33:30.116  7201  7201 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-10 13:33:30.116  7201  7201 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
,08-10 13:33:30.127   310  1387 V AudioPolicyService: registerClient() client 0xb0010020, uid 10093
08-10 13:33:30.128  7201  7263 W AudioManagerAndroid: Requires BLUETOOTH permission
08-10 13:33:30.138  7201  7201 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-10 13:33:30.138  7201  7201 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-10 13:33:30.138  7201  7201 I Adreno-EGL: Build Date: 12/12/14 금
08-10 13:33:30.138  7201  7201 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-10 13:33:30.138  7201  7201 I Adreno-EGL: Remote Branch: 
08-10 13:33:30.138  7201  7201 I Adreno-EGL: Local Patches: 
08-10 13:33:30.138  7201  7201 I Adreno-EGL: Reconstruct Branch: 
,08-10 13:33:30.226  7201  7201 I NSApplication: Starting up...
,08-10 13:33:30.266   306   896 D SoftapController: Softap fwReload - Ok
,08-10 13:33:30.277  1031  1539 E NetdConnector: NDC Command {52 softap fwreload wlan0 STA} took too long (864ms)
08-10 13:33:30.279   306   896 D CommandListener: Setting iface cfg
08-10 13:33:30.279   306   896 D CommandListener: Trying to bring down wlan0
08-10 13:33:30.280   306   896 D CommandListener: Clearing all IP addresses on wlan0
,08-10 13:33:30.283  1031  1539 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-10 13:33:30.284  1031  1908 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7277 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-10 13:33:30.286  1031  1908 I ActivityManager: Killing 6665:com.lge.clock/u0a10 (adj 15): empty #17
08-10 13:33:30.287  1031  1539 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-10 13:33:30.287  1031  1539 E WifiStateMachine: useWiFiOffloading() : false
08-10 13:33:30.287  1031  1539 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-10 13:33:30.272  7283  7283 W wpa_supplicant: type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-10 13:33:30.272  7283  7283 W wpa_supplicant: type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-10 13:33:30.314  7283  7283 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-10 13:33:30.348  7283  7283 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-10 13:33:30.348  7283  7283 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
08-10 13:33:30.395  1031  1096 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-10 13:33:30.396  1031  1096 D Tethering: InitialState.processMessage what=4
,08-10 13:33:30.399  1031  1539 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-10 13:33:30.399  1031  1890 W libprocessgroup: failed to open /acct/uid_10010/pid_6665/cgroup.procs: No such file or directory
08-10 13:33:30.400  1031  1539 D WifiMonitor: connecting to supplicant
,08-10 13:33:30.413  7283  7283 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-10 13:33:30.423  1031  1096 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-10 13:33:30.426  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-10 13:33:30.427  1945  1945 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-10 13:33:30.427  1031  1031 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-10 13:33:30.428  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 13:33:30.428  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 13:33:30.429  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 13:33:30.448  7277  7277 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-10 13:33:30.479  7283  7283 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-10 13:33:30.495  1031  1539 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
,08-10 13:33:30.496  1031  1539 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-10 13:33:30.497  1031  1539 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-10 13:33:30.498  1031  1539 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-10 13:33:30.499  1031  1539 E WifiStateMachine:  SupplicantStartingState CMD_STOP_SUPPLICANT_FAILED 1 0
08-10 13:33:30.500  1031  1539 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
08-10 13:33:30.501  1031  1539 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-10 13:33:30.501  1031  1539 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-10 13:33:30.502  7283  7283 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-10 13:33:30.502  7283  7283 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-10 13:33:30.502  1031  1539 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-10 13:33:30.502  1031  1539 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-10 13:33:30.503  1031  7301 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-10 13:33:30.503  1031  7301 D WifiMonitor: Dropping event because (p2p0) is stopped
08-10 13:33:30.503  1031  1539 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-10 13:33:30.503  1031  7301 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-10 13:33:30.503  1031  7301 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-10 13:33:30.503  1031  1539 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-10 13:33:30.503  1031  7301 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-10 13:33:30.503  1031  1539 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-10 13:33:30.503  1031  7301 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-10 13:33:30.504  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 13:33:30.504  1031  1539 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-10 13:33:30.504  1031  1539 E WifiStateMachine: useWiFiOffloading() : false
08-10 13:33:30.504  1031  1539 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-10 13:33:30.504  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 13:33:30.504  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 13:33:30.504  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 13:33:30.504  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-10 13:33:30.506  1945  1945 D WfdService: Waiting for WifiP2p enabling
08-10 13:33:30.506  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 13:33:30.507  1031  1031 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-10 13:33:30.507  1031  1539 D WifiNative-wlan0: doBoolean: SET update_config 1
,08-10 13:33:30.507  1031  1539 D WifiNative-wlan0: SET update_config 1: returned true
08-10 13:33:30.508  1031  1539 D WifiConfigStore: Loading config and enabling all networks 
08-10 13:33:30.508  1031  1539 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-10 13:33:30.508  1031  1539 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
,08-10 13:33:30.509  1031  1543 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-10 13:33:30.510  6729  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 13:33:30.510  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 13:33:30.510  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 13:33:30.510  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 13:33:30.510  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 13:33:30.510  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 13:33:30.510  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 13:33:30.510  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 13:33:30.510  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 13:33:30.510  6729  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 13:33:30.511  6729  6729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-10 13:33:30.512  6729  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 13:33:30.512  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 13:33:30.512  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 13:33:30.512  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 13:33:30.512  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 13:33:30.512  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 13:33:30.512  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 13:33:30.512  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 13:33:30.512  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 13:33:30.512  6729  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 13:33:30.512  6729  6729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-10 13:33:30.515  6729  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 13:33:30.515  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 13:33:30.515  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 13:33:30.515  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 13:33:30.515  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 13:33:30.515  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 13:33:30.515  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 13:33:30.515  6729  6729 V io.jxcore.node.ConnectivityMonitor:   ,  - is connected/connecting to active network: false
08-10 13:33:30.515  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 13:33:30.515  6729  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 13:33:30.515  6729  6729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-10 13:33:30.515  1031  1539 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-10 13:33:30.525  1031  1539 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-10 13:33:30.525  1031  1539 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-10 13:33:30.526  1031  1539 D WifiStateMachine: enableVerboseLogging : level 2
08-10 13:33:30.526  1031  1539 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-10 13:33:30.527  1031  1539 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-10 13:33:30.527  1031  1539 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-10 13:33:30.527  1031  1539 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-10 13:33:30.527  1031  1539 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-10 13:33:30.528  1031  1539 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-10 13:33:30.528  1031  1539 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-10 13:33:30.528  1031  1539 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-10 13:33:30.528  1031  1539 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-10 13:33:30.529  1031  1539 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-10 13:33:30.529  1031  1539 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-10 13:33:30.529  1031  1539 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-10 13:33:30.529  1031  1539 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
,08-10 13:33:30.530  1031  1539 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-10 13:33:30.531  1945  1945 D WfdsService: Supplicant Connection state is changed : true
08-10 13:33:30.531  1031  1539 D WifiStateMachine: Setting OUI to DA-A1-19
08-10 13:33:30.531  1945  2312 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-10 13:33:30.531  1031  1539 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-10 13:33:30.531  1945  2312 D WfdsService: Set the WFDS Monitor: true
08-10 13:33:30.531  1945  2312 D WfdsMonitor: WfdsMonitorThread create
08-10 13:33:30.531  1945  2312 D WfdsMonitor: WFDS Monitor is created and started
08-10 13:33:30.531  1945  2312 D WfdsService: WiFi: Supplicant connection re-established
08-10 13:33:30.532  1031  1539 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
,08-10 13:33:30.532  1031  1539 D WifiNative-HAL: Setting external_sim to 1
08-10 13:33:30.532  1031  1539 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-10 13:33:30.533  1031  1539 D WifiNative-wlan0: SET external_sim 1: returned true
08-10 13:33:30.533  1945  7302 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-10 13:33:30.533  1031  1539 I WifiNative-HAL: startHal
08-10 13:33:30.533  1031  1539 D wifi    : setting scan oui 0x9535c4c0
08-10 13:33:30.533  1031  1539 D WifiStateMachine: Setting OUI to DA-A1-19
08-10 13:33:30.533  1031  1539 I WifiNative-HAL: startHal
08-10 13:33:30.533  1945  7302 E CtrlSupplicant: Succeed to open control connection
08-10 13:33:30.533  1031  1539 D wifi    : setting scan oui 0x9535c4c0
08-10 13:33:30.533  1031  1539 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-10 13:33:30.533  1945  7302 E CtrlSupplicant: Succeed to open monitor connection
08-10 13:33:30.534  1945  7302 D WfdsMonitor: Supplicant connection established
08-10 13:33:30.534  1945  2312 D WfdsService: Connected to the supplicant for wfds
08-10 13:33:30.534  1031  1539 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-10 13:33:30.534  1031  1539 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-10 13:33:30.534  7283  7283 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-10 13:33:30.535  1031  1539 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-10 13:33:30.535  1031  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-10 13:33:30.535  7283  7283 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-10 13:33:30.536  1031  1539 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-10 13:33:30.536  1031  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-10 13:33:30.536  7283  7283 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-10 13:33:30.536  1031  1539 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-10 13:33:30.536  1031  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-10 13:33:30.536  7283  7283 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-10 13:33:30.537  1031  1539 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-10 13:33:30.537  1031  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-10 13:33:30.537  7283  7283 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-10 13:33:30.537  1031  1539 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-10 13:33:30.537  1031  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-10 13:33:30.538  7283  7283 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-10 13:33:30.538  1031  1539 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-10 13:33:30.538  1031  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-10 13:33:30.538  7283  7283 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-10 13:33:30.539  1031  1539 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-10 13:33:30.539  1031  1539 E WifiNative: : [357,745,404 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-10 13:33:30.539  1031  1539 D WifiNative-wlan0: doBoolean: RECONNECT
08-10 13:33:30.540  1031  1539 D WifiNative-wlan0: RECONNECT: returned true
08-10 13:33:30.540  1031  1539 D WifiNative-wlan0: doString: [STATUS]
08-10 13:33:30.541  1031  7301 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-10 13:33:30.541  1031  7301 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-10 13:33:30.541  1031  1539 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-10 13:33:30.541  1031  1539 D WifiNative-wlan0: doBoolean: SET ps 1
08-10 13:33:30.542  1031  1539 D WifiNative-wlan0: SET ps 1: returned true
0,8-10 13:33:30.542  1031  1538 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
,08-10 13:33:30.543  1031  1031 D WifiScanningService: SCAN_AVAILABLE : 3
08-10 13:33:30.543  1031  1031 D RttService: SCAN_AVAILABLE : 3
08-10 13:33:30.543  1031  1559 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-10 13:33:30.543  1031  1559 I WifiNative-HAL: startHal
08-10 13:33:30.543  1031  1559 D wifi    : getting scan capabilities on interface[1] = 0x9535c4c0
08-10 13:33:30.543  1031  1559 D wifi    : failed to get capabilities : -3
08-10 13:33:30.543  1031  1559 E WifiScanningService: could not get scan capabilities
08-10 13:33:30.544  1031  1560 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-10 13:33:30.544  1031  1539 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-10 13:33:30.544  1031  1539 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-10 13:33:30.545  1031  1539 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-10 13:33:30.545  1031  1539 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-10 13:33:30.545  1031  1539 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-10 13:33:30.546   306   896 D CommandListener: Setting iface cfg
08-10 13:33:30.546  1031  1539 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-10 13:33:30.546   306   896 D CommandListener: Trying to bring up p2p0
08-10 13:33:30.546  1031  1539 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-10 13:33:30.546  1031  1539 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-10 13:33:30.546  7283  7283 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-10 13:33:30.547  1031  1539 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-10 13:33:30.547  1031  1539 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-10 13:33:30.548  1031  1539 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-10 13:33:30.548  1031  1539 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-10 13:33:30.548  7283  7283 E wpa_supplicant: disconnect_rssi_lvl: -100
08-10 13:33:30.549  1031  1539 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-10 13:33:30.549  1031  1539 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-10 13:33:30.549  1031  1539 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-10 13:33:30.549  1031  1539 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-10 13:33:30.550  7283  7283 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-10 13:33:30.550  7283  7283 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-10 13:33:30.551  7283  7283 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-10 13:33:30.551  7283  7283 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 13:33:30.551  1031  7301 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-10 13:33:30.551  1031  7301 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-10 13:33:30.551  1031  7301 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-10 13:33:30.552  1031  7301 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-10 13:33:30.552  7283  7283 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 13:33:30.552  1031  7301 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-10 13:33:30.552  1031  1538 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-10 13:33:30.552  1031  1538 D LGWifiP2pService: P2pEnablingState
08-10 13:33:30.552  1031  7301 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 13:33:30.552  1031  1538 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHa,ndler }
08-10 13:33:30.552  1031  1538 D LGWifiP2pService: P2p socket connection successful
08-10 13:33:30.552  1031  7301 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 13:33:30.552  1031  1538 D LGWifiP2pService: P2pEnabledState
08-10 13:33:30.552  1031  7301 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 13:33:30.552  1031  7301 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-10 13:33:30.552  1031  1539 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-10 13:33:30.552  1031  7301 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 13:33:30.552  1031  7301 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 13:33:30.552  1031  7301 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 13:33:30.552  1031  1538 D LGWifiP2pService: sending p2p connection changed broadcast
08-10 13:33:30.552  1031  1539 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-10 13:33:30.552  1031  1538 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-10 13:33:30.553  1031  1539 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-10 13:33:30.553  1031  1539 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-10 13:33:30.553  1031  1539 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-10 13:33:30.553  1945  1945 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-10 13:33:30.553  1945  7302 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-10 13:33:30.553  1945  7302 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-10 13:33:30.554  1945  1945 D WfdsService: WifiP2pState is changed : true
,08-10 13:33:30.554  1031  1538 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-10 13:33:30.554  1945  2312 D WfdsService: Receive the WFDS_ENABLE Method
08-10 13:33:30.554  1945  2312 D WfdsService: Set the WFDS Monitor: true
08-10 13:33:30.554  7283  7283 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-10 13:33:30.554  1945  2312 D WfdsService: Connected to the supplicant for wfds
08-10 13:33:30.554  1945  2312 D WfdsJNI : doCommand: WFDS_SET TRUE
08-10 13:33:30.554  7283  7283 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-10 13:33:30.555  1031  7301 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-10 13:33:30.555  1031  7301 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-10 13:33:30.555  1945  1945 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-10 13:33:30.555  7283  7283 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-10 13:33:30.555  1031  7301 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-10 13:33:30.555  1031  7301 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-10 13:33:30.555  1031  1539 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-10 13:33:30.556  1031  1539 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-10 13:33:30.556  1945  1945 D WfdsService: isConnected: false
08-10 13:33:30.556  1945  2312 D WfdsService: selectPreferredScanChannel [36]
08-10 13:33:30.556  1945  2312 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-10 13:33:30.556  1031  1539 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-10 13:33:30.556  1031  1539 D WifiNative-wlan0: doBoolean: SCAN
08-10 13:33:30.556  1031  1539 D WifiNative-wlan0: SCAN: returned false
08-10 13:33:30.557  1031  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=357763  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-10 13:33:30.558  1031  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=357764  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-10 13:33:30.558  1031  1539 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-10 13:33:30.558  1031  1538 D WifiNative-p2p0: doBoolean: SET device_name G3
08-10 13:33:30.559  1031  1538 D WifiNative-p2p0: SET device_name G3: returned true
08-10 13:33:30.559  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 13:33:30.559  1031  1538 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-10 13:33:30.559  1031  1538 D LGWifiP2pService: before postfix = G3
08-10 13:33:30.559  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 13:33:30.559  1031  1538 D WifiServerServiceExt: postfix byte check : 2
08-10 13:33:30.559  1031  1538 D LGWifiP2pService: after postfix = G3
08-10 13:33:30.559  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-10 13:33:30.559  1031  1538 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-10 13:33:30.559  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 13:33:30.559  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-10 13:33:30.559  1031  1538 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-10 13:33:30.559  1031  1538 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-10 13:33:30.559  1031  1538 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-10 13:33:30.559  1031 , 1538 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-10 13:33:30.560  1031  1538 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-10 13:33:30.560  1031  1538 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-10 13:33:30.560  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 13:33:30.560  1031  1538 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-10 13:33:30.560  1031  1538 D WifiNative-HAL: p2pGetDeviceAddress
08-10 13:33:30.561  1031  1538 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-10 13:33:30.561  1031  1539 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-10 13:33:30.561  1031  1538 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-10 13:33:30.561  1031  1538 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-10 13:33:30.561  1031  1539 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-10 13:33:30.561  1031  1539 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-10 13:33:30.562  1031  1538 D WifiNative-p2p0: P2P_FLUSH: returned true
08-10 13:33:30.562  1031  1538 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-10 13:33:30.562  1031  1538 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-10 13:33:30.562  1031  1538 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-10 13:33:30.562  1031  1539 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-10 13:33:30.562  1945  1945 I WfdStateTracker: handleP2pThisDeviceChanged
08-10 13:33:30.562  1031  1538 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-10 13:33:30.562  1031  1538 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-10 13:33:30.563  1945  1945 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-10 13:33:30.563  1945  1945 D WfdsService: Update P2p Interface State: 3
08-10 13:33:30.563  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-10 13:33:30.564  1031  1031 D WifiServerServiceExt: setSupplicantStateSCANNING
08-10 13:33:30.570  1031  1538 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-10 13:33:30.570  1031  1538 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-10 13:33:30.571  1031  1538 D LGWifiP2pService: InactiveState
08-10 13:33:30.571  1031  1538 D LGWifiP2pService: InactiveState{ when=-19ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-10 13:33:30.571  1031  1538 D LGWifiP2pService: P2pEnabledState{ when=-19ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-10 13:33:30.571  1031  1538 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-10 13:33:30.572  7283  7283 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
,08-10 13:33:30.575  7283  7283 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-10 13:33:30.575  1031  7301 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-10 13:33:30.575  1031  7301 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-10 13:33:30.575  1031  7301 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-10 13:33:30.575  1031  7301 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-10 13:33:30.575  1945  7302 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-10 13:33:30.575  7283  7283 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-10 13:33:30.575  7283  7283 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 13:33:30.575  1945  7302 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-10 13:33:30.576  1031  1538 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-10 13:33:30.576  1031  1538 D LGWifiP2pService: InactiveState{ when=-14ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-10 13:33:30.576  1031  1538 D LGWifiP2pService: P2pEnabledState{ when=-14ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-10 13:33:30.576  1031  1538 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-10 13:33:30.576  1031  1538 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-10 13:33:30.576  1031  1538 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-10 13:33:30.576  7283  7283 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 13:33:30.576  1031  1538 D LGWifiP2pService: InactiveState{ when=0 what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-10 13:33:30.576  1945  7302 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-10 13:33:30.576  1031  1538 D LGWifiP2pService: P2pEnabledState{ when=0 what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-10 13:33:30.576  1031  1538 D LGWifiP2pService: DefaultState{ when=0 what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-10 13:33:30.576  1031  1031 E WifiServerServiceExt: No p2p device connected
08-10 13:33:30.576  1031  7301 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-10 13:33:30.576  1031  7301 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 13:33:30.576  1031  7301 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 13:33:30.576  1031  7301 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 13:33:30.577  1031  7301 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-10 13:33:30.577  1031  7301 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 13:33:30.577  1031  7301 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 13:33:30.577  1031  7301 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 13:33:30.662  1031  2035 I art     : Explicit concurrent mark sweep GC freed 69760(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 1.483ms total 117.708ms
,08-10 13:33:30.667  1031  1538 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-10 13:33:30.667  1031  1538 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-10 13:33:30.667  1031  1538 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-10 13:33:30.668  1031  1538 D LGWifiP2pService: InactiveState{ when=0 what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-10 13:33:30.668  1031  1538 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-10 13:33:30.668  1031  1538 D LGWifiP2pService: DefaultState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-10 13:33:30.669  1945  2312 W WfdsService: DefaultState - msg [9441285] is not handled
08-10 13:33:30.857  6357  6357 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-10 13:33:30.861  6357  6900 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-10 13:33:30.877  2193  2193 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-10 13:33:30.885  7060  7060 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-10 13:33:30.886  7060  7060 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-10 13:33:30.886  7060  7060 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-10 13:33:30.886  7060  7060 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-10 13:33:30.887  7060  7060 I AppUp4:CustModeStarterReceiver: onReceive
08-10 13:33:30.891  7060  7060 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@866a964
08-10 13:33:30.891  7060  7060 D AppUp4:CustFacade: isCustomizationCompleted : false
08-10 13:33:30.891  7060  7060 D AppUp4:CustFacade: isPhone : true
08-10 13:33:30.891  7060  7060 D AppUp4:CustModeStarterReceiver: begin check event
08-10 13:33:30.891  7060  7060 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
,08-10 13:33:30.894  4325  4325 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-10 13:33:30.894  4325  4325 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-10 13:33:30.896  4325  4325 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-10 13:33:30.898  4325  4325 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-10 13:33:30.903  7089  7089 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-10 13:33:30.909  4325  7316 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-10 13:33:30.917  4325  7318 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,08-10 13:33:30.917  4325  7318 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-10 13:33:30.920  7089  7319 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 13:33:30.927  3485  3485 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-10 13:33:30.927  3485  3485 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-10 13:33:30.927  3485  3485 I LgeMiscReceiver: networkInfo.isConnected() = false
08-10 13:33:30.929  7117  7117 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-10 13:33:30.929  7117  7117 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-10 13:33:30.939  7182  7182 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:33:30
08-10 13:33:30.940  7182  7182 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-10 13:33:30.940  7182  7182 D Weather.Utils: 2 : All the weather widget is gone.
08-10 13:33:30.941  7182  7182 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-10 13:33:30.941  7182  7182 D WeatherAncestor: connectivity changed - connection : true
08-10 13:33:30.941  7182  7182 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@125b882
08-10 13:33:30.941  7182  7182 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-10 13:33:30.943  7182  7182 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-10 13:33:30.943  7182  7182 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-10 13:33:30.943  7182  7182 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-10 13:33:30.943  7182  7182 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:33:30
08-10 13:33:30.943  6971  7322 W FormManager: Network not available. Please check & try again.
,08-10 13:33:30.948  6971  7323 V FormManager: Network unavailable.
08-10 13:33:30.956  6971  7323 V FormManager: Network unavailable.
,08-10 13:33:30.984   306  7332 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-10 13:33:30.985  1031  1094 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-10 13:33:30.986  6876  6876 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-10 13:33:30.986  6876  6876 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-10 13:33:30.987  6876  6876 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-10 13:33:30.987  6876  6876 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-10 13:33:30.990  6876  6876 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-10 13:33:30.991  6876  6876 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-10 13:33:30.991  6876  6876 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-10 13:33:30.991  6876  6876 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-10 13:33:30.991  6876  6876 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-10 13:33:30.991  6876  6876 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-10 13:33:30.991  6876  6876 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-10 13:33:31.000  6901  6901 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-10 13:33:31.006  6876  6876 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-10 13:33:31.011  6971  7335 W FormManager: Network not available. Please check & try again.
,08-10 13:33:31.013  6876  6876 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 13:33:31.025  6971  7336 V FormManager: Network unavailable.
,08-10 13:33:31.028  6971  7336 V FormManager: Network unavailable.
08-10 13:33:31.043  6901  6901 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-10 13:33:31.047  6876  6876 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-10 13:33:31.052  6971  7339 W FormManager: Network not available. Please check & try again.
08-10 13:33:31.055  6971  7340 V FormManager: Network unavailable.
,08-10 13:33:31.056  6876  6876 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-10 13:33:31.061  6971  7340 V FormManager: Network unavailable.
08-10 13:33:31.073  4325  4325 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-10 13:33:31.074  4325  4325 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-10 13:33:31.075  4325  4325 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-10 13:33:31.079  4325  4325 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-10 13:33:31.084  7283  7283 E wpa_supplicant: USIM:  scard_init function
08-10 13:33:31.084  1031  7301 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-10 13:33:31.084  1031  7301 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-10 13:33:31.084  1031  7301 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-10 13:33:31.085  1031  7301 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: WPS-AP-AVAILABLE 
08-10 13:33:31.085  7283  7283 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-10 13:33:31.085  1031  7301 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-10 13:33:31.085  1031  1539 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-10 13:33:31.086  1031  1539 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-10 13:33:31.086  1031  1539 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-10 13:33:31.087  1031  1539 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-10 13:33:31.087  1031  1539 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-10 13:33:31.087  1031  7301 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-10 13:33:31.087  1031  7301 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
,08-10 13:33:31.089  4325  7341 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-10 13:33:31.095  4325  7342 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-10 13:33:31.095  4325  7342 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-10 13:33:31.121  1031  2016 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7343 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
08-10 13:33:31.123  1031  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=358329  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-10 13:33:31.126  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 13:33:31.126  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-10 13:33:31.127  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-10 13:33:31.127  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 13:33:31.127  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-10 13:33:31.128  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 13:33:31.129  1031  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=358336  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-10 13:33:31.132  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 13:33:31.132  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 13:33:31.132  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-10 13:33:31.132  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-10 13:33:31.132  1031  1031 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-10 13:33:31.148  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 13:33:31.148  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-10 13:33:31.149  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 13:33:31.151   341   341 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 608us total 28.116ms
,08-10 13:33:31.171   341   341 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 388us total 19.236ms
,08-10 13:33:31.185   341   341 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 288us total 13.535ms
,08-10 13:33:31.192  1031  1096 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-10 13:33:31.192  7283  7283 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-10 13:33:31.193  1031  7301 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-10 13:33:31.193  1031  7301 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-10 13:33:31.193  1031  1539 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
08-10 13:33:31.193  1031  7301 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-10 13:33:31.193  1031  7301 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-10 13:33:31.193  1031  7301 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-10 13:33:31.193  1031  7301 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-10 13:33:31.193  1031  1539 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-10 13:33:31.194  1031  1539 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-10 13:33:31.194  1031  1539 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-10 13:33:31.195  1031  1539 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-10 13:33:31.195  1031  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=358401  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-10 13:33:31.196  1031  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=358402  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-10 13:33:31.196  1031  1539 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=358402
08-10 13:33:31.196  1031  1539 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=358403
08-10 13:33:31.197  1031  1539 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=358403
08-10 13:33:31.197  1031  1539 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=358404
,08-10 13:33:31.198  1031  1539 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=358404
08-10 13:33:31.198  1031  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=358404  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-10 13:33:31.200  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 13:33:31.200  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-10 13:33:31.201  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 13:33:31.201  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 13:33:31.201  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-10 13:33:31.202  1031  7301 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-10 13:33:31.202  1031  7301 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-10 13:33:31.202  7283  7283 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-10 13:33:31.202  1031  7301 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-10 13:33:31.202  7283  7283 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-10 13:33:31.202  1031  7301 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-10 13:33:31.202  1031  7301 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-10 13:33:31.202  1031  7301 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-10 13:33:31.202  1031  7301 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-10 13:33:31.202  1031  7301 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-10 13:33:31.203  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 13:33:31.203  1031  7301 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-10 13:33:31.203  1031  7301 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-10 13:33:31.205  1031  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=358411  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-10 13:33:31.205  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 13:33:31.205  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 13:33:31.205  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-10 13:33:31.206  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-10 13:33:31.206  1031  1031 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-10 13:33:31.206  1031  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=358413  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-10 13:33:31.207  1031  1539 E WifiSt,ateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=358413  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-10 13:33:31.208  1031  1539 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=358414
08-10 13:33:31.208  1031  1539 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=358414
08-10 13:33:31.208  1031  1539 D WifiNative-wlan0: doString: [STATUS]
08-10 13:33:31.209  1031  7301 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-10 13:33:31.209  1031  7301 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-10 13:33:31.210  1031  1539 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-10 13:33:31.211  1031  1539 I WifiServiceExtension: setVHTCapabilityType  : false
08-10 13:33:31.215  1031  1539 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-10 13:33:31.215  1031  1539 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,08-10 13:33:31.217  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 13:33:31.217  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 13:33:31.218  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-10 13:33:31.220  6596  7043 D UEI.SmartControl: Internal timer expired: 2
08-10 13:33:31.220  6596  7043 D UEI.SmartControl: unbind internal service
08-10 13:33:31.221  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 13:33:31.222  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-10 13:33:31.223  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 13:33:31.223  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 13:33:31.223  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-10 13:33:31.226  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 13:33:31.226  1031  1539 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,08-10 13:33:31.226  1031  1545 D ConnectivityService: Got NetworkAgent Messenger
08-10 13:33:31.226  1031  1539 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-10 13:33:31.226  1031  1539 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
,08-10 13:33:31.227  1031  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-10 13:33:31.227  1031  1545 D ConnectivityService: NetworkAgent connected
08-10 13:33:31.227  1031  1539 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-10 13:33:31.227  1031  1539 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-10 13:33:31.228  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 13:33:31.228  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-10 13:33:31.229  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 13:33:31.230  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 13:33:31.230  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-10 13:33:31.230  1031  1539 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-10 13:33:31.230  1031  1539 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-10 13:33:31.230  1031  1539 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-10 13:33:31.231  1031  1539 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-10 13:33:31.231  1031  1539 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-10 13:33:31.231  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 13:33:31.234  1031  1539 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-10 13:33:31.236   306   896 D CommandListener: Setting iface cfg
08-10 13:33:31.238  1031  1539 E WifiStateMachine: Start Dhcp Watchdog 2
08-10 13:33:31.238  1031  1539 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=358445  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-10 13:33:31.239  1031  1539 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=358445  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-10 13:33:31.239  1031  7361 D DhcpStateMachine: StoppedState
08-10 13:33:31.239  1031  7361 D DhcpStateMachine: StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-10 13:33:31.239  1031  7361 D DhcpStateMachine: WaitBeforeStartState
08-10 13:33:31.239  1031  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=358446  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-10 13:33:31.240  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-10 13:33:31.240  7343  7343 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-10 13:33:31.240  1031  1031 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-10 13:33:31.240  7343  7343 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
08-10 13:33:31.241  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-10 13:33:31.241  1031  1031 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
,08-10 13:33:31.242  1031  1539 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=358448  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-10 13:33:31.242  1031  1539 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=358448  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-10 13:33:31.243  1031  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=358449  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-10 13:33:31.244  1031  1539 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:313279] from screen [on:0 period:1949996012] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-10 13:33:31.244  1031  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:1949996012] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-10 13:33:31.244  1031  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-10 13:33:31.246  7343  7343 V [BNRBootReceiver]: Boot Receiver Return
08-10 13:33:31.246  7343  7343 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-10 13:33:31.249  6357  6357 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 13:33:31.251  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 13:33:31.251  1031  1545 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-10 13:33:31.252  1031  1539 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
,08-10 13:33:31.253  1031  1539 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 13:33:31.254  1031  1539 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 13:33:31.254  1031  1539 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 13:33:31.255  1031  1539 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 13:33:31.255  1031  1539 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 13:33:31.256  1031  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,08-10 13:33:31.256  1031  1539 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=145,0,0
08-10 13:33:31.257  1031  1539 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=145,0,0
08-10 13:33:31.257  1031  1539 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-10 13:33:31.257  7283  7283 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-10 13:33:31.257  1031  1539 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-10 13:33:31.257  1031  1539 D WifiNative-wlan0: doBoolean: SET ps 0
08-10 13:33:31.258  1031  1539 D WifiNative-wlan0: SET ps 0: returned true
08-10 13:33:31.258  1031  1539 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-10 13:33:31.258  7283  7283 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-10 13:33:31.258  6596  7037 D serial_port: close(fd = 24)
08-10 13:33:31.258  1031  1539 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-10 13:33:31.258  1031  1539 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-10 13:33:31.258  1031  1539 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-10 13:33:31.259  1031  1539 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-10 13:33:31.259  1031  1538 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@39424efd target=com.android.internal.util.StateMachine$SmHandler }
08-10 13:33:31.259  1031  1538 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@39424efd target=com.android.internal.util.StateMachine$SmHandler }
,08-10 13:33:31.259  1031  7361 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-10 13:33:31.259  1031  7361 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-10 13:33:31.259  6876  6876 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-10 13:33:31.260   306   896 D CommandListener: Setting iface cfg
08-10 13:33:31.260   306   896 D CommandListener: Trying to bring up wlan0
08-10 13:33:31.260  1031  1539 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-10 13:33:31.261  1031  1539 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 13:33:31.262  1031  1539 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 13:33:31.262  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-10 13:33:31.262  1031  1031 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-10 13:33:31.262  1031  1539 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 13:33:31.263  1031  1539 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 13:33:31.263  6596  7037 I UEI.SmartControl: Serial port is closed.
08-10 13:33:31.263  1031  1539 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 13:33:31.263  1031  1539 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 13:33:31.264  1031  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-10 13:33:31.264  1031  1539 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-10 13:33:31.264  1031  1539 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-10 13:33:31.265  1031  1539 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-10 13:33:31.265  7283  7283 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-10 13:33:31.266  6876  6876 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 13:33:31.266  1031  1539 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-10 13:33:31.266  1031  1539 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-10 13:33:31.266  7283  7283 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
,08-10 13:33:31.266  1031  1539 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-10 13:33:31.266  1031  1539 D WifiNative-wlan0: doBoolean: SET ps 1
08-10 13:33:31.267  1031  1539 D WifiNative-wlan0: SET ps 1: returned true
08-10 13:33:31.267  1031  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-10 13:33:31.268  1031  1539 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-10 13:33:31.268  1031  1539 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-10 13:33:31.268  1031  1539 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-10 13:33:31.269  1031  1545 D ConnectivityService: ignoring duplicate network state non-change
08-10 13:33:31.269  1031  1538 D LGWifiP2pService: InactiveState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-10 13:33:31.269  1031  1538 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-10 13:33:31.271  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 13:33:31.271  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-10 13:33:31.272  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 13:33:31.273  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 13:33:31.273  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 13:33:31.273  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-10 13:33:31.275  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 13:33:31.276  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 13:33:31.276  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-10 13:33:31.276  1031  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-10 13:33:31.277  1031  1545 D ConnectivityService: Adding iface wlan0 to network 101
,08-10 13:33:31.281  1031  1539 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-10 13:33:31.282  1031  1031 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-10 13:33:31.283  1945  1945 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-10 13:33:31.283  6933  6933 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-10 13:33:31.283  6933  6933 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-10 13:33:31.287  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 13:33:31.287  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 13:33:31.287  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-10 13:33:31.288  1031  1031 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,08-10 13:33:31.293  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 13:33:31.293  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 13:33:31.293  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-10 13:33:31.294  6933  6933 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-10 13:33:31.295  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 13:33:31.295  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-10 13:33:31.297  1031  1545 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-10 13:33:31.297  1031  1545 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-10 13:33:31.298  6876  6876 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-10 13:33:31.299  1031  1545 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-10 13:33:31.299   306   896 E Netd    : netlink response contains error (File exists)
08-10 13:33:31.300  1031  1545 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-10 13:33:31.300  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 13:33:31.301  1031  1545 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-10 13:33:31.301  1031  1545 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-10 13:33:31.301  1031  1545 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-10 13:33:31.302  6876  6876 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-10 13:33:31.302  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 13:33:31.302  1605  1605 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-10 13:33:31.303  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 13:33:31.304  1031  1545 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-10 13:33:31.304  1031  1545 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-10 13:33:31.304  1031  1545 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-10 13:33:31.304  1031  1545 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-10 13:33:31.304  1031  1545 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-10 13:33:31.304  1031  1545 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-10 13:33:31.304  1031  1545 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-10 13:33:31.304  1031  1545 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 13:33:31.305  1031  1545 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-10 13:33:31.305  1031  1545 D ConnectivityService: currentScore = 0, newScore = 20
08-10 13:33:31.305  1031  1545 D ConnectivityService:    accepting network in place of null
08-10 13:33:31.305  1031  1545 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 13:33:31.305  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 13:33:31.305  1031  7360 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-10 13:33:31.305  1031  7360 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-10 13:33:31.305  1605  1605 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-10 13:33:31.305  1031  7360 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-10 13:33:31.305  1031  7360 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-10 13:33:31.306  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 13:33:31.306  1856  1856 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 13:33:31.306  6357  6357 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 13:33:31.307  1856  1856 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-10 13:33:31.307  1031  1539 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 13:33:31.307  1031  1539 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-10 13:33:31.308  1031  1545 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} exp,licitlySelected{false} } for legacy network type 1
08-10 13:33:31.308  1031  1545 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-10 13:33:31.308  1031  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-10 13:33:31.308   306  7366 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-10 13:33:31.311  1031  1545 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-10 13:33:31.311  1031  1545 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-10 13:33:31.311  1031  1545 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-10 13:33:31.315  1031  1545 D ConnectivityService: validation of new default Network = false
08-10 13:33:31.315  1031  1545 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-10 13:33:31.315  1031  1545 D DSQN    : enableDataServiceNotify 
08-10 13:33:31.315  1031  1545 D DSQN    : start dsqn bin
,08-10 13:33:31.319  1031  1031 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-10 13:33:31.319  1031  1545 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-10 13:33:31.319  1031  1031 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-10 13:33:31.319  1031  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 13:33:31.319  1031  1031 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-10 13:33:31.319  1031  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-10 13:33:31.319  1031  1031 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,08-10 13:33:31.320  1031  1545 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-10 13:33:31.320  1605  2072 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-10 13:33:31.302  7367  7367 W dsqn    : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-10 13:33:31.302  7367  7367 W dsqn    : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-10 13:33:31.327  6876  6876 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-10 13:33:31.332  1031  1537 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-10 13:33:31.336  6876  6876 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 13:33:31.337  7367  7367 E DSQN    : DSQN ssw
08-10 13:33:31.346  6933  6933 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-10 13:33:31.346  6933  6933 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-10 13:33:31.347  6933  6933 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-10 13:33:31.350  6357  6357 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 13:33:31.357  6876  6876 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-10 13:33:31.359  1821  7371 I CheckinService: active receiver: enabled
,08-10 13:33:31.365  6876  6876 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 13:33:31.368  1821  7371 I CheckinService: Preparing to send checkin request
08-10 13:33:31.368  1821  7371 I EventLogService: Accumulating logs since 1470828509749
08-10 13:33:31.373  6933  6933 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-10 13:33:31.373  6933  6933 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-10 13:33:31.374  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-10 13:33:31.374  6933  6933 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-10 13:33:31.375  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 13:33:31.376  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 13:33:31.376  6876  6876 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-10 13:33:31.376  6876  6876 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-10 13:33:31.376  6876  6876 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-10 13:33:31.376  6876  6876 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-10 13:33:31.377  6876  6876 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-10 13:33:31.378  6876  6876 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-10 13:33:31.378  6876  6876 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-10 13:33:31.378  6876  6876 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-10 13:33:31.378  6876  6876 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-10 13:33:31.378  6876  6876 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-10 13:33:31.378  6876  6876 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-10 13:33:31.378  6876  6876 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-10 13:33:31.381  6357  6357 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 13:33:31.385  6876  6876 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-10 13:33:31.389  6876  6876 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 13:33:31.395  6933  6933 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-10 13:33:31.395  6933  6933 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-10 13:33:31.395  6933  6933 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-10 13:33:31.398  6357  6357 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 13:33:31.405  6876  6876 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-10 13:33:31.406  1821  7371 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
08-10 13:33:31.410  6876  6876 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 13:33:31.411   306  7366 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-10 13:33:31.416  6933  6933 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-10 13:33:31.416  6933  6933 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-10 13:33:31.417  6933  6933 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-10 13:33:31.419  6357  6357 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 13:33:31.428  6876  6876 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-10 13:33:31.434  6876  6876 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 13:33:31.444   306  7366 D libc-netbsd: res_queryN name = clients3.google.com succeed
08-10 13:33:31.445  6933  6933 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-10 13:33:31.445  6933  6933 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-10 13:33:31.445  6933  6933 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-10 13:33:31.449  6357  6357 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 13:33:31.460  1031  7361 D DhcpStateMachine: DHCPV4 request on wlan0
08-10 13:33:31.461  1031  7361 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-10 13:33:31.461  1031  7361 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
,08-10 13:33:31.462  6876  6876 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-10 13:33:31.452  7373  7373 W dhcpcd  : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-10 13:33:31.452  7373  7373 W dhcpcd  : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-10 13:33:31.473  7373  7373 I dhcpcd  : version 5.5.6 starting
,08-10 13:33:31.475   306   895 D LGDataListener: argv[0]=dsqncommand
08-10 13:33:31.475   306   895 D LGDataListener: argv[1]=wlan0
08-10 13:33:31.475   306   895 D LGDataListener: argv[2]=1
08-10 13:33:31.475   306   895 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-10 13:33:31.476  1031  1094 D DSQN    : DSQM DsqnNotification wlan0  1
08-10 13:33:31.476  1031  1094 D DSQN    : start to monitor internet connection
08-10 13:33:31.477  7373  7373 E dhcpcd  : get_duid: m
08-10 13:33:31.477  7373  7373 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-10 13:33:31.477  7373  7373 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-10 13:33:31.479  6876  6876 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 13:33:31.488  6933  6933 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-10 13:33:31.489  6933  6933 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-10 13:33:31.489  6933  6933 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-10 13:33:31.496  6357  6357 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 13:33:31.504  1031  7360 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 10 Aug 2016 11:33:31 GMT], X-Android-Received-Millis=[1470828811503], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1470828811474]}
08-10 13:33:31.504  1031  7360 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-10 13:33:31.504  1031  7360 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
,08-10 13:33:31.504  1031  1545 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-10 13:33:31.504  1031  1545 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-10 13:33:31.504  1031  1545 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-10 13:33:31.504  1031  1545 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-10 13:33:31.504  1031  1545 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-10 13:33:31.505  1031  1545 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-10 13:33:31.505  1031  1545 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-10 13:33:31.505  1031  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 13:33:31.505  1031  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-10 13:33:31.505  1031  1545 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-10 13:33:31.506  1031  1545 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 13:33:31.506  1031  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-10 13:33:31.506  1856  1856 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 13:33:31.507  1856  1856 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-10 13:33:31.507  1031  1539 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 13:33:31.507  1031  1539 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-10 13:33:31.507  1605  2072 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-10 13:33:31.513  6876  6876 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-10 13:33:31.523  6876  6876 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 13:33:31.548  7373  7373 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-10 13:33:31.548  7373  7373 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
,08-10 13:33:31.548  7373  7373 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-10 13:33:31.549  7373  7373 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
08-10 13:33:31.549  7373  7373 D dhcpcd  : wlan0: sending REQUEST (xid 0x94b16aa7), next in 3.51 seconds
,08-10 13:33:31.565  1031  1908 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7382 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-10 13:33:31.571  6933  6933 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-10 13:33:31.571  7373  7373 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
08-10 13:33:31.572  6933  6933 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-10 13:33:31.579  6933  6933 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-10 13:33:31.583  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-10 13:33:31.584  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 13:33:31.585  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 13:33:31.587  6357  6357 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 13:33:31.596  6876  6876 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-10 13:33:31.602  7373  7373 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
08-10 13:33:31.602  7373  7373 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
08-10 13:33:31.602  7373  7373 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-10 13:33:31.602  7373  7373 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-10 13:33:31.602  7373  7373 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,08-10 13:33:31.603  7373  7373 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-10 13:33:31.603  7373  7373 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-10 13:33:31.603  7373  7373 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,08-10 13:33:31.617  6876  6876 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 13:33:31.634  6933  6933 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-10 13:33:31.634  6933  6933 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-10 13:33:31.635  6933  6933 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-10 13:33:31.639  6357  6357 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 13:33:31.644  6901  6901 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-10 13:33:31.653  6901  6901 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,08-10 13:33:31.657  6876  6876 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-10 13:33:31.662  7382  7382 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-10 13:33:31.663  7382  7382 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
08-10 13:33:31.667  6876  6876 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 13:33:31.676  6933  6933 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-10 13:33:31.676  6933  6933 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-10 13:33:31.677  6933  6933 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-10 13:33:31.678  6933  6933 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-10 13:33:31.678  6933  6933 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,08-10 13:33:31.685  6357  6357 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 13:33:31.693  6901  6901 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-10 13:33:31.696  6901  6901 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-10 13:33:31.700  6876  6876 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-10 13:33:31.710  6876  6876 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 13:33:31.711  7382  7382 I MultiDex: VM with version 2.1.0 has multidex support
08-10 13:33:31.711  7382  7382 I MultiDex: install
08-10 13:33:31.711  7382  7382 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-10 13:33:31.719  6933  6933 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-10 13:33:31.719  6933  6933 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-10 13:33:31.720  6933  6933 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-10 13:33:31.721  6933  6933 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,08-10 13:33:31.721  6933  6933 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-10 13:33:31.723  1031  1926 I ActivityManager: Killing 6850:com.lge.lifetracker/u0a37 (adj 15): empty #17
08-10 13:33:31.784  1031  1046 W libprocessgroup: failed to open /acct/uid_10037/pid_6850/cgroup.procs: No such file or directory
,08-10 13:33:31.788  7382  7382 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
08-10 13:33:31.793  2193  2193 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-10 13:33:31.803  2193  2193 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
08-10 13:33:31.803  2193  2193 D c       : Getting all permits...
08-10 13:33:31.803  2193  2193 D a       : Opening database...
08-10 13:33:31.806  2193  2193 D a       : Opening database auth.proximity.permit_store...
08-10 13:33:31.807  2193  2193 D a       : Closing database...
,08-10 13:33:31.864  1031  7361 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-10 13:33:31.865  1031  7361 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-10 13:33:31.865  1031  7361 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-10 13:33:31.865  1031  7361 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
08-10 13:33:31.866  1031  7361 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-10 13:33:31.866  1031  7361 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-10 13:33:31.866  1031  7361 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-10 13:33:31.866  1031  7361 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-10 13:33:31.866  1031  7361 D DhcpStateMachine: RunningState
08-10 13:33:32.129  7425  7425 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-10 13:33:32.202  7425  7425 I dex2oat : dex2oat took 72.392ms (threads: 4)
,08-10 13:33:32.214  7382  7397 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-10 13:33:32.214  7382  7397 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-10 13:33:32.214  7382  7397 I Adreno-EGL: Build Date: 12/12/14 금
08-10 13:33:32.214  7382  7397 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-10 13:33:32.214  7382  7397 I Adreno-EGL: Remote Branch: 
08-10 13:33:32.214  7382  7397 I Adreno-EGL: Local Patches: 
08-10 13:33:32.214  7382  7397 I Adreno-EGL: Reconstruct Branch: 
,08-10 13:33:32.302  7382  7397 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-10 13:33:32.302  7382  7397 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-10 13:33:32.302  7382  7397 I Adreno-EGL: Build Date: 12/12/14 금
08-10 13:33:32.302  7382  7397 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-10 13:33:32.302  7382  7397 I Adreno-EGL: Remote Branch: 
08-10 13:33:32.302  7382  7397 I Adreno-EGL: Local Patches: 
08-10 13:33:32.302  7382  7397 I Adreno-EGL: Reconstruct Branch: 
,08-10 13:33:32.322  1031  1545 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
08-10 13:33:32.392  7382  7397 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-10 13:33:32.392  7382  7397 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-10 13:33:32.392  7382  7397 I Adreno-EGL: Build Date: 12/12/14 금
08-10 13:33:32.392  7382  7397 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-10 13:33:32.392  7382  7397 I Adreno-EGL: Remote Branch: 
08-10 13:33:32.392  7382  7397 I Adreno-EGL: Local Patches: 
08-10 13:33:32.392  7382  7397 I Adreno-EGL: Reconstruct Branch: 
,08-10 13:33:32.459  7382  7397 D LgDataFeature: LgDataFeature() Constructor: none
08-10 13:33:32.459  7382  7397 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-10 13:33:32.818   306  7436 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-10 13:33:32.818   306  7436 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
,08-10 13:33:32.865   306  7436 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,08-10 13:33:33.062  1821  7371 I CheckinTask: Sending checkin request (7901 bytes)
,08-10 13:33:33.199  1031  1539 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-10 13:33:33.201  1031  1539 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-10 13:33:33.214  1031  1539 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-10 13:33:33.215  1031  1539 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-10 13:33:33.216  1031  1539 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-10 13:33:33.216  1031  1539 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-10 13:33:33.217  1031  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
08-10 13:33:33.217  1031  1545 D ConnectivityService: identical MTU - not setting
08-10 13:33:33.217  1031  1545 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-10 13:33:33.217  1031  1545 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-10 13:33:33.217  1031  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 13:33:33.217  1031  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-10 13:33:33.218  1031  1545 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-10 13:33:33.219  1605  2072 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-10 13:33:33.298  1821  7371 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,08-10 13:33:33.311  1821  7371 I CheckinService: active receiver: disabled
,08-10 13:33:33.342  2193  2193 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-10 13:33:33.362  2193  2193 I GCM     : GCM config loaded
,08-10 13:33:33.380   306  7442 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-10 13:33:33.382   306  7442 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
08-10 13:33:33.387  7117  7117 V SetupWizard: Connected to Gservices successfully
08-10 13:33:33.414   306  7442 D libc-netbsd: res_queryN name = mtalk.google.com succeed
,08-10 13:33:33.680  2193  7445 D GCM     : Connected
,08-10 13:33:33.709  2193  7445 D GCM     : Message class com.google.e.a.a.q
08-10 13:33:34.256  1031  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=72.5, 0.0, 0.0  rx=70.5 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1949999023] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-10 13:33:34.259  1031  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=72.5, 0.0, 0.0  rx=70.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1949999026] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-10 13:33:34.259  1031  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-10 13:33:34.286  1031  1540 V WifiInternetCheck: Single check msg out of sync, ignoring.
,08-10 13:33:34.301  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-10 13:33:34.314  1031  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-10 13:33:34.326  1031  1096 D Tethering: MasterInitialState.processMessage what=3
,08-10 13:33:34.338  6729  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 13:33:34.338  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 13:33:34.338  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 13:33:34.338  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 13:33:34.338  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 13:33:34.338  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 13:33:34.338  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 13:33:34.338  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 13:33:34.338  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-10 13:33:34.338  6729  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 13:33:34.338  6729  6729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-10 13:33:34.346  6729  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 13:33:34.346  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 13:33:34.346  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 13:33:34.346  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 13:33:34.346  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 13:33:34.346  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 13:33:34.346  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 13:33:34.346  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 13:33:34.346  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-10 13:33:34.346  6729  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 13:33:34.346  6729  6729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-10 13:33:34.351  6729  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 13:33:34.351  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 13:33:34.351  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 13:33:34.351  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 13:33:34.351  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 13:33:34.351  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 13:33:34.351  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 13:33:34.351  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 13:33:34.351  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-10 13:33:34.351  6729  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 13:33:34.351  6729  6729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-10 13:33:34.362  1031  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-10 13:33:34.366  6357  6357 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-10 13:33:34.368  6357  6900 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-10 13:33:34.381  5771  5771 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,08-10 13:33:34.410  1031  1046 D WifiServiceImplEx: setWifiEnabled: false pid=6729, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-10 13:33:34.410  1031  1046 D WifiService: setWifiEnabled: false pid=6729, uid=10118
08-10 13:33:34.410  1031  1046 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-10 13:33:34.416  2193  2193 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-10 13:33:34.438  7060  7060 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-10 13:33:34.438  7060  7060 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,08-10 13:33:34.441  7060  7060 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-10 13:33:34.441  7060  7060 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-10 13:33:34.453  7060  7060 I AppUp4:CustModeStarterReceiver: onReceive
,08-10 13:33:34.459  1031  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 13:33:34.462  7060  7060 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@866a964
08-10 13:33:34.462  7060  7060 D AppUp4:CustFacade: isCustomizationCompleted : false
08-10 13:33:34.462  7060  7060 D AppUp4:CustFacade: isPhone : true
08-10 13:33:34.463  7060  7060 D AppUp4:CustModeStarterReceiver: begin check event
08-10 13:33:34.463  7060  7060 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-10 13:33:34.467  4325  4325 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-10 13:33:34.468  4325  4325 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-10 13:33:34.470  4325  4325 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-10 13:33:34.470  1031  1047 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10005
08-10 13:33:34.470  1031  7360 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-10 13:33:34.470  1031  7360 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-10 13:33:34.470  1031  7360 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-10 13:33:34.471  1031  7360 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-10 13:33:34.471  1031  7360 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
,08-10 13:33:34.474  4325  4325 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-10 13:33:34.481  3538  3538 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
08-10 13:33:34.484  3538  3538 V DownloadManager: DownloadService onCreate
08-10 13:33:34.486  3538  7462 I DownloadManager: in removeSpuriousFiles
08-10 13:33:34.487  3538  7462 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
08-10 13:33:34.487  7089  7089 D eas_req : ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-10 13:33:34.489  4325  7464 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-10 13:33:34.493  3538  7462 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@31a80348 on behalf of 3538
08-10 13:33:34.495  3538  7462 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
08-10 13:33:34.495  3538  7462 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
08-10 13:33:34.495  3538  7462 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
08-10 13:33:34.495  3538  7462 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
08-10 13:33:34.495  3538  7462 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
08-10 13:33:34.496  3538  7462 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
08-10 13:33:34.496  3538  7462 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
08-10 13:33:34.496  3538  7462 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
08-10 13:33:34.496  3538  7462 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
08-10 13:33:34.496  3538  7462 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
08-10 13:33:34.496  3538  7462 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
08-10 13:33:34.497  4325  7465 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-10 13:33:34.497  4325  7465 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-10 13:33:34.497  3538  7462 I DownloadManager: in trimDatabase
08-10 13:33:34.499  3538  7462 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
08-10 13:33:34.500  3538  3538 V DownloadManager: DownloadService onStartCommand
08-10 13:33:34.501  3538  7463 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
08-10 13:33:34.501  3538  7462 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@3f5f59c7 on behalf of 3538
08-10 13:33:34.505  1031  1539 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-10 13:33:34.506  1031  7360 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 10 Aug 2016 11:33:34 GMT], X-Android-Received-Millis=[1470828814505], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1470828814481]}
08-10 13:33:34.506  1031  1539 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-10 13:33:34.506  1031  7360 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-10 13:33:34.506  1031  7360 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-10 13:33:34.506  1031  1545 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
,08-10 13:33:34.506  1031  1545 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-10 13:33:34.506  1031  1539 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-10 13:33:34.506  1031  1545 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-10 13:33:34.506  1031  1545 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-10 13:33:34.506  1031  1545 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-10 13:33:34.506  1031  1545 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-10 13:33:34.506  1031  1545 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-10 13:33:34.506  1031  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 13:33:34.507  1031  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-10 13:33:34.507  1031  1539 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-10 13:33:34.507  1031  1539 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-10 13:33:34.507  1031  1539 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-10 13:33:34.507  1031  1539 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-10 13:33:34.507  1031  1539 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-10 13:33:34.508  1031  1539 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-10 13:33:34.508  1031  1031 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-10 13:33:34.508  1031  1539 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-10 13:33:34.508  1031  1031 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-10 13:33:34.508  1031  1031 D Ulp_jni : JNI:system_update. Event-4
08-10 13:33:34.510  1031  1545 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-10 13:33:34.511  4325  7464 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
08-10 13:33:34.512  1605  2072 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-10 13:33:34.514  3538  7463 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@3fde0bf4 on behalf of 3538
08-10 13:33:34.515  1031  1539 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-10 13:33:34.515  1031  1539 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-10 13:33:34.515  1031  1538 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-10 13:33:34.515  1031  1538 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-10 13:33:34.515  7283  7283 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-10 13:33:34.515  1031  1539 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-10 13:33:34.515  1031  1539 D WifiNative-wlan0: doBoolean: SET ps 1
08-10 13:33:34.516  1031  1539 D WifiNative-wlan0: SET ps 1: returned true
08-10 13:33:34.516   306   896 D CommandListener: Clearing all IP addresses on wlan0
08-10 13:33:34.517  1031  7361 D DhcpStateMachine: RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-10 13:33:34.521  3538  7463 V DownloadManager: processing inserted download 1
,08-10 13:33:34.535  1031  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-10 13:33:34.535  1031  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
,08-10 13:33:34.537  7089  7467 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 13:33:34.540  1031  1539 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 13:33:34.540  1031  1539 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 13:33:34.541  1031  1539 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 13:33:34.541  1031  1539 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-10 13:33:34.541  1031  1539 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 13:33:34.541  1031  1539 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 13:33:34.542  1031  1538 D LGWifiP2pService: InactiveState{ when=-3ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-10 13:33:34.542  1031  1538 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-10 13:33:34.542  1031  1538 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@1eba7ca2
08-10 13:33:34.542  1031  1538 D LGWifiP2pService: P2pDisablingState
08-10 13:33:34.543  1031  1538 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-10 13:33:34.543  1031  1538 D LGWifiP2pService: p2p socket connection lost
08-10 13:33:34.543  1031  1538 D LGWifiP2pService: P2pDisabledState
08-10 13:33:34.544  1031  1539 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 13:33:34.545  1031  1539 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-10 13:33:34.545  1031  1538 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-10 13:33:34.545  1031  1538 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-10 13:33:34.545  1031  1539 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-10 13:33:34.545  7283  7283 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-10 13:33:34.546  1031  1539 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-10 13:33:34.546  1031  1539 D WifiNative-wlan0: doBoolean: SET ps 1
08-10 13:33:34.546  1031  1539 D WifiNative-wlan0: SET ps 1: returned true
,08-10 13:33:34.547  3485  3485 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-10 13:33:34.547  3485  3485 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-10 13:33:34.547  3485  3485 I LgeMiscReceiver: networkInfo.isConnected() = true
08-10 13:33:34.547  3485  3485 D PhoneState: setPdpRejectCasuse : false
08-10 13:33:34.548  1031  1031 D WifiHS20: hidePasspointNotification off =false
08-10 13:33:34.548  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 13:33:34.548  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 13:33:34.548  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-10 13:33:34.548  1031  1031 D WifiHS20: hidePasspointNotification off =false
08-10 13:33:34.549  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 13:33:34.549  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 13:33:34.549  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-10 13:33:34.549  1031  1031 D WifiScanningService: SCAN_AVAILABLE : 1
08-10 13:33:34.549  1031  1559 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-10 13:33:34.550  1031  1031 D RttService: SCAN_AVAILABLE : 1
08-10 13:33:34.550  1031  1560 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-10 13:33:34.550  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 13:33:34.550  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-10 13:33:34.551  1945  1945 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-10 13:33:34.552  1945  1945 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-10 13:33:34.552  1945  1945 D WfdsService: WifiP2pState is changed : false
08-10 13:33:34.552  1945  2312 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-10 13:33:34.552  1945  2312 D WfdsService: Set the WFDS Monitor: false
08-10 13:33:34.553  1945  2312 D WfdsMonitor: WFDS Monitor is stopped
08-10 13:33:34.553  1945  2312 D WfdsService: STATE : WfdsDisabledState - enter
08-10 13:33:34.553  1945  7302 D CtrlSupplicant: Received on exit socket, terminate
08-10 13:33:34.553  1945  7302 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-10 13:33:34.553  1945  7302 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-10 13:33:34.553  1945  7302 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-10 13:33:34.553  1945  2313 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-10 13:33:34.553  1945  2312 W WfdsService: DefaultState - msg [9445378] is not handled
08-10 13:33:34.554  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 13:33:34.556  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 13:33:34.556  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-10 13:33:34.558  1605  1605 D StatusBar.NetworkController: refreshView,s: Data not connected!! Set no data type icon / Roaming
08-10 13:33:34.558  7117  7117 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-10 13:33:34.558  7117  7117 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-10 13:33:34.563  4325  7464 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
08-10 13:33:34.564  7182  7182 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:33:34
08-10 13:33:34.565  7182  7182 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-10 13:33:34.565  7182  7182 D Weather.Utils: 2 : All the weather widget is gone.
08-10 13:33:34.565  7182  7182 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-10 13:33:34.565  7182  7182 D WeatherAncestor: connectivity changed - connection : true
08-10 13:33:34.565  7182  7182 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@125b882
08-10 13:33:34.567  3538  7463 V DownloadManager: processing inserted download 4
08-10 13:33:34.567  7182  7182 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-10 13:33:34.567  7182  7182 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-10 13:33:34.567  7182  7182 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-10 13:33:34.567  7182  7182 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-10 13:33:34.567  7182  7182 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:33:34
08-10 13:33:34.568  4325  4325 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
08-10 13:33:34.568  4325  4325 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
08-10 13:33:34.568  3538  7463 V DownloadManager: processing inserted download 7
08-10 13:33:34.568  4325  4325 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
08-10 13:33:34.569  3538  7463 V DownloadManager: processing inserted download 8
08-10 13:33:34.569  4325  4325 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
08-10 13:33:34.569  3538  7463 V DownloadManager: processing inserted download 9
08-10 13:33:34.570  3538  7463 V DownloadManager: processing inserted download 10
08-10 13:33:34.571  3538  7463 V DownloadManager: processing inserted download 11
08-10 13:33:34.572  4325  4325 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
08-10 13:33:34.572  3538  7463 V DownloadManager: processing inserted download 12
08-10 13:33:34.573  3538  7463 V DownloadManager: processing inserted download 13
08-10 13:33:34.573   306   896 D CommandListener: Clearing all IP addresses on wlan0
08-10 13:33:34.574  3538  7463 V DownloadManager: processing inserted download 14
08-10 13:33:34.575  3538  7463 V DownloadManager: processing inserted download 16
08-10 13:33:34.575  1031  1545 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-10 13:33:34.575  1031  1545 D DSQN    : disableDataServiceNotify
08-10 13:33:34.575  1031  1545 D DSQN    : stop dsqn bin
08-10 13:33:34.576  1031  1539 D WifiNative-p2p0: doBoolean: TERMINATE
08-10 13:33:34.577  1031  1031 D WifiHS20: hidePasspointNotification off =false
08-10 13:33:34.577  1031  1539 D WifiNative-p2p0: TERMINATE: returned true
08-10 13:33:34.577  1031  1539 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-10 13:33:34.577  1031  1539 E WifiStateMachine: useWiFiOffloading() : false
08-10 13:33:34.577  1031  1539 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-10 13:33:34.577  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 13:33:34.577  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 13:33:34.577  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-10 13:33:34.579  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-10 13:33:34.579  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-10 13:33:34.580  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 13:33:34.581  1031  1545 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-10 13:33:34.581  1031  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 13:33:34.581  1031  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-10 13:33:34.582  1031  1545 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-10 13:33:34.582  1031  1545 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-10 13:33:34.582  1605  2072 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-10 13:33:34.582  1031  7360 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-10 13:33:34.582  1031  7360 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-10 13:33:34.582  1031  7360 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-10 13:33:34.582  1031  1545 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-10 13:33:34.583  1031  1545 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-10 13:33:34.583  1031  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-10 13:33:34.583  1031  1545 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-10 13:33:34.583  1031  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-10 13:33:34.584  1031  1537 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-10 13:33:34.584   306  7480 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-10 13:33:34.584  1031  1094 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-10 13:33:34.585  1031  1031 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-10 13:33:34.586  1945  1945 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-10 13:33:34.588  1031  1031 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-10 13:33:34.588  1031  1031 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-10 13:33:34.588  1031  1031 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-10 13:33:34.588  1031  1031 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-10 13:33:34.588  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-10 13:33:34.588  1031  1031 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-10 13:33:34.590  1031  1545 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-10 13:33:34.590  1031  1545 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 13:33:34.590  1031  1545 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 13:33:34.590  1031  1545 D NetworkManagementService: Removing idletimer
08-10 13:33:34.590  1031  1545 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 13:33:34.590  1031  1545 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-10 13:33:34.590  1031  1537 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-10 13:33:34.590  1031  1539 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 13:33:34.591  1031  1539 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-10 13:33:34.591  1031  1031 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-10 13:33:34.591  1031  1031 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-10 13:33:34.591  1031  1031 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-10 13:33:34.591  1031  1031 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-10 13:33:34.591  1856  1856 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 13:33:34.591  1856  1856 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-10 13:33:34.596  6971  7472 I FormManager: Network unavailable (Unable to resolve host "static-avc.lglime.com": No address associated with hostname, URL : http://static-avc.lglime.com/avc/list/FORMMANAGER_lastUpdatedTime.json)
08-10 13:33:34.599  6729  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 13:33:34.599  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 13:33:34.599  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 13:33:34.599  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 13:33:34.599  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 13:33:34.599  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 13:33:34.599  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 13:33:34.599  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 13:33:34.599  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 13:33:34.599  6729  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 13:33:34.599  6729  6729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 13:33:34.600  6729  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 13:33:34.600  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 13:33:34.600  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 13:33:34.600  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 13:33:34.600  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 13:33:34.600  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 13:33:34.600  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 13:33:34.600  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 13:33:34.600  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 13:33:34.600  6729  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 13:33:34.600  6729  6729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 13:33:34.600  6729  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 13:33:34.600  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 13:33:34.600  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 13:33:34.600  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 13:33:34.600  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 13:33:34.600  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 13:33:34.600  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 13:33:34.600  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 13:33:34.600  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 13:33:34.600  6729  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 13:33:34.600  6729  6729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 13:33:34.601  6357  6357 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 13:33:34.602  3538  3538 V DownloadManager: DownloadService onDestroy
08-10 13:33:34.605  6901  6901 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-10 13:33:34.605  6901  6901 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-10 13:33:34.605  6901  6901 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-10 13:33:34.606  6971  7472 V FormManager: Network unavailable.
08-10 13:33:34.608  6876  6876 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-10 13:33:34.612  7283  7283 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-10 13:33:34.612  7283  7283 I wpa_supplicant: monitor socket send errors count : 1
08-10 13:33:34.612  7283  7283 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1945-4\x00 that cannot receive messages
08-10 13:33:34.613  1031  7301 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-10 13:33:34.613  1031  7301 D WifiMonitor: Dropping event because (p2p0) is stopped
08-10 13:33:34.617  6971  7472 V FormManager: Network unavailable.
08-10 13:33:34.619  6876  6876 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 13:33:34.623  6971  7472 V FormManager: Network unavailable.
,08-10 13:33:34.628  6933  6933 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-10 13:33:34.628  6933  6933 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-10 13:33:34.629  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-10 13:33:34.629  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 13:33:34.630  6933  6933 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-10 13:33:34.630  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 13:33:34.630  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 13:33:34.635  6357  6357 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 13:33:34.637  7283  7283 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-10 13:33:34.637  1031  7301 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-10 13:33:34.637  1031  7301 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-10 13:33:34.637  1031  7301 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-10 13:33:34.638  1031  7301 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-10 13:33:34.638  7283  7283 W wpa_supplicant: USIM:  scard_deinit function
08-10 13:33:34.638  1031  7301 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-10 13:33:34.638  1031  7301 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-10 13:33:34.638  1031  1096 D Tethering: InitialState.processMessage what=4
08-10 13:33:34.638  6901  6901 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-10 13:33:34.639  6901  6901 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-10 13:33:34.639  6901  6901 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-10 13:33:34.639  1031  1539 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=361845
08-10 13:33:34.639  1031  1096 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-10 13:33:34.639  1031  1539 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=361845
08-10 13:33:34.640  1031  1539 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=361846  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-10 13:33:34.640  1031  1539 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=361846  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-10 13:33:34.640  1031  1539 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-10 13:33:34.640  1031  1539 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-10 13:33:34.642  6876  6876 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-10 13:33:34.651  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-10 13:33:34.651  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 13:33:34.652  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 13:33:34.656  6876  6876 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 13:33:34.659  6933  6933 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-10 13:33:34.659  6933  6933 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-10 13:33:34.660  6933  6933 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-10 13:33:34.663  6357  6357 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 13:33:34.665  6901  6901 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-10 13:33:34.665  6901  6901 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-10 13:33:34.665  6901  6901 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-10 13:33:34.668  6876  6876 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-10 13:33:34.672  6876  6876 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 13:33:34.675  6933  6933 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-10 13:33:34.675  6933  6933 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-10 13:33:34.676  6933  6933 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-10 13:33:34.680  6901  6901 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-10 13:33:34.683  6876  6876 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-10 13:33:34.686  6971  7484 W FormManager: Network not available. Please check & try again.
,08-10 13:33:34.687  6971  7485 V FormManager: Network unavailable.
08-10 13:33:34.688  6876  6876 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 13:33:34.691  6971  7485 V FormManager: Network unavailable.
08-10 13:33:34.699  6876  6876 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED,
08-10 13:33:34.699  6876  6876 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-10 13:33:34.699  6876  6876 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-10 13:33:34.699  6876  6876 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-10 13:33:34.699  6876  6876 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-10 13:33:34.700  6876  6876 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-10 13:33:34.700  6876  6876 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-10 13:33:34.700  6876  6876 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-10 13:33:34.700  6876  6876 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-10 13:33:34.700  6876  6876 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-10 13:33:34.700  6876  6876 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-10 13:33:34.712  7283  7283 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-10 13:33:34.713  1031  7301 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-10 13:33:34.713  1031  7301 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-TERMINATING 
08-10 13:33:34.713  1031  7301 D WifiMonitor: Disconnecting from the supplicant, no more events
08-10 13:33:34.714  1031  1539 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 44 0
08-10 13:33:34.733  1031  7361 D DhcpStateMachine: StoppedState
08-10 13:33:34.733  1031  7361 D DhcpStateMachine: StoppedState{ when=-187ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,08-10 13:33:34.762  7201  7231 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,08-10 13:33:34.816  1945  1945 D WfdsService: Supplicant Connection state is changed : false
,08-10 13:33:34.817  1945  2312 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
,08-10 13:33:34.817  1945  2312 D WfdsService: Set the WFDS Monitor: false
08-10 13:33:34.817  1945  2312 D WfdsMonitor: WFDS Monitor is stopped
08-10 13:33:34.818  1031  1539 D WifiOffDelayIfNotUsed: stopMonitoring
08-10 13:33:34.818  1031  1539 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-10 13:33:34.818  1031  1539 E WifiStateMachine: useWiFiOffloading() : false
08-10 13:33:34.818  1031  1539 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-10 13:33:34.821  4325  4325 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-10 13:33:34.821  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-10 13:33:34.823  1945  1945 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-10 13:33:34.823  1031  1031 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-10 13:33:34.823  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 13:33:34.824  1031  1543 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-10 13:33:34.824  1031  1543 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-10 13:33:34.824  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 13:33:34.825  4325  4325 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-10 13:33:34.827  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 13:33:34.827  2514  2514 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 13:33:34.830  4325  4325 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-10 13:33:34.833  4325  4325 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-10 13:33:34.840  4325  7488 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-10 13:33:34.841  6901  6901 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-10 13:33:34.841  6901  6901 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-10 13:33:34.841  6901  6901 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-10 13:33:34.846  4325  7489 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-10 13:33:34.846  4325  7489 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-10 13:33:34.849  6876  6876 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-10 13:33:34.850  6971  7491 W FormManager: Network not available. Please check & try again.
08-10 13:33:34.853  6971  7492 V FormManager: Network unavailable.
,08-10 13:33:34.855  6876  6876 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 13:33:34.855  6971  7492 V FormManager: Network unavailable.
08-10 13:33:35.023  1031  1539 E WifiStateMachine:  InitialState CMD_ON_QUIT 0 0
,08-10 13:33:35.024  1031  1539 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-10 13:33:35.868  1031  2373 I ActivityManager: Killing 6950:com.lge.settings.easy/1000 (adj 15): empty #17
,08-10 13:33:35.899  1031  2006 W libprocessgroup: failed to open /acct/uid_1000/pid_6950/cgroup.procs: No such file or directory
,08-10 13:33:37.366  1031  1539 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1950002134] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-10 13:33:37.368  1031  1539 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:1950002136] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-10 13:33:37.587  1031  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-10 13:33:37.600  1031  1096 D Tethering: MasterInitialState.processMessage what=3
08-10 13:33:37.614  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 13:33:37.619  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 13:33:37.621  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 13:33:37.623  1031  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-10 13:33:37.627  1031  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-10 13:33:37.631  1031  1096 D Tethering: MasterInitialState.processMessage what=3
08-10 13:33:37.640  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 13:33:37.643  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 13:33:37.645  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 13:33:37.647  6357  6357 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-10 13:33:37.649  6357  6900 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-10 13:33:37.660  5771  5771 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-10 13:33:37.670  5771  5771 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-10 13:33:37.687  2193  2193 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-10 13:33:37.705  7060  7060 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-10 13:33:37.705  7060  7060 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-10 13:33:37.705  7060  7060 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-10 13:33:37.705  7060  7060 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-10 13:33:37.709  7060  7060 I AppUp4:CustModeStarterReceiver: onReceive
08-10 13:33:37.713  7060  7060 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@866a964
08-10 13:33:37.713  7060  7060 D AppUp4:CustFacade: isCustomizationCompleted : false
08-10 13:33:37.713  7060  7060 D AppUp4:CustFacade: isPhone : true
08-10 13:33:37.714  7060  7060 D AppUp4:CustModeStarterReceiver: begin check event
08-10 13:33:37.714  7060  7060 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-10 13:33:37.718  4325  4325 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-10 13:33:37.719  4325  4325 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-10 13:33:37.720  4325  4325 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-10 13:33:37.726  4325  4325 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-10 13:33:37.733  7089  7089 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-10 13:33:37.757  1031  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-10 13:33:37.762  4325  7507 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-10 13:33:37.769  4325  7508 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-10 13:33:37.769  4325  7508 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-10 13:33:37.773  1031  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-10 13:33:37.773  1031  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-10 13:33:37.775  7089  7516 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 13:33:37.783  3485  3485 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-10 13:33:37.783  3485  3485 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-10 13:33:37.783  3485  3485 I LgeMiscReceiver: networkInfo.isConnected() = false
08-10 13:33:37.785  6971  7521 W FormManager: Network not available. Please check & try again.
,08-10 13:33:37.787  6971  7522 V FormManager: Network unavailable.
,08-10 13:33:37.789  7117  7117 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-10 13:33:37.789  7117  7117 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-10 13:33:37.794  6971  7522 V FormManager: Network unavailable.
08-10 13:33:37.800  7182  7182 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:33:37
,08-10 13:33:37.804  7182  7182 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-10 13:33:37.804  7182  7182 D Weather.Utils: 2 : All the weather widget is gone.
08-10 13:33:37.805  7182  7182 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-10 13:33:37.805  7182  7182 D WeatherAncestor: connectivity changed - connection : true
08-10 13:33:37.805  7182  7182 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@125b882
08-10 13:33:37.806  7182  7182 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-10 13:33:37.806  7182  7182 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-10 13:33:37.806  7182  7182 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-10 13:33:37.806  7182  7182 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-10 13:33:37.806  7182  7182 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:33:37
08-10 13:33:37.825  1031  1773 I ActivityManager: Killing 7343:com.lge.bnr/1000 (adj 15): empty #17
,08-10 13:33:37.857  1031  2006 W libprocessgroup: failed to open /acct/uid_1000/pid_7343/cgroup.procs: No such file or directory
,08-10 13:33:37.881  6357  6357 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-10 13:33:37.885  6357  6900 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-10 13:33:37.921  2193  2193 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-10 13:33:37.935  7060  7060 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-10 13:33:37.936  7060  7060 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-10 13:33:37.936  7060  7060 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-10 13:33:37.936  7060  7060 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-10 13:33:37.942  7060  7060 I AppUp4:CustModeStarterReceiver: onReceive
08-10 13:33:37.948  7060  7060 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@866a964
08-10 13:33:37.948  7060  7060 D AppUp4:CustFacade: isCustomizationCompleted : false
08-10 13:33:37.948  7060  7060 D AppUp4:CustFacade: isPhone : true
08-10 13:33:37.949  7060  7060 D AppUp4:CustModeStarterReceiver: begin check event
08-10 13:33:37.949  7060  7060 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
,08-10 13:33:37.954  4325  4325 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-10 13:33:37.955  4325  4325 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-10 13:33:37.959  4325  4325 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-10 13:33:37.964  4325  4325 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-10 13:33:37.977  4325  7527 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-10 13:33:37.981  7089  7089 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-10 13:33:37.983  4325  7528 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-10 13:33:37.983  4325  7528 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-10 13:33:38.010  7089  7529 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-10 13:33:38.017  6971  7531 W FormManager: Network not available. Please check & try again.
08-10 13:33:38.019  3485  3485 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-10 13:33:38.019  3485  3485 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-10 13:33:38.020  3485  3485 I LgeMiscReceiver: networkInfo.isConnected() = false
08-10 13:33:38.025  7117  7117 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-10 13:33:38.026  7117  7117 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-10 13:33:38.035  6971  7532 V FormManager: Network unavailable.
08-10 13:33:38.043  7182  7182 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:33:38
,08-10 13:33:38.043  6971  7532 V FormManager: Network unavailable.
,08-10 13:33:38.044  7182  7182 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-10 13:33:38.044  7182  7182 D Weather.Utils: 2 : All the weather widget is gone.
08-10 13:33:38.045  7182  7182 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-10 13:33:38.045  7182  7182 D WeatherAncestor: connectivity changed - connection : true
08-10 13:33:38.046  7182  7182 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@125b882
08-10 13:33:38.047  7182  7182 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-10 13:33:38.047  7182  7182 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-10 13:33:38.047  7182  7182 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-10 13:33:38.047  7182  7182 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-10 13:33:38.047  7182  7182 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:33:38
08-10 13:33:39.514  1031  1944 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 13:33:39.515  1031  1944 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-10 13:33:39.539  1031  1031 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-10 13:33:39.540  1031  1031 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-10 13:33:39.540  1031  1031 D Ulp_jni : JNI:system_update. Event-4
,08-10 13:33:39.543  1031  1096 D BluetoothManagerService: Message: 1
08-10 13:33:39.543  1031  1096 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-10 13:33:39.547  1031  1538 D LGWifiP2pService: P2pDisabledState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-10 13:33:39.547  1031  1538 D LGWifiP2pService: DefaultState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-10 13:33:39.571  1031  1096 D BluetoothManagerService: Message: 20
08-10 13:33:39.571  1031  1096 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1940aa4d:true
,08-10 13:33:39.575  6994  6994 D BluetoothAdapterState: make
08-10 13:33:39.580  6994  6994 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-10 13:33:39.580  1031  1539 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
08-10 13:33:39.581  1031  1539 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
08-10 13:33:39.581  6994  6994 I bluedroid-qcom: init
08-10 13:33:39.583  6994  7544 I BluetoothAdapterState: Entering OffState
08-10 13:33:39.584  6994  6994 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-10 13:33:39.584  6994  6994 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-10 13:33:39.584  6994  6994 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-10 13:33:39.584  6994  6994 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-10 13:33:39.584  6994  6994 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
,08-10 13:33:39.588  6994  6994 I bluedroid-qcom: get_profile_interface socket
08-10 13:33:39.588  6994  6994 I bluedroid-qcom: get_profile_interface map_client
08-10 13:33:39.590  6994  7548 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-10 13:33:39.582  7547  7547 W bdaddr_loader: type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-10 13:33:39.582  7547  7547 W bdaddr_loader: type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-10 13:33:39.601  7547  7547 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-10 13:33:39.601  7547  7547 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-10 13:33:39.601  7547  7547 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,08-10 13:33:39.607  1031  1031 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-10 13:33:39.608  1031  1096 D BluetoothManagerService: Message: 40
08-10 13:33:39.608  1031  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-10 13:33:39.608  6994  7013 I bluedroid-qcom: config_hci_snoop_log
08-10 13:33:39.610  1031  1096 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-10 13:33:39.610  1031  1096 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-10 13:33:39.612  7547  7547 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-10 13:33:39.617  6994  7544 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,08-10 13:33:39.621  6994  7548 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-10 13:33:39.623  7547  7547 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-10 13:33:39.623  7547  7547 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-10 13:33:39.625  1031  1031 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-10 13:33:39.626  1031  1031 D BluetoothManagerService: Stored Bluetooth name: G3
08-10 13:33:39.626  6994  7548 D BluetoothAdapterProperties: Name is: G3
08-10 13:33:39.626  6994  7544 D BluetoothAdapterProperties: Setting state to 11
08-10 13:33:39.626  6994  7544 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-10 13:33:39.627  1031  1096 D BluetoothManagerService: Message: 60
08-10 13:33:39.627  1031  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-10 13:33:39.627  1031  1096 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
,08-10 13:33:39.635  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-10 13:33:39.637  1945  1945 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-10 13:33:39.638  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 13:33:39.641  6876  6876 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-10 13:33:39.645  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 13:33:39.651  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 13:33:39.652  6994  6994 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-10 13:33:39.652  6994  6994 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-10 13:33:39.652  6994  6994 V BluetoothPbapReceiver: ***********state = 11
08-10 13:33:39.659  2193  2193 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-10 13:33:39.685  6994  7544 I LGBluetoothServiceJni: classInitNative: succeeds
,08-10 13:33:39.728  1031  1578 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7565 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-10 13:33:39.730  6994  7544 D BluetoothBondStateMachine: make
08-10 13:33:39.734  6994  7574 I BluetoothBondStateMachine: StableState(): Entering Off State
08-10 13:33:39.734  6994  7544 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@125b882
08-10 13:33:39.735  6994  7544 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-10 13:33:39.735  6994  7544 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@125b882
08-10 13:33:39.735  6994  7544 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-10 13:33:39.735  6994  7544 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-10 13:33:39.739  6994  7544 E BluetoothAdapterService: File transfer profiles supported!!
08-10 13:33:39.745  6994  7544 E BluetoothAdapterService: File transfer profiles supported!!
08-10 13:33:39.746  6994  6994 D HeadsetService: Received start request. Starting profile...
,08-10 13:33:39.747  6994  6994 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-10 13:33:39.747  6994  6994 D LGBluetoothHfpAdapter: Version 1.6
08-10 13:33:39.750  6994  6994 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-10 13:33:39.751  6994  7544 E BluetoothAdapterService: File transfer profiles supported!!
08-10 13:33:39.751  6994  6994 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-10 13:33:39.752  6994  6994 D HeadsetStateMachine: make
08-10 13:33:39.756  6994  7544 E BluetoothAdapterService: File transfer profiles supported!!
08-10 13:33:39.760  6994  7544 E BluetoothAdapterService: File transfer profiles supported!!
08-10 13:33:39.764  6994  7544 E BluetoothAdapterService: File transfer profiles supported!!
,08-10 13:33:39.775  6994  7544 E BluetoothAdapterService: File transfer profiles supported!!
08-10 13:33:39.789  6994  6994 D LgDataFeature: LgDataFeature() Constructor: none
08-10 13:33:39.789  6994  6994 D LgDataFeature: LgDataFeature() Constructor Done, null
08-10 13:33:39.791  6994  7544 V LGMDMManager: Create singleton instance
08-10 13:33:39.793  6994  7544 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-10 13:33:39.795  6994  6994 D HeadsetStateMachine: max_hf_connections = 1
08-10 13:33:39.795  6994  6994 I bluedroid-qcom: get_profile_interface handsfree
08-10 13:33:39.797  6994  6994 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-10 13:33:39.798   310   310 V AudioPolicyService: registerClient() client 0xb1019500, uid 1002
08-10 13:33:39.798   310  1386 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-10 13:33:39.798   310  1386 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-10 13:33:39.798   310  1386 V AudioPolicyManagerEx: getOutput() returns output 2
08-10 13:33:39.798  6994  6994 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-10 13:33:39.798   310  1387 V AudioFlinger: registerClient() client 0xb101a070, pid 6994
08-10 13:33:39.799   310  1382 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-10 13:33:39.799   310  1382 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-10 13:33:39.799  1031  1980 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-10 13:33:39.799  1031  1980 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-10 13:33:39.799  6994  6994 V ToneGenerator: Create Track: 0xb4928080
08-10 13:33:39.799   310  1381 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-10 13:33:39.799  6994  7013 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-10 13:33:39.799   310  1381 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-10 13:33:39.800  6994  7013 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-10 13:33:39.800  6994  6994 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-10 13:33:39.800  6994  6994 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-10 13:33:39.800  1031  2373 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-10 13:33:39.800  1031  2373 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-10 13:33:39.800   310  2199 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-10 13:33:39.800   310  2199 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-10 13:33:39.800   310  2199 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-10 13:33:39.800   310  2199 V AudioPolicyManagerEx: getOutput() returns output 2
08-10 13:33:39.800  1605  1621 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-10 13:33:39.800  1605  1621 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-10 13:33:39.800  6994  7013 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-10 13:33:39.800  6994  7013 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-10 13:33:39.800  1605  1621 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-10 13:33:39.800  1605  1621 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-10 13:33:39.800   310  2199 I AudioFlinger: isAudioPlaybackHookOn() false
08-10 13:33:39.801  1856  4020 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-10 13:33:39.801  1856  4020 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-10 13:33:39.801  1856  4020 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-10 13:33:39.801  1856  4020 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-10 13:33:39.801   310  1386 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-10 13:33:39.801   310  1386 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-10 13:33:39.801   310  1386 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-10 13:33:39.801   310  1386, V AudioPolicyManagerEx: getOutput() returns output 2
08-10 13:33:39.801  6994  6994 V AudioSystem: getLatency() output 2, latency 50
08-10 13:33:39.801  6994  6994 V AudioSystem: getFrameCount() output 2, frameCount 960
08-10 13:33:39.801  6994  6994 V AudioTrack: createTrack_l() output 2 afLatency 50
08-10 13:33:39.801  3485  3501 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-10 13:33:39.801  3485  3501 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-10 13:33:39.801  3485  3501 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-10 13:33:39.801  3485  3501 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-10 13:33:39.802   310   310 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-10 13:33:39.802   310   310 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-10 13:33:39.802   310   310 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-10 13:33:39.802   310   310 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-10 13:33:39.802   310   310 V AudioFlinger: createTrack() lSessionId: 22
08-10 13:33:39.803  6994  6994 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-10 13:33:39.803   310   310 V AudioFlinger: acquiring 22 from 6994, for 6994
08-10 13:33:39.803   310   310 V AudioFlinger:  added new entry for 22
08-10 13:33:39.803  6994  6994 V ToneGenerator: ToneGenerator INIT OK, time: 367021
08-10 13:33:39.803  6994  6994 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@125b882
,08-10 13:33:39.808  6994  6994 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@125b882
08-10 13:33:39.809  6994  7584 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-10 13:33:39.809  6994  7584 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-10 13:33:39.809  6994  7584 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-10 13:33:39.809  6994  7584 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-10 13:33:39.809  6994  6994 D A2dpService: Received start request. Starting profile...
08-10 13:33:39.809   310  1387 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6994
08-10 13:33:39.810   310  1387 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-10 13:33:39.810   310  1387 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-10 13:33:39.810  6994  6994 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-10 13:33:39.810   310  1387 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-10 13:33:39.810   310  1387 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-10 13:33:39.810   310  1387 V voice   : voice_set_parameters: exit with code(0)
08-10 13:33:39.810   310  1387 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-10 13:33:39.810   310  1387 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-10 13:33:39.810   310  1387 V msm8974_platform: platform_set_parameters: exit with code(0)
08-10 13:33:39.810   310  1387 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-10 13:33:39.811   310  1387 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-10 13:33:39.811   310  1387 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-10 13:33:39.811  6994  7584 V ToneGenerator: ToneGenerator destructor
08-10 13:33:39.811  6994  7584 V ToneGenerator: stopTone
08-10 13:33:39.811  6994  6994 V Avrcp   : make
08-10 13:33:39.811  6994  7584 V ToneGenerator: Delete Track: 0xb4928080
08-10 13:33:39.812  6994  6994 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-10 13:33:39.812  6994  6994 I bluedroid-qcom: get_profile_interface avrcp
08-10 13:33:39.812  6994  7584 V AudioTrack: ~AudioTrack, releasing session id from 6994 on behalf of 6994
08-10 13:33:39.812   310   310 V AudioFlinger: releasing 22 from 6994 for 6994
08-10 13:33:39.812   310   310 V AudioFlinger:  decremented refcount to 0
08-10 13:33:39.812   310   310 V AudioFlinger: purging stale effects
08-10 13:33:39.812   310   310 V AudioPolicyService: AudioCommandThread() adding release output 2
08-10 13:33:39.812   310   310 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-10 13:33:39.812   310   310 V AudioFlinger: PlaybackThread::Track destructor
08-10 13:33:39.812   310  1260 V AudioPolicyService: AudioCommandThread() waking up
08-10 13:33:39.812   310   310 V AudioFlinger: removeClient_l() pid 6994, calling pid 310
08-10 13:33:39.812   310  1260 V AudioPolicyService: AudioCommandThread() processing release output 2
08-10 13:33:39.812   310  1260 V AudioPolicyManager: releaseOutput() 2
08-10 13:33:39.812   310  1260 V AudioPolicyService: AudioCommandThread() going to sleep
08-10 13:33:39.818  6994  6994 V AudioManager: registerRemoteController: size of Media player list: 0
,08-10 13:33:39.820  6994  6994 E AudioManager: No RCC entry present to update
08-10 13:33:39.820  6994  6994 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-10 13:33:39.822  6994  6994 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-10 13:33:39.823  6994  6994 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-10 13:33:39.823  6994  6994 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-10 13:33:39.827  6994  6994 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-10 13:33:39.862  7565  7565 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
,08-10 13:33:39.863  7565  7565 W LG Account v2.2: No ProfileInfo entries
,08-10 13:33:39.863  7565  7565 I LG Account v2.2: isEnabled: false
08-10 13:33:39.863  7565  7565 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-10 13:33:39.864  7565  7565 I Feature : [Lifetracker]Country: EU
08-10 13:33:39.864  7565  7565 I Feature : [Lifetracker]Operator: OPEN
08-10 13:33:39.864  7565  7565 I Feature : [Lifetracker]Ranking support: false
08-10 13:33:39.864  7565  7565 I Feature : [Lifetracker]Comfort support: false
08-10 13:33:39.864  7565  7565 I Feature : [Lifetracker]Accessory: true
08-10 13:33:39.864  7565  7565 I Feature : [Lifetracker]Health device: true
08-10 13:33:39.864  7565  7565 I Feature : [Lifetracker]Extra Pedometer: false
08-10 13:33:39.865  7565  7565 I Feature : [Lifetracker]Blood glucose device: false
08-10 13:33:39.865  7565  7565 I Feature : [Lifetracker]Device Number: 3
08-10 13:33:39.882  6876  6876 D BluetoothPermissionRequest: onReceive
,08-10 13:33:39.887  6876  6876 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-10 13:33:39.918  1031  1578 V SIM_STK : Menu title from STK is T-Mobile
08-10 13:33:39.918  1031  1578 V SIM_STK : Menu title from STK is T-Mobile
,08-10 13:33:40.035  1031  1046 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-10 13:33:40.045  6994  6994 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-10 13:33:40.049  6994  6994 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
,08-10 13:33:40.050  6994  6994 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-10 13:33:40.050  6994  6994 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-10 13:33:40.050  6994  6994 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-10 13:33:40.051  6994  6994 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-10 13:33:40.051  6994  6994 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-10 13:33:40.051  6994  6994 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-10 13:33:40.051  6994  6994 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-10 13:33:40.051  6994  6994 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-10 13:33:40.051  6994  6994 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-10 13:33:40.052  6994  6994 I BluetoothA2dpServiceJni: classInitNative
08-10 13:33:40.052  6994  6994 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-10 13:33:40.052  6994  6994 D A2dpStateMachine: make
08-10 13:33:40.056  6994  6994 I bluedroid-qcom: get_profile_interface a2dp
08-10 13:33:40.056  6994  7592 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-10 13:33:40.062  6994  6994 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-10 13:33:40.062  6994  6994 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-10 13:33:40.063  6994  6994 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@125b882
08-10 13:33:40.065  6994  6994 I BluetoothHidServiceJni: classInitNative: succeeds
08-10 13:33:40.065  6994  7591 D A2dpStateMachine: Enter Disconnected: -2
,08-10 13:33:40.066  6994  6994 D HidService: Received start request. Starting profile...
,08-10 13:33:40.066  6994  6994 I bluedroid-qcom: get_profile_interface hidhost
08-10 13:33:40.066  6994  6994 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@125b882
08-10 13:33:40.067  6994  6994 I BluetoothHealthServiceJni: classInitNative: succeeds
08-10 13:33:40.068  6994  6994 D HealthService: Received start request. Starting profile...
08-10 13:33:40.070  6994  6994 I bluedroid-qcom: get_profile_interface health
08-10 13:33:40.070  6994  6994 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-10 13:33:40.070  6994  6994 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@125b882
08-10 13:33:40.071  6994  6994 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-10 13:33:40.072  6994  6994 D PanService: Received start request. Starting profile...
08-10 13:33:40.072  6994  6994 D BluetoothPanServiceJni: initializeNative(L110): pan
08-10 13:33:40.072  6994  6994 I bluedroid-qcom: get_profile_interface pan
08-10 13:33:40.079  6994  6994 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-10 13:33:40.079  6994  6994 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@125b882
08-10 13:33:40.080  6994  6994 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
,08-10 13:33:40.088  6994  6994 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-10 13:33:40.089  6994  6994 D BtGatt.GattService: Received start request. Starting profile...
08-10 13:33:40.089  6994  6994 D BtGatt.GattService: start()
08-10 13:33:40.089  6994  6994 I bluedroid-qcom: get_profile_interface gatt
08-10 13:33:40.090  6994  6994 D BtGatt.AdvertiseManager: advertise manager created
08-10 13:33:40.100  6994  6994 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@125b882
,08-10 13:33:40.102  6994  6994 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@125b882
08-10 13:33:40.102  6994  6994 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-10 13:33:40.103  6994  6994 V BluetoothMapService: BluetoothMapBinder()
08-10 13:33:40.104  6994  6994 D BluetoothMapService: Received start request. Starting profile...
08-10 13:33:40.104  6994  6994 D BluetoothMapService: start()
08-10 13:33:40.109  6994  6994 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-10 13:33:40.109  6994  6994 D BluetoothMapEmailAppObserver: createReceiver()
08-10 13:33:40.110  6994  6994 D BluetoothMapEmailAppObserver: initObservers()
08-10 13:33:40.110  6994  6994 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-10 13:33:40.120  6994  6994 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@125b882
,08-10 13:33:40.120  6994  6994 D HeadsetStateMachine: Proxy object connected
08-10 13:33:40.121  6994  6994 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-10 13:33:40.121  6994  6994 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-10 13:33:40.129  6994  6994 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-10 13:33:40.130  6994  7584 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-10 13:33:40.131  6994  7584 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-10 13:33:40.131  6994  7584 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-10 13:33:40.137  6994  6994 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-10 13:33:40.140  6994  6994 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-10 13:33:40.144  6994  6994 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-10 13:33:40.144  6994  6994 V PanService: [BTUI] SIM Extra State :ABSENT
08-10 13:33:40.148  6994  6994 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-10 13:33:40.151  6994  6994 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-10 13:33:40.151  6994  6994 V BluetoothMapService: Handler(): got msg=1
08-10 13:33:40.153  6994  7544 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
,08-10 13:33:40.153  6994  7544 I bluedroid-qcom: enable
08-10 13:33:40.153  6994  7544 I bt_hci_bdroid: init
08-10 13:33:40.157  6994  6994 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-10 13:33:40.159  6994  6994 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-10 13:33:40.159  6994  6994 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-10 13:33:40.159  6994  6994 V BluetoothSapReceiver: SapReceiver onReceive 
08-10 13:33:40.159  6994  6994 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-10 13:33:40.160  6994  6994 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-10 13:33:40.161  6994  7602 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-10 13:33:40.162  6994  7602 I bt-btu  : btu_task pending for preload complete event
08-10 13:33:40.162  6994  7544 I bt_vendor: bt-vendor : init
08-10 13:33:40.162  6994  7544 I bt_vendor: bt-vendor : get_bt_soc_type
08-10 13:33:40.162  6994  7544 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-10 13:33:40.162  6994  7544 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-10 13:33:40.162  6994  7544 D bt_userial_mct: userial_init
08-10 13:33:40.163  6994  7544 D bt_hci_bdroid: set_power 1
08-10 13:33:40.163  6994  7544 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-10 13:33:40.163  6994  7544 I bt_vendor: Starting hciattach daemon
08-10 13:33:40.163  6994  7544 I bt_vendor: try to set true
08-10 13:33:40.152  7605  7605 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-10 13:33:40.152  7605  7605 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-10 13:33:40.205  7606  7606 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-10 13:33:40.235  1031  1773 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7609 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-10 13:33:40.280  7629  7629 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-10 13:33:40.291  7630  7630 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-10 13:33:40.314  7632  7632 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-10 13:33:40.320  7609  7609 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-10 13:33:40.327  7633  7633 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-10 13:33:40.338  1031  2006 I ActivityManager: Killing 6596:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
08-10 13:33:40.341  7634  7634 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-10 13:33:40.353  7635  7635 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-10 13:33:40.365  6933  6933 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
,08-10 13:33:40.365  6933  6933 W System.err: android.os.DeadObjectException
,08-10 13:33:40.366  6933  6933 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-10 13:33:40.366  6933  6933 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-10 13:33:40.366  6933  6933 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-10 13:33:40.366  6933  6933 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-10 13:33:40.366  6933  6933 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-10 13:33:40.366  6933  6933 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-10 13:33:40.366  6933  6933 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-10 13:33:40.366  6933  6933 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-10 13:33:40.366  6933  6933 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-10 13:33:40.366  6933  6933 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-10 13:33:40.366  6933  6933 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 13:33:40.366  6933  6933 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-10 13:33:40.367  6933  6933 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-10 13:33:40.367  6933  6933 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-10 13:33:40.367  6933  6933 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-10 13:33:40.367  6933  6933 W System.err: android.os.DeadObjectException
08-10 13:33:40.367  6933  6933 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-10 13:33:40.367  6933  6933 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-10 13:33:40.367  6933  6933 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-10 13:33:40.368  6933  6933 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-10 13:33:40.368  6933  6933 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-10 13:33:40.368  6933  6933 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-10 13:33:40.368  6933  6933 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-10 13:33:40.368  6933  6933 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-10 13:33:40.368  6933  6933 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-10 13:33:40.368  6933  6933 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-10 13:33:40.368  6933  6933 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 13:33:40.368  6933  6933 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-10 13:33:40.368  6933  6933 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-10 13:33:40.368  6933  6933 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-10 13:33:40.368  6933  6933 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-10 13:33:40.369  6933  6933 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-10 13:33:40.373  7637  7637 I libmdmdetect: ESOC framework not supported
08-10 13:33:40.373  7637  7637 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
08-10 13:33:40.381  7637  7637 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-10 13:33:40.381  7637  7637 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-10 13:33:40.381  7637  7637 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-10 ,13:33:40.381  7637  7637 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-10 13:33:40.381  7637  7637 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-10 13:33:40.381  7637  7637 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-10 13:33:40.381  7637  7637 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
,08-10 13:33:40.425  7637  7639 E QC-QMI  : qmi_client [7637] 14: failed to locate client data
,08-10 13:33:40.426   484   484 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-10 13:33:40.426   484   484 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
08-10 13:33:40.466  7640  7640 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-10 13:33:40.475  1031  1772 W libprocessgroup: failed to open /acct/uid_1000/pid_6596/cgroup.procs: No such file or directory
,08-10 13:33:40.476  1031  1772 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
08-10 13:33:40.483  7641  7641 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-10 13:33:40.487  6933  6933 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-10 13:33:40.487  6933  6933 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-10 13:33:40.516  6994  7544 I bt_vendor: bluetooth satus is on
08-10 13:33:40.516  6994  7544 D bt_hci_bdroid: preload
,08-10 13:33:40.517  6994  7604 D bt_userial_mct: userial_open(port:0)
08-10 13:33:40.517  6994  7604 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-10 13:33:40.521  6994  7604 I bt_vendor: Done intiailizing UART
08-10 13:33:40.524  6994  7604 I bt_vendor: Done intiailizing UART
08-10 13:33:40.524  6994  7604 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-10 13:33:40.525  6994  7604 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-10 13:33:40.525  6994  7643 D bt_userial_mct: Entering userial_read_thread()
08-10 13:33:40.525  6994  7602 I bt-btu  : btu_task received preload complete event
08-10 13:33:40.527  6994  7602 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-10 13:33:40.527  6994  7602 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-10 13:33:40.534  6994  7602 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
,08-10 13:33:40.542  6994  7602 I         : BTE_InitTraceLevels -- TRC_HCI
08-10 13:33:40.542  6994  7602 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-10 13:33:40.542  6994  7602 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-10 13:33:40.542  6994  7602 I         : BTE_InitTraceLevels -- TRC_AVDT
08-10 13:33:40.543  6994  7602 I         : BTE_InitTraceLevels -- TRC_AVRC
08-10 13:33:40.543  6994  7602 I         : BTE_InitTraceLevels -- TRC_A2D
08-10 13:33:40.543  6994  7602 I         : BTE_InitTraceLevels -- TRC_BNEP
08-10 13:33:40.543  6994  7602 I         : BTE_InitTraceLevels -- TRC_BTM
08-10 13:33:40.543  6994  7602 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-10 13:33:40.543  6994  7602 I         : BTE_InitTraceLevels -- TRC_GAP
08-10 13:33:40.543  6994  7602 I         : BTE_InitTraceLevels -- TRC_PAN
08-10 13:33:40.543  6994  7602 I         : BTE_InitTraceLevels -- TRC_SDP
08-10 13:33:40.543  6994  7602 I         : BTE_InitTraceLevels -- TRC_GATT
08-10 13:33:40.543  6994  7602 I         : BTE_InitTraceLevels -- TRC_SMP
08-10 13:33:40.543  6994  7602 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-10 13:33:40.543  6994  7602 I         : BTE_InitTraceLevels -- TRC_BTIF
08-10 13:33:40.574  1031  2373 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7644 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-10 13:33:40.574  6933  6933 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-10 13:33:40.610  6994  7602 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-10 13:33:40.610  6994  7602 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa014d061 
08-10 13:33:40.610  6994  7602 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa014d061 
,08-10 13:33:40.628  6994  7548 E bt-btif : Calling BTA_HhEnable
08-10 13:33:40.628  6994  7548 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-10 13:33:40.628  6994  7548 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-10 13:33:40.632  6994  7548 D BluetoothAdapterProperties: Name is: G3
08-10 13:33:40.632  1031  1031 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-10 13:33:40.633  1031  1031 D BluetoothManagerService: Stored Bluetooth name: G3
08-10 13:33:40.633  6994  7602 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-10 13:33:40.633  6994  7602 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-10 13:33:40.633  6994  7602 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-10 13:33:40.633  6994  7602 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-10 13:33:40.633  6994  7602 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-10 13:33:40.634  6994  7548 D BluetoothAdapterProperties: Scan Mode:20
08-10 13:33:40.634  6994  7548 D BluetoothAdapterProperties: Discoverable Timeout:120
08-10 13:33:40.634  6994  7548 D bt_hci_bdroid: postload
08-10 13:33:40.634  6994  7604 D bt_hci_bdroid: Used up Tx Cmd credits
08-10 13:33:40.635  6994  7602 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-10 13:33:40.635  6994  7548 D bte_conf: Device ID record 1 : primary
08-10 13:33:40.635  6994  7548 D bte_conf:   vendorId            = 00c4
08-10 13:33:40.635  6994  7548 D bte_conf:   vendorIdSource      = 0001
08-10 13:33:40.635  6994  7548 D bte_conf:   product             = 13a1
08-10 13:33:40.635  6994  7548 D bte_conf:   version             = 1000
08-10 13:33:40.635  6994  7548 D bte_conf:   clientExecutableURL = 
08-10 13:33:40.635  6994  7548 D bte_conf:   serviceDescription  = 
,08-10 13:33:40.635  6994  7548 D bte_conf:   documentationURL    = 
08-10 13:33:40.635  6994  7548 D bte_conf: bte_load_did_conf no section named DID2.
08-10 13:33:40.637  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 13:33:40.637  6994  7604 D bt_hci_bdroid: Used up Tx Cmd credits
08-10 13:33:40.639  6994  7604 D bt_hci_bdroid: Used up Tx Cmd credits
08-10 13:33:40.639  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 13:33:40.622  7665  7665 W sh      : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-10 13:33:40.622  7665  7665 W sh      : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-10 13:33:40.640  6994  7548 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-10 13:33:40.640  6994  7544 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-10 13:33:40.641  6994  7544 D BluetoothAdapterProperties: ScanMode =  20
08-10 13:33:40.641  6994  7544 D BluetoothAdapterProperties: State =  11
08-10 13:33:40.641  6994  7544 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-10 13:33:40.641  6994  7544 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-10 13:33:40.641  6994  7544 D BluetoothAdapterProperties: Setting state to 12
08-10 13:33:40.641  6994  7544 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-10 13:33:40.643  6994  7548 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-10 13:33:40.652  6994  7604 D bt_hci_bdroid: Used up Tx Cmd credits
08-10 13:33:40.654  6994  7548 D BluetoothAdapterProperties: Discoverable Timeout:120
08-10 13:33:40.654  6994  7548 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-10 13:33:40.655  6994  7643 E bt_mct  : hci lib postload completed
,08-10 13:33:40.659  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 13:33:40.659  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 13:33:40.659  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 13:33:40.659  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 13:33:40.659  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 13:33:40.659  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 13:33:40.659  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 13:33:40.659  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 13:33:40.661  6994  7602 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-10 13:33:40.661  6994  7602 W bt-smp  : Plain text(LSB ~ MSB) = 12 5a 4c 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-10 13:33:40.662  6994  7602 W bt-smp  : Encrypted text(LSB ~ MSB) = 0d 40 fc 5b 20 da 57 5f 29 26 54 32 b3 49 f1 da 
08-10 13:33:40.662  6994  7602 W bt-btm  : Stopping oneshot timer
08-10 13:33:40.663  6729  6729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 13:33:40.664  1031  1096 D BluetoothManagerService: Message: 60
08-10 13:33:40.664  1031  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-10 13:33:40.664  1031  1096 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
08-10 13:33:40.666  1856  1871 D BluetoothHeadset: onBluetoothStateChange: up=true
08-10 13:33:40.666  6994  7544 I BluetoothAdapterState: Entering On State
,08-10 13:33:40.681  6994  7602 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-10 13:33:40.681  6994  7602 W bt-smp  : Plain text(LSB ~ MSB) = e1 0f 7a 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-10 13:33:40.681  6994  7602 W bt-smp  : Encrypted text(LSB ~ MSB) = fb d7 91 bd 82 f6 e1 14 80 b8 12 21 bc 35 9c 14 
08-10 13:33:40.681  6994  7602 W bt-btm  : Stopping oneshot timer
08-10 13:33:40.683  6994  7544 D LGBluetoothServiceAdapter: [BTUI] OnState
08-10 13:33:40.684  6994  7544 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-10 13:33:40.684  6994  7544 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-10 13:33:40.685  6994  7544 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-10 13:33:40.699  6994  7602 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
,08-10 13:33:40.699  6994  7602 W bt-smp  : Plain text(LSB ~ MSB) = 9b b4 4f 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-10 13:33:40.699  6994  7602 W bt-smp  : Encrypted text(LSB ~ MSB) = 7f 86 69 4f a2 ee 84 e7 e6 5b 28 1d 12 80 f1 08 
08-10 13:33:40.699  6994  7602 W bt-btm  : Stopping oneshot timer
,08-10 13:33:40.708  1856  1856 D BluetoothHeadset: Proxy object connected
08-10 13:33:40.708  1031  1096 D BluetoothA2dp: onBluetoothStateChange: up=true
08-10 13:33:40.710  1031  1031 D BluetoothA2dp: Proxy object connected
08-10 13:33:40.711  6876  6892 D BluetoothPbap: onBluetoothStateChange: up=true
08-10 13:33:40.712  7678  7678 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-10 13:33:40.714  1856  4044 D BluetoothHeadset: onBluetoothStateChange: up=true
08-10 13:33:40.714  6994  7602 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-10 13:33:40.715  6994  7602 W bt-smp  : Plain text(LSB ~ MSB) = 0e 9a 7f 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-10 13:33:40.715  6994  7602 W bt-smp  : Encrypted text(LSB ~ MSB) = 45 e1 89 c1 fe de c7 f4 ef 3a 66 9d 0f 7a 1b d6 
08-10 13:33:40.715  6994  7602 W bt-btm  : Stopping oneshot timer
08-10 13:33:40.715  1856  1856 D BluetoothHeadset: Proxy object connected
08-10 13:33:40.715  6994  7544 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-10 13:33:40.715  6876  6893 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-10 13:33:40.717  1856  4020 D BluetoothHeadset: onBluetoothStateChange: up=true
08-10 13:33:40.718  1856  1856 D BluetoothHeadset: Proxy object connected
08-10 13:33:40.718  1031  1096 D BluetoothHeadset: onBluetoothStateChange: up=true
08-10 13:33:40.718  6876  6876 D BluetoothInputDevice: Proxy object connected
08-10 13:33:40.718  6876  6876 D HidProfile: Bluetooth service connected
,08-10 13:33:40.718  1031  1031 D BluetoothHeadset: Proxy object connected
,08-10 13:33:40.719  6876  6892 D BluetoothMap: onBluetoothStateChange: up=true
08-10 13:33:40.721  6876  6893 D BluetoothPan: onBluetoothStateChange on: true
08-10 13:33:40.722  6876  6893 D BluetoothPan: onBluetoothStateChange call bindService
08-10 13:33:40.722  6876  6876 D BluetoothMap: Proxy object connected
08-10 13:33:40.722  6876  6876 D MapProfile: Bluetooth service connected
08-10 13:33:40.722  6876  6876 D BluetoothMap: getConnectedDevices()
08-10 13:33:40.723  1031  1096 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-10 13:33:40.723  1031  1096 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-10 13:33:40.725  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-10 13:33:40.725  1945  1945 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-10 13:33:40.725  1945  2120 D LGBluetoothAPIService: Message: 1
08-10 13:33:40.725  1945  2120 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-10 13:33:40.726  6994  7013 V BluetoothMapService: getConnectedDevices()
08-10 13:33:40.727  6729  6729 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
08-10 13:33:40.731  6994  7602 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-10 13:33:40.731  6994  7602 W bt-smp  : Plain text(LSB ~ MSB) = dc 22 5f 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-10 13:33:40.731  6994  7602 W bt-smp  : Encrypted text(LSB ~ MSB) = 80 39 8f 14 cb 23 df 53 ef e0 15 c7 4b bc 94 bc 
08-10 13:33:40.731  6994  7602 W bt-btm  : Stopping oneshot timer
,08-10 13:33:40.732  1031  1031 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-10 13:33:40.733  6876  6876 D BluetoothPan: BluetoothPAN Proxy object connected
08-10 13:33:40.733  6876  6876 D PanProfile: Bluetooth service connected
08-10 13:33:40.735  1945  2120 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-10 13:33:40.735  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 13:33:40.735  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 13:33:40.735  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 13:33:40.735  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 13:33:40.735  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 13:33:40.735  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 13:33:40.735  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 13:33:40.735  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 13:33:40.736  6994  6994 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-10 13:33:40.736  6994  6994 D BluetoothMapService: STATE_ON
08-10 13:33:40.738  6994  6994 D LGBluetoothAPIServer: [BTUI] onCreate()
08-10 13:33:40.738  6994  6994 D LGBluetoothAPIServer: [BTUI] onBind()
08-10 13:33:40.738  1031  1096 D BluetoothManagerService: Message: 40
08-10 13:33:40.738  1031  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-10 13:33:40.739  6876  6876 D LocalBluetoothProfileManager: Adding local A2DP profile
08-10 13:33:40.739  6994  6994 V BluetoothMapService: Handler(): got msg=1
08-10 13:33:40.739  1945  1945 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-10 13:33:40.739  1945  2120 D LGBluetoothAPIService: Message: 100
08-10 13:33:40.739  1945  2120 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-10 13:33:40.740  6994  6994 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-10 13:33:40.741  1031  1096 D BluetoothManagerService: Message: 30
08-10 13:33:40.741  6729  6729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-10 13:33:40.743  6994  7683 D BluetoothMapMasInstance: MAS initSocket()
08-10 13:33:40.744  6994  7683 D BluetoothMapMasInstance:   masId = 00
08-10 13:33:40.744  6994  7683 D BluetoothMapMasInstance:   msgTypes = 0e
08-10 13:33:40.744  6994  7683 D BluetoothMapMasInstance:   masName = SMS/MMS
08-10 13:33:40.744  6994  7683 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-10 13:33:40.745  6876  6876 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-10 13:33:40.745  1031  1908 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 13:33:40.746  6994  7683 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-10 13:33:40.747  1031  1096 D BluetoothManagerService: Message: 30
08-10 13:33:40.749  6994  7683 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-10 13:33:40.749  6994  7548 D BluetoothAdapterProperties: Scan Mode:21
08-10 13:33:40.749  6994  7548 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-10 13:33:40.749  6994  7683 V BluetoothMapMasInstance: Succeed to create listening socket 
,08-10 13:33:40.750  6994  6994 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@125b882
08-10 13:33:40.750  6994  7683 D BluetoothMapMasInstance: Accepting socket connection...
08-10 13:33:40.750  6994  6994 V BluetoothPbapService: Pbap Service onCreate
08-10 13:33:40.750  6994  6994 V BluetoothPbapService: Starting PBAP service
08-10 13:33:40.751  6994  6994 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-10 13:33:40.751  6994  6994 V BluetoothPbapService: Pbap Service onBind
08-10 13:33:40.753  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 13:33:40.753  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 13:33:40.753  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 13:33:40.753  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 13:33:40.753  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 13:33:40.753  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 13:33:40.753  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 13:33:40.753  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 13:33:40.755  6729  6729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 13:33:40.755  6994  6994 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-10 13:33:40.755  6994  6994 V BluetoothPbapService: state: 12
08-10 13:33:40.755  6994  6994 V BluetoothPbapService: Handler(): got msg=1
08-10 13:33:40.756  6994  6994 V BluetoothPbapService: Pbap Service startRfcommSocketListener
,08-10 13:33:40.758  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 13:33:40.760  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 13:33:40.761  6876  6876 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-10 13:33:40.761  6994  7684 V BluetoothPbapService: Pbap Service initSocket
08-10 13:33:40.762  1031  1980 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 13:33:40.762  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 13:33:40.763  6876  6876 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-10 13:33:40.765  6876  6876 D BluetoothA2dp: Proxy object connected
08-10 13:33:40.766  6876  6876 D A2dpProfile: Bluetooth service connected
08-10 13:33:40.766  6994  6994 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-10 13:33:40.766  6994  6994 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-10 13:33:40.766  6994  6994 V BluetoothPbapReceiver: ***********state = 12
08-10 13:33:40.767  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 13:33:40.768  6994  7684 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-10 13:33:40.771  2193  2193 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-10 13:33:40.771  6994  7684 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-10 13:33:40.772  6994  7684 V BluetoothPbapService: Succeed to create listening socket 
08-10 13:33:40.772  6994  7684 V BluetoothPbapService: Accepting socket connection...
08-10 13:33:40.773  2193  2193 D c       : Getting all permits...
08-10 13:33:40.773  2193  2193 D a       : Opening database...
08-10 13:33:40.776  2193  2193 D a       : Opening database auth.proximity.permit_store...
08-10 13:33:40.776  2193  2193 D a       : Closing database...
,08-10 13:33:40.777  6876  6876 D BluetoothPbap: Proxy object connected
08-10 13:33:40.778  6876  6876 D PbapServerProfile: Bluetooth service connected
08-10 13:33:40.778  6876  6876 D BluetoothHeadset: Proxy object connected
08-10 13:33:40.779  6876  6876 D HeadsetProfile: Bluetooth service connected
,08-10 13:33:40.784  6876  6876 D DockEventReceiver: finishStartingService: stopping service
08-10 13:33:40.788  6876  6876 D BluetoothPermissionRequest: onReceive
08-10 13:33:40.789  6876  6876 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-10 13:33:40.790  6876  6876 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-10 13:33:40.794  6994  6994 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
,08-10 13:33:40.795  6994  6994 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-10 13:33:40.799  6994  6994 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
08-10 13:33:40.809  6994  6994 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-10 13:33:40.809  6994  6994 V BtOppService: onCreate
,08-10 13:33:40.812  6994  6994 V BluetoothOppNotification: send message
08-10 13:33:40.814  6994  6994 V BtOppService: Starting RfcommListener
08-10 13:33:40.818  6994  6994 D BluetoothOppPreference: Dumping Names:  
08-10 13:33:40.818  6994  6994 D BluetoothOppPreference: {}
08-10 13:33:40.818  6994  6994 D BluetoothOppPreference: Dumping Channels:  
08-10 13:33:40.818  6994  6994 D BluetoothOppPreference: {}
08-10 13:33:40.818  6994  6994 V BtOppService: onStartCommand
08-10 13:33:40.819  6994  7693 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-10 13:33:40.821  6994  7693 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-10 13:33:40.822  6994  6994 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-10 13:33:40.822  6994  7690 V BtOppService: Deleted complete outbound shares, number =  0
08-10 13:33:40.822  6994  6994 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-10 13:33:40.823  6994  7693 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3167babf on behalf of 
,08-10 13:33:40.824  6994  6994 V BluetoothOppNotification: new notify threadi!
08-10 13:33:40.825  6994  6994 V BluetoothOppNotification: send delay message
08-10 13:33:40.825  6994  7693 V BluetoothOppNotification: update too frequent, put in queue
08-10 13:33:40.825  6994  7690 V BtOppService: Deleted complete inbound failed shares, number = 0
08-10 13:33:40.825  6994  6994 V BtOppService: start RfcommListener
08-10 13:33:40.826  6994  7693 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-10 13:33:40.826  6994  7694 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-10 13:33:40.826  6994  7693 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-10 13:33:40.826  6994  6994 V BtOppService: RfcommListener started
08-10 13:33:40.826  6994  6994 V BtOppService: ContentObserver received notification
08-10 13:33:40.826  6994  6994 V BtOppService: ContentObserver received notification
08-10 13:33:40.827  6994  7695 V BtOppRfcommListener: Starting RFCOMM listener....
08-10 13:33:40.829  1031  1047 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 13:33:40.829  6994  7695 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-10 13:33:40.830  6994  7695 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
08-10 13:33:40.831  6994  7695 V BtOppRfcommListener: Started RFCOMM listener....
08-10 13:33:40.831  6994  7695 I BtOppRfcommListener: Accept thread started.
08-10 13:33:40.831  6994  7695 V BtOppRfcommListener: Accepting connection...
08-10 13:33:40.831  6994  7694 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@12cae58c on behalf of 
08-10 13:33:40.832  6994  7693 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@289c94d5 on behalf of 
08-10 13:33:40.832  6994  7690 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-10 13:33:40.832  6994  7694 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-10 13:33:40.834  6994  7690 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@31c274ea on behalf of 
08-10 13:33:40.834  6994  6994 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@125b882
08-10 13:33:40.834  6994  6994 V BluetoothFtpService: Ftp Service onCreate
08-10 13:33:40.834  6994  6994 I BluetoothFtpService: Ftp Service onCreate
08-10 13:33:40.834  6994  7693 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-10 13:33:40.834  6994  6994 V BluetoothFtpService: Ftp Service onStartCommand
08-10 13:33:40.834  6994  6994 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-10 13:33:40.834  6994  6994 V BluetoothFtpService: Starting Listening on sockets
08-10 13:33:40.834  6994  6994 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-10 13:33:40.835  6994  6994 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-10 13:33:40.834  6994  7693 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-10 13:33:40.835  6994  6994 V BluetoothSapReceiver: SapReceiver onReceive 
08-10 13:33:40.835  6994  6994 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-10 13:33:40.835  6994  6994 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-10 13:33:40.835  6994  6994 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-10 13:33:40.836  6994  6994 V BluetoothFtpService: Handler(): got msg=1
,08-10 13:33:40.837  6994  6994 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-10 13:33:40.837  6994  6994 V BluetoothFtpService: Ftp Service initSocket
08-10 13:33:40.839  1031  2006 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 13:33:40.839  6994  6994 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-10 13:33:40.840  6994  7694 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-10 13:33:40.841  6994  7694 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@706ce78 on behalf of 
08-10 13:33:40.841  6994  7693 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@399ea951 on behalf of 
08-10 13:33:40.841  6994  7694 V BluetoothOppNotification: outbound: succ-0  fail-0
08-10 13:33:40.841  6994  7693 V BluetoothOppNotification: update too frequent, put in queue
08-10 13:33:40.843  6994  7694 V BluetoothOppNotification: outbound notification was removed.
08-10 13:33:40.843  6994  7694 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-10 13:33:40.844  6994  7693 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-10 13:33:40.844  6994  6994 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=78
08-10 13:33:40.844  6994  6994 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-10 13:33:40.844  6994  7694 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@25caf5b6 on behalf of 
08-10 13:33:40.845  6994  7694 V BluetoothOppNotification: inbound: succ-0  fail-0
08-10 13:33:40.845  6994  7696 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-10 13:33:40.846  6994  7694 V BluetoothOppNotification: inbound notification was removed.
08-10 13:33:40.846  6994  7694 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-10 13:33:40.847  6994  7694 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2f0c42b7 on behalf of 
08-10 13:33:40.857  6994  6994 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@125b882
08-10 13:33:40.857  1031  2373 I art     : Explicit concurrent mark sweep GC freed 131759(6MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/64MB, paused 2.493ms total 163.833ms
08-10 13:33:40.857  6994  6994 V BluetoothSapService: Sap Service onCreate
08-10 13:33:40.859  6994  6994 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-10 13:33:40.859  6994  6994 V BluetoothSapService: state: 12
08-10 13:33:40.859  6994  6994 V BluetoothSapService: Starting SAP server process
,08-10 13:33:40.842  7697  7697 W sapd    : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-10 13:33:40.861  6994  6994 V BluetoothSapService: SAP Service startRfcommListenerThread
08-10 13:33:40.842  7697  7697 W sapd    : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-10 13:33:40.862  6994  7698 V BluetoothSapService: Sap Service initRfcommSocket
08-10 13:33:40.862  1031  1047 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 13:33:40.862  6994  7698 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-10 13:33:40.863  6994  7698 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-10 13:33:40.863  6994  7698 V BluetoothSapService: Succeed to create listening socket 
08-10 13:33:40.863  6994  7698 V BluetoothSapService: Accepting socket connection...
08-10 13:33:40.870  7697  7697 V BT_SAP  : Event pipe created
08-10 13:33:40.870  7697  7697 V BT_SAP  : create_server_socket qcom.sap.server
08-10 13:33:40.871  7697  7697 V BT_SAP  : created socket fd 6
,08-10 13:33:40.878  7644  7644 D UEI.SmartControl: Quickset Services start...
08-10 13:33:40.879  7644  7644 I UEI.SmartControl: Manufacture = LGE
08-10 13:33:40.879  7644  7644 D UEI.SmartControl: Id = LGNevo
08-10 13:33:40.880  7644  7644 D UEI.SmartControl: File observer start...
08-10 13:33:40.881  7644  7644 E UEI.SmartControl: IR Port is disabled: false
08-10 13:33:40.881  7644  7644 D UEI.SmartControl: Starting file observer...
08-10 13:33:40.881  7644  7644 D UEI.SmartControl: Extracting JNI libs...
08-10 13:33:40.881  7644  7644 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-10 13:33:40.933  7644  7644 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-10 13:33:40.933  7644  7644 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-10 13:33:40.933  7644  7644 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-10 13:33:40.954  7644  7644 I UEI.SmartControl: --- Selecting new region: 6
,08-10 13:33:40.955  7644  7644 I UEI.SmartControl: Model = LG-D855,
08-10 13:33:40.956  7644  7644 D UEI.SmartControl: QS Service created
08-10 13:33:40.965  7644  7644 I UEI.SmartControl: Service initServices...
08-10 13:33:40.968  7644  7644 D UEI.SmartControl: QS start get config
,08-10 13:33:41.001  7644  7644 D UEI.SmartControl: Loading JNI Libs...
,08-10 13:33:41.350  7644  7644 I UEI.SmartControl: Supports setup maps: true
,08-10 13:33:41.355  7644  7644 D UEI.SmartControl: QS start statue = true Error code = 0
08-10 13:33:41.355  7644  7644 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-10 13:33:41.355  7644  7644 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-10 13:33:41.356  7644  7644 I UEI.SmartControl: ### init IR Blaster...
08-10 13:33:41.361  7644  7644 D serial_port: Configuring serial port
08-10 13:33:41.365  7644  7644 E UEI.SmartControl: UEIBLaster setting for 616
08-10 13:33:41.366  7644  7644 I UEI.SmartControl: Setting serial record hearder size = 2
08-10 13:33:41.366  7644  7644 I UEI.SmartControl: configuring settings for MAXQ616
,08-10 13:33:41.366  7644  7644 I UEI.SmartControl: Get version...
08-10 13:33:41.384  7644  7706 D UEI.SmartControl: serial port data available: 21
,08-10 13:33:41.393  2036  2036 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
08-10 13:33:41.405  1031  1390 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-10 13:33:41.410  1605  1605 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
08-10 13:33:41.420  7644  7644 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-10 13:33:41.421  7644  7644 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-10 13:33:41.421  7644  7644 I UEI.SmartControl: QS saving settings...
,08-10 13:33:41.425  7644  7644 D UEI.SmartControl: IR Blaster version: 25672567
08-10 13:33:41.464  1031  1031 D administrator: Handling package changes for user 0
,08-10 13:33:41.473  1031  1092 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7708 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
08-10 13:33:41.477  1605  1605 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
,08-10 13:33:41.481  1605  1605 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
08-10 13:33:41.507  2036  2036 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-10 13:33:41.509  7644  7706 D UEI.SmartControl: serial port data available: 4
,08-10 13:33:41.531  7708  7708 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-10 13:33:41.540  7644  7644 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-10 13:33:41.541  7644  7644 E UEI.SmartControl: Services init done
08-10 13:33:41.541  7644  7644 D UEI.SmartControl: QS Service init finished
08-10 13:33:41.543  7644  7644 D UEI.SmartControl: QS Service version name: 2.1.91
08-10 13:33:41.543  7644  7644 D UEI.SmartControl: QS Service version code: 201091
08-10 13:33:41.543  7644  7644 D UEI.SmartControl: Service requested: Control
08-10 13:33:41.544  7644  7735 I UEI.SmartControl: Device manager: loading config....
08-10 13:33:41.544  7644  7735 D UEI.SmartControl: ----------- loading internal config...
,08-10 13:33:41.550  7644  7735 E UEI.SmartControl: Loading SETTINGS...
08-10 13:33:41.554  7644  7735 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-10 13:33:41.554  7644  7644 D UEI.SmartControl: Request IControl service: devices are loaded...
08-10 13:33:41.555  6933  6933 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
,08-10 13:33:41.555  1031  1908 I ActivityManager: Killing 6933:com.lge.qremote/u0a112 (adj 15): empty #17
08-10 13:33:41.557  7644  7662 I UEI.SmartControl: ------ IControl API: 11
08-10 13:33:41.557  7644  7662 I UEI.SmartControl: Registering callback...
08-10 13:33:41.559  7644  7734 I UEI.SmartControl: Notify AllClients services are ready: 0
08-10 13:33:41.559  7644  7734 D UEI.SmartControl: -----service ready thread exits
08-10 13:33:41.567  1031  1031 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-10 13:33:41.567  1031  1031 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-10 13:33:41.613  1031  1091 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-10 13:33:41.618  1031  1091 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-10 13:33:41.623  1031  2016 W libprocessgroup: failed to open /acct/uid_10112/pid_6933/cgroup.procs: No such file or directory
08-10 13:33:41.624  7644  7644 D UEI.SmartControl: Internal service binding...
08-10 13:33:41.629  2514  2514 V GmsNetworkLocationProvi: DISABLE
,08-10 13:33:41.630  2036  2036 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-10 13:33:41.653  7708  7708 D LgDataFeature: LgDataFeature() Constructor: none
08-10 13:33:41.653  7708  7708 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-10 13:33:41.667  1031  1091 D LocationProviderProxy: applying state to connected service
,08-10 13:33:41.672  2514  2514 E GCoreFlp: Bound FusedProviderService with LocationManager
,08-10 13:33:41.778  7708  7751 I Babel   : MmsConfig: mnc/mcc: 0/0
08-10 13:33:41.779  7708  7751 I Babel   : MmsConfig.loadMmsSettings
08-10 13:33:41.786  7708  7751 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-10 13:33:41.786  7708  7751 I Babel   : MmsConfig.loadFromDatabase
,08-10 13:33:41.804  7708  7751 E Babel   : canonicalizeMccMnc: invalid mccmnc 
,08-10 13:33:41.804  7708  7751 I Babel   : MmsConfig.loadFromResources
08-10 13:33:41.808  7708  7751 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-10 13:33:41.809  7708  7751 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,08-10 13:33:41.826  6994  6994 V BluetoothOppNotification: new notify threadi!
08-10 13:33:41.826  6994  6994 V BluetoothOppNotification: send delay message
08-10 13:33:41.827  6994  7752 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-10 13:33:41.828  7708  7708 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 13:33:41.828  6994  7752 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3d985353 on behalf of 
08-10 13:33:41.829  6994  7752 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-10 13:33:41.830  6994  7752 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,08-10 13:33:41.831  6994  7752 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2870f490 on behalf of 
08-10 13:33:41.832  6994  7752 V BluetoothOppNotification: outbound: succ-0  fail-0
08-10 13:33:41.834  6994  7752 V BluetoothOppNotification: outbound notification was removed.
08-10 13:33:41.834  6994  7752 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-10 13:33:41.835  6994  7752 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@19fc3189 on behalf of 
08-10 13:33:41.836  6994  7752 V BluetoothOppNotification: inbound: succ-0  fail-0
08-10 13:33:41.843  6994  7752 V BluetoothOppNotification: inbound notification was removed.
08-10 13:33:41.843  6994  7752 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,08-10 13:33:41.847  6994  7752 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@6f058e on behalf of 
08-10 13:33:41.853  7708  7749 W AudioCapabilities: Unsupported mime audio/evrc
08-10 13:33:41.855  7708  7749 W AudioCapabilities: Unsupported mime audio/qcelp
,08-10 13:33:41.860  7708  7749 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-10 13:33:41.873  1821  7754 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-10 13:33:41.873  1821  7754 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
,08-10 13:33:41.879  7060  7060 I AppUp4:CustModeStarterReceiver: onReceive
08-10 13:33:41.884  7060  7060 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@866a964
08-10 13:33:41.884  7060  7060 D AppUp4:CustFacade: isCustomizationCompleted : false
08-10 13:33:41.884  7060  7060 D AppUp4:CustFacade: isPhone : true
08-10 13:33:41.885  7060  7060 D AppUp4:CustModeStarterReceiver: begin check event
08-10 13:33:41.885  7060  7060 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
,08-10 13:33:41.889  1821  4777 I Icing   : updateResources: need to parse e{com.google.android.gms}
08-10 13:33:41.892  7708  7749 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
08-10 13:33:41.897  7708  7749 W AudioCapabilities: Unsupported mime audio/qcelp
,08-10 13:33:41.898  7708  7749 W AudioCapabilities: Unsupported mime audio/evrc
08-10 13:33:41.914  7708  7749 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-10 13:33:41.917  7708  7749 W VideoCapabilities: Unsupported mime video/divx
08-10 13:33:41.919  7708  7749 W VideoCapabilities: Unsupported mime video/divx311
08-10 13:33:41.920  7708  7749 W VideoCapabilities: Unsupported mime video/divx4
08-10 13:33:41.925  7708  7749 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-10 13:33:41.937  1031  1046 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7757 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,08-10 13:33:41.941  7708  7749 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
08-10 13:33:41.943  1031  1046 I ActivityManager: Killing 6901:com.lge.sync/1000 (adj 15): empty #17
08-10 13:33:41.946  7708  7749 W AudioCapabilities: Unsupported mime audio/eac3
08-10 13:33:41.947  7708  7749 W AudioCapabilities: Unsupported mime audio/ac3
08-10 13:33:41.948  7708  7749 W AudioCapabilities: Unsupported mime audio/g726
08-10 13:33:41.949  7708  7749 W AudioCapabilities: Unsupported mime audio/wma-voice
08-10 13:33:41.950  7708  7749 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-10 13:33:41.951  7708  7749 W AudioCapabilities: Unsupported mime audio/adpcm
,08-10 13:33:41.952  7708  7749 W VideoCapabilities: Unsupported mime video/theora
08-10 13:33:41.954  7708  7749 W VideoCapabilities: Unsupported mime video/mjpg
08-10 13:33:42.044  1031  1047 W libprocessgroup: failed to open /acct/uid_1000/pid_6901/cgroup.procs: No such file or directory
,08-10 13:33:42.083  7757  7757 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-10 13:33:42.084  7757  7757 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-10 13:33:42.084  7757  7757 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-10 13:33:42.086  7757  7757 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-10 13:33:42.086  7757  7757 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-10 13:33:42.172  7757  7757 I SystemConfig: BUILD Country: EU
08-10 13:33:42.172  7757  7757 I SystemConfig: BUILD Operator: OPEN
,08-10 13:33:42.218  1031  2016 I ActivityManager: Killing 7382:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
,08-10 13:33:42.314  1031  1772 W libprocessgroup: failed to open /acct/uid_10005/pid_7382/cgroup.procs: No such file or directory
,08-10 13:33:42.322  7757  7775 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
,08-10 13:33:42.326  7757  7775 I SystemConfig: existFile = false
08-10 13:33:42.326  7757  7775 I SystemConfig: canReadFile = false
08-10 13:33:42.326  7757  7775 I SystemConfig: systemFeature RCS result false
08-10 13:33:42.327  7757  7775 D SystemConfig: refreshRcsSupport() :false
08-10 13:33:42.399  1031  2016 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7780 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-10 13:33:42.482  7780  7780 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-10 13:33:42.483  7780  7780 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-10 13:33:42.483  7780  7780 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,08-10 13:33:42.484  7780  7780 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-10 13:33:42.589  7780  7780 I AppConfig: Total System Memory = 2995761152
,08-10 13:33:42.601  7780  7780 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
08-10 13:33:42.729  1031  1047 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7802 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-10 13:33:42.735  1031  1047 I ActivityManager: Killing 7089:com.lge.email/u0a23 (adj 15): empty #17
08-10 13:33:42.741  1031  1092 W ProcessCpuTracker: Skipping unknown process pid 7718
08-10 13:33:42.743  1031  1092 W ProcessCpuTracker: Skipping unknown process pid 7721
08-10 13:33:42.803  1031  2373 W libprocessgroup: failed to open /acct/uid_10023/pid_7089/cgroup.procs: No such file or directory
,08-10 13:33:43.005  7802  7802 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-10 13:33:43.117  7802  7802 D LgDataFeature: LgDataFeature() Constructor: none
08-10 13:33:43.118  7802  7802 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-10 13:33:43.170  7802  7802 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-10 13:33:43.192  7802  7802 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-10 13:33:43.192  7802  7802 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-10 13:33:43.208  7802  7802 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-10 13:33:43.208  7802  7802 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-10 13:33:43.240  1031  1962 I ActivityManager: Killing 6971:com.lge.formmanager/u0a26 (adj 15): empty #17
,08-10 13:33:43.324  1031  1944 W libprocessgroup: failed to open /acct/uid_10026/pid_6971/cgroup.procs: No such file or directory
,08-10 13:33:43.330  3538  6629 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,08-10 13:33:43.339  3538  6629 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@1187c592 on behalf of 7802
08-10 13:33:43.352  4638  7839 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,08-10 13:33:43.356  7802  7802 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
08-10 13:33:43.394  1031  1578 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7841 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-10 13:33:43.442  7802  7802 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-10 13:33:43.484  7841  7841 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-10 13:33:43.511  7841  7841 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-10 13:33:43.511  7841  7841 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-10 13:33:43.511  7841  7841 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-10 13:33:43.511  7841  7841 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-10 13:33:43.511  7841  7841 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-10 13:33:43.511  7841  7841 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,08-10 13:33:43.537  1031  1773 I ActivityManager: Killing 6357:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,08-10 13:33:43.616  1031  2373 W libprocessgroup: failed to open /acct/uid_1000/pid_6357/cgroup.procs: No such file or directory
,08-10 13:33:43.775  1031  1772 V SIM_STK : Menu title from STK is T-Mobile
,08-10 13:33:43.800  4638  7839 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 448 ms] updated apps [took 448 ms] 
,08-10 13:33:44.549  1031  1773 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 13:33:44.549  1031  1773 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@88d1254 mBinding = false
,08-10 13:33:44.570  1031  1031 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-10 13:33:44.571  1031  1031 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-10 13:33:44.571  1031  1031 D Ulp_jni : JNI:system_update. Event-4
,08-10 13:33:44.574  1031  1096 D BluetoothManagerService: Message: 2
08-10 13:33:44.575  1031  1096 D BluetoothManagerService: Sending off request.
08-10 13:33:44.575  6994  7012 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-10 13:33:44.576  6994  7544 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-10 13:33:44.576  6994  7544 D BluetoothAdapterProperties: Setting state to 13
08-10 13:33:44.576  6994  7544 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-10 13:33:44.577  6994  7544 D BluetoothAdapterProperties: onBluetoothDisable()
08-10 13:33:44.577  6994  7544 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-10 13:33:44.579  6994  7548 D BluetoothAdapterProperties: Scan Mode:20
08-10 13:33:44.580  6994  7544 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-10 13:33:44.581  6994  7544 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-10 13:33:44.582  6994  7683 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-10 13:33:44.582  6994  7683 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-10 13:33:44.582  6994  7683 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-10 13:33:44.582  6994  7683 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-10 13:33:44.582  6994  7683 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-10 13:33:44.582  6994  7683 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-10 13:33:44.582  6994  7683 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-10 13:33:44.582  6994  7683 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-10 13:33:44.584  6994  7684 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-10 13:33:44.587  6994  7695 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-10 13:33:44.587  6994  7696 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-10 13:33:44.588  6994  7602 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-10 13:33:44.588  6994  7602 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-10 13:33:44.589  6994  7602 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-10 13:33:44.589  6994  7602 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-10 13:33:44.589  6994  7602 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-10 13:33:44.589  6994  7602 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-10 13:33:44.589  6994  7602 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-10 13:33:44.589  6994  7602 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-10 13:33:44.589  6994  7602 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-10 13:33:44.589  6994  7602 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-10 13:33:44.589  6994  7602 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-10 13:33:44.590  6994  7602 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-10 13:33:44.590  6994  7602 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-10 13:33:44.590  6994  7602 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-10 13:33:44.590  6994  7698 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-10 13:33:44.596  1031  1545 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
,08-10 13:33:44.608  6729  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 13:33:44.608  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 13:33:44.608  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 13:33:44.608  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 13:33:44.608  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 13:33:44.608  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 13:33:44.608  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 13:33:44.608  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 13:33:44.608  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 13:33:44.611  6729  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 13:33:44.611  6729  6729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-10 13:33:44.616  6729  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 13:33:44.616  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 13:33:44.616  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 13:33:44.616  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 13:33:44.616  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 13:33:44.616  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 13:33:44.616  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 13:33:44.616  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 13:33:44.616  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 13:33:44.616  6729  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 13:33:44.616  6729  6729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 13:33:44.619  6729  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 13:33:44.619  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 13:33:44.619  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 13:33:44.619  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 13:33:44.619  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 13:33:44.619  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 13:33:44.619  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 13:33:44.619  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 13:33:44.619  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 13:33:44.620  6729  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 13:33:44.620  6729  6729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 13:33:44.624  1031  1096 D BluetoothManagerService: Message: 60
08-10 13:33:44.624  1031  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-10 13:33:44.624  1031  1096 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
,08-10 13:33:44.634  1945  1945 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-10 13:33:44.638  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-10 13:33:44.647  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 13:33:44.651  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 13:33:44.656  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 13:33:44.661  6876  6876 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
,08-10 13:33:44.671  6994  6994 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-10 13:33:44.671  6994  6994 D BluetoothMapService: STATE_TURNING_OFF
08-10 13:33:44.672  6994  6994 V BluetoothMapService: Handler(): got msg=4
08-10 13:33:44.672  6994  6994 D BluetoothMapService: MAP Service closeService in
08-10 13:33:44.672  6994  6994 D BluetoothMapMasInstance: MAP Service shutdown
08-10 13:33:44.673  6994  6994 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-10 13:33:44.673  6994  6994 V BluetoothMapService: MAP Service closeService out
08-10 13:33:44.673  6994  6994 V BtOppService: Receiver DISABLED_ACTION 
08-10 13:33:44.674  6994  6994 I BtOppRfcommListener: stopping Accept Thread
08-10 13:33:44.674  6994  6994 V BtOppRfcommListener: close mBtServerSocket
08-10 13:33:44.674  6994  7695 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-10 13:33:44.675  6994  6994 V BtOppRfcommListener: waiting for thread to terminate
08-10 13:33:44.675  6994  6994 V BtOppRfcommListener: done waiting for thread to terminate
08-10 13:33:44.678  6994  6994 V BtOppService: onDestroy
,08-10 13:33:44.679  6876  6876 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-10 13:33:44.683  6994  6994 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-10 13:33:44.687  6994  6994 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-10 13:33:44.688  6994  6994 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-10 13:33:44.688  6994  6994 V BluetoothPbapReceiver: ***********state = 13
08-10 13:33:44.691  6994  6994 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
,08-10 13:33:44.694  6994  6994 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-10 13:33:44.694  6994  6994 V BluetoothPbapService: state: 13
08-10 13:33:44.694  6994  6994 V BluetoothPbapService: Pbap Service closeService in
08-10 13:33:44.694  2193  2193 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-10 13:33:44.696  6994  6994 V BluetoothPbapService: successfully stopped pbap service
08-10 13:33:44.696  6994  6994 V BluetoothPbapService: Pbap Service closeService out
,08-10 13:33:44.696  6994  6994 V BluetoothPbapService: Pbap Service onDestroy
08-10 13:33:44.696  6994  6994 V BluetoothPbapService: Pbap Service closeService in
08-10 13:33:44.696  6994  6994 V BluetoothPbapService: Pbap Service closeService out
08-10 13:33:44.696  6994  6994 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-10 13:33:44.700  6876  6876 D DockEventReceiver: finishStartingService: stopping service
08-10 13:33:44.701  6876  6876 D BluetoothPbap: Proxy object disconnected
08-10 13:33:44.701  6876  6876 D PbapServerProfile: Bluetooth service disconnected
08-10 13:33:44.709  6876  6876 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-10 13:33:44.715  6876  6876 D BluetoothPermissionRequest: onReceive
08-10 13:33:44.715  6876  6876 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-10 13:33:44.719  6876  6876 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-10 13:33:44.722  6994  6994 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
,08-10 13:33:44.722  6994  6994 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-10 13:33:44.723  6994  6994 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-10 13:33:44.727  6994  6994 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-10 13:33:44.727  6994  6994 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-10 13:33:44.728  6994  6994 V BluetoothFtpService: Ftp Service onStartCommand
08-10 13:33:44.728  6994  6994 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-10 13:33:44.729  6994  6994 V BluetoothFtpService: Ftp Service closeService
08-10 13:33:44.729  6994  6994 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-10 13:33:44.729  6994  6994 V BluetoothFtpService: successfully stopped ftp service
08-10 13:33:44.730  6994  6994 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-10 13:33:44.730  6994  6994 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-10 13:33:44.730  6994  6994 V BluetoothSapReceiver: SapReceiver onReceive 
08-10 13:33:44.730  6994  6994 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-10 13:33:44.730  6994  6994 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-10 13:33:44.730  6994  6994 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-10 13:33:44.731  6994  6994 V BluetoothFtpService: Ftp Service onDestroy
08-10 13:33:44.731  6994  6994 V BluetoothFtpService: Ftp Service closeService
08-10 13:33:44.734  6994  6994 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-10 13:33:44.734  6994  6994 V BluetoothSapService: state: 13
08-10 13:33:44.734  6994  6994 V BluetoothSapService: Stopping SAP server process
,08-10 13:33:44.738  6994  6994 V BluetoothSapService: Sap Service closeSapService in
08-10 13:33:44.738  6994  6994 V BluetoothSapService: Close listen Socket : 
08-10 13:33:44.739  6994  6994 V BluetoothSapService: Close rfcomm Socket : 
08-10 13:33:44.739  6994  6994 V BluetoothSapService: Close sapd  Socket : 
08-10 13:33:44.739  6994  6994 V BluetoothSapService: Sap Service closeSapService out
08-10 13:33:44.740  6994  6994 V BluetoothSapService: Sap Service onDestroy
08-10 13:33:44.740  6994  6994 V BluetoothSapService: Sap Service closeSapService in
08-10 13:33:44.740  6994  6994 V BluetoothSapService: Close listen Socket : 
08-10 13:33:44.740  6994  6994 V BluetoothSapService: Close rfcomm Socket : 
08-10 13:33:44.740  6994  6994 V BluetoothSapService: Close sapd  Socket : 
08-10 13:33:44.740  6994  6994 V BluetoothSapService: Sap Service closeSapService out
08-10 13:33:45.506  1031  1377 V AlarmManager: ELAPSED_WAKEUP set : Alarm{33e722f2 type 2 when 372703 com.google.android.gms} when 372703
,08-10 13:33:45.542   306  7902 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-10 13:33:45.547  6994  7548 D bt_hci_bdroid: cleanup
08-10 13:33:45.547  6994  7604 I bt_lpm  : LPM is already off!!!
08-10 13:33:45.547  6994  7643 I bt_userial_mct: exiting userial_read_thread
08-10 13:33:45.547  6994  7643 D bt_userial_mct: Leaving userial_evt_read_thread()
08-10 13:33:45.549  1031  1094 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-10 13:33:45.549  6994  7602 W bt-btif : ag scb idx 1 not allocated
08-10 13:33:45.549  6994  7602 E bt-btif : BTA AG is already disabled, ignoring ...
08-10 13:33:45.549  6994  7602 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-10 13:33:45.549  6994  7602 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-10 13:33:45.549  6994  7602 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-10 13:33:45.549  6994  7602 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-10 13:33:45.549  6994  7602 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-10 13:33:45.549  6994  7602 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-10 13:33:45.549  6994  7602 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-10 13:33:45.550  6994  7602 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-10 13:33:45.550  6994  7602 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-10 13:33:45.550  6994  7602 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-10 13:33:45.550  6994  7602 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-10 13:33:45.550  6994  7602 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-10 13:33:45.550  6994  7602 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-10 13:33:45.550  6994  7602 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-10 13:33:45.550  6994  7602 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-10 13:33:45.550  6994  7602 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-10 13:33:45.550  6994  7602 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-10 13:33:45.550  6994  7602 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-10 13:33:45.550  6994  7602 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-10 13:33:45.551  6994  7548 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-10 13:33:45.551  6994  7604 I bt_vendor: hw_epilog_process
08-10 13:33:45.551  6994  7548 D bt_hci_bdroid: cleanup Finalizing cleanup
08-10 13:33:45.551  6994  7548 D bt_userial_mct: userial_close
08-10 13:33:45.551  6994  7548 E bt_userial_mct: pthread_join() FAILED result:3
08-10 13:33:45.551  6994  7548 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-10 13:33:45.575  1031  2016 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7904 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-10 13:33:45.622  6994  7548 D bt_hci_bdroid: set_power 0
08-10 13:33:45.622  6994  7548 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-10 13:33:45.622  6994  7548 I bt_vendor: bluetooth satus is on
08-10 13:33:45.622  6994  7548 I bt_vendor: bt-vendor : resetting BT status
08-10 13:33:45.622  6994  7548 I bt_vendor: Starting hciattach daemon
08-10 13:33:45.622  6994  7548 I bt_vendor: try to set false
,08-10 13:33:45.625  6994  7548 I bt_vendor: Starting hciattach daemon
08-10 13:33:45.625  6994  7548 I bt_vendor: try to set false
08-10 13:33:45.626  6994  7548 I bt_vendor: cleanup
08-10 13:33:45.627  6994  7602 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-10 13:33:45.627  6994  7548 I GKI_LINUX: GKI_exit_task 0 done
08-10 13:33:45.627  6994  7548 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-10 13:33:45.628  6994  7544 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-10 13:33:45.632  6994  6994 D HeadsetService: Received stop request...Stopping profile...
08-10 13:33:45.634  6994  6994 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
,08-10 13:33:45.637  6994  7584 D HeadsetStateMachine: Exit Disconnected: -1
08-10 13:33:45.638  6994  6994 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-10 13:33:45.638  6994  6994 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@125b882
08-10 13:33:45.640  6994  7544 D BluetoothAdapterState: Stopping profile services that were post enabled
08-10 13:33:45.642  1856  1856 D BluetoothHeadset: Proxy object disconnected
08-10 13:33:45.642  1856  1856 D BluetoothHeadset: Proxy object disconnected
08-10 13:33:45.643  1031  1031 D BluetoothHeadset: Proxy object disconnected
08-10 13:33:45.643  1031  1031 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-10 13:33:45.644  6994  6994 D A2dpService: Received stop request...Stopping profile...
08-10 13:33:45.644  1856  1856 D BluetoothHeadset: Proxy object disconnected
08-10 13:33:45.644  6994  7591 D A2dpStateMachine: Exit Disconnected: -1
08-10 13:33:45.645  6994  6994 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-10 13:33:45.647  6994  6994 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-10 13:33:45.647  6994  6994 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-10 13:33:45.647  6994  6994 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@125b882
,08-10 13:33:45.654  1031  1031 D BluetoothA2dp: Proxy object disconnected
08-10 13:33:45.654  1031  1031 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-10 13:33:45.656  6994  6994 D HidService: Received stop request...Stopping profile...
08-10 13:33:45.656  6994  6994 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@125b882
08-10 13:33:45.663  6994  6994 D HealthService: Received stop request...Stopping profile...
08-10 13:33:45.663  6994  6994 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@125b882
,08-10 13:33:45.668  6994  7586 W art     : No such thread id for suspend: 16
08-10 13:33:45.668  6994  7591 W art     : No such thread id for suspend: 16
08-10 13:33:45.670  6876  6876 D BluetoothHeadset: Proxy object disconnected
,08-10 13:33:45.670  6876  6876 D HeadsetProfile: Bluetooth service disconnected
08-10 13:33:45.671  6876  6876 D BluetoothA2dp: Proxy object disconnected
08-10 13:33:45.671  6876  6876 D A2dpProfile: Bluetooth service disconnected
08-10 13:33:45.672  6876  6876 D BluetoothInputDevice: Proxy object disconnected
08-10 13:33:45.672  6876  6876 D HidProfile: Bluetooth service disconnected
08-10 13:33:45.672  6994  6994 D PanService: Received stop request...Stopping profile...
08-10 13:33:45.673  6994  6994 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@125b882
08-10 13:33:45.674  6994  6994 D BtGatt.DebugUtils: handleDebugAction() action=null
08-10 13:33:45.674  6994  6994 D BtGatt.GattService: Received stop request...Stopping profile...
08-10 13:33:45.675  6994  6994 D BtGatt.GattService: stop()
08-10 13:33:45.675  6994  6994 D BtGatt.AdvertiseManager: advertise clients cleared
08-10 13:33:45.676  6994  6994 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@125b882
08-10 13:33:45.676  6876  6876 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-10 13:33:45.676  6876  6876 D PanProfile: Bluetooth service disconnected
08-10 13:33:45.677  6994  6994 D BluetoothMapService: Received stop request...Stopping profile...
08-10 13:33:45.677  6994  6994 D BluetoothMapService: stop()
,08-10 13:33:45.682  6994  6994 D BluetoothMapEmailAppObserver: deinitObservers()
08-10 13:33:45.683  6994  6994 D BluetoothMapEmailAppObserver: removeReceiver()
08-10 13:33:45.683  6994  6994 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@125b882
08-10 13:33:45.686  6994  6994 D HeadsetStateMachine: Unbinding service...
08-10 13:33:45.687  6994  6994 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-10 13:33:45.687  6876  6876 D BluetoothMap: Proxy object disconnected
08-10 13:33:45.687  6876  6876 D MapProfile: Bluetooth service disconnected
08-10 13:33:45.687  6994  6994 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-10 13:33:45.687  6994  6994 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-10 13:33:45.687  6994  6994 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-10 13:33:45.687  6994  6994 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-10 13:33:45.687  6994  6994 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-10 13:33:45.687  6994  6994 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-10 13:33:45.688  6994  6994 I BluetoothA2dpServiceJni: cleanupNative
08-10 13:33:45.692  6994  7592 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,08-10 13:33:45.692  6994  6994 I GKI_LINUX: GKI_exit_task 2 done
08-10 13:33:45.692  6994  6994 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-10 13:33:45.693  6994  6994 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-10 13:33:45.693  6994  6994 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-10 13:33:45.693  6994  6994 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-10 13:33:45.694  6994  6994 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-10 13:33:45.694  6994  6994 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-10 13:33:45.694  6994  6994 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-10 13:33:45.694  6994  6994 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-10 13:33:45.695  6994  6994 V BluetoothMapService: Handler(): got msg=4
08-10 13:33:45.695  6994  6994 D BluetoothMapService: MAP Service closeService in
08-10 13:33:45.695  6994  6994 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-10 13:33:45.695  6994  6994 V BluetoothMapService: MAP Service closeService out
08-10 13:33:45.695  6994  7544 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-10 13:33:45.695  6994  7544 D BluetoothAdapterProperties: Setting state to 10
08-10 13:33:45.695  6994  6994 D BluetoothMapService: cleanup()
08-10 13:33:45.695  6994  7544 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-10 13:33:45.695  6994  6994 D BluetoothMapService: MAP Service closeService in
08-10 13:33:45.695  6994  6994 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-10 13:33:45.695  6994  6994 V BluetoothMapService: MAP Service closeService out
08-10 13:33:45.696  1031  1096 D BluetoothManagerService: Message: 60
08-10 13:33:45.696  1031  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-10 13:33:45.696  1031  1096 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-10 13:33:45.696  6994  7544 I BluetoothAdapterState: Entering OffState
08-10 13:33:45.696  6876  6892 D BluetoothA2dp: onBluetoothStateChange: up=false
08-10 13:33:45.697  6876  7305 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 13:33:45.697  1856  1872 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 13:33:45.698  1031  1096 D BluetoothA2dp: onBluetoothStateChange: up=false
08-10 13:33:45.698  6876  6893 D BluetoothPbap: onBluetoothStateChange: up=false
08-10 13:33:45.699  1856  4020 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 13:33:45.699  6876  6892 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-10 13:33:45.700  1856  4019 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 13:33:45.700  1031  1096 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 13:33:45.700  6876  7305 D BluetoothMap: onBluetoothStateChange: up=false
08-10 13:33:45.701  6876  6893 D BluetoothPan: onBluetoothStateChange on: false
08-10 13:33:45.702  1031  1096 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-10 13:33:45.702  1031  1096 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-10 13:33:45.704  1031  1096 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-10 13:33:45.704  1031  1096 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-10 13:33:45.704  1031  1096 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@88d1254 mBinding = false
,08-10 13:33:45.704  1031  1096 D BluetoothManagerService: Sending unbind request.
08-10 13:33:45.704  7904  7904 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-10 13:33:45.705  1031  1096 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-10 13:33:45.709  1945  1945 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-10 13:33:45.710  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-10 13:33:45.712  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 13:33:45.712  1945  2120 D LGBluetoothAPIService: Message: 2
08-10 13:33:45.712  1945  2120 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@398f1323 mBinding = false
08-10 13:33:45.712  1945  2120 D LGBluetoothAPIService: Sending unbind request.
08-10 13:33:45.712  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 13:33:45.713  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 13:33:45.713  6876  6876 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-10 13:33:45.713  6876  6876 D LGBluetoothEventManager: [BTUI] clear device connection state
08-10 13:33:45.716  6876  6876 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-10 13:33:45.717  6994  7548 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-10 13:33:45.717  6994  6994 I GKI_LINUX: GKI_exit_task 1 done
08-10 13:33:45.717  6994  6994 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-10 13:33:45.717  6994  6994 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-10 13:33:45.717  6994  6994 I art     : --- WEIRD: removing null entry 248
08-10 13:33:45.717  6994  6994 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-10 13:33:45.717  6994  6994 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-10 13:33:45.719  1605  1605 D BluetoothAdapter: 371047941: getState() :  mService = null. Returning STATE_OFF
08-10 13:33:45.719  1605  1605 D BluetoothAdapter: 371047941: getState() :  mService = null. Returning STATE_OFF
08-10 13:33:45.720  6994  6994 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-10 13:33:45.723  6994  6994 I art     : System.exit called, status: 0
08-10 13:33:45.723  6994  6994 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-10 13:33:45.726  6876  6876 D DockEventReceiver: finishStartingService: stopping service
,08-10 13:33:45.740   310  2198 V AudioFlinger: 6994 died, releasing its sessions
,08-10 13:33:45.741   310  2198 V AudioFlinger:  pid 1856 @ 0
08-10 13:33:45.741  6876  6876 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-10 13:33:45.741   310  2198 V AudioFlinger:  pid 3485 @ 1
08-10 13:33:45.741   310  2198 V AudioFlinger:  pid 3485 @ 2
08-10 13:33:45.812  1031  1773 I ActivityManager: Process com.android.bluetooth (pid 6994) has died
08-10 13:33:45.813  1031  1773 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms
,08-10 13:33:45.827  2193  2193 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-10 13:33:45.827  7904  7904 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-10 13:33:45.860  6876  6876 D BluetoothPermissionRequest: onReceive
,08-10 13:33:45.871  6876  6876 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-10 13:33:45.871  6876  6876 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-10 13:33:45.875  6876  6876 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-10 13:33:45.913  7904  7904 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-10 13:33:45.914  7904  7904 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-10 13:33:45.914  7904  7904 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-10 13:33:45.915  7904  7904 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-10 13:33:45.915  7904  7904 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
,08-10 13:33:45.917  7904  7904 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-10 13:33:45.923  7904  7904 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-10 13:33:45.935  1031  1046 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7941 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
08-10 13:33:45.947  7904  7904 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
08-10 13:33:45.948  7904  7904 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:9070
,08-10 13:33:45.958  7904  7904 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-10 13:33:45.959   341   341 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 466us total 23.607ms
08-10 13:33:45.969  7904  7904 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
,08-10 13:33:45.970  7904  7904 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-10 13:33:45.974  7904  7904 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-10 13:33:45.975  7904  7904 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-10 13:33:45.979   341   341 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 448us total 19.473ms
08-10 13:33:45.987  7941  7941 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-10 13:33:45.988  7941  7941 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-10 13:33:45.988  7941  7941 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-10 13:33:45.989  7941  7941 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-10 13:33:45.999   341   341 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 405us total 19.154ms
08-10 13:33:46.000  7941  7941 D BluetoothAdapterApp: Loading JNI Library
08-10 13:33:46.014  7904  7904 D LgDataFeature: LgDataFeature() Constructor: none
,08-10 13:33:46.015  7904  7904 D LgDataFeature: LgDataFeature() Constructor Done, null
08-10 13:33:46.020  7941  7941 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@3d3d8e2a Instance Count = 1
08-10 13:33:46.021  7904  7904 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-10 13:33:46.021  7904  7904 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-10 13:33:46.021  7904  7904 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-10 13:33:46.021  7904  7904 V SoundPool: doLoad: loading sample sampleID=1
08-10 13:33:46.023  7904  7961 V SoundPool: Start decode
08-10 13:33:46.024  7904  7961 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-10 13:33:46.025  7904  7904 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-10 13:33:46.027  7941  7941 D BluetoothAdapterApp: onCreate
08-10 13:33:46.027  7904  7904 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-10 13:33:46.027   310  2199 V MediaPlayerService: decode(23, 10857164, 17813)
08-10 13:33:46.027   310  2199 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-10 13:33:46.027   310  2199 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-10 13:33:46.027   310  2199 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-10 13:33:46.027   310  2199 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-10 13:33:46.027   310  2199 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-10 13:33:46.027   310  2199 V MediaPlayerService: player type = 3
08-10 13:33:46.028   310  2199 V AwesomePlayer: AwesomePlayer create()
08-10 13:33:46.029   310  2199 V AwesomePlayer: reset_l() 
08-10 13:33:46.029   310  2199 V AwesomePlayer: cancelPlayerEvents
08-10 13:33:46.029   310  2199 V AwesomePlayer: setAudioSink() 
08-10 13:33:46.029   310  2199 V AwesomePlayer: reset_l() 
08-10 13:33:46.029   310  2199 V AudioCache: notify(0xb1432400, 8, 0, 0)
08-10 13:33:46.030   310  2199 V AudioCache: ignored
08-10 13:33:46.030   310  2199 V AwesomePlayer: cancelPlayerEvents
08-10 13:33:46.030   310  2199 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-10 13:33:46.030   310  2199 V AwesomePlayer: setDataSource_l dataSource
08-10 13:33:46.030   310  2199 V LGParserOSAL: SniffLGParser start
08-10 13:33:46.030   310  2199 V LGParserOSAL: MainType:5, SubType=0
08-10 13:33:46.030   310  2199 V LGParserOSAL: #### check Mime : application/ogg
08-10 13:33:46.030   310  2199 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-10 13:33:46.030   310  2199 E MediaExtractor: Use LGExtractor :application/ogg 
08-10 13:33:46.032  7904  7904 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-10 13:33:46.033  7904  7904 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,08-10 13:33:46.045  7941  7941 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-10 13:33:46.046  7941  7941 D ProfileConfigQcom: Adding HeadsetService
08-10 13:33:46.047  7941  7941 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-10 13:33:46.047  7941  7941 D ProfileConfigQcom: Adding A2dpService
08-10 13:33:46.048  7941  7941 D ProfileConfigQcom: [BTUI] HidService is supported
08-10 13:33:46.049  7941  7941 D ProfileConfigQcom: Adding HidService
08-10 13:33:46.049  7941  7941 D ProfileConfigQcom: [BTUI] HealthService is supported
,08-10 13:33:46.050  7941  7941 D ProfileConfigQcom: Adding HealthService
08-10 13:33:46.051  7941  7941 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-10 13:33:46.052  7904  7904 V LGMDMManager: Create singleton instance
08-10 13:33:46.053  7941  7941 D ProfileConfigQcom: [BTUI] PanService is supported
08-10 13:33:46.053  7941  7941 D ProfileConfigQcom: Adding PanService
08-10 13:33:46.054  7941  7941 D ProfileConfigQcom: [BTUI] GattService is supported
08-10 13:33:46.055  7941  7941 D ProfileConfigQcom: Adding GattService
08-10 13:33:46.055  7941  7941 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-10 13:33:46.056  7941  7941 D ProfileConfigQcom: Adding BluetoothMapService
08-10 13:33:46.057  7941  7941 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-10 13:33:46.061  7941  7941 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,08-10 13:33:46.064   310  2199 V LGParserOSAL: supported mime: application/ogg
08-10 13:33:46.064   310  2199 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-10 13:33:46.064   310  2199 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-10 13:33:46.064   310  2199 V AwesomePlayer: mBitrate = -1 bits/sec
08-10 13:33:46.064   310  2199 V AwesomePlayer: AudioTrack Setting
08-10 13:33:46.064   310  2199 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-10 13:33:46.064   310  2199 V AwesomePlayer: setAudioSource() 
08-10 13:33:46.064   310  2199 V MediaPlayerService: prepare
08-10 13:33:46.064   310  2199 V AwesomePlayer: prepareAsync_l() 
08-10 13:33:46.064   310  2199 V MediaPlayerService: wait for prepare
08-10 13:33:46.064   310  7963 V AwesomePlayer: onPrepareAsyncEvent() 
08-10 13:33:46.064   310  7963 V AwesomePlayer: initAudioDecoder() 
08-10 13:33:46.064   310  7963 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-10 13:33:46.064   310  7963 V AudioSystem: isOffloadSupported()
08-10 13:33:46.064   310  7963 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-10 13:33:46.064   310  7963 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-10 13:33:46.064   310  7963 I AudioFlinger: isAudioPlaybackHookOn() false
08-10 13:33:46.064   310  7963 V AwesomePlayer: getUseOffload() = 0 
08-10 13:33:46.064   310  7963 V OMXCodec: OMXCodec::Create
08-10 13:33:46.064   310  7963 V OMXCodec: findMatchingCodecs()
08-10 13:33:46.064   310  7963 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-10 13:33:46.065   310  7963 V OMXCodec: matchingCodecs.size()=1
08-10 13:33:46.065   310  7963 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-10 13:33:46.066   310  7963 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-10 13:33:46.066   310  7963 V LGCodecAdapter: LG Codec Adapter start
08-10 13:33:46.066   310  7963 V OMXCodec: OMXCodec Createtor
08-10 13:33:46.066   310  7963 V OMXCodec: setComponentRole
08-10 13:33:46.066   310  7963 V OMXCodec: configureCodec protected=0
,08-10 13:33:46.066   310  7963 V LGCodecAdapter: called getLGCodecSpecificData
08-10 13:33:46.066   310  7963 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-10 13:33:46.066   310  7963 V LGCodecOSAL: Called LGconfigureCodecMETA
08-10 13:33:46.066   310  7963 V LGCodecOSAL: Called LGconfigureCodecMSG
08-10 13:33:46.066   310  7963 V LGCodecOSAL: Not support LGCodec
08-10 13:33:46.066   310  7963 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-10 13:33:46.066   310  7963 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-10 13:33:46.066   310  7963 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-10 13:33:46.066   310  7963 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-10 13:33:46.066   310  7963 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-10 13:33:46.066   310  7963 V AudioSystem: isOffloadSupported()
08-10 13:33:46.066   310  7963 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-10 13:33:46.066   310  7963 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-10 13:33:46.066   310  7963 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-10 13:33:46.066   310  7963 V OMXCodec: init()
08-10 13:33:46.066   310  7963 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-10 13:33:46.066   310  7963 V OMXCodec: allocateBuffers
08-10 13:33:46.066   310  7963 V OMXCodec: allocateBuffersOnPort portIndex=0
08-10 13:33:46.066   310  7963 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-10 13:33:46.066   310  7963 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f78d0 on input port
08-10 13:33:46.066   310  7963 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7920 on input port
08-10 13:33:46.066   310  7963 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on input port
08-10 13:33:46.066   310  7963 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on input port
08-10 13:33:46.066   310  7963 V OMXCodec: allocateBuffersOnPort portIndex=1
08-10 13:33:46.066   310  7963 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-10 13:33:46.066   310  7963 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on output port
08-10 13:33:46.066   310  7963 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on output port
08-10 13:33:46.066   310  7963 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d80 on output port
08-10 13:33:46.066   310  7963 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57bd3d0 on output port
08-10 13:33:46.066   310  7963 V OMXCodec: init() mAsyncCompletion wait!!! 
08-10 13:33:46.067   310  7965 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-10 13:33:46.067   310  7965 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-10 13:33:46.067   310  7965 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-10 13:33:46.068   310  7963 V OMXCodec: init() mAsyncCompletion wait!!! 
08-10 13:33:46.068  6876  6876 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-10 13:33:46.072   310  7965 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-10 13:33:46.072   310  7965 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-10 13:33:46.072   310  7965 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-10 13:33:46.072   310  7963 V OMXCodec: init() mAsyncCompletion wait free! 
08-10 13:33:46.072   310  7963 V AwesomePlayer: finishAsyncPrepare_l() 
08-10 13:33:46.072   310  7963 V AudioCache: notify(,0xb1432400, 5, 0, 0)
08-10 13:33:46.072   310  7963 V AudioCache: ignored
08-10 13:33:46.072   310  7963 V AudioCache: notify(0xb1432400, 1, 0, 0)
08-10 13:33:46.072   310  7963 V AudioCache: prepared
08-10 13:33:46.072   310  2199 V AudioCache: wait - success
08-10 13:33:46.072   310  2199 V MediaPlayerService: start
08-10 13:33:46.072   310  2199 V AwesomePlayer: play_l() 
08-10 13:33:46.072   310  2199 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-10 13:33:46.072   310  2199 V AwesomePlayer: createAudioPlayer_l
08-10 13:33:46.072   310  2199 V AwesomePlayer: seekAudioIfNecessary_l() 
08-10 13:33:46.072   310  2199 V AwesomePlayer: startAudioPlayer_l() 
08-10 13:33:46.072   310  2199 D AudioPlayer: start of Playback, useOffload 0
08-10 13:33:46.072   310  2199 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-10 13:33:46.072  7941  7941 V LGMDMManagerInternal: Create singleton instance
08-10 13:33:46.073   310  2199 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-10 13:33:46.076   310  7965 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-10 13:33:46.076   310  7965 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-10 13:33:46.076   310  7965 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
,08-10 13:33:46.076   310  7965 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-10 13:33:46.076   310  7965 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-10 13:33:46.076   310  7965 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-10 13:33:46.076   310  7965 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884768
08-10 13:33:46.076   310  7965 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-10 13:33:46.076   310  7965 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885328
08-10 13:33:46.076   310  7965 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-10 13:33:46.077   310  7965 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885568
08-10 13:33:46.077   310  7965 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-10 13:33:46.077   310  7965 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044791248
,08-10 13:33:46.077   310  7965 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-10 13:33:46.077   310  7965 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-10 13:33:46.077   310  7965 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-10 13:33:46.077   310  7965 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-10 13:33:46.077   310  7965 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-10 13:33:46.077   310  7965 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-10 13:33:46.077   310  7965 V OMXCodec: allocateBuffersOnPort portIndex=1
08-10 13:33:46.077   310  7965 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-10 13:33:46.077   310  7965 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d80 on output port
,08-10 13:33:46.077   310  7965 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on output port
08-10 13:33:46.077   310  7965 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on output port
08-10 13:33:46.077   310  7965 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57bd650 on output port
,08-10 13:33:46.082   310  7965 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
,08-10 13:33:46.082   310  7965 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-10 13:33:46.082   310  2199 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-10 13:33:46.084   310  2199 V AudioCache: notify(0xb1432400, 6, 0, 0)
08-10 13:33:46.084   310  2199 V AudioCache: ignored
08-10 13:33:46.084   310  2199 V MediaPlayerService: wait for playback complete
08-10 13:33:46.084   310  7966 V AudioCache: write(0xb17fd000, 4096)
08-10 13:33:46.084   310  7966 V AudioCache: memcpy(0xac300000, 0xb17fd000, 4096)
08-10 13:33:46.085   310  7966 V AudioCache: write(0xb17fd000, 4096)
08-10 13:33:46.085   310  7966 V AudioCache: memcpy(0xac301000, 0xb17fd000, 4096)
08-10 13:33:46.086   310  7966 V AudioCache: write(0xb17fd000, 4096)
08-10 13:33:46.086   310  7966 V AudioCache: memcpy(0xac302000, 0xb17fd000, 4096)
08-10 13:33:46.086   310  7966 V AudioCache: write(0xb17fd000, 4096)
08-10 13:33:46.086   310  7966 V AudioCache: memcpy(0xac303000, 0xb17fd000, 4096)
08-10 13:33:46.087   310  7966 V AudioCache: write(0xb17fd000, 4096)
08-10 13:33:46.087   310  7966 V AudioCache: memcpy(0xac304000, 0xb17fd000, 4096)
08-10 13:33:46.087   310  7966 V AudioCache: write(0xb17fd000, 4096)
08-10 13:33:46.087   310  7966 V AudioCache: memcpy(0xac305000, 0xb17fd000, 4096)
,08-10 13:33:46.088   310  7966 V AudioCache: write(0xb17fd000, 4096)
08-10 13:33:46.088   310  7966 V AudioCache: memcpy(0xac306000, 0xb17fd000, 4096)
08-10 13:33:46.088   310  7966 V AudioCache: write(0xb17fd000, 4096)
08-10 13:33:46.088   310  7966 V AudioCache: memcpy(0xac307000, 0xb17fd000, 4096)
08-10 13:33:46.089   310  7966 V AudioCache: write(0xb17fd000, 4096)
08-10 13:33:46.089   310  7966 V AudioCache: memcpy(0xac308000, 0xb17fd000, 4096)
08-10 13:33:46.089   310  7966 V AudioCache: write(0xb17fd000, 4096)
08-10 13:33:46.089   310  7966 V AudioCache: memcpy(0xac309000, 0xb17fd000, 4096)
08-10 13:33:46.090   310  7966 V AudioCache: write(0xb17fd000, 4096)
08-10 13:33:46.090   310  7966 V AudioCache: memcpy(0xac30a000, 0xb17fd000, 4096)
08-10 13:33:46.090   310  7966 V AudioCache: write(0xb17fd000, 4096)
,08-10 13:33:46.091   310  7966 V AudioCache: memcpy(0xac30b000, 0xb17fd000, 4096)
08-10 13:33:46.091   310  7966 V AudioCache: write(0xb17fd000, 4096)
08-10 13:33:46.091   310  7966 V AudioCache: memcpy(0xac30c000, 0xb17fd000, 4096)
08-10 13:33:46.092   310  7966 V AudioCache: write(0xb17fd000, 4096)
08-10 13:33:46.092   310  7966 V AudioCache: memcpy(0xac30d000, 0xb17fd000, 4096)
08-10 13:33:46.093   310  7966 V AudioCache: write(0xb17fd000, 4096)
08-10 13:33:46.093   310  7966 V AudioCache: memcpy(0xac30e000, 0xb17fd000, 4096)
08-10 13:33:46.093   310  7966 V AudioCache: write(0xb17fd000, 4096)
08-10 13:33:46.093   310  7966 V AudioCache: memcpy(0xac30f000, 0xb17fd000, 4096)
08-10 13:33:46.094   310  7966 V AudioCache: write(0xb17fd000, 4096)
08-10 13:33:46.094   310  7966 V AudioCache: memcpy(0xac310000, 0xb17fd000, 4096)
08-10 13:33:46.094   310  7966 V AudioCache: write(0xb17fd000, 4096)
08-10 13:33:46.094   310  7966 V AudioCache: memcpy(0xac311000, 0xb17fd000, 4096)
08-10 13:33:46.095   310  7966 V AudioCache: write(0xb17fd000, 4096)
08-10 13:33:46.095   310  7966 V AudioCache: memcpy(0xac312000, 0xb17fd000, 4096)
08-10 13:33:46.095   310  7966 V AudioCache: write(0xb17fd000, 4096)
08-10 13:33:46.095   310  7966 V AudioCache: memcpy(0xac313000, 0xb17fd000, 4096)
08-10 13:33:46.096   310  7966 V AudioCache: write(0xb17fd000, 4096)
08-10 13:33:46.096   310  7966 V AudioCache: memcpy(0xac314000, 0xb17fd000, 4096)
08-10 13:33:46.097   310  7966 V AudioCache: write(0xb17fd000, 4096)
08-10 13:33:46.097   310  7966 V AudioCache: memcpy(0xac315000, 0xb17fd000, 4096)
08-10 13:33:46.097   310  7966 V AudioCache: write(0xb17fd000, 4096),
08-10 13:33:46.097   310  7966 V AudioCache: memcpy(0xac316000, 0xb17fd000, 4096)
08-10 13:33:46.098   310  7966 V AudioCache: write(0xb17fd000, 4096)
08-10 13:33:46.098   310  7966 V AudioCache: memcpy(0xac317000, 0xb17fd000, 4096)
08-10 13:33:46.099   310  7966 V AudioCache: write(0xb17fd000, 4096)
,08-10 13:33:46.099   310  7966 V AudioCache: memcpy(0xac318000, 0xb17fd000, 4096)
08-10 13:33:46.099   310  7966 V AudioCache: write(0xb17fd000, 4096)
08-10 13:33:46.099   310  7966 V AudioCache: memcpy(0xac319000, 0xb17fd000, 4096)
08-10 13:33:46.100   310  7966 V AudioCache: write(0xb17fd000, 4096)
,08-10 13:33:46.100   310  7966 V AudioCache: memcpy(0xac31a000, 0xb17fd000, 4096)
08-10 13:33:46.102   310  7966 V AudioCache: write(0xb17fd000, 4096)
08-10 13:33:46.102   310  7966 V AudioCache: memcpy(0xac31b000, 0xb17fd000, 4096)
08-10 13:33:46.103   310  7966 V AudioCache: write(0xb17fd000, 4096)
,08-10 13:33:46.103   310  7966 V AudioCache: memcpy(0xac31c000, 0xb17fd000, 4096)
08-10 13:33:46.104   310  7966 V AudioCache: write(0xb17fd000, 4096)
08-10 13:33:46.104   310  7966 V AudioCache: memcpy(0xac31d000, 0xb17fd000, 4096)
08-10 13:33:46.104   310  7966 V AudioCache: write(0xb17fd000, 4096)
,08-10 13:33:46.104   310  7966 V AudioCache: memcpy(0xac31e000, 0xb17fd000, 4096)
,08-10 13:33:46.105   310  7966 V AudioCache: write(0xb17fd000, 4096),
08-10 13:33:46.105   310  7966 V AudioCache: memcpy(0xac31f000, 0xb17fd000, 4096)
08-10 13:33:46.106   310  7966 V AudioCache: write(0xb17fd000, 4096)
08-10 13:33:46.106   310  7966 V AudioCache: memcpy(0xac320000, 0xb17fd000, 4096)
,08-10 13:33:46.106   310  7966 V AudioCache: write(0xb17fd000, 4096)
08-10 13:33:46.106   310  7966 V AudioCache: memcpy(0xac321000, 0xb17fd000, 4096)
08-10 13:33:46.107   310  7966 V AudioCache: write(0xb17fd000, 4096)
08-10 13:33:46.107   310  7966 V AudioCache: memcpy(0xac322000, 0xb17fd000, 4096)
,08-10 13:33:46.107   310  7966 V AudioCache: write(0xb17fd000, 4096)
08-10 13:33:46.107   310  7966 V AudioCache: memcpy(0xac323000, 0xb17fd000, 4096)
08-10 13:33:46.108   310  7966 V AudioCache: write(0xb17fd000, 4096)
08-10 13:33:46.108   310  7966 V AudioCache: memcpy(0xac324000, 0xb17fd000, 4096)
,08-10 13:33:46.108   310  7966 V AudioCache: write(0xb17fd000, 4096)
08-10 13:33:46.108   310  7966 V AudioCache: memcpy(0xac325000, 0xb17fd000, 4096)
08-10 13:33:46.109   310  7966 V AudioCache: write(0xb17fd000, 4096)
08-10 13:33:46.109   310  7966 V AudioCache: memcpy(0xac326000, 0xb17fd000, 4096)
,08-10 13:33:46.109   310  7966 V AudioCache: write(0xb17fd000, 4096)
08-10 13:33:46.109   310  7966 V AudioCache: memcpy(0xac327000, 0xb17fd000, 4096)
08-10 13:33:46.110   310  7966 V AudioCache: write(0xb17fd000, 4096)
08-10 13:33:46.110   310  7966 V AudioCache: memcpy(0xac328000, 0xb17fd000, 4096)
,08-10 13:33:46.110   310  7966 V AudioCache: write(0xb17fd000, 4096)
08-10 13:33:46.110   310  7966 V AudioCache: memcpy(0xac329000, 0xb17fd000, 4096)
08-10 13:33:46.111   310  7966 V AudioCache: write(0xb17fd000, 4096)
08-10 13:33:46.111   310  7966 V AudioCache: memcpy(0xac32a000, 0xb17fd000, 4096)
,08-10 13:33:46.112   310  7966 V AudioCache: write(0xb17fd000, 4096)
08-10 13:33:46.112   310  7966 V AudioCache: memcpy(0xac32b000, 0xb17fd000, 4096)
08-10 13:33:46.112   310  7966 V AudioCache: write(0xb17fd000, 4096)
08-10 13:33:46.112   310  7966 V AudioCache: memcpy(0xac32c000, 0xb17fd000, 4096)
08-10 13:33:46.113   310  7966 V AudioCache: write(0xb17fd000, 4096),
08-10 13:33:46.113   310  7966 V AudioCache: memcpy(0xac32d000, 0xb17fd000, 4096)
08-10 13:33:46.113   310  7966 V AudioCache: write(0xb17fd000, 4096)
08-10 13:33:46.113   310  7966 V AudioCache: memcpy(0xac32e000, 0xb17fd000, 4096)
08-10 13:33:46.114   310  7966 V AudioCache: write(0xb17fd000, 4096)
,08-10 13:33:46.114   310  7966 V AudioCache: memcpy(0xac32f000, 0xb17fd000, 4096)
08-10 13:33:46.114   310  7966 V AudioCache: write(0xb17fd000, 4096)
08-10 13:33:46.114   310  7966 V AudioCache: memcpy(0xac330000, 0xb17fd000, 4096)
08-10 13:33:46.115   310  7966 V AudioCache: write(0xb17fd000, 4096)
08-10 13:33:46.115   310  7966 V AudioCache: memcpy(0xac331000, 0xb17fd000, 4096)
08-10 13:33:46.115   310  7965 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-10 13:33:46.115   310  7966 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-10 13:33:46.115   310  7966 V AwesomePlayer: postAudioEOS() 
08-10 13:33:46.115   310  7966 V AudioCache: write(0xb17fd000, 280),
08-10 13:33:46.115   310  7966 V AudioCache: memcpy(0xac332000, 0xb17fd000, 280)
08-10 13:33:46.122   310  7963 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-10 13:33:46.122   310  7963 V AwesomePlayer: onStreamDone
08-10 13:33:46.122   310  7963 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-10 13:33:46.122   310  7963 V AudioCache: notify(0xb1432400, 2, 0, 0),
08-10 13:33:46.122   310  7963 V AudioCache: playback complete
08-10 13:33:46.122   310  7963 V AwesomePlayer: pause_l() 
08-10 13:33:46.122   310  7963 V AudioCache: notify(0xb1432400, 7, 0, 0)
08-10 13:33:46.122   310  7963 V AudioCache: ignored
,08-10 13:33:46.122   310  7963 V AwesomePlayer: cancelPlayerEvents
08-10 13:33:46.122   310  2199 V AudioCache: wait - success
08-10 13:33:46.122   310  2199 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-10 13:33:46.122   310  7963 D AudioPlayer: Pause Playback at 1068125,
08-10 13:33:46.122   310  2199 V AwesomePlayer: reset_l() 
08-10 13:33:46.122   310  2199 V AudioCache: notify(0xb1432400, 8, 0, 0)
08-10 13:33:46.122   310  2199 V AudioCache: ignored
08-10 13:33:46.122   310  2199 V AwesomePlayer: cancelPlayerEvents
,08-10 13:33:46.122   310  2199 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-10 13:33:46.122   310  2199 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-10 13:33:46.122   310  2199 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-10 13:33:46.122   310  2199 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-10 13:33:46.122   310  2199 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!,
,08-10 13:33:46.132   310  7965 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
,08-10 13:33:46.132   310  7965 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-10 13:33:46.132   310  7965 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-10 13:33:46.132   310  7965 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 0
08-10 13:33:46.132   310  7965 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-10 13:33:46.132   310  7965 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f79c0 on port 0
08-10 13:33:46.132   310  7965 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-10 13:33:46.132   310  7965 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7920 on port 0
08-10 13:33:46.132   310  7965 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-10 13:33:46.132   310  7965 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f78d0 on port 0
08-10 13:33:46.132   310  7965 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-10 13:33:46.132   310  7965 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-10 13:33:46.132   310  7965 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57bd650 on port 1
08-10 13:33:46.132   310  7965 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-10 13:33:46.133   310  7965 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 1
08-10 13:33:46.133   310  7965 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-10 13:33:46.133   310  7965 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c90 on port 1
08-10 13:33:46.133   310  7965 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-10 13:33:46.133   310  7965 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7d80 on port 1
08-10 13:33:46.133   310  7965 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-10 13:33:46.133   310  7965 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-10 13:33:46.133   310  2199 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-10 13:33:46.133   310  2199 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-10 13:33:46.133   310  7965 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-10 13:33:46.133   310  7965 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-10 13:33:46.133   310  7965 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-10 13:33:46.133   310  2199 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-10 13:33:46.133   310  2199 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-10 13:33:46.133   310  2199 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-10 13:33:46.134   310  2199 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-10 13:33:46.134   310  2199 D AudioPlayer: AudioPlayer releasing audio source
08-10 13:33:46.134   310  2199 D AudioPlayer: AudioPlayer done releasing audio source
08-10 13:33:46.134   310  2199 V AwesomePlayer: reset_l() 
08-10 13:33:46.134   310  2199 V AwesomePlayer: cancelPlayerEvents
08-10 13:33:46.134   310  2199 V AwesomePlayer: ~AwesomePlayer call
08-10 13:33:46.134   310  2199 V AwesomePlayer: reset_l() 
08-10 13:33:46.134   310  2199 V AwesomePlayer: cancelPlayerEvents
08-10 13:33:46.135  7904  7961 V SoundPool: close(31)
08-10 13:33:46.135  7904  7961 V SoundPool: pointer = 0x9fe3b000, size = 205080, sampleRate = 48000, numChannels = 2
08-10 13:33:46.140  7904  7904 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-10 13:33:46.141  7904  7904 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-10 13:33:46.144  7904  7904 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:4955
08-10 13:33:46.146  7904  7904 I QRemote : [RemoteCon,trolManager.java:183:onServiceConnected()] oooooo start
,08-10 13:33:46.147  7644  7662 I UEI.SmartControl: ------ IControl API: 11
08-10 13:33:46.147  7644  7662 I UEI.SmartControl: Registering callback...
08-10 13:33:46.148  7644  7663 I UEI.SmartControl: ------ IControl API: 19
08-10 13:33:46.149  7644  7663 I UEI.SmartControl: Registering Services Ready callback...
08-10 13:33:46.149  7644  7663 I UEI.SmartControl: Notify client services are ready...
08-10 13:33:46.150  7904  7920 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-10 13:33:46.150  7904  7959 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-10 13:33:46.151  7904  7959 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-10 13:33:46.151  7904  7904 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-10 13:33:46.151  7941  7941 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-10 13:33:46.151  7904  7904 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-10 13:33:46.152  7644  7662 I UEI.SmartControl: ------ IControl API: 8
08-10 13:33:46.153  7904  7904 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-10 13:33:46.153  7904  7904 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-10 13:33:46.154  7904  7904 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-10 13:33:46.154  7904  7904 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-10 13:33:46.154  7904  7904 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-10 13:33:46.155  7941  7941 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-10 13:33:46.155  7941  7941 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-10 13:33:46.156  7941  7941 V BluetoothSapReceiver: SapReceiver onReceive 
08-10 13:33:46.157  7941  7941 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-10 13:33:46.157  7941  7941 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-10 13:33:46.157  7904  7904 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-10 13:33:46.166  7904  7904 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
,08-10 13:33:46.169  7609  7609 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-10 13:33:46.172  7904  7904 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-10 13:33:46.173  7904  7904 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-10 13:33:46.174  7904  7904 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-10 13:33:46.174  7904  7904 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-10 13:33:46.175  7904  7904 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-10 13:33:46.175  7904  7904 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-10 13:33:46.176  7904  7904 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-10 13:33:46.177  7904  7904 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1470828826176]
,08-10 13:33:46.179  7904  7904 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-10 13:33:46.180  1031  1908 I ActivityManager: Killing 7144:com.android.chrome/u0a57 (adj 15): empty #17
08-10 13:33:46.198  7904  7968 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-10 13:33:46.263  1031  1908 I ActivityManager: Killing 7117:com.google.android.setupwizard/u0a46 (adj 15): empty #18
,08-10 13:33:46.321  1031  1890 W libprocessgroup: failed to open /acct/uid_10057/pid_7144/cgroup.procs: No such file or directory
,08-10 13:33:46.328  1031  2035 W libprocessgroup: failed to open /acct/uid_10046/pid_7117/cgroup.procs: No such file or directory
08-10 13:33:46.339  7904  7904 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,08-10 13:33:46.341  7904  7904 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-10 13:33:46.342  7904  7904 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-10 13:33:46.343  7904  7904 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-10 13:33:46.344  7904  7904 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-10 13:33:46.345  7904  7904 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
,08-10 13:33:46.346  7904  7904 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-10 13:33:46.359  7904  7904 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-10 13:33:46.541  7644  7736 D UEI.SmartControl: Internal timer expired: 1
08-10 13:33:46.541  7644  7736 D UEI.SmartControl: unbind internal service
,08-10 13:33:46.697  7644  7707 D serial_port: close(fd = 25)
,08-10 13:33:46.704  7644  7707 I UEI.SmartControl: Serial port is closed.
,08-10 13:33:49.673  6729  6799 D io.jxcore.node.ConnectivityMonitor: stop
08-10 13:33:49.673  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-10 13:33:54.686  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-10 13:33:54.686  6729  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1a11afb4 removed from the list
08-10 13:33:54.686  6729  6799 D io.jxcore.node.ConnectivityMonitor: stop
08-10 13:33:54.686  6729  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 13:33:54.687  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 13:33:54.689  6729  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 13:33:54.690  6729  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b76f52 added. We now have 4 listener(s)
,08-10 13:33:54.690  6729  6799 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-10 13:33:54.704  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 13:33:54.704  6729  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b76f52 removed from the list
08-10 13:33:54.704  6729  6799 D io.jxcore.node.ConnectivityMonitor: stop
08-10 13:33:54.705  6729  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 13:33:54.705  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 13:33:54.707  6729  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 13:33:54.707  6729  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1d719223 added. We now have 4 listener(s)
08-10 13:33:54.707  6729  6799 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 13:33:54.708  6729  6799 I System.out: IsBluetoothEnabled
08-10 13:33:54.709  1031  2373 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 13:33:54.709  1031  2373 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
08-10 13:33:54.709  1031  1096 D BluetoothManagerService: Message: 2
08-10 13:33:54.713  6729  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 13:33:54.716  1031  2006 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 13:33:54.716  1031  2006 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-10 13:33:54.734  1031  1031 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-10 13:33:54.734  1031  1031 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-10 13:33:54.734  1031  1031 D Ulp_jni : JNI:system_update. Event-4
08-10 13:33:54.735  1031  1096 D BluetoothManagerService: Message: 1
08-10 13:33:54.735  1031  1096 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-10 13:33:54.763  1031  1096 D BluetoothManagerService: Message: 20
08-10 13:33:54.763  1031  1096 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f25f86d:true
,08-10 13:33:54.767  7941  7941 D BluetoothAdapterState: make
08-10 13:33:54.772  7941  7941 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-10 13:33:54.772  7941  7941 I bluedroid-qcom: init
08-10 13:33:54.773  7941  7981 I BluetoothAdapterState: Entering OffState
08-10 13:33:54.773  7941  7941 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-10 13:33:54.774  7941  7941 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-10 13:33:54.774  7941  7941 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-10 13:33:54.774  7941  7941 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-10 13:33:54.774  7941  7941 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-10 13:33:54.776  7941  7941 I bluedroid-qcom: get_profile_interface socket
08-10 13:33:54.776  7941  7941 I bluedroid-qcom: get_profile_interface map_client
,08-10 13:33:54.780  7941  7985 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-10 13:33:54.763  7984  7984 W bdaddr_loader: type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-10 13:33:54.785  7941  7985 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-10 13:33:54.773  7984  7984 W bdaddr_loader: type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-10 13:33:54.795  1031  1031 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-10 13:33:54.795  1031  1031 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-10 13:33:54.796  1031  1031 D BluetoothManagerService: Stored Bluetooth name: G3
,08-10 13:33:54.798  1031  1096 D BluetoothManagerService: Message: 40
08-10 13:33:54.798  1031  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-10 13:33:54.800  7984  7984 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-10 13:33:54.800  7984  7984 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-10 13:33:54.800  7984  7984 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-10 13:33:54.801  7941  7957 I bluedroid-qcom: config_hci_snoop_log
08-10 13:33:54.803  7984  7984 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-10 13:33:54.804  1031  1096 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-10 13:33:54.805  1031  1096 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-10 13:33:54.807  7984  7984 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-10 13:33:54.807  7984  7984 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-10 13:33:54.809  7941  7985 D BluetoothAdapterProperties: Name is: G3
,08-10 13:33:54.816  7941  7981 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-10 13:33:54.816  7941  7981 D BluetoothAdapterProperties: Setting state to 11
08-10 13:33:54.816  7941  7981 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-10 13:33:54.817  1031  1096 D BluetoothManagerService: Message: 60
08-10 13:33:54.817  1031  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-10 13:33:54.817  1031  1096 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-10 13:33:54.818  7941  7981 I LGBluetoothServiceJni: classInitNative: succeeds
08-10 13:33:54.825  1945  1945 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-10 13:33:54.827  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-10 13:33:54.829  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 13:33:54.831  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 13:33:54.833  6876  6876 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-10 13:33:54.840  7941  7941 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-10 13:33:54.841  7941  7941 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-10 13:33:54.841  7941  7941 V BluetoothPbapReceiver: ***********state = 11
,08-10 13:33:54.852  2193  2193 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-10 13:33:54.856  7941  7981 D BluetoothBondStateMachine: make
,08-10 13:33:54.861  7941  7981 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@125b882
08-10 13:33:54.862  7941  7981 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-10 13:33:54.862  7941  7981 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@125b882
08-10 13:33:54.862  7941  7981 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-10 13:33:54.863  7941  7981 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-10 13:33:54.864  7941  7998 I BluetoothBondStateMachine: StableState(): Entering Off State
08-10 13:33:54.866  7941  7981 E BluetoothAdapterService: File transfer profiles supported!!
08-10 13:33:54.873  7941  7981 E BluetoothAdapterService: File transfer profiles supported!!
08-10 13:33:54.873  6876  6876 D BluetoothPermissionRequest: onReceive
08-10 13:33:54.873  7941  7941 D HeadsetService: Received start request. Starting profile...
,08-10 13:33:54.874  7941  7941 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-10 13:33:54.874  7941  7941 D LGBluetoothHfpAdapter: Version 1.6
08-10 13:33:54.877  7941  7941 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-10 13:33:54.878  7941  7941 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-10 13:33:54.879  6876  6876 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-10 13:33:54.879  7941  7941 D HeadsetStateMachine: make
08-10 13:33:54.881  7941  7981 E BluetoothAdapterService: File transfer profiles supported!!
08-10 13:33:54.886  7941  7981 E BluetoothAdapterService: File transfer profiles supported!!
,08-10 13:33:54.891  7941  7981 E BluetoothAdapterService: File transfer profiles supported!!
08-10 13:33:54.895  7941  7981 E BluetoothAdapterService: File transfer profiles supported!!
08-10 13:33:54.899  7941  7981 E BluetoothAdapterService: File transfer profiles supported!!
,08-10 13:33:54.914  7941  7981 V LGMDMManager: Create singleton instance
,08-10 13:33:54.915  7941  7941 D LgDataFeature: LgDataFeature() Constructor: none
08-10 13:33:54.915  7941  7941 D LgDataFeature: LgDataFeature() Constructor Done, null
08-10 13:33:54.916  7941  7981 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-10 13:33:54.919  7941  7941 D HeadsetStateMachine: max_hf_connections = 1
08-10 13:33:54.919  7941  7941 I bluedroid-qcom: get_profile_interface handsfree
08-10 13:33:54.921  7941  7941 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-10 13:33:54.922   310  1386 V AudioPolicyService: registerClient() client 0xb558aac0, uid 1002
08-10 13:33:54.922   310  2198 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
,08-10 13:33:54.922   310  2198 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-10 13:33:54.922   310  2198 V AudioPolicyManagerEx: getOutput() returns output 2
08-10 13:33:54.922  7941  7941 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-10 13:33:54.923   310  1387 V AudioFlinger: registerClient() client 0xb101a358, pid 7941
08-10 13:33:54.923   310  1381 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-10 13:33:54.923   310  1381 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-10 13:33:54.923  7941  7941 V ToneGenerator: Create Track: 0xb4928080
08-10 13:33:54.923  1031  1980 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-10 13:33:54.923  7941  7941 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-10 13:33:54.923  1031  1980 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-10 13:33:54.923  7941  7941 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-10 13:33:54.923  1605  1621 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-10 13:33:54.923  1605  1621 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-10 13:33:54.923  1856  4020 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-10 13:33:54.923  1856  4020 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-10 13:33:54.923  3485  3500 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-10 13:33:54.923  3485  3500 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-10 13:33:54.924   310  1382 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-10 13:33:54.924   310  1382 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-10 13:33:54.924  1856  4019 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-10 13:33:54.924  1856  4019 V AudioSystem: ioConfigChanged() opening already existing output! 4
,08-10 13:33:54.924  1605  1626 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-10 13:33:54.924  1605  1626 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-10 13:33:54.924   310  2199 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-10 13:33:54.924   310  2199 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-10 13:33:54.924   310  2199 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-10 13:33:54.924   310  2199 V AudioPolicyManagerEx: getOutput() returns output 2
08-10 13:33:54.924  1031  1578 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-10 13:33:54.924  7941  7957 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-10 13:33:54.924  1031  1578 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-10 13:33:54.924  7941  7957 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-10 13:33:54.924  3485  3501 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-10 13:33:54.924  3485  3501 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-10 13:33:54.924  7941  7957 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-10 13:33:54.924  7941  7957 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-10 13:33:54.924   310  2199 I AudioFlinger: isAudioPlaybackHookOn() false
08-10 13:33:54.925   310  2198 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-10 13:33:54.925   310  2198 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-10 13:33:54.925   310  2198 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-10 13:33:54.925   310  2198 V AudioPolicyManagerEx: getOutput() returns output 2
08-10 13:33:54.925  7941  7941 V AudioSystem: getLatency() output 2, latency 50
08-10 13:33:54.925  7941  7941 V AudioSystem: getFrameCount() output 2, frameCount 960
08-10 13:33:54.925  7941  7941 V AudioTrack: createTrack_l() output 2 afLatency 50
08-10 13:33:54.925   310  1386 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-10 13:33:54.925   310  1386 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-10 13:33:54.925   310  1386 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-10 13:33:54.925   310  1386 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-10 13:33:54.925   310  1386 V AudioFlinger: createTrack() lSessionId: 23
08-10 13:33:54.926  7941  7941 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-10 13:33:54.926   310  1386 V AudioFlinger: acquiring 23 from 7941, for 7941
08-10 13:33:54.926   310  1386 V AudioFlinger:  added new entry for 23
08-10 13:33:54.926  7941  7941 V ToneGenerator: ToneGenerator INIT OK, time: 382144
08-10 13:33:54.927  7941  7941 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@125b882
,08-10 13:33:54.928  7941  8002 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-10 13:33:54.929  7941  8002 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-10 13:33:54.929  7941  8002 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-10 13:33:54.929  7941  8002 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-10 13:33:54.929   310   310 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7941
08-10 13:33:54.930   310   310 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-10 13:33:54.930   310   310 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-10 13:33:54.930   310   310 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-10 13:33:54.930   310   310 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-10 13:33:54.930   310   310 V voice   : voice_set_parameters: exit with code(0)
08-10 13:33:54.930   310   310 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-10 13:33:54.930   310   310 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-10 13:33:54.930   310   310 V msm8974_platform: platform_set_parameters: exit with code(0)
08-10 13:33:54.930   310   310 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-10 13:33:54.930   310   310 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-10 13:33:54.930   310   310 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-10 13:33:54.930  7941  8002 V ToneGenerator: ToneGenerator destructor
08-10 13:33:54.930  7941  8002 V ToneGenerator: stopTone
08-10 13:33:54.930  7941  8002 V ToneGenerator: Delete Track: 0xb4928080
08-10 13:33:54.931  7941  8002 V AudioTrack: ~AudioTrack, releasing session id from 7941 on behalf of 7941
08-10 13:33:54.931   310  2199 V AudioFlinger: releasing 23 from 7941 for 7941
08-10 13:33:54.931   310  2199 V AudioFlinger:  decremented refcount to 0
08-10 13:33:54.931   310  2199 V AudioFlinger: purging stale effects
08-10 13:33:54.932   310  2199 V AudioPolicyService: AudioCommandThread() adding release output 2
08-10 13:33:54.932  7941  7941 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@125b882
08-10 13:33:54.932   310  2199 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-10 13:33:54.932   310  1260 V AudioPolicyService: AudioCommandThread() waking up
08-10 13:33:54.932   310  1260 V AudioPolicyService: AudioCommandThread() processing release output 2
08-10 13:33:54.932   310  1260 V AudioPolicyManager: releaseOutput() 2
08-10 13:33:54.932   310  1260 V AudioPolicyService: AudioCommandThread() going to sleep
08-10 13:33:54.932   310  2199 V AudioFlinger: PlaybackThread::Track destructor
08-10 13:33:54.932   310  2199 V AudioFlinger: removeClient_l() pid 7941, calling pid 310
08-10 13:33:54.933  1031  2016 W Process : Unable to open /proc/8005/status
08-10 13:33:54.934  7941  7941 D A2dpService: Received start request. Starting profile...
08-10 13:33:54.935  7941  7941 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-10 13:33:54.935  7941  7941 V Avrcp   : make
08-10 13:33:54.936  7941  7941 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-10 13:33:54.936  7941  7941 I bluedroid-qcom: get_profile_interface avrcp
08-10 13:33:54.943  7941  7941 V AudioManager: registerRemoteController: size of Media player list: 0
,08-10 13:33:54.945  7941  7941 E AudioManager: No RCC entry present to update
08-10 13:33:54.945  7941  7941 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-10 13:33:54.948  7941  7941 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-10 13:33:54.948  7941  7941 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-10 13:33:54.948  7941  7941 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-10 13:33:54.952  7941  7941 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-10 13:33:55.081  1031  1908 V SIM_STK : Menu title from STK is T-Mobile
08-10 13:33:55.081  1031  1908 V SIM_STK : Menu title from STK is T-Mobile
,08-10 13:33:55.215  1031  2373 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-10 13:33:55.230  7941  7941 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,08-10 13:33:55.237  7941  7941 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
,08-10 13:33:55.238  7941  7941 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-10 13:33:55.238  7941  7941 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-10 13:33:55.238  7941  7941 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-10 13:33:55.238  7941  7941 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
,08-10 13:33:55.238  7941  7941 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-10 13:33:55.238  7941  7941 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-10 13:33:55.238  7941  7941 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-10 13:33:55.238  7941  7941 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-10 13:33:55.238  7941  7941 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-10 13:33:55.239  7941  7941 I BluetoothA2dpServiceJni: classInitNative
08-10 13:33:55.239  7941  7941 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-10 13:33:55.239  7941  7941 D A2dpStateMachine: make
08-10 13:33:55.243  7941  7941 I bluedroid-qcom: get_profile_interface a2dp,
08-10 13:33:55.243  7941  8013 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-10 13:33:55.246  7941  7941 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-10 13:33:55.247  7941  7941 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-10 13:33:55.248  7941  7941 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@125b882
08-10 13:33:55.249  7941  7941 I BluetoothHidServiceJni: classInitNative: succeeds
,08-10 13:33:55.253  7941  8012 D A2dpStateMachine: Enter Disconnected: -2
,08-10 13:33:55.253  7941  7941 D HidService: Received start request. Starting profile...
08-10 13:33:55.253  7941  7941 I bluedroid-qcom: get_profile_interface hidhost
,08-10 13:33:55.253  7941  7941 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@125b882
08-10 13:33:55.254  7941  7941 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-10 13:33:55.256  7941  7941 D HealthService: Received start request. Starting profile...
08-10 13:33:55.260  7941  7941 I bluedroid-qcom: get_profile_interface health
08-10 13:33:55.261  7941  7941 I LGBluetoothHealthServiceJni: classInitNative: succeeds
,08-10 13:33:55.261  7941  7941 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@125b882
08-10 13:33:55.263  7941  7941 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-10 13:33:55.265  7941  7941 D PanService: Received start request. Starting profile...
08-10 13:33:55.265  7941  7941 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-10 13:33:55.265  7941  7941 I bluedroid-qcom: get_profile_interface pan
,08-10 13:33:55.275  7941  7941 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
,08-10 13:33:55.275  7941  7941 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@125b882
,08-10 13:33:55.277  7941  7941 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-10 13:33:55.283  7941  7941 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-10 13:33:55.290  7941  7941 D BtGatt.GattService: Received start request. Starting profile...
08-10 13:33:55.290  7941  7941 D BtGatt.GattService: start()
08-10 13:33:55.290  7941  7941 I bluedroid-qcom: get_profile_interface gatt
08-10 13:33:55.291  7941  7941 D BtGatt.AdvertiseManager: advertise manager created
08-10 13:33:55.300  7941  7941 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@125b882
,08-10 13:33:55.304  7941  7941 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@125b882
08-10 13:33:55.305  7941  7941 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-10 13:33:55.306  7941  7941 V BluetoothMapService: BluetoothMapBinder()
08-10 13:33:55.306  7941  7941 D BluetoothMapService: Received start request. Starting profile...
08-10 13:33:55.306  7941  7941 D BluetoothMapService: start()
08-10 13:33:55.310  7941  7941 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-10 13:33:55.310  7941  7941 D BluetoothMapEmailAppObserver: createReceiver()
08-10 13:33:55.311  7941  7941 D BluetoothMapEmailAppObserver: initObservers()
08-10 13:33:55.311  7941  7941 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-10 13:33:55.320  7941  7941 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@125b882
,08-10 13:33:55.321  7941  7941 D HeadsetStateMachine: Proxy object connected
08-10 13:33:55.321  7941  7941 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-10 13:33:55.322  7941  7941 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-10 13:33:55.327  7941  7941 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-10 13:33:55.328  7941  8002 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-10 13:33:55.328  7941  8002 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-10 13:33:55.328  7941  8002 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-10 13:33:55.330  7941  7941 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-10 13:33:55.334  7941  7941 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-10 13:33:55.337  7941  7941 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-10 13:33:55.339  7941  7941 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-10 13:33:55.342  7941  7941 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-10 13:33:55.343  7941  7941 V PanService: [BTUI] SIM Extra State :ABSENT
08-10 13:33:55.346  7941  7941 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
,08-10 13:33:55.346  7941  7941 V BluetoothMapService: Handler(): got msg=1
08-10 13:33:55.347  7941  7941 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-10 13:33:55.348  7941  7941 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-10 13:33:55.348  7941  7941 V BluetoothSapReceiver: SapReceiver onReceive 
08-10 13:33:55.348  7941  7941 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-10 13:33:55.348  7941  7941 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-10 13:33:55.350  7941  7981 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-10 13:33:55.350  7941  7981 I bluedroid-qcom: enable
08-10 13:33:55.350  7941  7981 I bt_hci_bdroid: init
08-10 13:33:55.353  7941  7981 I bt_vendor: bt-vendor : init
08-10 13:33:55.353  7941  7981 I bt_vendor: bt-vendor : get_bt_soc_type
08-10 13:33:55.353  7941  7981 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-10 13:33:55.353  7941  7981 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-10 13:33:55.353  7941  7981 D bt_userial_mct: userial_init
,08-10 13:33:55.354  7941  8023 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-10 13:33:55.354  7941  8023 I bt-btu  : btu_task pending for preload complete event
,08-10 13:33:55.356  7941  7981 D bt_hci_bdroid: set_power 1
08-10 13:33:55.356  7941  7981 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-10 13:33:55.356  7941  7981 I bt_vendor: Starting hciattach daemon
08-10 13:33:55.356  7941  7981 I bt_vendor: try to set true
08-10 13:33:55.342  8026  8026 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-10 13:33:55.342  8026  8026 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-10 13:33:55.384  8036  8036 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-10 13:33:55.486  8044  8044 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-10 13:33:55.507  8045  8045 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-10 13:33:55.556  8047  8047 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-10 13:33:55.571  8048  8048 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-10 13:33:55.594  8049  8049 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-10 13:33:55.607  8050  8050 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-10 13:33:55.633  8052  8052 I libmdmdetect: ESOC framework not supported
08-10 13:33:55.635  8052  8052 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-10 13:33:55.646  8052  8052 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,08-10 13:33:55.646  8052  8052 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-10 13:33:55.646  8052  8052 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-10 13:33:55.646  8052  8052 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-10 13:33:55.647  8052  8052 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-10 13:33:55.647  8052  8052 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-10 13:33:55.647  8052  8052 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-10 13:33:55.694  8052  8056 E QC-QMI  : qmi_client [8052] 15: failed to locate client data
08-10 13:33:55.695   484   484 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-10 13:33:55.695   484   484 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,08-10 13:33:55.726  8060  8060 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-10 13:33:55.739  8061  8061 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-10 13:33:55.810  7941  7981 I bt_vendor: bluetooth satus is on
08-10 13:33:55.811  7941  7981 D bt_hci_bdroid: preload
,08-10 13:33:55.812  7941  8025 D bt_userial_mct: userial_open(port:0)
08-10 13:33:55.812  7941  8025 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-10 13:33:55.816  7941  8025 I bt_vendor: Done intiailizing UART
08-10 13:33:55.820  7941  8025 I bt_vendor: Done intiailizing UART
08-10 13:33:55.820  7941  8025 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-10 13:33:55.821  7941  8025 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-10 13:33:55.821  7941  8063 D bt_userial_mct: Entering userial_read_thread()
08-10 13:33:55.822  7941  8023 I bt-btu  : btu_task received preload complete event
08-10 13:33:55.822  7941  8023 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-10 13:33:55.823  7941  8023 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
,08-10 13:33:55.827  7941  8023 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003,
08-10 13:33:55.836  7941  8023 I         : BTE_InitTraceLevels -- TRC_HCI
08-10 13:33:55.837  7941  8023 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-10 13:33:55.837  7941  8023 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-10 13:33:55.837  7941  8023 I         : BTE_InitTraceLevels -- TRC_AVDT
08-10 13:33:55.837  7941  8023 I         : BTE_InitTraceLevels -- TRC_AVRC,
08-10 13:33:55.837  7941  8023 I         : BTE_InitTraceLevels -- TRC_A2D
08-10 13:33:55.837  7941  8023 I         : BTE_InitTraceLevels -- TRC_BNEP
08-10 13:33:55.837  7941  8023 I         : BTE_InitTraceLevels -- TRC_BTM
08-10 13:33:55.837  7941  8023 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-10 13:33:55.837  7941  8023 I         : BTE_InitTraceLevels -- TRC_GAP
08-10 13:33:55.837  7941  8023 I         : BTE_InitTraceLevels -- TRC_PAN,
08-10 13:33:55.837  7941  8023 I         : BTE_InitTraceLevels -- TRC_SDP
08-10 13:33:55.837  7941  8023 I         : BTE_InitTraceLevels -- TRC_GATT
08-10 13:33:55.837  7941  8023 I         : BTE_InitTraceLevels -- TRC_SMP
,08-10 13:33:55.837  7941  8023 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-10 13:33:55.837  7941  8023 I         : BTE_InitTraceLevels -- TRC_BTIF
08-10 13:33:55.886  7941  8023 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-10 13:33:55.886  7941  8023 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa014d061 
08-10 13:33:55.886  7941  8023 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa014d061 ,
,08-10 13:33:55.909  7941  7985 E bt-btif : Calling BTA_HhEnable
08-10 13:33:55.909  7941  7985 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-10 13:33:55.910  7941  7985 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-10 13:33:55.917  1031  1031 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-10 13:33:55.918  7941  7985 D BluetoothAdapterProperties: Name is: G3
08-10 13:33:55.921  7941  7985 D BluetoothAdapterProperties: Scan Mode:20
08-10 13:33:55.922  7941  7985 D BluetoothAdapterProperties: Discoverable Timeout:120
08-10 13:33:55.922  7941  7985 D bt_hci_bdroid: postload
08-10 13:33:55.925  7941  7985 D bte_conf: Device ID record 1 : primary
08-10 13:33:55.925  7941  7985 D bte_conf:   vendorId            = 00c4
08-10 13:33:55.925  7941  7985 D bte_conf:   vendorIdSource      = 0001
08-10 13:33:55.925  7941  7985 D bte_conf:   product             = 13a1
08-10 13:33:55.925  7941  7985 D bte_conf:   version             = 1000
08-10 13:33:55.925  7941  7985 D bte_conf:   clientExecutableURL = 
08-10 13:33:55.925  7941  7985 D bte_conf:   serviceDescription  = 
08-10 13:33:55.925  7941  7985 D bte_conf:   documentationURL    = 
,08-10 13:33:55.928  7941  8025 D bt_hci_bdroid: Used up Tx Cmd credits
,08-10 13:33:55.929  7941  7985 D bte_conf: bte_load_did_conf no section named DID2.
08-10 13:33:55.929  7941  8025 D bt_hci_bdroid: Used up Tx Cmd credits
08-10 13:33:55.934  7941  7981 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-10 13:33:55.934  7941  7981 D BluetoothAdapterProperties: ScanMode =  20
08-10 13:33:55.934  7941  7981 D BluetoothAdapterProperties: State =  11
08-10 13:33:55.934  7941  7981 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-10 13:33:55.935  7941  7981 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-10 13:33:55.935  7941  7981 D BluetoothAdapterProperties: Setting state to 12
08-10 13:33:55.935  7941  7981 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-10 13:33:55.922  8068  8068 W sh      : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-10 13:33:55.946  1031  1096 D BluetoothManagerService: Message: 60
08-10 13:33:55.946  1031  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-10 13:33:55.946  1031  1096 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
08-10 13:33:55.946  7941  7981 I BluetoothAdapterState: Entering On State
08-10 13:33:55.932  8068  8068 W sh      : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-10 13:33:55.952  7941  8063 E bt_mct  : hci lib postload completed
08-10 13:33:55.954  7941  7985 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-10 13:33:55.960  1031  1031 D BluetoothManagerService: Stored Bluetooth name: G3
08-10 13:33:55.975  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 13:33:55.975  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 13:33:55.975  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 13:33:55.975  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 13:33:55.975  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 13:33:55.975  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 13:33:55.975  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 13:33:55.975  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-10 13:33:55.982  7941  7985 D BluetoothAdapterProperties: Discoverable Timeout:120
08-10 13:33:55.982  7941  7985 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-10 13:33:55.988  6729  6729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-10 13:33:55.997  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 13:33:55.997  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 13:33:55.997  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 13:33:55.997  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 13:33:55.997  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 13:33:55.997  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 13:33:55.997  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 13:33:55.997  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 13:33:56.002  6729  6729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-10 13:33:56.017  7941  7981 D LGBluetoothServiceAdapter: [BTUI] OnState
08-10 13:33:56.017  7941  7981 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-10 13:33:56.017  7941  7981 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,08-10 13:33:56.020  7941  7981 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-10 13:33:56.020  7941  7981 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-10 13:33:56.021  7941  8023 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-10 13:33:56.021  7941  8023 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-10 13:33:56.021  7941  8023 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-10 13:33:56.022  7941  8023 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-10 13:33:56.022  7941  8023 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-10 13:33:56.022  7941  8023 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-10 13:33:56.022  7941  7985 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-10 13:33:56.023  6876  6892 D BluetoothA2dp: onBluetoothStateChange: up=true
08-10 13:33:56.053  6876  6893 D BluetoothHeadset: onBluetoothStateChange: up=true
08-10 13:33:56.053  6876  6876 D BluetoothA2dp: Proxy object connected
08-10 13:33:56.053  6876  6876 D A2dpProfile: Bluetooth service connected
,08-10 13:33:56.060  7941  8023 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-10 13:33:56.060  7941  8023 W bt-smp  : Plain text(LSB ~ MSB) = cb 09 6b 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-10 13:33:56.060  7941  8023 W bt-smp  : Encrypted text(LSB ~ MSB) = 91 5e 91 93 61 26 a4 3a a5 de f8 a7 e6 49 d3 a8 
08-10 13:33:56.060  7941  8023 W bt-btm  : Stopping oneshot timer
08-10 13:33:56.061  1856  2431 D BluetoothHeadset: onBluetoothStateChange: up=true
08-10 13:33:56.062  8085  8085 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-10 13:33:56.078  7941  8023 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-10 13:33:56.078  7941  8023 W bt-smp  : Plain text(LSB ~ MSB) = 92 e0 50 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-10 13:33:56.078  7941  8023 W bt-smp  : Encrypted text(LSB ~ MSB) = e8 7d 22 96 97 19 9c 4f 0d b2 d1 1f b5 f3 6d 59 
08-10 13:33:56.078  7941  8023 W bt-btm  : Stopping oneshot timer
,08-10 13:33:56.093  7941  8023 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-10 13:33:56.093  7941  8023 W bt-smp  : Plain text(LSB ~ MSB) = f5 3c 68 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-10 13:33:56.093  7941  8023 W bt-smp  : Encrypted text(LSB ~ MSB) = 6c f8 21 42 75 6b 12 bb 8a 76 d0 b3 1c e2 a3 7b 
08-10 13:33:56.093  7941  8023 W bt-btm  : Stopping oneshot timer
,08-10 13:33:56.106  7941  8023 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-10 13:33:56.106  7941  8023 W bt-smp  : Plain text(LSB ~ MSB) = c1 50 64 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-10 13:33:56.106  7941  8023 W bt-smp  : Encrypted text(LSB ~ MSB) = 29 47 94 c8 bf ec 83 67 f8 19 90 20 b8 54 1e ab 
08-10 13:33:56.106  7941  8023 W bt-btm  : Stopping oneshot timer
,08-10 13:33:56.123  7941  8023 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-10 13:33:56.123  7941  8023 W bt-smp  : Plain text(LSB ~ MSB) = c3 0d 47 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-10 13:33:56.123  7941  8023 W bt-smp  : Encrypted text(LSB ~ MSB) = 40 96 59 95 15 a0 6a 85 76 1f f9 da 1a 1c 49 b2 
08-10 13:33:56.123  7941  8023 W bt-btm  : Stopping oneshot timer
,08-10 13:33:56.187  1031  1047 I art     : Explicit concurrent mark sweep GC freed 28820(1413KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 1.850ms total 124.139ms
,08-10 13:33:56.193  1031  1096 D BluetoothA2dp: onBluetoothStateChange: up=true
08-10 13:33:56.193  1856  1856 D BluetoothHeadset: Proxy object connected
08-10 13:33:56.194  6876  6876 D BluetoothHeadset: Proxy object connected
08-10 13:33:56.194  6876  6876 D HeadsetProfile: Bluetooth service connected
08-10 13:33:56.196  1031  1031 D BluetoothA2dp: Proxy object connected
08-10 13:33:56.196  6876  6893 D BluetoothPbap: onBluetoothStateChange: up=true
08-10 13:33:56.198  1856  1872 D BluetoothHeadset: onBluetoothStateChange: up=true
08-10 13:33:56.199  1856  1856 D BluetoothHeadset: Proxy object connected
08-10 13:33:56.200  6876  6893 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-10 13:33:56.201  1856  2431 D BluetoothHeadset: onBluetoothStateChange: up=true
08-10 13:33:56.202  1856  1856 D BluetoothHeadset: Proxy object connected
08-10 13:33:56.202  1031  1096 D BluetoothHeadset: onBluetoothStateChange: up=true
08-10 13:33:56.203  6876  6876 D BluetoothInputDevice: Proxy object connected
08-10 13:33:56.203  6876  6876 D HidProfile: Bluetooth service connected
08-10 13:33:56.203  1031  1031 D BluetoothHeadset: Proxy object connected
08-10 13:33:56.203  6876  6892 D BluetoothMap: onBluetoothStateChange: up=true
08-10 13:33:56.208  6876  6893 D BluetoothPan: onBluetoothStateChange on: true
08-10 13:33:56.208  6876  6893 D BluetoothPan: onBluetoothStateChange call bindService
08-10 13:33:56.209  6876  6876 D BluetoothMap: Proxy object connected
08-10 13:33:56.209  6876  6876 D MapProfile: Bluetooth service connected
08-10 13:33:56.209  6876  6876 D BluetoothMap: getConnectedDevices()
08-10 13:33:56.211  7941  8089 V BluetoothMapService: getConnectedDevices()
,08-10 13:33:56.213  1031  1096 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-10 13:33:56.214  1031  1096 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-10 13:33:56.215  6876  6876 D BluetoothPan: BluetoothPAN Proxy object connected
08-10 13:33:56.215  6876  6876 D PanProfile: Bluetooth service connected
08-10 13:33:56.215  1031  1031 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-10 13:33:56.219  1031  1096 D BluetoothManagerService: Message: 40
08-10 13:33:56.219  1031  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-10 13:33:56.220  1945  1945 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-10 13:33:56.220  1945  2120 D LGBluetoothAPIService: Message: 1
08-10 13:33:56.220  1945  2120 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-10 13:33:56.220  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-10 13:33:56.225  1945  2120 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-10 13:33:56.226  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 13:33:56.226  7941  7941 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-10 13:33:56.226  7941  7941 D BluetoothMapService: STATE_ON
08-10 13:33:56.228  7941  7941 D LGBluetoothAPIServer: [BTUI] onCreate()
08-10 13:33:56.228  7941  7941 D LGBluetoothAPIServer: [BTUI] onBind()
08-10 13:33:56.228  7941  7941 V BluetoothMapService: Handler(): got msg=1
08-10 13:33:56.228  1945  1945 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-10 13:33:56.229  1945  2120 D LGBluetoothAPIService: Message: 100
08-10 13:33:56.229  1945  2120 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-10 13:33:56.229  7941  7941 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-10 13:33:56.229  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 13:33:56.230  6876  6876 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-10 13:33:56.231  7941  8093 D BluetoothMapMasInstance: MAS initSocket()
08-10 13:33:56.231  6876  6876 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-10 13:33:56.231  7941  8093 D BluetoothMapMasInstance:   masId = 00
08-10 13:33:56.231  7941  8093 D BluetoothMapMasInstance:   msgTypes = 0e
08-10 13:33:56.231  7941  8093 D BluetoothMapMasInstance:   masName = SMS/MMS
08-10 13:33:56.231  7941  8093 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-10 13:33:56.233  1031  1578 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 13:33:56.234  7941  8093 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-10 13:33:56.236  7941  7985 D BluetoothAdapterProperties: Scan Mode:21
08-10 13:33:56.236  7941  7985 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-10 13:33:56.237  7941  8093 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-10 13:33:56.237  7941  8093 V BluetoothMapMasInstance: Succeed to create listening socket 
08-10 13:33:56.237  7941  8093 D BluetoothMapMasInstance: Accepting socket connection...
08-10 13:33:56.238  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 13:33:56.238  6876  6876 D DockEventReceiver: finishStartingService: stopping service
,08-10 13:33:56.245  7941  7941 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@125b882
08-10 13:33:56.245  7941  7941 V BluetoothPbapService: Pbap Service onCreate
08-10 13:33:56.245  7941  7941 V BluetoothPbapService: Starting PBAP service
08-10 13:33:56.246  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 13:33:56.246  7941  7941 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-10 13:33:56.247  7941  7941 V BluetoothPbapService: Pbap Service onBind
08-10 13:33:56.248  7941  7941 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-10 13:33:56.249  7941  7941 V BluetoothPbapService: state: 12
08-10 13:33:56.249  6876  6876 D BluetoothPbap: Proxy object connected
08-10 13:33:56.249  6876  6876 D PbapServerProfile: Bluetooth service connected
08-10 13:33:56.249  7941  7941 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-10 13:33:56.249  7941  7941 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-10 13:33:56.249  7941  7941 V BluetoothPbapReceiver: ***********state = 12
08-10 13:33:56.250  7941  7941 V BluetoothPbapService: Handler(): got msg=1
08-10 13:33:56.250  7941  7941 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-10 13:33:56.252  7941  8096 V BluetoothPbapService: Pbap Service initSocket
08-10 13:33:56.252  2193  2193 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-10 13:33:56.254  2193  2193 D c       : Getting all permits...
08-10 13:33:56.254  1031  1047 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 13:33:56.254  2193  2193 D a       : Opening database...
08-10 13:33:56.256  7941  8096 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-10 13:33:56.256  7941  8096 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-10 13:33:56.256  7941  8096 V BluetoothPbapService: Succeed to create listening socket 
08-10 13:33:56.256  7941  8096 V BluetoothPbapService: Accepting socket connection...
08-10 13:33:56.258  2193  2193 D a       : Opening database auth.proximity.permit_store...
08-10 13:33:56.259  2193  2193 D a       : Closing database...
08-10 13:33:56.266  6876  6876 D BluetoothPermissionRequest: onReceive
,08-10 13:33:56.267  6876  6876 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-10 13:33:56.268  6876  6876 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-10 13:33:56.271  7941  7941 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-10 13:33:56.272  7941  7941 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-10 13:33:56.277  7941  7941 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-10 13:33:56.287  7941  7941 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-10 13:33:56.287  7941  7941 V BtOppService: onCreate
,08-10 13:33:56.290  7941  7941 V BluetoothOppNotification: send message
08-10 13:33:56.292  7941  7941 V BtOppService: Starting RfcommListener
08-10 13:33:56.295  7941  7941 D BluetoothOppPreference: Dumping Names:  
08-10 13:33:56.295  7941  7941 D BluetoothOppPreference: {}
08-10 13:33:56.295  7941  7941 D BluetoothOppPreference: Dumping Channels:  
08-10 13:33:56.296  7941  7941 D BluetoothOppPreference: {}
08-10 13:33:56.296  7941  7941 V BtOppService: onStartCommand
08-10 13:33:56.298  7941  8102 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-10 13:33:56.298  7941  7941 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-10 13:33:56.298  7941  7941 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-10 13:33:56.300  7941  7941 V BluetoothOppNotification: new notify threadi!
08-10 13:33:56.300  7941  7941 V BluetoothOppNotification: send delay message
08-10 13:33:56.303  7941  7941 V BtOppService: start RfcommListener
,08-10 13:33:56.303  7941  8102 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-10 13:33:56.304  7941  8103 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-10 13:33:56.308  7941  8099 V BtOppService: Deleted complete outbound shares, number =  0
08-10 13:33:56.309  7941  7941 V BtOppService: RfcommListener started
08-10 13:33:56.310  7941  8104 V BtOppRfcommListener: Starting RFCOMM listener....
08-10 13:33:56.311  1031  1773 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 13:33:56.311  7941  8102 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3167babf on behalf of 
08-10 13:33:56.311  7941  8104 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-10 13:33:56.312  7941  8104 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=75
08-10 13:33:56.313  7941  8099 V BtOppService: Deleted complete inbound failed shares, number = 0
08-10 13:33:56.313  7941  8104 V BtOppRfcommListener: Started RFCOMM listener....
08-10 13:33:56.313  7941  8104 I BtOppRfcommListener: Accept thread started.
08-10 13:33:56.313  7941  8103 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@12cae58c on behalf of 
08-10 13:33:56.313  7941  8099 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
,08-10 13:33:56.314  7941  8104 V BtOppRfcommListener: Accepting connection...
08-10 13:33:56.314  7941  8103 V BluetoothOppNotification: mUpdateCompleteNotification = true
,08-10 13:33:56.315  7941  8099 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@289c94d5 on behalf of 
,08-10 13:33:56.315  7941  8102 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-10 13:33:56.317  7941  8103 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-10 13:33:56.318  7941  8103 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@31c274ea on behalf of 
08-10 13:33:56.318  7941  8103 V BluetoothOppNotification: outbound: succ-0  fail-0
08-10 13:33:56.319  7941  8103 V BluetoothOppNotification: outbound notification was removed.
08-10 13:33:56.320  7941  8103 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-10 13:33:56.321  7941  8103 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@66743db on behalf of 
08-10 13:33:56.321  7941  8103 V BluetoothOppNotification: inbound: succ-0  fail-0
08-10 13:33:56.322  7941  8103 V BluetoothOppNotification: inbound notification was removed.
08-10 13:33:56.322  7941  8103 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-10 13:33:56.323  7941  8103 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@706ce78 on behalf of 
08-10 13:33:56.330  7941  7941 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@125b882
08-10 13:33:56.330  7941  7941 V BluetoothFtpService: Ftp Service onCreate
08-10 13:33:56.330  7941  7941 I BluetoothFtpService: Ftp Service onCreate
08-10 13:33:56.330  7941  7941 V BluetoothFtpService: Ftp Service onStartCommand
08-10 13:33:56.330  7941  7941 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-10 13:33:56.330  7941  7941 V BluetoothFtpService: Starting Listening on sockets
08-10 13:33:56.331  7941  7941 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-10 13:33:56.331  7941  7941 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-10 13:33:56.331  7941  7941 V BluetoothSapReceiver: SapReceiver onReceive 
08-10 13:33:56.331  7941  7941 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-10 13:33:56.331  7941  7941 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-10 13:33:56.331  7941  7941 V BluetoothSapReceiver: Calling SAP service start service with action = null
,08-10 13:33:56.333  7941  7941 V BtOppService: ContentObserver received notification
08-10 13:33:56.333  7941  7941 V BtOppService: ContentObserver received notification
08-10 13:33:56.334  7941  7941 V BluetoothFtpService: Handler(): got msg=1
08-10 13:33:56.334  7941  8105 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-10 13:33:56.334  7941  8105 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-10 13:33:56.335  7941  7941 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-10 13:33:56.335  7941  7941 V BluetoothFtpService: Ftp Service initSocket
08-10 13:33:56.335  7941  8105 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@25caf5b6 on behalf of 
08-10 13:33:56.335  7941  8105 V BluetoothOppNotification: update too frequent, put in queue
08-10 13:33:56.336  7941  8105 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-10 13:33:56.338  1031  1773 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 13:33:56.338  7941  7941 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-10 13:33:56.339  7941  7941 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-10 13:33:56.341  7941  8106 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-10 13:33:56.356  7941  7941 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@125b882
,08-10 13:33:56.356  7941  7941 V BluetoothSapService: Sap Service onCreate
08-10 13:33:56.358  7941  7941 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-10 13:33:56.358  7941  7941 V BluetoothSapService: state: 12
,08-10 13:33:56.359  7941  7941 V BluetoothSapService: Starting SAP server process
08-10 13:33:56.361  7941  7941 V BluetoothSapService: SAP Service startRfcommListenerThread
08-10 13:33:56.342  8107  8107 W sapd    : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-10 13:33:56.342  8107  8107 W sapd    : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-10 13:33:56.364  7941  8108 V BluetoothSapService: Sap Service initRfcommSocket
08-10 13:33:56.365  1031  1908 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 13:33:56.367  7941  8108 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-10 13:33:56.369  7941  8108 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-10 13:33:56.370  7941  8108 V BluetoothSapService: Succeed to create listening socket 
08-10 13:33:56.370  7941  8108 V BluetoothSapService: Accepting socket connection...
,08-10 13:33:56.376  8107  8107 V BT_SAP  : Event pipe created
,08-10 13:33:56.376  8107  8107 V BT_SAP  : create_server_socket qcom.sap.server
,08-10 13:33:56.377  8107  8107 V BT_SAP  : created socket fd 6
08-10 13:33:56.770  6729  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 13:33:56.770  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 13:33:56.770  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 13:33:56.770  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 13:33:56.770  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 13:33:56.770  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 13:33:56.770  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 13:33:56.770  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-10 13:33:56.787  6729  6799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 13:33:56.789  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 13:33:56.789  6729  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1d719223 removed from the list
08-10 13:33:56.789  6729  6799 D io.jxcore.node.ConnectivityMonitor: stop
08-10 13:33:56.789  6729  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 13:33:56.789  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 13:33:56.790  6729  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 13:33:56.790  6729  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@df41320 added. We now have 4 listener(s)
08-10 13:33:56.790  6729  6799 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 13:33:56.794  1031  1908 D WifiServiceImplEx: setWifiEnabled: false pid=6729, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-10 13:33:56.797  1031  1908 D WifiService: setWifiEnabled: false pid=6729, uid=10118
08-10 13:33:56.797  1031  1908 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-10 13:33:56.802  6729  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 13:33:56.805  1031  2006 D WifiServiceImplEx: setWifiEnabled: true pid=6729, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-10 13:33:56.805  1031  2006 D WifiService: setWifiEnabled: true pid=6729, uid=10118
08-10 13:33:56.805  1031  2006 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-10 13:33:56.824  1031  1031 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-10 13:33:56.824  1031  1031 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,08-10 13:33:56.824  1031  1031 D Ulp_jni : JNI:system_update. Event-4
08-10 13:33:56.826  1031  1539 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-10 13:33:56.826  1031  1539 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-10 13:33:56.828  1031  1539 E WifiUtil: wfc_util_ffile_check_copy(): pid[1031] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-10 13:33:56.829  1031  1539 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-10 13:33:56.829  1031  1539 E WifiUtil: wfc_util_ffile_check_copy(): pid[1031] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-10 13:33:56.829  1031  1539 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
,08-10 13:33:56.829  1031  1539 I WifiUtil: Intf0MacAddress=C49A027FFB5D,
08-10 13:33:56.829  1031  1539 E WifiHW  : unknown target_country: EU , set to default,
08-10 13:33:56.829  1031  1539 E WifiHW  : [wifi_ensure_config_files] default country1 = GB,
,08-10 13:33:56.829  1031  1539 E WifiHW  : [wifi_ensure_config_files] default country2 = GB,
08-10 13:33:56.829  1031  1539 I WifiUtil: gEnableBmps=1
08-10 13:33:57.305  7941  7941 V BluetoothOppNotification: new notify threadi!
,08-10 13:33:57.305  7941  7941 V BluetoothOppNotification: send delay message
,08-10 13:33:57.326  7941  8127 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-10 13:33:57.327  7941  8127 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3f08b742 on behalf of 
08-10 13:33:57.327  7941  8127 V BluetoothOppNotification: mUpdateCompleteNotification = true
,08-10 13:33:57.330  7941  8127 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-10 13:33:57.331  7941  8127 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3d985353 on behalf of 
08-10 13:33:57.332  7941  8127 V BluetoothOppNotification: outbound: succ-0  fail-0
08-10 13:33:57.335  7941  8127 V BluetoothOppNotification: outbound notification was removed.
08-10 13:33:57.335  7941  8127 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-10 13:33:57.336  7941  8127 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2870f490 on behalf of 
08-10 13:33:57.336  7941  8127 V BluetoothOppNotification: inbound: succ-0  fail-0
08-10 13:33:57.338  7941  8127 V BluetoothOppNotification: inbound notification was removed.
08-10 13:33:57.338  7941  8127 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-10 13:33:57.339  7941  8127 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@19fc3189 on behalf of 
,08-10 13:33:57.411   306   896 D SoftapController: Softap fwReload - Ok
,08-10 13:33:57.415  1031  1539 E NetdConnector: NDC Command {82 softap fwreload wlan0 STA} took too long (583ms)
08-10 13:33:57.422   306   896 D CommandListener: Setting iface cfg
08-10 13:33:57.422   306   896 D CommandListener: Trying to bring down wlan0
08-10 13:33:57.423  1031  1096 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-10 13:33:57.443  1031  1096 D Tethering: InitialState.processMessage what=4
08-10 13:33:57.444  1031  1096 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-10 13:33:57.448   306   896 D CommandListener: Clearing all IP addresses on wlan0
,08-10 13:33:57.460  1031  1539 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,08-10 13:33:57.452  8129  8129 W wpa_supplicant: type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-10 13:33:57.462  8129  8129 W wpa_supplicant: type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-10 13:33:57.479  1031  1539 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-10 13:33:57.479  1031  1539 E WifiStateMachine: useWiFiOffloading() : false
08-10 13:33:57.479  1031  1539 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-10 13:33:57.493  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-10 13:33:57.502  1945  1945 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-10 13:33:57.523  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 13:33:57.527  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 13:33:57.527  1031  1031 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-10 13:33:57.527  1031  1539 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-10 13:33:57.527  1031  1539 D WifiMonitor: connecting to supplicant
08-10 13:33:57.540  6876  6876 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-10 13:33:57.540  6876  6876 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-10 13:33:57.540  6876  6876 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-10 13:33:57.540  6876  6876 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-10 13:33:57.541  6876  6876 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-10 13:33:57.544  6876  6876 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-10 13:33:57.545  6876  6876 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-10 13:33:57.545  6876  6876 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-10 13:33:57.545  6876  6876 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-10 13:33:57.545  6876  6876 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-10 13:33:57.545  6876  6876 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-10 13:33:57.546  6876  6876 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-10 13:33:57.550  8129  8129 I wpa_supplicant: Successfully initialized wpa_supplicant
08-10 13:33:57.552  6876  6876 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-10 13:33:57.552  6876  6876 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-10 13:33:57.552  6876  6876 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-10 13:33:57.552  6876  6876 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-10 13:33:57.553  6876  6876 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-10 13:33:57.554  6876  6876 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-10 13:33:57.554  6876  6876 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-10 13:33:57.554  6876  6876 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-10 13:33:57.554  6876  6876 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-10 13:33:57.554  6876  6876 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-10 13:33:57.554  6876  6876 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-10 13:33:57.592  8129  8129 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-10 13:33:57.592  8129  8129 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-10 13:33:57.604  1031  1944 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8147 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-10 13:33:57.659  8129  8129 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-10 13:33:57.698  8129  8129 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-10 13:33:57.712  1031  1539 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
,08-10 13:33:57.713  1031  1539 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-10 13:33:57.714  1031  1539 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-10 13:33:57.715  1031  1539 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-10 13:33:57.716  1031  1539 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-10 13:33:57.717  1031  1539 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-10 13:33:57.718  1031  1539 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-10 13:33:57.719  1031  1539 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-10 13:33:57.720  1031  1539 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-10 13:33:57.720  1031  1539 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-10 13:33:57.721  1031  1539 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
,08-10 13:33:57.722  1031  1539 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-10 13:33:57.722  1031  1539 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-10 13:33:57.730  1031  8169 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-10 13:33:57.730  1031  8169 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-10 13:33:57.731  8129  8129 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-10 13:33:57.731  1031  8169 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-10 13:33:57.732  1031  8169 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-10 13:33:57.732  1031  8169 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-10 13:33:57.732  1031  8169 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,08-10 13:33:57.741  1031  1046 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8170 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-10 13:33:57.743  1031  1539 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-10 13:33:57.743  1031  1539 E WifiStateMachine: useWiFiOffloading() : false
08-10 13:33:57.743  1031  1539 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-10 13:33:57.746  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 13:33:57.746  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-10 13:33:57.747  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 13:33:57.747  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 13:33:57.747  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-10 13:33:57.747  1031  1539 D WifiNative-wlan0: doBoolean: SET update_config 1
08-10 13:33:57.748  1031  1539 D WifiNative-wlan0: SET update_config 1: returned true
08-10 13:33:57.748  1031  1539 D WifiConfigStore: Loading config and enabling all networks 
08-10 13:33:57.748  1031  1539 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-10 13:33:57.750  1031  1539 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-10 13:33:57.750  1945  1945 D WfdService: Waiting for WifiP2p enabling
08-10 13:33:57.751  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 13:33:57.758  1031  1539 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-10 13:33:57.758  1031  1031 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-10 13:33:57.759  1031  1543 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
,08-10 13:33:57.761  8147  8167 W FormManager: Network not available. Please check & try again.
08-10 13:33:57.762  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 13:33:57.762  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 13:33:57.762  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 13:33:57.762  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 13:33:57.762  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 13:33:57.762  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 13:33:57.762  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 13:33:57.762  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 13:33:57.765  6729  6729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-10 13:33:57.772  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 13:33:57.772  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 13:33:57.772  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 13:33:57.772  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 13:33:57.772  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 13:33:57.772  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 13:33:57.772  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 13:33:57.772  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-10 13:33:57.774  6729  6729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-10 13:33:57.780  1031  1539 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-10 13:33:57.781  1031  1539 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-10 13:33:57.782  1031  1539 D WifiStateMachine: enableVerboseLogging : level 2
08-10 13:33:57.782  1031  1539 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-10 13:33:57.784  1031  1539 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-10 13:33:57.784  1031  1539 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-10 13:33:57.784  1031  1539 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-10 13:33:57.784  1031  1539 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-10 13:33:57.785  1031  1539 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-10 13:33:57.785  1031  1539 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-10 13:33:57.785  1031  1539 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-10 13:33:57.785  1031  1539 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-10 13:33:57.785  1031  1539 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-10 13:33:57.785  1031  1539 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-10 13:33:57.786  1031  1539 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-10 13:33:57.786  1031  1539 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
,08-10 13:33:57.786  1031  1539 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-10 13:33:57.787  1031  1539 D WifiStateMachine: Setting OUI to DA-A1-19
,08-10 13:33:57.787  1031  1539 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-10 13:33:57.787  1031  1539 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-10 13:33:57.787  1031  1539 D WifiNative-HAL: Setting external_sim to 1
08-10 13:33:57.787  1031  1539 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-10 13:33:57.788  1031  1539 D WifiNative-wlan0: SET external_sim 1: returned true
08-10 13:33:57.788  1031  1539 I WifiNative-HAL: startHal
08-10 13:33:57.788  1031  1539 D wifi    : setting scan oui 0x9535c4c0
08-10 13:33:57.788  1945  1945 D WfdsService: Supplicant Connection state is changed : true
08-10 13:33:57.788  1945  2312 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-10 13:33:57.788  1945  2312 D WfdsService: Set the WFDS Monitor: true
08-10 13:33:57.788  1945  2312 D WfdsMonitor: WfdsMonitorThread create
08-10 13:33:57.788  1031  1539 D WifiStateMachine: Setting OUI to DA-A1-19
08-10 13:33:57.788  1031  1539 I WifiNative-HAL: startHal
08-10 13:33:57.788  1031  1539 D wifi    : setting scan oui 0x9535c4c0
08-10 13:33:57.788  1945  2312 D WfdsMonitor: WFDS Monitor is created and started
08-10 13:33:57.788  1945  2312 D WfdsService: WiFi: Supplicant connection re-established
08-10 13:33:57.788  1031  1539 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-10 13:33:57.789  1031  1539 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-10 13:33:57.789  1031  1539 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-10 13:33:57.789  8129  8129 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-10 13:33:57.790  1031  1539 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-10 13:33:57.790  1945  8188 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-10 13:33:57.790  1031  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-10 13:33:57.790  8129  8129 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-10 13:33:57.790  1945  8188 E CtrlSupplicant: Succeed to open control connection
08-10 13:33:57.790  1945  8188 E CtrlSupplicant: Succeed to open monitor connection
08-10 13:33:57.791  1945  8188 D WfdsMonitor: Supplicant connection established
08-10 13:33:57.791  1031  1539 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-10 13:33:57.791  1945  2312 D WfdsService: Connected to the supplicant for wfds
08-10 13:33:57.791  1031  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-10 13:33:57.791  7708  7708 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 13:33:57.791  8129  8129 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
,08-10 13:33:57.791  1031  1539 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-10 13:33:57.791  1031  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-10 13:33:57.791  8129  8129 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-10 13:33:57.792  1031  1539 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-10 13:33:57.792  1031  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-10 13:33:57.792  8129  8129 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-10 13:33:57.792  1031  1539 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-10 13:33:57.793  1031  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-10 13:33:57.793  8129  8129 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-10 13:33:57.793  1031  1539 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-10 13:33:57.793  8147  8168 V FormManager: Network unavailable.
08-10 13:33:57.793  1031  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-10 13:33:57.793  8129  8129 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-10 13:33:57.793  1031  1539 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-10 13:33:57.796  1031  1539 E WifiNative: : [385,000,259 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-10 13:33:57.796  1031  1539 D WifiNative-wlan0: doBoolean: RECONNECT
08-10 13:33:57.796  1031  1539 D WifiNative-wlan0: RECONNECT: returned true
08-10 13:33:57.796  1031  1539 D WifiNative-wlan0: doString: [STATUS]
08-10 13:33:57.797  1031  8169 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-10 13:33:57.797  1031  8169 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-10 13:33:57.797  1031  1539 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-10 13:33:57.797  1031  1539 D WifiNative-wlan0: doBoolean: SET ps 1
08-10 13:33:57.798  1031  1539 D WifiNative-wlan0: SET ps 1: returned true
08-10 13:33:57.798  1031  1538 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-10 13:33:57.799  1031  1031 D WifiScanningService: SCAN_AVAILABLE : 3
08-10 13:33:57.799  1031  1539 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-10 13:33:57.799  1031  1031 D RttService: SCAN_AVAILABLE : 3
08-10 13:33:57.799  1031  1559 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-10 13:33:57.799  1031  1559 I WifiNative-HAL: startHal
08-10 13:33:57.799  1031  1559 D wifi    : getting scan capabilities on interface[1] = 0x9535c4c0
08-10 13:33:57.799  1031  1559 D wifi    : failed to get capabilities : -3
08-10 13:33:57.799  1031  1559 E WifiScanningService: could not get scan capabilities
08-10 13:33:57.799  1031  1539 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-10 13:33:57.800  1031  1539 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-10 13:33:57.800   306   896 D CommandListener: Setting iface cfg
08-10 13:33:57.800   306   896 D CommandListener: Trying to bring up p2p0
08-10 13:33:57.800  1031  1539 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-10 13:33:57.800  1031  1560 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-10 13:33:57.801  1031  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=385007  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-10 13:33:57.801  1031  1538 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-10 13:33:57.801  1031  1538 D LGWifiP2pService: P2pEnablingState
08-10 13:33:57.801  1031  1538 D LGWifiP2pService: P2pEnablingState{ when=0 wh,at=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-10 13:33:57.801  1031  1538 D LGWifiP2pService: P2p socket connection successful
08-10 13:33:57.801  1031  1538 D LGWifiP2pService: P2pEnabledState
,08-10 13:33:57.802  1031  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=385008  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-10 13:33:57.802  1031  1538 D LGWifiP2pService: sending p2p connection changed broadcast
08-10 13:33:57.802  1031  1538 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-10 13:33:57.803  1031  1539 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-10 13:33:57.803  1031  1539 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-10 13:33:57.803  1031  1539 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-10 13:33:57.803  1031  1539 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
,08-10 13:33:57.803  8129  8129 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-10 13:33:57.804  1031  1539 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-10 13:33:57.804  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 13:33:57.804  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-10 13:33:57.804  1031  1539 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-10 13:33:57.805  1031  1539 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-10 13:33:57.805  1031  1539 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-10 13:33:57.805  8129  8129 E wpa_supplicant: disconnect_rssi_lvl: -100
08-10 13:33:57.805  1031  1539 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-10 13:33:57.805  1031  1539 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-10 13:33:57.806  1031  1538 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-10 13:33:57.806  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 13:33:57.806  1031  1539 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-10 13:33:57.806  1031  1538 D WifiNative-p2p0: doBoolean: SET device_name G3
08-10 13:33:57.806  1031  1539 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-10 13:33:57.806  1031  1538 D WifiNative-p2p0: SET device_name G3: returned true
08-10 13:33:57.806  1031  1538 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-10 13:33:57.806  1031  1538 D LGWifiP2pService: before postfix = G3
08-10 13:33:57.806  1031  1538 D WifiServerServiceExt: postfix byte check : 2
08-10 13:33:57.806  1031  1538 D LGWifiP2pService: after postfix = G3
08-10 13:33:57.807  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 13:33:57.807  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 13:33:57.807  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-10 13:33:57.807  1031  1538 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-10 13:33:57.807  1031  1538 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-10 13:33:57.807  1031  1538 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-10 13:33:57.808  1945  1945 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-10 13:33:57.808  1945  1945 D WfdsService: WifiP2pState is changed : true
08-10 13:33:57.808  1945  1945 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-10 13:33:57.808  1945  1945 D WfdsService: isConnected: false
08-10 13:33:57.808  1945  2312 D WfdsService: Receive the WFDS_ENABLE Method
08-10 13:33:57.808  1945  2312 D WfdsService: Set the WFDS Monitor: true
08-10 13:33:57.808  1945  2312 D WfdsService: Connected to the supplicant for wfds
08-10 13:33:57.808  1945  2312 D WfdsJNI : doCommand: WFDS_SET TRUE
08-10 13:33:57.808  8129  8129 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-10 13:33:57.809  1945  2312 D WfdsService: selectPreferredScanChannel [36]
08-10 13:33:57.809  1945  2312 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-10 13:33:57.809  1031  1538 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-10 13:33:57.809  1031  1538 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-10 13:33:57.810  8129  8129 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-10 13:33:57.810  8147  8168 V FormManager: Network unavailable.
08-10 13:33:57.810  8129  8129 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=,USER type=COUNTRY alpha2=CZ
08-10 13:33:57.810  1031  8169 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-10 13:33:57.810  1031  8169 E WifiMonitor: WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-10 13:33:57.810  1031  8169 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-10 13:33:57.810  1031  8169 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-10 13:33:57.811  8129  8129 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-10 13:33:57.811  8129  8129 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 13:33:57.811  1031  1539 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-10 13:33:57.811  8129  8129 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 13:33:57.811  1031  1539 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-10 13:33:57.812  1031  8169 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-10 13:33:57.812  1031  8169 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 13:33:57.812  1031  8169 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 13:33:57.812  1031  8169 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 13:33:57.812  1945  8188 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-10 13:33:57.812  1031  8169 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-10 13:33:57.812  1945  8188 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-10 13:33:57.812  1031  8169 E WifiMonitor: WifiMonitor:p2p0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 13:33:57.812  1031  8169 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 13:33:57.812  1031  8169 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 13:33:57.813  1031  1538 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-10 13:33:57.813  1031  1538 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-10 13:33:57.813  1031  1539 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-10 13:33:57.813  1031  1538 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-10 13:33:57.813  1031  1538 D WifiNative-HAL: p2pGetDeviceAddress
08-10 13:33:57.813  1031  1538 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-10 13:33:57.813  1031  1539 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-10 13:33:57.813  1031  1539 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-10 13:33:57.813  8129  8129 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-10 13:33:57.813  8129  8129 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-10 13:33:57.813  1031  8169 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-10 13:33:57.813  1031  8169 E WifiMonitor: WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-10 13:33:57.814  1031  8169 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-10 13:33:57.814  1031  8169 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-10 13:33:57.814  1031  1538 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-10 13:33:57.814  1031  1539 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-10 13:33:57.814  1031  1538 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-10 13:33:57.814  1031  1539 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-10 13:33:57.815  1945  1945 I WfdStateTracker: handleP2pThisDeviceChanged
08-10 13:33:57.815  1945  1945 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-10 13:33:57.815  1945  1945 D WfdsService: Update P2p Interface State: 3
08-10 13:33:57.815  1031  1538 D WifiNative-p2p0: P2P_FLUSH: returned true
08-10 13:33:57.815  1031  1538 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-10 13:33:57.815  1031  1539 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-10 13:33:57.815  1031  1539 D WifiNative-wlan0: doBoolean: SCAN
08-10 13:33:57.816  1031  1538 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-10 13:33:57.816  1031  1538 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-10 13:33:57.816  1031  1539 D WifiNative-wlan0: SCAN: returned false
08-10 13:33:57.816  1031  1538 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-10 13:33:57.816  1031  1538 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-10 13:33:57.817  1031  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=385023  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-10 13:33:57.817  1031  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=385024  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-10 13:33:57.821  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 13:33:57.821  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 13:33:57.821  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-10 13:33:57.822  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-10 13:33:57.822  1031  1031 D WifiServerServiceExt: setSupplicantStateSCANNING
08-10 13:33:57.822  1031  1538 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-10 13:33:57.822  1031  1538 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-10 13:33:57.822  1031  1538 D LGWifiP2pService: InactiveState
08-10 13:33:57.822  1031  1538 D LGWifiP2pService: InactiveState{ when=-11ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-10 13:33:57.822  1031  1538 D LGWifiP2pService: P2pEnabledState{ when=-11ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-10 13:33:57.822  1031  1538 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-10 13:33:57.823  8129  8129 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-10 13:33:57.823  8129  8129 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-10 13:33:57.824  1031  1539 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-10 13:33:57.824  8129  8129 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-10 13:33:57.824  8129  8129 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 13:33:57.824  1031  1539 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-10 13:33:57.824  8129  8129 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,08-10 13:33:57.825  1031  1539 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-10 13:33:57.825  1945  8188 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-10 13:33:57.825  1945  8188 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-10 13:33:57.825  1945  8188 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-10 13:33:57.825  1031  1539 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-10 13:33:57.825  1031  1538 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-10 13:33:57.825  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 13:33:57.825  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-10 13:33:57.825  1031  1538 D LGWifiP2pService: InactiveState{ when=-9ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-10 13:33:57.825  1031  1538 D LGWifiP2pService: P2pEnabledState{ when=-9ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-10 13:33:57.825  1031  1538 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-10 13:33:57.825  1031  1538 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-10 13:33:57.826  1031  1538 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-10 13:33:57.826  1031  1538 D LGWifiP2pService: InactiveState{ when=-4ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-10 13:33:57.826  1031  1538 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-10 13:33:57.826  1031  8169 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-10 13:33:57.826  1031  1538 D LGWifiP2pService: DefaultState{ when=-4ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-10 13:33:57.826  1031  8169 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-10 13:33:57.826  1031  8169 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-10 13:33:57.826  1031  8169 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-10 13:33:57.826  1031  1538 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-10 13:33:57.826  1031  1538 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-10 13:33:57.826  1031  8169 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-10 13:33:57.826  1031  8169 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 13:33:57.826  1031  1538 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-10 13:33:57.826  1031  8169 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 13:33:57.826  1031  8169 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 13:33:57.826  1031  8169 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,08-10 13:33:57.826  1031  8169 E WifiMonitor: WifiMonitor:p2p0 cnt=53 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 13:33:57.826  1031  8169 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 13:33:57.826  1031  8169 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 13:33:57.826  1945  2312 W WfdsService: DefaultState - msg [9441285] is not handled
08-10 13:33:57.827  1031  1539 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
,08-10 13:33:57.827  1031  1538 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-10 13:33:57.827  1031  1538 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-10 13:33:57.827  1031  1538 D LGWifiP2pService: DefaultState{ when=-2ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-10 13:33:57.827  1031  1031 E WifiServerServiceExt: No p2p device connected
08-10 13:33:57.827  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 13:33:57.828  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-10 13:33:57.828  1031  1031 D WifiServerServiceExt: setSupplicantStateSCANNING
08-10 13:33:57.848  8170  8170 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-10 13:33:57.851  6876  6876 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-10 13:33:57.855  6876  6876 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-10 13:33:57.856  1031  1962 I ActivityManager: Killing 7165:com.lge.drmservice/u0a62 (adj 15): empty #17
08-10 13:33:57.904  1031  1046 W libprocessgroup: failed to open /acct/uid_10062/pid_7165/cgroup.procs: No such file or directory
,08-10 13:33:57.924  8170  8170 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-10 13:33:57.932  6876  6876 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-10 13:33:57.934  8147  8192 W FormManager: Network not available. Please check & try again.
,08-10 13:33:57.941  8147  8193 V FormManager: Network unavailable.
08-10 13:33:57.943  6876  6876 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 13:33:57.973  8147  8193 V FormManager: Network unavailable.
,08-10 13:33:57.978  4325  4325 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-10 13:33:57.978  4325  4325 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-10 13:33:57.980  4325  4325 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-10 13:33:57.982  4325  4325 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-10 13:33:57.991  4325  8194 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-10 13:33:57.998  4325  8195 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
,08-10 13:33:57.998  4325  8195 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-10 13:33:58.066  1031  2016 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8196 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-10 13:33:58.150  8196  8196 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-10 13:33:58.176  8196  8196 D PluginManager: init()
,08-10 13:33:58.375  8129  8129 E wpa_supplicant: USIM:  scard_init function
08-10 13:33:58.376  8129  8129 I wpa_supplicant: Trying to associate with SSID 'NG700'
,08-10 13:33:58.383  1031  8169 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-10 13:33:58.383  1031  8169 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-10 13:33:58.383  1031  8169 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-10 13:33:58.383  1031  8169 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: WPS-AP-AVAILABLE 
08-10 13:33:58.383  1031  8169 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-10 13:33:58.383  1031  8169 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-10 13:33:58.383  1031  8169 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-10 13:33:58.384  1031  1539 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-10 13:33:58.384  1031  1539 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-10 13:33:58.384  1031  1539 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-10 13:33:58.385  1031  1539 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-10 13:33:58.385  1031  1539 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-10 13:33:58.392  1031  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=385599  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-10 13:33:58.399  1031  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=385606  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-10 13:33:58.402  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 13:33:58.402  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 13:33:58.402  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-10 13:33:58.404  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 13:33:58.404  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-10 13:33:58.407  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-10 13:33:58.407  1031  1031 D WifiServerServiceExt: setSupplicantStateASSOCIATING
,08-10 13:33:58.411  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 13:33:58.490  1031  1096 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-10 13:33:58.492  8129  8129 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-10 13:33:58.493  1031  8169 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-10 13:33:58.493  1031  8169 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-10 13:33:58.493  1031  8169 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-10 13:33:58.493  1031  8169 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-10 13:33:58.494  1031  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=385700  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-10 13:33:58.494  1031  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=385700  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-10 13:33:58.495  1031  1539 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=385701
08-10 13:33:58.495  1031  1539 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=385702
08-10 13:33:58.496  1031  1539 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=385702
08-10 13:33:58.496  1031  1539 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=385702
08-10 13:33:58.496  1031  1539 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=385702
08-10 13:33:58.497  1031  8169 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-10 13:33:58.497  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-10 13:33:58.497  1031  1031 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-10 13:33:58.497  1031  8169 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-10 13:33:58.498  1031  1539 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
08-10 13:33:58.498  1031  1539 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-10 13:33:58.498  1031  1539 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-10 13:33:58.498  1031  1539 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-10 13:33:58.499  1031  1539 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-10 13:33:58.499  1031  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=385705  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-10 13:33:58.501  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 13:33:58.501  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 13:33:58.502  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-10 13:33:58.503  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 13:33:58.503  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-10 13:33:58.506  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 13:33:58.506  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 13:33:58.506  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
,08-10 13:33:58.507  1031  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=385713  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-10 13:33:58.508  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-10 13:33:58.508  1031  1031 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-10 13:33:58.510  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 13:33:58.511  1031  8169 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-10 13:33:58.511  1031  8169 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-10 13:33:58.512  8129  8129 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-10 13:33:58.512  8129  8129 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-10 13:33:58.514  1031  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=385720  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-10 13:33:58.515  1031  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=385721  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-10 13:33:58.515  1031  8169 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-10 13:33:58.515  1031  8169 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-10 13:33:58.515  1031  8169 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-10 13:33:58.515  1031  8169 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
,08-10 13:33:58.515  1031  8169 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-10 13:33:58.515  1031  8169 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-10 13:33:58.515  1031  8169 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-10 13:33:58.515  1031  8169 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-10 13:33:58.516  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-10 13:33:58.516  1031  1031 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-10 13:33:58.517  1031  1539 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=385723
08-10 13:33:58.517  1031  1539 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=385723
08-10 13:33:58.517  1031  1539 D WifiNative-wlan0: doString: [STATUS]
08-10 13:33:58.518  1031  8169 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-10 13:33:58.518  1031  8169 E WifiMonitor: WifiMonitor:wlan0 cnt=64 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-10 13:33:58.518  1031  1539 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-10 13:33:58.519  1031  1539 I WifiServiceExtension: setVHTCapabilityType  : false
08-10 13:33:58.521  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 13:33:58.521  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-10 13:33:58.525  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-10 13:33:58.527  1031  1539 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-10 13:33:58.527  1031  1539 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-10 13:33:58.531  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 13:33:58.531  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 13:33:58.531  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-10 13:33:58.531  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 13:33:58.531  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-10 13:33:58.533  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 13:33:58.534  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 13:33:58.534  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 13:33:58.534  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-10 13:33:58.535  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 13:33:58.536  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-10 13:33:58.536  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 13:33:58.537  1031  1539 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-10 13:33:58.537  1031  1539 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-10 13:33:58.537  1031  1539 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-10 13:33:58.537  1031  1539 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-10 13:33:58.537  1031  1539 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-10 13:33:58.538  1031  1545 D ConnectivityService: Got NetworkAgent Messenger
08-10 13:33:58.538  1031  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-10 13:33:58.538  1031  1545 D ConnectivityService: NetworkAgent connected
08-10 13:33:58.540  1031  1539 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-10 13:33:58.540  1031  1539 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-10 13:33:58.540  1031  1539 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-10 13:33:58.541  1031  1539 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-10 13:33:58.541  1031  1539 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,08-10 13:33:58.544  1031  1539 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-10 13:33:58.546   306   896 D CommandListener: Setting iface cfg
08-10 13:33:58.548  1031  1539 E WifiStateMachine: Start Dhcp Watchdog 3
08-10 13:33:58.548  1031  8232 D DhcpStateMachine: StoppedState
08-10 13:33:58.549  1031  8232 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-10 13:33:58.549  1031  8232 D DhcpStateMachine: WaitBeforeStartState
08-10 13:33:58.549  1031  1539 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=385755  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-10 13:33:58.549  1031  1539 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=385755  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-10 13:33:58.550  1031  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=385756  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-10 13:33:58.550  1031  1539 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=385756  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-10 13:33:58.551  1031  1539 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=385757  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-10 13:33:58.551  1031  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=385757  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-10 13:33:58.552  1031  1539 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:21183] from screen [on:0 period:1950023320] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-10 13:33:58.553  1031  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1950023321] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-10 13:33:58.553  1031  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-10 13:33:58.555  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 13:33:58.556  1031  1545 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
08-10 13:33:58.556  1031  1539 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 13:33:58.557  1031  1539 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 13:33:58.557  1031  1539 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 13:33:58.557  1031  1539 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 13:33:58.558  1031  1539 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 13:33:58.558  1031  1539 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 13:33:58.558  1031  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-10 13:33:58.558  1031  1539 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=185,0,0
08-10 13:33:58.559  1031  1539 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=185,0,0
08-10 13:33:58.559  1031  1539 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-10 13:33:58.559  8129  8129 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-10 13:33:58.559  1031  1539 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-10 13:33:58.559  1031  1539 D WifiNative-wlan0: doBoolean: SET ps 0
08-10 13:33:58.560  1031  1539 D WifiNative-wlan0: SET ps 0: returned true
08-10 13:33:58.560  1031  1539 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-10 13:33:58.560  8129  8129 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-10 13:33:58.560  1031  1539 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-10 13:33:58.560  1031  1538 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2e4cebca target=com.android.internal.util.StateMachine$SmHandler }
08-10 13:33:58.560  1031  1538 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2e4cebca target=com.android.internal.util.StateMachine$SmHandler }
08-10 13:33:58.560  1031  8232 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-10 13:33:58.560  1031  8232 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-10 13:33:58.561  1031  1539 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-10 13:33:58.561  1031  1539 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-10 13:33:58.561  1031  1539 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-10 13:33:58.562   306   896 D CommandListener: Setting iface cfg
08-10 13:33:58.562   306   896 D CommandListener: Trying to bring up wlan0
08-10 13:33:58.563  1031  1539 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-10 13:33:58.564  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-10 13:33:58.564  1031  1031 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-10 13:33:58.564  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-10 13:33:58.564  1031  1031 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-10 13:33:58.565  1031  1539 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 13:33:58.565  1031  1539 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 13:33:58.565  1031  1539 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 13:33:58.566  1031  1539 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 13:33:58.566  1031  1539 E WifiStateMachine:  SupplicantStart,edState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 13:33:58.567  1031  1539 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,08-10 13:33:58.570  1031  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-10 13:33:58.570  1031  1539 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-10 13:33:58.571  1031  1539 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-10 13:33:58.571  1031  1539 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-10 13:33:58.571  8129  8129 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-10 13:33:58.571  1031  1538 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-10 13:33:58.571  1031  1538 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-10 13:33:58.571  1031  1539 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-10 13:33:58.571  1031  1539 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-10 13:33:58.571  8129  8129 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-10 13:33:58.571  1031  1539 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-10 13:33:58.571  1031  1539 D WifiNative-wlan0: doBoolean: SET ps 1
,08-10 13:33:58.587  1031  1539 D WifiNative-wlan0: SET ps 1: returned true
08-10 13:33:58.587  1031  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-10 13:33:58.588  1031  1539 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-10 13:33:58.588  1031  1539 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-10 13:33:58.588  1031  1539 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-10 13:33:58.588  1031  1545 D ConnectivityService: ignoring duplicate network state non-change
,08-10 13:33:58.591  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 13:33:58.591  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 13:33:58.591  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-10 13:33:58.591  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 13:33:58.591  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-10 13:33:58.592  1031  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-10 13:33:58.593  1031  1545 D ConnectivityService: Adding iface wlan0 to network 102
08-10 13:33:58.593  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 13:33:58.597  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 13:33:58.597  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 13:33:58.597  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-10 13:33:58.599  1031  1539 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-10 13:33:58.601  1031  1031 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,08-10 13:33:58.605  1945  1945 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-10 13:33:58.607  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 13:33:58.607  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 13:33:58.607  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-10 13:33:58.609  1031  1031 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-10 13:33:58.614  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 13:33:58.614  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-10 13:33:58.616  1031  1545 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-10 13:33:58.616  1031  1545 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-10 13:33:58.617  1031  1545 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
08-10 13:33:58.617   306   896 E Netd    : netlink response contains error (File exists)
08-10 13:33:58.617  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 13:33:58.617  1031  1545 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-10 13:33:58.617  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 13:33:58.617  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,08-10 13:33:58.618  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 13:33:58.618  1031  1545 D ConnectivityService: addLocalRoutetoDefaultNetwork
,08-10 13:33:58.618  1031  1545 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
08-10 13:33:58.618  1031  1545 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
08-10 13:33:58.619  1031  1545 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-10 13:33:58.619  1031  1545 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-10 13:33:58.619  1031  1545 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-10 13:33:58.619  1031  1545 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-10 13:33:58.619  1031  1545 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-10 13:33:58.619  1031  1545 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-10 13:33:58.619  1031  8231 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-10 13:33:58.619  1031  1545 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-10 13:33:58.619  1031  8231 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-10 13:33:58.619  1031  1545 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 13:33:58.619  1031  8231 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-10 13:33:58.619  1031  1545 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-10 13:33:58.619  1031  1545 D ConnectivityService: currentScore = 0, newScore = 20
08-10 13:33:58.619  1031  1545 D ConnectivityService:    accepting network in place of null
08-10 13:33:58.619  1031  8231 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-10 13:33:58.619  1031  1545 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 13:33:58.620  1031  1539 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 13:33:58.620  1031  1539 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-10 13:33:58.620  1031  1545 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-10 13:33:58.620  1031  1545 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-10 13:33:58.621  1031  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-10 13:33:58.621  1856  1856 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=,-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 13:33:58.621  1856  1856 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-10 13:33:58.623   306  8236 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-10 13:33:58.623  1031  1545 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-10 13:33:58.623  1031  1545 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-10 13:33:58.624  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 13:33:58.624  1031  1545 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-10 13:33:58.624  1605  1605 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-10 13:33:58.624  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 13:33:58.625  1031  1031 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-10 13:33:58.626  1031  1031 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-10 13:33:58.627  1031  1031 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-10 13:33:58.627  1031  1031 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-10 13:33:58.627  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 13:33:58.627  1605  1605 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-10 13:33:58.628  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 13:33:58.628  1031  1545 D ConnectivityService: validation of new default Network = false
08-10 13:33:58.628  1031  1545 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
,08-10 13:33:58.628  1031  1545 D DSQN    : enableDataServiceNotify 
08-10 13:33:58.628  1031  1545 D DSQN    : start dsqn bin
,08-10 13:33:58.631  1031  1545 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-10 13:33:58.631  1031  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 13:33:58.631  1031  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-10 13:33:58.632  1031  1545 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-10 13:33:58.622  8237  8237 W dsqn    : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-10 13:33:58.622  8237  8237 W dsqn    : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-10 13:33:58.638  1605  2072 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-10 13:33:58.644  1031  1537 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,08-10 13:33:58.649  8237  8237 E DSQN    : DSQN ssw
,08-10 13:33:58.658  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-10 13:33:58.659  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 13:33:58.660  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 13:33:58.681   306  8236 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-10 13:33:58.716   306  8236 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-10 13:33:58.746  8196  8196 W ExternalStrings: load override strings
08-10 13:33:58.746  8196  8196 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
08-10 13:33:58.746  8196  8196 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
08-10 13:33:58.746  8196  8196 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
08-10 13:33:58.746  8196  8196 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
08-10 13:33:58.746  8196  8196 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
08-10 13:33:58.746  8196  8196 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
08-10 13:33:58.746  8196  8196 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
08-10 13:33:58.746  8196  8196 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-10 13:33:58.746  8196  8196 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-10 13:33:58.746  8196  8196 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-10 13:33:58.746  8196  8196 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-10 13:33:58.746  8196  8196 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 13:33:58.746  8196  8196 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
08-10 13:33:58.746  8196  8196 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-10 13:33:58.746  8196  8196 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 13:33:58.746  8196  8196 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-10 13:33:58.746  8196  8196 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-10 13:33:58.746  8196  8196 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-10 13:33:58.749  8196  8196 D StatusProvider: onCreate
,08-10 13:33:58.754   306   895 D LGDataListener: argv[0]=dsqncommand
08-10 13:33:58.754   306   895 D LGDataListener: argv[1]=wlan0
08-10 13:33:58.754   306   895 D LGDataListener: argv[2]=1
08-10 13:33:58.754   306   895 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-10 13:33:58.755  1031  1094 D DSQN    : DSQM DsqnNotification wlan0  1
08-10 13:33:58.755  1031  1094 D DSQN    : start to monitor internet connection
08-10 13:33:58.764  1031  8232 D DhcpStateMachine: DHCPV4 request on wlan0
08-10 13:33:58.766  1031  8232 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-10 13:33:58.766  1031  8232 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
,08-10 13:33:58.752  8243  8243 W dhcpcd  : type=1400 audit(0.0:195): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-10 13:33:58.762  8243  8243 W dhcpcd  : type=1400 audit(0.0:196): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-10 13:33:58.787  1031  8231 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 10 Aug 2016 11:33:58 GMT], X-Android-Received-Millis=[1470828838786], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1470828838753]}
08-10 13:33:58.787  1031  8231 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-10 13:33:58.787  1031  8231 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-10 13:33:58.788  1031  1545 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
08-10 13:33:58.788  1031  1545 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-10 13:33:58.788  1031  1545 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-10 13:33:58.788  1031  1545 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-10 13:33:58.788  1031  1545 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-10 13:33:58.788  1031  1545 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-10 13:33:58.788  1031  1545 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-10 13:33:58.789  1031  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 13:33:58.789  1031  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-10 13:33:58.789  1031  1545 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-10 13:33:58.790  1605  2072 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-10 13:33:58.792  1031  1545 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 13:33:58.792  1031  1539 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 13:33:58.792  1031  1539 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-10 13:33:58.792  8243  8243 I dhcpcd  : version 5.5.6 starting
08-10 13:33:58.793  1031  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-10 13:33:58.793  1856  1856 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 13:33:58.793  1856  1856 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-10 13:33:58.794  8243  8243 E dhcpcd  : get_duid: m
08-10 13:33:58.795  8243  8243 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-10 13:33:58.795  8243  8243 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-10 13:33:58.824  8196  8196 V Signer  : override build config not found
08-10 13:33:58.824  8196  8196 D Signer  : value of property debug is false
08-10 13:33:58.826  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-10 13:33:58.829  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 13:33:58.831  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 13:33:58.840  6729  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 13:33:58.840  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 13:33:58.840  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 13:33:58.840  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 13:33:58.840  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 13:33:58.840  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 13:33:58.840  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 13:33:58.840  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-10 13:33:58.841  6729  6799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-10 13:33:58.842  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 13:33:58.842  6729  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@df41320 removed from the list
08-10 13:33:58.842  6729  6799 D io.jxcore.node.ConnectivityMonitor: stop
08-10 13:33:58.842  6729  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 13:33:58.842  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 13:33:58.847  6729  8250 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
08-10 13:33:58.847  6729  8250 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-10 13:33:58.847  8243  8243 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-10 13:33:58.848  8243  8243 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-10 13:33:58.848  8243  8243 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-10 13:33:58.848  8243  8243 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
08-10 13:33:58.848  8243  8243 D dhcpcd  : wlan0: sending REQUEST (xid 0x556bde35), next in 4.75 seconds
08-10 13:33:58.851  8196  8196 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
08-10 13:33:58.851  8196  8196 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
08-10 13:33:58.851  8196  8196 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
08-10 13:33:58.851  8196  8196 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
08-10 13:33:58.851  8196  8196 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
08-10 13:33:58.851  8196  8196 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
,08-10 13:33:58.851  8196  8196 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
,08-10 13:33:58.852  8196  8196 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
,08-10 13:33:58.852  8196  8196 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
08-10 13:33:58.852  8196  8196 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
08-10 13:33:58.852  8196  8196 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
,08-10 13:33:58.852  8196  8196 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
08-10 13:33:58.853  8196  8196 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
08-10 13:33:58.860  8196  8196 V LGMDMManager: Create singleton instance
08-10 13:33:58.894  8243  8243 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,08-10 13:33:58.895  8196  8196 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
,08-10 13:33:58.909  8243  8243 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
,08-10 13:33:58.909  8243  8243 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
08-10 13:33:58.909  8243  8243 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
,08-10 13:33:58.910  8243  8243 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-10 13:33:58.910  8243  8243 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,08-10 13:33:58.911  8243  8243 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-10 13:33:58.911  8243  8243 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-10 13:33:58.911  8243  8243 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-10 13:33:58.941  8196  8196 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-10 13:33:58.949  6876  6876 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-10 13:33:58.954  8196  8255 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-10 13:33:58.954  6876  6876 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 13:33:58.970  7904  7904 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-10 13:33:58.973  7904  7904 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-10 13:33:58.981  7904  7904 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-10 13:33:59.025  1031  2006 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8267 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-10 13:33:59.026  1031  2006 I ActivityManager: Killing 7182:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
08-10 13:33:59.085  8196  8254 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-10 13:33:59.134  1031  1774 W libprocessgroup: failed to open /acct/uid_10085/pid_7182/cgroup.procs: No such file or directory
,08-10 13:33:59.171  1031  8232 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-10 13:33:59.173  1031  8232 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-10 13:33:59.174  1031  8232 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-10 13:33:59.174  1031  8232 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
08-10 13:33:59.174  1031  8232 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-10 13:33:59.174  1031  8232 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-10 13:33:59.174  1031  8232 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-10 13:33:59.174  1031  8232 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-10 13:33:59.174  1031  8232 D DhcpStateMachine: RunningState
08-10 13:33:59.226  8267  8267 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-10 13:33:59.227  8267  8267 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-10 13:33:59.237  8267  8267 V [BNRBootReceiver]: Boot Receiver Return
08-10 13:33:59.238  8267  8267 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-10 13:33:59.243  8196  8196 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 13:33:59.243  8196  8255 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-10 13:33:59.255  6876  6876 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-10 13:33:59.264  6876  6876 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 13:33:59.275  7904  7904 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-10 13:33:59.276  7904  7904 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-10 13:33:59.279  7904  7904 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-10 13:33:59.283  6876  6876 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-10 13:33:59.287  6876  6876 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-10 13:33:59.295  8196  8255 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-10 13:33:59.296  8196  8196 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 13:33:59.303  6876  6876 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-10 13:33:59.312  6876  6876 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-10 13:33:59.322  7904  7904 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-10 13:33:59.323  7904  7904 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-10 13:33:59.323  7904  7904 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-10 13:33:59.332  6876  6876 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-10 13:33:59.332  6876  6876 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-10 13:33:59.332  6876  6876 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-10 13:33:59.332  6876  6876 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-10 13:33:59.335  6876  6876 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-10 13:33:59.336  6876  6876 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-10 13:33:59.336  6876  6876 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-10 13:33:59.336  6876  6876 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-10 13:33:59.336  6876  6876 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-10 13:33:59.336  6876  6876 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-10 13:33:59.336  6876  6876 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-10 13:33:59.336  6876  6876 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-10 13:33:59.339  8196  8196 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 13:33:59.339  8196  8255 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-10 13:33:59.345  6876  6876 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-10 13:33:59.360  8196  8254 D LgDataFeature: LgDataFeature() Constructor: none
,08-10 13:33:59.360  8196  8254 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-10 13:33:59.364  6876  6876 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 13:33:59.371  7904  7904 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-10 13:33:59.372  7904  7904 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-10 13:33:59.372  7904  7904 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-10 13:33:59.376  8196  8196 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 13:33:59.376  8196  8255 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-10 13:33:59.387  6876  6876 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-10 13:33:59.393  6876  6876 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 13:33:59.400  7904  7904 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-10 13:33:59.400  7904  7904 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-10 13:33:59.400  7904  7904 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-10 13:33:59.405  8196  8196 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 13:33:59.406  8196  8255 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-10 13:33:59.411  6876  6876 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-10 13:33:59.417  6876  6876 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 13:33:59.424  7904  7904 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-10 13:33:59.425  7904  7904 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-10 13:33:59.425  7904  7904 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-10 13:33:59.430  8196  8196 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 13:33:59.430  8196  8255 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-10 13:33:59.441  6876  6876 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-10 13:33:59.451  6876  6876 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 13:33:59.458  7904  7904 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-10 13:33:59.459  7904  7904 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-10 13:33:59.459  7904  7904 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-10 13:33:59.483  8196  8196 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 13:33:59.484  8196  8255 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-10 13:33:59.503  6876  6876 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-10 13:33:59.510  6876  6876 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 13:33:59.522  7904  7904 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-10 13:33:59.522  7904  7904 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-10 13:33:59.528  8196  8254 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
08-10 13:33:59.536  7904  7904 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-10 13:33:59.542  8196  8196 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 13:33:59.542  8196  8255 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-10 13:33:59.555  8196  8254 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
,08-10 13:33:59.559  6876  6876 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-10 13:33:59.566  6876  6876 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 13:33:59.570  8196  8254 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
08-10 13:33:59.571  8196  8254 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-10 13:33:59.572  8196  8254 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-10 13:33:59.573  8196  8254 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
,08-10 13:33:59.574  8196  8254 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
08-10 13:33:59.576  7904  7904 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-10 13:33:59.577  7904  7904 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-10 13:33:59.579  7904  7904 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-10 13:33:59.583  8196  8254 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
08-10 13:33:59.586  8196  8254 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
08-10 13:33:59.586  8196  8196 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 13:33:59.587  8196  8255 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-10 13:33:59.591  8170  8170 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-10 13:33:59.597  8170  8170 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-10 13:33:59.606  6876  6876 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-10 13:33:59.616  6876  6876 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-10 13:33:59.633  7904  7904 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-10 13:33:59.633  7904  7904 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-10 13:33:59.635  7904  7904 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-10 13:33:59.636  7904  7904 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-10 13:33:59.636  7904  7904 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-10 13:33:59.645  8196  8196 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 13:33:59.645  8196  8255 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-10 13:33:59.649  8170  8170 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-10 13:33:59.650  8170  8170 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,08-10 13:33:59.665  6876  6876 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-10 13:33:59.673  6876  6876 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 13:33:59.683  7904  7904 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-10 13:33:59.684  7904  7904 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-10 13:33:59.684  7904  7904 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-10 13:33:59.685  7904  7904 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-10 13:33:59.686  7904  7904 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-10 13:33:59.693  8196  8196 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-10 13:33:59.696  8196  8196 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
,08-10 13:33:59.699  8196  8196 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-10 13:33:59.702  8196  8196 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-10 13:33:59.704  8196  8196 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-10 13:33:59.706  8196  8196 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-10 13:33:59.708  8196  8196 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-10 13:33:59.710  8196  8196 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-10 13:33:59.713  8196  8196 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
,08-10 13:33:59.715  8196  8196 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-10 13:33:59.718  8196  8196 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-10 13:33:59.719  1031  1772 I ActivityManager: Killing 7201:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
08-10 13:33:59.816  1031  1539 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-10 13:33:59.818  1031  1539 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-10 13:33:59.819  1031  1539 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-10 13:33:59.821  1031  1539 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-10 13:33:59.822  1031  1539 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-10 13:33:59.824  1031  1539 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-10 13:33:59.826  1031  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
08-10 13:33:59.826  1031  1545 D ConnectivityService: identical MTU - not setting
08-10 13:33:59.826  1031  1545 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-10 13:33:59.827  1031  1545 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-10 13:33:59.827  1031  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 13:33:59.827  1031  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-10 13:33:59.829  1031  1545 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-10 13:33:59.831  1605  2072 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-10 13:33:59.844  1031  2006 W libprocessgroup: failed to open /acct/uid_10093/pid_7201/cgroup.procs: No such file or directory
,08-10 13:33:59.977  1031  1092 W ProcessCpuTracker: Skipping unknown process pid 8223
,08-10 13:33:59.978  1031  1092 W ProcessCpuTracker: Skipping unknown process pid 8226
08-10 13:34:00.001  1031  1377 D PowerManagerServiceEx: acquireWakeLockInternal: lock=942226032, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1031
,08-10 13:34:00.013  7904  7904 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
08-10 13:34:00.014  7904  7904 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:4955
,08-10 13:34:00.060  2586  2586 D [Concierge]Service: onStartCommand(). Type : 9
,08-10 13:34:00.070  1605  1605 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-10 13:34:00.070  1605  1605 I KeyguardUpdateMonitor: called onTimeUpdated()
08-10 13:34:00.070  1605  1605 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-10 13:34:00.071  1605  1605 I [SystemUI]Clock: called onTimeUpdated()
08-10 13:34:00.074  1605  1605 I LgeClockWidgetControlView: called onTimeUpdated()
08-10 13:34:00.074  1605  1605 I [SystemUI]DateView: called onTimeUpdated()
08-10 13:34:00.076  1605  1605 I [SystemUI]DateView: called onTimeUpdated()
08-10 13:34:00.078  1605  1605 D KeyguardUpdateMonitor: handleTimeUpdate
08-10 13:34:00.127  1031  1031 D PowerManagerServiceEx: releaseWakeLockInternal: lock=942226032 [*alarm*], flags=0x0
,08-10 13:34:01.561  1031  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=92.5, 0.0, 0.0  rx=85.5 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1950026328] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-10 13:34:01.571  1031  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=92.5, 0.0, 0.0  rx=85.5 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:1950026339] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-10 13:34:01.574  1031  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-10 13:34:01.587  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-10 13:34:01.604  1031  1540 V WifiInternetCheck: Single check msg out of sync, ignoring.
,08-10 13:34:01.625  1031  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-10 13:34:01.641  1031  1096 D Tethering: MasterInitialState.processMessage what=3
08-10 13:34:01.668  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 13:34:01.668  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 13:34:01.668  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 13:34:01.668  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 13:34:01.668  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 13:34:01.668  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 13:34:01.668  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 13:34:01.668  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-10 13:34:01.674  6729  6729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-10 13:34:01.679  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 13:34:01.679  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 13:34:01.679  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 13:34:01.679  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 13:34:01.679  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 13:34:01.679  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 13:34:01.679  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 13:34:01.679  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-10 13:34:01.680  6729  6729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-10 13:34:01.683  1031  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-10 13:34:01.694  5771  5771 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,08-10 13:34:01.702  8196  8196 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-10 13:34:01.722  1031  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-10 13:34:01.740  8196  8254 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-10 13:34:01.756  2193  2193 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-10 13:34:01.773  1031  1774 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 102]) by 10005
,08-10 13:34:01.775  1031  8231 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-2ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-10 13:34:01.775  1031  8231 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-10 13:34:01.775  1031  8231 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-10 13:34:01.775  1031  8231 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-10 13:34:01.776   306  8321 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-10 13:34:01.777   306  8321 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
08-10 13:34:01.776  1031  8231 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
,08-10 13:34:01.806  7060  7060 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-10 13:34:01.806  7060  7060 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,08-10 13:34:01.806  7060  7060 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-10 13:34:01.806  7060  7060 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-10 13:34:01.809  7060  7060 I AppUp4:CustModeStarterReceiver: onReceive
08-10 13:34:01.814  7060  7060 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@866a964
08-10 13:34:01.814  7060  7060 D AppUp4:CustFacade: isCustomizationCompleted : false
08-10 13:34:01.814  7060  7060 D AppUp4:CustFacade: isPhone : true
08-10 13:34:01.814  7060  7060 D AppUp4:CustModeStarterReceiver: begin check event
08-10 13:34:01.815  7060  7060 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-10 13:34:01.816   306  8321 D libc-netbsd: res_queryN name = mtalk.google.com succeed
08-10 13:34:01.819  4325  4325 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,08-10 13:34:01.820  4325  4325 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-10 13:34:01.821  4325  4325 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-10 13:34:01.826  4325  4325 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-10 13:34:01.830  3538  3538 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
08-10 13:34:01.830  4325  8337 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-10 13:34:01.831  1031  8231 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 10 Aug 2016 11:34:01 GMT], X-Android-Received-Millis=[1470828841830], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1470828841798]}
08-10 13:34:01.831  1031  8231 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
,08-10 13:34:01.831  1031  8231 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-10 13:34:01.831  1031  1545 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
08-10 13:34:01.831  1031  1545 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-10 13:34:01.831  1031  1545 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-10 13:34:01.831  1031  1545 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-10 13:34:01.831  1031  1545 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-10 13:34:01.831  1031  1545 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-10 13:34:01.831  1031  1545 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-10 13:34:01.831  1031  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 13:34:01.831  1031  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-10 13:34:01.833  1031  1545 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-10 13:34:01.833  3538  3538 V DownloadManager: DownloadService onCreate
,08-10 13:34:01.836  4325  8338 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-10 13:34:01.836  4325  8338 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-10 13:34:01.837  4325  8337 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
08-10 13:34:01.842  1605  2072 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-10 13:34:01.844  3538  8339 I DownloadManager: in removeSpuriousFiles
08-10 13:34:01.844  3538  8339 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
08-10 13:34:01.847  3538  8339 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@1bc9f360 on behalf of 3538
,08-10 13:34:01.848  3538  8339 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
08-10 13:34:01.848  3538  8339 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
08-10 13:34:01.848  3538  8339 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
08-10 13:34:01.849  3538  8339 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
08-10 13:34:01.849  3538  8339 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
08-10 13:34:01.849  3538  8339 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
08-10 13:34:01.849  3538  8339 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
08-10 13:34:01.849  3538  8339 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
08-10 13:34:01.849  3538  8339 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
08-10 13:34:01.849  3538  8339 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
08-10 13:34:01.849  3538  8339 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
08-10 13:34:01.851  3538  8339 I DownloadManager: in trimDatabase
08-10 13:34:01.851  3538  8339 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
08-10 13:34:01.852  6729  8342 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
08-10 13:34:01.853  6729  8250 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
08-10 13:34:01.853  6729  8342 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-10 13:34:01.853  6729  8250 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-10 13:34:01.853  6729  8250 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-10 13:34:01.855  6729  8342 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-10 13:34:01.856  6729  8250 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-10 13:34:01.857  6729  8344 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 861, name: OutgoingSocketThread/Sender)
08-10 13:34:01.858  3538  8339 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@39641019 on behalf of 3538
,08-10 13:34:01.872  6729  8342 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-10 13:34:01.873  6729  8250 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
08-10 13:34:01.873  6729  8342 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
08-10 13:34:01.874  6729  8352 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 863, name: OutgoingSocketThread/Receiver)
08-10 13:34:01.874  6729  8352 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 863, thread name: OutgoingSocketThread/Receiver)
08-10 13:34:01.874  6729  8352 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-10 13:34:01.875  6729  8352 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 863, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,08-10 13:34:01.877  1031  2373 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=8345 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
08-10 13:34:01.880  6729  8351 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 862, name: IncomingSocketThread/Sender)
08-10 13:34:01.881  3538  3538 V DownloadManager: DownloadService onStartCommand
,08-10 13:34:01.882  6729  8353 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 864, name: IncomingSocketThread/Receiver)
08-10 13:34:01.883  6729  8353 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 864, thread name: IncomingSocketThread/Receiver)
08-10 13:34:01.883  6729  8353 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-10 13:34:01.883  6729  8353 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 864, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
08-10 13:34:01.884  3538  8340 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
08-10 13:34:01.886  4325  8337 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
08-10 13:34:01.890  4325  4325 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
08-10 13:34:01.889  3538  8340 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@3167babf on behalf of 3538
,08-10 13:34:01.890  4325  4325 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
08-10 13:34:01.891  4325  4325 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
08-10 13:34:01.893  4325  4325 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
08-10 13:34:01.894  3538  8340 V DownloadManager: processing inserted download 1
08-10 13:34:01.895  4325  4325 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
08-10 13:34:01.896  3538  8340 V DownloadManager: processing inserted download 4
08-10 13:34:01.898  3538  8340 V DownloadManager: processing inserted download 7
08-10 13:34:01.899  3538  8340 V DownloadManager: processing inserted download 8
08-10 13:34:01.900  3538  8340 V DownloadManager: processing inserted download 9
08-10 13:34:01.901  3538  8340 V DownloadManager: processing inserted download 10
08-10 13:34:01.902  3538  8340 V DownloadManager: processing inserted download 11
,08-10 13:34:01.903  3538  8340 V DownloadManager: processing inserted download 12
08-10 13:34:01.904  3538  8340 V DownloadManager: processing inserted download 13
08-10 13:34:01.905  3538  8340 V DownloadManager: processing inserted download 14
08-10 13:34:01.906  3538  8340 V DownloadManager: processing inserted download 16
08-10 13:34:01.908  3538  3538 V DownloadManager: DownloadService onDestroy
08-10 13:34:01.931  8345  8345 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-10 13:34:01.931  8345  8345 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-10 13:34:01.933  8345  8345 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-10 13:34:01.933  8345  8345 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-10 13:34:01.998  8345  8345 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-10 13:34:02.010  8345  8345 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
08-10 13:34:02.073  8345  8345 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-10 13:34:02.109  8345  8345 D LgDataFeature: LgDataFeature() Constructor: none
,08-10 13:34:02.109  8345  8345 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-10 13:34:02.268  8345  8345 D eas_req : ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-10 13:34:02.327  8345  8345 I HubEmail: JNI_OnLoad()
08-10 13:34:02.327  8345  8345 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-10 13:34:02.327  8345  8345 I HubEmail: registerNatives()
08-10 13:34:02.327  8345  8345 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-10 13:34:02.327  8345  8345 I HubEmail: registerNativeMethods()
08-10 13:34:02.327  8345  8345 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-10 13:34:02.328  8345  8345 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,08-10 13:34:02.340  8345  8380 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-10 13:34:02.362  3485  3485 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-10 13:34:02.362  3485  3485 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-10 13:34:02.363  3485  3485 I LgeMiscReceiver: networkInfo.isConnected() = true
08-10 13:34:02.363  3485  3485 D PhoneState: setPdpRejectCasuse : false
,08-10 13:34:02.392   306  8383 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-10 13:34:02.394   306  8383 D libc-netbsd: res_queryN name = static-avc.lglime.com, class = 1, type = 1
08-10 13:34:02.404  1031  1578 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=8389 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-10 13:34:02.459   306  8383 D libc-netbsd: res_queryN name = static-avc.lglime.com succeed
,08-10 13:34:02.503  8147  8379 V FormManager: There are no updated forms. The schedule will be deleted.
,08-10 13:34:02.510  8147  8379 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
08-10 13:34:02.529  8389  8389 D LgDataFeature: LgDataFeature() Constructor: none
08-10 13:34:02.529  8389  8389 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-10 13:34:02.535  8389  8389 D PhoneMonitor: Register our PhoneStateListener
08-10 13:34:02.547  1031  2035 I ActivityManager: Killing 7708:com.google.android.talk/u0a72 (adj 15): empty #17
,08-10 13:34:02.654  1031  1773 W libprocessgroup: failed to open /acct/uid_10072/pid_7708/cgroup.procs: No such file or directory
,08-10 13:34:02.669  8389  8389 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-10 13:34:02.676  8389  8389 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-10 13:34:02.707  8389  8389 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
08-10 13:34:02.709  8389  8389 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-10 13:34:02.710  8389  8389 D TelephonyAutoProfiling: [parse] Load xml
08-10 13:34:02.716  8389  8389 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
,08-10 13:34:02.716  8389  8389 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-10 13:34:02.716  8389  8389 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-10 13:34:02.716  8389  8389 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-10 13:34:02.716  8389  8389 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-10 13:34:02.717  8389  8389 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-10 13:34:02.717  8389  8389 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-10 13:34:02.717  8389  8389 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-10 13:34:02.717  8389  8389 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-10 13:34:02.717  8389  8389 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-10 13:34:02.717  8389  8389 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-10 13:34:02.717  8389  8389 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-10 13:34:02.717  8389  8389 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-10 13:34:02.717  8389  8389 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-10 13:34:02.717  8389  8389 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-10 13:34:02.718  8389  8389 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-10 13:34:02.718  8389  8389 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
08-10 13:34:02.725  8389  8389 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-10 13:34:02.759  1031  2016 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=8415 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-10 13:34:02.760  1031  2016 I ActivityManager: Killing 7757:com.android.contacts/u0a19 (adj 15): empty #17
08-10 13:34:02.818   306  8432 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-10 13:34:02.818   306  8432 D libc-netbsd: res_queryN name = www.google.com, class = 1, type = 1
,08-10 13:34:02.849  1031  1578 W libprocessgroup: failed to open /acct/uid_10019/pid_7757/cgroup.procs: No such file or directory
,08-10 13:34:02.852   306  8432 D libc-netbsd: res_queryN name = www.google.com succeed
08-10 13:34:02.864   306  8434 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-10 13:34:02.865   306  8434 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-10 13:34:02.865   306  8434 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-10 13:34:02.885  1821  8435 I CheckinService: active receiver: disabled
08-10 13:34:02.926  1031  1541 V WifiInternetCheck: isHttpConnectionAvailable - We got a valid response : 204
,08-10 13:34:03.067  1031  1890 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=8437 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
08-10 13:34:03.069  1031  1890 I ActivityManager: Killing 7780:com.android.gallery3d/u0a27 (adj 15): empty #17
08-10 13:34:03.164  1031  1046 W libprocessgroup: failed to open /acct/uid_10027/pid_7780/cgroup.procs: No such file or directory
,08-10 13:34:03.289  1031  1926 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=8457 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-10 13:34:03.290  1031  1926 I ActivityManager: Killing 7802:com.android.vending/u0a44 (adj 15): empty #17
08-10 13:34:03.353  1031  1773 W libprocessgroup: failed to open /acct/uid_10044/pid_7802/cgroup.procs: No such file or directory
,08-10 13:34:03.392  8457  8457 I art     : Almond Protected OAT
,08-10 13:34:03.451  8457  8457 D WeatherApplication: removeAccount
,08-10 13:34:03.453  8457  8457 D WeatherApplication: Account.length = 0
,08-10 13:34:03.454  8457  8457 E WeatherApplication: OPERATOR:OPEN
,08-10 13:34:03.466  8457  8457 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:34:3
,08-10 13:34:03.473  8457  8457 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,08-10 13:34:03.473  8457  8457 D Weather.Utils: 2 : All the weather widget is gone.
,08-10 13:34:03.476  8457  8457 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-10 13:34:03.479  8457  8457 D WeatherAncestor: connectivity changed - connection : true
08-10 13:34:03.480  8457  8457 D WeatherService: 2 : isServiceAlived():false forecastCache:null
08-10 13:34:03.492  8457  8457 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-10 13:34:03.492  8457  8457 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-10 13:34:03.493  8457  8457 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
,08-10 13:34:03.515  8457  8457 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
,08-10 13:34:03.515  8457  8457 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:34:3
,08-10 13:34:03.594  1031  2006 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=8478 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-10 13:34:03.602  1031  2006 I ActivityManager: Killing 7841:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
08-10 13:34:03.653  1031  1944 W libprocessgroup: failed to open /acct/uid_10080/pid_7841/cgroup.procs: No such file or directory
,08-10 13:34:03.783   278   404 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-10 13:34:03.783   278   404 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-10 13:34:03.783   278   404 W Vold    : Returning OperationFailed - no handler for errno 0
,08-10 13:34:03.788  8478  8496 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-10 13:34:03.794   278   404 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-10 13:34:03.794   278   404 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-10 13:34:03.794   278   404 W Vold    : Returning OperationFailed - no handler for errno 0
08-10 13:34:03.794  8478  8496 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-10 13:34:03.802   278   404 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-10 13:34:03.802   278   404 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-10 13:34:03.802   278   404 W Vold    : Returning OperationFailed - no handler for errno 0
08-10 13:34:03.803  8478  8500 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,08-10 13:34:03.808   278   404 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-10 13:34:03.808   278   404 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-10 13:34:03.808   278   404 W Vold    : Returning OperationFailed - no handler for errno 0
08-10 13:34:03.809  8478  8500 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-10 13:34:04.045  8478  8478 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-10 13:34:04.060  8478  8478 I LibraryLoader: Loading: webviewchromium
08-10 13:34:04.064  8478  8478 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 1277-1281)
08-10 13:34:04.064  8478  8478 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-10 13:34:04.076  8478  8478 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {346860df}
08-10 13:34:04.080  8478  8478 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-10 13:34:04.081  8478  8478 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,08-10 13:34:04.107  8478  8478 I BrowserStartupController: Initializing chromium process, renderers=0
,08-10 13:34:04.108  8478  8478 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-10 13:34:04.123  8478  8478 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-10 13:34:04.125  8478  8478 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
,08-10 13:34:04.126  8478  8478 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-10 13:34:04.133   310  2199 V AudioPolicyService: registerClient() client 0xb00100c0, uid 10093
08-10 13:34:04.134  8478  8520 W AudioManagerAndroid: Requires BLUETOOTH permission
08-10 13:34:04.157  8478  8478 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-10 13:34:04.157  8478  8478 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-10 13:34:04.157  8478  8478 I Adreno-EGL: Build Date: 12/12/14 금
08-10 13:34:04.157  8478  8478 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-10 13:34:04.157  8478  8478 I Adreno-EGL: Remote Branch: 
08-10 13:34:04.157  8478  8478 I Adreno-EGL: Local Patches: 
08-10 13:34:04.157  8478  8478 I Adreno-EGL: Reconstruct Branch: 
,08-10 13:34:04.244  8478  8478 I NSApplication: Starting up...
,08-10 13:34:04.289  1031  2373 I ActivityManager: Killing 7565:com.lge.lifetracker/u0a37 (adj 15): empty #17
,08-10 13:34:04.326  1031  1772 W libprocessgroup: failed to open /acct/uid_10037/pid_7565/cgroup.procs: No such file or directory
,08-10 13:34:04.343  2193  2193 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-10 13:34:04.595  1031  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=51.8, 0.0, 0.0  rx=45.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1950029363] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-10 13:34:04.599  1031  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=51.8, 0.0, 0.0  rx=45.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1950029366] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-10 13:34:04.599  1031  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-10 13:34:04.863  6729  6799 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-10 13:34:04.864  6729  6799 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-10 13:34:04.866  6729  6799 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@66375a6 Bundle[{}]
08-10 13:34:04.867  6729  6799 I io.jxcore.node.LifeCycleMonitor: start: OK
08-10 13:34:04.867  6729  6799 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-10 13:34:04.868  6729  6799 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-10 13:34:04.868  6729  6799 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-10 13:34:04.869  6729  6799 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-10 13:34:04.870  6729  6799 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-10 13:34:04.881  6729  6799 I System.out: Running OutgoingSocketThread
,08-10 13:34:04.883  6729  8537 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,08-10 13:34:04.883  6729  8537 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-10 13:34:07.625  1031  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=35.9, 0.0, 0.0  rx=30.4 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:1950032393] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-10 13:34:07.628  1031  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=35.9, 0.0, 0.0  rx=30.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1950032396] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-10 13:34:07.629  1031  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-10 13:34:07.893  6729  8537 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
08-10 13:34:07.893  6729  8537 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-10 13:34:07.894  6729  8537 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-10 13:34:07.894  6729  8537 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-10 13:34:07.894  6729  8537 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,08-10 13:34:07.898  6729  8538 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
08-10 13:34:07.898  6729  8538 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-10 13:34:07.899  6729  8538 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-10 13:34:07.899  6729  8538 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-10 13:34:07.899  6729  8538 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
08-10 13:34:07.902  6729  8541 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 874, name: OutgoingSocketThread/Receiver)
08-10 13:34:07.903  6729  8541 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 874, thread name: OutgoingSocketThread/Receiver)
08-10 13:34:07.903  6729  8541 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-10 13:34:07.903  6729  8541 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 874, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
08-10 13:34:07.905  6729  8542 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 875, name: IncomingSocketThread/Sender)
08-10 13:34:07.906  6729  8543 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 876, name: IncomingSocketThread/Receiver)
08-10 13:34:07.906  6729  8543 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 876, thread name: IncomingSocketThread/Receiver)
08-10 13:34:07.907  6729  8543 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-10 13:34:07.907  6729  8543 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 876, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
08-10 13:34:07.909  6729  8540 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 873, name: OutgoingSocketThread/Sender)
,08-10 13:34:08.817  8478  8498 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,08-10 13:34:10.655  1031  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=17.9, 0.0, 0.0  rx=15.2 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:1950035422] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-10 13:34:10.658  1031  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=17.9, 0.0, 0.0  rx=15.2 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:1950035426] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-10 13:34:10.658  1031  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-10 13:34:10.900  6729  6799 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 885)
,08-10 13:34:10.907  6729  6799 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-10 13:34:10.907  6729  6799 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 886)
08-10 13:34:10.910  6729  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-10 13:34:10.911  6729  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@398014d9 added. We now have 3 listener(s)
08-10 13:34:10.911  1031  1772 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 13:34:10.914  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-10 13:34:10.914  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-10 13:34:10.914  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-10 13:34:10.914  6729  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 13:34:10.915  6729  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ab92e9e added. We now have 4 listener(s)
08-10 13:34:10.915  6729  6799 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 13:34:10.915  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-10 13:34:10.923  6729  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 13:34:10.927  6729  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 13:34:10.927  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 13:34:10.927  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 13:34:10.927  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 13:34:10.927  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 13:34:10.927  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 13:34:10.927  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 13:34:10.927  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-10 13:34:10.929  6729  6799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-10 13:34:10.929  6729  6799 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-10 13:34:10.934  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 13:34:10.936  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 13:34:10.937  6729  6799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 13:34:10.937  6729  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 13:34:10.937  6729  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 13:34:10.937  6729  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 13:34:10.937  6729  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 13:34:10.938  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-10 13:34:10.938  6729  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-10 13:34:10.938  6729  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@398014d9 removed from the list
08-10 13:34:10.938  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 13:34:10.938  6729  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ab92e9e removed from the list
08-10 13:34:10.938  6729  6799 D io.jxcore.node.ConnectivityMonitor: stop
08-10 13:34:10.938  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 13:34:10.939  6729  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 13:34:10.939  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 13:34:10.940  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 13:34:10.940  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 13:34:10.940  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 13:34:10.940  6729  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ab92e9e not in the list
08-10 13:34:10.940  6729  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 13:34:10.940  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 13:34:10.941  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 13:34:10.941  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 13:34:10.941  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 13:34:10.941  6729  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ab92e9e not in the list
08-10 13:34:10.941  6729  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 13:34:10.941  6729  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 13:34:10.941  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: relea,se: 2 listener(s) left
08-10 13:34:10.941  6729  6799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@398014d9 not in the list
,08-10 13:34:10.949  6729  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-10 13:34:10.949  6729  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bd7414c added. We now have 3 listener(s)
08-10 13:34:10.950  1031  1908 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 13:34:10.953  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-10 13:34:10.953  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-10 13:34:10.953  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-10 13:34:10.953  6729  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 13:34:10.953  6729  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d542595 added. We now have 4 listener(s)
08-10 13:34:10.953  6729  6799 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 13:34:10.954  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-10 13:34:10.957  6729  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-10 13:34:10.963  6729  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 13:34:10.963  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 13:34:10.963  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 13:34:10.963  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 13:34:10.963  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 13:34:10.963  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 13:34:10.963  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 13:34:10.963  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-10 13:34:10.966  6729  6799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-10 13:34:10.966  6729  6799 D io.jxcore.node.ConnectivityMonitor: start: OK
08-10 13:34:10.968  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 13:34:10.970  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 13:34:10.971  6729  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-10 13:34:10.971  6729  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-10 13:34:10.972  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-10 13:34:10.972  6729  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 13:34:10.972  6729  6799 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-10 13:34:10.976  6729  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-10 13:34:10.977  1031  1046 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 13:34:10.981  6729  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-10 13:34:10.984  6729  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-10 13:34:10.986  6729  6799 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-10 13:34:10.986  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-10 13:34:10.988  6729  6799 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-10 13:34:10.989  6729  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 13:34:10.989  6729  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 13:34:10.991  6729  6799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 13:34:10.991  6729  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 13:34:10.991  6729  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 13:34:10.992  6729  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 13:34:10.992  6729  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 13:34:10.992  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-10 13:34:10.992  6729  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-10 13:34:10.992  6729  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bd7414c removed from the list
08-10 13:34:10.992  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 13:34:10.992  6729  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d542595 removed from the list
08-10 13:34:10.992  6729  6799 D io.jxcore.node.ConnectivityMonitor: stop
08-10 13:34:10.992  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 13:34:10.993  6729  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 13:34:10.993  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-10 13:34:10.996  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 13:34:10.996  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 13:34:10.997  6729  6799 D BluetoothLeScanner: could not find callback wrapper
08-10 13:34:10.997  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-10 13:34:10.997  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 13:34:10.997  6729  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d542595 not in the list
08-10 13:34:10.997  6729  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 13:34:10.997  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 13:34:10.998  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 13:34:10.999  6729  6799 D BluetoothLeScanner: could not find callback wrapper
08-10 13:34:10.999  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-10 13:34:10.999  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 13:34:10.999  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 13:34:10.999  6729  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d542595 not in the list
08-10 13:34:10.999  6729  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 13:34:10.999  6729  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 13:34:10.999  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 13:34:10.999  6729  6799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bd7414c not in the list
08-10 13:34:11.000  6729  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-10 13:34:11.000  6729  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f1e8611 added. We now have 3 listener(s)
08-10 13:34:11.002  1031  1772 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 13:34:11.005  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-10 13:34:11.005  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-10 13:34:11.005  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-10 13:34:11.005  6729  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 13:34:11.005  6729  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2efe7376 added. We now have 4 listener(s)
08-10 13:34:11.005  6729  6799 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-10 13:34:11.009  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-10 13:34:11.012  6729  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 13:34:11.016  6729  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 13:34:11.016  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 13:34:11.016  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 13:34:11.016  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 13:34:11.016  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 13:34:11.016  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 13:34:11.016  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 13:34:11.016  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-10 13:34:11.018  6729  6799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-10 13:34:11.018  6729  6799 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-10 13:34:11.022  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 13:34:11.024  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 13:34:11.025  6729  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-10 13:34:11.026  6729  6799 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
08-10 13:34:11.026  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
08-10 13:34:11.028  6729  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-10 13:34:11.028  6729  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
08-10 13:34:11.028  6729  6799 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-10 13:34:11.028  6729  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 13:34:11.030  6729  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-10 13:34:11.030  6729  6799 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,08-10 13:34:11.033  6729  6799 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-10 13:34:11.033  6729  6729 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-10 13:34:11.035  6729  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-10 13:34:11.035  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
08-10 13:34:11.035  6729  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 13:34:11.035  6729  6799 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-10 13:34:11.041  6729  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-10 13:34:11.046  1031  2016 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 13:34:11.063  1031  1908 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-10 13:34:11.071  6729  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-10 13:34:11.073  6729  8546 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-10 13:34:11.073  6729  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-10 13:34:11.074  7941  7958 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=82
08-10 13:34:11.075  6729  8546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
08-10 13:34:11.076  6729  6799 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-10 13:34:11.076  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-10 13:34:11.078  6729  6799 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-10 13:34:11.244  1031  1539 E WifiStateMachine:  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0,
,08-10 13:34:11.245  1031  1539 E WifiStateMachine:  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-10 13:34:11.247  1031  1539 E WifiStateMachine:  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-10 13:34:11.248  1031  1539 E WifiStateMachine:  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-10 13:34:11.249  1031  1539 E WifiStateMachine:  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-10 13:34:11.250  1031  1539 E WifiStateMachine:  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,08-10 13:34:13.681  1031  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=9.5, 0.0, 0.0  rx=7.6 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:1950038448] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-10 13:34:13.691  1031  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=9.5, 0.0, 0.0  rx=7.6 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:1950038459] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-10 13:34:13.691  1031  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-10 13:34:16.079  6729  6799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 13:34:16.079  6729  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 13:34:16.080  6729  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-10 13:34:16.080  6729  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-10 13:34:16.080  6729  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-10 13:34:16.080  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,08-10 13:34:16.093  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-10 13:34:16.093  6729  6799 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-10 13:34:16.094  6729  8546 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-10 13:34:16.094  6729  8546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-10 13:34:16.094  6729  8546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-10 13:34:16.094  6729  6729 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-10 13:34:16.097  6729  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-10 13:34:16.097  6729  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 13:34:16.097  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-10 13:34:16.099  6729  6729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 13:34:16.099  6729  6729 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-10 13:34:16.100  6729  6729 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-10 13:34:16.100  6729  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 13:34:16.100  6729  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 13:34:16.100  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-10 13:34:16.100  6729  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-10 13:34:16.100  6729  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f1e8611 removed from the list
08-10 13:34:16.100  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 13:34:16.100  6729  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2efe7376 removed from the list
08-10 13:34:16.100  6729  6799 D io.jxcore.node.ConnectivityMonitor: stop
08-10 13:34:16.100  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 13:34:16.101  6729  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 13:34:16.101  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 13:34:16.102  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 13:34:16.102  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-10 13:34:16.106  6729  6799 D BluetoothLeScanner: could not find callback wrapper
08-10 13:34:16.106  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-10 13:34:16.107  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 13:34:16.107  6729  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2efe7376 not in the list
08-10 13:34:16.107  6729  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 13:34:16.107  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 13:34:16.109  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 13:34:16.110  6729  6799 D BluetoothLeScanner: could not find callback wrapper
08-10 13:34:16.110  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-10 13:34:16.110  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 13:34:16.110  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 13:34:16.110  6729  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2efe7376 not in the list
08-10 13:34:16.110  6729  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 13:34:16.110  6729  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 13:34:16.110  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 13:34:16.110  6729  6799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f1e8611 not in the list
08-10 13:34:16.111  6729  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-10 13:34:16.111  6729  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19565102 added. We now have 3 listener(s)
08-10 13:34:16.114  1031  1980 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-10 13:34:16.119  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-10 13:34:16.120  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-10 13:34:16.120  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-10 13:34:16.120  6729  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 13:34:16.120  6729  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ffb4a13 added. We now have 4 listener(s)
08-10 13:34:16.120  6729  6799 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 13:34:16.122  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-10 13:34:16.126  6729  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-10 13:34:16.132  6729  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 13:34:16.132  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 13:34:16.132  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 13:34:16.132  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 13:34:16.132  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 13:34:16.132  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 13:34:16.132  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 13:34:16.132  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-10 13:34:16.135  6729  6799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-10 13:34:16.136  6729  6799 D io.jxcore.node.ConnectivityMonitor: start: OK
08-10 13:34:16.138  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 13:34:16.142  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 13:34:16.142  6729  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-10 13:34:16.142  6729  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-10 13:34:16.142  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-10 13:34:16.142  6729  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 13:34:16.142  6729  6799 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-10 13:34:16.146  6729  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-10 13:34:16.147  1031  2006 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 13:34:16.152  6729  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-10 13:34:16.154  6729  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-10 13:34:16.156  6729  6799 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-10 13:34:16.157  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-10 13:34:16.158  6729  6799 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-10 13:34:16.161  6729  6799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 13:34:16.161  6729  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 13:34:16.161  6729  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 13:34:16.162  6729  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 13:34:16.162  6729  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 13:34:16.162  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-10 13:34:16.162  6729  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-10 13:34:16.162  6729  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19565102 removed from the list
08-10 13:34:16.162  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 13:34:16.162  6729  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ffb4a13 removed from the list
08-10 13:34:16.162  6729  6799 D io.jxcore.node.ConnectivityMonitor: stop
08-10 13:34:16.162  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 13:34:16.163  6729  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 13:34:16.163  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-10 13:34:16.167  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 13:34:16.167  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 13:34:16.168  6729  6799 D BluetoothLeScanner: could not find callback wrapper
08-10 13:34:16.168  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-10 13:34:16.168  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 13:34:16.168  6729  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ffb4a13 not in the list
08-10 13:34:16.168  6729  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 13:34:16.168  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 13:34:16.169  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 13:34:16.169  6729  6799 D BluetoothLeScanner: could not find callback wrapper
08-10 13:34:16.169  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-10 13:34:16.169  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 13:34:16.169  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 13:34:16.170  6729  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ffb4a13 not in the list
08-10 13:34:16.170  6729  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 13:34:16.170  6729  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 13:34:16.170  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 13:34:16.170  6729  6799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19565102 not in the list
08-10 13:34:16.171  6729  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-10 13:34:16.171  6729  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2646746f added. We now have 3 listener(s)
08-10 13:34:16.173  1031  1047 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 13:34:16.176  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-10 13:34:16.176  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-10 13:34:16.176  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-10 13:34:16.176  6729  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 13:34:16.176  6729  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@53957c added. We now have 4 listener(s)
08-10 13:34:16.176  6729  6799 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-10 13:34:16.179  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-10 13:34:16.183  6729  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 13:34:16.188  6729  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 13:34:16.188  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 13:34:16.188  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 13:34:16.188  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 13:34:16.188  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 13:34:16.188  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 13:34:16.188  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 13:34:16.188  6729  6799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-10 13:34:16.191  6729  6799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-10 13:34:16.191  6729  6799 D io.jxcore.node.ConnectivityMonitor: start: OK
08-10 13:34:16.193  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 13:34:16.195  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 13:34:16.196  6729  6799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 13:34:16.196  6729  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 13:34:16.197  6729  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 13:34:16.197  6729  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 13:34:16.197  6729  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 13:34:16.197  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-10 13:34:16.197  6729  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-10 13:34:16.197  6729  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2646746f removed from the list
08-10 13:34:16.197  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 13:34:16.197  6729  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@53957c removed from the list
08-10 13:34:16.197  6729  6799 D io.jxcore.node.ConnectivityMonitor: stop
08-10 13:34:16.197  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 13:34:16.198  6729  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 13:34:16.198  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 13:34:16.199  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 13:34:16.199  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 13:34:16.199  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 13:34:16.199  6729  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@53957c not in the list
08-10 13:34:16.199  6729  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 13:34:16.199  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-10 13:34:16.203  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 13:34:16.203  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 13:34:16.203  6729  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 13:34:16.203  6729  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@53957c not in the list
08-10 13:34:16.203  6729  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 13:34:16.203  6729  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 13:34:16.203  6729  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 13:34:16.203  6729  6799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2646746f not in the list
08-10 13:34:16.205  6729  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-10 13:34:16.205  6729  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-10 13:34:16.205  6729  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-10 13:34:16.205  6729  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-10 13:34:16.206  6729  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-10 13:34:16.206  6729  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-10 13:34:16.216  6729  8556 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 895, name: My test thread name)
,08-10 13:34:16.714  1031  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=4.7, 0.0, 0.0  rx=3.8 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:1950041482] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-10 13:34:16.718  1031  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=4.7, 0.0, 0.0  rx=3.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1950041485] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-10 13:34:16.718  1031  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-10 13:34:18.216  6729  6799 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 895
,08-10 13:34:18.216  6729  6799 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 895, name: My test thread name)
,08-10 13:34:18.233  6729  8557 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 896, name: My test thread name)
08-10 13:34:18.233  6729  8557 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 896, thread name: My test thread name)
08-10 13:34:18.233  6729  8557 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 896, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
08-10 13:34:18.238  6729  6799 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-10 13:34:18.248  6729  8558 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 900, name: My test thread name)
08-10 13:34:18.248  6729  8558 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 900, thread name: My test thread name): Test exception.
08-10 13:34:18.248  6729  8558 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 900, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
08-10 13:34:18.252  6729  6799 I jxcore-log: Total number of executed tests:  82
08-10 13:34:18.252  6729  6799 I jxcore-log: 
08-10 13:34:18.252  6729  6799 I jxcore-log: Number of passed tests:  82
08-10 13:34:18.252  6729  6799 I jxcore-log: 
08-10 13:34:18.252  6729  6799 I jxcore-log: Number of failed tests:  0
08-10 13:34:18.252  6729  6799 I jxcore-log: 
08-10 13:34:18.252  6729  6799 I jxcore-log: Number of ignored tests:  0
08-10 13:34:18.252  6729  6799 I jxcore-log: 
08-10 13:34:18.253  6729  6799 I jxcore-log: Total duration:  79550
08-10 13:34:18.253  6729  6799 I jxcore-log: 
08-10 13:34:18.255  6729  6799 I jxcore-log: Unit Test app is loaded
08-10 13:34:18.255  6729  6799 I jxcore-log: 
08-10 13:34:18.276  6729  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 13:34:18.276  6729  6799 I jxcore-log: 
08-10 13:34:18.281  6729  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 13:34:18.281  6729  6799 I jxcore-log: 
,08-10 13:34:18.294  6729  6729 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
08-10 13:34:18.296  6729  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 13:34:18.296  6729  6799 I jxcore-log: 
08-10 13:34:18.297  6729  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 13:34:18.297  6729  6799 I jxcore-log: 
08-10 13:34:18.298  6729  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 13:34:18.298  6729  6799 I jxcore-log: 
08-10 13:34:18.300  6729  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 13:34:18.300  6729  6799 I jxcore-log: 
,08-10 13:34:18.306  6729  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 13:34:18.306  6729  6799 I jxcore-log: 
08-10 13:34:18.308  6729  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 13:34:18.308  6729  6799 I jxcore-log: 
08-10 13:34:18.309  6729  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 13:34:18.309  6729  6799 I jxcore-log: 
08-10 13:34:18.310  6729  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-10 13:34:18.310  6729  6799 I jxcore-log: 
08-10 13:34:18.311  6729  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-10 13:34:18.311  6729  6799 I jxcore-log: 
08-10 13:34:18.314  6729  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-10 13:34:18.314  6729  6799 I jxcore-log: 
08-10 13:34:18.315  6729  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-10 13:34:18.315  6729  6799 I jxcore-log: 
08-10 13:34:18.316  6729  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-10 13:34:18.316  6729  6799 I jxcore-log: 
08-10 13:34:18.317  6729  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-10 13:34:18.317  6729  6799 I jxcore-log: 
08-10 13:34:18.318  6729  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-10 13:34:18.318  6729  6799 I jxcore-log: 
08-10 13:34:18.319  6729  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-10 13:34:18.319  6729  6799 I jxcore-log: 
08-10 13:34:18.320  6729  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 13:34:18.320  6729  6799 I jxcore-log: 
08-10 13:34:18.320  6729  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 13:34:18.320  6729  6799 I jxcore-log: 
08-10 13:34:18.321  6729  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 13:34:18.321  6729  6799 I jxcore-log: 
,08-10 13:34:18.325  6729  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-10 13:34:18.325  6729  6799 I jxcore-log: 
08-10 13:34:18.328  6729  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-10 13:34:18.328  6729  6799 I jxcore-log: 
08-10 13:34:18.328  6729  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-10 13:34:18.328  6729  6799 I jxcore-log: 
08-10 13:34:18.329  6729  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-10 13:34:18.329  6729  6799 I jxcore-log: 
08-10 13:34:18.330  6729  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-10 13:34:18.330  6729  6799 I jxcore-log: 
08-10 13:34:18.331  6729  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-10 13:34:18.331  6729  6799 I jxcore-log: 
08-10 13:34:18.331  6729  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-10 13:34:18.331  6729  6799 I jxcore-log: 
08-10 13:34:18.332  6729  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-10 13:34:18.332  6729  6799 I jxcore-log: 
08-10 13:34:18.333  6729  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-10 13:34:18.333  6729  6799 I jxcore-log: 
08-10 13:34:18.334  6729  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-10 13:34:18.334  6729  6799 I jxcore-log: 
08-10 13:34:18.335  6729  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-10 13:34:18.335  6729  6799 I jxcore-log: 
08-10 13:34:18.335  6729  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-10 13:34:18.335  6729  6799 I jxcore-log: 
08-10 13:34:18.336  6729  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-10 13:34:18.336  6729  6799 I jxcore-log: 
08-10 13:34:18.337  6729  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-10 13:34:18.337  6729  6799 I jxcore-log: 
08-10 13:34:18.338  6729  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 13:34:18.338  6729  6799 I jxcore-log: 
08-10 13:34:18.338  6729  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 13:34:18.338  6729  6799 I jxcore-log: 
08-10 13:34:18.339  6729  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 13:34:18.339  6729  6799 I jxcore-log: 
08-10 13:34:18.340  6729  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on,","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 13:34:18.340  6729  6799 I jxcore-log: 
08-10 13:34:18.341  6729  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 13:34:18.341  6729  6799 I jxcore-log: 
08-10 13:34:18.342  6729  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 13:34:18.342  6729  6799 I jxcore-log: 
08-10 13:34:18.343  6729  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 13:34:18.343  6729  6799 I jxcore-log: 
08-10 13:34:18.344  6729  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 13:34:18.344  6729  6799 I jxcore-log: 
08-10 13:34:18.347  6729  6799 I jxcore-log: My device name is: LGE-LG-D855
08-10 13:34:18.347  6729  6799 I jxcore-log: 
08-10 13:34:18.348  6729  6799 I jxcore-log: WARN testUtils: myNameCallback not set!
08-10 13:34:18.348  6729  6799 I jxcore-log: 
,08-10 13:34:18.376  6729  8556 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 895, name: My test thread name), during the lifetime of the thread the total number of bytes read was 154 and the total number of bytes written 154
,08-10 13:34:19.742  1031  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=2.4, 0.0, 0.0  rx=1.9 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:1950044510] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-10 13:34:19.745  1031  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=2.4, 0.0, 0.0  rx=1.9 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:1950044512] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-10 13:34:19.745  1031  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-10 13:34:20.808  6729  6799 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-10 13:34:20.808  6729  6799 I jxcore-log: 
,08-10 13:34:21.438  6729  6799 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-10 13:34:21.438  6729  6799 I jxcore-log: 
,08-10 13:34:21.465  6729  6799 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-10 13:34:21.465  6729  6799 I jxcore-log: 
,08-10 13:34:22.769  1031  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=1.2, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:1950047537] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-10 13:34:22.777  1031  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=1.2, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1950047540] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-10 13:34:22.777  1031  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-10 13:34:22.788  6729  6799 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-10 13:34:22.788  6729  6799 I jxcore-log: 
,08-10 13:34:23.009  6729  6799 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
08-10 13:34:23.009  6729  6799 I jxcore-log: 
,08-10 13:34:23.016  6729  6799 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js
08-10 13:34:23.016  6729  6799 I jxcore-log: 
,08-10 13:34:23.021  6729  6799 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
08-10 13:34:23.021  6729  6799 I jxcore-log: 
08-10 13:34:23.037  6729  6799 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
08-10 13:34:23.037  6729  6799 I jxcore-log: 
,08-10 13:34:23.042  6729  6799 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
08-10 13:34:23.042  6729  6799 I jxcore-log: 
08-10 13:34:23.693  6729  6799 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
08-10 13:34:23.693  6729  6799 I jxcore-log: 
,08-10 13:34:23.708  6729  6799 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
08-10 13:34:23.708  6729  6799 I jxcore-log: 
,08-10 13:34:23.718  6729  6799 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
08-10 13:34:23.718  6729  6799 I jxcore-log: 
,08-10 13:34:23.725  6729  6799 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
08-10 13:34:23.725  6729  6799 I jxcore-log: 
,08-10 13:34:23.772  6729  6799 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
08-10 13:34:23.772  6729  6799 I jxcore-log: 
,08-10 13:34:23.827  6729  6799 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
08-10 13:34:23.827  6729  6799 I jxcore-log: 
,08-10 13:34:23.834  6729  6799 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
08-10 13:34:23.834  6729  6799 I jxcore-log: 
,08-10 13:34:23.995  6729  6799 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
08-10 13:34:23.995  6729  6799 I jxcore-log: 
,08-10 13:34:24.023  6729  6799 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
08-10 13:34:24.023  6729  6799 I jxcore-log: 
,08-10 13:34:24.029  6729  6799 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
08-10 13:34:24.029  6729  6799 I jxcore-log: 
,08-10 13:34:24.035  6729  6799 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
08-10 13:34:24.035  6729  6799 I jxcore-log: 
08-10 13:34:24.053  6729  6799 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
08-10 13:34:24.053  6729  6799 I jxcore-log: 
,08-10 13:34:24.133  6729  6799 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
08-10 13:34:24.133  6729  6799 I jxcore-log: 
,08-10 13:34:24.147  6729  6799 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
08-10 13:34:24.147  6729  6799 I jxcore-log: 
,08-10 13:34:24.175  6729  6799 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
08-10 13:34:24.175  6729  6799 I jxcore-log: 
,08-10 13:34:24.188  6729  6799 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
08-10 13:34:24.188  6729  6799 I jxcore-log: 
08-10 13:34:24.206  6729  6799 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
08-10 13:34:24.206  6729  6799 I jxcore-log: 
,08-10 13:34:24.240  6729  6799 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
08-10 13:34:24.240  6729  6799 I jxcore-log: 
,08-10 13:34:24.420  6729  6799 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
08-10 13:34:24.420  6729  6799 I jxcore-log: 
,08-10 13:34:24.447  6729  6799 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
08-10 13:34:24.447  6729  6799 I jxcore-log: 
,08-10 13:34:24.456  6729  6799 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
,08-10 13:34:24.457  6729  6799 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
08-10 13:34:24.457  6729  6799 I jxcore-log: 
,08-10 13:34:25.803  1031  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1950050571] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-10 13:34:25.806  1031  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1950050574] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-10 13:34:25.806  1031  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-10 13:34:27.011  1031  1377 V AlarmManager: ELAPSED_WAKEUP set : Alarm{2a6042 type 2 when 407409 com.google.android.gms} when 407409
,08-10 13:34:27.036   306  8577 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-10 13:34:27.039   306  8577 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
08-10 13:34:27.039   306  8577 D libc-netbsd: res_queryN name = mtalk.google.com succeed
,08-10 13:34:27.288  2193  8579 D GCM     : Connected
,08-10 13:34:27.302  2193  8579 D GCM     : Message class com.google.e.a.a.q
,08-10 13:34:28.834  1031  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=4.8, 0.0, 0.0  rx=3.7 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1950053602] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-10 13:34:28.837  1031  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=4.8, 0.0, 0.0  rx=3.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1950053605] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-10 13:34:28.838  1031  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-10 13:34:31.865  1031  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=6.4, 0.0, 0.0  rx=5.9 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1950056633] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-10 13:34:31.868  1031  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=6.4, 0.0, 0.0  rx=5.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1950056636] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-10 13:34:31.868  1031  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-10 13:34:34.891  1031  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=3.2, 0.0, 0.0  rx=2.9 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1950059658] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-10 13:34:34.904  1031  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=3.2, 0.0, 0.0  rx=2.9 bcn=0 [on:0 tx:0 rx:0 period:14] from screen [on:0 period:1950059672] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-10 13:34:34.905  1031  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-10 13:34:37.926  1031  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=1.6, 0.0, 0.0  rx=1.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1950062693] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-10 13:34:37.929  1031  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=1.6, 0.0, 0.0  rx=1.5 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:1950062697] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-10 13:34:37.929  1031  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-10 13:34:38.550  1031  1539 E WifiStateMachine:  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 3 0
,08-10 13:34:38.551  1031  1539 E WifiStateMachine:  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 3 0
,08-10 13:34:38.561  1031  1539 E WifiStateMachine:  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 3 0
,08-10 13:34:38.563  1031  1539 E WifiStateMachine:  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 3 0
08-10 13:34:38.565  1031  1539 E WifiStateMachine:  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 3 0
,08-10 13:34:38.570  1031  1539 E WifiStateMachine:  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 3 0
,08-10 13:34:39.354  6729  6799 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-10 13:34:39.354  6729  6799 I jxcore-log: 
,08-10 13:34:39.680  8580  8580 D AndroidRuntime: 
08-10 13:34:39.680  8580  8580 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-10 13:34:39.687  8580  8580 D AndroidRuntime: CheckJNI is OFF
08-10 13:34:39.811  8580  8580 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-10 13:34:39.973  1031  2016 I art     : Explicit concurrent mark sweep GC freed 95740(4MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 2.695ms total 157.507ms
,08-10 13:34:39.988  1031  1092 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-10 13:34:39.988  1031  1092 I ActivityManager: Killing 6729:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,08-10 13:34:40.051  1031  1908 I WindowState: WIN DEATH: Window{1d002375 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-10 13:34:40.052  1031  1544 D WifiService: Client connection lost with reason: 4
08-10 13:34:40.060  1031  1908 D InputDispatcher: Window went away: Window{1d002375 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-10 13:34:40.235  1031  1092 I ActivityManager:   Force finishing activity ActivityRecord{1cd80076 u0 com.test.thalitest/.MainActivity t6}
,08-10 13:34:40.272   337   361 E GBMv2   : DFP En is all cleared set to be enabled
,08-10 13:34:40.274  1031  1890 W ActivityManager: Spurious death for ProcessRecord{306b4853 6729:com.test.thalitest/u0a118}, curProc for 6729: null
08-10 13:34:40.274  1031  1113 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-10 13:34:40.282  1031  1113 I ActivityManager:   Force finishing activity ActivityRecord{1cd80076 u0 com.test.thalitest/.MainActivity t6 f}
08-10 13:34:40.282  1031  1113 W ActivityManager: Duplicate finish request for ActivityRecord{1cd80076 u0 com.test.thalitest/.MainActivity t6 f}
,08-10 13:34:40.305  2036  2036 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-10 13:34:40.308  2036  2036 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
,08-10 13:34:40.309  1945  3971 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-10 13:34:40.310  1945  3971 D SplitWindowPolicy: topRunningActivity=ActivityInfo{9d20020 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-10 13:34:40.312  2036  2036 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-10 13:34:40.313  2036  2108 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
08-10 13:34:40.314  1945  1960 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-10 13:34:40.317  2036  2036 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
,08-10 13:34:40.318  1909  1909 D ActionManagerService: notifyUserLog: 1000003
08-10 13:34:40.319  3765  4521 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-10 13:34:40.316  1945  1960 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2333fdd9 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
,08-10 13:34:40.336  2036  2036 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-10 13:34:40.337  1605  1605 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-10 13:34:40.341  1998  1998 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-10 13:34:40.341  7941  7941 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-10 13:34:40.341  7941  7941 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-10 13:34:40.341  3765  3765 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-10 13:34:40.355  1031  1390 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-10 13:34:40.365  2514  2687 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-10 13:34:40.392  4638  4638 I art     : Explicit concurrent mark sweep GC freed 8289(473KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 577us total 81.981ms
,08-10 13:34:40.416  2036  2036 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
,08-10 13:34:40.417  1031  1031 D administrator: Handling package changes for user 0
08-10 13:34:40.419  8196  8196 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-10 13:34:40.419  4527  4527 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-10 13:34:40.420  4527  4527 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-10 13:34:40.420  4527  4527 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-10 13:34:40.420  4527  4527 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-10 13:34:40.420  4527  4527 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-10 13:34:40.420  4527  4527 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-10 13:34:40.420  4527  4527 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-10 13:34:40.420  4527  4527 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-10 13:34:40.420  4527  4527 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 13:34:40.420  4527  4527 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-10 13:34:40.420  4527  4527 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-10 13:34:40.420  4527  4527 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-10 13:34:40.421  1031  1773 V SIM_STK : Menu title from STK is T-Mobile
08-10 13:34:40.427  1821  1821 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
,08-10 13:34:40.429  2036  2036 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-10 13:34:40.474  1873  1873 D SplitUIManager: split_name #11 / not available #0
,08-10 13:34:40.477  1031  1774 I ActivityManager: Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=8611 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
08-10 13:34:40.478  1873  1873 D SplitUIService: removed split : 
08-10 13:34:40.481  2036  2036 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-10 13:34:40.482  1909  1909 D ActionManagerService: notifyUserLog: 1000004
08-10 13:34:40.483  1605  1605 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-10 13:34:40.484  3765  4521 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-10 13:34:40.493   341   341 I art     : Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 266us total 15.890ms
08-10 13:34:40.495  3765  3780 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,08-10 13:34:40.500  1031  2035 V SIM_STK : Menu title from STK is T-Mobile
08-10 13:34:40.500  1031  2035 V SIM_STK : Menu title from STK is T-Mobile
08-10 13:34:40.505   341   341 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 227us total 11.946ms
08-10 13:34:40.516   341   341 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 237us total 10.522ms
,08-10 13:34:40.522  2193  2193 I ConfigService: onCreate
08-10 13:34:40.522  2193  2193 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-10 13:34:40.523  2036  2036 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-10 13:34:40.523  2036  2036 I GBoardWebViewUtils: , create_time: 1430832262123
08-10 13:34:40.523  2036  2036 I GBoardWebViewUtils: , expire_time: 0
08-10 13:34:40.523  2036  2036 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-10 13:34:40.523  2036  2036 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-10 13:34:40.523  2036  2036 I GBoardWebViewUtils: , display: false
08-10 13:34:40.523  2036  2036 I GBoardWebViewUtils: , animation: false }
08-10 13:34:40.523  2036  2036 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-10 13:34:40.523  2036  2036 I GBoardWebViewUtils: , create_time: 1430832262287
08-10 13:34:40.523  2036  2036 I GBoardWebViewUtils: , expire_time: 0
08-10 13:34:40.523  2036  2036 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-10 13:34:40.523  2036  2036 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-10 13:34:40.523  2036  2036 I GBoardWebViewUtils: , display: false
08-10 13:34:40.523  2036  2036 I GBoardWebViewUtils: , animation: false }
08-10 13:34:40.523  2036  2036 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1470393742816
08-10 13:34:40.523  2036  2036 I GBoardWebViewUtils: , create_time: 1470393743569
08-10 13:34:40.523  2036  2036 I GBoardWebViewUtils: , expire_time: 0
08-10 13:34:40.523  2036  2036 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide.html?id=guide_1111111111116_1470393742816&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-10 13:34:40.523  2036  2036 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-10 13:34:40.523  2036  2036 I GBoardWebViewUtils: , display: false
08-10 13:34:40.523  2036  2036 I GBoardWebViewUtils: , animation: false }
08-10 13:34:40.527  1873  1873 D SplitUIManager: split_name #11 / not available #0
08-10 13:34:40.527  1873  1873 I SplitUIService: split app #11
,08-10 13:34:40.532  2036  8631 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-10 13:34:40.532  1821  1821 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-10 13:34:40.535  1605  1605 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-10 13:34:40.535  1605  1605 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-10 13:34:40.537  2193  2193 I ConfigService: onBind returning update interface
08-10 13:34:40.538  2193  2193 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-10 13:34:40.538  2193  2193 I ConfigService: onBind returning config service
08-10 13:34:40.545  2193  2193 I ConfigService: onDestroy
08-10 13:34:40.545  2036  2036 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
,08-10 13:34:40.553  1821  8634 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-10 13:34:40.558  1031  2006 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-10 13:34:40.558  7941  7941 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-10 13:34:40.558  7941  7941 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-10 13:34:40.558  7941  7941 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-10 13:34:40.558  7941  7941 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-10 13:34:40.559  7941  7941 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-10 13:34:40.559  7941  7941 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-10 13:34:40.559  7941  7941 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-10 13:34:40.559  7941  7941 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-10 13:34:40.559  7941  7941 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-10 13:34:40.559  7941  7941 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-10 13:34:40.559  7941  7941 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-10 13:34:40.569  8611  8611 I LockScreenSettings: Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
,08-10 13:34:40.579  5980  8639 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
08-10 13:34:40.591  1031  1031 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-10 13:34:40.591  1031  1031 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-10 13:34:40.591  1031  1031 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-10 13:34:40.592  1031  1580 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-10 13:34:40.597  1031  1944 V SIM_STK : Menu title from STK is T-Mobile
08-10 13:34:40.599  1031  1113 I art     : Explicit concurrent mark sweep GC freed 12333(923KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 2.132ms total 276.170ms
08-10 13:34:40.604  7060  7060 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
08-10 13:34:40.606  1821  8641 I PeopleContactsSync: CP2 sync disabled
,08-10 13:34:40.623  2036  2036 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-10 13:34:40.636  1031  1980 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=8643 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,08-10 13:34:40.639  2036  2036 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-10 13:34:40.639  1605  1659 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-10 13:34:40.639  1605  1659 D KeyguardModel: createShortcutInfo...
08-10 13:34:40.639   330   423 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-10 13:34:40.640  3182  8653 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-10 13:34:40.641  1605  1659 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-10 13:34:40.641  1605  1659 D KeyguardModel: createShortcutInfo...
08-10 13:34:40.646  1605  1659 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-10 13:34:40.646  1605  1659 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-10 13:34:40.646  1605  1659 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-10 13:34:40.647  1605  1659 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-10 13:34:40.648  1605  1659 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-10 13:34:40.648  1605  1659 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-10 13:34:40.649  1605  1659 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-10 13:34:40.649  1605  1659 D KeyguardModel: createShortcutInfo...
08-10 13:34:40.649  1821  4777 I Icing   : doRemovePackageData com.test.thalitest
08-10 13:34:40.652  1605  1659 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-10 13:34:40.652  1605  1659 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-10 13:34:40.653  1605  1659 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-10 13:34:40.653  1605  1659 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-10 13:34:40.656  1605  1659 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-10 13:34:40.656  1605  1659 D KeyguardModel: createShortcutInfo...
08-10 13:34:40.659  1605  1659 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-10 13:34:40.659  1605  1659 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-10 13:34:40.659  1605  1659 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-10 13:34:40.659  1605  1659 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-10 13:34:40.661  1605  1659 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-10 13:34:40.661  1605  1659 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-10 13:34:40.662  1605  1659 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-10 13:34:40.662  1605  1659 D KeyguardModel: createShortcutInfo...
08-10 13:34:40.666  1605  1605 D KeyguardModel: handleShortcutListChanged...
08-10 13:34:40.666  1605  1605 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-10 13:34:40.668  1821  8640 W GmsApplication: Using Auth Proxy for data requests.
08-10 13:34:40.674  1605  1659 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-10 13:34:40.674  1605  1659 D KeyguardModel: createShortcutInfo...
08-10 13:34:40.676  1605  1659 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-10 13:34:40.676  1605  1659 D KeyguardModel: createShortcutInfo...
,08-10 13:34:40.677  1605  1659 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-10 13:34:40.677  1605  1659 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-10 13:34:40.678  1605  1659 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-10 13:34:40.678  1605  1659 D KeyguardModel: createShortcutInfo...
08-10 13:34:40.679  1605  1659 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-10 13:34:40.679  1605  1659 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-10 13:34:40.680  1605  1659 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-10 13:34:40.680  1605  1659 D KeyguardModel: createShortcutInfo...
08-10 13:34:40.680  1605  1659 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-10 13:34:40.681  1605  1659 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-10 13:34:40.681  1605  1659 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-10 13:34:40.681  1605  1659 D KeyguardModel: createShortcutInfo...
08-10 13:34:40.710  2193  2211 I art     : Explicit concurrent mark sweep GC freed 8329(545KB) AllocSpace objects, 6(96KB) LOS objects, 52% free, 29MB/61MB, paused 1.541ms total 35.672ms
,08-10 13:34:40.717  1031  1962 I ActivityManager: Killing 7609:com.lge.settings.easy/1000 (adj 15): empty #17
08-10 13:34:40.721  2036  2036 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
08-10 13:34:40.724  2036  2036 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-10 13:34:40.725  2036  2036 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-10 13:34:40.726  2036  2036 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-10 13:34:40.727  2036  2036 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-10 13:34:40.728  2036  2036 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
,08-10 13:34:40.739  8643  8643 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-10 13:34:40.740  8643  8643 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-10 13:34:40.740  8643  8643 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-10 13:34:40.740  8643  8643 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-10 13:34:40.741  8643  8643 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-10 13:34:40.744  2036  2036 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-10 13:34:40.744  2036  2036 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-10 13:34:40.744  2036  2148 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-10 13:34:40.744  2036  2148 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,08-10 13:34:40.757  2036  2036 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-10 13:34:40.758  2036  2036 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-10 13:34:40.758  2036  2036 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-10 13:34:40.765  2036  2036 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-10 13:34:40.767  8580  8580 D AndroidRuntime: Shutting down VM
08-10 13:34:40.772  1605  1605 D KeyguardModel: handleShortcutListChanged...
08-10 13:34:40.772  1605  1605 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,08-10 13:34:40.773  1031  1774 W libprocessgroup: failed to open /acct/uid_1000/pid_7609/cgroup.procs: No such file or directory
08-10 13:34:40.776  2586  2586 D [Concierge]Service: onStartCommand(). Type : 8
08-10 13:34:40.776  1031  1097 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{29f46d5a u0 com.lge.launcher2/.Launcher t5} time:427994
08-10 13:34:40.776  2586  2586 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-10 13:34:40.777  2586  2586 D [Concierge]Service: Update widget ID : 11
08-10 13:34:40.778  2036  2036 D [Concierge]WidgetView: change position of spinner
08-10 13:34:40.779  2036  2036 I [Concierge]WidgetView: initWebView(). Time : 1470828880779
08-10 13:34:40.779  2586  2586 D [Concierge]Service: onStartCommand(). Type : 0
08-10 13:34:40.781  1821  8640 W GmsApplication: Using Auth Proxy for data requests.
08-10 13:34:40.800  2036  2036 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 527958811
08-10 13:34:40.800  2036  2036 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-10 13:34:40.801  2036  2036 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-10 13:34:40.803  2036  2036 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@3e9ae14c
08-10 13:34:40.803  2036  2036 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-10 13:34:40.806  2036  2036 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-10 13:34:40.806  2036  2036 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-10 13:34:40.810  2036  2036 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-10 13:34:40.811  2036  2036 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-10 13:34:40.811  2036  2036 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-10 13:34:40.811  2036  2036 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1470828479981, New one : 1470828880779
08-10 13:34:40.811  2036  2036 D [Concierge]WidgetView: Unregister all receivers
08-10 13:34:40.811  2036  2036 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-10 13:34:40.812  2036  2036 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-10 13:34:40.813  8643  8643 I SystemConfig: BUILD Country: EU
08-10 13:34:40.813  8643  8643 I SystemConfig: BUILD Operator: OPEN
08-10 13:34:40.814  2036  2036 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-10 13:34:40.816  2036  2036 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-10 13:34:40.817  2036  2036 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
,08-10 13:34:40.818  2036  2036 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-10 13:34:40.819  2036  2036 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-10 13:34:40.835  2036  2036 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-10 13:34:40.836  2036  2036 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-10 13:34:40.854  1031  2035 I ActivityManager: Killing 8267:com.lge.bnr/1000 (adj 15): empty #17
,08-10 13:34:40.877  2036  2036 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-10 13:34:40.884  2036  2036 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-10 13:34:40.885  2036  2036 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-10 13:34:40.886  2036  2036 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-10 13:34:40.904  2036  2036 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@dd69454 time:428122
,08-10 13:34:40.951  1031  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1950065719] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-10 13:34:40.952  1031  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1950065720] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-10 13:34:40.952  1031  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-10 13:34:40.956  1031  1908 W libprocessgroup: failed to open /acct/uid_1000/pid_8267/cgroup.procs: No such file or directory
08-10 13:34:40.957  2351  8668 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-10 13:34:40.961  8345  8345 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
08-10 13:34:40.961  1031  1091 W InputMethodInfo: Duplicated subtype definition found: , voice
08-10 13:34:40.961  8643  8666 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-10 13:34:40.961  8643  8666 I SystemConfig: existFile = false
08-10 13:34:40.962  8643  8666 I SystemConfig: canReadFile = false
08-10 13:34:40.962  8643  8666 I SystemConfig: systemFeature RCS result false
08-10 13:34:40.962  8643  8666 D SystemConfig: refreshRcsSupport() :false
08-10 13:34:40.991  1031  1774 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=8669 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-10 13:34:41.012  2036  2036 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-10 13:34:41.023  1031  1113 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8686 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-10 13:34:41.051  8669  8669 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-10 13:34:41.052  8669  8669 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-10 13:34:41.052  8669  8669 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-10 13:34:41.052  8669  8669 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-10 13:34:41.056  2036  2868 I GBoardtInterface: onReloaded()
08-10 13:34:41.058  2036  2036 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-10 13:34:41.059  3765  3780 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,08-10 13:34:41.061  3765  4515 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-10 13:34:41.069  1909  1909 D ActionManagerService: notifyUserLog: 1000001
08-10 13:34:41.070  3765  4521 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
,08-10 13:34:41.071  3765  4521 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-10 13:34:41.074  1031  1980 I ActivityManager: Killing 8170:com.lge.sync/1000 (adj 15): empty #17
08-10 13:34:41.085  1031  1091 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-10 13:34:41.093  1031  1091 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-10 13:34:41.122  1031  1962 W libprocessgroup: failed to open /acct/uid_1000/pid_8170/cgroup.procs: No such file or directory
08-10 13:34:41.122  1909  1909 D ActionManagerService: notifyUserLog: 1000001

```
